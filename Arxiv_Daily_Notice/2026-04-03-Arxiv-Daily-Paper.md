# Showing new listings for Friday, 3 April 2026
## Keyword: SLAM
### Title:
          HyVGGT-VO: Tightly Coupled Hybrid Dense Visual Odometry with Feed-Forward Models
 - **Authors:** Junxiang Pan, Lipu Zhou, Baojie Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense visual odometry (VO), which provides pose estimation and dense 3D reconstruction, serves as the cornerstone for applications ranging from robotics to augmented reality. Recently, feed-forward models have demonstrated remarkable capabilities in dense mapping. However, when these models are used in dense visual SLAM systems, their heavy computational burden restricts them to yielding sparse pose outputs at keyframes while still failing to achieve real-time pose estimation. In contrast, traditional sparse methods provide high computational efficiency and high-frequency pose outputs, but lack the capability for dense reconstruction. To address these limitations, we propose HyVGGT-VO, a novel framework that combines the computational efficiency of sparse VO with the dense reconstruction capabilities of feed-forward models. To the best of our knowledge, this is the first work to tightly couple a traditional VO framework with VGGT, a state-of-the-art feed-forward model. Specifically, we design an adaptive hybrid tracking frontend that dynamically switches between traditional optical flow and the VGGT tracking head to ensure robustness. Furthermore, we introduce a hierarchical optimization framework that jointly refines VO poses and the scale of VGGT predictions to ensure global scale consistency. Our approach achieves an approximately 5x processing speedup compared to existing VGGT-based methods, while reducing the average trajectory error by 85% on the indoor EuRoC dataset and 12% on the outdoor KITTI benchmark. Our code will be publicly available upon acceptance. Project page: this https URL.
## Keyword: odometry
### Title:
          Hi-LOAM: Hierarchical Implicit Neural Fields for LiDAR Odometry and Mapping
 - **Authors:** Zhiliu Yang, Jianyuan Zhang, Lianhui Zhao, Jinyu Dai, Zhu Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR Odometry and Mapping (LOAM) is a pivotal technique for embodied-AI applications such as autonomous driving and robot navigation. Most existing LOAM frameworks are either contingent on the supervision signal, or lack of the reconstruction fidelity, which are deficient in depicting details of large-scale complex scenes. To overcome these limitations, we propose a multi-scale implicit neural localization and mapping framework using LiDAR sensor, called Hi-LOAM. Hi-LOAM receives LiDAR point cloud as the input data modality, learns and stores hierarchical latent features in multiple levels of hash tables based on an octree structure, then these multi-scale latent features are decoded into signed distance value through shallow Multilayer Perceptrons (MLPs) in the mapping procedure. For pose estimation procedure, we rely on a correspondence-free, scan-to-implicit matching paradigm to estimate optimal pose and register current scan into the submap. The entire training process is conducted in a self-supervised manner, which waives the model pre-training and manifests its generalizability when applied to diverse environments. Extensive experiments on multiple real-world and synthetic datasets demonstrate the superior performance, in terms of the effectiveness and generalization capabilities, of our Hi-LOAM compared to existing state-of-the-art methods.
### Title:
          PTC-Depth: Pose-Refined Monocular Depth Estimation with Temporal Consistency
 - **Authors:** Leezy Han, Seunggyu Kim, Dongseok Shim, Hyeonbeom Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular depth estimation (MDE) has been widely adopted in the perception systems of autonomous vehicles and mobile robots. However, existing approaches often struggle to maintain temporal consistency in depth estimation across consecutive frames. This inconsistency not only causes jitter but can also lead to estimation failures when the depth range changes abruptly. To address these challenges, this paper proposes a consistency-aware monocular depth estimation framework that leverages wheel odometry from a mobile robot to achieve stable and coherent depth predictions over time. Specifically, we estimate camera pose and sparse depth from triangulation using optical flow between consecutive frames. The sparse depth estimates are used to update a recursive Bayesian estimate of the metric scale, which is then applied to rescale the relative depth predicted by a pre-trained depth estimation foundation model. The proposed method is evaluated on the KITTI, TartanAir, MS2, and our own dataset, demonstrating robust and accurate depth estimation performance.
### Title:
          HyVGGT-VO: Tightly Coupled Hybrid Dense Visual Odometry with Feed-Forward Models
 - **Authors:** Junxiang Pan, Lipu Zhou, Baojie Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense visual odometry (VO), which provides pose estimation and dense 3D reconstruction, serves as the cornerstone for applications ranging from robotics to augmented reality. Recently, feed-forward models have demonstrated remarkable capabilities in dense mapping. However, when these models are used in dense visual SLAM systems, their heavy computational burden restricts them to yielding sparse pose outputs at keyframes while still failing to achieve real-time pose estimation. In contrast, traditional sparse methods provide high computational efficiency and high-frequency pose outputs, but lack the capability for dense reconstruction. To address these limitations, we propose HyVGGT-VO, a novel framework that combines the computational efficiency of sparse VO with the dense reconstruction capabilities of feed-forward models. To the best of our knowledge, this is the first work to tightly couple a traditional VO framework with VGGT, a state-of-the-art feed-forward model. Specifically, we design an adaptive hybrid tracking frontend that dynamically switches between traditional optical flow and the VGGT tracking head to ensure robustness. Furthermore, we introduce a hierarchical optimization framework that jointly refines VO poses and the scale of VGGT predictions to ensure global scale consistency. Our approach achieves an approximately 5x processing speedup compared to existing VGGT-based methods, while reducing the average trajectory error by 85% on the indoor EuRoC dataset and 12% on the outdoor KITTI benchmark. Our code will be publicly available upon acceptance. Project page: this https URL.
## Keyword: livox
There is no result 
## Keyword: loam
### Title:
          Hi-LOAM: Hierarchical Implicit Neural Fields for LiDAR Odometry and Mapping
 - **Authors:** Zhiliu Yang, Jianyuan Zhang, Lianhui Zhao, Jinyu Dai, Zhu Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR Odometry and Mapping (LOAM) is a pivotal technique for embodied-AI applications such as autonomous driving and robot navigation. Most existing LOAM frameworks are either contingent on the supervision signal, or lack of the reconstruction fidelity, which are deficient in depicting details of large-scale complex scenes. To overcome these limitations, we propose a multi-scale implicit neural localization and mapping framework using LiDAR sensor, called Hi-LOAM. Hi-LOAM receives LiDAR point cloud as the input data modality, learns and stores hierarchical latent features in multiple levels of hash tables based on an octree structure, then these multi-scale latent features are decoded into signed distance value through shallow Multilayer Perceptrons (MLPs) in the mapping procedure. For pose estimation procedure, we rely on a correspondence-free, scan-to-implicit matching paradigm to estimate optimal pose and register current scan into the submap. The entire training process is conducted in a self-supervised manner, which waives the model pre-training and manifests its generalizability when applied to diverse environments. Extensive experiments on multiple real-world and synthetic datasets demonstrate the superior performance, in terms of the effectiveness and generalization capabilities, of our Hi-LOAM compared to existing state-of-the-art methods.
## Keyword: lidar
### Title:
          Simulating Realistic LiDAR Data Under Adverse Weather for Autonomous Vehicles: A Physics-Informed Learning Approach
 - **Authors:** Vivek Anand, Bharat Lohani, Rakesh Mishra, Gaurav Pandey
 - **Subjects:** Subjects:
Robotics (cs.RO); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate LiDAR simulation is crucial for autonomous driving, especially under adverse weather conditions. Existing methods struggle to capture the complex interactions between LiDAR signals and atmospheric phenomena, leading to unrealistic representations. This paper presents a physics-informed learning framework (PICWGAN) for generating realistic LiDAR data under adverse weather conditions. By integrating physicsdriven constraints for modeling signal attenuation and geometryconsistent degradations into a physics-informed learning pipeline, the proposed method reduces the sim-to-real gap. Evaluations on real-world datasets (CADC for snow, Boreas for rain) and the VoxelScape dataset show that our approach closely mimics realworld intensity patterns. Quantitative metrics, including MSE, SSIM, KL divergence, and Wasserstein distance, demonstrate statistically consistent intensity distributions. Additionally, models trained on data enhanced by our framework outperform baselines in downstream 3D object detection, achieving performance comparable to models trained on real-world data. These results highlight the effectiveness of the proposed approach in improving the realism of LiDAR data and enabling robust perception under adverse weather conditions.
### Title:
          IGLOSS: Image Generation for Lidar Open-vocabulary Semantic Segmentation
 - **Authors:** Nermin Samet, Gilles Puy, Renaud Marlet
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a new method for the zero-shot open-vocabulary semantic segmentation (OVSS) of 3D automotive lidar data. To circumvent the recognized image-text modality gap that is intrinsic to approaches based on Vision Language Models (VLMs) such as CLIP, our method relies instead on image generation from text, to create prototype images. Given a 3D network distilled from a 2D Vision Foundation Model (VFM), we then label a point cloud by matching 3D point features with 2D image features of these prototypes. Our method is state-of-the-art for OVSS on nuScenes and SemanticKITTI. Code, pre-trained models, and generated images are available at this https URL.
### Title:
          Semantically Annotated Multimodal Dataset for RF Interpretation and Prediction
 - **Authors:** Steve Blandino, Jelena Senic, Raied Caromi, Samuel Berweger, Anuraag Bodi, Camillo Gentile, Nada Golmie
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET); Artificial Intelligence (cs.AI); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current limitations in wireless modeling and radio frequency (RF)-based AI are primarily driven by a lack of high-quality, measurement-based datasets that connect RF signals to their physical environments. RF heatmaps, the typical form of such data, are high-dimensional and complex but lack the geometric and semantic context needed for interpretation, constraining the development of supervised machine learning models. To address this bottleneck, we propose a new class of multimodal datasets that combines RF measurements with auxiliary modalities like high-resolution cameras and lidar to bridge the gap between RF signals and their physical causes. The proposed data collection will span diverse indoor and outdoor environments, featuring both static and dynamic scenarios, including human activities ranging from walking to subtle gestures. By achieving precise spatial and temporal co-registration and creating digital replicas for voxel-level annotation, this dataset will enable transformative AI research. Key tasks include the forward problem of predicting RF heatmaps from visual data to revolutionize wireless system design, and the inverse problem of inferring scene semantics from RF signals, creating a new form of RF-based perception.
### Title:
          F3DGS: Federated 3D Gaussian Splatting for Decentralized Multi-Agent World Modeling
 - **Authors:** Morui Zhu, Mohammad Dehghani Tezerjani, Mátyás Szántó, Márton Vaitkus, Song Fu, Qing Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present F3DGS, a federated 3D Gaussian Splatting framework for decentralized multi-agent 3D reconstruction. Existing 3DGS pipelines assume centralized access to all observations, which limits their applicability in distributed robotic settings where agents operate independently, and centralized data aggregation may be restricted. Directly extending centralized training to multi-agent systems introduces communication overhead and geometric inconsistency. F3DGS first constructs a shared geometric scaffold by registering locally merged LiDAR point clouds from multiple clients to initialize a global 3DGS model. During federated optimization, Gaussian positions are fixed to preserve geometric alignment, while each client updates only appearance-related attributes, including covariance, opacity, and spherical harmonic coefficients. The server aggregates these updates using visibility-aware aggregation, weighting each client's contribution by how frequently it observed each Gaussian, resolving the partial-observability challenge inherent to multi-agent exploration. To evaluate decentralized reconstruction, we collect a multi-sequence indoor dataset with synchronized LiDAR, RGB, and IMU measurements. Experiments show that F3DGS achieves reconstruction quality comparable to centralized training while enabling distributed optimization across agents. The dataset, development kit, and source code will be publicly released.
### Title:
          Hi-LOAM: Hierarchical Implicit Neural Fields for LiDAR Odometry and Mapping
 - **Authors:** Zhiliu Yang, Jianyuan Zhang, Lianhui Zhao, Jinyu Dai, Zhu Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR Odometry and Mapping (LOAM) is a pivotal technique for embodied-AI applications such as autonomous driving and robot navigation. Most existing LOAM frameworks are either contingent on the supervision signal, or lack of the reconstruction fidelity, which are deficient in depicting details of large-scale complex scenes. To overcome these limitations, we propose a multi-scale implicit neural localization and mapping framework using LiDAR sensor, called Hi-LOAM. Hi-LOAM receives LiDAR point cloud as the input data modality, learns and stores hierarchical latent features in multiple levels of hash tables based on an octree structure, then these multi-scale latent features are decoded into signed distance value through shallow Multilayer Perceptrons (MLPs) in the mapping procedure. For pose estimation procedure, we rely on a correspondence-free, scan-to-implicit matching paradigm to estimate optimal pose and register current scan into the submap. The entire training process is conducted in a self-supervised manner, which waives the model pre-training and manifests its generalizability when applied to diverse environments. Extensive experiments on multiple real-world and synthetic datasets demonstrate the superior performance, in terms of the effectiveness and generalization capabilities, of our Hi-LOAM compared to existing state-of-the-art methods.
### Title:
          FSKD: Monocular Forest Structure Inference via LiDAR-to-RGBI Knowledge Distillation
 - **Authors:** Taimur Khan, Hannes Feilhauer, Muhammad Jazib Zafar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Very High Resolution (VHR) forest structure data at individual-tree scale is essential for carbon, biodiversity, and ecosystem monitoring. Still, airborne LiDAR remains costly and infrequent despite being the reference for forest structure metrics like Canopy Height Model (CHM), Plant Area Index (PAI), and Foliage Height Diversity (FHD). We propose FSKD: a LiDAR-to-RGB-Infrared (RGBI) knowledge distillation (KD) framework in which a multi-modal teacher fuses RGBI imagery with LiDAR-derived planar metrics and vertical profiles via cross-attention, and an RGBI-only SegFormer student learns to reproduce these outputs. Trained on 384 $km^2$ of forests in Saxony, Germany (20 cm ground sampling distance (GSD)) and evaluated on eight geographically distinct test tiles, the student achieves state-of-the-art (SOTA) zero-shot CHM performance (MedAE 4.17 m, $R^2$=0.51, IoU 0.87), outperforming HRCHM/DAC baselines by 29--46% in MAE (5.81 m vs. 8.14--10.84 m) with stronger correlation coefficients (0.713 vs. 0.166--0.652). Ablations show that multi-modal fusion improves performance by 10--26% over RGBI-only training, and that asymmetric distillation with appropriate model capacity is critical. The method jointly predicts CHM, PAI, and FHD, a multi-metric capability not provided by current monocular CHM estimators, although PAI/FHD transfer remains region-dependent and benefits from local calibration. The framework also remains effective under temporal mismatch (winter LiDAR, summer RGBI), removing strict co-acquisition constraints and enabling scalable 20 cm operational monitoring for workflows such as Digital Twin Germany and national Digital Orthophoto programs.
