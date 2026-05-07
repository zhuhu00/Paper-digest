# Showing new listings for Thursday, 7 May 2026
## Keyword: SLAM
### Title:
          Hardware-Aware Neural Feature Extraction for Resource-Constrained Devices
 - **Authors:** Francesco Tosini, Simone Pedroni, Christian Veronesi, Pietro Bartoli, Marco Paracchini, Marco Marcon, Diana Trojaniello
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual SLAM is a core component of spatial computing systems, yet deploying learned local feature extractors on microcontroller-class hardware remains challenging due to memory, bandwidth, and quantization constraints. While modern neural descriptors provide strong robustness, their practical adoption is often hindered by system-level bottlenecks that are not captured by FLOP-based efficiency metrics. In this work, we introduce Gideon, a hardware-aware neural feature extractor explicitly designed for resource-constrained devices. Our approach combines relational knowledge distillation from a SuperPoint teacher with differentiable neural architecture search (DNAS) under strict memory and operator constraints. Unlike conventional design pipelines, we treat quantization stability and dynamic-range compactness as first-class objectives. We show that architectural choices such as replacing Batch Normalization with affine layers significantly improve INT8 robustness, and that descriptor dimensionality directly governs quantization resilience. Deployed on STM32N6, Gideon achieves 9.003 ms inference time (111 fps) while remaining below a 1.5 MB memory footprint. Remarkably, INT8 quantization induces negligible degradation and occasionally matches full-precision performance. These results demonstrate that robust learned feature extraction can be reconciled with embedded hardware constraints through holistic hardware-algorithm co-design.
### Title:
          Dr-PoGO: Direct Radar Pose-Graph Optimization
 - **Authors:** Cedric Le Gentil, Weican Li, Leonardo Brizi, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces Dr-PoGO, a method for Simultaneous Localization And Mapping (SLAM) using a 2D spinning radar. Unlike cameras or lidars that require line-of-sight, millimetre-wave radars can `see' through dust, falling snow, rain, etc. Accordingly, it is a great modality for robust perception regardless of the weather conditions. While most existing radar-based SLAM methods rely on the extraction of point clouds or features to perform ego-motion estimation, Dr-PoGO leverages direct registration techniques for odometry (DRO) and loop-closure registration. An off-the-shelf radar-focused place recognition algorithm, RaPlace, provides loop-closure candidates. As RaPlace does not provide relative transformations, Dr-PoGO introduces a coarse-to-fine registration that uses visual features and descriptors to obtain an initial guess for the direct transformation refinement. The global trajectory is optimized in a pose-graph optimization. Dr-PoGO demonstrates state-of-the-art performance over 300km of data in various real-world automotive environments. Our implementation is publicly available: this https URL.
### Title:
          A Closed-Form Dual-Barrier CBF Safety Filter for Holonomic Robots on Incrementally Built Occupancy Grid Maps
 - **Authors:** Himanshu Paudel, Basanta Joshi, Dhirendra Raj Madai, Alina Bartaula, Biman Rimal, Sanjay Neupane
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a dual-barrier control barrier function (CBF) safety filter for real-time, safety-critical velocity control of holonomic robots operating in incrementally built occupancy grid maps. As a robot explores an unknown environment, unmapped regions introduce irreducible uncertainty, since obstacle geometry beyond the explored frontier is unknown, making entry into such regions a source of collision risk, especially with front-facing sensors. To address this, we enforce two constraints: avoidance of mapped obstacles and restriction from unexplored regions. Both constraints are derived analytically from the occupancy grid's signed distance field, yielding a closed-form safety filter that requires only a small linear system solve per cycle. On resource-constrained platforms such as the Raspberry Pi, where SLAM and planning already consume significant compute, the low overhead of the proposed filter preserves resources. An adaptive gain schedule relaxes the frontier constraint in information-rich regions and tightens it in well-mapped areas, improving exploration efficiency while maintaining safety. The filter operates in velocity space as a minimally invasive correction and composes with arbitrary nominal controllers, including learning-based methods. Hardware flight experiments on a PX4-controlled quadrotor demonstrate zero collisions across multiple indoor runs.
## Keyword: odometry
### Title:
          Dr-PoGO: Direct Radar Pose-Graph Optimization
 - **Authors:** Cedric Le Gentil, Weican Li, Leonardo Brizi, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces Dr-PoGO, a method for Simultaneous Localization And Mapping (SLAM) using a 2D spinning radar. Unlike cameras or lidars that require line-of-sight, millimetre-wave radars can `see' through dust, falling snow, rain, etc. Accordingly, it is a great modality for robust perception regardless of the weather conditions. While most existing radar-based SLAM methods rely on the extraction of point clouds or features to perform ego-motion estimation, Dr-PoGO leverages direct registration techniques for odometry (DRO) and loop-closure registration. An off-the-shelf radar-focused place recognition algorithm, RaPlace, provides loop-closure candidates. As RaPlace does not provide relative transformations, Dr-PoGO introduces a coarse-to-fine registration that uses visual features and descriptors to obtain an initial guess for the direct transformation refinement. The global trajectory is optimized in a pose-graph optimization. Dr-PoGO demonstrates state-of-the-art performance over 300km of data in various real-world automotive environments. Our implementation is publicly available: this https URL.
