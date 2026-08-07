# Showing new listings for Friday, 7 August 2026
## Keyword: SLAM
There is no result 
## Keyword: odometry
### Title:
          KILVO: Kinematic-Inertial-LiDAR-Visual Odometry with Robust Multimodal Adaptation for Humanoid Robots
 - **Authors:** Jixin Gao, Fucheng Liu, Teng Zhang, Fusheng Zha
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This article presents a kinematic-inertial-LiDAR-visual odometry for humanoid robots, called KILVO. Tailored to the platform features, requirements, and real-world complexity, it fully utilizes the sensors commonly equipped on humanoid robots, including joint encoders, IMU, LiDAR, and camera, within an asynchronous-sequential hybrid error-state iterated Kalman filter (ESIKF). Specifically, inertial data are used for prediction, leg kinematics are processed asynchronously at a high rate and provide proprioceptive constraints, while exteroception is updated sequentially, first by registering LiDAR points for geometric priors and then by updating the visual component via photometric errors. Moreover, the framework is elaborately designed with multimodal adaptation for resilience to sensor failures. A compact contact estimation module is also developed, sharing information with state estimation without additional sensors. Extensive experiments on public datasets and in the real world across multiple humanoid robots, gait patterns, and scenarios demonstrate that KILVO achieves highly competitive accuracy, efficiency, and output rates, with strong robustness against sensor degradation and failures, making it more suitable for humanoid robots than state-of-the-art fusion methods. Our code and datasets are released on GitHub.
### Title:
          TRACE: Learned Proprioceptive Odometry for Legged Robots under Unreliable Contact Conditions
 - **Authors:** Taehyeon Kong, Woojin Kim, Jemin Hwangbo
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we present TRACE (Tokenized Robust Attention for Contact-Aware Estimation), an end-to-end learned proprioceptive odometry estimator for legged robots under unreliable contact conditions. The proposed estimator directly predicts relative displacement, relative rotation, and body-frame velocity from a recent history of onboard inertial and joint measurements. To improve robustness under unreliable contact conditions, we introduce a foot-aware cross-attention module that adaptively weights IMU and leg-wise kinematic tokens without relying on manually defined contact or slip thresholds. The estimator is trained with direct supervision and two physics-inspired auxiliary losses that promote kinematic consistency and reliable use of leg information. To reduce policy-specific overfitting and consequently improve sim-to-real transfer, simulation training incorporates policy randomization, followed by partial real-world fine-tuning of the temporal encoder and prediction head. Experiments across diverse indoor and outdoor terrains demonstrate consistent reductions in position drift compared with classical filtering-based, hybrid, and purely learning-based baselines. Ablation studies further validate the contributions of the proposed training objectives, policy randomization, and real-world fine-tuning, particularly under unreliable contacts and sim-to-real mismatch.
### Title:
          Topometric Autonomous Vehicle Localization by Combining Visual Embeddings and Feed-Forward 3D Models
 - **Authors:** Eulogio Quemada-Torres, Alberto Jaenal, Francisco-Angel Moreno, Javier Gonzalez-Jimenez
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective Visual Localization (VL) requires a map of the environment that combines compactness for efficient scalability with robustness against visual appearance changes and metric precision. Through low-dimensional image embeddings, Visual Place Recognition (VPR) is able to successfully meet the first two requirements, but its low metric accuracy makes it less suitable than standard VL approaches based on local features or neural representations. This limitation can be overcome by integrating VPR with the accurate local trajectory estimates produced by feed-forward neural 3D geometry (FF3D) models. In this paper, we address sequential appearance-based localization through a topometric framework that iteratively combines probabilistic VPR with FF3D metric pose estimation in controlled image sets. Our approach proposes an automatic offline mapping tool that models the topometric pose-appearance interaction in the different parts of the scene. This map is later employed by an online particle filter that estimates the pose from odometry and belief over places for FF3D inference, successfully incorporating neural metric estimation into probabilistic appearance-based localization. We extensively evaluate the framework on three known benchmarks, demonstrating substantial improvements over existing appearance-based methods. The modularity of our approach allows the descriptor extractor and FF3D model to remain interchangeable, and a focused analysis further shows that sequential belief can mitigate severe failures under perceptual aliasing.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          A System for Train Condition Monitoring and Structural Health Assessment of Rail Vehicles
 - **Authors:** Maximilian Posner, Martin Dazer, Daniela Lauer, Robert Winkler-Höhn, Mathilde Laporte, Tobias Herrmann, Martin Köppel
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The ongoing digitalization of rail systems and the increasing use of artificial intelligence (AI) are fundamentally transforming the design, operation, and maintenance of rail vehicles. While fully automated operation at Grade of Automation 4 (GoA4) is well established in metro systems, its deployment in mainline rail remains limited. This is primarily due to stringent safety requirements and the complexity of open operational environments. Current perception systems based on cameras, radar, and lidar are effective in detecting objects but provide limited capability for reliably identifying impacts, collisions, and driving-over events. This paper presents a novel approach for real-time vehicle condition monitoring and impact detection that integrates structural sensor technologies with AI-based data analysis. The proposed framework addresses three key applications: (1) automated detection of impacts, structural damage, and driving-over events, (2) condition-based maintenance enabled by continuous monitoring, and (3) long-term data analytics to support vehicle design optimization. The results demonstrate the feasibility of the proposed approach and highlight its potential to enhance operational safety, enable predictive maintenance strategies, and support the transition toward fully automated operation in mainline rail systems
### Title:
          LoDA: A Level of Detection Aware Method and a Multimodal Sensing Benchmark for Object Level Change Detection
 - **Authors:** Haitian Wang, Xinyu Wang, Sheldon Fung, Xian Zhang, Zichen Geng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-definition 3D LiDAR maps are important for autonomous driving and smart-city services, which require reliable detection of object-level changes in multi-temporal urban LiDAR to keep digital maps aligned with the physical world. Existing approaches from raster height differencing to depth image and point-cloud networks often remain tile-based and threshold-driven, yielding per-point scores without explicit detection limits or consistent object-level labels. We propose an object-level 3D change-detection pipeline that integrates detection-limit-aware registration, geometry-driven object proxies with rule-based semantic and instance segmentation, and displacement cues in height, volume, and surface-normal direction to assign five change labels with confidence. By decoupling registration, geometry, and semantics, the pipeline propagates pose uncertainty into spatially varying detection limits, stabilizes cross-epoch correspondences, and suppresses false changes caused by residual misalignment and density variation. We also present LoDA, a level-of-detection (LoD) aware benchmark for the Subiaco district with fused multi-temporal vehicle-LiDAR maps constructed with LiDAR, GNSS, and IMU support, semantic instances, and object-level annotations. On this benchmark, our method achieves 95.0% accuracy, 90.8% macro F1, and 83.0% macro IoU, exceeding the best baseline by 8.7 IoU points and 4.4 F1 points. On the public Urb3DCD-V2 benchmark evaluated under the official point-wise protocol, it reaches 96.81% mean accuracy and 89.52% mean change IoU, improving over the strongest reported baselines by 1.36 points in mAcc and 3.18 points in mIoUch.
### Title:
          CDSeg: A Renderable Gaussian Carrier for Image-to-3D Label Transfer
 - **Authors:** Wentao Sun, Yiping Chen, Zhengsen Xu, Jonathan Li, John S. Zelek
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern image models provide strong cues about \emph{what} should be segmented in each view, but their masks do not by themselves determine \emph{where} those labels should persist in 3D. We present Cross-Domain Segmentation via Gaussian Splatting (CDSeg), a label-transfer interface that requires no task-specific 3D segmentation training and uses Gaussian primitives as a renderable label carrier. An external mask source supplies the labels, while renderer-derived visibility determines which 3D primitives receive them. The carrier is instantiated either by completing each input point into one Gaussian, preserving its index, or by reusing the native primitives of an optimized Gaussian scene. CDSeg records pixel--primitive associations during rendering and fuses multi-view masks through voting and a local filter. The resulting labels can be returned to the original points, retained on the native Gaussian scene, or rendered into other views. CDSeg covers promptable, automatic instance, semantic, and LiDAR settings and processes scenes with millions of primitives in seconds. It obtains 92.35\% mIoU on DesktopObjects-360, 95.89\% on NeRDS-360, and 65.77\% on the full ScanNet-v2 validation split using the provided 2D semantic annotations. CDSeg thereby provides one interface for reusing 2D masks across point clouds, Gaussian scenes, and image views without a task-specific 3D segmentation network.
### Title:
          PathCover: A Fast Convex Decomposition along a Path via Randomized Iterative Space Partitioning (RISP) on Point Clouds
 - **Authors:** Kunal S. Narkhede, Abhijeet M. Kulkarni, Guoquan Huang, Ioannis Poulakakis
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous robot navigation requires the rapid generation of obstacle-free regions for trajectory planning. However, existing corridor generators struggle to meet real-time, sensor-rate computational constraints. To resolve this bottleneck, we introduce PathCover, a framework driven by RISP; a novel randomized algorithm that constructs convex polytopes directly from raw point cloud data in expected linear time under a mild probabilistic elimination condition. PathCover generates sequences of overlapping, obstacle-free polytopes that safely constrain downstream MPC and trajectory optimization. We mathematically guarantee that the algorithm terminates in finite steps while ensuring continuous progress along any obstacle-free reference path. Extensive benchmarks on synthetic and real-world LiDAR datasets demonstrate an order-of-magnitude speedup over state-of-the-art methods while maintaining comparable corridor volumes. The complete pipeline is validated via high-fidelity quadrotor simulations and physical deployment on a quadrupedal robot navigating constrained environments using live LiDAR perception.
### Title:
          KILVO: Kinematic-Inertial-LiDAR-Visual Odometry with Robust Multimodal Adaptation for Humanoid Robots
 - **Authors:** Jixin Gao, Fucheng Liu, Teng Zhang, Fusheng Zha
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This article presents a kinematic-inertial-LiDAR-visual odometry for humanoid robots, called KILVO. Tailored to the platform features, requirements, and real-world complexity, it fully utilizes the sensors commonly equipped on humanoid robots, including joint encoders, IMU, LiDAR, and camera, within an asynchronous-sequential hybrid error-state iterated Kalman filter (ESIKF). Specifically, inertial data are used for prediction, leg kinematics are processed asynchronously at a high rate and provide proprioceptive constraints, while exteroception is updated sequentially, first by registering LiDAR points for geometric priors and then by updating the visual component via photometric errors. Moreover, the framework is elaborately designed with multimodal adaptation for resilience to sensor failures. A compact contact estimation module is also developed, sharing information with state estimation without additional sensors. Extensive experiments on public datasets and in the real world across multiple humanoid robots, gait patterns, and scenarios demonstrate that KILVO achieves highly competitive accuracy, efficiency, and output rates, with strong robustness against sensor degradation and failures, making it more suitable for humanoid robots than state-of-the-art fusion methods. Our code and datasets are released on GitHub.
### Title:
          G$^2$ARD-GS: Geometry-Guided Anchor-Regularized Gaussian Splatting Distillation
 - **Authors:** Puyuan Zhang, Jianming Huang, Wenkai Ye, Wei Dong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense colored LiDAR maps provide accurate city-scale geometry, but lifting them into 3D Gaussian Splatting (3DGS) retains millions of primitives, making the resulting models costly to store, transmit, render, and adapt. Aggressive primitive reduction alleviates this burden, but can remove the local surface support needed for stable novel-view synthesis and downstream geometric use. We introduce G$^2$ARD-GS, a geometry-guided distillation method that converts a dense Gaussian prior instantiated either as a training-free point-cloud lift or a trained GS model into a compact, reusable representation. G$^2$ARD-GS progressively consolidates the prior into surface-aware representatives, then recovers appearance on the resulting fixed topology under construction-time anchor constraints, with no primitives added or removed during recovery. Under limited supervision, geometry-aware view selection allocates the available view budget. On MatrixCity, G$^2$ARD-GS achieves the best PSNR, SSIM, and LPIPS across matched $5\times$--$30\times$ compression budgets, outperforming PUP by $3.2$--$6.8$,dB in PSNR. When reused as frozen geometry, the compact model improves off-trajectory appearance adaptation by $3.7$--$4.9$,dB over PUP 3D-GS and preserves image-to-model registration accuracy on Cambridge KingsCollege at $30\times$ compression. Project page: this https URL.
### Title:
          Iterate or Widen? When Test-Time Refinement Helps LiDAR Scene Completion: A Controlled Study of Evidence Geometry, Training Coverage, and Compute
 - **Authors:** Shijie Hao, Weining Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Should a completion model spend extra test-time compute by iterating, or spend a similar parameter budget on a wider one-shot predictor? The answer is easily confounded by denoising curricula, corruption augmentation, capacity, and unpaired evaluation. We study this question in LiDAR semantic scene completion by comparing a one-shot predictor, a parameter-matched wider predictor, and a weight-tied multigrid refiner initialized from the same frozen predictor. The protocol separates coherent region removal, independent thinning, range-dependent attenuation, and additive clutter while preserving exact scene-condition pairing. Across five training seeds and 815 SemanticKITTI sequence-08 frames, the full iterative system improves mIoU over the wide control by 0.911 points under contiguous angular removal, with a 95% moving-block bootstrap interval of [0.804, 1.040] that clears a predeclared 0.5-point practical margin. Under independent 75% thinning, iteration adds only 0.300 points [0.166, 0.436], whereas observation-family augmentation adds 5.975 points [5.662, 6.140]. Neither intervention repairs additive clutter. The iterative system also costs 10.74 ms and 0.75 GiB per frame, versus 6.25 ms and 0.23 GiB for the wide control. These results establish a geometry-conditioned empirical boundary rather than a universal advantage: coherent gaps can justify fixed-depth refinement, broadly thinned evidence is addressed more effectively by training coverage, and spurious evidence requires a different robustness mechanism.