### Title:
          Learning Spatial Structure from Pre-Beamforming Per-Antenna Range-Doppler Radar Data via Visibility-Aware Cross-Modal Supervision
 - **Authors:** George Sebastian, Philipp Berthold, Bianca Forkel, Leon Pohl, Mirko Maehlisch
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automotive radar perception pipelines commonly construct angle-domain representations via beamforming before applying learning-based models. This work instead investigates a representational question: can meaningful spatial structure be learned directly from pre-beamforming per-antenna range-Doppler (RD) measurements? Experiments are conducted on a 6-TX x 8-RX (48 virtual antennas) commodity automotive radar employing an A/B chirp-sequence frequency-modulated continuous-wave (CS-FMCW) transmit scheme, in which the effective transmit aperture varies between chirps (single-TX vs. multi-TX), enabling controlled analysis of chirp-dependent transmit configurations. We operate on pre-beamforming per-antenna RD tensors using a dual-chirp shared-weight encoder trained in an end-to-end, fully data-driven manner, and evaluate spatial recoverability using bird's-eye-view (BEV) occupancy as a geometric probe rather than a performance-driven objective. Supervision is visibility-aware and cross-modal, derived from LiDAR with explicit modeling of the radar field-of-view and occlusion-aware LiDAR observability via ray-based visibility. Through chirp ablations (A-only, B-only, A+B), range-band analysis, and physics-aligned baselines, we assess how transmit configurations affect geometric recoverability. The results indicate that spatial structure can be learned directly from pre-beamforming per-antenna RD tensors without explicit angle-domain construction or hand-crafted signal-processing stages.
### Title:
          ROS 2-Based LiDAR Perception Framework for Mobile Robots in Dynamic Production Environments, Utilizing Synthetic Data Generation, Transformation-Equivariant 3D Detection and Multi-Object Tracking
 - **Authors:** Lukas Bergs, Tan Chung, Marmik Thakkar, Alexander Moriz, Amon Göppert, Chinnawut Nantabut, Robert Schmitt
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adaptive robots in dynamic production environments require robust perception capabilities, including 6D pose estimation and multi-object tracking. To address limitations in real-world data dependency, noise robustness, and spatiotemporal consistency, a LiDAR framework based on the Robot Operating System integrating a synthetic-data-trained Transformation-Equivariant 3D Detection with multi-object-tracking leveraging center poses is proposed. Validated across 72 scenarios with motion capture technology, overall results yield an Intersection over Union of 62.6% for standalone pose estimation, rising to 83.12% with multi-object-tracking integration. Our LiDAR-based framework achieves 91.12% of Higher Order Tracking Accuracy, advancing robustness and versatility of LiDAR-based perception systems for industrial mobile manipulators.
### Title:
          Deep Neural Network Based Roadwork Detection for Autonomous Driving
 - **Authors:** Sebastian Wullrich, Nicolai Steinke, Daniel Goehring
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Road construction sites create major challenges for both autonomous vehicles and human drivers due to their highly dynamic and heterogeneous nature. This paper presents a real-time system that detects and localizes roadworks by combining a YOLO neural network with LiDAR data. The system identifies individual roadwork objects while driving, merges them into coherent construction sites and records their outlines in world coordinates. The model training was based on an adapted US dataset and a new dataset collected from test drives with a prototype vehicle in Berlin, Germany. Evaluations on real-world road construction sites showed a localization accuracy below 0.5 m. The system can support traffic authorities with up-to-date roadwork data and could enable autonomous vehicles to navigate construction sites more safely in the future.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          GEMM-GS: Accelerating 3D Gaussian Splatting on Tensor Cores with GEMM-Compatible Blending
 - **Authors:** Haomin Li, Bowen Zhu, Fangxin Liu, Zongwu Wang, Xinran Liang, Li Jiang, Haibing Guan
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural Radiance Fields (NeRF) enables 3D scene reconstruction from several 2D images but incurs high rendering latency via its point-sampling design. 3D Gaussian Splatting (3DGS) improves on NeRF with explicit scene representation and an optimized pipeline yet still fails to meet practical real-time demands. Existing acceleration works overlook the evolving Tensor Cores of modern GPUs because 3DGS pipeline lacks General Matrix Multiplication (GEMM) operations. This paper proposes GEMM-GS, an acceleration approach utilizing tensor cores on GPUs via GEMM-friendly blending transformation. It equivalently reformulates the 3DGS blending process into a GEMM-compatible form to utilize Tensor Cores. A high-performance CUDA kernel is designed, integrating a three-stage double-buffered pipeline that overlaps computation and memory access. Extensive experiments show that GEMM-GS achieves $1.42\times$ speedup over vanilla 3DGS and provides an additional $1.47\times$ speedup on average when combining with existing acceleration approaches. Code is released at this https URL.
## Keyword: mapping
### Title:
          Computational Foundations for Strategic Coopetition: Formalizing Sequential Interaction and Reciprocity
 - **Authors:** Vik Pant, Eric Yu
 - **Subjects:** Subjects:
Multiagent Systems (cs.MA); Artificial Intelligence (cs.AI); Computers and Society (cs.CY); Computer Science and Game Theory (cs.GT); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Strategic coopetition in multi-stakeholder systems requires understanding how cooperation persists through time without binding contracts. This technical report extends computational foundations for strategic coopetition to sequential interaction dynamics, bridging conceptual modeling (i* framework) with game-theoretic reciprocity analysis. We develop: (1) bounded reciprocity response functions mapping partner deviations to finite conditional responses, (2) memory-windowed history tracking capturing cognitive limitations over k recent periods, (3) structural reciprocity sensitivity derived from interdependence matrices where behavioral responses are amplified by structural dependencies, and (4) trust-gated reciprocity where trust modulates reciprocity responses. The framework applies to both human stakeholder interactions and multi-agent computational systems. Comprehensive validation across 15,625 parameter configurations demonstrates robust reciprocity effects, with all six behavioral targets exceeding thresholds: cooperation emergence (97.5%), defection punishment (100%), forgiveness dynamics (87.9%), asymmetric differentiation (100%), trust-reciprocity interaction (100%), and bounded responses (100%). Empirical validation using the Apple iOS App Store ecosystem (2008-2024) achieves 43/51 applicable points (84.3%), reproducing documented cooperation patterns across five ecosystem phases. Statistical significance confirmed at p < 0.001 with Cohen's d = 1.57. This report concludes the Foundations Series (TR-1 through TR-4) adopting uniaxial treatment where agents choose cooperation levels along a single continuum. Companion work on interdependence (arXiv:2510.18802), trust (arXiv:2510.24909), and collective action (arXiv:2601.16237) has been prepublished. Extensions Series (TR-5 through TR-8) introduces biaxial treatment where cooperation and competition are independent dimensions.
### Title:
          JetPrism: diagnosing convergence for generative simulation and inverse problems in nuclear physics
 - **Authors:** Zeyu Xia, Tyler Kim, Trevor Reed, Judy Fox, Geoffrey Fox, Adam Szczepaniak
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Nuclear Experiment (nucl-ex); Data Analysis, Statistics and Probability (physics.data-an); Instrumentation and Detectors (physics.ins-det)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-fidelity Monte Carlo simulations and complex inverse problems, such as mapping smeared experimental observations to ground-truth states, are computationally intensive yet essential for robust data analysis. Conditional Flow Matching (CFM) offers a mathematically robust approach to accelerating these tasks, but we demonstrate its standard training loss is fundamentally misleading. In rigorous physics applications, CFM loss plateaus prematurely, serving as an unreliable indicator of true convergence and physical fidelity. To investigate this disconnect, we designed JetPrism, a configurable CFM framework acting as an efficient generative surrogate for evaluating unconditional generation and conditional detector unfolding. Using synthetic stress tests and a Jefferson Lab kinematic dataset ($\gamma p \to \rho^0 p \to \pi^+\pi^- p$) relevant to the forthcoming Electron-Ion Collider (EIC), we establish that physics-informed metrics continue to improve significantly long after the standard loss converges. Consequently, we propose a multi-metric evaluation protocol incorporating marginal and pairwise $\chi^2$ statistics, $W_1$ distances, correlation matrix distances ($D_{\mathrm{corr}}$), and nearest-neighbor distance ratios ($R_{\mathrm{NN}}$). By demonstrating that domain-specific evaluations must supersede generic loss metrics, this work establishes JetPrism as a dependable generative surrogate that ensures precise statistical agreement with ground-truth data without memorizing the training set. While demonstrated in nuclear physics, this diagnostic framework is readily extensible to parameter generation and complex inverse problems across broad domains. Potential applications span medical imaging, astrophysics, semiconductor discovery, and quantitative finance, where high-fidelity simulation, rigorous inversion, and generative reliability are critical.
### Title:
          The Digital Twin Counterfactual Framework: A Validation Architecture for Simulated Potential Outcomes
 - **Authors:** Olav Laudy
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Methodology (stat.ME)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The fundamental problem of causal inference - that the counterfactual outcome for any individual is never observed - has shaped the entire methodology of the field. Every existing approach substitutes assumptions for missing data: ignorability, parallel trends, exclusion restrictions. None produces the counterfactual itself. This paper proposes the Digital Twin Counterfactual Framework (DTCF): rather than estimating the counterfactual statistically, we simulate it using a digital twin and subject the simulation to a hierarchical validation regime. We formalize the digital twin simulator as a stochastic mapping within the potential outcomes framework and introduce a hierarchy of twin fidelity assumptions - from marginal fidelity through joint fidelity to structural fidelity - each unlocking a progressively richer class of estimands. The central contribution is threefold. First, a five-level validation architecture converts the unfalsifiable claim that the simulator produces correct counterfactuals into falsifiable tests against observable data. Second, a formal decomposition separates causal quantities into those that are marginally validated (ATE, CATE, QTE - testable through observable-arm comparison) and those that are copula-dependent (the ITE distribution, probability of benefit/harm, variance of treatment effects - permanently reliant on the unobservable within-individual dependence structure). Third, bounding, sensitivity, and uncertainty quantification tools make the copula dependence explicit. The DTCF does not resolve the fundamental problem of causal inference. What it provides is a framework in which marginal causal claims become increasingly testable, joint causal claims become explicitly assumption-indexed, and the gap between the two is formally characterized.
### Title:
          Residuals-based Offline Reinforcement Learning
 - **Authors:** Qing Zhu, Xian Yu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Offline reinforcement learning (RL) has received increasing attention for learning policies from previously collected data without interaction with the real environment, which is particularly important in high-stakes applications. While a growing body of work has developed offline RL algorithms, these methods often rely on restrictive assumptions about data coverage and suffer from distribution shift. In this paper, we propose a residuals-based offline RL framework for general state and action spaces. Specifically, we define a residuals-based Bellman optimality operator that explicitly incorporates estimation error in learning transition dynamics into policy optimization by leveraging empirical residuals. We show that this Bellman operator is a contraction mapping and identify conditions under which its fixed point is asymptotically optimal and possesses finite-sample guarantees. We further develop a residuals-based offline deep Q-learning (DQN) algorithm. Using a stochastic CartPole environment, we demonstrate the effectiveness of our residuals-based offline DQN algorithm.
### Title:
          Assertain: Automated Security Assertion Generation Using Large Language Models
 - **Authors:** Shams Tarek, Dipayan Saha, Khan Thamid Hasan, Sujan Kumar Saha, Mark Tehranipoor, Farimah Farahmandi
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The increasing complexity of modern system-on-chip designs amplifies hardware security risks and makes manual security property specification a major bottleneck in formal property verification. This paper presents Assertain, an automated framework that integrates RTL design analysis, Common Weakness Enumeration (CWE) mapping, and threat model intelligence to automatically generate security properties and executable SystemVerilog Assertions. Assertain leverages large language models with a self-reflection refinement mechanism to ensure both syntactic correctness and semantic consistency. Evaluated on 11 representative hardware designs, Assertain outperforms GPT-5 by 61.22%, 59.49%, and 67.92% in correct assertion generation, unique CWE coverage, and architectural flaw detection, respectively. These results demonstrate that Assertain significantly expands vulnerability coverage, improves assertion quality, and reduces manual effort in hardware security verification.
### Title:
          NED-Tree: Bridging the Semantic Gap with Nonlinear Element Decomposition Tree for LLM Nonlinear Optimization Modeling
 - **Authors:** Zhijing Hu, Yufan Deng, Haoyang Liu, Changjun Fan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automating the translation of Operations Research (OR) problems from natural language to executable models is a critical challenge. While Large Language Models (LLMs) have shown promise in linear tasks, they suffer from severe performance degradation in real-world nonlinear scenarios due to semantic misalignment between mathematical formulations and solver codes, as well as unstable information extraction. In this study, we introduce NED-Tree, a systematic framework designed to bridge the semantic gap. NED-Tree employs (a) a sentence-by-sentence extraction strategy to ensure robust parameter mapping and traceability; and (b) a recursive tree-based structure that adaptively decomposes complex nonlinear terms into solver-compatible sub-elements. Additionally, we present NEXTOR, a novel benchmark specifically designed for complex nonlinear, extensive-constraint OR problems. Experiments across 10 benchmarks demonstrate that NED-Tree establishes a new state-of-the-art with 72.51% average accuracy, NED-Tree is the first framework that drives LLMs to resolve nonlinear modeling difficulties through element decomposition, achieving alignment between modeling semantics and code semantics. The NED-Tree framework and benchmark are accessible in the anonymous repository this https URL.
### Title:
          Mitigating Implicit Inconsistencies in Patch Porting
 - **Authors:** Shengyi Pan, Zhongxin Liu, Jiayuan Zhou, Xing Hu, Xin Xia, Shanping Li
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Promptly porting patches from a source codebase to its variants (e.g., forks and branches) is essential for mitigating propagated defects and vulnerabilities. Recent studies have explored automated patch porting to reduce manual effort and delay, but existing approaches mainly handle inconsistencies visible in a patch's local context and struggle with those requiring global mapping knowledge between codebases. We refer to such non-local inconsistencies as implicit inconsistencies. Implicit inconsistencies pose greater challenges for developers to resolve due to their non-local nature. To address them, we propose MIP, which enables collaboration among an LLM, a compiler, and code analysis utilities. MIP adopts different strategies for different cases: when source identifiers exist in the target codebase, it leverages compiler diagnostics; otherwise, it retrieves matched code segment pairs from the two codebases as mapping knowledge for mitigation. Experiments on two representative scenarios, cross-fork and cross-branch patch porting, show that MIP successfully resolves more than twice as many patches as the best-performing baseline in both settings. A user study with our industry partner further demonstrates its practical effectiveness.
### Title:
          Bridging Large-Model Reasoning and Real-Time Control via Agentic Fast-Slow Planning
 - **Authors:** Jiayi Chen, Shuai Wang, Guangxu Zhu, Chengzhong Xu
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large foundation models enable powerful reasoning for autonomous systems, but mapping semantic intent to reliable real-time control remains challenging. Existing approaches either (i) let Large Language Models (LLMs) generate trajectories directly - brittle, hard to verify, and latency-prone - or (ii) adjust Model Predictive Control (MPC) objectives online - mixing slow deliberation with fast control and blurring interfaces. We propose Agentic Fast-Slow Planning, a hierarchical framework that decouples perception, reasoning, planning, and control across natural timescales. The framework contains two bridges. Perception2Decision compresses scenes into ego-centric topologies using an on-vehicle Vision-Language Model (VLM) detector, then maps them to symbolic driving directives in the cloud with an LLM decision maker - reducing bandwidth and delay while preserving interpretability. Decision2Trajectory converts directives into executable paths: Semantic-Guided A* embeds language-derived soft costs into classical search to bias solutions toward feasible trajectories, while an Agentic Refinement Module adapts planner hyperparameters using feedback and memory. Finally, MPC tracks the trajectories in real time, with optional cloud-guided references for difficult cases. Experiments in CARLA show that Agentic Fast-Slow Planning improves robustness under perturbations, reducing lateral deviation by up to 45% and completion time by over 12% compared to pure MPC and an A*-guided MPC baseline. Code is available at this https URL.
### Title:
          Hi-LOAM: Hierarchical Implicit Neural Fields for LiDAR Odometry and Mapping
 - **Authors:** Zhiliu Yang, Jianyuan Zhang, Lianhui Zhao, Jinyu Dai, Zhu Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR Odometry and Mapping (LOAM) is a pivotal technique for embodied-AI applications such as autonomous driving and robot navigation. Most existing LOAM frameworks are either contingent on the supervision signal, or lack of the reconstruction fidelity, which are deficient in depicting details of large-scale complex scenes. To overcome these limitations, we propose a multi-scale implicit neural localization and mapping framework using LiDAR sensor, called Hi-LOAM. Hi-LOAM receives LiDAR point cloud as the input data modality, learns and stores hierarchical latent features in multiple levels of hash tables based on an octree structure, then these multi-scale latent features are decoded into signed distance value through shallow Multilayer Perceptrons (MLPs) in the mapping procedure. For pose estimation procedure, we rely on a correspondence-free, scan-to-implicit matching paradigm to estimate optimal pose and register current scan into the submap. The entire training process is conducted in a self-supervised manner, which waives the model pre-training and manifests its generalizability when applied to diverse environments. Extensive experiments on multiple real-world and synthetic datasets demonstrate the superior performance, in terms of the effectiveness and generalization capabilities, of our Hi-LOAM compared to existing state-of-the-art methods.
