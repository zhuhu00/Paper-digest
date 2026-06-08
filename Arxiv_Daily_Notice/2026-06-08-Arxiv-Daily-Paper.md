# Showing new listings for Monday, 8 June 2026
## Keyword: SLAM
There is no result 
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Does Appearance Help? A Systematic Study of Image-Based Re-Identification in Online 3D Multi-Pedestrian Tracking
 - **Authors:** Eduardo Borges, Luís Garrote, Urbano J. Nunes
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based 3D Multi-Object Tracking (MOT) typically relies solely on geometric information, which is often insufficient to distinguish between targets during prolonged occlusions or in crowded human-populated environments. While integrating RGB-based Re-Identification (ReID) offers a theoretical solution for preserving identity context, existing approaches often rely on computationally expensive parallel detectors that hinder real-time robot responsiveness. This work presents a systematic study of image-based ReID in online 3D MOT, utilizing a lightweight projection-based framework to decouple geometric and appearance modeling for mobile robots. A comprehensive analysis of feature extraction architectures is conducted, employing lightweight CNNs and Vision Transformers, and evaluating various multi-modal data association strategies to balance computational latency with robust tracking. Experiments on the Pedestrian class of the KITTI dataset reveal that naive linear fusion, of appearance and motion costs, degrades performance due to visual noise. Conversely, a cascaded matching strategy successfully recovers occluded tracks without compromising overall precision, effectively preventing identity switches to maintain human-robot interaction continuity. We show that lightweight architectures can offer an optimal trade-off between the low latency required for safe navigation and the discriminative power needed for social awareness.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Geometric Second-Order Feature Correlation Learning for Self-Supervised Speech Emotion Recognition
 - **Authors:** Shuanglin Li, Ruxiao Qian, Siyang Song
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised learning (SSL) yields powerful, context-rich representations for speech emotion recognition (SER), yet aggregating these representations into holistic descriptors remains a bottleneck. Conventional first-order aggregation implicitly assumes feature independence, which overlooks the latent Riemannian geometry and discards higher-order relationships essential to the representational power of the backbone. To address this problem, this paper proposes a novel Second-Order Correlation (SOC) layer. Instead of treating features in isolation, SOC models feature correlations as covariance descriptors to capture synergistic co-occurrence patterns, which serve as discriminative signatures for robust emotion recognition. By mapping these descriptors from the Riemannian manifold to a Euclidean tangent space through Log-Euclidean mapping (LEM), the proposed method preserves geometric integrity while enabling direct linear discriminative learning. Extensive experiments on the ESD and RAVDESS datasets demonstrate that SOC recovers discriminative information lost in first-order pooling and effectively aggregates high-dimensional SSL features.
### Title:
          RPC-GS: Gaussian Splatting with native RPC Rendering for Satellite Imagery
 - **Authors:** Valentin Wagner, Sebastian Bullinger, Christoph Bodensteiner, Michael Arens
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present RPC-GS, the first Gaussian Splatting framework for satellite imagery that operates natively with Rational Polynomial Camera (RPC) models. The RPC model is the de facto standard for representing the complex imaging geometry of modern pushbroom satellite sensors. To simplify rendering, prior satellite Gaussian Splatting methods replace the RPC model with perspective or affine camera approximations, leading to geometric errors during reconstruction. RPC-GS avoids these approximations by projecting Gaussian means and covariances directly through the RPC model during the splatting process. We embed the RPC model in a chain of carefully selected geo-coordinate transformations representing a mapping from splatting-suitable scene coordinates to image coordinates. To map the Gaussian covariance matrices, we derive a numerically robust Jacobian-based covariance projection for the (partially nonlinear) coordinate transformations. Since RPCs lack an explicit notion of camera depth, we integrate a metric ray-based depth formulation. We benchmark RPC, perspective, and affine camera models in a unified framework, with our native RPC renderer consistently achieving the lowest reconstruction error on leading satellite benchmark datasets, improving mean altitude error over perspective and affine approximations by 29.6% and 63.8% on DFC2019, and by 9.9% and 37.9% on IARPA2016. We release our code to support future research of Gaussian Splatting in the satellite imaging domain.
### Title:
          SCOUT: Semantic scene COverage via Uncertainty-guided Traversal
 - **Authors:** Junyu Mao, Sara Ayoubi, Vishnu D. Sharma, Ilija Hadžić, Matthew Andrews
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robots that operate over extended periods should not merely visit space; they should progressively understand it. Yet most 3D scene graph pipelines treat perception as a post-processing stage over a fixed dataset, decoupling scene representation from the decisions that determine what is observed in the first place. We present SCOUT, an online semantic exploration framework that closes this loop by coupling active traversal with probabilistic scene graph construction. Given a prior 2D occupancy map and posed RGB-D observations, SCOUT incrementally builds an uncertainty-aware 3D scene graph whose nodes maintain fused geometry and posterior beliefs over open-vocabulary object labels, while edges encode structural relations such as on, inside, belong, and next to. These beliefs are fed back to an uncertainty-guided traversal planner, which selects viewpoints by balancing expected semantic certainty gain, geometric coverage gain, and travel cost. In this way, the robot revisits ambiguous objects when additional evidence matters and expands into unseen free space when the scene remains incomplete. The resulting system treats semantic scene completeness as an operational objective rather than a passive by-product of semantic mapping, moving toward autonomous agents that can patrol, update, and reason about evolving indoor environments with minimal human intervention.
### Title:
          When Better Codebooks Are Not Enough: Predictive Performance and Behavioral Reliability in LLM Political Event Coding
 - **Authors:** Zixian He, Bharath Raahul Murugesan, Patrick Brandt, Yibo Hu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High accuracy does not necessarily make an LLM a faithful coder. This issue matters because many social-science studies rely on expert-written codebooks to turn text into structured data. We study this problem in political event coding, a challenging source-target relation classification task beyond ordinary sentence-level classification, where models must determine what one actor did to another using detailed coding rules. We test whether expert codebooks become more effective when operationalized into LLM-friendly forms with clearer definitions, examples, retrieved context, and rules for difficult cases. We then evaluate behavioral reliability under controlled changes to label names, codebook order, and label-definition mappings. Clearer codebooks substantially improve classification performance, especially for fine-grained event classification. However, these predictive gains do not fully translate into behavioral reliability. Models may produce valid labels and recover definitions while still failing behavioral reliability tests under controlled codebook changes. These findings suggest that codebook-guided LLM systems should be evaluated not only by accuracy, but also by whether they preserve the coding logic that makes coded outputs meaningful for social-science research.
### Title:
          Terastal: Layer-Variant-based Scheduling for Real-Time Multi-DNN Workloads on Heterogeneous Accelerators
 - **Authors:** Sing-Yao Wu, Fengshuo Song, Eli Bozorgzadeh
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Heterogeneous DNN accelerators improve soft real-time multi-DNN execution by mapping each layer to its preferred accelerator to reduce latency. However, under skewed workloads, large layer-latency differences across accelerators limit scheduling flexibility and increase deadline misses. To address this challenge, we introduce layer variants, customized layer implementations that reduce latency gaps on non-preferred accelerators. We then present Terastal, a soft real-time framework for layer-variant design and scheduling on heterogeneous DNN accelerators. Terastal combines offline heterogeneity-aware virtual budget assignment and layer-variant design, and online scheduling to jointly optimize accelerator mapping and variant selection under timing and accuracy constraints. Experimental results show that Terastal reduces deadline miss rate per model by 40.58%, 30.53%, and 36.27% compared with FCFS, EDF, and DREAM, respectively, while incurring only 2.24% average normalized accuracy loss across models with variants.
### Title:
          FDM: A Framework for Decision-making to build ML-based Malware detection systems
 - **Authors:** Tadiwa Vhito, Jakapan Suaboot, Warodom Werapun, Norrathep Rattanavipanon
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Selecting appropriate machine learning (ML) configurations for malware detection is a complex, multi-criteria problem. Model choice, feature engineering, and update mechanisms must jointly satisfy operational constraints that vary across deployment contexts. This paper proposes the Framework for Decision-making (FDM) to build ML-based malware detection systems. The FDM formalises this selection process using the Weighted Configuration Compatibility Score (WCCS), a multi-criteria scoring function mapping five operational parameters (platform constraint, resource budget, response latency, update frequency, and detection sensitivity) to ranked recommendations across nine configuration dimensions. To validate the framework, four experiments were conducted on three datasets (a private Windows API dataset, the public Malimg image benchmark, and an Android static API dataset). Key results include: (i) XGBoost achieved the best accuracy-to-resource ratio in binary classification (97.46 % test accuracy, <70 MB RAM), outperforming LSTM/BiLSTM which consumed up to 2.8 GB; (ii) in multi-class classification, classical models (XGBoost 79.03 %) outperformed recurrent deep models (BiLSTM 72.27 %), reversing the binary ranking; (iii) class-incremental learning with EfficientNetB0 maintained 99.13 % accuracy with only 0.65 pp degradation across 11 incremental steps; (iv) transfer learning reduced training time by 2.14 times on average for image-based malware data without significant accuracy cost; and (v) autoencoder pre-processing yielded a 14 times training speedup at a cost of only 0.86 pp accuracy. These findings confirm that the optimal ML configuration is context-dependent, validating the FDM's core premise and demonstrating its practical utility for cybersecurity practitioners.
### Title:
          DREAM: Dynamic Refinement of Early Assignment Mappings
 - **Authors:** Liwei Guan, Huanjie Wang, Hongwei Zhang, Linxun Chen, Zhaojie Liu
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative recommendation advances item retrieval by reformulating it as autoregressive generation of Semantic IDs (SIDs), compact token sequences that encode item semantics. While SIDs offer a strong semantic prior, current SID-based methods assign each item a single static identifier through offline tokenization before sufficient user feedback is observed. For cold-start items, this one-shot commitment produces poorly discriminative codes, generating misaligned paths that remain unrefined because the associated tokens are rarely sampled during training. We identify this early static commitment, not model capacity, as the fundamental cold-start bottleneck in SID-based generative recommendation. To overcome this bottleneck and bridge the disjoint objectives of tokenization and generation, we propose DREAM (Dynamic Refinement of Early Assignment Mappings), a three-stage framework that resolves this flaw through progressive refinement. First, an intent-aware tokenizer rebuilds the SID space through counterfactual contrastive learning, generating a diverse pool of behavior-aligned candidates per cold-start item. Second, the frozen recommendation backbone serves as an evaluator, selecting the most reliable candidate based on multi-context user support without retraining. Third, a dynamic beam mechanism maintains multiple weighted SID hypotheses throughout training and inference, preventing premature collapse to a single assignment. Extensive experiments on three Amazon benchmarks show that DREAM substantially outperforms state-of-the-art generative and sequential baselines on cold-start metrics.
### Title:
          The Sound of Malware: A Memory Forensics Approach for Android Malware Analysis via Audio Signals
 - **Authors:** Silvia Lucia Sanna, Massimo Palozzi, Leonardo Regano, Riccardo Lazzeretti, Giorgio Giacinto
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Android malware analysis is currently facing increasing challenges in achieving robust classification and detecting stealth attacks. Modern threats employ advanced evasion strategies such as code obfuscation, dynamic loading, packing, and even steganographic manipulation of traditional static and dynamic features. These techniques reduce the effectiveness of signature-based systems and degrade the reliability of Machine Learning models that depend on explicit semantic indicators such as permissions, API calls, or control-flow structures. In this work, we propose \approachname, a memory forensics malware detection framework that shifts the analysis perspective from semantic program modeling to signal-based structural representation. Both static bytecode and early-execution memory snapshots are transformed into audio waveforms through direct binary-to-waveform mapping, preserving low-level structural patterns without requiring disassembly or feature engineering. The resulting signals are processed using handcrafted spectral descriptors, Convolutional Neural Networks, and transformer-based embeddings. Experiments on CICMalDroid2020 dataset and VirusTotal malware demonstrate that \approachname achieves up to 98.0\% accuracy, outperforming static sonification and competitive state-of-the-art approaches.
### Title:
          GuideCAD: A Lightweight Multimodal Framework for 3D CAD Model Generation via Prefix Embedding
 - **Authors:** Minseong Kim, Jinyeong Park, Sungho Park, Jibum Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-modal approaches used for 3D CAD generation require substantial computational resources, necessitating efficient training. To address this, we propose GuideCAD, which leverages semantically rich visual-textual representations having only a small number of trainable parameters to generate 3D CAD models. Specifically, GuideCAD uses a mapping network that converts image embeddings into prefix embeddings, enabling a pretrained large language model to integrate visual and textual information. As a result, a transformer-based decoder predicts the construction sequence using the visual-textual embeddings in order to generate the 3D CAD model. For experimental evaluation, we construct a new dataset, referred to as GuideCAD, which consists of text-image pairs. Each pair includes a text prompt that represents a 3D CAD construction sequence and its corresponding 3D CAD image. Our experimental results show that GuideCAD generates comparably high-quality 3D CAD models while using approximately four times fewer parameters and achieving twice the training efficiency compared to fine-tuning approaches. We have released the source code and dataset for our method at: this https URL
