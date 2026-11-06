---
title: Pediatric Vaccine Study
parent: Projects
nav_order: 1 # order in ToC
---


<!-- only 1 TOC
<div class="my-right-toc" markdown="1">
Table of Contents
{: .text-delta }

1. TOC
{:toc}
</div> -->



# {{page.title}}
Table of Contents
{: .text-delta }
1. TOC
{:toc}



---

## Overview
While vaccination is known to be effective in reducing influenza-related morbidity in school-age children it is not currently recommended in Hong Kong because few infections in this age group above 2 years result in significant morbidity or mortality. Also, the supply of vaccines is limited and indirect costs of vaccination are high.

However, evidence from randomized trials, observational studies and modeling studies has accumulated which suggests that the vaccination of school-age children can provide substantial indirect benefits to the rest of the community, particularly to older adults who are most at risk for the complications associated with influenza. This approach to vaccination is known as the "transmission-limiting" strategy, in contrast to the current "morbidity-limiting" approach where those individuals at highest risk of complications are targeted to receive the vaccine.

While the indirect benefits of vaccinating school-age children against influenza have been extensively studied at the community level, relatively few studies have investigated whether vaccination of school-age children can lead to indirect benefits at the household level, to the parents or siblings of vaccinees.

In 2008-09 (pilot) and 2009-10 (main study) we conducted a double-blind randomized controlled trial of households in Hong Kong, where one child aged 6-17 from each household was randomized to receive either one dose of trivalent inactivated seasonal influenza vaccine, or saline placebo. Each household was followed up for around a year, with serum drawn from each household member before and after the study, and also from some participants during the study. Subjects and household contacts were asked to keep daily symptom diaries, and during episodes of acute respiratory illness in any household member we arranged to collect nose and throat swabs from all household members regardless of illness for laboratory confirmation of influenza infection.

---

## Data

The latest version of the study year 1 (pilot) data (09-2008 to 12-2009) are available to download as a zip file here: [[file]][D1]

This version of the dataset covers the incidence of infections and illnesses in household members, and serologic and virologic laboratory results.

The latest version of the study year 2 (main) data (09-2009 to 12-2010) are available to download as a zip file here: [[file]][D2]

This version of the dataset covers the demographics, incidence of infections and illnesses in household vaccinees, and serologic and virologic laboratory results.

We provide our data under the [Open Data Commons Public Domain Dedication and License][L1], which is a version of open access for data. Under this licence we reserve no rights: there are no restrictions on use of our data, and no requirement to cite our work or this website. However we would anticipate that for academic purposes the standard practice of referencing sources would apply. We would like to hear from researchers who are using our data and we would be keen to work together on analyses.

---

## Pilot findings
The primary findings from the 2008-09 pilot study were published by [Cowling et al. (2010, Clin Infect Dis)][cowling2010]. In brief, the pilot study achieved its aim of confirming the feasibility of the main study design, provided some information about the incidence of influenza infections and illnesses, and provided primary evidence of temporary immunity. We found no evidence of indirect benefits although with only 119 households our pilot study was underpowered to detect even fairly large indirect effects.

Results presented in that manuscript are reproduced in the following scripts which can be run in the free (and increasingly popular) statistical software package R:

* [scripts][ps1] to reformat the raw data (used in some of the other scripts here) and [scripts][ps2] to reformat the raw data and adjust for cross reactivity.
* [Table 1][pT1]; [Table 2][pT2]; [Table 3][pT3]; [Table 4][pT4]; [Table 5][pT5]; [Table 6][pT6]; [Table 7][pT7]; [Table 8][pT8].
* [Figure 1][pF1]; [Figure S1][pFS1]; [Figure S2][pFS2]; [Figure S3][pFS3]; [Figure S4][pFS4].

---

## Transmissibility of influenza in households
We analyzed the final outbreak size distributions of pH1N1, sH1N1, sH3N2 infections identified in paired sera collected from 117 Hong Kong households in April and in August-October 2009. The results were published by [Klick et al. (2011, Epidemiology)][klick2011]. In conclusion, pandemic and seasonal influenza A viruses had similar age-specific transmissibility in a cohort of initially uninfected households, after adjustment for baseline immunity.

Results described in Klick et al. (2011) are reproduced in the following scripts which can be run in R:

* [functions][ptf] of the MCMC procedure (used in some of the other scripts here).
* [Table 1][ptT1]; [Table 2][ptT2]; [eTable 2][ptTS2]; [eTable 3][ptTS3]; [eTable 4][ptTS4]; [eTable 5][ptTS5].
* [Figure 1-3][ptF13].

