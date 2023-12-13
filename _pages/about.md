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

测试文字.

测试文字.

测试文字.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 藻华监测系统上线. 
- *2022.02*: &nbsp;🎉🎉 数据上线. 
- *2022.02*: &nbsp;🎉🎉 测试文字. 

# 📝 Products

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Algal Blooms</div><img src='images/WEBNEW.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Satellite Detection For Algal Blooms** 👉[[link](http://www.sklec-oceancolor.cn:8889/home/)]

**藻华卫星监测系统**

[**Introduction**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Online visualization of Red Tide Index  product in Eastern Seas of China base on C2RCC atomospheric corrected Sentinel-3 OLCI image. The Red Tide Index (RDI),  is a three-band-model-based index that can indicate magnitude of Chla, suitable for the purpose of detecting algal blooms in turbid coastal waters for multi-source ocean color data.
- 基于C2RCC大气校正Sentinel-3 OLCI图像的中国东海赤潮指数产品在线可视化。赤潮指数（RDI）是一个基于三波段模型的指数，可以指示叶绿素a的大小，适用于监测多源海洋颜色数据检测浑浊沿海水域的藻华情况。
- [**Paper**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- [Simple methods for satellite identification of algal blooms and species using 10-year time series data from the East China Sea](https://doi.org/10.1016/j.rse.2019.111484), **Remote Sensing of Environment**
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Global Phytoplankton Group</div><img src='images/Fig.9.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**Estimating Global Phytoplankton Group**

**全球浮游植物类群反演**

[**Introduction**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Accurate monitoring of the spatial-temporal distribution and variability of phytoplankton group (PG) composition is of vital importance in better understanding of marine ecosystem dynamics and biogeochemical cycles.  In this study, an ensemble learning approach, called the spatial-temporal-ecological ensemble (STEE) model, is developed to construct a robust prediction model for eight distinct phytoplankton groups  The proposed method introduces multiple data simultaneously: ocean color, physical oceanographic, biogeochemical, and spatial and temporal information. The proposed model was utilized to retrieve global monthly phytoplankton group products (STEE-PG) over an extended period (September 1997 to May 2020).
- 利用二十年的全球长时序海洋水色卫星数据、物理海洋学模式数据、生物地球化学再分析数据和气象数据等不同海洋环境变量，结合多种先进机器学习与集成学习框架，并同时纳入空间和时间信息，构建了面向浮游植物类群反演的Spatial-Temporal-Ecological Ensemble（STEE）模型，实现了八种主要浮游植物类群全球长时序时空分布格局的准确反演。该研究突破了传统生物光学方法完全依赖于海洋水色数据所造成的局限性，验证了基于多源海洋大数据与机器学习技术的浮游植物类群反演新范式。
- [**Paper**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- [Marine big data-driven ensemble learning for estimating global phytoplankton group composition over two decades (1997–2020)](https://doi.org/10.1016/j.rse.2023.113596), **Remote Sensing of Environment**
- [**Product**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- OneDrive: 👉[[link](https://1drv.ms/f/s!AgOcOG0HOHXIgX4OliC_dozAA5R-?e=lNuiBC)]
- 夸克网盘：👉[[链接](https://pan.quark.cn/s/53cacb8ffd02)] 提取码：SiTn
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Particulate Organic Carbon</div><img src='images/POCN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Monthly Average Phytoplankton, Organic detritus Particulate Organic Carbon Concentrations in the East China Sea (2022)** 

**东中国海浮游植物、碎屑颗粒有机碳月平均浓度数据集 (2022年)**

[**Introduction**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Monthly Average Remote Sensing Dataset of Phytoplankton and Organic Detritus POC in the East China Sea (2022), derived from Sentinel-3/OLCI and GOCI-Ⅱ fused remote sensing reflectance for the surface phytoplankton, particulate organic and total POC. The spatial resolution is 250 m, and the temporal resolution is monthly average. This dataset can be utilized for research on coastal carbon cycling, carbon storage, and related studies..
- 东中国海颗浮游植物、碎屑颗粒有机碳浓度月平均遥感数据集 (2022年)，提供东中国海表层浮游植物、碎屑颗粒有机碳和总颗粒有机碳浓度遥感产品。使用Sentinel-3/OLCI和GOCI-Ⅱ融合后的遥感反射率进行反演计算。空间分辨率为250 m，时间分辨率为月平均。可以用于近岸碳循环、碳储量等相关研究。
- 
- [**Paper**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- [Disentangling Particle Composition to Improve Space-Based Quantification of POC in Optically-Complex Estuarine and Coastal Waters](https://ieeexplore.ieee.org/document/10353986), **IEEE Transactions on Geoscience and Remote Sensing**
- [**Product**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- OneDrive: 👉[[link](https://1drv.ms/f/s!AgOcOG0HOHXIggMSPe1TW0icHS4g?e=mn01Sp)]
- 夸克网盘：👉[[链接](https://pan.quark.cn/s/4f54b7a23fea)] 提取码：86nw
- 
</div>
</div>



# 🎖 Publications
- *2021.10* 测试文字. 
- *2021.09* 测试文字. 

# 📖 待定
- *2019.06 - 2022.04 (now)*, 测试文字
- *2015.09 - 2019.06*, 测试文字

# 💬 待定
- *2021.06*, 测试文字
- *2021.03*, 测试文字.  \| [\[video\]](https://github.com/)

# 💻 待定
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
