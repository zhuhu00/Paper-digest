# Showing new listings for Wednesday, 24 June 2026
## Keyword: SLAM
### Title:
          Offline Reinforcement Learning for Warehouse SLAM Throughput Control
 - **Authors:** Tina Dongxu Li, Mouhacine Benosman, Rajat Kumar, Kevin Tan, Ken Meszaros, Trevor Dardik
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present an offline reinforcement learning (RL) framework for optimizing SLAM throughput control in a warehouse fulfillment environment. SLAM (Scan/Label/Apply/Manifest) throughput directly influences system congestion and operational efficiency. Our RL-based control approach dynamically recommends SLAM throughput settings that adaptively balance throughput maximization with downstream stability through intelligent adjustment of throttling behavior. We include a history-informed state representation, action space abstraction for delayed-impact control, and a reward function that captures both upstream and downstream operational metrics. Our approach is algorithm-agnostic, enabling integration of multiple offline RL methods under a unified architecture. We instantiate our framework with three state-of-the-art offline RL algorithms, and trained the models offline using de-identified historical operational logs from a large-scale warehouse. Policy performance is evaluated using a comprehensive multi-method strategy. These include model-free approaches including immediate reward estimation via regression models and long-horizon Fitted Q Evaluation (FQE), as well as model-based Deep Koopman dynamics evaluation. Empirical results reveal that the CQL policy consistently outperforms alternatives, improving system health by 22.97% and reducing average throttling duration by 3.18%. These findings demonstrate the potential of offline RL for safe and scalable warehouse throughput control optimization.
### Title:
          Decentralized Pose Graph Riemannian Optimization for Object-based Multi-Robot SLAM
 - **Authors:** Yixian Zhao, Yan Huang, Yang Xu, Liang Li, Jinming Xu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pose graph optimization (PGO) is a key back-end component for state estimation in networked multi-robot simultaneous localization and mapping (SLAM). In object-based multi-robot SLAM, the problem becomes more tightly coupled because robots must jointly estimate both their trajectories and the poses of persistent objects observed by multiple agents. Existing decentralized solutions often assume that the communication graph closely matches the physical interaction topology, which is restrictive in realistic deployments where communication is sparse, intermittent, or time-varying. This paper presents a fully decentralized Riemannian optimization framework for object-based multi-robot PGO that decouples the coupled estimation problem via a consensus mechanism, enabling flexible communication topologies. To improve convergence under limited communication budgets, we further develop a distributed approximate-Newton scheme that exploits local second-order information while operating directly on the SE(d) manifold to preserve geometric consistency, and we establish the convergence to Riemannian first-order stationary points and provide a local condition-number analysis explaining the benefit of approximate second-order information over first-order Riemannian descent. The resulting method reduces iteration count and communication overhead without sacrificing estimation accuracy. Extensive evaluations on public benchmarks, large-scale simulations, and real-world multi-robot experiments demonstrate improved accuracy, runtime efficiency, scalability across network topologies, and robustness to communication failures.
### Title:
          Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM
 - **Authors:** Leshu Li, Jie Peng, Yang Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has garnered significant attention in Simultaneous Localization and Mapping (SLAM) due to its advances in capturing fine-grained geometry features and synthesizing novel views. For SLAM in large-scale scenes, such as autonomous driving, 3DGS-SLAM faces a critical limitation: memory consumption increases continuously over time as Gaussian points accumulate, leading to poor memory efficiency and limiting its applicability. In this work, we propose a rendering-area-aware pruning strategy that selectively removes Gaussians based on their contribution to the effective rendering area, rather than solely relying on Gaussian-level heuristics such as opacity or gradient magnitude. This perspective directly targets the sources of memory redundancy, effectively reducing the peak memory footprint of 3DGS-SLAM during runtime. Evaluations on the EuRoC and KITTI datasets demonstrate that our method consistently outperforms existing pruning approaches in large-scale outdoor scenes, achieving over 60% memory reduction and more than 2 times FPS improvement while preserving localization and mapping accuracy. These results highlight rendering-area-aware pruning as a promising direction for scaling 3DGS-SLAM to real-world autonomous driving scenarios. Our code is publicly available at this https URL.
### Title:
          Vision-Language Model Reasoning for Contextual Semantic Mapping in Intralogistics
 - **Authors:** Marvin Rüdt, Hao Pang, Constantin Enke, Zäzilia Seibold, Kai Furmans
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous mobile robots operating in intralogistics environments rely on geometric maps for localization and navigation, but lack semantic understanding of objects and their contextual properties. We present a contextual semantic mapping pipeline that combines SLAM-based geometric mapping, SAM-based instance segmentation, instance clustering, and VLM multi-view reasoning to produce a contextual semantic map representation encoding geometric structure, object class, and object movability. By aggregating observations across multiple viewpoints and querying a VLM in a zero-shot, open-vocabulary setting, the pipeline infers contextual object properties--here demonstrated through movability--without requiring task-specific training or predefined object categories. We evaluate three VLMs under two prompting strategies and conduct a component-wise analysis of the pipeline. The proposed pipeline achieves 98.93 % mIoU for semantic classification and 89.17 % mAcc for object movability estimation. Component analysis identifies VLM reasoning as the primary bottleneck for contextual understanding and instance clustering as the main limitation for panoptic performance. The resulting semantic map supports context-aware filtering and robust navigation in dynamic intralogistics environments.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          OmniPath: A Multi-Modal Agentic Framework for Auditing Wheelchair Accessibility
 - **Authors:** ASM Mobarak Hossain, Nadim Mahmud, Vaskar Raychoudhury, Md Osman Gani
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 For a wheelchair user, a standard blue line on a map is often a broken promise. While platforms like OpenStreetMap (OSM) successfully capture where a path is, they frequently fail to convey how it physically feels to travel on it. This information barrier is problematic for wheelchair users. To solve this issue, we present OmniPath, a system that moves from passive mapping to proactive environmental auditing. Our framework fuses the network topology of OSM with the submeter precision of high-density aerial LiDAR (USGS 3DEP) to create a high-fidelity 3D model of the pedestrian environment. Rather than simply routing a user, our agent virtually traverses the network, analyzing the surface in 0.5 meter increments. It rigorously quantifies physical friction points specifically running slope, cross slope, and vertical discontinuities against ADA compliance standards, calculating a weighted severity score to categorize hazards from ``Mild'' to ``Critical.'' To ensure real world reliability, we validated the system against 200 physical ground truth field surveys across the National Mall using stratified random sampling. The framework demonstrated strong diagnostic reliability for high-severity hazards, achieving F1-scores of 0.60 for Severe and 0.58 for critical categories. By automating this micro-scale inspection, OmniPath identifies the ``invisible'' barriers that standard maps miss, effectively transforming a static dataset into accessibility data source that anticipates accessibility challenges before the user ever leaves home.
### Title:
          MM-TRELLIS: Point-Cloud Guided Multi-Modal 3D Vehicle Generation in Autonomous Driving
 - **Authors:** Hongli Xiao, Youjian Zhang, Yucai Bai, Chaoyue Wang, Yaohui Jin, Xiaoguang Ren, Wenjing Yang, Long Lan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recovering realistic 3D vehicle models from autonomous driving scenes is crucial for synthesizing training data and building simulation environment. However, most existing vehicle generation methods fail to fully exploit multimodal sensors i.e. multi-view images and LiDAR point clouds) and rely on neural rendering based reconstruction, leading to low-quality mesh. Recently, native 3D generative models have made significant progress, yet they are not built for arbitrary multi-view inputs and often struggle with in-the-wild driving images. In this work, we present MM-TRELLIS, a multi-modal version of TRELLIS for in-the-wild 3D vehicle generation that integrates LiDAR and image sensors from autonomous driving datasets into native 3D generative models. Specifically, multi-view images are cycled as conditioning inputs, while LiDAR point clouds provide test-time guidance to ensure geometric accuracy and cross-view consistency. During denoising, we first align the guidance point cloud with the model priors, then enforce consistency between the generated geometry and the guidance point cloud. Finally, we introduce a voxel filtering strategy based on the opacity of 3D Gaussian Splatting to suppress floaters and produce clean meshes. Comprehensive experiments on Waymo dataset demonstrate our method outperforms existing methods in high-fidelity 3D vehicle generation. Code is available at this https URL.
