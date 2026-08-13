---
title: "Publications"
type: "page"
layout: "standard"
show_title_as_headline: true
---

<div class="pub-search-box mb5">
  <input type="text" id="pub-search" placeholder="Search publications by author, title, journal, or year…" class="input-reset ba pa3 w-100 br2" style="border-color:#C4A77D;">
</div>

<script>
document.addEventListener('DOMContentLoaded', function () {
  var input = document.getElementById('pub-search');
  var container = document.querySelector('.page-content');
  if (!input || !container) return;
  var children = Array.prototype.slice.call(container.children);

  input.addEventListener('input', function () {
    var q = input.value.trim().toLowerCase();
    var lastHeader = null;
    var headerHasMatch = false;

    children.forEach(function (el) {
      if (el.classList && el.classList.contains('pub-search-box')) return;
      if (el.tagName === 'H2') {
        if (lastHeader) lastHeader.style.display = (headerHasMatch || q === '') ? '' : 'none';
        lastHeader = el;
        headerHasMatch = false;
        return;
      }
      var text = el.textContent.toLowerCase();
      var match = q === '' || text.indexOf(q) !== -1;
      el.style.display = match ? '' : 'none';
      if (match) headerHasMatch = true;
    });
    if (lastHeader) lastHeader.style.display = (headerHasMatch || q === '') ? '' : 'none';
  });
});
</script>

## 2026

Yip, T., Lorenzo, K., Woolverton, G. A., Wu, J., Cham, H., Chae, D., & El-Sheikh, M. (2026). Racial Differences in Sleep Outcomes in the First Two Years of College. *Journal of racial and ethnic health disparities,* 10.1007/s40615-026-03091-y. Advance online publication. https://doi.org/10.1007/s40615-026-03091-y

Jelsma, E., Wang, Y., Cham, H., Zhang, Y., Yan, J., Zhao, Z., Alegria, M. & Yip, T. (2026). Everyday ethnic discrimination and early substance use based on hair samples in high-risk racial/ethnic minority early adolescents. *Cultural Diversity and Ethnic Minority Psychology, 32*(2), 257–265. https://doi.org/10.1037/cdp0000732

Wu, J., Dimagiba, E., Zhao, A., Ahmed, M., Yu, X., Yan, J., Zhang, Y., Lorenzo, K., Cham, H. & Yip, T. (2026). Comparing the reliability of sleep metrics across two wrist actigraphs: Philips Actiwatch Spectrum Plus and ActiGraph CentrePoint Insight watch. *Sleep Science and Practice, 77*(4). https://doi.org/10.1186/s41606-026-00188-5

Yip, T., Yan, J., Woolverton, G.A., Wu, J., Johnson, N.C., Zhao, Z., Cham, H., El-Sheikh, M. & Chae, D. (2026). Ethnic-racial Discrimination and Sleep among Black College Students: The Moderating Role of Public Regard. *Social Science & Medicine, 400*, 119221. https://doi.org/10.1016/j.socscimed.2026.119221

Liu, C. H., & Yip, T. (2026). Generative AI in adolescence: A developmental framework. *JAMA Pediatrics, 180*(5), 473–474. https://doi.org/10.1001/jamapediatrics.2026.0032

Yip, T., Lorenzo, K., Zhao, Z., Diaz, J., Wang, L., Cruz-Gonzalez, M., Valentino, K., Park, I., Zhen-Duan, J., Alvarez, K., & Alegría, M. (2026). Daily associations between ethnic and racial discrimination and sleep among Mexican-origin adolescents. *Behavioral Sleep Medicine*. https://doi.org/10.1080/15402002.2026.2620780

Yip, T., Yan, J., Zhang, M. R., Wang, Y., Zhao, Z., Cham, H., & Alegría, M. (2026). School start times and racial disparities in early adolescent sleep. *Sleep Health, 12*(1), 30--38. https://doi.org/10.1016/j.sleh.2025.07.003

Yip, T., Zhao, Z., Wu, J., Yan, J., Zhang, M. R., Lorenzo, K., Ruedas-Gracia, N., Cham, H., Chae, D. H., & El-Sheikh, M. (2026). Discrimination and sleep difficulties among first-year students: Mediation by daily sleep quality. *Health Psychology, 45*(6), 658–668. https://doi.org/10.1037/hea0001575

## 2024-2025

