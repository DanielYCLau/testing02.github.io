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

scripts to reformat the raw data (used in some of the other scripts here) and scripts to reformat the raw data and adjust for cross reactivity.
* [Table 1][T1]; [Table 2][T2]; [Table 3][T3]; [Table 4][T4]; [Table 5][T5]; [Table 6][T6]; [Table 7][T7]; [Table 8][T8].
* [Figure 1][F1]; [Figure S1][FS1]; [Figure S2][FS2]; [Figure S3][FS3]; [Figure S4][FS4].

---

## Transmissibility of influenza in households
We analyzed the final outbreak size distributions of pH1N1, sH1N1, sH3N2 infections identified in paired sera collected from 117 Hong Kong households in April and in August-October 2009. The results were published by [Klick et al. (2011, Epidemiology)][klick2011]. In conclusion, pandemic and seasonal influenza A viruses had similar age-specific transmissibility in a cohort of initially uninfected households, after adjustment for baseline immunity.

Results described in Klick et al. (2011) are reproduced in the following scripts which can be run in R:

functions of the MCMC procedure (used in some of the other scripts here).
* Table 1; Table 2; eTable 2; eTable 3; eTable 4; eTable 5.
* Figure 1-3.

---

## Increased risk of noninfluenza respiratory virus infections
We randomized 115 children to TIV or placebo group. TIV recipients had an increased risk of noninfluenza respiratory virus infections over the following nine months. While being protected against influenza, TIV recipients may lack of temporary non-specific immunity that protected against other respiratory viruses. The results were published by Cowling et al. (2012, Clin Infect Dis).

Results described in the manuscript are reproduced in the following scripts which can be run in R:

* Table 1; Table 2; Table 3; Appendix Table 1.
* Figure 1; Appendix Figure 1.

---

## Main findings
The primary findings from the 2009-10 main study were published by [Cowling et al. (2012, Clin Infect Dis)][cowling2012]. In the main study, we recruited 796 children as well as their household members. Pandemic A(H1N1) circulated at the time of vaccination and for a short time afterward with no substantial seasonal influenza activity during that period. We found that seasonal TIV prevented pandemic influenza A(H1N1) and influenza B infections in children.

Results described in the manuscript are reproduced in the following scripts which can be run in R:

* scripts to reformat the raw data (used in some of the other scripts here).
* Table 1; Table 2; Table 3; Table S1; Table S2; Table S3; Table S4.
* Figure 2.

---

## Humoral antibody response after receipt of TIV
Among 119 children recruited in the pilot study, 64 children rejoined the main study and allocation of TIV/placebo in year 2 was independent of allocation in year 1. Ng et al. (2012, Pediatr Infect Dis J) studied those 64 subjects and suggested that humoral antibody response to TIV may be lower in children receiving repeated vaccination, but receipt of TIV induced seroprotection in most subjects.

Results described in the manuscript are reproduced in the following scripts which can be run in R:

* scripts to reformat the raw data (used in some of the other scripts here).
* Table 1; Table 2; Table 3.
* Figure 1.

---

## The effect of age and recent vaccination history on the efficacy of 2009-10 seasonal TIV
There is some evidence that annual vaccination of trivalent inactivated influenza vaccine (TIV) may lead to reduced vaccine immunogenicity but evidence is lacking on whether vaccine efficacy is affected by prior vaccination history. Ng et al. (2013, PLoS ONE) investigated on the 796 children recruited in the main study, whose influenza vaccination history in the two preceding years was recorded. Ng concluded that prior vaccination was associated with lower antibody responses to TIV against seasonal influenza A vaccine viruses, but higher responses to the same lineage of influenza B virus.

Results described in the manuscript are reproduced in the following scripts which can be run in R:

* scripts to reformat the raw data (used in some of the other scripts here).
* Table 2; Table 3; Table S1; Table S2; Table S3; Table S4.
* Figure 1; Figure S2.

---

## The association between antibody titers and protection against influenza
Antibody titers measured by hemagglutination inhibition (HAI) correlate with protection against influenza virus infection and are used to specify criteria for vaccine licensure. Ng et al. (2013, JID) investigated on the 773 children recruited in the main study with HAI titers available, and found that HAI titers of 1:40 against A(H1N1)pdm09 and B(Victoria lineage) were associated with 48% and 55% protection against PCR-confirmed infection with each strain.

Results described in the manuscript are reproduced in the following scripts which can be run in R:

* source 1; source 2; source 3; source 4; source 5; source 6 (used in some of the other scripts here).
* Figure 1; Figure 2; Appendix Figure 1.
* Appendix Table 1; Appendix Table 2.

---

## Further work
We have a series of further analyses underway using the data from our study. More details will follow later.


## Authors and investigators
The principal investigator of this study is Ben Cowling. The data were uploaded by Ben Cowling, and the scripts were written by Ben Cowling, Vicky Fang, Brendan Klick, and Sophia Ng.