### Title:
          Eyes Can't Always Tell: Fusing Eye Tracking and User Priors for User Modeling under AI Advice Conditions
 - **Authors:** Xin Sun, Shu Wei, Ting Pan, Yajing Wang, Jos A. Bosch, Isao Echizen, Abdallah El Ali, Saku Sugawara
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modeling users' cognitive states (e.g., cognitive load and decision confidence) is essential for building adaptive AI in high-stakes decision-making. While eye tracking provides non-invasive behavioral signals correlated with cognitive effort, prior work has not systematically examined how AI assistance contexts, specifically varying advice reliability and user heterogeneity, can alter the mapping between gaze signals and cognitive states. We conducted a within-subject lab eye-tracking study (N=54) on factual verification tasks under three conditions: No-AI, Correct-AI advice, and Incorrect-AI advice. We analyze condition-dependent changes in self-reports and eye-tracking patterns and evaluate the robustness of eye-tracking-based user modeling. Results show that AI advice increases decision confidence compared to No-AI, while Correct-AI is associated with lower perceived cognitive load and more efficient gaze behavior. Crucially, predictive modeling is context-sensitive: the relationship between eye-tracking signals and cognitive states shifts across AI conditions. Finally, fusing eye-tracking features with user priors (demographics, AI literacy/experience, and propensity to trust technology) improves cross-participant generalization. These findings support condition-aware and personalized user modeling for cognitively aligned adaptive AI systems.
### Title:
          Analysis of Efficient Transmission Methods of Grid Maps for Intelligent Vehicles
 - **Authors:** Robin Dehler, Dominik Authaler, Aryan Thakur, Thomas Wodtko, Michael Buchholz
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Grid mapping is a fundamental approach to modeling the environment of intelligent vehicles or robots. Compared with object-based environment modeling, grid maps offer the distinct advantage of representing the environment without requiring any assumptions about objects, such as type or shape. For grid-map-based approaches, the environment is divided into cells, each containing information about its respective area, such as occupancy. This representation of the entire environment is crucial for achieving higher levels of autonomy. However, it has the drawback that modeling the scene at the cell level results in inherently large data sizes. Patched grid maps tackle this issue to a certain extent by adapting cell sizes in specific areas. Nevertheless, the data sizes of patched grid maps are still too large for novel distributed processing setups or vehicle-to-everything (V2X) applications. Our work builds on a patch-based grid-map approach and investigates the size problem from a communication perspective. To address this, we propose a patch-based communication pipeline that leverages existing compression algorithms to transmit grid-map data efficiently. We provide a comprehensive analysis of this pipeline for both intra-vehicle and V2X-based communication. The analysis is verified for these use cases with two real-world experiment setups. Finally, we summarize recommended guidelines for the efficient transmission of grid-map data in intelligent transportation systems.
### Title:
          Hidden Meanings in Plain Sight: RebusBench for Evaluating Cognitive Visual Reasoning
 - **Authors:** Seyed Amir Kasaei, Arash Marioriyad, Mahbod Khaleti, MohammadAmin Fazli, Mahdieh Soleymani Baghshah, Mohammad Hossein Rohban
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Vision-Language Models (LVLMs) have achieved remarkable proficiency in explicit visual recognition, effectively describing what is directly visible in an image. However, a critical cognitive gap emerges when the visual input serves only as a clue rather than the answer. We identify that current models struggle with the complex, multi-step reasoning required to solve problems where information is not explicitly depicted. Successfully solving a rebus puzzle requires a distinct cognitive workflow: the model must extract visual and textual attributes, retrieve linguistic prior knowledge (such as idioms), and perform abstract mapping to synthesize these elements into a meaning that exists outside the pixel space. To evaluate this neurosymbolic capability, we introduce RebusBench, a benchmark of 1,164 puzzles designed to test this specific integration of perception and knowledge. Our evaluation of state-of-the-art models (including Qwen, InternVL, and LLaVA) shows a severe deficiency: performance saturates below 10% Exact Match and 20% semantic accuracy, with no significant improvement observed from model scaling or In-Context Learning (ICL). These findings suggest that while models possess the necessary visual and linguistic components, they lack the cognitive reasoning glue to connect them. Project page available at this https URL.
### Title:
          Domain-constrained knowledge representation: A modal framework
 - **Authors:** Chao Li, Yuru Wang, Chunyi Zhao
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Knowledge graphs store large numbers of relations efficiently, but they remain weak at representing a quieter difficulty: the meaning of a concept often shifts with the domain in which it is used. A triple such as Apple, instance-of, Company may be acceptable in one setting while being misleading or unusable in another. In most current systems, domain information is attached as metadata, qualifiers, or graph-level organization. These mechanisms help with filtering and provenance, but they usually do not alter the formal status of the assertion itself. This paper argues that domain should be treated as part of knowledge representation rather than as supplementary annotation. It introduces the Domain-Contextualized Concept Graph (DCG), a framework in which domain is written into the relation and interpreted as a modal world constraint. In the DCG form (C, R at D, C'), the marker at D identifies the world in which the relation holds. Formally, the relation is interpreted through a domain-indexed necessity operator, so that truth, inference, and conflict checking are all scoped to the relevant world. This move has three consequences: ambiguous concepts can be disambiguated at the point of representation; invalid assertions can be challenged against their domain; cross-domain relations can be connected through explicit predicates. The paper develops this claim through a Kripke-style semantics, a compact predicate system, a Prolog implementation, and mappings to RDF, OWL, and relational databases. The contribution is a representational reinterpretation of domain itself. The central claim is that many practical failures in knowledge systems begin when domain is treated as external to the assertion. DCG addresses that by giving domain a structural and computable role inside the representation.
### Title:
          Architectural Implications of the UK Cyber Security and Resilience Bill
 - **Authors:** Jonathan Shelby
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The UK Cyber Security and Resilience (CS&R) Bill represents the most significant reform of UK cyber legislation since the Network and Information Systems (NIS) Regulations 2018. While existing analysis has addressed the Bill's regulatory requirements, there is a critical gap in guidance on the architectural implications for organisations that must achieve and demonstrate compliance. This paper argues that the CS&R Bill's provisions (expanded scope to managed service providers (MSPs), data centres, and critical suppliers; mandatory 24/72-hour dual incident reporting; supply chain security duties; and Secretary of State powers of direction-), collectively constitute an architectural forcing function that renders perimeter-centric and point-solution security postures structurally non-compliant. We present a systematic mapping of the Bill's key provisions to specific architectural requirements, demonstrate that Zero Trust Architecture (ZTA) provides the most coherent technical foundation for meeting these obligations, and propose a reference architecture and maturity-based adoption pathway for CISOs and security architects. The paper further addresses the cross-regulatory challenge facing UK financial services firms operating under simultaneous CS&R, DORA, and NIS2 obligations, and maps the architectural framework against the NCSC Cyber Assessment Framework v4.0. This work extends a companion practitioner guide to the Bill by translating regulatory analysis into actionable architectural strategy. Keywords: Cyber Security and Resilience Bill, Zero Trust Architecture, Security Architecture, Critical National Infrastructure, NIS Regulations, DORA, Supply Chain Security, NCSC CAF v4.0
### Title:
          Are VLMs Lost Between Sky and Space? LinkS$^2$Bench for UAV-Satellite Dynamic Cross-View Spatial Intelligence
 - **Authors:** Dian Liu, Jie Feng, Di Li, Yuhui Zheng, Guanbin Li, Weisheng Dong, Guangming Shi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synergistic spatial intelligence between UAVs and satellites is indispensable for emergency response and security operations, as it uniquely integrates macro-scale global coverage with dynamic, real-time local perception. However, the capacity of Vision-Language Models (VLMs) to master this complex interplay remains largely unexplored. This gap persists primarily because existing benchmarks are confined to isolated Unmanned Aerial Vehicle (UAV) videos or static satellite imagery, failing to evaluate the dynamic local-to-global spatial mapping essential for comprehensive cross-view reasoning. To bridge this gap, we introduce LinkS$^2$Bench, the first comprehensive benchmark designed to evaluate VLMs' wide-area, dynamic cross-view spatial intelligence. LinkS$^2$Bench links 1,022 minutes of dynamic UAV footage with high-resolution satellite imagery covering over 200 km$^2$. Through an LMM-assisted pipeline and rigorous human annotation, we constructed 17.9k high-quality question-answer pairs comprising 12 fine-grained tasks across four dimensions: perception, localization, relation, and reasoning. Evaluations of 18 representative VLMs reveal a substantial gap compared to human baselines, identifying accurate cross-view dynamic alignment as the critical bottleneck. To alleviate this, we design a Cross-View Alignment Adapter, demonstrating that explicit alignment significantly improves model performance. Furthermore, fine-tuning experiments underscore the potential of LinkS$^2$Bench in advancing VLM adaptation for complex spatial reasoning.
### Title:
          HyVGGT-VO: Tightly Coupled Hybrid Dense Visual Odometry with Feed-Forward Models
 - **Authors:** Junxiang Pan, Lipu Zhou, Baojie Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense visual odometry (VO), which provides pose estimation and dense 3D reconstruction, serves as the cornerstone for applications ranging from robotics to augmented reality. Recently, feed-forward models have demonstrated remarkable capabilities in dense mapping. However, when these models are used in dense visual SLAM systems, their heavy computational burden restricts them to yielding sparse pose outputs at keyframes while still failing to achieve real-time pose estimation. In contrast, traditional sparse methods provide high computational efficiency and high-frequency pose outputs, but lack the capability for dense reconstruction. To address these limitations, we propose HyVGGT-VO, a novel framework that combines the computational efficiency of sparse VO with the dense reconstruction capabilities of feed-forward models. To the best of our knowledge, this is the first work to tightly couple a traditional VO framework with VGGT, a state-of-the-art feed-forward model. Specifically, we design an adaptive hybrid tracking frontend that dynamically switches between traditional optical flow and the VGGT tracking head to ensure robustness. Furthermore, we introduce a hierarchical optimization framework that jointly refines VO poses and the scale of VGGT predictions to ensure global scale consistency. Our approach achieves an approximately 5x processing speedup compared to existing VGGT-based methods, while reducing the average trajectory error by 85% on the indoor EuRoC dataset and 12% on the outdoor KITTI benchmark. Our code will be publicly available upon acceptance. Project page: this https URL.
### Title:
          SEAL: An Open, Auditable, and Fair Data Generation Framework for AI-Native 6G Networks
 - **Authors:** Sunder Ali Khowaja, Kapal Dev, Engin Zeydan, Madhusanka Liyanage
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI-native 6G networks promise to transform the telecom industry by enabling dynamic resource allocation, predictive maintenance, and ultra-reliable low-latency communications across all layers, which are essential for applications such as smart cities, autonomous vehicles, and immersive XR. However, the deployment of 6G systems results in severe data scarcity, hindering the training of efficient AI models. Synthetic data generation is extensively used to fill this gap; however, it introduces challenges related to dataset bias, auditability, and compliance with regulatory frameworks. In this regard, we propose the Synthetic Data Generation with Ethics Audit Loop (SEAL) framework, which extends baseline modular pipelines with an Ethical and Regulatory Compliance by Design (ERCD) module and a Federated Learning (FL) feedback system. The ERCD integrates fairness, bias detection, and standardized audit trails for regulatory mapping, while the FL enables privacy-preserving calibration using aggregated insights from real testbeds to close the reality-simulation gap. Results show that the SEAL framework outperforms existing methods in terms of Frechet Inception Distance, equalized odds, and accuracy. These results validate the framework's ability to generate auditable and bias-mitigated synthetic data for responsible AI-native 6G development.
### Title:
          Neural network methods for two-dimensional finite-source reflector design
 - **Authors:** Roel Hacking, Lisa Kusch, Koondanibha Mitra, Martijn Anthonissen, Wilbert IJzerman
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We address the inverse problem of designing two-dimensional reflectors that transform light from a finite, extended source into a prescribed far-field distribution. We propose a neural network parameterization of the reflector height and develop two differentiable objective functions: (i) a direct change-of-variables loss that pushes the source distribution through the learned inverse mapping, and (ii) a mesh-based loss that maps a target-space grid back to the source, integrates over intersections, and remains continuous even when the source is discontinuous. Gradients are obtained via automatic differentiation and optimized with a robust quasi-Newton method. As a comparison, we formulate a deconvolution baseline built on a simplified finite-source approximation: a 1D monotone mapping is recovered from flux balance, yielding an ordinary differential equation solved in integrating-factor form; this solver is embedded in a modified Van Cittert iteration with nonnegativity clipping and a ray-traced forward operator. Across four benchmarks -- continuous and discontinuous sources, and with/without minimum-height constraints -- we evaluate accuracy by ray-traced normalized mean absolute error (NMAE). Our neural network approach converges faster and achieves consistently lower NMAE than the deconvolution method, and handles height constraints naturally. We discuss how the method may be extended to rotationally symmetric and full three-dimensional settings via iterative correction schemes.
### Title:
          UniDriveVLA: Unifying Understanding, Perception, and Action Planning for Autonomous Driving
 - **Authors:** Yongkang Li, Lijun Zhou, Sixu Yan, Bencheng Liao, Tianyi Yan, Kaixin Xiong, Long Chen, Hongwei Xie, Bing Wang, Guang Chen, Hangjun Ye, Wenyu Liu, Haiyang Sun, Xinggang Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have recently emerged in autonomous driving, with the promise of leveraging rich world knowledge to improve the cognitive capabilities of driving systems. However, adapting such models for driving tasks currently faces a critical dilemma between spatial perception and semantic reasoning. Consequently, existing VLA systems are forced into suboptimal compromises: directly adopting 2D Vision-Language Models yields limited spatial perception, whereas enhancing them with 3D spatial representations often impairs the native reasoning capacity of VLMs. We argue that this dilemma largely stems from the coupled optimization of spatial perception and semantic reasoning within shared model parameters. To overcome this, we propose UniDriveVLA, a Unified Driving Vision-Language-Action model based on Mixture-of-Transformers that addresses the perception-reasoning conflict via expert decoupling. Specifically, it comprises three experts for driving understanding, scene perception, and action planning, which are coordinated through masked joint attention. In addition, we combine a sparse perception paradigm with a three-stage progressive training strategy to improve spatial perception while maintaining semantic reasoning capability. Extensive experiments show that UniDriveVLA achieves state-of-the-art performance in open-loop evaluation on nuScenes and closed-loop evaluation on Bench2Drive. Moreover, it demonstrates strong performance across a broad range of perception, prediction, and understanding tasks, including 3D detection, online mapping, motion forecasting, and driving-oriented VQA, highlighting its broad applicability as a unified model for autonomous driving. Code and model have been released at this https URL
### Title:
          Generative AI Spotlights the Human Core of Data Science: Implications for Education
 - **Authors:** Nathan Taback
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI); Applications (stat.AP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative AI (GAI) reveals an irreducible human core at the center of data science: advances in GAI should sharpen, rather than diminish, the focus on human reasoning in data science education. GAI can now execute many routine data science workflows, including cleaning, summarizing, visualizing, modeling, and drafting reports. Yet the competencies that matter most remain irreducibly human: problem formulation, measurement and design, causal identification, statistical and computational reasoning, ethics and accountability, and sensemaking. Drawing on Donoho's Greater Data Science framework, Nolan and Temple Lang's vision of computational literacy, and the McLuhan-Culkin insight that we shape our tools and thereafter our tools shape us, this paper traces the emergence of data science through three converging lineages: Tukey's intellectual vision of data analysis as a science, the commercial logic of surveillance capitalism that created industrial demand for data scientists, and the academic programs that followed. Mapping GAI's impact onto Donoho's six divisions of Greater Data Science shows that computing with data (GDS3) has been substantially automated, while data gathering, preparation, and exploration (GDS1) and science about data science (GDS6) still require essential human input. The educational implication is that data science curricula should focus on this human core while teaching students how to contribute effectively within iterative prompt-output-prompt cycles using retrieval-augmented generation, and that learning outcomes and assessments should explicitly evaluate reasoning and judgment.
### Title:
          Taming the Exponential: A Fast Softmax Surrogate for Integer-Native Edge Inference
 - **Authors:** Dimitrios Danopoulos, Enrico Lupi, Michael Kagan, Maurizio Pierini
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Softmax can become a computational bottleneck in the Transformer model's Multi-Head Attention (MHA) block, particularly in small models under low-precision inference, where exponentiation and normalization incur significant overhead. As such, we suggest using Head-Calibrated Clipped-Linear Softmax (HCCS), a bounded, monotone surrogate to the exponential softmax function, which uses a clipped linear mapping of the max centered attention logits. This approximation produces a stable probability distribution, maintains the ordering of the original logits and has non-negative values. HCCS differs from previous softmax surrogates as it includes a set of lightweight calibration parameters that are optimized offline based on a representative dataset and calibrated for each individual attention head to preserve the statistical properties of the individual heads. We describe a hardware-motivated implementation of HCCS for high-throughput scenarios targeting the AMD Versal AI Engines. The current reference implementations from AMD for this platform rely upon either bfloat16 arithmetic or LUTs to perform the exponential operation, which might limit the throughput of the platform and fail to utilize the high-throughput integer vector processing units of the AI Engine. In contrast, HCCS provides a natural mapping to the AI Engines' int8 multiply accumulate (MAC) units. To the best of our knowledge, this is the first int8 optimized softmax surrogate for AMD AI engines that significantly exceeds the speed performance of other reference implementations while maintaining competitive task accuracy on small or heavily quantized MHA workloads after quantization-aware retraining.
### Title:
          Modulate-and-Map: Crossmodal Feature Mapping with Cross-View Modulation for 3D Anomaly Detection
 - **Authors:** Alex Costanzino, Pierluigi Zama Ramirez, Giuseppe Lisanti, Luigi Di Stefano
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present ModMap, a natively multiview and multimodal framework for 3D anomaly detection and segmentation. Unlike existing methods that process views independently, our method draws inspiration from the crossmodal feature mapping paradigm to learn to map features across both modalities and views, while explicitly modelling view-dependent relationships through feature-wise modulation. We introduce a cross-view training strategy that leverages all possible view combinations, enabling effective anomaly scoring through multiview ensembling and aggregation. To process high-resolution 3D data, we train and publicly release a foundational depth encoder tailored to industrial datasets. Experiments on SiM3D, a recent benchmark that introduces the first multiview and multimodal setup for 3D anomaly detection and segmentation, demonstrate that ModMap attains state-of-the-art performance by surpassing previous methods by wide margins.
## Keyword: localization
### Title:
          GRAZE: Grounded Refinement and Motion-Aware Zero-Shot Event Localization
 - **Authors:** Syed Ahsan Masud Zaidi, Lior Shamir, William Hsu, Scott Dietrich, Talha Zaidi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 American football practice generates video at scale, yet the interaction of interest occupies only a brief window of each long, untrimmed clip. Reliable biomechanical analysis, therefore, depends on spatiotemporal localization that identifies both the interacting entities and the onset of contact. We study First Point of Contact (FPOC), defined as the first frame in which a player physically touches a tackle dummy, in unconstrained practice footage with camera motion, clutter, multiple similarly equipped athletes, and rapid pose changes around impact. We present GRAZE, a training-free pipeline for FPOC localization that requires no labeled tackle-contact examples. GRAZE uses Grounding DINO to discover candidate player-dummy interactions, refines them with motion-aware temporal reasoning, and uses SAM2 as an explicit pixel-level verifier of contact rather than relying on detection confidence alone. This separation between candidate discovery and contact confirmation makes the approach robust to cluttered scenes and unstable grounding near impact. On 738 tackle-practice videos, GRAZE produces valid outputs for 97.4% of clips and localizes FPOC within $\pm$ 10 frames on 77.5% of all clips and within $\pm$ 20 frames on 82.7% of all clips. These results show that frame-accurate contact onset localization in real-world practice footage is feasible without task-specific training.
### Title:
          Robust Autonomous Control of a Magnetic Millirobot in In Vitro Cardiac Flow
 - **Authors:** Anuruddha Bhattacharjee, Xinhao Chen, Lamar O. Mair, Suraj Raval, Yancy Diaz-Mercado, Axel Krieger
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Untethered magnetic millirobots offer significant potential for minimally invasive cardiac therapies; however, achieving reliable autonomous control in pulsatile cardiac flow remains challenging. This work presents a vision-guided control framework enabling precise autonomous navigation of a magnetic millirobot in an in vitro heart phantom under physiologically relevant flow conditions. The system integrates UNet-based localization, A* path planning, and a sliding mode controller with a disturbance observer (SMC-DOB) designed for multi-coil electromagnetic actuation. Although drag forces are estimated using steady-state CFD simulations, the controller compensates for transient pulsatile disturbances during closed-loop operation. In static fluid, the SMC-DOB achieved sub-millimeter accuracy (root-mean-square error, RMSE = 0.49 mm), outperforming PID and MPC baselines. Under moderate pulsatile flow (7 cm/s peak, 20 cP), it reduced RMSE by 37% and peak error by 2.4$\times$ compared to PID. It further maintained RMSE below 2 mm (0.27 body lengths) under elevated pulsatile flow (10 cm/s peak, 20 cP) and under low-viscosity conditions (4.3 cP, 7 cm/s peak), where baseline controllers exhibited unstable or failed tracking. These results demonstrate robust closed-loop magnetic control under time-varying cardiac flow disturbances and support the feasibility of autonomous millirobot navigation for targeted drug delivery.
### Title:
          VideoZeroBench: Probing the Limits of Video MLLMs with Spatio-Temporal Evidence Verification
 - **Authors:** Jiahao Meng, Tan Yue, Qi Xu, Haochen Wang, Zhongwei Ren, Weisong Liu, Yuhao Wang, Renrui Zhang, Yunhai Tong, Haodong Duan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent video multimodal large language models achieve impressive results across various benchmarks. However, current evaluations suffer from two critical limitations: (1) inflated scores can mask deficiencies in fine-grained visual understanding and reasoning, and (2) answer correctness is often measured without verifying whether models identify the precise spatio-temporal evidence supporting their predictions. To address this, we present VideoZeroBench, a hierarchical benchmark designed for challenging long-video question answering that rigorously verifies spatio-temporal evidence. It comprises 500 manually annotated questions across 13 domains, paired with temporal intervals and spatial bounding boxes as evidence. To disentangle answering generation, temporal grounding, and spatial grounding, we introduce a five-level evaluation protocol that progressively tightens evidence requirements. Experiments show that even Gemini-3-Pro correctly answers fewer than 17% of questions under the standard end-to-end QA setting (Level-3). When grounding constraints are imposed, performance drops sharply: No model exceeds 1% accuracy when both correct answering and accurate spatio-temporal localization are required (Level-5), with most failing to achieve any correct grounded predictions. These results expose a significant gap between surface-level answer correctness and genuine evidence-based reasoning, revealing that grounded video understanding remains a bottleneck for long-video QA. We further analyze performance across minimal evidence spans, atomic abilities, and inference paradigms, providing insights for future research in grounded video reasoning. The benchmark and code will be made publicly available.
### Title:
          Satellite-Free Training for Drone-View Geo-Localization
 - **Authors:** Tao Liu, Yingzhi Zhang, Kan Ren, Xiaoqi Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Drone-view geo-localization (DVGL) aims to determine the location of drones in GPS-denied environments by retrieving the corresponding geotagged satellite tile from a reference gallery given UAV observations of a location. In many existing formulations, these observations are represented by a single oblique UAV image. In contrast, our satellite-free setting is designed for multi-view UAV sequences, which are used to construct a geometry-normalized UAV-side location representation before cross-view retrieval. Existing approaches rely on satellite imagery during training, either through paired supervision or unsupervised alignment, which limits practical deployment when satellite data are unavailable or restricted. In this paper, we propose a satellite-free training (SFT) framework that converts drone imagery into cross-view compatible representations through three main stages: drone-side 3D scene reconstruction, geometry-based pseudo-orthophoto generation, and satellite-free feature aggregation for retrieval. Specifically, we first reconstruct dense 3D scenes from multi-view drone images using 3D Gaussian splatting and project the reconstructed geometry into pseudo-orthophotos via PCA-guided orthographic projection. This rendering stage operates directly on reconstructed scene geometry without requiring camera parameters at rendering time. Next, we refine these orthophotos with lightweight geometry-guided inpainting to obtain texture-complete drone-side views. Finally, we extract DINOv3 patch features from the generated orthophotos, learn a Fisher vector aggregation model solely from drone data, and reuse it at test time to encode satellite tiles for cross-view retrieval. Experimental results on University-1652 and SUES-200 show that our SFT framework substantially outperforms satellite-free generalization baselines and narrows the gap to methods trained with satellite imagery.
### Title:
          Riemannian and Symplectic Geometry for Hierarchical Text-Driven Place Recognition
 - **Authors:** Tianyi Shang, Zhenyu Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-point-cloud localization enables robots to understand spatial positions through natural language descriptions, which is crucial for human-robot collaboration in applications such as autonomous driving and last-mile delivery. However, existing methods employ pooled global descriptors for similarity retrieval, which suffer from severe information loss and fail to capture discriminative scene structures. To address these issues, we propose SympLoc, a novel coarse-to-fine localization framework with multi-level alignment in the coarse stage. Different from previous methods that rely solely on global descriptors, our coarse stage consists of three complementary alignment levels: 1) Instance-level alignment establishes direct correspondence between individual object instances in point clouds and textual hints through Riemannian self-attention in hyperbolic space; 2) Relation-level alignment explicitly models pairwise spatial relationships between objects using the Information-Symplectic Relation Encoder (ISRE), which reformulates relation features through Fisher-Rao metric and Hamiltonian dynamics for uncertainty-aware geometrically consistent propagation; 3) Global-level alignment synthesizes discriminative global descriptors via the Spectral Manifold Transform (SMT) that extracts structural invariants through graph spectral analysis. This hierarchical alignment strategy progressively captures fine-grained to coarse-grained scene semantics, enabling robust cross-modal retrieval. Extensive experiments on the KITTI360Pose dataset demonstrate that SympLoc achieves a 19% improvement in Top-1 recall@10m compared to existing state-of-the-art approaches.