Zhang, M. R., Wang, Y., Zhao, Z., Yan, J., Zhang, Y., Cham, H., Alegría, M., & Yip, T. (2025). Immigrant Status, Socioeconomic Status, and Sleep Disparities in Early Adolescence: Findings From the National Adolescent Brain Cognitive Development Study. *The Journal of adolescent health, 77*(6), 1205–1214. https://doi.org/10.1016/j.jadohealth.2025.08.010

Yan, J., Johnson, N. C., Zhao, Z., Lorenzo, K., Cham, H., Ruedas-Gracia, N., El-Sheikh, M., Chae, D. H., & Yip, T. (2025). Ethnic and racial discrimination and sleep health among Asian American college students. *Sleep Health, 11*(6), 808–815. https://doi.org/10.1016/j.sleh.2025.07.011

Yip, T., Lorenzo, K., Wu, J., Yan, J., Zhao, Z., Cham, H., Chae, D., & El-Sheikh, M. (2025). Racial Disparities in Sleep Among Diverse Young Adults During the First Semester of College. *Journal of Racial and Ethnic Health Disparities*. https://doi.org/10.1007/s40615-025-02592-6

Yip, T., Wang, Y. & Zhao, A. (2025). Promises and Pitfalls of Daily Diary Methods for Understanding Developmental Processes. *Annual Review of Developmental Psychology, 7*:439--60. https://doi.org/10.1146/annurev-devpsych-111323-095203

Zhao, Z., Yan, J., Wang, Y., Liu, C. H., Wang, L., Cham, H., & Yip, T. (2025). Race, ethnicity, sex, sexual orientation, and discrimination in the Adolescent Brain Cognitive Development Study. *JAMA Network Open, 8*(5), e2510799. https://doi.org/10.1001/jamanetworkopen.2025.10799

Yan, J., Xie, M., Zhao, Z., Bae, J., Cham, H. & Yip, T. (2025). Sleep difficulties and adolescent internalizing symptoms: The Moderating role of sleep regularity. *Journal of Sleep Research, 34*(5), e14481. https://doi.org/10.1111/jsr.14481

Yan, J., Xie, M., Zhao, Z., Cham, H., El-Sheikh, M. & Yip, T. (2025). Sleep profiles among ethnically-racially minoritized adolescents: Associations with sociocultural experiences and developmental outcomes. *Journal of Clinical Child and Adolescent Psychology,, 34*(5), e14481. https://doi.org/10.1080/15374416.2025.2475495

Wang, Y., Zhao, Z., Zhang, M., Zhang, Y., Yan, J., Jelsma, E., Cham, H., Alegria, M. & Yip, T. (2025). Sleep as a Protective Factor: Multiple Forms of Discrimination and Substance Use Intention among Racially and Ethnically Minoritized U.S. Youth. *Journal of Adolescent Health, 76*(4), 718–726.  https://doi.org/10.1016/j.jadohealth.2024.12.004

Zhao, Z., Wang, Y., Yan, J. Wang, L., Liu, C., Cham, H. & Yip, T. (2025). Adolescent health and the intersectionality of ethnicity/race, sex, and sexual orientation: A national probability sample from the ABCD Study. *Developmental Psychology, 61*(7), 1264–1274. https://doi.org/10.1037/dev0001912

Chung, K., Lorenzo, K., Chae, D., El-Sheikh, E. & Yip, T. (2024). Impact of daily neighborhood violent crime on nightly sleep among adolescence. *Child Development, 96*(2), 891--900. https://doi.org/10.1111/cdev.14202

Wang, Y., Zhao, Z., Zhang, Y., Yan, J., Zhang, M., Jelsma, E., Johnson, S., Cham, H., Algeria, M. & Yip, T. (2024). Race, ethnicity, and sleep in U.S. children. *JAMA Network Open, 7*(12). https://doi.org/10.1001/jamanetworkopen.2024.49861

Lorenzo, K., Xie, M., Cham, H., El-Sheikh, M., & Yip, T. (2024). Corresponding changes in sleep and discrimination: A three-year longitudinal study among ethnically/racially diverse adolescents. *Journal of Youth and Adolescence, 54*, 368–382. https://doi.org/10.1007/s10964-024-02086-4

Lorenzo, K., Cham, H. & Yip, T. (2024). Longitudinal associations between friendship ethnic/racial composition and ethnic/racial identity: The role of school diversity. *Journal of Youth & Adolescence, 53*, 2534–2550. https://doi.org/10.1007/s10964-024-02041-3

