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

I am a Ph.D. candidate in the Department of Computer Science and Engineering at Shanghai Jiao Tong University (SJTU, 上海交通大学), supervised by Prof. [Junchi Yan (严骏驰)](https://thinklab.sjtu.edu.cn/).  I received my bachelor degree from SJTU in 2021, majoring in Computer Science. 

My research focuses on deep learning for temporal data modeling, partically time series and event sequences. I have
published five independent first-authored paper at top-tier conferences (ICLR-23&26,
ICML-24, IJCAI-21&22), with over **2,600 citations**. Notably, my ICLR-23 paper, ***[Crossformer](https://openreview.net/pdf?id=vSVLM2j9eie)***, has been cited by AI pioneers including Prof. **[Yoshua Bengio](https://yoshuabengio.org/)** ([NeurIPS-23](https://proceedings.neurips.cc/paper_files/paper/2023/file/070a57c5ef1e58cc90201b11d369b3c2-Paper-Conference.pdf)) and Prof. **[Jürgen Schmidhuber](https://people.idsia.ch/~juergen/)** ([ICLR-25](https://openreview.net/pdf?id=dmCGjPFVhF)).

I serve as a reviewer for leading conferences (NeurIPS 2023-2025, ICML 2023-2026, ICLR 2024-2026) and journals (TPAMI, JMLR, TMLR, TKDE). I was recognized as a Top Reviewer for NeurIPS-24&25

<span style="color:red">*Update: I am currently interning as a quantitative researcher at Jump Trading Shanghai. I am seeking for a 2026 summer internship or a 2027 full-time position in quantitative trading or time-series modeling. Feel free to reach out at [zhangyunhao@sjtu.edu.cn](zhangyunhao@sjtu.edu.cn).*</span>

# 📝 Publications

## Time Series Modeling

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv Preprint</div><img src='images/UniTok.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Time Series as Language: A Universal Tokenizer for
General-Purpose Time Series Foundation Models \\
**Yunhao Zhang**, Ruiying Qi, Jiale Zheng, Jianfeng Zhang, Lujia Pan, Junchi Yan
- We present UniTok, a universal time series tokenizer that transforms time series into discrete tokens, and UniTok-FM, an LLM-style foundation model pretrained via next-token prediction for training-free in-context forecasting, generation, and classification.
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://arxiv.org/pdf/2606.09861) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR-2026</div><img src='images/MMPD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

MMPD: Diverse Time Series Forecasting via Multi-Mode Patch Diffusion Loss \\
**Yunhao Zhang**, Wenyao Hu, Jiale Zheng, Lujia Pan, Junchi Yan
- A loss for patch-based time series forecasting backbones to model complex future distributions, enabling them to generate multiple diverse predictions with corresponding probabilities.
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openreview.net/pdf?id=NEUgHT8dvH) \| [![](https://img.shields.io/github/stars/Thinklab-SJTU/MMPD?style=social&label=MMPD)](https://github.com/Thinklab-SJTU/MMPD) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML-2024</div><img src='images/UP2ME.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

UP2ME: Univariate Pre-training to Multivariate Fine-tuning as
a General-purpose Framework for Multivariate Time Series Analysis \\
**Yunhao Zhang**, Minghao Liu, Shengyang Zhou, Junchi Yan
- A general-purpose framework for multivariate time series analysis: univariate pre-training followed by multivariate fine-tuning.
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openreview.net/pdf?id=aR3uxWlZhX) \| [![](https://img.shields.io/github/stars/Thinklab-SJTU/UP2ME?style=social&label=UP2ME)](https://github.com/Thinklab-SJTU/UP2ME) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR-2023(Oral)</div><img src='images/crossformer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Crossformer: Transformer utilizing cross-dimension dependency for multivariate time series forecasting \\
**Yunhao Zhang**, Junchi Yan
- A Transformer that explicitly utilizes cross-dimension(cross-channel) dependency for multivariate time series forecasting.

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openreview.net/pdf?id=vSVLM2j9eie) \| [![](https://img.shields.io/github/stars/Thinklab-SJTU/Crossformer?style=social&label=Crossformer)](https://github.com/Thinklab-SJTU/Crossformer) | <strong><span class='show_paper_citations' data='LBpsK-UAAAAJ:Tyk-4Ss8FVUC'></span></strong>
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
- *2025.07 - 2026.01*, Huawei Noah’s Ark Laboratory, mentor: Dr. [Lujia Pan (潘璐伽)](https://scholar.google.com/citations?hl=zh-CN&user=qnUAFa8AAAAJ) and Dr. [Jiale Zheng (郑嘉乐)](https://scholar.google.com/citations?user=9l2vE2sAAAAJ&hl=zh-CN).
- *2026.04 - 2026.07*, Jump Trading Shanghai.