### Title:
          CARD: A Multi-Modal Automotive Dataset for Dense 3D Reconstruction in Challenging Road Topography
 - **Authors:** Gasser Elazab, Frank Neuhaus, Tilman Koß, Malte Splietker, Aditya Date, Michael Unterreiner, Maximilian Jansen, Olaf Hellwich
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving must operate across diverse surfaces to enable safe mobility. However, most driving datasets are captured on well-paved flat roads. Moreover, recent driving datasets primarily provide sparse LiDAR ground truth for images, which is insufficient for assessing fine-grained geometry in depth estimation and completion. To address these gaps, we introduce CARD, a multi-modal driving dataset that delivers quasi-dense 3D ground truth across continuous sequences rich in speed bumps, potholes, irregular surfaces and off-road segments. Our sensor suite includes synchronized global-shutter stereo cameras, front and rear LiDARs, 6-DoF poses from LiDAR-inertial odometry, per-wheel motion traces, and full calibration. Notably, our multi-LiDAR fusion yields ~500K valid depth pixels per frame, about 6.5x more than KITTI Depth Completion and 10x more on average than other public driving datasets. The dataset spans ~110 km and 4.7 hours across Germany and Italy. In addition, CARD provides 2D bounding boxes targeting road-topography irregularities, enabling accurate benchmarking for both geometry and perception tasks. Furthermore, we establish a standardized evaluation protocol for road surface irregularities on CARD and benchmark state-of-the-art depth estimation models to provide strong baselines. The CARD dataset is hosted on this https URL.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          InterFuserDVS: Event-Enhanced Sensor Fusion for Safe RL-Based Decision Making
 - **Authors:** Mustafa Sakhaia, Kaung Sithua, Min Khant Soe Okea, Maciej Wielgosza
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving systems rely heavily on robust sensor fusion to perceive complex envi- ronments. Traditional setups using RGB cameras and LiDAR often struggle in high-dynamic- range scenes or high-speed scenarios due to motion blur and latency. Dynamic Vision Sensors (DVS), or event cameras, offer a paradigm shift by capturing asynchronous brightness changes with microsecond temporal resolution and high dynamic range. In this paper, we propose an extended architecture of the state-of-the-art InterFuser model, integrating DVS as an additional modality to enhance perception reliability. We introduce a novel token-based fusion strategy that incorporates accumulated event frames into the transformer-based backbone of InterFuser. Our method leverages the complementary nature of RGB, LiDAR, and DVS data. We evaluate our approach on the Car Learning to Act (CARLA) Leaderboard benchmarks, demonstrating that the inclusion of DVS improves the robustness of the driving agent, achieving a competitive Driving Score of 77.2 and a superior Route Completion of 100%. The results indicate that event-based vision is a promising direction for improving safety and performance in adverse lighting and dynamic conditions.
### Title:
          Dr-PoGO: Direct Radar Pose-Graph Optimization
 - **Authors:** Cedric Le Gentil, Weican Li, Leonardo Brizi, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces Dr-PoGO, a method for Simultaneous Localization And Mapping (SLAM) using a 2D spinning radar. Unlike cameras or lidars that require line-of-sight, millimetre-wave radars can `see' through dust, falling snow, rain, etc. Accordingly, it is a great modality for robust perception regardless of the weather conditions. While most existing radar-based SLAM methods rely on the extraction of point clouds or features to perform ego-motion estimation, Dr-PoGO leverages direct registration techniques for odometry (DRO) and loop-closure registration. An off-the-shelf radar-focused place recognition algorithm, RaPlace, provides loop-closure candidates. As RaPlace does not provide relative transformations, Dr-PoGO introduces a coarse-to-fine registration that uses visual features and descriptors to obtain an initial guess for the direct transformation refinement. The global trajectory is optimized in a pose-graph optimization. Dr-PoGO demonstrates state-of-the-art performance over 300km of data in various real-world automotive environments. Our implementation is publicly available: this https URL.
### Title:
          CARD: A Multi-Modal Automotive Dataset for Dense 3D Reconstruction in Challenging Road Topography
 - **Authors:** Gasser Elazab, Frank Neuhaus, Tilman Koß, Malte Splietker, Aditya Date, Michael Unterreiner, Maximilian Jansen, Olaf Hellwich
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving must operate across diverse surfaces to enable safe mobility. However, most driving datasets are captured on well-paved flat roads. Moreover, recent driving datasets primarily provide sparse LiDAR ground truth for images, which is insufficient for assessing fine-grained geometry in depth estimation and completion. To address these gaps, we introduce CARD, a multi-modal driving dataset that delivers quasi-dense 3D ground truth across continuous sequences rich in speed bumps, potholes, irregular surfaces and off-road segments. Our sensor suite includes synchronized global-shutter stereo cameras, front and rear LiDARs, 6-DoF poses from LiDAR-inertial odometry, per-wheel motion traces, and full calibration. Notably, our multi-LiDAR fusion yields ~500K valid depth pixels per frame, about 6.5x more than KITTI Depth Completion and 10x more on average than other public driving datasets. The dataset spans ~110 km and 4.7 hours across Germany and Italy. In addition, CARD provides 2D bounding boxes targeting road-topography irregularities, enabling accurate benchmarking for both geometry and perception tasks. Furthermore, we establish a standardized evaluation protocol for road surface irregularities on CARD and benchmark state-of-the-art depth estimation models to provide strong baselines. The CARD dataset is hosted on this https URL.
### Title:
          Height-Guided Projection Reparameterization for Camera-LiDAR Occupancy
 - **Authors:** Yuan Wu, Zhiqiang Yan, Jiawei Lian, Zhengxue Wang, Jian Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D occupancy prediction aims to infer dense, voxel-wise scene semantics from sensor observations, where the 2D-to-3D view transformation serves as a crucial step in bridging image features and volumetric representations. Most previous methods rely on a fixed projection space, where 3D reference points are uniformly sampled along pillars. However, such sampling struggles to capture the sparsity and height variations of real-world scenes, leading to ambiguous correspondences and unreliable feature aggregation. To address these challenges, we propose HiPR, a camera-LiDAR occupancy framework with Height-Guided Projection Reparameterization. HiPR first encodes LiDAR into a BEV height map to capture the maximum height of the point cloud. HiPR then adjusts the sampling range of each pillar using the height prior, enabling adaptive reparameterization of the projection space. As a result, the projected points are redistributed into geometrically meaningful regions rather than fixed ranges. Meanwhile, we mask out the invalid parts of the height map to avoid misleading the feature aggregation. In addition, to alleviate the training instability caused by noisy LiDAR-derived heights, we introduce a training-time Progressive Height Conditioning strategy, which gradually transitions the conditioning signal from ground-truth heights to LiDAR heights. Extensive experiments demonstrate that HiPR consistently outperforms existing state-of-the-art methods while maintaining real-time inference. The code and pretrained models can be found at this https URL.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Transformation Categorization Based on Group Decomposition Theory Using Parameter Division
 - **Authors:** Takayuki Komatsu, Yoshiyuki Ohmura, Yasuo Kuniyoshi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Representation learning seeks meaningful sensory representations without supervision and can model aspects of human development. Although many neural networks empirically learn useful features, a principled account of what makes a representation "good" remains elusive. We study unsupervised categorization of transformations between pairs of inputs under algebraic constraints. Classical disentanglement favors mutually independent factors and fails when factors are coupled. Our prior Galois-theoretic approach decomposes a group via normal subgroups by learning a product of two transformations with one factor constrained to a normal subgroup, covering both commutative and non-commutative cases. That method, however, relied on auxiliary assumptions (e.g., motion and isometry restrictions) not required by decomposition theory, and ablations did not separate theory-based from auxiliary effects. We propose parameter division for a single transformation: we split its parameter into components, impose homomorphism constraints mapping the full transformation to one component, and identify the normal subgroup as the set of transformations when that component is fixed to the identity. This formulation drops the previous auxiliary assumptions and applies more broadly. We evaluate on image pairs involving rotation, translation, and scale; ablations show that group-decomposition constraints drive appropriate categorization.
### Title:
          Lookahead Drifting Model
 - **Authors:** Guoqiang Zhang, Kenta Niwa, W. Bastiaan Kleijn
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recently, a new paradigm named \emph{drifting model} has been proposed for mapping distributions, which achieves the SOTA image generation performance over ImageNet via one-step neural functional evaluation (NFE). The basic idea is to compute a drifting term at each training iteration and then push the output of the model towards the direction of the drifting term. In this paper, we propose a \emph{lookahead drifting model}. At each training iteration, we compute a set of drifting terms sequentially. Each drifting term is calculated by making use of previously computed ones as well as the positive samples and the output of the model. %One key step is to properly scale the drifting terms so that their magnitudes are in a comparable range. In principle, the drifting terms obtained at a later stage capture higher order gradient information towards the positive samples. At each training iteration, the model is optimized by pushing its output towards the direction of the (weighted) summation of the drifting terms. Experimental results on toy examples and CIFAR10 demonstrate the better performance of the new method than the baseline.
### Title:
          Constrained Extreme Gradient Boosting for Adapting Reduced-Order Models
 - **Authors:** Melika Baghi, Xiao Liu, Kamran Paynabar
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-fidelity simulations, such as computational fluid dynamics and finite element analysis, are essential for modeling complex engineering systems but are often prohibitively expensive for tasks including parametric studies, optimization, and real-time control. Projection-based reduced-order models (ROMs) alleviate this cost by projecting the governing dynamics onto low-dimensional subspaces. However, their performance can deteriorate under parameter variation, motivating the need for adaptive basis construction. In this work, we propose a constrained ensemble learning framework, termed Constrained Extreme Gradient Boosting (cXGBoost), for predicting Proper Orthogonal Decomposition (POD) bases as functions of system parameters. The approach leverages a geometric representation of subspaces on the Grassmann manifold, which are mapped to a Euclidean space to enable efficient regression using gradient boosting trees. A norm constraint is imposed during training to ensure the validity of the inverse mapping and preserve the geometric structure of the predicted subspaces. The proposed method is evaluated on four numerical examples, including fluid dynamics and wave propagation problems, demonstrating its ability to accurately predict parameter-dependent bases while maintaining robustness across nonlinear regimes. These results highlight the potential of combining geometric learning with constrained ensemble methods for scalable and reliable reduced-order modeling of high-dimensional parametric systems.
### Title:
          Two Integration Pathways in Human-Centered Requirements Engineering: A Systematic Mapping Study of Structural Gaps
 - **Authors:** Imen Benzarti, Ikram Darif, Abderrahmane Leshob, Hafedh Mili, Darine Amayed
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human-centered Requirements Engineering (HC-RE) integrates user cognition, emotions, and social interactions into the RE process through contributions from disciplines such as psychology, cognitive science, design thinking, and human-computer interaction. Despite growing interest, how these multidisciplinary contributions are structured and why they remain fragmented across the RE lifecycle is not well understood. This systematic mapping study analyzes 56 primary studies across seven dimensions, including RE phases, user involvement techniques, contributing disciplines, and evaluation methods. Results show that 70\% of approaches involve multidisciplinary contributions, yet only 39% have been empirically evaluated and 48% address only the elicitation phase. A cross-study analysis reveals a structural separation between two parallel integration traditions: a Cognitive-Formal (C-F) pathway grounded in goal-based frameworks and formal modeling, and a Participatory-Iterative (P-I) pathway grounded in scenario-based frameworks and iterative design. Each pathway has developed complementary strengths, but their near-total disconnection explains the persistent lifecycle concentration and theory-practice gap observed in the corpus. The findings identify the absence of translation mechanisms between human-centered artifacts and formal RE specifications as the field's primary structural gap, provide a structured research agenda organized into four priority tiers, and establish the empirical foundation for Experience-Centered Requirements Engineering, a direction in which user experience is explicitly operationalized as a first-class concern in requirements specification.
### Title:
          Towards a Zero-Trust Supply-Chain Assurance Rubric for ORAN RIC Applications
 - **Authors:** Chun Yin Chiu
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open RAN enables third-party xApps and rApps to be onboarded and updated at operational cadence, creating a software supply chain that spans developers, CI systems, registries, onboarding pipelines, and runtime enforcement points. This preprint proposes a zero-trust supply-chain assurance rubric for O-RAN RIC applications. It makes three contributions: first, an app-centric lifecycle threat model for RIC applications across build, signing, publication, onboarding, runtime, and update or rollback stages; second, a WG11-aligned threat-control-evidence mapping that relates lifecycle threats to O-RAN security baselines and complementary supply-chain evidence; and third, an operator-facing assurance profile that combines secure software development practices, SBOM transparency, and SLSA-style provenance into incremental onboarding levels. Analytical case-study walkthroughs and a minimal evidence-checking workflow illustrate how the rubric can support explicit Accept, Escalate, or Block decisions during RIC app onboarding. The evaluation is intended to assess applicability rather than deployment-scale performance; empirical measurements of operational overhead, decision consistency, and detection coverage are left for future work.
### Title:
          Memory as a Markov Matrix: Sample Efficient Knowledge Expansion via Token-to-Dictionary Mapping
 - **Authors:** Kaustubh Pethkar, Ziyang Xiong, Zuofeng Shang, Yingcong Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Continual incorporation of new knowledge is essential for the long-term evolution of large language models (LLMs). Existing approaches typically rely on parameter-update algorithms to mitigate catastrophic forgetting, yet they suffer from fundamental limitations: 1) forgetting is unavoidable as the amount of newly injected knowledge grows; and 2) model updates are often irreversible. As modern LLMs become increasingly expressive, it is natural to question whether large-scale weight updates are necessary for acquiring a small amount of new knowledge. In this work, we propose a principled framework that models autoregressive language generation as a Markov process over tokens, where model memory is represented by a Markov transition matrix. Under this formulation, incorporating new knowledge/tokens corresponds to extending the state space, and preserving existing transitions guarantees retention of previously learned knowledge. We then prove a sample complexity bound for incorporating new tokens via a token-to-dictionary mapping strategy. In particular, for learning the transition behavior of each new token, the required number of samples scales linearly with the number of existing tokens it is mapped to. To realize this mapping, we propose an embedding-tuning algorithm that requires minimal parameter updates and induces zero forgetting. Experimental results further demonstrate the effectiveness of our method and validate our theoretical findings.
### Title:
          From Language to Logic: A Theoretical Architecture for VLM-Grounded Safe Navigation
 - **Authors:** Kristy Sakano, Kalonji Harrington, Mumu Xu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose an architecture for integrating high-level, human-provided safety rules and operator-aligned semantic preferences into autonomous robot navigation in unstructured outdoor environments. In our approach, natural-language rules are translated into Signal Temporal Logic (STL) specifications that guide planning and navigation during runtime. Persistent, environment-centric rules and terrain preferences are grounded into a 2D cost map, while temporally dynamic requirements are expressed as STL specifications to be monitored during runtime. We hypothesize the use of Vision-Language Models (VLMs) for zero-shot scene understanding, enabling mapping between human instructions, semantic features, and environmental constraints. Within this framework, we construct an illustrative navigation model that is designed to satisfy a set of STL-encoded specifications and soft operator preferences through formal satisfaction metrics embedded into environmental properties and runtime monitoring.
### Title:
          Autonomous Laparoscope Control through Unified Mechanics-Based Representation of Multimodal Intraoperative Information
 - **Authors:** Xiaojian Li, Jin Fang, Yudong Shi, Xilin Xiao, Kai Yan, Kang Min, Ling Li, Hua Tang, Hangjie Mo
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Laparoscope-holding robots can provide surgeons with a stable laparoscopic field of view (FOV) and reduce the burden on human assistants. To maintain an ideal intraoperative FOV, the robot must continuously adjust the laparoscope pose according to intraoperative information. However, intraoperative multimodal signals, such as position, force/torque, and images, differ markedly in physical meaning and units, making it difficult to build a unified representation and to generate control commands that can be used directly for laparoscope control. To address this issue, we propose a laparoscope-holding robot control method based on unified mechanics modeling of multimodal information. First, we design mapping strategies for multiple intraoperative sources, including position, force/torque, and images, and unify them into an equivalent-wrench representation in the operational space. Then, using a task-priority scheme, we inject the wrenches into the task space and the null space, respectively, and synthesize laparoscope control commands via task-priority projection, thereby achieving consistent representation and coordinated fusion of multimodal information within a single framework. Finally, taking the intraoperative remote center of motion (RCM) position, force/torque sensor readings, and laparoscopic images as examples, we construct an RCM-constraint wrench to enforce the RCM geometric constraint and reduce the contact force at the trocar site, a laparoscope-manipulation wrench to enable compliant dragging, and an instrument-tracking wrench to achieve autonomous visual tracking of the instruments. Experiments on a surgical phantom and in vivo porcine trials demonstrate that the proposed method supports multi-task operation, including compliant laparoscope manipulation and autonomous instrument tracking, while maintaining the RCM constraint and reducing sustained trocar-site loading.
### Title:
          CoherentRaster: Efficient 3D Gaussian Splatting for Light Field Displays
 - **Authors:** Gyujin Sim, Seungjoo Shin, Hosung Jeon, Gwangsoon Lee, Hyon-Gon Choo, Sunghyun Cho
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Light field displays (LFDs) require rendering an interlaced image that encodes many view-dependent observations. This multi-view requirement introduces substantial computational overhead, making real-time rendering difficult to achieve. While 3D Gaussian Splatting (3DGS) is efficient for single-view rendering on 2D displays, directly extending it to LFDs is computationally expensive. Moreover, prior accelerations either suffer from GPU inefficiency under spatially incoherent subpixel layouts or rely on computationally heavy multi-plane intermediates. In this paper, we propose CoherentRaster, a 3DGS-based light field rendering framework that performs subpixel-level rasterization. Our method employs Cross-view Coherent Attribute Reuse to eliminate redundant computation across neighboring viewpoints and applies View-coherent Remapping to restore warp-level memory efficiency degraded by the interlaced subpixel layout. Together, CoherentRaster provides an efficient pipeline for real-time, high-quality light field synthesis on consumer-grade hardware.
### Title:
          FL-Sailer: Efficient and Privacy-Preserving Federated Learning for Scalable Single-Cell Epigenetic Data Analysis via Adaptive Sampling
 - **Authors:** Guangyi Zhang, Yi Dai, Yiyun He, Junhao Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Single-cell ATAC-seq (scATAC-seq) enables high-resolution mapping of chromatin accessibility, yet privacy regulations and data size constraints hinder multi-institutional sharing. Federated learning (FL) offers a privacy-preserving alternative, but faces three fundamental barriers in scATAC-seq analysis: ultra-high dimensionality, extreme sparsity, and severe cross-institutional heterogeneity. We propose FL-Sailer, the first FL framework designed for scATAC-seq data. FL-Sailer integrates two key innovations: (i) adaptive leverage score sampling, which selects biologically interpretable features while reducing dimensionality by 80%, and (ii) an invariant VAE architecture, which disentangles biological signals from technical confounders via mutual information minimization. We provide a convergence guarantee, showing that FL-Sailer converges to an approximate solution of the original high-dimensional problem with bounded error. Extensive experiments on synthetic and real epigenomic datasets demonstrate that FL-Sailer not only enables previously infeasible multi-institutional collaborations but also surpasses centralized methods by leveraging adaptive sampling as an implicit regularizer to suppress technical noise. Our work establishes that federated learning, when tailored to domain-specific challenges, can become a superior paradigm for collaborative epigenomic research.
### Title:
          PINSIGHT: A Comprehensive Threat Exploration of Domain-Adaptive Wi-Fi based PIN Code Inference
 - **Authors:** Johannes Kortz, Paul Staat, Christof Paar, Christian Zenger
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wi-Fi signals can be exploited by adversaries as a sensing side channel to eavesdrop on physical information. By monitoring propagation effects of radio waves within the victim's environment, attackers can remotely infer sensitive information. One particularly concerning example is PIN code inference, where the attacker faces the challenge of mapping Wi-Fi physical-layer channel estimations back into typed digits. While effective in their training environment, such attacks typically fail as soon as they are deployed in unseen environments. The current state-of-the-art attack, WiKI-Eve, attempts to overcome this problem using a deep-learning approach, reporting high PIN code inference accuracy independent of environments, devices, and users. While this suggests a significant real-world threat, it is not well understood how far the attack actually reaches, nor what its underlying generalization performance is based on. In this work, we close this gap by presenting PINSIGHT, a novel methodology that separates the effects of environmental variation and PIN code typing. This enables the first rigorous threat assessment of such attacks, evaluating their generalization capabilities and limitations. Our approach leverages a robotic typing platform that produces highly repeatable keystroke events across systematically varied environment changes [...]. This dataset constitutes the first benchmark for environment generalization in Wi-Fi PIN code inference attacks. Evaluating several state-of-the-art methods, we find that attacks generalize reliably across changes in the surrounding environment but degrade substantially when the channel's encoding of typing itself shifts - precisely the condition that defines a realistic attack scenario. We conclude that the reported performance of current state-of-the-art Wi-Fi PIN inference attacks is not representative of the actual real-world threat.
### Title:
          From Diffusion to Rectified Flow: Rethinking Text-Based Segmentation
 - **Authors:** Zishen Qu, Xuesong Li, Haijian Gu, Hongwei Kang, Quan Meng, Tianrui Niu, Xin Yang, Ruidong Pan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-based image segmentation aims to delineate object boundaries within an image from text prompts, offering higher flexibility and broader application scope compared to traditional fixed-category segmentation tasks. Recent studies have shown that diffusion models (e.g., Stable Diffusion) can provide rich multimodal semantic features, leading to studies of using diffusion models as feature extractors for segmentation tasks. Such methods, however, inherit the generative natures of diffusion models that are harmful to discriminative segmentation tasks. In response, we propose RLFSeg, a novel framework that leverages Rectified Flow to learn direct mapping from the image to the segmentation mask within the latent space. The model is thus freed from the noise-denoise process and the need to optimize the time step of diffusion models, resulting in substantially better performance than previous diffusion-based methods, especially on zero-shot scenarios. By introducing label refinement and an Adaptive One-Step Sampling strategy, the model achieves higher accuracy even on a single inference step. The framework redirects a pretrained generative model to the discriminative segmentation task with zero modification to model structure, thus reveals promising application potential and significant research value.
### Title:
          Active Contact Sensing for Robust Robot-to-Human Object Handover
 - **Authors:** Linfeng Li, Lin Shao, David Hsu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robot-to-human object handover is an essential skill for robot assistants, from serving drinks at home to passing surgical tools in the operating room. We expect robots to perform handover robustly -- to release the object only after a firm human grasp while ignoring incidental touches. Existing passive-sensing methods struggle to generalize across diverse objects and human behaviors, as they lack informative perturbations to disambiguate different contact conditions, such as firm grasp versus incidental touch. We propose an active sensing approach for robust handovers: the robot applies information-gathering motions and senses the resulting human-applied forces to infer the contact state. A firm grasp produces forces in multiple directions, while an accidental touch does not. To capture this distinction, we model the contact state with a Bayesian linear model: a distribution over piecewise-linear mappings from robot motions to human-applied forces. This model enables firm grasp detection and active information gathering. In experiments with 12 participants and 30 diverse rigid objects, our method achieved a 97.5% success rate -- over 30% higher than two common baselines.
### Title:
          Multi-Level Bidirectional Biomimetic Learning for EEG-Based Visual Decoding
 - **Authors:** Jingtao Liu, Peiliang Gong, Chuhang Zheng, Yiheng Liu, Qi Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 EEG-based visual neural decoding aims to align neural responses with visual stimuli for tasks such as image retrieval. However, limited paired data and a fundamental mismatch between high-fidelity digital images and biological visual perception - distorted by retinotopic mapping and subject-specific neuroanatomy - severely impede cross-modal alignment. To address this, we propose MB2L, a Multi-Level Bidirectional Biomimetic Learning framework that incorporates structured physiological inductive biases into representation learning. Specifically, we propose Adaptive Blur with Visual Priors to mitigate perceptual-structural mismatch by reweighting visual inputs according to retinotopic priors. We further propose Biomimetic Visual Feature Extraction to learn multi-level visual representations consistent with hierarchical cortical processing, enhancing subject-invariant encoding. These modules are jointly optimized via Multi-level Bidirectional Contrastive Learning, which aligns EEG and visual features in a shared semantic space through bidirectional contrastive objectives. Experiments show MB2L achieves 80.5% Top-1 and 97.6% Top-5 accuracy on zero-shot EEG-to-image retrieval, significantly outperforming prior methods and demonstrating strong generalization across subjects and experimental settings.
### Title:
          FaithfulFaces: Pose-Faithful Facial Identity Preservation for Text-to-Video Generation
 - **Authors:** Yuanzhi Wang, Xuhua Ren, Jiaxiang Cheng, Bing Ma, Kai Yu, Sen Liang, Wenyue Li, Tianxiang Zheng, Qinglin Lu, Zhen Cui
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Identity-preserving text-to-video generation (IPT2V) empowers users to produce diverse and imaginative videos with consistent human facial identity. Despite recent progress, existing methods often suffer from significant identity distortion under large facial pose variations or facial occlusions. In this paper, we propose \textit{FaithfulFaces}, a pose-faithful facial identity preservation learning framework to improve IPT2V in complex dynamic scenes. The key of FaithfulFaces is a pose-shared identity aligner that refines and aligns facial poses across distinct views via a pose-shared dictionary and a pose variation-identity invariance constraint. By mapping single-view inputs into a global facial pose representation with explicit Euler angle embeddings, FaithfulFaces provides a pose-faithful facial prior that guides generative foundations toward robust identity-preserving generation. In particular, we develop a specialized pipeline to curate a high-quality video dataset featuring substantial facial pose diversity. Extensive experiments demonstrate that FaithfulFaces achieves state-of-the-art performance, maintaining superior identity consistency and structural clarity even as pose changes and occlusions occur.
### Title:
          Morphology-Guided Cross-Task Coupling for Joint Building Height and Footprint Estimation
 - **Authors:** Jinzhen Han, JinByeong Lee, Jisung Kim, HongSik Yun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Building height (BH) and building footprint (BF) jointly describe the vertical and horizontal extent of the built environment and are required inputs for urban climate, disaster-risk, and population-mapping models. The two parameters are coupled through floor-area-ratio (FAR) constraints, yet remote-sensing approaches typically treat them as independent regression targets. We argue that explicitly encoding this cross-task coupling is more impactful than further refining individual encoders, and propose MorphoFormer, a joint BH/BF estimation framework built around two complementary mechanisms: (i) a BF-Guided Task Decoder (BGTD) that gates the height branch via cross-attention on a footprint-derived morphology context, and (ii) a Morphology Consistency Loss (MCL) that supervises a height-from-footprint surrogate against the ground-truth BH, indirectly forcing the BF feature to encode height-correlated structure. The encoder is a single-stage Swin backbone fed by Sentinel-1 SAR, Sentinel-2 multispectral, and DEM inputs, trained and evaluated on a geo-blocked split of 54 cities. Against a Swin-MTL baseline at identical receptive field, MorphoFormer reduces BH test RMSE from 3.39 to 3.15 m (R^2 improves 0.62 -> 0.67) with BF R^2 stable at 0.80. Controlled ablations at identical capacity attribute most of this 0.24 m improvement to the two proposed mechanisms: removing BGTD raises BH RMSE by 0.11 m and removing MCL raises it by 0.11 m, with the residual approximately 0.02 m falling within the noise floor of encoder-side variations. Because both mechanisms act on cross-task representations rather than pixels, the design carries no intrinsic dependence on input resolution.
### Title:
          Gaze4HRI: Zero-shot Benchmarking Gaze Estimation Neural-Networks for Human-Robot Interaction
 - **Authors:** Berk Sezer, Ali Görkem Küçük, Erol Şahin, Sinan Kalkan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While zero-shot appearance-based 3D gaze estimation offers significant cost-efficiency by directly mapping RGB images to gaze vectors, its reliability in Human-Robot Interaction (HRI) settings remains uncertain. Existing benchmarks frequently overlook fundamental HRI conditions, such as dynamic camera viewpoints and moving targets in video. Furthermore, current cross-dataset evaluations often suffer from a complexity gap, where methods trained on diverse datasets are tested on significantly smaller and less varied sets, failing to assess true robustness. To bridge these gaps, we introduce Gaze4HRI, a large-scale dataset (50+ subjects, 3,000+ videos, 600,000+ frames) designed to evaluate state-of-the-art performance against critical HRI variables: illumination, head-gaze conflict, as well as the motion of camera and gaze target in video. Our benchmark reveals that all evaluated methods fail in at least one condition, identifying steeply-downward gaze as a universal failure point. Notably, PureGaze trained on the ETH-X-Gaze dataset uniquely maintains resilience across all other conditions. These results challenge the recent focus in the literature on complex spatial-temporal modeling and Transformer-based architectures. Instead, our findings suggest that extensive data diversity, as exemplified by the ETH-X-Gaze dataset, serves as the primary driver of zero-shot robustness in unconstrained environments, while resilience-enhancing frameworks, such as PureGaze's self-adversarial loss for gaze feature purification, provide a substantial further improvement. Ultimately, this study establishes a rigorous benchmark that provides practical guidelines for practitioners as well as reshaping future research. The dataset and codes are available at this https URL.
### Title:
          MIRAGE: Retrieval and Generation of Multimodal Images and Texts for Medical Education
 - **Authors:** Miguel Diaz Benito, Cecilia Diana Albelda, Alvaro Garcia Martin, Jesus Bescos Cano, Marcos Escudero-Vinolo, Juan C. SanMiguel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Access to diverse, well-annotated medical images with interactive learning tools is fundamental for training practitioners in medicine and related fields to improve their diagnostic skills and understanding of anatomical structures. While medical atlases are valuable, they are often impractical due to their size and lack of interactivity, whereas online image search may provide mislabeled or incomplete material. To address this, we propose MIRAGE, a multimodal medical text and image retrieval and generation system that allows users to find and generate clinically relevant images from trustworthy sources by mapping both text and images to a shared latent space, enabling semantically meaningful queries. The system is based on a fine-tuned medical version of CLIP (MedICaT-ROCO), trained with the ROCO dataset, obtained from PubMed Central. MIRAGE allows users to give prompts to retrieve images, generate synthetic ones through a medical diffusion model (Prompt2MedImage) and receive enriched descriptions from a large language model (Dolly-v2-3b). It also supports a dual search option, enabling the visual comparison of different medical conditions. A key advantage of the system is that it relies entirely on publicly available pretrained models, ensuring reproducibility and accessibility. Our goal is to provide a free, transparent and easy-to-use didactic tool for medical students, especially those without programming skills. The system features an interface that enables interactive and personalized visual learning through medical image retrieval and generation. The system is accessible to medical students worldwide without requiring local computational resources or technical expertise, and is currently deployed on Kaggle: this http URL
### Title:
          AGIPC: Adaptive In-Solve Algebraic Coarsening for GPU IPC
 - **Authors:** Xuan Wang, Zhaofeng Luo, Minchen Li, Taku Komura, Kemeng Huang
 - **Subjects:** Subjects:
Graphics (cs.GR); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Implicit time integration is key to robustly simulating stiff materials and large deformations, but its performance is often dominated by repeatedly solving large linear systems. Adaptive coarsening can reduce this cost by concentrating degrees of freedom (DoF) to where it is most needed, yet conventional explicit remeshing changes connectivity (and often vertex ordering), complicating parallel implementations, harming memory locality, and sometimes being disallowed when it may introduce local geometry intersections. Adaptive subspace approaches avoid topological changes, but basis construction and updates incur irregular data access patterns and typically produce dense system matrices, limiting GPU efficiency and keeping many practical systems CPU-centric. We present algebraic adaptive in-solve coarsening, a GPU-oriented method that dynamically reduces DoF within the Newton solve of implicit time integration without explicit topological modification. Starting from a fine mesh, we express adaptivity as a selective edge-collapse process governed by per-edge tags. Collapsible edges are aggregated in parallel using a warp-level hash mapping scheme that groups fine vertices into coarse super-nodes, while protected edges preserve local detail. This defines an implicit coarse mesh whose linear system is assembled algebraically by mapping and reducing fine-scale gradients and Hessians via efficient GPU reduction kernels. We solve the resulting coarse system with a preconditioned conjugate gradient (PCG) method and then prolongate the solution back to the fine mesh. Our approach integrates seamlessly with IPC's barrier energy and exploits GPU parallelism end-to-end. Across a range of challenging scenarios, we achieve up to 3x speedup over a state-of-the-art GPU IPC solver while producing visually indistinguishable results.
### Title:
          Dr-PoGO: Direct Radar Pose-Graph Optimization
 - **Authors:** Cedric Le Gentil, Weican Li, Leonardo Brizi, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces Dr-PoGO, a method for Simultaneous Localization And Mapping (SLAM) using a 2D spinning radar. Unlike cameras or lidars that require line-of-sight, millimetre-wave radars can `see' through dust, falling snow, rain, etc. Accordingly, it is a great modality for robust perception regardless of the weather conditions. While most existing radar-based SLAM methods rely on the extraction of point clouds or features to perform ego-motion estimation, Dr-PoGO leverages direct registration techniques for odometry (DRO) and loop-closure registration. An off-the-shelf radar-focused place recognition algorithm, RaPlace, provides loop-closure candidates. As RaPlace does not provide relative transformations, Dr-PoGO introduces a coarse-to-fine registration that uses visual features and descriptors to obtain an initial guess for the direct transformation refinement. The global trajectory is optimized in a pose-graph optimization. Dr-PoGO demonstrates state-of-the-art performance over 300km of data in various real-world automotive environments. Our implementation is publicly available: this https URL.
