# Showing new listings for Monday, 29 June 2026
## Keyword: SLAM
### Title:
          Structured-Li-GS: Structured 3D Gaussians Splatting with LiDAR Incorporation and Spatial Constraints
 - **Authors:** Huaiyuan Weng, Huibin Li, Chul Min Yeum
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this study, we develop a Structured framework for Gaussian Splatting (3DGS) with LiDAR integration (Structured-Li-GS). It is a lightweight Gaussian Splatting pipeline that leverages LiDAR-inertial-visual SLAM. Structured-Li-GS achieves high-quality 3D reconstructions with fewer Gaussians by training on accurate, dense, colorized point clouds. Gaussian primitives are anchored using sub-sampled point clouds, and their ellipsoidal parameters are initialized from local surface geometry. Our training strategy integrates a comprehensive set of loss terms, including photometric, flattening, offset, depth, and normal losses, guided by the dense point cloud, enabling accurate reconstruction without Gaussian densification. This approach produces up-to-scale, high-fidelity results with a moderate model size. For experimental validation, we develop a custom hardware-synchronized LiDAR-camera handheld scanner. Experiments on both benchmark datasets and our real-world in-house dataset demonstrate that Structured-Li-GS surpasses state-of-the-art methods while using fewer Gaussians.
### Title:
          LXD-SLAM: LiDAR+X Dense SLAM with $\sum_{i=0}^{5}C_5^i$ Configurable Sensor Combinations
 - **Authors:** Zhong Wang, Lin Zhang, Linfei Li, Ying Shen, Shaoming Zhang, Pengcheng Shi, Shengjie Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous Localization and Mapping (SLAM) is essential for autonomous systems, yet achieving reliable, globally consistent pose estimation and dense mapping in complex environments remains challenging due to geometric degeneracy and sensor drift. While multi-sensor fusion addresses these issues, existing systems often lack the modularity to adapt to diverse platforms and rely on mathematically inconsistent fusion or suboptimal map representations. To address these limitations, we propose LXD-SLAM (LiDAR+X Dense SLAM), a highly versatile and unified multi-sensor fusion framework. Centered around 3D LiDAR, our system allows for the plug-and-play integration of LiDAR, Camera, IMU, Wheel Encoder, and GNSS, supporting up to 32 distinct sensor combinations. We employ a mathematically unified Iterative Error-Sate Kalman Filter with an adaptive hierarchical prediction strategy and an update step that minimizes point-to-mesh distances and visual reprojection errors. To support this, the environment is modeled using continuous multi-layered Gaussian Process (GP) sub-meshes, which enables efficient ray-to-mesh depth recovery for visual features. For global consistency, we introduce an Extended Scan Context (ESC) descriptor derived from the GP sub-meshes alongside a Bidirectional PnP optimization for robust multi-modal loop closure within a hybrid pose graph. Extensive evaluations on public datasets and real-world experiments demonstrate that LXD-SLAM matches or exceeds state-of-the-art specialized odometry solutions across various configurations while generating high-fidelity, globally consistent dense meshes in real-time. The relevant codes and data will be made available at this https URL upon publication.
## Keyword: odometry
### Title:
          LXD-SLAM: LiDAR+X Dense SLAM with $\sum_{i=0}^{5}C_5^i$ Configurable Sensor Combinations
 - **Authors:** Zhong Wang, Lin Zhang, Linfei Li, Ying Shen, Shaoming Zhang, Pengcheng Shi, Shengjie Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous Localization and Mapping (SLAM) is essential for autonomous systems, yet achieving reliable, globally consistent pose estimation and dense mapping in complex environments remains challenging due to geometric degeneracy and sensor drift. While multi-sensor fusion addresses these issues, existing systems often lack the modularity to adapt to diverse platforms and rely on mathematically inconsistent fusion or suboptimal map representations. To address these limitations, we propose LXD-SLAM (LiDAR+X Dense SLAM), a highly versatile and unified multi-sensor fusion framework. Centered around 3D LiDAR, our system allows for the plug-and-play integration of LiDAR, Camera, IMU, Wheel Encoder, and GNSS, supporting up to 32 distinct sensor combinations. We employ a mathematically unified Iterative Error-Sate Kalman Filter with an adaptive hierarchical prediction strategy and an update step that minimizes point-to-mesh distances and visual reprojection errors. To support this, the environment is modeled using continuous multi-layered Gaussian Process (GP) sub-meshes, which enables efficient ray-to-mesh depth recovery for visual features. For global consistency, we introduce an Extended Scan Context (ESC) descriptor derived from the GP sub-meshes alongside a Bidirectional PnP optimization for robust multi-modal loop closure within a hybrid pose graph. Extensive evaluations on public datasets and real-world experiments demonstrate that LXD-SLAM matches or exceeds state-of-the-art specialized odometry solutions across various configurations while generating high-fidelity, globally consistent dense meshes in real-time. The relevant codes and data will be made available at this https URL upon publication.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          SelectAnyTree: A Promptable Instance Segmentation Model for 3D Forest LiDAR Point Clouds
 - **Authors:** Trung Thanh Nguyen, Daniel Lusk, Kilian Gerberding, Janusch Vajna-Jehle, Tuan-Anh Vu, Duc Viet Le, Tu Vo, Phi Le Nguyen, Yasutomo Kawanishi, Takahiro Komamizu, Ichiro Ide, Julian Frey, Teja Kattenborn
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated instance segmentation of forest LiDAR point clouds is increasingly critical as forest monitoring moves toward scalable, detailed, 3D measurement. Yet, progress is constrained by label scarcity for tree instances; a single hectare can hold millions of points and hundreds of overlapping, complex crowns, making manual annotation from scratch with raw data laborious and error-prone. Annotations are often corrected from automatic pre-segmentations, but remain costly as these provide no interactive or AI-assisted refinement. Inspired by the promptable paradigm of foundation segmentation models, we propose SelectAnyTree, a promptable instance segmentation model that delineates any individual tree in a 3D forest point cloud from a few clicks. It introduces two key components: Click-to-query prompt encoder and Canopy Height Model (CHM)-guided first prompt. The former turns each click into a single content query, encoding its 3D position and positive/negative polarity together with a pooled local backbone feature. The latter provides treetops as a geometry- and ecologically guided first prompt without any user input. The resulting prompt query is then decoded into one tree mask by a state-space query decoder to efficiently capture long-range context in large-scale forest scenes with linear-time complexity. We evaluate SelectAnyTree in interactive and instance-level settings across seven diverse forest regions and an independent held-out test dataset, demonstrating strong generalization beyond the training domains. It segments a target tree to 78.2 Intersection over Union (IoU) from a single click, 24.8 points above the strongest promptable baseline, and reaches every accuracy target with the fewest clicks, while using far fewer parameters and less inference time than prior promptable models. The source code is available at this https URL.
### Title:
          Structured-Li-GS: Structured 3D Gaussians Splatting with LiDAR Incorporation and Spatial Constraints
 - **Authors:** Huaiyuan Weng, Huibin Li, Chul Min Yeum
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this study, we develop a Structured framework for Gaussian Splatting (3DGS) with LiDAR integration (Structured-Li-GS). It is a lightweight Gaussian Splatting pipeline that leverages LiDAR-inertial-visual SLAM. Structured-Li-GS achieves high-quality 3D reconstructions with fewer Gaussians by training on accurate, dense, colorized point clouds. Gaussian primitives are anchored using sub-sampled point clouds, and their ellipsoidal parameters are initialized from local surface geometry. Our training strategy integrates a comprehensive set of loss terms, including photometric, flattening, offset, depth, and normal losses, guided by the dense point cloud, enabling accurate reconstruction without Gaussian densification. This approach produces up-to-scale, high-fidelity results with a moderate model size. For experimental validation, we develop a custom hardware-synchronized LiDAR-camera handheld scanner. Experiments on both benchmark datasets and our real-world in-house dataset demonstrate that Structured-Li-GS surpasses state-of-the-art methods while using fewer Gaussians.
### Title:
          Learning 1-Bit LiDAR-based Localization with Auxiliary Objective
 - **Authors:** Kaijie Yin, Zhiyuan Zhang, Tian Gao, Wentao Zhu, Cheng-zhong Xu, Hui Kong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 6-DoF LiDAR-based localization is a fundamental capability for autonomous systems operating in large-scale outdoor environments. Many deep-learning-based localization methods have achieved promising performance so far. However, as one of the always-on modules competing for limited on-board computational resources, the localization module is expected to consume only a small portion of the overall compute budget. Most existing learning-based methods are still too heavy for this purpose. In contrast, binary neural networks (BNNs) offer an appealing solution, but the 1-bit compression causes severe information loss and performance drop. In this paper, we address this challenge by proposing Binarized LiDAR-based Localization (BiLoc), the first binary neural network framework for 6-DoF LiDAR localization. Specifically, we reinterpret the training of BNNs from the perspective of the information-bottleneck principle, aiming at retaining minimal yet sufficient representations for pose estimation while suppressing redundant variations. And we introduce an auxiliary objective that adaptively regulates information retention in the binary encoder, effectively mitigating the information loss caused by binarization. This auxiliary objective provides additional optimization signals that compensate for the limited representational capacity and the gradient mismatch inherent in BNNs. Extensive experiments on large-scale outdoor LiDAR datasets demonstrate that BiLoc establishes a new state of the art for LiDAR localization with BNNs.