### Title:
          Hierarchical Forecast Reconciliation for Urban Rail Transit Demand Prediction under Operational Disruptions
 - **Authors:** Dang Viet Anh Nguyen, Alma Fazlagic, Kristine Pryds Loft, Filipe Rodrigues
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate and coherent passenger demand forecasting is essential for Urban Rail Transit (URT) operations. Passenger demand has a hierarchical structure in which origin-destination (OD) flows aggregate to station-level inflows and outflows through conservation constraints. In practice, station-level and OD-level forecasts are often generated independently, producing incoherent predictions that violate these constraints and introduce inconsistencies into operational decision-making. Such issues become more severe during disruptions, when forecasting reliability is most critical. This paper presents the first hierarchical forecast reconciliation framework for joint station-level and OD-level URT demand prediction. A neural Fully Connected Reconciler (FCR) learns a non-linear mapping from incoherent base forecasts to coherent hierarchical predictions while guaranteeing exact structural consistency by construction. The method is benchmarked against OLS, WLS, and Minimum Trace (MinT) variants using Rejsekort smart-card data from the Copenhagen S-train network under one-step, multi-step, and disruption forecasting scenarios. Results show that reconciliation consistently improves OD forecasting accuracy while ensuring hierarchical coherence. Under normal conditions, FCR performs competitively with MinT-based methods. An oracle analysis indicates that perfect station-level forecasts could reduce OD prediction error by up to 34 percent, highlighting the value of improved base forecasts. Under severe disruptions, FCR outperforms classical methods, reducing OD forecasting error by up to 17.45 percent in multi-step destination-side delay scenarios. These findings establish hierarchical reconciliation as an effective mechanism for improving forecast robustness, with the largest benefits occurring under the most challenging operating conditions.
### Title:
          TrioPose: Native Triple-Stream Diffusion Transformers for Pose-Guided Text-to-Image Generation
 - **Authors:** Dian Gu, Zhengyi Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pose-guided text-to-image generation often suffers from limb distortions and feature crosstalk in complex multi-person scenarios. While existing UNet-based adapters struggle with long-range spatial dependencies, emerging Multimodal Diffusion Transformers (MM-DiTs) offer superior global modeling. However, naive signal concatenation in MM-DiTs severely disrupts pre-trained latent distributions. To address this, we propose TrioPose, a native pose-driven framework built upon the SD3.5M architecture. Specifically, we introduce a Triple-Stream Pose-Aware DiT (TSPA-DiT) that treats pose as an independent modality. It employs layer-wise activation and zero-initialized dual-residual injection to smoothly enforce geometric constraints while preserving pre-trained latent stability. To resolve severe multi-instance occlusions, we design a Learnable Relational Bias Mask that categorizes topological connectivity into fine-grained physical states, mapping them into continuous attention soft constraints to effectively decouple inter-instance interference. Furthermore, a Pose-Guided Spatial Loss Weighting strategy modulates the native diffusion objective using heatmap-derived error maps, focusing anatomical supervision strictly on distortion-prone regions. Extensive experiments demonstrate that TrioPose achieves state-of-the-art performance across challenging benchmarks, including Human-Art, CrowdPose, and OCHuman. Notably, it attains an AP of $64.33$ on Human-Art, representing a $30\%$ improvement over prior arts, while setting new standards for visual fidelity and text-image semantic alignment in complex multi-human generation.
### Title:
          Beyond Matching: Category-Guided Latent Intent Reasoning for Generative Retrieval in E-Commerce
 - **Authors:** Fuwei Zhang, Xiaoyu Liu, Jiajie Jin, Jiale Mao, Wei Chen, Dongbo Xi, Yifan Yang, Peng Yan, Zichao Hao, Zhao Zhang, Fuzhen Zhuang
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative retrieval offers a new paradigm for e-commerce search by mapping user queries directly to product Semantic Identifiers (SIDs). However, e-commerce queries are often short, noisy, attribute-heavy, and associated with multiple category-consistent products, creating a substantial representation gap between natural-language shopping intent and artificially constructed item SIDs. Explicit Chain-of-Thought (CoT) reasoning can help bridge this gap, but its extra generation cost is difficult to reconcile with the low-latency requirements of online e-commerce systems. To address this challenge, we propose CaLIR (Category-guided Latent Intent Reasoning), a category-guided latent intent reasoning framework for e-commerce generative retrieval. Rather than generating explicit textual rationales, CaLIR learns continuous latent intent states before SID decoding and uses product category hierarchies as a natural scaffold for coarse-to-fine intent reasoning. Specifically, we introduce hierarchical semantic reasoning to align latent states with category-level shopping intent, and query-wise reasoning enhancement to model diverse intent paths under multi-positive queries. CaLIR further combines a query-specific dynamic prefix trie, assembled from pre-indexed category-level tries, with reasoning-aware constrained decoding. Experiments on multilingual e-commerce search datasets show that CaLIR achieves a better balance between retrieval effectiveness and inference efficiency than existing methods, while also demonstrating transferability and robustness across induced hierarchies and different generative backbones.
### Title:
          MetaConfigurator: AI-Assisted RDF Authoring from JSON Data
 - **Authors:** Felix Neubauer, Mahdi Jafarkhani, Kenichi Endo, Jürgen Pleiss, Benjamin Uekermann
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scientific workflows increasingly generate structured JSON data that is easy to exchange but difficult to interpret consistently across systems due to lacking semantic interoperability. While JSON Schema ensures structural validation, it provides no native support for Linked Data semantics. This paper presents an RDF Authoring View extending the open-source JSON Schema editor MetaConfigurator, enabling researchers to transform existing JSON, YAML, or CSV data into RDF using AI-assisted RML mappings, refine triples, execute SPARQL queries, visualize knowledge graphs, and export RDF serializations within a single integrated web interface. This workflow is supported by ontology-aware IRI auto-completion, bidirectional synchronization between JSON-LD text views and RDF triple tables, and AI-assisted SPARQL query generation from natural language hints. We demonstrate the workflow using laboratory data from metal-organic framework (MOF) synthesis experiments. Protocol data describing reagents, procedure steps, and quantities is converted from JSON to ontology-based JSON-LD via RML mappings. We then refine the semantic representation, query relationships between experimental conditions and outcomes, and explore the resulting knowledge graph interactively. This integrated environment bridges conventional structured data management with Semantic Web technologies while preserving experimental context and lowering technical barriers through AI assistance.
### Title:
          Beyond Linear and Overcomplete Regimes: A Mean-Field Analysis of Bottleneck Autoencoders
 - **Authors:** Santanu Das, Ramyak Bilas, Pascal Esser, Satyaki Mukherjee
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoencoders (AEs) learn low-dimensional representations by mapping data into a latent space while minimizing reconstruction error. Despite their empirical success, theoretical understanding remains limited and largely restricted to linear models or settings without a bottleneck. In this work, we study nonlinear AEs with a fixed finite-dimensional bottleneck in the mean-field (MF) regime. We derive explicit MF learning dynamics for both encoder and decoder, providing a tractable characterization of training in the nonlinear setting. We show that, over finite time horizons, the empirical risk of finite-width networks trained with stochastic gradient descent closely tracks the MF risk trajectory with high probability. At optimality, we further establish that the finite-width risk converges to the MF optimum, demonstrating that finite networks are sufficiently expressive to approximate the infinite-width solution.
### Title:
          RISE: A Rust Library for Inverted Index Search Engines
 - **Authors:** Angelo Savino, Rossano Venturini
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inverted indexes are a crucial data structure for efficient information retrieval in large text corpora. They enable fast full-text search by mapping each term to the documents in which it appears, on top of which efficient algorithms quickly retrieve the documents relevant to a user query. We present RISE, a novel inverted index library implemented in Rust, designed to deliver high performance and efficiency for information retrieval tasks. RISE leverages Rust's safety and performance to provide a robust solution for building and querying inverted indexes, while offering accessible extensibility through its expressive trait system. While developing RISE, we revisited the inverted-index literature, thereby reproducing numerous prior works using this new test bench. We evaluated RISE against existing libraries, demonstrating competitive query performance across various datasets and workloads, with speedups of up to 2x over the current state of the art. Our results indicate that RISE is a promising tool for researchers and practitioners in the field of information retrieval.
### Title:
          Lost in Migration: Exposing Android Framework Vulnerabilities in Parallel Java-Kotlin Implementations
 - **Authors:** Rui Li, Wenrui Diao, Debin Gao
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Android has adopted Kotlin alongside Java across apps and core system components. During this shift, we observe parallel implementations in the Android Open Source Project (AOSP) where the same component is implemented in both Java and Kotlin. In principle, their functional purposes are identical. In practice, subtle semantic divergences can appear. Such divergences are not vulnerabilities by themselves, but they provide useful clues that may reveal flaws in surrounding enforcement logic. To the best of our knowledge, this paper presents the first systematic study of Java-Kotlin parallel implementations in the Android framework and examines their security implications. We design and build ParaDroid, an analysis framework that identifies parallel methods at scale and compares their behaviors. ParaDroid normalizes code into a bytecode-level intermediate representation, reconstructs class-to-source mappings, and uses large language models to reason about method semantics and identify behavioral divergences. Evaluated on AOSP Android 14-16, ParaDroid identified 329 parallel method pairs and 37 vulnerable divergences. We responsibly disclosed the exploitable issues to the Android Security Team. Three vulnerabilities and two bugs have been confirmed, and two CVE IDs have been assigned. Our results demonstrate that parallel Java-Kotlin code paths provide a practical surface for discovering security flaws in modern Android.
## Keyword: localization
### Title:
          Lean4Agent: Formal Modeling and Verification for Agent Workflow and Trajectory
 - **Authors:** Ruida Wang, Jerry Huang, Pengcheng Wang, Xuanqing Liu, Luyang Kong, Tong Zhang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Logic in Computer Science (cs.LO); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Equipping Large Language Models (LLMs) to execute reliable multi-step workflows has become a central challenge in artificial intelligence. Despite recent advances in LLMs' agentic capabilities, most agent systems still lack formal methods for specifying, verifying, and debugging their workflow and execution trajectories. This challenge mirrors a long-standing problem in mathematics, where the ambiguity of natural languages (NLs) motivates the development of formal languages (FLs). Inspired by this paradigm, we propose **Lean4Agent**, to the best of our knowledge, the first framework that uses Lean4, a dependent-type FL to model and verify agent behavior. **Lean4Agent** launches **FormalAgentLib**, an extensible Lean4 library for formally modeling and verifying agent workflows' semantic consistency under explicit assumptions, and enabling localization of execution-time failures revealed by trajectories. Building on **FormalAgentLib**, we further develop **LeanEvolve**, which applies results in **FormalAgentLib** to revise workflows to enhance its capability. Extensive experiments on a hard problem subset of SWE-Bench-Verified and a subset of ELAIP-Bench across 5 leading LLMs indicate that the verification-passing workflows outperform the failing ones by an average of **11.94%**, and **LeanEvolve** further improves SWE performance by **7.47%** on average. Furthermore, **Lean4Agent** establishes a foundation for a new field of using expressive dependent-type FL to formally model and verify agent behavior.
