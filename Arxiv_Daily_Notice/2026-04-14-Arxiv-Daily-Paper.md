# Showing new listings for Tuesday, 14 April 2026
## Keyword: SLAM
### Title:
          3D Multi-View Stylization with Pose-Free Correspondences Matching for Robust 3D Geometry Preservation
 - **Authors:** Shirsha Bose
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artistic style transfer is well studied for images and videos, but extending it to multi-view 3D scenes remains difficult because stylization can disrupt correspondences needed by geometry-aware pipelines. Independent per-view stylization often causes texture drift, warped edges, and inconsistent shading, degrading SLAM, depth prediction, and multi-view reconstruction. This thesis addresses multi-view stylization that remains usable for downstream 3D tasks without assuming camera poses or an explicit 3D representation during training. We introduce a feed-forward stylization network trained with per-scene test-time optimization under a composite objective coupling appearance transfer with geometry preservation. Stylization is driven by an AdaIN-inspired loss from a frozen VGG-19 encoder, matching channel-wise moments to a style image. To stabilize structure across viewpoints, we propose a correspondence-based consistency loss using SuperPoint and SuperGlue, constraining descriptors from a stylized anchor view to remain consistent with matched descriptors from the original multi-view set. We also impose a depth-preservation loss using MiDaS/DPT and use global color alignment to reduce depth-model domain shift. A staged weight schedule introduces geometry and depth constraints. We evaluate on Tanks and Temples and Mip-NeRF 360 using image and reconstruction metrics. Style adherence and structure retention are measured by Color Histogram Distance (CHD) and Structure Distance (DSD). For 3D consistency, we use monocular DROID-SLAM trajectories and symmetric Chamfer distance on back-projected point clouds. Across ablations, correspondence and depth regularization reduce structural distortion and improve SLAM stability and reconstructed geometry; on scenes with MuVieCAST baselines, our method yields stronger trajectory and point-cloud consistency while maintaining competitive stylization.
### Title:
          MonoEM-GS: Monocular Expectation-Maximization Gaussian Splatting SLAM
 - **Authors:** Evgenii Kruzhkov, Sven Behnke
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feed-forward geometric foundation models can infer dense point clouds and camera motion directly from RGB streams, providing priors for monocular SLAM. However, their predictions are often view-dependent and noisy: geometry can vary across viewpoints and under image transformations, and local metric properties may drift between frames. We present MonoEM-GS, a monocular mapping pipeline that integrates such geometric predictions into a global Gaussian Splatting representation while explicitly addressing these inconsistencies. MonoEM-GS couples Gaussian Splatting with an Expectation--Maximization formulation to stabilize geometry, and employs ICP-based alignment for monocular pose estimation. Beyond geometry, MonoEM-GS parameterizes Gaussians with multi-modal features, enabling in-place open-set segmentation and other downstream queries directly on the reconstructed map. We evaluate MonoEM-GS on 7-Scenes, TUM RGB-D and Replica, and compare against recent baselines.
### Title:
          MR.ScaleMaster: Scale-Consistent Collaborative Mapping from Crowd-Sourced Monocular Videos
 - **Authors:** Hyoseok Ju, Giseop Kim
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Crowd-sourced cooperative mapping from monocular cameras promises scalable 3D reconstruction without specialized sensors, yet remains hindered by two scale-specific failure modes: abrupt scale collapse from false-positive loop closures in repetitive environments, and gradual scale drift over long trajectories and per-robot scale ambiguity that prevent direct multi-session fusion. We present this http URL, a cooperative mapping system for crowd-sourced monocular videos that addresses both failure modes. this http URL introduces three key mechanisms. First, a Scale Collapse Alarm rejects spurious loop closures before they corrupt the pose graph. Second, a Sim(3) anchor node formulation generalizes the classical SE(3) framework to explicitly estimate per-session scale, resolving per-robot scale ambiguity and enforcing global scale consistency. Third, a modular, open-source, plug-and-play interface enables any monocular reconstruction model to integrate without backend modification. On KITTI sequences with up to 15 agents, the Sim(3) formulation achieves a 7.2x ATE reduction over the SE(3) baseline, and the alarm rejects all false-positive loops while preserving every valid constraint. We further demonstrate heterogeneous multi-robot dense mapping fusing MASt3R-SLAM, pi3, and VGGT-SLAM 2.0 within a single unified map.
## Keyword: odometry
### Title:
          AWARE: Adaptive Whole-body Active Rotating Control for Enhanced LiDAR-Inertial Odometry under Human-in-the-Loop Interaction
 - **Authors:** Yizhe Zhang, Jianping Li, Liangliang Yin, Zhen Dong, Bisheng Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human-in-the-loop (HITL) UAV operation is essential in complex and safety-critical aerial surveying environments, where human operators provide navigation intent while onboard autonomy must maintain accurate and robust state estimation. A key challenge in this setting is that resource-constrained UAV platforms are often limited to narrow-field-of-view LiDAR sensors. In geometrically degenerate or feature-sparse scenes, limited sensing coverage often weakens LiDAR Inertial Odometry (LIO)'s observability, causing drift accumulation, degraded geometric accuracy, and unstable state estimation, which directly compromise safe and effective HITL operation and the reliability of downstream surveying products. To overcome this limitation, we present AWARE, a bio-inspired whole-body active yawing framework that exploits the UAV's own rotational agility to extend the effective sensor horizon and improve LIO's observability without additional mechanical actuation. The core of AWARE is a differentiable Model Predictive Control (MPC) framework embedded in a Reinforcement Learning (RL) loop. It first identifies the viewing direction that maximizes information gain across the full yaw space, and a lightweight RL agent then adjusts the MPC cost weights online according to the current environmental context, enabling an adaptive balance between estimation accuracy and flight stability. A Safe Flight Corridor mechanism further ensures operational safety within this HITL paradigm by decoupling the operator's navigational intent from autonomous yaw optimization to enable safe and efficient cooperative control. We validate AWARE through extensive experiments in diverse simulated and real-world environments.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Consensus-based Recursive Multi-Output Gaussian Process
 - **Authors:** Yogesh Prasanna Kumar Rao, Tamas Keviczky, Raj Thilak Rajan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-output Gaussian Processes provide principled uncertainty-aware learning of vector-valued fields but are difficult to deploy in large-scale, distributed, and streaming settings due to their computational and centralized nature. This paper proposes a Consensus-based Recursive Multi-Output Gaussian Process (CRMGP) framework that combines recursive inference on shared basis vectors with neighbour-to-neighbour information-consensus updates. The resulting method supports parallel, fully distributed learning with bounded per-step computation while preserving inter-output correlations and calibrated uncertainty. Experiments on synthetic wind fields and real LiDAR data demonstrate that CRMGP achieves competitive predictive performance and reliable uncertainty calibration, offering a scalable alternative to centralized Gaussian process models for multi-agent sensing applications.
### Title:
          ReaLiTy and LADS: A Unified Framework and Dataset Suite for LiDAR Adaptation Across Sensors and Adverse Weather Conditions
 - **Authors:** Vivek Anand, Bharat Lohani, Rakesh Mishra, Gaurav Pandey
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable LiDAR perception requires robustness across sensors, environments, and adverse weather. However, existing datasets rarely provide physically consistent observations of the same scene under varying sensor configurations and weather conditions, limiting systematic analysis of domain shifts. This work presents ReaLiTy, a unified physics-informed framework that transforms LiDAR data to match target sensor specifications and weather conditions. The framework integrates physically grounded cues with a learning-based module to generate realistic intensity patterns, while a physics-based weather model introduces consistent geometric and radiometric degradations. Building on this framework, we introduce the LiDAR Adaptation Dataset Suite (LADS), a collection of physically consistent, transformation-ready point clouds with one-to-one correspondence to original datasets. Experiments demonstrate improved cross-domain consistency and realistic weather effects. ReaLiTy and LADS provide a reproducible foundation for studying LiDAR adaptation and simulation-driven perception in intelligent transportation systems.
### Title:
          A Comparison of Multi-View Stereo Methods for Photogrammetric 3D Reconstruction: From Traditional to Learning-Based Approaches
 - **Authors:** Yawen Li, George Vosselman, Francesco Nex
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Photogrammetric 3D reconstruction has long relied on traditional Structure-from-Motion (SfM) and Multi-View Stereo (MVS) methods, which provide high accuracy but face challenges in speed and scalability. Recently, learning-based MVS methods have emerged, aiming for faster and more efficient reconstruction. This work presents a comparative evaluation between a representative traditional MVS pipeline (COLMAP) and state-of-the-art learning-based approaches, including geometry-guided methods (MVSNet, PatchmatchNet, MVSAnywhere, MVSFormer++) and end-to-end frameworks (Stereo4D, FoundationStereo, DUSt3R, MASt3R, Fast3R, VGGT). Two experiments were conducted on different aerial scenarios. The first experiment used the MARS-LVIG dataset, where ground-truth 3D reconstruction was provided by LiDAR point clouds. The second experiment used a public scene from the Pix4D official website, with ground truth generated by Pix4Dmapper. We evaluated accuracy, coverage, and runtime across all methods. Experimental results show that although COLMAP can provide reliable and geometrically consistent reconstruction results, it requires more computation time. In cases where traditional methods fail in image registration, learning-based approaches exhibit stronger feature-matching capability and greater robustness. Geometry-guided methods usually require careful dataset preparation and often depend on camera pose or depth priors generated by COLMAP. End-to-end methods such as DUSt3R and VGGT achieve competitive accuracy and reasonable coverage while offering substantially faster reconstruction. However, they exhibit relatively large residuals in 3D reconstruction, particularly in challenging scenarios.
### Title:
          Class-Adaptive Cooperative Perception for Multi-Class LiDAR-based 3D Object Detection in V2X Systems
 - **Authors:** Blessing Agyei Kyem, Joshua Kofi Asamoah, Armstrong Aboah
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cooperative perception allows connected vehicles and roadside infrastructure to share sensor observations, creating a fused scene representation beyond the capability of any single platform. However, most cooperative 3D object detectors use a uniform fusion strategy for all object classes, which limits their ability to handle the different geometric structures and point-sampling patterns of small and large objects. This problem is further reinforced by narrow evaluation protocols that often emphasize a single dominant class or only a few cooperation settings, leaving robust multi-class detection across diverse vehicle-to-everything interactions insufficiently explored. To address this gap, we propose a class-adaptive cooperative perception architecture for multi-class 3D object detection from LiDAR data. The model integrates four components: multi-scale window attention with learned scale routing for spatially adaptive feature extraction, a class-specific fusion module that separates small and large objects into attentive fusion pathways, bird's-eye-view enhancement through parallel dilated convolution and channel recalibration for richer contextual representation, and class-balanced objective weighting to reduce bias toward frequent categories. Experiments on the V2X-Real benchmark cover vehicle-centric, infrastructure-centric, vehicle-to-vehicle, infrastructure-to-infrastructure, and vehicle-to-infrastructure settings under identical backbone and training configurations. The proposed method consistently improves mean detection performance over strong intermediate-fusion baselines, with the largest gains on trucks, clear improvements on pedestrians, and competitive results on cars. These results show that aligning feature extraction and fusion with class-dependent geometry and point density leads to more balanced cooperative perception in realistic vehicle-to-everything deployments.
### Title:
          Roadside LiDAR for Cooperative Safety Auditing at Urban Intersections: Toward Auditable V2X Infrastructure Intelligence
 - **Authors:** Bo Shang, Yiqiao Li
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Urban intersections expose the limitations of single-vehicle perception under occlusion and partial observability. In this study, we present an auditable roadside LiDAR framework for infrastructure-assisted safety analysis at a signalized urban intersection in New York City, developed and evaluated using real-world data. The proposed framework integrates trajectory construction, iterative human-in-the-loop quality assurance (QA), and interpretable near-miss analytics to produce defensible safety evidence from infrastructure sensing. Using a human-labeled heavy vehicle--bicycle interaction as an anchor case, we show that direction-agnostic time-to-collision (TTC) drops below 1s, while longitudinal TTC remains above conservative braking thresholds, revealing a lateral-intrusion-dominated conflict mechanism. Beyond individual cases, continuous-window evaluation and multi-round QA analysis demonstrate that the framework systematically reduces failure modes such as track fragmentation, spurious TTC triggers, unstable geometry, and cross-lane false conflicts. These results position roadside LiDAR as a practical post-hoc auditing mechanism for cooperative perception systems, with broader statistical validation discussed. This work provides a pathway toward scalable, data-driven safety auditing of urban intersections, enabling transportation agencies to identify and mitigate high-risk interactions beyond crash-based analyses.
### Title:
          Israel-Hamas War on X: A Case Study of Coordinated Campaigns and Information Integrity
 - **Authors:** Tuğrulcan Elmas, Filipi Nascimento Silva, Manita Pote, Priyanka Dey, Keng-Chi Chang, Jinyi Ye, Luca Luceri, Cody Buntain, Emilio Ferrara, Alessandro Flammini, Fil Menczer
 - **Subjects:** Subjects:
Social and Information Networks (cs.SI); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Coordinated campaigns on social media play a critical role in shaping crisis information environments, particularly during the onset of conflicts when uncertainty is high and verified information is scarce. We study the interplay between coordinated campaigns and information integrity through a case study of the 2023 Israel-Hamas War on Twitter (X). We analyze 4.5~million tweets and employ established coordination detection methods to identify 11 coordinated groups involving 541 accounts. We characterize these groups through a multimodal analysis that includes topics, account amplification, toxicity, emotional tone, visual themes, and misleading claims. Our analysis reveal that coordinated campaigns rely predominantly on low-complexity tactics, such as retweet amplification and copy-paste diffusion, and promote distinct narratives consistent with a fragmented manipulation landscape, without centralized control. Widely amplified misleading claims concentrate within just three of the identified coordinated groups; the remaining groups primarily engage in advocacy, religious solidarity, or humanitarian mobilization. Claim-level integrity, toxicity, and emotional signals are mutually uncorrelated: no single behavioral signal is a reliable proxy for the others. Targeting the most prolific spreaders of misleading content for moderation would be effective in reducing such content. However, targeting prolific amplifiers in general would not achieve the same mitigation effect. These findings suggest that evaluating coordination structures jointly with their specific content footprints is needed to effectively prioritize moderation interventions.
### Title:
          AWARE: Adaptive Whole-body Active Rotating Control for Enhanced LiDAR-Inertial Odometry under Human-in-the-Loop Interaction
 - **Authors:** Yizhe Zhang, Jianping Li, Liangliang Yin, Zhen Dong, Bisheng Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human-in-the-loop (HITL) UAV operation is essential in complex and safety-critical aerial surveying environments, where human operators provide navigation intent while onboard autonomy must maintain accurate and robust state estimation. A key challenge in this setting is that resource-constrained UAV platforms are often limited to narrow-field-of-view LiDAR sensors. In geometrically degenerate or feature-sparse scenes, limited sensing coverage often weakens LiDAR Inertial Odometry (LIO)'s observability, causing drift accumulation, degraded geometric accuracy, and unstable state estimation, which directly compromise safe and effective HITL operation and the reliability of downstream surveying products. To overcome this limitation, we present AWARE, a bio-inspired whole-body active yawing framework that exploits the UAV's own rotational agility to extend the effective sensor horizon and improve LIO's observability without additional mechanical actuation. The core of AWARE is a differentiable Model Predictive Control (MPC) framework embedded in a Reinforcement Learning (RL) loop. It first identifies the viewing direction that maximizes information gain across the full yaw space, and a lightweight RL agent then adjusts the MPC cost weights online according to the current environmental context, enabling an adaptive balance between estimation accuracy and flight stability. A Safe Flight Corridor mechanism further ensures operational safety within this HITL paradigm by decoupling the operator's navigational intent from autonomous yaw optimization to enable safe and efficient cooperative control. We validate AWARE through extensive experiments in diverse simulated and real-world environments.
### Title:
          Ozone: A Unified Platform for Transportation Research
 - **Authors:** Ou Zheng, Ruyi Feng, Yufeng Yang, Shengxuan Ding, Lishengsa Yue, Ye Li, Yunhan Zheng, Minwei Kong, Dingyi Zhuang, Ao Qu, Zhibin Li, Dongjie Wang, Wangyang Ying
 - **Subjects:** Subjects:
Databases (cs.DB); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Intelligent Transportation Systems increasingly depend on heterogeneous data from roadside cameras, UAV imagery, LiDAR, and in-vehicle sensors, yet the lack of unified data standards, model interfaces, and evaluation protocols across these sources hampers reproducibility, cross-dataset benchmarking, and cross-region transferability of research findings. Existing trajectory datasets follow incompatible conventions for coordinate systems, object representations, and metadata fields, forcing researchers to build custom preprocessing pipelines for each dataset and simulator combination. To address these challenges, we propose Ozone, a unified platform for transportation research organized around five interconnected layers -- Hardware, Data, Model, Evaluation, and Prototype -- each with standardized schemas, automated conversion pipelines, and interoperable interfaces. In the first release, the data schema unifies four trajectory datasets -- NGSIM, highD, CitySim, and UTE -- into a canonical format with oriented bounding boxes, kinematic variables, and pre-computed surrogate safety measures. Digital-twin maps in CARLA and calibrated traffic models provide integrated benchmarking environments. Case studies in human-factor research, traffic scene generation, and safety-critical modeling demonstrate that Ozone reduces experiment setup time by 85%, achieves 91% cross-city transfer efficiency for safety models, and improves cross-dataset reproducibility to within 3% variance. The source code and datasets are publicly available.
### Title:
          Ψ-Map: Panoptic Surface Integrated Mapping Enables Real2Sim Transfer
 - **Authors:** Xuan Yu, Yuxuan Xie, Changjian Jiang, Shichao Zhai, Rong Xiong, Yu Zhang, Yue Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary panoptic reconstruction is essential for advanced robotics perception and simulation. However, existing methods based on 3D Gaussian Splatting (3DGS) often struggle to simultaneously achieve geometric accuracy, coherent panoptic understanding, and real-time inference frequency in large-scale scenes. In this paper, we propose a comprehensive framework that integrates geometric reinforcement, end-to-end panoptic learning, and efficient rendering. First, to ensure physical realism in large-scale environments, we leverage LiDAR data to construct plane-constrained multimodal Gaussian Mixture Models (GMMs) and employ 2D Gaussian surfels as the map representation, enabling high-precision surface alignment and continuous geometric supervision. Building upon this, to overcome the error accumulation and cumbersome cross-frame association inherent in traditional multi-stage panoptic segmentation pipelines, we design a query-guided end-to-end learning architecture. By utilizing a local cross-attention mechanism within the view frustum, the system lifts 2D mask features directly into 3D space, achieving globally consistent panoptic understanding. Finally, addressing the computational bottlenecks caused by high-dimensional semantic features, we introduce Precise Tile Intersection and a Top-K Hard Selection strategy to optimize the rendering pipeline. Experimental results demonstrate that our system achieves superior geometric and panoptic reconstruction quality in large-scale scenes while maintaining an inference rate exceeding 40 FPS, meeting the real-time requirements of robotic control loops.
### Title:
          LEADER: Learning Reliable Local-to-Global Correspondences for LiDAR Relocalization
 - **Authors:** Jianshi Wu, Minghang Zhu, Dunqiang Liu, Wen Li, Sheng Ao, Siqi Shen, Chenglu Wen, Cheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR relocalization has attracted increasing attention as it can deliver accurate 6-DoF pose estimation in complex 3D environments. Recent learning-based regression methods offer efficient solutions by directly predicting global poses without the need for explicit map storage. However, these methods often struggle in challenging scenes due to their equal treatment of all predicted points, which is vulnerable to noise and outliers. In this paper, we propose LEADER, a robust LiDAR-based relocalization framework enhanced by a simple, yet effective geometric encoder. Specifically, a Robust Projection-based Geometric Encoder architecture which captures multi-scale geometric features is first presented to enhance descriptiveness in geometric representation. A Truncated Relative Reliability loss is then formulated to model point-wise ambiguity and mitigate the influence of unreliable predictions. Extensive experiments on the Oxford RobotCar and NCLT datasets demonstrate that LEADER outperforms state-of-the-art methods, achieving 24.1% and 73.9% relative reductions in position error over existing techniques, respectively. The source code is released on this https URL.
### Title:
          EagleVision: A Multi-Task Benchmark for Cross-Domain Perception in High-Speed Autonomous Racing
 - **Authors:** Zakhar Yagudin, Murad Mebrahtu, Ren Jin, Jiaqi Huang, Yujia Yue, Dzmitry Tsetserukou, Jorge Dias, Majid Khonji
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-speed autonomous racing presents extreme perception challenges, including large relative velocities and substantial domain shifts from conventional urban-driving datasets. Existing benchmarks do not adequately capture these high-dynamic conditions. We introduce EagleVision, a unified LiDAR-based multi-task benchmark for 3D detection and trajectory prediction in high-speed racing, providing newly annotated 3D bounding boxes for the Indy Autonomous Challenge dataset (14,893 frames) and the A2RL Real competition dataset (1,163 frames), together with 12,000 simulator-generated annotated frames, all standardized under a common evaluation protocol. Using a dataset-centric transfer framework, we quantify cross-domain generalization across urban, simulator, and real racing domains. Urban pretraining improves detection over scratch training (NDS 0.72 vs. 0.69), while intermediate pretraining on real racing data achieves the best transfer to A2RL (NDS 0.726), outperforming simulator-only adaptation. For trajectory prediction, Indy-trained models surpass in-domain A2RL training on A2RL test sequences (FDE 0.947 vs. 1.250), highlighting the role of motion-distribution coverage in cross-domain forecasting. EagleVision enables systematic study of perception generalization under extreme high-speed dynamics. The dataset and benchmark are publicly available at this https URL
## Keyword: loop detection
### Title:
          Jailbreaking the Matrix: Nullspace Steering for Controlled Model Subversion
 - **Authors:** Vishal Pramanik, Maisha Maliha, Susmit Jha, Sumit Kumar Jha
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models remain vulnerable to jailbreak attacks -- inputs designed to bypass safety mechanisms and elicit harmful responses -- despite advances in alignment and instruction tuning. We propose Head-Masked Nullspace Steering (HMNS), a circuit-level intervention that (i) identifies attention heads most causally responsible for a model's default behavior, (ii) suppresses their write paths via targeted column masking, and (iii) injects a perturbation constrained to the orthogonal complement of the muted subspace. HMNS operates in a closed-loop detection-intervention cycle, re-identifying causal heads and reapplying interventions across multiple decoding attempts. Across multiple jailbreak benchmarks, strong safety defenses, and widely used language models, HMNS attains state-of-the-art attack success rates with fewer queries than prior methods. Ablations confirm that nullspace-constrained injection, residual norm scaling, and iterative re-identification are key to its effectiveness. To our knowledge, this is the first jailbreak method to leverage geometry-aware, interpretability-informed interventions, highlighting a new paradigm for controlled model steering and adversarial safety circumvention.
## Keyword: nerf
### Title:
          3D Multi-View Stylization with Pose-Free Correspondences Matching for Robust 3D Geometry Preservation
 - **Authors:** Shirsha Bose
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artistic style transfer is well studied for images and videos, but extending it to multi-view 3D scenes remains difficult because stylization can disrupt correspondences needed by geometry-aware pipelines. Independent per-view stylization often causes texture drift, warped edges, and inconsistent shading, degrading SLAM, depth prediction, and multi-view reconstruction. This thesis addresses multi-view stylization that remains usable for downstream 3D tasks without assuming camera poses or an explicit 3D representation during training. We introduce a feed-forward stylization network trained with per-scene test-time optimization under a composite objective coupling appearance transfer with geometry preservation. Stylization is driven by an AdaIN-inspired loss from a frozen VGG-19 encoder, matching channel-wise moments to a style image. To stabilize structure across viewpoints, we propose a correspondence-based consistency loss using SuperPoint and SuperGlue, constraining descriptors from a stylized anchor view to remain consistent with matched descriptors from the original multi-view set. We also impose a depth-preservation loss using MiDaS/DPT and use global color alignment to reduce depth-model domain shift. A staged weight schedule introduces geometry and depth constraints. We evaluate on Tanks and Temples and Mip-NeRF 360 using image and reconstruction metrics. Style adherence and structure retention are measured by Color Histogram Distance (CHD) and Structure Distance (DSD). For 3D consistency, we use monocular DROID-SLAM trajectories and symmetric Chamfer distance on back-projected point clouds. Across ablations, correspondence and depth regularization reduce structural distortion and improve SLAM stability and reconstructed geometry; on scenes with MuVieCAST baselines, our method yields stronger trajectory and point-cloud consistency while maintaining competitive stylization.
### Title:
          Fast-SegSim: Real-Time Open-Vocabulary Segmentation for Robotics in Simulation
 - **Authors:** Xuan Yu, Yuxuan Xie, Shichao Zhai, Shuhao Ye, Rong Xiong, Yue Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary panoptic reconstruction is crucial for advanced robotics and simulation. However, existing 3D reconstruction methods, such as NeRF or Gaussian Splatting variants, often struggle to achieve the real-time inference frequency required by robotic control loops. Existing methods incur prohibitive latency when processing the high-dimensional features required for robust open-vocabulary segmentation. We propose Fast-SegSim, a novel, simple, and end-to-end framework built upon 2D Gaussian Splatting, designed to realize real-time, high-fidelity, and 3D-consistent open-vocabulary segmentation reconstruction. Our core contribution is a highly optimized rendering pipeline that specifically addresses the computational bottleneck of high-channel segmentation feature accumulation. We introduce two key optimizations: Precise Tile Intersection to reduce rasterization redundancy, and a novel Top-K Hard Selection strategy. This strategy leverages the geometric sparsity inherent in the 2D Gaussian representation to greatly simplify feature accumulation and alleviate bandwidth limitations, achieving render rates exceeding 40 FPS. Fast-SegSim provides critical value in robotic applications: it serves both as a high-frequency sensor input for simulation platforms like Gazebo, and its 3D-consistent outputs provide essential multi-view 'ground truth' labels for fine-tuning downstream perception tasks. We demonstrate this utility by using the generated labels to fine-tune the perception module in object goal navigation, successfully doubling the navigation success rate. Our superior rendering speed and practical utility underscore Fast-SegSim's potential to bridge the sim-to-real gap.
