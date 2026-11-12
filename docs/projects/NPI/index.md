---
title: "2009 NPI"
parent: Projects
nav_order: 3
---


# **{{page.title}}**
{: .no_toc }

<details close markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

## Overview

There is a serious deficit in the evidence base on whether non-pharmaceutical interventions can reduce the spread of influenza. We implemented a study of whether face masks and hand hygiene can reduce influenza transmission among Hong Kong household members.

In 2007 (pilot) and 2008 (main study) we recruited subjects presenting to outpatient clinics (in both the private and public sectors across Hong Kong) with influenza-like-illness of <48 hours duration. After influenza was confirmed in an index case by the QuickVue Influenza A+B rapid test, or in some clinics based on a clinical definition alone, the household of the index subject was randomized to 1) control or 2) hand hygiene or 3) hand hygiene plus surgical face masks (the 3rd arm was surgical face masks in the pilot study). We aimed to implement the interventions at an initial home visit within 36 hours of recruitment, and evaluate subsequent infections by self-reported daily symptom diaries and home visits after 3 and 6 days (and additionally after 9 days in the pilot study). Nose and throat swabs were collected from index subjects and all household contacts at each home visit and tested by viral culture and or RT-PCR. The primary outcome measure was laboratory-confirmed influenza infection in a household contact by viral culture (pilot) or RT-PCR (main); the secondary outcome was clinically diagnosed influenza by self-reported symptoms. We evaluated adherence by self-report and by measuring the number of surgical masks used and weighing the amount of soap/hand rub used.

Full details of our study design are available in our [study protocol][protocal].

We are often asked why we chose to recruit index cases presenting with ILI and observe their households for a week (called a 'case-ascertained' design), rather than starting with a cohort of uninfected households and following them over an influenza season. Much greater resources might be required for the latter study, given the low annual attack rate of influenza. A weakness of our chosen study design is the delay between index case symptom onset (or more precisely the onset of index case infectiousness) and application of the intervention, and any intervention effects we observe would likely be attenuated due to this delay. We are actively working on models which can estimate intervention effects allowing for delays.

---

## Data

### Study year 1
{: .no_toc }

The latest version of the NPI study year 1 (pilot) data (Feb-Sep 2007) are available to download as a zip file [here][D1].

This version of the dataset covers the transmission of influenza in households and adherence to interventions, antiviral treatment, quantitative viral loads, and data from recruiting clinics including presenting symptoms and rapid test performance in 2007.

### Study year 2
{: .no_toc }

The latest version of the NPI study year 2 data (Jan-Sep 2008) are available to download as a zip file [here][D2].

This version of the dataset covers the transmission of influenza in households and adherence to interventions, antiviral treatment, quantitative viral loads, and data from recruiting clinics including presenting symptoms and rapid test performance in 2008.

### Study year 3
{: .no_toc }

The latest version of the NPI study year 3 data (Jan-Jun 2009) are available to download as a zip file [here][D3].

This version of the dataset covers the transmission of influenza in households and subject demographics, antiviral treatment, quantitative viral loads, and data from recruiting clinics including presenting symptoms and rapid test performance in 2009.

We provide our data under the [Open Data Commons Public Domain Dedication and License][L1], which is a version of open access for data. Under this licence we reserve no rights: there are no restrictions on use of our data, and no requirement to cite our work or this website. However we would anticipate that for academic purposes the standard practice of referencing sources would apply. We would like to hear from researchers who are using our data and we would be keen to work together on analyses.

---

## Pilot findings
The primary findings from the 2007 pilot study were published by [Cowling et al. (2008, PLoS ONE)][cowling2008_L2]. In brief, the pilot study achieved its aim of confirming the feasibility of the main study design, and provided some information about the secondary attack ratios. We found no evidence of intervention effects although with only 122 households our pilot study was underpowered to detect even fairly large differences between arms, and adherence to the hand hygiene and face mask interventions was variable.

The results presented in the manuscript are reproduced by the R scripts, which can be downloaded [here][pfS1]. <br>
_(require the R package 'gee' and 'ROCR')_

