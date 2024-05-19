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

I am a third-year PhD student in Department of Computer Science and Engineering at Shanghai Jiao Tong University (SJTU, 上海交通大学), supervised by Prof. [Junchi Yan (严骏驰)](https://thinklab.sjtu.edu.cn/).  I received my bachelor degree from SJTU in 2021, majoring in Computer Science. 

My research interest lies in deep learning for temporal data modeling, especially for time series and event sequences. If you would like to engage in an academic discussion on these topics, please contact me at [zhangyunhao@sjtu.edu.cn](zhangyunhao@sjtu.edu.cn).

I serve as the reviewer for conferences (NeurIPS 2023-2024, ICML 2023-2024, ICLR 2024) and journals (PR, TKDE).

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

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openreview.net/pdf?id=vSVLM2j9eie) \| [![](https://img.shields.io/github/stars/Thinklab-SJTU/Crossformer?style=social&label=Crossformer)](https://github.com/Thinklab-SJTU/Crossformer)
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

## Others

- ![](https://img.shields.io/badge/ICML--2023-darkblue) LinSATNet: the positive linear satisfiability neural networks 
<br> Runzhong Wang, **Yunhao Zhang**, Ziao Guo, Tianyi Chen, Xiaokang Yang, Junchi Yan. 
<br> [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://proceedings.mlr.press/v202/wang23at/wang23at.pdf) | [![](https://img.shields.io/github/stars/Thinklab-SJTU/LinSATNet?style=social&label=LinSATNet)](https://github.com/Thinklab-SJTU/LinSATNet)

- ![](https://img.shields.io/badge/TKDE-darkblue) Learning generative RNN-ODE for collaborative time-series and event sequence forecasting 
<br> Longyuan Li, Junchi Yan, **Yunhao Zhang**, Jihai Zhang, Jie Bao, Yaohui Jin, Xiaokang Yang
<br> [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://ieeexplore.ieee.org/abstract/document/9806345) 

- ![](https://img.shields.io/badge/AAAI--2021-darkblue) Synergetic learning of heterogeneous temporal sequences for multi-horizon probabilistic forecasting 
<br> Longyuan Li, Jihai Zhang, Junchi Yan, Yaohui Jin, **Yunhao Zhang**, Yanjie Duan, Guangjian Tian. 
<br> [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://ojs.aaai.org/index.php/AAAI/article/view/17023) 

# 🎖 Honors and Awards
- *2023* Graduate Fellowship of Yang Yuanqing Education Fund (杨元庆教育基金优秀硕士奖学金, 3 in CS Department)
- *2022* National Scholarship (国家奖学金)
- *2021* Undergraduate Honors Scholarship of Yang Yuanqing Education Fund (杨元庆教育基金优秀本科生卓越奖学金, 3 in CS Department)
- *2020* Shanghai Scholarship (上海市奖学金)
- *2020* Meritorious Winner of Mathematical Contest in Modeling (美国大学生数学建模竞赛一等奖, approximately top 8% of teams)

# 📖 Educations
- *2021.09 - Current*, PhD of Comupter Science and Technology, Shanghai Jiao Tong University (SJTU, 上海交通大学)
- *2017.09 - 2021.06*, Bachelor of Comupter Science and Technology, Shanghai Jiao Tong University (SJTU, 上海交通大学)
- *2014.09 - 2017.06*, Xi'an Gaoxin No.1 High School (西安高新第一中学)

# 💻 Internships
- *2021.06 - 2021.09*, Alibaba DAMO Academy, mentor: Dr. [Qingsong Wen (文青松)](https://sites.google.com/site/qingsongwen8/).