# Showing new listings for Monday, 11 May 2026
## Keyword: SLAM
### Title:
          AERO-VIS: Asynchronous Event-based Real-time Onboard Visual-Inertial SLAM
 - **Authors:** Yannick Burkhardt, Sebastián Barbas Laina, Simon Boche, Leonard Freißmuth, Stefan Leutenegger
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The robustness of event cameras to high dynamic range and motion blur holds the potential to improve visual odometry systems in challenging environments. Although their high temporal resolution does not require synchronous processing, most event-based odometry methods still run at fixed rates, which simplifies system design but restricts latency and throughput. In this work, we present AERO-VIS, a stereo event-inertial SLAM system with an integrated, data-driven, robust, and performance-optimized keypoint detector. By processing the event stream asynchronously, the system dynamically adapts to downstream runtime demands, ensuring low-latency and real-time performance. When deploying AERO-VIS on a UAV, we achieve unprecedented accuracy in onboard event-based SLAM. These unique characteristics enable us to present the first purely event-based inertial SLAM system that demonstrates closed-loop UAV control and large-scale state estimation while relying solely on onboard compute. A video of the experiments and the source code are available at this http URL.
## Keyword: odometry
### Title:
          PathPainter: Transferring the Generalization Ability of Image Generation Models to Embodied Navigation
 - **Authors:** Yijin Wang, Yuru Tian, Xijie Huang, Weiqi Gai, Mo Zhu, Xin Zhou, Yuze Wu, Fei Gao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bird's-eye-view (BEV) images have been widely demonstrated to provide valuable prior information for navigation. Given the global information provided by such views, two key challenges remain: how to fully exploit this information and how to reliably use it during execution. In this paper, we propose a navigation system that uses BEV images as global priors and is designed for ground and near-ground robotic platforms. The system employs an image generation model to interpret human intent from natural language, identify the target destination, and generate traversability masks. During execution, we introduce cross-view localization to align the robot's odometry with the BEV map and mitigate long-term drift in conventional odometry. We conduct extensive benchmark experiments to evaluate the proposed method and further validate it on a UAV platform. Using only a conventional local motion planner, the UAV successfully completes a 160-meter outdoor long-range navigation task. This work demonstrates how the world-understanding capabilities of foundation models can be transferred to embodied navigation, enabling robots to benefit from the strong generalization ability of existing image generation models.
### Title:
          AERO-VIS: Asynchronous Event-based Real-time Onboard Visual-Inertial SLAM
 - **Authors:** Yannick Burkhardt, Sebastián Barbas Laina, Simon Boche, Leonard Freißmuth, Stefan Leutenegger
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The robustness of event cameras to high dynamic range and motion blur holds the potential to improve visual odometry systems in challenging environments. Although their high temporal resolution does not require synchronous processing, most event-based odometry methods still run at fixed rates, which simplifies system design but restricts latency and throughput. In this work, we present AERO-VIS, a stereo event-inertial SLAM system with an integrated, data-driven, robust, and performance-optimized keypoint detector. By processing the event stream asynchronously, the system dynamically adapts to downstream runtime demands, ensuring low-latency and real-time performance. When deploying AERO-VIS on a UAV, we achieve unprecedented accuracy in onboard event-based SLAM. These unique characteristics enable us to present the first purely event-based inertial SLAM system that demonstrates closed-loop UAV control and large-scale state estimation while relying solely on onboard compute. A video of the experiments and the source code are available at this http URL.
### Title:
          Rebalancing gradient to improve self-supervised co-training of depth, odometry and optical flow predictions
 - **Authors:** Marwane Hariat, Antoine Manzanera, David Filliat
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present CoopNet, an approach that improves the cooperation of co-trained networks by dynamically adapting the apportionment of gradient, to ensure equitable learning progress. It is applied to motion-aware self-supervised prediction of depth maps, by introducing a new hybrid loss, based on a distribution model of photo-metric reconstruction errors made by, on the one hand the depth + odometry paired networks, and on the other hand the optical flow network. This model essentially assumes that the pixels from moving objects (that must be discarded for training depth and odometry), correspond to those where the two reconstructions strongly disagree. We justify this model by theoretical considerations and experimental evidences. A comparative evaluation on KITTI and CityScapes datasets shows that CoopNet improves or is comparable to the state-of-the-art in depth, odometry and optical flow predictions.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Dr-BA: Separable Optimization for Direct Radar Bundle Adjustment & Localization
 - **Authors:** Daniil Lisus, Cedric Le Gentil, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces Dr-BA, a first-of-its-kind radar bundle adjustment (BA) framework that operates directly on 2D spinning radar intensity images. Unlike camera or lidar sensors, radar is largely unaffected by precipitation, making it a critical modality for autonomous systems that require all-weather robustness. Existing state estimation approaches using spinning radar typically extract sparse point clouds from range-azimuth-intensity measurements and apply point cloud alignment techniques to estimate vehicle motion, scene structure, or to localize within an existing map. In contrast, Dr-BA uses the full radar returns from multiple scans to jointly estimate dense maps and sensor poses. By formulating the problem as a separable optimization, we derive an efficient and general solution that decouples pose estimation from mapping. In addition to solving the BA problem, this formulation naturally extends to direct radar-only localization (DRL) within a previously built map. Dr-BA achieves state-of-the-art radar-based BA and cross-session localization performance, demonstrated on more than 200 km of on-road data across five distinct routes. Our implementation is publicly available at this https URL.
### Title:
          Palm-sized Omnidirectional Vision-Based UAV Exploration with Sparse Topological Map Guidance
 - **Authors:** Zirui Wang, Xinjia Luo, Haotian Sun, Jun Ma, Jian Guo, Boyu Zhou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Classic exploration methods often rely on dense occupancy maps or high-resolution point clouds for frontier detection and path planning, resulting in substantial memory consumption and computational overhead. Moreover, micro UAVs under size, weight, and power (SWaP) constraints are not practical to be equipped with sensors like LiDAR to obtain accurate environmental geometric measurements. This paper presents a lightweight autonomous exploration system that leverages omnidirectional vision and sparse topological map guidance. Specifically, we utilize a multi-fisheye camera setup to achieve omnidirectional Field of View (FoV) and perform depth estimation. To address the limited depth estimation accuracy, frontiers are represented as potential unexplored regions characterized by topological nodes instead of explicit boundaries, enabling efficient identification of frontier regions without maintaining occupancy grids or global point clouds. Unlike classic dense representations, our approach abstracts the environment using a sparse topological map composed of key nodes and their descriptors, reducing memory consumption and computational demands. Global path planning is performed directly on the sparse graph. The proposed method is validated in both simulation and on a palm-sized vision-based UAV with an 11 cm wheelbase and a 400 g weight in real-world experiments, demonstrating that our method can achieve efficient exploration with extremely low computational consumption.
### Title:
          GEM: Generating LiDAR World Model via Deformable Mamba
 - **Authors:** Yang Wu, Zhaojiang Liu, Qiang Meng, Youquan Liu, Renliang Weng, Jianjun Qian, Jian Yang, Jin Xie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models, which simulate environmental dynamics and generate sensor observations, are gaining increasing attention in autonomous driving. However, progress in LiDAR-based world models has lagged behind those built on camera videos or occupancy data, primarily due to two core challenges: the inherent disorder of LiDAR point clouds and the difficulty of distinguishing dynamic objects from static structures. To address these issues, we propose GEM: a Generative LiDAR world model that leverages deformable mamba architecture, significantly improving fidelity and imaginative capability. Specifically, leveraging the structural similarity between sequential laser scanning and Mamba's processing mechanism, we first tokenize LiDAR sweeps into compact representations via a custom LiDAR scene tokenizer. After unsupervised disentanglement of tokenized features via a dynamic-static separator, a tri-path deformable Mamba is introduced to perform selective scanning and adaptive gating fusion over the disentangled features, leading to enhanced spatial-temporal understanding of the world evolution. Optionally, a planner and a BEV layout controller can be integrated to explore the model's capability for autonomous rollout and its potential to generate ``what-if" scenarios. Extensive experiments show that GEM achieves state-of-the-art performances across diverse benchmarks and evaluation settings, demonstrating its superiority and effectiveness. Project page: this https URL.
### Title:
          UniD-Shift: Towards Unified Semantic Segmentation via Interpretable Share-Private Multimodal Decomposition
 - **Authors:** Shuai Zhang, Zhecheng Shi, Zhuxiao Li, Jing Ou, Tengxi Wang, Yuan Liu, Wufan Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic segmentation of large-scale 3D point clouds is crucial for applications such as autonomous driving and urban digital twins. However, the sparse sampling pattern of LiDAR and the view-dependent geometric distortion in image observations complicate cross-modal alignment and hinder stable fusion. Inspired by the fact that 2D images captured by cameras are representations of the 3D world, we recognize that the features learned from 2D and 3D segmentation share some common semantics, while other aspects remain modality-specific. This insight motivates a unified multimodal framework for joint 2D-3D semantic segmentation. We combine a SAM-based vision encoder with a SPTNet-based geometric encoder to extract complementary semantic and geometric representations. The resulting features from both modalities are explicitly decomposed into shared and private subspaces, where the shared components summarize semantic factors common to both domains, and the private components preserve properties that are unique to each modality. A lightweight attention-based fusion module aggregates the shared features into a consistent cross-modal representation, and a regularized training objective ensures both semantic alignment and subspace independence. Experiments on the SemanticKITTI and nuScenes benchmarks demonstrate consistent improvements in segmentation accuracy over representative multimodal baselines, accompanied by competitive computational efficiency. Cross-domain evaluation on nuScenes USA-Singapore shows stable performance under distribution shifts, demonstrating strong generalization. The implementation code is publicly available at: this https URL.
### Title:
          Weather-Robust Scene Semantics with Vision-Aligned 4D Radar
 - **Authors:** Kali Hamilton, Christoffer Heckman
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cameras and LiDAR degrade in rain, fog, and snow, while millimeter-wave radar remains largely unaffected. We align a radar encoder to frozen SigLIP vision embeddings and decode structured scene captions through a frozen vision-language model (VLM) with approximately 7M trainable parameters. On K-RADAR with held-out fog, light snow, and heavy snow sequences, all radar configurations outperform a camera baseline that collapses to over 90% hallucination. We identify a token-norm mismatch as the dominant failure mode when bridging radar to a frozen VLM and show that projector-output LayerNorm resolves it. Analysis of encoder complexity, caption format, and pooling strategy reveals tradeoffs that inform future radar-VLM pipeline design.
### Title:
          MORPH-U: Multi-Objective Resilient Motion Planning for V2X-Enabled Autonomous Driving in High-Uncertainty Environments via Simulation
 - **Authors:** Shih-Yu Lai
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 V2X can warn an autonomous vehicle about hazards beyond line-of-sight, but it also brings uncertainty: messages may be delayed, dropped, or even forged. Meanwhile, map knowledge may change during a trip, forcing the vehicle to replan under tight real-time budgets. This paper studies how to make motion planning and low-level control robust to such uncertain, event-driven updates. We present MORPH-U, a CARLA-based closed-loop stack that fuses LiDAR/radar/camera with V2X (CAM/DENM) into a Local Dynamic Map (LDM) and triggers Hybrid-A* replanning when validated hazards or map changes affect the planned route. We expose the planning/control trade-offs via a multi-objective formulation over tracking error, safety margin (minimum TTC), responsiveness, and smoothness, and select operating points using Pareto-frontier analysis. To avoid unsafe replanning from faulty V2X triggers, MORPH-U adds a lightweight Byzantine-inspired acceptance gate that combines a quorum rule with an on-board sensor veto. Experiments in dynamic CARLA scenarios show that V2X-augmented LDM improves downstream safety, Pareto tuning provides controllable accuracy-comfort trade-offs, and the gate prevents replanning under saturated false-DENM injection ($p_{\text{attack}}=1.0$).
### Title:
          Tracking Large-scale Shared Bikes with Inertial Motion Learning in GNSS Blocked Environments
 - **Authors:** Feng Liu (1), Kejia Li (1), Zhiwei Yang (2), Chunwei Yang (2), Qun Li (2), Guobin Wu (2), Qiang Ni (3), Ruipeng Gao (1) ((1) Beijing Jiaotong University, (2) DiDi Company, (3) Lancaster University)
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although Global Navigation Satellite Systems (GNSS) provide a general solution for bike tracking outdoors, there still exist complex riding environments where only inertial navigation systems work, such as urban canyons. Despite decades of research, localization using only low-cost inertial sensors still faces challenges such as cumulative drifts and poor robustness caused by filtering methods. Furthermore, sensors such as visual and LiDAR could provide reliable measurements, but they are not suitable for large-scale deployment. In this paper, we propose an inertial tracking framework that integrates bicycle mechanical constraints with a mixture-of-experts model. Specifically, we leverage multiple expert modules to capture shared representations and weight them through the gating mechanism, thus improving multi-task learning performance and enabling uncertainty-aware trajectory estimation. Furthermore, based on the mechanical transmission between the pedal and the rear wheel of a bike, we explore the intrinsic relationship between the rider's periodic pedalling behaviors and acceleration variations, and convert such patterns into bike's wheel speed for dynamic calibration. Experiments with real-world riding data from shared bikes of the DiDi ride-hailing platform demonstrate that our system improves the accuracy of baselines by at least 12%, with wheel speed errors below 0.5 m/s at 95-percentile.
### Title:
          Offline-Online Hierarchical 3D Global Relocalization With Synthetic LiDAR Sensing and Descriptor-Space Retrieval
 - **Authors:** Jiahua Ren, Kai Shen, Muhua Zhang, Lei Ma
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D global relocalization is one of the key capabilities for mobile robots in practical applications. However, in large scale spaces, existing methods often suffer from prolonged online relocalization time due to factors such as the massive pose search space and high computational overhead. To address these issues, this paper proposes an offline-online hierarchical framework that decouples the search space. In the offline phase, candidate positions and their corresponding geometric descriptor indices are generated in the map by simulating LiDAR scans within the grid map. In the online phase, a coarse pose estimate is first obtained via global retrieval, followed by point cloud registration to output precise 6-DoF pose estimates. Real-world experiments demonstrate that the proposed method achieves an average relocalization time of 3 s and an average localization accuracy of 8 cm in 3D environments. Compared with existing global relocalization methods, the proposed method achieves an order-of-magnitude improvement in computational efficiency while delivering comparable relocalization accuracy.
### Title:
          123D: Unifying Multi-Modal Autonomous Driving Data at Scale
 - **Authors:** Daniel Dauner, Valentin Charraut, Bastian Berle, Tianyu Li, Long Nguyen, Jiabao Wang, Changhui Jing, Maximilian Igl, Holger Caesar, Boris Ivanovic, Yiyi Liao, Andreas Geiger, Kashyap Chitta
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The pursuit of autonomous driving has produced one of the richest sensor data collections in all of robotics. However, its scale and diversity remain largely untapped. Each dataset adopts different 2D and 3D modalities, such as cameras, lidar, ego states, annotations, traffic lights, and HD maps, with different rates and synchronization schemes. They come in fragmented formats requiring complex dependencies that cannot natively coexist in the same development environment. Further, major inconsistencies in annotation conventions prevent training or measuring generalization across multiple datasets. We present 123D, an open-source framework that unifies such multi-modal driving data through a single API. To handle synchronization, we store each modality as an independent timestamped event stream with no prescribed rate, enabling synchronous or asynchronous access across arbitrary datasets. Using 123D, we consolidate eight real-world driving datasets spanning 3,300 hours and 90,000 kilometers, together with a synthetic dataset with configurable collection scripts, and provide tools for data analysis and visualization. We conduct a systematic study comparing annotation statistics and assessing each dataset's pose and calibration accuracy. Further, we showcase two applications 123D enables: cross-dataset 3D object detection transfer and reinforcement learning for planning, and offer recommendations for future directions. Code and documentation are available at this https URL.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          AdpSplit: Error-Driven Adaptive Splitting for Faster Geometry Discovery in 3D Gaussian Splatting
 - **Authors:** Yongjae Lee, Jingxing Li, Abhay Kumar Yadav, Rama Chellappa, Deliang Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive density control in 3D Gaussian Splatting (3DGS) repeatedly grows the Gaussian population through fixed-cardinality random splitting to discover useful scene structure. However, in vanilla 3DGS, its binary split operator requires many densification rounds to expose fine details, making it a bottleneck for efficient training schedules with fewer iterations. We introduce AdpSplit, an error-driven adaptive split operator that determines the number of split children and initializes the child parameters from L1-pixel-error region statistics, enabling fewer densification iterations, thus reduced training time, while preserving the rendering quality of full-schedule training. Across the MipNeRF360, Deep-Blending, and Tanks&Temples datasets, AdpSplit reduces the training time of multiple accelerated 3DGS pipelines by 9.2%-22.3% as a simple drop-in replacement for the standard split operator. With FastGS, AdpSplit matches the full-schedule PSNR on MipNeRF360 while reducing training time by 16.4%, corresponding to a 12.6x acceleration over vanilla 3DGS.
### Title:
          AsyncEvGS: Asynchronous Event-Assisted Gaussian Splatting for Handheld Motion-Blurred Scenes
 - **Authors:** Jun Dai, Renbiao Jin, Bo Xu, Yutian Chen, Linning Xu, Mulin Yu, Tianfan Xue, Shi Guo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D reconstruction methods such as 3D Gaussian Splatting (3DGS) and Neural Radiance Fields (NeRF) achieve impressive photorealism but fail when input images suffer from severe motion blur. While event cameras provide high-temporal-resolution motion cues, existing event-assisted approaches rely on low-resolution sensors and strict synchronization, limiting their practicality for handheld 3D capture on common devices, such as smartphones. We introduce a flexible, high-resolution asynchronous RGB-Event dual-camera system and a corresponding reconstruction framework. Our approach first reconstructs sharp images from the event data and then employs a cross-domain pose estimation module based on the Visual Geometry Transformer (VGGT) to obtain robust initialization for 3DGS. During optimization, we employ a structure-driven event loss and view-specific consistency regularizers to mitigate the ill-posed behavior of traditional event losses and deblurring losses, ensuring both stable and high-fidelity reconstruction. We further contribute AsyncEv-Deblur, a new high-resolution RGB-Event dataset captured with our asynchronous system. Experiments demonstrate that our method achieves state-of-the-art performance on both our challenging dataset and existing benchmarks, substantially improving reconstruction robustness under severe motion blur. Project page: this https URL