<!-- Results presented in that manuscript are reproduced in the following scripts which can be run in the free (and increasingly popular) statistical software package R:
* [Table 1][pfT1]
* [Table 2][pfT2]
* [Table 3][pfT3] _(requires the R package 'gee')_{: .fs-3 }
* [Figure 1][pfF1]
* [Figure 2][pfF2]
* [Table S1][pfTS1] _(requires the R package 'ROCR')_{: .fs-3 }
* [Figure S1][pfFS1]
* [Other results described in the manuscript text][pfR1] -->

---

## Serial interval
We investigated the clinical onset serial intervals in our pilot study, adjusting for our 'case-ascertained' study design, and our results are published in [Cowling et al. (2009, Epidemiology)][cowling2009_L2]. We used symptom onset times from 14 pairs of infector/infectee in the NPI pilot study to estimate the clinical serial interval of human influenza in households to have mean 3.6 days (95% confidence interval: 2.9, 4.3 days), with standard deviation 1.6 days. This is slightly longer than some previous estimates.

Our finding of a mean serial interval of 3.6 days suggests that the average time from symptom onset in the index case to secondary infection in the household setting may be around 2 days, assuming that the average time from secondary infection to secondary onset (the incubation period) is around 1.5 days ([Moser et al., AJE, 1979][moser1979_L2]). In the context of our NPI study where index cases were recruited within 48 hours of symptom onset, these findings suggest that our NPI study design may lead to an underestimate of the true effectiveness of the interventions because some infections may have occurred prior to recruitment and intervention. Nevertheless, provided that interventions can be applied soon after symptom onset, it is likely that in our NPI study we would be able to observe attenuated efficacies, and this should be taken into consideration when interpreting the results.

The results presented in the manuscript are reproduced by the R scripts, which can be downloaded [here][siS1]. <br>
_(require the R package 'R2WinBUGS')_

<!-- Results described in Cowling et al. (2009, Epidemiology) are reproduced in the following scripts which can be run in R:

* [functions][siR1] to calculate the non-parametric and parametric estimates of the serial interval (used in some of the other scripts here)
* [Figure 1][siF1]
* [Figure 2][siF2]
* [Appendix Table 1][siTS1] which produces the dataset [serial_appendix_table_1.csv][siD1] used in some of the other scripts here.
* [Appendix Table 2][siTS2]
* [Appendix Figure 1][siFS1]
* [Appendix Table 3 and Appendix Figure 2][siWin] <br />
_(downloadable zip file with WinBUGS scripts - these require the R package R2WinBUGS and a bit of effort setting up WinBUGS to run in R - instructions available [here][siL1])_{: .fs-3 } -->


---

## Rapid test sensitivity
We examined the performance of the QuickVue Influenza A+B rapid test, which we used in our study to screen subjects. The results are published in [Cheng et al. (2009, Diagnostic Microbiology and Infectious Disease)][cheng20098_L2]. We studied the sensitivity and specificity of the rapid test versus viral culture as the gold standard. We found moderate overall sensitivity of around 68% and high specificity of around 96%.

We also tested a subset of specimens by quantitative RT-PCR and found that test sensitivity increases with viral load. We also found that viral loads were higher in children and sooner after illness onset.

The results presented in the manuscript are reproduced by the R scripts, which can be downloaded [here][rtS1].

<!-- Results described in Cheng et al. (2009) are reproduced in the following scripts which can be run in R:
* [functions][rtR1] to calculate sensitivity, specificity,and 95% confidence intervel (used in some of the other scripts here)
* [scripts][rtR2] to reformat the raw data (used in some of the other scripts here)
* [Table 1][rtT1]
* [Table 2][rtT2]
* [Figure 2][rtF2]
* [Appendix Table A][rtTS1]
* [Appendix Figure 1][rtFS1]
* [Other results described in the manuscript text][rtR3] -->


---

## Main results
The primary findings from our main study in 2008 have been published in [Cowling et al. (2009, Annals of Internal Medicine)][cowling09aim_L2]. Our results suggested that hand hygiene and facemasks could prevent a substantial proportion of household transmission of influenza virus when implemented within 36 hours of illness onset in the index case.

The results presented in the manuscript are reproduced by the R scripts, which can be downloaded [here][mrS1]. <br>
_(require the R package 'gee' and 'Hmisc')_