### Title:
          Sentiment Analysis and Customer Satisfaction Prediction on E-Commerce Platforms Based on YouTube Comments Using the XGBoost Algorithm
 - **Authors:** Ridho Benedictus Togi Manik, Muhammad Aqil Ramadhan, Ihsan Maulana Yusuf, Luluk Muthoharoh, Ardika Satria, Martin Clinton Tosima Manullang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The exponential expansion of digital commerce in Indonesia has significantly shifted consumer interactions toward video-centric social networks, particularly YouTube. Consequently, the sheer volume of unstructured, multi-contextual comments poses a tremendous challenge for manual sentiment tracking. This study investigates and constructs a predictive model for customer satisfaction leveraging the Extreme Gradient Boosting (XGBoost) architecture coupled with Term Frequency-Inverse Document Frequency (TF-IDF) vectorization. By utilizing a secondary dataset of YouTube comments retrieved from e-commerce review videos, the raw text underwent rigorous preprocessing to generate normalized numerical features. The experimental results demonstrate that the PyCaret-optimized machine learning framework delivers superior classification resilience. Beyond standard performance metrics, lexical evaluations and feature-importance mapping uncover a notable phenomenon: e-commerce discourse is heavily infiltrated by socio-political terminologies, which ultimately influence the polarity of audience satisfaction.
### Title:
          EP-GRPO: Entropy-Progress Aligned Group Relative Policy Optimization with Implicit Process Guidance
 - **Authors:** Song Yu, Li Li, Wenwen Zhao, Zhisheng Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning with verifiable rewards (RLVR), particularly Group Relative Policy Optimization (GRPO), has advanced LLM reasoning. However, GRPO suffers from three credit assignment failures: uniform token-level granularity that ignores heterogeneous informational value, uniform polarity that penalizes correct steps and rewards incorrect ones, and zero-variance collapse that erases outcome-driven gradients. We systematically quantify these failures, revealing highly non-uniform token informativeness, widespread step-level polarity misalignment, and substantial training waste. To address these limitations, we propose Entropy-Progress Aligned GRPO (EP-GRPO), a framework that mines the model's intrinsic information flow for dense, self-supervised guidance. EP-GRPO integrates entropy-gated modulation to prioritize high entropy decision pivots, implicit process signals from policy divergence anchored to outcome advantages for directional token-level feedback without external reward models, and cumulative entropy mapping that enables progress-aligned advantage normalization, naturally maintaining gradient flow under zero reward variance. Extensive experiments on mathematical reasoning benchmarks demonstrate that EP-GRPO achieves superior accuracy and efficiency compared to GRPO and its variants. The code will be available.
### Title:
          Low-Rank Adaptation of Geospatial Foundation Models for Wildfire Mapping Using Sentinel-2 Data
 - **Authors:** Ali Shibli, Andrea Nascetti, Yifang Ban
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wildfire burned-area mapping is essential for damage assessment, emissions modeling, and understanding fire-climate interactions across diverse ecological regions. Recent geospatial foundation models provide strong general-purpose representations for satellite imagery, yet there is still no clear understanding of how to efficiently adapt these models for downstream Earth observation tasks, particularly under geographic and temporal domain shift. This study evaluates three state-of-the-art Geospatial Foundation Models (GFMs) - Terramind, DINOv3, and Prithvi-v2 - for burned-area mapping across the United States and Canada using Sentinel-2 data. Leveraging 3,820 wildfire events from 2017-2023, we conduct spatial and temporal generalization tests across diverse biomes. We systematically compare full fine-tuning, decoder-only fine-tuning, and Low-Rank Adaptation (LoRA) for adapting each model. Across all experiments, LoRA provides the strongest cross-domain generalization while updating less than 1% of parameters, demonstrating a favorable trade-off between accuracy and efficiency. Prithvi-v2 with LoRA achieves the highest overall accuracy and the largest improvement compared to full fine-tuning. These findings indicate that geospatial foundation models, when adapted using lightweight parameter-efficient methods such as LoRA, offer a robust and scalable solution for large-scale burned-area mapping. Code is available at this https URL.
### Title:
          You Snooze, You Lose: Automatic Safety Alignment Restoration through Neural Weight Translation
 - **Authors:** Marco Arazzi, Vignesh Kumar Kembu, Antonino Nocera, Stjepan Picek, Saraga Sakthidharan
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The open-source ecosystem has accelerated the democratization of Large Language Models (LLMs) through the public distribution of specialized Low-Rank Adaptation (LoRA) modules. However, integrating these third-party adapters often induces catastrophic forgetting of the base model's foundational safety alignment. Restoring these guardrails via fine-tuning on safety data introduces an opposing failure mode: the severe degradation of the specialized domain knowledge the adapter was originally designed to provide. To overcome this zero-resource challenge, we propose Neural Weight Translation (NeWTral), a framework that directly maps unsafe, domain-specific adapters onto a safe alignment manifold while rigorously preserving their core expertise. NeWTral operates as a non-linear translation module pre-trained on a diverse corpus of unsafe-to-safe adapter pairs. By executing this mapping entirely within the parameter space, NeWTral utilizes an adaptive Mixture of Experts (MoE) routing strategy to autonomously blend high-fidelity surgical translators and aggressive alignment experts. We evaluate our framework across four architectural families (Llama, Mistral, Qwen, and Gemma) at scales up to 72B parameters across eight diverse scientific and professional domains. Our results demonstrate that the MoE variant achieves a radical reduction in the average Attack Success Rate (ASR), dropping from 70% in unsafe experts to just 13%, while maintaining an exceptional 90\% average knowledge fidelity. Much like the crowdsourced adapters it remedies, the NeWTral module is designed as a standalone, downloadable asset that allows practitioners to restore safety alignment instantly without requiring access to original training data or hardware-intensive retraining.
### Title:
          ConsisVLA-4D: Advancing Spatiotemporal Consistency in Efficient 3D-Perception and 4D-Reasoning for Robotic Manipulation
 - **Authors:** Wei Li, Jizhihui Liu, Li Yixing, Junwen Tong, Rui Shao, Liqiang Nie
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current Vision-Language-Action (VLA) models primarily focus on mapping 2D observations to actions, but exhibit notable limitations in spatiotemporal perception and reasoning: 1) spatial representations often rely on additional sensors, introducing substantial computational overhead; 2) visual reasoning is typically limited to future-frame prediction, lacking alignment with the instruction-grounded scene and thus compromising spatiotemporal consistency. To address these challenges, we propose ConsisVLA-4D, a unified and efficient framework that enhances spatiotemporal consistency in 3D perception and 4D reasoning. Specifically, we design: 1) CV-Aligner, which ensures cross-view object semantic consistency by filtering instruction-relevant regions and aligning object identities across multiple viewpoints; 2) CO-Fuser, which guarantees cross-object spatial geometric consistency by eliminating spatial relation ambiguities between objects across views using compact latent representations. Building upon these, we introduce 3) CS-Thinker to achieve cross-scene spatiotemporal consistency as actions unfold. It learns implicit knowledge of local dynamics from object-semantic tokens of CV-Aligner and global depth from geometric tokens of CO-Fuser, thereby enhancing efficient visual reasoning under scene variations. Extensive experiments demonstrate that, benefiting from its efficient spatiotemporal consistency design, ConsisVLA-4D achieves 21.6% and 41.5% performance improvements, along with 2.3-fold and 2.4-fold inference speedups compared to OpenVLA on the LIBERO benchmark and real-world platforms, this http URL-4D is open-sourced and publicly available at
### Title:
          Transformed Latent Variable Multi-Output Gaussian Processes
 - **Authors:** Xiaoyu Jiang, Xinxing Shi, Sokratia Georgaka, Magnus Rattray, Mauricio A Álvarez
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-Output Gaussian Processes (MOGPs) provide a principled probabilistic framework for modelling correlated outputs but face scalability bottlenecks when applied to datasets with high-dimensional output spaces. To maintain tractability, existing methods typically resort to restrictive assumptions, such as employing low-rank or sum-of-separable kernels, which can limit expressiveness. We propose the Transformed Latent Variable MOGP (T-LVMOGP), a novel framework that scales MOGPs to a massive number of outputs while preserving the capacity to capture meaningful inter-output dependencies. T-LVMOGP constructs a flexible multi-output deep kernel by mapping inputs and output-specific latent variables into an embedding space using a Lipschitz-regularised neural network. Combined with stochastic variational inference, our model effectively scales to high-dimensional output settings. Across diverse benchmarks, including climate modelling with over 10,000 outputs and zero-inflated spatial transcriptomics data, T-LVMOGP outperforms baselines in both predictive accuracy and computational efficiency.
## Keyword: localization
### Title:
          Temporal Reasoning Is Not the Bottleneck: A Probabilistic Inconsistency Framework for Neuro-Symbolic QA
 - **Authors:** Tran Quang Liem
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite significant advances, large language models (LLMs) continue to exhibit brittle performance on complex temporal reasoning tasks. This failure mode is widely attributed to inherent deficits in autoregressive logical deduction. In this paper, we challenge this prevailing narrative, demonstrating that temporal reasoning is not the fundamental bottleneck; rather, the locus of failure lies in unstructured text-to-event representation. We introduce a novel neuro-symbolic question-answering framework governed by a Probabilistic Inconsistency Signal (PIS) that explicitly isolates perceptual errors from reasoning failures. By lifting unstructured text into explicit event graphs and interval constraints, our architecture strictly decouples semantic extraction from a symbolic reasoning engine. To robustly detect structural breaks, the PIS elegantly unifies symbolic credal intervals with epistemic neural uncertainty extracted via Evidential Deep Learning on LLM hidden states. Empirical evaluations reveal a striking paradigm shift: when provided with correct structural representations, our system's explicit proof traces achieve perfect 1.0 accuracy (4000/4000) and strictly zero false positives/negatives on temporal arithmetic benchmarks. On broader, noise-injected QA settings, the framework maintains a competitive 75.1\% accuracy while enabling deterministic, step-level failure localization. Ultimately, by isolating the representation bottleneck from the reasoning substrate, this work reframes temporal QA from an algorithmic reasoning challenge to a structural alignment problem, charting a verifiable path forward for reliable neuro-symbolic AI.
### Title:
          Root-Cause-Driven Automated Vulnerability Repair
 - **Authors:** Hulin Wang, Zion Leonahenahe Basque, Jie Hu, Ati Priya Bajaj, Yibo Liu, Samuel Zhu, Giorgi Kobakhia, Nikhil Chapre, Will Rosenberg, Siddharth Mishra, Aditya Maheshbhai Gabani, Moritz Schloegel, Adam Doupé, Yan Shoshitaishvili, Ruoyu Wang, Tiffany Bao
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent LLM-based systems have made automated vulnerability repair increasingly practical, but two challenges remain. First, without strong signals about where a bug originates, repair agents drift toward shallow edits that silence the observed failure while leaving the underlying defect unresolved. Second, finding the root cause for bugs is hard: even developers familiar with the codebase frequently produce fixes that address symptoms rather than the root cause, and LLM-based agents, operating with noisier context and less program understanding, are no exception. We present Kumushi, a root-cause-driven patching agent that addresses both challenges by combining diversified dynamic fault localization with evidence-weighted ranking to focus the LLM on the code most relevant to the defect. To rigorously measure whether Kumushi produces genuinely better patches, we also introduce a two-tier patch quality metric that pairs automated oracle validation with structured expert assessment of patches. Evaluated on 178 C/C++ vulnerabilities, Kumushi substantially outperforms prior specialized repair agents under automated evaluation while matching a frontier commercial coding agent. Expert assessment then reveals differences that oracles cannot: Kumushi produces more root-cause fixes and fewer superficial patches, and is preferred in the majority of decisive pairwise comparisons. Together, these results demonstrate that progress in automated vulnerability repair requires not only stronger patching systems, but also richer evaluation methods capable of distinguishing genuine fixes from oracle-passing ones.
### Title:
          RemoteZero: Geospatial Reasoning with Zero Human Annotations
 - **Authors:** Liang Yao, Fan Liu, Shengxiang Xu, Chuanyi Zhang, Rui Min, Shimin Di, Yuhui Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geospatial reasoning requires models to resolve complex spatial semantics and user intent into precise target locations for Earth observation. Recent progress has liberated the reasoning path from manual curation, allowing models to generate their own inference chains. Yet a final dependency remains: they are still supervised by human-annotated ground-truth coordinates. This leaves the reasoning process autonomous, but not its spatial endpoint, and prevents true self-evolution on abundant unlabeled remote sensing data. To break this bottleneck, we introduce RemoteZero, a box-supervision-free framework for geospatial reasoning. RemoteZero is motivated by a simple asymmetry: an MLLM is typically better at verifying whether a region satisfies a query than at directly generating precise coordinates. Leveraging this stronger discriminative ability, RemoteZero replaces geometric supervision with intrinsic semantic verification and enables GRPO training without box annotations. The resulting framework further supports iterative self-evolution, allowing the model to improve from unlabeled remote sensing imagery through its own verification signal. Experiments show that RemoteZero achieves competitive performance against strong supervised methods, demonstrating the potential of self-verifying training for geospatial reasoning localization.