### Title:
          UQ-Loc: Uncertainty-Aware LiDAR Scene Coordinate Regression
 - **Authors:** Jacek Komorowski
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based Scene Coordinate Regression (SCR) maps point clouds directly to 3D scene coordinates, enabling precise 6-DoF localisation without explicit map retrieval. However, existing methods produce deterministic predictions, discarding aleatoric uncertainty that could improve robustness and downstream decision-making. We present UQ-Loc, which extends the LightLoc architecture with an anisotropic Gaussian covariance head that predicts a full 3x3 positive-definite covariance matrix per voxel. Training uses a Negative Log-Likelihood (NLL) loss augmented with a kNN-based spatial smoothness regulariser, while inference employs a modified SC2-PCR solver with uncertainty-weighted seed scoring and a Mahalanobis-distance inlier test. We adopt Expected Calibration Error (ECE) as a principled metric for evaluating the quality of the predicted uncertainty. Experiments demonstrate that UQ-Loc achieves consistent improvement in 6-DoF localization accuracy while producing well-calibrated covariances.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          ASTELD: A Six-Axis Classification Framework for Autonomous AI Agents - Design, Evaluation, and an OpenClaw Case Study
 - **Authors:** Siyuan Li, Peng Shu, Churan Yu, Peilong Wang, Ruidong Zhang, Bowen Guo, Xinliang Li, Ruiyu Yan, Arif Hassan Zidan, Yi Pan, Wei Ruan, Lifeng Chen, Junhao Chen, Zhaojun Ding, Yiwei Li, Zhengliang Liu, Haixing Dai, Lin Zhao, Yu Bao, Xiang Li, Wei Zhang, Tianming Liu
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous AI agent platforms differ substantially in architecture, security, tool integration, execution, autonomy, and deployment, yet the field lacks a common classification scheme for comparing these design choices. We propose ASTELD, an operational six-axis classification framework for autonomous AI agents: Architecture pattern, Security posture, Tool integration model, Execution paradigm, Level of autonomy and human control, and Deployment topology. ASTELD is constructed by synthesizing prior agent taxonomies with observable platform properties and explicit category-assignment rules. We evaluate its discriminative and explanatory utility by mapping eight representative frameworks and by using OpenClaw as an in-depth case study. The resulting profiles separate all eight platforms under their dominant configurations and reveal three cross-platform patterns: a security-accessibility diagonal, strong execution-architecture coupling, and capability convergence with persistent architectural differentiation. We further classify 50+ OpenClaw derivatives and find that innovation concentrates on the Security, Execution, and Deployment axes, indicating that ASTELD can explain where ecosystem fragmentation occurs. The OpenClaw case study also supplies a six-category vulnerability taxonomy, evidence from five institutional assessments, and adoption and governance analyses that connect platform coordinates to observed risks. These results position ASTELD as a reproducible method for comparing agent platforms, identifying unoccupied design regions, guiding framework selection, and organizing future empirical research. The analysis also exposes a consequential empty region: none of the evaluated systems combines local-first deployment with enterprise-grade security.
### Title:
          CyberBridge: Bridging the Gap Between Cybersecurity Education and Industry
 - **Authors:** Arthur Nijdam, Paul Stankovski Wagner, Sara Ramezanian
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This full research paper presents CyberBridge, a framework that automatically maps cybersecurity job descrip- tions to professional role profiles. As the cybersecurity landscape evolves rapidly, it is difficult for academic programs to align curricula with the competencies expected in practice. CyberBridge addresses this gap by decomposing a given vacancy description into its constituent Knowledge, Skill, and Task (KST) statements, embedding them using a sentence- BERT model, and matching them to the most semantically similar workforce profiles. A key contribution of our approach is its interpretability. Rather than functioning as a black box, CyberBridge enables users to trace recommendations back to the specific competencies driving each match, providing a human- readable justification for the resulting mappings. CyberBridge supports three primary use cases; (1) job recom- mendation, providing students with vacancies and closely match- ing professional roles based on their completed curriculum, (2) market analysis, enabling educators and curriculum developers to analyze which roles are currently in demand, and (3) curriculum planning, assessing which course program best prepares students for in-demand cybersecurity roles. As such, CyberBridge can be used by educational institutions as a practical tool for career guidance and evidence-based curriculum development in cybersecurity education.
### Title:
          The Hidden Life of Public Safety Communications Signals: A Comparative Security Analysis of TETRA, TETRAPOL, and P25
 - **Authors:** Larry Hernandez, Sergey Bratus
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Public-safety agencies and critical infrastructure operators rely on trunked land-mobile radio (LMR) systems, based on P25, TETRA, and TETRAPOL. These systems are expected to protect not just the content of a communication but the fact of it. Yet LMR standards leave a stark gap between confidentiality of \emph{content} and of \emph{communication}: underneath an encrypted traffic plane, their signaling plane is almost entirely in the clear. We probe the depth and impact of adversarial inference from this exposed signaling. Prior security analyses of these systems have concentrated on the content plane---recovering encryption keys or capturing accidental cleartext. We show that comparably sensitive information can be \emph{inferred from passively observed signaling even if the content encryption were perfect}. In particular, we show that across the trunked LMR standards, a passive, receive-only software-defined radio (SDR) observer can recover operationally sensitive network topology and geography details, unit presence, mobility across cells and groups, organizational structure, as well as operational security details such as special key domains and key-epoch rotation. This signaling-plane inference reaches far beyond the observer's direct area of reception, turning \emph{local} sniffing into \emph{nationwide} network mapping capabilities that degrade or defeat LMR standards' identity obfuscation through timing and association. In the case of TETRAPOL, we demonstrate how inference and tracking of such signaling metadata and a standards-level confidentiality failure in emergency call handling enable unencrypted voice extraction. Finally, we discuss potential countermeasures and mitigations, including specific recommendations for protecting inter-cell, base station and subscriber identities.
### Title:
          Grad-CAM for Vision Transformers: A Systematic Taxonomy and Audit of Methodological Ambiguity in Explainable AI
 - **Authors:** Casey Wall, Longwei Wang, Rodrigue Rizk, KC Santosh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gradient-weighted Class Activation Mapping (Grad-CAM) is widely used to visualize model decisions, but it was originally formulated for convolutional neural networks, where spatial feature maps and channel dimensions have clear architectural meanings. Vision Transformers (ViTs) do not provide the same structure, instead representing images through tokens, attention, residual streams, and multimodal interactions. This paper presents a systematic taxonomy and literature audit of how Grad-CAM and related methods are adapted, justified, and reported for ViT-based architectures. From an initial search of more than 550 papers, we identify 175 papers that apply Grad-CAM or Grad-CAM-adjacent methods to ViTs. We find that most papers do not provide a full mathematical or implementation-level account of how Grad-CAM is adapted to transformer representations. To characterize this gap, we introduce a descriptive taxonomy of ViT Grad-CAM adaptations that makes explicit the feature locations, gradient targets, spatial reconstruction steps, and aggregation choices that are often left implicit. This taxonomy is not intended to prescribe a single correct adaptation, but to clarify the range of methodological choices being made. The study shows that Grad-CAM on ViTs is often treated as a trivial extension of CNN-based Grad-CAM, despite requiring nontrivial choices that affect rigor, reproducibility, and interpretation.
### Title:
          Rectifying Geometric Misalignment: Online Source-Free Adaptation for Class-Imbalanced EEG
 - **Authors:** Shiwen Chu, Shanglin Li, Motoaki Kawanabe, Reinmar Kobler
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electroencephalography (EEG) based Brain-Computer Interfaces (BCIs) often require unsupervised domain adaptation (UDA) to generalize across subjects and sessions. While Riemannian alignment methods like the Riemannian Centering Transformation (RCT) are effective for handling covariate shifts, they implicitly assume balanced class priors. However, in realistic online BCI scenarios, the label distributions vary dynamically (label shift), causing standard alignment techniques to geometrically misalign the target data distributions. In this work, we propose OSPDIM (Online SPD manifold information maximization), a source-free online UDA framework designed to address label shifts on the Riemannian manifold. OSPDIM introduces a manifold-constrained bias parameter into the tangent space mapping, which is optimized via information maximization to correct the geometric skew caused by imbalanced data streams. Unlike offline methods relying on global batch statistics, OSPDIM estimates and corrects geometric bias on-the-fly. Simulations on 2D SPD matrices visually demonstrate that OSPDIM successfully rectifies the misalignment where standard centering fails. Extensive experiments on multiple motor imagery datasets show that OSPDIM significantly outperforms standard Riemannian baselines, particularly in challenging online adaptation scenarios with severe class imbalance, offering a robust solution for practical, plug-and-play BCI systems.
### Title:
          Unified Planning-Learning Framework for Robust UUV Navigation Under Partial Observability
 - **Authors:** Md Ether Deowan, Eleni Kelasidi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents an observation-only autonomy framework for Unmanned Underwater Vehicles (UUVs) navigation in dynamic underwater environments that integrates persistent occupancy mapping, global clearance-aware planning, and risk-aware local control. The proposed pipeline constructs occupancy maps solely from onboard sonar and depth image observations, adapts a clearance-constrained global planner (GP) to provide long-horizon structure, and integrates a reinforcement learning (RL) policy to handle short-range tracking and reactive avoidance. To further support decision-making under partial observability, the system learns a compact latent state representation from onboard sensor data, encoding environmental structure, obstacle dynamics, and uncertainty. Behavior tree (BT) distillation with staged supervision is introduced to improve safety and training stability, while an uncertainty-calibrated distillation mechanism reweights teacher guidance using online latent-model uncertainty, emphasizing uncertain regimes during learning, with time-to-collision (TTC) and clearance cues remaining explicit in planning and local policy features. To demonstrate the efficacy of the framework, a reproducible multi-seed evaluation protocol is established in high-fidelity GPU-accelerated simulation using NVIDIA Isaac Sim, and performance is benchmarked against BT-only and standard RL baselines. The results obtained demonstrate improved robustness and safety under dynamic conditions, thus providing a general pipeline with a unified hybrid planning learning architecture and a reproducible methodology for robust UUV autonomy under partial observability.
### Title:
          Matrix Zonotopic Attention: A Context-Adaptive Value Projection for Set Transformers
 - **Authors:** Zhen Zhang, Amr Alanwar
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-head attention combines an input-dependent softmax routing with an input-independent linear value projection, so the per-sample operator mapping aggregated values to outputs is the same for every input set. We study the consequences of this asymmetry for permutation-invariant set targets. We introduce the Transformation Degrees of Freedom (TDOF) of a target operator, a complexity measure counting the input-dependent directions an exact representation requires, and present a depth-separation analysis showing that context-rigid attention needs depth proportional to the target's TDOF, whereas a single layer with a context-adaptive value family can represent the same target. Building on this analysis, we propose Matrix Zonotopic Attention (MZAttn), which replaces the fixed value projection with a context-adaptive matrix-zonotope family: a centre matrix plus a sum of generator matrices weighted by input-dependent gates. The construction reduces to standard multi-head attention at initialisation, preserves permutation equivariance, and admits a data-driven reachability interpretation. Experiments on a range of set-prediction tasks are consistent with the TDOF prediction that the architectural advantage is selective: it appears on targets that depend on the input set in a high-rank, sparsely combinatorial way, and is small on aggregate-statistic targets where parameter-matched standard attention is already competitive.
### Title:
          A Quantum Circuit Framework for Protein Ensemble-Level Energetics
 - **Authors:** Pratik Patil, Bhushan Bonde, Bhaskar Choubey
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET); Biomolecules (q-bio.BM); Molecular Networks (q-bio.MN)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Proteins occupy heterogeneous free-energy landscapes in which high-entropy ensembles converge toward compact, low-energy basins with multiple sub-states. Molecular dynamics can access these landscapes at atomic resolution, but exhaustive sampling remains computationally demanding. Meanwhile, most quantum approaches target only single optimal structures, leaving full ensemble energetic heterogeneity unexplored. We introduce a residue-level, gate-based quantum circuit framework for coarse-graining protein thermodynamics. Each amino acid is represented as a two-state qubit (stabilised vs. excited solvation state) based on residue solvation energetics. A structure-informed entanglement block then encodes covalent and non-covalent contacts using parameterised controlled gates, embedding correlations across the residue-interaction network. Sampling the circuit ($\sim 10^6$ measurements) yields binary thermodynamic microstates used to compute protein energy distributions, residue-level statistical couplings, energetic sensitivities, and information gains relative to total free energy. We showcase the framework on the benchmark Trp-cage miniprotein 1L2Y (TC5b) and 9GDL, a disulfide-stabilised Trp-cage-fortified exenatide chimera. For 1L2Y, the circuit reproduces a structured, folding-funnel-like energy distribution. Comparative analysis with 9GDL reveals shifts in global energy distributions and residue-level stability profiles. Coupling and information-theoretic analyses localise residues associated with ensemble reorganisation, while multi-body couplings show the circuit resolves both direct and indirect statistical correlations. This framework expands quantum protein modelling beyond single-structure optimisation toward ensemble-level characterisation, capturing key features of rugged energy landscapes to guide protein design, mutation mapping, and allosteric pathway identification.
### Title:
          Beyond Residual Connections: Manifold-Constrained Hyper-Connections for Robust Speaker Representation Learning
 - **Authors:** Zezhong Jin, Xiaoyu Wang, Zhe Li, Chong-Xin Gan, Zilong Huang, Man-Wai Mak, Kong Aik Lee
 - **Subjects:** Subjects:
