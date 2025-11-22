# EMNLP 2025 Main Conference Papers

**Summary:** 30 papers with extracted content:
- 📊 Total images: 14618
- 📋 Total tables: 17648
- 📄 Total files: 32266

*Note: Equations have been filtered out and are not included.*

---

# EMNLP 2025 Main Papers - Part 10 of 60

## 目录 (Table of Contents)

1. [APLOT: Robust Reward Modeling via Adaptive Preference Learning with Optimal Transport](#APLOT-Robust-Reward-Modeling-via-Adaptive-Preference-Learning-with-Optimal-Transport)
2. [HS-STaR: Hierarchical Sampling for Self-Taught Reasoners via Difficulty Estimation and Budget Reallocation](#HS-STaR-Hierarchical-Sampling-for-Self-Taught-Reasoners-via-Difficulty-Estimation-and-Budget-Reallocation)
3. [SEPS: A Separability Measure for Robust Unlearning inLLMs](#SEPS-A-Separability-Measure-for-Robust-Unlearning-inLLMs)
4. [TRUST-VL: An Explainable News Assistant for General Multimodal Misinformation Detection](#TRUST-VL-An-Explainable-News-Assistant-for-General-Multimodal-Misinformation-Detection)
5. [Tree-of-Quote Prompting Improves Factuality and Attribution in Multi-Hop and Medical Reasoning](#Tree-of-Quote-Prompting-Improves-Factuality-and-Attribution-in-Multi-Hop-and-Medical-Reasoning)
6. [UnitCoder: Scalable Code Synthesis from Pre-training Corpora](#UnitCoder-Scalable-Code-Synthesis-from-Pre-training-Corpora)
7. [GRPO-LEAD: A Difficulty-Aware Reinforcement Learning Approach for Concise Mathematical Reasoning in Language Models](#GRPO-LEAD-A-Difficulty-Aware-Reinforcement-Learning-Approach-for-Concise-Mathematical-Reasoning-in-Language-Models)
8. [Improving Low-Resource Sequence Labeling with Knowledge Fusion and Contextual Label Explanations](#Improving-Low-Resource-Sequence-Labeling-with-Knowledge-Fusion-and-Contextual-Label-Explanations)
9. [Rethinking Cross-Subject Data Splitting for Brain-to-Text Decoding](#Rethinking-Cross-Subject-Data-Splitting-for-Brain-to-Text-Decoding)
10. [RCScore: Quantifying Response Consistency in Large Language Models](#RCScore-Quantifying-Response-Consistency-in-Large-Language-Models)
11. [A Multi-Agent Framework with Automated Decision Rule Optimization for Cross-Domain Misinformation Detection](#A-Multi-Agent-Framework-with-Automated-Decision-Rule-Optimization-for-Cross-Domain-Misinformation-Detection)
12. [OmniEval: An Omnidirectional and AutomaticRAGEvaluation Benchmark in Financial Domain](#OmniEval-An-Omnidirectional-and-AutomaticRAGEvaluation-Benchmark-in-Financial-Domain)
13. [AQuilt: Weaving Logic and Self-Inspection into Low-Cost, High-Relevance Data Synthesis for SpecialistLLMs](#AQuilt-Weaving-Logic-and-Self-Inspection-into-Low-Cost-High-Relevance-Data-Synthesis-for-SpecialistLLMs)
14. [MoSEs: Uncertainty-AwareAI-Generated Text Detection via Mixture of Stylistics Experts with Conditional Thresholds](#MoSEs-Uncertainty-AwareAI-Generated-Text-Detection-via-Mixture-of-Stylistics-Experts-with-Conditional-Thresholds)
15. [Merger-as-a-Stealer: Stealing TargetedPIIfrom AlignedLLMs with Model Merging](#Merger-as-a-Stealer-Stealing-TargetedPIIfrom-AlignedLLMs-with-Model-Merging)
16. [Pragmatic Inference Chain (PIC) ImprovingLLMs’ Reasoning of Authentic Implicit Toxic Language](#Pragmatic-Inference-Chain-PIC-ImprovingLLMs-Reasoning-of-Authentic-Implicit-Toxic-Language)
17. [Beyond Demonstrations: Dynamic Vector Construction from Latent Representations](#Beyond-Demonstrations-Dynamic-Vector-Construction-from-Latent-Representations)
18. [Detoxifying Large Language Models via the Diversity of Toxic Samples](#Detoxifying-Large-Language-Models-via-the-Diversity-of-Toxic-Samples)
19. [LLM-Driven Implicit Target Augmentation and Fine-Grained Contextual Modeling for Zero-Shot and Few-Shot Stance Detection](#LLM-Driven-Implicit-Target-Augmentation-and-Fine-Grained-Contextual-Modeling-for-Zero-Shot-and-Few-Shot-Stance-Detection)
20. [Dial-InLLM: Human-AlignedLLM-in-the-loop Intent Clustering for Customer Service Dialogues](#Dial-InLLM-Human-AlignedLLM-in-the-loop-Intent-Clustering-for-Customer-Service-Dialogues)
21. [Superficial Self-Improved Reasoners Benefit from Model Merging](#Superficial-Self-Improved-Reasoners-Benefit-from-Model-Merging)
22. [CARFT: BoostingLLMReasoning via Contrastive Learning with Annotated Chain-of-Thought-based Reinforced Fine-Tuning](#CARFT-BoostingLLMReasoning-via-Contrastive-Learning-with-Annotated-Chain-of-Thought-based-Reinforced-Fine-Tuning)
23. [QualBench: BenchmarkingChineseLLMs with Localized Professional Qualifications for Vertical Domain Evaluation](#QualBench-BenchmarkingChineseLLMs-with-Localized-Professional-Qualifications-for-Vertical-Domain-Evaluation)
24. [VideoEraser: Concept Erasure in Text-to-Video Diffusion Models](#VideoEraser-Concept-Erasure-in-Text-to-Video-Diffusion-Models)
25. [Diagram-Driven Course Questions Generation](#Diagram-Driven-Course-Questions-Generation)
26. [ECC: An Emotion-Cause Conversation Dataset for Empathy Response](#ECC-An-Emotion-Cause-Conversation-Dataset-for-Empathy-Response)
27. [ThoughtProbe: Classifier-GuidedLLMThought Space Exploration via Probing Representations](#ThoughtProbe-Classifier-GuidedLLMThought-Space-Exploration-via-Probing-Representations)
28. [JOLT-SQL: Joint Loss Tuning of Text-to-SQLwith Confusion-aware Noisy Schema Sampling](#JOLT-SQL-Joint-Loss-Tuning-of-Text-to-SQLwith-Confusion-aware-Noisy-Schema-Sampling)
29. [DMDTEval: An Evaluation and Analysis ofLLMs on Disambiguation in Multi-domain Translation](#DMDTEval-An-Evaluation-and-Analysis-ofLLMs-on-Disambiguation-in-Multi-domain-Translation)
30. [SciRIFF: A Resource to Enhance Language Model Instruction-Following over Scientific Literature](#SciRIFF-A-Resource-to-Enhance-Language-Model-Instruction-Following-over-Scientific-Literature)

---


## APLOT: Robust Reward Modeling via Adaptive Preference Learning with Optimal Transport

### Images

![195bdba9ef5a68c800764cb900a1b1635e2aad8d9b4257f52fbf5f485a6bf832.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/images/195bdba9ef5a68c800764cb900a1b1635e2aad8d9b4257f52fbf5f485a6bf832.jpg)

![af07f35b02ef39ee769f7590c57455d8bee571e5e30ffa599f769cc37bbbb882.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/images/af07f35b02ef39ee769f7590c57455d8bee571e5e30ffa599f769cc37bbbb882.jpg)

![f32aa2e4b7ef71c5b3e53017ca68f4fcd88b19444f1d78d6042471d483eba8db.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/images/f32aa2e4b7ef71c5b3e53017ca68f4fcd88b19444f1d78d6042471d483eba8db.jpg)

### Tables

![02e3c8ba039710399475b38eaa6a291b9a86a3c502fb39d81bddd43cdf5c66a4.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/02e3c8ba039710399475b38eaa6a291b9a86a3c502fb39d81bddd43cdf5c66a4.jpg)

![07d929c7c7d25df6fe7d7239fb6ce54512472443cff0ee37317264da2b141f1a.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/07d929c7c7d25df6fe7d7239fb6ce54512472443cff0ee37317264da2b141f1a.jpg)

![0f610308d1c7fdc35d725fe39b9637f5c7e50280f3a76efd4346390b1dc2fd93.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/0f610308d1c7fdc35d725fe39b9637f5c7e50280f3a76efd4346390b1dc2fd93.jpg)

![23ce7baccf90ee6a41b16239a79396a98fca06b4ebe8a39d6cba1611bb2de82c.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/23ce7baccf90ee6a41b16239a79396a98fca06b4ebe8a39d6cba1611bb2de82c.jpg)

![3a85bfd3958e9504a4ed32d0f696c411d73c0487bdc2a849fdf09fa76b82eb49.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/3a85bfd3958e9504a4ed32d0f696c411d73c0487bdc2a849fdf09fa76b82eb49.jpg)

![3c9ba2caab88540df314fc2b73ef9b99e996cd862681a4424104ae90aadd8571.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/3c9ba2caab88540df314fc2b73ef9b99e996cd862681a4424104ae90aadd8571.jpg)

![3d47b27ac7eac19f79258df407a23920f351be2974cc194c0d6a28485446db6e.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/3d47b27ac7eac19f79258df407a23920f351be2974cc194c0d6a28485446db6e.jpg)

![41d4e7a9a9de8072e4db64ac6b83da793843d2663df893575ad41874abb6d04e.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/41d4e7a9a9de8072e4db64ac6b83da793843d2663df893575ad41874abb6d04e.jpg)

![45f1a98a89231466c2105e0833443a9034bd5d1829d88691c5f2c595d3091200.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/45f1a98a89231466c2105e0833443a9034bd5d1829d88691c5f2c595d3091200.jpg)

![6be6e5d044868c5107365cfbb5ac3e3e4dcd1cd9e902a46e0dd15c4619e1877b.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/6be6e5d044868c5107365cfbb5ac3e3e4dcd1cd9e902a46e0dd15c4619e1877b.jpg)

![70f214b5f1c9b7bcebe0ca5bd621e98ee59cb9ff9b6a1527b6be2c16991da5f4.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/70f214b5f1c9b7bcebe0ca5bd621e98ee59cb9ff9b6a1527b6be2c16991da5f4.jpg)

![77b859ef39675b6c582e54ff9ab95d8f4f2b210ecdba989639b218f80bb84bdf.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/77b859ef39675b6c582e54ff9ab95d8f4f2b210ecdba989639b218f80bb84bdf.jpg)

![7e29da3e8c915ed69e66d2d05d4a1e546373cd7349cb59582d2c6399d2f5056e.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/7e29da3e8c915ed69e66d2d05d4a1e546373cd7349cb59582d2c6399d2f5056e.jpg)

![81cce6bbc69eaf165ece2565c7247833f008d24bc3f16911e1f8d46cba5c3669.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/81cce6bbc69eaf165ece2565c7247833f008d24bc3f16911e1f8d46cba5c3669.jpg)

![8f9e3b226e830c273afe3bb3d94d16eec7aa68309cd38f89cab25cbbbbe443ab.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/8f9e3b226e830c273afe3bb3d94d16eec7aa68309cd38f89cab25cbbbbe443ab.jpg)

![afb2bbb935b23ab86c9db8c1f982173684739be589a2131108c481a80f9f5596.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/afb2bbb935b23ab86c9db8c1f982173684739be589a2131108c481a80f9f5596.jpg)

![b7a32dcb962cde2fdd935d7bbab851014224651c00b53b336ef7e93966ce3768.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/b7a32dcb962cde2fdd935d7bbab851014224651c00b53b336ef7e93966ce3768.jpg)

![bc34ca487c2828692eb998a4cda269726f638ced4e82f93d664e504d5a9ae9d5.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/bc34ca487c2828692eb998a4cda269726f638ced4e82f93d664e504d5a9ae9d5.jpg)

![c64572a59ad71491cd41fc2c729b53a95d5da1bc3bc5a81a6f1954695e3fb71a.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/c64572a59ad71491cd41fc2c729b53a95d5da1bc3bc5a81a6f1954695e3fb71a.jpg)

![c9e98b343675fc3a9e368c9142bfefd6907159df0013d748778ffcc3d3ed33d5.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/c9e98b343675fc3a9e368c9142bfefd6907159df0013d748778ffcc3d3ed33d5.jpg)

![d158fedcdc56e9a1fd50f4e9e236c0a860b50ae1333e110b3020947f7d8dab11.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/d158fedcdc56e9a1fd50f4e9e236c0a860b50ae1333e110b3020947f7d8dab11.jpg)

![d1ba38ab527497c0cba0044d1e8840536d678968ee2f15fd024bb51712f8414b.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/d1ba38ab527497c0cba0044d1e8840536d678968ee2f15fd024bb51712f8414b.jpg)

![de7a7f507002ddf8188a2c80a6a34f7b71bfcab32639f39b41aad03b67640ade.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/de7a7f507002ddf8188a2c80a6a34f7b71bfcab32639f39b41aad03b67640ade.jpg)

![e6293468e700e66502456a097cb8d38426b1e5b37fe7e9bbec2fcd34312f23f9.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/e6293468e700e66502456a097cb8d38426b1e5b37fe7e9bbec2fcd34312f23f9.jpg)

![f821ed94735fbf0ce4271ac476f9ddb3264fb7b0255ca577b076fb80600b6657.jpg](../emnlp_results/280_Text%20Meets%20Topology_%20Rethinking%20Out-of-distribution%20Detection%20in%20Text-Rich%20Networks/tables/f821ed94735fbf0ce4271ac476f9ddb3264fb7b0255ca577b076fb80600b6657.jpg)

## APLOT: Robust Reward Modeling via Adaptive Preference Learning with Optimal Transport


### Images

![06a9f848567da77d564aacc9277a19e9b974ccc207a459ce4cd42a6f24d1e5dd.jpg](../emnlp_results/281_APLOT_%20Robust%20Reward%20Modeling%20via%20Adaptive%20Preference%20Learning%20with%20Optimal%20Transport/images/06a9f848567da77d564aacc9277a19e9b974ccc207a459ce4cd42a6f24d1e5dd.jpg)

![17360ef71e0d70faa823720d5e04e6bd05d5553b2326bdb2fb81019967738487.jpg](../emnlp_results/281_APLOT_%20Robust%20Reward%20Modeling%20via%20Adaptive%20Preference%20Learning%20with%20Optimal%20Transport/images/17360ef71e0d70faa823720d5e04e6bd05d5553b2326bdb2fb81019967738487.jpg)

![a5632d27cbb8802d797f40c1d44aed5194659fdeb0bd1c23e4946b879361a0ca.jpg](../emnlp_results/281_APLOT_%20Robust%20Reward%20Modeling%20via%20Adaptive%20Preference%20Learning%20with%20Optimal%20Transport/images/a5632d27cbb8802d797f40c1d44aed5194659fdeb0bd1c23e4946b879361a0ca.jpg)

![b4336ca23f071eb58259f2a9ed7c074d80921b7760df49cb7c802b0513f52b8b.jpg](../emnlp_results/281_APLOT_%20Robust%20Reward%20Modeling%20via%20Adaptive%20Preference%20Learning%20with%20Optimal%20Transport/images/b4336ca23f071eb58259f2a9ed7c074d80921b7760df49cb7c802b0513f52b8b.jpg)

### Tables

![03053cc8377e334255a5da4a4a1e8416e24655a16d1ade99d28056977965590e.jpg](../emnlp_results/281_APLOT_%20Robust%20Reward%20Modeling%20via%20Adaptive%20Preference%20Learning%20with%20Optimal%20Transport/tables/03053cc8377e334255a5da4a4a1e8416e24655a16d1ade99d28056977965590e.jpg)

![2a2ec73079b35d1e4b3626d97c40a8ff53c06b5b5de008834438ac9e4bd87948.jpg](../emnlp_results/281_APLOT_%20Robust%20Reward%20Modeling%20via%20Adaptive%20Preference%20Learning%20with%20Optimal%20Transport/tables/2a2ec73079b35d1e4b3626d97c40a8ff53c06b5b5de008834438ac9e4bd87948.jpg)

![4691145011ca880ecb1466f53f394a009eb355c41de40d33b66879fe56e0d4af.jpg](../emnlp_results/281_APLOT_%20Robust%20Reward%20Modeling%20via%20Adaptive%20Preference%20Learning%20with%20Optimal%20Transport/tables/4691145011ca880ecb1466f53f394a009eb355c41de40d33b66879fe56e0d4af.jpg)

![790c46446005312441604da8281a737536e0a3992bcc122a922a665d71992034.jpg](../emnlp_results/281_APLOT_%20Robust%20Reward%20Modeling%20via%20Adaptive%20Preference%20Learning%20with%20Optimal%20Transport/tables/790c46446005312441604da8281a737536e0a3992bcc122a922a665d71992034.jpg)

![9cff4f1ef48179d66e4c795592a22e64db8d9b8195332e66e19433b34518ff97.jpg](../emnlp_results/281_APLOT_%20Robust%20Reward%20Modeling%20via%20Adaptive%20Preference%20Learning%20with%20Optimal%20Transport/tables/9cff4f1ef48179d66e4c795592a22e64db8d9b8195332e66e19433b34518ff97.jpg)

![a536df837cdb8f299159313aa6540b35ad182f293a734b7615e90c0e094da680.jpg](../emnlp_results/281_APLOT_%20Robust%20Reward%20Modeling%20via%20Adaptive%20Preference%20Learning%20with%20Optimal%20Transport/tables/a536df837cdb8f299159313aa6540b35ad182f293a734b7615e90c0e094da680.jpg)

![efd51155cc653b8cff68273f68f2521984e9141b6b2fd1e8957c43dd2e1c794d.jpg](../emnlp_results/281_APLOT_%20Robust%20Reward%20Modeling%20via%20Adaptive%20Preference%20Learning%20with%20Optimal%20Transport/tables/efd51155cc653b8cff68273f68f2521984e9141b6b2fd1e8957c43dd2e1c794d.jpg)

## HS-STaR: Hierarchical Sampling for Self-Taught Reasoners via Difficulty Estimation and Budget Reallocation


### Images

![00fd419124f88e05662270311aeef8482191bf5d8c3f725c18989bb61b25ce32.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/images/00fd419124f88e05662270311aeef8482191bf5d8c3f725c18989bb61b25ce32.jpg)

![1a6ea16fada053e236164f8bbe722641bc3f37fee596bbc3ac1234f51fefbe4c.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/images/1a6ea16fada053e236164f8bbe722641bc3f37fee596bbc3ac1234f51fefbe4c.jpg)

![6fc4999fa62d9f6a620a3f4a78449c0fe8fe894f364a6598dae5e39f180394aa.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/images/6fc4999fa62d9f6a620a3f4a78449c0fe8fe894f364a6598dae5e39f180394aa.jpg)

![94807062d54fae33e7b900dffab113610cd17c66523eba33db75cb1bfd419e83.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/images/94807062d54fae33e7b900dffab113610cd17c66523eba33db75cb1bfd419e83.jpg)

![c9bc7591426c9fc75dd1fb586fa8760536a8fe238cdc038cff8164df26e5fc42.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/images/c9bc7591426c9fc75dd1fb586fa8760536a8fe238cdc038cff8164df26e5fc42.jpg)

![e48361bc5be8e952bdc5aa88f5c924ee878e85fce854835d40f1f4fe10528f11.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/images/e48361bc5be8e952bdc5aa88f5c924ee878e85fce854835d40f1f4fe10528f11.jpg)

![ea264cc4573e76857571d303714a0e5670481abab605b5bdc2ccf9f3ed4238fd.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/images/ea264cc4573e76857571d303714a0e5670481abab605b5bdc2ccf9f3ed4238fd.jpg)

### Tables

![3ff4030fde2499abc698a9d2f2287b78709f51a00c0b6a9f80ff3f32adf51e2c.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/tables/3ff4030fde2499abc698a9d2f2287b78709f51a00c0b6a9f80ff3f32adf51e2c.jpg)

![8222ab05ac7925dd2fc1bbfe240ce9cf1d5e157ca0dc18bc4b0aa5e8e2d5ee33.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/tables/8222ab05ac7925dd2fc1bbfe240ce9cf1d5e157ca0dc18bc4b0aa5e8e2d5ee33.jpg)

![932919b645723e87f6e215d59d57fe62ff11031c8bb0dcb953dd43d6f3cfb5e7.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/tables/932919b645723e87f6e215d59d57fe62ff11031c8bb0dcb953dd43d6f3cfb5e7.jpg)

![94e4eb1522a339cea965fd672225bf4a434a0cc4bb92fc37d321115ec66e30fe.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/tables/94e4eb1522a339cea965fd672225bf4a434a0cc4bb92fc37d321115ec66e30fe.jpg)

![c9ce96d0ea57487e88a6a8440fcc8234296d5cd7fba6cde5e201eb34887525a3.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/tables/c9ce96d0ea57487e88a6a8440fcc8234296d5cd7fba6cde5e201eb34887525a3.jpg)

![de82253d7ef07aeb350f618d1797f15bed343150531002347402ba9f00ab3ac1.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/tables/de82253d7ef07aeb350f618d1797f15bed343150531002347402ba9f00ab3ac1.jpg)

![f3f3e79496cbba57c1b1055963f066c44961ce956990fb279858f7b283a360e6.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/tables/f3f3e79496cbba57c1b1055963f066c44961ce956990fb279858f7b283a360e6.jpg)

![f5197a0d450e2785718cc7af37732be8ccccd4c9bc2af5d0156c50ec51d75e5f.jpg](../emnlp_results/282_HS-STaR_%20Hierarchical%20Sampling%20for%20Self-Taught%20Reasoners%20via%20Difficulty%20Estimation%20and%20Budget%20Reallo/tables/f5197a0d450e2785718cc7af37732be8ccccd4c9bc2af5d0156c50ec51d75e5f.jpg)

## SEPS: A Separability Measure for Robust Unlearning inLLMs


### Images

![0966f600d92ba096613e5f0f81af1def333e664e8ae691170978643bdca65f39.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/0966f600d92ba096613e5f0f81af1def333e664e8ae691170978643bdca65f39.jpg)

![18f33352de510e6cb559566a76d0e95d0fc497cb94d39888210419096c349349.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/18f33352de510e6cb559566a76d0e95d0fc497cb94d39888210419096c349349.jpg)

![1b9a39b8a5c6459bf957fdc2fb50927a43a4e6ce0d0526479f3368a37b1f4346.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/1b9a39b8a5c6459bf957fdc2fb50927a43a4e6ce0d0526479f3368a37b1f4346.jpg)

![47a635c44d799fb7a9bd3656043d766eb3898728dbc00c17386b573de7021766.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/47a635c44d799fb7a9bd3656043d766eb3898728dbc00c17386b573de7021766.jpg)

![59ee6db8f70a3e6c297326594f6e7c6005448f16e202c4520b5ed1df27ad6ed0.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/59ee6db8f70a3e6c297326594f6e7c6005448f16e202c4520b5ed1df27ad6ed0.jpg)

![6213e5344415d6d4252b389e42c2356352b0080c5b355feac71a8463f661b814.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/6213e5344415d6d4252b389e42c2356352b0080c5b355feac71a8463f661b814.jpg)

![7aeceec80939390ed957c06cd1a07b7ed3584dc55b7a4b834d18842df4e4b3d0.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/7aeceec80939390ed957c06cd1a07b7ed3584dc55b7a4b834d18842df4e4b3d0.jpg)

![9b47d8a611610bab3e2011c24ea96db7637e1fb7c5a2cf2aae674a0650574e8c.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/9b47d8a611610bab3e2011c24ea96db7637e1fb7c5a2cf2aae674a0650574e8c.jpg)

![9e4711e9b0570f99d695e8c977c32b922497f817c01385c06d654718a237250e.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/9e4711e9b0570f99d695e8c977c32b922497f817c01385c06d654718a237250e.jpg)

![ae14dd3ad3ee90684c3ed923e6f469b93482e802c61a73ae16c4cb6d7f096d2a.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/ae14dd3ad3ee90684c3ed923e6f469b93482e802c61a73ae16c4cb6d7f096d2a.jpg)

![b47f51489bc3d56f26f8b6a4bb875b688646edc4c4e581b38480ee7ae7369be5.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/b47f51489bc3d56f26f8b6a4bb875b688646edc4c4e581b38480ee7ae7369be5.jpg)

![c4f9fac8a8bdb5c1fcb63748b519caaf4f5f5e523f7b76f54a376a7d012dcfa4.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/c4f9fac8a8bdb5c1fcb63748b519caaf4f5f5e523f7b76f54a376a7d012dcfa4.jpg)

![e48ea9a5427fff14c4df932eb7f35cb15e076a4626ee16aacb0045b0a62657ea.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/e48ea9a5427fff14c4df932eb7f35cb15e076a4626ee16aacb0045b0a62657ea.jpg)

![efc3525be18ebbdc83ca649f809c15f48ad19e5883875c4744dac6b30dc503e1.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/efc3525be18ebbdc83ca649f809c15f48ad19e5883875c4744dac6b30dc503e1.jpg)

![f8d1060f97f125e84c4fe0279365a097b679c89096f248bf806693e83a83ea9e.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/f8d1060f97f125e84c4fe0279365a097b679c89096f248bf806693e83a83ea9e.jpg)

![fb758d5acb29d15c3503ca4005e302770f71f4dfd023c5df41bcedc74325103e.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/fb758d5acb29d15c3503ca4005e302770f71f4dfd023c5df41bcedc74325103e.jpg)

![fdeff0c1edc1f39dc7a7e1e8d6c2f663f29e918fb713b31b3c03131acbad635b.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/fdeff0c1edc1f39dc7a7e1e8d6c2f663f29e918fb713b31b3c03131acbad635b.jpg)

![fff9588bb695ef9c175a1ee17c8dd21828d7ecda137b4aaa27c7ec37b527f657.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/images/fff9588bb695ef9c175a1ee17c8dd21828d7ecda137b4aaa27c7ec37b527f657.jpg)

### Tables

![0d347b541c943769b84999bc52580e954cc7c2f44d4f33ebb9d56befcaf547e5.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/0d347b541c943769b84999bc52580e954cc7c2f44d4f33ebb9d56befcaf547e5.jpg)

![233fec9890bee9040d3a5f772fb14090445bbcc92aef5f041682a7cc4d1b0114.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/233fec9890bee9040d3a5f772fb14090445bbcc92aef5f041682a7cc4d1b0114.jpg)

![25905e2e4996828fcd01f97631c8e616f6363411e855053ee71a89223f9ea630.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/25905e2e4996828fcd01f97631c8e616f6363411e855053ee71a89223f9ea630.jpg)

![45a05788105c41254561fa109d7171f8b99bb3ec321b9e616c29adb8b8f29bfa.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/45a05788105c41254561fa109d7171f8b99bb3ec321b9e616c29adb8b8f29bfa.jpg)

![52d3499eccbc3168e5efcad1978ed3a186be3e230ed0a2276888f5a0d9ce94cc.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/52d3499eccbc3168e5efcad1978ed3a186be3e230ed0a2276888f5a0d9ce94cc.jpg)

![58654cb5315eb5a35e49fb79be134597547df4c502d10e73c4dfae3f148e13fa.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/58654cb5315eb5a35e49fb79be134597547df4c502d10e73c4dfae3f148e13fa.jpg)

![73ddacfbe9f3ce3f8abeb432c29012584f3e4f2e8dc842ceb52e4618561623a0.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/73ddacfbe9f3ce3f8abeb432c29012584f3e4f2e8dc842ceb52e4618561623a0.jpg)

![990ad656efd4f0ef3d7fe21d391d86c0377d498b97c0b77daaa51d2953591713.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/990ad656efd4f0ef3d7fe21d391d86c0377d498b97c0b77daaa51d2953591713.jpg)

![a9c8d58272d97dcd5e0e7d2f6df59b8fa522082e77e87b9e42d058e2b223853b.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/a9c8d58272d97dcd5e0e7d2f6df59b8fa522082e77e87b9e42d058e2b223853b.jpg)

![baa6cbfd2fac8f24756dbee22771c80b121898bd7c1606b5f0d320c98be64d34.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/baa6cbfd2fac8f24756dbee22771c80b121898bd7c1606b5f0d320c98be64d34.jpg)

![cb9ae52f7ca9ec902b4d82b05f2cd1c094eaf23093615b9cb4634f9ea5ed89ff.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/cb9ae52f7ca9ec902b4d82b05f2cd1c094eaf23093615b9cb4634f9ea5ed89ff.jpg)

![cf121474dafd5111d651f142a389180765ddf809a3c77dad2fbd60e78d81c53c.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/cf121474dafd5111d651f142a389180765ddf809a3c77dad2fbd60e78d81c53c.jpg)

![d5c611d45d79f34874b767d381807db3a815f8dd32d6e8e0ac6fd9d16b092775.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/d5c611d45d79f34874b767d381807db3a815f8dd32d6e8e0ac6fd9d16b092775.jpg)

![e6045cc50723300e9d20fef1be1975594425d1d6c7a9539b39810d366961bfc3.jpg](../emnlp_results/283_SEPS_%20A%20Separability%20Measure%20for%20Robust%20Unlearning%20inLLMs/tables/e6045cc50723300e9d20fef1be1975594425d1d6c7a9539b39810d366961bfc3.jpg)

## TRUST-VL: An Explainable News Assistant for General Multimodal Misinformation Detection


### Images

![0c37a07c95998d720c4a7ed6e645005b8604f6fa38483e859936db46ba58f380.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/images/0c37a07c95998d720c4a7ed6e645005b8604f6fa38483e859936db46ba58f380.jpg)

![1041025a3be264cfe17bda75035353ebed42b580a2b885bf84c7e7ad37a8ea99.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/images/1041025a3be264cfe17bda75035353ebed42b580a2b885bf84c7e7ad37a8ea99.jpg)

![12d7078efb6287400a80d8a98f78aaa510ae653ed80442709623d9407c7fde91.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/images/12d7078efb6287400a80d8a98f78aaa510ae653ed80442709623d9407c7fde91.jpg)

![3d2507d0ad7d2ee93bc3033cc47dc06c46d2ae01f140e9782f17ca3dc0a2e46a.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/images/3d2507d0ad7d2ee93bc3033cc47dc06c46d2ae01f140e9782f17ca3dc0a2e46a.jpg)

![54176e2820fb14e75180dd2ef2dc6627561604358aff6ba63a006ca1a350314f.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/images/54176e2820fb14e75180dd2ef2dc6627561604358aff6ba63a006ca1a350314f.jpg)

![74818f354b3ee0aba3df921b6576b11d21a2d13e6d1437b9836c529529ac7ff1.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/images/74818f354b3ee0aba3df921b6576b11d21a2d13e6d1437b9836c529529ac7ff1.jpg)

![9fcab2ed40521f476c57be426ed4d1124dc7f3a27a9ba4372b9c1d3040bc5b25.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/images/9fcab2ed40521f476c57be426ed4d1124dc7f3a27a9ba4372b9c1d3040bc5b25.jpg)

![c85ab1eeae76c213a7f88446226fcd8f5999265c719f8af31c0926776abb4573.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/images/c85ab1eeae76c213a7f88446226fcd8f5999265c719f8af31c0926776abb4573.jpg)

![d1cf65e734b396c545170116108ff25f8848a27944c9e2efc288daa1351072d2.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/images/d1cf65e734b396c545170116108ff25f8848a27944c9e2efc288daa1351072d2.jpg)

![eb822c87745fac7ebc5a84e9b29cd6e5c9ab345ad0952d4cedc11ce1e1dff119.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/images/eb822c87745fac7ebc5a84e9b29cd6e5c9ab345ad0952d4cedc11ce1e1dff119.jpg)

![efec8c9adf69edc0f82000d22498d43505cb1516632085f8c8687befadd6c53e.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/images/efec8c9adf69edc0f82000d22498d43505cb1516632085f8c8687befadd6c53e.jpg)

### Tables

![1f2670eb9eece646e1d8e341e19ba8a67a48c6fc380744a887ef7edae9adb6be.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/tables/1f2670eb9eece646e1d8e341e19ba8a67a48c6fc380744a887ef7edae9adb6be.jpg)

![4d19e8dd40b051c928690b5fc93468a80f673e1663c5ef977d82c1e2ed79d084.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/tables/4d19e8dd40b051c928690b5fc93468a80f673e1663c5ef977d82c1e2ed79d084.jpg)

![939fe035fdb6b1e1fab8d8e159564ab77d051628c6679314447fe85786c73604.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/tables/939fe035fdb6b1e1fab8d8e159564ab77d051628c6679314447fe85786c73604.jpg)

![9ed67a2e514d05773306bcac00e4aefe12acb8c4fcd7c22aa7c1cac11c0fd3ca.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/tables/9ed67a2e514d05773306bcac00e4aefe12acb8c4fcd7c22aa7c1cac11c0fd3ca.jpg)

![cd2f9ad6b43cd6c80dbab41b085bdfb1c130a9cc12738763c2523b1925df3992.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/tables/cd2f9ad6b43cd6c80dbab41b085bdfb1c130a9cc12738763c2523b1925df3992.jpg)

![d0c8dc8abc8c58236b0f8d15b0ed008d2ab365ac460ac4049730bb14cda1813a.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/tables/d0c8dc8abc8c58236b0f8d15b0ed008d2ab365ac460ac4049730bb14cda1813a.jpg)

![ea22a1ea132c1d722b97492342882fac139fe83d7efb41c93725b9ac06c0cf4c.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/tables/ea22a1ea132c1d722b97492342882fac139fe83d7efb41c93725b9ac06c0cf4c.jpg)

![ef9ee431302d4127673e6eebe1ae00c72ccb3713574c5c47095515b8023ae5bc.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/tables/ef9ee431302d4127673e6eebe1ae00c72ccb3713574c5c47095515b8023ae5bc.jpg)

![f94e1c9b60ec6b191d8e0e6e4d42ad3fd4fbc8dd7ec2ab96a123c67fb244597e.jpg](../emnlp_results/284_TRUST-VL_%20An%20Explainable%20News%20Assistant%20for%20General%20Multimodal%20Misinformation%20Detection/tables/f94e1c9b60ec6b191d8e0e6e4d42ad3fd4fbc8dd7ec2ab96a123c67fb244597e.jpg)

## Tree-of-Quote Prompting Improves Factuality and Attribution in Multi-Hop and Medical Reasoning


### Images

![038ab689cd9884696b5f43f4606f6a7df0c2c43a17896c3b8a5e174153320e09.jpg](../emnlp_results/285_Tree-of-Quote%20Prompting%20Improves%20Factuality%20and%20Attribution%20in%20Multi-Hop%20and%20Medical%20Reasoning/images/038ab689cd9884696b5f43f4606f6a7df0c2c43a17896c3b8a5e174153320e09.jpg)

![083f1697295fb16f3de3cb6c5155df04f608ae93fe234efbd18b1852f13414e5.jpg](../emnlp_results/285_Tree-of-Quote%20Prompting%20Improves%20Factuality%20and%20Attribution%20in%20Multi-Hop%20and%20Medical%20Reasoning/images/083f1697295fb16f3de3cb6c5155df04f608ae93fe234efbd18b1852f13414e5.jpg)

![6f1a7c1d2c5d04bea1f84ac627980b21592bf49026a2571d6e104a0d10ff7cbb.jpg](../emnlp_results/285_Tree-of-Quote%20Prompting%20Improves%20Factuality%20and%20Attribution%20in%20Multi-Hop%20and%20Medical%20Reasoning/images/6f1a7c1d2c5d04bea1f84ac627980b21592bf49026a2571d6e104a0d10ff7cbb.jpg)

### Tables

![0fc6d95dae1112428315e238ac63a782baf3abea2e57e426b70685d05ecd42b8.jpg](../emnlp_results/285_Tree-of-Quote%20Prompting%20Improves%20Factuality%20and%20Attribution%20in%20Multi-Hop%20and%20Medical%20Reasoning/tables/0fc6d95dae1112428315e238ac63a782baf3abea2e57e426b70685d05ecd42b8.jpg)

![17096e265c00d73fb6c5b65631bdaf385c2a2b1172125080ff59c08b05a49461.jpg](../emnlp_results/285_Tree-of-Quote%20Prompting%20Improves%20Factuality%20and%20Attribution%20in%20Multi-Hop%20and%20Medical%20Reasoning/tables/17096e265c00d73fb6c5b65631bdaf385c2a2b1172125080ff59c08b05a49461.jpg)

![48cbb1052fa6f4f12169d90c6f844cf39da45bb2927781f974d1387a1e848ed0.jpg](../emnlp_results/285_Tree-of-Quote%20Prompting%20Improves%20Factuality%20and%20Attribution%20in%20Multi-Hop%20and%20Medical%20Reasoning/tables/48cbb1052fa6f4f12169d90c6f844cf39da45bb2927781f974d1387a1e848ed0.jpg)

![4e603809f6921fe0aeb97c5c54ed37c1427d27d4a2f929f00136635d06ad73a4.jpg](../emnlp_results/285_Tree-of-Quote%20Prompting%20Improves%20Factuality%20and%20Attribution%20in%20Multi-Hop%20and%20Medical%20Reasoning/tables/4e603809f6921fe0aeb97c5c54ed37c1427d27d4a2f929f00136635d06ad73a4.jpg)

![54460263648d3f1f575a2a50e134828cfdeb9d4f0eb663eec42b786a8aa9b1f9.jpg](../emnlp_results/285_Tree-of-Quote%20Prompting%20Improves%20Factuality%20and%20Attribution%20in%20Multi-Hop%20and%20Medical%20Reasoning/tables/54460263648d3f1f575a2a50e134828cfdeb9d4f0eb663eec42b786a8aa9b1f9.jpg)

![6f2a0a1e6fa940d8f446db71b9049e29e677d11a43f6bf7d411395a7b87c283e.jpg](../emnlp_results/285_Tree-of-Quote%20Prompting%20Improves%20Factuality%20and%20Attribution%20in%20Multi-Hop%20and%20Medical%20Reasoning/tables/6f2a0a1e6fa940d8f446db71b9049e29e677d11a43f6bf7d411395a7b87c283e.jpg)

![bd02e8ee28021110b6b857a75ff5d5e5021667edc9d41ad6f2fe2fb2aa989301.jpg](../emnlp_results/285_Tree-of-Quote%20Prompting%20Improves%20Factuality%20and%20Attribution%20in%20Multi-Hop%20and%20Medical%20Reasoning/tables/bd02e8ee28021110b6b857a75ff5d5e5021667edc9d41ad6f2fe2fb2aa989301.jpg)

![eac0cb929f44ab36936150226b3b66c10c82551dac1357d09f3f6474e82d6088.jpg](../emnlp_results/285_Tree-of-Quote%20Prompting%20Improves%20Factuality%20and%20Attribution%20in%20Multi-Hop%20and%20Medical%20Reasoning/tables/eac0cb929f44ab36936150226b3b66c10c82551dac1357d09f3f6474e82d6088.jpg)

## UnitCoder: Scalable Code Synthesis from Pre-training Corpora


### Images

![0aa49ac1918d44f7c1d94572d754bc497ac53a283f5a2e3f54057d887f25ef0d.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/images/0aa49ac1918d44f7c1d94572d754bc497ac53a283f5a2e3f54057d887f25ef0d.jpg)

![6e39085a08fe16806881863af4313a24cec81bff8df9d569d4e8e19f5186556b.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/images/6e39085a08fe16806881863af4313a24cec81bff8df9d569d4e8e19f5186556b.jpg)

![b917e04b1a61b8264c5f0a82c887ce5c6b01abbfffe315595f07b7644559131c.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/images/b917e04b1a61b8264c5f0a82c887ce5c6b01abbfffe315595f07b7644559131c.jpg)

### Tables

![0b1e055ac0b0c71a3a3ead9d96a6ff64f7aa63292a1745d560ce62b1450fa026.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/tables/0b1e055ac0b0c71a3a3ead9d96a6ff64f7aa63292a1745d560ce62b1450fa026.jpg)

![0f8cec2b6c384b1ff3330ae1f62736e63153039886e727ecd1cb741d9847e3ea.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/tables/0f8cec2b6c384b1ff3330ae1f62736e63153039886e727ecd1cb741d9847e3ea.jpg)

![2540fafaf7857b4b558e211cf26c7932dc85559b3d5009f91b953432d0cb1ec2.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/tables/2540fafaf7857b4b558e211cf26c7932dc85559b3d5009f91b953432d0cb1ec2.jpg)

![40b1f3f76eb616759146a5c3fc13f24524a3a715f6f07ab97cb5521132e35160.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/tables/40b1f3f76eb616759146a5c3fc13f24524a3a715f6f07ab97cb5521132e35160.jpg)

![47bfb79a9203e27189c324139cb602c3588daad022406ea0a74dffaad9841ce1.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/tables/47bfb79a9203e27189c324139cb602c3588daad022406ea0a74dffaad9841ce1.jpg)

![4b4642e544b597ea1af97caf1c1dfbfcc2f429a8515a89efeb5b4bf3d8ed4ab9.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/tables/4b4642e544b597ea1af97caf1c1dfbfcc2f429a8515a89efeb5b4bf3d8ed4ab9.jpg)

![6ca103128111595f1203bf326f26b7b919393515d7081ac821c4c10a64fbd495.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/tables/6ca103128111595f1203bf326f26b7b919393515d7081ac821c4c10a64fbd495.jpg)

![704cb974eb16ca4e902e5d989436aae054aeeba24e4364ac1af147fb198558fb.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/tables/704cb974eb16ca4e902e5d989436aae054aeeba24e4364ac1af147fb198558fb.jpg)

![a296ba0a8dcf39ab48141bae92772489ae4cb46828ba5032682ffda1adba7e3b.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/tables/a296ba0a8dcf39ab48141bae92772489ae4cb46828ba5032682ffda1adba7e3b.jpg)

![bbfbb16e7326ba1f0b88fa13f539cd3d5e0fc2d0725d6092cbac5fd45aad8547.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/tables/bbfbb16e7326ba1f0b88fa13f539cd3d5e0fc2d0725d6092cbac5fd45aad8547.jpg)

![dfc777f2955e3422422b3465db49a6b77beaa7a987fae59def92eb5e710afa8e.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/tables/dfc777f2955e3422422b3465db49a6b77beaa7a987fae59def92eb5e710afa8e.jpg)

![f61965eaf980afef17b32ad614aeb2b46a5128649aff4056d000f81114e89ea6.jpg](../emnlp_results/286_UnitCoder_%20Scalable%20Code%20Synthesis%20from%20Pre-training%20Corpora/tables/f61965eaf980afef17b32ad614aeb2b46a5128649aff4056d000f81114e89ea6.jpg)

## GRPO-LEAD: A Difficulty-Aware Reinforcement Learning Approach for Concise Mathematical Reasoning in Language Models


### Images

![07315055e940b41d2825346857142ba030edf73dc92b595bfbd5ebad290356c6.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/07315055e940b41d2825346857142ba030edf73dc92b595bfbd5ebad290356c6.jpg)

![1f31ad751e655431160aeac3213845a561766851b0f4d63792c509d38a315a66.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/1f31ad751e655431160aeac3213845a561766851b0f4d63792c509d38a315a66.jpg)

![2e567a0a2af8eaf99021c82f7c950aa6b5b470d6a7e57dbbf9cbc74ccf6724bc.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/2e567a0a2af8eaf99021c82f7c950aa6b5b470d6a7e57dbbf9cbc74ccf6724bc.jpg)

![2f5080e37fbd11a8e69cd2963cff631af1a869da77da8cf9f498fae7708fd268.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/2f5080e37fbd11a8e69cd2963cff631af1a869da77da8cf9f498fae7708fd268.jpg)

![4771cf6162a9fa542f70330abe1eabe5e0ef115f33f21ece13402f8ebc1a8e38.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/4771cf6162a9fa542f70330abe1eabe5e0ef115f33f21ece13402f8ebc1a8e38.jpg)

![5115c9e1e3aa37f4392fe36c6c93609ea0b28f32a40f4bd2e1280decb6009d28.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/5115c9e1e3aa37f4392fe36c6c93609ea0b28f32a40f4bd2e1280decb6009d28.jpg)

![5abc183d1f470299dcb8ca8a8ee35ada0829fc05754f28a4565270a389ece111.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/5abc183d1f470299dcb8ca8a8ee35ada0829fc05754f28a4565270a389ece111.jpg)

![6b5b7774d2c6150b070a0219120fa463d40f963a61de6c194abefe48b4669dde.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/6b5b7774d2c6150b070a0219120fa463d40f963a61de6c194abefe48b4669dde.jpg)

![720c71a228978ea93f6d5ada1499fe04c204978a531f036d9472d7e5a26261f8.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/720c71a228978ea93f6d5ada1499fe04c204978a531f036d9472d7e5a26261f8.jpg)

![729cb2b3b6c95cd2415c569c812f28dcfa99b87175d7efc778d2d06e160e510b.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/729cb2b3b6c95cd2415c569c812f28dcfa99b87175d7efc778d2d06e160e510b.jpg)

![8d82fb5565dd1b2a9cc52e4ca8c42c2f7c4cd8ef77269be6906e93578d52e325.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/8d82fb5565dd1b2a9cc52e4ca8c42c2f7c4cd8ef77269be6906e93578d52e325.jpg)

![a877ab692f3e16cf40e925884ad92e2f3be2a04839a0374f88853a6a9aa86b76.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/a877ab692f3e16cf40e925884ad92e2f3be2a04839a0374f88853a6a9aa86b76.jpg)

![c16cd07854b1e986f0f4b2cfe0984ee2fca8138409c48f4eba8036fb4038919b.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/c16cd07854b1e986f0f4b2cfe0984ee2fca8138409c48f4eba8036fb4038919b.jpg)

![c365dd9a609b41cc350d663fd17d11e4fb2e7d67dc7c91a73a55117d51a527dc.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/c365dd9a609b41cc350d663fd17d11e4fb2e7d67dc7c91a73a55117d51a527dc.jpg)

![ce77baf8e6d1085fd0f1a671a6f7fec56941f36b698a13ff689bae1a919ebe2f.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/ce77baf8e6d1085fd0f1a671a6f7fec56941f36b698a13ff689bae1a919ebe2f.jpg)

![e360306c5787ee2ce3cf5338beef00dad879703bf7bf17d233c306b54cc50b85.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/e360306c5787ee2ce3cf5338beef00dad879703bf7bf17d233c306b54cc50b85.jpg)

![f7d0c1ee164334b9a3d3909c12bbfedbd60686be2845ca4673a3f6896bd95b8f.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/images/f7d0c1ee164334b9a3d3909c12bbfedbd60686be2845ca4673a3f6896bd95b8f.jpg)

### Tables

![35ed6629b03208905ac77a2da7b11f946365a1b3fd263047fa6f48a1b74d41ce.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/tables/35ed6629b03208905ac77a2da7b11f946365a1b3fd263047fa6f48a1b74d41ce.jpg)

![665f8ab9a995d89247a19d4cf2658a3a48872165527e6d51750b462f1f615502.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/tables/665f8ab9a995d89247a19d4cf2658a3a48872165527e6d51750b462f1f615502.jpg)

![9f25c8fddcdf1e9f0e1e1fcfbf3bacce04a4d992b79fe437006c6c1b050f1e5f.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/tables/9f25c8fddcdf1e9f0e1e1fcfbf3bacce04a4d992b79fe437006c6c1b050f1e5f.jpg)

![b92fbc872ff73d4fcaea1a6294311718e670f8f0d3ec75a0918297fe49e149bf.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/tables/b92fbc872ff73d4fcaea1a6294311718e670f8f0d3ec75a0918297fe49e149bf.jpg)

![de4a176367bd96af64b64156f58b47c701b04c7043b396f3880842d0310f9f72.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/tables/de4a176367bd96af64b64156f58b47c701b04c7043b396f3880842d0310f9f72.jpg)

![f5e0139cff9645ec742acef0457cd53c02074c120dd677bff056f703f20c3a76.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/tables/f5e0139cff9645ec742acef0457cd53c02074c120dd677bff056f703f20c3a76.jpg)

![f8f2d82c8f32d5929feb1ec59879c2313c4e83174ab0f769e1f418825bb3b16f.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/tables/f8f2d82c8f32d5929feb1ec59879c2313c4e83174ab0f769e1f418825bb3b16f.jpg)

![f93a389ccef432401996a4ed67d8829d2ebcb709b2ac7bc246f341b4b5103a56.jpg](../emnlp_results/287_GRPO-LEAD_%20A%20Difficulty-Aware%20Reinforcement%20Learning%20Approach%20for%20Concise%20Mathematical%20Reasoning%20in%20/tables/f93a389ccef432401996a4ed67d8829d2ebcb709b2ac7bc246f341b4b5103a56.jpg)

## Improving Low-Resource Sequence Labeling with Knowledge Fusion and Contextual Label Explanations


### Images

![2c3d9565b1a00377b1a2d55baecb4eeb37c77be8abea9163857ca0580b138d7b.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/images/2c3d9565b1a00377b1a2d55baecb4eeb37c77be8abea9163857ca0580b138d7b.jpg)

![37df2b044adc06b9d24c68273d180b2368c8c3f96d0f982638fb649c3f8379e9.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/images/37df2b044adc06b9d24c68273d180b2368c8c3f96d0f982638fb649c3f8379e9.jpg)

![600651ea1f12dd3d19014df2bc148291c0c5135665745fe14a8c7ab9b3cf1511.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/images/600651ea1f12dd3d19014df2bc148291c0c5135665745fe14a8c7ab9b3cf1511.jpg)

![66b29deaeb3870409a01f89a1e455d320972d77f1f03ec671322f5560f6013c3.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/images/66b29deaeb3870409a01f89a1e455d320972d77f1f03ec671322f5560f6013c3.jpg)

![81c817eb879f43c90057368be3d5fb982f8f7b89a2f2ff5d8c6ba8a8ea56387e.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/images/81c817eb879f43c90057368be3d5fb982f8f7b89a2f2ff5d8c6ba8a8ea56387e.jpg)

![b087b36b606ac1736aff6e84073e8da160e3f2d1c914c033148e0a9c9d13b2d0.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/images/b087b36b606ac1736aff6e84073e8da160e3f2d1c914c033148e0a9c9d13b2d0.jpg)

![c346172d819b75b815bb017cb3e3857b7a95af4a8636154800e0aebc0e408f76.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/images/c346172d819b75b815bb017cb3e3857b7a95af4a8636154800e0aebc0e408f76.jpg)

![d72cc056471ac8e4bfb4ea8b5714a3ddbdc42b38a3f1112e7f8f7687e6f6f8bf.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/images/d72cc056471ac8e4bfb4ea8b5714a3ddbdc42b38a3f1112e7f8f7687e6f6f8bf.jpg)

### Tables

![0c0d9aeb80fc2bc68e091aa2b84797a7f5c69e71f1c4ef483827fe971dd84428.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/tables/0c0d9aeb80fc2bc68e091aa2b84797a7f5c69e71f1c4ef483827fe971dd84428.jpg)

![0e301d2d8c8981c7c452f3aa47d9e9b8cbac5ff54ab7de9a4f56a31c2e4dd199.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/tables/0e301d2d8c8981c7c452f3aa47d9e9b8cbac5ff54ab7de9a4f56a31c2e4dd199.jpg)

![5e5f5d40aeef3decd436dbb227ea37a3579a01aabcd4b499e8470fbdf447a9db.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/tables/5e5f5d40aeef3decd436dbb227ea37a3579a01aabcd4b499e8470fbdf447a9db.jpg)

![70d8bec4b4a02c9d352c7cbf0f1d1d4a6bc502838e38cbb0ebdabd117d73fc61.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/tables/70d8bec4b4a02c9d352c7cbf0f1d1d4a6bc502838e38cbb0ebdabd117d73fc61.jpg)

![a1d052b45d3f025100a65aa3ca586766a1a9dba26ab72d8909d61ab881912867.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/tables/a1d052b45d3f025100a65aa3ca586766a1a9dba26ab72d8909d61ab881912867.jpg)

![a4e83e48eef5e0f10cfc1cd6d70743e2b523fef3f517debab31acb9345fa6d68.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/tables/a4e83e48eef5e0f10cfc1cd6d70743e2b523fef3f517debab31acb9345fa6d68.jpg)

![b900ee5ef9688e7890f7204877cef3b0d41fd8f2829786a343f8c2e6c2856481.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/tables/b900ee5ef9688e7890f7204877cef3b0d41fd8f2829786a343f8c2e6c2856481.jpg)

![c6d0a5e4f6a9f0d0384cde17dc7b4dcb973a6588c3572b880be978f668bbf487.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/tables/c6d0a5e4f6a9f0d0384cde17dc7b4dcb973a6588c3572b880be978f668bbf487.jpg)

![d479382b62864e7d1016c047047b76fa72b31172a0958da9b34692b405c5d2a3.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/tables/d479382b62864e7d1016c047047b76fa72b31172a0958da9b34692b405c5d2a3.jpg)

![ec49d4de55388b35cf5de9eb52b34ca5d25465ee47ba1fa817103542fe051960.jpg](../emnlp_results/288_Improving%20Low-Resource%20Sequence%20Labeling%20with%20Knowledge%20Fusion%20and%20Contextual%20Label%20Explanations/tables/ec49d4de55388b35cf5de9eb52b34ca5d25465ee47ba1fa817103542fe051960.jpg)

## Rethinking Cross-Subject Data Splitting for Brain-to-Text Decoding


### Images

![0923732f7ab1e10416d3787c1b4a8bbc9e331876f7d96f291590083f913b5bf3.jpg](../emnlp_results/289_Rethinking%20Cross-Subject%20Data%20Splitting%20for%20Brain-to-Text%20Decoding/images/0923732f7ab1e10416d3787c1b4a8bbc9e331876f7d96f291590083f913b5bf3.jpg)

![149cd365c2425783b778c32b726aad3984a6473d70c69b6f4eeecb461392b242.jpg](../emnlp_results/289_Rethinking%20Cross-Subject%20Data%20Splitting%20for%20Brain-to-Text%20Decoding/images/149cd365c2425783b778c32b726aad3984a6473d70c69b6f4eeecb461392b242.jpg)

![543a3fedea5e08a4544f0bd0ddcade0bf573b4728327597ef3fad6940534ff81.jpg](../emnlp_results/289_Rethinking%20Cross-Subject%20Data%20Splitting%20for%20Brain-to-Text%20Decoding/images/543a3fedea5e08a4544f0bd0ddcade0bf573b4728327597ef3fad6940534ff81.jpg)

![99c07af887d9579c773f1148a106e718fd3ad37c66b1d92fcb736b0c0923b2c5.jpg](../emnlp_results/289_Rethinking%20Cross-Subject%20Data%20Splitting%20for%20Brain-to-Text%20Decoding/images/99c07af887d9579c773f1148a106e718fd3ad37c66b1d92fcb736b0c0923b2c5.jpg)

![b3d6d6c7cb0467e89741339035197e50b3877054276f6dfde4096179375d11f1.jpg](../emnlp_results/289_Rethinking%20Cross-Subject%20Data%20Splitting%20for%20Brain-to-Text%20Decoding/images/b3d6d6c7cb0467e89741339035197e50b3877054276f6dfde4096179375d11f1.jpg)

### Tables

![4db2731ba4b7eb6cce754ce823fe153f1046e474de9afcd31f640b8949a3fd7c.jpg](../emnlp_results/289_Rethinking%20Cross-Subject%20Data%20Splitting%20for%20Brain-to-Text%20Decoding/tables/4db2731ba4b7eb6cce754ce823fe153f1046e474de9afcd31f640b8949a3fd7c.jpg)

![5ab69e8eb2349ada5ec46d1c6bf0146a90e1d277bd9f25a74cdf877c7d1eb244.jpg](../emnlp_results/289_Rethinking%20Cross-Subject%20Data%20Splitting%20for%20Brain-to-Text%20Decoding/tables/5ab69e8eb2349ada5ec46d1c6bf0146a90e1d277bd9f25a74cdf877c7d1eb244.jpg)

![68df99886c9f1d8aa8c7d3ac678e771961fcf9f6930186c2ab37865ac7fb5100.jpg](../emnlp_results/289_Rethinking%20Cross-Subject%20Data%20Splitting%20for%20Brain-to-Text%20Decoding/tables/68df99886c9f1d8aa8c7d3ac678e771961fcf9f6930186c2ab37865ac7fb5100.jpg)

![696cc075520fd76a91845c4e53e6cd84279a362b650a2d855964c9e6d7a5f290.jpg](../emnlp_results/289_Rethinking%20Cross-Subject%20Data%20Splitting%20for%20Brain-to-Text%20Decoding/tables/696cc075520fd76a91845c4e53e6cd84279a362b650a2d855964c9e6d7a5f290.jpg)

![7ebe45369659cc5de27bdb196a39a4a3f3b8d118f138d65a3389343dd91990fa.jpg](../emnlp_results/289_Rethinking%20Cross-Subject%20Data%20Splitting%20for%20Brain-to-Text%20Decoding/tables/7ebe45369659cc5de27bdb196a39a4a3f3b8d118f138d65a3389343dd91990fa.jpg)

![b59329f1fe50f028048389e77262c5530893d70a8622f2c3f9f3be8290c97449.jpg](../emnlp_results/289_Rethinking%20Cross-Subject%20Data%20Splitting%20for%20Brain-to-Text%20Decoding/tables/b59329f1fe50f028048389e77262c5530893d70a8622f2c3f9f3be8290c97449.jpg)

![bf2d833a4c732c0db87383a3e9aae6ebd82056b11fb5d951ae2fb927744241b9.jpg](../emnlp_results/289_Rethinking%20Cross-Subject%20Data%20Splitting%20for%20Brain-to-Text%20Decoding/tables/bf2d833a4c732c0db87383a3e9aae6ebd82056b11fb5d951ae2fb927744241b9.jpg)

![d6e90ea8c770602daad99e50d2eb034fb29e8177819f19c35b6813b890d4e78d.jpg](../emnlp_results/289_Rethinking%20Cross-Subject%20Data%20Splitting%20for%20Brain-to-Text%20Decoding/tables/d6e90ea8c770602daad99e50d2eb034fb29e8177819f19c35b6813b890d4e78d.jpg)

## RCScore: Quantifying Response Consistency in Large Language Models


### Images

![1f79d561e474f3de35222b18b97c5b27408f513f4ec487e083133f61c0221e79.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/images/1f79d561e474f3de35222b18b97c5b27408f513f4ec487e083133f61c0221e79.jpg)

![6f29d04e7be54acbf17f9972088cf7c84219325f683c11a4b40a8a043967912e.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/images/6f29d04e7be54acbf17f9972088cf7c84219325f683c11a4b40a8a043967912e.jpg)

![7c96a9f5ee5fe6542919461ea740b47388b867adbe9f014b8708aa1eeb345537.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/images/7c96a9f5ee5fe6542919461ea740b47388b867adbe9f014b8708aa1eeb345537.jpg)

![a62572e21654ed041c68b83cd877fa88b085d5516036c7fbf5221553d37cee6e.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/images/a62572e21654ed041c68b83cd877fa88b085d5516036c7fbf5221553d37cee6e.jpg)

![b0428bf50ba6f25e5010a3d1e3ce522a28141d70575f91a1904ce83bf6c32cd1.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/images/b0428bf50ba6f25e5010a3d1e3ce522a28141d70575f91a1904ce83bf6c32cd1.jpg)

![ba307f0cebacc8aca75e395b741627ad2d6a22c29db5f4b0974a80ce884f84bb.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/images/ba307f0cebacc8aca75e395b741627ad2d6a22c29db5f4b0974a80ce884f84bb.jpg)

![f141b00bda2705f6e4628d0c697fc4813cbe7509d6cc427884616c347f54163e.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/images/f141b00bda2705f6e4628d0c697fc4813cbe7509d6cc427884616c347f54163e.jpg)

### Tables

![0a5f9defd8e04b57f6eb39190aedc3423c7fe380aab5f295cee7f9fcdd2f0af3.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/tables/0a5f9defd8e04b57f6eb39190aedc3423c7fe380aab5f295cee7f9fcdd2f0af3.jpg)

![44f33476d772326012c5e2d5b1057ecfd70676973a9863d45c10cf43fd1b8fe7.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/tables/44f33476d772326012c5e2d5b1057ecfd70676973a9863d45c10cf43fd1b8fe7.jpg)

![5d5780b7453c133431eb469ad2d8cc523c3b069072e9fded4e0ba313371ed2e4.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/tables/5d5780b7453c133431eb469ad2d8cc523c3b069072e9fded4e0ba313371ed2e4.jpg)

![60fab8dafb8049ea220fe414210f4c5872f924f946edbf39036e47eacbd2a651.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/tables/60fab8dafb8049ea220fe414210f4c5872f924f946edbf39036e47eacbd2a651.jpg)

![63262701bd3a40c84ea028ba5db4cb57d3f1a1b67f60f8de8a19c0bc03789d25.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/tables/63262701bd3a40c84ea028ba5db4cb57d3f1a1b67f60f8de8a19c0bc03789d25.jpg)

![63b147d1a3807b813c2bc905010a35187c35b9f8cc47c1ce51e6df8b11e86f69.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/tables/63b147d1a3807b813c2bc905010a35187c35b9f8cc47c1ce51e6df8b11e86f69.jpg)

![692b885a7a7ba6eaa74976f122e8d99f3f3062cab9308d2ead1bd2767265998a.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/tables/692b885a7a7ba6eaa74976f122e8d99f3f3062cab9308d2ead1bd2767265998a.jpg)

![694b749143ca74afa1cf5e810f304146c0757114afb6f1c179f9d8b543f40ecb.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/tables/694b749143ca74afa1cf5e810f304146c0757114afb6f1c179f9d8b543f40ecb.jpg)

![8d0ae4dfcdba1b01f7f938924cac52e343efe1df8d62c1748a5cf37664e25d10.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/tables/8d0ae4dfcdba1b01f7f938924cac52e343efe1df8d62c1748a5cf37664e25d10.jpg)

![9dd555be64f147930a4a8eecb6c59c99637b9c711df200efa14b68e36dc663ee.jpg](../emnlp_results/290_RCScore_%20Quantifying%20Response%20Consistency%20in%20Large%20Language%20Models/tables/9dd555be64f147930a4a8eecb6c59c99637b9c711df200efa14b68e36dc663ee.jpg)

## A Multi-Agent Framework with Automated Decision Rule Optimization for Cross-Domain Misinformation Detection


### Images

![0e4e8ad90823a07d6d712fd5c9401d5404702660c33af80b04e9055a1d75376c.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/images/0e4e8ad90823a07d6d712fd5c9401d5404702660c33af80b04e9055a1d75376c.jpg)

![4428e13e193028974cae6bd785f09f292eb03c8658069867e00de37e49bdb322.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/images/4428e13e193028974cae6bd785f09f292eb03c8658069867e00de37e49bdb322.jpg)

![ad6322c7afd4b448c1d0d0c61fac2eabac436edd3d643b11304d4df62d745568.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/images/ad6322c7afd4b448c1d0d0c61fac2eabac436edd3d643b11304d4df62d745568.jpg)

![b4d0e5d9ac194072373fe89fe9ddb7db02bacbbc4f56daa3b5bfc824a35a9eee.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/images/b4d0e5d9ac194072373fe89fe9ddb7db02bacbbc4f56daa3b5bfc824a35a9eee.jpg)

![bbc8868da928285a824a1d3db2a8ff54c4b582b3d7ead9cd9f97cddfe0843723.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/images/bbc8868da928285a824a1d3db2a8ff54c4b582b3d7ead9cd9f97cddfe0843723.jpg)

![e603798796f12c889e242751bbab65e7c18c388958f5121d9e9bb3aeee15e8ba.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/images/e603798796f12c889e242751bbab65e7c18c388958f5121d9e9bb3aeee15e8ba.jpg)

![ff54929424f54de62e648edec88fc71488d531b0690033eb9bb6320cd8b35dfd.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/images/ff54929424f54de62e648edec88fc71488d531b0690033eb9bb6320cd8b35dfd.jpg)

### Tables

![092373dad217164761f0ab28d22bda5f2782cbc6d453e7410cfd25c224a5ad55.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/092373dad217164761f0ab28d22bda5f2782cbc6d453e7410cfd25c224a5ad55.jpg)

![1669a9c7d973c9a061af97090849615affa3c34e8ab5c02a5ac1d3cb88e7cbe9.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/1669a9c7d973c9a061af97090849615affa3c34e8ab5c02a5ac1d3cb88e7cbe9.jpg)

![1b1d7c17437c5011953e4f35b84902aadf4a46236a07b7f69e7d488835494735.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/1b1d7c17437c5011953e4f35b84902aadf4a46236a07b7f69e7d488835494735.jpg)

![2de5fa236a0fcf848bf5bd68c4c8d67c7d88764f6636e2fc297faf6be83a17b6.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/2de5fa236a0fcf848bf5bd68c4c8d67c7d88764f6636e2fc297faf6be83a17b6.jpg)

![36265ac19d22c388b49cc2f5d02506ae49ca5bccb04f9581650c4cb4438bfbac.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/36265ac19d22c388b49cc2f5d02506ae49ca5bccb04f9581650c4cb4438bfbac.jpg)

![37490076b6605a039942a51eee465df00787569a6fbae6b984345c9c542ea304.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/37490076b6605a039942a51eee465df00787569a6fbae6b984345c9c542ea304.jpg)

![53741fd3025f996f1036351718ef637994bdb1e89b54919e122797fc8a89f1c3.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/53741fd3025f996f1036351718ef637994bdb1e89b54919e122797fc8a89f1c3.jpg)

![5b0aeb14c380ac7c09ceca4d16cec944a5c1f392d69ed46cb99e0be293a20b50.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/5b0aeb14c380ac7c09ceca4d16cec944a5c1f392d69ed46cb99e0be293a20b50.jpg)

![6f6f073bb95de1481df029149f1870cd646d8648c4d992e61c746c919618f675.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/6f6f073bb95de1481df029149f1870cd646d8648c4d992e61c746c919618f675.jpg)

![71af3a2e7fd2dc7245b1979be6f76b6eadd81fb3c98d9ba8dc995dca30e0fefc.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/71af3a2e7fd2dc7245b1979be6f76b6eadd81fb3c98d9ba8dc995dca30e0fefc.jpg)

![726be6292519721bee7faec4f59d3c3ff1a17468fdde4a2a6cb9ee60aa9d596c.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/726be6292519721bee7faec4f59d3c3ff1a17468fdde4a2a6cb9ee60aa9d596c.jpg)

![7d094cbdf04848513843eae762e1e9795d02539d0d38530cdce47c086fa17000.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/7d094cbdf04848513843eae762e1e9795d02539d0d38530cdce47c086fa17000.jpg)

![852aa18673eaaf6feb7a9e429d1906fe873d7169ad248b9618442b22fb3830a6.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/852aa18673eaaf6feb7a9e429d1906fe873d7169ad248b9618442b22fb3830a6.jpg)

![a218ba347a067fbdf1ab7be38d51a23fe67512af55326b47f6c9974464423df8.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/a218ba347a067fbdf1ab7be38d51a23fe67512af55326b47f6c9974464423df8.jpg)

![ac47ca2702ddea93fd2da948ad5279b541cb853746140f22b293d5a9ad355f8e.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/ac47ca2702ddea93fd2da948ad5279b541cb853746140f22b293d5a9ad355f8e.jpg)

![c0314e2fefc0391ec74fd552a8e1512d2d721e0cab16f1640918b5a70e5d19fd.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/c0314e2fefc0391ec74fd552a8e1512d2d721e0cab16f1640918b5a70e5d19fd.jpg)

![c6e7440301d75fe0e65830c149297121c809a030e5669249b4d65f457f231acf.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/c6e7440301d75fe0e65830c149297121c809a030e5669249b4d65f457f231acf.jpg)

![e48b46920a4289b8658606c9983a99178dc2829ef24cb3bbdeee3b71225a891e.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/e48b46920a4289b8658606c9983a99178dc2829ef24cb3bbdeee3b71225a891e.jpg)

![eec04ec1ef8618bafddb949d4aff38b3b41fbf7ee239ca33392c6fbb452a49eb.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/eec04ec1ef8618bafddb949d4aff38b3b41fbf7ee239ca33392c6fbb452a49eb.jpg)

![f2fe49ccf85703a86fcd012b012a885694b9daeffc317f62ae460a1266166729.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/f2fe49ccf85703a86fcd012b012a885694b9daeffc317f62ae460a1266166729.jpg)

![f44e5deec88e14acfa66f2c9101a626df93c8d6f4599aafff168df4d3e22d5c7.jpg](../emnlp_results/291_A%20Multi-Agent%20Framework%20with%20Automated%20Decision%20Rule%20Optimization%20for%20Cross-Domain%20Misinformation%20De/tables/f44e5deec88e14acfa66f2c9101a626df93c8d6f4599aafff168df4d3e22d5c7.jpg)

## OmniEval: An Omnidirectional and AutomaticRAGEvaluation Benchmark in Financial Domain


### Images

![0aaff96efc2299182f18865c5a1d1c185bbfe460e970cd7d760d67beb662b2b6.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/0aaff96efc2299182f18865c5a1d1c185bbfe460e970cd7d760d67beb662b2b6.jpg)

![14d1ea9219733792db7f1f62ff0af42690c24457f5131e10ed3b105b2ae15ea2.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/14d1ea9219733792db7f1f62ff0af42690c24457f5131e10ed3b105b2ae15ea2.jpg)

![1eb9884e014ca31fd6b947fc0a2e02462a602e910e150f9825a29bb3764d9669.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/1eb9884e014ca31fd6b947fc0a2e02462a602e910e150f9825a29bb3764d9669.jpg)

![276507072ce07d09d75ef68af6de8335590871aa4186f1990890eb257d37709d.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/276507072ce07d09d75ef68af6de8335590871aa4186f1990890eb257d37709d.jpg)

![279dfbd3b0c5395f75e87a0cce2e3060c5f24d38386956f3261291f7e7bf8160.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/279dfbd3b0c5395f75e87a0cce2e3060c5f24d38386956f3261291f7e7bf8160.jpg)

![37d5c8b6f8890e7696335c662831bf4d48efb140056655154134ef15e9a80402.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/37d5c8b6f8890e7696335c662831bf4d48efb140056655154134ef15e9a80402.jpg)

![3ce7c539bc599628a49450ba752b99f0b36573cca7530b67dd9142244f3b2f7f.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/3ce7c539bc599628a49450ba752b99f0b36573cca7530b67dd9142244f3b2f7f.jpg)

![46d8c3e442d40cefa199df81526592e606c767af8249e2611c7f4a27a779daf1.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/46d8c3e442d40cefa199df81526592e606c767af8249e2611c7f4a27a779daf1.jpg)

![5444866993aa15072e07e64ba7bf892db1fcfc4888cdfc607cd97e896f518e06.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/5444866993aa15072e07e64ba7bf892db1fcfc4888cdfc607cd97e896f518e06.jpg)

![65ac7035e90ff5b4b42be463137d3dbac543e9594ed61745f6095183c226e282.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/65ac7035e90ff5b4b42be463137d3dbac543e9594ed61745f6095183c226e282.jpg)

![73862571a8a737e3de5fe7e4c07e22b6c4d01cd852765c66685a014d35b103cc.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/73862571a8a737e3de5fe7e4c07e22b6c4d01cd852765c66685a014d35b103cc.jpg)

![86a51ae40b0ec60b136735bab74ec3b0dd79d9fcd99bf71244baf6993db9f7be.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/86a51ae40b0ec60b136735bab74ec3b0dd79d9fcd99bf71244baf6993db9f7be.jpg)

![8c35d3683ce9cf52a618b4d48eeb5dba2dde69c5f38a4d58f904a754fed34ee1.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/8c35d3683ce9cf52a618b4d48eeb5dba2dde69c5f38a4d58f904a754fed34ee1.jpg)

![9253497d00e2a62ec2247330b38593198dafa6fe0c2c2db176c289a9461398c8.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/9253497d00e2a62ec2247330b38593198dafa6fe0c2c2db176c289a9461398c8.jpg)

![9bfcc7fb4b18ee7f90f3f903424da85381a3280bd7b2d1b74ea7572850277f9e.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/9bfcc7fb4b18ee7f90f3f903424da85381a3280bd7b2d1b74ea7572850277f9e.jpg)

![b07c91d264dd08cb03e687397386b197bb409a3a9d380a07aa44dc85f98957a4.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/b07c91d264dd08cb03e687397386b197bb409a3a9d380a07aa44dc85f98957a4.jpg)

![c0dfb821ad89e82d22e210348fdf8297f9fd98202928bb157b4929f9b6d1dbf5.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/c0dfb821ad89e82d22e210348fdf8297f9fd98202928bb157b4929f9b6d1dbf5.jpg)

![d5be29c0a3d4ddb44c937e95c2cc184951daed5fc27138d3c468ecb84b92bf06.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/d5be29c0a3d4ddb44c937e95c2cc184951daed5fc27138d3c468ecb84b92bf06.jpg)

![f88b0c69632cbe545f8e2f296fc3fd9c7b6734376f06456e4f5f9c065c9245f1.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/images/f88b0c69632cbe545f8e2f296fc3fd9c7b6734376f06456e4f5f9c065c9245f1.jpg)

### Tables

![45e1ad2b3975512ed04098f0215eb231fb5fa9327a0732e597e8b02c5255a432.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/tables/45e1ad2b3975512ed04098f0215eb231fb5fa9327a0732e597e8b02c5255a432.jpg)

![47f7943143d9ca31fdec4ea271887978e4bfb4331e392b38c612272ff3259604.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/tables/47f7943143d9ca31fdec4ea271887978e4bfb4331e392b38c612272ff3259604.jpg)

![50f1d56412dd4873efaab0fde947f71cd8da459bc4994528a17ec37143f6333e.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/tables/50f1d56412dd4873efaab0fde947f71cd8da459bc4994528a17ec37143f6333e.jpg)

![65ad339f3b3cb17093c2ce2ac03e9d30c539b85f0aa67bd40de50dffbfbe9779.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/tables/65ad339f3b3cb17093c2ce2ac03e9d30c539b85f0aa67bd40de50dffbfbe9779.jpg)

![a43ab2a075749777e3f0d45089d898b8a98c91302236a2841b560a32b24d08c5.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/tables/a43ab2a075749777e3f0d45089d898b8a98c91302236a2841b560a32b24d08c5.jpg)

![a7aa3a562d65dc5c4ef151753d04590212c3fb619e69f2ba7669f7537ae6a475.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/tables/a7aa3a562d65dc5c4ef151753d04590212c3fb619e69f2ba7669f7537ae6a475.jpg)

![f5d3000342462c2fc159402acb827e393a836eca0da968cfa7b84219e533ed42.jpg](../emnlp_results/292_OmniEval_%20An%20Omnidirectional%20and%20AutomaticRAGEvaluation%20Benchmark%20in%20Financial%20Domain/tables/f5d3000342462c2fc159402acb827e393a836eca0da968cfa7b84219e533ed42.jpg)

## AQuilt: Weaving Logic and Self-Inspection into Low-Cost, High-Relevance Data Synthesis for SpecialistLLMs


### Images

![020cfd2d9db928558fa8efb1d1fb2abcabd333bdefe7ad2677fca8466f1700ec.jpg](../emnlp_results/293_AQuilt_%20Weaving%20Logic%20and%20Self-Inspection%20into%20Low-Cost%2C%20High-Relevance%20Data%20Synthesis%20for%20Specialis/images/020cfd2d9db928558fa8efb1d1fb2abcabd333bdefe7ad2677fca8466f1700ec.jpg)

![320e30876c648f48f7df83a0e9038835646319d3afdde342c00b4e46e8982e9f.jpg](../emnlp_results/293_AQuilt_%20Weaving%20Logic%20and%20Self-Inspection%20into%20Low-Cost%2C%20High-Relevance%20Data%20Synthesis%20for%20Specialis/images/320e30876c648f48f7df83a0e9038835646319d3afdde342c00b4e46e8982e9f.jpg)

![d3972020361833ddcbbe78fac10e82c93010cc607ab57e8d90aecd8d36a9a0d5.jpg](../emnlp_results/293_AQuilt_%20Weaving%20Logic%20and%20Self-Inspection%20into%20Low-Cost%2C%20High-Relevance%20Data%20Synthesis%20for%20Specialis/images/d3972020361833ddcbbe78fac10e82c93010cc607ab57e8d90aecd8d36a9a0d5.jpg)

![d9556356cc32157013ead9b3c683d609d07e6fa64cf002bc8f674dd44026a99f.jpg](../emnlp_results/293_AQuilt_%20Weaving%20Logic%20and%20Self-Inspection%20into%20Low-Cost%2C%20High-Relevance%20Data%20Synthesis%20for%20Specialis/images/d9556356cc32157013ead9b3c683d609d07e6fa64cf002bc8f674dd44026a99f.jpg)

### Tables

![3129cd87e7bd4aab82b6d7b86a71258300278d930ddfd07c76cb659dc41357f0.jpg](../emnlp_results/293_AQuilt_%20Weaving%20Logic%20and%20Self-Inspection%20into%20Low-Cost%2C%20High-Relevance%20Data%20Synthesis%20for%20Specialis/tables/3129cd87e7bd4aab82b6d7b86a71258300278d930ddfd07c76cb659dc41357f0.jpg)

![44d1290379c1d197d95773414ee50c7801f49f8ca304db119f1d036a158feafa.jpg](../emnlp_results/293_AQuilt_%20Weaving%20Logic%20and%20Self-Inspection%20into%20Low-Cost%2C%20High-Relevance%20Data%20Synthesis%20for%20Specialis/tables/44d1290379c1d197d95773414ee50c7801f49f8ca304db119f1d036a158feafa.jpg)

![63866ff33f5864cc679f7f2ba616fb3267df95d9cf2c5aefc513db4de9a803c9.jpg](../emnlp_results/293_AQuilt_%20Weaving%20Logic%20and%20Self-Inspection%20into%20Low-Cost%2C%20High-Relevance%20Data%20Synthesis%20for%20Specialis/tables/63866ff33f5864cc679f7f2ba616fb3267df95d9cf2c5aefc513db4de9a803c9.jpg)

![6d5b74805fb862d57f7378d4315268df178ce468fa6356a7e2a7714aed0a8d9e.jpg](../emnlp_results/293_AQuilt_%20Weaving%20Logic%20and%20Self-Inspection%20into%20Low-Cost%2C%20High-Relevance%20Data%20Synthesis%20for%20Specialis/tables/6d5b74805fb862d57f7378d4315268df178ce468fa6356a7e2a7714aed0a8d9e.jpg)

![6f0db9ed5da488e017b1d887cf8934f05c4fd1706164cb484bff60d0be22fb1d.jpg](../emnlp_results/293_AQuilt_%20Weaving%20Logic%20and%20Self-Inspection%20into%20Low-Cost%2C%20High-Relevance%20Data%20Synthesis%20for%20Specialis/tables/6f0db9ed5da488e017b1d887cf8934f05c4fd1706164cb484bff60d0be22fb1d.jpg)

![878135cfa92293e87ad4c383284a8cea238f0371afead61d244e9fded7227206.jpg](../emnlp_results/293_AQuilt_%20Weaving%20Logic%20and%20Self-Inspection%20into%20Low-Cost%2C%20High-Relevance%20Data%20Synthesis%20for%20Specialis/tables/878135cfa92293e87ad4c383284a8cea238f0371afead61d244e9fded7227206.jpg)

![ce0ad6f40b4515affe146298e41f7b6da58ba7234a4107836a49308530da1252.jpg](../emnlp_results/293_AQuilt_%20Weaving%20Logic%20and%20Self-Inspection%20into%20Low-Cost%2C%20High-Relevance%20Data%20Synthesis%20for%20Specialis/tables/ce0ad6f40b4515affe146298e41f7b6da58ba7234a4107836a49308530da1252.jpg)

![e4586e8b075a584466756cd8a9ecd08a03ffb0f15ca8e46d652ab09d9316f727.jpg](../emnlp_results/293_AQuilt_%20Weaving%20Logic%20and%20Self-Inspection%20into%20Low-Cost%2C%20High-Relevance%20Data%20Synthesis%20for%20Specialis/tables/e4586e8b075a584466756cd8a9ecd08a03ffb0f15ca8e46d652ab09d9316f727.jpg)

## MoSEs: Uncertainty-AwareAI-Generated Text Detection via Mixture of Stylistics Experts with Conditional Thresholds


### Images

![022f52a79f3f08a20a176a59fc62465cc1d6ec98dfb60fd4cb84c46d0fcc2435.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/images/022f52a79f3f08a20a176a59fc62465cc1d6ec98dfb60fd4cb84c46d0fcc2435.jpg)

![9700fcd9688b2cd46c8be29b72e6ea7a8ffed9745cd2207f79ab6a07ec331938.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/images/9700fcd9688b2cd46c8be29b72e6ea7a8ffed9745cd2207f79ab6a07ec331938.jpg)

![9c24002bc1646a6760339da1e0f5168649efe55f68b420b4b28076a0dfa0b9a1.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/images/9c24002bc1646a6760339da1e0f5168649efe55f68b420b4b28076a0dfa0b9a1.jpg)

![d661b329e1d8a96f8b62eb8b0074c38397675b86a65cd9ee591de7dd3273da10.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/images/d661b329e1d8a96f8b62eb8b0074c38397675b86a65cd9ee591de7dd3273da10.jpg)

### Tables

![0a4f74c9f63c8bfaa6340ffa38955c21967f9c02d89cb0e71766c2b6385ec3d7.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/0a4f74c9f63c8bfaa6340ffa38955c21967f9c02d89cb0e71766c2b6385ec3d7.jpg)

![10756c812d9ac82339029d028306aa2cd55f2e717aa93e21e6bb948dac9e1dd5.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/10756c812d9ac82339029d028306aa2cd55f2e717aa93e21e6bb948dac9e1dd5.jpg)

![26b4fc7d752ebb4f9ccdcb37cf77e69ceb0d338311bfcc3a63ae7519de3b2b17.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/26b4fc7d752ebb4f9ccdcb37cf77e69ceb0d338311bfcc3a63ae7519de3b2b17.jpg)

![32c256478f993502b3d6a457ba26c895782ae5483e7181dc8d0e9f3063531a04.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/32c256478f993502b3d6a457ba26c895782ae5483e7181dc8d0e9f3063531a04.jpg)

![37a1fa298a601b0361f93f113df50698770a4eaa86b0762a760f6b3506e8a4bf.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/37a1fa298a601b0361f93f113df50698770a4eaa86b0762a760f6b3506e8a4bf.jpg)

![438cf8a9b2dcb537e5a9aa343c24a679380904982bee32a9da7db25e8bc056b0.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/438cf8a9b2dcb537e5a9aa343c24a679380904982bee32a9da7db25e8bc056b0.jpg)

![72a6b7ffce72034549e4cd46be8a26c685df0db09146d6acc8f66cedddd34a46.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/72a6b7ffce72034549e4cd46be8a26c685df0db09146d6acc8f66cedddd34a46.jpg)

![738bef341026d70d9e716ba0d6cf6e9d49110314af0bdecc556e8393eee1ab21.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/738bef341026d70d9e716ba0d6cf6e9d49110314af0bdecc556e8393eee1ab21.jpg)

![7eb9507583674845f8c70b557290da98cd40db054c3a190c78ea2794527f56f6.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/7eb9507583674845f8c70b557290da98cd40db054c3a190c78ea2794527f56f6.jpg)

![931b746bcc8cadf41be301da167e82ec670e3329badd2dceb3c788186d618d4a.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/931b746bcc8cadf41be301da167e82ec670e3329badd2dceb3c788186d618d4a.jpg)

![962b78a9057c3293fb5b5c32dd804c89f91e5b2f864b4ea5855f8e24c7a151c7.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/962b78a9057c3293fb5b5c32dd804c89f91e5b2f864b4ea5855f8e24c7a151c7.jpg)

![9691c87cda8b3c72154b35655df6a840d9531af6ea93345f79bd73cf74d7a321.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/9691c87cda8b3c72154b35655df6a840d9531af6ea93345f79bd73cf74d7a321.jpg)

![969b08eb02875eb1b15e67b967ed05bfd183f35ce2166e88bd2cc284936972d2.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/969b08eb02875eb1b15e67b967ed05bfd183f35ce2166e88bd2cc284936972d2.jpg)

![98d68fb9441e25c8bd3c16c97a8f4a45084f7541f2244798f15a88e76a367bde.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/98d68fb9441e25c8bd3c16c97a8f4a45084f7541f2244798f15a88e76a367bde.jpg)

![a283adb8071cd63b37d10372d8cbc503fe71cffd3cddcaa24c94d06f39be5a32.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/a283adb8071cd63b37d10372d8cbc503fe71cffd3cddcaa24c94d06f39be5a32.jpg)

![acc01d00f3397ecb9e9966acccc3a1a6159e767bb43888c289e871c79a52069d.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/acc01d00f3397ecb9e9966acccc3a1a6159e767bb43888c289e871c79a52069d.jpg)

![e5ab114c9da1748dccf97d2dc267e5dbd3bcdb40b0289a6816bfd920a482e5f4.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/e5ab114c9da1748dccf97d2dc267e5dbd3bcdb40b0289a6816bfd920a482e5f4.jpg)

![f454124413c81c72faeddfbd9d86301b3046c13a17d20841eff79d11d6524066.jpg](../emnlp_results/294_MoSEs_%20Uncertainty-AwareAI-Generated%20Text%20Detection%20via%20Mixture%20of%20Stylistics%20Experts%20with%20Condition/tables/f454124413c81c72faeddfbd9d86301b3046c13a17d20841eff79d11d6524066.jpg)

## Merger-as-a-Stealer: Stealing TargetedPIIfrom AlignedLLMs with Model Merging


### Images

![0ce588fff940301edf5c7cae0127076808a8590c0920078d836e2d22f685b615.jpg](../emnlp_results/295_Merger-as-a-Stealer_%20Stealing%20TargetedPIIfrom%20AlignedLLMs%20with%20Model%20Merging/images/0ce588fff940301edf5c7cae0127076808a8590c0920078d836e2d22f685b615.jpg)

![1184d9f1b3225bcddfc94b1cb9ae559b1c15646c874e09f7f87ba9fd33152124.jpg](../emnlp_results/295_Merger-as-a-Stealer_%20Stealing%20TargetedPIIfrom%20AlignedLLMs%20with%20Model%20Merging/images/1184d9f1b3225bcddfc94b1cb9ae559b1c15646c874e09f7f87ba9fd33152124.jpg)

![1ff6d0f51ec17acf1b7c0b20c9a14b4f5a186bcfa9bcac49de362015d2172543.jpg](../emnlp_results/295_Merger-as-a-Stealer_%20Stealing%20TargetedPIIfrom%20AlignedLLMs%20with%20Model%20Merging/images/1ff6d0f51ec17acf1b7c0b20c9a14b4f5a186bcfa9bcac49de362015d2172543.jpg)

### Tables

![50ee6dda5560d4964d635a980325acef1784948d8aa5f87a83f427e064d35558.jpg](../emnlp_results/295_Merger-as-a-Stealer_%20Stealing%20TargetedPIIfrom%20AlignedLLMs%20with%20Model%20Merging/tables/50ee6dda5560d4964d635a980325acef1784948d8aa5f87a83f427e064d35558.jpg)

![a581a44093557b45935efd2602a727a7e907d2bbdc9ce7cfc9e46ed1552db6f1.jpg](../emnlp_results/295_Merger-as-a-Stealer_%20Stealing%20TargetedPIIfrom%20AlignedLLMs%20with%20Model%20Merging/tables/a581a44093557b45935efd2602a727a7e907d2bbdc9ce7cfc9e46ed1552db6f1.jpg)

![cc86087032f4c9684669c891c8a58148c0d7f99d02eee008b786b7d351e83832.jpg](../emnlp_results/295_Merger-as-a-Stealer_%20Stealing%20TargetedPIIfrom%20AlignedLLMs%20with%20Model%20Merging/tables/cc86087032f4c9684669c891c8a58148c0d7f99d02eee008b786b7d351e83832.jpg)

![f65bf31adf18d39a8eff652bb867c718e309b5bf46bf64abe460254006f65206.jpg](../emnlp_results/295_Merger-as-a-Stealer_%20Stealing%20TargetedPIIfrom%20AlignedLLMs%20with%20Model%20Merging/tables/f65bf31adf18d39a8eff652bb867c718e309b5bf46bf64abe460254006f65206.jpg)

## Pragmatic Inference Chain (PIC) ImprovingLLMs’ Reasoning of Authentic Implicit Toxic Language


### Images

![08555452b2b27ac1b3422e0920e9d67fb9d67e78ab8ccb1a3d8cf534849c0bd7.jpg](../emnlp_results/296_Pragmatic%20Inference%20Chain%20%28PIC) ImprovingLLMs’ Reasoning of Authentic Implicit Toxic Language/images/08555452b2b27ac1b3422e0920e9d67fb9d67e78ab8ccb1a3d8cf534849c0bd7.jpg)

![5b9df6a58b448892a42f942342459dd3d02fd0c0ea84e2e4000169a0f83937a7.jpg](../emnlp_results/296_Pragmatic%20Inference%20Chain%20%28PIC) ImprovingLLMs’ Reasoning of Authentic Implicit Toxic Language/images/5b9df6a58b448892a42f942342459dd3d02fd0c0ea84e2e4000169a0f83937a7.jpg)

![73edee9943ef727120b251f2bed9c0e58ec39ba022dad9ec04a799782aef36d8.jpg](../emnlp_results/296_Pragmatic%20Inference%20Chain%20%28PIC) ImprovingLLMs’ Reasoning of Authentic Implicit Toxic Language/images/73edee9943ef727120b251f2bed9c0e58ec39ba022dad9ec04a799782aef36d8.jpg)

![d454429ee46a10d746cdf9125e9fd91fa521b73077ae85c740b949792c41c41d.jpg](../emnlp_results/296_Pragmatic%20Inference%20Chain%20%28PIC) ImprovingLLMs’ Reasoning of Authentic Implicit Toxic Language/images/d454429ee46a10d746cdf9125e9fd91fa521b73077ae85c740b949792c41c41d.jpg)

### Tables

![3b5f2257f5214147cab591786d4cd4185542a388511ab402b97800e9e4d1056c.jpg](../emnlp_results/296_Pragmatic%20Inference%20Chain%20%28PIC) ImprovingLLMs’ Reasoning of Authentic Implicit Toxic Language/tables/3b5f2257f5214147cab591786d4cd4185542a388511ab402b97800e9e4d1056c.jpg)

![416d3c2c410ca643732e3717194eb7e10522a4ce607c54ef8ad5e90e9cb31494.jpg](../emnlp_results/296_Pragmatic%20Inference%20Chain%20%28PIC) ImprovingLLMs’ Reasoning of Authentic Implicit Toxic Language/tables/416d3c2c410ca643732e3717194eb7e10522a4ce607c54ef8ad5e90e9cb31494.jpg)

![5d8087af390dbde6dee90f8e3ad4ed89f4390b8336877b0f0e8e4c48141810c5.jpg](../emnlp_results/296_Pragmatic%20Inference%20Chain%20%28PIC) ImprovingLLMs’ Reasoning of Authentic Implicit Toxic Language/tables/5d8087af390dbde6dee90f8e3ad4ed89f4390b8336877b0f0e8e4c48141810c5.jpg)

![acd7818b89a4d2e8905f7d491999695665acf9d5315df16f7fbc172ccca4705a.jpg](../emnlp_results/296_Pragmatic%20Inference%20Chain%20%28PIC) ImprovingLLMs’ Reasoning of Authentic Implicit Toxic Language/tables/acd7818b89a4d2e8905f7d491999695665acf9d5315df16f7fbc172ccca4705a.jpg)

## Beyond Demonstrations: Dynamic Vector Construction from Latent Representations


### Images

![093516cebc4f69bc7cd3bbb37f30dc49f619fca9a6adb1b68eb89dfcfe076c34.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/images/093516cebc4f69bc7cd3bbb37f30dc49f619fca9a6adb1b68eb89dfcfe076c34.jpg)

![48839e432ff01483e21481539287580fb08439a5f53c951638820bac4a8dc585.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/images/48839e432ff01483e21481539287580fb08439a5f53c951638820bac4a8dc585.jpg)

![6e8adef24b795429d7e284b4cfff762514011865d77211061f693bdec554105b.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/images/6e8adef24b795429d7e284b4cfff762514011865d77211061f693bdec554105b.jpg)

![c2af11308653337bc7bf36b4caf262491869299846e05107135afa81922c3648.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/images/c2af11308653337bc7bf36b4caf262491869299846e05107135afa81922c3648.jpg)

### Tables

![00ad2b6c9b740b1f0c32cc2c3656e87107fe9bf7c00589e722912485fdb50ccf.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/00ad2b6c9b740b1f0c32cc2c3656e87107fe9bf7c00589e722912485fdb50ccf.jpg)

![2027e4b33878e2bc4f658dc63eec1b7859f02fdcbb566565e021f563b5a04229.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/2027e4b33878e2bc4f658dc63eec1b7859f02fdcbb566565e021f563b5a04229.jpg)

![2cef527657e42eff80d87878c37b4e5ac9664c414c6977acb37cf8e3fb669a4d.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/2cef527657e42eff80d87878c37b4e5ac9664c414c6977acb37cf8e3fb669a4d.jpg)

![3124d8191780990c4f88872df350be0b7c3892a99c9a492295e33c1e352c85c1.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/3124d8191780990c4f88872df350be0b7c3892a99c9a492295e33c1e352c85c1.jpg)

![54db7bdf3685eb2e7bccc1df488af9922b6183c31f2bc0f20d655bc916a9e96a.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/54db7bdf3685eb2e7bccc1df488af9922b6183c31f2bc0f20d655bc916a9e96a.jpg)

![6b1ced86e0901b4ec672d9f4bf21c3d288822ca3e0c398c4d08caf5d44bf4069.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/6b1ced86e0901b4ec672d9f4bf21c3d288822ca3e0c398c4d08caf5d44bf4069.jpg)

![74fec163dc674ba2f7bc03d9ad1dae6a03eb44db388cd6872d5dec6039c6a63d.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/74fec163dc674ba2f7bc03d9ad1dae6a03eb44db388cd6872d5dec6039c6a63d.jpg)

![839e167712e5f9b3616d3a834b1944a2164917537265263bb1539735f84928ad.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/839e167712e5f9b3616d3a834b1944a2164917537265263bb1539735f84928ad.jpg)

![8620dbb300d7b53b1e4ecda31792d6363e598553d36aacbc52d9a886b50633cb.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/8620dbb300d7b53b1e4ecda31792d6363e598553d36aacbc52d9a886b50633cb.jpg)

![88b0932d3412651050bb5e0bdb79227650fcbb71b711b75d7a5f53792eca3eb6.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/88b0932d3412651050bb5e0bdb79227650fcbb71b711b75d7a5f53792eca3eb6.jpg)

![8b1ce71745958639079806c958cf9ae56152ab98cfc25bd9286108ca41acef42.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/8b1ce71745958639079806c958cf9ae56152ab98cfc25bd9286108ca41acef42.jpg)

![9b844524de02fdab08fb4b433d50dc047e8a33c5c1d690bdb20ead868cce3856.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/9b844524de02fdab08fb4b433d50dc047e8a33c5c1d690bdb20ead868cce3856.jpg)

![a898e6fa387afb2d9af4437d541c652e145c9ff2c94ab82216b9ba7484599c3e.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/a898e6fa387afb2d9af4437d541c652e145c9ff2c94ab82216b9ba7484599c3e.jpg)

![d5dd409b7a2e4a76d8e03f8ad34f99e41de82333ed17a960a521af7715c1a1b1.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/d5dd409b7a2e4a76d8e03f8ad34f99e41de82333ed17a960a521af7715c1a1b1.jpg)

![e915b268fe8d420ff035b0391288a6d691c4fc81ccaeb34579faf90a4b9d718c.jpg](../emnlp_results/297_Beyond%20Demonstrations_%20Dynamic%20Vector%20Construction%20from%20Latent%20Representations/tables/e915b268fe8d420ff035b0391288a6d691c4fc81ccaeb34579faf90a4b9d718c.jpg)

## Detoxifying Large Language Models via the Diversity of Toxic Samples


### Images

![07493322680dc9cc9801cf4927ab49d5dea0dcb95ef905041a5138649357c87a.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/images/07493322680dc9cc9801cf4927ab49d5dea0dcb95ef905041a5138649357c87a.jpg)

![33b78e4f632a60a9d4a9506b9f8d569db83a7747b868bec82aa5ce68e5260ad7.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/images/33b78e4f632a60a9d4a9506b9f8d569db83a7747b868bec82aa5ce68e5260ad7.jpg)

![38f9ced0d207ef1178b2d70528d1db3e2f8316cda8a3963e640dceef8a3264ad.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/images/38f9ced0d207ef1178b2d70528d1db3e2f8316cda8a3963e640dceef8a3264ad.jpg)

### Tables

![1e0d1415a933ff89954a9780509c936613f52829b847ae705c74dd60b059ba3e.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/tables/1e0d1415a933ff89954a9780509c936613f52829b847ae705c74dd60b059ba3e.jpg)

![298fd14a1cbe61ee83e0174310d9df3980c8b13316729f94f140d76cda2437f6.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/tables/298fd14a1cbe61ee83e0174310d9df3980c8b13316729f94f140d76cda2437f6.jpg)

![2a1bfd529869e715d5d225616f961eae8ecb58cfc305b55dfeb99df69233e42f.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/tables/2a1bfd529869e715d5d225616f961eae8ecb58cfc305b55dfeb99df69233e42f.jpg)

![3038ca768fe83a3937492764f7677478644de020a2d4f66e9fb3ae7c36e5f172.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/tables/3038ca768fe83a3937492764f7677478644de020a2d4f66e9fb3ae7c36e5f172.jpg)

![31752412b7894db7f157e6450a69303082cd2e29bd98e0ed17c3b26020fb341f.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/tables/31752412b7894db7f157e6450a69303082cd2e29bd98e0ed17c3b26020fb341f.jpg)

![3a72e78442a43eb1a891878012c9e33be9f9ca5e323abfd6a11815d5067e0971.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/tables/3a72e78442a43eb1a891878012c9e33be9f9ca5e323abfd6a11815d5067e0971.jpg)

![490750f395dd4ae7bdac0387956817f603f46a255b27a7388205f33d493e4239.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/tables/490750f395dd4ae7bdac0387956817f603f46a255b27a7388205f33d493e4239.jpg)

![8f5bf9b9ff5705aeaf8ed70863e063eaf982684c24939114318a14f031de50e5.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/tables/8f5bf9b9ff5705aeaf8ed70863e063eaf982684c24939114318a14f031de50e5.jpg)

![db1a38ab35a5381aa40f3e64e1aa85f65867dd3ce699c2c856b040061e38cb53.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/tables/db1a38ab35a5381aa40f3e64e1aa85f65867dd3ce699c2c856b040061e38cb53.jpg)

![e9ba4d85f967d85b7b61d8ce7bc1be7e08bfec95023a49a4db4c525f04a2f3fa.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/tables/e9ba4d85f967d85b7b61d8ce7bc1be7e08bfec95023a49a4db4c525f04a2f3fa.jpg)

![ecf93165d06ec5ddea03de92e2dbeac7cb69b478f84680073ace9f1068f5a84d.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/tables/ecf93165d06ec5ddea03de92e2dbeac7cb69b478f84680073ace9f1068f5a84d.jpg)

![f26c5738e45d40ff22e9f9bf439e30e86293a4ed160be065eb95164c8436aba0.jpg](../emnlp_results/298_Detoxifying%20Large%20Language%20Models%20via%20the%20Diversity%20of%20Toxic%20Samples/tables/f26c5738e45d40ff22e9f9bf439e30e86293a4ed160be065eb95164c8436aba0.jpg)

## LLM-Driven Implicit Target Augmentation and Fine-Grained Contextual Modeling for Zero-Shot and Few-Shot Stance Detection


### Images

![0780003282b07fc4152e59a115f8dc4bb48b60782479f89c211d594ad0ec1ca0.jpg](../emnlp_results/299_LLM-Driven%20Implicit%20Target%20Augmentation%20and%20Fine-Grained%20Contextual%20Modeling%20for%20Zero-Shot%20and%20Few-S/images/0780003282b07fc4152e59a115f8dc4bb48b60782479f89c211d594ad0ec1ca0.jpg)

![58e64fda0952099e9b96ebfcfb4e5c89016cb3de00418518b42314642d87ee8a.jpg](../emnlp_results/299_LLM-Driven%20Implicit%20Target%20Augmentation%20and%20Fine-Grained%20Contextual%20Modeling%20for%20Zero-Shot%20and%20Few-S/images/58e64fda0952099e9b96ebfcfb4e5c89016cb3de00418518b42314642d87ee8a.jpg)

![d4efd492f25aabd70b4b56f0f745d9f135d24eebe11e362bf084dda352a19570.jpg](../emnlp_results/299_LLM-Driven%20Implicit%20Target%20Augmentation%20and%20Fine-Grained%20Contextual%20Modeling%20for%20Zero-Shot%20and%20Few-S/images/d4efd492f25aabd70b4b56f0f745d9f135d24eebe11e362bf084dda352a19570.jpg)

### Tables

![5f75a17ed568319668e869f435ecb813e2864860d994d77eb3ce9047aa571340.jpg](../emnlp_results/299_LLM-Driven%20Implicit%20Target%20Augmentation%20and%20Fine-Grained%20Contextual%20Modeling%20for%20Zero-Shot%20and%20Few-S/tables/5f75a17ed568319668e869f435ecb813e2864860d994d77eb3ce9047aa571340.jpg)

![7af6b4857490de00b8269ead8ce025c38137444db690e8fecb9356e48dc324ba.jpg](../emnlp_results/299_LLM-Driven%20Implicit%20Target%20Augmentation%20and%20Fine-Grained%20Contextual%20Modeling%20for%20Zero-Shot%20and%20Few-S/tables/7af6b4857490de00b8269ead8ce025c38137444db690e8fecb9356e48dc324ba.jpg)

![7be50077c7b04592108c0d999bafe936b011e33e3c34e09a510cb9b4f9bb95f6.jpg](../emnlp_results/299_LLM-Driven%20Implicit%20Target%20Augmentation%20and%20Fine-Grained%20Contextual%20Modeling%20for%20Zero-Shot%20and%20Few-S/tables/7be50077c7b04592108c0d999bafe936b011e33e3c34e09a510cb9b4f9bb95f6.jpg)

![84f20f088cb32b8634df43964bbac51fda13aa570832b7c6425fd967188edb23.jpg](../emnlp_results/299_LLM-Driven%20Implicit%20Target%20Augmentation%20and%20Fine-Grained%20Contextual%20Modeling%20for%20Zero-Shot%20and%20Few-S/tables/84f20f088cb32b8634df43964bbac51fda13aa570832b7c6425fd967188edb23.jpg)

![b10e06816b6d21d483e21173c1b785bff8105024b8ab7bcbeb3a83772184b43d.jpg](../emnlp_results/299_LLM-Driven%20Implicit%20Target%20Augmentation%20and%20Fine-Grained%20Contextual%20Modeling%20for%20Zero-Shot%20and%20Few-S/tables/b10e06816b6d21d483e21173c1b785bff8105024b8ab7bcbeb3a83772184b43d.jpg)

![c0a3f6945b28d8cf2a8dfa407bc650c465bdb12392ede02b39c4c4b1a35d5f95.jpg](../emnlp_results/299_LLM-Driven%20Implicit%20Target%20Augmentation%20and%20Fine-Grained%20Contextual%20Modeling%20for%20Zero-Shot%20and%20Few-S/tables/c0a3f6945b28d8cf2a8dfa407bc650c465bdb12392ede02b39c4c4b1a35d5f95.jpg)

![cea6abf334dbdb84fd0ae2503f6f92ba9d81f8052eb33f113b252c9806bdbeba.jpg](../emnlp_results/299_LLM-Driven%20Implicit%20Target%20Augmentation%20and%20Fine-Grained%20Contextual%20Modeling%20for%20Zero-Shot%20and%20Few-S/tables/cea6abf334dbdb84fd0ae2503f6f92ba9d81f8052eb33f113b252c9806bdbeba.jpg)

![e0bc05d067cb69d45f88802e0766b0137e5bbc0c22042e09f35152e6fd1ff095.jpg](../emnlp_results/299_LLM-Driven%20Implicit%20Target%20Augmentation%20and%20Fine-Grained%20Contextual%20Modeling%20for%20Zero-Shot%20and%20Few-S/tables/e0bc05d067cb69d45f88802e0766b0137e5bbc0c22042e09f35152e6fd1ff095.jpg)

![e15c3e13525110a08b055fd061653bc389c26b4bb41e725fb9fafff16e1a95a6.jpg](../emnlp_results/299_LLM-Driven%20Implicit%20Target%20Augmentation%20and%20Fine-Grained%20Contextual%20Modeling%20for%20Zero-Shot%20and%20Few-S/tables/e15c3e13525110a08b055fd061653bc389c26b4bb41e725fb9fafff16e1a95a6.jpg)

![e8f0d0935b2539706663cf1ef384e8193d0f28d366dbb0dd86c9bfa19369f8a1.jpg](../emnlp_results/299_LLM-Driven%20Implicit%20Target%20Augmentation%20and%20Fine-Grained%20Contextual%20Modeling%20for%20Zero-Shot%20and%20Few-S/tables/e8f0d0935b2539706663cf1ef384e8193d0f28d366dbb0dd86c9bfa19369f8a1.jpg)

## Dial-InLLM: Human-AlignedLLM-in-the-loop Intent Clustering for Customer Service Dialogues


### Images

![42985f55618832c39fb27ca6b031b58bb57fe8b673011dd86bd6f1d2b7febaf1.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/images/42985f55618832c39fb27ca6b031b58bb57fe8b673011dd86bd6f1d2b7febaf1.jpg)

![45c92615cd83969ff2be8518db61ecf9f16718cf4c5b7c64d7938a11d511906c.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/images/45c92615cd83969ff2be8518db61ecf9f16718cf4c5b7c64d7938a11d511906c.jpg)

![53e7406685fd335eff7ecfe62f4f990444e3dfd430f54a85c77df13047499beb.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/images/53e7406685fd335eff7ecfe62f4f990444e3dfd430f54a85c77df13047499beb.jpg)

### Tables

![0e3c70d9e281ab170ed1d41db22099403c1d398123941c83819f5ad0edd30bba.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/0e3c70d9e281ab170ed1d41db22099403c1d398123941c83819f5ad0edd30bba.jpg)

![2303bd4af189811649a95e521732b3274c8417d3f1566b466a0cff374c634f7c.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/2303bd4af189811649a95e521732b3274c8417d3f1566b466a0cff374c634f7c.jpg)

![2ff41a3513831ce46d4d1b41ba220391217c5a4bb3c39fe731db00e31d2405f4.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/2ff41a3513831ce46d4d1b41ba220391217c5a4bb3c39fe731db00e31d2405f4.jpg)

![49339bd03870135d7182d81fd753f455c8c8ac28f45bec2e3587ef0de3006a34.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/49339bd03870135d7182d81fd753f455c8c8ac28f45bec2e3587ef0de3006a34.jpg)

![5d39f8507fa0fd4ec8c0faf6e352e0dd3868fc9ef56b96ad337e4b3a68f5859c.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/5d39f8507fa0fd4ec8c0faf6e352e0dd3868fc9ef56b96ad337e4b3a68f5859c.jpg)

![5f8137665d29e0dc71f3e789d9194f6a6544ebcc8561b386260e95302a03f2c6.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/5f8137665d29e0dc71f3e789d9194f6a6544ebcc8561b386260e95302a03f2c6.jpg)

![7bff2374a13b5718308ab2af355234100bd621474663c81e6584cf3c039cd193.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/7bff2374a13b5718308ab2af355234100bd621474663c81e6584cf3c039cd193.jpg)

![814c8705bf178ad03f8b5bf73a6cc35c477816340e5a7166932e72a1edfceba7.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/814c8705bf178ad03f8b5bf73a6cc35c477816340e5a7166932e72a1edfceba7.jpg)

![8c2788e7b6646aa21019b5e1732f0f9bd13b9fc5e5da3cac25370be186d88bbb.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/8c2788e7b6646aa21019b5e1732f0f9bd13b9fc5e5da3cac25370be186d88bbb.jpg)

![9abef4332d028967129a986af847097eb121c2298e6548a2afacc2e2fad8edf1.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/9abef4332d028967129a986af847097eb121c2298e6548a2afacc2e2fad8edf1.jpg)

![9c8273e6fb2a48323217a9290126c14c74af250d8b441446125636b91f740f6c.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/9c8273e6fb2a48323217a9290126c14c74af250d8b441446125636b91f740f6c.jpg)

![b105b8aa377e16de51648b0fd7ae3acfff25fe5ecfba306a0968b95bdd736e71.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/b105b8aa377e16de51648b0fd7ae3acfff25fe5ecfba306a0968b95bdd736e71.jpg)

![bc57250453ff6c041d37635710b8ba322fb86065f54764d1955558a962f1cba9.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/bc57250453ff6c041d37635710b8ba322fb86065f54764d1955558a962f1cba9.jpg)

![c10400c3d9bffcc05e647fd84131058f32f4a490617672f5237c32acc16099c5.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/c10400c3d9bffcc05e647fd84131058f32f4a490617672f5237c32acc16099c5.jpg)

![ea170f5cf7bb84817d157a8ae35f4b98b3a23307f92300e4dfdf00871725650b.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/ea170f5cf7bb84817d157a8ae35f4b98b3a23307f92300e4dfdf00871725650b.jpg)

![fe247019d51fedd09b643f7a1dfd00cb61959c48e7c30ef1177d7d02d1a680b5.jpg](../emnlp_results/300_Dial-InLLM_%20Human-AlignedLLM-in-the-loop%20Intent%20Clustering%20for%20Customer%20Service%20Dialogues/tables/fe247019d51fedd09b643f7a1dfd00cb61959c48e7c30ef1177d7d02d1a680b5.jpg)

## Superficial Self-Improved Reasoners Benefit from Model Merging


### Images

![04d97abca3e0f46074d670ac888b1c0992b46f70e2225ebf801e07faabf8cfc0.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/images/04d97abca3e0f46074d670ac888b1c0992b46f70e2225ebf801e07faabf8cfc0.jpg)

![355fc38319ae7573de93d18820785b95f09175ea2bae5d8ba5fabb18b8c8d2d9.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/images/355fc38319ae7573de93d18820785b95f09175ea2bae5d8ba5fabb18b8c8d2d9.jpg)

![3f4f7ee3b07264518c387560bd4603a28a4d8dd5d43548effe1800e0b2bf9648.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/images/3f4f7ee3b07264518c387560bd4603a28a4d8dd5d43548effe1800e0b2bf9648.jpg)

![57cec6b9bf1a580076069e9008d60c0d6ea2d6b56b8301b189ceaeee5a34b6a1.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/images/57cec6b9bf1a580076069e9008d60c0d6ea2d6b56b8301b189ceaeee5a34b6a1.jpg)

![59d637bb3d9d11064373d9c298dcaa4cfd2ca88de09ae9f8060ff6992a6993c7.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/images/59d637bb3d9d11064373d9c298dcaa4cfd2ca88de09ae9f8060ff6992a6993c7.jpg)

![69e261c93f6b07533dc63c6a900065e5cbd2d9439baf43d8e7ab0bb7a6240699.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/images/69e261c93f6b07533dc63c6a900065e5cbd2d9439baf43d8e7ab0bb7a6240699.jpg)

![7ad3324a275d80e6965c37c8c8f8c75c49c2999d5532d91625c80485d9803409.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/images/7ad3324a275d80e6965c37c8c8f8c75c49c2999d5532d91625c80485d9803409.jpg)

![806f0bb8b29632661b5a7bc694e37083cc5f2a6109722589ebeb0bcc1a566667.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/images/806f0bb8b29632661b5a7bc694e37083cc5f2a6109722589ebeb0bcc1a566667.jpg)

![85172f67ae298d3f508a496cecb1e67698a03ecf466e951433b6730cb94a6c39.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/images/85172f67ae298d3f508a496cecb1e67698a03ecf466e951433b6730cb94a6c39.jpg)

![a37b7aa0a9f04bcf35ea2fe02a711b0027e11e8f0161623351a5f9fadb1a8c56.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/images/a37b7aa0a9f04bcf35ea2fe02a711b0027e11e8f0161623351a5f9fadb1a8c56.jpg)

![af3f472e35c38ab48a286a97ae2620e2f385cc99c9e765c540fe4bf8f0b91cd3.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/images/af3f472e35c38ab48a286a97ae2620e2f385cc99c9e765c540fe4bf8f0b91cd3.jpg)

![da9a7151a49ef6472c34ab32ca65f69ad61048e473338ff95ac2ec440905be6a.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/images/da9a7151a49ef6472c34ab32ca65f69ad61048e473338ff95ac2ec440905be6a.jpg)

![f850e8d8b8dad357ae6c0d4c9a6d1de6acc1942e56380891fa3934b67034498d.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/images/f850e8d8b8dad357ae6c0d4c9a6d1de6acc1942e56380891fa3934b67034498d.jpg)

### Tables

![1151fc22446aec03afac54fc74e89ad534b9deaf8eb09a23502e235f73bcdd47.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/tables/1151fc22446aec03afac54fc74e89ad534b9deaf8eb09a23502e235f73bcdd47.jpg)

![13570e21bd039fd8cd1bd7c4f2292562a3615bc64bd23ae57340c03d538fa4e7.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/tables/13570e21bd039fd8cd1bd7c4f2292562a3615bc64bd23ae57340c03d538fa4e7.jpg)

![229124e7d676880d23ab33d60c0469edfa9d13781cb44a0a628da4be376caecf.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/tables/229124e7d676880d23ab33d60c0469edfa9d13781cb44a0a628da4be376caecf.jpg)

![3594f301bd7093f139c29183a6987fb1ffd00de7c663d83c18960cd160c5ee81.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/tables/3594f301bd7093f139c29183a6987fb1ffd00de7c663d83c18960cd160c5ee81.jpg)

![4ad7b6c3e7c8924c48e9a7a9e582e7af7f5c9d00d33bbcf525a576e6243f1228.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/tables/4ad7b6c3e7c8924c48e9a7a9e582e7af7f5c9d00d33bbcf525a576e6243f1228.jpg)

![7aed7214304e9950c9d4e7b48710ae55553434319a03bc3f5950d6eefdddab60.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/tables/7aed7214304e9950c9d4e7b48710ae55553434319a03bc3f5950d6eefdddab60.jpg)

![7cb6d037e4ea1f89c280cd936644299b1516e897c4d765d0312f8c29b99ad244.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/tables/7cb6d037e4ea1f89c280cd936644299b1516e897c4d765d0312f8c29b99ad244.jpg)

![9dac8b8bef27f68aba070b832aeef86d2aa8c8d87377977701fafdd1a77048ff.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/tables/9dac8b8bef27f68aba070b832aeef86d2aa8c8d87377977701fafdd1a77048ff.jpg)

![c5c6bdaf6326adcd8b33a849284ebbbbdaea7fcee17cbdc15e77ac35b2ddd700.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/tables/c5c6bdaf6326adcd8b33a849284ebbbbdaea7fcee17cbdc15e77ac35b2ddd700.jpg)

![f9219804b59182f4c764d04ed45183bc49752ee22df5aa6e6895948388a0d3ed.jpg](../emnlp_results/301_Superficial%20Self-Improved%20Reasoners%20Benefit%20from%20Model%20Merging/tables/f9219804b59182f4c764d04ed45183bc49752ee22df5aa6e6895948388a0d3ed.jpg)

## CARFT: BoostingLLMReasoning via Contrastive Learning with Annotated Chain-of-Thought-based Reinforced Fine-Tuning


### Images

![011dfb32ab85e1ea4abfa7d52af743f8382b3bb600e8d6614f59b61043866e94.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/011dfb32ab85e1ea4abfa7d52af743f8382b3bb600e8d6614f59b61043866e94.jpg)

![05f3c47f25783716ca0ae167b0b0ea28240766969767ad55f05423139f038bac.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/05f3c47f25783716ca0ae167b0b0ea28240766969767ad55f05423139f038bac.jpg)

![104efb526fbd6aef4c9879433099d5ad44f986123e83ac50db48bcbb3355d100.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/104efb526fbd6aef4c9879433099d5ad44f986123e83ac50db48bcbb3355d100.jpg)

![153fd16439f514d1338556a8f86f9871f0e9171618054b605c01596fcb6ec238.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/153fd16439f514d1338556a8f86f9871f0e9171618054b605c01596fcb6ec238.jpg)

![157e20d57ac74b73178876249919fbc29afc0eebd6cc852ff75420dba56df12f.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/157e20d57ac74b73178876249919fbc29afc0eebd6cc852ff75420dba56df12f.jpg)

![3d9cbadb492f29fc7783cdb6adb39ec599f060526ff72cf9f3099034d1c28d5b.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/3d9cbadb492f29fc7783cdb6adb39ec599f060526ff72cf9f3099034d1c28d5b.jpg)

![678ea71c1441745b137ae3e03395abee7926861ef85f1de04c063ded0fa026b7.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/678ea71c1441745b137ae3e03395abee7926861ef85f1de04c063ded0fa026b7.jpg)

![87e36801d44d3e965676aa16e0ca769297a4755f9fa5c3bd4032262a7450fd81.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/87e36801d44d3e965676aa16e0ca769297a4755f9fa5c3bd4032262a7450fd81.jpg)

![94fce2864c4c90823a1a1fd4f795b2744fc40549ba2987479c33495b1df76592.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/94fce2864c4c90823a1a1fd4f795b2744fc40549ba2987479c33495b1df76592.jpg)

![c226e1aa9d2707c5d9c0cc1d780070219a8e09d36b605f20677003e673f74000.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/c226e1aa9d2707c5d9c0cc1d780070219a8e09d36b605f20677003e673f74000.jpg)

![d5daccfeb727742681b235f792b2144d3d99bfef38bfcfaf4d38e31afe4d0d21.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/d5daccfeb727742681b235f792b2144d3d99bfef38bfcfaf4d38e31afe4d0d21.jpg)

![d86d7e98f491a9b67f6213fe40c570f7ad25a0b8cd0400c4f19390c6ce71b249.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/d86d7e98f491a9b67f6213fe40c570f7ad25a0b8cd0400c4f19390c6ce71b249.jpg)

![dc250e7fd0cde1fd709b3ab4766f4daec82d81470f3d21e75913bbbae8c0aaa9.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/dc250e7fd0cde1fd709b3ab4766f4daec82d81470f3d21e75913bbbae8c0aaa9.jpg)

![e7dab5974a4a09d6695baab3e7d8f516e7eb0bad8ae72d556ff6c6d3d1cac684.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/e7dab5974a4a09d6695baab3e7d8f516e7eb0bad8ae72d556ff6c6d3d1cac684.jpg)

![e9b3d9f58515b7bb439b68424123ecfc1485e2fca0556a179468b76197655ffe.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/e9b3d9f58515b7bb439b68424123ecfc1485e2fca0556a179468b76197655ffe.jpg)

![eacfbbf5ec84941f2f850f42ac4009467124b0467102e1054d3946ffcf7801c1.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/eacfbbf5ec84941f2f850f42ac4009467124b0467102e1054d3946ffcf7801c1.jpg)

![fab2b0fbed6aee8c5300128cfddfbbce81b155c51878d63663025489cbd82379.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/images/fab2b0fbed6aee8c5300128cfddfbbce81b155c51878d63663025489cbd82379.jpg)

### Tables

![174e43dd755cbf71b8974d54f911c9299d0a98e37613faf3e5c8751688abbc7a.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/tables/174e43dd755cbf71b8974d54f911c9299d0a98e37613faf3e5c8751688abbc7a.jpg)

![32462c3440cd1b767439534049acefc7e224ec5bd9f427dd7df786b2e3a2da1c.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/tables/32462c3440cd1b767439534049acefc7e224ec5bd9f427dd7df786b2e3a2da1c.jpg)

![592fbb3295b49ec4a54e738ec81ccbe4c755f945558eeda4e681ddd8b6576aff.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/tables/592fbb3295b49ec4a54e738ec81ccbe4c755f945558eeda4e681ddd8b6576aff.jpg)

![89c5edbb29fb1ed97bea6c1cc730ed350b78861afef2b2f0498a4416c6a4fa0b.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/tables/89c5edbb29fb1ed97bea6c1cc730ed350b78861afef2b2f0498a4416c6a4fa0b.jpg)

![9cc3524beec846cbf94813f18450b732d1243177b92005277477a407381ab2af.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/tables/9cc3524beec846cbf94813f18450b732d1243177b92005277477a407381ab2af.jpg)

![ae7850adf4e96bce353bc471b9a35ec8fefbec187cfb24f234aa51b99a4c4cd6.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/tables/ae7850adf4e96bce353bc471b9a35ec8fefbec187cfb24f234aa51b99a4c4cd6.jpg)

![da8cefb34c1716cec31aa5c71391363ee38f3e1cb65e55b13a16636cc52584c5.jpg](../emnlp_results/302_CARFT_%20BoostingLLMReasoning%20via%20Contrastive%20Learning%20with%20Annotated%20Chain-of-Thought-based%20Reinforce/tables/da8cefb34c1716cec31aa5c71391363ee38f3e1cb65e55b13a16636cc52584c5.jpg)

## QualBench: BenchmarkingChineseLLMs with Localized Professional Qualifications for Vertical Domain Evaluation


### Tables

![01bc13ae1aaab9642ebf41fc98b06241c57f8fbb82fb6f2bc9273186c11375bb.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/01bc13ae1aaab9642ebf41fc98b06241c57f8fbb82fb6f2bc9273186c11375bb.jpg)

![17e6691db66300b1f0c9b904f87654d7c822d63cb06a8a9f7fe353e052e974ba.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/17e6691db66300b1f0c9b904f87654d7c822d63cb06a8a9f7fe353e052e974ba.jpg)

![23d680d00209ec77d36d00e6cdf31011b8b94eb878be2ca9c103f4f15e8f360c.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/23d680d00209ec77d36d00e6cdf31011b8b94eb878be2ca9c103f4f15e8f360c.jpg)

![247e200f502e180b8dc791ec497492a033848688f223ca7ad68727e8ff45aa2d.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/247e200f502e180b8dc791ec497492a033848688f223ca7ad68727e8ff45aa2d.jpg)

![3256289f2b66d4eb39c750b2485320f02b43c4989aa0697ca69135706b4fe4cc.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/3256289f2b66d4eb39c750b2485320f02b43c4989aa0697ca69135706b4fe4cc.jpg)

![4125af008a56c3b159153bbf6023a39c685817305fd7656cab8b3f3520d91d29.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/4125af008a56c3b159153bbf6023a39c685817305fd7656cab8b3f3520d91d29.jpg)

![4b5e199dd8927c2fc151fd33e794cb3f9f0fe3993fc3df398147eec0abeb21a1.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/4b5e199dd8927c2fc151fd33e794cb3f9f0fe3993fc3df398147eec0abeb21a1.jpg)

![6c8732129f55bcb4ad74f1054481a59edaaf858a9797c25f1363ff622bd71e86.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/6c8732129f55bcb4ad74f1054481a59edaaf858a9797c25f1363ff622bd71e86.jpg)

![75cf539b2f869dfbbe11d764a368e17c75dfedc2bcab5a7eda135471943c9b0d.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/75cf539b2f869dfbbe11d764a368e17c75dfedc2bcab5a7eda135471943c9b0d.jpg)

![794c404631bc87129240bd17854dac0db99b87069b4530cd0e24315c9d59208e.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/794c404631bc87129240bd17854dac0db99b87069b4530cd0e24315c9d59208e.jpg)

![9df61cb3ee83e34443bcad6938726f3a826e7a417daa2973f7123b6aef6af5db.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/9df61cb3ee83e34443bcad6938726f3a826e7a417daa2973f7123b6aef6af5db.jpg)

![b2b00244b8e19da58e3c1228aeaa8baa5f7b1af7452318a6101b2b275ac1d02e.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/b2b00244b8e19da58e3c1228aeaa8baa5f7b1af7452318a6101b2b275ac1d02e.jpg)

![c7aee66a3e04ed6c24a2dd224846c4e32e57093270fc490b3c8f9f6588859857.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/c7aee66a3e04ed6c24a2dd224846c4e32e57093270fc490b3c8f9f6588859857.jpg)

![d579b18924d6d29bed6dd6bf833bf3736847dc44bc5c71d399e05217f4226c23.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/d579b18924d6d29bed6dd6bf833bf3736847dc44bc5c71d399e05217f4226c23.jpg)

![da6a7b385488468db33ff9b6c64f33d9adafdf7b42da37376d2f47a3ff6a607d.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/da6a7b385488468db33ff9b6c64f33d9adafdf7b42da37376d2f47a3ff6a607d.jpg)

![e50ac856ce8b73979387ff1519d4b5ba2667bc4bcbea7628d8964219897a3ee3.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/e50ac856ce8b73979387ff1519d4b5ba2667bc4bcbea7628d8964219897a3ee3.jpg)

![eb429242fc2a8a1c91ba2ff0b31f3f378c60af082e33f96e2c0c184a267883aa.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/eb429242fc2a8a1c91ba2ff0b31f3f378c60af082e33f96e2c0c184a267883aa.jpg)

![fdde493da510e078d254966dd083246ee2a1cb691354cbb2386bbb5a500480c1.jpg](../emnlp_results/303_QualBench_%20BenchmarkingChineseLLMs%20with%20Localized%20Professional%20Qualifications%20for%20Vertical%20Domain%20Ev/tables/fdde493da510e078d254966dd083246ee2a1cb691354cbb2386bbb5a500480c1.jpg)

## VideoEraser: Concept Erasure in Text-to-Video Diffusion Models


### Images

![132f12d9764bd3c5be2825f3636a92118274e59dd2f229a7bb48aef22435c59e.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/132f12d9764bd3c5be2825f3636a92118274e59dd2f229a7bb48aef22435c59e.jpg)

![1d703b537f86f204ad595e298155307b1ac23f6b3a206193c4b7fad0a391af02.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/1d703b537f86f204ad595e298155307b1ac23f6b3a206193c4b7fad0a391af02.jpg)

![2943435e57c2c247755d6600ac062f81529ce1953825752deaff99e32ceb44e3.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/2943435e57c2c247755d6600ac062f81529ce1953825752deaff99e32ceb44e3.jpg)

![3dc5c8baea9391e285924b197d339e530fde14b0273bc6f225f718c97540ad94.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/3dc5c8baea9391e285924b197d339e530fde14b0273bc6f225f718c97540ad94.jpg)

![40d9a7ef1edce58f78d6d66658cd87b9e28e20a761033fce9ad25cb27f34cad7.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/40d9a7ef1edce58f78d6d66658cd87b9e28e20a761033fce9ad25cb27f34cad7.jpg)

![4493d66aa3e5b9cb781ea2d3052250b5e20c6bf18d6efa7f923c1d68a27b4e1d.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/4493d66aa3e5b9cb781ea2d3052250b5e20c6bf18d6efa7f923c1d68a27b4e1d.jpg)

![57bc5fa5312022314b0306bd4ce03f7bf40dd63761a59202f3860cd0146e1517.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/57bc5fa5312022314b0306bd4ce03f7bf40dd63761a59202f3860cd0146e1517.jpg)

![61b794cedb00cba015db6ad0ffef60e930f0be967f9c450f09dc074fa6189a9d.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/61b794cedb00cba015db6ad0ffef60e930f0be967f9c450f09dc074fa6189a9d.jpg)

![7a86e23179276bf86f983ec06857ac5eaf31a1e97906fe81605a0d1ffcfcb4b7.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/7a86e23179276bf86f983ec06857ac5eaf31a1e97906fe81605a0d1ffcfcb4b7.jpg)

![7e0f0bdc2afaaacbf39fca0c2beb19e2747304b947c47a29edb29fa9132572d3.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/7e0f0bdc2afaaacbf39fca0c2beb19e2747304b947c47a29edb29fa9132572d3.jpg)

![8c995c5cb3782f8733c864e47c1cab70c82c5aabd8867c6260f77d155f9f1f5b.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/8c995c5cb3782f8733c864e47c1cab70c82c5aabd8867c6260f77d155f9f1f5b.jpg)

![99478067d940579f537ae5cd1133360b9c740e473d1cd8ddbac88ed80d0b24fd.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/99478067d940579f537ae5cd1133360b9c740e473d1cd8ddbac88ed80d0b24fd.jpg)

![9a175f5a4e68ee31d2eda11da6443ad4fea89e49b610571400616cb1aeeeffc6.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/9a175f5a4e68ee31d2eda11da6443ad4fea89e49b610571400616cb1aeeeffc6.jpg)

![9e69ecf878387e3ca029b7fa8d6a6cb7d1e755f14bca86c0f5cf2956024f0cd7.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/9e69ecf878387e3ca029b7fa8d6a6cb7d1e755f14bca86c0f5cf2956024f0cd7.jpg)

![aeedd9962b02dc920dd8f30d2e0db1a9421bc13f4dfacd35c29cc881f307e2be.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/aeedd9962b02dc920dd8f30d2e0db1a9421bc13f4dfacd35c29cc881f307e2be.jpg)

![b1ec6839cf46c084525d8f7d5bdabb350d0f14e72a07150fb09d8699425e14d9.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/b1ec6839cf46c084525d8f7d5bdabb350d0f14e72a07150fb09d8699425e14d9.jpg)

![c51e3f661b5565b9beb4f81b50dbcda0e457018fe5c6474cc41b2f2db25300b1.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/c51e3f661b5565b9beb4f81b50dbcda0e457018fe5c6474cc41b2f2db25300b1.jpg)

![c5a9651c2d51ecfc28c5101a5b5d58e68450ed0f0690caa2b3f31dcc53848a7a.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/c5a9651c2d51ecfc28c5101a5b5d58e68450ed0f0690caa2b3f31dcc53848a7a.jpg)

![ce414e43eaf62ef4a2090623f6e00016b0cd381a320e7d9d1ab34800ccae86d9.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/ce414e43eaf62ef4a2090623f6e00016b0cd381a320e7d9d1ab34800ccae86d9.jpg)

![d02f316b6b15c6d269c49575b1f3c2e8a1c3081daa74741afda81f23e87ab662.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/d02f316b6b15c6d269c49575b1f3c2e8a1c3081daa74741afda81f23e87ab662.jpg)

![e0c52f096ab5cc427f4c8a66cbc99f2a4e76ddb790f8744c3d09584fc1a6d6c4.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/e0c52f096ab5cc427f4c8a66cbc99f2a4e76ddb790f8744c3d09584fc1a6d6c4.jpg)

![e3f219af199a1ac18fa4aa5b957c8bb4238b31e1c2a78777cc79f2864ee9e203.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/e3f219af199a1ac18fa4aa5b957c8bb4238b31e1c2a78777cc79f2864ee9e203.jpg)

![eda46ed2b11936b6c14fe2b133ad4f4460ab3b380e8a553d89deb3afe04228d0.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/eda46ed2b11936b6c14fe2b133ad4f4460ab3b380e8a553d89deb3afe04228d0.jpg)

![fa2152de417de6a697c14027e950bc11cf5cf151dbf3ce67a222790591742bc7.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/fa2152de417de6a697c14027e950bc11cf5cf151dbf3ce67a222790591742bc7.jpg)

![ff9d899d0e814d969d59f4e213845ff055913cec67a0bbec32d41c2a0883591e.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/images/ff9d899d0e814d969d59f4e213845ff055913cec67a0bbec32d41c2a0883591e.jpg)

### Tables

![0f78f3b2f35c4ef74fdeab9e67274aba6b19db6e92b59b457e3d083a43c493d7.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/0f78f3b2f35c4ef74fdeab9e67274aba6b19db6e92b59b457e3d083a43c493d7.jpg)

![1868dc2a2dc310400d053cb9be43340ddacd7af39d874f7035112df6fc2e9600.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/1868dc2a2dc310400d053cb9be43340ddacd7af39d874f7035112df6fc2e9600.jpg)

![2e80e7aaa7faa59d109e00d8015bbd32198453f3153d2e45ef4cd06e0a3ece59.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/2e80e7aaa7faa59d109e00d8015bbd32198453f3153d2e45ef4cd06e0a3ece59.jpg)

![3d9525cff377c6e773dabfa194947123b6320f7a51113eb30b6061686218297b.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/3d9525cff377c6e773dabfa194947123b6320f7a51113eb30b6061686218297b.jpg)

![47e43b75f48ca8a3297589d7a0335d71513eec701ea75b81d5f68d1636d263ee.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/47e43b75f48ca8a3297589d7a0335d71513eec701ea75b81d5f68d1636d263ee.jpg)

![59b45a8bac6d6b66ffe9d052d3722f3dff46adfd2795ce28130b8b82a2fefe45.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/59b45a8bac6d6b66ffe9d052d3722f3dff46adfd2795ce28130b8b82a2fefe45.jpg)

![6855c1f6d221989b67895bf188afdef986b73ea2e574dbda10b3d45fc89c7625.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/6855c1f6d221989b67895bf188afdef986b73ea2e574dbda10b3d45fc89c7625.jpg)

![72b64abcc6a72ea00cd43ec33eaec105f5929eb448508ad168e891d49bf352ab.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/72b64abcc6a72ea00cd43ec33eaec105f5929eb448508ad168e891d49bf352ab.jpg)

![76bb91884df3e2640f15b5172c1f8f8d057751f11cb2ded1566613c2b99e809b.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/76bb91884df3e2640f15b5172c1f8f8d057751f11cb2ded1566613c2b99e809b.jpg)

![7701baf95c317edbb4b42c15ba58d495a091b707948ade38a66f0fa23194519f.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/7701baf95c317edbb4b42c15ba58d495a091b707948ade38a66f0fa23194519f.jpg)

![7dd1f9aaa6aa29df5f9c183d90a43ec7bf7090ca871a5476da9fc1890f495592.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/7dd1f9aaa6aa29df5f9c183d90a43ec7bf7090ca871a5476da9fc1890f495592.jpg)

![95d428466018248d6cb2f4b8f783afed77810c90cc58cdbdbcab7b16f9e194ee.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/95d428466018248d6cb2f4b8f783afed77810c90cc58cdbdbcab7b16f9e194ee.jpg)

![a51870da634a819458560e17ae32a3bccd1cf6d8d4ccc4a8fe2dba8df8257dda.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/a51870da634a819458560e17ae32a3bccd1cf6d8d4ccc4a8fe2dba8df8257dda.jpg)

![d057bdfb5ca186297c52216211b79243f691c0ce52315a9a6292cfe64c67f8f3.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/d057bdfb5ca186297c52216211b79243f691c0ce52315a9a6292cfe64c67f8f3.jpg)

![d8d841440f05743831e53041909d507bebb56e70a88e2dc10bb0e3a1833f4994.jpg](../emnlp_results/304_VideoEraser_%20Concept%20Erasure%20in%20Text-to-Video%20Diffusion%20Models/tables/d8d841440f05743831e53041909d507bebb56e70a88e2dc10bb0e3a1833f4994.jpg)

## Diagram-Driven Course Questions Generation


### Images

![1385088838e6839f07d6171504a0fc94c2c81a637313b2e1aebb38e82e5fbd54.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/images/1385088838e6839f07d6171504a0fc94c2c81a637313b2e1aebb38e82e5fbd54.jpg)

![3e23d8cb2d247296d491ce1c14670149edbac29213cf70b930e10b6839a9a98b.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/images/3e23d8cb2d247296d491ce1c14670149edbac29213cf70b930e10b6839a9a98b.jpg)

![4da36abebbeddeea0c2c45f71505ccb44fa220d01e3329ffa1278dee578b8f8f.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/images/4da36abebbeddeea0c2c45f71505ccb44fa220d01e3329ffa1278dee578b8f8f.jpg)

![71a43f398d2b335187e9da11d33880f3a47360199ce5d33813de8577777da920.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/images/71a43f398d2b335187e9da11d33880f3a47360199ce5d33813de8577777da920.jpg)

![7e7f8985b3d50decf437f444baea5873e29597447862b918d12316f3117e9450.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/images/7e7f8985b3d50decf437f444baea5873e29597447862b918d12316f3117e9450.jpg)

![8355831e80db8bd4a3a24cad6215f73b11d1a323af53ffa865683376cd0745c3.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/images/8355831e80db8bd4a3a24cad6215f73b11d1a323af53ffa865683376cd0745c3.jpg)

![9602dfaf9d1d93559b5a37cc8686b19f904f16007682a6b1b5869d397f1f68fb.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/images/9602dfaf9d1d93559b5a37cc8686b19f904f16007682a6b1b5869d397f1f68fb.jpg)

![be002020f5d13465f09d12517bb33ec55215e89ee5eb3c1d05bbcaaf437440fa.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/images/be002020f5d13465f09d12517bb33ec55215e89ee5eb3c1d05bbcaaf437440fa.jpg)

![f21c85405601672b0949798e588a10760800cc318728739000f2bc6ba88978ee.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/images/f21c85405601672b0949798e588a10760800cc318728739000f2bc6ba88978ee.jpg)

### Tables

![3612e981c4df800cad55f8896cd98de44631579844aed18b1be15e5f64319884.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/tables/3612e981c4df800cad55f8896cd98de44631579844aed18b1be15e5f64319884.jpg)

![6141f1e801475f5d278209f14510a2383630003a67bb38ffaf3fa5e81e5595d4.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/tables/6141f1e801475f5d278209f14510a2383630003a67bb38ffaf3fa5e81e5595d4.jpg)

![ad40c6ba8404cfd152b71333c0d76edbd85e6fd434616b7f1c26b671e216682c.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/tables/ad40c6ba8404cfd152b71333c0d76edbd85e6fd434616b7f1c26b671e216682c.jpg)

![cf86fc1b2391b1732f7520b8c4961b05a413fb9cd4ec37ffeeaee4a6c883cae8.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/tables/cf86fc1b2391b1732f7520b8c4961b05a413fb9cd4ec37ffeeaee4a6c883cae8.jpg)

![e4a6555d2cdfce1b91e3b0693a29c023c6d1d9810e1002765162fda487d8d487.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/tables/e4a6555d2cdfce1b91e3b0693a29c023c6d1d9810e1002765162fda487d8d487.jpg)

![ee122d5d149bee753f5de9ff7b80ac23d7b1b829cbf7a64b6ff58d01df592c04.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/tables/ee122d5d149bee753f5de9ff7b80ac23d7b1b829cbf7a64b6ff58d01df592c04.jpg)

![efd14c3ea0884d05a730b390d2457ab3fe75cc159d0554877b800137c4ec343a.jpg](../emnlp_results/305_Diagram-Driven%20Course%20Questions%20Generation/tables/efd14c3ea0884d05a730b390d2457ab3fe75cc159d0554877b800137c4ec343a.jpg)

## ECC: An Emotion-Cause Conversation Dataset for Empathy Response


### Images

![3be0f98a6c4c0140a19c96c42c9c5dd5175273b11308c6818dea72436cf61199.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/images/3be0f98a6c4c0140a19c96c42c9c5dd5175273b11308c6818dea72436cf61199.jpg)

![42df940052c518cb10a62343a5eb5c2ee195df77b4034757e2e2987f14430a1a.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/images/42df940052c518cb10a62343a5eb5c2ee195df77b4034757e2e2987f14430a1a.jpg)

![c8672107b676148b73cebe480dc9a03b8cc3d1e25dd8495ea952762f4c8eea6f.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/images/c8672107b676148b73cebe480dc9a03b8cc3d1e25dd8495ea952762f4c8eea6f.jpg)

![d18a79ee5effb911b4fc3c4eedfc193077734fae513d2842dcc8e2d83649a160.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/images/d18a79ee5effb911b4fc3c4eedfc193077734fae513d2842dcc8e2d83649a160.jpg)

![e65bde28917ad8c4ff84555c7a7d0d1c8c4c089d96db07c68063e409d36c301e.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/images/e65bde28917ad8c4ff84555c7a7d0d1c8c4c089d96db07c68063e409d36c301e.jpg)

### Tables

![00854587a51d3ac2c77870fa2d8cd07149b559e1601a74db1f095fced929c5a1.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/00854587a51d3ac2c77870fa2d8cd07149b559e1601a74db1f095fced929c5a1.jpg)

![06f10780b2fa63b6ebb80f5aeb3eba5224cc91ce6660af2e6b7f176d5ef1ece2.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/06f10780b2fa63b6ebb80f5aeb3eba5224cc91ce6660af2e6b7f176d5ef1ece2.jpg)

![1d22b4d7037c259cf1209337fef968a01e5b2798c79a7a65d8bbd74ec5f44188.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/1d22b4d7037c259cf1209337fef968a01e5b2798c79a7a65d8bbd74ec5f44188.jpg)

![228bc6b8fce6628eeee4f7545c8fdeecc5126764b5b372260986bcdd9bb2ae13.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/228bc6b8fce6628eeee4f7545c8fdeecc5126764b5b372260986bcdd9bb2ae13.jpg)

![22f4de03af0f72496406651fac2123d539be4a0679c14b3807cc7f5ba951965b.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/22f4de03af0f72496406651fac2123d539be4a0679c14b3807cc7f5ba951965b.jpg)

![2b306ff65ffad36da63c7c386131648f44d04ce31eb0262351a9983b33225d32.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/2b306ff65ffad36da63c7c386131648f44d04ce31eb0262351a9983b33225d32.jpg)

![30b7b6fc653407a9f39baab64de17238375b8770ed6e8824354a6ebd556f9ead.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/30b7b6fc653407a9f39baab64de17238375b8770ed6e8824354a6ebd556f9ead.jpg)

![3c54d992833870a66ca7a6d776bfeb2397a6c0d36e9f2c7b88ff9783efdcf97e.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/3c54d992833870a66ca7a6d776bfeb2397a6c0d36e9f2c7b88ff9783efdcf97e.jpg)

![3fc7aa4eb3e9c085030dfee3f044f421904f85cc6e13d9aff97b26f59115a8a7.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/3fc7aa4eb3e9c085030dfee3f044f421904f85cc6e13d9aff97b26f59115a8a7.jpg)

![54a168f8fe1ee59b32f2ea100a49d8cdfb846fcc859314672a2237280df69c36.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/54a168f8fe1ee59b32f2ea100a49d8cdfb846fcc859314672a2237280df69c36.jpg)

![699029fcdccbfc6540bbea56097544c0cf1109d59d6198a673ea53066fd0ae71.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/699029fcdccbfc6540bbea56097544c0cf1109d59d6198a673ea53066fd0ae71.jpg)

![6998899f7c9cf8beae7b19e71443233287fca9684aca837848479db965ba8779.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/6998899f7c9cf8beae7b19e71443233287fca9684aca837848479db965ba8779.jpg)

![6dd3aba1d3c28e0a6b189623ea1f69df2ab0b9971ef9b001c522b7bbfcdb272a.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/6dd3aba1d3c28e0a6b189623ea1f69df2ab0b9971ef9b001c522b7bbfcdb272a.jpg)

![857611260008d1a7b059b43357732c563d13e306738513c787022877f05bf070.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/857611260008d1a7b059b43357732c563d13e306738513c787022877f05bf070.jpg)

![9fc5bb436aeb7448e25deba16b78154fc2675c529c2394b17f8d9632ce2512f6.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/9fc5bb436aeb7448e25deba16b78154fc2675c529c2394b17f8d9632ce2512f6.jpg)

![d1cf1c6499fcfcd9e81f0c45eafd1ac5773366234c0e146bec9288936d87b028.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/d1cf1c6499fcfcd9e81f0c45eafd1ac5773366234c0e146bec9288936d87b028.jpg)

![f9b1fcd146175a1ccd72fbf3a4cb7a7fed0661f017389f3589976af8ee0d129e.jpg](../emnlp_results/306_ECC_%20An%20Emotion-Cause%20Conversation%20Dataset%20for%20Empathy%20Response/tables/f9b1fcd146175a1ccd72fbf3a4cb7a7fed0661f017389f3589976af8ee0d129e.jpg)

## ThoughtProbe: Classifier-GuidedLLMThought Space Exploration via Probing Representations


### Images

![03ade53433d5b4d56b5a8dce798e999b6e98b8c95386bbe7f7f70f6013c7aec8.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/03ade53433d5b4d56b5a8dce798e999b6e98b8c95386bbe7f7f70f6013c7aec8.jpg)

![0c1a19e17d40e0c505f6a1e707e44d18788357149d4ce3886cb24ebe6e8be5fe.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/0c1a19e17d40e0c505f6a1e707e44d18788357149d4ce3886cb24ebe6e8be5fe.jpg)

![11dc32a551ca020fc4ca51756c89d8178c39977e6bc22b1e0de537280f485d15.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/11dc32a551ca020fc4ca51756c89d8178c39977e6bc22b1e0de537280f485d15.jpg)

![1325617afe413826753977f7672b8367899dfe54d723f1c03e76e028f139a61b.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/1325617afe413826753977f7672b8367899dfe54d723f1c03e76e028f139a61b.jpg)

![16397072c9d2c01a9ba2c43f11c22e73f518d6d6b8e8b37bd25b5b2d263ea6c5.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/16397072c9d2c01a9ba2c43f11c22e73f518d6d6b8e8b37bd25b5b2d263ea6c5.jpg)

![18e4d1a82763e09bc76686b29aa7d3ad8aa7016ad86f50685cfcabd7f35d3b0d.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/18e4d1a82763e09bc76686b29aa7d3ad8aa7016ad86f50685cfcabd7f35d3b0d.jpg)

![19423930e4ed58dd4f41f714e99f10d0f822911e8b67a10c8f889272b9e213fe.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/19423930e4ed58dd4f41f714e99f10d0f822911e8b67a10c8f889272b9e213fe.jpg)

![1976dc3a3c82a88e0918173ff6e29228ae57f93bac2a062cfa0de852b65c5d71.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/1976dc3a3c82a88e0918173ff6e29228ae57f93bac2a062cfa0de852b65c5d71.jpg)

![23029765b12dd1a1677461b7cc2172e067cddcca8b4073ee93ceb40778d65cc7.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/23029765b12dd1a1677461b7cc2172e067cddcca8b4073ee93ceb40778d65cc7.jpg)

![3cbbd1b73787e0aeb37ffca55a5163bef51e52e199afa3ff79818aeaa02009fa.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/3cbbd1b73787e0aeb37ffca55a5163bef51e52e199afa3ff79818aeaa02009fa.jpg)

![62610d47548b35be62b8d1c83dfb9d856ab01bc2d12526586aaa87dfafbdca82.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/62610d47548b35be62b8d1c83dfb9d856ab01bc2d12526586aaa87dfafbdca82.jpg)

![8f05d9972bf11f704661f2ed9323f646ec18601ae670d55d776eea91cea7b0f1.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/8f05d9972bf11f704661f2ed9323f646ec18601ae670d55d776eea91cea7b0f1.jpg)

![a681eb9b9d283bb70de9fff12b984c72ccb7a69ec0ed7a03d0e4324820d06828.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/a681eb9b9d283bb70de9fff12b984c72ccb7a69ec0ed7a03d0e4324820d06828.jpg)

![d3dce673716bffb4b238e63a305f0a475cab9486d1e34a1fab5fca96ae693d32.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/d3dce673716bffb4b238e63a305f0a475cab9486d1e34a1fab5fca96ae693d32.jpg)

![ef427381be42145245da4146fe932f113c2a4f99cc46867388402fb42e1aef63.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/images/ef427381be42145245da4146fe932f113c2a4f99cc46867388402fb42e1aef63.jpg)

### Tables

![119b205824fe6ddbeeda1f159317c3eb14eb1a476f575f6adcd01b0a53cf884b.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/tables/119b205824fe6ddbeeda1f159317c3eb14eb1a476f575f6adcd01b0a53cf884b.jpg)

![58f59ea5a35f38f27f6633a7a12d1328db5d63bb858974a88d1038bf4bd92a20.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/tables/58f59ea5a35f38f27f6633a7a12d1328db5d63bb858974a88d1038bf4bd92a20.jpg)

![afb286f246f9d4c5e211f041732616737bf2bba525dd081004615c88e18e1bb8.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/tables/afb286f246f9d4c5e211f041732616737bf2bba525dd081004615c88e18e1bb8.jpg)

![facf58773b972051884c7bbe9da9836f7672c9eecdcbccbe1232e39a130caf24.jpg](../emnlp_results/307_ThoughtProbe_%20Classifier-GuidedLLMThought%20Space%20Exploration%20via%20Probing%20Representations/tables/facf58773b972051884c7bbe9da9836f7672c9eecdcbccbe1232e39a130caf24.jpg)

## JOLT-SQL: Joint Loss Tuning of Text-to-SQLwith Confusion-aware Noisy Schema Sampling


### Images

![415a3ed25e75cda4194af707ff0c195ce0f10b431fdac07d7b59b503e212e404.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/images/415a3ed25e75cda4194af707ff0c195ce0f10b431fdac07d7b59b503e212e404.jpg)

![524b3d9532a769629cb9e9cbc74930000eba0f269e81547189cbe95e479575bf.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/images/524b3d9532a769629cb9e9cbc74930000eba0f269e81547189cbe95e479575bf.jpg)

![7a8a1ae087667a32571917f15742f6f7c09b5a5ea9d0ccc438e1b2cd4667ba1e.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/images/7a8a1ae087667a32571917f15742f6f7c09b5a5ea9d0ccc438e1b2cd4667ba1e.jpg)

![8e2b59a11658597525d6f17f76863385d5f671a5e937308619e946408aab1417.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/images/8e2b59a11658597525d6f17f76863385d5f671a5e937308619e946408aab1417.jpg)

![b1a0e43b828fae07d317aef453d6118cd1ef3b2efc7be495ae695ae601c0b2bb.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/images/b1a0e43b828fae07d317aef453d6118cd1ef3b2efc7be495ae695ae601c0b2bb.jpg)

### Tables

![07b0339ad28c98046d8219e746f336a149978c24958f1a9facb6e7b57af14d45.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/tables/07b0339ad28c98046d8219e746f336a149978c24958f1a9facb6e7b57af14d45.jpg)

![0fdf02d72c2f753b28b9739dee47ebacbbbe0f00e66c4d1b16d9875279fc506b.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/tables/0fdf02d72c2f753b28b9739dee47ebacbbbe0f00e66c4d1b16d9875279fc506b.jpg)

![41de9d2a19aed851b7f5a1929ee0bf440b2459472f72202d3bbb061870487f84.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/tables/41de9d2a19aed851b7f5a1929ee0bf440b2459472f72202d3bbb061870487f84.jpg)

![55edbb68879ea083b8c9579ecc087f64de7bb5c2fe71bf0029b2093583da0bce.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/tables/55edbb68879ea083b8c9579ecc087f64de7bb5c2fe71bf0029b2093583da0bce.jpg)

![57f615e2c2a3ecddf2926262c825351c924f547c65a458d9d14eff38011b758f.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/tables/57f615e2c2a3ecddf2926262c825351c924f547c65a458d9d14eff38011b758f.jpg)

![6076deaa5534e3785efc4aaa7b6bf4abdbe1506d709a2c294f2aa53eb89cdaab.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/tables/6076deaa5534e3785efc4aaa7b6bf4abdbe1506d709a2c294f2aa53eb89cdaab.jpg)

![69c3359d2b8da2cefe57b8d1f22d50ff4e78671b4729722d9769dd86c6967cd0.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/tables/69c3359d2b8da2cefe57b8d1f22d50ff4e78671b4729722d9769dd86c6967cd0.jpg)

![6e155d401d8bf8c689577f791e7c3c3849ef4c7772fe1e4b76c103550fc0c451.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/tables/6e155d401d8bf8c689577f791e7c3c3849ef4c7772fe1e4b76c103550fc0c451.jpg)

![8e1d61333b46ba04604dff0768210dcc4c4800cd9a8ae297bb99534aef4b8a6c.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/tables/8e1d61333b46ba04604dff0768210dcc4c4800cd9a8ae297bb99534aef4b8a6c.jpg)

![b6ed70344df8ad30b7266f3588e2a6e35f26c150e53e32a6c7c6d993aac57c04.jpg](../emnlp_results/308_JOLT-SQL_%20Joint%20Loss%20Tuning%20of%20Text-to-SQLwith%20Confusion-aware%20Noisy%20Schema%20Sampling/tables/b6ed70344df8ad30b7266f3588e2a6e35f26c150e53e32a6c7c6d993aac57c04.jpg)

## DMDTEval: An Evaluation and Analysis ofLLMs on Disambiguation in Multi-domain Translation


### Images

![01a3ad55961d82530e06ba26c346f93bd675ee1e24170e8dd5d0af090c33b458.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/images/01a3ad55961d82530e06ba26c346f93bd675ee1e24170e8dd5d0af090c33b458.jpg)

![25892bcb296ff47c225530ba63b300dfe7248fb009da59163f4a5540d7390fab.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/images/25892bcb296ff47c225530ba63b300dfe7248fb009da59163f4a5540d7390fab.jpg)

![6930c21089f7c376899134e00ced941d6cb670087679b7d4a0e0434478fc2674.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/images/6930c21089f7c376899134e00ced941d6cb670087679b7d4a0e0434478fc2674.jpg)

![c63069becbfa48685a8f0ac681be77b72d517b72202b17d618b1470df79c1c06.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/images/c63069becbfa48685a8f0ac681be77b72d517b72202b17d618b1470df79c1c06.jpg)

![c6889985931ffcb188ef8862c4eef22c21b8545335f0d22d4f92f8db6043d1ea.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/images/c6889985931ffcb188ef8862c4eef22c21b8545335f0d22d4f92f8db6043d1ea.jpg)

![d200decf5eb9d8b9569ed87637c91bb1fdb079eb242245ae518e7b87fed5e38f.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/images/d200decf5eb9d8b9569ed87637c91bb1fdb079eb242245ae518e7b87fed5e38f.jpg)

![e782e126ed6de3f61fb485ddc8560845f6f046685f38651666a68eb5f31faa0a.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/images/e782e126ed6de3f61fb485ddc8560845f6f046685f38651666a68eb5f31faa0a.jpg)

### Tables

![109f46ccaf3d5a31d2897edbe15bf280d5121a3d4ce68d23c54f800f7325057d.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/109f46ccaf3d5a31d2897edbe15bf280d5121a3d4ce68d23c54f800f7325057d.jpg)

![2a5c8485562cac1fb6cb552f594d55e36b6e18c6948e52c8da7dee8c363c557c.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/2a5c8485562cac1fb6cb552f594d55e36b6e18c6948e52c8da7dee8c363c557c.jpg)

![431a907b856793c1ef71af98a9a9ed3a60530d84e68692a84823abcd2895b5b3.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/431a907b856793c1ef71af98a9a9ed3a60530d84e68692a84823abcd2895b5b3.jpg)

![481af071683b7ea3be09e7f9c2efbde1a580239ec31cb0df76d29d30bf670ca6.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/481af071683b7ea3be09e7f9c2efbde1a580239ec31cb0df76d29d30bf670ca6.jpg)

![5b8e9e31d6f43dad1912c587c9470c88fd5e054daf6362a9d561eea0c2fb679b.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/5b8e9e31d6f43dad1912c587c9470c88fd5e054daf6362a9d561eea0c2fb679b.jpg)

![607441fcee96dab99302161f3b811c8da222a6f0f83bbda030275c85e7954809.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/607441fcee96dab99302161f3b811c8da222a6f0f83bbda030275c85e7954809.jpg)

![7f90fe3ba7b3ba8543017cd28728c35d2611b9a1c9c2ab926d9b6e26e87e8a15.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/7f90fe3ba7b3ba8543017cd28728c35d2611b9a1c9c2ab926d9b6e26e87e8a15.jpg)

![7fccfea8811996c9fd6239ae1de524d35698ccf8bfb416c7692c69ebaec46d08.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/7fccfea8811996c9fd6239ae1de524d35698ccf8bfb416c7692c69ebaec46d08.jpg)

![823084ab8beacd2ed3085a386a636953671cbaf3d3018aaed47c7a8e90c4b998.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/823084ab8beacd2ed3085a386a636953671cbaf3d3018aaed47c7a8e90c4b998.jpg)

![82d3e404981a3a2458453d01f60393f6224ee3c1c6ee6af5e4acb6e21f8a8918.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/82d3e404981a3a2458453d01f60393f6224ee3c1c6ee6af5e4acb6e21f8a8918.jpg)

![860a5126c2ba988fd382e57873c37b24d5c7fcd729693219014de4e46f688869.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/860a5126c2ba988fd382e57873c37b24d5c7fcd729693219014de4e46f688869.jpg)

![a92becf85e1bb4d74d03833a2fb7d810926f25a02aeb85493ad385c69acac43a.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/a92becf85e1bb4d74d03833a2fb7d810926f25a02aeb85493ad385c69acac43a.jpg)

![d4a7a94ec4ed924122c287c89dd4cfb219c88cf71b65bd469a708886b0a97a6b.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/d4a7a94ec4ed924122c287c89dd4cfb219c88cf71b65bd469a708886b0a97a6b.jpg)

![d7e4c1565aa2774c6a96b728eb4db953964707a9991a0fbbf54f36ff5d265cfa.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/d7e4c1565aa2774c6a96b728eb4db953964707a9991a0fbbf54f36ff5d265cfa.jpg)

![ed4e263adb088d82b691ea556b0d64957dfbe034075e91b2d68d38f71ec7496c.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/ed4e263adb088d82b691ea556b0d64957dfbe034075e91b2d68d38f71ec7496c.jpg)

![f1bac73c3d4c08e006dc7724832aa9baf33ddf9ef6b254d6f9d078ed9d8d094b.jpg](../emnlp_results/309_DMDTEval_%20An%20Evaluation%20and%20Analysis%20ofLLMs%20on%20Disambiguation%20in%20Multi-domain%20Translation/tables/f1bac73c3d4c08e006dc7724832aa9baf33ddf9ef6b254d6f9d078ed9d8d094b.jpg)

## SciRIFF: A Resource to Enhance Language Model Instruction-Following over Scientific Literature

### Images

![072cedfd08fa7703345a0d8d2ba8b5160c393bc002ea0c7bebe856eed143f37e.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/images/072cedfd08fa7703345a0d8d2ba8b5160c393bc002ea0c7bebe856eed143f37e.jpg)

![07575e5106e68e63ad792978cb1aa44db6ca50e9a7d1e8b0c4d60c4e7c043ffb.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/images/07575e5106e68e63ad792978cb1aa44db6ca50e9a7d1e8b0c4d60c4e7c043ffb.jpg)

![2fb411cbcb05ccfaad5031cf9b49cbe19edd7a682456d6c890b2b3f3d83b7385.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/images/2fb411cbcb05ccfaad5031cf9b49cbe19edd7a682456d6c890b2b3f3d83b7385.jpg)

![42d4d5dc87f858af06a367f0437c2546bb715300b657ee7c6c8324542e8302ff.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/images/42d4d5dc87f858af06a367f0437c2546bb715300b657ee7c6c8324542e8302ff.jpg)

![a55fc602b775c347ee234facbd6144ffc51efc640bc4e786d2ba03503d4a9420.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/images/a55fc602b775c347ee234facbd6144ffc51efc640bc4e786d2ba03503d4a9420.jpg)

![a812170aa0eae3f74b1a4cd2862797cdbf66c1a6d6bc5d3be594ac90dc40d1c4.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/images/a812170aa0eae3f74b1a4cd2862797cdbf66c1a6d6bc5d3be594ac90dc40d1c4.jpg)

![c4231c29ad2082aef827fe5197def2cb7c3008a936482f8850d86844c3dc8c45.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/images/c4231c29ad2082aef827fe5197def2cb7c3008a936482f8850d86844c3dc8c45.jpg)

### Tables

![2a64e16ceef2e02749763c8143d20e050b143b26f999098be0f1963f4ff13789.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/tables/2a64e16ceef2e02749763c8143d20e050b143b26f999098be0f1963f4ff13789.jpg)

![2d942e173f1cdd025c832309c6ea491b26ddd1355fcfb28de74dbe2fe2465815.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/tables/2d942e173f1cdd025c832309c6ea491b26ddd1355fcfb28de74dbe2fe2465815.jpg)

![35acda5c2f7651a5712faa03c5815a83fd7a536e7b8e37fbf29b5fcf4a4305f2.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/tables/35acda5c2f7651a5712faa03c5815a83fd7a536e7b8e37fbf29b5fcf4a4305f2.jpg)

![65ba4af6409a81e8d74a34da7105c637b5f7136f1a8593b1a3e447e531fdc654.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/tables/65ba4af6409a81e8d74a34da7105c637b5f7136f1a8593b1a3e447e531fdc654.jpg)

![8b10f658558f9809a9c0664b4fd43f680264a0a697968bb2280e234d1ba85998.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/tables/8b10f658558f9809a9c0664b4fd43f680264a0a697968bb2280e234d1ba85998.jpg)

![96cb2e4f335e52a3ccd398d45d6b2d5bd2c3a36ae10f00ffb2a0e6f05a9b998f.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/tables/96cb2e4f335e52a3ccd398d45d6b2d5bd2c3a36ae10f00ffb2a0e6f05a9b998f.jpg)

![acdae455f12bc7cd91e743f40cd98dbd06d3539a0353132082b3246d7448c62e.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/tables/acdae455f12bc7cd91e743f40cd98dbd06d3539a0353132082b3246d7448c62e.jpg)

![aff24d142628e95de874a0e40ea2949d2dc59c94237e74ff7cf1073a207625ae.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/tables/aff24d142628e95de874a0e40ea2949d2dc59c94237e74ff7cf1073a207625ae.jpg)

![d9f766700c0611adf97698dc4d2fdf15284bcea70e97980096ad157a5de51555.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/tables/d9f766700c0611adf97698dc4d2fdf15284bcea70e97980096ad157a5de51555.jpg)

![fc85106727d7a1b5cd238ed22df7d085020e4deb5f76974a08db1cc4e354b5c7.jpg](../emnlp_results/310_SciRIFF_%20A%20Resource%20to%20Enhance%20Language%20Model%20Instruction-Following%20over%20Scientific%20Literature/tables/fc85106727d7a1b5cd238ed22df7d085020e4deb5f76974a08db1cc4e354b5c7.jpg)