---

## Increased risk of noninfluenza respiratory virus infections
We randomized 115 children to TIV or placebo group. TIV recipients had an increased risk of noninfluenza respiratory virus infections over the following nine months. While being protected against influenza, TIV recipients may lack of temporary non-specific immunity that protected against other respiratory viruses. The results were published by [Cowling et al. (2012, Clin Infect Dis)][cowling201203].

Results described in the manuscript are reproduced in the following scripts which can be run in R:

* [Table 1][pcT1]; [Table 2][pcT2]; [Table 3][pcT3]; [Appendix Table 1][pcTS1].
* [Figure 1][pcF1]; [Appendix Figure 1][pcFS1].

---

## Main findings
The primary findings from the 2009-10 main study were published by [Cowling et al. (2012, Clin Infect Dis)][cowling201206]. In the main study, we recruited 796 children as well as their household members. Pandemic A(H1N1) circulated at the time of vaccination and for a short time afterward with no substantial seasonal influenza activity during that period. We found that seasonal TIV prevented pandemic influenza A(H1N1) and influenza B infections in children.

Results described in the manuscript are reproduced in the following scripts which can be run in R:

* [scripts][ms] to reformat the raw data (used in some of the other scripts here).
* [Table 1][mT1]; [Table 2][mT2]; [Table 3][mT3]; [Table S1][mTS1]; [Table S2][mTS2]; [Table S3][mTS3]; [Table S4][mTS4].
* [Figure 2][mF2].

---

## Humoral antibody response after receipt of TIV
Among 119 children recruited in the pilot study, 64 children rejoined the main study and allocation of TIV/placebo in year 2 was independent of allocation in year 1. [Ng et al. (2012, Pediatr Infect Dis J)][ng2012] studied those 64 subjects and suggested that humoral antibody response to TIV may be lower in children receiving repeated vaccination, but receipt of TIV induced seroprotection in most subjects.

Results described in the manuscript are reproduced in the following scripts which can be run in R:

* [scripts][mhs] to reformat the raw data (used in some of the other scripts here).
* [Table 1][mhT1]; [Table 2][mhT2]; [Table 3][mhT3].
* [Figure 1][mhF1].

---

## The effect of age and recent vaccination history on the efficacy of 2009-10 seasonal TIV
There is some evidence that annual vaccination of trivalent inactivated influenza vaccine (TIV) may lead to reduced vaccine immunogenicity but evidence is lacking on whether vaccine efficacy is affected by prior vaccination history. [Ng et al. (2013, PLoS ONE)][ng2013plos] investigated on the 796 children recruited in the main study, whose influenza vaccination history in the two preceding years was recorded. Ng concluded that prior vaccination was associated with lower antibody responses to TIV against seasonal influenza A vaccine viruses, but higher responses to the same lineage of influenza B virus.

Results described in the manuscript are reproduced in the following scripts which can be run in R:

* [scripts][mas] to reformat the raw data (used in some of the other scripts here).
* [Table 2][maT2]; [Table 3][maT3]; [Table S1][maTS1]; [Table S2][maTS2]; [Table S3][maTS3]; [Table S4][maTS4].
* [Figure 1][maF1]; [Figure S2][maFS2].

---

## The association between antibody titers and protection against influenza
Antibody titers measured by hemagglutination inhibition (HAI) correlate with protection against influenza virus infection and are used to specify criteria for vaccine licensure. [Ng et al. (2013, JID)][ng2013jid] investigated on the 773 children recruited in the main study with HAI titers available, and found that HAI titers of 1:40 against A(H1N1)pdm09 and B(Victoria lineage) were associated with 48% and 55% protection against PCR-confirmed infection with each strain.

Results described in the manuscript are reproduced in the following scripts which can be run in R:

* [source 1][mps1]; [source 2][mps2]; [source 3][mps3]; [source 4][mps4]; [source 5][mps5]; [source 6][mps6] (used in some of the other scripts here).
* [Figure 1][mpF1]; [Figure 2][mpF2]; [Appendix Figure 1][mpFS1].
* [Appendix Table 1][mpTS1]; [Appendix Table 2][mpTS2].

---

## Further work
We have a series of further analyses underway using the data from our study. More details will follow later.


## Authors and investigators
The principal investigator of this study is [Ben Cowling][cowlingHKUSPH]. The data were uploaded by [Ben Cowling][cowlingHKUSPH], and the scripts were written by [Ben Cowling][cowlingHKUSPH], Vicky Fang, Brendan Klick, and Sophia Ng.