### Title:
          LXD-SLAM: LiDAR+X Dense SLAM with $\sum_{i=0}^{5}C_5^i$ Configurable Sensor Combinations
 - **Authors:** Zhong Wang, Lin Zhang, Linfei Li, Ying Shen, Shaoming Zhang, Pengcheng Shi, Shengjie Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous Localization and Mapping (SLAM) is essential for autonomous systems, yet achieving reliable, globally consistent pose estimation and dense mapping in complex environments remains challenging due to geometric degeneracy and sensor drift. While multi-sensor fusion addresses these issues, existing systems often lack the modularity to adapt to diverse platforms and rely on mathematically inconsistent fusion or suboptimal map representations. To address these limitations, we propose LXD-SLAM (LiDAR+X Dense SLAM), a highly versatile and unified multi-sensor fusion framework. Centered around 3D LiDAR, our system allows for the plug-and-play integration of LiDAR, Camera, IMU, Wheel Encoder, and GNSS, supporting up to 32 distinct sensor combinations. We employ a mathematically unified Iterative Error-Sate Kalman Filter with an adaptive hierarchical prediction strategy and an update step that minimizes point-to-mesh distances and visual reprojection errors. To support this, the environment is modeled using continuous multi-layered Gaussian Process (GP) sub-meshes, which enables efficient ray-to-mesh depth recovery for visual features. For global consistency, we introduce an Extended Scan Context (ESC) descriptor derived from the GP sub-meshes alongside a Bidirectional PnP optimization for robust multi-modal loop closure within a hybrid pose graph. Extensive evaluations on public datasets and real-world experiments demonstrate that LXD-SLAM matches or exceeds state-of-the-art specialized odometry solutions across various configurations while generating high-fidelity, globally consistent dense meshes in real-time. The relevant codes and data will be made available at this https URL upon publication.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          TeRoR: Decoupled Temporal Rotation with Relational Circular Region for Temporal Knowledge Graph Embedding
 - **Authors:** Peijia Xie, Yike Liu, Chao He, Huiling Zhu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In recent years, with the emergence of Temporal Knowledge Graphs (TKGs), research on learning entity and relation representations in TKGs has attracted increasing attention, giving rise to a large number of TKG embedding methods. TeRo is a simple and efficient temporal knowledge graph embedding approach. However, TeRo does not do well in modeling the mapping properties of various relations, such as one-to-many, many-to-one, and many-to-many. Meanwhile, it also has limitations in the expression of temporal information. To address these issues, we propose a novel TKG embedding method named TeRoR. This method divides the temporal evolution of entity embeddings, and conducts independent rotation transformations on head and tail entities in the complex vector space to strengthen temporal information modeling capacity. In terms of relational characteristics, we train a radius to constrain the rotated and translated head entities within a circular region centered on the tail entity, which effectively captures the diverse mapping properties of relations. Experimental results demonstrate that TeRoR achieves competitive performance against state-of-the-art models on four distinct TKG datasets.
### Title:
          LXD-SLAM: LiDAR+X Dense SLAM with $\sum_{i=0}^{5}C_5^i$ Configurable Sensor Combinations
 - **Authors:** Zhong Wang, Lin Zhang, Linfei Li, Ying Shen, Shaoming Zhang, Pengcheng Shi, Shengjie Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous Localization and Mapping (SLAM) is essential for autonomous systems, yet achieving reliable, globally consistent pose estimation and dense mapping in complex environments remains challenging due to geometric degeneracy and sensor drift. While multi-sensor fusion addresses these issues, existing systems often lack the modularity to adapt to diverse platforms and rely on mathematically inconsistent fusion or suboptimal map representations. To address these limitations, we propose LXD-SLAM (LiDAR+X Dense SLAM), a highly versatile and unified multi-sensor fusion framework. Centered around 3D LiDAR, our system allows for the plug-and-play integration of LiDAR, Camera, IMU, Wheel Encoder, and GNSS, supporting up to 32 distinct sensor combinations. We employ a mathematically unified Iterative Error-Sate Kalman Filter with an adaptive hierarchical prediction strategy and an update step that minimizes point-to-mesh distances and visual reprojection errors. To support this, the environment is modeled using continuous multi-layered Gaussian Process (GP) sub-meshes, which enables efficient ray-to-mesh depth recovery for visual features. For global consistency, we introduce an Extended Scan Context (ESC) descriptor derived from the GP sub-meshes alongside a Bidirectional PnP optimization for robust multi-modal loop closure within a hybrid pose graph. Extensive evaluations on public datasets and real-world experiments demonstrate that LXD-SLAM matches or exceeds state-of-the-art specialized odometry solutions across various configurations while generating high-fidelity, globally consistent dense meshes in real-time. The relevant codes and data will be made available at this https URL upon publication.
### Title:
          OrthoTryOn: Geometric Orthogonalization for Conflict-Free Unified Fashion Generation
 - **Authors:** Zhaotong Yang, Ying Tai, Jiahui Zhan, Yu Zheng, Jianjun Qian, Jian Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unified fashion generation integrates tasks like virtual try-on and garment reconstruction into a single model to reduce task-specific adaptation costs. However, naive parameter sharing across semantically distinct tasks induces negative transfer through severe inter-task gradient conflict. We propose OrthoTryOn, a unified framework mitigating this interference within a shared Low-Rank Adaptation (LoRA) module. Its Orthogonal Subspace Projection (OSP) applies task-specific orthogonal rotations to bottleneck features, mapping them into decorrelated coordinate frames. To address residual semantic coupling at inference time, we further propose Fisher-guided Negative Guidance (FNG), a parameter-free strategy that utilizes diagonal Fisher information to quantify inter-task sensitivity overlap and explicitly repels generation trajectories from the most confusable task via Classifier-Free Guidance. Extensive experiments demonstrate that OrthoTryOn avoids the severe performance degradation typical of naive unified training and even surpasses independently trained task-specific models, achieving state-of-the-art results across multiple benchmarks while generalizing robustly across diverse diffusion backbones. Code is available at this https URL.
### Title:
          SEADA: An efficient methodology for optimizing mixed-precision DNNs on multi-precision spatial architectures
 - **Authors:** Leandro Fiorin, Marco Ronzani, Cristina Silvano
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mixed-precision computation has been introduced in deep neural networks (DNNs) as an effective approach to reduce latency, energy consumption, and memory footprint. However, efficiently mapping mixed-precision networks onto multi-precision spatial architectures poses several challenges. These include determining the appropriate precision for each layer, balancing layer-wise accuracy sensitivity to quantization against architectural heterogeneity and system-level constraints, and accurately estimating the system-level cost of heterogeneous precision assignments. This work presents SEADA, an efficient methodology designed to address these challenges. SEADA comprises: (i) a configurable system-level analytical cost model of a multi-precision spatial accelerator architecture; (ii) a fast mapping tool that identifies near-optimal mappings of DNN workloads onto the target integer accelerator; (iii) analytical models for floating-point layers to estimate the overall benefits of mixed-precision execution; and (iv) a per-layer precision selection methodology based on bit-level entropy, enabling efficient assignment across multiple numerical precisions. SEADA's efficiency provides designers with a robust framework for the design-space exploration of multi-precision architectures.
### Title:
          Phase Matters: Characterizing Heterogeneous Vision-Language Inference on a Mobile SoC
 - **Authors:** Aryama V Murthy, Yashas N Kotre, Prathmesh Sharma, Pragya Mishra, Sanjith Ganapathi, Priyesh Shukla
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent phone-class mobile SoCs expose practical NPU execution paths for on-device vision-language model (VLM) inference, but developers still lack phase-level guidance for mapping VLM pipelines across heterogeneous backends. We present a hardware-in-the-loop characterization of VLM inference on the Qualcomm SM8750 (Snapdragon 8 Elite), covering phase throughput, cache-state effects, 100-run thermal stability, energy, heterogeneous CPU/NPU pipeline configurations, and visual-token-budget sensitivity. Using FastVLM-0.5B as an end-to-end case study, together with encoder-only measurements across four architecture families, we show that phase matters: NPU execution is highly phase-dependent, delivering 1.64x speedup for prefill but only 1.18x for decode, while vision encoders achieve 20-45x speedups over CPU. These gains translate into 10.47 degrees C lower steady-state temperature and 2.52x lower energy, avoiding thermal throttling in always-on settings. Finally, we show that a four-step graph rewrite enables previously unsupported encoders, such as Phi-3.5-V, to reach the QNN path with up to 22x speedup, providing a practical porting recipe for mobile VLM deployment.
### Title:
          TA-SparseMG: Trend-Aware Sparse Forecasting via Multi-Scale Gating for Long-Term Time Series
 - **Authors:** Wenchao Liu, Hongbing Wang, Youji Zhu, Xiaodong Liu, Xiangguang Xiong
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-term time series forecasting finds extensive applications in domains such as power demand, traffic flow, meteorological observation, and renewable energy dispatch. Forecasting dynamically varying long-term time series poses inherent challenges, including statistical nonstationarity, local high-frequency disturbances, and coupled cross-period dependencies, which make it difficult for lightweight models to balance parameter efficiency and forecasting performance. To address this issue, this study presents TA-SparseMG, a lightweight cross-period forecasting model built on SparseTSF's sparse cross-period modeling framework. It incorporates three key modules: a trend-aware reversible instance normalization module, a scale-adaptive gated denoising module, and a multiscale gated-attention MLP forecasting module. The trend-aware normalization module captures input-window statistics and calibrates forecast-window distributions, effectively mitigating distribution shift. The scale-adaptive gated denoising module performs feature smoothing and residual suppression before period rearrangement, thereby reducing interference from high-frequency perturbations. The multiscale gated attention prediction module strengthens the prediction head's adaptive representational capacity via conditional gating and feature modulation. Extensive experiments across multiple LTSF benchmarks demonstrate that the proposed TA-SparseMG consistently achieves superior, stable performance. Ablation studies confirm that each module independently improves distribution adaptation, input robustness, and cross-period feature mapping capability.
### Title:
          SHARD: cell-keyed residual splitting for alignment-resistant private dense retrieval
 - **Authors:** Sergey Kurilenko
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense embeddings underpin semantic search and RAG, yet a leaked vector store hands much of the underlying text back to whoever holds it. The attacks that make this possible (few-shot alignment, zero-shot inversion, unsupervised cross-space translation) share one weakness: the protected store is a single global geometry that can be aligned to a known one. A secret global rotation, the usual lightweight defence, is no exception: orthogonal Procrustes recovers it once the attacker has about the subspace dimension in known pairs. We introduce Shard, a retrieval-preserving embedding transform that removes this weak axis. The centred embedding is split into a short public prefix (for stage-1 retrieval) and a private residual sharded into C cells under separate secret keys; the residual is reranked under CKKS, where the keys cancel and leave the inner product exact. A single parameter C runs the design from the global-linear baseline it replaces (C=1) to per-document micro-keys (C=N). Because the rerank is full-dimensional, Shard returns the raw-space nDCG@10 that half-SVD truncation gives up; and because the residual is keyed cell-locally, mapping it back to a common frame under a diffuse known-plaintext leak costs roughly C times more anchors (median 200 to 102,400 at C=256), for a few encrypted queries. The short public prefix leaks far less neighbour structure, and a micro-key limit drives the residual graph to zero with an unlinkable, renewable template. The barrier holds against learned, non-linear and unsupervised aligners, and where a matched-utility noise defence de-anonymises almost every probe, Shard de-anonymises none. We are plain about the limits: within a cell the keys cancel, a targeted attacker needs only about d_priv anchors, and an overlapping reference corpus still leaks through the prefix. Shard is an attack-aware geometric defence, not a cryptographic guarantee.
### Title:
          ToxiREX: A Dataset on Toxic REasoning in ConteXt
 - **Authors:** Stefan F. Schouten, Ilia Markov, Piek Vossen
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a new, contextual, multilingual dataset called ToxiREX: Toxic REasoning in ConteXt. The dataset consists of threads of Reddit comments and structured characterizations of what the comments imply, following a systematic toxic reasoning schema developed in a previous paper. Using the schema allows us to capture and explain implicit and context-dependent toxicity, while supporting mappings to existing toxicity taxonomies. The dataset includes comments in six languages (English, Arabic, Turkish, Spanish, German, and Dutch), collected from posts connected to specific major events (e.g. the 2023 Turkey earthquakes; the Russian invasion of Ukraine). We describe the context-preserving preprocessing of the threads. We create a training set of 125 thousand comments which is annotated by a commercially available LLM, and a test set of just under three thousand comments that is annotated by native speakers. We show that apparent disagreements in the test set annotations often reflect defensible alternative interpretations rather than noise. Finally, we provide baseline results by prompting and fine-tuning language models. To produce these results, we develop evaluation strategies for our hierarchical, schema-based predictions. While models perform better than random, there remains a lot of room for improvement, showing the task to be challenging. ToxiREX is the first dataset to simultaneously incorporate multiple languages, conversational context, and implicit toxicity, while using the toxic reasoning schema for rich, structured annotations. Dataset available at: this https URL
### Title:
          Ontology-Guided Evidence Path Inference for Multi-hop Knowledge Graph Question Answering
 - **Authors:** Yongxue Shan, Meihan Wu, Cundi Fang, Jie Peng, Xiaodong Wang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Knowledge graph question answering (KGQA) aims to answer natural-language questions by reasoning over structured facts. Existing multi-hop KGQA methods mainly rely on topic-centered expansion, which faces two key challenges: the search space rapidly grows with noisy mixed-type paths, and retrieved paths may fail to satisfy the semantic constraints of complex questions. To address these challenges, we propose OPI, an ontology-guided evidence path inference framework for multi-hop KGQA. OPI introduces a relation-centric ontology graph to capture the head-tail type constraints of relations, providing a compact interface for answer-side constraints. Based on this ontology graph, OPI first introduces a bidirectional retrieval mechanism by mapping the predicted answer type to compatible final-hop relations and combining topic-side prefix expansion with answer-side final-hop matching, thereby suppressing noisy mixed-type expansion. OPI further adopts an iterative refinement strategy to reassess retrieved paths and candidate answers under the question context, filtering type-compatible but question-irrelevant evidence for more reliable answer prediction. Experiments on WebQSP, CWQ, and MetaQA show that OPI substantially reduces the search space, improves Hit@1/F1 by 4.6/5.0 points on WebQSP and 8.9/3.3 points on CWQ over the strongest prior results, and achieves near-saturated Hit@1 on MetaQA with the retrieval module alone.