### Title:
          OSCAR: Orchestrated Self-verification and Cross-path Refinement
 - **Authors:** Yash Shah, Abhijit Chakraborty, Naresh Kumar Devulapally, Vishnu Lokhande, Vivek Gupta
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion language models (DLMs) expose their denoising trajectories, offering a natural handle for inference-time control; accordingly, an ideal hallucination mitigation framework should intervene during generation using this model-native signal rather than relying on an externally trained hallucination classifier. Toward this, we formulate commitment uncertainty localization: given a denoising trajectory, identify token positions whose cross-chain entropy exceeds an unsupervised threshold before factually unreliable commitments propagate into self-consistent but incorrect outputs. We introduce a suite of trajectory-level assessments, including a cross-chain divergence-at-hallucination (CDH) metric, for principled comparison of localization methods. We also introduce OSCAR, a training-free inference-time framework operationalizing this formulation. OSCAR runs N parallel denoising chains with randomized reveal orders, computes cross-chain Shannon entropy to detect high-uncertainty positions, and then performs targeted remasking conditioned on retrieved evidence. Ablations confirm that localization and correction contribute complementary gains, robust across N in {4, 8, 16}. On TriviaQA, HotpotQA, RAGTruth, and CommonsenseQA using LLaDA-8B and Dream-7B, OSCAR enhances generation quality by significantly reducing hallucinated content and improving factual accuracy through uncertainty-guided remasking, which also facilitates more effective integration of retrieved evidence. Its native entropy-based uncertainty signal surpasses that of specialized trained detectors, highlighting an inherent capacity of diffusion language models to identify factual uncertainty that is not present in the sequential token commitment structure of autoregressive models. We are releasing the codebase1 to support future research on localization and uncertainty-aware generation in DLMs.
### Title:
          TOL: Textual Localization with OpenStreetMap
 - **Authors:** Youqi Liao, Shuhao Kang, Jingyu Xu, Olaf Wysocki, Yan Xia, Jianping Li, Zhen Dong, Bisheng Yang, Xieyuanli Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Natural language provides an intuitive way to express spatial intent in geospatial applications. While existing localization methods often rely on dense point cloud maps or high-resolution imagery, OpenStreetMap (OSM) offers a compact and freely available map representation that encodes rich semantic and structural information, making it well suited for large-scale localization. However, text-to-OSM (T2O) localization remains largely unexplored. In this paper, we formulate the T2O global localization task, which aims to estimate accurate 2 degree-of-freedom (DoF) positions in urban environments from textual scene descriptions without relying on geometric observations or GNSS-based initial location. To support the proposed task, we introduce TOL, a large-scale benchmark spanning multiple continents and diverse urban environments. TOL contains approximately 121K textual queries paired with OSM map tiles and covers about 316 km of road trajectories across Boston, Karlsruhe, and Singapore. We further propose TOLoc, a coarse-to-fine localization framework that explicitly models the semantics of surrounding objects and their directional information. In the coarse stage, direction-aware features are extracted from both textual descriptions and OSM tiles to construct global descriptors, which are used to retrieve candidate locations for the query. In the fine stage, the query text and top-1 retrieved tile are jointly processed, where a dedicated alignment module fuses textual descriptor and local map features to regress the 2-DoF pose. Experimental results demonstrate that TOLoc achieves strong localization performance, outperforming the best existing method by 6.53%, 9.93%, and 8.31% at 5m, 10m, and 25m thresholds, respectively, and shows strong generalization to unseen environments. Dataset, code and models will be publicly available at: this https URL.
### Title:
          GPA: Learning GUI Process Automation from Demonstrations
 - **Authors:** Zirui Zhao, Jun Hao Liew, Yan Yang, Wenzhuo Yang, Ziyang Luo, Doyen Sahoo, Silvio Savarese, Junnan Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 GUI Process Automation (GPA) is a lightweight but general vision-based Robotic Process Automation (RPA), which enables fast and stable process replay with only a single demo. Addressing the fragility of traditional RPA and the non-deterministic risks of current vision language model-based GUI agents, GPA introduces three core benefits: (1) Robustness via Sequential Monte Carlo-based localization to handle rescaling and detection uncertainty; (2) Deterministic and Reliability safeguarded by readiness calibration; and (3) Privacy through fast, fully local execution. This approach delivers the adaptability, robustness, and security required for enterprise workflows. It can also be used as an MCP/CLI tool by other agents with coding capabilities so that the agent only reasons and orchestrates while GPA handles the GUI execution. We conducted a pilot experiment to compare GPA with Gemini 3 Pro (with CUA tools) and found that GPA achieves higher success rate with 10 times faster execution speed in finishing long-horizon GUI tasks.
### Title:
          3-D Relative Localization for Multi-Robot Systems with Angle and Self-Displacement Measurements
 - **Authors:** Chenyang Liang, Liangming Chen, Baoyi Cui, Jie Mei
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Realizing relative localization by leveraging inter-robot local measurements is a challenging problem, especially in the presence of measurement noise. Motivated by this challenge, in this paper we propose a novel and systematic 3-D relative localization framework based on inter-robot interior angle and self-displacement measurements. Initially, we propose a linear relative localization theory comprising a distributed linear relative localization algorithm and sufficient conditions for localizability. According to this theory, robots can determine their neighbors' relative positions and orientations in a purely linear manner. Subsequently, in order to deal with measurement noise, we present an advanced Maximum a Posterior (MAP) estimator by addressing three primary challenges existing in the MAP estimator. Firstly, it is common to formulate the MAP problem as an optimization problem, whose inherent non-convexity can result in local optima. To address this issue, we reformulate the linear computation process of the linear relative localization algorithm as a Weighted Total Least Squares (WTLS) optimization problem on manifolds. The optimal solution of the WTLS problem is more accurate, which can then be used as initial values when solving the optimization problem associated with the MAP problem, thereby reducing the risk of falling into local optima. The second challenge is the lack of knowledge of the prior probability density of the robots' relative positions and orientations at the initial time, which is required as an input for the MAP estimator. To deal with it, we combine the WTLS with a Neural Density Estimator (NDE). Thirdly, to prevent the increasing size of the relative positions and orientations to be estimated as the robots continuously move when solving the MAP problem, a marginalization mechanism is designed, which ensures that the computational cost remains constant.
### Title:
          Hi-LOAM: Hierarchical Implicit Neural Fields for LiDAR Odometry and Mapping
 - **Authors:** Zhiliu Yang, Jianyuan Zhang, Lianhui Zhao, Jinyu Dai, Zhu Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR Odometry and Mapping (LOAM) is a pivotal technique for embodied-AI applications such as autonomous driving and robot navigation. Most existing LOAM frameworks are either contingent on the supervision signal, or lack of the reconstruction fidelity, which are deficient in depicting details of large-scale complex scenes. To overcome these limitations, we propose a multi-scale implicit neural localization and mapping framework using LiDAR sensor, called Hi-LOAM. Hi-LOAM receives LiDAR point cloud as the input data modality, learns and stores hierarchical latent features in multiple levels of hash tables based on an octree structure, then these multi-scale latent features are decoded into signed distance value through shallow Multilayer Perceptrons (MLPs) in the mapping procedure. For pose estimation procedure, we rely on a correspondence-free, scan-to-implicit matching paradigm to estimate optimal pose and register current scan into the submap. The entire training process is conducted in a self-supervised manner, which waives the model pre-training and manifests its generalizability when applied to diverse environments. Extensive experiments on multiple real-world and synthetic datasets demonstrate the superior performance, in terms of the effectiveness and generalization capabilities, of our Hi-LOAM compared to existing state-of-the-art methods.
