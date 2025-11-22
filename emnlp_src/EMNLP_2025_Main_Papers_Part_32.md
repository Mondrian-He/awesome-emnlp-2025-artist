# EMNLP 2025 Main Conference Papers

**Summary:** 30 papers with extracted content:
- 📊 Total images: 14618
- 📋 Total tables: 17648
- 📄 Total files: 32266

*Note: Equations have been filtered out and are not included.*

---

# EMNLP 2025 Main Papers - Part 32 of 60

## 目录 (Table of Contents)

1. [SAFE-SQL: Self-Augmented In-Context Learning with Fine-grained Example Selection for Text-to-SQL](#SAFE-SQL-Self-Augmented-In-Context-Learning-with-Fine-grained-Example-Selection-for-Text-to-SQL)
2. [ExpandR: Teaching Dense Retrievers Beyond Queries withLLMGuidance](#ExpandR-Teaching-Dense-Retrievers-Beyond-Queries-withLLMGuidance)
3. [Anecdoctoring: Automated Red-Teaming Across Language and Place](#Anecdoctoring-Automated-Red-Teaming-Across-Language-and-Place)
4. [ACING: Actor-Critic for Instruction Learning in Black-BoxLLMs](#ACING-Actor-Critic-for-Instruction-Learning-in-Black-BoxLLMs)
5. [Women, Infamous, and Exotic Beings: A Comparative Study of Honorific Usages inWikipedia andLLMs forBengali andHindi](#Women-Infamous-and-Exotic-Beings-A-Comparative-Study-of-Honorific-Usages-inWikipedia-andLLMs-forBengali-andHindi)
6. [Process-Supervised Reward Models for Verifying Clinical Note Generation: A Scalable Approach Guided by Domain Expertise](#Process-Supervised-Reward-Models-for-Verifying-Clinical-Note-Generation-A-Scalable-Approach-Guided-by-Domain-Expertise)
7. [GCML: Gradient Coherence Guided Meta-Learning for Cross-Domain Emerging Topic Rumor Detection](#GCML-Gradient-Coherence-Guided-Meta-Learning-for-Cross-Domain-Emerging-Topic-Rumor-Detection)
8. [CanLLMs Generate and Solve Linguistic Olympiad Puzzles?](#CanLLMs-Generate-and-Solve-Linguistic-Olympiad-Puzzles)
9. [E2LLM: Encoder Elongated Large Language Models for Long-Context Understanding and Reasoning](#E2LLM-Encoder-Elongated-Large-Language-Models-for-Long-Context-Understanding-and-Reasoning)
10. [DivScore: Zero-Shot Detection ofLLM-Generated Text in Specialized Domains](#DivScore-Zero-Shot-Detection-ofLLM-Generated-Text-in-Specialized-Domains)
11. [Multi-Document Event Extraction Using Large and Small Language Models](#Multi-Document-Event-Extraction-Using-Large-and-Small-Language-Models)
12. [MA-GTS: A Multi-Agent Framework for Solving Complex Graph Problems in Real-World Applications](#MA-GTS-A-Multi-Agent-Framework-for-Solving-Complex-Graph-Problems-in-Real-World-Applications)
13. [Enhancing Speech Large Language Models with Prompt-Aware Mixture of Audio Encoders](#Enhancing-Speech-Large-Language-Models-with-Prompt-Aware-Mixture-of-Audio-Encoders)
14. [CIKT: A Collaborative and Iterative Knowledge Tracing Framework with Large Language Models](#CIKT-A-Collaborative-and-Iterative-Knowledge-Tracing-Framework-with-Large-Language-Models)
15. [Mitigating Hallucinations inLM-BasedTTSModels via Distribution Alignment UsingGFlowNets](#Mitigating-Hallucinations-inLM-BasedTTSModels-via-Distribution-Alignment-UsingGFlowNets)
16. [MolErr2Fix: BenchmarkingLLMTrustworthiness in Chemistry via Modular Error Detection, Localization, Explanation, and Correction](#MolErr2Fix-BenchmarkingLLMTrustworthiness-in-Chemistry-via-Modular-Error-Detection-Localization-Explanation-and-Correction)
17. [Shared Path: Unraveling Memorization in MultilingualLLMs through Language Similarities](#Shared-Path-Unraveling-Memorization-in-MultilingualLLMs-through-Language-Similarities)
18. [Embedding Domain Knowledge for Large Language Models via Reinforcement Learning from Augmented Generation](#Embedding-Domain-Knowledge-for-Large-Language-Models-via-Reinforcement-Learning-from-Augmented-Generation)
19. [LLM-Driven Completeness and Consistency Evaluation for Cultural Heritage Data Augmentation in Cross-Modal Retrieval](#LLM-Driven-Completeness-and-Consistency-Evaluation-for-Cultural-Heritage-Data-Augmentation-in-Cross-Modal-Retrieval)
20. [Artificial Impressions: Evaluating Large Language Model Behavior Through the Lens of Trait Impressions](#Artificial-Impressions-Evaluating-Large-Language-Model-Behavior-Through-the-Lens-of-Trait-Impressions)
21. [Mitigating Hallucinations in Large Vision-Language Models via Entity-Centric Multimodal Preference Optimization](#Mitigating-Hallucinations-in-Large-Vision-Language-Models-via-Entity-Centric-Multimodal-Preference-Optimization)
22. [3DS: Medical Domain Adaptation ofLLMs via Decomposed Difficulty-based Data Selection](#3DS-Medical-Domain-Adaptation-ofLLMs-via-Decomposed-Difficulty-based-Data-Selection)
23. [InfiniBench: A Benchmark for Large Multi-Modal Models in Long-Form Movies andTVShows](#InfiniBench-A-Benchmark-for-Large-Multi-Modal-Models-in-Long-Form-Movies-andTVShows)
24. [Intrinsic Test of Unlearning Using Parametric Knowledge Traces](#Intrinsic-Test-of-Unlearning-Using-Parametric-Knowledge-Traces)
25. [Speculative Streaming: Efficient and Scalable Speculative Decoding with Multi-Stream Attention](#Speculative-Streaming-Efficient-and-Scalable-Speculative-Decoding-with-Multi-Stream-Attention)
26. [Evaluating Cognitive-Behavioral Fixation via Multimodal User Viewing Patterns on Social Media](#Evaluating-Cognitive-Behavioral-Fixation-via-Multimodal-User-Viewing-Patterns-on-Social-Media)
27. [Mind the Gap: A Closer Look at Tokenization for Multiple-Choice Question Answering withLLMs](#Mind-the-Gap-A-Closer-Look-at-Tokenization-for-Multiple-Choice-Question-Answering-withLLMs)
28. [VocalNet: SpeechLLMs with Multi-Token Prediction for Faster and High-Quality Generation](#VocalNet-SpeechLLMs-with-Multi-Token-Prediction-for-Faster-and-High-Quality-Generation)
29. [Path Drift in Large Reasoning Models: How First-Person Commitments Override Safety](#Path-Drift-in-Large-Reasoning-Models-How-First-Person-Commitments-Override-Safety)
30. [CBP-Tuning: Efficient Local Customization for Black-box Large Language Models](#CBP-Tuning-Efficient-Local-Customization-for-Black-box-Large-Language-Models)

---


## SAFE-SQL: Self-Augmented In-Context Learning with Fine-grained Example Selection for Text-to-SQL

### Images

![0e892ba683c10d3bf8423dc12bdfefa9da6a6380b40fa3ebeb9695dafe9c5cc4.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/images/0e892ba683c10d3bf8423dc12bdfefa9da6a6380b40fa3ebeb9695dafe9c5cc4.jpg)

![1300b183909aa3b2aff1abf8c5d2cde9354b4145063da657fa329e53b2663215.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/images/1300b183909aa3b2aff1abf8c5d2cde9354b4145063da657fa329e53b2663215.jpg)

![5a2ee423771913724933782c822de213b206a493f80c12c7fa9522cdffb78abb.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/images/5a2ee423771913724933782c822de213b206a493f80c12c7fa9522cdffb78abb.jpg)

![870f6218ca945cda399b5b094ec5111ff3e20898ebabd25addded27e7e435177.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/images/870f6218ca945cda399b5b094ec5111ff3e20898ebabd25addded27e7e435177.jpg)

![9c38ebad9c85eb811ed6b1f9f835c49425d8ad1e35b7d689e3ac1e3708e0593c.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/images/9c38ebad9c85eb811ed6b1f9f835c49425d8ad1e35b7d689e3ac1e3708e0593c.jpg)

![a1f726e100153bbcf64163b1a303e24c6f387bcc3c0bcedde80c226961e0f5f5.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/images/a1f726e100153bbcf64163b1a303e24c6f387bcc3c0bcedde80c226961e0f5f5.jpg)

![bf0aabb2642543f536bff496866f99f9ea022323b7039c0b253de201fc89a18e.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/images/bf0aabb2642543f536bff496866f99f9ea022323b7039c0b253de201fc89a18e.jpg)

![d053634f8fd5d896c599e1c2fdd7ebc256617609984a80f4283b7c88eb36fb26.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/images/d053634f8fd5d896c599e1c2fdd7ebc256617609984a80f4283b7c88eb36fb26.jpg)

![f5666ce2e82fba0bd21d0a39d99d7c51c832b3265f7b82c076edf0e43356a8e3.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/images/f5666ce2e82fba0bd21d0a39d99d7c51c832b3265f7b82c076edf0e43356a8e3.jpg)

### Tables

![2c0e87223e27b60b4fb3e5bc306976f4080d84475c8f4b2cec97144b963c34b4.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/tables/2c0e87223e27b60b4fb3e5bc306976f4080d84475c8f4b2cec97144b963c34b4.jpg)

![6a5e5480b39eb821d02344f881b8da750ea290680cb10b674027a42dc56b237d.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/tables/6a5e5480b39eb821d02344f881b8da750ea290680cb10b674027a42dc56b237d.jpg)

![93b6a10522b6d492a31d93b4257e196dfec9d7b0897fed85ba48a4bbb2b7bfa0.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/tables/93b6a10522b6d492a31d93b4257e196dfec9d7b0897fed85ba48a4bbb2b7bfa0.jpg)

![975145fdc4b82bbde88e1f9c92f16c52d27e4f47dc3abd4203b4b2095d43851d.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/tables/975145fdc4b82bbde88e1f9c92f16c52d27e4f47dc3abd4203b4b2095d43851d.jpg)

![fa65347b1a594cdc50b782c7862386a07e64c783c854c16b7801e1c144db8990.jpg](../emnlp_results/961_PhonoThink_%20Improving%20Large%20Language%20Models%E2%80%99%20Reasoning%20onChinese%20Phonological%20Ambiguities/tables/fa65347b1a594cdc50b782c7862386a07e64c783c854c16b7801e1c144db8990.jpg)

## SAFE-SQL: Self-Augmented In-Context Learning with Fine-grained Example Selection for Text-to-SQL


### Images

![6996445ef348bb4b9e57f2a872ad3d735f70f1beacbbcdeef8d0a60b62d82c11.jpg](../emnlp_results/962_SAFE-SQL_%20Self-Augmented%20In-Context%20Learning%20with%20Fine-grained%20Example%20Selection%20for%20Text-to-SQL/images/6996445ef348bb4b9e57f2a872ad3d735f70f1beacbbcdeef8d0a60b62d82c11.jpg)

![701a654c223ae66fb68ae3903a5f3aab8f743df61f27a83ef96254c23afe3aed.jpg](../emnlp_results/962_SAFE-SQL_%20Self-Augmented%20In-Context%20Learning%20with%20Fine-grained%20Example%20Selection%20for%20Text-to-SQL/images/701a654c223ae66fb68ae3903a5f3aab8f743df61f27a83ef96254c23afe3aed.jpg)

![8350841f469b7cb6d0e52664de706da44327c681b29bf2bf6ed1f8cd8aff464b.jpg](../emnlp_results/962_SAFE-SQL_%20Self-Augmented%20In-Context%20Learning%20with%20Fine-grained%20Example%20Selection%20for%20Text-to-SQL/images/8350841f469b7cb6d0e52664de706da44327c681b29bf2bf6ed1f8cd8aff464b.jpg)

![c4b6f67e3fef9ea8932531e83bd9d83a8a6ed6c9cf6946eec1b53bc67c71eb03.jpg](../emnlp_results/962_SAFE-SQL_%20Self-Augmented%20In-Context%20Learning%20with%20Fine-grained%20Example%20Selection%20for%20Text-to-SQL/images/c4b6f67e3fef9ea8932531e83bd9d83a8a6ed6c9cf6946eec1b53bc67c71eb03.jpg)

![fba3c7711ecb087eccdb2c642ec43d33f020ad1a52f67408dd5fdb970dca2384.jpg](../emnlp_results/962_SAFE-SQL_%20Self-Augmented%20In-Context%20Learning%20with%20Fine-grained%20Example%20Selection%20for%20Text-to-SQL/images/fba3c7711ecb087eccdb2c642ec43d33f020ad1a52f67408dd5fdb970dca2384.jpg)

### Tables

![1903f0b65cb4bb0a17d182bfc9511462f852a40d1ab80e0cef0966e80de1f8d8.jpg](../emnlp_results/962_SAFE-SQL_%20Self-Augmented%20In-Context%20Learning%20with%20Fine-grained%20Example%20Selection%20for%20Text-to-SQL/tables/1903f0b65cb4bb0a17d182bfc9511462f852a40d1ab80e0cef0966e80de1f8d8.jpg)

![8d5dc942d9d70d05585912eb1f0ef3bfaa2e1a849dc1d9ebd4d8d575d9ec168d.jpg](../emnlp_results/962_SAFE-SQL_%20Self-Augmented%20In-Context%20Learning%20with%20Fine-grained%20Example%20Selection%20for%20Text-to-SQL/tables/8d5dc942d9d70d05585912eb1f0ef3bfaa2e1a849dc1d9ebd4d8d575d9ec168d.jpg)

![8e418b729ec0dd69ed031bfc8861fc086e1beb66661238072717d50db803e0a7.jpg](../emnlp_results/962_SAFE-SQL_%20Self-Augmented%20In-Context%20Learning%20with%20Fine-grained%20Example%20Selection%20for%20Text-to-SQL/tables/8e418b729ec0dd69ed031bfc8861fc086e1beb66661238072717d50db803e0a7.jpg)

![cc400e6c65738a46ddc9b15b03ed0d77552f1d413cf5099f4f9a90f9725670cb.jpg](../emnlp_results/962_SAFE-SQL_%20Self-Augmented%20In-Context%20Learning%20with%20Fine-grained%20Example%20Selection%20for%20Text-to-SQL/tables/cc400e6c65738a46ddc9b15b03ed0d77552f1d413cf5099f4f9a90f9725670cb.jpg)

![f4aba37e726359d2efcf63e24075469f4cfcd6e3d7d7fced892406eda2bb2aa4.jpg](../emnlp_results/962_SAFE-SQL_%20Self-Augmented%20In-Context%20Learning%20with%20Fine-grained%20Example%20Selection%20for%20Text-to-SQL/tables/f4aba37e726359d2efcf63e24075469f4cfcd6e3d7d7fced892406eda2bb2aa4.jpg)

![f852b49307e7a6d36b8c8dda101e865021d71e6faa482bf951473f4224ef2f48.jpg](../emnlp_results/962_SAFE-SQL_%20Self-Augmented%20In-Context%20Learning%20with%20Fine-grained%20Example%20Selection%20for%20Text-to-SQL/tables/f852b49307e7a6d36b8c8dda101e865021d71e6faa482bf951473f4224ef2f48.jpg)

![fbc03f5cb0886d8eb3ba7c22674b81df1374ab1605f2e926f6f2e4fb82cf7b58.jpg](../emnlp_results/962_SAFE-SQL_%20Self-Augmented%20In-Context%20Learning%20with%20Fine-grained%20Example%20Selection%20for%20Text-to-SQL/tables/fbc03f5cb0886d8eb3ba7c22674b81df1374ab1605f2e926f6f2e4fb82cf7b58.jpg)

## ExpandR: Teaching Dense Retrievers Beyond Queries withLLMGuidance


### Images

![43a48690cad7b5d546cc880df42839592b8d960ea04d3f8c1873839cd2387d52.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/images/43a48690cad7b5d546cc880df42839592b8d960ea04d3f8c1873839cd2387d52.jpg)

![5b988cca80c617ba1b8cf3b732819e91e4f297958f8c934851c5c8a8a78c06e5.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/images/5b988cca80c617ba1b8cf3b732819e91e4f297958f8c934851c5c8a8a78c06e5.jpg)

![7e6ee7608bd4c224d753f2e512183ab24600883e61474b28f6cf7dd5debb476f.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/images/7e6ee7608bd4c224d753f2e512183ab24600883e61474b28f6cf7dd5debb476f.jpg)

![e4db988af751d632c2f48bdc852ad4b0229301d079a0e68218a9d2730b76212b.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/images/e4db988af751d632c2f48bdc852ad4b0229301d079a0e68218a9d2730b76212b.jpg)

![ec602a87259d81cf7879d47436864a3c54cfe03aa87fff3a4b0e80165dbf5d47.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/images/ec602a87259d81cf7879d47436864a3c54cfe03aa87fff3a4b0e80165dbf5d47.jpg)

### Tables

![014e1d07449f2b9b869dc8f4e5cad9dd147dac65773504294433b535e7e5e47d.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/tables/014e1d07449f2b9b869dc8f4e5cad9dd147dac65773504294433b535e7e5e47d.jpg)

![11755764e5a9dfa078a7b4deb15902153c640c8845dad2533274b76fa4329b42.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/tables/11755764e5a9dfa078a7b4deb15902153c640c8845dad2533274b76fa4329b42.jpg)

![24450daf238f2148c9558d503f513692fd2c585cd456981a64ba130b05e62235.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/tables/24450daf238f2148c9558d503f513692fd2c585cd456981a64ba130b05e62235.jpg)

![2a76b753dfbbb31f5cb5a42d7be0c5a26124c26af75ad017ad957b92584ae100.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/tables/2a76b753dfbbb31f5cb5a42d7be0c5a26124c26af75ad017ad957b92584ae100.jpg)

![308ddfa6fc4a9c5d9e4bcb80f0a809d95cf93a4463bb730635d9d8ce0dd4c4d6.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/tables/308ddfa6fc4a9c5d9e4bcb80f0a809d95cf93a4463bb730635d9d8ce0dd4c4d6.jpg)

![74bfdd88b269b456984c5cab844db45451c4fa4b3cb9e0f997decf3d1f01f66d.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/tables/74bfdd88b269b456984c5cab844db45451c4fa4b3cb9e0f997decf3d1f01f66d.jpg)

![8158e8005e25c64b12420218b21924d82b6b86feea95afc24860f00b1810e8d3.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/tables/8158e8005e25c64b12420218b21924d82b6b86feea95afc24860f00b1810e8d3.jpg)

![a59b096d9ef346204878037576eb68615da2d02cb727d02eba3033cf2a175552.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/tables/a59b096d9ef346204878037576eb68615da2d02cb727d02eba3033cf2a175552.jpg)

![c769e4ee35960eae745367150c732b559b47fc8d7e2d0d0f6c0b62036b58ec07.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/tables/c769e4ee35960eae745367150c732b559b47fc8d7e2d0d0f6c0b62036b58ec07.jpg)

![c9a03f4bfd72573f11774083b8d0bab83cb911d078952100ef68e22c5264bd9f.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/tables/c9a03f4bfd72573f11774083b8d0bab83cb911d078952100ef68e22c5264bd9f.jpg)

![d5451a73e3f459e915e34a44c6f0ee046647eba8e88067aacea46f8a476687c9.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/tables/d5451a73e3f459e915e34a44c6f0ee046647eba8e88067aacea46f8a476687c9.jpg)

![debb2a78b88ce5b72145052bab22da57f0c7011b6fa60decf7f21465f5c93c6a.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/tables/debb2a78b88ce5b72145052bab22da57f0c7011b6fa60decf7f21465f5c93c6a.jpg)

![f811ace982a17587cde7133aa79cd368f3040b4c9c4cab74829ad22cc07faa31.jpg](../emnlp_results/963_ExpandR_%20Teaching%20Dense%20Retrievers%20Beyond%20Queries%20withLLMGuidance/tables/f811ace982a17587cde7133aa79cd368f3040b4c9c4cab74829ad22cc07faa31.jpg)

## Anecdoctoring: Automated Red-Teaming Across Language and Place


### Images

![0b664c0a41bcb4a969afa9b27d4b638bc7f552531a8cdfa6789139ed2f041797.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/images/0b664c0a41bcb4a969afa9b27d4b638bc7f552531a8cdfa6789139ed2f041797.jpg)

![0d3ed505e4bb5572a5a41de02e91856627154f122a6b6036842349a1ae0b9e75.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/images/0d3ed505e4bb5572a5a41de02e91856627154f122a6b6036842349a1ae0b9e75.jpg)

![228ee01fd9ae21b2fd98024dcfe950b4240f77b6a90c57ce044e8c5e5f25f559.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/images/228ee01fd9ae21b2fd98024dcfe950b4240f77b6a90c57ce044e8c5e5f25f559.jpg)

![2a9392c8870b5d7547a39131d9a23da01abe56f645a448e90be60b841e16eb95.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/images/2a9392c8870b5d7547a39131d9a23da01abe56f645a448e90be60b841e16eb95.jpg)

![391000a207f755e3d6a63dd5c59fb2d562d38e446d2933639faa615d0cca6e3a.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/images/391000a207f755e3d6a63dd5c59fb2d562d38e446d2933639faa615d0cca6e3a.jpg)

![816226ed3e62e9128089785f6e3d7690d2248138cacba36f16523afb9783e5db.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/images/816226ed3e62e9128089785f6e3d7690d2248138cacba36f16523afb9783e5db.jpg)

![88fc0d40833c9739697e77f610204e54b749bcfd63af1d7c1974e2953c5d21e9.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/images/88fc0d40833c9739697e77f610204e54b749bcfd63af1d7c1974e2953c5d21e9.jpg)

![ae09fae46342440efd62c2e74ae471eff9ec47baac41d178bc0b99788ee5c078.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/images/ae09fae46342440efd62c2e74ae471eff9ec47baac41d178bc0b99788ee5c078.jpg)

![bdea6da4be5480c5c0c49c6d0806ad657b6bfd9bbd5b27720afa5b5eb53e0ee1.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/images/bdea6da4be5480c5c0c49c6d0806ad657b6bfd9bbd5b27720afa5b5eb53e0ee1.jpg)

![fe9566d5a58623461561b2fa3ec49c4abc7460bcfacb650efd706f5c814af821.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/images/fe9566d5a58623461561b2fa3ec49c4abc7460bcfacb650efd706f5c814af821.jpg)

![feb1eea63df4856f26f9a478a7bd9ff93b12958449861753ced0f2cae7702150.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/images/feb1eea63df4856f26f9a478a7bd9ff93b12958449861753ced0f2cae7702150.jpg)

### Tables

![259c5197c4da5c5f64a49d3c378ac5c1dcb5a111bb16e8482629438c2c2c8a41.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/tables/259c5197c4da5c5f64a49d3c378ac5c1dcb5a111bb16e8482629438c2c2c8a41.jpg)

![ac050ad3e32b687f5d42b4ca42e3a8cf81bc3a6adb4a123faa60e666bc067c07.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/tables/ac050ad3e32b687f5d42b4ca42e3a8cf81bc3a6adb4a123faa60e666bc067c07.jpg)

![c35bdeb8143341cb0bc01d0e3a80640cf4ece02c0aa2aba4d61cf6a088146506.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/tables/c35bdeb8143341cb0bc01d0e3a80640cf4ece02c0aa2aba4d61cf6a088146506.jpg)

![db66951fd0465da032eedcdc9ceb74e28e42bb7dcb71088b69c1bf3c648820b0.jpg](../emnlp_results/964_Anecdoctoring_%20Automated%20Red-Teaming%20Across%20Language%20and%20Place/tables/db66951fd0465da032eedcdc9ceb74e28e42bb7dcb71088b69c1bf3c648820b0.jpg)

## ACING: Actor-Critic for Instruction Learning in Black-BoxLLMs


### Images

![1995138438b41dbf7352fbee7daaea734c55dc71482de54fee97763986872474.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/images/1995138438b41dbf7352fbee7daaea734c55dc71482de54fee97763986872474.jpg)

![32d12f56d9a864068610ff82074f0b21b27326dc77122914c8ac30c4bba2ce27.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/images/32d12f56d9a864068610ff82074f0b21b27326dc77122914c8ac30c4bba2ce27.jpg)

![9ec910a364ea6581ff2633e0088892492d9fcb498560f2d909410a0d88eceb3a.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/images/9ec910a364ea6581ff2633e0088892492d9fcb498560f2d909410a0d88eceb3a.jpg)

![ebbbf635416a213db5ab9a19ce8010d93200a18624316abce96cf4c28adb3092.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/images/ebbbf635416a213db5ab9a19ce8010d93200a18624316abce96cf4c28adb3092.jpg)

### Tables

![01a407911c0f71af3cf176ff0df66c44ca625dc3dd4d079b557a7ca5924396cc.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/01a407911c0f71af3cf176ff0df66c44ca625dc3dd4d079b557a7ca5924396cc.jpg)

![0787a482a677a9fa2f5cdf279ae508a1a04f1bba4dbc7bcb9421bfc6afd9a296.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/0787a482a677a9fa2f5cdf279ae508a1a04f1bba4dbc7bcb9421bfc6afd9a296.jpg)

![0c7143f709fcb1c908283baf8746fbeebe593a7333ee277653f7d6edc71df940.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/0c7143f709fcb1c908283baf8746fbeebe593a7333ee277653f7d6edc71df940.jpg)

![1ebcd6ae4ab46567033fa214da12e9f8d65894fe66492a5941509b7a6f50f021.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/1ebcd6ae4ab46567033fa214da12e9f8d65894fe66492a5941509b7a6f50f021.jpg)

![446fdb610dec3aa4faec36d5abf4c2c59da717ea550737c918a409963f1d20f5.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/446fdb610dec3aa4faec36d5abf4c2c59da717ea550737c918a409963f1d20f5.jpg)

![47d4de43c7cb2ad36fc87346ab4e1d721461bea1869f9c7fb0e8f1d6c14b1b80.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/47d4de43c7cb2ad36fc87346ab4e1d721461bea1869f9c7fb0e8f1d6c14b1b80.jpg)

![4e5899849d9b822d22eab6db1b0a6fd8261eb930e302a486125f94fa1194480a.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/4e5899849d9b822d22eab6db1b0a6fd8261eb930e302a486125f94fa1194480a.jpg)

![4ebdfc5bc78e969b20df82690a009643d61fec11a35ca718b4823519f3a756e2.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/4ebdfc5bc78e969b20df82690a009643d61fec11a35ca718b4823519f3a756e2.jpg)

![5e8b9402b18ead5009bfb69a79752bb0fe0954563296aac96f65176f65d47b85.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/5e8b9402b18ead5009bfb69a79752bb0fe0954563296aac96f65176f65d47b85.jpg)

![603a56b9c2566701e4c975716a9692833a9c278fb16822f58f143d2cd44f440f.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/603a56b9c2566701e4c975716a9692833a9c278fb16822f58f143d2cd44f440f.jpg)

![6cb5b873fd935b382a23dbf45878c5d5e9bc817169a24e14980031d1e0aff641.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/6cb5b873fd935b382a23dbf45878c5d5e9bc817169a24e14980031d1e0aff641.jpg)

![720bb67bca1cbee53e20f8c3dadce37ce797dcca3d85be21c1a20f0ab4c784c4.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/720bb67bca1cbee53e20f8c3dadce37ce797dcca3d85be21c1a20f0ab4c784c4.jpg)

![73d8914ee1a9f5934b9a269e4b389593557d5e3fb626c7019cd45e8a37ec70ee.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/73d8914ee1a9f5934b9a269e4b389593557d5e3fb626c7019cd45e8a37ec70ee.jpg)

![7e699e6abe219bcd9a1403641d381541544a69581d783db5386c60293394046a.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/7e699e6abe219bcd9a1403641d381541544a69581d783db5386c60293394046a.jpg)

![90db2a2eb671cc934cf7f173840ea58b389453681ebbd24ba473a7b14d1bb2f8.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/90db2a2eb671cc934cf7f173840ea58b389453681ebbd24ba473a7b14d1bb2f8.jpg)

![9202674e8dabb849279b412ade1fd255316c67dd3d0827f3de1616ee255a51cc.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/9202674e8dabb849279b412ade1fd255316c67dd3d0827f3de1616ee255a51cc.jpg)

![9e8adab0b8e402008d755e96bb7f9992ed894d1a97b51aba21d4e3b3626f904f.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/9e8adab0b8e402008d755e96bb7f9992ed894d1a97b51aba21d4e3b3626f904f.jpg)

![a6a7d2b94e90608ba411550ce7ec7b6896c9b4ece42bbe157b3474896563a440.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/a6a7d2b94e90608ba411550ce7ec7b6896c9b4ece42bbe157b3474896563a440.jpg)

![a8d65f859662498bc4c2df3cd652335ba0a3767bfa68765f3fb57e270f759be4.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/a8d65f859662498bc4c2df3cd652335ba0a3767bfa68765f3fb57e270f759be4.jpg)

![b2aff4369dfb38596db81f34fa5b15a2970cde6f1d049d834a514b3f9b13e7f5.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/b2aff4369dfb38596db81f34fa5b15a2970cde6f1d049d834a514b3f9b13e7f5.jpg)

![c0400fdc6c51f012f90040d439906e24bf38bd61278e99bdec7ca5b564e21003.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/c0400fdc6c51f012f90040d439906e24bf38bd61278e99bdec7ca5b564e21003.jpg)

![c72fb0f17ab9d4fa87ce895a200bf3abea6e095e7cff8964ec1f00f4f82362dc.jpg](../emnlp_results/965_ACING_%20Actor-Critic%20for%20Instruction%20Learning%20in%20Black-BoxLLMs/tables/c72fb0f17ab9d4fa87ce895a200bf3abea6e095e7cff8964ec1f00f4f82362dc.jpg)

## Women, Infamous, and Exotic Beings: A Comparative Study of Honorific Usages inWikipedia andLLMs forBengali andHindi


### Images

![03237bd63e15faa0c9d191cf781aac6afa9b70130bde6a02939dd4cf97f477f1.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/images/03237bd63e15faa0c9d191cf781aac6afa9b70130bde6a02939dd4cf97f477f1.jpg)

![0825acca5a37bc5265596ca194a9502cad255a2e1ddfa34efdb46a9793bad154.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/images/0825acca5a37bc5265596ca194a9502cad255a2e1ddfa34efdb46a9793bad154.jpg)

![0c1673c648717ad22b1c9beb341903ddfce401c618c7f98eb03dd4460427fbe6.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/images/0c1673c648717ad22b1c9beb341903ddfce401c618c7f98eb03dd4460427fbe6.jpg)

![0ec0ce70369bba5df834fe283d50eb32099d310bbb317545ec9617bf7e26b79f.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/images/0ec0ce70369bba5df834fe283d50eb32099d310bbb317545ec9617bf7e26b79f.jpg)

![27dc1775261febd5fd9b19483ccfcd35bcdffd3103e1fa92fd30d0284464aead.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/images/27dc1775261febd5fd9b19483ccfcd35bcdffd3103e1fa92fd30d0284464aead.jpg)

![612f4f094e9591c5bd394649ff38dad91519109a56a178d62d81dfaa39914959.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/images/612f4f094e9591c5bd394649ff38dad91519109a56a178d62d81dfaa39914959.jpg)

![747153a32d0d3a89e28f3e46ebafd2a08791815e3eb442249063204ecfc04f0b.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/images/747153a32d0d3a89e28f3e46ebafd2a08791815e3eb442249063204ecfc04f0b.jpg)

![9adcd72cfad8399ac3c48529178dd80111bd4c52f79bd294df0045411aafe053.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/images/9adcd72cfad8399ac3c48529178dd80111bd4c52f79bd294df0045411aafe053.jpg)

![b6a2ad76d584a5e22b13471e7cbc7c48e3670de46b592b200bdbfc882c9319ca.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/images/b6a2ad76d584a5e22b13471e7cbc7c48e3670de46b592b200bdbfc882c9319ca.jpg)

![b77f45141ec544402171f28c27f221d8816d23bf25d2f38cd2c8dfd1c845272e.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/images/b77f45141ec544402171f28c27f221d8816d23bf25d2f38cd2c8dfd1c845272e.jpg)

![e0c5c848c4eb4b63dc94ac13f73c7659e8f00fef11099d38e84896f51f532cd8.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/images/e0c5c848c4eb4b63dc94ac13f73c7659e8f00fef11099d38e84896f51f532cd8.jpg)

![e681f745e2fe21b4ba2181a1b02882dcdcf0b85df84cec99fa62ee19b4b2721d.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/images/e681f745e2fe21b4ba2181a1b02882dcdcf0b85df84cec99fa62ee19b4b2721d.jpg)

### Tables

![07ec63521f366a3ee79398dc17d8d10eb50d5d0c73503ba86fa0bd6d06b78351.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/tables/07ec63521f366a3ee79398dc17d8d10eb50d5d0c73503ba86fa0bd6d06b78351.jpg)

![0a09f1ebce0dcd09656554df9f47cf719393e8362a94c3adbb039526c5d5c783.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/tables/0a09f1ebce0dcd09656554df9f47cf719393e8362a94c3adbb039526c5d5c783.jpg)

![23b786d68515fb71bc672d76b9e2f6c2840d2e425145ab6542bdffdaa93cba3e.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/tables/23b786d68515fb71bc672d76b9e2f6c2840d2e425145ab6542bdffdaa93cba3e.jpg)

![2662a1b203b93a43d24a06d63fee2ccf44443d006ebf6a0e9de8c079d54e3073.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/tables/2662a1b203b93a43d24a06d63fee2ccf44443d006ebf6a0e9de8c079d54e3073.jpg)

![3a090ddbf729eecbcf9c88963b84409ac316aaee92edcd6e1c3330c50a68c4ac.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/tables/3a090ddbf729eecbcf9c88963b84409ac316aaee92edcd6e1c3330c50a68c4ac.jpg)

![635154e7c2afe4a5acb23c158c16276c710c85de856b67b260584fc5a3d656aa.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/tables/635154e7c2afe4a5acb23c158c16276c710c85de856b67b260584fc5a3d656aa.jpg)

![758ae9b423f11d76149fbdc26d2caac28f77de4187416e4285bd263020e4c2a0.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/tables/758ae9b423f11d76149fbdc26d2caac28f77de4187416e4285bd263020e4c2a0.jpg)

![7c0b28e667f89e37a8d37576615f6ef0860d545743b2c9765628f383a4b41d03.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/tables/7c0b28e667f89e37a8d37576615f6ef0860d545743b2c9765628f383a4b41d03.jpg)

![e6d813b4e4f9b9d285cea9444d85d1207263e681a996030d6a2fdc262dbb84d8.jpg](../emnlp_results/966_Women%2C%20Infamous%2C%20and%20Exotic%20Beings_%20A%20Comparative%20Study%20of%20Honorific%20Usages%20inWikipedia%20andLLMs%20forB/tables/e6d813b4e4f9b9d285cea9444d85d1207263e681a996030d6a2fdc262dbb84d8.jpg)

## Process-Supervised Reward Models for Verifying Clinical Note Generation: A Scalable Approach Guided by Domain Expertise


### Images

![13738d1feb34bd3cb64f7ed61b00c9726a46c0df83f00c7f287240b2d86ca956.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/images/13738d1feb34bd3cb64f7ed61b00c9726a46c0df83f00c7f287240b2d86ca956.jpg)

![45284705c628ce9936bd6d3bc1e79643bbb52eec8f388f454fb5484c004f3caa.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/images/45284705c628ce9936bd6d3bc1e79643bbb52eec8f388f454fb5484c004f3caa.jpg)

![686067f6814f7e9c9c5a7475b0233600a36fe02580e6f456ae45e712e6c3ad4d.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/images/686067f6814f7e9c9c5a7475b0233600a36fe02580e6f456ae45e712e6c3ad4d.jpg)

![d218767aacceafb2981f5a5174dfcebb1ad126478b74fbfaebfa19ec31470643.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/images/d218767aacceafb2981f5a5174dfcebb1ad126478b74fbfaebfa19ec31470643.jpg)

![fc3afef134ef89a746a598807dc9d8aaf416eb6f8a716e0b93cd253f8c59853f.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/images/fc3afef134ef89a746a598807dc9d8aaf416eb6f8a716e0b93cd253f8c59853f.jpg)

### Tables

![31904ba8af3b1cf4b24beadff63f6560e2e21836cdba87d77fd77f26231367e8.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/tables/31904ba8af3b1cf4b24beadff63f6560e2e21836cdba87d77fd77f26231367e8.jpg)

![4a33412e25b4a6695b5d8b41a22076acfafeb279b3d30a66780170d41e454ba9.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/tables/4a33412e25b4a6695b5d8b41a22076acfafeb279b3d30a66780170d41e454ba9.jpg)

![677e0ca889f36c2cd0b2f51bc75de81bb2351b889e0e212ee22c4fdc8f1d84d6.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/tables/677e0ca889f36c2cd0b2f51bc75de81bb2351b889e0e212ee22c4fdc8f1d84d6.jpg)

![71b5a042187bad49290ed0200a7bc6e39b2916a8441de2f586218f41791f125b.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/tables/71b5a042187bad49290ed0200a7bc6e39b2916a8441de2f586218f41791f125b.jpg)

![8f8428ce35882be7a904ecc4c768adb2eacee7d8763c7a349fd5c81f14bc98df.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/tables/8f8428ce35882be7a904ecc4c768adb2eacee7d8763c7a349fd5c81f14bc98df.jpg)

![9d242ddd1343884ba52ce0c97e95884a3638210b29c99000aa888c1914238100.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/tables/9d242ddd1343884ba52ce0c97e95884a3638210b29c99000aa888c1914238100.jpg)

![a7aa351e449392dcc9bf73d7567155daecbc267a459f174c1288a4000e0ee81d.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/tables/a7aa351e449392dcc9bf73d7567155daecbc267a459f174c1288a4000e0ee81d.jpg)

![ae38d0dfb455a50cef511be3044c37a94e4342c28e4b447ac184f3d37792d6ae.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/tables/ae38d0dfb455a50cef511be3044c37a94e4342c28e4b447ac184f3d37792d6ae.jpg)

![c06b1aa16aa9f4d99d0df55d2297d528c27096a9c5277fb020cb7256d5114aa9.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/tables/c06b1aa16aa9f4d99d0df55d2297d528c27096a9c5277fb020cb7256d5114aa9.jpg)

![d3e97236994f4fbf398b83a0af38fccae8c14211f80db7221f8b21d6914bc3a0.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/tables/d3e97236994f4fbf398b83a0af38fccae8c14211f80db7221f8b21d6914bc3a0.jpg)

![d40c18298748eb5486394a13e64ae549012804963d687655c8485e56bb88477e.jpg](../emnlp_results/967_Process-Supervised%20Reward%20Models%20for%20Verifying%20Clinical%20Note%20Generation_%20A%20Scalable%20Approach%20Guided%20/tables/d40c18298748eb5486394a13e64ae549012804963d687655c8485e56bb88477e.jpg)

## GCML: Gradient Coherence Guided Meta-Learning for Cross-Domain Emerging Topic Rumor Detection


### Images

![12b887942aff62824ad3d85c608ad76fce97c8979139296b3922f454c134b5cc.jpg](../emnlp_results/968_GCML_%20Gradient%20Coherence%20Guided%20Meta-Learning%20for%20Cross-Domain%20Emerging%20Topic%20Rumor%20Detection/images/12b887942aff62824ad3d85c608ad76fce97c8979139296b3922f454c134b5cc.jpg)

![143144d4e33f29ff1a9887c39efa78ddcf623f1551512d93458a65786dea10ca.jpg](../emnlp_results/968_GCML_%20Gradient%20Coherence%20Guided%20Meta-Learning%20for%20Cross-Domain%20Emerging%20Topic%20Rumor%20Detection/images/143144d4e33f29ff1a9887c39efa78ddcf623f1551512d93458a65786dea10ca.jpg)

![1ef425257bbb7ba4226e57729d992906e0445334d5f5a7fdd0a09ca812f9b623.jpg](../emnlp_results/968_GCML_%20Gradient%20Coherence%20Guided%20Meta-Learning%20for%20Cross-Domain%20Emerging%20Topic%20Rumor%20Detection/images/1ef425257bbb7ba4226e57729d992906e0445334d5f5a7fdd0a09ca812f9b623.jpg)

![2bfcf203d8f891a0117bade3a636aec836b97bdf607219811fe3cf8b1ce01582.jpg](../emnlp_results/968_GCML_%20Gradient%20Coherence%20Guided%20Meta-Learning%20for%20Cross-Domain%20Emerging%20Topic%20Rumor%20Detection/images/2bfcf203d8f891a0117bade3a636aec836b97bdf607219811fe3cf8b1ce01582.jpg)

![92e6bf7d89cc2272b9e5e71d89a7c98f777a52b960863a3a8d215a34ea430f5c.jpg](../emnlp_results/968_GCML_%20Gradient%20Coherence%20Guided%20Meta-Learning%20for%20Cross-Domain%20Emerging%20Topic%20Rumor%20Detection/images/92e6bf7d89cc2272b9e5e71d89a7c98f777a52b960863a3a8d215a34ea430f5c.jpg)

![a1b7c1a9ace189f25af6c5a19c90967a3c84ce35fa6ea4b66064fae8ebaaab45.jpg](../emnlp_results/968_GCML_%20Gradient%20Coherence%20Guided%20Meta-Learning%20for%20Cross-Domain%20Emerging%20Topic%20Rumor%20Detection/images/a1b7c1a9ace189f25af6c5a19c90967a3c84ce35fa6ea4b66064fae8ebaaab45.jpg)

### Tables

![141d62e54db6e810ac4172c6a3c2f7809e043a3e1e32120d6f4ffcdc777435da.jpg](../emnlp_results/968_GCML_%20Gradient%20Coherence%20Guided%20Meta-Learning%20for%20Cross-Domain%20Emerging%20Topic%20Rumor%20Detection/tables/141d62e54db6e810ac4172c6a3c2f7809e043a3e1e32120d6f4ffcdc777435da.jpg)

![25d995c595b80edc2da4575fdf0a735abc107dfa4a7e6079ae1eff1cfa18baa7.jpg](../emnlp_results/968_GCML_%20Gradient%20Coherence%20Guided%20Meta-Learning%20for%20Cross-Domain%20Emerging%20Topic%20Rumor%20Detection/tables/25d995c595b80edc2da4575fdf0a735abc107dfa4a7e6079ae1eff1cfa18baa7.jpg)

![7d7d9e261d93b89c1136d84177bb7d239dd6212d332719daf8f965b028ea997d.jpg](../emnlp_results/968_GCML_%20Gradient%20Coherence%20Guided%20Meta-Learning%20for%20Cross-Domain%20Emerging%20Topic%20Rumor%20Detection/tables/7d7d9e261d93b89c1136d84177bb7d239dd6212d332719daf8f965b028ea997d.jpg)

![b3952918b16796f1185fc7618cafeb02e672677702fae3969b92a68f6874156d.jpg](../emnlp_results/968_GCML_%20Gradient%20Coherence%20Guided%20Meta-Learning%20for%20Cross-Domain%20Emerging%20Topic%20Rumor%20Detection/tables/b3952918b16796f1185fc7618cafeb02e672677702fae3969b92a68f6874156d.jpg)

## CanLLMs Generate and Solve Linguistic Olympiad Puzzles?


### Images

![017bf0f2d1e1f6cdfb18f487323323e08b178f16883b5b66bc1201327dc1931e.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/017bf0f2d1e1f6cdfb18f487323323e08b178f16883b5b66bc1201327dc1931e.jpg)

![1cd5bc56e0d806f0b079d0f73697fcdf7d0002c8af0a786272b88f5e39fd8a8b.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/1cd5bc56e0d806f0b079d0f73697fcdf7d0002c8af0a786272b88f5e39fd8a8b.jpg)

![3a558684e94526fc31516adeaa58bcdd7ed82c49ed43ec196812c6956c6893ef.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/3a558684e94526fc31516adeaa58bcdd7ed82c49ed43ec196812c6956c6893ef.jpg)

![3e609151ea3aacebed0a53fb57109e86f549c77b06879f903e5feaafeb674a3d.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/3e609151ea3aacebed0a53fb57109e86f549c77b06879f903e5feaafeb674a3d.jpg)

![487a7293dba5b46c4f8e1c74283f896afbdfdd654a9bc6d265e3385395e3ae63.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/487a7293dba5b46c4f8e1c74283f896afbdfdd654a9bc6d265e3385395e3ae63.jpg)

![5fa2de5a35a2758e37a625dc94583f0bf39674a427a128b5191879e07e710ca6.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/5fa2de5a35a2758e37a625dc94583f0bf39674a427a128b5191879e07e710ca6.jpg)

![67d185ec9ff99ba196048894bfbfbb00b28b94f848efb1375a554d4ae86056c1.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/67d185ec9ff99ba196048894bfbfbb00b28b94f848efb1375a554d4ae86056c1.jpg)

![6a20728a5190597c983ad4a07eabc3856fc7d994fda2e90cf5d84b152feaa011.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/6a20728a5190597c983ad4a07eabc3856fc7d994fda2e90cf5d84b152feaa011.jpg)

![77315d5db2d11ec895b52b50d70121bd4d16dbd359c2c762bfd8fe8c5c3445dc.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/77315d5db2d11ec895b52b50d70121bd4d16dbd359c2c762bfd8fe8c5c3445dc.jpg)

![80f90696344d2dda3740194902ee61f5ce01e0e88d8207fa6b404b3b66b40a2b.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/80f90696344d2dda3740194902ee61f5ce01e0e88d8207fa6b404b3b66b40a2b.jpg)

![b4dbe850ca3759e3a8aa1bfba093c9492a722178c12aefa943c275ffa26c09a5.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/b4dbe850ca3759e3a8aa1bfba093c9492a722178c12aefa943c275ffa26c09a5.jpg)

![c014017185216aabdf0fc94e9cdb4a077d1cf220c13ef45f13f002c675263e70.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/c014017185216aabdf0fc94e9cdb4a077d1cf220c13ef45f13f002c675263e70.jpg)

![d785b3455577c9ebf2d25bcd94c8be4dda463fdd67bc9e2218f532c01c0067bb.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/d785b3455577c9ebf2d25bcd94c8be4dda463fdd67bc9e2218f532c01c0067bb.jpg)

![dcd3d5da26f495eab58c8cd3bf63710f40d874afa601c7e9a47c06e9c7ddedf0.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/dcd3d5da26f495eab58c8cd3bf63710f40d874afa601c7e9a47c06e9c7ddedf0.jpg)

![e8572d6cf468b974f1f0b9df90fc4e9b6471420978ab30554637e302f566eb45.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/e8572d6cf468b974f1f0b9df90fc4e9b6471420978ab30554637e302f566eb45.jpg)

![f36b5d1104381298c9607846f6231684b7c5aff6890011addb1d7f7e2a1e69e2.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/images/f36b5d1104381298c9607846f6231684b7c5aff6890011addb1d7f7e2a1e69e2.jpg)

### Tables

![195f3084415d03082932a9beb915804cc76bdccbedda317d130ea3dce55f1fc2.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/195f3084415d03082932a9beb915804cc76bdccbedda317d130ea3dce55f1fc2.jpg)

![33246282dd36959c89a99a014593e28fa0c674b2c089f5cc766b4af6b74f6a07.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/33246282dd36959c89a99a014593e28fa0c674b2c089f5cc766b4af6b74f6a07.jpg)

![36854f798623e4cccf932a2fdf1256e96d334a52ee2f3a54e1f17c29b61e3f7a.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/36854f798623e4cccf932a2fdf1256e96d334a52ee2f3a54e1f17c29b61e3f7a.jpg)

![3a163d9ee8b02fa575c58396b15faacd8dfbb7339eefdf472f022a0a3b6a76e3.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/3a163d9ee8b02fa575c58396b15faacd8dfbb7339eefdf472f022a0a3b6a76e3.jpg)

![4353e6be6a1ba8ae3562db27918b9135b10a47c936b9ed5b94a5d4034d8c1e59.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/4353e6be6a1ba8ae3562db27918b9135b10a47c936b9ed5b94a5d4034d8c1e59.jpg)

![489c2c1370906c68f161ff2c4e0b2f74f4a08ac5add591202f40d295f493a68b.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/489c2c1370906c68f161ff2c4e0b2f74f4a08ac5add591202f40d295f493a68b.jpg)

![5b0617d2b7b871f80f4d467bd25de9e69317ed529eac5c3e06391c82c0818a49.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/5b0617d2b7b871f80f4d467bd25de9e69317ed529eac5c3e06391c82c0818a49.jpg)

![5bb9cc6abce19c9956fd79a5e29a8b062609ea15163bfa96dc5aa5dfafcfc3d2.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/5bb9cc6abce19c9956fd79a5e29a8b062609ea15163bfa96dc5aa5dfafcfc3d2.jpg)

![641c6ad0a05a83c36036fb4be2035dbf68078952dcf0756c8b1f8c469ff85d38.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/641c6ad0a05a83c36036fb4be2035dbf68078952dcf0756c8b1f8c469ff85d38.jpg)

![87ee4872c1d27c221dfd161cf29d0de6018683ede5190960f0a9ebcff34c27b5.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/87ee4872c1d27c221dfd161cf29d0de6018683ede5190960f0a9ebcff34c27b5.jpg)

![8b18154cd49e8d58811a5d41e810c6b217c95859f0be30bd2283de2e7a13ae99.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/8b18154cd49e8d58811a5d41e810c6b217c95859f0be30bd2283de2e7a13ae99.jpg)

![a01676d0b29f5dc9ec6692f0bd249dd2fb20ccfcc5a179b75de6190b83ae40a7.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/a01676d0b29f5dc9ec6692f0bd249dd2fb20ccfcc5a179b75de6190b83ae40a7.jpg)

![bf6d19b84add68b98a12ebcf773740df6a1f4c02dccb61f855cd01163ba9c471.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/bf6d19b84add68b98a12ebcf773740df6a1f4c02dccb61f855cd01163ba9c471.jpg)

![c1b95b05ecae27cb0b6b73f1d4d30beae2c87ffe90b8edec8c9904d0119579e1.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/c1b95b05ecae27cb0b6b73f1d4d30beae2c87ffe90b8edec8c9904d0119579e1.jpg)

![c7711ea491e5df8a6d12672227e0dc72c0e6bf2550096eb0cd8a6daf3eb9e808.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/c7711ea491e5df8a6d12672227e0dc72c0e6bf2550096eb0cd8a6daf3eb9e808.jpg)

![ca062e1a5c0e0cf811a4812baaebf2498a59bfe58827ab29fb263eb3f66f7adc.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/ca062e1a5c0e0cf811a4812baaebf2498a59bfe58827ab29fb263eb3f66f7adc.jpg)

![cd8e20150033560806644ce0864df20deaae00cf2ba2f117de28c81ef6393e29.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/cd8e20150033560806644ce0864df20deaae00cf2ba2f117de28c81ef6393e29.jpg)

![d95ac7738d151b80f8ce62730be44a5e7c7a91ae19ceae9f3fb9457bcea03c54.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/d95ac7738d151b80f8ce62730be44a5e7c7a91ae19ceae9f3fb9457bcea03c54.jpg)

![e2f327d51adffb2ae249b4be97d98019bcb0e67218b1a68280e22595d08606de.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/e2f327d51adffb2ae249b4be97d98019bcb0e67218b1a68280e22595d08606de.jpg)

![ec1845a473209029786ae9c21007e908ace0a234925aef58868ca35504257821.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/ec1845a473209029786ae9c21007e908ace0a234925aef58868ca35504257821.jpg)

![f2baa5d9f7ac8ab03b7c2e36fe5136111c520111b300307146de4eab66bc8936.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/f2baa5d9f7ac8ab03b7c2e36fe5136111c520111b300307146de4eab66bc8936.jpg)

![fa4b5c9c18d3caad78cb4312be72db1a26170a5662fdcc3b32780b02864a25d7.jpg](../emnlp_results/969_CanLLMs%20Generate%20and%20Solve%20Linguistic%20Olympiad%20Puzzles_/tables/fa4b5c9c18d3caad78cb4312be72db1a26170a5662fdcc3b32780b02864a25d7.jpg)

## E2LLM: Encoder Elongated Large Language Models for Long-Context Understanding and Reasoning


### Images

![76ebee9ad3ec9b0e152ab8b9dab1d0ba125d78cfe316acac411af6101b8cd408.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/images/76ebee9ad3ec9b0e152ab8b9dab1d0ba125d78cfe316acac411af6101b8cd408.jpg)

![7d87c0c19f99627f751b67f3288675f4eaf93f9fab9e673ddefcbe3b9263b85b.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/images/7d87c0c19f99627f751b67f3288675f4eaf93f9fab9e673ddefcbe3b9263b85b.jpg)

![a9fdf9f05d99777368e0881e0bc0959ec1b9d1564517895fe914948c59b1a6d4.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/images/a9fdf9f05d99777368e0881e0bc0959ec1b9d1564517895fe914948c59b1a6d4.jpg)

![e957db22ebd1b794c52ea80495df76acd54e9192d4ea4f9a5bdd8a662654b464.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/images/e957db22ebd1b794c52ea80495df76acd54e9192d4ea4f9a5bdd8a662654b464.jpg)

### Tables

![0d0c0a38931dd5763c3af59f4e28128f8793a5c06dc035f83fa4a5b224a808d6.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/0d0c0a38931dd5763c3af59f4e28128f8793a5c06dc035f83fa4a5b224a808d6.jpg)

![239536cad2bcc5a2a0dc814d2b4351a09a2ded6b7655d41bc0f5a15231bd2186.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/239536cad2bcc5a2a0dc814d2b4351a09a2ded6b7655d41bc0f5a15231bd2186.jpg)

![25739d26961d32e555dfe9f2c38e3539314ef782085c7b7152b1e459cc0ed570.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/25739d26961d32e555dfe9f2c38e3539314ef782085c7b7152b1e459cc0ed570.jpg)

![306442d2a7ebee737482a1517e192f563d10d13059f8a0d3cfa75c166262b4a8.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/306442d2a7ebee737482a1517e192f563d10d13059f8a0d3cfa75c166262b4a8.jpg)

![38fb031cdd831a586f7370774b06c45b53c8769a61cdd49aa71a695a30045499.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/38fb031cdd831a586f7370774b06c45b53c8769a61cdd49aa71a695a30045499.jpg)

![6800d53dce2f3c446e1b9de0224d5659fceddd8080053c170bb66c19fa92cca1.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/6800d53dce2f3c446e1b9de0224d5659fceddd8080053c170bb66c19fa92cca1.jpg)

![71fe7f6af220dc67734f6176ff106b8cf94b893d471c01dd5c705a65aa3db937.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/71fe7f6af220dc67734f6176ff106b8cf94b893d471c01dd5c705a65aa3db937.jpg)

![7551a2e4974de2fe1bb6386235506d4c1514d356ebb95fdf500e35404b399c39.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/7551a2e4974de2fe1bb6386235506d4c1514d356ebb95fdf500e35404b399c39.jpg)

![7d3e5d62ae68647374974801c57a348ecb9b01028e7693814bda401e1fa88669.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/7d3e5d62ae68647374974801c57a348ecb9b01028e7693814bda401e1fa88669.jpg)

![8b5d705c1c0074ab22841c2e2174ada042751b42e5ab102d8f3b91d38293f648.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/8b5d705c1c0074ab22841c2e2174ada042751b42e5ab102d8f3b91d38293f648.jpg)

![905331444d7a669e22660515fe283149aa1a1f72dd0ddd24e675e32f5c48b592.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/905331444d7a669e22660515fe283149aa1a1f72dd0ddd24e675e32f5c48b592.jpg)

![9a1b8d1c0aabc4c5e997767987813ae56781811d9905d0153ca1546c79ba30fa.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/9a1b8d1c0aabc4c5e997767987813ae56781811d9905d0153ca1546c79ba30fa.jpg)

![b0d34b07e756300cb104f863a17d1220bc19e562204edc2dc8d24a57843005ba.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/b0d34b07e756300cb104f863a17d1220bc19e562204edc2dc8d24a57843005ba.jpg)

![c3676427fc86bd99d02419ecc0da3ba1b79855ef30f3ce341984764f7cca064d.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/c3676427fc86bd99d02419ecc0da3ba1b79855ef30f3ce341984764f7cca064d.jpg)

![c371af2fe9fe0a97c18513b3c6979a4231f6437fa90efb0acf20cca48a4944e1.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/c371af2fe9fe0a97c18513b3c6979a4231f6437fa90efb0acf20cca48a4944e1.jpg)

![f4efc78488f6564e717e3c1e1e0a8692f633afc8898792f230b6d4a20086540e.jpg](../emnlp_results/970_E2LLM_%20Encoder%20Elongated%20Large%20Language%20Models%20for%20Long-Context%20Understanding%20and%20Reasoning/tables/f4efc78488f6564e717e3c1e1e0a8692f633afc8898792f230b6d4a20086540e.jpg)

## DivScore: Zero-Shot Detection ofLLM-Generated Text in Specialized Domains


### Images

![01cf3491154165570e164ae078adc72ff0ebe7484745a375cc8cbc64082d9d3f.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/images/01cf3491154165570e164ae078adc72ff0ebe7484745a375cc8cbc64082d9d3f.jpg)

![1c10bad6075b189cc1112c2a477342922666370e1c32fe5aa7a7e6517434f47a.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/images/1c10bad6075b189cc1112c2a477342922666370e1c32fe5aa7a7e6517434f47a.jpg)

![7b71edd3072f107d165a12c0cdade849a9b1f73086ca10924ec94f12bda577b0.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/images/7b71edd3072f107d165a12c0cdade849a9b1f73086ca10924ec94f12bda577b0.jpg)

![b169a0190273beb0cc019e78fe86a13de1c9d5798b01cfa54afe8cdfac24c696.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/images/b169a0190273beb0cc019e78fe86a13de1c9d5798b01cfa54afe8cdfac24c696.jpg)

![b33997681008aa6a70d6930549dad746d19cc5897e16a896b48bf44227930687.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/images/b33997681008aa6a70d6930549dad746d19cc5897e16a896b48bf44227930687.jpg)

![cc67d523870514d6ad2d57ca8ae5e349be21c157bc65eb0df1ab7bfad56ed9dc.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/images/cc67d523870514d6ad2d57ca8ae5e349be21c157bc65eb0df1ab7bfad56ed9dc.jpg)

### Tables

![235f594347a69e130860d23c4b24364ead47b35d0b7836415717b761d8e788f7.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/tables/235f594347a69e130860d23c4b24364ead47b35d0b7836415717b761d8e788f7.jpg)

![4a79f0085c954dfbf777e43bd7085ac810d92f4cf647c96f4b0cf8e381b7f054.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/tables/4a79f0085c954dfbf777e43bd7085ac810d92f4cf647c96f4b0cf8e381b7f054.jpg)

![5d60fc10d9e12e1eedd20ea6f7ad508cb9b9c2c3f0e1660bcb5400ed9a7a5472.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/tables/5d60fc10d9e12e1eedd20ea6f7ad508cb9b9c2c3f0e1660bcb5400ed9a7a5472.jpg)

![8fb99ac8cb68cea276a6c676767cd8be15f0b3457590ce150b2dd18440a598a4.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/tables/8fb99ac8cb68cea276a6c676767cd8be15f0b3457590ce150b2dd18440a598a4.jpg)

![d0c942c72bccb2b3d0a6cac08bc588584f21e94aef3247adf2343f92842bf65f.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/tables/d0c942c72bccb2b3d0a6cac08bc588584f21e94aef3247adf2343f92842bf65f.jpg)

![d643080efd41f3c5019ae93b345e5931346bc8476883e4ce7be576703a859d60.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/tables/d643080efd41f3c5019ae93b345e5931346bc8476883e4ce7be576703a859d60.jpg)

![e3f0adae5caccd340ab76aa56a00ef447b2f0777400915fce6ab9674471ef2ac.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/tables/e3f0adae5caccd340ab76aa56a00ef447b2f0777400915fce6ab9674471ef2ac.jpg)

![f46f654b86c49ec88d699b28cf4b976f6c9397cda4163964355d2dc2d0670881.jpg](../emnlp_results/971_DivScore_%20Zero-Shot%20Detection%20ofLLM-Generated%20Text%20in%20Specialized%20Domains/tables/f46f654b86c49ec88d699b28cf4b976f6c9397cda4163964355d2dc2d0670881.jpg)

## Multi-Document Event Extraction Using Large and Small Language Models


### Images

![5f83cb381338b5c02783e9938d4661c8a5ef07249d9755b5af00e035d26f59a2.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/images/5f83cb381338b5c02783e9938d4661c8a5ef07249d9755b5af00e035d26f59a2.jpg)

![696d8f00c59c4ef9cb77b7b84bfcd5567abba619c7b40cb2c5dea6710e4296ac.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/images/696d8f00c59c4ef9cb77b7b84bfcd5567abba619c7b40cb2c5dea6710e4296ac.jpg)

![70955b399fe05cd83b5ce33033fdf9132e927da7bb67f167caa21698164f8e0e.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/images/70955b399fe05cd83b5ce33033fdf9132e927da7bb67f167caa21698164f8e0e.jpg)

![7f861d4f2bfeac9ee86a0a5b62afdce81bcd1ff4d095ee46a6b6d970090f46ba.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/images/7f861d4f2bfeac9ee86a0a5b62afdce81bcd1ff4d095ee46a6b6d970090f46ba.jpg)

![8c9200670f0595ab976261bca0b0564aefdb7d96400f345dc5d37935af68ff43.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/images/8c9200670f0595ab976261bca0b0564aefdb7d96400f345dc5d37935af68ff43.jpg)

![94797605c3b9226e92543a58c5d4607024f5de9eb319e3559f1bdab6a7778ff8.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/images/94797605c3b9226e92543a58c5d4607024f5de9eb319e3559f1bdab6a7778ff8.jpg)

![9de8447b2a024aefa904cb48cf55d22bebef6642b1c4e74993a38f62822445c0.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/images/9de8447b2a024aefa904cb48cf55d22bebef6642b1c4e74993a38f62822445c0.jpg)

![fbee6e85332dee23979a111c71bda169dd19ca022c1b2ba47705f994191e18dd.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/images/fbee6e85332dee23979a111c71bda169dd19ca022c1b2ba47705f994191e18dd.jpg)

### Tables

![754b16a5a10b305c59534abf0d5186f8737cd0f9d7b89e4847a2b625dbecba3a.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/tables/754b16a5a10b305c59534abf0d5186f8737cd0f9d7b89e4847a2b625dbecba3a.jpg)

![77f811bc112eabd653f1ce3e85a8e63dd9ce0e2c1388a77ecfaf5e51f6fdc222.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/tables/77f811bc112eabd653f1ce3e85a8e63dd9ce0e2c1388a77ecfaf5e51f6fdc222.jpg)

![896b6ecd9a84ef4e43891a332e63ecb85ed4696fca99f27e2b2f2e2b50ffe880.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/tables/896b6ecd9a84ef4e43891a332e63ecb85ed4696fca99f27e2b2f2e2b50ffe880.jpg)

![9d675f2ba9bf40fe02d890f88f432639fe41183b203ccbcb040e293fbc7e88ee.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/tables/9d675f2ba9bf40fe02d890f88f432639fe41183b203ccbcb040e293fbc7e88ee.jpg)

![c355b2bdb13cc7218200e8d3aa827a403c2f219a48f6c1cba9549bbb03a96cc0.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/tables/c355b2bdb13cc7218200e8d3aa827a403c2f219a48f6c1cba9549bbb03a96cc0.jpg)

![cbdd3cbc835cf9a88ed2a9980e919478bd2e07a0cf386b07b316486b91181d77.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/tables/cbdd3cbc835cf9a88ed2a9980e919478bd2e07a0cf386b07b316486b91181d77.jpg)

![d3503efed7e94d042445850479569293fdd8451e32ea35758bfa8c99408f5fa1.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/tables/d3503efed7e94d042445850479569293fdd8451e32ea35758bfa8c99408f5fa1.jpg)

![dc9ff298370eb0c5e958ce61b5ad87cc43e5296fcd2123ca39c396d65f2e8a2d.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/tables/dc9ff298370eb0c5e958ce61b5ad87cc43e5296fcd2123ca39c396d65f2e8a2d.jpg)

![f7249b09ae38fab6033261dde544c756a87f1238f676850ad1cb7baa7070655f.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/tables/f7249b09ae38fab6033261dde544c756a87f1238f676850ad1cb7baa7070655f.jpg)

![fb0663fc7ec33049c5db54eb468dfa98ebff2d4c993de5725366e892601219bf.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/tables/fb0663fc7ec33049c5db54eb468dfa98ebff2d4c993de5725366e892601219bf.jpg)

![fee2d3c08ef54ed2a2721536dc57fd0816e4d9c893f57428b3630a9affdefb10.jpg](../emnlp_results/972_Multi-Document%20Event%20Extraction%20Using%20Large%20and%20Small%20Language%20Models/tables/fee2d3c08ef54ed2a2721536dc57fd0816e4d9c893f57428b3630a9affdefb10.jpg)

## MA-GTS: A Multi-Agent Framework for Solving Complex Graph Problems in Real-World Applications


### Images

![13080b596497982bf5c15a8f6a2de2b1e65125600e8c19d853cb02cdb6ba8681.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/images/13080b596497982bf5c15a8f6a2de2b1e65125600e8c19d853cb02cdb6ba8681.jpg)

![27b833390bd909224b63e208aa11c361738e2def3fc2cf7857338af64ccd8c04.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/images/27b833390bd909224b63e208aa11c361738e2def3fc2cf7857338af64ccd8c04.jpg)

![3834f82be8a48eee530ba6d66f4021a2edbb1196423b117b1a02175c540e1a8b.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/images/3834f82be8a48eee530ba6d66f4021a2edbb1196423b117b1a02175c540e1a8b.jpg)

![49abe779fa6222c4f0cef7fa6ea89f587f3e97d57bdb4368b8b3af7520a81759.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/images/49abe779fa6222c4f0cef7fa6ea89f587f3e97d57bdb4368b8b3af7520a81759.jpg)

![62ae7529bed8908c321599d4968e160d2f8fc75fe4293f30995fb09961da9020.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/images/62ae7529bed8908c321599d4968e160d2f8fc75fe4293f30995fb09961da9020.jpg)

![7185de0d3a987027226edd6cc520eab3275e577661c2803e3ed15523773e5752.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/images/7185de0d3a987027226edd6cc520eab3275e577661c2803e3ed15523773e5752.jpg)

![92b42a672d82584cfa3786ec245d1d1a7c98bafee30cff97923ac0389f02fc92.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/images/92b42a672d82584cfa3786ec245d1d1a7c98bafee30cff97923ac0389f02fc92.jpg)

![d1d71f3a27a30eb6bda512ffb166e2696141ec25e0f529e052848b5f11ad78ae.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/images/d1d71f3a27a30eb6bda512ffb166e2696141ec25e0f529e052848b5f11ad78ae.jpg)

![ea59cf94a5bf2f627d33ed905b443abc45a54601b4b70f5cffbde5c48f5bacf3.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/images/ea59cf94a5bf2f627d33ed905b443abc45a54601b4b70f5cffbde5c48f5bacf3.jpg)

### Tables

![1a4e17009cf5c4edb31442cda4d1b5195ebad954e68c80800254a108bdb0d731.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/tables/1a4e17009cf5c4edb31442cda4d1b5195ebad954e68c80800254a108bdb0d731.jpg)

![306260a173378f88ea0ebcd41179c41b8f8df28725208bb51a2932544ba217bc.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/tables/306260a173378f88ea0ebcd41179c41b8f8df28725208bb51a2932544ba217bc.jpg)

![4f3bee9f790cdb1ac833322287014f5ec7bde8296691752879a5932ae53d0a15.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/tables/4f3bee9f790cdb1ac833322287014f5ec7bde8296691752879a5932ae53d0a15.jpg)

![58a5100520188d7582aa3516bf831bae497359b8cb3638256f8b2266ebf5d2a6.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/tables/58a5100520188d7582aa3516bf831bae497359b8cb3638256f8b2266ebf5d2a6.jpg)

![76faa777e72c556e0d0bfb88d72c65f01e4fc306c17aafc44cb0a4df3d2573a9.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/tables/76faa777e72c556e0d0bfb88d72c65f01e4fc306c17aafc44cb0a4df3d2573a9.jpg)

![7acb39d7eeff493d4a744e682fbba940ddf46f25f26760b3eb36b398eb955396.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/tables/7acb39d7eeff493d4a744e682fbba940ddf46f25f26760b3eb36b398eb955396.jpg)

![c7b9980f67a5d6b4400da2da510795e75b9995fe11654dde2a1f553c6da1c14f.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/tables/c7b9980f67a5d6b4400da2da510795e75b9995fe11654dde2a1f553c6da1c14f.jpg)

![d2f257ba80c75c7589a59c5f1851fde9a64c9b2ed041714d5f53101591ea59d1.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/tables/d2f257ba80c75c7589a59c5f1851fde9a64c9b2ed041714d5f53101591ea59d1.jpg)

![d3bdc77b82410e0588f9fb7e3b69c675ee205f085c3ddfa5031f08947cbd1c66.jpg](../emnlp_results/973_MA-GTS_%20A%20Multi-Agent%20Framework%20for%20Solving%20Complex%20Graph%20Problems%20in%20Real-World%20Applications/tables/d3bdc77b82410e0588f9fb7e3b69c675ee205f085c3ddfa5031f08947cbd1c66.jpg)

## Enhancing Speech Large Language Models with Prompt-Aware Mixture of Audio Encoders


### Images

![a02eec4485220bd06a724f01d6f1469e5925b0701e4624865591a300c377f6ff.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/images/a02eec4485220bd06a724f01d6f1469e5925b0701e4624865591a300c377f6ff.jpg)

![a30d07787c9ae289faa78f76faee89f2de8da395ca5f37a29741c0009c73aaa9.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/images/a30d07787c9ae289faa78f76faee89f2de8da395ca5f37a29741c0009c73aaa9.jpg)

![bed83f8a7df518793ce0f519aa4605db9d9218d75651e57bf46865643dd5e033.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/images/bed83f8a7df518793ce0f519aa4605db9d9218d75651e57bf46865643dd5e033.jpg)

![ebd160c63e5301b628eac24da221ed785bfa2cc49f98d884af117dd8fac73b46.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/images/ebd160c63e5301b628eac24da221ed785bfa2cc49f98d884af117dd8fac73b46.jpg)

### Tables

![13b26a2f6129479fedf079c791b9c9f619dcb36259040142d0800bdac9bb0b9c.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/tables/13b26a2f6129479fedf079c791b9c9f619dcb36259040142d0800bdac9bb0b9c.jpg)

![1e0324752f14ac5224957e1b4efe16bbeb0fb5a3904381c6fe86eb01843d1413.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/tables/1e0324752f14ac5224957e1b4efe16bbeb0fb5a3904381c6fe86eb01843d1413.jpg)

![387d48916bb4cc1534aee93156ebdee0d29d322ed913f21b25f9bd684aef3bf5.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/tables/387d48916bb4cc1534aee93156ebdee0d29d322ed913f21b25f9bd684aef3bf5.jpg)

![58cee475ef9d617714a5a5020b999b78d451cbb873cb39a311792f95202ce583.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/tables/58cee475ef9d617714a5a5020b999b78d451cbb873cb39a311792f95202ce583.jpg)

![68c03d4dc50606e11e899cbbd19699018f18ee5a5f33ff11d15d77f9000431a5.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/tables/68c03d4dc50606e11e899cbbd19699018f18ee5a5f33ff11d15d77f9000431a5.jpg)

![832d5399fdd06b760058b9293ee28fa8d6d7430a0f482d485225635752aa93a3.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/tables/832d5399fdd06b760058b9293ee28fa8d6d7430a0f482d485225635752aa93a3.jpg)

![945cb5955ed79049342663083647a8af5779eb67713bf837393ec9aa2cd24f91.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/tables/945cb5955ed79049342663083647a8af5779eb67713bf837393ec9aa2cd24f91.jpg)

![a5f2f39e308c9fe140fad02f52964c08b8b49ac4fcffccfc3b7f76108ba5cd5d.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/tables/a5f2f39e308c9fe140fad02f52964c08b8b49ac4fcffccfc3b7f76108ba5cd5d.jpg)

![a6bb0fe63e5270d5c8c0aaa41ce7e8e3c02a41f20bdab3ee8f7dfa2c9e67835b.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/tables/a6bb0fe63e5270d5c8c0aaa41ce7e8e3c02a41f20bdab3ee8f7dfa2c9e67835b.jpg)

![b0c319ea879c5dded343b0e1202bba4176eda13cd1f75c71c03c7c0550fe2e1a.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/tables/b0c319ea879c5dded343b0e1202bba4176eda13cd1f75c71c03c7c0550fe2e1a.jpg)

![dec8c9e6fd3c1a06f9b3133d2635168f6f5103c5bd0cdce178dbecde442bfa20.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/tables/dec8c9e6fd3c1a06f9b3133d2635168f6f5103c5bd0cdce178dbecde442bfa20.jpg)

![ef5ec8634e1189f247a1e659a7b51d037226ec0454dea59f51472e0f2730cfaf.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/tables/ef5ec8634e1189f247a1e659a7b51d037226ec0454dea59f51472e0f2730cfaf.jpg)

![fdc73591a7396f958274a914b70c3a46f9dc12f5dd8c36da8f58f36afa74063c.jpg](../emnlp_results/974_Enhancing%20Speech%20Large%20Language%20Models%20with%20Prompt-Aware%20Mixture%20of%20Audio%20Encoders/tables/fdc73591a7396f958274a914b70c3a46f9dc12f5dd8c36da8f58f36afa74063c.jpg)

## CIKT: A Collaborative and Iterative Knowledge Tracing Framework with Large Language Models


### Images

![0656b870ed9fe4055f02827c286b6741060a95c4728a4dccbdaa11b9aece1f64.jpg](../emnlp_results/975_CIKT_%20A%20Collaborative%20and%20Iterative%20Knowledge%20Tracing%20Framework%20with%20Large%20Language%20Models/images/0656b870ed9fe4055f02827c286b6741060a95c4728a4dccbdaa11b9aece1f64.jpg)

![9620689160a7b8e3f9b23b10242b08f25ea9927f3badc2a955ad33cf7c12c7ea.jpg](../emnlp_results/975_CIKT_%20A%20Collaborative%20and%20Iterative%20Knowledge%20Tracing%20Framework%20with%20Large%20Language%20Models/images/9620689160a7b8e3f9b23b10242b08f25ea9927f3badc2a955ad33cf7c12c7ea.jpg)

### Tables

![2c7c03858b48ddc78303e1b3c209c752f5b441b8e01f4081cde76515b729579f.jpg](../emnlp_results/975_CIKT_%20A%20Collaborative%20and%20Iterative%20Knowledge%20Tracing%20Framework%20with%20Large%20Language%20Models/tables/2c7c03858b48ddc78303e1b3c209c752f5b441b8e01f4081cde76515b729579f.jpg)

![43112f8a26225b0dffbbbf74f268fcb556d42853bba2ba524a2af886df1fa39f.jpg](../emnlp_results/975_CIKT_%20A%20Collaborative%20and%20Iterative%20Knowledge%20Tracing%20Framework%20with%20Large%20Language%20Models/tables/43112f8a26225b0dffbbbf74f268fcb556d42853bba2ba524a2af886df1fa39f.jpg)

![457f10b71bb681306e2f91c9a7fbb917345299f27e2613ec1d9bb22a7e65efc2.jpg](../emnlp_results/975_CIKT_%20A%20Collaborative%20and%20Iterative%20Knowledge%20Tracing%20Framework%20with%20Large%20Language%20Models/tables/457f10b71bb681306e2f91c9a7fbb917345299f27e2613ec1d9bb22a7e65efc2.jpg)

![7234ee3d2fa684da2d25946b8f10b35055d41d3692e2b1854d1d06c1eab3aa98.jpg](../emnlp_results/975_CIKT_%20A%20Collaborative%20and%20Iterative%20Knowledge%20Tracing%20Framework%20with%20Large%20Language%20Models/tables/7234ee3d2fa684da2d25946b8f10b35055d41d3692e2b1854d1d06c1eab3aa98.jpg)

![9efb6607a1f966cf5ce37737576c01e70c0d8ec7feae2d3fb1607a588aff0b12.jpg](../emnlp_results/975_CIKT_%20A%20Collaborative%20and%20Iterative%20Knowledge%20Tracing%20Framework%20with%20Large%20Language%20Models/tables/9efb6607a1f966cf5ce37737576c01e70c0d8ec7feae2d3fb1607a588aff0b12.jpg)

![c0da040a097569de454c9a200da771b0143a503365474880d183f7692d9c4350.jpg](../emnlp_results/975_CIKT_%20A%20Collaborative%20and%20Iterative%20Knowledge%20Tracing%20Framework%20with%20Large%20Language%20Models/tables/c0da040a097569de454c9a200da771b0143a503365474880d183f7692d9c4350.jpg)

![d0b5d623ceaea1b42f2f0c2a6dbbcc9680163d3048d5d7ef058b3760764bbc20.jpg](../emnlp_results/975_CIKT_%20A%20Collaborative%20and%20Iterative%20Knowledge%20Tracing%20Framework%20with%20Large%20Language%20Models/tables/d0b5d623ceaea1b42f2f0c2a6dbbcc9680163d3048d5d7ef058b3760764bbc20.jpg)

## Mitigating Hallucinations inLM-BasedTTSModels via Distribution Alignment UsingGFlowNets


### Images

![0d6f35b1f38b596680031e3a97fa1fa639dc6037d6f656a2785a5c29bf909fcf.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/images/0d6f35b1f38b596680031e3a97fa1fa639dc6037d6f656a2785a5c29bf909fcf.jpg)

![3d6d0e02f3cfc70880385a5ae847ec1651f5a22eed590d86f21ec10ec393598d.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/images/3d6d0e02f3cfc70880385a5ae847ec1651f5a22eed590d86f21ec10ec393598d.jpg)

![405beb31220897f069db86ea56c52fcbfe87691666e445248b0c881ac032a908.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/images/405beb31220897f069db86ea56c52fcbfe87691666e445248b0c881ac032a908.jpg)

![541fd8b34f74624eea99a601e25544b4e74f39797ac3c121cc075ba36b1ff545.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/images/541fd8b34f74624eea99a601e25544b4e74f39797ac3c121cc075ba36b1ff545.jpg)

![62e7f4cb21518786c34c76e82680a870455c7877e99dacb76bb31af76e389734.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/images/62e7f4cb21518786c34c76e82680a870455c7877e99dacb76bb31af76e389734.jpg)

![807b9d15e1b87034da1d0fcba0a7798f16b4b2145986cec3087069b613daa606.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/images/807b9d15e1b87034da1d0fcba0a7798f16b4b2145986cec3087069b613daa606.jpg)

![8cf09aabd411e76af6a19b3b8098b3742b28cf5435c61834d97c5a118c8c0576.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/images/8cf09aabd411e76af6a19b3b8098b3742b28cf5435c61834d97c5a118c8c0576.jpg)

![b549a69a6ad2548438a392184966580c7e4b23b5debf3d067ba38ceaac9c0a0b.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/images/b549a69a6ad2548438a392184966580c7e4b23b5debf3d067ba38ceaac9c0a0b.jpg)

![c31ad6f925003b403dc34473a19fbccde8167ba39ee9ef06f5558c84eee01b22.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/images/c31ad6f925003b403dc34473a19fbccde8167ba39ee9ef06f5558c84eee01b22.jpg)

![d3d119d2737c11f5571dc0431fbc492c221ca8114462a08fc1baf74a6bb90427.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/images/d3d119d2737c11f5571dc0431fbc492c221ca8114462a08fc1baf74a6bb90427.jpg)

![d783d992a89baf3789a974c5d392f20a3477b41bd43212a7d5a704167759621e.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/images/d783d992a89baf3789a974c5d392f20a3477b41bd43212a7d5a704167759621e.jpg)

![f240fe16291b1e9bfc6d23477699d7db6b0bdeff579368d25d0bdb59919989b4.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/images/f240fe16291b1e9bfc6d23477699d7db6b0bdeff579368d25d0bdb59919989b4.jpg)

![f561ee56733bd59363f3d575fd1db03c14b61a1beebffaee573cf5c4824b72fe.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/images/f561ee56733bd59363f3d575fd1db03c14b61a1beebffaee573cf5c4824b72fe.jpg)

### Tables

![0eee05b31e7c861c7d45d6283803b4861719b116f0fda2e4d1e0a5a046cbdd6e.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/tables/0eee05b31e7c861c7d45d6283803b4861719b116f0fda2e4d1e0a5a046cbdd6e.jpg)

![4553be36a3b83727c521a99eaf61e98a13507cf592b3ca059729e6810e00e300.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/tables/4553be36a3b83727c521a99eaf61e98a13507cf592b3ca059729e6810e00e300.jpg)

![5e5e37f536101c43f908552db3384e03dcf4e14e080bd06ead2a1d0fd65233bd.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/tables/5e5e37f536101c43f908552db3384e03dcf4e14e080bd06ead2a1d0fd65233bd.jpg)

![7717d92691103ad996a0d7fd99c1f5e028faae4c56639f5b49c85142f2bfb049.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/tables/7717d92691103ad996a0d7fd99c1f5e028faae4c56639f5b49c85142f2bfb049.jpg)

![7d7b5709e3c75574b7facf92026cd40b69baf984c994b91763e580d305d1aaa5.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/tables/7d7b5709e3c75574b7facf92026cd40b69baf984c994b91763e580d305d1aaa5.jpg)

![adcf416958e14225479af75db633144a3d226c44c8d20d55970760ed57ed5ec4.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/tables/adcf416958e14225479af75db633144a3d226c44c8d20d55970760ed57ed5ec4.jpg)

![c6f4856e11c768d3c572028f1e27a1d33891b014e0ce301a0fd347c48378013a.jpg](../emnlp_results/976_Mitigating%20Hallucinations%20inLM-BasedTTSModels%20via%20Distribution%20Alignment%20UsingGFlowNets/tables/c6f4856e11c768d3c572028f1e27a1d33891b014e0ce301a0fd347c48378013a.jpg)

## MolErr2Fix: BenchmarkingLLMTrustworthiness in Chemistry via Modular Error Detection, Localization, Explanation, and Correction


### Images

![241f1ae45fdb620a70a933d093d6e89599ee3c0392101abf999e7840973ec3cd.jpg](../emnlp_results/977_MolErr2Fix_%20BenchmarkingLLMTrustworthiness%20in%20Chemistry%20via%20Modular%20Error%20Detection%2C%20Localization%2C%20E/images/241f1ae45fdb620a70a933d093d6e89599ee3c0392101abf999e7840973ec3cd.jpg)

![2ea5f5c237e15212cf745d3df577a5743e76d2156a506de26c7433951d2e6233.jpg](../emnlp_results/977_MolErr2Fix_%20BenchmarkingLLMTrustworthiness%20in%20Chemistry%20via%20Modular%20Error%20Detection%2C%20Localization%2C%20E/images/2ea5f5c237e15212cf745d3df577a5743e76d2156a506de26c7433951d2e6233.jpg)

![51a7af81ae71af37ca781d083c89e4fb5c676468c18e835c1d6c50433581b4c6.jpg](../emnlp_results/977_MolErr2Fix_%20BenchmarkingLLMTrustworthiness%20in%20Chemistry%20via%20Modular%20Error%20Detection%2C%20Localization%2C%20E/images/51a7af81ae71af37ca781d083c89e4fb5c676468c18e835c1d6c50433581b4c6.jpg)

![5b868327612f344e1f6295781eb2e89f8ea4a9e2f093d71f15260612dccdb969.jpg](../emnlp_results/977_MolErr2Fix_%20BenchmarkingLLMTrustworthiness%20in%20Chemistry%20via%20Modular%20Error%20Detection%2C%20Localization%2C%20E/images/5b868327612f344e1f6295781eb2e89f8ea4a9e2f093d71f15260612dccdb969.jpg)

![b4e255528bd179f74b2ace76e2c3e0a208b68ea926705991b3559dde37d996e3.jpg](../emnlp_results/977_MolErr2Fix_%20BenchmarkingLLMTrustworthiness%20in%20Chemistry%20via%20Modular%20Error%20Detection%2C%20Localization%2C%20E/images/b4e255528bd179f74b2ace76e2c3e0a208b68ea926705991b3559dde37d996e3.jpg)

![dcf939d9c5e896dd05035c08c564fba30487d9cfa7ab88c7a8fedc92fb37e1f5.jpg](../emnlp_results/977_MolErr2Fix_%20BenchmarkingLLMTrustworthiness%20in%20Chemistry%20via%20Modular%20Error%20Detection%2C%20Localization%2C%20E/images/dcf939d9c5e896dd05035c08c564fba30487d9cfa7ab88c7a8fedc92fb37e1f5.jpg)

![f44473a27695398d6b57d89816abad898ca02d5a3712d159d2353a174c434c61.jpg](../emnlp_results/977_MolErr2Fix_%20BenchmarkingLLMTrustworthiness%20in%20Chemistry%20via%20Modular%20Error%20Detection%2C%20Localization%2C%20E/images/f44473a27695398d6b57d89816abad898ca02d5a3712d159d2353a174c434c61.jpg)

### Tables

![22d8f3ae7d2df3d00d1d57336956445dadce501d6647459357c4b417ef0142b7.jpg](../emnlp_results/977_MolErr2Fix_%20BenchmarkingLLMTrustworthiness%20in%20Chemistry%20via%20Modular%20Error%20Detection%2C%20Localization%2C%20E/tables/22d8f3ae7d2df3d00d1d57336956445dadce501d6647459357c4b417ef0142b7.jpg)

![6ab78f037bc8497b41893571753bec4b8f1207100f104971367504626e08bf09.jpg](../emnlp_results/977_MolErr2Fix_%20BenchmarkingLLMTrustworthiness%20in%20Chemistry%20via%20Modular%20Error%20Detection%2C%20Localization%2C%20E/tables/6ab78f037bc8497b41893571753bec4b8f1207100f104971367504626e08bf09.jpg)

## Shared Path: Unraveling Memorization in MultilingualLLMs through Language Similarities


### Images

![1556bbf7604bf1eb09107c7bec9c4ec7d76d590ad4a3abe74a9c86c4a535fbcc.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/images/1556bbf7604bf1eb09107c7bec9c4ec7d76d590ad4a3abe74a9c86c4a535fbcc.jpg)

![616f68af632f9bdb9c53ec860cd37434990b1df88c66ddc5d3ec242662fd85f7.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/images/616f68af632f9bdb9c53ec860cd37434990b1df88c66ddc5d3ec242662fd85f7.jpg)

![6c04f03e431540af174001b6f975a453761077ead7872256fb8584250b9b0b56.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/images/6c04f03e431540af174001b6f975a453761077ead7872256fb8584250b9b0b56.jpg)

![711a799aba8bd220e92a3870aa352513bec5ccfcb312f659d5eaf6d2abee097a.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/images/711a799aba8bd220e92a3870aa352513bec5ccfcb312f659d5eaf6d2abee097a.jpg)

![a211ec2a8c94b75b1d976bdc8b9b4793b5c9aaa094b88a57e7831be9d1c04f4b.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/images/a211ec2a8c94b75b1d976bdc8b9b4793b5c9aaa094b88a57e7831be9d1c04f4b.jpg)

![a99082f69ededd2720d77e21ab77d6d70df199c30373db534e8d7ecdf0cb0ff2.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/images/a99082f69ededd2720d77e21ab77d6d70df199c30373db534e8d7ecdf0cb0ff2.jpg)

![bd9a472b0bad6e447739a1c4127ad2b6b602c540c5f682363f2aa76ebe14feaf.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/images/bd9a472b0bad6e447739a1c4127ad2b6b602c540c5f682363f2aa76ebe14feaf.jpg)

![c0fefdf0abfac1d4c24df822568349ba34df9d4fe619772f1eeed883bbbe09dd.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/images/c0fefdf0abfac1d4c24df822568349ba34df9d4fe619772f1eeed883bbbe09dd.jpg)

![db29be99643b46d8e81bee01690c706ed8809ba7e524c6d53b9ceda85dd11560.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/images/db29be99643b46d8e81bee01690c706ed8809ba7e524c6d53b9ceda85dd11560.jpg)

![ed12ba3b3612a6e61ef08ac543475dc46bb3f95840f793d05482c2c83875af8a.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/images/ed12ba3b3612a6e61ef08ac543475dc46bb3f95840f793d05482c2c83875af8a.jpg)

### Tables

![0998714538c8615f4c8d636855d347dadece206f39832d8b881a19d79ec16b08.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/0998714538c8615f4c8d636855d347dadece206f39832d8b881a19d79ec16b08.jpg)

![0af8392566ab7cc269d34ce9ff26ad2a0d41a1a7b54a77676d9d6334ba4bc80c.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/0af8392566ab7cc269d34ce9ff26ad2a0d41a1a7b54a77676d9d6334ba4bc80c.jpg)

![17bb8a2c9f5e467b8678a874f85cf490f2f0cb0a0b89ec882a269ec0f2561952.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/17bb8a2c9f5e467b8678a874f85cf490f2f0cb0a0b89ec882a269ec0f2561952.jpg)

![276c509bd8dd78f9c7c4fede4c611e0865ce661252e64150f7dc9ca3e0a221c8.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/276c509bd8dd78f9c7c4fede4c611e0865ce661252e64150f7dc9ca3e0a221c8.jpg)

![3352253bf99d811d93718974e21f31c2fc9719d9aa38457e2aaadcaed782ff7b.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/3352253bf99d811d93718974e21f31c2fc9719d9aa38457e2aaadcaed782ff7b.jpg)

![7fc111d7a0edcd1607467289effee360a3f795829cac1a6e08a7c882524d7e63.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/7fc111d7a0edcd1607467289effee360a3f795829cac1a6e08a7c882524d7e63.jpg)

![a892b224b5ec900fefc155caebdbc5540e9ad56c2193d3c21c55e523ab422597.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/a892b224b5ec900fefc155caebdbc5540e9ad56c2193d3c21c55e523ab422597.jpg)

![ad084b3ddd11d42b6278e5790d1dcb48f0f6f9a8d15b878296701fcb1fb75ff3.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/ad084b3ddd11d42b6278e5790d1dcb48f0f6f9a8d15b878296701fcb1fb75ff3.jpg)

![ad35e83432fed2a724dfde7e3ba7386ed4c9440d5cd452c29b1dbf2afd03fdd5.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/ad35e83432fed2a724dfde7e3ba7386ed4c9440d5cd452c29b1dbf2afd03fdd5.jpg)

![be769928bbadb17ec35f21207594a032dd3aedd8d2a8b4a15a1de26a79d5d215.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/be769928bbadb17ec35f21207594a032dd3aedd8d2a8b4a15a1de26a79d5d215.jpg)

![ca3f8b7902d891319ab2d240a31d9027e4cf75b35e8fc8851f6d4ba815872f21.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/ca3f8b7902d891319ab2d240a31d9027e4cf75b35e8fc8851f6d4ba815872f21.jpg)

![e5d818ad33769f6047f726649df70da90c84d159add0dc3a6d4380f194d67670.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/e5d818ad33769f6047f726649df70da90c84d159add0dc3a6d4380f194d67670.jpg)

![f6e31c12b0e23a450defc7415d8288e05fb70324b308320d900bc41bcc827157.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/f6e31c12b0e23a450defc7415d8288e05fb70324b308320d900bc41bcc827157.jpg)

![f95bd0b7ba1841472f5555045421ab92adcd9fc82196f66b8053abe238b972d2.jpg](../emnlp_results/978_Shared%20Path_%20Unraveling%20Memorization%20in%20MultilingualLLMs%20through%20Language%20Similarities/tables/f95bd0b7ba1841472f5555045421ab92adcd9fc82196f66b8053abe238b972d2.jpg)

## Embedding Domain Knowledge for Large Language Models via Reinforcement Learning from Augmented Generation


### Images

![46bae19dcab01c0ddf080ec5cd5f33f691f5d2ac87ca84b7244c02619dcec4aa.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/images/46bae19dcab01c0ddf080ec5cd5f33f691f5d2ac87ca84b7244c02619dcec4aa.jpg)

![9d4a1df57f73550765c5020dd40cfd448e8394c8ed52ffc564aa7caf197e6c46.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/images/9d4a1df57f73550765c5020dd40cfd448e8394c8ed52ffc564aa7caf197e6c46.jpg)

![a10c21020163c3da206606b76d63516ec78e420dcd8d371466b7a23e9c2d4951.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/images/a10c21020163c3da206606b76d63516ec78e420dcd8d371466b7a23e9c2d4951.jpg)

![a63e0e767cfcfdcbc48cb16b627dde7ed4569df05f8a9b04e014084c1d538804.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/images/a63e0e767cfcfdcbc48cb16b627dde7ed4569df05f8a9b04e014084c1d538804.jpg)

![e7ec5c86a902038f0e5c52c275ed813629bcd3967476519f9e195e6db3ab7c3e.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/images/e7ec5c86a902038f0e5c52c275ed813629bcd3967476519f9e195e6db3ab7c3e.jpg)

![efcec55c1a352d8c9c7b0d48eb9c0e80495686979f09430e0af8e463bb600afe.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/images/efcec55c1a352d8c9c7b0d48eb9c0e80495686979f09430e0af8e463bb600afe.jpg)

### Tables

![01887c93c07d166bd016d4e2f6eec4fe20258e0386732f47a80f1dc508b8362e.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/01887c93c07d166bd016d4e2f6eec4fe20258e0386732f47a80f1dc508b8362e.jpg)

![048bab1ffba817549623050caf5ee29f70044ba115b26e8316220f052a291f50.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/048bab1ffba817549623050caf5ee29f70044ba115b26e8316220f052a291f50.jpg)

![11365c31219c5429b1746b08cbf8355c1c371d94856b5f63045295a0d04df149.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/11365c31219c5429b1746b08cbf8355c1c371d94856b5f63045295a0d04df149.jpg)

![11a8be632adb1bb4d4b4d8a2fcf086f10f1eb5dc261a98a5bfe6b7c383c975a1.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/11a8be632adb1bb4d4b4d8a2fcf086f10f1eb5dc261a98a5bfe6b7c383c975a1.jpg)

![29f196e82e8f3e63468cffeca133b2a09ffc57457e0aa823e611d397f308afd0.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/29f196e82e8f3e63468cffeca133b2a09ffc57457e0aa823e611d397f308afd0.jpg)

![3553534eace6983ee393c3995640b30391ecda07e8df99c675fd027fd893707c.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/3553534eace6983ee393c3995640b30391ecda07e8df99c675fd027fd893707c.jpg)

![392de4c9212229220729141a5d3cbf53163f6919894204e6cbae2220977b3560.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/392de4c9212229220729141a5d3cbf53163f6919894204e6cbae2220977b3560.jpg)

![3d5dbe524a44496e4fc940057507bf876345a462cedf3a9f08268e15a75951c6.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/3d5dbe524a44496e4fc940057507bf876345a462cedf3a9f08268e15a75951c6.jpg)

![3e2aadc279bbe4e640cbabf90d7951a754993526ee4e440ef2e09da20b2c564b.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/3e2aadc279bbe4e640cbabf90d7951a754993526ee4e440ef2e09da20b2c564b.jpg)

![3ef2b07f7399919df309f38d84c422c327fd188d300627d64e2d1ebf446cec8a.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/3ef2b07f7399919df309f38d84c422c327fd188d300627d64e2d1ebf446cec8a.jpg)

![48a181c7264f7e86b442d2dad86f41202badd7845532bd3cf78573e7f9f7d066.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/48a181c7264f7e86b442d2dad86f41202badd7845532bd3cf78573e7f9f7d066.jpg)

![5998154fb76da06712e1b031dff4539c52622f4430755af9f64a4156d97b7ed7.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/5998154fb76da06712e1b031dff4539c52622f4430755af9f64a4156d97b7ed7.jpg)

![72d54ba1540a971b4909b8b94bef2c7bbbb39331d224993cca318377a9adb0ab.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/72d54ba1540a971b4909b8b94bef2c7bbbb39331d224993cca318377a9adb0ab.jpg)

![779bed041dfbf61c82aae07c23a3b1d7ba07d228832399911055eedce1f3ccdd.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/779bed041dfbf61c82aae07c23a3b1d7ba07d228832399911055eedce1f3ccdd.jpg)

![7b2347dbb0a1d6e48e72f2d8ecb292f96868bcc1aad037c98828c00f77f70c5d.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/7b2347dbb0a1d6e48e72f2d8ecb292f96868bcc1aad037c98828c00f77f70c5d.jpg)

![878da20ff58884d4887ee76085087d25d96b76492408348e9ea25978cd7e29db.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/878da20ff58884d4887ee76085087d25d96b76492408348e9ea25978cd7e29db.jpg)

![93e161498419475abcbb0df3f99a7e81c3e4f553855a57a51b1027d19bab9a54.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/93e161498419475abcbb0df3f99a7e81c3e4f553855a57a51b1027d19bab9a54.jpg)

![9a8c88753447516cd94e070117cdc71d260f834606738d8150ad2d8972bb8b27.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/9a8c88753447516cd94e070117cdc71d260f834606738d8150ad2d8972bb8b27.jpg)

![af8170374484307c2c3ff29f6d946ea52b9867859852322eb063b1159e65f05c.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/af8170374484307c2c3ff29f6d946ea52b9867859852322eb063b1159e65f05c.jpg)

![bea0d83370e5a93496bf1549343b3b49efbaa95473767320e58db0db2c9f2bee.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/bea0d83370e5a93496bf1549343b3b49efbaa95473767320e58db0db2c9f2bee.jpg)

![e83d5a5369a846a2ee9ffc48128a51f6a9b9671d3e58008cab9d6cb931c1a7a2.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/e83d5a5369a846a2ee9ffc48128a51f6a9b9671d3e58008cab9d6cb931c1a7a2.jpg)

![f15a54afa754bfa943fd4329b086c39646b8e5805530893f9a3ba276a1c5dce4.jpg](../emnlp_results/979_Embedding%20Domain%20Knowledge%20for%20Large%20Language%20Models%20via%20Reinforcement%20Learning%20from%20Augmented%20Gener/tables/f15a54afa754bfa943fd4329b086c39646b8e5805530893f9a3ba276a1c5dce4.jpg)

## LLM-Driven Completeness and Consistency Evaluation for Cultural Heritage Data Augmentation in Cross-Modal Retrieval


### Images

![6a02a70713aef513faab41ffb0219c4570be71bf027385828eef347523d7e0f1.jpg](../emnlp_results/980_LLM-Driven%20Completeness%20and%20Consistency%20Evaluation%20for%20Cultural%20Heritage%20Data%20Augmentation%20in%20Cross-/images/6a02a70713aef513faab41ffb0219c4570be71bf027385828eef347523d7e0f1.jpg)

![6ec54dac563fd8fc76adefd34c004552960afa58325b67b17490b194499fe66e.jpg](../emnlp_results/980_LLM-Driven%20Completeness%20and%20Consistency%20Evaluation%20for%20Cultural%20Heritage%20Data%20Augmentation%20in%20Cross-/images/6ec54dac563fd8fc76adefd34c004552960afa58325b67b17490b194499fe66e.jpg)

![760b68c86c89f101748547a70aee91941ed39e0290f8c4454bdf04e7e2a33b49.jpg](../emnlp_results/980_LLM-Driven%20Completeness%20and%20Consistency%20Evaluation%20for%20Cultural%20Heritage%20Data%20Augmentation%20in%20Cross-/images/760b68c86c89f101748547a70aee91941ed39e0290f8c4454bdf04e7e2a33b49.jpg)

![b7670f75f4b52b1cd7fa81232a3f14a0c6aea7ac8728030555aa1f7748c74d69.jpg](../emnlp_results/980_LLM-Driven%20Completeness%20and%20Consistency%20Evaluation%20for%20Cultural%20Heritage%20Data%20Augmentation%20in%20Cross-/images/b7670f75f4b52b1cd7fa81232a3f14a0c6aea7ac8728030555aa1f7748c74d69.jpg)

### Tables

![0c91f39c0d5add0759035c2044673a7f5fbef2f3f343c07b349e5674fc242b4e.jpg](../emnlp_results/980_LLM-Driven%20Completeness%20and%20Consistency%20Evaluation%20for%20Cultural%20Heritage%20Data%20Augmentation%20in%20Cross-/tables/0c91f39c0d5add0759035c2044673a7f5fbef2f3f343c07b349e5674fc242b4e.jpg)

![648308f26e25ae6d3e85abfc3d5e6c214918f5747bd8daac10e86ca3db020d9d.jpg](../emnlp_results/980_LLM-Driven%20Completeness%20and%20Consistency%20Evaluation%20for%20Cultural%20Heritage%20Data%20Augmentation%20in%20Cross-/tables/648308f26e25ae6d3e85abfc3d5e6c214918f5747bd8daac10e86ca3db020d9d.jpg)

![878a3fd0a15f4284d32af70b83d4c8adb67cf516dcca88d9b1e89c27287f2592.jpg](../emnlp_results/980_LLM-Driven%20Completeness%20and%20Consistency%20Evaluation%20for%20Cultural%20Heritage%20Data%20Augmentation%20in%20Cross-/tables/878a3fd0a15f4284d32af70b83d4c8adb67cf516dcca88d9b1e89c27287f2592.jpg)

## Artificial Impressions: Evaluating Large Language Model Behavior Through the Lens of Trait Impressions


### Images

![194ea133dc029fa4dc0b52488d058d029562ce5d0f191bec5c3daaf813ae76ba.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/images/194ea133dc029fa4dc0b52488d058d029562ce5d0f191bec5c3daaf813ae76ba.jpg)

![23f1c75b40956e852ba7a50f584f28cef701cc06ac01ed33993f3ad362d5a914.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/images/23f1c75b40956e852ba7a50f584f28cef701cc06ac01ed33993f3ad362d5a914.jpg)

![42ce582e9d6930a885f8f3daa3ef2fe5408c76afbf5a50e4a8fb1e490f822064.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/images/42ce582e9d6930a885f8f3daa3ef2fe5408c76afbf5a50e4a8fb1e490f822064.jpg)

![611c99d4454a23f3c3cb2933aaa48ef04c2a7304087fee8f5b9c7c95fec52278.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/images/611c99d4454a23f3c3cb2933aaa48ef04c2a7304087fee8f5b9c7c95fec52278.jpg)

![786bea3a35a84a690ae576b74efe9fe8d13643e5231c9c40a16f586f596c8f74.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/images/786bea3a35a84a690ae576b74efe9fe8d13643e5231c9c40a16f586f596c8f74.jpg)

![7a91dc2ef8512170abc7435718c85ab1d96ff6360042abeeb157971abb621715.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/images/7a91dc2ef8512170abc7435718c85ab1d96ff6360042abeeb157971abb621715.jpg)

![af0b363647b1bdc48382a6e5df5607e3ccce83b7596ce5fd3bc150da3b50de38.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/images/af0b363647b1bdc48382a6e5df5607e3ccce83b7596ce5fd3bc150da3b50de38.jpg)

![bb966732fd3bb1d01ff27ca12b3080547c759267fe0bba1cc8f6226174059387.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/images/bb966732fd3bb1d01ff27ca12b3080547c759267fe0bba1cc8f6226174059387.jpg)

![d10f0e0f9939763615f61713fb5f7ff36d4dd080053a354f170d9a6d57e8c526.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/images/d10f0e0f9939763615f61713fb5f7ff36d4dd080053a354f170d9a6d57e8c526.jpg)

![d5b6c36e0759ffe995b469d7b7d1f8de07363db3f7c86120283a8559a56bfb72.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/images/d5b6c36e0759ffe995b469d7b7d1f8de07363db3f7c86120283a8559a56bfb72.jpg)

![f6bcd29b60d616520158dd79f89755030c3fae1430d1aeae1d320d6b4fdd3a69.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/images/f6bcd29b60d616520158dd79f89755030c3fae1430d1aeae1d320d6b4fdd3a69.jpg)

### Tables

![01a1155d9cabb7c79b48392ce27b34106b24d1e8112a4df0083408746e414a1d.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/01a1155d9cabb7c79b48392ce27b34106b24d1e8112a4df0083408746e414a1d.jpg)

![09cfe89b19a472b2be9488870a593d543c2e57fbc1583837add8ccceae9a7a4b.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/09cfe89b19a472b2be9488870a593d543c2e57fbc1583837add8ccceae9a7a4b.jpg)

![0a4fde6a79269fad0771747842b728b7db50890bf9a1f118c9ae118e85f92740.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/0a4fde6a79269fad0771747842b728b7db50890bf9a1f118c9ae118e85f92740.jpg)

![13cf18d02fea3216cb065955218a3b862065b37f2c3df2c90405bd503d3d02b9.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/13cf18d02fea3216cb065955218a3b862065b37f2c3df2c90405bd503d3d02b9.jpg)

![14c96add57d3095c21a64722d9a8587a2dc3fdb748f50a012278ee60da9afa29.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/14c96add57d3095c21a64722d9a8587a2dc3fdb748f50a012278ee60da9afa29.jpg)

![17a7c8df8423bf9e1ffb4f5eea7b0b19a623ff011bef34fc3985e215724b246a.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/17a7c8df8423bf9e1ffb4f5eea7b0b19a623ff011bef34fc3985e215724b246a.jpg)

![196141d5c32d3a727a9a56402077027b63da9c16d1885e5a7a42de6f006b6fc1.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/196141d5c32d3a727a9a56402077027b63da9c16d1885e5a7a42de6f006b6fc1.jpg)

![22aaa3ee205408ad69d05139ff9a61567f6a8d662cc78377170ca298a3686165.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/22aaa3ee205408ad69d05139ff9a61567f6a8d662cc78377170ca298a3686165.jpg)

![2585538964212bf5010e574a810367bd6579dd41c97942c7c41fcc2a8f883d34.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/2585538964212bf5010e574a810367bd6579dd41c97942c7c41fcc2a8f883d34.jpg)

![2757e9f8fcbf50fbe2f928ce0519bea46267292a862ff26489ad309d0218c1d9.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/2757e9f8fcbf50fbe2f928ce0519bea46267292a862ff26489ad309d0218c1d9.jpg)

![29a6447134381431e9cc7d3d9cb7b112f1d1846c1ce03cd798b4d4086d1e955e.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/29a6447134381431e9cc7d3d9cb7b112f1d1846c1ce03cd798b4d4086d1e955e.jpg)

![2e07a898de14f3ccd1e97c5f51ba557b4befb66048f57a052789f9a51e11984b.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/2e07a898de14f3ccd1e97c5f51ba557b4befb66048f57a052789f9a51e11984b.jpg)

![3078d49d58eb5b7815feccadf45b8a1116dbb53ecc4bdc08594c2008a38aeb26.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/3078d49d58eb5b7815feccadf45b8a1116dbb53ecc4bdc08594c2008a38aeb26.jpg)

![31cf99f2df24bbddee2b79d3f4ab4cbfe55fa0d7f451b0e935210fe6ebce82b3.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/31cf99f2df24bbddee2b79d3f4ab4cbfe55fa0d7f451b0e935210fe6ebce82b3.jpg)

![33bc32ab46981a16b482135f1e998bff717863ca8568141033dc975f5b3b4931.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/33bc32ab46981a16b482135f1e998bff717863ca8568141033dc975f5b3b4931.jpg)

![35c41054d6ad03bae07a3ea55c608607bb71e56ae72d4be99c0f743cb7f339ac.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/35c41054d6ad03bae07a3ea55c608607bb71e56ae72d4be99c0f743cb7f339ac.jpg)

![370ccd22c666a062dce1f9a40ce142141773d706c9d99a033c7cc7ff5cc67323.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/370ccd22c666a062dce1f9a40ce142141773d706c9d99a033c7cc7ff5cc67323.jpg)

![3751e9e89a92bd023729a232e8d20aaa8d7ca97cb3b6b35f5a6e36552e726ba8.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/3751e9e89a92bd023729a232e8d20aaa8d7ca97cb3b6b35f5a6e36552e726ba8.jpg)

![3ad8989763865b578bbc95786e8174124e4199a86ac3e3f93dd06d484f72fe19.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/3ad8989763865b578bbc95786e8174124e4199a86ac3e3f93dd06d484f72fe19.jpg)

![3b57c3305153e0f75fff395a5670aa9456d9b4615b14070fe56557af241ced7e.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/3b57c3305153e0f75fff395a5670aa9456d9b4615b14070fe56557af241ced7e.jpg)

![3c2c01ebe14fb7bc28aed85dd224ca3ef3594c51a107a696cf5d1e98f79e0d19.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/3c2c01ebe14fb7bc28aed85dd224ca3ef3594c51a107a696cf5d1e98f79e0d19.jpg)

![4365ff2ac6ed2ccd15a980c0a92544f22a6619c67a2d14160d235a018bd82ec7.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/4365ff2ac6ed2ccd15a980c0a92544f22a6619c67a2d14160d235a018bd82ec7.jpg)

![47643abea4be6026b9a4d024c33b4da8c8da074f30380da81a4cb8f0ff9995c4.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/47643abea4be6026b9a4d024c33b4da8c8da074f30380da81a4cb8f0ff9995c4.jpg)

![4e6ba780dce6927a6613e6d3db065a16108c88fd399e646124fb92a611e1a972.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/4e6ba780dce6927a6613e6d3db065a16108c88fd399e646124fb92a611e1a972.jpg)

![4f6158ae037acc1c5e735d989e5073864291b17c7238df79df33ef4e09814288.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/4f6158ae037acc1c5e735d989e5073864291b17c7238df79df33ef4e09814288.jpg)

![5d42dc66f27ed40a96a48d0053540289158916fc4f8215fd7b0ca2eef3664165.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/5d42dc66f27ed40a96a48d0053540289158916fc4f8215fd7b0ca2eef3664165.jpg)

![61fc331671af3242d3a3f1759ed59e4c20f814ced808b463e87ccde030436b59.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/61fc331671af3242d3a3f1759ed59e4c20f814ced808b463e87ccde030436b59.jpg)

![6fdd8bc26436e8f32568807f7cf776d696d14bb7f6a5307013772c04154fbcaf.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/6fdd8bc26436e8f32568807f7cf776d696d14bb7f6a5307013772c04154fbcaf.jpg)

![703ccdebe7ce0ea5b6abffafef2128c58766bcba0015cd6153ef683c4c0b2440.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/703ccdebe7ce0ea5b6abffafef2128c58766bcba0015cd6153ef683c4c0b2440.jpg)

![72ae39713c9ed0e1b1b51dcab2ec04b9abcce2d736f35847051d9cdac1537b7f.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/72ae39713c9ed0e1b1b51dcab2ec04b9abcce2d736f35847051d9cdac1537b7f.jpg)

![74842965c22761192daadbbba790bdd4617404c106d1e2f92a61c022deeedbdd.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/74842965c22761192daadbbba790bdd4617404c106d1e2f92a61c022deeedbdd.jpg)

![7495eb294a9bd1790a777bc050331ea19b8176b27a8c677d27cb34a98e39a4ee.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/7495eb294a9bd1790a777bc050331ea19b8176b27a8c677d27cb34a98e39a4ee.jpg)

![7ce529c4aca43e8def7156ee23f187bad613bf8628174234f3eac9ea7e7608ec.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/7ce529c4aca43e8def7156ee23f187bad613bf8628174234f3eac9ea7e7608ec.jpg)

![7ff6abdee4a339e8a6df10c0492eeef7a36205d7d19e7f4ccd9303d4a9085abb.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/7ff6abdee4a339e8a6df10c0492eeef7a36205d7d19e7f4ccd9303d4a9085abb.jpg)

![8e3d96c62eaa50c2a1d840cc974974a076a9930674f00eaa2ccb053803f045ba.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/8e3d96c62eaa50c2a1d840cc974974a076a9930674f00eaa2ccb053803f045ba.jpg)

![a090e4705f3afd967a748d61e95ac600e7a1482dbdeab19ea7ab826ed222b544.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/a090e4705f3afd967a748d61e95ac600e7a1482dbdeab19ea7ab826ed222b544.jpg)

![baf5cabeff6466ae4dc5374711d4525362936a6dc3fc75794bc6815b07f75ff1.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/baf5cabeff6466ae4dc5374711d4525362936a6dc3fc75794bc6815b07f75ff1.jpg)

![be05c358c71db35db2a2eb95695c1ee99ff1dc660104ec6cde96f2d58c89d0db.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/be05c358c71db35db2a2eb95695c1ee99ff1dc660104ec6cde96f2d58c89d0db.jpg)

![be18ce87be7cf75c64f4f533388b0f991d7eab80552ae68fa1cc3bf727aa1042.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/be18ce87be7cf75c64f4f533388b0f991d7eab80552ae68fa1cc3bf727aa1042.jpg)

![c59d56fdb6d9d94e2ae051c8f00f6d3affdf2e7f9d785130cbcdb08619f9d741.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/c59d56fdb6d9d94e2ae051c8f00f6d3affdf2e7f9d785130cbcdb08619f9d741.jpg)

![d37e2de524c6709b056ab0cf5e62ce4ec4622b77baa5da367fa6d6fc066ce7da.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/d37e2de524c6709b056ab0cf5e62ce4ec4622b77baa5da367fa6d6fc066ce7da.jpg)

![e31f867a0c732dc295811061fef20d332ad73d7c096c1ce02a41e686336e4570.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/e31f867a0c732dc295811061fef20d332ad73d7c096c1ce02a41e686336e4570.jpg)

![e5caea4c9e7312508087f1f9fef86b18f7cbc35d98d2d3d3247a50af23b2b66c.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/e5caea4c9e7312508087f1f9fef86b18f7cbc35d98d2d3d3247a50af23b2b66c.jpg)

![ecb7bef97b605c16fa900115cf6d2a3203f589b5a94be2f7c2c763f863a27c11.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/ecb7bef97b605c16fa900115cf6d2a3203f589b5a94be2f7c2c763f863a27c11.jpg)

![ee45fdb72c05df87234ad392e4a10462414cf9e5f8aac512d31dab0a441f4fa8.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/ee45fdb72c05df87234ad392e4a10462414cf9e5f8aac512d31dab0a441f4fa8.jpg)

![f0066f80c2180ec017aae190c8361b13ffe3a90d38d63fe6b73358e87fda92c7.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/f0066f80c2180ec017aae190c8361b13ffe3a90d38d63fe6b73358e87fda92c7.jpg)

![f2badb286ae30d6a4a5ccb25bd370429abfd056ac57521611ead2500f56f15cd.jpg](../emnlp_results/981_Artificial%20Impressions_%20Evaluating%20Large%20Language%20Model%20Behavior%20Through%20the%20Lens%20of%20Trait%20Impressio/tables/f2badb286ae30d6a4a5ccb25bd370429abfd056ac57521611ead2500f56f15cd.jpg)

## Mitigating Hallucinations in Large Vision-Language Models via Entity-Centric Multimodal Preference Optimization


### Images

![15646244763e31c8755ae4de8ceb1e1f9d98ed87131918a3c0ee682807591e18.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/15646244763e31c8755ae4de8ceb1e1f9d98ed87131918a3c0ee682807591e18.jpg)

![1cfa810297139e85820e1f50bd60da6ea50a5d871b9420e018557bab9219f744.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/1cfa810297139e85820e1f50bd60da6ea50a5d871b9420e018557bab9219f744.jpg)

![31a7dd591f62795e6430db3667386ae8fc483ee98d022611d49d204ea5613d43.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/31a7dd591f62795e6430db3667386ae8fc483ee98d022611d49d204ea5613d43.jpg)

![3da9713ee1548c4a65ffda4cee91750559e7522664acf4662a1c2755dc2be73c.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/3da9713ee1548c4a65ffda4cee91750559e7522664acf4662a1c2755dc2be73c.jpg)

![42df89c1f8db5114ab236859cb6cc82cbdf5d3d840fdcbc2e6c425729d364d22.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/42df89c1f8db5114ab236859cb6cc82cbdf5d3d840fdcbc2e6c425729d364d22.jpg)

![490621a0da01cff59f7bfadbac88ab038eab62ba0fdbb0f014a8fcb0fe023eee.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/490621a0da01cff59f7bfadbac88ab038eab62ba0fdbb0f014a8fcb0fe023eee.jpg)

![5bc8d638678689e69d961bd426095d3d207921058154920ebddec95ee6bf6685.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/5bc8d638678689e69d961bd426095d3d207921058154920ebddec95ee6bf6685.jpg)

![68874e71ac6cf5bdcefd459a09a96a8eb7d1a0a20bf266abc0ae5f6c90040b67.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/68874e71ac6cf5bdcefd459a09a96a8eb7d1a0a20bf266abc0ae5f6c90040b67.jpg)

![700a162348f5773ee8935057407d0a3855a08a0b8eed276b0032c6ff2bf4fc00.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/700a162348f5773ee8935057407d0a3855a08a0b8eed276b0032c6ff2bf4fc00.jpg)

![9ef10964f6f05b286a8d64e93195c80ef6e768350488eb70130c46a5dddaeab0.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/9ef10964f6f05b286a8d64e93195c80ef6e768350488eb70130c46a5dddaeab0.jpg)

![a5057f94ed8e1b016259775eea8cde1aedd5daaa4c99741a76ad8930a43e1baf.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/a5057f94ed8e1b016259775eea8cde1aedd5daaa4c99741a76ad8930a43e1baf.jpg)

![a846356c3e11bec22a81cf145cae521d595c67c067a2e2864d96e5a277bf8607.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/a846356c3e11bec22a81cf145cae521d595c67c067a2e2864d96e5a277bf8607.jpg)

![a91644c90477ee2edcc8fbde75d834564abea6450ebf7af05c37002936f268a2.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/a91644c90477ee2edcc8fbde75d834564abea6450ebf7af05c37002936f268a2.jpg)

![f119cf8f6207fe64dae953a95f29a852721ef8c0ba2d022365c3076bf073d90c.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/f119cf8f6207fe64dae953a95f29a852721ef8c0ba2d022365c3076bf073d90c.jpg)

![ffa1f8f13ccd13f1efb59831d58a51e3b396c1c6502a2e18665956e2118c55b2.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/images/ffa1f8f13ccd13f1efb59831d58a51e3b396c1c6502a2e18665956e2118c55b2.jpg)

### Tables

![16ef66e364065144ab9ea97d4d494cc42644fd766448c9ee67c6deecd9230501.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/tables/16ef66e364065144ab9ea97d4d494cc42644fd766448c9ee67c6deecd9230501.jpg)

![435a204e1244bf1d7d5ef643532f5134ee001fc477d2648e6a69e76d163d52bd.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/tables/435a204e1244bf1d7d5ef643532f5134ee001fc477d2648e6a69e76d163d52bd.jpg)

![6afa5706f32a59f11edaa70fd3e9492e73c0156d92b321fb99e1b2967fd090d0.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/tables/6afa5706f32a59f11edaa70fd3e9492e73c0156d92b321fb99e1b2967fd090d0.jpg)

![8a22858d29537cd6d786796204e5a09b5d6e0799a6519f122094b66f83793066.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/tables/8a22858d29537cd6d786796204e5a09b5d6e0799a6519f122094b66f83793066.jpg)

![a87420b705d5a47c4ce317774be0f28f406b4f8dce12db61b389d2081b19d0d8.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/tables/a87420b705d5a47c4ce317774be0f28f406b4f8dce12db61b389d2081b19d0d8.jpg)

![b9d0d22441b8298ddaf6c080e07a0ca222597bb45abcc7f483ad010a963d8930.jpg](../emnlp_results/982_Mitigating%20Hallucinations%20in%20Large%20Vision-Language%20Models%20via%20Entity-Centric%20Multimodal%20Preference%20O/tables/b9d0d22441b8298ddaf6c080e07a0ca222597bb45abcc7f483ad010a963d8930.jpg)

## 3DS: Medical Domain Adaptation ofLLMs via Decomposed Difficulty-based Data Selection


### Images

![0e66aee757e9fa14a9cae4f7567ec84e7bbe912f68b69280e359a60cd118355a.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/images/0e66aee757e9fa14a9cae4f7567ec84e7bbe912f68b69280e359a60cd118355a.jpg)

![100230da3b7143f88371c13490e7041a552f42daa2ec3407911f74acc7e7d20a.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/images/100230da3b7143f88371c13490e7041a552f42daa2ec3407911f74acc7e7d20a.jpg)

![40b2e70ec52c6a2aaf4f9f769616bea361115da1fdf846670f2e2018605c9efa.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/images/40b2e70ec52c6a2aaf4f9f769616bea361115da1fdf846670f2e2018605c9efa.jpg)

![4b62cb669913c569d17b3ead8df4bbab302ce2d676cd445a52e008375936ef58.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/images/4b62cb669913c569d17b3ead8df4bbab302ce2d676cd445a52e008375936ef58.jpg)

![6de4f2b83ec7450200e40e09d7fb848f69bde34d017faa4dc29e4c63d3c84474.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/images/6de4f2b83ec7450200e40e09d7fb848f69bde34d017faa4dc29e4c63d3c84474.jpg)

![dee43c7db5dda61d102f818d198a5f0e7dfd3077a3faaa30194f76fbf455c572.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/images/dee43c7db5dda61d102f818d198a5f0e7dfd3077a3faaa30194f76fbf455c572.jpg)

### Tables

![0e648c392d3bcdb6a328afe984962e1304ea9f80f5f7b551d21ac95d68150b86.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/0e648c392d3bcdb6a328afe984962e1304ea9f80f5f7b551d21ac95d68150b86.jpg)

![1f1e5247749b5747436fe31ee61b20bbbd234d786dee8803e02409ed833f788f.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/1f1e5247749b5747436fe31ee61b20bbbd234d786dee8803e02409ed833f788f.jpg)

![2d15db42166862a1334a31fd69f369f581289b6b13335a342a2935a363cc9b2c.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/2d15db42166862a1334a31fd69f369f581289b6b13335a342a2935a363cc9b2c.jpg)

![38cf1be594205f1ace1422553a21e4b5d46f4e46acc01d7a78bd0dca3df95228.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/38cf1be594205f1ace1422553a21e4b5d46f4e46acc01d7a78bd0dca3df95228.jpg)

![3ae9c2e6a6ade8c9c7f5abaf4ab80ce2a6a2fa2af229faafdfe8269dd7a923fa.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/3ae9c2e6a6ade8c9c7f5abaf4ab80ce2a6a2fa2af229faafdfe8269dd7a923fa.jpg)

![442c6ccba9d210044328a6ec20b178da32d4e3ff2ebd938096abe3f4d9d20856.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/442c6ccba9d210044328a6ec20b178da32d4e3ff2ebd938096abe3f4d9d20856.jpg)

![5d66725ac183f4ac7e1b899cdf7715226d5ab49bf72e34fb3df75534da6ff3d2.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/5d66725ac183f4ac7e1b899cdf7715226d5ab49bf72e34fb3df75534da6ff3d2.jpg)

![748675dc47a383840309b7431a6dbdd316cbad9a34fea6e8a14a56e066bd31cd.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/748675dc47a383840309b7431a6dbdd316cbad9a34fea6e8a14a56e066bd31cd.jpg)

![8a1028ddfd2e568f9350be8eea6d1d352f4b7cb833cac380a367923ea701a8db.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/8a1028ddfd2e568f9350be8eea6d1d352f4b7cb833cac380a367923ea701a8db.jpg)

![a255b92099396523b8a48efc9caae9d1f1ce3c5b5b71cf70cf39a29294fcbbfd.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/a255b92099396523b8a48efc9caae9d1f1ce3c5b5b71cf70cf39a29294fcbbfd.jpg)

![af2c153a703d159363bad8aeff5925ea64d207fdddc38b566a6e14bd98da9765.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/af2c153a703d159363bad8aeff5925ea64d207fdddc38b566a6e14bd98da9765.jpg)

![d0d3d6ebcdd0d7837aed05d94b631669360f2ded43ffd9f92a5685d54876aaf8.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/d0d3d6ebcdd0d7837aed05d94b631669360f2ded43ffd9f92a5685d54876aaf8.jpg)

![d53ad77f17c28fbe14203688c0c8f1652bfadfbced95aa62ed69524a74bbbd21.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/d53ad77f17c28fbe14203688c0c8f1652bfadfbced95aa62ed69524a74bbbd21.jpg)

![dcd7af4c82757671d34092338aa3eb17216318107a38bea55b7bfaad96ad1153.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/dcd7af4c82757671d34092338aa3eb17216318107a38bea55b7bfaad96ad1153.jpg)

![ee3d21f312ced982ac5aab2ea9deb0e31e8b2b8b7209d7d791de29f02991dbb4.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/ee3d21f312ced982ac5aab2ea9deb0e31e8b2b8b7209d7d791de29f02991dbb4.jpg)

![f36f1e00d281fe5b1fd58617d7b66127af28d3ad25e31d498b5362e683348057.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/f36f1e00d281fe5b1fd58617d7b66127af28d3ad25e31d498b5362e683348057.jpg)

![f801e0c157120e40770e4b03dacdd5c36df5b040df47cada37abba9c3a1c90db.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/f801e0c157120e40770e4b03dacdd5c36df5b040df47cada37abba9c3a1c90db.jpg)

![fd0991670814e34fc72e25663423716584ebd95efe6066ef4250c57825ebfdc0.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/fd0991670814e34fc72e25663423716584ebd95efe6066ef4250c57825ebfdc0.jpg)

![fdf6eccb70667511666f8300005e6bca87d4304c87ef8a7d177e4aaca9ad458b.jpg](../emnlp_results/983_3DS_%20Medical%20Domain%20Adaptation%20ofLLMs%20via%20Decomposed%20Difficulty-based%20Data%20Selection/tables/fdf6eccb70667511666f8300005e6bca87d4304c87ef8a7d177e4aaca9ad458b.jpg)

## InfiniBench: A Benchmark for Large Multi-Modal Models in Long-Form Movies andTVShows


### Images

![2da5c17535388b0e48b72ff74294632d17169dfa0b495a87682562876272b190.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/2da5c17535388b0e48b72ff74294632d17169dfa0b495a87682562876272b190.jpg)

![318f6689a469230a0194ff8068a527eb633bb96cab6a2c68bebdbce30dca1886.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/318f6689a469230a0194ff8068a527eb633bb96cab6a2c68bebdbce30dca1886.jpg)

![3bec5ce720378b6d15236d136753ccb44eaa52ad4c38905da8ea978a1d25df8e.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/3bec5ce720378b6d15236d136753ccb44eaa52ad4c38905da8ea978a1d25df8e.jpg)

![48b0c3565c81555f7d393bb4d27a1987a4d2f73c0102136bbbbaeccc51ba43f4.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/48b0c3565c81555f7d393bb4d27a1987a4d2f73c0102136bbbbaeccc51ba43f4.jpg)

![70a403e8a0aa3a8cd61fee7a1392b2544800be8e010957164f7763b798e71b51.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/70a403e8a0aa3a8cd61fee7a1392b2544800be8e010957164f7763b798e71b51.jpg)

![7d9e9ebd11aa3c574f901fd9d6785a5364ad1392751f8b47034b1f8138b296e7.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/7d9e9ebd11aa3c574f901fd9d6785a5364ad1392751f8b47034b1f8138b296e7.jpg)

![80bd18c8f6ba719164951bc837d5c3a0bcd3256e45c31883741d6ac9fce885b2.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/80bd18c8f6ba719164951bc837d5c3a0bcd3256e45c31883741d6ac9fce885b2.jpg)

![932aaa11ecb57124aa8ab65c9033992004a4b2318b1497c7c292aecfeec7b9f4.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/932aaa11ecb57124aa8ab65c9033992004a4b2318b1497c7c292aecfeec7b9f4.jpg)

![9399ab2ee73455a305cfb471d2394373ebd73fa377a580b20f2f562e270da3ba.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/9399ab2ee73455a305cfb471d2394373ebd73fa377a580b20f2f562e270da3ba.jpg)

![9b2af3c583c2b371bd2fa999b6984cb8af816514cb762823533045cf1d74f651.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/9b2af3c583c2b371bd2fa999b6984cb8af816514cb762823533045cf1d74f651.jpg)

![9d695c5a121be5b9727300486440290121bce65857b30dce073bf4aae9fa9fb9.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/9d695c5a121be5b9727300486440290121bce65857b30dce073bf4aae9fa9fb9.jpg)

![a597d6bb0d666a0b3375d1a2542f49e05e7b3b0b18c7a73c27c335debe59ba63.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/a597d6bb0d666a0b3375d1a2542f49e05e7b3b0b18c7a73c27c335debe59ba63.jpg)

![aeeae1045e1dee2a82e5ea5be80bdcf45deb59faff5953fc0e8552b37bf42e7d.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/aeeae1045e1dee2a82e5ea5be80bdcf45deb59faff5953fc0e8552b37bf42e7d.jpg)

![b76e71646d5072b709644406f22a136442717b10e9757ade509e9e7921357a5e.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/b76e71646d5072b709644406f22a136442717b10e9757ade509e9e7921357a5e.jpg)

![b8fdb162d1f37dfcaeb59e4220f7cff9dffd7cde662859b5ef9395a77f0e779f.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/b8fdb162d1f37dfcaeb59e4220f7cff9dffd7cde662859b5ef9395a77f0e779f.jpg)

![e3ac6839bade090131968f6178b8f39327b012193acd225b3cb27d35cbf15933.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/e3ac6839bade090131968f6178b8f39327b012193acd225b3cb27d35cbf15933.jpg)

![edf77a2014badaef56e7e578b9d781c5a7a60dc49e655fcdfa7b8a30df1c9762.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/edf77a2014badaef56e7e578b9d781c5a7a60dc49e655fcdfa7b8a30df1c9762.jpg)

![ee4a24ba39880c9e02b4b9bc25f1c177a309e6be5aaabcdc70859109eeca0dcb.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/ee4a24ba39880c9e02b4b9bc25f1c177a309e6be5aaabcdc70859109eeca0dcb.jpg)

![f0cd19e3fa49c6a76fe13828b8a319f1a5f682601556f0186dcdc6dfa510859d.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/f0cd19e3fa49c6a76fe13828b8a319f1a5f682601556f0186dcdc6dfa510859d.jpg)

![fc2248eea19c75b38d33b68296f3b54f6fa67afb8af8c92d8a3346545ba4fb8e.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/fc2248eea19c75b38d33b68296f3b54f6fa67afb8af8c92d8a3346545ba4fb8e.jpg)

![fd5771b8abd53a4ebe07e6f1c4ec7140e286fdbeebd953c64b0130d0387df042.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/images/fd5771b8abd53a4ebe07e6f1c4ec7140e286fdbeebd953c64b0130d0387df042.jpg)

### Tables

![0c68aa5b0f1dd8c231571f22649d1b08292bcf6a7ab3fc84ef00717219d8480e.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/tables/0c68aa5b0f1dd8c231571f22649d1b08292bcf6a7ab3fc84ef00717219d8480e.jpg)

![14fdeb0c9bc2b79c30e761175afe6a7a7412ff4709eec0500e4398be6cb58ad2.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/tables/14fdeb0c9bc2b79c30e761175afe6a7a7412ff4709eec0500e4398be6cb58ad2.jpg)

![24e013114d4a191419b8c6bb0e1177c7c65935f4257291e2e3dba0a1ae3dcb25.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/tables/24e013114d4a191419b8c6bb0e1177c7c65935f4257291e2e3dba0a1ae3dcb25.jpg)

![2a7da364514a3e39272fe120a28fb784940055099f708d021707777d3713cfac.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/tables/2a7da364514a3e39272fe120a28fb784940055099f708d021707777d3713cfac.jpg)

![35488dd33b35e50f419bd9e3752d96eb251b4fd5a306d24eb0740fb644d9853f.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/tables/35488dd33b35e50f419bd9e3752d96eb251b4fd5a306d24eb0740fb644d9853f.jpg)

![39bdd6e0c78a5a647ddaa69d88731d7a7437d8e32bbf385d7c852be6f3da982b.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/tables/39bdd6e0c78a5a647ddaa69d88731d7a7437d8e32bbf385d7c852be6f3da982b.jpg)

![4d7dbaebfa707db2d270a4084b62b6ec53c53e8af127d1ab125c365b2b2120d4.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/tables/4d7dbaebfa707db2d270a4084b62b6ec53c53e8af127d1ab125c365b2b2120d4.jpg)

![6543bedddb22d804ca37427104d5b78dfe7753f2fb2fb0a139744f0135290da3.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/tables/6543bedddb22d804ca37427104d5b78dfe7753f2fb2fb0a139744f0135290da3.jpg)

![c930441de26d215484550aa2281c597dd6154a6dff02e51eee792bb8dfd501ce.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/tables/c930441de26d215484550aa2281c597dd6154a6dff02e51eee792bb8dfd501ce.jpg)

![f2605518c17f49190102c68ad2bab4bf7ae245d72ed7810ce519cad6f9692051.jpg](../emnlp_results/984_InfiniBench_%20A%20Benchmark%20for%20Large%20Multi-Modal%20Models%20in%20Long-Form%20Movies%20andTVShows/tables/f2605518c17f49190102c68ad2bab4bf7ae245d72ed7810ce519cad6f9692051.jpg)

## Intrinsic Test of Unlearning Using Parametric Knowledge Traces


### Images

![227fc577b28688fdcc46018dd13174857987b75218be70b01af74d4d56e6386a.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/images/227fc577b28688fdcc46018dd13174857987b75218be70b01af74d4d56e6386a.jpg)

![3a22110ce3538c576e1fc4ceabc3afafd99757cace8ae73b783fc48fac4582d0.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/images/3a22110ce3538c576e1fc4ceabc3afafd99757cace8ae73b783fc48fac4582d0.jpg)

![4cbe745c481466c2fd29c4023e47870908e2339f9528847ab3aab99cb16578c7.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/images/4cbe745c481466c2fd29c4023e47870908e2339f9528847ab3aab99cb16578c7.jpg)

![52acaa308729a334a839808b018a2403a3c6a4c16795f87ed49793265542e115.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/images/52acaa308729a334a839808b018a2403a3c6a4c16795f87ed49793265542e115.jpg)

![5a20526692af5ee7f803834e3cc15185b4c45d3a91a775f390850e1689ef5832.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/images/5a20526692af5ee7f803834e3cc15185b4c45d3a91a775f390850e1689ef5832.jpg)

![5b32b29fc8ddc8e150ab1d05073c015f001becbe630ce3618d08488bf2e58496.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/images/5b32b29fc8ddc8e150ab1d05073c015f001becbe630ce3618d08488bf2e58496.jpg)

![a4002b822f21bc60c38818014067622d7b9a442fc6041cf6b0b611e79c36dd48.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/images/a4002b822f21bc60c38818014067622d7b9a442fc6041cf6b0b611e79c36dd48.jpg)

![b3daaac4a847e9146cbe0433b2663513155d5bf84a1580ed88f56fcce318d96d.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/images/b3daaac4a847e9146cbe0433b2663513155d5bf84a1580ed88f56fcce318d96d.jpg)

![b79ab137569239de315b1d2a66bb02c2042ec9635b184823e769b880951782f8.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/images/b79ab137569239de315b1d2a66bb02c2042ec9635b184823e769b880951782f8.jpg)

![d308d2282fdb906550427453f8b586ca8288e3ad0edf20c924dee7a6b8e92d6b.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/images/d308d2282fdb906550427453f8b586ca8288e3ad0edf20c924dee7a6b8e92d6b.jpg)

### Tables

![28df88ce2cb7dda8db71d1c5e6eb73fc2a7a6cc44693b3c8b6b49e35e9f180a9.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/tables/28df88ce2cb7dda8db71d1c5e6eb73fc2a7a6cc44693b3c8b6b49e35e9f180a9.jpg)

![31858eda19c2900632514fbd99a5a731a904dc4ef0322e190fc04cdcbad1510d.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/tables/31858eda19c2900632514fbd99a5a731a904dc4ef0322e190fc04cdcbad1510d.jpg)

![336b6a2a73125ebf0a611680104e344025665df8d09b290d96b526bf75a5c6e4.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/tables/336b6a2a73125ebf0a611680104e344025665df8d09b290d96b526bf75a5c6e4.jpg)

![741ab6fb99a3af554ac8ec5de4e4f6a669092fee6b450daf4c281ed5c43920c7.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/tables/741ab6fb99a3af554ac8ec5de4e4f6a669092fee6b450daf4c281ed5c43920c7.jpg)

![799b798be9d86de9f823b7bac296eb7eb93bddad989aacc8f0a971d8dcd4f17b.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/tables/799b798be9d86de9f823b7bac296eb7eb93bddad989aacc8f0a971d8dcd4f17b.jpg)

![aa857b4010af951ee186a03b1ef5480ad31d922cb42675ceb81f16b6b899216a.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/tables/aa857b4010af951ee186a03b1ef5480ad31d922cb42675ceb81f16b6b899216a.jpg)

![d6fdb96676e7ab274d8338c3d1322a3887089b0d6d857dda53d88b89e35c6ccb.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/tables/d6fdb96676e7ab274d8338c3d1322a3887089b0d6d857dda53d88b89e35c6ccb.jpg)

![e06ba9799800af7e0b92f89f389297925007550d398cbbfe84e77c20b7896122.jpg](../emnlp_results/985_Intrinsic%20Test%20of%20Unlearning%20Using%20Parametric%20Knowledge%20Traces/tables/e06ba9799800af7e0b92f89f389297925007550d398cbbfe84e77c20b7896122.jpg)

## Speculative Streaming: Efficient and Scalable Speculative Decoding with Multi-Stream Attention


### Images

![0bd2474915afcb45c03b1cff8a6edac9c374d77e871c01c51f440a863d828d23.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/0bd2474915afcb45c03b1cff8a6edac9c374d77e871c01c51f440a863d828d23.jpg)

![0cdefbf0f14b6b32455a19884f8bcf1162fd4fe3812d2bd6f6882fd4d9c45a56.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/0cdefbf0f14b6b32455a19884f8bcf1162fd4fe3812d2bd6f6882fd4d9c45a56.jpg)

![1b0eb4d1d83a6537b4bd3f4d3f64966d032275edb09aadd0d303a094190af6ce.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/1b0eb4d1d83a6537b4bd3f4d3f64966d032275edb09aadd0d303a094190af6ce.jpg)

![1bfe2d091a70a87ecacc4f4ee24659f808cb60870ca0e195d186051b883ccf53.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/1bfe2d091a70a87ecacc4f4ee24659f808cb60870ca0e195d186051b883ccf53.jpg)

![278d6e1980d4ce0e534acd40eaa5be307484f153d98472a1a885860e85db33e8.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/278d6e1980d4ce0e534acd40eaa5be307484f153d98472a1a885860e85db33e8.jpg)

![3785df3c18cba596a7cee82baef94ef3d76ca557aa6d62a9df49bcecd4df4544.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/3785df3c18cba596a7cee82baef94ef3d76ca557aa6d62a9df49bcecd4df4544.jpg)

![43642b0590a89adc900706fb2f50b45444fe6b4b2cd3bb6c1aaa496e3e0eb8e8.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/43642b0590a89adc900706fb2f50b45444fe6b4b2cd3bb6c1aaa496e3e0eb8e8.jpg)

![4a46b2d4fb3349fc1c41f6e04ef15322778bcd92e80b90ecc597b2e3ae26c9bf.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/4a46b2d4fb3349fc1c41f6e04ef15322778bcd92e80b90ecc597b2e3ae26c9bf.jpg)

![779481cab9cd6ea5179e451dbb4af15540250f5e822bf60e2c8280f5357ee0ea.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/779481cab9cd6ea5179e451dbb4af15540250f5e822bf60e2c8280f5357ee0ea.jpg)

![a04e8d4fe83e54bbdca8e71380e5b6c4e6721bc6be8ea418482b9b77f3718f9e.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/a04e8d4fe83e54bbdca8e71380e5b6c4e6721bc6be8ea418482b9b77f3718f9e.jpg)

![a56509f11d1c762ca4e242f84f35fb83b1d95d12d5ba759fa7cef0999bdb97ed.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/a56509f11d1c762ca4e242f84f35fb83b1d95d12d5ba759fa7cef0999bdb97ed.jpg)

![c9f87dc8dbc6f35143b197206e148e1bec75e8cf571adbfb996a673db88e46e0.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/c9f87dc8dbc6f35143b197206e148e1bec75e8cf571adbfb996a673db88e46e0.jpg)

![d4a0412b20b40a130e3a9b1fef612538f4391f6a596112cb9186143ae64d3322.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/d4a0412b20b40a130e3a9b1fef612538f4391f6a596112cb9186143ae64d3322.jpg)

![dba556e5e7b9a7bd69bd88f80a4fa1f14f2a67778bd64dc28dfa63d7ce4f53e9.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/dba556e5e7b9a7bd69bd88f80a4fa1f14f2a67778bd64dc28dfa63d7ce4f53e9.jpg)

![e3bbdce56d3ea328a4d27d7e110126e289a5975199744997c83af48a9cc5dd39.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/e3bbdce56d3ea328a4d27d7e110126e289a5975199744997c83af48a9cc5dd39.jpg)

![ee1d6184669bdb84c85c7c25828f23cc7a6b1524ff1e63b5b740d78333f2d03f.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/ee1d6184669bdb84c85c7c25828f23cc7a6b1524ff1e63b5b740d78333f2d03f.jpg)

![f9d4acd67e7d4eb8dd185d3946a447bd586bf629c24e3f757e8de02d0297381c.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/f9d4acd67e7d4eb8dd185d3946a447bd586bf629c24e3f757e8de02d0297381c.jpg)

![fa80fb8f4917b435b82a22951bcd89dfb64d93ee78cd117a3e40dc3f7a652a86.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/images/fa80fb8f4917b435b82a22951bcd89dfb64d93ee78cd117a3e40dc3f7a652a86.jpg)

### Tables

![1dfe25e0084cbb20389aec3dc442ff9059dba889e28dc8676a4683a6c56b2901.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/tables/1dfe25e0084cbb20389aec3dc442ff9059dba889e28dc8676a4683a6c56b2901.jpg)

![c63e765f19bd6a151e6782a183571980c5e6b1cfaef3edea94539f1796650932.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/tables/c63e765f19bd6a151e6782a183571980c5e6b1cfaef3edea94539f1796650932.jpg)

![c6ff6a56f526c8db803ff02b4438d3a71a04ec4f519c17fa86194c63525ad24a.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/tables/c6ff6a56f526c8db803ff02b4438d3a71a04ec4f519c17fa86194c63525ad24a.jpg)

![d1b18d51a0bf83a4420787beeec0476782b9ab436c859a90375f3564c97c7514.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/tables/d1b18d51a0bf83a4420787beeec0476782b9ab436c859a90375f3564c97c7514.jpg)

![fbd5bf5742b6d8222d82974314cb8732f072924025eb527009b0587d32c2e36e.jpg](../emnlp_results/986_Speculative%20Streaming_%20Efficient%20and%20Scalable%20Speculative%20Decoding%20with%20Multi-Stream%20Attention/tables/fbd5bf5742b6d8222d82974314cb8732f072924025eb527009b0587d32c2e36e.jpg)

## Evaluating Cognitive-Behavioral Fixation via Multimodal User Viewing Patterns on Social Media


### Images

![0482b0738f45ef4e6dab8d733b792d4d0f001f6a1ad212a149f71f20c3e991f2.jpg](../emnlp_results/987_Evaluating%20Cognitive-Behavioral%20Fixation%20via%20Multimodal%20User%20Viewing%20Patterns%20on%20Social%20Media/images/0482b0738f45ef4e6dab8d733b792d4d0f001f6a1ad212a149f71f20c3e991f2.jpg)

![2417f86f7e8bce939d6a436880f66767101cd91726d7298ea52f940dce9cf649.jpg](../emnlp_results/987_Evaluating%20Cognitive-Behavioral%20Fixation%20via%20Multimodal%20User%20Viewing%20Patterns%20on%20Social%20Media/images/2417f86f7e8bce939d6a436880f66767101cd91726d7298ea52f940dce9cf649.jpg)

![3726c6c7a0c0d52a878430df8ac2b01e0997229cda9cba4ecc5aae50cfaadba9.jpg](../emnlp_results/987_Evaluating%20Cognitive-Behavioral%20Fixation%20via%20Multimodal%20User%20Viewing%20Patterns%20on%20Social%20Media/images/3726c6c7a0c0d52a878430df8ac2b01e0997229cda9cba4ecc5aae50cfaadba9.jpg)

![63c95fa6a60b3e0c8150ff6a736c8c9f8a1645586db7b7f147e0298d7052b8e6.jpg](../emnlp_results/987_Evaluating%20Cognitive-Behavioral%20Fixation%20via%20Multimodal%20User%20Viewing%20Patterns%20on%20Social%20Media/images/63c95fa6a60b3e0c8150ff6a736c8c9f8a1645586db7b7f147e0298d7052b8e6.jpg)

![67d8dc5fdfbc21cf43d97f5f46b7120690fef32fa6e0fcdb28358941512696be.jpg](../emnlp_results/987_Evaluating%20Cognitive-Behavioral%20Fixation%20via%20Multimodal%20User%20Viewing%20Patterns%20on%20Social%20Media/images/67d8dc5fdfbc21cf43d97f5f46b7120690fef32fa6e0fcdb28358941512696be.jpg)

![dac87e903a4b5367e4c02b0e6a1dc903a1f5e8f989a22b559eb19e6fa84bb8a3.jpg](../emnlp_results/987_Evaluating%20Cognitive-Behavioral%20Fixation%20via%20Multimodal%20User%20Viewing%20Patterns%20on%20Social%20Media/images/dac87e903a4b5367e4c02b0e6a1dc903a1f5e8f989a22b559eb19e6fa84bb8a3.jpg)

![f3869b5c83082c1953211724a04d894d974486e4d5484940beacb25a4682ab06.jpg](../emnlp_results/987_Evaluating%20Cognitive-Behavioral%20Fixation%20via%20Multimodal%20User%20Viewing%20Patterns%20on%20Social%20Media/images/f3869b5c83082c1953211724a04d894d974486e4d5484940beacb25a4682ab06.jpg)

### Tables

![10d4eb54bacbdd38c5332436845f9bc2b6a5dbf8f033b815ce36621652fd5333.jpg](../emnlp_results/987_Evaluating%20Cognitive-Behavioral%20Fixation%20via%20Multimodal%20User%20Viewing%20Patterns%20on%20Social%20Media/tables/10d4eb54bacbdd38c5332436845f9bc2b6a5dbf8f033b815ce36621652fd5333.jpg)

![4a6c1ca34a807f05a35524c9672373632f35bcb26bda61775734cc59df3a4ab1.jpg](../emnlp_results/987_Evaluating%20Cognitive-Behavioral%20Fixation%20via%20Multimodal%20User%20Viewing%20Patterns%20on%20Social%20Media/tables/4a6c1ca34a807f05a35524c9672373632f35bcb26bda61775734cc59df3a4ab1.jpg)

![7b23eda69c40b53a13ef9ee3de01d1dd2753ae4949564a23de5f436a6c9f359f.jpg](../emnlp_results/987_Evaluating%20Cognitive-Behavioral%20Fixation%20via%20Multimodal%20User%20Viewing%20Patterns%20on%20Social%20Media/tables/7b23eda69c40b53a13ef9ee3de01d1dd2753ae4949564a23de5f436a6c9f359f.jpg)

## Mind the Gap: A Closer Look at Tokenization for Multiple-Choice Question Answering withLLMs


### Images

![0b7b796b94c2c22133214f43d833590693abc7fb649334e2e7c3d95fb6b91578.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/images/0b7b796b94c2c22133214f43d833590693abc7fb649334e2e7c3d95fb6b91578.jpg)

![2c207f517960c60f366cd4dfb2e0feb15c339ab6bc25f6a7527fb4b02e328d4d.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/images/2c207f517960c60f366cd4dfb2e0feb15c339ab6bc25f6a7527fb4b02e328d4d.jpg)

![412f8fddd9dc13e31ba034b44709bcee1feede615dbbb464a060504452af2645.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/images/412f8fddd9dc13e31ba034b44709bcee1feede615dbbb464a060504452af2645.jpg)

![4ae837dc5e10ab9344b217a413b827e81a857d8daad533b70436b7d305bce563.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/images/4ae837dc5e10ab9344b217a413b827e81a857d8daad533b70436b7d305bce563.jpg)

![cc88e02f6b924ce4f67f5cd7b399bb27b89969026f43a1825d41bf202c33269c.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/images/cc88e02f6b924ce4f67f5cd7b399bb27b89969026f43a1825d41bf202c33269c.jpg)

### Tables

![2711beaeae028d7d8557f180015b1f0b991fc7b7c4b6b1bc6ae9973740863d88.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/tables/2711beaeae028d7d8557f180015b1f0b991fc7b7c4b6b1bc6ae9973740863d88.jpg)

![2a55a1590a5112a8a4f8e17251965120596f8acb3205f51e84f1a30ecb834cd7.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/tables/2a55a1590a5112a8a4f8e17251965120596f8acb3205f51e84f1a30ecb834cd7.jpg)

![32c9bd5b97f27e79e1acd6e7e470fdd13df837d9613b8d9b0c9351d510b2ca9d.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/tables/32c9bd5b97f27e79e1acd6e7e470fdd13df837d9613b8d9b0c9351d510b2ca9d.jpg)

![43389c358979028734c91bcc245213822b515988fd6f99588ae9af4a5996b6fc.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/tables/43389c358979028734c91bcc245213822b515988fd6f99588ae9af4a5996b6fc.jpg)

![58594d30978c23426b6833b539b9b818e9c9ec541702f0f0e16c98af245a9301.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/tables/58594d30978c23426b6833b539b9b818e9c9ec541702f0f0e16c98af245a9301.jpg)

![6b7c381b31fa36549ac1e6a8583f008a71e593950ca3cb37d6bc8918b62bccb7.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/tables/6b7c381b31fa36549ac1e6a8583f008a71e593950ca3cb37d6bc8918b62bccb7.jpg)

![7fdeea978e208b8d67a7ba01894dd7a106b1148fedaed8b97f654420beed4e25.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/tables/7fdeea978e208b8d67a7ba01894dd7a106b1148fedaed8b97f654420beed4e25.jpg)

![dbdc624514d7ec325c49860da248b28b9ac40ad9ab1b5972a4ac666b6c5732ea.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/tables/dbdc624514d7ec325c49860da248b28b9ac40ad9ab1b5972a4ac666b6c5732ea.jpg)

![ea002221850452e0645bcb9cfd5ebdba1b8456a04197a9633961d03ef952926c.jpg](../emnlp_results/988_Mind%20the%20Gap_%20A%20Closer%20Look%20at%20Tokenization%20for%20Multiple-Choice%20Question%20Answering%20withLLMs/tables/ea002221850452e0645bcb9cfd5ebdba1b8456a04197a9633961d03ef952926c.jpg)

## VocalNet: SpeechLLMs with Multi-Token Prediction for Faster and High-Quality Generation


### Images

![134b544487e6c095b0f278861872af5e6eec8d1ec473cd0371e37060e1974483.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/images/134b544487e6c095b0f278861872af5e6eec8d1ec473cd0371e37060e1974483.jpg)

![1f5538646fdcabd24906c71cb0c0f05ec4a75406486a79eb11c5997a9568307c.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/images/1f5538646fdcabd24906c71cb0c0f05ec4a75406486a79eb11c5997a9568307c.jpg)

![46897aeab9c526634766d48efd6e396eafbc69eb7c2ebdccdd27ec7c786c9271.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/images/46897aeab9c526634766d48efd6e396eafbc69eb7c2ebdccdd27ec7c786c9271.jpg)

![83e84adee86b4d079a7e58c6bf1dadbd9f634caee188c341bf75ee2d45e72a0b.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/images/83e84adee86b4d079a7e58c6bf1dadbd9f634caee188c341bf75ee2d45e72a0b.jpg)

![9b8499634ad93e6ac8f2b3a08559ce99cb787b11f0c9cb81928a666eb4f53315.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/images/9b8499634ad93e6ac8f2b3a08559ce99cb787b11f0c9cb81928a666eb4f53315.jpg)

![ac2d4597da8dc1ba6ffc77983d6b24147d6fd39c62225eea3dba5889733f471e.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/images/ac2d4597da8dc1ba6ffc77983d6b24147d6fd39c62225eea3dba5889733f471e.jpg)

![d425e84f14c2940fecc6e3e3e567db2fb36d3c8ca0c04ca2fbdc9800b9987a49.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/images/d425e84f14c2940fecc6e3e3e567db2fb36d3c8ca0c04ca2fbdc9800b9987a49.jpg)

### Tables

![027370cbf92bca26d9d701251631e6a1d22bb83f4848c54048380737f1e682e1.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/tables/027370cbf92bca26d9d701251631e6a1d22bb83f4848c54048380737f1e682e1.jpg)

![0986b3b5e23aaff1cf706c5c30353acaca9ba5a126447ea4240a4e2c00f12768.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/tables/0986b3b5e23aaff1cf706c5c30353acaca9ba5a126447ea4240a4e2c00f12768.jpg)

![0c36c054cac9e3b6a382201eefbf9b534fada5a3d2fe41c8b1b9f5c62c3d1300.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/tables/0c36c054cac9e3b6a382201eefbf9b534fada5a3d2fe41c8b1b9f5c62c3d1300.jpg)

![2161aa1be49b50b3687f4a4eac263fd35766b3f2caceeb9fad2ca8f573fce598.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/tables/2161aa1be49b50b3687f4a4eac263fd35766b3f2caceeb9fad2ca8f573fce598.jpg)

![2c52585c53d65c453cf6cf2bb4a94add7517af4a30c54d3d9a06f7553cebb046.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/tables/2c52585c53d65c453cf6cf2bb4a94add7517af4a30c54d3d9a06f7553cebb046.jpg)

![5c48b8e9aad6b0e146a5b38bf01d57aee614b8b46b47dfe299c1d2493be1646b.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/tables/5c48b8e9aad6b0e146a5b38bf01d57aee614b8b46b47dfe299c1d2493be1646b.jpg)

![5ecdb40d70422b4ab04aaa3ba05bfb5ebfbb6d93ce244185c9e48b28c04d183e.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/tables/5ecdb40d70422b4ab04aaa3ba05bfb5ebfbb6d93ce244185c9e48b28c04d183e.jpg)

![7f947211b9037d48801c0b93adf33590c54ce87da0cca55360306c44a3082161.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/tables/7f947211b9037d48801c0b93adf33590c54ce87da0cca55360306c44a3082161.jpg)

![9ad9d04511d86db37aed1f5607287a118bbc279f0d443a63c19a96130a658261.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/tables/9ad9d04511d86db37aed1f5607287a118bbc279f0d443a63c19a96130a658261.jpg)

![9d31b52543d715ceaf7b97bbc89573e2d424e79f2df7821174f2a8c5e866ebc5.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/tables/9d31b52543d715ceaf7b97bbc89573e2d424e79f2df7821174f2a8c5e866ebc5.jpg)

![a3ab507b779e7c91c23202dc4b55457cebb777c58085d0e010f2bbc5ce254ea9.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/tables/a3ab507b779e7c91c23202dc4b55457cebb777c58085d0e010f2bbc5ce254ea9.jpg)

![c8f0a97452b354a328e0ab5dffbc957ce3bcdaf64f422ee139e4f56dc149b3ed.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/tables/c8f0a97452b354a328e0ab5dffbc957ce3bcdaf64f422ee139e4f56dc149b3ed.jpg)

![f6beb57d71ca9e8fb4c5a7f8a1cd25bd001dff33336c663d298b4236fba272e4.jpg](../emnlp_results/989_VocalNet_%20SpeechLLMs%20with%20Multi-Token%20Prediction%20for%20Faster%20and%20High-Quality%20Generation/tables/f6beb57d71ca9e8fb4c5a7f8a1cd25bd001dff33336c663d298b4236fba272e4.jpg)

## Path Drift in Large Reasoning Models: How First-Person Commitments Override Safety


### Images

![3e6c4fae4a72588051640ce36b503028abf6a4773e18e927420147d2b9a85802.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/images/3e6c4fae4a72588051640ce36b503028abf6a4773e18e927420147d2b9a85802.jpg)

![4aefed7f099e72cae3beb4165cdfc3cd90331ba01d8567f55aa210ac6526a72a.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/images/4aefed7f099e72cae3beb4165cdfc3cd90331ba01d8567f55aa210ac6526a72a.jpg)

![4cbcca10d0ea25c207c8331a907c4c433a81c2d83d2c4f2359cdc5c16e60e0e6.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/images/4cbcca10d0ea25c207c8331a907c4c433a81c2d83d2c4f2359cdc5c16e60e0e6.jpg)

![51577ce3965ca8cb4f461800789667cab6ad990e833f757c57aa8919da076fc7.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/images/51577ce3965ca8cb4f461800789667cab6ad990e833f757c57aa8919da076fc7.jpg)

![67f23a72dbe57066bc28bc25a6abed80016c04cb950bbc43919eaed5a5269281.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/images/67f23a72dbe57066bc28bc25a6abed80016c04cb950bbc43919eaed5a5269281.jpg)

![6bd1a7a776910adade1253e8801e60a9fa1d9abfc1e68943207c50ee40f64639.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/images/6bd1a7a776910adade1253e8801e60a9fa1d9abfc1e68943207c50ee40f64639.jpg)

![9cbfa9fb7ff63856aee52b9279b1cbc6b54e1a2aa82373017e0875d008a89675.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/images/9cbfa9fb7ff63856aee52b9279b1cbc6b54e1a2aa82373017e0875d008a89675.jpg)

![ac1d65b90db63f17f1aa49aa73a5d441ab1be5fc64422db416852d8d601b8368.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/images/ac1d65b90db63f17f1aa49aa73a5d441ab1be5fc64422db416852d8d601b8368.jpg)

![c491ad16e7644505076d91e5be479fc36a1da75581aba8fa507d0019240de2ca.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/images/c491ad16e7644505076d91e5be479fc36a1da75581aba8fa507d0019240de2ca.jpg)

![db34ad964cf51af0423669175181d5199c8f55d0ed59df2d27c9a890ed3b008a.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/images/db34ad964cf51af0423669175181d5199c8f55d0ed59df2d27c9a890ed3b008a.jpg)

![e4458567a45481d161d22c102e942e8976af1d724b8740e5432ad1e930df1908.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/images/e4458567a45481d161d22c102e942e8976af1d724b8740e5432ad1e930df1908.jpg)

### Tables

![11a5de9993c37a1f4a8c5a3bea47e335c01d452145b04e82bf525b7ce2ef8f04.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/tables/11a5de9993c37a1f4a8c5a3bea47e335c01d452145b04e82bf525b7ce2ef8f04.jpg)

![4a10e6098957ebec882d752da239305d79b3b34a01e078e09df8d4f18f7481fe.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/tables/4a10e6098957ebec882d752da239305d79b3b34a01e078e09df8d4f18f7481fe.jpg)

![6192e841f7b3e140bd5c741deef0b2997f8598887b8feeb34efbefd588520c08.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/tables/6192e841f7b3e140bd5c741deef0b2997f8598887b8feeb34efbefd588520c08.jpg)

![63ce0c9a185f2fe2db62790818783e224ea8e2b97223cd0ca7728d283c6f38f6.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/tables/63ce0c9a185f2fe2db62790818783e224ea8e2b97223cd0ca7728d283c6f38f6.jpg)

![75a4685f71e1bec38f41eb7337b0e1f8c104039e2d40c505bf2de22cef798bdf.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/tables/75a4685f71e1bec38f41eb7337b0e1f8c104039e2d40c505bf2de22cef798bdf.jpg)

![840c40d0f01f41186b7a41fa166d53ec86b6b26e679df7aa683b2e475acbed08.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/tables/840c40d0f01f41186b7a41fa166d53ec86b6b26e679df7aa683b2e475acbed08.jpg)

![bf3dc650dbb34bf6a66ef07ccbcb6cf7d9119691a0bcfef6bab929600089b9f6.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/tables/bf3dc650dbb34bf6a66ef07ccbcb6cf7d9119691a0bcfef6bab929600089b9f6.jpg)

![f037e1c63cc71487c0e51f6f59d383b21c6c733917d1258ed3a5eb9547b37386.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/tables/f037e1c63cc71487c0e51f6f59d383b21c6c733917d1258ed3a5eb9547b37386.jpg)

![f6db10454af42447b39b788f59aa4f5aad145f8ae3ec3036cd882f4d9ae3deaa.jpg](../emnlp_results/990_Path%20Drift%20in%20Large%20Reasoning%20Models_%20How%20First-Person%20Commitments%20Override%20Safety/tables/f6db10454af42447b39b788f59aa4f5aad145f8ae3ec3036cd882f4d9ae3deaa.jpg)

## CBP-Tuning: Efficient Local Customization for Black-box Large Language Models

### Images

![37780cdd30a2d0021601c1df702fff0c55a55ee90f40cf1df9de59d25ca4e4b4.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/images/37780cdd30a2d0021601c1df702fff0c55a55ee90f40cf1df9de59d25ca4e4b4.jpg)

![8211eba5a856dd4d47184ec2d35f2fb879d53ed97409b0ff174c7c17b3aaa727.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/images/8211eba5a856dd4d47184ec2d35f2fb879d53ed97409b0ff174c7c17b3aaa727.jpg)

![83d2e5333e1256f209f56a47109c98e7d7b58f0c9d5e2947f0ba3f43b34ec996.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/images/83d2e5333e1256f209f56a47109c98e7d7b58f0c9d5e2947f0ba3f43b34ec996.jpg)

![8f0f35546629bb1281bff1afd3ab56a950f72c4256a92f64d873f7f8e9f95c8e.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/images/8f0f35546629bb1281bff1afd3ab56a950f72c4256a92f64d873f7f8e9f95c8e.jpg)

![a7eed2779fc4f98a8ed6bcec63b3b0470cbcce2cddd00cc1cb43daea23e7510e.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/images/a7eed2779fc4f98a8ed6bcec63b3b0470cbcce2cddd00cc1cb43daea23e7510e.jpg)

### Tables

![1faeffef7f27acb0db1abdf74e3bc446c406439661fd726d34df32ea73778ac1.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/tables/1faeffef7f27acb0db1abdf74e3bc446c406439661fd726d34df32ea73778ac1.jpg)

![419c5e5064fc7ca92ca651888344291e027e6b9623697a53fad821fae3715e56.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/tables/419c5e5064fc7ca92ca651888344291e027e6b9623697a53fad821fae3715e56.jpg)

![4e08054860cbffdc422e0efea9bdfbe8449faebba0ce069521e7f4148325d4fb.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/tables/4e08054860cbffdc422e0efea9bdfbe8449faebba0ce069521e7f4148325d4fb.jpg)

![5ba7f944b84011603c9a11a1f4c69492d41883e4b73d339e88fc89d2cc7ba566.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/tables/5ba7f944b84011603c9a11a1f4c69492d41883e4b73d339e88fc89d2cc7ba566.jpg)

![959afdadf2f682b88dfc1f49a8771b28647797c7b7cff5a1153f391058771276.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/tables/959afdadf2f682b88dfc1f49a8771b28647797c7b7cff5a1153f391058771276.jpg)

![9818bfafc4ab44f72ca8f7c17ad00b59b08225959afbd7ef482fc56d112af06a.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/tables/9818bfafc4ab44f72ca8f7c17ad00b59b08225959afbd7ef482fc56d112af06a.jpg)

![adf00d7aa24ca78ef1ab78e13cae4b99732c2451d7451d6c20492f176816d9c0.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/tables/adf00d7aa24ca78ef1ab78e13cae4b99732c2451d7451d6c20492f176816d9c0.jpg)

![d2891b8ce9f20fbf68a90a42b9497248b4733f351e6098df88cb994b95082ba2.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/tables/d2891b8ce9f20fbf68a90a42b9497248b4733f351e6098df88cb994b95082ba2.jpg)

![e9ac10b7781a49b11728eb62d3274bf830f00570d5ba1495be211736e7ecb2c4.jpg](../emnlp_results/991_CBP-Tuning_%20Efficient%20Local%20Customization%20for%20Black-box%20Large%20Language%20Models/tables/e9ac10b7781a49b11728eb62d3274bf830f00570d5ba1495be211736e7ecb2c4.jpg)