### Title:
          AB-Sync: Attention-Based Slot-Level Clock Synchronization Method for UWB-TDOA Localization Networks
 - **Authors:** Tianyi Lyu, Kefei Tian, Kangqiao Qin, Qingwen Liu, Mingqing Liu
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ultra-wideband (UWB) time-difference-of-arrival (TDOA) localization networks provide high-update-rate indoor location services for IoT and cyber-physical applications, but their accuracy depends on nanosecond-level clock synchronization among anchors. Existing wireless clock synchronization (WCS) methods typically estimate clock states at the synchronization-stage or interval level, whereas TDMA-based UWB-TDOA systems localize tags from blinks transmitted in discrete short slots inside each synchronization stage. We identify this granularity mismatch as a source of residual TDOA error and present AB-Sync, an attention-based slot-level clock synchronization method. AB-Sync models the relationship between the slot-specific clock-speed ratio required by a target tag blink and neighboring clock-fluctuation observations, thereby enabling tag-slot-level timestamp mapping without adding extra UWB synchronization messages. On a real UWB-TDOA testbed, AB-Sync reduces the multi-anchor average TDOA ranging STD.V by 9.4% and improves representative static localization accuracy by 18.6% compared with Deferred+3S-KF, the leading low-overhead baseline in our evaluation. In a five-slot multi-tag experiment, AB-Sync consistently improves localization stability across all TDMA slots, reducing STD.V by 5.3% on average and up to 16.2% per slot with no extra UWB synchronization overhead.
### Title:
          Higher-Order Fourier Neural Operator: Explicit Mode Mixer for Nonlinear PDEs
 - **Authors:** Alex Colagrande, Paul Caillon, Eva Feillet, Alexandre Allauzen
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators provide deep neural networks for learning mappings between function spaces. Among them, the Fourier Neural Operator (FNO) is particularly effective: its spectral convolution relies on low-dimensional Fourier-domain representations and can handle inputs at different resolutions. This design aligns well with settings where the Fourier basis diagonalizes the underlying operator, such as linear, constant-coefficient PDEs on periodic domains, in which Fourier modes evolve independently. However, nonlinear PDEs may benefit from an additional inductive bias, as they exhibit structured interactions between modes, governed by polynomial nonlinearities. To capture this inductive bias, we introduce the Higher-Order Spectral Convolution, a spectral mixer that extends FNO from diagonal modulation to explicit n-linear mode mixing, aligned with the dynamics of nonlinear PDEs. Our experiments on standard benchmarks show that the proposed Higher-Order FNO (HO-FNO) retains the efficiency of FNO-based architectures and consistently improves over other spectral neural operators. HO-FNO also performs on par with or better than state-of-the-art transformers and state-space models on several datasets, with stronger gains in highly nonlinear regimes, such as the Poisson equation with polynomial forcing, where a single HO-FNO layer outperforms FNO models with up to 16 layers. We open-source our code for reproducibility at: this https URL.
## Keyword: localization
### Title:
          SemCityLoc: Aerial 6DoF Localization Using Semantic 3D City Models
 - **Authors:** Jingfeng Mao, Xuyang Chen, Qilin Zhang, Oussema Dhaouadi, Guangming Wang, Brian Sheil, Daniel Cremers, Yan Xia, Olaf Wysocki
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Aerial 6DoF localization typically relies on precise GNSS signals or radiometrically rich 3D reconstructions, limiting scalability and on-board deployment. We propose SemCityLoc, a semantic-geometric alignment system that reframes aerial pose estimation as structured surface registration between foundation-model-derived visual priors and standardized LoD-compliant 3D city models. Instead of matching sparse contours or dense texture, our method aligns semantic surfaces and monocular depth with lightweight semantic 3D building models, increasing pose discriminability in repetitive and occluded urban environments. To enable accurate evaluation, we introduce SemCityLockeD, the first real-world benchmark combining centimeter-accurate UAV poses with standardized LoD1--LoD3 semantic city models and challenging low-altitude imagery. Experiments demonstrate substantial improvements over existing map-based approaches, improving recall by up to 36% and reducing mean positional error from 9.89m to 2.62m in challenging urban canyons. Our results indicate that semantically structured geometry provides sufficient and scalable constraints for high-precision aerial localization without radiometric scene reconstructions. The code and data are available at this https URL.
### Title:
          TruEye: Fine-Grained Detection of AI-Generated Human Subjects in Images
 - **Authors:** Jay Barot, Dan Lin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI generated images are proliferating across the Internet. While some are used for entertainment, others are weaponized for fraud and social engineering attacks on social media users. Existing detectors overfit to generators seen during training, treat detection as opaque binary classification, or rely on costly Large Language Models (LLMs) to explain their outputs. In this paper, we present TruEye, a novel model for fine grained detection and localization of AI manipulated or AI generated humans and scenes. Unlike conventional detectors that assign a single authenticity label, TruEye is the first to distinguish among five compositional categories of synthetic content, including the most challenging case in which a real human is composited into a real scene where they were never physically present. At its core is a mask conditioned dual stream transformer that separates human and scene tokens while preserving patch level spatial correspondence. Specialized reasoning within each stream and region gated cross attention enforce semantic coherence between subject and background, while token level supervision and global compositional classification yield robust, interpretable predictions without invoking an LLM. By restricting intra stream attention to semantically coherent tokens, TruEye also runs over $100\times$ faster than LLM based competitors. Experiments on 6 datasets and our newly curated FineSyn dataset, show that TruEye surpasses state of the art detectors with higher accuracy, faster inference, and stronger generalization to unseen AI generated or manipulated images.
### Title:
          Physics-Guided Robotic Radiation Source Localization along Arbitrary Measurement Paths in Unstructured Environments
 - **Authors:** Hojoon Son, Kai Tan, Fan Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Using robots to estimate the location of the radiation source is an effective way to improve efficiency and safety. Existing methods focus on planning the robot's path to achieve precise estimation, typically approaching the source. However, approaching the source increases the risk of radiation damage to a robot. In addition, a path-planning algorithm designed solely for radiation source localization (RSL) limits the flexibility of missions that deploy robots into radioactive environments. This study presents an automation framework for robotic RSL that leverages a physics-informed machine learning (PIML) model to precisely estimate the source location, regardless of measurement paths, in unknown environments. Physics-inspired model tensors have been designed for PIML to handle attenuated gamma-ray flux signals from unknown obstacles, and multiple models are computed in parallel to improve the robustness and precision of the RSL. The proposed method is evaluated in high-fidelity simulation environments using Monte Carlo particle transport across diverse randomized domains, including spatial scales, radiation source types, obstacle materials and geometries, and robot trajectories. The method is also validated through physical experiments on configurations that are not included in the simulation-based evaluation. The continuous learning technique is applied in real-robot deployment to enhance the practical applicability of the online robotic RSL system. The proposed method advances robot radiation perception from pointwise flux detection to spatial intelligence.
