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

I am currently a postdoctoral researcher at Lawrence Livermore National Laboratory. My research focuses on the hydroclimate system, exploring climate change impacts, detection and attribution (D&A), and extreme events. I use machine learning and deep learning to study climate, as well as simulations from climate models. 


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

- [Higher-order internal modes of variability imprinted in year-to-year California streamflow changes](https://www.nature.com/articles/s43247-024-01594-2) **Shiheng Duan**, Giuliana Pallotta, Céline Bonfils
  - Higher-order EOF modes are derived from the well-known climate variability domains. 
  - The BCSD-CMIP6-LSTM streamflow projections are quantitatively related with internal variability indices using various ML models. 
  - All the ML models show PNA-5 is the most dominant pattern affecting streamflow in California, which looks like an atmospheric-river pattern. 
  - BCSD does not change variability indices, as a technical note. 
  - [GitHub](https://github.com/ShihengDuan/ClimateVariabilityStreamflow)

- [Meteorological drivers of North American monsoon extreme precipitation events](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2023JD040535) 
**Shiheng Duan**, Paul Ullrich, William Boos
  - North American Monsoon area is delineated from a gridded precpitation dataset, and further divded into seven subregions with distinct precipitation characteristics. 
  - The meteorological drivers are identified for extreme precpitation events (p95) for each subregion. 
  - The interaction effects of these meteorological drivers on EPE probability are analyzed. 
  - [GitHub](https://github.com/ShihengDuan/NorthAmericanMonsoon)

- [Using temporal deep learning models to estimate daily snow water equivalent over the Rocky Mountains](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2023WR035009)
**Shiheng Duan**, Paul Ullrich, Mark Risser, Alan Rhoades
  - LSTM, TCNN and Transformer models are benchmarked with in-situ snow observations. 
  - A transformation (SWE to SWE ratio) is applied to extrapolate the DL models to generate gridded SWE estimations. 
  - This technique can be used for climate projections (deleted after peer-review). 
  - [GitHub](https://github.com/ShihengDuan/code-SWE)

- [Using convolutional neural networks for streamflow projection in California](https://www.frontiersin.org/journals/water/articles/10.3389/frwa.2020.00028/full) **Shiheng Duan**, Paul Ullrich, Lele Shu
  - TCNN can be used for hydrological modelling, in addition to LSTM. 
  - An idealized test is designed for projection purpose. 
  - A "nonlinear" relationship of precipitation-runoff is revealed from DL models for snow-dominant basins. 
  - [GitHub](https://github.com/ShihengDuan/Streamflow)

- [Atmospheric emission inventory of hazardous air pollutants from China's cement plants: Temporal trends, spatial variation characteristics and scenario projections](https://www.sciencedirect.com/science/article/pii/S1352231015306385) Hua, Shenbing, et al. 2016
  - A comprehensive emission inventory of air pollutants. 
  - More inventory and air pollution studies from Prof. Tian's team in Beijing Normal University. 

* in preparation
  - [Through the lens of a kilometer-scale climate model: 2023 Jing-Jin-Ji flood under climate change](https://www.authorea.com/doi/full/10.22541/au.172773252.24608967) Jishi Zhang, et al. 2024
    - Storyline simulation using regional-refined model for Beijing storm 2023
    - The double tropical cyclone is a unique feature. 

  - [Recommendations for comprehensive and independent evaluation of machine learning-based Earth system models](https://arxiv.org/abs/2410.19882) Paul Ullrich, et al. 2024
    - How do we evaluate AI-based Earth system models? 
    - Overview paper in revison. 

  - [AI-based climate model evaluation through the lens of heatwave storylines](https://arxiv.org/abs/2410.09120) Shiheng Duan, et al. 2024
    - Can we use AI-climate model to conduct storyline simulations? How do we "nudge"? 
    - Rejected. Let's see where it goes. A relevant GitHub [issue](https://github.com/neuralgcm/neuralgcm/issues/247).
  
  - [Towards enhanced detectability of forced signals in monthly rainfall changes] Shiheng Duan, et al. 2025
    - Detect forced precipitation changes without any spatial or temporal aggregation. 
    - Work from ForceSMIP. 
    - Submitted. 

# 🎖 Honors and Awards
- *2020.06* UC Davis Summer GSR Award. 
- *2020.02* Walter and Margaret Milton Graduate Atmospheric Science Award. 
- *2016.06* Beijing Normal University Second Prize Scholarship



# 💬 Talks
- *2024.06*, Detection of Anthropogenic Signals in Western US Snowpack Changes. $15^{th}$ International Meeting on Statistical Climatology. Toulouse, France. 
- *2021.12*, A Comprehensive Investigation of Machine Learning Models for Estimating Daily Snow Water Equivalent over the Western US. AGU fall meeting. New Orleans, LA. 


# 🎹 Life

My wedding [video](https://www.bilibili.com/video/BV1ht421b7GN/?spm_id_from=333.337.search-card.all.click), 2023 Christmas. 

My piano [video](https://www.bilibili.com/video/BV1Je411W7L7/?spm_id_from=333.999.0.0) when I was 12 year-old. 