Yan, J., Jelsma, E., Wang, Y., Zhang, Y., Zhao, Z., Cham, H., Alegria, M. & Yip, T. (2024). Racial-ethnic discrimination and early adolescents' behavioral problems: The protective role of parental warmth. *Journal of the American Academy of Child and Adolescent Psychiatry, 64*(2), 249–261. https://doi.org/10.1016/j.jaac.2024.03.020

Park, I. J. K., Wang, L., Li, R., Yip, T., Valentino, K., Cruz-Gonzalez, M., Giraldo-Santiago, N., Lorenzo, K., Zhen-Duan, J., Alvarez, K. & Alegria, M. (2024). A Daily Diary Study of Discrimination and Distress in Mexican-Origin Adolescents: Testing Mediating Mechanisms. *Child Development, 95*(5), 1754–1769. https://doi.org/10.1111/cdev.14108

Valentino, K., Park, I. J. K., Cruz-Gonzalez, M., Zhen-Duan, J., Wang, L., Yip, T., Lorenzo, K., Dias, D., Alvarez, K., & Alegría, M. (2024). Family-level moderators of daily associations between discrimination and distress among Mexican-origin youth. *Development and Psychopathology, 37*(2), 902–917. https://doi.org/10.1017/S0954579424000749

Yip, T., Yan, J., Johnson, S., Bae, J., Lorenzo, K., Ruedas-Gracia, N., & Zhao, Z. (2024). Developmental links between ethnic and racial discrimination and sleep. *Child development perspectives, 18*(4), 172–181. https://doi.org/10.1111/cdep.12513

Yip, T., Lorenzo, K., Bae, J., Hall, G. N., Cheah, C. S. L., Kiang, L., Takeuchi, D., & Tseng, V. (2024). Anti-Asian biases in federal grant reviews: Commentary on Yip et al. (2021). *The American psychologist, 79*(5), 770–776. https://doi.org/10.1037/amp0001337

Wang, Y., Zhang, Y., Zhao, Z., Jelsma, E., Cham, H., Wadsworth, H., Yan, J., Johnson, S., Alegría, M., & Yip, T. (2024). Multiple Discrimination and Substance Use Intention in Late Childhood: Findings From the Adolescent Brain Cognitive Development (ABCD) Study. *The Journal of adolescent health, 74*(6), 1217–1224. https://doi.org/10.1016/j.jadohealth.2024.01.028

Alegría, M., Cruz-Gonzalez, M., Yip, T., Wang, L., Park, I. J. K., Fukuda, M., Valentino, K., Giraldo-Santiago, N., Zhen-Duan, J., Alvarez, K., Barrutia, X. A., & Shrout, P. E. (2024). Yearly and Daily Discrimination-Related Stressors and Mexican Youth's Mental Health and Sleep: Insights From the First Wave of a Three-Wave Family Study. *Journal of the American Academy of Child and Adolescent Psychiatry, 63*(11), 1134–1148. https://doi.org/10.1016/j.jaac.2023.12.010

Lorenzo, K., Gee, G., de Castro, B., Zhao, Z., Yan, J., Hussein, N., & Yip, T. (2024). Everyday Discrimination and Sleep Among Migrant and Non-migrant Filipinos: Longitudinal Analyses from the Health of Philippine Emigrants Study (HoPES). *Journal of immigrant and minority health, 26*(2), 304–315. https://doi.org/10.1007/s10903-023-01554-6

## 2022-2023

Xie, M., Zhao, Z., Yan, J., Cham, H., & Yip, T. (2024). Ethnic/Racial Identity, Adolescent Sleep, and Somatic Health: Discrimination and Stress Responses as Mediating Mechanisms. *The Journal of adolescent health, 74*(3), 514–522. https://doi.org/10.1016/j.jadohealth.2023.09.012

Yip, T., Feng, Y., Lorenzo, K. & El-Sheikh, M. (2022). Ethnic/racial discrimination and academic grades among adolescents: moderation by sleep regularity. *Journal of Sleep Research, 32*(3), e13798. https://doi.org/10.1111/jsr.13798

Yip, T., Wang, Y., Xie, M., Ip, P. S., Fowle, J. & Buckhalt, J. (2022). School start times, sleep, and youth outcomes: A Meta-analysis, *Pediatrics, 149*(6): e2021054068. https://doi.org/10.1542/peds.2021-054068