### Title:
          Direct Action-Head Injection of A Grounded 3D Point Unlocks Spatial and Task Generalization
 - **Authors:** Shiang-Feng Tsai, Jin-Cheng Jhang, Yen-Ling Tai, Jia-Hong Lai, Shih-Yun Wong, KangTung-Hsu, Yi-Ting Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models leverage large-scale vision-language pretraining for flexible robot manipulation, yet at test time they remain brittle along two axes: spatial generalization, when object positions differ from those seen during training, and task generalization, when a familiar scene is paired with a different language instruction than the one seen in training. A growing family of methods addresses this brittleness by endowing a policy with the spatial and task-aware information such as 2D pixel-coordinate for object localization and placement. However, we find that existing representation through language prompting or visual prompting does not address the limitations; in contrast, exploiting a 3D point-based representation and feeding it directly to the action head leads to substantial improvements-revealing that how the grounding signal is represented and injected into the VLA is the true game changer. Thus, we propose a lightweight, model-agnostic module that represents the grounding signal in 3D, computes its relative displacement to the gripper, and injects the resulting spatial embedding directly into the action head through adaptive layer normalization. The entire module is a two-layer MLP that requires no changes to the VLA backbone or pretraining pipeline. On LIBERO-PRO, our method improves the average success rate of GR00T-N1.6 from 31.2 to 77.5 points under task perturbation and from 28.1 to 60.2 points under position perturbation (gains of 46.3 and 32.1 points). Comparable gains are achieved for $\pi_{0.5}$ as well, demonstrating that the mechanism is backbone-agnostic. Together, these results support our central finding: given adequate grounding lifted into 3D, injecting it directly into the action head is what unlocks both spatial and task generalization in VLAs-achievable with nothing more than a lightweight module on top of a pretrained backbone.
### Title:
          Scene and Human in One World: Reconstruction in a Feedforward Pass
 - **Authors:** Boao Shi, Qiao Feng, Yiming Huang, Lingjie Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing humans in dynamic scenes from moving monocular cameras remains challenging due to scale ambiguity, human-scene misalignment, and occlusion interference. Rather than treating human mesh recovery and scene reconstruction as separate tasks, we believe that accurate human-scene reconstruction requires the two tasks to mutually inform each other: parametric human models offer semantic structure and metric-scale priors, while scene geometry provides spatial context for human localization and alignment. Built on this insight, we introduce SHOW, a mask-promptable human mesh recovery framework that couples feed-forward 3D scene reconstruction with Human Mesh Recovery in a unified metric space. SHOW injects human semantics and scale priors from parametric human models into normalized point-map prediction, enabling metric-scale scene reconstruction from inherently scale-ambiguous monocular input. In turn, the recovered scene geometry constrains human mesh estimation, encouraging spatially consistent human placement and improved human-scene alignment. To handle complex multi-person and cluttered scenes, SHOW further incorporates a promptable masking mechanism that enables flexible target-human selection while suppressing background distractions and occlusion interference. Through joint training, the model learns both human-aware geometric features and geometry-constrained human features, producing aligned metric-scale reconstructions from monocular human-centric videos. Extensive experiments demonstrate that SHOW improves metric-scale consistency, human-scene alignment, and reconstruction accuracy under challenging camera motion, occlusion, and cluttered backgrounds.
### Title:
          Learning 1-Bit LiDAR-based Localization with Auxiliary Objective
 - **Authors:** Kaijie Yin, Zhiyuan Zhang, Tian Gao, Wentao Zhu, Cheng-zhong Xu, Hui Kong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 6-DoF LiDAR-based localization is a fundamental capability for autonomous systems operating in large-scale outdoor environments. Many deep-learning-based localization methods have achieved promising performance so far. However, as one of the always-on modules competing for limited on-board computational resources, the localization module is expected to consume only a small portion of the overall compute budget. Most existing learning-based methods are still too heavy for this purpose. In contrast, binary neural networks (BNNs) offer an appealing solution, but the 1-bit compression causes severe information loss and performance drop. In this paper, we address this challenge by proposing Binarized LiDAR-based Localization (BiLoc), the first binary neural network framework for 6-DoF LiDAR localization. Specifically, we reinterpret the training of BNNs from the perspective of the information-bottleneck principle, aiming at retaining minimal yet sufficient representations for pose estimation while suppressing redundant variations. And we introduce an auxiliary objective that adaptively regulates information retention in the binary encoder, effectively mitigating the information loss caused by binarization. This auxiliary objective provides additional optimization signals that compensate for the limited representational capacity and the gradient mismatch inherent in BNNs. Extensive experiments on large-scale outdoor LiDAR datasets demonstrate that BiLoc establishes a new state of the art for LiDAR localization with BNNs.
### Title:
          From General-Purpose Audio Tagging to Spatially Grounded Sound Event Localization and Detection
 - **Authors:** Stefano Giacomelli, Stefano Damiano, Claudia Rinaldi, Fabio Graziosi, Toon van Waterschoot
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This report investigates the extension of pretrained General-Purpose Audio Tagging (GP-AT) models toward spatially grounded Sound Event Localization and Detection (SELD). The proposed AT2SELD framework couples a pretrained AT backbone with compact First-Order Ambisonics (FOA) spatial processing, track-wise SED and Cartesian DOA estimation, permutation aware supervision, and calibration. It characterizes how semantic audio priors support localization-aware scene analysis under data, computation, and deployment constraints. The framework is developed through informed multi-stage Neural Architecture Search (NAS). Stage 1 shows that spectral FOA descriptors, based on magnitude, phase, and Intensity Vectors (IVs), provide the most reliable interface for semantic-to-spatial transfer. Stage 2 identifies early residual spatial encoding as the main capacity-sensitive component, while late track-wise abstraction and recurrent smoothing act mainly as refinement stages. Stage 3 shows that late cross-stitch coupling improves semantic-spatial interaction, whereas early fusion is costlier and less effective. Diagnostic evaluation analyzes the selected architecture under class balancing, focal loss, activity-conditioned DOA supervision, threshold calibration, and transfer across STARSS23, TAU2019, TAU-NIGENS2020, and TAU-NIGENS2021. Focal loss improves the activity point, active-only DOA supervision mitigates inactive target dominance, and validation-selected thresholds recover calibration without replacing spatial learning. Cross-dataset and oracle-activity analyses indicate strong fixed source localization on TAU2019, transferable representations from TAU NIGENS2021, and meaningful but uncertain behavior on STARSS23. Overall, GP-AT priors appear promising for SELD design when embedded in spatial-aware architectures and optimized through integrated calibration and deployment oriented strategies.
### Title:
          LXD-SLAM: LiDAR+X Dense SLAM with $\sum_{i=0}^{5}C_5^i$ Configurable Sensor Combinations
 - **Authors:** Zhong Wang, Lin Zhang, Linfei Li, Ying Shen, Shaoming Zhang, Pengcheng Shi, Shengjie Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simultaneous Localization and Mapping (SLAM) is essential for autonomous systems, yet achieving reliable, globally consistent pose estimation and dense mapping in complex environments remains challenging due to geometric degeneracy and sensor drift. While multi-sensor fusion addresses these issues, existing systems often lack the modularity to adapt to diverse platforms and rely on mathematically inconsistent fusion or suboptimal map representations. To address these limitations, we propose LXD-SLAM (LiDAR+X Dense SLAM), a highly versatile and unified multi-sensor fusion framework. Centered around 3D LiDAR, our system allows for the plug-and-play integration of LiDAR, Camera, IMU, Wheel Encoder, and GNSS, supporting up to 32 distinct sensor combinations. We employ a mathematically unified Iterative Error-Sate Kalman Filter with an adaptive hierarchical prediction strategy and an update step that minimizes point-to-mesh distances and visual reprojection errors. To support this, the environment is modeled using continuous multi-layered Gaussian Process (GP) sub-meshes, which enables efficient ray-to-mesh depth recovery for visual features. For global consistency, we introduce an Extended Scan Context (ESC) descriptor derived from the GP sub-meshes alongside a Bidirectional PnP optimization for robust multi-modal loop closure within a hybrid pose graph. Extensive evaluations on public datasets and real-world experiments demonstrate that LXD-SLAM matches or exceeds state-of-the-art specialized odometry solutions across various configurations while generating high-fidelity, globally consistent dense meshes in real-time. The relevant codes and data will be made available at this https URL upon publication.
