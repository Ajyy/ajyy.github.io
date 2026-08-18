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

Hi, I received my Ph.D. from the School of Data Science, The Chinese University of Hong Kong, Shenzhen, in July 2026, supervised by [Prof. Haizhou Li](https://colips.org/~eleliha/). Prior to that, I received my bachelor's degree from Southern University of Science and Technology, supervised by [Prof. Tom Ko](https://tomkocse.github.io/). My research interests include speech large language models, automatic speech recognition, speech pre-training, speaker diarization, and speech separation. My work has been published at international AI conferences and journals including TASLP, NeurIPS, ICLR, ACL, EMNLP, and ICASSP. <a href='https://scholar.google.com/citations?user=eUiG0O0AAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fajyy%2Fajyy.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>


# 📖 Education
- *2022.09 - 2026.07*, Ph.D., The Chinese University of Hong Kong, Shenzhen.
- *2024.01 - 2025.01*, Visiting Student, National University of Singapore.
- *2016.09 - 2020.06*, B.Eng, Southern University of Science and Technology.
- *2018.09 - 2019.05*, Visiting Student, the University of Edinburgh.

# 💻 Internships
- *2025.05 - 2025.11*, Full-Time Research Scientist Intern, Meta Superintelligence Labs (formerly GenAI), Speech Team. Conducted research on speech large language models and full-duplex spoken dialogue systems.
- *2024.03 - 2025.05*, Full-Time Intern, ByteDance Data Department (remote). Conducted research on speech large language models and spoken dialogue understanding, mentored by [Dr. Xiaohai Tian](https://scholar.google.com/citations?user=6gc45QcAAAAJ&hl=en).
- *2023.01 - 2024.02*, Part-Time Intern, ByteDance AI Lab (remote). Continued research on self-supervised speech representation learning, mentored by [Prof. Tom Ko](https://tomkocse.github.io/).
- *2022.06 - 2022.12*, Full-Time Intern, ByteDance AI Lab, Shenzhen. Worked on self-supervised speech representation learning and joint speech-and-text pre-training, mentored by [Prof. Tom Ko](https://tomkocse.github.io/).
- *2021.06 - 2022.04*, Full-Time Intern, [MSRA NLC group](https://www.microsoft.com/en-us/research/group/natural-language-computing/), Beijing. Conducted research on joint speech and text pre-training, mentored by [Dr. Shujie Liu](https://www.microsoft.com/en-us/research/people/shujliu/).
- *2019.06 - 2019.08*, Machine Learning Intern, Tencent, Shenzhen.

# 📝 Publications (\* denotes equal contribution)


- [Scaling Speech Tokenizers with Diffusion Autoencoders](https://arxiv.org/abs/2602.06602), Yuancheng Wang, Zhenyu Tang, Yun Wang, Arthur Hinsvark, Yingru Liu, Yinghao Li, Kainan Peng, **Junyi Ao**, Mingbo Ma, Mike Seltzer, Qing He, Xubo Liu, **ICLR 2026**

- [EchoMind: An Interrelated Multi-level Benchmark for Evaluating Empathetic Speech Language Models](https://arxiv.org/abs/2510.22758), Li Zhou, Lutong Yu, You Lyu, Yihang Lin, Zefeng Zhao, **Junyi Ao**, Yuhao Zhang, Benyou Wang, Haizhou Li, **ICLR 2026**

- [A Two-Stage Self-Supervised Speech Representation Learning for Acoustic, Phonetic and Semantic Modeling](https://ieeexplore.ieee.org/document/11447409/), Jingru Lin, **Junyi Ao**, Meng Ge, Mengling Feng, Haizhou Li, **IEEE/ACM Transactions on Audio, Speech, and Language Processing, 2026**

- [Leveraging Language Information for Target Language Extraction](https://arxiv.org/abs/2511.01652), Mehmet Sinan Yıldırım, Ruijie Tao, Wupeng Wang, **Junyi Ao**, Haizhou Li, **APSIPA ASC 2025**

- [USED: Universal Speaker Extraction and Diarization](https://arxiv.org/abs/2309.10674v2), **Junyi Ao**, Mehmet Sinan Yıldırım, Ruijie Tao, Meng Ge, Shuai Wang, Yanmin Qian, Haizhou Li, **IEEE/ACM Transactions on Audio, Speech, and Language Processing, 2025**

- [SD-Eval: A Benchmark Dataset for Spoken Dialogue Understanding Beyond Words](https://arxiv.org/pdf/2406.13340), **Junyi Ao**<sup>*</sup>, Yuancheng Wang<sup>*</sup>, Xiaohai Tian, Dekun Chen, Jun Zhang, Lu Lu, Yuxuan Wang, Haizhou Li, Zhizheng Wu, **NeurIPS Datasets and Benchmarks Track 2024** \| [![](https://img.shields.io/github/stars/amphionspace/SD-Eval?style=social&label=Code+Stars)](https://github.com/amphionspace/SD-Eval)

- [SA-WavLM: Speaker-Aware Self-Supervised Pre-Training for Mixture Speech](https://arxiv.org/abs/2407.02826), Jingru Lin, Meng Ge, **Junyi Ao**, Liqun Deng, Haizhou Li, **INTERSPEECH 2024**

- [Text-Guided HuBERT: Self-Supervised Speech Pre-Training via Generative Adversarial Networks](https://arxiv.org/abs/2402.15725), Duo Ma, Xianghu Yue, **Junyi Ao**, Xiaoxue Gao, Haizhou Li, **IEEE Signal Processing Letters, 2024**

- [CoBERT: Self-Supervised Speech Representation Learning Through Code Representation Learning](https://arxiv.org/abs/2210.04062), Chutong Meng<sup>*</sup>, **Junyi Ao**<sup>*</sup>, Tom Ko, Mingxuan Wang, Haizhou Li, **INTERSPEECH 2023** \| [![](https://img.shields.io/github/stars/mct10/CoBERT?style=social&label=Code+Stars)](https://github.com/mct10/CoBERT)

- [Self-Supervised Acoustic Word Embedding Learning via Correspondence Transformer Encoder](https://arxiv.org/abs/2307.09871), Jingru Lin, Xianghu Yue, **Junyi Ao**, Haizhou Li, **INTERSPEECH 2023**

- [token2vec: A Joint Self-Supervised Pre-Training Framework Using Unpaired Speech and Text](https://arxiv.org/abs/2210.16755), Xianghu Yue, **Junyi Ao**, Xiaoxue Gao, Haizhou Li, **ICASSP 2023**

- [SpeechUT: Bridging Speech and Text with Hidden-Unit for Encoder-Decoder Based Speech-Text Pre-Training](https://arxiv.org/abs/2210.03730), Ziqiang Zhang, Long Zhou, **Junyi Ao**, Shujie Liu, Lirong Dai, Jinyu Li, Furu Wei, **EMNLP 2022** \| [![](https://img.shields.io/github/stars/microsoft/SpeechT5?style=social&label=Code+Stars)](https://github.com/microsoft/SpeechT5/tree/main/SpeechUT)

- [Pre-Training Transformer Decoder for End-to-End ASR Model with Unpaired Speech Data](https://arxiv.org/abs/2203.17113), **Junyi Ao**<sup>*</sup>, Ziqiang Zhang<sup>*</sup>, Long Zhou, Shujie Liu, Haizhou Li, Tom Ko, Lirong Dai, Jinyu Li, Yao Qian, Furu Wei, **INTERSPEECH 2022** \| [![](https://img.shields.io/github/stars/microsoft/SpeechT5?style=social&label=Code+Stars)](https://github.com/microsoft/SpeechT5/tree/main/Speech2C)

- [LightHuBERT: Lightweight and Configurable Speech Representation Learning with Once-for-All Hidden-Unit BERT](https://arxiv.org/abs/2203.15610), Rui Wang, Qibing Bai, **Junyi Ao**, Long Zhou, Zhixiang Xiong, Zhihua Wei, Yu Zhang, Tom Ko, Haizhou Li, **INTERSPEECH 2022** \| [![](https://img.shields.io/github/stars/mechanicalsea/lighthubert?style=social&label=Code+Stars)](https://github.com/mechanicalsea/lighthubert)

- [SpeechT5: Unified-Modal Encoder-Decoder Pre-Training for Spoken Language Processing](https://aclanthology.org/2022.acl-long.393/), **Junyi Ao**<sup>*</sup>, Rui Wang<sup>*</sup>, Long Zhou<sup>*</sup>, Chengyi Wang, Shuo Ren, Yu Wu, Shujie Liu, Tom Ko, Qing Li, Yu Zhang, Zhihua Wei, Yao Qian, Jinyu Li, Furu Wei, **ACL 2022** \| [![](https://img.shields.io/github/stars/microsoft/SpeechT5?style=social&label=Code+Stars)](https://github.com/microsoft/SpeechT5)

- [The YiTrans Speech Translation System for the IWSLT 2022 Offline Shared Task](https://aclanthology.org/2022.iwslt-1.11/), Ziqiang Zhang<sup>*</sup>, **Junyi Ao**<sup>*</sup>, **Proceedings of the 19th International Conference on Spoken Language Translation, 2022**

- [Multi-View Self-Attention Based Transformer for Speaker Recognition](https://ieeexplore.ieee.org/document/9746639/), Rui Wang<sup>*</sup>, **Junyi Ao**<sup>*</sup>, Long Zhou, Shujie Liu, Zhihua Wei, Tom Ko, Qing Li, Yu Zhang, **ICASSP 2022**

- [Improving Attention-based End-to-end ASR by Incorporating an N-gram Neural Network](https://ieeexplore.ieee.org/abstract/document/9362055), **Junyi Ao**, Tom Ko, **ISCSLP 2021**

# 📜 Preprints

- [Solla: Towards a Speech-Oriented LLM That Hears Acoustic Context](https://arxiv.org/abs/2503.15338), **Junyi Ao**, Dekun Chen, Xiaohai Tian, Wenjie Feng, Jun Zhang, Lu Lu, Yuxuan Wang, Haizhou Li, Zhizheng Wu, **arXiv preprint arXiv:2503.15338, 2025**

- [Audio Deepfake Verification](https://arxiv.org/abs/2509.08476), Li Wang, **Junyi Ao**, Linyong Gan, Yuancheng Wang, Xueyao Zhang, Zhizheng Wu, **arXiv preprint arXiv:2509.08476, 2025**

- [Overview of the Amphion Toolkit (v0.2)](https://arxiv.org/abs/2501.15442), Jiaqi Li, Xueyao Zhang, Yuancheng Wang, Haorui He, Chaoren Wang, Li Wang, Huan Liao, **Junyi Ao**, Zeyu Xie, Yiqiao Huang, et al., **arXiv preprint arXiv:2501.15442, 2025**

- [The NUS-HLT System for the ICASSP 2024 ICMC-ASR Grand Challenge](https://arxiv.org/abs/2312.16002), Meng Ge, Yizhou Peng, Yidi Jiang, Jingru Lin, **Junyi Ao**, Mehmet Sinan Yildirim, Shuai Wang, Haizhou Li, Mengling Feng, **arXiv preprint arXiv:2312.16002, 2023**


# 🎖 Others

**Reviewer**
- IEEE Transactions on Multimedia (TMM)
- The International Conference on Learning Representations (ICLR)
- The Conference on Neural Information Processing Systems (NeurIPS)
- The Annual Meeting of the Association for Computational Linguistics (ACL)
- The Conference on Empirical Methods in Natural Language Processing (EMNLP)
- IEEE Signal Processing Letters (SPL)
- Computer Speech and Language
- The International Conference on Acoustics, Speech and Signal Processing (ICASSP)
- INTERSPEECH
- International Joint Conference on Neural Networks (IJCNN)
- National Conference on Man-Machine Speech Communication (NCMMSC)

**Teaching**
- Leading TA, DDA3020 Machine Learning, Spring 2023
- TA, CSC3100 Data Structures, Fall 2022