### Title:
          SADE: Symptom-Aware Diagnostic Escalation for LLM-Based Network Troubleshooting
 - **Authors:** Kuan-Hao Tseng, Niruth Bogahawatta, Yasod Ginige, Kosta Dekic, Arunan Sivanathan, Suranga Seneviratne
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language model (LLM) agents are increasingly applied to network troubleshooting, but root-cause localization on public benchmarks remains well below practical deployment thresholds. We argue this is because existing agents do not encode the disciplined, layer-by-layer methodology that human network engineers use, and instead rely on free-form deliberation that conflates evidence acquisition with hypothesis commitment. We present SADE (Symptom-Aware Diagnostic Escalation), an agent that encodes the classical Cisco troubleshooting methodology as an explicit policy. SADE pairs a phase-gated diagnostic workflow, which separates evidence acquisition from hypothesis commitment, with a routed library of fault-family skills and high-yield diagnostic helpers. On a held-out 523 incident set of the public NIKA benchmark covering eleven unseen scenarios, SADE improves root-cause F1 by 37 percentage points over a ReAct + GPT-5 baseline; a model-controlled comparison against the same Claude Sonnet backend without the SADE policy attributes 22 of those points to the diagnostic policy alone, showing that the gain is not a side-effect of the model upgrade.
### Title:
          Angle-I2P: Angle-Consistent-Aware Hierarchical Attention for Cross-Modality Outlier Rejection
 - **Authors:** Muyao Peng, Shun Zou, Pei An, You Yang, Qiong Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image-to-point-cloud registration (I2P) is a fundamental task in robotic applications such as manipulation,grasping, and localization. Existing deep learning-based I2P methods seek to align image and point cloud features in a learned representation space to establish correspondences, and have achieved promising results. However, when the inlier ratio of the initial matching pairs is low, conventional Perspective-n-Points (PnP) methods may struggle to achieve accurate results. To address this limitation, we propose Angle-I2P, an outlier rejection network that leverages angle-consistent geometric constraints and hierarchical attention. First, we design a scale-invariant, crossmodality geometric constraint based on angular consistency. This explicit geometric constraint guides the model in distinguishing inliers from outliers. Furthermore, we propose a global-tolocal hierarchical attention mechanism that effectively filters out geometrically inconsistent matches under rigid transformation, thereby improving the Inlier Ratio (IR) and Registration Recall (RR). Experimental results demonstrate that our method achieves state-of-the-art performance on the 7Scenes, RGBD Scenes V2, and a self-collected dataset, with consistent improvements across all benchmarks.
### Title:
          DiCLIP: Diffusion Model Enhances CLIP's Dense Knowledge for Weakly Supervised Semantic Segmentation
 - **Authors:** Zhiwei Yang, Pengfei Song, Yucong Meng, Kexue Fu, Shuo Wang, Zhijian Song
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Weakly Supervised Semantic Segmentation (WSSS) with image-level labels typically leverages Class Activation Maps (CAMs) to achieve pixel-level predictions. Recently, Contrastive Language-Image Pre-training (CLIP) has been introduced to generate CAMs in WSSS. However, previous WSSS methods solely adopt CLIP's vision-language paired property for dense localization, neglecting its inherently limited dense knowledge across both visual and text modalities, which renders CAM generation suboptimal. In this work, we propose DiCLIP, a novel WSSS framework that leverages the generative diffusion model to enhance CLIP's dense knowledge across two modalities. Specifically, Visual Correlation Enhancement (VCE) and Text Semantic Augmentation (TSA) modules are proposed for dense prediction enhancement. To improve the spatial awareness of visual features, our VCE module utilizes diffusion's reliable spatial consistency to mitigate the over-smoothing issue in CLIP's attention. It designs the Attention Clustering Refinement (ACR) module to reliably extract diverse correlation maps from the diffusion model. The correlation maps act as a diversity bias for CLIP's self-attention, recursively pushing its visual features towards a more discriminative dense distribution. To augment the semantics of text embeddings, our TSA module argues that a single text modality is insufficient to encompass the variability of visual categories. Thus, we leverage diffusion's generative power to maintain a dynamic key-value cache model, shifting CAM generation from a patch-text matching mechanism to a novel visual knowledge retrieval paradigm. With these enhancements, DiCLIP not only outperforms state-of-the-art methods on PASCAL VOC and MS COCO but also significantly reduces training costs. Code is publicly available at this https URL.
### Title:
          ULF-Loc: Unbiased Landmark Feature for Robust Visual Localization with 3D Gaussian Splatting
 - **Authors:** Yingdong Gu, Shaocheng Yan, Zhenjun Zhao, Yuan Kou, Jianxin Luo, Pengcheng Shi, Jiayuan Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual localization is a core technology for augmented reality and autonomous navigation. Recent methods combine the efficient rendering of 3D Gaussian Splatting (3DGS) with feature-based localization. These methods rely on direct matching between 2D query features and the 3D Gaussian feature field, but this often results in mismatches due to an inherent bias in the learned Gaussian feature. We theoretically analyze the feature learning process in 3DGS, revealing that the widely adopted $\alpha$-blending optimization inherently introduces bias into 3D point features. This bias stems from the entanglement between individual Gaussians and their neighboring Gaussians, making the learned features unsuitable for precise matching tasks. Motivated by these findings, we propose ULF-Loc, an unbiased landmark feature framework that replaces biased feature optimization with geometry-weighted feature fusion. We further introduce keypoint-consensus landmark sampling to select reliable Gaussians and local geometric consistency verification to reject mismatches caused by rendering artifacts. On the Cambridge Landmarks dataset, ULF-Loc reduces the mean median translation error by 17\% compared to the state-of-the-art, while achieving superior efficiency with only 1/10 the training time and 1/6 the GPU memory of STDLoc.