## Keyword: mapping
### Title:
          VTC: DNN Compilation with Virtual Tensors for Data Movement Elimination
 - **Authors:** Muyan Hu, Ahan Gupta, Jiachen Yuan, Vima Gupta, Taeksang Kim, Xin Xu, Janardhan Kulkarni, Ofer Dekel, Vikram Adve, Charith Mendis
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Machine Learning (cs.LG); Programming Languages (cs.PL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the widening gap between compute and memory operation latencies, data movement optimizations have become increasingly important for DNN compilation. Current optimizations such as layout transformations and operator fusion only target a subset of tensor operators and consequently miss important opportunities for reducing data movement in contemporary DNN workloads, including large language models. We introduce VTC, a novel tensor compilation framework that for the first time eliminates all unnecessary data movement by targeting the full spectrum of data movement operators. VTC proposes the concept of virtual tensors to track data movement between compute operators via index mappings rather than expensive physical data transfers to and from global memory, which can seamlessly interoperate with existing computation kernels and handle arbitrary tensor operator compositions. We also introduce a novel data movement elimination algorithm to automatically identify a profitable virtual tensor creation strategy. Evaluation on a variety of DNNs shows that VTC can outperform existing ML compilers by up to 1.93x (1.28x on average) on NVIDIA GPUs with up to 60% (17.5% on average) inference memory savings.
### Title:
          Grid2Matrix: Revealing Digital Agnosia in Vision-Language Models
 - **Authors:** Yunkai Zhang, Linda Li, Yingxin Cui, Xiyuan Ruan, Zeyu Zheng, Kezhen Chen, Yi Zhang, Diji Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) excel on many multimodal reasoning benchmarks, but these evaluations often do not require an exhaustive readout of the image and can therefore obscure failures in faithfully capturing all visual details. We introduce Grid2Matrix (G2M), a controlled benchmark in which a model is shown a color grid and a color-to-number mapping, and must output the corresponding matrix. By varying grid size and the number of colors, G2M provides a simple way to increase visual complexity while minimizing semantic confounds. We find that VLMs exhibit a sharp early collapse in zero-shot end-to-end evaluation, failing on surprisingly small grids rather than degrading gradually as the task becomes denser. We probe the visual encoders of VLMs from two representative families and find that they preserve substantially more of the grid information than the corresponding end-to-end outputs. This suggests that the failure is not explained by visual encoding alone, but also reflects a gap between what remains recoverable from visual features and what is ultimately expressed in language. We term this gap \textit{Digital Agnosia}. Further analyses show that these errors are highly structured and depend strongly on how grid cells overlap with visual patch boundaries. We also find that common strategies such as model scaling and multimodal alignment do not fully eliminate this failure mode. We expect G2M to serve as a useful testbed for understanding where and how VLMs lose fine visual details, and for evaluating tasks where missing even small visual details can matter, such as tables, charts, forms, and GUIs.
### Title:
          Beyond Silicon: Materials, Mechanisms, and Methods for Physical Neural Computing
 - **Authors:** Stefan Fischer, Nihat Ay, Olaf Landsiedel, Esfandiar Mohammadi, Sebastian Otte, Bernd-Christian Renner, Nele Rußwinkel
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physical implementations of neural computation now extend far beyond silicon hardware, encompassing substrates such as memristive devices, photonic circuits, mechanical metamaterials, microfluidic networks, chemical reaction systems, and living neural tissue. By exploiting intrinsic physical processes such as charge transport, wave interference, elastic deformation, mass transport, and biochemical regulation, these substrates can realize neural inference and adaptation directly in matter. As silicon GPU-centered AI faces growing energy and data-movement constraints, physical neural computation is becoming increasingly relevant as a complementary path beyond conventional digital accelerators. This trend is driven in particular by pervasive intelligence, i.e., the deployment of on-device and edge AI across large numbers of resource-constrained systems. In such settings, co-locating computation with sensing and memory can reduce data shuttling and improve efficiency. Meanwhile, physical neural approaches have emerged across disparate disciplines, yet progress remains fragmented, with limited shared terminology and few principled ways to compare platforms. This survey unifies the field by mapping neural primitives to substrate-specific mechanisms, analyzing architectural and training paradigms, and identifying key engineering constraints including scalability, precision, programmability, and I/O interfacing overhead. To enable cross-domain comparison, we introduce a first-order benchmarking scheme based on standardized static and dynamic tasks and physically interpretable performance dimensions. We show that no single substrate dominates across the considered dimensions; instead, physical neural systems occupy complementary operating regimes, enabling applications ranging from ultrafast signal processing and in-memory inference to embodied control and in-sample biochemical decision making.
### Title:
          Learning Hierarchical and Geometry-Aware Graph Representations for Text-to-CAD
 - **Authors:** Shengjie Gong, Wenjie Peng, Hongyuan Chen, Gangyu Zhang, Yunqing Hu, Huiyuan Zhang, Shuangping Huang, Tianshui Chen
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-CAD code generation is a long-horizon task that translates textual instructions into long sequences of interdependent operations. Existing methods typically decode text directly into executable code (e.g., bpy) without explicitly modeling assembly hierarchy or geometric constraints, which enlarges the search space, accumulates local errors, and often causes cascading failures in complex assemblies. To address this issue, we propose a hierarchical and geometry-aware graph as an intermediate representation. The graph models multi-level parts and components as nodes and encodes explicit geometric constraints as edges. Instead of mapping text directly to code, our framework first predicts structure and constraints, then conditions action sequencing and code generation, thereby improving geometric fidelity and constraint satisfaction. We further introduce a structure-aware progressive curriculum learning strategy that constructs graded tasks through controlled structural edits, explores the model's capability boundary, and synthesizes boundary examples for iterative training. In addition, we build a 12K dataset with instructions, decomposition graphs, action sequences, and bpy code, together with graph- and constraint-oriented evaluation metrics. Extensive experiments show that our method consistently outperforms existing approaches in both geometric fidelity and accurate satisfaction of geometric constraints.
### Title:
          Global monitoring of methane point sources using deep learning on hyperspectral radiance measurements from EMIT
 - **Authors:** Vishal V. Batchu, Michelangelo Conserva, Alex Wilson, Anna M. Michalak, Varun Gulshan, Philip G. Brodrick, Andrew K. Thorpe, Christopher V. Arsdale
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Atmospheric and Oceanic Physics (physics.ao-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Anthropogenic methane (CH4) point sources drive near-term climate forcing, safety hazards, and system inefficiencies. Space-based imaging spectroscopy is emerging as a tool for identifying emissions globally, but existing approaches largely rely on manual plume identification. Here we present the Methane Analysis and Plume Localization with EMIT (MAPL-EMIT) model, an end-to-end vision transformer framework that leverages the complete radiance spectrum from the Earth Surface Mineral Dust Source Investigation (EMIT) instrument to jointly retrieve methane enhancements across all pixels within a scene. This approach brings together spectral and spatial context to significantly lower detection limits. MAPL-EMIT simultaneously supports enhancement quantification, plume delineation, and source localization, even for multiple overlapping plumes. The model was trained on 3.6 million physics-based synthetic plumes injected into global EMIT radiance data. Synthetic evaluation confirms the model's ability to identify plumes with high recall and precision and to capture weaker plumes relative to existing matched-filter approaches. On real-world benchmarks, MAPL-EMIT captures 79% of known hand-annotated NASA L2B plume complexes across a test set of 1084 EMIT granules, while capturing twice as many plausible plumes than identified by human analysts. Further validation against coincident airborne data, top-emitting landfills, and controlled release experiments confirms the model's ability to identify previously uncaptured sources. By incorporating model-generated metrics such as spectral fit scores and estimated noise levels, the framework can further limit false-positive rates. Overall, MAPL-EMIT enables high-throughput implementation on the full EMIT catalog, shifting methane monitoring from labor-intensive workflows to a rapid, scalable paradigm for global plume mapping at the facility scale.
### Title:
          WaveTune: Wave-aware Bilinear Modeling for Efficient GPU Kernel Auto-tuning
 - **Authors:** Kaixuan Zhang, Chutong Ding, Shiyou Qian, Luping Wang, Jian Cao, Guangtao Xue, Cheng Huang, Guodong Yang, Liping Zhang
 - **Subjects:** Subjects:
Performance (cs.PF); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid adoption of Large Language Models (LLMs) has made GPU inference efficiency an increasingly critical system concern. The runtime of LLM workloads is largely dominated by tile-based kernels, particularly General Matrix Multiplications (GEMMs). Although these kernels are highly optimized, their performance remains sensitive to a large space of runtime parameters, such as tile sizes and pipeline stages. The interaction between these parameters and hardware resources leads to a non-convex optimization landscape. Existing approaches to parameter configuration -- including search-based auto-tuning, heuristic rules, and learned cost models -- face a fundamental trade-off between performance optimality and runtime efficiency. In this paper, we present WaveTune, a wave-aware framework for runtime kernel auto-tuning. First, we introduce a unified mapping method to handle input diversity and decompose the configuration space to manage high dimensionality. Second, we develop an analytical wave-aware bilinear model that accurately predicts kernel latency. Third, we design a sparse sampling scheme based on wave structures and a lightweight dual-table retrieval mechanism to minimize runtime overhead. As a result, WaveTune enables precise and efficient runtime configuration for GPU kernels. Across three representative kernels and five GPU architectures, WaveTune consistently achieves near-optimal kernel performance, delivering up to 1.83x kernel-level speedup and up to 1.33x end-to-end TTFT reduction, while reducing runtime decision overhead by five orders of magnitude compared to exhaustive search. These results demonstrate that WaveTune effectively eliminates the traditional trade-off between configuration latency and execution optimality, providing a practical and robust solution for high-performance LLM inference.
### Title:
          FAITH: Factuality Alignment through Integrating Trustworthiness and Honestness
 - **Authors:** Xiaoning Dong, Chengyan Wu, Yajie Wen, Yu Chen, Yun Xue, Jing Zhang, Wei Xu, Bolei Ma
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) can generate factually inaccurate content even if they have corresponding knowledge, which critically undermines their reliability. Existing approaches attempt to mitigate this by incorporating uncertainty in QA prompt during training, but these numerical scores lack the semantic richness for LLM to properly understand its internal states of trustworthiness and honestness, leading to insufficient factuality alignment. We introduce FAITH (Factuality Alignment through Integrating Trustworthiness and Honestness), a post-training framework for factuality alignment that integrates natural-language uncertainty signals with external knowledge. Specifically, we augment training datasets by computing confidence scores and semantic entropy from LLM outputs and mapping them into a knowledge state quadrant that describes the model's internal knowledge possession (trustworthiness) and answering behaviors (honestness) in natural language. Based on this enhanced data, we design a reward function that considers both correctness and uncertainty signals, and fine-tune the LLM using the Proximal Policy Optimization (PPO) algorithm. To further mitigate weakly grounded responses, we design a retrieval-augmented module that retrieves relevant external passages, improving the consistency between internal and external knowledge representations. Extensive experiments on four knowledge-intensive benchmarks demonstrate that FAITH enhances the factual accuracy and truthfulness of LLMs.
### Title:
          A Dual-Positive Monotone Parameterization for Multi-Segment Bids and a Validity Assessment Framework for Reinforcement Learning Agent-based Simulation of Electricity Markets
 - **Authors:** Zunnan Xu, Zhaoxia Jing, Zhanhua Pan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning agent-based simulation (RL-ABS) has become an important tool for electricity market mechanism analysis and evaluation. In the modeling of monotone, bounded, multi-segment stepwise bids, existing methods typically let the policy network first output an unconstrained action and then convert it into a feasible bid curve satisfying monotonicity and boundedness through post-processing mappings such as sorting, clipping, or projection. However, such post-processing mappings often fail to satisfy continuous differentiability, injectivity, and invertibility at boundaries or kinks, thereby causing gradient distortion and leading to spurious convergence in simulation results. Meanwhile, most existing studies conduct mechanism analysis and evaluation mainly on the basis of training-curve convergence, without rigorously assessing the distance between the simulation outcomes and Nash equilibrium, which severely undermines the credibility of the results. To address these issues, this paper proposes...
### Title:
          Trajectory-based actuator identification via differentiable simulation
 - **Authors:** Vyacheslav Kovalev, Ekaterina Chaikovskaia, Egor Davydenko, Roman Gorbachev
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate actuation models are critical for bridging the gap between simulation and real robot behavior, yet obtaining high-fidelity actuator dynamics typically requires dedicated test stands and torque sensing. We present a trajectory-based actuator identification method that uses differentiable simulation to fit system-level actuator models from encoder motion alone. Identification is posed as a trajectory-matching problem: given commanded joint positions and measured joint angles and velocities, we optimize actuator and simulator parameters by backpropagating through the simulator, without torque sensors, current/voltage measurements, or access to embedded motor-control internals. The framework supports multiple model classes, ranging from compact structured parameterizations to neural actuator mappings, within a unified optimization pipeline. On held-out real-robot trajectories under identical commands, the proposed torque-sensor-free identification achieves much tighter trajectory alignment than a supervised stand-trained baseline dominated by steady-state data, reducing mean absolute position error from 14.20 mrad to as low as 7.54 mrad (1.88 times). Finally, we demonstrate downstream impact in a real-robot locomotion study: training policies with the refined actuator model increases travel distance by 46% and reduces rotational deviation by 75% relative to the baseline.
### Title:
          Battery health prognosis using Physics-informed neural network with Quantum Feature mapping
 - **Authors:** Muhammad Imran Hossain, Md Fazley Rafy, Sarika Khushlani Solanki, Anurag K. Srivastava
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate battery health prognosis using State of Health (SOH) estimation is essential for the reliability of multi-scale battery energy storage, yet existing methods are limited in generalizability across diverse battery chemistries and operating conditions. The inability of standard neural networks to capture the complex, high-dimensional physics of battery degradation is a major contributor to these limitations. To address this, a physics-informed neural network with the Quantum Feature Mapping(QFM) technique (QPINN) is proposed. QPINN projects raw battery sensor data into a high-dimensional Hilbert space, creating a highly expressive feature set that effectively captures subtle, non-linear degradation patterns using Nyström method. These quantum-enhanced features are then processed by a physics-informed network that enforces physical constraints. The proposed method achieves an average SOH estimation accuracy of 99.46\% across different datasets, substantially outperforming state-of-the-art baselines, with reductions in MAPE and RMSE of up to 65\% and 62\%, respectively. This method was validated on a large-scale, multi-chemistry dataset of 310,705 samples from 387 cells, and further showed notable adaptability in cross-validation settings, successfully transferring from one chemistry to another without relying on target-domain SOH labels.
### Title:
          GTASA: Ground Truth Annotations for Spatiotemporal Analysis, Evaluation and Training of Video Models
 - **Authors:** Nicolae Cudlenco, Mihai Masala, Marius Leordeanu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating complex multi-actor scenario videos remains difficult even for state-of-the-art neural generators, while evaluating them is hard due to the lack of ground truth for physical plausibility and semantic faithfulness. We introduce GTASA, a corpus of multi-actor videos with per-frame spatial relation graphs and event-level temporal mappings, and the system that produced it based on Graphs of Events in Space and Time (GEST): GEST-Engine. We compare our method with both open and closed source neural generators and prove both qualitatively (human evaluation of physical validity and semantic alignment) and quantitatively (via training video captioning models) the clear advantages of our method. Probing four frozen video encoders across 11 spatiotemporal reasoning tasks enabled by GTASA's exact 3D ground truth reveals that self-supervised encoders encode spatial structure significantly better than VLM visual encoders.
