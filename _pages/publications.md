---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


### By date
_pending_
* Ollison G., Hu, S.K., Mesrop, L.Y., Delong, E. & Caron, D. A. Come Rain or Shine: Depth Not Season Shapes the Protistan Community at Station ALOHA in the North Pacific Subtropical Gyre. (In Review, Deep-Sea Research Part I).

* Hu, S.K., Herrera, E.L., Smith, A.R., Pachiadaki, M.G., Edgcomb, V.P., Sylva, S.P., Chan E.W., Seewald, J.S., German, C.R., & Huber, J.A. Protistan grazing impacts microbial communities and carbon cycling in the deep-sea hydrothermal vent environment. (In Prep).

* Hu, S.K., Alexander, H., Liu, Z., Heidelberg, K.B., Dyhrman, S. & Caron, D.A. Distinct transcriptional signatures of the protistan community at the SPOT and ALOHA ocean time-series stations. (In Prep).

## 2020
* Coesel, S.N., Durham, B.P., Groussman, R.D., Hu, S.K., Caron, D.A., Morales, R.L., Ribalet, F., Armbrust, E.V. Diel transcriptional oscillations of light-sensitive regulatory elements in open ocean eukaryotic plankton communities. (In Press, Proc Natl Acad Sci USA).

* Krinos, A., Hu, S.K., Cohen, N.R. & Alexander, H. EUKulele: Taxonomic annotation of the unsung eukaryotic microbes. (In Press, Journal of Open Source Software) Preprint DOI:10.21105/joss.02799 

* Goordial, J., Hu, S., & Tully, B. (2020). C-DEBI NextGen 2019 Early Career perspective on ‘What’s Next?’: Upcoming Challenges and Opportunities. DOI: 10.31219/osf.io/7xkpq

* Coenen, A.R., Hu, S.K., Luo, E., Muratore, D., and Weitz, J.S. (2020) A Primer for Microbiome Time-Series Analysis. Front Genet 11: 310.

* Lim, Darlene S.S., Raineault, N.A., Brier, J.A., Chan, E., Chernov, J., Cohen, T., Deans, M., Garcia, A., German, C. R., Hauer, M., Hu, S.K., Huber, J.A., Kane, R., Kobs Nawotniak, S., Lees, D., Lowe, J., Lubetkin, M., Marsh, L., Milesi, V., Miller, M., Miramalek, Z., Saunders, M., Sharif, K., Shields, A., Shock, E., Smith, A.R., and Sylva, S. (2020), SUBSEA 2019 Expedition to the Gorda Ridge, Oceanography 33(1), Supplement Pages 36 – 37.

## 2019
* Boeuf, D., Edwards, B.R., Eppley, J.M., Hu, S.K., Poff, K.E., Romano, A.E., et al. (2019) Biological composition and microbial dynamics of sinking particulate organic matter at abyssal depths in the oligotrophic open ocean. Proc Natl Acad Sci USA 11824–11832.

* Liu, Z., Mesrop, L.Y., Hu, S.K., and Caron, D.A. (2019) Transcriptome of Thalassicolla nucleata Holobiont Reveals Details of a Radiolarian Symbiotic Relationship. Front Mar Sci 6: 284.

* Pasulka, A., Hu, S.K., Countway, P.D., Coyne, K.J., Cary, S.C., Heidelberg, K.B., and Caron, D.A. (2019) SSU rRNA Gene Sequencing Survey of Benthic Microbial Eukaryotes from Guaymas Basin Hydrothermal Vent. Journal of Eukaryotic Microbiology jeu.12711.

* Caron, D.A. and Hu, S.K. (2019) Are We Overestimating Protistan Diversity in Nature? Trends in Microbiology 27: 197–205.

## 2018
* Hu, S.K., Liu, Z., Alexander, H., Campbell, V., Connell, P.E., Dyhrman, S.T., et al. (2018) Shifting metabolic priorities among key protistan taxa within and below the euphotic zone: Depth-related protistan metatranscriptomes. Environ Microbiol 20: 2865–2879.

* Hu, S.K., Paige E. Connell, Mesrop, L.Y., and Caron, D.A. (2018) A Hard Day’s Night: Diel Shifts in Microbial Eukaryotic Activity in the North Pacific Subtropical Gyre. Front Mar Sci 5:251.

## 2017
* Liu, Z., Hu, S.K., Campbell, V., Tatters, A.O., Heidelberg, K.B., and Caron, D.A. (2017) Single-cell transcriptomics of small microbial eukaryotes: limitations and potential. The ISME Journal 11: 1282–1285.

* Connell, P.E., Campbell, V., Gellene, A.G., Hu, S.K., and Caron, D.A. (2017) Planktonic food web structure at a coastal time-series site: II. Spatiotemporal variability of microbial trophic activities. Deep Sea Res Part I Oceanogr Res Pap 121: 210–223.

## 2016
* Hu, S.K., Campbell, V., Connell, P., Gellene, A.G., Liu, Z., Terrado, R., and Caron, D.A. (2016) Protistan diversity and activity inferred from RNA and DNA at a coastal ocean site in the eastern North Pacific. FEMS Microbiol Ecol fiw050.

## 2015 
* Hu, S.K., Liu, Z., Lie, A.A.Y., Countway, P.D., Kim, D.Y., Jones, A.C., et al. (2015) Estimating Protistan Diversity Using High-Throughput Sequencing. Journal of Eukaryotic Microbiology 62: 688–693.

* Lie, A.A.Y., Liu, Z., Hu, S.K., Jones, A.C., Kim, D.Y., Countway, P.D., et al. (2014) Investigating Microbial Eukaryotic Diversity from a Global Census: Insights from a Comparison of Pyrotag and Full-Length Sequences of 18S rRNA Genes. Applied and Environmental Microbiology 80: 4363–4373.


---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
