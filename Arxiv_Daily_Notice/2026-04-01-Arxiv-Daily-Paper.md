# Showing new listings for Wednesday, 1 April 2026
## Keyword: SLAM
### Title:
          A Classification of Heterogeneity in Uncrewed Vehicle Swarms and the Effects of Its Inclusion on Overall Swarm Resilience
 - **Authors:** Abhishek Joshi, Abhishek Phadke, Tianxing Chu, F. Antonio Medrano
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Combining different types of agents in uncrewed vehicle (UV) swarms has emerged as an approach to enhance mission resilience and operational capabilities across a wide range of applications. This study offers a systematic framework for grouping different types of swarms based on three main factors: agent nature (behavior and function), hardware structure (physical configuration and sensing capabilities), and operational space (domain of operation). A literature review indicates that strategic heterogeneity significantly improves swarm performance. Operational challenges, including communication architecture constraints, energy-aware coordination strategies, and control system integration, are also discussed. The analysis shows that heterogeneous swarms are more resilient because they can leverage diverse capabilities, adapt roles on the fly, and integrate data from multidimensional sensor feeds. Some important factors to consider when implementing are sim-to-real-world transfer for learned policies, standardized evaluation metrics, and control architectures that can work together. Learning-based coordination, GPS (Global Positioning System)-denied multi-robot SLAM (Simultaneous Localization and Mapping), and domain-specific commercial deployments collectively demonstrate that heterogeneous swarm technology is moving closer to readiness for high-value applications. This study offers a single taxonomy and evidence-based observations on methods for designing mission-ready heterogeneous swarms that balance complexity and increased capability.
### Title:
          M2H-MX: Multi-Task Dense Visual Perception for Real-Time Monocular Spatial Understanding
 - **Authors:** U.V.B.L. Udugama, George Vosselman, Francesco Nex
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular cameras are attractive for robotic perception due to their low cost and ease of deployment, yet achieving reliable real-time spatial understanding from a single image stream remains challenging. While recent multi-task dense prediction models have improved per-pixel depth and semantic estimation, translating these advances into stable monocular mapping systems is still non-trivial. This paper presents M2H-MX, a real-time multi-task perception model for monocular spatial understanding. The model preserves multi-scale feature representations while introducing register-gated global context and controlled cross-task interaction in a lightweight decoder, enabling depth and semantic predictions to reinforce each other under strict latency constraints. Its outputs integrate directly into an unmodified monocular SLAM pipeline through a compact perception-to-mapping interface. We evaluate both dense prediction accuracy and in-the-loop system performance. On NYUDv2, M2H-MX-L achieves state-of-the-art results, improving semantic mIoU by 6.6% and reducing depth RMSE by 9.4% over representative multi-task baselines. When deployed in a real-time monocular mapping system on ScanNet, M2H-MX reduces average trajectory error by 60.7% compared to a strong monocular SLAM baseline while producing cleaner metric-semantic maps. These results demonstrate that modern multi-task dense prediction can be reliably deployed for real-time monocular spatial perception in robotic systems.
### Title:
          Semantic Zone-Based Map Management for Stable AI-Integrated Mobile Robots
 - **Authors:** Huichang Yun, Seungho Yoo
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in large AI models (VLMs and LLMs) and joint use of the 3D dense maps, enable mobile robots to provide more powerful and interactive services grounded in rich spatial context. However, deploying both heavy AI models and dense maps on edge robots is challenging under strict memory budgets. When the memory budget is exceeded, required keyframes may not be loaded in time, which can degrade the stability of position estimation and interfering model performance. We proposes a semantic zone-based map management approach to stabilize dense-map utilization under memory constraints. We associate keyframes with semantic indoor regions (e.g., rooms and corridors) and keyframe management at the semantic zone level prioritizes spatially relevant map content while respecting memory constraints. This reduces keyframe loading and unloading frequency and memory usage. We evaluate the proposed approach in large-scale simulated indoor environments and on an NVIDIA Jetson Orin Nano under concurrent SLAM-VLM execution. With Qwen3.5:0.8b, the proposed method improves throughput by 3.3 tokens/s and reduces latency by 21.7% relative to a geometric map-management strategy. Furthermore, while the geometric strategy suffers from out-of-memory failures and stalled execution under memory pressure, the proposed method eliminates both issues, preserving localization stability and enabling robust VLM operation. These results demonstrate that the proposed approach enables efficient dense map utilization for memory constrained, AI-integrated mobile robots. Code is available at: this https URL
## Keyword: odometry
### Title:
          Interacting Multiple Model Proprioceptive Odometry for Legged Robots
 - **Authors:** Wanlei Li, Zichang Chen, Shilei Li, Xiaogang Xiong, Yunjiang Lou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State estimation for legged robots remains challenging because legged odometry generally suffers from limited observability and therefore depends critically on measurement constraints to suppress drift. When exteroceptive sensors are unreliable or degraded, such constraints are mainly derived from proprioceptive measurements, particularly contact-related leg kinematics information. However, most existing proprioceptive odometry methods rely on an idealized point-contact assumption, which is often violated during real locomotion. Consequently, the effectiveness of proprioceptive constraints may be significantly reduced, resulting in degraded estimation accuracy. To address these limitations, we propose an interacting multiple model (IMM)-based proprioceptive odometry framework for legged robots. By incorporating multiple contact hypotheses within a unified probabilistic framework, the proposed method enables online mode switching and probabilistic fusion under varying contact conditions. Extensive simulations and real-world experiments demonstrate that the proposed method achieves superior pose estimation accuracy over state-of-the-art methods while maintaining comparable computational efficiency.