## A comment on reproducible research
We fully support the increasing calls from the academic community for epidemiologic analyses to be reproducible, and raw data from randomized controlled trials to be published, as a part of the wider scientific endeavour to replicate results. Another example of this recommendation is in the Good Practice Guide for Quantitative Veterinary Epidemiology. Here we have published the raw anonymised data from our HK vaccination pilot study, and will later release the data from our main study. We have also published scripts which allow the analyses in our published papers to be reproduced.

Thousands of local people have given their time, and their families', as part of their participation in our studies, all in the expectation that our research studies will add to medical and scientific knowledge. Participants should also expect that we will make the best possible use of the information that we have collected about them. It would be difficult to argue that facilitating best use of the data by the research community need not involve releasing raw data.

Publication of anonymised raw data has been approved by our local IRB and funding sources, and participants were advised that anonymised data would be published during the informed consent process. We anticipate that release of the raw data will:

* Promote reproducibility of our results.
* Allow other investigators to conduct their own analyses on our data.
* Allow other investigators to compare our data with theirs, for example to explore similarities and differences between research findings.
* Allow other investigators to prepare and plan for their own studies.

---

## Publications 
1. Xiong W, Tsang TK, Perera RAPM, Leung NHL, Fang VJ, Barr IG, Malik Peiris JS, Cowling BJ. Biphasic Waning of Hemagglutination Inhibition Antibody Titers After Influenza Vaccination in Children. J Infect Dis. 2022 Sep 21;226(6):1022-1026. doi: 10.1093/infdis/jiac117. PMID: 35380689.
1. Tsang TK, Lam KT, Liu Y, Fang VJ, Mu X, Leung NHL, Peiris JSM, Leung GM, Cowling BJ, Tu W. Investigation of CD4 and CD8 T cell-mediated protection against influenza A virus in a cohort study. BMC Med. 2022 Jul 21;20(1):230. doi: 10.1186/s12916-022-02429-7. PMID: 35858844; PMCID: PMC9301821.
1. Lau YC, Perera RAPM, Fang VJ, Luk LH, Chu DKW, Wu P, Barr IG, Peiris JSM, Cowling BJ. Variation by lineage in serum antibody responses to influenza B virus infections. PLoS One. 2020 Nov 9;15(11):e0241693. doi: 10.1371/journal.pone.0241693. PMID: 33166348; PMCID: PMC7652285.
1. Cowling BJ, Perera RA, Fang VJ, Chan KH, Wai W, So HC, Chu DK, Wong JY, Shiu EY, Ng S, Ip DK, Peiris JS, Leung GM. Incidence of influenza virus infections in children in Hong Kong in a 3-year randomized placebo-controlled vaccine study, 2009-2012. Clin Infect Dis. 2014 Aug 15;59(4):517-24. doi: 10.1093/cid/ciu356. Epub 2014 May 13. PMID: 24825868.
1. Cowling BJ, Ng S, Ma ES, Fang VJ, So HC, Wai W, Cheng CK, Wong JY, Chan KH, Ip DK, Chiu SS, Peiris JS, Leung GM. Protective efficacy against pandemic influenza of seasonal influenza vaccination in children in Hong Kong: a randomized controlled trial. Clin Infect Dis. 2012 Sep;55(5):695-702. doi: 10.1093/cid/cis518. Epub 2012 Jun 5. PMID: 22670050.




[D1]: {% link docs/projects/kiddivax/data/KiddivaxPilot.zip %}
[D2]: {% link docs/projects/kiddivax/data/KiddivaxMain.zip %}

[L1]: http://www.opendatacommons.org/odc-public-domain-dedication-and-licence/

[cowling2010]: http://dx.doi.org/10.1086/657311
[cowling2012]: https://doi.org/10.1093/cid/cis307
[klick2011]: http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3206962/

[T1]: {% link docs/projects/kiddivax/script/Table_1.r %}
[T2]: {% link docs/projects/kiddivax/script/Table_2.r %}
[T3]: {% link docs/projects/kiddivax/script/Table_3.r %}
[T4]: {% link docs/projects/kiddivax/script/Table_4.r %}
[T5]: {% link docs/projects/kiddivax/script/Table_5.r %}
[T6]: {% link docs/projects/kiddivax/script/Table_6.r %}
[T7]: {% link docs/projects/kiddivax/script/Table_7.r %}
[T8]: {% link docs/projects/kiddivax/script/Table_8.r %}

[F1]: {% link docs/projects/kiddivax/script/Figure_1.r %}
[FS1]: {% link docs/projects/kiddivax/script/Figure_S1.r %}
[FS2]: {% link docs/projects/kiddivax/script/Figure_S2.r %}
[FS3]: {% link docs/projects/kiddivax/script/Figure_S3.r %}
[FS4]: {% link docs/projects/kiddivax/script/Figure_S4.r %}