### Title:
          AB-Sync: Attention-Based Slot-Level Clock Synchronization Method for UWB-TDOA Localization Networks
 - **Authors:** Tianyi Lyu, Kefei Tian, Kangqiao Qin, Qingwen Liu, Mingqing Liu
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ultra-wideband (UWB) time-difference-of-arrival (TDOA) localization networks provide high-update-rate indoor location services for IoT and cyber-physical applications, but their accuracy depends on nanosecond-level clock synchronization among anchors. Existing wireless clock synchronization (WCS) methods typically estimate clock states at the synchronization-stage or interval level, whereas TDMA-based UWB-TDOA systems localize tags from blinks transmitted in discrete short slots inside each synchronization stage. We identify this granularity mismatch as a source of residual TDOA error and present AB-Sync, an attention-based slot-level clock synchronization method. AB-Sync models the relationship between the slot-specific clock-speed ratio required by a target tag blink and neighboring clock-fluctuation observations, thereby enabling tag-slot-level timestamp mapping without adding extra UWB synchronization messages. On a real UWB-TDOA testbed, AB-Sync reduces the multi-anchor average TDOA ranging STD.V by 9.4% and improves representative static localization accuracy by 18.6% compared with Deferred+3S-KF, the leading low-overhead baseline in our evaluation. In a five-slot multi-tag experiment, AB-Sync consistently improves localization stability across all TDMA slots, reducing STD.V by 5.3% on average and up to 16.2% per slot with no extra UWB synchronization overhead.
## Keyword: transformer
### Title:
          PairSAE: Mechanistic Interpretability from Pair Representations in Protein Co-Folding
 - **Authors:** Giosue Migliorini, Aristofanis Rontogiannis, Grigori Guitchounts, Nicholas Franklin, Axel Elaldi, Olivia Viessmann
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation models for structural biology have achieved remarkable performance in predicting biomolecular structure and show promise for the design of proteins and small molecules. Yet understanding which internal features drive their outputs remains challenging. Standard sparse autoencoders (SAEs), effective on transformer-style sequence embeddings, do not transfer cleanly to pairformer-like architectures: naively operating on pairwise representations yields a quadratic blow-up of features and obscures concepts distributed jointly across sequence and pair representations. We introduce PairSAE, which summarizes pairwise tensors via an N-mode SVD into token-wise interaction roles, then uses a sparse autoencoder to learn a shared set of token-level features that decode into both sequence and pair representations. Evaluated on Boltz-2 activations for PLINDER protein-ligand complexes, PairSAE yields interpretable features that align with UniProt annotations and predict Boltz-2 affinity values. These results indicate that PairSAE links the latent space of foundation models for structural biology to interpretable structural concepts, clarifying what the model "knows" while avoiding pairformer-induced pitfalls that limit conventional SAEs.
### Title:
          Prism Transformer: Progressive Head Schedules for Hierarchical Attention Processing
 - **Authors:** Shubham Aggarwal
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-head attention conventionally partitions the hidden dimension equally across all heads at every layer, enforcing an identical representational subspace dimension (dh = dmodel/h) throughout the models depth. In this work, we identify this uniform allocation as a fundamental structural bottleneck: due to their restricted dimensional space, early-layer heads are unable to faithfully capture complex, high-dimensional contextual patterns. To resolve this, we introduce the Prism Transformer, a novel architectural paradigm that replaces the static, uniform head configuration with a progressive head schedule. By monotonically increasing the head count across layers, the Prism Transformer naturally establishes a local-to-global representational hierarchy: early layers leverage fewer, exceptionally wide heads to capture complex, local compositional patterns, while deep layers deploy many, narrow heads to decompose these patterns into specialized linguistic features. Crucially, this structural shift is parameter-neutral, compute-neutral, and introduces zero training or inference overhead, preserving identical weight matrices and FLOP budgets as the standard Transformer. Across three model scales (124M, 354M, and 757M), the Prism Transformer consistently outperforms uniform baselines, achieving consistent reductions in validation loss alongside consistent gains on downstream zero-shot benchmarks (including PIQA, HellaSwag, ARC-Easy, and WinoGrande). Our findings demonstrate that non-uniform subspace allocation unlocks latent capacity within the standard Transformer budget, enabling more effective use of model capacity.
### Title:
          Developmental approach reveals the statistical learning of Neural Language Models: Transformers generalize from the most abstract statistical patterns
 - **Authors:** Wang Bojun, Holly Jenkins, Elizabeth Wonnacott
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this study, we use a developmental approach to investigate the statistical learning and mental representation of neural language models (NLM). A series of Generative Transformer models are trained on a synthetic grammar. The model states are saved at multiple stages in the course of training. Through analyzing how the internal representations of these models change in the developmental path, we found that NLMs acquire the most abstract global statistical knowledge at the beginning of learning and later acquire the relatively local statistical dependencies. This learning path contains many over-generalizations from the very beginning and these over-generalizations are gradually constrained in the later stage of learning. Based on this observation, we propose a new framework to explain the statistical learning and language cognition of NLMs.
### Title:
          TruEye: Fine-Grained Detection of AI-Generated Human Subjects in Images
 - **Authors:** Jay Barot, Dan Lin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI generated images are proliferating across the Internet. While some are used for entertainment, others are weaponized for fraud and social engineering attacks on social media users. Existing detectors overfit to generators seen during training, treat detection as opaque binary classification, or rely on costly Large Language Models (LLMs) to explain their outputs. In this paper, we present TruEye, a novel model for fine grained detection and localization of AI manipulated or AI generated humans and scenes. Unlike conventional detectors that assign a single authenticity label, TruEye is the first to distinguish among five compositional categories of synthetic content, including the most challenging case in which a real human is composited into a real scene where they were never physically present. At its core is a mask conditioned dual stream transformer that separates human and scene tokens while preserving patch level spatial correspondence. Specialized reasoning within each stream and region gated cross attention enforce semantic coherence between subject and background, while token level supervision and global compositional classification yield robust, interpretable predictions without invoking an LLM. By restricting intra stream attention to semantically coherent tokens, TruEye also runs over $100\times$ faster than LLM based competitors. Experiments on 6 datasets and our newly curated FineSyn dataset, show that TruEye surpasses state of the art detectors with higher accuracy, faster inference, and stronger generalization to unseen AI generated or manipulated images.
### Title:
          The Context-Ready Transformer
 - **Authors:** Mahesh Godavarti
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce the context-ready transformer, a new recurrent neural network architecture built from a D-layer transformer block that pre-contextualizes each token before it enters the block. During left-to-right generation, a correction network combines the previous position's block output -- a cached summary of past context -- with the current token embedding, so the tokenenters the block already contextualized rather than as a raw embedding. At sequential inference, the correction chain makes the architecture a recurrent neural network. For training, we unroll the correction process K times over the full sequence, processing all positions in parallel at each step. A pretrained transformer can also be converted to a context-ready model by adding a zero-initialized correction FFN and fine-tuning. We evaluate across widths, depths, block sizes, and two datasets, with all comparisons against standard transformers, variants, and ablations. A D=5 model beats a 12-layer transformer while generating 1.7x faster on an A100. With K=10, a single-layermodel (D=1) beats a 6-layer transformer with a 2.6x inference speedup, and sequential inference matches parallel K=10 to within 0.01 PPL. The architecture benefits most from wide representations and long contexts. On a pointer-chasing task, D=1 trained with BPTT solves all 10 composition levels, while standard transformers exhibit staircase-like depth dependence.
### Title:
          Quantum Generative Diffusion Model for Real-World Time Series
 - **Authors:** Jack Waller, Filippo Caruso, Dimitrios Makris, Rajagopal Nilavalan, Xing Liang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Quantum Physics (quant-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative models have achieved remarkable success in data synthesis, though recent advances driven by increasing model scale have introduced challenges in computational cost and efficiency. Quantum machine learning offers a promising alternative, representing complex data distributions using compact, highly expressive models. Here, we propose QDiffusion-TS, the first quantum generative diffusion model for time series synthesis, and validate it on the IQM quantum processor. The framework extends a classical diffusion architecture by replacing feed-forward components within the denoising transformer with quantum neural networks, yielding a hybrid quantum transformer that reduces the number of trainable parameters in each replaced component by nearly three orders of magnitude. Evaluated on financial time series from Apple and Amazon, the model generates synthetic data that more accurately reproduces the real distributions, reducing Wasserstein distance by approximately 44% relative to its classical counterpart across both datasets. In a downstream forecasting task, augmentation with the generated data improves predictive performance by up to 71% in RMSE over a baseline trained solely on real data. These results show that quantum enhanced architectures can consistently match and frequently surpass classical performance with substantially fewer parameters, establishing a practical framework towards more efficient and scalable data-driven generative modelling.
### Title:
          Odyssey: Constructing Verifiable Local Truth-Preserving Foundation Models
 - **Authors:** Sridhar Mahadevan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a categorical framework called ODYSSEY for constructing verifiable, local truth-preserving foundation models as compositions of foundries: building-block architectural components that specify a cover of local contexts, local representation families, restriction maps, gluing rules, obstruction policies, update obligations, and human-facing views. A foundry is an organized sheaf of knowledge that carries within it an argumentation component. Concrete foundries are built from generic foundries such as evidence/argument, operational decision, institutional/financial, market meaning, scientific challenge, research-program, assistant-build, and evaluation-harness foundries. Universal Foundry Learning (UFL) formalizes foundry construction as a composition of left and right Kan extensions, with left Kan extension rolling local artifacts into candidate foundries and right Kan extension enforcing the restriction, gluing, obstruction, and argumentation conditions required for promotion. Foundry SQL (FSQL) is a small typed query surface for slicing maintained foundry artifacts that uses TICKET (Topos Integration using Causal Kan Extension Transformers) certification for admitting external or pre-built models into durable ODYSSEY state. ODYSSEY is fully implemented and tested across a wide spectrum of concrete foundries, showing that the same categorical machinery supports domain construction, artifact replay, sheaf diagnostics, grounded Toulmin/local-LLM scrutiny, residual-obstruction ledgers, and optimized TICKET-compatible causal-claim extraction across heterogeneous sources. This paper is to be presented as a 2.5 hour tutorial at ICML 2026. The tutorial home page is at this https URL.
### Title:
          HybridCodec: Modeling Discrete and Continuous Representations for Efficient Speech Language Models
 - **Authors:** Artem Ploujnikov, Francesco Verdini, Samir Sadok, Mirco Ravanelli
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Discrete audio representations have become increasingly popular for building multimodal text-audio systems and integrating audio capabilities into Large Language Models (LLMs). However, numerous studies report performance degradation on various downstream tasks due to information loss during discretization. To address this, we propose a novel approach combining temporally compressed discrete tokens with dimensionality-reduced continuous residuals. Our framework consists of a hybridized discrete-continuous focal modulation codec and a hybrid Transformer. This architecture performs autoregressive inference in the discrete domain, coupled with non-autoregressive prediction and continuous residual upsampling. Experimental results show that our approach significantly improves the retention of speaker characteristics compared to discrete-only methods, while simultaneously reducing the number of required autoregressive steps.
### Title:
          CryptoGAT: Are Time Series Models Effective for Cryptocurrency Forecasting?
 - **Authors:** Yu Peng, Matloob Khushi, Josiah Poon
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE); Statistical Finance (q-fin.ST)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cryptocurrency price prediction is a significant challenge in quantitative investment. In recent years, time series models have made significant progress in financial forecasting tasks, especially in the stock market. Despite the growing performance over the past few years, we question the validity of this line of research in cryptocurrency prediction. Specifically, time series models (e.g., LSTM, GRU, and Transformers) are effective at extracting temporal relationships in stock market data. However, in pure price-based cryptocurrency prediction, facing data with extreme volatility and wild swings, time series models have difficulty learning effective information. To validate our claim, we propose CryptoGAT, a lightweight Graph Attention Network that recasts cryptocurrency pure price prediction as a cross-asset graph problem rather than a temporal modeling task. Extensive experiments on real cryptocurrency benchmarks demonstrate that our proposed CryptoGAT outperforms various state-of-the-art forecasting methods with a notable margin. Moreover, we conduct comprehensive empirical studies to explore the fundamental differences exposed by time series models in stock and cryptocurrency prediction: differences in predictability of the signal and cross-asset dependencies. This finding opens up new research directions for the cryptocurrency pure price prediction task and inspires further graph-based exploration in the field. The source code is available at this https URL
### Title:
          Multi-Modal Conditioned High-Resolution Transformer for Urban Electromagnetic Field Map Prediction Download PDF
 - **Authors:** Do-Eon Kim, Dongryul Park, Seungyoung Ahn, Namwoo Kang, Seong-heum Kim, Seongsin Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting electromagnetic field (EMF) strength in urban environments is essential for cellular network planning but computationally expensive with physics-based simulators. We propose a multi-conditioned dense prediction framework that generates 500 500 EMF maps from building layout images and antenna configurations. Our architecture uses a High-Resolution Transformer (HRFormer) backbone with two complementary conditioning mechanisms: Feature-wise Linear Modulation (FiLM) injects scalar antenna parameters into all backbone stages, while cross-attention fuses 1-D radiation pattern tokens with spatial features at the deepest stage. We further introduce transmitter-relative spatial channels encoding distance, proximity, and bearing from the antenna, enabling coordinate-consistent test-time augmentation (TTA) that reduces test MAE by 6.3%. To address the prediction difficulty imbalance across EMF maps, we design a composite loss combining masked L1, multi-scale structural similarity (MS-SSIM), and a focal L1 term that upweights high-signal pixels, outperforming individual loss components in all metrics. Our best model achieves a test MAE of 0.0461, a 25.2% improvement over a plain UNet baseline and 31.8% over an HRFormer-only this http URL-