Sound (cs.SD); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Residual connections are fundamental to deep speaker recogni- tion models, such as ECAPA-TDNN and ResNet. However, standard identity mapping limits information flow to a sin- gle path, constraining representation capacity. We introduce Manifold-Constrained Hyper-Connections (mHC), reformulat- ing residual paths as a multi-stream evolution where informa- tion is mixed through a doubly stochastic matrix. By employing Sinkhorn-Knopp iterations, mHC ensures energy conservation by preserving signal intensity and feature mean, which stabi- lizes gradients and mitigates signal degradation in complex net- works. We evaluate mHC by replacing standard residual con- nections in backbones including ECAPA-TDNN, ResNet-34, Res2Net, and E-Res2Net. Extensive experiments on VoxCeleb1 demonstrate that mHC connections consistently enhance per- formance across all architectures, highlighting its effectiveness for robust speaker representation learning.
### Title:
          ESVR: 3D Ellipsoid-based Sparse Volume Rendering via Structure-aware Primitive Learning and Per-primitive Ray Sampling
 - **Authors:** Suemin Jeon, Youjin Kim, Jungwoo Park, Kyungryun Lee, Won-Ki Jeong
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient representation and rendering of large-scale sparse volumetric data remain challenging in scientific visualization, as meaningful structures often occupy only a small fraction of the spatial domain. While direct volume rendering (DVR) provides high-quality visualization, its computational and memory costs scale poorly with data size. Recent advances in 3D Gaussian Splatting (3DGS) address this challenge by representing volumetric scenes with compact geometric primitives, enabling efficient, high-fidelity rendering. However, existing 3DGS-based methods learn from DVR rendered images rather than raw volumes, leading to information loss and limiting flexible transfer function control for interactive exploration. To address these limitations, we propose ESVR, an ellipsoid-based sparse volume rendering framework that directly learns and renders volumetric data in 3D space. Our method combines differentiable ellipsoidal primitives with bounded support, structure-aware primitive learning with complementary pruning, and a per-primitive ray sampling strategy for fast and accurate transfer function mapping. To support large-scale datasets, we further introduce a chunk-based optimization scheme with ghost ellipsoids, providing boundary context during training. Across large sparse datasets, ESVR achieves up to four orders of magnitude compression and real-time rendering at 43-223 FPS while maintaining competitive reconstruction quality.
### Title:
          Keeping Models and Code in Sync: Roundtrip Engineering for Tactical Domain-Driven Design
 - **Authors:** Weixing Zhang, Mario Herb, Wai Chung Dorothy Cheng, Michael Wagner, Bowen Jiang, Tianhai Liu, Anne Koziolek
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Domain-Driven Design gives teams a shared vocabulary for complex business logic, but that vocabulary only stays useful as long as the model and the code agree with each other. In practice, they drift apart: code changes outpace the model, or model revisions never make it into the codebase. This paper presents JDomInO, a bidirectional synchronization toolchain for tactical DDD that keeps a Java codebase and its domain model connected through a shared metamodel, with the goal of keeping the two in sync as the system evolves. JDomInO generates Java code structure deterministically from a domain model (forward path) and reconstructs a domain model from existing Java code (reverse path). The forward path has been fully validated on a Hotel Management scenario covering all 12 building block types in the metamodel; the reverse path's mapping logic has passed unit testing, with end-to-end validation underway. We also outline how the structured domain model produced by JDomInO could serve as a precision context layer for AI code assistants, helping them respect aggregate boundaries and DDD semantics that raw source code alone does not convey.
### Title:
          Dual-Output Multi-Exposure HDR Reconstruction via SDR Fusion and Gain Map Inverse Tone Mapping
 - **Authors:** Jinho Kim, Jinwoo Kim, Seon Joo Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose DOME-HDR, a dual-output multi-exposure HDR reconstruction framework that jointly produces a perceptually balanced SDR image and a consistent HDR image via gain map inverse tone mapping. Given three bracketed LDR inputs, DOME-HDR first synthesizes a base SDR using a LoRA-adapted latent diffusion model. A dual cross-attention fusion module injects complementary structural and color cues from the under- and over-exposed images while anchoring on the mid exposure for stability. The synthesized SDR then guides HPGM, our HDR Prior-guided Gain Map network, to predict a spatially varying gain map for reliable dynamic-range expansion. We evaluate on Kalantari, Tel, and Challenge123 using both full-reference and no-reference metrics, where DOME-HDR achieves state-of-the-art HDR reconstruction quality; ablations further confirm the effectiveness of dual cross-attention and SDR-guided gain map estimation.
### Title:
          MEC-Patch: Visible-Infrared Cross-Modal Adversarial Attack Driven by Intrinsic Material Emissivity Laws
 - **Authors:** Zhixiang Huang, Xinbo Nie, Wenxuan Wang, Lu Yang, Xin Li, Xuelin Qian, Peng Wang
 - **Subjects:** Subjects:
Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the widespread deployment of visible-infrared multimodal perception systems in safety-critical domains such as autonomous driving, evaluating their cross-modal adversarial robustness has become increasingly vital. However, existing approaches exhibit significant limitations in approximating the intrinsic laws of imaging. Most studies either focus on a single modality, failing to bypass cross-modal verification, or simplify infrared modeling into heuristic pixel-intensity distributions, neglecting the impact of ambient temperature fluctuations on adversarial stability. To bridge this gap, this paper proposes MEC-Patch, a cross-modal adversarial attack framework driven by intrinsic physical laws. By leveraging the Stefan-Boltzmann Law, we establish a physics-grounded cross-spectral mapping that explicitly links material emissivity to thermal radiation. Building on this formulation, we reveal that, under a fixed emissivity distribution, ambient temperature variations induce consistent global scaling while preserving relative emissivity-induced contrast. We exploit this property to construct temperature-robust adversarial perturbations whose discriminative patterns remain stable in the infrared modality, thereby fundamentally mitigating environmental sensitivity. Furthermore, we employ the physics-constrained NSGA-II algorithm to synergistically optimize the material-distribution-based patch parameters effective across both modalities, while enhancing generalization through a Dynamic Adversarial Resampling (DAR) strategy. Experimental results demonstrate that MEC-Patch effectively deceives state-of-the-art multimodal detectors and exhibits high robustness within high-fidelity, physically-consistent, and multi-scene simulation environments. This research provides a physical-law-driven perspective for the security assessment of multimodal perception systems.
### Title:
          Flow-Map Distillation on Relation Manifolds for Image Restoration
 - **Authors:** Zihao He, Songhua Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Knowledge distillation for image restoration typically aligns intermediate features or relation matrices between teacher and student networks as static targets, ignoring the dynamic structure of the knowledge transfer process. In this paper, we propose Flow-Map Distillation on Relation Manifolds (FoRM), which reformulates relation-based knowledge transfer as a continuous flow mapping problem on the relation manifold. Rather than regressing a constant velocity field between student and teacher relation states, FoRM learns a flow map operator $\mathcal{F}_\theta(\mathbf{z}, t, s)$ that directly predicts the relation state at any target time $s$ given the current state at time $t$, enabling richer trajectory-level supervision. To ensure global self-consistency of the learned flow map, we introduce a safe semigroup consistency constraint that enforces compositional agreement using ground-truth bridge states, eliminating phantom-state error accumulation. An endpoint anchoring loss further prevents the operator from drifting away from the teacher target. Extensive experiments on five image restoration tasks, including super-resolution, deraining, denoising, deblurring, and low-light enhancement, demonstrate consistent gains over state-of-the-art distillation baselines across multiple backbone architectures, reducing training variance by approximately 50\% compared to naive flow matching distillation while achieving superior restoration quality.
### Title:
          M$^3$R-Bench: A Unified Benchmark for Evidence-Grounded Multimodal Metaphor Understanding
 - **Authors:** Hong Jiang, Junnan Zhu, Jingwang Huang, Xiao Sun, Yuming Yang, Jiang Zhong, Ruirui Chen, Jingman Shi, Hao Wu, Nayu Liu, Xinyi Jiang, Kaiwen Wei
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Metaphor enables the understanding of abstract concepts through cross-domain mappings while conveying affective attitudes. In multimodal scenarios, visual and textual information jointly construct Target--Source mappings, requiring both conceptual understanding and cross-modal reasoning. However, existing benchmarks mainly evaluate metaphor understanding through isolated subtasks and lack evidence-grounded explanations, making it difficult to assess whether models establish mappings grounded in visual and textual this http URL address these limitations, we introduce M$^3$R-Bench, a unified and evidence-grounded benchmark containing 1,000 image--text instances with human-verified annotations. Guided by Conceptual Metaphor Theory and theories of nonliteral language understanding, M$^3$R-Bench provides joint annotations for metaphor occurrence, Target--Source mapping, sentiment, and stage-wise explanations following ``evidence identification--mapping establishment--sentiment inference.''Evaluations on M$^3$R-Bench reveal that existing models often overlook visual evidence, rely on superficial textual cues, and produce inaccurate Target--Source mappings, exposing a cross-modal evidence--mapping mismatch. To address this mismatch, we propose M$^3$R-Reasoner, which combines curriculum-based reasoning supervision with task-aware reinforcement learning to align model reasoning with metaphor interpretation. Experiments show that, with only an 8B-parameter backbone, M$^3$R-Reasoner outperforms larger proprietary MLLMs across four unified-task metrics and improves Visual Evidence and Sentiment Justification scores over GPT-5.5 by 28.45 and 30.11 points, respectively, while surpassing Claude-Sonnet-4.6 by 8.00 points in mean rubric score. The dataset and code are available at this https URL.
### Title:
          On the Figures of Merit for Quantum Software Security: Toward a Benchmarking Rubric
 - **Authors:** Badhon Rahman, Majid Haghparast, Tommi Mikkonen
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Quantum software is increasingly provided through multi-tenant and cloud-based Quantum-as-a-Service (QaaS) stacks. A growing concern about the diverse attack vectors across the pipeline has been demonstrated in recent research. Yet the community has converged on three mature pillars: Scale (Qubit Count), Quality (Quantum Volume), and Speed (Circuit Layer Operations per Second (CLOPS)) for the merit performance figures. Moreover, it has also begun to define software-quality metrics. However, the security of quantum software remains largely unmeasured. A few quantitative security indicators, such as Total Variation Distance (TVD) and Degree of Functional Corruption (DFC), exist. Although they were introduced ad hoc for individual circuit obfuscation techniques, they are incompatible. We assert that the security of quantum software deserves the same attention as the performance: an explicit set of Security Figures of Merit (S-FoMs). The research of this paper is threefold: (i) characterizes a three-layer measurement gap, (ii) proposes a structured S-FoM set organized by ISO/IEC 25010 security sub-characteristics, QaaS pipeline mapping, and measurement maturity, and (iii) defines a benchmarking rubric that normalizes and aggregates S-FoMs into a combined Quantum Software Security Posture (QSSP) score. Additionally, an illustrative reanalysis of published obfuscation techniques has been presented. Our aim is a first step toward security-aware benchmarking of the Quantum Software Stack (QSS).
### Title:
          Mapping Similarity Spaces across Embedding Models with Synthetic Query Probing
 - **Authors:** Marcin Rozmus, Peter van der Putten
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Retrieval-Augmented Generation systems rely on similarity scores to retrieve relevant content, yet scores are not directly comparable across embedding models due to differing geometric properties, complicating model migration and limiting threshold reuse. We study how similarity scores can be related by learning mappings between score distributions rather than embeddings. We introduce Synthetic Query Probing, generating queries from documents to create controlled query-chunk pairs, enabling large-scale, reference-free analysis of cross-model similarity behavior. We evaluate the approach on multiple embedding configurations and learn score conversion functions using linear, isotonic, and quantile mappings. Experiments on SciFact and a proprietary corpus show that while models largely agree on rankings, their absolute scores exhibit systematic distortions. Learned mappings partially align these spaces and improve threshold portability, with isotonic regression performing best. Our results highlight the need for cross-model calibration and position Synthetic Query Probing as a scalable framework for analyzing embedding comparability.
### Title:
          Improving Interoperability among Defence and National Security Ontologies: Analysis and Evaluation Tasks
 - **Authors:** Jonathon Dilworth, Pedro Giesteira Cotovio, David Herron, Paul Cripps, Nigel Dewdney, Catia Pesquita, Ernesto Jiménez-Ruiz
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The use of ontologies and knowledge graphs is becoming increasingly widespread in the defence and national security domain. Numerous ontologies have been developed through initiatives led by academia, industry, and government. Achieving interoperability across diverse defence and national security ontologies remains a major challenge due to the domain's breadth and specialisation. In this work, we analyse and document over 60 publicly available ontologies and introduce a new track for the Ontology Alignment Evaluation Initiative (OAEI). This track comprises eight matching tasks, consensus alignments and manually-curated (silver-standard) mappings. The consensus alignments are derived by aggregating the outputs of several state-of-the-art ontology alignment systems. The silver-standard is obtained from the manual validation of the consensus alignment together with a subset of the unique mappings (i.e., mappings suggested by only one system).
### Title:
          How Far Do Simple Transformations Translate Across Text Embedding Models?
 - **Authors:** Sid Ali Hamideche, Louis Adrien Dufrene, Quentin Lampin, Guillaume Larue (Orange Research)
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate whether simple transformations can translate representations across heterogeneous text embedding models. Understanding how independently trained models organize semantic information is an enabler for AI-to-AI latent communication without decoding into human-readable text. Focusing on lightweight translators such as linear mappings, we test the literature hypothesis of latent universality in a realistic text setting beyond simplified benchmarks. Across nine embedding models differing in architecture, pooling strategy, and training objective, we evaluate compatibility using CKA, downstream transfer, fidelity, and retrieval. Simple translators recover meaningful shared structure and support transfer for some compatible pairs, but fail sharply for others. Compatibility depends jointly on architecture, training objective, pooling, and data distribution. Overall, the results show that heterogeneous embedding spaces are not universally related by simple mappings as often suggested in some literature.
### Title:
          Temporal Bridges for Spatial Resolution: Enhancing Climate Data Super-Resolution with Bidirectional Alignment
 - **Authors:** Yichen Zhang, Yixiong Xiao, Congxi Xiao, Jingbo Zhou
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-resolution climate data is crucial for meteorological predictions and for informing decision support across diverse domains. However, the acquisition of such high-resolution climate information is often prohibitively costly, necessitating the development of data-driven meteorological prediction models. These models aim to generate fine-grained climate data from low-resolution inputs, a process termed climate data super-resolution (SR). Nevertheless, recent advancements in deep learning for climate data SR have primarily focused on leveraging single-frame spatial information, largely neglecting the temporal correlations between different time frames that could enhance SR outcomes. Furthermore, climate data are inherently stochastic and noisy, rendering widely used temporal alignment methods, such as optical flow models, ineffective in this context. Consequently, the development of a framework tailored for climate data SR that effectively captures implicit temporal correlations remains an unresolved challenge. To this end, we propose a novel Temporal-Enhanced framework with bidirectional temporal alignment. In essence, our framework establishes a temporal bridge to enhance spatial resolution in climate data SR through bidirectional alignment, leading to improved SR performance. Within this framework, Paired Latent Mapping achieves spatial alignment and noise reduction by unifying latent spaces. Then a Bidirectional Temporal Alignment captures temporal correlations by training forward and backward networks on consecutive latent frames. Temporal Enhanced Super-resolution then optimizes the entire framework for climate data SR. Experiments on large-scale real-world datasets demonstrated the superior performance of our framework.
### Title:
          Topometric Autonomous Vehicle Localization by Combining Visual Embeddings and Feed-Forward 3D Models
 - **Authors:** Eulogio Quemada-Torres, Alberto Jaenal, Francisco-Angel Moreno, Javier Gonzalez-Jimenez
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective Visual Localization (VL) requires a map of the environment that combines compactness for efficient scalability with robustness against visual appearance changes and metric precision. Through low-dimensional image embeddings, Visual Place Recognition (VPR) is able to successfully meet the first two requirements, but its low metric accuracy makes it less suitable than standard VL approaches based on local features or neural representations. This limitation can be overcome by integrating VPR with the accurate local trajectory estimates produced by feed-forward neural 3D geometry (FF3D) models. In this paper, we address sequential appearance-based localization through a topometric framework that iteratively combines probabilistic VPR with FF3D metric pose estimation in controlled image sets. Our approach proposes an automatic offline mapping tool that models the topometric pose-appearance interaction in the different parts of the scene. This map is later employed by an online particle filter that estimates the pose from odometry and belief over places for FF3D inference, successfully incorporating neural metric estimation into probabilistic appearance-based localization. We extensively evaluate the framework on three known benchmarks, demonstrating substantial improvements over existing appearance-based methods. The modularity of our approach allows the descriptor extractor and FF3D model to remain interchangeable, and a focused analysis further shows that sequential belief can mitigate severe failures under perceptual aliasing.
### Title:
          Dynamic Graph Prompting via Topology-Routed Mixed-Curvature Experts
 - **Authors:** Quanxin Wang, Xuanting Xie, Bingheng Li, Xingtong Yu, Shuo Wang, Ruiyi Fang, Zhao Kang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dynamic graph prompting freezes a pre-trained temporal backbone and adapts it to label-scarce downstream tasks using lightweight prompts. However, existing methods operate within a single, fixed embedding space. In this work, we reveal that temporal shifts in local clustering and degree heterogeneity actively reorganize the edge curvature spectrum---indicating that the optimal representation geometry dynamically evolves with local topology over time. We formalize this unaddressed mismatch as geometry under-adaptation. To overcome this limitation, we propose CurvPrompt, a topology-routed geometry prompting framework for dynamic graphs. Instead of relying on a single space, CurvPrompt maintains a bank of curvature-diverse Riemannian experts, each paired with a learnable prompt. A topology-aware gate dynamically routes each node--time instance to a sparse subset of experts, constructing a personalized mixed-curvature representation. To ensure parameter efficiency and training stability under extreme label scarcity, CurvPrompt employs soft routing during pre-training to build a continuous topology--geometry mapping, and transitions to hard Top-K routing with uniform weights during downstream adaptation. Extensive experiments across four benchmark datasets show that CurvPrompt significantly advances few-shot link prediction while delivering strong, consistent performance on node classification tasks, validating the necessity of geometry-adaptive prompting.
