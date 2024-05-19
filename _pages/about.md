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

I am a third-year PhD student in Department of Computer Science and Engineering at Shanghai Jiao Tong University (SJTU, 上海交通大学), supervised by Prof. [Junchi Yan (严骏驰)](https://thinklab.sjtu.edu.cn/).  I received my bachelor degree from SJTU in 2021, majoring in Computer Science. I also worked as a research intern at Alibaba DAMO Academy.

My research interest lies in deep learning for temporal data modeling, especially for time series and event sequences. If you would like to engage in an academic discussion on these topics, please contact me at [zhangyunhao@sjtu.edu.cn](zhangyunhao@sjtu.edu.cn).

# 🔥 News
- *2024.05*: &nbsp;🎉🎉 One paper on time series pre-training and fine-tuning was accepted by ICML-2024!

# 📝 Publications 

## Time Series Modeling

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML-2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

UP2ME: Univariate Pre-training to Multivariate Fine-tuning as
a General-purpose Framework for Multivariate Time Series Analysis \\
**Yunhao Zhang**, Minghao Liu, Shengyang Zhou, Junchi Yan
- A general-purpose framework for multivariate time series analysis: univariate pre-training followed by multivariate fine-tuning.


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR-2023(oral)</div><img src='images/crossformer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Crossformer: Transformer utilizing cross-dimension dependency for multivariate time series forecasting \\
**Yunhao Zhang**, Junchi Yan
- A Transformer that explicitly utilizes cross-dimension(cross-channel) dependency for multivariate time series forecasting.

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openreview.net/pdf?id=vSVLM2j9eie) \| [![](https://img.shields.io/github/stars/walker-hyf/ECSS?style=social&label=Crossformer)](https://github.com/Thinklab-SJTU/Crossformer)
</div>
</div>

## Event Sequence Modeling

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI-2022</div><img src='images/NTPP-mix.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Learning Mixture of Neural Temporal Point Processes
for Multi-dimensional Event Sequence Clustering \\
**Yunhao Zhang**, Junchi Yan, Xiaolu Zhang, Jun Zhou, Xiaokang Yang
- A general framework that mixs multiple Neural Temporal Point Processes (NTTPs) for event sequence clustering.

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://www.ijcai.org/proceedings/2022/0523.pdf) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI-2021</div><img src='images/TPP-NRI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Neural Relation Inference for Multi-dimensional Temporal Point Processes via Message Passing Graph \\
**Yunhao Zhang**, Junchi Yan
- A neural relation inference model for multi-dimensional event sequences that discovers relations among different type of events. 

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://www.ijcai.org/proceedings/2021/0469.pdf) 
</div>
</div>


- `ICML-2023` LinSATNet: the positive linear satisfiability neural networks \\Runzhong Wang, **Yunhao Zhang**, Ziao Guo, Tianyi Chen, Xiaokang Yang, Junchi Yan. [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://proceedings.mlr.press/v202/wang23at/wang23at.pdf) | [![](https://img.shields.io/github/stars/walker-hyf/ECSS?style=social&label=LinSATNet)](https://github.com/Thinklab-SJTU/LinSATNet)

- `TKDE` Learning generative RNN-ODE for collaborative time-series and event sequence forecasting \\Longyuan Li, Junchi Yan, **Yunhao Zhang**, Jihai Zhang, Jie Bao, Yaohui Jin, Xiaokang Yang [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://ieeexplore.ieee.org/abstract/document/9806345) 