### Title:
          Flexformer: Flexible Linear Transformer with Learnable Attention Kernel
 - **Authors:** Haoran Zhang, Feng Zhou
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer models rely on attention mechanism to capture long-range dependencies but suffer from quadratic complexity, limiting their scalability to long sequences. Kernel-based linear attention reduces this complexity but typically relies on fixed or weakly learnable kernels, restricting expressiveness and performance. In this work, we propose Flexformer, a flexible linear Transformer that learns attention kernels in a fully data-driven manner. Flexformer builds on random Fourier feature-based linear attention and treats spectral frequencies as trainable parameters, enabling the model to learn a broad family of attention kernels. We develop both stationary and nonstationary variants, with the latter offering strictly greater expressiveness. Extensive experiments on language modeling and sequence classification demonstrate that Flexformer consistently outperforms baselines. Moreover, Flexformer can be effectively distilled from pretrained Transformers to recover softmax attention and exhibits strong kernel transferability across domains, achieving both high efficiency and competitive performance on long-sequence tasks.
### Title:
          Drop-Then-Recovery: How Redundant Are Vision-Language-Action Models?
 - **Authors:** Guoheng Sun, Kaixi Feng, Shwai He, Xiaochuan Gong, Yexiao He, Ziyao Wang, Zheyu Shen, Wanghao Ye, Ramana Rao Kompella, Gaowen Liu, Ang Li
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models enable instruction-driven robotic manipulation, but they inherit oversized language backbones from pretrained VLMs whose capacity far exceeds what is needed for short robotic instructions. This raises a basic question: how much of a VLA model is actually necessary for closed-loop control? In this work, we study architectural redundancy in VLA models by using transformer block removal as a controlled intervention. We introduce \textbf{Drop-Then-Recovery (DTR)}, an analysis protocol that removes selected blocks from a pretrained VLA model and then fine-tunes the resulting model to measure whether the removed capacity was necessary for downstream control. To make this intervention reliable, we propose \textbf{GateProbe}, a one-shot virtual-gate sensitivity metric that ranks blocks by their contribution to the downstream action loss. Across multiple VLA architectures, manipulation benchmarks and even real-robot industrial scenarios, we find a strong asymmetry in post-removal recoverability: \ul{\textit{language backbones are highly redundant for standard robotic manipulation tasks, whereas vision and action pathways are substantially less tolerant to removal}}. On LIBERO, removing half of the LLM blocks even improves OpenVLA-OFT from 95.0% to 98.3% under the same downstream fine-tuning budget, and retaining only two language blocks still recovers baseline-level performance. These results suggest that current VLA benchmarks may exert limited pressure on deep language grounding and compositional instruction understanding, and that future VLA architectures should allocate capacity more deliberately across language, vision, and action components. The code is available at this https URL.
### Title:
          PixelU: A U-Shaped Transformer for Efficient End-to-End Pixel Diffusion
 - **Authors:** Zipeng Guo, Lichen Ma, Yu He, Xiaolong Fu, Jingling Fu, Junshi Huang, Yan Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end pixel-space diffusion models bypass the lossy compression of Latent Diffusion Models (LDMs) but struggle to jointly model low-frequency semantics and high-frequency signals in high-dimensional space. Existing works heavily rely on complex pixel decoders to alleviate this issue. In this paper, we challenge this trend by revealing that these decoders primarily compensate for the optimization difficulties inherent to velocity prediction ($v$-prediction). Under the clean data paradigm ($x$-prediction), they are redundant. Motivated by this insight, we advocate for simplicity over complexity and introduce PixelU, a minimalist, single-stage U-shaped Diffusion Transformer tailored for pixel space. PixelU abandons auxiliary decoders in favor of zero-cost skip connections, which provide an "information highway" that directly routes uncorrupted high-frequency spatial details from shallow to deep layers. To further enable the backbone to focus exclusively on modeling low-frequency semantics, we introduce a constant-channel spatial down-sampling mechanism as a natural low-pass filter, which compresses deep features into a compact, low-frequency semantic manifold. Extensive experiments demonstrate that this decoupling of frequencies could outperform the strong baseline (JiT-G) with only about 1/3 of its computation cost. On ImageNet 256$\times$256 and 512$\times$512, PixelU achieves FID of 1.63 and 1.92 respectively, surpassing recent pixel-space methods and establishing a simple yet powerful new paradigm for end-to-end diffusion models.
### Title:
          SpikeVLA: Vision-Language-Action Models with Spiking Neural Networks
 - **Authors:** Ruiqi Song, Dujun Nie, Siyu Teng, Baiyong Ding, Xiaotong Zhang, Dong Li, Chenming Zhang, Yuchen Li, Hangbin Wu, Long Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have become a dominant paradigm for embodied intelligence. However, most existing approaches are built on large-scale transformers, resulting in substantial inference latency and energy consumption that limit their practical deployment in low-power, real-time scenarios. We propose SpikeVLA, a spiking VLA architecture for embodied navigation with energy-efficient inference, consisting of three key components. (i) A spiking vision encoder, Spike-V, that replaces dense continuous layers with event-driven spiking layers to reduce the energy consumption of visual representation learning. (ii) A multi-modal spiking large language model, Spike-L, that reformulates cross-modal reasoning with spiking dynamics and token-level event-driven sparsity to further lower computational cost. (iii) A spiking action policy network, Spike-A employs Laplacian-kernel population coding with a multi-layer fully connected SNN, and decodes spiking activities into stable and robust continuous control with energy-efficient inference under low-power constraints. Experiments on navigation and robotic control tasks show that SpikeVLA significantly reduces energy consumption and computational cost while maintaining competitive performance, highlighting its potential for low-power, real-time embodied intelligence.