### Title:
          Attention-Guided Autoencoder Fusion for Insulator Defect Detection Using UAV Transmission-Line Imaging
 - **Authors:** Malak Allam, Khaled Shaban, Ali Hamdi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated defect detection in high-voltage transmission-line insulators remains challenging due to severe class imbalance, large scale variation, and the small spatial extent of defect instances in Unmanned Aerial Vehicle (UAV) imagery. To address these challenges, this paper proposes AE-YOLO, an Attention-Guided AutoEncoder-Enhanced YOLO framework for robust insulator defect detection. The architecture integrates lightweight bottleneck autoencoders within a Feature Pyramid Network-Path Aggregation Network (FPN-PAN) neck. This preserves anomaly-sensitive information during multi-scale feature fusion. Convolutional Block Attention Modules (CBAM) are used throughout the backbone, enhancing feature discrimination and suppressing background interference. The framework also introduces a variance-maximizing autoencoder regularization strategy, which encourages diverse, defect-discriminative latent representations. The network trains using a unified objective that combines focal loss, Complete IoU (CIoU) loss, and autoencoder regularization to address foreground-background imbalance and improve localization accuracy. During inference, Weighted Boxes Fusion (WBF) combines predictions from YOLOv8, YOLOv10, and YOLO11. An autoencoder-guided confidence boosting mechanism improves sensitivity to rare defect categories. Experiments on the Insulator-Defect Detection dataset show that AE-YOLO with an EfficientNetV2 backbone achieves 95.10 percent mAP at 0.5, 96.40 percent precision, and 93.80 percent recall. This performance surpasses the strongest YOLO-family baseline by 5.0 points in mAP at 0.5 and 6.7 points in recall. These results confirm the effectiveness and adaptability of the framework. The model is a practical and scalable solution for UAV-based transmission-line inspection and defect monitoring.
### Title:
          VideoSEG-O3: A Multi-turn Reinforcement Learning Framework for Reasoning Video Object Segmentation
 - **Authors:** Ming Dai, Sen Yang, Boqiang Duan, Boyuan Tong, Jiedong Zhuang, Wankou Yang, Jingdong Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reasoning Video Object Segmentation (RVOS) demands a sophisticated integration of temporal dynamics, spatial details, and linguistic reasoning to achieve precise pixel-level localization. Existing methods are limited to reasoning over fixed initial inputs and lack the capacity to actively acquire further visual evidence, which is often essential for resolving complex references in long or intricate videos. To address this, we propose \textbf{VideoSEG-O3}, the first multi-turn reinforcement learning framework for RVOS that emulates the human \textit{``coarse-to-fine''} cognitive process. It employs a \textit{multi-turn temporal-spatial chain-of-thought} to capture fine-grained details by iteratively pinpointing critical intervals and keyframes. Additionally, to enable the policy to perceive segmentation quality beyond mere text probability of \texttt{[SEG]} during the RL stage, we introduce \textit{SEG-aware logit calibration}, which integrates pixel-wise segmentation feedback directly into the token-level logits. Furthermore, we design a \textit{decoupled thinking trace} to hierarchically decompose the reasoning process into temporal, spatial, and linguistic dimensions, and construct \textbf{VTS-CoT}, a specialized cold-start dataset featuring comprehensive reasoning trajectories. The code and models will be released at this https URL.
### Title:
          EASE-TTT: Evidence-Aligned Selective Test-Time Training for Long-Context Question Answering
 - **Authors:** Xiaopeng Yuan, Zebin Wang, Suwen Wang, Zongxin Yang, Haohan Wang, Yushun Dong
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-context question answering (QA) remains challenging for smaller language models even when answer-bearing evidence is already present in the input. Existing within-context retrieval methods localize and expose candidate evidence chunks for the question, but they stop at input-level evidence exposure rather than adapting the query-side attention parameters that control how the model allocates attention over full-context positions. In contrast, lightweight test-time adaptation methods, such as query-only test-time training (qTTT), leave evidence localization unresolved because their generic span-level self-supervised objectives do not identify which context positions support the current answer. In this paper, we propose Evidence-Aligned SElective Test-Time Training (EASE-TTT), a within-context retrieval-augmented test-time training framework that converts selected evidence chunks into a soft attention supervision target over their token positions. Instead of replacing the full context with retrieved chunks, EASE-TTT uses the resulting attention target to guide query-side adaptation, with the adapted model generating the final answer from the original full context. Experiments on six LongBench QA tasks and three small decoder-only language models show that EASE-TTT achieves the strongest macro-average performance among full-context inference, retrieval-only baselines, and qTTT, supporting evidence-aligned test-time adaptation in long-context QA.
### Title:
          DRIFT: From Robustness Gaps to Invariance Manifolds for AI-Generated Image Detection
 - **Authors:** Abhishek Ameta, Sayan Banerjee, Shreyas Pandith, Harshit, Ankita Chatterjee, Akshay Janardan Bankar, Amit Satish Unde
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid evolution of generative image models challenges existing AI-generated image detectors, particularly in open-world settings with unseen generators. Recent training-free approaches measure robustness gaps in frozen vision foundation models (VFMs), detecting fakes via perturbation-induced embedding drift. However, these methods rely on fixed invariance geometry inherited from pretraining and lack principled adaptation to the detection task. We instead formulate AI-generated image detection as learning a structured invariance manifold of real images under one-class supervision. Building upon a frozen VFM, we introduce lightweight projection heads that decompose representation space into complementary robust and fragile subspaces. The robust subspace is explicitly trained to suppress variations induced by physically plausible imaging transformations, approximating tangent directions of a real-image manifold, while the fragile subspace retains sensitivity to edit-like perturbations. A structured ordering margin enforces hierarchical separation between physical invariance and edit-induced variability, enabling detection as a margin-violation test relative to the learned manifold. At inference, multi-scale patch-wise drift under both transformation families yields a dual-channel invariance signature and interpretable localization. Extensive experiments demonstrate strong open-world generalization across unseen generators and resolutions, consistently outperforming training-free robustness-based baselines while providing interpretable invariance-violation maps.
### Title:
          Hierarchical Semantic-Constrained Heterogeneous Graph for Audio-Visual Event Localization
 - **Authors:** Zhe Yang, Ruyi Zhang, Hongtao Chen, Wenrui Li, Hengyu Man, Wangmeng Zuo, Xiaopeng Fan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary audio-visual event localization (OV-AVEL) jointly models audio-visual cues to recognize and temporally localize events, including categories unseen during training. Existing methods primarily learn joint audio-visual representations in Euclidean space, but still face two significant challenges. First, the lack of supervision signals for unseen categories makes it difficult to maintain audio-visual consistency across multiple temporal scales. Second, the lack of hierarchical constraints between segment- and video-level semantics prevents the model from establishing semantic consistency across different levels. To address these challenges, we propose a hierarchical semantic constrained heterogeneous graph (HSCHG) for audio-visual event localization framework. We first construct a heterogeneous hierarchical graph in Euclidean space, which includes audio and visual segment nodes and their corresponding video-level nodes. We use multi-directional temporal edges to capture complete temporal information within each modality. Simultaneously, we employ a dual-threshold filtering gated fusion strategy, introducing cross-modal information only when the alignment confidence is high. Furthermore, we introduce bidirectional semantic constraints between segment- and video-level representations to achieve semantic consistency across different levels. Based on this, we map the multi-level audio-visual representations and text prototypes uniformly into hyperbolic space. We use a hierarchical entailment regularization loss to characterize the hierarchical relationships between videos and segments. Extensive experimental results show that our method outperforms existing methods on the OV-AVEL benchmark. Ablation studies further validate the effectiveness of our method.
### Title:
          On the Geometry of On-Policy Distillation
 - **Authors:** Zhennan Shen, Yanshu Li, Qingyu Yin, Chak Tou Leong, Zhilin Wang, Yanxu Chen, Rongduo Han, Sunbowen Lee, Yi R. Fung
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 On-policy distillation (OPD) is increasingly used to improve large language model reasoning, but its training dynamics remain poorly understood. We characterize the trajectory of OPD updates in parameter space and compare it with supervised fine-tuning (SFT) and reinforcement learning with verifiable rewards (RLVR). A suite of parameter-space diagnostics consistently places OPD in a relaxed off-principal regime: compared with SFT, its updates affect fewer weights and avoid principal directions more strongly, while compared with RLVR, they remain less tightly constrained. Beyond this static localization, OPD exhibits subspace locking: its cumulative updates rapidly enter a narrow low-dimensional channel. Constraining training to the update subspace formed early in training preserves OPD performance but substantially degrades SFT, indicating that the locked subspace is functionally sufficient for OPD. Control experiments further show that sparsifying the update tokens and shifting rollout generation off-policy preserve the rank dynamics, whereas mixing the OPD objective with RLVR changes them. Overall, these results suggest that OPD is not merely an intermediate point between SFT and RLVR, but induces its own update geometry in parameter space.
### Title:
          DualGate-Net: A Prior-Gated Dual-Encoder Framework for Histopathology Cell Detection
 - **Authors:** Bahman Jafari Tabaghsar, Son Tran, K. Devaraja, Atul Sajjanhar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cell detection in histopathology images strongly depends on surrounding tissue context, where visually similar cells may belong to different classes under different microenvironments. Recent tissue-aware methods incorporate contextual priors, but often rely on static fusion strategies that may propagate noisy information. In this work, we propose DualGate-Net, a prior-aware dual-encoder framework that combines a ConvNeXtV2-based local encoder and a SegFormer-based global encoder through a learnable prior-gated fusion mechanism. The proposed module adaptively regulates the influence of tissue priors across spatial locations, while an auxiliary foreground reconstruction branch preserves high-frequency cellular structures during training. In addition, auxiliary cellness-guided cues are incorporated to further improve localization robustness. Experiments on the OCELOT benchmark demonstrate consistent improvements, achieving macro F1-scores of 0.7722 on the validation set and 0.7345 on the test set, highlighting the effectiveness of adaptive prior integration for robust histopathology cell detection.