### Title:
          Hybrid Congestion Classification Framework Using Flow-Guided Attention and Empirical Mode Decomposition
 - **Authors:** Eugene Kofi Okrah Denteh, Blessing Agyei Kyem, Joshua Kofi Asamoah, Armstrong Aboah
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate traffic congestion classification requires models that jointly capture roadway scene context and non-stationary traffic motion, yet most prior work treats these requirements in isolation. Vision-based methods often depend on appearance cues with standard temporal pooling, which can bias predictions toward static infrastructure, whereas signal-based approaches characterize temporal dynamics but lack the spatial context needed for scene-level localization. These complementary limitations motivate a unified framework that links motion evidence to spatial feature selection while preserving data-adaptive temporal characterization. This study therefore proposes FLO-EMD, a hybrid approach that couples motion-guided attention with empirical, data-driven temporal decomposition. Dense optical flow guides channel and spatial attention so that RGB features are refined toward motion-relevant regions. In parallel, aggregated flow statistics form compact motion traces that are decomposed using Empirical Mode Decomposition (EMD) to extract intrinsic temporal components. The resulting EMD embedding is fused with learned spatiotemporal representations to classify light, medium, and heavy congestion. Experiments on 1,050 five-second clips from four surveillance networks show that FLO-EMD achieves 97.5% overall test accuracy (weighted F1 = 0.9742), outperforming established baselines and remaining robust across diverse environmental conditions; ablation and sensitivity analyses further quantify the contributions of EMD, the number of intrinsic mode functions, and the selected motion descriptors.
### Title:
          Dr-PoGO: Direct Radar Pose-Graph Optimization
 - **Authors:** Cedric Le Gentil, Weican Li, Leonardo Brizi, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces Dr-PoGO, a method for Simultaneous Localization And Mapping (SLAM) using a 2D spinning radar. Unlike cameras or lidars that require line-of-sight, millimetre-wave radars can `see' through dust, falling snow, rain, etc. Accordingly, it is a great modality for robust perception regardless of the weather conditions. While most existing radar-based SLAM methods rely on the extraction of point clouds or features to perform ego-motion estimation, Dr-PoGO leverages direct registration techniques for odometry (DRO) and loop-closure registration. An off-the-shelf radar-focused place recognition algorithm, RaPlace, provides loop-closure candidates. As RaPlace does not provide relative transformations, Dr-PoGO introduces a coarse-to-fine registration that uses visual features and descriptors to obtain an initial guess for the direct transformation refinement. The global trajectory is optimized in a pose-graph optimization. Dr-PoGO demonstrates state-of-the-art performance over 300km of data in various real-world automotive environments. Our implementation is publicly available: this https URL.
### Title:
          Toward an Understanding of Developer Behaviour while Using Bug Localization Tools
 - **Authors:** Pablo Diaz Pedreira, Tamara Lopez, Michel Wermelinger
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bug fixing is a complex and time-consuming task in software development. Bug localization research tends to focus on the accuracy of automated tools that suggest source code files for developers to look at. However, little is known about how developers use these tools in practice. This paper reports on an ongoing qualitative user study. Eleven participants worked through four realistic bug localization tasks in a controlled environment and were given varying levels of support information offered by a specialized tool. Participants were asked to think aloud in a semi-structured interview session. The preliminary findings provide insight into three aspects of practice: how developers interact with tools, the role social and contextual information plays, and problem solving. The study demonstrates that bug localization is complex and suggests that the adoption of effective tools depends on more than their accuracy.
### Title:
          VTAgent: Agentic Keyframe Anchoring for Evidence-Aware Video TextVQA
 - **Authors:** Haibin He, Maoyuan Ye, Jing Zhang, Juhua Liu, Bo Du
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video text-based visual question answering (Video TextVQA) aims to answer questions by reasoning over visual textual content appearing in videos. Despite the strong multimodal video understanding capabilities of recent Video-LLMs, their performance on existing Video TextVQA benchmarks remains limited. To better understand this gap, we conduct an upper-bound analysis through frame-wise question answering, counting a sample as correct if any frame yields the right answer, which significantly outperforms direct video-based inference and reveals a substantial performance gap. The results suggest that the primary bottleneck lies in the localization of key question-relevant evidence, rather than in reasoning capacity itself. Building on this insight, we propose a question-guided agent framework that explicitly anchors the relevant keyframes before answering. The approach operates effectively in a training-free setting and consistently surpasses direct video inference. With additional supervised fine-tuning (SFT) and reinforcement learning (RL), it achieves an average improvement of +12.12 in accuracy and +11.15 in ANLS across benchmarks, establishing new state-of-the-art results. Our study underscores the critical role of explicit keyframe anchoring for advancing Video TextVQA. The code will be publicly released.
### Title:
          Adaptive Learning Strategies for AoA-Based Outdoor Localization: A Comprehensive Framework
 - **Authors:** Bac Trinh-Nguyen, Sara Berri, Sin G. Teo, Tram Truong-Huu, Arsenia Chorti
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localization in 5G and 6G networks is essential for important use cases such as intelligent transportation, smart factories, and smart cities. Although deep learning has enabled improving localization accuracy, depending on the deployment scenario and the effort required for dataset collection campaigns on a given infrastructure, the training process for localization models can vary significantly. Furthermore, with respect to feature selection, recent works have demonstrated the robustness of angle-of-arrival (AoA) based localization. In view of these two points, we propose an adaptive framework for AoA-based localization that consists of two alternative learning strategies, each suited either for large or small training datasets. The proposed framework is evaluated on a real, massive multiple input multiple output (mMIMO) orthogonal frequency division multiplexing (OFDM) outdoor channel state information (CSI) dataset. First, we investigate offline learning when large training datasets are available; we propose a hierarchical framework that first distinguishes between line of sight (LoS) and non line of sight (NLoS) regions and then moves to more fine grained localization in the respective region. This approach provides high-performance localization through accumulated batch retraining and an integrated hyperparameter optimization mechanism. Second, when only a small training dataset is available, an online learning framework is proposed, using incremental tree-based and ensemble-based models for handling streaming data and continuously updating mode, as well as an online few-shot learning model for rapidly initializing new classes from a limited labeled support set. These results showcase that highly accurate robust localization can be achieved incrementally during network operation by exploiting online learning, alleviating the need for large dataset collection campaigns.
### Title:
          LoViF 2026 The First Challenge on Holistic Quality Assessment for 4D World Model (PhyScore)
 - **Authors:** Wei Luo, Yiting Lu, Xin Li, Haoran Li, Fengbin Guan, Chen Gao, Xin Jin, Yong Li, Zhibo Chen, Sijing Wu, Kang Fu, Yunhao Li, Ziang Xiao, Huiyu Duan, Jing Liu, Qiang Hu, Xiongkuo Min, Guangtao Zhai, Manxi Sun, Zixuan Guo, Yun Li, Ziyang Chen, Manabu Tsukada, Zhengyang Li, Zhenglin Du, Yi Wen, Licheng Jiao, Fang Liu, Lingling Li, Yiwen Ren, Zhilong Song, Dubing Chen, Yucheng Zhou, Tianyi Yan, Huan Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper reports on the LoViF 2026 PhyScore challenge, a competition on holistic quality assessment of world-model-generated videos across both 2D and 4D generation settings. The challenge is motivated by a central gap in current evaluation practice: perceptual quality alone is insufficient to judge whether generated dynamics are physically plausible, temporally coherent, and consistent with input conditions. Participants are required to build a metric that jointly predicts four dimensions, i.e., Video Quality, Physical Realism, Condition-Video Alignment, and Temporal Consistency. Depart from that, participants also need to localize physical anomaly timestamps for fine-grained diagnosis. The benchmark dataset contains 1,554 videos generated by seven representative world generative models, organized into three tracks (text-2D, image-to-4D, and video-to-4D) and spanning 26 categories. These categories explicitly cover physics-relevant scenarios, including dynamics, optics, and thermodynamics, together with diverse real-world and creative content. To ensure label reliability, scores and anomaly timestamps are produced through trained human annotation with an additional automated quality-control pass. Evaluation is based on both score prediction and anomaly localization, with a composite protocol that combines TimeStamp_IOU and SRCC/PLCC. This report summarizes the challenge design and provides method-level insights from submitted solutions.
## Keyword: transformer
### Title:
          A Self-Attentive Meta-Optimizer with Group-Adaptive Learning Rates and Weight Decay
 - **Authors:** JiangBo Zhao, ZhaoXin Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive optimizers like AdamW apply uniform hyperparameters across all parameter groups, ignoring heterogeneous optimization dynamics across layers and modules. We address this limitation by proposing MetaAdamW - a new optimizer that integrates a self-attention mechanism to dynamically modulate per-group learning rates and weight decay. The modulation factors are produced by a lightweight Transformer encoder that operates on statistical features (gradient norms, momentum norms, correlations) extracted from each parameter group. To train the attention module, we introduce a meta-learning objective that combines gradient alignment, loss decrease, and generalization gap. A key novel contribution is the extension of homoscedastic uncertainty weighting (HUW) with task-specific priorities that directly scale the regularization terms - enabling domain knowledge to guide automatic loss balancing. Extensive experiments on five diverse tasks-time series forecasting (ETT), language modeling (WikiText-2), machine translation (Multi30k), image classification (CIFAR-10), and sentiment analysis (IMDB) - demonstrate that MetaAdamW consistently outperforms the standard AdamW baseline in terms of validation loss, accuracy, or perplexity. Depending on the task, MetaAdamW either reduces overall training time (by up to 17.11%) or improves performance (by up to 11.08%) while introducing only moderate overhead; in some cases, it can also mitigate issues of insufficient convergence caused by premature early stopping. Ablation studies validate the effectiveness of each component, including feature versions, grouping strategies, and the proposed priority-injected uncertainty weighting.
### Title:
          Improving Medical VQA through Trajectory-Aware Process Supervision
 - **Authors:** Halil Ibrahim Gulluk, Olivier Gevaert
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reasoning capabilities are crucial for reliable medical visual question answering (VQA); however, existing datasets rarely include reasoning explanations. We address this by generating reasoning trajectories for six medical VQA benchmarks using the COMCTS algorithm with open-source vision-language models, with an LLM serving as the verification judge. Building on these generated datasets, we propose a two-stage training framework: supervised fine-tuning followed by Group Relative Policy Optimization (GRPO) with a novel process-based reward. While standard approaches rely solely on exact-match rewards for final answers, we introduce a trajectory-aware reward that measures the similarity between generated and ground-truth reasoning processes. Specifically, we embed reasoning steps using sentence transformers and compute the Dynamic Time Warping (DTW) distance between the resulting vector sequences. Experiments across six benchmarks demonstrate that combining the DTW-based process reward with exact-match reward consistently outperforms SFT-only training, raising mean accuracy from 0.598 to 0.689, mean BERTScore from 0.845 to 0.881, and mean ROUGE-L from 0.665 to 0.748. Our results highlight the importance of process supervision in training reasoning-capable medical VLMs. We make our code and generated reasoning datasets publicly available at this https URL
### Title:
          Sparse Autoencoder Decomposition of Clinical Sequence Model Representations: Feature Complexity, Task Specialisation, and Mortality Prediction
 - **Authors:** Chris Sainsbury, Feng Dong, Andreas Karwath
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse autoencoders (SAEs) have been applied to large language models and protein language models, but not systematically to electronic health record (EHR) foundation models. We train TopK SAEs on FlatASCEND, a 14.5-million-parameter autoregressive clinical sequence model, at all 10 residual stream extraction points on INSPECT (outpatient) and MIMIC-IV (ICU). SAE decomposition reveals progressive abstraction across transformer depth: layer-0 features are near-perfect token detectors (45.7% singleton), while layer-6 features span approximately 30 token types across multiple clinical categories (0.5% singleton). Under full-sequence simple linear probes, SAE features outperform dense representations for discrete event prediction (mortality) while dense representations outperform for continuous magnitude prediction (length of stay) - a probe-level representational phenomenon that does not extend to clinically relevant leakage-safe windows, where dense representations match or exceed SAE features across all tested settings (eICU-CRD 48-hour AUC: SAE 0.871 versus dense 0.880; base model zero-shot, SAE dictionaries trained on eICU activations; MIMIC-IV: 0.836 versus 0.914; INSPECT 1-year/3-year: 0.697 versus 0.800). A delta-mode intervention method reduces SAE perturbation noise by 86x, enabling cleaner feature-level experiments, though the resulting perturbation effects are larger than random controls in 3 of 4 conditions but not formally significant. Feature reproducibility across random seeds is 21%, and individual features should be interpreted as illustrative rather than stable.
### Title:
          A Physics-Aware Framework for Short-Term GPU Power Forecasting of AI Data Centers
 - **Authors:** Mohammad AlShaikh Saleh, Sanjay Chawla, Sertac Bayhan, Haitham Abu-Rub, Ali Ghrayeb
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computational Engineering, Finance, and Science (cs.CE); Distributed, Parallel, and Cluster Computing (cs.DC); Emerging Technologies (cs.ET); Operating Systems (cs.OS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI data centers experience rapid fluctuations in power demand due to the heterogeneity of computational tasks that they have to support. For example, the power profile of inference and training of large language models (LLMs) is quite distinct and big divergences can result in the instability of the underlying electricity grid. In this paper we propose, to the best of our knowledge, the first physics-informed DLinear time-series model that can accurately forecast power utilization of an AI data center 5-80 minutes (short-term forecasting) into the future. The physics, based on a multi-node lumped thermal resistance-capacitance (RC) network consistent with Newton's law of cooling, is captured using newly derived time-dependent ordinary differential equations (ODE) that separately models and interlinks power consumption with the GPU compute and memory utilization and temperature. The resulting model, that we refer to as PI-DLinear, trained and evaluated on a real AI data center dataset and is not only more accurate than the state-of-the-art (SOTA) models tested, but the forecast profile respects the underlying physics under power throttling and load transient events. Relative to the SOTA transformer-based and non-transformer-based models, improvements in forecasting accuracy (averaged across all look-back and prediction windows) range from 0.782%-39.08% for MSE, 0.993%-51.82% for MAE, and 0.370%-22.28% for RMSE.
### Title:
          Awaking Spatial Intelligence in Unified Multimodal Understanding and Generation
 - **Authors:** Lin Song, Wenbo Li, Guoqing Ma, Wei Tang, Bo Wang, Yuan Zhang, Yijun Yang, Yicheng Xiao, Jianhui Liu, Yanbing Zhang, Guohui Zhang, Wenhu Zhang, Hang Xu, Nan Jiang, Xin Han, Haoze Sun, Maoquan Zhang, Haoyang Huang, Nan Duan
 - **Subjects:** Subjects:
Graphics (cs.GR); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present JoyAI-Image, a unified multimodal foundation model for visual understanding, text-to-image generation, and instruction-guided image editing. JoyAI-Image couples a spatially enhanced Multimodal Large Language Model (MLLM) with a Multimodal Diffusion Transformer (MMDiT), allowing perception and generation to interact through a shared multimodal interface. Around this architecture, we build a scalable training recipe that combines unified instruction tuning, long-text rendering supervision, spatially grounded data, and both general and spatial editing signals. This design gives the model broad multimodal capability while strengthening geometry-aware reasoning and controllable visual synthesis. Experiments across understanding, generation, long-text rendering, and editing benchmarks show that JoyAI-Image achieves state-of-the-art or highly competitive performance. More importantly, the bidirectional loop between enhanced understanding, controllable spatial editing, and novel-view-assisted reasoning enables the model to move beyond general visual competence toward stronger spatial intelligence. These results suggest a promising path for unified visual models in downstream applications such as vision-language-action systems and world models.
### Title:
          Undetectable Backdoors in Model Parameters: Hiding Sparse Secrets in High Dimensions
 - **Authors:** Sarthak Choudhary, Atharv Singh Patlan, Nils Palumbo, Ashish Hooda, Kassem Fawaz, Somesh Jha
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Sparse Backdoor, a supply-chain attack that plants a \emph{provably undetectable} backdoor in pre-trained image classifiers, including convolutional networks and Vision Transformers. The attack injects a structured sparse perturbation along a randomly chosen direction into a small subset of columns at each fully connected layer, propagating a trigger signal to an adversary-chosen target class, and masks the perturbation with an independent isotropic Gaussian dither. The dither serves a single technical purpose: it induces a clean reference distribution anchored at the pre-trained weights, against which undetectability can be formalized. Under a mild margin condition on the pre-trained classifier, we show that the dithered reference is functionally equivalent to the original classifier. We prove that distinguishing the backdoor-injected model from this reference is at least as hard as Sparse PCA detection, which is computationally infeasible under standard hardness assumptions. The guarantee holds against any probabilistic polynomial-time distinguisher with white-box access to the parameters.
### Title:
          Layerwise LQR for Geometry-Aware Optimization of Deep Networks
 - **Authors:** Simon Dufort-Labbé, Pierre-Luc Bacon, Razvan Pascanu, Simon Lacoste-Julien, Aristide Baratin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Geometry-aware optimizers such as Newton and natural gradient can improve conditioning in deep learning, but scalable variants such as K-FAC, Shampoo, and related preconditioners usually impose structural approximations early, often discarding cross-layer interactions induced by the network computation. We introduce Layerwise LQR (LLQR), a framework for learning structured inverse preconditioners under a global layerwise optimal-control objective. The starting point is an exact equivalence: the steepest-descent step under a broad class of divergence-induced quadratic models--including Newton, Gauss-Newton, Fisher/natural-gradient, and intermediate-layer metrics--can be written as a finite-horizon Linear Quadratic Regulator (LQR) problem. This formulation serves as a reference that exposes the layerwise dynamics and cost matrices encoding the original dense geometry. We then derive a scalable relaxation that learns diagonal, (E-)Kronecker-factored, or other structured inverse preconditioners by minimizing the LQR objective and reusing them across iterations. The resulting optimizer wraps standard methods while retaining a principled connection to second-order geometry, without forming or inverting the global curvature matrix. Experiments on ResNets and Transformers show that LLQR improves optimization dynamics and often translates these gains into improved final test performance, while adding only modest wall-clock overhead. It establishes LLQR as a practical framework for geometry-aware second-order methods and a reference for evaluating scalable approximations.
### Title:
          Lightweight Vulnerability Detection from Code Metrics and Token Features
 - **Authors:** Chun Yin Chiu
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vulnerability detection for C/C++ code increasingly relies on heavy representations such as code graphs and deep models, while many practical workflows still benefit from fast and reproducible ranking baselines for human triage. This preprint studies a lightweight function-level vulnerability triage pipeline that combines sparse token n-grams from raw function text with a small set of inexpensive code metrics, including NLOC, approximate cyclomatic complexity, token count, maximum brace depth, and parameter count. We use TF-IDF token features and a class-weighted logistic regression classifier, avoiding deep learning, transformers, and program graphs. Using the Devign function-level labels, we evaluate random and cross-project settings, including a FFmpeg-to-QEMU transfer experiment. We emphasize precision-recall AUC and Recall@10% as ranking-oriented metrics for skewed or triage-oriented workloads. On the random split, the best combined variant reaches PR-AUC 0.642 and Recall@10% 0.161, while cross-project generalization is substantially harder, with PR-AUC around 0.436. We further report ablations, test-only identifier-renaming robustness, and end-to-end efficiency. The results suggest that simple token and metric features provide a useful transparent baseline, but also expose sensitivity to superficial lexical cues and limited cross-project transfer.
### Title:
          Gradient Flow Structure and Quantitative Dynamics of Multi-Head Self-Attention
 - **Authors:** Ayan Pendharkar
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer self-attention can be interpreted as a gradient flow on the unit sphere, in which tokens evolve under softmax interaction potentials and tend to form clusters. While prior work has established clustering behavior for single-head attention, the multi-head setting remains less understood due to geometric interference between heads, which invalidates standard monotonicity arguments. In this work, we develop a theoretical framework for multi-head self-attention dynamics and resolve several open questions. We show that, under suitable conditions on the score matrices, a natural multi-head energy functional is non-decreasing along both flat and spherical dynamics. We identify the key obstruction to per-head monotonicity as radial shadow terms, which are projections of each head's output onto token directions, persisting even under orthogonality assumptions. We introduce a sufficient condition ensuring monotonicity and establish robustness to approximate orthogonality. In a simplified scalar-head regime with equiangular token configurations, we derive a closed-form expression for the critical inverse temperature governing clustering behavior, and show that heterogeneous heads exhibit super-additive clustering rates. In this regime, we also prove a separation in clustering time between ReLU and softmax attention in the linearized dynamics. Finally, we establish an entropy production identity and show that attention entropy increases monotonically toward equilibrium as clustering progresses. Our results provide a unified perspective on the dynamics of multi-head attention and clarify the mechanisms underlying clustering and stability in transformer models.
### Title:
          Building Power Grid Models from Open Data: A Complete Pipeline from OpenStreetMap to Optimal Power Flow
 - **Authors:** Andrea Britto, Thiago Spina, Weiwei Yang, Spencer Fowers, Baosen Zhang, Chris White
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Access to realistic transmission grid models is essential for power systems research, yet detailed network data in the United States remains restricted under critical-infrastructure regulations. We present a pipeline that constructs complete, OPF-solvable transmission network models entirely from publicly available data. The five-stage pipeline (1) extracts power infrastructure from OpenStreetMap via a local Overpass API instance, (2) reconstructs bus-branch topology through voltage inference, line merging, and transformer detection, (3) estimates electrical parameters using voltage-class lookup tables calibrated with U.S. Energy Information Administration (EIA) plant-level data, (4) allocates hourly demand from EIA-930 to individual buses using US Census population as a spatial proxy, and (5) solves both DC and AC optimal power flow using this http URL with a progressive relaxation strategy that automatically loosens constraints on imprecise models. We validate the pipeline on all 48 contiguous US states and six multi-state regions, including the full Western (5,076 buses) and Eastern (21,697 buses) Interconnections. Of the 48 single-state models, 42 (88%) converge at the strictest relaxation level for AC-OPF at peak hour and 44 (92%) off-peak. Dispatch costs (median $22/MWh) and system losses (median 1.0%) are consistent with real wholesale-market outcomes. The pipeline relies exclusively on open data sources, enabling reproducible grid analysis without proprietary data. All 54 models (48 single-state and 6 multi-state) are publicly released at this https URL.
### Title:
          LUCAS-MEGA: A Large-Scale Multimodal Dataset for Representation Learning in Soil-Environment Systems
 - **Authors:** Kuangdai Leng, Simon Jeffery, Panos Panagos, Tarje Nissen-Meyer
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding soil is fundamental to agriculture, carbon cycling, and environmental sustainability, yet progress is limited by fragmented and heterogeneous datasets that constrain modeling to small-scale predictive settings rather than high-dimensional representation learning. We introduce LUCAS-MEGA, a large-scale multimodal dataset constructed through systematic data fusion of European soil-environment observations, with the LUCAS survey as its backbone. The fused dataset comprises over 70,000 samples and more than 1,000 features spanning physical, chemical, environmental, biological, and visual attributes, aggregated from 68 source datasets. To enable integration at scale, we develop SoilFuser, a multi-agent, human-in-the-loop data fusion pipeline that standardizes heterogeneous data formats and measurement protocols, resolves inconsistencies and invalid entries (e.g., unit inconsistencies, codebook mismatches, and erroneous values), incorporates natural language annotations, and harmonizes multimodal attributes and metadata into a unified, machine learning-ready feature space. The resulting dataset captures key characteristics of real-world soil observations, including multimodality, uneven feature coverage, and heterogeneous uncertainty. To demonstrate the usability of LUCAS-MEGA for data-driven modeling, we pretrain a multimodal tabular transformer (SoilFormer) using a self-supervised objective based on feature masking, achieving stable training, strong predictive performance, and representations that support uncertainty-aware prediction. We further show that the learned representations recover relationships consistent with established soil processes. LUCAS-MEGA is released with open access and is accompanied by composable, agent-friendly APIs that support structured querying and data-driven workflows.
### Title:
          The Scaling Properties of Implicit Deductive Reasoning in Transformers
 - **Authors:** Enrico Vompa, Tanel Tammet
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computational Complexity (cs.CC); Logic in Computer Science (cs.LO); Symbolic Computation (cs.SC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate the scaling properties of implicit deductive reasoning over Horn clauses in depth-bounded Transformers. By systematically decorrelating provability from spurious features and enforcing algorithmic alignment, we find that in sufficiently deep models with a bidirectional prefix mask, implicit reasoning approaches explicit CoT performance across graph topologies and problem widths, though CoT remains necessary for depth extrapolation.
### Title:
          InterFuserDVS: Event-Enhanced Sensor Fusion for Safe RL-Based Decision Making
 - **Authors:** Mustafa Sakhaia, Kaung Sithua, Min Khant Soe Okea, Maciej Wielgosza
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving systems rely heavily on robust sensor fusion to perceive complex envi- ronments. Traditional setups using RGB cameras and LiDAR often struggle in high-dynamic- range scenes or high-speed scenarios due to motion blur and latency. Dynamic Vision Sensors (DVS), or event cameras, offer a paradigm shift by capturing asynchronous brightness changes with microsecond temporal resolution and high dynamic range. In this paper, we propose an extended architecture of the state-of-the-art InterFuser model, integrating DVS as an additional modality to enhance perception reliability. We introduce a novel token-based fusion strategy that incorporates accumulated event frames into the transformer-based backbone of InterFuser. Our method leverages the complementary nature of RGB, LiDAR, and DVS data. We evaluate our approach on the Car Learning to Act (CARLA) Leaderboard benchmarks, demonstrating that the inclusion of DVS improves the robustness of the driving agent, achieving a competitive Driving Score of 77.2 and a superior Route Completion of 100%. The results indicate that event-based vision is a promising direction for improving safety and performance in adverse lighting and dynamic conditions.
### Title:
          Critical Windows of Complexity Control: When Transformers Decide to Reason or Memorize
 - **Authors:** Sarwan Ali
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent work has shown that Transformers' compositional generalization is governed by \emph{complexity control}, initialization scale and weight decay, which steers training toward low-complexity reasoning solutions rather than high-complexity memorization. Existing analyses, however, treat complexity control as a single static hyperparameter choice, leaving open \emph{when} during training this control is actually decisive. We show that the memorization-versus-reasoning fate of a Transformer is determined within a sharp, identifiable window of training. On a controlled compositional task we find that (i)~weight decay applied for a single 25\%-of-training window matches full-training weight decay in out-of-distribution (OOD) accuracy ($0.93$ vs $0.91$); (ii)~holding total regularization budget constant, placing it in the middle of training yields $5{-}9\times$ higher OOD accuracy than placing it early; (iii)~the boundary of the critical window is remarkably sharp, window onset shifted by as little as $100$ optimization steps causes mean OOD to jump from chance ($0.15$) to reasoning-regime ($0.61$); (iv)~the window's position depends systematically on initialization scale, but the basin of attraction for reasoning solutions \emph{shrinks} at small initialization, contradicting the prevailing recommendation that smaller initialization is uniformly better. We further show that the critical-window phenomenon is task-specific: it does not appear on grokking with modular arithmetic, where properly tuned constant weight decay matches scheduled weight decay.
### Title:
          Counterfactual identifiability beyond global monotonicity: non-monotone triangular structural causal models
 - **Authors:** Pengcheng Tan, Jiang Chen, Dehui Du
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Methodology (stat.ME)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Structural causal models provide a unified semantics for interventions and counterfactuals, but most identifiability results rely on restrictive assumptions like global monotonicity, which are often violated in embodied interaction, where the same exogenous perturbation can induce opposite responses under different contact contexts. We ask what structure still suffices once global monotonicity is dropped. We introduce non-monotone triangular structural causal models (NM-TM-SCM), which retain triangular recursion but replace global monotonicity with mechanism-wise invertibility and context-independent inverse transport. We prove that these conditions are equivalent to exogenous isomorphism and imply complete counterfactual identifiability, and we give a counterexample showing that local invertibility alone is insufficient. We instantiate the theory in CausalInverter, with triangular invertible layers, orientation gates, and transport-stability regularization. On synthetic non-monotonic mechanisms, the structural bias yields systematic counterfactual gains as non-monotonicity increases. On MuJoCo Door, our model achieves perfect event-level counterfactual recovery, lowers continuous angle error relative to a Transformer baseline, and delivers substantially more stable recovery than Transformer and conditional-flow predictors. On MuJoCo Push, where non-monotonicity is weaker, the same low-data predictors remain competitive or better, consistent with a bias-variance boundary. These results identify a broader identifiable regime between globally monotone triangular models and unconstrained black-box world models.
### Title:
          FLUID: Continuous-Time Hyperconnected Sparse Transformer for Sink-Free Learning
 - **Authors:** Waleed Razzaq, Yun-Bo Zhao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Continuous-time (CT) Transformers improve irregular and long-range modeling over CT-RNNs by exploiting inputs or outputs embeddings with continuous dynamics. However, the core scaled-dot-product-attention (SDPA) mechanism remains inherently discrete. We propose FLUID (Flexible Unified Information Dynamics), a CT Transformer that incorporates continuous dynamics directly into the attention computation by replacing it with Liquid Attention Network (LAN). LAN reinterprets attention logits as continuous dynamical system and reformulates them as the solution to a linear ODE modulated by input-dependent nonlinear recurrent gates. Theoretically, we establish stability guarantees for LAN dynamics and show that it serves as an interpolating middle ground between SDPA and CT-RNNs, recovering each as special case under well-defined parameterization of its gating functions. LAN also introduces an explicit attention-sink gate to eliminate disproportionate attention mass on uninformative nodes. FLUID replaces standard residual connections with input-dependent Liquid Hyper-Connections to adaptively regulate interlayer information flow. Empirically, we evaluate FLUID on a broad set of learning tasks, including (i) irregular time-series, (ii) long-range modeling, (iii) lane-keeping control of autonomous vehicles, and (iv) learning physical dynamics under a scarce data regime. Across all the tasks, FLUID consistently matches or outperforms CT baselines, achieving improvements of up to 47% in certain scenarios and enhancing generalization under distributional shifts. Additionally, FLUID demonstrates superior noise robustness and a self-correcting inductive bias in autonomous vehicle control. We also provide a detailed analysis of key hyperparameters to guide tuning and show that FLUID occupies an intermediate position among competing approaches in terms of runtime and memory efficiency.
### Title:
          Benchmarking POS Tagging for the Tajik Language: A Comparative Study of Neural Architectures on the TajPersParallel Corpus
 - **Authors:** Mullosharaf K. Arabov
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents the first benchmark for the task of automatic part-of-speech (POS) tagging for the Tajik language. Despite the existence of multilingual language models demonstrating high effectiveness for many of the world's languages, their capacity for grammatical analysis of Tajik has remained unexplored until now. The aim of this study is to fill this gap through a systematic comparison of classical neural network architectures and modern multilingual transformers. Experiments were conducted on the TajPersParallel corpus, a parallel lexical resource comprising approximately 44,000 dictionary entries. Due to the absence of full-fledged example sentences in the current version of the corpus, the task was performed at the level of isolated lexical units, representing a challenging case of context-independent classification. The study compares the following architectures: a recurrent BiLSTM-CRF model, as well as multilingual models XLM-RoBERTa (large), mBERT, ParsBERT (Persian), and ruBERT (Russian), adapted using the parameter-efficient fine-tuning method LoRA. The testing results showed that the best performance is achieved by the mBERT + LoRA model (macro F1-score = 0.11, weighted F1-score = 0.62). It was established that in the absence of syntactic context, all models experience significant difficulty in resolving morphological ambiguity, successfully classifying primarily high-frequency classes ("noun," "adjective") while demonstrating zero effectiveness for rare function words. Zero-shot evaluation revealed the greatest typological proximity of Tajik to Persian (ParsBERT) and Russian (ruBERT). The obtained results form a foundation for further research and development in the field of automatic processing of the Tajik language.
### Title:
          GTF: Omnidirectional EPI Transformer for Light Field Super-Resolution
 - **Authors:** Kunyu Li, Fei Wang, Lichao Zhang, Junjie Liu, Bihong Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Light field (LF) image super-resolution benefits from Epipolar Plane Images (EPIs), whose line slopes explicitly encode disparity. However, existing Transformer-based LF SR methods mainly attend to horizontal and vertical EPIs, leaving diagonal epipolar geometry underexplored. We present GTF, an omnidirectional EPI Transformer that explicitly models horizontal, vertical, 45-degree, and 135-degree EPIs within a unified reconstruction framework. GTF combines directional EPI processing, MacPI-based prior injection, adaptive directional fusion, and a topology-preserving feed-forward network to better exploit LF geometry. For the NTIRE 2026 fidelity tracks, we use GTF as the main model, while a lightweight GTF-Tiny variant targets the efficiency track. On five standard LF SR benchmarks covering both real-captured and synthetic scenes, GTF reaches 32.78 dB without inference-time enhancement, and stronger inference settings with EPSW and test-time augmentation further improve performance. Under the NTIRE 2026 efficiency constraint, GTF-Tiny attains 32.57 dB with only 0.915M parameters and 19.81 GFLOPs. In the NTIRE 2026 Light Field Image Super-Resolution Challenge, our submissions rank 3rd on Track 1 and Track 3 and 4th on Track 2. Architecture-evolution, channel-width, and inference analyses further support the effectiveness of diagonal EPI modeling, directional fusion, and the lightweight design.
### Title:
          HEXST: Hexagonal Shifted-Window Transformer for Spatial Transcriptomics Gene Expression Prediction
 - **Authors:** Keunho Byeon, Jin Tae Kwak
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spatial transcriptomics offers spatially resolved gene expression profiling within tissue sections, but its cost and limited throughput hinder large-scale deployment. To extend this capability to routine practice, recent computational methods aim to infer spatial gene expression directly from ubiquitous hematoxylin and eosin-stained histology slides. However, most existing models assume Cartesian or geometry-agnostic locality, despite the hexagonal sampling of widely used spot-array platforms, and point-wise regression objectives often yield over-smoothed gene expression profiles, obscuring gene-specific spatial heterogeneity. To address these, we propose HEXST, a geometry-aligned Transformer for spatial gene expression prediction from histology. HEXST operates directly on hexagonal spot coordinates to enable efficient local-to-global contextual modeling via tailored shifted-window attention mechanism and hexagonal rotary positional encoding. To enhance gene-wise spatial contrast, HEXST complements point-wise regression with a contrast-sensitive differential objective and transcriptomic priors from a pretrained single-cell foundation model during training. Across seven spatial transcriptomics datasets, HEXST consistently outperforms state-of-the-art models, providing accurate and robust spatial gene expression predictions while preserving gene-wise contrast and spatial heterogeneity.
### Title:
          Average Attention Transformers and Arithmetic Circuits
 - **Authors:** Lena Ehrmuth, Laura Strieker
 - **Subjects:** Subjects:
Computational Complexity (cs.CC); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We analyse the computational power of transformer encoders as sequence-to-sequence functions on vectors. We show that average hard attention can be used to simulate arithmetic circuits if they are given as an input to an encoder. The circuit families that can be simulated this way have constant depth while using unbounded addition, binary multiplication and sign gates. The transformers we use have arithmetic circuits instead of feed-forward networks. With typical average attention the functions they compute are also computed by the same class of circuit families. Our results hold for transformers over the reals, rationals and any ring in between the two.
### Title:
          Not Every Subject Should Stay: Machine Unlearning for Noisy Engagement Recognition
 - **Authors:** Alexander Vedernikov
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Engagement recognition datasets are typically subject-indexed and often contain noisy, subjective supervision, making post-hoc dataset revision a practical problem. Existing noisy-label and data-cleaning methods largely operate at the sample level before or during training, but do not directly address a different question: once a model has already been trained, can the influence of an entire problematic subject be removed without full retraining? We study this setting through subject-level machine unlearning as a post-hoc sanitization mechanism for engagement recognition. Starting from a baseline trained on all subjects, we rank candidate harmful subjects using a model-dependent proxy, apply a lightweight approximate unlearning update, and compare the result against an oracle model retrained from scratch on the retained subjects only. We instantiate this protocol on DAiSEE and EngageNet using Tensor-Convolution and Convolution-Transformer Network (TCCT-Net) as a fixed platform and evaluate three matched model states under the same removal scenario: baseline, unlearned, and oracle. In representative K=3 forget-set settings, the unlearned model recovers 89.3% and 92.5% of the oracle gain on EngageNet and DAiSEE, respectively, at roughly one quarter of retraining cost. Across the tested small-audit regimes, effectiveness is strongest at an intermediate forget-set size, indicating that approximate subject-level unlearning is a useful low-cost correction mechanism, but one whose benefit depends on subject selection quality and removal regime.
### Title:
          AxMoE: Characterizing the Impact of Approximate Multipliers on Mixture-of-Experts DNN Architectures
 - **Authors:** Omkar B Shende, Marcello Traiola, Gayathri Ananthanarayanan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep neural network (DNN) inference at the edge demands simultaneous improvements in accuracy, computational efficiency, and energy consumption. Approximate computing and Mixture-of-Experts (MoE) architectures have each been studied as independent routes towards efficient inference, the former by replacing exact arithmetic with low-power approximate multipliers, the latter by routing inputs through specialized expert sub-networks to enable conditional computation. However, their interaction remains entirely unexplored. This paper presents AxMoE, the first study of the impact of approximate multiplication on MoE DNN architectures. We evaluate three MoE variants: Hard MoE, Soft MoE, and Cluster MoE against dense baselines across three CNN architectures (ResNet-20, VGG11_bn, VGG19_bn) on CIFAR-100 and a Vision Transformer (ViT-Small) on Tiny ImageNet-200 dataset, using eight 8-bit signed multipliers (including one exact baseline) from the EvoApproxLib library. Results show that, without retraining, the Dense baseline is the most resilient topology across all CNN architectures, whereas on ViT-Small, all topologies degrade at comparable rates regardless of routing strategy. After approximate-aware retraining, recovery varies substantially across architectures, topologies, and multipliers. ResNet-20 achieves full recovery across the entire multiplier range, whereas VGG architectures recover at moderate multipliers but fail irreversibly at aggressive ones for all topologies except Cluster MoE on VGG11_bn; on ViT-Small, Hard MoE outperforms Dense under aggressive approximation at equal normalized inference cost. These results pave the way for future approximate MoE hardware-software co-design strategies.
### Title:
          Gyan: An Explainable Neuro-Symbolic Language Model
 - **Authors:** Venkat Srinivasan, Vishaal Jatav, Anushka Chandrababu, Geetika Sharma
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Emerging Technologies (cs.ET); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer based pre-trained large language models have become ubiquitous. There is increasing evidence to suggest that even with large scale pre-training, these models do not capture complete compositional context and certainly not, the full human analogous context. Besides, by the very nature of the architecture, these models hallucinate, are difficult to maintain, are not easily interpretable and require enormous compute resources for training and inference. Here, we describe Gyan, an explainable language model based on a novel non-transformer architecture, without any of these limitations. Gyan achieves SOTA performance on 3 widely cited data sets and superior performance on two proprietary data sets. The novel architecture decouples the language model from knowledge acquisition and representation. The model draws on rhetorical structure theory, semantic role theory and knowledge-based computational linguistics. Gyan's meaning representation structure captures the complete compositional context and attempts to mimic humans by expanding the context to a 'world model'. AI model adoption critically depends on trust and transparency especially in mission critical use cases. Collectively, our results demonstrate that it is possible to create models which are trustable and reliable for mission critical tasks. We believe our work has tremendous potential for guiding the development of transparent and trusted architectures for language models.
### Title:
          Lightweight Cross-Spectral Face Recognition via Contrastive Alignment and Distillation
 - **Authors:** Anjith George, Sebastien Marcel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Heterogeneous Face Recognition (HFR) aims at matching face images captured across different sensing modalities, such as thermal-to-visible or near-infrared-to-visible, enhancing the usability of face recognition systems in challenging real-world conditions. Although recent HFR methods have achieved significant improvements in performance, many rely on computationally expensive models, making them impractical for deployment on resource-limited edge devices. In this work, we introduce a lightweight yet effective HFR framework by adapting a hybrid CNN-Transformer model originally developed for RGB homogeneous face recognition. Our approach enables efficient end-to-end training with only a small amount of paired heterogeneous data, while still maintaining strong performance on standard RGB face recognition benchmarks. This makes it suitable for both homogeneous and heterogeneous settings. Comprehensive experiments on several challenging HFR and face recognition benchmarks show that our method achieves state-of-the-art or competitive performance while keeping computational requirements low.
### Title:
          Gaze4HRI: Zero-shot Benchmarking Gaze Estimation Neural-Networks for Human-Robot Interaction
 - **Authors:** Berk Sezer, Ali Görkem Küçük, Erol Şahin, Sinan Kalkan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While zero-shot appearance-based 3D gaze estimation offers significant cost-efficiency by directly mapping RGB images to gaze vectors, its reliability in Human-Robot Interaction (HRI) settings remains uncertain. Existing benchmarks frequently overlook fundamental HRI conditions, such as dynamic camera viewpoints and moving targets in video. Furthermore, current cross-dataset evaluations often suffer from a complexity gap, where methods trained on diverse datasets are tested on significantly smaller and less varied sets, failing to assess true robustness. To bridge these gaps, we introduce Gaze4HRI, a large-scale dataset (50+ subjects, 3,000+ videos, 600,000+ frames) designed to evaluate state-of-the-art performance against critical HRI variables: illumination, head-gaze conflict, as well as the motion of camera and gaze target in video. Our benchmark reveals that all evaluated methods fail in at least one condition, identifying steeply-downward gaze as a universal failure point. Notably, PureGaze trained on the ETH-X-Gaze dataset uniquely maintains resilience across all other conditions. These results challenge the recent focus in the literature on complex spatial-temporal modeling and Transformer-based architectures. Instead, our findings suggest that extensive data diversity, as exemplified by the ETH-X-Gaze dataset, serves as the primary driver of zero-shot robustness in unconstrained environments, while resilience-enhancing frameworks, such as PureGaze's self-adversarial loss for gaze feature purification, provide a substantial further improvement. Ultimately, this study establishes a rigorous benchmark that provides practical guidelines for practitioners as well as reshaping future research. The dataset and codes are available at this https URL.
### Title:
          Concurrence of Symmetry Breaking and Nonlocality Phase Transitions in Diffusion Models
 - **Authors:** Yifan F. Zhang, Fangjun Hu, Guangkuo Liu, Mert Okyay, Xun Gao
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models undergo a phase transition in a critical time window during generation dynamics, with two complementary diagnoses of criticality. The symmetry breaking picture views the critical window as when trajectories bifurcate into different semantic minima of the energy landscape, whereas the nonlocality picture views the critical window as when local denoising fails. We study whether two notions of such phase transitions are concurrent in modern diffusion transformers. By evaluating the dynamics and outcomes of the generation trajectory, we observe a near-simultaneous occurrence of the non-locality and symmetry breaking critical times. Our work is the first to unify the two notions of phase transitions in practice: it provides a concrete diagnostic for when and why diffusion models rely on conditioning and global denoising, enabling principled evaluation of model efficiency and guiding the design of architectures and sampling schemes that avoid unnecessary computation.
### Title:
          3D Ultrasound-Derived Pseudo-CT Synthesis Using a Transformer-Augmented Residual Network for Real-Time Operator Guidance
 - **Authors:** Sapna Sachan, Amulya Kumar Mahto
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Computed tomography (CT) is indispensable for clinical diagnosis and image-guided interventions but exposes patients to ionizing radiation, motivating the development of safer imaging alternatives. Ultrasound (US) is non-ionizing and widely accessible; however, it is highly operator dependent and lacks quantitative tissue characterization, often leading to diagnostic uncertainty and unnecessary CT examinations. This work presents a 3D ultrasound-derived pseudo-CT (UD-pCT) framework that generates CT-like anatomical reference volumes inferred from US, without aiming to reproduce physically accurate Hounsfield Units. Paired 3D kidney US and CT volumes from the TRUSTED dataset are first spatially aligned using a landmark-based multimodal registration pipeline, creating high-quality paired inputs for supervised training of an adversarial framework. The proposed Bottleneck Transformer Residual U-Net3D (BT-ResUNet3D) model employs a 3D residual encoder-decoder generator augmented with a transformer bottleneck, enabling effective modeling of fine-grained local anatomical structures as well as long-range volumetric dependencies, while a 3D Conditional PatchGAN discriminator enforces local structural realism in the synthesized pseudo-CT volumes. Quantitative evaluation using PSNR and SSIM demonstrates that the proposed method outperforms established baselines in structural fidelity and perceptual image quality. The UD-pCT volumes provide real-time anatomical reference for operator guidance, potentially reducing acquisition variability and unnecessary CT use. A limitation of this study is the relatively small paired dataset, which may limit the generalizability of the proposed model.
### Title:
          Anticipating Innovation Using Large Language Models
 - **Authors:** Enrico Maria Fenoaltea, Filippo Santoro, Giordano De Marzo, Segun Taofeek Aroyehun, Andrea Tacchella
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Forecasting innovation, intended as the emergence of new technological combinations, is a fundamental challenge for science and policy. We show that forthcoming combinations leave an early trace in the collective language of patents, with predictive signals detectable even decades in advance. We show that signal is not attributable to any single inventor, but emerges as a collective shift in how technologies are described across thousands of patents. To this end, we introduce TechToken, a transformer-based model that treats technologies, classified by International Patent Classification codes, as words in its vocabulary, learning the language of technologies by embedding these codes during fine-tuning. We define context similarity between code embeddings as a measure of linguistic convergence and show that it accurately predicts first technological combinations. TechToken also improves general representation quality, outperforming state-of-the-art models across different patent-related tasks.
### Title:
          On the (In-)Security of the Shuffling Defense in the Transformer Secure Inference
 - **Authors:** Zhengyi Li, Yakai Wang, Kang Yang, Yu Yu, Jiaping Gui, Yu Feng, Ning Liu, Minyi Guo, Jingwen Leng
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 For Transformer models, cryptographically secure inference ensures that the client learns only the final output, while the server learns nothing about the client's input. However, securely computing nonlinear layers remains a major efficiency bottleneck due to the substantial communication rounds and data transmission required. To address this issue, prior works reveal intermediate activations to the client, allowing nonlinear operations to be computed in plaintext. Although this approach significantly improves efficiency, exposing activations enables adversaries to extract model weights. To mitigate this risk, existing works employ a shuffling defense that reveals only randomly permuted activations to the client. In this work, we show that the shuffling defense is not as robust as previously claimed. We propose an attack that aligns differently shuffled activations to a common permutation and subsequently exploits them to extract model weights. Experiments on Pythia-70m and GPT-2 demonstrate that the proposed attack can align shuffled activations with mean squared errors ranging from $10^{-9}$ to $10^{-6}$. With a query cost of approximately \$1, the adversary can recover model weights with L1-norm differences ranging from $10^{-4}$ to $10^{-2}$ compared to the oracle weights.
### Title:
          Rethinking Local Learning: A Cheaper and Faster Recipe for LLM Post-Training
 - **Authors:** Hengyu Shi, Tianyang Han, Peizhe Wang, Zhiling Wang, Xu Yang, Junhao Su
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM post-training typically propagates task gradients through the full depth of the model. Although this end-to-end structure is simple and general, it couples task adaptation to full-depth activation storage, long-range backward dependencies and direct task-gradient access to pretrained representations. We argue that this full-depth backward coupling can be unnecessarily expensive and intrusive, particularly when post-training supervision is much narrower than pre-training. To this end, we propose \textbf{LoPT}: Local-Learning Post-Training, a simple post-training strategy that makes gradient reach an explicit design choice. LoPT places a single gradient boundary at the transformer midpoint: the second-half block learns from the task objective, while the first-half block is updated by a lightweight feature-reconstruction objective to preserve useful representations and maintain interface compatibility. LoPT shortens the task-induced backward path while limiting direct interference from narrow task gradients on early-layer representations. Extensive experiments demonstrate that LoPT achieves competitive performance with lower memory cost, higher training efficiency and better retention of pretrained capabilities. Our code is available at: this https URL
### Title:
          DART: A Vision-Language Foundation Model for Comprehensive Rope Condition Monitoring
 - **Authors:** Anju Rani, Daniel Ortiz-Arroyo, Petar Durdevic
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The condition monitoring (CM) of synthetic fibre ropes (SFRs) used in offshore, maritime, and industrial settings demands more than a classifier: inspectors need continuous severity estimates, maintenance recommendations, anomaly flags, deterioration timelines, and automated reports, all from a single inspection image. We present DART (Damage Assessment via Rope Transformer), a vision-language foundation model that addresses the full rope inspection workflow through a unified multi-task architecture. DART extends the Joint-Embedding Predictive Architecture (JEPA) to the cross-modal domain by coupling a Vision Transformer (ViT-H/14) with Llama-3.2-3B-Instruct via a Severity-Conditioned Cross-Modal Fusion (SC-CMF) module. Three architectural innovations drive the model's versatility: (1) HD-MASK, a saliency-guided masking strategy that focuses self-supervised reconstruction on damage-dense patches; (2) per-class learnable severity gates that adaptively weight language grounding by damage category; and (3) a Contrastive Damage Disentanglement (CDD) loss that shapes the embedding space to simultaneously encode damage type, severity ordering, and cross-modal semantics. Trained once on 4,270 images spanning 14 fine-grained rope damage classes, the frozen DART backbone supports downstream tasks without any task-specific fine-tuning: damage classification (93.22 % accuracy, 91.04 % macro-F1, +38.5 pp over a vision-only baseline), continuous severity regression (Spearman rho = 0.94, within-1-ordinal accuracy 99.6 %), few-shot recognition (89.2 % macro-F1 at 20 shots). These results demonstrate that DART functions as a general-purpose CM backbone that goes well beyond classification, providing actionable inspection intelligence from a single shared representation.
### Title:
          Adaptive Inverted-Index Routing for Granular Mixtures-of-Experts
 - **Authors:** Klaus-Rudolf Kladny, Maximilian Mordig, Bernhard Schölkopf, Michael Muehlebach
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mixture-of-experts (MoE) models enable scalable transformer architectures by activating only a subset of experts per token. Recent evidence suggests that performance improves with increasingly granular experts, i.e., many small experts instead of a few large ones. However, this regime substantially increases routing cost, which can dominate computation. We introduce adaptive inverted-index routing for MoE (AIR-MoE), an inverted-index-inspired routing architecture based on vector quantization (VQ). In a first stage, AIR-MoE performs coarse shortlisting by assigning tokens to VQ codewords to construct a candidate set of experts. In a second stage, fine scoring computes exact routing scores restricted to this shortlist. This two-stage procedure approximates true top-k routing while avoiding full expert scoring and, in contrast to prior work, imposing no structural constraints on expert parameters. AIR-MoE serves as a drop-in replacement for standard routers and requires no modifications to the model architecture or loss function. We further provide a lower bound on the mass recall achieved by AIR-MoE that yields insights into its inner workings. Empirically, we demonstrate that AIR-MoE achieves improved performance compared to existing routing approaches in granular MoE settings.
### Title:
          Why Geometric Continuity Emerges in Deep Neural Networks: Residual Connections and Rotational Symmetry Breaking
 - **Authors:** Kyungwon Jeong, Won-Gi Paeng, Honggyo Suh
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Weight matrices in deep networks exhibit geometric continuity -- principal singular vectors of adjacent layers point in similar directions. While this property has been widely observed, its origin remains unexplained. Through experiments on toy MLPs and small transformers, we identify two mechanisms: residual connections create cross-layer gradient coherence that aligns weight updates across layers, and symmetry-breaking nonlinearities constrain all layers to a shared coordinate frame, preventing the rotation drift that would otherwise destabilize weight structure. Crucially, a nonlinear but rotation-preserving activation fails to retain continuity, isolating symmetry breaking -- not nonlinearity itself -- as the active ingredient. Activation and normalization play distinct roles: activation concentrates continuity in the leading singular direction, while normalization distributes it across multiple directions. In transformers, continuity is projection-specific: Q, K, Gate, and Up (which read from the residual stream) develop input-space ($\mathbf{v}_1$) continuity; O and Down (which write to it) develop output-space ($\mathbf{u}_1$) continuity; V alone, lacking an adjacent nonlinearity, develops only low continuity.
### Title:
          Empirical Study of Pop and Jazz Mix Ratios for Genre-Adaptive Chord Generation
 - **Authors:** Jinju Lee
 - **Subjects:** Subjects:
Sound (cs.SD); Information Retrieval (cs.IR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chord progression generation is practically important but understudied. Most large-scale symbolic music systems target melody, multi-track arrangement, or audio synthesis, and chord-only models tend to be relegated to conditioning components inside larger pipelines. This paper treats chord generation as a standalone task and addresses a question that arises whenever such a model is adapted across genres: how much old-domain data must be retained during fine-tuning to acquire a new domain without forgetting the old? I study jazz fine-tuning starting from a pop-pretrained 25M-parameter Music Transformer (84.24% top-1 chord accuracy on a held-out pop test set). The available jazz corpus is an order of magnitude smaller than the pop corpus, so every fine-tune run uses all 1,513 jazz training sequences. The swept variable is the volume of pop "rehearsal" data mixed alongside, taking values in {0, 1K, 2.5K, 5K, 10K}. Every fine-tuned model gains 7 to 9 points of jazz top-1. Pop accuracy collapses by 2.14 points under jazz-only fine-tuning, recovers to baseline at approximately 2.5K rehearsal samples (1.65x the jazz volume), and saturates beyond that point. A complementary observation: the metric-best run (F3, 2.5K mix) is not always the perceptually preferred one. The pop-leaning (10K) and jazz-leaning (1K) endpoints carry more committed stylistic identities that the author more often selects as finished output in informal listening. I discuss what this suggests for music co-creation tools but make no perceptual claim, since no formal listening study has been conducted. All six checkpoints are released on the HuggingFace Hub at this https URL.
### Title:
          Chaotic Contrastive Learning for Robust Texture Classification
 - **Authors:** Joao B Florindo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Texture classification is a pivotal task in computer vision, presenting unique challenges due to high inter-class similarity and the sensitivity of structural patterns to scale and illumination changes. While Convolutional Neural Networks (CNNs) and recent Vision Transformers have set performance benchmarks, they often require extensive labeled datasets or struggle to generalize across domains due to an over-reliance on color and shape features. This paper introduces a novel framework that synergizes Self-Supervised Learning (SSL) with deterministic chaotic dynamics. We propose a chaotic contrastive pre-training strategy, where pixel-wise chaotic maps, specifically Logistic, Tent, and Sine maps, act as non-linear data augmentation techniques. These chaotic perturbations, grounded in ergodic theory, force the network to learn topologically robust features by mimicking complex environmental noise and reflectance variations. Furthermore, we introduce an attention-based feature ensemble that fuses high-level semantic representations from a supervised large backbone with low-frequency structural features from a chaos-pretrained tiny encoder. Experimental results on six texture benchmarks (FMD, UMD, KTH-TIPS2-b, DTD, GTOS, and 1200Tex) demonstrate the superiority of the proposed method, outperforming state-of-the-art approaches and achieving promising accuracies on all the analyzed datasets.
### Title:
          Computer-Aided Design Generation by Cascaded Discrete Diffusion Model
 - **Authors:** Honghu Pan, Xiaoling Luo, Yongyong Chen, Zhenyu He, Pengyang Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent deep learning approaches seek to automate CAD creation by representing a model as a sequence of discrete commands and parameters, and then generating them using autoregressive models or continuous diffusion operating in Euclidean embedding space. However, continuous diffusion perturbs representations in a continuous Euclidean domain that does not reflect the inherently discrete and heterogeneous nature of CAD tokens, often producing perturbed representations that map to semantically invalid symbols. To overcome this limitation, we propose a cascaded discrete diffusion framework for CAD generation, which consists of a command diffusion for generating CAD commands and a parameter diffusion conditioned on CAD commands. Unlike isotropic Gaussian perturbation, the forward process of our approach operates directly over categorical token distributions using delicate transition matrices. For commands, we adopt an absorbing-state transition matrix that progressively corrupts tokens to a designated symbol; for parameters, we introduce specific transition matrices tailored to heterogeneous attributes: a Gaussian kernel for coordinate continuity, a scale-invariant kernel for dimensional values, and a prior-preserving kernel for boolean attributes. The reverse process is achieved by two denoising networks: a Transformer-based encoder for command recovery, and a parameter network with extra local self-attention for command-level interaction and cross-attention for conditional injection. Experiments on the DeepCAD dataset show that the proposed approach surpasses existing autoregressive and continuous diffusion models on unconditional generation metrics, while qualitative results validate effective controllability in conditional generation tasks. Source codes will be released.
### Title:
          The Impossibility Triangle of Long-Context Modeling
 - **Authors:** Yan Zhou
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We identify and prove a fundamental trade-off governing long-sequence models: no model can simultaneously achieve (i) per-step computation independent of sequence length (Efficiency), (ii) state size independent of sequence length (Compactness), and (iii) the ability to recall a number of historical facts proportional to sequence length (Recall). We formalize this trade-off within an Online Sequence Processor abstraction that unifies Transformers, state space models, linear recurrent networks, and their hybrids. Using the Data Processing Inequality and Fano's Inequality, we prove that any model satisfying Efficiency and Compactness can recall at most O(poly(d)/log V) key-value pairs from a sequence of arbitrary length, where d is the model dimension and V is the vocabulary size. We classify 52 architectures published before March 2026 into the triangle, showing that each achieves at most two of the three properties and that hybrid architectures trace continuous trajectories in the interior. Experiments on synthetic associative recall tasks with five representative architectures validate the theoretical bound: empirical recall capacity lies strictly below the information-theoretic limit, and no architecture escapes the triangle.
### Title:
          CapsID: Soft-Routed Variable-Length Semantic IDs for Generative Recommendation
 - **Authors:** Wenzhuo Cheng, Menghang Gong, Qixin Guo, Hang Zheng, Zhaobin Yang, Jianguo Lou, Zhengwei Zheng
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative recommendation maps each item to a sequence of Semantic IDs (SIDs) and recasts retrieval as autoregressive token generation. In this paradigm the main bottleneck is the tokenizer rather than the Transformer: residual vector quantization with a hard nearest-neighbor assignment at every layer collapses multi-faceted item semantics at cluster boundaries and propagates early errors to later SID positions. A common workaround is to append a dense vector or attribute prefix to the SID, but this dual-representation design inflates inference cost and gives up the simplicity of a generative interface. We address the bottleneck at the tokenizer itself. CAPSID replaces hard residual quantization with capsule routing: at each layer an item probabilistically routes to several semantic capsules, the residual is updated by the routed reconstruction rather than by a single winning code, and the SID terminates once the active capsule's confidence is high enough. On top of CAPSID, SEMANTICBPE composes adjacent SID tokens into reusable subwords by combining their co-occurrence with their embedding compatibility. On Amazon Beauty, Sports, Toys, and a 35M-item proprietary industrial catalog, CAPSID+SEMANTICBPE improves Recall at 10 by 9.6% on average over ReSID, the strongest single-representation baseline, and matches or exceeds a COBRA-style sparse-dense system on every public benchmark while running at 51% of its inference latency. Ablations show that soft routing, iterative agreement, and confidence-driven length each contribute independently, and the gains are largest on tail items where boundary semantics dominate.
### Title:
          Superposition Is Not Necessary: A Mechanistic Interpretability Analysis of Transformer Representations for Time Series Forecasting
 - **Authors:** Alper Yıldırım
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer architectures have been widely adopted for time series forecasting, yet whether the representational mechanisms that make them powerful in NLP actually engage on time series data remains unexplored. The persistent competitiveness of simple linear models such as DLinear has fueled ongoing debate, but no mechanistic explanation for this phenomenon has been offered. We address this gap by applying sparse autoencoders (SAEs), a tool from mechanistic interpretability, to probe the internal representations of PatchTST. We first establish that a single-layer, narrow-dimensional transformer matches the forecasting performance of deeper configurations across commonly used benchmarks. We then train SAEs on the post-GELU intermediate FFN activations with dictionary sizes ranging from 0.5x to 4.0x the native dimensionality. Expanding the dictionary yields negligible downstream performance change (average 0.214%), with large portions of overcomplete dictionaries remaining inactive. Targeted causal interventions on dominant latent features produce minimal forecast perturbation. Across all evaluated settings, we observe no empirical evidence that the analyzed FFN representations rely on strong superposition. Instead, the representations remain sparse, stable under aggressive dictionary expansion, and largely insensitive to latent interventions. These results demonstrate that superposition is not necessary for competitive performance on standard forecasting benchmarks, suggesting they may not demand the rich compositional representations that drive transformer success in language modeling, and helping explain the persistent competitiveness of simple linear models
### Title:
          Understanding In-Context Learning for Nonlinear Regression with Transformers: Attention as Featurizer
 - **Authors:** Alexander Hsu, Zhaiming Shen, Wenjing Liao, Rongjie Lai
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pre-trained transformers are able to learn from examples provided as part of the prompt without any weight updates, a remarkable ability known as in-context learning (ICL). Despite its demonstrated efficacy across various domains, the theoretical understanding of ICL is still developing. Whereas most existing theory has focused on linear models, we study ICL in the nonlinear regression setting. Through the interaction mechanism in attention, we explicitly construct transformer networks to realize nonlinear features, such as polynomial or spline bases, which span a wide class of functions. Based on this construction, we establish a framework to analyze end-to-end in-context nonlinear regression with the constructed features. Our theory provides finite-sample generalization error bounds in terms of context length and training set size. We numerically validate the theory on synthetic regression tasks.
### Title:
          Taming Outlier Tokens in Diffusion Transformers
 - **Authors:** Xiaoyu Wu, Yifei Wang, Tsu-Jui Fu, Liang-Chieh Chen, Zhe Gan, Chen Wei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study outlier tokens in Diffusion Transformers (DiTs) for image generation. Prior work has shown that Vision Transformers (ViTs) can produce a small number of high-norm tokens that attract disproportionate attention while carrying limited local information, but their role in generative models remains underexplored. We show that this phenomenon appears in both the encoder and denoiser of modern Representation Autoencoder (RAE)-DiT pipelines: pretrained ViT encoders can produce outlier representations, and DiTs themselves can develop internal outlier tokens, especially in intermediate layers. Moreover, simply masking high-norm tokens does not improve performance, indicating that the problem is not only caused by a few extreme values, but is more closely related to corrupted local patch semantics. To address this issue, we introduce Dual-Stage Registers (DSR), a register-based intervention for both components: trained registers when available, recursive test-time registers otherwise, and diffusion registers for the denoiser. Across ImageNet and large-scale text-to-image generation, these interventions consistently reduce outlier artifacts and improve generation quality. Our results highlight outlier-token control as an important ingredient in building stronger DiTs.
## Keyword: autonomous driving
### Title:
          Beyond Fixed Thresholds and Domain-Specific Benchmarks for Explainable Multi-Task Classification in Autonomous Vehicles
 - **Authors:** Maryam Sadat Hosseini Azad, Shahriar Baradaran Shokouhi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scene understanding is a vital part of autonomous driving systems, which requires the use of deep learning models. Deep learning methods are intrinsically black box models, which lack transparency and safety in autonomous driving. To make these systems transparent, multi-task visual understanding has become crucial for explainable autonomous driving perception systems, where simultaneous prediction of multiple driving behaviors and their underlying explanations is essential for safe navigation and human trust in autonomous vehicles. In order to design an accurate and cross-cultural explainable autonomous driving system, we introduce a comprehensive confidence threshold sensitivity analysis that evaluates various threshold values to identify optimal decision boundaries for different tasks. Our analysis demonstrates that traditional fixed threshold approaches are suboptimal for multi-task scenarios. Through extensive evaluation, we demonstrate that our adaptive threshold selection methodology improves F1-scores across different tasks. In addition, we introduce IUST-XAI-AD, a novel dataset consisting of 958 images with human annotations for driving decisions and corresponding reasoning. This dataset addresses the critical gap in domain-specific evaluation benchmarks for distinct driving contexts and provides a more challenging test environment compared to existing datasets. Experimental results demonstrate that confidence threshold sensitivity analysis can significantly improve model performance, while the introduction of the IUST-XAI-AD dataset reveals important insights about cross-cultural driving behavior patterns. The combined contributions of this work provide both methodological advances and practical evaluation tools that can accelerate the development of more reliable, explainable, and culturally-adaptive autonomous driving systems for global deployment.
### Title:
          InterFuserDVS: Event-Enhanced Sensor Fusion for Safe RL-Based Decision Making
 - **Authors:** Mustafa Sakhaia, Kaung Sithua, Min Khant Soe Okea, Maciej Wielgosza
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving systems rely heavily on robust sensor fusion to perceive complex envi- ronments. Traditional setups using RGB cameras and LiDAR often struggle in high-dynamic- range scenes or high-speed scenarios due to motion blur and latency. Dynamic Vision Sensors (DVS), or event cameras, offer a paradigm shift by capturing asynchronous brightness changes with microsecond temporal resolution and high dynamic range. In this paper, we propose an extended architecture of the state-of-the-art InterFuser model, integrating DVS as an additional modality to enhance perception reliability. We introduce a novel token-based fusion strategy that incorporates accumulated event frames into the transformer-based backbone of InterFuser. Our method leverages the complementary nature of RGB, LiDAR, and DVS data. We evaluate our approach on the Car Learning to Act (CARLA) Leaderboard benchmarks, demonstrating that the inclusion of DVS improves the robustness of the driving agent, achieving a competitive Driving Score of 77.2 and a superior Route Completion of 100%. The results indicate that event-based vision is a promising direction for improving safety and performance in adverse lighting and dynamic conditions.
### Title:
          Ground4D: Spatially-Grounded Feedforward 4D Reconstruction for Unstructured Off-Road Scenes
 - **Authors:** Shuo Wang, Jilin Mei, Fuyang Liu, Wenfei Guan, Fanjie Kong, Zhihua Zhao, Shuai Wang, Chen Min, Yu Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feedforward Gaussian Splatting has recently emerged as an efficient paradigm for 4D reconstruction in autonomous driving. However, in unstructured off-road scenes, its performance degrades due to high-frequency geometry, ego-motion jitter, and increased non-rigid dynamics. These factors introduce conflicting Gaussian observations across timestamps, leading to either over-smoothed renderings or structural artifacts. To address this issue, we propose Ground4D, a spatially-grounded 4D feedforward framework for pose-free off-road reconstruction. The key idea is to resolve temporal conflicts through spatially localized conditioning. Specifically, we introduce voxel-grounded temporal Gaussian aggregation, which partitions the canonical Gaussian space into spatial voxels and performs query-conditioned temporal attention within each voxel. Intra-voxel softmax normalization ensures that temporal selectivity and spatial occupancy become mutually reinforcing rather than conflicting. We furthermore introduce surface normal cues as auxiliary geometric guidance to regularize the geometry of Gaussian primitives. Extensive experiments on ORAD-3D and RELLIS-3D demonstrate that Ground4D consistently outperforms existing feedforward methods in reconstruction quality and generalizes zero-shot to unseen off-road domains. Project page and code:this https URL.
### Title:
          CRAFT: Counterfactual-to-Interactive Reinforcement Fine-Tuning for Driving Policies
 - **Authors:** Keyu Chen, Nanfei Ye, Yida Wang, Wenchao Sun, Danqi Zhao, Hao Cheng, Sifa Zheng
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-loop imitation learning has advanced modern autonomous driving policy architectures, but closed-loop deployment remains vulnerable to policy-induced distribution shift. Existing post-training paradigms exhibit fundamental trade-offs: closed-loop RL fine-tuning provides grounded feedback from executed actions but is constrained by the sparsity of informative events, whereas counterfactual fine-tuning provides dense supervision over candidate futures but inherits bias from imperfect future estimates. We introduce Counterfactual-to-Interactive Reinforcement Fine-Tuning (CRAFT), an on-policy framework that formulates closed-loop post-training as proxy-residual optimization. CRAFT uses group-normalized counterfactual advantages as a dense proxy for real closed-loop advantages and aligns this proxy with the closed-loop world through grounded residual correction from interaction-critical events. To stabilize adaptation, CRAFT regularizes the online policy toward an EMA teacher via asymmetric KL self-distillation. Theoretically, CRAFT decomposes the real closed-loop policy gradient into proxy and residual terms under the same visited-state distribution, reducing residual variance with an aligned proxy while mitigating proxy bias through grounded residual approximation. Empirically, CRAFT achieves the strongest closed-loop gains on Bench2Drive across hierarchical planning, vision-language-action, and vocabulary-scoring architectures. Ablations, scaling behavior, stability analyses, and transfer results further validate the complementary roles of dense counterfactual proxy and grounded residual correction. Project page: this https URL.
### Title:
          Information Coordination as a Bridge: A Neuro-Symbolic Architecture for Reliable Autonomous Driving Scene Understanding
 - **Authors:** Shuo Liu, Lei Shi, Haowen Liu, Jing Xu, Yufei Gao, Yucheng Shi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable autonomous driving requires scene understanding that is semantically consistent across heterogeneous sensors and verifiable at the reasoning stage. However, many recent LLM-driven driving systems attach the language model as a post-processor and force it to reason over redundant or conflicting perception outputs, which can amplify hallucinated entities and unsafe conclusions. This paper proposes InfoCoordiBridge, a BEV-centric neuro-symbolic architecture that inserts an explicit coordination bridge between perception and language reasoning. InfoCoordiBridge comprises (i) a unified multi-agent perception layer that outputs typed structured facts together with modality-focused synopses, (ii) an ICA module that aligns and fuses multi-source outputs into a single SceneSummary, and (iii) an SSRE module that performs SceneSummary-grounded reasoning with verification. Experiments on nuScenes and Waymo show that ICA preserves competitive 3D detection accuracy while substantially improving fusion consistency, reducing redundancy to below 1% and achieving about 98% attribute agreement. On NuScenes-QA and a template-aligned Waymo-QA benchmark, SSRE improves factual grounding and reduces hallucinated entity mentions compared with representative VLM and agentic baselines. Overall, by coordinating multi-sensor outputs into a single conflict-aware SceneSummary before prompting, InfoCoordiBridge prevents redundant and cross-modally inconsistent perception evidence from propagating into high-level reasoning.
### Title:
          ReflectDrive-2: Reinforcement-Learning-Aligned Self-Editing for Discrete Diffusion Driving
 - **Authors:** Huimin Wang, Yue Wang, Bihao Cui, Pengxiang Li, Ben Lu, Mingqian Wang, Tong Wang, Chuan Tang, Teng Zhang, Kun Zhan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce ReflectDrive-2, a masked discrete diffusion planner with separate action expert for autonomous driving that represents plans as discrete trajectory tokens and generates them through parallel masked decoding. This discrete token space enables in-place trajectory revision: AutoEdit rewrites selected tokens using the same model, without requiring an auxiliary refinement network. To train this capability, we use a two-stage procedure. First, we construct structure-aware perturbations of expert trajectories along longitudinal progress and lateral heading directions and supervise the model to recover the original expert trajectory. We then fine-tune the full decision--draft--reflect rollout with reinforcement learning (RL), assigning terminal driving reward to the final post-edit trajectory and propagating policy-gradient credit through full-rollout transitions. Full-rollout RL proves crucial for coupling drafting and editing: under supervised training alone, inference-time AutoEdit improves PDMS by at most $0.3$, whereas RL increases its gain to $1.9$. We also co-design an efficient reflective decoding stack for the decision--draft--reflect pipeline, combining shared-prefix KV reuse, Alternating Step Decode, and fused on-device unmasking. On NAVSIM, ReflectDrive-2 achieves $91.0$ PDMS with camera-only input and $94.8$ PDMS in a best-of-6 oracle setting, while running at $31.8$ ms average latency on NVIDIA Thor.
### Title:
          Physical Adversarial Clothing Evades Visible-Thermal Detectors via Non-Overlapping RGB-T Pattern
 - **Authors:** Xiaopei Zhu, Guanning Zeng, Zhanhao Hu, Jun Zhu, Xiaolin Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visible-thermal (RGB-T) object detection is a crucial technology for applications such as autonomous driving, where multimodal fusion enhances performance in challenging conditions like low light. However, the security of RGB-T detectors, particularly in the physical world, has been largely overlooked. This paper proposes a novel approach to RGB-T physical attacks using adversarial clothing with a non-overlapping RGB-T pattern (NORP). To simulate full-view (0$^{\circ}$--360$^{\circ}$) RGB-T attacks, we construct 3D RGB-T models for human and adversarial clothing. NORP is a new adversarial pattern design using distinct visible and thermal materials without overlap, avoiding the light reduction in overlapping RGB-T patterns (ORP). To optimize the NORP on adversarial clothing, we propose a spatial discrete-continuous optimization (SDCO) method. We systematically evaluated our method on RGB-T detectors with different fusion architectures, demonstrating high attack success rates both in the digital and physical worlds. Additionally, we introduce a fusion-stage ensemble method that enhances the transferability of adversarial attacks across unseen RGB-T detectors with different fusion architectures.
### Title:
          CARD: A Multi-Modal Automotive Dataset for Dense 3D Reconstruction in Challenging Road Topography
 - **Authors:** Gasser Elazab, Frank Neuhaus, Tilman Koß, Malte Splietker, Aditya Date, Michael Unterreiner, Maximilian Jansen, Olaf Hellwich
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving must operate across diverse surfaces to enable safe mobility. However, most driving datasets are captured on well-paved flat roads. Moreover, recent driving datasets primarily provide sparse LiDAR ground truth for images, which is insufficient for assessing fine-grained geometry in depth estimation and completion. To address these gaps, we introduce CARD, a multi-modal driving dataset that delivers quasi-dense 3D ground truth across continuous sequences rich in speed bumps, potholes, irregular surfaces and off-road segments. Our sensor suite includes synchronized global-shutter stereo cameras, front and rear LiDARs, 6-DoF poses from LiDAR-inertial odometry, per-wheel motion traces, and full calibration. Notably, our multi-LiDAR fusion yields ~500K valid depth pixels per frame, about 6.5x more than KITTI Depth Completion and 10x more on average than other public driving datasets. The dataset spans ~110 km and 4.7 hours across Germany and Italy. In addition, CARD provides 2D bounding boxes targeting road-topography irregularities, enabling accurate benchmarking for both geometry and perception tasks. Furthermore, we establish a standardized evaluation protocol for road surface irregularities on CARD and benchmark state-of-the-art depth estimation models to provide strong baselines. The CARD dataset is hosted on this https URL.
### Title:
          FlowDIS: Language-Guided Dichotomous Image Segmentation with Flow Matching
 - **Authors:** Andranik Sargsyan, Shant Navasardyan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate image segmentation is essential for modern computer vision applications such as image editing, autonomous driving, and medical image analysis. In recent years, Dichotomous Image Segmentation (DIS) has become a standard task for training and evaluating highly accurate segmentation models. Existing DIS approaches often fail to preserve fine-grained details or fully capture the semantic structure of the foreground. To address these challenges, we present FlowDIS, a novel dichotomous image segmentation method built on the flow matching framework, which learns a time-dependent vector field to transport the image distribution to the corresponding mask distribution, optionally conditioned on a text prompt. Moreover, with our Position-Aware Instance Pairing (PAIP) training strategy, FlowDIS offers strong controllability through text prompts, enabling precise, pixel-level object segmentation. Extensive experiments demonstrate that our method significantly outperforms state-of-the-art approaches both with and without language guidance. Compared with the best prior DIS method, FlowDIS achieves a 5.5% higher $F_{\beta}^{\omega}$ measure and 43% lower MAE ($\mathcal{M}$) on the DIS-TE test set. The code is available at: this https URL