### Title:
          Scalable and Differentiable Point-Cloud Registration Using Maximum Mean Discrepancy
 - **Authors:** Rixon Crane, Fahira Afzal Maken, Nicholas Lawrance, Stanislav Funiak, Kasra Khosoussi, Ming Xu, Russell Tsuchida
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present MMD-Reg, a novel correspondence-free approach to point-cloud registration that is differentiable and has linear computational complexity in the number of points. We model registration as a nonlinear least-squares problem based on the Maximum Mean Discrepancy, approximated using random Fourier features. The resulting objective can be solved efficiently with standard methods such as Levenberg-Marquardt, and the solution is differentiable via the implicit function theorem. This allows MMD-Reg to be used as a differentiable optimization layer within end-to-end trainable models, supporting registration under challenging conditions such as poor initial alignment and partial overlap. We demonstrate this Neural MMD-Reg formulation by integrating the layer with a set transformer, training the resulting model in supervised and unsupervised settings, and comparing its performance against recent learning-based methods. We also evaluate standalone MMD-Reg, comparing its accuracy and scalability against widely used non-learning-based registration methods.
### Title:
          A Unified Framework for Vision Transformers Equivariant to Discrete Subgroups of $\mathrm{O}(2)$
 - **Authors:** T\=ıkun Ông, Georg Bökman
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision transformers have become a dominant architecture for visual recognition. However, standard models do not explicitly encode the planar symmetries that arise in many vision domains. We introduce a family of vision transformers equivariant to arbitrary discrete subgroups of $\mathrm{O}(2)$, providing a unified framework that generalizes prior flipping- and $D_4$-equivariant transformer architectures. Our construction yields equivariant analogues of the core transformer components, together with expressivity guarantees for the resulting layers. In particular, we show that whenever $H \le G$, the class of $G$-equivariant ViTs embeds naturally into the class of $H$-equivariant ViTs. We also prove that, in the single-head setting, the corresponding equivariant self-attention layer realizes every $G$-equivariant self-attention map representable by ordinary self-attention. We further construct a $D_6$-equivariant model based on hexagonal patches, making the architecture compatible with six-fold rotational symmetries. We evaluate the resulting models on the PatternNet aerial image dataset in artificially data-scarce regimes across subgroups of $D_4$ and $D_6$. Our experiments compare two equivariant attention mechanisms and analyze how the choice of homogeneous-space configurations used in the nonlinearities affects performance. Preliminary results under matched parameter budgets indicate that equivariance can improve recognition accuracy, motivating further study of how discrete symmetry groups shape transformer-based visual recognition models.
### Title:
          From Bootstrapping to Sequence Modeling: A Unified Generative Framework for Personalized Landing-Page Modeling
 - **Authors:** Fan Li, Chang Meng, Jiaqi Fu, Shuchang Liu, Tianke Zhang, Xueliang Wang, Xiaoqiang Feng, Yongqi Liu, Kaiqiao Zhan
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern online platforms increasingly adopt multi-page architectures to accommodate diverse user needs. On these platforms, page navigation (the process of directing users to specific functional pages upon app entry) serves as a critical gateway that shapes user's first impression and significantly influences subsequent engagement. To optimize this process, Kuaishou formulated the task of Personalized Landing Page Modeling (PLPM) and proposed KLAN, a reinforcement learning framework built upon Conservative Q-Learning (CQL). However, CQL-based approaches suffer from two fundamental limitations: (1) the Markov assumption fails to capture the strong non-Markovian temporal dependencies inherent in real-world user behaviors, and (2) TD learning with bootstrapping incurs severe cumulative errors and credit assignment difficulties under delayed rewards, particularly in long-horizon settings where users enter the app multiple times daily. To address these limitations, we propose GLAN (Generative Landing-page Adaptive Navigator), a sequence modeling framework built on Decision Transformer to tackle PLPM from a unified global-local perspective. Specifically, GLAN incorporates two key modules. First, we design the L-RTG module that captures users' inter-day consumption dynamics to provide accurate global guidance for all page assignments within a day. Furthermore, we propose the HRM module that decomposes session-level feedback into fine-grained signals, enabling precise local supervision for each page assignment. Extensive online experiments conducted on the Kuaishou platform demonstrate the effectiveness of GLAN, achieving +0.158\% and +0.108\% improvements on Daily Active Users (DAU) and user Lifetime (LT) respectively.
### Title:
          A Study of Temporal Fusion Strategies for Named Entity Recognition in Historical Texts
 - **Authors:** Emanuela Boros
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Temporal variation poses a unique challenge for named entity recognition (NER) in historical texts, where entities drift in surface form and salience across time. While language models (LMs) have made progress in various NLP tasks, their ability to reason about temporality, especially in diachronic contexts, remains limited or at least, questionable. In this paper, we systematically study how temporal metadata can be structurally embedded into NER models using a range of lightweight fusion strategies. We experiment with both absolute and relative temporal representations, injected into Transformer-based architectures via early or late fusion mechanisms such as cross-attention, adapters, and concatenation. Our evaluations on French and German historical datasets reveal that late fusion strategies yield more robust and temporally generalisable performance, particularly in early and noisy periods.
### Title:
          A Multi-Attribute Latent Space for Visual Analysis of Watches
 - **Authors:** Kai Lawonn, Tobias Günther, Monique Meuschke
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a design rationale, embedding model, and interactive visual-analysis system for exploring large wristwatch collections through heterogeneous visual and semantic attributes. The system addresses a common limitation of catalog and e-commerce interfaces: users can filter by metadata, but they receive little support for open-ended exploration of visual similarity, stylistic alternatives, and mixed aesthetic-functional criteria. We therefore represent watches with separate attribute graphs for dial color and dial design, while using watch type as an explicit semantic organizer. Dials are segmented with a U-Net, watch types are predicted with a Vision Transformer, colors are represented through a shared CIELAB reference palette, and dial structure is described with a gradient-based image descriptor. We extend UMAP by combining attribute-specific neighborhood graphs in a unified probabilistic objective and by adding a class-aware layout term that separates global type structure from local visual neighborhoods. The resulting map is exposed in an interactive interface with spatial navigation, metadata filtering, detail inspection, and search-by-example insertion. We evaluate the approach through parameter analysis, runtime measurements, and a qualitative pilot study with watch experts and novices. The results suggest that the system supports discovery and comparison, while also revealing limitations in scalability assessment, search-by-example validation, and the need for broader domain studies. We explicitly discuss these limitations and derive design implications for multi-attribute latent-space visualization across heterogeneous visual collections.
### Title:
          Long-Term Prediction of Local and Global Human Motion with Occlusion Recovery
 - **Authors:** Qiaoyue Yang, Sven Heutger, Christopher Niemann, Magnus Jung, Ayoub Al-Hamadi, Sven Wachsmuth
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human motion describes the three-dimensional full-body movement of a person. Anticipating such motion holds significant relevance across a wide range of application domains such as human-robot interaction, autonomous driving, animation, and healthcare. In recent research, spatial and temporal dependencies are modeled by bidirectional attention mechanisms. These typically anticipate human motion in an autoregressive manner which could cause an accumulation of errors over time. As a consequence, they solely focus on local pose forecasting. To address these limitations, we propose a non-autoregressive transformer based on spatio-temporal attention, and train it not only for local pose anticipation, but also for global motion prediction in space. Furthermore, to enhance its applicability in real-world scenarios, our model is also trained to recover missing joints due to occlusions, and is capable of processing varying lengths of history observations. Our code is publicly available at this https URL.
### Title:
          There and Back Again: A Flexible-Frame Transformer for Multi-Exposure Fusion
 - **Authors:** Lishen Qu, Yao Liu, Shihao Zhou, Jie Liang, Hui Zeng, Lei Zhang, Jufeng Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-exposure fusion (MEF) brings the dynamic range of conventional cameras closer to that of human vision, producing images with rich scene content. Given the large variability in scene luminance, exposure strategies often require different numbers of frames to capture the full radiance range faithfully. However, conventional MEF techniques are typically designed for a fixed number of inputs, forcing deployment systems to maintain separate models for different frame-count requirements, which undermines deployment efficiency. To address this limitation, we propose FreeMEF, the first flexible-frame transformer for MEF that seamlessly accommodates varying numbers of input exposures without retraining or architectural changes. The proposed approach consists of two key modules. First, we introduce a recurrent state space module (RSSM) that sequentially fuses features from arbitrary sequences via adaptive alignment and state-space recurrent modeling, thereby providing global information guidance for the subsequent restoration. Second, we devise a global feature guided block (GFGB) incorporating an extremity-aware hybrid attention (EAHA) and an affine-injection feed-forward network (AFFN), which effectively resolves the similarity paradox while simultaneously optimizing contrast and brightness regulation. Extensive experiments on three benchmark datasets demonstrate the effectiveness of our method, which performs favorably against state-of-the-art methods both quantitatively and qualitatively.
### Title:
          VASAE: Naming SAE Dictionary Directions with Vocabulary-Aligned Anchoring
 - **Authors:** Kairui Zhang, Ziwen Yu, Zahraa S. Abdallah, Martha Lewis
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse autoencoders (SAEs) provide useful decompositions of Transformer residual streams, but their learned features are usually named post hoc rather than directly connected to the Transformer's token vocabulary. We introduce Vocabulary-Aligned Sparse Autoencoder (VASAE), a method that trains SAE features under vocabulary-aligned anchoring and assigns each feature an intrinsic token name: the token string whose embedding is nearest to that feature. Without reducing reconstruction quality compared with a standard SAE, VASAE produces dictionaries with vocabulary-aligned features. Using a 0.8 cutoff on the nearest-token alignment score, dictionaries trained on GPT-2-small post-residual streams align about 90% of features in layers 0--10. In Llama-3.1-8B, representative shallow and middle-layer dictionaries contain strongly aligned features, including 92.8% in the shallow layer, while the representative final-layer dictionary shows limited alignment. After subtracting the sentence-level mean sparse code, case studies show that many remaining intrinsic token names are relevant to nearby input tokens. These results suggest that vocabulary-aligned anchoring can connect learned features to intrinsic token names during training, complementing post hoc interpretation of learned dictionaries.
### Title:
          From Black-Box to Clinical Insight: A Multi-Stage Explainable Framework for Speech-Based Cognitive Impairment Detection
 - **Authors:** Yasaman Haghbin, Sina Rashidi, Ali Zolnour, Fatemeh Taherinezhad, Ali Fartoot, Hossein Azadmaleki, James M Noble, Maryam Dadkhah, Maryam Zolnoori
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Speech-based cognitive impairment detection offers a noninvasive, accessible alternative to costly biomarker assays, yet transformer-based models remain clinically uninterpretable. We propose a multi-stage explainability framework that translates black-box transformer predictions into clinically grounded narratives by integrating SHapley Additive exPlanations (SHAP)-based token attribution, theory-informed linguistic features, and a four-stage LLM reasoning pipeline using LLaMA-3.1-70B-Instruct. Built on the SpeechCARE-Adaptive Gating Network multimodal screening model (F1 = 72.11% on the NIA PREPARE benchmark), the framework maps model outputs to four cognitive-linguistic dimensions, including lexical richness, syntactic complexity, and semantic coherence. Physician evaluation on 70 stratified English samples demonstrated strong alignment with patient-level cognitive profiles, and a System Usability Scale score of 82/100 indicated high potential for clinical workflow integration.
### Title:
          MultiHashFormer: Hash-based Generative Language Models
 - **Authors:** Huiyin Xue, Atsuki Yamaguchi, Nikolaos Aletras
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Language models (LMs) represent tokens using embedding matrices that scale linearly with the vocabulary size. To constrain the parameter footprint, prior work proposes hashing many tokens into a single vector within encoder-only models. While this offers parameter efficiency, many-to-one collisions prevent its use in causal LMs. In this paper, we propose MultiHashFormer, a new framework that allows hash-based autoregression. Each token is represented as a unique hash signature, a short sequence of discrete hash IDs, generated by multiple independent hash functions. A Hash Encoder compresses this signature into a single latent vector for processing by a Transformer decoder. Then, a Hash Decoder generates the hash signature of the next token, which is then mapped back to text. We evaluate our approach at the 100M, 1B and 3B parameter scales, demonstrating that MultiHashFormer consistently outperforms standard Transformer LMs across multiple benchmarks. Furthermore, we show that our model handles multilingual vocabulary expansion with a constant parameter footprint without any modifications.
### Title:
          STAG: Spatio-temporal Evolving Structural Representation of Action Units for Micro-expression Recognition
 - **Authors:** Nandani Sharma, Varun Sharma, Dinesh Singh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Graphics (cs.GR); Human-Computer Interaction (cs.HC); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Micro-expression recognition is challenging due to subtle and short-lived facial muscle movements. Existing methods rely heavily on apex-onset frames, overlook fine-grained inter-frame dynamics, and separately model spatial and temporal information, limiting generalization across datasets. To address these challenges, we propose STAG, a dynamic ROI-AU-coupled spatial-temporal network that jointly models motion flow and adaptive facial connectivity. The framework extracts optical flow from discriminative frames using magnitude-based selection and temporal attention. A dual-branch architecture combines an enhanced graph attention network for structured spatial reasoning with a transformer encoder for temporal modeling. A bidirectional cross-attention module enables mutual refinement of spatial and temporal features, while AU-guided dynamic connectivity adapts facial region interactions according to muscle activation patterns. The transformer captures subtle temporal dynamics beyond apex-based approaches, improving semantic consistency and interpretability for explainable micro-expression recognition. The fused representation is optimized using focal loss and evaluated on CASME II, 4DME, DFME, NaME, SAMM, and SMIC-HS. Extensive experiments demonstrate improved robustness, generalization, interpretability, and computational efficiency, confirming the effectiveness of adaptive relational reasoning, AU-guided dynamic connectivity, and deep spatial-temporal feature fusion for accurate cross-dataset micro-expression recognition.