<!-- Results described in Cowling et al. (2009) are reproduced in the following scripts which can be run in R:

* [scripts][mrR1] to mark the analyzed households (used in some of the other scripts here).
* [Table 2][mrT2]
* [Table 3][mrT3]
* [Table 4][mrT4] _(requires the R package 'gee')_{: .fs-3 }
* [Table 5][mrT5] _(requires the R package 'gee')_{: .fs-3 }
* [Table 6][mrT6]
* [Figure 1][mrF1]
* [Appendix Table 1][mrTS1]
* [Appendix Table 2][mrTS2]
* [Appendix Table 3][mrTS3]
* [Appendix Table 4][mrTS4]
* [Appendix Table 5][mrTS5]
* [Appendix Table 6][mrTS6] _(requires the R package 'gee')_{: .fs-3 }
* [Appendix Table 7][mrTS7] _(requires the R package 'gee')_{: .fs-3 }
* [Appendix Table 8][mrTS8] _(requires the R packages 'Hmisc' and 'gee')_{: .fs-3 }
* [Appendix Table 9][mrTS9] _(requires the R packages 'Hmisc' and 'gee')_{: .fs-3 }
* [Appendix Table 10][mrTS10]
* [Appendix Figure 1][mrFS1]
* [Appendix Figure 2][mrFS2] -->


---

## Direct and indirect benefits of oseltamivir treatment
Almost 25% of index cases in our pilot and main studies were prescribed oseltamivir treatment by their treating physician. We studied the effectiveness of oseltamivir treatment in reducing duration of illness and viral shedding, as well as the indirect benefits in reducing transmission to household members. The findings from our study are published in [Ng et al. (2010, CID)][ng2010_L2]. We found that oseltamivir treatment given within 24 hours reduced the duration of illness by around half (statistically significant), and the risk of transmission to household contacts by around half (not statistically significant).

The results presented in the manuscript are reproduced by the R scripts, which can be downloaded [here][diS1]. <br>
_(require the R package 'gee', 'chron' and 'survival')_

<!-- Results described in Ng et al. (2010) are reproduced in the following scripts which can be run in R:
* [scripts][diR1] to reformat the raw data (used in some of the other scripts here).
* [Table 1][diT1]
* [Table 2][diT2] _(requires the R packages 'chron' and 'survival')_{: .fs-3 }
* [Table 3][diT3] _(requires the R packages 'chron' and 'survival')_{: .fs-3 }
* [Table 4][diT4] _(requires the R packages 'chron' and 'gee')_{: .fs-3 }
* [Figure 1][diF1] _(requires the R package 'survival')_{: .fs-3 }
* [Figure 2][diF2] _(requires the R package 'chron')_{: .fs-3 }
* [Appendix Table A1][diTS1]
* [Appendix Table A2][diTS2] _(requires the R packages 'chron' and 'gee')_{: .fs-3 } -->

---

## Viral shedding and clinical illness
In acute influenza virus infections most viral shedding occurs within a few days of illness onset, and the degree of viral shedding correlates with symptoms and tympanic temperature.

The results presented in the manuscript are reproduced by the R scripts, which can be downloaded [here][vsS1]. <br>
_(require the R package 'WinBUGS')_

<!-- Results described in [Lau et al. (2010, JID)][lau2010_L2] are reproduced in the following scripts which can be run in R:

* [scripts][vsR1] to reformat the raw data (used in some of the other scripts here).
* [Table 1][vsT1]
* [Figure 1][vsF1]
* [Figure 2][vsF2]
* [Figure 3][vsF3]<br />
_(downloadable zip file with WinBUGS scripts - these require the R package R2WinBUGS and a bit of effort setting up WinBUGS to run in R - instructions available [here][vsL1])_{: .fs-3 }
* [Appendix Table 1][vsTS1]
* [Appendix Figure 1][vsFS1]
* [Appendix Figure 2][vsFS2] -->



---

## Heterogeneity in viral shedding among seasonal influenza A virus infections
Between January 2008 and August 2009, 637 patients had influenza A virus detected by a rapid test. [Lau et al. (2013, JID)][lau2013_L2] studies these subjects and found that viral shedding in more heterogeneous in children than adults. The top 20% most infectious subjects were estimated to be responsible for 80%-90% of the total infectiousness.

