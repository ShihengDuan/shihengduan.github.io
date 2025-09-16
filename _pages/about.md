---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a postdoctoral researcher at Lawrence Livermore National Laboratory. My research focuses on the hydroclimate system, climate change impacts, detection and attribution (D&A), and extreme events. I use machine learning and deep learning to study climate, as well as simulations from climate models. My broader goal is to integrate AI and climate science to improve prediction, risk assessment, and climate adaptation strategies. 


# 📖 Educations
- *2017.09 - 2022.08*, Ph.D. in Atmospheric Science. University of California, Davis. 
- *2016.08 - 2016.12*, Exchange student, University of Oklahoma. 
- *2013.09 - 2017.06*, Bachelor in Environment Engineering. Beijing Normal University. 

# 💼 Work Experience
- *2022.09 - current*, Postdoctoral researcher @ LLNL
- *2017.09 - 2022.08*, Graduate student researcher @ UC Davis 

<!---
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
--->

# 📝 Publications
## First-Author

1. [Testing NeuralGCM's capability to simulate future heatwaves based on the 2021 Pacific Northwest heatwave event](https://www.nature.com/articles/s41612-025-01137-2) **Shiheng Duan**, Jishi Zhang, Céline Bonfils, Giuliana Pallotta. 2025
    - Could NeuralGCM effectively simulate future heatwaves? A case study based on the 2021 Pacific Northwest heatwave
    - How do we nudge? For stochastic ensembles, we introduce _ensemble involution_. For determinstic version, we follow the traditional nudging tendency and there is a relevant GitHub [issue](https://github.com/neuralgcm/neuralgcm/issues/247).

1. [Higher-order internal modes of variability imprinted in year-to-year California streamflow changes](https://www.nature.com/articles/s43247-024-01594-2) **Shiheng Duan**, Giuliana Pallotta, Céline Bonfils. 2024
  - Higher-order EOF modes are derived from the well-known climate variability domains with [PMP](https://pcmdi.github.io/pcmdi_metrics/). 
  - The BCSD-CMIP6-LSTM streamflow projections are quantitatively related with internal variability indices using various ML models. 
  - All the ML models show PNA-5 is the most dominant pattern affecting streamflow in California, which looks like an atmospheric-river pattern. 
  - BCSD does not change variability indices, as a technical note. 
  
1. [Meteorological drivers of North American monsoon extreme precipitation events](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2023JD040535) 
**Shiheng Duan**, Paul Ullrich, William Boos. 2024
  - North American Monsoon area is delineated from a gridded precpitation dataset, and further divded into seven subregions with distinct precipitation characteristics. 
  - The meteorological drivers are identified for extreme precpitation events (p95) for each subregion. 
  - The interaction effects of these meteorological drivers on EPE probability are analyzed. 
  
1. [Using temporal deep learning models to estimate daily snow water equivalent over the Rocky Mountains](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2023WR035009)
**Shiheng Duan**, Paul Ullrich, Mark Risser, Alan Rhoades. 2024
  - LSTM, TCNN and Transformer models are benchmarked with in-situ SNOTEL observations. 
  - A transformation (SWE to SWE ratio) is applied to extrapolate the DL models to generate gridded SWE estimations. 
  - This technique can be used for climate projections (deleted after peer-review). Some results are available [here](https://essopenarchive.org/doi/full/10.1002/essoar.10509011.1). 


1. [Using convolutional neural networks for streamflow projection in California](https://www.frontiersin.org/journals/water/articles/10.3389/frwa.2020.00028/full) **Shiheng Duan**, Paul Ullrich, Lele Shu. 2020
  - TCNN can be used for hydrological modelling, in addition to LSTM. 
  - An idealized test is designed for projection purpose. 
  - A "nonlinear" relationship of precipitation-runoff is revealed from DL models for snow-dominant basins. 
{: reversed="reversed"}
## Co-Author
1. [Through the lens of a kilometer-scale climate model: 2023 Jing-Jin-Ji flood under climate change](https://www.authorea.com/doi/full/10.22541/au.172773252.24608967) Jishi Zhang, et al. 2025
  - Storyline simulation using regional-refined model for Beijing storm 2023
  - The double tropical cyclone is a unique feature. 
  - Preprint.
  
1. [Recommendations for comprehensive and independent evaluation of machine learning-based Earth system models](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2024JH000496) Paul Ullrich, et al. 2025
  - How do we evaluate ML-based Earth system models?  
  - More detailed following studies. 
  - FY25 PLS Summer Award. 

1. [Atmospheric emission inventory of hazardous air pollutants from China's cement plants: Temporal trends, spatial variation characteristics and scenario projections](https://www.sciencedirect.com/science/article/pii/S1352231015306385) Shenbing Hua, et al. 2016
  - A comprehensive emission inventory of air pollutants. 
  - More inventory and air pollution studies from [Prof. Tian's team](https://envfaculty.bnu.edu.cn/Public/htm/news/5/107.html) in Beijing Normal University. 
{: reversed="reversed"}

## in preparation

  - Towards enhanced detectability of forced signals in monthly rainfall changes. Shiheng Duan, et al. 2025
    - Detect forced precipitation changes without any spatial or temporal aggregation. 
    - Work from [ForceSMIP](https://sites.google.com/ethz.ch/forcesmip/).  
    - Revision. 

  - Understanding the Evolving Patterns of Extreme Rainfall. Céline Bonfils, et al. 2025
    - Forced changes on extreme precipitation (rx1day, rx5day). 
    - A related [video](https://pacificclimate.org/~IMSC/4-Thursday/1-Plenaries/Bonfils.mp4) introducing climate change signals in rainfall (from [mean precipitation](https://www.nature.com/articles/s41558-020-0821-1) to extreme precipitation). 
    - Revision. 

  - [Forced Component Estimation Statistical Method Intercomparison Project (ForceSMIP)](https://essopenarchive.org/doi/full/10.22541/essoar.175003371.14843115/v1). Robert Wills, et al. 2025
    - Hackathon paper from [ForceSMIP](https://sites.google.com/ethz.ch/forcesmip/).
    - Revision. 
  - A PMP-Inspired Evaluation Framework for Assessing the fit-for-purpose of Deep-Learning Weather Prediction Models. Giuliana Pallotta, et al. 2025
    - Using PMP to diagnose and compare DL-ESMs with traditional CMIP6 models. 
    - I have conducted AMIP-type simulation with NeuralGCM and ACE2. The output is CMORized following the [PCMDI code](https://github.com/PCMDI/AI-MIP). 
    - Apply PMP metrics. 
    
# 🎖 Honors and Awards
- *2020.06* UC Davis Summer GSR Award. 
- *2020.02* Walter and Margaret Milton Graduate Atmospheric Science Award. 3000 for research expenses (got a GPU on Tempest) and 1000 personal stipend.  
- *2016.06* Beijing Normal University Second Prize Scholarship



# 💬 Talks
- *2024.06*, Higher-order internal modes of variability imprinted in year-to-year California streamflow changes. $15^{th}$ International Meeting on Statistical Climatology. Toulouse, France. 
- *2024.06*, Detection of Anthropogenic Signals in Western US Snowpack Changes. $15^{th}$ International Meeting on Statistical Climatology. Toulouse, France. 
- *2022.12*, [AutoML-based Almond Yield Prediction and Projection in California.](https://arxiv.org/abs/2211.03925) Tackling Climate Change with Machine Learning: workshop at NeurIPS 2022. 
- *2021.12*, A Comprehensive Investigation of Machine Learning Models for Estimating Daily Snow Water Equivalent over the Western US. AGU fall meeting. New Orleans, LA. 


# 🎹 Life

My daughter, Lumina Duan, was born on March 19th 2025 🎉🎉   

My father, an artist, likes to make [music videos](https://www.bilibili.com/video/BV1KZ421B7uB?spm_id_from=333.788.videopod.sections&vd_source=0c17b8138080aa025465aa1df1a15014) by himself.    

My wedding [video](https://www.bilibili.com/video/BV1ht421b7GN/?spm_id_from=333.337.search-card.all.click), 2023 Christmas in China. 

My piano [video](https://www.bilibili.com/video/BV1Je411W7L7/?spm_id_from=333.999.0.0) when I was 12 years old. 