### Title:
          High-Fidelity Surface Splatting-Based 3D Reconstruction from Multi-View Images
 - **Authors:** Nandhana Sunil, Abhirami R Iyer, Avirup Mandal
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-view mesh reconstruction remains a core challenge in computer graphics and vision, especially for recovering high-frequency geometry from sparse observations. Recent methods such as 3D Gaussian Splatting (3DGS) and Neural Radiance Fields (NeRF) rely on post-processing for mesh extraction, thereby limiting joint optimization of geometry and appearance. Implicit Moving Least Squares (IMLS) instead enables direct conversion of point clouds into signed distance and texture fields, supporting end-to-end reconstruction and rendering. However, existing IMLS formulations use exponential kernels that struggle with high-frequency detail. We introduce a compact polynomial kernel with local support and greater flexibility, allowing better control over frequency content and improved geometric fidelity. To further enhance fine details, we incorporate stochastic regularization with Laplacian filtering. Together, these improve the preservation of high-frequency structure while maintaining stable optimization. Experiments show state-of-the-art performance in both surface reconstruction and rendering, yielding more accurate geometry and sharper visuals from multi-view data.
## Keyword: mapping
### Title:
          Semantic State Abstraction Interfaces for LLM-Augmented Portfolio Decisions: Multi-Axis News Decomposition and RL Diagnostics
 - **Authors:** Likhita Yerra (1), Remi Uttejitha Allam (1) ((1) AIVANCITY School of AI and Data)
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Semantic State Abstraction Interfaces (SSAI): a methodological template for mapping sparse unstructured text into $K$ auditable, named coordinates with neutral defaults on no-news days, designed to separate representation hypotheses from optimisation variance in sequential decision systems. Our contribution is the framework and its evaluation protocol, not a claim that SSAI outperforms denser alternatives. We instantiate SSAI with $K=4$ axes (sentiment, risk, confidence, volatility forecast) on a US-equity panel (30 NASDAQ-100 names, FNSPID news, 2019--2023 test), and evaluate it across direct factor portfolios, supervised ridge forecasters, and RL agents (DP-PPO, SAC) that share the same fixed $\phi$. The four-factor factor portfolio reaches 307.2% cumulative return and Sharpe 1.067, but apparent gains versus buy-and-hold (243.6%) fail coverage-stratified controls, reverse at $\geq 0.2$% costs, and are statistically fragile versus a sentiment-only baseline; a PC1 composite and a FinBERT portfolio baseline are stronger ranking signals in this setting. Ridge and RL blocks diagnose representation versus optimiser effects. We position SSAI as an interpretability-performance diagnostic and reusable protocol for sparse-text decision systems.
### Title:
          Benchmarked Yet Not Measured -- Generative AI Should be Evaluated Against Real-World Utility
 - **Authors:** Ishani Mondal, Shweta Bhardwaj
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative AI systems achieve impressive performance on standard benchmarks yet fail to deliver real-world utility, a disconnect we identify across 28 deployment cases spanning education, healthcare, software engineering, and law. We argue that this benchmark utility gap arises from three recurring failures in evaluation practice: proxy displacement, temporal collapse, and distributional concealment. Motivated by these observations, we argue that generative AI evaluation requires a paradigm shift from static benchmark-centered transparency toward stakeholder, goal, and context-conditioned utility transparency grounded in human outcome trajectories. Existing evaluations primarily characterize properties of model outputs, while deployment success depends on whether interaction with AI improves stakeholders' ability to achieve their goals over time. The missing construct is therefore utility: the change in a stakeholder's capability induced through sustained interaction with an AI system within a deployment context. To operationalize this perspective, we propose SCU-GenEval, a four-stage evaluation framework consisting of stakeholder-goal mapping, construct-indicator specification, mechanism modeling, and longitudinal utility measurement. To make these stages practically deployable, we introduce three supporting instruments: structured deployment protocols, context-conditioned user simulators, and persona- and goal-conditioned proxy metrics. We conclude with domain-specific calls to action, arguing that progress in generative AI must be evaluated through measurable improvements in human outcomes rather than benchmark performance alone.
### Title:
          Zombies in Alternate Realities: The Afterlife of Domain Names in DNS Integrations
 - **Authors:** Sulyab Thottungal Valapu, John Heidemann, Mattijs Jonker, Raffaele Sommese
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 DNS integrations leverage the discovery, trust, and uniqueness of the global Domain Name System with a linkage to another naming ecosystem, so the DNS name can help identify resources such as a cryptocurrency wallet or software component. While DNS ownership is verified at linkage creation, many ecosystems do not track subsequent DNS changes. The result is zombie linkages, where the DNS ownership has expired or changed, but the mapping to the linked resource persists. We define a threat model for DNS integrations, identifying five classes of attacks that leverage or exploit zombie linkages. We measure zombie occurrence across three DNS integrations -- Web PKI; ENS, a blockchain naming system; and Maven Central, a Java software repository. We show that zombies exist in every ecosystem, but at very different fractions -- zombies make up roughly 3% of TLS certificates for new domains, 24% of ENS on-chain imports, and 15% of Maven Central namespaces. We evaluate how integration design choices affect outcomes, with validate-once integrations (ENS on-chain, Maven Central) accumulating long-lasting zombies, linkages with expiration (Web PKI) limiting damage, while integrations that validate on every use (ENS gasless) are zombie-free by design. We look for specific attacks, finding attacks actively available for exploitation in both Web PKI and Maven Central. Finally, we recommend steps to reduce zombie occurrence.
### Title:
          Why Does Agentic Safety Fail to Generalize Across Tasks?
 - **Authors:** Yonatan Slutzky, Yotam Alexander, Tomer Slor, Yoav Nagel, Nadav Cohen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI agents are increasingly deployed in multi-task settings, where the task to perform is specified at test time, and the agent must generalize to unseen tasks. A major concern in such settings is safety: often, an agent must not only execute unseen tasks, but do so while avoiding risks and handling ones that materialize. Empirical evidence suggests that even when the ability to execute generalizes to unseen tasks, the ability to do so safely frequently does not. This paper provides theory and experiments indicating that failures of agentic safety to generalize across tasks are not merely due to limitations of training methods, but reflect an inherent property of safety itself: the relationship between a task and its safe execution is more complex than the relationship between a task and its execution alone. Theoretically, we analyze linear-quadratic control with $H_{\infty}$-robustness, and prove that the mapping from task specification to an optimal controller has higher Lipschitz constant with safety requirements than without, yielding a Lipschitz bound of independent interest. Empirically, we demonstrate our conclusions in simulated quadcopter navigation with a neural network agent and in CRM with an LLM agent. Our findings suggest that current efforts to enhance agentic safety may be insufficient, and point to a need for fundamentally different approaches.
### Title:
          Dr-BA: Separable Optimization for Direct Radar Bundle Adjustment & Localization
 - **Authors:** Daniil Lisus, Cedric Le Gentil, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces Dr-BA, a first-of-its-kind radar bundle adjustment (BA) framework that operates directly on 2D spinning radar intensity images. Unlike camera or lidar sensors, radar is largely unaffected by precipitation, making it a critical modality for autonomous systems that require all-weather robustness. Existing state estimation approaches using spinning radar typically extract sparse point clouds from range-azimuth-intensity measurements and apply point cloud alignment techniques to estimate vehicle motion, scene structure, or to localize within an existing map. In contrast, Dr-BA uses the full radar returns from multiple scans to jointly estimate dense maps and sensor poses. By formulating the problem as a separable optimization, we derive an efficient and general solution that decouples pose estimation from mapping. In addition to solving the BA problem, this formulation naturally extends to direct radar-only localization (DRL) within a previously built map. Dr-BA achieves state-of-the-art radar-based BA and cross-session localization performance, demonstrated on more than 200 km of on-road data across five distinct routes. Our implementation is publicly available at this https URL.
### Title:
          Almost Sure Convergence Rates of Stochastic Approximation and Reinforcement Learning via a Poisson-Moreau Drift
 - **Authors:** Xinyu Liu, Zixuan Xie, Shangtong Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optimization and Control (math.OC); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Establishing almost sure convergence rates for stochastic approximation and reinforcement learning under Markovian noise is a fundamental theoretical challenge. We make progress towards this challenge for a class of stochastic approximation algorithms whose expected updates are contractive, a setting that arises in many reinforcement learning algorithms such as $Q$-learning and linear temporal difference learning. Specifically, for a power-law learning rate $O(n^{-\eta})$ with $\eta \in (1/2, 1)$, we obtain an almost sure convergence rate arbitrarily close to $o(n^{1 - 2\eta})$. For a harmonic learning rate $O(n^{-1})$, we obtain an almost sure convergence rate arbitrarily close to $o(n^{-1})$, which we argue is a strong result because it is close to the optimal rate $O(n^{-1}\log\log n)$ given by the law of the iterated logarithm (for a special case of i.i.d. noise). Key to our analysis is a novel Lyapunov drift construction that applies a Poisson-equation based correction for Markovian noise to the well-established Moreau-envelope smoothing for the contractive mapping.
### Title:
          LoHGNet: Infrared Small Target Detection through Lorentz Geometric Encoding with High-Order Relation Learning
 - **Authors:** Qianwen Ma, Yang Xu, Shangwei Deng, Xiaobo Li, Haofeng Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Infrared small target detection (IRSTD) remains challenging due to the scarcity of useful target cues and the presence of severe background clutter. Most current methods rely on conventional feature learning and local interaction modeling, where features are represented in Euclidean space. However, such designs may still be limited in describing the subtle differences of weak targets and the contextual relations between targets and backgrounds. To address these limitations, we propose LoHGNet, an IRSTD network that integrates Lorentz geometric encoding with high-order relation learning. By introducing Lorentz manifold based feature learning, LoHGNet offers a different feature representation from conventional IRSTD methods and provides new discriminative cues for IRSTD. Specifically, a Lorentz encoding branch is constructed with the Geometric Attention Guided Lorentz Residual Convolution Module (GA-LRCM) to perform feature modeling under hyperbolic geometric constraints and enhance the hierarchical geometric representation capability of weak targets. Subsequently, the hyperbolic features are mapped into the Euclidean tangent space through logarithmic mapping, and a High-Order Relation Learning Module (HORL) is designed to model the high-order contextual dependencies between targets and backgrounds via hypergraph construction, thereby improving target discrimination in complex backgrounds. Experimental results on three datasets demonstrate that the proposed LoHGNet achieves competitive performance in both detection accuracy and adaptability to complex scenes. The code will be available at this https URL.
### Title:
          Sat3R: Satellite DSM Reconstruction via RPC-Aware Depth Fine-tuning
 - **Authors:** Qiaoyi Yang, Chaoyi Zhou, Xi Liu, Run Wang, Minghui Xu, Mert D. Pesé, Feng Luo, Yuhao Xu, Zhi-Qi Cheng, Qiushi Chen, Hairong Qi, Siyu Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate Digital Surface Model (DSM) reconstruction from satellite imagery is critical for applications such as disaster response, urban planning, and large-scale geographic mapping. Existing approaches face a fundamental trade-off: optimization-based methods achieve strong accuracy but require hours of per-scene computation, while generalizable geometry foundation models offer near-instant inference but fail to generalize to satellite imagery due to the domain gap introduced by the Rational Polynomial Camera (RPC) model and mismatched depth scale distributions. We present Sat3R, a feed-forward framework that bridges this gap via RPC-aware metric depth fine-tuning of Depth Anything V2 using the Scale-Invariant Logarithmic (SiLog) loss. By constructing physically consistent pseudo depth supervision from RPC geometry, Sat3R adapts a monocular depth foundation model to the satellite domain without per-scene optimization. Experiments on the DFC2019 benchmark demonstrate that Sat3R reduces MAE by 38% over zero-shot feed-forward baselines and achieves competitive accuracy against optimization-based methods, while delivering over 300x speedup. Sat3R demonstrates that feed-forward models, when properly adapted to the satellite domain, can match optimization-based accuracy at a fraction of the computational cost, paving the way for practical large-scale satellite DSM reconstruction.
### Title:
          Sparse Random-Feature Neural Networks with Krylov-Based SVD for Singularly Perturbed ODE
 - **Authors:** Kevin Kurian Thomas Vaidyan, Siddharth Rout
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Machine Learning (cs.LG); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Random-feature neural networks (RFNNs), including architectures with fixed hidden layers and analytically determined output weights, offer fast training but often suffer from issues due to dense representations of the hidden layer activation. Their reliance on dense feature mappings and least squares solvers can limit scalability and numerical stability, particularly for high-dimensional or stiff systems. Specifically, the activation matrix is observed to be low-rank and extremely ill-conditioned. In this work, we propose a sparse framework for RFNNs that integrates structured sparsity into the hidden layer activations that increases the rank and employs Sparse Singular Value Decomposition (sSVD) for solving the resulting linear least squares problem scalably and efficiently while catering to the bad condition number. We explore the theory behind Lanczos-Golub-Kahan Bidiagonalization technique for sparse SVD and conduct some experiments to identify some limitations and justify the requirement for orthogonalization step in our application. Then, we demonstrate that the proposed method maintains or improves solution accuracy for solving the benchmark one-dimensional steady convection-diffusion equations case having stronger advection, while achieving substantial gains in training efficiency and robustness compared to standard dense implementations.
### Title:
          GC-ART: Global Learnable Second-Order Rational Tone Curves for Illumination Robustness
 - **Authors:** Wei Huang, Joyce Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce GC-ART (Global Curve Adaptive Rational Tone-mapping), a lightweight differentiable pre-processing module for robust image classification. GC-ART predicts an endpoint-pinned rational tone curve from per-channel soft histograms using a 643-parameter MLP, then applies the curve pointwise before the classifier. The module is trained end-to-end with cross-entropy and a soft monotonicity penalty. On CIFAR-10 with a CIFAR-style ResNet-18, GC-ART matches clean accuracy with the unenhanced baseline and other learned enhancers, improves over the baseline on multiplicative darkening, and achieves the best learned-method result on contrast corruption (48.45% vs. 46.27% for the baseline and 47.13% for Zero-DCE++). These results suggest that histogram-conditioned rational curves can learn useful global tone corrections, including contrast-expanding behavior, while preserving edge locations by construction through pointwise mapping. GC-ART also uses substantially fewer FLOPs than convolutional learned enhancers at 32 x 32. The current hyperparameters are untuned, leaving room for systematic improvement.
### Title:
          Beyond Linear Attention: Softmax Transformers Implement In-Context Reinforcement Learning
 - **Authors:** Zixuan Xie, Xinyu Liu, Claire Chen, Shuze Daniel Liu, Rohan Chandra, Shangtong Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context reinforcement learning (ICRL) studies agents that, after pretraining, adapt to new tasks by conditioning on additional context without parameter updates. Existing theoretical analyses of ICRL largely rely on linear attention, which replaces the softmax function in the standard attention with an identity mapping. This paper provides the first theoretical understanding of ICRL without making the unrealistic linear attention simplification. In particular, we consider the standard softmax attention used in practice. We show that, with certain parameters, the layerwise forward pass of a Transformer with such softmax attention is equivalent to iterative updates of a weighted softmax temporal difference (TD) learning algorithm. Here, weighted softmax TD is a new RL algorithm that performs policy evaluation in kernel space and adopts both linear TD and tabular TD as special cases. We also prove that under a certain contraction condition, the policy evaluation error decays as the number of layers grows, with the identified parameters above. Finally, we prove that those parameters are a global minimizer of a pretraining loss, explaining their emergence in our numerical experiments.
### Title:
          Disambiguating 2D-3D Correspondences in Gaussian Splatting-based Feature Fields for Visual Localization
 - **Authors:** Miso Lee, Sangeek Hyun, Yerim Jeon, Jae-Pil Heo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Gaussian Splatting-based Feature Fields (GSFFs) have shown promise for visual localization, this paper highlights that photometrically optimized GSFFs are inherently ill-suited for 2D-3D matching. The volumetric extent of each Gaussian induces many-to-one pixel-to-point mappings that destabilize PnP-based pose estimation, while photometric optimization gives rise to superfluous Gaussians devoid of multi-view consistency. To address these issues, we propose SplitGS-Loc, a localization-specialized GSFFs construction framework that disambiguates 2D-3D correspondences by exploiting Gaussian attributes. Our key design, Mixture-of-Gaussians-based splitting, decomposes each Gaussian into smaller Gaussians, replacing ambiguous many-to-one with precise one-to-one correspondences. In parallel, we exploit composition weights from GS rasterization to select Gaussians that significantly and consistently contribute across multiple views and aggregate discriminative features through strong pixel-Gaussian associations, enforcing multi-view consistency. The resulting compact yet discriminative feature fields enable stable PnP convergence, achieving state-of-the-art performance on localization benchmarks. Extensive experiments validate that SplitGS-Loc extends the utility of photometric GSFFs to accurate and efficient localization by exploiting Gaussian attributes, without per-scene training or iterative pose refinement.
### Title:
          LoBoFit: Flexible Garment Refitting via Local Bone Mapping Blending
 - **Authors:** Meng Zhang, Yu Xin, Feiya Guo, Kaizhang Kang, Mengyu Chu, Ruizhen Hu
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Garment refitting, the task of adapting a garment from a source to a target avatar, must preserve the original design features and fine-scale wrinkles, a challenge exacerbated by significant shape variations and varying poses without registration to a shared canonical pose. Existing methods struggle to balance robustness, efficiency, and fidelity of detail: physics-based simulation is costly, data-driven approaches lack generalizability, and geometry optimization in the full vertex space is often ill-conditioned and prone to local minima with unsatisfactory quality. We identify that a fundamental limitation lies in the representation: deforming garments directly in global coordinates couples vertices non-locally, creating a complex and poorly-structured optimization landscape. Therefore, we introduce LoBoFit, a robust refitting method built upon a novel Local Bone Mapping Blending (LoBoMap Blending) representation. Instead of manipulating global vertex positions, LoBoMap Blending expresses garment geometry as a linear blend of its mappings into local bone coordinate frames. This representation is highly expressive and flexible: local bone mappings yield a pose-robust initialization and a well-conditioned parameterization, while blending weights smooth the optimization landscape and broaden the space of plausible solutions for stable convergence with fine-scale detail preservation. The subsequent refinement efficiently resolves collisions and preserves details by optimizing localized residuals, effectively decomposing the complex global deformation into manageable subproblems. Our experiments demonstrate that LoBoFit reliably refits high-resolution, single- and multi-layer garments across avatars with large shape and topological differences, while faithfully preserving intricate wrinkles and the intended fit style, outperforming state-of-the-art methods in robustness and output quality.
### Title:
          AudioFace: Language-Assisted Speech-Driven Facial Animation with Multimodal Language Models
 - **Authors:** Kai Zheng, Zejian Kang, Rui Mao, Hongyuan Zou, Yuanchen Fei, Xuanyang Xu, Xiangru Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Speech-driven facial animation requires accurate correspondence between acoustic signals and facial motion, especially for articulation-related mouth movements. However, directly mapping speech audio to facial coefficients often overlooks the linguistic and phonetic structure underlying speech production. In this paper, we propose AudioFace, a language-assisted framework for speech-driven blendshape generation that treats mouth-related facial coefficient prediction as a structured generation problem guided by linguistic and articulatory information. Instead of relying solely on acoustic features, our method leverages the prior knowledge of multimodal large language models and introduces transcript- and phoneme-level cues to bridge speech signals with interpretable facial actions. Extensive experiments show that AudioFace achieves superior performance across multiple evaluation metrics, validating the effectiveness of language-assisted and multimodal-prior-guided speech-driven facial animation.