### Title:
          SWE-Explore: Benchmarking How Coding Agents Explore Repositories
 - **Authors:** Shaoqiu Zhang, Yuhang Wang, Jialiang Liang, Yuling Shi, Wenhao Zeng, Maoquan Wang, Shilin He, Ningyuan Xu, Siyu Ye, Kai Cai, Xiaodong Gu
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Repository-level coding benchmarks such as SWE-bench have driven a rapid surge in the capabilities of coding agents. Yet they usually treat coding tasks as a holistic, binary prediction problem (e.g., resolved or unresolved), neglecting fine-grained agent capabilities such as repository understanding, context retrieval, code localization, and bug diagnosis. In this paper, we introduce SWE-Explore, a benchmark that isolates the evaluation of repository exploration, a critical capability of coding agents. Given a repository and an issue, SWE-Explore asks an explorer to return a ranked list of relevant code regions under a fixed line budget. SWE-Explore covers 848 issues across 10 programming languages and 203 open-source repositories. For each instance, we derive line-level ground truth from independent agent trajectories that successfully solved the same issue, distilling the specific code regions their solution paths actually consulted. We evaluate exploration along coverage, ranking, and context-efficiency dimensions, showing that these metrics strongly track downstream repair behavior. Across a broad set of retrieval methods, general coding agents, and specialized localizers, we find that agentic explorers form a clear tier above classical retrieval. While file-level localization is already strong for modern methods, line-level coverage and efficient ranking remain the key axes differentiating state-of-the-art explorers.
### Title:
          DisPOSE: Projected Polystochastic Diffusion for Self-Supervised Multi-View 3D Human Pose Estimation
 - **Authors:** Tony Danjun Wang, Tolga Birdal, Nassir Navab
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recovering 3D human poses for multiple individuals from different camera views is a fundamental bottleneck for analyzing interacting behaviors. Existing self-supervised approaches leverage synthetic catalogues of 3D poses; however, this leads to poor generalization in real-world scenarios due to distribution shifts. We therefore introduce DisPOSE, a self-supervised framework that approximates the inherently discrete multi-view person-assignment problem as a generative diffusion process over the space of polystochastic tensors. By employing differentiable Sinkhorn projections during denoising, our model learns to guide solutions toward valid and feasible assignments based on 2D image priors. The complete 3D skeletons of localized individuals are then regressed using a Hypergraph-Convolutional Decoder that explicitly models relational structures and articulated joints across multiple views. The proposed approach outperforms current state-of-the-art self-supervised methods on standard datasets and demonstrates strong performance on a newly proposed benchmark featuring highly occluded scenes from surgical operating rooms. Our diffusion-based localization demonstrates high label efficiency, retaining 99% of its performance with only 10% of the pseudo-labels. Notably, disentangling the assignment and root regression components while maintaining differentiability makes DisPOSE nearly agnostic to different camera arrangements.
## Keyword: transformer
### Title:
          Real-Time AttentionBender: Granular Interactive Network Bending of Video Diffusion Transformers
 - **Authors:** Adam Cole, Mick Grierson
 - **Subjects:** Subjects:
Graphics (cs.GR); Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative video models have achieved remarkable visual fidelity, yet their prompt-only interface offers thin creative agency and obscures the model's material process from the artists working with it. We present Real-Time AttentionBender, a tool that extends the practice of network bending across the full depth of the video diffusion transformer (DiT) and brings it into live, interactive generation. Built as a plugin within the DayDream Scope ecosystem and wrapping open-source real-time Wan pipelines, the tool exposes self-attention, cross-attention, and the feed-forward network as independently manipulable surfaces, with targeting down to individual diffusion steps, DiT layers, prompt tokens, and hidden neurons. The immediacy of live manipulation affords what we call "material intimacy" with the model: a responsive, near-mechanistic feel for how specific layers and neurons shape generated video. We position the tool as simultaneously an XAIxArts probe into transformer internals and an expressive instrument for discovering aesthetics outside the model's default representational space.
### Title:
          Semantic-Structural Alignment for Generative Pictorial Charts
 - **Authors:** Zhida Sun, Yulin Zhang, Zheng Gu, Min Lu, Bongshin Lee, Daniel Cohen-Or, Hui Huang
 - **Subjects:** Subjects:
Graphics (cs.GR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional statistical graphics are precise but often lack the visual appeal, memorability, and engagement of pictorial charts. We present a generative framework for the automated synthesis of pictorial charts that bridges the gap between semantic expression and structural faithfulness. Rather than treating charts merely as images to be stylized, we frame the problem as a dual-conditioned generation task guided by two parallel external control signals: a text prompt capturing the semantic context of the editing intent, and a context image providing the abstract statistical chart's global structure. To reinforce these controls within a Multi-Modal Diffusion Transformer, we introduce two complementary feature-level mechanisms: structural alignment to anchor spatial layouts to the input chart, and semantic alignment to transfer expressive textures from reference images. Generalizing across major visual channels (i.e., length, area, angle, and position) and diverse semantic domains, our method produces pictorial charts that are both artistically compelling and structurally consistent. Extensive quantitative evaluations and perceptual user studies demonstrate that our framework outperforms traditional controllable generation and image editing baselines, providing a foundation for high-fidelity, data-driven generative modeling in expressive visual storytelling. Project page: this https URL.
### Title:
          DxPTA: An Architecture Design Space Exploration with Optical Dataflow-guided Strategy for HW/SW Co-Design of Photonic Transformer Accelerators
 - **Authors:** Rachmad Vidya Wicaksana Putra, Solomon Micheal Serunjogi, Mahmoud Rasras, Muhammad Shafique
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI); Distributed, Parallel, and Cluster Computing (cs.DC); Emerging Technologies (cs.ET); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based networks have emerged as prominent AI models with state-of-the-art performance, which potentially pave the way toward artificial general intelligence (AGI). However, their large sizes still hinder their efficient implementation, thus highlighting the need for alternate solutions to enable their energy-efficient acceleration. Recently, state-of-the-art works propose photonic transformer accelerators (PTAs) with significant speedup and energy efficiency improvements over the conventional electronic accelerators. However, their PTA architectures are developed without considering the application constraints (e.g., area, power, energy, and latency). Moreover, their manual design approach also requires huge design time to determine a suitable architecture for the targeted application, hence making this approach not scalable. To address these limitations, we propose DxPTA, a novel design space exploration methodology for enabling efficient hardware/software co-design of the appropriate PTA architecture that meets all constraints. It is achieved by (1) identifying the PTA architecture parameters based on the coherent optical dataflow; (2) analyzing the impact/significance of the parameters; and (3) leveraging this analysis for devising a constraint-aware architecture search algorithm. Experimental results show that, our DxPTA can find the appropriate PTA architectures for different transformer-based models (i.e., DeiT-T/S/B and BERT-B/L). It achieves up to 26mm^2 area, 4.8W power, 39mJ energy, and 6ms latency, for constraints of 50mm^2 area, 5W power, 50mJ energy, and 10ms latency; with 15.2x faster searching time than the exhaustive approach. These results demonstrate the potential of DxPTA methodology for enabling efficient PTA designs for diverse AGI-based applications.
### Title:
          WAV: Multi-Resolution Block Residual Routing for Deep Decoder-Only Transformers
 - **Authors:** Kehan Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Residual connections are central to training deep Transformers, but standard PreNorm residual streams aggregate sublayer updates with fixed unit weights. Recent Attention Residuals replace this fixed accumulation with content-dependent depth-wise routing, and Block Attention Residuals make the mechanism efficient by routing over block-level residual summaries. However, a single block summary stores only the low-frequency total residual displacement inside a block, discarding directional structure such as attention-vs-MLP imbalance and early-vs-late block dynamics. We propose WAV v1, a lightweight multi-resolution residual routing method for decoder-only Transformers. Instead of representing each block only by its accumulated residual sum, WAV v1 augments every block with two directional detail bases: a phase basis that contrasts attention and MLP updates, and a split basis that contrasts early and late sublayer updates. These bases are routed together with standard block summaries through the same depth-wise softmax mixer, while negative detail-source initialization and detached RMS matching stabilize training. On character-level TinyStories and Text8 language modeling, WAV v1 shows a clear depth-dependent benefit. Although it is not consistently beneficial at 12 layers, it becomes competitive at 24 layers and outperforms all baselines at 48 layers. At 48 layers, WAV v1 reduces validation loss relative to Block AttnRes from 0.4960 to 0.4738 on TinyStories and from 0.9363 to 0.9305 on Text8, with negligible additional parameters. These results suggest that directional residual details, not only block-level sums, are important for scaling residual routing in deeper Transformers.
