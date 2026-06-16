# Showing new listings for Tuesday, 16 June 2026
## Keyword: SLAM
### Title:
          FD-SLAM: Fast Dense Radar-Inertial SLAM with Frequency-Domain Loop Closure and Pose Graph Optimization
 - **Authors:** Nader J. Abu-Alrub, Nathir A. Rawashdeh
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar SLAM is attractive for autonomous ground vehicles operating in visually degraded environments, however, scanning radars are noisy, have low scanning rates, and their measurements are challenging to match reliably over long trajectories. This paper presents FD-SLAM, a fast dense radar-inertial SLAM system that extends dense radar-inertial odometry with frequency-domain loop closure and pose graph optimization. The proposed method preserves an image-like structure of scanning radar measurements by using a compact frequency-domain polar descriptor for loop-candidate retrieval and a multi-stage verification pipeline based on temporal filtering, phase-correlation screening, scan-alignment similarity, and geometric consistency checks. Verified loop closures are added as non-sequential constraints in an SE(2) pose graph together with radar-inertial odometry factors. FD-SLAM is evaluated on a publicly available dataset using standard KITTI evaluation metrics. The results show that FD-SLAM improves FD-RIO baseline, achieves competitive performance against current state-of-the-art radar SLAM methods, and provides favorable rotational accuracy across multiple evaluated driving trajectories. Runtime analysis further indicates that the radar-inertial front-end operates above the radar sampling rate on a CPU-only setup, while loop closure detection and graph optimization remain suitable for parallel background execution.
### Title:
          A Smart-Scheduled Hybrid (SSH) EKF-FGO State Estimation
 - **Authors:** Eric Levi, Soosan Beheshti
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable state estimation in robotics and control re quires balancing estimation accuracy against computational cost. While filtering-based methods such as the Extended Kalman Filter (EKF) provide efficient real-time updates, and optimisation based formulations using factor graphs improve global consistency, the role of optimisation scheduling is often treated implicitly rather than examined as an explicit design variable. This paper presents an experimental study that explicitly isolates optimisation scheduling using a Smart Scheduled Hybrid (SSH) EKF-FGO framework as a controlled testbed. By combining EKF-based state propagation with periodically invoked batch optimisation and holding solver structure and effort fixed, the main contribution of this work is the experimental characterisation of optimisation scheduling as an independent design variable governing the trade-off between intermediate estimation accuracy and computational cost. Simulation results in a planar SLAM environment show that scheduling strongly influences pre optimisation drift, transient error behaviour, and runtime. In particular, the results identify operating regimes in which most of the benefit of global optimisation can be retained at a fraction of the computational cost, highlighting optimisation scheduling as an under-explored yet critical consideration in hybrid state estimation systems.
### Title:
          MVOFormer: Flow-Semantic Transformer for Robust Monocular Visual Odometry
 - **Authors:** Jituo Li, Shunwang Sun, Jialu Zhang, Xinqi Liu, Jinyao Hu, Zhicheng Lu, Sajad Saeedi, Guodong Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular visual odometry (MVO) is foundational to autonomous navigation and robotic localization. However, existing learning-based MVO approaches often struggle with either a lack of interpretable, complementary features or overly complex multi-stage architectures. These limitations inherently restrict their robustness and cross-domain generalization. In this work, we propose MVOFormer, a novel transformer framework for robust monocular visual odometry. Our architecture features a Flow-Semantic Dual Branch Encoder that synergizes dense geometric motion cues with object-centric semantic priors, explicitly distinguishing static structures from dynamic distractors. These representations are then fused by an Iterative Multimodal Decoder, enabling coarse-to-fine pose refinement while dynamically suppressing attention on unreliable regions. Extensive evaluations demonstrate that, without any target-domain fine-tuning, MVOFormer achieves superior zero-shot generalization and robustness, significantly outperforming prior learning-based frame-to-frame methods across diverse benchmarks including TartanAir, KITTI, TUM-RGBD, and ETH3D-SLAM.
### Title:
          Islamic Large Language Models: From Knowledge Acquisition to Trustworthy and Hallucination-Resistant AI
 - **Authors:** Mohammed Amine Mouhoub
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are increasingly used for knowledge-intensive question answering, including religious and legal questions. Islamic knowledge is a particularly demanding setting: answers are expected to be grounded in authoritative sources, citations must be exact, Arabic varieties differ substantially from the language of classical sources, and legitimate jurisprudential disagreement must be represented rather than collapsed into a single answer. This survey reviews the emerging field of Islamic LLMs and trustworthy Islamic AI. We organize the literature around Arabic NLP and Arabic-centric LLMs, Islamic NLP resources, Qur'anic question answering, Islamic knowledge benchmarks, retrieval-augmented generation, Islamic legal reasoning, inheritance reasoning, hallucination evaluation, and trustworthiness. We argue that fluency in Arabic is not sufficient for Islamic AI. Reliable systems require curated sources, retrieval and verification modules, citation-aware generation, madhhab-aware reasoning, human expert evaluation, and benchmarks that measure not only answer accuracy but also faithfulness, source validity, and reasoning quality. The survey concludes with a research agenda for hallucination-resistant Islamic AI systems.
### Title:
          SGM-SLAM: Scene Graph Matching for Data-Efficient Distributed SLAM
 - **Authors:** Yewei Huang, Tixiao Shan, Abhinav Rajvanshi, Niluthpol Chowdhury Mithun, Yaxuan Li, Brendan Englot, Han-Pang Chiu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a data-efficient distributed Simultaneous Localization and Mapping (SLAM) framework designed for a team of robots equipped with LiDAR, cameras, and inertial sensors. Our framework uses scene graph matching to identify inter-robot measurement constraints. Unlike prior approaches that rely on feature-level matching, our framework is the first to perform scene graph matching using only object labels and centroids. Our approach constructs a scene graph by using fused RGB-LiDAR point clouds to generate both a semantically segmented point cloud layer, and a layer of discrete bounded objects, to accompany estimated robot trajectories. Scene graph matching is performed collaboratively through exchanging and matching object data with neighboring robots. To maximize communication efficiency, we utilize a multi-step data exchange and optimization process. We demonstrate the effectiveness and efficiency of our approach using both simulation and real-world datasets collected by legged robots in indoor and outdoor environments.
### Title:
          CrossMaps: Confidence-Aware Open-Vocabulary Semantic Mapping for Rover Navigation
 - **Authors:** Jan-Niklas Klein, Sona Ghahremani, Christian Medeiros Adriano, Holger Giese
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rovers rely on perception to maintain spatial maps that encode both objects and sensor quality (e.g., range reliability, lighting artifacts, data density), guiding data fusion, embedding updates, and navigation under partial observability. To study these coupled perception-navigation processes, we present CrossMaps, a real-time confidence-aware open-vocabulary semantic mapping pipeline that constructs language-queryable maps from RGB-D data. Building on VLMaps-style approaches, CrossMaps integrates multi-scale CLIP embeddings with confidence-aware fusion and a dual-memory architecture consisting of Short-Term Memory (STM) and Long-Term Memory (LTM). The STM aggregates noisy visual observations using geometric, semantic, and temporal confidence cues, while confident and coherent cells are promoted to the LTM as persistent semantic landmarks. Designed for deployment with a Jetson Orin-powered UGV alongside SLAM, CrossMaps runs in real time and produces semantic heatmaps that can be queried with natural language to guide rover navigation.
## Keyword: odometry
### Title:
          CREST: Deployment-Realistic Hardware-in-the-Loop NAS for Embedded Sensing Systems
 - **Authors:** Joseph Q. Zales, Pragya Sharma, Mani Srivastava
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying neural networks on low-power microcontrollers (MCUs) requires selecting model architectures under tight memory, latency, and energy constraints. Existing workflows often simplify this process along one or more axes: static proxy costs such as FLOPs or parameters, treating one MCU as representative, and continuous-inference tests instead of deployed sensing schedules. These assumptions can mis-rank Pareto-front candidates, miss infeasible deployments, and obscure schedule-dependent energy. We present CREST (Cross-platform Runtime Evaluation and Search Tool), a deployment-realistic hardware-in-the-loop (HIL) neural architecture search (NAS) framework for MCU sensing systems. CREST keeps the optimizer, HIL measurement boundary, logging, and replay workflow fixed while exposing workload, model family, target backend, schedule, quantization, and scoring policy as configurable axes. This makes deployment effects experimentally separable within one reusable workflow. We evaluate CREST on inertial odometry and audio classification across three Arm Cortex-M targets. For inertial odometry, measured-energy HIL search reduces median per-inference energy by 41.7% versus FLOPs-based selection and 40.8% versus memory-traffic-based selection at similar error. FLOPs-based selection also chooses infeasible deployments on memory-constrained targets. On the STM32 N657 target, continuous-inference and duty-cycled searches produce different Pareto frontiers. For audio classification, the same application-level policy selects different DS-CNN architectures on different boards, and cross-board replay changes deployment cost substantially. Overall, CREST shows that deployment-realistic MCU NAS must jointly optimize model architecture, target platform, runtime schedule, and deployment policy rather than relying only on static proxy costs or continuous-inference measurements.
### Title:
          LV-Calib: LiDAR-Camera Extrinsic Calibration with Boundary-Response Modeling
 - **Authors:** Sheng Hong
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present LV-Calib, a calibration framework for LiDAR-camera extrinsic estimation and LiDAR boundary-response calibration using a printable planar target. The target serves as a shared observation carrier: visual fiducials provide indexed image measurements, while circular reflectivity boundaries provide LiDAR-observable structural feature points. Instead of directly fitting boundary points as ideal geometric contours, LV-Calib automatically crops background points, estimates the target plane, and iteratively refines accurate LiDAR-side 3-D feature points from intensity and geometric constraints. The refinement explicitly handles the broadened and distorted transition band induced by finite beam footprint and mixed-intensity returns around black-white reflectivity discontinuities. Given these refined LiDAR features, we formulate a weighted reprojection-consistent extrinsic optimization with LiDAR feature alignment, where image observations are kept in the reprojection domain and LiDAR feature residuals are weighted by refinement confidence. Finally, using the estimated extrinsic and the extracted transition band, LV-Calib calibrates the LiDAR boundary response by estimating pitch-yaw-range residual statistics of boundary-overlap samples. Experiments on printed-board calibration data demonstrate sub-pixel reprojection accuracy, millimeter-level LiDAR feature consistency, and improved odometry performance. Code and calibration data will be released for reproducible evaluation.
### Title:
          FD-SLAM: Fast Dense Radar-Inertial SLAM with Frequency-Domain Loop Closure and Pose Graph Optimization
 - **Authors:** Nader J. Abu-Alrub, Nathir A. Rawashdeh
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar SLAM is attractive for autonomous ground vehicles operating in visually degraded environments, however, scanning radars are noisy, have low scanning rates, and their measurements are challenging to match reliably over long trajectories. This paper presents FD-SLAM, a fast dense radar-inertial SLAM system that extends dense radar-inertial odometry with frequency-domain loop closure and pose graph optimization. The proposed method preserves an image-like structure of scanning radar measurements by using a compact frequency-domain polar descriptor for loop-candidate retrieval and a multi-stage verification pipeline based on temporal filtering, phase-correlation screening, scan-alignment similarity, and geometric consistency checks. Verified loop closures are added as non-sequential constraints in an SE(2) pose graph together with radar-inertial odometry factors. FD-SLAM is evaluated on a publicly available dataset using standard KITTI evaluation metrics. The results show that FD-SLAM improves FD-RIO baseline, achieves competitive performance against current state-of-the-art radar SLAM methods, and provides favorable rotational accuracy across multiple evaluated driving trajectories. Runtime analysis further indicates that the radar-inertial front-end operates above the radar sampling rate on a CPU-only setup, while loop closure detection and graph optimization remain suitable for parallel background execution.
### Title:
          PointDiffusion: Diffusion-Based Scene Completion in the Point Cloud Domain
 - **Authors:** Chidera Agbasiere, Mikhail Sannikov, Faith Ogunwoye, Erik Shaikhiev, Alex Kozinov, Ilya Mikhalchuk, Iana Zhura, Dzmitry Tsetserukou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing dense 3D scenes from sparse LiDAR point clouds is a fundamental challenge in autonomous driving, where latent diffusion models offer a promising solution. However, existing approaches rely on object-level autoencoders that collapse into unstable global representations at outdoor scale and suffer from ground truth data corrupted by odometry drift that systematically degrades supervision quality. Furthermore, multi-step diffusion inference incurs prohibitive latency for real-time deployment. We propose a novel multi-token Gaussian VAE with cross-attention pooling for stable scene-scale LiDAR compression, combined with an anchor-based ICP ground truth refinement pipeline that eliminates drift-induced noise from training supervision. Together, these components enable a scaffold-free single-step diffusion completion model that achieves an approximately 16x reduction in squared Chamfer distance on SemanticKITTI seq. 08 (0.396 m^2 to 0.024 m^2), surpasses LiDiff and ScoreLiDAR by 17-19% and 10-11%, respectively, and operates at 25-143x lower inference latency. Our results demonstrate that data quality dominates model design in this regime and that multi-token latent spaces provide a stable first stage for latent diffusion-based scene completion.
### Title:
          MVOFormer: Flow-Semantic Transformer for Robust Monocular Visual Odometry
 - **Authors:** Jituo Li, Shunwang Sun, Jialu Zhang, Xinqi Liu, Jinyao Hu, Zhicheng Lu, Sajad Saeedi, Guodong Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular visual odometry (MVO) is foundational to autonomous navigation and robotic localization. However, existing learning-based MVO approaches often struggle with either a lack of interpretable, complementary features or overly complex multi-stage architectures. These limitations inherently restrict their robustness and cross-domain generalization. In this work, we propose MVOFormer, a novel transformer framework for robust monocular visual odometry. Our architecture features a Flow-Semantic Dual Branch Encoder that synergizes dense geometric motion cues with object-centric semantic priors, explicitly distinguishing static structures from dynamic distractors. These representations are then fused by an Iterative Multimodal Decoder, enabling coarse-to-fine pose refinement while dynamically suppressing attention on unreliable regions. Extensive evaluations demonstrate that, without any target-domain fine-tuning, MVOFormer achieves superior zero-shot generalization and robustness, significantly outperforming prior learning-based frame-to-frame methods across diverse benchmarks including TartanAir, KITTI, TUM-RGBD, and ETH3D-SLAM.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Bayesian Optimization for Learning Nonlinear MPC in Autonomous Agent Navigation
 - **Authors:** Lorenzo Ortolani, Gabriel Voss, Gabriele Beltrami, Francesco Dorati, Tommaso Felice Banfi
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time autonomous navigation in dynamic, unknown environments remains a fundamental challenge for mobile robotics. We propose a map-free framework that tightly integrates reactive rolling-horizon planning with nonlinear Model Predictive Control (MPC). At each control cycle, a LiDAR-based Gaussian occupancy representation is constructed and used to generate collision-free trajectories via A* search, which are then tracked by a CasADi/IPOPT MPC formulation incorporating a smooth sigmoid obstacle barrier. To improve robustness to parameter sensitivity, we adopt an offline Bayesian optimization scheme based on Tree-structured Parzen Estimators (TPE), which identifies near-optimal controller parameters with respect to a composite navigation objective. In addition, a Gaussian Process surrogate is used to analyze parameter sensitivity and provide insight into the optimization landscape. The proposed framework is robot-agnostic and is evaluated on the Unitree Go2 quadruped in simulation using Gazebo, followed by deployment on the physical robot. Experimental results show that parameters tuned in simulation transfer effectively to hardware, maintaining comparable performance without additional tuning. The full system achieves up to a 90.0\% navigation success rate when deployed, along with a 38.9\% average improvement in the evaluation metrics across simulated environments.
### Title:
          α-Fair Insurance Pricing: A Fairness Continuum
 - **Authors:** Tianhe Zhang, Xiguang Liu, Peng Shi
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fairness in insurance pricing remains a long-standing and deeply debated puzzle. On one hand, insurers, driven by profitability considerations, set premiums that differentiate across individual risks to achieve actuarial fairness. On the other hand, insurance serves a critical societal function by pooling risks across a population, motivating cross-subsidization among groups to promote solidarity fairness. The tension between these two competing notions of fairness makes insurance pricing inherently complex, particularly in modern settings where granular data allow for increasingly fine risk differentiation and regulators face growing pressure to protect vulnerable groups. To address this challenge, we propose an $\alpha$-\textbf{F}air \textbf{I}ndividual \textbf{S}olvent \textbf{P}remium ($\alpha$-FISP) framework for insurance pricing that explicitly captures the trade-off between actuarial and solidarity fairness while guaranteeing solvency, a fundamental requirement in insurance operations. We formulate the pricing problem as a constrained optimization task, where actuarially fair premiums are adjusted subject to budget constraints on cross-subsidization within each risk class. This formulation naturally yields a family of solutions parameterized by $\alpha$, tracing a continuum between purely actuarial and purely solidarity-based pricing and enabling decision-makers to select an operating point along this fairness spectrum. We derive theoretical guarantees for the proposed framework. Numerical experiments show that $\alpha$-FISP is computationally tractable and aligns well with the U.S. regulatory regimes featuring heterogeneous state-level fairness requirements.
### Title:
          LV-Calib: LiDAR-Camera Extrinsic Calibration with Boundary-Response Modeling
 - **Authors:** Sheng Hong
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present LV-Calib, a calibration framework for LiDAR-camera extrinsic estimation and LiDAR boundary-response calibration using a printable planar target. The target serves as a shared observation carrier: visual fiducials provide indexed image measurements, while circular reflectivity boundaries provide LiDAR-observable structural feature points. Instead of directly fitting boundary points as ideal geometric contours, LV-Calib automatically crops background points, estimates the target plane, and iteratively refines accurate LiDAR-side 3-D feature points from intensity and geometric constraints. The refinement explicitly handles the broadened and distorted transition band induced by finite beam footprint and mixed-intensity returns around black-white reflectivity discontinuities. Given these refined LiDAR features, we formulate a weighted reprojection-consistent extrinsic optimization with LiDAR feature alignment, where image observations are kept in the reprojection domain and LiDAR feature residuals are weighted by refinement confidence. Finally, using the estimated extrinsic and the extracted transition band, LV-Calib calibrates the LiDAR boundary response by estimating pitch-yaw-range residual statistics of boundary-overlap samples. Experiments on printed-board calibration data demonstrate sub-pixel reprojection accuracy, millimeter-level LiDAR feature consistency, and improved odometry performance. Code and calibration data will be released for reproducible evaluation.
### Title:
          G2IA: Geometry-Guided Instance-Aware Retrieval and Refinement for Cross-Modal Place Recognition
 - **Authors:** Xianyun Jiao, Jingyi Xu, Zhongmiao Yan, Xieyuanli Chen, Lin Pei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-modal place recognition (CMPR) enables camera-only robots to localize against pre-built LiDAR maps in autonomous navigation scenarios. This image-to-point-cloud setting is challenged by two coupled ambiguities: the modality gap between perspective RGB appearance and sparse metric geometry, and perceptual aliasing among urban places with similar roads, facades, intersections, and object arrangements. Instead of treating CMPR as a single global descriptor matching problem, we argue that reliable retrieval requires both geometry-aware representation alignment and fine-grained candidate verification. In this paper, we propose G2IA, a geometry-guided instance-aware framework for image-to-point-cloud place recognition. In the retrieval stage, visual geometry priors from VGGT and instance features are integrated to construct place descriptors that are more compatible with LiDAR-derived map representations. In the refinement stage, the retrieved candidates are re-ranked by explicitly verifying whether local instance shapes and their relative spatial layouts are consistent across modalities. Experiments on public benchmarks demonstrate that G2IA consistently improves image-to-point-cloud place recognition under different localization thresholds, and exhibits strong cross-dataset generalization.
### Title:
          A Corridor-Scale CARLA-VISSIM Co-Simulation Framework for Multi-Intersection Urban Traffic
 - **Authors:** Sima Ashayer, Austin Haris, Mina Sartipi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents an implemented CARLA-VISSIM co-simulation framework for an urban corridor comprising approximately fifteen connected intersections centered on Martin Luther King Jr. Boulevard in Chattanooga, Tennessee. The system integrates CARLA 0.10.0 Unreal Engine 5 with PTV VISSIM 2026 through a bidirectional, step-synchronized interface that couples VISSIM's microscopic vehicle, pedestrian, and signal-controller logic with CARLA's high-fidelity 3D rendering. A LiDAR-derived elevation model and RoadRunner-based High Definition (HD) map provide terrain-accurate road geometry deployed consistently across both simulators. The framework incorporates explicit actor ownership, mirrored lifecycle management, coordinate reconciliation, and a latest-state-per-actor update policy, enabling stable interaction between VISSIM-controlled traffic and a CARLA-controlled ego vehicle. A corridor-scale case study demonstrates consistent traffic-signal mirroring, synchronized vehicle-pedestrian interactions, and stable mixed-authority operation under peak loads of approximately 100 vehicles and 100 pedestrians. The deployment captures the interaction of the five signalized intersections along MLK Street and their connecting upstream and downstream intersections, revealing synchronization challenges unique to multi-intersection corridors. Results indicate that this MLK-centered corridor provides an effective testbed for verifying cross-simulator consistency and that the proposed architecture supports reliable, perception-ready co-simulation for corridor-level traffic studies.
### Title:
          LoComposition: Terrain-Adaptive Energy-Efficient Quadruped Locomotion without Gait Priors
 - **Authors:** Loukas Kordos, Leonard T. Franz, Simon Rappenecker, Oliver Hausdoerfer, Angela P. Schoellig, Pavel Kolev, Georg Martius
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning-based quadrupedal locomotion typically relies on complex reward formulations that entangle task specification, operational limits, gait preference, and terrain adaptation within a single optimization objective. We instead treat these functions through distinct mechanisms: rewards for task specification, constraints for operational limits, energy minimization for gait preference, and exteroceptive perception for adapting energy use to terrain difficulty. We show that these components jointly enable efficient, terrain-adaptive locomotion, and that removing each component exposes a distinct failure mode. Our formulation removes explicit gait priors (including air-time, contact-count, and foot-clearance targets) in favor of emergent behavior. Compared to a conventional complex-reward baseline, our formulation achieves comparable terrain traversal while reducing cost of transport by 56% and operational-limit violations by 96%. The resulting policies transfer zero-shot to a physical Unitree Go2 using LiDAR-based elevation mapping. Project website with videos: this https URL.
### Title:
          PointDiffusion: Diffusion-Based Scene Completion in the Point Cloud Domain
 - **Authors:** Chidera Agbasiere, Mikhail Sannikov, Faith Ogunwoye, Erik Shaikhiev, Alex Kozinov, Ilya Mikhalchuk, Iana Zhura, Dzmitry Tsetserukou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing dense 3D scenes from sparse LiDAR point clouds is a fundamental challenge in autonomous driving, where latent diffusion models offer a promising solution. However, existing approaches rely on object-level autoencoders that collapse into unstable global representations at outdoor scale and suffer from ground truth data corrupted by odometry drift that systematically degrades supervision quality. Furthermore, multi-step diffusion inference incurs prohibitive latency for real-time deployment. We propose a novel multi-token Gaussian VAE with cross-attention pooling for stable scene-scale LiDAR compression, combined with an anchor-based ICP ground truth refinement pipeline that eliminates drift-induced noise from training supervision. Together, these components enable a scaffold-free single-step diffusion completion model that achieves an approximately 16x reduction in squared Chamfer distance on SemanticKITTI seq. 08 (0.396 m^2 to 0.024 m^2), surpasses LiDiff and ScoreLiDAR by 17-19% and 10-11%, respectively, and operates at 25-143x lower inference latency. Our results demonstrate that data quality dominates model design in this regime and that multi-token latent spaces provide a stable first stage for latent diffusion-based scene completion.
### Title:
          GraphBEV++: Multi-Modal Feature Alignment for Autonomous Driving
 - **Authors:** Ziying Song, Caiyan Jia, Lin Liu, Shaoqing Xu, Lei Yang, Yadan Luo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feature misalignment in BEV perception is a critical yet often overlooked challenge in autonomous driving, especially under calibration uncertainties between LiDAR and camera sensors. To address this issue, we propose a robust multi-modal fusion framework, GraphBEV++, which systematically mitigates projection-induced misalignment. The framework consists of two key modules: LocalAlign-v2 and GlobalAlign-v2. LocalAlign-v2 introduces neighborhood-aware depth features via graph matching to correct local misalignment. It supports both LSS-based and query-based BEV representations, making it compatible with BEVFusion and BEVFormer architectures for consistent cross-paradigm alignment. GlobalAlign-v2 encompasses two variants: Deformable and Diffusion. The Deformable variant addresses global misalignment in LSS-based multi-modal BEV by explicitly learning cross-modal feature offsets. In contrast, the Diffusion variant targets implicit misalignment in query-based BEV by injecting noise to simulate misalignment and employing a denoising process to recover aligned features. Experimental results show that GraphBEV++ achieves state-of-the-art performance under misalignment noise on nuScenes and Waymo subset, improves long-range detection on Argoverse2, and generalizes effectively to the 3D occupancy prediction task, consistently improving occupancy estimation accuracy and robustness under both clean and noisy settings. Furthermore, GraphBEV++ effectively alleviates misalignment issues in end-to-end autonomous driving. Compared with five baselines (UniAD, VAD, FusionAD, MomAD, and WoTE), it demonstrates superior performance in both open-loop (nuScenes) and closed-loop (Bench2Drive and NAVSIM) evaluations across perception, prediction, and planning tasks.
### Title:
          Automated Digital Twin Construction for Highway Scenarios Using LiDAR Point Clouds and OpenStreetMap
 - **Authors:** Yongqi Zhao, Dong Bi, Paul Kovacevic, Tomislav Mihalj, Martin Schabauer, Johannes Betz, Arno Eichberger
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate road environment modeling is fundamental to the simulation and validation of automated driving systems. However, constructing road maps in standardized formats such as ASAM OpenDRIVE from real-world sensor data remains a time-consuming and costly process. Mobile mapping LiDAR captures accurate lane-level geometry but is confined to the driven corridor, while OpenStreetMap (OSM) provides broad road network topology but lacks geometric precision at the lane level. To address this, an automated workflow is proposed to fuse LiDAR point clouds with OSM data to generate georeferenced ASAM OpenDRIVE maps of highway environments, requiring minimal manual intervention. The pipeline reconstructs mainline roads from LiDAR-derived measurements and infers ramp geometry and topology from the OSM road graph, enabling complete highway interchange modeling without full sensor coverage. Experiments demonstrate a mean lateral RMSE of 0.740 m, and the generated maps are directly usable in mainstream simulation platforms including IPG CarMaker and Esmini. These results validate the effectiveness of combining measurement-derived geometry with map-derived topology for automated OpenDRIVE digital twin generation. The project code is available at this https URL
### Title:
          SGM-SLAM: Scene Graph Matching for Data-Efficient Distributed SLAM
 - **Authors:** Yewei Huang, Tixiao Shan, Abhinav Rajvanshi, Niluthpol Chowdhury Mithun, Yaxuan Li, Brendan Englot, Han-Pang Chiu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a data-efficient distributed Simultaneous Localization and Mapping (SLAM) framework designed for a team of robots equipped with LiDAR, cameras, and inertial sensors. Our framework uses scene graph matching to identify inter-robot measurement constraints. Unlike prior approaches that rely on feature-level matching, our framework is the first to perform scene graph matching using only object labels and centroids. Our approach constructs a scene graph by using fused RGB-LiDAR point clouds to generate both a semantically segmented point cloud layer, and a layer of discrete bounded objects, to accompany estimated robot trajectories. Scene graph matching is performed collaboratively through exchanging and matching object data with neighboring robots. To maximize communication efficiency, we utilize a multi-step data exchange and optimization process. We demonstrate the effectiveness and efficiency of our approach using both simulation and real-world datasets collected by legged robots in indoor and outdoor environments.
### Title:
          SurroundNEXO: Ego-Centric Metric Bridging for Spatially Consistent Geometry in Autonomous Driving
 - **Authors:** Shuai Yuan, Runxi Tang, Yuzhou Ji, Fudong Ge, Hanshi Wang, Yifei Wang, Xianming Zeng, Jianyun Xu, Xingliang Liu, Yanfeng Wang, Zhipeng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern autonomous driving depends on accurate metric 3D understanding for perception, reconstruction, and planning, which in turn requires reliable multi-camera depth prediction. However, the outward-facing nature of vehicle-mounted surround-view camera rigs inherently limits visual overlap across views, challenging the correspondence-based assumptions that underpin conventional multi-view geometry. To bridge this gap, we present SurroundNEXO, named after the Spanish word nexo for a geometric link, a low-overlap multi-camera metric depth framework that grounds cross-view reasoning in ego-centric geometry rather than dense visual correspondences. Instead of directly enforcing early global fusion, SurroundNEXO first assigns image tokens globally comparable ego-frame viewing directions through Ego-Ray Positional Encoding, then uses sparse LiDAR measurements as metric anchors to propagate absolute scale cues, and finally expands feature interaction progressively from view-local modeling to decomposed spatio-temporal reasoning and global integration. This design enables metric-scale depth prediction with improved spatial consistency across weakly overlapping cameras. Across low-overlap autonomous driving benchmarks, including NuScenes, Waymo and DDAD, SurroundNEXO reduces single-view error by 33.2%, improves cross-view consistency by 10.5%, and enhances metric reconstruction quality by 25.6% compared with SOTA methods. It further remains robust under extremely sparse depth prompts and exhibits strong zero-shot generalization to unseen camera layouts.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Double-Helix Vision (DH-V2): A Geometry-Based Visual Sampler for Bandwidth-Constrained Perception
 - **Authors:** Jinwen Wen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Double-Helix Vision (DH), a geometry-based visual sampler that compresses 2D images into compact 1D signals using paired golden-ratio-inspired spiral trajectories. Rather than processing every pixel uniformly, DH employs two phase-shifted helices (Alpha and Beta, offset by 180 degrees) to sample the image with biologically-inspired foveation: high density at the center, sparse coverage at the periphery. At 4K resolution, DH achieves a 1,433x compression ratio (99.93% reduction) while preserving the geometric structure of the scene. The full perception pipeline -- including spatial mapping, temporal collision detection, and intra-frame structural disparity estimation -- runs in 0.52 ms at 1080p on CPU-only hardware, with no neural network dependencies. On CIFAR-10 at extreme sampling budgets (K=128 points per helix), DH achieves a +6.03% accuracy gain over uniform random sampling. A JSON-serializable Robotics API is provided, delivering sub-millisecond spatial perception reports in 2.7 KB packets. Code and benchmarks are available under the MIT License.
