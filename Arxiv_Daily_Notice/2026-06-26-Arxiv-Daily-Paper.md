# Showing new listings for Friday, 26 June 2026
## Keyword: SLAM
### Title:
          PanoImager: Geometry-Guided Novel View Synthesis and Reconstruction from Sparse Panoramic Views
 - **Authors:** Zhisong Xu, Takeshi Oishi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Panoramic sensing offers wide field-of-view coverage, yet 3D reconstruction from sparse panoramas remains challenging under rotation-dominant, weak-parallax motion. In such regimes, SfM/SLAM initialization is often ill-conditioned and unreliable. We present PanoImager, an SfM-free framework that combines feed-forward pose/depth priors, geometry-conditioned diffusion view completion, and depth-guided 3DGS optimization. Given only a few panoramic images, PanoImager decomposes them into local perspective views, synthesizes auxiliary observations to enrich sparse evidence, and stabilizes Gaussian optimization for improved cross-view consistency. Experiments on multiple benchmarks show improved stability under extreme sparsity, suggesting PanoImager as an offline/background component for map refinement when SfM/SLAM fails to initialize.
### Title:
          RayPE: Ray-Space Positional Encoding for 3D-Aware Video Generation
 - **Authors:** Minghao Yin, Jiahao Lu, Wenbo Hu, Wang Zhao, Shan Ying, Kai Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern video diffusion transformers position their tokens through RoPE on the (u,v,t) axes -- a description of the camera's sampling grid that says nothing about the 3D structure of the scene. We observe that the geometric relation between two camera rays is captured by the Plucker reciprocal product, which is bilinear in the two rays -- the same algebraic form as the dot product in Transformer attention. Building on this analogy, we propose RayPE, a positional-encoding extension that injects per-token 6D Plucker coordinates additively into the queries and keys of self-attention, with a query/key flip arrangement under which the symmetric identity configuration coincides exactly with the reciprocal product. The injection is additive, the resulting attention score decomposes into a content term, a geometry term, and two content and geometry cross-terms -- all of which our experiments find individually necessary. To make the encoding stable across video data with heterogeneous camera-translation scales (SfM, deep SLAM, metric), we further decouple ray direction from moment magnitude, gate the encoding by a learned function of the log-magnitude, and apply RMSNorm to align it with the QKNorm-normalized content branch. The full module adds less than 0.1% parameters to a pretrained video DiT, is zero-initialized to start from the pretrained weights, and improves camera controllability, cross-frame 3D consistency, and overall video quality on a four-dataset training mixture.
## Keyword: odometry
### Title:
          A Closed-Form 4-DoF Inter-Robot Pose Estimator using Bearing-only Measurements
 - **Authors:** Qixin De, Ao Zhuang, Yechen Zhang, Zhuozhou Qian, Danping Zou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bearing-odometry-based cooperative localization has attracted increasing research interest due to its minimal infrastructure requirements, low communication bandwidth and broad applicability in complex environments. However, existing 6-DoF approaches still face challenges in rapidly obtaining accurate and reliable inter-robot pose estimation, as the system is prone to observability degeneracy under specific motion patterns. To address these issues, we first propose a closed-form 4-DoF inter-robot pose estimator, which relaxes nonlinear constraints for rotations estimation and employs error projection for translations estimation. We then conduct a theoretical analysis of the system's observability, identifying degeneracy under two typical motion patterns: collinear and shape-preserving formations. The analysis further shows that the proposed 4-DoF system requires less stringent motion excitation for observability, enabling reliable estimation under a broader range of cooperative maneuvers. Furthermore, an observability test module is introduced to autonomously determine the optimal estimation instant, eliminating reliance on a predefined fixed-length sliding window. Extensive simulations and real-world experiments demonstrate that the proposed algorithm achieves higher estimation accuracy with significantly low computational cost, and the observability test module ensures estimation reliability while minimizing the data collection interval.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Unsupervised Memory-Enhanced Video Transformers: Obstacle Detection for Autonomous Agricultural Rover
 - **Authors:** Théo Biardeau (XLIM-ASALI, UFR SFA (Poitiers)), Anne-Sophie Capelle-Laizé (UP, XLIM-ASALI, XLIM-ASALI), Salwan Alwan, David Helbert (UFR SFA (Poitiers), XLIM-ASALI, LabCom I3M (Poitiers))
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While autonomous rovers have become indispensable to precision farming, achieving consistent operational safety remains a critical challenge. Conventional safety sensors, such as LiDAR, fail to detect obstacles positioned below the plant canopy, posing a significant risk. While camera-based supervised learning methods can detect common objects, they perform poorly when faced with obstacles that were not present in their training data. Actual unsupervised anomaly detection offers a solution by learning the normal visual patterns of an environment, but often fails for the dynamic scenes captured by a moving rover.\\ This paper introduces Video Memory Transformers for Anomaly Detection (VMTAD), a fully unsupervised method designed for real-time obstacle detection in dynamic agricultural scenes. VMTAD utilizes a transformer-driven architecture augmented with a dedicated memory module. This memory module leverages temporal context by processing encoded representations of preceding frames. This approach enables the system to effectively address the dynamic context caused by the robot's movement. The model is trained using only images that represent normal operation, requiring no data labels.\\ VMTAD was rigorously evaluated on the 'Grillion' agricultural rover. On a challenging rapeseed dataset, VMTAD achieved state-of-the-art performance, reaching a 0.973 detection and 0.997 segmentation Area Under the Receiver Operating Characteristic curve. A lightweight variant provides an optimal balance of high accuracy and real-time inference (14 ms), which is critical for safety, as confirmed by our analysis of the rover's total stopping distance.
### Title:
          Self-Supervised Tree-level Biomass Estimation in Urban Environments From Airborne LiDAR and Optical Observations
 - **Authors:** Jose Bermudez (1), Zilong Zhong (1), Dominic Cyr (2), Camile Sothe (3), Alemu Gonsamo (1) ((1) McMaster University, Hamilton, Ontario, Canada (2), Environment and Climate Change Canada, Montreal, Quebec, Canada, (3) Planet Labs PBC, San Francisco, California, USA)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Urban tree biomass remains less spatially explicitly quantified than biomass in managed forests because many estimates rely on inventories or coarse products that cannot resolve individual crowns or fine-scale heterogeneity. We present a crown-level above-ground biomass (AGB) framework for an 810~km$^2$ landscape in Ontario, Canada, using leaf-off airborne LiDAR (8--10~pulses~m$^{-2}$) and near-infrared RGB orthophotography (0.16--0.20~m) from 2018 and 2023. A dual-stream cross-attention network trained on rule-based pseudo-labels produced semantic marks for buildings, needleleaf trees, and deciduous trees, supporting crown delineation and functional-type assignment. On independently annotated withheld tiles, global/mean precision, recall, and Dice scores were 0.86, 0.83, and 0.84. Crowns were delineated with multiscale watershed segmentation in mapped tree areas, and AGB was estimated from a crown area--height power-law proxy calibrated to species-specific allometry (Lambert et al., 2005) for 21,921 inventory trees. For 18,713 inventory--segment matched pairs from a 90,726-tree held-out test set, AGB prediction achieved $R^2=0.609$ using inventory crown geometry and $R^2=0.570$ under operational segmentation, identifying crown delineation as the remaining uncertainty source. Aggregated to 30~m, estimates yielded total AGB stocks of 1.73~Tg in 2018 and 1.81~Tg in 2023 (811--850~Gg~C), local densities up to ${\sim}140$~Mg~ha$^{-1}$ along the Niagara Escarpment, and a net carbon gain of 39~Gg~C over five years. Deep-ensemble uncertainty maps highlighted high-epistemic-uncertainty areas linked to underrepresented land covers and guided assignment of uncertain crowns to a pooled allometric equation. The framework uses standard provincial data, requires no manual annotation, and produces a public bitemporal crown-level AGB database for trees outside forests at management-relevant resolution.