### Title:
          Implicit Multi-Camera System Calibration Using Gaussian Processes
 - **Authors:** Ivan De Boi, Bart Ribbens, Veronika Golanova, Ursula Kapov, Simon Verspeek
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes a novel framework for implicit multi-camera system calibration utilizing Gaussian Process (GP) regression. Conventional explicit calibration methods are constrained by rigid mathematical models and struggle with complex, non-linear distortions from unconventional optics, while existing neural network-based implicit approaches are typically data-hungry and lack inherent uncertainty quantification (UQ). Our GP-based model directly learns the complex, non-linear mapping from 2D image coordinates across all cameras to a 3D world coordinate, completely bypassing time-consuming estimation of explicit intrinsic and extrinsic parameters. Moreover, the inherent UQ is critical for transforming a simple 3D point prediction into a verifiable 3D measurement, complete with statistically-sound confidence bounds. To further enhance data efficiency and practical deployment, we integrate Active Learning (AL), which intelligently leverages the GP's predictive uncertainty to strategically guide the acquisition of new calibration data. This approach results in a robust, data-efficient, and reliable calibration solution, proving particularly effective in practical scenarios where collecting extensive calibration data is a dominant constraint. Our experiments show that the uncertainty for the 3D predictions is higher closer to the cameras. The data points in $uv$-coordinate space are more sparse in that region, even though they are not in 3D space. This work is relevant for anyone who is tasked with the calibration of complex multi-camera systems.
### Title:
          TCMIIES: A Browser-Based LLM-Powered Intelligent Information Extraction System for Academic Literature
 - **Authors:** Hanqing Zhao
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The exponential growth of academic publications has created an urgent need for automated tools capable of extracting structured knowledge from unstructured scientific texts. While large language models (LLMs) have demonstrated remarkable capabilities in natural language understanding and information extraction, existing solutions often require specialized infrastructure, programming expertise, or fine-tuned domain-specific models that create barriers for researchers in specialized fields. This paper presents TCMIIES, a browser-based, zero-installation platform that leverages commercial LLM APIs to perform structured information extraction from academic literature. The system employs a novel schema-guided prompting framework with automatic system prompt generation, enabling researchers to define custom extraction schemas through an intuitive graphical interface without any programming. TCMIIES features a pure front-end architecture that ensures data privacy by processing all information locally in the browser, supports five major LLM providers, implements concurrent batch processing with automatic retry mechanisms, and provides intelligent field mapping for Chinese academic databases including CNKI and Wanfang. We demonstrate the system's effectiveness through comprehensive evaluation across multiple extraction scenarios in Traditional Chinese Medicine research, achieving structured output compliance rates exceeding 94\% and information extraction accuracy comparable to domain-expert annotation. The system represents a practical, accessible solution that bridges the gap between advanced LLM capabilities and domain-specific academic information extraction needs, particularly for researchers in specialized fields who require flexible, privacy-preserving, and cost-effective extraction tools.
### Title:
          Can LLMs Solve Science or Just Write Code? Evaluating Quantum Solver Generation
 - **Authors:** Luciano Baresi, Domenico Bianculli, Maryse Ernzer, Livia Lestingi, Fabrizio Pastore, Seung Yeob Shin
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) show strong capabilities in code generation, motivating their use in automated quantum solver development. However, in quantum computing, successful execution of generated code is not sufficient: correctness depends on numerically accurate results, which are sensitive to non-trivial mappings, hybrid quantum-classical workflows, and algorithm-specific approximations. This work introduces Q-SAGE, an iterative methodology to evaluate LLMs' capability in generating quantum solvers for scientific problems. The methodology adopts an iterative approach by executing the script generated by the LLM, comparing the result with the result of a classical solver, and refining the script until the two results match within a tolerance threshold. We empirically evaluated the methodology with five families of scientific problems of different complexities and five LLMs, both open source and proprietary. The results show that iterative refinement substantially improves success rates, but introduces a significant computational overhead. Moreover, as model capability increases, failure modes shift from execution errors to numerical inaccuracies, highlighting the current limitations of LLM-based quantum software.
### Title:
          Stencil Computations on Tenstorrent Wormhole
 - **Authors:** Lorenzo Piarulli, Daniele De Sensi
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As investment in AI-focused accelerators grows and their deployment in supercomputing facilities expands, understanding whether these architectures can efficiently support traditional scientific kernels is critical for the future of High-Performance Computing. We investigate the mapping of 2D 5-point stencil computations onto the Tenstorrent Wormhole, a RISC-V AI dataflow accelerator. We develop two heterogeneous implementations: Axpy, which decomposes the stencil into element-wise submatrix operations, and MatMul, which reformulates it as a matrix multiplication. While the CPU baseline remains 3x faster end-to-end, profiling reveals that the isolated Wormhole kernel is competitive with CPU execution, with the gap driven by PCIe transfers, device initialization, and host-side preprocessing. Despite slower runtime, Axpy achieves lower energy consumption than the CPU baseline for large inputs. Through detailed profiling and theoretical analysis, we identify key architectural and software limitations of the current platform and outline concrete hardware and software directions that could make AI accelerators competitive for HPC workloads.
### Title:
          LithoBench: Benchmarking Large Multimodal Models for Remote-Sensing Lithology Interpretation
 - **Authors:** Jun Wang, Fengpeng Li, Hang Dong, Tianjin Huang, Wei Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote sensing lithology interpretation is fundamental to geological surveys, mineral exploration, and regional geological mapping. Unlike general land-cover recognition, lithology interpretation is a knowledge-intensive task that requires experts to infer rock types from various features, e.g., subtle visual, spectral, textural, geomorphological, and contextual cues, making reliable automated interpretation highly challenging. Geological knowledge-guided large multimodal models offer new opportunities, yet their evaluation remains constrained by the lack of benchmarks that capture lithological annotations, multi-level geological semantics, and expert-informed assessment. Here, we propose LithoBench, a multi-level benchmark for evaluating geological semantic understanding in remote sensing lithology interpretation. LithoBench contains 10,000 expert-annotated interpretation instances across 12 representative lithological categories, including 4,000 multiple-choice and 6,000 open-ended tasks organized into five cognitive levels: Identification and Description, Comparative Analysis, Mechanism Explanation, Practical Application, and Comprehensive Reasoning. We further develop an expert-in-the-loop, knowledge-grounded semi-automated construction pipeline, coupling multi sub-processes, e.g., structured geological image descriptions, to enhance geological validity and evaluation reliability. Experiments with multiple large vision-language models eveal substantial limitations in geological semantic understanding, particularly on higher-order explanation, application, and reasoning tasks.
### Title:
          OphEdit: Training-Free Text-Guided Editing of Ophthalmic Surgical Videos
 - **Authors:** Ritul Jangir, Arkya Jyoti Bagchi, Aiman Farooq, Mangalton Okram, Saurabh Seetaram Korgaonkar, Deepak Mishra
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-fidelity surgical video generation can greatly improve medical training and the development of AI, adapting these generative models for precise video editing remains a formidable challenge. Modifying surgical attributes, such as instrument tissue interactions or procedural phases is challenging due to the strict anatomical and temporal constraints. In this paper, we propose OphEdit, a novel training-free framework for the text-guided editing of ophthalmic surgical videos. Our approach leverages a deterministic second-order ODE inversion pipeline to capture Attention Value (V) tensors from the original video. By selectively injecting these stored tensors into the conditional Classifier-Free Guidance (CFG) branch during the denoising phase, OphEdit rigorously preserves the intricate anatomical geometry of the eye while seamlessly mapping text-driven semantic modifications onto the video stream. Clinical evaluations demonstrates that OphEdit effectively handles complex surgical transformations, such as instrument swaps and procedural variations, with superior structural fidelity and temporal consistency compared to natural-domain video editors. Our work represents the first application of training-free video editing in the ophthalmic surgical domain, offering a scalable solution for generating diverse, annotated medical datasets without the need for exhaustive manual recording or costly model fine-tuning. The code and prompts can be accessed at this https URL
### Title:
          Accelerating Precise End-to-End Simulation: Latency-Sensitive Many-core System Modeling
 - **Authors:** Yinrong Li, Zexin Fu, Yichao Zhang, Germain Haugou, Chi Zhang, Marco Bertuletti, Bowen Wang, Luca Benini
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern large language model workloads put increasing demands on parallel compute capability and on-chip memory capacity, while also stressing fine-grained data movement and synchronization. These trends motivate exploring and designing many-core accelerators with tightly coupled scratchpad memory (SPM) for scalable compute and predictable, explicitly managed data access. However, this architectural shift raises two challenges: cycle-accurate register-transfer level (RTL) simulation becomes prohibitively slow as system complexity grows, and performance estimation requires precise modeling of latency-sensitive interconnect behavior. This paper presents a fast yet accurate end-to-end modeling approach for latency-sensitive many-core architectures, targeting large-scale instances such as TeraNoC with 1024 cores and a 4MiB globally shared L1 SPM. The approach captures timing behavior of latency-sensitive SPM accesses across multiple interconnect scales, while abstracting non-essential hardware details. Across diverse benchmarks, the model tracks a cycle-accurate RTL golden model with errors below 7%, while delivering up to 115x faster simulation. The framework also provides detailed profiling across processing elements and interconnect, enabling efficient end-to-end software development and hardware design exploration. Two case studies demonstrate its practicality: profiling-guided optimization of FlashAttention-2 to reduce interconnect stalls and synchronization overhead, and design space exploration of network-on-chip (NoC) router remapping to alleviate traffic imbalance and improve throughput.
### Title:
          Analyzing Human Heuristics and Strategies in Everyday Decision-Making Conversations for Conversational AI Design
 - **Authors:** Sora Kang, Soyun Jeon, Jinsu Eun, Kwangwon Lee, Chaerin Song, Minyoung Joo, Joonhwan Lee
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conversational AI increasingly supports everyday decision-making, yet most systems rely on data-centric reasoning rather than the heuristic and interactional strategies people use in natural conversation. To ground design in actual human practice, we analyze 955 real-world Korean conversations (15,476 utterances) involving food and travel decisions, applying a decision-making codebook through an LLM-assisted coding pipeline. Our findings reveal that people prioritize satisficing over optimization, relying heavily on internal knowledge and interactional strategies to manage cognitive load. Critically, we identify a frequency-efficiency mismatch: the most prevalent heuristics sustain conversational flow during exploration, whereas infrequent, rule-based strategies are highly effective at driving resolution during exploitation. By mapping how these patterns transfer across the spectrum of human-AI interaction, this work provides empirical grounding consistent with cognitive theories of decision-making and offers design implications that align AI systems with human heuristic processes.
### Title:
          Hybrid TF--IDF Logistic Regression and MLP Neural Baseline for Indonesian Three-Class Sentiment Analysis on Social Media Text
 - **Authors:** Allya Nurul Islami Pasha, Eka Fidiya Putri, Luluk Muthoharoh, Ardika Satria, Martin C.T. Manullang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a compact three-class sentiment analysis study for Indonesian social media text. The task is formulated with positive, negative, and neutral outputs derived from a fine-grained emotion dataset. The proposed practical baseline combines TF--IDF text features, three lightweight numeric metadata features, and a balanced multinomial Logistic Regression classifier. For comparison, the study also includes a neural baseline using a two-layer multilayer perceptron (MLP) over the same hybrid feature representation. The dataset originally contains 732 rows and 191 fine-grained emotion labels; after cleaning, deduplication, and label remapping, 707 samples remain with an imbalanced distribution of 459 positive, 188 negative, and 60 neutral instances. Experimental results show that the Logistic Regression deployment model reaches 0.8028 accuracy, 0.8003 weighted F1, and 0.7276 macro F1, while project documentation reports a higher-accuracy but non-production MLP baseline. These findings indicate that careful preprocessing, interpretable feature engineering, and class balancing remain competitive for small Indonesian sentiment datasets, whereas the neural baseline is better treated as a comparative experiment than as the default deployment model.
### Title:
          Physics-Inspired Probabilistic Computing for Extremely Large-Scale MIMO Detection in Future 6G Wireless Systems
 - **Authors:** Andrea Grimaldi, Christian Duffee, Eleonora Raimondo, Edoardo Piccolo, Deborah Volpe, Filip B. Maciejewski, Mario Carpentieri, Massimo Chiappini, Pedram Khalili Amiri, Davide Venturelli, Giovanni Finocchio
 - **Subjects:** Subjects:
Information Theory (cs.IT); Other Condensed Matter (cond-mat.other)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Extremely large-scale multiple-input multiple-output (XL-MIMO) architectures are a key enabler of forthcoming 6G wireless communication networks by allowing high data rates through massive spatial multiplexing. Here, we approach these problems with physics-inspired unconventional computing based on Ising machines (IMs). For binary modulation, probabilistic IMs (PIMs) and oscillator-based IMs achieve optimal ML detection with systems up to 2048x2048 antennas with only 100 iterations, matching optimal sphere decoder performance for computationally treatable sizes and outperforming the minimum mean-square error (MMSE) industrial standard. For M-QAM up to 256, a generalized PIM-inspired framework, based on d-dimensional probabilistic variables (p-dits) that directly encode QAM symbols, shows low bit-error-rate across sizes up to 256x256 antennas, outperforming or matching MMSE with reduced algorithmic complexity. Unlike the binary mapping, the p-dit interaction matrix is independent of the QAM order, enabling adaptive MIMO modulation. These results show a promising scalable paradigm for XL MIMO detection in future 6G networks.
### Title:
          Adaptive Regularization for Sparsity Control in Bregman-Based Optimizers
 - **Authors:** Ahmad Aloradi, Tim Roith, Emanuël A. P. Habets, Daniel Tenbrinck
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse training reduces the memory and computational costs of deep neural networks. However, sparse optimization methods, e.g., those adding an $\ell_1$ penalty, often control sparsity only indirectly through a regularization parameter $\lambda$, whose mapping to the final sparsity rate is non-trivial. In our experiments, we found this parameter sensitivity to be particularly pronounced for Bregman-based optimizers. Specifically, the two variants LinBreg and AdaBreg reach the same sparsity at $\lambda$ values that differ by up to two orders of magnitude, requiring expensive trial-and-error sweeps to achieve a user-specified sparsity. To address this, we propose an adaptive regularization scheme that updates $\lambda$ based on the difference between the model's current sparsity and the target sparsity. We analyze the resulting algorithm and evaluate it on automatic speaker verification with ECAPA-TDNN and ResNet34 on VoxCeleb and CNCeleb. The proposed method reliably achieves sparsity targets ranging between 75% and 99%. It also converges faster than the oracle-tuned non-adaptive baseline during early training and matches or surpasses its final performance in equal error rate. We further show that the adaptive scheme inherits key properties from its non-adaptive counterpart, including improved out-of-distribution robustness over the dense baselines.
### Title:
          Tree SAE: Learning Hierarchical Feature Structures in Sparse Autoencoders
 - **Authors:** Tue M. Cao, Hoang X. Nhat, Raed Alharbi, My T. Thai
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning hierarchical features in Sparse Autoencoders (SAEs) is essential for capturing the structured nature of real-world data and mitigating issues like feature absorption or splitting. Existing works attempt to identify hierarchical relationships within independent feature sets by relying on activation coverage, the assumption that child feature should only activate when its parent feature activates. However, we demonstrate that this condition alone is insufficient; that is, it often produces false positives where parent and child concepts are semantically unrelated. To address this, we introduce a novel reconstruction condition that enforces a deeper functional link between hierarchical levels. By combining both activation and reconstruction constraints, we propose the Tree SAE, a model designed to learn hierarchical structures directly from within the feature set. Our results demonstrate that Tree SAEs significantly surpass the existing SAEs at learning hierarchical pairs while maintaining competitive performance to the state-of-the-art on several key benchmarks. Finally, we demonstrate the practical utility of our Tree SAE in mapping the geometry of child feature subspaces and uncovering the complex hierarchical concept structures encoded within large language models.
### Title:
          Stencil Computations on Cerebras Wafer-Scale Engine
 - **Authors:** Elia Belli, Daniele De Sensi
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Computational Engineering, Finance, and Science (cs.CE); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Stencil computations are a fundamental kernel in scientific computing, critical for simulations in domains such as fluid dynamics and climate modeling. However, these computations are often memory-bound on traditional High-Performance Computing architectures like GPUs, struggling against the "Memory Wall". Simultaneously, the rise of AI-oriented hardware, such as the Cerebras Wafer-Scale Engine, offers massive core parallelism and high-bandwidth on-chip memory, though typically optimized for lower-precision workloads. This work investigates the viability of bridging this divergence by mapping stencil algorithms onto the Cerebras WSE-3. The study introduces CStencil, a novel framework designed to implement two-dimensional stencil computations on the WSE-3. To ensure a rigorous and fair performance evaluation, the research also adapts ConvStencil, a state-of-the-art GPU stencil solver, porting it from its original double-precision design to single-precision for execution on an NVIDIA A100 GPU. Experimental results show that the WSE-3's distributed SRAM and mesh interconnect effectively eliminate the off-chip memory bottlenecks common in GPU implementations. CStencil achieves speedups of up to 342x over the adapted ConvStencil version. A roofline model analysis further confirms that CStencil saturates the available compute and memory resources, demonstrating that the WSE dataflow architecture can be successfully repurposed for traditional scientific algorithms. These findings highlight the potential of the WSE-3 to deliver hardware utilization levels unattainable on conventional systems, offering a promising path toward overcoming the memory limitations of current HPC architectures.
### Title:
          Zero-Shot Imagined Speech Decoding via Imagined-to-Listened MEG Mapping
 - **Authors:** Maryam Maghsoudi, Shihab Shamma
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decoding imagined speech from non-invasive brain recordings is challenging because imagined datasets are scarce and difficult to align temporally across subjects and sessions In this work, we propose a new approach to the decoding of imagined speech that leverages the richer and more reliably labeled recordings during listening to speech. We collected paired listened and imagined MEG recordings to rhythmic melodic and spoken stimuli from trained musicians. Using trained musicians helped improve temporal alignment across conditions. We then developed a three-stage decoding pipeline that revealed consistent and meaningful relationships between neural activity evoked by imagining and listening to the same stimuli. First, we trained six linear and neural models to map imagined MEG responses to listened responses. We evaluated these models against a null baseline from unseen subjects to validate that the predicted-listening responses preserve stimulus-specific information. In the second stage, we trained a contrastive word decoder exclusively on the listened MEG responses, and evaluated it using four embedding strategies including semantic, acoustic, and phonetic representations. In the third stage, we process the imagined MEG responses from held-out subjects through the mapping pipeline to compute the corresponding listening responses that are then decoded by the listened decoder. Using rank-based analysis, we show that the imagined words are decodable significantly above chance. We shall report here the results of a proof-of-concept implementation to decode imagined speech, where all evaluations are performed on held-out subjects. We also demonstrate that performance improves with training data size, suggesting that this approach is scalable and can directly be made applicable to realistic brain-computer interface scenarios.
## Keyword: localization
### Title:
          An Aerial Manipulator for Perception-Driven Flower Targeting Toward Contactless Pollination in Vertical Farming
 - **Authors:** Chenzhe Jin, Zhuohang Wu, Yifan Cai, Xiangqi Li, Jan Ming Kevin Tan, Narsimlu Kemsaram, Valerio Modugno
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The decline of natural pollinators has created a major challenge for crop production in controlled indoor agriculture, particularly in vertical farming environments where natural insect pollination is absent. This motivates the development of robotic systems capable of performing precise flower targeting tasks while minimizing physical interference with delicate floral structures. This paper presents an aerial manipulator platform for perception driven flower detection, localization, and approach in vertical farming environments. The proposed system integrates onboard RGBD based perception, model predictive path integral (MPPI) based unmanned aerial vehicle (UAV) control on a PX4 platform, and a lightweight 2DoF manipulator for precise end effector positioning. The platform is evaluated in both MuJoCo simulation and UAV lab experiments using a flower targeting testbed. The experimental results demonstrate stable UAV flight, reliable flower localization, and centimeter level end effector positioning accuracy. In simulation, the proposed controller achieves consistent trajectory convergence and accurate target alignment. In the real world UAV lab environment, the integrated perception control manipulation framework enables stable flower targeted positioning and end effector alignment under constrained aerial operation. These results validate the proposed aerial manipulator as a robust robotic carrier and positioning framework for future contactless pollination systems. While the current study focuses on perception guided targeting and positioning, the developed platform provides a practical foundation for integrating advanced contactless end effectors, including acoustic based pollen manipulation modules, in future work.
### Title:
          PLOT: Progressive Localization via Optimal Transport in Neural Causal Abstraction
 - **Authors:** Jonathn Chang, Arya Datla, Ziv Goldfeld
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Causal abstraction offers a principled framework for mechanistic interpretability, aligning a high-level causal model with the low-level computation realized by a neural network through counterfactual intervention analysis. Existing methods such as distributed alignment search (DAS) learn expressive subspace interventions, but the relevant neural site is unknown a priori, so finding a handle requires a computationally burdensome search over candidate sites. We introduce PLOT (Progressive Localization via Optimal Transport), a transport-based framework that localizes causal variables from the output effect geometry of abstract and neural interventions. PLOT fits an optimal transport coupling between abstract variables and candidate neural sites, yielding a global soft correspondence that can be calibrated into intervention handles. In simple settings, a single coupling over individual neurons suffices. In larger models, PLOT is applied progressively, moving from coarse sites such as tokens, timesteps, or layers to finer supports such as coordinate groups or PCA spans, and optionally guiding DAS based on the localized signal. Across experiments of increasing complexity, transport-only PLOT handles are exceedingly fast and competitive on accuracy, while PLOT-guided DAS reaches DAS-level accuracy at a fraction of full DAS runtime, providing an efficient localization engine for causal abstraction research at scale.
### Title:
          Self Driving Datasets: From 20 Million Papers to Nuanced Biomedical Knowledge at Scale
 - **Authors:** Haydn Jones, Yimeng Zeng, Alden Rose, Li S. Yifei, Yining Huang, Kaiwen Wu, Jiaming Liang, Maggie Ziyu Huan, Yoseph Barash, Cesar de la Fuente-Nunez, Osbert Bastani, Zachary Ives, Mark Yatskar, Jacob R. Gardner
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Manually curated biomedical repositories -- spanning bioactivity, genomics, and chemistry -- are expensive to maintain, lag behind primary literature, and discard experimental context, obscuring nuances needed to assess data correctness and coverage. We show that PubMed itself can be autonomously and cost-effectively turned into structured datasets that are larger, more nuanced, and more accurate than the curated databases they replace. We present three coupled contributions: (1) an LLM-based entity-tagging pipeline, grounded in nine biomedical ontologies, that tags 4.5B entities across 19 categories in a 22.5M-paper, 2.5T-token PubMed corpus; (2) hybrid sparse-dense retrieval supporting entity-filtered semantic queries over the tagged corpus; and (3) Starling, a multi-agent deep research system that, given only a natural-language task description, designs precision- and recall-targeted retrieval filters, induces an extraction schema, and emits structured records with nuance-rich fields and supporting passages. Across six tasks -- blood-brain barrier permeability, oral bioavailability, acute toxicity (LD50), gene-disease associations, protein subcellular localization, and chemical reactions -- Starling produces ~6.3M records (91K-3M per task); several are, to our knowledge, the largest public datasets for their property. Frontier-model rejection of our extractions is 0.6-7.7% across tasks, far below error rates we measure on widely used curated counterparts (e.g., 16.5% on BBB_Martins, 7.3% on Bioavailability_Ma). Beyond scale and accuracy, the supporting passages carry nuance tabular databases discard -- e.g., oral bioavailability may depend on fed vs. fasted state. Together, the corpus, retrieval, and agent establish a foundation for AI-driven therapeutic design. Code and datasets: this https URL.
### Title:
          Dr-BA: Separable Optimization for Direct Radar Bundle Adjustment & Localization
 - **Authors:** Daniil Lisus, Cedric Le Gentil, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces Dr-BA, a first-of-its-kind radar bundle adjustment (BA) framework that operates directly on 2D spinning radar intensity images. Unlike camera or lidar sensors, radar is largely unaffected by precipitation, making it a critical modality for autonomous systems that require all-weather robustness. Existing state estimation approaches using spinning radar typically extract sparse point clouds from range-azimuth-intensity measurements and apply point cloud alignment techniques to estimate vehicle motion, scene structure, or to localize within an existing map. In contrast, Dr-BA uses the full radar returns from multiple scans to jointly estimate dense maps and sensor poses. By formulating the problem as a separable optimization, we derive an efficient and general solution that decouples pose estimation from mapping. In addition to solving the BA problem, this formulation naturally extends to direct radar-only localization (DRL) within a previously built map. Dr-BA achieves state-of-the-art radar-based BA and cross-session localization performance, demonstrated on more than 200 km of on-road data across five distinct routes. Our implementation is publicly available at this https URL.