### Title:
          Pandas for Reproducible Data Analysis: From Spreadsheets to Research-Grade Python Workflows
 - **Authors:** Sidney Shapiro, Daniel Pearson, Emiliano Sebastian Gonzalez Venegas
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spreadsheet-heavy analytical work remains common in business analytics, operations reporting, and applied research, yet workbooks that grow through formulas, manual edits, and copy-paste refresh are difficult to audit, reproduce, and govern at scale. When tabular work requires repeatability, validation, version control, automated refresh, or integration with statistics and machine learning, analysts need a transformation layer that preserves familiar table concepts while making assumptions explicit. This paper treats the Python pandas library as that layer: a practical bridge between spreadsheet practice and research-grade workflows, not a wholesale replacement for Excel. The paper contributes an Excel-to-pandas migration mapping, a taxonomy of nine workflow categories, seven end-to-end examples drawn from business analytics and applied research, a failure-mode catalog, and reusable code recipes for governed tabular work. pandas is most useful when tabular analysis must be repeatable, auditable, and defensible, while Excel can remain a familiar input and output interface for stakeholders who need workbooks.
### Title:
          KATANA: A Fast, Low-Power Mapping of Kalman Filters onto Edge NPUs for Real-Time Tracking
 - **Authors:** Bodhisatwa Kundu, Anish Rooj, Sumit Saha, Abhradeep Sarkar, Arghadip Das, Arnab Raha, Mrinal K. Naskar
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State estimation is the closed-loop core of every real-time tracking system, from radar surveillance and counter-UAV defense to autonomous driving and robotics. These deployments run on edge platforms, where defense systems mount on vehicles and drones, and civilian pipelines live on cars and handheld devices. Here, every additional watt of compute erodes mission duration or operational range. Two hard constraints follow: each new measurement must be fused before the next control cycle, and the total compute must fit within a strict battery and thermal power envelope. The Linear and Extended Kalman Filters (LKF, EKF) are dominant estimators on these systems, but today they execute almost exclusively on CPUs, which serialize multi-object tracking (MOT) updates, or on custom FPGA/ASIC accelerators that lengthen design cycles. Contemporary AI-PC SoCs, like the Intel Core Ultra Series 1 and 2, integrate a low-power, data-parallel Neural Processing Unit (NPU). We therefore ask whether the Kalman filter can be mapped onto this existing matrix engine to meet real-time and low-power budgets simultaneously, avoiding a dedicated accelerator and keeping the CPU and GPU free for primary workloads. We present KATANA, an NPU-aware optimization framework delivering the first end-to-end mapping of the LKF and EKF onto a commercial NPU, alongside a cross-platform characterization on shipping AI-PC silicon. KATANA applies three algebraic graph rewrites: subtract-to-add reformulation via a precomputed negative-projection matrix H_neg, static-shape tensor fusion, and block-diagonal batched parallelization, ensuring 100% of operations execute on the DPU matrix engine. On the Series 2, the optimized batched EKF reaches 223.35 FPS at 13.43 W active power, and the LKF reaches 408.73 FPS at 14.05 W, delivering up to a 97.9% reduction in dynamic energy versus the CPU implementation.
### Title:
          A Structure-preserving Adaptive-Rank Approach to the High-Dimensional Wigner-Poisson System
 - **Authors:** Andrew J. Christlieb, Sining Gong, Jing-Mei Qiu, Nanyi Zheng
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Wigner-Poisson system is a deterministic phase-space model for quantum kinetic electron dynamics, but high-dimensional simulations are limited by the full 3D3V phase space and the nonlocal Wigner potential. We develop a structure-preserving, sampling-based adaptive-rank solver in hierarchical Tucker format for finite-$H$ regimes in which Wigner-Poisson solutions exhibit exploitable low-rank structure. The central difficulty is that adaptive compression can destroy the Fourier-Hermitian tensor symmetry required for a real inverse velocity transform and can break discrete global conservation laws. We address these issues with a Fourier-Hermitian-symmetry-aware sampling and mapping procedure and a global moment correction enforcing mass, momentum, and self-consistent total energy. Numerical tests for two-stream instability and strong Landau damping in 2D2V and 3D3V show roundoff-level conservation, preservation of the real-valued inverse transform, and approximately linear scaling with respect to the number of grid points per coordinate over the tested rank range. The results demonstrate that long-time 3D3V Wigner-Poisson simulations can be performed without assembling the full phase-space tensor.
### Title:
          City landscape in sight: A crowdsourced framework for unlocking urban-scale window view perceptions from real estate imagery
 - **Authors:** Chucai Peng, Sijie Yang, Ang Liu, Yang Xiang, Zhixiang Zhou, Filip Biljecki
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 City landscapes viewed through home windows influence quality of life, yet perceptions of actual window views at the urban scale remain understudied. This study presents an approach for large-scale mapping of perceptions using 12,334 window view images (WVIs) collected from actual residential properties listed on real estate platforms in Wuhan, China, representing a rarely explored form of urban view imagery that offers advantages over the rendered or simulated window views commonly examined in previous studies. Through a non-immersive virtual reality platform, we collected 27,477 pairwise comparisons across six perceptual dimensions (e.g.\ Vivid) from 304 participants based on 499 WVIs. A hybrid neural network model was trained to predict human perceptions of all crowdsourced WVIs and map their spatial distribution. Results reveal significant spatial autocorrelation with distinct hot and cold spots across the whole city. Floor level strongly influences human perceptions: while higher floors offer more preferred and extensive window views, lower-floor windows provide residents with quiet and vivid views. An inference model further shows that window view composition matters considerably: high ratios of sky, trees, and low-rise buildings enhance people's preferences and perceptions of vividness, whereas high ratios of high-rise buildings increase perceptions of monotony and oppression. Importantly, these effects are non-linear: the excessive presence of certain elements can alter their impact on human perception. This work advances urban-scale understanding of residents' visual experiences and provides evidence-based guidance for human-centric urban planning and real estate to optimise visual landscapes from windows.
### Title:
          Co-Creating Buildable and Open Social Robot Study Companions with University Students
 - **Authors:** Farnaz Baksh, Matevž B. Zorec, Feiazie Baksh, Karl Kruusamäe
 - **Subjects:** Subjects:
Robotics (cs.RO); Computers and Society (cs.CY); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-source social robots offer accessibility, repairability, and student empowerment, yet the build itself often presents a barrier. Existing platforms either ship pre-assembled, foreclosing hands-on learning, or expose students to unfamiliar fasteners, opaque wiring, and inaccessible service points that erode engagement. Whether targeted mechanical redesign can lower this barrier whilst maintaining structural integrity remains untested. Here we show that Design for Assembly (DfA) and Design for Disassembly (DfD) interventions reshape how a build feels before they shorten how long it takes. Working with university students in Guyana and Estonia, we applied the Double Diamond framework to co-create the Robot Study Companion (RSC) v4.1: mapping pain points, then redesigning its chassis around twist-lock fasteners, snap-fit joints, and tool-free service latches. Across two studies with developers and first-time builders, system usability climbed from Poor to Excellent (SUS 59.4 to 89.4), perceived workload trended downward (NASA-TLX 4.29 to 4.00), and mean assembly time trended downward (21.4 to 13.7 minutes, with juniors' learning effect), whilst orientation cues and navigation continuity for first-time builders emerged as the next documentation frontier. Perceived workload, not completion time, appears to govern whether students take up open hardware.
### Title:
          Learning Earthquake Wave Arrival Time Picking from Labels with Inaccuracies
 - **Authors:** Sen Li, Xu Yang, S. Mostafa Mousavi, Anye Cao, Keting Fan, Yaoqi Liu, Changbin Wang, Qiang Niu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Geophysics (physics.geo-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inaccurately labeled training data, or "label noise", poses a significant threat to the integrity of supervised machine learning models. This corruption directly degrades performance by teaching the model erroneous mappings between features and labels, which leads to poor generalization and reduced accuracy on properly labeled validation and test data. Current seismological applications mainly rely on large-scale training sets or data augmentation to reduce the label-noise impact, which can be labor-intensive and costly. Here, we introduce a Label Noise-Contrastive Robust Learning (LaNCoR) approach that can effectively handle noisy labels in seismic signal processing tasks, without requiring large-scale training datasets. In this approach, the input waveform feature and label representation distributions are aligned in the feature space to correct mislabeling and reduce its impact on the training process. We present LaNCoR's performance on the task of P-phase arrival-time picking of real microseismic data using two baseline models and training approaches. Our results indicate that LaNCoR can improve performance by up to 28.8% across performance metrics. This approach holds great promise for model training in seismology and geosciences.
### Title:
          Toward the Whole Picture: Accumulative Fingerprint Mapping and Reconstruction for Small-Area Mobile Sensors
 - **Authors:** Xiongjun Guan, Jianjiang Feng, Jie Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Small-area fingerprint sensing on mobile devices creates a fundamental mismatch between acquisition and recognition: each touch captures only a tiny, pose-varying local patch, while reliable biometric matching ultimately requires a stable and sufficiently complete fingerprint representation. Existing pipelines largely cope with this mismatch by treating repeated touches as independent partial templates, which leads to repeated registration, repeated matching, and no guarantee of adequate global coverage. In this paper, we advocate a different formulation, namely \emph{accumulative fingerprint mapping and reconstruction} for small-area mobile sensing. Rather than matching every partial patch separately, the proposed perspective converts a sequence of local observations into a unified fingerprint state that is progressively refined as new touches arrive and can be matched only once after consolidation. As a concrete baseline, we present a classical pipeline that performs patch-wise structural feature extraction, feature-level registration and fusion, fingerprint map construction, and phase-based ridge reconstruction. More importantly, we position this baseline within a broader mobile fingerprint framework that integrates structured token learning, two-stage pose reasoning, and diffusion-based generative reconstruction. This viewpoint reframes mobile fingerprint recognition from multi-capture multi-match processing to accumulative map building, state refinement, and one-shot matching, offering a principled route toward efficient, pose-robust, and deployment-friendly biometrics for small-area mobile platforms. The baseline implementation has been publicly released at this https URL.
### Title:
          Open-World Video Segmentation
 - **Authors:** Qing Su, Kaiyang Li, Yuan Zhuang, Fei Miao, Shihao Ji
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While video segmentation has advanced rapidly on short clips and closed-set benchmarks, open-world video segmentation remains largely unexplored. The challenge is twofold: (1) existing methods are not designed to support object discovery and identity maintenance in long videos of dynamic ego-motion, and (2) existing evaluation protocols rely on a rigid 1:1 matching that unfairly penalizes semantically valid predictions with mismatched granularity. To address both gaps, we introduce Savvy, a practical and strong system for zero-shot open-world long-horizon video segmentation. Savvy combines hierarchical mask discovery, deferred admission, and track consolidation to support persistent object discovery, safe track promotion, and stable long-range identity maintenance. We further propose OGA, a granularity-aware evaluation suite for open-world video segmentation. Built on a Granularity-Agnostic (GA) matching protocol, OGA relaxes conventional 1:1 matching to an n:1 mapping, but still enforces temporal rigor by detecting support discontinuities through sever points and scoring each reference object through its dominant coherent fragment. This prevents fragmented or flickering support from being over-rewarded while enabling GA-adapted metrics and structural diagnostics: identity persistence (IP), and identity concentration (IC). On VIPSeg, we show that standard 1:1 evaluation substantially underestimates open-world methods, whereas GA evaluation recovers much of their suppressed performance. On the more realistic long-horizon benchmarks: ScanNet and HM3D, Savvy consistently outperforms strong baselines across both classical and proposed metrics, including STQ, VPQ$_\infty$, IP and IC. Together, these results establish a practical benchmark and a strong baseline for open-world long-horizon video segmentation.
### Title:
          Visualizing Uncertainty: Spatial Maps of Missing and Conflicting Evidence in Deep Learning
 - **Authors:** Dong Hyun Jeong, Feng Chen, Jin-Hee Cho, Lance M. Kaplan, Audun Jøsang, Soo-Yeon Ji
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding when and why deep neural networks are uncertain is crucial for deploying reliable machine learning systems in safety-critical domains. While existing uncertainty quantification methods provide scalar measures of model confidence, they offer limited insight into which spatial regions of an input contribute to different types of uncertainty. We propose a novel visualization framework, Uncertainty Activation Map (UAM), that combines Evidential Deep Learning (EDL) with Full-Gradient Class Activation Mapping (FullGrad) to generate interpretable spatial uncertainty activation maps. Our approach distinguishes between two fundamental types of uncertainty: vacuity, representing lack of evidence, and dissonance, capturing conflicting evidence between competing hypotheses. By leveraging the complete gradient decomposition property of FullGrad and the principled uncertainty quantification of Subjective Logic, our method produces theoretically grounded visualizations that highlight specific image regions responsible for model uncertainty. With this framework, vacuity and dissonance activation maps are generated by computing belief-weighted attributions, enabling identification of where models lack knowledge versus where they encounter ambiguous evidence. Extensive evaluations across multiple benchmark datasets demonstrate that the proposed framework effectively addresses the critical gap between uncertainty quantification and explainability, providing intuitive visual feedback to assess model reliability in complex visual recognition tasks.
### Title:
          Learning a Sampling-Free Variational DNN Plugin from Tiny Training Sets to Refine OOD Segmentation With Uncertainty Estimation
 - **Authors:** Jimut B. Pal, Suyash P. Awate
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Methodology (stat.ME); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep neural networks (DNNs) frequently fail to generalize to out-of-distribution (OOD) medical images because of variations in scanners and acquisition protocols. Retraining DNN models to address these distribution shifts is often impractical due to the high cost of acquiring and annotating new medical datasets. To address this, we introduce VarDeepPCA, a novel lightweight variational DNN framework designed to restore/refine degraded segmentation maps by leveraging intrinsic geometric priors. Unlike existing approaches that require target-domain data or extensive pre-training, our VarDeepPCA explicitly learns a distribution of valid anatomical geometries using only small in-distribution (ID) datasets. Theoretically, our novel variational learning framework leverages a reinterpretation of the softmax mapping to implicitly perform exact distribution modeling, thereby enabling computationally efficient, sampling-free learning and inference. This also enables VarDeepPCA to provide uncertainty estimates associated with its restored segmentation maps. We empirically validate our framework across 4 distinct clinical applications, using 14 publicly available datasets, involving segmentation of the myocardium, neuroretinal rim, prostate, and fetal head. Comparisons against 15 existing methods demonstrate that VarDeepPCA consistently restores segmentation maps produced by the existing methods on OOD data to (i) significantly improve anatomical plausibility of geometries and clinical utility of the segmentations, and (ii) significantly reduce errors, without needing any more training data than that used by existing methods.
### Title:
          LoComposition: Terrain-Adaptive Energy-Efficient Quadruped Locomotion without Gait Priors
 - **Authors:** Loukas Kordos, Leonard T. Franz, Simon Rappenecker, Oliver Hausdoerfer, Angela P. Schoellig, Pavel Kolev, Georg Martius
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning-based quadrupedal locomotion typically relies on complex reward formulations that entangle task specification, operational limits, gait preference, and terrain adaptation within a single optimization objective. We instead treat these functions through distinct mechanisms: rewards for task specification, constraints for operational limits, energy minimization for gait preference, and exteroceptive perception for adapting energy use to terrain difficulty. We show that these components jointly enable efficient, terrain-adaptive locomotion, and that removing each component exposes a distinct failure mode. Our formulation removes explicit gait priors (including air-time, contact-count, and foot-clearance targets) in favor of emergent behavior. Compared to a conventional complex-reward baseline, our formulation achieves comparable terrain traversal while reducing cost of transport by 56% and operational-limit violations by 96%. The resulting policies transfer zero-shot to a physical Unitree Go2 using LiDAR-based elevation mapping. Project website with videos: this https URL.
### Title:
          Friction Characterization of a Cable-Driven Differential Actuation System for Lower-Limb Exoskeletons
 - **Authors:** Alberto Maria Nobili, Fabio Salsedo, Alessandro Filippeschi
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lower-limb exoskeletons require actuation systems that can provide accurate joint torque control while preserving low mass and encumbrance. Conventional architectures often rely on independently actuated joints and joint-level torque sensors, increasing system complexity and weight. This paper presents a novel differential actuation architecture for hip-knee flexion/extension, enabling cooperative torque sharing between two motors via a linear differential mapping between motor and joint. To compensate for transmission losses, a model-based friction estimation strategy is developed and experimentally implemented, allowing accurate joint torque estimation without the need for torque sensors. The proposed solution is validated on a physical prototype, demonstrating the feasibility of sensorless torque estimation in a differentially actuated hip-knee module of a lower-limb exoskeleton.
### Title:
          $λ$-Reachability: Geometric-Horizon Safety Bellman Equations for Humanoid Safety
 - **Authors:** Rui Chen, Shangtao Li, Yifan Sun, Changliu Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce $\lambda$-Reachability, a scalable approach to Hamilton--Jacobi safety analysis for high-dimensional robotic systems. Unlike prior discounted formulations that rely on fixed one-step Bellman updates, $\lambda$-Reachability employs a stochastic multi-step estimator of the safety value, using a geometrically distributed rollout horizon together with a randomly absorbed terminal. Conceptually analogous to TD($\lambda$), $\lambda$-Reachability interpolates between local self-consistency updates and long-horizon max-over-trajectory safety targets via an interpretable horizon-control parameter. Unlike TD($\lambda$), where the terminal value is always incorporated in learning targets, the terminal safety value in $\lambda$-Reachability is only used at a probability controlled by parameter $\delta$. We formally show that for $\delta<1$, the update induces a contraction mapping that allows temporal-difference learning; as $\lambda \to 1$, the estimator recovers the undiscounted reachability objective. We apply $\lambda$-Reachability to high-dimensional safety learning problems with both simulated and real humanoid robots under balance and collision avoidance constraints. Experimental results demonstrate that $\lambda$-Reachability significantly improves both safe-set boundary classification and safety margin estimation compared to single-step temporal-difference baselines.
### Title:
          AME: A Multi-Type Contributor Attribution Framework in Generative AI Markets
 - **Authors:** Yang Shi, Songwen Pei, Yang Gao, Bingxue Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative AI enables value creation through multi-stage collaboration among heterogeneous contributors, including training data, base models, fine-tuning behaviors, and prompts. However, how to fairly allocate the data value remains largely unexplored. This paper formulates multi-stage generative AI value allocation as a new research problem and identifies three core challenges: heterogeneous data contribution valuation, data rights mapping, and trustworthy execution. We propose AME (Attribution-Mapping-Execution) framework, a unified framework that integrates data contribution valuation, data rights mapping, and trustworthy execution into a single workflow. Experimental results demonstrate that AME framework achieves data value allocation outcomes more consistent with human reference judgments while maintaining low-cost trustworthy execution. Our work provides an initial foundation for value assessment and revenue allocation in generative AI data markets.
### Title:
          Geospatial sensitivity of transmission-constrained ACOPF to generator retirement
 - **Authors:** Willa Gutowski, Ulyana Shyrokaya, Nicholson Koukpaizan, Joshua Hambrick, Slaven Peles, Eve Tsybina
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The US faces a growing resource adequacy challenge: new loads are being added at unprecedented scale while aging generating assets are being retired. In transmission-constrained grids, it is difficult to determine which units can be safely retired and which cannot be retired and instead require lifetime extensions until new generation can be built. Historically, this analysis was prohibitively time consuming. Transmission-constrained AC optimal power flow (ACOPF) is computationally intensive, and a thorough comparison and prioritization of generators could require hundreds or thousands of scenarios. We present an HPC-enabled framework that enables computation and geospatial mapping of the effects of generator retirement in terms of voltage magnitude and angle effects in the steady state. Specifically, our framework detects the effects of generator retirement using a simple k-nearest-neighbors model and a voltage-class-adjusted neighbor model. We demonstrate the results on over 8,000 generator retirement scenarios for a 70,000-bus transmission-constrained synthetic grid.
### Title:
          AIA: A Customized Multi-core RISC-V SoC for Discrete Sampling Workloads in 16 nm
 - **Authors:** Shirui Zhao, Nimish Shah, Wannes Meert, Marian Verhelst
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Probabilistic models (PMs) are essential in advancing machine learning capabilities, particularly in safety-critical applications involving reasoning and decision-making. Among the methods employed for inference in these models, sampling-based Markov Chain Monte Carlo (MCMC) techniques are widely used. However, MCMC methods come with significant computational costs and are inherently challenging to parallelize, resulting in inefficient execution on conventional CPU/GPU platforms. To overcome these challenges, this paper presents AIA, a multi-core RISC-V System-on-Chip (SoC) design fabricated using Intel's 16 nm process technology. Our Approximate Inference Accelerator (AIA) is specifically designed to empower edge devices with robust decision-making and reasoning abilities. The AIA architecture incorporates a RISC-V host processor to manage chip-to-chip data communication and a 2D mesh of 16 custom versatile RISC-V cores optimized for high-efficiency approximate inference. Each core features (i) custom instructions and datapath blocks for non-normalized Knuth-Yao (KY) sampling, as well as for the interpolation of non-linear functions (e.g., logarithmic, exponential), and (ii) direct data access to the register file of each neighboring core, to reduce the data movement costs of frequent data exchanges between nearby cores. To further capitalize on the parallelism potential in MCMC algorithms, we developed a specialized compile chain that enables efficient spatial mapping and scheduling across the cores.
### Title:
          AIA: A 16nm Multicore SoC for Approximate Inference Acceleration Exploiting Non-normalized Knuth-Yao Sampling and Inter-Core Register Sharing
 - **Authors:** Shirui Zhao, Nimish Shah, Wannes Meert, Marian Verhelst
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Probabilistic graphical models (PMs) are popular to empower machine learning with the ability of reasoning and decision-making. To perform approximate inference in PMs, sampling-based Markov Chain Monte Carlo (MCMC) algorithms are commonly employed. Unfortunately, MCMC is compute-intensive and hard to run in parallel, resulting in inefficient execution on modern CPU/GPU platforms. This paper proposes \name{}, an Approximate Inference Accelerator designed to empower decision-making and reasoning at the edge. \name{} consists of a RISC-V host, and a 2D mesh of 16 customized RISC-V cores optimized to efficiently support PM inference, each featuring (i) a novel non-normalized Knuth-Yao sampler and interpolation unit; and (ii) core-to-core direct data access via the register file, which provides solutions for compute-intensive operations. To fully exploit the parallel potential of Markov Chain Monte Carlo (MCMC) algorithms, a customized compiler chain has been developed for effective spatial mapping and scheduling on the chip. \name{} can generate 1277 MSample/s at 0.9V and 20 GSamples/s/W at 0.7V which is up to 2$\times$ faster and 1.45x more energy efficient compared to the previous state-of-the-art Markov Random Field (MRF) accelerator. We further map Bayesian Networks benchmark onto \name{} to show the flexibility of our design.
### Title:
          LiteOdyssey: A Lightweight Reasoning AI Agent for Interpretable Rare-Disease Diagnosis
 - **Authors:** Minh-Ha Nguyen, Erica Gray, Chih-Ting Yang, Rizwan Hamid, Lingyao Li, Siyuan Ma, Thomas A. Cassini, Cathy Shyr
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most medical AI systems improve by scaling additional machinery: more fine-tuning data, more agents, and/or larger retrieval databases. In rare-disease diagnosis, however, such scaling can produce systems that are difficult to deploy, audit, and maintain. We asked whether state-of-the-art diagnostic performance could instead be achieved by extending the reasoning chain of a single AI agent: guiding it with a diagnostic policy, developed through human-AI collaboration and augmenting with freely available biomedical tools. We introduce LiteOdyssey, a lightweight rare-disease diagnostic framework that guides reasoning language model through a clinical genetics workflow. This framework was developed through Policy Iteration with Human Feedback (PIHF) and uses dynamic access to public biomedical tools. On two challenging benchmarks that provide only patient clinical features, LiteOdyssey achieved state-of-the-art performance, with an overall disease Recall@1 of 59.3% over the combined 1,243 cases of LIRICAL (n = 370) and the PhenoPacket Store (n = 873). Both benchmarks have a high proportion of ultra-rare disease (a prevalence below 1 in 1,000,000, with ultra-rare shares of approximately 45% and 52.8%, respectively). On the more difficult PhenoPacket subset, where causal diseases were not mapped to Orphanet in our rarity-mapping pipeline, LiteOdyssey achieved 60.7% Recall@1, compared with 10.7% for the same baseline model (GPT-5.4) without tools. This performance was achieved without fine-tuning, multi-agent ensembles, or a large case-retrieval database. Gains were also observed in the following: on cases never seen during development, on a private cohort of real-world rare disease patients, and on a smaller open-weights model. LiteOdyssey suggests a path toward rare-disease AI systems that are accurate, easier to deploy, and more transparent for physician review.
### Title:
          Robust Neural Tucker Factorization with Bias Correction and Adaptive Initialization
 - **Authors:** Yuchao Su, Yixin Ran
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-dimensional incomplete (HDI) tensors are widely used in traffic and climate applications, but sparse observations make accurate completion difficult. The intrinsic non-linear dynamics and non-stationary variations across distinct multi-modal fields severely hinder the efficacy of conventional linear reconstruction frameworks. Neural Tucker factorization provides an effective framework for modeling high-order interactions among tensor modes. By parameterizing underlying structural characteristics into continuous latent spaces, neural representations circumvent the rigid low-rank constraints of classical algebra. However, its performance can still be affected by implementation-level choices, especially parameter initialization and the bias configuration of the final output mapping. Suboptimal initializations frequently lead to variance explosion across the cubically expanded interaction spaces, driving the subsequent non-linear activation boundaries into severe gradient saturation zones, while the omission of a dedicated translation parameter forces interaction weights to implicitly absorb global statistical deviations. This paper proposes a simple yet effective neural Tucker factorization model with Kaiming initialization and bias correction (KaBiN) for HDI tensor completion. The proposed model utilizes Kaiming uniform initialization for the embedding and Tucker linear parameters, and adopts a simple bias correction in output mapping. By elegantly decoupling global mean shifts from local structural representations, the framework provides a highly stable and well-conditioned optimization landscape. Experiments on three real-world HDI tensor datasets show that KaBiN achieves better performance than the original NeuTucF, while introducing minimal computational overhead.
### Title:
          Towards UAV Image Dehazing: A UAV Atmospheric Scattering Model, Benchmark, and Geometry-Aware Deep Unfolding Network
 - **Authors:** Wenxuan Fang, Jiangwei Weng, Yu Zheng, Junkai Fan, Guangfa Wang, Xiang Chen, Jian Yang, Jun Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In UAV applications, haze significantly obscures distant details and weaken structural information, hindering the recovery of details. Current UAV scenarios still face two key challenges: (i) paired hazy/clean images from the real world are unobtainable, while the classical atmospheric scattering model is inadequate for modeling the spatially non-uniform haze in UAV imagery; (ii) existing dehazing methods struggle to remove the heavy haze accumulated in the upper regions of UAV images. To address these issues, we first propose a UAV Atmospheric Scattering Model (UASM), which explicitly incorporates flight altitude, viewing pitch, and extinction to characterize the non-uniform haze distribution in UAV imaging. Based on UASM, we develop a physics-driven dehazing framework, termed Geometry-aware Proximal Deep Unfolding Network (GP-DUN). Specifically, GP-DUN consists of three key modules: a Latent Geometry Estimator (LGE) that infers transmittance consistent with UAV imaging geometry, a Geometry-aware Gradient Descent Module (GeoGDM) that embeds UASM into the data-fidelity term and performs physics-consistent closed-form updates, and an Pooling-Expert Proximal Mapping Module (PE-PMM) that learns an implicit prior to restore textures and structures beyond the capability of explicit physical modeling. In addition, we further construct UASM-HazeSet, which provides controllable paired synthetic data together with 2,285 real UAV haze images for testing. Extensive experiments show that GP-DUN consistently outperforms existing methods on both UASM-HazeSet and real UAV haze benchmarks.
### Title:
          MUNI: Multimodal Unified Latent Diffusion for Coherent Any-to-Any Generation
 - **Authors:** Kyeongmin Yeo, Yunhong Min, Minhyuk Sung
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce MUNI, an end-to-end multimodal latent diffusion framework for any-to-any generation that unifies subset-conditioned cross-modal generation and unconditional joint sampling through a shared stochastic latent. Existing multimodal generative models are largely LLM-based, which limits leveraging modality-specific generators and requires text-paired data for training. Recent diffusion- and flow-based any-to-any extensions take a different direction but still rely on text-aligned embeddings, fully-paired training, or matched-dimensionality deterministic mappings. MUNI rests on two complementary contributions, one architectural and one in the training objective. First, we extend latent diffusion to multimodal any-to-any generation end-to-end: instead of the standard two-stage recipe that precomputes a frozen latent space and then fits a prior over it, MUNI jointly trains modality-specific encoders, expressive decoders, and a single shared flow-based prior under one objective. Second, we identify that the standard aggregation rules of multimodal variational inference are insufficient once coupled with a learned prior and expressive decoders. A suitable shared latent must simultaneously satisfy coherence across generated modalities, predictive sufficiency of subset latents, and minimality of the latent content. We propose a routed training objective whose structural choices align the latent with these criteria and admit a minimal-sufficiency characterization in the realizable setting. Experiments on PolyMNIST-Quadrant-Labels and a large-scale image-text-audio benchmark show MUNI matching or exceeding the strongest baselines on conditional generation while opening its largest margins on unconditional coherence. Project page: this https URL.
### Title:
          Automated Digital Twin Construction for Highway Scenarios Using LiDAR Point Clouds and OpenStreetMap
 - **Authors:** Yongqi Zhao, Dong Bi, Paul Kovacevic, Tomislav Mihalj, Martin Schabauer, Johannes Betz, Arno Eichberger
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate road environment modeling is fundamental to the simulation and validation of automated driving systems. However, constructing road maps in standardized formats such as ASAM OpenDRIVE from real-world sensor data remains a time-consuming and costly process. Mobile mapping LiDAR captures accurate lane-level geometry but is confined to the driven corridor, while OpenStreetMap (OSM) provides broad road network topology but lacks geometric precision at the lane level. To address this, an automated workflow is proposed to fuse LiDAR point clouds with OSM data to generate georeferenced ASAM OpenDRIVE maps of highway environments, requiring minimal manual intervention. The pipeline reconstructs mainline roads from LiDAR-derived measurements and infers ramp geometry and topology from the OSM road graph, enabling complete highway interchange modeling without full sensor coverage. Experiments demonstrate a mean lateral RMSE of 0.740 m, and the generated maps are directly usable in mainstream simulation platforms including IPG CarMaker and Esmini. These results validate the effectiveness of combining measurement-derived geometry with map-derived topology for automated OpenDRIVE digital twin generation. The project code is available at this https URL
### Title:
          ArtNet: A JEPA-Like Articulatory Predictive Framework for Robust Zero-Shot Phoneme Recognition
 - **Authors:** Zeqian Hu, Fuliang Weng, Shu Shang, Yaqian Zhou
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Zero-shot cross-lingual phoneme recognition is often hindered by the fragility of direct acoustic-to-symbol mapping, which is susceptible to language-specific variations. Echoing joint-embedding predictive architecture (JEPA) work in vision, we propose ArtNet, a framework that explores a structured feature prediction task based on articulatory features to enhance acoustic robustness. Specifically, ArtNet integrates an articulatory predictor, designed to extract universal articulatory representations from self-supervised learning (SSL) features, with a variational information bottleneck (VIB) to suppress language-specific variations. Experiments on seven unseen languages demonstrate that ArtNet, particularly when synergized with the proposed vector-space inventory alignment (VSIA) strategy, significantly outperforms competitive baselines, achieving a 20.56\% relative reduction in phoneme error rate (PER) and 7.01\% in phoneme feature error rate (PFER).
### Title:
          3D Classification of Paramagnetic Rim Lesions in Multiple Sclerosis via Asymmetric QSM-FLAIR Modeling
 - **Authors:** Veronica Pignedoli, Giacomo Boffa, Nicoletta Noceti, Matilde Inglese, Francesca Odone, Matteo Moro
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Paramagnetic rim lesions (Rim$^+$) identified on susceptibility-sensitive MRI have recently emerged as a specific biomarker of chronic active inflammation in Multiple Sclerosis (MS) and are associated with long-term disability progression. However, susceptibility imaging and expert interpretation remain limited to specialized centers, visual assessment is time-consuming and variable, and the low prevalence of Rim$^+$ lesions poses severe class imbalance challenges for automated analysis. We propose a 3D multimodal deep learning framework for lesion-level Rim$^+$/Rim$^-$ classification from Quantitative Susceptibility Mapping (QSM) and FLAIR MRI. The architecture explicitly models modality asymmetry by treating QSM as the primary susceptibility-driven signal and conditioning it with FLAIR-derived structural context. To improve robustness under limited data, we employ self-supervised multimodal pretraining followed by supervised fine-tuning with contrastive regularization. The method was evaluated on a clinically acquired cohort of 88 people with MS with expert lesion annotations as reference standard. Results highlight improved performance compared to prior architectures, supporting the effectiveness of asymmetric multimodal modeling for automated chronic active lesion identification.
### Title:
          Connecting Speech to Words through Images
 - **Authors:** Gabriel Pirlogeanu, Dan Oneata, Horia Cucu, Herman Kamper
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 How can we learn the mapping between written words and their spoken counterparts in the absence of explicit textual supervision? We present a visually grounded method for building a vocabulary of spoken words using only images and their spoken descriptions. First, image captioning systems are used to build a vocabulary of written words representing salient visual concepts in the images. For each word, we then find utterances whose image captions contain that word. Then we use an unsupervised word discovery technique to align these utterances to locate instances of the target word. The result is spoken word segments that are linked to written words -- all accomplished without any text supervision. In spoken word retrieval and keyword spotting experiments, the proposed approach outperforms a strong neural baseline while being more interpretable. These results demonstrate the feasibility of the approach in English and motivate future work on low-resource languages without transcripts.
### Title:
          From the NYU Ultracomputer to Modern Exascale: A Historical and Architectural Survey of In-Network Computing and Scalable Synchronization
 - **Authors:** Lars Warren Ericson
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Hardware Architecture (cs.AR); General Literature (cs.GL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a historical and technical survey of the hardware architectures, interconnection networks, and synchronization primitives that have shaped massively parallel systems over the past four decades. We examine the design of the NYU Ultracomputer and the IBM Research Parallel Processor Prototype (RP3), focusing on the hardware implementation of the Fetch-and-Add primitive in multistage interconnection networks. We contrast these early attempts at fine-grained, shared-memory hardware combining with the distributed-memory architectures of the IBM SP series and the modern in-network computation models found in NVIDIA SHARP and HPE Slingshot. We provide a technical analysis of message-passing synchronization, presenting a complete profiling of MPI operation frequencies and detailing the low-level hardware mapping of one-sided RMA atomics to PCIe Atomics and GPU caches. We investigate the software-hardware boundary in modern deep learning, detailing how HIP translation, Triton compilation, and 4-bit quantization (W4A16) execute on modern heterogeneous silicon. To evaluate alternative network node designs, we present a historical hardware case study analyzing the feasibility of implementing active combining switches using message-passing Inmos Transputers programmed in Occam. Finally, we contextualize the evolution of concurrent software synchronization by examining Isaac Dimitrovsky's parallel "group lock" primitive, tracing its downstream echoes in group mutual exclusion (GME) and room synchronization, and reflect on the historical, philosophical divide between American systems engineering and European formal methods.
### Title:
          Latent Space Reinforcement Learning for Inverse Material Estimation in Food Fracture Simulation
 - **Authors:** Adrian Ramlal, Yuhao Chen, John S. Zelek
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Realistic visual simulation of food manipulation requires accurate material parameters, yet these are difficult to measure directly and vary across the heterogeneous regions of a single food item. We address the inverse problem of estimating material parameters from a target description of fracture behavior in a non-differentiable continuum damage mechanics simulator. Using orange peeling as a test case, we train a neural surrogate on 2,000 forward simulations and compare Covariance Matrix Adaptation Evolution Strategy (CMA-ES, a gradient-free evolutionary optimizer) with Proximal Policy Optimization (PPO, a reinforcement learning algorithm) across the original 9-dimensional parameter space and two learned 4-dimensional latent representations. Since different oranges have different material properties, a practical inverse system must handle arbitrary targets without retraining. We train a goal-conditioned PPO policy that learns a general inverse mapping: given any target description of peeling behavior, the policy produces a material parameter estimate in a single forward pass (8 surrogate evaluations, approximately 10ms). Operating in a normalizing flow latent space with a shared surrogate evaluator, the goal-conditioned policy achieves 0.642 actual recovery when validated through the simulator, outperforming the original parameter space by 23%. A warm-start extension that initializes CMA-ES refinement from the policy's output further improves recovery to 0.828 with 540 evaluations. These findings provide a practical framework for inverse food physics and lay groundwork for vision-driven material identification from video observations of food manipulation.
### Title:
          ExoTraj: A General Lower-limb Exoskeleton Assistance Policy for Complex Environments
 - **Authors:** Xiao-Yin Liu, Guotao Li, Long Sun, Xu Liang, Zeng-Guang Hou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive torque prediction in dynamic exoskeleton scenarios requires expensive motion capture systems, which are infeasible in complex outdoor environments. Trajectory prediction has emerged as one of the effective approaches to address such an issue. However, the core challenges of exoskeleton trajectory prediction are twofold: establishing the mapping from multi-modal features to trajectory information; constructing the mapping from trajectory to torque. For the former, most existing methods perform only single-step prediction and neglect inter-subject trajectory variability, thereby limiting the trajectory optimization space and prediction generalization. To address this, this paper proposes a fast flow matching method that enables accurate trajectory prediction and better generalization for real-time performance, where trajectory generation errors and encoded observations are used to guide the training direction. For the second challenge, due to the high dynamics of the human-robot system and the strong coupling between perception and control, simple control methods struggle to achieve efficient assistance based on the predicted trajectory. This paper utilizes model predictive control and designs a novel optimization objective to optimize torque, ensuring the exoskeleton achieves comfortable and robust assistance. By integrating the above two components, the unified policy, denoted as ExoTraj, is developed to enable adaptive assistance in complex outdoor scenarios without high data acquisition cost. Experimental results show that compared to traditional methods, ExoTraj reduces cross-subject prediction error by 14.0% during the online phase and maintains robustness against external noise. Relative to the zero torque condition, ExoTraj decreases metabolic rate by 11.5-24.4%, heart rate by 1.7-19.5%, and peak muscle activation levels by 10.9-41.3%, respectively.
### Title:
          SGM-SLAM: Scene Graph Matching for Data-Efficient Distributed SLAM
 - **Authors:** Yewei Huang, Tixiao Shan, Abhinav Rajvanshi, Niluthpol Chowdhury Mithun, Yaxuan Li, Brendan Englot, Han-Pang Chiu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a data-efficient distributed Simultaneous Localization and Mapping (SLAM) framework designed for a team of robots equipped with LiDAR, cameras, and inertial sensors. Our framework uses scene graph matching to identify inter-robot measurement constraints. Unlike prior approaches that rely on feature-level matching, our framework is the first to perform scene graph matching using only object labels and centroids. Our approach constructs a scene graph by using fused RGB-LiDAR point clouds to generate both a semantically segmented point cloud layer, and a layer of discrete bounded objects, to accompany estimated robot trajectories. Scene graph matching is performed collaboratively through exchanging and matching object data with neighboring robots. To maximize communication efficiency, we utilize a multi-step data exchange and optimization process. We demonstrate the effectiveness and efficiency of our approach using both simulation and real-world datasets collected by legged robots in indoor and outdoor environments.
### Title:
          CrossMaps: Confidence-Aware Open-Vocabulary Semantic Mapping for Rover Navigation
 - **Authors:** Jan-Niklas Klein, Sona Ghahremani, Christian Medeiros Adriano, Holger Giese
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rovers rely on perception to maintain spatial maps that encode both objects and sensor quality (e.g., range reliability, lighting artifacts, data density), guiding data fusion, embedding updates, and navigation under partial observability. To study these coupled perception-navigation processes, we present CrossMaps, a real-time confidence-aware open-vocabulary semantic mapping pipeline that constructs language-queryable maps from RGB-D data. Building on VLMaps-style approaches, CrossMaps integrates multi-scale CLIP embeddings with confidence-aware fusion and a dual-memory architecture consisting of Short-Term Memory (STM) and Long-Term Memory (LTM). The STM aggregates noisy visual observations using geometric, semantic, and temporal confidence cues, while confident and coherent cells are promoted to the LTM as persistent semantic landmarks. Designed for deployment with a Jetson Orin-powered UGV alongside SLAM, CrossMaps runs in real time and produces semantic heatmaps that can be queried with natural language to guide rover navigation.
### Title:
          Qwen-RobotWorld Technical Report: Unifying Embodied World Modeling through Language-Conditioned Video Generation
 - **Authors:** Jie Zhang, Xiaoyue Chen, Anzhe Chen, Chenxu Lv, Deqing Li, Gengze Zhou, Hang Yin, Haoqi Yuan, Haoyang Li, Jiahao Li, Jiazhao Zhang, Jingren Zhou, Kaiyuan Gao, Kun Yan, Lihan Jiang, Ningyuan Tang, Pei Lin, Qihang Peng, Shengming Yin, Tianhe Wu, Tianyi Yan, Xiao Xu, Yan Shu, Yanran Zhang, Ye Wang, Yi Wang, Yilei Chen, Yixian Xu, Yiyang Huang, Yuxiang Chen, Zekai Zhang, Zhendong Wang, Zhixing Lei, Zhixuan Liang, Zihao Liu, Zikai Zhou, Xiong-Hui Chen, Chenfei Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Qwen-RobotWorld, a language-conditioned video world model for embodied intelligence. With natural language as a unified action interface, it predicts physically grounded future visual trajectories from current observations across robotic manipulation, autonomous driving, indoor navigation, and human-to-robot transfer. This unified formulation provides three promising application directions: synthetic data generation for policy training augmentation, scalable virtual environments for policy evaluation, and language-guided planning signals for downstream robot control. This is achieved through a three-part design: a) Double-Stream MMDiT with MLLM Action Encoding, where a 60-layer double-stream diffusion transformer couples frozen Qwen2.5-VL semantics with video-VAE latents through layer-wise joint attention; b) Embodied World Knowledge (EWK), an 8.6M video-text corpus (200M+ frames) with action-language mapping over 20+ embodiments and 500+ action categories; and c) General+Expert Progressive Curriculum, a two-stage training strategy that first learns general visual priors and then injects embodied specialization under a shared language interface. Extensive results show strong competitiveness: ranks 1st overall on EWMBench and DreamGen Bench, outperforms all open-source models on WorldModelBench and PBench. Additional zero-shot analyses on RoboTwin-IF benchmark further support robust generalization and multi-view consistency.
