---
title: "2009 Pandemic Influenza A(H1N1) Surveys"
parent: Projects
nav_order: 2 # order in ToC
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
There is a substantial literature examining psychosocial determinants of behavior change in relation to non-communicable disease, but much less research has been devoted to understanding how populations react and respond to communicable disease epidemics. Yet is it precisely these responses that can potentially determine the overall impact of an epidemic by influencing risk-taking and protective practices.

Our group has been conducting a series of population surveys in collaboration with the [School of Public Health at CUHK][sphpcCUHK], to study community responses before, during and after the first wave of 2009 pandemic influenza A(H1N1) locally, to determine disease attack rates and use of healthcare services, and to study the use of preventive measures, and how these might be affected by individuals’ attitudes towards influenza and their perception of the risks they faced.

---

## Data
Raw data from our surveys and the data dictionary are available to download [here][D1].

<!-- Raw data from our surveys is available to download here:
* [File][D1]
* [Dictionary][D2] -->

This version of the survey data contains all items included in our first paper. Data on additional items included in our surveys will be released at a later date.

We provide our data under the [Open Data Commons Public Domain Dedication and License][L1], which is a version of open access for data. Under this licence we reserve no rights: there are no restrictions on use of our data, and no requirement to cite our work or this website. However we would anticipate that for academic purposes the standard practice of referencing sources would apply. We would like to hear from researchers who are using our data and we would be keen to work together on analyses.

---

## Main findings
Our first manuscript, published in the Journal of Infectious Diseases, describes the main results of 13 cross-sectional telephone surveys conducted between April and November 2009. Overall we identified no substantial changes in preventive measures through the first wave of H1N1, suggesting that community measures may not have played a substantial role in mitigating the epidemic impact. We also explored the factors associated with the adoption of hygiene behaviors, face mask use and social distancing.

The results presented in the manuscript are reproduced by the R scripts, which can be downloaded [here][S1]. <br>
_(require the R package 'MASS', 'IDPmisc' and 'fields')_{: .fs-3 }

The raw data sources and R scripts can also be downloaded from [DRYAD][DRYAD].

<!-- Results presented in that manuscript are reproduced in the following scripts which can be run in the free statistical software package R:
* [scripts][R1] to reformat the raw data (used in some of the other scripts here)
* [Table 3][T3] _(requires the R package 'MASS')_{: .fs-3 }
* [Table 4][T4] _(requires the R package 'MASS')_{: .fs-3 }
* [Table 5][T5] _(requires the R package 'MASS')_{: .fs-3 }
* [Figure 2][F2] _(requires the R package 'IDPmisc' and 'fields')_{: .fs-3 }

The raw data sources and R scripts to regenerate results in the published paper can also be downloaded from [DRYAD][DRYAD]. -->

---

## Further work
{: .no_toc }

We are continuing to analyze our survey data and further work is in preparation. More details will follow later.



## Authors and investigators

The principal investigators of this study are Richard Fielding and [Ben Cowling][cowlingHKUSPH]. <br>
The data were uploaded by [Ben Cowling][cowlingHKUSPH], and the scripts were written by Diane Ng, Vicky Fang and [Ben Cowling][cowlingHKUSPH].

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
1. Cowling BJ, Ng DMW, Ip DKM, Liao Q, Lam WWT, Wu JT, Lau JTF, Griffiths SM, Fielding R. Community psychological and behavioral responses through the first wave of 2009 influenza A(H1N1) pandemic in Hong Kong. Journal of Infectious Diseases, 2010; 202(6):867-876. <br>
<span class="fs-2"> [DOI][cowling2010_L1]{: .btn .btn-outline .mt-1 .mr-1 } </span>
<span class="fs-2"> [PubMed][cowling2010_L2]{: .btn .btn-outline } </span>



---

## Acknowledgements
This study received funding from the Research Fund for the Control of Infectious Disease, Food and Health Bureau, Government of the Hong Kong SAR (grant no. PHE-1), and the Area of Excellence Scheme of the Hong Kong University Grants Committee (grant no. AoE/M-12/06).

Surveys were conducted by HKU Public Opinion Program (HKUPOP) (was succeeded by [Hong Kong Public Opinion Research Institute (HKPORI)][HKPORI]).



[D1]: {% link docs/projects/H1N1_survey/data/H1N1_survey_data.zip %}

<!-- [D1]: {% link docs/projects/H1N1_survey/data/HKU_surveys_v1.csv %}
[D2]: {% link docs/projects/H1N1_survey/data/survey_data_dictionary.xls %} -->

[L1]: https://opendatacommons.org/licenses/pddl/1-0/

[sphpcCUHK]: https://sphpc.cuhk.edu.hk/

[S1]: {% link docs/projects/H1N1_survey/script/H1N1_survey_script.zip %}

<!-- [R1]: {% link docs/projects/H1N1_survey/script/dataframe.r %}
[T3]: {% link docs/projects/H1N1_survey/script/Table_3.r %}
[T4]: {% link docs/projects/H1N1_survey/script/Table_4.r %}
[T5]: {% link docs/projects/H1N1_survey/script/Table_5.r %}
[F2]: {% link docs/projects/H1N1_survey/script/Figure_2.r %} -->

[DRYAD]: http://doi.org/10.5061/dryad.1485f

[cowlingHKUSPH]: https://sph.hku.hk/en/Biography/Cowling-Benjamin-John

[ref1]: https://doi.org/10.1097/EDE.0b013e318196784a
[ref2]: https://doi.org/10.1093/aje/kwj093
[ref3]: https://doi.org/10.1186/1745-6215-10-17

[cowling2010_L1]: https://doi.org/10.1086/655811
[cowling2010_L2]: http://www.ncbi.nlm.nih.gov/pubmed/20677945

[HKPORI]: https://www.pori.hk/