### Title:
          InfoGeo: Information-Theoretic Object-Centric Learning for Cross-View Generalizable UAV Geo-Localization
 - **Authors:** Hongyang Zhang, Maonnan Wang, Ziyao Wang, Hongrui Yin, Man OnPun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view geo-localization (CVGL) is fundamental for precise localization and navigation in GPS-denied environments, aiming to match ground or UAV imagery with satellite views. While existing approaches rely on global feature alignment, they often suffer from substantial domain shifts induced by varying regional textures and weather conditions. This issue becomes even more pronounced in UAV-based scenarios, where the broader perspective inevitably introduces dense, fine-grained objects, creating significant visual clutter. To address this, we draw inspiration from Object-Centric Learning (OCL) and propose InfoGeo, an information-theoretic framework designed to enhance robustness and generalization. InfoGeo reformulates the optimization as an information bottleneck process with two core objectives: (i) maximizing view-invariant information by aligning the object-centric structural relations across views, and (ii) minimizing view-specific noisy signals through cross-view knowledge constraints. Extensive evaluations across diverse benchmarks and challenging scenarios demonstrate that InfoGeo significantly outperforms state-of-the-art methods.
### Title:
          Conformal-Style Quantile Analyses for Stochastic Bandits
 - **Authors:** Chengyu Du, Mengfan Xu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Stochastic bandit algorithms are usually analyzed under a mean-reward criterion, yet many problems favor arms with strong upper-tail performance, which we study herein. For a fixed miscoverage level \(\alpha\), the natural upper-tail target of arm \(j\) is the upper endpoint \(F_j^{-1}(1-\alpha/2)\) of a central prediction interval. This target can rank arms differently from their means, creating a central mismatch with the classical bandit objective. To this end, we propose ACP-UCB1, a conformal-style policy that combines an adaptive conformal estimate of the upper endpoint with a UCB-type optimism bonus. The technical challenge is that the conformity scores used by ACP-UCB1 are recomputed from evolving empirical quantile estimates and evaluated at an adaptive level. We control this endpoint through reward-quantile concentration, a perturbation argument for recomputed score quantiles, and deterministic localization of the adaptive level. ACP-UCB1 achieves logarithmic upper-quantile regret with per-arm contribution \(O(\nicefrac{\log n}{\Delta_j^{\mathrm{ACP}}})\). We also provide metric-specific regret decompositions comparing ACP-UCB1 with UCB1 and use numerical experiments to validate performance and improvement.
### Title:
          AGA3DNet: Anatomy-Guided Gaussian Priors with Multi-view xLSTM for 3D Brain MRI Subtype Classification
 - **Authors:** Peiyu Duan, Xueqi Guo, Sepehr Farhand, Mehmet Berk Sahin, Xinyuan Zheng, James S. Duncan, Gerardo Hermosillo Valadez, Yoshihisa Shinagawa
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D brain MRI subtype classification benefits from both localized anatomical cues and long-range contextual reasoning. We present AGA3DNet, a report-grounded framework that incorporates brief anatomical phrases extracted from radiology reports as a soft anatomical prior channel and fuses it with a lightweight 3D CNN and multi-view xLSTM aggregation. Specifically, extracted anatomical phrases are mapped to atlas-defined regions and converted into smooth spatial priors using a signed-distance transform followed by Gaussian weighting, providing interpretable, anatomy-grounded guidance without requiring dense voxel annotations. We evaluate AGA3DNet on a retrospective institutional brain MRI cohort for abnormal subtype discrimination and compare against reproducible 3D classification baselines. AGA3DNet achieves improved overall balance across performance metrics and supports clinically interpretable localization through the prior channel. We discuss limitations related to single-cohort evaluation and the lack of large-scale public brain MRI datasets paired with radiology reports under broadly usable terms.
### Title:
          Learning Multi-Relational Graph Representations for DNA Methylation-Based Biological Age Estimation
 - **Authors:** Qing Qing, Xikun Zhang, Zhongyuan Zhang, Jiarui Liu, Xingtong Yu, Xiaotao Shen, Ziqi Xu, Qixin Zhang, Zhe Wang, Renqiang Luo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Aging clocks aim to estimate biological age, a measure of physiological state distinct from chronological age, from observable biomarkers, and are widely used for health assessment and disease analysis. DNA methylation is a particularly informative biomarker due to its stability and strong association with aging, and recent learning-based approaches have improved predictive performance. However, most existing methods treat CpG sites as independent features, overlooking the complex and heterogeneous biological relationships among them. We propose RelAge-GNN, a multi-relational graph neural network framework for DNA methylation-based age prediction. Our method constructs three complementary graphs capturing co-methylation patterns, genomic co-localization, and gene-level associations among CpG sites. Each graph is modeled by an independent GNN branch, and a learnable gating mechanism adaptively fuses the resulting representations. Experiments on large-scale datasets show that RelAge-GNN achieves competitive accuracy and stronger correlation with chronological age compared to state-of-the-art methods. Moreover, the model exhibits improved sensitivity in detecting age acceleration across diverse disease cohorts, highlighting its potential utility for disease characterization. Finally, through post hoc interpretability analyses, we quantify the contributions of different relational structures and CpG sites, providing biologically meaningful insights and suggesting potential directions for aging-related research. Our code is available at: this https URL.
### Title:
          Towards multi-modal forgery representation learning for AI-generated video detection and localization
 - **Authors:** Dat Le, Khoa Nguyen, Xin Wang, Shu Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in generative AI have democratized video creation at scale. AI-generated videos, including partially manipulated clips across visual and audio channels, pose escalating risks of semantic distortion and misuse, which motivates the need for reliable detection tools. Most existing AI-generated video detectors remain limited by single- or partial-modality of data modeling and the lack of fine-grained temporal forgery localization. To address these challenges, our primary novelty introduces a core architecture that jointly integrates an LMM semantic branch with a spatio-temporal (ST) visual branch and a multi-scale partial-spoof (PS) audio branch. This multi-modal approach enables simultaneous detection and fine-grained temporal localization of partially manipulated AI-generated video forgeries. Extensive experiments show that this approach outperforms existing state-of-the-art methods.
### Title:
          RCoT-Seg: Reinforced Chain-of-Thought for Video Reasoning and Segmentation
 - **Authors:** Junwei Wen, Deshui Miao, Guangming Lu, Xin Li, Wenjie Pei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video Reasoning Segmentation (VRS) aims to segment target objects in videos based on implicit instructions that convey human intent and temporal logic. Existing MLLM-based methods predict masks with a [SEG] token after selecting frames via simple sampling or an auxiliary MLLM, where limited supervision and frame-language similarity rules often yield narrow-scope keyframe choices that weaken holistic temporal understanding and lead to brittle localization in complex multi-object scenes. To address these issues, we introduce RCoT-Seg, a video-of-thought framework that factorizes VRS into temporal video reasoning (TVR) and keyframe target perception (KTP), explicitly separating temporal reasoning from spatial perception. Specifically, in the TVR stage, an agentic keyframe selection module, initialized with a curated CoT-start corpus and refined by GRPO under task-aligned rewards, is proposed to generate and reselect the keyframe through self-evaluation, strengthening moment localization and temporal reasoning. In the KTP stage, RCoT-Seg performs high-resolution segmentation on the selected frame and propagates masks with SAM2-based methods across the sequence, replacing heuristic sampling and external selectors while improving spatial precision and inter-frame consistency. Extensive experimental results demonstrate that the proposed RCoT-Seg achieves favorable performance against the state-of-the-art methods. The code and models will be publicly released at this https URL.
### Title:
          Disambiguating 2D-3D Correspondences in Gaussian Splatting-based Feature Fields for Visual Localization
 - **Authors:** Miso Lee, Sangeek Hyun, Yerim Jeon, Jae-Pil Heo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Gaussian Splatting-based Feature Fields (GSFFs) have shown promise for visual localization, this paper highlights that photometrically optimized GSFFs are inherently ill-suited for 2D-3D matching. The volumetric extent of each Gaussian induces many-to-one pixel-to-point mappings that destabilize PnP-based pose estimation, while photometric optimization gives rise to superfluous Gaussians devoid of multi-view consistency. To address these issues, we propose SplitGS-Loc, a localization-specialized GSFFs construction framework that disambiguates 2D-3D correspondences by exploiting Gaussian attributes. Our key design, Mixture-of-Gaussians-based splitting, decomposes each Gaussian into smaller Gaussians, replacing ambiguous many-to-one with precise one-to-one correspondences. In parallel, we exploit composition weights from GS rasterization to select Gaussians that significantly and consistently contribute across multiple views and aggregate discriminative features through strong pixel-Gaussian associations, enforcing multi-view consistency. The resulting compact yet discriminative feature fields enable stable PnP convergence, achieving state-of-the-art performance on localization benchmarks. Extensive experiments validate that SplitGS-Loc extends the utility of photometric GSFFs to accurate and efficient localization by exploiting Gaussian attributes, without per-scene training or iterative pose refinement.
### Title:
          RELO: Reinforcement Learning to Localize for Visual Object Tracking
 - **Authors:** Xin Chen, Chuanyu Sun, Jiao Xu, Houwen Peng, Dong Wang, Huchuan Lu, Kede Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conventional visual object trackers localize targets using handcrafted spatial priors, often in the form of heatmaps. Such priors provide only surrogate supervision and are poorly aligned with tracking optimization and evaluation metrics, such as intersection over union (IoU) and area under the success curve (AUC). Here, we introduce RELO, a REinforcement-learning-to-LOcalize method for visual object tracking that formulates target localization as a Markov decision process. Specifically, RELO replaces handcrafted spatial priors with a localization policy learned over spatial positions via reinforcement learning, with rewards combining frame-level IoU and sequence-level AUC. We additionally introduce layer-aligned temporal token propagation to improve semantic consistency across frames, with negligible computational overhead. Across multiple benchmarks, RELO achieves superior results, attaining 57.5% AUC on LaSOText without template updates. This confirms that reward-driven localization provides an effective alternative to prior-driven localization for visual object tracking.
### Title:
          Tracking Large-scale Shared Bikes with Inertial Motion Learning in GNSS Blocked Environments
 - **Authors:** Feng Liu (1), Kejia Li (1), Zhiwei Yang (2), Chunwei Yang (2), Qun Li (2), Guobin Wu (2), Qiang Ni (3), Ruipeng Gao (1) ((1) Beijing Jiaotong University, (2) DiDi Company, (3) Lancaster University)
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although Global Navigation Satellite Systems (GNSS) provide a general solution for bike tracking outdoors, there still exist complex riding environments where only inertial navigation systems work, such as urban canyons. Despite decades of research, localization using only low-cost inertial sensors still faces challenges such as cumulative drifts and poor robustness caused by filtering methods. Furthermore, sensors such as visual and LiDAR could provide reliable measurements, but they are not suitable for large-scale deployment. In this paper, we propose an inertial tracking framework that integrates bicycle mechanical constraints with a mixture-of-experts model. Specifically, we leverage multiple expert modules to capture shared representations and weight them through the gating mechanism, thus improving multi-task learning performance and enabling uncertainty-aware trajectory estimation. Furthermore, based on the mechanical transmission between the pedal and the rear wheel of a bike, we explore the intrinsic relationship between the rider's periodic pedalling behaviors and acceleration variations, and convert such patterns into bike's wheel speed for dynamic calibration. Experiments with real-world riding data from shared bikes of the DiDi ride-hailing platform demonstrate that our system improves the accuracy of baselines by at least 12%, with wheel speed errors below 0.5 m/s at 95-percentile.
### Title:
          ChartREG++: Towards Benchmarking and Improving Chart Referring Expression Grounding under Diverse referring clues and Multi-Target Referring
 - **Authors:** Tianhao Niu, Ziyu Han, Qingfu Zhu, Wanxiang Che
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Referring expression grounding is a core problem in visual grounding and is widely used as a diagnostic of spatial grounding and reasoning in vision and language models, yet most prior work focuses on natural images. In contrast, existing chart referring expression grounding-related benchmarks remain limited: (1) they largely adopt bounding boxes, constraining localization precision for fine chart elements (2) they mostly assume a single and two referred target instances, failing to handle multi-instance target references; (3) the language expressions over-rely on textual cues or data-rank clues (4) they cover only a narrow range of chart types. To address these issues, we introduce a chart referring expression grounding benchmark that systematically supports multiple localization forms, multiple referred targets, diverse grounding cues and diverse chart types. Results across representative multimodal large models reveal a significant performance gap. We further introduce a code-driven synthesis pipeline that exploits the inherent alignment between plotting programs and rendered chart primitives to derive pixel accurate instance masks across chart element types and granularities. We train an instance segmentation model with the synthesized masks and integrate it into a general-purpose multimodal grounding framework. The resulting system consistently outperforms baselines on our benchmark and generalizes well to a ChartQA-derived real-chart grounding benchmark.
### Title:
          EditRefiner: A Human-Aligned Agentic Framework for Image Editing Refinement
 - **Authors:** Zitong Xu, Huiyu Duan, Yifei Nie, Mingda Du, Sijing Wu, Xiongkuo Min, Tianyi Zheng, Jian Zhang, Shusong Xu, Jinwei Chen, Bo Li, Guangtao Zhai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent text-guided image editing (TIE) models have made remarkable progress, yet edited images still frequently suffer from fine-grained issues such as unnatural objects, lighting mismatch, and unexpected changes. Existing refinement approaches either rely on costly iterative regeneration or employ vision-language models (VLMs) with weak spatial grounding, often resulting in semantic drift and unreliable local corrections. To address these limitations, we first construct EditFHF-15K, a dataset of fine-grained human feedback for edited images, comprising (1) 15K images from 12 TIE models spanning 43 editing tasks, (2) 60K annotated artifact regions and 80K editing failure regions, each accompanied by textual reasoning, and (3) 45K mean opinion scores (MOSs) assessing perceptual quality, instruction following, and visual consistency. Based on EditFHF-15K, we propose EditRefiner, a hierarchical, interpretable, and human-aligned agentic framework that reformulates post-editing correction as a human-like perception-reasoning-action-evaluation loop. Specifically, we introduce: (1) a perception agent that detects contextual saliency maps of artifacts and editing failures, (2) a reasoning agent that interprets these perceptual cues to perform human-aligned diagnostic inference, (3) an action agent that uses the reasoning output to plan and execute localized re-editing, and (4) an evaluation agent that assesses the re-edited image and guides the action agent on whether further refinements are required. Extensive experiments demonstrate that EditRefiner consistently outperforms state-of-the-art methods in distortion localization, diagnose accuracy and human perception alignment, establishing a new paradigm for self-corrective and perceptually reliable image editing. The code is available at this https URL.
### Title:
          PathPainter: Transferring the Generalization Ability of Image Generation Models to Embodied Navigation
 - **Authors:** Yijin Wang, Yuru Tian, Xijie Huang, Weiqi Gai, Mo Zhu, Xin Zhou, Yuze Wu, Fei Gao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bird's-eye-view (BEV) images have been widely demonstrated to provide valuable prior information for navigation. Given the global information provided by such views, two key challenges remain: how to fully exploit this information and how to reliably use it during execution. In this paper, we propose a navigation system that uses BEV images as global priors and is designed for ground and near-ground robotic platforms. The system employs an image generation model to interpret human intent from natural language, identify the target destination, and generate traversability masks. During execution, we introduce cross-view localization to align the robot's odometry with the BEV map and mitigate long-term drift in conventional odometry. We conduct extensive benchmark experiments to evaluate the proposed method and further validate it on a UAV platform. Using only a conventional local motion planner, the UAV successfully completes a 160-meter outdoor long-range navigation task. This work demonstrates how the world-understanding capabilities of foundation models can be transferred to embodied navigation, enabling robots to benefit from the strong generalization ability of existing image generation models.
### Title:
          Search-based Robustness Testing of Laptop Refurbishing Robotic Software
 - **Authors:** Erblin Isaku, Hassan Sartaj, Shaukat Ali, Malaika Din Hashmi, Francois Picard
 - **Subjects:** Subjects:
Robotics (cs.RO); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Danish Technological Institute (DTI) focuses on transferring advanced technologies (including robots) to the industry and the public sector. One key application is laptop refurbishment using specialized robots, aimed at promoting reuse, reducing electronic waste, and supporting the European Circular Economy Action Plan. The software of such robots often includes features that use object detection models to detect objects for various purposes, such as identifying screws for laptop disassembly or detecting stickers to remove them. Ensuring the robustness of such models to small input variations remains a critical challenge, and addressing it is important to avoid potential damage to laptops during refurbishment. In this paper, we propose PROBE, a search-based robustness testing approach that leverages multi-objective optimization to identify minimal, localized perturbations that expose failures in object detection models used in the software of laptop refurbishing robots. PROBE employs NSGA-II to systematically explore the perturbation space, optimizing for failure induction considering both localization and confidence, and perturbation magnitude, while enabling the discovery of diverse failure cases. Results show that PROBE is 3$\times$ to 7$\times$ more effective than random search in generating failure-inducing perturbations, while requiring smaller perturbation magnitudes, and that the generated perturbations transfer across models. We further show that metamorphic relations provide additional insights into model robustness, enabling the assessment of stability even in non-failing cases.
### Title:
          Offline-Online Hierarchical 3D Global Relocalization With Synthetic LiDAR Sensing and Descriptor-Space Retrieval
 - **Authors:** Jiahua Ren, Kai Shen, Muhua Zhang, Lei Ma
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D global relocalization is one of the key capabilities for mobile robots in practical applications. However, in large scale spaces, existing methods often suffer from prolonged online relocalization time due to factors such as the massive pose search space and high computational overhead. To address these issues, this paper proposes an offline-online hierarchical framework that decouples the search space. In the offline phase, candidate positions and their corresponding geometric descriptor indices are generated in the map by simulating LiDAR scans within the grid map. In the online phase, a coarse pose estimate is first obtained via global retrieval, followed by point cloud registration to output precise 6-DoF pose estimates. Real-world experiments demonstrate that the proposed method achieves an average relocalization time of 3 s and an average localization accuracy of 8 cm in 3D environments. Compared with existing global relocalization methods, the proposed method achieves an order-of-magnitude improvement in computational efficiency while delivering comparable relocalization accuracy.
### Title:
          Similar Pattern Annotation via Retrieval Knowledge for LLM-Based Test Code Fault Localization
 - **Authors:** Golnaz Gharachorlu, Mahsa Panahandeh, Lionel C. Briand, Ruifeng Gao, Ruiyuan Wan
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Software failures remain a major challenge in modern software development, and identifying the code elements responsible for failures is a time-consuming debugging task. While extensive research has focused on fault localization in the system under test (SUT), failures can also originate from faulty system test scripts. This problem, known as Test Code Fault Localization (TCFL), has received significantly less attention despite its importance in continuous integration (CI) environments where large test suites are executed frequently. TCFL is particularly challenging because it typically operates under black-box conditions, relies on limited diagnostic signals such as error messages and partial logs, and involves large system-level test scripts that expand the fault localization search space. In this paper, we propose SPARK, a framework that integrates accumulated debugging knowledge from continuous integration (CI) environments into Large Language Model (LLM)-based TCFL. Given a newly observed failing test case, SPARK retrieves similar fault-labeled test cases from a debugging knowledge corpus and selectively annotates suspicious lines of the failing test based on their similarity to previously observed fault patterns. These annotations guide the LLM's reasoning while maintaining scalability and avoiding the prompt-length explosion common to naive retrieval-augmented approaches. We evaluate SPARK on three industrial datasets containing real-world faulty Python test cases from different software products. The results show that SPARK consistently improves fault localization effectiveness compared to the existing LLM-based TCFL baseline while maintaining comparable inference cost and token usage. In particular, the approach advances the state of the art by identifying more correct faulty locations in complex test cases containing multiple faults.
### Title:
          Seeing Across Skies and Streets: Feedforward 3D Reconstruction from Satellite, Drone, and Ground Images
 - **Authors:** Qiwei Wang, Zhongyao Tuo, Xianghui Ze, Yujiao Shi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view localization classically asks: where does this ground image lie on the satellite tile? Existing methods are typically limited to 3-DoF estimates -- an $(x,y)$ position and a yaw angle -- because nadir satellite imagery provides no direct cues for roll, pitch, or altitude, forcing a reliance on planar-motion and zero-tilt assumptions. These assumptions break on real terrain with slopes, ramps, and tilted camera mounts. To overcome this, we introduce a single UAV image as an intermediate viewpoint: it reveals the 3D structure invisible from nadir, supplies the cues for roll, pitch, and altitude that the satellite alone cannot provide, and needs only spatial overlap with the ground camera -- no known relative pose is required. Building on this insight, we propose **Cross3R**, a flexible feed-forward model that ingests a satellite tile together with a UAV image, a ground image, or both, and, in a single forward pass, recovers a cross-view 3D point cloud, the 6-DoF poses of every input camera, and the on-tile $(x,y)$ position and yaw of each perspective camera. For training and evaluation, we also construct **CrossGeo**, a 278K-image tri-view dataset spanning 85 scenes across every continent except Antarctica. On CrossGeo, Cross3R consistently outperforms feed-forward 3D baselines in point-cloud reconstruction, 6-DoF camera-pose estimation, and cross-view localization. On KITTI, it outperforms dedicated cross-view methods trained on KITTI on most metrics, despite having no KITTI training itself.