## Keyword: localization
### Title:
          Knowledge-Based Zero-Replay Debugging of Multi-Agent LLM Traces
 - **Authors:** Dong Ho Kang, Hyeonjeong Cha, Daein Weon
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable operation of multi-agent large language model (LLM) systems depends on debugging long execution traces, where the few causally decisive events are buried in unstructured logs of messages, routes, memory writes, and tool calls. The standard tool is counterfactual replay (rewind, edit, and re-run the trajectory to measure each event's effect), but its cost grows linearly with the number of candidate events, making exhaustive replay infeasible at scale. We frame trace debugging as a knowledge-based decision-support problem. Each trace is compiled into a structured event knowledge graph over routing, memory, tool-use, uncertainty, and latent evidence, and a calibrated predictor decides where a scarce replay budget should be spent. We do not propose a new replay oracle; we propose a method to predict its results without paying the replay cost. We formulate zero-replay counterfactual-effect prediction: given a trace under a fixed budget, predict which events the oracle would mark high-effect before any replay is performed. BranchPoint-Latent is a lightweight predictor over observable, structural, uncertainty, and latent features of the knowledge graph. Calibrated against a deterministic replay oracle across 37 trace families, a single learning-to-rank gradient-boosted predictor raises per-trace localization (Branch Recall@5) from 0.73 to 0.93 on held-out families at zero oracle-replay cost. Rather than claiming universal dominance, we characterize when cheap graph centrality suffices and when learned evidence is necessary. The result is an auditable, cost-efficient decision-support system for AI-reliability debugging, positioned explicitly on the cost-accuracy frontier with reproducible artifacts.
### Title:
          Spectro-Temporal Interference Confounds Phase Encoding in Spatial Audio Foundation Models
 - **Authors:** Yuxuan Chen, Haoyuan Yu, Peize He
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent spatial self supervised audio models achieve high performance on localization tasks, raising questions about their encoding of microsecond interaural phase fine structures. We propose a psychoacoustic benchmark based on the binaural masking level difference to evaluate this. Using an equalization cancellation baseline and a GCC PHAT positive control we evaluate nine frozen audio models spanning binaural SSL, monaural SSL, and neural audio codecs. Four monaural negative controls yield zero BMLD confirming binaural specificity. Two general purpose binaural SSL models exhibit minimal phase sensitivity while dedicated binaural spatial SSL models achieve BMLD comparable to the analytical baseline. Progressive physical ablations show that general purpose binaural SSL models rely on spectro temporal interference textures rather than cross channel phase computation. High detection rates in speech reflect a confounding reliance on broadband envelopes rather than genuine phase encoding.
### Title:
          Multi-HMR 2: Multi-Person Camera-Centric Human Detection, Mesh Recovery and Tracking
 - **Authors:** Guénolé Fiche, Philippe Weinzaepfel, Romain Brégier, Fabien Baradel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most advances in human mesh recovery (HMR) have focused on pelvis-centered recovery, overlooking metric 3D localization and detection accuracy in the camera coordinate system - two key factors for real-world applications such as human-robot interaction and social scene understanding. Current evaluation protocols often ignore these aspects, emphasizing per-person, root-centered recovery rather than camera-space perception. As a result, existing approaches rely on fixed camera assumptions or handcrafted post-processing, limiting their robustness and practical deployment. We introduce Multi-HMR 2, a simple yet robust DETR-based framework for Multi-person Camera-centric Human detection, mesh Recovery, and tracking. Multi-HMR 2 predicts a scene-consistent camera together with human meshes, enabling metric 3D localization without ground-truth intrinsics. Moreover, by distilling image-based memory features from SAM2, Multi-HMR 2 extends to tracking, achieving consistent identity association without video supervision. Despite its conceptual simplicity - no handcrafted components, no video input, and no ground-truth cameras - Multi-HMR 2 achieves state-of-the-art pelvis-centered performance while substantially improving detection accuracy and metric 3D localization.
### Title:
          Task-Aware Environment Augmentation for Reliable Navigation via Shielded Conditional Diffusion
 - **Authors:** Bharawee Phoompho, Gokul Puthumanaillam, Yan Miao, Ruben Hernandez, Tim Bretl, Sayan Mitra, Melkior Ornik
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable trajectory planning under partial observability depends not only on computing a feasible geometric path, but also on whether the robot receives informative observations while executing that trajectory. Existing approaches usually keep the environment fixed and adapt the robot through belief-space planning, active localization, or added sensing, often incurring costly uncertainty propagation and brittle behavior in observation-poor regions. We flip this perspective and address the largely open problem of \emph{task-aware environment augmentation}: given a mapped environment, a planned task trajectory, and a small budget of visual fiducial markers, where should the environment be augmented so that the planned trajectory can be executed reliably under uncertainty? Our key observation is that useful marker layouts are defined by the localization support they provide along the task trajectory: a small number of well-timed observations can be sufficient to prevent uncertainty from accumulating in regions where state-estimation error would otherwise compromise control. Building on this observation, we present \tbp{SCoDA}, $\textbf{S}$hielded $\textbf{Co}$nditional $\textbf{D}$iffusion for Environment $\textbf{A}$ugmentation. \tbp{SCoDA} learns a conditional distribution over high-performing fiducial layouts from data, using the environment, planned trajectory, disturbance context, and desired execution profile as conditioning. Its shielded sampler reasons over where along the planned execution pose corrections should occur, and steers this distribution toward task-relevant, finite-budget augmentations. Across simulated benchmarks and hardware deployments, we show that \tbp{SCoDA} improves trajectory execution reliability and completion time over strong baselines. Code, models and dataset available at: \hyperlink{this http URL}{this https URL}
### Title:
          G2IA: Geometry-Guided Instance-Aware Retrieval and Refinement for Cross-Modal Place Recognition
 - **Authors:** Xianyun Jiao, Jingyi Xu, Zhongmiao Yan, Xieyuanli Chen, Lin Pei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-modal place recognition (CMPR) enables camera-only robots to localize against pre-built LiDAR maps in autonomous navigation scenarios. This image-to-point-cloud setting is challenged by two coupled ambiguities: the modality gap between perspective RGB appearance and sparse metric geometry, and perceptual aliasing among urban places with similar roads, facades, intersections, and object arrangements. Instead of treating CMPR as a single global descriptor matching problem, we argue that reliable retrieval requires both geometry-aware representation alignment and fine-grained candidate verification. In this paper, we propose G2IA, a geometry-guided instance-aware framework for image-to-point-cloud place recognition. In the retrieval stage, visual geometry priors from VGGT and instance features are integrated to construct place descriptors that are more compatible with LiDAR-derived map representations. In the refinement stage, the retrieved candidates are re-ranked by explicitly verifying whether local instance shapes and their relative spatial layouts are consistent across modalities. Experiments on public benchmarks demonstrate that G2IA consistently improves image-to-point-cloud place recognition under different localization thresholds, and exhibits strong cross-dataset generalization.
### Title:
          S1-DeepResearch: Beyond Search, Toward Real-World Long-Horizon Research Agents
 - **Authors:** Yao Dong, Xinglin Xiao, Liwei Dong, Xinlong Jin, Zhengbo Li, Heng Zhang, Duyun Wang, Nan Xu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Information Retrieval (cs.IR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep research agents aim to solve complex knowledge-intensive tasks through long-horizon planning, evidence gathering, reasoning, and report generation. While recent progress in search agents has demonstrated strong capabilities in information retrieval and answer verification, most existing training datasets remain search-centric, focusing primarily on closed-ended question answering and information localization. As a result, they mainly train information-seeking behavior while providing limited coverage of key deep research capabilities, including evidence integration, knowledge synthesis, planning, file understanding, and structured report generation. In this work, we propose a unified trajectory construction paradigm for deep research agents that combines closed-ended QA and open-ended exploration. The proposed framework consists of graph-grounded task formulation, agentic trajectory rollout, and multi-dimensional trajectory verification, enabling scalable synthesis of high-quality agentic trajectories spanning long-chain complex reasoning, deep research instruction following, report writing, file understanding and generation, and skills usage. Compared with existing search-oriented datasets, our synthesized trajectories place greater emphasis on knowledge synthesis, complex reasoning, and planning. S1-DeepResearch-32B achieves state-of-the-art performance among open-source models of comparable scale across 20 benchmarks spanning five capability dimensions, including complex reasoning, instruction following, report generation, file understanding, and skills usage. On several challenging deep research benchmarks, it approaches the performance of leading proprietary frontier models. These results highlight the importance of jointly modeling information acquisition, knowledge synthesis, and planning-oriented agent behaviors for building effective deep research agents.
### Title:
          Post-Launch Capability Expansion of Vision-Language Models via Prompting for On-Orbit Spacecraft Inspection
 - **Authors:** Nicholas A. Welsh, Lennon J. Shikhman, Monty Nehru Attazs, Seemanthini K. Putane, Van Minh Nguyen, Ryan T. White
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spaceborne inspection systems often deploy perception models prior to launch, after which updating model weights or expanding fixed label sets becomes operationally impractical. While supervised models can be integrated pre-flight, adding new semantic capabilities in orbit requires retraining and re-uploading parameters. We investigate whether prompt-driven vision--language models can enable post-launch semantic expansion, allowing new spacecraft components to be specified via natural-language prompts without modifying onboard weights. We evaluate zero-shot instance segmentation of spacecraft components under a strictly frozen, single-pass inference protocol on a test set of $129$ images of previously unseen satellites. Under fixed global thresholds and no post-processing, SAM3 achieves $0.385$ mAP@$0.5$ and $0.267$ mAP@$0.5{:}0.95$. Performance is strongly scale-dependent: large structural elements like spacecraft bodies ($0.639$ AP@$0.50$) and solar arrays ($0.598$ AP@$0.5$) localize reliably, while relatively small appendages like antennas ($0.221$ AP@$0.5$) and thrusters ($0.081$ AP@$0.5$) remain difficult. Prompt formulation influences performance, with structured prompts incorporating spatial and geometric descriptors yielding up to $82%$ improvement over short category-name prompts. The model operates within the memory and compute envelope of contemporary embedded GPUs, suggesting prompt-driven grounding can provide a practical mechanism for post-launch semantic extension of dominant spacecraft structures while highlighting limitations of zero-shot localization for fine-scale components under orbital domain shift.
### Title:
          Analyzing Visual Aircraft Representations with Sparse Autoencoders
 - **Authors:** Deepshik Sharma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision models can achieve strong performance on classification tasks, but the internal representations supporting their predictions are often difficult to interpret. This work investigates whether sparse autoencoders can decompose intermediate representations of a vision model into interpretable features. We train a ConvNeXt classifier on the FGVC-Aircraft dataset, extract spatial activations from its final feature stage, and train a sparse autoencoder on these activations. The learned sparse features are analyzed using top-activating image patches, activation strength, and class selectivity. Qualitative visual inspection reveals that several features correspond to recognizable aircraft structures and visual patterns. We evaluate a subset of selected features using input-space and feature-space ablations, measuring how blurring image patches and suppressing sparse features affect class logits, classification margins, and prediction confidence. The results suggest that sparse autoencoders can reveal partially interpretable, class-relevant visual features associated with aircraft recognition, while also exposing limitations such as polysemanticity and coarse spatial localization.
### Title:
          OneFocus: Enabling Real-World X-ray Security Screening with a Unified Vision-Language Model
 - **Authors:** Jiali Wen, Hongxia Gao, Litao Li, Yixin Chen, Kaijie Zhang, Qianyun Liu, Xiaoqin Wen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 X-ray contraband detection is critical for security in large-scale logistics and transportation, yet conventional detectors struggle to adapt to emerging contraband types and lack fundamental visual understanding. Vision-language models (VLMs) offer strong generalization but are hindered by the scarcity of high-quality X-ray image-caption data. To bridge this critical gap, we present MMXray, a meticulously curated benchmark of 52,124 image-caption pairs spanning 28 fine-grained classes of X-ray contraband. To enrich MMXray with realistic occlusion patterns, we further introduce CleanDET, a dedicated synthesis dataset containing clean foreground contraband images from 28 categories and background images with diverse density levels, together with AnyContraSyn, a controllable synthesis method designed to operate on CleanDET. We also develop OnePipe, an extensible pipeline for systematic data curation. Built on MMXray, we propose OneFocus, a unified VLM that supports four core tasks: visual question answering, contraband localization, classification, and image understanding. OneFocus achieves state-of-the-art performance in X-ray contraband understanding and demonstrates robust cross-domain generalization, establishing a strong vision-language baseline for security screening.
### Title:
          Imperfect Visual Verification for Code Edition : A Case Study on TikZ
 - **Authors:** Charly Reux (UR, INSA Rennes, DiverSe), Mathieu Acher (CNRS, IUF, IRISA, UR, DiverSe), Djamel Eddine Khelladi (DiverSe, UR, CNRS, IRISA), Clément Quinton (SPIRALS, CNRS), Olivier Barais (UR, IRISA, DiverSe)
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLMs have significantly advanced code generation, enabling the synthesis of functional programs. While recent systems achieve strong performance on many coding benchmarks, tasks involving programs such as TikZ that generate visual artifacts remain challenging, in particular on visual code customization. Unlike generation from scratch, customization requires localized, semantics-preserving edits: the model must locate relevant code, modify it according to the instruction, and preserve the remaining structure and rendering. Approaches based on post-hoc iterative refinement/correction where a verifier provides feedback to guide corrections, have shown promise. However, in the case of programs with a visual outcome such as in TikZ, where correctness is harder or likely impossible to formalize and evaluate automatically, deterministic verifiers do not exist. Hence, developers can only rely on imperfect verifiers. In this paper, we conduct an empirical study to answer:to what extent can iterative refinement remain effective when the verifier itself is unreliable?} We use TikZ as a focused case study that isolates the core difficulties of the problem (weak code structure, fine-grained visual semantics, and difficult feature localization) in a controlled and challenging setting. We define visual code customization as an iterative editing problem with an imperfect oracle, and introduce a framework for analyzing such iterative refinements. We conduct a large-scale study and evaluate multiple LLM-based and tool-augmented visual verifiers within iterative refinement pipelines, and perform extensive manual annotation of refinement trajectories to assess verifier behavior and feedback quality. Our findings show that even imperfect verifiers can determine with moderate accuracy whether visual instructions are applied to code, achieving F1-scores up to 0.815. Feedback improves iterative refinement, especially for weaker models, adding 11--20 perfect customizations for Qwen3-vl-30b-a3b-Instruct, while stronger models like Gemini-3 gain fewer improvements (+5) but benefit more from accurate verification that prevents premature acceptance. Feedback is effective only when it precisely identifies image issues, provides actionable guidance, addresses all relevant problems, and remains grounded in the original instruction.
### Title:
          RoboPIN: Grounded Embodied Reasoning via Pinned Chain-of-Thought
 - **Authors:** Yaoting Huang, Yifu Yuan, Linqi Han, Chengwen Li, Shuoheng Zhang, Xianze Yao, Hongyao Tang, Yan Zheng, Jianye Hao
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Embodied reasoning requires models to perceive task-relevant objects and spaces in physical environments and maintain consistent visual grounding throughout multi-step reasoning. However, current vision-language models rely on text-only or coordinate-augmented chain-of-thought, where entity references remain implicit and ambiguous. This may cause the reasoning process to decouple from visual evidence, entity references to drift across steps, and a causal disconnection between the reasoning trajectory and the final answer, with these problems further amplified in multi-view scenarios due to cross-view appearance changes. To address these issues, we propose Pinned Chain-of-Thought (\pincot{}), a structured reasoning paradigm that pins every reasoning step to visual evidence. \pincot{} introduces the concept of \reasoninganchor{}, which binds each task-relevant entity to a structured visual anchor with entity name, unique identity, view index, and spatial grounding, enabling consistent entity tracking across reasoning steps and views. We build a fully automated data generation pipeline to construct \dataset{}, a high-quality \pincot{}-formatted reasoning dataset. We then train \method{} through three-stage post-training that progressively injects embodied knowledge, structured reasoning ability, and process-supervised alignment, with rewards that directly constrain both anchor localization and identity consistency during reasoning. On 14 benchmarks covering embodied spatial reasoning, multi-view reasoning, and pointing, \method{} with only 4B parameters consistently outperforms 7B level open-source embodied models, achieving a 12\% average improvement over the strongest 7B baseline, Mimo-Embodied. Further analysis shows that \pincot{} improves grounding accuracy and cross-step identity consistency, validating the effectiveness of process supervision.
### Title:
          Theorem-Grounded Execution Ontologies for Interpretable Machine Reasoning
 - **Authors:** Raghu Anantharangachar
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models have achieved impressive performance on reasoning tasks spanning mathematics, science, programming, and commonsense inference. Despite these advances, their reasoning processes remain largely latent, making them difficult to interpret, verify, replay, debug, and transfer across domains. Existing approaches such as chain-of-thought, tree-of-thoughts, graph-of-thoughts, and tool-augmented reasoning expose intermediate reasoning artifacts but typically lack explicit execution semantics, formal state representations, and verifiable reasoning structures. We introduce Theorem-Grounded Execution Ontologies (TGEO), a framework that models reasoning as an executable state-transition process rather than a sequence of generated tokens. Given an input problem, TGEO identifies relevant theorem families, binds the problem to a domain ontology, discovers semantic objects, instantiates states and operators, constructs predicates and contracts, and synthesizes an executable reasoning graph. The resulting graph provides an interpretable, replayable, and auditable representation of reasoning in which every state transition, operator application, and validation step is explicitly represented. TGEO integrates five architectural components: (1) theorem-grounded reasoning priors, (2) executable ontologies, (3) operator-mediated state transitions, (4) predicate and contract-based execution validation, and (5) architectural auditing and failure localization. We evaluate TGEO on theorem-intensive reasoning tasks derived from mathematical benchmark domains and a curated Golden Execution Suite. Our findings demonstrate the value of executable reasoning representations for interpretable, verifiable, and reproducible AI reasoning systems.
### Title:
          Effective and Low-cost Lane-based Map Localization for Vehicle-Centric Route Generation
 - **Authors:** Hong-Shiang Lin, Jung-Hsin Chen, Yu-Luen Tzeng, Wei-Hao Chen, Yi-Chen Lee, Li-Jhe Chen, Peng-Yuan Chen
 - **Subjects:** Subjects:
Multimedia (cs.MM); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Driver-centric route representation plays a vital role in intuitive driving guidance systems. This paper presents OLRA, a low-cost, map-localization-based framework that derives driver-view-aligned routes by matching map-based navigation routes with camera-detected lane markings. This alignment process mutually enhances vehicle localization accuracy and visual route consistency. To bridge the evaluation gap across different paradigms, we introduce practical route evaluation metrics and benchmark OLRA against OpenPilot, a representative direct-generation approach. Experimental results on the nuScenes dataset demonstrate that OLRA outperforms OpenPilot in complex road segments and in route estimation at distance beyond 20 meters, achieving lower overall Euclidean error. This study is expected to promote future research in low-cost, maplocalization-based route generation methods.
### Title:
          When the Past Matters: FlashBack Memory for Precipitation Nowcasting
 - **Authors:** Yuhao Du, Boxiao Huang, Chengrong Wu, Jiankai Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate precipitation nowcasting is crucial for disaster mitigation and socio-economic planning, yet existing methods often struggle with false alarms, missed events, and long range dependency modeling at high spatiotemporal resolution. To address these challenges, we propose FlashBack Memory (FB), a module that dynamically retrieves key historical states and integrates them via an adaptive fusion gate, enhancing the spatiotemporal representation capability of recurrent-based models. We incorporate FB into PredRNN, PredRNNpp, MIM, MotionRNN, and PredRNN-V2, and evaluate on CIKM2017, Shanghai2020, and SEVIR datasets. Experimental results demonstrate that FB significantly improves MSE, MAE, SSIM, and CSI metrics, particularly for high-intensity rainfall and long-sequence predictions, while reducing false alarms and missed events and enhancing temporal consistency and spatial localization. The proposed method provides a general and efficient memory enhancement mechanism, improving the overall performance of recurrent-based precipitation nowcasting models.
### Title:
          MVOFormer: Flow-Semantic Transformer for Robust Monocular Visual Odometry
 - **Authors:** Jituo Li, Shunwang Sun, Jialu Zhang, Xinqi Liu, Jinyao Hu, Zhicheng Lu, Sajad Saeedi, Guodong Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular visual odometry (MVO) is foundational to autonomous navigation and robotic localization. However, existing learning-based MVO approaches often struggle with either a lack of interpretable, complementary features or overly complex multi-stage architectures. These limitations inherently restrict their robustness and cross-domain generalization. In this work, we propose MVOFormer, a novel transformer framework for robust monocular visual odometry. Our architecture features a Flow-Semantic Dual Branch Encoder that synergizes dense geometric motion cues with object-centric semantic priors, explicitly distinguishing static structures from dynamic distractors. These representations are then fused by an Iterative Multimodal Decoder, enabling coarse-to-fine pose refinement while dynamically suppressing attention on unreliable regions. Extensive evaluations demonstrate that, without any target-domain fine-tuning, MVOFormer achieves superior zero-shot generalization and robustness, significantly outperforming prior learning-based frame-to-frame methods across diverse benchmarks including TartanAir, KITTI, TUM-RGBD, and ETH3D-SLAM.
### Title:
          LOCUS: Local Visual Cue Search for Enhancing Fine-Grained Perception in Multimodal Large Language Models
 - **Authors:** Zhou Tao, Fang Zhang, Zewen Ding, Shida Wang, Xiaokun Sun, YongXiang Hua, Haoyu Cao, Linli Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Large Language Models (MLLMs) remain unreliable on fine-grained visual perception, even when high-resolution inputs preserve the necessary local details. We identify this limitation as visual context rot: decisive evidence may exist in the full image, yet fail to be reliably selected and used amid redundant visual context. We propose LOCUS (LOcal visual CUe Search), a training framework that teaches MLLMs to internalize local evidence search through a verifiable proxy task. During training, LOCUS provides a local crop as a visual cue and optimizes the model to recover its spatial support in the full image using an IoU-based reward. The visual cue is used only during training, leaving the standard image-question inference interface unchanged. Experiments across fine-grained perception, hallucination, general understanding, and reasoning benchmarks show that LOCUS improves localization-sensitive visual understanding while preserving broad capabilities. Attention analyses further indicate stronger focus on task-relevant evidence regions, suggesting that training-time visual cue search provides an effective route to internalized fine-grained evidence selection.
### Title:
          DifferAD-R1: A Difference-Guided IndustrialAnomaly Localization with Multimodal LargeLanguage Models
 - **Authors:** Dingrong Wang, Xian Tao, Zhen Qu, Hengliang Luo, Xinyi Gong, Fei Shen, Zhengtao Zhang, Guiguang Ding
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Industrial anomaly localization aims to accurately identify and localize abnormal regions in industrial products, addressing the critical challenge of detecting unseen defect categories in real-world scenarios. Traditional closed-set methods often suffer from poor cross-scenario generalization, while existingMultimodal Large Language Model (MLLM)-based approachesface two core limitations: they either adopt QA-style paradigmsmisaligned with the practical demands of localization, or relyon standard optimization techniques such as Group RelativePolicy Optimization (GRPO), which fails to deliver effectivelearning signals for subtle defects. To tackle these issues, thispaper proposes DifferAD-R1, an MLLM-augmented reinforcement learning framework tailored for industrial anomaly localization. We design a Difference-Guided dual-image paradigm,which reformulates the localization task as a one-shot difference grounding problem to effectively explore cross-scenarioanomalies. A Dual-Consistency Localization Reward is developedfor hard-to-detect anomalies, enhancing optimization stabilityand robustness. Additionally, we integrate a difficulty-awarestrategy with adaptive reweighting and group-wise resamplingto prioritize learning on challenging instances. To facilitateevaluations in real-world industrial settings, we construct theAD-DualDiff dataset, comprising 13K paired images across 20categories. Experimental results demonstrate that DifferADR1 significantly outperforms existing baselines and achievescompetitive performance compared to large-scale models likeQwen3-VL (235B parameters). Our code is publicly availableat: this https URL.
### Title:
          Nodal Representations for Kernel-Based Multilevel Interpolation
 - **Authors:** Lorenz Gollwitzer, Rüdiger Kempf, Holger Wendland
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study the kernel-based multilevel method for approximating or learning a multivariate function from scattered data, motivated in part by recent applications in sparse grid methods. For nested families of point sets, we derive a nodal representation of the multilevel interpolant that depends explicitly on the values of the target function. This representation allows us to characterize the range of the associated interpolation operator and to construct a cardinal basis for this space. We prove that the resulting basis functions exhibit exponential decay, analogous to the localization properties known for certain kernel-based Lagrange functions. We further analyze the computational cost of the resulting formulation. For non-nested families of point sets, we derive a generalized nodal representation.
### Title:
          LLM-Based Visual Explanation Evaluation Framework for Assessing the Explainability of Facial Skin Disease Classification Models
 - **Authors:** Gyuyeon Na
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study proposes a domain-specific LLM-based Visual Explanation Evaluation Framework for assessing Grad-CAM explanations in facial skin disease diagnosis models. While previous studies have primarily focused on improving classification performance through data augmentation techniques, relatively few studies have systematically examined whether model explanations are grounded in clinically relevant lesion regions. In this study, geometric augmentation, color-based augmentation, and mixed augmentation strategies were applied to facial skin disease classification models based on EfficientNet-B0, MobileNetV3, and ResNet18. Grad-CAM was employed to generate visual explanations representing the models' decision-making processes. Furthermore, an LLM-as-a-Judge evaluation framework was designed using GPT-5.5, Gemini 3.5 Flash, and Claude Sonnet 4.6 to assess Grad-CAM explanations from the perspectives of lesion localization and explanation trustworthiness. To improve evaluation consistency and clinical grounding, a progressive prompt engineering strategy was introduced, incorporating evaluation rubrics, clinical knowledge, penalty rules, and structured output formats.
### Title:
          SGM-SLAM: Scene Graph Matching for Data-Efficient Distributed SLAM
 - **Authors:** Yewei Huang, Tixiao Shan, Abhinav Rajvanshi, Niluthpol Chowdhury Mithun, Yaxuan Li, Brendan Englot, Han-Pang Chiu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a data-efficient distributed Simultaneous Localization and Mapping (SLAM) framework designed for a team of robots equipped with LiDAR, cameras, and inertial sensors. Our framework uses scene graph matching to identify inter-robot measurement constraints. Unlike prior approaches that rely on feature-level matching, our framework is the first to perform scene graph matching using only object labels and centroids. Our approach constructs a scene graph by using fused RGB-LiDAR point clouds to generate both a semantically segmented point cloud layer, and a layer of discrete bounded objects, to accompany estimated robot trajectories. Scene graph matching is performed collaboratively through exchanging and matching object data with neighboring robots. To maximize communication efficiency, we utilize a multi-step data exchange and optimization process. We demonstrate the effectiveness and efficiency of our approach using both simulation and real-world datasets collected by legged robots in indoor and outdoor environments.
### Title:
          Semantic Flip: Synthetic OOD Generation for Robust Refusal in Embodied Question Answering and Spatial Localization
 - **Authors:** Dongbin Na, Chanwoo Kim, Giyun Choi, Dooyoung Hong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Detecting unanswerable user queries remains essential for the reliable deployment of real-world embodied agents. However, modern vision-language models (VLMs) often generate overly confident answers even when the available visual memory cannot support the query. Such overconfidence poses various task-dependent risks. The agent may provide misleading information to the user in Embodied Question Answering and select an arbitrary coordinate and physically guide the user there in spatial reasoning for navigation. Despite these high stakes, only a few prior studies directly address when and how an embodied VLM should respond with "I do not know." This work proposes Semantic Flip, a simple yet effective framework that synthesizes auxiliary out-of-distribution (OOD) samples for embodied refusal without requiring external OOD annotations. The key idea is to independently transform the query and video memory to construct auxiliary OOD pairs that lack sufficient visual grounding. These synthesized pairs enable training a lightweight rejection module on top of a frozen pretrained VLM. The module attaches to any existing VLM-based pipeline without retraining the underlying model. Across two complementary benchmarks, Semantic Flip consistently outperforms strong prompting baselines. This work also introduces SpaceReject, a new refusal benchmark for spatial localization with deliberately unanswerable queries over long video memory, where Semantic Flip achieves an $F_1$ score of 0.9559. The source codes and datasets are publicly available at this https URL.
### Title:
          Binary Tracking for Spatial QA and Navigation with Open Vision-Language Models
 - **Authors:** Dongbin Na, Chanwoo Kim, Soonbin Rho, Giyun Choi, Gangbok Lee, Dooyoung Hong
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work addresses spatial question answering for service robots traversing long egocentric routes. Given a query such as "where can I find a dry cleaner on the way back home?", the system returns a metric coordinate that downstream navigation components can act on. Prior Spatial Question Answering approaches leverage retrieval-augmented agents built on closed-source models such as GPT-4o for path exploration. However, robots operating in the real world often cannot reliably depend on online closed-source models due to network instability, communication latency, and deployment cost. It creates a need for open-source based Spatial Question Answering approaches that can run onboard the robot, yet prior research in this direction remains limited. This work proposes BinTrack, a simple yet effective, fully open-source spatial-localization agent that leverages the temporal ordering of a robot's trajectory. BinTrack performs a binary search over the trajectory segments between two anchor landmarks identified from a query. It improves overall accuracy by up to 22.8% over other open-source implementations and even matches the reported closed-source model result on the global category of the SpaceLocQA benchmark, the most challenging setting that has so far required strong reasoning agents such as GPT-4o. Furthermore, its optimized inference strategy consistently yields more than a 1.5x inference speedup over previous approaches. Finally, this work releases GangnamLoop, a novel and practical multi-trip outdoor benchmark collected by deploying a real quadruped robot on public streets with the anonymization policy. It revisits the same locations under different outdoor conditions and pairs the robot's low viewpoint with the human owner's. The source codes and datasets are publicly available at this https URL
## Keyword: transformer
### Title:
          AI for Maritime Security: Comparative Evaluation of CNN and Vision Transformer Architectures for Maritime Object Detection
 - **Authors:** Ismet Gocer, Zakirul Bhuiayn, Shakeel Ahmad, Raza Hasan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study aims to enhance maritime security by using advanced Artificial Intelligence (AI) and Computer Vision (CV) techniques. For this purpose, it was designed and assessed intelligent object detection systems that can detect the presence of ships on the sea surface under different real-time environments. To achieve this goal, a maritime image dataset with 6,468 images was used, covering different weather conditions like cloudy, foggy, rainy, and sunny environments. Six deep learning architectures were evaluated, including a base Convolutional Neural Network (CNN) model, four transfer learning models (Xception, VGG16, MobileNetV2, and EfficientNetV2L), and a Vision Transformer (ViT) model. The models were compared using multiple performance indicators, including accuracy, Type I and Type II errors, model size, and video processing time. The results show that model performance varies depending on computational constraints and deployment conditions. While lightweight architectures are suitable for resource-limited devices, the ViT achieved the best overall performance, reaching 100% accuracy with the lowest error rates and the fastest video processing time. The findings highlight the potential of AI-driven computer vision systems for maritime surveillance, border protection, and autonomous navigation.
### Title:
          Interpolation between Convolution and Attention via K-Nearest Neighbors
 - **Authors:** Mingi Kang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The shift from Convolutional Neural Networks to Transformers has reshaped computer vision, yet these two architectural families are typically viewed as fundamentally distinct. Convolutional Neural Networks are defined by spatially local convolution operations, while Transformers rely on global self-attention. We argue that convolution and self-attention, despite their apparent differences, can be unified within a single k-nearest neighbor aggregation framework. The critical insight is that both operations are special cases of neighbor selection and weighted aggregation. Convolution selects neighbors by spatial proximity while self-attention selects by feature similarity, revealing that they lie on a continuous spectrum rather than representing categorically different computations. We introduce Convolutional Nearest Neighbors (ConvNN), a unified framework that formalizes this connection. ConvNN exactly recovers standard and depthwise convolution by restricting neighbor selection to normalized spatial coordinates, and exactly recovers self-attention and its sparse variants, including KVT-attention, by replacing spatial proximity with scaled dot-product similarity. Beyond these special cases, ConvNN serves as a drop-in replacement for both convolution and attention layers, enabling systematic exploration of the intermediate spectrum between local and global aggregation through configurable similarity functions, neighbor selection strategies, positional encodings, and aggregation kernels.
### Title:
          Hierarchical GRU with Input-Conditioned Slot Queries for Ball Action Anticipation
 - **Authors:** Parthsarthi Rawat
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a hierarchical model for ball action anticipation in football broadcast video. Given a 30-second observation window, the system predicts actions occurring in the subsequent 5-second window across 10 classes. A shared local Transformer encodes clip-level features within each 5-second sub-window; a GRU then aggregates temporal context across all sub-windows; finally, a Transformer decoder with K input-conditioned event slots decodes the anticipation target via three decoupled heads (objectness, class, temporal offset). We introduce frequency-reweighted Hungarian matching that systematically favours rare action classes, and Gaussian soft targets for temporal bin supervision. On the SoccerNet Ball Action Anticipation benchmark, our method achieves 17.91% mAP on the test server.
### Title:
          UtVAA: Ultra-tiny Vision Transformer with Affix Attention for Mobile Image Classification
 - **Authors:** Romiyal George, Sathiyamohan Nishankar, Selvarajah Thuseethan, Roshan G. Ragel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) have demonstrated strong representation capability in image classification. However, their quadratic self-attention complexity and large parameter counts limit deployment on resource-constrained mobile and edge devices. This paper introduces UtVAA, an ultra-tiny Vision Transformer architecture designed for efficient visual recognition under strict computational budgets. It incorporates a novel Affix Attention block that combines depthwise-pointwise local feature extraction, linear self-attention, coordinate attention for spatial dependency modelling, and a lightweight ternary fusion strategy to integrate local and global representations. In addition, Dilated Bottleneck blocks expand the receptive field using dilated depthwise separable convolutions while maintaining low FLOPs and stable optimisation through residual connections. UtVAA is implemented in scalable Tiny, Medium, and Large variants, with the smallest model containing 204.67K parameters and 53.95M FLOPs. Experimental results on CIFAR-10, CIFAR-100, PlantVillage-Tomato and SLIF-Tomato datasets show that UtVAA achieves competitive accuracy within a sub-million-parameter regime. Overall, the results demonstrate that transformer-based vision models can be redesigned into ultra-tiny architectures without significant loss in discriminative performance, making UtVAA suitable for mobile and edge deployment. Code is available at this https URL
