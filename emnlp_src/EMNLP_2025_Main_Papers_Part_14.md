# EMNLP 2025 Main Conference Papers

**Summary:** 30 papers with extracted content:
- 📊 Total images: 14618
- 📋 Total tables: 17648
- 📄 Total files: 32266

*Note: Equations have been filtered out and are not included.*

---

# EMNLP 2025 Main Papers - Part 14 of 60

## 目录 (Table of Contents)

1. [WebAgent-R1: Training Web Agents via End-to-End Multi-Turn Reinforcement Learning](#WebAgent-R1-Training-Web-Agents-via-End-to-End-Multi-Turn-Reinforcement-Learning)
2. [Same evaluation, more tokens: On the effect of input length for machine translation evaluation using Large Language Models](#Same-evaluation-more-tokens-On-the-effect-of-input-length-for-machine-translation-evaluation-using-Large-Language-Models)
3. [PAKTON: A Multi-Agent Framework for Question Answering in Long Legal Agreements](#PAKTON-A-Multi-Agent-Framework-for-Question-Answering-in-Long-Legal-Agreements)
4. [PoSum-Bench: Benchmarking Position Bias inLLM-based Conversational Summarization](#PoSum-Bench-Benchmarking-Position-Bias-inLLM-based-Conversational-Summarization)
5. [ConCISE: Confidence-guided Compression in Step-by-step Efficient Reasoning](#ConCISE-Confidence-guided-Compression-in-Step-by-step-Efficient-Reasoning)
6. [Layer-Aware Representation Filtering: Purifying Finetuning Data to PreserveLLMSafety Alignment](#Layer-Aware-Representation-Filtering-Purifying-Finetuning-Data-to-PreserveLLMSafety-Alignment)
7. [Cross-domain Rumor Detection via Test-Time Adaptation and Large Language Models](#Cross-domain-Rumor-Detection-via-Test-Time-Adaptation-and-Large-Language-Models)
8. [MLWQ: Efficient Small Language Model Deployment via Multi-Level Weight Quantization](#MLWQ-Efficient-Small-Language-Model-Deployment-via-Multi-Level-Weight-Quantization)
9. [ToDi: Token-wise Distillation via Fine-Grained Divergence Control](#ToDi-Token-wise-Distillation-via-Fine-Grained-Divergence-Control)
10. [RethinkMCTS: Refining Erroneous Thoughts inMonteCarlo Tree Search for Code Generation](#RethinkMCTS-Refining-Erroneous-Thoughts-inMonteCarlo-Tree-Search-for-Code-Generation)
11. [Probing for Arithmetic Errors in Language Models](#Probing-for-Arithmetic-Errors-in-Language-Models)
12. [NILE: Internal Consistency Alignment in Large Language Models](#NILE-Internal-Consistency-Alignment-in-Large-Language-Models)
13. [Mining the Past with Dual Criteria: Integrating Three types of Historical Information for Context-aware Event Forecasting](#Mining-the-Past-with-Dual-Criteria-Integrating-Three-types-of-Historical-Information-for-Context-aware-Event-Forecasting)
14. [RAGferee: Building Contextual Reward Models for Retrieval-Augmented Generation](#RAGferee-Building-Contextual-Reward-Models-for-Retrieval-Augmented-Generation)
15. [Large Language Models Discriminate Against Speakers ofGerman Dialects](#Large-Language-Models-Discriminate-Against-Speakers-ofGerman-Dialects)
16. [Uncovering Argumentative Flow: A Question-Focus Discourse Structuring Framework](#Uncovering-Argumentative-Flow-A-Question-Focus-Discourse-Structuring-Framework)
17. [AbsVis – Benchmarking How Humans and Vision-Language Models “See” Abstract Concepts in Images](#AbsVis-Benchmarking-How-Humans-and-Vision-Language-Models-See-Abstract-Concepts-in-Images)
18. [A Rigorous Evaluation ofLLMData Generation Strategies for Low-Resource Languages](#A-Rigorous-Evaluation-ofLLMData-Generation-Strategies-for-Low-Resource-Languages)
19. [Alignment with Fill-In-the-Middle for Enhancing Code Generation](#Alignment-with-Fill-In-the-Middle-for-Enhancing-Code-Generation)
20. [A Middle Path for On-PremisesLLMDeployment: Preserving Privacy Without Sacrificing Model Confidentiality](#A-Middle-Path-for-On-PremisesLLMDeployment-Preserving-Privacy-Without-Sacrificing-Model-Confidentiality)
21. [Variance Sensitivity Induces Attention Entropy Collapse and Instability in Transformers](#Variance-Sensitivity-Induces-Attention-Entropy-Collapse-and-Instability-in-Transformers)
22. [X-FLoRA: Cross-modal Federated Learning with Modality-expertLoRAfor MedicalVQA](#X-FLoRA-Cross-modal-Federated-Learning-with-Modality-expertLoRAfor-MedicalVQA)
23. [Robust Native Language Identification through Agentic Decomposition](#Robust-Native-Language-Identification-through-Agentic-Decomposition)
24. [ConsistentChat: Building Skeleton-Guided Consistent Multi-Turn Dialogues for Large Language Models from Scratch](#ConsistentChat-Building-Skeleton-Guided-Consistent-Multi-Turn-Dialogues-for-Large-Language-Models-from-Scratch)
25. [Does Acceleration Cause Hidden Instability in Vision Language Models? Uncovering Instance-Level Divergence Through a Large-Scale Empirical Study](#Does-Acceleration-Cause-Hidden-Instability-in-Vision-Language-Models-Uncovering-Instance-Level-Divergence-Through-a-Large-Scale-Empirical-Study)
26. [When Annotators Disagree, Topology Explains: Mapper, a Topological Tool for Exploring Text Embedding Geometry and Ambiguity](#When-Annotators-Disagree-Topology-Explains-Mapper-a-Topological-Tool-for-Exploring-Text-Embedding-Geometry-and-Ambiguity)
27. [Self-Critique and Refinement for Faithful Natural Language Explanations](#Self-Critique-and-Refinement-for-Faithful-Natural-Language-Explanations)
28. [The Psychology of Falsehood: A Human-Centric Survey of Misinformation Detection](#The-Psychology-of-Falsehood-A-Human-Centric-Survey-of-Misinformation-Detection)
29. [SEAL: Structure and Element Aware Learning Improves Long Structured Document Retrieval](#SEAL-Structure-and-Element-Aware-Learning-Improves-Long-Structured-Document-Retrieval)
30. [AnchorAttention: Difference-Aware Sparse Attention with Stripe Granularity](#AnchorAttention-Difference-Aware-Sparse-Attention-with-Stripe-Granularity)

---


## WebAgent-R1: Training Web Agents via End-to-End Multi-Turn Reinforcement Learning

### Images

![0c7c4e43d8691921d02910b142dc4d8df732b94bb50099f79e102254f9560221.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/images/0c7c4e43d8691921d02910b142dc4d8df732b94bb50099f79e102254f9560221.jpg)

![27d24a5b17356ba048cb1a03b0aaf584919bb6e7f3cf705f867731a8928571a1.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/images/27d24a5b17356ba048cb1a03b0aaf584919bb6e7f3cf705f867731a8928571a1.jpg)

![35221c5f423e33866eb00c9c3acfeb36206f34af7355c60bd7426416bcff73f4.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/images/35221c5f423e33866eb00c9c3acfeb36206f34af7355c60bd7426416bcff73f4.jpg)

![471609c00d7b387dc22df37dabae5d4afbda898b423709cf85a2c19de6999695.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/images/471609c00d7b387dc22df37dabae5d4afbda898b423709cf85a2c19de6999695.jpg)

![4c0d3abf382ab0c1401543b98033ae8b304f862369fe8f8554b2a6f78c49b953.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/images/4c0d3abf382ab0c1401543b98033ae8b304f862369fe8f8554b2a6f78c49b953.jpg)

![5254a318bcc28ebe5bd94bbd6944af49a0602258700fed59e275e65d909cc736.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/images/5254a318bcc28ebe5bd94bbd6944af49a0602258700fed59e275e65d909cc736.jpg)

![7807dc4d3a88c9a95c89375f3bea1fe90ddd138828380f4c282a77ccf60da067.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/images/7807dc4d3a88c9a95c89375f3bea1fe90ddd138828380f4c282a77ccf60da067.jpg)

![7dca7482e90ab197e47dc59ac08cb1157f98e0760d798f57a28851b4e82da066.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/images/7dca7482e90ab197e47dc59ac08cb1157f98e0760d798f57a28851b4e82da066.jpg)

![83c219ece3660ebbdad7fb57741436299137433587659680e7493527e5c4a718.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/images/83c219ece3660ebbdad7fb57741436299137433587659680e7493527e5c4a718.jpg)

![b86c9f63c568074b314d57b2d802b35027cb0ddd1e344efd08776d6127579552.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/images/b86c9f63c568074b314d57b2d802b35027cb0ddd1e344efd08776d6127579552.jpg)

![bdfe6f521d0ef09cbe6b9d5a7e3f6003439019411820201f1de7606dc18de657.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/images/bdfe6f521d0ef09cbe6b9d5a7e3f6003439019411820201f1de7606dc18de657.jpg)

![c355a531a28223239709dd21e16a51a8de13c0a02754ce1113b92e47de87e3f6.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/images/c355a531a28223239709dd21e16a51a8de13c0a02754ce1113b92e47de87e3f6.jpg)

### Tables

![04ca5cd0bca4c308faf16f245e16ed016c28cf312bca6b7b63f9c3ded73e885e.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/04ca5cd0bca4c308faf16f245e16ed016c28cf312bca6b7b63f9c3ded73e885e.jpg)

![04f01f1cf8d4063d96a0a88371f9c64de10d62f65da423c1a826077c20e273e7.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/04f01f1cf8d4063d96a0a88371f9c64de10d62f65da423c1a826077c20e273e7.jpg)

![1a19a6661160532171f0d7d9ef29db57f32b64d4dd9928fca5f3b68a528c1c78.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/1a19a6661160532171f0d7d9ef29db57f32b64d4dd9928fca5f3b68a528c1c78.jpg)

![313a048b1960d813883cda442ea727250d6eff7c2fb571a197910ea36882af42.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/313a048b1960d813883cda442ea727250d6eff7c2fb571a197910ea36882af42.jpg)

![4f7baff5cf33106b2066692d7e154968c57215c84a171a3f4f4acef8ffee7ee3.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/4f7baff5cf33106b2066692d7e154968c57215c84a171a3f4f4acef8ffee7ee3.jpg)

![53b4446c20dca29aa025a19f07a1a1aef461b207c79b90f2e20739da292471d0.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/53b4446c20dca29aa025a19f07a1a1aef461b207c79b90f2e20739da292471d0.jpg)

![5698c98f97a290126521b5afa7db43a6b9a6f202a51c97ee86e98eb57b6bdcf1.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/5698c98f97a290126521b5afa7db43a6b9a6f202a51c97ee86e98eb57b6bdcf1.jpg)

![57f36c2364088a12b077d1c4f987bcf6f799656de1c5d1fd600195ab33c54dee.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/57f36c2364088a12b077d1c4f987bcf6f799656de1c5d1fd600195ab33c54dee.jpg)

![76ac1b48c0effeaf0131e42f658a23a67fc4219e844ced2e1903c4570da8589b.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/76ac1b48c0effeaf0131e42f658a23a67fc4219e844ced2e1903c4570da8589b.jpg)

![89cf105e5af4df6e9030355882e96e72720937ff70d8fc0dcfea67c33596a9ac.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/89cf105e5af4df6e9030355882e96e72720937ff70d8fc0dcfea67c33596a9ac.jpg)

![9e7fb1cd12f0a5f25f748adfe3c44d2549778b1f61d860e29e75959c5f4f5e68.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/9e7fb1cd12f0a5f25f748adfe3c44d2549778b1f61d860e29e75959c5f4f5e68.jpg)

![a5aaf06600374cc5269ff224ad18294e1de5e5969f0784571af9a2390fa8b4b1.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/a5aaf06600374cc5269ff224ad18294e1de5e5969f0784571af9a2390fa8b4b1.jpg)

![b42cf7fd8baaf7ee9d3aa9f480554e177e0c20fca0252b5535188bae34d331ff.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/b42cf7fd8baaf7ee9d3aa9f480554e177e0c20fca0252b5535188bae34d331ff.jpg)

![caa63674a72236b0927bd10b3fc18b3274cb2c69a702377c2726e078d5023c8c.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/caa63674a72236b0927bd10b3fc18b3274cb2c69a702377c2726e078d5023c8c.jpg)

![d6fee3aaacb63b455c881ca66eb328696eb483c2971ffaca145d35ce062b90b0.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/d6fee3aaacb63b455c881ca66eb328696eb483c2971ffaca145d35ce062b90b0.jpg)

![fa5dfeb3616457a36b99419e02be94d8daa99da57728a5bc19f952977b5f2593.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/fa5dfeb3616457a36b99419e02be94d8daa99da57728a5bc19f952977b5f2593.jpg)

![fcc7722e555d126204f5238da2798eb028d31792f9a45648418f9f6f36731154.jpg](../emnlp_results/400_UNCERTAINTY-LINE_%20Length-Invariant%20Estimation%20of%20Uncertainty%20for%20Large%20Language%20Models/tables/fcc7722e555d126204f5238da2798eb028d31792f9a45648418f9f6f36731154.jpg)

## WebAgent-R1: Training Web Agents via End-to-End Multi-Turn Reinforcement Learning


### Images

![01f1cb57d5180f125cbb4720f55a5d9dae50d445cbde20e169642325dc7e0e88.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/images/01f1cb57d5180f125cbb4720f55a5d9dae50d445cbde20e169642325dc7e0e88.jpg)

![2c9981b5a148664b7ab32541d745b1e908f910b1cc25c41c433908ce9e1dd628.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/images/2c9981b5a148664b7ab32541d745b1e908f910b1cc25c41c433908ce9e1dd628.jpg)

![34fb106c6f6474446d70e7a1257d59ebe47eb5d7d3d5484ea0604b654785e686.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/images/34fb106c6f6474446d70e7a1257d59ebe47eb5d7d3d5484ea0604b654785e686.jpg)

![377ec4201eb9f389d25ad7b00c0ad5d70cb47e91d7efc6ae19e909ef2f5e906e.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/images/377ec4201eb9f389d25ad7b00c0ad5d70cb47e91d7efc6ae19e909ef2f5e906e.jpg)

![531686968483de49017eb6af645e0e5a6b58320d2f61526a1b7b89c99e8d6cea.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/images/531686968483de49017eb6af645e0e5a6b58320d2f61526a1b7b89c99e8d6cea.jpg)

![58b83e46fef15cc9b9c92432592281e3d65b3b69db84dcba54b79925576a610e.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/images/58b83e46fef15cc9b9c92432592281e3d65b3b69db84dcba54b79925576a610e.jpg)

![592c6e0bdfefafd3c5bab66b53532879ab27254ff415491a466c36f8a34477f4.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/images/592c6e0bdfefafd3c5bab66b53532879ab27254ff415491a466c36f8a34477f4.jpg)

![92f55e53601c573de0ae26474ce5ee32b30a6f7690570cbd2e1aea852bbe5882.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/images/92f55e53601c573de0ae26474ce5ee32b30a6f7690570cbd2e1aea852bbe5882.jpg)

![993e4e280809b43c4f1890a165871c06a9f62cb2f772ca86b242d5bce1955118.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/images/993e4e280809b43c4f1890a165871c06a9f62cb2f772ca86b242d5bce1955118.jpg)

![c142cf1cd530ef7a5a37a46be4e6bcb3ebce2b790dc18a49a42ef205b446d537.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/images/c142cf1cd530ef7a5a37a46be4e6bcb3ebce2b790dc18a49a42ef205b446d537.jpg)

### Tables

![5bbdb1b4b3cd6056511da7851ef08034dd7392899b5c994374921f2e8345be24.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/tables/5bbdb1b4b3cd6056511da7851ef08034dd7392899b5c994374921f2e8345be24.jpg)

![62a8d93fde954c74e57966f18d666ff9d5827d8d7b10241c838969ae6efd72d2.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/tables/62a8d93fde954c74e57966f18d666ff9d5827d8d7b10241c838969ae6efd72d2.jpg)

![8c2ba0ff9291959303c911e16a660b20973d1261e477c321457151edf97cde24.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/tables/8c2ba0ff9291959303c911e16a660b20973d1261e477c321457151edf97cde24.jpg)

![a8df4f7088cec6764f5e0173e4e4c61130a031a5459d80ee5ae7efa370319ca7.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/tables/a8df4f7088cec6764f5e0173e4e4c61130a031a5459d80ee5ae7efa370319ca7.jpg)

![f090064ef6f78146ab1956522e93e167e4a27bd78001b10257cfefa0126a9164.jpg](../emnlp_results/401_WebAgent-R1_%20Training%20Web%20Agents%20via%20End-to-End%20Multi-Turn%20Reinforcement%20Learning/tables/f090064ef6f78146ab1956522e93e167e4a27bd78001b10257cfefa0126a9164.jpg)

## Same evaluation, more tokens: On the effect of input length for machine translation evaluation using Large Language Models


### Images

![187e112dd09ebf5d51522b847c6d13392851393ab7e287a30197a35bdbc790b1.jpg](../emnlp_results/402_Same%20evaluation%2C%20more%20tokens_%20On%20the%20effect%20of%20input%20length%20for%20machine%20translation%20evaluation%20using/images/187e112dd09ebf5d51522b847c6d13392851393ab7e287a30197a35bdbc790b1.jpg)

![42368c030e726b5debdc3155cbf5d392192c95c16b40734a182c9b81ba4c5c19.jpg](../emnlp_results/402_Same%20evaluation%2C%20more%20tokens_%20On%20the%20effect%20of%20input%20length%20for%20machine%20translation%20evaluation%20using/images/42368c030e726b5debdc3155cbf5d392192c95c16b40734a182c9b81ba4c5c19.jpg)

![4944f81058e7e29931fb849caf49dbcc5840583752971aa280120595383ae3ba.jpg](../emnlp_results/402_Same%20evaluation%2C%20more%20tokens_%20On%20the%20effect%20of%20input%20length%20for%20machine%20translation%20evaluation%20using/images/4944f81058e7e29931fb849caf49dbcc5840583752971aa280120595383ae3ba.jpg)

![6e10592309176a588a3b2ea409dedd1fcb0817089e672ca53081581d35da6210.jpg](../emnlp_results/402_Same%20evaluation%2C%20more%20tokens_%20On%20the%20effect%20of%20input%20length%20for%20machine%20translation%20evaluation%20using/images/6e10592309176a588a3b2ea409dedd1fcb0817089e672ca53081581d35da6210.jpg)

![81390b96aa83e5d97e428a7ec1a248a7facd72ba0f763e42e42359aad742e3a8.jpg](../emnlp_results/402_Same%20evaluation%2C%20more%20tokens_%20On%20the%20effect%20of%20input%20length%20for%20machine%20translation%20evaluation%20using/images/81390b96aa83e5d97e428a7ec1a248a7facd72ba0f763e42e42359aad742e3a8.jpg)

![87a775dbfa9e6cdbdec10a897600d613bc1775afb7e5de2d8bd17cb416f8f9ec.jpg](../emnlp_results/402_Same%20evaluation%2C%20more%20tokens_%20On%20the%20effect%20of%20input%20length%20for%20machine%20translation%20evaluation%20using/images/87a775dbfa9e6cdbdec10a897600d613bc1775afb7e5de2d8bd17cb416f8f9ec.jpg)

![8d2525b20adc500fb559c1c37015b30e1b6cfc35be981b0b26f941944645fa88.jpg](../emnlp_results/402_Same%20evaluation%2C%20more%20tokens_%20On%20the%20effect%20of%20input%20length%20for%20machine%20translation%20evaluation%20using/images/8d2525b20adc500fb559c1c37015b30e1b6cfc35be981b0b26f941944645fa88.jpg)

![8e59fecefb4a6e656231d8c1c9559facd855897d4d7d2f696fbfd6254b00fe8e.jpg](../emnlp_results/402_Same%20evaluation%2C%20more%20tokens_%20On%20the%20effect%20of%20input%20length%20for%20machine%20translation%20evaluation%20using/images/8e59fecefb4a6e656231d8c1c9559facd855897d4d7d2f696fbfd6254b00fe8e.jpg)

![a7a8e8794ca9fa430fe0d8aa33585a623e419c67f954628dc99dc09ac4d3f0c3.jpg](../emnlp_results/402_Same%20evaluation%2C%20more%20tokens_%20On%20the%20effect%20of%20input%20length%20for%20machine%20translation%20evaluation%20using/images/a7a8e8794ca9fa430fe0d8aa33585a623e419c67f954628dc99dc09ac4d3f0c3.jpg)

![bb220790edca9c54d99a0e4d63ef4dd58b215423cddaa1043fac5d26a2b74575.jpg](../emnlp_results/402_Same%20evaluation%2C%20more%20tokens_%20On%20the%20effect%20of%20input%20length%20for%20machine%20translation%20evaluation%20using/images/bb220790edca9c54d99a0e4d63ef4dd58b215423cddaa1043fac5d26a2b74575.jpg)

![f3e1fc8e401ef8bb1a4189f89ca3242c292d43d48404dd66a7fbfc47fdf1a172.jpg](../emnlp_results/402_Same%20evaluation%2C%20more%20tokens_%20On%20the%20effect%20of%20input%20length%20for%20machine%20translation%20evaluation%20using/images/f3e1fc8e401ef8bb1a4189f89ca3242c292d43d48404dd66a7fbfc47fdf1a172.jpg)

### Tables

![e6bd4fb33a62d8ee304427027ba9b2ec839f7b20bcd598560790c5f888c196a1.jpg](../emnlp_results/402_Same%20evaluation%2C%20more%20tokens_%20On%20the%20effect%20of%20input%20length%20for%20machine%20translation%20evaluation%20using/tables/e6bd4fb33a62d8ee304427027ba9b2ec839f7b20bcd598560790c5f888c196a1.jpg)

![f906c5f8f0311ec6d31233cc72a1f7fc46b7948b9ac1169fc947774eb49b9d5e.jpg](../emnlp_results/402_Same%20evaluation%2C%20more%20tokens_%20On%20the%20effect%20of%20input%20length%20for%20machine%20translation%20evaluation%20using/tables/f906c5f8f0311ec6d31233cc72a1f7fc46b7948b9ac1169fc947774eb49b9d5e.jpg)

## PAKTON: A Multi-Agent Framework for Question Answering in Long Legal Agreements


### Images

![148c1d76352e697d4ab821edcdeb0371f6fba4663ade110de423f3fd8055f0e8.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/images/148c1d76352e697d4ab821edcdeb0371f6fba4663ade110de423f3fd8055f0e8.jpg)

![156946bf027a70cf33a73fe5ad388c9e721b7f19686b1c13f6762e221d6a3e5e.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/images/156946bf027a70cf33a73fe5ad388c9e721b7f19686b1c13f6762e221d6a3e5e.jpg)

![31ae3d12f7c5bfa3c939666f88cb114ed0516fc6b97a5afc82abaf41ef8ca702.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/images/31ae3d12f7c5bfa3c939666f88cb114ed0516fc6b97a5afc82abaf41ef8ca702.jpg)

![34ca6c9c38aabdf5666fd1453893b4233ffe2ab81b7a085a605433b5c144eeba.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/images/34ca6c9c38aabdf5666fd1453893b4233ffe2ab81b7a085a605433b5c144eeba.jpg)

![4524a7bc1ad9c9884358639e8dbf601ad180070f5280e44c1886bd74e2baf531.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/images/4524a7bc1ad9c9884358639e8dbf601ad180070f5280e44c1886bd74e2baf531.jpg)

![4f472f7a9932bc4a2fd9b5688e2dd4e2a311bf556220acd667e012e9050b4b30.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/images/4f472f7a9932bc4a2fd9b5688e2dd4e2a311bf556220acd667e012e9050b4b30.jpg)

![56e8229b9e64750b1050bbe2a990818258b3a850f99a5e00bc7aef983f16be82.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/images/56e8229b9e64750b1050bbe2a990818258b3a850f99a5e00bc7aef983f16be82.jpg)

![85d40bc1fadeb8cb93418a5a0c405ae285dd2f2a0d2a817b1fad19d96ebd458c.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/images/85d40bc1fadeb8cb93418a5a0c405ae285dd2f2a0d2a817b1fad19d96ebd458c.jpg)

![d883b14619c4a1e7fedfc630bce49091db9041e8dbc0fdde21245c796d5f4639.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/images/d883b14619c4a1e7fedfc630bce49091db9041e8dbc0fdde21245c796d5f4639.jpg)

![e5ac378db06676cd1bdfca9c4f46093c0a38d7a610fab2757bb5922e17aaa6d7.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/images/e5ac378db06676cd1bdfca9c4f46093c0a38d7a610fab2757bb5922e17aaa6d7.jpg)

![f4444c24a7adc69b342b831f5c76ef1452de2e23c5b05bd9c50a57830bd075ba.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/images/f4444c24a7adc69b342b831f5c76ef1452de2e23c5b05bd9c50a57830bd075ba.jpg)

### Tables

![26756cebb749e57ee05615a9031dd46995db4a101d4da86688ab4d684db5b6ea.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/26756cebb749e57ee05615a9031dd46995db4a101d4da86688ab4d684db5b6ea.jpg)

![2941b7e3418131777a6860192c9428d23258061767b688b187bf2532693917b6.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/2941b7e3418131777a6860192c9428d23258061767b688b187bf2532693917b6.jpg)

![32bcff199d5a304610aa38b0e9b19bf49bc90432a3e56d0718c1eb3256ac88a3.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/32bcff199d5a304610aa38b0e9b19bf49bc90432a3e56d0718c1eb3256ac88a3.jpg)

![6abd6bd6c74bf872a4b64fb117f4146b40f848bb869110799b8772efbf0501a9.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/6abd6bd6c74bf872a4b64fb117f4146b40f848bb869110799b8772efbf0501a9.jpg)

![6e829ca84e8c2bd7391f70946aa2b123e1c4eeb48e9b80bff816f0cb1b4eb25b.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/6e829ca84e8c2bd7391f70946aa2b123e1c4eeb48e9b80bff816f0cb1b4eb25b.jpg)

![7550863dfaa2134d94dbdc4ccd529f910cb29b6a8d8bcbe315c7264c0078c957.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/7550863dfaa2134d94dbdc4ccd529f910cb29b6a8d8bcbe315c7264c0078c957.jpg)

![7e274b91bba2e43cbfb0bff5a1a9ed5e089899e4864ee24238e37e9935ac41a6.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/7e274b91bba2e43cbfb0bff5a1a9ed5e089899e4864ee24238e37e9935ac41a6.jpg)

![93ffa480d14ce6f7f9254a71b181b7d0ca7ac7d6321e2ea7f2abae647c170a29.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/93ffa480d14ce6f7f9254a71b181b7d0ca7ac7d6321e2ea7f2abae647c170a29.jpg)

![9d2cac0f2612755718bdfdd357870a3598e1ce6d2f94a7e7c94e2080d82d938f.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/9d2cac0f2612755718bdfdd357870a3598e1ce6d2f94a7e7c94e2080d82d938f.jpg)

![bbd3d3b94f16cff6fbc81fca93850916de7edf660e98cbd727d55d1a3c190ec9.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/bbd3d3b94f16cff6fbc81fca93850916de7edf660e98cbd727d55d1a3c190ec9.jpg)

![c482d3dbb8183a0c83ea1a27d0e47000e58342425ee9e68bbdd1f92d8d96ce8e.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/c482d3dbb8183a0c83ea1a27d0e47000e58342425ee9e68bbdd1f92d8d96ce8e.jpg)

![cbb22100011f3402b4dde927ea17e03b474ab51ae225b9face68972e3857a6d4.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/cbb22100011f3402b4dde927ea17e03b474ab51ae225b9face68972e3857a6d4.jpg)

![d331dacb9cdc822ff0a42f7fb816eba62a54fc692ed49b1975b030c4acd07bc7.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/d331dacb9cdc822ff0a42f7fb816eba62a54fc692ed49b1975b030c4acd07bc7.jpg)

![e4d410f31f3e3d3b6af15052469d3ed947508a82a332e7ae2db7f9b2d92a3a9d.jpg](../emnlp_results/403_PAKTON_%20A%20Multi-Agent%20Framework%20for%20Question%20Answering%20in%20Long%20Legal%20Agreements/tables/e4d410f31f3e3d3b6af15052469d3ed947508a82a332e7ae2db7f9b2d92a3a9d.jpg)

## PoSum-Bench: Benchmarking Position Bias inLLM-based Conversational Summarization


### Images

![0088b9315e2a68957ded8622cebcf1f7e6d2a9aa8842e958948bfc2d7afbfa53.jpg](../emnlp_results/404_PoSum-Bench_%20Benchmarking%20Position%20Bias%20inLLM-based%20Conversational%20Summarization/images/0088b9315e2a68957ded8622cebcf1f7e6d2a9aa8842e958948bfc2d7afbfa53.jpg)

![115cb5c68974d76bd4dcd816fda698c72e54f4bf98bd38f5e067a55626c5c01f.jpg](../emnlp_results/404_PoSum-Bench_%20Benchmarking%20Position%20Bias%20inLLM-based%20Conversational%20Summarization/images/115cb5c68974d76bd4dcd816fda698c72e54f4bf98bd38f5e067a55626c5c01f.jpg)

![170a6f8d2eea834f74177a39c3af9fde02d09d39c11c88388da6088f787e9a7a.jpg](../emnlp_results/404_PoSum-Bench_%20Benchmarking%20Position%20Bias%20inLLM-based%20Conversational%20Summarization/images/170a6f8d2eea834f74177a39c3af9fde02d09d39c11c88388da6088f787e9a7a.jpg)

![196f35e400b269d5ad42a756b623af51f13e58908dd055b085bdaba8cab5cdd1.jpg](../emnlp_results/404_PoSum-Bench_%20Benchmarking%20Position%20Bias%20inLLM-based%20Conversational%20Summarization/images/196f35e400b269d5ad42a756b623af51f13e58908dd055b085bdaba8cab5cdd1.jpg)

![20555e2f827b1f75c6152e94d8837a6b9ee1a94e7796f61398c785ea520f4f96.jpg](../emnlp_results/404_PoSum-Bench_%20Benchmarking%20Position%20Bias%20inLLM-based%20Conversational%20Summarization/images/20555e2f827b1f75c6152e94d8837a6b9ee1a94e7796f61398c785ea520f4f96.jpg)

![8ed32fcb0c04013e562a322c682fbc09a9bbe44855e88a9f63b6c0ac0a093062.jpg](../emnlp_results/404_PoSum-Bench_%20Benchmarking%20Position%20Bias%20inLLM-based%20Conversational%20Summarization/images/8ed32fcb0c04013e562a322c682fbc09a9bbe44855e88a9f63b6c0ac0a093062.jpg)

### Tables

![31045cb09824a0f24efe056b50014ecdbefbbc85d5c5535fc79519c11c5c1253.jpg](../emnlp_results/404_PoSum-Bench_%20Benchmarking%20Position%20Bias%20inLLM-based%20Conversational%20Summarization/tables/31045cb09824a0f24efe056b50014ecdbefbbc85d5c5535fc79519c11c5c1253.jpg)

![5f3bef9a1f068b47730ded7e95918b40a36d2137284c498822a10fc70f38b519.jpg](../emnlp_results/404_PoSum-Bench_%20Benchmarking%20Position%20Bias%20inLLM-based%20Conversational%20Summarization/tables/5f3bef9a1f068b47730ded7e95918b40a36d2137284c498822a10fc70f38b519.jpg)

![a250c9128ab09d4f1118e4ff6b59bb041da0de5cf873c3a42cfe80607fc17018.jpg](../emnlp_results/404_PoSum-Bench_%20Benchmarking%20Position%20Bias%20inLLM-based%20Conversational%20Summarization/tables/a250c9128ab09d4f1118e4ff6b59bb041da0de5cf873c3a42cfe80607fc17018.jpg)

![ae9f26929f6695d2b396b9cf50012ae2415dfc9e4a0ec4de7ba104bee18802df.jpg](../emnlp_results/404_PoSum-Bench_%20Benchmarking%20Position%20Bias%20inLLM-based%20Conversational%20Summarization/tables/ae9f26929f6695d2b396b9cf50012ae2415dfc9e4a0ec4de7ba104bee18802df.jpg)

![e87393aee9b0bb836a721d6e10c0aca5a40e628170b7646e426b2b56d8f00472.jpg](../emnlp_results/404_PoSum-Bench_%20Benchmarking%20Position%20Bias%20inLLM-based%20Conversational%20Summarization/tables/e87393aee9b0bb836a721d6e10c0aca5a40e628170b7646e426b2b56d8f00472.jpg)

![f451e5307c8eb45440180263e6bdeb4871e196556e5bbfeae5128039557f04e5.jpg](../emnlp_results/404_PoSum-Bench_%20Benchmarking%20Position%20Bias%20inLLM-based%20Conversational%20Summarization/tables/f451e5307c8eb45440180263e6bdeb4871e196556e5bbfeae5128039557f04e5.jpg)

![f58727ede08e4f24aa0f1a8cfbc372f656e7af0e206fd86b62ba43be102d18e3.jpg](../emnlp_results/404_PoSum-Bench_%20Benchmarking%20Position%20Bias%20inLLM-based%20Conversational%20Summarization/tables/f58727ede08e4f24aa0f1a8cfbc372f656e7af0e206fd86b62ba43be102d18e3.jpg)

## ConCISE: Confidence-guided Compression in Step-by-step Efficient Reasoning


### Images

![100851e4818f4fd611554882b78de784bdf4be9a59b38f828863003cc117bd69.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/images/100851e4818f4fd611554882b78de784bdf4be9a59b38f828863003cc117bd69.jpg)

![1bfd7ad8a19f351eb13f6200d99e630f6cb2a6959348d0a7509ba22962ce0a09.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/images/1bfd7ad8a19f351eb13f6200d99e630f6cb2a6959348d0a7509ba22962ce0a09.jpg)

![2af9d9275bd6b8c81acf774c1126f8118d7fea79bd36741e5450633e330cbcb1.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/images/2af9d9275bd6b8c81acf774c1126f8118d7fea79bd36741e5450633e330cbcb1.jpg)

![3126249f996776458e3dbcc7e95d56a3b330a0efcef66dc80790d475b301a9e1.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/images/3126249f996776458e3dbcc7e95d56a3b330a0efcef66dc80790d475b301a9e1.jpg)

![6edcda920a234d739ec6f4ed9b765d347fbc0ecb230728aa627224fdb40c8faa.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/images/6edcda920a234d739ec6f4ed9b765d347fbc0ecb230728aa627224fdb40c8faa.jpg)

![7e32aa9c3c18b6f539afc2c052e5b36260998f611ada0b8462520aab6114f43d.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/images/7e32aa9c3c18b6f539afc2c052e5b36260998f611ada0b8462520aab6114f43d.jpg)

![83bca8cf1c8e3eb1b9bdfcf37d78bdfaa406c2be0daf17674fbe5677170018f6.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/images/83bca8cf1c8e3eb1b9bdfcf37d78bdfaa406c2be0daf17674fbe5677170018f6.jpg)

![8b15713bbcf9bac028041bbb68790e23dffc5171283720400f0f92705b519a93.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/images/8b15713bbcf9bac028041bbb68790e23dffc5171283720400f0f92705b519a93.jpg)

![8d59d5a0edf4bc3ef53658121a576b69ead4aba3365bcdde487935641c0b3278.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/images/8d59d5a0edf4bc3ef53658121a576b69ead4aba3365bcdde487935641c0b3278.jpg)

![936e06f5cb6de712b8a6d1cf5a1090a1c0708b8993296f4b758cfa2a430d9dd1.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/images/936e06f5cb6de712b8a6d1cf5a1090a1c0708b8993296f4b758cfa2a430d9dd1.jpg)

![b93fdcdefe797fe45c14a9c4091e54b0cfa50131f03027ad9162dbb120a365eb.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/images/b93fdcdefe797fe45c14a9c4091e54b0cfa50131f03027ad9162dbb120a365eb.jpg)

![efb2d1441854f18f3e2325c25a40aee2565f2fd9141d29e5e375b00401bc00ca.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/images/efb2d1441854f18f3e2325c25a40aee2565f2fd9141d29e5e375b00401bc00ca.jpg)

![fd370e564fd4745ba9176f4442952cad1b9a438c9abd47b205d267c83a7cb6b3.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/images/fd370e564fd4745ba9176f4442952cad1b9a438c9abd47b205d267c83a7cb6b3.jpg)

### Tables

![0e63dc7b4e7bda392a8fc9f35e70a730ca94c3420168c9eef7da6cc2e79702fe.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/tables/0e63dc7b4e7bda392a8fc9f35e70a730ca94c3420168c9eef7da6cc2e79702fe.jpg)

![2cb62b64bb1213e5260e296c963ea5b887a4b2a8cc00ea216c60d426b17fdde4.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/tables/2cb62b64bb1213e5260e296c963ea5b887a4b2a8cc00ea216c60d426b17fdde4.jpg)

![55c980de2e91898bf037e5803b3668eb5fcc82912da168ca588858f3add2c663.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/tables/55c980de2e91898bf037e5803b3668eb5fcc82912da168ca588858f3add2c663.jpg)

![756abd50292ba22895f317db9d368a1e00adc44e9b606fc5c6d268f3cc730c9f.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/tables/756abd50292ba22895f317db9d368a1e00adc44e9b606fc5c6d268f3cc730c9f.jpg)

![b5bf4349f1ed0a4ba2b35fd6df584993d9a2d63c86c2c23d346aae16c0a640b0.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/tables/b5bf4349f1ed0a4ba2b35fd6df584993d9a2d63c86c2c23d346aae16c0a640b0.jpg)

![fe0011c7f273cdc8c42267e725bbf257de9190dd621e2d8b9d5f7f5af1438cdf.jpg](../emnlp_results/405_ConCISE_%20Confidence-guided%20Compression%20in%20Step-by-step%20Efficient%20Reasoning/tables/fe0011c7f273cdc8c42267e725bbf257de9190dd621e2d8b9d5f7f5af1438cdf.jpg)

## Layer-Aware Representation Filtering: Purifying Finetuning Data to PreserveLLMSafety Alignment


### Images

![0c7eb981f097930995eb82d74d56ce602973e6d45572d388c3f9d48e603370c3.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/0c7eb981f097930995eb82d74d56ce602973e6d45572d388c3f9d48e603370c3.jpg)

![1403e6d3c0f3fa57e8aaefb03b310981c6c54e3f0445579432aada99892a5128.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/1403e6d3c0f3fa57e8aaefb03b310981c6c54e3f0445579432aada99892a5128.jpg)

![1728ec17fdceeb44e1b9449906732a2285980e2ef8533346ca1553ec99f5d151.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/1728ec17fdceeb44e1b9449906732a2285980e2ef8533346ca1553ec99f5d151.jpg)

![19c5df69b416350994a2a0ddce035e8db8c475cee76b92a4c4dd1236ed7f5b59.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/19c5df69b416350994a2a0ddce035e8db8c475cee76b92a4c4dd1236ed7f5b59.jpg)

![2bfeb8823dfcb356da330b8a12e739061247674add410cc9e0bea66a254d3dba.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/2bfeb8823dfcb356da330b8a12e739061247674add410cc9e0bea66a254d3dba.jpg)

![4befb59bd3ec76d61b856be22933f0302b31e79d61e51018c6eeaeeb3cdfd862.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/4befb59bd3ec76d61b856be22933f0302b31e79d61e51018c6eeaeeb3cdfd862.jpg)

![573c04bca8c072374687d1afcaa5e0080c90a6d7736e9112df41f82735c2246e.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/573c04bca8c072374687d1afcaa5e0080c90a6d7736e9112df41f82735c2246e.jpg)

![5c1dcab135ddf718a1b6b811c7b25e3c0abb41b54e4ba44a9622e257ae2a7916.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/5c1dcab135ddf718a1b6b811c7b25e3c0abb41b54e4ba44a9622e257ae2a7916.jpg)

![6e7b5af29203579848b131e1cb6b8d41900754f3e778f64578716013741dbd42.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/6e7b5af29203579848b131e1cb6b8d41900754f3e778f64578716013741dbd42.jpg)

![79bfd5eb3e78ad7ac6a2fbc7086eade39f656eef0f1ae81825c11f1b585e1822.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/79bfd5eb3e78ad7ac6a2fbc7086eade39f656eef0f1ae81825c11f1b585e1822.jpg)

![82bfdbecfff8acda9b0ab5ecb8fc521d5bd0c70285291425671404f579b069d3.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/82bfdbecfff8acda9b0ab5ecb8fc521d5bd0c70285291425671404f579b069d3.jpg)

![87e32e18095f5ce0a249b5a664bfa93ec5d8439650567055fa7ba65fa89e2e75.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/87e32e18095f5ce0a249b5a664bfa93ec5d8439650567055fa7ba65fa89e2e75.jpg)

![9234e678d0a888640ce31ced61ae00f281f8fda3160ba7967bcdc06085d7e3c9.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/9234e678d0a888640ce31ced61ae00f281f8fda3160ba7967bcdc06085d7e3c9.jpg)

![a1d12e31eb7657ec13faa8dfed5dacca4d5433a14deae230cd00860cad730a51.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/a1d12e31eb7657ec13faa8dfed5dacca4d5433a14deae230cd00860cad730a51.jpg)

![a2f4e70e1ba415301dc146aebf405ec8bee8cb73a32bd20059d25df70d918fd1.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/a2f4e70e1ba415301dc146aebf405ec8bee8cb73a32bd20059d25df70d918fd1.jpg)

![a938c0533c277cbb64b187933f5ff0c6ed988af52333770b0e9dd07ded7e5508.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/a938c0533c277cbb64b187933f5ff0c6ed988af52333770b0e9dd07ded7e5508.jpg)

![c675e0655678d23b277c4c6b66361f0d1e469ff2547efa720dd382fac86bbeba.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/c675e0655678d23b277c4c6b66361f0d1e469ff2547efa720dd382fac86bbeba.jpg)

![ce8845946412f60d5eb99f029fc12d561aa12f0c884b6f6f2e579b8f9572f679.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/ce8845946412f60d5eb99f029fc12d561aa12f0c884b6f6f2e579b8f9572f679.jpg)

![d7bceef172bd3aff89aff810f3b3972f64fd0c22cf830f8268d6be19ea557461.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/d7bceef172bd3aff89aff810f3b3972f64fd0c22cf830f8268d6be19ea557461.jpg)

![db34f2f23a0d62ae3b042982d9c8f2d28aeb08349de1c998961d9631f34d925c.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/db34f2f23a0d62ae3b042982d9c8f2d28aeb08349de1c998961d9631f34d925c.jpg)

![fb1a5efb49ba18070125c944680982c9782fa14b57d5de733c2ec7860ccc6a3d.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/images/fb1a5efb49ba18070125c944680982c9782fa14b57d5de733c2ec7860ccc6a3d.jpg)

### Tables

![07c7cf4c0161d8235dedc401d1abd7bf9ed6fd24d6cb6807156b3556aa8224c4.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/tables/07c7cf4c0161d8235dedc401d1abd7bf9ed6fd24d6cb6807156b3556aa8224c4.jpg)

![1f596df129df41380f122ac53cf78d5cf2806a9f08effbcdc0fc6a3a05e436b7.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/tables/1f596df129df41380f122ac53cf78d5cf2806a9f08effbcdc0fc6a3a05e436b7.jpg)

![33c615d31257fc59f7df833ab0f3263e879a4fadaeba84445e7c3f42b1eec545.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/tables/33c615d31257fc59f7df833ab0f3263e879a4fadaeba84445e7c3f42b1eec545.jpg)

![3495596ba7540da9c14ca4a2c4a505d3c89bfbec37007c25460e999d77f4f1f0.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/tables/3495596ba7540da9c14ca4a2c4a505d3c89bfbec37007c25460e999d77f4f1f0.jpg)

![3da23802c8aa1042dc7140b3243510283f51d9799e4f7fdddbbcad6adfa52122.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/tables/3da23802c8aa1042dc7140b3243510283f51d9799e4f7fdddbbcad6adfa52122.jpg)

![43e41a15648d0cd7af6076dca205e513d8b77b209671ff5ffe276271e7f6269b.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/tables/43e41a15648d0cd7af6076dca205e513d8b77b209671ff5ffe276271e7f6269b.jpg)

![67257951105089d116487422fab761705a2ad377476f0ea2ff6c2282d9961ab0.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/tables/67257951105089d116487422fab761705a2ad377476f0ea2ff6c2282d9961ab0.jpg)

![7db8d461e024632ce9ea5057f791b856bfbf0c9c29c7fdfbfaebb2011733bdea.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/tables/7db8d461e024632ce9ea5057f791b856bfbf0c9c29c7fdfbfaebb2011733bdea.jpg)

![d23ad8b989bb5d66d448ffc5f408d407dbb7be7777c393122130568fa1f3f58e.jpg](../emnlp_results/406_Layer-Aware%20Representation%20Filtering_%20Purifying%20Finetuning%20Data%20to%20PreserveLLMSafety%20Alignment/tables/d23ad8b989bb5d66d448ffc5f408d407dbb7be7777c393122130568fa1f3f58e.jpg)

## Cross-domain Rumor Detection via Test-Time Adaptation and Large Language Models


### Images

![23fd968e4b40e6772d45863c617aa82d99d20048b5fe55f6083bb22ba2c5ae27.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/images/23fd968e4b40e6772d45863c617aa82d99d20048b5fe55f6083bb22ba2c5ae27.jpg)

![2966ef28f237c5e85b4388055c17f3f29ad663c0491dd101f0d5fffc18882f4b.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/images/2966ef28f237c5e85b4388055c17f3f29ad663c0491dd101f0d5fffc18882f4b.jpg)

![537add05bfe0d5605e2a3d8d4a72532f834e6262d25e9b19eb15313116a40183.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/images/537add05bfe0d5605e2a3d8d4a72532f834e6262d25e9b19eb15313116a40183.jpg)

![620dcb6e84ababfbd6574b7a84c9a78e15a6b11bc143f0d4bebeef5347c84b41.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/images/620dcb6e84ababfbd6574b7a84c9a78e15a6b11bc143f0d4bebeef5347c84b41.jpg)

![7a4c99962e44732391df98211b223fb09c6606f7cc4ebbdb04802dcac6e551c9.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/images/7a4c99962e44732391df98211b223fb09c6606f7cc4ebbdb04802dcac6e551c9.jpg)

![87cc4122dc7a0d829cc272efcfccdb47da4b58cc4e6f57822dda5704589334b2.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/images/87cc4122dc7a0d829cc272efcfccdb47da4b58cc4e6f57822dda5704589334b2.jpg)

![a684509c810f913d8ab8e6ec2b2741999662f40910871a4c88cfb810fb167356.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/images/a684509c810f913d8ab8e6ec2b2741999662f40910871a4c88cfb810fb167356.jpg)

![d3ae0e9833b734bbeee14c5d415cd4cf3f8e756ff5b4a82796f604b3dd31d522.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/images/d3ae0e9833b734bbeee14c5d415cd4cf3f8e756ff5b4a82796f604b3dd31d522.jpg)

![f5416f3111efac236b905805449e0589e5a12650ddc4e88ae9e87c538639a8f3.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/images/f5416f3111efac236b905805449e0589e5a12650ddc4e88ae9e87c538639a8f3.jpg)

### Tables

![0cf41a62482d9d9de21c8f327b80c5b830f3459c365746e9e95ac5461a5aff2b.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/tables/0cf41a62482d9d9de21c8f327b80c5b830f3459c365746e9e95ac5461a5aff2b.jpg)

![130e3f8f4e9f6352ae857762aafe1c8d9ac787a87e27a5c7658e4bb9e31152b0.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/tables/130e3f8f4e9f6352ae857762aafe1c8d9ac787a87e27a5c7658e4bb9e31152b0.jpg)

![2241b7494e62e5d54d1c693ffdca82eef9232108c3ecf7b831aa081cd10c2c84.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/tables/2241b7494e62e5d54d1c693ffdca82eef9232108c3ecf7b831aa081cd10c2c84.jpg)

![2639f0114cbe46594799db0cb95a7417f7f5600b080d43a561bec6fc9d2f2647.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/tables/2639f0114cbe46594799db0cb95a7417f7f5600b080d43a561bec6fc9d2f2647.jpg)

![2b10a94ee10e8369ee9fe4d326b5c9c768c17d4dc335d18abdc178376b0cd5e5.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/tables/2b10a94ee10e8369ee9fe4d326b5c9c768c17d4dc335d18abdc178376b0cd5e5.jpg)

![502042d60bf60b490c9e16c0484900468eabf668f5f2cebcc803ad2db9d84ce8.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/tables/502042d60bf60b490c9e16c0484900468eabf668f5f2cebcc803ad2db9d84ce8.jpg)

![52de9335ec0077b0017265b8b64aaee5dcb7fc30686b59534f19c3c7130e507e.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/tables/52de9335ec0077b0017265b8b64aaee5dcb7fc30686b59534f19c3c7130e507e.jpg)

![9afc9f906e52b79e9f8445eebb840f555612e0b1ea8c838eaf64fa29a99d9670.jpg](../emnlp_results/407_Cross-domain%20Rumor%20Detection%20via%20Test-Time%20Adaptation%20and%20Large%20Language%20Models/tables/9afc9f906e52b79e9f8445eebb840f555612e0b1ea8c838eaf64fa29a99d9670.jpg)

## MLWQ: Efficient Small Language Model Deployment via Multi-Level Weight Quantization


### Images

![444b96562e1090641b04e5b43f205f3e9c1e8d90cbed15886b53f67441bfae2c.jpg](../emnlp_results/408_MLWQ_%20Efficient%20Small%20Language%20Model%20Deployment%20via%20Multi-Level%20Weight%20Quantization/images/444b96562e1090641b04e5b43f205f3e9c1e8d90cbed15886b53f67441bfae2c.jpg)

![5760a7fc72620d19d9ba6b9a2ee7a8558632a7d0f99441977aaf924991f384de.jpg](../emnlp_results/408_MLWQ_%20Efficient%20Small%20Language%20Model%20Deployment%20via%20Multi-Level%20Weight%20Quantization/images/5760a7fc72620d19d9ba6b9a2ee7a8558632a7d0f99441977aaf924991f384de.jpg)

![5ce28cc54d507e78dd1f98343ce4ece738763ccad3f95d72eede884ae76932cd.jpg](../emnlp_results/408_MLWQ_%20Efficient%20Small%20Language%20Model%20Deployment%20via%20Multi-Level%20Weight%20Quantization/images/5ce28cc54d507e78dd1f98343ce4ece738763ccad3f95d72eede884ae76932cd.jpg)

![5f292cc842377ba0a69b68ac677459dcab8794b848261ad175da5a464744e79d.jpg](../emnlp_results/408_MLWQ_%20Efficient%20Small%20Language%20Model%20Deployment%20via%20Multi-Level%20Weight%20Quantization/images/5f292cc842377ba0a69b68ac677459dcab8794b848261ad175da5a464744e79d.jpg)

![cad5d1eead53d95813061344bc9c4e049330b6dfa7c6b64d0d229bc73a68227c.jpg](../emnlp_results/408_MLWQ_%20Efficient%20Small%20Language%20Model%20Deployment%20via%20Multi-Level%20Weight%20Quantization/images/cad5d1eead53d95813061344bc9c4e049330b6dfa7c6b64d0d229bc73a68227c.jpg)

![ed1d2eec1b07895714564ec4d6af97d3a29be407eea4ded699e21448035fcbc3.jpg](../emnlp_results/408_MLWQ_%20Efficient%20Small%20Language%20Model%20Deployment%20via%20Multi-Level%20Weight%20Quantization/images/ed1d2eec1b07895714564ec4d6af97d3a29be407eea4ded699e21448035fcbc3.jpg)

### Tables

![2340c921cfc1b2410fef8ebf572be2c729340f2bbe3563480d94f5c69cda91b0.jpg](../emnlp_results/408_MLWQ_%20Efficient%20Small%20Language%20Model%20Deployment%20via%20Multi-Level%20Weight%20Quantization/tables/2340c921cfc1b2410fef8ebf572be2c729340f2bbe3563480d94f5c69cda91b0.jpg)

![3201e4bf3542d293e857f9b8e681b54c85b8faec61008f0847ec3559ea878d79.jpg](../emnlp_results/408_MLWQ_%20Efficient%20Small%20Language%20Model%20Deployment%20via%20Multi-Level%20Weight%20Quantization/tables/3201e4bf3542d293e857f9b8e681b54c85b8faec61008f0847ec3559ea878d79.jpg)

![96caf8d97b4e111ba5efd211434282396f345f6edd474df40713a82cf7acda4a.jpg](../emnlp_results/408_MLWQ_%20Efficient%20Small%20Language%20Model%20Deployment%20via%20Multi-Level%20Weight%20Quantization/tables/96caf8d97b4e111ba5efd211434282396f345f6edd474df40713a82cf7acda4a.jpg)

![aa04187eeacda2665d3e37c6e6557574c1cfa7b9816cdb16aa36d69e66fb76ab.jpg](../emnlp_results/408_MLWQ_%20Efficient%20Small%20Language%20Model%20Deployment%20via%20Multi-Level%20Weight%20Quantization/tables/aa04187eeacda2665d3e37c6e6557574c1cfa7b9816cdb16aa36d69e66fb76ab.jpg)

![b440d5111a38b7dadef9f91de2a22fd8dbb70abe044d356593da4f0244b2f4b9.jpg](../emnlp_results/408_MLWQ_%20Efficient%20Small%20Language%20Model%20Deployment%20via%20Multi-Level%20Weight%20Quantization/tables/b440d5111a38b7dadef9f91de2a22fd8dbb70abe044d356593da4f0244b2f4b9.jpg)

![d68a49d9042808830a81b7a799446868dd8f847010ba2116519b34cb2f2be59c.jpg](../emnlp_results/408_MLWQ_%20Efficient%20Small%20Language%20Model%20Deployment%20via%20Multi-Level%20Weight%20Quantization/tables/d68a49d9042808830a81b7a799446868dd8f847010ba2116519b34cb2f2be59c.jpg)

![e57bc0ee6d9b0a29102524d5a052c99cdc5c4aa805dcb5afcdf01ec61e4bef20.jpg](../emnlp_results/408_MLWQ_%20Efficient%20Small%20Language%20Model%20Deployment%20via%20Multi-Level%20Weight%20Quantization/tables/e57bc0ee6d9b0a29102524d5a052c99cdc5c4aa805dcb5afcdf01ec61e4bef20.jpg)

## ToDi: Token-wise Distillation via Fine-Grained Divergence Control


### Images

![0e40b5d9848100c3794eb406ed8ec5275ff8745695c44d2400225a66d6c036cf.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/images/0e40b5d9848100c3794eb406ed8ec5275ff8745695c44d2400225a66d6c036cf.jpg)

![2f16c3151f74fb7fff9cfe6a66b4fe46a5a2543f70b2ea8c50632bc268c8894e.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/images/2f16c3151f74fb7fff9cfe6a66b4fe46a5a2543f70b2ea8c50632bc268c8894e.jpg)

![7710e74370a29608f0527a182d85c907c35b8bcc2910b54899e4f49071ea6a03.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/images/7710e74370a29608f0527a182d85c907c35b8bcc2910b54899e4f49071ea6a03.jpg)

![854816e9b5112a5520774f3c5d82201d5cce16f9b40c269ac5884c4adbeaa2d2.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/images/854816e9b5112a5520774f3c5d82201d5cce16f9b40c269ac5884c4adbeaa2d2.jpg)

![94312295cff8d2688f216ab6e7269d051306e40e565f08bd7b669497c826cf14.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/images/94312295cff8d2688f216ab6e7269d051306e40e565f08bd7b669497c826cf14.jpg)

![dc7b438179411dc73e3aea19e4f5f7f378f1788eadfc0d1a330c12b4d2acbb52.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/images/dc7b438179411dc73e3aea19e4f5f7f378f1788eadfc0d1a330c12b4d2acbb52.jpg)

![f413d5c08ad00dcbdaddf93c3267350a60b5c2b1dc92ac3b6108fcd912c1b36c.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/images/f413d5c08ad00dcbdaddf93c3267350a60b5c2b1dc92ac3b6108fcd912c1b36c.jpg)

### Tables

![49244b9ccf64ac80a5e7cefa7e503b0260e9b71548ea31abd950d2086d07b80c.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/tables/49244b9ccf64ac80a5e7cefa7e503b0260e9b71548ea31abd950d2086d07b80c.jpg)

![62e3f997fa7bdb170c5c2ff30a0122e4acd983342c32eb0adcdd2f89a6ed3a33.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/tables/62e3f997fa7bdb170c5c2ff30a0122e4acd983342c32eb0adcdd2f89a6ed3a33.jpg)

![877499aeab8e9da63d561750197573e3c1d3a865f8a4013d9ae871fe6cc15e1a.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/tables/877499aeab8e9da63d561750197573e3c1d3a865f8a4013d9ae871fe6cc15e1a.jpg)

![c068c2d028bacfbb6dcc1c5bedb6bf4b78ae3d83c9a8d31a000a8373e8125581.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/tables/c068c2d028bacfbb6dcc1c5bedb6bf4b78ae3d83c9a8d31a000a8373e8125581.jpg)

![df9489f862191f631d2369829b4080010a9f4d61a9455baea4f77088be1d783b.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/tables/df9489f862191f631d2369829b4080010a9f4d61a9455baea4f77088be1d783b.jpg)

![e17c7afd32b7aa4e31900e2e6202af8ad3a26491fb82ac00cabb17b1f79125be.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/tables/e17c7afd32b7aa4e31900e2e6202af8ad3a26491fb82ac00cabb17b1f79125be.jpg)

![f59e4b5f26dc809cc56a014d3d2a60db2c6cce7c05fe76c59272b01e5a056533.jpg](../emnlp_results/409_ToDi_%20Token-wise%20Distillation%20via%20Fine-Grained%20Divergence%20Control/tables/f59e4b5f26dc809cc56a014d3d2a60db2c6cce7c05fe76c59272b01e5a056533.jpg)

## RethinkMCTS: Refining Erroneous Thoughts inMonteCarlo Tree Search for Code Generation


### Images

![1a828a2ed0a82b8450a89a54ad9f597ae8710603f15beabfa309fc1684af9cd8.jpg](../emnlp_results/410_RethinkMCTS_%20Refining%20Erroneous%20Thoughts%20inMonteCarlo%20Tree%20Search%20for%20Code%20Generation/images/1a828a2ed0a82b8450a89a54ad9f597ae8710603f15beabfa309fc1684af9cd8.jpg)

![1c88d754df055958ee7ba4b6f8df065e96261e5953cbb97d258ed3a4cca40069.jpg](../emnlp_results/410_RethinkMCTS_%20Refining%20Erroneous%20Thoughts%20inMonteCarlo%20Tree%20Search%20for%20Code%20Generation/images/1c88d754df055958ee7ba4b6f8df065e96261e5953cbb97d258ed3a4cca40069.jpg)

![2a2c9e865031a7d76f6fca80c0fdec80a97b3892fad387222d324929227c85c8.jpg](../emnlp_results/410_RethinkMCTS_%20Refining%20Erroneous%20Thoughts%20inMonteCarlo%20Tree%20Search%20for%20Code%20Generation/images/2a2c9e865031a7d76f6fca80c0fdec80a97b3892fad387222d324929227c85c8.jpg)

![57204052c7c70c3024c5490c3cacebe7e87ec378961b3cfdb0e96c8300933961.jpg](../emnlp_results/410_RethinkMCTS_%20Refining%20Erroneous%20Thoughts%20inMonteCarlo%20Tree%20Search%20for%20Code%20Generation/images/57204052c7c70c3024c5490c3cacebe7e87ec378961b3cfdb0e96c8300933961.jpg)

![9efc883a89cbe84e9a1135536801809cdb371b4eeb5f68812cdcdcb25bd7db22.jpg](../emnlp_results/410_RethinkMCTS_%20Refining%20Erroneous%20Thoughts%20inMonteCarlo%20Tree%20Search%20for%20Code%20Generation/images/9efc883a89cbe84e9a1135536801809cdb371b4eeb5f68812cdcdcb25bd7db22.jpg)

![d829dab64db4d816128d0e70387edfad014cdbe6b873fcb9fa8edf7e925428d7.jpg](../emnlp_results/410_RethinkMCTS_%20Refining%20Erroneous%20Thoughts%20inMonteCarlo%20Tree%20Search%20for%20Code%20Generation/images/d829dab64db4d816128d0e70387edfad014cdbe6b873fcb9fa8edf7e925428d7.jpg)

### Tables

![08356486983b189c8017e4c49c806f9d119dd2aaef375fb7b11bc945ddf5d303.jpg](../emnlp_results/410_RethinkMCTS_%20Refining%20Erroneous%20Thoughts%20inMonteCarlo%20Tree%20Search%20for%20Code%20Generation/tables/08356486983b189c8017e4c49c806f9d119dd2aaef375fb7b11bc945ddf5d303.jpg)

![1a61fa08205e96add10bb40e9be62e810bff0d2fa4e8c2ca347ae4ab9aa6ffaa.jpg](../emnlp_results/410_RethinkMCTS_%20Refining%20Erroneous%20Thoughts%20inMonteCarlo%20Tree%20Search%20for%20Code%20Generation/tables/1a61fa08205e96add10bb40e9be62e810bff0d2fa4e8c2ca347ae4ab9aa6ffaa.jpg)

![24ac2364a6782df147f0eb9f14e58516c072f27c25d04baa6c43174bd02e4db5.jpg](../emnlp_results/410_RethinkMCTS_%20Refining%20Erroneous%20Thoughts%20inMonteCarlo%20Tree%20Search%20for%20Code%20Generation/tables/24ac2364a6782df147f0eb9f14e58516c072f27c25d04baa6c43174bd02e4db5.jpg)

![63d901547878484b6355e3cb76dc321e9f2be7f9244cf5e263c8f0ca672e6b76.jpg](../emnlp_results/410_RethinkMCTS_%20Refining%20Erroneous%20Thoughts%20inMonteCarlo%20Tree%20Search%20for%20Code%20Generation/tables/63d901547878484b6355e3cb76dc321e9f2be7f9244cf5e263c8f0ca672e6b76.jpg)

![9686cf70c2bc48c5e26fbcb9f94926c2f76f2c6fc299fad8d21405f8c8f55797.jpg](../emnlp_results/410_RethinkMCTS_%20Refining%20Erroneous%20Thoughts%20inMonteCarlo%20Tree%20Search%20for%20Code%20Generation/tables/9686cf70c2bc48c5e26fbcb9f94926c2f76f2c6fc299fad8d21405f8c8f55797.jpg)

![b74b3afe4cca984413fe1c1e5b3409b21983917a0928cc42199d9e1d48e08ec0.jpg](../emnlp_results/410_RethinkMCTS_%20Refining%20Erroneous%20Thoughts%20inMonteCarlo%20Tree%20Search%20for%20Code%20Generation/tables/b74b3afe4cca984413fe1c1e5b3409b21983917a0928cc42199d9e1d48e08ec0.jpg)

![f1db8e1da5e43c2398f9727ef8172203870ab5bf5c6e7d6179e970397e7d7fd0.jpg](../emnlp_results/410_RethinkMCTS_%20Refining%20Erroneous%20Thoughts%20inMonteCarlo%20Tree%20Search%20for%20Code%20Generation/tables/f1db8e1da5e43c2398f9727ef8172203870ab5bf5c6e7d6179e970397e7d7fd0.jpg)

## Probing for Arithmetic Errors in Language Models


### Images

![2205757d699e27ebba361f227209b28d3befc2581e262f536ee0884f260414d9.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/images/2205757d699e27ebba361f227209b28d3befc2581e262f536ee0884f260414d9.jpg)

![3427bfbf28785ad197e0ff707be3c0e91cf208e0c3cb0d4a6a7b2e667172e9a2.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/images/3427bfbf28785ad197e0ff707be3c0e91cf208e0c3cb0d4a6a7b2e667172e9a2.jpg)

![3b19795e0989e73f2956ffc553ed23212818948b76fda31c5ef86b43777784b0.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/images/3b19795e0989e73f2956ffc553ed23212818948b76fda31c5ef86b43777784b0.jpg)

![5354f82d564b8961eb1ee68abeb3fce774662b0c5aa54d52be3e632b8f1c73d8.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/images/5354f82d564b8961eb1ee68abeb3fce774662b0c5aa54d52be3e632b8f1c73d8.jpg)

![6467a00c8a45a1ef0f825e44e8402cf7aba3a5f3359da68debf9425fddf1ed85.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/images/6467a00c8a45a1ef0f825e44e8402cf7aba3a5f3359da68debf9425fddf1ed85.jpg)

![6efbfbdba6daab54c4a7061a656c75f2309ad4f6272efdf9370a5fe7ec6d5f82.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/images/6efbfbdba6daab54c4a7061a656c75f2309ad4f6272efdf9370a5fe7ec6d5f82.jpg)

![7124f19176543ba3ea4bdf5c82ec574f09fec38c1cdd1f2ac8a73dbb50c405c9.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/images/7124f19176543ba3ea4bdf5c82ec574f09fec38c1cdd1f2ac8a73dbb50c405c9.jpg)

![9559a1aeed3a4af599827368ecfd200bb8abb2512f70504d5b7a587be9b5e944.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/images/9559a1aeed3a4af599827368ecfd200bb8abb2512f70504d5b7a587be9b5e944.jpg)

![a04df46d2138619b75546a35dfd7233b3fa27f6f195f55c5254de75b026edf9c.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/images/a04df46d2138619b75546a35dfd7233b3fa27f6f195f55c5254de75b026edf9c.jpg)

![c33d4d74cfb78e55102cff53c995c6168af955c420a940092907c2774990bb78.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/images/c33d4d74cfb78e55102cff53c995c6168af955c420a940092907c2774990bb78.jpg)

### Tables

![358acb142fdf8ea644f61e9165547a7b810583113fb9d19e6733b3675fd66e06.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/tables/358acb142fdf8ea644f61e9165547a7b810583113fb9d19e6733b3675fd66e06.jpg)

![4d7766231b62070ffe829ae03f450163dc9eb197c63bacc9da6c8a50aa059c96.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/tables/4d7766231b62070ffe829ae03f450163dc9eb197c63bacc9da6c8a50aa059c96.jpg)

![7a97599c1fad4ad8b98fb1eb9b0bf6400b0e3999cc7db1bed5a827afcc4bb7fd.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/tables/7a97599c1fad4ad8b98fb1eb9b0bf6400b0e3999cc7db1bed5a827afcc4bb7fd.jpg)

![e2261d851a7dc189f6a7c3ffbd4cf26d445cd5817ae3f352b0d4ad5cf9c606f0.jpg](../emnlp_results/411_Probing%20for%20Arithmetic%20Errors%20in%20Language%20Models/tables/e2261d851a7dc189f6a7c3ffbd4cf26d445cd5817ae3f352b0d4ad5cf9c606f0.jpg)

## NILE: Internal Consistency Alignment in Large Language Models


### Images

![1e455be782cfdf00887193fab0c2c19354d09a7dfd9de6b9e4e477fa4b6e6cee.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/images/1e455be782cfdf00887193fab0c2c19354d09a7dfd9de6b9e4e477fa4b6e6cee.jpg)

![3cf4f4dad2b01f45ed9a2a795dbc19a70b19aaabcde322a9db851dd263b08b3f.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/images/3cf4f4dad2b01f45ed9a2a795dbc19a70b19aaabcde322a9db851dd263b08b3f.jpg)

![48618a28ce8d7da6ff4ea4f2d2ae9c77ba57acac96297e9fd2a43a70d1065730.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/images/48618a28ce8d7da6ff4ea4f2d2ae9c77ba57acac96297e9fd2a43a70d1065730.jpg)

![7849847b42c81a044fe5c052f1c681a6a17fa4cff1681feada47f9b88f1ed123.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/images/7849847b42c81a044fe5c052f1c681a6a17fa4cff1681feada47f9b88f1ed123.jpg)

![8c3d5b9a83b2d2932793ed20185c518d4805d4c10cfb329f342bb09fb9e3a167.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/images/8c3d5b9a83b2d2932793ed20185c518d4805d4c10cfb329f342bb09fb9e3a167.jpg)

![df78c18ab9cdae0375e45df7babdcef7ae805d8a29b886aa41ba4d1b4d3d8a57.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/images/df78c18ab9cdae0375e45df7babdcef7ae805d8a29b886aa41ba4d1b4d3d8a57.jpg)

### Tables

![2f6b41f6aa137f6826b0a3a8a1e247d9a0fba86de33b588c7200dc437dd98343.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/tables/2f6b41f6aa137f6826b0a3a8a1e247d9a0fba86de33b588c7200dc437dd98343.jpg)

![2fcd5efe721519e047cf3541f0db9036f885dcdb376a2d26e0611db662c2169d.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/tables/2fcd5efe721519e047cf3541f0db9036f885dcdb376a2d26e0611db662c2169d.jpg)

![38eb48beefdbf6b8977cade8eadb7a093c1fbfa7a0eef4da68c54bdba2cc2889.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/tables/38eb48beefdbf6b8977cade8eadb7a093c1fbfa7a0eef4da68c54bdba2cc2889.jpg)

![583d30d805a64798c52f58e11af668d752a4756b37f414986d845aba53f39674.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/tables/583d30d805a64798c52f58e11af668d752a4756b37f414986d845aba53f39674.jpg)

![926b6941f218c0a8d98aa4aee527fada95d0a6753086547df936e8d6c87b137b.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/tables/926b6941f218c0a8d98aa4aee527fada95d0a6753086547df936e8d6c87b137b.jpg)

![9ece237b592c6d3f3d13c353a9e35c5f927c3a214921f3569050da76558a1689.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/tables/9ece237b592c6d3f3d13c353a9e35c5f927c3a214921f3569050da76558a1689.jpg)

![a2642e62311abdff3b3c7bb681e9fa4643bb9445bae5ddc293e49cadca8550df.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/tables/a2642e62311abdff3b3c7bb681e9fa4643bb9445bae5ddc293e49cadca8550df.jpg)

![bb8c7d88ad648594e5b62011f25f761f196af8a174ae0a76f7b00013ab57950b.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/tables/bb8c7d88ad648594e5b62011f25f761f196af8a174ae0a76f7b00013ab57950b.jpg)

![df6157c56ee5a327035f9d51bc789668fff068b0c916c724152b0ca1544a8348.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/tables/df6157c56ee5a327035f9d51bc789668fff068b0c916c724152b0ca1544a8348.jpg)

![e5365590fb93c02212a00e680cab8a6fe14b2e9e3ba787668f0e4bca49051687.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/tables/e5365590fb93c02212a00e680cab8a6fe14b2e9e3ba787668f0e4bca49051687.jpg)

![e7551efd3668029f5dda9e85e955c99caf39717a3b3757fb8e3baf8ab3962432.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/tables/e7551efd3668029f5dda9e85e955c99caf39717a3b3757fb8e3baf8ab3962432.jpg)

![ec769271e81fa8a9761e0f3381faa7ba72850bba6d37d4fdf3d200a4f9c1a379.jpg](../emnlp_results/412_NILE_%20Internal%20Consistency%20Alignment%20in%20Large%20Language%20Models/tables/ec769271e81fa8a9761e0f3381faa7ba72850bba6d37d4fdf3d200a4f9c1a379.jpg)

## Mining the Past with Dual Criteria: Integrating Three types of Historical Information for Context-aware Event Forecasting


### Images

![4d6c531b3c3074fff4e2a5ed77db3e81612fe680b66e1ca303fc70c5ea5a231f.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/images/4d6c531b3c3074fff4e2a5ed77db3e81612fe680b66e1ca303fc70c5ea5a231f.jpg)

![5fa9f9f4563bd6959e3c9c9f830d62f8975571cc619b097caaeccaa410578178.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/images/5fa9f9f4563bd6959e3c9c9f830d62f8975571cc619b097caaeccaa410578178.jpg)

![a4821d7117d06294e9954866916f51d3713cb5287e7e49c0bd455b907ffd2741.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/images/a4821d7117d06294e9954866916f51d3713cb5287e7e49c0bd455b907ffd2741.jpg)

![e47cde1c26066a189a7b2a51080b72193bb13e029b7951dfd66ecd4340992f3b.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/images/e47cde1c26066a189a7b2a51080b72193bb13e029b7951dfd66ecd4340992f3b.jpg)

![f478e782ae702abba23d1d70f3e410a8be1adb33278b990d9c04ef124bcef5a8.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/images/f478e782ae702abba23d1d70f3e410a8be1adb33278b990d9c04ef124bcef5a8.jpg)

### Tables

![228142bd6e63b7e980b1187fdf83594e5457dcead1c460f93c49095f980b0542.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/tables/228142bd6e63b7e980b1187fdf83594e5457dcead1c460f93c49095f980b0542.jpg)

![2e652a5a44e2f1abf651fe007ac8aa2a9f1fd5e1f7e93523c68c89b58c111f16.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/tables/2e652a5a44e2f1abf651fe007ac8aa2a9f1fd5e1f7e93523c68c89b58c111f16.jpg)

![3cc88b1eed5abd36002a6f1feae444abfa5e5ed07975823d8d87de23447a8d4b.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/tables/3cc88b1eed5abd36002a6f1feae444abfa5e5ed07975823d8d87de23447a8d4b.jpg)

![4210afc7ca28f97f4612a86463f10b599a5e645e9a566acc520d4560e4d6e58c.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/tables/4210afc7ca28f97f4612a86463f10b599a5e645e9a566acc520d4560e4d6e58c.jpg)

![6a83d23a43500f678efc268c35b9c808368f93598edb1a25bf1ffdeb4f77ef12.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/tables/6a83d23a43500f678efc268c35b9c808368f93598edb1a25bf1ffdeb4f77ef12.jpg)

![6bd0ce0d5d7801081c8322e21c694942e116e48c87fe7b2882fc698519deedd5.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/tables/6bd0ce0d5d7801081c8322e21c694942e116e48c87fe7b2882fc698519deedd5.jpg)

![78e8a94a4974b7ad1378a7a00cc8a9ab09fae7c0f3c5e449d8df34c3d9c3b442.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/tables/78e8a94a4974b7ad1378a7a00cc8a9ab09fae7c0f3c5e449d8df34c3d9c3b442.jpg)

![8b987cad386806cd33396831643cfc6d4b9a5de2a5684a785b7c215d314932a8.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/tables/8b987cad386806cd33396831643cfc6d4b9a5de2a5684a785b7c215d314932a8.jpg)

![b484f57f366d4582d9a7c6dc2c320f9c7728d3f5c6d1b08ae7cf3475f6bfe4c4.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/tables/b484f57f366d4582d9a7c6dc2c320f9c7728d3f5c6d1b08ae7cf3475f6bfe4c4.jpg)

![b89f89c54fe7116bee0ee52a89d69828abfbb18bcb2e38e87599050a46652ebf.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/tables/b89f89c54fe7116bee0ee52a89d69828abfbb18bcb2e38e87599050a46652ebf.jpg)

![fca1338998a7f5cde737019305228895fe6f739bf3a0e89324021d9432a776cd.jpg](../emnlp_results/413_Mining%20the%20Past%20with%20Dual%20Criteria_%20Integrating%20Three%20types%20of%20Historical%20Information%20for%20Context-aw/tables/fca1338998a7f5cde737019305228895fe6f739bf3a0e89324021d9432a776cd.jpg)

## RAGferee: Building Contextual Reward Models for Retrieval-Augmented Generation


### Images

![20f20a3584a2335034c9a1afda85bbc169da06c61774b4ca8c97c1867b7dfc37.jpg](../emnlp_results/414_RAGferee_%20Building%20Contextual%20Reward%20Models%20for%20Retrieval-Augmented%20Generation/images/20f20a3584a2335034c9a1afda85bbc169da06c61774b4ca8c97c1867b7dfc37.jpg)

![3d9c3dc73f932de43623bd05227822c05aad0e31b72ac1aec84f921328420e5f.jpg](../emnlp_results/414_RAGferee_%20Building%20Contextual%20Reward%20Models%20for%20Retrieval-Augmented%20Generation/images/3d9c3dc73f932de43623bd05227822c05aad0e31b72ac1aec84f921328420e5f.jpg)

![525e796667ee4135d1fcda95bc19682aa2a33064b33addb51d0d47db6dd38519.jpg](../emnlp_results/414_RAGferee_%20Building%20Contextual%20Reward%20Models%20for%20Retrieval-Augmented%20Generation/images/525e796667ee4135d1fcda95bc19682aa2a33064b33addb51d0d47db6dd38519.jpg)

![5b373909b96166b03454c1247c657adc179f717b967a50f5b1adf90c9edc7e10.jpg](../emnlp_results/414_RAGferee_%20Building%20Contextual%20Reward%20Models%20for%20Retrieval-Augmented%20Generation/images/5b373909b96166b03454c1247c657adc179f717b967a50f5b1adf90c9edc7e10.jpg)

![adf4c812f4cb4fade9687269cd4532312f9387a5bf6d74abcd7151c63ce05acc.jpg](../emnlp_results/414_RAGferee_%20Building%20Contextual%20Reward%20Models%20for%20Retrieval-Augmented%20Generation/images/adf4c812f4cb4fade9687269cd4532312f9387a5bf6d74abcd7151c63ce05acc.jpg)

### Tables

![105ce15d2d590def00f2464491f5b99f30e1783ddf2b3cedcf65c00ef121ced3.jpg](../emnlp_results/414_RAGferee_%20Building%20Contextual%20Reward%20Models%20for%20Retrieval-Augmented%20Generation/tables/105ce15d2d590def00f2464491f5b99f30e1783ddf2b3cedcf65c00ef121ced3.jpg)

![4397b09dc81d3619e929662d4246778812ccd09d3c150b5b64824e6204da96e0.jpg](../emnlp_results/414_RAGferee_%20Building%20Contextual%20Reward%20Models%20for%20Retrieval-Augmented%20Generation/tables/4397b09dc81d3619e929662d4246778812ccd09d3c150b5b64824e6204da96e0.jpg)

![4929a3d4ac54b3cbcd948c81a793fe5f721626c42ffb5102fcbbe4de9780c0f6.jpg](../emnlp_results/414_RAGferee_%20Building%20Contextual%20Reward%20Models%20for%20Retrieval-Augmented%20Generation/tables/4929a3d4ac54b3cbcd948c81a793fe5f721626c42ffb5102fcbbe4de9780c0f6.jpg)

![8469fbadbac9d5bd815226e2e6f67bc0579e88476d4d2b08b7e8ecac66371f62.jpg](../emnlp_results/414_RAGferee_%20Building%20Contextual%20Reward%20Models%20for%20Retrieval-Augmented%20Generation/tables/8469fbadbac9d5bd815226e2e6f67bc0579e88476d4d2b08b7e8ecac66371f62.jpg)

![b6681487709028a67c541723d3f454fe78dde3c2412714eb2af42826a16ab1e1.jpg](../emnlp_results/414_RAGferee_%20Building%20Contextual%20Reward%20Models%20for%20Retrieval-Augmented%20Generation/tables/b6681487709028a67c541723d3f454fe78dde3c2412714eb2af42826a16ab1e1.jpg)

![e26d1979c0f8ac67cd5a64aa693b747fb2c1d0821f0872cc817b904f16833aa3.jpg](../emnlp_results/414_RAGferee_%20Building%20Contextual%20Reward%20Models%20for%20Retrieval-Augmented%20Generation/tables/e26d1979c0f8ac67cd5a64aa693b747fb2c1d0821f0872cc817b904f16833aa3.jpg)

![e9bfa2d5a774f95e346faef44e76e6a926a374843ff42dcf294ad0eed207730f.jpg](../emnlp_results/414_RAGferee_%20Building%20Contextual%20Reward%20Models%20for%20Retrieval-Augmented%20Generation/tables/e9bfa2d5a774f95e346faef44e76e6a926a374843ff42dcf294ad0eed207730f.jpg)

![f5f1659b7a4be14ec84046760d2b3f90fd94077ba90e5a17b601342da615365f.jpg](../emnlp_results/414_RAGferee_%20Building%20Contextual%20Reward%20Models%20for%20Retrieval-Augmented%20Generation/tables/f5f1659b7a4be14ec84046760d2b3f90fd94077ba90e5a17b601342da615365f.jpg)

## Large Language Models Discriminate Against Speakers ofGerman Dialects


### Images

![03e604e2419ac0f53fdad69a1c75c9bbafcac31e41f0564a665a537e1302eb4a.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/03e604e2419ac0f53fdad69a1c75c9bbafcac31e41f0564a665a537e1302eb4a.jpg)

![17562bbe6a41c9868b9e25e0d884e92f98a285825952fcba8d4809dacd594459.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/17562bbe6a41c9868b9e25e0d884e92f98a285825952fcba8d4809dacd594459.jpg)

![310f484317be81b199877e6b51a72a912f968691911bdf92470b7ffe8b5778bd.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/310f484317be81b199877e6b51a72a912f968691911bdf92470b7ffe8b5778bd.jpg)

![4165d3339167537b68c7331b23baf88152ea7608c3a7604dd39329cbb6e0fac3.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/4165d3339167537b68c7331b23baf88152ea7608c3a7604dd39329cbb6e0fac3.jpg)

![4728dd984ef99d48552c3441aba6a8857f6b25e42583c947004fcd3f7962487b.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/4728dd984ef99d48552c3441aba6a8857f6b25e42583c947004fcd3f7962487b.jpg)

![4aa0af0035a55afe35a9e0b6332b320dd0b8bec2cedfd2dc84d85c9920f74b9f.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/4aa0af0035a55afe35a9e0b6332b320dd0b8bec2cedfd2dc84d85c9920f74b9f.jpg)

![66b25cc2e683159628fcfbc26ff432b91e09df633833272b52829a519aa2e805.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/66b25cc2e683159628fcfbc26ff432b91e09df633833272b52829a519aa2e805.jpg)

![750c0b052a42e5ce8c7e4d95ac70a87a03604493cd579129a98cab7c96477a87.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/750c0b052a42e5ce8c7e4d95ac70a87a03604493cd579129a98cab7c96477a87.jpg)

![85f9a036b92f449ee3aad8125c7b2bfc1b843e73a1e1d8502590644189213d7a.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/85f9a036b92f449ee3aad8125c7b2bfc1b843e73a1e1d8502590644189213d7a.jpg)

![8ce90044bbc6e445fbff1d2438b454836028af75283d4964c020390bd605c276.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/8ce90044bbc6e445fbff1d2438b454836028af75283d4964c020390bd605c276.jpg)

![b3e18f75ea37b8cd9f0807a60e7d2b8b6f0e8e8c1ffe19928381672be4f09f8a.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/b3e18f75ea37b8cd9f0807a60e7d2b8b6f0e8e8c1ffe19928381672be4f09f8a.jpg)

![b50d8de4392433d7fe836c0043ebcf2a05a1bc2e656a4d3c52b78020dda5b889.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/b50d8de4392433d7fe836c0043ebcf2a05a1bc2e656a4d3c52b78020dda5b889.jpg)

![c7d7c13e0b4d3f475e6aee2ddae7f6af559f30eb260eb7bedbe190ec82c63b74.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/c7d7c13e0b4d3f475e6aee2ddae7f6af559f30eb260eb7bedbe190ec82c63b74.jpg)

![e122d896ffbb9d4914cb703ef2a794736c37d5d8f73b7b301ade310198d730cf.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/e122d896ffbb9d4914cb703ef2a794736c37d5d8f73b7b301ade310198d730cf.jpg)

![ea21b90b21b517fbec3ab7f379f34ca8c22ab24d98fbbadf886155fc639ad987.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/ea21b90b21b517fbec3ab7f379f34ca8c22ab24d98fbbadf886155fc639ad987.jpg)

![f49055b5f292432454aa6f816e42ed439409263b7ff4164e6104bfc5f27de986.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/images/f49055b5f292432454aa6f816e42ed439409263b7ff4164e6104bfc5f27de986.jpg)

### Tables

![052e1f912e9d882b5a1ef7c8b87ff3e06e331812f2c5de1b5a83bb7203446384.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/tables/052e1f912e9d882b5a1ef7c8b87ff3e06e331812f2c5de1b5a83bb7203446384.jpg)

![0d7a7c46cd5ea815849813a42d413bf7b6cdb26c3e30557c7f0bf76799e76557.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/tables/0d7a7c46cd5ea815849813a42d413bf7b6cdb26c3e30557c7f0bf76799e76557.jpg)

![25083e2571a970688b57c49369577e212ccfa86af045fac4c7af7e006618b5da.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/tables/25083e2571a970688b57c49369577e212ccfa86af045fac4c7af7e006618b5da.jpg)

![34b9b3176bab50d4355c282216fd54b3f80b4bef4acf24f7e7dd09c028452158.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/tables/34b9b3176bab50d4355c282216fd54b3f80b4bef4acf24f7e7dd09c028452158.jpg)

![392dca61a44b577307af3c493f6fd8032dd6195579a9a45192e6e70764918bbb.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/tables/392dca61a44b577307af3c493f6fd8032dd6195579a9a45192e6e70764918bbb.jpg)

![79726cba521cc33d1b6f1c965b9f340813cd1bee8ae11649eb406dc725736841.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/tables/79726cba521cc33d1b6f1c965b9f340813cd1bee8ae11649eb406dc725736841.jpg)

![8dc6f239b872dae97cf45dab95bbafb55c05e95ea19aa5f90eed55b2e2e6ff94.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/tables/8dc6f239b872dae97cf45dab95bbafb55c05e95ea19aa5f90eed55b2e2e6ff94.jpg)

![9e0217865a8f185469cb9f7d97149a59dfeb7908f0de83f24e22c45c8d5de4d2.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/tables/9e0217865a8f185469cb9f7d97149a59dfeb7908f0de83f24e22c45c8d5de4d2.jpg)

![a761856eba2426d2fe719b64e166fad060a6a778b20facbabfdf359d311816a4.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/tables/a761856eba2426d2fe719b64e166fad060a6a778b20facbabfdf359d311816a4.jpg)

![a92ab801dfcec913bff75b5aa5c91258d053689d26dd81a90a8e07c03994a8ca.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/tables/a92ab801dfcec913bff75b5aa5c91258d053689d26dd81a90a8e07c03994a8ca.jpg)

![b06e802582543471b3b03843c06e691d31031a2ce018a029eb1f56e1258b3037.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/tables/b06e802582543471b3b03843c06e691d31031a2ce018a029eb1f56e1258b3037.jpg)

![c971eada44fe3a4f732c1854b02735b5cb22e0c22fa8e8d8c2fa3774d6a86195.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/tables/c971eada44fe3a4f732c1854b02735b5cb22e0c22fa8e8d8c2fa3774d6a86195.jpg)

![f2a2f6bea24a4bef9fbb174b95af1f1ae2998d3661227c5a1228cf7dbbfde0f8.jpg](../emnlp_results/415_Large%20Language%20Models%20Discriminate%20Against%20Speakers%20ofGerman%20Dialects/tables/f2a2f6bea24a4bef9fbb174b95af1f1ae2998d3661227c5a1228cf7dbbfde0f8.jpg)

## Uncovering Argumentative Flow: A Question-Focus Discourse Structuring Framework


### Images

![b92d80dc55c960e68764d8a0a9375b9bc02e91b0641ca723f8c9fe51c3f80f75.jpg](../emnlp_results/416_Uncovering%20Argumentative%20Flow_%20A%20Question-Focus%20Discourse%20Structuring%20Framework/images/b92d80dc55c960e68764d8a0a9375b9bc02e91b0641ca723f8c9fe51c3f80f75.jpg)

![c4564071e1ab56085af536a5bf8006263e44f6d19bd9d80005470b63459ba4b1.jpg](../emnlp_results/416_Uncovering%20Argumentative%20Flow_%20A%20Question-Focus%20Discourse%20Structuring%20Framework/images/c4564071e1ab56085af536a5bf8006263e44f6d19bd9d80005470b63459ba4b1.jpg)

### Tables

![1ef853fe69c31aff481c6de30730052f607e489ae65addfa2efcc0d5c4f0ef18.jpg](../emnlp_results/416_Uncovering%20Argumentative%20Flow_%20A%20Question-Focus%20Discourse%20Structuring%20Framework/tables/1ef853fe69c31aff481c6de30730052f607e489ae65addfa2efcc0d5c4f0ef18.jpg)

![417466637ceb443f186e33c565b852d6fa34c256aa0cc7c810594f048de8ef8d.jpg](../emnlp_results/416_Uncovering%20Argumentative%20Flow_%20A%20Question-Focus%20Discourse%20Structuring%20Framework/tables/417466637ceb443f186e33c565b852d6fa34c256aa0cc7c810594f048de8ef8d.jpg)

![8c44ccc1983cd8db53643c3c6e3c2fb65576b504aa824b2b76d7bbf59f29fab5.jpg](../emnlp_results/416_Uncovering%20Argumentative%20Flow_%20A%20Question-Focus%20Discourse%20Structuring%20Framework/tables/8c44ccc1983cd8db53643c3c6e3c2fb65576b504aa824b2b76d7bbf59f29fab5.jpg)

![ad963296d31a7491a9eff11dec65ff3646c105d6f9be1b72927775165eb53533.jpg](../emnlp_results/416_Uncovering%20Argumentative%20Flow_%20A%20Question-Focus%20Discourse%20Structuring%20Framework/tables/ad963296d31a7491a9eff11dec65ff3646c105d6f9be1b72927775165eb53533.jpg)

![ddf4d1541c5ffd0282d9fe6daa790cfbf02e4d44685c58b1d336fd3c5dee621f.jpg](../emnlp_results/416_Uncovering%20Argumentative%20Flow_%20A%20Question-Focus%20Discourse%20Structuring%20Framework/tables/ddf4d1541c5ffd0282d9fe6daa790cfbf02e4d44685c58b1d336fd3c5dee621f.jpg)

![e378e781e8478f4ccbb93938f9b5755b3b0417ac639b85dcc119eb791bf8053f.jpg](../emnlp_results/416_Uncovering%20Argumentative%20Flow_%20A%20Question-Focus%20Discourse%20Structuring%20Framework/tables/e378e781e8478f4ccbb93938f9b5755b3b0417ac639b85dcc119eb791bf8053f.jpg)

![ebfebfc12063bc241528af641c47cc1084344a00ac6ad06a0e195e8542b298d7.jpg](../emnlp_results/416_Uncovering%20Argumentative%20Flow_%20A%20Question-Focus%20Discourse%20Structuring%20Framework/tables/ebfebfc12063bc241528af641c47cc1084344a00ac6ad06a0e195e8542b298d7.jpg)

## AbsVis – Benchmarking How Humans and Vision-Language Models “See” Abstract Concepts in Images


### Images

![028625276f2ffdc969a718f26e053f284ac5b73d78f3753e189f486780bc43bb.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/images/028625276f2ffdc969a718f26e053f284ac5b73d78f3753e189f486780bc43bb.jpg)

![048e6229ea2b36c6d11e4c9596459fc190990d89466671f078c0a911a731fef2.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/images/048e6229ea2b36c6d11e4c9596459fc190990d89466671f078c0a911a731fef2.jpg)

![14289b0e6eabc227622506e730ed25a7c890659b8f80f371d1967958d4c61d30.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/images/14289b0e6eabc227622506e730ed25a7c890659b8f80f371d1967958d4c61d30.jpg)

![180e84388d1856c59ee9b6346d63b2076f41a6b30b069e0703ef7e7be8d493c6.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/images/180e84388d1856c59ee9b6346d63b2076f41a6b30b069e0703ef7e7be8d493c6.jpg)

![46872cbb7e0248352ea87737caaffe0a33df66909aa0e95a7d04a30be09b14aa.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/images/46872cbb7e0248352ea87737caaffe0a33df66909aa0e95a7d04a30be09b14aa.jpg)

![6e7ebabd39795c95d6e1ace1c9684a8fffb700a6a13c3029ed38e79583fc9aed.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/images/6e7ebabd39795c95d6e1ace1c9684a8fffb700a6a13c3029ed38e79583fc9aed.jpg)

![72d70ef71ecebec33d69f64123f8fe29cef9f51552d453cb3d0cd8a7302d442d.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/images/72d70ef71ecebec33d69f64123f8fe29cef9f51552d453cb3d0cd8a7302d442d.jpg)

![947b2f6e232c9c66d5e0306e74899e16f6364d74b53812e194efb570484d3882.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/images/947b2f6e232c9c66d5e0306e74899e16f6364d74b53812e194efb570484d3882.jpg)

![968539d1a7d32719badc837283b285e9cb5fe25cfee1508c6a88d8282eb41474.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/images/968539d1a7d32719badc837283b285e9cb5fe25cfee1508c6a88d8282eb41474.jpg)

![bcfb8b7a62ea8f9f2aeb96bb37d4e007497985b6108376b86513d12aeda0dd76.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/images/bcfb8b7a62ea8f9f2aeb96bb37d4e007497985b6108376b86513d12aeda0dd76.jpg)

![c749203c4da409bc14d07304f6e3be45244cdafb287a1a5b2d92451e193f26b0.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/images/c749203c4da409bc14d07304f6e3be45244cdafb287a1a5b2d92451e193f26b0.jpg)

![dad309b16873572a96e948c0f7b24216577e4fa142afb2a5e760b83e72e9652f.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/images/dad309b16873572a96e948c0f7b24216577e4fa142afb2a5e760b83e72e9652f.jpg)

![db4ad6f459a6349353c526dc2dc8ffbdb47a785879564f03a1903cf6793ae5a9.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/images/db4ad6f459a6349353c526dc2dc8ffbdb47a785879564f03a1903cf6793ae5a9.jpg)

### Tables

![098275b5ab49093a2601b8297286716eca5250615ffb1335fd145019f3fdc7ce.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/tables/098275b5ab49093a2601b8297286716eca5250615ffb1335fd145019f3fdc7ce.jpg)

![1602d240494c46a22547565aea6fd9077bd4fb3acb3b14982b41d534c26cf83e.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/tables/1602d240494c46a22547565aea6fd9077bd4fb3acb3b14982b41d534c26cf83e.jpg)

![300eb205985493c0af6c00bc157d5123831fdd84635d3ba1f1c7b2309c344320.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/tables/300eb205985493c0af6c00bc157d5123831fdd84635d3ba1f1c7b2309c344320.jpg)

![34824bb2af3c8bbf36b0e24a5d2ae0068ceb03b239068c312e000835451878cd.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/tables/34824bb2af3c8bbf36b0e24a5d2ae0068ceb03b239068c312e000835451878cd.jpg)

![70e3c8f485c66b5c0892c41a8c9de2bf3bb48bc8b3d96283cf0ebae4e8c55810.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/tables/70e3c8f485c66b5c0892c41a8c9de2bf3bb48bc8b3d96283cf0ebae4e8c55810.jpg)

![9128963add2ca3c29270a78775fb5f13d1461b653f2e2b1d8fc5dd50d244e43a.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/tables/9128963add2ca3c29270a78775fb5f13d1461b653f2e2b1d8fc5dd50d244e43a.jpg)

![aedfd8c2949c2f449980f0d88eb7923c435e99b2241b54581350b3c0ee3d6668.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/tables/aedfd8c2949c2f449980f0d88eb7923c435e99b2241b54581350b3c0ee3d6668.jpg)

![b324311b84b68758da0339810dcec80c489085b0d36cfa888864dfba0bf3396f.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/tables/b324311b84b68758da0339810dcec80c489085b0d36cfa888864dfba0bf3396f.jpg)

![bf6c85aa7c40a71e5bd080d57fe210e33bde5d31ab8665045f11d225fadd1e24.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/tables/bf6c85aa7c40a71e5bd080d57fe210e33bde5d31ab8665045f11d225fadd1e24.jpg)

![cb4877ab56bee2ff2daed883d21657f1714cac9af421496ac9a4e89a0ceabb43.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/tables/cb4877ab56bee2ff2daed883d21657f1714cac9af421496ac9a4e89a0ceabb43.jpg)

![d575eca19edc391c5e4aa51fb4d92e6d760be41ed57eaed7705dc13132ddade7.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/tables/d575eca19edc391c5e4aa51fb4d92e6d760be41ed57eaed7705dc13132ddade7.jpg)

![fdaa12b549ffbb3921c1b0714cd99624faa9776a353515a5ce5de8e79700b8a4.jpg](../emnlp_results/417_AbsVis%20%E2%80%93%20Benchmarking%20How%20Humans%20and%20Vision-Language%20Models%20%E2%80%9CSee%E2%80%9D%20Abstract%20Concepts%20in%20Images/tables/fdaa12b549ffbb3921c1b0714cd99624faa9776a353515a5ce5de8e79700b8a4.jpg)

## A Rigorous Evaluation ofLLMData Generation Strategies for Low-Resource Languages


### Images

![05c69dd71ba3467dc0e4716e6aceebde98adda13e0cf8bd8b9f4c1fbf18f2440.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/images/05c69dd71ba3467dc0e4716e6aceebde98adda13e0cf8bd8b9f4c1fbf18f2440.jpg)

![0f3d1c80668018059c53fe36ef6d6c4c45568bd46d4f2d5b094cbc02908c2e66.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/images/0f3d1c80668018059c53fe36ef6d6c4c45568bd46d4f2d5b094cbc02908c2e66.jpg)

![255cbb79c3d6299a887e3fb69e04e372fde29f7fccaa2c5da0462cfff3c9018c.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/images/255cbb79c3d6299a887e3fb69e04e372fde29f7fccaa2c5da0462cfff3c9018c.jpg)

![3f3d577e3d504b3f9b7ee665347f71a52139888bf753d23d626076723e1e49c1.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/images/3f3d577e3d504b3f9b7ee665347f71a52139888bf753d23d626076723e1e49c1.jpg)

![4191f06e6315a71210f04f6ac8ccd30ee3a636f072fe6bd99145093b08fa498b.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/images/4191f06e6315a71210f04f6ac8ccd30ee3a636f072fe6bd99145093b08fa498b.jpg)

![5638695ac27d62472e1bb9a1eb14862ebad376fd90e9ba3b1c5b839272c7ba2f.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/images/5638695ac27d62472e1bb9a1eb14862ebad376fd90e9ba3b1c5b839272c7ba2f.jpg)

![64a0353cc09b649725cd22d40c9ab0a3cf603763e14b80625d0ec583f57e421f.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/images/64a0353cc09b649725cd22d40c9ab0a3cf603763e14b80625d0ec583f57e421f.jpg)

![b92f86f24a8735a772e78b01aef8fb016cb85b5f9f721da354121979142118a2.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/images/b92f86f24a8735a772e78b01aef8fb016cb85b5f9f721da354121979142118a2.jpg)

![be4d487b982e72e7ba53d13317b8091aac1aebe99b47309f6e41c4491191a718.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/images/be4d487b982e72e7ba53d13317b8091aac1aebe99b47309f6e41c4491191a718.jpg)

![ddb0c9321cef6f108f45a898fd0b390a25754aa917c90ee671527d7f7f993c97.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/images/ddb0c9321cef6f108f45a898fd0b390a25754aa917c90ee671527d7f7f993c97.jpg)

### Tables

![1062abdef4b4281ce9a3a829b8817ba6d5c5e8e5317998f611404564c9a058df.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/tables/1062abdef4b4281ce9a3a829b8817ba6d5c5e8e5317998f611404564c9a058df.jpg)

![3b39d666465351083df32560545a61abd50a688902905790090ad8267326c955.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/tables/3b39d666465351083df32560545a61abd50a688902905790090ad8267326c955.jpg)

![4784fa6b905b68e1cd4cc6ae7ef355169413ddaa5368d8dd51e22f072b215558.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/tables/4784fa6b905b68e1cd4cc6ae7ef355169413ddaa5368d8dd51e22f072b215558.jpg)

![60d85de0190c296abd903bd3fd7c61a27dc8dfe797d9e4860868f690ca508718.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/tables/60d85de0190c296abd903bd3fd7c61a27dc8dfe797d9e4860868f690ca508718.jpg)

![74147f4f3547c760fba464dd2716648dbad1910167b06f1f774177d0b8729691.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/tables/74147f4f3547c760fba464dd2716648dbad1910167b06f1f774177d0b8729691.jpg)

![a289d5b27aa2779d70ed4db747fd4b1d138ddc31de8fd9ca85e5336948a7a780.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/tables/a289d5b27aa2779d70ed4db747fd4b1d138ddc31de8fd9ca85e5336948a7a780.jpg)

![aa361bb2236aa518f1c3a3dca6865c5d0514a366aa659a4682fdd4fc28f5d9a6.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/tables/aa361bb2236aa518f1c3a3dca6865c5d0514a366aa659a4682fdd4fc28f5d9a6.jpg)

![b6bf921503f787f0b498bda37a38876918e6a50ad1327267c34c5e4c2b90686e.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/tables/b6bf921503f787f0b498bda37a38876918e6a50ad1327267c34c5e4c2b90686e.jpg)

![d202515c7edcf18a82c7bf86a1fef78cb8e6459d8a573f98e2d33ee7fbe5d772.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/tables/d202515c7edcf18a82c7bf86a1fef78cb8e6459d8a573f98e2d33ee7fbe5d772.jpg)

![da231a5b1d0a5281b87c835667a554272d63711473638ca678b790bca1a6a3a4.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/tables/da231a5b1d0a5281b87c835667a554272d63711473638ca678b790bca1a6a3a4.jpg)

![dd5887b90ed97f539bc9c57b088314ad3379a014c69de206e1d0b63e1122009b.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/tables/dd5887b90ed97f539bc9c57b088314ad3379a014c69de206e1d0b63e1122009b.jpg)

![ea012521d76c38103cc343426f1eea0155c51b787790f036bd2390134b65468b.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/tables/ea012521d76c38103cc343426f1eea0155c51b787790f036bd2390134b65468b.jpg)

![f80f3cba4e92ba19f9fa707a7e1ff8539a17fd6f3043756ae066bb3c2752c5eb.jpg](../emnlp_results/418_A%20Rigorous%20Evaluation%20ofLLMData%20Generation%20Strategies%20for%20Low-Resource%20Languages/tables/f80f3cba4e92ba19f9fa707a7e1ff8539a17fd6f3043756ae066bb3c2752c5eb.jpg)

## Alignment with Fill-In-the-Middle for Enhancing Code Generation


### Images

![18adadbe1e4e18aa87add678726e148c4518e0b837aced86c969f2d6d0fd77f0.jpg](../emnlp_results/419_Alignment%20with%20Fill-In-the-Middle%20for%20Enhancing%20Code%20Generation/images/18adadbe1e4e18aa87add678726e148c4518e0b837aced86c969f2d6d0fd77f0.jpg)

![4744d90b187902a33bc38f975c31d523147ab36635889b5ea3ea3904efc7583f.jpg](../emnlp_results/419_Alignment%20with%20Fill-In-the-Middle%20for%20Enhancing%20Code%20Generation/images/4744d90b187902a33bc38f975c31d523147ab36635889b5ea3ea3904efc7583f.jpg)

![606677fb39c8be98fac034e16ec683e6b84b8916ea649f43cdf1e5cf4cbbf583.jpg](../emnlp_results/419_Alignment%20with%20Fill-In-the-Middle%20for%20Enhancing%20Code%20Generation/images/606677fb39c8be98fac034e16ec683e6b84b8916ea649f43cdf1e5cf4cbbf583.jpg)

![8d4b10c17e485d74b06d685483c8538053301ca37162e0d31152d2e51b3eefe7.jpg](../emnlp_results/419_Alignment%20with%20Fill-In-the-Middle%20for%20Enhancing%20Code%20Generation/images/8d4b10c17e485d74b06d685483c8538053301ca37162e0d31152d2e51b3eefe7.jpg)

![ab7a10d0a36931b49a6f7c3fd5455d7e6ee3ce8ab7cbbd5095ca8a13702e09d1.jpg](../emnlp_results/419_Alignment%20with%20Fill-In-the-Middle%20for%20Enhancing%20Code%20Generation/images/ab7a10d0a36931b49a6f7c3fd5455d7e6ee3ce8ab7cbbd5095ca8a13702e09d1.jpg)

![cb3e0ff1180c78d402e442a7fb5c53ecaf15b0f058d397112c3070aaabad9840.jpg](../emnlp_results/419_Alignment%20with%20Fill-In-the-Middle%20for%20Enhancing%20Code%20Generation/images/cb3e0ff1180c78d402e442a7fb5c53ecaf15b0f058d397112c3070aaabad9840.jpg)

![cddfc251e3633a73f20a62d64c52435ef71f896f77bf5ea5f058d06d6917b4c7.jpg](../emnlp_results/419_Alignment%20with%20Fill-In-the-Middle%20for%20Enhancing%20Code%20Generation/images/cddfc251e3633a73f20a62d64c52435ef71f896f77bf5ea5f058d06d6917b4c7.jpg)

![feaa0623ebfb369166e1fa51f48c4dfbd409cda85a55a839d0d1d7a32a2afcd9.jpg](../emnlp_results/419_Alignment%20with%20Fill-In-the-Middle%20for%20Enhancing%20Code%20Generation/images/feaa0623ebfb369166e1fa51f48c4dfbd409cda85a55a839d0d1d7a32a2afcd9.jpg)

### Tables

![22bc1eb9c491d8094caf4c6b87e2f89bcf3e8181c01ff530d100860839553e7f.jpg](../emnlp_results/419_Alignment%20with%20Fill-In-the-Middle%20for%20Enhancing%20Code%20Generation/tables/22bc1eb9c491d8094caf4c6b87e2f89bcf3e8181c01ff530d100860839553e7f.jpg)

![5782cf690cce6eb706492977d6e5cceecd83e865911960fc2f4112ab1d7dc2bf.jpg](../emnlp_results/419_Alignment%20with%20Fill-In-the-Middle%20for%20Enhancing%20Code%20Generation/tables/5782cf690cce6eb706492977d6e5cceecd83e865911960fc2f4112ab1d7dc2bf.jpg)

![d3ada0bd298123cb23d04d6acdbe2e75ad063fb461d1cffdb089a742fcfbc77f.jpg](../emnlp_results/419_Alignment%20with%20Fill-In-the-Middle%20for%20Enhancing%20Code%20Generation/tables/d3ada0bd298123cb23d04d6acdbe2e75ad063fb461d1cffdb089a742fcfbc77f.jpg)

![ff44a5f69f1d2011f2da560c6ebc8798924083ba6550b3e35b8fab8630d9d334.jpg](../emnlp_results/419_Alignment%20with%20Fill-In-the-Middle%20for%20Enhancing%20Code%20Generation/tables/ff44a5f69f1d2011f2da560c6ebc8798924083ba6550b3e35b8fab8630d9d334.jpg)

## A Middle Path for On-PremisesLLMDeployment: Preserving Privacy Without Sacrificing Model Confidentiality


### Images

![005141e01739deebd3d8b7b0dd5bcc28d1f145d319a9802a646ed9ee4fd8e9e0.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/images/005141e01739deebd3d8b7b0dd5bcc28d1f145d319a9802a646ed9ee4fd8e9e0.jpg)

![10c1de7113738831bca82dfe772468bb540bfe54605032d1dbdb17800e7d09b2.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/images/10c1de7113738831bca82dfe772468bb540bfe54605032d1dbdb17800e7d09b2.jpg)

![1358ec5dde34f712fc305c058e8f0b5d6eb800da1728d21ab362ebf30cf7eeb4.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/images/1358ec5dde34f712fc305c058e8f0b5d6eb800da1728d21ab362ebf30cf7eeb4.jpg)

![18eede24d0155469b38d7854b9376510d257b11f1ecbb60e0c7a0c682c431165.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/images/18eede24d0155469b38d7854b9376510d257b11f1ecbb60e0c7a0c682c431165.jpg)

![212993d9132467d67e91f0cffa503c11de9d8036bf9beecab474eebdb9991c24.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/images/212993d9132467d67e91f0cffa503c11de9d8036bf9beecab474eebdb9991c24.jpg)

![84fa0c7557426f6bada91ca7982c5fa38a9d4ac6e6af2593b8bc449d6308d445.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/images/84fa0c7557426f6bada91ca7982c5fa38a9d4ac6e6af2593b8bc449d6308d445.jpg)

![94173f5fdf0b233e2508bd43b1f2d71e34133081bf56dff5fa2e361cc76adc10.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/images/94173f5fdf0b233e2508bd43b1f2d71e34133081bf56dff5fa2e361cc76adc10.jpg)

![a871ab45214be7534e21c4d349daa379be38fcda33970add32e73f7ea171f82f.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/images/a871ab45214be7534e21c4d349daa379be38fcda33970add32e73f7ea171f82f.jpg)

![bf5a409fa1e08b4408ecf6906f00867a19d2bcbf231e25a66b4d918ae7412d84.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/images/bf5a409fa1e08b4408ecf6906f00867a19d2bcbf231e25a66b4d918ae7412d84.jpg)

![e1211dd94e317fc732f84e4c31a58a2fa8f33b26599bb8d5bb1e8278716c8716.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/images/e1211dd94e317fc732f84e4c31a58a2fa8f33b26599bb8d5bb1e8278716c8716.jpg)

![ed659d6c5b304c928dee6d311319e663ec94ee3764a806ae41bc7df5669159ab.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/images/ed659d6c5b304c928dee6d311319e663ec94ee3764a806ae41bc7df5669159ab.jpg)

![ee02470b4c8ac2d689cf1e2f4c5337190f4910a36a2fd3c39f6f251dc85b0396.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/images/ee02470b4c8ac2d689cf1e2f4c5337190f4910a36a2fd3c39f6f251dc85b0396.jpg)

![fa06ccca6cb3bb6c7192f831313e76d08f58bf534dd1d87774e4643118efc9ec.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/images/fa06ccca6cb3bb6c7192f831313e76d08f58bf534dd1d87774e4643118efc9ec.jpg)

### Tables

![0fd627080b81533d64fb759b6cc15fa4fe9870cee73a1c9c435914966a87c32c.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/0fd627080b81533d64fb759b6cc15fa4fe9870cee73a1c9c435914966a87c32c.jpg)

![147b5354ab2d2d08e8a5529907c8e3c398e955a8bcd9ab6463963a6027158b5f.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/147b5354ab2d2d08e8a5529907c8e3c398e955a8bcd9ab6463963a6027158b5f.jpg)

![1bb7ec48cc92a69ef4c145b4d98edfdcf40b069edfc7cec4b2fcaabd878848b4.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/1bb7ec48cc92a69ef4c145b4d98edfdcf40b069edfc7cec4b2fcaabd878848b4.jpg)

![1ca29c134f4f7704f7a643723049e8c9c1b41be5b07ed97859257ea864810556.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/1ca29c134f4f7704f7a643723049e8c9c1b41be5b07ed97859257ea864810556.jpg)

![1d2de85d9d84ddf08fa92aee0e1e899ab40e4303c38a50d97bdf0af682fac3d1.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/1d2de85d9d84ddf08fa92aee0e1e899ab40e4303c38a50d97bdf0af682fac3d1.jpg)

![1dd6f73ab808364fd1dfd0d8f8f05485103f34ff142eace45de1bf12996d2a8d.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/1dd6f73ab808364fd1dfd0d8f8f05485103f34ff142eace45de1bf12996d2a8d.jpg)

![1fa2643d574b440b9348f9bb7f7d117b3d399c422a3d37ee4a8ee61cea05663e.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/1fa2643d574b440b9348f9bb7f7d117b3d399c422a3d37ee4a8ee61cea05663e.jpg)

![24352e1e8d4684609f3c50ee287c42bc1b972499de5287195b018157b446edcc.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/24352e1e8d4684609f3c50ee287c42bc1b972499de5287195b018157b446edcc.jpg)

![3709a8fbd563b8c0433e3973112a1b5c761b6a350fcad725409c503a283e0d74.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/3709a8fbd563b8c0433e3973112a1b5c761b6a350fcad725409c503a283e0d74.jpg)

![375fae302ccb8d93d1a6fdf8c849d6a655d6a24e6b38622a7c0984b437b3e16f.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/375fae302ccb8d93d1a6fdf8c849d6a655d6a24e6b38622a7c0984b437b3e16f.jpg)

![383cb332d0e881b711e7ea7e775748c37577a1b756e010127b3f9b0f5e22ad45.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/383cb332d0e881b711e7ea7e775748c37577a1b756e010127b3f9b0f5e22ad45.jpg)

![3a7042612105f2f4b80ee4656013b45d45bb5205f1a012382acf63e9079af98f.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/3a7042612105f2f4b80ee4656013b45d45bb5205f1a012382acf63e9079af98f.jpg)

![3b8b312f82aea6c8a209aee8e8c26d57e2378c562dc4baf3470d9c16d5a0f96b.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/3b8b312f82aea6c8a209aee8e8c26d57e2378c562dc4baf3470d9c16d5a0f96b.jpg)

![4615e78487e393302e439f614317c30866a1d706c88ea695c73702bc98b45d72.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/4615e78487e393302e439f614317c30866a1d706c88ea695c73702bc98b45d72.jpg)

![4a1c405c80aca8a64961c0bf29507f802aa438235f937ce012bc04f61b84eb73.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/4a1c405c80aca8a64961c0bf29507f802aa438235f937ce012bc04f61b84eb73.jpg)

![5a0d949eec56e16c21bebe1c6e7cebf03ce42a0ba426fee49227929005c9d1ad.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/5a0d949eec56e16c21bebe1c6e7cebf03ce42a0ba426fee49227929005c9d1ad.jpg)

![5c43b0d6ca7644e64b377c7feeecee8e2189354609ac3d835babdfba982979ea.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/5c43b0d6ca7644e64b377c7feeecee8e2189354609ac3d835babdfba982979ea.jpg)

![61d614e34990eb2754bfc89c74939ec4305c058d18245a7b06c278140b2a0c38.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/61d614e34990eb2754bfc89c74939ec4305c058d18245a7b06c278140b2a0c38.jpg)

![6bb48ea25e13ec488cd1ea1c61d21dceacd6075d9ca7de57c61dfad0c9811cc4.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/6bb48ea25e13ec488cd1ea1c61d21dceacd6075d9ca7de57c61dfad0c9811cc4.jpg)

![750c8b4491156e065262063ad270ab870bfacf5fb1a7103b1d993d31dfbbdc3b.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/750c8b4491156e065262063ad270ab870bfacf5fb1a7103b1d993d31dfbbdc3b.jpg)

![7f9674b02911f877b009c6b9bcb80e4d6bcb9171ad96a98724d039ed1f830eae.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/7f9674b02911f877b009c6b9bcb80e4d6bcb9171ad96a98724d039ed1f830eae.jpg)

![89ad68b6bc24021802904ae3592c00d8f61db8fe19463f0bfec42d96cb926600.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/89ad68b6bc24021802904ae3592c00d8f61db8fe19463f0bfec42d96cb926600.jpg)

![914853e82f6fd5289584f77a1baa3d6471826feba63b356dda8c194f62d2ac82.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/914853e82f6fd5289584f77a1baa3d6471826feba63b356dda8c194f62d2ac82.jpg)

![945de86bf69e1034ab0c30718c71c011ac35710495be7933d6822af053487c46.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/945de86bf69e1034ab0c30718c71c011ac35710495be7933d6822af053487c46.jpg)

![989b6e3c0db2a56da39cbea586be0e29f853adea630d89749b6fb3724d2ee812.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/989b6e3c0db2a56da39cbea586be0e29f853adea630d89749b6fb3724d2ee812.jpg)

![9c8de0b423568f861dfee9e899ae62ac8e569d244b6a378d994215073eb36e4a.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/9c8de0b423568f861dfee9e899ae62ac8e569d244b6a378d994215073eb36e4a.jpg)

![a11f295c26e2249465c9a79709118aadbafc18aa53f99968d00d5565cdc98ec2.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/a11f295c26e2249465c9a79709118aadbafc18aa53f99968d00d5565cdc98ec2.jpg)

![a55a44f354adfcf7b473000988113f06ab591602c69a5cdba1aae6ee9046e699.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/a55a44f354adfcf7b473000988113f06ab591602c69a5cdba1aae6ee9046e699.jpg)

![aeb58f1b37c670b1f5823d86290e887b1a2640d80d572eda03efa2433b5237a4.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/aeb58f1b37c670b1f5823d86290e887b1a2640d80d572eda03efa2433b5237a4.jpg)

![b1d4e1480631dff50690f30688290e9c723a9ddb43ceb6fe36369cb8699e9e78.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/b1d4e1480631dff50690f30688290e9c723a9ddb43ceb6fe36369cb8699e9e78.jpg)

![b1d636cd98b4bbd4e1787923c5a36069bd30ad4148729c9394972eabdf6974ee.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/b1d636cd98b4bbd4e1787923c5a36069bd30ad4148729c9394972eabdf6974ee.jpg)

![b294d9dfcff7d8a59912f47d34f88f19a8567dd6d4489a813e41102771da4b59.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/b294d9dfcff7d8a59912f47d34f88f19a8567dd6d4489a813e41102771da4b59.jpg)

![b8f70cd4fba3f7c83d1ea2121dbe126aafdc1d6973ed58587af7b0ead18916a5.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/b8f70cd4fba3f7c83d1ea2121dbe126aafdc1d6973ed58587af7b0ead18916a5.jpg)

![c60c8d7f627efd11e57cddfaadf0163947dab48535fba3632f1a27740f973d79.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/c60c8d7f627efd11e57cddfaadf0163947dab48535fba3632f1a27740f973d79.jpg)

![c6e945938bb0a7ba05dbea763ec462cdabccf2726fa8154b74add21a3e894a63.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/c6e945938bb0a7ba05dbea763ec462cdabccf2726fa8154b74add21a3e894a63.jpg)

![cb37cd6f5f047edabc7b885346187dd4d6461cb03e46026369ab19a609a02e63.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/cb37cd6f5f047edabc7b885346187dd4d6461cb03e46026369ab19a609a02e63.jpg)

![d23809cd27608b579405adc66bb2dd0bf451e93a7214e2d89bb752f72ea5b243.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/d23809cd27608b579405adc66bb2dd0bf451e93a7214e2d89bb752f72ea5b243.jpg)

![d406c790b0f67cc63dfdc72f578e43ee7812f8756947231b23110206729e1fb3.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/d406c790b0f67cc63dfdc72f578e43ee7812f8756947231b23110206729e1fb3.jpg)

![d4a3dcd7be212257d8fe7de3d84a20f5d1e0561f8ed6ee9609647c62e6d70e17.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/d4a3dcd7be212257d8fe7de3d84a20f5d1e0561f8ed6ee9609647c62e6d70e17.jpg)

![dbedc685b35b8c56da046227cf9d7080f83729d2d020dcc61fa9706e48f778b5.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/dbedc685b35b8c56da046227cf9d7080f83729d2d020dcc61fa9706e48f778b5.jpg)

![dc05da9b997601446d82519ebbef619745e823b690dcf7878a619b6abaee1f00.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/dc05da9b997601446d82519ebbef619745e823b690dcf7878a619b6abaee1f00.jpg)

![dcefbb090642ab5963c2041feac5f92e81481e1b924d508945c64b0a9e2c3e2b.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/dcefbb090642ab5963c2041feac5f92e81481e1b924d508945c64b0a9e2c3e2b.jpg)

![ea872362451a7397882aaedc73ce374d8b1317513aeba7109a5d25bf8bb0b45e.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/ea872362451a7397882aaedc73ce374d8b1317513aeba7109a5d25bf8bb0b45e.jpg)

![f344801aa75ef6d5253877d2cfac26c48cec2065f51791aaf8a2cd90fc9790ec.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/f344801aa75ef6d5253877d2cfac26c48cec2065f51791aaf8a2cd90fc9790ec.jpg)

![f42a4f62685ed83dc7f0f16335b6a4baa03d5095b7a3534f437aa7e4d68ea691.jpg](../emnlp_results/420_A%20Middle%20Path%20for%20On-PremisesLLMDeployment_%20Preserving%20Privacy%20Without%20Sacrificing%20Model%20Confidentia/tables/f42a4f62685ed83dc7f0f16335b6a4baa03d5095b7a3534f437aa7e4d68ea691.jpg)

## Variance Sensitivity Induces Attention Entropy Collapse and Instability in Transformers


### Images

![0e24979340bf6b5b5e8ec89b933f6e79ae5bb414299b608ea8b5857295e73ce1.jpg](../emnlp_results/421_Variance%20Sensitivity%20Induces%20Attention%20Entropy%20Collapse%20and%20Instability%20in%20Transformers/images/0e24979340bf6b5b5e8ec89b933f6e79ae5bb414299b608ea8b5857295e73ce1.jpg)

![100fbb8fc05553578d02f30a194f3f019df0fdb6638e89254230e410c03f9755.jpg](../emnlp_results/421_Variance%20Sensitivity%20Induces%20Attention%20Entropy%20Collapse%20and%20Instability%20in%20Transformers/images/100fbb8fc05553578d02f30a194f3f019df0fdb6638e89254230e410c03f9755.jpg)

![209a5b19510137d3db597ba7d9c612caec0868702aedc7b406a5d99cbb12a2c1.jpg](../emnlp_results/421_Variance%20Sensitivity%20Induces%20Attention%20Entropy%20Collapse%20and%20Instability%20in%20Transformers/images/209a5b19510137d3db597ba7d9c612caec0868702aedc7b406a5d99cbb12a2c1.jpg)

![2dc6512fc13642184a12643b5092f8661794bf3d4a01558b8558bcc7575816e6.jpg](../emnlp_results/421_Variance%20Sensitivity%20Induces%20Attention%20Entropy%20Collapse%20and%20Instability%20in%20Transformers/images/2dc6512fc13642184a12643b5092f8661794bf3d4a01558b8558bcc7575816e6.jpg)

![478047cda9b3225a2cc9d0b116c201266dc0dbf0893e57a71944a76831a9d702.jpg](../emnlp_results/421_Variance%20Sensitivity%20Induces%20Attention%20Entropy%20Collapse%20and%20Instability%20in%20Transformers/images/478047cda9b3225a2cc9d0b116c201266dc0dbf0893e57a71944a76831a9d702.jpg)

![4c0022bd92797291a092a2e7192a815752e2a61cb9d6620ef7e4e115e0af72af.jpg](../emnlp_results/421_Variance%20Sensitivity%20Induces%20Attention%20Entropy%20Collapse%20and%20Instability%20in%20Transformers/images/4c0022bd92797291a092a2e7192a815752e2a61cb9d6620ef7e4e115e0af72af.jpg)

![6ff792bc40d7ec5698e72af21c87e77587fc5dcbaf09a6d11396abef93ef7617.jpg](../emnlp_results/421_Variance%20Sensitivity%20Induces%20Attention%20Entropy%20Collapse%20and%20Instability%20in%20Transformers/images/6ff792bc40d7ec5698e72af21c87e77587fc5dcbaf09a6d11396abef93ef7617.jpg)

![81b04ea04a1fd6ea7599006367e6683a1514c087a0708fff7f7044e403b3f879.jpg](../emnlp_results/421_Variance%20Sensitivity%20Induces%20Attention%20Entropy%20Collapse%20and%20Instability%20in%20Transformers/images/81b04ea04a1fd6ea7599006367e6683a1514c087a0708fff7f7044e403b3f879.jpg)

![9694feefa48adc2bd14a8e815a91b5acba5857143e2b432259cb796bb9d4bc99.jpg](../emnlp_results/421_Variance%20Sensitivity%20Induces%20Attention%20Entropy%20Collapse%20and%20Instability%20in%20Transformers/images/9694feefa48adc2bd14a8e815a91b5acba5857143e2b432259cb796bb9d4bc99.jpg)

![cf903b084a8820f2ecec47446513d5cd3b974a5b11ce01af1ea432a8f68f0b85.jpg](../emnlp_results/421_Variance%20Sensitivity%20Induces%20Attention%20Entropy%20Collapse%20and%20Instability%20in%20Transformers/images/cf903b084a8820f2ecec47446513d5cd3b974a5b11ce01af1ea432a8f68f0b85.jpg)

![e335a3dddc8a3c5804c400cf0b5f63c08ef5e489ad4223a4174e48bddc8c3547.jpg](../emnlp_results/421_Variance%20Sensitivity%20Induces%20Attention%20Entropy%20Collapse%20and%20Instability%20in%20Transformers/images/e335a3dddc8a3c5804c400cf0b5f63c08ef5e489ad4223a4174e48bddc8c3547.jpg)

### Tables

![c722941e13b2b33b8ff902279f155504c470a7d57ff20b96a74553460d1ea340.jpg](../emnlp_results/421_Variance%20Sensitivity%20Induces%20Attention%20Entropy%20Collapse%20and%20Instability%20in%20Transformers/tables/c722941e13b2b33b8ff902279f155504c470a7d57ff20b96a74553460d1ea340.jpg)

## X-FLoRA: Cross-modal Federated Learning with Modality-expertLoRAfor MedicalVQA


### Images

![049d8292d999de3757a8117a5e4f1aa67080ceaa65e1aa0c6b59170d72a9553d.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/049d8292d999de3757a8117a5e4f1aa67080ceaa65e1aa0c6b59170d72a9553d.jpg)

![0f892754c8b249b4137b4aa62cca2b3accf375a4c80933ae137d204cf7d243ce.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/0f892754c8b249b4137b4aa62cca2b3accf375a4c80933ae137d204cf7d243ce.jpg)

![16051619c22dab459a99ae1114d78686f4070ba14d699b96e2209bfd4d1c08d2.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/16051619c22dab459a99ae1114d78686f4070ba14d699b96e2209bfd4d1c08d2.jpg)

![1fb0fabf7f67779672fa800090fbca7484eade6872bc8971068d73987d2d4ba1.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/1fb0fabf7f67779672fa800090fbca7484eade6872bc8971068d73987d2d4ba1.jpg)

![225cf51e32fe1b658bbfaa76f7a19c343eb4bdd689d83c07f417da75f0e0f694.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/225cf51e32fe1b658bbfaa76f7a19c343eb4bdd689d83c07f417da75f0e0f694.jpg)

![3aecea7a3cc108e89129cc017728c6d55cef2050acc78592a91b2bdfaf6ae312.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/3aecea7a3cc108e89129cc017728c6d55cef2050acc78592a91b2bdfaf6ae312.jpg)

![405470d10f97cd07d652df6d6d5d75c809db091a6e68bc0551ce8afa506bbe14.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/405470d10f97cd07d652df6d6d5d75c809db091a6e68bc0551ce8afa506bbe14.jpg)

![5a7793a9ddbc8d5a874067490fd827531bd3cda84b41932a37b10b1d8a872765.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/5a7793a9ddbc8d5a874067490fd827531bd3cda84b41932a37b10b1d8a872765.jpg)

![624ef750c7a29e2aeb3288c41e1282aafc6a13733820dda44272c602a06c9fa5.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/624ef750c7a29e2aeb3288c41e1282aafc6a13733820dda44272c602a06c9fa5.jpg)

![64c93a9d77d021cfb08aacb4109b712f0729c41aed49b586db1087deb9fb7cb2.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/64c93a9d77d021cfb08aacb4109b712f0729c41aed49b586db1087deb9fb7cb2.jpg)

![6ca13abcc441a0d77211931b068677b0eca576c27418410a069c79da7afc1154.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/6ca13abcc441a0d77211931b068677b0eca576c27418410a069c79da7afc1154.jpg)

![7144825f3742d41af61e5dad394421107012e32f20977c14b3c4bf66da3bcc1d.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/7144825f3742d41af61e5dad394421107012e32f20977c14b3c4bf66da3bcc1d.jpg)

![7aa3f68545b134975bf6557dcb3965f099d90176d383fd2f55fcf80d1fbf41b2.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/7aa3f68545b134975bf6557dcb3965f099d90176d383fd2f55fcf80d1fbf41b2.jpg)

![89297b8ed49fbf774cb368f8f44c6239300a7fab857063a196879d3613aff534.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/89297b8ed49fbf774cb368f8f44c6239300a7fab857063a196879d3613aff534.jpg)

![9af9cab913b746bc3640e499c59bdb1a2e220bb646a731913ad2540f7dc597e2.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/9af9cab913b746bc3640e499c59bdb1a2e220bb646a731913ad2540f7dc597e2.jpg)

![9e0e7ed0439472aae99b0f337cf29895ea2322cba5d5b4cdcb9f6bf1c7b87940.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/9e0e7ed0439472aae99b0f337cf29895ea2322cba5d5b4cdcb9f6bf1c7b87940.jpg)

![d84cc40df94f42f5f0c906309a99846a429406514f971c53c5892d214b1b983d.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/images/d84cc40df94f42f5f0c906309a99846a429406514f971c53c5892d214b1b983d.jpg)

### Tables

![0d2dce4fe2745f19795d0fcdd7d4086e4a89f47a1b52df94b7b17cc1374bc80d.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/0d2dce4fe2745f19795d0fcdd7d4086e4a89f47a1b52df94b7b17cc1374bc80d.jpg)

![147c27d654193b1b35a5dbe5d894a4b25afee08e147df599213965d46549a672.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/147c27d654193b1b35a5dbe5d894a4b25afee08e147df599213965d46549a672.jpg)

![187cea97f391d8b2818c6711569eb80a290f6bf4910dbd7e98406b50c38c72f6.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/187cea97f391d8b2818c6711569eb80a290f6bf4910dbd7e98406b50c38c72f6.jpg)

![434a17c385a0cf78f7ca779b96e3bb6a266034a1c463efda14ae5eb1498f9601.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/434a17c385a0cf78f7ca779b96e3bb6a266034a1c463efda14ae5eb1498f9601.jpg)

![6246d2f5805ce3225512f0f1ea310f39f57247fbba515c0babe33e62b4964cef.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/6246d2f5805ce3225512f0f1ea310f39f57247fbba515c0babe33e62b4964cef.jpg)

![63955f3a40ede3cfce373221b6f508bcc41deedb852fb547278bd36ab596c0ed.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/63955f3a40ede3cfce373221b6f508bcc41deedb852fb547278bd36ab596c0ed.jpg)

![6adfe49ab87adefb9a405bbd1794b6003fd29aa946e54e8f9bcade9d58989b65.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/6adfe49ab87adefb9a405bbd1794b6003fd29aa946e54e8f9bcade9d58989b65.jpg)

![702b3121e71a7851915042cccde01de830e656423e312895d26858a8d42dabf2.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/702b3121e71a7851915042cccde01de830e656423e312895d26858a8d42dabf2.jpg)

![76689505d3424d88e3352b2740930c576df1fbca21e8dfe6d5b1da0db3a2c905.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/76689505d3424d88e3352b2740930c576df1fbca21e8dfe6d5b1da0db3a2c905.jpg)

![7efe0cf54647284b19156909c346106eaf2ef359b45dfe821246e7ad74442c29.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/7efe0cf54647284b19156909c346106eaf2ef359b45dfe821246e7ad74442c29.jpg)

![86f8123dc3d46ddc5c175f81785286949a6a0163cd501b855f2b370d6bd6d933.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/86f8123dc3d46ddc5c175f81785286949a6a0163cd501b855f2b370d6bd6d933.jpg)

![92968c4b9595e20be11e5951b99bc6f5f95255ae4109d82eca2ad479418749bf.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/92968c4b9595e20be11e5951b99bc6f5f95255ae4109d82eca2ad479418749bf.jpg)

![a5764c51902643718ec6ad39252a5cb0d7279a8b36682938507fd177f2b014ff.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/a5764c51902643718ec6ad39252a5cb0d7279a8b36682938507fd177f2b014ff.jpg)

![c5e6e910899a0a792ccf181ea21a8a80a21dfd8d4200ef8de382308672ff1111.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/c5e6e910899a0a792ccf181ea21a8a80a21dfd8d4200ef8de382308672ff1111.jpg)

![d97350a7ecd2d6dddcbf318716a2ad96c0f0947a2ed2b44e109388112779507e.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/d97350a7ecd2d6dddcbf318716a2ad96c0f0947a2ed2b44e109388112779507e.jpg)

![fd870c9c591058236a51a192c2a47a12cc5da97cace8b189075d36bea0ba9003.jpg](../emnlp_results/422_X-FLoRA_%20Cross-modal%20Federated%20Learning%20with%20Modality-expertLoRAfor%20MedicalVQA/tables/fd870c9c591058236a51a192c2a47a12cc5da97cace8b189075d36bea0ba9003.jpg)

## Robust Native Language Identification through Agentic Decomposition


### Images

![0e8563f7816361c1d03d7748a845bfd9f215d03a342208881e07f3db8aa83c75.jpg](../emnlp_results/423_Robust%20Native%20Language%20Identification%20through%20Agentic%20Decomposition/images/0e8563f7816361c1d03d7748a845bfd9f215d03a342208881e07f3db8aa83c75.jpg)

![23b65d4dc6bbdda95b72b36ad5278a81e447d7fcbde2d986e6800aa91e26deee.jpg](../emnlp_results/423_Robust%20Native%20Language%20Identification%20through%20Agentic%20Decomposition/images/23b65d4dc6bbdda95b72b36ad5278a81e447d7fcbde2d986e6800aa91e26deee.jpg)

![31db8af1f42d677d206bab0561cbcedb2c4a3b9d99d5c0f26595631d5425e95c.jpg](../emnlp_results/423_Robust%20Native%20Language%20Identification%20through%20Agentic%20Decomposition/images/31db8af1f42d677d206bab0561cbcedb2c4a3b9d99d5c0f26595631d5425e95c.jpg)

![63409442b4ec7cc712354b9193f64ec2a1329b973b3ba5a9e345a5d8d2323e39.jpg](../emnlp_results/423_Robust%20Native%20Language%20Identification%20through%20Agentic%20Decomposition/images/63409442b4ec7cc712354b9193f64ec2a1329b973b3ba5a9e345a5d8d2323e39.jpg)

![966a7d7a090e92a48c8fc22b849373c398ae9a0d798c870f1ee98236b144df16.jpg](../emnlp_results/423_Robust%20Native%20Language%20Identification%20through%20Agentic%20Decomposition/images/966a7d7a090e92a48c8fc22b849373c398ae9a0d798c870f1ee98236b144df16.jpg)

![be9fa11dd1d9973164fd02199587a35af038ea912a4651224419ebe7495de01d.jpg](../emnlp_results/423_Robust%20Native%20Language%20Identification%20through%20Agentic%20Decomposition/images/be9fa11dd1d9973164fd02199587a35af038ea912a4651224419ebe7495de01d.jpg)

![d75a68627521805f7c638508b2f2873ffae8695b90b4b98c60eef68102487c98.jpg](../emnlp_results/423_Robust%20Native%20Language%20Identification%20through%20Agentic%20Decomposition/images/d75a68627521805f7c638508b2f2873ffae8695b90b4b98c60eef68102487c98.jpg)

### Tables

![09d7569b49e81525391eef22cfd399e1cb78a968261d6b8e325796f3468f4519.jpg](../emnlp_results/423_Robust%20Native%20Language%20Identification%20through%20Agentic%20Decomposition/tables/09d7569b49e81525391eef22cfd399e1cb78a968261d6b8e325796f3468f4519.jpg)

![225ba61ea04517e52ad148d833fac23fe57368cba14a901e79f24f40a5556028.jpg](../emnlp_results/423_Robust%20Native%20Language%20Identification%20through%20Agentic%20Decomposition/tables/225ba61ea04517e52ad148d833fac23fe57368cba14a901e79f24f40a5556028.jpg)

![2da10760bd2617c7d6f61bc80dc678e3100a50d29e727db6e44870c6108c83ce.jpg](../emnlp_results/423_Robust%20Native%20Language%20Identification%20through%20Agentic%20Decomposition/tables/2da10760bd2617c7d6f61bc80dc678e3100a50d29e727db6e44870c6108c83ce.jpg)

![52d0a0b94b69eaf2e35f4af31c62732ebb5ee8e1672b04be946df1a0720ef95f.jpg](../emnlp_results/423_Robust%20Native%20Language%20Identification%20through%20Agentic%20Decomposition/tables/52d0a0b94b69eaf2e35f4af31c62732ebb5ee8e1672b04be946df1a0720ef95f.jpg)

## ConsistentChat: Building Skeleton-Guided Consistent Multi-Turn Dialogues for Large Language Models from Scratch


### Images

![0c3afeee9c8264294e74ef7d9daea12d322e39c8275a5c8780e9451f9777c4d6.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/images/0c3afeee9c8264294e74ef7d9daea12d322e39c8275a5c8780e9451f9777c4d6.jpg)

![37889b48118c4fd7f693d9a90ac52c9c81cddb8073f4b66f033de0d851a136f3.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/images/37889b48118c4fd7f693d9a90ac52c9c81cddb8073f4b66f033de0d851a136f3.jpg)

![49705dc96c24e4add577d250c00b4e5514971266b8ff074a22e6541791d89d5a.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/images/49705dc96c24e4add577d250c00b4e5514971266b8ff074a22e6541791d89d5a.jpg)

![54dfb63c2625d1355d3870ac40b70d52e5d8c20bb58344c44352992c30424fed.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/images/54dfb63c2625d1355d3870ac40b70d52e5d8c20bb58344c44352992c30424fed.jpg)

![9c0a5cf0eee4311167937924a4f7dd7a8012949db1cc83406248df51a4aba2db.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/images/9c0a5cf0eee4311167937924a4f7dd7a8012949db1cc83406248df51a4aba2db.jpg)

![a6ce0daded489d78ffcf07e62ff8db71c8e949f9513fa45b986ee908c557d968.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/images/a6ce0daded489d78ffcf07e62ff8db71c8e949f9513fa45b986ee908c557d968.jpg)

![c26abedd03ec146c89806a297865ee713dbae50151fb320abc219d1799ab201f.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/images/c26abedd03ec146c89806a297865ee713dbae50151fb320abc219d1799ab201f.jpg)

![f5088bad425db32eac1c4dda18a2bdcd6cb08fd0b9ad40e92d8b914da56b1845.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/images/f5088bad425db32eac1c4dda18a2bdcd6cb08fd0b9ad40e92d8b914da56b1845.jpg)

### Tables

![0464f95e64b4ec810d3245ac19189005868227232b811c9e4c4d66dcd61a1a9e.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/0464f95e64b4ec810d3245ac19189005868227232b811c9e4c4d66dcd61a1a9e.jpg)

![12607ae0d85fb7fb138c8e2ac7a6a5d87f69ed53d5f49ac94f21b8eca5ff1627.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/12607ae0d85fb7fb138c8e2ac7a6a5d87f69ed53d5f49ac94f21b8eca5ff1627.jpg)

![2a0ee1660ebce384a284080ca7dcd6714d208deecdb1c069fad8f6cffb3fa691.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/2a0ee1660ebce384a284080ca7dcd6714d208deecdb1c069fad8f6cffb3fa691.jpg)

![301fb5efd3c48fe80408567098430ba192b51b2184a2797f0fad7d0198df7159.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/301fb5efd3c48fe80408567098430ba192b51b2184a2797f0fad7d0198df7159.jpg)

![522061ca1bf3ed423800594a6ca37d681c6749ef6632beea30e93ccab60e8a72.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/522061ca1bf3ed423800594a6ca37d681c6749ef6632beea30e93ccab60e8a72.jpg)

![5d4c294f6de45fbcabe397a784c6b155af095a1c93ddc654a23f48836a8672fe.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/5d4c294f6de45fbcabe397a784c6b155af095a1c93ddc654a23f48836a8672fe.jpg)

![60870d01582d2c18b3e67390dacaca5115b0820918157d443e0181ab4cceca2e.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/60870d01582d2c18b3e67390dacaca5115b0820918157d443e0181ab4cceca2e.jpg)

![621fa3f08ab3d3a89fab1050c45caac3b6a09751154006e0c931a75f190eb9b9.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/621fa3f08ab3d3a89fab1050c45caac3b6a09751154006e0c931a75f190eb9b9.jpg)

![6c99cbb4484b53ad6490511b42f4f66d5fb4a5db78696e3059b34df263eea4c6.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/6c99cbb4484b53ad6490511b42f4f66d5fb4a5db78696e3059b34df263eea4c6.jpg)

![7c15950bf1b88f9c7dcbd48a91b7d1ab208384cd0335230f6daaebd0c637c7ff.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/7c15950bf1b88f9c7dcbd48a91b7d1ab208384cd0335230f6daaebd0c637c7ff.jpg)

![84193a5258d36f5dcfd55d4ff4eaf58812d565f317b9544f71804f1843faaf8c.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/84193a5258d36f5dcfd55d4ff4eaf58812d565f317b9544f71804f1843faaf8c.jpg)

![84bf4fe68d1abb5b1906dab323a0dfb84ad24cde359333a6e1ccbe186e0f5224.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/84bf4fe68d1abb5b1906dab323a0dfb84ad24cde359333a6e1ccbe186e0f5224.jpg)

![9976ca4666a6fd60b8455fe18e6f52e83231d20ac93ac97859fada675bec8aca.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/9976ca4666a6fd60b8455fe18e6f52e83231d20ac93ac97859fada675bec8aca.jpg)

![a7f9c323d53c428051bfeaf59fded667d75e707b728468d0a5f88391df03502d.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/a7f9c323d53c428051bfeaf59fded667d75e707b728468d0a5f88391df03502d.jpg)

![bdfd98e7bf68858ca99be3b490143bbb8b7ec04665c8ddf458e7d0e42c56e351.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/bdfd98e7bf68858ca99be3b490143bbb8b7ec04665c8ddf458e7d0e42c56e351.jpg)

![cf82dfa45f6abe9ad69dcbd5086e08991fe498d4410a7175923b2fae640e568e.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/cf82dfa45f6abe9ad69dcbd5086e08991fe498d4410a7175923b2fae640e568e.jpg)

![d400adf65b5b45ab58361d93c192c5b727189ec02e83643b23bb210984b2b7ce.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/d400adf65b5b45ab58361d93c192c5b727189ec02e83643b23bb210984b2b7ce.jpg)

![de6bd2503909209c3cc32c0f2206e3237786c21d88c38954bd1cf2e53f113d9d.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/de6bd2503909209c3cc32c0f2206e3237786c21d88c38954bd1cf2e53f113d9d.jpg)

![ff2d3140cb1f0c2617ab3c37499aaeb09be7599380b84a51e366319f53f17f32.jpg](../emnlp_results/424_ConsistentChat_%20Building%20Skeleton-Guided%20Consistent%20Multi-Turn%20Dialogues%20for%20Large%20Language%20Models%20f/tables/ff2d3140cb1f0c2617ab3c37499aaeb09be7599380b84a51e366319f53f17f32.jpg)

## Does Acceleration Cause Hidden Instability in Vision Language Models? Uncovering Instance-Level Divergence Through a Large-Scale Empirical Study


### Images

![002d6767211344764091b02fbf7f0b341415c4264203c6f17e09b0d9cf1426b3.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/images/002d6767211344764091b02fbf7f0b341415c4264203c6f17e09b0d9cf1426b3.jpg)

![1dad21f3b9a27871d0c417b4369f46311e86b72869e51e25ae92b19cd344626d.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/images/1dad21f3b9a27871d0c417b4369f46311e86b72869e51e25ae92b19cd344626d.jpg)

![4a8dc8f68709f3b59f93812de690d5808c0bd18bc4859e542b55587ff6e5c3be.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/images/4a8dc8f68709f3b59f93812de690d5808c0bd18bc4859e542b55587ff6e5c3be.jpg)

![5a65eabab3b73b2165c3882814d6001a780309bf674b9124f9084730b49d6c2f.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/images/5a65eabab3b73b2165c3882814d6001a780309bf674b9124f9084730b49d6c2f.jpg)

![66c9078798239590c140d049f4c84fee76f910314d0e46b7062df7a10b3e599a.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/images/66c9078798239590c140d049f4c84fee76f910314d0e46b7062df7a10b3e599a.jpg)

![9c3140fbff58775553bb0b1c0f8b2c3429b9e9c24cd9cd6aafb3a06cbb67f1b0.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/images/9c3140fbff58775553bb0b1c0f8b2c3429b9e9c24cd9cd6aafb3a06cbb67f1b0.jpg)

![9e4e75349901473ff9591ce8d76f77c7277d1bba8d179dbfad3a2990e5ab3b0b.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/images/9e4e75349901473ff9591ce8d76f77c7277d1bba8d179dbfad3a2990e5ab3b0b.jpg)

![b9b7502f165aba45354beb44680ea4b0be83f3896ab6d1fbe8a8c1939cf43aab.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/images/b9b7502f165aba45354beb44680ea4b0be83f3896ab6d1fbe8a8c1939cf43aab.jpg)

### Tables

![09727e2a79cb62713452a9bbbfac78d269ff1edcb13b565c033b6e0254c92661.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/tables/09727e2a79cb62713452a9bbbfac78d269ff1edcb13b565c033b6e0254c92661.jpg)

![18adab68907b00c7eb36b6d8103807c35692e155494933dbd186e6b3873b49ef.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/tables/18adab68907b00c7eb36b6d8103807c35692e155494933dbd186e6b3873b49ef.jpg)

![20a4e77b004bf4cf6e090743df51ae4788876be47146ef5e41b5c297b2023163.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/tables/20a4e77b004bf4cf6e090743df51ae4788876be47146ef5e41b5c297b2023163.jpg)

![27a7cce66a2973ca7f5118ab308ec715f1b093d50b14847ba2d304018c359f03.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/tables/27a7cce66a2973ca7f5118ab308ec715f1b093d50b14847ba2d304018c359f03.jpg)

![59be390be7700e8c5a7791fff394c5eb823ce1bcd6905ceb4a2e96d58406f13a.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/tables/59be390be7700e8c5a7791fff394c5eb823ce1bcd6905ceb4a2e96d58406f13a.jpg)

![675aef9eceea2af438bc24693b59222562e8b45e315f670b543bd9ec4ede5bfa.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/tables/675aef9eceea2af438bc24693b59222562e8b45e315f670b543bd9ec4ede5bfa.jpg)

![85ae6e234ba3e076a818a1bc04e1725f83fa8a8baa74046693ddf4013c39ad03.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/tables/85ae6e234ba3e076a818a1bc04e1725f83fa8a8baa74046693ddf4013c39ad03.jpg)

![af897fdd5a26a051f36df290ed7d6a489c2cd7d08ad16e78235a762477f620e8.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/tables/af897fdd5a26a051f36df290ed7d6a489c2cd7d08ad16e78235a762477f620e8.jpg)

![dff959d1b5bf329565bf21873bcfb02edb55bdd0191ad4ca8cc418eb7b1a8a50.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/tables/dff959d1b5bf329565bf21873bcfb02edb55bdd0191ad4ca8cc418eb7b1a8a50.jpg)

![e55f374711319a201429cff22857cc79036be9a95cfd6c377cb58e0778f4a411.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/tables/e55f374711319a201429cff22857cc79036be9a95cfd6c377cb58e0778f4a411.jpg)

![f61e3204a2e7a00076b2b72f662a7809bb29388559b27c234f12eae9b558c452.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/tables/f61e3204a2e7a00076b2b72f662a7809bb29388559b27c234f12eae9b558c452.jpg)

![fde51061941c532b08239eec38fde458a7595a92f5f63960d22054806b70ca79.jpg](../emnlp_results/425_Does%20Acceleration%20Cause%20Hidden%20Instability%20in%20Vision%20Language%20Models_%20Uncovering%20Instance-Level%20Dive/tables/fde51061941c532b08239eec38fde458a7595a92f5f63960d22054806b70ca79.jpg)

## When Annotators Disagree, Topology Explains: Mapper, a Topological Tool for Exploring Text Embedding Geometry and Ambiguity


### Images

![101058b536268c3ce1f807f758d958d1872ce6f5a463500609d00760975e3163.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/images/101058b536268c3ce1f807f758d958d1872ce6f5a463500609d00760975e3163.jpg)

![173f45299b0f9a754c9db35562dd12698d2650b6de61f621e9718b2233ff8f2f.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/images/173f45299b0f9a754c9db35562dd12698d2650b6de61f621e9718b2233ff8f2f.jpg)

![17acc4739a54d4195ba989fe59ace7c16d81b6259596a69e673af6f3a5b75a45.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/images/17acc4739a54d4195ba989fe59ace7c16d81b6259596a69e673af6f3a5b75a45.jpg)

![3c7938d62062470767abfbb14cb283dc5521e03f5b2bbf10b69500fa0e9051b6.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/images/3c7938d62062470767abfbb14cb283dc5521e03f5b2bbf10b69500fa0e9051b6.jpg)

![4b930dd9ebf8aa5e0613a14a12f6a5e2e57918699859259dcf67a8bd5d1314af.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/images/4b930dd9ebf8aa5e0613a14a12f6a5e2e57918699859259dcf67a8bd5d1314af.jpg)

![6c8b90181e52a06b340dda3ff42f28a99d747f6f799c06b0b4dc60314ed2431d.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/images/6c8b90181e52a06b340dda3ff42f28a99d747f6f799c06b0b4dc60314ed2431d.jpg)

![87601fa1df6a612daee190ec087dd3c2109e378dfa8d4780c4dbe901601e548e.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/images/87601fa1df6a612daee190ec087dd3c2109e378dfa8d4780c4dbe901601e548e.jpg)

![9875a92cb532a31958c786c397a470aeeb08559a8be83cffa125cc55352ee6e3.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/images/9875a92cb532a31958c786c397a470aeeb08559a8be83cffa125cc55352ee6e3.jpg)

![a9355d8db5f94eeb711ca7e555fae071658a64e7d76f04ddf43efc13a8d76b37.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/images/a9355d8db5f94eeb711ca7e555fae071658a64e7d76f04ddf43efc13a8d76b37.jpg)

![b35a3c02cd9f156fd8bfdb1b2d2041ef3e96ac9e96482d30ffea048139c868d3.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/images/b35a3c02cd9f156fd8bfdb1b2d2041ef3e96ac9e96482d30ffea048139c868d3.jpg)

![b4127d6ebdf6261844b6c6875d2f10c653f6b09b6695e85f80e3be5cdbbc69ee.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/images/b4127d6ebdf6261844b6c6875d2f10c653f6b09b6695e85f80e3be5cdbbc69ee.jpg)

![b9c5f73e3fd91d59b82e21d7ca634d97fa55206c861830501e5aa30bbf5862bd.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/images/b9c5f73e3fd91d59b82e21d7ca634d97fa55206c861830501e5aa30bbf5862bd.jpg)

![bee95f6604a7e3d47f927410ba736e3f922dc5db339dd7e8b6222b5efd1fd046.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/images/bee95f6604a7e3d47f927410ba736e3f922dc5db339dd7e8b6222b5efd1fd046.jpg)

### Tables

![0d8fa144572d1d5d530c489a76b40d185faedf8513cba9afcc55add2b19b1337.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/tables/0d8fa144572d1d5d530c489a76b40d185faedf8513cba9afcc55add2b19b1337.jpg)

![1230c917309a1f0a5db59290c4b7d776f44f14469dc30008e94fab7476197190.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/tables/1230c917309a1f0a5db59290c4b7d776f44f14469dc30008e94fab7476197190.jpg)

![1b6e4ada598ffe93e3fa6d219e9866817170718c679662827f61436472ef1ebf.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/tables/1b6e4ada598ffe93e3fa6d219e9866817170718c679662827f61436472ef1ebf.jpg)

![465bbb18237769479b3e5bf76bb098e93d74a031d336384d0a8e775f5dfb8fe9.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/tables/465bbb18237769479b3e5bf76bb098e93d74a031d336384d0a8e775f5dfb8fe9.jpg)

![46e75f599b567407b3ff9cf1f7d5a6b04f2ee1efb2818163357d50a812a8f360.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/tables/46e75f599b567407b3ff9cf1f7d5a6b04f2ee1efb2818163357d50a812a8f360.jpg)

![5301042b5d2edf6abd53965282eac188e1a93f202ab99d9fb1cd2c26279f8b3e.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/tables/5301042b5d2edf6abd53965282eac188e1a93f202ab99d9fb1cd2c26279f8b3e.jpg)

![fa38f84ff81f0b826444c824e6089571745d039a2c730cd938c93383f29a8dcf.jpg](../emnlp_results/426_When%20Annotators%20Disagree%2C%20Topology%20Explains_%20Mapper%2C%20a%20Topological%20Tool%20for%20Exploring%20Text%20Embedding/tables/fa38f84ff81f0b826444c824e6089571745d039a2c730cd938c93383f29a8dcf.jpg)

## Self-Critique and Refinement for Faithful Natural Language Explanations


### Images

![0c261a781a79673d143c866bec15e6daf69be23a0b9e8248a8a555393f7de0ed.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/images/0c261a781a79673d143c866bec15e6daf69be23a0b9e8248a8a555393f7de0ed.jpg)

![33977f786320b543a3e2c401f169ecc5ddcbaccfb78f0b1f03bc9068208b9f09.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/images/33977f786320b543a3e2c401f169ecc5ddcbaccfb78f0b1f03bc9068208b9f09.jpg)

![741a0b6fcdb6cb9be027d086da54aa1acdeeef11de6e325d05b4f538367a6008.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/images/741a0b6fcdb6cb9be027d086da54aa1acdeeef11de6e325d05b4f538367a6008.jpg)

![836a3f937195398f75c9a1087d7b795e539f7cc53236eda06c34efb3203dd852.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/images/836a3f937195398f75c9a1087d7b795e539f7cc53236eda06c34efb3203dd852.jpg)

![868ee7981275fa5ed2057775760ab6365b58d0ab71cca8e38e91efecd4f023f7.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/images/868ee7981275fa5ed2057775760ab6365b58d0ab71cca8e38e91efecd4f023f7.jpg)

![af597aa25aa41fd28ecbc6fca7667aa8e65bb67ca7c5b409dd85e52ad4ed964e.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/images/af597aa25aa41fd28ecbc6fca7667aa8e65bb67ca7c5b409dd85e52ad4ed964e.jpg)

![c473e2ff184453effdf93b39d6297b35d5d8b54f93870885959a3cc91c98e764.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/images/c473e2ff184453effdf93b39d6297b35d5d8b54f93870885959a3cc91c98e764.jpg)

![c57b9b6f3e5277b7c9d7aca99d3ad9936ff386776bcf13b24419ef3490a3a727.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/images/c57b9b6f3e5277b7c9d7aca99d3ad9936ff386776bcf13b24419ef3490a3a727.jpg)

![d47cdf6a99edb42417c49e64e9afe800510ee6c8a145bec8e92471815e387d17.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/images/d47cdf6a99edb42417c49e64e9afe800510ee6c8a145bec8e92471815e387d17.jpg)

![df1cf2139b22e0024b9a503e15c4ca9b13e4a77c3fe63977e4ebd24d8bde2eab.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/images/df1cf2139b22e0024b9a503e15c4ca9b13e4a77c3fe63977e4ebd24d8bde2eab.jpg)

### Tables

![0a70fbf237298bcec7732391a257a3ba202c24c3bd8e78ff86c222ed67bcb2d6.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/0a70fbf237298bcec7732391a257a3ba202c24c3bd8e78ff86c222ed67bcb2d6.jpg)

![0c635b77efc27365ed4b2eb374503c88e1b35b1b9e88a08f538c7ccaf7ca49e5.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/0c635b77efc27365ed4b2eb374503c88e1b35b1b9e88a08f538c7ccaf7ca49e5.jpg)

![1033f5c4daf7c0658c3bd3d71c3119c0dfbc2395f96c87a94bb678028f4fdc9d.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/1033f5c4daf7c0658c3bd3d71c3119c0dfbc2395f96c87a94bb678028f4fdc9d.jpg)

![111946a8dd7e07ff77abb96f310cf9ca43f185a720a9b25f7cd0fc2bc3c3ed01.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/111946a8dd7e07ff77abb96f310cf9ca43f185a720a9b25f7cd0fc2bc3c3ed01.jpg)

![2828088f0c0cd5dc1fb7a16b5115f45296b432b08f06f5e3084fcb02e50d36fd.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/2828088f0c0cd5dc1fb7a16b5115f45296b432b08f06f5e3084fcb02e50d36fd.jpg)

![3e621ce877135e529b05e36f87d43fc0f5630fa33d410ba2112d90b129985480.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/3e621ce877135e529b05e36f87d43fc0f5630fa33d410ba2112d90b129985480.jpg)

![432e6fa5154fc67bcfb4ec53c0a70d37266445336189f06f61b9a64cd7656fd5.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/432e6fa5154fc67bcfb4ec53c0a70d37266445336189f06f61b9a64cd7656fd5.jpg)

![56b20e20413974c2cda7acb7934758df7bd2c2861f5dea5e1cd5fd12a1072e09.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/56b20e20413974c2cda7acb7934758df7bd2c2861f5dea5e1cd5fd12a1072e09.jpg)

![6e0aaca9410dc14195263e810c3d418bd75713cf03a99fd23b1c9230980bf213.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/6e0aaca9410dc14195263e810c3d418bd75713cf03a99fd23b1c9230980bf213.jpg)

![728ee7ec1539fed84e57826bcf94ec3b4a1556891c3f01be12e775966a6916c9.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/728ee7ec1539fed84e57826bcf94ec3b4a1556891c3f01be12e775966a6916c9.jpg)

![8b69433c908366057bb227ef5f41ffd471d49bda820a587bb21bc9a653c739cf.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/8b69433c908366057bb227ef5f41ffd471d49bda820a587bb21bc9a653c739cf.jpg)

![8cd3060f98186159f357c87558c5ca3cdef42408821701877b12e9052d0a7672.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/8cd3060f98186159f357c87558c5ca3cdef42408821701877b12e9052d0a7672.jpg)

![a0528995481c0aa490dfb2b8e85574bce4a4ae19ed1f363b8a23d3116b5149aa.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/a0528995481c0aa490dfb2b8e85574bce4a4ae19ed1f363b8a23d3116b5149aa.jpg)

![a2ea37800a92411511e5ac7b32fdf1baf8111a5c25bd984a83fb7da0c5adc3b2.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/a2ea37800a92411511e5ac7b32fdf1baf8111a5c25bd984a83fb7da0c5adc3b2.jpg)

![a9b55eaa9fe14af31529e18a8cc139859607fe645c4eda57c357681c80912747.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/a9b55eaa9fe14af31529e18a8cc139859607fe645c4eda57c357681c80912747.jpg)

![acb6b1771bc745c6421e13a49bd303f053b415caf8f95f9aaf8c833c20f59f8f.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/acb6b1771bc745c6421e13a49bd303f053b415caf8f95f9aaf8c833c20f59f8f.jpg)

![b00aba12282ca4232089dcbc28a2878c228226adf2cf312bd916f15597a55e49.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/b00aba12282ca4232089dcbc28a2878c228226adf2cf312bd916f15597a55e49.jpg)

![b8c220471c5f27a2538b38ea7870358e6f51bb46b3a643ce2e89d8e54eb54740.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/b8c220471c5f27a2538b38ea7870358e6f51bb46b3a643ce2e89d8e54eb54740.jpg)

![c8532409d4330b060f31114dfa8ef630a17371238d8a16cb3b63c3c72bffc4a2.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/c8532409d4330b060f31114dfa8ef630a17371238d8a16cb3b63c3c72bffc4a2.jpg)

![d4e7bd317fa934a6f9ed052e8a5151c6d6729d5bbf2c592bdc23e1d709c0f11c.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/d4e7bd317fa934a6f9ed052e8a5151c6d6729d5bbf2c592bdc23e1d709c0f11c.jpg)

![e8f67de5240cd8d34983b028df7f218854b0c7d8890f16038538114808769efb.jpg](../emnlp_results/427_Self-Critique%20and%20Refinement%20for%20Faithful%20Natural%20Language%20Explanations/tables/e8f67de5240cd8d34983b028df7f218854b0c7d8890f16038538114808769efb.jpg)

## The Psychology of Falsehood: A Human-Centric Survey of Misinformation Detection


### Images

![7f21f1473fdb705a5cce910aa662074bfd37cfcd70d9a5ab11632828b6189d7e.jpg](../emnlp_results/428_The%20Psychology%20of%20Falsehood_%20A%20Human-Centric%20Survey%20of%20Misinformation%20Detection/images/7f21f1473fdb705a5cce910aa662074bfd37cfcd70d9a5ab11632828b6189d7e.jpg)

![add94cee9de75b787ebe41a3569e3277ca13aaeb66061786656b60425e994fa6.jpg](../emnlp_results/428_The%20Psychology%20of%20Falsehood_%20A%20Human-Centric%20Survey%20of%20Misinformation%20Detection/images/add94cee9de75b787ebe41a3569e3277ca13aaeb66061786656b60425e994fa6.jpg)

![d79b3efb6709b1641670ad7d3bc02d91ad3b2853fefd6137f6d80769a76057a2.jpg](../emnlp_results/428_The%20Psychology%20of%20Falsehood_%20A%20Human-Centric%20Survey%20of%20Misinformation%20Detection/images/d79b3efb6709b1641670ad7d3bc02d91ad3b2853fefd6137f6d80769a76057a2.jpg)

### Tables

![86b96c157072b2940321def3807451fe65de37691a394ce26246dabe5c343ac4.jpg](../emnlp_results/428_The%20Psychology%20of%20Falsehood_%20A%20Human-Centric%20Survey%20of%20Misinformation%20Detection/tables/86b96c157072b2940321def3807451fe65de37691a394ce26246dabe5c343ac4.jpg)

![be947213c06f70685ff8bf09549826ae8563f18f69ec18286c11a7e7964dc30f.jpg](../emnlp_results/428_The%20Psychology%20of%20Falsehood_%20A%20Human-Centric%20Survey%20of%20Misinformation%20Detection/tables/be947213c06f70685ff8bf09549826ae8563f18f69ec18286c11a7e7964dc30f.jpg)

![e89384eef2e190b0895c022d9f5b10a7c13d6353fcedeabfdf8f338b2745eafa.jpg](../emnlp_results/428_The%20Psychology%20of%20Falsehood_%20A%20Human-Centric%20Survey%20of%20Misinformation%20Detection/tables/e89384eef2e190b0895c022d9f5b10a7c13d6353fcedeabfdf8f338b2745eafa.jpg)

## SEAL: Structure and Element Aware Learning Improves Long Structured Document Retrieval


### Images

![089a47f6fd68fc3d72610712aadcd7d213de19565beff4ccf99152c2b6871ea0.jpg](../emnlp_results/429_SEAL_%20Structure%20and%20Element%20Aware%20Learning%20Improves%20Long%20Structured%20Document%20Retrieval/images/089a47f6fd68fc3d72610712aadcd7d213de19565beff4ccf99152c2b6871ea0.jpg)

![4a2c8a7f67edca8bda7594b9d9b9558245a52943e5a7d4f485c3d2ff635f5f0d.jpg](../emnlp_results/429_SEAL_%20Structure%20and%20Element%20Aware%20Learning%20Improves%20Long%20Structured%20Document%20Retrieval/images/4a2c8a7f67edca8bda7594b9d9b9558245a52943e5a7d4f485c3d2ff635f5f0d.jpg)

![8c918b23be62dc3ea4ccc3c9b8ff869b74c10ff5b5b68c0fa0b5f6e75b64030d.jpg](../emnlp_results/429_SEAL_%20Structure%20and%20Element%20Aware%20Learning%20Improves%20Long%20Structured%20Document%20Retrieval/images/8c918b23be62dc3ea4ccc3c9b8ff869b74c10ff5b5b68c0fa0b5f6e75b64030d.jpg)

![919fff7769b6589320ef22e22c443f5b3fe5a35d2ba4683f8356268187c91c67.jpg](../emnlp_results/429_SEAL_%20Structure%20and%20Element%20Aware%20Learning%20Improves%20Long%20Structured%20Document%20Retrieval/images/919fff7769b6589320ef22e22c443f5b3fe5a35d2ba4683f8356268187c91c67.jpg)

### Tables

![08ab14f4a21916d715fe8ae2eb620d504e5be2ca5fbb4acb66c301fd320074dc.jpg](../emnlp_results/429_SEAL_%20Structure%20and%20Element%20Aware%20Learning%20Improves%20Long%20Structured%20Document%20Retrieval/tables/08ab14f4a21916d715fe8ae2eb620d504e5be2ca5fbb4acb66c301fd320074dc.jpg)

![0eda92bad5c7cb8ff2e6b926c092d60a4f16f83422b54bda7145dfcc891104e7.jpg](../emnlp_results/429_SEAL_%20Structure%20and%20Element%20Aware%20Learning%20Improves%20Long%20Structured%20Document%20Retrieval/tables/0eda92bad5c7cb8ff2e6b926c092d60a4f16f83422b54bda7145dfcc891104e7.jpg)

![1cece8e49416091a6016b0b50114fe7b09cdd7881e555f8fc9d358b6557b7252.jpg](../emnlp_results/429_SEAL_%20Structure%20and%20Element%20Aware%20Learning%20Improves%20Long%20Structured%20Document%20Retrieval/tables/1cece8e49416091a6016b0b50114fe7b09cdd7881e555f8fc9d358b6557b7252.jpg)

![72c903f9c95f507e16e404d590d72f6924254ffafb5f16a5aa66c1596e228409.jpg](../emnlp_results/429_SEAL_%20Structure%20and%20Element%20Aware%20Learning%20Improves%20Long%20Structured%20Document%20Retrieval/tables/72c903f9c95f507e16e404d590d72f6924254ffafb5f16a5aa66c1596e228409.jpg)

![b318602c73f171f666cf0fe555d084c838d5817f5ca0bb909e560ddaaf200664.jpg](../emnlp_results/429_SEAL_%20Structure%20and%20Element%20Aware%20Learning%20Improves%20Long%20Structured%20Document%20Retrieval/tables/b318602c73f171f666cf0fe555d084c838d5817f5ca0bb909e560ddaaf200664.jpg)

![c553fe05e45efbc8076dfa771ebbf8c445a1cd25c5670b8d057ffb9c41a72fab.jpg](../emnlp_results/429_SEAL_%20Structure%20and%20Element%20Aware%20Learning%20Improves%20Long%20Structured%20Document%20Retrieval/tables/c553fe05e45efbc8076dfa771ebbf8c445a1cd25c5670b8d057ffb9c41a72fab.jpg)

![d9190c98dd761e3aba7f6d2a72c877b70df1e7425dc2167a558fac8dc85aaa47.jpg](../emnlp_results/429_SEAL_%20Structure%20and%20Element%20Aware%20Learning%20Improves%20Long%20Structured%20Document%20Retrieval/tables/d9190c98dd761e3aba7f6d2a72c877b70df1e7425dc2167a558fac8dc85aaa47.jpg)

![e1ca862ccecd43d4a59cc6722cc82cf955ec86662e131619c6115d0fb48d066e.jpg](../emnlp_results/429_SEAL_%20Structure%20and%20Element%20Aware%20Learning%20Improves%20Long%20Structured%20Document%20Retrieval/tables/e1ca862ccecd43d4a59cc6722cc82cf955ec86662e131619c6115d0fb48d066e.jpg)

## AnchorAttention: Difference-Aware Sparse Attention with Stripe Granularity

### Images

![13484b69926dc1763d2aa2714670f3add04415501458c079121fd4fa7f4e9d78.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/images/13484b69926dc1763d2aa2714670f3add04415501458c079121fd4fa7f4e9d78.jpg)

![183d2597466ec5a894b3d4c60bab835900e4c1bf3c545b32e4d97977f873843c.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/images/183d2597466ec5a894b3d4c60bab835900e4c1bf3c545b32e4d97977f873843c.jpg)

![1efc0f92db47cbdccfb5d7d3824aade48eeea7f988df6596ca35a5af04de4aba.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/images/1efc0f92db47cbdccfb5d7d3824aade48eeea7f988df6596ca35a5af04de4aba.jpg)

![337a977826a457bf8c05537fcbf6976337bd497d17b3e122a790823de11f81c1.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/images/337a977826a457bf8c05537fcbf6976337bd497d17b3e122a790823de11f81c1.jpg)

![3f3a666cf6facf6c84d255e46b3aa566b02e3e6b04cfbc3b376a0650ff6d4732.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/images/3f3a666cf6facf6c84d255e46b3aa566b02e3e6b04cfbc3b376a0650ff6d4732.jpg)

![791c0eb7b87815f4435b58ffa480800538da8fbef630bf47d7ae3daef1fb80e5.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/images/791c0eb7b87815f4435b58ffa480800538da8fbef630bf47d7ae3daef1fb80e5.jpg)

![beb144937725481cad248fcfae901a07a58b35ebd8ca8cf39eca4a32bd6871fb.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/images/beb144937725481cad248fcfae901a07a58b35ebd8ca8cf39eca4a32bd6871fb.jpg)

![c6a6d7046b90fed80d1f48fac17bccbdfb3f6c7f366e29a9203eb1e5c8ffb829.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/images/c6a6d7046b90fed80d1f48fac17bccbdfb3f6c7f366e29a9203eb1e5c8ffb829.jpg)

![de2bb0e0c38852475bccbb18e2312cc486dd592160b502b98c51bd8fb0db1a87.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/images/de2bb0e0c38852475bccbb18e2312cc486dd592160b502b98c51bd8fb0db1a87.jpg)

![fc2d788b8d3ed71cc7c7240bd2535eabe2053001196879b52603ad67125fb38b.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/images/fc2d788b8d3ed71cc7c7240bd2535eabe2053001196879b52603ad67125fb38b.jpg)

### Tables

![14370d72c2d78401d92a820acdb1b4d20fe9697ca242713d2faa1c869add5e05.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/tables/14370d72c2d78401d92a820acdb1b4d20fe9697ca242713d2faa1c869add5e05.jpg)

![44bd7cfb6949b7b20fd506100ecfd414936bf5d0879f866f3d7c6e1088055339.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/tables/44bd7cfb6949b7b20fd506100ecfd414936bf5d0879f866f3d7c6e1088055339.jpg)

![64f60b5e4128d9a7b4b883e2671987ce2d1ff811d5e6cfeae6bd20d0ab3e41b5.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/tables/64f60b5e4128d9a7b4b883e2671987ce2d1ff811d5e6cfeae6bd20d0ab3e41b5.jpg)

![68884a6ccb189d4739bf6e3576cb4330781dd3c0acdef6a14d4d1fe9ddb88b50.jpg](../emnlp_results/430_AnchorAttention_%20Difference-Aware%20Sparse%20Attention%20with%20Stripe%20Granularity/tables/68884a6ccb189d4739bf6e3576cb4330781dd3c0acdef6a14d4d1fe9ddb88b50.jpg)