## A comment on reproducible research
We fully support the [increasing calls][ref1] from the academic community for [epidemiologic analyses to be reproducible][ref2], and [raw data from randomized controlled trials to be published][ref3], as a part of the wider scientific endeavour to replicate results. Another example of this recommendation is in the Good Practice Guide for Quantitative Veterinary Epidemiology. Here we have published the raw anonymised data from our HK vaccination pilot study, and will later release the data from our main study. We have also published scripts which allow the analyses in our published papers to be reproduced.

Thousands of local people have given their time, and their families', as part of their participation in our studies, all in the expectation that our research studies will add to medical and scientific knowledge. Participants should also expect that we will make the best possible use of the information that we have collected about them. It would be difficult to argue that facilitating best use of the data by the research community need not involve releasing raw data.

Publication of anonymised raw data has been approved by our local IRB and funding sources, and participants were advised that anonymised data would be published during the informed consent process. We anticipate that release of the raw data will:

* Promote reproducibility of our results.
* Allow other investigators to conduct their own analyses on our data.
* Allow other investigators to compare our data with theirs, for example to explore similarities and differences between research findings.
* Allow other investigators to prepare and plan for their own studies.

---

## Publications 
1. Cowling BJ, Ng S, Ma ESK, Cheng CKY, Wai W, Fang VJ, Chan KH, Ip DKM, Chiu SS, Peiris JSM, and Leung GM. Protective efficacy of seasonal influenza vaccination against seasonal and pandemic influenza virus infection during 2009 in Hong Kong. Clinical Infectious Diseases, 2010; 51(12):1370-9. [[link]][cowling2010]
1. Klick B, Nishiura H, Ng S, Fang VJ, Leung GM, Peiris JSM, and Cowling BJ. Transmissibility of seasonal and pandemic influenza in a cohort of households in Hong Kong in 2009. Epidemiology, 2011; 22(6):793-6. [[link]][klick2011]
1. Cowling BJ, Fang VJ, Nishiura H, Chan KH, Ng S, Ip DKM, Chiu SS, Leung GM and Peiris JSM. Increased risk of noninfluenza respiratory virus infections associated with receipt of inactivated influenza vaccine. Clinical Infectious Diseases, 2012; 54(12):1778-83. [[link]][cowling201203]
1. Cowling BJ, Ng S, Ma ES, Fang VJ, So HC, Wai W, Cheng KY, Wong JY, Chan KH, Ip DKM, Chiu SS, Peiris JSM, and Leung GM. Protective Efficacy Against Pandemic Influenza of Seasonal Influenza Vaccination in Children in Hong Kong: A Randomized Controlled Trial. Clinical Infectious Diseases, 2012; 55(5):695-702. [[link]][cowling201206]
1. Ng S, Fang VJ, Ip DKM, Chiu SS, Leung GM, Peiris JSM, and Cowling BJ. Humoral Antibody Response after Receipt of Inactivated Seasonal Influenza Vaccinations One Year Apart in Children. The Pediatric Infectious Disease Journal, 2012; 31(9):964-9. [[link]][ng2012]
Ng S, Ip DKM, Fang VJ, Chan KH, Chiu SS, Leung GM, Peiris JSM, and Cowling BJ. The effect of age and recent influenza vaccination history on the immunogenicity and efficacy of 2009-10 seasonal trivalent inactivated influenza vaccination in children. PLoS ONE, 2013; 8(3):e59077. [[link]][ng2013plos]
1. Ng S, Fang VJ, Ip DKM, Chan KH, Leung GM, Peiris JSM, and Cowling BJ. Estimation of the association between antibody titers and protection against confirmed influenza virus infection in children. The Journal of Infectious Diseases, 2013; 208(8):1320-4. [[link]][ng2013jid]



---

## Acknowledgements
The pilot study (2008-09) was funded by the Area of Excellence Scheme of the Hong Kong University Grants Committee (grant no. AoE/M-12/06) and the Research Fund for the Control of Infectious Disease, Food and Health Bureau, Government of the Hong Kong SAR (grant no. PHE-02).

The main study (2009-10) was funded by the Research Fund for the Control of Infectious Disease, Food and Health Bureau, Government of the Hong Kong SAR (grant no. CHP-CE-03).

Further analyses are supported by the Area of Excellence Scheme of the Hong Kong University Grants Committee (grant no. AoE/M-12/06), and the Harvard Center for Communicable Disease Dynamcs from the US National Institutes of Health Models of Infectious Disease Agent Study program (grant no. 1 U54 GM088558).