### Title:
          Style-CCL: Content-Preserving Style Transfer via Curriculum Continual Learning
 - **Authors:** Shiwen Zhang, Haoyuan Wang, Xianghao Zang, Haibin Huang, Chi Zhang, Xuelong Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Content-Preserving Style transfer, given content and style references, remains challenging for Diffusion Transformers (DiTs) due to entangled content and style features. With a reverse triplet synthesis pipeline to build a million-scale training set and a dual-branch Style-Content DiT (SC-DiT) that decouples style and content via separate ROPE embeddings and causal masking, we observe that such a one-stage training paradigm on mixed style categories causes semantic styles to dominate, hindering texture style learning, and harming content preservation. To address these issues, we propose Style-CCL, a Multi-Stage Curriculum Continual Learning framework that trains SC-DiT from semantic (easy) to texture (hard) styles, and from clean to synthetic data, with Random Memory Rehearsal across stages to avoid catastrophic forgetting. Extensive experiments demonstrate that our Style-CCL achieves state-of-the-art performance in three core metrics: style similarity, content consistency, and aesthetic quality.
### Title:
          Beyond Self-Attention: Sub-Quadratic Vision Transformers for Fast Image Captioning
 - **Authors:** Chiradeep Ghosh, Dakshina Ranjan Kisku
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image captioning is a challenging and significant task that aims to generate coherent and semantically meaningful textual descriptions for given images. To accomplish this task, it requires a deep understanding of visual content along with the ability to express that understanding in natural language. Despite remarkable progress with transformer-based architectures, existing approaches often suffer from limitations, such as a lack of rich local feature representations and the high computational cost of quadratic self-attention. The proposed model focuses on improving computational efficiency by restructuring the vision transformer architecture. In designing this approach, the standard self-attention mechanism in Vision Transformers is replaced with a probabilistic transformer approach based on a Gaussian Mixture Model (GMM), a soft-clustering technique. Instead of computing pairwise attention among all image patches, the model groups similar patches into a fixed number of clusters using an Expectation-Maximization (EM) algorithm. This clustering-based mechanism reduces the computational complexity from quadratic O(n^2) to linear O(nK), where K << n. The autoregressive GPT-based decoder is used for caption generation. The model is evaluated on the Flickr 30K dataset, demonstrating competitive and significant improvement over existing works.
### Title:
          Spatial Priors via Space Filling Curves for Small and Limited Data Vision Transformers
 - **Authors:** Leyla Naz Candogan, Arshia Afzal, Pol Puigdemont, Volkan Cevher
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Though Vision Transformers (ViTs) have become the dominant backbone in many computer vision tasks, due to permutation equivariance, their attention mechanism lacks explicit spatial inductive biases. This become particularly important in two settings: when model capacity is small or training data is limited. Inspired by the attention masking strategies in Linear Transformers and the scanning patterns of Vision SSMs, we introduce VIOLIN, a lightweight masked attention mechanism that encodes spatial structure within attention via Space Filling Curves (SFCs) with less than 0.0015% extra parameters and negligible computational overhead. VIOLIN scans the image using multiple SFCs to construct curve-specific decay masks, which are then combined and multiplied with the attention matrix. Across a wide range of evaluations, VIOLIN consistently improves performance. In limited data regimes such as fine-tuning on VTAB-1K, it boosts accuracy across all task groups and by up to 8.7% on the tasks where spatial information is essential. It can be combined with parameter-efficient fine-tuning methods such as LoRA to further increase the performance. Beyond fine-tuning, VIOLIN improves various small scale ViT architectures (e.g., DeiT, DINO) during pretraining on ImageNet-1K. Additionally, on pixel-level CIFAR-100 training, a task that is highly dependent on location information, VIOLIN increases accuracy by up to 7.2%. Overall, VIOLIN provides a computationally efficient yet effective way to inject spatial inductive bias into ViTs, especially benefiting small models and limited data settings.
### Title:
          Synthetic-to-Real Pipeline for Safe Landing Zone Detection
 - **Authors:** Shrikant Banerjee, Reza Faieghi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As Uncrewed Aerial Vehicles (UAVs) transition toward higher levels of autonomy, the ability to perform unassisted recovery in non-cooperative, unstructured environments becomes critical. Achieving safe autonomous landing requires high-fidelity semantic resolution to distinguish navigable terrain from hazardous obstacles, yet development is often hindered by the scarcity of annotated aerial datasets. This work proposes a comprehensive perception and data generation pipeline designed to bridge the sim-to-real gap for autonomous landing tasks. We introduce a procedural synthetic data engine that generates photorealistic urban environments with automated semantic annotations through domain randomization. A Transformer-based OneFormer architecture is fine-tuned exclusively on this synthetic data, leveraging multi-head self-attention mechanisms for global context resolution. To ensure operational safety, a deterministic landing module utilizes a Euclidean Distance Transform (EDT) and dynamic inference logic to identify the largest inscribed safe landing zones while maintaining strict clearance buffers around obstacles. Quantitative benchmarking against the UAVid dataset demonstrates robust semantic segmentation performance, while qualitative validation on real-world UAV footage confirms the system's ability to identify collision-free landing sites in unseen environments. Our results highlight the potential of high-fidelity procedural simulation to eliminate the need for manual annotation while providing robust, edge-deployable situational awareness for autonomous UAV recovery.