### Title:
          Unifying UAV Cross-View Geo-Localization via 3D Geometric Perception
 - **Authors:** Haoyuan Li, Wen Yang, Fang Xu, Hong Tan, Haijian Zhang, Shengyang Li, Gui-Song Xia
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view geo-localization for Unmanned Aerial Vehicles (UAVs) operating in GNSS-denied environments remains challenging due to the severe geometric discrepancy between oblique UAV imagery and orthogonal satellite maps. Most existing methods address this problem through a decoupled pipeline of place retrieval and pose estimation, implicitly treating perspective distortion as appearance noise rather than an explicit geometric transformation. In this work, we propose a geometry-aware UAV geo-localization framework that explicitly models the 3D scene geometry to unify coarse place recognition and fine-grained pose estimation within a single inference pipeline. Our approach reconstructs a local 3D scene from multi-view UAV image sequences using a Visual Geometry Grounded Transformer (VGGT), and renders a virtual Bird's-Eye View (BEV) representation that orthorectifies the UAV perspective to align with satellite imagery. This BEV serves as a geometric intermediary that enables robust cross-view retrieval and provides spatial priors for accurate 3 Degrees of Freedom (3-DoF) pose regression. To efficiently handle multiple location hypotheses, we introduce a Satellite-wise Attention Block that isolates the interaction between each satellite candidate and the reconstructed UAV scene, preventing inter-candidate interference while maintaining linear computational complexity. In addition, we release a recalibrated version of the University-1652 dataset with precise coordinate annotations and spatial overlap analysis, enabling rigorous evaluation of end-to-end localization accuracy. Extensive experiments on the refined University-1652 benchmark and SUES-200 demonstrate that our method significantly outperforms state-of-the-art baselines, achieving robust meter-level localization accuracy and improved generalization in complex urban environments.
### Title:
          Tree-Adaptive Multiscale Kernel Lasso in Samplet Coordinates
 - **Authors:** Sara Avesani, Gaia Fumagalli, Michael Multerer, Chiara Segala
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We develop a novel framework for sparse multiscale kernel approximation of large scattered data problems based on a samplet representation. Samplets form a multiresolution analysis of localized discrete signed measures and enable quasi-sparse representations of kernel matrices associated to asymptotically smooth kernels as well as smoothness detection of scattered data. Building on the latter, we introduce an adaptive data site selection strategy based on the localization of the native reproducing kernel Hilbert space norm in the samplet expansion coefficients. The selection results in a small set of representative data sites, significantly reducing the effective problem size. On the corresponding reduced kernel subspace, we solve an $\ell^1$-regularized least-squares problem using a trust-region semismooth Newton method in a normal-map formulation, stabilized by an online low-rank SVD on the active set to handle the notorious ill-conditioning of kernel matrices. Numerical experiments in two and three dimensions, including multi-kernel models with varying lengthscales, demonstrate that the proposed approach achieves accurate reconstructions with considerably sparser representations and good computational efficiency.
### Title:
          Combining Boundary Supervision and Segment-Level Regularization for Fine-Grained Action Segmentation
 - **Authors:** Hinako Mitsuoka, Kazuhiro Hotta
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in Temporal Action Segmentation (TAS) has increasingly relied on complex architectures, which can hinder practical deployment. We present a lightweight dual-loss training framework that improves fine-grained segmentation quality with only one additional output channel and two auxiliary loss terms, requiring minimal architectural modification. Our approach combines a boundary-regression loss that promotes accurate temporal localization via a single-channel boundary prediction and a CDF-based segment-level regularization loss that encourages coherent within-segment structure by matching cumulative distributions over predicted and ground-truth segments. The framework is architecture-agnostic and can be integrated into existing TAS models (e.g., MS-TCN, C2F-TCN, FACT) as a training-time loss function. Across three benchmark datasets, the proposed method improves segment-level consistency and boundary quality, yielding higher F1 and Edit scores across three different models. Frame-wise accuracy remains largely unchanged, highlighting that precise segmentation can be achieved through simple loss design rather than heavier architectures or inference-time refinements.
### Title:
          ProVG: Progressive Visual Grounding via Language Decoupling for Remote Sensing Imagery
 - **Authors:** Ke Li, Ting Wang, Di Wang, Yongshan Zhu, Yiming Zhang, Tao Lei, Quan Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote sensing visual grounding (RSVG) aims to localize objects in remote sensing imagery according to natural language expressions. Previous methods typically rely on sentence-level vision-language alignment, which struggles to exploit fine-grained linguistic cues, such as \textit{spatial relations} and \textit{object attributes}, that are crucial for distinguishing objects with similar characteristics. Importantly, these cues play distinct roles across different grounding stages and should be leveraged accordingly to provide more explicit guidance. In this work, we propose \textbf{ProVG}, a novel RSVG framework that improves localization accuracy by decoupling language expressions into global context, spatial relations, and object attributes. To integrate these linguistic cues, ProVG employs a simple yet effective progressive cross-modal modulator, which dynamically modulates visual attention through a \textit{survey-locate-verify} scheme, enabling coarse-to-fine vision-language alignment. In addition, ProVG incorporates a cross-scale fusion module to mitigate the large-scale variations in remote sensing imagery, along with a language-guided calibration decoder to refine cross-modal alignment during prediction. A unified multi-task head further enables ProVG to support both referring expression comprehension and segmentation tasks. Extensive experiments on two benchmarks, \textit{i.e.}, RRSIS-D and RISBench, demonstrate that ProVG consistently outperforms existing methods, achieving new state-of-the-art performance.
### Title:
          Enhancing Medical Visual Grounding via Knowledge-guided Spatial Prompts
 - **Authors:** Yifan Gao, Tao Zhou, Yi Zhou, Ke Zou, Yizhe Zhang, Huazhu Fu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medical Visual Grounding (MVG) aims to identify diagnostically relevant phrases from free-text radiology reports and localize their corresponding regions in medical images, providing interpretable visual evidence to support clinical decision-making. Although recent Vision-Language Models (VLMs) exhibit promising multimodal reasoning ability, their grounding remains insufficient spatial precision, largely due to a lack of explicit localization priors when relying solely on latent embeddings. In this work, we analyze this limitation from an attention perspective and propose KnowMVG, a Knowledge-prior and global-local attention enhancement framework for MVG in VLMs that explicitly strengthens spatial awareness during decoding. Specifically, we present a knowledge-enhanced prompting strategy that encodes phrase related medical knowledge into compact embeddings, together with a global-local attention that jointly leverages coarse global information and refined local cues to guide precise region localization. localization. This design bridges high-level semantic understanding and fine-grained visual perception without introducing extra textual reasoning overhead. Extensive experiments on four MVG benchmarks demonstrate that our KnowMVG consistently outperforms existing approaches, achieving gains of 3.0% in AP50 and 2.6% in mIoU over prior state-of-the-art methods. Qualitative and ablation studies further validate the effectiveness of each component.
### Title:
          GenGait: A Transformer-Based Model for Human Gait Anomaly Detection and Normative Twin Generation
 - **Authors:** Elisa Motta, Marta Lorenzini, Clara Mouawad, Alberto Ranavolo, Mariano Serrao, Arash Ajoudani
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gait analysis provides an objective characterization of locomotor function and is widely used to support diagnosis and rehabilitation monitoring across neurological and orthopedic disorders. Deep learning has been increasingly applied to this domain, yet most approaches rely on supervised classifiers trained on disease-labeled data, limiting generalization to heterogeneous pathological presentations. This work proposes a label-free framework for joint-level anomaly detection and kinematic correction based on a Transformer masked autoencoder trained exclusively on normative gait sequences from 150 adults, acquired with a markerless multi-camera motion-capture system. At inference, a two-pass procedure is applied to potentially pathological input sequences, first it estimates joint inconsistency scores by occluding individual joints and measuring deviations from the learned normative prior. Then, it withholds the flagged joints from the encoder input and reconstructs the full skeleton from the remaining spatiotemporal context, yielding corrected kinematic trajectories at the flagged positions. Validation on 10 held-out normative participants, who mimicked seven simulated gait abnormalities, showed accurate localization of biomechanically inconsistent joints, a significant reduction in angular deviation across all analyzed joints with large effect sizes, and preservation of normative kinematics. The proposed approach enables interpretable, subject-specific localization of gait impairments without requiring disease labels. Video is available at this https URL.
### Title:
          Are VLMs Lost Between Sky and Space? LinkS$^2$Bench for UAV-Satellite Dynamic Cross-View Spatial Intelligence
 - **Authors:** Dian Liu, Jie Feng, Di Li, Yuhui Zheng, Guanbin Li, Weisheng Dong, Guangming Shi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synergistic spatial intelligence between UAVs and satellites is indispensable for emergency response and security operations, as it uniquely integrates macro-scale global coverage with dynamic, real-time local perception. However, the capacity of Vision-Language Models (VLMs) to master this complex interplay remains largely unexplored. This gap persists primarily because existing benchmarks are confined to isolated Unmanned Aerial Vehicle (UAV) videos or static satellite imagery, failing to evaluate the dynamic local-to-global spatial mapping essential for comprehensive cross-view reasoning. To bridge this gap, we introduce LinkS$^2$Bench, the first comprehensive benchmark designed to evaluate VLMs' wide-area, dynamic cross-view spatial intelligence. LinkS$^2$Bench links 1,022 minutes of dynamic UAV footage with high-resolution satellite imagery covering over 200 km$^2$. Through an LMM-assisted pipeline and rigorous human annotation, we constructed 17.9k high-quality question-answer pairs comprising 12 fine-grained tasks across four dimensions: perception, localization, relation, and reasoning. Evaluations of 18 representative VLMs reveal a substantial gap compared to human baselines, identifying accurate cross-view dynamic alignment as the critical bottleneck. To alleviate this, we design a Cross-View Alignment Adapter, demonstrating that explicit alignment significantly improves model performance. Furthermore, fine-tuning experiments underscore the potential of LinkS$^2$Bench in advancing VLM adaptation for complex spatial reasoning.
### Title:
          Center-Aware Detection with Swin-based Co-DETR Framework for Cervical Cytology
 - **Authors:** Yan Kong, Yuan Yin, Hongan Chen, Yuqi Fang, Caifeng Shan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated analysis of Pap smear images is critical for cervical cancer screening but remains challenging due to dense cell distribution and complex morphology. In this paper, we present our winning solution for the RIVA Cervical Cytology Challenge, achieving 1st place in Track B and 2nd place in Track A. Our approach leverages a powerful baseline, integrating the Co-DINO framework with a Swin-Large backbone for robust multi-scale feature extraction. To address the dataset's unique fixed-size bounding box annotations, we formulate the detection task as a center-point prediction problem. Tailoring our approach to this formulation, we introduce a center-preserving data augmentation strategy and an analytical geometric box optimization to effectively absorb localization jitter. Finally, we apply track-specific loss tuning to adapt the loss weights for each task. Experiments demonstrate that our targeted optimizations improve detection performance, providing an effective pipeline for cytology image analysis. Our code is available at this https URL.
### Title:
          GroundVTS: Visual Token Sampling in Multimodal Large Language Models for Video Temporal Grounding
 - **Authors:** Rong Fan, Kaiyan Xiao, Minghao Zhu, Liuyi Wang, Kai Dai, Zhao Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video temporal grounding (VTG) is a critical task in video understanding and a key capability for extending video large language models (Vid-LLMs) to broader applications. However, existing Vid-LLMs rely on uniform frame sampling to extract video information, resulting in a sparse distribution of key frames and the loss of crucial temporal cues. To address this limitation, we propose Grounded Visual Token Sampling (GroundVTS), a Vid-LLM architecture that focuses on the most informative temporal segments. GroundVTS employs a fine-grained, query-guided mechanism to filter visual tokens before feeding them into the LLM, thereby preserving essential spatio-temporal information and maintaining temporal coherence. Futhermore, we introduce a progressive optimization strategy that enables the LLM to effectively adapt to the non-uniform distribution of visual features, enhancing its ability to model temporal dependencies and achieve precise video localization. We comprehensively evaluate GroundVTS on three standard VTG benchmarks, where it outperforms existing methods, achieving a 7.7-point improvement in mIoU for moment retrieval and 12.0-point improvement in mAP for highlight detection. Code is available at this https URL.
### Title:
          Deep Neural Network Based Roadwork Detection for Autonomous Driving
 - **Authors:** Sebastian Wullrich, Nicolai Steinke, Daniel Goehring
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Road construction sites create major challenges for both autonomous vehicles and human drivers due to their highly dynamic and heterogeneous nature. This paper presents a real-time system that detects and localizes roadworks by combining a YOLO neural network with LiDAR data. The system identifies individual roadwork objects while driving, merges them into coherent construction sites and records their outlines in world coordinates. The model training was based on an adapted US dataset and a new dataset collected from test drives with a prototype vehicle in Berlin, Germany. Evaluations on real-world road construction sites showed a localization accuracy below 0.5 m. The system can support traffic authorities with up-to-date roadwork data and could enable autonomous vehicles to navigate construction sites more safely in the future.
## Keyword: transformer
### Title:
          ViTs for Action Classification in Videos: An Approach to Risky Tackle Detection in American Football Practice Videos
 - **Authors:** Syed Ahsan Masud Zaidi, William Hsu, Scott Dietrich
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Early identification of hazardous actions in contact sports enables timely intervention and improves player safety. We present a method for detecting risky tackles in American football practice videos and introduce a substantially expanded dataset for this task. Our work contains 733 single-athlete-dummy tackle clips, each temporally localized around first point contact and labeled with a strike zone component of the standardized Assessment for Tackling Technique (SATT-3), extending prior work that reported 178 annotated videos. Using a Vision transformer-based model with imbalance-aware training, we obtain risky recall of 0.67 and Risky F1 of 0.59 under crossvalidation. Relative to the previous baseline in a smaller subset (risky recall of 0.58; Risky F1 0.56 ), our approach improves risky recall by more than 8% points on a much larger dataset. These results indicate that the vision transformer-based video analysis, coupled with careful handling of class imbalance, can reliably detect rare but safety-critical tackling patterns, offering a practical pathway toward coach-centered injury prevention tools.
### Title:
          Regularizing Attention Scores with Bootstrapping
 - **Authors:** Neo Christopher Chung, Maxim Laletin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Methodology (stat.ME); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision transformers (ViT) rely on attention mechanism to weigh input features, and therefore attention scores have naturally been considered as explanations for its decision-making process. However, attention scores are almost always non-zero, resulting in noisy and diffused attention maps and limiting interpretability. Can we quantify uncertainty measures of attention scores and obtain regularized attention scores? To this end, we consider attention scores of ViT in a statistical framework where independent noise would lead to insignificant yet non-zero scores. Leveraging statistical learning techniques, we introduce the bootstrapping for attention scores which generates a baseline distribution of attention scores by resampling input features. Such a bootstrap distribution is then used to estimate significances and posterior probabilities of attention scores. In natural and medical images, the proposed \emph{Attention Regularization} approach demonstrates a straightforward removal of spurious attention arising from noise, drastically improving shrinkage and sparsity. Quantitative evaluations are conducted using both simulation and real-world datasets. Our study highlights bootstrapping as a practical regularization tool when using attention scores as explanations for ViT. Code available: this https URL
### Title:
          EgoFlow: Gradient-Guided Flow Matching for Egocentric 6DoF Object Motion Generation
 - **Authors:** Abhishek Saroha, Huajian Zeng, Xingxing Zuo, Daniel Cremers, Xi Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding and predicting object motion from egocentric video is fundamental to embodied perception and interaction. However, generating physically consistent 6DoF trajectories remains challenging due to occlusions, fast motion, and the lack of explicit physical reasoning in existing generative models. We present EgoFlow, a flow-matching framework that synthesizes realistic and physically plausible trajectories conditioned on multimodal egocentric observations. EgoFlow employs a hybrid Mamba-Transformer-Perceiver architecture to jointly model temporal dynamics, scene geometry, and semantic intent, while a gradient-guided inference process enforces differentiable physical constraints such as collision avoidance and motion smoothness. This combination yields coherent and controllable motion generation without post-hoc filtering or additional supervision. Experiments on real-world datasets HD-EPIC, EgoExo4D, and HOT3D show that EgoFlow outperforms diffusion-based and transformer baselines in accuracy, generalization, and physical realism, reducing collision rates by up to 79%, and strong generalization to unseen scenes. Our results highlight the promise of flow-based generative modeling for scalable and physically grounded egocentric motion understanding.
