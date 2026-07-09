# Showing new listings for Thursday, 9 July 2026
## Keyword: SLAM
### Title:
          MiLSD: A Micro Line-Segment Detector for Resource-Constrained Devices
 - **Authors:** Parsa Hassani Shariat Panahi, Amir Hossein Jalilvand, M. Hassan Najafi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Line segment detection is a key building block in visual SLAM, 3D reconstruction, and industrial inspection. Recent deep learning methods have greatly improved accuracy, yet even the smallest models require several megabytes of memory, exceeding low-cost MCU capacity. This work investigates the maximum achievable accuracy under a sub-megabyte budget. We propose MiLSD, a detector tailored for MCU-level constraints, and systematically compare three output representations within a compact fully-convolutional backbone. Our study shows that the proposed F-Clip center-with-length-and-angle formulation learns most effectively at small model sizes. We find that 8-bit quantization preserves full-precision performance, while 4-bit quantization causes significant degradation, particularly in angle regression, with quantization-aware training recovering only part of the loss. With a one-megabyte activation budget and inference enhancements including sub-pixel decoding, test-time augmentation, and a lightweight verifier, MiLSD improves sAP10 on ShanghaiTech Wireframe from 10.6 (25k parameters, 0.25 MB) to 24.1 within 1 MB. Rather than competing with GPU-scale parsers, we map the accuracy memory trade-off across representations, bit-widths, capacities, and post-processing strategies for embedded vision systems.
### Title:
          CILC: Cryptographically-secure Inter-agent Loop Closure Candidate Detection for Multi-Agent Collaborative SLAM
 - **Authors:** Andrew Fishberg, Yixuan Jia, Jonathan P. How
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-agent Simultaneous Localization and Mapping (SLAM) and collaborative SLAM (CSLAM) require robots to continuously exchange global descriptors (GDs) to detect inter-agent loop closures (ILCs). While encrypted radios protect this traffic from external eavesdroppers, they offer no protection against a compromised swarm member. We show this threat is concrete by demonstrating how a corrupted agent can reconstruct approximations of an honest agent's imagery and trajectory from its public GD broadcasts. To address this, we propose CILC (Cryptographically-secure Inter-agent Loop Closure candidate detection), a first-of-its-kind system leveraging Secure Multi-Party Computation (SMPC) to detect ILC candidates without exchanging GDs in the clear. Rather than securing the entire CSLAM pipeline, we apply SMPC only to ILC candidate detection (i.e., GD similarity comparison), a privacy-sensitive yet computationally lightweight step, yielding an advantageous privacy-to-overhead trade-off. We validate in both simulation and hardware experiments that CILC remains real-time and communication-feasible across multimodal GDs (visual and LiDAR), while mitigating information leakage to a compromised swarm agent.
### Title:
          Dynamic Object Detection and Tracking in Construction: A Fisheye Camera and LiDAR Sensor Fusion Model
 - **Authors:** Yilong Chen, Huili Huang, Yong K. Cho
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust dynamic object detection and tracking are essential for enabling robots to operate safely and effectively alongside humans in complex environments such as construction sites. While LiDAR-based SLAM and occupancy grid methods offer viable solutions for detecting and tracking motion, many state-of-the-art 3D vision approaches rely heavily on pre-trained neural networks and require additional post-processing to identify moving objects. Sensor fusion techniques, combining the precision of LiDAR with the semantic richness of RGB imagery, offer a promising alternative. In this work, we present a novel framework that enhances a quadruped robot equipped with a LiDAR sensor and an upward-facing fisheye camera for real-time dynamic object detection and tracking. After identifying moving objects within a registered point cloud, our method assigns semantic labels by projecting 3D coordinates onto a 2D cylindrical panorama, aligning with real-time image-based detections for observation update of the Kalman filter. The proposed system demonstrates high precision, simplicity, and robustness, particularly in handling objects transitioning between dynamic and static states, thus it is well-suited for deployment in real-world construction environments.
### Title:
          PLED-VINS: A Point-Line Event-Based Visual Inertial SLAM for Dynamic Environments
 - **Authors:** Seunghun Lee, Jihun Nam, Dong-Uk Seo, Hyun Myung
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dynamic environments remain a fundamental challenge for visual SLAM, where unreliable observations from moving objects and rapid motion degrade state estimation accuracy. Although event cameras preserve fine-grained spatio-temporal information, most existing event-based SLAM frameworks still assume static scenes and lack approaches to estimate the reliability of features. To this end, we propose PLED-VINS, a monocular event camera-based visual-inertial SLAM framework that enables robust state estimation in dynamic environments. We propose an entropy-recency score map to characterize the temporal reliability of both point and line features based on event temporal statistics. Concurrently, geometric reliability is estimated via a unified point-line robust bundle adjustment. Building upon these, we design an adaptive weighting strategy that fuses temporal and geometric reliability, including motion-conditioned reliability modeling for line features, to suppress unreliable observations. Experimental results demonstrate that PLED-VINS improves state estimation on the evaluated dynamic sequences with moving objects.
### Title:
          GeoGS-SLAM: Geometry-Only Gaussian Splatting for Dense Monocular SLAM
 - **Authors:** Lipu Zhou, Yaoyun Kang, Junxiang Pang, Shengkai Sun, Tingting Bao, Kehan Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense visual SLAM is a fundamental problem in robotics. Recent advances in 3DGS have demonstrated its potential for dense SLAM. Existing 3DGS frameworks focus on both appearance and geometry modeling. However, scene geometry is typically more critical for SLAM than novel view synthesis because downstream robotic tasks, such as navigation and obstacle avoidance, rely primarily on accurate spatial geometry rather than photorealistic rendering. This observation raises a natural question: Is it feasible for 3DGS to perform 3D reconstruction without scene appearance modeling? Motivated by this, we propose Geometry-only Gaussian Splatting (GeoGS), which directly reconstructs scene geometry, and further present GeoGS-SLAM, a dense visual SLAM system built upon this representation. Specifically, GeoGS retains only spatial parameters to reduce the number of per-primitive parameters by over 80%. In contrast to existing 3DGS methods, GeoGS focuses solely on geometric reconstruction, which significantly reduces the number of Gaussian primitives, accelerates geometric convergence, and enhances robustness to illumination variations. In addition, we present an effective training framework that optimizes the Gaussian primitives via single-view and multi-view geometric and photometric supervision, and speeds up geometry convergence with a local-plane driven initialization that better aligns primitives with local structures. Furthermore, we introduce a map update strategy for loop closure that globally transforms the Gaussian map to align it with the corrected pose estimates, thereby preventing map tearing caused by inconsistent per-viewpoint pose corrections in existing methods. Extensive experiments on synthetic and real-world benchmarks demonstrate that our method outperforms SOTA methods in terms of online mapping efficiency and geometric reconstruction quality.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          CILC: Cryptographically-secure Inter-agent Loop Closure Candidate Detection for Multi-Agent Collaborative SLAM
 - **Authors:** Andrew Fishberg, Yixuan Jia, Jonathan P. How
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-agent Simultaneous Localization and Mapping (SLAM) and collaborative SLAM (CSLAM) require robots to continuously exchange global descriptors (GDs) to detect inter-agent loop closures (ILCs). While encrypted radios protect this traffic from external eavesdroppers, they offer no protection against a compromised swarm member. We show this threat is concrete by demonstrating how a corrupted agent can reconstruct approximations of an honest agent's imagery and trajectory from its public GD broadcasts. To address this, we propose CILC (Cryptographically-secure Inter-agent Loop Closure candidate detection), a first-of-its-kind system leveraging Secure Multi-Party Computation (SMPC) to detect ILC candidates without exchanging GDs in the clear. Rather than securing the entire CSLAM pipeline, we apply SMPC only to ILC candidate detection (i.e., GD similarity comparison), a privacy-sensitive yet computationally lightweight step, yielding an advantageous privacy-to-overhead trade-off. We validate in both simulation and hardware experiments that CILC remains real-time and communication-feasible across multimodal GDs (visual and LiDAR), while mitigating information leakage to a compromised swarm agent.
### Title:
          G-PROBE: Cross-FOV Place Recognition and Certainty-Coupled Localization for 3D Point Clouds
 - **Authors:** Jinseop Lee
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Global localization from 3D point clouds remains challenging under limited or asymmetric fields of view (FOV), which fail to provide the dense, symmetric coverage that place recognition methods assume. We present G-PROBE, a learning-free global localization framework that removes this assumption. A virtual sensor decomposition runs the same pipeline, by design, on configurations ranging from a narrow-FOV sensor to a panoramic or multi-sensor rig. The front-end enumerates cross-FOV branch ensembles that encode heading hypotheses for heading-invariant place recognition. A score-scale-invariant, tuning-free gamma-SGRT suppresses heading aliasing under partial FOV and provably becomes inert at symmetric 360 degrees. The back-end, CG-GICP, refines a coarse full-cloud GICP with a pass restricted to high-certainty co-observed points selected by a bird's-eye-view certainty map (a by-product of front-end scoring). This certainty coupling links descriptor evaluation to 6-DoF metric pose estimation without an external verification module. Evaluated on five LiDAR datasets and three modalities (mechanical, solid-state, FMCW), G-PROBE attains the highest learning-free multi-session F1 on average and is competitive in panoramic single-session settings. Where hand-crafted and zero-shot supervised baselines collapse under wide-to-narrow cross-sensor pairing, it remains usable end-to-end (up to 55.0% vs. no more than 6.8% success), and under FOV asymmetry (360 to 60 degrees) it retains about 54% Recall@1, about 18x the strongest learning-free baseline.
### Title:
          Rail Track Extraction from Rasterized Classified Point Clouds Using a Full-Resolution, Fully Convolutional Recurrent Neural Network
 - **Authors:** Alexander Gribov, Jie Chang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rail track extraction is essential for effective railway asset management and maintenance, especially in automated inspection and mapping workflows. This paper introduces a novel method for extracting rail tracks from classified 3D point clouds using a fully convolutional recurrent neural network that preserves full spatial resolution and is trained exclusively on synthetically generated data. This approach enhances per-pixel quality and is particularly suited for rail track extraction. The proposed method begins by rasterizing points corresponding to railroad tracks, then applies the neural network to reduce noise and yield a cleaner track representation suitable for vectorization [1]. Subsequent morphological operations further refine the resultant data, enabling accurate track centerline extraction. Next, the extracted centerlines undergo smoothing to eliminate residual irregularities [2, 3]. Finally, the algorithm transfers 3D information from lidar points onto 2D polylines and applies additional vertical smoothing. A single centerline for both tracks is found using the Dynamic Time Warping (DTW) algorithm [4]. The final outcome consists of rail top centerlines and track centerlines derived for rail pairs, with minimal manual intervention. Experimental validation confirms the effectiveness of this method in yielding high-quality rail track extraction.