[D1]: {% link docs/projects/kiddivax/data/KiddivaxPilot.zip %}
[D2]: {% link docs/projects/kiddivax/data/KiddivaxMain.zip %}

[L1]: http://www.opendatacommons.org/odc-public-domain-dedication-and-licence/

[cowlingHKUSPH]: https://sph.hku.hk/en/Biography/Cowling-Benjamin-John

[ref1]: https://doi.org/10.1097/EDE.0b013e318196784a
[ref2]: https://doi.org/10.1093/aje/kwj093
[ref3]: https://doi.org/10.1186/1745-6215-10-17



<!-- Pilot -->
[cowling2010]: http://dx.doi.org/10.1086/657311

[ps1]: {% link docs/projects/kiddivax/script/KiddivaxPilot/dataframe.r %}
[ps2]: {% link docs/projects/kiddivax/script/KiddivaxPilot/dataframe_cross.r %}

[pT1]: {% link docs/projects/kiddivax/script/KiddivaxPilot/Table_1.r %}
[pT2]: {% link docs/projects/kiddivax/script/KiddivaxPilot/Table_2.r %}
[pT3]: {% link docs/projects/kiddivax/script/KiddivaxPilot/Table_3.r %}
[pT4]: {% link docs/projects/kiddivax/script/KiddivaxPilot/Table_4.r %}
[pT5]: {% link docs/projects/kiddivax/script/KiddivaxPilot/Table_5.r %}
[pT6]: {% link docs/projects/kiddivax/script/KiddivaxPilot/Table_6.r %}
[pT7]: {% link docs/projects/kiddivax/script/KiddivaxPilot/Table_7.r %}
[pT8]: {% link docs/projects/kiddivax/script/KiddivaxPilot/Table_8.r %}

[pF1]:  {% link docs/projects/kiddivax/script/KiddivaxPilot/Figure_1.r %}
[pFS1]: {% link docs/projects/kiddivax/script/KiddivaxPilot/Figure_S1.r %}
[pFS2]: {% link docs/projects/kiddivax/script/KiddivaxPilot/Figure_S2.r %}
[pFS3]: {% link docs/projects/kiddivax/script/KiddivaxPilot/Figure_S3.r %}
[pFS4]: {% link docs/projects/kiddivax/script/KiddivaxPilot/Figure_S4.r %}



<!-- Pilot Transmissibility -->
[klick2011]: https://doi.org/10.1097/EDE.0b013e3182302e8e

[ptf]: {% link docs/projects/kiddivax/script/KiddivaxPilot_Transmission/MCMC_function.r %}

[ptT1]:  {% link docs/projects/kiddivax/script/KiddivaxPilot_Transmission/Table_1.r %}
[ptT2]:  {% link docs/projects/kiddivax/script/KiddivaxPilot_Transmission/Table_2.r %}
[ptTS2]: {% link docs/projects/kiddivax/script/KiddivaxPilot_Transmission/eTable_2.r %}
[ptTS3]: {% link docs/projects/kiddivax/script/KiddivaxPilot_Transmission/eTable_3.r %}
[ptTS4]: {% link docs/projects/kiddivax/script/KiddivaxPilot_Transmission/eTable_4.r %}
[ptTS5]: {% link docs/projects/kiddivax/script/KiddivaxPilot_Transmission/eTable_5.r %}

[ptF13]: {% link docs/projects/kiddivax/script/KiddivaxPilot_Transmission/Figure_1to3.r %}



<!-- Pilot respiratory -->
[cowling201203]: https://doi.org/10.1093/cid/cis307

[pcT1]:  {% link docs/projects/kiddivax/script/KiddivaxPilot_CID_respiratory/Table_1.r %}
[pcT2]:  {% link docs/projects/kiddivax/script/KiddivaxPilot_CID_respiratory/Table_2.r %}
[pcT3]:  {% link docs/projects/kiddivax/script/KiddivaxPilot_CID_respiratory/Table_3.r %}
[pcTS1]: {% link docs/projects/kiddivax/script/KiddivaxPilot_CID_respiratory/Appendix_Table_1.r %}

[pcF1]:  {% link docs/projects/kiddivax/script/KiddivaxPilot_CID_respiratory/Figure_1.r %}
[pcFS1]: {% link docs/projects/kiddivax/script/KiddivaxPilot_CID_respiratory/Appendix_Figure_1.r %}




<!-- Main -->
[cowling201206]: https://doi.org/10.1093/cid/cis518

