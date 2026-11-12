---
title: "Hong Kong pandemic (H1N1) 2009 transmission study"
parent: Projects
nav_order: 4 # order in ToC
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

Following the emergence of pandemic 2009 influenza A (H1N1), we conducted a household transmission study based on a similar protocol to our earlier trial of non-pharmaceutical interventions, to establish the basic household epidemiology of novel H1N1 and compare with seasonal influenza.

In July and August 2009 we recruited subjects presenting to outpatient clinics (in both the private and public sectors across Hong Kong) with influenza-like-illness of <48 hours duration. After influenza was confirmed in an index case by the QuickVue Influenza A+B rapid test the household of the index subject was recruited to our household transmission study. We aimed to conduct an initial home visit within 36 hours of recruitment, and evaluate subsequent infections by self-reported daily symptom diaries and home visits after 3 and 6 days. Nose and throat swabs were collected from index subjects and all household contacts at each home visit and tested by RT-PCR. The primary outcome measure was laboratory-confirmed influenza infection in a household contact by RT-PCR; the secondary outcome was clinically diagnosed influenza by self-reported symptoms. We collected acute and convalescent sera from a subset of participants and tested for antibody titers to seasonal and pandemic influenza.

---

## Data

The latest version of the Hong Kong household transmission study is available to download as a zip file [here][D1].

This version of the dataset covers the transmission of influenza in households and adherence to interventions, antiviral treatment, quantitative viral loads, serology, and data from recruiting clinics including presenting symptoms and rapid test performance.

We provide our data under the [Open Data Commons Public Domain Dedication and License][L1], which is a version of open access for data. Under this licence we reserve no rights: there are no restrictions on use of our data, and no requirement to cite our work or this website. However we would anticipate that for academic purposes the standard practice of referencing sources would apply. We would like to hear from researchers who are using our data and we would be keen to work together on analyses.

---

## Main findings

The primary findings from our main study have been published in [Cowling et al. (2010, NEJM)][cowling2010_L2]. Our main findings were that RT-PCR-confirmed secondary attack rates were similar among household contacts of index cases with pandemic and seasonal influenza A, while patterns in viral shedding and course of illness among index cases with pandemic and seasonal influenza A were similar.

The results presented in the manuscript are reproduced by the R scripts, which can be downloaded [here][S1].

<!-- Results described in Cowling et al. (2010) are reproduced in the following scripts which can be run in R:

* [Table 1 and Appendix Table 1][T1]
* [Table 2][T2]
* [Table 3][T3]
* [Figure 2][F2]
* [Appendix Table 2][TS2]
* [Appendix Figure 1][FS1]
* [Appendix Figure 2][FS2]
* [Appendix Figure 3][FS3]
* [Appendix Figure 4][FS4]
* [Other results described in the manuscript text][R1] -->

---

## Further work
{: .no_toc }

We have further analyses underway using the data from our study. More details will follow later.

## Authors and investigators
The principal investigator of this study is [Ben Cowling][cowlingHKUSPH]. <br>
The data were uploaded by [Ben Cowling][cowlingHKUSPH], and the scripts were written by Vicky Fang and [Ben Cowling][cowlingHKUSPH].

## A comment on reproducible research
{: .no_toc }

We fully support the [increasing calls][ref1] from the academic community for [epidemiologic analyses to be reproducible][ref2], and [raw data from randomized controlled trials to be published][ref3], as a part of the wider scientific endeavour to replicate results. Another example of this recommendation is in the Good Practice Guide for Quantitative Veterinary Epidemiology. Here we have published the raw anonymised data from our HK vaccination pilot study, and will later release the data from our main study. We have also published scripts which allow the analyses in our published papers to be reproduced.

Thousands of local people have given their time, and their families', as part of their participation in our studies, all in the expectation that our research studies will add to medical and scientific knowledge. Participants should also expect that we will make the best possible use of the information that we have collected about them. It would be difficult to argue that facilitating best use of the data by the research community need not involve releasing raw data.

Publication of anonymised raw data has been approved by our local IRB and funding sources, and participants were advised that anonymised data would be published during the informed consent process. We anticipate that release of the raw data will:
* Promote reproducibility of our results.
* Allow other investigators to conduct their own analyses on our data.
* Allow other investigators to compare our data with theirs, for example to explore similarities and differences between research findings.
* Allow other investigators to prepare and plan for their own studies.

---

## Publications

1. Cowling BJ, Chan KH, Fang VJ, et al. Comparative epidemiology of pandemic and seasonal influenza A in households. New England Journal of Medicine, 2010; 362:2175-84. <br> 
<span class="fs-2"> [DOI][cowling2010_L1]{: .btn .btn-outline .mt-1 .mr-1 .mb-0 } </span>
<span class="fs-2"> [PubMed][cowling2010_L2]{: .btn .btn-outline } </span>



--- 

## Acknowledgements

This project was supported with Federal funds from the National Institute of Allergy and Infectious Diseases, National Institutes of Health, under Contract No. HHSN266200700005C; ADB No. N01-AI-70005 (NIAID Centers for Excellence in Influenza Research and Surveillance) and the Area of Excellence Scheme of the Hong Kong University Grants Committee (grant no. AoE/M-12/06). Further analyses were supported by the Harvard Center for Communicable Disease Dynamcs from the US National Institutes of Health Models of Infectious Disease Agent Study program (grant no. 1 U54 GM088558).




[D1]: {% link docs/projects/HTS/data/HongKongHTSV1.zip %}
[L1]: https://opendatacommons.org/licenses/pddl/1-0/

[cowling2010_L1]: https://doi.org/10.1056/nejmoa0911530
[cowling2010_L2]: http://www.ncbi.nlm.nih.gov/pubmed/20558368

[S1]: {% link docs/projects/HTS/script/HTS_script.zip %}

<!-- [T1]: {% link docs/projects/HTS/script/Table_1.r %}
[T2]: {% link docs/projects/HTS/script/Table_2.r %}
[T3]: {% link docs/projects/HTS/script/Table_3.r %}
[TS2]: {% link docs/projects/HTS/script/Appendix_Table_2.r %}

[F2]: {% link docs/projects/HTS/script/Figure_2.r %}
[FS1]: {% link docs/projects/HTS/script/Appendix_Figure_1.r %}
[FS2]: {% link docs/projects/HTS/script/Appendix_Figure_2.r %}
[FS3]: {% link docs/projects/HTS/script/Appendix_Figure_3.r %}
[FS4]: {% link docs/projects/HTS/script/Appendix_Figure_4.r %}

[R1]: {% link docs/projects/HTS/script/Text_result.r %} -->

[cowlingHKUSPH]: https://sph.hku.hk/en/Biography/Cowling-Benjamin-John

[ref1]: https://doi.org/10.1097/EDE.0b013e318196784a
[ref2]: https://doi.org/10.1093/aje/kwj093
[ref3]: https://doi.org/10.1186/1745-6215-10-17





