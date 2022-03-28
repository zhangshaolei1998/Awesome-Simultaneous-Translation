# Papers by Categories
We divide the papers related to simultaneous translation into the following categories according to their motivation:
- **Towards Translation Policy**
  - Fixed policy
  - Adaptive policy
  - Segmentation policy

- **Towards Limited Source**
  - Introducing future information
  - Introducing multimodal information

- **Towards Data Improvement**
- **Towards Evaluation**
- **Others**

## 1 Towards Translation Policy

### 1.1 Fixed Policy

- Incremental Decoding and Training Methods for Simultaneous Translation in Neural Machine Translation. *NAACL 2018*. [[PDF](https://aclanthology.org/N18-2079)] [[Code](https://github.com/fdalvi/seq2seq-attn-stream)]

- STACL: Simultaneous Translation with Implicit Anticipation and Controllable Latency using Prefix-to-Prefix Framework. *ACL 2019*. [[PDF](https://aclanthology.org/P19-1289)]

- SimulSpeech: End-to-End Simultaneous Speech to Text Translation. *ACL 2020*. [[PDF](https://aclanthology.org/2020.acl-main.350)]

- Fluent and Low-latency Simultaneous Speech-to-Speech Translation with Self-adaptive Training. *EMNLP 2020 findings*. [[PDF](https://aclanthology.org/2020.findings-emnlp.349)]

- Efficient Wait-k Models for Simultaneous Machine Translation. *InterSpeech 2020*. [[PDF](http://www.interspeech2020.org/index.php?m=content&c=index&a=show&catid=282&id=611)] [[Code](https://github.com/elbayadm/attn2d)]

- RealTranS: End-to-End Simultaneous Speech Translation with Convolutional Weighted-Shrinking Transformer. *ACL 2021 findings*. [[PDF](https://aclanthology.org/2021.findings-acl.218)]

- Direct Simultaneous Speech-to-Text Translation Assisted by Synchronized Streaming ASR. *ACL 2021 findings*. [[PDF](https://aclanthology.org/2021.findings-acl.406)]

- Universal Simultaneous Machine Translation with Mixture-of-Experts Wait-k Policy. *EMNLP 2021*. [[PDF](https://aclanthology.org/2021.emnlp-main.581)] [[Code](https://github.com/ictnlp/MoE-Waitk)]

### 1.2 Adaptive Policy

- Simultaneous Machine Translation using Deep Reinforcement Learning. *ICML 2016*  [[PDF](http://docs.wixstatic.com/ugd/3195dc_538b63de8e2644b782db920c55f74650.pdf)]

- Can neural Machine Translation do Simultaneous Translation? *Arxiv 2016*. [[PDF](https://arxiv.org/pdf/1606.02012)]

- Online and Linear-Time Attention by Enforcing Monotonic Alignments. *ICML 2017*. [[PDF](https://arxiv.org/pdf/1704.00784.pdf)] [[Code](https://github.com/craffel/mad)]

- Learning to Translate in Real-time with Neural Machine Translation. *EACL 2017*.  [[PDF](https://aclanthology.org/E17-1099)] [[Code](https://github.com/yifanjun233/dl4mt-simul-trans)]

- Monotonic Chunkwise Attention. *ICLR 2018*. [[PDF](https://openreview.net/pdf?id=Hko85plCW)]  [[Code](https://github.com/craffel/mocha)] 

- Monotonic Infinite Lookback Attention for Simultaneous Machine Translation. *ACL 2019*. [[PDF](https://aclanthology.org/P19-1126)]

- Simultaneous Translation with Flexible Policy via Restricted Imitation Learning. *ACL 2019*. [[PDF](https://aclanthology.org/P19-1582)]

- Simpler and Faster Learning of Adaptive Policies for Simultaneous Translation. *EMNLP 2019*. [[PDF](https://aclanthology.org/D19-1137)]

- Simultaneous Neural Machine Translation using Connectionist Temporal Classification. *Arxiv 2019*. [[PDF](https://arxiv.org/pdf/1911.11933.pdf)]

- Simultaneous Translation Policies: From Fixed to Adaptive. *ACL 2020*. [[PDF](https://aclanthology.org/2020.acl-main.254)]

- Monotonic Multihead Attention. *ICLR 2020*.  [[PDF](https://openreview.net/pdf?id=Hyg96gBKPS)] [[Code](https://github.com/pytorch/fairseq/tree/6f847c8654d56b4d1b1fbacec027f47419426ddb/examples/simultaneous_translation)]

- A General Framework for Adaptation of Neural Machine Translation to Simultaneous Translation. *AACL 2020*. [[PDF](https://aclanthology.org/2020.aacl-main.23)]

- Cross Attention Augmented Transducer Networks for Simultaneous Translation. *EMNLP 2021*. [[PDF](https://aclanthology.org/2021.emnlp-main.4)] [[Code](https://github.com/danliu2/caat)]

- A Generative Framework for Simultaneous Machine Translation. *EMNLP 2021*. [[PDF](https://aclanthology.org/2021.emnlp-main.536)]

- Learning Coupled Policies for Simultaneous Machine Translation using Imitation Learning. *EACL 2021*. [[PDF](https://aclanthology.org/2021.eacl-main.233)] [[Code](https://github.com/Monash-NLP-ML-Group/arthur-eacl2021)]

- Modeling Dual Read/Write Paths for Simultaneous Machine Translation. *ACL 2022*. [[PDF](https://arxiv.org/pdf/2203.09163)] [[Code](https://github.com/ictnlp/Dual-Path)]

- Gaussian Multi-head Attention for Simultaneous Machine Translation. *ACL 2022 findings*. [[PDF](https://arxiv.org/pdf/2203.09072)] [[Code](https://github.com/ictnlp/GMA)]

### 1.3 Segmentation Policy

- Optimizing Segmentation Strategies for Simultaneous Speech Translation. *ACL 2014*. [[PDF](https://aclanthology.org/P14-2090)]

- Segmentation Strategies for Streaming Speech Translation. *NAACL 2014*. [[PDF](https://www.aclweb.org/anthology/N13-1023)]

- An Efficient and Effective Online Sentence Segmenter for Simultaneous Interpretation. *WAT 2016*. [[PDF](https://aclanthology.org/W16-4613)]

- Simultaneous Sentence Boundary Detection and Alignment with Pivot-based Machine Translation Generated Lexicons. *LREC 2016*. [[PDF](https://aclanthology.org/L16-1348)]

- Simultaneous Translation using Optimized Segmentation. *AMTA 2018*. [[PDF](https://aclanthology.org/W18-1815)]

- DuTongChuan: Context-aware Translation Model for Simultaneous Interpreting. *Arxiv 2019*. [[PDF](https://arxiv.org/pdf/1907.12984)]

- Learning Adaptive Segmentation Policy for Simultaneous Translation. *EMNLP 2020*. [[PDF](https://aclanthology.org/2020.emnlp-main.178)]

- Direct Segmentation Models for Streaming Speech Translation. *EMNLP 2020*. [[PDF](https://aclanthology.org/2020.emnlp-main.206.pdf)] [[Code](https://github.com/jairsan/Speech_Translation_Segmenter)]

- Simultaneous Neural Machine Translation with Constituent Label Prediction. *WMT 2021*. [[PDF](https://aclanthology.org/2021.wmt-1.120)]

- Translation-based Supervision for Policy Generation in Simultaneous Neural Machine Translation. *EMNLP 2021*. [[PDF](https://aclanthology.org/2021.emnlp-main.130)] [[Code](https://github.com/sfu-natlang/supervised-simultaneous-mt)]

- Impact of Encoding and Segmentation Strategies on End-to-End Simultaneous Speech Translation. *Interspeech 2021*. [[PDF](https://arxiv.org/pdf/2104.14470)]

## 2 Towards Limited Source

### 2.1 Introducing Future Information

- Don't Until the Final Verb Wait: Reinforcement Learning for Simultaneous Machine Translation. *EMNLP 2014*. [[PDF](https://aclanthology.org/D14-1140)]

- Syntax-based Simultaneous Translation through Prediction of Unseen Syntactic Constituents. *ACL 2015*. [[PDF](https://aclanthology.org/P15-1020)]

- Prediction Improves Simultaneous Neural Machine Translation. *EMNLP 2018*. [[PDF](https://aclanthology.org/D18-1337)] [[Code](https://github.com/ashkanalinejad/Real-time-translator)]

- Lost in Interpretation: Predicting Untranslated Terminology in Simultaneous Interpretation. *NAACL 2019*. [[PDF](https://aclanthology.org/N19-1010)] [[Code](https://github.com/nvog/lost-in-interpretation)]

- Future-Guided Incremental Transformer for Simultaneous Translation. *AAAI 2021*. [[PDF](https://arxiv.org/pdf/2012.12465.pdf)]

- Learning to Use Future Information in Simultaneous Translation. *Arxiv 2021* [[PDF](https://arxiv.org/pdf/2007.05290)]

- Reducing Position Bias in Simultaneous Machine Translation with Length-Aware Framework. *ACL 2022*. [[PDF](https://arxiv.org/pdf/2203.09053)]

### 2.2 Introducing Multimodal Information

- Towards Multimodal Simultaneous Neural Machine Translation. *WMT 2020*. [[PDF](https://aclanthology.org/2020.wmt-1.70)] [[Code](https://github.com/toshohirasawa/mst)]

- Simultaneous Machine Translation with Visual Context. *EMNLP 2020*. [[PDF](https://aclanthology.org/2020.emnlp-main.184)] [[Code](https://github.com/ImperialNLP/pysimt)]

- Studying The Impact Of Document-level Context On Simultaneous Neural Machine Translation. *Machine Translation 2021*. [[PDF](https://aclanthology.org/2021.mtsummit-research.17)]

- Beyond Sentence-Level End-to-End Speech Translation: Context Helps. *ACL 2021*. [[PDF](https://aclanthology.org/2021.acl-long.200)] [[Code](https://github.com/bzhangGo/zero)]

- Exploiting Multimodal Reinforcement Learning for Simultaneous Machine Translation. *EACL 2021*. [[PDF](https://aclanthology.org/2021.eacl-main.281)] [[Code](https://github.com/ImperialNLP/pysimt)]

- Visualization: the missing factor in Simultaneous Speech Translation. *CLIC-it 2021*. [[PDF](http://ceur-ws.org/Vol-3033/paper22.pdf)]

## 3 Towards Data Improvement

- Collection of a Simultaneous Translation Corpus for Comparative Analysis. *IREC 2014*. [[PDF](http://www.lrec-conf.org/proceedings/lrec2014/pdf/162_Paper.pdf)]

- Towards Simultaneous Interpreting: the Timing of Incremental Machine Translation and Speech Synthesis. *IWSLT 2014*. [[PDF](https://aclanthology.org/2014.iwslt-papers.2)]

- Syntax-based Rewriting for Simultaneous Machine Translation. *EMNLP 2015*. [[PDF](https://aclanthology.org/D15-1006)]

- Interpretese vs. Translationese: The Uniqueness of Human Strategies in Simultaneous Interpretation. *NAACL 2016*. [[PDF](https://aclanthology.org/N16-1111)] [[Code](https://github.com/hhexiy/interpretese)]

- Monotonic Simultaneous Translation with Chunk-wise Reordering and Refinement. *WMT2021*. [[PDF](https://aclanthology.org/2021.wmt-1.119)]

- Improving Simultaneous Translation by Incorporating Pseudo-References with Fewer Reorderings. *EMNLP 2021*. [[PDF](https://aclanthology.org/2021.emnlp-main.473)]

- It Is Not As Good As You Think! Evaluating Simultaneous Machine Translation on Interpretation Data. *EMNLP 2021*. [[PDF](https://aclanthology.org/2021.emnlp-main.537)] [[Code](https://github.com/mingzi151/InterpretationData)]

## 4 Towards Evaluation

- Automatic Estimation of Simultaneous Interpreter Performance. *ACL 2018*. [[PDF](https://aclanthology.org/P18-2105)] [[Code](https://github.com/craigastewart/qe_sim_interp)]

- Statistical Analysis of Missing Translation in Simultaneous Interpretation Using A Large-scale Bilingual Speech Corpus. *LREC 2018*. [[PDF](https://aclanthology.org/L18-1676)]

- Thinking Slow about Latency Evaluation for Simultaneous Machine Translation. *Arxiv 2019*. [[PDF](https://arxiv.org/pdf/1906.00048.pdf)]

- SIMULEVAL: An Evaluation Toolkit for Simultaneous Translation. *EMNLP 2020*. [[PDF](https://aclanthology.org/2020.emnlp-demos.19)] [[Code](https://github.com/facebookresearch/SimulEval)]

- Stream-level Latency Evaluation for Simultaneous Machine Translation. *EMNLP 2021 findings*. [[PDF](https://aclanthology.org/2021.findings-emnlp.58)] [[Code](https://github.com/jairsan/Stream-level_Latency_Evaluation_for_Simultaneous_Machine_Translation)]

## 5 Others

- Automated Simultaneous Interpretation: Hints of a Cognitive Framework for Machine Translation. *HyTra 2015*. [[PDF](https://aclanthology.org/W15-4106)]

- A Prototype Automatic Simultaneous Interpretation System. *COLING 2016*. [[PDF](https://aclanthology.org/C16-2007)]

- KIT Lecture Translator: Multilingual Speech Translation with One-Shot Learning. *COLING 2018*. [[PDF](https://aclanthology.org/C18-2020)]

- Speculative Beam Search for Simultaneous Translation. *EMNLP 2019*. [[PDF](https://aclanthology.org/D19-1144)]

- Opportunistic Decoding with Timely Correction for Simultaneous Translation. *ACL 2020*. [[PDF](https://aclanthology.org/2020.acl-main.42)]

- Incremental Text-to-Speech Synthesis with Prefix-to-Prefix Framework. *EMNLP 2020 findings*. [[PDF](https://aclanthology.org/2020.findings-emnlp.346)]

- SimulMT to SimulST: Adapting Simultaneous Text Translation to End-to-End Simultaneous Speech Translation. *AACL 2020*. [[PDF](https://aclanthology.org/2020.aacl-main.58)] [[Code](https://github.com/pytorch/fairseq)]

- Re-Translation Strategies For Long Form, Simultaneous, Spoken Language Translation. *ICASSP 2020*  [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9054585)]

- Presenting Simultaneous Translation in Limited Space. *Arxiv 2020*.  [[PDF](https://arxiv.org/pdf/2009.09016)]

- Simultaneous Speech-to-Speech Translation System with Neural Incremental ASR, MT, and TTS. *Arxiv 2020*.  [[PDF](https://arxiv.org/pdf/2011.04845.pdf)]

- Low Latency ASR for Simultaneous Speech Translation. *Arxiv 2020*.  [[PDF](https://arxiv.org/pdf/2003.09891)]

- Multilingual Simultaneous Neural Machine Translation. *ACL 2021 findings*. [[PDF](https://aclanthology.org/2021.findings-acl.420)]

- MiSS: An Assistant for Multi-Style Simultaneous Translation. *EMNLP 2021 Demo*. [[PDF](https://aclanthology.org/2021.emnlp-demo.1)]

- An Empirical Study Of End-To-End Simultaneous Speech Translation Decoding Strategies. *ICASSP 2021* [[PDF](https://arxiv.org/pdf/2103.03233.pdf)]

- Streaming Simultaneous Speech Translation With Augmented Memory Transformer. *ICASSP 2021* [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9414897)]

- UniST: Unified End-to-end Model for Streaming and Non-streaming Speech Translation. *Arxiv 2021*. [[PDF](https://arxiv.org/pdf/2109.07368.pdf)]

- Faster Re-translation Using Non-Autoregressive Model For Simultaneous Neural Machine Translation. *Arxiv 2021*. [[PDF](https://arxiv.org/pdf/2012.14681)]

- Simultaneous Multi-Pivot Neural Machine Translation. *Arxiv 2021*. [[PDF](https://arxiv.org/pdf/2104.07410)]

- Full-Sentence Models Perform Better in Simultaneous Translation Using the Information Enhanced Decoding Strategy. *Arxiv 2021*. [[PDF](https://arxiv.org/pdf/2105.01893)]

- Decision Attentive Regularization to Improve Simultaneous Speech Translation Systems. *Arxiv 2021*. [[PDF](https://arxiv.org/pdf/2110.15729)]

- Direct Simultaneous Speech-to-Speech Translation with Variational Monotonic Multihead Attention. *Arxiv 2021*. [[PDF](https://arxiv.org/pdf/2110.15729)]

- From Simultaneous to Streaming Machine Translation by Leveraging Streaming History. *ACL 2022*. [[PDF](https://arxiv.org/pdf/2203.02459)] 