Yip, T., Xie, M., Cham, H. & El-Sheikh, M. (2022). Linking ethnic/racial discrimination to adolescent mental health: Sleep disturbance as an explanatory pathway, *Child Development, 93*(4), 974-994. https://doi.org/10.1111/cdev.13747

Yip, T., Cham, H., Wang, Y. & Xie, M. (2022). Applying stress and coping models to ethnic/racial identity, discrimination, and adjustment among diverse adolescents, *Developmental Psychology, 58*(1), 176-192. https://doi.org/10.1037/dev0001283

Yip, T., Chung K. & Chae, D. H. (2022). Vicarious racism, ethnic/racial identity and sleep among Asian Americans, *Cultural Diversity and Ethnic Minority Psychology, 30*(2), 319–329. https://doi.org/10.1037/cdp0000534

Fisher, C. B., Tao, X. & Yip, T. (2022). The effects of coronavirus victimization distress and coronavirus racial bias on mental health among Black, Indigenous and Latinx young adults in the United States, *Cultural Diversity and Ethnic Minority Psychology, 29*(2), 119–131. https://doi.org/10.1037/cdp0000539

## 2020-2021

Rogers, L. O., Niwa, E. Y., Chung, K., Yip, T. & Chae, D. (2021). M(ai)cro: Centering the Macrosystem in Human Development. *Human Development, 65*(5-6), 270--292. https://doi.org/10.1159/000519630

Alegria, M., Yip, T., Marks, A., Juang, L., Cohen, L. & Cuervo-Torello, F. (2021). Editorial: Improving Mental Health for Immigrant Populations. *Frontiers in Psychiatry,* 12:785137, <https://doi.org/10.3389/fpsyt.2021.785137>

El-Sheikh, M., Zeringue, M., Saini, E., Fuller-Rowell, T. & Yip, T. (2021). Discrimination and adjustment in adolescence: The moderating role of sleep. *Sleep,* <https://doi.org/10.1093/sleep/zsab215>

Yip, T., Feng, Y., Fowle, J. & Fisher, C. B. (2021). Sleep disparities during the COVID-19 pandemic: An Investigation of AIAN, Asian, Black, Latinx and White young adults. *Sleep Health,* 7(4), 459-467.