### Title:
          From Pixels to Newtons: Predicting In Vivo Joint Contact Forces from Monocular Video
 - **Authors:** Jessy Lauer
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Joint contact forces govern implant longevity, cartilage health, and rehabilitation outcomes, shaping who develops osteoarthritis, who recovers well from joint replacement, and who benefits from biomechanical interventions. Yet they remain measurable only invasively, in a few dozen patients with instrumented implants. I present a physics-free pipeline to predict instantaneous 3D hip and knee contact forces from an uncalibrated monocular video: no markers, force plates, electromyography, subject-specific imaging, or musculoskeletal model. Parametric body meshes are recovered per frame, encoded as kinematic features, and decoded into forces by a transformer whose pose stream is adaptively modulated at every layer by body shape, joint, side, activity text, and self-supervised video tokens (V-JEPA 2), unifying hip and knee in a single model. Under leave-one-subject-out cross-validation across 26 patients and 25 activity categories from the in vivo OrthoLoad database, the pipeline matches the accuracy of subject-specific musculoskeletal simulations ($0.32 \pm 0.08$ BW RMSE for hip; $0.23 \pm 0.03$ BW for knee) and resolves peak force changes smaller than those reported for gait retraining and osteoarthritis progression. Applied zero-shot to an independent instrumented cohort, it rivals or outperforms prior published methods. Even without curated activity labels, video features alone preserve accuracy and enable end-to-end inference on raw footage. Driven by the predictor, a generative motion prior produces biomechanically plausible variants with reduced peak loading, rediscovering strategies from the predictive simulation literature. This pipeline establishes uncalibrated monocular video as a viable modality for estimating joint loading, opening a path toward retrospective analysis of archived clinical recordings, primary-care screening, and at-home rehabilitation tracking.
### Title:
          Inside the Visual Mind: Neuroscience-Motivated Concept Circuits for Interpreting and Steering Vision Transformers
 - **Authors:** Tang Li, Yanlin Chen, Mengmeng Ma, Xi Peng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite high accuracy, Vision Transformer (ViT) predictions can be driven by spurious cues, raising the need to understand their inner workings before safe deployment. Sparse autoencoders (SAEs) provide a promising lens for decomposing model representations into human-interpretable concepts, yet adapting SAE-based interpretation to ViTs remains challenging due to limited control over concept coverage and subjective, non-scalable feature interpretation. To fill the gaps, motivated by neuroscience-inspired principles, we propose ViSAE, a mechanistic interpretability toolbox for understanding ViT inner workings through concept circuits. ViSAE consists of three components: (1) A probing suite with 64K images and a 16K visually grounded concept vocabulary, improving concept coverage efficiency by 20x over ImageNet and interpretation accuracy by 28.7% over existing concept sets. (2) Top-down concept reading and Bottom-up circuit tracing algorithms that automatically recover ViT inner workings via concept circuits. (3) Applications for auditing and steering ViT behavior. Through concept editing, ViSAE improves the worst-group accuracy on WaterBirds by 48.2%, outperforming existing methods by 23.8%. Our data and code: this https URL.
### Title:
          Breaking the Lock-in: Diversifying Text-to-Image Generation via Representation Modulation
 - **Authors:** Dahee Kwon, Haeun Lee, Jaesik Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent text-to-image models built on large-scale Transformer backbones and flow-based objectives deliver strong text-image alignment and high visual quality, yet often produce overly similar samples under a fixed prompt. Existing diversity-enhancement methods alleviate this issue, but typically require expensive sampling or auxiliary optimization, incurring non-trivial overhead. To investigate the root cause of this homogeneity, we examine intermediate Transformer features and observe that the zero-frequency spatial average (DC) component rapidly converges across seeds early in generation, causing early trajectory lock-in that limits downstream variation. Building on this observation, we propose DC Attenuation for diVersity Enhancement (DAVE), a training-free representation-level intervention that selectively attenuates this component in the early regime. DAVE preserves the sampling pipeline with negligible overhead, improving prompt-consistent diversity while maintaining competitive image quality.
### Title:
          The Geometry of Last-Layer Model Stealing
 - **Authors:** Snigdha Chandan Khilar
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper uses geometry to explain how a machine learning model can be stolen using an already existing well-known method. The author has shown the exact conditions required to perfectly copy the final layer of a transformer network. When looking deeper into the hidden layers the author has explained clear limits. The author has also demonstrated that a hidden network cannot be fully reverse engineered just by looking at the final results. The research clearly maps out what can and cannot be stolen from a model.
### Title:
          Unified Safe In-context Image Generation in Multimodal Diffusion Transformers via Restricting Unsafe Information Flows
 - **Authors:** Xiang Yang, Feifei Li, Mi Zhang, Geng Hong, Xiaoyu You, Mi Wen, Min Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion transformers (DiTs) equipped with multimodal attention (MM-Attn) have become a dominant paradigm for image generation. However, preventing the generation of harmful content remains a critical challenge, particularly in image-to-image (I2I) editing tasks. Existing safety mechanisms are primarily designed for text-to-image (T2I) synthesis or U-Net-based architectures, which limits their effectiveness for unified safety mitigation in DiT-based frameworks. To bridge this gap, we propose Unified Visual Safety Regulator (UVR), a training-free safe generation framework that regulates unsafe semantics in generated images. UVR is grounded in an analysis of attention dynamics from the perspective of information flow in MM-Attn. We identify a task-independent start-up stage, during which unsafe semantics in output patches rapidly emerge and can be accurately localized, followed by task-specific semantic amplification and interference stages, where harmful signals are further propagated and entangled with benign content. Based on these observations, UVR mitigates unsafe generation through unified, targeted attention modulation and explicit restriction of harmful information flow over the identified unsafe output patches. Experiments across various concepts show that UVR achieves state-of-the-art safety performance by achieving 91% and 77% erase rate in image synthesis and editing tasks, while preserving visual quality and fidelity with minimal degradation. Code is available at this https URL.
### Title:
          An Expanded Synthetic Conversation Dataset for Multi-Turn Smishing Detection
 - **Authors:** Carl Lochstampfor, Ayan Roy
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Our prior work introduced COVA, a synthetically generated multi-turn conversational smishing dataset of 3,201 labeled conversations, establishing baseline detection benchmarks across eight models. While XGBoost with TF-IDF features achieved the best performance, with 72.5\% accuracy and 0.691 macro F1, transformer models underperformed, which was attributed to input truncation and insufficient training data. We present COVA-X, an expanded dataset of 10,985 conversations spanning eight elder-targeted scam categories, produced by an improved generation pipeline addressing contamination, label mismatch, stage-direction bleed, and prompt-design failures from the first iteration. Retraining all classifiers on the expanded dataset yields the central finding of this work: Longformer now surpasses XGBoost on all evaluation metrics, achieving 79.71\% accuracy and 0.7786 macro F1 compared with 78.43\% and 0.7563 for XGBoost. This directly confirms that transformer models require larger conversational corpora to realize their contextual advantages. We additionally document a quality life-cycle including a 12.7$\times$ improvement in label correction rate, from 49.8\% to 3.9\%, an architectural intervention reducing virtual-kidnapping artifact rates from 67.1\% to 46.5\%, and a per-scam-type outcome analysis showing that scam categories modulate results in mechanism-consistent ways. A pre/post-cleanup sensitivity analysis confirms that dataset refinement recovers genuine label-relevant signal across all three classifier architectures.
### Title:
          TALAN: Task-Aligned Latent Adaptation Networks for Targeted Post-Training of Large Language Models
 - **Authors:** Chengkai Zhang, Ziteng Liu, Junpu Wang, Zeyi Tao, Yang Wang, Sagar Chordia, Qin Huang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Targeted post-training aims to improve reasoning, math, and code without degrading strengths. Low-rank adapters are efficient but task-global; activation interventions are input-aware but often require separate probes, vectors, or inference-time steering. We introduce TALAN (Task-Aligned Latent Adaptation Networks), a sequence-conditioned latent side path inserted into a transformer's residual stream and co-trained with a low-rank adapter in one SFT loop. TALAN compresses the active sequence into latent memory, remixes it into token-level perturbations, and writes them back through a controlled residual update. It is configured along six axes: insertion location, memory size, mixer, writeback rule, trainability scope, and gradient scale. Across four Qwen3-family backbones and four STEM/code benchmarks, TALAN improves matched LoRA and DoRA baselines. With LoRA, it yields a +1.41 point cross-model mean gain, positive on all four backbones and non-negative on all 16 model-benchmark cells. With DoRA, it yields a +1.85 point mean gain, positive on all backbones and on 13 of 16 cells. Paired seed checks support positive average effects but show nontrivial variance, so we treat them as sensitivity checks. Cost is small: <1% trainable parameters relative to the backbone and 1.01-1.02x inference overhead versus matched LoRA. A Llama-3.2-1B transfer probe is also positive under LoRA and rsLoRA across seven paired seeds, supporting a transfer beyond Qwen. Internal-state analyses suggest TALAN is a small complementary activation intervention. The matched adapter update is 80-1,700x larger than the TALAN perturbation, yet their directions have near-zero cosine; per-layer measurements show this small orthogonal perturbation propagates and amplifies through depth. TALAN offers a practical platform for studying steerable activation-level adaptation within standard adapter-based post-training.