The results presented in the manuscript are reproduced by the R scripts, which can be downloaded here.
{: .d-inline-block }

Coming soon
{: .label .label-yellow }


<!-- Results described in the manuscript are reproduced in the following scripts which can be run in R:
* XXX -->


---

## Modes of transmission of influenza virus in households

### Influenza A
{: .no_toc }

Influenza A viruses are believed to spread between humans through contact, large respiratory droplets and small particle droplet nuclei (aerosols), but the relative importance of each of these modes of transmission is unclear. [Cowling et al. (2013, Nat Comm)][cowling13natcomm_L2] modelled data of 822 subjects recruited from NPI study 2008-2009 to estimate that aerosol transmission accounts for approximately half of all influenza transmission events.

The results presented in the manuscript are reproduced by the R scripts, which can be downloaded [here][mtaS1]. <br>
*Scripts for results presented in Supplementary file will be uploaded soon.

<!-- Results described in the [Cowling et al. (2013, Nat Comm)][cowling13natcomm_L2] are reproduced in the following scripts which can be run in R:

* [scripts][mtaR1] to reformat the raw data (used in some of the other scripts here).
* [Table 1][mtaT1]
* [Figure 1][mtaF1]
* [Figure 2][mtaF2]

*Scripts for results presented in Supplementary file will be uploaded soon. -->

### Influenza B
{: .no_toc }

Continued with the above study on influenza A, we further explore the modes of transmission of influenza B virus based on the same household settings. [Cowling et al. (2014, PLoS One)][cowling14plosone_L2] found aerosol transmission may be an important mode of spread of influenza B virus. The point estimates of aerosol transmission were slightly lower for influenza B virus compared to previously published estimates for influenza A virus in both Hong Kong and Bangkok.

The results presented in the manuscript are reproduced by the R scripts, which can be downloaded [here][mtbS1].

<!-- Results described in the [Cowling et al. (2014, PLoS One)][cowling14plosone_L2] are reproduced in the following scripts which can be run in R:
* [scripts][mtbR1] to reformat the raw data (used in some of the other scripts here).
* [Table 2][mtbT2]
* [Table 4][mtbT4]
* [Figure 1][mtbF1]
* [Figure 2][mtbF2] -->

---

## Further work
{: .no_toc }

We have a series of further analyses underway using the data from our study. More details will follow later.


## Authors and investigators

