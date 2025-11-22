# EMNLP 2025 Main Conference Papers

**Summary:** 30 papers with extracted content:
- 📊 Total images: 14618
- 📋 Total tables: 17648
- 📄 Total files: 32266

*Note: Equations have been filtered out and are not included.*

---

# EMNLP 2025 Main Papers - Part 12 of 60

## 目录 (Table of Contents)

1. [Invisible Entropy: Towards Safe and Efficient Low-EntropyLLMWatermarking](#Invisible-Entropy-Towards-Safe-and-Efficient-Low-EntropyLLMWatermarking)
2. [Measuring Bias or Measuring the Task: Understanding the Brittle Nature ofLLMGender Biases](#Measuring-Bias-or-Measuring-the-Task-Understanding-the-Brittle-Nature-ofLLMGender-Biases)
3. [Alignment-Augmented Speculative Decoding with Alignment Sampling and Conditional Verification](#Alignment-Augmented-Speculative-Decoding-with-Alignment-Sampling-and-Conditional-Verification)
4. [ViLBench: A Suite for Vision-Language Process Reward Modeling](#ViLBench-A-Suite-for-Vision-Language-Process-Reward-Modeling)
5. [Keep Security! Benchmarking Security Policy Preservation in Large Language Model Contexts Against Indirect Attacks in Question Answering](#Keep-Security-Benchmarking-Security-Policy-Preservation-in-Large-Language-Model-Contexts-Against-Indirect-Attacks-in-Question-Answering)
6. [Route Sparse Autoencoder to Interpret Large Language Models](#Route-Sparse-Autoencoder-to-Interpret-Large-Language-Models)
7. [BTS: Harmonizing Specialized Experts into a GeneralistLLM](#BTS-Harmonizing-Specialized-Experts-into-a-GeneralistLLM)
8. [CoCoA: Confidence- and Context-Aware Adaptive Decoding for Resolving Knowledge Conflicts in Large Language Models](#CoCoA-Confidence-and-Context-Aware-Adaptive-Decoding-for-Resolving-Knowledge-Conflicts-in-Large-Language-Models)
9. [R-Bind: Unified Enhancement of Attribute and Relation Binding in Text-to-Image Diffusion Models](#R-Bind-Unified-Enhancement-of-Attribute-and-Relation-Binding-in-Text-to-Image-Diffusion-Models)
10. [Middo: Model-Informed Dynamic Data Optimization for EnhancedLLMFine-Tuning via Closed-Loop Learning](#Middo-Model-Informed-Dynamic-Data-Optimization-for-EnhancedLLMFine-Tuning-via-Closed-Loop-Learning)
11. [Information Integration in Large Language Models is Gated by Linguistic Structural Markers](#Information-Integration-in-Large-Language-Models-is-Gated-by-Linguistic-Structural-Markers)
12. [Why and HowLLMs Benefit from Knowledge Introspection in Commonsense Reasoning](#Why-and-HowLLMs-Benefit-from-Knowledge-Introspection-in-Commonsense-Reasoning)
13. [GraDaSE: Graph-Based Dataset Search with Examples](#GraDaSE-Graph-Based-Dataset-Search-with-Examples)
14. [Confidence-guided Refinement Reasoning for Zero-shot Question Answering](#Confidence-guided-Refinement-Reasoning-for-Zero-shot-Question-Answering)
15. [DICE: Structured Reasoning inLLMs throughSLM-Guided Chain-of-Thought Correction](#DICE-Structured-Reasoning-inLLMs-throughSLM-Guided-Chain-of-Thought-Correction)
16. [CTCC: A Robust and Stealthy Fingerprinting Framework for Large Language Models via Cross-Turn Contextual Correlation Backdoor](#CTCC-A-Robust-and-Stealthy-Fingerprinting-Framework-for-Large-Language-Models-via-Cross-Turn-Contextual-Correlation-Backdoor)
17. [Realistic Training Data Generation and Rule Enhanced Decoding inLLMforNameGuess](#Realistic-Training-Data-Generation-and-Rule-Enhanced-Decoding-inLLMforNameGuess)
18. [EverTracer: Hunting Stolen Large Language Models via Stealthy and Robust Probabilistic Fingerprint](#EverTracer-Hunting-Stolen-Large-Language-Models-via-Stealthy-and-Robust-Probabilistic-Fingerprint)
19. [Selective Preference Optimization via Token-Level Reward Function Estimation](#Selective-Preference-Optimization-via-Token-Level-Reward-Function-Estimation)
20. [Arena-lite: Efficient and Reliable Large Language Model Evaluation via Tournament-Based Direct Comparisons](#Arena-lite-Efficient-and-Reliable-Large-Language-Model-Evaluation-via-Tournament-Based-Direct-Comparisons)
21. [Addressing Tokenization Inconsistency in Steganography and Watermarking Based on Large Language Models](#Addressing-Tokenization-Inconsistency-in-Steganography-and-Watermarking-Based-on-Large-Language-Models)
22. [ExeCoder: Empowering Large Language Models with Executability Representation for Code Translation](#ExeCoder-Empowering-Large-Language-Models-with-Executability-Representation-for-Code-Translation)
23. [TableEval: A Real-World Benchmark for Complex, Multilingual, and Multi-Structured Table Question Answering](#TableEval-A-Real-World-Benchmark-for-Complex-Multilingual-and-Multi-Structured-Table-Question-Answering)
24. [NOVA-63: Native Omni-lingual Versatile Assessments of 63 Disciplines](#NOVA-63-Native-Omni-lingual-Versatile-Assessments-of-63-Disciplines)
25. [InfoGain-RAG: Boosting Retrieval-Augmented Generation through Document Information Gain-based Reranking and Filtering](#InfoGain-RAG-Boosting-Retrieval-Augmented-Generation-through-Document-Information-Gain-based-Reranking-and-Filtering)
26. [SpecVLM: Enhancing Speculative Decoding of VideoLLMs via Verifier-Guided Token Pruning](#SpecVLM-Enhancing-Speculative-Decoding-of-VideoLLMs-via-Verifier-Guided-Token-Pruning)
27. [What Do Indonesians Really Need from Language Technology? A Nationwide Survey](#What-Do-Indonesians-Really-Need-from-Language-Technology-A-Nationwide-Survey)
28. [LEO-MINI: An Efficient Multimodal Large Language Model using Conditional Token Reduction and Mixture of Multi-Modal Experts](#LEO-MINI-An-Efficient-Multimodal-Large-Language-Model-using-Conditional-Token-Reduction-and-Mixture-of-Multi-Modal-Experts)
29. [Confounding Factors in Relating Model Performance to Morphology](#Confounding-Factors-in-Relating-Model-Performance-to-Morphology)
30. [Context-Aware Membership Inference Attacks against Pre-trained Large Language Models](#Context-Aware-Membership-Inference-Attacks-against-Pre-trained-Large-Language-Models)

---


## Invisible Entropy: Towards Safe and Efficient Low-EntropyLLMWatermarking

### Images

![196fdaea634388b65eb9a023a51e10a7856234ff48b616a48020168f8eda17d8.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/images/196fdaea634388b65eb9a023a51e10a7856234ff48b616a48020168f8eda17d8.jpg)

![56f94504f1fb2f4be17e419107e2e3b1df34b4efaa6651923b0b5aff0b0a4aaa.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/images/56f94504f1fb2f4be17e419107e2e3b1df34b4efaa6651923b0b5aff0b0a4aaa.jpg)

![65601ee1b565993de2a53b8519479b032e8ac1d49c21dcc262bdaa2e39ac7ae5.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/images/65601ee1b565993de2a53b8519479b032e8ac1d49c21dcc262bdaa2e39ac7ae5.jpg)

![7f4e15d949ddb6d091fb9add6141d9caa5d243d746c011ddf5495a827f6af792.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/images/7f4e15d949ddb6d091fb9add6141d9caa5d243d746c011ddf5495a827f6af792.jpg)

![8bf4396aa6f7add0bc1e7ad3616a12c8af1cca27eee0f675416b6950ad21baca.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/images/8bf4396aa6f7add0bc1e7ad3616a12c8af1cca27eee0f675416b6950ad21baca.jpg)

![8ded36ebf92a882cb805093535285888d922f2172f156ef3be7efaefbd5f5f7c.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/images/8ded36ebf92a882cb805093535285888d922f2172f156ef3be7efaefbd5f5f7c.jpg)

![9daebff03650d25e7c521d630f47f4a2c43640f7138d5e6caeef70cb5bd0809d.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/images/9daebff03650d25e7c521d630f47f4a2c43640f7138d5e6caeef70cb5bd0809d.jpg)

![a072906477a99202fc9f47ebb09e9a1e1dc7e320bc41812b574f55ab5a68b3ea.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/images/a072906477a99202fc9f47ebb09e9a1e1dc7e320bc41812b574f55ab5a68b3ea.jpg)

![af754558405d169c5087ed58631a36f4400f932451d419cd6fffaae4d42af4e1.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/images/af754558405d169c5087ed58631a36f4400f932451d419cd6fffaae4d42af4e1.jpg)

![ba1f076d235106a88627f6222507a7c8eadbcb86dce05711530509267a562fc3.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/images/ba1f076d235106a88627f6222507a7c8eadbcb86dce05711530509267a562fc3.jpg)

![d50404909c4792f6219823616701950fdc8d9b574fca65f66fc9546883723beb.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/images/d50404909c4792f6219823616701950fdc8d9b574fca65f66fc9546883723beb.jpg)

![f525076a961a8f1ff74b2e5b10052e9cd419bf6f141ecc9cb5d19e3ecf4ca37c.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/images/f525076a961a8f1ff74b2e5b10052e9cd419bf6f141ecc9cb5d19e3ecf4ca37c.jpg)

### Tables

![07fcafe0d851e36c74443a0dedf2b43c6038d2f314a5c759ed66d2892d2eafe7.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/07fcafe0d851e36c74443a0dedf2b43c6038d2f314a5c759ed66d2892d2eafe7.jpg)

![0a260eafc7b994b05252ecca01affbc8737f4deefffd6aceee1836669bdca237.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/0a260eafc7b994b05252ecca01affbc8737f4deefffd6aceee1836669bdca237.jpg)

![291cea1ab2d243cb8f368552dc95701247bcdd2774964182103126f59171cba6.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/291cea1ab2d243cb8f368552dc95701247bcdd2774964182103126f59171cba6.jpg)

![42568414a419027aabe129dcd597f494a60997697169b3eb804b56bf6a2eceeb.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/42568414a419027aabe129dcd597f494a60997697169b3eb804b56bf6a2eceeb.jpg)

![4baf3b569001b850662c0a1b17dbada4b07ce0f3b370ab13dc80bdc3c3b00fab.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/4baf3b569001b850662c0a1b17dbada4b07ce0f3b370ab13dc80bdc3c3b00fab.jpg)

![4cd3605d4bf9558e9d9e81febbd75ef0f4f79a3dd889938d81d442134f49c4f3.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/4cd3605d4bf9558e9d9e81febbd75ef0f4f79a3dd889938d81d442134f49c4f3.jpg)

![6249d9732e5aa1029f9457a93edadc5dfc438f06927564e553368339c92b1924.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/6249d9732e5aa1029f9457a93edadc5dfc438f06927564e553368339c92b1924.jpg)

![667e18b7bbbac9c3d488ff09ceda948af7b30be46f4c2a2c8c1eaaaef7c83227.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/667e18b7bbbac9c3d488ff09ceda948af7b30be46f4c2a2c8c1eaaaef7c83227.jpg)

![6b1aa988137bac9798ebbfd78fb0c5e598619b08bb6fb263b0f5ba959a2e6bbd.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/6b1aa988137bac9798ebbfd78fb0c5e598619b08bb6fb263b0f5ba959a2e6bbd.jpg)

![83d5f7cc33a77cb9373db79df033afe0efc2c85f83176adbc4c68a1cb7be314f.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/83d5f7cc33a77cb9373db79df033afe0efc2c85f83176adbc4c68a1cb7be314f.jpg)

![a2a34b005cbb8b5ed4d002bea9363f6b19c473d7fcd86155e3eb05b775f7c457.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/a2a34b005cbb8b5ed4d002bea9363f6b19c473d7fcd86155e3eb05b775f7c457.jpg)

![ba92b0382358e9c461670ee7d1c64ad9fafb85f2a8dad5bcb13756cb2aceb1bd.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/ba92b0382358e9c461670ee7d1c64ad9fafb85f2a8dad5bcb13756cb2aceb1bd.jpg)

![df5a777bf8399aeed3dffcd4fd7952bc4689058a33bb8bc015fa3342056a80e0.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/df5a777bf8399aeed3dffcd4fd7952bc4689058a33bb8bc015fa3342056a80e0.jpg)

![eee5b94689a37effc20d3fcdeaf498ee43b3101c21a669912d07d3b09ddcb867.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/eee5b94689a37effc20d3fcdeaf498ee43b3101c21a669912d07d3b09ddcb867.jpg)

![f621d4c59316a20a9575e936efda03b16f3101c18da5d96e2e39d55d5c2ac501.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/f621d4c59316a20a9575e936efda03b16f3101c18da5d96e2e39d55d5c2ac501.jpg)

![f91005b28cd5d91008c971838ff5c0b7f43e49d252d7bc2539fca8831f36b44b.jpg](../emnlp_results/340_LoSiA_%20Efficient%20High-Rank%20Fine-Tuning%20via%20Subnet%20Localization%20and%20Optimization/tables/f91005b28cd5d91008c971838ff5c0b7f43e49d252d7bc2539fca8831f36b44b.jpg)

## Invisible Entropy: Towards Safe and Efficient Low-EntropyLLMWatermarking


### Images

![1976af15376702066c90bea8c63049a8c94c3ca0e9b084ce32f1a47bf97ec4a8.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/images/1976af15376702066c90bea8c63049a8c94c3ca0e9b084ce32f1a47bf97ec4a8.jpg)

![370456a555d7c767c96655e071950956f20eaf6bab04d05b7238b146f921900b.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/images/370456a555d7c767c96655e071950956f20eaf6bab04d05b7238b146f921900b.jpg)

![6bfeb15dd1e5a247f377edcdbdd92fece05de8dc4473b9d759249d75f3930cac.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/images/6bfeb15dd1e5a247f377edcdbdd92fece05de8dc4473b9d759249d75f3930cac.jpg)

![950114fef09856faac0044ed214435566ed97b43ec4c68858321927a59637732.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/images/950114fef09856faac0044ed214435566ed97b43ec4c68858321927a59637732.jpg)

![bacde85ea87417f894d6cce74b886dbbfe5086d7c6018d543b4eb5f595460ab7.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/images/bacde85ea87417f894d6cce74b886dbbfe5086d7c6018d543b4eb5f595460ab7.jpg)

![f018fa069ac888cdadf0bc91ae8c2b8b454b204d9e66a944b176b7a5889e3fac.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/images/f018fa069ac888cdadf0bc91ae8c2b8b454b204d9e66a944b176b7a5889e3fac.jpg)

![f087ab76f4ccaed6a6a5b33673e92de30b7115238687e3a940b695b5d77ea074.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/images/f087ab76f4ccaed6a6a5b33673e92de30b7115238687e3a940b695b5d77ea074.jpg)

### Tables

![0148168230efefca40bc73d50f27a1e4a5ec969aa6e264db49c1de1a47ed3104.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/tables/0148168230efefca40bc73d50f27a1e4a5ec969aa6e264db49c1de1a47ed3104.jpg)

![0ff22e83b902894c8288e8621393d4046ca1cfd9b831dd82e150935455b745f4.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/tables/0ff22e83b902894c8288e8621393d4046ca1cfd9b831dd82e150935455b745f4.jpg)

![184231dab5a5abd604ff5e8c9b9f117c59cdf186d5531b74aa6fad7dd56d5183.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/tables/184231dab5a5abd604ff5e8c9b9f117c59cdf186d5531b74aa6fad7dd56d5183.jpg)

![1baf767b608b4931150ae3012a585a87618b08ad076b6cd0f1ae76f8f7d27d51.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/tables/1baf767b608b4931150ae3012a585a87618b08ad076b6cd0f1ae76f8f7d27d51.jpg)

![1c4cb86e9bec01a7badba6b2bf177fefd7cc0af39937c40741a272cbd3917649.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/tables/1c4cb86e9bec01a7badba6b2bf177fefd7cc0af39937c40741a272cbd3917649.jpg)

![56601c8cf60cc9000d7290dcc5e1eae1ed1c9fbd6ab97e0a6ab07b01751d78ec.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/tables/56601c8cf60cc9000d7290dcc5e1eae1ed1c9fbd6ab97e0a6ab07b01751d78ec.jpg)

![5ac20e38d7dd7da085410e743fc492bfc4823db7bbe8a71b5b902275444308e6.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/tables/5ac20e38d7dd7da085410e743fc492bfc4823db7bbe8a71b5b902275444308e6.jpg)

![93064ba2da26b69c0fa00ff0710f95900c318bc73ff96c4e9cef0131a4b7d0c9.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/tables/93064ba2da26b69c0fa00ff0710f95900c318bc73ff96c4e9cef0131a4b7d0c9.jpg)

![a58c8c0ca19cec8aa40ac3d614552ca8e3595adcd191e03d5897ec8eace065e7.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/tables/a58c8c0ca19cec8aa40ac3d614552ca8e3595adcd191e03d5897ec8eace065e7.jpg)

![c385477b30f0ef0ee6a8dcd9e87b1db3923e7303fbef989d255f75a463e82347.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/tables/c385477b30f0ef0ee6a8dcd9e87b1db3923e7303fbef989d255f75a463e82347.jpg)

![cbb5c621f61be33bc49f17941465abaa4208cdb7e7908f57e315520b444214ad.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/tables/cbb5c621f61be33bc49f17941465abaa4208cdb7e7908f57e315520b444214ad.jpg)

![f0a8d7713e03bd55b76774b0bf7efbcf260fcba97d5b92322b21a93319a658ce.jpg](../emnlp_results/341_Invisible%20Entropy_%20Towards%20Safe%20and%20Efficient%20Low-EntropyLLMWatermarking/tables/f0a8d7713e03bd55b76774b0bf7efbcf260fcba97d5b92322b21a93319a658ce.jpg)

## Measuring Bias or Measuring the Task: Understanding the Brittle Nature ofLLMGender Biases


### Images

![01601f69188ecb8849cd032c5a93040c34ee0c82020cbde1708aedbaa9904075.jpg](../emnlp_results/342_Measuring%20Bias%20or%20Measuring%20the%20Task_%20Understanding%20the%20Brittle%20Nature%20ofLLMGender%20Biases/images/01601f69188ecb8849cd032c5a93040c34ee0c82020cbde1708aedbaa9904075.jpg)

![09b67b8cc0cad4d8e318d6269e61d7f5f11ad161a5727b1c8de2171b3c297967.jpg](../emnlp_results/342_Measuring%20Bias%20or%20Measuring%20the%20Task_%20Understanding%20the%20Brittle%20Nature%20ofLLMGender%20Biases/images/09b67b8cc0cad4d8e318d6269e61d7f5f11ad161a5727b1c8de2171b3c297967.jpg)

![0dcf5fcc420b3789eb5bf313a9db5e640312e714bcab4966f36a327d3addc9d1.jpg](../emnlp_results/342_Measuring%20Bias%20or%20Measuring%20the%20Task_%20Understanding%20the%20Brittle%20Nature%20ofLLMGender%20Biases/images/0dcf5fcc420b3789eb5bf313a9db5e640312e714bcab4966f36a327d3addc9d1.jpg)

![4d59bdba1d134cc2a64daa558bb89975f2ae24a6af70d203013839b282d8ee33.jpg](../emnlp_results/342_Measuring%20Bias%20or%20Measuring%20the%20Task_%20Understanding%20the%20Brittle%20Nature%20ofLLMGender%20Biases/images/4d59bdba1d134cc2a64daa558bb89975f2ae24a6af70d203013839b282d8ee33.jpg)

![629a5245faca023ef70a8d48a3ef3cc5138473bfa935f93a2f6daaa3874849c9.jpg](../emnlp_results/342_Measuring%20Bias%20or%20Measuring%20the%20Task_%20Understanding%20the%20Brittle%20Nature%20ofLLMGender%20Biases/images/629a5245faca023ef70a8d48a3ef3cc5138473bfa935f93a2f6daaa3874849c9.jpg)

### Tables

![3bad282d7e90aa1c3474b17ca56bb10b30411b5b606ca9b3ea144869daede425.jpg](../emnlp_results/342_Measuring%20Bias%20or%20Measuring%20the%20Task_%20Understanding%20the%20Brittle%20Nature%20ofLLMGender%20Biases/tables/3bad282d7e90aa1c3474b17ca56bb10b30411b5b606ca9b3ea144869daede425.jpg)

![64244625a315fad805c26bc4eeb076d6859698f2f11282fe72e4fb6199c7c756.jpg](../emnlp_results/342_Measuring%20Bias%20or%20Measuring%20the%20Task_%20Understanding%20the%20Brittle%20Nature%20ofLLMGender%20Biases/tables/64244625a315fad805c26bc4eeb076d6859698f2f11282fe72e4fb6199c7c756.jpg)

![d842f61b6441b5fb31aa6718e5e0368718f8f456360fdb34807a93eae0613023.jpg](../emnlp_results/342_Measuring%20Bias%20or%20Measuring%20the%20Task_%20Understanding%20the%20Brittle%20Nature%20ofLLMGender%20Biases/tables/d842f61b6441b5fb31aa6718e5e0368718f8f456360fdb34807a93eae0613023.jpg)

![f4ab3042a4563c695e6f5f42ed51e6ef7c6b650ce582156bc097ace44f5d2437.jpg](../emnlp_results/342_Measuring%20Bias%20or%20Measuring%20the%20Task_%20Understanding%20the%20Brittle%20Nature%20ofLLMGender%20Biases/tables/f4ab3042a4563c695e6f5f42ed51e6ef7c6b650ce582156bc097ace44f5d2437.jpg)

![fa6ab510ccae45c31b6e3283a9a6f810274f313cac1823f73c6bfb5d82516e54.jpg](../emnlp_results/342_Measuring%20Bias%20or%20Measuring%20the%20Task_%20Understanding%20the%20Brittle%20Nature%20ofLLMGender%20Biases/tables/fa6ab510ccae45c31b6e3283a9a6f810274f313cac1823f73c6bfb5d82516e54.jpg)

## Alignment-Augmented Speculative Decoding with Alignment Sampling and Conditional Verification


### Images

![0a035f89f80c9e811ea626fc0b275e4de5ca8ed64d9fb82253a8d3f2e5b774d6.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/images/0a035f89f80c9e811ea626fc0b275e4de5ca8ed64d9fb82253a8d3f2e5b774d6.jpg)

![1df42728839b0d8cc627f71142e0a5481e34f23bb8535053b3014c55e236caad.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/images/1df42728839b0d8cc627f71142e0a5481e34f23bb8535053b3014c55e236caad.jpg)

![766770b218721effb45945cf94fe1db2238fef20cabb3b5e16cb7c289db3d7bb.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/images/766770b218721effb45945cf94fe1db2238fef20cabb3b5e16cb7c289db3d7bb.jpg)

![88b040ccc6fde9ef75de29b62b5fec08f91d53c3c03bf9907bf3b698bc7829b8.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/images/88b040ccc6fde9ef75de29b62b5fec08f91d53c3c03bf9907bf3b698bc7829b8.jpg)

![b61c5908cc9e8e3261031be4ee86b19b35cc87ee40ac07b1772726eb362bae6b.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/images/b61c5908cc9e8e3261031be4ee86b19b35cc87ee40ac07b1772726eb362bae6b.jpg)

### Tables

![08c87e310f512a791c34aab2ee4aa001043eef42c9a603b500fdc407bb6f2341.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/tables/08c87e310f512a791c34aab2ee4aa001043eef42c9a603b500fdc407bb6f2341.jpg)

![1021a159e857954d986d71688aba4d787100b9b69672a996952a0eb613137f95.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/tables/1021a159e857954d986d71688aba4d787100b9b69672a996952a0eb613137f95.jpg)

![10b3ae18d181315846da71ef1502af2fb3037fdaa104e84ec63228a95733a463.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/tables/10b3ae18d181315846da71ef1502af2fb3037fdaa104e84ec63228a95733a463.jpg)

![331ad61f8457bc7d86ea7f78e8f42120af0bc8fa832d04667b19bc81dca7e05a.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/tables/331ad61f8457bc7d86ea7f78e8f42120af0bc8fa832d04667b19bc81dca7e05a.jpg)

![375dfda5c7729a724872adfdef3ff0365f33cbc2716cf2cd4947c54958dd1f85.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/tables/375dfda5c7729a724872adfdef3ff0365f33cbc2716cf2cd4947c54958dd1f85.jpg)

![391914cff29d8c3bed3d63c86cd899907abaa701167be9edeadf8860caadabdb.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/tables/391914cff29d8c3bed3d63c86cd899907abaa701167be9edeadf8860caadabdb.jpg)

![42ec33f2b60b3352e7d59767cf563c14fd58d6de08ee88b926992cfa5f1610dd.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/tables/42ec33f2b60b3352e7d59767cf563c14fd58d6de08ee88b926992cfa5f1610dd.jpg)

![7e100ee9e9f886740ac1f54c2d8c20ebd741d27fc98a9281098943e84409bb01.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/tables/7e100ee9e9f886740ac1f54c2d8c20ebd741d27fc98a9281098943e84409bb01.jpg)

![f7e56fc1c4e629960a0a6c848032ca690ed24a08c1f2819dea751068073e9516.jpg](../emnlp_results/343_Alignment-Augmented%20Speculative%20Decoding%20with%20Alignment%20Sampling%20and%20Conditional%20Verification/tables/f7e56fc1c4e629960a0a6c848032ca690ed24a08c1f2819dea751068073e9516.jpg)

## ViLBench: A Suite for Vision-Language Process Reward Modeling


### Images

![021672e568f8da6062ac50888ee85186012e5653321a0814db7870f4127268d4.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/images/021672e568f8da6062ac50888ee85186012e5653321a0814db7870f4127268d4.jpg)

![0377f20ea981437f879b5693028a17f5c01367b228e6c0b75d13bcfb41bf49db.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/images/0377f20ea981437f879b5693028a17f5c01367b228e6c0b75d13bcfb41bf49db.jpg)

![154f9eb572833bcc75b600f1a7361df1b3c759e2b86b2393485e07fbc2bb3d01.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/images/154f9eb572833bcc75b600f1a7361df1b3c759e2b86b2393485e07fbc2bb3d01.jpg)

![579a297d5881387ed1302f32280d885169c6e8a518bd42861c43ea5dbe43c55f.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/images/579a297d5881387ed1302f32280d885169c6e8a518bd42861c43ea5dbe43c55f.jpg)

![5a890832778fcd113c64879a60d87378e879c7d1f55b47d675023dd08015e9ff.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/images/5a890832778fcd113c64879a60d87378e879c7d1f55b47d675023dd08015e9ff.jpg)

![8ebbe5306fd109414f063d498e5d07aa3ce0b53a368e4e3fe37a649821d397ea.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/images/8ebbe5306fd109414f063d498e5d07aa3ce0b53a368e4e3fe37a649821d397ea.jpg)

![a11d927ba16eafe5ede7ec7f5a7924b31f3749550d30bd194a17e9aec3fef209.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/images/a11d927ba16eafe5ede7ec7f5a7924b31f3749550d30bd194a17e9aec3fef209.jpg)

![a88cc963a8983e4d2b331687427ee5c4721448a4b084220cf4a0d02a48f3ee25.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/images/a88cc963a8983e4d2b331687427ee5c4721448a4b084220cf4a0d02a48f3ee25.jpg)

![c3f7ea52e46cb162476416d31b680f112ee1ce3547a0013a4eff7328ebb29c01.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/images/c3f7ea52e46cb162476416d31b680f112ee1ce3547a0013a4eff7328ebb29c01.jpg)

![d3f18b2277680e2f1b3cf5d2aa7d63de3e6f7886c72baa7cf66168c4b227e782.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/images/d3f18b2277680e2f1b3cf5d2aa7d63de3e6f7886c72baa7cf66168c4b227e782.jpg)

![db4df546a65c08f0c26b967131d2996de46b79441b0f88c0fdc8def8ac84539d.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/images/db4df546a65c08f0c26b967131d2996de46b79441b0f88c0fdc8def8ac84539d.jpg)

![e1b6e991da40c04687f7d0f2e2ec38573b0c327bd44fcf6d44eda68d1833c664.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/images/e1b6e991da40c04687f7d0f2e2ec38573b0c327bd44fcf6d44eda68d1833c664.jpg)

### Tables

![05207cd4db5ff79c93f51efec5afc3488a02e528afa13365b13e99787ada5295.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/tables/05207cd4db5ff79c93f51efec5afc3488a02e528afa13365b13e99787ada5295.jpg)

![19c38047447a7fdcf678f0a9b197c610533a2454456433f077c04e7528df062c.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/tables/19c38047447a7fdcf678f0a9b197c610533a2454456433f077c04e7528df062c.jpg)

![27fb5aa63699010ac8f6e22efce3c6ede65fd6feefabd9bf881345c9597c6d39.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/tables/27fb5aa63699010ac8f6e22efce3c6ede65fd6feefabd9bf881345c9597c6d39.jpg)

![6a5ada7abde8d99bfb703a25ade129647132648a8b67bf9463c5de94b6317c2f.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/tables/6a5ada7abde8d99bfb703a25ade129647132648a8b67bf9463c5de94b6317c2f.jpg)

![b1ab301e69f36d5b5015bb12be5019871dba1fd4f7f844f5f89f2da7410256c9.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/tables/b1ab301e69f36d5b5015bb12be5019871dba1fd4f7f844f5f89f2da7410256c9.jpg)

![b63ac66458783621a6706d8bae16c67ea62a3c5784d8f7f08cfe93e9b53124d5.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/tables/b63ac66458783621a6706d8bae16c67ea62a3c5784d8f7f08cfe93e9b53124d5.jpg)

![d0257935601d1d41a433c8d5f9d0eefd085f9f029f836813c14afe25bd4c73a0.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/tables/d0257935601d1d41a433c8d5f9d0eefd085f9f029f836813c14afe25bd4c73a0.jpg)

![de016846014d2a9768398a50e4b943c129b8aed4151d210e72eb0b82ec8e498f.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/tables/de016846014d2a9768398a50e4b943c129b8aed4151d210e72eb0b82ec8e498f.jpg)

![eb51aafd3eeb35e5ef8b82672aeada2e2f53304391f240ebb53c96769f84eebb.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/tables/eb51aafd3eeb35e5ef8b82672aeada2e2f53304391f240ebb53c96769f84eebb.jpg)

![ec7848535b38a7ee98fee6fada607888937eeca7a5425ff71baeb1bf7897f677.jpg](../emnlp_results/344_ViLBench_%20A%20Suite%20for%20Vision-Language%20Process%20Reward%20Modeling/tables/ec7848535b38a7ee98fee6fada607888937eeca7a5425ff71baeb1bf7897f677.jpg)

## Keep Security! Benchmarking Security Policy Preservation in Large Language Model Contexts Against Indirect Attacks in Question Answering


### Images

![0a970b3943dd153836a7065acdf736d9d50bc788ac538fbbd69f5f88afd0c96c.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/images/0a970b3943dd153836a7065acdf736d9d50bc788ac538fbbd69f5f88afd0c96c.jpg)

![2d054f1a8ffbfa69aebda2fa78fab463eeeb329f318326838701070e697b28b6.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/images/2d054f1a8ffbfa69aebda2fa78fab463eeeb329f318326838701070e697b28b6.jpg)

![835f04f9ed1980357f8632fac3f3fcc65591bc464c35bf7efce6682a1afeb6bc.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/images/835f04f9ed1980357f8632fac3f3fcc65591bc464c35bf7efce6682a1afeb6bc.jpg)

![901ba31d1db514f80dcd11f52a157052b7e42fc81a9ff1181eb80b57da2db634.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/images/901ba31d1db514f80dcd11f52a157052b7e42fc81a9ff1181eb80b57da2db634.jpg)

![c2d973fe43643faf5e542990db7defdfa5b75d88afb269baaec91a3de8fe8c50.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/images/c2d973fe43643faf5e542990db7defdfa5b75d88afb269baaec91a3de8fe8c50.jpg)

![c44695664adfca8bfac08af776059ed0c0e3e712693e47fbad429bea026bd04e.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/images/c44695664adfca8bfac08af776059ed0c0e3e712693e47fbad429bea026bd04e.jpg)

![cc5f8a2bfd322b9a409286c6fb9915f390316673cc9503f41ce1cee1f4689a38.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/images/cc5f8a2bfd322b9a409286c6fb9915f390316673cc9503f41ce1cee1f4689a38.jpg)

![e07526bcc69d9671d56466bdfaa21e774b9fe35aaffddc971cb2b64d05e83b40.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/images/e07526bcc69d9671d56466bdfaa21e774b9fe35aaffddc971cb2b64d05e83b40.jpg)

### Tables

![0808b241eedf525550a9a80b241a53e3c6df7f69816abb4ff28759166f63d272.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/tables/0808b241eedf525550a9a80b241a53e3c6df7f69816abb4ff28759166f63d272.jpg)

![25e39b10d2ae28949bd8b56afd5696e11ebb24f904f5bc3bb88520aa8e365ed5.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/tables/25e39b10d2ae28949bd8b56afd5696e11ebb24f904f5bc3bb88520aa8e365ed5.jpg)

![3380c78264a76c8d1d325717586f2b886976d571af0794750633e0bc3fcf09ab.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/tables/3380c78264a76c8d1d325717586f2b886976d571af0794750633e0bc3fcf09ab.jpg)

![505dd8cf55a5eeff11135d054b0e0d925dc5b47524d2fb248ff5cd39d9de607b.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/tables/505dd8cf55a5eeff11135d054b0e0d925dc5b47524d2fb248ff5cd39d9de607b.jpg)

![5e08097e96caae579aae6ff464e14f3a324b78523eab8f3ee52381a0e89d0c69.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/tables/5e08097e96caae579aae6ff464e14f3a324b78523eab8f3ee52381a0e89d0c69.jpg)

![656fd737335ccc24182c9f6e87704d788033c83d25ef04329f982050090dd164.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/tables/656fd737335ccc24182c9f6e87704d788033c83d25ef04329f982050090dd164.jpg)

![71ba8791eaad61873d9a47645669000a6166c43ff16ba23edee3139bb5a061a4.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/tables/71ba8791eaad61873d9a47645669000a6166c43ff16ba23edee3139bb5a061a4.jpg)

![a20578c9857b3bf7eb30f2988e363b59d1d9ea179c7fd1d2e02cec0a579e1c53.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/tables/a20578c9857b3bf7eb30f2988e363b59d1d9ea179c7fd1d2e02cec0a579e1c53.jpg)

![a53c35a49f6a863fe119476cece325c16518c1320e9e2b7688223a7bb4c150a6.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/tables/a53c35a49f6a863fe119476cece325c16518c1320e9e2b7688223a7bb4c150a6.jpg)

![b3c77d9bdbb4df2d151aa02ff82539f3ce6c056d758afdba0a958de1d51d98a4.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/tables/b3c77d9bdbb4df2d151aa02ff82539f3ce6c056d758afdba0a958de1d51d98a4.jpg)

![b6e1985d50b4d38fcf91e0483cea5f4d265cad6936eae248ba815000f3e6898a.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/tables/b6e1985d50b4d38fcf91e0483cea5f4d265cad6936eae248ba815000f3e6898a.jpg)

![e3b8b76bf7da906a14d314167158652285d0349aa96956db8d543dcd0912b8b8.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/tables/e3b8b76bf7da906a14d314167158652285d0349aa96956db8d543dcd0912b8b8.jpg)

![f30cf715a7955b008386c95a90a0f747875aa2c8c48066644e5cdfe9776de75e.jpg](../emnlp_results/345_Keep%20Security%21%20Benchmarking%20Security%20Policy%20Preservation%20in%20Large%20Language%20Model%20Contexts%20Against%20In/tables/f30cf715a7955b008386c95a90a0f747875aa2c8c48066644e5cdfe9776de75e.jpg)

## Route Sparse Autoencoder to Interpret Large Language Models


### Images

![06a2ccf878f588360ae2c706b68a21b065cc7ede4fa24f70206b78376262ad62.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/images/06a2ccf878f588360ae2c706b68a21b065cc7ede4fa24f70206b78376262ad62.jpg)

![427e125cf1b505f94ddf9c9d4f9f7f5f02730564986bd44a40ffa0d4289b9064.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/images/427e125cf1b505f94ddf9c9d4f9f7f5f02730564986bd44a40ffa0d4289b9064.jpg)

![4a07e79b33b9f52281ffe14dd42ac529069dee88e6a1ad34283429b28cf83852.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/images/4a07e79b33b9f52281ffe14dd42ac529069dee88e6a1ad34283429b28cf83852.jpg)

![5dfb29e05448840190d2307dba0eac4e2018cb547298ca2a08cd7758f6e246a0.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/images/5dfb29e05448840190d2307dba0eac4e2018cb547298ca2a08cd7758f6e246a0.jpg)

![7b82c15d715324a26cbc893be722c74070da548a584f6a7a5caca46e6cba9292.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/images/7b82c15d715324a26cbc893be722c74070da548a584f6a7a5caca46e6cba9292.jpg)

![8a04ab64fbe9e48c56fdd0012090834e5110120dd10e19d053c6799f7e917761.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/images/8a04ab64fbe9e48c56fdd0012090834e5110120dd10e19d053c6799f7e917761.jpg)

![96bd69c306d319fd5f3f473e1d2327819147868d841e1241ddbdf5b9f3c3666c.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/images/96bd69c306d319fd5f3f473e1d2327819147868d841e1241ddbdf5b9f3c3666c.jpg)

![b2ef56c7699259875e12ab3fe048c26d9b7ae5e26008b165cf8fd3b6a5149573.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/images/b2ef56c7699259875e12ab3fe048c26d9b7ae5e26008b165cf8fd3b6a5149573.jpg)

![b9362780fed5e3aca402f8f1ae180383d30cd3180b999f31ed8c80e845befcfd.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/images/b9362780fed5e3aca402f8f1ae180383d30cd3180b999f31ed8c80e845befcfd.jpg)

![d2543ce90cb54ce764fbde2ad58107d7d54a5cc3f2cbc6fc56668dd77d89c5ad.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/images/d2543ce90cb54ce764fbde2ad58107d7d54a5cc3f2cbc6fc56668dd77d89c5ad.jpg)

![fc091a00ee3a0488d41bb58f049ca051ffa4bc3a7ac5f1ea39fcb5f5ea7f7900.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/images/fc091a00ee3a0488d41bb58f049ca051ffa4bc3a7ac5f1ea39fcb5f5ea7f7900.jpg)

### Tables

![41dc509d001b6b6837d56f03a426484d328e96a587aef7f77dacc137b81a80bd.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/tables/41dc509d001b6b6837d56f03a426484d328e96a587aef7f77dacc137b81a80bd.jpg)

![5445154e729b8b96a923a7ad6bf5c943f0ded0877c5788936d2b529b98bfffaf.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/tables/5445154e729b8b96a923a7ad6bf5c943f0ded0877c5788936d2b529b98bfffaf.jpg)

![ca9b7550108c77a71618334431803ffed3879a6f044a1f9d9a0db22a16cf7771.jpg](../emnlp_results/346_Route%20Sparse%20Autoencoder%20to%20Interpret%20Large%20Language%20Models/tables/ca9b7550108c77a71618334431803ffed3879a6f044a1f9d9a0db22a16cf7771.jpg)

## BTS: Harmonizing Specialized Experts into a GeneralistLLM


### Images

![3bd5ca9065aaf2abba6b7c0da39e3541a383e674300574d1881181509f9a0b94.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/images/3bd5ca9065aaf2abba6b7c0da39e3541a383e674300574d1881181509f9a0b94.jpg)

![4927756ec4c04fdf751b2315b0bc0a00beda0d8a08644914926ab60844fb49bc.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/images/4927756ec4c04fdf751b2315b0bc0a00beda0d8a08644914926ab60844fb49bc.jpg)

![cdd36dae97c3918a2e37bc3579b032a185dc8a72934d39b7dd798ce653ff1104.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/images/cdd36dae97c3918a2e37bc3579b032a185dc8a72934d39b7dd798ce653ff1104.jpg)

### Tables

![0e1da89cd944e2a9677d89e93855c463c69e14e2bd55b5276bf7a2b9c31f93a5.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/tables/0e1da89cd944e2a9677d89e93855c463c69e14e2bd55b5276bf7a2b9c31f93a5.jpg)

![12c53ad8b6b669e15a29b2a749c12f648afabe4785c996f9239682d9f737a9f0.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/tables/12c53ad8b6b669e15a29b2a749c12f648afabe4785c996f9239682d9f737a9f0.jpg)

![1f90421710009c7821296115d2765b3b7d155574dab359836807ca7b095569b8.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/tables/1f90421710009c7821296115d2765b3b7d155574dab359836807ca7b095569b8.jpg)

![211647e084335123799c927775598de74c775d521f436435c4c9c3f81970933e.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/tables/211647e084335123799c927775598de74c775d521f436435c4c9c3f81970933e.jpg)

![2f93a3e30625752e18532dd7725c0862fc55499e9f495e11ee02f1c092e0d15c.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/tables/2f93a3e30625752e18532dd7725c0862fc55499e9f495e11ee02f1c092e0d15c.jpg)

![3adea01409eb2ec8d701b67ebd67a587a269d3162e4d84300ea88fc51349541b.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/tables/3adea01409eb2ec8d701b67ebd67a587a269d3162e4d84300ea88fc51349541b.jpg)

![5e3dd1cf884e3c8e9d3c4a83045d13ed84dbac4704667ad85a5812f3c679e9ae.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/tables/5e3dd1cf884e3c8e9d3c4a83045d13ed84dbac4704667ad85a5812f3c679e9ae.jpg)

![8f16ddc6c76074c1451a765595912caac6eb8f02ed3d075a1c0c63e414e9f5bb.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/tables/8f16ddc6c76074c1451a765595912caac6eb8f02ed3d075a1c0c63e414e9f5bb.jpg)

![9af01852b87a28d98e153558ac222f3f06569f0e41d2cbd78ce6083c283b9a9c.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/tables/9af01852b87a28d98e153558ac222f3f06569f0e41d2cbd78ce6083c283b9a9c.jpg)

![b94f4b477a30d8cc0be5980db04ed917e53c942c7399b51f91abc7397a6a2623.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/tables/b94f4b477a30d8cc0be5980db04ed917e53c942c7399b51f91abc7397a6a2623.jpg)

![ca2851bc74f8c8071de741f05e9ffc09bf8c99fad034fa333bbd13cf8f1e6793.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/tables/ca2851bc74f8c8071de741f05e9ffc09bf8c99fad034fa333bbd13cf8f1e6793.jpg)

![def2e533570c53b321e7bdaed21ee8f3a0094fea6cfa1ad3f37ebd53e336c426.jpg](../emnlp_results/347_BTS_%20Harmonizing%20Specialized%20Experts%20into%20a%20GeneralistLLM/tables/def2e533570c53b321e7bdaed21ee8f3a0094fea6cfa1ad3f37ebd53e336c426.jpg)

## CoCoA: Confidence- and Context-Aware Adaptive Decoding for Resolving Knowledge Conflicts in Large Language Models


### Images

![12a557b6875d85f8d9968295fff39a8cb46c5d61722ed6a4a1f57eb146396b83.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/images/12a557b6875d85f8d9968295fff39a8cb46c5d61722ed6a4a1f57eb146396b83.jpg)

![c07de8b0032822aab8ab2c479ac09b15e3ff81753df2055778a4d416a760e98b.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/images/c07de8b0032822aab8ab2c479ac09b15e3ff81753df2055778a4d416a760e98b.jpg)

### Tables

![2535b7a21ae3ada19d4e2e89992d9401620b3ee9018fda96f8bab83342f11274.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/2535b7a21ae3ada19d4e2e89992d9401620b3ee9018fda96f8bab83342f11274.jpg)

![345809f4ba304ad3c6129b67c00887aced08b38015149cc00df853218db3ee4d.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/345809f4ba304ad3c6129b67c00887aced08b38015149cc00df853218db3ee4d.jpg)

![3a8f76e6c3f29338478f025e22672c8b3ff918d41424ac771d3f499367d9cede.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/3a8f76e6c3f29338478f025e22672c8b3ff918d41424ac771d3f499367d9cede.jpg)

![4830a209ca33dee0938c9875825eecad0e0ed302afed7de14ab27cb427fc335b.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/4830a209ca33dee0938c9875825eecad0e0ed302afed7de14ab27cb427fc335b.jpg)

![5546dfcf4d5007f7a7648c96a952912d184183a9831a254bd7d3df4a7cec5dbf.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/5546dfcf4d5007f7a7648c96a952912d184183a9831a254bd7d3df4a7cec5dbf.jpg)

![574b4ea66dbae1b6da837df43e598ac93e5ed1a03a9cddfbcb36934ffc5e488a.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/574b4ea66dbae1b6da837df43e598ac93e5ed1a03a9cddfbcb36934ffc5e488a.jpg)

![6a0086ccad57c94e8671b4b7cf96525b2bb08a734cca784ca59fb61da5a0caf4.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/6a0086ccad57c94e8671b4b7cf96525b2bb08a734cca784ca59fb61da5a0caf4.jpg)

![8738d256633b97d36031bab6bf23b82d8fbdcad1a9d460b33ff79d84bbffb01a.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/8738d256633b97d36031bab6bf23b82d8fbdcad1a9d460b33ff79d84bbffb01a.jpg)

![94cc0983f3925cb7c82e3c7917b7f5df81f70f2532e31255acea8b40b8449f06.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/94cc0983f3925cb7c82e3c7917b7f5df81f70f2532e31255acea8b40b8449f06.jpg)

![98a4cb398dea9d209049880b513fe99db0b374cadc7a771d961b312d06dc8dd1.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/98a4cb398dea9d209049880b513fe99db0b374cadc7a771d961b312d06dc8dd1.jpg)

![a43a54c7fef6cdddb742cb7f55e520d2da892376dd536d91179fc74bc9d82811.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/a43a54c7fef6cdddb742cb7f55e520d2da892376dd536d91179fc74bc9d82811.jpg)

![a647b54660327a736ed559ba86956b4b676d01731e60af0d671bba4c39825cdc.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/a647b54660327a736ed559ba86956b4b676d01731e60af0d671bba4c39825cdc.jpg)

![ad655b832324640830498a539dff4f0d02e34020bb6e441dbfbe8e5ea3b94e92.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/ad655b832324640830498a539dff4f0d02e34020bb6e441dbfbe8e5ea3b94e92.jpg)

![cb01945abdfd54c2eed8b1f4535528863cd0c71c8d7374c9a7439ce82ba3f62f.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/cb01945abdfd54c2eed8b1f4535528863cd0c71c8d7374c9a7439ce82ba3f62f.jpg)

![d7698fe2d41a0501af7e4f8c4af777e1724a0089af5ce36a48c2d7c3cc947c33.jpg](../emnlp_results/348_CoCoA_%20Confidence-%20and%20Context-Aware%20Adaptive%20Decoding%20for%20Resolving%20Knowledge%20Conflicts%20in%20Large%20La/tables/d7698fe2d41a0501af7e4f8c4af777e1724a0089af5ce36a48c2d7c3cc947c33.jpg)

## R-Bind: Unified Enhancement of Attribute and Relation Binding in Text-to-Image Diffusion Models


### Images

![0884e9ab8d2ed112c7442ddc737275cd0e5257f168cbcb48bb9411e229cfb839.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/images/0884e9ab8d2ed112c7442ddc737275cd0e5257f168cbcb48bb9411e229cfb839.jpg)

![578de28d0dd5845daf5932bde115e611ed3e98736f0c72ca1c9b79d2f9b01692.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/images/578de28d0dd5845daf5932bde115e611ed3e98736f0c72ca1c9b79d2f9b01692.jpg)

![6c6fa40b184aafd9f9e70c126bddee1600a8583cba56b3866f58db3a29cc83a9.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/images/6c6fa40b184aafd9f9e70c126bddee1600a8583cba56b3866f58db3a29cc83a9.jpg)

![acbed86fd704a8e1397fb78c03fffe783f97f985de170d590dde109f8439a720.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/images/acbed86fd704a8e1397fb78c03fffe783f97f985de170d590dde109f8439a720.jpg)

![b265a6a7e845ec2ea4034eb183e9385045ddb83997d855a639a37aef7fdaa71f.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/images/b265a6a7e845ec2ea4034eb183e9385045ddb83997d855a639a37aef7fdaa71f.jpg)

![c9756ccc73e4bb72f9e11e5ea7427d2dc3b6eaba9efe1c1c0dedaef4a0f17a57.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/images/c9756ccc73e4bb72f9e11e5ea7427d2dc3b6eaba9efe1c1c0dedaef4a0f17a57.jpg)

![cfc202105d2e9de0e79512e8571e4170ec5683ff5f5a66d1bab1b747d4d5572a.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/images/cfc202105d2e9de0e79512e8571e4170ec5683ff5f5a66d1bab1b747d4d5572a.jpg)

![de7a216bca7bf37d95d67d8fd801ffe62229a08774bae41a27becba139f0cf3e.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/images/de7a216bca7bf37d95d67d8fd801ffe62229a08774bae41a27becba139f0cf3e.jpg)

### Tables

![00a9f9998e0f87534e9dc8b537f22b01475f51a1b3d5bcaca8316453fe93df0b.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/tables/00a9f9998e0f87534e9dc8b537f22b01475f51a1b3d5bcaca8316453fe93df0b.jpg)

![05cf114daa175f0536c4bfde2324eb4966b36bd6d98c6c4117ecbd0d84fc24d9.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/tables/05cf114daa175f0536c4bfde2324eb4966b36bd6d98c6c4117ecbd0d84fc24d9.jpg)

![0bcfcc1e5f3edc41a187ecf383348e340dc7a454d23fa3054830b5bba57a7336.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/tables/0bcfcc1e5f3edc41a187ecf383348e340dc7a454d23fa3054830b5bba57a7336.jpg)

![2d5281ba243af02690b9ccd7b7e736e0e427193405e6f291ac633e16626e08c7.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/tables/2d5281ba243af02690b9ccd7b7e736e0e427193405e6f291ac633e16626e08c7.jpg)

![4734ff959ea7c7b240dd2dc41e93e0eadb34b1b899cb40f2989f7a9bd781e8bc.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/tables/4734ff959ea7c7b240dd2dc41e93e0eadb34b1b899cb40f2989f7a9bd781e8bc.jpg)

![5215d7f6fb80f285c164a4c7b395e9c702cddbf7680cb6c7a3f074694b84378f.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/tables/5215d7f6fb80f285c164a4c7b395e9c702cddbf7680cb6c7a3f074694b84378f.jpg)

![7ce7aa0c0b76169d1a0db7811bb9c8265eaaad5ff480729e125b2f7548ec76c6.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/tables/7ce7aa0c0b76169d1a0db7811bb9c8265eaaad5ff480729e125b2f7548ec76c6.jpg)

![a671b876da08b24fdd421c6a1d5464c5dcb7feb43281044efd04385883344644.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/tables/a671b876da08b24fdd421c6a1d5464c5dcb7feb43281044efd04385883344644.jpg)

![c80f8ba80acdb6155e5f72b8001fb5aa0353ea701d4ab6806288d975654f3328.jpg](../emnlp_results/349_R-Bind_%20Unified%20Enhancement%20of%20Attribute%20and%20Relation%20Binding%20in%20Text-to-Image%20Diffusion%20Models/tables/c80f8ba80acdb6155e5f72b8001fb5aa0353ea701d4ab6806288d975654f3328.jpg)

## Middo: Model-Informed Dynamic Data Optimization for EnhancedLLMFine-Tuning via Closed-Loop Learning


### Images

![07b9d3a2511b818220b27c5afa78e270d9e44c39b04ae8012f2d734a3c191225.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/images/07b9d3a2511b818220b27c5afa78e270d9e44c39b04ae8012f2d734a3c191225.jpg)

![19311fc4b6cfc5695ed8f42c76bd5a9fa4cff9c1049d11f8798d013e037bec12.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/images/19311fc4b6cfc5695ed8f42c76bd5a9fa4cff9c1049d11f8798d013e037bec12.jpg)

![1e412c629ae0e064c0ff6f1de7a249ffe93807ddff239a7ad742708a1c533c47.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/images/1e412c629ae0e064c0ff6f1de7a249ffe93807ddff239a7ad742708a1c533c47.jpg)

![2f0b77d6b5fdd9fc87bccbb50fa564b13cbf97e4526e05cb57b3daa18c5d1886.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/images/2f0b77d6b5fdd9fc87bccbb50fa564b13cbf97e4526e05cb57b3daa18c5d1886.jpg)

![81994fcd59ec9477b94c940d2967fba5c7bce5ba553eab7a936cf175a48db234.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/images/81994fcd59ec9477b94c940d2967fba5c7bce5ba553eab7a936cf175a48db234.jpg)

![b7ffa0df621274449a898f50e2d25cd0251f07b8f93f03c2d4604bba4881bfa2.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/images/b7ffa0df621274449a898f50e2d25cd0251f07b8f93f03c2d4604bba4881bfa2.jpg)

![cc435c319e0ed35dd435953faa4d1a970cce44463c9033dc584ddc5dcaab1c70.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/images/cc435c319e0ed35dd435953faa4d1a970cce44463c9033dc584ddc5dcaab1c70.jpg)

![f898e14491df80b670a060f4e1cdb5e8fb3e3073d210cc8caa55b04689d2508a.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/images/f898e14491df80b670a060f4e1cdb5e8fb3e3073d210cc8caa55b04689d2508a.jpg)

![ff2bdf65584304cf21f2896345a6551ae4ac17ba435454fcd717683f1e76bc00.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/images/ff2bdf65584304cf21f2896345a6551ae4ac17ba435454fcd717683f1e76bc00.jpg)

### Tables

![018f673531d3a8901004f3a7104e27670a45d542fe4ca71406a390248eb63ee7.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/tables/018f673531d3a8901004f3a7104e27670a45d542fe4ca71406a390248eb63ee7.jpg)

![0453cce74512cfb694ae709d98ea30e98678ad547b9bb5c2c2dd82ce079c6cc3.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/tables/0453cce74512cfb694ae709d98ea30e98678ad547b9bb5c2c2dd82ce079c6cc3.jpg)

![0781c863ecf5017ddd95b18206da334529e34911737b4174f53f0bbc3749d898.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/tables/0781c863ecf5017ddd95b18206da334529e34911737b4174f53f0bbc3749d898.jpg)

![602a667741656c409e7bee744a0f7dd30d762b088d6337a095e35d1fdd38306c.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/tables/602a667741656c409e7bee744a0f7dd30d762b088d6337a095e35d1fdd38306c.jpg)

![658a7272d02e03f66e2b810e678ce254f3aced45b1af2d29d751d573428070ad.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/tables/658a7272d02e03f66e2b810e678ce254f3aced45b1af2d29d751d573428070ad.jpg)

![7e6f78ee42db235fbfa377eab3d2b329491eef7af92001468e5ea53254b9288f.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/tables/7e6f78ee42db235fbfa377eab3d2b329491eef7af92001468e5ea53254b9288f.jpg)

![8a0774113e6db70e903aa7d1be34397a3dc98bf75f59dd978458667a833f1131.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/tables/8a0774113e6db70e903aa7d1be34397a3dc98bf75f59dd978458667a833f1131.jpg)

![a3a7d9a1bcbc940a3240749fbdfca9279742c5b30437c7ead9887c80e7d8343e.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/tables/a3a7d9a1bcbc940a3240749fbdfca9279742c5b30437c7ead9887c80e7d8343e.jpg)

![abf3dc176255fdb04744e3f1b9fa0d8b51cd78800bf6b1652fa471f98fc46ffa.jpg](../emnlp_results/350_Middo_%20Model-Informed%20Dynamic%20Data%20Optimization%20for%20EnhancedLLMFine-Tuning%20via%20Closed-Loop%20Learning/tables/abf3dc176255fdb04744e3f1b9fa0d8b51cd78800bf6b1652fa471f98fc46ffa.jpg)

## Information Integration in Large Language Models is Gated by Linguistic Structural Markers


### Images

![1202479edbb21a8f8938a655743b947ba131bf1c87850346f802fc2d523141fb.jpg](../emnlp_results/351_Information%20Integration%20in%20Large%20Language%20Models%20is%20Gated%20by%20Linguistic%20Structural%20Markers/images/1202479edbb21a8f8938a655743b947ba131bf1c87850346f802fc2d523141fb.jpg)

![12498e341326787e8b64ed9377b8fd26b8a5c589949ab56eb6903a70ed2cc574.jpg](../emnlp_results/351_Information%20Integration%20in%20Large%20Language%20Models%20is%20Gated%20by%20Linguistic%20Structural%20Markers/images/12498e341326787e8b64ed9377b8fd26b8a5c589949ab56eb6903a70ed2cc574.jpg)

![1fabe28a7261d9d48a8827f57fd74a5d45030026d51413af42df78da580ebb3e.jpg](../emnlp_results/351_Information%20Integration%20in%20Large%20Language%20Models%20is%20Gated%20by%20Linguistic%20Structural%20Markers/images/1fabe28a7261d9d48a8827f57fd74a5d45030026d51413af42df78da580ebb3e.jpg)

![354f743b89c96d36ca0d6a37012a77a34e929ffe92e00b0942bf4390346cb980.jpg](../emnlp_results/351_Information%20Integration%20in%20Large%20Language%20Models%20is%20Gated%20by%20Linguistic%20Structural%20Markers/images/354f743b89c96d36ca0d6a37012a77a34e929ffe92e00b0942bf4390346cb980.jpg)

![35be8c128b19cf88412108cb5a8f413dc5f514cd86356c97563bee4f735751cc.jpg](../emnlp_results/351_Information%20Integration%20in%20Large%20Language%20Models%20is%20Gated%20by%20Linguistic%20Structural%20Markers/images/35be8c128b19cf88412108cb5a8f413dc5f514cd86356c97563bee4f735751cc.jpg)

![560a2232654f07772b20e51d1327d40142c4f265cc86e994ae3cd0e1421b9d8f.jpg](../emnlp_results/351_Information%20Integration%20in%20Large%20Language%20Models%20is%20Gated%20by%20Linguistic%20Structural%20Markers/images/560a2232654f07772b20e51d1327d40142c4f265cc86e994ae3cd0e1421b9d8f.jpg)

![81814094be5e1de9270c461dde134862077c4983b5985a9b98687041e3ccbcd5.jpg](../emnlp_results/351_Information%20Integration%20in%20Large%20Language%20Models%20is%20Gated%20by%20Linguistic%20Structural%20Markers/images/81814094be5e1de9270c461dde134862077c4983b5985a9b98687041e3ccbcd5.jpg)

![bbca49a278e79e424fb56a8ef46e5725415c6f3803dd3e9008ec7ff2b9c59425.jpg](../emnlp_results/351_Information%20Integration%20in%20Large%20Language%20Models%20is%20Gated%20by%20Linguistic%20Structural%20Markers/images/bbca49a278e79e424fb56a8ef46e5725415c6f3803dd3e9008ec7ff2b9c59425.jpg)

![c659ed7d4bf6991bfb8dc88307de7605fd28e8d22b82bbaaeb9aade8e511223a.jpg](../emnlp_results/351_Information%20Integration%20in%20Large%20Language%20Models%20is%20Gated%20by%20Linguistic%20Structural%20Markers/images/c659ed7d4bf6991bfb8dc88307de7605fd28e8d22b82bbaaeb9aade8e511223a.jpg)

![e91a36af681903ef01a562a8eb8954c00d2c15e6abd6091b2e5ef78ccf55e86b.jpg](../emnlp_results/351_Information%20Integration%20in%20Large%20Language%20Models%20is%20Gated%20by%20Linguistic%20Structural%20Markers/images/e91a36af681903ef01a562a8eb8954c00d2c15e6abd6091b2e5ef78ccf55e86b.jpg)

## Why and HowLLMs Benefit from Knowledge Introspection in Commonsense Reasoning


### Images

![08f11e587fa2cada463cc0699aebec872474d2454a7f2dea26a95da9a5311e5e.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/images/08f11e587fa2cada463cc0699aebec872474d2454a7f2dea26a95da9a5311e5e.jpg)

![32f5d957e4ed05ed317c21fa9883103fccb2b92aa6cbde1d9154103870c3468f.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/images/32f5d957e4ed05ed317c21fa9883103fccb2b92aa6cbde1d9154103870c3468f.jpg)

![4d72a8ad836621eb4df951ddd1e715182530746dfdc7c1952d277124f34c03a1.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/images/4d72a8ad836621eb4df951ddd1e715182530746dfdc7c1952d277124f34c03a1.jpg)

![7b70c59c208cd111e9e2cf331f4172decc5170bc3058306ccab6241aba6af58f.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/images/7b70c59c208cd111e9e2cf331f4172decc5170bc3058306ccab6241aba6af58f.jpg)

![959dc8080b886f0de2e87ed521d8cab430643dcbefefc3aeefb43808f30af492.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/images/959dc8080b886f0de2e87ed521d8cab430643dcbefefc3aeefb43808f30af492.jpg)

![a5449b4fc8735a77b1af6b885cd013d0990fa4d7495f3cd076a87beb78f3885a.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/images/a5449b4fc8735a77b1af6b885cd013d0990fa4d7495f3cd076a87beb78f3885a.jpg)

![cd1474c1fce5a9f342a752bfd3b49933f016b48aa21ddff2ae870e4ebe505fac.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/images/cd1474c1fce5a9f342a752bfd3b49933f016b48aa21ddff2ae870e4ebe505fac.jpg)

![cdae46d1ca4c3e6d4c3d82334a3bd682d6e1b24da701f16dc869ce33f7d361cc.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/images/cdae46d1ca4c3e6d4c3d82334a3bd682d6e1b24da701f16dc869ce33f7d361cc.jpg)

![cfe558e6c6caa2df1f50f4555d161629f14aec64502e1dd16a5ee74f4a431001.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/images/cfe558e6c6caa2df1f50f4555d161629f14aec64502e1dd16a5ee74f4a431001.jpg)

![d2d87de2e004729017e5b42351d98079519893efa5ef3fd148e4acdae286e63a.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/images/d2d87de2e004729017e5b42351d98079519893efa5ef3fd148e4acdae286e63a.jpg)

![dfc0f8ca19f9bcf05383c78344a472d0bbfaa9acd3cce2c4162066853a39a8b2.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/images/dfc0f8ca19f9bcf05383c78344a472d0bbfaa9acd3cce2c4162066853a39a8b2.jpg)

![f78fff2e35a2d7d863513d7659fe1a7cdde27258ea3e1b914b204ffed45cd324.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/images/f78fff2e35a2d7d863513d7659fe1a7cdde27258ea3e1b914b204ffed45cd324.jpg)

### Tables

![13c2d050531baac23a5dd5f1af888c34696dabd73071c7eaa61416200c34c964.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/tables/13c2d050531baac23a5dd5f1af888c34696dabd73071c7eaa61416200c34c964.jpg)

![96b3c2c70d46603ba473ba4cd47c693f5161ee378317631f41c91a9713f1f11b.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/tables/96b3c2c70d46603ba473ba4cd47c693f5161ee378317631f41c91a9713f1f11b.jpg)

![be2c6ee218dca47c28f920da1648a8b6083911b8755d822279adb7aa293336ef.jpg](../emnlp_results/352_Why%20and%20HowLLMs%20Benefit%20from%20Knowledge%20Introspection%20in%20Commonsense%20Reasoning/tables/be2c6ee218dca47c28f920da1648a8b6083911b8755d822279adb7aa293336ef.jpg)

## GraDaSE: Graph-Based Dataset Search with Examples


### Images

![18b1f0fd7e33450c6b9f459964b343091cc971e7be7a45dd47df0c129ff362ee.jpg](../emnlp_results/353_GraDaSE_%20Graph-Based%20Dataset%20Search%20with%20Examples/images/18b1f0fd7e33450c6b9f459964b343091cc971e7be7a45dd47df0c129ff362ee.jpg)

![908ff7643fb35b48b2e44f111a2f9372d2fd339613382160bb7b1386eebe3056.jpg](../emnlp_results/353_GraDaSE_%20Graph-Based%20Dataset%20Search%20with%20Examples/images/908ff7643fb35b48b2e44f111a2f9372d2fd339613382160bb7b1386eebe3056.jpg)

![b8e0586b0859dd136912039e5a018cfbe42ae5da95c5e261851496032162e67c.jpg](../emnlp_results/353_GraDaSE_%20Graph-Based%20Dataset%20Search%20with%20Examples/images/b8e0586b0859dd136912039e5a018cfbe42ae5da95c5e261851496032162e67c.jpg)

![fbbef3cdd497d2b8645c90a9203350095f39bbb5d05d799e701743c2f52b6eb7.jpg](../emnlp_results/353_GraDaSE_%20Graph-Based%20Dataset%20Search%20with%20Examples/images/fbbef3cdd497d2b8645c90a9203350095f39bbb5d05d799e701743c2f52b6eb7.jpg)

### Tables

![053b0fa2b86a2056ec83e1c3be8b1fec623d757fc6d1782ad3723f4c64e3ad36.jpg](../emnlp_results/353_GraDaSE_%20Graph-Based%20Dataset%20Search%20with%20Examples/tables/053b0fa2b86a2056ec83e1c3be8b1fec623d757fc6d1782ad3723f4c64e3ad36.jpg)

![0a446aa61decfd845f3305a042b2fb6c0894697f8100da80211ca6e41f63b3d8.jpg](../emnlp_results/353_GraDaSE_%20Graph-Based%20Dataset%20Search%20with%20Examples/tables/0a446aa61decfd845f3305a042b2fb6c0894697f8100da80211ca6e41f63b3d8.jpg)

![2faaa806237f9d333965425702b69d562e93195c0e9030f69da5abf45cb53e8e.jpg](../emnlp_results/353_GraDaSE_%20Graph-Based%20Dataset%20Search%20with%20Examples/tables/2faaa806237f9d333965425702b69d562e93195c0e9030f69da5abf45cb53e8e.jpg)

![34128f9a647fa37b54cd6ffa9cb1c98241cea10905e94cb9ef0e4ebcc46c1ff3.jpg](../emnlp_results/353_GraDaSE_%20Graph-Based%20Dataset%20Search%20with%20Examples/tables/34128f9a647fa37b54cd6ffa9cb1c98241cea10905e94cb9ef0e4ebcc46c1ff3.jpg)

![429d269999333460a5a5634018036e0645738cba8c9c916c1a6ffe483cfa2653.jpg](../emnlp_results/353_GraDaSE_%20Graph-Based%20Dataset%20Search%20with%20Examples/tables/429d269999333460a5a5634018036e0645738cba8c9c916c1a6ffe483cfa2653.jpg)

![d3e9be9c096c3c2e4ce2744d12f9caba403777407c753d759f1e5c1f121744bb.jpg](../emnlp_results/353_GraDaSE_%20Graph-Based%20Dataset%20Search%20with%20Examples/tables/d3e9be9c096c3c2e4ce2744d12f9caba403777407c753d759f1e5c1f121744bb.jpg)

![f5accad69d85c583b33b87e9aa228479c81fb0fa02c781811d6a214f25f3691c.jpg](../emnlp_results/353_GraDaSE_%20Graph-Based%20Dataset%20Search%20with%20Examples/tables/f5accad69d85c583b33b87e9aa228479c81fb0fa02c781811d6a214f25f3691c.jpg)

## Confidence-guided Refinement Reasoning for Zero-shot Question Answering


### Images

![1df564ed11175d292e9fcfbead32ed16c4ab662cf1bae11a7204afc5eb8bb28b.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/images/1df564ed11175d292e9fcfbead32ed16c4ab662cf1bae11a7204afc5eb8bb28b.jpg)

![56ac99ab764822f6729d925d0a9149819cc561a58b411c0ccde4dd1a37027262.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/images/56ac99ab764822f6729d925d0a9149819cc561a58b411c0ccde4dd1a37027262.jpg)

![c212e849ba8dcee460aa0df0b668faa779af31a9417c0d07d35fe2365d813a38.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/images/c212e849ba8dcee460aa0df0b668faa779af31a9417c0d07d35fe2365d813a38.jpg)

![c512b83460d64a6fe6a0b9b2e439f3bd3424eb6b129d5efc8666c27947f511e1.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/images/c512b83460d64a6fe6a0b9b2e439f3bd3424eb6b129d5efc8666c27947f511e1.jpg)

![d81b6da78c36641c0f47b8433b634fc5c6e3cbc64db90842c9d16cb86024e323.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/images/d81b6da78c36641c0f47b8433b634fc5c6e3cbc64db90842c9d16cb86024e323.jpg)

![dff4c7d8af78f6cedf7054730bd85ab18bf655439d24be065e883c648c9bd4f0.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/images/dff4c7d8af78f6cedf7054730bd85ab18bf655439d24be065e883c648c9bd4f0.jpg)

![e5ce1928b3728575d180cff26fcd18b2c8dc2aeeda908a32c914f6bba01b205f.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/images/e5ce1928b3728575d180cff26fcd18b2c8dc2aeeda908a32c914f6bba01b205f.jpg)

![f0502c7f43b8ff5c62e22411ae7ec8ade05be15fcd7a5f7bca7e6dfae6822826.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/images/f0502c7f43b8ff5c62e22411ae7ec8ade05be15fcd7a5f7bca7e6dfae6822826.jpg)

### Tables

![05df6aec169a0d44bbaf51ad1a1e2294d916d0a0c8a958829592defce9625390.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/tables/05df6aec169a0d44bbaf51ad1a1e2294d916d0a0c8a958829592defce9625390.jpg)

![14a26c242b8a167f07b59bb02a4984a681280f3b4399b87252072d043b18d58f.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/tables/14a26c242b8a167f07b59bb02a4984a681280f3b4399b87252072d043b18d58f.jpg)

![3a47f29bdbdc9b9d3b70bc68895c03f9dd682c47ae87c190d192e37c07b6f09f.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/tables/3a47f29bdbdc9b9d3b70bc68895c03f9dd682c47ae87c190d192e37c07b6f09f.jpg)

![4934f5d8d578fa76722b23c99c43e6180300c415bd8a80ec5b56e018b693c37f.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/tables/4934f5d8d578fa76722b23c99c43e6180300c415bd8a80ec5b56e018b693c37f.jpg)

![67b9f29b2e5b1ad6325d59988099b1ebcedaa9cb2d622bcdec13498c9fea849c.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/tables/67b9f29b2e5b1ad6325d59988099b1ebcedaa9cb2d622bcdec13498c9fea849c.jpg)

![8ad87b4dcb6876b32b87a1b7d7edc3567003e109a2f2018b3dddf6462aca977b.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/tables/8ad87b4dcb6876b32b87a1b7d7edc3567003e109a2f2018b3dddf6462aca977b.jpg)

![8e0a3ee55b13d590bdb7277804cfe14edb0efb1c572bb79bdcf39727e6570205.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/tables/8e0a3ee55b13d590bdb7277804cfe14edb0efb1c572bb79bdcf39727e6570205.jpg)

![b06a7ffe723d545203498432588843687d6a6bee745e5e306f6c6c80e427c164.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/tables/b06a7ffe723d545203498432588843687d6a6bee745e5e306f6c6c80e427c164.jpg)

![b972f9a8b48c3737f0cc9a4680c29ee1444c1d6f95a8709e23a580d1ffc5ef94.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/tables/b972f9a8b48c3737f0cc9a4680c29ee1444c1d6f95a8709e23a580d1ffc5ef94.jpg)

![ba19d4800b9e07b5a7e9e1619f26d3bb1d67a7082bb1268700084ca55b1f73f1.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/tables/ba19d4800b9e07b5a7e9e1619f26d3bb1d67a7082bb1268700084ca55b1f73f1.jpg)

![e7e7d830160f9f99509a51c0ecf5eff1f718084821c5e6626db64263609f7089.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/tables/e7e7d830160f9f99509a51c0ecf5eff1f718084821c5e6626db64263609f7089.jpg)

![f044109aadd17dc7c58e30c1ce852533f66df0c15c9bc36456a19faa0a98f597.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/tables/f044109aadd17dc7c58e30c1ce852533f66df0c15c9bc36456a19faa0a98f597.jpg)

![f88fff6dc5bd28e08b60e9836e651d8045e062a38671a9bb07b1541d4b2ab0dd.jpg](../emnlp_results/354_Confidence-guided%20Refinement%20Reasoning%20for%20Zero-shot%20Question%20Answering/tables/f88fff6dc5bd28e08b60e9836e651d8045e062a38671a9bb07b1541d4b2ab0dd.jpg)

## DICE: Structured Reasoning inLLMs throughSLM-Guided Chain-of-Thought Correction


### Images

![5d5d8dcbba8ac82f276757953356c03b1693a3cf4fd088e6630b1574b00f7f0d.jpg](../emnlp_results/355_DICE_%20Structured%20Reasoning%20inLLMs%20throughSLM-Guided%20Chain-of-Thought%20Correction/images/5d5d8dcbba8ac82f276757953356c03b1693a3cf4fd088e6630b1574b00f7f0d.jpg)

![5ea761941f91d0d274247b28523771970b55a37014585ee857bcda0dd90c48b4.jpg](../emnlp_results/355_DICE_%20Structured%20Reasoning%20inLLMs%20throughSLM-Guided%20Chain-of-Thought%20Correction/images/5ea761941f91d0d274247b28523771970b55a37014585ee857bcda0dd90c48b4.jpg)

![67f826375748b9e77e2ef327c27c570e6c8b5507177601eb8fb38084b2a93cc2.jpg](../emnlp_results/355_DICE_%20Structured%20Reasoning%20inLLMs%20throughSLM-Guided%20Chain-of-Thought%20Correction/images/67f826375748b9e77e2ef327c27c570e6c8b5507177601eb8fb38084b2a93cc2.jpg)

![7425c948ab20318b0c9e29fa41b356c3d0458114a17783ebb2bfc0d0fbcec57f.jpg](../emnlp_results/355_DICE_%20Structured%20Reasoning%20inLLMs%20throughSLM-Guided%20Chain-of-Thought%20Correction/images/7425c948ab20318b0c9e29fa41b356c3d0458114a17783ebb2bfc0d0fbcec57f.jpg)

![8d67b85b2632bbf9a6f81621d60f95af0ae48fa405f8761bed4e22ef21d844ee.jpg](../emnlp_results/355_DICE_%20Structured%20Reasoning%20inLLMs%20throughSLM-Guided%20Chain-of-Thought%20Correction/images/8d67b85b2632bbf9a6f81621d60f95af0ae48fa405f8761bed4e22ef21d844ee.jpg)

### Tables

![003b62a462ab06221871e5319497d3a04e83782639024f7f2e58ac813d0193b2.jpg](../emnlp_results/355_DICE_%20Structured%20Reasoning%20inLLMs%20throughSLM-Guided%20Chain-of-Thought%20Correction/tables/003b62a462ab06221871e5319497d3a04e83782639024f7f2e58ac813d0193b2.jpg)

![17d7f6b7d4997b67a9893c5bd5487e1f9edf5fdd4d97055eb6997a8936d3a545.jpg](../emnlp_results/355_DICE_%20Structured%20Reasoning%20inLLMs%20throughSLM-Guided%20Chain-of-Thought%20Correction/tables/17d7f6b7d4997b67a9893c5bd5487e1f9edf5fdd4d97055eb6997a8936d3a545.jpg)

![27a6428957d8c219815276c05521114d747bad60eacf5034ac219168d46a66ba.jpg](../emnlp_results/355_DICE_%20Structured%20Reasoning%20inLLMs%20throughSLM-Guided%20Chain-of-Thought%20Correction/tables/27a6428957d8c219815276c05521114d747bad60eacf5034ac219168d46a66ba.jpg)

![332532048d21f77e71dc370fa97f9846d2966c4479c42ae086ed82fab65091a0.jpg](../emnlp_results/355_DICE_%20Structured%20Reasoning%20inLLMs%20throughSLM-Guided%20Chain-of-Thought%20Correction/tables/332532048d21f77e71dc370fa97f9846d2966c4479c42ae086ed82fab65091a0.jpg)

![7e6458590c6a5040b1fcdaeb5c73fececfa878747e8c8f4531401b1ca04abd3f.jpg](../emnlp_results/355_DICE_%20Structured%20Reasoning%20inLLMs%20throughSLM-Guided%20Chain-of-Thought%20Correction/tables/7e6458590c6a5040b1fcdaeb5c73fececfa878747e8c8f4531401b1ca04abd3f.jpg)

![b16203f31abe0aa8ce6e56ae2622cfe864ef465fc559eeacf4c7c39290b1680e.jpg](../emnlp_results/355_DICE_%20Structured%20Reasoning%20inLLMs%20throughSLM-Guided%20Chain-of-Thought%20Correction/tables/b16203f31abe0aa8ce6e56ae2622cfe864ef465fc559eeacf4c7c39290b1680e.jpg)

![ded26df251536d64b7e84500ef8cf84bfc54758aaa7ca9d0a1d301928f71463a.jpg](../emnlp_results/355_DICE_%20Structured%20Reasoning%20inLLMs%20throughSLM-Guided%20Chain-of-Thought%20Correction/tables/ded26df251536d64b7e84500ef8cf84bfc54758aaa7ca9d0a1d301928f71463a.jpg)

## CTCC: A Robust and Stealthy Fingerprinting Framework for Large Language Models via Cross-Turn Contextual Correlation Backdoor


### Images

![3ba87ccea1ea86c2248af759718688e919d121d0c94f76b90fec0ba6eac907ad.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/images/3ba87ccea1ea86c2248af759718688e919d121d0c94f76b90fec0ba6eac907ad.jpg)

![5e57eb28aee7c443ebda85d07386c6bb41c45e54c85ff4db1660f27fa2d42cb4.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/images/5e57eb28aee7c443ebda85d07386c6bb41c45e54c85ff4db1660f27fa2d42cb4.jpg)

![62370b2c5d798e14118d3f29cd3ae5dfda5b6f9ca935a4640dca18ae521c86fd.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/images/62370b2c5d798e14118d3f29cd3ae5dfda5b6f9ca935a4640dca18ae521c86fd.jpg)

![c5be5f10e1721f7fd3ec2cf2e1bd329fd0116954fdba76fc05bfca30aaeb27b1.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/images/c5be5f10e1721f7fd3ec2cf2e1bd329fd0116954fdba76fc05bfca30aaeb27b1.jpg)

![d6d5c002c3672325a055562514b2df3f51f1a009603e306decbbf31ab77c984f.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/images/d6d5c002c3672325a055562514b2df3f51f1a009603e306decbbf31ab77c984f.jpg)

![eddc69338572a99465fb32a2cae45d4c10774d5dafb25f09e16b039b3535071e.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/images/eddc69338572a99465fb32a2cae45d4c10774d5dafb25f09e16b039b3535071e.jpg)

### Tables

![0411649bace47c1f8792fc50bd9ac6588f9275ca0ec56f0ade8f63204dc98a65.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/0411649bace47c1f8792fc50bd9ac6588f9275ca0ec56f0ade8f63204dc98a65.jpg)

![0d229ded944296ac04e6e405d8d495ec6a2017213027588327d20b5175ee2967.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/0d229ded944296ac04e6e405d8d495ec6a2017213027588327d20b5175ee2967.jpg)

![0f1890a189707da0b3608fd1bb5962ae171cfaf295ab3b2d43ce84ec5ac00cef.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/0f1890a189707da0b3608fd1bb5962ae171cfaf295ab3b2d43ce84ec5ac00cef.jpg)

![1b90d2775c9c547c439b3ec69152bfdc2a86ad8bfe7ed51647ad85483962e278.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/1b90d2775c9c547c439b3ec69152bfdc2a86ad8bfe7ed51647ad85483962e278.jpg)

![2ae52d0c8cefbeb73fa8356e8944bc22ba6cf499bbd8065278bd63bcb163f4ed.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/2ae52d0c8cefbeb73fa8356e8944bc22ba6cf499bbd8065278bd63bcb163f4ed.jpg)

![3c203747d43c8a930174a94e194d3679b479b362638391bd6bf5cdd19df88f73.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/3c203747d43c8a930174a94e194d3679b479b362638391bd6bf5cdd19df88f73.jpg)

![456e7bb815dbe283a82c4a5955959e6355a3c42c13a7a867df31f6637857e9fe.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/456e7bb815dbe283a82c4a5955959e6355a3c42c13a7a867df31f6637857e9fe.jpg)

![668c0923982108b59ec12d54ff3342aac6cd6067092364c5ee132bcbfc13e1a0.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/668c0923982108b59ec12d54ff3342aac6cd6067092364c5ee132bcbfc13e1a0.jpg)

![690a96a156627533400ad6be585bb8bf9f2540d36cdf5fa2d345e55370230985.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/690a96a156627533400ad6be585bb8bf9f2540d36cdf5fa2d345e55370230985.jpg)

![6a1958207c1646af954eb7a92ce6efb9daec8316d9ec9b5320ace9837bc98cca.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/6a1958207c1646af954eb7a92ce6efb9daec8316d9ec9b5320ace9837bc98cca.jpg)

![6f174a75686436c97e3b2c7a5d3fca15c12b91a11633f34a465aaa64f4406fdc.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/6f174a75686436c97e3b2c7a5d3fca15c12b91a11633f34a465aaa64f4406fdc.jpg)

![7906550ed1ec71e5df4fdf7a5d89f0a0c7c5b027e7d770eb695978e404bb9f95.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/7906550ed1ec71e5df4fdf7a5d89f0a0c7c5b027e7d770eb695978e404bb9f95.jpg)

![7ef62d9de211be0e93e5318291d343b795e8cde89f90d017e011578da8bfc919.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/7ef62d9de211be0e93e5318291d343b795e8cde89f90d017e011578da8bfc919.jpg)

![8d979a434d950bc9f8c90f3aff3e224b1dd1a51e0b591c849cedd0d537b1f960.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/8d979a434d950bc9f8c90f3aff3e224b1dd1a51e0b591c849cedd0d537b1f960.jpg)

![aa8313bd0d85f8437cede58f43af13542237ffedb49df51fcde4027f214b1330.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/aa8313bd0d85f8437cede58f43af13542237ffedb49df51fcde4027f214b1330.jpg)

![b8a9088d7dd7ea4ba7cb791ef1276ea1c671501553d37e1ad7e05be0ccdfc7dc.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/b8a9088d7dd7ea4ba7cb791ef1276ea1c671501553d37e1ad7e05be0ccdfc7dc.jpg)

![ba611e24840623d73af7b3e3c2b2f661e226c392bbcffb20eea0c7528baf9a1c.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/ba611e24840623d73af7b3e3c2b2f661e226c392bbcffb20eea0c7528baf9a1c.jpg)

![bc6025ce62319b96c6a5d3c36da5a801df784f9bbb411ea578f41eca69790f0e.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/bc6025ce62319b96c6a5d3c36da5a801df784f9bbb411ea578f41eca69790f0e.jpg)

![caf6f5a932c9fa6c27ad32e0a9aaf4ede8befeda973979db685a02483ae5198c.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/caf6f5a932c9fa6c27ad32e0a9aaf4ede8befeda973979db685a02483ae5198c.jpg)

![e2fccdce7f5ae99cf9bcd25300a767e1daf129fa3b1573247640c658a9a68cb5.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/e2fccdce7f5ae99cf9bcd25300a767e1daf129fa3b1573247640c658a9a68cb5.jpg)

![e92f476810490d83acf71cb73980f1d596a6944b6a255cd9d831254a8b3701c4.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/e92f476810490d83acf71cb73980f1d596a6944b6a255cd9d831254a8b3701c4.jpg)

![eb78eb5351ced7c9f154c96be810a383763abadce4225f23d35a1a68ea6d46c2.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/eb78eb5351ced7c9f154c96be810a383763abadce4225f23d35a1a68ea6d46c2.jpg)

![fa7fc5c9d3036874cb54dd74d2c1f7b85eb376a57f6bf886eb0557815fba17c3.jpg](../emnlp_results/356_CTCC_%20A%20Robust%20and%20Stealthy%20Fingerprinting%20Framework%20for%20Large%20Language%20Models%20via%20Cross-Turn%20Contex/tables/fa7fc5c9d3036874cb54dd74d2c1f7b85eb376a57f6bf886eb0557815fba17c3.jpg)

## Realistic Training Data Generation and Rule Enhanced Decoding inLLMforNameGuess


### Images

![6cda8b1311d0eb688ee93c3f83825af20f43e23032f66ad42a7c80ab48e7acc2.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/images/6cda8b1311d0eb688ee93c3f83825af20f43e23032f66ad42a7c80ab48e7acc2.jpg)

![a912a7af114ed39e86c559e7b33dfb8ca48f35e7f76af0abb112c60595e799d2.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/images/a912a7af114ed39e86c559e7b33dfb8ca48f35e7f76af0abb112c60595e799d2.jpg)

![b38d18c264fe4d6f4183f817e79834ec94d309ea168fe8942ba8ce620c508884.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/images/b38d18c264fe4d6f4183f817e79834ec94d309ea168fe8942ba8ce620c508884.jpg)

![b8910260f454aeb73dc1a7cc93b0dc74c30ae7b657620f3a1fce2ea5c00b5fac.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/images/b8910260f454aeb73dc1a7cc93b0dc74c30ae7b657620f3a1fce2ea5c00b5fac.jpg)

![b98b77c70ca855b946b4f1e0b0161211bea66bed6e14adf1bf1bfbd0a6f52e4c.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/images/b98b77c70ca855b946b4f1e0b0161211bea66bed6e14adf1bf1bfbd0a6f52e4c.jpg)

![ef4e18bbfbef796e08cc98cfa733e56db7a05ff626c9e3b9d8a2d99c7f5bdf63.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/images/ef4e18bbfbef796e08cc98cfa733e56db7a05ff626c9e3b9d8a2d99c7f5bdf63.jpg)

### Tables

![17d905299171ff797f88f329668d4dd6d3dc95c9e91ae95b63db37b8890c15f3.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/tables/17d905299171ff797f88f329668d4dd6d3dc95c9e91ae95b63db37b8890c15f3.jpg)

![1eb99ac5189a0078d3af854364e8880f12f42db10152115fb8b30dcfd0fbb715.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/tables/1eb99ac5189a0078d3af854364e8880f12f42db10152115fb8b30dcfd0fbb715.jpg)

![278c05b5b3898fa08db301e31af2b008779ac95a4f32789ab44fcb99244eaf35.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/tables/278c05b5b3898fa08db301e31af2b008779ac95a4f32789ab44fcb99244eaf35.jpg)

![2b5cab8d763d408ef26eccea195dffbd6e8d8c0f94d4575c00349059c1fb546e.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/tables/2b5cab8d763d408ef26eccea195dffbd6e8d8c0f94d4575c00349059c1fb546e.jpg)

![5f85127dd912478e16de4072819abeb68edc3d1ef2573ac58cbb969c4215b816.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/tables/5f85127dd912478e16de4072819abeb68edc3d1ef2573ac58cbb969c4215b816.jpg)

![637c05a2d57366a7501fd9b7a6146e881ada2e765b87a435d4c15752eb97b2cc.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/tables/637c05a2d57366a7501fd9b7a6146e881ada2e765b87a435d4c15752eb97b2cc.jpg)

![91080ac3d936adc18184f0395c0158989b5df77bcc097e62aab4f293aa0a2635.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/tables/91080ac3d936adc18184f0395c0158989b5df77bcc097e62aab4f293aa0a2635.jpg)

![e325b804fe32cd0e59840e338ddc9a72dcec85b65241c852ea0e9a5442526415.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/tables/e325b804fe32cd0e59840e338ddc9a72dcec85b65241c852ea0e9a5442526415.jpg)

![e75221eae333956b8c2e49b071f073b50dcc78270374f033c1ad169c7f58f6d0.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/tables/e75221eae333956b8c2e49b071f073b50dcc78270374f033c1ad169c7f58f6d0.jpg)

![eec6c65a022f87d11edbfc6f548dd820cf76377340b95ecf8b61c6792f73ba2e.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/tables/eec6c65a022f87d11edbfc6f548dd820cf76377340b95ecf8b61c6792f73ba2e.jpg)

![ff736cc4fb749d434d857e06ccb90b206af88296438c899de7e557b885c070a3.jpg](../emnlp_results/357_Realistic%20Training%20Data%20Generation%20and%20Rule%20Enhanced%20Decoding%20inLLMforNameGuess/tables/ff736cc4fb749d434d857e06ccb90b206af88296438c899de7e557b885c070a3.jpg)

## EverTracer: Hunting Stolen Large Language Models via Stealthy and Robust Probabilistic Fingerprint


### Images

![0e42c9747bb5e752955704058f92d086e57565735f09bfe55142fe0936b1a781.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/images/0e42c9747bb5e752955704058f92d086e57565735f09bfe55142fe0936b1a781.jpg)

![2c669ad6ca48fc5252dfcbc09f11229d2170149feee3e55976ac4d6f4af54548.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/images/2c669ad6ca48fc5252dfcbc09f11229d2170149feee3e55976ac4d6f4af54548.jpg)

![3395337369b9b17ade6fec50ebda37401e702cc273acc615fdee8e3a368019a7.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/images/3395337369b9b17ade6fec50ebda37401e702cc273acc615fdee8e3a368019a7.jpg)

![7ae811647c557e0e2c10451d515b906896196f27e98191d657bd86fe0c0984d3.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/images/7ae811647c557e0e2c10451d515b906896196f27e98191d657bd86fe0c0984d3.jpg)

![94afc3382987fbdd6868d853b1c49f8316be7c4398c0745e60499ecfcc2cd055.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/images/94afc3382987fbdd6868d853b1c49f8316be7c4398c0745e60499ecfcc2cd055.jpg)

![b5baf88c3fd072ac218b88f7d7527e008869ed6eb8594c4015fc69c9f3601b3a.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/images/b5baf88c3fd072ac218b88f7d7527e008869ed6eb8594c4015fc69c9f3601b3a.jpg)

### Tables

![108b7104661be0d07200f425062376c35d897e602ba7f1ed8626b0a11570427b.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/108b7104661be0d07200f425062376c35d897e602ba7f1ed8626b0a11570427b.jpg)

![1e04e42a265da3cb7a72eb8f0929818e93827e37eec1a8b57b9d89828073e1a8.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/1e04e42a265da3cb7a72eb8f0929818e93827e37eec1a8b57b9d89828073e1a8.jpg)

![1f27a0278ecd9e92a8e6b80532669973def13d7a3c3561ec02c867eecc029239.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/1f27a0278ecd9e92a8e6b80532669973def13d7a3c3561ec02c867eecc029239.jpg)

![307cda894a05ad9596fee299599e132927bcd048896ebffcef8c6f67d87e56a5.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/307cda894a05ad9596fee299599e132927bcd048896ebffcef8c6f67d87e56a5.jpg)

![3e25ddf9f6cb0c5eebbe6a20fea262a9c4b59e681904cf14993efb4e3c02e412.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/3e25ddf9f6cb0c5eebbe6a20fea262a9c4b59e681904cf14993efb4e3c02e412.jpg)

![47a0721efc4ff43d9ce3ec59a75b66ac81c3437251e0129aeb8899fbf794af62.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/47a0721efc4ff43d9ce3ec59a75b66ac81c3437251e0129aeb8899fbf794af62.jpg)

![53c14b65f0d1e374c3a8a4c34017578ff0a1ad4eb4e364bf25b5e3a2193283ba.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/53c14b65f0d1e374c3a8a4c34017578ff0a1ad4eb4e364bf25b5e3a2193283ba.jpg)

![6e5cbd0044355197645e229b370126764f9a5f34fcdf3ea67cac566c4e202c1d.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/6e5cbd0044355197645e229b370126764f9a5f34fcdf3ea67cac566c4e202c1d.jpg)

![8804b0d68671e19d5e4440a2ea1bbaa6e79c72a705b0eb57ebe68ebfb751a118.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/8804b0d68671e19d5e4440a2ea1bbaa6e79c72a705b0eb57ebe68ebfb751a118.jpg)

![8fe286c361a653ae4fdfccbf0337d3845491eba4c4b398d553533aa647ee0991.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/8fe286c361a653ae4fdfccbf0337d3845491eba4c4b398d553533aa647ee0991.jpg)

![adac8aa8b4843d3fd8a1dfa1c79c52f5700d0e7ecb545cc5a72cc7f1e54aea44.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/adac8aa8b4843d3fd8a1dfa1c79c52f5700d0e7ecb545cc5a72cc7f1e54aea44.jpg)

![aed8e2a613663d218bfe014f1372d472b195f9bb2359d1fb75a082adbeea4252.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/aed8e2a613663d218bfe014f1372d472b195f9bb2359d1fb75a082adbeea4252.jpg)

![e7491ad929c10a454e115834bbab0114f3205ebeb74398d55365e66cdd98e534.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/e7491ad929c10a454e115834bbab0114f3205ebeb74398d55365e66cdd98e534.jpg)

![ea3f1633a549a86142deef3fe9b3d4797d46cc6a51949b3cb4f89f9d8ac36171.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/ea3f1633a549a86142deef3fe9b3d4797d46cc6a51949b3cb4f89f9d8ac36171.jpg)

![ede5f3d5f8380f5dd9fe1619c6574fab0a4af14ba2b33d00282edaa3b2f070ed.jpg](../emnlp_results/358_EverTracer_%20Hunting%20Stolen%20Large%20Language%20Models%20via%20Stealthy%20and%20Robust%20Probabilistic%20Fingerprint/tables/ede5f3d5f8380f5dd9fe1619c6574fab0a4af14ba2b33d00282edaa3b2f070ed.jpg)

## Selective Preference Optimization via Token-Level Reward Function Estimation


### Images

![26ecea5172e0c3adcf0b41d172a2c5c9753b8cf17668223ed5fdbcae09406fec.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/images/26ecea5172e0c3adcf0b41d172a2c5c9753b8cf17668223ed5fdbcae09406fec.jpg)

![3b226dfb2da94809ff951be4b9b2a50711aa5054fe5cbde2692faec2f275c49e.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/images/3b226dfb2da94809ff951be4b9b2a50711aa5054fe5cbde2692faec2f275c49e.jpg)

![51f2c136998bf96d08bcf3359554cadddf21e96421c26a0cbb18a47b81cfb611.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/images/51f2c136998bf96d08bcf3359554cadddf21e96421c26a0cbb18a47b81cfb611.jpg)

![5f1e192d3bbb42d85cb11d69482ab7519a23a31e6272adb3241630ab1667677d.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/images/5f1e192d3bbb42d85cb11d69482ab7519a23a31e6272adb3241630ab1667677d.jpg)

![7fa13cebfe42a565144f7d38a6caa6cf56de8c4480868f24a17713057e2d6304.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/images/7fa13cebfe42a565144f7d38a6caa6cf56de8c4480868f24a17713057e2d6304.jpg)

![96104cea1cc2f53fef97b9f894cbd46674c9e81c7cc68dd1eca93d7d684d84d4.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/images/96104cea1cc2f53fef97b9f894cbd46674c9e81c7cc68dd1eca93d7d684d84d4.jpg)

![cd3b648f3188be0a9ee208d3f074e4a36de0fd900c8fbf4410455316dc017bce.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/images/cd3b648f3188be0a9ee208d3f074e4a36de0fd900c8fbf4410455316dc017bce.jpg)

![d0792fc8eb9fa3c43d0e2e6efbd38ab0e6fe4d058a145e1eea6df8d81b412aa7.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/images/d0792fc8eb9fa3c43d0e2e6efbd38ab0e6fe4d058a145e1eea6df8d81b412aa7.jpg)

### Tables

![1c2f0b4b7d7618fffee36db3f02707086a9b5b3246847f0f146da506dfe2f112.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/tables/1c2f0b4b7d7618fffee36db3f02707086a9b5b3246847f0f146da506dfe2f112.jpg)

![8242fb7a2e7358ef1bb2ed4cbd11aaec0a4f17dfd576c2cca7e196e85606b0b5.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/tables/8242fb7a2e7358ef1bb2ed4cbd11aaec0a4f17dfd576c2cca7e196e85606b0b5.jpg)

![83dca5d88caee0f22b744d623650824aaa2f6611411061e0123866785c611291.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/tables/83dca5d88caee0f22b744d623650824aaa2f6611411061e0123866785c611291.jpg)

![8fcedd6311b93598aff5fc7e850a5b4011fd57fb5280b3e650a53df7a8c7665d.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/tables/8fcedd6311b93598aff5fc7e850a5b4011fd57fb5280b3e650a53df7a8c7665d.jpg)

![91394b86c2fae976445742f2af5afa3d6d1c7868385027e045eef14ae5968fe4.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/tables/91394b86c2fae976445742f2af5afa3d6d1c7868385027e045eef14ae5968fe4.jpg)

![973e4cc7b7a50367c25c145c5504c53c7f413d8d50dcb8b1ff6c5d920e00a9dd.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/tables/973e4cc7b7a50367c25c145c5504c53c7f413d8d50dcb8b1ff6c5d920e00a9dd.jpg)

![97516ed7343d690a6236df6bb71ecdbd96592d5ad14c65a906c652567cc27cbe.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/tables/97516ed7343d690a6236df6bb71ecdbd96592d5ad14c65a906c652567cc27cbe.jpg)

![c8884dad0d5d75d0a0a20bd58c4ab150930b503bb4431a4c3002ed1610baca76.jpg](../emnlp_results/359_Selective%20Preference%20Optimization%20via%20Token-Level%20Reward%20Function%20Estimation/tables/c8884dad0d5d75d0a0a20bd58c4ab150930b503bb4431a4c3002ed1610baca76.jpg)

## Arena-lite: Efficient and Reliable Large Language Model Evaluation via Tournament-Based Direct Comparisons


### Images

![4e0df49b82b7b170df1828caaa9d7621f55556f8c86c88d1af39ead939bf57cd.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/images/4e0df49b82b7b170df1828caaa9d7621f55556f8c86c88d1af39ead939bf57cd.jpg)

![6c611c67b647fcde35f7213ecad45daea794b04bca514f31191eeb74e0a5c8cc.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/images/6c611c67b647fcde35f7213ecad45daea794b04bca514f31191eeb74e0a5c8cc.jpg)

![729feaf9d2fe798613013014dc74b07e62562f2055ba2ee5d7dc3a8d58fd60d5.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/images/729feaf9d2fe798613013014dc74b07e62562f2055ba2ee5d7dc3a8d58fd60d5.jpg)

![a185034e3428eaf8982fd319549adf4ccd4ef75c8cf801b575026ef1b31cf0d5.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/images/a185034e3428eaf8982fd319549adf4ccd4ef75c8cf801b575026ef1b31cf0d5.jpg)

![b4b703b4452bc5fa9086889e94d8f44e44f7acd50bf4e0263bc64b6cb955b5fc.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/images/b4b703b4452bc5fa9086889e94d8f44e44f7acd50bf4e0263bc64b6cb955b5fc.jpg)

![b96eeaabf0f71426889f537e94028217ca0de8a95212ff4bd96292e6a9a5bc68.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/images/b96eeaabf0f71426889f537e94028217ca0de8a95212ff4bd96292e6a9a5bc68.jpg)

![c488cafa13ea708b8343202176cbe012b6eb32058dc0955240acda19cb7b38d8.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/images/c488cafa13ea708b8343202176cbe012b6eb32058dc0955240acda19cb7b38d8.jpg)

![d895b944466bae76ea4e153b9d12df076c2de7001f42aa99502a7f086e29b65e.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/images/d895b944466bae76ea4e153b9d12df076c2de7001f42aa99502a7f086e29b65e.jpg)

![eec2a7b8d873e82765f4d693d0ff31444a64cb4c14507e13a7445222c22ec2bf.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/images/eec2a7b8d873e82765f4d693d0ff31444a64cb4c14507e13a7445222c22ec2bf.jpg)

![f4c0b152c1c3a78b4263f9d0ed1936924dac6fec0e2291f534924ffd86bf7488.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/images/f4c0b152c1c3a78b4263f9d0ed1936924dac6fec0e2291f534924ffd86bf7488.jpg)

### Tables

![13b93c90a405006f5fe3a72ebe13409bcced04c221a94d0ef7518726382e88ba.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/tables/13b93c90a405006f5fe3a72ebe13409bcced04c221a94d0ef7518726382e88ba.jpg)

![19607f5d5d697b8e3fa3ae050d5d251335b9962b76b2ddbb264fc76740e4e1ac.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/tables/19607f5d5d697b8e3fa3ae050d5d251335b9962b76b2ddbb264fc76740e4e1ac.jpg)

![1e3bdcb42b9ac3f43e28f04d577e90af28a9f244762cfe00037c92f5d76e6fb1.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/tables/1e3bdcb42b9ac3f43e28f04d577e90af28a9f244762cfe00037c92f5d76e6fb1.jpg)

![3b9d324b0d972b17ee47acca534ead6051f27aa973874a8cffaedebe0944bbc5.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/tables/3b9d324b0d972b17ee47acca534ead6051f27aa973874a8cffaedebe0944bbc5.jpg)

![4817a9d7ea643cf66165d5798eaea03038be524221c0ea1750a9ac8729b8eda2.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/tables/4817a9d7ea643cf66165d5798eaea03038be524221c0ea1750a9ac8729b8eda2.jpg)

![7990121b01f1d21f2ca65689762fed345748aaf459a51c74626d55a72a5c8000.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/tables/7990121b01f1d21f2ca65689762fed345748aaf459a51c74626d55a72a5c8000.jpg)

![b543029567bc03d5283103d5c397c92a32802d4bc22874297c401ea50e7c034b.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/tables/b543029567bc03d5283103d5c397c92a32802d4bc22874297c401ea50e7c034b.jpg)

![e004635487cdad90a4454641d2236e4ade2964959c6d675951dc5e44a8550015.jpg](../emnlp_results/360_Arena-lite_%20Efficient%20and%20Reliable%20Large%20Language%20Model%20Evaluation%20via%20Tournament-Based%20Direct%20Compa/tables/e004635487cdad90a4454641d2236e4ade2964959c6d675951dc5e44a8550015.jpg)

## Addressing Tokenization Inconsistency in Steganography and Watermarking Based on Large Language Models


### Images

![610271b790840baee84263451260ad23403be7071ba9f2317dabb75c41a66637.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/images/610271b790840baee84263451260ad23403be7071ba9f2317dabb75c41a66637.jpg)

![682361d916c33818bba5fb691b056e0f8f2a361b42a78153379dc2753e538531.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/images/682361d916c33818bba5fb691b056e0f8f2a361b42a78153379dc2753e538531.jpg)

![7d2aade5f1581e5fa9705dc03388617c6276ad5cf4ff7bddbe3233d9352d6950.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/images/7d2aade5f1581e5fa9705dc03388617c6276ad5cf4ff7bddbe3233d9352d6950.jpg)

![c8805bb417ce1cb6705b0ea0f81b4666b0e755d0c512391aa4c6fc08aa11dcbd.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/images/c8805bb417ce1cb6705b0ea0f81b4666b0e755d0c512391aa4c6fc08aa11dcbd.jpg)

![dcd101c1b2ffc68e8b78f558a9811df10070ba6584b407932b6465c861e79380.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/images/dcd101c1b2ffc68e8b78f558a9811df10070ba6584b407932b6465c861e79380.jpg)

![e1acea1a3b8f3b8879a8eb874d50663b4fbd2ee6c0f599468a9e4960685fa01e.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/images/e1acea1a3b8f3b8879a8eb874d50663b4fbd2ee6c0f599468a9e4960685fa01e.jpg)

### Tables

![0261327e9a9ccd1404ff7a6e67ee881a49e00b18ee663ff67dc492c3222de59f.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/0261327e9a9ccd1404ff7a6e67ee881a49e00b18ee663ff67dc492c3222de59f.jpg)

![12d8582d5ec7b9deaa00feb76f2da4986c8bc73d763e274f55a98886bfa50ce3.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/12d8582d5ec7b9deaa00feb76f2da4986c8bc73d763e274f55a98886bfa50ce3.jpg)

![18d7e7cfb2b5e73e30ad1962c7bb4137cb7e63169a280012f2f767cc4980ca95.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/18d7e7cfb2b5e73e30ad1962c7bb4137cb7e63169a280012f2f767cc4980ca95.jpg)

![2c2cd75e2c0effa495f702c7435e84cd740fc772797fc5341763a49da49cf3ed.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/2c2cd75e2c0effa495f702c7435e84cd740fc772797fc5341763a49da49cf3ed.jpg)

![309f81278198f6567775d75bab82d5c19491822f154128d29972049d22c3b6e6.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/309f81278198f6567775d75bab82d5c19491822f154128d29972049d22c3b6e6.jpg)

![3990c76b8685ced5c1712f955d8bdd9f11de7ece3b46581e4d55074323ea7f21.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/3990c76b8685ced5c1712f955d8bdd9f11de7ece3b46581e4d55074323ea7f21.jpg)

![440ea6ce46f0be334e675aeedfa37142b67d40173147668e652e16d596c29b7c.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/440ea6ce46f0be334e675aeedfa37142b67d40173147668e652e16d596c29b7c.jpg)

![44c4f8df50232a6c4416359e578c5cc4ad3e10e45b907b1ba4c03fbb2b9111c8.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/44c4f8df50232a6c4416359e578c5cc4ad3e10e45b907b1ba4c03fbb2b9111c8.jpg)

![51991f5d18e094f9841ec7237c80ae1a317ac390b6edeaa19dd13897d0e2cd2b.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/51991f5d18e094f9841ec7237c80ae1a317ac390b6edeaa19dd13897d0e2cd2b.jpg)

![547f1f12016cbd063ddfa6d976398689f0a7a647e69738ecf2f60e0cb3f25265.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/547f1f12016cbd063ddfa6d976398689f0a7a647e69738ecf2f60e0cb3f25265.jpg)

![86adfa40bc6f7807dcb54955ea942170c29de3e427868262aa124ac5efcc0c59.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/86adfa40bc6f7807dcb54955ea942170c29de3e427868262aa124ac5efcc0c59.jpg)

![86f827af5383f3652cad67a77b59d1fe7b6b5b3b6a6021ecddda6950f3a4732a.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/86f827af5383f3652cad67a77b59d1fe7b6b5b3b6a6021ecddda6950f3a4732a.jpg)

![8be417da8e622f06c057ffbf6a0822be12031defffd3e26490008a5753a0718b.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/8be417da8e622f06c057ffbf6a0822be12031defffd3e26490008a5753a0718b.jpg)

![94778c1c9a110b81c5c839a2273a7dad679301e2b551d86b86a993977b0bed08.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/94778c1c9a110b81c5c839a2273a7dad679301e2b551d86b86a993977b0bed08.jpg)

![a3b0e715665c361d5b19e9d86149fa2f28b61115be634ddb3b6c9ecfd3acdf61.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/a3b0e715665c361d5b19e9d86149fa2f28b61115be634ddb3b6c9ecfd3acdf61.jpg)

![a6a127a72db91341dd4ba97ab87358e852dbedcc61184b756c70373e72aad43f.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/a6a127a72db91341dd4ba97ab87358e852dbedcc61184b756c70373e72aad43f.jpg)

![afd703ef0955f7691f04ab28322e4c7336ebf0e3036c2d276e2c8c4ddb9d84e9.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/afd703ef0955f7691f04ab28322e4c7336ebf0e3036c2d276e2c8c4ddb9d84e9.jpg)

![b6174c2810d201115ff1ee5b65ce77a1113f882b4082c545b4c6f24f3dc249e6.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/b6174c2810d201115ff1ee5b65ce77a1113f882b4082c545b4c6f24f3dc249e6.jpg)

![c2d60546df5043185e8859763bc7783b6795136a996429528242165c55cf5a07.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/c2d60546df5043185e8859763bc7783b6795136a996429528242165c55cf5a07.jpg)

![d72d89470557bc3fe837d936e512bd63819943aa2ffc9ae51c74eadf1de10723.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/d72d89470557bc3fe837d936e512bd63819943aa2ffc9ae51c74eadf1de10723.jpg)

![e56e2f0e942fb00b7a3bfa6026922243b57f1ebd11abc61cc5bc3d79fd2d10f8.jpg](../emnlp_results/361_Addressing%20Tokenization%20Inconsistency%20in%20Steganography%20and%20Watermarking%20Based%20on%20Large%20Language%20Mode/tables/e56e2f0e942fb00b7a3bfa6026922243b57f1ebd11abc61cc5bc3d79fd2d10f8.jpg)

## ExeCoder: Empowering Large Language Models with Executability Representation for Code Translation


### Images

![01fa2594bb81ae027974ba6dd15d2ba0fe0128f0de759c1b59e2069a02e2fad3.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/01fa2594bb81ae027974ba6dd15d2ba0fe0128f0de759c1b59e2069a02e2fad3.jpg)

![21d8513ae4f07d854ec28feed7c5f437f8c99728316b39ff2a2477a259123de8.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/21d8513ae4f07d854ec28feed7c5f437f8c99728316b39ff2a2477a259123de8.jpg)

![2e966d47591ccf78dd50c4e116647f1d666601e99ab357e9f01effd7afa9fb21.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/2e966d47591ccf78dd50c4e116647f1d666601e99ab357e9f01effd7afa9fb21.jpg)

![4a9820610f3163a9e9bc23d04458b21c7bafda43d6ac758be87ba948c8776ae8.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/4a9820610f3163a9e9bc23d04458b21c7bafda43d6ac758be87ba948c8776ae8.jpg)

![72547da633bc19697bc28ecb0105176e9e51d9ccfcbf452fb3897946e5c392af.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/72547da633bc19697bc28ecb0105176e9e51d9ccfcbf452fb3897946e5c392af.jpg)

![9267044a20c0a8c5be4603a5f33414580f1f98080835f852f44e4c9ccab0688a.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/9267044a20c0a8c5be4603a5f33414580f1f98080835f852f44e4c9ccab0688a.jpg)

![a0637c968921cbd7ed937afe5046f92245eadb4a745b21289fdbf7838a6433e2.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/a0637c968921cbd7ed937afe5046f92245eadb4a745b21289fdbf7838a6433e2.jpg)

![a1e151eefbe51aa03b41eb66097595ba25275c24d17247407f2217cef9fbf7eb.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/a1e151eefbe51aa03b41eb66097595ba25275c24d17247407f2217cef9fbf7eb.jpg)

![a559ddf8c0302c635636bdd8dae7640f6bf0c50c35fdf2fcb6a0c7bd2f34bbfb.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/a559ddf8c0302c635636bdd8dae7640f6bf0c50c35fdf2fcb6a0c7bd2f34bbfb.jpg)

![a8f40f73b117273b072ecdaea72be23c087c3e14d055be22870a052975d073e5.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/a8f40f73b117273b072ecdaea72be23c087c3e14d055be22870a052975d073e5.jpg)

![be3cc8e82e4024105fec9249be68465a34b241ac133d0c49eb7f01a604c364a1.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/be3cc8e82e4024105fec9249be68465a34b241ac133d0c49eb7f01a604c364a1.jpg)

![e653cfa23cb5ced34b37f57b515183b148e3b549e6846d3e3b8e0b47a16068ed.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/e653cfa23cb5ced34b37f57b515183b148e3b549e6846d3e3b8e0b47a16068ed.jpg)

![e6dde18cc1fc1ba4e6f36b61710995d1d8d6e3c844696567c5d6aaa6f21c84e5.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/e6dde18cc1fc1ba4e6f36b61710995d1d8d6e3c844696567c5d6aaa6f21c84e5.jpg)

![e7dcf5c23f1654a781ba3d76230853e1f4e6bb497e7d389967643811b0b8b26b.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/images/e7dcf5c23f1654a781ba3d76230853e1f4e6bb497e7d389967643811b0b8b26b.jpg)

### Tables

![18a9c83cfbfe49fda3949352b1cae0881c3594f10d4f3489718cec0f78e35212.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/tables/18a9c83cfbfe49fda3949352b1cae0881c3594f10d4f3489718cec0f78e35212.jpg)

![1a2fd14296cddce7500671707050defde9f7ccdcb83f52649bb1c3b2d2594230.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/tables/1a2fd14296cddce7500671707050defde9f7ccdcb83f52649bb1c3b2d2594230.jpg)

![45dc9ffda3f8cd5ee699bbf878c678de41f2ca6bd2ab0a6447135771f882c8a3.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/tables/45dc9ffda3f8cd5ee699bbf878c678de41f2ca6bd2ab0a6447135771f882c8a3.jpg)

![8963f82dc96f5723368378d902c0a207cf978e3562aa3763700118191ec85dc0.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/tables/8963f82dc96f5723368378d902c0a207cf978e3562aa3763700118191ec85dc0.jpg)

![cb9be5896b95730a86d477b3eea9dd521572cabc80b2230f5e69c094c5fff5dd.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/tables/cb9be5896b95730a86d477b3eea9dd521572cabc80b2230f5e69c094c5fff5dd.jpg)

![cbc015f8e99c1f524b5067c647cefef9697b62a694004def02e7c8afe273c55a.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/tables/cbc015f8e99c1f524b5067c647cefef9697b62a694004def02e7c8afe273c55a.jpg)

![d6b99e88e008a84ae16939fb360bf25f480b8163654f519f11818a8ea211ce9c.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/tables/d6b99e88e008a84ae16939fb360bf25f480b8163654f519f11818a8ea211ce9c.jpg)

![df68d84b76296f43801874e9ccbb9636c5cbd9294786937dbc1da36287bcd83d.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/tables/df68d84b76296f43801874e9ccbb9636c5cbd9294786937dbc1da36287bcd83d.jpg)

![ec8a45b42c9c50cd2d3a4cf6fc659003a31c1ca5be41566a1ad23979852c9432.jpg](../emnlp_results/362_ExeCoder_%20Empowering%20Large%20Language%20Models%20with%20Executability%20Representation%20for%20Code%20Translation/tables/ec8a45b42c9c50cd2d3a4cf6fc659003a31c1ca5be41566a1ad23979852c9432.jpg)

## TableEval: A Real-World Benchmark for Complex, Multilingual, and Multi-Structured Table Question Answering


### Images

![2f4b9eae9ed13c3ba4b3d35d4382f2eca783bc54e853b4f27da6a19ef80375ca.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/images/2f4b9eae9ed13c3ba4b3d35d4382f2eca783bc54e853b4f27da6a19ef80375ca.jpg)

![3bead2045f5818c71b10b5aef63d72a00278ff437a91966375b859984ef1ce8a.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/images/3bead2045f5818c71b10b5aef63d72a00278ff437a91966375b859984ef1ce8a.jpg)

![40a583471f35c8c32588da7be9d777dc3817c914994f0009500726d0532d2f67.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/images/40a583471f35c8c32588da7be9d777dc3817c914994f0009500726d0532d2f67.jpg)

![4a62d4aabbc5e4839649162a48d20ae8f63086c49f59e26f3c4aa7ee1504dc8c.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/images/4a62d4aabbc5e4839649162a48d20ae8f63086c49f59e26f3c4aa7ee1504dc8c.jpg)

![721fb7e8ff4235dd55140a0b49cf0b4245e74a61b8859fe2651979578f7cfee2.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/images/721fb7e8ff4235dd55140a0b49cf0b4245e74a61b8859fe2651979578f7cfee2.jpg)

![7dbce57c0aa406796312d296b3152a39be0bf06bbcabca76d3693c811be429ba.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/images/7dbce57c0aa406796312d296b3152a39be0bf06bbcabca76d3693c811be429ba.jpg)

![92ce229dd1eabd08d309ce17025e23270cd2644fa8dfee9b1dd03714193939c2.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/images/92ce229dd1eabd08d309ce17025e23270cd2644fa8dfee9b1dd03714193939c2.jpg)

![a2477e095613dbc61697cb6e6bf9aa20ac010156457ed76a97a8a9224d1367d4.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/images/a2477e095613dbc61697cb6e6bf9aa20ac010156457ed76a97a8a9224d1367d4.jpg)

![a3ff6ab43c1b35caed690dfb6e1c4166b22fffa25ca7801d32e6acab69fee0fb.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/images/a3ff6ab43c1b35caed690dfb6e1c4166b22fffa25ca7801d32e6acab69fee0fb.jpg)

![bbb880d5f5a577b53e5e6c330fa284e9aae14fefd61a783b2b4e69a449ff4450.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/images/bbb880d5f5a577b53e5e6c330fa284e9aae14fefd61a783b2b4e69a449ff4450.jpg)

![d7e39742a45df7b26732e8c86868801b373b17c9873d8e292943153e8e91e178.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/images/d7e39742a45df7b26732e8c86868801b373b17c9873d8e292943153e8e91e178.jpg)

![db728d15619fcdeff1ab84efd9ae914ccebb4669d93d6350411ae705758ab44a.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/images/db728d15619fcdeff1ab84efd9ae914ccebb4669d93d6350411ae705758ab44a.jpg)

### Tables

![3335fb32ff87b6f08fba0628ffe0e10752f8a4d54584076ea73f04cf5b3e99df.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/3335fb32ff87b6f08fba0628ffe0e10752f8a4d54584076ea73f04cf5b3e99df.jpg)

![3f04d0c20e645c5bf0590b8aa7655d2e9a8bf769dfe293cc5d78efbfacd00ce9.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/3f04d0c20e645c5bf0590b8aa7655d2e9a8bf769dfe293cc5d78efbfacd00ce9.jpg)

![4723fe0a46fd9a62b721c1a10ca88d8c80f5faa9abe71d03250fe0feab089061.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/4723fe0a46fd9a62b721c1a10ca88d8c80f5faa9abe71d03250fe0feab089061.jpg)

![4ecb06349cd022fc29faef04447be58ff9bf146aea36ead6d64c7181a2c99ac7.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/4ecb06349cd022fc29faef04447be58ff9bf146aea36ead6d64c7181a2c99ac7.jpg)

![5bb797c4a36a133904b46257bb91a587a347c5941591e5f3574fd94976e9c404.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/5bb797c4a36a133904b46257bb91a587a347c5941591e5f3574fd94976e9c404.jpg)

![5fefce68c111f932ed70959083b5043601af78f5c1f169b7bcb1bb6305754fc7.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/5fefce68c111f932ed70959083b5043601af78f5c1f169b7bcb1bb6305754fc7.jpg)

![63b6833c379b05197f787a0f373e41d08ff6430de473b2fbf6a11262230a6d7f.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/63b6833c379b05197f787a0f373e41d08ff6430de473b2fbf6a11262230a6d7f.jpg)

![6e1a494b8d09b1b521bf8f7faaa127a0b1af2f98e8d6dfd2c2c7649617bb1a08.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/6e1a494b8d09b1b521bf8f7faaa127a0b1af2f98e8d6dfd2c2c7649617bb1a08.jpg)

![8d113f4a481d963bc3e63385895b746236dd9ac32da860daf609f4bac44c1a26.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/8d113f4a481d963bc3e63385895b746236dd9ac32da860daf609f4bac44c1a26.jpg)

![8f770e2a9955dcc90940c8c7d9f5b319210aec4d95c6c00fedb11d1a943942a6.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/8f770e2a9955dcc90940c8c7d9f5b319210aec4d95c6c00fedb11d1a943942a6.jpg)

![96fb7217d4c84d0be7dad76f3cdb701e4bfec0e5989f8568c331fd9349a8a4a1.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/96fb7217d4c84d0be7dad76f3cdb701e4bfec0e5989f8568c331fd9349a8a4a1.jpg)

![9b53b94d66d9cf3a05fef8592d38f098c34c1f909dc5cb82cf3d21a3a8526b7a.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/9b53b94d66d9cf3a05fef8592d38f098c34c1f909dc5cb82cf3d21a3a8526b7a.jpg)

![c8594a15bfc2def2344a9d32218f972433bfbbe75838e07a27d30cc28d371853.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/c8594a15bfc2def2344a9d32218f972433bfbbe75838e07a27d30cc28d371853.jpg)

![ca8e66f15e3a1ac94ee67bf4681e2f9296033607dac8025b0fb9bc00b29ac69b.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/ca8e66f15e3a1ac94ee67bf4681e2f9296033607dac8025b0fb9bc00b29ac69b.jpg)

![da3863a11b93ca9c95989043e65f7024b18ddb1cd733b2554c6a6eab87b51e71.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/da3863a11b93ca9c95989043e65f7024b18ddb1cd733b2554c6a6eab87b51e71.jpg)

![dbcd077be3a838bd7ccf54c8017341b1b1931d58031bd4cdb2b4c4f1b2a52719.jpg](../emnlp_results/363_TableEval_%20A%20Real-World%20Benchmark%20for%20Complex%2C%20Multilingual%2C%20and%20Multi-Structured%20Table%20Question%20Ans/tables/dbcd077be3a838bd7ccf54c8017341b1b1931d58031bd4cdb2b4c4f1b2a52719.jpg)

## NOVA-63: Native Omni-lingual Versatile Assessments of 63 Disciplines


### Images

![089f0847e0e9be598f41c27849079bc1b354410219a4f73a2c7db48162cf2b12.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/089f0847e0e9be598f41c27849079bc1b354410219a4f73a2c7db48162cf2b12.jpg)

![11d73e7a5e2262355a985821f8a97b73b1bf7c59eada6f542283aec79bebc9b8.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/11d73e7a5e2262355a985821f8a97b73b1bf7c59eada6f542283aec79bebc9b8.jpg)

![150b527898006b4a5b0d486b8466b4541a4bf2d548ea8afb1dba0e9d538647d1.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/150b527898006b4a5b0d486b8466b4541a4bf2d548ea8afb1dba0e9d538647d1.jpg)

![1520960cb7a03930570b981d840d9b697436497ec4f5728ccb8f4b091af28d84.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/1520960cb7a03930570b981d840d9b697436497ec4f5728ccb8f4b091af28d84.jpg)

![18c23fe3618dd4970721746e87cc5d569d4832a054e5b07adfe392e5880d4f1e.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/18c23fe3618dd4970721746e87cc5d569d4832a054e5b07adfe392e5880d4f1e.jpg)

![193bbdc4538c6960cea5914cf46e2caa74c72dfff5634711ab144d0d302ec02d.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/193bbdc4538c6960cea5914cf46e2caa74c72dfff5634711ab144d0d302ec02d.jpg)

![29d4fc518b5d246ba276843360a5769e767276c499af9bbc53fac8360d8650cc.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/29d4fc518b5d246ba276843360a5769e767276c499af9bbc53fac8360d8650cc.jpg)

![2a5170f2645600881d31b32a80d5b6503bb0264f751063ce9458e15bb2dcf014.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/2a5170f2645600881d31b32a80d5b6503bb0264f751063ce9458e15bb2dcf014.jpg)

![5e86872d217c61fed6fc11db0ac619126272583e884ef58f6676b128ab5fddba.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/5e86872d217c61fed6fc11db0ac619126272583e884ef58f6676b128ab5fddba.jpg)

![5f28163aa4fce8801b9852288f7d58b1faab2b8195c3cf7e78ab3262ee11cc13.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/5f28163aa4fce8801b9852288f7d58b1faab2b8195c3cf7e78ab3262ee11cc13.jpg)

![629d54c36a1f9992576273ef7ee72ecc87e7ed8595fd10a6900b509970923df5.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/629d54c36a1f9992576273ef7ee72ecc87e7ed8595fd10a6900b509970923df5.jpg)

![7befa34aca27f64fa02fed1a390b653268b54f24fee183d460fb2b3ab31969a3.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/7befa34aca27f64fa02fed1a390b653268b54f24fee183d460fb2b3ab31969a3.jpg)

![a98f361a4a840423fe8bdfd87057a6fe8d3644d20de02af81ff455c433c9f81c.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/a98f361a4a840423fe8bdfd87057a6fe8d3644d20de02af81ff455c433c9f81c.jpg)

![bb859b85db422ab0d40cff7c56fbe7371aad2ffc5edb3853da1306480e35f2e6.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/bb859b85db422ab0d40cff7c56fbe7371aad2ffc5edb3853da1306480e35f2e6.jpg)

![c1be283971f6af677871207e5bf798dc190a9df4d1203e72700db5b634aeb8ef.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/c1be283971f6af677871207e5bf798dc190a9df4d1203e72700db5b634aeb8ef.jpg)

![c6b3142d2673ee7a97e54f37ff0897e14d32348270bb6964d3b82b251fbd6fc9.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/c6b3142d2673ee7a97e54f37ff0897e14d32348270bb6964d3b82b251fbd6fc9.jpg)

![e06065cb52f2a8d5e72ebe524d14d0a6b0f10437951b05c27b89167d087bcba8.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/e06065cb52f2a8d5e72ebe524d14d0a6b0f10437951b05c27b89167d087bcba8.jpg)

![e0e4a1319522abde631330ace573fe413f42aed623ce46bdfd483cb2b566700c.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/e0e4a1319522abde631330ace573fe413f42aed623ce46bdfd483cb2b566700c.jpg)

![edc3b957c6d177867b4bf47d6ed13b0f711ea94aa3feaddd1cccbe97abc889de.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/images/edc3b957c6d177867b4bf47d6ed13b0f711ea94aa3feaddd1cccbe97abc889de.jpg)

### Tables

![0d519883b8f689caa0ab83f8dd1b33a522427ba0c2e3bfdbdeae4fc4f798f915.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/0d519883b8f689caa0ab83f8dd1b33a522427ba0c2e3bfdbdeae4fc4f798f915.jpg)

![13e2ea11681831088aea44f0d7f3dbe79edc24a0e04c9ffb05bfdf69983670c5.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/13e2ea11681831088aea44f0d7f3dbe79edc24a0e04c9ffb05bfdf69983670c5.jpg)

![3d4a90afc1c3cdff86e3a628cfcc2b6d0fdeb27d72c12846ef25faeac71536b8.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/3d4a90afc1c3cdff86e3a628cfcc2b6d0fdeb27d72c12846ef25faeac71536b8.jpg)

![3d9720067ffa8c91d78427cbfd0a57e8490f8e54a3f877dd8f7e5dc0a76c0d27.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/3d9720067ffa8c91d78427cbfd0a57e8490f8e54a3f877dd8f7e5dc0a76c0d27.jpg)

![4263ab42c20358c1e6481cb1f5ef19d9d7cc9b2f6b17a8212c684eddb1f6a4ee.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/4263ab42c20358c1e6481cb1f5ef19d9d7cc9b2f6b17a8212c684eddb1f6a4ee.jpg)

![475c9d967e880b6271471fb6114579d09ae2ef414b679c77a5a79da4d0423bc5.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/475c9d967e880b6271471fb6114579d09ae2ef414b679c77a5a79da4d0423bc5.jpg)

![5bda64ff4f6383d82108b38d056ed8d651924b00da304ab9db58accea7fd54bc.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/5bda64ff4f6383d82108b38d056ed8d651924b00da304ab9db58accea7fd54bc.jpg)

![65eb0e6129c7c7b4496be3e61876bf10a73c6395f8fb752c717113a919967f76.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/65eb0e6129c7c7b4496be3e61876bf10a73c6395f8fb752c717113a919967f76.jpg)

![6ef2609437c7084772e201879357e593f0fdec1f79a626170ba1dcd50162ff80.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/6ef2609437c7084772e201879357e593f0fdec1f79a626170ba1dcd50162ff80.jpg)

![8c12013b15b85033cfac68db2cf849a6b5777df1f7249a9a9bef6f83a30bb8d9.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/8c12013b15b85033cfac68db2cf849a6b5777df1f7249a9a9bef6f83a30bb8d9.jpg)

![b2886fb16ef4658100e1d547d673f22320f325be5653bf6202ca543217235829.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/b2886fb16ef4658100e1d547d673f22320f325be5653bf6202ca543217235829.jpg)

![b39cfe9bc354569f157a87859887241611c918a8246be417b38d681435712a02.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/b39cfe9bc354569f157a87859887241611c918a8246be417b38d681435712a02.jpg)

![bfbba56c446f4e4ecda7eda42c0c3cfa849a4fc0a27f8610a927a1f7fdd90454.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/bfbba56c446f4e4ecda7eda42c0c3cfa849a4fc0a27f8610a927a1f7fdd90454.jpg)

![c3702e748766dc18ae72a4ff06c852bcdff365c8242e5edaf318ef9bde786572.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/c3702e748766dc18ae72a4ff06c852bcdff365c8242e5edaf318ef9bde786572.jpg)

![e147f5df2875d19e880b2b1f3506e0b8da1e2f6f0cd0133c1d8977e2be9b210e.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/e147f5df2875d19e880b2b1f3506e0b8da1e2f6f0cd0133c1d8977e2be9b210e.jpg)

![f3134336d2dcee3d73c66777f388659f55e23e34b210491754d3ad8b592e54fc.jpg](../emnlp_results/364_NOVA-63_%20Native%20Omni-lingual%20Versatile%20Assessments%20of%2063%20Disciplines/tables/f3134336d2dcee3d73c66777f388659f55e23e34b210491754d3ad8b592e54fc.jpg)

## InfoGain-RAG: Boosting Retrieval-Augmented Generation through Document Information Gain-based Reranking and Filtering


### Images

![04fc4373f26dbf528170fcd00ab5b4d7cdc213301eabb00d6431a602dce584e7.jpg](../emnlp_results/365_InfoGain-RAG_%20Boosting%20Retrieval-Augmented%20Generation%20through%20Document%20Information%20Gain-based%20Rerank/images/04fc4373f26dbf528170fcd00ab5b4d7cdc213301eabb00d6431a602dce584e7.jpg)

![71f00501b2b17019b00385c4b48dd76db175e4c3380498ec16e2af2361a88949.jpg](../emnlp_results/365_InfoGain-RAG_%20Boosting%20Retrieval-Augmented%20Generation%20through%20Document%20Information%20Gain-based%20Rerank/images/71f00501b2b17019b00385c4b48dd76db175e4c3380498ec16e2af2361a88949.jpg)

![a287e499d8590d9796e5926681dba25e9b4e23d75828e794795ab5c114f0c678.jpg](../emnlp_results/365_InfoGain-RAG_%20Boosting%20Retrieval-Augmented%20Generation%20through%20Document%20Information%20Gain-based%20Rerank/images/a287e499d8590d9796e5926681dba25e9b4e23d75828e794795ab5c114f0c678.jpg)

![cfbed1b9cce18e829801f365e08f73295dbca94c0d5ef00fd4709e0e6bfc424c.jpg](../emnlp_results/365_InfoGain-RAG_%20Boosting%20Retrieval-Augmented%20Generation%20through%20Document%20Information%20Gain-based%20Rerank/images/cfbed1b9cce18e829801f365e08f73295dbca94c0d5ef00fd4709e0e6bfc424c.jpg)

### Tables

![108777699f87f6c04312aa31981a874bda2f00102aca65e52a76ccfeebb85b87.jpg](../emnlp_results/365_InfoGain-RAG_%20Boosting%20Retrieval-Augmented%20Generation%20through%20Document%20Information%20Gain-based%20Rerank/tables/108777699f87f6c04312aa31981a874bda2f00102aca65e52a76ccfeebb85b87.jpg)

![3a6774a6e509981dd9a0721ec779598805963b020d65c322ae895502db1f6ef6.jpg](../emnlp_results/365_InfoGain-RAG_%20Boosting%20Retrieval-Augmented%20Generation%20through%20Document%20Information%20Gain-based%20Rerank/tables/3a6774a6e509981dd9a0721ec779598805963b020d65c322ae895502db1f6ef6.jpg)

![646414756abd56d26bc1a88d08d48b0acd2b2a301acc09473842313f16be5fbe.jpg](../emnlp_results/365_InfoGain-RAG_%20Boosting%20Retrieval-Augmented%20Generation%20through%20Document%20Information%20Gain-based%20Rerank/tables/646414756abd56d26bc1a88d08d48b0acd2b2a301acc09473842313f16be5fbe.jpg)

![7dcb82a66693d3a4b79c46cf9f2f22733effdbaff3a5a64db3267fa8fd359f28.jpg](../emnlp_results/365_InfoGain-RAG_%20Boosting%20Retrieval-Augmented%20Generation%20through%20Document%20Information%20Gain-based%20Rerank/tables/7dcb82a66693d3a4b79c46cf9f2f22733effdbaff3a5a64db3267fa8fd359f28.jpg)

![836895ea56503baaf90a20d0b33bf7f5c922b0cb37e6d7dafd04c425a5c8ce8d.jpg](../emnlp_results/365_InfoGain-RAG_%20Boosting%20Retrieval-Augmented%20Generation%20through%20Document%20Information%20Gain-based%20Rerank/tables/836895ea56503baaf90a20d0b33bf7f5c922b0cb37e6d7dafd04c425a5c8ce8d.jpg)

![decb648a6307ea656550475f31560e863544ce6adfd4b9d7e93b71c4c9fe9fc3.jpg](../emnlp_results/365_InfoGain-RAG_%20Boosting%20Retrieval-Augmented%20Generation%20through%20Document%20Information%20Gain-based%20Rerank/tables/decb648a6307ea656550475f31560e863544ce6adfd4b9d7e93b71c4c9fe9fc3.jpg)

## SpecVLM: Enhancing Speculative Decoding of VideoLLMs via Verifier-Guided Token Pruning


### Images

![017625294462de460c39a2e65eeb16be6ebecf91175038522b89e6da5c3431df.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/017625294462de460c39a2e65eeb16be6ebecf91175038522b89e6da5c3431df.jpg)

![0e48a4e1882127e98c6ec1a1c795db715152fda0da7c6aae944378199a342828.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/0e48a4e1882127e98c6ec1a1c795db715152fda0da7c6aae944378199a342828.jpg)

![3986a10dbe4f990de2ffed16ec4c503dfff327fb46255ccb7e3e1046327fac61.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/3986a10dbe4f990de2ffed16ec4c503dfff327fb46255ccb7e3e1046327fac61.jpg)

![54bf7c1c96b885bc683c0a2fa296df8a6972774f527cd9e453807f48ae882fe6.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/54bf7c1c96b885bc683c0a2fa296df8a6972774f527cd9e453807f48ae882fe6.jpg)

![5644f2a83b87e12cfacfd0f16f2847a1270dfd1b42d7588d9fe590bedc06c7d3.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/5644f2a83b87e12cfacfd0f16f2847a1270dfd1b42d7588d9fe590bedc06c7d3.jpg)

![5dcc75e6cf3449a2d3e395e1d76d49a833bc99664d4d9995c7478defeae6169f.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/5dcc75e6cf3449a2d3e395e1d76d49a833bc99664d4d9995c7478defeae6169f.jpg)

![5f3f02b42e94a36884a70c259d18c9f360c665d8daad7bb95c25d6ffc405a4cf.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/5f3f02b42e94a36884a70c259d18c9f360c665d8daad7bb95c25d6ffc405a4cf.jpg)

![6fd024aa79aa1453140e0e834144d354fbcff9e94daa2ebbb85e0c3acdf952c5.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/6fd024aa79aa1453140e0e834144d354fbcff9e94daa2ebbb85e0c3acdf952c5.jpg)

![71c7e6748850c7ec6fcd467113ae313aca48dbccd01b548dd2e4d3425ae26082.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/71c7e6748850c7ec6fcd467113ae313aca48dbccd01b548dd2e4d3425ae26082.jpg)

![7b22b7838c298e1e61ed87a6cf2a43a41ce689b99ad3baee74577f402a351ad9.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/7b22b7838c298e1e61ed87a6cf2a43a41ce689b99ad3baee74577f402a351ad9.jpg)

![90669f275f382885c80064c465220187885a605aca16dd1c98ebe4d552d9209b.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/90669f275f382885c80064c465220187885a605aca16dd1c98ebe4d552d9209b.jpg)

![9f13f2870f495aeea6b4d5be7d61304dbaac1d5a46eb51156262116ecf5fb9c3.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/9f13f2870f495aeea6b4d5be7d61304dbaac1d5a46eb51156262116ecf5fb9c3.jpg)

![a725a63ca14f0f76cd71397376f9f56f21fd32780ef5da8083eb448332e5a587.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/a725a63ca14f0f76cd71397376f9f56f21fd32780ef5da8083eb448332e5a587.jpg)

![ac051fd1a80ab7c37259783d40d94af34e9a0c7b216cb1bad8d3fdb1ef7f5de8.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/ac051fd1a80ab7c37259783d40d94af34e9a0c7b216cb1bad8d3fdb1ef7f5de8.jpg)

![bdb9e5e7575805ff442917e1a6e4b50eff8a38344ed809a0f882a7c6f6f7c691.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/bdb9e5e7575805ff442917e1a6e4b50eff8a38344ed809a0f882a7c6f6f7c691.jpg)

![ce9dfc75b23d1e718053a3ebc459f0058db3e75fc6bf531101037f81f8518851.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/images/ce9dfc75b23d1e718053a3ebc459f0058db3e75fc6bf531101037f81f8518851.jpg)

### Tables

![23ebdabdb6a4600f13d20159c39ba2fd2a04ec3aaa0ca8b31c4ea7aaaceaf737.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/tables/23ebdabdb6a4600f13d20159c39ba2fd2a04ec3aaa0ca8b31c4ea7aaaceaf737.jpg)

![405d0f5a181f6f85b210589e8f91494b7ea4fc3303e2146c686d4ab6c5dc9e56.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/tables/405d0f5a181f6f85b210589e8f91494b7ea4fc3303e2146c686d4ab6c5dc9e56.jpg)

![8c9d88ad4595c8a1854bbf875c480a8a1212d370265e9098b19e37d3feab28f0.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/tables/8c9d88ad4595c8a1854bbf875c480a8a1212d370265e9098b19e37d3feab28f0.jpg)

![c3abab84d461be3c51e6bbc1dcefe2d4348e4c7403d13df0f446583b717351af.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/tables/c3abab84d461be3c51e6bbc1dcefe2d4348e4c7403d13df0f446583b717351af.jpg)

![dd2abceb6fb2915e52c77bc68f1b13a5de22c4c29da720c6f37920c4fe1d1908.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/tables/dd2abceb6fb2915e52c77bc68f1b13a5de22c4c29da720c6f37920c4fe1d1908.jpg)

![e34a38add170a020ba8dc92940d8990cff00965fc5e49f6a68c59dfa5e41e3f0.jpg](../emnlp_results/366_SpecVLM_%20Enhancing%20Speculative%20Decoding%20of%20VideoLLMs%20via%20Verifier-Guided%20Token%20Pruning/tables/e34a38add170a020ba8dc92940d8990cff00965fc5e49f6a68c59dfa5e41e3f0.jpg)

## What Do Indonesians Really Need from Language Technology? A Nationwide Survey


### Images

![0e863335d0e29c76a0859a00801b2a3ebbc5c8cfa9d739ef0513e5a60d931bdc.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/images/0e863335d0e29c76a0859a00801b2a3ebbc5c8cfa9d739ef0513e5a60d931bdc.jpg)

![1ce905e42e9a046ac01c97029a11b6d24294b0ee0568b261b3e1012931ad61e1.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/images/1ce905e42e9a046ac01c97029a11b6d24294b0ee0568b261b3e1012931ad61e1.jpg)

![2267fca4b79d6965f0743600b7dbeba39c1d951998bcdf7955b8beede063beba.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/images/2267fca4b79d6965f0743600b7dbeba39c1d951998bcdf7955b8beede063beba.jpg)

![2e1801220130f7467d4f137009df2765230dfee22aea24c89dab0a2940c5392e.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/images/2e1801220130f7467d4f137009df2765230dfee22aea24c89dab0a2940c5392e.jpg)

![3aafbceea52c611c5af25157588d0b05f751d502641a8ac90afd1600934d7f70.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/images/3aafbceea52c611c5af25157588d0b05f751d502641a8ac90afd1600934d7f70.jpg)

![3e6b543d3aa0fe5e5297f90d5618cfcd06f30973a4bf07d92b349bb5d4225ce3.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/images/3e6b543d3aa0fe5e5297f90d5618cfcd06f30973a4bf07d92b349bb5d4225ce3.jpg)

![5c0800077f269f5f0de5321fa72e1dfc5c63d0731853eddd5a7b36e5fc4ef13a.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/images/5c0800077f269f5f0de5321fa72e1dfc5c63d0731853eddd5a7b36e5fc4ef13a.jpg)

![7f8ae4c86ebaaff6db0ccff6ed3b4cbfb3f66443ad5cef36acdcd09d96f6ca73.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/images/7f8ae4c86ebaaff6db0ccff6ed3b4cbfb3f66443ad5cef36acdcd09d96f6ca73.jpg)

![90a5573335d2522c1b9f0a670e7c11226f4b68bb2d81e6ea7a56c94ce969cfd1.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/images/90a5573335d2522c1b9f0a670e7c11226f4b68bb2d81e6ea7a56c94ce969cfd1.jpg)

![9b89698eb953436b20161265f822b1885917e9969fbedbcd5aa44bc13abaf4d0.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/images/9b89698eb953436b20161265f822b1885917e9969fbedbcd5aa44bc13abaf4d0.jpg)

![a503119a50127fba0dd5af60249148249f79f0b3ef14f2a3031d0a2c45911e06.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/images/a503119a50127fba0dd5af60249148249f79f0b3ef14f2a3031d0a2c45911e06.jpg)

### Tables

![016f527390d44b5d9cc550f19e8a840baff2424c97e58a7a8ac35e39c6828ea8.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/tables/016f527390d44b5d9cc550f19e8a840baff2424c97e58a7a8ac35e39c6828ea8.jpg)

![245950db7516b82d7f7232517b2556bdb1b57bc8305c2b7bcea80318ee3f7ae1.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/tables/245950db7516b82d7f7232517b2556bdb1b57bc8305c2b7bcea80318ee3f7ae1.jpg)

![5e60566f721bc643e71286fc86ea026463590b1d5998a95ce4c8442b7bea8822.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/tables/5e60566f721bc643e71286fc86ea026463590b1d5998a95ce4c8442b7bea8822.jpg)

![732a1aa078de8b96d5677c356fdf375c94caaa87fec88c310359777752a41c10.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/tables/732a1aa078de8b96d5677c356fdf375c94caaa87fec88c310359777752a41c10.jpg)

![77dd1c27fa6c3adbb97a61a1c43d69df535fabaa42e95ffe6f027935bdc78069.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/tables/77dd1c27fa6c3adbb97a61a1c43d69df535fabaa42e95ffe6f027935bdc78069.jpg)

![ea504511fa5054bd02868b072f8441ac0421cccaba94fe42cc77c3546be7cc3b.jpg](../emnlp_results/367_What%20Do%20Indonesians%20Really%20Need%20from%20Language%20Technology_%20A%20Nationwide%20Survey/tables/ea504511fa5054bd02868b072f8441ac0421cccaba94fe42cc77c3546be7cc3b.jpg)

## LEO-MINI: An Efficient Multimodal Large Language Model using Conditional Token Reduction and Mixture of Multi-Modal Experts


### Images

![08bccc770661df7784cf74b9b75cd28703ec9d3e8314b30868c6671c28e14a85.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/images/08bccc770661df7784cf74b9b75cd28703ec9d3e8314b30868c6671c28e14a85.jpg)

![217df4e1f0cc730867f0a06c2509c3c82bdc066f2c92fc692c3282979c2eec3a.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/images/217df4e1f0cc730867f0a06c2509c3c82bdc066f2c92fc692c3282979c2eec3a.jpg)

![35acb41e9ffbdaa6435e0efc6963bff206844f832a1a66de993915f3857281f0.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/images/35acb41e9ffbdaa6435e0efc6963bff206844f832a1a66de993915f3857281f0.jpg)

![658f51ea60e1b75724cd1abe1fbab56bbf90db38553c77fdbb26595d3513bb9c.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/images/658f51ea60e1b75724cd1abe1fbab56bbf90db38553c77fdbb26595d3513bb9c.jpg)

![6deb041c0d1d0c2ce74d4047b645e269313b4ee73ea71f33104d02253f3356e5.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/images/6deb041c0d1d0c2ce74d4047b645e269313b4ee73ea71f33104d02253f3356e5.jpg)

![757638e0e102137c130c2d0c4cbdb41fbf9d49d5425ca70135565acc852228d1.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/images/757638e0e102137c130c2d0c4cbdb41fbf9d49d5425ca70135565acc852228d1.jpg)

![7c5e98df0bc63fe75c3453360d35421fc795abf1579f44475e50b66cac8f28a1.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/images/7c5e98df0bc63fe75c3453360d35421fc795abf1579f44475e50b66cac8f28a1.jpg)

![85fe5201ae837c0a88480df6d740dd688c79c58af9feb8f97d176e1bc0d4bb1d.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/images/85fe5201ae837c0a88480df6d740dd688c79c58af9feb8f97d176e1bc0d4bb1d.jpg)

![bc4c671dae44bc91cae3c228ec2f1c32c49f4e44c9cf09c265704092d58ea37a.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/images/bc4c671dae44bc91cae3c228ec2f1c32c49f4e44c9cf09c265704092d58ea37a.jpg)

![c5b56830b32bbf7a9135bc70f6aa55db2885bd4cb9d755dee5050d8a21c54995.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/images/c5b56830b32bbf7a9135bc70f6aa55db2885bd4cb9d755dee5050d8a21c54995.jpg)

### Tables

![0238f7f507f5f2b9710de9a6217c178d29cadb8ffda04e1f44b343c292eac953.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/tables/0238f7f507f5f2b9710de9a6217c178d29cadb8ffda04e1f44b343c292eac953.jpg)

![1fb19bc796762fccb9333cd019d412df98a7fc153084726d6343cc483c0d9b8c.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/tables/1fb19bc796762fccb9333cd019d412df98a7fc153084726d6343cc483c0d9b8c.jpg)

![78ad5097cc787c6a06777db707dfa489bb8061a818994dc50f9ef879a661d3b6.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/tables/78ad5097cc787c6a06777db707dfa489bb8061a818994dc50f9ef879a661d3b6.jpg)

![82b102f25b3f929cf9bcaff1af27a29bc99ee442cb231c0cb5a7fcdcd7c251d2.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/tables/82b102f25b3f929cf9bcaff1af27a29bc99ee442cb231c0cb5a7fcdcd7c251d2.jpg)

![be0697cdff9198aec58bb6f620fc49df576577e621c0a4191e4952fc566322c7.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/tables/be0697cdff9198aec58bb6f620fc49df576577e621c0a4191e4952fc566322c7.jpg)

![f18bb5f6162f72fc4e7c7e043f70a2e56a5ba9bfae6d4b836c2e1d44b1614b5a.jpg](../emnlp_results/368_LEO-MINI_%20An%20Efficient%20Multimodal%20Large%20Language%20Model%20using%20Conditional%20Token%20Reduction%20and%20Mixture/tables/f18bb5f6162f72fc4e7c7e043f70a2e56a5ba9bfae6d4b836c2e1d44b1614b5a.jpg)

## Confounding Factors in Relating Model Performance to Morphology


### Images

![256e23ad9c5cfee10fdfe668f9dc0c5613a7b6458a333e126d879dbac65a5737.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/images/256e23ad9c5cfee10fdfe668f9dc0c5613a7b6458a333e126d879dbac65a5737.jpg)

![28db397cb5d4dd799516fc1eb0b4c2e0a68be8399bd111d8ca2b8057666abc2a.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/images/28db397cb5d4dd799516fc1eb0b4c2e0a68be8399bd111d8ca2b8057666abc2a.jpg)

![390bbaa059df1ba0036d0f1cbb5eed741584cc7e89effee257712dda3d08ac97.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/images/390bbaa059df1ba0036d0f1cbb5eed741584cc7e89effee257712dda3d08ac97.jpg)

![3e9cc6322ddc21805b91f17a4d874278bedc022820659e46611dbfd273db08c6.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/images/3e9cc6322ddc21805b91f17a4d874278bedc022820659e46611dbfd273db08c6.jpg)

![61049ce828fa8ea2b36f2427481d6ce8f9e146e987256e0af777aa76c1e9c53f.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/images/61049ce828fa8ea2b36f2427481d6ce8f9e146e987256e0af777aa76c1e9c53f.jpg)

![78bcc7b774651c1d918f7fd2ac63b7076ad60b411aef88b23a5f30d50f914863.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/images/78bcc7b774651c1d918f7fd2ac63b7076ad60b411aef88b23a5f30d50f914863.jpg)

![7a418d8e2c53fdac36f99f4728c276d161253b12734d5c9b5b398e6d13e90fda.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/images/7a418d8e2c53fdac36f99f4728c276d161253b12734d5c9b5b398e6d13e90fda.jpg)

![9bc9298d3937fe71b0019c56c76f3e49fe1aea14e9cf0f4ed781a45a8c986307.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/images/9bc9298d3937fe71b0019c56c76f3e49fe1aea14e9cf0f4ed781a45a8c986307.jpg)

![9ce84ffa277aca1944c4945e7a370fabff5aad03fe554be8339603662492fe34.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/images/9ce84ffa277aca1944c4945e7a370fabff5aad03fe554be8339603662492fe34.jpg)

![f829d2cf11471aed70ab29156ae7e1d4b8a20fb4137c1f6f3e3be36d63c56b9b.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/images/f829d2cf11471aed70ab29156ae7e1d4b8a20fb4137c1f6f3e3be36d63c56b9b.jpg)

### Tables

![0039ba68e5614949a351c95794da64265109a035e14ef3155365c5bf7de79457.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/tables/0039ba68e5614949a351c95794da64265109a035e14ef3155365c5bf7de79457.jpg)

![088b6b4725a13ff2172c1ffab6c59013e6b28abf41daf23cdd79be9f739a4564.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/tables/088b6b4725a13ff2172c1ffab6c59013e6b28abf41daf23cdd79be9f739a4564.jpg)

![1165a4a139eea1565bd246cbce037c872ae471064b0e4df97fc7fb9a23cacbc7.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/tables/1165a4a139eea1565bd246cbce037c872ae471064b0e4df97fc7fb9a23cacbc7.jpg)

![23a5806cfd1064c814c7ba9bbfab6a6fd2c635377d0c7a58308464919a8d6e21.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/tables/23a5806cfd1064c814c7ba9bbfab6a6fd2c635377d0c7a58308464919a8d6e21.jpg)

![394cef9fb576bc83fd0130809723b23bd60970c4e306884b7612230835d753a4.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/tables/394cef9fb576bc83fd0130809723b23bd60970c4e306884b7612230835d753a4.jpg)

![40b26b144a2b5df98305725ad7d9cdd43038ee43024032c6ee46518d5dcb3f60.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/tables/40b26b144a2b5df98305725ad7d9cdd43038ee43024032c6ee46518d5dcb3f60.jpg)

![5ddae5fed6b70a50dcf49e42e1ae1624b8eeb68071e201ec8a3163ef5e7910c8.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/tables/5ddae5fed6b70a50dcf49e42e1ae1624b8eeb68071e201ec8a3163ef5e7910c8.jpg)

![65d4bc7d7535736bc3e7b2b7c843e276553f1527d9d9fe1c3d9670ca1af1ab8b.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/tables/65d4bc7d7535736bc3e7b2b7c843e276553f1527d9d9fe1c3d9670ca1af1ab8b.jpg)

![bba9ce205c893ab881130df5f25d6af6ed8daab83137f1078ac60380dc7df7b5.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/tables/bba9ce205c893ab881130df5f25d6af6ed8daab83137f1078ac60380dc7df7b5.jpg)

![bd3f30a4512c8355a9203787c03a4095e2d6adc1ff3c1081fe3cb0a2f41e3e90.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/tables/bd3f30a4512c8355a9203787c03a4095e2d6adc1ff3c1081fe3cb0a2f41e3e90.jpg)

![e0f57623da3c6e55446690afe128e3b8fb70ecfe31c44f4adf52c911bd9d45e2.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/tables/e0f57623da3c6e55446690afe128e3b8fb70ecfe31c44f4adf52c911bd9d45e2.jpg)

![fd5a626f8ed4649990de1dce520a857ebf16763a32c9e2d908da806eb474af9b.jpg](../emnlp_results/369_Confounding%20Factors%20in%20Relating%20Model%20Performance%20to%20Morphology/tables/fd5a626f8ed4649990de1dce520a857ebf16763a32c9e2d908da806eb474af9b.jpg)

## Context-Aware Membership Inference Attacks against Pre-trained Large Language Models

### Images

![036c67f7d93d73c8d68dd41dbfd067e5567d50aa71870b2a8116294efc69d7c7.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/images/036c67f7d93d73c8d68dd41dbfd067e5567d50aa71870b2a8116294efc69d7c7.jpg)

![0f7195755917e8103e3a732926047f344b49f904abb383125045d7e72a8ba4ad.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/images/0f7195755917e8103e3a732926047f344b49f904abb383125045d7e72a8ba4ad.jpg)

![2cf5b770ff830efd43d3a144502371cda4278cb98ebeb6af5aeab106c62aacf6.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/images/2cf5b770ff830efd43d3a144502371cda4278cb98ebeb6af5aeab106c62aacf6.jpg)

![3afca95cd91ebddf7b70d86b2836ca1bb58fb62b7fd192b875c1091275469ef9.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/images/3afca95cd91ebddf7b70d86b2836ca1bb58fb62b7fd192b875c1091275469ef9.jpg)

![4be6eb8484d61f1a372860356222bcada292a0bd09ed3972af6fe1e830e28172.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/images/4be6eb8484d61f1a372860356222bcada292a0bd09ed3972af6fe1e830e28172.jpg)

![5869d23251e6a6625f4590a02b6d6f3677ba33783f5ed3dcae3ec2e397685d1e.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/images/5869d23251e6a6625f4590a02b6d6f3677ba33783f5ed3dcae3ec2e397685d1e.jpg)

![8a014b14044e1f4cc6b0316452f3195ffea9ff8bebf491e4a319283236726191.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/images/8a014b14044e1f4cc6b0316452f3195ffea9ff8bebf491e4a319283236726191.jpg)

![b5ae47a0ffb9ca282642c9c1bb6e9a5811a0403aa0dc440fc73d952dba56da25.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/images/b5ae47a0ffb9ca282642c9c1bb6e9a5811a0403aa0dc440fc73d952dba56da25.jpg)

![c7ff9e584b61fad9499dabd5f31bf745dceae5192fee5247cb81e036a3d1bf47.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/images/c7ff9e584b61fad9499dabd5f31bf745dceae5192fee5247cb81e036a3d1bf47.jpg)

### Tables

![06fe63209adce4625908f44a1cadcffc9ed945edc9afff12db28684d7c1d47dd.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/06fe63209adce4625908f44a1cadcffc9ed945edc9afff12db28684d7c1d47dd.jpg)

![106ef9548e518d48e516a90a304d97e34f52bd320919daeee4cc40d472959a55.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/106ef9548e518d48e516a90a304d97e34f52bd320919daeee4cc40d472959a55.jpg)

![119744422f44ab1078cbc61ebe7ebdad2d3d998555cc17cb6e3365b98586fbb7.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/119744422f44ab1078cbc61ebe7ebdad2d3d998555cc17cb6e3365b98586fbb7.jpg)

![1d1b6503aae8ddca54078685aec51f2e7098c787a498cd895405a7bb537eb20c.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/1d1b6503aae8ddca54078685aec51f2e7098c787a498cd895405a7bb537eb20c.jpg)

![2cd21f379f63a791b16b79ac17075145c28b593613509aebbaecf3570cd31f65.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/2cd21f379f63a791b16b79ac17075145c28b593613509aebbaecf3570cd31f65.jpg)

![5065670be7b3406b301ecf0c5fe84c45c7018a1251b3e4ae221613197b534784.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/5065670be7b3406b301ecf0c5fe84c45c7018a1251b3e4ae221613197b534784.jpg)

![51007098db09c0fb8a8bbfff1dba3bc425058fa5d1fae1f8c962a7f3c983c237.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/51007098db09c0fb8a8bbfff1dba3bc425058fa5d1fae1f8c962a7f3c983c237.jpg)

![590db3db699c348e062ba2f4b7d69278bfc276225e660ac17fff5bf559d3f2c1.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/590db3db699c348e062ba2f4b7d69278bfc276225e660ac17fff5bf559d3f2c1.jpg)

![7f73bd71e079d2da798eb10323ed85b9996c4c7ecfc9be191c980a397f6ea38c.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/7f73bd71e079d2da798eb10323ed85b9996c4c7ecfc9be191c980a397f6ea38c.jpg)

![81e46b57df0e90ee3ec699929456e9b51a2ea8113066817aba3cc16b5432ae97.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/81e46b57df0e90ee3ec699929456e9b51a2ea8113066817aba3cc16b5432ae97.jpg)

![82be3b62f0ef3f3df5f3a87d2f5e1d912e33ee3d425ba7c74eed098c1a3f7e90.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/82be3b62f0ef3f3df5f3a87d2f5e1d912e33ee3d425ba7c74eed098c1a3f7e90.jpg)

![cb3a9d3c0be528dbbcd79519572ca35f0ba5b7a018341f760b9c2b5fddddf821.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/cb3a9d3c0be528dbbcd79519572ca35f0ba5b7a018341f760b9c2b5fddddf821.jpg)

![d438abca5cfc94e5776aef5c27ba610b0e8da8b24a30fa0f6ec52fe07dee1a6b.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/d438abca5cfc94e5776aef5c27ba610b0e8da8b24a30fa0f6ec52fe07dee1a6b.jpg)

![e743906a802559decd14bcef0e164f44b12702d261c12c44a5b0f355dc570045.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/e743906a802559decd14bcef0e164f44b12702d261c12c44a5b0f355dc570045.jpg)

![fb85bb71a0b33c87c9e80bd4aab0a4299df28f248461a633f5056d902b9a6a82.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/fb85bb71a0b33c87c9e80bd4aab0a4299df28f248461a633f5056d902b9a6a82.jpg)

![fdc1cb37e427113ebc7f060522ff7facb98c29861e31ded47a22dcf193dea16e.jpg](../emnlp_results/370_Context-Aware%20Membership%20Inference%20Attacks%20against%20Pre-trained%20Large%20Language%20Models/tables/fdc1cb37e427113ebc7f060522ff7facb98c29861e31ded47a22dcf193dea16e.jpg)