### Title:
          ASGE-RR: Agentic Service Graph Embedding with Revisable Reservations for Dynamic AI-Agent Calls
 - **Authors:** Trond Vatten, Yuming Jiang
 - **Subjects:** Subjects:
Multiagent Systems (cs.MA); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI-agent workflows often involve remote calls to models, memory stores, and tools distributed across a network. As execution progresses, these dependency calls collectively form an agentic service graph (ASG). Unlike traditional service requests, many dependency calls are revealed only at runtime. Consequently, allocating resources to a currently visible call may consume capacity later needed by a call from a higher-value workflow. We formulate this challenge as Agentic Service Graph Embedding (ASGE), an online network-control problem that maps runtime-revealed workflow calls to service replicas and network paths under capacity, cost and deadline constraints. We present ASGE-RR, an online ASGE controller with revisable reservations. ASGE-RR protects capacity for likely future calls while enforcing the constraints. ASGE-RR evaluates candidate replica-and-path mappings against predicted workflow continuations and updates reservations as new execution information becomes available. We evaluate ASGE-RR using OpenHands and GPT Researcher workflows executed with gpt-5.6-luna and replayed over in two complementary experimental environments, a controlled Docker testbed and a WAN testbed. The investigation shows that all the evaluated AI-agent tasks expose at least one runtime-revealed dependency call that can be steered before connection establishment. Exploiting this control point, even though the experimental environments are small-scale, ASGE-RR already demonstrates noticeable potential: It completes (up to) 10% more workflow value than a same-information rolling-horizon controller and a current-call steering controller on the WAN testbed. The results suggest that runtime-revealed workflow structure creates a new network control opportunity: protecting resources for likely future calls allows more AI-agent workflows to finish in time.
### Title:
          VIDP: Variable Impedance Diffusion Policy for Compliant Robot Manipulation from Diverse Demonstrations
 - **Authors:** Hisham Khalil, Neil Fernandes, Thomas M. Kwok, Hsiu-Chin Lin, Yue Hu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Contact-rich manipulation requires precise tracking and mechanical compliance, where variable impedance control can improve robustness in task success, whereas static compliance cannot adapt to varying contact constraints. Variable impedance skills can be learned from demonstrations, avoiding complex modeling, but compliance is a hidden variable in force-agnostic kinematic data. While existing methods infer compliance from trajectory variations, these variations may reflect geometric adaptation and not intentional compliance when subject to changing spatial layouts. Therefore, this letter introduces Variable Impedance Diffusion Policy (VIDP), an imitation learning-based variable impedance control framework leveraging a Task-Parameterized Directionality-Aware Mixture Model (TP-DAMM) to extract physically consistent trajectory distributions from diverse demonstrations. By mapping distributions to stiffness profiles, VIDP jointly predicts pose actions and task compliance without force sensors. Real-world experiments show that VIDP significantly outperforms fixed-impedance baselines in task success rate while reducing interaction forces with respect to high stiffness controllers and tracking errors with respect to low stiffness baselines.
### Title:
          TLNM: Externally Validated Tooth Detection, Numbering and Segmentation from Smartphone Photographs Using Mask R-CNN
 - **Authors:** Arash Nedaei, Henna Tiensuu, Elina Väyrynen, Saujanya Karki, Jaakko Suutala
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Oral health issues affect billions globally, but the cost and limited access to professional dental care hinder preventive oral healthcare. Research relies on clinical-grade radiographs or intraoral camera images, unavailable for public self-screening. This study introduces a tooth localisation and numbering model for smartphone photographs. We developed a customised Mask Region-based Convolutional Neural Network (Mask R-CNN) pipeline trained on 1,272 annotated smartphone images. To address variability in patient-generated health data, the pipeline incorporates two domain-informed mechanisms: a masked gray-world white-balancing algorithm to mitigate artificial colour casts and an anatomically constrained detection layer to enforce structural validity and suppress false positives. Evaluation comprised four stages: internal held-out testing, independent external testing, a descriptive ablation study, and fold-based training stability analysis using the same internal test set. On the internal test set, the model achieved an instance-mask AP@50 of 0.818, class-aware PQ of 0.780, and operational F1 of 0.884. Training stability showed limited between-model variation: across ten runs, instance-mask AP@50 had a standard deviation of 0.009. On the external dataset, the model achieved an instance-mask AP@50 of 0.901, class-aware PQ of 0.832, and operational F1 of 0.928 despite differences in population, sensors, and acquisition protocols. The inference pipeline is available as an open-source, containerised API. These results demonstrate that consumer-grade smartphone imagery can support automated tooth-level anatomical mapping, offering a scalable, potentially low-cost foundation for remote screening and tele-dentistry in resource-constrained environments.
### Title:
          Bias Analysis of L2 Speaking Assessment Systems Using Concept Activation Vectors
 - **Authors:** Arya Labroo, Mengjie Qian, Kate Knill
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic speaking assessment systems are increasingly deployed in high-stakes settings to mark second language (L2) learners' speaking tests, making it critical to show that their scores depend on speaking proficiency rather than irrelevant speaker attributes such as first language (L1) or age. Transformer-based foundation models have improved the accuracy of these L2 speaking graders, but their black-box representations make fairness and interpretability analysis more difficult. Building on prior work that used Concept Activation Vectors (CAVs) to detect bias towards unwanted attributes (`concepts') in feature-based graders, we extend CAV-based analysis to two neural speaking assessment systems: a text-based BERT grader and a speech-and-text multimodal grader based on Whisper. CAVs represent human-interpretable concepts as directions in a model's activation space, allowing us to distinguish between whether a concept is encoded in a model's internal representations and whether it influences the predicted score, the latter quantified using a gradient-based sensitivity metric. Since CAVs rely on linear separability, which is less likely in complex neural embedding spaces, we also investigate whether sparse autoencoders (SAEs) provide cleaner concept directions by learning CAVs in a sparse latent space and mapping them back to activation space. Our analysis shows that concept recoverability depends strongly on the representation and architecture being probed, rather than on the concept alone. Sensitivity to concepts is also architecture-dependent. SAEs make concepts more linearly recoverable, but attenuate the original activation-space sensitivity, especially in low-dimensional layers. These findings highlight the need to distinguish concept recoverability from concept influence when auditing bias in speaking assessment systems.
## Keyword: localization
### Title:
          Improving Debugging in Verification-Aware Languages Through Automated Fault Localization: A Case Study in Dafny
 - **Authors:** Álvaro Silva, Isabel Amaral, João Pascoal Faria, Alexandra Mendes
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Verification-aware languages, like Dafny, integrate formal specifications directly into source code to enable static correctness checks. However, when verification fails, the feedback provided is often limited to the specific condition of the error, such as a violated postcondition, rather than the root cause of the fault. While Dafny's counterexample features provide concrete execution traces, these typically expose a single failing path per assertion failure, leaving the developer to manually look through the entire trace to locate the error. This paper investigates automated fault localization for verification-aware languages by comparing two paradigms: state-based and counterexample-based localization. Our state-based localization strategy replicates the ``snapshot'' methodology of AutoFix by inferring invariants and predicates to identify suspicious program states. The counterexample-based strategy consists of a family of techniques that progressively enrich the use of verifier output: from raw counterexample extraction, to structured single-trace ranking, and to multi-trace aggregation. To validate these methods, we present an evaluation framework using MutDafny to generate a diverse mutant dataset from DafnyBench and measure localization effectiveness using the EXAM score. Our results show that counterexample-based approaches substantially outperform state-based localization in this setting. Structured ranking over a single trace yields the largest improvement over raw counterexample output, while multi-trace aggregation provides additional gains in robustness and debugging utility by increasing coverage and reducing path bias introduced by the solver. These findings demonstrate that effective fault localization in verification-aware languages depends both on using counterexample information, and how that information is structured and diversified.
### Title:
          Reasoning from Traces: Divergence-Guided Agentic Repair of WebAssembly Discrepancies
 - **Authors:** Liyan Huang, Kaicheng Wang, Weihang Wang
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 WebAssembly (Wasm) promises seamless reuse of C/C++ codebases as portable, fast, sandboxed binaries. In practice, however, this promise often falls short: recent studies show that cross-compiling the same C/C++ source to Wasm and native binaries frequently leads to runtime discrepancies, owing to library implementation differences or compiler bugs. Since the root causes lie in the platform-level runtime and are hidden beneath the source code, even state-of-the-art LLM-based repair agents often fail to fix these discrepancies. In this paper, we present WasmMend, the first system to automatically repair Native-Wasm functional discrepancies. WasmMend converts the undirected exploration to a focused reasoning task in two stages: First, a novel differential trace analysis approach localizes the function where Wasm and native executions initially diverge; guided by this localization, LLM agents then reason about the root causes and generate patches that eliminate the divergent behavior. Experiments on real-world C/C++ projects show that WasmMend achieves a fix rate of 70.0%, compared to 50.2% for the agentic baseline and 54.5\% for the approach augmented with repair-time LLM-based instrumentation, demonstrating the value of divergence-guided reasoning for cross-platform repair.
### Title:
          CoordRefer: Coordinate-Aware 3D Visual Grounding from Multiview Images
 - **Authors:** Haijie Li, Jiaxin Zhang, Dave Zhenyu Chen, Youyu Chen, Yanmin Wu, Jian Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multiview image-based 3D visual grounding predicts a coordinate frame to define a coordinate system and then regresses a 3D bounding box for localization. However, existing methods jointly optimize coordinate frame selection and box regression, leading to coordinate-relative box ambiguity and degraded grounding performance. This ambiguity arises because the same box admits different numerical representations across coordinate frames, creating multiple optimization targets and yielding invalid compromise predictions. To tackle this challenge, we propose CoordRefer, a coordinate-aware framework that decouples coordinate frame selection from coordinate-conditioned grounding. CoordRefer first selects a reference frame to define the coordinate system and then conditions 3D box prediction on the coordinate system. We perform coordinate-aware supervised fine-tuning to establish coordinate frame selection and coordinate-conditioned box regression, followed by Group Relative Policy Optimization with 3D IoU-based rewards to align both stages with downstream grounding quality. On ScanRefer with Qwen3-VL-2B, CoordRefer achieves gains of 11% in Acc@0.25 and 7% in Acc@0.5 over the coordinate-agnostic baseline, while its geometrically refined variant surpasses methods using explicit 3D inputs.
