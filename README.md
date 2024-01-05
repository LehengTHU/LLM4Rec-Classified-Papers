<div align=center>

<h1>LLM for Recommendation</h1>

</div>

This repository maintains the latest paper list of large language model (LLM) for recommendation.

<p id="Catalogue"></p>  

## Catalogue 
- [Catalogue](#catalogue)
- [Survey](#survey)
- [Interpretation with LLM](#interpretation-with-llm)
- [Agent for Recommendation](#agent-for-recommendation)
  - [User Side](#user-side)
  - [Recommender Side](#recommender-side)
- [LLM as Recommender](#llm-as-recommender)
  - [ChatGPT4Rec (Early Explorations)](#chatgpt4rec-early-explorations)
  - [Full Rank](#full-rank)
  - [Industrial Application](#industrial-application)
  - [General](#general)


<p id="Survey"></p>  

## Survey

| Source | Time | Title                                                         | Group                 | Citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| arxiv | 202309 | [Large Language Models for Generative Recommendation: A Survey and Visionary Discussions](https://arxiv.org/pdf/2309.01157.pdf) |  Yongfeng Zhang  | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa1081c6fc6921d6b76d9ebda4d712333fd7bbbf5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Large-Language-Models-for-Generative-A-Survey-and-Li-Zhang/a1081c6fc6921d6b76d9ebda4d712333fd7bbbf5) |
| arxiv | 202307 | [When Large Language Models Meet Personalization: Perspectives of Challenges and Opportunities](https://arxiv.org/pdf/2307.16376.pdf) |  Enhong Chen           | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7d46a13a1edd02dd6ae2b9f713e6f91ea001dfb4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/When-Large-Language-Models-Meet-Personalization%3A-of-Chen-Liu/7d46a13a1edd02dd6ae2b9f713e6f91ea001dfb4) |
| arxiv | 202307 | [Recommender Systems in the Era of Large Language Models (LLMs)](https://arxiv.org/pdf/2307.02046.pdf) |     Qing Li  | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa35f1315e91513ff0bec0c488fe175214fd9636c%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Recommender-Systems-in-the-Era-of-Large-Language-Fan-Zhao/a35f1315e91513ff0bec0c488fe175214fd9636c) |
| arxiv | 202306 | [How Can Recommender Systems Benefit from Large Language Models: A Survey](https://arxiv.org/pdf/2306.05817.pdf)  |     Ruiming Tang             | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbac54736112098616f0e1c90435888ef3e119d32%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/How-Can-Recommender-Systems-Benefit-from-Large-A-Lin-Dai/bac54736112098616f0e1c90435888ef3e119d32) |
| arxiv | 202305 | [A Survey on Large Language Models for Recommendation](https://arxiv.org/pdf/2305.19860.pdf)  | Enhong Chen                  | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb486982fa7c68a8a08df1111ba9607119419c488%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/A-Survey-on-Large-Language-Models-for-Wu-Zheng/b486982fa7c68a8a08df1111ba9607119419c488) |

<p id="Interpretation-with-LLM"></p>

## Interpretation with LLM

| Source | Name | Title                                                         | Group                 | Citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| arxiv 202311 | RecExplainer | [RecExplainer: Aligning Large Language Models for Recommendation Model Interpretability](https://arxiv.org/pdf/2311.10947.pdf) | Xing Xie                 | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd357a811d8ee0e2537c2987564df5c13d59ec02d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/RecExplainer%3A-Aligning-Large-Language-Models-for-Lei-Lian/d357a811d8ee0e2537c2987564df5c13d59ec02d) |
| arxiv 202310 | RecInterpreter | [Large Language Model Can Interpret Latent Space of Sequential Recommender](https://arxiv.org/pdf/2310.20487.pdf) | Xiangnan He                  | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F984583e8380fc8af8e20f32ed6ad9d7bc4888c6c%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Large-Language-Model-Can-Interpret-Latent-Space-of-Yang-Wu/984583e8380fc8af8e20f32ed6ad9d7bc4888c6c) |
| TOIS 2023 | PEPLER | [Personalized prompt learning for explainable recommendation](https://arxiv.org/pdf/2202.07371.pdf) |  Yongfeng Zhang           | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8498daeeb893870524ffaa63086f8528795003d4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Personalized-Prompt-Learning-for-Explainable-Li-Zhang/8498daeeb893870524ffaa63086f8528795003d4) |


<p id="Agent-for-Recommendation"></p>

## Agent for Recommendation

<p id="User-Side"></p>

### User Side

| Source | Name | Title                                                         | Group                 | Citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| arxiv 202310 | Agent4Rec | [On Generative Agents in Recommendation](https://arxiv.org/pdf/2310.10108.pdf) | Xiang Wang                  | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F489a31c4b5d09d7bd3788962f7dd20671f557000%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/On-Generative-Agents-in-Recommendation-Zhang-Sheng/489a31c4b5d09d7bd3788962f7dd20671f557000) |
| arxiv 202306 | RecAgent | [When Large Language Model based Agent Meets User Behavior Analysis: A Novel User Simulation Paradigm](https://arxiv.org/pdf/2306.02552.pdf) |  Xu Chen           | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F773d8eb9715847f279cc55386080208d1e84cdc5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/When-Large-Language-Model-based-Agent-Meets-User-A-Wang-Zhang/773d8eb9715847f279cc55386080208d1e84cdc5) |


<p id="Recommender-Side"></p>

### Recommender Side

| Source | Name | Title                                                         | Group                 | Citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| arxiv 202310 | AgentCF | [AgentCF: Collaborative Learning with Autonomous Language Agents for Recommender Systems](https://arxiv.org/pdf/2310.09233.pdf) | Xin Zhao & Ji-rong Wen                 | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F44576a2c6337f41019f29b055d8c7f7f5891be92%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/AgentCF%3A-Collaborative-Learning-with-Autonomous-for-Zhang-Hou/44576a2c6337f41019f29b055d8c7f7f5891be92) |
| arxiv 202308 | RecMind | [RecMind: Large Language Model Powered Agent For Recommendation](https://arxiv.org/pdf/2308.14296.pdf) |  Amazon           | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F26059f871eea2ef9aeeda228ebd40a69b61ab65c%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/RecMind%3A-Large-Language-Model-Powered-Agent-For-Wang-Jiang/26059f871eea2ef9aeeda228ebd40a69b61ab65c) |
| arxiv 202308 | InteRecAgent | [Recommender AI Agent: Integrating Large Language Models for Interactive Recommendations](https://arxiv.org/pdf/2308.16505.pdf) | Microsoft Xing Xie                 | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc237a22698223e4060d83027f399f4fb2aa24291%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Recommender-AI-Agent%3A-Integrating-Large-Language-Huang-Lian/c237a22698223e4060d83027f399f4fb2aa24291) |





<p id="General"></p>

## LLM as Recommender

<p id="Freezed-LLM"></p>  

### ChatGPT4Rec (Early Explorations)

| Source | Name | Title                                                         | Group                 | Citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| RecSys 2023 | N/A | [Uncovering ChatGPT's Capabilities in Recommender Systems](https://arxiv.org/pdf/2305.02182.pdf) |     Chen Gao & Jun Xu             | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F450b5490cc653478c272be50aa986798df828a20%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Uncovering-ChatGPT%E2%80%99s-Capabilities-in-Recommender-Dai-Shao/450b5490cc653478c272be50aa986798df828a20) |
| arxiv 202306 | N/A | [A Preliminary Study of ChatGPT on News Recommendation: Personalization, Provider Fairness, Fake News](https://arxiv.org/pdf/2306.10702.pdf) |  Yongfeng Zhang  | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F17c36e4f1addd6ad3acd6e4bb7cc0e6156e5d790%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/A-Preliminary-Study-of-ChatGPT-on-News-Provider-Li-Zhang/17c36e4f1addd6ad3acd6e4bb7cc0e6156e5d790) |
| arxiv 202305 | N/A | [Large Language Models are Zero-Shot Rankers for Recommender Systems](https://arxiv.org/pdf/2305.08845.pdf) |     Qing Li  | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4683d3d6cb31111cf4499a199c0b036662b3eb32%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Large-Language-Models-are-Zero-Shot-Rankers-for-Hou-Zhang/4683d3d6cb31111cf4499a199c0b036662b3eb32) |
| arxiv 202304 | N/A | [Is ChatGPT a Good Recommender? A Preliminary Study](https://arxiv.org/pdf/2304.10149.pdf) | Alibaba                  | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fca7bd64d372e3bcb3f4633ca4a20291ff57de3c3%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Is-ChatGPT-a-Good-Recommender-A-Preliminary-Study-Liu-Liu/ca7bd64d372e3bcb3f4633ca4a20291ff57de3c3) |
| arxiv 202303 | Chat-REC | [Chat-REC: Towards Interactive and Explainable LLMs-Augmented Recommender System](https://arxiv.org/pdf/2303.14524.pdf) |  Enhong Chen           | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0cfdd655100055f234fd23ebecd915504b8e00e3%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Chat-REC%3A-Towards-Interactive-and-Explainable-Gao-Sheng/0cfdd655100055f234fd23ebecd915504b8e00e3) |

<p id="Full-Rank"></p>

### Full Rank
| Source | Name | Title                                                         | Group                 | Citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| arxiv 202312 | LC-Rec | [Adapting Large Language Models by Integrating Collaborative Semantics for Recommendation](https://arxiv.org/pdf/2311.09049.pdf) |  Xin Zhao & Jirong Wen               | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9d2c9a7c3ff8f760b43fdd6a7082069a467c8956%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Adapting-Large-Language-Models-by-Integrating-for-Zheng-Hou/9d2c9a7c3ff8f760b43fdd6a7082069a467c8956) |
| arxiv 202310 | TransRec | [A Multi-facet Paradigm to Bridge Large Language Model and Recommendation](https://arxiv.org/pdf/2310.06491v1.pdf) | Tat-Seng Chua                | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6887b37bab9bc67910e435c13d0ca545da4dd3ba%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/A-Multi-facet-Paradigm-to-Bridge-Large-Language-and-Lin-Wang/6887b37bab9bc67910e435c13d0ca545da4dd3ba) |
| arxiv 202308 | BIGRec | [A Bi-Step Grounding Paradigm for Large Language Models in Recommendation Systems](https://arxiv.org/pdf/2308.08434.pdf) | Xiangnan He                | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Faae1d88c70cf18ef6aa23693a4dce8204e22d087%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/A-Bi-Step-Grounding-Paradigm-for-Large-Language-in-Bao-Zhang/aae1d88c70cf18ef6aa23693a4dce8204e22d087) |

### Industrial Application
| Source | Name | Title                                                         | Group                 | Citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| arxiv 202308 | CTRL | [CTRL: Connect Collaborative and Language Model for CTR Prediction](https://arxiv.org/pdf/2306.02841.pdf) | Ruiming Tang                | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8120b21c146bd96d82add2b5af54f2673d9d437c%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/CTRL%3A-Connect-Collaborative-and-Language-Model-for-Li-Chen/8120b21c146bd96d82add2b5af54f2673d9d437c) |
| arxiv 202305 | M6-Rec | [M6-Rec: Generative Pretrained Language Models are Open-Ended Recommender Systems](https://arxiv.org/pdf/2205.08084.pdf) | Alibaba                 | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fcbf3bf8f541f5b446c59c8deacbcc18527768c75%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/M6-Rec%3A-Generative-Pretrained-Language-Models-are-Cui-Ma/cbf3bf8f541f5b446c59c8deacbcc18527768c75) |


### General
| Source | Name | Title                                                         | Group                 | Citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| WSDM 2024 | LLMRec | [LLMRec: Large Language Models with Graph Augmentation for Recommendation](https://arxiv.org/pdf/2311.00423.pdf) | Chao Huang                | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5aa3b1009955ce2c8f896e0d5e94e06155ef1e43%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/LLMRec%3A-Large-Language-Models-with-Graph-for-Wei-Ren/5aa3b1009955ce2c8f896e0d5e94e06155ef1e43) |
| RecSys 2023 | TALLRec | [TALLRec: An Effective and Efficient Tuning Framework to Align Large Language Model with Recommendation](https://arxiv.org/pdf/2305.00447.pdf) |  Xiangnan He                | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3487c12512fa41d3a4d64f00cb842525a8590ad3%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/TALLRec%3A-An-Effective-and-Efficient-Tuning-to-Align-Bao-Zhang/3487c12512fa41d3a4d64f00cb842525a8590ad3) |
| ACL 2023 | UniTRec | [UniTRec: A Unified Text-to-Text Transformer and Joint Contrastive Learning Framework for Text-based Recommendation](https://arxiv.org/pdf/2305.15756.pdf) |  Kam-Fai Wong                | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb04952bddf52c1693b6792700cf9886e18fcdacb%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/UniTRec%3A-A-Unified-Text-to-Text-Transformer-and-for-Mao-Wang/b04952bddf52c1693b6792700cf9886e18fcdacb) |
| Gen-IR@ SIGIR2023 2023 | GPTRec | [Generative Sequential Recommendation with GPTRec](https://arxiv.org/pdf/2306.11114.pdf) |  Craig Macdonald                | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff23496d38da8f149127ef013f1604e1057aa2779%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Generative-Sequential-Recommendation-with-GPTRec-Petrov-Macdonald/f23496d38da8f149127ef013f1604e1057aa2779) |
| SIGIR-AP | IID | [How to Index Item IDs for Recommendation Foundation Models](https://arxiv.org/pdf/2305.06569.pdf) | Yongfeng Zhang                 | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd219717aae02ee08ecc36cf015763bf03cbb84e0%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/How-to-Index-Item-IDs-for-Recommendation-Foundation-Hua-Xu/d219717aae02ee08ecc36cf015763bf03cbb84e0) |
| arxiv 202312 | RecPrompt | [RecPrompt: A Prompt Tuning Framework for News Recommendation Using Large Language Models](https://arxiv.org/pdf/2312.10463.pdf) |  Irene Li               | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb9987c7e009caca3005b53bedb26c8d5484eb6ed%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/RecPrompt%3A-A-Prompt-Tuning-Framework-for-News-Using-Liu-Yang/b9987c7e009caca3005b53bedb26c8d5484eb6ed) |
| arxiv 202312 | RecRanker | [RecRanker: Instruction Tuning Large Language Model as Ranker for Top-k Recommendation](https://arxiv.org/pdf/2312.16018.pdf) |  Linqi Song               | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbbf159cfafbb37108bafdf9dcf4767643ae5d23d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/RecRanker%3A-Instruction-Tuning-Large-Language-Model-Luo-He/bbf159cfafbb37108bafdf9dcf4767643ae5d23d) |
| arxiv 202312 | LLaRA | [LLaRA: Aligning Large Language Models with Sequential Recommenders](https://arxiv.org/pdf/2312.02445.pdf) |  Xiangnan He               | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0e8dec431a62dea147139d7805ab3a0a97bf3857%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/LLaRA%3A-Aligning-Large-Language-Models-with-Liao-Li/0e8dec431a62dea147139d7805ab3a0a97bf3857) |
| arxiv 202311 | CLLM4Rec | [Collaborative Large Language Model for Recommender Systems](https://arxiv.org/pdf/2311.01343.pdf) |  LinkedIn               | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6531e6b6b8e43901a804fe3f03dd941c4e781718%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Collaborative-Large-Language-Model-for-Recommender-Zhu-Wu/6531e6b6b8e43901a804fe3f03dd941c4e781718) |
| arxiv 202306 | OpenP5 | [OpenP5: Benchmarking Foundation Models for Recommendation](https://arxiv.org/pdf/2306.11134.pdf) | Yongfeng Zhang                 | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2e351be5d4323bdf40f2ff6029bacb9dc5c8cc8c%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/OpenP5%3A-Benchmarking-Foundation-Models-for-Xu-Hua/2e351be5d4323bdf40f2ff6029bacb9dc5c8cc8c) |
| arxiv 202305 | PALR | [PALR: Personalization Aware LLMs for Recommendation](https://arxiv.org/pdf/2305.07622.pdf) | Amazon                 | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F60f8a7ac53585aa2c173219e97507d6d963864e7%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/PALR%3A-Personalization-Aware-LLMs-for-Recommendation-Chen-Jiang/60f8a7ac53585aa2c173219e97507d6d963864e7) |
| arxiv 202305 | InstructRec | [Recommendation as Instruction Following: A Large Language Model Empowered Recommendation Approach](https://arxiv.org/pdf/2305.07001.pdf) | Xin Zhao & Ji-rong Wen                 | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0383e049e98c9eedbc61be728d4ef037300bbedf%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Recommendation-as-Instruction-Following%3A-A-Large-Zhang-Xie/0383e049e98c9eedbc61be728d4ef037300bbedf) |
| arxiv 202304 | GPT4Rec | [GPT4Rec: A Generative Framework for Personalized Recommendation and User Interests Interpretation](https://arxiv.org/pdf/2304.03879.pdf) | Amazon                 | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F26f7785ef8da35820599799549152b9ef695dae2%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/GPT4Rec%3A-A-Generative-Framework-for-Personalized-Li-Zhang/26f7785ef8da35820599799549152b9ef695dae2) |
| arxiv 202304 | GeneRec | [Generative Recommendation: Towards Next-generation Recommender Paradigm](https://arxiv.org/pdf/2304.03516.pdf) | Xiangnan He                 | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6159549f986c63e160a678feef2130a2a4b93feb%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Generative-Recommendation%3A-Towards-Next-generation-Wang-Lin/6159549f986c63e160a678feef2130a2a4b93feb) |
| KDD 2022 | UniSRec | [Towards Universal Sequence Representation Learning for Recommender Systems](https://arxiv.org/pdf/2206.05941.pdf) | Xin Zhao & Ji-rong Wen                 | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdbb4e3592ad72a2667374c6ef7d259a42c74ccc6%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Towards-Universal-Sequence-Representation-Learning-Hou-Mu/dbb4e3592ad72a2667374c6ef7d259a42c74ccc6) |
| RecSys 2022 | P5 | [Recommendation as Language Processing (RLP): A Unified Pretrain, Personalized Prompt & Predict Paradigm (P5)](https://arxiv.org/pdf/2203.13366.pdf) |  Amazon           | [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F18e27c61ccc227fefc8a82b5732f08b6b41e0c84%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Recommendation-as-Language-Processing-(RLP)%3A-A-%26-Geng-Liu/18e27c61ccc227fefc8a82b5732f08b6b41e0c84) |




<!-- [![citation](https://img.shields.io/badge/dynamic/json?label=cite&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa1081c6fc6921d6b76d9ebda4d712333fd7bbbf5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Large-Language-Models-for-Generative-A-Survey-and-Li-Zhang/a1081c6fc6921d6b76d9ebda4d712333fd7bbbf5) -->