### Title:
          Efficient Equivariant Transformer for Self-Driving Agent Modeling
 - **Authors:** Scott Xu, Dian Chen, Kelvin Wong, Chris Zhang, Kion Fallah, Raquel Urtasun
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurately modeling agent behaviors is an important task in self-driving. It is also a task with many symmetries, such as equivariance to the order of agents and objects in the scene or equivariance to arbitrary roto-translations of the entire scene as a whole; i.e., SE(2)-equivariance. The transformer architecture is a ubiquitous tool for modeling these symmetries. While standard self-attention is inherently permutation equivariant, explicit pairwise relative positional encodings have been the standard for introducing SE(2)-equivariance. However, this approach introduces an additional cost that is quadratic in the number of agents, limiting its scalability to larger scenes and batch sizes. In this work, we propose DriveGATr, a novel transformer-based architecture for agent modeling that achieves SE(2)-equivariance without the computational cost of existing methods. Inspired by recent advances in geometric deep learning, DriveGATr encodes scene elements as multivectors in the 2D projective geometric algebra $\mathbb{R}^*_{2,0,1}$ and processes them with a stack of equivariant transformer blocks. Crucially, DriveGATr models geometric relationships using standard attention between multivectors, eliminating the need for costly explicit pairwise relative positional encodings. Experiments on the Waymo Open Motion Dataset demonstrate that DriveGATr is comparable to the state-of-the-art in traffic simulation and establishes a superior Pareto front for performance vs computational cost.
### Title:
          Prototype-Based Low Altitude UAV Semantic Segmentation
 - **Authors:** Da Zhang, Gao Junyu, Zhao Zhiyuan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic segmentation of low-altitude UAV imagery presents unique challenges due to extreme scale variations, complex object boundaries, and limited computational resources on edge devices. Existing transformer-based segmentation methods achieve remarkable performance but incur high computational overhead, while lightweight approaches struggle to capture fine-grained details in high-resolution aerial scenes. To address these limitations, we propose PBSeg, an efficient prototype-based segmentation framework tailored for UAV applications. PBSeg introduces a novel prototype-based cross-attention (PBCA) that exploits feature redundancy to reduce computational complexity while maintaining segmentation quality. The framework incorporates an efficient multi-scale feature extraction module that combines deformable convolutions (DConv) with context-aware modulation (CAM) to capture both local details and global semantics. Experiments on two challenging UAV datasets demonstrate the effectiveness of the proposed approach. PBSeg achieves 71.86\% mIoU on UAVid and 80.92\% mIoU on UDD6, establishing competitive performance while maintaining computational efficiency. Code is available at this https URL.
### Title:
          Thinking While Listening: Fast-Slow Recurrence for Long-Horizon Sequential Modeling
 - **Authors:** Shota Takashiro, Masanori Koyama, Takeru Miyato, Yusuke Iwasawa, Yutaka Matsuo, Kohei Hayashi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We extend the recent latent recurrent modeling to sequential input streams. By interleaving fast, recurrent latent updates with self-organizational ability between slow observation updates, our method facilitates the learning of stable internal structures that evolve alongside the input. This mechanism allows the model to maintain coherent and clustered representations over long horizons, improving out-of-distribution generalization in reinforcement learning and algorithmic tasks compared to sequential baselines such as LSTM, state space models, and Transformer variants.
### Title:
          NEMESIS: Noise-suppressed Efficient MAE with Enhanced Superpatch Integration Strategy
 - **Authors:** Kyeonghun Kim, Hyeonseok Jung, Youngung Han, Hyunsu Go, Eunseob Choi, Seongbin Park, Junsu Lim, Jiwon Yang, Sumin Lee, Insung Hwang, Ken Ying-Kai Liao, Nam-Joon Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Volumetric CT imaging is essential for clinical diagnosis, yet annotating 3D volumes is expensive and time-consuming, motivating self-supervised learning (SSL) from unlabeled data. However, applying SSL to 3D CT remains challenging due to the high memory cost of full-volume transformers and the anisotropic spatial structure of CT data, which is not well captured by conventional masking strategies. We propose NEMESIS, a masked autoencoder (MAE) framework that operates on local 128x128x128 superpatches, enabling memory-efficient training while preserving anatomical detail. NEMESIS introduces three key components: (i) noise-enhanced reconstruction as a pretext task, (ii) Masked Anatomical Transformer Blocks (MATB) that perform dual-masking through parallel plane-wise and axis-wise token removal, and (iii) NEMESIS Tokens (NT) for cross-scale context aggregation. On the BTCV multi-organ classification benchmark, NEMESIS with a frozen backbone and a linear classifier achieves a mean AUROC of 0.9633, surpassing fully fine-tuned SuPreM (0.9493) and VoCo (0.9387). Under a low-label regime with only 10% of available annotations, it retains an AUROC of 0.9075, demonstrating strong label efficiency. Furthermore, the superpatch-based design reduces computational cost to 31.0 GFLOPs per forward pass, compared to 985.8 GFLOPs for the full-volume baseline, providing a scalable and robust foundation for 3D medical imaging.
### Title:
          Transformer self-attention encoder-decoder with multimodal deep learning for response time series forecasting and digital twin support in wind structural health monitoring
 - **Authors:** Feiyu Zhou, Marios Impraimakis
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Signal Processing (eess.SP); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The wind-induced structural response forecasting capabilities of a novel transformer methodology are examined here. The model also provides a digital twin component for bridge structural health monitoring. Firstly, the approach uses the temporal characteristics of the system to train a forecasting model. Secondly, the vibration predictions are compared to the measured ones to detect large deviations. Finally, the identified cases are used as an early-warning indicator of structural change. The artificial intelligence-based model outperforms approaches for response forecasting as no assumption on wind stationarity or on structural normal vibration behavior is needed. Specifically, wind-excited dynamic behavior suffers from uncertainty related to obtaining poor predictions when the environmental or traffic conditions change. This results in a hard distinction of what constitutes normal vibration behavior. To this end, a framework is rigorously examined on real-world measurements from the Hardanger Bridge monitored by the Norwegian University of Science and Technology. The approach captures accurate structural behavior in realistic conditions, and with respect to the changes in the system excitation. The results, importantly, highlight the potential of transformer-based digital twin components to serve as next-generation tools for resilient infrastructure management, continuous learning, and adaptive monitoring over the system's lifecycle with respect to temporal characteristics.
### Title:
          MATA-Former & SIICU: Semantic Aware Temporal Alignment for High-Fidelity ICU Risk Prediction
 - **Authors:** Zhichong Zheng, Xiaohang Nie, Xueqi Wang, Yuanjin Zhao, Haitao Zhang, Yichao Tang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Forecasting evolving clinical risks relies on intrinsic pathological dependencies rather than mere chronological proximity, yet current methods struggle with coarse binary supervision and physical timestamps. To align predictive modeling with clinical logic, we propose the Medical-semantics Aware Time-ALiBi Transformer (MATA-Former), utilizing event semantics to dynamically parameterize attention weights to prioritize causal validity over time lags. Furthermore, we introduce Plateau-Gaussian Soft Labeling (PSL), reformulating binary classification into continuous multi-horizon regression for full-trajectory risk modeling. Evaluated on SIICU -- a newly constructed dataset featuring over 506k events with rigorous expert-verified, fine-grained annotations -- and the MIMIC-IV dataset, our framework demonstrates superior efficacy and robust generalization in capturing risks from text-intensive, irregular clinical time series.
### Title:
          Unifying UAV Cross-View Geo-Localization via 3D Geometric Perception
 - **Authors:** Haoyuan Li, Wen Yang, Fang Xu, Hong Tan, Haijian Zhang, Shengyang Li, Gui-Song Xia
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view geo-localization for Unmanned Aerial Vehicles (UAVs) operating in GNSS-denied environments remains challenging due to the severe geometric discrepancy between oblique UAV imagery and orthogonal satellite maps. Most existing methods address this problem through a decoupled pipeline of place retrieval and pose estimation, implicitly treating perspective distortion as appearance noise rather than an explicit geometric transformation. In this work, we propose a geometry-aware UAV geo-localization framework that explicitly models the 3D scene geometry to unify coarse place recognition and fine-grained pose estimation within a single inference pipeline. Our approach reconstructs a local 3D scene from multi-view UAV image sequences using a Visual Geometry Grounded Transformer (VGGT), and renders a virtual Bird's-Eye View (BEV) representation that orthorectifies the UAV perspective to align with satellite imagery. This BEV serves as a geometric intermediary that enables robust cross-view retrieval and provides spatial priors for accurate 3 Degrees of Freedom (3-DoF) pose regression. To efficiently handle multiple location hypotheses, we introduce a Satellite-wise Attention Block that isolates the interaction between each satellite candidate and the reconstructed UAV scene, preventing inter-candidate interference while maintaining linear computational complexity. In addition, we release a recalibrated version of the University-1652 dataset with precise coordinate annotations and spatial overlap analysis, enabling rigorous evaluation of end-to-end localization accuracy. Extensive experiments on the refined University-1652 benchmark and SUES-200 demonstrate that our method significantly outperforms state-of-the-art baselines, achieving robust meter-level localization accuracy and improved generalization in complex urban environments.
### Title:
          Attention Mechanisms Through the Lens of Numerical Methods: Approximation Methods and Alternative Formulations
 - **Authors:** Michel Fabrice Serret, Alice Cortinovis, Yijun Dong, Diana Halikias, Anna Ma, Fabio Matti, Deanna Needell, Katherine J. Pearce, Elizaveta Rebrova, Disha Shur, Rudi Smith, Hai-Xiao Wang, Laura Grigori
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The attention mechanism is the computational core of modern Transformer architectures, but its quadratic complexity in the input sequence length is the bottleneck for large-scale inference. This has motivated a rapidly growing body of work aimed at accelerating attention through approximation and reformulation. In this survey, we revisit attention mechanisms through the lens of numerical analysis, with a particular emphasis on tools and perspectives from numerical linear algebra. Our goal is twofold: first, we aim to systematically review and classify fast approximation methods according to the numerical principles they exploit. These include sparsity and clustering approaches, low-rank and subspace projection techniques, randomized sketching methods, and tensor-based decompositions. We also discuss kernel-inspired reformulations of attention and recent architectural variants, such as Latent Attention, that modify the standard softmax formulation to improve efficiency. Second, by presenting these developments within a unified mathematical framework, we aim to bridge the gap between disciplines and highlight opportunities for further contributions from computational mathematics, particularly numerical linear algebra, to the design of scalable attention mechanisms.
### Title:
          Cosine-Normalized Attention for Hyperspectral Image Classification
 - **Authors:** Muhammad Ahmad, Manuel Mazzara
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based methods have improved hyperspectral image classification (HSIC) by modeling long-range spatial-spectral dependencies; however, their attention mechanisms typically rely on dot-product similarity, which mixes feature magnitude and orientation and may be suboptimal for hyperspectral data. This work revisits attention scoring from a geometric perspective and introduces a cosine-normalized attention formulation that aligns similarity computation with the angular structure of hyperspectral signatures. By projecting query and key embeddings onto a unit hypersphere and applying a squared cosine similarity, the proposed method emphasizes angular relationships while reducing sensitivity to magnitude variations. The formulation is integrated into a spatial-spectral Transformer and evaluated under extremely limited supervision. Experiments on three benchmark datasets demonstrate that the proposed approach consistently achieves higher performance, outperforming several recent Transformer- and Mamba-based models despite using a lightweight backbone. In addition, a controlled analysis of multiple attention score functions shows that cosine-based scoring provides a reliable inductive bias for hyperspectral representation learning.
### Title:
          SafeRoPE: Risk-specific Head-wise Embedding Rotation for Safe Generation in Rectified Flow Transformers
 - **Authors:** Xiang Yang, Feifei Li, Mi Zhang, Geng Hong, Xiaoyu You, Min Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent Text-to-Image (T2I) models based on rectified-flow transformers (e.g., SD3, FLUX) achieve high generative fidelity but remain vulnerable to unsafe semantics, especially when triggered by multi-token interactions. Existing mitigation methods largely rely on fine-tuning or attention modulation for concept unlearning; however, their expensive computational overhead and design tailored to U-Net-based denoisers hinder direct adaptation to transformer-based diffusion models (e.g., MMDiT). In this paper, we conduct an in-depth analysis of the attention mechanism in MMDiT and find that unsafe semantics concentrate within interpretable, low-dimensional subspaces at head level, where a finite set of safety-critical heads is responsible for unsafe feature extraction. We further observe that perturbing the Rotary Positional Embedding (RoPE) applied to the query and key vectors can effectively modify some specific concepts in the generated images. Motivated by these insights, we propose SafeRoPE, a lightweight and fine-grained safe generation framework for MMDiT. Specifically, SafeRoPE first constructs head-wise unsafe subspaces by decomposing unsafe embeddings within safety-critical heads, and computes a Latent Risk Score (LRS) for each input vector via projection onto these subspaces. We then introduce head-wise RoPE perturbations that can suppress unsafe semantics without degrading benign content or image quality. SafeRoPE combines both head-wise LRS and RoPE perturbations to perform risk-specific head-wise rotation on query and key vector embeddings, enabling precise suppression of unsafe outputs while maintaining generation fidelity. Extensive experiments demonstrate that SafeRoPE achieves SOTA performance in balancing effective harmful content mitigation and utility preservation for safe generation of MMDiT. Codes are available at this https URL.
