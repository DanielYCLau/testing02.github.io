---
title: "Healthcare Worker Study (2010)"
parent: Projects
nav_order: 5 # order in ToC
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
{: .d-inline-block }

Coming soon
{: .label .label-yellow }


---

## Data

The latest version of the HCWs antibody study is available to download [here][D1].

This version of the dataset covers the basic characteristics of HCWs, vaccine history, pH1N1 infection history, and serology results.

We provide our data under the Open Data Commons Public Domain Dedication and License, which is a version of open access for data. Under this licence we reserve no rights: there are no restrictions on use of our data, and no requirement to cite our work or this website. However we would anticipate that for academic purposes the standard practice of referencing sources would apply. We would like to hear from researchers who are using our data and we would be keen to work together on analyses.

---

## Main findings

The primary findings from our main study have been published in [Zhou et al. (2011, JHI)][zhou2011_L2]. Our main findings were that.

The results presented in the manuscript are reproduced by the R scripts, which can be downloaded [here][S1].

<!-- Results described in Zhou et al. (2011) are reproduced in the following scripts which can be run in R:

* [Table 1][T1]
* [Table 2][T2]
* [Table 3][T3]
* [Other results described in the manuscript text][R1] -->

---

## Further work
{: .no_toc }

We have further analyses underway using the data from our study. More details will follow later.


## Authors and investigators
The principal investigator of this study is [Ben Cowling][cowlingHKUSPH]. <br>
The data were uploaded by [Ben Cowling][cowlingHKUSPH], and the scripts were written by Joey Zhou, Vicky Fang and [Ben Cowling][cowlingHKUSPH].

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
1. Zhou Y, Ng DMW, Seto WH, Ip DKM, Kwok HKH, Ma ESK, Ng S, Lau LLH, Wu JT, Peiris JSM, Cowling BJ. Seroprevalence of antibody to pandemic influenza A (H1N1) 2009 among healthcare workers after the first wave in Hong Kong. Journal of Hospital Infection, 2011; 78 (4):308-311. <br>
<span class="fs-2"> [DOI][zhou2011_L1]{: .btn .btn-outline .mt-1 .mr-1 } </span>
<span class="fs-2"> [PubMed][zhou2011_L2]{: .btn .btn-outline } </span>



---

## Acknowledgements
This project was funded by the Area of Excellence Scheme of the Hong Kong University Grants Committee (grant no. AoE/M-12/06) and the Research Fund for the Control of Infetious Disease, Food and Health Bureau, Government of the Hong Kong SAR (grant no. PHE-20).




[D1]: {% link docs/projects/HCW2010/data/hcws2010.csv %}


[S1]: {% link docs/projects/HCW2010/script/HCW2010_script.zip %}

<!-- [T1]: {% link docs/projects/HCW2010/script/Table_1.r %}
[T2]: {% link docs/projects/HCW2010/script/Table_2.r %}
[T3]: {% link docs/projects/HCW2010/script/Table_3.r %}
[R1]: {% link docs/projects/HCW2010/script/Text_results.r %} -->


[cowlingHKUSPH]: https://sph.hku.hk/en/Biography/Cowling-Benjamin-John

[ref1]: https://doi.org/10.1097/EDE.0b013e318196784a
[ref2]: https://doi.org/10.1093/aje/kwj093
[ref3]: https://doi.org/10.1186/1745-6215-10-17

[zhou2011_L1]: https://doi.org/10.1016/j.jhin.2011.02.017
[zhou2011_L2]: http://www.ncbi.nlm.nih.gov/pubmed/21501896

