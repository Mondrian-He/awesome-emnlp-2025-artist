# EMNLP 2025 Main Conference Papers

**Summary:** 30 papers with extracted content:
- 📊 Total images: 14618
- 📋 Total tables: 17648
- 📄 Total files: 32266

*Note: Equations have been filtered out and are not included.*

---

# EMNLP 2025 Main Papers - Part 8 of 60

## 目录 (Table of Contents)

1. [Chain-of-Talkers (CoTalk): Fast Human Annotation of Dense Image Captions](#Chain-of-Talkers-CoTalk-Fast-Human-Annotation-of-Dense-Image-Captions)
2. [DecoupleSearch: Decouple Planning and Search via Hierarchical Reward Modeling](#DecoupleSearch-Decouple-Planning-and-Search-via-Hierarchical-Reward-Modeling)
3. [RewardDS: Privacy-Preserving Fine-Tuning for Large Language Models via Reward Driven Data Synthesis](#RewardDS-Privacy-Preserving-Fine-Tuning-for-Large-Language-Models-via-Reward-Driven-Data-Synthesis)
4. [Synergizing Multimodal Temporal Knowledge Graphs and Large Language Models for Social Relation Recognition](#Synergizing-Multimodal-Temporal-Knowledge-Graphs-and-Large-Language-Models-for-Social-Relation-Recognition)
5. [LegalSearchLM: Rethinking Legal Case Retrieval as Legal Elements Generation](#LegalSearchLM-Rethinking-Legal-Case-Retrieval-as-Legal-Elements-Generation)
6. [ChartMind: A Comprehensive Benchmark for Complex Real-world Multimodal Chart Question Answering](#ChartMind-A-Comprehensive-Benchmark-for-Complex-Real-world-Multimodal-Chart-Question-Answering)
7. [COLA: Collaborative Multi-Agent Framework with Dynamic Task Scheduling forGUIAutomation](#COLA-Collaborative-Multi-Agent-Framework-with-Dynamic-Task-Scheduling-forGUIAutomation)
8. [DASA-Trans-STM: Adaptive Efficient Transformer for Short Text Matching using Data Augmentation and Semantic Awareness](#DASA-Trans-STM-Adaptive-Efficient-Transformer-for-Short-Text-Matching-using-Data-Augmentation-and-Semantic-Awareness)
9. [Pruning the Paradox: HowCLIP’s Most Informative Heads Enhance Performance While Amplifying Bias](#Pruning-the-Paradox-HowCLIPs-Most-Informative-Heads-Enhance-Performance-While-Amplifying-Bias)
10. [CoLA: Compute-Efficient Pre-Training ofLLMs via Low-Rank Activation](#CoLA-Compute-Efficient-Pre-Training-ofLLMs-via-Low-Rank-Activation)
11. [TS-CLIP: Time Series Understanding byCLIP](#TS-CLIP-Time-Series-Understanding-byCLIP)
12. [MultiAgentESC: ALLM-based Multi-Agent Collaboration Framework for Emotional Support Conversation](#MultiAgentESC-ALLM-based-Multi-Agent-Collaboration-Framework-for-Emotional-Support-Conversation)
13. [Continuously SteeringLLMs Sensitivity to Contextual Knowledge with Proxy Models](#Continuously-SteeringLLMs-Sensitivity-to-Contextual-Knowledge-with-Proxy-Models)
14. [ProbingLLMWorld Models: Enhancing Guesstimation with Wisdom of Crowds Decoding](#ProbingLLMWorld-Models-Enhancing-Guesstimation-with-Wisdom-of-Crowds-Decoding)
15. [Recall with Reasoning: Chain-of-Thought Distillation for Mamba’s Long-Context Memory and Extrapolation](#Recall-with-Reasoning-Chain-of-Thought-Distillation-for-Mambas-Long-Context-Memory-and-Extrapolation)
16. [Scalable Data Synthesis through Human-like Cognitive Imitation and Data Recombination](#Scalable-Data-Synthesis-through-Human-like-Cognitive-Imitation-and-Data-Recombination)
17. [BeSimulator: A Large Language Model Powered Text-based Behavior Simulator](#BeSimulator-A-Large-Language-Model-Powered-Text-based-Behavior-Simulator)
18. [Too Consistent to Detect: A Study of Self-Consistent Errors inLLMs](#Too-Consistent-to-Detect-A-Study-of-Self-Consistent-Errors-inLLMs)
19. [pFedGPT: Hierarchically OptimizingLoRAAggregation Weights for Personalized FederatedGPTModels](#pFedGPT-Hierarchically-OptimizingLoRAAggregation-Weights-for-Personalized-FederatedGPTModels)
20. [QSpec: Speculative Decoding with Complementary Quantization Schemes](#QSpec-Speculative-Decoding-with-Complementary-Quantization-Schemes)
21. [Co-EvolvingLLMs and Embedding Models via Density-Guided Preference Optimization for Text Clustering](#Co-EvolvingLLMs-and-Embedding-Models-via-Density-Guided-Preference-Optimization-for-Text-Clustering)
22. [P-MMEval: A Parallel Multilingual Multitask Benchmark for Consistent Evaluation ofLLMs](#P-MMEval-A-Parallel-Multilingual-Multitask-Benchmark-for-Consistent-Evaluation-ofLLMs)
23. [SingleLLM, Multiple Roles: A Unified Retrieval-Augmented Generation Framework Using Role-Specific Token Optimization](#SingleLLM-Multiple-Roles-A-Unified-Retrieval-Augmented-Generation-Framework-Using-Role-Specific-Token-Optimization)
24. [TrInk: Ink Generation with Transformer Network](#TrInk-Ink-Generation-with-Transformer-Network)
25. [CalligraphicOCRforChinese Calligraphy Recognition](#CalligraphicOCRforChinese-Calligraphy-Recognition)
26. [When Audio and Text Disagree: Revealing Text Bias in Large Audio-Language Models](#When-Audio-and-Text-Disagree-Revealing-Text-Bias-in-Large-Audio-Language-Models)
27. [RESF: Regularized-Entropy-Sensitive Fingerprinting for Black-Box Tamper Detection of Large Language Models](#RESF-Regularized-Entropy-Sensitive-Fingerprinting-for-Black-Box-Tamper-Detection-of-Large-Language-Models)
28. [Model-based Large Language Model Customization as Service](#Model-based-Large-Language-Model-Customization-as-Service)
29. [Collab-Overcooked: Benchmarking and Evaluating Large Language Models as Collaborative Agents](#Collab-Overcooked-Benchmarking-and-Evaluating-Large-Language-Models-as-Collaborative-Agents)
30. [Improving Reasoning Capabilities in Small Models through Mixture-of-layers Distillation with Stepwise Attention on Key Information](#Improving-Reasoning-Capabilities-in-Small-Models-through-Mixture-of-layers-Distillation-with-Stepwise-Attention-on-Key-Information)

---


## Chain-of-Talkers (CoTalk): Fast Human Annotation of Dense Image Captions

### Images

![7a55c32a9d48c56dbb6b00438a9e9a9e02954a03a899eb829b5a7d0c817f04dd.jpg](../emnlp_results/220_Reasoning%20Model%20Unlearning_%20Forgetting%20Traces%2C%20Not%20Just%20Answers%2C%20While%20Preserving%20Reasoning%20Skills/images/7a55c32a9d48c56dbb6b00438a9e9a9e02954a03a899eb829b5a7d0c817f04dd.jpg)

![a050bb0ae1e8727fb2d95e2e03b0878792a502c2d0b2360e8edb6c4e86e31041.jpg](../emnlp_results/220_Reasoning%20Model%20Unlearning_%20Forgetting%20Traces%2C%20Not%20Just%20Answers%2C%20While%20Preserving%20Reasoning%20Skills/images/a050bb0ae1e8727fb2d95e2e03b0878792a502c2d0b2360e8edb6c4e86e31041.jpg)

![a8928a447c9925b699ac43331957c2eb1bdb20f93daaf670900429e1c0ca4b7f.jpg](../emnlp_results/220_Reasoning%20Model%20Unlearning_%20Forgetting%20Traces%2C%20Not%20Just%20Answers%2C%20While%20Preserving%20Reasoning%20Skills/images/a8928a447c9925b699ac43331957c2eb1bdb20f93daaf670900429e1c0ca4b7f.jpg)

![b4f0389e5827c6176f4b53dc221b9f89f0d5c005a49799326fbea595372b5ae5.jpg](../emnlp_results/220_Reasoning%20Model%20Unlearning_%20Forgetting%20Traces%2C%20Not%20Just%20Answers%2C%20While%20Preserving%20Reasoning%20Skills/images/b4f0389e5827c6176f4b53dc221b9f89f0d5c005a49799326fbea595372b5ae5.jpg)

![beaa60acc93756bbb239491f120e128da50d2bb91ad23d4ae3119ea328f2e905.jpg](../emnlp_results/220_Reasoning%20Model%20Unlearning_%20Forgetting%20Traces%2C%20Not%20Just%20Answers%2C%20While%20Preserving%20Reasoning%20Skills/images/beaa60acc93756bbb239491f120e128da50d2bb91ad23d4ae3119ea328f2e905.jpg)

![c91e1918197b3b1f4a3a48227ddbc37fbf6101676c6e755f13dfeae3e0874f0f.jpg](../emnlp_results/220_Reasoning%20Model%20Unlearning_%20Forgetting%20Traces%2C%20Not%20Just%20Answers%2C%20While%20Preserving%20Reasoning%20Skills/images/c91e1918197b3b1f4a3a48227ddbc37fbf6101676c6e755f13dfeae3e0874f0f.jpg)

### Tables

![36456537230452e483acffdbc8ac1c0d05de7c9ffce8c8fb5c2897b43d64d9bd.jpg](../emnlp_results/220_Reasoning%20Model%20Unlearning_%20Forgetting%20Traces%2C%20Not%20Just%20Answers%2C%20While%20Preserving%20Reasoning%20Skills/tables/36456537230452e483acffdbc8ac1c0d05de7c9ffce8c8fb5c2897b43d64d9bd.jpg)

![57f437faf99b581214b6bed630f6ca15ba60e7a69cc30676a5750b1a4e9aea36.jpg](../emnlp_results/220_Reasoning%20Model%20Unlearning_%20Forgetting%20Traces%2C%20Not%20Just%20Answers%2C%20While%20Preserving%20Reasoning%20Skills/tables/57f437faf99b581214b6bed630f6ca15ba60e7a69cc30676a5750b1a4e9aea36.jpg)

![5a4096b7586505f981b56c6acc1e9806f9811486afcb571f4c9787f8fca83187.jpg](../emnlp_results/220_Reasoning%20Model%20Unlearning_%20Forgetting%20Traces%2C%20Not%20Just%20Answers%2C%20While%20Preserving%20Reasoning%20Skills/tables/5a4096b7586505f981b56c6acc1e9806f9811486afcb571f4c9787f8fca83187.jpg)

## Chain-of-Talkers (CoTalk): Fast Human Annotation of Dense Image Captions


### Images

![107ade8d577113c07f6ecbe328e54ffdb1bc17938f514b29b3a0133210c610d5.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/images/107ade8d577113c07f6ecbe328e54ffdb1bc17938f514b29b3a0133210c610d5.jpg)

![33b754839ff7c005c66afbc9bf17843cd1eb978d6aea2504a8c9e054e8157909.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/images/33b754839ff7c005c66afbc9bf17843cd1eb978d6aea2504a8c9e054e8157909.jpg)

![41d5077003ade93c313d098788671c64f8cd2cef645aea11c097fa232cd38089.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/images/41d5077003ade93c313d098788671c64f8cd2cef645aea11c097fa232cd38089.jpg)

![9e4d5a9d598999bb6f6cdd883e876ae3f91d7aac6ad9acfe49cec21c48da4ce7.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/images/9e4d5a9d598999bb6f6cdd883e876ae3f91d7aac6ad9acfe49cec21c48da4ce7.jpg)

![a62ad9cf121c1e6654e1d0c991038b4d2e5e56779af413bb031140b01fa5551a.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/images/a62ad9cf121c1e6654e1d0c991038b4d2e5e56779af413bb031140b01fa5551a.jpg)

![bbd75cb4bf6482a86db13fbf439f4fd65a11209656a1a61b754853552a18058f.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/images/bbd75cb4bf6482a86db13fbf439f4fd65a11209656a1a61b754853552a18058f.jpg)

![c07164b881965791189eea59f6ab375494375ef5b99e0abae1c7859b779d0f09.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/images/c07164b881965791189eea59f6ab375494375ef5b99e0abae1c7859b779d0f09.jpg)

![c86708432ec6a3fce20cc10780f06a9ee6f513fb8793570acbd3bd4b3002ba02.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/images/c86708432ec6a3fce20cc10780f06a9ee6f513fb8793570acbd3bd4b3002ba02.jpg)

![d556af5fbd595c34bd6b38f95279b940a38cfd34e1cf39c5074bf48d523ca5c9.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/images/d556af5fbd595c34bd6b38f95279b940a38cfd34e1cf39c5074bf48d523ca5c9.jpg)

![efdedf7e8dcda873a29ca58d4c877104d8cd08e7f7df9fbee9c58ef3718782e5.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/images/efdedf7e8dcda873a29ca58d4c877104d8cd08e7f7df9fbee9c58ef3718782e5.jpg)

![f5aa2a725aba9a88ec9e2db9436ec8bcad9ce2cb5965bee94ac3bfc403e41ae3.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/images/f5aa2a725aba9a88ec9e2db9436ec8bcad9ce2cb5965bee94ac3bfc403e41ae3.jpg)

![fb48350afc14e32d53ca53c54ee6b4842435e4a40d89f147613d94c3bcd0424e.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/images/fb48350afc14e32d53ca53c54ee6b4842435e4a40d89f147613d94c3bcd0424e.jpg)

### Tables

![1996f35f066d706815dd5766561ac4e10e89abc7a87b1b2412392fd417a2ce8e.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/tables/1996f35f066d706815dd5766561ac4e10e89abc7a87b1b2412392fd417a2ce8e.jpg)

![1d27f2ac67ee496a7a4461491d6b443967a3a14bbe8bba71bae54375020f753e.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/tables/1d27f2ac67ee496a7a4461491d6b443967a3a14bbe8bba71bae54375020f753e.jpg)

![2917aa60a2948318ffcd4d94180e8cd1e40f64f2de8a5e8cc495ed6127d3a750.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/tables/2917aa60a2948318ffcd4d94180e8cd1e40f64f2de8a5e8cc495ed6127d3a750.jpg)

![597693f78bed23ff9118908328164877ae16eb364aa7f32c8229e9029dcccfd8.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/tables/597693f78bed23ff9118908328164877ae16eb364aa7f32c8229e9029dcccfd8.jpg)

![8bf48d2ebba73d819c38709f4f58543cd79b76c0a29a6fe551cfa18e7dbfaa19.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/tables/8bf48d2ebba73d819c38709f4f58543cd79b76c0a29a6fe551cfa18e7dbfaa19.jpg)

![a21f061bc84730704aa6e4efc50cfbafcd5de376f1fc46fd3ae3dbb964fe5ffa.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/tables/a21f061bc84730704aa6e4efc50cfbafcd5de376f1fc46fd3ae3dbb964fe5ffa.jpg)

![d56b0dabe0f6e848af1a7222dde8d3bc50f117443c09b0e9eeb1fbae9156475b.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/tables/d56b0dabe0f6e848af1a7222dde8d3bc50f117443c09b0e9eeb1fbae9156475b.jpg)

![db472632cd55e90f09040d7fc6f5d849af6a94090f84c6c3a3c96a2d16ae40ab.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/tables/db472632cd55e90f09040d7fc6f5d849af6a94090f84c6c3a3c96a2d16ae40ab.jpg)

![e96ae8493fca8588ac18d2f9dce641c9b599c79713f6e1eca76759a52e50c596.jpg](../emnlp_results/221_Chain-of-Talkers%20%28CoTalk)_ Fast Human Annotation of Dense Image Captions/tables/e96ae8493fca8588ac18d2f9dce641c9b599c79713f6e1eca76759a52e50c596.jpg)

## DecoupleSearch: Decouple Planning and Search via Hierarchical Reward Modeling


### Images

![37942d53c93547909b35fd33f75347bd67039ffef8e92da5df658f8ce3f2b62e.jpg](../emnlp_results/222_DecoupleSearch_%20Decouple%20Planning%20and%20Search%20via%20Hierarchical%20Reward%20Modeling/images/37942d53c93547909b35fd33f75347bd67039ffef8e92da5df658f8ce3f2b62e.jpg)

![6873d0d00534fb2b3895554f6eab17dda820af44011d2a8733f4c2f585b9dff2.jpg](../emnlp_results/222_DecoupleSearch_%20Decouple%20Planning%20and%20Search%20via%20Hierarchical%20Reward%20Modeling/images/6873d0d00534fb2b3895554f6eab17dda820af44011d2a8733f4c2f585b9dff2.jpg)

![7373c53156d9d2a96b92eeb9dc72eef3c9c9c383f6c78acf17da349ca3d2a04f.jpg](../emnlp_results/222_DecoupleSearch_%20Decouple%20Planning%20and%20Search%20via%20Hierarchical%20Reward%20Modeling/images/7373c53156d9d2a96b92eeb9dc72eef3c9c9c383f6c78acf17da349ca3d2a04f.jpg)

![ced67b5a0f2246a0454f9ea023cc6667837a1df3a1a98794e38e2dcffd6fc0f1.jpg](../emnlp_results/222_DecoupleSearch_%20Decouple%20Planning%20and%20Search%20via%20Hierarchical%20Reward%20Modeling/images/ced67b5a0f2246a0454f9ea023cc6667837a1df3a1a98794e38e2dcffd6fc0f1.jpg)

![f53dd0dc876cb06bab31aa1affe6beb1fdf5232184cb385b06e53a7cf5091462.jpg](../emnlp_results/222_DecoupleSearch_%20Decouple%20Planning%20and%20Search%20via%20Hierarchical%20Reward%20Modeling/images/f53dd0dc876cb06bab31aa1affe6beb1fdf5232184cb385b06e53a7cf5091462.jpg)

### Tables

![02497aa50ea8cef1667b6f7b08b4d13238979a678297a3c59b101069c67223de.jpg](../emnlp_results/222_DecoupleSearch_%20Decouple%20Planning%20and%20Search%20via%20Hierarchical%20Reward%20Modeling/tables/02497aa50ea8cef1667b6f7b08b4d13238979a678297a3c59b101069c67223de.jpg)

![22783db0f48ff40cbe6e5b7b69f5f284f975d1c0209d170dad4912da767defed.jpg](../emnlp_results/222_DecoupleSearch_%20Decouple%20Planning%20and%20Search%20via%20Hierarchical%20Reward%20Modeling/tables/22783db0f48ff40cbe6e5b7b69f5f284f975d1c0209d170dad4912da767defed.jpg)

![5a5276c1c6fa9ced2a325122af49b0dfbb9f168832b48f984332c51123243311.jpg](../emnlp_results/222_DecoupleSearch_%20Decouple%20Planning%20and%20Search%20via%20Hierarchical%20Reward%20Modeling/tables/5a5276c1c6fa9ced2a325122af49b0dfbb9f168832b48f984332c51123243311.jpg)

![6eac680737a0efd9b8a3c286f2f34a8d9c04ca7b616cf0e62f22356455f3411c.jpg](../emnlp_results/222_DecoupleSearch_%20Decouple%20Planning%20and%20Search%20via%20Hierarchical%20Reward%20Modeling/tables/6eac680737a0efd9b8a3c286f2f34a8d9c04ca7b616cf0e62f22356455f3411c.jpg)

![846320a994806c124772ccc47f66bef8b4ff4ab16999b19a2533e89738e2e923.jpg](../emnlp_results/222_DecoupleSearch_%20Decouple%20Planning%20and%20Search%20via%20Hierarchical%20Reward%20Modeling/tables/846320a994806c124772ccc47f66bef8b4ff4ab16999b19a2533e89738e2e923.jpg)

![b6fdf90d0a97672b8128b27483b13935a9d58fc02e2595972fdd3756c161b3ef.jpg](../emnlp_results/222_DecoupleSearch_%20Decouple%20Planning%20and%20Search%20via%20Hierarchical%20Reward%20Modeling/tables/b6fdf90d0a97672b8128b27483b13935a9d58fc02e2595972fdd3756c161b3ef.jpg)

## RewardDS: Privacy-Preserving Fine-Tuning for Large Language Models via Reward Driven Data Synthesis


### Images

![04e475c6049f26568578e3aeb5c1e98794fb8722336ed9b3f350ad54e3963800.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/04e475c6049f26568578e3aeb5c1e98794fb8722336ed9b3f350ad54e3963800.jpg)

![0e344979c2516e0af4b79357e78cea4fe5bdb22dc7e0e22a1fb01ec6fb347140.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/0e344979c2516e0af4b79357e78cea4fe5bdb22dc7e0e22a1fb01ec6fb347140.jpg)

![633e1ed7e079bcab66a60070a8b6276e9404fa3e0a8c50aab4368498a829280d.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/633e1ed7e079bcab66a60070a8b6276e9404fa3e0a8c50aab4368498a829280d.jpg)

![6a74f9ceea4a5dc6722d58b63bd13c0e57af805fc890acc364f885bdae799375.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/6a74f9ceea4a5dc6722d58b63bd13c0e57af805fc890acc364f885bdae799375.jpg)

![7ae04afcb9a09fdfc93397e94a3f255d359573812bba04e9e21102e9dbe69429.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/7ae04afcb9a09fdfc93397e94a3f255d359573812bba04e9e21102e9dbe69429.jpg)

![7e44cd77ff30e912d4bab32299ed19ca4043ff2487d149c633366e3af6bf63e1.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/7e44cd77ff30e912d4bab32299ed19ca4043ff2487d149c633366e3af6bf63e1.jpg)

![8dc96bc62f595251fc8e4c948a8fe516b34bd31e1e7a9a63d39f16b3cd374e66.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/8dc96bc62f595251fc8e4c948a8fe516b34bd31e1e7a9a63d39f16b3cd374e66.jpg)

![91e0f3cf0f9a4b769ccc141aced76a052b6999762d11b31e2d3c23a07b6b33e8.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/91e0f3cf0f9a4b769ccc141aced76a052b6999762d11b31e2d3c23a07b6b33e8.jpg)

![927f697266cf07dfba777959a402fd56bedede5ea7fdc3164625de103160febe.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/927f697266cf07dfba777959a402fd56bedede5ea7fdc3164625de103160febe.jpg)

![991027040b955dcc7388ac29caf7dcfd7d93d0b3adb990e7d5b812087affc168.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/991027040b955dcc7388ac29caf7dcfd7d93d0b3adb990e7d5b812087affc168.jpg)

![a52da830f7c159789219479e81a45f994b441ecc3bed3155ab17d9e3d9e321e6.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/a52da830f7c159789219479e81a45f994b441ecc3bed3155ab17d9e3d9e321e6.jpg)

![ab7ebb13b107c4a874afdfd8292764dbf8ad850a50525ea08ff01f64d33c8ffe.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/ab7ebb13b107c4a874afdfd8292764dbf8ad850a50525ea08ff01f64d33c8ffe.jpg)

![af18532b51205a6cd096d0cb4ccc78ebb88f71cbeaf871697aba26386a566e21.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/af18532b51205a6cd096d0cb4ccc78ebb88f71cbeaf871697aba26386a566e21.jpg)

![c3b965389e684e5a80bf9af80699ca8f71d2ca8fc300e963637100f9cdde8438.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/c3b965389e684e5a80bf9af80699ca8f71d2ca8fc300e963637100f9cdde8438.jpg)

![da7bac3a5c2ffa8a501b1e4224162b6edd8d6f844696c724cd4329fe9da04bcf.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/da7bac3a5c2ffa8a501b1e4224162b6edd8d6f844696c724cd4329fe9da04bcf.jpg)

![def645774ae1c13554c529f43820faac046d414a9793f01bd540c444c3592404.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/def645774ae1c13554c529f43820faac046d414a9793f01bd540c444c3592404.jpg)

![e03f3ffffc604c8f39c2275f2fa977c6256fcf7e75a898e5665bbf0f3846953a.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/e03f3ffffc604c8f39c2275f2fa977c6256fcf7e75a898e5665bbf0f3846953a.jpg)

![ee0d8a3c1baea4026228bc9cc22f52e2818e582533733fdd8d03c6ecfeda0124.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/images/ee0d8a3c1baea4026228bc9cc22f52e2818e582533733fdd8d03c6ecfeda0124.jpg)

### Tables

![1ddf4090f6b5995f0504911d594270726147b910616de1df7a35b614e86f26d6.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/tables/1ddf4090f6b5995f0504911d594270726147b910616de1df7a35b614e86f26d6.jpg)

![1f78b8182aa574aff097095a02ad40415679f99ba84a686a82c442d459ab873b.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/tables/1f78b8182aa574aff097095a02ad40415679f99ba84a686a82c442d459ab873b.jpg)

![3ac934d4880c73cc3cd2ed63ae2bf6aad5434de2bccc07dd920deb0bdf6bcbaf.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/tables/3ac934d4880c73cc3cd2ed63ae2bf6aad5434de2bccc07dd920deb0bdf6bcbaf.jpg)

![401f796884321c09ba250d8aeb6af08b1b34d71b5a863564012b1fd295398230.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/tables/401f796884321c09ba250d8aeb6af08b1b34d71b5a863564012b1fd295398230.jpg)

![b9847b0c6e731cb7f32100884037bf15bdbc8e782315ebcb4853f986cf190afa.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/tables/b9847b0c6e731cb7f32100884037bf15bdbc8e782315ebcb4853f986cf190afa.jpg)

![ec8f1d590daa4a12e8af287148c785736ed754d7d27bd7c08d3939aa2d346bbc.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/tables/ec8f1d590daa4a12e8af287148c785736ed754d7d27bd7c08d3939aa2d346bbc.jpg)

![f21674c57b078c77a46674c25936cd2b4478d270aea4745eea9d679f2df603d1.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/tables/f21674c57b078c77a46674c25936cd2b4478d270aea4745eea9d679f2df603d1.jpg)

![faabde6ecb47e2329c0efd92261c67538248f73de2c0326463b8f86c800200b8.jpg](../emnlp_results/223_RewardDS_%20Privacy-Preserving%20Fine-Tuning%20for%20Large%20Language%20Models%20via%20Reward%20Driven%20Data%20Synthesis/tables/faabde6ecb47e2329c0efd92261c67538248f73de2c0326463b8f86c800200b8.jpg)

## Synergizing Multimodal Temporal Knowledge Graphs and Large Language Models for Social Relation Recognition


### Images

![0f1906ffaa4785a1d7b705685eb179cefcbbd5f4166665f493590fd41f451b03.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/images/0f1906ffaa4785a1d7b705685eb179cefcbbd5f4166665f493590fd41f451b03.jpg)

![7b9f306fe84e2259641efed151fde3d0dba1eaec376f5a7de20ec57c6ef93646.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/images/7b9f306fe84e2259641efed151fde3d0dba1eaec376f5a7de20ec57c6ef93646.jpg)

![aa60829fb8a536a6ddb3148d4d15cdaf57912b6e63aff96ba28ff940122893e9.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/images/aa60829fb8a536a6ddb3148d4d15cdaf57912b6e63aff96ba28ff940122893e9.jpg)

![c6008b94935095701d652c65528dcb1740d01d92fd99d939b1289d18ecf94245.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/images/c6008b94935095701d652c65528dcb1740d01d92fd99d939b1289d18ecf94245.jpg)

![cca743091c1f1d1d5faf092f60235987795d7da30390eee1a286b4c2f3e5c19b.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/images/cca743091c1f1d1d5faf092f60235987795d7da30390eee1a286b4c2f3e5c19b.jpg)

![ccef686137d5a834e36b53130b253c3df1e4bb2d33469ddbb73af2d3f84b69be.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/images/ccef686137d5a834e36b53130b253c3df1e4bb2d33469ddbb73af2d3f84b69be.jpg)

![da6042b9321b2a81cc881cfb43093ced7559571d2998b13ff94a13ac88ca4a96.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/images/da6042b9321b2a81cc881cfb43093ced7559571d2998b13ff94a13ac88ca4a96.jpg)

### Tables

![1eca31c5233fdfd30a02c0580ac6dc68dd280d77348c46d1af3f0ddb59509a84.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/tables/1eca31c5233fdfd30a02c0580ac6dc68dd280d77348c46d1af3f0ddb59509a84.jpg)

![3358a9f8b314faec43db1142643145851cbb0b84b02325cc705e791d305ff452.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/tables/3358a9f8b314faec43db1142643145851cbb0b84b02325cc705e791d305ff452.jpg)

![cf6dd324259abda292214adcc0e2b40d905d653671c60e4999de09b73640716f.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/tables/cf6dd324259abda292214adcc0e2b40d905d653671c60e4999de09b73640716f.jpg)

![d0d2e08f3eaf7e0aafff2f695698c3ff73ac1418f20c5505c6d22c426a69547f.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/tables/d0d2e08f3eaf7e0aafff2f695698c3ff73ac1418f20c5505c6d22c426a69547f.jpg)

![dafa3907ddd799b6d8109c119bec510135d4ec3b0ae94e9f6d4baa7988bad632.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/tables/dafa3907ddd799b6d8109c119bec510135d4ec3b0ae94e9f6d4baa7988bad632.jpg)

![dccc532688c77431dd94d0f49f8651cb9ee4b58d54b4f072eabae58211af921b.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/tables/dccc532688c77431dd94d0f49f8651cb9ee4b58d54b4f072eabae58211af921b.jpg)

![fd8732b37caea3f8b463ca87426d7bfb3b63d24e634aef0d8c36e14d6c01f980.jpg](../emnlp_results/224_Synergizing%20Multimodal%20Temporal%20Knowledge%20Graphs%20and%20Large%20Language%20Models%20for%20Social%20Relation%20Recog/tables/fd8732b37caea3f8b463ca87426d7bfb3b63d24e634aef0d8c36e14d6c01f980.jpg)

## LegalSearchLM: Rethinking Legal Case Retrieval as Legal Elements Generation


### Images

![05afa9dfce3083e72fbcb16b4faa00ff38296919d52e58ed87a70394aae1fb0e.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/images/05afa9dfce3083e72fbcb16b4faa00ff38296919d52e58ed87a70394aae1fb0e.jpg)

![32ed4aba6b6d5a9bafa92e6d7ee8c53c766e1a86fdfc9896f164edafce2e9094.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/images/32ed4aba6b6d5a9bafa92e6d7ee8c53c766e1a86fdfc9896f164edafce2e9094.jpg)

![78dfb7117687af9c8df01e57788478f03b91b2342f3928e54bfad269921724be.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/images/78dfb7117687af9c8df01e57788478f03b91b2342f3928e54bfad269921724be.jpg)

![a46c7aeb188456ede674c1854e191ed612ce0572c6fe2855acfdbefabf25f610.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/images/a46c7aeb188456ede674c1854e191ed612ce0572c6fe2855acfdbefabf25f610.jpg)

![bd9c6809b42a9f7b7b9705c6e3a6dba2e2d19890525d4a6c5b0e8aee84de22aa.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/images/bd9c6809b42a9f7b7b9705c6e3a6dba2e2d19890525d4a6c5b0e8aee84de22aa.jpg)

![fdef37faff67042ec66c39e31753188f450778588006c410a47536e98363e840.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/images/fdef37faff67042ec66c39e31753188f450778588006c410a47536e98363e840.jpg)

### Tables

![02fe718a7cb822f601c6e741d4505766bfcca05f314d1ee549a1c1d0fe56d16a.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/02fe718a7cb822f601c6e741d4505766bfcca05f314d1ee549a1c1d0fe56d16a.jpg)

![0daf45356460f0f168404e050a30477eedc55092c082c89a2db0d1f17a131d6a.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/0daf45356460f0f168404e050a30477eedc55092c082c89a2db0d1f17a131d6a.jpg)

![0f6b308579bcd596dbe292846925bbed4a1937724c43a3a82933e2641b7417cf.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/0f6b308579bcd596dbe292846925bbed4a1937724c43a3a82933e2641b7417cf.jpg)

![131a465a4c37f12451a341dd1330b1e1b034db9bf11f4adf2a1c9a16c25072df.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/131a465a4c37f12451a341dd1330b1e1b034db9bf11f4adf2a1c9a16c25072df.jpg)

![141960c4a1e6c813a3fb37b1d9ceff3a66bfdabe5024a9ebd60d5ff614088696.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/141960c4a1e6c813a3fb37b1d9ceff3a66bfdabe5024a9ebd60d5ff614088696.jpg)

![16b3a1363ccaa841567e30fa4da08d2aafb261af6a47f6b36b862cb49287ef77.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/16b3a1363ccaa841567e30fa4da08d2aafb261af6a47f6b36b862cb49287ef77.jpg)

![1fab835c15a1ec903dac1e8ad6dbe1c15948f3a27069aeae9b54c7f59c517284.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/1fab835c15a1ec903dac1e8ad6dbe1c15948f3a27069aeae9b54c7f59c517284.jpg)

![224a8dd585de98396955e140b0fa2b52f7c12b15296305046b49b42a8b3fb051.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/224a8dd585de98396955e140b0fa2b52f7c12b15296305046b49b42a8b3fb051.jpg)

![290a83efad61d9b754fc813a5826cd95bbd86e35772d79138036cfabfd21124d.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/290a83efad61d9b754fc813a5826cd95bbd86e35772d79138036cfabfd21124d.jpg)

![2a55f982b672f0c3807bc7cd32daf121a6df0761b6dab537f535d03e733ef9af.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/2a55f982b672f0c3807bc7cd32daf121a6df0761b6dab537f535d03e733ef9af.jpg)

![2c48ccda0e24455981a33408f850c5eb522fbb64e87b06fe47223641e61d0db7.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/2c48ccda0e24455981a33408f850c5eb522fbb64e87b06fe47223641e61d0db7.jpg)

![2e3615e66d72dac26ca6cc2203a9f35e76cdb19367b19844cc65dc9f419ab5ae.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/2e3615e66d72dac26ca6cc2203a9f35e76cdb19367b19844cc65dc9f419ab5ae.jpg)

![307156a45cfdb41c9555f1a786b2520a9c404ed8bbb701a184fdd43da56baeb4.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/307156a45cfdb41c9555f1a786b2520a9c404ed8bbb701a184fdd43da56baeb4.jpg)

![309f4d31fcce2cc751b4517c77c8624e41611f91732690aabeb60defe869efe1.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/309f4d31fcce2cc751b4517c77c8624e41611f91732690aabeb60defe869efe1.jpg)

![38696c11af79b41fb05af829fbe564efa3b5f9bfc0a70953690ec3ad7b153e5f.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/38696c11af79b41fb05af829fbe564efa3b5f9bfc0a70953690ec3ad7b153e5f.jpg)

![3da0f41e0844c75f35a8e64ae50896dba1c9ab0e2f754c8d949b91e5166d0378.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/3da0f41e0844c75f35a8e64ae50896dba1c9ab0e2f754c8d949b91e5166d0378.jpg)

![445bb71d14403aa287ea4437409a57e82f637665fa7b5a06ad161dd8b939a494.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/445bb71d14403aa287ea4437409a57e82f637665fa7b5a06ad161dd8b939a494.jpg)

![4495b95f3f72d52ad6ea80dd59a46524f68762f50fcf3368388f4d3e9603c663.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/4495b95f3f72d52ad6ea80dd59a46524f68762f50fcf3368388f4d3e9603c663.jpg)

![44e4699f5dba8f046248175886cee79c6387cb9fb6575a9fec78cd54221b76ac.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/44e4699f5dba8f046248175886cee79c6387cb9fb6575a9fec78cd54221b76ac.jpg)

![4731c2e58d5ecd602b366c79c0e26801d1a015832b99dbc4dd339bb22385431c.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/4731c2e58d5ecd602b366c79c0e26801d1a015832b99dbc4dd339bb22385431c.jpg)

![5db3a2516970052ecf3b600fca6f76bbb8d6406b3065d56189667b9b41b771d1.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/5db3a2516970052ecf3b600fca6f76bbb8d6406b3065d56189667b9b41b771d1.jpg)

![5df90ea85d85f8aa1bf27ed738126480a24ffebd2bed34a9401938103617f4e0.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/5df90ea85d85f8aa1bf27ed738126480a24ffebd2bed34a9401938103617f4e0.jpg)

![6507eba25f469ec34302fbfa0ee61f57b56a87b16de3fdbeff1bee30a1f95338.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/6507eba25f469ec34302fbfa0ee61f57b56a87b16de3fdbeff1bee30a1f95338.jpg)

![667d7ec04b7479f3bd889983ea4c61878a234a338501aa6828dafdeced67d4a5.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/667d7ec04b7479f3bd889983ea4c61878a234a338501aa6828dafdeced67d4a5.jpg)

![6696c92023a99333a58273917501284666cdea6f1381a7bec860ea3a3c69f10f.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/6696c92023a99333a58273917501284666cdea6f1381a7bec860ea3a3c69f10f.jpg)

![67d6cfe1e4acb3fcfe23a8a2583f1a97ae9055ae2769fb244a185a578c1ac4d1.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/67d6cfe1e4acb3fcfe23a8a2583f1a97ae9055ae2769fb244a185a578c1ac4d1.jpg)

![692d9ff89b119de638afe725ebd756d3948076ef4138da3328129d49289fc270.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/692d9ff89b119de638afe725ebd756d3948076ef4138da3328129d49289fc270.jpg)

![6f97ba8e2be785622402e74f08549cb11fd304c202f01e01736ba4e64c8fe105.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/6f97ba8e2be785622402e74f08549cb11fd304c202f01e01736ba4e64c8fe105.jpg)

![6fa7d0841bfb0dd640f3d9d03f9240c602d9db4f820776cf9894902fad999860.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/6fa7d0841bfb0dd640f3d9d03f9240c602d9db4f820776cf9894902fad999860.jpg)

![7045f09f30275cc321dd17c2860bbf371218f8ce5a4e9b51dad14715d9fde98f.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/7045f09f30275cc321dd17c2860bbf371218f8ce5a4e9b51dad14715d9fde98f.jpg)

![7ad7a47df0b492df83a21fc47d5f8ae92fc6fec626009b8efc087e99ad2aca7a.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/7ad7a47df0b492df83a21fc47d5f8ae92fc6fec626009b8efc087e99ad2aca7a.jpg)

![81255c46a6a2bfa38845def8fc99a1e75c53e395703a5224221dfdd61d3055b2.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/81255c46a6a2bfa38845def8fc99a1e75c53e395703a5224221dfdd61d3055b2.jpg)

![833d7c7fede39aef4d5c0589463c9d3142492eff834162843c53e94876cf2627.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/833d7c7fede39aef4d5c0589463c9d3142492eff834162843c53e94876cf2627.jpg)

![91b8585396817364fda4304d0e280e28b51218d739068cf8fa444e4fa42a6dc2.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/91b8585396817364fda4304d0e280e28b51218d739068cf8fa444e4fa42a6dc2.jpg)

![929ecd935899162e37cf35aa5ccf3051c109e1dbdb43af1ab35169668d591583.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/929ecd935899162e37cf35aa5ccf3051c109e1dbdb43af1ab35169668d591583.jpg)

![9bd542acdc84c9f066df0c928b9e11d0b6529f4e0782aedd451fcbb758c45857.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/9bd542acdc84c9f066df0c928b9e11d0b6529f4e0782aedd451fcbb758c45857.jpg)

![aaca057ff2dfa093136c90358b25ebaf864144ea56d1a1b73d6138f7441c2708.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/aaca057ff2dfa093136c90358b25ebaf864144ea56d1a1b73d6138f7441c2708.jpg)

![c0a21ae4a5673ca2bacef143df35e126d79f681e04f7c96f9da7b762047622ec.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/c0a21ae4a5673ca2bacef143df35e126d79f681e04f7c96f9da7b762047622ec.jpg)

![c9d55dec713dc2f066293299a28b0732400fa82923c5ed6a01af84c3ba68ca72.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/c9d55dec713dc2f066293299a28b0732400fa82923c5ed6a01af84c3ba68ca72.jpg)

![cff2061194aa2c273369fa4be4f895731a6df11542f8a4fad192830d8f18c252.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/cff2061194aa2c273369fa4be4f895731a6df11542f8a4fad192830d8f18c252.jpg)

![d417c81a25126dc0f53a496387db49a00129c76f3a752324aba53356634347a4.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/d417c81a25126dc0f53a496387db49a00129c76f3a752324aba53356634347a4.jpg)

![d70f925d08f386bb04727243e4a15d73bfe13353d5d88ba6f9828d8393566b16.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/d70f925d08f386bb04727243e4a15d73bfe13353d5d88ba6f9828d8393566b16.jpg)

![e0c490a678efaaf16d22fcd07e224f9d6c196c6fcf26f71009184d99108e0d41.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/e0c490a678efaaf16d22fcd07e224f9d6c196c6fcf26f71009184d99108e0d41.jpg)

![e6d94bced067f5005278bf334a328d85003341e9062d3aa729d18f0e6f02a427.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/e6d94bced067f5005278bf334a328d85003341e9062d3aa729d18f0e6f02a427.jpg)

![ee1d6bb094fba5ec25661761ebcb0d664449dd84be0133b5800d47df381bb873.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/ee1d6bb094fba5ec25661761ebcb0d664449dd84be0133b5800d47df381bb873.jpg)

![f521a81dbf28edd7cc4b1ff96881f384f493897451f6065faa9b8f0a7a285792.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/f521a81dbf28edd7cc4b1ff96881f384f493897451f6065faa9b8f0a7a285792.jpg)

![f7c7a6e7b1fd125818ce769e16ac39434af5f82ae8647042eeab2b4d6e35a23c.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/f7c7a6e7b1fd125818ce769e16ac39434af5f82ae8647042eeab2b4d6e35a23c.jpg)

![fb063f66b9f6c2e4f3dcc68abb626661812064819c069b12a50f0905f3292e7a.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/fb063f66b9f6c2e4f3dcc68abb626661812064819c069b12a50f0905f3292e7a.jpg)

![fdc2475588da70cf54a4558e9a916209d77bdd05d61aee9dee1231c4ba592aa7.jpg](../emnlp_results/225_LegalSearchLM_%20Rethinking%20Legal%20Case%20Retrieval%20as%20Legal%20Elements%20Generation/tables/fdc2475588da70cf54a4558e9a916209d77bdd05d61aee9dee1231c4ba592aa7.jpg)

## ChartMind: A Comprehensive Benchmark for Complex Real-world Multimodal Chart Question Answering


### Images

![16b576aabba7e090dc7759209d8918732b8d395fbb3e26af5b43bf45cae42fe3.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/images/16b576aabba7e090dc7759209d8918732b8d395fbb3e26af5b43bf45cae42fe3.jpg)

![1aa0995c89fd5eb12901343f37059676fcbe4c3eb5ce153a0f920fc49e7b387b.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/images/1aa0995c89fd5eb12901343f37059676fcbe4c3eb5ce153a0f920fc49e7b387b.jpg)

![3510c455cb65a049eb058889ccc23962aa07fc2b5ed4407740f7578e6ee72ff8.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/images/3510c455cb65a049eb058889ccc23962aa07fc2b5ed4407740f7578e6ee72ff8.jpg)

![3ab3a1cae9c768a15d8438e253bf92f471831e12ad8422f838b86f186d55e599.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/images/3ab3a1cae9c768a15d8438e253bf92f471831e12ad8422f838b86f186d55e599.jpg)

![77eead87c0d2947741b277503f6e2ede1fe2bf457b29be05eae04e5a72ed8063.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/images/77eead87c0d2947741b277503f6e2ede1fe2bf457b29be05eae04e5a72ed8063.jpg)

![8464018c62a5aefc283f07ef6c79d6f2a7a4ba62d3947eb94459500ae7801046.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/images/8464018c62a5aefc283f07ef6c79d6f2a7a4ba62d3947eb94459500ae7801046.jpg)

![85e1693abc91fe6b7974b403f4865d93b43d721abeb0a5808cc9175bd8540b01.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/images/85e1693abc91fe6b7974b403f4865d93b43d721abeb0a5808cc9175bd8540b01.jpg)

![b7890f8b9fda029c8d7a744d6f85cf22d6a6db9c237e8c64a30d6fa3a2918544.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/images/b7890f8b9fda029c8d7a744d6f85cf22d6a6db9c237e8c64a30d6fa3a2918544.jpg)

![d2419db2bfce21122e2d3c5244fa7fe2cdac9811d35fce78d88f4a36fc3fd27c.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/images/d2419db2bfce21122e2d3c5244fa7fe2cdac9811d35fce78d88f4a36fc3fd27c.jpg)

![f07c093c235865b63c1846395df6293b7a4e39d65bd33326e187d41b92c467e2.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/images/f07c093c235865b63c1846395df6293b7a4e39d65bd33326e187d41b92c467e2.jpg)

### Tables

![04d7d03750e543a055422c3447d0f4b5a8484edb09ad4409515952beac44aadc.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/tables/04d7d03750e543a055422c3447d0f4b5a8484edb09ad4409515952beac44aadc.jpg)

![68f1e47571ceaf5899b070296ab8e3566ded1ac5302c203da217b56d6a6c5025.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/tables/68f1e47571ceaf5899b070296ab8e3566ded1ac5302c203da217b56d6a6c5025.jpg)

![894bceb910f1657f96c1d1c1cdbf4358498f97ccef2f2acec6a516ea8906286e.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/tables/894bceb910f1657f96c1d1c1cdbf4358498f97ccef2f2acec6a516ea8906286e.jpg)

![8f690dac4eb5860cb450bcd10dad06056277628ec42daf8d1f2850dd2c894ea2.jpg](../emnlp_results/226_ChartMind_%20A%20Comprehensive%20Benchmark%20for%20Complex%20Real-world%20Multimodal%20Chart%20Question%20Answering/tables/8f690dac4eb5860cb450bcd10dad06056277628ec42daf8d1f2850dd2c894ea2.jpg)

## COLA: Collaborative Multi-Agent Framework with Dynamic Task Scheduling forGUIAutomation


### Images

![362ab800bd7c5e28299bade73a13dc2c12c897ab3a42ffa49c6a93975fa01dad.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/images/362ab800bd7c5e28299bade73a13dc2c12c897ab3a42ffa49c6a93975fa01dad.jpg)

![4856b9b6c812a642350af54545cf1b8c195d7cf3d4295a2879aac3d93b8b45a3.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/images/4856b9b6c812a642350af54545cf1b8c195d7cf3d4295a2879aac3d93b8b45a3.jpg)

![5f20ff32596747531e5c82f31942a9dce750dd3c4f2a50eb968dd501596090db.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/images/5f20ff32596747531e5c82f31942a9dce750dd3c4f2a50eb968dd501596090db.jpg)

![67b7967ec93644b226bd6568173439c02ffc0fe1f7db47c5d6193b6f91e0c325.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/images/67b7967ec93644b226bd6568173439c02ffc0fe1f7db47c5d6193b6f91e0c325.jpg)

![d5344e0869b7b836ccc1faa201d334740ae59853137c208891f47cda520624eb.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/images/d5344e0869b7b836ccc1faa201d334740ae59853137c208891f47cda520624eb.jpg)

### Tables

![0da6db04cdbb796af795706689d952a53ac82f1b58ddf166ce11eda96fc045c5.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/0da6db04cdbb796af795706689d952a53ac82f1b58ddf166ce11eda96fc045c5.jpg)

![25c09d4c531ff0aefbbe246c8dfc91d824a9df1ebf98c758f97c24881814c9c5.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/25c09d4c531ff0aefbbe246c8dfc91d824a9df1ebf98c758f97c24881814c9c5.jpg)

![2f57a42057f641ab10a945e5f83a7dfa18802f50c145cedb8db0435b93cd95c3.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/2f57a42057f641ab10a945e5f83a7dfa18802f50c145cedb8db0435b93cd95c3.jpg)

![4fc0e503c4d06b77f0115234cd189faf46944198296678cdfdac266cbacc06c8.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/4fc0e503c4d06b77f0115234cd189faf46944198296678cdfdac266cbacc06c8.jpg)

![504b4a45208bd3e0538fe21bb19276d7602defce07c23228602b98bac9c888b9.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/504b4a45208bd3e0538fe21bb19276d7602defce07c23228602b98bac9c888b9.jpg)

![62f79a90e2eb6e7608be296b2dd912986caf717f79c7d2d7e735fa87cc067fff.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/62f79a90e2eb6e7608be296b2dd912986caf717f79c7d2d7e735fa87cc067fff.jpg)

![684fc0c41894e2d5b9b4e67d19f6183e68b06b971e916d4e3542d0ea9ea7d89b.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/684fc0c41894e2d5b9b4e67d19f6183e68b06b971e916d4e3542d0ea9ea7d89b.jpg)

![69696bf258f89f98551c2a591e2fc86937f2efd52daae2994b2351f0f522c1a2.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/69696bf258f89f98551c2a591e2fc86937f2efd52daae2994b2351f0f522c1a2.jpg)

![9421c88801282379eb8849fcd9774abac8a090cb33299783fb49f881086c1843.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/9421c88801282379eb8849fcd9774abac8a090cb33299783fb49f881086c1843.jpg)

![ad62585743998eb2235cda8daae0f0ff1ecb8825884e8349f4b43be8a653253d.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/ad62585743998eb2235cda8daae0f0ff1ecb8825884e8349f4b43be8a653253d.jpg)

![ae30b09833c1f558aeee2f03c3ee1ccc1b9aeddd0a01ea16bb08b8104c2fa2f6.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/ae30b09833c1f558aeee2f03c3ee1ccc1b9aeddd0a01ea16bb08b8104c2fa2f6.jpg)

![b8760918515412c1cf1bdbd8dd0a7a149d3bc474a80c31dc6786876a55185460.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/b8760918515412c1cf1bdbd8dd0a7a149d3bc474a80c31dc6786876a55185460.jpg)

![bda6dd616f41627f5ae56ae451ef93f1c0bd480cd20443907f70c2f8a6f17ab2.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/bda6dd616f41627f5ae56ae451ef93f1c0bd480cd20443907f70c2f8a6f17ab2.jpg)

![fa65bceac8fc5e1a74987ad3be56d16a65ba67674a3f89c1566809922e31e4f2.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/fa65bceac8fc5e1a74987ad3be56d16a65ba67674a3f89c1566809922e31e4f2.jpg)

![fec092e9d04c910ce5d8cdbf640d3be36281effaf9b6f327aeb283d799ee0201.jpg](../emnlp_results/227_COLA_%20Collaborative%20Multi-Agent%20Framework%20with%20Dynamic%20Task%20Scheduling%20forGUIAutomation/tables/fec092e9d04c910ce5d8cdbf640d3be36281effaf9b6f327aeb283d799ee0201.jpg)

## DASA-Trans-STM: Adaptive Efficient Transformer for Short Text Matching using Data Augmentation and Semantic Awareness


### Images

![3dd54add086aefbfd5d48fc9eb69c78719bbe2492c1303b7d54ede16f9f72ce8.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/images/3dd54add086aefbfd5d48fc9eb69c78719bbe2492c1303b7d54ede16f9f72ce8.jpg)

![47f9bbe988692ff0ee07ba38e6daf98a502e08acfecd520d2a3956551d3dcdc8.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/images/47f9bbe988692ff0ee07ba38e6daf98a502e08acfecd520d2a3956551d3dcdc8.jpg)

![77d24033c51ee3bd5f86cc9e48c8b3e3be711e8bb6f49f4d0ce0f4aea286d61f.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/images/77d24033c51ee3bd5f86cc9e48c8b3e3be711e8bb6f49f4d0ce0f4aea286d61f.jpg)

![82a9a22e190920c64449d1e5713b3d1f55b1ff8d9d7614cc6e98317337cc58d6.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/images/82a9a22e190920c64449d1e5713b3d1f55b1ff8d9d7614cc6e98317337cc58d6.jpg)

![9a95fd0d529212c0763df3a3c14465d87aa91700b75da2e93b6913b88fcb96bd.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/images/9a95fd0d529212c0763df3a3c14465d87aa91700b75da2e93b6913b88fcb96bd.jpg)

![a1d2e901d6df29acea46a8e0610738b68cc62707a8986d43c3bb9be61298866c.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/images/a1d2e901d6df29acea46a8e0610738b68cc62707a8986d43c3bb9be61298866c.jpg)

![ef6205198deeb92b1605041456229cf8c86e3572626295136b9e3f8422f7738b.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/images/ef6205198deeb92b1605041456229cf8c86e3572626295136b9e3f8422f7738b.jpg)

### Tables

![295c5e1fd48b79dae1c8cc09ab35923c1c245323c9040d0205110d4b868d006f.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/tables/295c5e1fd48b79dae1c8cc09ab35923c1c245323c9040d0205110d4b868d006f.jpg)

![4232759e3a6db15b98e63d824fde52ea5358dc1f434b9831f772bc2601c08bf5.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/tables/4232759e3a6db15b98e63d824fde52ea5358dc1f434b9831f772bc2601c08bf5.jpg)

![5964d316dc5c188919b35f3f638c9e8ccbe237b9944df02a08748aa716fd199f.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/tables/5964d316dc5c188919b35f3f638c9e8ccbe237b9944df02a08748aa716fd199f.jpg)

![9bffea3a7d4a1c9edb705f925b53cd8c20df6d0d005328044132aad2f6183e91.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/tables/9bffea3a7d4a1c9edb705f925b53cd8c20df6d0d005328044132aad2f6183e91.jpg)

![af2ca70e65cb2b41403a96c01088bcbfd67042b4feea70a637286a057febd4a8.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/tables/af2ca70e65cb2b41403a96c01088bcbfd67042b4feea70a637286a057febd4a8.jpg)

![b1bf0e20b212ea4ba3bbf38e824c721be1086bdee98fada85441921cb91ad977.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/tables/b1bf0e20b212ea4ba3bbf38e824c721be1086bdee98fada85441921cb91ad977.jpg)

![c24dfd7102669d4b5d23dab018d1448c1716f382e3a00919f6af77a771f463a2.jpg](../emnlp_results/228_DASA-Trans-STM_%20Adaptive%20Efficient%20Transformer%20for%20Short%20Text%20Matching%20using%20Data%20Augmentation%20and%20S/tables/c24dfd7102669d4b5d23dab018d1448c1716f382e3a00919f6af77a771f463a2.jpg)

## Pruning the Paradox: HowCLIP’s Most Informative Heads Enhance Performance While Amplifying Bias


### Images

![33e911394fa351e1e7265204bed59c2aca651a4583e2dcf30407cb05236bdad1.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/images/33e911394fa351e1e7265204bed59c2aca651a4583e2dcf30407cb05236bdad1.jpg)

![5cbd3e92c422064dd5d0435632eb7a9ede983e89579cb3381d7481effb628022.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/images/5cbd3e92c422064dd5d0435632eb7a9ede983e89579cb3381d7481effb628022.jpg)

![62a4218fba618e35c9413b2019896a70e85611b19eff4a3a5bb5a3648cca86ab.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/images/62a4218fba618e35c9413b2019896a70e85611b19eff4a3a5bb5a3648cca86ab.jpg)

![80c0ae48c5aae7bf1b24e8d014140e4e2d1dfe075d60d1b7643ca0dd06b2c7a3.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/images/80c0ae48c5aae7bf1b24e8d014140e4e2d1dfe075d60d1b7643ca0dd06b2c7a3.jpg)

![c2c4fbfd15b176a888021eeb32e7a80cce1845407085228567c120d9d0556827.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/images/c2c4fbfd15b176a888021eeb32e7a80cce1845407085228567c120d9d0556827.jpg)

### Tables

![00fbfcc6e8e9786590f6d71097b4ac9562af64256532e5d1f18bc39b6a2920f2.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/00fbfcc6e8e9786590f6d71097b4ac9562af64256532e5d1f18bc39b6a2920f2.jpg)

![03d7cb46405bbceb949f854358279966ea0039f894961cd007f5feff992f1715.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/03d7cb46405bbceb949f854358279966ea0039f894961cd007f5feff992f1715.jpg)

![1135341b42d9e332b75c5fa6dd303eb7db4aaeb5b6aeb57caa5c2c21a5e179d6.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/1135341b42d9e332b75c5fa6dd303eb7db4aaeb5b6aeb57caa5c2c21a5e179d6.jpg)

![1a91487c9c292349bdbfe97e0c1b61e0affbde16970bfc8372430b91577e4e9d.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/1a91487c9c292349bdbfe97e0c1b61e0affbde16970bfc8372430b91577e4e9d.jpg)

![312eaa77382906b9819b30bde6796727257f549d712291d09cc3f06f00df85dd.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/312eaa77382906b9819b30bde6796727257f549d712291d09cc3f06f00df85dd.jpg)

![4fde0a0c7da7d0276338c2aa358bd8aca24d3d4bf0ee60fe0aa8792ed830d6c9.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/4fde0a0c7da7d0276338c2aa358bd8aca24d3d4bf0ee60fe0aa8792ed830d6c9.jpg)

![51f453a4caea2786b0a606529bf7f2829a5636a1bde3e3ddae679f6898fe920b.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/51f453a4caea2786b0a606529bf7f2829a5636a1bde3e3ddae679f6898fe920b.jpg)

![54ea3435de8adf38a91f0a9d325e5ce2f5b0298b081e0bbcb26a2b4984d3b376.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/54ea3435de8adf38a91f0a9d325e5ce2f5b0298b081e0bbcb26a2b4984d3b376.jpg)

![560e1f06e3b53a38730b6d60c43f87020edd5217b4b92c64fd42e210cedfbdcd.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/560e1f06e3b53a38730b6d60c43f87020edd5217b4b92c64fd42e210cedfbdcd.jpg)

![611c7afb6dd1e9a4dc7539c85ea397f7c9ebbf45bbc7aa701e100545a7ffbe6d.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/611c7afb6dd1e9a4dc7539c85ea397f7c9ebbf45bbc7aa701e100545a7ffbe6d.jpg)

![6d749e347a844ba7148dbb1c65edc81ae9e2c0fbd906243096b1289ba0f66920.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/6d749e347a844ba7148dbb1c65edc81ae9e2c0fbd906243096b1289ba0f66920.jpg)

![d8ae9387a00397ec6cd39990b6e9e3072f870ce8f2ffb6247a1ad125718c0198.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/d8ae9387a00397ec6cd39990b6e9e3072f870ce8f2ffb6247a1ad125718c0198.jpg)

![f04e98f19ef58a04d2f6ff969f3e905ee2694474d9b5d8cbe16dd3c93eeb6d50.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/f04e98f19ef58a04d2f6ff969f3e905ee2694474d9b5d8cbe16dd3c93eeb6d50.jpg)

![f1711a93768bd2872b2b8da08f24fce7ce524809bb2ca86de77cf935107fa0fc.jpg](../emnlp_results/229_Pruning%20the%20Paradox_%20HowCLIP%E2%80%99s%20Most%20Informative%20Heads%20Enhance%20Performance%20While%20Amplifying%20Bias/tables/f1711a93768bd2872b2b8da08f24fce7ce524809bb2ca86de77cf935107fa0fc.jpg)

## CoLA: Compute-Efficient Pre-Training ofLLMs via Low-Rank Activation


### Images

![1b097e4668d923960ec26d4eb4f61ab18c5b3772ea9680d6ef56dee60b33c73d.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/images/1b097e4668d923960ec26d4eb4f61ab18c5b3772ea9680d6ef56dee60b33c73d.jpg)

![238d7c22770b513d5230203b687e8ca37fdc4b3767bc40d06cbe4f3fac742530.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/images/238d7c22770b513d5230203b687e8ca37fdc4b3767bc40d06cbe4f3fac742530.jpg)

![30fe8761335b7b74404f5fef70e6ad63b4aaebcacc77665632aed26335c257f7.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/images/30fe8761335b7b74404f5fef70e6ad63b4aaebcacc77665632aed26335c257f7.jpg)

![34d95757728b881dd937822a01b6450be27a36bf839b5ec2d9c5a2bc8f1dcad3.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/images/34d95757728b881dd937822a01b6450be27a36bf839b5ec2d9c5a2bc8f1dcad3.jpg)

![38d68457ac2f4c7b9d5aa547d283a727e6e2e5349691c6f75e99e66a211c2246.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/images/38d68457ac2f4c7b9d5aa547d283a727e6e2e5349691c6f75e99e66a211c2246.jpg)

![3e2580f77e455e4e4e4627f7694832d706e6847df61e93056b47e79102b55520.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/images/3e2580f77e455e4e4e4627f7694832d706e6847df61e93056b47e79102b55520.jpg)

![401a65a5ff3a8b793d9ca95c7d5cf1e581a02601ea285e15812518083e27740f.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/images/401a65a5ff3a8b793d9ca95c7d5cf1e581a02601ea285e15812518083e27740f.jpg)

![4ca9b17ec9b71e751bee48d922acfd12935b59b70ac464c3d705271dffc2d98d.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/images/4ca9b17ec9b71e751bee48d922acfd12935b59b70ac464c3d705271dffc2d98d.jpg)

![527d2031ccaecdc6a35de584d6974d8ab7881c9854b5bc39576093d055a6129d.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/images/527d2031ccaecdc6a35de584d6974d8ab7881c9854b5bc39576093d055a6129d.jpg)

![6462bd5d5b84d06393faa690835b09ccd070b03cce4d9f01accd4825d01b431f.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/images/6462bd5d5b84d06393faa690835b09ccd070b03cce4d9f01accd4825d01b431f.jpg)

![81e05c2249a81a80e7d413ef36bb9d39bbb11cc151bac161c957e8b334583ed6.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/images/81e05c2249a81a80e7d413ef36bb9d39bbb11cc151bac161c957e8b334583ed6.jpg)

![9ba2ff278ab3d546a366a6f568ffab88b7f33e8d04cad4b8774c0b68a3e1e690.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/images/9ba2ff278ab3d546a366a6f568ffab88b7f33e8d04cad4b8774c0b68a3e1e690.jpg)

### Tables

![00605b3209e1a6e2cefb0cc2b51743bc013b132e44d928584d6b2a9c97025130.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/tables/00605b3209e1a6e2cefb0cc2b51743bc013b132e44d928584d6b2a9c97025130.jpg)

![1134320813e0eb28241e577852dc914aea34c217b58216e27b3b135bda4443cd.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/tables/1134320813e0eb28241e577852dc914aea34c217b58216e27b3b135bda4443cd.jpg)

![3430df27c1e3cca5ea3572c94c55abb3681c1e12075badf930c492c192306c58.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/tables/3430df27c1e3cca5ea3572c94c55abb3681c1e12075badf930c492c192306c58.jpg)

![3bee53836a71c9ad82a7b598116db7f1673d93dd393edf0c5a365fc4ab97580d.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/tables/3bee53836a71c9ad82a7b598116db7f1673d93dd393edf0c5a365fc4ab97580d.jpg)

![81a665d130726b15efe82f01752a098d79e6bc478336add9711d937047a46955.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/tables/81a665d130726b15efe82f01752a098d79e6bc478336add9711d937047a46955.jpg)

![96aa7b8825cdd8caa200645b17c33f346a49ae586badb9b5448ae8f56fb11f08.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/tables/96aa7b8825cdd8caa200645b17c33f346a49ae586badb9b5448ae8f56fb11f08.jpg)

![a2f8b2a7bd291525309b65b0ea34c8710ed2903b8c3a8e9b9962819ec0ae7208.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/tables/a2f8b2a7bd291525309b65b0ea34c8710ed2903b8c3a8e9b9962819ec0ae7208.jpg)

![a799837ffe8b75f56a2a0f4306752de7f0e196704566c7e1e45c95244dc5a04d.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/tables/a799837ffe8b75f56a2a0f4306752de7f0e196704566c7e1e45c95244dc5a04d.jpg)

![b140806c6ee0c71b217d3b590a68803077888f4388e6d13c9d54164c7eed5a26.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/tables/b140806c6ee0c71b217d3b590a68803077888f4388e6d13c9d54164c7eed5a26.jpg)

![be5bf87fc796c12ce97fffb032f1a256ad9fc08c19b30872592dd12283651d00.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/tables/be5bf87fc796c12ce97fffb032f1a256ad9fc08c19b30872592dd12283651d00.jpg)

![c01bc4b142236f9297a38742c9f61fa99b006078512083d3f69b826d2aa62698.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/tables/c01bc4b142236f9297a38742c9f61fa99b006078512083d3f69b826d2aa62698.jpg)

![fbadf59d2c96779bced185c78f239259b5118fe0158b4f8e91c54bf368964c73.jpg](../emnlp_results/230_CoLA_%20Compute-Efficient%20Pre-Training%20ofLLMs%20via%20Low-Rank%20Activation/tables/fbadf59d2c96779bced185c78f239259b5118fe0158b4f8e91c54bf368964c73.jpg)

## TS-CLIP: Time Series Understanding byCLIP


### Images

![040cfd4f81bcabe40bf5a8d7765fa3b97dcc4190dc26fd4174d072f1fcec7c3d.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/images/040cfd4f81bcabe40bf5a8d7765fa3b97dcc4190dc26fd4174d072f1fcec7c3d.jpg)

![0bac58c6c06cff7fb81957e4d91fa8d5e007b853390f8f0878e7385c2552f86a.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/images/0bac58c6c06cff7fb81957e4d91fa8d5e007b853390f8f0878e7385c2552f86a.jpg)

![18e7665f036b1322174bbac7e52d3077202cf995ff44985697a06bc072d96daa.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/images/18e7665f036b1322174bbac7e52d3077202cf995ff44985697a06bc072d96daa.jpg)

![493d2f4175f457b2cf611f67a7b32ab5e4f8e5689e89aa2f7242018c9f77b5f3.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/images/493d2f4175f457b2cf611f67a7b32ab5e4f8e5689e89aa2f7242018c9f77b5f3.jpg)

![5599faa5963694adfa4e914e4a03a4975aa3205b4e8c218c0af9e1e73f2c55e3.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/images/5599faa5963694adfa4e914e4a03a4975aa3205b4e8c218c0af9e1e73f2c55e3.jpg)

![6ab7982add07a4f05fc88ce6fbf5f24530046cc319e197a9226347ebd09a2382.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/images/6ab7982add07a4f05fc88ce6fbf5f24530046cc319e197a9226347ebd09a2382.jpg)

![ae2cb6b2816714a0c0df8fd2e3d8caf08f904d263499217df58e87997e2e6122.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/images/ae2cb6b2816714a0c0df8fd2e3d8caf08f904d263499217df58e87997e2e6122.jpg)

![b6c528b437ff2c761ad41b62e1e68c35dd3c266e80dab48e55e2d5a74bdb009d.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/images/b6c528b437ff2c761ad41b62e1e68c35dd3c266e80dab48e55e2d5a74bdb009d.jpg)

![d3a7f2b1c79320e62f677855c22e1c91928515c09853a6227aac4ff26567b290.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/images/d3a7f2b1c79320e62f677855c22e1c91928515c09853a6227aac4ff26567b290.jpg)

![e5de58d8e116d8ad6eb0010b1b2f5a34a4f7a5d432e7b07ff68fafa8882c4de1.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/images/e5de58d8e116d8ad6eb0010b1b2f5a34a4f7a5d432e7b07ff68fafa8882c4de1.jpg)

![eafa4a4d23a2d0c5266441806ca84f904a9e8414fae71168c933be6ac1c8bfcc.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/images/eafa4a4d23a2d0c5266441806ca84f904a9e8414fae71168c933be6ac1c8bfcc.jpg)

### Tables

![02773dce42e96b9c0fb4d8d1cca95dfcd7ace1fa3c582bcd107759bae64543ad.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/02773dce42e96b9c0fb4d8d1cca95dfcd7ace1fa3c582bcd107759bae64543ad.jpg)

![0d007dfa58423e23e111e39aacf065979409eff60ed4cf723d5f06d0d7de01e5.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/0d007dfa58423e23e111e39aacf065979409eff60ed4cf723d5f06d0d7de01e5.jpg)

![307e52635ba0ade01bb316ad09242e69cae618a212435420746870491a2e617c.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/307e52635ba0ade01bb316ad09242e69cae618a212435420746870491a2e617c.jpg)

![34f78845b1d066e311ab2c9c1dfc2cf5f867ac5b7fe8999a9eb59c6eaedc214d.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/34f78845b1d066e311ab2c9c1dfc2cf5f867ac5b7fe8999a9eb59c6eaedc214d.jpg)

![3a1239af8bbe35436f5496dc7bc048f62831d4d37cff9f0e06096c0ca3e2533a.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/3a1239af8bbe35436f5496dc7bc048f62831d4d37cff9f0e06096c0ca3e2533a.jpg)

![4d177da24e197ae4811e835f684d4b97a193ea4af76cc823a05956f21d5c2b82.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/4d177da24e197ae4811e835f684d4b97a193ea4af76cc823a05956f21d5c2b82.jpg)

![6e203a490c7aacb480c7c2a12296482ec530ca46b364c57b7059b3a96ad04249.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/6e203a490c7aacb480c7c2a12296482ec530ca46b364c57b7059b3a96ad04249.jpg)

![73c9f7bc6d7071476be407689702abeeff7f7c8d900d20c57ef0e447c57736cd.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/73c9f7bc6d7071476be407689702abeeff7f7c8d900d20c57ef0e447c57736cd.jpg)

![7aee4f85af3c12441bc6cf1a44004996155cead96973f01d471a72ad60bbb3d8.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/7aee4f85af3c12441bc6cf1a44004996155cead96973f01d471a72ad60bbb3d8.jpg)

![a8725c8a925d9668b85ffdd9672461faf931aba8e3c13443f019f182b438a281.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/a8725c8a925d9668b85ffdd9672461faf931aba8e3c13443f019f182b438a281.jpg)

![c1e800fb22f6f0845c23348003760b3a63b50465e413d65bd5ef86a26f41cab5.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/c1e800fb22f6f0845c23348003760b3a63b50465e413d65bd5ef86a26f41cab5.jpg)

![dbdb71ba557ffcf180719fbdf5f937c4421b7336c91684cac9b48f38c0253513.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/dbdb71ba557ffcf180719fbdf5f937c4421b7336c91684cac9b48f38c0253513.jpg)

![e90ce5f5e78f489588c122d1f169e87dcce695d870a7ca5ef1cb92d43c1773fb.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/e90ce5f5e78f489588c122d1f169e87dcce695d870a7ca5ef1cb92d43c1773fb.jpg)

![f76cc02e1e77944e80d1de6f11017a197c15576c689b54e7aa338f9134e3fa7b.jpg](../emnlp_results/231_TS-CLIP_%20Time%20Series%20Understanding%20byCLIP/tables/f76cc02e1e77944e80d1de6f11017a197c15576c689b54e7aa338f9134e3fa7b.jpg)

## MultiAgentESC: ALLM-based Multi-Agent Collaboration Framework for Emotional Support Conversation


### Images

![1894025fdb852f9240d68fa427956ac5cc20070b8ae1209e4b2357899088a83e.jpg](../emnlp_results/232_MultiAgentESC_%20ALLM-based%20Multi-Agent%20Collaboration%20Framework%20for%20Emotional%20Support%20Conversation/images/1894025fdb852f9240d68fa427956ac5cc20070b8ae1209e4b2357899088a83e.jpg)

![cb5ff6d96fea48b99bc02090dd6eda3027a9d67712d3cf50f1cc6f43f82e1b99.jpg](../emnlp_results/232_MultiAgentESC_%20ALLM-based%20Multi-Agent%20Collaboration%20Framework%20for%20Emotional%20Support%20Conversation/images/cb5ff6d96fea48b99bc02090dd6eda3027a9d67712d3cf50f1cc6f43f82e1b99.jpg)

![e713efff9004e066dbcd75d6454de21a5989a76127a7f4416310defa538f60c7.jpg](../emnlp_results/232_MultiAgentESC_%20ALLM-based%20Multi-Agent%20Collaboration%20Framework%20for%20Emotional%20Support%20Conversation/images/e713efff9004e066dbcd75d6454de21a5989a76127a7f4416310defa538f60c7.jpg)

### Tables

![2a4b993a2d29c983ec93b12db5886b014028c160ca22d55f7253f5dc413a5e2b.jpg](../emnlp_results/232_MultiAgentESC_%20ALLM-based%20Multi-Agent%20Collaboration%20Framework%20for%20Emotional%20Support%20Conversation/tables/2a4b993a2d29c983ec93b12db5886b014028c160ca22d55f7253f5dc413a5e2b.jpg)

![2fe34f14101e8e97cd38b91e86981c25fdd1a053d5e2ea7a22bc66b26b14bce6.jpg](../emnlp_results/232_MultiAgentESC_%20ALLM-based%20Multi-Agent%20Collaboration%20Framework%20for%20Emotional%20Support%20Conversation/tables/2fe34f14101e8e97cd38b91e86981c25fdd1a053d5e2ea7a22bc66b26b14bce6.jpg)

![43d54385923473f268c5d6d3da8f334ded26a5d75d3569b97c78d9817cc05f40.jpg](../emnlp_results/232_MultiAgentESC_%20ALLM-based%20Multi-Agent%20Collaboration%20Framework%20for%20Emotional%20Support%20Conversation/tables/43d54385923473f268c5d6d3da8f334ded26a5d75d3569b97c78d9817cc05f40.jpg)

![520a1172ae5fd3773e9bce3a2ebc1ccbdb66533d0742d2f7e5ca9c57f5a8bac7.jpg](../emnlp_results/232_MultiAgentESC_%20ALLM-based%20Multi-Agent%20Collaboration%20Framework%20for%20Emotional%20Support%20Conversation/tables/520a1172ae5fd3773e9bce3a2ebc1ccbdb66533d0742d2f7e5ca9c57f5a8bac7.jpg)

![67e10b8213bf7f78c6a61962539e24ad0ccca660cddf32d4a43087fc0b12c9e3.jpg](../emnlp_results/232_MultiAgentESC_%20ALLM-based%20Multi-Agent%20Collaboration%20Framework%20for%20Emotional%20Support%20Conversation/tables/67e10b8213bf7f78c6a61962539e24ad0ccca660cddf32d4a43087fc0b12c9e3.jpg)

![be718793d3a96cc0dfdaecd1afe7c78460d5608c4d29e528aae776137c336f78.jpg](../emnlp_results/232_MultiAgentESC_%20ALLM-based%20Multi-Agent%20Collaboration%20Framework%20for%20Emotional%20Support%20Conversation/tables/be718793d3a96cc0dfdaecd1afe7c78460d5608c4d29e528aae776137c336f78.jpg)

![fb73b8c15e2f58cab483eedaf24c9383f83ef3e5e9bf9c872cc6a36cb6006846.jpg](../emnlp_results/232_MultiAgentESC_%20ALLM-based%20Multi-Agent%20Collaboration%20Framework%20for%20Emotional%20Support%20Conversation/tables/fb73b8c15e2f58cab483eedaf24c9383f83ef3e5e9bf9c872cc6a36cb6006846.jpg)

## Continuously SteeringLLMs Sensitivity to Contextual Knowledge with Proxy Models


### Images

![10072f4203521ce3e681f8021c12eb4ee9a79663d260674ab0b314f82c11fbc4.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/images/10072f4203521ce3e681f8021c12eb4ee9a79663d260674ab0b314f82c11fbc4.jpg)

![1a9c6e1dda48b74c6737044e65118f6ecc3ec6ab9f4424ef2b7a58c7852eec7e.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/images/1a9c6e1dda48b74c6737044e65118f6ecc3ec6ab9f4424ef2b7a58c7852eec7e.jpg)

![278e916a2c2f090a8cd2b70e57ede7a6bfd0b4aba017a95738f2d61f8ae6a74e.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/images/278e916a2c2f090a8cd2b70e57ede7a6bfd0b4aba017a95738f2d61f8ae6a74e.jpg)

![2a12168f6b4f9e02c90b8deca49b97fbf4fe0c4160d2e96d947ca9a4bf347b3b.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/images/2a12168f6b4f9e02c90b8deca49b97fbf4fe0c4160d2e96d947ca9a4bf347b3b.jpg)

![2f921b5de68333d140565fc288c9e4d9b17e461f32f1eed85d513a3b3fe561f1.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/images/2f921b5de68333d140565fc288c9e4d9b17e461f32f1eed85d513a3b3fe561f1.jpg)

![4534245771edeabc96607237ad540c354d1364786924a3cb47c0d028fd705646.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/images/4534245771edeabc96607237ad540c354d1364786924a3cb47c0d028fd705646.jpg)

![7e8f794266138b137c31aafa6c0e7c51a3651e66153e3a2097c0ddc7e12db4f7.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/images/7e8f794266138b137c31aafa6c0e7c51a3651e66153e3a2097c0ddc7e12db4f7.jpg)

![91a6c7cfcf41c04a620203251ac45f0bf150330d5b930c688f541708a40cbf04.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/images/91a6c7cfcf41c04a620203251ac45f0bf150330d5b930c688f541708a40cbf04.jpg)

![9484ceb257430caae26161a41003adf2c14d99ea0ec7b8f6f5043e2fe7c84257.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/images/9484ceb257430caae26161a41003adf2c14d99ea0ec7b8f6f5043e2fe7c84257.jpg)

![95194ed1a7273df1d8573e8a9384ce4c3c5f2f4ccad0cd1dcb47d90b348fb502.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/images/95194ed1a7273df1d8573e8a9384ce4c3c5f2f4ccad0cd1dcb47d90b348fb502.jpg)

![b4b828c17d7a172c23acf1e3080d2669f703d0aa27b97176143080b06df37dc9.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/images/b4b828c17d7a172c23acf1e3080d2669f703d0aa27b97176143080b06df37dc9.jpg)

![ba9c6b64fc6fd1e5e63ce737a3d11663abf54dcbd170011cc353ae4297c0da0b.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/images/ba9c6b64fc6fd1e5e63ce737a3d11663abf54dcbd170011cc353ae4297c0da0b.jpg)

### Tables

![1407ba8bba937a70cadd2434d1395755a60ddf263492c6513e7722c77bb38ee4.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/tables/1407ba8bba937a70cadd2434d1395755a60ddf263492c6513e7722c77bb38ee4.jpg)

![3dcef06d6bd4b56abca994e4140973088177563993c4e4154c21ae870ac643f4.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/tables/3dcef06d6bd4b56abca994e4140973088177563993c4e4154c21ae870ac643f4.jpg)

![587bac34f46aef2dbb81a58145f3ea334e23e3172f8b0831e50b15f335381e96.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/tables/587bac34f46aef2dbb81a58145f3ea334e23e3172f8b0831e50b15f335381e96.jpg)

![a61ff26c97d377f6e2ee83e22cb3f1335c593c53050b2c3c675ea14e987606df.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/tables/a61ff26c97d377f6e2ee83e22cb3f1335c593c53050b2c3c675ea14e987606df.jpg)

![a986759930b6bb6e2b9391447b8a0aee619d895c3caf8a2b440aa60f74259fb0.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/tables/a986759930b6bb6e2b9391447b8a0aee619d895c3caf8a2b440aa60f74259fb0.jpg)

![bec4ed6f4ba16d7d47f9929c545f4ec01a96b069191e8850c88cdc26db07e7de.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/tables/bec4ed6f4ba16d7d47f9929c545f4ec01a96b069191e8850c88cdc26db07e7de.jpg)

![dd5aa72579c24dffc6320926ea902cc36641fac7d8b52cd5fd5c5e9abd8fab5c.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/tables/dd5aa72579c24dffc6320926ea902cc36641fac7d8b52cd5fd5c5e9abd8fab5c.jpg)

![f2a1c1321962700e862fb6f2bf5bcc5ee5133b65b77567fbbe3ad2dfb25d2f53.jpg](../emnlp_results/233_Continuously%20SteeringLLMs%20Sensitivity%20to%20Contextual%20Knowledge%20with%20Proxy%20Models/tables/f2a1c1321962700e862fb6f2bf5bcc5ee5133b65b77567fbbe3ad2dfb25d2f53.jpg)

## ProbingLLMWorld Models: Enhancing Guesstimation with Wisdom of Crowds Decoding


### Images

![b1614d1730f672e39f1a3d12c5279c3fa1be1acfddff300983e266eab2a7c550.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/images/b1614d1730f672e39f1a3d12c5279c3fa1be1acfddff300983e266eab2a7c550.jpg)

![ec7a81c90ed4e39cad3191ab6e8cf70273a854cf9a56bd73ef6dfcd26dcc5cde.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/images/ec7a81c90ed4e39cad3191ab6e8cf70273a854cf9a56bd73ef6dfcd26dcc5cde.jpg)

![f3c2244eaaee9934f88bae9d5fbc0de7605515b392b996eab057ce3ffcd2866b.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/images/f3c2244eaaee9934f88bae9d5fbc0de7605515b392b996eab057ce3ffcd2866b.jpg)

### Tables

![2a3e9a5950065f18a8a2c48be76806208dc71f2f583ec3cf5d4e1562c2a824a8.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/tables/2a3e9a5950065f18a8a2c48be76806208dc71f2f583ec3cf5d4e1562c2a824a8.jpg)

![488ef65ce22396f3f657bea0dc7ffdbfa51f8b91f00dacf161dbeca2d28988bd.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/tables/488ef65ce22396f3f657bea0dc7ffdbfa51f8b91f00dacf161dbeca2d28988bd.jpg)

![4d530c05d7f30208c4279c04e0ee9193478310746bd48b09cf1719bc89dd95d0.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/tables/4d530c05d7f30208c4279c04e0ee9193478310746bd48b09cf1719bc89dd95d0.jpg)

![56557b2678c5e2d5bcfc296d8bfab352fcd5d52cb238aa61617efb8a6b6b6da3.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/tables/56557b2678c5e2d5bcfc296d8bfab352fcd5d52cb238aa61617efb8a6b6b6da3.jpg)

![5969487cbfcea14c00a680b6b453d9fcf28ccf0278935aac49be6043ed030f43.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/tables/5969487cbfcea14c00a680b6b453d9fcf28ccf0278935aac49be6043ed030f43.jpg)

![6635a9956f91094eb146ee6f982ca5eb669d6036f3158045546d1da17fc1a43b.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/tables/6635a9956f91094eb146ee6f982ca5eb669d6036f3158045546d1da17fc1a43b.jpg)

![7f8642780fce280e277de80b7f9dad3e2f4157d9b4f5699bbd9c66b806d1d008.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/tables/7f8642780fce280e277de80b7f9dad3e2f4157d9b4f5699bbd9c66b806d1d008.jpg)

![87780c32afedaa5db244de9000514a46b340b9da2439cbdf7e34c4613cb35cff.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/tables/87780c32afedaa5db244de9000514a46b340b9da2439cbdf7e34c4613cb35cff.jpg)

![b168d70acbf25466ee60a5395d3e4202b550abe0421b7ea3f1cc084a8c8aa6fe.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/tables/b168d70acbf25466ee60a5395d3e4202b550abe0421b7ea3f1cc084a8c8aa6fe.jpg)

![d487dd41a20e94c4d586defa99825f9281bc4d6e65d0bfb32b49f314e3d28628.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/tables/d487dd41a20e94c4d586defa99825f9281bc4d6e65d0bfb32b49f314e3d28628.jpg)

![ff8713ce2eff9840f143d851233c98aac9269a7e94f17d3f3b67f6eefa37cd76.jpg](../emnlp_results/234_ProbingLLMWorld%20Models_%20Enhancing%20Guesstimation%20with%20Wisdom%20of%20Crowds%20Decoding/tables/ff8713ce2eff9840f143d851233c98aac9269a7e94f17d3f3b67f6eefa37cd76.jpg)

## Recall with Reasoning: Chain-of-Thought Distillation for Mamba’s Long-Context Memory and Extrapolation


### Images

![0ed17670bd5672fb25e6f424b2ce7c34c5f36cd909897d64dc4e25025c882d42.jpg](../emnlp_results/235_Recall%20with%20Reasoning_%20Chain-of-Thought%20Distillation%20for%20Mamba%E2%80%99s%20Long-Context%20Memory%20and%20Extrapolati/images/0ed17670bd5672fb25e6f424b2ce7c34c5f36cd909897d64dc4e25025c882d42.jpg)

![efed49c037997c3d684494ea09b8d708accdbf566e8e062141113874a3a607ab.jpg](../emnlp_results/235_Recall%20with%20Reasoning_%20Chain-of-Thought%20Distillation%20for%20Mamba%E2%80%99s%20Long-Context%20Memory%20and%20Extrapolati/images/efed49c037997c3d684494ea09b8d708accdbf566e8e062141113874a3a607ab.jpg)

### Tables

![1797cacd8890d07496e020af95774496abe90e5241859438bb7d3c8e12b03d3b.jpg](../emnlp_results/235_Recall%20with%20Reasoning_%20Chain-of-Thought%20Distillation%20for%20Mamba%E2%80%99s%20Long-Context%20Memory%20and%20Extrapolati/tables/1797cacd8890d07496e020af95774496abe90e5241859438bb7d3c8e12b03d3b.jpg)

![6d865a5978ce00215d707c4bf96f68ce1ee85863ec9020b296cc4e0ae5cf7f0a.jpg](../emnlp_results/235_Recall%20with%20Reasoning_%20Chain-of-Thought%20Distillation%20for%20Mamba%E2%80%99s%20Long-Context%20Memory%20and%20Extrapolati/tables/6d865a5978ce00215d707c4bf96f68ce1ee85863ec9020b296cc4e0ae5cf7f0a.jpg)

![811814708ef887052a1a67e911c7fab42fdd404d245b66aa410a034c48c3eaa3.jpg](../emnlp_results/235_Recall%20with%20Reasoning_%20Chain-of-Thought%20Distillation%20for%20Mamba%E2%80%99s%20Long-Context%20Memory%20and%20Extrapolati/tables/811814708ef887052a1a67e911c7fab42fdd404d245b66aa410a034c48c3eaa3.jpg)

![f01d55f3517e7d0a952f0954d2d385e3fd7dd0bc3b4c99e76df6acc86bb410a1.jpg](../emnlp_results/235_Recall%20with%20Reasoning_%20Chain-of-Thought%20Distillation%20for%20Mamba%E2%80%99s%20Long-Context%20Memory%20and%20Extrapolati/tables/f01d55f3517e7d0a952f0954d2d385e3fd7dd0bc3b4c99e76df6acc86bb410a1.jpg)

## Scalable Data Synthesis through Human-like Cognitive Imitation and Data Recombination


### Images

![3f5e4512b6fda2908cfaff94ed0f79a3ab5f1a04eeabbe82176d64c602e74b2f.jpg](../emnlp_results/236_Scalable%20Data%20Synthesis%20through%20Human-like%20Cognitive%20Imitation%20and%20Data%20Recombination/images/3f5e4512b6fda2908cfaff94ed0f79a3ab5f1a04eeabbe82176d64c602e74b2f.jpg)

![4ca88b45843a5d414fe059a69d4a32a87eb517656418556929dca8104f35c050.jpg](../emnlp_results/236_Scalable%20Data%20Synthesis%20through%20Human-like%20Cognitive%20Imitation%20and%20Data%20Recombination/images/4ca88b45843a5d414fe059a69d4a32a87eb517656418556929dca8104f35c050.jpg)

![7cab617796d7606e5252ac708faab126a8835c18c6b5550c2e8dfb37c11ce4aa.jpg](../emnlp_results/236_Scalable%20Data%20Synthesis%20through%20Human-like%20Cognitive%20Imitation%20and%20Data%20Recombination/images/7cab617796d7606e5252ac708faab126a8835c18c6b5550c2e8dfb37c11ce4aa.jpg)

![ab31409d2e8519d5ccc4a711be276ea234f0d4d51540b153dc8a6becfdf8aa91.jpg](../emnlp_results/236_Scalable%20Data%20Synthesis%20through%20Human-like%20Cognitive%20Imitation%20and%20Data%20Recombination/images/ab31409d2e8519d5ccc4a711be276ea234f0d4d51540b153dc8a6becfdf8aa91.jpg)

![d797de320e76e7cb12f9d705f8bbfe747151d462901e0f50befdf36047a6122a.jpg](../emnlp_results/236_Scalable%20Data%20Synthesis%20through%20Human-like%20Cognitive%20Imitation%20and%20Data%20Recombination/images/d797de320e76e7cb12f9d705f8bbfe747151d462901e0f50befdf36047a6122a.jpg)

### Tables

![0f9b485b62cf0099e0d4289d70267af3a1d48750f16e772c352e4da775d919a2.jpg](../emnlp_results/236_Scalable%20Data%20Synthesis%20through%20Human-like%20Cognitive%20Imitation%20and%20Data%20Recombination/tables/0f9b485b62cf0099e0d4289d70267af3a1d48750f16e772c352e4da775d919a2.jpg)

![350997caba93a0c75568914c86109b4d4240cb358b85dbf22ae3c4142f4b5cf3.jpg](../emnlp_results/236_Scalable%20Data%20Synthesis%20through%20Human-like%20Cognitive%20Imitation%20and%20Data%20Recombination/tables/350997caba93a0c75568914c86109b4d4240cb358b85dbf22ae3c4142f4b5cf3.jpg)

![7bbae9ac61ece75e2ad222004482e3c542f4bdc8cb7a45c05ca830e32e00165c.jpg](../emnlp_results/236_Scalable%20Data%20Synthesis%20through%20Human-like%20Cognitive%20Imitation%20and%20Data%20Recombination/tables/7bbae9ac61ece75e2ad222004482e3c542f4bdc8cb7a45c05ca830e32e00165c.jpg)

![f171b0c43c4af70cd1bbe6a4643e073eeb512409720f93df317644b5ab5bb91c.jpg](../emnlp_results/236_Scalable%20Data%20Synthesis%20through%20Human-like%20Cognitive%20Imitation%20and%20Data%20Recombination/tables/f171b0c43c4af70cd1bbe6a4643e073eeb512409720f93df317644b5ab5bb91c.jpg)

## BeSimulator: A Large Language Model Powered Text-based Behavior Simulator


### Images

![2e4e67d410cb0533841facc26d8c9c1e1ccaffaa5aaf83d3cc547d38642e9046.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/images/2e4e67d410cb0533841facc26d8c9c1e1ccaffaa5aaf83d3cc547d38642e9046.jpg)

![392dc4f303ae0c4a440ddf0e0d8057e5a81223038e64eedbabd0af1f9bc58fb4.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/images/392dc4f303ae0c4a440ddf0e0d8057e5a81223038e64eedbabd0af1f9bc58fb4.jpg)

![8112a1157d36703f71fe9590773adcb705d7cbeec27721ac69ee35bbccec1991.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/images/8112a1157d36703f71fe9590773adcb705d7cbeec27721ac69ee35bbccec1991.jpg)

![e2186eb3f2da534adc89be6f48e903b100f21944072a822aee69a3bbd5419684.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/images/e2186eb3f2da534adc89be6f48e903b100f21944072a822aee69a3bbd5419684.jpg)

![fafd13525b251f0696505d68264df8c4a80dd9f8fc3f21916a8f28f32352997f.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/images/fafd13525b251f0696505d68264df8c4a80dd9f8fc3f21916a8f28f32352997f.jpg)

### Tables

![01a512b18b979a5ac6f867c8d4e1fc55da320302c534d5a4f0f04480f472986d.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/tables/01a512b18b979a5ac6f867c8d4e1fc55da320302c534d5a4f0f04480f472986d.jpg)

![0356f2b0e8fade98e993e644128d14edab5eee66a976fff192a2fc6fcca29372.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/tables/0356f2b0e8fade98e993e644128d14edab5eee66a976fff192a2fc6fcca29372.jpg)

![037ee9c667ee81bd83570daacff1bebf19e1ef6fa14f31a86c50a2a57be18d4f.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/tables/037ee9c667ee81bd83570daacff1bebf19e1ef6fa14f31a86c50a2a57be18d4f.jpg)

![27b91a22156700011956d466c5e3680fa866f688779b271f4c644ec03105c5ae.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/tables/27b91a22156700011956d466c5e3680fa866f688779b271f4c644ec03105c5ae.jpg)

![306eb3ff823d8bb004f5cdd84c9d0deaf607ca08da7b5439dbbb01df671201a9.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/tables/306eb3ff823d8bb004f5cdd84c9d0deaf607ca08da7b5439dbbb01df671201a9.jpg)

![85f10734077fab90d2711880a321fe0a8abc16dd846f23b602bc509d07faae44.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/tables/85f10734077fab90d2711880a321fe0a8abc16dd846f23b602bc509d07faae44.jpg)

![966d60cc846671b14d6ba22f4387f075ea16816467ce569c138561806ed546fd.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/tables/966d60cc846671b14d6ba22f4387f075ea16816467ce569c138561806ed546fd.jpg)

![a3a46e5c72897e45b80a36063ae61d26a4f9269cc8ba841aa22073ef1338e15d.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/tables/a3a46e5c72897e45b80a36063ae61d26a4f9269cc8ba841aa22073ef1338e15d.jpg)

![cf423be58a708d26fa731b491e0afeb263ff52816f4e54745f1c3a22cab2dba1.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/tables/cf423be58a708d26fa731b491e0afeb263ff52816f4e54745f1c3a22cab2dba1.jpg)

![dea844e6ff8c2c93ecab3b577c1a856e5a7357f2b39fe936ad583c059db7dc57.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/tables/dea844e6ff8c2c93ecab3b577c1a856e5a7357f2b39fe936ad583c059db7dc57.jpg)

![e5fc5ebec8b97fa598425f854359b8bc4d9dbccb544d05f50874264c4b0cbb95.jpg](../emnlp_results/237_BeSimulator_%20A%20Large%20Language%20Model%20Powered%20Text-based%20Behavior%20Simulator/tables/e5fc5ebec8b97fa598425f854359b8bc4d9dbccb544d05f50874264c4b0cbb95.jpg)

## Too Consistent to Detect: A Study of Self-Consistent Errors inLLMs


### Images

![12e579ddfe9837981e738d19f7c3799dfce25782f8f7af9daff6cf1f50c32586.jpg](../emnlp_results/238_Too%20Consistent%20to%20Detect_%20A%20Study%20of%20Self-Consistent%20Errors%20inLLMs/images/12e579ddfe9837981e738d19f7c3799dfce25782f8f7af9daff6cf1f50c32586.jpg)

![2e0381329f7931cfb393164d375eb5cff5cae59bca08681162ea7eefb53eccdb.jpg](../emnlp_results/238_Too%20Consistent%20to%20Detect_%20A%20Study%20of%20Self-Consistent%20Errors%20inLLMs/images/2e0381329f7931cfb393164d375eb5cff5cae59bca08681162ea7eefb53eccdb.jpg)

![4c6f5cfd6f1c9735bfdc319b5cc7a33336980f2aa05f1dd2aa4df3583adc23d2.jpg](../emnlp_results/238_Too%20Consistent%20to%20Detect_%20A%20Study%20of%20Self-Consistent%20Errors%20inLLMs/images/4c6f5cfd6f1c9735bfdc319b5cc7a33336980f2aa05f1dd2aa4df3583adc23d2.jpg)

![6b3fefff6357215e28a24b4f1986d3eb9816e8d71388c4e0ea745737763ca04f.jpg](../emnlp_results/238_Too%20Consistent%20to%20Detect_%20A%20Study%20of%20Self-Consistent%20Errors%20inLLMs/images/6b3fefff6357215e28a24b4f1986d3eb9816e8d71388c4e0ea745737763ca04f.jpg)

### Tables

![03481dd968282d96fa8a2c7bc8d8a112a4bc93292cd70faf9a4eefe437060e9a.jpg](../emnlp_results/238_Too%20Consistent%20to%20Detect_%20A%20Study%20of%20Self-Consistent%20Errors%20inLLMs/tables/03481dd968282d96fa8a2c7bc8d8a112a4bc93292cd70faf9a4eefe437060e9a.jpg)

![2e41debb8d687f090b3a2958e706ce42e9d83e55552f15b3075a0727883b68a2.jpg](../emnlp_results/238_Too%20Consistent%20to%20Detect_%20A%20Study%20of%20Self-Consistent%20Errors%20inLLMs/tables/2e41debb8d687f090b3a2958e706ce42e9d83e55552f15b3075a0727883b68a2.jpg)

![943084ec617355e1640e8c0e3609cc1a6c84528f8dddddf3f73a45887d45c4a9.jpg](../emnlp_results/238_Too%20Consistent%20to%20Detect_%20A%20Study%20of%20Self-Consistent%20Errors%20inLLMs/tables/943084ec617355e1640e8c0e3609cc1a6c84528f8dddddf3f73a45887d45c4a9.jpg)

![ddb4deafc4d776c89a95cafcc53b4e8adda0c8d015635e50e6ace938f8a9fdfe.jpg](../emnlp_results/238_Too%20Consistent%20to%20Detect_%20A%20Study%20of%20Self-Consistent%20Errors%20inLLMs/tables/ddb4deafc4d776c89a95cafcc53b4e8adda0c8d015635e50e6ace938f8a9fdfe.jpg)

## pFedGPT: Hierarchically OptimizingLoRAAggregation Weights for Personalized FederatedGPTModels


### Images

![23c92c3641b8bc9a26a8b9a9ccf6194c3c681b29e25e09bdb7b2560d3a3db0d6.jpg](../emnlp_results/239_pFedGPT_%20Hierarchically%20OptimizingLoRAAggregation%20Weights%20for%20Personalized%20FederatedGPTModels/images/23c92c3641b8bc9a26a8b9a9ccf6194c3c681b29e25e09bdb7b2560d3a3db0d6.jpg)

![2fe2b3fd1c98d66db52eb92dcff443533ab4ab9d6f8cbc17f1e9e761081a5fe8.jpg](../emnlp_results/239_pFedGPT_%20Hierarchically%20OptimizingLoRAAggregation%20Weights%20for%20Personalized%20FederatedGPTModels/images/2fe2b3fd1c98d66db52eb92dcff443533ab4ab9d6f8cbc17f1e9e761081a5fe8.jpg)

![354ea36e83c58ac8e536b5351b33cb11d48ffbc600bf921b987aaf5d302b0f2c.jpg](../emnlp_results/239_pFedGPT_%20Hierarchically%20OptimizingLoRAAggregation%20Weights%20for%20Personalized%20FederatedGPTModels/images/354ea36e83c58ac8e536b5351b33cb11d48ffbc600bf921b987aaf5d302b0f2c.jpg)

![5848f719da197683cf9a3be55a267f2e81833a6fab55fc9046615f26d79217e9.jpg](../emnlp_results/239_pFedGPT_%20Hierarchically%20OptimizingLoRAAggregation%20Weights%20for%20Personalized%20FederatedGPTModels/images/5848f719da197683cf9a3be55a267f2e81833a6fab55fc9046615f26d79217e9.jpg)

![e8432b4712fc4b8708a29eecfb3beb1c1e7da4f9e9392d0fd167166a862ff941.jpg](../emnlp_results/239_pFedGPT_%20Hierarchically%20OptimizingLoRAAggregation%20Weights%20for%20Personalized%20FederatedGPTModels/images/e8432b4712fc4b8708a29eecfb3beb1c1e7da4f9e9392d0fd167166a862ff941.jpg)

### Tables

![0538f0f921c754b000821ff9347d266942a96c0e8ab9d2ffcb76e54446eab333.jpg](../emnlp_results/239_pFedGPT_%20Hierarchically%20OptimizingLoRAAggregation%20Weights%20for%20Personalized%20FederatedGPTModels/tables/0538f0f921c754b000821ff9347d266942a96c0e8ab9d2ffcb76e54446eab333.jpg)

![12e8afe3e447b3c997f447dbdb3fa97be76d7e243b7dcc6d6a369066928e1fd8.jpg](../emnlp_results/239_pFedGPT_%20Hierarchically%20OptimizingLoRAAggregation%20Weights%20for%20Personalized%20FederatedGPTModels/tables/12e8afe3e447b3c997f447dbdb3fa97be76d7e243b7dcc6d6a369066928e1fd8.jpg)

![8815226c724374e61b9c36e3ff01f8a341db1e974afe1d26b7a8f7068b790a63.jpg](../emnlp_results/239_pFedGPT_%20Hierarchically%20OptimizingLoRAAggregation%20Weights%20for%20Personalized%20FederatedGPTModels/tables/8815226c724374e61b9c36e3ff01f8a341db1e974afe1d26b7a8f7068b790a63.jpg)

![913aae97fc178a39b69525aa1af53ccd9242c875f2ebb8378887c454aeb4ce22.jpg](../emnlp_results/239_pFedGPT_%20Hierarchically%20OptimizingLoRAAggregation%20Weights%20for%20Personalized%20FederatedGPTModels/tables/913aae97fc178a39b69525aa1af53ccd9242c875f2ebb8378887c454aeb4ce22.jpg)

![ef8cde639517f97b6c257647f8cab959370d6a055132161c786c8e82951cb628.jpg](../emnlp_results/239_pFedGPT_%20Hierarchically%20OptimizingLoRAAggregation%20Weights%20for%20Personalized%20FederatedGPTModels/tables/ef8cde639517f97b6c257647f8cab959370d6a055132161c786c8e82951cb628.jpg)

## QSpec: Speculative Decoding with Complementary Quantization Schemes


### Images

![2fa5a2d0c1b6244e636629a6337dda3918d86936742bffbc1ebd9da0b57dda21.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/images/2fa5a2d0c1b6244e636629a6337dda3918d86936742bffbc1ebd9da0b57dda21.jpg)

![350f39ac9c5fc06ae6b9956cf79ce63754f224dac59f4fcad780edf6d8050816.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/images/350f39ac9c5fc06ae6b9956cf79ce63754f224dac59f4fcad780edf6d8050816.jpg)

![8240a930d92c01989181d69c57a4109a93d7159d8fc35f615ab2d559bca2ae23.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/images/8240a930d92c01989181d69c57a4109a93d7159d8fc35f615ab2d559bca2ae23.jpg)

![9ebaa27e6d8b79a20a994d7619d1b958e3397c32d6b8e4b3d564a73c10c1c88c.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/images/9ebaa27e6d8b79a20a994d7619d1b958e3397c32d6b8e4b3d564a73c10c1c88c.jpg)

![aaa71db1c1ce0052ef8fd82c434b3e1c6711fecc1234e3e13106459f7e7fc4d2.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/images/aaa71db1c1ce0052ef8fd82c434b3e1c6711fecc1234e3e13106459f7e7fc4d2.jpg)

![d80c89ce65f8a19419c1fa838356f4cb017e5ae422fff903194190a6f62055c4.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/images/d80c89ce65f8a19419c1fa838356f4cb017e5ae422fff903194190a6f62055c4.jpg)

![f668728d76e0836d6e24540823a2a95cbde443a9f12d45139207a864b8e2050f.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/images/f668728d76e0836d6e24540823a2a95cbde443a9f12d45139207a864b8e2050f.jpg)

### Tables

![025fa5acf67b4b98fec3126d2a6c01e41a1f6f46debc9f0b2dc35921072ee6e0.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/tables/025fa5acf67b4b98fec3126d2a6c01e41a1f6f46debc9f0b2dc35921072ee6e0.jpg)

![0d4c6a62ad0ae355945619c9baa1ffb97c7c9ba90ddca2eef913e287c8041d5f.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/tables/0d4c6a62ad0ae355945619c9baa1ffb97c7c9ba90ddca2eef913e287c8041d5f.jpg)

![2fe0c69750bd83504040fb70e195d8a60cc3ae538917b0cd58622a69cc25357b.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/tables/2fe0c69750bd83504040fb70e195d8a60cc3ae538917b0cd58622a69cc25357b.jpg)

![36762b03ef350bbae0ff97c055831b30ac44ad3c2071c9e423a0fca34389ed47.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/tables/36762b03ef350bbae0ff97c055831b30ac44ad3c2071c9e423a0fca34389ed47.jpg)

![b32bbbadf0a149fa4abd0a35089ac7e04bc36fd5e8b01c4cd00c408f97c737db.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/tables/b32bbbadf0a149fa4abd0a35089ac7e04bc36fd5e8b01c4cd00c408f97c737db.jpg)

![c6b8de12dbb54390950fb291589daa9573234601e01238258f0403e4a1d7dc28.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/tables/c6b8de12dbb54390950fb291589daa9573234601e01238258f0403e4a1d7dc28.jpg)

![d3c047f2a1536dd8f6683f6470aff1b5bb7604a4776486dad290e2bf572f0de0.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/tables/d3c047f2a1536dd8f6683f6470aff1b5bb7604a4776486dad290e2bf572f0de0.jpg)

![da927d888939a0854af22f9dc9687dd20cd3bad558afc25f27ab8d528b2e6e01.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/tables/da927d888939a0854af22f9dc9687dd20cd3bad558afc25f27ab8d528b2e6e01.jpg)

![dae947cf821d69e9bc97b358cf6a66c15fd4ef32b75ff87781f51e09835a65cd.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/tables/dae947cf821d69e9bc97b358cf6a66c15fd4ef32b75ff87781f51e09835a65cd.jpg)

![dfcdc9d1fb7382a45a42c13b163c11a6e2375d5007e0d2b076908804d88ff942.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/tables/dfcdc9d1fb7382a45a42c13b163c11a6e2375d5007e0d2b076908804d88ff942.jpg)

![f5297ae9d365696c894c5cea0c57a252a740a2c2e3c9178a82134d9c3f4f33f5.jpg](../emnlp_results/240_QSpec_%20Speculative%20Decoding%20with%20Complementary%20Quantization%20Schemes/tables/f5297ae9d365696c894c5cea0c57a252a740a2c2e3c9178a82134d9c3f4f33f5.jpg)

## Co-EvolvingLLMs and Embedding Models via Density-Guided Preference Optimization for Text Clustering


### Images

![07d3ca0081e262b060119b2816f9e59763fb875a69fcf46cb4331a5062340148.jpg](../emnlp_results/241_Co-EvolvingLLMs%20and%20Embedding%20Models%20via%20Density-Guided%20Preference%20Optimization%20for%20Text%20Clustering/images/07d3ca0081e262b060119b2816f9e59763fb875a69fcf46cb4331a5062340148.jpg)

![85fc5def3859af8f4bc5609083d3f49c351ab44f5fa2a1bc451923f5beae7cc5.jpg](../emnlp_results/241_Co-EvolvingLLMs%20and%20Embedding%20Models%20via%20Density-Guided%20Preference%20Optimization%20for%20Text%20Clustering/images/85fc5def3859af8f4bc5609083d3f49c351ab44f5fa2a1bc451923f5beae7cc5.jpg)

![a87d4bbfc953ad70edf1790801e0290fd8c061d8e73d39f92d8b108c1c3362f6.jpg](../emnlp_results/241_Co-EvolvingLLMs%20and%20Embedding%20Models%20via%20Density-Guided%20Preference%20Optimization%20for%20Text%20Clustering/images/a87d4bbfc953ad70edf1790801e0290fd8c061d8e73d39f92d8b108c1c3362f6.jpg)

### Tables

![1885b6b8b275b18dd4976c8057693eaeb0ae61ac4f125b399ad2312aaa326098.jpg](../emnlp_results/241_Co-EvolvingLLMs%20and%20Embedding%20Models%20via%20Density-Guided%20Preference%20Optimization%20for%20Text%20Clustering/tables/1885b6b8b275b18dd4976c8057693eaeb0ae61ac4f125b399ad2312aaa326098.jpg)

![30fa9638df4c4be2bcfe93ef9c2c4bf952cb0d25374d6d433639024611fa7664.jpg](../emnlp_results/241_Co-EvolvingLLMs%20and%20Embedding%20Models%20via%20Density-Guided%20Preference%20Optimization%20for%20Text%20Clustering/tables/30fa9638df4c4be2bcfe93ef9c2c4bf952cb0d25374d6d433639024611fa7664.jpg)

![67ba94f27e3f2a4a4525b9d98bb239e877c3319ec163444b0f13331ba294e3d7.jpg](../emnlp_results/241_Co-EvolvingLLMs%20and%20Embedding%20Models%20via%20Density-Guided%20Preference%20Optimization%20for%20Text%20Clustering/tables/67ba94f27e3f2a4a4525b9d98bb239e877c3319ec163444b0f13331ba294e3d7.jpg)

![78dec73b38b781b0ef6731e1c97db0a761288e9ba022b336e9d783113b144e21.jpg](../emnlp_results/241_Co-EvolvingLLMs%20and%20Embedding%20Models%20via%20Density-Guided%20Preference%20Optimization%20for%20Text%20Clustering/tables/78dec73b38b781b0ef6731e1c97db0a761288e9ba022b336e9d783113b144e21.jpg)

![8e1624777773590dd6d502dd105584169e7acfee4fc8e9d6f72b8593ccdbebf6.jpg](../emnlp_results/241_Co-EvolvingLLMs%20and%20Embedding%20Models%20via%20Density-Guided%20Preference%20Optimization%20for%20Text%20Clustering/tables/8e1624777773590dd6d502dd105584169e7acfee4fc8e9d6f72b8593ccdbebf6.jpg)

![bcb2214572e9b165201c04ed17926c91f77700ca421cf86a1a03f46f964b6e7f.jpg](../emnlp_results/241_Co-EvolvingLLMs%20and%20Embedding%20Models%20via%20Density-Guided%20Preference%20Optimization%20for%20Text%20Clustering/tables/bcb2214572e9b165201c04ed17926c91f77700ca421cf86a1a03f46f964b6e7f.jpg)

![d6a8df286785ac5e334f4f24bac81121e946296c4923c9938f0a71a787860f1b.jpg](../emnlp_results/241_Co-EvolvingLLMs%20and%20Embedding%20Models%20via%20Density-Guided%20Preference%20Optimization%20for%20Text%20Clustering/tables/d6a8df286785ac5e334f4f24bac81121e946296c4923c9938f0a71a787860f1b.jpg)

![ea00f9259d63111374de4297924278a8f6865cd882789d5d7c141aca7552aca5.jpg](../emnlp_results/241_Co-EvolvingLLMs%20and%20Embedding%20Models%20via%20Density-Guided%20Preference%20Optimization%20for%20Text%20Clustering/tables/ea00f9259d63111374de4297924278a8f6865cd882789d5d7c141aca7552aca5.jpg)

![f2f03b57539d3aae2707e297fd47edf20f6a11f9a8d6304d13f6fa2d27ef2ac9.jpg](../emnlp_results/241_Co-EvolvingLLMs%20and%20Embedding%20Models%20via%20Density-Guided%20Preference%20Optimization%20for%20Text%20Clustering/tables/f2f03b57539d3aae2707e297fd47edf20f6a11f9a8d6304d13f6fa2d27ef2ac9.jpg)

## P-MMEval: A Parallel Multilingual Multitask Benchmark for Consistent Evaluation ofLLMs


### Images

![13b7d0a8b7ee9b705b51f9cc26a782ac85218097b877f6e852845b203bea417f.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/images/13b7d0a8b7ee9b705b51f9cc26a782ac85218097b877f6e852845b203bea417f.jpg)

![1a26e15b75bb800c3de29edca662f42b324e1f1d9ad0d48b6a671d5d00c770d8.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/images/1a26e15b75bb800c3de29edca662f42b324e1f1d9ad0d48b6a671d5d00c770d8.jpg)

![1d464c9083f693fef702d170fe32d045ab501c51ebad69fb73e3bd080ae80922.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/images/1d464c9083f693fef702d170fe32d045ab501c51ebad69fb73e3bd080ae80922.jpg)

![3b543dc6e58a375eeb443d3f704f428561f0ee2cc51f6d561e1fd7f4f8fec712.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/images/3b543dc6e58a375eeb443d3f704f428561f0ee2cc51f6d561e1fd7f4f8fec712.jpg)

![3f0847f54a06ae955d97abd0261c1db9e16e2239fa25acbf048ad8953155dcc0.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/images/3f0847f54a06ae955d97abd0261c1db9e16e2239fa25acbf048ad8953155dcc0.jpg)

![649209290dc269c36cd9e75a116096ae9c992dd46a22114fd34d1e674668fb0a.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/images/649209290dc269c36cd9e75a116096ae9c992dd46a22114fd34d1e674668fb0a.jpg)

![7de8a192763ca4ab49a68e21c7646a6ecb8e449be6c71eae48e73d93ac7bce6e.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/images/7de8a192763ca4ab49a68e21c7646a6ecb8e449be6c71eae48e73d93ac7bce6e.jpg)

![8bb77318c5330f413ac550905c39c199ac2bebe3b5b7f54bd6c33646501cadc5.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/images/8bb77318c5330f413ac550905c39c199ac2bebe3b5b7f54bd6c33646501cadc5.jpg)

![deb532c50cc1421b906a51b9081ac60a1cfc7c3c5d6eae3d46cf893740b5c92b.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/images/deb532c50cc1421b906a51b9081ac60a1cfc7c3c5d6eae3d46cf893740b5c92b.jpg)

### Tables

![009c64002de565786a8661711cbd5303617eae360dc72e246c375d19f31657c2.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/009c64002de565786a8661711cbd5303617eae360dc72e246c375d19f31657c2.jpg)

![060fb2ef313596680d743135503bbc39af674f84c20bdb0f54c9460cd82054af.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/060fb2ef313596680d743135503bbc39af674f84c20bdb0f54c9460cd82054af.jpg)

![0df549c7551eef8f3d2df52878f5016dcca0814fa0f92e9fba92e04dfcbd3ea4.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/0df549c7551eef8f3d2df52878f5016dcca0814fa0f92e9fba92e04dfcbd3ea4.jpg)

![0e9c4ce4a64f1d8976c68485bca50310d9265fa8d7cee9971c2691673f685d81.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/0e9c4ce4a64f1d8976c68485bca50310d9265fa8d7cee9971c2691673f685d81.jpg)

![27656df3b61413f182dd955b50f448a3ffb6984cf3b689a339e6dbd201ada613.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/27656df3b61413f182dd955b50f448a3ffb6984cf3b689a339e6dbd201ada613.jpg)

![2b80bf73d77943df4ae5d19ffa516cf97fa03f271e23767d532ecdb818afd4a1.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/2b80bf73d77943df4ae5d19ffa516cf97fa03f271e23767d532ecdb818afd4a1.jpg)

![447b1871ac01ba0dc076ba5b1e2975a88b981449ca54d6d33167f9964c95290d.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/447b1871ac01ba0dc076ba5b1e2975a88b981449ca54d6d33167f9964c95290d.jpg)

![79a70e1e5158b5d3ac4c1fcca0a21d03f2b2425e7d8e9a5831cf14aa9d329ae0.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/79a70e1e5158b5d3ac4c1fcca0a21d03f2b2425e7d8e9a5831cf14aa9d329ae0.jpg)

![a08b4a47e7988a6fcc663ec33cbce70d76146ae43bcaa73c5fb10417f263e251.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/a08b4a47e7988a6fcc663ec33cbce70d76146ae43bcaa73c5fb10417f263e251.jpg)

![bf7cd154be76d051bfe00492033e4123eb98536e363f7677eaa48655aa3e32fe.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/bf7cd154be76d051bfe00492033e4123eb98536e363f7677eaa48655aa3e32fe.jpg)

![c2b1c9b0e6857bff516b8c70780c9490daef361599abbda0eb607cbbd437d2a8.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/c2b1c9b0e6857bff516b8c70780c9490daef361599abbda0eb607cbbd437d2a8.jpg)

![c2f68adf2f8a4cadffd7a77274d3a338eb0545a4fd1a6b625e9090198d675ffc.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/c2f68adf2f8a4cadffd7a77274d3a338eb0545a4fd1a6b625e9090198d675ffc.jpg)

![cb416816c89f0b804fe08f7550e43e878cd652d826ed19c2c572a0dcf033e666.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/cb416816c89f0b804fe08f7550e43e878cd652d826ed19c2c572a0dcf033e666.jpg)

![d4b0a5517d8f3a3cf174d268719b5a8fd5e6fe88f1261ea6171ffd085b5ec20e.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/d4b0a5517d8f3a3cf174d268719b5a8fd5e6fe88f1261ea6171ffd085b5ec20e.jpg)

![d776c8a22bd1b3a45d5fc162f18c48fed147f59e2b88894eeca46ef821b59daa.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/d776c8a22bd1b3a45d5fc162f18c48fed147f59e2b88894eeca46ef821b59daa.jpg)

![eea9c9e7ef5640f51c7d243f43693e81f22cf4227ca40a3373bcb1dc944a11d2.jpg](../emnlp_results/242_P-MMEval_%20A%20Parallel%20Multilingual%20Multitask%20Benchmark%20for%20Consistent%20Evaluation%20ofLLMs/tables/eea9c9e7ef5640f51c7d243f43693e81f22cf4227ca40a3373bcb1dc944a11d2.jpg)

## SingleLLM, Multiple Roles: A Unified Retrieval-Augmented Generation Framework Using Role-Specific Token Optimization


### Images

![067d31c115e8f78f069ccfdd7894333b846f4e82c4d5a9b29d90bcee3de4a60b.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/images/067d31c115e8f78f069ccfdd7894333b846f4e82c4d5a9b29d90bcee3de4a60b.jpg)

![0a143f720754b23a8cd3ec2ad6218245dba7e1a0e93dc5c3ffde3976e67dcf7d.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/images/0a143f720754b23a8cd3ec2ad6218245dba7e1a0e93dc5c3ffde3976e67dcf7d.jpg)

![2102d2ed3f48cace3651269944eb9073e04985fe484d4acf6c1b1071221766a6.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/images/2102d2ed3f48cace3651269944eb9073e04985fe484d4acf6c1b1071221766a6.jpg)

![2759bc8d30dad341a874652a1452ac698130971ffa64dbda88deaa0b13b06541.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/images/2759bc8d30dad341a874652a1452ac698130971ffa64dbda88deaa0b13b06541.jpg)

![2994ce539529ad75b30aec16555d70e99b7472aa6d3e6d25bf46cc57db38693f.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/images/2994ce539529ad75b30aec16555d70e99b7472aa6d3e6d25bf46cc57db38693f.jpg)

![50b33df0b3f393038f2fb010cbc2b183426ea5f7defe54872edaf623c13e35f3.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/images/50b33df0b3f393038f2fb010cbc2b183426ea5f7defe54872edaf623c13e35f3.jpg)

![85d32437536cb81a292bc590a2e8a349a1c6ad0b959c910234f01a9a2a684db6.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/images/85d32437536cb81a292bc590a2e8a349a1c6ad0b959c910234f01a9a2a684db6.jpg)

![89ce570d1bf044f525fcd63da4b76fbbb2c72a1527f518cc72cbc278acff1d4d.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/images/89ce570d1bf044f525fcd63da4b76fbbb2c72a1527f518cc72cbc278acff1d4d.jpg)

![8a440d96a3a29440bbbda67213c788fd3c14375316471056f00a212f4d3616d2.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/images/8a440d96a3a29440bbbda67213c788fd3c14375316471056f00a212f4d3616d2.jpg)

![9253ae277b624ed2805e7521ed0e53d0c6f5d670cc3b26d95149a0781f4a06d9.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/images/9253ae277b624ed2805e7521ed0e53d0c6f5d670cc3b26d95149a0781f4a06d9.jpg)

![a6af2d173cb247e3044c087bf76ae77334dfe0927e437f5a2cd92576e71c5bc6.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/images/a6af2d173cb247e3044c087bf76ae77334dfe0927e437f5a2cd92576e71c5bc6.jpg)

### Tables

![0c3860f6f476b5c3c5ee2d5b2c99d021f2b968c8f2b7474365d42b31758de062.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/tables/0c3860f6f476b5c3c5ee2d5b2c99d021f2b968c8f2b7474365d42b31758de062.jpg)

![49b3019b48ad0c4c5db09ec563a495611dac55f8b871e9198ecf0747f9135d93.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/tables/49b3019b48ad0c4c5db09ec563a495611dac55f8b871e9198ecf0747f9135d93.jpg)

![6149f525377b717052374493a9f8b079ce6732ddf810610154eb00e205ed14f6.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/tables/6149f525377b717052374493a9f8b079ce6732ddf810610154eb00e205ed14f6.jpg)

![6acb452c60692d246754b6722849bd3a0c9324c5a90bb80a3356be06267ace64.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/tables/6acb452c60692d246754b6722849bd3a0c9324c5a90bb80a3356be06267ace64.jpg)

![8b14c09f629b3f293500e57629179cea7c8f102f3a8df5964f5f91d5517675f5.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/tables/8b14c09f629b3f293500e57629179cea7c8f102f3a8df5964f5f91d5517675f5.jpg)

![9c2ed31132a3d765008e7fb456f7fdbf41b0d44c905d8890bb423c0bc9173e48.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/tables/9c2ed31132a3d765008e7fb456f7fdbf41b0d44c905d8890bb423c0bc9173e48.jpg)

![fec717c5c3f933894839645e238359708a54aa1e4691d37b37ac06ba1e8c8b34.jpg](../emnlp_results/243_SingleLLM%2C%20Multiple%20Roles_%20A%20Unified%20Retrieval-Augmented%20Generation%20Framework%20Using%20Role-Specific%20To/tables/fec717c5c3f933894839645e238359708a54aa1e4691d37b37ac06ba1e8c8b34.jpg)

## TrInk: Ink Generation with Transformer Network


### Images

![217aa920aa591232a1d7b0712796a775f3d3f6f35e062e8536623fb17dfa6e78.jpg](../emnlp_results/244_TrInk_%20Ink%20Generation%20with%20Transformer%20Network/images/217aa920aa591232a1d7b0712796a775f3d3f6f35e062e8536623fb17dfa6e78.jpg)

![817fefda44445f19480a3fefd043bffd9612189ed93b363dbee70cb04b174249.jpg](../emnlp_results/244_TrInk_%20Ink%20Generation%20with%20Transformer%20Network/images/817fefda44445f19480a3fefd043bffd9612189ed93b363dbee70cb04b174249.jpg)

![93c2124b174ff85082e52f5a11e2d7568bfd40019f7b45b84a8ccf3ff7db94d2.jpg](../emnlp_results/244_TrInk_%20Ink%20Generation%20with%20Transformer%20Network/images/93c2124b174ff85082e52f5a11e2d7568bfd40019f7b45b84a8ccf3ff7db94d2.jpg)

![dde699698de70966ac4c9d0f0f3b88121a8ce0afc8a8728852ab04f3c230a69b.jpg](../emnlp_results/244_TrInk_%20Ink%20Generation%20with%20Transformer%20Network/images/dde699698de70966ac4c9d0f0f3b88121a8ce0afc8a8728852ab04f3c230a69b.jpg)

![e2f5f16496a1f4bab632c958c85d796470507221d097c66135c45523d20adc95.jpg](../emnlp_results/244_TrInk_%20Ink%20Generation%20with%20Transformer%20Network/images/e2f5f16496a1f4bab632c958c85d796470507221d097c66135c45523d20adc95.jpg)

![e6b7191cf567de66a33059f2e64884bb0622ebe544a7a0bca971f2f95b54171d.jpg](../emnlp_results/244_TrInk_%20Ink%20Generation%20with%20Transformer%20Network/images/e6b7191cf567de66a33059f2e64884bb0622ebe544a7a0bca971f2f95b54171d.jpg)

### Tables

![36115c7234970873b8e1a810b9b4bacde7ed6b1c62fd4483c98e2c9adbe331e2.jpg](../emnlp_results/244_TrInk_%20Ink%20Generation%20with%20Transformer%20Network/tables/36115c7234970873b8e1a810b9b4bacde7ed6b1c62fd4483c98e2c9adbe331e2.jpg)

![4676d659d65546ac91d12282e387ac88ab210f5ff37b7a6b8c4bde57ba86af88.jpg](../emnlp_results/244_TrInk_%20Ink%20Generation%20with%20Transformer%20Network/tables/4676d659d65546ac91d12282e387ac88ab210f5ff37b7a6b8c4bde57ba86af88.jpg)

![5befc13163b265ae96d1c3c80ba2003a6f420d7f0793fc4fc69a19279de63395.jpg](../emnlp_results/244_TrInk_%20Ink%20Generation%20with%20Transformer%20Network/tables/5befc13163b265ae96d1c3c80ba2003a6f420d7f0793fc4fc69a19279de63395.jpg)

![b10c31b1492414186d8cb73c50be63d2a94fc8bdc80e52dbf594466b83d668d5.jpg](../emnlp_results/244_TrInk_%20Ink%20Generation%20with%20Transformer%20Network/tables/b10c31b1492414186d8cb73c50be63d2a94fc8bdc80e52dbf594466b83d668d5.jpg)

## CalligraphicOCRforChinese Calligraphy Recognition


### Images

![1393b1adcdf0e9c084f4a0587510da437abdba22be7aa725e69d1d612e39aed0.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/images/1393b1adcdf0e9c084f4a0587510da437abdba22be7aa725e69d1d612e39aed0.jpg)

![3495366736dd971f74d1aa3c57f186c60fa8bf1349a3761afcedd759570dd36d.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/images/3495366736dd971f74d1aa3c57f186c60fa8bf1349a3761afcedd759570dd36d.jpg)

![4b514f10c8b0fbec95a1f46bac1f2e70f5b5e8becdb956fc62be7ac92b047815.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/images/4b514f10c8b0fbec95a1f46bac1f2e70f5b5e8becdb956fc62be7ac92b047815.jpg)

![6ce39524ff00772209af4180340ad6e38733620ede3fd6e1ef1c7fe9bad4acc6.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/images/6ce39524ff00772209af4180340ad6e38733620ede3fd6e1ef1c7fe9bad4acc6.jpg)

![7ebbc6480d5d67acb682c0f3869b1b45d5ca4bc04a4ee82ff9a736c4f3ff170e.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/images/7ebbc6480d5d67acb682c0f3869b1b45d5ca4bc04a4ee82ff9a736c4f3ff170e.jpg)

![9d3bd024586a10db4bb79afe032fa7d7890576243c72a0527113f1e8141b2e09.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/images/9d3bd024586a10db4bb79afe032fa7d7890576243c72a0527113f1e8141b2e09.jpg)

![f531027c90b1cf85fc851e142623b986534871804ae2b6ad52ea1d54265a0bde.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/images/f531027c90b1cf85fc851e142623b986534871804ae2b6ad52ea1d54265a0bde.jpg)

### Tables

![496c398a058c71bd84de0acfe0bc9ab38b5e889d0bd09f869c882f075fb71ba5.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/tables/496c398a058c71bd84de0acfe0bc9ab38b5e889d0bd09f869c882f075fb71ba5.jpg)

![730e1111812d188b53324a70f9ac7cb1116698b4bbbac4fd3c73b8541caee057.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/tables/730e1111812d188b53324a70f9ac7cb1116698b4bbbac4fd3c73b8541caee057.jpg)

![85f5651888d010327041b24f5751d925ab135a801f0010e5eef1566e56257ae2.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/tables/85f5651888d010327041b24f5751d925ab135a801f0010e5eef1566e56257ae2.jpg)

![967050fd070a1e12451cf9ad6e763b405818a17e66c195c1db7953763fde5c45.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/tables/967050fd070a1e12451cf9ad6e763b405818a17e66c195c1db7953763fde5c45.jpg)

![ac1d5f4a1ddf7bfc0e59cb2a468a71dbedb5ced0b271db563c0a8c7ca8680370.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/tables/ac1d5f4a1ddf7bfc0e59cb2a468a71dbedb5ced0b271db563c0a8c7ca8680370.jpg)

![c78115f47004bd95595d6c27b80d8c181ab4bde57f75857329d9c05a66794860.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/tables/c78115f47004bd95595d6c27b80d8c181ab4bde57f75857329d9c05a66794860.jpg)

![d43ebf8759d722bbe32ff2e139223c5bc8323489feea623867e34522bbf6da04.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/tables/d43ebf8759d722bbe32ff2e139223c5bc8323489feea623867e34522bbf6da04.jpg)

![f9b6c166d957bbdc9a24ec743ed76e6e37d759440349f50a109b8fa872abd8f4.jpg](../emnlp_results/245_CalligraphicOCRforChinese%20Calligraphy%20Recognition/tables/f9b6c166d957bbdc9a24ec743ed76e6e37d759440349f50a109b8fa872abd8f4.jpg)

## When Audio and Text Disagree: Revealing Text Bias in Large Audio-Language Models


### Images

![68d7754fe5e1b8ab1012ae6dec0029f59ec226beab4782fb93e449307a5b9460.jpg](../emnlp_results/246_When%20Audio%20and%20Text%20Disagree_%20Revealing%20Text%20Bias%20in%20Large%20Audio-Language%20Models/images/68d7754fe5e1b8ab1012ae6dec0029f59ec226beab4782fb93e449307a5b9460.jpg)

![7c40676a1142e19c61cc6b4ad3429ddf62772218a175a3cb52c760dc1663dea5.jpg](../emnlp_results/246_When%20Audio%20and%20Text%20Disagree_%20Revealing%20Text%20Bias%20in%20Large%20Audio-Language%20Models/images/7c40676a1142e19c61cc6b4ad3429ddf62772218a175a3cb52c760dc1663dea5.jpg)

![8113c9e03eb1b809d60e0e8a5ae8d8e9a79d53fe9f604de116f95954d37686f0.jpg](../emnlp_results/246_When%20Audio%20and%20Text%20Disagree_%20Revealing%20Text%20Bias%20in%20Large%20Audio-Language%20Models/images/8113c9e03eb1b809d60e0e8a5ae8d8e9a79d53fe9f604de116f95954d37686f0.jpg)

![a7d7f8010a57096191f6e0bba49d11ef2e441e2db4feff59a01022aeb470f20a.jpg](../emnlp_results/246_When%20Audio%20and%20Text%20Disagree_%20Revealing%20Text%20Bias%20in%20Large%20Audio-Language%20Models/images/a7d7f8010a57096191f6e0bba49d11ef2e441e2db4feff59a01022aeb470f20a.jpg)

![e1cd7d533c025b811a692ac3f8f49f19178bd9080381c5f731d7dd1b72fe54c8.jpg](../emnlp_results/246_When%20Audio%20and%20Text%20Disagree_%20Revealing%20Text%20Bias%20in%20Large%20Audio-Language%20Models/images/e1cd7d533c025b811a692ac3f8f49f19178bd9080381c5f731d7dd1b72fe54c8.jpg)

### Tables

![b139e3c9f6f0509ce360e0c366cbefeb3a8d332c50399eeeaf0cb8b1f7618a72.jpg](../emnlp_results/246_When%20Audio%20and%20Text%20Disagree_%20Revealing%20Text%20Bias%20in%20Large%20Audio-Language%20Models/tables/b139e3c9f6f0509ce360e0c366cbefeb3a8d332c50399eeeaf0cb8b1f7618a72.jpg)

![dd50371ca03c7ba9c90500d2fecec622166d5aa51d9ec30dfd57c61cb7a8ba81.jpg](../emnlp_results/246_When%20Audio%20and%20Text%20Disagree_%20Revealing%20Text%20Bias%20in%20Large%20Audio-Language%20Models/tables/dd50371ca03c7ba9c90500d2fecec622166d5aa51d9ec30dfd57c61cb7a8ba81.jpg)

![f54f2f93f7b20c04d4ace3a6db33efcadd41073c56a7a4bf9ceb21b7c9d5a01a.jpg](../emnlp_results/246_When%20Audio%20and%20Text%20Disagree_%20Revealing%20Text%20Bias%20in%20Large%20Audio-Language%20Models/tables/f54f2f93f7b20c04d4ace3a6db33efcadd41073c56a7a4bf9ceb21b7c9d5a01a.jpg)

![f869fe06c0e4961572a3741341668245b6eca895ae5c5d1441adcebf7740d505.jpg](../emnlp_results/246_When%20Audio%20and%20Text%20Disagree_%20Revealing%20Text%20Bias%20in%20Large%20Audio-Language%20Models/tables/f869fe06c0e4961572a3741341668245b6eca895ae5c5d1441adcebf7740d505.jpg)

## RESF: Regularized-Entropy-Sensitive Fingerprinting for Black-Box Tamper Detection of Large Language Models


### Images

![414201ade3273fee0f177ab79a97019c4a295edac6801e00dfa96e39a0deb47f.jpg](../emnlp_results/247_RESF_%20Regularized-Entropy-Sensitive%20Fingerprinting%20for%20Black-Box%20Tamper%20Detection%20of%20Large%20Language%20/images/414201ade3273fee0f177ab79a97019c4a295edac6801e00dfa96e39a0deb47f.jpg)

![60dd9a452df1eb76177fad520cbf41c843e61329100db35abced88a6a1f428c1.jpg](../emnlp_results/247_RESF_%20Regularized-Entropy-Sensitive%20Fingerprinting%20for%20Black-Box%20Tamper%20Detection%20of%20Large%20Language%20/images/60dd9a452df1eb76177fad520cbf41c843e61329100db35abced88a6a1f428c1.jpg)

![9f00920c94d2a49b20b7ccb3e86adb580877e9fe866a6c82e90a3247750f360d.jpg](../emnlp_results/247_RESF_%20Regularized-Entropy-Sensitive%20Fingerprinting%20for%20Black-Box%20Tamper%20Detection%20of%20Large%20Language%20/images/9f00920c94d2a49b20b7ccb3e86adb580877e9fe866a6c82e90a3247750f360d.jpg)

### Tables

![29f4245896b0ba1e20178d8e4114f9dccc43bfa6e953f7803151f005925b5095.jpg](../emnlp_results/247_RESF_%20Regularized-Entropy-Sensitive%20Fingerprinting%20for%20Black-Box%20Tamper%20Detection%20of%20Large%20Language%20/tables/29f4245896b0ba1e20178d8e4114f9dccc43bfa6e953f7803151f005925b5095.jpg)

![52da359485c63965ef71789cdd391b367bd172f3cb9f9a495057f5d6da7706be.jpg](../emnlp_results/247_RESF_%20Regularized-Entropy-Sensitive%20Fingerprinting%20for%20Black-Box%20Tamper%20Detection%20of%20Large%20Language%20/tables/52da359485c63965ef71789cdd391b367bd172f3cb9f9a495057f5d6da7706be.jpg)

![c20e9ea3c2f51af18fcf1069bb936a3866e630faf3e4c64323b4faed38cc4d61.jpg](../emnlp_results/247_RESF_%20Regularized-Entropy-Sensitive%20Fingerprinting%20for%20Black-Box%20Tamper%20Detection%20of%20Large%20Language%20/tables/c20e9ea3c2f51af18fcf1069bb936a3866e630faf3e4c64323b4faed38cc4d61.jpg)

![d4b455b28e94c67bedba0abda4865cc9844968d1ecfa035e25852799c92e9e7f.jpg](../emnlp_results/247_RESF_%20Regularized-Entropy-Sensitive%20Fingerprinting%20for%20Black-Box%20Tamper%20Detection%20of%20Large%20Language%20/tables/d4b455b28e94c67bedba0abda4865cc9844968d1ecfa035e25852799c92e9e7f.jpg)

![d8f94cb648eda90110e594fb445ff0c2df8b961c3ae42169cf50a5318f867b7e.jpg](../emnlp_results/247_RESF_%20Regularized-Entropy-Sensitive%20Fingerprinting%20for%20Black-Box%20Tamper%20Detection%20of%20Large%20Language%20/tables/d8f94cb648eda90110e594fb445ff0c2df8b961c3ae42169cf50a5318f867b7e.jpg)

![e06bd1bd087ba760d3e6fb9da526fb1d026629cce695692c377232eee0e54dd1.jpg](../emnlp_results/247_RESF_%20Regularized-Entropy-Sensitive%20Fingerprinting%20for%20Black-Box%20Tamper%20Detection%20of%20Large%20Language%20/tables/e06bd1bd087ba760d3e6fb9da526fb1d026629cce695692c377232eee0e54dd1.jpg)

![fa658a473f7aa793feee90a73d85bd60bfcd151d9f570564a59af90526c97b28.jpg](../emnlp_results/247_RESF_%20Regularized-Entropy-Sensitive%20Fingerprinting%20for%20Black-Box%20Tamper%20Detection%20of%20Large%20Language%20/tables/fa658a473f7aa793feee90a73d85bd60bfcd151d9f570564a59af90526c97b28.jpg)

## Model-based Large Language Model Customization as Service


### Images

![171202ac61912a0f33c7c29475cf37525e95d988c3ba6a3d1f64179d946a6639.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/images/171202ac61912a0f33c7c29475cf37525e95d988c3ba6a3d1f64179d946a6639.jpg)

![20cdf063d41fe2155a53fbe706042d99b6332607d0db64b82674498ac397f092.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/images/20cdf063d41fe2155a53fbe706042d99b6332607d0db64b82674498ac397f092.jpg)

![32aa0fbfc3b03fe5ff2a84f64eeb77d21f1556179a7c4d4209fad028f23f9f26.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/images/32aa0fbfc3b03fe5ff2a84f64eeb77d21f1556179a7c4d4209fad028f23f9f26.jpg)

![454a233b0519455cd8a972a6e28e681f6ad63b1aa1d82fbdaf608e38e349f531.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/images/454a233b0519455cd8a972a6e28e681f6ad63b1aa1d82fbdaf608e38e349f531.jpg)

![49326c82db7cf296ba7ab3da073cecc4d0ffcd218e640fc466d44ed881e15b70.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/images/49326c82db7cf296ba7ab3da073cecc4d0ffcd218e640fc466d44ed881e15b70.jpg)

![545fc5b285109b6c523c5e356e2da931cf7a7f207b712f41285c194945f2d43a.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/images/545fc5b285109b6c523c5e356e2da931cf7a7f207b712f41285c194945f2d43a.jpg)

![d4b060cc227bc630c78f60d9e53b351d1721bf5b12e99e6c153d8d295efc57e1.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/images/d4b060cc227bc630c78f60d9e53b351d1721bf5b12e99e6c153d8d295efc57e1.jpg)

![e402c7e68e9c012c135c01eb381181bd101e2d32bfba1801dac8d91f64512a04.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/images/e402c7e68e9c012c135c01eb381181bd101e2d32bfba1801dac8d91f64512a04.jpg)

### Tables

![1a2396a5f10ab4c20a80a5a69283af15c80059599af32293974426775ceac198.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/tables/1a2396a5f10ab4c20a80a5a69283af15c80059599af32293974426775ceac198.jpg)

![2c460e2c66bc429eca972586c116bcc23b400768f6a1c3d60f64bbb12a915403.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/tables/2c460e2c66bc429eca972586c116bcc23b400768f6a1c3d60f64bbb12a915403.jpg)

![386b23d4b031882bb13825deec6f095250adac4a1be3e8febd5781bebd8715b9.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/tables/386b23d4b031882bb13825deec6f095250adac4a1be3e8febd5781bebd8715b9.jpg)

![83b082d3697d8ea362dfbe3f9476e179c38b3e9fbefcab559581b1a2ee39535c.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/tables/83b082d3697d8ea362dfbe3f9476e179c38b3e9fbefcab559581b1a2ee39535c.jpg)

![87abd70757bf3aeae1b8cd668dd1b8c95d75b2207a84f5dc2cfc556d1c23bd69.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/tables/87abd70757bf3aeae1b8cd668dd1b8c95d75b2207a84f5dc2cfc556d1c23bd69.jpg)

![ae52bd04f1b866c20ff4c0bbba7fb2289ded9ab311933b92099de5da65f64409.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/tables/ae52bd04f1b866c20ff4c0bbba7fb2289ded9ab311933b92099de5da65f64409.jpg)

![b1e9bc780bcb1ebc050c95dc52913bca38e3c5d80804241c8c67b5853af1633f.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/tables/b1e9bc780bcb1ebc050c95dc52913bca38e3c5d80804241c8c67b5853af1633f.jpg)

![b7939f227ee9123c629db05e46c645ffc5fb4bfb8a31c22bab91c5dad3c37ff9.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/tables/b7939f227ee9123c629db05e46c645ffc5fb4bfb8a31c22bab91c5dad3c37ff9.jpg)

![cb004795788b445f80e894ce1c794d6aa8741987d97a4101f4202025a538f9e9.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/tables/cb004795788b445f80e894ce1c794d6aa8741987d97a4101f4202025a538f9e9.jpg)

![cd2389c62982c04f6998979e1300a8d3e4b4c700c7b9c3b8f1fd10f6701e9fc8.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/tables/cd2389c62982c04f6998979e1300a8d3e4b4c700c7b9c3b8f1fd10f6701e9fc8.jpg)

![d5504724af5bb4965e7f99a6227b05ff08f2d2ec27369031a176b062b1ef26d2.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/tables/d5504724af5bb4965e7f99a6227b05ff08f2d2ec27369031a176b062b1ef26d2.jpg)

![f45c34d7e7702e87f26e6198767650383e4fb021b3c28b2856c03e01db22bdd5.jpg](../emnlp_results/248_Model-based%20Large%20Language%20Model%20Customization%20as%20Service/tables/f45c34d7e7702e87f26e6198767650383e4fb021b3c28b2856c03e01db22bdd5.jpg)

## Collab-Overcooked: Benchmarking and Evaluating Large Language Models as Collaborative Agents


### Images

![0b0ebdc851f1db3f4b60516750d50502aac8bb4807ce0e1d79794ddb15906672.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/0b0ebdc851f1db3f4b60516750d50502aac8bb4807ce0e1d79794ddb15906672.jpg)

![1417247b6908b0204d117d40b6fa234422390c6325299b927783b639ae02bddf.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/1417247b6908b0204d117d40b6fa234422390c6325299b927783b639ae02bddf.jpg)

![1982a40b113a8a70bfcae9a0e6838128b973601cdc961d1220973d3293b7c11a.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/1982a40b113a8a70bfcae9a0e6838128b973601cdc961d1220973d3293b7c11a.jpg)

![29048ea50f6c0e201b0aba77b1a2be8502af6a1654bd05855ce39ba0c1973c52.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/29048ea50f6c0e201b0aba77b1a2be8502af6a1654bd05855ce39ba0c1973c52.jpg)

![33ef67261827b4ba9687f9f0f5082b82ce0ab07c4ebb6aac2ac1e080cdf1bc6e.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/33ef67261827b4ba9687f9f0f5082b82ce0ab07c4ebb6aac2ac1e080cdf1bc6e.jpg)

![348a082f0b4dc1370bf3a8f162e7c634af779ddfa554cf9c61bbfe8407327ba8.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/348a082f0b4dc1370bf3a8f162e7c634af779ddfa554cf9c61bbfe8407327ba8.jpg)

![3549092affd4aa36b5136737b79bc3d941b5aa819b3aae4cc84f542003ef0900.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/3549092affd4aa36b5136737b79bc3d941b5aa819b3aae4cc84f542003ef0900.jpg)

![469a1be9775443671ae32f5ef2f04dc8fbdcd5281237b550cc21cfab465e6373.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/469a1be9775443671ae32f5ef2f04dc8fbdcd5281237b550cc21cfab465e6373.jpg)

![486bbefa05f572d561360686bd2158a257957b284e567ab332a94c5b6bedf6ff.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/486bbefa05f572d561360686bd2158a257957b284e567ab332a94c5b6bedf6ff.jpg)

![5c8f643dd2819bcc14f082f1947acf509746a8e2b262260c8582e8fb31a8a9a6.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/5c8f643dd2819bcc14f082f1947acf509746a8e2b262260c8582e8fb31a8a9a6.jpg)

![77f882ae478e7eaa52879ec5ac01fe91f36ecfd14adc81ec400ab6389a5c70f8.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/77f882ae478e7eaa52879ec5ac01fe91f36ecfd14adc81ec400ab6389a5c70f8.jpg)

![7e5d2a6829360a5bd0ac16cd028905f15e5e997e33ef153cbce7a3516dede713.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/7e5d2a6829360a5bd0ac16cd028905f15e5e997e33ef153cbce7a3516dede713.jpg)

![7f60eac8e92c0c758610b44e4ceae0b2de9fe2e918285245404d683a26388768.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/7f60eac8e92c0c758610b44e4ceae0b2de9fe2e918285245404d683a26388768.jpg)

![8cbdf8757b76a12ab38e884e66bae01671cb5a6dc8c77e0db9ec242e3ef4ea86.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/8cbdf8757b76a12ab38e884e66bae01671cb5a6dc8c77e0db9ec242e3ef4ea86.jpg)

![8fc144dd6cf4d61c455f5fa160cc325a4ad3e586b9f1927592a35b7786d9c818.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/8fc144dd6cf4d61c455f5fa160cc325a4ad3e586b9f1927592a35b7786d9c818.jpg)

![b19491a1801f0f9d7561ccf56e317f0f7459baa8499a1477bbb5c269576f8ca6.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/b19491a1801f0f9d7561ccf56e317f0f7459baa8499a1477bbb5c269576f8ca6.jpg)

![d1316e7f4e025eec32ac4cbf76f84dbedbbb1ba512a48c38afe4f4868cf91e5a.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/d1316e7f4e025eec32ac4cbf76f84dbedbbb1ba512a48c38afe4f4868cf91e5a.jpg)

![d80eba85f55b987e7f9a84992a8d9c2257e5c9e3a373468ebd7035e907638bfd.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/d80eba85f55b987e7f9a84992a8d9c2257e5c9e3a373468ebd7035e907638bfd.jpg)

![d9a0ff4926df30fc01a97356255dc6881e576d1c0b47341070d1162e0d5234f5.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/d9a0ff4926df30fc01a97356255dc6881e576d1c0b47341070d1162e0d5234f5.jpg)

![e0c6a8e6b524b95d4e824b9c964bdf14f7cd368b63a14f6700ba8c3de5d09761.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/e0c6a8e6b524b95d4e824b9c964bdf14f7cd368b63a14f6700ba8c3de5d09761.jpg)

![e0e3396c2ae1853dcbb500a32467cce850a1ba8cbcca6775199c6e2a6afe5943.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/e0e3396c2ae1853dcbb500a32467cce850a1ba8cbcca6775199c6e2a6afe5943.jpg)

![ebeb2024919d58ee3a01386723a645c801a34d4494b8931d688628ebecd027f9.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/ebeb2024919d58ee3a01386723a645c801a34d4494b8931d688628ebecd027f9.jpg)

![edea41d948ae1c7073ced06c5ccea5004dd4521fde69ff07cd554b9c85dbe30b.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/images/edea41d948ae1c7073ced06c5ccea5004dd4521fde69ff07cd554b9c85dbe30b.jpg)

### Tables

![132538ee851cf2ced404f06886ef37f24a1754fea1f8b8620eb8877980d8d16a.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/tables/132538ee851cf2ced404f06886ef37f24a1754fea1f8b8620eb8877980d8d16a.jpg)

![1772be22801c14349c3fc67fc8ed0663c460552149929bab7d0406571269907e.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/tables/1772be22801c14349c3fc67fc8ed0663c460552149929bab7d0406571269907e.jpg)

![5bb887ac03e86cd2c7676a3a2aed7d89db838523739946e2b08d8717da5975a8.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/tables/5bb887ac03e86cd2c7676a3a2aed7d89db838523739946e2b08d8717da5975a8.jpg)

![62681f331d6a2999f090a0d1e2970d948994f342039e3914bab907106a577561.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/tables/62681f331d6a2999f090a0d1e2970d948994f342039e3914bab907106a577561.jpg)

![6e2fb0326c64cc088a2424e246bce9361093ee460f006e585662a4d8572d3be7.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/tables/6e2fb0326c64cc088a2424e246bce9361093ee460f006e585662a4d8572d3be7.jpg)

![8c06c03668bb67f4d70fa497880d32458e2e7e01a782f84f6e5278883d5caf52.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/tables/8c06c03668bb67f4d70fa497880d32458e2e7e01a782f84f6e5278883d5caf52.jpg)

![b6805f2c579f0c37b86bd07a3e2eab65ba82b66a85f95b0131185bc780f3f4d5.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/tables/b6805f2c579f0c37b86bd07a3e2eab65ba82b66a85f95b0131185bc780f3f4d5.jpg)

![beaa242c801c5a76f2c05925435989732fac3e7453c940a9d9b40df5c1467a92.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/tables/beaa242c801c5a76f2c05925435989732fac3e7453c940a9d9b40df5c1467a92.jpg)

![c306bc7023164b0dde2dfaf04275dfdbe40894e7976e40b13de6ef31fa418d3c.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/tables/c306bc7023164b0dde2dfaf04275dfdbe40894e7976e40b13de6ef31fa418d3c.jpg)

![d88fc45edfa3aa9f8f979f1efd98ebcbb53993f3743499250dda870bf4521d16.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/tables/d88fc45edfa3aa9f8f979f1efd98ebcbb53993f3743499250dda870bf4521d16.jpg)

![dc4c3eb5d03feffc03067b8a1fcc6801839f82ba0596453fc3ec52099d0eee25.jpg](../emnlp_results/249_Collab-Overcooked_%20Benchmarking%20and%20Evaluating%20Large%20Language%20Models%20as%20Collaborative%20Agents/tables/dc4c3eb5d03feffc03067b8a1fcc6801839f82ba0596453fc3ec52099d0eee25.jpg)

## Improving Reasoning Capabilities in Small Models through Mixture-of-layers Distillation with Stepwise Attention on Key Information

### Images

![0ea8d6399394763424033d05e8f8466e2f880b747f0de8b75c59f4cad443bbdd.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/images/0ea8d6399394763424033d05e8f8466e2f880b747f0de8b75c59f4cad443bbdd.jpg)

![376c4fe22c9385f1275e436d76d3d0dcbfd7e5fcbbd0647b50f549432e3994d8.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/images/376c4fe22c9385f1275e436d76d3d0dcbfd7e5fcbbd0647b50f549432e3994d8.jpg)

![393a8620308135ab8cbce579a5fd1d58fe315ede723218f882fdf9579b10da1a.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/images/393a8620308135ab8cbce579a5fd1d58fe315ede723218f882fdf9579b10da1a.jpg)

![5736f392ea71dc06fcb5b3e623bb3556989fbed79e16cf25cf5e4d6248468f9d.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/images/5736f392ea71dc06fcb5b3e623bb3556989fbed79e16cf25cf5e4d6248468f9d.jpg)

![8eabb8c6081f2bba103473f8676c773d745e65bf73b439c1b798dbd3ef517cce.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/images/8eabb8c6081f2bba103473f8676c773d745e65bf73b439c1b798dbd3ef517cce.jpg)

![8f812f8f604c24683ce60206445fd8b542bf939189f8b64abd3c7b31636be4b9.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/images/8f812f8f604c24683ce60206445fd8b542bf939189f8b64abd3c7b31636be4b9.jpg)

![900f96293554353f80e9b67fa3f2ddb2b50c0c6c87e7eea2194355b4e36515a9.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/images/900f96293554353f80e9b67fa3f2ddb2b50c0c6c87e7eea2194355b4e36515a9.jpg)

![90b6d1819725e47aa4d21403abc886e75e8c913124e371837b2a554322e89ba2.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/images/90b6d1819725e47aa4d21403abc886e75e8c913124e371837b2a554322e89ba2.jpg)

![a042c80a27f9af9c4b36f30a1883130f1ee9a84afd49a86d99c44a4d9e08e747.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/images/a042c80a27f9af9c4b36f30a1883130f1ee9a84afd49a86d99c44a4d9e08e747.jpg)

![b77c8bcf9a7963a5fc5c53a5da418d53db6f3ca34a216f7d6f737cf9c409a052.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/images/b77c8bcf9a7963a5fc5c53a5da418d53db6f3ca34a216f7d6f737cf9c409a052.jpg)

![b917c111699f590de21cd6991aeca2074df9ecb8f20fae94b86a0d8cab427e8e.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/images/b917c111699f590de21cd6991aeca2074df9ecb8f20fae94b86a0d8cab427e8e.jpg)

### Tables

![47da3918277b4d73b8b11c71e2a25540dc9ed9cc70249f7e880127ba172ccac6.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/tables/47da3918277b4d73b8b11c71e2a25540dc9ed9cc70249f7e880127ba172ccac6.jpg)

![685a48d888f4faf89e384f7aba99d44c235b32d55da94b565eb605db53826f08.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/tables/685a48d888f4faf89e384f7aba99d44c235b32d55da94b565eb605db53826f08.jpg)

![797d836c84eb323941dc2171803f9ae547f2cbd8cd2b6aba30e3235b74d2e8df.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/tables/797d836c84eb323941dc2171803f9ae547f2cbd8cd2b6aba30e3235b74d2e8df.jpg)

![849a87a5b95cc3a0722574554e3180e512a87fb5dc5a00d672671befd7e71fd2.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/tables/849a87a5b95cc3a0722574554e3180e512a87fb5dc5a00d672671befd7e71fd2.jpg)

![b720b208eefb4c9e98ecf7d46907d6d59349f3d31228ac76227940bf56ae4aa1.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/tables/b720b208eefb4c9e98ecf7d46907d6d59349f3d31228ac76227940bf56ae4aa1.jpg)

![bbc948f27308188b7e201864d6dd39a917836d88c9b4d35a853cb5fb36124b21.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/tables/bbc948f27308188b7e201864d6dd39a917836d88c9b4d35a853cb5fb36124b21.jpg)

![c99267b8d9b2d1a1de743e9b31b5836a0e53c67cc977b73f2d7de52271940fc8.jpg](../emnlp_results/250_Improving%20Reasoning%20Capabilities%20in%20Small%20Models%20through%20Mixture-of-layers%20Distillation%20with%20Stepwis/tables/c99267b8d9b2d1a1de743e9b31b5836a0e53c67cc977b73f2d7de52271940fc8.jpg)