### Title:
          GRAPHLCP: Structure-Aware Localized Conformal Prediction on Graphs
 - **Authors:** Peyman Baghershahi, Fangxin Wang, Debmalya Mandal, Sourav Medya
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conformal prediction (CP) provides a distribution-free approach to uncertainty quantification with finite-sample guarantees. However, applying CP to graph neural networks (GNNs) remains challenging as the combinatorial nature of graphs often leads to insufficiently certain predictions and indiscriminative embeddings. Existing methods primarily rely on embedding-space proximity for localization, which can be unreliable for graphs and yield inefficient prediction sets. We propose GRAPHLCP, a proximity-based localized CP framework that explicitly incorporates graph topology and inter-node dependencies into localization and weighting. Our approach introduces a feature-aware densification step to mitigate locality bias in sparse graphs, followed by a Personalized PageRank-based kernel computation to model structural proximity. This enables topology-dependent anchor sampling and calibration weighting that captures both local and long-range dependencies. Extensive experiments on several regression and classification datasets demonstrate that GRAPHLCP guarantees marginal coverage with finite samples while efficiently attaining favorable test conditional coverage across various conditioning scenarios.
## Keyword: transformer
### Title:
          Toeplitz MLP Mixers are Low Complexity, Information-Rich Sequence Models
 - **Authors:** Benjamin L. Badger, Ethan Roland
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based large language models are in some respects limited by the quadratic time and space computational complexity of attention. We introduce the Toeplitz MLP Mixer (TMM), a transformer-like architecture that swaps attention for triangular-masked Toeplitz matrix multiplication over the sequence dimension resulting in $\mathcal{O} (dn \log n)$ time and $\mathcal O(dn)$ space complexity during training and $\mathcal O(dn)$ time and space at inference prefill. Despite the lack of sophisticated input modulation or state maintenance present in other sub-quadratic architectures, TMMs yield greater training efficiency in terms of loss achieved per compute and device memory. We demonstrate that TMMs are capable of retaining more input information resulting in improved copying ability, which we argue results from a lack of architectural biases. Consistent with higher input information retention, TMMs exhibit superior information retrieval and in-context learning benchmark accuracy compared to comparable architectures. We conclude with an analysis from the perspective of operator index theory and show that, counterintuitively, trained Toeplitz layers of causal non-invertible models are more likely to be invertible or nearly so than models that are actually invertible over their inputs.
### Title:
          Transformer-Based Wildlife Species Classification from Daily Movement Trajectories
 - **Authors:** Obed Irakoze, Prasenjit Mitra
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inferring the identity of wildlife species from daily movement data alone is a challenging task. We train sequence models on large-scale, 7-species GPS trajectories from the Movebank platform. Trajectories models are evaluated using a protocol in which entire telemetry studies or regions are heldout during testing. We compare Transformer-based sequence models to LSTM, CNN, and Temporal Convolutional Networks, and find that Transformers consistently achieve higher balanced accuracy with gains of approximately 8 to 22 percentage points, depending on the species and experimental setting. In an elephant binary classification task with 1-hour resolution, the Transformer achieves a balanced accuracy of 0.83 and an AUC of 0.92, substantially outperforming all baseline models. We examine, under data-limited conditions, feature representations by analyzing the differences between a basic displacement-based encoding and an expanded range of movement descriptors that include speed, direction, and turning behavior. With feature augmentation, we see clear performance gains, especially for underrepresented and sparsely represented species, such as large carnivores, lions, and Zebras. Finally, experiments comparing 1-hour and 30-minutetemporal resolutions show that while finer sampling can capture short-term movement patterns for some species, a unified 1-hour resolution yields more promising performance across studies by reducing missing data and ensuring consistent temporal coverage.
### Title:
          The E$Δ$-MHC-Geo Transformer: Adaptive Geodesic Operations with Guaranteed Orthogonality
 - **Authors:** Arash Shahmansoori
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present the E$\Delta$-MHC-Geo Transformer, a novel architecture that unifies Manifold-Constrained Hyper-Connections (mHC), Deep Delta Learning (DDL), and the Cayley transform to obtain input-adaptive, unconditionally orthogonal residual connections. Unlike DDL, whose Householder operator is orthogonal only at $\beta \in \{0,2\}$, our Data-Dependent Cayley rotation $Q(x)=(I+(\beta/2)A(x))^{-1}(I-(\beta/2)A(x))$ preserves orthogonality for all $\beta$ and all inputs. To handle negation, an eigenvalue $-1$ case that Cayley provably excludes, we introduce the E$\Delta$-MHC-Geo Hybrid, which combines Cayley rotation with Householder reflection via a learned operator-selection gate $X'=\gamma(X)Q(X)X+(1-\gamma(X))H_2(X)X$. A midpoint-collapse regularizer, $4\gamma(1-\gamma)$, encourages boundary gate decisions, where each selected component is orthogonal. In matched-parameter comparisons, with approximately 1.79M parameters per model and mean +/- standard deviation over 3 seeds, against four baselines including the concurrent JPmHC, E$\Delta$-MHC-Geo achieves the best long-horizon stability, 1.9x over JPmHC and 3.8x over GPT; the best near-$\pi$ rotation loss, 4.5x over JPmHC on single-plane; strong norm preservation, with 0.001 mean deviation; and 0.96 negation cosine alignment in a diagnostic reflection probe, all with 33% fewer layers. While JPmHC's wider representation excels on pure rotation, its finite Cayley residual mixer excludes an exact $\lambda=-1$ operator and has no reflection branch, motivating our hybrid approach for accessing both connected components of $O(n)$.
### Title:
          LookWhen? Fast Video Recognition by Learning When, Where, and What to Compute
 - **Authors:** Ali Salamatian, Anthony Fuller, Pritam Sarkar, James R. Green, Leonid Sigal, Evan Shelhamer
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers dominate video recognition. They split videos into tokens, and processing them has expensive superlinear computational cost. Yet videos are filled with redundancy, so we can question the need for this expense. We introduce LookWhen, a selector-extractor framework that factorizes video recognition into learning when, where, and what to compute. Our shallow selector gets a scaled-down video and quickly scores all tokens across space-time, while our deep extractor gets the top-K selected tokens to approximate full-video representations without actually processing all the tokens. A key challenge is defining effective supervision for selection and extraction. For selection pre-training, we introduce a score on representations that ranks tokens by uniqueness using a simple nearest-neighbor distance. For extraction pre-training, we distill both a video teacher and an image teacher, for which we normalize its frame-wise representations to learn what changes within videos. Through these strategies, our selector-extractor learns general and efficient representations for feature extraction or fine-tuning to a task. Through experiments on Kinetics-400, SSv2, Epic-Kitchens, Diving48, Jester, and Charades, we show that LookWhen achieves a better accuracy-computation trade-off than efficient models and upgraded baselines of similar size. LookWhen Pareto-dominates in accuracy-FLOPs on 9 of 12 cases (6 tasks x 2 settings) and roughly matches on 3. In accuracy-throughput, measuring time in practice, LookWhen is more efficient still at 6.7x faster than InternVideo2-B at equal accuracy.
### Title:
          ProtSent: Protein Sentence Transformers
 - **Authors:** Dan Ofer, Oriel Perets, Michal Linial, Nadav Rappoport
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Protein language models (pLMs) produce per-residue representations that capture evolutionary and structural information, yet their mean-pooled sequence embeddings are not explicitly trained to reflect functional, evolutionary or structural similarity between proteins. We present Protein Sentence Transformers (ProtSent), a contrastive fine-tuning framework for adapting PLMs into general-purpose embedding models. ProtSent trains with MultipleNegativesRankingLoss across five protein-pair datasets: Pfam families, structurally derived hard negatives, AlphaFold DB structural pairs, and StringDB protein--protein interactions, and Deep Mutational Scanning data. We evaluate on 23~downstream tasks using frozen embeddings with a k-nearest-neighbor probe to measure embedding neighborhood quality. On ESM-2 150M, ProtSent improves 15 of 23 tasks, with gains of +105% on remote homology detection, +17% on variant effect prediction, and +19.9% Recall@1 on SCOPe-40 structural retrieval. The 35M variant improves 16 of 23 tasks with +40.5% on remote homology and +15.5% Recall@1 on SCOPe-40. Contrastive fine-tuning restructures the embedding space to better capture protein function and structure, without any task-specific supervision. We release the models, public data, and training recipe and code.
### Title:
          PAMPOS: Causal Transformer-based Trajectory Prediction for Attack-Agnostic Misbehavior Detection in V2X Networks
 - **Authors:** Konstantinos Kalogiannis, Ahmed Mohamed Hussain, Panos Papadimitratos
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Misbehavior detection in Vehicle-to-Everything (V2X) networks is a second line of defense against insider falsification attacks that cryptographic mechanisms alone cannot address. Existing learning-based Misbehavior Detection Schemes (MDSs) are supervised, requiring labeled attack samples at training time, thus failing to counter unseen falsification attacks. We present PAMPOS, a causal transformer-decoder trained on benign VeReMi++ trajectories to learn normal mobility patterns. At inference time, misbehavior is identified as a deviation from the model's next-step kinematic predictions using a top-K normalized anomaly scoring mechanism that localizes falsification to specific kinematic features, without requiring attack-labeled training data. We evaluate PAMPOS across all 19 attack types in VeReMi++ under rush-hour and afternoon scenarios, achieving Area Under the Curve (AUC) values of up to 0.98 and F1-scores of up to 0.95 for most attack categories.
### Title:
          Temporal Attention for Adaptive Control of Euler-Lagrange Systems with Unobservable Memory
 - **Authors:** Giansalvo Cirrincione, Adriano Fagiolini
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive control of Euler-Lagrange systems is challenging when friction is governed by a finite-horizon internal state that is not directly observable from joint measurements. In this setting, the measured closed-loop state is no longer Markovian, and standard certainty-equivalence adaptive laws may lose their convergence guarantees. The paper proposes a meta-control architecture in which the gains of a computed-torque controller are generated by a self-attention block processing a short window of recent motion history. The number of attention heads is selected before policy training through a surrogate analysis of the autocovariance of the memory-state gradient along the temporal window. This surrogate is based on a temporal adaptation of an incremental rank-tracking framework previously developed by the authors. The selected head count is then fixed and used as an architectural hyperparameter in a reinforcement-learning stage, where the policy is trained under a shielded admissibility constraint. The approach is tested on a 2-DOF manipulator with nonlinear friction and variable payload. In the short and matched memory regimes, the single-layer attention-only meta-controller outperforms a deeper Transformer baseline, with tracking-error reductions of 12 and 19 percentage points, respectively. The reported effect sizes are large, with d approximately -1.1 and -2.1, and Mann-Whitney p < 0.05 in both cases. In the long memory regime, however, the advantage disappears. Four out of ten training runs show either divergence or payload-invariant policy collapse, revealing a weakness in the static Phase-1 head-count prescription. This motivates moving rank-tracking inside the reinforcement-learning loop, allowing attention heads to be pruned or grown at runtime instead of fixed before training.
### Title:
          TajPersLexon: A Tajik-Persian Lexical Resource and Hybrid Model for Cross-Script Low-Resource NLP
 - **Authors:** Mullosharaf K. Arabov
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work introduces TajPersLexon, a curated Tajik--Persian parallel lexical resource of 40,112 word and short-phrase pairs for cross-script lexical retrieval, transliteration, and alignment in low-resource settings. We conduct a comprehensive CPU-only benchmark comparing three methodological families: (i) a lightweight hybrid pipeline, (ii) neural sequence-to-sequence models, and (iii) retrieval methods. Our evaluation establishes that the task is essentially solvable, with neural and retrieval baselines achieving 98-99% top-1 accuracy. Crucially, we demonstrate that while large multilingual sentence transformers fail on this exact lexical matching, our interpretable hybrid model offers a favorable accuracy-efficiency trade-off for practical applications, achieving 96.4% accuracy in an OCR post-correction task. All experiments use fixed random seeds for full reproducibility. The dataset, code, and models will be publicly released.
### Title:
          Not All Tokens Need 40 Steps: Heterogeneous Step Allocation in Diffusion Transformers for Efficient Video Generation
 - **Authors:** Ernie Chu, Vishal M. Patel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) have achieved state-of-the-art video generation quality, but they incur immense computational cost because standard inference applies the same number of denoising steps uniformly to every token in the sequence. It is well known that human vision ignores vast amounts of redundant motion. Why, then, do our densest models treat every spatiotemporal token with equal priority? In this paper, we introduce Heterogeneous Step Allocation (HSA), a training-free inference algorithm that assigns varying step budgets to different spatiotemporal tokens based on their velocity dynamics. To resolve the resulting sequence-length mismatch without sacrificing global context, HSA introduces a KV-cache synchronization mechanism that allows active tokens to attend to the full sequence while entirely bypassing inactive tokens. Furthermore, we derive a cached Euler update that advances the latent states of skipped tokens in a single operation without additional model evaluations. We evaluate HSA on the Wan-2 and LTX-2 models for both text-to-video (T2V) and image-to-video (I2V) generation. Our results demonstrate that HSA significantly outperforms previous state-of-the-art caching methods and the vanilla Flow Matching baseline, especially at aggressive acceleration regimes (e.g., 50% and 25% runtimes). Crucially, HSA achieves a superior quality-runtime Pareto frontier without the need for expensive offline profiling, robustly preserving structural integrity and generation quality even under tight computational budgets. Project page: this https URL
### Title:
          Tyche: One Step Flow for Efficient Probabilistic Weather Forecasting
 - **Authors:** Fan Xu, Yuan Gao, Kun Wang, Rui Su, Fenghua Ling, Hao Wu, Wanli Ouyang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Probabilistic weather forecasting requires not only accurate trajectories, but calibrated distributions over plausible atmospheric futures. Recent data-driven systems have achieved remarkable deterministic skill, and diffusion-based ensemble forecasters have substantially improved sample realism and uncertainty quantification. However, their inference cost scales with forecast horizon, ensemble size, and the number of denoising steps required for each transition, making large operational ensembles expensive. To address this, we present Tyche, a one-step conditional flow model for efficient probabilistic weather forecasting. Tyche models the conditional forecast distribution with a destination-aware average-velocity flow that maps Gaussian noise directly to future weather states in a single function evaluation (1-NFE). To make this one-step transport learnable in high-dimensional geophysical fields, we derive a JVP-regularized rectification objective that enforces temporal self-consistency across source and destination flow timesteps without explicitly forming Jacobians. The transport field is parameterized by an isotropic Swin-style transformer that preserves fine-scale spatial structure while remaining scalable on global grids. To improve ensemble reliability under autoregressive forecasting, we further introduce a rollout-based finetuning stage with curriculum CRPS calibration supervision. Experiments on ERA5 at 1.5$^\circ$ and 6-hour resolution show that our Tyche, using merely a single NFE, matches or exceeds the forecast skill and calibration of state-of-the-art multi-step generative baselines and the operational ECMWF IFS ensemble.
### Title:
          Adaptive Memory Decay for Log-Linear Attention
 - **Authors:** Yaxita Amin, Helen Zichen Li, Mengfan Zhang, Samet Ayhan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequence models face a fundamental tradeoff between memory capacity and computational efficiency. Transformers achieve expressive context modeling at quadratic cost, while linear attention and state-space models run in linear time by compressing context into a fixed-size hidden state, inherently limiting recall. Log-linear attention navigates this tradeoff by organizing memory across a Fenwick tree hierarchy, growing its hidden state logarithmically with sequence length at log-linear compute cost. However, its memory decay parameter {\lambda} is fixed and independent of the input, assigning uniform weights across all hierarchy levels regardless of the content, which introduces unnecessary rigidity. We propose learning {\lambda} directly from the input via a lightweight two-layer MLP, producing per-token, per-level decay that adapts to content rather than position. A softplus activation lets each Fenwick tree level scale independently, avoiding the inter-level competition that softmax introduces. This modification preserves log-linear complexity exactly and adds negligible parameter overhead. We evaluate on associative recall, selective copying, and language modeling, finding that input-dependent decay consistently outperforms the baseline, with the largest gains in long-range memory settings where baseline {\lambda} degrades or collapses entirely.
### Title:
          Echo: KV-Cache-Free Associative Recall with Spectral Koopman Operators
 - **Authors:** Anupama Sridhar, Alexander Johansen
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long chain-of-thought reasoning and agentic tool-calling produce traces spanning tens of thousands of tokens, yet Transformer KV caches grow linearly with sequence length, creating a memory bottleneck on commodity hardware. State-space models offer constant-memory recurrence but suffer a memory cliff: retrieval accuracy collapses once the gap between a stored fact and its query exceeds the effective horizon of the recurrent state. We introduce Echo, a KV-cache-free associative recall architecture built around Spectral Koopman Attention (SKA); a drop-in replacement for attention layers that augments SSM blocks with a closed-form dynamical operator whose sufficient statistics are accumulated in constant memory with no KV cache. Echo fits a spectral linear system to the key and value history via kernel ridge regression and retrieves through a learned power-iterated filter, all from $O(r^{2})$ streaming state where $r$ is a small projection rank. On the Multi-Query Associative Recall benchmark, a pure Mamba-2 SSM fails to exceed chance accuracy (${\sim}3\%$) across all gap lengths and KV-pair counts, while at the 50M parameter scale SKA-augmented models achieve $100\%$ retrieval accuracy on every configuration tested, including distractor gaps of $4{,}096$ tokens with $32$ KV pairs. Across five additional transfer benchmarks including needle-in-a-haystack, tool-trace, and multi-hop retrieval, SKA consistently outperforms both pure SSM and SSM+Attention hybrids while maintaining constant inference memory. Ablations confirm that the spectral operator, not the prefix masking strategy, drives the retrieval gain.
### Title:
          PolarAdamW: Disentangling Spectral Control and Schur Gauge-Equivariance in Matrix Optimisation
 - **Authors:** Haozhou Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Muon's matrix-level update couples two distinct effects: spectral control via a polar map, and equivariance under orthogonal changes of multiplicity-space basis (Schur gauge-equivariance). We separate them with PolarAdamW, a controlled hybrid that preserves Muon's polar spectral-norm control but breaks the gauge-equivariance, since AdamW's coordinatewise preconditioner is basis-dependent. Algorithmically, PolarAdamW applies Muon's Newton-Schulz polar map to AdamW's preconditioned direction rather than to raw momentum, at per-iteration wall-time comparable to Muon. We prove that Muon's polar step is Schur gauge-equivariant on multiplicity matrices while AdamW's coordinatewise step is not. On DeiT-Tiny trained from scratch on four independently sampled 100-class subsets of ImageNet-1k, where multiplicity-basis freedom is trivial, PolarAdamW outperforms Muon by +1.93 pp in test accuracy on average and AdamW by +9.5 pp; under the 300-epoch DeiT-style recipe, it remains ahead of Muon by +1.37 pp and AdamW by +5.80 pp on average. On SO(3)-equivariant 3D point-cloud regression, where multiplicity-basis freedom is non-trivial, the ordering reverses: Muon outperforms PolarAdamW at every audited capacity, and the gap widens with capacity. Both matrix-polar optimisers continue to outperform AdamW. This double dissociation separates spectral control from Schur gauge-equivariance: the first composes well with AdamW preconditioning on standard transformers, while the second becomes consequential when multiplicity-basis freedom is structurally non-trivial.