### Title:
          Counting Trees from Satellite Imagery with Noisy Supervision
 - **Authors:** Dimitri Gominski, Maurice Mugabowindekwe, Qiue Xu, Xiaowei Tong, Martin Brandt, Hieu Le, Rasmus Fensholt, Dimitris Samaras, Loic Landrieu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Counting individual trees is a fundamental task for environmental monitoring, yet remains largely unexplored with satellite imagery. At these resolutions, isolated trees may still be identifiable, but crown boundaries become ambiguous in dense forests, making the notion of an individual tree inherently ill-defined. Moreover, large-scale manual annotations of individual trees are prohibitively expensive. While scalable supervision can be derived from airborne LiDAR, the resulting annotations are noisy and difficult to exploit effectively. We address these challenges by formulating tree counting as a spatial density matching problem supervised through Unbalanced Optimal Transport. This formulation naturally accommodates both precise localization of isolate trees and robust density estimation in dense forests. We further introduce a self-correction mechanism that leverages transport residuals to progressively refine noisy supervision during training. We evaluate our approach on TinyTrees, a new benchmark spanning three continents and three satellite sensors, comprising over 215 million tree annotations (including 773K manually verified instances) across 23,000 this http URL. Our method consistently outperforms detection-based, regression-based, and transport-based distribution-matching baselines, demonstrating the effectiveness of unbalanced transport and reliability-aware supervision for large-scale tree counting from satellite imagery. Code, data and models are available at this https URL.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Privacy Engineering: A Systematic Literature Review
 - **Authors:** Nemania Borovits, Damian Andrew Tamburri, Willem-Jan van den Heuvel
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Privacy obligations under GDPR increasingly shape software engineering. We synthesize 90 studies from 2018 to 2025 using a systematic review with thematic synthesis to chart privacy engineering. Thirteen dimensions form two recurrent cores: Privacy Enhancing Technologies (PETs) with Privacy Metrics (PM) and Verification and Testing (VT) and Governance and Accountability (GA) with Transparency and Communication (TC) and Organizational Measures (OM). Modeling and Specification (MS) mediates between the cores. Lifecycle mapping shows concentrations at requirements and design (MS, GA), at implementation and verification (PETs, VT, PM, TC) and at operation and decommissioning (GA, OM, Data Subject Rights Management (DSRM), Incident Response and Management (IRM), Lifelong Management (LM)). Handoffs link models to rules and tests, mechanisms to metrics and deployments such as enclaves and ledgers to governance records. Domains reweight but do not alter structure: healthcare weights GA with VT and PETs, IoT and edge weight PETs with VT and PM at device and edge, web measurement weights TC with VT, AI and ML weight PETs with PM. IRM, LM and Data Minimization and Purpose Limitation (DMPL) are less often primary foci, signaling priorities for future work. The results provide a practical map and a replication-ready scaffold for assessment and updates.
### Title:
          Federated Survival Analysis in Healthcare: A Multi-Model Evaluation on Cross-Institutional Heterogeneous Breast Cancer Data
 - **Authors:** Natalia Moreno-Blasco, Anusha Ihalapathirana, Pekka Siirtola, Miguel Fernandez-de-Retana
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Quantitative Methods (q-bio.QM); Methodology (stat.ME); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Survival analysis is central to clinical decision-making, yet reliable time-to-event models require large, diverse cohorts that are rarely available at a single institution, while privacy regulations restrict the centralization of patient data. Federated learning (FL) offers a privacy-preserving alternative by training shared models without exchanging raw data, but its effectiveness for survival modeling under realistic, heterogeneous conditions remains insufficiently understood. This paper presents a systematic, multi-model evaluation of federated survival analysis on a cross-institutional breast cancer cohort with naturally heterogeneous distributed clients. Three representative survival models, the Cox Proportional Hazards model, DeepSurv, and Random Survival Forest (RSF), are compared across centralized, local, and federated training, and three federated optimization strategies (FedAvg, FedProx, and FedAdam) are assessed for the gradient-based models. Results show that FL consistently outperforms local training and approaches, and occasionally exceeds, centralized performance, while RSF offers the best overall balance of discrimination, calibration, and robustness across heterogeneous clients. We further find that performance depends on the diversity of client distributions, and that FedAvg and FedProx are stronger and more stable than FedAdam. Based on these findings, we derive practical, decision-oriented guidelines mapping data, privacy, interpretability, and resource constraints to recommended model and training-paradigm choices for federated survival modeling in healthcare.
### Title:
          On the Semantics of Generative SPARQL
 - **Authors:** Ratan Bahadur Thapa, Steffen Staab
 - **Subjects:** Subjects:
Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We extend SPARQL with a generative query construct, called \tx{GenOp}, whose evaluation calls a language model and produces typed solution mappings. We define the semantics of the GenOp in the query in a way that maintains the fixed-dataset assumption, on which formal semantics of SPARQL build, and extend solution mappings with values generated by the language model. We formalize the semantics of the extended language over these mappings using a compatibility relation that generalizes equality and supports similarity-based matching between RDF terms and generated values. We analyze the semantic consequences of generative query patterns, focusing on mapping-level recursion induced by the reuse of generated bindings. Under deterministic bounded generation and finite candidate coverage assumptions, we characterize acyclic and stratified fragments with fixpoint semantics, establish algebraic equivalence and semantics-preserving rewrite rules, and provide an executable evaluation method; and we show that data and combined complexity coincide with those of standard SPARQL.
### Title:
          Towards Version-aware Operations and Transaction Memories for Multi-layer MeMo
 - **Authors:** Peiran Li
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Symbolic Computation (cs.SC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 MeMo proposes language models with explicit multi-layer correlation matrix memories (CMMs), where memorization, retrieval, and forgetting are architectural operations. This paper asks how such memories can reduce the need for retraining when knowledge changes. For changes expressible as MeMo memory associations, the model's accessible knowledge can be updated by editing explicit memories rather than retraining the whole model. We propose a version-aware operation layer in which high-level operations such as replace, obsolete, keep-history, rollback, and trace are compiled into MeMo-native primitive calls over sequences and tokens. The key observation is that a version-aware operation is rarely a single MeMo association. It is an ordered transaction of primitive edits, for example forgetting one sequence-token chain, memorizing another, preserving a historical chain, and recording an inverse program. The framework introduces two auxiliary CMMs: a Version CMM (V-CMM) for mapping version transitions to transaction handles, and a Transaction CMM (T-CMM) for storing reusable change contents and inverse programs. It supports both direct sequence-level edits and structured diff-level inputs, and outlines an evaluation route for update success, rollback, traceability, locality, and transaction reuse.
### Title:
          Selective Capability Unlearning in End-to-End Spoken Language Understanding
 - **Authors:** Akanksha Singh, Vinod Kumar Kurmi
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern spoken language understanding (SLU) systems are increasingly deployed in real-world settings, where specific functionalities may need to be removed due to policy or safety constraints. In SLU, a functionality corresponds to an intent and its associated slot-generation behavior. However, in autoregressive models, suppressing a target intent does not eliminate the conditional mapping that generates slots conditioned on that intent. When the intent prefix is externally supplied, the model can reconstruct the original intent-slot structure. We identify this structural failure as \textbf{\emph{capability persistence}}. We propose \textit{\underline{B}inding \underline{S}ubspace (BSU)}, a representation-level framework that isolates and attenuates intent-conditioned directions underlying this mapping. Across SLU benchmarks, BSU substantially reduces forced-prefix recoverability while preserving retained performance.
### Title:
          Progressive Pixel-Neighborhood Deformable Cross-Attention for Multispectral Object Detection
 - **Authors:** Tian Qiu, Jifeng Shen, Xin Zuo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective cross-modal feature alignment and interaction are central challenges in multispectral object detection. Although global cross-attention provides strong long-range modeling ability, its quadratic complexity with respect to feature size limits deployment on resource-constrained platforms. We therefore propose Progressive Pixel-Neighborhood Deformable Cross-Attention for multispectral feature fusion, termed PNAFusion. The proposed framework is motivated by two observations: weak misalignment between visible and thermal images is usually concentrated around local neighborhoods, and semantic correspondence across modalities often follows non-linear spatial mappings that fixed receptive fields cannot model well. To address these issues, PNAFusion incorporates local spatial priors into its architectural design to concentrate feature interaction and alignment on the most relevant neighborhoods. Specifically, a Pixel-Neighborhood Cross-Attention (PNCA) module is introduced to avoid redundant global feature matching and suppress background noise. Meanwhile, an Adaptive Deformable Alignment (ADA) module captures non-linear spatial correspondences through learned pixel-wise offsets. These components are further integrated through an iterative feedback mechanism to progressively refine cross-modal feature alignment. Experiments on FLIR, M3FD, and DroneVehicle show that PNAFusion achieves 84.2, 90.5, and 85.5 mAP@0.5, respectively, under the YOLOv5 detector, and further reaches 86.8 mAP@0.5 on FLIR and 90.8 mAP@0.5 on M3FD when transferred to Co-DETR. Efficiency analysis indicates that PNAFusion reduces allocated GPU memory by 33.0\% compared with ICAFusion and reduces theoretical FLOPs from 194.8 G to 156.4 G, although the deformable sampling and iterative refinement introduce additional latency. Our code will be available at this https URL.
### Title:
          PORTER: Language-Grounded Event Representations for Portable Structured EHR Foundation Models
 - **Authors:** Lin Lawrence Guo, Adam Paul Yan, Emily Vettese, Lillian Sung
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most electronic health record (EHR) foundation models encode clinical events as discrete event tokens from a fixed vocabulary and therefore cannot directly represent events containing unseen concepts or new combinations of concepts and attributes such as numeric values. This limits transfer across institutions and even across deployment pipelines within the same institution. We introduce PORTER, a language-grounded structured EHR foundation model that decouples event representation from this fixed vocabulary. PORTER represents events through their descriptions using a frozen text encoder, integrates numeric values through a dedicated pathway, and learns clinical dynamics over patient timelines with an autoregressively pretrained temporal backbone. Across 74 clinical prediction tasks at a pediatric hospital, PORTER matched the mean AUROC of a fixed-vocabulary model with the same temporal backbone and pretraining objective. When the same patient timelines were rendered using event descriptions not seen during pretraining, PORTER transferred without retraining or vocabulary mapping, recovering 97.1% of the mean AUROC of a model trained directly on the target vocabulary. When transferred to MIMIC, PORTER outperformed the fixed-vocabulary model, which dropped 69% of events because their tokens were unseen. Mechanistic analyses showed cross-vocabulary transfer tracked preservation of patient-level representation geometry rather than the scale of the text encoder, and the numeric pathway improved sensitivity to magnitude without disrupting clinical concept identity. PORTER also achieved higher AUROC than a task-specific text serialization comparator, at 329-fold lower amortized compute. PORTER is a step toward vocabulary-independent EHR foundation models that reduce the need for vocabulary harmonization while preserving in-domain performance and enabling efficient cross-task reuse.
### Title:
          Flood Mapping from RGB imagery using a Vision Foundation Model
 - **Authors:** Vladyslav Polushko, Tilman Bucher, Ronald Rösch, Thomas März, Markus Rauhut, Andreas Weinmann
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Timely, high-resolution maps of flood extent around settlements are essential for emergency response and damage assessment. We consider airborne RGB imagery for flood mapping as it can be collected rapidly at low cost. To produce flood maps, deep learning models for water segmentation are often used. CNN based and small vision transformer models are used. However, they need much data for adaptation to a change of scenery, i.e., another flooding event. Vision foundation models or large vision transformers are known to generalize across domains. Recently, foundation models for Earth observation became available. They are pretrained on satellite data, whose spatial resolution, viewing geometry, and radiometry differ from nadir RGB imagery. Thus, adaptation is required. We investigate how a satellite-pretrained Earth observation foundation model can be adapted to centimeter-scale floodwater mapping from RGB imagery. Specifically, we fine-tune a model we call Prithvi-2.0-UPN consisting of the Prithvi-EO-2.0-600M Vision Transformer combined with a UPerNet decoder for binary water segmentation on two RGB datasets (BlessemFlood21, NeuenahrFlood). In a first experiment we observe that Prithvi-2.0-UPN reaches state-of-the-art results on BlessemFlood21 and NeuenahrFlood, when trained on their datasets. In a second experiment we show that Prithvi-2.0-UPN performs better than state-of-the-art baseline models for transfer to a new flood event (trained on BlessemFlood21, tested on NeuenahrFlood) in a zero-shot setting. However, the performance indicates room for improvement. In this respect, we investigate in a third experiment how performance improves when further fine-tuning the models with small shares of NeuenahrFlood training data: Prithvi-2.0-UPN improves the fastest and reaches almost the performance level when fully trained on NeuenahrFlood, indicating transfer capabilities.
### Title:
          OmniPath: A Multi-Modal Agentic Framework for Auditing Wheelchair Accessibility
 - **Authors:** ASM Mobarak Hossain, Nadim Mahmud, Vaskar Raychoudhury, Md Osman Gani
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 For a wheelchair user, a standard blue line on a map is often a broken promise. While platforms like OpenStreetMap (OSM) successfully capture where a path is, they frequently fail to convey how it physically feels to travel on it. This information barrier is problematic for wheelchair users. To solve this issue, we present OmniPath, a system that moves from passive mapping to proactive environmental auditing. Our framework fuses the network topology of OSM with the submeter precision of high-density aerial LiDAR (USGS 3DEP) to create a high-fidelity 3D model of the pedestrian environment. Rather than simply routing a user, our agent virtually traverses the network, analyzing the surface in 0.5 meter increments. It rigorously quantifies physical friction points specifically running slope, cross slope, and vertical discontinuities against ADA compliance standards, calculating a weighted severity score to categorize hazards from ``Mild'' to ``Critical.'' To ensure real world reliability, we validated the system against 200 physical ground truth field surveys across the National Mall using stratified random sampling. The framework demonstrated strong diagnostic reliability for high-severity hazards, achieving F1-scores of 0.60 for Severe and 0.58 for critical categories. By automating this micro-scale inspection, OmniPath identifies the ``invisible'' barriers that standard maps miss, effectively transforming a static dataset into accessibility data source that anticipates accessibility challenges before the user ever leaves home.
### Title:
          Zero-Shot Test-Time Canonicalization using Out-of-Distribution Scoring
 - **Authors:** Dominik Lindner, Johann Schmidt, Tom Siegl, Martin Becker, Sebastian Stober
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pretrained vision models often misclassify inputs that are rotated, scaled, or sheared, even though these affine transformations leave the object class unchanged. Robustness is usually restored either by building equivariance into the architecture or by retraining with augmentation, both of which require changing or retraining the model. Test-time canonicalization instead leaves the classifier untouched. It undoes the transformation of each input, mapping it to a canonical form near the training distribution before classification. Existing canonicalizers, however, rely on a narrow set of logit-based energy scores and bespoke search procedures, leaving the design space of scoring functions and optimizers unexplored. We reframe canonicalization as out-of-distribution (OOD) detection, which lets any OOD score serve as the energy minimized over transformations. Across benchmarks ranging from handwritten characters and sketches to natural images and 3D point clouds, we systematically evaluate around twenty OOD scores and nine search algorithms, finding that distance-based scores paired with random search and local refinement perform best overall. Because canonicalizing an already-aligned input can hurt accuracy, we add a gated mechanism that transforms an input only when its OOD score indicates this is needed, preserving most in-distribution accuracy while retaining the robustness gains on transformed inputs. Code is available at this http URL.
### Title:
          Unified Dominance Graph for Interval-Predicate Approximate Nearest Neighbor Search
 - **Authors:** Kwun Hang Lau, Ruiyuan Zhang, Elton Chun-Chai Li, Wun Yu Chan, Xiaojun Cheng, Xiaofang Zhou
 - **Subjects:** Subjects:
Databases (cs.DB); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Approximate Nearest Neighbor Search (ANNS) is a core primitive for unstructured data retrieval. Real-world applications--such as temporal databases, financial data analysis, and retrieval-augmented generation--often require hybrid queries whose valid objects are constrained by continuous interval attributes, such as lifespans or price ranges. We study Interval-Predicate ANNS (IPANNS), where validity is determined by a predicate between an object interval and a query interval. Existing range-filtering ANNS (RFANNS) methods are designed for single-dimensional scalar filters, but interval predicates such as containment and overlap rely on two coupled endpoint constraints. Treating endpoints as independent scalar attributes can incur large intersection overhead, while containment-specific methods lack a generalized indexing abstraction. In this paper, we propose the Unified Dominance Graph (UDG), a graph-indexing framework for the closed two-bound conjunctive fragment of IPANNS. For a chosen interval predicate, UDG maps object and query endpoints into a normalized two-dimensional dominance space and builds a dominance-labeled graph over the transformed coordinates. Containment, overlap, and other supported endpoint-bound predicates therefore reuse the same construction and search algorithms after semantic mapping, while each UDG instance remains tied to its selected predicate. UDG compresses query-state-specific proximity graphs into one compact index. To improve graph search under restrictive interval filters, we add validity-preserving patch edges that provide routing choices when few objects remain valid. Extensive evaluations on standard benchmarks and real-world datasets show that UDG achieves stable query performance across multiple interval relations and workloads, significantly outperforming existing hybrid search baselines while maintaining low indexing overhead.
### Title:
          FiCA: Feed-forward instant Gaussian Codec Avatars from a Single Portrait Image
 - **Authors:** Kim Youwang, Zhengyu Yang, Liuhao Ge, Yu Rong, Timur Bagautdinov, Su Zhaoen, Nir Sopher, Jovan Popović, Teng Deng, Tae-Hyun Oh, Chen Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce FiCA, a Feed-forward, instant Gaussian Codec Avatar generation pipeline that creates lifelike avatars from a single portrait image. Generating a photorealistic and drivable avatar from just a single image is significantly challenging due to the limited visual information available to accurately infer the 3D appearance and geometry of human heads. To address this, we develop a novel system that combines human-centric vision foundation models with a diffusion model. This system is designed to fully exploit partial visual observations to generate lifelike human avatars. Our proposed diffusion model learns a generative mapping from these partial observations to complete and authentic 3D mesh reconstruction. Additionally, we introduce a feed-forward mesh refinement network that enhances the fidelity and identity preservation of the generated avatars, eliminating the need for person-specific test-time optimization. By leveraging a universal prior model that decodes a generated mesh into a set of 3D Gaussians, we generate a photorealistic 3D Gaussian avatar, capable of being driven with novel expressions in real-time. Our experiments demonstrate that the avatars generated by our feed-forward approach faithfully represent diverse identities and surpass the visual quality of avatars produced by recent competing methods.
### Title:
          What Does ODRL Mean? A Cross-Level Ontological Grounding of Permissions, Prohibitions, and Duties in UFO-L
 - **Authors:** Daham M. Mustafa, Christoph Lange, Giancarlo Guizzardi, Diego Collarana, Christoph Quix, Stefan Decker
 - **Subjects:** Subjects:
Logic in Computer Science (cs.LO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 ODRL policy evaluators produce verdicts, but say nothing about the normative positions a policy brings into existence, the authority structures those positions presuppose, or who holds the power to declare a norm violated. We formulate the Cross-Level Design Principle: any normative language with violable, consequential norms requires both conduct-level positions (Permission, Duty, Right, No right) and competence-level positions (Power, Subjection, Immunity, Disability). Applying this to ODRL, we establish that prohibition is sanctioned (violation possible and consequential), that permission is underspecified across its behaviour parameter (open vs. closed world), and that the formal semantics covers achievement obligations only. We ground ODRL in UFO-L, mapping each activated rule to a simple legal relator and extending coverage from two to eight legal positions; violation-declaration authority, implicit in every existing evaluator, becomes an explicit Power-Subjection pair. All axioms are mechanically verified in Isabelle/HOL and across a 39-problem benchmark under Vampire, E, and Z3.
### Title:
          PDS Joint: A Parametric Double-Spiral Joint Tailored for Dexterous Hands
 - **Authors:** Haoyang Li, Yibo Wen, Yixiang Fan, Yiheng Xu, Yufeng Yue
 - **Subjects:** Subjects:
Robotics (cs.RO); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Compliant joints can embed safety and adaptability into dexterous hands, but achieving large-stroke anthropomorphic motion while maintaining joint-specific, directiondependent stiffness and reliable proprioception remains challenging. This paper presents the PDS joint, a parametric doublespiral (PDS) compliant joint that enables systematic shaping of directional stiffness across multiple deformation modes, including flexion/extension, abduction/adduction, and pronation/supination. We instantiate the joint using Archimedean and logarithmic spiral templates for different hand joints and introduce an asymmetry ratio to tailor stiffness distributions for both grasp stability and hyperextension resistance. To make the joint practically usable under large deformation, we co-design embedded inductive proprioception and propose a learningbased calibration pipeline that maps raw inductive signals to joint states using ArUco-marker tracking. Experiments characterize the stiffness landscapes across geometric parameters and demonstrate a non-monotonic dependence of lateral support on asymmetry, indicating the importance of principled parameter tuning. For joint-state estimation in the most challenging abduction/adduction motion, a learned multilayer-perceptron (MLP) mapping reduces the error compared with conventional curve fitting by 41.6%. Finally, we integrate the proposed joints into an open-source dexterous hand as a demonstration platform, on which the hand grasps a set of nine everyday objects and performs safe, contact-rich human-involved interactions.
### Title:
          P-MTP: Efficient Document Parsing via Multi-Token Prediction with Progressive Depth Scaling
 - **Authors:** Le Xiang, Chenxi Zhai, Shu Wei, Jingjing Wu, Qunyi Xie, Xiao Tan, Kunbin Chen, Wei He
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) have revolutionized document parsing by enabling end-to-end mapping from images to structured text, imposing a significant latency bottleneck, particularly for token-dense documents. While Multi-Token Prediction (MTP) has emerged as a promising approach for accelerating inference, its potential is constrained by optimization instability when scaling to deeper look-ahead depth. In this paper, we propose \textbf{P-MTP}, a framework that leverages \textbf{Progressive Multi-Token Prediction} with a lightweight MTP module to scale the look-ahead depth for high-throughput document parsing. Specifically, we introduce Progressive Curriculum Loss that adaptively re-weights different look-ahead depths using cumulative path reliability and retrospective target consistency. By effectively suppressing gradient noise in long-range predictions, P-MTP, facilitates an automated easy-to-hard optimization transition, enabling the model to master increasingly distant look-ahead depths. Furthermore, we propose Confidence-Gated Dynamic Drafting to maximize the effective look-ahead depth and acceptance rate by adaptively calibrating speculative length during inference, thereby minimizing computational waste and further pushing the boundaries of inference speedup. Experimental results across multiple benchmarks and architectures demonstrate that P-MTP, achieves up to a $5\times$ speedup with negligible loss in accuracy, providing the first successful validation of extensive look-ahead MTP in the document parsing domain.
### Title:
          Decentralized Pose Graph Riemannian Optimization for Object-based Multi-Robot SLAM
 - **Authors:** Yixian Zhao, Yan Huang, Yang Xu, Liang Li, Jinming Xu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pose graph optimization (PGO) is a key back-end component for state estimation in networked multi-robot simultaneous localization and mapping (SLAM). In object-based multi-robot SLAM, the problem becomes more tightly coupled because robots must jointly estimate both their trajectories and the poses of persistent objects observed by multiple agents. Existing decentralized solutions often assume that the communication graph closely matches the physical interaction topology, which is restrictive in realistic deployments where communication is sparse, intermittent, or time-varying. This paper presents a fully decentralized Riemannian optimization framework for object-based multi-robot PGO that decouples the coupled estimation problem via a consensus mechanism, enabling flexible communication topologies. To improve convergence under limited communication budgets, we further develop a distributed approximate-Newton scheme that exploits local second-order information while operating directly on the SE(d) manifold to preserve geometric consistency, and we establish the convergence to Riemannian first-order stationary points and provide a local condition-number analysis explaining the benefit of approximate second-order information over first-order Riemannian descent. The resulting method reduces iteration count and communication overhead without sacrificing estimation accuracy. Extensive evaluations on public benchmarks, large-scale simulations, and real-world multi-robot experiments demonstrate improved accuracy, runtime efficiency, scalability across network topologies, and robustness to communication failures.
### Title:
          Abstractions of Queries in Ontology-Based Data Access
 - **Authors:** Michel Leclère, Marie-Laure Mugnier, Guillaume Pérution-Kihli
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In ontology-based data access (OBDA), multiple data sources are integrated via mappings to an ontology. We consider an OBDA setting based on existential rules and the certain answer semantics. We address the recent issue of query abstraction, which consists of abstracting data queries by translating them to the ontology layer. Since a perfect abstraction may not exist, the notions of minimally complete and maximally sound abstractions have been introduced. We study abstractions within an extension of UCQs with a limited form of inequality and a special predicate marking database constants. While this extension does not lead to an increased complexity of the problems of interest, it is able to express minimally complete abstractions, hence perfect abstractions when they exist. We also characterize maximally sound abstractions by making a new connection with the notion of maximum recovery stemming from data exchange.
### Title:
          Evaluating the Interpretability of Sparse Autoencoders with Concept Annotations
 - **Authors:** Jonas Klotz, Cassio F. Dantas, Pallavi Jain, Diego Marcos, Begüm Demir
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse autoencoders (SAEs) are increasingly used to extract interpretable concepts from vision and vision language models, yet existing evaluation methods largely rely on proxy metrics or qualitative inspection rather than measuring semantic correspondence. We present a human-grounded evaluation framework that quantifies alignment between SAE latents and human-annotated concepts, without requiring user studies, and validate this matching through targeted attribute perturbations. To enable this intervention-style evaluation in vision, we construct synCUB and synCOCO, synthetic benchmarks of paired images that differ in exactly one attribute. We introduce Fully-Binary Matching Pursuit (FBMP), a coalition-based matching procedure that supports many-to-one mappings between SAE latents and annotated concepts, and consistently outperforms one-to-one baselines. For functional validation, we propose a Targeted Attribute Perturbation Alignment Score (TAPAScore), which tests whether matched concepts respond selectively and in the expected direction under targeted image-level attribute perturbations. Under sanity checks, our matching and TAPAScore are the only evaluated metrics that reliably distinguish trained SAEs from untrained ones. Across SAEs trained on CLIP and DINOv2 embeddings, we find that increased overcompleteness can reduce perturbation alignment, indicating a reduction in interpretability. Our evaluation framework suggests that moderate dictionary sizes provide the best trade-off, yielding the most interpretable SAEs. Code and datasets are available at this https URL.
### Title:
          Two-Level vs. Multi-Level Modelling: An Empirical Study of Cascading Maintenance Burden
 - **Authors:** Yuhong Fu, Weixing Zhang, Bowen Jiang, Haowei Cheng, Georg Grossmann, Karamjit Kaur, Matt Selway, Markus Stumptner
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When a core definition changes, every dependent artefact must be updated, a cascading problem central to software maintenance. In Model-Driven Engineering (MDE), the dominant two-level modelling (2LM) paradigm fragments domain knowledge across metamodel and model artefacts that must be kept mutually consistent, making co-evolution a persistent source of inconsistencies and effort. Multi-level modelling (MLM) unifies these artefacts and is claimed to reduce co-evolution burden, but this has not been tested in a controlled, paired comparison against 2LM. We hypothesise that MLM's structural unification yields fewer post-change inconsistencies and a smaller modification footprint than 2LM for semantically equivalent evolution scenarios. To test this, we present a pre-registered, mutation-based empirical comparison of co-evolution behaviour in both paradigms. From a curated corpus of published 2LM co-evolution scenarios, we construct semantically equivalent MLM counterparts, apply identical evolution mutations to both, and measure outcomes through automated consistency checking and pre-registered hypothesis tests. Positive controls and a blinded mapping protocol guard against bias. This design provides the first empirical framework for assessing whether paradigm-level structural choices affect cascading maintenance burden, operationalising co-evolution burden as two automatically measurable outcome variables and delivering a reusable benchmarking protocol for replication and extension.
### Title:
          SciFi-VIS: Way Out There -- How SciFi and Visualization Influence Each Other
 - **Authors:** Ulrik Günther, Julián Méndez, Gabriela Molina León, Samuel Pantze, Mario Romero, Abdulhaq Adetunji Salako, Annalena Ulschmid
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose a hybrid half-day workshop at IEEE VIS 2026, calling for participation from visualization researchers and science fiction creators in order to develop a systematic understanding of the two-way relationship these communities have long shared. We invite submissions of creative formats showcasing connections and inspiring future research. Our workshop plan includes a keynote, lightning talks, brainstorming, cross-community critique, affinity mapping, and discussion around identified themes.
### Title:
          AerialFusionMapNet: Online HD Map Construction with Aerial-Onboard BEV Fusion
 - **Authors:** Daniel Lengerer, Mathias Pechinger, Klaus Bogenberger, Carsten Markgraf
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-resolution aerial imagery has recently emerged as a complementary modality for automated driving perception and has shown potential to improve birds-eye-view (BEV) scene understanding when fused with onboard sensors. Prior work demonstrated performance gains for online high-definition (HD) map construction through aerial-onboard fusion; however, conventional end-to-end fusion does not fully exploit the structural information contained in aerial representations. In this work, we introduce AerialFusionMapNet, a fusion-based mapping framework with a structured two-stage training strategy that explicitly enhances the contribution of aerial features within a unified pipeline. The proposed training scheme enables more effective integration of structural aerial priors. On the nuScenes geographic split, AerialFusionMapNet achieves up to 54.7 mAP, improving over prior aerial-onboard fusion baselines from 48.8 mAP by +5.9 absolute and +12.1% relative. The results suggest that structured training design, rather than increased architectural complexity, plays a more decisive role in unlocking the full potential of aerial imagery for online HD map construction. Code and trained models are available at this https URL.
### Title:
          Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM
 - **Authors:** Leshu Li, Jie Peng, Yang Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has garnered significant attention in Simultaneous Localization and Mapping (SLAM) due to its advances in capturing fine-grained geometry features and synthesizing novel views. For SLAM in large-scale scenes, such as autonomous driving, 3DGS-SLAM faces a critical limitation: memory consumption increases continuously over time as Gaussian points accumulate, leading to poor memory efficiency and limiting its applicability. In this work, we propose a rendering-area-aware pruning strategy that selectively removes Gaussians based on their contribution to the effective rendering area, rather than solely relying on Gaussian-level heuristics such as opacity or gradient magnitude. This perspective directly targets the sources of memory redundancy, effectively reducing the peak memory footprint of 3DGS-SLAM during runtime. Evaluations on the EuRoC and KITTI datasets demonstrate that our method consistently outperforms existing pruning approaches in large-scale outdoor scenes, achieving over 60% memory reduction and more than 2 times FPS improvement while preserving localization and mapping accuracy. These results highlight rendering-area-aware pruning as a promising direction for scaling 3DGS-SLAM to real-world autonomous driving scenarios. Our code is publicly available at this https URL.
### Title:
          Vision-Language Model Reasoning for Contextual Semantic Mapping in Intralogistics
 - **Authors:** Marvin Rüdt, Hao Pang, Constantin Enke, Zäzilia Seibold, Kai Furmans
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous mobile robots operating in intralogistics environments rely on geometric maps for localization and navigation, but lack semantic understanding of objects and their contextual properties. We present a contextual semantic mapping pipeline that combines SLAM-based geometric mapping, SAM-based instance segmentation, instance clustering, and VLM multi-view reasoning to produce a contextual semantic map representation encoding geometric structure, object class, and object movability. By aggregating observations across multiple viewpoints and querying a VLM in a zero-shot, open-vocabulary setting, the pipeline infers contextual object properties--here demonstrated through movability--without requiring task-specific training or predefined object categories. We evaluate three VLMs under two prompting strategies and conduct a component-wise analysis of the pipeline. The proposed pipeline achieves 98.93 % mIoU for semantic classification and 89.17 % mAcc for object movability estimation. Component analysis identifies VLM reasoning as the primary bottleneck for contextual understanding and instance clustering as the main limitation for panoptic performance. The resulting semantic map supports context-aware filtering and robust navigation in dynamic intralogistics environments.
### Title:
          Solving Inverse Problems of Chaotic Systems with Bidirectional Conditional Flow Matching
 - **Authors:** Peiyan Hu, Jian Zhang, Jiashu Pan, Ruiqi Feng, Tao Zhang, Zhi-Ming Ma, Yuan-Sen Ting, Gongjie Li, Tailin Wu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modeling chaotic systems is crucial yet challenging. Inverse problems in chaotic dynamics, namely inferring initial conditions from final states, remain largely unsolved because of ill-posedness, non-uniqueness, instability, and potentially chaotic time-reverse dynamics. We address this open problem with Bidirectional Conditional Flow Matching (Bi-CFM), which learns bidirectional mappings between distributions of initial and final states to capture the stochasticity of chaotic evolution and mitigate exponential error accumulation over time. Furthermore, for systems with conservation laws, we extend it to Conservation-constrained Bi-CFM (CBi-CFM). Across the classic Lorenz, Circuit, and high-dimensional Lorenz 96 systems, Bi-CFM improves five distribution-level metrics over baselines while achieving a speedup of more than two orders of magnitude. In the three-body planet-planet scattering problem in planetary dynamics, CBi-CFM better respects conservation laws, with conservation errors comparable to those of the ground truth. Finally, on real observations of globular clusters, collisional million-body systems shaped by $\sim 10^{10}$ years (10 Gyr) of evolution, our method represents an advance in accuracy, establishing a scalable route to solving inverse problems of long-timescale real-world chaotic dynamics.
## Keyword: localization
### Title:
          A Unified Framework for Runtime Verification and Model-Based Diagnosis in LOLA
 - **Authors:** Raik Hipler, Martin Leucker, Patrick Rodler
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present an integrated framework that unifies runtime verification and model-based diagnosis within the stream specification language LOLA. By encoding system descriptions, component health states, and observations into a single stream-based formalism, the approach enables continuous, online fault localization directly alongside fault detection, without requiring separate toolchains. The framework supports both time-invariant and transient faults, and naturally accommodates nondeterministic observations.
### Title:
          VeriPilot: An LLM-Powered Verilog Debugging Framework
 - **Authors:** Yihan Wang, Cheng Liu, Jiazheng Zhang, Lei Zhang, Long Cheng, Xiaowei Li, Huawei Li
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Verilog debugging remains one of the most time-consuming stages in digital circuit design. Recent advances in Large Language Models (LLMs) have enabled automated debugging; however, most existing approaches rely solely on test outputs and compiler feedback in an end-to-end manner, limiting their effectiveness on complex bugs. A key challenge is that the root cause of an error may be far removed from its observable outputs, making it difficult for LLMs to trace long dependency chains in code. This challenge is further exacerbated in large codebases, where long context lengths hinder efficient reasoning. To address these limitations, we propose VeriPilot, an LLM-powered debugging framework that leverages golden reference models to enable fine-grained bug localization and repair. VeriPilot goes beyond output-level comparison by aligning internal variable semantics between the Verilog design and its corresponding golden model through LLM-based analysis. It then performs step-by-step signal tracing using Control-Data-Flow Graphs (CDFGs) derived from static analysis, identifying a minimal set of suspicious code regions along with their correct counterparts from the golden model. These structured insights are subsequently provided to the LLM to guide reasoning and automated code repair. Experimental results on the Comprehensive Verilog Design Problems (CVDP) benchmark from NVIDIA demonstrate that VeriPilot improves the repair success rate of GPT-4o from 54.3\% to 85.71\%, significantly enhancing both bug localization accuracy and repair effectiveness for complex Verilog designs. The source code and benchmark are publicly available at Github this https URL.
### Title:
          Listening makes Vision Clear for VLMs
 - **Authors:** Yiyang Chen, Yixin Tan, Binrui Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent work typically assesses vision--language consistency using attention distributions of answer-side tokens. However, we observe that highest attention regions are not always consistent with the intended semantic token. This probably stems from decoding drift, where language priors from previously generated answer tokens accumulate and mismatch with visual attention. Besides the priors from previous answer tokens, we find that structural tokens, e.g., modality boundary markers, may encompass the entire context and generate high attention to areas unrelated to the target. To avoid these distortions and provide consistency evaluation for large VLMs, we adopt prompt-side semantics and propose Prompt-Vision Token Activation Map (PV-TAM). PV-TAM further incorporates a filter to remove systematic bias induced by modality boundary markers. Unlike traditional methods that evaluate overlap solely through masks while ignoring activation intensity, our metrics leverage the peak distribution of attention to measure the alignment between prompts and visual regions. In experiments, PV-TAM consistently improves both attention-based and IoU-style localization metrics over answer-side baselines on various datasets.
### Title:
          From Spatial to Spectral: An Efficient, Frequency-Guided Feature Representation Learner for Small Object Detection
 - **Authors:** Yuhan Rui, Shihan Qiao, Yibin Lou, Mingxi Yu, Yutong Wan, Yanqiao Chen, Dongsheng Hou, Zhen Cao, Athena Zhuoming Zhong, Qi Hao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient small object detection is bottlenecked by the inherent feature scarcity of tiny targets, which is further aggravated by operations of spatial-domain detectors that indiscriminately discard critical high-frequency details. Recovering these fragile cues within the spatial domain is notoriously difficult, as it often requires computationally expensive architectural upscaling that inadvertently amplifies background noise. To bridge this gap, we propose a paradigm \textbf{shift from spatial to spectral} feature processing, introducing a holistic solution with the following novelty: (1) A versatile \textbf{Frequency-Guided Feature Representation framework} that generalizes across diverse detector architectures (both CNN and Transformer-based), offering a robust alternative to spatial-only feature extraction; (2) The unified \textbf{Decompose--Enhance--Reconstruct (DER)} operator, instantiated via three \textbf{lightweight, plug-and-play} modules -- Wavelet-Difference Gate (WDG), Log-Gabor Enhancer (LGE), and Frequency-Driven Head (FDHead) -- to systematically inject frequency-aware modulation into the backbone, neck, and head. This mechanism decouples feature modeling from resolution reduction, capturing discriminative high-frequency components to enable accurate localization with significantly reduced parameter redundancy; (3) Extensive validation on multi-domain benchmarks (VisDrone2019, UAVDT, TinyPerson, DOTAv1) demonstrating consistent gains. Notably, our proposed \textbf{DERNet} series outperforms YOLOv11 models under the same scale while requiring \textbf{only 1/6 of the parameters}, backed by rigorous spectral diagnostics and error decomposition analysis.
### Title:
          ABACUS: Adapting Unified Foundation Model for Bridging Image Count Understanding and Generation
 - **Authors:** Anindya Mondal, Sauradip Nag, Anjan Dutta
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 ABACUS is a unified vision-language model that handles object counting, crowd counting, referring-expression counting, and count-faithful image generation without any benchmark-specific training required. Our model is built on existing 3B-parameter unified foundation model and is adapted for object localization tasks using three key innovations: density-aware adaptive zooming with objectness maps for spatial grounding; a boundary-aware count policy via GRPO to eliminate crop-boundary errors; and a cycle-consistent GRPO strategy where the understanding branch self-critiques generated outputs, closing the understanding-generation gap without any external annotations. ABACUS achieves state-of-the-art results across seven benchmarks, outperforming both task-specific specialists and larger generalist models.
### Title:
          Trustworthy Image Authentication using Forensic Knowledge Graphs
 - **Authors:** Tai D. Nguyen, Matthew C. Stamm
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Advances in generative AI have made image falsification highly realistic, demanding trustworthy authentication systems. Existing forensic detectors can target certain forgery types but lack interpretability, while vision-language models (VLMs) provide explanations but cannot exploit forensic traces for reliable detection. We propose Forensic Knowledge Graphs (FKGs), a unified framework that integrates forensic evidence extraction, structured reasoning, and human-interpretable explanation. Our FKG structure encodes forensic traces along with their causal dependencies and links to scene content. To generate accurate FKGs, we introduce a novel forensic authentication network and an Iterative Context Refinement strategy that guides VLMs to produce faithful, grounded explanations. We also present FKG-50K, a dataset of 50,000 realistic forgeries with ground-truth FKGs. Experiments demonstrate that FKG outperforms both forensic detectors and VLMs in detection, forgery identification and localization, and forensic justification.
### Title:
          3D Masked Autoencoders are Robust Learners of Volumetric and Multimodal Cellular Representations for Microscopy
 - **Authors:** Amirhossein Kardoost, Lion Gleiter, Tingying Peng, Carsten Marr
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised learning in fluorescence microscopy often relies on 2D projections, despite the inherently three-dimensional nature of cells. We present a systematic comparison of 2D and 3D masked autoencoders (MAE-2D vs. MAE-3D) on volumetric microscopy data. Under matched architectures and training protocols, MAE-3D consistently outperforms 2D max-projection and slice-based variants on downstream single-cell tasks. We further align visual representations with a pretrained protein language model (ESM2) and show that cross-modal supervision yields larger gains for volumetric models. Channel cross-attention and frequency-domain regularization are critical for leveraging 3D spatial context. On a protein--protein interaction task, MAE-3D achieves a ROC--AUC of 0.865, outperforming prior methods by up to +0.025. For protein localization, our best 3D model attains state-of-the-art AUC$_{\text{micro}}$ (0.952) and F1$_{\text{micro}}$ (0.742), improving over previous approaches by +0.003 and +0.010 absolute, respectively. Overall, these results demonstrate the advantages of native 3D modeling and multimodal alignment for representation learning in single-cell microscopy.
### Title:
          Faithful by Construction: Claim-Anchored Attribution for Multi-Document Summarization
 - **Authors:** Shuo Guan
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end large language models (LLMs) produce fluent multi-document summaries but remain prone to hallucination, and the attributions they offer are typically coarse (whole documents or passages) and generated post hoc, leaving each summary statement hard to verify. We revisit the modular Extract--Select--Rewrite paradigm and recast its intermediate representation as the unit of attribution. We present CAMS, a Claim-Anchored Multi-document Summarization framework that (i) extracts atomic claims with token-level provenance from every source document, (ii) clusters equivalent claims across documents while flagging inter-source conflicts, (iii) selects a support-aware and salient subset, and (iv) rewrites the selection into a summary in which every sentence is anchored to a support-checked claim that links back to one or more source spans. Because content is localized before it is realized, the pipeline is attribution-oriented by construction and faithfulness-oriented by construction: it structurally preserves fine-grained, multi-source traceability while using support-aware selection, constrained rewriting, and verification to encourage, rather than guarantee, factual faithfulness. We evaluate quality, faithfulness, and localization on MultiNews, analyze conflict handling on DiverseSumm, and test zero-shot transfer on WCEP, using a two-regime protocol that separates reference-free citation quality from gold-aligned localization accuracy, and we add an evaluator-decoupled audit that tests citation precision with a support model never used for selection or verification. CAMS matches strong end-to-end and span-attribution baselines on summary quality while substantially improving faithfulness and citation precision, lifting multi-source attribution accuracy by roughly two-thirds, and exposing a controllable faithfulness--coverage trade-off that end-to-end models leave implicit.
### Title:
          An LMM for Precisely Grounding Elements in Documents
 - **Authors:** Yijian Lu, Chuangxin Zhao, Kai Sun, Lei Hou, Juanzi Li, Ji Qi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual grounding in documents is a crucial ability for Large Multimodal Models (LMMs) in areas such as document understanding, deep research and document error detection. However, existing approaches exhibit poor grounding precision in text-rich document images, often failing to accurately locate the critical document elements needed for reliable reasoning. To address this gap, we introduce PreciseDoc, an LMM specifically designed for precise element grounding and can be further optimized for Document VQA tasks. Specifically, to enhance the basic localization capability, we construct challenging training data by two pipelines capable of mass-producing high-quality documents with paired metadata of fine-grained coordinates, including synthetic hand-filled documents with camera effects. The model develops more real-world functions beyond straightforward localization of single text, such as locating personal information from CVs. Furthermore, we introduce a training paradigm for visual grounded reasoning where the grounding and reasoning are supervised jointly with reinforcement learning to improve the contribution of the grounded evidence. A comprehensive evaluation on various benchmarks demonstrates the advantage of the proposed data and methods in document spatial grounding and document understanding.
### Title:
          VeryTrace: Verifying Reasoning Traces through Compilable Formalism and Structured Verification
 - **Authors:** Ninghan Zhong, Ahmet Ege Tanriverdi, Kaan Kale, Sriram Vishwanath
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-step reasoning with Chain-of-Thought (CoT) prompting remains fragile: logical errors or hallucinations in early steps silently propagate, producing confident but incorrect conclusions. This paper presents VeryTrace, a zero-shot verification-and-repair framework that formalizes natural-language reasoning traces into a structured, compilable representation. VeryTrace introduces a Domain-Specific Language (DSL) that (i) makes step dependencies explicit, (ii) mechanizes quantitative content as executable expressions, and (iii) structures semantic inferences via deduction schemas. Our hybrid verifier combines deterministic checks for computational correctness, dependency resolution, and constraint satisfaction with targeted LLM audits for non-mechanizable semantic judgments, enabling step-level error localization and repair. Across three diverse domains-competition mathematics (AIME 2025), robotics planning (LLM-BabyBench), and kinship reasoning (CLUTRR), VeryTrace improves accuracy over zero-shot baselines on state-of-the-art LLMs without requiring domain-specific training or in-context examples, demonstrating that formalized trace verification achieves both precision and generalization.
### Title:
          From Open Waters to Enclosed Cabins: ProteusVPR for Cross-Scene Visual Place Recognition in Maritime Perception and Cabin Inspection
 - **Authors:** Zexi Chena, Zitai Huang, Qiwen Gu, Zhiqi Li, Shengli Dong, Chenlei Wang, Junqiao Zhao, Hongdong Wang, Bing Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous robotic inspection in maritime environments presents unique challenges for Visual Place Recognition (VPR) due to cross-scene perceptual shifts. Robots navigating ship-borne environments must transition between visually distinct domains: open decks with sparse textures and severe illumination changes, and enclosed cabins with repetitive structures and high visual ambiguity. Existing VPR methods, designed primarily for urban or indoor scenes, fail to generalize reliably across these starkly different scenarios. To address this, we propose ProteusVPR, a two-stage retrieval-refinement framework. The first stage employs any standard VPR model for initial image retrieval. The second stage introduces a geometric-visual estimation network that fuses the retrieved image with two temporally preceding frames, incorporating geometric descriptors, a local affine coordinate system, and camera azimuth encoding to achieve precise localization. To support this task, we introduce the XHZ dataset, an 8K-panoramic ship-borne dataset collected from an operational vessel, featuring multi-floor cabin structures, deck transition zones, and strict query-database separation for rigorous evaluation. Extensive experiments on the XHZ dataset demonstrate that ProteusVPR consistently improves the localization accuracy across multiple VPR backbones, reducing mean localization error by over 60\% on average and that ProteusVPR offers an effective and robust solution for precise visual localization in challenging, cross-scene maritime environments.
### Title:
          ActiveScope: Actively Seeking and Correcting Perception for MLLMs
 - **Authors:** Yajing Wang, Chao Bi, Junshu Sun, Shufan Shen, Zhaobo Qi, Shuhui Wang, Qingming Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Large Language Models (MLLMs) have demonstrated impressive vision-language understanding, yet still struggle with fine-grained perception in high-resolution images. While existing training-free methods typically rely on attention-based localization or coarse-to-fine search, they are often misled by distractors and fail to locate multiple targets. Our investigation attributes these failures to Contextual Dominance, where salient distractors overwhelm target attention and cause inaccurate localization, and Semantic Bias, where global semantics cause the model to fixate on the most salient concept, resulting in incomplete localization in multi-object scenarios. Built on these insights, we propose ActiveScope, a training-free framework that enhances MLLMs by actively seeking and correcting perception. ActiveScope features two modules. The Semantic Anchor Localization (SAL) utilizes fine-grained semantic anchors to independently localize key targets, thereby mitigating semantic bias. The Interference-Suppressed Refinement (ISR) refines localization by suppressing attention on salient distractions to overcome contextual dominance. Extensive experiments on high-resolution image understanding benchmarks demonstrate that ActiveScope outperforms existing training-free methods (e.g., 96.34 percent accuracy on $V^{*}$ Bench), validating the superiority of the active search and self-correction paradigm. Our code is available at this https URL.
### Title:
          Decentralized Pose Graph Riemannian Optimization for Object-based Multi-Robot SLAM
 - **Authors:** Yixian Zhao, Yan Huang, Yang Xu, Liang Li, Jinming Xu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pose graph optimization (PGO) is a key back-end component for state estimation in networked multi-robot simultaneous localization and mapping (SLAM). In object-based multi-robot SLAM, the problem becomes more tightly coupled because robots must jointly estimate both their trajectories and the poses of persistent objects observed by multiple agents. Existing decentralized solutions often assume that the communication graph closely matches the physical interaction topology, which is restrictive in realistic deployments where communication is sparse, intermittent, or time-varying. This paper presents a fully decentralized Riemannian optimization framework for object-based multi-robot PGO that decouples the coupled estimation problem via a consensus mechanism, enabling flexible communication topologies. To improve convergence under limited communication budgets, we further develop a distributed approximate-Newton scheme that exploits local second-order information while operating directly on the SE(d) manifold to preserve geometric consistency, and we establish the convergence to Riemannian first-order stationary points and provide a local condition-number analysis explaining the benefit of approximate second-order information over first-order Riemannian descent. The resulting method reduces iteration count and communication overhead without sacrificing estimation accuracy. Extensive evaluations on public benchmarks, large-scale simulations, and real-world multi-robot experiments demonstrate improved accuracy, runtime efficiency, scalability across network topologies, and robustness to communication failures.
### Title:
          VistaRef: Boosting Visual Spatial Orientation Awareness for Pointing-to-Object Detection
 - **Authors:** Ling Li, Zhizhen Cai, Xinkun Wu, Ziyu Zhu, Jiaqing Lyu, Bowen Liu, Zhidong Deng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Grounding deictic gestures in natural images is fundamental to AR and human-robot collaboration, providing a basis for seamless spatial interaction. While Transformer-based visual models have achieved significant progress in general object detection, their global attention mechanisms often neglect micro-geometric relationships, degrading orientation accuracy. In pointing tasks, this deficiency manifests as an inability to accurately capture the pointing ray implied by finger poses, which results in pointing drift and localization ambiguity when dealing with distant or densely packed objects. To address this, we propose VistaRef, a framework designed to explicitly enhance spatial orientation awareness. First, we develop the Local Hand Entity Modeling (LHEM) module, which incorporates hand-pose embeddings to strengthen the model's capability to capture subtle finger deviations. Second, drawing inspiration from multi-view geometry, we construct the Geometric Ray Modeling (GRM) module to transform implicit orientation information into explicit spatial geometric features, guiding feature aggregation and deep fusion via attention mechanisms. Furthermore, we introduce a novel Orientation-Consistent Alignment Loss (OCAL) to synergistically supervise hand presence and pointing consistency, ensuring that all architectural improvements collectively serve the core objective of spatial localization. Experimental results demonstrate that VistaRef significantly outperforms the baseline, achieving a 14-point absolute gain in grounding accuracy. Qualitative analysis further confirms that VistaRef effectively models the geometric correlation from hand to target, bridging the spatial perception gap inherent in traditional Transformers for complex scenarios. Code: this https URL.
### Title:
          ForensicsTok: Forensics-Guided Tokenized Modeling for Image Tampering Localization
 - **Authors:** Lei Xu, Haowei Wang, Shen Chen, Taiping Yao, Bin Li, Changsheng Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-modal Large Language Models (MLLMs) offer powerful reasoning for forensic tasks, yet existing approaches utilizing exogenous segmentation decoders often suffer from suboptimal localization. The reliance on stitched pipelines introduces information bottlenecks during backpropagation, which dilutes spatial signals and is limited by semantic priors of the segmentor. To address these limitations, we propose ForensicsTok, which reformulates image manipulation localization as an autoregressive sequence generation task. ForensicsTok directly generates spatially grounded token sequences, enabling precise mask prediction without intermediary supervision. Specifically, we introduce a Token Splatting Decoder (TSD) to map tokens to binary masks via codebook-aware code smoothing, which mitigates sharp gradients from deterministic detokenizers. Furthermore, to capture diverse tampering clues, we propose a Hierarchical Expert Fusion (HEF) module that injects multi-scale features from a forensic expert model. This unified architecture effectively compensates for the lack of forensic priors in standard MLLMs. Extensive experiments on six benchmarks show that ForensicsTok substantially improves over existing MLLM-based baselines and slightly improves over strong forensic expert baselines, while exhibiting stronger robustness to perturbations.
### Title:
          Jolia: Concept-Level Vision-Language Alignment for 3D CT Contrastive Learning
 - **Authors:** Julien Khlaut, Charles Corbière, Baptiste Callard, Amaury Prat, Leo Butsanets, Antoine Saporta, Théo Danielou, Leo Machado, Korentin Le Floch, Tom Boeken, Pierre Manceron, Corentin Dancette
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language contrastive pretraining has become the dominant recipe for 3D medical foundation models, leveraging the large volumes of paired scans and reports produced in clinical practice. However, medical images usually span dozens of organs, and radiological reports are much longer than typical natural image captions and are composed of multiple structured sections. CLIP-style pretraining compresses this structure by encoding each modality into a single global token, at the risk of losing important details. We introduce ConQuer (Concept Queries), an image-text pretraining method that augments CLIP's global alignment with a set of localized alignments, one per concept. ConQuer splits the report into concept-specific sections and learns cross-attention queries that pool the matching image features without using any segmentation mask or spatial supervision. Contrastive learning is then applied independently for each concept. Concepts can be any unit of semantic localization; here, they are anatomical regions, one query per organ or gross body region. As a byproduct, each query learns attention maps focused on its concept, providing built-in spatial interpretability. We use ConQuer to train Jolia, a 3D CT foundation model on chest and abdominal CT. Jolia consistently outperforms a CLIP baseline on findings classification, report generation, and cross-center transfer, and sets a new state of the art across multiple public benchmarks. Jolia's weights will be released upon acceptance.
### Title:
          SER: Learning to Ground Video Reasoning with Semantic Evidence Rewards
 - **Authors:** Sheng Xia, Zhengqin Lai, Tianxiang Jiang, Kanghui Tian, Shoujun Zhou, Bin Li, Yi Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video MLLMs often struggle with fine-grained spatio-temporal reasoning, sometimes generating correct answers based on irrelevant frames or objects. Although outputting spatio-temporal evidence during reasoning is a promising direction, existing RL frameworks typically rely on geometry-only (IoU) rewards, which can be sensitive to boundary perturbations and overlook semantic alignment. To address this, we propose Semantic Evidence Reward (SER), which reformulates spatio-temporal evidence grounding as a constrained verification task. Instead of computing pixel-level overlap, SER uses a referee VLM as a local checker to evaluate model-generated evidence claims across two dimensions: relevance and localization quality, combined with a temporal penalty. This design reduces the reliance on dense box annotations and enables training directly on standard video QA data. On the V-STAR benchmark, SER achieves 49.6% mLGM, improving by 3.0 points over the strong evidence-grounded baseline Open-o3-Video, demonstrating its potential in enhancing both answer accuracy and evidence grounding.
### Title:
          UniDrive: A Unified Vision-Language and Grounding Framework for Interpretable Risk Understanding in Autonomous Driving
 - **Authors:** Xiaowei Gao, Pengxiang Li, Yitai Cheng, Ruihan Xu, James Haworth, Stephen Law, Yun Ye
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent multimodal large language models (MLLMs) have shown strong potential for autonomous driving scene understanding, yet existing methods still face a fundamental trade-off between temporal reasoning and spatial precision. Models that rely on single-frame or low-resolution inputs often miss small, distant, or partially occluded hazards, while language-centric driving models frequently provide limited grounded evidence for their explanations. To address this gap, we propose UniDrive, a unified visual-language and grounding framework for interpretable risk understanding in autonomous driving. UniDrive combines a temporal reasoning branch that models scene dynamics from multi-frame visual input with a high-resolution perception branch that preserves fine-grained spatial details from the latest frame. The two branches are integrated through a gated cross-attention fusion module, enabling dynamic context to be aligned with precise spatial evidence. Based on the fused representation, UniDrive jointly generates natural-language risk descriptions and grounded bounding-box outputs for risk objects. Experiments on the DRAMA-Reasoning benchmark show that UniDrive outperforms representative image-based and video-based baselines in both captioning and risk-object grounding. In particular, UniDrive achieves the best overall performance on the validation split and demonstrates clear advantages in small-object localization, zero-shot generalization to NuScenes and BDD100K, and human-rated interpretability and trustworthiness. These results suggest that explicitly combining temporal semantics and high-resolution perception provides a stronger foundation for interpretable and safety-oriented autonomous driving systems. The code is available at this https URL.
### Title:
          Compact Object-Level Representations with Open-Vocabulary Understanding for Indoor Visual Relocalization
 - **Authors:** Zhaopeng Cui, Jiarui Hu, Jingbo Liu, Boming Zhao, Xiyue Guo, Boyin Feng, Haocheng Peng, Yujun Shen, Hujun Bao, Guofeng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Indoor visual relocalization plays a critical role in emerging spatial and embodied AI applications. However, prior research was predominantly devoted to low-level vision schemes, struggling to perceive scene semantics and compositions, which limits both interpretability and applicability. In this paper, we explore the issue of how to organize rich object information in a scene, including semantics, layout, and geometry, into a structured map representation, thereby utilizing object units exclusively to drive the camera relocalization task. To this end, we propose OpenReLoc, a camera relocalization system designed to provide scene understanding and accurate pose estimation capabilities. Leveraging recent foundation models, we first introduce a multi-modal mechanism to integrate open-vocabulary semantic knowledge for effective 2D-3D object matching. Additionally, we design object-oriented reference frames as position priors, paired with a reference frame selection strategy based on the Distance-IoU (DIOU), enabling extension to scalable scenes. Moreover, to ensure stable and accurate pose optimization, we also propose a dual-path 2D Iterative Closest Pixel loss guided by object shape. Experimental results demonstrate that OpenReLoc achieves superior relocalization recall and accuracy across various datasets. Our source code will be released upon acceptance.
### Title:
          Counting Trees from Satellite Imagery with Noisy Supervision
 - **Authors:** Dimitri Gominski, Maurice Mugabowindekwe, Qiue Xu, Xiaowei Tong, Martin Brandt, Hieu Le, Rasmus Fensholt, Dimitris Samaras, Loic Landrieu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Counting individual trees is a fundamental task for environmental monitoring, yet remains largely unexplored with satellite imagery. At these resolutions, isolated trees may still be identifiable, but crown boundaries become ambiguous in dense forests, making the notion of an individual tree inherently ill-defined. Moreover, large-scale manual annotations of individual trees are prohibitively expensive. While scalable supervision can be derived from airborne LiDAR, the resulting annotations are noisy and difficult to exploit effectively. We address these challenges by formulating tree counting as a spatial density matching problem supervised through Unbalanced Optimal Transport. This formulation naturally accommodates both precise localization of isolate trees and robust density estimation in dense forests. We further introduce a self-correction mechanism that leverages transport residuals to progressively refine noisy supervision during training. We evaluate our approach on TinyTrees, a new benchmark spanning three continents and three satellite sensors, comprising over 215 million tree annotations (including 773K manually verified instances) across 23,000 this http URL. Our method consistently outperforms detection-based, regression-based, and transport-based distribution-matching baselines, demonstrating the effectiveness of unbalanced transport and reliability-aware supervision for large-scale tree counting from satellite imagery. Code, data and models are available at this https URL.
### Title:
          Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM
 - **Authors:** Leshu Li, Jie Peng, Yang Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has garnered significant attention in Simultaneous Localization and Mapping (SLAM) due to its advances in capturing fine-grained geometry features and synthesizing novel views. For SLAM in large-scale scenes, such as autonomous driving, 3DGS-SLAM faces a critical limitation: memory consumption increases continuously over time as Gaussian points accumulate, leading to poor memory efficiency and limiting its applicability. In this work, we propose a rendering-area-aware pruning strategy that selectively removes Gaussians based on their contribution to the effective rendering area, rather than solely relying on Gaussian-level heuristics such as opacity or gradient magnitude. This perspective directly targets the sources of memory redundancy, effectively reducing the peak memory footprint of 3DGS-SLAM during runtime. Evaluations on the EuRoC and KITTI datasets demonstrate that our method consistently outperforms existing pruning approaches in large-scale outdoor scenes, achieving over 60% memory reduction and more than 2 times FPS improvement while preserving localization and mapping accuracy. These results highlight rendering-area-aware pruning as a promising direction for scaling 3DGS-SLAM to real-world autonomous driving scenarios. Our code is publicly available at this https URL.
### Title:
          EG-VQA: Benchmarking Verifiable Video Question Answering with Grounded Temporal Evidence
 - **Authors:** Linpeng Huang, Weixing Chen, Zexin Chen, Yang Liu, Liang Lin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in Video Large Language Models (Video-LLMs) have yielded promising performance on video question answering (VideoQA). Nevertheless, existing benchmarks are predominantly evaluated through answer correctness, while the grounding of predictions in relevant video evidence remains largely unexamined. This disconnect between answer generation and evidence understanding motivates the construction of the Evidence-Grounded Video Question Answering Benchmark (EG-VQA), an open-ended evaluation protocol in which each QA pair is explicitly annotated with supporting temporal evidence, thereby requiring joint reasoning and precise evidence localization. EG-VQA is comprised of 2,067 videos and 11,838 QA pairs with fine-grained evidence annotations. To evaluate predicted evidence, Evidence-Grounded F1 (EG-F1) is introduced as a unified metric in which temporal alignment and semantic consistency against ground-truth evidence are jointly measured. Experimental evaluation reveals that even strong proprietary models struggle to accurately ground their predictions, exposing a fundamental discrepancy between answer correctness and faithful evidence localization. To bridge this gap, EG-Reasoner, an evidence-grounded reasoning model trained with explicit supervision, is proposed. State-of-the-art performance is achieved among open-source models, with results competitive against proprietary systems, particularly pronounced gains are observed on reasoning-intensive tasks such as counterfactual questions. These findings demonstrate that scaling alone is insufficient for robust video understanding and that structured evidence supervision is essential for the development of more reliable and interpretable VideoQA systems.
### Title:
          Vision-Language Model Reasoning for Contextual Semantic Mapping in Intralogistics
 - **Authors:** Marvin Rüdt, Hao Pang, Constantin Enke, Zäzilia Seibold, Kai Furmans
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous mobile robots operating in intralogistics environments rely on geometric maps for localization and navigation, but lack semantic understanding of objects and their contextual properties. We present a contextual semantic mapping pipeline that combines SLAM-based geometric mapping, SAM-based instance segmentation, instance clustering, and VLM multi-view reasoning to produce a contextual semantic map representation encoding geometric structure, object class, and object movability. By aggregating observations across multiple viewpoints and querying a VLM in a zero-shot, open-vocabulary setting, the pipeline infers contextual object properties--here demonstrated through movability--without requiring task-specific training or predefined object categories. We evaluate three VLMs under two prompting strategies and conduct a component-wise analysis of the pipeline. The proposed pipeline achieves 98.93 % mIoU for semantic classification and 89.17 % mAcc for object movability estimation. Component analysis identifies VLM reasoning as the primary bottleneck for contextual understanding and instance clustering as the main limitation for panoptic performance. The resulting semantic map supports context-aware filtering and robust navigation in dynamic intralogistics environments.
### Title:
          MANGO: Automated Multi-Agent Test Oracle Generation for Vision-Language-Action Models
 - **Authors:** Pablo Valle, Shaukat Ali, Aitor Arrieta, Lionel Briand
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models are emerging robotic control systems that integrate perception, language understanding, and action generation in a unified architecture. Existing testing approaches for VLA-enabled robots rely on manually constructed symbolic test oracles that determine task success from final environment states. These oracles are costly to construct, require domain expertise, and are often tightly coupled to specific tasks and environments, limiting scalability and reuse. Furthermore, they provide only end-state assessments of task outcomes, offering limited insight into intermediate behavior and fault localization. To address these limitations, we introduce MANGO, a multi-agent framework that automatically generates fine-grained oracles from natural-language descriptions of robotic tasks. MANGO first generates a reusable library of atomic tasks, then generates simulator-grounded oracle definitions for each atomic task, and finally produces executable fine-grained oracles by decomposing complex instructions into ordered sequences of atomic actions and corresponding oracles. The framework uses collaborative Generator, Assessor, and Judge agents that iteratively refine generated artifacts through structured feedback. We evaluate MANGO on the LIBERO_10 and RoboCasa Humanoid Tabletop benchmarks. Results show that MANGO generates executable, fine-grained oracles that detect a similar number of failures as symbolic oracles while accurately localizing them and providing richer diagnostic information. Through ablation studies, we further analyzed component contributions and the effect of initial task set, while preserving oracle quality. Overall, the results show the feasibility and effectiveness of test oracle generation for VLA-enabled robots testing.
### Title:
          SHERLOC: Structured Diagnostic Localization for Code Repair Agents
 - **Authors:** Hovhannes Tamoyan, Sean Narenthiran, Erik Arakelyan, Mira Mezini, Boris Ginsburg
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM agents solve repository-level coding tasks through multi-turn tool use, but utilize half their budget on locating faults before editing. Dedicated localization frameworks have emerged, yet are still evaluated as file retrieval rather than actionable diagnosis, producing locations without the diagnostic context a repair agent needs. We introduce SHERLOC (Structured Hypothesis-driven Exploration and Reasoning for Localization), a training-free framework pairing a reasoning LLM with compact repository tools and self-recovery, without fine-tuning or multi-agent orchestration. SHERLOC reaches state-of-the-art localization across model scales: 84.33% accuracy@1 on SWE-Bench Lite and 81.27% recall@1 on SWE-Bench Verified; at ~30B parameters, it matches or outperforms other agentic methods. Injecting our locations and diagnostic findings into repair agents yields, on average, +5.95 pp resolve rate on SWE-Bench Verified while cutting localization and total tokens by 36.7% and 23.1%.
### Title:
          Accuracy and Satisfaction in Multi-Turn LLM Dialogues for NFR Assessment
 - **Authors:** Ali Pourghasemi Fatideh, Wilder Baldwin, Maria Dhakal, Collin McMillan, Sepideh Ghanavati
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM-based dialogue assistants have become mainstream tools for software developers, yet current evaluation benchmarks focus exclusively on functional correctness. This leaves a critical gap in assessing the quality and accuracy of these conversations when handling Non-Functional Requirements (NFRs), which are inherently vague, context-dependent, and involve many parts of a program. Evaluating how well these systems support collaborative reasoning about NFRs requires methods that go beyond single-turn accuracy to capture both the correctness of the system's outputs and the quality of the multi-turn interaction. In this paper, we investigate the accuracy and quality of multi-turn conversations between developers and an LLM-based agent in the domain of Health Insurance Portability and Accountability Act (HIPAA) regulatory compliance. We hired 49 programmers to interact with GitHub Copilot to assess 148 HIPAA-derived NFRs against the iTrust codebase, a system designed to comply with HIPAA regulations, across three dimensions: requirement satisfaction level, reasoning, and code localization. We find that developers tend to agree with LLM assessments, but accuracy against expert ground truth is low. We model user satisfaction and find that longer system responses and more information-providing turns negatively affect user satisfaction, whereas proactive interactions positively affect it. Our findings provide insights for designing LLM-based dialogue systems that support NFR assessment.
## Keyword: transformer
### Title:
          From Heuristics to Transformers: A Comprehensive Survey of Type Inference from Stripped Binaries
 - **Authors:** Hua Zheng, Yuhang Guo, Kuanishbay Sadatdiynov, Cheng Wen, Muhammad Sadiq, Dugang Liu, Jawwad Ahmed Shamsi, Anam Qureshi
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The recovery of high-level type information from stripped binaries-executables devoid of symbol tables and debugging information-is a cornerstone of software reverse engineering, vulnerability analysis, and decompilation. This survey tracks the evolution of binary type inference from early rule-based heuristics and static analysis to modern deep learning architectures. We analyze the shift from "duck typing" and constraint-solving techniques (e.g., BITY, BinSub) to context-aware neural models (e.g., EKLAVYA, CATI) and finally to state-of-the-art Transformer and Graph Neural Network (GNN) architectures (e.g., SeeType, TYGR). We identify core challenges, including optimization-induced semantics loss and structural type recovery, and propose future research directions in neuro-symbolic inference.
### Title:
          ModTGCN: Modularity-aware Graph Neural Networks for Text Classification
 - **Authors:** Rajarshi Misra, Aditya Sharma, Vinti Agarwal, Hari Om Aggrawal
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph-based text classification models typically rely on local neighborhood aggregation and overlook global community structure, despite semantic document graphs exhibiting strong class-consistent clustering. Ignoring this can blur class boundaries and lead to over-smoothing. We propose ModTGCN, a modularity-aware graph neural network for text classification that jointly optimizes cross-entropy and a modularity-based auxiliary objective to promote class-coherent document communities while preserving discriminative representations. The modularity term is computed on a document-document similarity graph derived from transformer embeddings (pretrained or fine-tuned). To improve scalability, we decouple the original heterogeneous TextGCN graph into separate document-word and word-word components, achieving 2x-10x faster training. We further study graph construction strategies, label-aware edge reweighting, and supervision choices for modularity optimization. Experiments on five benchmarks show consistent gains, with larger improvements on complex, low homophily datasets such as Ohsumed and 20NG.
### Title:
          Evaluating LLM Usage for Efficient and Explainable Numerical and Classified Implicit Sentiment Analysis of Product Desirability
 - **Authors:** Sherri Weitl-Harms, John Hastings
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Human-Computer Interaction (cs.HC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Qualitative product feedback can reveal nuanced user experiences, but its implicit sentiment is difficult to measure. This paper presents a scalable and interpretable framework that uses large language models (LLMs) to quantify product desirability from such data. Using two Product Desirability Toolkit (PDT) datasets from ZORQ and CARMA comprising 106 respondent term groupings with gold-standard human annotation, zero-shot continuous numerical sentiment scoring and categorical sentiment classification are evaluated without relying on explicit review scores. Across the datasets, LLMs generated numerical sentiment scores directly from qualitative responses and closely matched expert labels, achieving Pearson correlations up to 0.97 and classification accuracy up to 94%. LLMs maintained robustness even when handling data presented in multiple forms and consistently expressed high confidence. In contrast, lexicon-based and transformer baselines did not produce statistically significant results. Among the models tested, GPT-4o-mini achieved performance comparable to larger models at 94% lower cost, supporting scalable deployment. The framework also incorporates model confidence ratings and human-readable rationale explanations (xAI), improving interpretability, transparency, and trust while supporting practical use in product satisfaction assessment. In general, using the PDT tool as a survey method along with a cost efficient LLM for sentiment analysis has the potential to provide for product evaluation with results that are rich in terms of sentiment scores (both numerical and classified sentiment) and in terms of the high-level user impressions of the product that can be used to identify ideas for product development and improvement, as well as marketing ideas for target audiences.
### Title:
          From Spatial to Spectral: An Efficient, Frequency-Guided Feature Representation Learner for Small Object Detection
 - **Authors:** Yuhan Rui, Shihan Qiao, Yibin Lou, Mingxi Yu, Yutong Wan, Yanqiao Chen, Dongsheng Hou, Zhen Cao, Athena Zhuoming Zhong, Qi Hao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient small object detection is bottlenecked by the inherent feature scarcity of tiny targets, which is further aggravated by operations of spatial-domain detectors that indiscriminately discard critical high-frequency details. Recovering these fragile cues within the spatial domain is notoriously difficult, as it often requires computationally expensive architectural upscaling that inadvertently amplifies background noise. To bridge this gap, we propose a paradigm \textbf{shift from spatial to spectral} feature processing, introducing a holistic solution with the following novelty: (1) A versatile \textbf{Frequency-Guided Feature Representation framework} that generalizes across diverse detector architectures (both CNN and Transformer-based), offering a robust alternative to spatial-only feature extraction; (2) The unified \textbf{Decompose--Enhance--Reconstruct (DER)} operator, instantiated via three \textbf{lightweight, plug-and-play} modules -- Wavelet-Difference Gate (WDG), Log-Gabor Enhancer (LGE), and Frequency-Driven Head (FDHead) -- to systematically inject frequency-aware modulation into the backbone, neck, and head. This mechanism decouples feature modeling from resolution reduction, capturing discriminative high-frequency components to enable accurate localization with significantly reduced parameter redundancy; (3) Extensive validation on multi-domain benchmarks (VisDrone2019, UAVDT, TinyPerson, DOTAv1) demonstrating consistent gains. Notably, our proposed \textbf{DERNet} series outperforms YOLOv11 models under the same scale while requiring \textbf{only 1/6 of the parameters}, backed by rigorous spectral diagnostics and error decomposition analysis.
### Title:
          Deciphering Fingerprints of 3D Molecular Surfaces for Accurate Epitope Prediction
 - **Authors:** Fang Wu, Weihao Xuan, Jure Leskovec, Yejin Choi, Li Erran Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Molecular surfaces encode the geometric and physicochemical patterns that determine antibody-antigen recognition, central to epitope prediction. However, existing methods rely on sequences or backbone structures and struggle to capture discontinuous, surface-driven epitopes. This study presents SurfBind, a surface-centric learning framework for epitope prediction that operates directly on molecular surface representations. SurfBind integrates geometric and physicochemical cues through a Transformer-based architecture with patch-level surface modeling, binder-aware cross-attention, and a hierarchical coarse-to-fine prediction paradigm. Experiments on challenging epitope identification benchmarks, including SAbDab and DB5.5, demonstrate that SurfBind achieves state-of-the-art performance and strong generalization across unseen antibodies and conformational states, highlighting the value of interaction-aware surface modeling for understanding the crucial mechanisms of protein-protein interactions.
### Title:
          Mind the Heads: Topological Representation Alignment for Multimodal LLMs
 - **Authors:** Davide Caffagni, Alberto Compagnoni, Federico Melis, Sara Sarto, Pier Luigi Dovesi, Mark Granroth-Wilding, Marcella Cornia, Lorenzo Baraldi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Representation alignment has emerged as an effective approach to improve Multimodal Large Language Models (MLLMs) by regularizing their internal representations toward those of an external vision encoder. However, existing methods typically align a fixed layer of the language backbone, overlooking the fine-grained structure of Transformer models. In this work, we propose Head-Wise Representation Alignment (HeRA), a method that enforces cross-modal alignment at the level of individual attention heads. Our approach is grounded in the Platonic Representation Hypothesis, focusing on preserving the topological structure of representations (i.e., their local neighborhood relationships) across modalities. Following the Mutual K-Nearest Neighbor (MKNN) alignment metric, we introduce a contrastive objective that acts as a differentiable proxy for matching local structures. HeRA applies this objective during multimodal training to specific attention heads in the LLM, selected by their alignment score according to the MKNN metric. Counterintuitively, we find that aligning the least aligned heads yields the largest gains. Extensive evaluations across multiple MLLMs and 18 benchmarks demonstrate that HeRA consistently improves performance on challenging vision-centric tasks and serves as an effective regularizer against visual hallucinations by naturally curbing the over-reliance on linguistic priors. Our code is publicly released.
### Title:
          Unified Multi-Task Relevance Modeling for E-Commerce: Comparing Task Routing Architectures Across LLMs and Cross-Encoders
 - **Authors:** Md Omar Faruk Rokon, Jhalak Nilesh Acharya, Shasvat Desai, Hong Yao, Kuang-chih Lee
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 How can we build a single relevance model that handles six different entity pair relationship types in e commerce from query product matching to product type similarity when each task has different data volumes, different semantic requirements, and potentially conflicting learning signals? This question is important because current industry practice relies on separate models for each task, preventing knowledge transfer and producing inconsistent relevance signals. Our work is driven by the following insight: encoder based and decoder only models encode task identity through different mechanisms, so the choice of task routing architecture how task identity is communicated to the shared model affects these two families in asymmetric ways. As our key novelty, we combine three ideas: (a) a unified multi task framework that jointly trains on six entity pair tasks under a shared three point relevance scale, (b) a systematic comparison of three task routing architectures (text prefix routing, multi head classification, and multihead with private transformer layers) across both LoRA adapted LLMs and fully finetuned cross encoders, and (c) a majority vote ensemble that exploits the diversity induced by private layer routing. First, we show that the MHP Ensemble (multi head with private layers) achieves 89.96% accuracy on 453K test examples the highest across all configurations . Second, we show that removing text prefixes without private layers causes severe degradation for decoder only LLMs while cross encoders remain robust , suggesting an encoder decoder asymmetry in task identity encoding. Third, we show that multi task training yields up to 14% improvement on low resource tasks over single task baselines.
### Title:
          DREG: A Layer-Wise Jacobian Regularization as a General-Purpose Penalty
 - **Authors:** Rowan Martnishn
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a large-scale empirical study isolating the contributions of the Derivative Regularization penalty (DREG). Across a fully-crossed factorial sweep of 960 experiments spanning 4 activations, 6 regularizers, 8 datasets, and 5 random seeds, we ask: when, where, and why does DREG work? Our results establish three principal findings. First, DREG achieves the highest overall and clean-regime accuracy among all regularizers evaluated (significantly so against the unregularized baseline, Weight Decay, and IGPen; Wilcoxon $p \leq 0.031$). It ranks second in noise robustness behind Spectral Normalization (SN) - the only two layer-wise regularizers in the study. Second, DREG is globally the best-performing regularizer under GELU, the default activation in modern transformer architectures, particularly on both messy vision and messy NLP benchmarks, suggesting direct applicability to frontier deep learning settings. Third, DREG's advantage over competing regularizers is most pronounced under data scarcity, consistent with its role as a geometric inductive bias that substitutes for the regularizing effect of data volume. Throughout, DREG is applied with a single fixed hyperparameter $\lambda = 10^{-2.5}$ and no per-dataset tuning, supporting its characterization as a plug-and-play regularizer for neural networks with nontrivial Jacobian structure. These findings are consistent with DREG's design: concentrating regularization pressure on layers where the activation derivative is largest, rather than constraining the network uniformly.
### Title:
          Learning the Koopman Operator using Attention Free Transformers
 - **Authors:** Mohammed Nagdi, Evangelos-Marios Nikolados, Alexey Yermakov, Mars Gao, Nathan Kutz, Filippo Menolascina
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Systems and Control (eess.SY); Molecular Networks (q-bio.MN)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning Koopman operators with autoencoders enables linear prediction in a latent space, but long-horizon rollouts often drift off the learned manifold, leading to phase and amplitude errors on systems with switching, continuous spectra, or strong transients. We introduce two complementary components that make Koopman predictors more robust. First, we add an attention-free latent memory (AFT) block that aggregates a short window of past latents to produce a corrected latent before each Koopman update. Unlike multi-head attention, AFT operates in linear time and adds only $\approx$30k parameters ($3d^2 + T^2$, fewer than matched multi-head attention), yet captures the local temporal context needed to suppress error divergence. Second, we propose dynamic re-encoding: lightweight, online change-point triggers (EWMA, CUSUM, and sequential two-sample tests) that detect latent drift and project predictions back onto the autoencoder manifold. Across three benchmark systems -- Duffing oscillator, Repressilator, IRMA -- our model consistently reduces error accumulation compared to a Koopman autoencoder and matched-capacity multi-head attention. We also compare against GRU and Transformer autoencoders, evaluated both from initial conditions and with a 50-step context, and find that Koopman+AFT (with optional re-encoding) attains markedly lower long-horizon error while maintaining lower inference latency. We report improvements over horizons up to 1000 steps, together with ablations over trigger policies. The result is a fast, compact predictor that stays on the learned manifold over long horizons.
### Title:
          Can Language Model Agents be Helpful Circuit Explainers in Mechanistic Interpretability?
 - **Authors:** Ayan Antik Khan, Harsh Kohli, Yuekun Yao, Huan Sun, Ziyu Yao
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability has made substantial progress in automatically localizing circuits, but explaining what localized components do remains labor-intensive and difficult to standardize. In this work, we study whether language model (LM) agents can assist with this explanation problem once a circuit has already been identified. We introduce AgenticInterpBench, a benchmark for circuit explanation built from 84 semi-synthetic transformer circuits with 163 component-level annotations. We propose HyVE (Hypothesize, Validate, Explain), an agentic explainer that analyzes each component through an iterative loop of observation, hypothesis generation, and causal validation, eventually producing a component-level explanation and a circuit-level task description. Across four LM backbones, HyVE recovers useful component- and task-level explanations, but no backbone is uniformly best. Our analysis shows that strong backbones usually form observation-grounded hypotheses, while failures more often arise later in the validation loop, through incomplete validation plans, code execution errors, or unresolved hypotheses. A case study on an arithmetic circuit in Llama-3-8B shows that the same formulation can extend beyond semi-synthetic benchmarks to naturally trained models. Overall, LM agents are promising circuit explainers, but reliable validation remains the key obstacle.
### Title:
          End-to-End Radar and Communication Modulation Recognition with Neuromorphic Computing
 - **Authors:** Xiaohu Li, Chongxiao Qu, Caiyong Lin, Chenxiao Dou, Wei Hua
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although deep learning-based methods can achieve high accuracy in automatic modulation recognition (AMR) tasks, their high computational cost makes it difficult to strike a balance between accuracy and power consumption, thereby limiting their application on resource-constrained platforms. Neuromorphic architectures that perform spike-driven inference with modest energy budgets have recently been explored for vision and timeseries tasks. Motivated by these works, we propose EMRFormer, a novel end-to-end spiking nerural network (SNN) architecture that applies spike-driven transformer to the constraints of neuromorphic hardware for AMR. The model incorporates an adaptive spike encoder and Integer Leaky Integrate-and-Fire neurons to mitigate the degradation of effective information and enhance SNN representational capacity. By integrating spike-separable Convolution Neural Networks (SSCNN) into Spike-Driven Transformers (SpikeFormer), EMRFormer effectively extracts multi-scale temporal features from the raw IQ waveforms. We validate our approach across various mainstream datasets, the experimental results show that EMRFormer achieves state-of-the-art interms of accuracy, outperforming all the baselines. Furthermore, the model maintains strong performance in low signal-to-noise(SNR) environments and reduces theoretical energy consumption by over 90%. Finally, we evaluate our model on a KA200 neuromorphic chip. The results show that our model achieves up to 5 times reduction in power compared to running on a 3090 GPU or an Orin NX. This work demonstrates a promising pathway for AMR on resource-constrained devices.
### Title:
          NeuroSonic: Conditional Flow Matching for EEG-to-Speech Reconstruction
 - **Authors:** Wenhao Gao, Yifan Wang, Yijia Ma, Carl Yang, Wen Li, Chenyu You
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing continuous speech from scalp electroencephalography (EEG) remains fundamentally challenging. EEG provides a weak, spatially diffuse, and highly variable measurement of distributed cortical activity, whereas speech is organized as a coherent acoustic trajectory with strong harmonic and temporal structure. The resulting mismatch makes waveform regression unstable and causes stochastic multi-step generation to be sensitive to artifact-dependent conditioning and subject variability. We introduce NeuroSonic, a conditional flow-matching framework for EEG-to-speech reconstruction. Instead of predicting waveforms directly or refining them through stochastic denoising, NeuroSonic learns a deterministic probability-flow velocity field that transports a noise-corrupted acoustic state toward clean speech under EEG conditioning. EEG and audio are embedded into a shared token space and processed by a time-conditioned gated Transformer that parameterizes the transport ordinary differential equation. This formulation models trajectory evolution explicitly while avoiding iterative stochastic sampling. We evaluate NeuroSonic on the CineBrain and EAV benchmarks under cross-subject evaluation. Across both datasets, the proposed method improves distributional realism, spectral fidelity, and perceptual quality over representative GAN-, diffusion-, and mean-flow baselines, with up to a 26.3\% gain in overall perceptual quality. The performance gap is most evident in artifact-heavy segments, where conditioning variability is strongest. These findings indicate that deterministic conditional transport provides a stable and effective formulation for EEG-driven speech reconstruction. Code is available at this https URL .
### Title:
          Predicting Poets' Origins from Verse: A Computational Analysis of Regional Linguistic Fingerprints in the Complete Tang Poems
 - **Authors:** Chi-Sheng Chen, Hung-Yun Liu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We ask whether the geographic origin of Tang-dynasty poets leaves a detectable linguistic trace in their work. Aggregating every poem attributed to each author in the Complete Tang Poems (Quan Tang Shi) and linking poets to their administrative circuit of origin via the China Biographical Database (CBDB), we build a poet-level corpus of 357 poets across the ten Tang circuits and frame origin prediction as multi-class classification. Using character $n$-gram TF-IDF together with interpretable domain features (imagery, season, and allusion), classical and neural models predict a poet's broad region (South vs.\ North) at $0.69$ accuracy, well above the $0.53$ majority baseline, and finer circuit-level origin above chance. Beyond classification, three findings emerge. (i) Linguistic distance between circuits grows with geographic distance (Mantel $r=0.40$, $p\approx0.09$ over nine circuits), evidence of a distance-decay effect in poetic language. (ii) The signal interacts with time: South/North separability is at chance in the High Tang and strongest in the Late Tang, consistent with court-driven homogenization at the empire's height followed by regional divergence. (iii) The model's confident errors are historically meaningful -- in the Early Tang, every misclassification is a southern poet read as northern, reflecting the prestige of the northern court idiom. We further show that, when given the whole corpus through a hierarchical frozen-encoder representation, a classical-Chinese transformer (GuwenBERT) only matches -- not beats -- simple TF-IDF, and that combining them adds nothing, indicating that character $n$-grams already capture the regional signal. Our results position interpretable machine learning as a hypothesis generator for literary history.
### Title:
          Flood Mapping from RGB imagery using a Vision Foundation Model
 - **Authors:** Vladyslav Polushko, Tilman Bucher, Ronald Rösch, Thomas März, Markus Rauhut, Andreas Weinmann
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Timely, high-resolution maps of flood extent around settlements are essential for emergency response and damage assessment. We consider airborne RGB imagery for flood mapping as it can be collected rapidly at low cost. To produce flood maps, deep learning models for water segmentation are often used. CNN based and small vision transformer models are used. However, they need much data for adaptation to a change of scenery, i.e., another flooding event. Vision foundation models or large vision transformers are known to generalize across domains. Recently, foundation models for Earth observation became available. They are pretrained on satellite data, whose spatial resolution, viewing geometry, and radiometry differ from nadir RGB imagery. Thus, adaptation is required. We investigate how a satellite-pretrained Earth observation foundation model can be adapted to centimeter-scale floodwater mapping from RGB imagery. Specifically, we fine-tune a model we call Prithvi-2.0-UPN consisting of the Prithvi-EO-2.0-600M Vision Transformer combined with a UPerNet decoder for binary water segmentation on two RGB datasets (BlessemFlood21, NeuenahrFlood). In a first experiment we observe that Prithvi-2.0-UPN reaches state-of-the-art results on BlessemFlood21 and NeuenahrFlood, when trained on their datasets. In a second experiment we show that Prithvi-2.0-UPN performs better than state-of-the-art baseline models for transfer to a new flood event (trained on BlessemFlood21, tested on NeuenahrFlood) in a zero-shot setting. However, the performance indicates room for improvement. In this respect, we investigate in a third experiment how performance improves when further fine-tuning the models with small shares of NeuenahrFlood training data: Prithvi-2.0-UPN improves the fastest and reaches almost the performance level when fully trained on NeuenahrFlood, indicating transfer capabilities.
### Title:
          Spectral Evolution-Guided Token Pruning in Multimodal Large Language Models
 - **Authors:** Bin Chen, Yuxiang Cai, Yadan Luo, Yi Zhang, Jianwei Yin, Zhi Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reducing visual token redundancy is critical for accelerating Multimodal Large Language Models (MLLMs) without degrading cross-modal reasoning performance. Existing token pruning methods typically rely on single-layer signals, such as attention scores or token similarities, which overlook the cross-layer transformation of visual representations and may exhibit positional bias in multimodal token sequences. To address this limitation, we propose a training-free token pruning framework based on Cross-Layer Spectral Evolution (CLSE). Instead of measuring token importance from single-layer feature magnitudes, CLSE quantifies how token representations evolve across Transformer layers in the frequency domain. This evolution reflects the transition from high-frequency structural details to low-frequency semantic abstractions. We observe that tokens with stronger spectral redistribution across layers are more likely to be semantically active and should therefore be preserved. By modeling cross-layer token dynamics, CLSE provides a stable importance criterion that mitigates positional bias. Extensive experiments on both image and video benchmarks demonstrate that CLSE achieves a superior trade-off between efficiency and accuracy under aggressive token reduction. Across multiple MLLMs, CLSE reduces FLOPs, KV cache memory, and latency while maintaining competitive or improved performance.
### Title:
          Lightweight Transformer Models for On-Device Fault Detection: A Benchmark Study on Resource-Constrained Deployment
 - **Authors:** Disha Patel
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 On-device fault detection enables real-time diagnostics without cloud dependency, but deploying machine learning models on resource-constrained hardware demands careful tradeoffs between accuracy, latency, and model size. We present a benchmark comparing traditional ML methods (Random Forest, XGBoost, SVM, Logistic Regression) against lightweight transformer architectures (DistilBERT, TinyBERT-6L, TinyBERT-4L, MobileBERT) for binary fault detection across three public datasets: NASA C-MAPSS turbofan degradation, SECOM semiconductor manufacturing, and UCI AI4I 2020 predictive maintenance. We evaluate classification performance (F1-score, AUC), model size, and CPU inference latency, and further assess INT8 dynamic quantization and a two-stage adaptive inference pipeline. Our results reveal that on well-separated sensor data (C-MAPSS), lightweight transformers match traditional ML at 87.8% F1 but at 100x the model size and 9000x the latency. TinyBERT-4L emerges as the most deployment-friendly transformer at 55 MB and 18 ms CPU latency. INT8 quantization reduces size by 25% while preserving 86.9% F1. Our adaptive pipeline, routing 97.9% of predictions through a quantized triage model and only 2.1% to a larger expert, achieves 87.6% F1 at 19.5 ms average latency. On severely imbalanced datasets (SECOM, UCI-PM), both traditional and transformer methods struggle significantly, highlighting fundamental limitations of current approaches for extreme class imbalance in fault detection. All code is publicly available.
### Title:
          Deep Learning Approaches for 3D Medical Scene Completion: From Geometric Modeling to Generative Paradigms
 - **Authors:** Afifa Khaled, Said Jadid Abdulkadir, Majdy Mohamed Eltayeb Eltahir
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Three-dimensional scene completion has evolved as a major problem in computer vision and robotics, and its applications are diverse, including autonomous navigation and augmented reality. In this study, a systematic review has been conducted to compile the research contributions made in the last ten years, i.e., 2016 to 2026, which has revolutionized the field from the voxel semantic completion paradigm represented by SSCNet to the latest paradigm that combines generative diffusion priors with real-time rendering using a Gaussian splatting technique. The evolution in representation paradigms, such as voxel grids, point learning, implicit neural fields, transformer networks, diffusion networks, and the latest paradigm based on rendering-aware 3D Gaussian primitives, has been discussed in this study. A comprehensive analysis has been carried out on the contributions made in the last ten years, and a taxonomy has been developed to provide a clear idea about the contributions made in the field. The study has also discussed the research contributions made in the field, along with the challenges that still need to be addressed. Finally, the study has presented a research agenda that will provide a clear idea about the directions that can be followed in the development of the next-generation system
### Title:
          TuringViT: Making SOTA Vision Transformers Accessible to All
 - **Authors:** Qiman Wu, Hanlin Chen, Lyujie Chen, Rui Xin, Jianlei Zheng, Mingyuan Wang, Jiahui Hu, Da Zhu, Yuecheng Ma, Yuhua Wei, Yizhao Wang, Hua Zhou, Yuheng Zhang, Anhua Liu, Shaman Tang, Yue He, Pengfei Diao, Shuang Su, Haotong Xin, Weichao Huang, Hang Zhang, Xianming Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern VLMs and VLA systems commonly adopt off-the-shelf ViTs such as SigLIP2 as visual encoders, but diverse downstream requirements in latency, temporal modeling, and VLM integration often call for customized SOTA-level ViTs. Training such encoders remains beyond the reach of much of the community, as it requires massive image-text data, while standard softmax attention makes high-resolution or dynamic-resolution pretraining prohibitively costly and often forces low-resolution pretraining followed by post-hoc adaptation. TuringViT addresses these challenges with three key designs: Turing Linear Attention (TLA) for efficient sequence modeling, VISTA-Curation to construct supervision-rich image-video training data, and native dynamic-resolution pretraining that supports flexible inputs from the start and transfers seamlessly to downstream VLMs. As a result, TuringViT outperforms leading open-source ViT baselines with only 10% of the data, achieves stronger downstream VLM performance, and delivers substantially better latency scaling on high-resolution inputs. Our scaling-law analysis further shows that TuringViT continues to improve predictably with curated data scale, far from saturation. Its fast adaptation, hardware-friendly design, and efficient deployment have made it a unified visual foundation across XPeng's AI systems. More broadly, TuringViT provides a reproducible pipeline that dramatically lowers the cost for the community to train, customize, and deploy SOTA-level ViTs, moving toward making such Vision Transformers accessible to all.
### Title:
          SURGELLM: Rethinking Multi-Task Evaluation through Task-Aware Feature Gating with Class-Balanced Normalization
 - **Authors:** Noor Islam S. Mohammad, Ulug Bayazit
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-tuned encoders deployed across heterogeneous NLP tasks face three compounding problems: mismatched inductive biases, class-imbalance corruption of feature statistics, and no mechanism to condition attention on external lexical knowledge. We introduce \textbf{\surgellm}, a unified transformer framework that addresses each with a dedicated lightweight module: a \emph{surgical feature gate} (learned per-dimension sigmoid over curated lexical indicators and \texttt{[CLS]}; provably degenerates to identity when features are uninformative), \emph{task-conditioned prefix tokens} (quantized feature values and task identity prepended to every input), and \emph{Instance-Weighted Normalization} (IWN; removes class-prior bias from gate statistics). We prove an excess-risk bound linking gate benefit to \emph{surgical feature alignment}. Across four tasks, SST-2, multi-hop retrieval, LLM-prompt attribution, and authorship detection, covering 17,830 examples and eleven model variants over three seeds, the IWN variant achieves macro-F1 \textbf{0.940} ($+0.036$ over the strongest non-IWN baseline; $+0.130$ on authorship detection). A random-vocabulary control ($-0.028$ avg.\ F1) confirms gains are lexical, not parametric. Code, vocabularies, and a $99.5\%$-recovery auto-extraction recipe are released.
### Title:
          TrOCR for Medieval HTR: A Systematic Ablation Study with Cross-Dataset Validation
 - **Authors:** Sachin Sharma, Michele Flammini, Federico Simonetta
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Digital Libraries (cs.DL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-tuning transformer-based handwritten text recognition (HTR) models on medieval manuscripts is challenging because these models are pre-trained on modern text and must adapt to a very different visual domain. This paper studies how three controllable fine-tuning choices (contrast normalization, data augmentation, and layer freezing) affect recognition accuracy when adapting TrOCR to small historical datasets. We run controlled experiments on a 13th-century Italian manuscript (I-CT 91 "Cortonese") and replicate the same experimental grid on the public READ-16 benchmark as robustness evidence. On Cortonese, our best configuration achieves 8.03% character error rate (CER). Statistical comparisons across 13 configurations show that freezing up to three encoder layers or six decoder layers does not significantly harm accuracy, while deeper freezing becomes progressively detrimental. Removing contrast normalization (CLAHE) yields 7.84% CER, comparable to a domain-specialized baseline, suggesting strong optimization can reduce reliance on image preprocessing. Cross-dataset validation on READ-16 shows that decoder freezing thresholds transfer more robustly than encoder thresholds, and combined freezing strategies require dataset-specific re-validation. Finally, we use Grad-CAM gradient attributions and decoder cross-attention maps to diagnose error patterns and failure modes revealed by the ablations. Source code is available at this https URL
### Title:
          Transformer-Based Language Models Across Domain Verticals: Architectures, Applications and Critical Assessment
 - **Authors:** Guruprakash J, Krithika L.B
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based language models have become the default substrate for natural language processing and the pace of new releases has made it hard for practitioners to separate durable ideas from the noise of incremental announcements. This review works at two levels. At the level of mechanism, we organise the main transformer families into a working taxonomy, covering encoder-only, decoder-only, encoder-decoder, long-context, permutation-based, and generator-discriminator variants. We then extend the discussion to post-2023 developments that changed the picture in practice: instruction tuning, reinforcement learning from human feedback, direct preference optimisation, mixture-of-experts scaling, retrieval augmentation and the current flagship model families from OpenAI, Anthropic, Google, Meta, Mistral and DeepSeek. At the level of use, we survey deployments across healthcare, finance, legal, education, customer service, creative writing and scientific work. Based on this we link each to the specific capabilities that make a transformer the appropriate tool. The contribution of this paper is a critical assessment that is based on the survey. We compare architectures on four axes that matter to deployment decisions, we quantify the trade-off between parameter count and energy cost. We also discuss how alignment methods, data provenance and benchmark saturation change what it means to call a model "state of the art". The final section lists the research questions that we think deserve more attention.
### Title:
          AutoSpecNER: A Fine-Grained Named Entity Recognition Dataset for Vehicle Specification Extraction
 - **Authors:** Jordan Lee, Filippos Ventirozos, Abdirahman Abdullahm, Ioanna Nteka, Peter Appleby, Matthew Shardlow
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vehicle advertisements contain rich specification information, but automotive NER resources remain limited. We introduce AutoSpecNER, an expert-annotated dataset for fine-grained entity recognition in vehicle listings. The dataset includes 659 advertisements from a popular car-selling website, with over 10,000 entities annotated across 15 categories, including MODEL, ENGINE_SPEC, and BATTERY_CAPACITY. Annotation quality was validated through inter-annotator agreement, achieving an average score of 91.5%. We benchmark rule-based extraction, fine-tuned transformer encoders, and large language models. DeBERTa achieves the best performance with a 90% micro-F1 score, outperforming the rule-based baseline (43%) and the strongest large language model (77.8%).
### Title:
          Parallel Manifold Steering: Efficient Adaptation of Large Associative Memories via Residual Energy Shaping
 - **Authors:** Kanishk Awadhiya
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Transformer models function as Dense Associative Memories (DAMs), retrieving knowledge via high-dimensional attractor dynamics driven by the self-attention mechanism \citep{ramsauer2020hopfield, wu2024attention}. However, adapting these frozen memory systems to new tasks presents a fundamental ``Plasticity-Stability'' dilemma. Current methods either risk catastrophic interference by modifying synaptic weights directly (e.g., LoRA) \citep{hu2021lora} or degrade associative capacity by clogging the retrieval buffer with static prompt tokens (e.g., VPT) \citep{jia2022vpt}. In this work, we propose \textbf{H-Res} (Hierarchical Residual Steering), a mechanism that modulates the effective energy landscape of the Transformer without altering its global equilibrium or expanding its sequence length. By formulating adaptation as a control problem on the activation manifold \citep{chen2018neuralode}, H-Res learns a state-dependent vector field that steers token trajectories into task-specific basins of attraction. We formally prove that H-Res preserves the attention entropy of the foundation model and facilitates Neural Collapse \citep{papyan2020prevalence}. Empirically, Manifold Steering outperforms global weight modification by 26\% on associative retrieval tasks and eliminates the computational overhead of prompt-based methods, scaling effectively to structured domains \citep{zha2023vtab}.
### Title:
          NoContactNoWorries: Estimating Contact through Vision and Proprioception for In-Hand Dexterous Manipulation
 - **Authors:** Soham Patil, Avirup Das, Sourabh Bhosale, Spandan Roy
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Perceiving physical contact is fundamental to dexterous manipulation. While robots often rely on dedicated hardware tactile sensors, humans exhibit a remarkable ability to infer contact by integrating visual information with an innate sense of their body's pose and movement. Inspired by this embodied perceptual skill, we investigate whether a robot can learn to infer contact from vision, an approach that also offers a scalable alternative to tactile hardware specifically for binary contact estimation, which faces practical challenges in cost, fragility, and integration. We present NoContactNoWorries, a transformer-based multimodal framework that fuses RGB-D vision with the robot's proprioception to infer binary contact states as a pseudo-tactile signal for hand-object interactions. We validate by training a single contact prediction model on multiple objects and show that the inferred contact signal supports downstream reinforcement learning agents for in-hand object reorientation, generalizing to novel objects. Experiments in both simulation and on a real-world robot validate our approach, highlighting the feasibility of inferring contact from vision and proprioception. Project Page: this https URL
### Title:
          An LLM-based Two-Stage Transformer Framework for Cross-Domain Bearing Fault Diagnosis with Limited Data
 - **Authors:** Jinghan Wang, Feng Cheng, Wentao Wu, Hang Li, Gaoliang Peng, Tianchen Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bearing fault diagnosis faces critical challenges when dataset heterogeneity, operating condition variations, and limited labeled data occur simultaneously in industrial environments. Existing approaches address these issues in isolation and rely on implicit feature alignment, limiting effectiveness under concurrent challenges. This paper proposes a knowledge-guided two-stage transfer learning framework that employs a lightweight GPT-2-style Transformer with causal self-attention for hierarchical feature extraction from vibration signals, establishing explicit pathways where pre-trained encoder weights and fault prototype embeddings serve as knowledge carriers from multi-source pre-training to target adaptation. The framework addresses the dual-shift challenge through multi-source learning for generalizable representations, prototype-based knowledge modulation for target adaptation, and taxonomy-adaptive classification for seamless transfer across heterogeneous fault categories. Experimental validation on four real-world datasets demonstrates 92.61% average accuracy with only 10% labeled target data, outperforming state-of-the-art methods by 17.24 percentage points, establishing a practical pathway toward cost-effective predictive maintenance in Industry 4.0 applications.
### Title:
          VistaRef: Boosting Visual Spatial Orientation Awareness for Pointing-to-Object Detection
 - **Authors:** Ling Li, Zhizhen Cai, Xinkun Wu, Ziyu Zhu, Jiaqing Lyu, Bowen Liu, Zhidong Deng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Grounding deictic gestures in natural images is fundamental to AR and human-robot collaboration, providing a basis for seamless spatial interaction. While Transformer-based visual models have achieved significant progress in general object detection, their global attention mechanisms often neglect micro-geometric relationships, degrading orientation accuracy. In pointing tasks, this deficiency manifests as an inability to accurately capture the pointing ray implied by finger poses, which results in pointing drift and localization ambiguity when dealing with distant or densely packed objects. To address this, we propose VistaRef, a framework designed to explicitly enhance spatial orientation awareness. First, we develop the Local Hand Entity Modeling (LHEM) module, which incorporates hand-pose embeddings to strengthen the model's capability to capture subtle finger deviations. Second, drawing inspiration from multi-view geometry, we construct the Geometric Ray Modeling (GRM) module to transform implicit orientation information into explicit spatial geometric features, guiding feature aggregation and deep fusion via attention mechanisms. Furthermore, we introduce a novel Orientation-Consistent Alignment Loss (OCAL) to synergistically supervise hand presence and pointing consistency, ensuring that all architectural improvements collectively serve the core objective of spatial localization. Experimental results demonstrate that VistaRef significantly outperforms the baseline, achieving a 14-point absolute gain in grounding accuracy. Qualitative analysis further confirms that VistaRef effectively models the geometric correlation from hand to target, bridging the spatial perception gap inherent in traditional Transformers for complex scenarios. Code: this https URL.
### Title:
          VisCritic: Visual State Comparison as Process Reward for GUI Agents
 - **Authors:** Jiachen Qian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 GUI agents powered by vision-language models show strong potential for automating digital tasks, yet frequently fail in long-horizon scenarios due to the absence of step-level verification. Existing process reward models verify actions through textual reasoning alone, missing the visual nature of GUI state changes. We introduce VisCritic, a visual process reward framework that verifies agent actions by directly comparing pre-action and post-action screenshots in visual feature space. VisCritic employs a Siamese vision transformer to extract change-aware representations, coupled with an Action-Aware Critic Head that jointly evaluates action success, task progress, and error type. A critic-training data construction pipeline generates weakly supervised samples from existing trajectories without additional human labels for critic training. Experiments and offline analyses across five benchmarks demonstrate that VisCritic serves as a plug-and-play enhancement for diverse GUI agents, generally improving benchmark metrics while providing visual diagnostic cues.
### Title:
          Heterogeneous Knowledge Distillation via Geometry Decoupling and Momentum-Aware Gradient Regulation
 - **Authors:** Wuming Yang, Xiang Zhang, Hongmin Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Heterogeneous Knowledge Distillation (HKD) aims to transfer knowledge across varying architectures (e.g., from Transformer to CNN) but inherently suffers from severe training instability. We reveal that this instability stems from two highly coupled challenges: massive feature norm discrepancies that cause optimization drag, and severe gradient conflicts between the primary and distillation objectives arising from distinct inductive biases. To achieve stable distillation, we propose SPOFA, a framework built upon a novel Feature and Gradient Dual Stabilization mechanism. Specifically, at the feature level, we introduce a LayerNorm-based decoupling projector that explicitly decouples feature magnitude from direction, creating a bounded and stable space for semantic alignment. At the gradient level, we propose a momentum-driven Exponential Moving Average (MEMA) dynamic scaler. By establishing a robust historical baseline of the optimization trajectory, MEMA actively evaluates instantaneous gradient conflicts and adaptively penalizes harmful distillation signals, guaranteeing stable convergence. Importantly, SPOFA achieves this dual stabilization with an extremely lightweight parameter footprint. Extensive experiments on two mainstream benchmarks demonstrate that SPOFA achieves state-of-the-art accuracy, significantly outperforming computationally expensive methods while introducing only minimal computational overhead compared to standard baselines.
### Title:
          Uncertainty-Aware Longitudinal Forecasting of Alzheimer's Disease Progression Using Deep Learning
 - **Authors:** Arya Hariharan, Shreyank N Gowda, Anala M R
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Longitudinal modelling of Alzheimer's disease progression is clinically useful only if it can describe not just the most likely next diagnosis, but how a patient may evolve over time and how reliable that forecast is. Most deep learning approaches reduce this problem to single-step classification, treating cognitively normal, mild cognitive impairment, and dementia as flat categories while providing limited insight into how uncertainty accumulates across future visits. We propose a probabilistic framework that combines ordinal diagnosis prediction, multi-horizon trajectory generation, and decomposed uncertainty estimation. A Temporal Fusion Transformer encoder is adapted with a CORAL ordinal output layer, asymmetric loss weighting, and converter oversampling to respect disease-stage ordering and improve sensitivity to MCI-to-dementia transitions. Conditioned on the learned patient-context representation, an autoregressive Mixture Density Network generates five-year probabilistic trajectories for diagnosis state, CDR Sum of Boxes, MMSE orientation, and hippocampal volume. On ADNI, the model outperforms linear, recurrent, and transformer baselines for next-visit diagnosis prediction, with the strongest gains on MCI-versus-dementia discrimination. Generated trajectories achieve near-nominal 90% credible interval coverage, widening uncertainty across the forecast horizon, and biomarker dynamics consistent with expected Alzheimer's disease progression. We further separate aleatoric from epistemic uncertainty using analytic mixture variance and a five-member bootstrap ensemble, which provides the strongest encoder diversity and output-level epistemic signal. Epistemic uncertainty is higher for rare progression archetypes, MCI and dementia patients, and under external evaluation on OASIS-3, where it increases alongside prediction error.
### Title:
          Harmonic: Hierarchical State Space Models for Efficient Long-Context Language Modeling
 - **Authors:** Petr Nyoma
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Harmonic, a hierarchical state space model (SSM) for language modeling. The architecture stacks three recurrent levels at progressively slower timescales; each level receives the prediction error of the level below as input, rather than its raw hidden state. On enwiki8 with equal token budgets, Harmonic outperforms a comparable Transformer (28M params) by +1.4% at 1K tokens, +6.7% at 8K tokens, and +11.4% at 32K tokens (bpt, lower is better). It also outperforms Mamba at every tested length by 0.7--1.8%. At 64K tokens, both Mamba and Transformer run out of memory on an 80GB H100; Harmonic trains successfully, reaching 6.169 bpt. Results replicate on WikiText-103 (H-TF gap +1.7% to +7.2% across 1K--32K). At 1B parameter scale, replacing all attention layers in TinyLlama 1.1B with HarmonicBlock eliminates the RoPE positional encoding limit: the resulting Hallamonic model maintains stable loss across sequence lengths 1K--8K on two independent clean benchmarks (Lambada and fineweb-edu held-out), while TinyLlama degrades catastrophically past its 2K-token RoPE limit (gap: +9.4 bpt at seq=8K on Lambada). Compute is O(L) per forward pass vs. O(L^2) for attention. Logs: this https URL.
### Title:
          Decentralised AI Training and Inference with BlockTrain
 - **Authors:** Peter Toth
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Frontier AI training is increasingly shaped by access to dense, centrally controlled accelerator clusters. This creates a structural advantage for hyperscalers and large centralized laboratories, and makes open or independent AI efforts depend on scarce capital, privileged infrastructure, and data-center geography. We present Spheroid BlockTrain, a decentralized training protocol in which a model is partitioned into independently trainable blocks, each optimized on a local objective derived from the same global target and composed at inference into one model. On byte-level WikiText, BlockTrain reaches cross entropy 1.359 (perplexity 3.89), within about 0.04 CE of a same-setup end-to-end Transformer reference, while each active worker trains only one block and avoids full-model optimizer state. A shared six-worker block training run reaches CE 1.385 by averaging same-block updates into one assembled model. HTTP/TCP transport experiments move real serialized checkpoints and updates, including a public-IP three-host run that improves CE from 5.580 to 1.811 while moving 15.22 GB. For inference, the current BlockTrain path uses one block-stack traversal per full output and serves over direct TCP across three public-network GPU hosts up to a 75.80B-parameter logical fp16 shape, outperforming a matched plain-autoregressive TCP pipeline baseline because it emits a full sequence per WAN pipeline traversal rather than one token per traversal.
### Title:
          Can Scale Save Us From Plasticity Loss in Large Language Models?
 - **Authors:** J. Fernando Hernandez-Garcia, Tomás Figliolia, Beren Millidge
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The loss of plasticity - the ability of a network to learn new information after having already learned older information - is a fundamental challenge in creating artificial neural networks capable of continual learning. Although this phenomenon has been known for decades, it has mostly been studied in older, relatively small architectures and rarely in natural-language domains. To determine whether loss of plasticity remains a problem in the modern transformer-based LLM paradigm, we study plasticity loss in GPT-style Transformer models trained on a multilingual continual learning problem. Consistent with prior work, we find evidence of plasticity loss across models ranging from 5M to 314M non-embedding parameters, as measured by deterioration on a held-out Vietnamese probing task. We further find that the onset of plasticity loss follows a predictable scaling law, growing sublinearly with model size. These results suggest that larger models may delay the measurable effects of plasticity loss, but that increasing parameter count alone is likely to be insufficient to completely prevent it. We also find evidence of plasticity loss under stationary multilingual training, challenging the view that the phenomenon is exclusive to continual learning with abrupt task changes. Overall, our results suggest that even large Transformer language models trained on natural-language will eventually lose the ability to efficiently adapt to new data after sufficiently long training, in both continual and stationary settings.
### Title:
          Adaptive Hebbian Memory Routing in Vision Transformers for Few-Shot Learning
 - **Authors:** Mohammed Yusuf Mujawar, Noorbakhsh Amiri Golilarz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Few-shot image recognition requires models to adapt to new classes from a small labeled support set. Hebbian fast-weight memory can provide temporary associative information during an episode, but fixed memory behavior may not be appropriate for every few-shot task. In this work, we propose Adaptive Hebbian Routing for few-shot Vision Transformers. The method uses a lightweight MLP router to control the contribution of Hebbian memory, the strength of memory updates, and the retention of previous memory from support-set features. We study Adaptive Placement, Adaptive Plasticity, and Fully Adaptive Hebbian Routing. Experiments use ViT-Small, DeiT-Small, and Swin-Tiny under 5-way 1-shot evaluation on Omniglot, CIFAR-FS, and cross-domain transfer from CIFAR-FS to Omniglot. In the direct Swin comparison, fixed and adaptive Hebbian variants use the same memory location. Adaptive Plasticity improves the fixed Hebbian result from 96.74\% to 96.92\%, while Fully Adaptive Routing achieves the best result at 96.94\%. The fully adaptive Swin model also reduces inference time from 16.51 ms to 14.05 ms relative to fixed Hebbian Swin. On CIFAR-FS, adaptive variants improve performance across all three backbones, and the multi-shot evaluation shows that these gains remain useful as the number of support examples increases. These results show that adaptive plasticity and adaptive memory activation can improve few-shot Transformer representations beyond fixed Hebbian behavior.
### Title:
          DDStereo: Efficient Dual Decoder Transformers for Stereo 3D Road Anomaly Detection
 - **Authors:** Shiyi Mu, Zichong Gu, Zhiqi Ai, Yilin Gao, Shugong Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Stereo-based 3D object detection still faces two critical safety challenges: real-time performance and open-set generalization. Existing stereo 3D methods typically achieve twice the accuracy of monocular methods but suffer from significantly lower inference speeds, making them unsuitable for real-time applications. Meanwhile, recent advances in open-world detection have introduced open-set and open-vocabulary algorithms in monocular 2D and 3D settings, yet stereo-based open-set detection remains largely unexplored. To bridge this gap, we propose DDStereo, a novel Dual-Decoder Stereo Transformer for real-time open-set 3D object detection. DDStereo features two lightweight decoder branches: one for open-set foreground 2D detection and the other for 3D attribute regression. These decoders share object-level queries to achieve unified target-level alignment. To enhance inference efficiency, we designed a compact disparity feature extractor and a streamlined decoder architecture. Experiments on public stereo 3D benchmarks demonstrate that DDStereo achieves state-of-the-art accuracy under both closed-set and open-set protocols. Notably, our method surpasses existing stereo 3D detectors in inference speed and, for the first time, achieves real-time performance comparable to monocular approaches.
### Title:
          L3Cube-MahaPOS: A Marathi Part-of-Speech Tagging Dataset and BERT Models
 - **Authors:** Hariom Ingle, Ronit Ghode, Ishwari Gondkar, Jidnyasa Harad, Raviraj Joshi
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Part-of-Speech (POS) tagging is a foundational NLP task underpinning machine translation, information extraction, and syntactic parsing. Despite Marathi being spoken by over 83 million people and ranking among the top twenty most spoken languages worldwide, it remains severely under-resourced in annotated corpora and standardised evaluation benchmarks. Marathi presents unique challenges for computational modelling owing to its rich morphology, relatively free word order, lack of capitalisation conventions, and pervasive code-mixing with Hindi and English. We introduce L3Cube-MahaPOS, a gold-standard POS tagging dataset for Marathi comprising 32,354 manually annotated sentences drawn from news text. Annotation was performed entirely manually by a team of Marathi-proficient annotators following a 16-tag Universal Dependencies-aligned scheme. A structured preprocessing pipeline covering Unicode normalisation, Devanagari-aware tokenisation, and noise filtering ensures label consistency across all splits. We benchmark the dataset across six model families spanning HMM, CRF, BiLSTM, BiLSTM+CharCNN, MuRIL, and the Marathi-specific transformer MahaBERT-v2. The best system achieves 88.67\% token-level accuracy and a macro-F1 of 81.67% over 15 evaluated tag classes. We release the dataset, annotation guidelines, and trained model checkpoints to foster further research in Marathi NLP.
### Title:
          FLUX3D: High-Fidelity 3D Gaussian Generation with Diffusion-Aligned Sparse Representation
 - **Authors:** Haorui Ji, Weizhe Liu, Hongdong Li, Hengkai Guo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse voxel representation has emerged as a scalable foundation for image-to-3D Gaussian Splatting (3DGS) generation, yet current methods struggle to preserve high-frequency visual details of input images due to two structural bottlenecks. First, they adopt discriminative 2D features optimized for semantic abstraction to construct sparse voxel latents, which suppress reconstructive cues and induce a representation bottleneck. Second, in the generation stage, standard diffusion transformers lack effective mechanisms to align dense 2D image tokens with sparse 3D voxel latents, resulting in a cross-modal correspondence bottleneck. To address these issues, we propose FLUX3D, a scalable image-to-3DGS framework that boosts both representation learning and cross-modal alignment during generation. We first revisit 2D feature selection for sparse-voxel-based 3D representation learning, propose Diffusion-Aligned Structured Latents (DA-SLAT) and couple it with a decoder-only architecture to improve 3DGS reconstruction fidelity. We also design a sparse-structure-aware diffusion framework, which integrates the Sparse-structure Multimodal Diffusion Transformer (SMDiT) and Modal-Aware Rotary Positional Embedding (MARoPE) to achieve geometry-agnostic 2D-3D alignment. Extensive benchmark experiments demonstrate that FLUX3D yields substantial improvements in appearance fidelity and significantly outperforms all state-of-the-art (SOTA) methods in generating high-quality 3DGS assets.
### Title:
          DiffusionBench: On Holistic Evaluation of Diffusion Transformers
 - **Authors:** Xingjian Leng, Jaskirat Singh, Zhanhao Liang, Ethan Smith, Martin Bell, Aninda Saha, Yuhui Yuan, Liang Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion transformer (DiT) research on image generation has converged to a single evaluation setup: class-conditional generation on ImageNet. While methods improve the FID and related metrics, it is increasingly unclear whether they reflect real progress in generative modeling. The natural alternative, i.e., text-to-image (T2I) generation, is perceived as too costly or inconvenient to train and evaluate and is often skipped. We argue that this perception no longer holds. We introduce NanoGen, a unified DiT training and evaluation framework. NanoGen matches state-of-the-art DiT baselines on ImageNet and, with 12 lines of configuration change, also trains competitive text-to-image models. It currently supports RAE, VAE, pixel-space, and MeanFlow diffusion methods under both ImageNet and T2I setups. Under NanoGen, training T2I requires comparable compute to ImageNet. After training 21 latent diffusion models with NanoGen, we observe that method ranking shows no strong correlation between ImageNet and T2I generation: Pearson correlation is between -0.377 and -0.580 across three metrics. This suggests that a method which improves class-conditional ImageNet FID may show no corresponding improvement on T2I, clearly indicating the necessity of evaluating DiTs on both tasks. To this end, we summarize ImageNet and text-to-image results, which yields DiffusionBench, a holistic benchmark for DiT research. We recommend reporting DiffusionBench in place of ImageNet alone: methods that improve DiffusionBench are more likely to reflect broader progress.
## Keyword: autonomous driving
### Title:
          Beyond Bayer: Task-Optimal Sensor Co-Design for Robust Autonomous-Driving Segmentation
 - **Authors:** Reeshad Khan, John Gauch
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust perception underpins autonomous driving, and most recent progress comes from scaling the model-larger backbones, foundation models, and cooperative multi-agent fusion. We pursue a complementary, upstream question: what should the camera itself measure? Using a differentiable RAW-to-task pipeline, we decompose which sensor degrees of freedom benefit dense prediction. Learning the spectral colour-filter-array (CFA) weights is the dominant lever, improving mIoU by +0.017 (KITTI-360) and +0.023 (ACDC) over a fixed camera. In contrast, point-spread-function (optics) co-design is net-negative (-0.020 mIoU on KITTI-360) - a consequence of the data-processing inequality, which also bounds the task information that any downstream model, however large or cooperative, can recover. Noise co-optimisation is marginal, and counter to intuition enlarging the CFA tile beyond 2x2 consistently hurts, as the filters are confined to the rank three sRGB input. Because the intervention is at the sensor, the gains are model-agnostic; we validate robustness on ACDC's fog, night, rain, and snow, and conclude with a simple recipe: learn the 2x2 CFA weights and keep an identity PSF.
### Title:
          3DCarGen: Scalable 3D Car Generation via 3D-consistent Multi-view Synthesis
 - **Authors:** Hongli Xiao, Youjian Zhang, Yaohui Jin, Xiaoguang Ren, Wenjing Yang, Long Lan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-quality 3D vehicle assets are essential for autonomous driving simulation. Although multi-view diffusion-based paradigms enable controllable single-image reconstruction, they typically produce limited viewpoints and exhibit cross-view geometric inconsistencies, thereby reducing reconstruction fidelity in real-world scenarios. In this work, we introduce 3DCarGen, a scalable single-view 3D car generation framework designed for real-world images by synthesizing an arbitrary number of 3D-consistent multi-view images. Specifically, given a single image as input, we first synthesize a set of images from fixed viewpoints. These images are then fed into a feed-forward reconstruction model, resulting in a coarse 3D representation based on 3D Gaussian Splatting. Conditioned on this explicit 3D prior, our multi-view diffusion model generates 3D-consistent images from arbitrary camera viewpoints. We further extend a fast mesh reconstruction algorithm by incorporating color-normal joint optimization to recover detailed and coherent 3D vehicle models from the synthesized dense views. Extensive experiments on synthetic and real-world datasets demonstrate that our approach achieves robust geometric consistency and reconstruction fidelity compared to existing methods. Code and models will be released.
### Title:
          MM-TRELLIS: Point-Cloud Guided Multi-Modal 3D Vehicle Generation in Autonomous Driving
 - **Authors:** Hongli Xiao, Youjian Zhang, Yucai Bai, Chaoyue Wang, Yaohui Jin, Xiaoguang Ren, Wenjing Yang, Long Lan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recovering realistic 3D vehicle models from autonomous driving scenes is crucial for synthesizing training data and building simulation environment. However, most existing vehicle generation methods fail to fully exploit multimodal sensors i.e. multi-view images and LiDAR point clouds) and rely on neural rendering based reconstruction, leading to low-quality mesh. Recently, native 3D generative models have made significant progress, yet they are not built for arbitrary multi-view inputs and often struggle with in-the-wild driving images. In this work, we present MM-TRELLIS, a multi-modal version of TRELLIS for in-the-wild 3D vehicle generation that integrates LiDAR and image sensors from autonomous driving datasets into native 3D generative models. Specifically, multi-view images are cycled as conditioning inputs, while LiDAR point clouds provide test-time guidance to ensure geometric accuracy and cross-view consistency. During denoising, we first align the guidance point cloud with the model priors, then enforce consistency between the generated geometry and the guidance point cloud. Finally, we introduce a voxel filtering strategy based on the opacity of 3D Gaussian Splatting to suppress floaters and produce clean meshes. Comprehensive experiments on Waymo dataset demonstrate our method outperforms existing methods in high-fidelity 3D vehicle generation. Code is available at this https URL.
### Title:
          Open-Vocabulary BEV Segmentation with 3D-Aware Geometric Constraints
 - **Authors:** Hojun Choi, Seulbin Hwang, Dae Jung Kim, Kisung Kim, Hyunjung Shim, Jinhan Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bird's-eye view (BEV) perception fuses multi-camera images into a unified top-down representation for autonomous driving. Despite recent progress, state-of-the-art methods remain confined to closed-set scenarios, making them vulnerable to unpredictable real-world environments. In this work, we introduce open-vocabulary BEV segmentation (OVBS), which leverages vision-language models (VLMs) to recognize categories beyond the training set while maintaining precise BEV perception and real-time efficiency. A key challenge in OVBS lies in the 3D geometric inconsistency inherent in the ill-posed lifting of 2D VLM semantics into BEV. To address this, we propose OVBEVSeg, a geometry-aware OVBS framework that enhances efficient Gaussian splatting (GS)-based unprojection by leveraging robust 3D geometric constraints across three progressive stages: (1) 2D-to-BEV pseudo-labeling via reliable 3D projection for OV generalization; (2) joint 2D-BEV per-scene optimization with BEV structural constraints for 3D geometric consistency; and (3) 3D geometric distillation for online efficiency. On the nuScenes dataset, OVBEVSeg achieves state-of-the-art performance, outperforming closed-set methods by 15.3 mIoU on unseen categories. Remarkably, even with no novel-class ground-truth labels, it remains competitive with self- and semi-supervised baselines trained with up to 40% of ground-truth annotations. Furthermore, it achieves 2.5x faster inference with only 0.22x the memory consumption of projection-based methods. Project page: this https URL.
### Title:
          UniDrive: A Unified Vision-Language and Grounding Framework for Interpretable Risk Understanding in Autonomous Driving
 - **Authors:** Xiaowei Gao, Pengxiang Li, Yitai Cheng, Ruihan Xu, James Haworth, Stephen Law, Yun Ye
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent multimodal large language models (MLLMs) have shown strong potential for autonomous driving scene understanding, yet existing methods still face a fundamental trade-off between temporal reasoning and spatial precision. Models that rely on single-frame or low-resolution inputs often miss small, distant, or partially occluded hazards, while language-centric driving models frequently provide limited grounded evidence for their explanations. To address this gap, we propose UniDrive, a unified visual-language and grounding framework for interpretable risk understanding in autonomous driving. UniDrive combines a temporal reasoning branch that models scene dynamics from multi-frame visual input with a high-resolution perception branch that preserves fine-grained spatial details from the latest frame. The two branches are integrated through a gated cross-attention fusion module, enabling dynamic context to be aligned with precise spatial evidence. Based on the fused representation, UniDrive jointly generates natural-language risk descriptions and grounded bounding-box outputs for risk objects. Experiments on the DRAMA-Reasoning benchmark show that UniDrive outperforms representative image-based and video-based baselines in both captioning and risk-object grounding. In particular, UniDrive achieves the best overall performance on the validation split and demonstrates clear advantages in small-object localization, zero-shot generalization to NuScenes and BDD100K, and human-rated interpretability and trustworthiness. These results suggest that explicitly combining temporal semantics and high-resolution perception provides a stronger foundation for interpretable and safety-oriented autonomous driving systems. The code is available at this https URL.
### Title:
          Pocket-SLAM: Rendering-Area-Aware Pruning for Memory-Efficient 3DGS-SLAM
 - **Authors:** Leshu Li, Jie Peng, Yang Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has garnered significant attention in Simultaneous Localization and Mapping (SLAM) due to its advances in capturing fine-grained geometry features and synthesizing novel views. For SLAM in large-scale scenes, such as autonomous driving, 3DGS-SLAM faces a critical limitation: memory consumption increases continuously over time as Gaussian points accumulate, leading to poor memory efficiency and limiting its applicability. In this work, we propose a rendering-area-aware pruning strategy that selectively removes Gaussians based on their contribution to the effective rendering area, rather than solely relying on Gaussian-level heuristics such as opacity or gradient magnitude. This perspective directly targets the sources of memory redundancy, effectively reducing the peak memory footprint of 3DGS-SLAM during runtime. Evaluations on the EuRoC and KITTI datasets demonstrate that our method consistently outperforms existing pruning approaches in large-scale outdoor scenes, achieving over 60% memory reduction and more than 2 times FPS improvement while preserving localization and mapping accuracy. These results highlight rendering-area-aware pruning as a promising direction for scaling 3DGS-SLAM to real-world autonomous driving scenarios. Our code is publicly available at this https URL.