Hyun, S., Wong, G. T. F., Levy-Carrick, N. C., Charmaraman, L., Cozier, Y., Yip, T., Hahm, H. & Liu, C. H. (2021). Psychosocial Correlates of Posttraumatic Growth among U.S. Young Adults During the COVID-19 Pandemic. *Psychiatry Research*, 302, [doi.org/10.1016/j.psychres.2021.114035](https://doi.org/10.1016/j.psychres.2021.114035)

Chae, D.H., Yip, T., Martz, C. D., Chung, K., Richeson, J., Hajat, A., Curtis, D., Rogers, L.O. & LaVeist, T. (2021). Vicarious racism and vigilance during the COVID-19 pandemic: Mental health implications among Asian and Black Americans. *Public Health Reports*, 136(4), 508--517.

Xie, M., Yip, T. Cham, H. & El-Sheikh, M. (2021). The impact of daily discrimination on sleep/wake problem trajectories among diverse adolescents. *Child Development,* 92 (5), e1061-e1074, <http://doi.org/10.1111/cdev.13605>

Xie, M., Fowle, J., Ip, P.S., Haskin, M.* & Yip, T. (2021). Profiles of ethnic-racial identity, socialization, and model minority experiences: Associations with well-being among Asian American adolescents. *Journal of Youth and Adolescence,* 50, 1173-1188, doi:10.1007/s10964-021-01436-w

Yip, T., Cheah, C., Kiang, L., Hall, G. & Comas-Diaz, L. (2021). Rendered Invisible: Are Asian Americans a Model or a Marginalized Minority? *American Psychologist*, 76(4), 575-581. http://dx.doi.org/10.1037/amp0000857

Feng, Y., Cheon, Y., Cham, H & Yip, T. (2021). A Multilevel IRT analysis of two discrimination scales among diverse adolescents and young adults. *Psychological Assessment,* 33(7), 637

Yip, T., Smith, P., Tynes, M., Mirpuri, S., Weems, A. & Cheon, Y. M. (2021). Discrimination and hair cortisol concentration among Asian, Latinx and White young adults. *Comprehensive Psychoneuroendocrinology*, 6, <https://doi.org/10.1016/j.cpnec.2021.100047>

Yip, T., Chen, M., Wang, Y., Slopen, N. B., Cheon, Y., Chae, D. H., Priest, N. & Williams, D.R. (2021). Linking Sleep and Discrimination with Biomarker Profiles: An Investigation in the MIDUS Study. *Comprehensive Psychoneuroendocrinology*, 5, https://doi.org/10.1016/j.cpnec.2020.100021

Wang, Y. & Yip, T. (2020). Parallel changes in ethnic/racial discrimination and identity in high school. *Journal of Youth and Adolescence,* 49, 1517-1530. https://doi.org/10.1007/s10964-019-01186-w

Yip, T., Cheon, Y., Wang, Y., Deng, W. & Seligson, A.* (2020). Sociodemographic and environmental factors associated with childhood sleep duration. *Sleep Health*, 6, 767-777. https://doi.org/10.1016/j.sleh.2020.05.007

Cheon, Y., Niu, L., Ehrhardt, A. & Yip, T. (2020). Daily academic satisfaction and ethnic/racial identity of Asian American adolescents: The role of objective and subjective peer diversity at school, *Asian American Journal of Psychology*, 11(2), 59-68.

Cheon, Y. M., Ip, P.S., Haskin, M. & Yip, T. (2020). Profiles of adolescent identity development at the intersection of ethnic/racial identity, American identity and subjective social status. *Frontiers in Psychology,* 11: 959. doi:10.3389/fpsyg.2020.00959

Yip, T. & Cheon, Y.M. (2020, e-pub). Sleep, Psychopathology and Cultural Diversity. *Current Opinion in Psychology.* 10.1016/j.copsyc.2020.02.006

Cheon, Y. & Yip, T. (2020, e-pub). Longitudinal associations between ethnic/racial identity and discrimination among Asian and Latinx adolescents. *Journal of Youth and Adolescence.* DOI: 10.1007/s10964-019-01055-6

Yip, T., Cham, H., Wang, Y. & El-Sheikh, M. (2020). Discrimination and sleep mediate ethnic/racial identity and adolescent adjustment: Uncovering change processes with slope-as-mediator mediation. *Child Development,* 91(3), 1021-1043. DOI:10.1111/cdev.13276

Yip, T. Cheon, Y., Wang, Y., Cham, H., Tryon, W. & El-Sheikh, M. (2020). Racial disparities in sleep among ethnic minority adolescents: Daily associations between discrimination and sleep. *Child Development,* 91(3), 914-931. https://doi.org/10.1111/cdev.13234

Yip, T., Cheon, Y. & Ehrhardt, A. (2020). Applying experience-sampling methods to investigate the impact of school diversity on youth development in multicultural contexts. In P. T. Tizmann & P. Jugert (Eds.). *Youth in Superdiverse Societies: Growing Up with Globalization, Diversity, and Acculturation.* (pp. 111-128). Routledge, New York, NY.

Chae, D. H., Wang, Y., Martz, C. D., Slopen, N. B., Yip, T., Adler, N. E., Fuller-Rowell, T. E., Lin, J., Matthews, K. A., Brody, G. H., Spears, E. C., Puterman, E., & Epel, E. S. (2020). Racial discrimination and telomere shortening among African Americans: The Coronary Artery Risk Development in Young Adults (CARDIA) Study. *Health Psychology,* https://doi.org/10.1037/hea0000832

## 2018-2019

Wang, Y. & Yip, T. (2019). Sleep facilitates coping with racial discrimination: Moderated mediation of daily sleep, racial discrimination, coping and adolescent well-being. *Child Development,* <https://doi.org/10.1111/cdev.13324>

Spears Brown, C., Mistry, R. S. & Yip, T. (2019). Moving from the margins to the mainstream: Equity and justice as key considerations for developmental science. *Child Development Perspectives,* doi: 10.1111/cdep.12340

Cheon, Y., Ip, P.S. & Yip, T. (2019). Adolescent profiles of ethnicity/race and socioeconomic status: Implications for sleep and the role of discrimination and ethnic/racial identity. *Advances in Child Development and Behavior,* 57, 195-233, <https://doi.org/10.1016/bs.acdb.2019.04.002>

Mirpuri, S., Ray, C., Hassan, A., Tynes, M., Wang, Y. & Yip, T. (2019). Ethnic/racial identity as a moderator of the relationship between discrimination and adolescent outcomes. In H. E. Fitzgerald, D. J. Johnson, D. B. Qin, F. A. Villarruel & J. Norder (Eds.). *Children and Prejudice*. Praeger Press.

Yip, T., Wang, Y., Mootoo, C. & Mirpuri, S. (2019). Moderating the association between discrimination and adjustment: A Meta-analysis of ethnic/racial identity, *Developmental Psychology,* 55(6), 1274-1298. [http://dx.doi.org/10.1037/dev0000708](https://psycnet.apa.org/doi/10.1037/dev0000708)

Yip, T., Cheon, Y. & Wang, Y. (2019). The diversity paradox: Opportunities and challenges across development. *Research in Human Development*, 16(1), 51-75, https://doi.org/10.1080/15427609.2018.1549404

Yip, T. (2018). Ethnic/racial identity -- A double-edged sword? Associations with discrimination and psychological outcomes. *Current Directions in Psychological Science*, 27(3), 170-175, https://doi.org/10.1177/0963721417739348

Wang, Y., Cham, H., Aladin, M. & Yip, T. (2018). Parental cultural socialization and adolescent private regard: Exploring mediating pathways through daily experiences, *Child Development,* DOI: 10.1111/cdev.12911

Cheon, Y., Douglass, S., Wang, Y. & Yip, T. (2018). The development of ethnic self-labeling among adolescents: Individual differences in school context. *Journal of Youth and Adolescence,* 47 (10), 2261-2278. https://doi.org/10.1007/s10964-018-0843-4

## 2016-2017

Wang, Y., Douglass, S. & Yip T. (2017). Longitudinal relations between ethnic/racial identity process and content: Exploration, commitment, and salience among diverse adolescents, *Developmental Psychology*, 53 (11), 2154-2169.

Dunbar, M., Mirpuri, S*. & Yip, T. (2017). The effects of sleep and ethnic/racial discrimination on academic achievement trajectories across high school. *Cultural Diversity and Ethnic Minority Psychology,* 23 (4), 527-540.

Seaton, E.K., Yip, T. & Douglass, S. (2017). Racial and ethnic discrimination. In R. Levesque (Ed.) *Encyclopedia of Adolescence*. New York: Springer.

Mirpuri, S. & Yip, T. (2017). Intergroup contact and racial/ethnic identity development. In A. Rutland, D. Nesdale & C. Spears Brown (Eds.), *The Wiley-Blackwell Handbook of Group Processes in Children and Adolescents*. (pp. 47-66). Hoboken, NJ: Wiley-Blackwell Press.

Cross, W. E., Seaton, E., Yip, T., Rivas-Drake, D., Gee, G. C., Ngo, B. & Roth, W. (2017). Identity work: Enactment of racial-ethnic identity in everyday life. *Identity,* 17 (1), 1-12.

Douglass, S., Mirpuri, S. & Yip, T. (2017). Considering friends within the context of peers in school for the development of ethnic/racial identity. *Journal of Youth and Adolescence,* 46, 300-316.

Douglass, S., Wang, Y. & Yip, T. (2016). The everyday implications of ethnic-racial identity status: Exploring variability in ethnic-racial identity salience across situations. *Journal of Youth and Adolescence,* 45, 1396-1411.

Yip, T. (2016). To be or not to be: How racial/ethnic stereotypes influence ethnic disidentification and private regard, *Cultural Diversity and Ethnic Minority Psychology,* 22 (1), 38-46.

Killen, M; Rutland, A. & Yip, T. (2016). Equity and Justice in Developmental Science: Discrimination, Social Exclusion, and Intergroup Attitudes. *Child Development,* 87 (5), 1317-1336.

Kiang, L., Tseng, V. & Yip, T. (2016). Placing Asian American child development within historical context. *Child Development,* 87 (4), 995--1013.

Hall, G., Yip, T. & Zarate, M. (2016). On becoming multicultural in a monocultural research world: A conceptual approach to ethnocultural diversity. *American Psychologist,* 71(1), 40-51.

Hall, G., Yip, T. & Zarate, M. (2016). Disciplinary perspectives on multicultural research: Reply to Dvorakova (2016) and Yakushko et al. (2016). *American Psychologist,* 71(9), 892-893.

## 2014-2015

Yip, T. (2015). The Effects of ethnic/racial discrimination and sleep quality on trajectories of depressive symptoms and self-esteem among diverse adolescents. *Journal of Youth and Adolescence,* 44 (2), 419-430.

Chae, D. H.; Wang, Y.; Yip, T.; Douglass, S.; Slopen, N. B.; Lin, J., Epel, E. S., Blackburn, E. H. & Wholley, M. A. (2015). Racial differences in biomarkers of stress and cell aging: Latent transition analysis of 5-year change among patients in the heart and soul study. *Brain, Behavior, and Immunity*, 49, 46.

Douglass, S. & Yip, T. (2015). Adolescent ethnic identity in context: Integrating daily diaries, biannual surveys and school-level data. In A. Umana-Taylor & C. E. Santos (Eds.), *Studying Ethnic Identity: Methodological Advances and Consideration for Future Research* (pp. 203-234). Washington, D.C.: APA Press.

Douglass, S., Mirpuri, S., English, D. & Yip, T. (2015). "They were just making jokes": racial/ethnic teasing and discrimination among adolescent friends. *Cultural Diversity and Ethnic Minority Psychology,* 22 (1), 69-82.

Shelton, J. N., Garcia, R. L., Douglass, S., Yip, T. & Trail, T. (2014). Feeling (mis)understood and intergroup friendships in interracial interactions. *Personality and Social Psychology Bulletin,* 40 (9), 1193-1204.

Douglass, S., Yip, T. & Shelton, J. N. (2014). Intragroup contact and anxiety for ethnic minority adolescents: The influence of ethnic identity and school diversity transitions. *Journal of Youth and Adolescence*, 43(10), 1628-1641.

Umana-Taylor, A. J., Quintana, S. M., Lee, R. M., Cross, W. E., Rivas-Drake, D., Schwartz, S. J., Syed, M., Yip, T., Seaton, E. K. & Study Group on Ethnic and Racial Identity in the 21^st^ Century. (2014). Ethnic and racial identity during adolescence and into young adulthood: An integrated conceptualization. *Child Development,* 85 (1), 21-39.

Rivas-Drake, D., Seaton, E. K., Markstrom, C., Schwartz, S. J., Umana-Taylor, A. J., French, S. E., Syed, M., Yip, T., Lee, R. M. & Study Group on Ethnic and Racial Identity in the 21^st^ Century. (2014). Ethnic and racial identity in adolescence: Implications for psychosocial, academic and health outcomes. *Child Development,* 85 (1), 40-57.

Schwartz, S. J., Syed, M., Yip, T., Knight, G. P., Umana-Taylor, A. J., Rivas-Drake, D., & Study Group on Ethnic and Racial Identity in the 21^st^ Century. (2014). Methodological issues in ethnic and racial identity research: Theoretical prevision, measurement issues and research designs. *Child Development,* 85 (1), 58-76.

Yip, T. (2014). Ethnic identity in everyday life: The influence of identity development status. *Child Development,* 85 (1), 205-219.

## 2012-2013

Yip, T. & Douglass, S. (2013). The application of experience sampling approaches to the study of ethnic identity: New developmental insights and directions. *Child Development Perspectives,* 7 (4), 211-214.

Yip, T., Douglass, S. & Shelton, J. N. (2013). Daily intragroup contact in diverse settings: Implications for Asian Adolescents' ethnic identity. *Child Development*, 84 (4), 1425-1441.

Yip, T., Douglass, S. & Sellers, R. (2013). Ethnic and racial identity. In F. Leong & J. Trimble (Eds.), *APA Handbook of Multicultural Psychology* (Vol. 1, pp. 179-205). Washington, D.C.: APA Press.

Lam, J., Yip, T. & Gee, G. (2012). The physical and mental health effects of immigration, age, and perceived difference in social status among first generation Asian-Americans. *Asian American Journal of Psychology*, 3 (1), 29-43.

## 2010-2011

Seaton, E. K., Yip, T., Morgan-Lopez, A. & Sellers, R. M. (2011). Racial discrimination and racial socialization as predictors of African American adolescents' racial identity development using latent transition analysis. *Developmental Psychology*, 48 (2), 448-458.

Seaton, E.K., Yip, T. & Douglass, S. (2011). Racial and ethnic discrimination. In R. Levesque (Ed.) *Encyclopedia of Adolescence* (Vol. 4, pp. 2287-2294). New York: Springer.

Yip, T. & Douglass, S. (2011). Ethnic identity of Asian American youth: process, context, outcomes. In F. Leong, L. Juang & D. Qin (Eds.), *Asian American and Pacific Islander Children and Mental Health*, Volume 1: Development and Context (pp. 169-192). Greenwood/Praeger Press.

Yip, T. & Douglass, S. (2011). Ethnic/Racial identity and peer relationships across elementary, middle and high school. In X. Chen & K. H. Rubin (Eds.), *Socioemotional Development in Cultural Context* (pp. 186-207). New York, New York: Guilford Press.

Yip, T., Seaton, E. K. & Sellers, R. M. (2010). Interracial and intraracial contact, school-level diversity, and change in racial identity status among African American adolescents. *Child Development,* 81 (5), 1431-1444.

## 2008-2009

Yip, T. (2009). Simultaneously salient Chinese and American identities: An experience sampling study of self-complexity, context and positive mood among Chinese young adults. *Cultural Diversity and Ethnic Minority Psychology,* 15 (3), 285-294.

Seaton, E. K., Yip, T. & Sellers, R. M. (2009). Racial identity and perceptions of discrimination: A longitudinal analysis. *Child Development,* 80 (2), 406-417.

Seaton, E. K. & Yip, T. (2009). School and neighborhood contexts, perceptions of racial discrimination, and psychological well-being among African American adolescents. *Journal of Youth and Adolescence,* 38(2), 153-163.

Kiang, L., Yip, T. & Fuligni, A. J. (2008). Multiple social identities and adjustment in young adults from ethnically diverse backgrounds. *Journal of Research on Adolescence*, 18 (4), 643-670.

Yip, T., Kiang, L. & Fuligni, A. J. (2008). Multiple social identities and reactivity to daily stress among ethnically diverse young adults. *Journal of Research in Personality*, 42, 1160-1172.

Cole, E. R. & Yip, T. (2008). Using outgroup comfort to predict Black students' college experiences. *Cultural Diversity and Ethnic Minority Psychology,* 14 (1), 57-66.

Yip, T. (2008). Everyday experiences of ethnic and racial identity among adolescents and young adults. In S. M. Quintana & C. McKown (Eds.), *The Handbook of Race, Racism, and the Developing Child* (pp. 182-202). Hoboken, New Jersey: John Wiley and Sons.

Yip, T., Gee, G. C. & Takeuchi, D. (2008). Racial discrimination and psychological distress: The impact of ethnic identity and age among immigrant and United States-born Asian adults. *Developmental Psychology*, 44 (3), 787-800.

## 2006-2007

Gee, G. C., Spencer, M., Chen, J, Yip, T. & Takeuchi, D. (2007). The association between perceived discrimination and DSM-IV mental health disorders: A nationally representative study of Asian and Pacific Islander Americans. *Social Science and Medicine*, 64 (10), 1984-1996.

Cranford, J. A., Shrout, P. E., Iida, M., Rafaeli, E., Yip, T. & Bolger, N. (2006). Ensuring sensitivity to process and change: The case of mood measures in diary studies. *Personality and Social Psychology Bulletin*, 32 (7), 917-929.

Kiang, L., Yip, T., Fuligni, A. J., Gonzales-Backen, M. & Witkow, M. (2006). Ethnic identity and daily psychological well-being of adolescents from Mexican and Chinese backgrounds. *Child Development*, 77, 1338-1350.

Yip, T., Seaton, E. K. & Sellers, R. M. (2006). African American racial identity across the lifespan: A cluster analysis of identity status, identity content and depression among adolescents, emerging adults and adults. *Child Development*, 77, 1504-1517.

## 2002-2005

Yip, T. (2005). Sources of situational variation in ethnic identity and psychological well-being: A Palm Pilot study of Chinese American students. *Personality and Social Psychology Bulletin*, 31 (2), 1603-1616.

Shelton, J.N., Yip, T., Eccles, J., Chatman, C. M., Fuligni, A. J. & Wong, C. (2005). Ethnic identity as a buffer in psychological adjustment. In G. Downey, J. Eccles & C. M. Chatman (Eds.), *Navigating the Future: Social Identity, Coping and Life Tasks* (pp. 96-115). New York, NY: Russell Sage Foundation.

Yip, T. & Cross, W. E. (2004). A daily diary study of mental health and community involvement for three Chinese American social identities. *Cultural Diversity and Ethnic Minority Psychology,* 10 (4), 394-408.

Yip, T. & Fuligni, A. J. (2002). Daily variation in ethnic identity, ethnic behaviors, and psychological well-being among American adolescents of Chinese descent. *Child Development*, 73 (5), 1557-1572.

Fuligni, A. J., Yip, T. & Tseng, V. (2002). The impact of family obligations on the daily activities and psychological well-being of Chinese American adolescents. *Child Development*, 73 (1), 302-314.