### Title:
          Self-Consolidating Language Models: Continual Knowledge Incorporation from Context
 - **Authors:** Zekun Wang, Anant Gupta, Zihan Dong, Christopher J. MacLellan
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) increasingly receive information as streams of passages, conversations, and long-context workflows. While longer context windows expose more evidence, they do not ensure that useful information is preserved and reused. We study continual context consolidation: writing current context into model weights while limiting interference with previously consolidated information. We propose \textbf{S}elf-\textbf{Co}nsolidating \textbf{L}anguage Models (SCoL), a post-training framework in which, given current context, an LLM learns to generate textual update instructions specifying which of its own Transformer layers should be updated. Because committed updates change the model that later generates future selections, we train SCoL with meta-reinforcement learning over an evolving model state. We instantiate SCoL with supervised QA rewards on SQuAD knowledge incorporation and intrinsic likelihood-based rewards for LongBench v2 long-context consolidation. Across both settings, SCoL improves acquisition and retention over prompting, summarization, batch test-time training, and sequential finetuning baselines. Analysis of learned selection patterns shows that SCoL encourages the LLM to generate sparse update locations that align with layers of high Fisher information, suggesting that the model learns to route plasticity toward loss-sensitive regions while limiting interference. Moreover, SCoL transfers from shorter meta-training streams to longer LongBench v2 streams at evaluation, suggesting that our framework supports scalable streaming consolidation.
### Title:
          CarCrashNet: A Large-Scale Dataset and Hierarchical Neural Solver for Data-Driven Structural Crash Simulation
 - **Authors:** Mohamed Elrefaie, Dule Shu, Matthew Klenk, Faez Ahmed
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Crash simulation is a cornerstone of modern vehicle development because it reduces the need for costly physical prototypes, accelerates safety-driven design iteration, and increasingly supports virtual testing workflows. At the same time, modeling structural crash mechanics remains exceptionally challenging: the response is governed by nonlinear contact, large deformation, material plasticity, failure, and complex multi-body interactions evolving over space and time on high-resolution finite-element meshes. In this work, we introduce \textsc{CarCrashNet}, a public high-fidelity open-source benchmark for data-driven structural crash simulation. \textsc{CarCrashNet} combines component-scale and full-vehicle simulations in a multi-modal format, including more than 14{,}000 bumper-beam pole-impact simulations with varying geometry, materials, and boundary conditions, together with 825 full-vehicle crash simulations built from three industry-standard vehicle models of increasing structural complexity: Dodge Neon, Toyota Yaris, and Chevrolet Silverado. To establish the reliability of the benchmark, we validate our open-source finite-element workflow based on OpenRadioss against both experimental crash data and the commercial solver Ansys LS-DYNA. We also introduce \textsc{CrashSolver}, a machine-learning model designed for full-vehicle crash prediction from high-resolution finite-element crash data. We further perform extensive benchmarking across the released datasets and evaluate \textsc{CrashSolver} against state-of-the-art geometric deep learning and transformer-based neural solvers. Our results position \textsc{CarCrashNet} as a foundation for reproducible research in structural simulation, crashworthiness modeling, and AI-driven virtual crash testing. The dataset is available at this https URL.
### Title:
          When Symbol Names Should Not Matter: A Logistic Theory of Fresh-Symbol Classification
 - **Authors:** Wenjie Guan, Jelena Bradic
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Template tasks have emerged as a clean testbed for asking whether transformers reason with abstract symbols rather than concrete token names. We study the fixed-label classification version of this problem, where train and test examples share latent templates but may use disjoint vocabularies. Unlike next-token prediction, the model need not emit unseen symbols; it must learn a decision rule invariant to symbol renaming. We analyze regularized kernel logistic classification in the transformer-kernel regime. Our main result decomposes the learned predictor into an ideal template-level classifier and a finite-sample perturbation caused by accidental token overlaps in the training data. We encode these overlaps by a colored collision graph and prove high-probability margin-transfer guarantees for fresh-symbol classification. This perspective extends template-based analyses to logistic classification and refines scalar diversity conditions: vocabulary size controls the average rate of collisions, but collision geometry controls whether the ideal classification margin is preserved. More broadly, the same perturbation framework applies to abstraction-augmented inputs, yielding a general margin-versus-collision criterion for identifying when prompting strategies improve fresh-symbol generalization. Synthetic template experiments illustrate the predicted roles of regularization, sample size, and transformer-kernel structure.
### Title:
          Convergence and Emergence of In-Context Reinforcement Learning with Chain of Thought
 - **Authors:** Zixuan Xie, Xinyu Liu, Rohan Chandra, Shangtong Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context reinforcement learning (ICRL) refers to the ability of RL agents to adapt to new tasks at inference time without parameter updates by conditioning on additional context. Recent empirical studies further demonstrate that Chain-of-Thought (CoT) generation can amplify this ICRL capability. This paper is the first to provide a theoretical understanding on how CoT interacts with ICRL. We conduct our analysis in a policy evaluation setup with linear Transformer. We prove that with specific Transformer parameters, the CoT generation process is equivalent to repeatedly executing temporal difference learning updates. Additionally, we provide finite sample convergence analysis showing that the policy evaluation error decreases geometrically with CoT length and eventually saturates at a statistical floor determined by the context length. We also prove that the desired Transformer parameters are a global minimizer of the pretraining loss, providing a theoretical understanding on the empirical emergence of those parameters.
### Title:
          Attention Transfer Is Not Universally Effective for Vision Transformers
 - **Authors:** Huaiyuan Qin, Muli Yang, Gabriel James Goenawan, Peng Hu, Chen Gong, Xi Peng, Hongyuan Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A recent work shows that Attention Transfer, which transfers only the attention patterns from a pre-trained teacher Vision Transformer (ViT) to a randomly initialized standard student ViT, is sufficient to recover the full benefit of the teacher's pre-trained weights. We revisit this finding on a comprehensive benchmark of 20 teachers from 11 well-known ViT families and reveal that Attention Transfer is not universally effective. While 7 families transfer successfully, 4 consistently fail, falling up to 5.1\% below the from-scratch no-transfer baseline. Further results demonstrate that this failure is family-consistent across model sizes, and persists under extended training durations, different transfer datasets, and out-of-distribution evaluations. Controlled analyses then consistently localize the problem to the attention-routing channel, indicating that the key issue is not whether the student can match the teacher's attention patterns, but whether the matched patterns remain functional for the student. Crucially, we identify architectural mismatch between the pre-trained teacher and the standard student as the primary mechanism. By adding only the teacher's native architectural components to the student in a randomly initialized state, we completely reverse the failure for all 4 families. Notably, these components alone do not improve from-scratch training, confirming that they specifically unlock the usability of the teacher's attention. We further systematically show that this failure is not explained by the inadequate choice of transfer loss or by differences in pre-training recipes. Our findings refine the prevailing understanding of attention in ViT representations: attention is sufficient \textit{only} when the student architecture matches the teacher.
### Title:
          AsyncEvGS: Asynchronous Event-Assisted Gaussian Splatting for Handheld Motion-Blurred Scenes
 - **Authors:** Jun Dai, Renbiao Jin, Bo Xu, Yutian Chen, Linning Xu, Mulin Yu, Tianfan Xue, Shi Guo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D reconstruction methods such as 3D Gaussian Splatting (3DGS) and Neural Radiance Fields (NeRF) achieve impressive photorealism but fail when input images suffer from severe motion blur. While event cameras provide high-temporal-resolution motion cues, existing event-assisted approaches rely on low-resolution sensors and strict synchronization, limiting their practicality for handheld 3D capture on common devices, such as smartphones. We introduce a flexible, high-resolution asynchronous RGB-Event dual-camera system and a corresponding reconstruction framework. Our approach first reconstructs sharp images from the event data and then employs a cross-domain pose estimation module based on the Visual Geometry Transformer (VGGT) to obtain robust initialization for 3DGS. During optimization, we employ a structure-driven event loss and view-specific consistency regularizers to mitigate the ill-posed behavior of traditional event losses and deblurring losses, ensuring both stable and high-fidelity reconstruction. We further contribute AsyncEv-Deblur, a new high-resolution RGB-Event dataset captured with our asynchronous system. Experiments demonstrate that our method achieves state-of-the-art performance on both our challenging dataset and existing benchmarks, substantially improving reconstruction robustness under severe motion blur. Project page: this https URL
### Title:
          Arrow: A Foundation Model for Causal Discovery
 - **Authors:** Ryan Thompson, He Zhao, Daniel M. Steinberg, Edwin V. Bonilla
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Arrow, a foundation model for zero-shot causal discovery on observational tabular data. Arrow factorizes a directed acyclic graph into an undirected skeleton and a topological order, guaranteeing acyclicity by construction. Given a new dataset, it uses a transformer-based architecture to contextualize variables within and across observations, then predicts skeleton edge probabilities and node order scores that together define a graph. Arrow is trained in a supervised fashion on synthetic datasets with ground-truth graphs, using an end-to-end differentiable directed edge composite likelihood induced by the skeleton-order factorization. The training distribution spans diverse graph families, functional forms, noise models, and dataset shapes. Across in- and out-of-distribution synthetic, semi-synthetic, and real datasets, Arrow matches or outperforms existing causal discovery methods at substantially lower inference cost than competitive alternatives. Our results demonstrate that large-scale pretraining on diverse synthetic data can yield zero-shot causal discovery models that are fast, accurate, and reusable on new datasets.
### Title:
          Hallucination Detection via Activations of Open-Weight Proxy Analyzers
 - **Authors:** Akshita Singh, Prabesh Paudel, Siddhartha Roy
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a proxy-analyzer framework for detecting hallucinations in large language models. Instead of looking inside the generating model, our system reads already-generated text through a small locally hosted open-weight model and spots hallucinations using the reader's own internal activations. This works just as well when the generator is a closed API like GPT-4 as when it is any open-weight model. We built eighteen features grounded in how transformers process text, covering residual stream norms, per-head source-document attention, entropy, MLP activations, logit-lens trajectories, and three new token-level grounding statistics. We trained a stacking ensemble on 72,135 samples from five hallucination datasets. We tested across seven analyzer architectures from 0.5 billion to 9 billion parameters: Qwen2.5 at 0.5B and 7B, Gemma-2 at 2B and 9B, Pythia at 1.4B, and LLaMA-3 at both 3B and 8B. Across all seven, we consistently beat ReDeEP's token-level AUC of 0.73 on RAGTruth by 7.4 to 10.3 percentage points. Qwen2.5-7B reached an F1 of 0.717, just above ReDeEP's 0.713, while Qwen2.5-0.5B hit 0.706. The most striking finding is how tightly all seven models cluster: AUC spans only 2.3 percentage points across an eighteen-fold difference in model size. Even more surprising, our 3B LLaMA outperforms our 8B LLaMA on RAGTruth, showing that bigger is not always better even within the same model family. Both RAGTruth and LLM-AggreFact include outputs from multiple LLM families, so our results are not skewed toward any particular generator.
### Title:
          DINO-MVR: Multi-View Readout of Frozen DINOv3 for Annotation-Efficient Medical Segmentation
 - **Authors:** Wei Jiang, Feng Liu, Nan Ye, Hongfu Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adapting foundation models to medical segmentation typically requires either backbone fine-tuning or high-capacity task-specific decoders, both of which are difficult to fit reliably when annotations are scarce. We show that frozen DINOv3 features already contain useful structural and boundary cues for medical segmentation, and that the main bottleneck lies in how these features are read out. We propose DINO-MVR, a Multi-View Readout framework for annotation-efficient medical segmentation. DINO-MVR trains only lightweight MLP probes on features from the final three transformer blocks of a frozen DINOv3 backbone, without updating the backbone itself. At inference, each input is interpreted through complementary resolutions and test-time augmentations, whose probability maps are combined by entropy-weighted fusion and refined with simple spatial regularization. For volumetric inputs, Gaussian z-axis smoothing further improves inter-slice consistency. Under fixed evaluation protocols on endoscopy, dermoscopy, and MRI benchmarks, DINO-MVR achieves strong readout-only performance, including 0.895 Dice on Kvasir-SEG, 0.897 Dice on ISIC 2018, and 0.908 Dice on BraTS FLAIR whole-tumor segmentation. With only five annotated BraTS patients, it recovers 98.4% of the performance obtained by the 40-patient BraTS reference run. These results suggest that frozen self-supervised vision backbones can support accurate medical segmentation when paired with an effective multi-view readout.
### Title:
          PersonaGest: Personalized Co-Speech Gesture Generation with Semantic-Guided Hierarchical Motion Representation
 - **Authors:** Junchuan Zhao, Qifan Liang, Ye Wang
 - **Subjects:** Subjects:
Graphics (cs.GR); Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Co-speech gesture generation aims to synthesize realistic body movements that are semantically coherent with speech and faithful to a user-specified gestural style. Existing VQ-VAE based co-speech gesture generation methods improve generation quality but fail to encode semantic structure into the motion representation or explicitly disentangle content from style, limiting both semantic coherence and personalization fidelity. We present PersonaGest, a two-stage framework addressing both limitations. In the first stage, a semantic-guided RVQ-VAE disentangles motion content and gestural style within the residual quantization structure, where a Semantic-Aware Motion Codebook (SMoC) organizes the content codebook by gesture semantics and contrastive learning further enforces content-style separation. In the second stage, a Masked Generative Transformer generates content tokens via a semantic-aware re-masking strategy, followed by a cascade of Style Residual Transformers conditioned on a reference motion prompt for style control. Extensive experiments demonstrate state-of-the-art performance on objective metrics and perceptual user studies, with strong style consistency to the reference prompt. Our project page with demo videos is available at this https URL
### Title:
          TAS-LoRA: Transformer Architecture Search with Mixture-of-LoRA Experts
 - **Authors:** Jeimin Jeon, Hyunju Lee, Bumsub Ham
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer architecture search (TAS) discovers optimal vision transformer (ViT) architectures automatically, reducing human effort to manually design ViTs. However, existing TAS methods suffer from the feature collapse problem, where subnets within a supernet fail to learn subnet-specific features, mainly due to the shared weights in a supernet, limiting the performance of individual subnets. To address this, we propose TAS-LoRA, a novel method that introduces parameter-efficient low-rank adaptation (LoRA) to enable subnet-specific feature learning, while maintaining computational efficiency. TAS-LoRA incorporates a Mixture-of-LoRAExperts (MoLE) strategy, where a lightweight router dynamically assigns LoRA experts based on subnet architectures, and introduces a group-wise router initialization technique to encourage diverse feature learning across experts early in training. Extensive experiments on ImageNet and several transfer learning benchmarks, including CIFAR-10/100, Flowers, CARS, and INAT-19, demonstrate that TAS-LoRA mitigates feature collapse effectively, improving performance over state-of-the-art TAS methods significantly.
### Title:
          Evidence-Tracked Tape Semantics for Probabilistic Computation
 - **Authors:** Liron Cohen (1), Tomer Samara (1) ((1) Ben-Gurion University of the Negev, Beer-Sheva, Israel)
 - **Subjects:** Subjects:
Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A standard intensional account of probabilistic computation represents a randomized program as a deterministic computation that consumes an explicit random tape. This yields a two-layer perspective: an intensional layer that makes reuse of randomness and correlation visible, and an extensional layer obtained by interpreting tapes under a chosen probability measure. We develop an evidence-tracked tape semantics using the monadic-core-to-evidenced-frame pipeline (and its induced realizability tripos), obtaining a higher-order logic in which entailments are witnessed by uniform evidence transformers. Quantitative statements are recovered by interpretation: once a tape measure is fixed, probabilities and expectations arise by extracting numerical summaries from tape-indexed predicates, and entailments yield sound inequalities, with an almost-sure quotient supporting probability-one reasoning. We also study intensional principles that are lost at the level of laws, including proof-relevant transport along realizable tape-rewiring maps and a canonical splitting discipline for stream tapes enforcing independent draws. Finally, we relate tape-based reasoning to an extensional law semantics via pushforward, isolating a probability-one must abstraction as a sound summary of tape-based proofs.
### Title:
          Amortized-Precision Quantization for Early-Exit Vision Transformers
 - **Authors:** Rui Fang, Hsi-Wen Chen, Ming-Syan Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) achieve strong performance across vision tasks, yet their deployment with low-precision early exiting remains fragile. Existing quantization methods assume static full-depth execution, making them unstable when exit decisions are perturbed by quantization noise, which can amplify errors along dynamic inference paths. In this paper, we introduce Amortized-Precision Quantization (APQ), a utilization-aware formulation that accounts for layer-wise stochastic exposure to quantization noise and reveals depth-precision trade-offs. Building on APQ, we propose Mutual Adaptive Quantization with Early Exiting (MAQEE), a bi-level framework that jointly optimizes exit thresholds and bit-widths under explicit risk control to improve inference stability. MAQEE establishes a superior Pareto frontier in the accuracy-efficiency trade-off, reducing BOPs by up to 95% while maintaining accuracy and outperforming strong baselines by up to 20\% across classification, detection, and segmentation tasks.
### Title:
          Activation Differences Reveal Backdoors: A Comparison of SAE Architectures
 - **Authors:** Sachin Kumar
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Backdoor attacks on language models pose a significant threat to AI safety, where models behave normally on most inputs but exhibit harmful behavior when triggered by specific patterns. Detecting such backdoors through mechanistic interpretability remains an open challenge. We investigate two sparse autoencoder architectures -- Crosscoders and Differential SAEs (Diff-SAE) -- for isolating backdoor-related features in fine-tuned models. Using a controlled SQL injection backdoor triggered by year-based context ("2024" triggers vulnerable code, "2023" triggers safe code), we evaluate both approaches across LoRA and full-rank fine-tuning regimes on SmolLM2-360M. We find that Diff-SAE consistently and substantially outperforms Crosscoders for backdoor isolation. Diff-SAE achieves a Backdoor Isolation Score (BIS) of 0.40 with perfect precision (1.0) and zero false positive rate across most experimental conditions, while Crosscoders fail almost entirely with BIS below 0.02 in most cases. This performance gap holds across multiple transformer layers (14, 18, 22, 26) and both fine-tuning regimes, with full-rank fine-tuning producing particularly clean backdoor signals. Our results suggest that backdoors manifest as directional activation shifts rather than sparse feature activations, making difference-based representations fundamentally more effective for detection. These findings have important implications for AI safety monitoring and the development of interpretability tools for detecting model manipulation.
### Title:
          Beyond Linear Attention: Softmax Transformers Implement In-Context Reinforcement Learning
 - **Authors:** Zixuan Xie, Xinyu Liu, Claire Chen, Shuze Daniel Liu, Rohan Chandra, Shangtong Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context reinforcement learning (ICRL) studies agents that, after pretraining, adapt to new tasks by conditioning on additional context without parameter updates. Existing theoretical analyses of ICRL largely rely on linear attention, which replaces the softmax function in the standard attention with an identity mapping. This paper provides the first theoretical understanding of ICRL without making the unrealistic linear attention simplification. In particular, we consider the standard softmax attention used in practice. We show that, with certain parameters, the layerwise forward pass of a Transformer with such softmax attention is equivalent to iterative updates of a weighted softmax temporal difference (TD) learning algorithm. Here, weighted softmax TD is a new RL algorithm that performs policy evaluation in kernel space and adopts both linear TD and tabular TD as special cases. We also prove that under a certain contraction condition, the policy evaluation error decays as the number of layers grows, with the identified parameters above. Finally, we prove that those parameters are a global minimizer of a pretraining loss, explaining their emergence in our numerical experiments.
