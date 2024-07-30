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

Hi, I am a PhD student at the School of Data Science, the Chinese University of Hong Kong (Shenzhen), supervised by [Prof. Haizhou Li](https://colips.org/~eleliha/). Prior to that, I received my Bachelor Degree from Southern University of Science and Technology, supervised by [Prof. Tom Ko](https://tomkocse.github.io/). My research interests include automatic speech recognition, speech translation and speech pre-training. I have published several papers at the top international AI conferences such as ICASSP, INTERSPEECH, ACL and EMNLP. <a href='https://scholar.google.com/citations?user=eUiG0O0AAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fajyy%2Fajyy.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> 


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->


# 📖 Educations
- *2022.09 - now*, Ph.D., the Chinese University of Hong Kong (Shenzhen).
- *2016.09 - 2020.06*, B.Eng, Southern University of Science and Technology.
- *2018.09 - 2019.05*, Visiting Student, the University of Edinburgh.

# 💻 Internships
- *2021.06 - 2022.04*, [MSRA NLC group](https://www.microsoft.com/en-us/research/group/natural-language-computing/), Beijing, mentored by [Dr. Long Zhou](https://long-zhou.github.io/) and [Dr. Shujie Liu](https://www.microsoft.com/en-us/research/people/shujliu/).
- *2019.06 - 2019.08*, Tencent, Shenzhen.

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun -->

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

- [Text-guided HuBERT: Self-Supervised Speech Pre-training via Generative Adversarial Networks](https://arxiv.org/abs/2402.15725), Duo Ma, Xianghu Yue, **Junyi Ao**, Xiaoxue Gao, Haizhou Li
, **Signal Processing Letters**

- [SA-WavLM: Speaker-Aware Self-Supervised Pre-training for Mixture Speech](https://arxiv.org/abs/2407.02826), Jingru Lin, Meng Ge, **Junyi Ao**, Liqun Deng, Haizhou Li
, **INTERSPEECH 2024**

- [CoBERT: Self-Supervised Speech Representation Learning Through Code Representation Learning](https://arxiv.org/abs/2210.04062), Chutong Meng, **Junyi Ao**, Tom Ko, Mingxuan Wang, Haizhou Li, **INTERSPEECH 2023** \| [![](https://img.shields.io/github/stars/mct10/CoBERT?style=social&label=Code+Stars)](https://github.com/mct10/CoBERT)

- [Self-Supervised Acoustic Word Embedding Learning via Correspondence Transformer Encoder](https://arxiv.org/abs/2307.09871), Jingru Lin, Xianghu Yue, **Junyi Ao**, Haizhou Li, **INTERSPEECH 2023**

- [token2vec: A Joint Self-Supervised Pre-training Framework Using Unpaired Speech and Text](https://arxiv.org/abs/2210.16755), Xianghu Yue, **Junyi Ao**, Xiaoxue Gao, Haizhou Li, **ICASSP 2023**


- [Pre-Training Transformer Decoder for End-to-End ASR Model with Unpaired Speech Data](https://arxiv.org/abs/2203.17113), **Junyi Ao**, Ziqiang Zhang, Long Zhou, Shujie Liu, Haizhou Li, Tom Ko, Lirong Dai, Jinyu Li, Yao Qian, Furu Wei, **INTERSPEECH 2022** \| [![](https://img.shields.io/github/stars/microsoft/SpeechT5?style=social&label=Code+Stars)](https://github.com/microsoft/SpeechT5/tree/main/Speech2C)

- [SpeechT5: Unified-Modal Encoder-Decoder Pre-Training for Spoken Language Processing](https://aclanthology.org/2022.acl-long.393/), **Junyi Ao**, Rui Wang, Long Zhou, Chengyi Wang, Shuo Ren, Yu Wu, Shujie Liu, Tom Ko, Qing Li, Yu Zhang, Zhihua Wei, Yao Qian, Jinyu Li, Furu Wei, **ACL 2022** \| [![](https://img.shields.io/github/stars/microsoft/SpeechT5?style=social&label=Code+Stars)](https://github.com/microsoft/SpeechT5)

- [SpeechUT: Bridging Speech and Text with Hidden-Unit for Encoder-Decoder Based Speech-Text Pre-training](https://arxiv.org/abs/2210.03730), Ziqiang Zhang, Long Zhou, **Junyi Ao**, Shujie Liu, Lirong Dai, Jinyu Li, Furu Wei, **EMNLP 2022** \| [![](https://img.shields.io/github/stars/microsoft/SpeechT5?style=social&label=Code+Stars)](https://github.com/microsoft/SpeechT5/tree/main/SpeechUT)

- [LightHuBERT: Lightweight and Configurable Speech Representation Learning with Once-for-All Hidden-Unit BERT](https://arxiv.org/abs/2203.15610), Rui Wang, Qibing Bai, **Junyi Ao**, Long Zhou, Zhixiang Xiong, Zhihua Wei, Yu Zhang, Tom Ko, Haizhou Li, **INTERSPEECH 2022** \| [![](https://img.shields.io/github/stars/mechanicalsea/lighthubert?style=social&label=Code+Stars)](https://github.com/mechanicalsea/lighthubert)

- [The YiTrans Speech Translation System for IWSLT 2022 Offline Shared Task](https://aclanthology.org/2022.iwslt-1.11/), Ziqiang Zhang, **Junyi Ao**, Long Zhou, Shujie Liu, Furu Wei, Jinyu Li, **ACL@IWSLT 2022** \| [![](https://img.shields.io/github/stars/microsoft/SpeechT5?style=social&label=Code+Stars)](https://github.com/microsoft/SpeechT5/tree/main/YiTrans)

- [Multi-View Self-Attention Based Transformer for Speaker Recognition](https://ieeexplore.ieee.org/document/9746639/), Rui Wang, **Junyi Ao**, Long Zhou, Shujie Liu, Zhihua Wei, Tom Ko, Qing Li, Yu Zhang, **ICASSP 2022**

- [Improving Attention-based End-to-end ASR by Incorporating an N-gram Neural Network](https://ieeexplore.ieee.org/abstract/document/9362055), **Junyi Ao**, Tom Ko, **ISCSLP 2021**

# 📜 Preprints
- [SD-Eval: A Benchmark Dataset for Spoken Dialogue Understanding Beyond Words](https://arxiv.org/pdf/2406.13340), **Junyi Ao**, Yuancheng Wang, Xiaohai Tian, Dekun Chen, Jun Zhang, Lu Lu, Yuxuan Wang, Haizhou Li, Zhizheng Wu, **arXiv preprint arXiv:2406.13340** \| [![](https://img.shields.io/github/stars/amphionspace/SD-Eval?style=social&label=Code+Stars)](https://github.com/amphionspace/SD-Eval)

- [USED: Universal Speaker Extraction and Diarization](https://arxiv.org/abs/2309.10674v2), **Junyi Ao**, Mehmet Sinan Yıldırım, Ruijie Tao, Meng Ge, Shuai Wang, Yanmin Qian, Haizhou Li, **arXiv preprint arXiv:2309.10674**

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 🎖 Others

**Reviewer**
- Signal Processing Letters
- ICASSP
- INTERSPEECH

**Teaching**
- Leading TA, DDA3020 Machine Learning, Spring 2023
- TA, CSC3100 Data Structures, Fall 2022