### Title:
          Semantic Segmentation of Textured Non-manifold 3D Meshes using Transformers
 - **Authors:** Mohammadreza Heidarianbaei, Max Mehltretter, Franz Rottensteiner
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Textured 3D meshes jointly represent geometry, topology, and appearance, yet their irregular structure poses significant challenges for deep-learning-based semantic segmentation. While a few recent methods operate directly on meshes without imposing geometric constraints, they typically overlook the rich textural information also provided by such meshes. We introduce a texture-aware transformer that learns directly from raw pixels associated with each mesh face, coupled with a new hierarchical learning scheme for multi-scale feature aggregation. A texture branch summarizes all face-level pixels into a learnable token, which is fused with geometrical descriptors and processed by a stack of Two-Stage Transformer Blocks (TSTB), which allow for both a local and a global information flow. We evaluate our model on the Semantic Urban Meshes (SUM) benchmark and a newly curated cultural-heritage dataset comprising textured roof tiles with triangle-level annotations for damage types. Our method achieves 81.9\% mF1 and 94.3\% OA on SUM and 49.7\% mF1 and 72.8\% OA on the new dataset, substantially outperforming existing approaches.
### Title:
          DDCL-INCRT: A Self-Organising Transformer with Hierarchical Prototype Structure (Theoretical Foundations)
 - **Authors:** Giansalvo Cirrincione
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern neural networks of the transformer family require the practitioner to decide, before training begins, how many attention heads to use, how deep the network should be, and how wide each component should be. These decisions are made without knowledge of the task, producing architectures that are systematically larger than necessary: empirical studies find that a substantial fraction of heads and layers can be removed after training without performance loss. This paper introduces DDCL-INCRT, an architecture that determines its own structure during training. Two complementary ideas are combined. The first, DDCL (Deep Dual Competitive Learning), replaces the feedforward block with a dictionary of learned prototype vectors representing the most informative directions in the data. The prototypes spread apart automatically, driven by the training objective, without explicit regularisation. The second, INCRT (Incremental Transformer), controls the number of heads: starting from one, it adds a new head only when the directional information uncaptured by existing heads exceeds a threshold. The main theoretical finding is that these two mechanisms reinforce each other: each new head amplifies prototype separation, which in turn raises the signal triggering the next addition. At convergence, the network self-organises into a hierarchy of heads ordered by representational granularity. This hierarchical structure is proved to be unique and minimal, the smallest architecture sufficient for the task, under the stated conditions. Formal guarantees of stability, convergence, and pruning safety are established throughout. The architecture is not something one designs. It is something one derives.
### Title:
          SURE: Synergistic Uncertainty-aware Reasoning for Multimodal Emotion Recognition in Conversations
 - **Authors:** Yiqiang Cai, Chengyan Wu, Bolei Ma, Bo Chen, Yun Xue, Julia Hirschberg, Ziwei Gong
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal emotion recognition in conversations (MERC) requires integrating multimodal signals while being robust to noise and modeling contextual reasoning. Existing approaches often emphasize fusion but overlook uncertainty in noisy features and fine-grained reasoning. We propose SURE (Synergistic Uncertainty-aware REasoning) for MERC, a framework that improves robustness and contextual modeling. SURE consists of three components: an Uncertainty-Aware Mixture-of-Experts module to handle modality-specific noise, an Iterative Reasoning module for multi-turn reasoning over context, and a Transformer Gate module to capture intra- and inter-modal interactions. Experiments on benchmark MERC datasets show that SURE consistently outperforms state-of-the-art methods, demonstrating its effectiveness in robust multimodal reasoning. These results highlight the importance of uncertainty modeling and iterative reasoning in advancing emotion recognition in conversational settings.
### Title:
          Is Clinical Text Enough? A Multimodal Study on Mortality Prediction in Heart Failure Patients
 - **Authors:** Oumaima El Khettari, Virgile Barthet, Guillaume Hocquet, Joconde Weller, Emmanuel Morin, Pierre Zweigenbaum
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate short-term mortality prediction in heart failure (HF) remains challenging, particularly when relying on structured electronic health record (EHR) data alone. We evaluate transformer-based models on a French HF cohort, comparing text-only, structured-only, multimodal, and LLM-based approaches. Our results show that enriching clinical text with entity-level representations improves prediction over CLS embeddings alone, and that supervised multimodal fusion of text and structured variables achieves the best overall performance. In contrast, large language models perform inconsistently across modalities and decoding strategies, with text-only prompts outperforming structured or multimodal inputs. These findings highlight that entity-aware multimodal transformers offer the most reliable solution for short-term HF outcome prediction, while current LLM prompting remains limited for clinical decision support.
### Title:
          A Data-Aided Power Transformer Differential Protection without Inrush Blocking Module
 - **Authors:** Zexuan Lin, Songhao Yang, Yubo Zhang, Zhiguo Hao, Baohui Zhang
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When a slightly faulty transformer closes without load, the current waveform presents the coexistence of inrush and fault current. At this time, the inrush blocking module will block the relay, which may delay the removal of the slight fault and lead to more serious faults. To address this problem, this paper proposes a data-aided power transformer differential protection without inrush blocking module. The key to eliminating the negative influence of inrush current is to extract the fundamental component from the non-inrush part of the current waveform, which corresponds to the unsaturation period of the transformer core. Firstly, a data-aided module, namely an Attention module embedded Fully Convolutional Network (A-FCN), is built to distinguish the inrush and non-inrush parts of the current waveform. Then, a physical model of the current waveform is built for the non-inrush part, and the fundamental component is extracted by the nonlinear least square (NLS) algorithm. The proposed method can avoid the block of differential protections when inrush current occurs, which improves the sensitivity and rapidity of the relay, especially in the case of a weak internal fault hidden in inrush current. Finally, simulation and experimental data verify the effectiveness and generalization of the proposed method.
### Title:
          Physics-Informed Transformer for Multi-Band Channel Frequency Response Reconstruction
 - **Authors:** Anatolij Zubow, Joana Angjo, Sigrid Dimce, Falko Dressler
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wideband channel frequency response (CFR) estimation is challenging in multi-band wireless systems, especially when one or more sub-bands are temporarily blocked by co-channel interference. We present a physics-informed complex Transformer that reconstructs the full wideband CFR from such fragmented, partially observed spectrum snapshots. The interference pattern in each sub-band is modeled as an independent two-state discrete-time Markov chain, capturing realistic bursty occupancy behavior. Our model operates on the joint time-frequency grid of $T$ snapshots and $F$ frequency bins and uses a factored self-attention mechanism that separately attends along both axes, reducing the computational complexity to $O(TF^2 + FT^2)$. Complex-valued inputs and outputs are processed through a holomorphic linear layer that preserves phase relationships. Training uses a composite physics-informed loss combining spectral fidelity, power delay profile (PDP) reconstruction, channel impulse response (CIR) sparsity, and temporal smoothness. Mobility effects are incorporated through per-sample velocity randomization, enabling generalization across different mobility regimes. Evaluation against three classical baselines, namely, last-observation-carry-forward, zero-fill, and cubic-spline interpolation, shows that our approach achieves the highest PDP similarity with respect to the ground truth, reaching $\rho \geq 0.82$ compared to $\rho \geq 0.62$ for the best baseline at interference occupancy levels up to 50%. Furthermore, the model degrades smoothly across the full velocity range, consistently outperforming all other baselines.
### Title:
          Curia-2: Scaling Self-Supervised Learning for Radiology Foundation Models
 - **Authors:** Antoine Saporta, Baptiste Callard, Corentin Dancette, Julien Khlaut, Charles Corbière, Leo Butsanets, Amaury Prat, Pierre Manceron
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid growth of medical imaging has fueled the development of Foundation Models (FMs) to reduce the growing, unsustainable workload on radiologists. While recent FMs have shown the power of large-scale pre-training to CT and MRI analysis, there remains significant room to optimize how these models learn from complex radiological volumes. Building upon the Curia framework, this work introduces Curia-2, which significantly improves the original pre-training strategy and representation quality to better capture the specificities of radiological data. The proposed methodology enables scaling the architecture up to billion-parameter Vision Transformers, marking a first for multi-modal CT and MRI FMs. Furthermore, we formalize the evaluation of these models by extending and restructuring CuriaBench into two distinct tracks: a 2D track tailored for slice-based vision models and a 3D track for volumetric benchmarking. Our results demonstrate that Curia-2 outperforms all FMs on vision-focused tasks and fairs competitively to vision-language models on clinically complex tasks such as finding detection. Weights will be made publicly available to foster further research.
### Title:
          GenGait: A Transformer-Based Model for Human Gait Anomaly Detection and Normative Twin Generation
 - **Authors:** Elisa Motta, Marta Lorenzini, Clara Mouawad, Alberto Ranavolo, Mariano Serrao, Arash Ajoudani
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gait analysis provides an objective characterization of locomotor function and is widely used to support diagnosis and rehabilitation monitoring across neurological and orthopedic disorders. Deep learning has been increasingly applied to this domain, yet most approaches rely on supervised classifiers trained on disease-labeled data, limiting generalization to heterogeneous pathological presentations. This work proposes a label-free framework for joint-level anomaly detection and kinematic correction based on a Transformer masked autoencoder trained exclusively on normative gait sequences from 150 adults, acquired with a markerless multi-camera motion-capture system. At inference, a two-pass procedure is applied to potentially pathological input sequences, first it estimates joint inconsistency scores by occluding individual joints and measuring deviations from the learned normative prior. Then, it withholds the flagged joints from the encoder input and reconstructs the full skeleton from the remaining spatiotemporal context, yielding corrected kinematic trajectories at the flagged positions. Validation on 10 held-out normative participants, who mimicked seven simulated gait abnormalities, showed accurate localization of biomechanically inconsistent joints, a significant reduction in angular deviation across all analyzed joints with large effect sizes, and preservation of normative kinematics. The proposed approach enables interpretable, subject-specific localization of gait impairments without requiring disease labels. Video is available at this https URL.
### Title:
          Test-Time Adaptation for Height Completion via Self-Supervised ViT Features and Monocular Foundation Models
 - **Authors:** Osher Rafaeli, Tal Svoray, Ariel Nahlieli
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate digital surface models (DSMs) are essential for many geospatial applications, including urban monitoring, environmental analyses, infrastructure management, and change detection. However, large-scale DSMs frequently contain incomplete or outdated regions due to acquisition limitations, reconstruction artifacts, or changes in the built environment. Traditional height completion approaches primarily rely on spatial interpolation or which assume spatial continuity and therefore fail when objects are missing. Recent learning-based approaches improve reconstruction quality but typically require supervised training on sensor-specific datasets, limiting their generalization across domains and sensing conditions. We propose Prior2DSM, a training-free framework for metric DSM completion that operates entirely at test time by leveraging foundation models. Unlike previous height completion approaches that require task-specific training, the proposed method combines self-supervised Vision Transformer (ViT) features from DINOv3 with monocular depth foundation models to propagate metric information from incomplete height priors through semantic feature-space correspondence. Test-time adaptation (TTA) is performed using parameter-efficient low-rank adaptation (LoRA) together with a lightweight multilayer perceptron (MLP), which predicts spatially varying scale and shift parameters to convert relative depth estimates into metric heights. Experiments demonstrate consistent improvements over interpolation based methods, prior-based rescaling height approaches, and state-of-the-art monocular depth estimation models. Prior2DSM reduces reconstruction error while preserving structural fidelity, achieving up to a 46% reduction in RMSE compared to linear fitting of MDE, and further enables DSM updating and coupled RGB-DSM generation.
### Title:
          Ouroboros: Dynamic Weight Generation for Recursive Transformers via Input-Conditioned LoRA Modulation
 - **Authors:** Jaber Jaber, Osama Jaber
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recursive transformers reuse a shared weight block across multiple depth steps, trading parameters for compute. A core limitation: every step applies the same transformation, preventing the model from composing distinct operations across depth. We present Ouroboros, a system that attaches a compact Controller hypernetwork to a recursive transformer block. The Controller observes the current hidden state, produces a per-step diagonal modulation vector, and applies it to frozen SVD-initialized LoRA bases, making each recurrence step input-dependent. We combine this with gated recurrence (bias-initialized to 88% retention) and per-step LayerNorm for stable deep iteration. On Qwen2.5-3B split into a Prelude/Recurrent/Coda architecture (17 of 36 layers retained), Ouroboros reduces training loss by 43.4% over the unmodified 17-layer baseline, recovering 51.3% of the performance gap caused by layer removal. The full system adds only 9.2M trainable parameters (Controller, gate, and per-step norms) yet outperforms equivalently-sized static per-step LoRA by 1.44 loss points at depth 1 and remains ahead across all tested depths (1, 4, 8, 16) and ranks (8, 32, 64). We also find that gated recurrence is essential: without it, recursive layer application makes the model strictly worse. These gains are measured on the training distribution; on held-out text, the Controller does not yet improve over the baseline, a limitation we attribute to frozen downstream layers and discuss in detail. Code: this https URL
### Title:
          CASHG: Context-Aware Stylized Online Handwriting Generation
 - **Authors:** Jinsu Shin, Sungeun Hong, Jin Yeong Bak
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online handwriting represents strokes as time-ordered trajectories, which makes handwritten content easier to transform and reuse in a wide range of applications. However, generating natural sentence-level online handwriting that faithfully reflects a writer's style remains challenging, since sentence synthesis demands context-dependent characters with stroke continuity and spacing. Prior methods treat these boundary properties as implicit outcomes of sequence modeling, which becomes unreliable at the sentence scale and under limited compositional diversity. We propose CASHG, a context-aware stylized online handwriting generator that explicitly models inter-character connectivity for style-consistent sentence-level trajectory synthesis. CASHG uses a Character Context Encoder to obtain character identity and sentence-dependent context memory and fuses them in a bigram-aware sliding-window Transformer decoder that emphasizes local predecessor--current transitions, complemented by gated context fusion for sentence-level this http URL proceeds through a three-stage curriculum from isolated glyphs to full sentences, improving robustness under sparse transition coverage. We further introduce Connectivity and Spacing Metrics (CSM), a boundary-aware evaluation suite that quantifies cursive connectivity and spacing similarity. Under benchmark-matched evaluation protocols, CASHG consistently improves CSM over comparison methods while remaining competitive in DTW-based trajectory similarity, with gains corroborated by a human evaluation.
### Title:
          AA-SVD : Anchored and Adaptive SVD for Large Language Model Compression
 - **Authors:** Atul Kumar Sinha, François Fleuret
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a fast low-rank factorization-based framework for compressing large language models that enables rapid compression of billion-parameter models without retraining. Unlike existing factorization-based approaches that optimize only on the original inputs, ignoring distribution shifts from upstream compression and thus propagating errors forward, or those that rely only on shifted inputs and risk drifting away from the original outputs, our approach accounts for both. Beyond individual layer compression, we further refine each transformer block end-to-end, minimizing block-level output distortion and allowing compressed layers to jointly compensate for accumulated errors. By anchoring each compressed layer to the original outputs while explicitly modeling input distribution shifts, our method finds a low-rank approximation that maintains functional equivalence with the original model. Experiments on large language models show that our method consistently outperforms existing SVD-based baselines across compression ratios, with the advantage becoming increasingly pronounced at aggressive compression budgets, where competing methods degrade substantially or collapse entirely, offering a practical solution for efficient, large-scale model deployment.
### Title:
          AEGIS: Adversarial Entropy-Guided Immune System -- Thermodynamic State Space Models for Zero-Day Network Evasion Detection
 - **Authors:** Vickson Ferrel
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As TLS 1.3 encryption limits traditional Deep Packet Inspection (DPI), the security community has pivoted to Euclidean Transformer-based classifiers (e.g., ET-BERT) for encrypted traffic analysis. However, these models remain vulnerable to byte-level adversarial morphing -- recent pre-padding attacks reduced ET-BERT accuracy to 25.68%, while VLESS Reality bypasses certificate-based detection entirely. We introduce AEGIS: an Adversarial Entropy-Guided Immune System powered by a Thermodynamic Variance-Guided Hyperbolic Liquid State Space Model (TVD-HL-SSM). Rather than competing in the Euclidean payload-reading domain, AEGIS discards payload bytes in favor of 6-dimensional continuous-time flow physics projected into a non-Euclidean Poincare manifold. Liquid Time-Constants measure microsecond IAT decay, and a Thermodynamic Variance Detector computes sequence-wide Shannon Entropy to expose automated C2 tunnel anomalies. A pure C++ eBPF Harvester with zero-copy IPC bypasses the Python GIL, enabling a linear-time O(N) Mamba-3 core to process 64,000-packet swarms at line-rate. Evaluated on a 400GB, 4-tier adversarial corpus spanning backbone traffic, IoT botnets, zero-days, and proprietary VLESS Reality tunnels, AEGIS achieves an F1-score of 0.9952 and 99.50% True Positive Rate at 262 us inference latency on an RTX 4090, establishing a new state-of-the-art for physics-based adversarial network defense.
### Title:
          Transformer-Accelerated Interpolated Data-Driven Reachability Analysis from Noisy Data
 - **Authors:** Zhen Zhang, Ahmad Hafez, Peng Xie, Yanliang Huang, Wenyuan Wu, Amr Alanwar
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data-driven reachability analysis provides guaranteed outer approximations of reachable sets from input-state measurements, yet each propagation step requires a matrix-zonotope multiplication whose cost grows with the horizon length, limiting scalability. We observe that data-driven propagation is inherently step-size sensitive, in the sense that set-valued operators at different discretization resolutions yield non-equivalent reachable sets at the same physical time, a property absent in model-based propagation. Exploiting this multi-resolution structure, we propose Interpolated Reachability Analysis (IRA), which computes a sparse chain of coarse anchor sets sequentially and reconstructs fine-resolution intermediate sets in parallel across coarse intervals. We derive a fully data-driven coarse-noise over-approximation that removes the need for continuous-time system knowledge, prove deterministic outer-approximation guarantees for all interpolated sets, and establish conditional tightness relative to the fine-resolution chain. To replace the remaining matrix-zonotope multiplications in the fine phase, we further develop Transformer-Accelerated IRA (TA-IRA), where an encoder-decoder Transformer is calibrated via split conformal prediction to provide finite-sample pointwise and path-wise coverage certificates. Numerical experiments on a five-dimensional linear system confirm the theoretical guarantees and demonstrate significant computational savings.
### Title:
          Transformer-Enhanced Data-Driven Output Reachability with Conformal Coverage Guarantees
 - **Authors:** Zhen Zhang, Peng Xie, Wenyuan Wu, Yanliang Huang, Amr Alanwar
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper considers output reachability analysis for linear time-invariant systems with unknown state-space matrices and unknown observation map, given only noisy input-output measurements. The Cayley--Hamilton theorem is applied to eliminate the latent state algebraically, producing an autoregressive input-output model whose parameter uncertainty is enclosed in a matrix zonotope. Set-valued propagation of this model yields output reachable sets with deterministic containment guarantees under a bounded aggregated residual assumption. The conservatism inherent in the lifted matrix-zonotope product is then mitigated by a decoder-only Transformer trained on labels obtained through directional contraction of the formal envelope via an exterior non-reachability certificate. Split conformal prediction restores distribution-free coverage at both per-step and trajectory levels without access to the true reachable-set hull. The framework is validated on a five-dimensional system with multiple unknown observation matrices.
### Title:
          ViT-Explainer: An Interactive Walkthrough of the Vision Transformer Pipeline
 - **Authors:** Juan Manuel Hernandez, Mariana Fernandez-Espinosa, Denis Parra, Diego Gomez-Zara
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based architectures have become the shared backbone of natural language processing and computer vision. However, understanding how these models operate remains challenging, particularly in vision settings, where images are processed as sequences of patch tokens. Existing interpretability tools often focus on isolated components or expert-oriented analysis, leaving a gap in guided, end-to-end understanding of the full inference pipeline. To bridge this gap, we present ViT-Explainer, a web-based interactive system that provides an integrated visualization of Vision Transformer inference, from patch tokenization to final classification. The system combines animated walkthroughs, patch-level attention overlays, and a vision-adapted Logit Lens within both guided and free exploration modes. A user study with six participants suggests that ViT-Explainer is easy to learn and use, helping users interpret and understand Vision Transformer behavior.
### Title:
          UniDriveVLA: Unifying Understanding, Perception, and Action Planning for Autonomous Driving
 - **Authors:** Yongkang Li, Lijun Zhou, Sixu Yan, Bencheng Liao, Tianyi Yan, Kaixin Xiong, Long Chen, Hongwei Xie, Bing Wang, Guang Chen, Hangjun Ye, Wenyu Liu, Haiyang Sun, Xinggang Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have recently emerged in autonomous driving, with the promise of leveraging rich world knowledge to improve the cognitive capabilities of driving systems. However, adapting such models for driving tasks currently faces a critical dilemma between spatial perception and semantic reasoning. Consequently, existing VLA systems are forced into suboptimal compromises: directly adopting 2D Vision-Language Models yields limited spatial perception, whereas enhancing them with 3D spatial representations often impairs the native reasoning capacity of VLMs. We argue that this dilemma largely stems from the coupled optimization of spatial perception and semantic reasoning within shared model parameters. To overcome this, we propose UniDriveVLA, a Unified Driving Vision-Language-Action model based on Mixture-of-Transformers that addresses the perception-reasoning conflict via expert decoupling. Specifically, it comprises three experts for driving understanding, scene perception, and action planning, which are coordinated through masked joint attention. In addition, we combine a sparse perception paradigm with a three-stage progressive training strategy to improve spatial perception while maintaining semantic reasoning capability. Extensive experiments show that UniDriveVLA achieves state-of-the-art performance in open-loop evaluation on nuScenes and closed-loop evaluation on Bench2Drive. Moreover, it demonstrates strong performance across a broad range of perception, prediction, and understanding tasks, including 3D detection, online mapping, motion forecasting, and driving-oriented VQA, highlighting its broad applicability as a unified model for autonomous driving. Code and model have been released at this https URL
