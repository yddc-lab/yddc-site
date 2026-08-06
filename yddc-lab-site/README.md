# YDDC Lab Website

Source for the Youth Development in Diverse Contexts (YDDC) Lab website, built
with **Hugo** + the **hugo-apero** theme, edited through **R / blogdown**, and
deployed automatically to **GitHub Pages** via GitHub Actions.

Repo: `github.com/yddc-lab/yddc-site` → published at
**https://yddc-lab.github.io/yddc-site/**

---

## 1. One-time setup (do this first)

1. Install R and RStudio if you don't have them: https://posit.co/download/rstudio-desktop/
2. Open `yddc-site.Rproj` in RStudio (double-click it, or File → Open Project).
3. In the R console, install blogdown once:
   ```r
   install.packages("blogdown")
   ```
   You do **not** need to run `blogdown::install_hugo()` — Hugo Extended is
   already vendored for you conceptually; just make sure you have Hugo
   Extended ≥ 0.123 installed locally (blogdown will offer to install it for
   you the first time you run `serve_site()` if it's missing).

That's it — the theme (`themes/hugo-apero`) is already included in this repo
(not a submodule), so there's nothing else to download.

## 2. Preview the site locally

In RStudio, with this project open:

```r
blogdown::serve_site()
```

This builds the site and opens a live preview in the RStudio Viewer / your
browser. Any time you save a file, it rebuilds automatically. Stop it with
`blogdown::stop_server()`.

Prefer the command line? From this folder:

```bash
hugo server
```

## 3. How the content is organized

```
content/
  _index.md              ← homepage hero text
  about/_index.md         ← About the Lab page
  team/
    _index.md             ← Team page intro + Collaborators + Alumni lists
    <person-slug>/index.md ← one file per current team member
    research-opportunities/index.md
    lab-pets/index.md
  project/
    _index.md              ← Projects page intro
    <project-slug>/index.md ← one file per research study
  publications/_index.md   ← full bibliography, organized by year
  resources/_index.md      ← Resources page
  contact/_index.md        ← Contact page
  blog/
    _index.md               ← News & Press listing page
    <post-slug>/index.md     ← one file per news/press item
```

### Adding a new team member

Copy an existing folder, e.g.:

```bash
cp -r content/team/christy-wu content/team/new-person-slug
```

Edit `content/team/new-person-slug/index.md`:

```yaml
---
title: "Full Name"
subtitle: "Their Role"
excerpt: "Their Role"      # shown on the card in the grid
weight: 20                  # controls ordering (lower = earlier)
---

Full bio paragraph goes here.
```

**To add a photo:** drop a headshot into the same folder and name it so it
contains the word `feature` (e.g. `feature.jpg`) — the theme automatically
picks up any image matching `*feature*` in that folder as the person's photo.
None of the original photos were copied over from Wix (they're hosted on
Wix's own CDN), so you'll want to add real photos here.

### Adding a new research project

Same pattern as above, but inside `content/project/`. Look at
`content/project/fuss/index.md` for the full set of fields (`links:` for
buttons like "Study Website", `current_study: true` to feature it on the
homepage, etc.). Only one project should have `current_study: true` at a
time.

### Adding a news/press item

Copy any file in `content/blog/`, e.g.:

```bash
cp -r content/blog/most-white-parents-dont-talk-racism content/blog/my-new-post
```

Set `title`, `date` (YYYY-MM-DD), `excerpt`, and the `links:` URL, then write
a short blurb in the body. Posts are automatically sorted newest-first and
also feed the "Recent News" section on the homepage (top 3).

### Editing Publications

`content/publications/_index.md` is one long Markdown file, organized by year
with `##` headers. Add new citations at the top of the most recent year
section (or start a new `## 2026-2027` section as needed).

### Using R Markdown (.Rmd) instead of .md

If you want a blog post that runs R code (e.g. a plot of study data), you can
add an `.Rmd` file instead of `.md` in `content/blog/` — blogdown will knit it
to Markdown automatically when you run `serve_site()` or `build_site()`. Plain
`.md` files (used everywhere in this site currently) don't need knitting at
all, which keeps the GitHub Actions deploy simple and fast.

## 4. Customizing look & feel

- **Colors:** `config.toml` → `[params] theme = "water"`. Other built-in
  options: earth, forest, grayscale, magma, paper, peach, plum, poppy,
  primer, sky, violet. Full palette reference:
  https://hugo-apero.netlify.app/blog/color-themes/
- **Fonts:** `[params] customtextFontFamily` / `customheadingFontFamily`.
- **Navigation menu:** `[[menu.header]]` blocks in `config.toml`.
- **Logo / favicon:** replace the placeholder files at
  `static/img/yddc-logo.png` and `static/img/favicon.ico` with real ones.
- **Homepage layout:** `layouts/index.html` (site-level override) controls
  the hero + "Current Study" + "Recent News" sections.
- **Team/Projects grid:** `layouts/project/list-grid.html` (site-level
  override) — this is a small tweak to the theme's default so that any text
  you put in `content/team/_index.md` (like the Alumni list) renders below
  the card grid.

## 5. Deploying to GitHub Pages

This repo already includes `.github/workflows/hugo.yml`, which builds the
site with Hugo and deploys it automatically on every push to `main`.

**One-time step in GitHub:** go to
`Settings → Pages → Build and deployment → Source`, and select
**"GitHub Actions"** (not "Deploy from a branch"). After that, every push to
`main` will publish automatically — no manual `hugo` build step needed on
your end.

Your site will be live at: **https://yddc-lab.github.io/yddc-site/**

If you ever rename the repo or move to a custom domain, update `baseURL` at
the top of `config.toml` to match, then push again.

## 6. What changed from the old Wix site

Everything from `yddclab.wixsite.com/yddc` has been migrated: Home, About,
Team (19 current members + Collaborators + Lab Alumni), Research
Opportunities, Lab Pets, Projects (all 9 studies), Publications
(2002–2025), Resources, News & Press (30 items), and Contact.

Two things need your attention:

1. **Photos** — none of the Wix-hosted images were copied over (see "Adding
   a new team member" above for how to add your own).
2. **Nested nav dropdowns** — the old site had "Research Opportunities" and
   "Lab Pets" as a dropdown under "The Team." The new site links to them
   directly from the Team page instead (simpler menu, same content two
   clicks away).