### Title:
          Belief-Aware Scheduling for Predictive Wildfire Hazard Mapping under Sparse-Window Telemetry
 - **Authors:** Xun Shao, Kohsuke Yamakawa, Cheah Wai Shiang
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 An edge node monitoring a wildfire observes more than a duty-limited or windowed down-link can carry. The receiver must predict the H-step-ahead hazard map from whatever the link delivers. We argue the operative design problem is not which neural architecture to use but how to derive a structured belief sufficient for the receiver's prediction task and maintain it through a scheduler that anticipates future transmission opportunities. We formalize this as a partially observed sequential allocation problem with three coupled per-region action axes (sensing, representation, transmission), and derive each component of the structured belief from the H-step forward operator's input requirements. Identifying these mechanisms requires independent control over the window period P, per-window capacity C, predictive horizon H, and fuel composition, which is not separable in real-landscape data; we therefore evaluate on a physics-calibrated synthetic environment. Three empirical observations support the principle: the gap between a non-myopic activity-paced reference and uniform pacing is unimodal in window-period sparsity, peaking at intermediate spacing; ablating the structured belief, the dominant operative component flips between a default landscape (temporal staleness) and a structured landscape (static-risk prior), while the per-cell intensity belief is redundant in both; and a 40 k-parameter lightweight cross-region attention encoder exceeds the FAIR activity-paced reference by ~28% on the default landscape and ~11% on the structured landscape. A deeper Transformer encoder does not improve over the lightweight encoder in mean predictive loss and exhibits higher training-seed variance. Within this task class and regime, a modest architectural inductive bias suffices when the belief and the scheduling problem are correctly posed.
### Title:
          When is 3D Worth It? A Resource-Performance Frontier for CNNs and Transformers in Lung CT
 - **Authors:** Md Enamul Hoq, Sharafat Hossain, Imraul Emmaka, Linda Larson-Prior, Lawrence Tarbox, Jonathan Bona, Donald Johann Jr.and Fred Prior
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Three-dimensional models are widely assumed preferable for volumetric medical imaging, yet their practical value depends on whether performance gains justify added computational cost and complexity. Rather than proposing a new architecture, we study how input dimensionality (2D, 2.5D, 3D) affects model behavior across convolutional neural networks (CNNs) and Vision Transformers (ViTs) under a fixed training protocol. Using a leakage-free NLST cohort (n = 1,977) with supporting LIDC-IDRI data, we find that the 2.5D CNN offers the most favorable discrimination-stability trade-off in our comparison (ROC-AUC 0.682, 95% CI [0.546, 0.799]) with a stable operating point. In contrast, 3D CNNs show threshold instability, and transformers exhibit degenerate predictions, such as all-positive predictions. Confidence intervals are wide and overlapping, so we present these results as a controlled resource-performance frontier and a failure-mode taxonomy rather than as definitive superiority claims. For class-imbalanced lung cancer screening classification, 2D and 2.5D inputs provide a more reliable trade-off between performance, stability, and computational efficiency than full 3D representations.
### Title:
          Accelerating Reproducible Research in Synthetic EHR Generation
 - **Authors:** Jalen Jiang, Chufan Gao, Ethan Rasmussen, Stephen Z. Xie, Jimeng Sun
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The generation of high-fidelity synthetic Electronic Health Records (EHR) is crucial for advancing medical research while preserving patient privacy. However, head-to-head comparison of existing generative models is hindered by disjointed codebases, incompatible data loaders, conflicting library dependencies, and inconsistent evaluation protocols. To address these gaps, we introduce a lightweight, end-to-end benchmarking framework for reproducible synthetic EHR evaluation, organized as a unified pipeline spanning data ingestion, standardized model training, and architecture-agnostic evaluation. Our current implementation targets the generation of longitudinal ICD diagnosis codes -- the most commonly studied modality in this literature -- and is built on the community-maintained PyHealth library. We reimplement and unify strong baselines (MedGAN, CorGAN, PromptEHR, HALO) under full ICD-9 vocabulary granularity, and add a lightweight GPT-2 baseline from the general-purpose sequence-modeling literature. We contribute a rigorous, architecture-agnostic privacy-utility evaluation suite that applies identically to GAN- and transformer-based generators, and report bootstrapped confidence intervals across all metrics. We further analyze the poor long-tailed performance of existing models and discuss the extensibility of our framework beyond diagnosis codes. By lowering the engineering barrier to running, extending, and evaluating under a single pipeline, we introduce a starting point for community-driven reproducibility and benchmarking synthetic EHR models.
### Title:
          Principles of Concept Representation in Sentence Encoders
 - **Authors:** Isabelle Mohr, John Dujany, Jonathan Souquet, Andre Freitas
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 What makes a sentence encoder produce good concept representations? We approach this through the lens of representational compositionality: an encoder supports a concept family only when its latent space admits a low-distortion realization of the corresponding semantic operator. This framing predicts both where current encoders succeed and where they are structurally mismatched to their supervision. Through a controlled ablation over encoder conditions trained on 3.3 million synonym and definition pairs from WordNet and Wiktionary, evaluated on three decontaminated splits and a modifier-labeled noun-phrase benchmark, we identify four principles. Fine-tuning recalibrates the latent geometry rather than expanding it (P1). Semantic signal concentrates in the final transformer layer before concept-specific training begins, making cross-layer pooling redundant (P2). Hard negatives improve discrimination and stress-test robustness without improving retrieval ranking, showing that calibration and ranking are independently addressable (P3). Finally, the effectiveness of supervision depends on the composition type of the target concept. Extensional training helps intersective and subsective families while degrading relational and intensional ones, exposing a structural limitation of current training paradigms (P4). We release two new evaluation datasets: a DBpedia semantic-gap benchmark and a modifier-labeled NP paraphrase suite.
### Title:
          The Sound of Malware: A Memory Forensics Approach for Android Malware Analysis via Audio Signals
 - **Authors:** Silvia Lucia Sanna, Massimo Palozzi, Leonardo Regano, Riccardo Lazzeretti, Giorgio Giacinto
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Android malware analysis is currently facing increasing challenges in achieving robust classification and detecting stealth attacks. Modern threats employ advanced evasion strategies such as code obfuscation, dynamic loading, packing, and even steganographic manipulation of traditional static and dynamic features. These techniques reduce the effectiveness of signature-based systems and degrade the reliability of Machine Learning models that depend on explicit semantic indicators such as permissions, API calls, or control-flow structures. In this work, we propose \approachname, a memory forensics malware detection framework that shifts the analysis perspective from semantic program modeling to signal-based structural representation. Both static bytecode and early-execution memory snapshots are transformed into audio waveforms through direct binary-to-waveform mapping, preserving low-level structural patterns without requiring disassembly or feature engineering. The resulting signals are processed using handcrafted spectral descriptors, Convolutional Neural Networks, and transformer-based embeddings. Experiments on CICMalDroid2020 dataset and VirusTotal malware demonstrate that \approachname achieves up to 98.0\% accuracy, outperforming static sonification and competitive state-of-the-art approaches.
### Title:
          Towards Unified Song Generation and Singing Voice Conversion with Accompaniment Co-Generation
 - **Authors:** Ziyu Zhang, Chunyu Qiang, Xiaopeng Wang, Yuxin Guo, Kang Yin, Wenjie Tian, Jingbin Hu, Tianlun Zuo, Zhao Guo, Teng Ma, Yuzhe Liang, Chen Zhang, Lei Xie
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While song generation and singing voice conversion (SVC) have evolved significantly, they have long been developed isolated: the former lacks zero-shot speaker cloning, while the latter overlooks vocal-accompaniment synergy. To bridge this gap, we propose UniSinger, the first end-to-end framework unifying speaker cloning song generation and accompaniment co-generation SVC. Building on the multimodal diffusion transformer, we construct a unified speaker embedding space transferring speaker representation from SVC to song generation, endowing fine-grained cross-task timbre control. To mitigate multi-task optimization conflicts, we design a curriculum learning strategy using task-specific modality masking to guide the model to gradually master the generative mechanisms among semantic content, vocal timbre, and accompaniment. Experiments show state-of-the-art performance on both tasks and realizes complementary benefits, offering new possibilities for intelligent music production.
### Title:
          GuideCAD: A Lightweight Multimodal Framework for 3D CAD Model Generation via Prefix Embedding
 - **Authors:** Minseong Kim, Jinyeong Park, Sungho Park, Jibum Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-modal approaches used for 3D CAD generation require substantial computational resources, necessitating efficient training. To address this, we propose GuideCAD, which leverages semantically rich visual-textual representations having only a small number of trainable parameters to generate 3D CAD models. Specifically, GuideCAD uses a mapping network that converts image embeddings into prefix embeddings, enabling a pretrained large language model to integrate visual and textual information. As a result, a transformer-based decoder predicts the construction sequence using the visual-textual embeddings in order to generate the 3D CAD model. For experimental evaluation, we construct a new dataset, referred to as GuideCAD, which consists of text-image pairs. Each pair includes a text prompt that represents a 3D CAD construction sequence and its corresponding 3D CAD image. Our experimental results show that GuideCAD generates comparably high-quality 3D CAD models while using approximately four times fewer parameters and achieving twice the training efficiency compared to fine-tuning approaches. We have released the source code and dataset for our method at: this https URL
### Title:
          CF-JEPA: Mask-free forward prediction with asymmetric encoder utilization for time-series representation learning
 - **Authors:** Jaehoon Lee, Sunghyun Sim
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised learning (SSL) for time-series representation learning is dominated by two paradigms: contrastive methods, which face challenges in constructing positive or negative pairs, and masking-based methods, which disrupt the temporal continuity of time-series signals. Joint-Embedding Predictive Architecture (JEPA) offers a promising alternative by predicting in representation space rather than reconstructing raw inputs. However, existing time-series JEPA variants still rely on masking and therefore inherit its continuity problem. Crop-based Forward JEPA (CF-JEPA) is proposed as an innovative mask-free framework that replaces masking with multi-horizon forward prediction: random crops serve as context views, and short-, mid-, and long-horizon future representations are predicted in the forward temporal direction, directly leveraging the inherent temporal ordering of time-series data as a learning signal. A strong asymmetry is also identified between the online encoder and the exponential moving average (EMA) target encoder, both produced from a single training run: the online encoder develops higher-rank discriminative features, while the EMA target encoder develops smoother, lower-rank temporal features. Exploiting this asymmetry, classification is routed to the online encoder and forecasting or anomaly detection to the EMA target encoder, achieving a 27% reduction in multivariate forecasting mean squared error (MSE) at no additional training cost. Across 126 University of California, Riverside (UCR) and 26 University of East Anglia (UEA) classification datasets, eight electricity transformer temperature forecasting benchmarks, and Key Performance Indicator /Yahoo anomaly detection, CF-JEPA achieves the highest average accuracy and rank on UCR and UEA among self-supervised baselines and ranks second on univariate forecasting and k-nearest neighbors-scored anomaly detection.
### Title:
          ForensicConcept: Transferable Forensic Concepts for AIGI Detection
 - **Authors:** Menyanshu Zhou, Ziyin Zhou, Ke Sun, Yunpeng Luo, Jiayi Ji, Xiaoshuai Sun, Rongrong Ji
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI-generated image detectors achieve high accuracy on in-distribution data but often fail on unseen generators. A key obstacle to understanding this failure is the black-box nature of current detectors: they do not reveal which evidence drives their decisions. We propose ForensicConcept, a framework that extracts explicit forensic concepts from detectors and enables their transfer across backbones. Our method localizes decision-critical patches via Transformer attribution, clusters them into a compact concept codebook, and uses a concept-aligned projection to produce auditable evidence readouts. Motivated by prior studies showing that DINO representations can guide diffusion generation and exhibit concept-level correspondence with diffusion features, we introduce a generation-trace reference based on CleanDIFT diffusion features and quantify backbone-trace alignment via neighborhood-structure consistency (CKNNA). We further propose concept codebook injection to transfer diffusion-derived concepts into target backbones. Experiments on GenImage, GAN-family, and Chameleon benchmarks show consistent improvements over prior methods. We also find that CKNNA alignment predicts transfer effectiveness, providing a principled explanation for why some backbones yield more transferable forensic evidence than others.
### Title:
          STREAM: Stochastic Riemannian Flow Matching with Anisotropic Decoder for Digital Histopathology Image Generation
 - **Authors:** Won June Cho, Daeky Jeong, Hyeongyeol Lim, Hongjun Yoon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computational Engineering, Finance, and Science (cs.CE); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synthetic histopathology image generation addresses critical challenges in computational pathology, including patient privacy and the growing need for large-scale training data for foundation models. Latent diffusion models have dominated the image generation domain, with recent works emphasizing that the choice of latent space is critical to the quality of generated images. Existing state-of-the-art generative models in histopathology use pretrained Vision Foundation Models (VFMs) as conditioning signals, and we observe that this leads to "conditioning collapse," where the conditioning signal dominates the latent space and lowers the quality and diversity of generated samples. Therefore, we instead use pretrained histopathology VFMs as the latent space itself, leveraging their patch-token features that encode rich semantic information. We empirically show that these features are $\ell_2$-normalized and lie on the unit hypersphere $\mathcal{S}^{d-1}$ with strong angular dominance and intrinsic curvature, making them naturally suited for a Riemannian formulation. We therefore present STREAM, the first framework to apply Riemannian flow matching in the pathology domain. STREAM consists of two stages: 1) a bridge-type stochastic perturbation that establishes per-token rectifiability on $\mathcal{S}^{d-1}$ for training a Diffusion Transformer (DiT) in latent space, and 2) a novel anisotropic decoder that allocates robustness to low-energy directions of the velocity-field Jacobian while preserving fidelity along its high-energy directions. Together, STREAM achieves state-of-the-art reconstruction and generation performance on breast and colorectal cancer datasets. The code will be publicly released upon acceptance.