### Title:
          OctoSense: Self-Supervised Learning for Multimodal Robot Perception
 - **Authors:** Anthony Bisulco, Jeremy Wang, Kostas Daniilidis, Randall Balestriero, Pratik Chaudhari
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present OctoSense, an open-source sensor platform with stereo RGB and event cameras, LiDAR, a thermal camera, an inertial measurement unit, RTK-corrected global positioning system, and proprioception (CAN bus data from a car, and joint angles for a quadruped robot). The eponymous OctoSense dataset contains 59 hours of time-synchronized driving data across different types of environments at different times of the day, including situations with highly degraded sensors. We demonstrate multi-modal self-supervised learning using such real-world robotics data, where sensors have different representations, frequencies, latencies and noise. Our approach, a "late-fusion" masked autoencoder, (i) uses modality-specific tokenizers to account for different spatiotemporal characteristics of these sensors, and (ii) caches modality-specific tokens at inference time to process new measurements as they come. This architecture (i) is fast (6.68 ms and 112 ms on NVIDIA 5090 and Orin NX respectively, to compute the representation), (ii) performs better than existing image-only foundation models on tasks such as estimation of optical flow, depth, semantic segmentation, and ego-motion (translation, rotation, and steering angle), and (iii) predicts robustly at nighttime or in situations where sensory data is degraded. See our project page for links to the dataset, code, and supplementary videos: this https URL.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          Sculpting NeRF Geometry: Human-Preference Fine-Tuning of a 3D-Aware Face GAN
 - **Authors:** Archer Moore, Mingming Gong, Liam Hodgkinson
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning from human feedback (RLHF) for 3D generation is now established across a number of works, but most existing pipelines optimise explicit surface representations, often by converting radiance fields into meshes and training heavily on surface-supervised data. We instead fine-tune a pretrained 3D-aware generative model directly from a learned reward over radiance-field density ($\sigma$) values, with no externally supplied mesh or shape prior. The reward model requires no pretraining, trains easily on a small set of preference samples, and yields robust improvement in 3D geometry. Working on an unconditional 3D-aware face GAN (EG3D), our reward reads the continuous 3D density field of the neural radiance field (NeRF) directly and supplies a geometry-only learning signal, requiring neither text conditioning, mesh extraction, nor multi-view rendering. A density-consistency constraint keeps the 2D appearance qualitatively similar while the geometry is reshaped, at a measurable but bounded distributional cost (FID-50k rises from 4.09 to 6.66): the fine-tuned generator, trained from the preferences of a single annotator as a proof of concept, produces face geometries preferred by users in 74.4% of pairwise comparisons.
## Keyword: mapping
### Title:
          Dream machine -- the next creative economy
 - **Authors:** Peter Woodbridge, John J. O'Hare
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We examine the structural transformation of creative industries under generative artificial intelligence, drawing on 374 primary sources spanning policy documents, industry data, creator surveys, and platform analytics. Beginning with the December 2024 release of OpenAI's Sora video model as a watershed event, we trace the historical pattern of creative resistance to technological disruption, then develop an analytical framework -- the Human-AI Agency Continuum for mapping the spectrum of human and machine collaboration in creative work. We present evidence for the "slop ceiling," an audience-imposed quality threshold that constrains AI-generated content to approximately 1--3% of platform streams despite comprising 44% of uploads. Analysis of the UK Government's 2025 consultation on AI and copyright (over 11,500 responses, 88% opposing expanded AI training rights) reveals deep structural tensions between technology firms and creative workers. We investigate how major studios, from Disney's $1 billion OpenAI investment to Netflix's AI-native animation unit, are positioning for an AI-augmented production pipeline. The work covers coordination collapse in creative supply chains, the emergence of new professional roles such as prompt engineers and AI orchestrators, and proposes four principles for navigating the transition: transparency, consent, compensation, and human-centred design. Eight appendices provide quantitative analysis, a glossary, topical bibliography, and deep dives into shadow AI adoption, AI stigma, and algorithmic intent.
### Title:
          A Multi-Layer AI Framework for Information Landscape Analysis
 - **Authors:** Maryam Fooladi, Federico Bottino
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes a multi-layer AI framework for information landscape analysis in the context of information disorder. Rather than treating misinformation detection as a binary fact-checking task, the framework analyzes political and media content across multiple dimensions, including source reliability, factual structure, framing, bias, emotional activation, manipulation patterns, and propagation dynamics. The goal is to move beyond isolated claim verification toward a structured representation of the informational environment surrounding an event, entity, or narrative. We argue that AI systems for media analysis should support epistemic mapping: a transparent, multi-dimensional account of how facts, interpretations, actors, and narratives interact over time. The paper presents the conceptual architecture, analytical layers, and methodological rationale of the framework, with the aim of supporting more nuanced, explainable, and critically useful tools for information disorder research.
### Title:
          Mitigating High-Frequency Geometric Noise in Non-Parametric 1-Bit Sparse
 - **Authors:** Lars Kopp
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Energy-efficient neuromorphic computing requires alternative data-encoding paradigms that bypass power-hungry floating-point operations. This paper evaluates a deterministic, non-parametric dual-manifold execution framework that maps dense 128-element integer vectors - representing digitized multi-frequency trigonometric waveforms - into a 1024-dimensional overcomplete space using 8-bit bounded transformation matrices. By enforcing a hard activation threshold, the system yields an ultra-sparse, 1-bit binary population code where y belongs to the set (0, 1)^1024. We identify and address a critical phenotypic artifact of this non-parametric mapping: the emergence of high-frequency geometric noise during linear reconstruction. Furthermore, we document an algorithmic complexity paradox where low-complexity input functions yield significantly higher reconstruction errors than highly complex, high-degree trigonometric combinations. Because the underlying basis functions operate as purely objective mathematical entities without statistical priors regarding signal smoothness, this geometric noise is proven to be strictly orthogonal to the core signal topology. Consequently, we demonstrate that a low-overhead, hardware-level digital low-pass filter completely eliminates this artifact, reducing reconstruction errors to near-zero bounds even under tight overcompleteness constraints. This architecture validates a highly stable, multiplier-free alternative to traditional deep learning hardware for edge-AI applications, verified through comprehensive empirical evaluations across varying complexity scales and classification thresholds (tau = 10 and tau = 100).
### Title:
          The Kernel's Write: Application Read-Only Memory
 - **Authors:** Hui Sub Shim, Katherine Mohr, Philip Levis
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Operating Systems (cs.OS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Alongside power, DRAM has become a major limiting factor in datacenter growth. As DRAM's cost-per-bit has plateaued over the past decade, a class of emerging memory technologies, called Long-term RAM (LtRAM), offers a path to denser and cheaper main memory. However, LtRAM has three main drawbacks: asymmetric read/write latencies, limited endurance, and coarse write granularity. In an attempt to isolate software from these drawbacks, LtRAM technologies such as Intel Optane copy an approach from flash devices and introduce a translation layer that manages wear-leveling, address remapping, and read/write caching. Prior experimental studies have found these operations add significantly to LtRAM latency. Rather than making LtRAM look like DRAM, we propose redesigning the hardware/software interface to offload more responsibility to the operating system. This design hinges on one central property, Application Read-Only Memory (AROM): LtRAM pages are read-only to applications and written only by the OS during page migrations. AROM is enforced by leveraging copy-on-write (CoW): application writes to LtRAM trigger a fault that migrates the page back to DRAM before the store is applied. This invariant allows us to shift LtRAM management from the on-DIMM controller to the operating system, drastically simplifying the DIMM's hardware. With this approach, we aim to match the performance of pure DRAM on read-mostly workloads while delivering LtRAM's density and cost advantages.
### Title:
          KRVF: A Source-Aware Semantic Voxel World Representation for Edge Mobile Manipulation
 - **Authors:** Runfeng Ling
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mobile manipulators need world models that are current, queryable, semantically meaningful, and usable under edge-compute constraints. This technical report presents KRVF, a source-aware semantic voxel world representation for edge mobile manipulation. Unlike reconstruction-centric mapping pipelines that primarily optimize global geometric fidelity, KRVF represents local world state as task-oriented voxels that encode occupancy, color, semantic evidence, temporal freshness, and evidence source. The representation separates measured occupancy from semantic-prior hypotheses, enabling depth-failure-aware object reasoning without silently corrupting persistent geometry. KRVF also closes a feedback loop between mapping and sensing by rendering map-prior depth for repair, and exposes task-level query operators for semantic objects and grasp candidates. The report formalizes the KRVF representation and documents a ROS 2 implementation that turns online RGB-D observations into a task-facing robot memory.
### Title:
          Data-driven Machine Learning Cannot Reach Symbolic-level Logical Reasoning -- The Limit of the Scaling Law
 - **Authors:** Tiansi Dong, Mateja Jamnik, Pietro Liò
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sphere neural networks have achieved symbolic level syllogistic reasoning without training data, raising the question of where the limit of the scaling law for logical reasoning lies, i.e., whether data-driven machine learning systems can achieve the same level by increasing training data and training time. We show two methodological limitations that prevent supervised deep learning from reaching the symbolic-level syllogistic reasoning: (1) training data can not distinguish all 24 types of valid syllogistic reasoning; (2) end-to-end mapping from premises to conclusion introduces contradictory training targets between neural components for pattern recognition and logical reasoning. Beside theoretical analysis, we experimentally illustrate that Euler Net cannot achieve rigorous syllogistic reasoning. We further challenge the most recent ChatGPTs (GPT-5-nano and GPT-5) to determine the satisfiability of syllogistic statements in four surface forms (patterns): words, double words, simple symbols, and long random symbols, showing that surface forms affect the reasoning performance and that ChatGPT GPT-5 may reach 100% accuracy but still provide incorrect explanations. As empirical training processes are stopped after achieving 100% accuracy, we conclude that supervised machine learning systems will not attain the rigour of symbolic logical reasoning.
### Title:
          OSC2Runner: OpenSCENARIO 2.x Compliant High-Fidelity AV Simulation in CARLA
 - **Authors:** Thoshitha Gamage, Lasanthi Gamage
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scenario-Based Testing predominantly relies on the legacy ASAM OpenSCENARIO 1.x XML standard because existing continuous simulation frameworks lack native execution support for the recently matured v2.x Domain-Specific Language (DSL). Adapting legacy interpreters to evaluate v2.x logic introduces spatiotemporal drift, asynchronous event latencies, and artificial kinematic snapping. Addressing this execution gap, OSC2Runner introduces the first orchestration framework capable of natively mapping the OpenSCENARIO v2.x DSL to CARLA. The framework achieves this by formalizing scenario translation as a compilation pipeline through a multi-pass transpiler architecture. Bypassing static trajectory playback, the architecture synthesizes type-safe Abstract Syntax Trees directly into dynamic deterministic behavior trees (py_trees) natively mapped to CARLA's atomic APIs. Empirical validation in highly concurrent adversarial case studies demonstrates tick-by-tick determinism, exact spatial trigger evaluation, and 100.0 ms cross-actor blackboard synchronization. Kinematic analysis proves the strict adherence to continuous environmental boundaries. This architecture transitions Scenario-Based Testing from approximate behavioral interpretation to mathematically rigorous execution, establishing the deterministic backend required for co-simulation, hardware-in-the-loop testing, and automated LLM-driven generation pipelines.
### Title:
          Coarse-to-Fine: A Hybrid Self-Supervised Method for Non-rigid 3D Shape Matching
 - **Authors:** Feifan Luo, Ting Li, Zhao Li, Hongyang Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Non-rigid 3D shape matching is a fundamental task in computer vision and graphics. In this paper, we propose a hybrid self-supervised method based on a coarse-to-fine strategy, which ensures consistency between the coarse mapping and the refined correspondence produced by our refinement module. The architecture features a dual-branch design, consisting of two symmetric functional map learning streams: one based on the Laplacian basis and the other utilizing the elastic basis. Extensive experiments show that our approach not only maintains computational efficiency, but also achieves state-of-the-art performance across a variety of challenging scenarios, including non-isometric deformations and topological noise. Finally, we rigorously demonstrate that contrastive energies promote feature discrimination. Furthermore, integrating these energies with existing methods yields consistent improvements, validating the overall efficacy of our approach. Our code is available at this https URL.
### Title:
          Simulating Unified Tensor Resharding in heterogeneous AI systems
 - **Authors:** Sumit Kumar, Sayantan Dasgupta, Kushal Mitra, Meet Dadhania, Rohan Sudhir Basugade, Praveen Tammana, Satananda Burla, Abed Mohammad Kamaluddin, Rinku Shah
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State-of-the-art AI training simulators assume homogeneous compute and network infrastructure. However, real-world training infrastructure is becoming increasingly heterogeneous since: (a) Model architectures such as multimodal and MoE exploit heterogeneity to improve device utilization, (b) Public cloud platforms often provide limited availability of homogeneous hardware due to fast hardware evolution, and (c) Large enterprises frequently deploy geographically distributed infrastructure that is both diverse and heterogeneous. In this paper, we present Xsim, a heterogeneity-aware simulator for distributed LLM training. Xsim supports: (i) Load balancing through non-uniform workload partitioning across heterogeneous device groups, (ii) Heterogeneity-aware collective communication via customized ring construction and chunk partitioning, (iii) Reusable heterogeneity-aware abstractions for emerging pipeline-parallel algorithms and non-uniform tensor resharding technique, (iv) Flexible input abstractions for specifying deployment plans with custom device groups and custom device-to-parallelism mappings, and (v) Pluggable integration with NS-3 and htsim, allowing users to trade off simulation fidelity for performance and scalability. Our evaluation demonstrates that Xsim accurately predicts training time for real-world heterogeneous deployments, with an error of less than 5% across most heterogeneous data-parallel/tensor-parallel configurations and around 2% error with pipeline-parallel communication modeling. We expose actionable metrics such as pipeline bubble time and straggler waiting time.
### Title:
          SegFold: Accelerating Sparse GEMM with a Fine-Grained Dynamic Dataflow
 - **Authors:** Xinrui Wu, Hanyu Wang, Jason Cong, Tony Nowatzki
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generalized sparse matrix-matrix multiplication (SpGEMM) is critical in many domains. Existing CPUs and GPUs, as well as specialized accelerators, rely on static dataflows (e.g., inner product, outer product, Gustavson, etc.). Each static dataflow sacrifices some data reuse opportunities and imposes constraints on load balance. To address this inefficiency, we extend the typical SpGEMM dataflows by considering dynamism. Specifically, we add fine-grained dynamic scheduling to optimize reuse and reduce resource contention. We also develop dynamic remapping of partially completed work to improve load balance and parallelism. These ideas are formalized into a specific dataflow called Segment. To demonstrate Segment, we codesign a SpGEMM accelerator called SegFold. SegFold includes a memory controller that identifies fine-grained reuse opportunities in a local window of the stationary input array and exploits them through dynamic work assignment. It also incorporates a merge network that routes inputs to appropriate processing elements (PEs) for computation while dynamically remapping the work assigned to each PE to balance load. Across diverse densities and matrix sizes, SegFold achieves a geometric-mean $1.95\times$ speedup over state-of-the-art SpGEMM accelerators and $5.3\times$ over the best static dataflow configuration, demonstrating that adding dynamism to the dataflow design space unlocks reuse and load-balance gains that no static scheduling choice can achieve in isolation.
### Title:
          Regularization of the metric generalized inverse in Banach spaces and the dichotomy phenomenon
 - **Authors:** Peter Mathé, Bernd Hofmann
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Functional Analysis (math.FA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 For a bounded linear operator acting between Banach spaces, its metric generalized inverse is the analog to the prominent Moore-Penrose inverse for operators acting between Hilbert spaces. This generalized inverse is well-defined for Banach spaces that are strictly convex and reflexive. Previous studies had been restricted to closed range situations, where the metric generalized inverse constitutes a continuous homogeneous mapping. The focus of the present study is on the ill-posed situation in the sense of Nashed, when the governing operator has a non-closed range. We define and analyze iterative schemes as the Landweber and the Schulz-Newton method, as well as parametric schemes with focus on a specific Tikhonov method. Both types are called regularizations aimed at approximating the metric generalized inverse. As a fundamental feature of such schemes we observe a dichotomy. This emphasizes that these schemes, when applied to elements of the domain of the metric generalized inverse, approximate the corresponding best approximate solutions well, whereas the resulting approximations will be asymptotically unbounded if they are applied to elements that do not belong to the domain of the metric generalized inverse.
### Title:
          EGG: An Expert-Guided Agent Framework for Kernel Generation
 - **Authors:** Yaochen Han, Ke Fan, Hongxu Jiang, Wanqi Xu, Weiyu Xie, Runhua Zhang, Chenhui Zhu, Yixiang Zhang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-performance GPU kernels are critical for reducing the exponentially growing computational costs of large language models (LLMs), but their development heavily relies on manual tuning by domain experts. While recent advances in LLM-based approaches show promise for automating kernel generation, they still struggle to achieve both correctness and high performance. This limitation primarily arises from the lack of domain-specific optimization guidance, hindering effective exploration of the optimization space. We propose EGG, an Expert-Guided Agent Framework for Kernel Generation, which incorporates expert optimization principles to guide LLMs' decisions. Inspired by expert workflows, we decompose kernel generation into two hierarchical stages: 1) algorithmic structure design, which establishes a high-quality computational structure foundation; 2) hardware-specific tuning, which performs targeted adjustments through parallel mapping, tensor tiling, and memory optimization. This staged decomposition defines explicit optimization objectives, structuring the design space to achieve progressive refinement. To this end, a stage-aware multi-agent collaboration mechanism is designed for inter and intra-stage context management, ensuring stable optimization trajectories. Experiments on KernelBench and real-world workloads show that EGG achieves a 2.13x average speedup over PyTorch, outperforming existing agent-based and RL-based approaches.
### Title:
          ResilPhase: Plug-and-Play Phase Mapping and Noise-Resilient Macro-Trajectory Extrapolation for Diffusion Acceleration
 - **Authors:** Qicheng Zhao, Yu Li, Qi Sun, Zheyu Yan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The adoption of powerful diffusion models is hindered by their significant inference latency. Recent ``cache-then-forecast'' schemes alleviate this issue by accelerating DiTs using derivative-based polynomials, but they suffer from severe quality degradation at high acceleration ratios. Our analysis reveals its root cause: the discrete extrapolation performed on representations that are misaligned with the continuous diffusion trajectory and are numerically unstable. Thus, accelerated DiTs suffer from accumulated spatial errors, noisy derivative amplification, and high-order instability. We therefore reformulate accelerated inference as stable macro-trajectory extrapolation in ordinary differential equation (ODE) space. Instead of predicting intermediate features, we align forecasting with the model's Global Drift (GD), i.e., the end-to-end state evolution, thereby eliminating feature inconsistency and memory overhead. However, even this smooth macro-trajectory remains vulnerable to the derivative fallacy: its higher-order temporal derivatives are intrinsically noisy. Thus, we introduce a derivative-free barycentric Lagrange extrapolator to effectively bypass derivative instability and approximation error. We further propose a bounded Phase Mapping that regularizes the extrapolation domain, suppressing oscillatory error growth. These elements collectively constitute ResilPhase, a noise-resilient acceleration framework. Experiments on FLUX.1-dev and HunyuanVideo demonstrate state-of-the-art fidelity under aggressive acceleration ratios.
### Title:
          NaviCache: Test-Time Self-Calibration Caching for Video Generation
 - **Authors:** Zheqi Lv, Zhibo Zhu, Jinke Wang, Qi Tian, Shengyu Zhang, Zhengyu Chen, Chengxi Zang, Zhou Zhao, Fei Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video Diffusion Models (VDMs) is constrained by immense computational costs. While offline calibration-based acceleration suffers from calibration data dependency, prohibitive calibration duration, and susceptibility to distribution shifts, offline calibration-free methods eliminate these hurdles. However, since they rely on instantaneous zero-order approximations where the mapping between input and output differences varies in real-time, they are susceptible to observational noise and ignore the intrinsic momentum within the diffusion trajectory. In this paper, we propose NaviCache, a plug-and-play test-time self-calibration method re-conceptualizing feature evolution as an Inertial Navigation System (INS) problem. NaviCache bridges the fundamental domain gap and the non-stationary nature of diffusion by modeling the relative coupling between input and output variations. We introduce a dual-state estimation architecture that adaptively tracks the feature change ratio and its latent drift, initialized via a specialized Initial Alignment phase. By integrating a time-dependent noise schedule with an uncertainty-aware Measurement Update mechanism, NaviCache provides a theoretically grounded mechanism for error-bounded computation skipping. Extensive experiments on the HunyuanVideo, Wan, and Open-Sora series demonstrate that NaviCache exhibits more accurate error judgment for computation skipping and achieves outstanding comprehensive performance.
### Title:
          Multi-modality Image Fusion under Adverse Weather: Mask-Guided Feature Restoration and Interaction
 - **Authors:** Xilai Li, Xiaosong Li, Haishu Tan, Tao Ye, Huafeng Li, Hongbin Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-modality image fusion (MMIF) enhances scene representation by exploiting complementary cues from different modalities. Adverse weather, however, causes significant image degradation, disrupting feature representation and requiring simultaneous feature restoration and cross-modal complementarity. Existing methods often struggle with effective representation learning under such conditions, limiting their practical performance. To address these challenges, we propose a mask-guided MMIF method that integrates feature restoration and interaction. We first introduce "Pseudo Ground Truth" to simplify training, promoting faster and more effective feature learning. Then, we design a mask generation mechanism based on the mapping relationship between the fused result and the source images, quantifying the relative contribution of each modality during the fusion process. By incorporating the proposed mask-guided cross-modal cross-attention mechanism, the network is encouraged to selectively attend to informative features during modality interaction, mitigating the risk of overfitting to the static distribution of the "Pseudo Ground Truth". Additionally, we propose a mask-guided learning strategy and a task-coupled degradation-aware learning strategy to balance feature restoration and interaction. Extensive experiments on synthetic and real-world datasets demonstrate that our method surpasses state-of-the-art approaches in visual quality, quantitative metrics, and downstream tasks. The source code is available at this https URL.
### Title:
          A Shared IPTC Topic Space for Cross-Source Topic Modelling
 - **Authors:** Din Iskakov, Sebastian Gonçalves, Marco Idiat, Mendeli Vainstein, Aline Villavicencio, Ronaldo Menezes, Rodrigo Wilkens
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Comparing topic attention across different media is hindered by a fundamental modelling problem: topic models fitted separately to each corpus produce corpus-specific topic spaces that cannot be aligned directly. This paper presents a reproducible framework that places corpora in a single shared topic space defined by a taxonomy. Discovered topics are obtained with guided BERTopic, scored against the ninety-four IPTC Media Topics' taxonomy topics (level-1) through weighted keyword and target centroids, and then collapsed upward to seventeen IPTC parent topics by a maximum-similarity rule. The framework was developed and selected on a controlled New York Times 2011 corpus through a narrowing sequence: a broad model screen, a focused mapping refinement, a strict finalist comparison, a target-construction ablation, and a threshold calibration. In this corpus, the guided family retained substantially stronger mapped coverage than a zero-shot benchmark under stricter assignment thresholds, a parent-enriched target construction improved both coverage and parent consistency, and coverage declined gradually rather than collapsing as the assignment threshold was tightened. The contribution is an externally anchored method for constructing a shared topic space that enables reproducible cross-source topic comparison.
### Title:
          UAV-MapFusion: RTK-Aligned Uncertainty-Aware Coarse-to-Fine Multi-Session UAV Mapping
 - **Authors:** Feng Pan, Chunran Zheng, Bing Xue, Yukang Cui, Jiayu Wen, Zhiyu Chen, Wei Wang
 - **Subjects:** Subjects:
Robotics (cs.RO); Social and Information Networks (cs.SI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale point cloud maps are essential for robotics and spatial intelligence tasks. UAVs provide an efficient means for large-scale map acquisition; however, due to limited flight endurance and onboard storage, mapping a large-scale scene within a single flight remains difficult. Existing multi-session map merging methods can extend the mapping range, yet in UAV scenarios they still struggle to simultaneously suppress long-range drift and preserve local geometric accuracy. To address this issue, an uncertainty-aware multi-session point cloud map merging and coarse-to-fine optimization system is proposed. The proposed method first performs initial multi-session map merging based on a scene graph, and then incorporates RTK observations through an RTK spatiotemporal alignment module, where temporal offsets are estimated using Dynamic Time Warping (DTW), and continuous RTK constraints are recovered using Multi-Output Gaussian Processes (MOGP) under incomplete sampling and frame dropouts. On this basis, a unified uncertainty-aware factor graph is constructed, and local geometric accuracy is further improved through iterative plane-factor refinement. Experiments on real-world datasets validate the effectiveness and robustness of the proposed method. To facilitate further research and development in the community, our code and dataset will be publicly released.
### Title:
          Term-Centric Hierarchy Induction from Heterogeneous Corpora
 - **Authors:** Elena Senger, Yuri Campbell, Jan-Peter Bergmann, Rob van der Goot, Barbara Plank
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Organizing knowledge from diverse text sources into interpretable hierarchies is crucial for tasks such as policy analysis, innovation monitoring, and exploratory domain mapping. Existing taxonomy induction methods typically rely on document-level representations that capture entire documents rather than the specific domain concepts relevant for knowledge organization, limiting their ability to generalize across heterogeneous sources. We propose a term-centric framework for inducing hierarchical taxonomies from heterogeneous corpora that scales to massive document collections. Our approach maps documents from diverse sources into a shared representation space using automatic term extraction, enabling robust cross-source alignment. Based on these representations, we construct interpretable hierarchies that integrate domain priors with datadriven clustering. Experiments on a novel English and German multi-source benchmark of over one million documents demonstrate that our method improves cross-source coherence and hierarchy quality over text- and summarybased baselines. A case study on German regional innovation analysis further demonstrates its practical utility for technology landscape mapping.
### Title:
          On-board Remote-Sensing Foundation Models for Unsupervised Change Detection of Disaster Events
 - **Authors:** S. Ramírez-Gallego
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote Sensing Foundation Models (RSFMs) have emerged as a powerful alternative to supervised models for Earth Observation, allowing satellites to autonomously trigger high-resolution captures or adjust tasking parameters upon detecting an anomaly, thereby maximizing the utility of the mission's limited power and computational resources. RSFMs are versatile, unified encoders that optimize onboard storage for multiple orbital applications while ensuring high-fidelity feature extraction. In particular, unsupervised change detection with RSFMs offers a well-informed and transformative path for disaster monitoring without expensive labels. In this paper, we present a novel unsupervised detection method based on ResNet (RSFM) + FPN which identifies a wide spectrum of anomalies by detecting subtle semantic shifts in the latent space between successive orbital passes. By relying on an untrained FPN architecture and its intrinsic priors, the system achieves efficient image-level generation and higher resolution mapping with minimal effort (training-free) compared to previous proposals (patch-based, trained). And by replacing tailored models with RSFMs, we can achieve comparable results through an approach that eliminates the need for bespoke training and extensive development effort and adds customization, while ensuring high-performance generalization across diverse terrains and sensors.
### Title:
          Safe Autoregressive Image Generation with Iterative Self-Improving Codebooks
 - **Authors:** Yunqi Xue, Zhijiang Li, Philip Torr, Jindong Gu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unlike diffusion-based models that operate in continuous latent spaces, autoregressive unified multimodal models produce images by sequentially predicting discretized visual tokens. These tokens are derived from a codebook that maps embeddings to quantized visual patterns. The language-like architecture enables unified multimodal models to effectively capture text conditional information for generation, making them promising for text-to-image tasks. This also raises an interesting question: how safe are the images generated in such an autoregressive way? In this work, we propose iterative self-improving codebooks for safe autoregressive generation. We leverage the understanding and judgment capabilities of the unified multimodal model itself to identify unsafe generated images without human annotation. Subsequently, the inherent representations in the codebook are fixed to eliminate harmful mappings. Our method comprises two steps: first, we use the unified model to identify unsafe generations and construct corresponding harmful and safe image-text pairs. These pairs are used to construct the Harmful Space and guide updates to the codebook, thereby eliminating harmful outputs. Second, we perform adaptive fine-tuning on the codebook within the harmless space using safe image-text pairs to ensure the quality of generated images. These two steps are repeated until no further improvement is observed, producing a safety-enhanced model codebook. Without additional external feedback, the safety of models is improved iteratively.
### Title:
          LA4VLA: Learning to Act without Seeing via Language-Action Pretraining
 - **Authors:** Tao Lin, Yuxin Du, Yiran Mao, Zewei Ye, Yilei Zhong, Bing Cheng, Yiming Wang, Jiting Liu, Yang Tian, Junchi Yan, Feiran Wu, Zenan Meng, Hu Wei, Yuqian Fu, Gen Li, Bo Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models are commonly pretrained on robot demonstrations by jointly mapping visual observations and language instructions to actions. However, dense visual-action supervision can dominate the comparatively sparse language-action signal. As a result, policies may rely on visual shortcuts rather than learn how language conditions action execution, making them sensitive to visual variations. To address this limitation, we propose LA4VLA, a language-action pretraining framework that enables policies to acquire language-conditioned action priors without visual observations. These priors capture reusable manipulation skills shared across tasks and scenes, reducing reliance on scene-specific visual cues. Specifically, LA4VLA decomposes expert demonstration trajectories into atomic action segments and pairs each segment with a corresponding low-level action description. This yields LA4-33K, a dataset of 33K Language-Action (LA) episodes derived entirely from existing demonstrations without additional robot data collection. We further develop LA4VLA-1B, a lightweight 1B-parameter VLA model, and investigate three paradigms for incorporating language-action supervision into VLA learning: LA-only pretraining, sequential LA-to-VLA pretraining, and mixed LA-VLA pretraining. Across simulation and real-world tasks, LA-pretrained policies consistently outperform matched VLA-pretrained counterparts, while combining LA and VLA supervision leads to further gains. In particular, mixed LA-VLA pretraining improves the average success rate of LA4VLA-1B over the no-pretraining baseline by up to 17.8 and 45.0 percentage points in simulation and real-world tasks, respectively. These results establish LA4VLA as an effective and complementary pretraining strategy for building stronger and more robust VLA policies.
### Title:
          Mapping Political-Elite Networks in Europe with a Multilingual Joint Entity-Relation Extraction Pipeline
 - **Authors:** Kirill Solovev, Jana Lasser
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Whether political elites organise into rent-seeking coalitions that capture public resources or civic networks that sustain governance is a central question in comparative politics. Yet observing these complex, informal, and adversarial ties at scale has historically required intensive manual coding, while automated text-as-data methods have largely been limited to simple co-occurrence. Recent large language model (LLM) approaches offer a path forward but often rely on proprietary APIs, lack cross-lingual capability, and struggle with scalable entity resolution. We present a modular, fully open-weight pipeline for multilingual joint entity-relation extraction that builds signed, temporal knowledge graphs from massive unstructured news corpora. It combines span-based named-entity recognition (NER) with a three-stage linking cascade mapping mentions to language-independent Wikidata identifiers; a high-throughput, ontology-constrained mixture-of-experts model then uses guided decoding to extract directed, signed relationships grounded in a domain ontology. A full-coverage spot-check against a 3491-relation gold standard shows high textual correctness (68.2% strict to 93.7% lenient). Two large-scale case studies validate the pipeline against the public record. In Austria, it reconstructs a political party's complete lifecycle, dating internal fractures and tracking personnel into successor factions and court convictions. In a Polish corpus, it uncovers the overlapping economic and governance networks of state-enterprise patronage, alongside the structurally balanced, signed conflict network of the polarized Civic Platform (Platforma Obywatelska, PO)--Law and Justice (Prawo i Sprawiedliwość, PiS) duopoly. By bridging raw multilingual text and structured relational data, our framework provides a robust, replicable foundation for cross-national empirical computational social science.
### Title:
          Error-Conditioned Neural Solvers
 - **Authors:** Haina Jiang, Liam Wang, Peng-Chen Chen, Min Seop Kwak, Seungryong Kim, Brian Bell, Jeong Joon Park
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural surrogate models offer fast approximate mappings from PDE parameters to solutions, but they typically treat solving as a purely statistical task: once trained, they struggle to correct their own constraint violations and extrapolate beyond the training distribution. Recent hybrid methods promote physical correctness by targeting the PDE residual via gradient descent or Gauss--Newton steps, but inherit the compute cost and instability of the underlying classical optimizers. We show, theoretically and empirically, that numerically minimizing the PDE residual can be an unreliable proxy for reconstruction accuracy in ill-conditioned systems, explaining why these methods often do not make accurate predictions despite achieving low residuals. We propose error-conditioned Neural Solvers (ENS), built on a different principle: rather than an optimization target, the PDE residual field is passed as a direct input to the network at each iteration, enabling it to read the spatial structure of its own errors and learn an update policy to iteratively correct its predictions. Across four PDE families, ENS attains the highest prediction accuracy in the large majority of settings, with gains reaching $10\times$ on turbulent Kolmogorov flow, while avoiding the expensive compute cost of hybrid methods. ENS's learned correction policy generalizes under distribution shift, including zero-shot parameter changes and cross-equation transfer, where its relative advantage is largest in the ill-conditioned regimes where residual minimization is least reliable. Project website: this https URL.
## Keyword: localization
### Title:
          Soroll-IA: A Weakly Labeled Audio Dataset for Real-World Industrial Port Monitoring
 - **Authors:** Javier Naranjo-Alcazar, Jordi Grau-Haro, Ruben Ribes-Serrano, Marta Garcia-Ballesteros, Pedro Zuccarello
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Soroll-IA is a weakly labeled environmental audio dataset recorded in a real-world industrial port environment in Valencia (Spain) using two fixed sensing nodes. The dataset comprises approximately 22 hours of audio segmented into 7,396 clips and covers 26 sound event classes representative of industrial port acoustic activity commonly observed in such environments, such as crane sirens, train movements, traffic, and other logistical and industrial sounds. Recordings were captured under highly challenging acoustic conditions, including strong background noise, long-distance sources, and frequent event overlap. All audio clips were annotated by domain experts following a weak labeling strategy, where tags indicate the presence of sound events within a clip without temporal localization. To account for inter-annotator variability, two ground-truth versions are released: one without cross-validation, where a class is considered present if annotated by at least one expert, and a second, more conservative version based on cross-validation, where agreement by at least two-thirds of the annotators is required. The dataset is intended to support research in audio tagging, weakly supervised sound event detection, and machine learning under realistic industrial acoustic conditions. Benchmark results are provided using two complementary architectures: CNN14 representing high-capacity convolutional models for audio tagging, and MobileNetV2, selected for its suitability in real-time classification on low-resource edge devices. To the best of current knowledge, Soroll-IA constitutes an available dataset dedicated exclusively to industrial port acoustic environments, aiming to foster advances in robust environmental sound analysis for safety-critical and operational monitoring applications. The dataset is available online and collected under Attribution-NonCommercial 4.0 International license.
### Title:
          CyberChainBench: Can AI Agents Secure Smart Contracts Against Real-World On-Chain Vulnerabilities?
 - **Authors:** Jintao Huang, Fengqing Jiang, Radha Poovendran, Zhiqiang Lin
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present CyberChainBench, a benchmark for evaluating LLM-based agents on smart contract security across three complementary tasks: vulnerability detection, exploit generation, and patch synthesis. Built from 541 real-world exploit incidents from DeFiHackLabs spanning 9 EVM chains, the benchmark provides end-to-end on-chain evaluation where agents interact with historical blockchain state through isolated evaluation environments orchestrated by Harbor, using tools to read code, trace transactions, and validate exploits on mainnet forks. Each case is anchored to a specific block and includes structured ground truth covering vulnerability type, localization, and attacker profit. Exploits are graded by economic impact on historical forks; patches are validated by replaying historical attacks and legitimate transactions as fail-to-pass test oracles on a proxy-upgradeable subset. We define a five-type vulnerability taxonomy and evaluate multiple agent--model configurations. Results reveal a clear difficulty gradient: the best configuration scores 37.5% on detection, 43.7% on exploitation, but only 23.4% on patching, with the top agent (Codex with GPT-5.5) realizing \$57.4M in total exploit profit across the 200-case exploit set at a cost of $2.39 per case.
### Title:
          Active Adversarial Perturbation-driven Associative Memory Retrieval for RGB-Event Visual Object Tracking
 - **Authors:** Xiao Wang, Xufeng Lou, Zikang Yan, Lan Chen, Sibao Chen, Yaowei Wang, Yonghong Tian, Jin Tang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 RGB-Event tracking improves localization robustness by fusing RGB appearance textures and dense temporal motion cues from event sensors. While this multi-modal scheme broadens tracking applicability, real-world scenes suffer diverse structured signal degradations that hinder traditional multi-modal fusion. In harsh environments, either modality can lose reliability drastically, and targets frequently appear incomplete due to occlusion, edge truncation and foreground this http URL tackle the above challenges, we present a hierarchical perturbation and retrieval framework tailored for RGB-Event tracking with robustness against partial target missing and modal degradation, termed APRTrack. To mimic real-world signal corruption, APRTrack constructs structured degradation via two adversarial perturbation branches at the modality and spatial levels, which separately simulate full-modal failure and localized target region absence. A hierarchical routing mechanism is designed to disentangle the training pipelines of the two perturbation types, effectively eliminating feature collapse induced by superimposed degradation constraints. Furthermore, we devise Footprint-guided Channel-calibrated Hopfield Retrieval (FCHR) for reliable historical information compensation. This module evaluates retrieval confidence based on association footprints between queries and memory banks, and calibrates the retrieval metric space prior to Hopfield matching, realizing controllable historical feature compensation bounded to target regions. Extensive experiments on FE108, COESOT, VisEvent, and FELT datasets demonstrate the effectiveness of our proposed strategies for the RGB-Event visual object tracking. The source code and pre-trained models will be released on this https URL
### Title:
          A Multi-Level Validation and Traceability Framework for AI-Generated Telescope Scheduling Decisions
 - **Authors:** Hengchu Xiao, Chuanjun Wang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the gradual introduction of AI into telescope scheduling, AI-based decision-making has shown advantages in handling complex multi-constraint problems. However, its outputs often suffer from inconsistent data references, reasoning errors, and non-executable decisions, limiting applicability in high-reliability observational tasks. In this work, we propose a multi-level validation and traceable reasoning framework that performs systematic reliability verification of AI-generated decisions prior to execution, and enables explicit representation of the reasoning process to support traceable decision-making. The framework integrates data reference validation, logical consistency checks, and observational and instrumental constraint verification to filter and correct invalid decisions. It also introduces atomic reasoning units and their dependency relationships, representing scheduling decisions as a sequence of interconnected reasoning steps that support error localization and post hoc analysis. Experiments show that the framework improves executability and reliability of AI scheduling and reduces loss of transient opportunities. In particular, feedback correction and structured validation of reasoning steps enhance the ability to repair and block erroneous decisions, especially in complex scenarios. Compared with pure AI methods, the framework-enhanced approach maintains flexibility while substantially improving reliability and executability. These results demonstrate a feasible and verifiable pathway for applying AI to high-reliability astronomical observation scheduling.
### Title:
          A Closed-Form 4-DoF Inter-Robot Pose Estimator using Bearing-only Measurements
 - **Authors:** Qixin De, Ao Zhuang, Yechen Zhang, Zhuozhou Qian, Danping Zou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bearing-odometry-based cooperative localization has attracted increasing research interest due to its minimal infrastructure requirements, low communication bandwidth and broad applicability in complex environments. However, existing 6-DoF approaches still face challenges in rapidly obtaining accurate and reliable inter-robot pose estimation, as the system is prone to observability degeneracy under specific motion patterns. To address these issues, we first propose a closed-form 4-DoF inter-robot pose estimator, which relaxes nonlinear constraints for rotations estimation and employs error projection for translations estimation. We then conduct a theoretical analysis of the system's observability, identifying degeneracy under two typical motion patterns: collinear and shape-preserving formations. The analysis further shows that the proposed 4-DoF system requires less stringent motion excitation for observability, enabling reliable estimation under a broader range of cooperative maneuvers. Furthermore, an observability test module is introduced to autonomously determine the optimal estimation instant, eliminating reliance on a predefined fixed-length sliding window. Extensive simulations and real-world experiments demonstrate that the proposed algorithm achieves higher estimation accuracy with significantly low computational cost, and the observability test module ensures estimation reliability while minimizing the data collection interval.
### Title:
          LayersReg: A Layer-by-Layer Progressive Regressor for Reliable Intraoperative 3D/2D Registration
 - **Authors:** Xiyuan Wang, Zhenchao Wang, Xinran Chen, Junkai Liu, Chuan Chen, Feng Yin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D/2D registration serves as a cornerstone technique in surgical navigation. Traditional iterative optimization algorithms suffer from low efficiency and high failure rates in intraoperative settings. Deep learning-based methods reformulate registration from iterative optimization to a regression problem that maps image appearance features to spatial pose, typically achieving improved real-time performance and accuracy. However, such learnable methods are confined to memory-driven retrieval of specific pose features rather than understanding the task of image alignment itself, which limits their generalization in complex scenarios. We propose LayersReg, a pioneering regression paradigm that endows the model with 3D anatomical awareness and searches for the correct pose in a progressive, layer-by-layer manner. Inspired by the iterative pose-searching optimization criterion of classical registration, LayersReg searches for correlations between the moving and fixed images in feature space, capturing the trend of pixel flow and thereby converging iteratively toward the correct spatial pose transformation. We further design a coupling of node-wise regression with the progressive registration framework to enhance the model's perception of spatial pose changes. Experimental results demonstrate that under large offsets and multimodality conditions, LayersReg achieves high accuracy on both X-ray/CT registration (0.68°, 1.41 mm) and slice localization (0.73°, 1.55 mm) tasks, outperforming existing state-of-the-art methods while meeting the intraoperative demands for precision and real-time capability.
### Title:
          Event-based Gaze Control System for Accurate Real-time Spin Estimation in Professional Ball Games
 - **Authors:** Yunpu Hu, Fabian Schilling, Valentina Cavinato, Asude Aydin, Agis Politis, Ricardo Tapiador Morales, Kirk Y.W. Scheper, Peter Dürr, Naoya Takahashi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spin plays a crucial role in many ball sports due to its effect on the trajectory of the ball. Vision-based estimation of the ball's spin during a game with conventional cameras is challenging due to the ball's small size, high speed, and fast rotation. To address these challenges, we propose an event-based active vision system that can track unmodified balls and measure their spin in real-time. The system consists of an event camera for its high temporal resolution and minimal motion blur, high-speed pan/tilt galvanometer mirrors to keep the ball in the field of view, and a low-latency focus-tunable telephoto lens to increase the spatial resolution on the ball and keep it in focus. To track the ball, we use a hybrid approach that combines 2D event-based detection for centering and 3D positions from a ball localization system for re-initialization. For high-accuracy spin estimation, we propose an offline method that performs contrast maximization on the sphere (s-CMax). This method achieves state-of-the-art accuracy on static balls across multiple sports (table tennis, baseball, tennis, and golf), with mean magnitude and axis errors of 2.1% and 4.0 degrees, respectively. We then develop a low-latency online method for table tennis as a case study in real-time applications. This method uses an uncertainty-aware convolutional neural network trained on pseudo-ground-truth spin labels from the offline approach, combined with a GPU-accelerated batch implementation of contrast maximization for refinement. We demonstrate reliable tracking and spin estimation with a three-view setup during professional table tennis matches, with high accuracy (8.8% magnitude and 6.4 degrees axis mismatch), 3 ms latency, and 750 Hz throughput.
### Title:
          Learning Adversarial Augmentation Policies for Robust Garlic Seedling Detection
 - **Authors:** Soeun Lee, Chanho Kim, Yeji Kang, YoungKi Hong, Byeongkeun Kang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate seedling detection during early growth stages is essential for timely replanting and effective crop management in precision agriculture. However, existing studies are mostly evaluated under relatively stable imaging conditions, such as UAV imagery or greenhouse environments, leaving robust detection under severe and spatially heterogeneous illumination in ground-based outdoor monitoring insufficiently explored. In addition, many illumination-robust detection methods rely on additional enhancement or feature-extraction modules, which increase inference-time overhead and are not tailored to seedling detection and downstream missing seedling localization. To address these gaps, we construct a new garlic seedling dataset captured using a ground-based monitoring platform under real outdoor field conditions with highly variable illumination. We further propose an illumination-robust seedling detection framework based on adversarial augmentation policy learning. The proposed method jointly optimizes a stochastic augmentation policy agent and an object detector, enabling the detector to learn robust representations under challenging visual conditions. A structural penalty is introduced to prevent unrealistic distortions while encouraging challenging augmentations during training. Extensive experiments show that the proposed approach achieves an AP$_{50}$ of 91.6%, improving the baseline by 0.9 percentage points and outperforming the previous best-performing method by 0.2 percentage points. For downstream missing seedling localization, it achieves 75.0% precision and a 67.0% F1-score, improving the baseline by 4.8 and 2.0 percentage points, respectively. These results demonstrate the effectiveness of the proposed framework for practical ground-based agricultural monitoring under complex outdoor lighting conditions without additional inference-time computational overhead.
### Title:
          Bridging Vision and Language Concepts through Optimal Transport Semantic Flow
 - **Authors:** Chenyang Zhang, Anqi Dong, Guangming Zhu, Nuoye Xiong, Siyuan Wang, Lin Mei, Liang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Concept Bottleneck Models (CBMs) promise transparent reasoning by predicting through human-interpretable concepts, yet their effectiveness fundamentally depends on how well visual and textual representations are aligned or matched. Existing vision-language CBMs often rely on pre-aligned encoders or global cosine similarity, which obscures fine-grained concept localization and fails to reflect true semantic geometry. In this work, we rethink concept alignment as a dynamic cross-modal transport process instead of static projection and propose the Optimal Transport Flow Concept Bottleneck Model (OTF-CBM). It first learns a data-driven semantic cost via Inverse Optimal Transport to measure cross-modal distances, and then performs unbalanced optimal-transport-based flow matching to model semantic transitions between visual patches and textual concepts. With velocity-based concept activation, OTF-CBM captures interpretable geometric relations without ODE integration. Experiments further show that OTF-CBM achieves superior classification accuracy and concept faithfulness, offering a new geometric and dynamical perspective for interpretable cross-modal reasoning.
### Title:
          GAVEL: Grounded Caption Error Verification and Localization
 - **Authors:** Zixian Gao, Atsushi Hashimoto, Kuniaki Saito
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models (VLMs) often produce hallucinated or inconsistent outputs, where text and images are not properly aligned. Addressing this issue requires not only detecting misalignment but also explaining the discrepancy and localizing its visual evidence. We introduce GAVEL (Grounded Caption Error Verification and Localization), a task that jointly addresses verification, explanation, and localization for image-text pairs. To support systematic evaluation, we also present a corresponding dataset and benchmark. We further train a supervised baseline on the human-annotated training split to assess whether GAVEL provides learnable supervision for these abilities. Experiments show that even strong closed-source models struggle on GAVEL, while the supervised baseline yields consistent improvements across grounding and explanation metrics.
### Title:
          How Much Static Structure Do Code Agents Need? A Study of Deterministic Anchoring
 - **Authors:** Zhihao Lin, Mingyi Zhou, Yizhuo Yang, Li Li
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM-based code agents navigate repositories through keyword search but miss the structural relationships, such as call graphs, inheritance hierarchies, and configuration dependencies, that define how software actually works. This makes agent navigation stochastic and difficult to reproduce across runs. We investigate whether lightweight static analysis can provide deterministic anchors for these agents: stable structural facts injected as plain-text comments that constrain probabilistic exploration and make navigation more predictable. Starting from a strong baseline, Codex from OpenAI, we systematically inject varying granularities of structural annotations and measure their effects on localization, trajectory behavior, and run-to-run stability. Our study identifies what we call the deterministic anchoring effect: static structure helps less by making agents "smarter" and more by making their navigation disciplined and reproducible. Three observations support this finding: (1) Anchoring works: lightweight call/inheritance topology improves function-level localization (+2.2pp Func@5) and shortens trajectories (-1.6 interaction rounds); (2) Anchoring is scale-sensitive: the optimal granularity and directionality depend on repository characteristics, where denser semantics show diminishing returns and hub-heavy projects benefit from inverse-only links that expose "who-calls-me" without forward edges; (3) Anchoring stabilizes: tags raise link-following rate from 0.15-0.18 to 0.21-0.24, roughly halve run-to-run variance, and improve single-run reliability (Pass@1 +3.4 pp) on medium-scale repositories, at the cost of roughly 10% more input tokens. These observations suggest practical guidelines: default to lightweight topology on medium projects, prune forward edges in large repositories, and reserve dense tags for implicit-dependency cases.
### Title:
          Pseudo-Text-Conditioned 3D Grounding DINO for Organ Localization in Abdominal CT
 - **Authors:** Siqi Chen, Han Gong, Keyi Hou, Jingxuan Yang, Sheethal Bhat, Andreas Maier
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable organ localization in abdominal CT can provide spatial priors for downstream trauma analysis. We propose CT-3GDINO, a lightweight 3D detector that adapts a Grounding-DINO-style query-based architecture to fixed organ localization using frozen pseudo-text class tokens instead of a real text encoder. The model combines a Swin3D visual backbone, bidirectional feature enhancement, pseudo-text-guided query selection, and a cross-modality decoder to predict normalized 3D boxes for liver, spleen, left kidney, right kidney, and bowel. We train and evaluate on 193 matched RSNA/RATIC CT volumes with segmentation-derived boxes. The best multi-scale model, trained from scratch, achieves 0.5830 overall top-1 class-wise mAP over 3D IoU thresholds from 0.1 to 0.7, outperforming fixed- and trainable-backbone classification-pretrained variants with 0.5570 and 0.4657 mAP. Performance is strong for coarse localization, with 0.9649 AP at IoU 0.1, but remains limited for strict box alignment, with 0.1552 AP at IoU 0.7. These results establish CT-3GDINO as an open-source baseline for pseudo-text-conditioned 3D organ localization and motivate future work on localization-aware pretraining, richer multimodal conditioning, and injury-focused detection.
### Title:
          FlameVQA: A Physically-Grounded UAV Wildfire VQA Benchmark with Radiometric Thermal Supervision
 - **Authors:** Mobin Habibpour, John Spodnik, Niloufar Alipour Talemi, Fatemeh Afghah
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wildfire monitoring from UAVs requires reliable reasoning over complex aerial scenes, where smoke, scale variation, and occlusions often limit RGB-only interpretation. We introduce FlameVQA, a multiple-choice visual question answering benchmark for UAV-based wildfire intelligence built on FLAME 3, leveraging paired RGB imagery and radiometric thermal TIFFs for temperature-grounded, safety-critical reasoning. FlameVQA includes 34 multiple-choice questions per image spanning six operational capability groups, covering tasks such as detection, localization, distribution/coverage estimation, cross-modal reasoning, and flight planning. To ensure label reliability, we combine MLLM-assisted annotation with deterministic thermal rules and cross-question consistency checks, followed by human auditing. We also evaluate representative MLLMs on FlameVQA to provide baselines for future work. Results show strong performance when explicit cross-modal cues are available, but notable failures on presence detection under heavy smoke and on coverage estimation. These findings suggest that current MLLMs require domain-specific adaptation to better support disaster and wildfire monitoring. The dataset and benchmark code are open-source at this http URL
### Title:
          LMs as Task-Specific Knowledge Bases: An Interpretability Analysis
 - **Authors:** Amit Elhelo, Amir Globerson, Mor Geva
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Language models (LMs) capture large amounts of factual knowledge applicable to a wide range of tasks, motivating the view of their parameters as a knowledge base. An important property of knowledge bases is that different queries for the same fact return consistent results, drawing on a single source of truth. We investigate whether LMs satisfy this property through behavioral and mechanistic analyses. Our results suggest that they encode knowledge in a task-specific manner. Behaviorally, facts acquired on one task frequently fail to co-emerge on others during training. Parameter localization experiments suggest a mechanistic explanation, revealing distinct parameter subsets underlying different tasks for the same fact. Finally, we show that chain-of-thought reasoning draws part of its effectiveness from engaging task-specific parameters beyond those tied to the evaluation task. Our findings suggest that what the model knows and how it is asked are intertwined in parameter space, undermining the "knowledge base" analogy and carrying implications for the reliability and controllability of factual knowledge in LMs.
### Title:
          See & Sniff: Learning Visuo-Olfactory Representations
 - **Authors:** Seongyu Kim, Seungwoo Lee, Hyeonggon Ryu, Joon Son Chung, Arda Senocak
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While modern multimodal models integrate vision with language, audio, or touch, olfaction remains largely unexplored due to the lack of paired visuo-olfactory data. We introduce SmellNet-V, a scalable visuo-olfactory dataset built on the insight that odor identity is largely invariant to visual transformations within a semantic category. This allows us to synthetically pair smell-only samples with semantically aligned in-the-wild web images, converting a unimodal olfactory dataset into a cross-modal benchmark without costly co-collection. Building on this dataset, we propose See & Sniff, a self-supervised framework that learns joint visuo-olfactory representations via dense local alignment and naturally produces smell saliency maps for spatial grounding of odor sources. We further introduce pixel-level smell localization task and a benchmark for evaluation. Our method surpasses smell-only baselines by 7% in smell classification from smell alone and generalizes to cross-modal retrieval and smell localization, establishing visuo-olfactory learning as a new direction in multimodal perception.
## Keyword: transformer
### Title:
          HierBias: Context-Conditioned Hierarchical Media Bias Detection with Multi-Task Type Classification
 - **Authors:** Kaining Li, Ruichen Yan, Yuxin Dong
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Media bias detection is a critical task for ensuring fair and balanced information dissemination, yet existing sentence-level approaches classify each sentence independently, ignoring inter-sentence contextual signals that human annotators naturally exploit. We present \textbf{HierBias}, a hierarchical context-conditioned media bias detector that formally models document context in bias prediction. We introduce the \emph{context-conditioned bias probability} and prove theoretically that leveraging document context strictly reduces the Bayes error of sentence-level classification when inter-sentence mutual information is non-zero. A multi-task generalization bound further establishes that jointly training binary bias detection and fine-grained bias type classification improves sample efficiency on small annotated corpora. Architecturally, HierBias pairs a sentence-level RoBERTa encoder with a cross-sentence Transformer aggregator and dual output heads for binary detection and four-class type classification. Evaluated on BABE and BASIL, HierBias achieves 0.853 F1 and 0.723 MCC, surpassing the state-of-the-art bias-detector by $+2.6\%$ F1 and $+4.3\%$ MCC (McNemar's test, $p < 0.05$). Ablation experiments confirm that each theoretical component contributes independently and consistently.
### Title:
          Low Resource Multimodal Translation of Nepali Spoken Words into Emotion-Conditioned Sign Language Avatars
 - **Authors:** Jatin Bhusal, Salma Tamang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sign language communication systems, that integrate emotional expression remain underexplored, particularly for low-resource languages. This pilot study presents NEST-V1 (Nepali Emotion and Speech Transformer - Version 1), a proof-of-concept multimodal framework that demonstrates the feasibility of generating emotion-conditioned Nepali Sign Language avatars from spoken input. As a preliminary investigation, we focus on four common Nepali words ("thank you", "hello", "house", "me") across three emotional states (happy, neutral, sad) to validate our core technical approach. Our lightweight architecture employs a shared acoustic encoder for simultaneous Automatic Speech Recognition and emotion classification, achieving 81.1% ASR accuracy and 79.21% emotion recognition accuracy on a dataset of 600 labeled audio samples from 50 speakers. The system demonstrates 37% parameter efficiency compared to separate model architectures while maintaining a lightweight footprint with only 22.1M parameters suitable for edge deployment. This pilot work establishes the technical foundation for emotion-aware sign language translation in low-resource settings and provides a scalable framework for future expansion to larger vocabularies and more diverse emotional expressions. Our preliminary results indicate the viability of real-time, emotionally expressive sign language communication systems for the hearing-impaired community, with clear pathways for enhancement in subsequent development phases.
### Title:
          Unsupervised Memory-Enhanced Video Transformers: Obstacle Detection for Autonomous Agricultural Rover
 - **Authors:** Théo Biardeau (XLIM-ASALI, UFR SFA (Poitiers)), Anne-Sophie Capelle-Laizé (UP, XLIM-ASALI, XLIM-ASALI), Salwan Alwan, David Helbert (UFR SFA (Poitiers), XLIM-ASALI, LabCom I3M (Poitiers))
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While autonomous rovers have become indispensable to precision farming, achieving consistent operational safety remains a critical challenge. Conventional safety sensors, such as LiDAR, fail to detect obstacles positioned below the plant canopy, posing a significant risk. While camera-based supervised learning methods can detect common objects, they perform poorly when faced with obstacles that were not present in their training data. Actual unsupervised anomaly detection offers a solution by learning the normal visual patterns of an environment, but often fails for the dynamic scenes captured by a moving rover.\\ This paper introduces Video Memory Transformers for Anomaly Detection (VMTAD), a fully unsupervised method designed for real-time obstacle detection in dynamic agricultural scenes. VMTAD utilizes a transformer-driven architecture augmented with a dedicated memory module. This memory module leverages temporal context by processing encoded representations of preceding frames. This approach enables the system to effectively address the dynamic context caused by the robot's movement. The model is trained using only images that represent normal operation, requiring no data labels.\\ VMTAD was rigorously evaluated on the 'Grillion' agricultural rover. On a challenging rapeseed dataset, VMTAD achieved state-of-the-art performance, reaching a 0.973 detection and 0.997 segmentation Area Under the Receiver Operating Characteristic curve. A lightweight variant provides an optimal balance of high accuracy and real-time inference (14 ms), which is critical for safety, as confirmed by our analysis of the rover's total stopping distance.
### Title:
          Topology-Informed Neural Networks for Flood Detection in Optical and Synthetic Aperture Radar Imagery
 - **Authors:** Sophia Li, Max Zhao, Raghu G. Raj, Tianyu Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Floods frequently impact regions around the world. Rapid and accurate flood detection is crucial for emergency response and timely mitigation of human and economic loss. The expanding availability of satellite data and advances in artificial intelligence have enhanced monitoring of environmental hazards, but many flood events remain challenging to detect because cloud cover obscures optical satellite imagery. Rambour et al. introduced the SEN12-FLOOD dataset and extracted per-image features using a ResNet-50 convolutional neural network backbone, then fed these features into a gated recurrent unit network to show that temporal information can substantially improve accuracy compared to single-image baselines. More recently, Chamatidis et al. showed that a vision transformer can achieve strong performance with popular convolutional architectures. However, these models typically function as opaque black boxes, making it difficult to interpret their decision boundaries, learned features, and internal reasoning, especially in safety-critical domains like remote sensing. In contrast, topological data analysis (TDA) provides a mathematically grounded framework for capturing global structural features of data. TDA has emerged as a powerful tool for analyzing complex imagery, especially imagery with geometrically interpretable structures, of which floods are a prime candidate. In this work, we systematically evaluate topological descriptors for flood detection using the open-source SEN12-FLOOD dataset. By extracting topological features from each image and incorporating them into neural networks, we demonstrate that topological descriptors carry meaningful flood signals independently and complement existing networks to yield more robust and interpretable flood detection systems.
### Title:
          From Clicks to Intent: Cross-Platform Session Embeddings with LLM-Distilled Taxonomy for Financial Services Recommendations
 - **Authors:** Dianjing Fan, Yao Li, Kyaw Hpone Myint, Dwipam Katariya, Alexandre G.R. Day, Pranab Mohanty, Giri Iyengar
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI); Computational Engineering, Finance, and Science (cs.CE); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequential user behavior modeling is widely adopted in industrial recommender systems; however, significant gaps remain in financial services, where pre-login web interactions and authenticated in-app experiences differ drastically. Specifically, pre-login web users typically explore new products, whereas logged-in app users focus on account servicing. Due to the challenge of cross-channel entity resolution (e.g., matching anonymous web sessions to authenticated mobile accounts), web-based intent signals remain underutilized for post-authentication personalization. Existing methods for capturing web-based intent are often ad-hoc and narrow, lacking the flexibility to support both quantitative downstream recommendations and qualitative understanding at scale. In this work, we propose a scalable and dual-purpose intent prediction framework for web-based interactions and demonstrate its applicability for personalization. Our approach transforms raw web clickstreams into two outputs: a self-supervised Transformer encodes multi-modal clickstreams into a compact session embedding, while an LLM-based taxonomy generation and distillation pipeline produces interpretable intent labels. Our system demonstrates that self-supervised clickstream representations combined with LLM-distilled taxonomies can jointly serve quantitative tasks and qualitative understanding in production: on the mobile homepage tile ranking task, the session embedding improves macro Recall@1 by 1.88% and reduces Log Loss by 13.38% over production baselines. On the user conversion prediction task, the embedding outperforms the LLM labels by 4.3% on micro F1, while the distillation layer delivers interpretable labels at ultra-low latency with only a 7% performance drop.
### Title:
          Instruction Bleed: Cross-Module Interference in Prompt-Composed Agentic Systems
 - **Authors:** Ching-Yu Lin, Yifan Liu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Information Retrieval (cs.IR); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Practitioners of prompt-composed agentic systems report a recurring failure mode: editing one prompt module silently shifts the behavior of others despite no shared variable or executable dependency. We formalize this as compositional behavioral leakage (CBL): interference between modules sharing a context window. CBL is enabled by architectural non-isolation: transformer self-attention provides no formal boundary between concatenated modules. We probe CBL on a deployed job-evaluation agent (Claude Sonnet 4.6, 144 trials) through a reusable three-channel protocol that perturbs non-focal modules along volume, content, and form. Only the content channel produces a detectable paired effect (Cohen's d = 0.63, bootstrap 95% CI excluding zero); no recommendation flipped -- a sub-threshold regime invisible to standard QA but compounding across the thousands of decisions a deployed agent makes. CBL is orthogonal to known agent-failure axes (adversarial injection, cognitive degradation, multi-agent fault propagation, privacy leakage). We contribute an operational definition, a reusable protocol, a falsifiable prediction set, and a system-class characterization, establishing cross-module interference measurement as a requirement for prompt-composed agent evaluation.
### Title:
          Layer-Specific Prompt Fusion Discovery via Differentiable Search in Vision Foundation Models
 - **Authors:** Xi Xiao, Xingjian Li, Yunbei Zhang, Cheng Han, Tianming Liu, Tianyang Wang, Runmin Jiang, Jihun Hamm, Xiao Wang, Min Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual prompt tuning has emerged as a parameter-efficient fine-tuning approach for adapting large-scale Vision Transformers (ViTs) to downstream tasks. As its learnable prompts are applied in input and feature spaces, prior to jointly going through attention in transformer layers, the most commonly used scheme for fusing image and prompt tokens is concatenation or addition. In this paper, we aim to study a fundamental yet essential problem in visual prompt tuning: whether a single fusion scheme tends to yield better results, and whether that would be beneficial to develop a hybrid fusion scheme. To this end, we formulate the task as a bi-level optimization problem, and solve it leveraging differentiable architecture search. In this context, the learnable prompts and their fusion schemes are jointly optimized. To enrich the search space in the architecture search, we propose two additional fusion schemes, namely, affine transformation and cross-attention, in addition to concatenation and addition. Extensive experiments on 34 datasets spanning VTAB-1k, FGVC, and HTA show consistent gains over prompt-tuning baselines. With a frozen ViT backbone, our method delivers a favorable accuracy--latency--parameter trade-off compared with VPT-Deep and recent variants. Our findings reveal that how prompts fuse with image tokens plays a significant role in visual prompt tuning, and a hybrid fusion fashion can more effectively leverage layer semantics of ViTs, contributing a novel perspective for visual prompt-tuning research.
### Title:
          At the Edge of Understanding: Sparse Autoencoders Trace The Limits of Transformer Generalization
 - **Authors:** Praneet Suresh, Jack Stanley, Sonia Joseph, Luca Scimeca, Danilo Bzdok
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pre-trained transformers have demonstrated remarkable generalization abilities, at times extending beyond the scope of their training data. Yet, real-world deployments often face unexpected or adversarial data that diverges from training data distributions. Without explicit mechanisms for handling such shifts, model reliability and safety degrade, urging more disciplined study of out-of-distribution (OOD) settings for transformers. By systematic experiments, we present a mechanistic framework for delineating the precise contours of transformer model robustness. We find that OOD inputs, including subtle typos and jailbreak prompts, drive language models to operate on an increased number of fallacious concepts in their internals. We leverage this device to quantify and understand the degree of distributional shift in prompts, enabling a mechanistically grounded fine-tuning strategy to robustify LLMs. Expanding the very notion of OOD from input data to a model's private computational processes, a new transformer diagnostic at inference time is a critical step toward making AI systems safe for deployment across science, business, and government.
### Title:
          Geometry-Aware MCTS for Extremal Problems in Combinatorial Geometry
 - **Authors:** Luoning Zhang, Xu Zhuang, Tianhao Wang, Nathan Kaplan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computational Geometry (cs.CG); Machine Learning (cs.LG); Combinatorics (math.CO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study certain extremal problems in combinatorial geometry that ask about configurations of points in an $n \times n$ grid that satisfy strict, global geometric constraints. Classical exact solvers suffer from combinatorial explosion for these types of problems, and standard reinforcement learning and transformer-based models struggle with the sparse reward "validity cliff" and quadratic token-consumption limits. To overcome these bottlenecks, we propose a Geometry-Aware Monte Carlo Tree Search (MCTS) framework. Our approach strictly enforces geometric constraints through incremental updates to the feasible action space. For constraints about collections of collinear points, like those that occur in the classic No-Three-in-Line problem (Max-N3IL), this mechanism reduces the constraint checking complexity from $O(n^3)$ to $O(n^2)$. To improve search efficiency, we exploit geometric symmetries in two ways: canonical pruning during node expansion to reduce the branching factor, and symmetric batch transitions to accelerate the discovery of promising configurations. We perform extensive experiments and establish new best-known computational results on five out of six of the problems that we considered. Notably, for Max-N3IL we find configurations of size roughly $1.8 n$ for grids of size $82 \le n \le 119$. For the Smallest Complete Set problem, we find configurations of size roughly $0.95 n$, providing new upper bounds within the tested grids. This work establishes Geometry-Aware MCTS as a highly adaptable framework for discovering novel configurations in combinatorial geometry.
### Title:
          Methane-Plume Segmentation From Hyperspectral Satellite Imagery Via Multimodal Deep Learning
 - **Authors:** Brayan Quintero, Jeferson Acevedo, Samuel Traslaviña, Hoover Rueda-Chacón
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient detection of methane plumes is crucial for understanding and mitigating global warming, as accurately identifying and segmenting them in earth observation imagery remain essential for large-scale monitoring. In this work, we propose a multimodal deep learning model that integrates a feature-guided methane enhancement (FGME) mechanism which injects physically meaningful methane cues into transformer-based RGB representations at multiple semantic scales. Our method is evaluated on the MPDataset, where it outperforms the state-of-the-art with improvements of +0.92 in MIoU, +0.87 in MPrecision and +1.01 in Recall. Notably, these gains are obtained with a substantially lower computational cost than other high-performing architectures, resulting in a favorable accuracy-efficiency trade-off for large-scale methane monitoring. These results highlight the potential of efficient multimodal fusion strategies for accurate and scalable methane plume segmentation in real-world remote sensing applications.
### Title:
          Extracting Problem and Method Sentence from Scientific Papers: A Context-enhanced Transformer Using Formulaic Expression Desensitization
 - **Authors:** Yingyi Zhang, Chengzhi Zhang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Digital Libraries (cs.DL); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Billions of scientific papers lead to the need to identify essential parts from the massive text. Scientific research is an activity from putting forward problems to using methods. To learn the main idea from scientific papers, we focus on extracting problem and method sentences. Annotating sentences within scientific papers is labor-intensive, resulting in small-scale datasets that limit the amount of information models can learn. This limited information leads models to rely heavily on specific forms, which in turn reduces their generalization capabilities. This paper addresses the problems caused by small-scale datasets from three perspectives: increasing dataset scale, reducing dependence on specific forms, and enriching the information within sentences. To implement the first two ideas, we introduce the concept of formulaic expression (FE) desensitization and propose FE desensitization-based data augmenters to generate synthetic data and reduce models' reliance on FEs. For the third idea, we propose a context-enhanced transformer that utilizes context to measure the importance of words in target sentences and to reduce noise in the context. Furthermore, this paper conducts experiments using large language model (LLM) based in-context learning (ICL) methods. Quantitative and qualitative experiments demonstrate that our proposed models achieve a higher macro F1 score compared to the baseline models on two scientific paper datasets, with improvements of 3.71% and 2.67%, respectively. The LLM based ICL methods are found to be not suitable for the task of problem and method extraction.
### Title:
          Speaking Numbers to LLMs: Multi-Wavelet Number Embeddings for Time Series Forecasting
 - **Authors:** Defu Cao, Zijie Lei, Muyan Weng, Jiao Sun, Yan Liu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are attractive for context-aware time series forecasting because they can integrate heterogeneous textual signals, yet their discrete, language-oriented tokenization and embedding interfaces are misaligned with continuous numerical values, often harming numerical ordering and forecasting reliability. We propose TempoWave, a plug-and-play temporal wavelet digit interface that maps each scalar observation into digit-wise embeddings constructed from multi-wavelet, multi-scale coefficients. By directly overriding standard token representations, TempoWave seamlessly exposes both fine-grained local fluctuations and macro global structures in a transformer-compatible form, ensuring that precise numerical formatting, distinct digit identity, and robustness to common normalization operations are maintained throughout the LLM pipeline. Experiments across five context-enriched forecasting benchmarks demonstrate that TempoWave consistently improves LLM-based forecasters over standard numeric tokenization and alternative embedding interfaces, achieving a new state-of-the-art. These results highlight the numeric interface as a key bottleneck and suggest that principled multi-resolution embeddings can better couple LLMs' contextual reasoning with precise forecasting. Our code is available at this https URL and our model can be accessed at this https URL.
### Title:
          Nemotron-TwoTower: Diffusion Language Modeling with Pretrained Autoregressive Context
 - **Authors:** Fitsum Reda, John Kamalu, Roger Waleffe, Mostofa Patwary, Mohammad Shoeybi, Bryan Catanzaro
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion language models offer a promising alternative to autoregressive models due to their potential for parallel and iterative generation. However, existing approaches use a single network for both context representation and iterative denoising, forcing one model to serve both roles and limiting its capacity for either role. We propose TwoTower, a block-wise autoregressive diffusion model that decouples these roles into two towers: a frozen AR context tower that causally processes clean tokens, and a trainable diffusion denoiser tower with bidirectional block attention that refines noisy blocks via cross-attention to the context. Built on Nemotron-3-Nano-30B-A3B, an open-weight 30B hybrid Mamba-Transformer MoE model, and trained on approximately 2.1T tokens, Nemotron-TwoTower retains 98.7% of the autoregressive baseline's quality while offering 2.42X higher wall-clock generation throughput. We release the code and model weights at this https URL.
### Title:
          Learning Probabilistic Filters with Strictly Proper Scoring Rules
 - **Authors:** Eviatar Bach, Ricardo Baptista, Jochen Bröcker, Bohan Chen, Andrew Stuart
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Dynamical Systems (math.DS); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bayesian filtering of partially and noisily observed dynamical systems seeks to infer the evolving conditional distribution of the state of a dynamical system, given observations, in an online fashion. This Bayesian filtering distribution is the natural object for uncertainty quantification, but it is rarely available as a supervised learning target. However, one can often use the forecast model to generate synthetic system trajectories, along with synthetic observations. We introduce the proper scoring ensemble filter (PSEF), an ensemble data assimilation method based on training an analysis map to approximate the filtering distribution using only synthetic state--observation trajectories. The analysis step is represented as a permutation-invariant, transformer-based map that takes as input a forecast ensemble and observations, producing an analysis ensemble. Training is based on strictly proper scoring rules -- with the energy score used in our implementation -- so that probabilistic accuracy is rewarded over the whole probability distribution. We prove that, under a realizability assumption, the population objective is minimized by the true Bayesian filtering distribution. We also derive the finite-ensemble empirical objective used in training and relate its single state--observation trajectory form to the population objective, using a mean-field consistency argument. Numerical experiments show that the learned filter accurately approximates challenging filtering distributions, including nonlinear, non-Gaussian, and multi-modal posteriors, and achieves stronger performance in data assimilation tasks than classical methods or learning-based methods with mean-squared-error objectives. For close-to-Gaussian problems, learning a correction to the EnKF is the best approach, while for highly non-Gaussian problems an end-to-end approach that discards this inductive bias is superior.
### Title:
          CascadeFormer: Depth-Tapered Transformers Motivated by Gradient Fan-in Asymmetry
 - **Authors:** Huzama Ahmad, Cao Viet Hai Nam, Se-Young Yun
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep Transformers are composed of uniformly stacked residual blocks, yet their deepest layers often add little value. We present two efficiency methods that exploit this asymmetry. CascadeFormer tapers width with depth to match the uneven information flow across layers, achieving comparable perplexity to a uniform baseline at the same training budget while reducing latency by 8.6% and increasing throughput by 9.4%. CascadeFlow Pruning removes layers using accumulated training gradients, with no post hoc analysis. It outperforms standard heuristics on perplexity and rank-stability and stays competitive on downstream accuracy. To motivate these methods, we propose Gradient Fan-in Asymmetry (GFA) as a structural account of why deeper layers contribute less. In Pre-LayerNorm residual stacks, the gradient at a layer is the sum of an identity path and all downstream functional paths, producing a gradient fan-in that decays linearly with depth (and quadratically under deep supervision), yielding richer gradients for early layers and sparser ones for later layers. We provide correlational and interventional evidence for GFA on models trained from scratch up to 1.2B parameters. Across Transformers and ResNets, accumulated training gradients follow the theoretical fan-in and are associated with post hoc layer importance. Two interventions point to structure rather than magnitude as the bottleneck: equalizing per-layer gradient norms does not restore late-layer value, while increasing downstream path counts via parameter-shared repetition restores and elevates it. Whether gradient magnitude proxies fan-in beyond high-rank regimes, and how these dynamics behave at the 100B+ scale, remain open questions.
### Title:
          PMDformer: Patch-Mean Decoupling Information Transformer for Long-term Forecasting
 - **Authors:** Ao Hu, Liangjian Wen, Jiang Duan, Yong Dai, He Yan, Dongkai Wang, Jun Wang, Yukun Zhang, Ruoxi Jiang, Zenglin Xu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-term time series forecasting (LTSF) plays a crucial role in fields such as energy management, finance, and traffic prediction. Transformer-based models have adopted patch-based strategies to capture long-range dependencies, but accurately modeling shape similarities across patches and variables remains challenging due to scale differences. To address this, we introduce patch-mean decoupling (PMD), which separates the trend and residual shape information by subtracting the mean of each patch, preserving the original structure and ensuring that the attention mechanism captures true shape similarities. Futhermore, to more effectively model long-range dependencies and capture cross-variable relationships, we propose Trend Restoration Attention (TRA) and Proximal Variable Attention (PVA). The former module reintegrates the decoupled trend from PMD while calculating attention output. And the latter focuses cross-variable attention on the most relevant, recent time segments to avoid overfitting on outdated correlations. Combining these components, we propose PMDformer, a model designed to effectively capture shape similarity in long-term forecasting scenarios. Extensive experiments indicate that PMDformer outperforms existing state-of-the-art methods in stability and accuracy across multiple LTSF benchmarks. The code is available at this https URL.
### Title:
          Temporally Consistent Label Interpolation for Robust Surgical Multi-Task Learning under Challenging Conditions
 - **Authors:** Garam Kim, Juyoun Park
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective multi-task learning for surgical scene understanding is fundamentally hindered by annotation granularity mismatch; temporal workflow tasks such as phase recognition, step recognition and anticipation benefit from dense frame-level supervision, whereas pixel-level spatial tasks including instrument segmentation and action recognition are only sparsely annotated on selected keyframes due to prohibitive labeling costs. This supervision imbalance undermines shared representation learning and limits joint optimization across heterogeneous surgical tasks. To address this, we propose Flow-guided Annotation for Robust Operating Scenes (FAROS), a flow-guided label interpolation framework, that combines zero-shot segmentation-based mask propagation with optical flow estimation to overcome the limitations of appearance-based propagation under challenging surgical conditions such as occlusion, smoke, and motion blur, generating temporally consistent dense pseudo labels from sparse keyframe annotations. The densified instrument masks and action labels are integrated into a unified Transformer-based multi-task framework that jointly learns surgical phase recognition, step recognition, anticipation, instrument segmentation, and action recognition, enabling balanced optimization between dense temporal supervision and sparse spatial supervision. The label interpolation quality of FAROS is first validated on the DAVIS 2017 benchmark under a sparse ground-truth protocol, confirming robust propagation beyond the surgical domain. Extensive experiments on GraSP, MISAW, and AutoLaparo benchmarks further demonstrate that FAROS significantly improves cross-task representation learning and enhances holistic surgical scene understanding performance across spatio-temporal tasks.
### Title:
          Learning Motion Feasibility from Point Clouds in Cluttered Environments
 - **Authors:** Sajid Ansari, Arthi, Girish Varma, Antony Thomas
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Motion feasibility prediction plays a central role in robotics, particularly in task and motion planning and manipulation. A major bottleneck for this problem in cluttered environments is that infeasible planning attempts by Sampling-based motion planners (SBMPs) can incur substantial computational cost. Also existing approaches for infeasibility certification are limited to low-dimensional configuration spaces and often assume simplified geometric environments represented by primitive objects with known parameters. We study the complementary problem of learning motion feasibility prediction directly from raw RGB-D observations for a 7-DOF manipulator operating in realistic cluttered scenes. We introduce the first large-scale benchmark for this setting, comprising 2.7M grasp feasibility labels over 88 scanned objects and 190 cluttered tabletop scenes. We benchmark three representative classifier families spanning MLP- based, volumetric-CNN, and point-cloud-based Transformer architectures under matched training conditions. Our best model, GRASPFC-PTX (a point-cloud transformer), achieves an AUROC of 0.996 on Novel objects while providing predictions significantly faster than SBMPs.
### Title:
          LearniBridge: Learnable Calibration of Feature Caching for Diffusion Models Acceleration
 - **Authors:** Xuyue Huang, Zhe Chen, Wang Shen, Xiao-Ping Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) have driven substantial progress in image and video generation but suffer from prohibitive computational costs. Feature caching accelerates inference by reusing intermediate representations. Existing methods rely on historical features for implementation simplicity, yet suffer from severe error accumulation at high acceleration ratios. To address this limitation, we investigate the nature of the requisite feature correction. We demonstrate that the optimal calibration update is characterized by a shared low-rank subspace across diverse prompts. Guided by this structural insight, we propose LearniBridge, a learnable calibration mechanism for feature caching that bridges multiple timesteps through lightweight LoRA updates. This mechanism enables effective calibration requiring only 3-5 training samples. Extensive experiments on image and video generation show that LearniBridge achieves up to $5.87\times$, $5.75\times$, and $4.10\times$ acceleration on FLUX, HunyuanVideo, and WAN2.1, respectively. On WAN2.1, it improves VBench by 1.28% over the previous SOTA at $4.10\times$ acceleration. Our code is available at this https URL.
### Title:
          Modeling Local, Global, and Cross-Modal Context in Multimodal 3D MRI
 - **Authors:** Minh Duc Do, Tillmann Rheude, Noel Kronenberg, Roland Eils, Benjamin Wild
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Brain MRI poses a fundamental challenge for machine learning: models must learn from high-dimensional 3D data spanning multiple co-registered modalities, despite the limited sample sizes typical of neuroimaging studies relative to the diversity in anatomy, pathology, and acquisition conditions. While multimodal imaging provides complementary information critical for clinical interpretation, effectively integrating these signals remains difficult. We propose Multimodal Intra- and Cross-Context Vision Transformer (MICViT), a 3D vision transformer that explicitly models both modality-specific representations and cross-modal interactions across local and global contexts. Concretely, MICViT combines four attention mechanisms: modality-specific local and global attention for intra-modal feature learning, and cross-modal local and global attention to capture interactions between modalities. We evaluate MICViT on brain age prediction across three heterogeneous datasets (UK Biobank, n=41,404; SOOP, n=1,062; Cam-CAN, n=613) using multiple MRI modalities (e.g. T1, FLAIR, DWI, SWI). MICViT consistently outperforms state-of-the-art CNN and transformer baselines in 3D settings. Notably, it benefits more strongly from multimodal inputs, yielding larger performance gains as additional modalities are incorporated. These results demonstrate that explicitly modeling intra- and cross-modal interactions is key to unlocking the full potential of multimodal brain MRI, highlighting a promising direction for representation learning in neuroimaging.
### Title:
          Auditing Framing-Sensitive Behavioral Instability in Large Language Models for Mental Health Interactions
 - **Authors:** Abla Bedoui, Ashley L. Greene, Mohammed Cherkaoui
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are increasingly being integrated into mental health support tools and other psychologically sensitive conversational applications. In such settings, behavioral stability and consistency are important for trustworthy human-AI interaction. However, semantically similar concerns can be presented through different contextual framings, potentially eliciting different model responses. Such framing-sensitive variability may challenge user expectations regarding system behavior and complicate the assessment of AI reliability. While prior studies have primarily examined such effects at the behavioral level, less is known about how framing-related variation is reflected in the internal representations of aligned language models. In this work, we investigate these effects using controlled matched prompts spanning multiple contextual framing conditions across several instruction-tuned model families. Across architectures, framing systematically alters interpretive response tendencies. Layer-wise probing analyses show that behavior-associated information remains decodable throughout transformer depth, with architecture-dependent variation in decoding strength. Moreover, held-out framing probes remained consistently above chance across architectures despite strong lexical baselines. Activation steering experiments further suggest that framing-associated representational directions can partially modulate downstream behavioral outcomes. Finally, these findings indicate that robustness to contextual variation may represent an important consideration when evaluating the consistency and trustworthiness of conversational AI systems deployed in mental-health-oriented interactions.
### Title:
          SubdivAR: Autoregressive Next-Scale Prediction for Neural Mesh Subdivision
 - **Authors:** Huipeng Guo, Zikai Song, Hang Long, Jielei Zhang, Wenbing Li, Junkai Lin, Tianhao Zhao, Jinshen Zhang, Tianle Guo, Wei Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mesh subdivision is a fundamental operation for converting coarse, editable meshes into high-resolution surfaces, with broad applications in digital asset creation. Classical rule-based schemes rely on fixed local refinement rules and often produce over-smoothed surfaces. Recent neural subdivision methods improve detail synthesis, but remain constrained by local modeling and exhibit limited generalizability. We present SubdivAR, a neural mesh subdivision framework based on our proposed Mesh Autoregressive Representation (MAR). MAR arranges meshes at different subdivision levels into an ordered scale sequence, reformulating subdivision as autoregressive next-scale prediction. To support this formulation, we introduce a Hybrid Topology-Aware Transformer that combines global semantic attention with topology-constrained local feature aggregation. SubdivAR adopts a next-scale coordinate prediction paradigm, regressing vertex offsets at each refinement stage to preserve subdivision topology while recovering fine-grained geometric details. To enable reliable learning, we construct FII-40K, a curated dataset of nearly 40,000 high-quality meshes with multi-level subdivision supervision. Experiments show that SubdivAR outperforms state-of-the-art baselines, reducing Hausdorff Distance and Chamfer Distance by 18.8% and 14.2%, respectively, and demonstrates strong robustness on complex open-surface geometries.
### Title:
          TMP: Tree-structured Mixed-policy Pruning for Large-scale Image Generation and Editing
 - **Authors:** Peizhen Zhang, Yang Li, Xunsong Li, Songtao Liu, Zewen Liu, Qiangqiang Hu, Guotong Guo, Jupeng Ding, Yifu Sun, coopersli, Jian Zhang, Zhao Zhong, Liefeng Bo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern image generation model rapidly grows their sizes to meet high-fidelity image synthesis. However, they gradually become unaffordable for their enormous parameter consumption and computation budget that lead to massive resources requirement and gpu memory footprint. In this paper, we propose TMP, the first Tree-structured Mixed-policy Pruning framework that generalizes prevalent image tasks (T2I and TI2I) and architectures (Mixture-of-Experts (MoE) and Diffusion transformer (DiT)). It could be applied to the step-distilled models and contribute as the last stage. We perform experiments upon current open-sourced SOTA HunyuanImage-3.0 instruct and a popular efficient model Z-Image turbo. The proposed pruning framework manages to compress HunyuanImage 3.0 from 80B to 20B parameters at 75% reduction ratio, sacrificing limited generation quality. We also optimize to enable the inference of the pruned 20B version of HunyuanImage 3.0 on a single 24GB 4090 GPU by engineering skills. The inference script and model weight have been integrated into the existing HunyuanImage3.0 open-source github and huggingface repository. Besides, we prove the efficacy of TMP by compressing Z-Image turbo from 6B to 4B (33% reduction) with negligible degradation.
### Title:
          Transformer-Based Classification of Bacterial Raman Spectra with LOOCV
 - **Authors:** Jamile Mohammad Jafari, Thomas Bocklitz
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based models have recently attracted increasing attention for Raman spectral classification. In this study, a transformer-based approach was systematically evaluated using a nested leave-one-replicate-out cross-validation framework and compared with conventional machine-learning pipelines combining PCA or ICA with LDA, SVM, and Random Forest classifiers. A bacterial Raman dataset comprising 5,417 single-cell spectra from six bacterial species and nine independent measurement replicates was used. The transformer consistently achieved the highest classification performance across independent test replicates and significantly outperformed all conventional approaches. Analysis of the learned latent feature space revealed improved class separation compared with PCA- and ICA-based representations. Furthermore, the transformer maintained superior performance when applied directly to raw Raman spectra without preprocessing, demonstrating robust behavior across measurement replicates. These findings highlight the potential of transformer-based models for robust Raman spectral classification and emphasize the importance of replicate-aware validation for realistic model evaluation.
### Title:
          Hierarchical Muon: Tiled Newton-Schulz Updates for Efficient Muon Optimization
 - **Authors:** Ziyuan Tang, Tianshi Xu, Yousef Saad, Yuanzhe Xi
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Muon-type optimizers construct update directions for dense neural-network weights by applying a finite Newton-Schulz map to momentum-gradient matrices. For an $H \times W$ matrix, with $r=\min\{H,W\}$ and $s=\max\{H,W\}$, $K$ steps of the full-matrix Newton-Schulz update require $O(r^2 s K)$ work and couple all rows and columns through repeated Gram matrix products. We introduce Hierarchical Muon (HiMuon), a tiled Newton-Schulz scheme for Muon-type optimization. HiMuon partitions each momentum-gradient matrix into $T \times T$ tiles, applies the same finite Newton-Schulz map independently to each tile, and reassembles the results. For finite $T$ below the matrix dimensions, HiMuon defines a local matrix-function map rather than a convergent approximation to the full-matrix update: spectral interactions are preserved within tiles and discarded across tile boundaries. For fixed finite $T$, the leading Newton-Schulz work decreases to $O(H W T K)$, and the computation decomposes into independent small dense matrix operations. This structure enables tile-size-dependent GPU kernels, cross-layer batching, memory-bounded chunking, and runtime tile-size schedules. Experiments on transformer training and controlled matrix-function diagnostics show that HiMuon improves optimizer-step efficiency while keeping training behavior close to full-matrix Muon in the tested regimes.
### Title:
          CARVE: Content-Aware Recurrent with Value Efficiency for Chunk-Parallel Linear Attention
 - **Authors:** Sayak Dutta
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recurrent models must forget in order to remember, yet the state of the art decides what to erase without consulting what is stored -- the gate sees only the arriving token, not the memory it is about to modify. This memory-blind gating is one of three coupled defects in the leading delta-rule architecture (GDN-2): the value-axis erase mask wastes parameters at the scale of the value projection, and -- as we prove -- mathematically prevents the WY-form triangular chunk solver that makes recurrent training competitive with Transformers. We introduce CARVE (Content-Aware Recurrent with Value Efficiency), which resolves all three problems through one principle: erase only on the key axis. This is provably necessary and sufficient for the WY-form solver to remain valid. Within it, CARVE reuses the recurrent output tensor -- already written to GPU memory -- as a free content signal for the erase gate, and replaces the per-value write-gate projection with a single scalar per head. At initialisation CARVE is bit-identical to GDN-2; any quality difference emerges from what the content gate learns. At 1.3B parameters trained on 100B tokens, CARVE achieves WikiText perplexity 15.72 (minus 0.18 vs. GDN-2, a 4.5-sigma effect), leads every recurrent baseline on nine common-sense reasoning benchmarks, and sets state of the art on every RULER retrieval probe -- at 0.4% throughput overhead, 13% lower peak memory, and 19% fewer parameters. Six formal theorems cover memory capacity, Lyapunov stability, gradient flow, expressivity separation, Pareto-optimal chunk size, and hybrid optimality.
### Title:
          Evaluating Architectural Trade-offs in CGRAs: The Impact of Scratchpad Memory and Heterogeneity on Compute-Intensive Kernels
 - **Authors:** María José Belda, Lara Orlandic, Fernando Castro, Miguel Peón-Quirós, Katzalin Olcoz, David Atienza
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern edge computing applications, particularly high-throughput stream processing like Vision Transformers (ViTs), demand massive spatial parallelism and efficient data movement under tight power and area constraints. Coarse-Grained Reconfigurable Architectures (CGRAs) offer a promising paradigm to balance performance, flexibility, and energy efficiency. This paper analyzes the impact of two critical CGRA design choices: processing element heterogeneity and local data reuse support. We evaluate essential computational kernels (Fast Fourier Transform (FFT) and General Matrix Multiply (GEMM)) alongside an end-to-end seizure detection transformer workload across two distinct configurations: a baseline homogeneous architecture and a heterogeneous evolution integrating specialized functional units with an Scratchpad Memory (SPM). Our evaluation demonstrates that the SPM significantly optimizes data movement, reducing memory traffic eightfold compared to a memory-less design. While the heterogeneous architecture achieves superior energy efficiency for data-shuffling tasks, the homogeneous design minimizes area overhead by 4.4x to 8.2x relative to state-of-the-art CGRAs. Furthermore, it sustains a 700 MHz operating frequency, enabling up to a 5x execution speedup over the heterogeneous configuration during matrix computations. Ultimately, this work provides an architectural roadmap for selecting CGRA fabrics based on the arithmetic intensity, performance goals, and resource envelopes of edge-scale workloads.
### Title:
          RSPC: A Benchmark for Modeling Stress and Psychiatric Conditions in Digitally Mediated Relationships using Psychiatrist Annotations
 - **Authors:** Parmitha Vangapandu, Sai Ganesh Mokkapati, Sathwik Narkedimilli, MSVPJ Sathvik, Timothy Liu, Simon See, Johannes C. Eichstaedt
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In NLP, mental health conditions are often modeled as isolated phenomena, without interpersonal context. We use Reddit posts about long-distance relationships to capture both mental health distress and associated relational triggers. We introduce the Relational Stress and Psychiatry Corpus (RSPC) containing 1,799 Reddit posts annotated by psychiatrists for diagnostic categories, including the most prevalent mood disorders (anxiety and depression), relational stressor triggers, and indications of relationship phase. We benchmark seven fine-tuned transformer models and five large language models across multi-label disorder classification, relational trigger detection, and temporal phase prediction tasks. We find clear task-dependent differences between model families, with Claude-3-Haiku achieving the best disorder classification performance (Macro-F1 = 0.538) and GPT-4o obtaining the strongest relational trigger detection performance (Macro-F1 = 0.519), suggesting distinct model capabilities. We further find strong associations between anxiety disorders and chronic relational uncertainty. Overall, RSPC establishes a benchmark for NLP tasks that consider relational context and supports a shift from individual-centric to context-aware mental health modeling that captures the social and temporal dynamics of distress.
### Title:
          EO-WM: A Physically Informed World Model for Probabilistic Earth Observation Forecasting
 - **Authors:** Junwei Luo, Shuai Yuan, Zhenya Yang, Yansheng Li, Zhe Liu, Hengshuang Zhao
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Earth Observation (EO) forecasting aims to predict future Earth surface dynamics from satellite observations under changing meteorological conditions. In this paper, we view this task as a partially observed, weather-driven world modeling problem, in which weather acts as a conditioning signal, while forecasting remains uncertain due to sparse observations and unobserved land-surface states. However, existing methods do not fully capture this setting: deterministic models collapse uncertainty into a single future prediction, while diffusion-based methods typically treat weather variables as undifferentiated conditioning signals, and existing benchmarks focus mainly on reconstruction accuracy rather than whether forecasts respond correctly to changed weather this http URL introduce EO-WM, a video diffusion transformer for multispectral EO forecasting. EO-WM incorporates a physically informed conditioning framework that represents meteorological forcing through a climatological baseline, weather anomalies, and cumulative physical stress signals. Specifically, it separates baseline and anomaly through distinct conditioning pathways, and accumulates anomalous forcing over time to capture sustained heat and drought stress. To evaluate weather-response behavior beyond standard metrics, we introduce two diagnostic benchmarks: an Extreme Summer Benchmark for severity-aware prediction of vegetation degradation under extreme weather, and a Seasonal Matched-Pair Benchmark for testing response fidelity under changed weather forcing. Experiments show that EO-WM reduces the error in predicted Normalized Difference Vegetation Index (NDVI) decline amplitude by a relative 5.63% and improves directional hit rate by a relative 7.80%, while remaining competitive on standard pixel-level metrics. The benchmarks and model will be made open-source at this https URL.
### Title:
          How Good Can Linear Models Be for Time-Series Forecasting?
 - **Authors:** Lang Huang, Jinglue Xu, Luke Darlow
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time-series forecasting research has been moving steadily toward larger architectures, from specialized transformers to general-purpose foundation models, on the assumption that capacity is what unlocks accuracy. We take the opposite position: most of the gap can be closed at far lower cost by tuning preprocessing rather than scaling models. We use Ridge regression as the testbed, since it has a closed-form solution and interpretable weights, which let the optimal hyperparameters be read off the search directly. We search over context length, local normalization, regularization, and augmentation on eight standard benchmarks and find three patterns. (1) Optimal lookback is strongly series-specific and often non-monotonic in forecast horizon, with fitted power-law exponents ranging from $+0.46$ on ETTm2 to $-0.19$ on Exchange and Traffic, challenging the convention that longer horizons need longer history. (2) Normalizing over a learned trailing fraction of the context, rather than its entirety, is almost universally preferred. (3) Series within the same dataset often disagree on hyperparameters; the optimal degree of cross-series sharing varies from fully shared to fully per-series. The resulting models beat prior linear forecasters on most dataset-horizon entries and exceed Transformer, MLP, and CNN baselines on six of eight benchmarks. The optimized hyperparameters also serve as a diagnostic on the data itself, revealing structures that larger models absorb silently into their learned parameters.
### Title:
          RoPEMover: Depth-Aware Object Relocation via Positional Embeddings
 - **Authors:** Ipek Oztas, Duygu Ceylan, Aybars Bugra Aksoy, Aysegul Dundar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Moving an object in a single image requires geometry-consistent spatial rearrangement, including handling occlusions, revealing previously unseen regions, and maintaining coherent shadows and reflections. Existing approaches are not well suited to this setting and often fail to preserve such scene-level consistency. We address this problem by introducing a geometry-aware object motion method that operates directly on the positional representations of diffusion transformers. Our key insight is that rotary positional embeddings (RoPE) define a structured spatial field that can be explicitly manipulated to induce controlled motion. We extend 2D RoPE into a depth-aware formulation that encodes 3D spatial structure, enabling consistent object displacement and scene-aware updates. Our model is trained using synthetic data combined with a small set of real images via parameter-efficient fine-tuning. Despite minimal real supervision, it preserves object identity under large spatial displacements, generates plausible content in newly revealed regions, and consistently updates scene-dependent effects such as shadows and illumination. Experimental results on standard object motion benchmarks demonstrate state-of-the-art performance across all evaluation metrics.
### Title:
          RayPE: Ray-Space Positional Encoding for 3D-Aware Video Generation
 - **Authors:** Minghao Yin, Jiahao Lu, Wenbo Hu, Wang Zhao, Shan Ying, Kai Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern video diffusion transformers position their tokens through RoPE on the (u,v,t) axes -- a description of the camera's sampling grid that says nothing about the 3D structure of the scene. We observe that the geometric relation between two camera rays is captured by the Plucker reciprocal product, which is bilinear in the two rays -- the same algebraic form as the dot product in Transformer attention. Building on this analogy, we propose RayPE, a positional-encoding extension that injects per-token 6D Plucker coordinates additively into the queries and keys of self-attention, with a query/key flip arrangement under which the symmetric identity configuration coincides exactly with the reciprocal product. The injection is additive, the resulting attention score decomposes into a content term, a geometry term, and two content and geometry cross-terms -- all of which our experiments find individually necessary. To make the encoding stable across video data with heterogeneous camera-translation scales (SfM, deep SLAM, metric), we further decouple ray direction from moment magnitude, gate the encoding by a learned function of the log-magnitude, and apply RMSNorm to align it with the QKNorm-normalized content branch. The full module adds less than 0.1% parameters to a pretrained video DiT, is zero-initialized to start from the pretrained weights, and improves camera controllability, cross-frame 3D consistency, and overall video quality on a four-dataset training mixture.
### Title:
          PhysiFormer: Learning to Simulate Mechanics in World Space
 - **Authors:** Yiming Chen, Yushi Lan, Andrea Vedaldi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present PhysiFormer, a diffusion transformer for physically-plausible 3D object motion. Unlike video world models that operate in view-dependent pixel space, PhysiFormer represents objects as 3D meshes expressed in world coordinates. Given the initial vertex positions and velocities, as well as object material type, rigid or elastic, the model samples future vertex trajectories. While related neural physics approaches build on ad-hoc latent spaces or explicitly enforce rigidity and causality, PhysiFormer shows that excellent results can be obtained without any such inductive biases, by casting vertex trajectory prediction as a single denoising diffusion process directly in world coordinates. The probabilistic formulation captures uncertainty in the learned dynamics, enabling diverse plausible futures from initial conditions, making this framework potentially useful for applications with unobserved uncertainty. The model features attention factorised over time, space, and objects for efficiency, enabling permutation-invariant multi-object reasoning without needing explicit object encoding. Trained on over 100k simulated trajectories, PhysiFormer generates rigid and elastic mechanics, and generalises to mixed-material settings, unseen real-world geometries, and larger object counts. It substantially outperforms autoregressive baselines in trajectory accuracy, rigidity preservation, and momentum-based physical consistency. Our results position coordinate-space diffusion as a promising step toward view-invariant, geometry-aware world modelling for robotics, graphics, and physical design. Visualisations, code, and models are available at this https URL.
### Title:
          DnA: Denoising Attention for Visual Tasks
 - **Authors:** Ron Campos, Subhajit Maity, Xin Li, Srijan Das, Aritra Dutta
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The softmax activation in multihead attention (MHA) is the de facto standard for attention-based models in visual perception tasks. However, standard softmax can produce noisy attention patterns that dilute relevant features and degrade its performance. In this paper, we propose Denoising Attention or DnA, in which, first, a positive query identifies which image features belong to the correct class, and a negative query identifies closely associated but irrelevant image features. DnA then projects these interactions into two distinct subspaces with larger principal angles, promoting subspace separation and improved discriminability. Using a ViT-B backbone, our proposed DnA achieves an absolute gain of 0.8% on ImageNet-1K compared to the baseline. We further show improvements across multiple visual understanding tasks, including video understanding with video transformers (1.8%) and video LLMs (0.5%). Our extensive empirical analyses justify the design choices involving two interacting subspaces and the denoising effect of DnA.
### Title:
          Scalable Behavior Cloning with Open Data, Training, and Evaluation
 - **Authors:** Arthur Allshire, Himanshu Gaurav Singh, Ritvik Singh, Adam Rashid, Hongsuk Choi, David McAllister, Justin Yu, Yiyuan Chen, Huang Huang, Pieter Abbeel, Xi Chen, Rocky Duan, Phillip Isola, Jitendra Malik, Fred Shentu, Guanya Shi, Philipp Wu, Angjoo Kanazawa
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce ABC, a fully open-source stack for manipulation with behavior cloning. At its core is ABC-130K: the largest open-source teleoperation dataset to date, featuring 3,500 hours of data spanning over 130K episodes across 195 diverse tasks. Furthermore, we open-source our accessible hardware setup, training infrastructure, and simulation pipeline. We also release 400 hours of sim-teleop data and provide a co-training recipe that produces correlated simulation and real-world evaluation, offering a reliable proxy for ablating model-design and training decisions before costly real-world evaluation. We explore various training recipes and compare common architectural choices for Diffusion Transformers (DiT) and Vision-Language-Action (VLA) models, grounding our findings in real-world evaluations. The resulting policies successfully execute dexterous tasks such as box folding and extracting credit cards from wallets. By providing a reproducible toolkit, we aim to place researchers on an equal footing, establishing the necessary foundation to learn the ABCs of Behavior Cloning together as a community.
## Keyword: autonomous driving
### Title:
          Rethinking Training & Inference for Forecasting: Linking Winner-Take-All back to GMMs
 - **Authors:** Qiyuan Wu, Katie Z Luo, Bharath Hariharan, Wei-Lun Chao, Mark Campbell
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Trajectory forecasting for autonomous driving has advanced rapidly, yet representative models often produce uninformative posteriors over forecast modes, causing problems for mode pruning. We trace this to a modeling-training mismatch: forecasters are typically modeled as conditional Gaussian mixture models (GMMs) but trained with a winner-take-all (WTA) loss that assigns each sample to its nearest mode. We argue that this K-means-like hard assignment (one-hot), while preventing mode collapse, is the source of uninformative mode probabilities: it over-segments the trajectory space, ignores relatedness among nearby modes, and yields assignment instability under small perturbations. Guided by this lens, we introduce two post-hoc treatments: (1) test-time posterior-weighted merging that aggregates nearby candidate trajectories; and (2) a one-step expectation-maximization (EM) update that replaces hard labels with soft responsibilities, sharing probability mass across neighboring modes. Across several WTA-trained architectures, these lightweight steps produce more informative, faithfully ranked mode posteriors and strengthen final forecasts on popular displacement metrics -- without retraining. Our analysis unifies recent design choices through a GMM-vs-K-means perspective and offers principled, practical corrections that better align training objectives with inference.
### Title:
          Towards Safety-Aware Mutation Testing for Autonomous Driving Systems
 - **Authors:** Donghwan Shin
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simulation-based testing is essential for ensuring the safety of Autonomous Driving Systems (ADS), yet the community lacks a systematic criterion for determining when we can safely stop additional test scenario generation. Existing coverage metrics typically focus on individual component reliability or treat the ADS as a black box, failing to capture certain component interactions that cause most ADS accidents. While traditional mutation testing provides a falsifiable measure of test adequacy, directly porting code- and deep learning model-level mutations to the corresponding modules of ADS is insufficient. In this vision paper, we propose a paradigm shift toward Safety-Aware Mutation Testing (SAMT). Unlike traditional mutation testing, which creates mutants (i.e., faulty versions of the software under test) by injecting artificial faults into individual components, SAMT systematically injects temporally bounded faults into the messages exchanged between ADS modules to simulate realistic interaction failures. To ensure these mutants represent genuine hazards, we propose deriving mutant generation rules directly from top-down safety engineering frameworks, such as System-Theoretic Process Analysis (STPA). By embedding systems thinking into the mutation testing pipeline, SAMT provides a rigorous mechanism for evaluating test adequacy, enabling automated scenario generation, and guiding ADS repair. We also outline critical open challenges.
### Title:
          Revisiting Action Factorization for Complex Action Spaces
 - **Authors:** Timothy Flavin, Sandip Sen
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many real-world control problems involve hybrid discrete-continuous action spaces. For example, steering and signaling in autonomous driving, and aiming and firing in robotics or video-games. Despite real-world hybrid factorization and reinforcement learning framework support for complex action spaces (e.g., Gymnasium, PettingZoo, TorchRL, SeedRL, Mujoco, etc), the default environments within those frameworks often implement uniform action space configurations (LunarLander, Walker2D, Cheetah, SMAC, SUMO, Ant, Atari). Landmark hybrid-action benchmarks (RoboCup 2D HFO, SC2LE, Platform, CARLA, etc) are mostly heavyweight or archival implementations originating from papers which test one or a small number of competing factorization methods on one kind of control. This article provides a cross-sectional study of factorization methods [independent networks, shared encoder, VDN, QPLEX, Joint, Auto-Regressive] on each of three families of algorithms [PPO, SAC, DQN] across three action spaces [discretized, hybrid, continuous] over four lightweight environments [Platform, hybrid-LunarLander, Hybrid-Shoot, CoopPush]. Accounting for some invalid pairings such as joint-continuous, we are left with 220 configurations to analyze each method. We provide two new C++ parallel gymnasium and petting-zoo compliant environments [CoopPush, Hybrid-Shoot] to isolate particular challenges such as state-dependent inter-action dependence. Finally, we introduce VDN-PPO and PPO-MIX which use a branching critic to assign credit to multi-headed PPO. These variants out-perform all other tested PPO factorizations. Our results suggest that branching dueling architectures balance compute and performance most effectively, with Auto-Regressive actions reaching the highest performance overall and native continuous SAC outperforming discrete and hybrid algorithms, albiet both at increased computational cost.
### Title:
          LAMP: Lane-Aligned Motion Primitives for Feasible Trajectory Prediction
 - **Authors:** Sangjin Han, Hoseong Jung, Jeongtae Her, Changhyun Choi, H. Jin Kim
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Motion forecasting is essential for autonomous driving systems to enable safe decision-making and planning in complex driving scenarios. While existing predictors excel at minimizing standard displacement errors, they often overlook the adherence to lane topology of multimodal predictions, particularly for lower-probability modes. Consequently, predicted trajectories may violate physical and logical constraints, making the prediction set unreliable for safety-critical planning. In this paper, we propose LAMP (Lane-Aligned Motion Primitives), a topology-aware forecasting framework that anchors multimodal prediction to structured motion primitives aligned with lane topology. Specifically, we use a VQ-VAE to learn shape-aware motion primitives as discrete intention queries, capturing spatiotemporal patterns beyond endpoint-based intentions. We further introduce a feasibility-aware intention selector trained with a lane-topology prior for filtering unreachable intention queries, guiding the decoder to prioritize topology-consistent intentions while preserving behavioral diversity. Extensive experiments on the Argoverse 2 dataset demonstrate that LAMP achieves prediction accuracy comparable to state-of-the-art baselines while outperforming them in feasibility and diversity metrics.