### Title:
          Higher-Order Fourier Neural Operator: Explicit Mode Mixer for Nonlinear PDEs
 - **Authors:** Alex Colagrande, Paul Caillon, Eva Feillet, Alexandre Allauzen
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators provide deep neural networks for learning mappings between function spaces. Among them, the Fourier Neural Operator (FNO) is particularly effective: its spectral convolution relies on low-dimensional Fourier-domain representations and can handle inputs at different resolutions. This design aligns well with settings where the Fourier basis diagonalizes the underlying operator, such as linear, constant-coefficient PDEs on periodic domains, in which Fourier modes evolve independently. However, nonlinear PDEs may benefit from an additional inductive bias, as they exhibit structured interactions between modes, governed by polynomial nonlinearities. To capture this inductive bias, we introduce the Higher-Order Spectral Convolution, a spectral mixer that extends FNO from diagonal modulation to explicit n-linear mode mixing, aligned with the dynamics of nonlinear PDEs. Our experiments on standard benchmarks show that the proposed Higher-Order FNO (HO-FNO) retains the efficiency of FNO-based architectures and consistently improves over other spectral neural operators. HO-FNO also performs on par with or better than state-of-the-art transformers and state-space models on several datasets, with stronger gains in highly nonlinear regimes, such as the Poisson equation with polynomial forcing, where a single HO-FNO layer outperforms FNO models with up to 16 layers. We open-source our code for reproducibility at: this https URL.
### Title:
          From Tokens to States: LLMs as a Special Case of World Models and the Continuous Path Beyond
 - **Authors:** Paul Dubois
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The AI community has framed the relationship between large language models (LLMs) and world models as a dichotomy: LLMs predict tokens; world models simulate reality. Yann LeCun argues in 2022 that reaching general intelligence requires abandoning autoregressive token prediction in favour of latent-space architectures. This framing is unnecessarily binary. Two claims will be defended. First, LLMs are a degenerate special case of world models: the state space is the set of all token sequences, the only action is appending one token, and world models are therefore a strict generalisation of LLMs, not a replacement. Second, there is a natural continuous spectrum from NTP to JEPA, with multi-token prediction, future-summary prediction, and next-latent prediction as intermediate stations already populated by current research. Moving along this spectrum relaxes the LLM constraints one by one. It also progressively surrenders the two practical advantages that make LLMs trainable at scale: internet-scale self-supervised data, and a transformer architecture co-designed for discrete token prediction. Both are examined as open research questions: the data question (the cliff from self-supervised text to instrumented action-labelled environments) and the architecture question (whether the transformer generalises to continuous-state prediction, or whether a new primitive is needed).
### Title:
          Parameter Efficient Hybrid Transformer (PEHT) for Network Traffic Prediction via Dynamic Urban Congestion Integration
 - **Authors:** Abdolazim Rezaei, Mehdi Sookhak, Mahboobeh Haghparast
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate network traffic prediction is a critical element for efficient resource allocation in dynamic urban cellular networks. However, prediction remains challenging because network demand is influenced by complex mobility patterns, congestion dynamics, and heterogeneous user behavior. This paper introduces the Parameter-Efficient Hybrid Transformer (PEHT), a network traffic prediction framework that integrates urban mobility and congestion information into a Transformer-based architecture. PEHT separates primary network communication features from secondary urban mobility features and incorporates Low-Rank Adaptation (LoRA) into the Transformer encoder to reduce the number of trainable parameters while maintaining high predictive accuracy. A multimodal fusion strategy then injects external mobility and congestion features into the decoder to improve traffic forecasting. Experiments on the Telecom Italia Milan dataset and multiple synthetic congestion scenarios show that PEHT outperforms state-of-the-art baselines in terms of RMSE, MAE, and $R^2$. The implementation is available in the GitHub repository.
## Keyword: autonomous driving
### Title:
          ReWorld: Learning Better Representations for World Action Models
 - **Authors:** Tianze Xia, Lijun Zhou, Kaixin Xiong, Jingfeng Yao, Yu Zhu, Zhenxin Zhu, Bing Wang, Guang Chen, Hangjun Ye, Wenyu Liu, Haiyang Sun, Xinggang Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World Action Models (WAMs) model future environment evolution under action conditioning, offering a scalable paradigm for autonomous driving. However, existing approaches focus largely on model architecture design, and how a WAM can efficiently learn better world representations for planning remains underexplored. To address this gap, we propose ReWorld, the first representation learning framework specifically designed for autonomous-driving world action models. In WAMs, standard training supervises only the output ends of the generation and planning modules, leaving the intermediate representations that carry world knowledge to be shaped only indirectly, as byproducts of fitting these outputs. The core idea of ReWorld is to treat intermediate representations as direct targets of optimization, shaping them along three complementary dimensions. On the Video DiT responsible for generation, we impose future-predictive supervision on its intermediate representations. On the Action DiT responsible for planning, we first align its intermediate representations cross-modally with the video world representation, then further shape them to be discriminative around safety-critical boundaries via hard-negative supervision. In addition, we systematically analyze the effectiveness of existing representation learning methods in video generation world models, and discuss why their performance is limited on this task. Experiments on nuScenes and NAVSIM show that ReWorld improves fine-tuned video generation by 23.9% in FVD (81.3 to 61.9), raises closed-loop PDMS from 89.1 to 90.4 without any post-training such as RL or post-processing, and accelerates from-scratch convergence by approximately 2x.
### Title:
          Understanding Cross-Rig Generalization in Automotive Perception: a Multi-Rig Benchmark and Rig Variation Metrics
 - **Authors:** Tim Alexander Bader, Tim Dieter Eberhardt, Maximilian Dillitzer, Wilhelm Stork
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Camera-based perception systems for autonomous driving are typically developed and evaluated using fixed sensor rigs, while real-world vehicle fleets exhibit substantial variation in camera placement, orientation, field of view, and camera count. This mismatch introduces a cross-rig domain gap in which only the geometric observation process changes. To study this effect under controlled conditions, we introduce Plentiful CARLA Camera Rigs, a benchmark that renders identical driving scenes under 14 systematically designed camera rigs. This setup enables direct analysis of cross-rig generalization without confounding changes in scene content or appearance. Using the benchmark, we analyze cross-rig transfer behavior of representative multi-view perception architectures and observe substantial performance shifts induced by geometric rig variation. To facilitate structured analysis, we further introduce two calibration-based descriptors derived from rig metadata: Rig Variance, capturing internal rig diversity, and Rig Contrastive Distance, measuring geometric discrepancy between rigs. Our experiments show that geometric rig differences strongly correlate with relative cross-rig performance shifts and that Rig Contrastive Distance provides a reliable proxy for ranking transfer difficulty between sensor rigs.
### Title:
          CascadeOcc: Rethinking 3D Occupancy World Models with Cascaded VQ Representations
 - **Authors:** Kyumin Hwang, Wonhyeok Choi, Jaeyeul Kim, Jihun Park, Daehee Park, Sunghoon Im
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This letter proposes CascadeOcc, a novel occupancy world model that prioritizes intrinsic structural hierarchy over extrinsic auxiliary modalities for autonomous driving. Occupancy world models -- forecasting the future driving environment and planning the driving trajectory -- effectively bridge perception and planning, but current approaches often heavily rely on external modalities or large language models, failing to fully exploit the inherent structural potential of occupancy representations themselves. To enhance representational capacity for complex 3D scenes, we integrate a cascaded Vector Quantized (VQ) mechanism into an autoregressive framework. Following a coarse-to-fine principle, CascadeOcc progressively refines fine-grained details from global structures through a multi-scale architecture. Additionally, we incorporate a TimeMixer to capture multi-scale temporal dependencies, establishing a dual-hierarchy mechanism in both space and time. Experimental results on 4D occupancy forecasting and motion planning benchmarks demonstrate that CascadeOcc achieves superior performance among vision-centric approaches, validating that optimizing inherent representations is a powerful alternative to relying on external foundation models.
### Title:
          MVPruner: Dynamic Token Pruning for Accelerating Multi-view Vision-Language Models in Autonomous Driving
 - **Authors:** Nan Yang, Zhanwen Liu, Linfeng Zhang, Shangyu Xie, Yang Wang, Wenzhuo Zhou, Xiangmo Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) improve generalization and interpretability in autonomous driving but suffer from efficiency issues due to long visual token sequences, particularly in standard multi-view settings. Existing token pruning methods employ fixed pruning rate allocation and static importance metrics, ignoring dynamic inter-view importance differences and the evolving information importance during inference. Our analysis reveals that multi-view VLMs inherently encode task-related view priors in deeper layers and exhibit dynamic information requirements. Motivated by these findings, we propose MVPruner, a two-stage adaptive token pruning method that aligns pruning behavior with the model's dynamic information requirements. The first stage allocates pruning budgets based on the information diversity of each view, and retains tokens with consistent contribution across stages, ensuring semantic representational capacity. The second stage allocates budgets and selects tokens guided by instruction text to guarantee task alignment. Experimental results on four benchmarks demonstrate the superior performance of our method. For example, DriveMM equipped with MVPruner achieves 87.3% reduction in FLOPs, 4.97* speedup in prefilling phase while retaining 98.5% accuracy on DriveLM benchmark.
### Title:
          Long-Term Prediction of Local and Global Human Motion with Occlusion Recovery
 - **Authors:** Qiaoyue Yang, Sven Heutger, Christopher Niemann, Magnus Jung, Ayoub Al-Hamadi, Sven Wachsmuth
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human motion describes the three-dimensional full-body movement of a person. Anticipating such motion holds significant relevance across a wide range of application domains such as human-robot interaction, autonomous driving, animation, and healthcare. In recent research, spatial and temporal dependencies are modeled by bidirectional attention mechanisms. These typically anticipate human motion in an autoregressive manner which could cause an accumulation of errors over time. As a consequence, they solely focus on local pose forecasting. To address these limitations, we propose a non-autoregressive transformer based on spatio-temporal attention, and train it not only for local pose anticipation, but also for global motion prediction in space. Furthermore, to enhance its applicability in real-world scenarios, our model is also trained to recover missing joints due to occlusions, and is capable of processing varying lengths of history observations. Our code is publicly available at this https URL.