### Title:
          ShellfishNet: A Domain-Specific Benchmark for Visual Recognition of Marine Molluscs
 - **Authors:** Ziheng Zhou, Yang Wang, Nan Wang, Chengliang Wu, Jun Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The decline of global shellfish biodiversity poses a severe threat to coastal ecosystems. Although artificial intelligence (AI) technologies show potential for automated ecological monitoring, existing marine benthic datasets often lack adaptation to the complexities of real underwater environments (e.g., variable lighting conditions and diverse species postures), posing challenges for the robust generalization of vision models in practical ecological monitoring. To address this problem, we construct ShellfishNet, a comprehensive image benchmark dataset designed specifically for real-world ecological monitoring constraints. Comprising 8,691 images across 32 taxa, this dataset includes a curated subset annotated with descriptive captions. It is constructed through field photography and web scraping, encompassing samples from complex real-world environments. Based on this benchmark, we systematically evaluate 80 representative neural network models, including Convolutional Neural Networks (CNNs), Vision Transformers (ViTs), State Space Models (SSMs), and Self-Supervised Learning (SSL) methods. Furthermore, we evaluate the performance of fine-grained visual categorization (FGVC) models and investigate the image captioning capabilities of several mainstream multimodal large language models (MLLMs). Meanwhile, we introduce image corruption benchmark tests to simulate common underwater degradation scenarios (turbidity, severe weather) and assess the robustness of vision models, enabling trustworthy decisions on ecological protection in the wild. ShellfishNet is dedicated to providing a data foundation and a model-evaluation benchmark for the intelligent monitoring of benthic organisms.
### Title:
          Mean-Pooled Cosine Similarity is Not Length-Invariant: Theory and Cross-Domain Evidence for a Length-Invariant Alternative
 - **Authors:** Sibayan Mitra (1), Dhruv Kumar (1) ((1) BITS Pilani)
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mean-pooled cosine similarity is the default metric for comparing neural representations across languages, modalities, and tasks. We establish that this metric is not length-invariant: under the anisotropy that characterizes modern transformer representations, mean-pooled cosine grows monotonically in sequence length, independent of representational content. Empirically, on HumanEvalPack across four code LLMs, the length ratio alone explains $R^2 = 0.52$--$0.75$ of cross-language "Python proximity," while AST depth and shared-token fraction add less than 3% of explained variance beyond length. Substituting Centered Kernel Alignment (CKA) reduces explained variance by 83% and reverses the sign of the length coefficient ($\beta_{\mathrm{len}}: +0.86 \to -0.37$). The same pattern holds in Mistral-7B on parallel WMT pairs ($R^2 = 0.23$ EN-FR, $R^2 = 0.33$ EN-DE for cosine; $R^2 < 0.01$ for CKA). In CLIP ViT-B/32, mean-pooling reduces the length effect relative to EOS-pooling ($R^2: 0.21 \to {<}0.01$), as predicted by the theory's dependence on anisotropy. We argue that length-invariant metrics such as CKA should be the default for cross-representation comparisons, and that recent claims of cross-lingual representational convergence built on mean-pooled cosine warrant re-examination.
### Title:
          Zero-Shot Neural Network Evaluation with Sample-Wise Activation Patterns
 - **Authors:** Yameng Peng, Andy Song, HaythamM. Fayek, Vic Ciesielski, Xiaojun Chang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Zero-shot proxies, also known as training-free metrics, are widely adopted to reduce the computational overhead in neural network evaluation for scenarios such as Neural Architecture Search (NAS), as they do not require any training. Existing zero-shot metrics have several limitations, including weak correlation with the true performance and poor generalisation across different networks or downstream tasks. For example, most of these metrics apply only to either convolutional neural networks (CNNs) or Transformers, but not both. To address these limitations, we propose Sample-Wise Activation Patterns (SWAP), and its derivative, SWAP-Score, a novel and highly effective zero-shot metric. SWAP-Score is broadly applicable across both architecture families and task domains, demonstrating strong predictive performance in the majority of tasks. This metric measures the expressivity of neural networks over a mini-batch of samples, showing a high correlation with the neural networks' ground-truth performance. For both CNNs and Transformers, the SWAP-Score outperforms existing zero-shot metrics across computer vision and natural language processing tasks. For instance, Spearman's correlation coefficient between the SWAP-Score and CIFAR-10 validation accuracy for DARTS CNNs is 0.93, and 0.71 for FlexiBERT Transformers on GLUE tasks. Moreover, SWAP-Score is label-independent, hence can be applied at the pre-training stage of language models to estimate their performance for downstream tasks. When applied to NAS, SWAP-empowered NAS, SWAP-NAS can achieve competitive performance using only approximately 6 and 9 minutes of GPU time, on CIFAR-10 and ImageNet respectively. Our code is available at: this https URL
### Title:
          EditTransfer++: Toward Faithful and Efficient Visual-Prompt-Guided Image Editing
 - **Authors:** Lan Chen, Qi Mao, Yiren Song, Yuchao Gu, Siwei Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual-prompt-guided edit transfer aims to learn image transformations directly from example pairs, offering more precise and controllable editing than purely text-driven approaches. However, existing diffusion transformer-based methods often fail to faithfully reproduce the demonstrated edits due to structural mismatches between the task and the backbone, including a pretrained bias toward textual conditioning and inherent stochastic instability during sampling. To bridge this gap, we present EditTransfer++, a framework that combines progressively structured training with an efficient conditioning scheme to improve both visual prompt faithfulness and inference efficiency. We first mitigate textual dominance with a text-decoupled training strategy that removes text conditioning during fine-tuning, compelling the model to infer transformations solely from visual evidence while still supporting optional text guidance at inference. On top of this visually grounded model, a best-worst contrastive refinement mechanism reshapes the denoising trajectories to suppress unfaithful generations and improve consistency across random seeds. To alleviate the computational bottleneck of high-resolution in-context editing, we further introduce a condition compression and reuse strategy that reduces token redundancy and enables efficient generation of images with a 1024-pixel long edge. Extensive experiments on existing benchmarks and the proposed EditTransfer-Bench show that EditTransfer++ achieves state-of-the-art visual prompt faithfulness with substantially faster inference than prior methods, suggesting a promising direction for scalable prompt-guided image editing and broader visual in-context learning.
### Title:
          Approximation Error Upper and Lower Bounds for Hölder Class with Transformers
 - **Authors:** Xin He, Yuling Jiao, Xiliang Lu, Jerry Zhijian Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We explore the expressive power of Transformers by establishing precise approximation error upper and lower bounds for Hölder class. Specifically, a new approximation upper bound is derived for the standard Transformer architecture equipped with Softmax operators, ReLU activation functions, and residual connections. We prove that a Transformer network composed of at most $\mathcal{O}(\varepsilon^{-{d_{0}}/{\alpha}})$ blocks can approximate any bounded Hölder function with $d_{0}$-dimensional input and smoothness $\alpha\in(0,1]$ under any accuracy $\varepsilon>0$. In the case of approximation lower bounds, leveraging the VC-dimension upper bound, we are the first to rigorously prove that Transformers demand for at least $\Omega(\varepsilon^{-{d_{0}}/({4\alpha})})$ blocks to achieve the $\varepsilon$ approximation accuracy. As a final step, we extend the derived results for standard Transformers to a general regression task and establish the corresponding excess risk rates demonstrating Transformers' empirical effectiveness in real-world settings.
### Title:
          A Unified Framework for the Detection and Classification of Fatty Pancreas in Ultrasound Images
 - **Authors:** Ioan-Tudor-Alexandru Anghel, Ciprian-Mihai Ceausescu, Elena Dana Nedelcu, Elena Raluca Stirban, Camelia Croitoru, Despina Ungureanu, Ana Maria Palan, Gabriela Pop
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Non-alcoholic fatty pancreas disease (NAFPD) is an underdiagnosed condition associated with metabolic syndrome, insulin resistance, and increased risk of pancreatic cancer. Diagnosis typically relies on subjective visual assessment of ultrasound images by clinicians. We propose an end-to-end framework for automatically classifying normal versus fatty pancreas from abdominal ultrasound images. Our method employs a TransUNet-based segmentation architecture with a ResNet encoder and transformer bottleneck to delineate the pancreas and the splenic vein, followed by anatomically-guided patch extraction and patient-level classification through pairwise texture comparison. The feature engineering mimics clinical reasoning by comparing the echogenicity of peri-venous fat to the pancreatic parenchyma, providing an interpretable signal for classification. The segmentation models are initialized via domain-specific transfer learning from a liver segmentation task. We validate the full pipeline on a clinical dataset of 214 abdominal ultrasound images with 107 expert-labeled cases using 5-fold cross-validation. SVM with RBF kernel achieves a mean cross-validated accuracy of 89.7\%\,$\pm$\,1.8\% and F1 of 0.898\,$\pm$\,0.019, while the unsupervised K-Means baseline reaches 87.8\% accuracy, demonstrating that the proposed features capture the relevant clinical signal even without labeled training data. To our knowledge, this is the first end-to-end automated framework for fatty pancreas classification from ultrasound using segmentation-guided texture analysis.
### Title:
          Transfer Learning Across Fast- and Full-Simulation Domains in High-Energy Physics
 - **Authors:** Matthias Schott, Lucie Flek
 - **Subjects:** Subjects:
Machine Learning (cs.LG); High Energy Physics - Experiment (hep-ex)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Machine-learning models in high-energy physics are often trained on simulated data, where fully simulated samples are computationally expensive while fast simulation provides large statistics at reduced realism. In this work, we systematically study transfer learning between fast-simulated and fully simulated datasets in a realistic LHC environment. We consider three representative tasks, signal-background classification, quark-gluon jet tagging, and missing transverse energy reconstruction, using dense neural networks, graph neural networks, and transformer-based architectures. Models are pretrained on ATLAS-like fast simulation and adapted to CMS-like fast simulation and to fully simulated ATLAS Open Data. Across all tasks, pretrained models consistently outperform independently trained baselines and require significantly less target-domain training data, typically reducing the needed statistics by about a factor of two. These results demonstrate that fast simulation can be used to learn robust, reusable representations and motivate publishing trained models as reusable scientific assets beyond large foundation models.
### Title:
          Does Your Neural Network Extrapolate? Feature Engineering as Identifiability Bias for OOD Generalization
 - **Authors:** Leonel Aguilar, Jan Nagler, Christoph Hoelscher, Nino Antulov-Fantulin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Successful deep neural networks discover salient features of data. We show when and why they fail to learn out-of-distribution (OOD)-relevant representations from an in-distribution (ID) training window. This requires decoupling feature learning from data-generating-process (DGP) identifiability. From a single training window, OOD extrapolation is non-identifiable: infinitely many DGPs are $\varepsilon$-observationally equivalent on the training data but diverge arbitrarily outside it, and no in-distribution criterion alone reliably breaks the tie. A structural commitment, the feature map, label map, and model class $(\varphi, \psi, \mathcal{M})$, dictates the assumed DGP and governs OOD generalization while leaving ID performance essentially unchanged. When architecture, pretraining, augmentation, input formats, or domain knowledge implicitly inject the missing commitment, the model succeeds. When it cannot infer OOD-relevant structure from ID evidence, it fails. Changing only the representation can make the same architecture, at the same in-distribution loss, differ by ${\sim}520\times$ out of distribution. When the commitment is correct and identifiable, OOD error vanishes. For example, Fourier coordinates turn periodic extrapolation into interpolation on $\mathbb{S}^1$. The same mechanism predicts outcomes in three natural-science settings (mass-action chemistry; Kepler's-third-law exoplanet prediction, $n=2{,}362$; and cross-species coding-DNA detection) and in a 264-run positional-encoding study across Transformer, Mamba, and S4D. Finally, a controlled study shows: correct features are necessary but not sufficient. The model class must express the target, and the transformed training data must cover the relevant representation space.
### Title:
          VIMCAN: Visual-Inertial 3D Human Pose Estimation with Hybrid Mamba-Cross-Attention Network
 - **Authors:** Zepeng Yang, Junxuan Bai, Hao Li, Ju Dai, Junjun Pan, Yongfeng Yin, Bin Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid advances in deep learning have significantly enhanced the accuracy of multimodal 3D human pose estimation (HPE). However, the state-of-the-art (SOTA) HPE pipelines still rely on Transformers, whose quadratic complexity makes real-time processing for long sequences impractical. Mamba addresses this issue through selective state-space modeling, enabling efficient sequence processing without sacrificing representational power. Nevertheless, it struggles to capture complex spatial dependencies in multimodal settings. To bridge this gap, we propose VIMCAN, a hybrid architecture that combines the efficient sequence modeling of Mamba with the spatial reasoning of Cross-Attention, and performs robust visual-inertial fusion and human pose estimation between RGB keypoints and wearable IMU data. By leveraging Mamba's dynamic parameterization for temporal modeling and Attention for spatial dependency extraction, VIMCAN achieves superior accuracy, with mean per-joint position errors (MPJPE) of 17.2 mm on TotalCapture and 45.3 mm on 3DPW. VIMCAN outperforms prior Transformer-based and other SOTA approaches while supporting real-time inference at over 60 frames per second on consumer-grade hardware. The source code is available on GitHub.
### Title:
          Dynamic Mode Decomposition along Depth in Vision Transformers
 - **Authors:** Nishant Suresh Aswani, Saif Eddin Jabari
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent work has shown that contiguous vision transformer (ViT) blocks (a) can be replaced by a linear map and (b) organize into recurrent phases of computation. We ask whether these observations coincide: does ViT depth implement approximately \textit{autonomous linear} dynamics, admitting a single operator $K$ applied recurrently across a contiguous span? We test this using Dynamic Mode Decomposition (DMD), which fits $K$ from selected, consecutive hidden-state pairs and predicts $p$ steps ahead via $K^p$. On four pretrained DINO ViTs, we study the regularization, rank, and calibration budget required for stable fitting. For short spans ($p \leq 4$), $K^p$ tracks an unconstrained endpoint map to within $0.02$ cosine similarity on DINOv3-H/16+, while also recovering intermediate activations at each skipped block. At early cut starts, the fitted operators compress to rank $\ll d$ with minimal calibration data, and across tokens, \texttt{cls} is most amenable to linearization; both properties decay monotonically with depth. Yet this local fidelity does not transfer downstream. At the final hidden state, after propagating through the remaining blocks, an identity baseline becomes competitive.
### Title:
          Revisiting Transformer Layer Parameterization Through Causal Energy Minimization
 - **Authors:** Jin Xu, Camille Couturier, Victor Rühle, Saravan Rajmohan, James Hensman
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer blocks typically combine multi-head attention (MHA) for token mixing with gated MLPs for token-wise feature transformation, yet many choices in their parameterization remain largely empirical. We introduce Causal Energy Minimization (CEM), a framework that recasts Transformer layers as optimization steps on conditional energy functions while explicitly accounting for layer parameterization. Extending prior energy-based interpretations of attention, CEM shows that weight-tied MHA can be derived as a gradient update on an interaction energy, and that a gated MLP with shared up/down projections can be viewed through an element-wise energy. This perspective identifies a design space for Transformer layers that includes within-layer weight sharing, diagonal-plus-low-rank interactions, lightweight preconditioners, and recursive updates. We evaluate CEM-derived layers in language-modeling experiments at the moderate hundred-million-parameter scale. Despite their constrained parameterizations, these layers train stably and can match corresponding Transformer baselines. Overall, our results suggest that CEM provides a useful lens for understanding Transformer layer parameterization, connecting Transformer architectures to energy-based models and motivating further exploration of energy-guided layer designs.
### Title:
          FS-I2P:A Hierarchical Focus-Sweep Registration Network with Dynamically Allocated Depth
 - **Authors:** Zhixin Cheng, Yujia Chen, Xujing Tao, Bohao Liao, Xiaotian Yin, Baoqun Yin, Tianzhu Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image-to-point cloud registration is often challenged by viewpoint changes, cross-modal discrepancies, and repetitive textures, which induce scale ambiguity and consequently lead to erroneous correspondences. Recent detection-free methods alleviate this issue by leveraging multi-scale features and transformer-based interactions. However, they still suffer from attention drift across layers and intra-scale inconsistencies, hindering precise registration. Inspired by human behavior, we propose a ``Focus--Sweep'' paradigm and develop a Hierarchical Focus--Sweep Interaction Module within an SSM-based framework to enhance multi-level cross-modal feature association. In addition, we introduce a Dynamic Layer Allocation Strategy that adaptively determines the iteration depth to better exploit geometric constraints and improve matching robustness. Extensive experiments and ablations on two benchmarks, RGB-D Scenes V2 and 7-Scenes, demonstrate that our approach achieves state-of-the-art performance.
### Title:
          Is She Even Relevant? When BERT Ignores Explicit Gender Cues
 - **Authors:** Jonas Klein, Chiara Manna, Eva Vanmassenhove
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gender bias in large language models has primarily been investigated for English, while languages with grammatical or morphological gender remain comparatively understudied. This paper investigates how and when gender information emerges in a Dutch BERT model trained from scratch, offering one of the first checkpoint-level analyses of bias formation in a Transformer architecture for a language combining overt morphological gender marking and generic forms. By extracting contextual embeddings throughout training, we construct dynamic gender subspaces using linear SVMs to trace when gender becomes linearly encoded and how this encoding evolves over time. Contextual embeddings are often assumed to integrate contextual cues robustly, allowing models to adjust the representation of a word depending on its more local usage. We therefore test whether explicit gender cues in controlled sentence templates (e.g., Zij is een loodgieter ('She is a plumber')) can override learned statistical associations (plumber -> male). Our findings challenge this assumption: although gender becomes clearly linearly separable around epoch 20 and is distributed across multiple embedding dimensions, the model struggles to update its internal gender representation in light of explicit contextual cues in short sentence templates. Stereotypical gender-profession pairings are predicted far more accurately than anti-stereotypical ones, and generic forms in Dutch systematically default to a male interpretation, even when the context explicitly denotes a female referent. Together, our results seem to indicate that contextualization in the representations learned by our Dutch BERT model is not sufficiently dynamic along the probed gender direction: explicit gender cues in anti-stereotypical contexts are not reliably reflected in the resulting representations, resulting in persistent male-default behaviour.
### Title:
          Cross-Attention and Encoder-Decoder Transformers: A Logical Characterization
 - **Authors:** Veeti Ahvonen, Damian Heiman, Antti Kuusisto, Miguel Moreno, Matias Selin
 - **Subjects:** Subjects:
Logic in Computer Science (cs.LO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We give a novel logical characterization of encoder-decoder transformers, the foundational architecture for LLMs that also sees use in various settings that benefit from cross-attention. We study such transformers over text in the practical setting of floating-point numbers and soft-attention, characterizing them with a new temporal logic. This logic extends propositional logic with a counting global modality over the encoder input and a past modality over the decoder input. We also give an additional characterization of such transformers via a type of distributed automata, and show that our results are not limited to the specific choices in the architecture and can account for changes in, e.g., masking. Finally, we discuss encoder-decoder transformers in the autoregressive setting.
### Title:
          Memory-Efficient Looped Transformer: Decoupling Compute from Memory in Looped Language Models
 - **Authors:** Victor Conchello Vendrell, Arnau Padres Masdemont, Niccolò Grillo, Jordi Ros-Giralt, Arash Behboodi, Fabio Valerio Massoli
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recurrent LLM architectures have emerged as a promising approach for improving reasoning, as they enable multi-step computation in the embedding space without generating intermediate tokens. Models such as Ouro perform reasoning by iteratively updating internal representations while retaining a standard Key-Value (KV) cache across iterations, causing memory consumption to grow linearly with reasoning depth. Consequently, increasing the number of reasoning iterations can lead to prohibitive memory usage, limiting the practical scalability of such architectures. In this work, we propose Memory-Efficient Looped Transformer (MELT), a novel architecture that decouples reasoning depth from memory consumption. Instead of using a standard KV cache per layer and loop, MELT maintains a single KV cache per layer that is shared across reasoning loops. This cache is updated over time via a learnable gating mechanism. To enable stable and efficient training under this architecture, we propose to train MELT using chunk-wise training in a two phase procedure: interpolated transition, followed by attention-aligned distillation, both from the LoopLM starting model to MELT. Empirically, we show that MELT models fine-tuned from pretrained Ouro parameters outperform standard LLMs of comparable size, while maintaining a memory footprint comparable to those models and dramatically smaller than Ouro's. Overall, MELT achieves constant-memory iterative reasoning without sacrificing LoopLM performance, using only a lightweight post-training procedure.
### Title:
          TextLDM: Language Modeling with Continuous Latent Diffusion
 - **Authors:** Jiaxiu Jiang, Jingjing Ren, Wenbo Li, Bo Wang, Haoze Sun, Yijun Yang, Jianhui Liu, Yanbing Zhang, Shenghe Zheng, Yuan Zhang, Haoyang Huang, Nan Duan, Wangmeng Zuo
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiT) trained with flow matching in a VAE latent space have unified visual generation across images and videos. A natural next step toward a single architecture for both generation (visual synthesis) and understanding (text generation) is to apply this framework to language modeling. We propose TextLDM, which transfers the visual latent diffusion recipe to text generation with minimal architectural modification. A Transformer-based VAE maps discrete tokens to continuous latents, enhanced by Representation Alignment (REPA) with a frozen pretrained language model to produce representations effective for conditional denoising. A standard DiT then performs flow matching in this latent space, identical in architecture to its visual counterpart. The central challenge we address is obtaining high-quality continuous text representations: we find that reconstruction fidelity alone is insufficient, and that aligning latent features with a pretrained language model via REPA is critical for downstream generation quality. Trained from scratch on OpenWebText2, TextLDM substantially outperforms prior diffusion language models and matches GPT-2 under the same settings. Our results establish that the visual DiT recipe transfers effectively to language, taking a concrete step toward unified diffusion architectures for multimodal generation and understanding.
### Title:
          Training-Induced Escape from Token Clustering in a Mean-Field Formulation of Transformers
 - **Authors:** Noboru Isobe, Daisuke Inoue, Masaaki Imaizumi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Analysis of PDEs (math.AP); Dynamical Systems (math.DS); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers perform inference by iteratively transforming token representations across layers. This layerwise computation has been studied empirically, and recent mean-field theories of Transformer dynamics explain how attention can drive token distributions toward clustering. However, existing mean-field analyses largely treat model parameters as prescribed, leaving open how training reshapes this clustering picture. We study this question in a noisy mean-field Transformer in which only a parameter-linear FFN is trained under $L^2$ regularization. We find and analyze a training-induced phase in the dynamics: after initially following attention-driven clustering, the token distribution can leave the clustered regime near the final layers. Our mathematical analysis is based on an entropy-regularized interaction energy that captures the clustering bias of attention. More broadly, our results point toward a training-aware mean-field theory of Transformer dynamics, in which training and inference dynamics are treated together.
### Title:
          NoiseGate: Learning Per-Latent Timestep Schedules as Information Gating in World Action Models
 - **Authors:** Wen Huang, Haoran Sun, Yongjian Guo, Yunxuan Ma, Haoran Li, Jing Long, Zhouying Mo, Zhong Guan, Yucheng Guo, Shuai Di, Junwu Xiong
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World Action Models (WAMs) are an emerging family of policies that tie robot action generation to future-observation modeling. In this work, we focus on the joint video--action modeling paradigm, where actions and imagined future observations are co-generated along a shared denoising or flow trajectory, so that perception, prediction, and control are coupled within one generative process. Existing WAMs typically realize this paradigm with a Mixture-of-Transformers (MoT), where video and action tokens interact through shared self-attention. This architecture can in principle assign a separate timestep $t_f$ to each predicted latent frame, yet current systems collapse this degree of freedom onto a single shared scalar $t$. Under the noise-as-masking view of Diffusion Forcing, this shared schedule imposes the unjustified prior that every predicted latent is equally reliable for action generation. We instead view the per-latent schedule as a \emph{learnable information-gating policy}: by changing a latent frame's noise level, the policy modulates the reliability of its Key/Value contribution to the action tokens. We propose \textbf{NoiseGate}, which combines independent per-latent timestep sampling during backbone training, a lightweight Gating Policy Network that emits per-latent time increments during denoising, and task-reward optimization that trains the schedule policy without hand-crafted shape priors. Built on a joint video--action MoT backbone, NoiseGate delivers consistent gains on diverse RoboTwin random-scene manipulation tasks.
### Title:
          RelAgent: LLM Agents as Data Scientists for Relational Learning
 - **Authors:** Xingyue Huang, Louis Tichelman, Jinwoo Kim, Krzysztof Olejniczak, İsmail İlkan Ceylan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Relational learning is a challenging problem that has motivated a wide range of approaches, including graph-based models (e.g., graph neural networks, graph transformers), tabular methods (e.g., tabular foundation models), and sequence-based approaches (e.g., large language models), each with its own advantages and limitations. We propose RelAgent, an LLM-based autonomous data scientist for relational learning, which operates in two phases. In the search phase, an LLM agent uses database, validation, and evaluation workspace tools to construct SQL feature programs and select a predictive model. In the inference phase, the resulting program is executed without further LLM calls. The final predictor consists of SQL queries and a classical model, enabling fast, deterministic, and intrinsically interpretable predictions: features are human-readable queries, and predictions depend only on the resulting query-defined feature map, enabling scalable deployment using standard database systems.
### Title:
          BeeVe: Unsupervised Acoustic State Discovery in Honey Bee Buzzing
 - **Authors:** Hamze Hammami, Nidhal Abdulaziz
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Discovering structure in biological signals without supervision is a fundamental problem in computational intelligence, yet existing bioacoustic methods assume vocal production models or predefined semantic units, leaving non-vocal species poorly served. This work introduces BeeVe, an unsupervised framework for acoustic state discovery in collective honey bee buzzing. BeeVe uses the self-supervised Patchout Spectrogram Transformer (PaSST) as a frozen feature extractor, then trains a Vector-Quantized Variational Autoencoder (VQ-VAE) without labels on those embeddings, learning a finite discrete codebook of acoustic tokens directly from unlabelled hive audio. No labels, pretext tasks, or contrastive objectives are used at any stage. Post-hoc evaluation against known queen status reveals that the learned tokens separate queenright and queenless conditions with Jensen-Shannon Divergence values between 0.609 and 0.688, and that the queenless condition further decomposes into three internally coherent sub-states stable across experiments with different codebook sizes and random seeds. Token transition analysis confirms non-random sequential structure (p << 0.001) across all experiments. Generalisation to unseen recordings preserves both token overlap (Jaccard = 0.947) and global manifold topology. These results demonstrate that unsupervised discrete codebook learning can recover repeatable acoustic structure from a non-vocal biological signal without annotation, opening a path toward non-invasive acoustic hive health monitoring.
### Title:
          Convergent Stochastic Training of Attention and Understanding LoRA
 - **Authors:** Zhengkai Sun, Dibyakanti Kumar, Alejandro F Frangi, Anirbit Mukherjee, Mingfei Sun
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Functional Analysis (math.FA); Probability (math.PR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have revolutionized machine learning and deploying attention layers in the model is increasingly standard across a myriad of applications. Further, for large models, it is common to implement Low Rank Adaptation (LoRA), whereby a factorized parameterization of them is trained, to achieve a surprisingly beneficial accuracy-size trade-off. In this work, via a unified framework we rigorously establish trainability of such models under stochastic methods. We prove that for any mild regularization, the empirical regression loss on a attention layer and LoRA on a shallow neural net, both induce Poincaré inequality for the corresponding Gibbs' measure. Then it follows via invoking recent results that a certain SDE, which mimics the SGD, minimizes the corresponding losses. In both the cases, our first-of-its-kind results of trainability on attention and nets, do not rely on any assumptions on the data or the size of the architecture.
### Title:
          STARFlow2: Bridging Language Models and Normalizing Flows for Unified Multimodal Generation
 - **Authors:** Ying Shen, Tianrong Chen, Yuan Gao, Yizhe Zhang, Yuyang Wang, Miguel Ángel Bautista, Shuangfei Zhai, Joshua M. Susskind, Jiatao Gu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep generative models have advanced rapidly across text and vision, motivating unified multimodal systems that can understand, reason over, and generate interleaved text-image sequences. Most existing approaches combine autoregressive language modeling with diffusion-based image generators, inheriting a structural mismatch between causal text generation and iterative visual denoising. We observe that autoregressive normalizing flows are autoregressive Transformers--sharing the same causal mask, KV-cache mechanism, and left-to-right structure as LLMs--making them the most natural paradigm for true unified multimodal generation. We present STARFlow2, built on the Pretzel architecture that vertically interleaves a pretrained VLM stream with a TarFlow stream via residual skip connections, both operating under the same causal mask. Combined with a deep-shallow flow design and a unified FAE latent space, STARFlow2 enables cache-friendly interleaved generation where both text and visual outputs directly enter the KV-cache without re-encoding. Experiments demonstrate strong performance across image generation and multimodal understanding benchmarks, validating autoregressive flows as a viable foundation for unified multimodal modeling.
### Title:
          Fast Byte Latent Transformer
 - **Authors:** Julie Kallini, Artidoro Pagnoni, Tomasz Limisiewicz, Gargi Ghosh, Luke Zettlemoyer, Christopher Potts, Xiaochuang Han, Srinivasan Iyer
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent byte-level language models (LMs) match the performance of token-level models without relying on subword vocabularies, yet their utility is limited by slow, byte-by-byte autoregressive generation. We address this bottleneck in the Byte Latent Transformer (BLT) through new training and generation techniques. First, we introduce BLT Diffusion (BLT-D), a new model and our fastest BLT variant, trained with an auxiliary block-wise diffusion objective alongside the standard next-byte prediction loss. This enables an inference procedure that generates multiple bytes in parallel per decoding step, substantially reducing the number of forward passes required to generate a sequence. Second, we propose two extensions inspired by speculative decoding that trade some of this speed for higher generation quality: BLT Self-speculation (BLT-S), in which BLT's local decoder continues generating past its normal patch boundaries to draft bytes, which are then verified with a single full-model forward pass; and BLT Diffusion+Verification (BLT-DV), which augments BLT-D with an autoregressive verification step after diffusion-based generation. All methods may achieve an estimated memory-bandwidth cost over 50% lower than BLT on generation tasks. Each approach offers its own unique advantages, together removing key barriers to the practical use of byte-level LMs.
### Title:
          EmambaIR: Efficient Visual State Space Model for Event-guided Image Reconstruction
 - **Authors:** Wei Yu, Yunhang Qian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent event-based image reconstruction methods predominantly rely on Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs) to process complementary event information. However, these architectures face fundamental limitations: CNNs often fail to capture global feature correlations, whereas ViTs incur quadratic computational complexity (e.g., $O(n^2)$), hindering their application in high-resolution scenarios. To address these bottlenecks, we introduce EmambaIR, an Efficient visual State Space Model designed for image reconstruction using spatially sparse and temporally continuous event streams. Our framework introduces two key components: the cross-modal Top-k Sparse Attention Module (TSAM) and the Gated State-Space Module (GSSM). TSAM efficiently performs pixel-level top-k sparse attention to guide cross-modal interactions, yielding rich yet sparse fusion features. Subsequently, GSSM utilizes a nonlinear gated unit to enhance the temporal representation of vanilla linear-complexity ($O(n)$) SSMs, effectively capturing global contextual dependencies without the typical computational overhead. Extensive experiments on six datasets across three diverse image reconstruction tasks - motion deblurring, deraining, and High Dynamic Range (HDR) enhancement - demonstrate that EmambaIR significantly outperforms state-of-the-art methods while offering substantial reductions in memory consumption and computational cost. The source code and data are publicly available at: this https URL
## Keyword: autonomous driving
### Title:
          See Tomorrow, Act Today: Foresight-Driven Autonomous Driving
 - **Authors:** Bozhou Zhang, Nan Song, Yuang Wang, Jiankang Deng, Xiatian Zhu, Li Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current end-to-end autonomous driving planners are fundamentally reactive: they condition on historical and present observations to predict future actions. We argue that autonomous agents should instead imagine future scenes before deciding, just as human drivers mentally simulate ``what will happen next" before acting. We introduce ForeSight, a foundation world model centric planning framework that reframes autonomous driving as anticipatory decision-making. Rather than treating world models as auxiliary components, ForeSight makes future scene imagination the primary driver of action prediction. Our approach operates in two stages: (1) generating plausible future visual worlds via a pretrained world model, and (2) planning actions conditioned on these imagined futures. This paradigm shift from ``what should I do now?" to ``what will happen, and how should I respond?" enables genuinely anticipatory rather than reactive planning. By grounding decisions in anticipated contexts rather than present observations alone, ForeSight navigates dynamic, interactive scenarios more effectively. Extensive experiments on NAVSIM and nuScenes demonstrate that explicit future imagination significantly outperforms previous state-of-the-art alternatives, validating our foresight-driven approach.
### Title:
          GEM: Generating LiDAR World Model via Deformable Mamba
 - **Authors:** Yang Wu, Zhaojiang Liu, Qiang Meng, Youquan Liu, Renliang Weng, Jianjun Qian, Jian Yang, Jin Xie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models, which simulate environmental dynamics and generate sensor observations, are gaining increasing attention in autonomous driving. However, progress in LiDAR-based world models has lagged behind those built on camera videos or occupancy data, primarily due to two core challenges: the inherent disorder of LiDAR point clouds and the difficulty of distinguishing dynamic objects from static structures. To address these issues, we propose GEM: a Generative LiDAR world model that leverages deformable mamba architecture, significantly improving fidelity and imaginative capability. Specifically, leveraging the structural similarity between sequential laser scanning and Mamba's processing mechanism, we first tokenize LiDAR sweeps into compact representations via a custom LiDAR scene tokenizer. After unsupervised disentanglement of tokenized features via a dynamic-static separator, a tri-path deformable Mamba is introduced to perform selective scanning and adaptive gating fusion over the disentangled features, leading to enhanced spatial-temporal understanding of the world evolution. Optionally, a planner and a BEV layout controller can be integrated to explore the model's capability for autonomous rollout and its potential to generate ``what-if" scenarios. Extensive experiments show that GEM achieves state-of-the-art performances across diverse benchmarks and evaluation settings, demonstrating its superiority and effectiveness. Project page: this https URL.
### Title:
          UniD-Shift: Towards Unified Semantic Segmentation via Interpretable Share-Private Multimodal Decomposition
 - **Authors:** Shuai Zhang, Zhecheng Shi, Zhuxiao Li, Jing Ou, Tengxi Wang, Yuan Liu, Wufan Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic segmentation of large-scale 3D point clouds is crucial for applications such as autonomous driving and urban digital twins. However, the sparse sampling pattern of LiDAR and the view-dependent geometric distortion in image observations complicate cross-modal alignment and hinder stable fusion. Inspired by the fact that 2D images captured by cameras are representations of the 3D world, we recognize that the features learned from 2D and 3D segmentation share some common semantics, while other aspects remain modality-specific. This insight motivates a unified multimodal framework for joint 2D-3D semantic segmentation. We combine a SAM-based vision encoder with a SPTNet-based geometric encoder to extract complementary semantic and geometric representations. The resulting features from both modalities are explicitly decomposed into shared and private subspaces, where the shared components summarize semantic factors common to both domains, and the private components preserve properties that are unique to each modality. A lightweight attention-based fusion module aggregates the shared features into a consistent cross-modal representation, and a regularized training objective ensures both semantic alignment and subspace independence. Experiments on the SemanticKITTI and nuScenes benchmarks demonstrate consistent improvements in segmentation accuracy over representative multimodal baselines, accompanied by competitive computational efficiency. Cross-domain evaluation on nuScenes USA-Singapore shows stable performance under distribution shifts, demonstrating strong generalization. The implementation code is publicly available at: this https URL.
### Title:
          Probabilistic Object Detection with Conformal Prediction
 - **Authors:** Christopher Ries, Moussa Kassem Sbeyti, Nicolas Bianco, Nadja Klein
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conformal Prediction (CP) is a distribution-free method for constructing prediction sets with marginal finite-sample coverage guarantees, making it a suitable framework for reliable uncertainty quantification in safety-critical object detection. However, object detection introduces structured multi-output predictions, complicating the application of classical CP theory developed for single outputs. In addition, standard, unscaled CP produces fixed-width prediction intervals across inputs, leading to unnecessary width for low-uncertainty predictions. While scaled CP addresses this by adapting the interval width to an input-dependent uncertainty estimate, prior work has neither systematically compared unscaled and scaled CP for multi-class object detection, nor integrated CP with a complementary uncertainty quantification method in this setting. We fill this gap by: (i) applying CP coordinate-wise to bounding box corners with a Bonferroni correction for box-level guarantees; (ii) scaling the resulting intervals using per-prediction aleatoric uncertainty estimates derived from a probabilistic object detector trained with loss attenuation, evaluated in uncalibrated and two calibrated variants; (iii) extending to a two-step pipeline that constructs prediction sets for the class using RAPS and conditions the conformalized bounding boxes on the predicted class set. Across three autonomous driving datasets (KITTI, BDD, CODA), including a cross-domain setting under distribution shift, scaled CP consistently improves interval sharpness over unscaled CP, achieving up to 19% higher IoU and 39% lower interval scores, without sacrificing coverage. Class-wise calibration further improves coverage for both variants with a negligible effect on sharpness. Together, these improvements yield more actionable uncertainty estimates for real-time, real-world object detection.
### Title:
          One World, Dual Timeline: Decoupled Spatio-Temporal Gaussian Scene Graph for 4D Cooperative Driving Reconstruction
 - **Authors:** Yulong Chen, Xiaoyun Dong, Haoyu Zhang, Zongxian Yang, Lewei Xie, Xinke Li, Yifan Zhang, Kai Wang, Jianping Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing dynamic scenes from Vehicle-to-Infrastructure Cooperative Autonomous Driving (VICAD) data is fundamentally complicated by temporal asynchrony: vehicle and infrastructure cameras operate on independent clocks, capturing the same dynamic agent such as cars and pedestrians at different physical times. Existing Gaussian Scene Graph methods implicitly assume synchronized observations and assign a single pose per agent per frame, which is an assumption that breaks in cooperative settings, where the resulting gradient conflicts cause severe ghosting on dynamic agents. We identify this as a representation-level failure, not an optimization artifact: we prove that any single-timeline formulation incurs an irreducible photometric loss scaling quadratically with agent velocity and cross-source time offset. To resolve this, we propose Dust (DecoUpled Spatio-Temporal) Gaussian Scene Graph for 4D Cooperative Driving Reconstruction. DUST Gaussian Scene Graph shares a canonical Gaussian set per agent for appearance consistency, while maintaining decouple pose trajectories aligned to each source's true capture timestamps. We prove that this decoupling enables the pose-gradient kernel block-diagonal, eliminating cross-source interference entirely. To make Dust practical, we further introduce a static anchor-based pose correction pipeline that corrects spatio misalignment between vehicle and infrastructure annotations, and a pose-regularized joint optimization scheme that prevents trajectory jitter and drift during early training. On 26 sequences from V2X-Seq, DUST achieves state-of-the-art performance, improving dynamic-area PSNR by 3.2 dB over the strongest baseline and reducing Fréchet Video Distance by 37.7%, with keeping robustness under larger temporal asynchrony. Code is available at this https URL.
### Title:
          123D: Unifying Multi-Modal Autonomous Driving Data at Scale
 - **Authors:** Daniel Dauner, Valentin Charraut, Bastian Berle, Tianyu Li, Long Nguyen, Jiabao Wang, Changhui Jing, Maximilian Igl, Holger Caesar, Boris Ivanovic, Yiyi Liao, Andreas Geiger, Kashyap Chitta
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The pursuit of autonomous driving has produced one of the richest sensor data collections in all of robotics. However, its scale and diversity remain largely untapped. Each dataset adopts different 2D and 3D modalities, such as cameras, lidar, ego states, annotations, traffic lights, and HD maps, with different rates and synchronization schemes. They come in fragmented formats requiring complex dependencies that cannot natively coexist in the same development environment. Further, major inconsistencies in annotation conventions prevent training or measuring generalization across multiple datasets. We present 123D, an open-source framework that unifies such multi-modal driving data through a single API. To handle synchronization, we store each modality as an independent timestamped event stream with no prescribed rate, enabling synchronous or asynchronous access across arbitrary datasets. Using 123D, we consolidate eight real-world driving datasets spanning 3,300 hours and 90,000 kilometers, together with a synthetic dataset with configurable collection scripts, and provide tools for data analysis and visualization. We conduct a systematic study comparing annotation statistics and assessing each dataset's pose and calibration accuracy. Further, we showcase two applications 123D enables: cross-dataset 3D object detection transfer and reinforcement learning for planning, and offer recommendations for future directions. Code and documentation are available at this https URL.