### Title:
          TrioPose: Native Triple-Stream Diffusion Transformers for Pose-Guided Text-to-Image Generation
 - **Authors:** Dian Gu, Zhengyi Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pose-guided text-to-image generation often suffers from limb distortions and feature crosstalk in complex multi-person scenarios. While existing UNet-based adapters struggle with long-range spatial dependencies, emerging Multimodal Diffusion Transformers (MM-DiTs) offer superior global modeling. However, naive signal concatenation in MM-DiTs severely disrupts pre-trained latent distributions. To address this, we propose TrioPose, a native pose-driven framework built upon the SD3.5M architecture. Specifically, we introduce a Triple-Stream Pose-Aware DiT (TSPA-DiT) that treats pose as an independent modality. It employs layer-wise activation and zero-initialized dual-residual injection to smoothly enforce geometric constraints while preserving pre-trained latent stability. To resolve severe multi-instance occlusions, we design a Learnable Relational Bias Mask that categorizes topological connectivity into fine-grained physical states, mapping them into continuous attention soft constraints to effectively decouple inter-instance interference. Furthermore, a Pose-Guided Spatial Loss Weighting strategy modulates the native diffusion objective using heatmap-derived error maps, focusing anatomical supervision strictly on distortion-prone regions. Extensive experiments demonstrate that TrioPose achieves state-of-the-art performance across challenging benchmarks, including Human-Art, CrowdPose, and OCHuman. Notably, it attains an AP of $64.33$ on Human-Art, representing a $30\%$ improvement over prior arts, while setting new standards for visual fidelity and text-image semantic alignment in complex multi-human generation.
### Title:
          Native3D: End-to-End 3D Scene Generation via Unified Mesh-Texture Modeling and Semantic Alignment
 - **Authors:** Yibo Liu, Ziwei Zhang, Haozhou Pang, Menghao Li, Lanshan He, Gan Qi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents Native3D, the first end-to-end 3D scene generation framework that completely bypasses 2D intermediate representations. Traditional approaches typically require adapting 3D representations to the 2D domain to leverage pre-trained diffusion models, which inevitably introduces domain adaptation issues including geometric structural distortion and texture detail degradation. To address these limitations, we design a unified mesh-texture joint representation that simultaneously models both geometric structures and texture features through a Transformer-based scene encoder, effectively maintaining spatial relationships and visual consistency among objects within scenes. We further propose the 3D Representation Alignment Loss (3D REPA Loss), which employs an improved contrastive learning mechanism to align multi-level semantic representations in the latent space, significantly enhancing geometric and textural fidelity. Experimental results demonstrate that Native3D outperforms existing methods in both generation quality and editing flexibility, providing a novel solution for 3D scene editing.
### Title:
          RETROSPECT: RETROsynthesis via Sequential Prediction, and Chemically Transformed-ranking
 - **Authors:** Raja Sekhar Pappala, Shreyas Vinaya Sathyanarayana, Ronit Kumar Choudhary, Arjun Verma, Deepak Warrier
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Molecular Networks (q-bio.MN)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Single-step retrosynthesis needs both accurate first-ranked suggestions and candidate lists that are rich enough for downstream selection. We study this as a proposal-selection decomposition. Our system, RETROSPECT, combines a single Transformer proposal model, which we call the ChemAlign Transformer, with a LambdaMART reranker over structural, reaction-template, upstream-score, and optional DFT-derived descriptors. The generator is trained with hybrid root-aligned and random SMILES augmentation, Pre-LayerNorm, tied embeddings, exponential moving average weights, and a differentiable atom-balance auxiliary loss. On the full USPTO-50K test set of 5,007 reactions, the generator reaches 55.00% top-1 and 86.18% top-10 exact-match accuracy with 99.86% top-1 validity. On the merged candidate-pool benchmark used for reranking, which contains 5,007 test products and about 111 candidates per product, a LambdaMART model trained on the structural feature set reaches 59.4% top-1 with 0.7171 mean reciprocal rank. Feature ablations show that upstream proposal score and template-frequency statistics provide most of the reranking signal, while DFT and reaction-center DFT features provide smaller and less consistent gains. These results support a modular view of retrosynthesis: stronger single-model proposal and learned candidate selection are complementary, and the proposal model can serve as a drop-in component for ensemble systems such as RetroChimera (Maziarz et al., 2024)
### Title:
          Geometry of Semantic Space: Comparative Study of Discrete and Continuous Models
 - **Authors:** Gabriel Bounias, Sabine Ploux
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work examines the semantic geometry underlying NLP models. We compare supervised vector embeddings, such as CamemBERT, with lexical co-occurrence graphs that encode semantic relations more directly. While transformer-based embeddings achieve strong performance, their induced geometries often display unsatisfactory distributions. In contrast, graph-based models reveal a clearer and more human-readable organization of meaning. We have implemented a methodology that allows us to perform a comparative analysis either based on the structure of the graphs or based on the topology of the embeddings induced by these two approaches. The results of the comparison -- applied to the French "Great National Debate" corpus a collection of citizen contributions to the public debate -- show a similar local topology but a very different overall structure and topology. Theses findings suggest complementary perspectives between deep supervised models and graph-based models, considering a new pathway to guide neural architectures toward more stable and interpretable convergence with graphs structures.
### Title:
          Towards Tight Bounds for Streaming Attention
 - **Authors:** Justin Y. Chen, Ying Feng, Piotr Indyk, Michael Kapralov, Ekaterina Kochetkova, Boris Prokhorov
 - **Subjects:** Subjects:
Data Structures and Algorithms (cs.DS); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The attention mechanism is a cornerstone of modern transformer architectures. However, its expressive power comes at the cost of quadratic runtime and linear space usage. In particular, the classical transformer architecture explicitly stores all previously seen input elements (tokens) in order to generate the next one. The problem of implementing a transformer in limited space, known as KV cache compression, has received much interest over the past few years, spurring the development of powerful heuristics. Recent works of Haris et al, COLT'25 and Kochetkova et al, NeurIPS'25, formalized KV cache compression as the streaming attention approximation problem, providing both upper bounds (based on discrepancy theory) and information theoretic lower bounds. However, those papers left open a significant gap between the upper and lower bounds. For example, the space usage of their algorithms increases with the precision parameter, but the lower bound does not get stronger. In this work, we revisit the streaming attention approximation problem and provide nearly tight bounds on its space complexity. On the algorithmic side, we achieve the result through a surprisingly tight interplay between three distinct methods for kernel density estimation: discrepancy-based coreset constructions (e.g., Charikar-Kapralov-Waingarten'24), the polynomial method (e.g., Greengard-Rokhlin'87, Alman-Song'23), and space partitioning (e.g., Andoni-Laarhoven-Razenshteyn-Waingarten'17, Charikar-Kapralov-Nouri-Siminelakis'20). On the lower bound side, our main technical contribution is a new technique for using the INDEX problem with a large amount of side information that we hope will prove useful in other high dimensional geometric estimation problems.
### Title:
          Does Appearance Help? A Systematic Study of Image-Based Re-Identification in Online 3D Multi-Pedestrian Tracking
 - **Authors:** Eduardo Borges, Luís Garrote, Urbano J. Nunes
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based 3D Multi-Object Tracking (MOT) typically relies solely on geometric information, which is often insufficient to distinguish between targets during prolonged occlusions or in crowded human-populated environments. While integrating RGB-based Re-Identification (ReID) offers a theoretical solution for preserving identity context, existing approaches often rely on computationally expensive parallel detectors that hinder real-time robot responsiveness. This work presents a systematic study of image-based ReID in online 3D MOT, utilizing a lightweight projection-based framework to decouple geometric and appearance modeling for mobile robots. A comprehensive analysis of feature extraction architectures is conducted, employing lightweight CNNs and Vision Transformers, and evaluating various multi-modal data association strategies to balance computational latency with robust tracking. Experiments on the Pedestrian class of the KITTI dataset reveal that naive linear fusion, of appearance and motion costs, degrades performance due to visual noise. Conversely, a cascaded matching strategy successfully recovers occluded tracks without compromising overall precision, effectively preventing identity switches to maintain human-robot interaction continuity. We show that lightweight architectures can offer an optimal trade-off between the low latency required for safe navigation and the discriminative power needed for social awareness.
### Title:
          Reconstructing Multi-Decadal Forest Disturbances: A Spatio-Temporal Transformer Approach
 - **Authors:** Linus Scheibenreif, Anton Raichuk, Maxim Neumann
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate monitoring of forest disturbances is essential for understanding carbon dynamics and land management, yet traditional approaches typically rely on pixel-wise analysis of satellite time-series, ignoring spatial context. We present a deep learning framework that maps 38 years (1984-2022) of forest disturbance across the contiguous United States by modeling temporal trajectories and spatial neighborhoods simultaneously. By leveraging a vision transformer architecture, our approach effectively filters noise from weak supervision signals to produce spatially coherent disturbance maps. We perform exhaustive evaluations across multiple satellites (Landsat, Sentinel-1, Sentinel-2) and temporal windows (38 years and the more recent 6 years), validating performance against a novel, manually annotated validation dataset (n=300) and independent fire perimeter dataset (n=706). The results highlight the complexity of the task: while our spatio-temporal model demonstrates high precision (up to 98.2% for +-1 year detection on MTBS and up to 71.3% on the CONUS validation datasets, with F1-scores up to 75.8% and 47.3%, respectively) and effectively reduces spatial artifacts, it exhibits performance trade-offs across different disturbance regimes compared to pixel-wise baselines. Our method offers a promising foundation for consistent forest monitoring.
### Title:
          How Far Can Chord-Symbol Time-Series Adaptation Carry Genre Identity? Capabilities and Boundaries in Multi-Genre Chord-Symbol Modeling
 - **Authors:** Jinju Lee
 - **Subjects:** Subjects:
Sound (cs.SD); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Harmony is a compact symbolic layer where mathematical pitch relations, acoustic consonance, and musical convention meet. This report treats chord-symbol sequences not as a complete representation of music, but as an interpretable, controllable time series for genre-local harmonic modeling. Starting from a frozen pop-jazz Music Transformer checkpoint, I evaluate how far small adaptation interfaces can extend the model to eleven target genres: blues, bossa nova, Bach chorales, country, electronic, folk, funk, gospel, hip-hop, R&B/soul, and rock. The main evaluation compares LoRA, IA3, BitFit, prefix tuning, and full fine-tuning over 11 genres and 3 seeds, a complete 165-cell grid. All five methods improve over the frozen base on held-out chord prediction, with macro gains from +2.89 to +3.61 points; LoRA and IA3 score highest, but Wilcoxon tests with Holm and Benjamini-Hochberg correction do not support a decisive winner. A matched-data-size control sharpens this: when genres are sub-sampled to a common corpus size, IA3 stays on top but LoRA's full-data edge disappears and it falls to last, indicating the small gaps are partly data-driven. A control-token baseline is also strong, and wrong-genre adapters often beat the frozen base, suggesting much of the effect comes from lightweight conditioning over a reusable harmonic base rather than one particular adapter family. Additional diagnostics (rank sweeps, wrong-genre rotation, a base-checkpoint ablation, chord-only genre classification, generated-output statistics, real-song evaluation, and duplicate analysis) support a bounded conclusion: chord-symbol adaptation reliably improves genre-local harmonic prediction, but chord symbols alone do not carry complete genre identity. The report therefore avoids claims about perceived genre authenticity or full musical quality, which require controlled listener or musician evaluation.
### Title:
          Spline Policy: A Structured Representation for Robot Policies
 - **Authors:** Mengze Tian, Yiming Li, Sichao Liu, Auke Ijspeert, Sylvain Calinon
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern imitation-learning policies for robot manipulation often represent actions as fixed-resolution action chunks, which are simple and effective but expose limited geometric and temporal structure before execution. This paper studies Spline Policy (SP), a structured representation that replaces action chunks with spline parameters while keeping the policy backbone unchanged. The predicted spline can be decoded as a compact continuous trajectory, queried at different temporal resolutions, constrained or edited in parameter space, and passed to downstream controllers. For quadratic spline outputs, the same representation can also be converted into a state-dependent vector field through an analytical distance-field construction. Under the regularity and projection assumptions of this construction, the induced dynamics do not increase the distance to the generated spline, yielding a principled local corrective mechanism around the predicted motion. The spline output further supports uncertainty propagation from observations to spline parameters, trajectories, and flow fields, and can be combined with classical control mechanisms such as null-space collision avoidance without retraining the policy backbone. We instantiate SP with diffusion, flow-matching, transformer-based, and vision-language-action backbones. Experiments in low-dimensional motion learning, simulated manipulation under matched backbones, dexterous manipulation, and real-robot case studies show that SP remains compatible with modern policy learners while exposing useful motion-structure properties, including compact decoding, temporal resampling, local correction around predicted motions, uncertainty evaluation, and controller compatibility.
### Title:
          Sparsely gated tiny linear experts
 - **Authors:** Simon Schug
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparsity allows scaling model parameters without proportionally increasing computational cost. While mixture of experts (MoE) models are made increasingly sparse, individual experts typically remain large and dense. Here, we demonstrate that further increasing sparsity by shrinking each expert to consist of a single neuron and selecting a tiny fraction of many available neurons can improve compute efficiency and interpretability. Counterintuitively, the key to achieving both is removing the nonlinearity typically applied to the experts, resulting in a network of sparsely gated linear neurons (sgatlin). In an isoflop comparison, we find that replacing all transformer feedforward layers with sgatlin improves perplexity in language models across different compute budgets. At the same time, the sparsity and linearity of the resulting feedforward circuits present new opportunities for model interpretability. In a small-scale case study, we demonstrate that feedforward circuits in sgatlin can be interpreted without having to train additional replacement models. We find that they form semantically structured clusters and are causally implicated in factual recall. Our findings paint a possible path towards compute-efficient and interpretable transformer feedforward layers.
### Title:
          Planning-aligned Token Compression for Long-Context Autonomous Driving
 - **Authors:** Zhixuan Liang, Yuxiao Chen, Yurong You, Peter Karkus, Wenhao Ding, Boyi Li, Alexander Popov, Yan Wang, Maximilian Igl, Yiming Li, Danfei Xu, Nikolai Smolyanskiy, Boris Ivanovic, Ping Luo, Marco Pavone
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monolithic vision-action models represent an emerging paradigm in autonomous driving. However, this architecture produces token sequences that quickly exceed real-time computational budgets when encoding extended temporal context for complex interactions. While approaches like linear transformers and external memory try to make the context lightweight, token compression is most compatible with the architecture as it requires no backbone modifications. Yet existing compression adopts rule-based heuristics like temporal decay, decoupled from planning, risking loss of decision-critical information. We propose COMPACT-VA, a planning-aligned working memory framework built on conditional VQ-VAE, compressing extended context into bounded representations. Compression is conditioned on both historical trajectory and a learned planning intent that the posterior encoder distills from future trajectories during training, while the prior encoder learns to predict it from compressed observations. The compressed memory, concatenated with the predicted latent, feeds the policy for end-to-end optimization, planning with retained decision-critical information. We evaluate on high-signal dynamic scenarios where historical context is most critical for behavior correctness (e.g., stop, yield, or proceed), and accordingly design behavioral metrics. Under comparable token budgets, we achieve $>$6% improvement (68.3%) on success rates with consistent gains across metrics. Ablations validate planning-aligned coupling effectiveness. Closed-loop evaluation confirms that COMPACT-VA maintained general driving performance with 3.3* speedup and 2.7* memory reduction over uncompressed processing.
## Keyword: autonomous driving
### Title:
          Mission-Level Runtime Assurance Framework for Autonomous Driving
 - **Authors:** Chieh Tsai, Salim Hariri
 - **Subjects:** Subjects:
Robotics (cs.RO); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper studies runtime safety for autonomous driving when high-level driving commands become faulty or unreliable. Unlike conventional runtime-safety approaches that mainly focus on immediate vehicle safety, the proposed framework evaluates both driving safety and whether the vehicle can still successfully complete its mission before a command is executed. The framework extends highway-env with mission-level fault scenarios such as skipping required checkpoints, entering restricted areas, and generating future routes that can no longer complete the mission successfully. A runtime monitoring system is introduced to detect and reject unsafe or mission-infeasible commands before execution. For comparison, an adapted Simplex-Drive runtime-safety baseline with learning-based driving control, safety fallback control, and runtime controller switching is implemented using the public Simplex-Drive framework. Experimental results show that platform-level runtime safety alone cannot detect mission-level planning faults, while the proposed framework successfully rejects mission-infeasible commands and improves mission success under randomized fault conditions.
### Title:
          Extending Responsibility-Sensitive Safety for the Assessment of Offloaded Autonomous Driving Services
 - **Authors:** Robin Dehler, Aryan Thakur, Michael Buchholz
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safety is a fundamental requirement in the development of autonomous driving (AD) systems. While function offloading has demonstrated significant benefits in terms of computational efficiency and energy consumption, its application to safety-critical AD functionality introduces new challenges. In particular, offloaded service compositions incur increased and variable response times due to wireless vehicle-to-everything (V2X) communication, which directly affects the vehicle's reaction time and thus its safety guarantees. In this paper, we address this challenge by extending the definitions of Responsibility-Sensitive Safety (RSS) to explicitly account for different response times of local and offloaded AD service compositions. Based on this extension, we propose an integration into function offloading, using the RSS safety constraints for offloading decision-making and fallback mechanisms. Offloaded service compositions are only permitted if the current traffic situation remains safe under the corresponding end-to-end response time. If this condition is violated, the system performs a controlled fallback to local execution. Furthermore, we introduce an enhanced fallback strategy that includes a warm-standby phase for offloaded services, enabling faster and safer transitions from offloaded to local services. The proposed approach is integrated into our AD stack and evaluated in both simulation and the real world. Experimental results demonstrate that the proposed method improves safety compared to state-of-the-art function offloading and safety frameworks, while preserving the benefits of distributed computation when safety conditions allow.
### Title:
          Test-Time Trajectory Optimization for Autonomous Driving
 - **Authors:** Yihong Xu, Eloi Zablocki, Yuan Yin, Elias Ramzi, Ellington Kirby, Alexandre Boulch, Matthieu Cord
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end planners for autonomous driving typically generate a set of candidate trajectories, score each one, and return the highest-scoring candidate. However, the scorer is applied only after the proposals are generated and cannot influence the set of trajectories: a weak set of candidates limits planning performance regardless of the scorer's quality. We instead treat the scorer as a learned trajectory-level reward function and search for trajectories that maximize it. Our method, TOAD, runs the Cross-Entropy Method at test time, warm-started from the planner's proposals. It requires no retraining and is plug-and-play for existing planners. Across six base planners, TOAD improves results on NAVSIM-v1 (94.7 PDMS), NAVSIM-v2 (56.3 EPDMS), and the closed-loop HUGSIM benchmark. The code will be made publicly available via the project page: this https URL.
### Title:
          A Causal Probabilistic Framework for Perception-Informed Closed-Loop Simulation of Autonomous Driving
 - **Authors:** Zhennan Fei, Rickard Johansson, Mikael Andersson, Matthias Eng, Mattias Eriksson, Kaveh Kianfar, Sadegh Rahrovani, Chris van der Ploeg, Michael Borth, Maren Buermann, Michiel Braat, Henk Goossens, Zijian Han, Majid Khorsand Vakilzadeh, Gabriel Rodrigues de Campos
 - **Subjects:** Subjects:
Robotics (cs.RO); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Software-in-the-loop (SIL) simulation is a cornerstone for the validation of modern automotive safety functions. However, many current frameworks utilize ideal sensing, which bypasses the functional insufficiencies of perception algorithms, leading to over-optimistic safety assessments. This paper proposes a perception-informed SIL testing methodology that bridges the gap between ground-truth simulation and real-world perception behavior. We present a framework for incorporating causal probabilistic models into standardized, scenario-based simulation toolchains, applicable to both Advanced Driver Assistance Systems (ADAS) and Autonomous Driving Systems (ADS). Our approach enables the systematic injection of realistic perception errors, such as loss of detection, sizing inaccuracies, and positioning offsets, derived from physical triggering conditions like fog, rain, and object-merging scenarios. By evaluating these ``faults'' within a standardized simulation environment, we demonstrate that perception-informed testing reveals latent operational risks that ideal SIL environments fail to capture, providing a scalable pathway for SOTIF (ISO 21448) validation.
### Title:
          Planning-aligned Token Compression for Long-Context Autonomous Driving
 - **Authors:** Zhixuan Liang, Yuxiao Chen, Yurong You, Peter Karkus, Wenhao Ding, Boyi Li, Alexander Popov, Yan Wang, Maximilian Igl, Yiming Li, Danfei Xu, Nikolai Smolyanskiy, Boris Ivanovic, Ping Luo, Marco Pavone
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monolithic vision-action models represent an emerging paradigm in autonomous driving. However, this architecture produces token sequences that quickly exceed real-time computational budgets when encoding extended temporal context for complex interactions. While approaches like linear transformers and external memory try to make the context lightweight, token compression is most compatible with the architecture as it requires no backbone modifications. Yet existing compression adopts rule-based heuristics like temporal decay, decoupled from planning, risking loss of decision-critical information. We propose COMPACT-VA, a planning-aligned working memory framework built on conditional VQ-VAE, compressing extended context into bounded representations. Compression is conditioned on both historical trajectory and a learned planning intent that the posterior encoder distills from future trajectories during training, while the prior encoder learns to predict it from compressed observations. The compressed memory, concatenated with the predicted latent, feeds the policy for end-to-end optimization, planning with retained decision-critical information. We evaluate on high-signal dynamic scenarios where historical context is most critical for behavior correctness (e.g., stop, yield, or proceed), and accordingly design behavioral metrics. Under comparable token budgets, we achieve $>$6% improvement (68.3%) on success rates with consistent gains across metrics. Ablations validate planning-aligned coupling effectiveness. Closed-loop evaluation confirms that COMPACT-VA maintained general driving performance with 3.3* speedup and 2.7* memory reduction over uncompressed processing.