[ms]: {% link docs/projects/kiddivax/script/KiddivaxMain/dataframe.r %}

[mT1]:  {% link docs/projects/kiddivax/script/KiddivaxMain/Table_1.r %}
[mT2]:  {% link docs/projects/kiddivax/script/KiddivaxMain/Table_2.r %}
[mT3]:  {% link docs/projects/kiddivax/script/KiddivaxMain/Table_3.r %}
[mTS1]: {% link docs/projects/kiddivax/script/KiddivaxMain/Table_S1.r %}
[mTS2]: {% link docs/projects/kiddivax/script/KiddivaxMain/Table_S2.r %}
[mTS3]: {% link docs/projects/kiddivax/script/KiddivaxMain/Table_S3.r %}
[mTS4]: {% link docs/projects/kiddivax/script/KiddivaxMain/Table_S4.r %}

[mF2]: {% link docs/projects/kiddivax/script/KiddivaxMain/Figure_2.r %}



<!-- Humoral antibody -->
[ng2012]:https://doi.org/10.1097/INF.0b013e318263280e

[mhs]: {% link docs/projects/kiddivax/script/KiddivaxMain_PIDJ_antibody/dataframe.r %}

[mhT1]: {% link docs/projects/kiddivax/script/KiddivaxMain_PIDJ_antibody/Table_1.r %}
[mhT2]: {% link docs/projects/kiddivax/script/KiddivaxMain_PIDJ_antibody/Table_2.r %}
[mhT3]: {% link docs/projects/kiddivax/script/KiddivaxMain_PIDJ_antibody/Table_3.r %}

[mhF1]: {% link docs/projects/kiddivax/script/KiddivaxMain_PIDJ_antibody/Figure_1.r %}



<!-- Effect of age and vac history -->
[ng2013plos]: https://doi.org/10.1371/journal.pone.0059077

[mas]: {% link docs/projects/kiddivax/script/KiddivaxMain_PLoSONE/dataframe.r %}

[maT2]: {% link docs/projects/kiddivax/script/KiddivaxMain_PLoSONE/Table_2.r %}
[maT3]: {% link docs/projects/kiddivax/script/KiddivaxMain_PLoSONE/Table_3.r %}
[maTS1]: {% link docs/projects/kiddivax/script/KiddivaxMain_PLoSONE/Table_S1.r %}
[maTS2]: {% link docs/projects/kiddivax/script/KiddivaxMain_PLoSONE/Table_S2.r %}
[maTS3]: {% link docs/projects/kiddivax/script/KiddivaxMain_PLoSONE/Table_S3.r %}
[maTS4]: {% link docs/projects/kiddivax/script/KiddivaxMain_PLoSONE/Table_S4.r %}

[maF1]: {% link docs/projects/kiddivax/script/KiddivaxMain_PLoSONE/Figure_1.r %}
[maFS2]: {% link docs/projects/kiddivax/script/KiddivaxMain_PLoSONE/Figure_S2.r %}



<!-- association between antibody titers and protection against influenza -->
[ng2013jid]: https://doi.org/10.1093/infdis/jit372

[mps1]: {% link docs/projects/kiddivax/script/KiddivaxMain_JID_titerprot/source_1.r %}
[mps2]: {% link docs/projects/kiddivax/script/KiddivaxMain_JID_titerprot/source_2.r %}
[mps3]: {% link docs/projects/kiddivax/script/KiddivaxMain_JID_titerprot/source_3.r %}
[mps4]: {% link docs/projects/kiddivax/script/KiddivaxMain_JID_titerprot/source_4.r %}
[mps5]: {% link docs/projects/kiddivax/script/KiddivaxMain_JID_titerprot/source_5.r %}
[mps6]: {% link docs/projects/kiddivax/script/KiddivaxMain_JID_titerprot/source_6.r %}

[mpF1]: {% link docs/projects/kiddivax/script/KiddivaxMain_JID_titerprot/Figure_1.r %}
[mpF2]: {% link docs/projects/kiddivax/script/KiddivaxMain_JID_titerprot/Figure_2.r %}
[mpFS1]: {% link docs/projects/kiddivax/script/KiddivaxMain_JID_titerprot/Appendix_Figure_1.r %}

[mpTS1]: {% link docs/projects/kiddivax/script/KiddivaxMain_JID_titerprot/Appendix_Table_1.r %}
[mpTS2]: {% link docs/projects/kiddivax/script/KiddivaxMain_JID_titerprot/Appendix_Table_2.r %}