### Title:
          ConceptADapt: Concept-guided Adaptive Feature Reconstruction with Dynamic Attention for Few-Shot Industrial Anomaly Detection
 - **Authors:** Yufei Li, Yicheng Ruan, Long Tian, Dongsheng Wang, Liang Bao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Few-shot industrial anomaly detection (FS-IAD) focuses on detecting and localizing visual defects in industrial inspection during the cold-start phase, where only a limited number of normal training samples are available per category. Recent advances in this field predominantly leverage visual features from foundation-model and have achieved promising performance. Despite the strong representational power of foundation-model features, the model generalization remains fragile due to the extreme scarcity of normal training this http URL address this pivotal issue, we propose ConceptADapt, a concept-guided adaptive feature reconstruction model with dynamic attention. Specifically, our model pre-learns a set of fixed normal concepts from the limited support features and leverages them to mine relationships with query features, thereby recalibrating their statistics for improved anomaly detection at test time. To mitigate the prevalent feature shortcut problem, which is particularly severe under low-data regimes, we further develop a dynamic attention mechanism integrated with sparse autoencoders to learn robust normal concepts during training. Moreover, to enable fast adaptation during inference, our model remains lightweight by incorporating LoRA into the attention module, which introduces only minimal updating this http URL experiments on three widely adopted FS-IAD benchmarks, including MVTec-AD, VisA, and MPDD, demonstrate that our model consistently outperforms state-of-the-art (SOTA) approaches across both detection and localization tasks, achieving significant improvements under various shot settings.
### Title:
          Equipment-centric workpiece localization in near real-time using deep learning-based vision and event-driven finite state machines
 - **Authors:** Dohyeon Kong, Jaebong Cho, Hyunbo Cho
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Continuous workpiece localization is essential for traceability and process coordination in hot forging, but direct tracking is unreliable because of extreme temperatures, surface degradation, and irregular routing. This study presents an equipment-centric framework that infers workpiece locations from handling equipment observed by multiple static 2D cameras. The framework estimates floorplan-space 3D equipment coordinates and recognizes grasp and release activities. Event-driven finite state machines validate these activities as discrete handling events and continuously update workpiece states and locations. A keypoint-guided attention mechanism integrated into a 3D convolutional neural network improves activity recognition by focusing on functionally relevant equipment regions. Evaluation in an operational hot forging factory achieved 100\% event detection accuracy within a 33-second tolerance window, a mean localization error of 317.8 mm, and a mean system latency of 21 seconds. The framework connects vision-based perception with interpretable event-driven reasoning and supports visualization of workpiece transfers and quantitative analysis of equipment operations.
### Title:
          Accurate Localization of Road Traffic Objects on the Road Plane Using Surveillance Camera Imagery
 - **Authors:** Jan Gawroński, Witold Czajewski
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate vehicle localization from monocular roadside surveillance cameras is important for intelligent transportation systems, traffic monitoring, and traffic conflict analysis. Standard approaches often estimate vehicle position from the center of the detector bounding box, which can produce large errors due to perspective distortion and parallax, especially for elevated cameras and large vehicles. This paper proposes a two-stage geometry-aware localization pipeline that estimates the projection of the vehicle footprint onto the road plane. First, vehicles are detected using a YOLO26-based detector. Second, a dedicated ResNet34 regression network predicts four corner points corresponding to the projected vehicle base. The final position is computed as the geometric center of the predicted quadrilateral. The method was trained on synthetic data generated in CARLA and fine-tuned on real-world roadside imagery from DAIR-V2X. Experiments on synthetic and real data showed clear improvements over naive bounding-box-center localization. On DAIR-V2X, the mean image-space localization error decreased from 31.77 px to 15.30 px, a 51.8% improvement, while the median error decreased to 4.29 px. Median ground-plane error for medium-range vehicles decreased from 5.52 m to 0.90 m, and for far-range vehicles from 8.67 m to 1.84 m. The results also show that contextual information surrounding the detector bounding box is important for geometric localization. The largest gains were observed for distant vehicles and geometrically challenging cases affected by strong perspective distortion and parallax.
### Title:
          Topometric Autonomous Vehicle Localization by Combining Visual Embeddings and Feed-Forward 3D Models
 - **Authors:** Eulogio Quemada-Torres, Alberto Jaenal, Francisco-Angel Moreno, Javier Gonzalez-Jimenez
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Effective Visual Localization (VL) requires a map of the environment that combines compactness for efficient scalability with robustness against visual appearance changes and metric precision. Through low-dimensional image embeddings, Visual Place Recognition (VPR) is able to successfully meet the first two requirements, but its low metric accuracy makes it less suitable than standard VL approaches based on local features or neural representations. This limitation can be overcome by integrating VPR with the accurate local trajectory estimates produced by feed-forward neural 3D geometry (FF3D) models. In this paper, we address sequential appearance-based localization through a topometric framework that iteratively combines probabilistic VPR with FF3D metric pose estimation in controlled image sets. Our approach proposes an automatic offline mapping tool that models the topometric pose-appearance interaction in the different parts of the scene. This map is later employed by an online particle filter that estimates the pose from odometry and belief over places for FF3D inference, successfully incorporating neural metric estimation into probabilistic appearance-based localization. We extensively evaluate the framework on three known benchmarks, demonstrating substantial improvements over existing appearance-based methods. The modularity of our approach allows the descriptor extractor and FF3D model to remain interchangeable, and a focused analysis further shows that sequential belief can mitigate severe failures under perceptual aliasing.
### Title:
          EpiBench: Can LLMs Understand Epitopes for Antibody Drug Discovery?
 - **Authors:** Zirui Wang, Jiaqi Wang, Qinghan Wang, Yuzhi Xu, Gang Du, Tingjun Hou, Odin Zhang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Genomics (q-bio.GN)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Epitopes determine where antibodies bind antigens and shape downstream therapeutic properties such as functional blockade and escape resistance, making epitope understanding central to antibody drug discovery. Although large language models (LLMs) have shown strong biomedical reasoning ability, it remains unclear whether they can infer epitope information directly from antigen and antibody sequences. Existing epitope resources typically focus on isolated prediction tasks or rely on specialized structural settings, while general protein benchmarks do not evaluate epitope-centered decisions across the antibody development workflow. To address this gap, we introduce EpiBench, a closed-book, sequence-based, and automatically scorable benchmark for evaluating epitope reasoning in LLMs. EpiBench contains 1,609 curated samples grounded in structural antibody--antigen contacts, curated functional B-cell assays, and deep mutational scanning escape measurements. It covers five connected tasks: targetable region discovery, antibody-conditioned epitope identification, epitope binning, functional epitope assessment, and antibody escape assessment, with controlled sampling to reduce shortcut-based evaluation artifacts. We evaluate nine general-purpose LLMs and analyze their behavior through task-specific baselines, antigen length stratification, explicit-reasoning comparison, and failure-mode inspection. The results show that current LLMs capture partial epitope-related signals but remain limited in antibody-specific sequence grounding, long-context residue localization, and biologically grounded reasoning. Therefore, EpiBench provides a diagnostic testbed for measuring and improving sequence-aware biomedical LLMs toward reliable LLM-assisted antibody discovery.
### Title:
          CogVis: Must Open-Vocabulary Change Detection Perceive the Scene Anew for Every Query?
 - **Authors:** Zijie Wang, Chen Zhong, Wei He
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Earth-surface monitoring requires change detection models capable of recognizing arbitrary semantic categories. Open-Vocabulary Change Detection (OVCD) addresses this need. However, existing methods often entangle temporal perception, semantic discrimination, and region verification, causing unstable results and redundant computation. Inspired by human visual change perception, we propose CogVis, a cognitive memory-guided framework that reformulates OVCD as a perception-memory-verification paradigm. CogVis first employs a Scene Change Perceptron (SCP) to extract a reusable, category-agnostic change prior from frozen bi-temporal features, thereby decoupling temporal evidence from semantic category decisions. A Semantic Memory Calibrator (SMC) then compensates for category-dependent score shifts by dynamically estimating an image-query-specific decision threshold. Finally, an Adaptive Region Filter (ARF) filters connected candidates using learned semantic, temporal, and structural reliability. Experiments on seven benchmarks spanning semantic change detection, binary change localization, and building-damage assessment show that CogVis achieves state-of-the-art performance across all evaluated datasets. By sharing scene-level change perception, CogVis further avoids repeating category-agnostic temporal perception across queries and improves inference throughput by 28.50%.
### Title:
          UQ-Loc: Uncertainty-Aware LiDAR Scene Coordinate Regression
 - **Authors:** Jacek Komorowski
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based Scene Coordinate Regression (SCR) maps point clouds directly to 3D scene coordinates, enabling precise 6-DoF localisation without explicit map retrieval. However, existing methods produce deterministic predictions, discarding aleatoric uncertainty that could improve robustness and downstream decision-making. We present UQ-Loc, which extends the LightLoc architecture with an anisotropic Gaussian covariance head that predicts a full 3x3 positive-definite covariance matrix per voxel. Training uses a Negative Log-Likelihood (NLL) loss augmented with a kNN-based spatial smoothness regulariser, while inference employs a modified SC2-PCR solver with uncertainty-weighted seed scoring and a Mahalanobis-distance inlier test. We adopt Expected Calibration Error (ECE) as a principled metric for evaluating the quality of the predicted uncertainty. Experiments demonstrate that UQ-Loc achieves consistent improvement in 6-DoF localization accuracy while producing well-calibrated covariances.
## Keyword: transformer
### Title:
          The Ignition Index: Measuring Global Workspace Dynamics in Language Models
 - **Authors:** Saman Rahbar
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce the Ignition Index (I), a validated scalar metric that operationalizes Global Workspace Theory's (GWT) all-or-none ignition prediction in transformer language models. The metric fits a four-parameter sigmoid to per-layer linear probe accuracy as a function of input signal strength, extracting steepness parameter beta-hat: high values indicate abrupt, ignition-like transitions; low values indicate graded build-up. Across 11 models spanning five architecture families, shuffled-label controls demonstrate 9.6-fold selectivity for genuine linguistic structure over spurious probe capacity (p < 0.001, Mann-Whitney U-test). We find: (1) Feedforward transformers exceed SSMs by 89% in aggregate beta-hat (p < 1e-13, Cohen's d = 0.52), with Mamba exhibiting near-linear profiles consistent with absent global broadcast. (2) Huginn-3.5B exhibits 2.12-fold higher ignition along its iteration axis than its depth axis, demonstrating that recurrent architectures manifest workspace-like transitions along the recurrence dimension. (3) Pythia-410M shows a PELT-detected phase transition at training step 256 (+67%), preceding induction-head formation. (4) Hypotheses linking ignition to model scale and signal strength were not confirmed, suggesting transformer architectures may saturate available ignition mechanisms. The Ignition Index provides the first validated quantitative bridge between GWT's dynamical predictions and mechanistic interpretability, with 9.6-fold measurement selectivity and architecture-level discriminability not previously characterized in the scaling literature. Code: this https URL
### Title:
          CNM-BERT: A Drop-In Structural Embedding for Chinese Characters via Ideographic Description Sequences
 - **Authors:** Thomas Sing-wing Wu, Liqian Yan
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Token-based encoders like BERT treat Chinese characters as atomic identifiers, ignoring their recursive orthographic structure. Consequently, models rely on contextual co-occurrence, degrading performance on rare and out-of-vocabulary (OOV) characters. We propose the Compositional Network Model (CNM), a lightweight augmentation that injects discrete compositional structure into Transformer encoders. CNM parses Ideographic Description Sequences (IDS) into trees, encodes them via a recursive Tree-MLP, and fuses the structural embeddings into BERT without modifying the backbone. Evaluated on the Wu et al. (2025) structural-probing benchmark, CNM-BERT outperforms the strongest baseline (ChineseBERT) on long-tail and OOV characters by +9.8 Structure accuracy and +7.7 Radical F1. Furthermore, CNM-BERT achieves consistent gains across CLUE, MRC, and NER tasks at both base and large scales, demonstrating that explicit structural injection delivers both robust OOV understanding and tangible downstream value.
### Title:
          A Survey of Adversarial Efficiency Degradation for Vision Transformer by Exploiting Input-adaptive Optimization
 - **Authors:** Anadi Goyal, Nandish Chattopadhyay, Anupam Chattopadhyay, Chandan Karfa
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) increasingly rely on input-adaptive inference, such as token pruning and early halting, to meet energy and latency budgets. This survey examines a recent class of adversarial efficiency degradation attacks that target these mechanisms to increase computation without necessarily degrading accuracy. We unify and compare two representative attacks, SlowFormer (a universal adversarial patch) and DeSparsify (per-image perturbations), across three popular token-pruning frameworks: A-ViT, ATS, and AdaViT. We standardize reporting using GFLOPs, accuracy loss, and an Attack Success (AS) metric that measures how much of the model's compute savings the attack takes away. Understanding these attacks is crucial for designing countermeasures that not only mitigate risk but also remain lightweight, since deployment often occurs in low-power settings such as mobile or embedded devices. To organize our analysis, we focus on three questions: how input-adaptive optimizations (e.g., token pruning and early halting) create attack surfaces for efficiency degradation; how such attacks operate in practice and which optimizations are most vulnerable; and which defenses exist today and whether they meaningfully restore efficiency under attack.
### Title:
          Diff-Symbo: Text-Controlled Long-Duration Symbolic Music Generation Using Autoregressive Latent Diffusion Model
 - **Authors:** Zhiwei Lin, Jun Chen, Boshi Tang, Weihao Wu, Yang Jing, Yaolong Ju, Fan Fan, Zhiyong Wu
 - **Subjects:** Subjects:
Sound (cs.SD); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-controlled symbolic music generation has recently gained research attention due to its versatile, flexible and straightforward approach to music composition. However, previous approaches tend to generate symbolic music with compromising quality, diversity, controllability and limited duration. In this paper, we present Diff-Symbo, an innovative method that uses latent diffusion model (LDM) to generate high-quality, diverse and long-duration symbolic music. To address the lack of text-symbolic music dataset, we develop a comprehensive dataset with 19,345 text templates by employing large language model. Furthermore, we design a music information encoder to reduce the training overhead while extracting more effective control representations. Given textual descriptions, our proposed method leverages LDM to improve the quality and diversity of music generation. Our method also improves the duration and the compositional consistency of music generation through an autoregressive approach. Experimental results show significant improvements of Diff-Symbo in text controllability, duration, and the quality of generated music compared to the baseline models such as GPT-4, MuseCoco and Multitrack Music Transformer (MMT). As one of the pioneer models in this field, Diff-Symbo paves the way towards controllable and high-quality symbolic music composition based on LDM, offering valuable contributions to both music amateurs and practitioners.
### Title:
          Grad-CAM for Vision Transformers: A Systematic Taxonomy and Audit of Methodological Ambiguity in Explainable AI
 - **Authors:** Casey Wall, Longwei Wang, Rodrigue Rizk, KC Santosh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gradient-weighted Class Activation Mapping (Grad-CAM) is widely used to visualize model decisions, but it was originally formulated for convolutional neural networks, where spatial feature maps and channel dimensions have clear architectural meanings. Vision Transformers (ViTs) do not provide the same structure, instead representing images through tokens, attention, residual streams, and multimodal interactions. This paper presents a systematic taxonomy and literature audit of how Grad-CAM and related methods are adapted, justified, and reported for ViT-based architectures. From an initial search of more than 550 papers, we identify 175 papers that apply Grad-CAM or Grad-CAM-adjacent methods to ViTs. We find that most papers do not provide a full mathematical or implementation-level account of how Grad-CAM is adapted to transformer representations. To characterize this gap, we introduce a descriptive taxonomy of ViT Grad-CAM adaptations that makes explicit the feature locations, gradient targets, spatial reconstruction steps, and aggregation choices that are often left implicit. This taxonomy is not intended to prescribe a single correct adaptation, but to clarify the range of methodological choices being made. The study shows that Grad-CAM on ViTs is often treated as a trivial extension of CNN-based Grad-CAM, despite requiring nontrivial choices that affect rigor, reproducibility, and interpretation.
### Title:
          Context Matters: Support Set Selection and Failure Detection for In-Context Medical Image Segmentation
 - **Authors:** Youssef Gehad, Emmanuel Zerefa, Krish Kabra, Guha Balakrishnan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context learning (ICL) adapts medical image segmentation models to unseen structures and modalities without retraining by conditioning on a task-specific support set of image-mask exemplars. Because this support set is the model's only task-specific signal, its composition directly influences segmentation performance. In this work, we investigate the support set as a controllable determinant of ICL reliability. First, we compare random sampling against similarity-based selection, where exemplars are retrieved based on their visual similarity to the query image. Second, we train a transformer-based classifier to predict, from the query and support images alone, whether a segmentation will fall below a specified Intersection-over-Union (IoU) threshold. Using MultiverSeg with DINOv3 embeddings across four benchmarks and three imaging modalities, we show that similarity-based selection consistently matches or outperforms random sampling, with the largest gains at the smallest support set sizes. Furthermore, our classifier predicts segmentation failure above chance on all four benchmarks. Ultimately, these results demonstrate that the reliability of in-context segmentation can be both improved via informed support selection and anticipated before use, providing practical mechanisms for safer clinical deployment.
### Title:
          Multi-Agent Transformer for Queue-Level XR Traffic Scheduling in TSN Networks
 - **Authors:** Marcos Carvalho, Fatih Temiz, Shavbo Salehi, Melike Erol-Kantarci, Daniel F. Macedo
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time-Sensitive Networking (TSN) and Mobile Edge Computing (MEC) hold strong potential for enabling ultra-reliable low-latency communication for time-sensitive applications, such as eXtended Reality (XR). However, the widespread adoption of XR introduces significant challenges due to co-located services in MEC environments, leading to contention for shared network resources. Moreover, XR traffic types have distinct characteristics and criticality in terms of timing requirements, further increasing the complexity and dynamics of such environments. Although reinforcement learning has shown promise for TSN scheduling optimization in dynamic network scenarios, existing approaches rely on centralized or high-level multi-agent designs and are typically tailored to periodic and predictable industrial traffic, limiting their applicability to XR workloads. As a result, these approaches suffer from (i) limited ability to capture inter-queue dependencies due to coarse-grained control, and (ii) poor adaptability to highly dynamic and heterogeneous XR traffic. To address these gaps, we propose a multi-agent reinforcement learning approach for queue-level XR traffic scheduling. We adopt the multi-agent transformer (MAT) to model inter-queue dependencies via attention over agents' observations and actions, enabling implicit coordination across heterogeneous co-located XR applications. Our simulation results show that the proposed method outperforms baselines, achieving up to 71.42% latency reduction and up to 83.2% reduction in failure rate, while consistently achieving high reliability across all queues.
### Title:
          Quantum-Structured World Models (QSWMs) for Predictive Latent Dynamics
 - **Authors:** Hailong Jiang, Emran Hossain, Feng Yu, Jianfeng Zhu, Guilin Zhang, Wulan Guo
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models learn latent states that summarize interaction histories, evolve over time, and support prediction, simulation, or planning. Most existing world models represent these states using classical vectors, probability distributions, recurrent hidden states, or transformer activations. In this paper, we introduce Quantum-Structured World Models (QSWMs), a quantum-inspired framework for predictive world modeling with structured latent states, latent transition operators, and measurement-inspired decoding maps. We study whether mathematical structures inspired by quantum theory, such as complex-valued representations and density-matrix-like latents, provide useful inductive biases for world modeling. We establish three foundational properties: classical inclusion, predictive sufficiency, and structured compactness. We then instantiate complex-valued and density-matrix-like QSWM variants and evaluate them on elementary cellular automata against strong classical baselines. Results show promising local predictive potential for complex-valued QSWMs, while also revealing limitations in long-horizon rollout, density-matrix variants
### Title:
          Adapting Vision Foundation Models with Cascaded Semantics
 - **Authors:** Xi Xiao, Xingjian Li, Cheng Han, Tianyang Wang, Lin Zhao, Yunbei Zhang, Guosheng Hu, Runmin Jiang, Xi Li, Xiao Wang, Min Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Prompt tuning, a leading parameter-efficient adaptation paradigm in NLP, has recently been extended to computer vision. Visual prompt tuning (VPT) adapts pre-trained vision transformers (ViTs) by updating a small set of additional prompt parameters. However, existing visual prompts are randomly initialized and do not exploit prior knowledge, such as instructions in NLP. We address this gap by injecting two complementary semantic priors into VPT. Fundamental image priors, including color, texture, and shape, are extracted with classical hand-crafted operators and injected into the input space, while self-attention maps provide instance-aware semantics in the feature space. We further propose a cascaded scheme that integrates both priors throughout ViT adaptation. Experiments on 34 challenging image classification datasets demonstrate superior downstream adaptation while tuning only 0.74% of ViT parameters. Project page: this https URL.
### Title:
          APQF: Agentic Profiling-Guided Structured Pruning and Mixed-Precision Quantization with Adaptive Fine-Tuning
 - **Authors:** Sadegh Jafari, Mohiuddin Bilwal, Fan Zhou, Brian Gelder, Ali Jannesari
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern deep neural networks achieve strong performance, but their scale makes them costly and slow, especially on resource-constrained edge devices. Pruning and quantization address this, but rely on manual, expert choices and on algorithms that are hard to apply across architectures. Uniform settings also ignore how differently individual layers respond to compression, which costs accuracy. We introduce APQF, an agentic profiling-guided framework that combines structured pruning, mixed-precision quantization-aware training, and accuracy recovery in one automated pipeline. A profiling agent measures how cost is distributed across the model and how sensitive each part is to pruning, and this evidence drives per-layer pruning ratios, per-layer bit-widths, and the recovery strategy, all proposed by LLM planners and validated before execution. To our knowledge, APQF is the first framework to combine LLM-guided, profiling-grounded decisions with a fully training-aware pruning and quantization pipeline for both CNNs and vision transformers. We evaluate APQF on ResNet, VGG7, ViT, DeiT, and Swin using ImageNet-1k and CIFAR-10. On ImageNet it cuts compute to 5.6-7.7 percent of the original bit-operations, a 13-18x reduction, while keeping accuracy close to the baseline, and under a 200K-image budget it stays roughly 17 points higher in Top-1 than existing joint pruning and quantization methods. On CIFAR-10 it compresses further than that method on four of five architectures. On VGG7 it reaches 93.15 percent using only 0.41 percent of baseline bit-operations, the only method at that compression level to improve on its full-precision baseline. Ablations show that uniform compression loses the most accuracy at matched compute, and that withholding profiling data from the planner hurts every model. Six LLM planners, including free open-weight ones, all reach 97.4-97.9 percent on Swin-Tiny.
### Title:
          Spectral Aliasing Pretext: A novel task for Self-Supervised fault diagnosis in rotating machinery
 - **Authors:** Victor Gialis, Maxime Metz, David Esteve, Abdenour Soualhi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning is a new way for machinery fault diagnosis but requires extensive labeled data, a scarce resource in industrial settings. We propose Spectral Aliasing Pretext (SAP), a self-supervised learning method that pretrains models on unlabeled vibration data by exploiting spectral aliasing. We deliberately undersample signals to create folded spectrum, then train a Transformer to reconstruct the original unfolded spectrum. This pretext task forces the model to learn frequency-domain invariants characteristic of mechanical faults, without potentially destructive augmentations. Experiments on the CWRU dataset show that SAP learns stable and highly discriminative representations. In a linear probing setting, SAP quickly achieves very high classification performance with only a small fraction of labeled data and low variance. In contrast, full fine-tuning, including fully supervised training, does not lead to more stable or better results. Overall, these findings suggest that SAP combined with linear probing can be more effective and reliable than fully supervised training for fault diagnosis with limited labeled data.
### Title:
          Vorch-Director: Interactive World Story Model via Noise-Aware Error Rectification
 - **Authors:** Lisai Zhang, Yidi Wu, Qi Liu, Xin Ma, Yang Ding, Gang Yue, Siqian Yang, Jingyuan Chen, Lin Ma, Yaohui Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autoregressive continuation provides a natural path toward minute-scale audio-visual generation by repeatedly extending a short-window generator conditioned on previously generated video and audio. However, models are trained on clean ground-truth histories, while inference relies on their own generated histories, where accumulated errors cause identity drift, over-smoothing, and audio-visual desynchronization. Recent methods reduce this mismatch by reusing prediction residuals as synthetic corruption, but we observe that the effectiveness of residual correction critically depends on the flow-matching noise level at which residuals are produced. We propose Vorch-Director, a noise-level-aware residual correction strategy that associates each residual with its originating noise level and injects residuals from matched noise regimes during training. By aligning injected errors with the denoising process, Vorch-Director produces more realistic autoregressive histories while retaining efficient teacher-forcing training. Built on the audio-visual LTX-2 diffusion transformer, Vorch-Director further introduces task embeddings to distinguish historical video, reference images, and target video, enabling unified conditioning for long-horizon generation. Together with a clean conditioning sink and mixed-task training, Vorch-Director supports multi-shot, multi-subject, reference-guided audio-visual long-video generation. We evaluate Vorch-Director on ST-Bench and introduce a new long-horizon audio-visual benchmark with metrics for quality drift and long-range consistency. Extensive experiments demonstrate improved stability and audio-visual fidelity over strong baselines.
### Title:
          Vorch-Omni: Multi-Task Orchestration of Sight and Sound
 - **Authors:** Vorch Team, Xiaoyu Chen, Yang Ding, Cong Han, Menglin Han, Yuxin Hong, Jiebo Hou, Zequn Jie, Xiang Li, Jing Liu, Qi Liu, Yulei Lu, Siyuan Luo, Lin Ma, Xin Ma, Yinlong Qian, Peng Shi, Fang Wan, Siqi Wang, Yaohui Wang, Yaole Wang, Yidi Wu, Siqian Yang, Mingyu Yin, Haoran Yu, Gang Yue, Lisai Zhang, Yuting Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in generative video modeling have enabled diverse generation, reference-based synthesis, extension, and editing, but existing approaches often rely on fragmented task-specific models. A general model must distinguish heterogeneous target, source, and reference signals to determine what to generate, preserve, or use as guidance, while reducing interference among tasks. Joint audio-visual generation further increases this challenge by introducing diverse conditioning and output configurations across modalities. We present Vorch-Omni, a unified multi-task framework for audio-visual synthesis based on an arbitrary-condition-to-arbitrary-output formulation. It flexibly treats video and audio signals as either conditioning inputs or generation targets. Token-level conditioning masks and task identifiers distinguish targets, source content, and references, while position types separate temporal context from independent conditions. To capture semantic and structural information, Vorch-Omni employs complementary visual conditioning pathways: a vision-language model interprets sampled frames with text instructions, and a video VAE encodes conditions into latent tokens for direct guidance. We further build a distributed data pipeline to curate diverse temporally aligned audio-visual clips, generate structured captions and metadata, and balance heterogeneous task distributions. Built on a single flow-matching diffusion transformer without task-specific architectural changes, Vorch-Omni supports over 10 tasks, including text-to-video, text-to-audio-video, image- and reference-conditioned generation, temporal extension, audio-driven generation, video transformation, and audio-visual editing. This unified framework provides a scalable foundation for general-purpose audio-visual generation and manipulation.