## Keyword: livox
There is no result 
## Keyword: loam
### Title:
          Koopman Operator Framework for Modeling and Control of Off-Road Vehicle on Deformable Terrain
 - **Authors:** Kartik Loya, Phanindra Tallapragada
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Robotics (cs.RO); Dynamical Systems (math.DS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents a hybrid physics-informed and data-driven modeling framework for predictive control of autonomous off-road vehicles operating on deformable terrain. Traditional high-fidelity terramechanics models are often too computationally demanding to be directly used in control design. Modern Koopman operator methods can be used to represent the complex terramechanics and vehicle dynamics in a linear form. We develop a framework whereby a Koopman linear system can be constructed using data from simulations of a vehicle moving on deformable terrain. For vehicle simulations, the deformable-terrain terramechanics are modeled using Bekker-Wong theory, and the vehicle is represented as a simplified five-degree-of-freedom (5-DOF) system. The Koopman operators are identified from large simulation datasets for sandy loam and clay using a recursive subspace identification method, where Grassmannian distance is used to prioritize informative data segments during training. The advantage of this approach is that the Koopman operator learned from simulations can be updated with data from the physical system in a seamless manner, making this a hybrid physics-informed and data-driven approach. Prediction results demonstrate stable short-horizon accuracy and robustness under mild terrain-height variations. When embedded in a constrained MPC, the learned predictor enables stable closed-loop tracking of aggressive maneuvers while satisfying steering and torque limits.
## Keyword: lidar
### Title:
          Bootstrap Perception Under Hardware Depth Failure for Indoor Robot Navigation
 - **Authors:** Nishant Pushparaju, Vivek Mattam, Aliasghar Arab
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a bootstrap perception system for indoor robot navigation under hardware depth failure. In our corridor data, the time-of-flight camera loses up to 78% of its depth pixels on reflective surfaces, yet a 2D LiDAR alone cannot sense obstacles above its scan plane. Our system exploits a self-referential property of this failure: the sensor's surviving valid pixels calibrate learned monocular depth to metric scale, so the system fills its own gaps without external data. The architecture forms a failure-aware sensing hierarchy, conservative when sensors work and filling in when they fail: LiDAR remains the geometric anchor, hardware depth is kept where valid, and learned depth enters only where needed. In corridor and dynamic pedestrian evaluations, selective fusion increases costmap obstacle coverage by 55-110% over LiDAR alone. A compact distilled student runs at 218\,FPS on a Jetson Orin Nano and achieves 9/10 navigation success with zero collisions in closed-loop simulation, matching the ground-truth depth baseline at a fraction of the foundation model's cost.
### Title:
          AutoWorld: Scaling Multi-Agent Traffic Simulation with Self-Supervised World Models
 - **Authors:** Mozhgan Pourkeshavatz, Tianran Liu, Nicholas Rhinehart
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-agent traffic simulation is central to developing and testing autonomous driving systems. Recent data-driven simulators have achieved promising results, but rely heavily on supervised learning from labeled trajectories or semantic annotations, making it costly to scale their performance. Meanwhile, large amounts of unlabeled sensor data can be collected at scale but remain largely unused by existing traffic simulation frameworks. This raises a key question: How can a method harness unlabeled data to improve traffic simulation performance? In this work, we propose AutoWorld, a traffic simulation framework that employs a world model learned from unlabeled occupancy representations of LiDAR data. Given world model samples, AutoWorld constructs a coarse-to-fine predictive scene context as input to a multi-agent motion generation model. To promote sample diversity, AutoWorld uses a cascaded Determinantal Point Process framework to guide the sampling processes of both the world model and the motion model. Furthermore, we designed a motion-aware latent supervision objective that enhances AutoWorld's representation of scene dynamics. Experiments on the WOSAC benchmark show that AutoWorld ranks first on the leaderboard according to the primary Realism Meta Metric (RMM). We further show that simulation performance consistently improves with the inclusion of unlabeled LiDAR data, and study the efficacy of each component with ablations. Our method paves the way for scaling traffic simulation realism without additional labeling. Our project page contains additional visualizations and released code.
### Title:
          Needle in a Haystack: Tracking UAVs from Massive Noise in Real-World 5G-A Base Station Data
 - **Authors:** Chengzhen Meng, Chenming He, Yidong Jiang, Xiaoran Fan, Dequan Wang, Lingyu Wang, Jianmin Ji, Yanyong Zhang
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The potential usage of UAVs in daily life has made monitoring them essential. However, existing systems for monitoring UAVs typically rely on cameras, LiDARs, or radars, whose limited sensing range or high deployment cost hinder large-scale adoption. In response, we develop BSense, the first system that tracks UAVs by leveraging point clouds from commercial 5G-A base stations. The key challenge lies in the dominant number of noise points that closely resemble true UAV points, resulting in a noise-to-UAV ratio over 100:1. Therefore, identifying UAVs from the raw point clouds is like finding a needle in a haystack. To overcome this, we propose a layered framework that filters noise at the point, object, and trajectory levels. At the raw point level, we observe that noise points from different spatial regions exhibit distinguishable and consistent signal fingerprints, which we can model to identify and remove them. At the object level, we design spatial and velocity consistency checks to identify false objects, and further compute confidence scores by aggregating these checks over multiple frames for more reliable discrimination. At the final trajectory level, we propose a Transformer-based network that captures multi-frame motion patterns to filter the few remaining false trajectories. We evaluated BSense on a commercial 5G-A base station deployed in an urban environment. The UAV was instructed to fly along 25 distinct trajectories across 54 cases over 7 days, yielding 155 minutes of data with more than 14,000 frames. On this dataset, our system reduces the number of false detections from an average of 168.05 per frame to 0.04, achieving an average F1 score of 95.56% and a mean localization error of 4.9 m at ranges up to 1,000 m.
### Title:
          Native-Domain Cross-Attention for Camera-LiDAR Extrinsic Calibration Under Large Initial Perturbations
 - **Authors:** Ni Ou, Zhuo Chen, Xinru Zhang, Junzheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate camera-LiDAR fusion relies on precise extrinsic calibration, which fundamentally depends on establishing reliable cross-modal correspondences under potentially large misalignments. Existing learning-based methods typically project LiDAR points into depth maps for feature fusion, which distorts 3D geometry and degrades performance when the extrinsic initialization is far from the ground truth. To address this issue, we propose an extrinsic-aware cross-attention framework that directly aligns image patches and LiDAR point groups in their native domains. The proposed attention mechanism explicitly injects extrinsic parameter hypotheses into the correspondence modeling process, enabling geometry-consistent cross-modal interaction without relying on projected 2D depth maps. Extensive experiments on the KITTI and nuScenes benchmarks demonstrate that our method consistently outperforms state-of-the-art approaches in both accuracy and robustness. Under large extrinsic perturbations, our approach achieves accurate calibration in 88% of KITTI cases and 99% of nuScenes cases, substantially surpassing the second-best baseline. We have open sourced our code on this https URL to benefit the community.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Legible Consensus: Topology-Aware Quorum Geometry for Asymmetric Networks
 - **Authors:** Tony Mason
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Quorum design over asymmetric topologies conflates two independent concerns: inter-tier obligation (which tiers must participate for cross-tier safety) and intra-tier replication (how each tier survives local failures). Flat quorums treat all nodes as interchangeable; when consensus fails, the structure does not reveal whether a tier was unreachable or a tier lost too many replicas. We show that mapping a crumbling-wall quorum construction to a physically tiered network separates these concerns and makes the protocol's failure modes legible: an operator can determine which tiers retain global consensus capability from the wall structure and connectivity state alone, without runtime probing. Using a 10-node Earth/LEO/Moon/Mars topology as a magnifying glass, we confirm that three of four tiers retain global liveness during Mars conjunction blackout; only the disconnected tier loses it. Consensus latency at each tier equals the speed-of-light round-trip to Earth: 183~ms (Earth), 131~ms (LEO), 5.1~s (Moon). The wall also imposes a leadership cost gradient on Multi-Paxos elections that symmetric grid quorums cannot express. A comparison between sparse and full-coverage topologies separates wall obligations from network reachability as independent liveness constraints. All results are design-level; quorum intersection is verified exhaustively in TLA+.
### Title:
          A Classification of Heterogeneity in Uncrewed Vehicle Swarms and the Effects of Its Inclusion on Overall Swarm Resilience
 - **Authors:** Abhishek Joshi, Abhishek Phadke, Tianxing Chu, F. Antonio Medrano
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Combining different types of agents in uncrewed vehicle (UV) swarms has emerged as an approach to enhance mission resilience and operational capabilities across a wide range of applications. This study offers a systematic framework for grouping different types of swarms based on three main factors: agent nature (behavior and function), hardware structure (physical configuration and sensing capabilities), and operational space (domain of operation). A literature review indicates that strategic heterogeneity significantly improves swarm performance. Operational challenges, including communication architecture constraints, energy-aware coordination strategies, and control system integration, are also discussed. The analysis shows that heterogeneous swarms are more resilient because they can leverage diverse capabilities, adapt roles on the fly, and integrate data from multidimensional sensor feeds. Some important factors to consider when implementing are sim-to-real-world transfer for learned policies, standardized evaluation metrics, and control architectures that can work together. Learning-based coordination, GPS (Global Positioning System)-denied multi-robot SLAM (Simultaneous Localization and Mapping), and domain-specific commercial deployments collectively demonstrate that heterogeneous swarm technology is moving closer to readiness for high-value applications. This study offers a single taxonomy and evidence-based observations on methods for designing mission-ready heterogeneous swarms that balance complexity and increased capability.
### Title:
          A Semantic Observer Layer for Autonomous Vehicles: Pre-Deployment Feasibility Study of VLMs for Low-Latency Anomaly Detection
 - **Authors:** Kunal Runwal, Swaraj Gajare, Daniel Adejumo, Omkar Ankalkope, Siddhant Baroth, Aliasghar Arab
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic anomalies-context-dependent hazards that pixel-level detectors cannot reason about-pose a critical safety risk in autonomous driving. We propose a \emph{semantic observer layer}: a quantized vision-language model (VLM) running at 1--2\,Hz alongside the primary AV control loop, monitoring for semantic edge cases, and triggering fail-safe handoffs when detected. Using Nvidia Cosmos-Reason1-7B with NVFP4 quantization and FlashAttention2, we achieve ~500 ms inference a ~50x speedup over the unoptimized FP16 baseline (no quantization, standard PyTorch attention) on the same hardware--satisfying the observer timing budget. We benchmark accuracy, latency, and quantization behavior in static and video conditions, identify NF4 recall collapse (10.6%) as a hard deployment constraint, and a hazard analysis mapping performance metrics to safety goals. The results establish a pre-deployment feasibility case for the semantic observer architecture on embodied-AI AV platforms.
### Title:
          A Computational Framework for Cross-Domain Mission Design and Onboard Cognitive Decision Support
 - **Authors:** J. de Curtò, Adrianne Schneider, Ricardo Yanez, María Begara, Álvaro Rodríguez, Javier López, Martina Fraga, Ignacio Gómez, Arman Akdag, Sumit Kulkarni, Siddhant Nair, Kiyan Govender, Eian Wratchford, Eli Lynskey, Seamus Dunlap, Cooper Nervick, Nicolas Tête, Rocío Fernández, Pablo González, Elena Municio, I. de Zarzà
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The design of distributed autonomous systems for operation beyond reliable ground contact presents a fundamental tension: as round-trip communication latency grows, the set of decisions delegable to ground operators shrinks. This paper establishes a unified computational methodology for quantifying and comparing this constraint across seven heterogeneous mission architectures, spanning Earth low-orbit surveillance constellations, Mars orbital navigation systems, autonomous underwater mine-clearing swarms, deep-space inter-satellite link networks, and outer-planet in-situ buoy platforms. We introduce the Autonomy Necessity Score, a log-domain latency metric mapping each system continuously from the ground-dependent to the fully-autonomous regime, grounded in nine independently validated computational studies covering Walker spherical-cap coverage mechanics, infrared Neyman-Pearson detection, Extended Kalman Filter hypersonic tracking, cross-mission RF and acoustic link budgets spanning seven orders of magnitude in range, Monte Carlo science-yield sensitivity for TDMA inter-satellite protocols, cross-architecture power budget sizing, distributed magnetic-signature formation emulation, and Arrhenius-corrected cryogenic swarm reliability. Building on this foundation, we evaluate an LLM-based Autonomous Mission Decision Support layer in which three foundation models (Llama-3.3-70B, DeepSeek-V3, and Qwen3-A22B) are queried live via the Nebius AI Studio API across ten structured anomaly scenarios derived directly from the preceding analyses. The best-performing model achieves 80% decision accuracy against physics-grounded ground truth, with all 180 inference calls completing within a 2 s latency budget consistent with radiation-hardened edge deployment, establishing the viability of foundation models as an onboard cognitive layer for high-ANS missions.
### Title:
          Attesting LLM Pipelines: Enforcing Verifiable Training and Release Claims
 - **Authors:** Zhuoran Tan, Jeremy Singer, Christos Anagnostopoulos
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern Large Language Model (LLM) systems are assembled from third-party artifacts such as pre-trained weights, fine-tuning adapters, datasets, dependency packages, and container images, fetched through automated pipelines. This speed comes with supply-chain risks, including compromised dependencies, malicious hub artifacts, unsafe deserialization, forged provenance, and backdoored models. A core gap is that training and release claims (e.g., data and code lineage, build environment, and security scanning results) are rarely cryptographically bound to the artifacts they describe, making enforcement inconsistent across teams and stages. We propose an attestation-aware promotion gate: before an artifact is admitted into trusted environments (training, fine-tuning, deployment), the gate verifies claim evidence, enforces safe loading and static scanning policies, and applies secure-by-default deployment constraints. When organizations operate runtime security tooling, the same gate can optionally ingest standardized dynamic signals via plugins to reduce uncertainty for high-risk artifacts. We outline a practical claims-to-controls mapping and an evaluation blueprint using representative supply-chain scenarios and operational metrics (coverage and decisions), charting a path toward a full research paper.
### Title:
          Gleanmer: A 6 mW SoC for Real-Time 3D Gaussian Occupancy Mapping
 - **Authors:** Zih-Sing Fu, Peter Zhi Xuan Li, Sertac Karaman, Vivienne Sze
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-fidelity 3D occupancy mapping is essential for many edge-based applications (such as AR/VR and autonomous navigation) but is limited by power constraints. We present Gleanmer, a system on chip (SoC) with an accelerator for GMMap, a 3D occupancy map using Gaussians. Through algorithm-hardware co-optimizations for direct computation and efficient reuse of these compact Gaussians, Gleanmer reduces construction and query energy by up to 63% and 81%, respectively. Approximate computation on Gaussians reduces accelerator area by 38%. Using 16nm CMOS, Gleanmer processes 640x480 images in real time beyond 88 fps during map construction and processes over 540K coordinates per second during map query. To our knowledge, Gleanmer is the first fabricated SoC to achieve real-time 3D occupancy mapping under 6 mW for edge-based applications.
### Title:
          Predictor-Based Output-Feedback Control of Linear Systems with Time-Varying Input and Measurement Delays via Neural-Approximated Prediction Horizons
 - **Authors:** Luke Bhan, Miroslav Krstic, Yuanyuan Shi
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Machine Learning (cs.LG); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Due to simplicity and strong stability guarantees, predictor feedback methods have stood as a popular approach for time delay systems since the 1950s. For time-varying delays, however, implementation requires computing a prediction horizon defined by the inverse of the delay function, which is rarely available in closed form and must be approximated. In this work, we formulate the inverse delay mapping as an operator learning problem and study predictor feedback under approximation of the prediction horizon. We propose two approaches: (i) a numerical method based on time integration of an equivalent ODE, and (ii) a data-driven method using neural operators to learn the inverse mapping. We show that both approaches achieve arbitrary approximation accuracy over compact sets, with complementary trade-offs in computational cost and scalability. Building on these approximations, we then develop an output-feedback predictor design for systems with delays in both the input and the measurement. We prove that the resulting closed-loop system is globally exponentially stable when the prediction horizon is approximated with sufficiently small error. Lastly, numerical experiments validate the proposed methods and illustrate their trade-offs between accuracy and computational efficiency.
### Title:
          Scalable and Near-Optimal Discrete Phase Shift Optimization for Reconfigurable Intelligent Surfaces with Over 20,000 Elements
 - **Authors:** Yuto Hama, Daisuke Kitayama, Kensuke Inaba, Toshimori Honjo, Hiroki Takesue, Naoki Ishikawa, Hiroyuki Takahashi
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes a novel optimization framework for discrete phase shifts of a reconfigurable intelligent surface (RIS) using a coherent Ising machine (CIM). Unlike conventional methods based on iterative convex approximation or combinatorial search with exponentially increasing complexity, the CIM physically explores the solution space of Ising Hamiltonians through collective mode competition in a network of optical oscillators, enabling efficient large-scale discrete optimization. We formulate the RIS discrete phase optimization problem as a quadratic Ising model, which supports both binary and quaternary phase shifts by appropriately mapping quantized phase states to spin variables. Using a real hardware CIM, we experimentally solve quadratic optimization problems for RISs with up to 22,201 elements. The results demonstrate that the proposed method achieves physically consistent beam patterns under both line-of-sight and non-line-of-sight environments and attains the theoretical gain when transitioning from binary to quaternary phase shift. To further enhance scalability, we introduce a spin-size reduction approach that removes spins deterministically fixed by dominant channel components. This technique efficiently reduces the problem size for CIM in line-of-sight conditions without performance loss. These results confirm that CIM-based optimization offers a practical and highly scalable solution for large RIS deployments with discrete phase shift constraints.
### Title:
          Segmentation of Gray Matters and White Matters from Brain MRI data
 - **Authors:** Chang Sun, Rui Shi, Tsukasa Koike, Tetsuro Sekine, Akio Morita, Tetsuya Sakai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate segmentation of brain tissues such as gray matter and white matter from magnetic resonance imaging is essential for studying brain anatomy, diagnosing neurological disorders, and monitoring disease progression. Traditional methods, such as FSL FAST, produce tissue probability maps but often require task-specific adjustments and face challenges with diverse imaging conditions. Recent foundation models, such as MedSAM, offer a prompt-based approach that leverages large-scale pretraining. In this paper, we propose a modified MedSAM model designed for multi-class brain tissue segmentation. Our preprocessing pipeline includes skull stripping with FSL BET, tissue probability mapping with FSL FAST, and converting these into 2D axial, sagittal, coronal slices with multi-class labels (background, gray matter, and white matter). We extend MedSAM's mask decoder to three classes, freezing the pre-trained image encoder and fine-tuning the prompt encoder and decoder. Experiments on the IXI dataset achieve Dice scores up to 0.8751. This work demonstrates that foundation models like MedSAM can be adapted for multi-class medical image segmentation with minimal architectural modifications. Our findings suggest that such models can be extended to more diverse medical imaging scenarios in future work.
### Title:
          Efficient Camera Pose Augmentation for View Generalization in Robotic Policy Learning
 - **Authors:** Sen Wang, Huaiyi Dong, Jingyi Tian, Jiayi Li, Zhuo Yang, Tongtong Cao, Anlin Chen, Shuang Wu, Le Wang, Sanping Zhou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Prevailing 2D-centric visuomotor policies exhibit a pronounced deficiency in novel view generalization, as their reliance on static observations hinders consistent action mapping across unseen views. In response, we introduce GenSplat, a feed-forward 3D Gaussian Splatting framework that facilitates view-generalized policy learning through novel view rendering. GenSplat employs a permutation-equivariant architecture to reconstruct high-fidelity 3D scenes from sparse, uncalibrated inputs in a single forward pass. To ensure structural integrity, we design a 3D-prior distillation strategy that regularizes the 3DGS optimization, preventing the geometric collapse typical of purely photometric supervision. By rendering diverse synthetic views from these stable 3D representations, we systematically augment the observational manifold during training. This augmentation forces the policy to ground its decisions in underlying 3D structures, thereby ensuring robust execution under severe spatial perturbations where baselines severely degrade.
### Title:
          M2H-MX: Multi-Task Dense Visual Perception for Real-Time Monocular Spatial Understanding
 - **Authors:** U.V.B.L. Udugama, George Vosselman, Francesco Nex
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular cameras are attractive for robotic perception due to their low cost and ease of deployment, yet achieving reliable real-time spatial understanding from a single image stream remains challenging. While recent multi-task dense prediction models have improved per-pixel depth and semantic estimation, translating these advances into stable monocular mapping systems is still non-trivial. This paper presents M2H-MX, a real-time multi-task perception model for monocular spatial understanding. The model preserves multi-scale feature representations while introducing register-gated global context and controlled cross-task interaction in a lightweight decoder, enabling depth and semantic predictions to reinforce each other under strict latency constraints. Its outputs integrate directly into an unmodified monocular SLAM pipeline through a compact perception-to-mapping interface. We evaluate both dense prediction accuracy and in-the-loop system performance. On NYUDv2, M2H-MX-L achieves state-of-the-art results, improving semantic mIoU by 6.6% and reducing depth RMSE by 9.4% over representative multi-task baselines. When deployed in a real-time monocular mapping system on ScanNet, M2H-MX reduces average trajectory error by 60.7% compared to a strong monocular SLAM baseline while producing cleaner metric-semantic maps. These results demonstrate that modern multi-task dense prediction can be reliably deployed for real-time monocular spatial perception in robotic systems.
### Title:
          A Unified Model for Thermo- and Multiple-Network Poroelasticity with a Global-in-Time Iterative Decoupling Scheme
 - **Authors:** Huipeng Gu, Mingchao Cai, Jingzhi Li, Yu Jiang
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces a unified model for thermo-poroelasticity and multiple-network poroelasticity, reformulated into a total-pressure-based system. We first establish the well-posedness of the problem via a Galerkin-based argument and subsequently introduce a robust space-time finite element approximation. To efficiently solve the fully coupled system, we propose a global-in-time iterative algorithm that sequentially decouples the mechanics from the transport equations, while incorporating necessary stabilization terms. We explicitly analyze the convergence rate and provide a rigorous proof that the proposed scheme constitutes a contraction mapping under physically relevant conditions, thereby ensuring its unconditional convergence. Numerical experiments confirm the theoretical stability bounds and demonstrate optimal convergence rates in both space and time, yielding solutions free of non-physical pressure oscillations.
### Title:
          Compressive sensing inspired self-supervised single-pixel imaging
 - **Authors:** Jijun Lu, Yifan Chen, Libang Chen, Yiqiang Zhou, Ye Zheng, Mingliang Chen, Zhe Sun, Xuelong Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Single-pixel imaging (SPI) is a promising imaging modality with distinctive advantages in strongly perturbed environments. Existing SPI methods lack physical sparsity constraints and overlook the integration of local and global features, leading to severe noise vulnerability, structural distortions and blurred details. To address these limitations, we propose SISTA-Net, a compressive sensing-inspired self-supervised method for single-pixel imaging. SISTA-Net unfolds the Iterative Shrinkage-Thresholding Algorithm (ISTA) into an interpretable network consisting of a data fidelity module and a proximal mapping module. The fidelity module adopts a hybrid CNN-Visual State Space Model (VSSM) architecture to integrate local and global feature modeling, enhancing reconstruction integrity and fidelity. We leverage deep nonlinear networks as adaptive sparse transforms combined with a learnable soft-thresholding operator to impose explicit physical sparsity in the latent domain, enabling noise suppression and robustness to interference even at extremely low sampling rates. Extensive experiments on multiple simulation scenarios demonstrate that SISTA-Net outperforms state-of-the-art methods by 2.6 dB in PSNR. Real-world far-field underwater tests yield a 3.4 dB average PSNR improvement, validating its robust anti-interference capability.
### Title:
          GRVS: a Generalizable and Recurrent Approach to Monocular Dynamic View Synthesis
 - **Authors:** Thomas Tanay, Mohammed Brahimi, Michal Nazarczuk, Qingwen Zhang, Sibi Catley-Chandar, Arthur Moreau, Zhensong Zhang, Eduardo Pérez-Pellitero
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synthesizing novel views from monocular videos of dynamic scenes remains a challenging problem. Scene-specific methods that optimize 4D representations with explicit motion priors often break down in highly dynamic regions where multi-view information is hard to exploit. Diffusion-based approaches that integrate camera control into large pre-trained models can produce visually plausible videos but frequently suffer from geometric inconsistencies across both static and dynamic areas. Both families of methods also require substantial computational resources. Building on the success of generalizable models for static novel view synthesis, we adapt the framework to dynamic inputs and propose a new model with two key components: (1) a recurrent loop that enables unbounded and asynchronous mapping between input and target videos and (2) an efficient use of plane sweeps over dynamic inputs to disentangle camera and scene motion, and achieve fine-grained, six-degrees-of-freedom camera controls. We train and evaluate our model on the UCSD dataset and on Kubric-4D-dyn, a new monocular dynamic dataset featuring longer, higher resolution sequences with more complex scene dynamics than existing alternatives. Our model outperforms four Gaussian Splatting-based scene-specific approaches, as well as two diffusion-based approaches in reconstructing fine-grained geometric details across both static and dynamic regions.
### Title:
          DIAL: Decoupling Intent and Action via Latent World Modeling for End-to-End VLA
 - **Authors:** Yi Chen, Yuying Ge, Hui Zhou, Mingyu Ding, Yixiao Ge, Xihui Liu
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The development of Vision-Language-Action (VLA) models has been significantly accelerated by pre-trained Vision-Language Models (VLMs). However, most existing end-to-end VLAs treat the VLM primarily as a multimodal encoder, directly mapping vision-language features to low-level actions. This paradigm underutilizes the VLM's potential in high-level decision making and introduces training instability, frequently degrading its rich semantic representations. To address these limitations, we introduce DIAL, a framework bridging high-level decision making and low-level motor execution through a differentiable latent intent bottleneck. Specifically, a VLM-based System-2 performs latent world modeling by synthesizing latent visual foresight within the VLM's native feature space; this foresight explicitly encodes intent and serves as the structural bottleneck. A lightweight System-1 policy then decodes this predicted intent together with the current observation into precise robot actions via latent inverse dynamics. To ensure optimization stability, we employ a two-stage training paradigm: a decoupled warmup phase where System-2 learns to predict latent futures while System-1 learns motor control under ground-truth future guidance within a unified feature space, followed by seamless end-to-end joint optimization. This enables action-aware gradients to refine the VLM backbone in a controlled manner, preserving pre-trained knowledge. Extensive experiments on the RoboCasa GR1 Tabletop benchmark show that DIAL establishes a new state-of-the-art, achieving superior performance with 10x fewer demonstrations than prior methods. Furthermore, by leveraging heterogeneous human demonstrations, DIAL learns physically grounded manipulation priors and exhibits robust zero-shot generalization to unseen objects and novel configurations during real-world deployment on a humanoid robot.
### Title:
          UniRank: End-to-End Domain-Specific Reranking of Hybrid Text-Image Candidates
 - **Authors:** Yupei Yang, Lin Yang, Wanxi Deng, Lin Qu, Shikui Tu, Lei Xu
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reranking is a critical component in many information retrieval pipelines. Despite remarkable progress in text-only settings, multimodal reranking remains challenging, particularly when the candidate set contains hybrid text and image items. A key difficulty is the modality gap: a text reranker is intrinsically closer to text candidates than to image candidates, leading to biased and suboptimal cross-modal ranking. Vision-language models (VLMs) mitigate this gap through strong cross-modal alignment and have recently been adopted to build multimodal rerankers. However, most VLM-based rerankers encode all candidates as images, and treating text as images introduces substantial computational overhead. Meanwhile, existing open-source multimodal rerankers are typically trained on general-domain data and often underperform in domain-specific scenarios. To address these limitations, we propose UniRank, a VLM-based reranking framework that natively scores and orders hybrid text-image candidates without any modality conversion. Building on this hybrid scoring interface, UniRank provides an end-to-end domain adaptation pipeline that includes: (1) an instruction-tuning stage that learns calibrated cross-modal relevance scoring by mapping label-token likelihoods to a unified scalar score; and (2) a hard-negative-driven preference alignment stage that constructs in-domain pairwise preferences and performs query-level policy optimization through reinforcement learning from human feedback (RLHF). Extensive experiments on scientific literature retrieval and design patent search demonstrate that UniRank consistently outperforms state-of-the-art baselines, improving Recall@1 by 8.9% and 7.3%, respectively.
### Title:
          Aligning Validation with Deployment: Target-Weighted Cross-Validation for Spatial Prediction
 - **Authors:** Alexander Brenning, Thomas Suesse
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-validation (CV) is commonly used to estimate predictive risk when independent test data are unavailable. Its validity depends on the assumption that validation tasks are sampled from the same distribution as prediction tasks encountered during deployment. In spatial prediction and other settings with structured data, this assumption is frequently violated, leading to biased estimates of deployment risk. We propose Target-Weighted CV (TWCV), an estimator of deployment risk that accounts for discrepancies between validation and deployment task distributions, thus accounting for (1) covariate shift and (2) task-difficulty shift. We characterize prediction tasks by descriptors such as covariates and spatial configuration. TWCV assigns weights to validation losses such that the weighted empirical distribution of validation tasks matches the corresponding distribution over a target domain. The weights are obtained via calibration weighting, yielding an importance-weighted estimator that targets deployment risk. Since TWCV requires adequate coverage of the deployment distribution's support, we combine it with spatially buffered resampling that diversifies the task difficulty distribution. In a simulation study, conventional as well as spatial estimators exhibit substantial bias depending on sampling, whereas buffered TWCV remains approximately unbiased across scenarios. A case study in environmental pollution mapping further confirms that discrepancies between validation and deployment task distributions can affect performance assessment, and that buffered TWCV better reflects the prediction task over the target domain. These results establish task distribution mismatch as a primary source of CV bias in spatial prediction and show that calibration weighting combined with a suitable validation task generator provides a viable approach to estimating predictive risk under dataset shift.
### Title:
          Enhancing Structural Mapping with LLM-derived Abstractions for Analogical Reasoning in Narratives
 - **Authors:** Mohammadhossein Khojasteh, Yifan Jiang, Stefano De Giorgis, Frank van Harmelen, Filip Ilievski
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Analogical reasoning is a key driver of human generalization in problem-solving and argumentation. Yet, analogies between narrative structures remain challenging for machines. Cognitive engines for structural mapping are not directly applicable, as they assume pre-extracted entities, whereas LLMs' performance is sensitive to prompt format and the degree of surface similarity between narratives. This gap motivates a key question: What is the impact of enhancing structural mapping with LLM-derived abstractions on their analogical reasoning ability in narratives? To that end, we propose a modular framework named YARN (Yielding Abstractions for Reasoning in Narratives), which uses LLMs to decompose narratives into units, abstract these units, and then passes them to a mapping component that aligns elements across stories to perform analogical reasoning. We define and operationalize four levels of abstraction that capture both the general meaning of units and their roles in the story, grounded in prior work on framing. Our experiments reveal that abstractions consistently improve model performance, resulting in competitive or better performance than end-to-end LLM baselines. Closer error analysis reveals the remaining challenges in abstraction at the right level, in incorporating implicit causality, and an emerging categorization of analogical patterns in narratives. YARN enables systematic variation of experimental settings to analyze component contributions, and to support future work, we make the code for YARN openly available.
## Keyword: localization
### Title:
          A Classification of Heterogeneity in Uncrewed Vehicle Swarms and the Effects of Its Inclusion on Overall Swarm Resilience
 - **Authors:** Abhishek Joshi, Abhishek Phadke, Tianxing Chu, F. Antonio Medrano
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Combining different types of agents in uncrewed vehicle (UV) swarms has emerged as an approach to enhance mission resilience and operational capabilities across a wide range of applications. This study offers a systematic framework for grouping different types of swarms based on three main factors: agent nature (behavior and function), hardware structure (physical configuration and sensing capabilities), and operational space (domain of operation). A literature review indicates that strategic heterogeneity significantly improves swarm performance. Operational challenges, including communication architecture constraints, energy-aware coordination strategies, and control system integration, are also discussed. The analysis shows that heterogeneous swarms are more resilient because they can leverage diverse capabilities, adapt roles on the fly, and integrate data from multidimensional sensor feeds. Some important factors to consider when implementing are sim-to-real-world transfer for learned policies, standardized evaluation metrics, and control architectures that can work together. Learning-based coordination, GPS (Global Positioning System)-denied multi-robot SLAM (Simultaneous Localization and Mapping), and domain-specific commercial deployments collectively demonstrate that heterogeneous swarm technology is moving closer to readiness for high-value applications. This study offers a single taxonomy and evidence-based observations on methods for designing mission-ready heterogeneous swarms that balance complexity and increased capability.
### Title:
          Beyond Localization: Recoverable Headroom and Residual Frontier in Repository-Level RAG-APR
 - **Authors:** Pengtao Zhao, Boyang Yang, Bach Le, Feng Liu, Haoye Tian
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Repository-level automated program repair (APR) increasingly treats stronger localization as the main path to better repair. We ask a more targeted question: once localization is strengthened, which post-localization levers still provide recoverable gains, which are bounded within our protocol, and what residual frontier remains? We study this question on SWE-bench Lite with three representative repository-level RAG-APR paradigms, Agentless, KGCompass, and ExpeRepair. Our protocol combines Oracle Localization, within-pool Best-of-K, fixed-interface added context probes with per-condition same-token filler controls and same-repository hard negatives, and a common-wrapper oracle check. Oracle Localization improves all three systems, but Oracle success still stays below 50%. Extra candidate diversity still helps inside the sampled 10-patch pools, but that headroom saturates quickly. Under the two fixed interfaces, most informative added context conditions still outperform their own matched controls. The common-wrapper check shows different system responses: under a common wrapper, gains remain large for KGCompass and ExpeRepair, while Agentless changes more with builder choice. Prompt-level fusion still leaves a large residual frontier: the best fixed probe adds only 6 solved instances beyond the native three-system Solved@10 union. Overall, stronger localization, bounded search, evidence quality, and interface design all shape repository-level repair outcomes.
### Title:
          SemLoc: Structured Grounding of Free-Form LLM Reasoning for Fault Localization
 - **Authors:** Zhaorui Yang, Haichao Zhu, Qian Zhang, Rajiv Gupta, Ashish Kundu
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fault localization identifies program locations responsible for observed failures. Existing techniques rank suspicious code using syntactic spectra--signals derived from execution structure such as statement coverage, control-flow divergence, or dependency reachability. These signals collapse for semantic bugs, where failing and passing executions follow identical code paths and differ only in whether semantic intent is satisfied. Recent LLM-based approaches introduce semantic reasoning but produce stochastic, unverifiable outputs that cannot be systematically cross-referenced across tests or distinguish root causes from cascading effects. We present SemLoc, a fault localization framework based on structured semantic grounding. SemLoc converts free-form LLM reasoning into a closed intermediate representation that binds each inferred property to a typed program anchor, enabling runtime checking and attribution to program structure. It executes instrumented programs to construct a semantic violation spectrum--a constraint-by-test matrix--from which suspiciousness scores are derived analogously to coverage-based methods. A counterfactual verification step further prunes over-approximate constraints and isolates primary causal violations. We evaluate SemLoc on SemFault-250, a corpus of 250 Python programs with single semantic faults. SemLoc outperforms five coverage-, reduction-, and LLM-based baselines, achieving Top-1 accuracy of 42.8% and Top-3 of 68%, while reducing inspection to 7.6% of executable lines. Counterfactual verification provides an additional 12% accuracy gain and identifies primary causal semantic constraints.
### Title:
          Logging Like Humans for LLMs: Rethinking Logging via Execution and Runtime Feedback
 - **Authors:** Xin Wang, Yang Feng, Jiaoxiao Qian, Yang Zhang, Zhenhao Li, Zishuo Ding
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Logging statements are essential for software debugging and maintenance. However, existing approaches to automatic logging generation rely on static analysis and produce statements in a single pass without considering runtime behavior. They are also typically evaluated by similarity to developer-written logs, assuming these logs form an adequate gold standard. This assumption is increasingly limiting in the LLM era, where logs are consumed not only by developers but also by LLMs for downstream tasks. As a result, optimizing logs for human similarity does not necessarily reflect their practical utility. To address these limitations, we introduce ReLog, an iterative logging generation framework guided by runtime feedback. ReLog leverages LLMs to generate, execute, evaluate, and refine logging statements so that runtime logs better support downstream tasks. Instead of comparing against developer-written logs, we evaluate ReLog through downstream debugging tasks, including defect localization and repair. We construct a benchmark based on Defects4J under both direct and indirect debugging settings. Results show that ReLog consistently outperforms all baselines, achieving an F1 score of 0.520 and repairing 97 defects in the direct setting, and the best F1 score of 0.408 in the indirect setting where source code is unavailable. Additional experiments across multiple LLMs demonstrate the generality of the framework, while ablations confirm the importance of iterative refinement and compilation repair. Overall, our work reframes logging as a runtime-guided, task-oriented process and advocates evaluating logs by their downstream utility rather than textual similarity.
### Title:
          Hierarchical Visual Relocalization with Nearest View Synthesis from Feature Gaussian Splatting
 - **Authors:** Huaqi Tao, Bingxi Liu, Guangcheng Chen, Fulin Tang, Li He, Hong Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual relocalization is a fundamental task in the field of 3D computer vision, estimating a camera's pose when it revisits a previously known scene. While point-based hierarchical relocalization methods have shown strong scalability and efficiency, they are often limited by sparse image observations and weak feature matching. In this work, we propose SplatHLoc, a novel hierarchical visual relocalization framework that uses Feature Gaussian Splatting as the scene representation. To address the sparsity of database images, we propose an adaptive viewpoint retrieval method that synthesizes virtual candidates with viewpoints more closely aligned with the query, thereby improving the accuracy of initial pose estimation. For feature matching, we observe that Gaussian-rendered features and those extracted directly from images exhibit different strengths across the two-stage matching process: the former performs better in the coarse stage, while the latter proves more effective in the fine stage. Therefore, we introduce a hybrid feature matching strategy, enabling more accurate and efficient pose estimation. Extensive experiments on both indoor and outdoor datasets show that SplatHLoc enhances the robustness of visual relocalization, setting a new state-of-the-art.
### Title:
          Needle in a Haystack: Tracking UAVs from Massive Noise in Real-World 5G-A Base Station Data
 - **Authors:** Chengzhen Meng, Chenming He, Yidong Jiang, Xiaoran Fan, Dequan Wang, Lingyu Wang, Jianmin Ji, Yanyong Zhang
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The potential usage of UAVs in daily life has made monitoring them essential. However, existing systems for monitoring UAVs typically rely on cameras, LiDARs, or radars, whose limited sensing range or high deployment cost hinder large-scale adoption. In response, we develop BSense, the first system that tracks UAVs by leveraging point clouds from commercial 5G-A base stations. The key challenge lies in the dominant number of noise points that closely resemble true UAV points, resulting in a noise-to-UAV ratio over 100:1. Therefore, identifying UAVs from the raw point clouds is like finding a needle in a haystack. To overcome this, we propose a layered framework that filters noise at the point, object, and trajectory levels. At the raw point level, we observe that noise points from different spatial regions exhibit distinguishable and consistent signal fingerprints, which we can model to identify and remove them. At the object level, we design spatial and velocity consistency checks to identify false objects, and further compute confidence scores by aggregating these checks over multiple frames for more reliable discrimination. At the final trajectory level, we propose a Transformer-based network that captures multi-frame motion patterns to filter the few remaining false trajectories. We evaluated BSense on a commercial 5G-A base station deployed in an urban environment. The UAV was instructed to fly along 25 distinct trajectories across 54 cases over 7 days, yielding 155 minutes of data with more than 14,000 frames. On this dataset, our system reduces the number of false detections from an average of 168.05 per frame to 0.04, achieving an average F1 score of 95.56% and a mean localization error of 4.9 m at ranges up to 1,000 m.
### Title:
          MELT: Improve Composed Image Retrieval via the Modification Frequentation-Rarity Balance Network
 - **Authors:** Guozhi Qiu, Zhiwei Chen, Zixu Li, Qinlei Huang, Zhiheng Fu, Xuemeng Song, Yupeng Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Composed Image Retrieval (CIR) uses a reference image and a modification text as a query to retrieve a target image satisfying the requirement of ``modifying the reference image according to the text instructions''. However, existing CIR methods face two limitations: (1) frequency bias leading to ``Rare Sample Neglect'', and (2) susceptibility of similarity scores to interference from hard negative samples and noise. To address these limitations, we confront two key challenges: asymmetric rare semantic localization and robust similarity estimation under hard negative samples. To solve these challenges, we propose the Modification frEquentation-rarity baLance neTwork MELT. MELT assigns increased attention to rare modification semantics in multimodal contexts while applying diffusion-based denoising to hard negative samples with high similarity scores, enhancing multimodal fusion and matching. Extensive experiments on two CIR benchmarks validate the superior performance of MELT. Codes are available at this https URL.
### Title:
          PromptForge-350k: A Large-Scale Dataset and Contrastive Framework for Prompt-Based AI Image Forgery Localization
 - **Authors:** Jianpeng Wang, Haoyu Wang, Baoying Chen, Jishen Zeng, Yiming Qin, Yiqi Yang, Zhongjie Ba
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid democratization of prompt-based AI image editing has recently exacerbated the risks associated with malicious content fabrication and misinformation. However, forgery localization methods targeting these emerging editing techniques remain significantly under-explored. To bridge this gap, we first introduce a fully automated mask annotating framework that leverages keypoint alignment and semantic space similarity to generate precise ground-truth masks for edited regions. Based on this framework, we construct PromptForge-350k, a large-scale forgery localization dataset covering four state-of-the-art prompt-based AI image editing models, thereby mitigating the data scarcity in this domain. Furthermore, we propose ICL-Net, an effective forgery localization network featuring a triple-stream backbone and intra-image contrastive learning. This design enables the model to capture highly robust and generalizable forensic features. Extensive experiments demonstrate that our method achieves an IoU of 62.5% on PromptForge-350k, outperforming SOTA methods by 5.1%. Additionally, it exhibits strong robustness against common degradations with an IoU drop of less than 1%, and shows promising generalization capabilities on unseen editing models, achieving an average IoU of 41.5%.
### Title:
          RAAP: Retrieval-Augmented Affordance Prediction with Cross-Image Action Alignment
 - **Authors:** Qiyuan Zhuang, He-Yang Xu, Yijun Wang, Xin-Yang Zhao, Yang-Yang Li, Xiu-Shen Wei
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding object affordances is essential for enabling robots to perform purposeful and fine-grained interactions in diverse and unstructured environments. However, existing approaches either rely on retrieval, which is fragile due to sparsity and coverage gaps, or on large-scale models, which frequently mislocalize contact points and mispredict post-contact actions when applied to unseen categories, thereby hindering robust generalization. We introduce Retrieval-Augmented Affordance Prediction (RAAP), a framework that unifies affordance retrieval with alignment-based learning. By decoupling static contact localization and dynamic action direction, RAAP transfers contact points via dense correspondence and predicts action directions through a retrieval-augmented alignment model that consolidates multiple references with dual-weighted attention. Trained on compact subsets of DROID and HOI4D with as few as tens of samples per task, RAAP achieves consistent performance across unseen objects and categories, and enables zero-shot robotic manipulation in both simulation and the real world. Project website: this https URL.
### Title:
          All-in-One Augmented Reality Guided Head and Neck Tumor Resection
 - **Authors:** Yue Yang, Matthieu Chabanas, Carrie Reale, Annie Benson, Jason Slagle, Matthew Weinger, Michael Topf, Jie Ying Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Emerging Technologies (cs.ET); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Positive margins are common in head and neck squamous cell carcinoma, yet intraoperative re-resection is often imprecise because margin locations are typically communicated verbally from pathology. We present an all-in-one augmented reality (AR) system that relocalizes positive margins from a resected specimen to the resection bed and visualizes them in situ using HoloLens 2 depth sensing and fully automated markerless surface registration. In a silicone phantom study with six medical trainees, markerless registration achieved target registration errors comparable to a marker-based baseline (median 1.8 mm vs. 1.7 mm; maximum < 4 mm). In a margin relocalization task, AR guidance reduced error from verbal guidance (median 14.2 mm) to a few millimeters (median 3.2 mm), with all AR localizations within 5 mm error. These results support the feasibility of markerless AR margin guidance for more precise intraoperative re-excision.
### Title:
          Total Variation Guarantees for Sampling with Stochastic Localization
 - **Authors:** Jakob Kellermann
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Probability (math.PR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Motivated by the success of score-based generative models, a number of diffusion-based algorithms have recently been proposed for the problem of sampling from a probability measure whose unnormalized density can be accessed. Among them, Grenioux et al. introduced SLIPS, a sampling algorithm based on Stochastic Localization. While SLIPS exhibits strong empirical performance, no rigorous convergence analysis has previously been provided. In this work, we close this gap by establishing the first guarantee for SLIPS in total variation distance. Under minimal assumptions on the target, our bound implies that the number of steps required to achieve an $\varepsilon$-guarantee scales linearly with the dimension, up to logarithmic factors. The analysis leverages techniques from the theory of score-based generative models and further provides theoretical insights into the empirically observed optimal choice of discretization points.
### Title:
          Semantic Zone-Based Map Management for Stable AI-Integrated Mobile Robots
 - **Authors:** Huichang Yun, Seungho Yoo
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in large AI models (VLMs and LLMs) and joint use of the 3D dense maps, enable mobile robots to provide more powerful and interactive services grounded in rich spatial context. However, deploying both heavy AI models and dense maps on edge robots is challenging under strict memory budgets. When the memory budget is exceeded, required keyframes may not be loaded in time, which can degrade the stability of position estimation and interfering model performance. We proposes a semantic zone-based map management approach to stabilize dense-map utilization under memory constraints. We associate keyframes with semantic indoor regions (e.g., rooms and corridors) and keyframe management at the semantic zone level prioritizes spatially relevant map content while respecting memory constraints. This reduces keyframe loading and unloading frequency and memory usage. We evaluate the proposed approach in large-scale simulated indoor environments and on an NVIDIA Jetson Orin Nano under concurrent SLAM-VLM execution. With Qwen3.5:0.8b, the proposed method improves throughput by 3.3 tokens/s and reduces latency by 21.7% relative to a geometric map-management strategy. Furthermore, while the geometric strategy suffers from out-of-memory failures and stalled execution under memory pressure, the proposed method eliminates both issues, preserving localization stability and enabling robust VLM operation. These results demonstrate that the proposed approach enables efficient dense map utilization for memory constrained, AI-integrated mobile robots. Code is available at: this https URL
### Title:
          End-to-End Image Compression with Segmentation Guided Dual Coding for Wind Turbines
 - **Authors:** Raül Pérez-Gonzalo, Andreas Espersen, Søren Forchhammer, Antonio Agudo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transferring large volumes of high-resolution images during wind turbine inspections introduces a bottleneck in assessing and detecting severe defects. Efficient coding must preserve high fidelity in blade regions while aggressively compressing the background. In this work, we propose an end-to-end deep learning framework that jointly performs segmentation and dual-mode (lossy and lossless) compression. The segmentation module accurately identifies the blade region, after which our region-of-interest (ROI) compressor encodes it at superior quality compared to the rest of the image. Unlike conventional ROI schemes that merely allocate more bits to salient areas, our framework integrates: (i) a robust segmentation network (BU-Netv2+P) with a CRF-regularized loss for precise blade localization, (ii) a hyperprior-based autoencoder optimized for lossy compression, and (iii) an extended bits-back coder with hierarchical models for fully lossless blade reconstruction. Furthermore, our ROI framework removes the sequential dependency in bits-back coding by reusing background-coded bits, enabling parallelized and efficient dual-mode compression. To the best of our knowledge, this is the first fully integrated learning-based ROI codec combining segmentation, lossy, and lossless compression, ensuring that subsequent defect detection is not compromised. Experiments on a large-scale wind turbine dataset demonstrate superior compression performance and efficiency, offering a practical solution for automated inspections.
### Title:
          SurgNavAR: An Augmented Reality Surgical Navigation Framework for Optical See-Through Head Mounted Displays
 - **Authors:** Abdullah Thabit, Mohamed Benmahdjoub, Rafiuddin Jinabade, Hizirwan S. Salim, Marie-Lise C. van Veelen, Mark G. van Vledder, Eppo B. Wolvius, Theo van Walsum
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Augmented reality (AR) devices with head mounted displays (HMDs) facilitate the direct superimposition of 3D preoperative imaging data onto the patient during surgery. To use an HMD-AR device as a stand-alone surgical navigation system, the device should be able to locate the patient and surgical instruments, align preoperative imaging data with the patient, and visualize navigation data in real time during surgery. Whereas some of the technologies required for this are known, integration in such devices is cumbersome and requires specific knowledge and expertise, hampering scientific progress in this field. This work therefore aims to present and evaluate an integrated HMD-based AR surgical navigation framework that is adaptable to diverse surgical applications. The framework tracks 2D patterns as reference markers attached to the patient and surgical instruments. It allows for the calibration of surgical tools using pivot and reference-based calibration techniques. It enables image-to-patient registration using point-based matching and manual positioning. The integrated functionalities of the framework are evaluated on two HMD devices, the HoloLens 2 and Magic Leap 2, with two surgical use cases being evaluated in a phantom setup: AR-guided needle insertion and rib fracture localization. The framework was able to achieve a mean tooltip calibration accuracy of 1 mm, a registration accuracy of 3 mm, and a targeting accuracy below 5 mm on the two surgical use cases. The framework presents an easy-to-use configurable tool for HMD-based AR surgical navigation, which can be extended and adapted to many surgical applications. The framework is publicly available at this https URL.
## Keyword: transformer
### Title:
          From Consensus to Split Decisions: ABC-Stratified Sentiment in Holocaust Oral Histories
 - **Authors:** Daban Q. Jaff
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Polarity detection becomes substantially more challenging under domain shift, particularly in heterogeneous, long-form narratives with complex discourse structure, such as Holocaust oral histories. This paper presents a corpus-scale diagnostic study of off-the-shelf sentiment classifiers on long-form Holocaust oral histories, using three pretrained transformer-based polarity classifiers on a corpus of 107,305 utterances and 579,013 sentences. After assembling model outputs, we introduce an agreement-based stability taxonomy (ABC) to stratify inter-model output stability. We report pairwise percent agreement, Cohen kappa, Fleiss kappa, and row-normalized confusion matrices to localize systematic disagreement. As an auxiliary descriptive signal, a T5-based emotion classifier is applied to stratified samples from each agreement stratum to compare emotion distributions across strata. The combination of multi-model label triangulation and the ABC taxonomy provides a cautious, operational framework for characterizing where and how sentiment models diverge in sensitive historical narratives. Inter-model agreement is low to moderate overall and is driven primarily by boundary decisions around neutrality.
### Title:
          From Energy Transition Pathways to Measurement Requirements: A Scenario-Based Study of Low-Voltage Grids
 - **Authors:** Nane Zimmermann, Lukas P. Wagner, Luca von Rönn, Florian Strobel, Paul Hüttmann, Felix Gehlhoff
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Increasing penetration of electric vehicles, heat pumps, and rooftop photovoltaics is creating thermal and voltage stress in low-voltage distribution grids. This work links three German energy transition pathways (2025-2045) with state estimation performance requirements, evaluated on two SimBench reference networks across three equipment quality levels (good, medium, poor) and three VDE Forum Netztechnik/Netzbetrieb (VDE FNN) measurement constellations that differ in the availability of transformer and feeder-level instrumentation. Congestion is caused exclusively by transformer overloading and voltage-band violations. No individual line exceeds its thermal rating. Equipment quality is the primary factor: under good equipment, congestion remains nearly absent through 2045 (1/26 scenarios), under medium equipment it emerges from 2035 (10/26), under poor equipment from 2025 (25/26), reaching 208 % peak transformer loading. Without transformer instrumentation, voltage estimation errors remain at 6-35% regardless of smart meter penetration. Adding a single transformer measurement reduces errors by a factor of 3 to 24, achieving median errors below 1.1% under poor equipment. Per-feeder measurements achieve comparable accuracy and outperform the transformer-only configuration under poor equipment in rural networks (0.8% vs. 1.1%). In urban networks under poor and medium equipment, transformer and feeder-level instrumentation meet the VDE FNN voltage accuracy target without requiring customer-side sensors. These findings motivate prioritizing transformer instrumentation as an effective first step for grid observability and supplementing the current consumption-driven metering rollout with risk-based deployment criteria linked to local congestion exposure.
### Title:
          MMFace-DiT: A Dual-Stream Diffusion Transformer for High-Fidelity Multimodal Face Generation
 - **Authors:** Bharath Krishnamurthy, Ajita Rattani
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent multimodal face generation models address the spatial control limitations of text-to-image diffusion models by augmenting text-based conditioning with spatial priors such as segmentation masks, sketches, or edge maps. This multimodal fusion enables controllable synthesis aligned with both high-level semantic intent and low-level structural layout. However, most existing approaches typically extend pre-trained text-to-image pipelines by appending auxiliary control modules or stitching together separate uni-modal networks. These ad hoc designs inherit architectural constraints, duplicate parameters, and often fail under conflicting modalities or mismatched latent spaces, limiting their ability to perform synergistic fusion across semantic and spatial domains. We introduce MMFace-DiT, a unified dual-stream diffusion transformer engineered for synergistic multimodal face synthesis. Its core novelty lies in a dual-stream transformer block that processes spatial (mask/sketch) and semantic (text) tokens in parallel, deeply fusing them through a shared Rotary Position-Embedded (RoPE) Attention mechanism. This design prevents modal dominance and ensures strong adherence to both text and structural priors to achieve unprecedented spatial-semantic consistency for controllable face generation. Furthermore, a novel Modality Embedder enables a single cohesive model to dynamically adapt to varying spatial conditions without retraining. MMFace-DiT achieves a 40% improvement in visual fidelity and prompt alignment over six state-of-the-art multimodal face generation models, establishing a flexible new paradigm for end-to-end controllable generative modeling. The code and dataset are available on our project page: this https URL
### Title:
          LA-Sign: Looped Transformers with Geometry-aware Alignment for Skeleton-based Sign Language Recognition
 - **Authors:** Muxin Pu, Mei Kuan Lim, Chun Yong Chong, Chen Change Loy
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Skeleton-based isolated sign language recognition (ISLR) demands fine-grained understanding of articulated motion across multiple spatial scales, from subtle finger movements to global body dynamics. Existing approaches typically rely on deep feed-forward architectures, which increase model capacity but lack mechanisms for recurrent refinement and structured representation. We propose LA-Sign, a looped transformer framework with geometry-aware alignment for ISLR. Instead of stacking deeper layers, LA-Sign derives its depth from recurrence, repeatedly revisiting latent representations to progressively refine motion understanding under shared parameters. To further regularise this refinement process, we present a geometry-aware contrastive objective that projects skeletal and textual features into an adaptive hyperbolic space, encouraging multi-scale semantic organisation. We study three looping designs and multiple geometric manifolds, demonstrating that encoder-decoder looping combined with adaptive Poincare alignment yields the strongest performance. Extensive experiments on WLASL and MSASL benchmarks show that LA-Sign achieves state-of-the-art results while using fewer unique layers, highlighting the effectiveness of recurrent latent refinement and geometry-aware representation learning for sign language recognition.
### Title:
          ARCS: Autoregressive Circuit Synthesis with Topology-Aware Graph Attention and Spec Conditioning
 - **Authors:** Tushar Dhananjay Pathak
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 I present ARCS, a system for amortized analog circuit generation that produces complete, SPICE-simulatable designs (topology and component values) in milliseconds rather than the minutes required by search-based methods. A hybrid pipeline combining two learned generators (a graph VAE and a flow-matching model) with SPICE-based ranking achieves 99.9% simulation validity (reward 6.43/8.0) across 32 topologies using only 8 SPICE evaluations, 40x fewer than genetic algorithms. For single-model inference, a topology-aware Graph Transformer with Best-of-3 candidate selection reaches 85% simulation validity in 97ms, over 600x faster than random search. The key technical contribution is Group Relative Policy Optimization (GRPO): I identify a critical failure mode of REINFORCE (cross-topology reward distribution mismatch) and resolve it with per-topology advantage normalization, improving simulation validity by +9.6pp over REINFORCE in only 500 RL steps (10x fewer). Grammar-constrained decoding additionally guarantees 100% structural validity by construction via topology-aware token masking. ARCS does not yet match the per-design quality of search-based optimization (5.48 vs. 7.48 reward), but its >1000x speed advantage enables rapid prototyping, design-space exploration, and warm-starting search methods (recovering 96.6% of GA quality with 49% fewer simulations).
### Title:
          On the Mirage of Long-Range Dependency, with an Application to Integer Multiplication
 - **Authors:** Zichao Wei
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Integer multiplication has long been considered a hard problem for neural networks, with the difficulty widely attributed to the O(n) long-range dependency induced by carry chains. We argue that this diagnosis is wrong: long-range dependency is not an intrinsic property of multiplication, but a mirage produced by the choice of computational spacetime. We formalize the notion of mirage and provide a constructive proof: when two n-bit binary integers are laid out as a 2D outer-product grid, every step of long multiplication collapses into a $3 \times 3$ local neighborhood operation. Under this representation, a neural cellular automaton with only 321 learnable parameters achieves perfect length generalization up to $683\times$ the training range. Five alternative architectures -- including Transformer (6,625 params), Transformer+RoPE, and Mamba -- all fail under the same representation. We further analyze how partial successes locked the community into an incorrect diagnosis, and argue that any task diagnosed as requiring long-range dependency should first be examined for whether the dependency is intrinsic to the task or induced by the computational spacetime.
### Title:
          The Future of AI is Many, Not One
 - **Authors:** Daniel J. Singer, Luca Garzino Demo
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The way we're thinking about generative AI right now is fundamentally individual. We see this not just in how users interact with models but also in how models are built, how they're benchmarked, and how commercial and research strategies using AI are defined. We argue that we should abandon this approach if we're hoping for AI to support groundbreaking innovation and scientific discovery. Drawing on research and formal results in complex systems, organizational behavior, and philosophy of science, we show why we should expect deep intellectual breakthroughs to come from epistemically diverse groups of AI agents working together rather than singular superintelligent agents. Having a diverse team broadens the search for solutions, delays premature consensus, and allows for the pursuit of unconventional approaches. Developing diverse AI teams also addresses AI critics' concerns that current models are constrained by past data and lack the creative insight required for innovation. The upshot, we argue, is that the future of transformative transformer-based AI is fundamentally many, not one.
### Title:
          HCLSM: Hierarchical Causal Latent State Machines for Object-Centric World Modeling
 - **Authors:** Jaber Jaber, Osama Jaber
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models that predict future states from video remain limited by flat latent representations that entangle objects, ignore causal structure, and collapse temporal dynamics into a single scale. We present HCLSM, a world model architecture that operates on three interconnected principles: object-centric decomposition via slot attention with spatial broadcast decoding, hierarchical temporal dynamics through a three-level engine combining selective state space models for continuous physics, sparse transformers for discrete events, and compressed transformers for abstract goals, and causal structure learning through graph neural network interaction patterns. HCLSM introduces a two-stage training protocol where spatial reconstruction forces slot specialization before dynamics prediction begins. We train a 68M-parameter model on the PushT robotic manipulation benchmark from the Open X-Embodiment dataset, achieving 0.008 MSE next-state prediction loss with emerging spatial decomposition (SBD loss: 0.0075) and learned event boundaries. A custom Triton kernel for the SSM scan delivers 38x speedup over sequential PyTorch. The full system spans 8,478 lines of Python across 51 modules with 171 unit tests. Code: this https URL
### Title:
          Needle in a Haystack: Tracking UAVs from Massive Noise in Real-World 5G-A Base Station Data
 - **Authors:** Chengzhen Meng, Chenming He, Yidong Jiang, Xiaoran Fan, Dequan Wang, Lingyu Wang, Jianmin Ji, Yanyong Zhang
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The potential usage of UAVs in daily life has made monitoring them essential. However, existing systems for monitoring UAVs typically rely on cameras, LiDARs, or radars, whose limited sensing range or high deployment cost hinder large-scale adoption. In response, we develop BSense, the first system that tracks UAVs by leveraging point clouds from commercial 5G-A base stations. The key challenge lies in the dominant number of noise points that closely resemble true UAV points, resulting in a noise-to-UAV ratio over 100:1. Therefore, identifying UAVs from the raw point clouds is like finding a needle in a haystack. To overcome this, we propose a layered framework that filters noise at the point, object, and trajectory levels. At the raw point level, we observe that noise points from different spatial regions exhibit distinguishable and consistent signal fingerprints, which we can model to identify and remove them. At the object level, we design spatial and velocity consistency checks to identify false objects, and further compute confidence scores by aggregating these checks over multiple frames for more reliable discrimination. At the final trajectory level, we propose a Transformer-based network that captures multi-frame motion patterns to filter the few remaining false trajectories. We evaluated BSense on a commercial 5G-A base station deployed in an urban environment. The UAV was instructed to fly along 25 distinct trajectories across 54 cases over 7 days, yielding 155 minutes of data with more than 14,000 frames. On this dataset, our system reduces the number of false detections from an average of 168.05 per frame to 0.04, achieving an average F1 score of 95.56% and a mean localization error of 4.9 m at ranges up to 1,000 m.
### Title:
          Omni-NegCLIP: Enhancing CLIP with Front-Layer Contrastive Fine-Tuning for Comprehensive Negation Understanding
 - **Authors:** Jingqi Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) have demonstrated strong capabilities across a wide range of multimodal tasks. However, recent studies have shown that VLMs, such as CLIP, perform poorly in understanding negation expressions, which are common in natural language. In this work, we propose Omni-NegCLIP, a fine-tuned CLIP model that improves CLIP's understanding of two types of negation, namely presence-based negation and absence-based negation, which correspond to negated expressions of objects that are actually present in an image and those that may plausibly exist in an image but are in fact absent, respectively, by modifying CLIP's original InfoNCE contrastive loss. Specifically, we design a presence-based contrastive objective that pulls image embeddings closer to their original caption embeddings while pushing them away from the corresponding presence-based negated caption embeddings, and an absence-based contrastive objective that aligns image embeddings with both original and absence-based negated caption embeddings while maintaining a semantic distinction between the two text embeddings. Based on our observation that the front transformer layers of CLIP text encoder have stronger learning ability for negated text than the later layers, we fine-tune the front transformer layers of the CLIP text encoder at each training step using the combined contrastive objective. Experimental results show that, compared with pretrained CLIP, Omni-NegCLIP improves performance on presence-based negation and absence-based negation tasks by up to 52.65% and 12.50%, respectively, without sacrificing general capability in image-text retrieval and even improving it by up to 19.62%. Compared with prior works, Omni-NegCLIP demonstrates a more comprehensive ability to understand multiple types of negation tasks.
### Title:
          StereoVGGT: A Training-Free Visual Geometry Transformer for Stereo Vision
 - **Authors:** Ziyang Chen, Yansong Qu, You Shen, Xuan Cheng, Liujuan Cao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Driven by the advancement of 3D devices, stereo vision tasks including stereo matching and stereo conversion have emerged as a critical research frontier. Contemporary stereo vision backbones typically rely on either monocular depth estimation (MDE) models or visual foundation models (VFMs). Crucially, these models are predominantly pretrained without explicit supervision of camera poses. Given that such geometric knowledge is indispensable for stereo vision, the absence of explicit spatial constraints constitutes a significant performance bottleneck for existing architectures. Recognizing that the Visual Geometry Grounded Transformer (VGGT) operates as a foundation model pretrained on extensive 3D priors, including camera poses, we investigate its potential as a robust backbone for stereo vision tasks. Nevertheless, empirical results indicate that its direct application to stereo vision yields suboptimal performance. We observe that VGGT suffers from a more significant degradation of geometric details during feature extraction. Such characteristics conflict with the requirements of binocular stereo vision, thereby constraining its efficacy for relative tasks. To bridge this gap, we propose StereoVGGT, a feature backbone specifically tailored for stereo vision. By leveraging the frozen VGGT and introducing a training-free feature adjustment pipeline, we mitigate geometric degradation and harness the latent camera calibration knowledge embedded within the model. StereoVGGT-based stereo matching network achieved the $1^{st}$ rank among all published methods on the KITTI benchmark, validating that StereoVGGT serves as a highly effective backbone for stereo vision.
### Title:
          A2BFR: Attribute-Aware Blind Face Restoration
 - **Authors:** Chenxin Zhu, Yushun Fang, Lu Liu, Shibo Yin, Xiaohong Liu, Xiaoyun Zhang, Qiang Hu, Guangtao Zhai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Blind face restoration (BFR) aims to recover high-quality facial images from degraded inputs, yet its inherently ill-posed nature leads to ambiguous and uncontrollable solutions. Recent diffusion-based BFR methods improve perceptual quality but remain uncontrollable, whereas text-guided face editing enables attribute manipulation without reliable restoration. To address these issues, we propose A$^2$BFR, an attribute-aware blind face restoration framework that unifies high-fidelity reconstruction with prompt-controllable generation. Built upon a Diffusion Transformer backbone with unified image-text cross-modal attention, A$^2$BFR jointly conditions the denoising trajectory on both degraded inputs and textual prompts. To inject semantic priors, we introduce attribute-aware learning, which supervises denoising latents using facial attribute embeddings extracted by an attribute-aware encoder. To further enhance prompt controllability, we introduce semantic dual-training, which leverages the pairwise attribute variations in our newly curated AttrFace-90K dataset to enforce attribute discrimination while preserving fidelity. Extensive experiments demonstrate that A$^2$BFR achieves state-of-the-art performance in both restoration fidelity and instruction adherence, outperforming diffusion-based BFR baselines by -0.0467 LPIPS and +52.58% attribute accuracy, while enabling fine-grained, prompt-controllable restoration even under severe degradations.
### Title:
          Few-shot Writer Adaptation via Multimodal In-Context Learning
 - **Authors:** Tom Simon, Stephane Nicolas, Pierrick Tranouez, Clement Chatelain, Thierry Paquet
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While state-of-the-art Handwritten Text Recognition (HTR) models perform well on standard benchmarks, they frequently struggle with writers exhibiting highly specific styles that are underrepresented in the training data. To handle unseen and atypical writers, writer adaptation techniques personalize HTR models to individual handwriting styles. Leading writer adaptation methods require either offline fine-tuning or parameter updates at inference time, both involving gradient computation and backpropagation, which increase computational costs and demand careful hyperparameter tuning. In this work, we propose a novel context-driven HTR framework3 inspired by multimodal in-context learning, enabling inference-time writer adaptation using only a few examples from the target writer without any parameter updates. We further demonstrate the impact of context length, design a compact 8M-parameter CNN-Transformer that enables few-shot in-context adaptation, and show that combining context-driven and standard OCR training strategies leads to complementary improvements. Experiments on IAM and RIMES validate our approach with Character Error Rates of 3.92% and 2.34%, respectively, surpassing all writer-independent HTR models without requiring any parameter updates at inference time.
### Title:
          Square Superpixel Generation and Representation Learning via Granular Ball Computing
 - **Authors:** Shuyin Xia, Meng Yang, Dawei Dai, Fan Chen, Shilin Zhao, Junwei Han, Xinbo Gao, Guoyin Wang, Wen Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Superpixels provide a compact region-based representation that preserves object boundaries and local structures, and have therefore been widely used in a variety of vision tasks to reduce computational cost. However, most existing superpixel algorithms produce irregularly shaped regions, which are not well aligned with regular operators such as convolutions. Consequently, superpixels are often treated as an offline preprocessing step, limiting parallel implementation and hindering end-to-end optimization within deep learning pipelines. Motivated by the adaptive representation and coverage property of granular-ball computing, we develop a square superpixel generation approach. Specifically, we approximate superpixels using multi-scale square blocks to avoid the computational and implementation difficulties induced by irregular shapes, enabling efficient parallel processing and learnable feature extraction. For each block, a purity score is computed based on pixel-intensity similarity, and high-quality blocks are selected accordingly. The resulting square superpixels can be readily integrated as graph nodes in graph neural networks (GNNs) or as tokens in Vision Transformers (ViTs), facilitating multi-scale information aggregation and structured visual representation. Experimental results on downstream tasks demonstrate consistent performance improvements, validating the effectiveness of the proposed method.
### Title:
          VecAttention: Vector-wise Sparse Attention for Accelerating Long Context Inference
 - **Authors:** Anmin Liu, Ruixuan Yang, Huiqiang Jiang, Bin Lin, Minmin Sun, Yong Li, Chen Zhang, Tao Xie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-context video understanding and generation pose a significant computational challenge for Transformer-based video models due to the quadratic complexity of self-attention. While existing sparse attention methods employ coarse-grained patterns to improve efficiency, they typically incur redundant computation and suboptimal performance. To address this issue, in this paper, we propose \textbf{VecAttention}, a novel framework of vector-wise sparse attention that achieves superior accuracy-efficiency trade-offs for video models. We observe that video attention maps exhibit a strong vertical-vector sparse pattern, and further demonstrate that this vertical-vector pattern offers consistently better accuracy-sparsity trade-offs compared with existing coarse-grained sparse patterns. Based on this observation, VecAttention dynamically selects and processes only informative vertical vectors through a lightweight important-vector selection that minimizes memory access overhead and an optimized kernel of vector sparse attention. Comprehensive evaluations on video understanding (VideoMME, LongVideoBench, and VCRBench) and generation (VBench) tasks show that VecAttention delivers a 2.65$\times$ speedup over full attention and a 1.83$\times$ speedup over state-of-the-art sparse attention methods, with comparable accuracy to full attention. Our code is available at this https URL.
### Title:
          One-for-All: A Lightweight Stabilized and Parameter-Efficient Pre-trained LLM for Time Series Forecasting
 - **Authors:** Prasanjit Dey, Soumyabrata Dev, Bianca Schoen-Phelan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We address the challenge of adapting pre-trained Large Language Models (LLMs) for multivariate time-series analysis, where their deployment is often hindered by prohibitive computational and memory demands. Our solution, One-for-All, introduces Gaussian Rank-Stabilized Low-Rank Adapters (rsLoRA) to enable parameter-efficient fine-tuning of frozen LLMs. While inspired by LoRA, rsLoRA introduces a mathematically grounded rank-stabilization mechanism that enables provable gradient stability at low ranks a novel contribution absent in prior PEFT methods. Our framework injects trainable rank decomposition matrices (rank 16) into positional embeddings and output layers, while keeping self-attention weights fixed. This design reduces trainable parameters by 6.8$\times$ (vs. TimesNet), 21$\times$ (vs. GPT4TS), and 11.8$\times$ (vs. TIME-LLM), while achieving a 168-1,776$\times$ smaller memory footprint (2.2MiB vs. 340MiB-4.18GiB in SOTA models). Rigorous evaluation across six time-series tasks demonstrates that One-for-All achieves state-of-the-art efficiency-accuracy trade-offs: 5.5$\times$ higher parameter efficiency (MSE=5.50) than TimesNet and 21$\times$ better than GPT4TS, while matching their forecasting accuracy (MSE=0.33). The framework's stability is validated through consistent performance across diverse horizons (96-720 steps) and datasets (ETT, Weather, M3, M4), with 98.3% fewer parameters than conventional transformers. These advances enable deployment on edge devices for healthcare, finance, and environmental monitoring without compromising performance.
### Title:
          Beyond Ground-Truth: Leveraging Image Quality Priors for Real-World Image Restoration
 - **Authors:** Fengyang Xiao, Peng Hu, Lei Xu, XingE Guo, Guanyi Qin, Yuqi Shen, Chengyu Fang, Rihan Zhang, Chunming He, Sina Farsiu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-world image restoration aims to restore high-quality (HQ) images from degraded low-quality (LQ) inputs captured under uncontrolled conditions. Existing methods typically depend on ground-truth (GT) supervision, assuming that GT provides perfect reference quality. However, GT can still contain images with inconsistent perceptual fidelity, causing models to converge to the average quality level of the training data rather than achieving the highest perceptual quality attainable. To address these problems, we propose a novel framework, termed IQPIR, that introduces an Image Quality Prior (IQP)-extracted from pre-trained No-Reference Image Quality Assessment (NR-IQA) models-to guide the restoration process toward perceptually optimal outputs explicitly. Our approach synergistically integrates IQP with a learned codebook prior through three key mechanisms: (1) a quality-conditioned Transformer, where NR-IQA-derived scores serve as conditioning signals to steer the predicted representation toward maximal perceptual quality. This design provides a plug-and-play enhancement compatible with existing restoration architectures without structural modification; and (2) a dual-branch codebook structure, which disentangles common and HQ-specific features, ensuring a comprehensive representation of both generic structural information and quality-sensitive attributes; and (3) a discrete representation-based quality optimization strategy, which mitigates over-optimization effects commonly observed in continuous latent spaces. Extensive experiments on real-world image restoration demonstrate that our method not only surpasses cutting-edge methods but also serves as a generalizable quality-guided enhancement strategy for existing methods. The code is available.
### Title:
          Towards Empowering Consumers through Sentence-level Readability Scoring in German ESG Reports
 - **Authors:** Benjamin Josef Schüßler, Jakob Prange
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the ever-growing urgency of sustainability in the economy and society, and the massive stream of information that comes with it, consumers need reliable access to that information. To address this need, companies began publishing so called Environmental, Social, and Governance (ESG) reports, both voluntarily and forced by law. To serve the public, these reports must be addressed not only to financial experts but also to non-expert audiences. But are they written clearly enough? In this work, we extend an existing sentence-level dataset of German ESG reports with crowdsourced readability annotations. We find that, in general, native speakers perceive sentences in ESG reports as easy to read, but also that readability is subjective. We apply various readability scoring methods and evaluate them regarding their prediction error and correlation with human rankings. Our analysis shows that, while LLM prompting has potential for distinguishing clear from hard-to-read sentences, a small finetuned transformer predicts human readability with the lowest error. Averaging predictions of multiple models can slightly improve the performance at the cost of slower inference.
### Title:
          Learning Structural-Functional Brain Representations through Multi-Scale Adaptive Graph Attention for Cognitive Insight
 - **Authors:** Badhan Mazumder, Sir-Lord Wiafe, Aline Kotoski, Vince D. Calhoun, Dong Hye Ye
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding how brain structure and function interact is key to explaining intelligence yet modeling them jointly is challenging as the structural and functional connectome capture complementary aspects of organization. We introduced Multi-scale Adaptive Graph Network (MAGNet), a Transformer-style graph neural network framework that adaptively learns structure-function interactions. MAGNet leverages source-based morphometry from structural MRI to extract inter-regional morphological features and fuses them with functional network connectivity from resting-state fMRI. A hybrid graph integrates direct and indirect pathways, while local-global attention refines connectivity importance and a joint loss simultaneously enforces cross-modal coherence and optimizes the prediction objective end-to-end. On the ABCD dataset, MAGNet outperformed relevant baselines, demonstrating effective multimodal integration for advancing our understanding of cognitive function.
### Title:
          Tracking Equivalent Mechanistic Interpretations Across Neural Networks
 - **Authors:** Alan Sun, Mariya Toneva
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability (MI) is an emerging framework for interpreting neural networks. Given a task and model, MI aims to discover a succinct algorithmic process, an interpretation, that explains the model's decision process on that task. However, MI is difficult to scale and generalize. This stems in part from two key challenges: there is no precise notion of a valid interpretation; and, generating interpretations is often an ad hoc process. In this paper, we address these challenges by defining and studying the problem of interpretive equivalence: determining whether two different models share a common interpretation, without requiring an explicit description of what that interpretation is. At the core of our approach, we propose and formalize the principle that two interpretations of a model are equivalent if all of their possible implementations are also equivalent. We develop an algorithm to estimate interpretive equivalence and case study its use on Transformer-based models. To analyze our algorithm, we introduce necessary and sufficient conditions for interpretive equivalence based on models' representation similarity. We provide guarantees that simultaneously relate a model's algorithmic interpretations, circuits, and representations. Our framework lays a foundation for the development of more rigorous evaluation methods of MI and automated, generalizable interpretation discovery methods.
### Title:
          Automatic Identification of Parallelizable Loops Using Transformer-Based Source Code Representations
 - **Authors:** Izavan dos S. Correia, Henrique C. T. Santos, Tiago A. E. Ferreira
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic parallelization remains a challenging problem in software engineering, particularly in identifying code regions where loops can be safely executed in parallel on modern multi-core architectures. Traditional static analysis techniques, such as dependence analysis and polyhedral models, often struggle with irregular or dynamically structured code. In this work, we propose a Transformer-based approach to classify the parallelization potential of source code, focusing on distinguishing independent (parallelizable) loops from undefined ones. We adopt DistilBERT to process source code sequences using subword tokenization, enabling the model to capture contextual syntactic and semantic patterns without handcrafted features. The approach is evaluated on a balanced dataset combining synthetically generated loops and manually annotated real-world code, using 10-fold cross-validation and multiple performance metrics. Results show consistently high performance, with mean accuracy above 99\% and low false positive rates, demonstrating robustness and reliability. Compared to prior token-based methods, the proposed approach simplifies preprocessing while improving generalization and maintaining computational efficiency. These findings highlight the potential of lightweight Transformer models for practical identification of parallelization opportunities at the loop level.
## Keyword: autonomous driving
### Title:
          OccSim: Multi-kilometer Simulation with Long-horizon Occupancy World Models
 - **Authors:** Tianran Liu, Shengwen Zhao, Mozhgan Pourkeshavarz, Weican Li, Nicholas Rhinehart
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data-driven autonomous driving simulation has long been constrained by its heavy reliance on pre-recorded driving logs or spatial priors, such as HD maps. This fundamental dependency severely limits scalability, restricting open-ended generation capabilities to the finite scale of existing collected datasets. To break this bottleneck, we present OccSim, the first occupancy world model-driven 3D simulator. OccSim obviates the requirement for continuous logs or HD maps; conditioned only on a single initial frame and a sequence of future ego-actions, it can stably generate over 3,000 continuous frames, enabling the continuous construction of large-scale 3D occupancy maps spanning over 4 kilometers for simulation. This represents an >80x improvement in stable generation length over previous state-of-the-art occupancy world models. OccSim is powered by two modules: W-DiT based static occupancy world model and the Layout Generator. W-DiT handles the ultra-long-horizon generation of static environments by explicitly introducing known rigid transformations in architecture design, while the Layout Generator populates the dynamic foreground with reactive agents based on the synthesized road topology. With these designs, OccSim can synthesize massive, diverse simulation streams. Extensive experiments demonstrate its downstream utility: data collected directly from OccSim can pre-train 4D semantic occupancy forecasting models to achieve up to 67% zero-shot performance on unseen data, outperforming previous asset-based simulator by 11%. When scaling the OccSim dataset to 5x the size, the zero-shot performance increases to about 74%, while the improvement over asset-based simulators expands to 22.1%.
### Title:
          A Semantic Observer Layer for Autonomous Vehicles: Pre-Deployment Feasibility Study of VLMs for Low-Latency Anomaly Detection
 - **Authors:** Kunal Runwal, Swaraj Gajare, Daniel Adejumo, Omkar Ankalkope, Siddhant Baroth, Aliasghar Arab
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic anomalies-context-dependent hazards that pixel-level detectors cannot reason about-pose a critical safety risk in autonomous driving. We propose a \emph{semantic observer layer}: a quantized vision-language model (VLM) running at 1--2\,Hz alongside the primary AV control loop, monitoring for semantic edge cases, and triggering fail-safe handoffs when detected. Using Nvidia Cosmos-Reason1-7B with NVFP4 quantization and FlashAttention2, we achieve ~500 ms inference a ~50x speedup over the unoptimized FP16 baseline (no quantization, standard PyTorch attention) on the same hardware--satisfying the observer timing budget. We benchmark accuracy, latency, and quantization behavior in static and video conditions, identify NF4 recall collapse (10.6%) as a hard deployment constraint, and a hazard analysis mapping performance metrics to safety goals. The results establish a pre-deployment feasibility case for the semantic observer architecture on embodied-AI AV platforms.
### Title:
          AutoWorld: Scaling Multi-Agent Traffic Simulation with Self-Supervised World Models
 - **Authors:** Mozhgan Pourkeshavatz, Tianran Liu, Nicholas Rhinehart
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-agent traffic simulation is central to developing and testing autonomous driving systems. Recent data-driven simulators have achieved promising results, but rely heavily on supervised learning from labeled trajectories or semantic annotations, making it costly to scale their performance. Meanwhile, large amounts of unlabeled sensor data can be collected at scale but remain largely unused by existing traffic simulation frameworks. This raises a key question: How can a method harness unlabeled data to improve traffic simulation performance? In this work, we propose AutoWorld, a traffic simulation framework that employs a world model learned from unlabeled occupancy representations of LiDAR data. Given world model samples, AutoWorld constructs a coarse-to-fine predictive scene context as input to a multi-agent motion generation model. To promote sample diversity, AutoWorld uses a cascaded Determinantal Point Process framework to guide the sampling processes of both the world model and the motion model. Furthermore, we designed a motion-aware latent supervision objective that enhances AutoWorld's representation of scene dynamics. Experiments on the WOSAC benchmark show that AutoWorld ranks first on the leaderboard according to the primary Realism Meta Metric (RMM). We further show that simulation performance consistently improves with the inclusion of unlabeled LiDAR data, and study the efficacy of each component with ablations. Our method paves the way for scaling traffic simulation realism without additional labeling. Our project page contains additional visualizations and released code.
### Title:
          C-TRAIL: A Commonsense World Framework for Trajectory Planning in Autonomous Driving
 - **Authors:** Zhihong Cui, Haoran Tang, Tianyi Li, Yushuai Li, Peiyuan Guan, Amir Taherkordi, Tor Skeie
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Trajectory planning for autonomous driving increasingly leverages large language models (LLMs) for commonsense reasoning, yet LLM outputs are inherently unreliable, posing risks in safety-critical applications. We propose C-TRAIL, a framework built on a Commonsense World that couples LLM-derived commonsense with a trust mechanism to guide trajectory planning. C-TRAIL operates through a closed-loop Recall, Plan, and Update cycle: the Recall module queries an LLM for semantic relations and quantifies their reliability via a dual-trust mechanism; the Plan module injects trust-weighted commonsense into Monte Carlo Tree Search (MCTS) through a Dirichlet trust policy; and the Update module adaptively refines trust scores and policy parameters from environmental feedback. Experiments on four simulated scenarios in Highway-env and two real-world levelXData datasets (highD, rounD) show that C-TRAIL consistently outperforms state-of-the-art baselines, reducing ADE by 40.2%, FDE by 51.7%, and improving SR by 16.9 percentage points on average. The source code is available at this https URL.
### Title:
          Better than Average: Spatially-Aware Aggregation of Segmentation Uncertainty Improves Downstream Performance
 - **Authors:** Vanessa Emanuela Guarino, Claudia Winklmayr, Jannik Franzen, Josef Lorenz Rumberger, Manuel Pfeuffer, Sonja Greven, Klaus Maier-Hein, Carsten T. Lüth, Christoph Karg, Dagmar Kainmueller
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Uncertainty Quantification (UQ) is crucial for ensuring the reliability of automated image segmentations in safety-critical domains like biomedical image analysis or autonomous driving. In segmentation, UQ generates pixel-wise uncertainty scores that must be aggregated into image-level scores for downstream tasks like Out-of-Distribution (OoD) or failure detection. Despite routine use of aggregation strategies, their properties and impact on downstream task performance have not yet been comprehensively studied. Global Average is the default choice, yet it does not account for spatial and structural features of segmentation uncertainty. Alternatives like patch-, class- and threshold-based strategies exist, but lack systematic comparison, leading to inconsistent reporting and unclear best practices. We address this gap by (1) formally analyzing properties, limitations, and pitfalls of common strategies; (2) proposing novel strategies that incorporate spatial uncertainty structure and (3) benchmarking their performance on OoD and failure detection across ten datasets that vary in image geometry and structure. We find that aggregators leveraging spatial structure yield stronger performance in both downstream tasks studied. However, the performance of individual aggregators depends heavily on dataset characteristics, so we (4) propose a meta-aggregator that integrates multiple aggregators and performs robustly across datasets.