### Title:
          Unifying Acoustic Features and Text with Multimodal LLMs for Neurodegenerative Screening
 - **Authors:** Qingfeng Zhang, Yuanxiong Guo, Yanmin Gong
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Voice-based screening offers a scalable and non-invasive way to assess neurodegenerative diseases such as Alzheimer's disease (AD) and Parkinson's disease (PD), but their staging remains challenging due to the difficulty of integrating heterogeneous data. This paper presents NeurMLLM, an efficient multimodal generative framework for neurodegenerative disease staging. NeurMLLM first encodes the spectrograms and Mel-frequency cepstral coefficients of audio data with vision transformers and projects their representations into the embedding space of a large language model (LLM), where they are concatenated with transcript and demographic instruction tokens as a single unified sequence. The LLM is then instruction-tuned via Low-Rank Adaptation using task prompts to autoregressively predict a constrained label token, enabling a generative classification. By evaluating on the Bridge2AI-Voice dataset for fine-grained staging of AD and PD, we observe that NeurMLLM achieves strong performance, consistently outperforming classical machine learning methods and existing LLM-based approaches. The results show the high potential of multimodal LLMs in neurodegenerative disease staging, improving staging accuracy and supporting accessible deployment.
### Title:
          Simplifying the Modeling of Arbitrary Conditionals in Natural Language
 - **Authors:** Yinhan Lu, Eric Elmoznino, Léo Gagnon, Sarthak Mittal, Tejas Kasetty, Guillaume Lajoie
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Causal Transformers model sequences through an autoregressive factorization of the joint distribution, which enables efficient left-to-right decoding and conditional likelihood computation. However, they cannot tractably sample from or evaluate arbitrary conditionals -- e.g., a block of text conditioned on past and future tokens. Recent work aims to solve this problem through novel architectures, but they often lead to sub-optimal modeling of such conditionals and degraded generations. We propose Arbitrary Conditionals GPT (AC-GPT) which introduces a simple modification to standard causal Transformers to enable evaluating and sampling from arbitrary conditionals -- including past, future, and mixed contexts -- within a single forward pass. Unlike prior approaches, our method preserves the standard left-to-right ordering and next-token prediction objective essential for both strong performance and efficient training on natural language. Crucially, this compatibility allows existing LLMs to be fine-tuned for arbitrary conditioning. Our empirical results indicate that our method outperforms baselines on modeling arbitrary conditionals, without degrading standard left-to-right performance.
### Title:
          Leveraging Physiological Signals to Predict Exam Outcomes with Machine Learning
 - **Authors:** Lala Yamazaki, Ramchandra Rimal
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study investigates the application of machine learning models to predict exam outcomes using physiological data collected during examination sessions. Physiological stress indicators, including electrodermal activity, heart rate, and skin temperature, were analyzed to uncover their association with academic performance. A variety of machine learning approaches were employed, ranging from standard models like logistic regression, random forest, and support vector machines to more advanced architectures, including transformers, long short-term memory (LSTM), and gated recurrent unit (GRU) models. This diversity aimed to capture the complex interactions within the data effectively. A key focus was assessing the adaptability of transformers in processing numerical data and evaluating their performance in this novel context. Standard performance metrics, such as accuracy, precision, recall, and F1-score, were used to compare model efficacy. The experimental results demonstrate that while deep learning models generally excel at capturing complex relationships in physiological data, simpler models like random forests can sometimes achieve superior performance while offering computational efficiency and interpretability. Furthermore, transformers demonstrated notable versatility, showcasing performances comparable to those of the LSTM and GRU models. This research underscores the importance of experimenting with a broad class of models that align with the objectives of the problem at hand, balancing precision, efficiency, and interpretability. By elucidating the relationships between physiological signals and academic performance, this study contributes to understanding stressors affecting students' mental health. It further promotes leveraging physiological data to enhance student well-being and academic outcomes.
### Title:
          Deep Temporal Modeling and Ensemble Fusion for Multimodal Emotion Recognition from Physiological Signals
 - **Authors:** Desta Haileselassie Hagos, Saurav Keshari Aryal, Patrick Ymele-Leki, Anietie Andy, Legand L. Burge
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physiological stress and emotion recognition are important for health monitoring and affective computing. In this work, we present a comprehensive evaluation of deep learning models such as Long Short-Term Memory (LSTM), Temporal Convolutional Networks (TCN), and Transformer on the WESAD dataset for multimodal affect recognition using wrist and chest sensor signals. We perform ablation studies to assess the individual contributions of each modality by training models on wrist-only and chest-only inputs. In addition, we implement a late-fusion ensemble strategy that combines predictions from all three architectures trained on multimodal input. We also employ early fusion at the sensor level by concatenating wrist and chest signals before feeding them into each model. Our results show that Transformer models consistently achieve the highest accuracy in multimodal settings, while TCN models perform best in the wrist-only configuration. The ensemble method yields the highest overall accuracy (98.91 +/- 0.13%) and macro-F1 score (98.56 +/- 0.17%). These findings demonstrate the effectiveness of sensor fusion and ensemble-based fusion in developing robust systems for physiological emotion recognition.
### Title:
          Transformers Learn the Mestre-Nagao Heuristic
 - **Authors:** Pranav Venkata Konda
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Number Theory (math.NT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We train a two-layer transformer encoder to classify rational elliptic curves $E/\mathbb{Q}$ of conductor $\leq 10000$ as either rank 0 or rank 1 from the first 128 normalized Frobenius traces. We achieve >99% accuracy on both classes, and accuracy is essentially unchanged on test curves with no isogeny or quadratic-twist relative in the training set. We then apply techniques from mechanistic interpretability such as attention analysis, linear probing, activation patching, logit attribution, and neuron-level circuit analysis to reverse-engineer the algorithm the (centroid in function space) model learned. We find that a sparse circuit of 20 out of 512 layer-1 MLP neurons is sufficient for rank prediction under a linear probe with an AUROC of 0.992 at plateau, implementing a push-pull detector architecture of rank-0 and rank-1 detectors with a one-sided readout. However, we notice that the model has sub-optimal readout problems indicating a mismatch in rank-order between the readout pathway and the discriminative circuit. Critically, the learned input weights of the top discriminating neuron match the Mestre-Nagao sum heuristic weights $\log(p)/(p\cdot \log{B})$ with a Spearman coefficient $r = 0.997$ and Pearson coefficient $r = 0.952$: the model has learnt a result from analytic number theory from the Frobenius trace data alone. We additionally find that all 50 independently trained models concentrate CLS attention on prime positions at 2-50$\times$ the rate of composite positions. The CLS embedding encodes $\log{L(E,1)}$ with $R^2 = 0.962\pm 0.011$ across the 50 models (after controlling for the conductor). Activation patching analysis reveals that attention weights are dissociated from causal information flow. Additionally, the 50 solutions from training are near-identical in function space (with pairwise agreement $>$98.8%) despite large weight space barriers.
### Title:
          Equity with Efficiency: An Empirical Study of Tokenizers for Multilingual Large Language Models
 - **Authors:** Kieron Seven Jun Wei Lee, Muhammad Reza Qorib, Andrew Ivan Soegeng, Hwee Tou Ng
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multilingual large language models (LLMs) depend on subword tokenization to bridge discrete text and continuous neural representation. State-of-the-art multilingual LLMs often use Byte-level Byte-Pair Encoding (BPE) tokenizers that structurally favor high-resource languages and Latin scripts. For speakers of underrepresented languages, particularly those across Southeast Asia, this bias inflates inference costs and widens cross-lingual capability gaps. We present the first systematic comparison of equitable tokenizers on a unified benchmark spanning 11 Southeast Asian languages. Beyond tokenizer-level analysis of compression efficiency and cross-lingual equity, we assess downstream task performance through controlled 1.5B-parameter language model training using the same training data. Our results show that Parity-aware BPE lies on the Pareto frontier of the efficiency-equity trade-off, achieving strong compression parity at competitive cost. Morphology-Driven Byte Encoding delivers the best semantic reasoning performance through morphologically richer representations, albeit at a higher computational expense. Byte Latent Transformer underperforms on downstream tasks, possibly because its architectural assumptions misalign with the constraints of limited low-resource training data. Together, our findings demonstrate that cross-lingual fairness and tokenization efficiency are not fundamentally at odds, and offer practical guidance for designing equitable multilingual models.
### Title:
          VGPT-RSI for RH-Adjacent Formal Progress: Boundary Certificates, Verified Finite Lagarias Inequalities, and Explicit Failure Localization
 - **Authors:** Zhixin Hu, Tao Xu, Xiaodian Sun, Li Jin, Momiao Xiong
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Riemann Hypothesis remains one of the central unsolved problems in mathematics. Rather than claiming proof, we investigate whether a verifiable AI-assisted reasoning system can produce reliable, formally checked partial progress while explicitly identifying the remaining mathematical obstructions. We apply the Verifiable Growing Physical Transformer with Recursive Self-Improvement (VGPT-RSI) to two RH-adjacent certification tasks. First, we construct and verify a finite RH-boundary certificate for inequality on a parameterized safe lower curve over a region. The numerical boundary curve is converted into a certificate-backed lower curve, audited using outward-rounded interval arithmetic and Arb/FLINT ball arithmetic, and then checked in Rocq/CoqInterval for the parameterized theorem. Second, we initiate a formal Lagarias-route certificate. Lagarias criterion states that RH is equivalent to the global inequality. We formalize the finite quantity and produce a Coq-checked finite certificate. The final system identifies the exact unresolved mathematical bottlenecks: formalizing the Lagarias equivalence, proving the global tail theorem beyond any finite cutoff, and potentially reducing counterexamples to colossally abundant or related extremal integers. These results demonstrate that VGPT-RSI can produce certified RH-adjacent formal progress, organize proof dependencies, and avoid overclaiming when the remaining obstruction is genuinely mathematical.
### Title:
          Multi-view feature High-order Fusion for Space Weak Object Detection and Segmentation
 - **Authors:** Weilong Guo, Yuhan Sun, Shengyang Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Weak objects are common in images and videos of space applications. However, it is hard to learn proper representations from their limited appearance information. Inspired by multi-view learning, we develop simple multi-view attentions, treating their outputs as multi-view features. We also propose a multi-view feature high-order fusion method (MHF) to aggregate more accurate and richer features of weak objects. Our MHF extends the commonly used low-order feature fusion method to higher orders. It enhances the model's capacity to capture relevant and complementary information about weak objects. This is achieved by introducing high-order multi-view features perception and a recursive task-contribution gated selection of multi-view features. The new operation is highly flexible and customizable. It is compatible with various variants of multi-view feature representations. We conduct extensive experiments on two newly constructed space science datasets and an open, large-scale satellite video dataset. Our MHF serves as a plug-and-play module and significantly improves various vision transformers and convolution-based detection and segmentation models. We achieve all state-of-the-art accuracies on both tasks across three datasets. Our MHF can be a new basic module for visual modeling that effectively represents weak objects in terms of multi-view learning. The code will be available at this https URL.
### Title:
          LLMs have Visualization Literacy: Now What? Experiments Exploring LLM Visualization Evaluation Capabilities
 - **Authors:** Christian Seto, Jacqueline Nguyen, Jiayi Hong, Ross Maciejewski
 - **Subjects:** Subjects:
Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As Large Language Models (LLMs) become more popular within the visualization community, researchers increasingly leverage them for diverse visualization tasks such as design guideline suggestions and visualization evaluation. However, in order for LLMs to act as trustworthy and fair evaluators, we argue that LLMs would need to possess visualization literacy, be capable of following user instructions and uphold graphical integrity. We test the latest versions of the most prominent LLMs, specifically Anthropic's Claude (Opus 4.5), OpenAI's Generative Pretrained Transformers (GPT 5.2 Pro), and Google's Gemini (Gemini 3 Flash) on these features and find that while these models now possess visualization literacy, they still struggle with other features necessary for instruction following and graphical integrity. Using a modified Visualization Literacy Assessment Test (VLAT), our findings show that these recent LLMs have achieved greater than human-levels of visualization literacy in contrast to prior research. In order to test the models' abilities to follow instructions, we used few-shot and chain-of-thought prompting as proxies for instruction following tasks on evaluating visualization literacy and find that these specialized prompting techniques are becoming obsolete with respect to improving visualization literacy. Additionally, we experiment with the inherent ability of LLMs to evaluate misleading visualizations to test the models' abilities for upholding graphical integrity and find that without specialized or leading prompting techniques, the models struggle with being able to accurately identify whether a visualization is misleading or not. Our results further break down the performance of each model on these tasks, but the culmination of our findings force us to reconsider the current effectiveness of LLMs as visualization evaluators.
### Title:
          HiRo: A Compact Four-Directional Hierarchical Reservoir Token-Mixer for Efficient Image Classification
 - **Authors:** Md Farhadul Islam, Ishan Thakkar, J. Todd Hastings
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent image classification models must balance local feature modeling, cross-window interaction, and parameter efficiency. Many high-performing architectures rely on fully trainable token-mixers, which improve representation learning but increase parameter count, optimization complexity and computational cost. We propose a parameter-efficient image classification model called HiRo that integrates shifted-window partitioning with multi-directional hierarchical reservoir computing. Images are divided into non-overlapping patches (treated as tokens), linearly projected, normalized, and enriched with 2D sinusoidal positional encodings, then processed within local windows. Inside each window, tokens are scanned in four directions and passed through a two-stage slice-and-mix reservoir module. In the first stage, directional sequences are split into contiguous slices, each processed by its own fixed reservoir with a trainable closed-loop readout. The resulting slice outputs are summarized using the start, end, and mean representations, and then mixed by a second-stage fixed reservoir for each direction. The mixed slice representations are expanded back to the token level and fused with the first-stage outputs, after which the four directional outputs are realigned and averaged. Consecutive blocks alternate between regular and shifted windows to enable cross-window interaction, followed by layer normalization, a residual feed-forward network, and global pooling for classification. This design combines regular and shifted window partitioning with hierarchical multi-directional reservoirs to make an efficient local-to-cross-window token-mixing framework for image classification. Despite using under 1M trainable parameters and significantly lower memory and time than transformer-style baselines, HiRo also achieves 99.46%, 85.57%, and 59.10% accuracy on MNIST, CIFAR-10, and CIFAR-100, respectively.
### Title:
          PolyKV: Heterogeneous Retention and Allocation for KV Cache Compression
 - **Authors:** Chao Fei, Panos Kalnis
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 KV cache compression is essential for reducing the memory cost of long-context large language model inference. Existing approaches, however, typically apply a single compression policy and a uniform cache budget across all transformer layers. This uniform design ignores the fact that different layers can play different roles during prefill and decoding, and may therefore require different eviction strategies and cache capacities. We present PolyKV, a layer-wise KV cache optimization framework that considers design space with method selection and budget allocation. PolyKV routes each layer to a suitable KV compression policy based on layer-level signals, while assigning non-uniform budgets under a fixed total budget. This formulation enables heterogeneous compositions of existing KV cache methods. Experiments on LLaMA-3.1-8B and Qwen3-8B show that, under the same 512-token average KV budget, PolyKV recovers 54.5% and 25.7% of the LongBench performance gap between the strongest single-policy baseline and FullKV, respectively. Across 128-1024 budget sweep, PolyKV consistently improves over the strongest baseline by 1.7%-6.4%, corresponding to 40.0%-54.5% recovery of the FullKV gap.
### Title:
          RefGC-SR$^2$: Reference-guided Generated Content Super-Resolution and Refinement
 - **Authors:** Jeahun Sung, Dahyeon Kye, Soo Ye Kim, Jihyong Oh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reference-guided generation (e.g., object compositing, customization) has progressed rapidly, yet current pipelines share a fundamental limitation: the object-centric high-resolution reference image (HRRI) provided by users is downsampled to a fixed low-resolution (LR) before being fed into the model, so the fine-grained details are discarded before the output is even produced. In addition, the generation step then introduces its own artifacts (e.g., identity distortion) on top of this loss. Existing reference-guided generated content refinement (RefGCR) methods can correct some of these artifacts but still operate in the LR domain; reference-guided super-resolution (RefSR) methods recover resolution but assume natural-image degradations and ignore the artifact distribution of generative pipelines. To address both gaps in a single formulation, we introduce a new task: reference-guided generated content super-resolution-refinement (RefGC-SR$^2$), where the original HRRI is reused at the post-processing stage to recover lost details, refine generative artifacts, and upscale the output simultaneously. We construct the first real-world triplet data generation pipeline for this RefGC-SR$^2$ task, training a diptych-conditioned generator to synthesize paired low-quality anchors that public pretrained models cannot provide. We further present a frequency-aware diffusion transformer model for RefGC-SR$^2$ that selectively injects fine details from the HRRI while removing generative artifacts. Extensive experiments demonstrate that our RefGC-SR$^2$ model successfully (i) refines the object identity faithfully with respect to the reference, and (ii) recovers high-resolution details, so that the final result is significantly higher quality and practically more usable compared to existing RefGCR and RefSR baselines.
### Title:
          Towards a Unified Generative Model for Scarce Time Series with Domain Experts
 - **Authors:** Zihao Yao, Qi Zheng, Jiankai Zuo, Yaying Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synthesizing realistic time series with generative models has wide-ranging applications in real-world scenarios. Despite recent progress, most existing methods are trained under the assumption of abundant training data, which substantially limits their effectiveness in data-scarce settings. In this paper, we propose TimeMoDE, a novel framework that integrates Diffusion Transformers with Mixture-of-Experts to exploit both domain adaptability and diffusion-stage awareness for time series generation under data scarcity. It is pre-trained on a large-scale collection of multi-domain datasets to extract domain-agnostic temporal representations and domain-specific information benefiting generalization during fine-tuning. We propose Domain Prompts to condition expert assignment for indistinguishable noised tokens, mitigating the limitations of capturing inter-dataset relationships. Moreover, we incorporate diffusion timestep signals to equip the experts with awareness of time series degradation variations, facilitating adaptive calibrate to stage-dependent denoising requirements. Extensive experiments demonstrate that TimeMoDE outperforms existing methods under diverse low-data settings. It establishes an innovative paradigm for advanced time series few-shot generation.
### Title:
          Controlled Dynamics Attractor Transformer
 - **Authors:** Cheng Zhang, Minnan Luo, Zesheng Yang, Ming Li, Yong-Jin Liu, Qinghua Zheng
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer architectures have dramatically advanced representation learning and inference in deep models through self-attention mechanisms. In parallel,associative memory (AM) frameworks map representations onto energy landscapes, offering interpretable retrieval mechanisms. However, their continuous-time inference dynamics lack the biological plausibility of classical Continuous Attractor Neural Networks (CANNs). To bridge this gap, we propose Controlled Dynamics Attractor Transformer (CDAT), which couples a mixture von Mises-Fisher (Mo-vMF) attention energy with a Hopfield refinement energy, while augmenting energy descent with a CANN-inspired excitation-inhibition modulation. CDAT instantiates a topology-constrained dynamical system whose couplings encode relational structure among tokens, thereby linking attractor-style dynamics to modern energy-based attention. We further provide a constructive dissipation analysis to formally establish their controlled inference dynamics. Benefiting from these robust and structured dynamics, CDAT achieves state-of-the-art performance across multiple benchmarks in graph anomaly detection and graph classification.
### Title:
          Focus, Align, and Sustain: Counteracting Gradient Dilution in Incremental Object Detection
 - **Authors:** Aoting Zhang, Dongbao Yang, Chang Liu, Xiaopeng Hong, Yu Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adapting Detection Transformers to Incremental Object Detection (IOD) poses a systemic challenge, as set-based optimization is inherently destabilized by sequential learning. In this work, we identify Gradient Dilution as the root cause of performance degradation, wherein optimization signals required to preserve old knowledge are progressively weakened. This phenomenon manifests as a cascading erosion of preservation gradients in magnitude, direction, and support coverage, driven by three tightly coupled factors: Signal Dispersion, where foreground gradients are overwhelmed by background noise; Assignment Drift, where stochastic query-target matching induces inconsistent gradient trajectories; and Support Attrition, where gradients from retained samples insufficiently cover the old-class feature space, weakening decision boundaries under interference from new classes. To counteract this, we propose FAS, a unified framework that Focuses, Aligns, and Sustains gradient flow throughout incremental learning. Specifically, we introduce prior-injected queries to focus discriminative signals by filtering background interference at the source. We further propose deterministic anchor distillation to align query-target assignments and enforce semantic consistency across stages under unstable matching. Finally, we devise manifold-support replay to sustain distributional support of old classes, counteracting representational erosion induced by continual updates. Extensive experiments show that FAS restores robust optimization dynamics and outperforms state-of-the-art methods, achieving over 5.0 AP improvement in the challenging 40+10x4 incremental setting.
### Title:
          MamBOA: State-Space Architecture for Video Recognition
 - **Authors:** Mustafa Bora Çelik
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-grained action recognition demands temporal reasoning that general-purpose architectures address through different cost-accuracy tradeoffs: 3D dense operators couple computation to the input volume, while difference-based methods approximate motion through rigid, hand-crafted subtraction of uncontextualized features - each reflecting a deliberate design choice with corresponding limitations in expressiveness or flexibility. We present MamBOA, a backbone-agnostic temporal framework built upon a novel interleaved scan structure that recasts the selective state-space recurrence (S6) as a native motion synthesizer. By interleaving consecutive feature representations extracted from a pretrained backbone into a single alternating sequence, the proposed scan structurally drives the recurrence to encode both temporal observations of each position within a shared hidden state, separated by only a single decay step - rendering the inter-frame transition an intrinsic component of the state dynamics rather than an externally computed quantity. A cascade of dedicated alignment and decoding operations then distills this joint encoding into an explicit motion representation, which a dual-path pooling mechanism adaptively aggregates by balancing attention-driven selection with uniform temporal coverage. The framework interfaces seamlessly with CNN, Transformer, and Mamba backbone families, adding only ~2.1 GFLOPs per feature pair. On Diving48, MamBOA achieves 85.02% Top-1 accuracy with an image-pretrained backbone and 86.24% with a video-pretrained backbone processing the entire video in a single forward pass - demonstrating that structurally induced state-space dynamics constitute a principled and general foundation for motion modeling.
### Title:
          Enhancing Precision Agriculture with a Hybrid Deep Learning Framework for Multi-Class Plant Disease Classification and Interpretability
 - **Authors:** Hasibul Islam Sufi, Ridam Roy, Shayla Alam Setu, Mahimul Islam Nadim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study proposes an overall deep learning architecture for multi-class classification of plant diseases from high-resolution leaf imagery, with a particular interest in investigating the behavior of ResNet-50 and a hybrid ResNet + Vision Transformer (ViT) design. A specially gathered image database with 15,200 training images and 3,800 validation images spanning 38 classes across multiple crops, including tomato, apple, grape etc. were subjected to preprocessing steps such as resizing, normalization, and data augmentation to enhance model robustness. Multiple architectures, including ResNet-50, MobileNetV2, and EfficientNet-B0, were trained and compared with the hybrid ResNet + ViT model. All models were fine-tuned using the AdamW optimizer and cross-entropy loss, with early stopping applied to prevent overfitting and ensure generalization. Furthermore, interpretability techniques such as Grad-CAM and saliency maps were implemented to indicate disease-relevant regions, while segmentation-based analysis was performed to identify the affected parts of a leaf. For every one of the considered architectures, ResNet-50 led to the highest accuracy of 98.74%, whereas the hybrid ResNet + ViT model achieved a competitive accuracy of 98.58%, showing that the hybrid architectures were effective in capturing both local and overall information. The experimental results showcase the promise of transformer-based models to achieve highly accurate, interpretable, and computationally efficient computer-based multi-class multi-disease classification systems, providing helpful assistance for cultivation management practices as well as for precision farming.
### Title:
          Adaptive Resource Management and Quality Control for Streaming Video Generation
 - **Authors:** Yifei Xia, Hao Yuan, Suhan Ling, Haoran Sun, Hanke Zhang, Xupeng Miao, Fangcheng Fu, Bin Cui
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive diffusion transformers (AR-DiTs) recast video generation from an offline paradigm to a real-time streaming one: the model generates video one chunk at a time, making each chunk available for playout once produced. The service-level objective (SLO) for this paradigm is no longer fixed latency or throughput but the preservation of playout continuity: generation must stay ahead of the playout timeline. Once generation falls behind, the remaining playable buffer (playout slack) is exhausted, and users experience visible stalls. This objective reveals two serving design insights. First, real-time video generation has a dynamic SLO that evolves with playout progress, so resources should move toward streams with lower playout slack. Second, an acceptable chunk delivered on time is preferable to a late high-fidelity chunk, so per-chunk fidelity configurations should adapt to available playout slack. Guided by these insights, we present SlackServe, a playout-slack-driven serving system that preserves playout continuity in real-time streaming video generation. SlackServe uses playout slack as a unified signal, reallocating resources across streams through three-tier priority queues, re-homing, and elastic sequence parallelism, while selecting per-chunk fidelity configurations within each stream through Bi-Modal Pareto Routing under a quality floor. On a 16-H100 GPU cluster, SlackServe improves Quality of Experience (QoE), measured by Continuous Play Ratio (CPR), by 1.64x-3.29x and reduces Time to First Chunk (TTFC) by 1.61x-9.65x over baselines, while preserving comparable generation quality.
### Title:
          SGFormer++: Semantic Graph Transformer for Incremental 3D Scene Graph Generation
 - **Authors:** Mengshi Qi, Changsheng Lv, Zijian Fu, Xianlin Zhang, Huadong Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we propose SGFormer++, a novel Semantic Graph Transformer for 3D scene graph generation (SGG), which aims to parse point cloud scenes into semantic structural graphs, where nodes denote detected object instances and edges encode their pairwise relationships, with the core challenge lying in modeling complex global scene structure. While existing graph convolutional network (GCN)-based methods suffer from over-smoothing and limited receptive fields, SGFormer++ leverages Transformer layers as its backbone to enable global message passing. Specifically, we introduce two key components tailored for 3D SGG: (1) a Graph Embedding Layer++ that efficiently integrates edge-aware global context with linear computational complexity, and (2) a Semantic Injection Layer++ that enriches visual features with linguistic priors from large language models (LLMs) and vision-language models (VLMs), boosting semantic representation without introducing extra trainable parameters. To further address the practical challenge of incremental SGG (I-SGG), where new relationship categories arrive sequentially, we equip SGFormer++ with a novel Spatial-guided Feature Adapter, which calibrates predicate features using subject-object spatial geometry to counter scale variation, and a Cascaded Binary Prediction Head that mitigates catastrophic forgetting via task-incremental classifier expansion and logit distillation. Extensive experiments on the 3DSSG benchmark demonstrate that SGFormer++ achieves state-of-the-art performance in both standard and incremental settings: it yields a significant 4.49% absolute improvement in Predicate A@1 under the incremental setting. Code and data are available at: this https URL.
### Title:
          DYNA-PRUNER: Input-Adaptive Data-Model Co-Pruning for Efficient and Scalable Spatio-Temporal Media Prediction
 - **Authors:** Fuyan Zhang, Yuqi Li, Yingli Tian, Edmond S.L. Ho
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spatio-temporal prediction supports radar/satellite nowcasting and city-scale traffic monitoring, but modern models are often too expensive for real-time deployment. This stems from a mismatch between dense computation and strong input-dependent redundancy (e.g., calm seas or clear skies). To enable automated, resource-aware architecture optimization in scalable media analysis, we propose Dyna-Pruner, an end-to-end framework for input-dependent co-pruning of data and model structure. A shared-importance synchronization mechanism generates coupled masks that prune redundant regions and their corresponding computational units (e.g., convolutional filters), yielding per-sample sparse sub-networks at inference time. Experiments on WeatherBench, SEVIR, and TaxiBJ show seamless integration with CNN, RNN, and Transformer backbones, reducing FLOPs by up to $70\%$ and achieving a $2.5\times$ speedup on NVIDIA Jetson AGX Orin with negligible accuracy loss ($<1\%$).
### Title:
          Facial Affect Analysis for Service-Oriented Systems: Advances, Challenges, and Future Visions
 - **Authors:** Spyridon Georgiou, Aggelos Psiris, Thomas Lagkas, Vasileios Argyriou, Panagiotis Sarigiannidis, Iraklis Varlamis, Georgios Th. Papadopoulos
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Facial Affect Analysis (FAA) is evolving from a stand-alone recognition task into a reusable perception capability for Service-Oriented Software Ecosystems (SoSE). This paper preserves the FAA methodological core while reframing recent advances through systems-engineering requirements for composable and dependable services. We review representative progress in static and dynamic expression analysis, action-unit and micro-expression modeling, and modern CNN, Transformer, graph, and hybrid architectures, then interpret these advances by their operational fit in edge, cloud, and hybrid service pipelines. The synthesis emphasizes SoSE concerns that determine deployability: service contracts for uncertainty-aware outputs, latency and availability envelopes, lifecycle monitoring and recalibration, governance-aware integration, and interoperability across independently evolving components. Our analysis shows that benchmark gains alone are insufficient for SoSE readiness; robustness under shift, intervention stability, fairness, privacy posture, and runtime guarantees are equally critical. We conclude with a roadmap for treating FAA as an operational service component with explicit interfaces, measurable quality attributes, and accountable lifecycle management.
### Title:
          Hierarchical Modeling of ICD Codes in EHR Foundation Models
 - **Authors:** Megha Thukral, Dong Gyun Kang, Rudra Pratap Singh, Shruthi Kashinath Hiremath, Katrin Hänsel, Thomas Plötz
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electronic health record foundation models typically treat ICD diagnosis codes as flat tokens, overlooking the clinically meaningful hierarchical structure that captures disease families, subcategories, and fine-grained diagnostic detail. As a result, existing EHR representation learning methods do not explicitly exploit the hierarchical structure already present in the coding system. In this work, we study ICD-10-CM hierarchy as a general inductive bias for clinical representation learning. We investigate two complementary mechanisms for incorporating hierarchy: first, by augmenting diagnosis sequences in a BERT-style transformer with tokens corresponding to different levels of the ICD hierarchy, and second, by injecting hierarchy into graph-based code representations through hierarchy-aware edges combined with diagnosis co-occurrence structure. Across these settings, we evaluate whether explicit hierarchy improves downstream prediction, which levels of the hierarchy are most useful, whether hierarchy encoding improves transfer across datasets, and how hierarchy reshapes embedding similarity structure. We conduct experiments on two large-scale real-world clinical datasets: MIMIC-IV, used for pretraining and in-domain evaluation, and eICU, used to assess cross-dataset transfer via frozen encoder probing. Our findings show that explicitly encoding ICD hierarchy improves over flat code representations in both in-domain and cross-dataset settings, while revealing that the most useful level of hierarchy depends on both the task and the modeling approach. More broadly, we focus on hierarchy-aware EHR representation learning and show that the benefits of encoding hierarchy are generalizable across modeling settings and hierarchy levels.
### Title:
          AQ4SViT: An Automated Quantization Framework with Search Gating Policy for Compressing Spiking Vision Transformers
 - **Authors:** Rachmad Vidya Wicaksana Putra, Saad Iftikhar, Muhammad Shafique
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking Vision Transformers (SViTs) have emerged as alternative low-power ViT models, but their large sizes hinder their deployments on resource-constrained embedded AI systems. To address this, state-of-the-art works proposed quantization techniques to compress SViT models, but their manual, human-guided approach needs a huge design time and power/energy consumption to find the appropriate quantization setting for each given network, making this approach not scalable for quantizing multiple networks. Toward this, we propose AQ4SViT, a novel automated quantization framework for SViTs that can provide quick quantization settings with good trade-offs between accuracy and memory. To achieve this, AQ4SViT employs the following key ideas: quantization search strategy that evaluates the quantization setting candidates while considering the accuracy constraint; and search gating policy that quickly evaluates and selects promising quantization candidates by leveraging membrane potential drift as a performance proxy. In the search gating policy, AQSViT employs two search algorithm variants to provide trade-off options: Greedy search, which performs fast but may lead to local optima; and Beam search, which performs slower but has better performance in finding global optima selection due to a wider search space. Experimental results show that AQ4SViT-Greedy quickly finds the appropriate quantization settings, achieving up to 6.6x faster search time and up to 82.5% memory saving compared to the state-of-the-art; while AQ4SViT-Beam further reduces the memory footprint by up to 90% compared to the state-of-the-art, but with 4.5x longer search time; all these results are obtained while maintaining high accuracy within 1.5% from the original/non-quantized models on the ImageNet dataset. These results highlight that AQ4SViT framework offers advancements toward SViT deployments on embedded AI systems.
### Title:
          Track2View: 4D-Consistent Camera-Controlled Video Generation via Paired 3D Point Tracks
 - **Authors:** Feng Qiao, Zhaochong An, Zhexiao Xiong, Serge Belongie, Nathan Jacobs
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Re-rendering an existing video from a novel camera viewpoint requires the output to follow the prescribed camera trajectory while preserving the appearance and dynamics of the original scene across every frame. Existing methods rely on per-frame pose embeddings, noisy point-cloud renderings, or implicit learned correspondences, none of which provides an explicit, temporally continuous link between source and target pixels. We propose Track2View, which conditions a video diffusion transformer on paired 3D point tracks: sparse trajectories of scene points projected into both the source and target camera views. These tracks provide explicit spatiotemporal correspondences that are temporally continuous by construction, encoding what content should appear where and when. At the core of Track2View is a dual-view track conditioner that transfers visual context from source to target view through parameter-free geometric operations and learned temporal aggregation, ensuring generalization to arbitrary camera trajectories without memorizing specific motions. We further introduce a data curation pipeline that extracts one-to-one track correspondences by running a 3D point tracker on temporally concatenated multi-camera view pairs. On a 400-video benchmark spanning static and dynamic scenes, Track2View achieves state-of-the-art results across visual quality, view synchronization, and camera accuracy, reducing rotation error by 30-65% and translation error by 61-72% relative to leading baselines. Project page is available at this https URL: this https URL
### Title:
          Robots as Tokens: Unified Diffusion Transformer for Coordinated Multi-Robot Trajectory Generation
 - **Authors:** Ruofei Bai, Jie Chen, Yuxin Cai, Jun Li, Wei-Yun Yau, Lihua Xie
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The success of generative models in language and visual generation has inspired extensive applications to generative robot planning. However, most existing works either focus on single-robot planning, or generate multi-robot trajectories in a sequential manner with iterative post-processing to resolve inter-robot conflicts. In this work, we investigate whether coordinated multi-robot trajectories, as a special spatiotemporal distribution, can be learned and generated with a generative model in a feed-forward manner. We propose Robots as Tokens (Roken), a unified diffusion transformer that directly generates multi-robot trajectories that satisfy both (individual) safety and (global) connectivity constraints. The core design of Roken is to represent each robot as a discrete token, allowing them to naturally interact with each other through self-attention, and cross-attend to map tokens for environment layouts. We further introduce several auxiliary tasks based on Bayes' theorem to provide multi-scale spatial-temporal supervision for efficient learning of the conditional distribution. In training, Roken absorbs diverse expert trajectories from different team sizes. During inference, Roken behaves as a versatile multi-robot planner that can handle single-robot planning, coordinated multi-robot trajectory generation, and conditional trajectory generation by fixing some robot tokens as conditions. Experiments in diverse cluttered environments show that Roken can generate coordinated multi-robot trajectories to perform connectivity-constrained goal navigation tasks with high success rates, outperforming the baseline method used to generate the training dataset. Roken also demonstrates good scalability after training with mixed team sizes, and shows generalization to unseen or partially observed environments, verifying its potential to learn from diverse data and perform versatile tasks.
### Title:
          A Decision-Theoretic View of Test-Time Training: When, How Far, and Which Directions to Adapt
 - **Authors:** Tomoya Wakayama
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Statistics Theory (math.ST); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Test-time training (TTT) adapts a pretrained model to each prompt via parameter updates, improving accuracy under pretraining-to-test distribution shifts. Yet, its performance often suffers from instability and sensitivity to hyperparameters such as update steps and subspace. We explain this behavior through a decision-theoretic lens, treating TTT as implicit Bayesian inference in the kernel regime. Under a Gaussian process benchmark, we show that TTT reduces prediction error when updates are spectrally matched to the prompt's signal-to-noise ratio and aligned with query-relevant eigen-directions. This perspective underpins the following results: (1) we show when fixed update steps and subspaces fail under distribution shifts, motivating adaptive strategies; (2) we prove that selecting update steps via prompt evidence admits a PAC-Bayes guarantee against overfitting; and (3) we characterize the Bayes-optimal update subspace under a linear-Gaussian correction model, yielding a scoring rule for selecting Transformer blocks and heads. Our theory helps explain the empirical instability of TTT, taking a step toward principled guidance for when, how far, and which directions to adapt.
### Title:
          MoECa: Aligning Feature Reuse with Expert Decomposition in Diffusion Transformers
 - **Authors:** Maoliang Li, Haojing Chen, Jiayu Chen, Zihao Zheng, Xinhao Sun, Hailong Zou, Xiang Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers with Mixture-of-Experts (DiT-MoE) improve model capacity under sparse activation, but diffusion inference is still bottlenecked by redundant computation across timesteps. Existing caching methods mainly operate at the token level, which becomes suboptimal in DiT-MoE because each token update is internally decomposed into multiple routed expert branches. Our analysis shows that cross-timestep redundancy in DiT-MoE is better characterized at the expert-branch level than at the whole-token level. Based on this observation, we propose MoECa, a fine-grained caching framework that performs branch-level feature reuse across timesteps. MoECa further introduces expert-aware adaptive control and synchronized cache updates across MoE and attention paths to maintain stable intermediate states. Experiments on multiple DiT-MoE models show that MoECa consistently achieves a better speed-quality trade-off than prior caching methods, with up to 2.83$\times$ inference speedup and minimal quality degradation.
### Title:
          CEVAR: Centerline Embedding Extraction for Endovascular Aneurysm Repair
 - **Authors:** Roman Naeem, Timo Niiniskorpi, Charlotte Sandström, Naman Desai, Anders Jeppsson, Ida Häggström, Fredrik Kahl, Håkan Roos, Jennifer Alvén
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-term mortality rates after endovascular aneurysm repair (EVAR) remain elevated due to post-EVAR rupture caused by loss of seal in stent graft sealing zones. Structured CT review using centerline measurements improves detection, but current workflows require manual centerline editing and expert operators. We propose a transformer framework for automated, protocol-driven sealing zone assessment that combines 3D centerline tracking with embedding-based geometric prediction. Two state-of-the-art image-to-graph models are evaluated for aorto-iliac centerline extraction from follow-up CT and for measurement of stent position, vessel diameters, and seal lengths according to EVAR4C protocol. Across the full test set and a challenging no-contrast subset, the proposed fully automatic method outperforms the commercial semi-automatic workflow.
### Title:
          The Reservoir Attention Network: Cross-Pass State in Pretrained Transformers via Content-Addressable Reservoir Injection
 - **Authors:** Emma Leonhart
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A feasibility and dynamics study of the Reservoir Attention Network (RAN), an architecture that injects a fixed, randomly-initialized reservoir into the mid-layer attention of a pretrained transformer to carry state across forward passes. Experiments span GPT-2 (124M, 355M) to Qwen2.5 (0.5B, 1.5B) on a single consumer GPU. The tasks are minimal probes chosen to isolate individual mechanisms; the broader always-alive agent vision is treated throughout as compute-limited future work, not a claim of this paper. The reservoir is left untrained (fixed random) by design: this isolates whether untrained recurrent dynamics alone suffice to carry usable cross-pass state, leaving trained recurrence as a complementary, more expensive direction.
### Title:
          Recurrent Reasoning on Symbolic Puzzles with Sequence Models
 - **Authors:** Gowrav Mannem, Chowdhury Marzia Mahjabin, Jason Chen, Shivank Garg, Kevin Zhu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models often appear strong on symbolic and algorithmic tasks, yet this apparent strength can hide brittle behaviour when problems become longer, harder, or slightly out of distribution. A major limitation of current reasoning benchmarks is that many primarily test whether a model can produce a valid answer, while paying less attention to whether the solution is minimal, robust, and stable under controlled difficulty scaling. We introduce RecurrReason, a difficulty-controlled benchmark of four recurrent logic puzzles (Tower of Hanoi, River Crossing, Block World, and Checkers Jumping) with BFS-optimal trajectories and a single interpretable difficulty parameter $N \in \{1,\dots,10\}$, totalling 10{,}817 unique puzzles and 285{,}933 moves. We benchmark two Transformer families, an encoder-decoder model (T5-style) and a decoder-only model (GPT-2-style), under consistent data splits and evaluation criteria, training on $N{=}1$ to $7$ and evaluating on both held-out in-distribution instances and harder out-of-distribution instances at $N{=}8$ to $10$. Fine-tuned pre-trained T5 achieves 97.27\% validation and 81.00\% OOD accuracy on Block World; all models score 0.00\% on River Crossing under all conditions. Failure mode analysis reveals that architecture is a stronger determinant of success than scale. Pre-training transfers only to puzzles with locally structured transition functions. Our code and dataset will be open-sourced upon acceptance.
### Title:
          Robust Transformer-Based One-Step Stock Index Forecasting via Shifted Data Augmentation
 - **Authors:** Tien Thanh Thach
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Statistical Finance (q-fin.ST)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have shown remarkable success in sequence modeling, yet their direct application to financial time series remains challenging due to noisy signals, short-memory dynamics, and distributional shifts. This paper proposes a modified Transformer architecture for one-step stock index forecasting, combined with advanced learning-rate scheduling and a novel Shifted Data Augmentation (SDA) technique. We evaluate the proposed framework on two benchmark stock index datasets, VN30 and S&P 500. Experimental results demonstrate that cosine annealing with warmup consistently improves forecasting accuracy over the generalized inverse-power scheduler. Furthermore, SDA substantially reduces forecasting errors and run-to-run variability while improving robustness to hyperparameter selection. The combination of cosine annealing scheduling and SDA achieved the best performance on both datasets, indicating that data augmentation can play a more important role than increasing model complexity in Transformer-based financial forecasting. These findings provide a practical and computationally efficient approach for robust stock index forecasting in noisy financial environments.
### Title:
          ttda704 at SemEval-2026 Task 4: Modeling Narrative Structures via Pseudonymization and Multi-View Sentence Alignment
 - **Authors:** Tai Tran Tan, An Dinh Thien
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present our approach to SemEval 2026 Task 4: Narrative Story Similarity and Narrative Representation Learning. Our solution uses contrastive learning with fine-tuned sentence transformers to capture narrative similarity across abstract themes, course of action, and outcomes. We develop two pipelines: (Track A) a single-view method that encodes full narratives with smart layer freezing to reduce overfitting, and (Track B) a multi-view method that models theme, plot, and outcome with view-specific projection heads and self-supervised alignment. Both pipelines build on sentence-transformers models and are trained with contrastive loss on synthetic data. The code is available at the following GitHub repository: this https URL.
### Title:
          DifFRACT: Diffusion Feature Reconstruction and Attribution for Circuit Tracing
 - **Authors:** Artyom Mazur, Nina Konovalova, Aibek Alanov
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability seeks to explain neural network behavior by decomposing model computations into interpretable features and circuits. While transcoder-based circuit tracing has recently enabled detailed causal analyses of large language models, multimodal diffusion transformers for image generation remain comparatively opaque. We still lack tools for understanding how semantic information propagates across denoising steps and how text and image representations interact within double-stream MM-DiT architectures. Existing methods provide only partial insight: attention maps expose a limited view of token interactions, while sparse autoencoders can discover interpretable features but do not directly reveal how these features are transformed and composed through nonlinear MLP layers. In this work, we extend transcoder-based circuit tracing to multimodal diffusion transformers. We train timestep-conditioned transcoders that faithfully approximate the input-output behavior of MLP sublayers in FLUX.1[schnell]. By replacing MLPs with transcoders and linearizing the remaining computation, we obtain exact feature-to-feature attribution and recover compact, interpretable circuits. Empirically, our transcoders match or slightly outperform sparse autoencoders on the sparsity-faithfulness tradeoff. The resulting circuits reveal mechanisms underlying attribute binding and cross-stream semantic propagation, and provide causal explanations for systematic generation errors. Moreover, circuit-guided interventions are substantially more precise and effective than standard SAE-based steering. Our results demonstrate that transcoder-based circuit analysis is feasible for state-of-the-art diffusion transformers and provides a powerful framework for understanding and controlling multimodal generative models. The code is available at this https URL
### Title:
          David vs. Goliath in Next Activity Prediction: Argmax vs. LSTM, Transformer, and LLM
 - **Authors:** Hans Weytjens, Ingo Weber
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Next activity prediction (NAP) is a cornerstone of predictive process monitoring (PPM), enabling organizations to move from retrospective analysis to proactive process steering. The PPM field has progressed from classical machine learning through deep learning architectures such as LSTMs and Transformers to large language models (LLMs). Despite growing model complexity, no benchmark jointly compares LLMs, Transformers, LSTMs, and simple baselines in a direct sequence modeling setting for NAP. In this paper, we fill this gap with a systematic benchmark. We compare vocabulary-adapted LLMs, Transformers trained from scratch, LLM-distilled Transformers, and LSTMs against a simple counting-based argmax baseline across seven real-life event logs. Our results tell a David vs. Goliath story: pretraining confers no consistent improvement over training from scratch, model size shows little effect on performance, and on most datasets the argmax baseline matches or approaches the performance of billion-parameter LLMs.
### Title:
          Metis: A Generalizable and Efficient World-Action Model for Autonomous Driving and Urban Navigation
 - **Authors:** Jingyu Li, Zhe Liu, Dongnan Hu, Junjie Wu, Zipei Ma, Wenxiao Wu, Chao Han, Zhihui Hao, Zhikang Liu, Kun Zhan, Jiankang Deng, Xiatian Zhu, Li Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World action models~(WAMs) have shown great promise for autonomous driving and urban navigation. Built upon Vision-Language-Action models or video generation models, existing approaches suffer key limitations: (1) High inference latency due to future observation prediction at test time, and (2) tightly coupled video and action modeling leading to representational mismatch and degraded generalization. To address both issues, we propose Metis, an end-to-end WAM framework that decouples video generation and action prediction. Specifically, Metis employs a Mixture-of-Transformers architecture with dedicated experts for video generation and action prediction, preserving the intrinsic distributional properties of each task. To enhance efficiency, we introduce an asymmetric attention mask that enables joint training of both experts while allowing the action model to bypass explicit video generation during inference. This design ensures training-inference consistency and significantly reduces computational costs without compromising planning performance. Extensive experiments demonstrate state-of-the-art performance on the NAVSIM navhard and navtest benchmarks and the CityWalker navigation benchmark, validating both the generalizability and efficiency across diverse tasks. Real-robot deployments further confirm the practical feasibility of our approach.
### Title:
          Google's Training Supercomputers from TPU v2 to Ironwood: Architectural Stability, Scale, Resilience, Power Efficiency, and Sustainability Across Five Generations
 - **Authors:** Norman P. Jouppi, Sridhar Lakshmanamurthy, Cliff Young, David Patterson
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper (to appear in the July/August 2026 issue of IEEE Micro magazine) summarizes five generations of Google s TPUs, from TPU v2 to Ironwood, highlighting their evolution as scalable, resilient, power-efficient, sustainable supercomputers for AI training. It details the TPU s stable architecture, which has surprisingly easily accommodated the rapidly changing deep neural network workloads, such as the rise of Transformers. Key advancements over eight years include 10x increase in HBM capacity and bandwidth per node, a 100x increase in peak node performance, and a 3600x increase in supercomputer performance. The paper also discusses the role of optical circuit switches, built-in self test, and hardware replay in enhancing resilience and how TPU's environmental impact is reduced with substantial improvements in performance per Watt and in carbon emissions per floating point operation. It concludes by identifying six features that may well characterize successful training accelerators of this decade.
### Title:
          VL2Spike: Spike-driven Distillation from VLMs for Low-Power Visual Perception in Embodied AI
 - **Authors:** Zinan Liu, Eric Zheng, Soumyaratna Debnath, Hao Shi, Ling Xiao, Lin Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking neural networks (SNNs) are brain-inspired, event-driven models that compute with sparse spikes, which enables highly efficient visual perception in resource-constrained embodied AI models. The emergence of Spiking-Transformer models with spike self-attention has substantially improved the learning capacity of pure SNNs. Although SNNs are energy efficient, their performance is still limited by the spike-based architecture and optimization challenges, as standard gradient descent rules cannot be directly applied. Recently, vision-language models (VLMs) have shown rich multi-modal knowledge representation capabilities for visual perception. Thus, it is promising to leverage VLMs for better Spikformer training. To this end, we present VL2Spike, a novel spike-based knowledge distillation (KD) framework that bridges multi-modal knowledge from VLMs with compact Spikformer models. This design enhances the learning capacity of Spikformer models while preserving their energy-efficiency merits, thereby offering a practical pathway toward low-power robotic perception. Our VL2Spike brings two key technical contributions. To align with spiking dynamics, we first propose spatial-temporal visual spike (SVS) distillation, which achieves (1) shared manifold alignment between VLM image features and spike tokens, and (2) warm-started temporal consistency on membrane potentials and spike rates. We then design a novel spike prototype-guided linguistic (SPL) distillation strategy that aligns Spikformer's class prototypes and logits with promptable VLM text embeddings. Extensive experiments show that VL2Spike achieves 6.81% gain across three static datasets with only 15.7% energy consumption. It also exhibits strong generalization capacity on robotic visual place recognition (VPR) with a gain of 6.63%, highlighting its potential for low-power perception in embodied AI.
### Title:
          High-Fidelity 4D Hand-Object Capture via Multi-View Spatiotemporal Tracking and Physics-Aware Gaussians
 - **Authors:** Bo Peng, Xu Chen, Yi Gu, Hidenobu Matsuki, Mingsong Dou, Jingjing Shen, Deying Kong, Juyong Zhang, Zhengyang Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The growing demand for high-fidelity 4D hand-object interaction (HOI) data in embodied AI and spatial computing is currently bottlenecked by the reliance on pre-scanned object templates and physical markers. While recent methods have demonstrated promising results in reconstructing 4D hand-object interaction from videos, they are highly sensitive to initial estimates of hand and object poses. Yet, estimating these poses from images is challenging, in particular under severe occlusion which is inherent in hand-object interaction scenarios. We propose a novel system for the robust and accurate reconstruction of hands and objects from synchronized and calibrated multi-view videos without requiring any templates or markers. Our system consists of two main components with key innovations: (1) a multi-view feed-forward transformer model that aggregates cross-view geometry and temporal cues to provide a reliable, metric-consistent initialization for both poses and dense object geometry, and (2) a hand-object physics-aware Gaussian-based optimization framework to refine the initial estimates, integrating tetrahedral constraints, collision refinement, and appearance decomposition to produce physically plausible and visually accurate reconstruction. Validated on public benchmarks and an extensive internal dataset, our pipeline achieves highly robust, artifact-free reconstruction, providing an efficient foundation for automated 4D asset generation. Our project page are available at this https URL.
### Title:
          Reinforcement Learning for LLM-based Event Forecasting
 - **Authors:** Amit Arnold Levy
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We use Group Relative Policy Optimization (GRPO), a recently devised sample and memory efficient reinforcement learning method, to finetune pretrained LLMs in the range of 1.5B to 14B parameters equipped with the ability to get current information through the use of a Wikipedia revisions tool, or news summaries, to forecast real events beyond the knowledge cutoff of the LLM, as well as problems made to simulate different aspects of the dynamics of that training. We use the results of these experiments to comment on the scaling capability of LLMs for forecasting, as well as classify how judgmental forecasting fits into the verifiable/unverifiable domain taxonomy, considering the impact of the inherent aleatoric uncertainty when forecasting future events (e.g. the roll of a die). As a result of the GRPO training, we manage to bring a 1.5B parameter transformer (Qwen 2.5 1.5B) to forecasting performance superior to Claude Sonnet 3.5 over the same dataset as measured by cross entropy from the market agreed probabilities. We also discuss various dead ends on the path to this result.
### Title:
          Multi-Task Tennis Stroke Biomechanics Analysis Using MediaPipe Pose
 - **Authors:** Jigyashman Hazarika
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We built a multi-task pipeline for tennis stroke biomechanics from plain RGB video. On top of pose-based stroke recognition, it adds two new tasks, predicting shot direction and grading posture quality, plus a rule-based feedback layer that suggests coaching tips. Strokes are found automatically using a weighted joint velocity score, s(t) = 0.5 v_wrist + 0.3 m_elbow + 0.2 m_shoulder, removing the need for manual annotation. Pose comes from MediaPipe Pose Landmarker (33 landmarks, metric world coordinates), with each stroke turned into a 30-frame by 39-feature sequence for TennisTransformerGPU, a compact 564,103-parameter transformer (4 layers, 4 heads, d=128) with three parallel output heads. Trained on 1,281 labeled strokes from 7 pros and 1 amateur across 11 videos, it hits 83.7% stroke-type accuracy, 61.9% on direction, and 62.6% on posture under a random 80/20 split. The interesting test is cross-player: train on pros, evaluate on the amateur. Stroke type barely budges, 82.9%, a 0.8% drop. Direction prediction does not transfer; it just falls back to the majority class. An ablation shows why world coordinates matter so much here: switching to image-space landmarks tanks cross-player stroke-type accuracy from 83% to 47% and direction from 68% to 21%. Everything runs on Kaggle's free T4 GPU tier and is fully reproducible.
### Title:
          SparseCol: A 1320 BTOPS/W Precision-scalable NPU Exploiting Training-free Structured Bit-level Sparsity and Dynamic Dataflow
 - **Authors:** Man Shi, Vikram Jain, Weijie Jiang, Chao Fang, Antony Joseph, Wim Dehaene, Marian Verhelst
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bit-serial computation enables sequential processing of data at the bit level, providing several advantages, such as scalable computational precision. This approach has gained significant attention, especially for exploiting bit-level sparsity in AI workloads. While current bit-serial processors leverage bit-level sparsity to eliminate the computation associated with zero bits, they face a fundamental trade-off: either they suffer from low memory-access and computation efficiency caused by irregular patterns of non-zero bits, or they incur substantial area overhead from complex online scheduling mechanisms required to reorganize bit-level data and preserve memory access and computation regularity. Therefore, we present the SparseCol processor, designed to harness extensive bit sparsity while maintaining high hardware utilization across various AI applications, including CNNs, RNNs, and transformers. In contrast to traditional methods, SparseCol exploits structured bit-level sparsity, denoted by bit-column sparsity, without requiring any re-training. Furthermore, SparseCol implements a dynamic dataflow architecture that tackles hardware under-utilization issues commonly found in existing bit-serial solutions. Fabricated in 16nm CMOS node, SparseCol delivers 1320 BTOPS/W (BTOPS represents Binary Tera-Operations Per Second, calculated as #W bits x #A bits TOPS) peak efficiency while maintaining accuracy, outperforming SotA sparse processors in terms of efficiency by 6.8x. Comprehensive evaluations on CNN classification tasks and transformer architectures demonstrate system-level efficiencies of 745.02 BTOPS/W and 850.5 BTOPS/W, respectively.
### Title:
          Trusting Right Predictions for Wrong Reasons: A LIME Based Analysis of Deep Learning Interpretability in Lung Cancer Diagnosis
 - **Authors:** Samarpan Poudel, Vladislav D Veksler
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lung cancer is the leading cause of cancer-related mortality, with approximately 2.5 million new cases and 1.8 million deaths annually, making reliable diagnosis a clinical priority. Although deep learning models have achieved strong performance in lung cancer classification, evaluation has largely focused on predictive accuracy, leaving their decision-making processes insufficiently examined. This study compares three architecturally distinct models: a Convolutional Neural Network (CNN), a pretrained ResNet50, and a Vision Transformer (ViT), trained on the IQ-OTH/NCCD lung cancer CT dataset. Local Interpretable Model-Agnostic Explanations (LIME) were applied to investigate model reasoning. In addition to standard performance metrics, a dual-correlation framework was introduced to measure both prediction agreement and explanation agreement across model pairs. All three models achieved strong classification performance, with ResNet50 attaining 98.61% accuracy, CNN 97.91%, and ViT 93.75%, while all achieved ROC-AUC scores of 0.99. Prediction correlations exceeded 0.99 across all model pairs, indicating highly consistent outputs. However, LIME explanation correlations remained below 0.26, revealing substantial differences in the image regions used to reach those predictions. Analysis of misclassified samples further identified a consistent spatial pattern: incorrect predictions were associated with attention outside the lung parenchyma, whereas correct predictions focused primarily within lung regions. These findings demonstrate that prediction agreement is a poor proxy for reasoning consistency, and that interpretability evaluation must be treated as an independent validation criterion alongside predictive performance in clinical AI systems.
### Title:
          Long-Context Modeling via GSS-Transformer Hybrid Architecture with Learnable Mixing
 - **Authors:** Kuzey Torlak, Hüseyin Arda Arslan, Anıl Dervişoğlu, Beyza Nur Deniz, Onur Boyar
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modeling long-range dependencies remains a central challenge in natural language processing. Transformer architectures achieve strong performance via self-attention but scale quadratically ($O(N^2)$) with sequence length, while State Space Models (SSMs) scale linearly ($O(N)$) but suffer from a selective recall bottleneck, struggling to retrieve precise information from compressed states. This creates a fundamental tradeoff between efficiency and perplexity. To tackle these challenges, we propose the \textit{Parallel Hybrid Architecture (PHA)}, which runs Gated State Spaces (GSS), Grouped Query Attention (GQA), and Feed-Forward Networks (FFNs) as independent parallel branches fused by a learnable mixing mechanism. Instead of forcing SSMs to approximate attention or serializing the two paradigms, PHA allows each branch to specialize: GSS captures global context, while attention performs selective retrieval, with FFN providing complementary processing. On WikiText-103, PHA achieves 16.51 PPL at 125M parameters, outperforming Hedgehog (16.70) and H3-125M (23.70). Scaling to 180M parameters yields 16.42 PPL, which gives comparable results with the pure attention baseline while delivering 24\% higher throughput and up to 40\% lower memory usage at long contexts. On OpenWebText, our 125M model achieves 19.72 PPL, outperforming standard Transformers (20.60) and GSS hybrid baselines (19.80). These results demonstrate that separating sequence modeling paradigms into parallel specialists enables Transformer-level perplexity with substantially improved efficiency for long-context language modeling.
### Title:
          Scaling Adaptive Depth with Norm-Agnostic Residual Networks
 - **Authors:** Tomás Figliolia, Beren Millidge
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Residual architectures are ubiquitous in deep learning, but they suffer from a subtle structural limitation: the norm of the residual stream can grow rapidly with depth. As a result, updates from later layers become small relative to the accumulated residual state. This reduces their impact on the representation and limits the benefits of scaling models in depth. To address this, we introduce NAG, a norm-agnostic residual architecture that separates magnitude from directional information in the residual stream, preserving meaningful layer contributions throughout depth and preventing later updates from being systematically suppressed by residual-norm growth. Importantly, NAG introduces only a negligible number of additional parameters and relies on simple operations that are easily kernel-fusible, preserving training efficiency in practice. We show that this architecture outperforms baseline Transformers, with gains that increase substantially as depth grows, enabling effective training of much deeper models. The norm-agnostic formulation also leads to an interpretable Mixture-of-Depths (MoD) mechanism that adaptively skips both attention and MLP layers. Beyond serving as a post-training accuracy-compute tradeoff, this mechanism can be used as a pretraining-time scaling strategy: under iso-FLOP training, compute saved by reducing per-token forward-pass cost can be reinvested into training on more tokens while keeping the total parameter count and KV-cache budget fixed. In our experiments, moderate Mixture-of-Depths rates of approximately 20%-25% match full-depth baseline performance under equal training compute while substantially reducing the number of executed layer parameters and forward-pass FLOPs. These results identify sparsity in depth as a new scaling axis for fixed-compute training, enabling very deep yet FLOP-efficient models.
### Title:
          A Comprehensive Survey of Medical Image Segmentation: Challenges, Benchmarks, and Beyond
 - **Authors:** Pengyu Zhu, Xiaojing Zhang, Kunbo Zhang, Chunyan Zhang, Zhenyu Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medical image segmentation plays a critical role in clinical diagnostics, treatment planning, disease monitoring, and neurological disorder identification. This article presents a comprehensive review of its systematic development, covering widely used public datasets, representative methods built on the U-Net, Transformer, and SAM architectures, and key evaluation metrics with their differences, followed by an analysis of major challenges from multiple perspectives. Unlike surveys that focus on a single model family or a specific clinical application, this review organizes U-Net-, Transformer-, and SAM-based methods within a unified analytical framework, with a particular focus on their effectiveness in improving segmentation accuracy and efficiency. This work aims to guide future research and support clinical translation of medical image segmentation, with all related resources publicly available in our GitHub repository: this https URL.
### Title:
          Dehaze-GaussianImage: Zero-Shot Dehazing via Efficient 2D Gaussian Splatting Representation
 - **Authors:** Yuhan Chen, Wenxuan Yu, Guofa Li, Kunyang Huang, Ying Fang, Yicui Shi, Wenbo Chu, Keqiang Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing single image dehazing methods are often constrained by computational redundancy in pixel-level optimization and the lack of physical interpretability in implicit neural networks. These limitations hinder the balance between representation efficiency and reconstruction fidelity. To address these issues, we propose Dehaze-GaussianImage, the first zero-shot framework that introduces 2D Gaussian Splatting (2DGS) into the image dehazing domain to break the traditional pixel-grid processing paradigm. Distinct from static convolutional neural networks (CNNs) or Transformers, our approach models hazy images as continuous and dynamically evolvable anisotropic Gaussian fields. Specifically, we propose a novel reconstruction-decoupling zero-shot learning strategy that embeds the atmospheric scattering model into the Gaussian parameter space. This strategy drives Gaussian primitives to adaptively split, clone, and prune during optimization, achieving geometric-level decoupling of the transmission medium and clear textures. Furthermore, explicit structure-preserving constraints are introduced to suppress artifacts commonly caused by traditional physical priors. Experimental results demonstrate that the proposed method achieves state-of-the-art (SOTA) performance in a fully unsupervised manner with minimal parameters, highlighting the potential of explicit Gaussian representation for low-level vision tasks.
### Title:
          Scaling Short-Term Memory of Visuomotor Policies for Long-Horizon Tasks
 - **Authors:** Rutav Shah, Rajat Kumar Jenamani, Xiaohan Zhang, Lingfeng Sun, Roberto Martín-Martín, Yuke Zhu, Deva Ramanan, Karl Schmeckpeper
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many robotic tasks require short-term memory, whether it's retrieving an object that's no longer visible or turning off an appliance after a set period. Yet, most visuomotor policies trained via imitation learning rely only on immediate sensory input without using past experiences to guide decisions. We present PRISM, a transformer-based architecture for visuomotor policies to effectively use short-term memory via two key components: (i) gated attention, which filters retrieved information to suppress irrelevant details, improving performance by reducing the spurious correlations between the history and current action prediction, (ii) a hierarchical architecture that first compresses local information into compact tokens and then integrates them to capture temporally extended dependencies, improving its compute and memory footprint. Together, these mechanisms enable us to scale short-term memory in visuomotor policies for up to two minutes. To systematically evaluate memory in visuomotor control, we introduce ReMemBench -- a benchmark of eight diverse household manipulation tasks spanning four categories of short-term memory -- designed to foster general memory mechanisms rather than siloed, task-specific solutions. PRISM consistently outperforms prior works, including recurrent architectures, transformers, and their variants -- achieving an absolute improvement of 5%--12% over the strongest baseline. On the RoboCasa and LIBERO benchmarks, it achieves absolute improvements of 11%--15% over its no-memory variant and fine-tuned Vision-Language-Action baselines such as GR00T-N1-3B and OpenVLA, despite not leveraging any large-scale pretraining. Together, PRISM and ReMemBench establish a foundation for developing and evaluating short-term memory-augmented visuomotor policies that scale to long-horizon tasks. Additional materials are available at this https URL
### Title:
          teasr: training-efficient any-step diffusion transformer for real-world image super-resolution
 - **Authors:** Xiang Gao, Chenxin Zhu, Yushun Fang, Qiang Hu, Xiaoyun Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models excel in Real-World Image Super-Resolution (Real-ISR) due to their powerful generative priors but suffer from slow iterative sampling. Although existing one-step distillation methods accelerate inference, they typically require auxiliary teacher models that inflate training memory and restrict scalability to large-scale architectures. Furthermore, these fixed-step models lack the flexibility to trade off speed for quality. In this paper, we propose TEASR, a training-efficient any-step diffusion framework for Real-ISR that enables both one-step and multi-step restoration within a unified model. Our key idea is to perform self-adversarial distillation within a single diffusion model, eliminating the need for auxiliary teachers or discriminators. Specifically, we propose a timestep-aware rectification strategy that stabilizes one-step generation across noise levels. These two designs further enables the distillation of 20B-parameter diffusion models on a single GPU, significantly improving training efficiency. Moreover, we introduce a dual-branch diffusion transformer with decoupled timestep condition to separate the current noise state and the denoising target to enhance sampling quality. Extensive experiments demonstrate that TEASR supports seamless any-step sampling and consistently outperforms state-of-the-art methods across multiple datasets.
### Title:
          Calibrated Sampling-Free Uncertainty Estimation in Bayesian Deep Learning
 - **Authors:** Tobias Jan Wieczorek, Leon de Andrade, Thomas Möllenhoff, Marcus Rohrbach
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern deep learning models remain notoriously prone to overconfidence, limiting their reliability in high-stakes applications. Bayesian methods aim to counter this by learning a distribution over model parameters, and recent advances now make this feasible for large-scale architectures at costs comparable to AdamW. However, a challenge remains at test time: predictions must be averaged across many forward passes with weights sampled from the posterior, which is prohibitively expensive. Variance propagation offers an efficient alternative, computing layer-wise analytical approximations of uncertainty in a single forward pass. While such techniques are effective for MLPs, their extension to modern architectures remains challenging, due to increased depth and diversity of layer types. To fill this gap, we propose Calibrated Variance Propagation (CVP), which introduces a new propagation method for normalization layers, combines it with recent techniques for handling activation functions, and absorbs residual error through a light calibration step. CVP yields comparably accurate uncertainty estimates to MC sampling across transformers and CNNs, at a fraction of the cost. Against prior variance propagation work, CVP improves coverage at $0.5\%$ risk from $8.2\%$ to $14.6\%$ with BEiT-3 on Visual Reasoning (NLVR2) and from $2.6\%$ to $10.8\%$ with ViLT on VQAv2, with gains extending to convolutional architectures.
### Title:
          Synthesizing Best Abstract Transformers via Parallel Bit-Vector Optimization
 - **Authors:** Weiqi Wang, Peisen Yao, Hanrui Zuo, Yuan Li, Hongfei Fu, Kui Ren
 - **Subjects:** Subjects:
Programming Languages (cs.PL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Abstract interpretation provides a principled foundation for constructing sound static analyses through systematic abstraction. A central challenge is synthesizing the best abstract transformers that achieve optimal precision within a given abstract domain. This paper addresses this problem for low-level code modeled with fixed-size bit-vectors. Recent approaches formulate the synthesis task as a multi-objective Optimization Modulo Theories (OMT) problem, but suffer from limited scalability. We introduce Spear, a parallel synthesis framework that exploits a key structural insight: while the bits within each objective must be processed sequentially, the objectives themselves are independent. Spear leverages the independence of inter-objective bits to better parallelize the synthesis. Experimental results on benchmarks across two binary analysis domains show that Spear consistently outperforms state-of-the-art OMT solvers, solving more instances and achieving significantly improved runtimes. To our knowledge, this is the first approach to apply parallelism to accelerate the synthesis of optimal abstract transformers.
### Title:
          Creative Collision: Directorial Persona Steering and Competition in Large Language Models
 - **Authors:** Subramanyam Sahoo, Justin Shenk
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Activation steering has emerged as a powerful tool for shaping the behaviour of large language models at inference time, yet most prior work injects a \emph{single} semantic direction into the residual stream. We study the richer setting in which two semantically opposing steering vectors are superimposed -- a regime we call \textbf{Creative Collision}. Concretely, we construct directorial persona vectors for Steven Spielberg (optimistic, redemptive moral valence) and Martin Scorsese (dark, morally ambiguous) via mean-difference activation contrast on curated screenplay-derived corpora, then interpolate between them with a scalar mixing parameter $\alpha \in [0,1]$ and a steering coefficient $\lambda$. Across five evaluation axes -- moral valence, generation coherence, surface style, directional dominance, and vector geometry -- three principal findings emerge: (i)~Spielberg's representational signature exhibits robust \emph{directional dominance}, suppressing Scorsese's moral influence across almost the entire interpolation range; (ii)~intermediate collision points paradoxically \emph{improve} generation coherence relative to pure single-director steering at high $\lambda$; and (iii)~both personas localise maximally to layer~28 of a 40-layer decoder-only transformer, revealing a shared \emph{moral-tone substrate}. These results illuminate the geometry of competing semantic directions in transformer residual streams and have direct implications for controllable creative generation and value-aligned narrative synthesis.
### Title:
          LiFT: Local Search via Linear Programming for Overfitting-Controlled Transformers
 - **Authors:** Abhishek Shukla, Anikeit Khanna, Ankur Sinha, Faiz Hamid
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes a Linear Programming (LP)-based local search framework for fine-tuning pretrained transformer models with explicit control against overfitting. The approach formulates transformer fine-tuning as a bilevel optimization-based regularization problem, in which model parameters and regularization hyperparameters are jointly updated. Information collected during initial warm-up iterations, including validation gradients and training Hessian information, is used to construct a local descent direction by solving an LP that minimizes a scaled directional derivative while preserving training optimality. This validation-aware descent direction enables focused local updates of both parameters and regularization hyperparameters, reducing overfitting without requiring repeated full retraining cycles. The resulting method, termed Linear Programming-based Fine-Tuning (LiFT) for transformers, differs from conventional fine-tuning by systematically identifying task-specific updates rather than relying on heuristic or grid-based hyperparameter selection. Experiments on GPT-2 Small fine-tuned on WikiText-2 demonstrate that LiFT enables effective adaptation through selective tuning of transformer blocks and regularization parameters, yielding consistent improvements in test perplexity across multiple layer configurations and regularization settings, with particularly pronounced gains in overfitting-prone scenarios. Beyond empirical performance, LiFT establishes a principled connection between transformer fine-tuning, bilevel optimization, local search, and regularization theory.
### Title:
          KeepLoRA++: Continual Learning with Layer-Scaled Residual Gradient Adaptation
 - **Authors:** Mao-Lin Luo, Yi-Lin Zhang, Zi-Hao Zhou, Yankun Hong, Xialiang Tong, Mingxuan Yuan, Tong Wei, Min-Ling Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Continual learning for pre-trained vision-language models requires balancing three competing objectives: retaining pre-trained knowledge, preserving knowledge from a sequence of learned tasks, and maintaining the plasticity to acquire new knowledge. This paper presents KeepLoRA++, balancing these objectives through a unified dual-dimensional knowledge retention mechanism. We analyze knowledge distribution of Transformer architecture from both inter-layer and intra-layer perspectives. The inter-layer perspective examines how retention is distributed across layers, while the intra-layer perspective focuses on the parameter space within each layer. Our analysis reveals a structural property: general transferable knowledge is mainly encoded in the shallow layers and the principal subspace of the parameters, while task-specific adaptations are localized in the deep layers and the residual subspace. Motivated by this insight, KeepLoRA++ introduces a layer-scaled residual gradient adaptation method. New tasks are learned by restricting LoRA parameter updates to the residual subspace, combined with a shallow-to-deep layer scaling, to prevent interference with previously acquired capabilities. Specifically, the gradient of a new task is projected onto a subspace orthogonal to both the principal subspace of the pre-trained model and the dominant directions of previous task features, while simultaneously assigning smaller update magnitudes to shallow layers and larger ones to deeper layers. Our theoretical analysis and empirical evaluations confirm that KeepLoRA++ successfully balances these three competing objectives, consistently outperforming representative baselines across image classification, visual question answering, and video understanding tasks.
### Title:
          Tropical: Enhancing SLO Attainment in Disaggregated LLM Serving via SLO-Aware Multiplexing
 - **Authors:** Jinming Ma, Jiefei Chen, Xiuhong Li, Jiangfei Duan, Haojie Duanmu, Xingcheng Zhang, Chao Yang, Dahua Lin
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To guarantee service quality in transformer based large language model (LLM) serving, it is essential to meet the latency constraints of both the prefill phase (measured by Time-to-First-Token, TTFT) and the decode phase (measured by Time-per-Output-Token, TPOT). Non-disaggregated serving places prefill and decode on the same worker, while disaggregated serving places the prefill and decode on isolated workers. However, no single architecture excels in both TTFT and TPOT metrics. After conducting a root cause analysis, we concluded that indisaggregated LLM serving, prefill execution has minimal interference with decode execution but result in high queuing times. In contrast,non-disaggregated LLM serving effectively reduces queuing times but introduces significant interference between prefills and decodes. In order to leverage the best aspects of both non-disaggregated anddisaggregated LLM serving, we have designed and implemented this http URL introduces an sevice-level objectives (SLO)-aware multiplexing strategy that balances the queuing time and the interference, enabling the LLM serving to achieve high TTFT and TPOT SLOs simultaneously. Our evaluation of real-world datasets reveals that Tropical outperforms both state-of-the-art non-disaggregated and disaggregated LLM serving systems, achieving up to 2.09 more requests within a 90% SLO attainment. Specially, compared to the disaggregated LLM serving system, Tropicalimproves P90 TTFT performance by 9 with only an 15% reduction in P90 TPOT. Against the non-disaggregated LLM serving systems, Tropicaldelivers a 2.8 performance improvement in P90 TPOT while maintaining the same P90 TTFT.
### Title:
          Explainable Flood Segmentation on Sentinel-1 SAR Imagery: A Comparative Study of CNN and Transformer Architectures
 - **Authors:** Arundhuti Banerjee, David Daou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rapid and accurate flood prediction is essential for disaster response and mitigation planning. Synthetic Aperture Radar (SAR) sensors in satellites are well-suited for this purpose because they operate independently of weather and daylight conditions. Although SAR-based data enable all-weather flood monitoring, distinguishing flooded land from permanent water remains a significant challenge, particularly when flooding is defined strictly as inundated land. This study provides a comprehensive comparison of convolutional neural network (CNN) and vision transformer architectures for multi-class flood segmentation using Sentinel-1 SAR imagery, specifically trained to separate flooded land from permanent water bodies and land. Three state-of-the-art (SOTA)CNN-based models, U-Net, U-Net++, and DeepLabV3 with ResNet-34 backbone, and three SegFormer variants (b0,b1,b2) were evaluated in two benchmark datasets, the ETCI NASA dataset and SenFloods11, using scene-based data splits to ensure a realistic assessment of spatial generalization. The results demonstrate that SegFormer-b2 significantly outperforms the U-Net baseline on the ETCI dataset (higher flood IoU across all 7 test scenes in the Wilcoxon signed-rank test), while after fine-tuning on Sen1Floods11, the advantage narrows to within the range of scene variability and is concentrated in spatially fragmented flood events. The study includes both qualitative and quantitative explainability techniques to visually comprehend model decisions and systematically assess prediction reliability. Qualitative analysis reveals that SegFormer-b2 produces more spatially coherent Grad-CAM activations focused on flood-relevant features, while U-Net generates more informative uncertainty estimates along flood boundaries.
### Title:
          Training-free sparse attention based on cumulative energy filtering
 - **Authors:** Chunlu Li, Yixuan Pan, Bai Du, Zhenyuan Chen, Yanzhao Li, Hui Dong, Hui Wang, Zhiqiang Zou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse attention accelerates Diffusion Transformers (DiTs) for video generation by computing only the important tokens while skipping the rest. The token selection strategy is key to balancing sparsity and accuracy. We formulate the token filtering process as a dual-goal optimization problem: maximizing sparsity and minimizing accuracy degradation. Existing algorithms cannot fulfill both objectives simultaneously. For example, Top-p only considers the accuracy constraint, while Top-k maintains a fixed computational budget but loosens the accuracy constraint. This paper demonstrates that maintaining a fixed recall rate is sufficient for ensuring accuracy, whereas a fixed threshold is suboptimal for reducing computational cost. Therefore, we propose a dynamic thresholding scheme to improve sparsity while maintaining the same level of accuracy. Furthermore, our algorithm is deeply integrated with Flash Attention (FA), eliminating the need for any additional masking computation overhead. Experimental results on Wan 2.2 validate that, compared to the BLASST algorithm which is also integrated with FA, our dynamic thresholding strategy enhances sparsity from 61.42\% to 82\% with a VBench metric drop of less than 5\%. This results in an approximate 15\% in attention computation and a $1.61\times$ increase in computational efficiency, which is 1.18x higher than that of BLASST.
### Title:
          Communication-Efficient Verifiable Attention for LLM Inference
 - **Authors:** Ziqun Chen, Ming Wu, Michael Heinrich, Jason Zeng, Huiying Lan, Tianwei Zhang, Rui Tan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Computation integrity of remote large language model (LLM) serving can be questionable. For conventional deep neural networks (DNNs), the existing TEE-shielded DNN partitioning (TSDP) approach uses Trusted Execution Environment (TEE) to compute non-linear components and verify the integrity of linear components offloaded to an untrusted GPU. However, directly applying TSDP to Transformer-based LLMs incurs significant TEE computation and TEE-GPU communication overhead. This paper presents Communication-efficient TEE-GPU Attention (\textsc{VeriAttn}) for accelerating verifiable LLM inference. \textsc{VeriAttn} offloads both linear and non-linear computations of attention to the GPU, while TEE performs verification. Moreover, for prefill, \textsc{VeriAttn} uses a two-level pipeline to overlap data movement, TEE pre-/post-processing, and GPU computation. For decoding, when the key-value cache exceeds available GPU memory, \textsc{VeriAttn} partitions attention across TEE and GPU to reduce repeated key-value transfers. Evaluation on an Intel TDX platform shows that \textsc{VeriAttn} achieves 2.60-3.38$\times$ and 3.86-5.42$\times$ acceleration over TSDP for 6k-token prompts and 10k-token outputs during prefill and decoding, respectively.
### Title:
          Taylor-Calibrate: Principled Initialization for Hybrid Linear Attention Distillation
 - **Authors:** Zhongzhu Zhou, Qingyang Wu, Junxiong Wang, Mayank Mishra, Shuaiwen Leon Song, Ben Athiwaratkun, Chenfeng Xu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hybrid linear attention models offer an appealing path to faster long-context inference: they reduce the quadratic cost and KV-cache burden of full softmax attention while retaining much of the quality of Transformer models. A practical way to obtain such models is to convert a pretrained Transformer instead of pretraining a new architecture from scratch, but this conversion is still brittle. Simply copying the teacher attention projections into a Gated DeltaNet (GDN) student does not specify the new recurrent decay, write, and output-gating dynamics. As a result, the converted model often starts in a poor dynamical regime and must spend many distillation tokens repairing initialization rather than learning the remaining teacher behavior. We propose Taylor-Calibrate, a lightweight initialization method for hybrid GDN students. The method uses Taylor-guided teacher attention statistics to set the value projection, memory timescale, write gates, and output gate, then applies a short per-layer alignment step to match each converted layer to the teacher output. Across four teacher settings and three retained-layer policies, Taylor-Calibrate gives substantially stronger zero-shot students, with up to an 88x improvement in a representative ablation, and reaches matched recovery targets with 4.9x--9.2x fewer training tokens than naive conversion.
### Title:
          NeuronFabric: A Software Reference Architecture for On-Chip Transformer Training with Local Adam
 - **Authors:** Evgeny Ukladchikov
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Publicly documented accelerator architectures generally separate training computation from optimizer-state updates or rely on external memory and host orchestration. This paper presents NeuronFabric, a software reference architecture intended for future FPGA and ASIC implementations of transformer training with local Adam updates. A complete C# prototype implements forward pass, backpropagation, and Adam optimization without external machine-learning frameworks. The goal is to validate numerical correctness and memory requirements before hardware implementation. The evaluated model is a 334K-parameter autoregressive transformer (d=88, H=4, f=264, L=4, vocab=256) trained on the Shakespeare corpus. The BF16W configuration achieves evaluation loss 1.5426 after 80K samples, compared with 1.5224 for an FP32 GPU reference, while producing coherent character-level text. The paper introduces BF16W, which stores weights in BF16 while retaining Adam optimizer moments in FP32. This reduces memory requirements for on-chip training. A 334K-parameter FP32 model with Adam moments requires approximately 4.0 MB, matching the BRAM capacity of a Xilinx ZCU102 device. The BF16W variant requires approximately 3.34 MB, leaving memory available for activation storage. We describe the vocabulary-budget constraint observed during earlier experiments, quantify BF16W memory savings, and outline FPGA training as the next stage of development. No FPGA measurements are included in this paper. This publication serves as a public architectural disclosure and software reference implementation for future FPGA and ASIC exploration of the NeuronFabric architecture.
### Title:
          Privacy from Symmetry: Orthogonally Equivariant Transformers for LLM Inference
 - **Authors:** Alexander Yukhimchuk, Andrey Shulga, Mladen Kolar, Martin Takáč
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Running large language models locally is often impractical, pushing inference on sensitive text to third-party providers. Split inference partially mitigates this by keeping tokens on the client and sending only hidden representations, but these representations can still be recovered via nearest-neighbor search against the public embedding table. We propose an orthogonal obfuscation procedure in which the client multiplies embeddings by a secret orthogonal matrix before transmission. To enable correct inference under arbitrary rotations, we introduce ConjFormer, a transformer variant that is exactly $\mathrm{O}(d)$-equivariant via a lightweight normalization change (scalar RMSNorm) together with blockwise orthogonal conjugation of all linear weights. As a result, the server performs the full forward pass entirely in the rotated basis and never observes unrotated hidden states. Experiments on GPT-2 and Llama 3.2 1B models fine-tuned on PubMed show that orthogonal obfuscation eliminates direct cosine nearest-neighbor inversion and reduces token recovery from over 35% top-10 to at most 1.3%, while increasing perplexity by only 0.4% after fine-tuning. These results indicate that enforcing symmetry at the architectural level can provide a practical defense for privacy-preserving LLM inference without noise injection or heavy cryptographic machinery.
### Title:
          MVOFormer: Flow-Semantic Transformer for Robust Monocular Visual Odometry
 - **Authors:** Jituo Li, Shunwang Sun, Jialu Zhang, Xinqi Liu, Jinyao Hu, Zhicheng Lu, Sajad Saeedi, Guodong Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular visual odometry (MVO) is foundational to autonomous navigation and robotic localization. However, existing learning-based MVO approaches often struggle with either a lack of interpretable, complementary features or overly complex multi-stage architectures. These limitations inherently restrict their robustness and cross-domain generalization. In this work, we propose MVOFormer, a novel transformer framework for robust monocular visual odometry. Our architecture features a Flow-Semantic Dual Branch Encoder that synergizes dense geometric motion cues with object-centric semantic priors, explicitly distinguishing static structures from dynamic distractors. These representations are then fused by an Iterative Multimodal Decoder, enabling coarse-to-fine pose refinement while dynamically suppressing attention on unreliable regions. Extensive evaluations demonstrate that, without any target-domain fine-tuning, MVOFormer achieves superior zero-shot generalization and robustness, significantly outperforming prior learning-based frame-to-frame methods across diverse benchmarks including TartanAir, KITTI, TUM-RGBD, and ETH3D-SLAM.
### Title:
          Uncertainty Quality of VGGT: An Analysis on the DTU Benchmark Dataset
 - **Authors:** Markus Hillemann, Robert Langendörfer, Steven Landgraf, Markus Ulrich
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual Geometry Grounded Transformer (VGGT) has already attracted a great deal of attention in a short period of time, not least due to the Best Paper Award at CVPR-2025. Similar to DUSt3R and MASt3R, VGGT aims to bring about a paradigm shift by replacing established methods like bundle adjustment and feature matching with a simple, unified, feed-forward neural network that predicts camera poses, depth maps, and dense 3D structure directly from multiple images of a scene in a few seconds. A key aspect is its ability to process an arbitrary number of views consistently in a single forward pass without any post-processing or iterative optimization. For photogrammetry, this opens new possibilities for real-time, scalable, and accessible 3D reconstruction. In this context, not only high reconstruction accuracy but also high-quality uncertainty estimates are crucial, as they foster trust and enable robust quality assurance. This paper therefore investigates the quality of VGGT's uncertainty predictions. The analysis identifies an effective confidence threshold for filtering VGGT's raw output and demonstrates that enhancing uncertainty quality holds strong potential for improving the accuracy of its 3D reconstructions.
### Title:
          ROSA-RL: Uncertainty-Aware Roundabout Optimized Speed Advisory with Reinforcement Learning
 - **Authors:** Anna-Lena Schlamp, Jeremias Gerner, Klaus Bogenberger, Werner Huber, Stefanie Schmidtner
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Roundabouts challenge automated driving in mixed traffic, as heterogeneous and non-deterministic human behavior, unknown driving intentions, and high interaction complexity create uncertainty about whether the conflict zone will be blocked or available at the moment of entry. We present ROSA-RL -- uncertainty-aware Roundabout Optimized Speed Advisory with Reinforcement Learning. It enables safe and efficient roundabout entry for automated and human-driven vehicles in mixed traffic through probabilistic conflict forecasting. A Transformer-based model predicts conflict zone occupancy over a five-second horizon, capturing multi-agent interactions to anticipate upcoming conflicts and available gaps. The prediction outputs encode uncertainty in future motion and intent, and augment the state of a classical RL framework, enabling uncertainty-aware speed coordination. Evaluated in simulations grounded in real-world data, ROSA-RL can effectively handle uncertainty and outperform a comparable model-based baseline, closing the gap to an ideal setting assuming fully known occupancy while improving traffic efficiency and safety. The source code of this work is available under: this http URL.
### Title:
          The BD-LSC Dataset: Facilitating the Benchmarking of Models for Lexical Semantic Change Detection in Slang and Standard Usage
 - **Authors:** Afnan Aloraini, Viktor Schlegel, Goran Nenadic, Riza Batista-Navarro
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic semantic change detection aims to identify how word meanings shift over time, offering insights into both linguistic and societal change. Despite recent progress in computational lexical semantic change (LSC), existing benchmarks and methods struggle to capture bi-directional semantic change, particularly cases where words simultaneously gain and lose senses. This problem is especially challenging for words that have both slang and standard meanings. To address these gaps, we introduce two complementary benchmark datasets. The Bi-Directional Lexical Semantic Change (BD-LSC) dataset captures sense gain, sense loss, and stability across three time periods, enabling the study of complex semantic trajectories. The SlangTrack Word Sense Disambiguation (ST-WSD) dataset provides fine-grained, instance-level sense annotations for words combining slang and standard usages, supporting systematic benchmarking of WSD and semantic change detection models. Using these benchmarks, we systematically evaluate models across different methodological families: unsupervised clustering using contextualised embeddings, supervised machine learning, transformer-based models, and state-of-the-art large language models. Among the evaluated systems, the few-shot GPT-4o model achieved the strongest aggregate performance on Exact Sense Match (ESM) and multi-label accuracy; however, Macro-F1 scores near 0.5 across all systems show that rare slang senses remain difficult, which we identify as the central open challenge.
### Title:
          MVM-IOD: An Industrial Object-Centric Benchmark Dataset for the Evaluation of 3D Reconstruction Methods
 - **Authors:** Robert Langendörfer, Markus Hillemann, Markus Ulrich
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D object reconstruction, and camera pose estimation in industrial applications are challenging tasks, as errors are costly while the computation time is often limited. The complexity of typical industrial objects further complicates these tasks. Most of the existing datasets in this context do not depict realistic industrial scenarios. Therefore, we introduce the Machine Vision Metrology Industrial Object Dataset (MVM-IOD). Images of typical industrial objects are captured systematically, by moving a camera, mounted at the end effector of an industrial robot arm, on a hemisphere around the objects. MVM-IOD contains reference camera poses and reference 3D point clouds, the acquired RGB images of 9 objects and 2 background choices resulting in 18 scenes, which allows evaluation of all image based methods that compute a 3D reconstruction, camera poses, or novel views of a scene. Based on MVM-IOD, we extensively evaluate current SOTA 3D reconstruction and camera pose estimation methods, such as Structure from Motion, Multi-View Stereo, recent feed forward methods (Visual Geometry Grounded Transformer, {\pi}3), and 2D Gaussian Splatting and report our findings as a baseline for future research. The experiments show that capture setups like ours generate out-of distribution images for feed forward methods, leading to suboptimal point clouds and camera poses. However, these out-of-distribution images can be shifted closer to the training distribution by applying simple preprocessing steps. Consequently, in certain industrial applications, feed forward methods should be used with caution.
### Title:
          MMDiff: Extending Diffusion Transformers for Multi-Modal Generation
 - **Authors:** Yagmur Akarken, Orest Kupyn, Christian Rupprecht
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion transformers have demonstrated remarkable generative capabilities, yet the rich perceptual representations computed across their denoising trajectory are discarded once the content is rendered. We present MMDiff, a framework that transforms a frozen diffusion transformer into a multi-modal generative system that jointly produces images alongside any combination of dense perceptual modalities using lightweight decoder heads. Our central finding is that perceptual information is temporally distributed along the denoising trajectory, and that multi-timestep feature fusion with spatially varying aggregation weights is essential, improving semantic segmentation results by up to 28.7% mIoU over single-timestep extraction. We further adopt concept-driven attention extraction for interpretable spatial guidance, and show that frozen diffusion features are competitive with and complementary to state-of-the-art encoders such as DINOv3. By training only lightweight decoder heads on a frozen backbone, we achieve strong performance in semantic segmentation, salient object detection, and depth estimation, and demonstrate that this framework enables effective synthetic data generation at scale.
### Title:
          Adaptive inference and function vectors in deep transformers
 - **Authors:** Ravin Raj, Gautam Reddy
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Applied Physics (physics.app-ph); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers are widely used as a general-purpose substrate for learning complex correlations between a large collection of coupled variables, but their internal mechanisms have remained mysterious. We introduce a theory of a deep transformer as a mean-field interacting system that implements distributed inference, subject to constraints on communication, locality and depth. We show that such a system can exploit internal state representations ('function vectors') to infer a latent context variable at increasingly finer scales over its layers. In an in-context regression task, the theory predicts a non-trivial relationship between non-Gaussian, hierarchical structure in the latent context variable, and transformer depth. Predictions are tested using constrained linear attention transformers and demonstrate adaptive inference in deep architectures. Feedforward blocks and depth enable transformers to implement a much richer class of in-context learning algorithms than previously described.
### Title:
          Taming Curvature: Architecture Warm-Up for Stable Transformer Training
 - **Authors:** Sameera Ramasinghe, Ajanthan Thalaiyasingam, Hadi Mohaghegh Dolatabadi, Chamin Hewa Koneputugodage, Gil Avraham, Violetta Shevchenko, Yan Zuo, Karol Pajak, Alexander Long
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training billion-parameter Transformers is often brittle, with transient loss spikes and divergence that waste compute. Even though the recently developed Edge of Stability (EoS) theory provides a powerful tool to understand and control the stability of optimization methods via the (preconditioned) curvature, these curvature-controlling methods are not popular in large-scale Transformer training due to the complexity of curvature estimation. To this end, we first introduce a fast online estimator of the largest (preconditioned) Hessian eigenvalue (i.e., curvature) based on a warm-started variant for power iteration with Hessian-vector products. We show theoretically, and verify empirically, that the proposed method makes per-iteration curvature tracking feasible at billion parameter scale while being more accurate. Using this tool, we find that training instabilities coincide with surges in preconditioned curvature and that curvature grows with depth. Motivated by these observations, we propose architecture warm-up: progressively growing network depth to carefully control the preconditioned Hessian and stabilize training. Experiments on large Transformers validate that our approach enables efficient curvature tracking and reduces instabilities compared to existing state-of-the-art stabilization techniques without slowing down convergence.
### Title:
          Tying the Loop -- Tied Expert Layers in Mixture-of-Experts Language Models
 - **Authors:** Martin Jaggi
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mixture-of-Experts (MoE) architectures efficiently scale Large Language Models (LLMs) by activating only a small fraction of their experts per token, yet the full parameter count - dominated by the expert parameters - must be held in training and inference memory. To address this, we introduce Expert Tying, an architectural modification that shares expert parameters across consecutive transformer layers while preserving independent, layer-wise routing and attention. We evaluate this approach across common, state-of-the-art architectures, including OLMoE, Qwen3, and DeepSeek-style MoEs. Our pretraining experiments demonstrate that tying experts can reduce memory footprint by almost 2x at virtually no degradation in perplexity or downstream quality. By exploiting the parameter redundancy inherent in MoE pathways, our method provides a highly favorable compute-to-memory trade-off, advancing efficient training and scaling of next-generation LLMs.
### Title:
          Does Traversal Order Matter? A Systematic Study of Tree Traversal Methods in Transformer Grammars
 - **Authors:** Zongru Liu, Pengyu Ji, Pengcheng Wang, Kewei Tu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer Grammars (TGs) enhance language modeling by incorporating syntactic tree structures. Despite the potentially significant impact on model performance of how syntactic trees are linearized in TGs, existing studies rely solely on Depth-First Traversal (DFT) for linearization. In this paper, we expand the traversal design space by exploring Breadth-First Traversal (BFT) and a novel hybrid traversal strategy, Production-Rule Traversal (PRT), which combines the structural lookahead of BFT with the early lexical generation of DFT. We integrate these traversal methods with varying tree configurations and masking strategies, and empirically evaluate their performance on language modeling, syntactic generalization and summarization. We reveal the inherent trade-offs between nested composition and global lookahead, providing actionable recommendations for designing task-aware Transformer Grammars.
### Title:
          OneRank: Unified Transformer-Native Ranking Architecture for Multi-Task Recommendation
 - **Authors:** Jiakai Tang, Sunhao Dai, Kun Wang, Zhiluohan Guo, Yu Zhao, Cong Fu, Kangle Wu, Yabo Ni, Anxiang Zeng, Xu Chen, Jun Xu
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-task learning (MTL) is essential in recommender systems to enable complementary learning among diverse user feedback. While modern industrial practices have shifted from DNNs to Transformer-centric architectures to strengthen sequence modeling and scaling capacity, they still decouple feature encoding from multi-task prediction, treating the Transformer as a task-agnostic encoder. This design fundamentally limits the performance and scalability by (1) creating an information bottleneck under heterogeneous task objectives, (2) inducing gradient interference that leads to the seesaw phenomenon, and (3) forcing a dataflow transition in which attention-based, context-adaptive representation learning is converted to static feed-forward task prediction with incompatible information read-write dynamics. We propose OneRank, a Transformer-native multi-task ranking framework that eliminates encoder-predictor separation and introduces task-private channels for forward representation learning and backward optimization, enabling task-specialized learning while reducing inter-task interference. In the forward pass, OneRank learns task-specific representations bottom-up through task-conditioned information selection, candidate-aware contextualization, and controlled cross-task interaction. In the backward pass, cross-task gradient detachment isolates task-private parameter updates from shared knowledge extraction modules, preventing negative transfer. We further replace static task-specific MLP scorers with dynamic matching-based scoring for context-aware personalized ranking. By internalizing multi-task reasoning within the Transformer stack, OneRank establishes a unified and scalable architectural paradigm. Offline and online experiments on large-scale industrial datasets show that OneRank significantly outperforms state-of-the-art baselines while maintaining computational efficiency.
### Title:
          Data-Driven Decoding of Russell's Circumplex Model of Affect
 - **Authors:** Amdjed Belaref, Samir Sadok, Zineb Noumir, Renaud Seguier
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Affective computing increasingly relies on deep learning to represent emotions, yet latent spaces often remain opaque, high-dimensional black boxes. This paper investigates whether Transformers' embeddings recover the geometric regularities of Russell's circumplex model. We unify two complementary experiments testing the hypothesis that, after training models on text and speech, their resulting latent spaces encode a topology consistent with valence-arousal and reproduce human-like neighborhood relations. Specifically, we evaluate deep representations extracted from Transformer-based text (RoBERTa) and speech (wav2vec 2.0) encoders, along with a multimodal Transformer fusion architecture, across naturalistic datasets like MSP-Podcast and controlled LLM-generated stimuli. Our analysis reveals that multimodal fusion of text and audio yields perfect topological alignment with Russell's primary emotion ordering. Furthermore, in a zero-shot setting using generic text embeddings, projected fine-grained emotion terms fall close to their established human-mapped coordinates. Our contribution is a novel, data-driven framework for validating emotion models, demonstrating that Russell's circumplex structure is intrinsically encoded in the embeddings of these modalities rather than being solely an artifact of human labeling, thereby bridging the gap between psychological theory and representation learning.
### Title:
          Robust Dual-Signal Fusion: Hybrid Neuro-Symbolic Gating with Compressed Chain-of-Thought Refinement for Irony Detection in Social Media Texts
 - **Authors:** Ankit Bhattacharjee, Krityapriya Bhaumik
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) natively default to literal semantic interpretations, making zero-shot irony detection a persistent challenge. We introduce the Robust Dual-Signal (RDS) Fusion framework, a hybrid neuro-symbolic architecture that compresses Chain-of-Thought (CoT) reasoning trajectories without Supervised Fine-Tuning (SFT). Evaluated on a strictly held-out TweetEval test set (N=734), RDS achieves 78.1% accuracy and a Macro F1 of 0.777, matching the absolute performance ceiling of the fine-tuned BERTweet. On the heavily imbalanced iSarcasm dataset, the frozen CoT pipeline filters 22.5% of out-of-distribution hallucinations, yielding a zero-shot Macro F1 of 0.6726 and Ironic F1 of 0.4821, outperforming multiple heavily supervised SemEval transformer ensembles. A statistical ablation confirms this structural synergy: adding the symbolic prior to the neural baseline yields no significant gain (p = 0.242), and the marginal benefit of adding the CoT pipeline to that prior is heavily compressed (p = 0.149). Only the complete, concurrent fusion of all three signals achieves a statistically validated improvement over the baseline (p = 0.005).
### Title:
          Compositional Reasoning Depth Predicts Clinical AI Failure: Empirical Evidence Consistent with Transformer Compositionality Limits in Electronic Health Record Question Answering
 - **Authors:** Sanjay Basu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Aggregate accuracy benchmarks conceal a systematic structure in how large language models fail at electronic health record (EHR) question answering: questions requiring more inferential steps produce disproportionately more errors. Motivated by theoretical results on transformer compositionality limits, we introduce a pre-specified hop-count taxonomy -- the number of distinct reasoning steps required to answer a clinical question from an EHR -- as a principled predictor of model failure. We annotate 313 clinician-generated MedAlign EHR question-answer pairs across four hop levels and evaluate 301 questions in a within-model ablation (claude-sonnet-4-6, zero-shot vs. extended thinking) and cross-architecture replications (gpt-4o and gpt-5.4-2026-03-05, zero-shot). All three models, spanning two providers and two OpenAI generations (GPT-4 and GPT-5), show monotone accuracy decline with hop count: Claude Sonnet zero-shot falls from 30.6% (hop=1) to 17.6% (hop=4) (Cochran-Armitage z=-2.30, p=0.011; OR per hop 0.72, 95% CI [0.56,0.92], p=0.008); GPT-4o replicates this (37.8% to 14.7%; OR 0.58 [0.45,0.75], p<0.001); and gpt-5.4-2026-03-05 confirms it (37.8% to 23.5%; OR 0.80 [0.66,0.98], p=0.027). A pre-specified context-sufficiency audit shows higher-hop questions are not differentially disadvantaged by EHR truncation (answerability 93-95% at hops 2-4 vs. 79% at hop=1), so the decline reflects compositional reasoning difficulty. Extended thinking did not significantly flatten the accuracy-depth curve across three reasoning conditions, and thinking-token usage scaled with hop count (r=0.31, p<0.0001), consistent with the predicted O(k) computational requirement. Hop count is thus a theory-motivated, cross-architecture predictor of large-language-model error on EHR question answering, with direct implications for deployment risk stratification of clinical AI.
### Title:
          LESS Is More: Mutual-Stability Sampling for Diffusion Language Models
 - **Authors:** Amr Mohamed, Guokan Shang, Michalis Vazirgiannis
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion large language models (dLLMs) offer a promising alternative to autoregressive decoding by iteratively refining masked sequences, enabling parallel token updates and bidirectional conditioning. Their practical efficiency, however, is limited by sampling procedures that execute a fixed number of reverse denoising steps selected before decoding, spending computation on already-stable positions and sometimes committing unstable ones too early. We present \textsc{LESS}, a training-free, model-agnostic adaptive sampler that treats token commitment as an online stopping problem. \textsc{LESS} implements mutual-stability sampling through a joint stability rule that makes a masked position eligible for unmasking only when its top-1 prediction has high confidence, its top-1 token persists across recent reverse steps, and its predictive distribution is stable under top-$K$ inter-step Jensen--Shannon divergence. We evaluate \textsc{LESS} on Dream-7B, LLaDA-8B, and LLaDA-1.5-8B, covering full-sequence diffusion and semi-autoregressive blockwise sampling regimes, across seven benchmarks spanning general knowledge, math, and code. \textsc{LESS} improves average accuracy over strong training-free adaptive samplers while using $72.1\%$ fewer reverse steps than fixed-budget decoding. Since each reverse step requires a Transformer forward pass, these step-count reductions translate into fewer forward evaluations, lower measured wall-clock latency, and lower estimated inference compute.
### Title:
          HAMON: Passive Optical Sequence Mixing for Long-Horizon Forecasting
 - **Authors:** Alper Yıldırım
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simple linear and frequency-domain models remain surprisingly competitive in long-horizon time-series forecasting, and recent mechanistic evidence suggests that standard forecasting benchmarks may not require the dense superposed representations that make transformers powerful in other domains. This raises a substrate-level question: if the core forecasting operator is often low-complexity and approximately linear, does it need to be implemented as learned digital temporal mixing? We introduce HAMON, a passive diffractive optical forecasting core in which historical values are encoded onto an optical aperture, future positions are left dark, and cascaded trainable phase masks with free-space diffraction shape the forecast directly in the output field. At inference, prediction is performed by a single passive optical propagation pass with no trainable digital sequence-mixing layer. Across standard benchmarks, HAMON outperforms the strongest digital baselines considered on ETTm2 at all horizons and on ETTh2 at all but the longest horizon, improving MSE by up to 14\% and doing so consistently across horizons rather than at isolated points. It is competitive on Weather and trails the strongest baselines on the remaining ETT settings and on the high-channel-count Traffic and Electricity datasets. Phase encoding, intensity-compatible readout, and phase-scrambling ablations, together with a TorchOptics cross-simulator check, indicate that the forecasts arise from the data-bearing optical field rather than from a digital forecasting head. Because the passive core uses standard Fourier optics, HAMON defines a concrete target for optical hardware and for passive physical sequence mixing.
### Title:
          Qwen-RobotWorld Technical Report: Unifying Embodied World Modeling through Language-Conditioned Video Generation
 - **Authors:** Jie Zhang, Xiaoyue Chen, Anzhe Chen, Chenxu Lv, Deqing Li, Gengze Zhou, Hang Yin, Haoqi Yuan, Haoyang Li, Jiahao Li, Jiazhao Zhang, Jingren Zhou, Kaiyuan Gao, Kun Yan, Lihan Jiang, Ningyuan Tang, Pei Lin, Qihang Peng, Shengming Yin, Tianhe Wu, Tianyi Yan, Xiao Xu, Yan Shu, Yanran Zhang, Ye Wang, Yi Wang, Yilei Chen, Yixian Xu, Yiyang Huang, Yuxiang Chen, Zekai Zhang, Zhendong Wang, Zhixing Lei, Zhixuan Liang, Zihao Liu, Zikai Zhou, Xiong-Hui Chen, Chenfei Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Qwen-RobotWorld, a language-conditioned video world model for embodied intelligence. With natural language as a unified action interface, it predicts physically grounded future visual trajectories from current observations across robotic manipulation, autonomous driving, indoor navigation, and human-to-robot transfer. This unified formulation provides three promising application directions: synthetic data generation for policy training augmentation, scalable virtual environments for policy evaluation, and language-guided planning signals for downstream robot control. This is achieved through a three-part design: a) Double-Stream MMDiT with MLLM Action Encoding, where a 60-layer double-stream diffusion transformer couples frozen Qwen2.5-VL semantics with video-VAE latents through layer-wise joint attention; b) Embodied World Knowledge (EWK), an 8.6M video-text corpus (200M+ frames) with action-language mapping over 20+ embodiments and 500+ action categories; and c) General+Expert Progressive Curriculum, a two-stage training strategy that first learns general visual priors and then injects embodied specialization under a shared language interface. Extensive results show strong competitiveness: ranks 1st overall on EWMBench and DreamGen Bench, outperforms all open-source models on WorldModelBench and PBench. Additional zero-shot analyses on RoboTwin-IF benchmark further support robust generalization and multi-view consistency.