### Title:
          MACRO: Markov Chain Routing of Transformer Layers
 - **Authors:** Paweł Batorski, Abtin Pourhadi, Akylgali Aitaza, Przemysław Spurek, Paul Swoboda
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard Large Language Models (LLMs) execute layers sequentially. Dynamic layer routing, i.e. search for a different execution path through layers involving layer repetitions, skips and other moves, can improve performance. Existing routing approaches often require updating model weights, running expensive search loops per test instance, or demand ground-truth labels during inference. In this work, we propose Markov Chain Routing of Transformer Layers (MACRO), a framework that learns task-specific routes over LLM architectures without modifying underlying parameters. MACRO models layer routing as a context-dependent Markov policy conditioned on layer indices, computation budget phases, directional displacements, and operator context, supporting skip, repeat, and residual hidden-state addition operations. The Markov route distribution is updated via feedback on training data and decoded using a top-k Viterbi algorithm to isolate high-probability candidate programs. We evaluate MACRO across diverse reasoning and knowledge benchmarks on multiple open-weight LLMs. MACRO achieves a +5.0% average accuracy improvement over the unrouted baselines, with largest gains on small models. We outperform the best dynamic routing approach Dr. LLM by +7.2%, while reducing route-search time 9.4x (from 14.8 to 1.6 hours). Our code is publicly available at this https URL.
### Title:
          MAVISEG: Manifold Propagation and Visual Prototypes for Zero-Shot Open-Vocabulary Segmentation in Diffusion Transformers
 - **Authors:** Rajatsubhra Chakraborty, Xujun Che, Ritabrata Chakraborty, Xi Niu, Depeng Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-image diffusion transformers learn about objects and scenes by learning to generate them, making them strong candidates for training-free zero-shot open-vocabulary semantic segmentation. State-of-the-art attribution methods score each pixel independently, comparing its features against a fixed text-derived class representation, whether as an output-space similarity or as a cross-attention weight. This discards structured signals the model itself exposes: the temporal structure of the generative trajectory, the visual appearance statistics of each concept, and the image's own pairwise feature geometry. We present MAVISEG, a training-free refinement layer that recovers these signals. Because its operators consume only a pixel-by-concept score field and a pixel feature space, MAVISEG is capture-agnostic rather than tied to one attribution method. Across six benchmarks it achieves the strongest overall results among training-free methods, including the best mIoU on every benchmark. Interestingly, gains are largest where the initial capture is weakest, and individual operators contribute depending on the noise in the field they refine. Our results indicate that diffusion transformers carry more concept-level information than current attribution methods recover, and that much of it is lost on the way to the mask rather than absent from the model.
### Title:
          Do Tabular Foundation Models Agree with Themselves?
 - **Authors:** Christian Klötergens, Vijaya Krishna Yalavarthi, Lars Schmidt-Thieme, Tom Hanika
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tabular Foundation Models (TFMs) are currently the best approach to tabular prediction problems. They are constructed as transformers that approximate the Bayesian posterior predictive distribution based on a pre-training prior. These univariate predictors can be converted into multivariate ones autoregressively by sampling one target and adding it to the features. However, the faithfulness of the resulting joint has not been investigated. Furthermore, TFMs cannot be evaluated against the posterior itself, at least not on real-world datasets, because the ground-truth distribution is unknown. We therefore propose asking a different question: could a model's predictions result from any joint distribution? To answer this question, we pose two requirements that any such model must satisfy. The first is marginalization consistency, which demands that marginalized conditionals are equal to directly predicted marginals. The second is factorization consistency, which demands that different factorization orders result in equal joint distributions. Every TFM that we evaluate violates both of these requirements for both classification and regression across all datasets.
### Title:
          Adaptive-WAM: Quality-Guided Early-Exit Planning from Intermediate Video-Diffusion Features
 - **Authors:** Sining Ang, Yuguang Yang, Yan Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large video diffusion models provide rich spatiotemporal priors for autonomous driving, but existing world-action models often inherit the cost of iterative future-video generation even though deployment only requires an ego trajectory. We ask a more basic question: how much of a video diffusion model must be executed to make a reliable driving decision? Through a controlled study of video denoising timesteps and Diffusion Transformer (DiT) depth, we find that planning performance is largely insensitive to the tested video-noise levels, whereas strong trajectories can already be decoded from intermediate layers. Based on this observation, we introduce Adaptive-WAM, a quality-aware multi-exit planner built on a Wan2.2-5B backbone. Trajectory diffusion heads are attached to selected DiT blocks, and a lightweight trajectory-quality scorer terminates inference once the best trajectory decoded so far satisfies a quality threshold; otherwise, computation continues from the cached hidden state to a deeper exit. The deployed planner therefore avoids the iterative classifier-free denoising loop and VAE decoding required for future-video synthesis, while dynamically allocating backbone depth according to trajectory quality. On NAVSIM, the adaptive single-trajectory planner achieves 90.8 PDMS; a separate fixed-exit variant reaches 92.6 PDMS with 64 proposals. It further obtains 89.9 EPDMS on NAVSIM v2, yielding the best reported results among the compared front-view video world-model planners. Without target-domain fine-tuning, Adaptive-WAM transfers to nuScenes with 0.88 m average L2 error and a 0.08\% collision rate. On an A100, adaptive routing improves PDMS from 90.62 to 90.79 while averaging 170 ms end-to-end planning latency, approximately 10\% below the 190 ms fixed block-15 planner and 47\% below the 320 ms fixed full-depth planner. Code will be released.
### Title:
          Wan-Animate-2: Pushing the Application Boundaries of Character Animation
 - **Authors:** Guangyuan Wang, Li Hu, Dechao Meng, Zhongyi Zhang, Peng Zhang, Mingyang Huang, Ruoshi Zhang, Ke Sun, Zhe Zhang, Xingjun Wang, Gang Cheng, Bang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Character image animation remains a foundational yet challenging task in computer vision. Existing approaches can be broadly categorized into three paradigms: methods based on explicit motion representations suffer from extraction errors and identity drift; methods based on implicit motion features lose fine-grained dynamics through compression; and in-context learning approaches avoid intermediate representations but incur prohibitive computational costs. Furthermore, all current systems are designed for offline synthesis, unable to meet the real-time requirements of interactive applications such as digital avatars and live-streaming hosts. To address these limitations, we present Wan-Animate-2, an end-to-end character animation framework that directly consumes the driving video within a redesigned Diffusion Transformer. Our architecture achieves superior motion fidelity and identity preservation by eliminating intermediate motion extractors entirely. We further introduce text driven viewpoint control that decouples the output camera perspective from the driving video--a capability rarely supported by prior character animation methods that rely on explicit motion representations. Beyond generation quality, we present Wan-Animate-2-Lite, an efficient variant that reduces inference latency to real-time thresholds through a three-stage training paradigm: teacher forcing pretraining with error buffer mechanism, and Self-Forcing distillation with chunk-wise backpropagation. This enables streaming character animation for interactive applications, opening new deployment scenarios that were previously infeasible. Qualitative evaluations and user studies demonstrate that Wan-Animate-2 achieves high-fidelity animation results across diverse characters and motion patterns. To foster further research and community development, we will release the Wan-Animate-2-Base model weights to the public.
### Title:
          Dense-Cast: A lightweight ensemble of deep learning architectures for precipitation nowcasting
 - **Authors:** Gourav Jyoti Kalita, Hidam Kumarjit Singh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Proper short-term forecasting of precipitation is crucial in disaster management and preparedness. Nonetheless, the variability and nonlinearity of precipitation make short-term forecasting challenging for meteorologists. Moreover, capturing temporal dependencies in spatiotemporal data is a challenge in precipitation nowcasting. In this article, we introduce a lightweight deep learning model for half-hourly precipitation nowcasting. This model has been designed by incorporating the DenseNet architecture, residual connections, and transformer encoders for effective precipitation nowcasting with reduced model parameters. The North-Eastern region of India has been selected as the area of interest for our study. The region receives the highest precipitation during the months of June-September due to the monsoon season. The proposed model takes the previous five time-steps of half-hourly precipitation as inputs and predicts the precipitation in the next two half-hours. The GPM IMERG precipitation dataset with a 30-minute cadence has been used in this study for training and testing the model. The proposed architecture achieves best MAE of 0.235 millimetres, RMSE of 0.735 millimetres, and KGE score of 0.816 at an interval of 30 minutes.
### Title:
          Beyond Sequence Order: Syntax-Informed Positional Embeddings for Transformers
 - **Authors:** Haris Riaz, Hyungji Kim, Mihai Surdeanu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Positional embeddings (PE) in Transformers encode token distance and order but are largely agnostic to \textit{syntactic structure}. We introduce \textbf{S}yntax-\textbf{i}nformed \textbf{P}ositional \textbf{E}mbeddings (\textbf{SiPE}), which learns a lightweight syntactic prior from dependency parses during pretraining and injects it across all three dominant PE families (absolute, relative, rotary), for both encoders and decoders, leaving self-attention and the rest of the architecture untouched. We isolate \emph{where} and \emph{how} the prior should enter the model, and find it depends on the architecture: for autoregressive decoders that use relative PE, the prior is strongest when coupled multiplicatively with the relative-position term of the attention score, outperforming injection into the input embeddings, into self-attention, or into the positional and attention terms jointly---while for encoders it is best added directly to the input embeddings, composing with each encoder's native positional mechanism. We find that models pre-trained with SiPE improve on the SyntaxGym benchmark by up to $10.3\%$ while simultaneously reducing perplexity by $9.0\%$ over a base model with no syntactic supervision---a metric nearly every existing syntax-injection method instead degrades. Crucially, these gains extend beyond syntactic generalization: SiPE also improves real-world language understanding, raising scores on the GLUE benchmark by up to $8.2\%$ over a model trained without it. Unlike existing syntactic language models that marginalize over many parses at inference or discard syntax at runtime, SiPE conditions on a single parse, establishing a new Pareto frontier between syntactic supervision and inference cost.
### Title:
          Confidence matters: Leveraging Multi-view Geometric Priors for GS-based Reconstruction
 - **Authors:** Hongyu Zhou, Zorah Lähner
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian splatting (3DGS) has emerged as a widely-used tool for novel view synthesis, offering real-time rendering in a sparse representation. However, the method's reliance on structure-from-motion initialization and photometric optimization can lead to suboptimal geometric reconstruction, particularly for objects with high specularity. In this work, we investigate the integration of geometric priors, in the form of predicted normal and depth maps, into the 3DGS framework to improve the reconstruction quality. We analyze the effect of incorporating these priors into GS-based methods and our evaluation reveals that multi-view predictions, as they are done by the recent visual geometry grounded transformer (VGGT), outperform single-view alternatives. A major factor is the existence of a confidence map for the estimations, which comes as a by-product of multi-view models and which can significantly improve the effectiveness of priors by weighting each prediction appropriately. Extensive experiments on standard benchmarks show consistent improvement in reconstruction quality and significant gains in complex scenes including specular objects.
### Title:
          Is Self-Pretraining really useful to improve diagnosis in medical Time Series?
 - **Authors:** Omar Coser, Antonio Orvieto, Paolo Soda, Loredana Zollo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inspired by recent evidence that transformer architectures benefit from Self-PreTraining (SPT) on long-context benchmarks, we investigate whether similar gains extend to multimodal, multivariate, and even simple univariate medical time series. Our objective is to assess the impact of SPT on the performance and scalability of transformer-based models across diverse medical applications, particularly under limited data conditions. We evaluate transformer architectures on three representative medical time-series tasks: rehabilitation robotics (Camargo dataset), stress detection (Non-EEG Stress), and Parkinson's disease detection (Gait Parkinson's Disease). Models are trained either from scratch or through SPT using four masking-based objectives designed to promote temporal and cross-modal representation learning, and we systematically vary model depth to examine how capacity interacts with pre-training benefits. Across datasets and configurations, SPT consistently improves classification accuracy by 0-6 percentage points depending on masking strategy, dataset and architecture, with gains observed not only in multivariate settings but also when models are restricted to simple univariate inputs. The improvements increase for deeper models that can better exploit the enriched temporal representations learned during pre-training. These findings indicate that SPT is a simple and general strategy that enhances transformer performance on medical time-series tasks without requiring task-specific architectural changes, supporting its potential to improve robustness and accuracy in data-limited clinical settings.