The principal investigators of this study are Gabriel Leung and [Ben Cowling][cowlingHKUSPH].<br> 
The full list of investigators is given in our study protocol (linked in [section 1](#overview)).<br>
The data were uploaded by [Ben Cowling][cowlingHKUSPH], and the scripts were written by Vicky Fang and [Ben Cowling][cowlingHKUSPH].

## A comment on reproducible research
{: .no_toc }

We fully support the [increasing calls][ref1] from the academic community for [epidemiologic analyses to be reproducible][ref2], and [raw data from randomized controlled trials to be published][ref3], as a part of the wider scientific endeavour to replicate results. Another example of this recommendation is in the Good Practice Guide for Quantitative Veterinary Epidemiology. Here we have published the raw anonymised data from our HK vaccination pilot study, and will later release the data from our main study. We have also published scripts which allow the analyses in our published papers to be reproduced.

Thousands of local people have given their time to answer our questions, in the expectation that our research studies will add to public health knowledge and inform policy makers. Participants are likely to expect that we will make the best possible use of the information that we have collected about them in our studies. It would be difficult to argue that facilitating best use of the data by the research community need not involve releasing raw data.

Publication of anonymised raw data has been approved by our local IRB and funding sources. We anticipate that release of the raw data will:
* Promote reproducibility of our results.
* Allow other investigators to conduct their own analyses on our data.
* Allow other investigators to compare our data with theirs, for example to explore similarities and differences between research findings.
* Allow other investigators to prepare and plan for their own studies.



---

## Publications

1. Cowling BJ, Fung RO, Cheng CK, Fang VJ, Chan KH, Seto WH, Yung R, Chiu B, Lee P, Uyeki TM, Houck PM, Peiris JS, Leung GM. Preliminary findings of a randomized trial of non-pharmaceutical interventions to prevent influenza transmission in households. PLoS ONE, 2008; 3(5):e2101.  <br>
<span class="fs-2"> [DOI][cowling2008_L1]{: .btn .btn-outline .mt-1 .mr-1 } </span>
<span class="fs-2"> [PubMed][cowling2008_L2]{: .btn .btn-outline } </span>

1. Cowling BJ, Fang VJ, Riley S, Peiris JS, Leung GM. Estimation of the serial interval of influenza. Epidemiology, 2009; 20(3):344-7. <br>
<span class="fs-2"> [DOI][cowling2009_L1]{: .btn .btn-outline .mt-1 .mr-1 } </span>
<span class="fs-2"> [PubMed][cowling2009_L2]{: .btn .btn-outline } </span>

1. Cheng KYC, Cowling BJ, Chan KH, Fang VJ, Seto WH, Yung R, Uyeki TM, Houck PM, Peiris JSM, Leung GM. Factors affecting QuickVue Influenza A+B rapid test performance in the community setting. Diagnostic Microbiology and Infectious Disease, 2009; 65(1):35-41. <br>
<span class="fs-2"> [DOI][cheng20098_L1]{: .btn .btn-outline .mt-1 .mr-1 } </span>
<span class="fs-2"> [PubMed][cheng20098_L2]{: .btn .btn-outline } </span>

1. Cowling BJ, Chan KH, Fang VJ, Cheng CKY, Fung ROP, Wai W, Sin J, Seto WH, Yung R, Chu DWS, Chiu BCF, Lee PWY, Chiu MC, Lee HC, Uyeki TM, Houck PM, Peiris JSM, Leung GM. Facemasks and hand hygiene to prevent influenza transmission in households: a randomized trial. Annals of Internal Medicine, 2009; 151(7):437-46. <br>
<span class="fs-2"> [DOI][cowling09aim_L1]{: .btn .btn-outline .mt-1 .mr-1 } </span>
<span class="fs-2"> [PubMed][cowling09aim_L2]{: .btn .btn-outline } </span>

1. Ng S, Cowling BJ, Fang VJ, Chan KH, Ip DKM, Cheng CKY, Uyeki TM, Houck PM, Peiris JSM, Leung GM. Effects of oseltamivir treatment on duration of clinical illness and viral shedding, and household transmission of influenza virus. Clinical Infectious Diseases, 2010; 50(5):707-14. <br>
<span class="fs-2"> [DOI][ng2010_L1]{: .btn .btn-outline .mt-1 .mr-1 } </span>
<span class="fs-2"> [PubMed][ng2010_L2]{: .btn .btn-outline } </span>

1. Lau LLH, Cowling BJ, Fang VJ, Chan KH, Lau EHY, Lipsitch M, Cheng CKY, Mouck PM, Uyeki TM, Peiris JSM, Leung GM. Viral shedding and clinical illness in naturally acquired influenza virus infections. Journal of Infectious Diseases, 2010; 201:1509-16. <br>
<span class="fs-2"> [DOI][lau2010_L1]{: .btn .btn-outline .mt-1 .mr-1 } </span>
<span class="fs-2"> [PubMed][lau2010_L2]{: .btn .btn-outline } </span>

1. Lau LLH, Ip DKM, Nishiura H, Fang VJ, Chan KH, Peiris JSM, Leung GM, Cowling BJ. Heterogeneity in virus shedding among medically-attended influenza A virus infections. Journal of Infectious Diseases, 2013. <br>
<span class="fs-2"> [DOI][lau2013_L1]{: .btn .btn-outline .mt-1 .mr-1 } </span>
<span class="fs-2"> [PubMed][lau2013_L2]{: .btn .btn-outline } </span>

1. Cowling BJ, Ip DK, Fang VJ, Suntarattiwong P, Olsen SJ, Levy J, Uyeki TM, Leung GM, Malik Peiris JS, Chotpitayasunondh T, Nishiura H, Mark Simmerman J. Aerosol transmission is an important mode of influenza A virus spread. Nat Commun. 2013;4:1935. <br>
<span class="fs-2"> [DOI][cowling13natcomm_L1]{: .btn .btn-outline .mt-1 .mr-1 } </span>
<span class="fs-2"> [PubMed][cowling13natcomm_L2]{: .btn .btn-outline } </span>

1. Cowling BJ, Ip DK, Fang VJ, Suntarattiwong P, Olsen SJ, Levy J, Uyeki TM, Leung GM, Peiris JS, Chotpitayasunondh T, Nishiura H, Simmerman JM. Modes of transmission of influenza B virus in households. PLoS One. 2014 Sep 30;9(9):e108850. <br>
<span class="fs-2"> [DOI][cowling14plosone_L1]{: .btn .btn-outline .mt-1 .mr-1 } </span>
<span class="fs-2"> [PubMed][cowling14plosone_L2]{: .btn .btn-outline } </span>
 


---

## Acknowledgements

The NPI study was funded by the US Centers for Disease Control and Prevention (grant no. 1 U01 CI000439-01). The work presented here has also received funding from the Research Fund for the Control of Infectious Disease, Food and Health Bureau, Government of the Hong Kong SAR (grant nos. 08070632, 08070562 and HKU-AA-23), the Area of Excellence Scheme of the Hong Kong University Grants Committee (grant no. AoE/M-12/06), the US National Institutes of Health cooperative agreement (grant no. 5 U01 GM076497), the Harvard Center for Communicable Disease Dynamcs from the US National Institutes of Health Models of Infectious Disease Agent Study program (grant no. 1 U54 GM088558), and the HKU University Research Council Strategic Research Theme of Public Health.





[protocal]: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0002101

[D1]: {% link docs/projects/NPI/data/HongKongNPIpilotV4.zip %}
[D2]: {% link docs/projects/NPI/data/HongKongNPIstudyV4.zip %}
[D3]: {% link docs/projects/NPI/data/HongKongNPIstudy2009V1.zip %}

[L1]: https://opendatacommons.org/licenses/pddl/1-0/



<!-- Pilot finding -->

[cowling2008_L1]: http://doi.org/10.1371/journal.pone.0002101
[cowling2008_L2]: http://www.ncbi.nlm.nih.gov/pubmed/18461182

[pfS1]:  {% link docs/projects/NPI/script/NPIpilot/NPIpilot.zip %}

<!-- [pfT1]:  {% link docs/projects/NPI/script/NPIpilot/Table_1.r %}
[pfT2]:  {% link docs/projects/NPI/script/NPIpilot/Table_2.r %}
[pfT3]:  {% link docs/projects/NPI/script/NPIpilot/Table_3.r %}
[pfF1]:  {% link docs/projects/NPI/script/NPIpilot/Figure_1.r %}
[pfF2]:  {% link docs/projects/NPI/script/NPIpilot/Figure_2.r %}
[pfTS1]: {% link docs/projects/NPI/script/NPIpilot/Table_S1.r %}
[pfFS1]: {% link docs/projects/NPI/script/NPIpilot/Figure_S1.r %}
[pfR1]:  {% link docs/projects/NPI/script/NPIpilot/Text_results.r %} -->



<!-- Serial interval -->

[cowling2009_L1]: http://doi.org/10.1097/EDE.0b013e31819d1092
[cowling2009_L2]: http://www.ncbi.nlm.nih.gov/pubmed/19279492
[moser1979_L2]: http://www.ncbi.nlm.nih.gov/pubmed/463858

[siS1]:  {% link docs/projects/NPI/script/serial_interval/serial_interval.zip %}

<!-- [siR1]:  {% link docs/projects/NPI/script/serial_interval/functions.r %}
[siF1]:  {% link docs/projects/NPI/script/serial_interval/Figure_1.r %}
[siF2]:  {% link docs/projects/NPI/script/serial_interval/Figure_2.r %}
[siTS1]: {% link docs/projects/NPI/script/serial_interval/Appendix_Table_1.r %}
[siD1]:  {% link docs/projects/NPI/script/serial_interval/serial_appendix_table_1.csv %}
[siTS2]: {% link docs/projects/NPI/script/serial_interval/Appendix_Table_2.r %}
[siFS1]: {% link docs/projects/NPI/script/serial_interval/Appendix_Figure_1.r %}

[siWin]: {% link docs/projects/NPI/script/serial_interval/WinBUGs.zip %}
[siL1]: http://www.stat.columbia.edu/~gelman/bugsR/ -->



<!-- Rapid test -->

[cheng20098_L1]: http://doi.org/10.1016/j.diagmicrobio.2009.05.003
[cheng20098_L2]: http://www.ncbi.nlm.nih.gov/pubmed/19679233

[rtS1]: {% link docs/projects/NPI/script/QuickVue/QuickVue.zip %}

<!-- [rtR1]: {% link docs/projects/NPI/script/QuickVue/qv_functions.r %}
[rtR2]: {% link docs/projects/NPI/script/QuickVue/add_groups.r %}
[rtR3]: {% link docs/projects/NPI/script/QuickVue/Text_results.r %}

[rtT1]: {% link docs/projects/NPI/script/QuickVue/Table_1.r %}
[rtT2]: {% link docs/projects/NPI/script/QuickVue/Table_2.r %}
[rtF2]: {% link docs/projects/NPI/script/QuickVue/Figure_2.r %}
[rtTS1]: {% link docs/projects/NPI/script/QuickVue/Appendix_Table_A.r %}
[rtFS1]: {% link docs/projects/NPI/script/QuickVue/Appendix_Figure_1.r %} -->



<!-- Main results -->

[cowling09aim_L1]: https://doi.org/10.7326/0003-4819-151-7-200910060-00142
[cowling09aim_L2]: http://www.ncbi.nlm.nih.gov/pubmed/19652172

[mrS1]: {% link docs/projects/NPI/script/NPImain/NPImain.zip %}

<!-- [mrR1]: {% link docs/projects/NPI/script/NPImain/Analyzed_hh.r %}

[mrT2]: {% link docs/projects/NPI/script/NPImain/Table_2.r %}
[mrT3]: {% link docs/projects/NPI/script/NPImain/Table_3.r %}
[mrT4]: {% link docs/projects/NPI/script/NPImain/Table_4.r %}
[mrT5]: {% link docs/projects/NPI/script/NPImain/Table_5.r %}
[mrT6]: {% link docs/projects/NPI/script/NPImain/Table_6.r %}

[mrF1]: {% link docs/projects/NPI/script/NPImain/Figure_1.r %}

[mrTS1]: {% link docs/projects/NPI/script/NPImain/Appendix_table_1.r %}
[mrTS2]: {% link docs/projects/NPI/script/NPImain/Appendix_table_2.r %}
[mrTS3]: {% link docs/projects/NPI/script/NPImain/Appendix_table_3.r %}
[mrTS4]: {% link docs/projects/NPI/script/NPImain/Appendix_table_4.r %}
[mrTS5]: {% link docs/projects/NPI/script/NPImain/Appendix_table_5.r %}
[mrTS6]: {% link docs/projects/NPI/script/NPImain/Appendix_table_6.r %}
[mrTS7]: {% link docs/projects/NPI/script/NPImain/Appendix_table_7.r %}
[mrTS8]: {% link docs/projects/NPI/script/NPImain/Appendix_table_8.r %}
[mrTS9]: {% link docs/projects/NPI/script/NPImain/Appendix_table_9.r %}
[mrTS10]: {% link docs/projects/NPI/script/NPImain/Appendix_table_10.r %}

[mrFS1]: {% link docs/projects/NPI/script/NPImain/Appendix_figure_1.r %}
[mrFS2]: {% link docs/projects/NPI/script/NPImain/Appendix_figure_2.r %} -->



<!-- Direct and indirect effect -->

[ng2010_L1]: https://doi.org/10.1086/650458
[ng2010_L2]: http://www.ncbi.nlm.nih.gov/pubmed/20121573

[diS1]: {% link docs/projects/NPI/script/Oseltamivir/Oseltamivir.zip %}

<!-- [diR1]: {% link docs/projects/NPI/script/Oseltamivir/dataframe.r %}

[diT1]: {% link docs/projects/NPI/script/Oseltamivir/Table_1.r %}
[diT2]: {% link docs/projects/NPI/script/Oseltamivir/Table_2.r %}
[diT3]: {% link docs/projects/NPI/script/Oseltamivir/Table_3.r %}
[diT4]: {% link docs/projects/NPI/script/Oseltamivir/Table_4.r %}

[diF1]: {% link docs/projects/NPI/script/Oseltamivir/Figure_1.r %}
[diF2]: {% link docs/projects/NPI/script/Oseltamivir/Figure_2.r %}

[diTS1]: {% link docs/projects/NPI/script/Oseltamivir/Appendix_Table_A1.r %}
[diTS2]: {% link docs/projects/NPI/script/Oseltamivir/Appendix_Table_A2.r %} -->



<!-- viral shedding and clinical illness -->

[lau2010_L1]: https://doi.org/10.1086/652241
[lau2010_L2]: http://www.ncbi.nlm.nih.gov/pubmed/20377412

[vsS1]: {% link docs/projects/NPI/script/vshed/vshed.zip %}

<!-- [vsR1]: {% link docs/projects/NPI/script/vshed/JID_dataframe.r %}

[vsT1]: {% link docs/projects/NPI/script/vshed/Table_1.r %}

[vsF1]: {% link docs/projects/NPI/script/vshed/Figure_1.r %}
[vsF2]: {% link docs/projects/NPI/script/vshed/Figure_2.r %}
[vsF3]: {% link docs/projects/NPI/script/vshed/WinBUGS.zip %}

[vsL1]: http://www.stat.columbia.edu/~gelman/bugsR/

[vsTS1]: {% link docs/projects/NPI/script/vshed/Appendix_Table_1.r %}
[vsFS1]: {% link docs/projects/NPI/script/vshed/Appendix_Figure_1.r %}
[vsFS2]: {% link docs/projects/NPI/script/vshed/Appendix_Figure_2.r %} -->



<!-- Heterogeneity in viral shedding -->

[lau2013_L1]: https://doi.org/10.1093/infdis/jit034
[lau2013_L2]: https://pubmed.ncbi.nlm.nih.gov/23382573/



<!-- Modes of transmission  -->

[cowling13natcomm_L1]: https://doi.org/10.1038/ncomms2922
[cowling13natcomm_L2]: https://pubmed.ncbi.nlm.nih.gov/23736803/

[mtaS1]: {% link docs/projects/NPI/script/NPI_NatureComm/NPI_NatureComm.zip %}

<!-- [mtaR1]: {% link docs/projects/NPI/script/NPI_NatureComm/dataframe.r %}
[mtaT1]: {% link docs/projects/NPI/script/NPI_NatureComm/Table_1.r %}
[mtaF1]: {% link docs/projects/NPI/script/NPI_NatureComm/Figure_1.r %}
[mtaF2]: {% link docs/projects/NPI/script/NPI_NatureComm/Figure_2.r %} -->



[cowling14plosone_L1]: https://doi.org/10.1371/journal.pone.0108850
[cowling14plosone_L2]: https://pubmed.ncbi.nlm.nih.gov/25268241/

[mtbS1]: {% link docs/projects/NPI/script/NPI_PLoSOne/NPI_PLoSOne.zip %}

<!-- [mtbR1]: {% link docs/projects/NPI/script/NPI_PLoSOne/dataframe.r %}
[mtbT2]: {% link docs/projects/NPI/script/NPI_PLoSOne/Table_2.r %} 
[mtbT4]: {% link docs/projects/NPI/script/NPI_PLoSOne/Table_4.r %}
[mtbF1]: {% link docs/projects/NPI/script/NPI_PLoSOne/Figure_1.r %}
[mtbF2]: {% link docs/projects/NPI/script/NPI_PLoSOne/Figure_2.r %} -->



<!-- others -->
[cowlingHKUSPH]: https://sph.hku.hk/en/Biography/Cowling-Benjamin-John

[ref1]: https://doi.org/10.1097/EDE.0b013e318196784a
[ref2]: https://doi.org/10.1093/aje/kwj093
[ref3]: https://doi.org/10.1186/1745-6215-10-17