### Title:
          Leveraging Mathematical Reasoning of LLMs for Efficient GPU Thread Mapping
 - **Authors:** Jose Maureira, Cristóbal A. Navarro, Hector Ferrada, Luis Veas-Castillo
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mapping parallel threads onto non-box-shaped domains is a known challenge in GPU computing that, if done efficiently, can prevent severe performance penalties from allocating unnecessary computational resources. Currently, achieving this optimal efficiency requires significant analytical human time and effort to manually derive bespoke mapping functions for each specific geometry. This work introduces a novel approach leveraging the symbolic reasoning capabilities of Large Language Models (LLMs) to automate this mathematical derivation process entirely through in-context learning. Focusing on state-of-the-art open-weights models, we conducted a rigorous comparative analysis across spatial domains of increasing complexity. Our results demonstrate that modern local LLMs successfully infer exact O(1) and O(log N) mapping equations for complex 2D/3D dense domains and 2D fractals, vastly outperforming traditional symbolic regression methods which systematically failed at this discrete task. Crucially, we profile the energetic viability of this approach on high-performance infrastructure, drawing a clear distinction between the code-generation and execution phases. While the one-time inference of the equation incurs a high energy penalty -- particularly for reasoning-focused models like DeepSeek-R1 -- this is a single upfront investment. Once integrated, the generated analytical kernels eliminate block waste entirely, yielding massive repeated energy and time savings (e.g., up to 4833x speedup and 2890x energy reduction) during actual GPU workloads. Finally, we identify a current "reasoning ceiling" when these models face highly recursive 3D fractals tested in this work (e.g., the Menger Sponge). This limitation establishes a clear benchmark for the maturity of open-weight architectures, charting a viable and sovereign path toward fully automated, energy-efficient GPU resource optimization.
### Title:
          Entangled happily ever after: Wedding reception seating mapped to classical and quantum optimizers
 - **Authors:** Karie A. Nicholas Vikram Khipple Mulligan
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET); Quantum Physics (quant-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although optimization is one of the most promising applications of quantum computers, the development of effective optimization strategies requires real-world test cases. When planning our recent wedding reception, we realized that the problem of optimally seating our guests, given constraints related to guests' relatedness, shared interests, and physical needs, could be mapped to a cost function network (CFN) form solvable with classical or quantum optimization algorithms. We compared the seating optimization performance of classical Monte Carlo CFN solvers in the Masala software suite to that of quantum annealing-based CFN optimization algorithms using one-hot, domain-wall, and approximate binary mappings, which we had developed for protein design problems. Surprisingly, the D-Wave Advantage 2 system, which performs well on similarly-structured CFN problems for protein design, struggled to return optimal seating arrangements that were easily found by classical Monte Carlo methods. We provide our seating optimization benchmark set, and code to convert seating optimization problems to CFN problems, as a plugin library for Masala, permitting this class of real-world problems to be used to benchmark performance of current and future classical CFN solvers, quantum optimization algorithms, and quantum computing hardware.
### Title:
          BareBones: Benchmarking Zero-Shot Geometric Comprehension in VLMs
 - **Authors:** Aaditya Baranwal, Vishal Yadav, Abhishek Rajora
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Vision-Language Models (VLMs) demonstrate remarkable zero-shot recognition capabilities across a diverse spectrum of multimodal tasks, it yet remains an open question whether these architectures genuinely comprehend geometric structure or merely exploit RGB textures and contextual priors as statistical shortcuts. Existing evaluations fail to isolate this mechanism, conflating semantic reasoning with texture mapping and relying on imprecise annotations that inadvertently leak environmental cues. To address this gap, we introduce \textbf{BareBones}, a zero-shot benchmark designed to stress-test pure geometric shape comprehension. We curate pixel-level silhouettes of geometrically distinct classes across six datasets: five established segmentation sources (ImageNet-S, DIS5K, ThinObject5K, PASCAL VOC, CUB-200) and our novel flagship collection, WTP-Bench, establishing a noise-free geometric taxonomy. WTP-Bench is an extreme, fine-grained visual puzzle that forces models to identify inter-class geometric concepts from boundary contours alone. Our evaluation of 26 state-of-the-art proprietary and open-weight VLMs (\eg, GPT-4.1, Gemini, Claude Sonnet 4.5, LLaVA) reveals a consistent, severe performance collapse under RGB deprivation, a phenomenon we term the \textit{Texture Bias Cliff}. By documenting universal structural blindspots, BareBones establishes a rigorous yardstick for genuine geometric grounding.
### Title:
          Bidirectional Learning of Facial Action Units and Expressions via Structured Semantic Mapping across Heterogeneous Datasets
 - **Authors:** Jia Li, Yu Zhang, Yin Chen, Zhenzhen Hu, Yong Li, Richang Hong, Shiguang Shan, Meng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Facial action unit (AU) detection and facial expression (FE) recognition can be jointly viewed as affective facial behavior tasks, representing fine-grained muscular activations and coarse-grained holistic affective states, respectively. Despite their inherent semantic correlation, existing studies predominantly focus on knowledge transfer from AUs to FEs, while bidirectional learning remains insufficiently explored. In practice, this challenge is further compounded by heterogeneous data conditions, where AU and FE datasets differ in annotation paradigms (frame-level vs.\ clip-level), label granularity, and data availability and diversity, hindering effective joint learning. To address these issues, we propose a Structured Semantic Mapping (SSM) framework for bidirectional AU--FE learning under different data domains and heterogeneous supervision. SSM consists of three key components: (1) a shared visual backbone that learns unified facial representations from dynamic AU and FE videos; (2) semantic mediation via a Textual Semantic Prototype (TSP) module, which constructs structured semantic prototypes from fixed textual descriptions augmented with learnable context prompts, serving as supervision signals and cross-task alignment anchors in a shared semantic space; and (3) a Dynamic Prior Mapping (DPM) module that incorporates prior knowledge derived from the Facial Action Coding System and learns a data-driven association matrix in a high-level feature space, enabling explicit and bidirectional knowledge transfer. Extensive experiments on popular AU detection and FE recognition benchmarks show that SSM achieves state-of-the-art performance on both tasks simultaneously, and demonstrate that holistic expression semantics can in turn enhance fine-grained AU learning even across heterogeneous datasets.
### Title:
          Simple but Stable, Fast and Safe: Achieve End-to-end Control by High-Fidelity Differentiable Simulation
 - **Authors:** Fanxing Li, Shengyang Wang, Yuxiang Huang, Fangyu Sun, Yufei Yan, Danping Zou, Wenxian Yu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Obstacle avoidance is a fundamental vision-based task essential for enabling quadrotors to perform advanced applications. When planning the trajectory, existing approaches both on optimization and learning typically regard quadrotor as a point-mass model, giving path or velocity commands then tracking the commands by outer-loop controller. However, at high speeds, planned trajectories sometimes become dynamically infeasible in actual flight, which beyond the capacity of controller. In this paper, we propose a novel end-to-end policy that directly maps depth images to low-level bodyrate commands by reinforcement learning via differentiable simulation. The high-fidelity simulation in training after parameter identification significantly reduces all the gaps between training, simulation and real world. Analytical process by differentiable simulation provides accurate gradient to ensure efficiently training the low-level policy without expert guidance. The policy employs a lightweight and the most simple inference pipeline that runs without explicit mapping, backbone networks, primitives, recurrent structures, or backend controllers, nor curriculum or privileged guidance. By inferring low-level command directly to the hardware controller, the method enables full flight envelope control and avoids the dynamic-infeasible this http URL results demonstrate that the proposed approach achieves the highest success rate and the lowest jerk among state-of-the-art baselines across multiple benchmarks. The policy also exhibits strong generalization, successfully deploying zero-shot in unseen, outdoor environments while reaching speeds of up to 7.5m/s as well as stably flying in the super-dense forest.
### Title:
          Bridging Linguistic Gaps: Cross-Lingual Mapping in Pre-Training and Dataset for Enhanced Multilingual LLM Performance
 - **Authors:** Weihua Zheng, Chang Liu, Zhengyuan Liu, Xin Huang, Kui Wu, Muhammad Huzaifah Md Shahrin, Aiti Aw, Roy Ka-Wei Lee
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multilingual Large Language Models (LLMs) struggle with cross-lingual tasks due to data imbalances between high-resource and low-resource languages, as well as monolingual bias in pre-training. Existing methods, such as bilingual fine-tuning and contrastive alignment, can improve cross-lingual performance, but they often require extensive parallel data or suffer from instability. To address these challenges, we introduce a Cross-Lingual Mapping Task during the pre-training phase, which enhances cross-lingual alignment without compromising monolingual fluency. Our approach bi-directionally maps languages within the LLM embedding space, improving both language generation and comprehension. We further propose a Language Alignment Coefficient to robustly quantify cross-lingual consistency, even in limited-data scenarios. Experimental results on machine translation (MT), cross-lingual natural language understanding (CLNLU), and cross-lingual question answering (CLQA) show that our model achieves gains of up to 11.9 BLEU points in MT, 6.72 points in CLQA BERTScore-Precision, and more than 5% in CLNLU accuracy over strong multilingual baselines. These findings highlight the potential of incorporating cross-lingual objectives into pre-training to improve multilingual LLMs.
### Title:
          MonoEM-GS: Monocular Expectation-Maximization Gaussian Splatting SLAM
 - **Authors:** Evgenii Kruzhkov, Sven Behnke
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feed-forward geometric foundation models can infer dense point clouds and camera motion directly from RGB streams, providing priors for monocular SLAM. However, their predictions are often view-dependent and noisy: geometry can vary across viewpoints and under image transformations, and local metric properties may drift between frames. We present MonoEM-GS, a monocular mapping pipeline that integrates such geometric predictions into a global Gaussian Splatting representation while explicitly addressing these inconsistencies. MonoEM-GS couples Gaussian Splatting with an Expectation--Maximization formulation to stabilize geometry, and employs ICP-based alignment for monocular pose estimation. Beyond geometry, MonoEM-GS parameterizes Gaussians with multi-modal features, enabling in-place open-set segmentation and other downstream queries directly on the reconstructed map. We evaluate MonoEM-GS on 7-Scenes, TUM RGB-D and Replica, and compare against recent baselines.
### Title:
          Entropy-Rate Selection for Partially Observed Processes
 - **Authors:** Oleg Kiriukhin
 - **Subjects:** Subjects:
Information Theory (cs.IT); Econometrics (econ.EM); Probability (math.PR); Statistics Theory (math.ST)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 I formulate an entropy-rate maximization problem at the observable level for stochastic processes observed through an information-reducing observation map. For a visible stationary law, the map determines an observational fiber of hidden stationary laws generating that law. In the finite-state finite-memory setting, retained visible constraints determine a feasible class of stationary $(r+1)$-block laws, and the entropy maximizer is defined as the entropy-rate maximizer on this class. The paper formulates entropy-rate maximization on feasible classes induced by partial observability and develops a structural theory for the resulting maximizer. I prove existence and uniqueness of the maximizer, with uniqueness under a fixed-context-marginal hypothesis and, more generally, via a strict-concavity characterization by row proportionality. Two global characterization regimes are central: a fixed one-point marginal yields the i.i.d. maximizer, and a fixed $r$-block law yields the $(r-1)$-step Markov extension. The gap functional equals a conditional mutual information and vanishes exactly at the maximizing completion. I also derive optimality conditions, local geometry of the maximizer, a latent random-mapping realization that leaves the visible law unchanged, and a local empirical consistency theorem, and illustrate the framework by an aliased hidden-state example.
### Title:
          Enhancing Understandability and Transparency of Research Software: Tracing Research to Code
 - **Authors:** Adrian Bajraktari, Andreas Vogelsang
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern research heavily relies on software. A significant challenge researchers face is understanding the complex software used in specific research fields. We target two scenarios in this context, namely long onboarding times for newcomers and conference reviewers evaluating replication packages. We hypothesize that both scenarios can be significantly improved when there is a clear link between the paper's ideas and the code that implements them. As a time- and staff-saving approach, we propose an LLM-based automation tool that takes in a paper and the software implementing the paper, and generates a trace mapping between research ideas and their locations in code. Initial experiments have shown that the tool can generate quite useful mappings.
### Title:
          MeloTune: On-Device Arousal Learning and Peer-to-Peer Mood Coupling for Proactive Music Curation
 - **Authors:** Hongwei Xu
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 MeloTune is an iPhone-deployed music agent that instantiates the Mesh Memory Protocol (MMP) and Symbolic-Vector Attention Fusion (SVAF) as a production system for affect-aware music curation with peer-to-peer mood coupling. Each device runs two closed-form continuous-time (CfC) networks: a private listener-level CfC that predicts a short-horizon affective trajectory on Russell's circumplex and drives proactive curation, and a shared mesh-runtime CfC at MMP Layer 6 that integrates Cognitive Memory Blocks (CMBs) from co-listening peers. CfC hidden states never cross the wire; only structured CMBs do. A Personal Arousal Function (PAF) replaces the standard linear mapping from audio intensity to psychological arousal with a per-listener learned adjustment, trained from behavioral signals (skip, completion, favorite, volume) and from drift between user-declared mood and machine inference. The same track receives different arousal predictions for different listeners. The model (94,552 parameters) achieves trajectory MAE 0.414, pattern accuracy 96.6%, and intent accuracy 69.4% on held-out validation. PAF evidence from a live deployment session (46 observations across 11 genres) demonstrates that the learning loop operates end-to-end, with pop reaching full confidence after 22 observations. All inference runs on-device via CoreML. To our knowledge, this is the first production deployment of MMP/SVAF on consumer mobile hardware. The accompanying SDK (sym-swift v0.3.78, SYMCore v0.3.7) enforces strict protocol conformance. Music is the case study; the substrate is the contribution.
### Title:
          Energy-oriented Diffusion Bridge for Image Restoration with Foundational Diffusion Models
 - **Authors:** Jinhui Hou, Zhiyu Zhu, Junhui Hou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion bridge models have shown great promise in image restoration by explicitly connecting clean and degraded image distributions. However, they often rely on complex and high-cost trajectories, which limit both sampling efficiency and final restoration quality. To address this, we propose an Energy-oriented diffusion Bridge (E-Bridge) framework to approximate a set of low-cost manifold geodesic trajectories to boost the performance of the proposed method. We achieve this by designing a novel bridge process that evolves over a shorter time horizon and makes the reverse process start from an entropy-regularized point that mixes the degraded image and Gaussian noise, which theoretically reduces the required trajectory energy. To solve this process efficiently, we draw inspiration from consistency models to learn a single-step mapping function, optimized via a continuous-time consistency objective tailored for our trajectory, so as to analytically map any state on the trajectory to the target image. Notably, the trajectory length in our framework becomes a tunable task-adaptive knob, allowing the model to adaptively balance information preservation against generative power for tasks of varying degradation, such as denoising versus super-resolution. Extensive experiments demonstrate that our E-Bridge achieves state-of-the-art performance across various image restoration tasks while enabling high-quality recovery with a single or fewer sampling steps. Our project page is this https URL.
### Title:
          On Switched Event-triggered Full State-constrained Formation Control for Multi-vehicle Systems
 - **Authors:** Zihan Li, Ziming Wang, Xin Wang
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vehicular formation control is an important component of intelligent transportation systems (ITSs). In practical implementations, the controller design needs to satisfy multiple state constraints, including inter-vehicle spacing and vehicle speed. When system states approach the constraint boundaries, control singularity and excessive control effort may arise, which limits the practical applicability of existing methods. To address this problem, this paper investigates a class of nonlinear vehicular formation systems for autonomous vehicles (AVs) with uncertain dynamics and develops a switched event-triggered control framework. A smooth nonlinear mapping is first introduced to transform the constrained state space into an unconstrained one, thereby avoiding singularity near the constraint boundaries. A radial basis function neural network (RBFNN) is then employed to approximate the unknown nonlinear dynamics online, based on which an adaptive controller is constructed via the backstepping technique. In addition, a switched event-triggered mechanism (SETM) is designed to increase the control update frequency during the transient stage and reduce the communication burden during the steady-state stage. Lyapunov-based analysis proves that all signals in the closed-loop system remain uniformly bounded and that Zeno behavior is excluded. Simulation results verify that the proposed method achieves stable platoon formation under prescribed state constraints while significantly reducing communication updates.
### Title:
          Diffusion-CAM: Faithful Visual Explanations for dMLLMs
 - **Authors:** Haomin Zuo, Yidi Li, Luoxiao Yang, Xiaofeng Zhang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While diffusion Multimodal Large Language Models (dMLLMs) have recently achieved remarkable strides in multimodal generation, the development of interpretability mechanisms has lagged behind their architectural evolution. Unlike traditional autoregressive models that produce sequential activations, diffusion-based architectures generate tokens via parallel denoising, resulting in smooth, distributed activation patterns across the entire sequence. Consequently, existing Class Activation Mapping (CAM) methods, which are tailored for local, sequential dependencies, are ill-suited for interpreting these non-autoregressive behaviors. To bridge this gap, we propose Diffusion-CAM, the first interpretability method specifically tailored for dMLLMs. We derive raw activation maps by differentiably probing intermediate representations in the transformer backbone, accordingly capturing both latent features and their class-specific gradients. To address the inherent stochasticity of these raw signals, we incorporate four key modules to resolve spatial ambiguity and mitigate intra-image confounders and redundant token correlations. Extensive experiments demonstrate that Diffusion-CAM significantly outperforms SoTA methods in both localization accuracy and visual fidelity, establishing a new standard for understanding the parallel generation process of diffusion multimodal systems.
### Title:
          EgoFun3D: Modeling Interactive Objects from Egocentric Videos using Function Templates
 - **Authors:** Weikun Peng, Denys Iliash, Manolis Savva
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present EgoFun3D, a coordinated task formulation, dataset, and benchmark for modeling interactive 3D objects from egocentric videos. Interactive objects are of high interest for embodied AI but scarce, making modeling from readily available real-world videos valuable. Our task focuses on obtaining simulation-ready interactive 3D objects from egocentric video input. While prior work largely focuses on articulations, we capture general cross-part functional mappings (e.g., rotation of stove knob controls stove burner temperature) through function templates, a structured computational representation. Function templates enable precise evaluation and direct compilation into executable code across simulation platforms. To enable comprehensive benchmarking, we introduce a dataset of 271 egocentric videos featuring challenging real-world interactions with paired 3D geometry, segmentation over 2D and 3D, articulation and function template annotations. To tackle the task, we propose a 4-stage pipeline consisting of: 2D part segmentation, reconstruction, articulation estimation, and function template inference. Comprehensive benchmarking shows that the task is challenging for off-the-shelf methods, highlighting avenues for future work.
### Title:
          EmergentBridge: Improving Zero-Shot Cross-Modal Transfer in Unified Multimodal Embedding Models
 - **Authors:** Jincheng Xie, Xingchen Xiao, Runheng Liu, Zhongyi Huang, Yu Zheng, Heyan Huang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unified multimodal embedding spaces underpin practical applications such as cross-modal retrieval and zero-shot recognition. In many real deployments, however, supervision is available only for a small subset of modality pairs (e.g., image--text), leaving \emph{unpaired} modality pairs (e.g., audio$\leftrightarrow$depth, infrared$\leftrightarrow$audio) weakly connected and thus performing poorly on zero-shot transfer. Addressing this sparse-pairing regime is therefore essential for scaling unified embedding systems to new tasks without curating exhaustive pairwise data. We propose \textbf{EmergentBridge}, an embedding-level bridging framework that improves performance on these unpaired pairs \emph{without requiring exhaustive pairwise supervision}. Our key observation is that naively aligning a new modality to a synthesized proxy embedding can introduce \emph{gradient interference}, degrading the anchor-alignment structure that existing retrieval/classification relies on. EmergentBridge addresses this by (i) learning a mapping that produces a \emph{noisy bridge anchor} (a proxy embedding of an already-aligned modality) from an anchor embedding, and (ii) enforcing proxy alignment only in the subspace orthogonal to the anchor-alignment direction, preserving anchor alignment while strengthening non-anchor connectivity. Across nine datasets spanning multiple modalities, EmergentBridge consistently outperforms prior binding baselines on zero-shot classification and retrieval, demonstrating strong emergent alignment.
### Title:
          From Context to Rules: Toward Unified Detection Rule Generation
 - **Authors:** Cheng Meng, Wenxin Le, Xinyi Li, Qiuyun Wang, Fangli Ren, Zhengwei Jiang, Baoxu Liu
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing methods for detection rule generation are tightly coupled to specific input-output combinations, requiring dedicated pipelines for each. We formalize this problem as a unified mapping f:C*L->R and characterize optimal rules through semantic distance. We propose UniRule, an agentic RAG framework built on dual semantic projection spaces: detection intent and detection logic. This design enables retrieval and generation across arbitrary contexts and target languages within a single system. Experiments across 12 scenarios (3 languages, 4 context types, 12,000 pairwise comparisons) show that UniRule significantly outperforms pure LLM generation with a Bradley-Terry coefficient of 0.52, validating semantic projection as an effective abstraction for unified rule generation. Together, the formalization, method, and evaluation provide an initial framework for studying detection rule generation as a unified task.
### Title:
          MapATM: Enhancing HD Map Construction through Actor Trajectory Modeling
 - **Authors:** Mingyang Li, Brian Lee, Rui Zuo, Brent Bacchus, Priyantha Mudalige, Qinru Qiu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-definition (HD) mapping tasks, which perform lane detections and predictions, are extremely challenging due to non-ideal conditions such as view occlusions, distant lane visibility, and adverse weather conditions. Those conditions often result in compromised lane detection accuracy and reduced reliability within autonomous driving systems. To address these challenges, we introduce MapATM, a novel deep neural network that effectively leverages historical actor trajectory information to improve lane detection accuracy, where actors refer to moving vehicles. By utilizing actor trajectories as structural priors for road geometry, MapATM achieves substantial performance enhancements, notably increasing AP by 4.6 for lane dividers and mAP by 2.6 on the challenging NuScenes dataset, representing relative improvements of 10.1% and 6.1%, respectively, compared to strong baseline methods. Extensive qualitative evaluations further demonstrate MapATM's capability to consistently maintain stable and robust map reconstruction across diverse and complex driving scenarios, underscoring its practical value for autonomous driving applications.
### Title:
          Measuring the Authority Stack of AI Systems: Empirical Analysis of 366,120 Forced-Choice Responses Across 8 AI Models
 - **Authors:** Seulki Lee
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 What values, evidence preferences, and source trust hierarchies do AI systems actually exhibit when facing structured dilemmas? We present the first large-scale empirical mapping of AI decision-making across all three layers of the Authority Stack framework (S. Lee, 2026a): value priorities (L4), evidence-type preferences (L3), and source trust hierarchies (L2). Using the PRISM benchmark -- a forced-choice instrument of 14,175 unique scenarios per layer, spanning 7 professional domains, 3 severity levels, 3 decision timeframes, and 5 scenario variants -- we evaluated 8 major AI models at temperature 0, yielding 366,120 total responses. Key findings include: (1) a symmetric 4:4 split between Universalism-first and Security-first models at L4; (2) dramatic defense-domain value restructuring where Security surges to near-ceiling win-rates (95.1%-99.8%) in 6 of 8 models; (3) divergent evidence hierarchies at L3, with some models favoring empirical-scientific evidence while others prefer pattern-based or experiential evidence; (4) broad convergence on institutional source trust at L2; and (5) Paired Consistency Scores (PCS) ranging from 57.4% to 69.2%, revealing substantial framing sensitivity across scenario variants. Test-Retest Reliability (TRR) ranges from 91.7% to 98.6%, indicating that value instability stems primarily from variant sensitivity rather than stochastic noise. These findings demonstrate that AI models possess measurable -- if sometimes unstable -- Authority Stacks with consequential implications for deployment across professional domains.
### Title:
          RUMLEM: A Dictionary-Based Lemmatizer for Romansh
 - **Authors:** Dominic P. Fischer, Zachary Hopton, Jannis Vamvas
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lemmatization -- the task of mapping an inflected word form to its dictionary form -- is a crucial component of many NLP applications. In this paper, we present RUMLEM, a lemmatizer that covers the five main varieties of Romansh as well as the supra-regional standard variety Rumantsch Grischun. It is based on comprehensive, community-driven morphological databases for Romansh, enabling RUMLEM to cover 77-84% of the words in a typical Romansh text. Since there is a dedicated database for each Romansh variety, an additional application of RUMLEM is variety-aware language classification. Evaluation on 30'000 Romansh texts of varying lengths shows that RUMLEM correctly identifies the variety in 95% of cases. In addition, a proof of concept demonstrates the feasibility of Romansh vs. non-Romansh language classification based on the lemmatizer.
### Title:
          Bridging the RGB-IR Gap: Consensus and Discrepancy Modeling for Text-Guided Multispectral Detection
 - **Authors:** Jiaqi Wu, Zhen Wang, Enhao Huang, Kangqing Shen, Yulin Wang, Yang Yue, Yifan Pu, Gao Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-guided multispectral object detection uses text semantics to guide semantic-aware cross-modal interaction between RGB and IR for more robust perception. However, notable limitations remain: (1) existing methods often use text only as an auxiliary semantic enhancement signal, without exploiting its guiding role to bridge the inherent granularity asymmetry between RGB and IR; and (2) conventional data-driven attention-based fusion tends to emphasize stable consensus while overlooking potentially valuable cross-modal discrepancies. To address these issues, we propose a semantic bridge fusion framework with bi-support modeling for multispectral object detection. Specifically, text is used as a shared semantic bridge to align RGB and IR responses under a unified category condition, while the recalibrated thermal semantic prior is projected onto the RGB branch for semantic-level mapping fusion. We further formulate RGB-IR interaction evidence into the regular consensus support and the complementary discrepancy support that contains potentially discriminative cues, and introduce them into fusion via dynamic recalibration as a structured inductive bias. In addition, we design a bidirectional semantic alignment module for closed-loop vision-text guidance enhancement. Extensive experiments demonstrate the effectiveness of the proposed fusion framework and its superior detection performance on multispectral benchmarks. Code is available at this https URL.
### Title:
          BRIDGE and TCH-Net: Heterogeneous Benchmark and Multi-Branch Baseline for Cross-Domain IoT Botnet Detection
 - **Authors:** Ammar Bhilwarawala, Likhamba Rongmei, Harsh Sharma, Arya Jena, Kaushal Singh, Jayashree Piri, Raghunath Dey
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 IoT botnet detection has advanced, yet most published systems are validated on a single dataset and rarely generalise across environments. Heterogeneous feature spaces make multi-dataset training practically impossible without discarding semantic interpretability or introducing data integrity violations. No prior work has addressed both problems with a formally specified, reproducible methodology. This paper does. We introduce BRIDGE (Benchmark Reference for IoT Domain Generalisation Evaluation), the first formally specified heterogeneous multi-dataset benchmark for IoT intrusion detection, unifying CICIDS-2017, CIC-IoT-2023, Bot-IoT, Edge-IIoTset, and N-BaIoT through a 46-feature semantic canonical vocabulary grounded in CICFlowMeter nomenclature, with genuine-equivalence-only feature mapping, explicit zero-filling, and per-dataset coverage from 15% to 93%. A leave-one-dataset-out (LODO) protocol makes the generalisation gap precisely measurable: all five evaluated architectures achieve mean LODO F1 between 0.39 and 0.47, and we establish the first community generalisation baseline at mean LODO F1 = 0.5577, a result that shifts the agenda from single-benchmark optimisation toward cross-environment generalisation. We propose TCH-Net, a multi-branch network fusing a three-path Temporal branch (residual convolutional-BiGRU, stride-downsampled BiGRU, pre-LayerNorm Transformer), a provenance-conditioned Contextual branch, and a Statistical branch via Cross-Branch Gated Attention Fusion (CB-GAF) with learnable sigmoid gates for dynamic feature-wise mixing. Across five random seeds, TCH-Net achieves F1 = 0.8296 +/- 0.0028, AUC = 0.9380 +/- 0.0025, and MCC = 0.6972 +/- 0.0056, outperforming all twelve baselines (p < 0.05, Wilcoxon) and recording the highest LODO F1 overall. BRIDGE and the full pipeline are at this https URL.
### Title:
          LoGo-MR: Screening Breast MRI for Cancer Risk Prediction by Efficient Omni-Slice Modeling
 - **Authors:** Xin Wang, Yuan Gao, George Yiasemis, Antonio Portaluri, Zahra Aghdam, Muzhen He, Luyi Han, Yaofei Duan, Chunyao Lu, Xinglong Liang, Tianyu Zhang, Vivien van Veldhuizen, Yue Sun, Tao Tan, Ritse Mann, Jonas Teuwen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient and explainable breast cancer (BC) risk prediction is critical for large-scale population-based screening. Breast MRI provides functional information for personalized risk assessment. Yet effective modeling remains challenging as fully 3D CNNs capture volumetric context at high computational cost, whereas lightweight 2D CNNs fail to model inter-slice continuity. Importantly, breast MRI modeling for shor- and long-term BC risk stratification remains underexplored. In this study, we propose LoGo-MR, a 2.5D local-global structural modeling framework for five-year BC risk prediction. Aligned with clinical interpretation, our framework first employs neighbor-slice encoding to capture subtle local cues linked to short-term risk. It then integrates transformer-enhanced multiple-instance learning (MIL) to model distributed global patterns related to long-term risk and provide interpretable slice importance. We further apply this framework across axial, sagittal, and coronal planes as LoGo3-MR to capture complementary volumetric information. This multi-plane formulation enables voxel-level risk saliency mapping, which may assist radiologists in localizing risk-relevant regions during breast MRI interpretation. Evaluated on a large breast MRI screening cohort (~7.5K), our method outperforms 2D/3D baselines and existing SOTA MIL methods, achieving AUCs of 0.77-0.69 for 1- to 5-year prediction and improving C-index by ~6% over 3D CNNs. LoGo3-MR further improves overall performance with interpretable localization across three planes, and validation across seven backbones shows consistent gains. These results highlight the clinical potential of efficient MRI-based BC risk stratification for large-scale screening. Code will be released publicly.
### Title:
          MR.ScaleMaster: Scale-Consistent Collaborative Mapping from Crowd-Sourced Monocular Videos
 - **Authors:** Hyoseok Ju, Giseop Kim
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Crowd-sourced cooperative mapping from monocular cameras promises scalable 3D reconstruction without specialized sensors, yet remains hindered by two scale-specific failure modes: abrupt scale collapse from false-positive loop closures in repetitive environments, and gradual scale drift over long trajectories and per-robot scale ambiguity that prevent direct multi-session fusion. We present this http URL, a cooperative mapping system for crowd-sourced monocular videos that addresses both failure modes. this http URL introduces three key mechanisms. First, a Scale Collapse Alarm rejects spurious loop closures before they corrupt the pose graph. Second, a Sim(3) anchor node formulation generalizes the classical SE(3) framework to explicitly estimate per-session scale, resolving per-robot scale ambiguity and enforcing global scale consistency. Third, a modular, open-source, plug-and-play interface enables any monocular reconstruction model to integrate without backend modification. On KITTI sequences with up to 15 agents, the Sim(3) formulation achieves a 7.2x ATE reduction over the SE(3) baseline, and the alarm rejects all false-positive loops while preserving every valid constraint. We further demonstrate heterogeneous multi-robot dense mapping fusing MASt3R-SLAM, pi3, and VGGT-SLAM 2.0 within a single unified map.
### Title:
          EdgeCIM: A Hardware-Software Co-Design for CIM-Based Acceleration of Small Language Models
 - **Authors:** Jinane Bazzi, Mariam Rakka, Fadi Kurdahi, Mohammed E. Fouda, Ahmed Eltawil
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The growing demand for deploying Small Language Models (SLMs) on edge devices, including laptops, smartphones, and embedded platforms, has exposed fundamental inefficiencies in existing accelerators. While GPUs handle prefill workloads efficiently, the autoregressive decoding phase is dominated by GEMV operations that are inherently memory-bound, resulting in poor utilization and prohibitive energy costs at the edge. In this work, we present EdgeCIM, a hardware-software co-design framework that rethinks accelerator design for end-to-end decoder-only inference. At its core is a CIM macro, implemented in 65nm, coupled with a tile-based mapping strategy that balances pipeline stages, maximizing parallelism while alleviating DRAM bandwidth bottlenecks. Our simulator enables design space exploration of SLMs up to 4B parameters, identifying Pareto-optimal configurations in terms of latency and energy. Compared to an NVIDIA Orin Nano, EdgeCIM achieves up to 7.3x higher throughput and 49.59x better energy efficiency on LLaMA3.2-1B, and delivers 9.95x higher throughput than Qualcomm SA8255P on LLaMA3.2-3B. Extensive benchmarks on TinyLLaMA-1.1B, LLaMA3.2 (1B, 3B), Phi-3.5-mini-3.8B, Qwen2.5 (0.5B, 1.5B, 3B), SmolLM2-1.7B, SmolLM3-3B, and Qwen3 (0.6B, 1.7B, 4B) reveal that our accelerator, under INT4 precision, achieves on average 336.42 tokens/s and 173.02 tokens/J. These results establish EdgeCIM as a compelling solution towards real-time, energy-efficient edge-scale SLM inference.
### Title:
          Progressively Texture-Aware Diffusion for Contrast-Enhanced Sparse-View CT
 - **Authors:** Tianqi Wang, Wenchao Du, Hongyu Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Medical Physics (physics.med-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion-based sparse-view CT (SVCT) imaging has achieved remarkable advancements in recent years, thanks to its more stable generative capability. However, recovering reliable image content and visually consistent textures is still a crucial challenge. In this paper, we present a Progressively Texture-aware Diffusion (PTD) model, a coarse-to-fine learning framework tailored for SVCT. Specifically, PTD comprises a basic reconstructive module PTD$_{\textit{rec}}$ and a conditional diffusion module PTD$_{\textit{diff}}$. PTD$_{\textit{rec}}$ first learns a deterministic mapping to recover the majority of the underlying low-frequency signals (i.e., coarse content with smoothed textures), which serves as the initial estimation to enable fidelity. Moreover, PTD$_{\textit{diff}}$ aims to reconstruct high-fidelity details for coarse prediction, which explores a dual-domain guided conditional diffusion to generate reliable and consistent textures. Extensive experiments on sparse-view CT reconstruction demonstrate that our PTD achieves superior performance in terms of structure similarity and visual appeal with only a few sampling steps, which mitigates the randomness inherent in general diffusion models and enables a better trade-off between visual quality and fidelity of high-frequency details.
### Title:
          A Triadic Suffix Tokenization Scheme for Numerical Reasoning
 - **Authors:** Olga Chetverina
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard subword tokenization methods fragment numbers inconsistently, causing large language models (LLMs) to lose positional and decimal structure - a primary driver of errors in arithmetic and scientific reasoning. We introduce Triadic Suffix Tokenization (TST), a deterministic scheme that partitions digits into three-digit triads and annotates each triad with an explicit magnitude marker. Critically, the scheme defines a fixed, one-to-one mapping between suffixes and orders of magnitude for the integer part (thousands, millions, billions, etc.) and a parallel system of replicated markers for fractional depth (tenths, thousandths, millionths, etc.). Unlike approaches that rely on positional inference, this method provides a consistent gradient signal, which should ensure stable convergence. Two implementation variants are proposed: (1) a vocabulary-based approach that adds at most 10,000 fixed tokens to an existing vocabulary, covering 33 orders of magnitude ($10^{-15}$ to $10^{18}$); and (2) a suffix-marker approach that uses a small set of special tokens to denote magnitude dynamically. Both variants preserve exact digits while making order-of-magnitude relationships transparent at the token level. The framework is inherently scalable, allowing for linear vocabulary expansion to accommodate arbitrary precision and range. TST is architecture-agnostic and can be integrated as a drop-in preprocessing step. Experimental validation is deferred to future work.
## Keyword: localization
### Title:
          Tuning Qwen2.5-VL to Improve Its Web Interaction Skills
 - **Authors:** Alexandra Yakovleva, Henrik Pärssinen, Harri Valpola, Juho Kannala, Alexander Ilin
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in vision-language models (VLMs) have sparked growing interest in using them to automate web tasks, yet their feasibility as independent agents that reason and act purely from visual input remains underexplored. We investigate this setting using Qwen2.5-VL-32B, one of the strongest open-source VLMs available, and focus on improving its reliability in web-based control. Through initial experimentation, we observe three key challenges: (i) inaccurate localization of target elements, the cursor, and their relative positions, (ii) sensitivity to instruction phrasing, and (iii) an overoptimistic bias toward its own actions, often assuming they succeed rather than analyzing their actual outcomes. To address these issues, we fine-tune Qwen2.5-VL-32B for a basic web interaction task: moving the mouse and clicking on a page element described in natural language. Our training pipeline consists of two stages: (1) teaching the model to determine whether the cursor already hovers over the target element or whether movement is required, and (2) training it to execute a single command (a mouse move or a mouse click) at a time, verifying the resulting state of the environment before planning the next action. Evaluated on a custom benchmark of single-click web tasks, our approach increases success rates from 86% to 94% under the most challenging setting.
### Title:
          TRACE: Thermal Recognition Attentive-Framework for CO2 Emissions from Livestock
 - **Authors:** Taminul Islam, Abdellah Lakhssassi, Toqi Tahamid Sarker, Mohamed Embaby, Khaled R Ahmed, Amer AbuGhazaleh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Quantifying exhaled CO2 from free-roaming cattle is both a direct indicator of rumen metabolic state and a prerequisite for farm-scale carbon accounting, yet no existing system can deliver continuous, spatially resolved measurements without physical confinement or contact. We present TRACE (Thermal Recognition Attentive-Framework for CO2 Emissions from Livestock), the first unified framework to jointly address per-frame CO2 plume segmentation and clip-level emission flux classification from mid-wave infrared (MWIR) thermal video. TRACE contributes three domain-specific advances: a Thermal Gas-Aware Attention (TGAA) encoder that incorporates per-pixel gas intensity as a spatial supervisory signal to direct self-attention toward high-emission regions at each encoder stage; an Attention-based Temporal Fusion (ATF) module that captures breath-cycle dynamics through structured cross-frame attention for sequence-level flux classification; and a four-stage progressive training curriculum that couples both objectives while preventing gradient interference. Benchmarked against fifteen state-of-the-art models on the CO2 Farm Thermal Gas Dataset, TRACE achieves an mIoU of 0.998 and the best result on every segmentation and classification metric simultaneously, outperforming domain-specific gas segmenters with several times more parameters and surpassing all baselines in flux classification. Ablation studies confirm that each component is individually essential: gas-conditioned attention alone determines precise plume boundary localization, and temporal reasoning is indispensable for flux-level discrimination. TRACE establishes a practical path toward non-invasive, continuous, per-animal CO2 monitoring from overhead thermal cameras at commercial scale. Codes are available at this https URL.
### Title:
          Identity-Aware U-Net: Fine-grained Cell Segmentation via Identity-Aware Representation Learning
 - **Authors:** Rui Xiao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precise segmentation of objects with highly similar shapes remains a challenging problem in dense prediction, especially in scenarios with ambiguous boundaries, overlapping instances, and weak inter-instance visual differences. While conventional segmentation models are effective at localizing object regions, they often lack the discriminative capacity required to reliably distinguish a target object from morphologically similar distractors. In this work, we study fine-grained object segmentation from an identity-aware perspective and propose Identity-Aware U-Net (IAU-Net), a unified framework that jointly models spatial localization and instance discrimination. Built upon a U-Net-style encoder-decoder architecture, our method augments the segmentation backbone with an auxiliary embedding branch that learns discriminative identity representations from high-level features, while the main branch predicts pixel-accurate masks. To enhance robustness in distinguishing objects with near-identical contours or textures, we further incorporate triplet-based metric learning, which pulls target-consistent embeddings together and separates them from hard negatives with similar morphology. This design enables the model to move beyond category-level segmentation and acquire a stronger capability for precise discrimination among visually similar objects. Experiments on benchmarks including cell segmentation demonstrate promising results, particularly in challenging cases involving similar contours, dense layouts, and ambiguous boundaries.
### Title:
          MuPPet: Multi-person 2D-to-3D Pose Lifting
 - **Authors:** Thomas Markhorst, Zhi-Yi Lin, Jouh Yeong Chew, Jan van Gemert, Xucong Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-person social interactions are inherently built on coherence and relationships among all individuals within the group, making multi-person localization and body pose estimation essential to understanding these social dynamics. One promising approach is 2D-to-3D pose lifting which provides a 3D human pose consisting of rich spatial details by building on the significant advances in 2D pose estimation. However, the existing 2D-to-3D pose lifting methods often neglect inter-person relationships or cannot handle varying group sizes, limiting their effectiveness in multi-person settings. We propose MuPPet, a novel multi-person 2D-to-3D pose lifting framework that explicitly models inter-person correlations. To leverage these inter-person dependencies, our approach introduces Person Encoding to structure individual representations, Permutation Augmentation to enhance training diversity, and Dynamic Multi-Person Attention to adaptively model correlations between individuals. Extensive experiments on group interaction datasets demonstrate MuPPet significantly outperforms state-of-the-art single- and multi-person 2D-to-3D pose lifting methods, and improves robustness in occlusion scenarios. Our findings highlight the importance of modeling inter-person correlations, paving the way for accurate and socially-aware 3D pose estimation. Our code is available at: this https URL
### Title:
          ACCIDENT: A Benchmark Dataset for Vehicle Accident Detection from Traffic Surveillance Videos
 - **Authors:** Lukas Picek, Michal Čermák, Marek Hanzl, Vojtěch Čermák
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce ACCIDENT, a benchmark dataset for traffic accident detection in CCTV footage, designed to evaluate models in supervised (IID and OOD) and zero-shot settings, reflecting both data-rich and data-scarce scenarios. The benchmark consists of a curated set of 2,027 real and 2,211 synthetic clips annotated with the accident time, spatial location, and high-level collision type. We define three core tasks: (i) temporal localization of the accident, (ii) its spatial localization, and (iii) collision type classification. Each task is evaluated using custom metrics that account for the uncertainty and ambiguity inherent in CCTV footage. In addition to the benchmark, we provide a diverse set of baselines, including heuristic, motion-aware, and vision-language approaches, and show that ACCIDENT is challenging. You can access the ACCIDENT at: this https URL
### Title:
          Deep Reinforcement Learning for Cognitive Time-Division Joint SAR and Secure Communications
 - **Authors:** Mohamed-Amine Lahmeri, Ata Khalili, Yujiao Liu, Anke Schmeink, Robert Schober
 - **Subjects:** Subjects:
Information Theory (cs.IT); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Synthetic aperture radar (SAR) imaging can be exploited to enhance wireless communication performance through high-precision environmental awareness. However, integrating sensing and communication functionalities in such wideband systems remains challenging, motivating the development of a joint SAR and communication (JSARC) framework. We propose a dynamic time-division JSARC (TD-JSARC) framework for secure aerial communications that is relevant for critical scenarios, such as surveillance or post-disaster communication, where conventional localization of mobile adversaries often fails. In particular, we consider a secure downlink communication scenario where an aerial base station (ABS) serves a ground user (UE) in the presence of a ground-moving eavesdropper. To detect and track the eavesdropper, the ABS uses cognitive SAR along-track interferometry (ATI) to estimate its position and velocity. Based on these estimates, the ABS applies adaptive beamforming and artificial-noise jamming to enhance secrecy. To this end, we jointly optimize the time and power allocation to maximize the worst-case secrecy rate, while satisfying both SAR and communication constraints. Using the estimated eavesdropper trajectory, we formulate the problem as a Markov decision process (MDP) and solve it via deep reinforcement learning (DRL). Simulation results show that the proposed learning-based approach outperforms both learning and non-learning baseline schemes employing equal-aperture and random time allocation. The proposed method also generalizes well to previously unseen eavesdropper motion patterns.
### Title:
          A Comparative Study of Modern Object Detectors for Robust Apple Detection in Orchard Imagery
 - **Authors:** Mohammed Asad, Ajai Kumar Gautam, Priyanshu Dhiman, Rishi Raj Prajapati
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate apple detection in orchard images is important for yield prediction, fruit counting, robotic harvesting, and crop monitoring. However, changing illumination, leaf clutter, dense fruit clusters, and partial occlusion make detection difficult. To provide a fair and reproducible comparison, this study establishes a controlled benchmark for single-class apple detection on the public AppleBBCH81 dataset using one deterministic train, validation, and test split and a unified evaluation protocol across six representative detectors: YOLOv10n, YOLO11n, RT-DETR-L, Faster R-CNN (ResNet50-FPN), FCOS (ResNet50-FPN), and SSDLite320 (MobileNetV3-Large). Performance is evaluated primarily using COCO-style mAP@0.5 and mAP@0.5:0.95, and threshold-dependent behavior is further analyzed using precision-recall curves and fixed-threshold precision, recall, and F1-score at IoU = 0.5. On the validation split, YOLO11n achieves the best strict localization performance with mAP@0.5:0.95 = 0.6065 and mAP@0.5 = 0.9620, followed closely by RT-DETR-L and YOLOv10n. At a fixed operating point with confidence >= 0.05, YOLOv10n attains the highest F1-score, whereas RT-DETR-L achieves very high recall but low precision because of many false positives at low confidence. These findings show that detector selection for orchard deployment should be guided not only by localization-aware accuracy but also by threshold robustness and the requirements of the downstream task.
### Title:
          Natural Gradient Gaussian Approximation Filter on Lie Groups for Robot State Estimation
 - **Authors:** Tianyi Zhang, Wenhan Cao, Chang Liu, Yao Lyu, Shengbo Eben Li
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate state estimation for robotic systems evolving on Lie group manifolds, such as legged robots, is a prerequisite for achieving agile control. However, this task is challenged by nonlinear observation models defined on curved manifolds, where existing filters rely on local linearization in the tangent space to handle such nonlinearity, leading to accumulated estimation errors. To address this limitation, we reformulate manifold filtering as a parameter optimization problem over a Gaussian-distributed increment variable, thereby avoiding linearization. Under this formulation, the increment can be mapped to the Lie group through the exponential operator, where it acts multiplicatively on the prior estimate to yield the posterior state. We further propose a natural gradient optimization scheme for solving this problem, whose iteration process leverages the Fisher information matrix of the increment variable to account for the curvature of the tangent space. This results in an iterative algorithm named the Natural Gradient Gaussian Approximation on Lie Groups (NANO-L) filter. Leveraging the perturbation model in Lie derivative, we prove that for the invariant observation model widely adopted in robotic localization tasks, the covariance update in NANO-L admits an exact closed-form solution, eliminating the need for iterative updates thus improving computational efficiency. Hardware experiments on a Unitree GO2 legged robot operating across different terrains demonstrate that NANO-L achieves approximately 40% lower estimation error than commonly used filters at a comparable computational cost.
### Title:
          Global monitoring of methane point sources using deep learning on hyperspectral radiance measurements from EMIT
 - **Authors:** Vishal V. Batchu, Michelangelo Conserva, Alex Wilson, Anna M. Michalak, Varun Gulshan, Philip G. Brodrick, Andrew K. Thorpe, Christopher V. Arsdale
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Atmospheric and Oceanic Physics (physics.ao-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Anthropogenic methane (CH4) point sources drive near-term climate forcing, safety hazards, and system inefficiencies. Space-based imaging spectroscopy is emerging as a tool for identifying emissions globally, but existing approaches largely rely on manual plume identification. Here we present the Methane Analysis and Plume Localization with EMIT (MAPL-EMIT) model, an end-to-end vision transformer framework that leverages the complete radiance spectrum from the Earth Surface Mineral Dust Source Investigation (EMIT) instrument to jointly retrieve methane enhancements across all pixels within a scene. This approach brings together spectral and spatial context to significantly lower detection limits. MAPL-EMIT simultaneously supports enhancement quantification, plume delineation, and source localization, even for multiple overlapping plumes. The model was trained on 3.6 million physics-based synthetic plumes injected into global EMIT radiance data. Synthetic evaluation confirms the model's ability to identify plumes with high recall and precision and to capture weaker plumes relative to existing matched-filter approaches. On real-world benchmarks, MAPL-EMIT captures 79% of known hand-annotated NASA L2B plume complexes across a test set of 1084 EMIT granules, while capturing twice as many plausible plumes than identified by human analysts. Further validation against coincident airborne data, top-emitting landfills, and controlled release experiments confirms the model's ability to identify previously uncaptured sources. By incorporating model-generated metrics such as spectral fit scores and estimated noise levels, the framework can further limit false-positive rates. Overall, MAPL-EMIT enables high-throughput implementation on the full EMIT catalog, shifting methane monitoring from labor-intensive workflows to a rapid, scalable paradigm for global plume mapping at the facility scale.
### Title:
          Semantic Manipulation Localization
 - **Authors:** Zhenshan Tan, Chenhan Lu, Yuxiang Huang, Ziwen He, Xiang Zhang, Yuzhe Sha, Xianyi Chen, Tianrun Chen, Zhangjie Fu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image Manipulation Localization (IML) aims to identify edited regions in an image. However, with the increasing use of modern image editing and generative models, many manipulations no longer exhibit obvious low-level artifacts. Instead, they often involve subtle but meaning-altering edits to an object's attributes, state, or relationships while remaining highly consistent with the surrounding content. This makes conventional IML methods less effective because they mainly rely on artifact detection rather than semantic sensitivity. To address this issue, we introduce Semantic Manipulation Localization (SML), a new task that focuses on localizing subtle semantic edits that significantly change image interpretation. We further construct a dedicated fine-grained benchmark for SML using a semantics-driven manipulation pipeline with pixel-level annotations. Based on this task, we propose TRACE (Targeted Reasoning of Attributed Cognitive Edits), an end-to-end framework that models semantic sensitivity through three progressively coupled components: semantic anchoring, semantic perturbation sensing, and semantic-constrained reasoning. Specifically, TRACE first identifies semantically meaningful regions that support image understanding, then injects perturbation-sensitive frequency cues to capture subtle edits under strong visual consistency, and finally verifies candidate regions through joint reasoning over semantic content and semantic scope. Extensive experiments show that TRACE consistently outperforms existing IML methods on our benchmark and produces more complete, compact, and semantically coherent localization results. These results demonstrate the necessity of moving beyond artifact-based localization and provide a new direction for image forensics in complex semantic editing scenarios.
### Title:
          Mask-Free Privacy Extraction and Rewriting: A Domain-Aware Approach via Prototype Learning
 - **Authors:** Xiaodong Li, Yuhua Wang, Qingchen Yu, Zixuan Qin, Yifan Sun, Qinnan Zhang, Hainan Zhang, Zhiming Zheng
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Client-side privacy rewriting is crucial for deploying LLMs in privacy-sensitive domains. However, existing approaches struggle to balance privacy and utility. Full-text methods often distort context, while span-level approaches rely on impractical manual masks or brittle static dictionaries. Attempts to automate localization via prompt-based LLMs prove unreliable, as they suffer from unstable instruction following that leads to privacy leakage and excessive context scrubbing. To address these limitations, we propose DAMPER (Domain-Aware Mask-free Privacy Extraction and Rewriting). DAMPER operationalizes latent privacy semantics into compact Domain Privacy Prototypes via contrastive learning, enabling precise, autonomous span localization. Furthermore, we introduce a Prototype-Guided Preference Alignment, which leverages learned prototypes as semantic anchors to construct preference pairs, optimizing a domain-compliant rewriting policy without human annotations. At inference time, DAMPER integrates a sampling-based Exponential Mechanism to provide rigorous span-level Differential Privacy (DP) guarantees. Extensive experiments demonstrate that DAMPER significantly outperforms existing baselines, achieving a superior privacy-utility trade-off.
### Title:
          CodeComp: Structural KV Cache Compression for Agentic Coding
 - **Authors:** Qiujiang Chen, Jing Xiong, Chenyang Zhao, Sidi Yang, Ngai Wong
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agentic code tasks such as fault localization and patch generation require processing long codebases under tight memory constraints, where the Key-Value (KV) cache becomes the primary inference bottleneck. Existing compression methods rely exclusively on attention signals to estimate token importance, systematically discarding structurally critical tokens such as call sites, branch conditions, and assignments that are essential for code understanding. We present CodeComp, a training-free KV cache compression framework that incorporates static program analysis into LLM inference via Code Property Graph priors extracted by Joern. Across bug localization and code generation benchmarks, CodeComp consistently outperforms attention-only compression baselines under equal memory budgets, recovering the majority of full-context accuracy under aggressive KV cache compression, while matching the patch generation quality of uncompressed full-context inference and integrating seamlessly into SGLang-based agentic coding pipelines without model modification.
### Title:
          Rethinking Video Human-Object Interaction: Set Prediction over Time for Unified Detection and Anticipation
 - **Authors:** Yuanhao Luo, Di Wen, Kunyu Peng, Ruiping Liu, Junwei Zheng, Yufan Chen, Jiale Wei, Rainer Stiefelhage
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video-based human-object interaction (HOI) understanding requires both detecting ongoing interactions and anticipating their future evolution. However, existing methods usually treat anticipation as a downstream forecasting task built on externally constructed human-object pairs, limiting joint reasoning between detection and prediction. In addition, sparse keyframe annotations in current benchmarks can temporally misalign nominal future labels from actual future dynamics, reducing the reliability of anticipation evaluation. To address these issues, we introduce DETAnt-HOI, a temporally corrected benchmark derived from VidHOI and Action Genome for more faithful multi-horizon evaluation, and HOI-DA, a pair-centric framework that jointly performs subject-object localization, present HOI detection, and future anticipation by modeling future interactions as residual transitions from current pair states. Experiments show consistent improvements in both detection and anticipation, with larger gains at longer horizons. Our results highlight that anticipation is most effective when learned jointly with detection as a structural constraint on pair-level video representation learning. Benchmark and code will be publicly available.
### Title:
          Enhancing Fine-Grained Spatial Grounding in 3D CT Report Generation via Discriminative Guidance
 - **Authors:** Chenyu Wang, Weicheng Dai, Han Liu, Wenchao Li, Kayhan Batmanghelich
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision--language models (VLMs) for radiology report generation (RRG) can produce long-form chest CT reports from volumetric scans and show strong potential to improve radiology workflow efficiency and consistency. However, existing methods face two key limitations: (i) training supervision is often coarse, aligning a whole CT volume with a full free-text report without explicit alignment for fine-grained attributes or pathology locations; and (ii) evaluation is typically holistic (lexical overlap, entity matching, or LLM-as-a-judge scores) and not diagnostic for spatial grounding. We propose \emph{Discriminative Cue-Prompting with Prompt Dropout (DCP-PD)}, a plug-and-play framework that distills fine-grained cues from free-text reports and uses them to guide report generation while mitigating shortcut reliance via prompt dropout. DCP-PD achieves state-of-the-art performance on CT-RATE, improving macro F1 from $=0.501$ to $0.603$ (20% relative), and substantially boosts out-of-distribution performance on Rad-ChestCT from F1 $=0.266$ to $0.503$ (89% relative). Finally, we introduce a hierarchical, location-aware question-set protocol (presence $\rightarrow$ laterality $\rightarrow$ lobe) to directly assess pathology-location grounding, showing that fine-grained spatial localization remains challenging even for models that score highly on current benchmarks.
### Title:
          Edge-Tilting Field Dynamics: Rapid Mixing at the Uniqueness Threshold and Optimal Mixing for Swendsen-Wang Dynamics
 - **Authors:** Xiaoyu Chen, Zhe Ju, Tianshun Miao, Yitong Yin, Xinyuan Zhang
 - **Subjects:** Subjects:
Data Structures and Algorithms (cs.DS); Probability (math.PR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We prove two results on the mixing times of Markov chains for two-spin systems. First, we show that the Glauber dynamics mixes in polynomial time for the Gibbs distributions of antiferromagnetic two-spin systems at the critical threshold of the uniqueness phase transition of the Gibbs measure on infinite regular trees. This completes the computational phase transition picture for antiferromagnetic two-spin systems, which includes near-linear-time optimal mixing in the uniqueness regime [Chen--Liu--Vigoda, STOC '21; Chen--Feng--Yin--Zhang, FOCS '22], NP-hardness of approximate sampling in the non-uniqueness regime [Sly--Sun, FOCS '12], and polynomial-time mixing at criticality (this work). Second, we prove an optimal $O(\log n)$ mixing time bound as well as an optimal $\Omega(1)$ spectral gap for the Swendsen--Wang dynamics for the ferromagnetic Ising model with an external field on bounded-degree graphs. To the best of our knowledge, these are the first sharp bounds on the mixing rate of this classical global Markov chain beyond mean-field or strong spatial mixing (SSM) regimes, and resolve a conjecture of [Feng--Guo--Wang, IANDC '23]. A key ingredient in both proofs is a new family of localization schemes that extends the field dynamics of [Chen--Feng--Yin--Zhang, FOCS '21] by tilting general edge (or hyperedge) weights rather than vertex fields. This framework, which subsumes the classical Swendsen--Wang dynamics as a special case, extends the localization framework of [Chen--Eldan, FOCS '22] beyond stochastic and field localizations, and enables controlled tilting of interaction strengths while preserving external fields.
### Title:
          Defending against Patch-Based and Texture-Based Adversarial Attacks with Spectral Decomposition
 - **Authors:** Wei Zhang, Xinyu Chang, Xiao Li, Yiming Zhu, Xiaolin Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adversarial examples present significant challenges to the security of Deep Neural Network (DNN) applications. Specifically, there are patch-based and texture-based attacks that are usually used to craft physical-world adversarial examples, posing real threats to security-critical applications such as person detection in surveillance and autonomous systems, because those attacks are physically realizable. Existing defense mechanisms face challenges in the adaptive attack setting, i.e., the attacks are specifically designed against them. In this paper, we propose Adversarial Spectrum Defense (ASD), a defense mechanism that leverages spectral decomposition via Discrete Wavelet Transform (DWT) to analyze adversarial patterns across multiple frequency scales. The multi-resolution and localization capability of DWT enables ASD to capture both high-frequency (fine-grained) and low-frequency (spatially pervasive) perturbations. By integrating this spectral analysis with the off-the-shelf Adversarial Training (AT) model, ASD provides a comprehensive defense strategy against both patch-based and texture-based adversarial attacks. Extensive experiments demonstrate that ASD+AT achieved state-of-the-art (SOTA) performance against various attacks, outperforming the APs of previous defense methods by 21.73%, in the face of strong adaptive adversaries specifically designed against ASD. Code available at this https URL .
### Title:
          Turning Generators into Retrievers: Unlocking MLLMs for Natural Language-Guided Geo-Localization
 - **Authors:** Yuqi Chen, Xiaohan Zhang, Ahmad Arrabi, Waqas Sultani, Chen Chen, Safwan Wshah
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Natural-language Guided Cross-view Geo-localization (NGCG) aims to retrieve geo-tagged satellite imagery using textual descriptions of ground scenes. While recent NGCG methods commonly rely on CLIP-style dual-encoder architectures, they often suffer from weak cross-modal generalization and require complex architectural designs. In contrast, Multimodal Large Language Models (MLLMs) offer powerful semantic reasoning capabilities but are not directly optimized for retrieval tasks. In this work, we present a simple yet effective framework to adapt MLLMs for NGCG via parameter-efficient finetuning. Our approach optimizes latent representations within the MLLM while preserving its pretrained multimodal knowledge, enabling strong cross-modal alignment without redesigning model architectures. Through systematic analysis of diverse variables, from model backbone to feature aggregation, we provide practical and generalizable insights for leveraging MLLMs in NGCG. Our method achieves SOTA on GeoText-1652 with a 12.2% improvement in Text-to-Image Recall@1 and secures top performance in 5 out of 12 subtasks on CVG-Text, all while surpassing baselines with far fewer trainable parameters. These results position MLLMs as a robust foundation for semantic cross-view retrieval and pave the way for MLLM-based NGCG to be adopted as a scalable, powerful alternative to traditional dual-encoder designs. Project page and code are available at this https URL.
### Title:
          Entropic independence via sparse localization
 - **Authors:** Vishesh Jain, Huy Tuan Pham, Thuy-Duong Vuong
 - **Subjects:** Subjects:
Information Theory (cs.IT); Data Structures and Algorithms (cs.DS); Probability (math.PR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Entropic independence is a structural property of measures that underlies modern proofs of functional inequalities, notably (modified) log-Sobolev inequalities, via ``annealing'' or local-to-global schemes. Existing sufficient criteria for entropic independence typically require spectral independence and/or uniform bounds on marginals under \emph{all} pinnings, which can fail in natural canonical-ensemble models even when strong mixing properties are expected. We introduce \emph{sparse localization}: a restricted localization framework, in the spirit of Chen--Eldan, in which one assumes $\ell_2$-independence only for a sparse family of pinnings (those fixing at most $cn$ coordinates for any $c > 0$), yet still deduces quadratic entropic stability and entropic independence with an explicit multiplicative loss of order $c^{-1}$. As an application, we give a rigorous proof of approximate conservation of entropy for the uniform distribution on independent sets of a given size in bounded degree graphs.
### Title:
          MMR-AD: A Large-Scale Multimodal Dataset for Benchmarking General Anomaly Detection with Multimodal Large Language Models
 - **Authors:** Xincheng Yao, Zefeng Qian, Chao Shi, Jiayang Song, Chongyang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In the progress of industrial anomaly detection, general anomaly detection (GAD) is an emerging trend and also the ultimate goal. Unlike the conventional single- and multi-class AD, general AD aims to train a general AD model that can directly detect anomalies in diverse novel classes without any retraining or fine-tuning on the target data. Recently, Multimodal Large Language Models (MLLMs) have shown great promise in achieving general anomaly detection due to their revolutionary visual understanding and language reasoning capabilities. However, MLLM's general AD ability remains underexplored due to: (1) MLLMs are pretrained on amounts of data sourced from the Web, these data still have significant gaps with the data in AD scenarios. Moreover, the image-text pairs during pretraining are also not specifically for AD tasks. (2) The current mainstream AD datasets are image-based and not yet suitable for post-training MLLMs. To facilitate MLLM-based general AD research, we present MMR-AD, which is a comprehensive benchmark for both training and evaluating MLLM-based AD models. With MMR-AD, we reveal that the AD performance of current SOTA generalist MLLMs still falls far behind the industrial requirements. Based on MMR-AD, we also propose a baseline model, Anomaly-R1, which is a reasoning-based AD model that learns from the CoT data in MMR-AD and is further enhanced by reinforcement learning. Extensive experiments show that our Anomaly-R1 achieves remarkable improvements over generalist MLLMs in both anomaly detection and localization.
### Title:
          Diffusion-CAM: Faithful Visual Explanations for dMLLMs
 - **Authors:** Haomin Zuo, Yidi Li, Luoxiao Yang, Xiaofeng Zhang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While diffusion Multimodal Large Language Models (dMLLMs) have recently achieved remarkable strides in multimodal generation, the development of interpretability mechanisms has lagged behind their architectural evolution. Unlike traditional autoregressive models that produce sequential activations, diffusion-based architectures generate tokens via parallel denoising, resulting in smooth, distributed activation patterns across the entire sequence. Consequently, existing Class Activation Mapping (CAM) methods, which are tailored for local, sequential dependencies, are ill-suited for interpreting these non-autoregressive behaviors. To bridge this gap, we propose Diffusion-CAM, the first interpretability method specifically tailored for dMLLMs. We derive raw activation maps by differentiably probing intermediate representations in the transformer backbone, accordingly capturing both latent features and their class-specific gradients. To address the inherent stochasticity of these raw signals, we incorporate four key modules to resolve spatial ambiguity and mitigate intra-image confounders and redundant token correlations. Extensive experiments demonstrate that Diffusion-CAM significantly outperforms SoTA methods in both localization accuracy and visual fidelity, establishing a new standard for understanding the parallel generation process of diffusion multimodal systems.
### Title:
          OmniScript: Towards Audio-Visual Script Generation for Long-Form Cinematic Video
 - **Authors:** Junfu Pu, Yuxin Chen, Teng Wang, Ying Shan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current multimodal large language models (MLLMs) have demonstrated remarkable capabilities in short-form video understanding, yet translating long-form cinematic videos into detailed, temporally grounded scripts remains a significant challenge. This paper introduces the novel video-to-script (V2S) task, aiming to generate hierarchical, scene-by-scene scripts encompassing character actions, dialogues, expressions, and audio cues. To facilitate this, we construct a first-of-its-kind human-annotated benchmark and propose a temporally-aware hierarchical evaluation framework. Furthermore, we present OmniScript, an 8B-parameter omni-modal (audio-visual) language model tailored for long-form narrative comprehension. OmniScript is trained via a progressive pipeline that leverages chain-of-thought supervised fine-tuning for plot and character reasoning, followed by reinforcement learning using temporally segmented rewards. Extensive experiments demonstrate that despite its parameter efficiency, OmniScript significantly outperforms larger open-source models and achieves performance comparable to state-of-the-art proprietary models, including Gemini 3-Pro, in both temporal localization and multi-field semantic accuracy.
### Title:
          A regularized truncated finite element method for degenerate parabolic stochastic PDE on non-compact graph
 - **Authors:** Jianbo Cui, Mihály Kovács, Derui Sheng
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study the numerical approximation of a class of degenerate parabolic stochastic partial differential equations on non-compact metric graphs, which naturally arise in the asymptotic analysis of Hamiltonian flows under small noise perturbations. The numerical discretization of these equations faces several challenges, including the non-compactness of the graph, the degeneracy of the differential operator near vertices, and the non-symmetry of the associated bilinear form. To address these issues, we propose a multi-step numerical strategy combining graph truncation, localized coefficient regularization, and finite element spatial discretization. By incorporating localization techniques, tightness arguments, and resolvent estimates, we establish the strong convergence of the proposed scheme in a weighted $L^2$-space. Our results provide a systematic methodology that is potentially extensible to more general non-compact graphs and degenerate operators.
### Title:
          Boxes2Pixels: Learning Defect Segmentation from Noisy SAM Masks
 - **Authors:** Camile Lendering, Erkut Akdag, Egor Bondarev
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate defect segmentation is critical for industrial inspection, yet dense pixel-level annotations are rarely available. A common workaround is to convert inexpensive bounding boxes into pseudo-masks using foundation segmentation models such as the Segment Anything Model (SAM). However, these pseudo-labels are systematically noisy on industrial surfaces, often hallucinating background structure while missing sparse defects. To address this limitation, a noise-robust box-to-pixel distillation framework, Boxes2Pixels, is proposed that treats SAM as a noisy teacher rather than a source of ground-truth supervision. Bounding boxes are converted into pseudo-masks offline by SAM, and a compact student is trained with (i) a hierarchical decoder over frozen DINOv2 features for semantic stability, (ii) an auxiliary binary localization head to decouple sparse foreground discovery from class prediction, and (iii) a one-sided online self-correction mechanism that relaxes background supervision when the student is confident, targeting teacher false negatives. On a manually annotated wind turbine inspection benchmark, the proposed Boxes2Pixels improves anomaly mIoU by +6.97 and binary IoU by +9.71 over the strongest baseline trained under identical weak supervision. Moreover, online self-correction increases the binary recall by +18.56, while the model employs 80\% fewer trainable parameters. Code is available at this https URL.
### Title:
          Evaluating LLM Agents on Automated Software Analysis Tasks
 - **Authors:** Michael Pradel, Cristian Cadar, Islem Bouzenia
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Numerous software analysis tools exist today, yet applying them to diverse open-source projects remains challenging due to environment setup, dependency resolution, and tool configuration. LLM-based agents offer a potential solution, yet no prior work has systematically studied their effectiveness on the specific task of automated software analysis, which, unlike issue solving or general environment setup, requires installing and configuring a separate analysis tool alongside the target project, generating tool-specific prerequisites, and validating that the tool produces meaningful analysis outputs. We introduce AnalysisBench, a benchmark of 35 tool-project pairs spanning seven analysis tools and ten diverse C/C++ and Java projects, each with a manually constructed reference setup. Using AnalysisBench, we evaluate four agent architectures across four LLM backends. Our custom agent, AnalysisAgent, achieves manually verified success rates of 94% (Gemini-3-Flash, 33/35 tasks), compared to 77% for the best baseline (ExecutionAgent). Beyond quantitative results, we identify key limitations in existing agents, including stage mixing, poor error localization, and premature termination, and show that agentic architecture matters more than LLM capability alone. We further find that whole-program analyses and symbolic execution are the most difficult tasks, that Java toolchains pose greater challenges than C/C++, and that LLM-self-validated success consistently overstates manually verified success.
### Title:
          LoGo-MR: Screening Breast MRI for Cancer Risk Prediction by Efficient Omni-Slice Modeling
 - **Authors:** Xin Wang, Yuan Gao, George Yiasemis, Antonio Portaluri, Zahra Aghdam, Muzhen He, Luyi Han, Yaofei Duan, Chunyao Lu, Xinglong Liang, Tianyu Zhang, Vivien van Veldhuizen, Yue Sun, Tao Tan, Ritse Mann, Jonas Teuwen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient and explainable breast cancer (BC) risk prediction is critical for large-scale population-based screening. Breast MRI provides functional information for personalized risk assessment. Yet effective modeling remains challenging as fully 3D CNNs capture volumetric context at high computational cost, whereas lightweight 2D CNNs fail to model inter-slice continuity. Importantly, breast MRI modeling for shor- and long-term BC risk stratification remains underexplored. In this study, we propose LoGo-MR, a 2.5D local-global structural modeling framework for five-year BC risk prediction. Aligned with clinical interpretation, our framework first employs neighbor-slice encoding to capture subtle local cues linked to short-term risk. It then integrates transformer-enhanced multiple-instance learning (MIL) to model distributed global patterns related to long-term risk and provide interpretable slice importance. We further apply this framework across axial, sagittal, and coronal planes as LoGo3-MR to capture complementary volumetric information. This multi-plane formulation enables voxel-level risk saliency mapping, which may assist radiologists in localizing risk-relevant regions during breast MRI interpretation. Evaluated on a large breast MRI screening cohort (~7.5K), our method outperforms 2D/3D baselines and existing SOTA MIL methods, achieving AUCs of 0.77-0.69 for 1- to 5-year prediction and improving C-index by ~6% over 3D CNNs. LoGo3-MR further improves overall performance with interpretable localization across three planes, and validation across seven backbones shows consistent gains. These results highlight the clinical potential of efficient MRI-based BC risk stratification for large-scale screening. Code will be released publicly.
### Title:
          LEADER: Learning Reliable Local-to-Global Correspondences for LiDAR Relocalization
 - **Authors:** Jianshi Wu, Minghang Zhu, Dunqiang Liu, Wen Li, Sheng Ao, Siqi Shen, Chenglu Wen, Cheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR relocalization has attracted increasing attention as it can deliver accurate 6-DoF pose estimation in complex 3D environments. Recent learning-based regression methods offer efficient solutions by directly predicting global poses without the need for explicit map storage. However, these methods often struggle in challenging scenes due to their equal treatment of all predicted points, which is vulnerable to noise and outliers. In this paper, we propose LEADER, a robust LiDAR-based relocalization framework enhanced by a simple, yet effective geometric encoder. Specifically, a Robust Projection-based Geometric Encoder architecture which captures multi-scale geometric features is first presented to enhance descriptiveness in geometric representation. A Truncated Relative Reliability loss is then formulated to model point-wise ambiguity and mitigate the influence of unreliable predictions. Extensive experiments on the Oxford RobotCar and NCLT datasets demonstrate that LEADER outperforms state-of-the-art methods, achieving 24.1% and 73.9% relative reductions in position error over existing techniques, respectively. The source code is released on this https URL.
### Title:
          Seeing Through Touch: Tactile-Driven Visual Localization of Material Regions
 - **Authors:** Seongyu Kim, Seungwoo Lee, Hyeonggon Ryu, Joon Son Chung, Arda Senocak
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We address the problem of tactile localization, where the goal is to identify image regions that share the same material properties as a tactile input. Existing visuo-tactile methods rely on global alignment and thus fail to capture the fine-grained local correspondences required for this task. The challenge is amplified by existing datasets, which predominantly contain close-up, low-diversity images. We propose a model that learns local visuo-tactile alignment via dense cross-modal feature interactions, producing tactile saliency maps for touch-conditioned material segmentation. To overcome dataset constraints, we introduce: (i) in-the-wild multi-material scene images that expand visual diversity, and (ii) a material-diversity pairing strategy that aligns each tactile sample with visually varied yet tactilely consistent images, improving contextual localization and robustness to weak signals. We also construct two new tactile-grounded material segmentation datasets for quantitative evaluation. Experiments on both new and existing benchmarks show that our approach substantially outperforms prior visuo-tactile methods in tactile localization.
### Title:
          CodeTracer: Towards Traceable Agent States
 - **Authors:** Han Li, Yifan Yao, Letian Zhu, Rili Feng, Hongyi Ye, Jiaming Wang, Yancheng He, Pengyu Zou, Lehan Zhang, Xinping Lei, Haoyang Huang, Ken Deng, Ming Sun, Zhaoxiang Zhang, He Ye, Jiaheng Liu
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Code agents are advancing rapidly, but debugging them is becoming increasingly difficult. As frameworks orchestrate parallel tool calls and multi-stage workflows over complex tasks, making the agent's state transitions and error propagation hard to observe. In these runs, an early misstep can trap the agent in unproductive loops or even cascade into fundamental errors, forming hidden error chains that make it hard to tell when the agent goes off track and why. Existing agent tracing analyses either focus on simple interaction or rely on small-scale manual inspection, which limits their scalability and usefulness for real coding workflows. We present CodeTracer, a tracing architecture that parses heterogeneous run artifacts through evolving extractors, reconstructs the full state transition history as a hierarchical trace tree with persistent memory, and performs failure onset localization to pinpoint the failure origin and its downstream chain. To enable systematic evaluation, we construct CodeTraceBench from a large collection of executed trajectories generated by four widely used code agent frameworks on diverse code tasks (e.g., bug fixing, refactoring, and terminal interaction), with supervision at both the stage and step levels for failure localization. Experiments show that CodeTracer substantially outperforms direct prompting and lightweight baselines, and that replaying its diagnostic signals consistently recovers originally failed runs under matched budgets. Our code and data are publicly available.
### Title:
          Angle-based Localization and Rigidity Maintenance Control for Multi-Robot Networks
 - **Authors:** J. Francisco Presenza, Leonardo J. Colombo, Juan I. Giribet, Ignacio Mas
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we study angle-based localization and rigidity maintenance control for multi-robot networks under sensing constraints. We establish the first equivalence between angle rigidity and bearing rigidity considering \textit{directed} sensing graphs and \textit{body-frame} bearing measurements in both $2$ and $3$-\textit{dimensional space}. In particular, we demonstrate that a framework in $\mathrm{SE}(d)$ is infinitesimally bearing rigid if and only if it is infinitesimally angle rigid and each robot obtains at least $d-1$ bearing measurements ($d \in \{2, 3\}$). Building on these findings, this paper proposes a distributed angle-based localization scheme and establishes local exponential stability under switching sensing graphs, requiring only infinitesimal angle rigidity across the visited topologies. Then, since angle rigidity strongly depends on the robots' spatial configuration, we investigate rigidity maintenance control. The \textit{angle rigidity eigenvalue} is presented as a metric for the degree of rigidity. A decentralized gradient-based controller capable of executing mission-specific commands while maintaining a sufficient level of angle rigidity is proposed. Simulations were conducted to evaluate the scheme's effectiveness and practicality.
### Title:
          Enhancing Program Repair with Specification Guidance and Intermediate Behavioral Signals
 - **Authors:** Minh Le-Anh, Cuong Chi Le, Tien N. Nguyen
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated Program Repair (APR) has recently benefited from large language models (LLMs). However, most LLM-based APR approaches still rely primarily on coarse end-to-end signals from test-suite outcomes to guide repair, providing limited insight into where a program's internal logic deviates from its intended behavior. In contrast, human debugging often relies on intermediate reasoning about program states through localized correctness conditions or assertions. Inspired by this observation, we propose SpecTune, a specification-guided debugging framework that incorporates intermediate behavioral reasoning into APR. SpecTune decomposes the repair task into suspicious regions connected by execution checkpoints and derives localized postconditions representing expected program behaviors at those points. By executing the buggy program and evaluating these postconditions, SpecTune produces micro-level debugging signals that indicate mismatches between observed and intended behaviors, enabling more precise fault localization and targeted patch generation. To address the potential unreliability of LLM-generated postconditions, we introduce two complementary signals: a specification validation signal alpha, which estimates the consistency of generated postconditions using partially passing test cases, and a discriminative signal beta, which detects violations of validated postconditions during execution. With these signals, SpecTune safely leverages automatically generated specifications for APR. Experimental results show that SpecTune improves fault localization and APR effectiveness than the baselines.
### Title:
          Psychological Concept Neurons: Can Neural Control Bias Probing and Shift Generation in LLMs?
 - **Authors:** Yuto Harada, Hiro Taiyo Hamada
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Using psychological constructs such as the Big Five, large language models (LLMs) can imitate specific personality profiles and predict a user's personality. While LLMs can exhibit behaviors consistent with these constructs, it remains unclear where and how they are represented inside the model and how they relate to behavioral outputs. To address this gap, we focus on questionnaire-operationalized Big Five concepts, analyze the formation and localization of their internal representations, and use interventions to examine how these representations relate to behavioral outputs. In our experiment, we first use probing to examine where Big Five information emerges across model depth. We then identify neurons that respond selectively to each Big Five concept and test whether enhancing or suppressing their activations can bias latent representations and label generation in intended directions. We find that Big Five information becomes rapidly decodable in early layers and remains detectable through the final layers, while concept-selective neurons are most prevalent in mid layers and exhibit limited overlap across domains. Interventions on these neurons consistently shift probe readouts toward targeted concepts, with targeted success rates exceeding 0.8 for some concepts, indicating that the model's internal separation of Big Five personality traits can be causally steered. At the label-generation level, the same interventions often bias generated label distributions in the intended directions, but the effects are weaker, more concept-dependent, and often accompanied by cross-trait spillover, indicating that comparable control over generated labels is difficult even with interventions on a large fraction of concept-selective neurons. Overall, our findings reveal a gap between representational control and behavioral control in LLMs.
## Keyword: transformer
### Title:
          The Diffusion-Attention Connection
 - **Authors:** Julio Candanedo
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers, diffusion-maps, and magnetic Laplacians are usually treated as separate tools; we show they are all different regimes of a single Markov geometry built from pre-softmax query-scores. We define a QK "bidivergence" whose exponentiated and normalized forms yield attention, diffusion-maps, and magnetic diffusion. And use product of experts and Schrödinger-bridges to connect and organize them into equilibrium, nonequilibrium steady-state, and driven dynamics.
### Title:
          Human-like Working Memory Interference in Large Language Models
 - **Authors:** Hua-Dong Xiong (1), Li Ji-An (2), Jiaqi Huang (3 and 4), Robert C. Wilson (1 and 5), Kwonjoon Lee (4), Xue-Xin Wei (6) ((1) School of Psychological and Brain Sciences, Georgia Tech, (2) Department of Psychology, New York University, (3) Department of Cognitive Science, Indiana University Bloomington, (4) Honda Research Institute, (5) Center of Excellence for Computational Cognition, Georgia Tech, (6) Departments of Neuroscience and Psychology, The University of Texas at Austin)
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Intelligent systems must maintain and manipulate task-relevant information online to adapt to dynamic environments and changing goals. This capacity, known as working memory, is fundamental to human reasoning and intelligence. Despite having on the order of 100 billion neurons, both biological and artificial systems exhibit limitations in working memory. This raises a key question: why do large language models (LLMs) show such limitations, given that transformers have full access to prior context through attention? We find that although a two-layer transformer can be trained to solve working memory tasks perfectly, a diverse set of pretrained LLMs continues to show working memory limitations. Notably, LLMs reproduce interference signatures observed in humans: performance degrades with increasing memory load and is biased by recency and stimulus statistics. Across models, stronger working memory capacity correlates with broader competence on standard benchmarks, mirroring its link to general intelligence in humans. Yet despite substantial variability in working memory performance, LLMs surprisingly converge on a common computational mechanism. Rather than directly copying the relevant memory item from context, models encode multiple memory items in entangled representations, such that successful recall depends on interference control -- actively suppressing task-irrelevant content to isolate the target for readout. Moreover, a targeted intervention that suppresses stimulus content information improves performance, providing causal support for representational interference. Together, these findings identify representational interference as a core constraint on working memory in pretrained LLMs, suggesting that working-memory limits in biological and artificial systems may reflect a shared computational challenge: selecting task-relevant information under interference.
### Title:
          Active Inference with a Self-Prior in the Mirror-Mark Task
 - **Authors:** Dongmin Kim, Hoshinori Kanazawa, Yasuo Kuniyoshi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The mirror self-recognition test evaluates whether a subject touches a mark on its own body that is visible only in a mirror, and is widely used as an indicator of self-awareness. In this study, we present a computational model in which this behavior emerges spontaneously through a single mechanism, the self-prior, without any external reward. The self-prior, implemented with a Transformer, learns the density of familiar multisensory experiences; when a novel mark appears, the discrepancy from this learned distribution drives mark-directed behavior through active inference. A simulated infant, relying solely on vision and proprioception without tactile input, discovered a sticker placed on its own face in the mirror and removed it in approximately 70% of cases without any explicit instruction. Expected free energy decreased significantly after sticker removal, confirming that the self-prior operates as an internal criterion for distinguishing self from non-self. Cross-modal sampling further demonstrated that the self-prior captures visual--proprioceptive associations, functioning as a probabilistic body schema. These results provide a concise computational account of the key behavior observed in the mirror test and suggest that the free energy principle can serve as a unifying hypothesis for investigating the developmental origins of self-awareness. Code is available at: this https URL
### Title:
          PASTA: Vision Transformer Patch Aggregation for Weakly Supervised Target and Anomaly Segmentation
 - **Authors:** Melanie Neubauer, Elmar Rueckert, Christian Rauch
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Detecting unseen anomalies in unstructured environments presents a critical challenge for industrial and agricultural applications such as material recycling and weeding. Existing perception systems frequently fail to satisfy the strict operational requirements of these domains, specifically real-time processing, pixel-level segmentation precision, and robust accuracy, due to their reliance on exhaustively annotated datasets. To address these limitations, we propose a weakly supervised pipeline for object segmentation and classification using weak image-level supervision called 'Patch Aggregation for Segmentation of Targets and Anomalies' (PASTA). By comparing an observed scene with a nominal reference, PASTA identifies Target and Anomaly objects through distribution analysis in self-supervised Vision Transformer (ViT) feature spaces. Our pipeline utilizes semantic text-prompts via the Segment Anything Model 3 to guide zero-shot object segmentation. Evaluations on a custom steel scrap recycling dataset and a plant dataset demonstrate a 75.8% training time reduction of our approach to domain-specific baselines. While being domain-agnostic, our method achieves superior Target (up to 88.3% IoU) and Anomaly (up to 63.5% IoU) segmentation performance in the industrial and agricultural domain.
### Title:
          Orthogonal Quadratic Complements for Vision Transformer Feed-Forward Networks
 - **Authors:** Wang Zixian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent bilinear feed-forward replacements for vision transformers can substantially improve accuracy, but they often conflate two effects: stronger second-order interactions and increased redundancy relative to the main branch. We study a complementary design principle in which auxiliary quadratic features contribute only information not already captured by the dominant hidden representation. To this end, we propose Orthogonal Quadratic Complements (OQC), which construct a low-rank quadratic auxiliary branch and explicitly project it onto the orthogonal complement of the main branch before injection. We further study an efficient low-rank realization (OQC-LR) and gated extensions (OQC-static and OQC-dynamic). Under a parameter-matched Deep-ViT and CIFAR-100 protocol with a fixed penultimate residual readout, full OQC improves an AFBO baseline from 64.25 +/- 0.22 to 65.59 +/- 0.22, while OQC-LR reaches 65.52 +/- 0.25 with a substantially better speed-accuracy tradeoff. On TinyImageNet, the gated extension OQC-dynamic achieves 51.88 +/- 0.32, improving the baseline (50.45 +/- 0.21) by 1.43 points and outperforming all ungated variants. Mechanism analyses show near-zero post-projection auxiliary-main overlap together with improved representation geometry and class separation. The full family, including both ungated and gated variants, generalizes consistently across both datasets.
### Title:
          Training Deep Visual Networks Beyond Loss and Accuracy Through a Dynamical Systems Approach
 - **Authors:** Hai La Quang, Hassan Ugail, Newton Howard, Cong Tran Tien, Nam Vu Hoai, Hung Nguyen Viet
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep visual recognition models are usually trained and evaluated using metrics such as loss and accuracy. While these measures show whether a model is improving, they reveal very little about how its internal representations change during training. This paper introduces a complementary way to study that process by examining training through the lens of dynamical systems. Drawing on ideas from signal analysis originally used to study biological neural activity, we define three measures from layer activations collected across training epochs: an integration score that reflects long-range coordination across layers, a metastability score that captures how flexibly the network shifts between more and less synchronised states, and a combined dynamical stability index. We apply this framework to nine combinations of model architecture and dataset, including several ResNet variants, DenseNet-121, MobileNetV2, VGG-16, and a pretrained Vision Transformer on CIFAR-10 and CIFAR-100. The results suggest three main patterns. First, the integration measure consistently distinguishes the easier CIFAR-10 setting from the more difficult CIFAR-100 setting. Second, changes in the volatility of the stability index may provide an early sign of convergence before accuracy fully plateaus. Third, the relationship between integration and metastability appears to reflect different styles of training behaviour. Overall, this study offers an exploratory but promising new way to understand deep visual training beyond loss and accuracy.
### Title:
          Multi-Head Attention based interaction-aware architecture for Bangla Handwritten Character Recognition: Introducing a Primary Dataset
 - **Authors:** Mirza Raquib, Asif Pervez Polok, Kedar Nath Biswas, Farida Siddiqi Prity, Saydul Akbar Murad, Nick Rahimi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Character recognition is the fundamental part of an optical character recognition (OCR) system. Word recognition, sentence transcription, document digitization, and language processing are some of the higher-order activities that can be done accurately through character recognition. Nonetheless, recognizing handwritten Bangla characters is not an easy task because they are written in different styles with inconsistent stroke patterns and a high degree of visual character resemblance. The datasets available are usually limited in intra-class and inequitable in class distribution. We have constructed a new balanced dataset of Bangla written characters to overcome those problems. This consists of 78 classes and each class has approximately 650 samples. It contains the basic characters, composite (Juktobarno) characters and numerals. The samples were a diverse group comprising a large age range and socioeconomic groups. Elementary and high school students, university students, and professionals are the contributing factors. The sample also has right and left-handed writers. We have further proposed an interaction-aware hybrid deep learning architecture that integrates EfficientNetB3, Vision Transformer, and Conformer modules in parallel. A multi-head cross-attention fusion mechanism enables effective feature interaction across these components. The proposed model achieves 98.84% accuracy on the constructed dataset and 96.49% on the external CHBCR benchmark, demonstrating strong generalization capability. Grad-CAM visualizations further provide interpretability by highlighting discriminative regions. The dataset and source code of this research is publicly available at: this https URL.
### Title:
          Efficient Matrix Implementation for Rotary Position Embedding
 - **Authors:** Chen Minqi, Zhongqi Yue, Shihao Zhang, Yun Xu, Peng Wu, kaixiang Xu, Zeyi Huang, Hanwang Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rotary Position Embedding (RoPE) has become a core component of modern Transformer architectures across language, vision, and 3D domains. However, existing implementations rely on vector-level split and merge operations that introduce non-negligible computational overhead, often overlooked in attention optimization. The problem is further amplified in multi-dimensional settings (e.g., 2D and 3D RoPE), where additional vector operations and uneven feature partitions degrade hardware utilization. To overcome these limitations, we propose RoME (Rotary Matrix position Embedding), a mathematically equivalent yet computationally efficient reformulation of RoPE that replaces vector operations with unified matrix transformations. RoME eliminates dimension-specific operations, simplifies implementation, and enables fused parallel execution across Cube and Vector units on modern NPUs. Experiments show that RoME delivers substantial acceleration at both the operator and full-model levels. The implementation is available at this https URL.
### Title:
          Sustainable Transformer Neural Network Acceleration with Stochastic Photonic Computing
 - **Authors:** S. Afifi, O. Alo, I. Thakkar, S. Pasricha
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers achieve state-of-the-art performance in natural language processing, vision, and scientific computing, but demand high computation and memory. To address these challenges, we present ASTRA, the first silicon-photonic accelerator leveraging stochastic computing for transformers. ASTRA employs novel optical stochastic multipliers and unary/analog homodyne accumulation in a crosstalk-minimal organization to efficiently process dynamic tensor computations. Evaluations show at least 7.6x speedup and 1.3x lower energy overheads compared to state-of-the-art accelerators, highlighting ASTRA's potential for efficient, scalable, and sustainable transformer inference.
### Title:
          MAGE: Modality-Agnostic Music Generation and Editing
 - **Authors:** Muhammad Usama Saleem, Tejasvi Ravi, Tianyu Xu, Rajeev Nongpiur, Ishan Chatterjee, Mayur Jagdishbhai Patel, Pu Wang
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal music creation requires models that can both generate audio from high-level cues and edit existing mixtures in a targeted manner. Yet most multimodal music systems are built for a single task and a fixed prompting interface, making their conditioning brittle when guidance is ambiguous, temporally misaligned, or partially missing. Common additive fusion or feature concatenation further weakens cross-modal grounding, often causing prompt drift and spurious musical content during generation and editing. We propose MAGE, a modality-agnostic framework that unifies multimodal music generation and mixture-grounded editing within a single continuous latent formulation. At its core, MAGE uses a Controlled Multimodal FluxFormer, a flow-based Transformer that learns controllable latent trajectories for synthesis and editing under any available subset of conditions. To improve grounding, we introduce Audio-Visual Nexus Alignment to select temporally consistent visual evidence for the audio timeline, and a cross-gated modulation mechanism that applies multiplicative control from aligned visual and textual cues to the audio latents, suppressing unsupported components rather than injecting them. Finally, we train with a dynamic modality-masking curriculum that exposes the model to text-only, visual-only, joint multimodal, and mixture-guided settings, enabling robust inference under missing modalities without training separate models. Experiments on the MUSIC benchmark show that MAGE supports effective multimodal-guided music generation and targeted editing, achieving competitive quality while offering a lightweight and flexible interface tailored to practical music workflows.
### Title:
          Improving DNS Exfiltration Detection via Transformer Pretraining
 - **Authors:** Miloš Tomić, Aleksa Cvetanović, Predrag Tadić
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study whether in-domain pretraining of Bidirectional Encoder Representations from Transformer (BERT) model improves subdomain-level detection of exfiltration at low false positive rates. While previous work mostly examines fine-tuned generic Transformers, it does not aim to isolate the effect of pretraining on the downstream task of classification. To address this gap, we develop a controlled pipeline where we freeze operating points on validation and transfer them to the test set, thus enabling clean ablations across different label and pretraining budgets. Our results show significant improvements in the left tail of the Receiver Operating Characteristic (ROC) curve, especially against randomly initialized baseline. Additionally, within pretrained model variants, increasing the number of pretraining steps helps the most when more labeled data are available for fine-tuning.
### Title:
          Relational Preference Encoding in Looped Transformer Internal States
 - **Authors:** Jan Kirin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate how looped transformers encode human preference in their internal iteration states. Using Ouro-2.6B-Thinking, a 2.6B-parameter looped transformer with iterative refinement, we extract hidden states from each loop iteration and train lightweight evaluator heads (~5M parameters) to predict human preference on the Anthropic HH-RLHF dataset. Our pairwise evaluator achieves 95.2% test accuracy on 8,552 unseen examples, surpassing a full-batch L-BFGS probe (84.5%) while the base model remains completely frozen. Our central finding is that loop states encode preference predominantly relationally: a linear probe on pairwise differences achieves 84.5%, the best nonlinear independent evaluator reaches only 65% test accuracy, and linear independent classification scores 21.75%, below chance and with inverted polarity. Interpreted precisely, the evaluator functions as a model-internal consistency probe, measuring how stably Ouro's own learned value system organizes its representations rather than how well it predicts noisy human annotations. We also document a systematic architecture search that established a genuine 70% ceiling for independent scoring, and show how the 50% argument-swap protocol required to prevent degenerate pairwise solutions deflated pairwise training metrics by about 31 points at peak, creating the false appearance that pairwise and pointwise evaluators shared the same ceiling. Finally, we show that a cosine learning-rate dead zone at epoch 2 accidentally acted as early stopping, preserving the generalization peak before overfitting degraded test accuracy from 95.2% to 62.4% by epoch 5. Cross-epoch flip-test analysis shows that antisymmetry correlation remains stable while strict sign-flip rate mainly tracks scorer bias. We propose the flip test as a mandatory diagnostic for pairwise preference evaluators.
### Title:
          PointSplat: Efficient Geometry-Driven Pruning and Transformer Refinement for 3D Gaussian Splatting
 - **Authors:** Anh Thuan Tran, Jana Kosecka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has recently unlocked real-time, high-fidelity novel view synthesis by representing scenes using explicit 3D primitives. However, traditional methods often require millions of Gaussians to capture complex scenes, leading to significant memory and storage demands. Recent approaches have addressed this issue through pruning and per-scene fine-tuning of Gaussian parameters, thereby reducing the model size while maintaining visual quality. These strategies typically rely on 2D images to compute important scores followed by scene-specific optimization. In this work, we introduce PointSplat, 3D geometry-driven prune-and-refine framework that bridges previously disjoint directions of gaussian pruning and transformer refinement. Our method includes two key components: (1) an efficient geometry-driven strategy that ranks Gaussians based solely on their 3D attributes, removing reliance on 2D images during pruning stage, and (2) a dual-branch encoder that separates, re-weights geometric and appearance to avoid feature imbalance. Extensive experiments on ScanNet++ and Replica across varying sparsity levels demonstrate that PointSplat consistently achieves competitive rendering quality and superior efficiency without additional per-scene optimization.
### Title:
          I Walk the Line: Examining the Role of Gestalt Continuity in Object Binding for Vision Transformers
 - **Authors:** Alexa R. Tartaglini, Michael A. Lepori
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Object binding is a foundational process in visual cognition, during which low-level perceptual features are joined into object representations. Binding has been considered a fundamental challenge for neural networks, and a major milestone on the way to artificial models with flexible visual intelligence. Recently, several investigations have demonstrated evidence that binding mechanisms emerge in pretrained vision models, enabling them to associate portions of an image that contain an object. The question remains: how are these models binding objects together? In this work, we investigate whether vision models rely on the principle of Gestalt continuity to perform object binding, over and above other principles like similarity and proximity. Using synthetic datasets, we demonstrate that binding probes are sensitive to continuity across a wide range of pretrained vision transformers. Next, we uncover particular attention heads that track continuity, and show that these heads generalize across datasets. Finally, we ablate these attention heads, and show that they often contribute to producing representations that encode object binding.
### Title:
          EncFormer: Secure and Efficient Transformer Inference over Encrypted Data
 - **Authors:** Yufan Zhu, Chao Jin, Khin Mi Mi Aung, Xiaokui Xiao
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer inference in machine-learning-as-a-service (MLaaS) raises privacy concerns for sensitive user inputs. Prior secure solutions that combine fully homomorphic encryption (FHE) and secure multiparty computation (MPC) are bottlenecked by inefficient FHE kernels, communication-heavy MPC protocols, and expensive FHE-MPC conversions. We present EncFormer, a two-party private Transformer inference framework that introduces Stage Compatible Patterns so that FHE kernels compose efficiently, reducing repacking and conversions. EncFormer also provides a cost analysis model built around a minimal-conversion baseline, enabling principled selection of FHE-MPC boundaries. To further reduce communication, EncFormer proposes a secure complex CKKS-MPC conversion protocol and designs communication-efficient MPC protocols for nonlinearities. With GPU optimizations, evaluations on GPT- and BERT-style models show that EncFormer achieves 1.4x-30.4x lower online MPC communication and 1.3x-9.8x lower end-to-end latency against prior hybrid FHE-MPC systems, and 1.9x-3.5x lower end-to-end latency on BERT-base than FHE-only pipelines under a matched backend, while maintaining near-plaintext accuracy on selected GLUE tasks.
### Title:
          Gait Recognition with Temporal Kolmogorov-Arnold Networks
 - **Authors:** Mohammed Asad, Dinesh Kumar Vishwakarma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gait recognition is a biometric modality that identifies individuals from their characteristic walking patterns. Unlike conventional biometric traits, gait can be acquired at a distance and without active subject cooperation, making it suitable for surveillance and public safety applications. Nevertheless, silhouette-based temporal models remain sensitive to long sequences, observation noise, and appearance-related covariates. Recurrent architectures often struggle to preserve information from earlier frames and are inherently sequential to optimize, whereas transformer-based models typically require greater computational resources and larger training sets and may be sensitive to irregular sequence lengths and noisy inputs. These limitations reduce robustness under clothing variation, carrying conditions, and view changes, while also hindering the joint modeling of local gait cycles and longer-term motion trends. To address these challenges, we introduce a Temporal Kolmogorov-Arnold Network (TKAN) for gait recognition. The proposed model replaces fixed edge weights with learnable one-dimensional functions and incorporates a two-level memory mechanism consisting of short-term RKAN sublayers and a gated long-term pathway. This design enables efficient modeling of both cycle-level dynamics and broader temporal context while maintaining a compact backbone. Experiments on the CASIA-B dataset indicate that the proposed CNN+TKAN framework achieves strong recognition performance under the reported evaluation setting.
### Title:
          SwinTextUNet: Integrating CLIP-Based Text Guidance into Swin Transformer U-Nets for Medical Image Segmentation
 - **Authors:** Ashfak Yeafi, Parthaw Goswami, Md Khairul Islam, Ashifa Islam Shamme
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precise medical image segmentation is fundamental for enabling computer aided diagnosis and effective treatment planning. Traditional models that rely solely on visual features often struggle when confronted with ambiguous or low contrast patterns. To overcome these limitations, we introduce SwinTextUNet, a multimodal segmentation framework that incorporates Contrastive Language Image Pretraining (CLIP), derived textual embeddings into a Swin Transformer UNet backbone. By integrating cross attention and convolutional fusion, the model effectively aligns semantic text guidance with hierarchical visual representations, enhancing robustness and accuracy. We evaluate our approach on the QaTaCOV19 dataset, where the proposed four stage variant achieves an optimal balance between performance and complexity, yielding Dice and IoU scores of 86.47% and 78.2%, respectively. Ablation studies further validate the importance of text guidance and multimodal fusion. These findings underscore the promise of vision language integration in advancing medical image segmentation and supporting clinically meaningful diagnostic tools.
### Title:
          On The Application of Linear Attention in Multimodal Transformers
 - **Authors:** Armin Gerami, Seyedehanita Madani, Ramani Duraiswami
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Transformers serve as the backbone for state-of-the-art vision-language models, yet their quadratic attention complexity remains a critical barrier to scalability. In this work, we investigate the viability of Linear Attention (LA) as a high-efficiency alternative within multimodal frameworks. By integrating LA, we reduce the computational overhead from quadratic to linear relative to sequence length while preserving competitive performance. We evaluate our approach across ViT-S/16, ViT-B/16, and ViT-L/16 architectures trained on the LAION-400M dataset, with validation focused on ImageNet-21K zero-shot accuracy. Our systematic evaluation demonstrates that Linear Attention not only yields significant computational savings but also adheres to the same scaling laws as standard softmax attention. These findings position Linear Attention as a robust, scalable solution for next-generation multimodal Transformers tasked with processing increasingly large and complex datasets.
### Title:
          Transformers Learn the Optimal DDPM Denoiser for Multi-Token GMMs
 - **Authors:** Hongkang Li, Hancheng Min, Rene Vidal
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based diffusion models have demonstrated remarkable performance at generating high-quality samples. However, our theoretical understanding of the reasons for this success remains limited. For instance, existing models are typically trained by minimizing a denoising objective, which is equivalent to fitting the score function of the training data. However, we do not know why transformer-based models can match the score function for denoising, or why gradient-based methods converge to the optimal denoising model despite the non-convex loss landscape. To the best of our knowledge, this paper provides the first convergence analysis for training transformer-based diffusion models. More specifically, we consider the population Denoising Diffusion Probabilistic Model (DDPM) objective for denoising data that follow a multi-token Gaussian mixture distribution. We theoretically quantify the required number of tokens per data point and training iterations for the global convergence towards the Bayes optimal risk of the denoising objective, thereby achieving a desired score matching error. A deeper investigation reveals that the self-attention module of the trained transformer implements a mean denoising mechanism that enables the trained model to approximate the oracle Minimum Mean Squared Error (MMSE) estimator of the injected noise in the diffusion steps. Numerical experiments validate these findings.
### Title:
          Attention-Guided Dual-Stream Learning for Group Engagement Recognition: Fusing Transformer-Encoded Motion Dynamics with Scene Context via Adaptive Gating
 - **Authors:** Saniah Kayenat Chowdhury, Muhammad E.H. Chowdhury
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Student engagement is crucial for improving learning outcomes in group activities. Highly engaged students perform better both individually and contribute to overall group success. However, most existing automated engagement recognition methods are designed for online classrooms or estimate engagement at the individual level. Addressing this gap, we propose DualEngage, a novel two-stream framework for group-level engagement recognition from in-classroom videos. It models engagement as a joint function of both individual and group-level behaviors. The primary stream models person-level motion dynamics by detecting and tracking students, extracting dense optical flow with the Recurrent All-Pairs Field Transforms network, encoding temporal motion patterns using a transformer encoder, and finally aggregating per-student representations through attention pooling into a unified representation. The secondary stream captures scene-level spatiotemporal information from the full video clip, leveraging a pretrained three-dimensional Residual Network. The two-stream representations are combined via softmax-gated fusion, which dynamically weights each stream's contribution based on the joint context of both features. DualEngage learns a joint representation of individual actions with overarching group dynamics. We evaluate the proposed approach using fivefold cross-validation on the Classroom Group Engagement Dataset developed by Ocean University of China, achieving an average classification accuracy of 0.9621+/-0.0161 with a macro-averaged F1 of 0.9530+/-0.0204. To understand the contribution of each branch, we further conduct an ablation study comparing single-stream variants against the two-stream model. This work is among the first in classroom engagement recognition to adopt a dual-stream design that explicitly leverages motion cues as an estimator.
### Title:
          Global monitoring of methane point sources using deep learning on hyperspectral radiance measurements from EMIT
 - **Authors:** Vishal V. Batchu, Michelangelo Conserva, Alex Wilson, Anna M. Michalak, Varun Gulshan, Philip G. Brodrick, Andrew K. Thorpe, Christopher V. Arsdale
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Atmospheric and Oceanic Physics (physics.ao-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Anthropogenic methane (CH4) point sources drive near-term climate forcing, safety hazards, and system inefficiencies. Space-based imaging spectroscopy is emerging as a tool for identifying emissions globally, but existing approaches largely rely on manual plume identification. Here we present the Methane Analysis and Plume Localization with EMIT (MAPL-EMIT) model, an end-to-end vision transformer framework that leverages the complete radiance spectrum from the Earth Surface Mineral Dust Source Investigation (EMIT) instrument to jointly retrieve methane enhancements across all pixels within a scene. This approach brings together spectral and spatial context to significantly lower detection limits. MAPL-EMIT simultaneously supports enhancement quantification, plume delineation, and source localization, even for multiple overlapping plumes. The model was trained on 3.6 million physics-based synthetic plumes injected into global EMIT radiance data. Synthetic evaluation confirms the model's ability to identify plumes with high recall and precision and to capture weaker plumes relative to existing matched-filter approaches. On real-world benchmarks, MAPL-EMIT captures 79% of known hand-annotated NASA L2B plume complexes across a test set of 1084 EMIT granules, while capturing twice as many plausible plumes than identified by human analysts. Further validation against coincident airborne data, top-emitting landfills, and controlled release experiments confirms the model's ability to identify previously uncaptured sources. By incorporating model-generated metrics such as spectral fit scores and estimated noise levels, the framework can further limit false-positive rates. Overall, MAPL-EMIT enables high-throughput implementation on the full EMIT catalog, shifting methane monitoring from labor-intensive workflows to a rapid, scalable paradigm for global plume mapping at the facility scale.
### Title:
          Attention Sink in Transformers: A Survey on Utilization, Interpretation, and Mitigation
 - **Authors:** Zunhai Su, Hengyuan Zhang, Wei Wu, Yifan Zhang, Yaxiu Liu, He Xiao, Qingyao Yang, Yuxuan Sun, Rui Yang, Chao Zhang, Keyu Fan, Weihao Ye, Jing Xiong, Hui Shen, Chaofan Tao, Taiqiang Wu, Zhongwei Wan, Yulei Qian, Yuchen Xie, Ngai Wong
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As the foundational architecture of modern machine learning, Transformers have driven remarkable progress across diverse AI domains. Despite their transformative impact, a persistent challenge across various Transformers is Attention Sink (AS), in which a disproportionate amount of attention is focused on a small subset of specific yet uninformative tokens. AS complicates interpretability, significantly affecting the training and inference dynamics, and exacerbates issues such as hallucinations. In recent years, substantial research has been dedicated to understanding and harnessing AS. However, a comprehensive survey that systematically consolidates AS-related research and offers guidance for future advancements remains lacking. To address this gap, we present the first survey on AS, structured around three key dimensions that define the current research landscape: Fundamental Utilization, Mechanistic Interpretation, and Strategic Mitigation. Our work provides a pivotal contribution by clarifying key concepts and guiding researchers through the evolution and trends of the field. We envision this survey as a definitive resource, empowering researchers and practitioners to effectively manage AS within the current Transformer paradigm, while simultaneously inspiring innovative advancements for the next generation of Transformers. The paper list of this work is available at this https URL.
### Title:
          Dual-Branch Remote Sensing Infrared Image Super-Resolution
 - **Authors:** Xining Ge, Gengjia Chang, Weijun Yuan, Zhan Li, Zhanglu Chen, Boyang Yao, Yihang Chen, Yifan Deng, Shuhong Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote sensing infrared image super-resolution aims to recover sharper thermal observations from low-resolution inputs while preserving target contours, scene layout, and radiometric stability. Unlike visible-image super-resolution, thermal imagery is weakly textured and more sensitive to unstable local sharpening, which makes complementary local and global modeling especially important. This paper presents our solution to the NTIRE 2026 Infrared Image Super-Resolution Challenge, a dual-branch system that combines a HAT-L branch and a MambaIRv2-L branch. The inference pipeline applies test-time local conversion on HAT, eight-way self-ensemble on MambaIRv2, and fixed equal-weight image-space fusion. We report both the official challenge score and a reproducible evaluation on 12 synthetic times-four thermal samples derived from Caltech Aerial RGB-Thermal, on which the fused output outperforms either single branch in PSNR, SSIM, and the overall Score. The results suggest that infrared super-resolution benefits from explicit complementarity between locally strong transformer restoration and globally stable state-space modeling.
### Title:
          Tracing the Thought of a Grandmaster-level Chess-Playing Transformer
 - **Authors:** Rui Lin, Zhenyu Jin, Guancheng Zhou, Xuyang Ge, Wentao Shu, Jiaxing Wu, Junxuan Wang, Zhengfu He, Junping Zhang, Xipeng Qiu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While modern transformer neural networks achieve grandmaster-level performance in chess and other reasoning tasks, their internal computation process remains largely opaque. Focusing on Leela Chess Zero (LC0), we introduce a sparse decomposition framework to interpret its internal computation by decomposing its MLP and attention modules with sparse replacement layers, which capture the primary computation process of LC0. We conduct a detailed case study showing that these pathways expose rich, interpretable tactical considerations that are empirically verifiable. We further introduce three quantitative metrics and show that LC0 exhibits parallel reasoning behavior consistent with the inductive bias of its policy head architecture. To the best of our knowledge, this is the first work to decompose the internal computation of a transformer on both MLP and attention modules for interpretability. Combining sparse replacement layers and causal interventions in LC0 provides a comprehensive understanding of advanced tactical reasoning, offering critical insights into the underlying mechanisms of superhuman systems. Our code is available at this https URL.
### Title:
          PoreDiT: A Scalable Generative Model for Large-Scale Digital Rock Reconstruction
 - **Authors:** Yizhuo Huang, Baoquan Sun, Haibo Huang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Applied Physics (physics.app-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This manuscript presents PoreDiT, a novel generative model designed for high-efficiency digital rock reconstruction at gigavoxel scales. Addressing the significant challenges in digital rock physics (DRP), particularly the trade-off between resolution and field-of-view (FOV), and the computational bottlenecks associated with traditional deep learning architectures, PoreDiT leverages a three-dimensional (3D) Swin Transformer to break through these limitations. By directly predicting the binary probability field of pore spaces instead of grayscale intensities, the model preserves key topological features critical for pore-scale fluid flow and transport simulations. This approach enhances computational efficiency, enabling the generation of ultra-large-scale ($1024^3$ voxels) digital rock samples on consumer-grade hardware. Furthermore, PoreDiT achieves physical fidelity comparable to previous state-of-the-art methods, including accurate porosity, pore-scale permeability, and Euler characteristics. The model's ability to scale efficiently opens new avenues for large-domain hydrodynamic simulations and provides practical solutions for researchers in pore-scale fluid mechanics, reservoir characterization, and carbon sequestration.
### Title:
          A3-FPN: Asymptotic Content-Aware Pyramid Attention Network for Dense Visual Prediction
 - **Authors:** Meng'en Qin, Yu Song, Quanling Zhao, Xiaodong Yang, Yingtao Che, Xiaohui Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning multi-scale representations is the common strategy to tackle object scale variation in dense prediction tasks. Although existing feature pyramid networks have greatly advanced visual recognition, inherent design defects inhibit them from capturing discriminative features and recognizing small objects. In this work, we propose Asymptotic Content-Aware Pyramid Attention Network (A3-FPN), to augment multi-scale feature representation via the asymptotically disentangled framework and content-aware attention modules. Specifically, A3-FPN employs a horizontally-spread column network that enables asymptotically global feature interaction and disentangles each level from all hierarchical representations. In feature fusion, it collects supplementary content from the adjacent level to generate position-wise offsets and weights for context-aware resampling, and learns deep context reweights to improve intra-category similarity. In feature reassembly, it further strengthens intra-scale discriminative feature learning and reassembles redundant features based on information content and spatial variation of feature maps. Extensive experiments on MS COCO, VisDrone2019-DET and Cityscapes demonstrate that A3-FPN can be easily integrated into state-of-the-art CNN and Transformer-based architectures, yielding remarkable performance gains. Notably, when paired with OneFormer and Swin-L backbone, A3-FPN achieves 49.6 mask AP on MS COCO and 85.6 mIoU on Cityscapes. Codes are available at this https URL.
### Title:
          Descriptor-Injected Cross-Modal Learning: A Systematic Exploration of Audio-MIDI Alignment via Spectral and Melodic Features
 - **Authors:** Mariano Fernández Méndez
 - **Subjects:** Subjects:
Sound (cs.SD); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-modal retrieval between audio recordings and symbolic music representations (MIDI) remains challenging because continuous waveforms and discrete event sequences encode different aspects of the same performance. We study descriptor injection, the augmentation of modality-specific encoders with hand-crafted domain features, as a bridge across this gap. In a three-phase campaign covering 13 descriptor-mechanism combinations, 6 architectural families, and 3 training schedules, the best configuration reaches a mean S of 84.0 percent across five independent seeds, improving the descriptor-free baseline by 8.8 percentage points. Causal ablation shows that the audio descriptor A4, based on octave-band energy dynamics, drives the gain in the top dual models, while the MIDI descriptor D4 has only a weak inference-time effect despite improving training dynamics. We also introduce reverse cross-attention, where descriptor tokens query encoder features, reducing attention operations relative to the standard formulation while remaining competitive. CKA analysis shows that descriptors substantially increase audio-MIDI transformer layer alignment, indicating representational convergence rather than simple feature concatenation. Perturbation analysis identifies high-frequency octave bands as the dominant discriminative signal. All experiments use MAESTRO v3.0.0 with an evaluation protocol controlling for composer and piece similarity.
### Title:
          Integrating SAINT with Tree-Based Models: A Case Study in Employee Attrition Prediction
 - **Authors:** Adil Derrazi, Javad Pourmostafa Roshan Sharami
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Employee attrition presents a major challenge for organizations, increasing costs and reducing productivity. Predicting attrition accurately enables proactive retention strategies, but existing machine learning models often struggle to capture complex feature interactions in tabular HR datasets. While tree-based models such as XGBoost and LightGBM perform well on structured data, traditional encoding techniques like one-hot encoding can introduce sparsity and fail to preserve semantic relationships between categorical features. This study explores a hybrid approach by integrating SAINT (Self-Attention and Intersample Attention Transformer)-generated embeddings with tree-based models to enhance employee attrition prediction. SAINT leverages self-attention mechanisms to model intricate feature interactions. In this study, we explore SAINT both as a standalone classifier and as a feature extractor for tree-based models. We evaluate the performance, generalizability, and interpretability of standalone models (SAINT, XGBoost, LightGBM) and hybrid models that combine SAINT embeddings with tree-based classifiers. Experimental results show that standalone tree-based models outperform both the standalone SAINT model and the hybrid approaches in predictive accuracy and generalization. Contrary to expectations, the hybrid models did not improve performance. One possible explanation is that tree-based models struggle to utilize dense, high-dimensional embeddings effectively. Additionally, the hybrid approach significantly reduced interpretability, making model decisions harder to explain. These findings suggest that transformer-based embeddings, while capturing feature relationships, do not necessarily enhance tree-based classifiers. Future research should explore alternative fusion strategies for integrating deep learning with structured data.
### Title:
          Multi-modal, multi-scale representation learning for satellite imagery analysis just needs a good ALiBi
 - **Authors:** Patrick Kage, Pavlos Andreadis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision foundation models have been shown to be effective at processing satellite imagery into representations fit for downstream tasks, however, creating models which operate over multiple spatial resolutions and modes is challenging. This paper presents Scale-ALiBi, a linear bias transformer attention mechanism with a spatial encoding bias to relationships between image patches at different ground sample distance scales. We provide an implementation of Scale-ALiBi over a dataset of aligned high- and low-resolution optical and low-resolution SAR satellite imagery data using a triple-contrastive and reconstructive architecture, show an improvement on the GEO-Bench benchmark, and release the newly curated dataset publicly.
### Title:
          Sense Less, Infer More: Agentic Multimodal Transformers for Edge Medical Intelligence
 - **Authors:** Chengwei Zhou, Zhaoyan Jia, Haotian Yu, Xuming Chen, Brandon Lee, Christopher Pulliam, Steve Majerus, Massoud Pedram, Gourav Datta
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Edge-based multimodal medical monitoring requires models that balance diagnostic accuracy with severe energy constraints. Continuous acquisition of ECG, PPG, EMG, and IMU streams rapidly drains wearable batteries, often limiting operation to under 10 hours, while existing systems overlook the high temporal redundancy present in physiological signals. We introduce Adaptive Multimodal Intelligence (AMI), an end-to-end framework that jointly learns when to sense and how to infer. AMI integrates three components: (1) a lightweight Agentic Modality Controller that uses differentiable Gumbel-Sigmoid gating to dynamically select active sensors based on model confidence and task relevance; (2) a Learned Sigma-Delta Sensing module that applies patch-wise Delta-Sigma operations with learnable thresholds to skip temporally redundant samples; and (3) a Foundation-backed Multimodal Prediction Model built on unimodal foundation encoders and a cross-modal transformer with temporal context, enabling robust fusion even under gated or missing inputs. These components are trained jointly via a multi-objective loss combining classification accuracy, sparsity regularization, cross-modal alignment, and predictive coding. AMI is hardware-aware, supporting dynamic computation graphs and masked operations, leading to real energy and latency savings. Across MHEALTH, HMC Sleep, and WESAD datasets, it reduces sensor usage by 48.8% while improving state-of-the-art accuracy by 1.9% on average.
### Title:
          Membership Inference Attacks Expose Participation Privacy in ECG Foundation Encoders
 - **Authors:** Ziyu Wang, Elahe Khatibi, Ankita Sharma, Krishnendu Chakrabarty, Sanaz Rahimi Moosavi, Farshad Firouzi, Amir Rahmani
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation-style ECG encoders pretrained with self-supervised learning are increasingly reused across tasks, institutions, and deployment contexts, often through model-as-a-service interfaces that expose scalar scores or latent representations. While such reuse improves data efficiency and generalization, it raises a participation privacy concern: can an adversary infer whether a specific individual or cohort contributed ECG data to pretraining, even when raw waveforms and diagnostic labels are never disclosed? In connected-health settings, training participation itself may reveal institutional affiliation, study enrollment, or sensitive health context. We present an implementation-grounded audit of membership inference attacks (MIAs) against modern self-supervised ECG foundation encoders, covering contrastive objectives (SimCLR, TS2Vec) and masked reconstruction objectives (CNN- and Transformer-based MAE). We evaluate three realistic attacker interfaces: (i) score-only black-box access to scalar outputs, (ii) adaptive learned attackers that aggregate subject-level statistics across repeated queries, and (iii) embedding-access attackers that probe latent representation geometry. Using a subject-centric protocol with window-to-subject aggregation and calibration at fixed false-positive rates under a cross-dataset auditing setting, we observe heterogeneous and objective-dependent participation leakage: leakage is most pronounced in small or institution-specific cohorts and, for contrastive encoders, can saturate in embedding space, while larger and more diverse datasets substantially attenuate operational tail risk. Overall, our results show that restricting access to raw signals or labels is insufficient to guarantee participation privacy, underscoring the need for deployment-aware auditing of reusable biosignal foundation encoders in connected-health systems.
### Title:
          Dynamic Adaptive Attention and Supervised Contrastive Learning: A Novel Hybrid Framework for Text Sentiment Classification
 - **Authors:** Qingyang Li
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The exponential growth of user-generated movie reviews on digital platforms has made accurate text sentiment classification a cornerstone task in natural language processing. Traditional models, including standard BERT and recurrent architectures, frequently struggle to capture long-distance semantic dependencies and resolve ambiguous emotional expressions in lengthy review texts. This paper proposes a novel hybrid framework that seamlessly integrates dynamic adaptive multi-head attention with supervised contrastive learning into a BERT-based Transformer encoder. The dynamic adaptive attention module employs a global context pooling vector to dynamically regulate the contribution of each attention head, thereby focusing on critical sentiment-bearing tokens while suppressing noise. Simultaneously, the supervised contrastive learning branch enforces tighter intra-class compactness and larger inter-class separation in the embedding space. Extensive experiments on the IMDB dataset demonstrate that the proposed model achieves competitive performance with an accuracy of 94.67\%, outperforming strong baselines by 1.5--2.5 percentage points. The framework is lightweight, efficient, and readily extensible to other text classification tasks.
### Title:
          UDAPose: Unsupervised Domain Adaptation for Low-Light Human Pose Estimation
 - **Authors:** Haopeng Chen, Yihao Ai, Kabeen Kim, Robby T. Tan, Yixin Chen, Bo Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-visibility scenarios, such as low-light conditions, pose significant challenges to human pose estimation due to the scarcity of annotated low-light datasets and the loss of visual information under poor illumination. Recent domain adaptation techniques attempt to utilize well-lit labels by augmenting well-lit images to mimic low-light conditions. But handcrafted augmentations oversimplify noise patterns, while learning-based methods often fail to preserve high-frequency low-light characteristics, producing unrealistic images that lead pose models to generalize poorly to real low-light scenes. Moreover, recent pose estimators rely on image cues through image-to-keypoint cross-attention, but these cues become unreliable under low-light conditions. To address these issues, we propose Unsupervised Domain Adaptation for Pose Estimation (UDAPose), a novel framework that synthesizes low-light images and dynamically fuses visual cues with pose priors for improved pose estimation. Specifically, our synthesis method incorporates a Direct-Current-based High-Pass Filter (DHF) and a Low-light Characteristics Injection Module (LCIM) to inject high-frequency details from input low-light images, overcoming rigidity or the detail loss in existing approaches. Furthermore, we introduce a Dynamic Control of Attention (DCA) module that adaptively balances image cues with learned pose priors in the Transformer architecture. Experiments show that UDAPose outperforms state-of-the-art methods, with notable AP gains of 10.1 (56.4%) on the ExLPose-test hard set (LL-H) and 7.4 (31.4%) in cross-dataset validation on EHPT-XC. Code: this https URL
### Title:
          SEED: A Large-Scale Benchmark for Provenance Tracing in Sequential Deepfake Facial Edits
 - **Authors:** Mengieong Hoi, Zhedong Zheng, Ping Liu, Wei Liu
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deepfake content on social networks is increasingly produced through multiple \emph{sequential} edits to biometric data such as facial imagery. Consequently, the final appearance of an image often reflects a latent chain of operations rather than a single manipulation. Recovering these editing histories is essential for visual provenance analysis, misinformation auditing, and forensic or platform moderation workflows that must trace the origin and evolution of AI-generated media. However, existing datasets predominantly focus on single-step editing and overlook the cumulative artifacts introduced by realistic multi-step pipelines. To address this gap, we introduce Sequential Editing in Diffusion (\textbf{SEED}), a large-scale benchmark for sequential provenance tracing in facial imagery. SEED contains over 90K images constructed via one to four sequential attribute edits using diffusion-based editing pipelines, with fine-grained annotations including edit order, textual instructions, manipulation masks, and generation models. These metadata enable step-wise evidence analysis and support forgery detection, sequence prediction. To benchmark the challenges posed by SEED, we evaluate representative analysis strategies and observe that spatial-only approaches struggle under subtle and distributed diffusion artifacts, especially when such artifacts accumulate across multiple edits. Motivated by this observation, we further establish \textbf{FAITH}, a frequency-aware Transformer baseline that aggregates spatial and frequency-domain cues to identify and order latent editing events. Results show that high-frequency signals, particularly wavelet components, provide effective cues even under image degradation. Overall, SEED facilitates systematic study of sequential provenance tracing and evidence aggregation for trustworthy analysis of AI-generated visual content.
### Title:
          TAPNext++: What's Next for Tracking Any Point (TAP)?
 - **Authors:** Sebastian Jung, Artem Zholus, Martin Sundermeyer, Carl Doersch, Ross Goroshin, David Joseph Tan, Sarath Chandar, Rudolph Triebel, Federico Tombari
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tracking-Any-Point (TAP) models aim to track any point through a video which is a crucial task in AR/XR and robotics applications. The recently introduced TAPNext approach proposes an end-to-end, recurrent transformer architecture to track points frame-by-frame in a purely online fashion -- demonstrating competitive performance at minimal latency. However, we show that TAPNext struggles with longer video sequences and also frequently fails to re-detect query points that reappear after being occluded or leaving the frame. In this work, we present TAPNext++, a model that tracks points in sequences that are orders of magnitude longer while preserving the low memory and compute footprint of the architecture. We train the recurrent video transformer using several data-driven solutions, including training on long 1024-frame sequences enabled by sequence parallelism techniques. We highlight that re-detection performance is a blind spot in the current literature and introduce a new metric, Re-Detection Average Jaccard ($AJ_{RD}$), to explicitly evaluate tracking on re-appearing points. To improve re-detection of points, we introduce tailored geometric augmentations, such as periodic roll that simulates point re-entries, and supervising occluded points. We demonstrate that recurrent transformers can be substantially improved for point tracking and set a new state-of-the-art on multiple benchmarks. Model and code can be found at this https URL.
### Title:
          LogitDynamics: Reliable ViT Error Detection from Layerwise Logit Trajectories
 - **Authors:** Ido Beigelman, Moti Freiman
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable confidence estimation is critical when deploying vision models. We study error prediction: determining whether an image classifier's output is correct using only signals from a single forward pass. Motivated by internal-signal hallucination detection in large language models, we investigate whether similar depth-wise signals exist in Vision Transformers (ViTs). We propose a simple method that models how class evidence evolves across layers. By attaching lightweight linear heads to intermediate layers, we extract features from the last L layers that capture both the logits of the predicted class and its top-K competitors, as well as statistics describing instability of top-ranked classes across depth. A linear probe trained on these features predicts the error indicator. Across datasets, our method improves or matches AUCPR over baselines and shows stronger cross-dataset generalization while requiring minimal additional computation.
### Title:
          INCRT: An Incremental Transformer That Determines Its Own Architecture
 - **Authors:** Giansalvo Cirrincione
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer architectures are designed by trial and error: the number of attention heads, the depth, and the head size are fixed before training begins, with no mathematical principle to guide the choice. The result is systematic structural redundancy -- between half and four-fifths of all heads in a trained model can be removed without measurable loss -- because the architecture allocates capacity without reference to the actual requirements of the this http URL paper introduces INCRT (Incremental Transformer), an architecture that determines its own structure during training. Starting from a single head, INCRT adds one attention head at a time whenever its current configuration is provably insufficient, and prunes heads that have become redundant. Each growth decision is driven by a single, online-computable geometric quantity derived from the task's directional structure, requiring no separate validation phase and no hand-tuned schedule. Two theorems form the theoretical backbone. The first (homeostatic convergence) establishes that the system always reaches a finite stopping configuration that is simultaneously minimal (no redundant heads) and sufficient (no uncaptured directional energy above the threshold). The second (compressed-sensing analogy) provides a geometric upper bound on the number of heads that this configuration can contain, as a function of the spectral complexity of the task. Experiments on SARS-CoV-2 variant classification and SST-2 sentiment analysis confirm both results: the predicted and observed head counts agree within 12% across all benchmarks, and the final architectures match or exceed BERT-base on distribution-specific tasks while using between three and seven times fewer parameters and no pre-training.
### Title:
          Audio-Omni: Extending Multi-modal Understanding to Versatile Audio Generation and Editing
 - **Authors:** Zeyue Tian, Binxin Yang, Zhaoyang Liu, Jiexuan Zhang, Ruibin Yuan, Hubery Yin, Qifeng Chen, Chen Li, Jing Lv, Wei Xue, Yike Guo
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in multimodal models has spurred rapid advances in audio understanding, generation, and editing. However, these capabilities are typically addressed by specialized models, leaving the development of a truly unified framework that can seamlessly integrate all three tasks underexplored. While some pioneering works have explored unifying audio understanding and generation, they often remain confined to specific domains. To address this, we introduce Audio-Omni, the first end-to-end framework to unify generation and editing across general sound, music, and speech domains, with integrated multi-modal understanding capabilities. Our architecture synergizes a frozen Multimodal Large Language Model for high-level reasoning with a trainable Diffusion Transformer for high-fidelity synthesis. To overcome the critical data scarcity in audio editing, we construct AudioEdit, a new large-scale dataset comprising over one million meticulously curated editing pairs. Extensive experiments demonstrate that Audio-Omni achieves state-of-the-art performance across a suite of benchmarks, outperforming prior unified approaches while achieving performance on par with or superior to specialized expert models. Beyond its core capabilities, Audio-Omni exhibits remarkable inherited capabilities, including knowledge-augmented reasoning generation, in-context generation, and zero-shot cross-lingual control for audio generation, highlighting a promising direction toward universal generative audio intelligence. The code, model, and dataset will be publicly released on this https URL.
### Title:
          Position-Agnostic Pre-Projection for Transformer Attention: Nonlinear Feature Construction and Content Skip Before Q/K/V
 - **Authors:** Chirag Shinde
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose two complementary modifications to transformer attention blocks. First, a non-linear pre-projection MLP is inserted between layer norm and Q/K/V projections, constructing richer features in a position-agnostic manner before any positional encoding is applied. Second, a content skip connection routes the pre-projection's features around the attention mechanism, allowing content information to bypass position-aware attention where beneficial. In frozen-probe experiments on Pythia-160M and 410M, the combined approach achieves the strongest results across methods: +40.6% LAMBADA accuracy and -39% perplexity at 160M scale. Learned skip connection weights reveal a consistent pattern across model sizes: later transformer layers activate the content bypass more strongly than earlier layers, suggesting that deeper layers benefit from content information that does not pass through positional attention. All modifications add no K/V cache overhead.
### Title:
          Transformers Learn Latent Mixture Models In-Context via Mirror Descent
 - **Authors:** Francesco D'Angelo, Nicolas Flammarion
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequence modelling requires determining which past tokens are causally relevant from the context and their importance: a process inherent to the attention layers in transformers, yet whose underlying learned mechanisms remain poorly understood. In this work, we formalize the task of estimating token importance as an in-context learning problem by introducing a framework based on Mixture of Transition Distributions, where a latent variable determines the influence of past tokens on the next. The distribution over this latent variable is parameterized by unobserved mixture weights that transformers must learn in-context. We demonstrate that transformers can implement Mirror Descent to learn these weights from the context. Specifically, we give an explicit construction of a three-layer transformer that exactly implements one step of Mirror Descent and prove that the resulting estimator is a first-order approximation of the Bayes-optimal predictor. Corroborating our construction and its learnability via gradient descent, we empirically show that transformers trained from scratch learn solutions consistent with our theory: their predictive distributions, attention patterns, and learned transition matrix closely match the construction, while deeper models achieve performance comparable to multi-step Mirror Descent.
### Title:
          LiveGesture Streamable Co-Speech Gesture Generation Model
 - **Authors:** Muhammad Usama Saleem, Mayur Jagdishbhai Patel, Ekkasit Pinyoanuntapong, Zhongxing Qin, Li Yang, Hongfei Xue, Ahmed Helmy, Chen Chen, Pu Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose LiveGesture, the first fully streamable, speech-driven full-body gesture generation framework that operates with zero look-ahead and supports arbitrary sequence length. Unlike existing co-speech gesture methods, which are designed for offline generation and either treat body regions independently or entangle all joints within a single model, LiveGesture is built from the ground up for causal, region-coordinated motion generation. LiveGesture consists of two main modules: the Streamable Vector Quantized Motion Tokenizer (SVQ) and the Hierarchical Autoregressive Transformer (HAR). The SVQ tokenizer converts the motion sequence of each body region into causal, discrete motion tokens, enabling real-time, streamable token decoding. On top of SVQ, HAR employs region-expert autoregressive (xAR) transformers to model expressive, fine-grained motion dynamics for each body region. A causal spatio-temporal fusion module (xAR Fusion) then captures and integrates correlated motion dynamics across regions. Both xAR and xAR Fusion are conditioned on live, continuously arriving audio signals encoded by a streamable causal audio encoder. To enhance robustness under streaming noise and prediction errors, we introduce autoregressive masking training, which leverages uncertainty-guided token masking and random region masking to expose the model to imperfect, partially erroneous histories during training. Experiments on the BEAT2 dataset demonstrate that LiveGesture produces coherent, diverse, and beat-synchronous full-body gestures in real time, matching or surpassing state-of-the-art offline methods under true zero look-ahead conditions.
### Title:
          Progressive Deep Learning for Automated Spheno-Occipital Synchondrosis Maturation Assessment
 - **Authors:** Omid Halimi Milani, Amanda Nikho, Marouane Tliba, Lauren Mills, Emadeldeen Hamdan, Ahmet Enis Cetin, Mohammed H. Elnagar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate assessment of spheno-occipital synchondrosis (SOS) maturation is a key indicator of craniofacial growth and a critical determinant for orthodontic and surgical timing. However, SOS staging from cone-beam CT (CBCT) relies on subtle, continuously evolving morphological cues, leading to high inter-observer variability and poor reproducibility, especially at transitional fusion stages. We frame SOS assessment as a fine-grained visual recognition problem and propose a progressive representation-learning framework that explicitly mirrors how expert clinicians reason about synchondral fusion: from coarse anatomical structure to increasingly subtle patterns of closure. Rather than training a full-capacity network end-to-end, we sequentially grow the model by activating deeper blocks over time, allowing early layers to first encode stable cranial base morphology before higher-level layers specialize in discriminating adjacent maturation stages. This yields a curriculum over network depth that aligns deep feature learning with the biological continuum of SOS fusion. Extensive experiments across convolutional and transformer-based architectures show that this expert-inspired training strategy produces more stable optimization and consistently higher accuracy than standard training, particularly for ambiguous intermediate stages. Importantly, these gains are achieved without changing network architectures or loss functions, demonstrating that training dynamics alone can substantially improve anatomical representation learning. The proposed framework establishes a principled link between expert dental intuition and deep visual representations, enabling robust, data-efficient SOS staging from CBCT and offering a general strategy for modeling other continuous biological processes in medical imaging.
### Title:
          Learning to Adapt: In-Context Learning Beyond Stationarity
 - **Authors:** Zhen Qin, Jiachen Jiang, Zhihui Zhu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer models have become foundational across a wide range of scientific and engineering domains due to their strong empirical performance. A key capability underlying their success is in-context learning (ICL): when presented with a short prompt from an unseen task, transformers can perform per-token and next-token predictions without any parameter updates. Recent theoretical efforts have begun to uncover the mechanisms behind this phenomenon, particularly in supervised regression settings. However, these analyses predominantly assume stationary task distributions, which overlook a broad class of real-world scenarios where the target function varies over time. In this work, we bridge this gap by providing a theoretical analysis of ICL under non-stationary regression problems. We study how the gated linear attention (GLA) mechanism adapts to evolving input-output relationships and rigorously characterize its advantages over standard linear attention in this dynamic setting. To model non-stationarity, we adopt a first-order autoregressive process and show that GLA achieves lower training and testing errors by adaptively modulating the influence of past inputs -- effectively implementing a learnable recency bias. Our theoretical findings are further supported by empirical results, which validate the benefits of gating mechanisms in non-stationary ICL tasks.
### Title:
          Diffusion-CAM: Faithful Visual Explanations for dMLLMs
 - **Authors:** Haomin Zuo, Yidi Li, Luoxiao Yang, Xiaofeng Zhang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While diffusion Multimodal Large Language Models (dMLLMs) have recently achieved remarkable strides in multimodal generation, the development of interpretability mechanisms has lagged behind their architectural evolution. Unlike traditional autoregressive models that produce sequential activations, diffusion-based architectures generate tokens via parallel denoising, resulting in smooth, distributed activation patterns across the entire sequence. Consequently, existing Class Activation Mapping (CAM) methods, which are tailored for local, sequential dependencies, are ill-suited for interpreting these non-autoregressive behaviors. To bridge this gap, we propose Diffusion-CAM, the first interpretability method specifically tailored for dMLLMs. We derive raw activation maps by differentiably probing intermediate representations in the transformer backbone, accordingly capturing both latent features and their class-specific gradients. To address the inherent stochasticity of these raw signals, we incorporate four key modules to resolve spatial ambiguity and mitigate intra-image confounders and redundant token correlations. Extensive experiments demonstrate that Diffusion-CAM significantly outperforms SoTA methods in both localization accuracy and visual fidelity, establishing a new standard for understanding the parallel generation process of diffusion multimodal systems.
### Title:
          Byte-level generative predictions for forensics multimedia carving
 - **Authors:** Jaewon Lee, Md Eimran Hossain Eimon, Avinash Srinivasan, Hari Kalva
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Digital forensic investigations often face significant challenges when recovering fragmented multimedia files that lack file system metadata. While traditional file carving relies on signatures and discriminative deep learning models for fragment classification, these methods cannot reconstruct or predict missing data. We propose a generative approach to multimedia carving using bGPT, a byte-level transformer designed for next-byte prediction. By feeding partial BMP image data into the model, we simulate the generation of likely fragment continuations. We evaluate the fidelity of these predictions using different metrics, namely, cosine similarity, structural similarity index (SSIM), chi-square distance, and Jensen-Shannon divergence (JSD). Our findings demonstrate that generative models can effectively predict byte-level patterns to support fragment matching in unallocated disk space.
### Title:
          AnomalyGen: Enhancing Log-Based Anomaly Detection with Code-Guided Data Augmentation
 - **Authors:** Xinyu Li, Yintong Huo, Chenxi Mao, Shiwen Shan, Yuxin Su, Yanlin Wang, Zibin Zheng
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Log-based anomaly detection is fundamentally constrained by training data sparsity. Our empirical study reveals that public benchmark datasets cover less than 10% of source code log templates. Consequently, models frequently misclassify unseen but valid execution paths as anomalies, leading to false alarms. To address this, we propose AnomalyGen, a novel framework that augments training data by synthesizing labeled log sequences from source code. AnomalyGen combines log-oriented static analysis with Large Language Model (LLM) reasoning in three stages: (1) building Log-Oriented Control Flow Graphs (LCFGs) to enumerate structurally valid execution paths; (2) applying LLM Chain-of-Thought (CoT) reasoning to verify logical consistency and generate realistic runtime parameters (e.g., block IDs, IP addresses); and (3) labeling generated sequences with domain heuristics. Evaluations on HDFS and Zookeeper across 12 diverse anomaly detection models show AnomalyGen consistently improves performance. Deep learning models achieved average F1-score gains of 2.18% (HDFS) and 1.69% (Zookeeper), with an unsupervised Transformer on HDFS jumping from 0.818 to 0.970. Ablation results show that both static analysis and LLM-based verification are necessary: removing them reduces F1 by up to 8.7 and 10.7 percentage points, respectively. Our framework and datasets are publicly available to facilitate future research.
### Title:
          AIM: Intent-Aware Unified world action Modeling with Spatial Value Maps
 - **Authors:** Liaoyuan Fan, Zetian Xu, Chen Cao, Wenyao Zhang, Mingqi Yuan, Jiayu Chen
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pretrained video generation models provide strong priors for robot control, but existing unified world action models still struggle to decode reliable actions without substantial robot-specific training. We attribute this limitation to a structural mismatch: while video models capture how scenes evolve, action generation requires explicit reasoning about where to interact and the underlying manipulation intent. We introduce AIM, an intent-aware unified world action model that bridges this gap via an explicit spatial interface. Instead of decoding actions directly from future visual representations, AIM predicts an aligned spatial value map that encodes task-relevant interaction structure, enabling a control-oriented abstraction of future dynamics. Built on a pretrained video generation model, AIM jointly models future observations and value maps within a shared mixture-of-transformers architecture. It employs intent-causal attention to route future information to the action branch exclusively through the value representation. We further propose a self-distillation reinforcement learning stage that freezes the video and value branches and optimizes only the action head using dense rewards derived from projected value-map responses together with sparse task-level signals. To support training and evaluation, we construct a simulation dataset of 30K manipulation trajectories with synchronized multi-view observations, actions, and value-map annotations. Experiments on RoboTwin 2.0 benchmark show that AIM achieves a 94.0% average success rate, significantly outperforming prior unified world action baselines. Notably, the improvement is more pronounced in long-horizon and contact-sensitive manipulation tasks, demonstrating the effectiveness of explicit spatial-intent modeling as a bridge between visual world modeling and robot control.
### Title:
          CapBench: A Multi-PDK Dataset for Machine-Learning-Based Post-Layout Capacitance Extraction
 - **Authors:** Hector R. Rodriguez, Jiechen Huang, Wenjian Yu
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present CapBench, a fully reproducible, multi-PDK dataset for capacitance extraction. The dataset is derived from open-source designs, including single-core CPUs, systems-on-chip, and media accelerators. All designs are fully placed and routed using 14 independent OpenROAD flow runs spanning three technology nodes: ASAP7, NanGate45, and Sky130HD. From these layouts, we extract 61,855 3D windows across three size tiers to enable transfer learning and scalability studies. High-fidelity capacitance labels are generated using RWCap, a state-of-the-art random-walk solver, and validated against the industry-standard Raphael, achieving a mean absolute error of 0.64% for total capacitance. Each window is pre-processed into density maps, graph representations, and point clouds. We evaluate 10 machine learning architectures that illustrate dataset usage and serve as baselines, including convolutional neural networks (CNNs), point cloud transformers, and graph neural networks (GNNs). CNNs demonstrate the lowest errors (1.75%), while GNNs are up to 41.4x faster but exhibit larger errors (10.2%), illustrating a clear accuracy-speed trade-off. Code and dataset are available at this https URL.
### Title:
          THEIA: Learning Complete Kleene Three-Valued Logic in a Pure-Neural Modular Architecture
 - **Authors:** Augustus Haoyang Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present THEIA, a modular neural architecture that learns complete Kleene three-valued logic (K3) end-to-end without any external symbolic solver, and investigate what architectural prior enables compositional generalization under uncertainty. THEIA processes four mathematical domains (arithmetic, order, set membership, propositional logic) through dedicated engines that converge in a final logic module. Trained on a 2M-sample dataset with input space ~3.4x10^13, it achieves 12/12 Kleene K3 rule coverage across 5 seeds in 9.2 +/- 3.5 minutes (5.6x faster than a parameter-comparable Transformer under matched settings). A mod-3 sequential composition experiment generalizes from 5-step training to 500-step evaluation at 99.97% +/- 0.02% -- a result that critically depends on structured inductive bias: replacing the four-engine backbone with a flat MLP collapses length generalization to chance by 50 steps regardless of capacity (both 0.80M and parameter-matched 2.75M variants fail), while a pre-LN TF8LTuned Transformer baseline (3,582,147 params) trained under the identical protocol reaches 99.24% at 500 steps (Appendix D). Mechanistic probing reveals that modularity induces a delayed verdict: upstream engines encode domain-specific variables without committing to the final truth value (probe accuracy <= 74% uncertainty-only ceiling), with the verdict emerging only at the Logic Engine boundary -- causally confirmed by activation patching (100% flip rate on 986 matched pairs, replicated across n=5 seeds; 100.0% aggregate). The Transformer baseline reaches equivalent correctness through a qualitatively different representational trajectory (contraction then expansion), suggesting that modular and monolithic architectures implement distinct compositional strategies.
### Title:
          Winner-Take-All Spiking Transformer for Language Modeling
 - **Authors:** Chenlin Zhou, Sihang Guo, Jiaqi Wang, Dongyang Ma, Kaiwei Che, Baiyu Chen, Qingyan Meng, Zhengyu Ma, Yonghong Tian
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking Transformers, which combine the scalability of Transformers with the sparse, energy-efficient property of Spiking Neural Networks (SNNs), have achieved impressive results in neuromorphic and vision tasks and attracted increasing attention. However, existing directly trained spiking transformers primarily focus on vision tasks. For language modeling with spiking transformer, convergence relies heavily on softmax-based spiking self-attention, which incurs high energy costs and poses challenges for neuromorphic deployment. To address this issue, we introduce Winner-Take-All (WTA) mechanisms into spiking transformers and propose two novel softmax-free, spike-driven self-attention modules: WTA Spiking Self-Attention (WSSA) and Causal WTA Spiking Self-Attention (CWSSA). Based on them, we design WTA-based Encoder-only Spiking Transformer (WE-Spikingformer) for masked language modeling and WTA-based Decoder-only Spiking Transformer (WD-Spikingformer) for causal language modeling, systematically exploring softmax-free, spiking-driven Transformer architectures trained end-to-end for natural language processing tasks. Extensive experiments on 16 datasets spanning natural language understanding, question-answering tasks, and commonsense reasoning tasks validate the effectiveness of our approach and highlight the promise of spiking transformers for general language modeling and energy-efficient artificial intelligence.
### Title:
          BRIDGE and TCH-Net: Heterogeneous Benchmark and Multi-Branch Baseline for Cross-Domain IoT Botnet Detection
 - **Authors:** Ammar Bhilwarawala, Likhamba Rongmei, Harsh Sharma, Arya Jena, Kaushal Singh, Jayashree Piri, Raghunath Dey
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 IoT botnet detection has advanced, yet most published systems are validated on a single dataset and rarely generalise across environments. Heterogeneous feature spaces make multi-dataset training practically impossible without discarding semantic interpretability or introducing data integrity violations. No prior work has addressed both problems with a formally specified, reproducible methodology. This paper does. We introduce BRIDGE (Benchmark Reference for IoT Domain Generalisation Evaluation), the first formally specified heterogeneous multi-dataset benchmark for IoT intrusion detection, unifying CICIDS-2017, CIC-IoT-2023, Bot-IoT, Edge-IIoTset, and N-BaIoT through a 46-feature semantic canonical vocabulary grounded in CICFlowMeter nomenclature, with genuine-equivalence-only feature mapping, explicit zero-filling, and per-dataset coverage from 15% to 93%. A leave-one-dataset-out (LODO) protocol makes the generalisation gap precisely measurable: all five evaluated architectures achieve mean LODO F1 between 0.39 and 0.47, and we establish the first community generalisation baseline at mean LODO F1 = 0.5577, a result that shifts the agenda from single-benchmark optimisation toward cross-environment generalisation. We propose TCH-Net, a multi-branch network fusing a three-path Temporal branch (residual convolutional-BiGRU, stride-downsampled BiGRU, pre-LayerNorm Transformer), a provenance-conditioned Contextual branch, and a Statistical branch via Cross-Branch Gated Attention Fusion (CB-GAF) with learnable sigmoid gates for dynamic feature-wise mixing. Across five random seeds, TCH-Net achieves F1 = 0.8296 +/- 0.0028, AUC = 0.9380 +/- 0.0025, and MCC = 0.6972 +/- 0.0056, outperforming all twelve baselines (p < 0.05, Wilcoxon) and recording the highest LODO F1 overall. BRIDGE and the full pipeline are at this https URL.
### Title:
          Any 3D Scene is Worth 1K Tokens: 3D-Grounded Representation for Scene Generation at Scale
 - **Authors:** Dongxu Wei, Qi Xu, Zhiqi Li, Hangning Zhou, Cong Qiu, Hailong Qin, Mu Yang, Zhaopeng Cui, Peidong Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computational Geometry (cs.CG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D scene generation has long been dominated by 2D multi-view or video diffusion models. This is due not only to the lack of scene-level 3D latent representation, but also to the fact that most scene-level 3D visual data exists in the form of multi-view images or videos, which are naturally compatible with 2D diffusion architectures. Typically, these 2D-based approaches degrade 3D spatial extrapolation to 2D temporal extension, which introduces two fundamental issues: (i) representing 3D scenes via 2D views leads to significant representation redundancy, and (ii) latent space rooted in 2D inherently limits the spatial consistency of the generated 3D scenes. In this paper, we propose, for the first time, to perform 3D scene generation directly within an implicit 3D latent space to address these limitations. First, we repurpose frozen 2D representation encoders to construct our 3D Representation Autoencoder (3DRAE), which grounds view-coupled 2D semantic representations into a view-decoupled 3D latent representation. This enables representing 3D scenes observed from arbitrary numbers of views--at any resolution and aspect ratio--with fixed complexity and rich semantics. Then we introduce 3D Diffusion Transformer (3DDiT), which performs diffusion modeling in this 3D latent space, achieving remarkably efficient and spatially consistent 3D scene generation while supporting diverse conditioning configurations. Moreover, since our approach directly generates a 3D scene representation, it can be decoded to images and optional point maps along arbitrary camera trajectories without requiring per-trajectory diffusion sampling pass, which is common in 2D-based approaches.
### Title:
          LoGo-MR: Screening Breast MRI for Cancer Risk Prediction by Efficient Omni-Slice Modeling
 - **Authors:** Xin Wang, Yuan Gao, George Yiasemis, Antonio Portaluri, Zahra Aghdam, Muzhen He, Luyi Han, Yaofei Duan, Chunyao Lu, Xinglong Liang, Tianyu Zhang, Vivien van Veldhuizen, Yue Sun, Tao Tan, Ritse Mann, Jonas Teuwen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient and explainable breast cancer (BC) risk prediction is critical for large-scale population-based screening. Breast MRI provides functional information for personalized risk assessment. Yet effective modeling remains challenging as fully 3D CNNs capture volumetric context at high computational cost, whereas lightweight 2D CNNs fail to model inter-slice continuity. Importantly, breast MRI modeling for shor- and long-term BC risk stratification remains underexplored. In this study, we propose LoGo-MR, a 2.5D local-global structural modeling framework for five-year BC risk prediction. Aligned with clinical interpretation, our framework first employs neighbor-slice encoding to capture subtle local cues linked to short-term risk. It then integrates transformer-enhanced multiple-instance learning (MIL) to model distributed global patterns related to long-term risk and provide interpretable slice importance. We further apply this framework across axial, sagittal, and coronal planes as LoGo3-MR to capture complementary volumetric information. This multi-plane formulation enables voxel-level risk saliency mapping, which may assist radiologists in localizing risk-relevant regions during breast MRI interpretation. Evaluated on a large breast MRI screening cohort (~7.5K), our method outperforms 2D/3D baselines and existing SOTA MIL methods, achieving AUCs of 0.77-0.69 for 1- to 5-year prediction and improving C-index by ~6% over 3D CNNs. LoGo3-MR further improves overall performance with interpretable localization across three planes, and validation across seven backbones shows consistent gains. These results highlight the clinical potential of efficient MRI-based BC risk stratification for large-scale screening. Code will be released publicly.
### Title:
          Beyond Reconstruction: Reconstruction-to-Vector Diffusion for Hyperspectral Anomaly Detection
 - **Authors:** Jijun Xiang, Jiayi Wang, Pengxiang Wang, Cheng Chen, Nian Wang, Tao Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Hyperspectral Anomaly Detection (HAD) excels at identifying sparse targets in complex scenes, existing models remain trapped in a scalar "reconstruction-as-endpoint" paradigm. This reliance on ambiguous scalar residuals consistently triggers sub-pixel anomaly vanishing during spatial downsampling, alongside severe confirmation bias when unpurified anomalies corrupt training weights. In this paper, we propose Reconstruction-to-Vector Diffusion (R2VD), which fundamentally redefines reconstruction as a manifold purification origin to establish a novel residual-guided generative dynamics paradigm. Our framework introduces a four-stage pipeline: (1) a Physical Prior Extraction (PPE) stage that mitigates early confirmation bias via dual-stream statistical guidance; (2) a Guided Manifold Purification (GMP) stage utilizing an OmniContext Autoencoder (OCA) to extract purified residual maps while preserving fragile sub-pixel topologies; (3) a Residual Score Modeling (RSM) stage where a Diffusion Transformer (DiT), guarded by a Physical Spectral Firewall (PSF), effectively isolates cross-spectral leakage; and (4) a Vector Dynamics Inference (VDI) stage that robustly decouples targets from backgrounds by evaluating high-dimensional vector interference patterns instead of conventional scalar errors. Comprehensive evaluations on eight datasets confirm that R2VD establishes a new state-of-the-art, delivering exceptional target detectability and background suppression.
### Title:
          Optimizing IoT Intrusion Detection with Tabular Foundation Models for Smart City Forensics
 - **Authors:** Asma Al-Dahmani, Abdulla Bin Safwan, Mohammad Obeidat, Belal Alsinglawi
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Security operations in smart cities demand detection systems that balance accuracy with response time. While ensemble methods like Random Forest achieve high accuracy, their computational overhead impedes real-time forensic triage. We present the first systematic evaluation of TabPFNv2.5, a transformer-based foundation model, against traditional ensemble classifiers for IoT intrusion detection. Using the TON IoT dataset, we demonstrate that TabPFNv2.5 achieves 40 faster inference than Random Forest while maintaining 97% binary classification accuracy. We propose a hybrid pipeline in which TabPFNv2.5 performs rapid threat screening, while ensemble models handle detailed classification. Our analysis reveals that scanning attacks remain the hardest to detect (F1: 69.8%) and cross-device generalization depends critically on feature similarity. These findings establish foundation models as viable components for time-sensitive IoT security operations
### Title:
          One Scale at a Time: Scale-Autoregressive Modeling for Fluid Flow Distributions
 - **Authors:** Mario Lino, Nils Thuerey
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE); Artificial Intelligence (cs.AI); Fluid Dynamics (physics.flu-dyn)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Analyzing unsteady fluid flows often requires access to the full distribution of possible temporal states, yet conventional PDE solvers are computationally prohibitive and learned time-stepping surrogates quickly accumulate error over long rollouts. Generative models avoid compounding error by sampling states independently, but diffusion and flow-matching methods, while accurate, are limited by the cost of many evaluations over the entire mesh. We introduce scale-autoregressive modeling (SAR) for sampling flows on unstructured meshes hierarchically from coarse to fine: it first generates a low-resolution field, then refines it by progressively sampling higher resolutions conditioned on coarser predictions. This coarse-to-fine factorization improves efficiency by concentrating computation at coarser scales, where uncertainty is greatest, while requiring fewer steps at finer scales. Across unsteady-flow benchmarks of varying complexity, SAR attains substantially lower distributional error and higher per-sample accuracy than state-of-the-art diffusion models based on multi-scale GNNs, while matching or surpassing a flow-matching Transolver (a linear-time transformer) yet running 2-7x faster than this depending on the task. Overall, SAR provides a practical tool for fast and accurate estimation of statistical flow quantities (e.g., turbulent kinetic energy and two-point correlations) in real-world settings.
### Title:
          Efficient Emotion-Aware Iconic Gesture Prediction for Robot Co-Speech
 - **Authors:** Edwin C. Montiel-Vazquez, Christian Arzate Cruz, Stefanos Gkikas, Thomas Kassiotis, Giorgos Giannakakis, Randy Gomez
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Co-speech gestures increase engagement and improve speech understanding. Most data-driven robot systems generate rhythmic beat-like motion, yet few integrate semantic emphasis. To address this, we propose a lightweight transformer that derives iconic gesture placement and intensity from text and emotion alone, requiring no audio input at inference time. The model outperforms GPT-4o in both semantic gesture placement classification and intensity regression on the BEAT2 dataset, while remaining computationally compact and suitable for real-time deployment on embodied agents.
### Title:
          Revisiting Compositionality in Dual-Encoder Vision-Language Models: The Role of Inference
 - **Authors:** Imanol Miranda, Ander Salaberria, Eneko Agirre, Gorka Azkune
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dual-encoder Vision-Language Models (VLMs) such as CLIP are often characterized as bag-of-words systems due to their poor performance on compositional benchmarks. We argue that this limitation may stem less from deficient representations than from the standard inference protocol based on global cosine similarity. First, through controlled diagnostic experiments, we show that explicitly enforcing fine-grained region-segment alignment at inference dramatically improves compositional performance without updating pretrained encoders. We then introduce a lightweight transformer that learns such alignments directly from frozen patch and token embeddings. Comparing against full fine-tuning and prior end-to-end compositional training methods, we find that although these approaches improve in-domain retrieval, their gains do not consistently transfer under distribution shift. In contrast, learning localized alignment over frozen representations matches full fine-tuning on in-domain retrieval while yielding substantial improvements on controlled out-of-domain compositional benchmarks. These results identify global embedding matching as a key bottleneck in dual-encoder VLMs and highlight the importance of alignment mechanisms for robust compositional generalization.
### Title:
          TAG-Head: Time-Aligned Graph Head for Plug-and-Play Fine-grained Action Recognition
 - **Authors:** Imtiaz Ul Hassan, Nik Bessis, Ardhendu Behera
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-grained human action recognition (FHAR) is challenging because visually similar actions differ by subtle spatio-temporal cues. Many recent systems enhance discriminability with extra modalities (e.g., pose, text, optical flow), but this increases annotation burden and computational cost. We introduce TAG-Head, a lightweight spatio-temporal graph head that upgrades standard 3D backbones (SlowFast, R(2+1)D-34, I3D, etc.) for FHAR using RGB only. Our pipeline first applies a Transformer encoder with learnable 3D positional encodings to the backbone tokens, capturing long-range dependencies across space and time. The resulting features are then refined by a graph in which (i) fully-connected intra-frame edges to resolve subtle appearance differences within frames, and (ii) time-aligned temporal edges that connect features at the same spatial location across frames to stabilise motion cues without over-smoothing. The head is compact (little parameter/FLOP overhead), plug-and-play across backbones, and trained end-to-end with the backbone. Extensive evaluations on FineGym (Gym99 and Gym288) and HAA500 show that TAG-Head sets a new state-of-the-art among RGB-only models and surpasses many recent multimodal approaches (video + pose + text) that rely on privileged information. Ablations disentangle the contributions of the Transformer and the graph topology, and complexity analyses confirm low latency. TAG-Head advances FHAR by explicitly coupling global context with high-resolution spatial interactions and low-variance temporal continuity inside a slim, composable graph head. The simplicity of the design enables straightforward adoption in practical systems that favour RGB-only sensors, while delivering performance gains typically associated with heavier or multimodal models. Code will be released on GitHub.
### Title:
          Quantization Dominates Rank Reduction for KV-Cache Compression
 - **Authors:** Samuel Salfati
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We compare two strategies for compressing the KV cache in transformer inference: rank reduction (discard dimensions) and quantization (keep all dimensions, reduce precision). At matched storage budgets across five models (124M-14B, MHA and GQA), we find that quantization consistently outperforms rank reduction by 4-364 PPL depending on model and compression level. The gap persists even when rank reduction is combined with quantization in hybrid baselines, and it grows with GQA aggressiveness. On LAMBADA, INT4 matches FP16 accuracy (+0.23 PPL on Mistral 7B, +0.58 on GPT-2) while rank-32 at identical storage collapses to 0.4%. We trace this gap to a structural asymmetry: under softmax attention routing, removing a dimension can flip which token is attended (a discrete failure), while quantization noise is bounded and typically preserves score ordering. We formalize this via a perturbation result showing projection damage exceeds quantization damage by 3 x 2^(2b) per direction under the softmax Fisher metric. A basis ablation confirms the finding is basis-independent (spread <0.4 PPL), establishing that the advantage comes from preserving dimensions, not from a better coordinate system. Joint K+V INT4 quantization achieves 75% total KV reduction at only +0.18 PPL on Mistral 7B.
### Title:
          Training-Free Model Ensemble for Single-Image Super-Resolution via Strong-Branch Compensation
 - **Authors:** Gengjia Chang, Xining Ge, Weijun Yuan, Zhan Li, Qiurong Song, Luen Zhu, Shuhong Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Single-image super-resolution has progressed from deep convolutional baselines to stronger Transformer and state-space architectures, yet the corresponding performance gains typically come with higher training cost, longer engineering iteration, and heavier deployment burden. In many practical settings, multiple pretrained models with partially complementary behaviors are already available, and the binding constraint is no longer architectural capacity but how effectively their outputs can be combined without additional training. Rather than pursuing further architectural redesign, this paper proposes a training-free output-level ensemble framework. A dual-branch pipeline is constructed in which a Hybrid attention network with TLC inference provides stable main reconstruction, while a MambaIRv2 branch with geometric self-ensemble supplies strong compensation for high-frequency detail recovery. The two branches process the same low-resolution input independently and are fused in the image space via a lightweight weighted combination, without updating any model parameters or introducing an additional trainable module. As our solution to the NTIRE 2026 Image Super-Resolution ($\times 4$) Challenge, the proposed design consistently improves over the base branch and slightly exceeds the pure strong branch in PSNR at the best operating point under a unified DIV2K bicubic $\times 4$ evaluation protocol. Ablation studies confirm that output-level compensation provides a low-overhead and practically accessible upgrade path for existing super-resolution systems.
### Title:
          Layerwise Dynamics for In-Context Classification in Transformers
 - **Authors:** Patrick Lutz, Themistoklis Haris, Arjun Chandra, Aditya Gangrade, Venkatesh Saligrama
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers can perform in-context classification from a few labeled examples, yet the inference-time algorithm remains opaque. We study multi-class linear classification in the hard no-margin regime and make the computation identifiable by enforcing feature- and label-permutation equivariance at every layer. This enables interpretability while maintaining functional equivalence and yields highly structured weights. From these models we extract an explicit depth-indexed recursion: an end-to-end identified, emergent update rule inside a softmax transformer, to our knowledge the first of its kind. Attention matrices formed from mixed feature-label Gram structure drive coupled updates of training points, labels, and the test probe. The resulting dynamics implement a geometry-driven algorithmic motif, which can provably amplify class separation and yields robust expected class alignment.
### Title:
          Predicting User Satisfaction in Online Education Platforms: A Large Language Model Based Multi-Modal Review Mining Framework
 - **Authors:** Arman Bekov, Azamat Nurgali
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online education platforms have experienced explosive growth over the past decade, generating massive volumes of user-generated content in the form of reviews, ratings, and behavioral logs. These heterogeneous signals provide unprecedented opportunities for understanding learner satisfaction, which is a critical determinant of course retention, engagement, and long-term learning outcomes. However, accurately predicting satisfaction remains challenging due to the short length, noise, contextual dependency, and multi-dimensional nature of online reviews. In this paper, we propose a unified \textbf{Large Language Model (LLM)-based multi-modal framework} for predicting both platform-level and course-level learner satisfaction. The proposed framework integrates three complementary information sources: (1) short-text topic distributions that capture latent thematic structures, (2) contextualized sentiment representations learned from pretrained Transformer-based language models, and (3) behavioral interaction features derived from learner activity logs. These heterogeneous representations are fused within a hybrid regression architecture to produce accurate satisfaction predictions. We conduct extensive experiments on large-scale MOOC review datasets collected from multiple public platforms. The experimental results demonstrate that the proposed LLM-based multi-modal framework consistently outperforms traditional text-only models, shallow sentiment baselines, and single-modality regression approaches. Comprehensive ablation studies further validate the necessity of jointly modeling topic semantics, deep sentiment representations, and behavioral analytics. Our findings highlight the critical role of large-scale contextual language representations in advancing learning analytics and provide actionable insights for platform design, course improvement, and personalized recommendation.
### Title:
          A Synthetic Conversational Smishing Dataset for Social Engineering Detection
 - **Authors:** Carl Lochstampfor, Ayan Roy
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Smishing (SMS phishing) has become a serious cybersecurity threat, especially for elderly and cyber-unaware individuals, causing financial loss and undermining user trust. Although prior work has focused on detecting smishing at the level of individual messages, real-world attackers often rely on multi-stage social engineering, gradually manipulating victims through extended conversations before attempting to steal sensitive information. Despite the existence of several datasets for single-message smishing detection, datasets capturing conversational smishing remain largely unavailable, limiting research on multi-turn attack detection. To address this gap, this paper presents a synthetically generated dataset of 3,201 labeled multi-round conversations designed to emulate realistic conversational smishing attacks. The dataset reflects diverse attacker strategies and victim responses across multiple stages of interaction. Using this dataset, we establish baseline performance by evaluating eight models, including traditional machine learning approaches (Logistic Regression, Random Forest, Linear SVM, and XGBoost) and transformer-based architectures (DistilBERT and Longformer), with both engineered conversational features and TF-IDF text representations. Experimental results show that TF-IDF-based models consistently outperform those using engineered features alone. The best-performing model, XGBoost with TF-IDF features, achieves 72.5% accuracy and a macro F1 score of 0.691, surpassing both transformer models. Our analysis suggests that transformer performance is limited primarily by input-length constraints and the relatively small size of the training data. Overall, the results highlight the value of lexical signals in conversational smishing detection and demonstrate the usefulness of the proposed dataset for advancing research on defenses against multi-turn social engineering attacks.
## Keyword: autonomous driving
### Title:
          Hardware Utilization and Inference Performance of Edge Object Detection Under Fault Injection
 - **Authors:** Faezeh Pasandideh, Mehdi Azarafza, Achim Rettberg
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As deep learning models are deployed on resource constrained edge platforms in autonomous driving systems, reli able knowledge of hardware behavior under resource degradation becomes an essential requirement. Therefore, we introduce a systematic characterization of CPU load, GPU utilization, RAM consumption, power draw, throughput, and thermal behaviour of TensorRT-optimized YOLOv10s, YOLOv11s and YOLO2026n pipelines running on NVIDIA Jetson Nano under a large-scale fault injection campaign targeting both lane-following and ob ject detection tasks. Faults are synthesized using a decoupled framework that leverages large language models (LLMs) and latent diffusion models (LDMs), based on original data from our JetBot platform data collection. Results show that across both tasks and both models the inference engines keep GPU occupancy stable, temperature rise under control, and power consumption within safe limits, while memory usage settles into a consistent release pattern after the initial warm-up phase. Object detection tends to show somewhat more variability in memory and thermal behavior, yet both tasks point to the same conclusion: the TensorRT pipelines hold up well even when the input data is heavily degraded. These findings offer a hardware-level view of model reliability that sits alongside, rather than against, the broader body of work focused on inference performance at the edge.
### Title:
          MAVEN-T: Multi-Agent enVironment-aware Enhanced Neural Trajectory predictor with Reinforcement Learning
 - **Authors:** Wenchang Duan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Trajectory prediction remains a critical yet challenging component in autonomous driving systems, requiring sophisticated reasoning capabilities while meeting strict real-time deployment constraints. While knowledge distillation has demonstrated effectiveness in model compression, existing approaches often fail to preserve complex decision-making capabilities, particularly in dynamic multi-agent scenarios. This paper introduces MAVEN-T, a teacher-student framework that achieves state-of-the-art trajectory prediction through complementary architectural co-design and progressive distillation. The teacher employs hybrid attention mechanisms for maximum representational capacity, while the student uses efficient architectures optimized for deployment. Knowledge transfer is performed via multi-granular distillation with adaptive curriculum learning that dynamically adjusts complexity based on performance. Importantly, the framework incorporates reinforcement learning to overcome the imitation ceiling of traditional distillation, enabling the student to verify, refine, and optimize teacher knowledge through dynamic environmental interaction, potentially achieving more robust decision-making than the teacher itself. Extensive experiments on NGSIM and highD datasets demonstrate 6.2x parameter compression and 3.7x inference speedup while maintaining state-of-the-art accuracy, establishing a new paradigm for deploying sophisticated reasoning models under resource constraints.
### Title:
          SignReasoner: Compositional Reasoning for Complex Traffic Sign Understanding via Functional Structure Units
 - **Authors:** Ruibin Wang, Zhenyu Lin, Xinhai Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate semantic understanding of complex traffic signs-including those with intricate layouts, multi-lingual text, and composite symbols-is critical for autonomous driving safety. Current models, both specialized small ones and large Vision Language Models (VLMs), suffer from a significant bottleneck: a lack of compositional generalization, leading to failure when encountering novel sign configurations. To overcome this, we propose SignReasoner, a novel paradigm that transforms general VLMs into expert traffic sign reasoners. Our core innovation is Functional Structure Unit (FSU), which shifts from common instance-based modeling to flexible function-based decomposition. By breaking down complex signs into minimal, core functional blocks (e.g., Direction, Notice, Lane), our model learns the underlying structural grammar, enabling robust generalization to unseen compositions. We define this decomposition as the FSU-Reasoning task and introduce a two-stage VLM post-training pipeline to maximize performance: Iterative Caption-FSU Distillation that enhances the model's accuracy in both FSU-reasoning and caption generation; FSU-GRPO that uses Tree Edit Distance (TED) to compute FSU differences as the rewards in GRPO algorithm, boosting reasoning abilities. Experiments on the newly proposed FSU-Reasoning benchmark, TrafficSignEval, show that SignReasoner achieves new SOTA with remarkable data efficiency and no architectural modification, significantly improving the traffic sign understanding in various VLMs.
### Title:
          Energy-Efficient Federated Edge Learning For Small-Scale Datasets in Large IoT Networks
 - **Authors:** Haihui Xie, Wenkun Wen, Shuwu Chen, Zhaogang Shu, Minghua Xia
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale Internet of Things (IoT) networks enable intelligent services such as smart cities and autonomous driving, but often face resource constraints. Collecting heterogeneous sensory data, especially in small-scale datasets, is challenging, and independent edge nodes can lead to inefficient resource utilization and reduced learning performance. To address these issues, this paper proposes a collaborative optimization framework for energy-efficient federated edge learning with small-scale datasets. We first derive an expected learning loss to quantify the relationship between the number of training samples and learning objectives. A stochastic online learning algorithm is then designed to adapt to data variations, and a resource optimization problem with a convergence bound is formulated. Finally, an online distributed algorithm efficiently solves large-scale optimization problems with high scalability. Extensive simulations and autonomous navigation case studies with collision avoidance demonstrate that the proposed approach significantly improves learning performance and resource efficiency compared to state-of-the-art benchmarks.
### Title:
          LIDARLearn: A Unified Deep Learning Library for 3D Point Cloud Classification, Segmentation, and Self-Supervised Representation Learning
 - **Authors:** Said Ohamouddou, Hanaa El Afia, Abdellatif El Afia, Raddouane Chiheb
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Three-dimensional (3D) point cloud analysis has become central to applications ranging from autonomous driving and robotics to forestry and ecological monitoring. Although numerous deep learning methods have been proposed for point cloud understanding, including supervised backbones, self-supervised pre-training (SSL), and parameter-efficient fine-tuning (PEFT), their implementations are scattered across incompatible codebases with differing data pipelines, evaluation protocols, and configuration formats, making fair comparisons difficult. We introduce \lib{}, a unified, extensible PyTorch library that integrates over 55 model configurations covering 29 supervised architectures, seven SSL pre-training methods, and five PEFT strategies, all within a single registry-based framework supporting classification, semantic segmentation, part segmentation, and few-shot learning. \lib{} provides standardised training runners, cross-validation with stratified $K$-fold splitting, automated LaTeX/CSV table generation, built-in Friedman/Nemenyi statistical testing with critical-difference diagrams for rigorous multi-model comparison, and a comprehensive test suite with 2\,200+ automated tests validating every configuration end-to-end. The code is available at this https URL under the MIT licence.
### Title:
          MapATM: Enhancing HD Map Construction through Actor Trajectory Modeling
 - **Authors:** Mingyang Li, Brian Lee, Rui Zuo, Brent Bacchus, Priyantha Mudalige, Qinru Qiu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-definition (HD) mapping tasks, which perform lane detections and predictions, are extremely challenging due to non-ideal conditions such as view occlusions, distant lane visibility, and adverse weather conditions. Those conditions often result in compromised lane detection accuracy and reduced reliability within autonomous driving systems. To address these challenges, we introduce MapATM, a novel deep neural network that effectively leverages historical actor trajectory information to improve lane detection accuracy, where actors refer to moving vehicles. By utilizing actor trajectories as structural priors for road geometry, MapATM achieves substantial performance enhancements, notably increasing AP by 4.6 for lane dividers and mAP by 2.6 on the challenging NuScenes dataset, representing relative improvements of 10.1% and 6.1%, respectively, compared to strong baseline methods. Extensive qualitative evaluations further demonstrate MapATM's capability to consistently maintain stable and robust map reconstruction across diverse and complex driving scenarios, underscoring its practical value for autonomous driving applications.
### Title:
          OpenDT: Exploring Datacenter Performance and Sustainability with a Self-Calibrating Digital Twin
 - **Authors:** Radu Nicolae, Jules van der Toorn, Stavriana Kraniti, Houcen Liu, Alexandru Iosup
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Datacenters are the backbone of our digital society, but raise numerous operational challenges. We envision digital twins becoming primary instruments in datacenter operations, continuously and autonomously helping with major operational decisions and with adapting ICT infrastructure, live, with a human-in-the-loop. Although fields such as aviation and autonomous driving successfully employ digital twins, an open-source digital twin for datacenters has not been demonstrated to the community. Addressing this challenge, we design, implement, and experiment using OpenDT, an Open-source, Digital Twin for monitoring and operating datacenters through a continuous integration cycle that includes: (1) live and continuous telemetry data; (2) discrete-event simulation using live telemetry from the physical ICT, with self-calibration; and (3) SLO-aware and human-approved feedback to physical ICT. Through trace-driven experiments with a prototype mainly covering stages 1 and 2 of the cycle, we show that (i) OpenDT can be used to reproduce peer-reviewed experiments and extend the analysis with performance and energy-efficiency results; (ii) OpenDT's online re-calibration can increase digital-twinning accuracy, quantified to a MAPE of 4.39% vs. 7.86% in peer-reviewed work. OpenDT adheres to FAIR/FOSS principles and is available at: this https URL.
### Title:
          Representations Before Pixels: Semantics-Guided Hierarchical Video Prediction
 - **Authors:** Efstathios Karypidis, Spyros Gidaris, Nikos Komodakis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate future video prediction requires both high visual fidelity and consistent scene semantics, particularly in complex dynamic environments such as autonomous driving. We present Re2Pix, a hierarchical video prediction framework that decomposes forecasting into two stages: semantic representation prediction and representation-guided visual synthesis. Instead of directly predicting future RGB frames, our approach first forecasts future scene structure in the feature space of a frozen vision foundation model, and then conditions a latent diffusion model on these predicted representations to render photorealistic frames. This decomposition enables the model to focus first on scene dynamics and then on appearance generation. A key challenge arises from the train-test mismatch between ground-truth representations available during training and predicted ones used at inference. To address this, we introduce two conditioning strategies, nested dropout and mixed supervision, that improve robustness to imperfect autoregressive predictions. Experiments on challenging driving benchmarks demonstrate that the proposed semantics-first design significantly improves temporal semantic consistency, perceptual quality, and training efficiency compared to strong diffusion baselines. We provide the implementation code at this https URL