### Title:
          Audio-to-Score Transcription using Pre-trained Features, Data Augmentation, and the New SheetSage-A2S Dataset
 - **Authors:** Eoin Cummins, Zhongyi Huang, Alexandre D'Hooge, Zhuoro Mo, Yaolong Ju
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing audio-to-score (A2S) systems primarily focus on classical music, and the application to popular music remains underexplored. This paper first presents the new SheetSage-A2S Dataset, which includes 61 hours of audio with \texttt{**kern} score encodings for 9,468 clips originating from 6,066 unique songs, the first of its kind to facilitate A2S research for popular music. Additionally, we improve on existing A2S approaches by using data augmentation and MuQ, a pretrained feature-extraction model for music audio, to enhance generalisation abilities and extract meaningful audio features. Results show that the proposed A2S model achieves 4.98\% symbol error rate (SER) on the Quartets collection for classical music, which significantly outperforms the 15.3\% SER from the existing state-of-the-art \cite{alfaro-contrerasTransformer2024}. Additionally, our model achieves 20.92\% SER on the SheetSage-A2S dataset for popular music, serving as a strong benchmark for future research. The dataset, model, and code are made publicly available at: this https URL.
### Title:
          HOPE: Hand-Object Pressure Estimation from Monocular Videos
 - **Authors:** Subin Jeon, Byungjun Kim, Hanbyul Joo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Estimating physical pressure from vision is essential for understanding contact-rich hand-object interaction. However, prior vision-based pressure estimation methods are largely limited to planar surfaces and single image input, making them difficult to apply to dynamic hand-object interaction with diverse objects. We instead formulate pressure estimation as a hand-centric video prediction problem with monocular video as input. This formulation predicts temporally evolving per-vertex normal pressure and contact directly on the hand mesh, yielding a unified output space independent of object shape and sensor layout. Building on this formulation, we propose \textbf{HOPE}, a framework with two key components. First, we lift tactile-glove pressure, planar-sensor pressure, and distance-based hand-object contact annotations into a shared hand vertex space, allowing bare-hand contact data to regularize pressure learning where metric labels are unavailable. Second, we introduce a vertex-anchored video transformer that treats each vertex as a persistent token, aggregates visual features and hand pose over time, and uses a contact-gated pressure head to enforce that pressure vanishes without contact. Experiments on OpenTouch, PressureVisionDB, and hand-object contact benchmarks validate HOPE across object-pressure, surface-pressure, and contact-supervised HOI settings. Despite using metric pressure supervision primarily from gloved-hand videos, HOPE generalizes to bare-hand egocentric and in-the-wild videos, producing joint contact and pressure predictions beyond the scope of contact-only or planar-pressure baselines.
### Title:
          TS-RAG: Retrieval Augmented Generation for Time Series Forecasting
 - **Authors:** Yixiong Xiao, Congxi Xiao, Jingbo Zhou
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While deep learning models, particularly transformer-based architectures, have shown impressive performance in time series forecasting, the application of retrieval-augmented generation (RAG) in this domain remains limited. Since RAG has proven effective in enhancing the capabilities of large language models by incorporating relevant external information, retrieving similar time series sequences as references might also improve accuracy in time series forecasting tasks. However, most time series models are constrained by limited training data, smaller parameter scales, and a lack of the extensive generative capabilities found in large language models. Simply concatenating reference sequences into the prompt, as done in language models, may not yield the expected results. To address these challenges, we propose a novel approach, TS-RAG, which leverages RAG to enhance forecasting performance. The framework introduces specially designed reference tokens to effectively fuse information from the input sequence with that from retrieved similar sequences, enabling a more robust capture of complex temporal dynamics. Experimental results demonstrate that TS-RAG achieves consistent state-of-the-art performance across several real-world forecasting benchmarks.
### Title:
          EmoWorld: A Decoupled Affective Field for Controllable Emotional Video Generation
 - **Authors:** Bingyuan Wang, Baistan Zhyldyzbekov, Kunyu Feng, Zeyu Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Emotion shapes how viewers interpret a scene, yet existing video generators entangle global atmosphere, affect-bearing semantic cues, and temporal progression within a single text condition. We present EmoWorld, a framework that decouples these factors within a frozen flow-matching video diffusion transformer (Video DiT). A one-time preparation stage extracts layer-specific affect directions and a reusable cue library from geometry-preserving neutral and emotion-edited panoramas. At inference, Visual Atmosphere Steering (VAS) injects atmosphere directions into hidden states, Semantic Affective Steering (SAS) isolates a separately scalable prompt residual for semantic cues, and Temporal Affective Steering (TAS) interpolates endpoint residual fields across denoising and video time. On Wan2.2, VAS improves target-emotion alignment by 19% while reducing a temporal-fluctuation proxy by 48%; SAS improves target-emotion alignment by 37% and increases detected affect-bearing cues by 36%; and TAS improves transition monotonicity by 15% over the strongest baseline. EmoWorld is evaluated across 27 emotion categories in text-to-video and image-to-video settings, demonstrates portability across multiple Video-DiT backbones, and supports camera-conditioned composition without updating generator parameters.
### Title:
          Timestep-Conditioned Transformers for Global Weather Forecasting
 - **Authors:** Sam Levang, Fran Bartolic, Ty Dickinson, Chase Dwelle, Paulius Rauba, Viktor Cikojevic
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Operating Systems (cs.OS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing machine-learning weather forecasting models rely on predetermined and fixed autoregressive timesteps. The choice of model timestep involves a fundamental trade-off: shorter timesteps (e.g. 1 to 6 hours) finely resolve atmospheric dynamics within the diurnal cycle but increase error accumulation for a given forecast horizon, while longer timesteps (e.g. 24 hours) reduce error accumulation but limit the usability of short-range forecasts where sub-daily predictability is high. In this work, we present GEM-3, a probabilistic global weather model that addresses this trade-off through explicit multi-timestep inference. With a single set of trained weights, the model timestep can be configured at inference time to balance predictability and usability across a broad forecast horizon. Additionally, we find that mixed-timestep training consistently improves rollout stability relative to timestep-specialist models. Under the hood, GEM-3 is a lightweight neighborhood-attention transformer with ~134M parameters on an equirectangular grid with a number of architectural advancements beyond its predecessor GEM-2. The result is a practical forecasting system that couples near-SOTA medium-range probabilistic skill, stable extended-range rollouts, efficient training and inference, and decision-relevant diagnostics.
### Title:
          Bias Analysis of L2 Speaking Assessment Systems Using Concept Activation Vectors
 - **Authors:** Arya Labroo, Mengjie Qian, Kate Knill
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic speaking assessment systems are increasingly deployed in high-stakes settings to mark second language (L2) learners' speaking tests, making it critical to show that their scores depend on speaking proficiency rather than irrelevant speaker attributes such as first language (L1) or age. Transformer-based foundation models have improved the accuracy of these L2 speaking graders, but their black-box representations make fairness and interpretability analysis more difficult. Building on prior work that used Concept Activation Vectors (CAVs) to detect bias towards unwanted attributes (`concepts') in feature-based graders, we extend CAV-based analysis to two neural speaking assessment systems: a text-based BERT grader and a speech-and-text multimodal grader based on Whisper. CAVs represent human-interpretable concepts as directions in a model's activation space, allowing us to distinguish between whether a concept is encoded in a model's internal representations and whether it influences the predicted score, the latter quantified using a gradient-based sensitivity metric. Since CAVs rely on linear separability, which is less likely in complex neural embedding spaces, we also investigate whether sparse autoencoders (SAEs) provide cleaner concept directions by learning CAVs in a sparse latent space and mapping them back to activation space. Our analysis shows that concept recoverability depends strongly on the representation and architecture being probed, rather than on the concept alone. Sensitivity to concepts is also architecture-dependent. SAEs make concepts more linearly recoverable, but attenuate the original activation-space sensitivity, especially in low-dimensional layers. These findings highlight the need to distinguish concept recoverability from concept influence when auditing bias in speaking assessment systems.
## Keyword: autonomous driving
### Title:
          LoDA: A Level of Detection Aware Method and a Multimodal Sensing Benchmark for Object Level Change Detection
 - **Authors:** Haitian Wang, Xinyu Wang, Sheldon Fung, Xian Zhang, Zichen Geng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-definition 3D LiDAR maps are important for autonomous driving and smart-city services, which require reliable detection of object-level changes in multi-temporal urban LiDAR to keep digital maps aligned with the physical world. Existing approaches from raster height differencing to depth image and point-cloud networks often remain tile-based and threshold-driven, yielding per-point scores without explicit detection limits or consistent object-level labels. We propose an object-level 3D change-detection pipeline that integrates detection-limit-aware registration, geometry-driven object proxies with rule-based semantic and instance segmentation, and displacement cues in height, volume, and surface-normal direction to assign five change labels with confidence. By decoupling registration, geometry, and semantics, the pipeline propagates pose uncertainty into spatially varying detection limits, stabilizes cross-epoch correspondences, and suppresses false changes caused by residual misalignment and density variation. We also present LoDA, a level-of-detection (LoD) aware benchmark for the Subiaco district with fused multi-temporal vehicle-LiDAR maps constructed with LiDAR, GNSS, and IMU support, semantic instances, and object-level annotations. On this benchmark, our method achieves 95.0% accuracy, 90.8% macro F1, and 83.0% macro IoU, exceeding the best baseline by 8.7 IoU points and 4.4 F1 points. On the public Urb3DCD-V2 benchmark evaluated under the official point-wise protocol, it reaches 96.81% mean accuracy and 89.52% mean change IoU, improving over the strongest reported baselines by 1.36 points in mAcc and 3.18 points in mIoUch.
### Title:
          From Sports to Safety: Benchmarking Proactive Risk Inference in MLLMs
 - **Authors:** Jiawei Qiu, Yichen Xu, Jianzhe Ma, Mingyang Yu, Wenbin Zhu, Yang Han, Pinzheng Lv, Wenxuan Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Timely anticipation of physical hazards is essential for real-world safety, yet existing MLLM evaluations focus on harmful content or general risks, leaving proactive physical hazard prediction underexplored. Sports provide a well-suited testbed: accident causes span diverse injury dimensions and pre-accident spatiotemporal cues draw on reasoning capabilities shared with broader safety domains such as autonomous driving and fall detection. We introduce SPRINT (Sports Proactive Risk INference Testbed), a benchmark of 2,888 real-world sports videos (2,440 accident, 448 safe controls) spanning 14 sports and 3 environmental settings. Accident videos feature fine-grained annotations of early hazard cues, accident timing, and hierarchical causes; safe videos are manually verified as accident-free and serve to diagnose prompt-induced false alarms. Evaluating state-of-the-art MLLMs under diverse prompts and temporal windows reveals a sharp gap between hazard sensitivity and understanding: the best model exceeds 95% in signaling hazards yet falls below 50% in identifying their causes. Diagnostic experiments further show that explicit danger queries trigger severe false alarms even on hazard-free videos. These findings indicate that current MLLMs exhibit only superficial proactive safety, lacking stable, cause-grounded early warning, and underscore the need for reliable proactive safety in dynamic physical environments. Data and code will be open-sourced upon acceptance.
### Title:
          MEC-Patch: Visible-Infrared Cross-Modal Adversarial Attack Driven by Intrinsic Material Emissivity Laws
 - **Authors:** Zhixiang Huang, Xinbo Nie, Wenxuan Wang, Lu Yang, Xin Li, Xuelin Qian, Peng Wang
 - **Subjects:** Subjects:
Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the widespread deployment of visible-infrared multimodal perception systems in safety-critical domains such as autonomous driving, evaluating their cross-modal adversarial robustness has become increasingly vital. However, existing approaches exhibit significant limitations in approximating the intrinsic laws of imaging. Most studies either focus on a single modality, failing to bypass cross-modal verification, or simplify infrared modeling into heuristic pixel-intensity distributions, neglecting the impact of ambient temperature fluctuations on adversarial stability. To bridge this gap, this paper proposes MEC-Patch, a cross-modal adversarial attack framework driven by intrinsic physical laws. By leveraging the Stefan-Boltzmann Law, we establish a physics-grounded cross-spectral mapping that explicitly links material emissivity to thermal radiation. Building on this formulation, we reveal that, under a fixed emissivity distribution, ambient temperature variations induce consistent global scaling while preserving relative emissivity-induced contrast. We exploit this property to construct temperature-robust adversarial perturbations whose discriminative patterns remain stable in the infrared modality, thereby fundamentally mitigating environmental sensitivity. Furthermore, we employ the physics-constrained NSGA-II algorithm to synergistically optimize the material-distribution-based patch parameters effective across both modalities, while enhancing generalization through a Dynamic Adversarial Resampling (DAR) strategy. Experimental results demonstrate that MEC-Patch effectively deceives state-of-the-art multimodal detectors and exhibits high robustness within high-fidelity, physically-consistent, and multi-scene simulation environments. This research provides a physical-law-driven perspective for the security assessment of multimodal perception systems.
### Title:
          Adaptive-WAM: Quality-Guided Early-Exit Planning from Intermediate Video-Diffusion Features
 - **Authors:** Sining Ang, Yuguang Yang, Yan Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large video diffusion models provide rich spatiotemporal priors for autonomous driving, but existing world-action models often inherit the cost of iterative future-video generation even though deployment only requires an ego trajectory. We ask a more basic question: how much of a video diffusion model must be executed to make a reliable driving decision? Through a controlled study of video denoising timesteps and Diffusion Transformer (DiT) depth, we find that planning performance is largely insensitive to the tested video-noise levels, whereas strong trajectories can already be decoded from intermediate layers. Based on this observation, we introduce Adaptive-WAM, a quality-aware multi-exit planner built on a Wan2.2-5B backbone. Trajectory diffusion heads are attached to selected DiT blocks, and a lightweight trajectory-quality scorer terminates inference once the best trajectory decoded so far satisfies a quality threshold; otherwise, computation continues from the cached hidden state to a deeper exit. The deployed planner therefore avoids the iterative classifier-free denoising loop and VAE decoding required for future-video synthesis, while dynamically allocating backbone depth according to trajectory quality. On NAVSIM, the adaptive single-trajectory planner achieves 90.8 PDMS; a separate fixed-exit variant reaches 92.6 PDMS with 64 proposals. It further obtains 89.9 EPDMS on NAVSIM v2, yielding the best reported results among the compared front-view video world-model planners. Without target-domain fine-tuning, Adaptive-WAM transfers to nuScenes with 0.88 m average L2 error and a 0.08\% collision rate. On an A100, adaptive routing improves PDMS from 90.62 to 90.79 while averaging 170 ms end-to-end planning latency, approximately 10\% below the 190 ms fixed block-15 planner and 47\% below the 320 ms fixed full-depth planner. Code will be released.