### Title:
          T-Rex: Tactile-Reactive Dexterous Manipulation
 - **Authors:** Dantong Niu, Zhuoyang Liu, Zekai Wang, Boning Shao, Zhao-Heng Yin, Anirudh Pai, Yuvan Sharma, Stefano Saravalle, Ruijie Zheng, Jing Wang, Ryan Punamiya, Mengda Xu, Yuqi Xie, Yunfan Jiang, Letian Fu, Konstantinos Kallidromitis, Matteo Gioia, Junyi Zhang, Jiaxin Ge, Haiwen Feng, Fabio Galasso, Wei Zhan, David M. Chan, Yutong Bai, Roei Herzig, Jiahui Lei, Fei-Fei Li, Ken Goldberg, Jitendra Malik, Pieter Abbeel, Yuke Zhu, Danfei Xu, Jim (Linxi)Fan, Trevor Darrell
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The ability to react dynamically to tactile signals has long been considered crucial to agile human-level dexterity. Yet contemporary learning-based Vision-Language-Action (VLA) models for robotic manipulation generally either overlook the tactile modality or are limited to encoders with static cues, due in part to the scarcity of diverse training data and standardized evaluation, architectural constraints in current VLA models, and limitations of static tactile encoders. In this paper, we push the frontier of tactile-reactive manipulation by addressing all of these limitations. We propose a large-scale, 100-hour tactile-rich dataset collected via a novel, data-efficient recipe that prioritizes elementary motor primitives. To effectively exploit naturally high-frequency touch signals without sacrificing the existing capabilities of existing VLAs, we introduce a variable-rate Mixture-of-Transformers (MoT) architecture equipped with a novel temporal tactile VQ-VAE encoder. We demonstrate the effectiveness of tactile-reactive policies on 12 manipulation tasks requiring delicate force control and deformable object manipulation, achieving over 30% higher average success rate than the strongest baseline.
## Keyword: autonomous driving
### Title:
          A Comparative Study of Graph Neural Network Layer Selection for Interaction Modelling in Driving Trajectory Prediction
 - **Authors:** George Daoud, Mohamed El-Darieby
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving systems rely on precise trajectory prediction to plan safe and efficient movement. Graph Neural Networks (GNNs) have become a promising approach for modelling spatiotemporal interactions among road agents. However, designing GNN architectures for trajectory prediction remains non-standardized, with little guidance on which graph layers effectively capture spatial interactions and temporal dynamics. This paper offers a detailed comparative study of 19 graph layer types, focusing on their spatial and temporal processing capabilities to discover the most effective architectures for trajectory prediction. Within the explored hyperparameter setting, we highlight five standout layer combinations, with ARMA, Chebyshev, and topology-aware layers consistently performing better than others. Beyond performance metrics, our findings yield practical design principles: sum-based aggregation is more effective than mean-based methods, multi-head attention mechanisms enable richer interactions, and assigning different weights to different hop distances significantly improves prediction accuracy. These findings offer useful guidance for designing more interpretable and effective trajectory prediction models.
### Title:
          KATANA: A Fast, Low-Power Mapping of Kalman Filters onto Edge NPUs for Real-Time Tracking
 - **Authors:** Bodhisatwa Kundu, Anish Rooj, Sumit Saha, Abhradeep Sarkar, Arghadip Das, Arnab Raha, Mrinal K. Naskar
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State estimation is the closed-loop core of every real-time tracking system, from radar surveillance and counter-UAV defense to autonomous driving and robotics. These deployments run on edge platforms, where defense systems mount on vehicles and drones, and civilian pipelines live on cars and handheld devices. Here, every additional watt of compute erodes mission duration or operational range. Two hard constraints follow: each new measurement must be fused before the next control cycle, and the total compute must fit within a strict battery and thermal power envelope. The Linear and Extended Kalman Filters (LKF, EKF) are dominant estimators on these systems, but today they execute almost exclusively on CPUs, which serialize multi-object tracking (MOT) updates, or on custom FPGA/ASIC accelerators that lengthen design cycles. Contemporary AI-PC SoCs, like the Intel Core Ultra Series 1 and 2, integrate a low-power, data-parallel Neural Processing Unit (NPU). We therefore ask whether the Kalman filter can be mapped onto this existing matrix engine to meet real-time and low-power budgets simultaneously, avoiding a dedicated accelerator and keeping the CPU and GPU free for primary workloads. We present KATANA, an NPU-aware optimization framework delivering the first end-to-end mapping of the LKF and EKF onto a commercial NPU, alongside a cross-platform characterization on shipping AI-PC silicon. KATANA applies three algebraic graph rewrites: subtract-to-add reformulation via a precomputed negative-projection matrix H_neg, static-shape tensor fusion, and block-diagonal batched parallelization, ensuring 100% of operations execute on the DPU matrix engine. On the Series 2, the optimized batched EKF reaches 223.35 FPS at 13.43 W active power, and the LKF reaches 408.73 FPS at 14.05 W, delivering up to a 97.9% reduction in dynamic energy versus the CPU implementation.
### Title:
          Adaptive Deep Koopman Operator for Vehicle Dynamics Modeling: A Physics-Informed and Tire-Force-Driven Approach
 - **Authors:** Wenjie Wang, Hao Chen, Ran Shu, Solyeon Kwon, Kyoungseok Han, Hongyu Shu
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate and adaptive modeling of vehicle dynamics is paramount for the safety of autonomous driving systems, particularly under extreme maneuvers and time-varying parameters. While Deep Koopman operator theory offers a promising global linearization framework, its online application faces a theoretical bottleneck: the high-dimensional lifted state space inherently induces a rank-deficient problem, rendering traditional recursive least squares based updates numerically unstable. To address this, we propose a novel tire-force-driven modeling framework with guaranteed online stability. First, an offline Deep Koopman model is constructed by embedding 7DOF dynamic equilibrium constraints into the learning objective, ensuring the structural fidelity and physical interpretability of the lifted manifold. Second, we theoretically reformulate the operator update in the rank-deficient space as a minimum-norm solution problem. A Physics-Informed Variable Step-Size Normalized Least Mean Squares (PI-VSS-NLMS) algorithm is proposed, which leverages the projection property of NLMS to act as a stable pseudo-inverse solver while incorporating an anchoring mechanism to suppress parameter drift. Extensive simulations on CarSim and Hardware-in-the-Loop validation on dSPACE MicroAutobox III confirm the superiority of the proposed algorithm. It achieves robust prediction accuracy under unseen excitations while guaranteeing real-time feasibility with an average execution time of 0.421 ms, thus bridging the gap between theoretical models and practical deployment.
### Title:
          Self-Driving Negotiator: An interactive, verifiable benchmark for social negotiation and theory of mind under hidden intent
 - **Authors:** Ashutosh Kumar
 - **Subjects:** Subjects:
Computer Science and Game Theory (cs.GT); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving is full of tiny social negotiations: a driver presses forward, another yields, a pedestrian fakes toward the curb, or a lane vehicle chooses whether to open a merge gap. Such interactions require inferring hidden intent from behavior under partial observability and then acting safely and efficiently. Existing autonomous-driving language benchmarks mostly focus on perception, visual question answering, or open-loop planning, while existing language-agent negotiation benchmarks typically make the negotiation explicit in text. Self-Driving Negotiator bridges the gap between the two: a text-only, multi-turn, procedurally generated environment for measuring implicit social coordination in driving. Agents generate specific driving actions. Reward and diagnostics are computed from the privileged simulator state, not from the explanation of the model. This report covers task design, reward and anti-gaming invariants, validated scenarios, non-LLM baselines, and a six-model inference leaderboard. Current models are far removed from the scripted expert. The best average success rate across three scenarios is 0.68; contested merge is statistically flat across models; and difficulty tiers separate cue-following from true wait-for-commitment behavior.
### Title:
          CausalDrive: Real-time Causal World Models for Autonomous Driving
 - **Authors:** Tianyi Yan, Huan Zheng, Dubing Chen, Meizhi Qu, Yingying Shen, Lijun Zhou, Mingfei Tu, Bing Wang, Guang Chen, Hangjun Ye, Haiyang Sun, Cheng-zhong Xu, Jianbing Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models have emerged as a promising paradigm for scaling autonomous driving (AD) data, yet existing video generative models fall short as interactive simulators. Layout-conditioned renderers rely on "oracle" future trajectories of all background agents, rendering them strictly non-reactive. Conversely, pure action-conditioned predictors lack semantic control over complex interactions and suffer from prohibitive diffusion latencies, hindering closed-loop policy learning. To bridge this gap, we present CausalDrive, a controllable, real-time foundation driving world renderer. CausalDrive operates solely on the initial front-view frame, the ego-vehicle's trajectory, and a macroscopic text prompt. By excluding future NPC layouts, we compel the model to intrinsically predict causal interactions, enabling text-driven control over Driving Sociology, allowing users to dynamically orchestrate diverse counterfactual reactions to identical ego-actions. To overcome the efficiency bottleneck and address the covariate shift in autoregressive generation, we propose a novel Context-Forced DMD architecture. This combines continuous flow-matching with a self-correcting distillation objective, achieving interactive speeds of 12 FPS. This breakthrough transforms the passive video generator into a playable neural simulator. We demonstrate its versatility across three downstream applications: (1) generative closed-loop evaluation with significantly mitigated collision artifacts, (2) large-scale Reinforcement Learning (RL) post-training driven by a Video2Reward module, and (3) real-time human-in-the-loop simulation. Extensive experiments validate that policies trained within CausalDrive's reactive scenarios exhibit superior interaction capabilities in the real world.