### Title:
          Dynamic Object Detection and Tracking in Construction: A Fisheye Camera and LiDAR Sensor Fusion Model
 - **Authors:** Yilong Chen, Huili Huang, Yong K. Cho
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust dynamic object detection and tracking are essential for enabling robots to operate safely and effectively alongside humans in complex environments such as construction sites. While LiDAR-based SLAM and occupancy grid methods offer viable solutions for detecting and tracking motion, many state-of-the-art 3D vision approaches rely heavily on pre-trained neural networks and require additional post-processing to identify moving objects. Sensor fusion techniques, combining the precision of LiDAR with the semantic richness of RGB imagery, offer a promising alternative. In this work, we present a novel framework that enhances a quadruped robot equipped with a LiDAR sensor and an upward-facing fisheye camera for real-time dynamic object detection and tracking. After identifying moving objects within a registered point cloud, our method assigns semantic labels by projecting 3D coordinates onto a 2D cylindrical panorama, aligning with real-time image-based detections for observation update of the Kalman filter. The proposed system demonstrates high precision, simplicity, and robustness, particularly in handling objects transitioning between dynamic and static states, thus it is well-suited for deployment in real-world construction environments.
### Title:
          Behavior Foundations for Quadruped Robots: ABot-C0 Technical Report
 - **Authors:** Xufeng Zhao, Fuzhi Yang, Jianhui Chen, Li Gao, Zhang Meng, Jie Gao, Yao Zheng, Wenyu Liu, Menglin Yang, Minqi Gu, Yaru Zhao, Honglin Han, Shihui Su, Zixiao Tang, Liu Liu, Mu Xu, Yang Cai, Wenbin Tang
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Human-Computer Interaction (cs.HC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In embodied intelligence systems, the motion controller serves as the critical bridge between semantic reasoning and physical execution. Humanoid control has progressed rapidly through large-scale human motion-capture data and motion-tracking paradigm. However, producing quadruped robots motion corpora with scalability and physical feasibility faces more fundamental obstacles: animal motion data is scarce, and cross-embodiment retargeting remains fragile. We present ABot-C0, a generalist motion-control system for quadruped robots that establishes three complementary behavior foundations: a scalable multi-source motion-data pipeline, robust policy learning across motion tracking, locomotion, and scene interaction, and a unified deployment stack for reliable real-world operation. Fundamentally, we construct a data pyramid through conditional video-generation synthesis, annotated motion capture, teleoperation and human design, producing 16,074 physically feasible motion clips as the data foundation for various motion learning demands. We then train a Flow-Matching generalist policy that demonstrates for the first time quadruped motion tracking scaling law that its performance improves consistently as training scales up, with zero-shot capability to track unseen motions. Then, we push a step further for robust all-terrain traversal locomotion by adopting a three-stage privileged-to-perceptive framework with temporal LiDAR memory and terrain-predictive supervision. Collectively, these components form a motion generalist that coordinates multi-policy execution, smooth behavior transitions, energy-efficient control, and safety mechanisms for real-world deployment. Extensive experiments on urban-terrain autonomous navigation and companion-style multimodal interaction demonstrate that quadruped robots move beyond single-function demos toward product-level behavioral intelligence.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          CILC: Cryptographically-secure Inter-agent Loop Closure Candidate Detection for Multi-Agent Collaborative SLAM
 - **Authors:** Andrew Fishberg, Yixuan Jia, Jonathan P. How
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-agent Simultaneous Localization and Mapping (SLAM) and collaborative SLAM (CSLAM) require robots to continuously exchange global descriptors (GDs) to detect inter-agent loop closures (ILCs). While encrypted radios protect this traffic from external eavesdroppers, they offer no protection against a compromised swarm member. We show this threat is concrete by demonstrating how a corrupted agent can reconstruct approximations of an honest agent's imagery and trajectory from its public GD broadcasts. To address this, we propose CILC (Cryptographically-secure Inter-agent Loop Closure candidate detection), a first-of-its-kind system leveraging Secure Multi-Party Computation (SMPC) to detect ILC candidates without exchanging GDs in the clear. Rather than securing the entire CSLAM pipeline, we apply SMPC only to ILC candidate detection (i.e., GD similarity comparison), a privacy-sensitive yet computationally lightweight step, yielding an advantageous privacy-to-overhead trade-off. We validate in both simulation and hardware experiments that CILC remains real-time and communication-feasible across multimodal GDs (visual and LiDAR), while mitigating information leakage to a compromised swarm agent.
### Title:
          SmartHomeSecure: Automated Detection and Repair of Smart Home Configuration Errors Using Large Language Models
 - **Authors:** Yizhi Wang, Xinghua Gao, Reachsak Ly, Alireza Shojaei
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Smart home automation platforms increasingly rely on user-authored YAML configuration files to define device behaviors, but these files are prone to syntax, formatting, and semantic logic errors that can cause automation failures and safety risks. Existing YAML validators, static analysis tools, and general-purpose large language models offer limited support for end-to-end diagnosis and repair because they lack domain-specific understanding and validated correction workflows. This paper presents SmartHomeSecure, a prototype for automated detection and repair of Home Assistant configuration errors using lightweight program analysis and constraint-guided large language model generation. SmartHomeSecure parses YAML files, detects syntactic and common semantic errors, normalizes error context, applies deterministic auto-fixes for routine defects, and constructs constrained prompts that guide LLMs toward minimal and structurally valid repairs. The system is implemented as a modular web application with four layers: UI Shell, Feature Orchestrator, Domain Engine, and Integration Layer. Its repair pipeline was evaluated on 100 real-world Home Assistant YAML files with manually injected errors across five categories: syntax/parsing, indentation, mapping, sequence, and scalar quoting errors. Four models were tested: gpt-oss-20b, gpt-oss-120b, llama-3.1-8b, and llama-3.3-70b. Results show that three models achieved 100% error detection accuracy, with repair success rates ranging from 87% to 93%. Manual verification found no hallucinated or incorrect repairs among successful outputs. These findings suggest that combining domain-aware program analysis with constrained generative AI is a feasible approach for improving the reliability and usability of smart home configuration repair.
### Title:
          Devising Interactive Spaces: A Rehearsal-Oriented Tool for Creating Responsive Environments for Immersive Theatre
 - **Authors:** Pavlos Panagiotidis, Paul Tennent, Jocelyn Spence, Nils Jaeger
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a rehearsal-oriented system for creating responsive built environments during theatre devising workshops. The system connects bespoke sensing modules for gesture, position, and speech recognition to light and sound outputs through a visual no-code programming layer. It was developed, used, and refined across six workshops with eight professional performance-makers, where participants created light-and-sound scores, gesture- and position-triggered scenes, responsive architectures, participatory prototypes, and a multi-room scratch performance. Rather than presenting a production-ready show-control platform, this demo focuses on how sensing and actuation can be made available as compositional materials during early-stage creative experimentation for immersive theatrical compositions. The system is designed to support quick configuration, visible mappings, and in-room testing, allowing performers to experiment with responsive spaces with minimal technical support. We describe the system architecture, its workshop use, and the practical conditions that helped integrate interactive sensing into embodied performance-making.
### Title:
          Rail Track Extraction from Rasterized Classified Point Clouds Using a Full-Resolution, Fully Convolutional Recurrent Neural Network
 - **Authors:** Alexander Gribov, Jie Chang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rail track extraction is essential for effective railway asset management and maintenance, especially in automated inspection and mapping workflows. This paper introduces a novel method for extracting rail tracks from classified 3D point clouds using a fully convolutional recurrent neural network that preserves full spatial resolution and is trained exclusively on synthetically generated data. This approach enhances per-pixel quality and is particularly suited for rail track extraction. The proposed method begins by rasterizing points corresponding to railroad tracks, then applies the neural network to reduce noise and yield a cleaner track representation suitable for vectorization [1]. Subsequent morphological operations further refine the resultant data, enabling accurate track centerline extraction. Next, the extracted centerlines undergo smoothing to eliminate residual irregularities [2, 3]. Finally, the algorithm transfers 3D information from lidar points onto 2D polylines and applies additional vertical smoothing. A single centerline for both tracks is found using the Dynamic Time Warping (DTW) algorithm [4]. The final outcome consists of rail top centerlines and track centerlines derived for rail pairs, with minimal manual intervention. Experimental validation confirms the effectiveness of this method in yielding high-quality rail track extraction.
### Title:
          Seekable OCI: Lazy-Loading Container Images via Range-Request Indexing
 - **Authors:** James Thompson, Wayne Mesard, Jesse Butler, Sri Saran Balaji Rajakumar, Henry Wang
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Operating Systems (cs.OS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Container image pulling accounts for the majority of pod startup time in Kubernetes environments. Standard pull downloads the entire image before the container can start, even when the application accesses only a fraction of the image content at startup. We present SOCI (Seekable OCI), a lazy-loading architecture that enables containers to start without downloading the full image. SOCI builds an external index over standard OCI images, mapping files to byte ranges within compressed layers. At runtime, a FUSE filesystem intercepts file accesses and serves them via HTTP range requests. Unlike prior approaches that require image format conversion, SOCI works with unmodified images and standard registries. The index is stored as an OCI referrer artifact, requiring no changes to images, registries, or deployment tooling. On a 1.3 GB Python web service image, SOCI reduces cold-start pull time from 20 seconds to approximately 2.8 seconds (7.4x speedup), with pull time independent of image size. Larger images see larger speedups (9.3x on a 2.5 GB image) because SOCI pull time is constant while standard pull scales linearly. We measure a crossover at 80% access density: below this, lazy loading wins; above, parallel full pull is faster. SOCI lazy loading is deployed in production on Amazon EKS and Amazon ECS Fargate (which launched 18.4 million tasks per day during Prime Day 2025), and has been serving lazy-load requests since 2023. EKS Auto Mode uses SOCI's parallel pull mode for GPU instances.
### Title:
          General Incomplete Multimodal Learning via Dynamic Quality Perception
 - **Authors:** Xiangyu Meng, Shicai Wei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal learning robust to missing modalities is essential for real-world applications. Existing methods mainly focus on inter-modality missing, where entire modalities are absent, while overlooking intra-modality degradation, where modalities are present but severely corrupted. In practice, these two types of missing often coexist, making existing approaches ineffective. To address this limitation, we propose General Incomplete Multimodal Learning (GIML), a unified framework that simultaneously handles both inter-modality missing and intra-modality degradation through dynamic quality perception. Specifically, GIML models heterogeneous missing patterns as continuous modality information degradation, enabling degradation-aware adaptive fusion. To achieve reliable quality perception, we introduce a Noise-aware Quality Estimator that learns the mapping from corrupted features to noise intensity through controlled noise injection. Furthermore, we propose a Noise-Semantic Decoupled module that separates semantic information from noise interference. This improves robustness and generalization to unseen corruption patterns. Extensive experiments across datasets with diverse modality types demonstrate the effectiveness and generality of GIML. Code is available at: this https URL.
### Title:
          ColorFM: An Optimization-to-Learning Framework for Color Transfer via Flow Matching
 - **Authors:** Yuhang He, Kai Zhang, Xiaoming Li, Du Chen, Jian Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Color transfer aims to align the color distribution of a source image with that of a reference image while preserving structural and semantic consistency. However, existing methods often suffer from inaccurate global mapping, semantic misalignment, and visual artifacts. To address these issues, we propose ColorFM, an optimization-to-learning framework. ColorFM connects online optimization to offline inference by reformulating color transfer as the transport of pixel distributions along velocity fields via Flow Matching. Specifically, we introduce ColorFM-O, an instance-specific optimization scheme that fits the velocity field through hierarchical color coupling guided by semantic priors. By numerically integrating the induced flow trajectories, ColorFM-O produces precise and semantically consistent color transfer results, while generating high-quality paired data as pseudo-supervision. Building upon this, we design ColorFM-L, an efficient feed-forward model trained on the generated pairs. Through implicit state modeling, ColorFM-L extracts deep semantic features to predict flow parameters for bidirectional linearized transport, ensuring accurate color transfer. Extensive experiments demonstrate that ColorFM-L outperforms state-of-the-art methods in visual quality, structural fidelity, and semantic consistency, successfully combining the accuracy of optimization with the speed of feed-forward inference.
### Title:
          Miter-Aware LUT Mapping: Aligning Structure and Solvability for Efficient Logic Equivalence Checking
 - **Authors:** Jiaying Zhu, Zhengyuan Shi, Mengxia Tao, Kezhi Li, Min Li, Qiang Xu
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Logic Equivalence Checking (LEC), a fundamental hardware verification task, is often bottlenecked by synthesis-induced structural perturbations and XOR-dense regions that degrade SAT solver performance. We contend that the modeling of the miter is as critical as the SAT solver itself. To this end, we introduce a miter-aware mapping framework that strategically formulates the problem before solving. By constructing a LUT-based miter -- instead of a traditional, flat netlist -- our approach preserves critical structural correspondence between the two designs while making high-level logic relations explicit. Our framework uniquely integrates three techniques: equivalence-preserving mapping to structurally align the two circuits, Gaussian-guided XOR modeling to algebraically simplify dense arithmetic, and solver-oriented LUT selection to generate a representation optimized for efficient SAT reasoning. Evaluated on comprehensive datasets, our method achieves up to a \textbf{92.1\%} reduction across state-of-the-art SAT solvers. This demonstrates that a solver-aware modeling paradigm, which unifies structural mapping with SAT reasoning, can fundamentally enhance LEC efficiency.
### Title:
          Benchmark Engineering as a Design Instrument for Heterogeneous Information Systems
 - **Authors:** Jáchym Bártík, Alžběta Šrůtková, Irena Holubová
 - **Subjects:** Subjects:
Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Contemporary information systems operate in heterogeneous and continuously evolving data environments, where representation choices and structural redesign decisions strongly influence system behavior. Existing benchmarking approaches, however, rely mostly on static datasets and fixed schemas, providing limited support for analyzing architectural trade-offs or guiding evolution in multi-model settings. This paper introduces TransforMMer, a framework for evolution-aware and representation-aware benchmark engineering in heterogeneous information systems. The approach treats benchmark construction as a systematic design process: starting from raw data, inferring structure, refining it conceptually, and generating comparable dataset variants across relational, document, and graph systems. The framework is grounded in a unified representation that enables explicit modeling of schemas and cross-model mappings and supports reproducible transformations across alternative representations. We position benchmarking as a system-design tool for evaluating architectural and representation-level decisions in evolving information systems, rather than as a static comparison of database engines. Through controlled benchmark construction scenarios on real-world datasets, we demonstrate how structural redesign steps -- such as embedding, enrichment, and hybrid partitioning -- affect observed query costs across systems. The results show that performance differences emerge primarily from the interaction between workload and representation design. By enabling systematic generation of structurally distinct yet semantically aligned dataset variants, the proposed approach connects conceptual data modeling with empirical system evaluation and supports reproducible, evolution-aware analysis of heterogeneous information systems.
### Title:
          Non-minimal k-perfect hashing: Tight lower bounds and an application to fast static hash tables
 - **Authors:** Ragnar Groot Koerkamp, Stefan Hermann, Peter Sanders, Stefan Walzer
 - **Subjects:** Subjects:
Data Structures and Algorithms (cs.DS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A minimal perfect hash function (minimal PHF) is a data structure mapping a static set of $n$ keys to $n$ bins without collisions. Two natural generalizations are minimal $k$-PHFs where $n$ keys are mapped to $n/k$ bins of capacity $k$ each, and (non-minimal) PHFs with load factor ${\alpha} < 1$ where the number of bins is increased by a factor of $1/{\alpha}$, resulting in spare capacity. While there has been a recent surge of interest in perfect hashing generally, non-minimal $k$-PHFs have not been systematically studied despite a natural use case of speeding up static hash tables: The idea is that a small cache-resident $k$-PHF maps each key $x$ to a cache-line-sized bin of capacity $k$ where $x$ resides. Ideally, this yields a branchless lookup operation with a single cache miss working at high load factors for positive and negative queries alike. Our main theoretical contribution is to determine tight space lower bounds for $k$-PHFs for all pairs of ${\alpha} \in (0,1]$ and $k \geq 1$. It turns out that combining ${\alpha} < 1$ and $k \geq 2$ drastically reduces the space of $k$-PHFs, e.g. for $(k,{\alpha}) = (16,0.8)$ the space lower bound is $0.027$ bits per key while for $(k,{\alpha}) = (16,1.0)$ and $(k,{\alpha}) = (1,0.8)$ the lower bounds are higher by factors of $\approx 8$ and $\approx 32$, respectively. On the practical side, we develop a $k$-PHF based on PtrHash and tune it for use in static hash tables. Empirically, our implementation produces $k$-PHFs of size roughly $50\%$ above the lower bound. A static hash set based on this $k$-PHF is consistently at least as fast as other hash sets for negative and mixed queries. On two of the three tested architectures it achieves up to $1.5\times$ speedup for large $n\geq 30M$ where a $1$-PHF does not fit in cache.
### Title:
          The AI Resilience Gap: Bringing Artificial Intelligence Inside the Operational Resilience Perimeter
 - **Authors:** Jonathan Shelby
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid adoption of artificial intelligence across regulated firms has produced an extensive governance response oriented around trustworthiness: the EU AI Act, ISO IEC 42001, the NIST AI Risk Management Framework, and the United Kingdom's principles-based approach all address safety, fairness, transparency, and model risk. That response is necessary but incomplete. It does not, on its own, address operational resilience: the continuity of important business services under severe but plausible disruption, the substitutability of AI components, and the concentration of dependency on the small number of firms that supply frontier models. This paper argues that AI adoption creates a resilience obligation that is distinct from, and inadequately covered by, the trustworthy AI stack, and that United Kingdom financial authorities are already closing this gap through the Financial Policy Committee's systemic analysis, the Critical Third Parties regime, and the May 2026 joint statement on frontier AI and cyber resilience. We map the two regulatory logics, identify the structural gap between them, and propose the AI Resilience Framework: a regime-agnostic method for bringing AI dependencies inside the operational resilience perimeter through dependency mapping, a criticality-substitutability tiering, the extension of impact tolerances to AI-specific failure modes, an explicit fallback doctrine, and provider level concentration management. The framework gives chief information security officers, security architects, and boards an actionable route from AI governance policy to demonstrable resilience. This work extends a companion analysis of the United Kingdom cyber resilience regulatory stack into the artificial intelligence dimension.
### Title:
          Communicative Efficiency of Single vs. Multi-Axis Robot Neck Motion
 - **Authors:** Chapa Sirithunge, Haewon Jeong, Qinghua Guan, Fumiya Iida, Josie Hughes
 - **Subjects:** Subjects:
Robotics (cs.RO); Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Nonverbal communication through head and neck movement is fundamental to human social signalling, yet how robotic neck morphology translates motion into communicative information remains poorly understood. We present an information-theoretic framework characterising robot neck movement as a communication channel, quantifying information transmitted and energy expended across varied configurations. Using a robotic neck platform, we recorded 84 video stimuli spanning three rotational degrees of freedom (DoF), varying amplitude, acceleration, and frequency, measuring Shannon entropy of pixel-change signals alongside energy consumption. A perceptual study validated communicative interpretations of each motion. While humans typically engage one axis per gesture, robots are unconstrained by biological architecture, motivating tests up to 3 DoF. Yet communicative information peaks at two DoF and decreases at three despite rising energy cost, a phenomenon we term the morphological information bottleneck. Motion parameter effects were parameter-dependent, some additive, others non-linear. We introduce the Motor Information Space, a framework mapping entropy against energy to expose communicative efficiency across morphologies, in which the optimal configuration achieves 5.26 bits at competitive energy cost. Perception data further confirm multi-axis movements reduce clarity. These findings challenge the assumption that anatomical completeness improves robotic expressiveness, establishing a quantitative basis for morphological design in robots, especially humanoids.
### Title:
          How Reliable Is the Multi-Input Heuristic for Bitcoin Address Clustering in Law Enforcement Contexts?
 - **Authors:** Leopold Müller (1), Jana Elsner (1), Thomas Niedermayer (2), Bernhard Haslhofer (3), Thomas Goger (4), Niklas Kühl (1), Christian Rückert (1) ((1) University of Bayreuth, (2) Iknaio Cryptoasset Analytics, (3) Complexity Science Hub, (4) Bavarian Central Office for the Prosecution of Cybercrime)
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Address clustering is an important technique in blockchain forensics, widely employed by law enforcement to trace illicit crypto asset flows. The multi-input heuristic (MIH), which clusters addresses potentially associated with the same entity, is the most widely used. Yet, despite its broad adoption, the MIH has rarely been evaluated against reliable ground truth data. We implement a reusable evaluation framework covering nine established metrics and apply it to ground truth address-to-entity mappings obtained directly from European crypto asset service providers under legally mandated reporting obligations. When evaluation is restricted to reported addresses, the MIH appears strong at dataset level: we observe no mergers between reported services and recover same-service address pairs with recall $0.71$. However, this result is driven by one large service and ignores unlabeled addresses absorbed into full clusters. Metrics that assess the full clusters show substantially lower precision and recall ($0.36$ and $0.44$), meaning that services are often only partially recovered or embedded in larger clusters. Entity-level results further reveal near-complete failures for some services. When MIH-based clusters are used to support criminal suspicion, preliminary seizure of crypto assets to secure later forfeiture/ confiscation, or as evidence in trial proceedings, prosecutors and judges must account for the heuristic's metric-dependent and entity-dependent reliability.
### Title:
          GeoGS-SLAM: Geometry-Only Gaussian Splatting for Dense Monocular SLAM
 - **Authors:** Lipu Zhou, Yaoyun Kang, Junxiang Pang, Shengkai Sun, Tingting Bao, Kehan Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense visual SLAM is a fundamental problem in robotics. Recent advances in 3DGS have demonstrated its potential for dense SLAM. Existing 3DGS frameworks focus on both appearance and geometry modeling. However, scene geometry is typically more critical for SLAM than novel view synthesis because downstream robotic tasks, such as navigation and obstacle avoidance, rely primarily on accurate spatial geometry rather than photorealistic rendering. This observation raises a natural question: Is it feasible for 3DGS to perform 3D reconstruction without scene appearance modeling? Motivated by this, we propose Geometry-only Gaussian Splatting (GeoGS), which directly reconstructs scene geometry, and further present GeoGS-SLAM, a dense visual SLAM system built upon this representation. Specifically, GeoGS retains only spatial parameters to reduce the number of per-primitive parameters by over 80%. In contrast to existing 3DGS methods, GeoGS focuses solely on geometric reconstruction, which significantly reduces the number of Gaussian primitives, accelerates geometric convergence, and enhances robustness to illumination variations. In addition, we present an effective training framework that optimizes the Gaussian primitives via single-view and multi-view geometric and photometric supervision, and speeds up geometry convergence with a local-plane driven initialization that better aligns primitives with local structures. Furthermore, we introduce a map update strategy for loop closure that globally transforms the Gaussian map to align it with the corrected pose estimates, thereby preventing map tearing caused by inconsistent per-viewpoint pose corrections in existing methods. Extensive experiments on synthetic and real-world benchmarks demonstrate that our method outperforms SOTA methods in terms of online mapping efficiency and geometric reconstruction quality.
### Title:
          GIFT: Geometry-Informed Low-precision Gradient Communication for LLM Pretraining
 - **Authors:** Jieying Wang, Shuyuan Fan, Mingkai Zheng, Zhao Zhang
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gradient communication is a primary scaling bottleneck in large language model (LLM) pretraining. Communicating gradients in low-precision formats, such as FP8 and NVFP4, can significantly reduce the communication volume. Existing methods quantize gradients via linear or nonlinear mappings in Euclidean space, often degrading model performance because highly anisotropic gradients incur direction-dependent distortion. We present GIFT, a geometry-informed gradient scaling method that performs low-precision communication in geometry-aware coordinates. By transforming gradients into a near-isotropic space before quantization, GIFT makes low-precision representations substantially more faithful to their high-precision counterparts. GIFT only changes the coordinate system used for low-precision gradient communication and does not change the optimizer, training recipe, communication collective, or low-precision format. We also develop a simplified geometry-aware transformation algorithm with low-rank approximation and selective application to balance the computation overhead and communication reduction. We examine the empirical convergence of GIFT using Llama-300M and Llama-600M models. Our results show that GIFT reduces the end-to-end pretraining time of Llama-600M by 7.6% on 64 NVIDIA GH200 Superchips, while improving the downstream task preservation profile over direct Euclidean FP8 communication under the same optimizer and communication path.
### Title:
          Context-Aware Slum Mapping in Sub-Saharan Africa Using Sentinel-1 Texture and Local Climate Zones
 - **Authors:** Peterson Chepkilot, Babak Memar, Paolo Gamba
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate mapping of informal settlements remains a major challenge in Sub-Saharan African (SSA) cities because optical imagery often fails to distinguish Informal Settlements (defined here as LCZ 7) from spectrally similar formal Compact Low-Rise areas (LCZ 3). This study presents a context-aware, reproducible Optical-SAR framework that improves informal settlement delineation using Sentinel-2 spectral features and Sentinel-1 structural information within an adapted Local Climate Zone (LCZ) taxonomy. We implement a three-tier SAR integration strategy: calibrated backscatter, GLCM textures, and a physics-guided feature engineered to capture the high structural disorder and weak radar return characteristic of SSA informal settlements. Using reference data across Nairobi and Eldoret (Kenya), we evaluate performance via a stratified hold-out protocol and a season-aware ablation study. Results show that SAR textures provide the dominant performance gain for LCZ 7 detection. The Optical-SAR model achieves overall accuracy of 0.816 (dry) and 0.807 (wet), significantly outperforming the WUDAPT baseline (OA 0.704) and reducing the critical LCZ 3 - LCZ 7 confusion to 7%. Seasonal analysis indicates that while optical-only separability varies with phenology, SAR-derived textures stabilize informal settlement mapping across seasons. These findings demonstrate that the incorporation of SAR-derived features yields consistent improvements for urban morphology mapping in data-scarce environments across seasons and across the evaluated source cities, while cross-city transfer remains limited without local adaptation strategies.
### Title:
          Simplification of the Isotropic Generalized Stop-Type Prandtl-Ishlinskii Vector Hysteresis Operator Using Analytical Return-Point Mapping
 - **Authors:** Arvinth Shankar, Klaus Kuhnen, Iryna Kulchytska-Ruchka, Sebastian Schöps
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While the thermodynamically formulated generalized Prandtl-Ishlinskii stop-type operator effectively captures hysteresis nonlinearities, it requires a local iterative procedure to update each hysteron, resulting in considerable computational effort. In this work, we propose a simplified thermodynamic formulation of the generalized Prandtl-Ishlinskii stop operator. The nonlinear mapping on the stop operator is replaced by an identity, such that the hysteresis operators are directly weighted through their outputs, while the nonlinear anhysteretic response, represented by ramp dead-zone basis functions, is fully preserved. For isotropic cases, this simplification enables a closed-form solution for the local plastic correction, eliminating per-hysteron iterative Newton updates. The resulting constitutive mapping is integrated into a finite element solver, and numerical results show a significant reduction in computation time with accuracy comparable to the generalized model.
### Title:
          PHaul: A PPO-based forwarding agent for Sub6 enhanced Integrated Access and Backhaul networks
 - **Authors:** Jorge Pueyo, Daniel Camps-Mur and, Miguel Catalan-Cid
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3GPP Integrated Access and Backhaul (IAB) allows operators to deploy outdoor mm-wave access networks in a cost-efficient manner, by reusing the same spectrum in access and backhaul. In IAB networks the performance bottleneck is the wireless backhaul segment, where efficient forwarding strategies are needed to effectively use the available capacity. In addition, the performance of the mm-wave IAB backhaul segment is contingent on the availability of line of sight (LoS) conditions in the selected deployment sites. To mitigate LoS dependence, in this paper, we propose to complement the mm-wave backhaul segment of IAB networks with additional Sub6 backhaul links, which contribute to the capacity and robustness of the backhaul network. We refer to IAB networks combining Sub6 and mm-wave links in the backhaul as Sub6 enhanced IAB networks. In this context, the main contribution of this paper is PHaul, a forwarding engine for Sub6 enhanced IAB networks that accomodates different traffic engineering criteria, and combines an offline path selection heuristic with an online Deep Reinforcement Learning (DRL) agent based on Proximal Policy Optimization (PPO). By leveraging a network digital twin of the IAB wireless backhaul, PHaul periodically samples the input traffic of the backhaul network and updates flow to path mappings, with execution times below 10 seconds in realistic backhaul topologies. We present an exhaustive performance evaluation, where we demonstrate that PHaul can achieve gains of up to 36\% in throughput efficiency and of up to 20\% in fairness, when compared against two alternative heuristics in a wide range of network configurations. We also demonstrate that PHaul is robust to differences between the network topologies considered in the training and inference phases, which can occur in practice due to link failures.
## Keyword: localization
### Title:
          CILC: Cryptographically-secure Inter-agent Loop Closure Candidate Detection for Multi-Agent Collaborative SLAM
 - **Authors:** Andrew Fishberg, Yixuan Jia, Jonathan P. How
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-agent Simultaneous Localization and Mapping (SLAM) and collaborative SLAM (CSLAM) require robots to continuously exchange global descriptors (GDs) to detect inter-agent loop closures (ILCs). While encrypted radios protect this traffic from external eavesdroppers, they offer no protection against a compromised swarm member. We show this threat is concrete by demonstrating how a corrupted agent can reconstruct approximations of an honest agent's imagery and trajectory from its public GD broadcasts. To address this, we propose CILC (Cryptographically-secure Inter-agent Loop Closure candidate detection), a first-of-its-kind system leveraging Secure Multi-Party Computation (SMPC) to detect ILC candidates without exchanging GDs in the clear. Rather than securing the entire CSLAM pipeline, we apply SMPC only to ILC candidate detection (i.e., GD similarity comparison), a privacy-sensitive yet computationally lightweight step, yielding an advantageous privacy-to-overhead trade-off. We validate in both simulation and hardware experiments that CILC remains real-time and communication-feasible across multimodal GDs (visual and LiDAR), while mitigating information leakage to a compromised swarm agent.
### Title:
          G-PROBE: Cross-FOV Place Recognition and Certainty-Coupled Localization for 3D Point Clouds
 - **Authors:** Jinseop Lee
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Global localization from 3D point clouds remains challenging under limited or asymmetric fields of view (FOV), which fail to provide the dense, symmetric coverage that place recognition methods assume. We present G-PROBE, a learning-free global localization framework that removes this assumption. A virtual sensor decomposition runs the same pipeline, by design, on configurations ranging from a narrow-FOV sensor to a panoramic or multi-sensor rig. The front-end enumerates cross-FOV branch ensembles that encode heading hypotheses for heading-invariant place recognition. A score-scale-invariant, tuning-free gamma-SGRT suppresses heading aliasing under partial FOV and provably becomes inert at symmetric 360 degrees. The back-end, CG-GICP, refines a coarse full-cloud GICP with a pass restricted to high-certainty co-observed points selected by a bird's-eye-view certainty map (a by-product of front-end scoring). This certainty coupling links descriptor evaluation to 6-DoF metric pose estimation without an external verification module. Evaluated on five LiDAR datasets and three modalities (mechanical, solid-state, FMCW), G-PROBE attains the highest learning-free multi-session F1 on average and is competitive in panoramic single-session settings. Where hand-crafted and zero-shot supervised baselines collapse under wide-to-narrow cross-sensor pairing, it remains usable end-to-end (up to 55.0% vs. no more than 6.8% success), and under FOV asymmetry (360 to 60 degrees) it retains about 54% Recall@1, about 18x the strongest learning-free baseline.
### Title:
          LLMs Silently Correct African American English: Auditing and Mitigating Dialect Bias via Activation Steering
 - **Authors:** Huan Wu, Ali Emami, Muhammad Furquan Hassan, Osaretin Igbinoba, Osakpolor Idusuyi, Osamede Igbinoba, Faiza Khan Khattak, Laleh Seyyed-Kalantari
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 African American English (AAE), a rule-governed dialect spoken by over 30 million people, is routinely misinterpreted and "corrected" by large language models (LLMs). Across six instruction-tuned LLMs (14B to 70B), we show that state-of-the-art models systematically prefer Standard American English (SAE) continuations even when the preceding context is in AAE, effectively rewriting AAE into SAE. We present an end-to-end framework to audit and mitigate this bias. For auditing, we introduce conditional Dialect Group Invariance (cDGI), which isolates true model bias from translator-induced artifacts, and a feature-level localization analysis that identifies which AAE markers most strongly trigger bias; we find that syntactic constructions, especially negative concord (e.g., "ain't nobody"), are universal triggers across all models. For mitigation, we introduce, to our knowledge, the first application of activation steering to dialect bias: a training-free, test-time method that extracts dialect directions via causal tracing and injects them into bias-relevant layers. Activation steering reduces bias 5 to 20 times more than prompting while preserving SAE fluency. To enable this work, we release REAL-AAE , the largest real-AAE parallel corpus to date: 17,479 AAE/SAE/ AAE_back triplets from natural tweets (2 to 6 times larger than prior real-AAE resources), validated automatically (BERTScore F1 = 0.95) and by three native AAE speakers (83.0% semantic agreement).
### Title:
          Stochastic Stability of Nonlinear MPPI via Contraction Theory and Control Lyapunov Functions
 - **Authors:** Hyung-Jin Yoon, Hunmin Kim
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Model Predictive Path Integral (MPPI) control is directly implementable on nonlinear systems because its online update requires only forward rollouts of the dynamics, not gradients, linearizations, or convex optimization. However, this algorithmic flexibility does not by itself provide a closed-loop stability certificate. This paper establishes such a certificate through a stability-inheritance argument. We assume that there exists a deterministic nonlinear MPC policy whose disturbance-free closed loop is certified by a Control Lyapunov Function terminal cost and a contraction metric, and we show that finite-sample MPPI inherits the nominal contraction when its sampling-based update approximates this reference policy with sufficient accuracy. The approximation error decomposes into a finite-temperature bias floor and a Monte Carlo term that vanishes at the inverse square-root rate in the sample count. Under an explicit small-gain condition, the resulting MPPI closed loop satisfies a finite-horizon, high-probability localized mean practical stability bound with residual floors due to MPPI approximation error, Gaussian process noise, and bad sampling events. The paper also gives an ISS-type restatement and a finite-horizon design procedure for choosing the localization set, temperature, and sample count.
### Title:
          TACoS: Weakly Supervised Learning of Two-Dimensional Materials from Scribble Annotations to Precise Segmentation
 - **Authors:** Jiabei Chen, Liping Zhang, Jiang-Bin Wu, Zhongming Wei, Enhao Ning, Su Yan, Weijun Li, Ping-Heng Tan, Xin Ning
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The precise pixel-level localization of 2D material flakes is crucial for high-throughput screening. However, traditional fully supervised methods rely on dense annotations, which are costly and time-consuming, severely limiting the practical deployment of segmentation models. This paper proposes TACoS, a specialized scribble segmentation framework tailored for 2D materials. First, we design a unified framework that integrates semi-supervised consistency learning with structured tree energy constraints. This framework comprises two core components: an unlabeled weak-strong distribution alignment module and a tree energy regularization module. The former employs cosine consistency constraints to enhance prediction alignment across views. Meanwhile, the latter utilizes minimum spanning trees to establish pixel affinity relationships and generate structure-aware soft pseudo labels for online semantic guidance. Next, we introduce asymmetric regional contrast learning. This approach fuses high-confidence predictions from the weak augmentation branch with scribbles to form augmented labels, and construct category prototypes in the representation space. Simultaneously, we prioritize contrastive constraints on challenging pixels in boundary-unlabeled regions. This strategy enhances intra-class cohesion and inter-class separation at the representation level, effectively reducing category confusion in low-contrast edges and complex backgrounds. Experiments conducted on the constructed graphene and MoS2 datasets demonstrate that our method TACoS achieves over 96% of fully supervised performance using less than 0.6% annotated data. Furthermore, it exhibits superior structural coherence and boundary stability in scenarios with weakly contrasting edges and complex backgrounds, providing an efficient and scalable solution for automated high-throughput screening of 2D material flakes.
### Title:
          Why Fake ? Unveiling the Semantic Vocabulary of Deepfake Detectors
 - **Authors:** Vazgken Vanian, Alexandros Doumanoglou, Dimitris Zarpalas
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deepfake (DF) technology poses a significant threat to information integrity, driving the need for robust detection methods. Most DF detectors only consider predicting a binary label for whether the input is real or fake, lacking the justification required for real-world applications like legal proceedings. Explainable DF Detection has emerged to address this limitation, but existing techniques frequently fall short by either relying on human annotations for precise artifact localization or generating superficially plausible textual explanations without grounding. This work investigates the use of post-hoc explainable AI (XAI) to analyze the decision-making process of state-of-the-art black-box DF detectors. Specifically, we employ Encoding-Decoding Direction Pairs (EDDP), a technique suitable for uncovering the concept space of DF detectors (their semantic vocabulary) as well as the mechanism for writing and reading concept information to and from internal representations. Our analysis reveals previously hidden real and fake features learned implicitly during detector training, offering nuanced explanations unattainable through conventional methods. This enables global model understanding, spatially aware concept localization, and counterfactual what-if analysis, all contributing to a deeper comprehension of DF detection strategies.
### Title:
          AA-ViT: Anatomically Aware Vision Transformer with Structural and Frequency Guidance for Contrast Enhanced Brain MRI Synthesis
 - **Authors:** Talha Meraj, Tom Flannery, Charlie Cummins, Matt Townend, Thomas C Booth, Peter Crossley, Michael McCann, Ian Overton, Saritha Unnikrishnan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate tumour localization and diagnosis is a critical component of clinical care for brain cancers. Magnetic Resonance Imaging (MRI) is the most commonly used imaging modality due to its superior soft-tissue contrast. However, standard MRI often exhibits limited contrast and imaging artifacts, which necessitates the use of contrast agents to enhance lesion visibility. The administration of chemical contrast agents is not always feasible and may be contraindicated in patients with renal impairment or other health conditions. As a result, developing accurate and non-invasive contrast enhanced MRI (CEMRI) synthesis methods has clinical importance. In recent years, numerous approaches for CEMRI synthesis have been proposed, predominantly relying on generative artificial intelligence models. While these methods demonstrate promising performance, their dependence on implicit feature learning often limits their ability to preserve anatomical boundaries and tumour-specific fine structures. To address these challenges, we propose an anatomically aware frequency-and-structure-guided vision transformer (AA-ViT), for CEMRI synthesis using pre-contrast MRI modalities (T1, T2, and FLAIR). Experiments on the BraTS 2021 dataset demonstrate that the proposed method preserves anatomical and lesion boundaries, achieving higher PSNR and SSIM than state-of-the-art approaches. Clinical evaluation by three neuroradiologists and a neurosurgeon on 19 randomly selected cases across diverse gliomas yielded a mean score of 3.94/5, providing preliminary clinical validation rarely seen in prior studies. Synthetic post-contrast scans from our model could lower scanning costs, shorten imaging time, and avoid the potential risks of using gadolinium-based contrast agents.
### Title:
          What Makes a Good Bug Report for an AI Agent?
 - **Authors:** Lara Khatib, Noble Saji Mathews, Meiyappan Nagappan, Pengyu Nie, Thomas Zimmermann
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated program repair (APR) agents are transitioning from research benchmarks to developer workflows, yet they still begin with bug reports written for human developers. While decades of research have established what makes a good bug report for humans (e.g., steps to reproduce, stack traces), it remains unclear whether these features transfer to LLM-based agents. We study this question in two analyses. First, we use statistical modeling to examine associations between 27 bug-report features and repair success across 433 SWE-bench Verified issues attempted by 87 repair agents. We find that fix suggestions, reproduction scripts, repository source code, and localization info are associated with higher resolution likelihood, while longer reports are associated with lower odds. Second, we conduct controlled ablations across 2 models and 17 problem-statement mutations on SWE-bench Pro, varying the information available to an agent while holding the underlying task fixed. We remove or isolate selected bug-report content, delete fault-localization cues, and test structural changes that flatten lists or remove section headers. We find that both models depend on localization cues and expected behavior, and that structural changes alone can reduce solve rates, even without removing any content. The two models diverge in how they handle missing information: Qwen searches more widely and can exhaust its turn budget, while Gemma commits to a plausible interpretation early and patches on it. Our findings indicate that a good bug report for an agent overlaps with, but is not identical to, a good report for a human: agents benefit most from concrete, executable, and well-localized information, whereas some qualities long emphasized for human readers, such as natural language steps to reproduce and readable descriptions, contribute little or even correlate with lower success.
### Title:
          From Noisy Traces to Root Causes: Structural Trajectory Analysis and Causal Extraction for Agent Optimization
 - **Authors:** Ying Chang, Jiahang Xu, Xuan Feng, Chenyuan Yang, Peng Cheng, Yuqing Yang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The optimization of long-horizon agents increasingly relies on reflection-based mechanisms, where a large language model (LLM) acts as an optimizer to diagnose agent failures and improve agent policies. However, real execution traces are difficult to use directly for optimization: large trace collections are often redundant and heterogeneous, making optimization inefficient and prone to overfitting to low-value failures; meanwhile, each individual trajectory also contains many irrelevant steps, while naive context reduction methods such as truncation or sliding windows can discard causally important evidence and produce misleading optimization signals. To resolve this dilemma, we introduce STRACE (Structural TRajectory Analysis and Causal Extraction), a framework that constructs high signal-noise optimization contexts for more precise and effective optimization. At the batch level, STRACE mines failure patterns to filter redundant traces and retain representative failures; within each selected trace, it performs causal localization over a textual dependency graph to remove non-causal steps and identify the true root-cause module for optimization. Empirical results demonstrate that STRACE significantly outperforms standard context-filtering baselines. Notably, on a challenging formal verification task (VeruSAGE-Bench), it successfully optimizes human-expert designed agents, delivering $1.4\times$ success-rate improvement (42.5% to 58.5%). The code is available at this https URL .
## Keyword: transformer
### Title:
          TriRoute: Unified Learned Routing for Joint Adaptive Attention, Experts, and KV-Cache Allocation
 - **Authors:** Andrii Balashov, Olena Ponomarova
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conditional computation can decouple language model quality from per-token inference cost, yet leading techniques act on a single axis in isolation: Mixture-of-Experts (MoE) sparsifies the FFN, Mixture-of-Depths (MoD) skips whole transformer blocks, and KV-cache quantization compresses attention memory. We argue these three decisions (attention resolution, expert selection, and cache bit-width) are strongly coupled and should be made jointly: a token rare enough to warrant full attention may also need high-precision caching regardless of which expert processes it. We introduce TriRoute, a single lightweight controller shared across all three axes that, for every token at every layer, emits a coordinated policy: (i) an attention mode (skip/local/full), (ii) a sparse set of FFN experts (with a null expert recovering MoD), and (iii) a KV-cache bit-width. The controller trains end-to-end via a heterogeneous relaxation (Gumbel-Softmax with straight-through estimation for categorical decisions and load-balanced top-k gating for experts) under a Lagrangian budget constraint that turns the average compute and memory cost into a controllable knob. We identify a cross-axis routing-collapse cascade in naive joint training, where collapse on one axis propagates to the others, and address it with per-axis normalization and a coupling-aware balancing loss. On decoder-only models from 160M to 1.3B parameters at compute-optimal token counts, TriRoute Pareto-dominates the best independent MoD+MoE+KV-quantization combination at matched inference FLOPs and memory, while better preserving tail-case robustness on rare entities, code, and arithmetic that pure perplexity optimization erodes. Post-hoc analysis reveals interpretable structure: the controller allocates full attention and high-precision cache to sentence-initial positions, rare subwords, and named entities, while cheaply routing function words.
### Title:
          Audio Sentiment Analysis via Distillation and Cross-Modal Integration of Generated Multilingual Transcripts
 - **Authors:** Andrei-George Durdun, Victor Constantinescu, Radu Tudor Ionescu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatically recognizing the sentiment, positive or negative, from speech is a challenging task, requiring both the analysis of vocal inflections and the interpretation of uttered words. Recent solutions rely on audio foundation models to solve the task, but it remains unclear if such models can take all aspects into account. To this end, we propose a multimodal solution that integrates audio and text information via cross-modal transformers, where text transcripts are automatically generated via an automatic speech recognition (ASR) tool. Moreover, we create multiple text modalities by automatically translating the transcripts into multiple languages via machine translation tools. Audio and multilingual text features are combined via a cascaded architecture comprising cross-modal transformer blocks that integrate modalities one by one. We further distill knowledge from the multimodal model, called teacher, into a unimodal (audio only) model, called student. We conduct experiments on a large-scale dataset, demonstrating that the automatically generated textual information can bring significant performance boosts in multimodal sentiment polarity classification. Our ablation study confirms that both automatic transcripts and automatic translations are helpful. Moreover, we show that the audio-only model can be enhanced via distillation, boosting performance without any computational overhead during inference. To reproduce the reported results, we publicly release our code at this https URL.
### Title:
          STAGformer: A Spatio-temporal Agent Graph Transformer for Micro Mobility Demand Forecasting
 - **Authors:** Ye Zihao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate station-level demand forecasting is essential for the efficient operation of bike-sharing systems, yet it remains challenging due to complex spatio-temporal dependencies and the large scale of urban networks. This paper presents STAGformer, a Spatio-Temporal Agent Graph Transformer that achieves efficient global modeling with linear computational complexity. The model introduces a two-step agent attention mechanism, where a small set of learnable spatial and temporal agent tokens first aggregate global information and then broadcast it back to individual stations and time steps, effectively capturing long-range interactions while reducing the quadratic cost of standard self-attention to O(NT). STAGformer integrates four core modules: a spatio-temporal encoder that fuses dynamic node features with external contextual factors (weather, time, points of interest), a graph propagation module for spatial neighbor aggregation, a temporal convolution module for local pattern extraction, and the agent attention module for global dependency modeling. Extensive experiments on two real-world datasets -- NYC Citi-Bike and Chicago Divvy-Bike -- demonstrate that STAGformer consistently outperforms state-of-the-art baselines across multiple prediction horizons, achieving significant improvements in both RMSE and MAE. Ablation studies validate the contribution of each component, with the agent attention mechanism proving critical for modeling global spatio-temporal dependencies.
### Title:
          STST-JEPA: Shallow-Target Spatio-Temporal Joint Embedding Prediction Architecture For EEG Self-Supervised Learning
 - **Authors:** Roy Segal, Yoni Svechinsky, Tomer Fekete
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Brain age -- the age inferred from a physiological recording -- is an emerging biomarker whose deviation from chronological age tracks neurological and psychiatric burden, and EEG is an attractive substrate for it because it is cheap, portable, and temporally rich. Yet EEG brain-age models must contend with cross-site montage heterogeneity, small labelled cohorts, and dominant subject-level non-stationarity, and few EEG foundation models have been shown to deliver competitive age regression across the full pediatric-to-older-adult range in which such a biomarker would actually be deployed. We introduce STST-JEPA, a self-supervised transformer for resting-state and task EEG, pretrained on 47,703 sessions spanning ages 5-81 from the this http URL and Healthy Brain Network (HBN) corpora. The model combines a latent-prediction objective - predicting masked-token representations against an EMA-of-tokenizer target - with an auxiliary signal-reconstruction term, applied to 30-second multi-channel windows under spatiotemporal block masks. A lightweight attentive probe trained on frozen pretrained embeddings achieves a best held-out-validation mean absolute error of 3.06 years (r = 0.924) for age regression on 3,367 sessions, against a predict-the-mean baseline of approximately 10 years MAE. With light task-specific fine-tuning of the model's final layers, the same pretrained encoder achieves rank-1 placements - with the model's native 30-second windows - on the public NeuralBench x this http URL EEG leaderboard for sex classification (balanced accuracy 0.911), age prediction (r = 0.749), and psychopathology composite regression (r = 0.215). We further show that the model's age-prediction residual is negatively correlated with cognitive efficiency over several tasks we examined.
### Title:
          At-Grok Is Not Converged:A Measurement-Validity Audit for Grokking Representation Metrics
 - **Authors:** Truong Xuan Khanh
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 On modular arithmetic, a network's embedding keeps compressing for tens of thousands of steps after it has already generalized. Reading effective rank at the grokking transition overstates the converged value by 3-5x on an MLP, and by 1.3-1.5x on a transformer trained to convergence; on the MLP it also erases which cells compress at all. Compression lags the accuracy transition by an amount on the order of the time-to-grok, at least 10,000 steps, rather than coinciding with it. A one-variable ablation shows what sets the lag size: adding LayerNorm to an otherwise identical transformer moves the fraction of compression done by the grok step from 0.87 to 0.25, and a pre-registered control rules out scale invariance as the mechanism. We package this as an audit that separates onset from compression, flags censoring, excludes boundary cells that never fully generalize, and checks that the reference floor has plateaued, with an adversarial suite that caught a false-confidence bug in our own branch. A secondary, MLP-specific depth law linking norm budget to converged floor fails a generality test on a transformer and flips sign under free weight decay. Code and the toolkit are released.
### Title:
          Dual Attention Heads for Personalized Federated Learning in ECG Classification
 - **Authors:** Kien Le, Joseph Lindley, Quoc Bao Phan, Tuy Tan Nguyen
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Federated learning (FL) enables collaborative model training across institutions without sharing sensitive patient data. However, the inherent heterogeneity of electrocardiogram (ECG) data across healthcare providers presents significant technical challenges for robust classification. We propose FedDualAtt, a personalized federated learning approach that splits transformer attention heads into global and local branches. Global heads are aggregated via FedAvg to capture shared cross-site patterns, while local heads remain client-specific to adapt to institution-level recording characteristics. Experiments on FedCVD, an FL benchmark for cardiovascular disease detection, demonstrate that FedDualAtt outperforms existing FL and personalized FL methods in ECG classification tasks. Analysis of global-local head ratios reveals that different clients benefit from varying levels of architectural personalization.
### Title:
          Enhancing deep learning models for time series classification via knowledge distillation
 - **Authors:** Javidan Abdullayev, Maxime Devanne, Jonathan Weber, Germain Forestier
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning has achieved remarkable success in various domains including time series analysis, computer vision and natural language processing. However, high computational and memory demands of state-of-the-art architectures pose challenges for deployment in resource-limited environments. Knowledge Distillation (KD) addresses this by transferring knowledge from a large teacher model to a smaller, more efficient student model while maintaining competitive performance. In this work, we investigate the effectiveness of KD for Time Series Classification (TSC) across three architectures: the classical Fully Convolutional Network (FCN), the convolutional Inception model and the transformer-based ConvTran model. We evaluate our approach on UCR Archive, the largest benchmark repository of time series datasets, by modifying architectural components such as convolutional filters, Inception modules and attention heads across the three architectures. Our results consistently show that KD most effectively benefits student models of intermediate complexity across all three architectures, with the distilled FCN student reducing parameters by a factor of 38, the distilled Inception student achieving nearly the same performance as the teacher with 42% fewer parameters and the distilled ConvTran student with 2 attention heads showing the most significant improvement through distillation. To encourage further research and reproducibility, we provide our implementation at this https URL.
### Title:
          Ad Headline Generation using Self-Critical Masked Language Model
 - **Authors:** Yashal Shakti Kanungo, Sumit Negi, Aruna Rajan
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 For any E-commerce website it is a nontrivial problem to build enduring advertisements that attract shoppers. It is hard to pass the creative quality bar of the website, especially at a large scale. We thus propose a programmatic solution to generate product advertising headlines using retail content. We propose a state of the art application of Reinforcement Learning (RL) Policy gradient methods on Transformer based Masked Language Models. Our method creates the advertising headline by jointly conditioning on multiple products that a seller wishes to advertise. We demonstrate that our method outperforms existing Transformer and LSTM + RL methods in overlap metrics and quality audits. We also show that our model-generated headlines outperform human submitted headlines in terms of both grammar and creative quality as determined by audits.
### Title:
          CaLiSym: Learning Symplectic Dynamics of Real-World Systems through Structured Canonical Lifts
 - **Authors:** Aristotelis Papatheodorou, Pranav Vaidhyanathan, Natalia Ares, Ioannis Havoutis, Gerard J. Milburn
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physics-informed learning promises data-efficient and stable dynamics prediction, yet its strongest geometric guarantees have largely remained confined to closed conservative systems. This excludes many robotic systems of practical interest, where actuation, dissipation, and constraints continuously exchange energy and momentum with the environment. We introduce CaLiSym, a lightweight framework that extends exact symplectic learning to such systems by changing where the geometric prior is imposed. Rather than enforcing symplecticity on the measured physical state, CaLiSym embeds the state and its physical ports into a structured lifted canonical phase space, where the learned dynamics evolve through an exactly symplectic map. The lift is explicit and algebraic, requiring neither recurrent latent states, transformer decoders, implicit optimization, nor inference-time ODE integration. We instantiate the framework with generalized-ridge SympNet predictors and introduce GRB-SympNet, a B-spline variant that combines local approximation with exact symplectic structure. Experiments on a controlled dissipative double pendulum, a real-world quadrotor, and a contact-rich quadruped demonstrate consistent improvements in out-of-distribution autoregressive prediction while using parameter-efficient models. At the same time, the learned lifted dynamics preserve the symplectic form to numerical precision. These results show that symplectic learning can be extended beyond conservative mechanics through structured canonical lifts, enabling geometry-preserving dynamics models for real-world robotic systems.
### Title:
          LoCA: Spatially-Aware Low-Rank Convolutional Adaptation of Vision Foundation Models
 - **Authors:** Sojung An, Junha Lee, Sujeong You, Nam Ik Cho, Donghyun Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pre-trained Vision Foundation Models (VFMs) provide strong visual representations for diverse downstream tasks. The key challenge of VFM adaptation stems from the prohibitive costs of full fine-tuning and catastrophic forgetting. To address this, Low-Rank Adaptation (LoRA) has emerged as the prevailing paradigm for Parameter-Efficient Fine-Tuning (PEFT). However, LoRA is typically designed for transformer self-attention layers parameterized by 2D matrices. Since convolutional kernels inherently couple spatial and channel information within a 4D tensor, forcing them into a monolithic 2D matrix disrupts the inherent spatial topology. In this paper, we propose Low-Rank Convolutional Adaptation (LoCA), a convolution-aware PEFT framework that addresses spatial-channel entanglement by decoupling channel and spatial adaptation. LoCA introduces a low-rank channel adaptation for dense cross-channel mixing and refines spatial bases extracted from pre-trained kernels via Singular Value Decomposition (SVD). Experimental results show that LoCA preserves pre-trained spatial priors and achieves competitive or state-of-the-art performance across fine-grained classification, domain-generalized semantic segmentation, and generative benchmarks.
### Title:
          Compass: Prostate Cancer Detection Needs Multi-View Context
 - **Authors:** Paul F.R. Wilson, Mohamed Harmanani, Zhuoxin Guo, Obed K. Dzikunu, Hannes Cash, Adam Kinnaird, Brian Wodlinger, Purang Abolmaesumi, Parvin Mousavi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artificial intelligence (AI) analysis of micro-ultrasound ($\mu$US) has shown promise for prostate cancer (PCa) detection. However, most existing AI methods focus on the analysis of single $\mu$US images in isolation. By contrast, expert $\mu$US readers typically assess a full recorded video study, which provides three-dimensional context, to improve PCa detection compared to single-frame analysis. Inspired by this clinical workflow, we propose Compass, a novel AI methodology which models a $\mu$US study as a stream of 2D images. Compass jointly integrates rotational sweep videos of the prostate with $\mu$US frames acquired at the moment of biopsy, and performs evidence aggregation across the study using a transformer conditioned on the probe's rotational angle. Finally, a decoder head predicts frame-level and study-level risk scores for the patient. The model is trained and evaluated using a multi-center clinical trial dataset of $\mu$US studies, including continuous rotational scans of the prostate and videos captured during biopsy acquisition. We compare the proposed method to baseline AI methods from the literature and to risk scores provided by clinical experts. Our framework shows strong performance, highlighting the value of multi-view context for $\mu$US PCa detection, and providing a potentially powerful tool to complement human expertise in $\mu$US-based PCa diagnosis. Our code is available at: this https URL.
### Title:
          Self-Supervised Pretraining Improves Cross-Site and Cross-Scale Robustness of Point Cloud Leaf-Wood Segmentation
 - **Authors:** Heeju Mun, Tackang Yang, Yunsoo Nam, Changhyun Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The accuracy of existing leaf-wood segmentation methods for tree point clouds varies across forest types and sites. Self-supervised learning (SSL) on point clouds has improved the generalization of deep learning models for forestry point cloud tasks, including biomass regression and individual tree segmentation, but its applicability to leaf-wood segmentation remains untested. In this study, we pretrained Point-M2AE, a widely used SSL architecture for point clouds, on ShapeNet-55 augmented with 2,400 individual tree point clouds. For fine-tuning and inference, we used recursive voxel subdivision to handle the wide variation in point density across inputs, allowing the same model to operate at both individual-tree and plot scales without architecture change. Compared to the model without pretraining, the pretrained model improved wood IoU from 60.5% to 70.0% for needleleaf and from 69.7% to 76.3% for broadleaf trees. On a benchmark spanning four countries across three climatic zones, the pretrained model achieved the smallest cross-site variation and highest overall performance among compared methods (LeWos, CWLS, and PointTransformer). Plot-level segmentation maintained accuracy comparable to individual-tree performance, with mIoU of 84.7% for broadleaf and 77.7% for needleleaf plots, showing that the model generalizes across scales without additional finetuning. As a downstream test in tropical forests, where dense canopies make segmentation challenging, we applied our model and a quantitative structure model to estimate wood volume for 28 trees from Guyana, Indonesia, and Peru to assess whether the segmentation improvements from SSL pretraining translate into improved downstream performance. The resulting volume estimates achieved the lowest error among all methods tested (MAE = 2.40 m$^3$), less than half that of algorithmic baselines (LeWos: 5.94 m$^3$; CWLS: 5.27 m$^3$).
### Title:
          Physics-guided spatiotemporal neural models for fuel density prediction
 - **Authors:** Tolga Caglar, Jaynil Jaiswal, Saqib Azim, Yudhir Gala, Mai H. Nguyen, Ilkay Altintas
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a physics-guided machine learning (PGML) framework for fuel density prediction, integrating physics constraints and domain knowledge into deep learning models to enhance model accuracy and stability. We explore three deep learning architectures -- ConvLSTM, Adaptive Fourier Neural Operator (AFNONet), and Video Vision Transformer (ViViT) -- to model the spatiotemporal evolution of fuel density. Our approach incorporates differentiable physics-informed terms in the loss function, including a mass-conserving fuel transport term and a rate-of-spread estimation. Experimental results, averaged across multiple independent trials, demonstrate that the proposed PGML framework outperforms purely data-driven baselines without physics constraints in both accuracy and stability. This framework enables computationally efficient, physically plausible fire forecasting to support adaptive prescribed burn management.
### Title:
          Latent graph encoding of multimodal neuroimaging features with generative AI architectures
 - **Authors:** Ishaan Batta, Meenu Ajith, Vince Calhoun
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While generative models enable encoding of complex neuroimaging data for feature generation and reconstruction, developing optimal architectural frameworks with appropriate encoding and latent space processes is crucial for studying structural and functional properties of the brain. We design a multimodal generative framework for structural and functional magnetic resonance imaging (MRI) features through systematic evaluation of encoding strategies, latent multimodal fusion, and generative model selection. Using structural gray matter volume (GMV) and static functional network connectivity (sFNC) features from a large neuroimaging dataset, we analyze generative frameworks involving variational autoencoders (VAEs), transformers, generative adversarial networks (GANs), and diffusion models. Architectures that employ modality-aware graph encoding of functional connectivity into a lower-dimensional latent space outperform vectorized encoders or direct data space approaches. The proposed multimodal graph VAE (gMMVAE) surpasses alternative generative variants across multiple metrics for generation fidelity, reconstruction quality, efficiency, and latent space discriminability, highlighting its potential for robust multimodal neuroimaging analysis.
### Title:
          Multiplication Beyond Groups: Stratified Fourier Mechanisms in Transformer Circuits
 - **Authors:** Zitong Andrew Chen, Junaid Hasan, Akhil Srinivasan, Hemkesh Bandi, Jarod Alper
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Number Theory (math.NT); Representation Theory (math.RT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have demonstrated a remarkable ability to learn algorithmic reasoning, yet mechanistic analyses have mostly focused on globally invertible operations such as cyclic addition and group composition. In this work, we investigate how small transformers learn modular integer multiplication over composite moduli, a fundamentally non-invertible operation due to the presence of zero-divisors. We propose the monoid extension: a localized generalization of Group Composition via Representation (GCR) that suggests the learned computation does not rely on a single global representation space. Instead, the model partitions the input space into local hierarchical algebraic regions, where group-like structure survives and Fourier mechanisms can be applied. In transformers trained on square-free modular multiplication, we find that embeddings organize around these regions, attention exhibits class-sensitive routing and low-rank write directions, and local character features explain a large fraction of the model's output logits. Our results suggest that representation-theoretic mechanisms previously identified for group operations can extend beyond groups to more general structures.
### Title:
          Vision Foundation Models in Radiology: A Scoping Review of Data, Methodology, Evaluation and Clinical Translation
 - **Authors:** Alejandro Vergara-Richart (1 and 2), Xavier Rafael-Palou (1), Almudena Fuster-Matanzo (1), Ignacio Iborra Roncales (1), Ángel Alberich-Bayarri (1), Ana Jiménez-Pastor (1) ((1) Quantitative Imaging Biomarkers in Medicine, Quibim S.L., València, Spain, (2) Universitat Politècnica de València, València, Spain)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision foundation models (VFMs) are increasingly being developed for radiological imaging, yet their definition, development and evaluation remain heterogeneous. We conducted a PRISMAScR scoping review of peer-reviewed studies published between January 2017 and March 2026 describing foundation models trained exclusively on radiological imaging data. Sixty-seven studies were included and mapped across three pillars: data scale and heterogeneity, architectural and pretraining scalability, and downstream transferability and generalization. Datasets primarily covered brain MRI, thoracoabdominal CT, and chest X-ray, ranging from fewer than 100,000 samples to multi-million-image cohorts. Transformer-based architectures and self-supervised pretraining predominated, particularly masked image modeling, contrastive learning and multi-stage approaches. Evaluation focused mainly on segmentation and classification, whereas cross-center, cross-scanner, anatomical and modality-shift validation was inconsistently reported. Alignment with FUTURE-AI principles was uneven. Overall, radiology-specific VFMs show promising transferability, but clinical translation remains constrained by limited data representativeness, heterogeneous benchmarks, incomplete reporting and insufficient deployment-oriented evaluation.
### Title:
          `Attention-Guided Cross-Temporal Clustering for Self-Supervised Video Object Segmentation
 - **Authors:** Waqas Arshid, Mohammad Awrangjeb, Alan Wee-Chung Liew, Yongsheng Gao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video object segmentation (VOS) is a fundamental task in video understanding, requiring accurate delineation and consistent tracking of objects across frames. While supervised methods achieve strong performance, they rely on densely annotated datasets that are costly to obtain and have limited domain coverage. Self-supervised learning offers a promising alternative by removing the need for manual labels; however, existing approaches often struggle to jointly maintain spatial accuracy and temporal coherence, particularly in unconstrained multi-object scenarios. Many rely on optical flow, synthetic motion cues, or task-specific pretraining, limiting scalability and generalisation. We propose a self-supervised framework, Cross-Temporal Consistency and Clustering, that learns mid-level, part-aware representations by combining attention-guided token selection with lightweight temporal clustering. Instead of operating at the pixel or whole-object level, the method aligns soft part assignments across time using a saliency-weighted symmetric consistency objective. The framework leverages a frozen transformer backbone with lightweight modules for adaptive token selection and multi-offset temporal alignment, enabling efficient scaling across resolutions and motion patterns.
### Title:
          Mechanistic Interpretability for Neural Networks: Circuits, Sparse Features and Symbolic Reasoning
 - **Authors:** Pranav Sawant, Jakub Krejčí
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This article offers a comprehensive overview of mechanistic interpretability, an emerging field that seeks to reverse-engineer the internal algorithms of modern neural networks. While traditional explainable AI methods often stop at surface-level input-output correlations, this approach directly addresses the opaque "black box" nature of machine learning models, which is essential for ensuring safety and auditability in high-stakes deployments. The paper provides a detailed examination of Transformer circuit analysis, exploring how internal components like the residual stream, attention mechanisms, and induction heads drive complex tasks and in-context learning. It subsequently tackles the core challenge of superposition and polysemanticity, demonstrating how tools like Sparse Autoencoders (SAEs) and transcoders can decompose tangled network activations into distinct, human-interpretable features. Furthermore, the paper explores methods for actively controlling and modifying model behavior through steering vectors and causal interventions. Finally, it connects these mechanistic insights with neurosymbolic AI frameworks designed to translate neural representations into explicit, executable logical rules.
### Title:
          HumAIN: Human-Aware Implicit Social Robot Navigation
 - **Authors:** Daeun Song, Nhat Le, Jeffrey Chen, Mohammad Nazeri, Amirreza Payandeh, Rohan Chandra, Reuth Mirsky, Ross Mead, Ling Xiao, Xuesu Xiao
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective social robot navigation requires sensitivity to human behavior, often revealed through subtle skeletal cues like gait and orientation. We present Human-Aware Implicit Social Robot Navigation (HumAIN), a novel framework that fuses implicit social cues directly into the planning loop via knowledge distillation. We first employ a transformer-based teacher model that fuses rich multi-modal inputs, including historic images, skeletal keypoints, robot state, and a robot's target goal, to learn robust, human-aware representations for the robot's future trajectory planning. To enable real-time deployment, we then distill this knowledge into a lightweight student model. By optimizing for both trajectory reconstruction and latent feature alignment with the teacher, the student learns to infer complex social dynamics from minimal inputs. Bridging the prediction-planning gap with an efficient distilled architecture, our method enables robots to reason about human behavior in a manner that is adaptive, robust, and socially compliant. We validate HumAIN through extensive experiments, where it improves trajectory prediction metrics by an average of 29.8% across all metrics compared to state-of-the-art baselines. These results highlight the benefit of using implicit, whole-body cues to achieve human-like navigation awareness on resource-constrained platforms.
### Title:
          On Adversarial Vulnerability of Vision-Language Models through the Lens of Intermediate Spectral Subspaces
 - **Authors:** Chethan Krishnamurthy Ramanaik, Tobias Callies, Michael Hecht, Eirini Ntoutsi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adversarial vulnerability in deep neural networks (DNNs) has been studied from the perspectives of decision-boundary geometry, feature robustness, input-output Jacobians, and the instability of inverse problems. Here, we focus on the spectral structure of intermediate linear transformations that propagate information through modern DNNs, an unexplored mechanism of adversarial vulnerability. Specifically, we investigate transformer-based vision-language models, whose linear layers admit interpretable spectral decompositions and whose widespread adoption makes understanding their robustness increasingly important. We propose a white-box spectral-subspace-guided attack (SSGRA) that aligns intermediate representations with the subspace spanned by the bottom right singular vectors. Our experiments show improved attack effectiveness over existing baselines. In addition, SSGRA offers a spectral interpretation of adversarial vulnerability in VLMs, providing insights for improving their robustness.
### Title:
          Sparse Delta Memory: Scaling the State of Linear RNNs through Sparsity
 - **Authors:** Loïc Cabannes, Pierre-Emmanuel Mazaré, Gergely Szilvasy, Matthijs Douze, Maria Lomeli, Ilze Amanda Auzina, Justin Carpentier, Gabriel Synnaeve, Hervé Jégou
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Linear attention models allow a fixed state size and a fixed amount of compute per token. However, due to their limited state size, linear attention models fall behind in long-context recall compared to softmax-attention-based transformer architectures. Increasing the state size of linear attention improves recall performance but at the cost of higher FLOPs. In this work, we introduce Sparse Delta Memory (SDM), an architecture that scales the hidden state of gated linear RNNs to orders of magnitude higher capacity using a sparse addressing scheme. SDM extends the Gated DeltaNet architecture by replacing the dense key-value outer product with sparse reads and writes to a large explicit memory. We show that, under an isoFLOP constraint and with an identical number of parameters, a higher state memory capacity significantly improves performance on in-context learning and long-context retrieval tasks. Moreover, by learning the initial state of the SDM memory and therefore using it as a parametric memory, we show that the model further improves on a wide range of common-knowledge and reasoning tasks.
### Title:
          TF-Engram: A Train-Free Engram with SSD-Backed Memory for Large Language Models
 - **Authors:** Yutang Ma, Kecheng Huang, Xikun Jiang, Zili Shao
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) store factual knowledge and domain-specific patterns implicitly in dense Transformer parameters, making knowledge expansion costly through pretraining, fine-tuning, retrieval augmentation, or longer contexts. Engram-style memory offers a compact hidden-state injection pathway, but existing GPU-resident designs often rely on hash-based compression, causing unrelated phrases to collide in shared slots and weakening phrase-level semantic fidelity. We present TF-Engram, a train-free Engram system that constructs phrase-specific semantic memory offline from external corpora, stores large memory tables across a GPU--DRAM--SSD hierarchy, and uses Early-Exit Guided Predictive Prefetching to hide external-memory latency during autoregressive decoding. On Qwen3-0.6B, TF-Engram improves the average downstream score from 57.6 to 59.4, outperforming both the frozen backbone and a parameter-matched LoRA baseline. System evaluation shows that large TF-Engram tables can be built with moderate offline cost, SSD-backed storage substantially reduces GPU memory demand, and predictive prefetching recovers much of the throughput loss caused by external memory access. These results demonstrate that static phrase memory can be integrated into LLM inference as a scalable, train-free, and low-overhead system component.
### Title:
          FourierQK: Spectral Preprocessing of Query-Key Projections Improves Transformer Attention
 - **Authors:** Athanasios Zeris
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 FFT-based spectral preprocessing of learned query-key (Q/K) projections substantially improves transformer attention on character-level language modelling. On TinyShakespeare: a fixed random spectral filter achieves val=1.031 (Delta=+0.443); a single learned frequency at paragraph scale achieves val=0.608 (Delta=+0.867); and four learned frequencies spanning paragraph to word scale achieve val=0.309 (Delta=+1.166), a 79% reduction over standard dot-product attention. The single-frequency result is confirmed across three random seeds (mean val=0.236, std=0.019). The four frequencies converge to a near-geometric multi-scale ordering (49, 27, 10, 6 tokens/cycle) corresponding to paragraph, sub-paragraph, phrase, and word scales. The gain is specific to spectral preprocessing: random orthogonal and non-orthogonal projections of Q/K produce no measurable improvement, suggesting the benefit comes from global frequency-domain mixing rather than metric distortion. All results are verified by a shuffled-validation diagnostic against positional leakage. Causal filters (Gaussian, Mexican Hat, Morlet) do not improve over standard attention at character-level tokenisation: the bilateral FFT kernel is structurally non-causal, coupling every position to future tokens. This defines an architectural boundary between bilateral spectral attention (this paper) and genuinely causal spectral attention at word-scale tokenisation (companion paper MorletQK). This work is architecturally distinct from FNet (Lee-Thorp et al., 2021), which replaces attention with Fourier mixing of token embeddings. Here, spectral preprocessing applies only to Q/K projections while the full attention score structure is preserved.
### Title:
          Generating Personalized Lower-Limb Kinematics Across Walking Speeds Using Subject-Conditioned Diffusion
 - **Authors:** Diya Dinesh, Adrian Krieger, Changseob Song, Dongho Park, Aaron J. Young, Inseung Kang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Personalizing exoskeleton assistance requires user-specific gait data across many locomotor tasks, yet collecting this data demands repeated motion capture sessions that are costly, time-intensive, and especially burdensome for clinical populations. This challenge is most acute across walking speeds, where gait changes substantially and deviates further in clinical gait. This work introduces a subject-conditioned residual diffusion framework that generates personalized lower-limb kinematics at unseen walking speeds from a subject's gait sequence at a single seen speed. Given sagittal-plane hip, knee, and ankle trajectories at a seen speed and a desired unseen speed, the model generates a residual that transforms the seen trajectory into the unseen one, using a transformer denoiser conditioned on the subject's gait and the two speeds through feature-wise linear modulation. Trained only on able-bodied data, the model achieved a mean absolute error (MAE) of 3.4° on held-out able-bodied subjects. Without any stroke-specific fine-tuning, it achieved a 6.0° MAE on out-of-training-distribution stroke subjects, retaining subject identity for clinical gait. The framework reduced the MAE by over 70% relative to supervised feed-forward baselines, and a single seen speed matched the accuracy of four speeds within 0.4°. These results demonstrate that subject-conditioned residual diffusion can synthesize personalized gait across speeds from minimal data, reducing the collection burden for downstream exoskeleton personalization.
### Title:
          AA-ViT: Anatomically Aware Vision Transformer with Structural and Frequency Guidance for Contrast Enhanced Brain MRI Synthesis
 - **Authors:** Talha Meraj, Tom Flannery, Charlie Cummins, Matt Townend, Thomas C Booth, Peter Crossley, Michael McCann, Ian Overton, Saritha Unnikrishnan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate tumour localization and diagnosis is a critical component of clinical care for brain cancers. Magnetic Resonance Imaging (MRI) is the most commonly used imaging modality due to its superior soft-tissue contrast. However, standard MRI often exhibits limited contrast and imaging artifacts, which necessitates the use of contrast agents to enhance lesion visibility. The administration of chemical contrast agents is not always feasible and may be contraindicated in patients with renal impairment or other health conditions. As a result, developing accurate and non-invasive contrast enhanced MRI (CEMRI) synthesis methods has clinical importance. In recent years, numerous approaches for CEMRI synthesis have been proposed, predominantly relying on generative artificial intelligence models. While these methods demonstrate promising performance, their dependence on implicit feature learning often limits their ability to preserve anatomical boundaries and tumour-specific fine structures. To address these challenges, we propose an anatomically aware frequency-and-structure-guided vision transformer (AA-ViT), for CEMRI synthesis using pre-contrast MRI modalities (T1, T2, and FLAIR). Experiments on the BraTS 2021 dataset demonstrate that the proposed method preserves anatomical and lesion boundaries, achieving higher PSNR and SSIM than state-of-the-art approaches. Clinical evaluation by three neuroradiologists and a neurosurgeon on 19 randomly selected cases across diverse gliomas yielded a mean score of 3.94/5, providing preliminary clinical validation rarely seen in prior studies. Synthetic post-contrast scans from our model could lower scanning costs, shorten imaging time, and avoid the potential risks of using gadolinium-based contrast agents.
### Title:
          PALS: Percentile-Aware Layerwise Sparsity for LLM Pruning
 - **Authors:** Yazdan Jamshidi, Alexey Shvets
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 One-shot pruning methods like Wanda and SparseGPT apply the same sparsity ratio to every layer of a transformer, ignoring known variation in layer importance. We propose PALS (Percentile-Aware Layerwise Sparsity), which adjusts per-layer sparsity based on the 99th percentile of activation magnitudes, bounded to $\pm 5\%$ around the target ratio. On LLaMA-2-7B at 50\% sparsity, PALS achieves 10.96 WikiText-2 perplexity versus 12.92 for uniform Wanda (mean over 9 runs, $p < 0.001$). The benefit is architecture-dependent: LLaMA-3-8B shows marginal gains and Mistral-7B shows none. We also find that gradient-based allocation -- the seemingly more principled approach -- produces results worse than random, suggesting that gradient magnitude does not predict the impact of discrete weight removal. PALS adds negligible cost to the pruning pipeline and requires no fine-tuning.
### Title:
          Multi-Class vs. Multi-Label BERT for CVE-to-CWE Mapping: How Taxonomy Structure Shapes the Errors
 - **Authors:** Ana Schwengber Kelm, Christian Bockermann, Jörg Frochte
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Assigning Common Weakness Enumeration (CWE) categories to Common Vulnerabilities and Exposures (CVE) records remains an important but largely manual step in vulnerability analysis. We study this task as a text classification problem and compare two modelling choices: a \emph{multi-class} formulation that predicts a single CWE per CVE and a \emph{multi-label} formulation that allows multiple assignments. Three transformer encoders (BERT Base, SecureBERT, and CySecBERT) are evaluated on three nested label spaces (83, 47, and 25 classes). Multi-class training achieves higher macro-F1 across all settings, although the gap to multi-label narrows from 21 to 2 percentage points as the label space shrinks. Post-hoc threshold optimisation on the multi-label side closes this gap on the 25-class setting. Confusion analysis shows that the dominant misclassification patterns follow the CWE hierarchy and are shared across all three encoders (Pearson $r > 0.92$), which suggests that the error structure is driven more by taxonomy design than by encoder choice. A hierarchy-relaxed evaluation that forgives within-family confusions raises macro-F1 from ${\sim}$81\% to ${\sim}$90\%, indicating that strict metrics understate branch-level classifier quality. CySecBERT achieves the strongest results overall, with statistically significant gains concentrated in the multi-label setting.
### Title:
          ATLAS: Automated HLS for DL-Optimized FPGAs
 - **Authors:** Ruthwik Reddy Sunketa, Aman Arora
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 FPGA architectures increasingly incorporate domain-specific in-fabric hardblocks to accelerate DL inference, particularly GEMM, which dominates DL computation. To realize the performance gains of these hardblocks, manual RTL design is required: the programmer must understand the hardblock microarchitecture, instantiate them in RTL, and manage tiling and control logic. While programming in C/C++ and using HLS tools has increased the abstraction level and productivity of FPGA engineers, HLS tools do not support code generation for custom hardblocks natively. Prior work has demonstrated that blackbox mechanisms in HLS tools can be used to target custom hardblocks, but this still requires explicit function calls in user-written HLS C and manual creation of RTL IP libraries, significant effort that must be repeated for every layer in a DL model. Furthermore, for DL, an even high-level programming interface, e.g., Pytorch/Keras instead of C/C++, is desirable for improved programmability and user adoption. We present ATLAS, a fully automated flow from a high-level DL model description to a hardware implementation on an FPGA with custom in-fabric DL-optimized hardblocks, requiring no manual RTL design or explicit hardblock instantiation from the end user. Our approach uses GEMM as a universal abstraction layer and comprises two components: (1) hls4ml-GEMM, a compiler frontend that transforms DL layers into HLS C code with architecture-agnostic GEMM function calls, and (2) a GEMM IP Generator, an architecture-aware backend that produces hardblock-based RTL wrappers with tiling logic, control FSMs, and scheduling metadata. We evaluate the flow across 11 DL designs, including individual fully connected, convolution, and attention layers, as well as full CNN, MLP, and Transformer models targeting an FPGA architecture with Tensor Slices using Catapult for HLS and VTR for implementation.
### Title:
          RL Post-Training Builds Compositional Reasoning Strategies
 - **Authors:** Azwar Abdulsalam, Nishil Patel, Andrew Saxe
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Does RL post-training merely amplify primitive skills already latent in a base model, or can it compose primitive skills into new higher-level strategies? We study this question in a fully observable rewrite-grammar environment where the pretraining distribution is known and every generated rewrite can be audited. A Transformer is pretrained on primitive symbol-rewrite chains and post-trained on a Trace-based reasoning task with only a binary final-answer reward. RL solves held-out problems that remain rarely solved by the pretrained model even under much larger sampling budgets, while rejection fine-tuning improves early but plateaus. Trace analysis shows that RL reorganizes primitive competence through a phased compositional mechanism: it first strengthens primitive reductions, then discovers valid composed procedures. These include sequential compositions, which collapse ordered chains of primitive contractions, and parallel compositions, which combine independent primitive contractions in a single step. The composed procedures are not isolated samples; they are reused and consolidated into a stable repertoire. Comparing RL with rejection fine-tuning shows that the key difference is not exploration volume but selectivity: RFT produces many shortcut-like rewrites, much of them invalid, whereas RL concentrates exploration into valid reusable structure. Pretraining ablations show that the emergence of compositional strategies is gated not by primitive exposure alone, but by whether pretraining organizes primitive competence into reduction procedures that RL can later compress. The base model provides weak procedural ingredients; RL builds them into reliable higher-level strategies.
### Title:
          How Data Shapes RoPE Frequency Usage: From Positional Scale Matching to Length Generalization
 - **Authors:** Xinyi Wu, Siyuan Liu, Ali Jadbabaie
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rotary Position Embeddings (RoPE) provide transformers with a fixed grid of positional frequencies, yet trained models use these frequencies highly non-uniformly. We study what determines this frequency usage and propose a data-centered explanation: RoPE frequencies are selected to match the relative-distance structure of the training data. Viewing each frequency as a positional lens, we formalize a field-resolution tradeoff and show that, for a data-induced dependency profile of width $W$, the optimal frequency scales as $1/W$. This frequency-matching principle explains controlled observations on synthetic and text-based data, and suggests that the mid-low frequency bands observed in language models arise from the multi-scale dependency structure of natural language. We further connect frequency selection to position-interpolation-based length generalization: scaling frequencies down expands the effective field while reducing resolution. This helps when longer-context dependencies are approximate dilations of those seen during training, but can fail when relevant dependencies do not scale with context length. Empirically, we show that natural language exhibits approximate self-similarity across positional scales, explaining why test-time frequency scaling can support long-context generalization. Overall, our results identify a data-driven mechanism behind emergent RoPE frequency usage and show that long-context generalization depends on two forms of scale matching: between learned frequencies and training-time dependencies, and between frequency scaling and how those dependencies extend to longer contexts.
### Title:
          The Key to Going Linear: Analysis-Driven Transformer Linearization
 - **Authors:** Anna Kuzina, Paul N. Whatmough, Babak Ehteshami Bejnordi
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The quadratic cost of causal self-attention severely bottlenecks long-context transformer inference. While numerous post hoc linearization pipelines exist, it is difficult to identify which components preserve model quality. This work isolates the effect of state update design in a strict frozen-backbone regime. We show that softmax relies on key-dependent, rank-1 orthogonal projections, elucidating why delta-style networks outperform purely gated accumulation. We identify a potential source of approximation errors and introduce structural interventions, specifically sink tokens, short convolutions, and fixed-budget cache routing, which reduces the remaining gap. We scale this linearization approach across LLaMA and Qwen models up to 32B parameters, outperforming prior post hoc baselines on MMLU and matching the long-context retrieval of complex adaptive-caching frameworks.
## Keyword: autonomous driving
### Title:
          Flow-ERD: Agent-type Aware Flow Matching with Entropy-Regularized Distillation for Diverse Traffic Simulation
 - **Authors:** Seulbin Hwang, Kiyoung Om, Daejung Kim, Jinhan Lee
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Realistic and diverse traffic simulation is essential to autonomous driving development. Yet prevailing benchmarks predominantly reward realism, and recent methods have optimized accordingly, leaving diversity underexplored. We introduce \textbf{Flow-ERD}, a multi-agent simulator that pursues realism and diversity jointly. Its backbone, \textbf{Agent-Type Aware Flow Matching} (AFM), couples flow matching's multi-modal expressiveness with type-specific kinematic execution. It preserves fine-grained diversity while keeping motions consistent with each agent type. A second stage, \textbf{Entropy-Regularized Distillation} (ERD), fine-tunes the closed-loop rollout distribution with an entropy-regularized reverse-KL objective. This mitigates covariate shift while explicitly preventing collapse onto high-density modes. We evaluate Flow-ERD with a log-free diversity metric alongside standard realism scores. Flow-ERD ranks first on the WOSAC test benchmark and dominates the realism--diversity Pareto front among reproducible baselines. Our project page is available \href{this https URL}{here}.
### Title:
          A knowledge-augmented dataset of high-risk driving scenarios with LLM annotations for autonomous driving
 - **Authors:** Heye Huang, Jingguang Li, Zhiyuan Zhou, Paul Liang, Mingyu Wu, Kitae Jang, Jianqiang Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safe autonomous driving requires both rapid responses to common high-risk events and deeper reasoning over rare, extreme long-tail scenarios in traffic safety. These scenarios are severely under-represented in naturalistic driving data, and existing trajectory and language-augmented datasets seldom provide high-risk event labels, semantic annotations, and verifiable safety signals. Here we present K-Risk, a knowledge-augmented dataset that combines structured driving trajectories with large language model generated semantic annotations for safety-critical driving scenarios. K-Risk integrates 20 human-driven and autonomous-vehicle trajectory datasets from Europe, China, and the United States, covering highways, urban freeways, intersections, and roundabouts. Using a unified risk-centric extraction pipeline, K-Risk curates 31,398 high-risk events, together with a 1,036-event extreme subset of near-collision cases. Each event is released as a synchronized trajectory, metadata, and language triplet containing structured scenario descriptions, abnormal-behavior notifications, and, for a representative subset, causal risk analyses and action recommendations validated through a closed-loop simulator with iterative reflection. By combining multi-dimensional risk annotations, interpretable language supervision, and verifiable decisions, K-Risk bridges structured traffic trajectories, semantic reasoning, and decision supervision, providing a standardized foundation for developing and evaluating next-generation risk-aware autonomous driving agents.
### Title:
          Validate the Dream Before You Trust Its Verdict: Admissibility for World-Model Simulators
 - **Authors:** Christian Oefinger, Finn Rasmus Schäfer, Korbinian Moller, Mattia Piccinini, Johannes Betz
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Across robotics, World Models (WMs) are increasingly used to evaluate action policies by simulating the consequences of actions in an imagined world, and returning a success or safety verdict. Yet a verdict is only as trustworthy as the WM that produced it, and the WM itself needs to be certified. In video-generation WMs, fidelity metrics such as Fréchet Video Distance (FVD) reward visual realism, but ignore whether the world responds correctly to the policy's actions, including those unseen in training. Classical simulation-based validation assumes a trusted simulator evaluating an untrusted policy, whereas generative WMs are themselves unverified learned artifacts. Hence, we argue that any WM used as a test oracle must first be accredited before its verdicts can serve as evidence. Building on credibility practices from safety-critical simulation, including Verification, Validation & Accreditation (VV&A), Safety of the Intended Functionality (SOTIF), and scenario-based testing standards, we define an admissibility ladder (L0-L4) that a WM must climb before its closed-loop verdicts are accepted as assurance evidence. Our framework is embodiment-agnostic, and is instantiated in autonomous driving (AD), where assurance methods for traditional simulation are most mature. Applied to two driving WMs, the lower rungs reveal a reversal: the model that ranks higher on visual generation quality (L0) ranks lower on action-following (L1-L2), so visual fidelity does not predict the action-robustness a closed-loop verdict depends on.
### Title:
          CARLA-GS: Decoupling Representation, Reasoning, and Physics Simulation for Autonomous Driving Corner-Case Synthesis
 - **Authors:** Kaicong Huang, Meng Ma, Ruimin Ke
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safety evaluation for autonomous driving is dominated by rare, safety-critical interactions, motivating simulators that can deliberately synthesize corner cases with photorealistic observations. Corner-case generation is inherently a multi-source problem spanning visual representation, scene reasoning, and vehicle trajectory generation and control. Prior knowledge- and model-based approaches typically focus on scene or trajectory components in isolation, while diffusion-based methods attempt end-to-end generation but still struggle to ensure spatiotemporal consistency and physical realism. To unify these aspects within a single framework, we propose CARLA-GS, a modular corner-case synthesis pipeline that decouples visual representation, semantic reasoning, and physics-based execution while maintaining tight cross-module coupling. Starting from real driving data, we reconstruct an editable gaussian scene with additional geometry-consistent constraints. A multi-agent LLM then performs scene-level reasoning to identify risky interactions and generate intent-level waypoint trajectories, while the low-level motion control is delegated to CARLA, where a PID controller ensures kinematic and dynamic feasibility. The simulated vehicle states are finally re-projected into the gaussian scene for ego-centric rendering. This design enables high-level semantic reasoning, low-level physically executable motion, and photorealistic corner-case generation within a unified pipeline. Experiments on the Waymo Open Dataset show, both quantitatively and qualitatively, that our framework enables controllable corner-case generation and produces photorealistic, spatiotemporally consistent videos aligned with semantic intent and physically feasible motion.