### Title:
          VISTA: Visualization of Token Attribution via Efficient Analysis
 - **Authors:** Syed Ahmed, Bharathi Vokkaliga Ganesh, Jagadish Babu P, Karthick Selvaraj, Praneeth Talluri, Sanket Hingne, Anubhav Kumar, Anushka Yadav, Pratham Kumar Verma, Kiranmayee Janardhan, Mandanna A N
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding how Large Language Models (LLMs) process information from prompts remains a significant challenge. To shed light on this "black box," attention visualization techniques have been developed to capture neuron-level perceptions and interpret how models focus on different parts of input data. However, many existing techniques are tailored to specific model architectures, particularly within the Transformer family, and often require backpropagation, resulting in nearly double the GPU memory usage and increased computational cost. A lightweight, model-agnostic approach for attention visualization remains lacking. In this paper, we introduce a model-agnostic token importance visualization technique to better understand how generative AI systems perceive and prioritize information from input text, without incurring additional computational cost. Our method leverages perturbation-based strategies combined with a three-matrix analytical framework to generate relevance maps that illustrate token-level contributions to model predictions. The framework comprises: (1) the Angular Deviation Matrix, which captures shifts in semantic direction; (2) the Magnitude Deviation Matrix, which measures changes in semantic intensity; and (3) the Dimensional Importance Matrix, which evaluates contributions across individual vector dimensions. By systematically removing each token and measuring the resulting impact across these three complementary dimensions, we derive a composite importance score that provides a nuanced and mathematically grounded measure of token significance. To support reproducibility and foster wider adoption, we provide open-source implementations of all proposed and utilized explainability techniques, with code and resources publicly available at this https URL
### Title:
          SPAR: Single-Pass Any-Resolution ViT for Open-vocabulary Segmentation
 - **Authors:** Naomi Kombol, Ivan Martinović, Siniša Šegvić, Giorgos Tolias
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundational Vision Transformers (ViTs) have limited effectiveness in tasks requiring fine-grained spatial understanding, due to their fixed pre-training resolution and inherently coarse patch-level representations. These challenges are especially pronounced in dense prediction scenarios, such as open-vocabulary segmentation with ViT-based vision-language models, where high-resolution inputs are essential for accurate pixel-level reasoning. Existing approaches typically process large-resolution images using a sliding-window strategy at the pre-training resolution. While this improves accuracy through finer strides, it comes at a significant computational cost. We introduce SPAR: Single-Pass Any-Resolution ViT, a resolution-agnostic dense feature extractor designed for efficient high-resolution inference. We distill the spatial reasoning capabilities of a finely-strided, sliding-window teacher into a single-pass student using a feature regression loss, without requiring architectural changes or pixel-level supervision. Applied to open-vocabulary segmentation, SPAR improves single-pass baselines by up to 10.5 mIoU and even surpasses the teacher, demonstrating effectiveness in efficient, high-resolution reasoning. Code: this https URL
### Title:
          Crystalite: A Lightweight Transformer for Efficient Crystal Modeling
 - **Authors:** Tin Hadži Veljković, Joshua Rosenthal, Ivor Lončarić, Jan-Willem van de Meent
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative models for crystalline materials often rely on equivariant graph neural networks, which capture geometric structure well but are costly to train and slow to sample. We present Crystalite, a lightweight diffusion Transformer for crystal modeling built around two simple inductive biases. The first is Subatomic Tokenization, a compact chemically structured atom representation that replaces high-dimensional one-hot encodings and is better suited to continuous diffusion. The second is the Geometry Enhancement Module (GEM), which injects periodic minimum-image pair geometry directly into attention through additive geometric biases. Together, these components preserve the simplicity and efficiency of a standard Transformer while making it better matched to the structure of crystalline materials. Crystalite achieves state-of-the-art results on crystal structure prediction benchmarks, and de novo generation performance, attaining the best S.U.N. discovery score among the evaluated baselines while sampling substantially faster than geometry-heavy alternatives.
### Title:
          Taming the Exponential: A Fast Softmax Surrogate for Integer-Native Edge Inference
 - **Authors:** Dimitrios Danopoulos, Enrico Lupi, Michael Kagan, Maurizio Pierini
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Softmax can become a computational bottleneck in the Transformer model's Multi-Head Attention (MHA) block, particularly in small models under low-precision inference, where exponentiation and normalization incur significant overhead. As such, we suggest using Head-Calibrated Clipped-Linear Softmax (HCCS), a bounded, monotone surrogate to the exponential softmax function, which uses a clipped linear mapping of the max centered attention logits. This approximation produces a stable probability distribution, maintains the ordering of the original logits and has non-negative values. HCCS differs from previous softmax surrogates as it includes a set of lightweight calibration parameters that are optimized offline based on a representative dataset and calibrated for each individual attention head to preserve the statistical properties of the individual heads. We describe a hardware-motivated implementation of HCCS for high-throughput scenarios targeting the AMD Versal AI Engines. The current reference implementations from AMD for this platform rely upon either bfloat16 arithmetic or LUTs to perform the exponential operation, which might limit the throughput of the platform and fail to utilize the high-throughput integer vector processing units of the AI Engine. In contrast, HCCS provides a natural mapping to the AI Engines' int8 multiply accumulate (MAC) units. To the best of our knowledge, this is the first int8 optimized softmax surrogate for AMD AI engines that significantly exceeds the speed performance of other reference implementations while maintaining competitive task accuracy on small or heavily quantized MHA workloads after quantization-aware retraining.
### Title:
          Steerable Visual Representations
 - **Authors:** Jona Ruthardt, Manu Gaur, Deva Ramanan, Makarand Tapaswi, Yuki M. Asano
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pretrained Vision Transformers (ViTs) such as DINOv2 and MAE provide generic image features that can be applied to a variety of downstream tasks such as retrieval, classification, and segmentation. However, such representations tend to focus on the most salient visual cues in the image, with no way to direct them toward less prominent concepts of interest. In contrast, Multimodal LLMs can be guided with textual prompts, but the resulting representations tend to be language-centric and lose their effectiveness for generic visual tasks. To address this, we introduce Steerable Visual Representations, a new class of visual representations, whose global and local features can be steered with natural language. While most vision-language models (e.g., CLIP) fuse text with visual features after encoding (late fusion), we inject text directly into the layers of the visual encoder (early fusion) via lightweight cross-attention. We introduce benchmarks for measuring representational steerability, and demonstrate that our steerable visual features can focus on any desired objects in an image while preserving the underlying representation quality. Our method also matches or outperforms dedicated approaches on anomaly detection and personalized object discrimination, exhibiting zero-shot generalization to out-of-distribution tasks.
## Keyword: autonomous driving
### Title:
          Simulating Realistic LiDAR Data Under Adverse Weather for Autonomous Vehicles: A Physics-Informed Learning Approach
 - **Authors:** Vivek Anand, Bharat Lohani, Rakesh Mishra, Gaurav Pandey
 - **Subjects:** Subjects:
Robotics (cs.RO); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate LiDAR simulation is crucial for autonomous driving, especially under adverse weather conditions. Existing methods struggle to capture the complex interactions between LiDAR signals and atmospheric phenomena, leading to unrealistic representations. This paper presents a physics-informed learning framework (PICWGAN) for generating realistic LiDAR data under adverse weather conditions. By integrating physicsdriven constraints for modeling signal attenuation and geometryconsistent degradations into a physics-informed learning pipeline, the proposed method reduces the sim-to-real gap. Evaluations on real-world datasets (CADC for snow, Boreas for rain) and the VoxelScape dataset show that our approach closely mimics realworld intensity patterns. Quantitative metrics, including MSE, SSIM, KL divergence, and Wasserstein distance, demonstrate statistically consistent intensity distributions. Additionally, models trained on data enhanced by our framework outperform baselines in downstream 3D object detection, achieving performance comparable to models trained on real-world data. These results highlight the effectiveness of the proposed approach in improving the realism of LiDAR data and enabling robust perception under adverse weather conditions.
### Title:
          Bench2Drive-VL: Benchmarks for Closed-Loop Autonomous Driving with Vision-Language Models
 - **Authors:** Xiaosong Jia, Yuqian Shao, Zhenjie Yang, Qifeng Li, Zhiyuan Zhang, Junchi Yan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the rise of vision-language models (VLM), their application for autonomous driving (VLM4AD) has gained significant attention. Meanwhile, in autonomous driving, closed-loop evaluation has become widely recognized as a more reliable validation method than open-loop evaluation, as it can evaluate the performance of the model under cumulative errors and out-of-distribution inputs. However, existing VLM4AD benchmarks evaluate the model`s scene understanding ability under open-loop, i.e., via static question-answer (QA) dataset. This kind of evaluation fails to assess the VLMs performance under out-of-distribution states rarely appeared in the human collected this http URL this end, we present Bench2Drive-VL, an extension of Bench2Drive that brings closed-loop evaluation to VLM-based driving, which introduces: (1) DriveCommenter, a closed-loop generator that automatically generates diverse, behavior-grounded question-answer pairs for all driving situations in CARLA,including severe off-route and off-road deviations previously unassessable in simulation. (2) A unified protocol and interface that allows modern VLMs to be directly plugged into the Bench2Drive closed-loop environment to compare with traditional agents. (3) A flexible reasoning and control framework, supporting multi-format visual inputs and configurable graph-based chain-of-thought execution. (4) A complete development ecosystem. Together, these components form a comprehensive closed-loop benchmark for VLM4AD. All codes and annotated datasets are open sourced.
### Title:
          Riemannian and Symplectic Geometry for Hierarchical Text-Driven Place Recognition
 - **Authors:** Tianyi Shang, Zhenyu Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-point-cloud localization enables robots to understand spatial positions through natural language descriptions, which is crucial for human-robot collaboration in applications such as autonomous driving and last-mile delivery. However, existing methods employ pooled global descriptors for similarity retrieval, which suffer from severe information loss and fail to capture discriminative scene structures. To address these issues, we propose SympLoc, a novel coarse-to-fine localization framework with multi-level alignment in the coarse stage. Different from previous methods that rely solely on global descriptors, our coarse stage consists of three complementary alignment levels: 1) Instance-level alignment establishes direct correspondence between individual object instances in point clouds and textual hints through Riemannian self-attention in hyperbolic space; 2) Relation-level alignment explicitly models pairwise spatial relationships between objects using the Information-Symplectic Relation Encoder (ISRE), which reformulates relation features through Fisher-Rao metric and Hamiltonian dynamics for uncertainty-aware geometrically consistent propagation; 3) Global-level alignment synthesizes discriminative global descriptors via the Spectral Manifold Transform (SMT) that extracts structural invariants through graph spectral analysis. This hierarchical alignment strategy progressively captures fine-grained to coarse-grained scene semantics, enabling robust cross-modal retrieval. Extensive experiments on the KITTI360Pose dataset demonstrate that SympLoc achieves a 19% improvement in Top-1 recall@10m compared to existing state-of-the-art approaches.
### Title:
          Hi-LOAM: Hierarchical Implicit Neural Fields for LiDAR Odometry and Mapping
 - **Authors:** Zhiliu Yang, Jianyuan Zhang, Lianhui Zhao, Jinyu Dai, Zhu Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR Odometry and Mapping (LOAM) is a pivotal technique for embodied-AI applications such as autonomous driving and robot navigation. Most existing LOAM frameworks are either contingent on the supervision signal, or lack of the reconstruction fidelity, which are deficient in depicting details of large-scale complex scenes. To overcome these limitations, we propose a multi-scale implicit neural localization and mapping framework using LiDAR sensor, called Hi-LOAM. Hi-LOAM receives LiDAR point cloud as the input data modality, learns and stores hierarchical latent features in multiple levels of hash tables based on an octree structure, then these multi-scale latent features are decoded into signed distance value through shallow Multilayer Perceptrons (MLPs) in the mapping procedure. For pose estimation procedure, we rely on a correspondence-free, scan-to-implicit matching paradigm to estimate optimal pose and register current scan into the submap. The entire training process is conducted in a self-supervised manner, which waives the model pre-training and manifests its generalizability when applied to diverse environments. Extensive experiments on multiple real-world and synthetic datasets demonstrate the superior performance, in terms of the effectiveness and generalization capabilities, of our Hi-LOAM compared to existing state-of-the-art methods.
### Title:
          Causal Scene Narration with Runtime Safety Supervision for Vision-Language-Action Driving
 - **Authors:** Yun Li, Yidu Zhang, Simon Thompson, Ehsan Javanmardi, Manabu Tsukada
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models for autonomous driving must integrate diverse textual inputs, including navigation commands, hazard warnings, and traffic state descriptions, yet current systems often present these as disconnected fragments, forcing the model to discover on its own which environmental constraints are relevant to the current maneuver. We introduce Causal Scene Narration (CSN), which restructures VLA text inputs through intent-constraint alignment, quantitative grounding, and structured separation, at inference time with zero GPU cost. We complement CSN with Simplex-based runtime safety supervision and training-time alignment via Plackett-Luce DPO with negative log-likelihood (NLL) regularization. A multi-town closed-loop CARLA evaluation shows that CSN improves Driving Score by +31.1% on original LMDrive and +24.5% on the preference-aligned variant. A controlled ablation reveals that causal structure accounts for 39.1% of this gain, with the remainder attributable to information content alone. A perception noise ablation confirms that CSN's benefit is robust to realistic sensing errors. Semantic safety supervision improves Infraction Score, while reactive Time-To-Collision monitoring degrades performance, demonstrating that intent-aware monitoring is needed for VLA systems.
### Title:
          UniDriveVLA: Unifying Understanding, Perception, and Action Planning for Autonomous Driving
 - **Authors:** Yongkang Li, Lijun Zhou, Sixu Yan, Bencheng Liao, Tianyi Yan, Kaixin Xiong, Long Chen, Hongwei Xie, Bing Wang, Guang Chen, Hangjun Ye, Wenyu Liu, Haiyang Sun, Xinggang Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have recently emerged in autonomous driving, with the promise of leveraging rich world knowledge to improve the cognitive capabilities of driving systems. However, adapting such models for driving tasks currently faces a critical dilemma between spatial perception and semantic reasoning. Consequently, existing VLA systems are forced into suboptimal compromises: directly adopting 2D Vision-Language Models yields limited spatial perception, whereas enhancing them with 3D spatial representations often impairs the native reasoning capacity of VLMs. We argue that this dilemma largely stems from the coupled optimization of spatial perception and semantic reasoning within shared model parameters. To overcome this, we propose UniDriveVLA, a Unified Driving Vision-Language-Action model based on Mixture-of-Transformers that addresses the perception-reasoning conflict via expert decoupling. Specifically, it comprises three experts for driving understanding, scene perception, and action planning, which are coordinated through masked joint attention. In addition, we combine a sparse perception paradigm with a three-stage progressive training strategy to improve spatial perception while maintaining semantic reasoning capability. Extensive experiments show that UniDriveVLA achieves state-of-the-art performance in open-loop evaluation on nuScenes and closed-loop evaluation on Bench2Drive. Moreover, it demonstrates strong performance across a broad range of perception, prediction, and understanding tasks, including 3D detection, online mapping, motion forecasting, and driving-oriented VQA, highlighting its broad applicability as a unified model for autonomous driving. Code and model have been released at this https URL