### Title:
          Metis: A Generalizable and Efficient World-Action Model for Autonomous Driving and Urban Navigation
 - **Authors:** Jingyu Li, Zhe Liu, Dongnan Hu, Junjie Wu, Zipei Ma, Wenxiao Wu, Chao Han, Zhihui Hao, Zhikang Liu, Kun Zhan, Jiankang Deng, Xiatian Zhu, Li Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World action models~(WAMs) have shown great promise for autonomous driving and urban navigation. Built upon Vision-Language-Action models or video generation models, existing approaches suffer key limitations: (1) High inference latency due to future observation prediction at test time, and (2) tightly coupled video and action modeling leading to representational mismatch and degraded generalization. To address both issues, we propose Metis, an end-to-end WAM framework that decouples video generation and action prediction. Specifically, Metis employs a Mixture-of-Transformers architecture with dedicated experts for video generation and action prediction, preserving the intrinsic distributional properties of each task. To enhance efficiency, we introduce an asymmetric attention mask that enables joint training of both experts while allowing the action model to bypass explicit video generation during inference. This design ensures training-inference consistency and significantly reduces computational costs without compromising planning performance. Extensive experiments demonstrate state-of-the-art performance on the NAVSIM navhard and navtest benchmarks and the CityWalker navigation benchmark, validating both the generalizability and efficiency across diverse tasks. Real-robot deployments further confirm the practical feasibility of our approach.
### Title:
          ControlMap: Controllable High-Definition Map Generation for Traffic Scenario Simulation
 - **Authors:** Marwan Farag, Steffen Wäldele, Yu Yao
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Simulation is central to validating autonomous driving systems, yet current pipelines are limited by insufficient scenario diversity due to costly High Definition (HD) map creation. Scaling HD maps requires expensive data collection and manual processing. Moreover, existing generative models lack the fine-grained control necessary to target specific road topologies during generation. This paper presents a data-driven pipeline for controllable HD map generation using latent diffusion and ControlNet for spatial conditioning. To our knowledge, we are the first to inject spatial guidance signals into a diffusion model for HD map synthesis. Furthermore, our model supports adjustable conditioning strength through classifier-free guidance and city-level style transfer via city label conditioning. To complement existing metrics, we introduce two novel metrics to evaluate adherence to the control signal and similarity to ground-truth maps. Experiments demonstrate that our model generates realistic HD maps that faithfully follow input road topologies while accurately preserving city-specific details.
### Title:
          PointDiffusion: Diffusion-Based Scene Completion in the Point Cloud Domain
 - **Authors:** Chidera Agbasiere, Mikhail Sannikov, Faith Ogunwoye, Erik Shaikhiev, Alex Kozinov, Ilya Mikhalchuk, Iana Zhura, Dzmitry Tsetserukou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing dense 3D scenes from sparse LiDAR point clouds is a fundamental challenge in autonomous driving, where latent diffusion models offer a promising solution. However, existing approaches rely on object-level autoencoders that collapse into unstable global representations at outdoor scale and suffer from ground truth data corrupted by odometry drift that systematically degrades supervision quality. Furthermore, multi-step diffusion inference incurs prohibitive latency for real-time deployment. We propose a novel multi-token Gaussian VAE with cross-attention pooling for stable scene-scale LiDAR compression, combined with an anchor-based ICP ground truth refinement pipeline that eliminates drift-induced noise from training supervision. Together, these components enable a scaffold-free single-step diffusion completion model that achieves an approximately 16x reduction in squared Chamfer distance on SemanticKITTI seq. 08 (0.396 m^2 to 0.024 m^2), surpasses LiDiff and ScoreLiDAR by 17-19% and 10-11%, respectively, and operates at 25-143x lower inference latency. Our results demonstrate that data quality dominates model design in this regime and that multi-token latent spaces provide a stable first stage for latent diffusion-based scene completion.
### Title:
          GraphWorld: Long-Horizon Planning with World Models for End-to-End Autonomous Driving
 - **Authors:** Ziying Song, Caiyan Jia, Lin Liu, Lei Yang, Shengkai Zhang, Feiyang Jia, Fengda Zhao, Peiliang Wu, Shaoqing Xu, Chen Lv, Yadan Luo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving has made significant progress by unifying perception, prediction, and planning within a single learning framework, achieving strong performance in short-horizon decision making. However, most existing E2E-AD methods remain confined to short-horizon planning and lack the ability to model long-term temporal dependencies, which severely limits their generalization and security in complex and highly interactive driving scenarios. In this work, we propose GraphWorld, an E2E-AD framework that explicitly enhances long-horizon planning through latent world modeling. We introduce an Ego-Centric Interaction Graph, which adaptively models critical neighboring agents based on spatial proximity, and propagates relational context to planning queries via cross-node cross-attention. We present a World-State-Conditioned Planning that learns ego-centric latent world representations by modeling interactions between an ego vehicle and surrounding agents. This latent world state captures key interaction dynamics and safety-relevant semantics, and serves as a conditioning signal to guide long-horizon, safety-aware trajectory planning. Extensive experiments on Bench2Drive, NAVSIMv1/2, and nuScenes demonstrate that GraphWorld significantly reduces collision rates and improves long-horizon planning performance, validating its effectiveness in complex driving environments.
### Title:
          RealityBridge: Bridging Editable 3D Gaussian Splatting Driving Simulations and Real-World Videos
 - **Authors:** Zhenhua Wu, Yun Pang, Mingkun Chang, Yuwei Ning, Liangzhi Wang, Yi Xiao, Guanbin Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-tail hazardous scenarios are essential for safety-oriented autonomous driving, yet they are difficult to collect and reproduce at scale. Editable 3D Gaussian Splatting (3DGS) simulation offers a promising alternative by reconstructing real driving scenes and supporting controllable scene editing. However, edited 3DGS-rendered videos still suffer from a significant Sim-to-Real gap, including rendering artifacts, degraded foreground assets, inconsistent illumination, and temporal flickering. Existing restoration and video generation methods are insufficient for this task, as they often fail to jointly repair 3DGS-specific artifacts, improve visual realism, and ensure temporal consistency. To fill this gap, we propose RealityBridge, a structure-preserving and asset-aware Sim-to-Real framework for edited 3DGS driving videos. RealityBridge uses multimodal controls, including rendered videos, foreground masks, edge maps, and semantic masks, together with a lightweight GateNet for adaptive condition allocation across backbone layers. We further construct targeted training data and introduce autoregressive long-video training with reward-guided post-training to improve restoration quality, temporal stability, and hallucination suppression. Extensive experiments on internal and public driving datasets show that RealityBridge outperforms existing methods in artifact removal, illumination harmonization, and long-sequence temporal consistency.
### Title:
          Is Your Trajectory Displacement Safe in Long-tail?
 - **Authors:** Qiao Sun, Weicheng Zheng, Yixin Huang, Hang Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-tail scenarios remain a major bottleneck for autonomous driving evaluation, even as datasets grow by orders of magnitude. Existing evaluation pipelines are rarely human-aligned, safety-aware, verifiable, and explainable at the same time: closed-loop metrics often saturate among strong planners, while unstructured human ratings can be noisy without a carefully designed protocol. We formulate planning evaluation as additional-threat detection: given a planner trajectory and an expert reference, does the planner's displacement introduce new unsafe driving behavior? We propose FluidTest, an evaluation pipeline with three components: a pairwise WebUI protocol for reliable human annotation; a taxonomy of 32 semantic threats with evidence-grounded decision graphs; and a three-agent verification system with reflection for precision and auditability. Experiments on the WOD-E2E dataset show that FluidTest produces consistent labels among trained annotators and identifies additional threats in 65% of Poutine trajectories and 51% of RAP trajectories. These results show that state-of-the-art planners can still exhibit substantial safety-relevant failures despite high Rater Feedback Scores (RFS) and low Average Displacement Error (ADE). Additional details, guidance, and code are available at this https URL.
### Title:
          GraphBEV++: Multi-Modal Feature Alignment for Autonomous Driving
 - **Authors:** Ziying Song, Caiyan Jia, Lin Liu, Shaoqing Xu, Lei Yang, Yadan Luo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feature misalignment in BEV perception is a critical yet often overlooked challenge in autonomous driving, especially under calibration uncertainties between LiDAR and camera sensors. To address this issue, we propose a robust multi-modal fusion framework, GraphBEV++, which systematically mitigates projection-induced misalignment. The framework consists of two key modules: LocalAlign-v2 and GlobalAlign-v2. LocalAlign-v2 introduces neighborhood-aware depth features via graph matching to correct local misalignment. It supports both LSS-based and query-based BEV representations, making it compatible with BEVFusion and BEVFormer architectures for consistent cross-paradigm alignment. GlobalAlign-v2 encompasses two variants: Deformable and Diffusion. The Deformable variant addresses global misalignment in LSS-based multi-modal BEV by explicitly learning cross-modal feature offsets. In contrast, the Diffusion variant targets implicit misalignment in query-based BEV by injecting noise to simulate misalignment and employing a denoising process to recover aligned features. Experimental results show that GraphBEV++ achieves state-of-the-art performance under misalignment noise on nuScenes and Waymo subset, improves long-range detection on Argoverse2, and generalizes effectively to the 3D occupancy prediction task, consistently improving occupancy estimation accuracy and robustness under both clean and noisy settings. Furthermore, GraphBEV++ effectively alleviates misalignment issues in end-to-end autonomous driving. Compared with five baselines (UniAD, VAD, FusionAD, MomAD, and WoTE), it demonstrates superior performance in both open-loop (nuScenes) and closed-loop (Bench2Drive and NAVSIM) evaluations across perception, prediction, and planning tasks.
### Title:
          HOLO-MPPI: Multi-Scenario Motion Planning via Hierarchical Policy Optimization
 - **Authors:** Youngjae Min, Jovin D'sa, Faizan M. Tariq, David Isele, Navid Azizan, Sangjae Bae
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robots deployed in the real world must plan motions across diverse scenarios without per-scenario retuning. End-to-end reinforcement learning (RL) can generalize across scenarios but often becomes brittle under distribution shift, reward misspecification, and stochastic interactions. Model predictive path integral (MPPI) control enables strong real-time refinement without gradients, but its performance depends on a well-shaped sampling prior, while manually designing the priors does not scale to multi-scenario deployment. We present HOLO-MPPI (High-level Offline, Low-level Online MPPI), a multi-scenario motion planning framework that combines high-level policy learning with low-level stochastic optimal control. Offline, we learn a high-level policy that proposes scenario-robust plans in an abstract action space, with a learned world model for online rollout. Online, the policy serves as a data-driven prior generator that parameterizes MPPI's sampling distribution conditioned on the current observation and goal. MPPI then optimizes low-level control sequences around this prior in real time to adapt to local disturbances. We instantiate HOLO-MPPI in autonomous driving by designing an effective high-level action space and tailored model architectures. Our evaluation across diverse driving scenarios shows that HOLO-MPPI improves upon MPPI and end-to-end RL baselines while maintaining real-time control.
### Title:
          SurroundNEXO: Ego-Centric Metric Bridging for Spatially Consistent Geometry in Autonomous Driving
 - **Authors:** Shuai Yuan, Runxi Tang, Yuzhou Ji, Fudong Ge, Hanshi Wang, Yifei Wang, Xianming Zeng, Jianyun Xu, Xingliang Liu, Yanfeng Wang, Zhipeng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern autonomous driving depends on accurate metric 3D understanding for perception, reconstruction, and planning, which in turn requires reliable multi-camera depth prediction. However, the outward-facing nature of vehicle-mounted surround-view camera rigs inherently limits visual overlap across views, challenging the correspondence-based assumptions that underpin conventional multi-view geometry. To bridge this gap, we present SurroundNEXO, named after the Spanish word nexo for a geometric link, a low-overlap multi-camera metric depth framework that grounds cross-view reasoning in ego-centric geometry rather than dense visual correspondences. Instead of directly enforcing early global fusion, SurroundNEXO first assigns image tokens globally comparable ego-frame viewing directions through Ego-Ray Positional Encoding, then uses sparse LiDAR measurements as metric anchors to propagate absolute scale cues, and finally expands feature interaction progressively from view-local modeling to decomposed spatio-temporal reasoning and global integration. This design enables metric-scale depth prediction with improved spatial consistency across weakly overlapping cameras. Across low-overlap autonomous driving benchmarks, including NuScenes, Waymo and DDAD, SurroundNEXO reduces single-view error by 33.2%, improves cross-view consistency by 10.5%, and enhances metric reconstruction quality by 25.6% compared with SOTA methods. It further remains robust under extremely sparse depth prompts and exhibits strong zero-shot generalization to unseen camera layouts.
### Title:
          ActiveSAM: Image-Conditional Class Pruning for Fast and Accurate Open-Vocabulary Segmentation
 - **Authors:** Tran Dinh Tien, Zhiqiang Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Segment Anything Model 3 (SAM 3) provides a strong frozen backbone for concept-prompted segmentation, but applying it directly to open-vocabulary semantic segmentation (OVSS) is inefficient: full-resolution decoding is typically run over the entire dataset vocabulary, whereas each image contains only a small active subset of classes. We introduce ActiveSAM, a training-free, zero-shot inference framework that turns SAM 3 into an active-vocabulary segmenter. ActiveSAM first canonicalizes and expands class prompts, then estimates an image-conditioned active set from a low-resolution presence preview. Only the retained classes are decoded at full resolution, using bucketed prompt multiplexing with the frozen SAM 3 decoder. The preview stage uses only class-presence evidence and skips unnecessary segmentation-head computation, while the final stage applies margin-aware background calibration to suppress low-confidence pixels. ActiveSAM requires no target-dataset training, no weight updates, and no oracle class-presence labels. Across eight OVSS benchmarks, ActiveSAM improves the speed-accuracy tradeoff of training-free open-vocabulary semantic segmentation, outperforming the current state-of-the-art SegEarth-OV3 by approximately +1.4 mIoU on average while running up to 5.5x faster on large-vocabulary datasets. ActiveSAM also demonstrates the strongest robustness under image corruption that simulates real-world distribution shift, making it well-suited for deployment in noisy-input domains such as autonomous driving and embodied AI. Code is available at this https URL.
### Title:
          Qwen-RobotWorld Technical Report: Unifying Embodied World Modeling through Language-Conditioned Video Generation
 - **Authors:** Jie Zhang, Xiaoyue Chen, Anzhe Chen, Chenxu Lv, Deqing Li, Gengze Zhou, Hang Yin, Haoqi Yuan, Haoyang Li, Jiahao Li, Jiazhao Zhang, Jingren Zhou, Kaiyuan Gao, Kun Yan, Lihan Jiang, Ningyuan Tang, Pei Lin, Qihang Peng, Shengming Yin, Tianhe Wu, Tianyi Yan, Xiao Xu, Yan Shu, Yanran Zhang, Ye Wang, Yi Wang, Yilei Chen, Yixian Xu, Yiyang Huang, Yuxiang Chen, Zekai Zhang, Zhendong Wang, Zhixing Lei, Zhixuan Liang, Zihao Liu, Zikai Zhou, Xiong-Hui Chen, Chenfei Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Qwen-RobotWorld, a language-conditioned video world model for embodied intelligence. With natural language as a unified action interface, it predicts physically grounded future visual trajectories from current observations across robotic manipulation, autonomous driving, indoor navigation, and human-to-robot transfer. This unified formulation provides three promising application directions: synthetic data generation for policy training augmentation, scalable virtual environments for policy evaluation, and language-guided planning signals for downstream robot control. This is achieved through a three-part design: a) Double-Stream MMDiT with MLLM Action Encoding, where a 60-layer double-stream diffusion transformer couples frozen Qwen2.5-VL semantics with video-VAE latents through layer-wise joint attention; b) Embodied World Knowledge (EWK), an 8.6M video-text corpus (200M+ frames) with action-language mapping over 20+ embodiments and 500+ action categories; and c) General+Expert Progressive Curriculum, a two-stage training strategy that first learns general visual priors and then injects embodied specialization under a shared language interface. Extensive results show strong competitiveness: ranks 1st overall on EWMBench and DreamGen Bench, outperforms all open-source models on WorldModelBench and PBench. Additional zero-shot analyses on RoboTwin-IF benchmark further support robust generalization and multi-view consistency.
### Title:
          BRDFusion: Physics Meets Generation for Urban Scene Inverse Rendering
 - **Authors:** Yi-Ruei Liu, Jie-Ying Lee, Zheng-Hui Huang, Yu-Lun Liu, Chih-Hao Lin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inverse rendering of urban scenes from captured videos enables numerous applications, including content creation and autonomous driving simulation. Physically-based rendering methods follow and control lighting physics, but suffer from reconstruction and rendering artifacts. While generative models produce realistic videos, they offer limited consistency and controllability. We present BRDFusion, a unified framework that combines two complementary models for inverse and forward rendering. Specifically, BRDFusion recovers explicit, consistent scene properties with physical modeling and alleviates optimization ambiguity with generative priors. During forward rendering, the physical model provides controllable rendering from the scene configuration, and the generative model denoises and fixes artifacts. Therefore, our method produces high-quality videos while allowing precise control, outperforming baselines in real and synthetic scenes. Moreover, BRDFusion supports novel-view relighting, night simulation, and dynamic object insertion/editing. Project page: this https URL
