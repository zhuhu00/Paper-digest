# Showing new listings for Friday, 13 March 2026
## Keyword: SLAM
### Title:
          Edge-Assisted Multi-Robot Visual-Inertial SLAM with Efficient Communication
 - **Authors:** Xin Liu, Shuhuan Wen, Jing Zhao, Tony Z. Qiu, Hong Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The integration of cloud computing and edge computing is an effective way to achieve global consistent and real-time multi-robot Simultaneous Localization and Mapping (SLAM). Cloud computing effectively solves the problem of limited computing, communication and storage capacity of terminal equipment. However, limited bandwidth and extremely long communication links between terminal devices and the cloud result in serious performance degradation of multi-robot SLAM systems. To reduce the computational cost of feature tracking and improve the real-time performance of the robot, a lightweight SLAM method of optical flow tracking based on pyramid IMU prediction is proposed. On this basis, a centralized multi-robot SLAM system based on a robot-edge-cloud layered architecture is proposed to realize real-time collaborative SLAM. It avoids the problems of limited on-board computing resources and low execution efficiency of single robot. In this framework, only the feature points and keyframe descriptors are transmitted and lossless encoding and compression are carried out to realize real-time remote information transmission with limited bandwidth resources. This design reduces the actual bandwidth occupied in the process of data transmission, and does not cause the loss of SLAM accuracy caused by data compression. Through experimental verification on the EuRoC dataset, compared with the current most advanced local feature compression method, our method can achieve lower data volume feature transmission, and compared with the current advanced centralized multi-robot SLAM scheme, it can achieve the same or better positioning accuracy under low computational load.
### Title:
          MirrorDrift: Actuated Mirror-Based Attacks on LiDAR SLAM
 - **Authors:** Rokuto Nagata, Kenji Koide, Kazuma Ikeda, Ozora Sako, Shion Horie, Kentaro Yoshioka
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR SLAM provides high-accuracy localization but is fragile to point-cloud corruption because scan matching assumes geometric consistency. Prior physical attacks on LiDAR SLAM largely rely on LiDAR spoofing via external signal injection, which requires sensor-specific timing knowledge and is increasingly mitigated by modern defense mechanisms such as timing obfuscation and injection rejection. In this work, we show that specular reflection offers an injection-free alternative and demonstrate an attack, MirrorDrift, that uses an actuated planar mirror to cause ghost points in LiDAR scans and systematically bias scan-matching correspondences. MirrorDrift optimizes mirror placement, alignment, and actuation. In simulation, it increases the average pose error (APE) by 6.1x over random placement, degrading three SLAM systems to 2.29-3.31 m mean APE. In real-world experiments on a modern LiDAR with state-of-the-art interference mitigation, it induces localization errors of up to 6.03 m. To the best of our knowledge, this is the first successful SLAM-targeted attack against production-grade secure LiDARs.
### Title:
          D-SLAMSpoof: An Environment-Agnostic LiDAR Spoofing Attack using Dynamic Point Cloud Injection
 - **Authors:** Rokuto Nagata, Kenji Koide, Kazuma Ikeda, Ozora Sako, Kentaro Yoshioka
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we introduce Dynamic SLAMSpoof (D-SLAMSpoof), a novel attack that compromises LiDAR SLAM even in feature-rich environments. The attack leverages LiDAR spoofing, which injects spurious measurements into LiDAR scans through external laser interference. By designing both spatial injection shapes and temporally coordinated dynamic injection patterns guided by scan-matching principles, D-SLAMSpoof significantly improves attack success rates in real-world, feature-rich environments such as urban areas and indoor spaces, where conventional LiDAR spoofing methods often fail. Furthermore, we propose a practical defense method, ISD-SLAM, that relies solely on inertial dead reckoning signals commonly available in autonomous systems. We demonstrate that ISD-SLAM accurately detects LiDAR spoofing attacks, including D-SLAMSpoof, and effectively mitigates the resulting position drift. Our findings expose inherent vulnerabilities in LiDAR-based SLAM and introduce the first practical defense against LiDAR-based SLAM spoofing using only standard onboard sensors, providing critical insights for improving the security and reliability of autonomous systems.
### Title:
          Dense Dynamic Scene Reconstruction and Camera Pose Estimation from Multi-View Videos
 - **Authors:** Shuo Sun, Unal Artan, Malcolm Mielle, Achim J. Lilienthaland, Martin Magnusson
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We address the challenging problem of dense dynamic scene reconstruction and camera pose estimation from multiple freely moving cameras -- a setting that arises naturally when multiple observers capture a shared event. Prior approaches either handle only single-camera input or require rigidly mounted, pre-calibrated camera rigs, limiting their practical applicability. We propose a two-stage optimization framework that decouples the task into robust camera tracking and dense depth refinement. In the first stage, we extend single-camera visual SLAM to the multi-camera setting by constructing a spatiotemporal connection graph that exploits both intra-camera temporal continuity and inter-camera spatial overlap, enabling consistent scale and robust tracking. To ensure robustness under limited overlap, we introduce a wide-baseline initialization strategy using feed-forward reconstruction models. In the second stage, we refine depth and camera poses by optimizing dense inter- and intra-camera consistency using wide-baseline optical flow. Additionally, we introduce MultiCamRobolab, a new real-world dataset with ground-truth poses from a motion capture system. Finally, we demonstrate that our method significantly outperforms state-of-the-art feed-forward models on both synthetic and real-world benchmarks, while requiring less memory.
## Keyword: odometry
There is no result 
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Radiometric fingerprinting of object surfaces using mobile laser scanning and semantic 3D road space models
 - **Authors:** Benedikt Schwab, Thomas H. Kolbe
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although semantic 3D city models are internationally available and becoming increasingly detailed, the incorporation of material information remains largely untapped. However, a structured representation of materials and their physical properties could substantially broaden the application spectrum and analytical capabilities for urban digital twins. At the same time, the growing number of repeated mobile laser scans of cities and their street spaces yields a wealth of observations influenced by the material characteristics of the corresponding surfaces. To leverage this information, we propose radiometric fingerprints of object surfaces by grouping LiDAR observations reflected from the same semantic object under varying distances, incident angles, environmental conditions, sensors, and scanning campaigns. Our study demonstrates how 312.4 million individual beams acquired across four campaigns using five LiDAR sensors on the Audi Autonomous Driving Dataset (A2D2) vehicle can be automatically associated with 6368 individual objects of the semantic 3D city model. The model comprises a comprehensive and semantic representation of four inner-city streets at Level of Detail (LOD) 3 with centimeter-level accuracy. It is based on the CityGML 3.0 standard and enables fine-grained sub-differentiation of objects. The extracted radiometric fingerprints for object surfaces reveal recurring intra-class patterns that indicate class-dominant materials. The semantic model, the method implementations, and the developed geodatabase solution 3DSensorDB are released under: this https URL
### Title:
          MirrorDrift: Actuated Mirror-Based Attacks on LiDAR SLAM
 - **Authors:** Rokuto Nagata, Kenji Koide, Kazuma Ikeda, Ozora Sako, Shion Horie, Kentaro Yoshioka
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR SLAM provides high-accuracy localization but is fragile to point-cloud corruption because scan matching assumes geometric consistency. Prior physical attacks on LiDAR SLAM largely rely on LiDAR spoofing via external signal injection, which requires sensor-specific timing knowledge and is increasingly mitigated by modern defense mechanisms such as timing obfuscation and injection rejection. In this work, we show that specular reflection offers an injection-free alternative and demonstrate an attack, MirrorDrift, that uses an actuated planar mirror to cause ghost points in LiDAR scans and systematically bias scan-matching correspondences. MirrorDrift optimizes mirror placement, alignment, and actuation. In simulation, it increases the average pose error (APE) by 6.1x over random placement, degrading three SLAM systems to 2.29-3.31 m mean APE. In real-world experiments on a modern LiDAR with state-of-the-art interference mitigation, it induces localization errors of up to 6.03 m. To the best of our knowledge, this is the first successful SLAM-targeted attack against production-grade secure LiDARs.
### Title:
          D-SLAMSpoof: An Environment-Agnostic LiDAR Spoofing Attack using Dynamic Point Cloud Injection
 - **Authors:** Rokuto Nagata, Kenji Koide, Kazuma Ikeda, Ozora Sako, Kentaro Yoshioka
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we introduce Dynamic SLAMSpoof (D-SLAMSpoof), a novel attack that compromises LiDAR SLAM even in feature-rich environments. The attack leverages LiDAR spoofing, which injects spurious measurements into LiDAR scans through external laser interference. By designing both spatial injection shapes and temporally coordinated dynamic injection patterns guided by scan-matching principles, D-SLAMSpoof significantly improves attack success rates in real-world, feature-rich environments such as urban areas and indoor spaces, where conventional LiDAR spoofing methods often fail. Furthermore, we propose a practical defense method, ISD-SLAM, that relies solely on inertial dead reckoning signals commonly available in autonomous systems. We demonstrate that ISD-SLAM accurately detects LiDAR spoofing attacks, including D-SLAMSpoof, and effectively mitigates the resulting position drift. Our findings expose inherent vulnerabilities in LiDAR-based SLAM and introduce the first practical defense against LiDAR-based SLAM spoofing using only standard onboard sensors, providing critical insights for improving the security and reliability of autonomous systems.
### Title:
          Unsupervised LiDAR-Based Multi-UAV Detection and Tracking Under Extreme Sparsity
 - **Authors:** Nivand Khosravi, Rodrigo Ventura, Meysam Basiri
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Non-repetitive solid-state LiDAR scanning leads to an extremely sparse measurement regime for detecting airborne UAVs: a small quadrotor at 10-25 m typically produces only 1-2 returns per scan, which is far below the point densities assumed by most existing detection approaches and inadequate for robust multi-target data association. We introduce an unsupervised, LiDAR-only pipeline that addresses both detection and tracking without the need for labeled training data. The detector integrates range-adaptive DBSCAN clustering with a three-stage temporal consistency check and is benchmarked on real-world air-to-air flight data under eight different parameter configurations. The best setup attains 0.891 precision, 0.804 recall, and 0.63 m RMSE, and a systematic minPts sweep verifies that most scans contain at most 1-2 target points, directly quantifying the sparsity regime. For multi-target tracking, we compare deterministic Hungarian assignment with joint probabilistic data association (JPDA), each coupled with Interacting Multiple Model filtering, in four simulated scenarios with increasing levels of ambiguity. JPDA cuts identity switches by 64% with negligible impact on MOTA, demonstrating that probabilistic association is advantageous when UAV trajectories approach one another closely. A two-environment evaluation strategy, combining real-world detection with RTK-GPS ground truth and simulation-based tracking with identity-annotated ground truth, overcomes the limitations of GNSS-only evaluation at inter-UAV distances below 2 m.
### Title:
          Decentralized Cooperative Localization for Multi-Robot Systems with Asynchronous Sensor Fusion
 - **Authors:** Nivand Khosravi, Niusha Khosravi, Mohammad Bozorg, Masoud S. Bahraini
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decentralized cooperative localization (DCL) is a promising approach for nonholonomic mobile robots operating in GPS-denied environments with limited communication infrastructure. This paper presents a DCL framework in which each robot performs localization locally using an Extended Kalman Filter, while sharing measurement information during update stages only when communication links are available and companion robots are successfully detected by LiDAR. The framework preserves cross-correlation consistency among robot state estimates while handling asynchronous sensor data with heterogeneous sampling rates and accommodating accelerations during dynamic maneuvers. Unlike methods that require pre-aligned coordinate systems, the proposed approach allows robots to initialize with arbitrary reference-frame orientations and achieves automatic alignment through transformation matrices in both the prediction and update stages. To improve robustness in feature-sparse environments, we introduce a dual-landmark evaluation framework that exploits both static environmental features and mobile robots as dynamic landmarks. The proposed framework enables reliable detection and feature extraction during sharp turns, while prediction accuracy is improved through information sharing from mutual observations. Experimental results in both Gazebo simulation and real-world basement environments show that DCL outperforms centralized cooperative localization (CCL), achieving a 34% reduction in RMSE, while the dual-landmark variant yields an improvement of 56%. These results demonstrate the applicability of DCL to challenging domains such as enclosed spaces, underwater environments, and feature-sparse terrains where conventional localization methods are ineffective.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          Node-RF: Learning Generalized Continuous Space-Time Scene Dynamics with Neural ODE-based NeRFs
 - **Authors:** Hiran Sarkar, Liming Kuang, Yordanka Velikova, Benjamin Busam
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting scene dynamics from visual observations is challenging. Existing methods capture dynamics only within observed boundaries failing to extrapolate far beyond the training sequence. Node-RF (Neural ODE-based NeRF) overcomes this limitation by integrating Neural Ordinary Differential Equations (NODEs) with dynamic Neural Radiance Fields (NeRFs), enabling a continuous-time, spatiotemporal representation that generalizes beyond observed trajectories at constant memory cost. From visual input, Node-RF learns an implicit scene state that evolves over time via an ODE solver, propagating feature embeddings via differential calculus. A NeRF-based renderer interprets calculated embeddings to synthesize arbitrary views for long-range extrapolation. Training on multiple motion sequences with shared dynamics allows for generalization to unseen conditions. Our experiments demonstrate that Node-RF can characterize abstract system behavior without explicit model to identify critical points for future predictions.
## Keyword: mapping
### Title:
          Structure-Aware Epistemic Uncertainty Quantification for Neural Operator PDE Surrogates
 - **Authors:** Haoze Song, Zhihao Li, Mengyi Deng, Xin Li, Duyi Pan, Zhilu Lai, Wei Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators (NOs) provide fast, resolution-invariant surrogates for mapping input fields to PDE solution fields, but their predictions can exhibit significant epistemic uncertainty due to finite data, imperfect optimization, and distribution shift. For practical deployment in scientific computing, uncertainty quantification (UQ) must be both computationally efficient and spatially faithful, i.e., uncertainty bands should align with the localized residual structures that matter for downstream risk management. We propose a structure-aware epistemic UQ scheme that exploits the modular anatomy common to modern NOs (lifting-propagation-recovering). Instead of applying unstructured weight perturbations (e.g., naive dropout) across the entire network, we restrict Monte Carlo sampling to a module-aligned subspace by injecting stochasticity only into the lifting module, and treat the learned solver dynamics (propagation and recovery) as deterministic. We instantiate this principle with two lightweight lifting-level perturbations, including channel-wise multiplicative feature dropout and a Gaussian feature perturbation with matched variance, followed by standard calibration to construct uncertainty bands. Experiments on challenging PDE benchmarks (including discontinuous-coefficient Darcy flow and geometry-shifted 3D car CFD surrogates) demonstrate that the proposed structure-aware design yields more reliable coverage, tighter bands, and improved residual-uncertainty alignment compared with common baselines, while remaining practical in runtime.
### Title:
          Edge-Assisted Multi-Robot Visual-Inertial SLAM with Efficient Communication
 - **Authors:** Xin Liu, Shuhuan Wen, Jing Zhao, Tony Z. Qiu, Hong Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The integration of cloud computing and edge computing is an effective way to achieve global consistent and real-time multi-robot Simultaneous Localization and Mapping (SLAM). Cloud computing effectively solves the problem of limited computing, communication and storage capacity of terminal equipment. However, limited bandwidth and extremely long communication links between terminal devices and the cloud result in serious performance degradation of multi-robot SLAM systems. To reduce the computational cost of feature tracking and improve the real-time performance of the robot, a lightweight SLAM method of optical flow tracking based on pyramid IMU prediction is proposed. On this basis, a centralized multi-robot SLAM system based on a robot-edge-cloud layered architecture is proposed to realize real-time collaborative SLAM. It avoids the problems of limited on-board computing resources and low execution efficiency of single robot. In this framework, only the feature points and keyframe descriptors are transmitted and lossless encoding and compression are carried out to realize real-time remote information transmission with limited bandwidth resources. This design reduces the actual bandwidth occupied in the process of data transmission, and does not cause the loss of SLAM accuracy caused by data compression. Through experimental verification on the EuRoC dataset, compared with the current most advanced local feature compression method, our method can achieve lower data volume feature transmission, and compared with the current advanced centralized multi-robot SLAM scheme, it can achieve the same or better positioning accuracy under low computational load.
### Title:
          H2LooP Spark Preview: Continual Pretraining of Large Language Models for Low-Level Embedded Systems Code
 - **Authors:** Amit Singh, Vedant Nipane, Pulkit Agrawal, Jatin Kishnani
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) demonstrate strong code generation abilities in general-purpose programming languages but remain limited in specialized domains such as low-level embedded systems programming. This domain involves hardware register manipulation, vendor-specific SDKs, real-time operating system APIs, and hardware abstraction layers that are underrepresented in standard pretraining corpora. We introduce H2LooP Spark Preview, a continual pretraining (CPT) pipeline that adapts the OLMo-3-7B-a fully open language model to the embedded systems domain using BF16 LoRA with rank-stabilized scaling on 8 NVIDIA H100 GPUs. Our training corpus is constructed from repository-datasheet pairs covering 100B tokens of raw embedded systems data across 117 manufacturers, processed using the hierarchical datasheet-to-code mapping approach proposed in SpecMap (Nipane et al., 2026). The resulting curated dataset split contains 23.5B tokens across 13 embedded domains. Continual pretraining with high-rank LoRA (r=512) yields substantial gains, reducing in-domain perplexity by 70.4% and held-out repository perplexity by 66.1%. On generative code completion benchmarks spanning 13 embedded domains, our 7B model outperforms Claude Opus 4.6 and Qwen3-Coder-30B on 8 categories in token accuracy, showing that targeted continual pretraining enables smaller open-weight models to rival frontier systems on specialized technical tasks. We release the production training checkpoint on Huggingface as an open-source artifact.
### Title:
          Bridging Behavioral Biometrics and Source Code Stylometry: A Survey of Programmer Attribution
 - **Authors:** Marek Horvath, Emilia Pietrikova, Diomidis Spinellis
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Programmer attribution seeks to identify or verify the author of a source code artifact using stylistic, structural, or behavioural characteristics. This problem has been studied across software engineering, security, and digital forensics, resulting in a growing and methodologically diverse set of publications. This paper presents a systematic mapping study of programmer attribution research focused on source code analysis. From an initial set of 135 candidate publications, 47 studies published between 2012 and 2025 were selected through a structured screening process. The included works are analysed along several dimensions, including authorship tasks, feature categories, learning and modelling approaches, dataset sources, and evaluation practices. Based on this analysis, we derive a taxonomy that relates stylistic and behavioural feature types to commonly used machine learning techniques and provide a descriptive overview of publication trends, benchmarks, programming languages. A content-level analysis highlights the main thematic clusters in the field. The results indicate a strong focus on closed-world authorship attribution using stylometric features and a heavy reliance on a small number of benchmark datasets, while behavioural signals, authorship verification, and reproducibility remain less explored. The study consolidates existing research into a unified framework and outlines methodological gaps that can guide future work. This manuscript is currently under review. The present version is a preprint.
### Title:
          Bayesian Optimization of Partially Known Systems using Hybrid Models
 - **Authors:** Eike Cramer, Luis Kutschat, Oliver Stollenwerk, Joel A. Paulson, Alexander Mitsos
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bayesian optimization (BO) has gained attention as an efficient algorithm for black-box optimization of expensive-to-evaluate systems, where the BO algorithm iteratively queries the system and suggests new trials based on a probabilistic model fitted to previous samples. Still, the standard BO loop may require a prohibitively large number of experiments to converge to the optimum, especially for high-dimensional and nonlinear systems. We present a hybrid model-based BO formulation that combines the iterative Bayesian learning of BO with partially known mechanistic physical models. Instead of learning a direct mapping from inputs to the objective, we write all known equations for a physics-based model and infer expressions for variables missing equations using a probabilistic model, in our case, a Gaussian process (GP). The final formulation then includes the GP as a constraint in the hybrid model, thereby allowing other physics-based nonlinear and implicit model constraints. This hybrid model formulation yields a constrained, nonlinear stochastic program, which we discretize using the sample-average approximation. In an in-silico optimization of a single-stage distillation, the hybrid BO model based on mass conservation laws yields significantly better designs than a standard BO loop. Furthermore, the hybrid model converges in as few as one iteration, depending on the initial samples, whereas, the standard BO does not converge within 25 for any of the seeds. Overall, the proposed hybrid BO scheme presents a promising optimization method for partially known systems, leveraging the strengths of both mechanistic modeling and data-driven optimization.
### Title:
          InstantHDR: Single-forward Gaussian Splatting for High Dynamic Range 3D Reconstruction
 - **Authors:** Dingqiang Ye, Jiacong Xu, Jianglu Ping, Yuxiang Guo, Chao Fan, Vishal M. Patel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High dynamic range (HDR) novel view synthesis (NVS) aims to reconstruct HDR scenes from multi-exposure low dynamic range (LDR) images. Existing HDR pipelines heavily rely on known camera poses, well-initialized dense point clouds, and time-consuming per-scene optimization. Current feed-forward alternatives overlook the HDR problem by assuming exposure-invariant appearance. To bridge this gap, we propose InstantHDR, a feed-forward network that reconstructs 3D HDR scenes from uncalibrated multi-exposure LDR collections in a single forward pass. Specifically, we design a geometry-guided appearance modeling for multi-exposure fusion, and a meta-network for generalizable scene-specific tone mapping. Due to the lack of HDR scene data, we build a pre-training dataset, called HDR-Pretrain, for generalizable feed-forward HDR models, featuring 168 Blender-rendered scenes, diverse lighting types, and multiple camera response functions. Comprehensive experiments show that our InstantHDR delivers comparable synthesis performance to the state-of-the-art optimization-based HDR methods while enjoying $\sim700\times$ and $\sim20\times$ reconstruction speed improvement with our single-forward and post-optimization settings. All code, models, and datasets will be released after the review process.
### Title:
          Physics-based Approximation and Prediction of Speedlines in Compressor Performance Maps
 - **Authors:** Abdul-Malik Akiev, Danyal Ergür, Alexander Schirger, Matthias Müller, Alexander Hinterleitner, Thomas Bartz-Beielstein
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Speedlines in compressor performance maps (CPMs) are critical for understanding and predicting compressor behavior under various operating conditions. We investigate a physics-based method for reconstructing compressor performance maps from sparse measurements by fitting each speedline with a superellipse and encoding it as a compact, interpretable vector (surge, choke, curvature, and shape parameters). Building on the formulation of Llamas et al., we develop a robust two-stage fitting pipeline that couples global search with local refinement. The approach is validated on industrial data-sets for different turbocharger types. We discuss prediction quality for inter- and extrapolation, metric sensitivities and outline opportunities for physics-informed constraints, alternative function families, and hybrid physics-ML mappings to improve boundary behavior and, ultimately, enable full CPM reconstruction from limited data.
### Title:
          Contractivity of Multi-Stage Runge-Kutta Dynamics
 - **Authors:** Yu Kawano, Francesco Bullo
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many control, optimization, and learning algorithms rely on discretizations of continuous-time contracting systems, where preservation of contractivity under numerical integration is key for stability, robustness, and reliable fixed-point computation. In this paper, we establish conditions under which multi-stage Runge-Kutta methods preserve strong contractivity when discretizing infinitesimally contractive continuous-time systems. For explicit Runge-Kutta methods, preservation conditions are derived by bounding Lipschitz constants of the associated composite stage mappings, leading to coefficient-dependent criteria. For implicit methods, the algebraic structure of the stage equations enables explicit conditions on the Runge-Kutta coefficients that guarantee preservation of strong contractivity. In the implicit case, these results extend classical guarantees, typically limited to weak contractivity in the Euclidean metric, to strong contractivity with respect to the $\ell_1$-, $\ell_2$-, and $\ell_\infty$-norms. In addition, we study well-definedness of implicit methods through an auxiliary continuous-time system associated with the stage equations. We show that strong infinitesimal contractivity of this auxiliary system is sufficient to guarantee unique solvability of the stage equations. This analysis generalizes standard well-definedness conditions and provides a dynamic implementation approach that avoids direct solution of the implicit algebraic equations.
### Title:
          Vision-Based Hand Shadowing for Robotic Manipulation via Inverse Kinematics
 - **Authors:** Hendrik Chiche, Antoine Jamme, Trevor Rigoberto Martinez
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Teleoperation of low-cost robotic manipulators remains challenging due to the complexity of mapping human hand articulations to robot joint commands. We present an offline hand-shadowing and retargeting pipeline from a single egocentric RGB-D camera mounted on 3D-printed glasses. The pipeline detects 21 hand landmarks per hand using MediaPipe Hands, deprojects them into 3D via depth sensing, transforms them into the robot coordinate frame, and solves a damped-least-squares inverse kinematics problem in PyBullet to produce joint commands for the 6-DOF SO-ARM101 robot. A gripper controller maps thumb-index finger geometry to grasp aperture with a four-level fallback hierarchy. Actions are first previewed in a physics simulation before replay on the physical robot through the LeRobot framework. We evaluate the IK retargeting pipeline on a structured pick-and-place benchmark (5-tile grid, 10 grasps per tile) achieving a 90% success rate, and compare it against four vision-language-action policies (ACT, SmolVLA, pi0.5, GR00T N1.5) trained on leader-follower teleoperation data. We also test the IK pipeline in unstructured real-world environments (grocery store, pharmacy), where hand occlusion by surrounding objects reduces success to 9.3% (N=75), highlighting both the promise and current limitations of marker-free analytical retargeting.
### Title:
          High-Precision 6DOF Pose Estimation via Global Phase Retrieval in Fringe Projection Profilometry for 3D Mapping
 - **Authors:** Sehoon Tak, Keunhee Cho, Sangpil Kim, Jae-Sang Hyun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Digital fringe projection (DFP) enables micrometer-level 3D reconstruction, yet extending it to large-scale mapping remains challenging because six-degree-of-freedom pose estimation often cannot match the reconstruction's precision. Conventional iterative closest point (ICP) registration becomes inefficient on multi-million-point clouds and typically relies on downsampling or feature-based selection, which can reduce local detail and degrade pose precision. Drift-correction methods improve long-term consistency but do not resolve sampling sensitivity in dense DFP point this http URL propose a high-precision pose estimation method that augments a moving DFP system with a fixed, intrinsically calibrated global projector. Using the global projector's phase-derived pixel constraints and a PnP-style reprojection objective, the method estimates the DFP system pose in a fixed reference frame without relying on deterministic feature extraction, and we experimentally demonstrate sampling invariance under coordinate-preserving subsampling. Experiments demonstrate sub-millimeter pose accuracy against a reference with quantified uncertainty bounds, high repeatability under aggressive subsampling, robust operation on homogeneous surfaces and low-overlap views, and reduced error accumulation when used to correct ICP-based trajectories. The method extends DFP toward accurate 3D mapping in quasi-static scenarios such as inspection and metrology, with the trade-off of time-multiplexed acquisition for the additional projector measurements.
### Title:
          Gen-Fab: A Variation-Aware Generative Model for Predicting Fabrication Variations in Nanophotonic Devices
 - **Authors:** Rambod Azimi, Yuri Grinberg, Dan-Xia Xu, Odile Liboiron-Ladouceur
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Silicon photonic devices often exhibit fabrication-induced variations such as over-etching, underetching, and corner rounding, which can significantly alter device performance. These variations are non-uniform and are influenced by feature size and shape. Accurate digital twins are therefore needed to predict the range of possible fabricated outcomes for a given design. In this paper, we introduce Gen-Fab, a conditional generative adversarial network (cGAN) based on Pix2Pix to predict and model uncertainty in photonic fabrication outcomes. The proposed method takes a design layout (in GDS format) as input and produces diverse high-resolution predictions similar to scanning electron microscope (SEM) images of fabricated devices, capturing the range of process variations at the nanometer scale. To enable one-to-many mapping, we inject a latent noise vector at the model bottleneck. We compare Gen-Fab against three baselines: (1) a deterministic U-Net predictor, (2) an inference-time Monte Carlo Dropout U-Net, and (3) an ensemble of varied U-Nets. Evaluations on an out-of-distribution dataset of fabricated photonic test structures demonstrate that Gen-Fab outperforms all baselines in both accuracy and uncertainty modeling. An additional distribution shift analysis further confirms its strong generalization to unseen fabrication geometries. Gen-Fab achieves the highest intersection-over-union (IoU) score of 89.8%, outperforming the deterministic U-Net (85.3%), the MC-Dropout U-Net (83.4%), and varying U-Nets (85.8%). It also better aligns with the distribution of real fabrication outcomes, achieving lower Kullback-Leibler divergence and Wasserstein distance.
### Title:
          Shadowless Projection Mapping for Tabletop Workspaces with Synthetic Aperture Projector
 - **Authors:** Takahiro Okamoto, Masaki Takeuchi, Masataka Sawayama, Daisuke Iwai
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Projection mapping (PM) enables augmented reality (AR) experiences without requiring users to wear head-mounted displays and supports multi-user interaction. It is regarded as a promising technology for a variety of applications in which users interact with content superimposed onto augmented objects in tabletop workspaces, including remote collaboration, healthcare, industrial design, urban planning, artwork creation, and office work. However, conventional PM systems often suffer from projection shadows when users occlude the light path. Prior approaches employing multiple distributed projectors can compensate for occlusion, but suffer from latency due to computational processing, degrading the user experience. In this research, we introduce a synthetic-aperture PM system that uses a significantly larger number of projectors, arranged densely in the environment, to achieve delay-free, shadowless projection for tabletop workspaces without requiring computational compensation. To address spatial resolution degradation caused by subpixel misalignment among overlaid projections, we develop and validate an offline blur compensation method whose computation time remains independent of the number of projectors. Furthermore, we demonstrate that our shadowless PM plays a critical role in achieving a fundamental goal of PM: altering material properties without evoking projection-like impression. Specifically, we define this perceptual impression as ``sense of projection (SoP)'' and establish a PM design framework to minimize the SoP based on user studies.
### Title:
          High-Contrast Projection Mapping under Light Field Illumination with LED Display and Aperiodic Lens Array
 - **Authors:** Kotaro Fujimura, Hiroki Kusuyama, Masaki Takeuchi, Daisuke Iwai
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Projection Mapping (PM) is a technology that projects images onto the surfaces of physical objects, allowing multiple users to share an augmented reality experience without special devices. However, its practical use has been constrained by the need for dark environments to ensure high-quality projection. To overcome this ``dark-room constraint,'' we propose a novel target-excluding lighting method that selectively illuminates the surrounding environment while avoiding the PM target. Our system achieves light-field illumination by combining an LED display panel with an optimized aperiodic lens array. The key contributions include a compact form factor that provides a large effective light source area, reproducing natural soft shadows comparable to typical lighting, while maintaining the spatial controllability needed to precisely avoid the target. We also introduce a computational technique for optimizing aperiodic lens placement to suppress undesired dark spots caused by crosstalk, and efficient methods for computing LED luminance patterns that enable dynamic PM. Experiments with a prototype system demonstrate that our approach achieves high-contrast PM even in bright environments.
### Title:
          Universal cycle constructions for k-subsets and k-multisets
 - **Authors:** Colin Campbell, Luke Janik-Jones, Joe Sawada
 - **Subjects:** Subjects:
Discrete Mathematics (cs.DM); Information Theory (cs.IT); Combinatorics (math.CO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A universal cycle for a set S of combinatorial objects is a cyclic sequence of length |S|that contains a representation of each element in S exactly once as a substring. If S is the set of k-subsets of [n] = {1, 2, . . . , n}, it is well-known that universal cycles do not always exists when applying a simple string representation, where 12 or 21 could represent the subset {1, 2}. Similarly, if S is the set of k-multisets of [n], it is also known that universal cycles do not always exist using a similar representation, where 112, 121, or 211 could represent the multiset {1, 1, 2}. By mapping these sets to an appropriate family of labeled graphs, universal cycles are known to exist, but without a known efficient construction. In this paper we consider a new representation for k-subsets and k-multisets that leads to efficient universal cycle constructions for all n, k >=2. We provide successor-rule algorithms to construct such universal cycles in O(n) time per symbol using O(n) space and demonstrate that necklace concatenation algorithms allow the same sequences to be generated in O(1) amortized time per symbol. They are the first known efficient universal cycle constructions for k-multisets. The results are obtained by considering constructions for bounded-weight de Bruijn sequences. In particular, we demonstrate that a bounded-weight generalization of the Grandmama de Bruijn sequence can be constructed in O(1) amortized time per symbol.
### Title:
          Learning Visuomotor Policy for Multi-Robot Laser Tag Game
 - **Authors:** Kai Li, Shiyu Zhao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we study multi robot laser tag, a simplified yet practical shooting-game-style task. Classic modular approaches on these tasks face challenges such as limited observability and reliance on depth mapping and inter robot communication. To overcome these issues, we present an end-to-end visuomotor policy that maps images directly to robot actions. We train a high performing teacher policy with multi agent reinforcement learning and distill its knowledge into a vision-based student policy. Technical designs, including a permutation-invariant feature extractor and depth heatmap input, improve performance over standard architectures. Our policy outperforms classic methods by 16.7% in hitting accuracy and 6% in collision avoidance, and is successfully deployed on real robots. Code will be released publicly.
### Title:
          Cascade: Composing Software-Hardware Attack Gadgets for Adversarial Threat Amplification in Compound AI Systems
 - **Authors:** Sarbartha Banerjee, Prateek Sahu, Anjo Vahldiek-Oberwagner, Jose Sanchez Vicarte, Mohit Tiwari
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rapid progress in generative AI has given rise to Compound AI systems - pipelines comprised of multiple large language models (LLM), software tools and database systems. Compound AI systems are constructed on a layered traditional software stack running on a distributed hardware infrastructure. Many of the diverse software components are vulnerable to traditional security flaws documented in the Common Vulnerabilities and Exposures (CVE) database, while the underlying distributed hardware infrastructure remains exposed to timing attacks, bit-flip faults, and power-based side channels. Today, research targets LLM-specific risks like model extraction, training data leakage, and unsafe generation -- overlooking the impact of traditional system vulnerabilities. This work investigates how traditional software and hardware vulnerabilities can complement LLM-specific algorithmic attacks to compromise the integrity of a compound AI pipeline. We demonstrate two novel attacks that combine system-level vulnerabilities with algorithmic weaknesses: (1) Exploiting a software code injection flaw along with a guardrail Rowhammer attack to inject an unaltered jailbreak prompt into an LLM, resulting in an AI safety violation, and (2) Manipulating a knowledge database to redirect an LLM agent to transmit sensitive user data to a malicious application, thus breaching confidentiality. These attacks highlight the need to address traditional vulnerabilities; we systematize the attack primitives and analyze their composition by grouping vulnerabilities by their objective and mapping them to distinct stages of an attack lifecycle. This approach enables a rigorous red-teaming exercise and lays the groundwork for future defense strategies.
### Title:
          Cross-Domain Policy Optimization via Bellman Consistency and Hybrid Critics
 - **Authors:** Ming-Hong Chen, Kuan-Chen Pan, You-De Huang, Xi Liu, Ping-Chun Hsieh
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-domain reinforcement learning (CDRL) is meant to improve the data efficiency of RL by leveraging the data samples collected from a source domain to facilitate the learning in a similar target domain. Despite its potential, cross-domain transfer in RL is known to have two fundamental and intertwined challenges: (i) The source and target domains can have distinct state space or action space, and this makes direct transfer infeasible and thereby requires more sophisticated inter-domain mappings; (ii) The transferability of a source-domain model in RL is not easily identifiable a priori, and hence CDRL can be prone to negative effect during transfer. In this paper, we propose to jointly tackle these two challenges through the lens of \textit{cross-domain Bellman consistency} and \textit{hybrid critic}. Specifically, we first introduce the notion of cross-domain Bellman consistency as a way to measure transferability of a source-domain model. Then, we propose $Q$Avatar, which combines the Q functions from both the source and target domains with an adaptive hyperparameter-free weight function. Through this design, we characterize the convergence behavior of $Q$Avatar and show that $Q$Avatar achieves reliable transfer in the sense that it effectively leverages a source-domain Q function for knowledge transfer to the target domain. Through experiments, we demonstrate that $Q$Avatar achieves favorable transferability across various RL benchmark tasks, including locomotion and robot arm manipulation. Our code is available at this https URL.
### Title:
          ComFree-Sim: A GPU-Parallelized Analytical Contact Physics Engine for Scalable Contact-Rich Robotics Simulation and Control
 - **Authors:** Chetan Borse, Zhixian Xie, Wei-Cheng Huang, Wanxin Jin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physics simulation for contact-rich robotics is often bottlenecked by contact resolution: mainstream engines enforce non-penetration and Coulomb friction via complementarity constraints or constrained optimization, requiring per-step iterative solves whose cost grows superlinearly with contact density. We present ComFree-Sim, a GPU-parallelized analytical contact physics engine built on complementarity-free contact modeling. ComFree-Sim computes contact impulses in closed form via an impedance-style prediction--correction update in the dual cone of Coulomb friction. Contact computation decouples across contact pairs and becomes separable across cone facets, mapping naturally to GPU kernels and yielding near-linear runtime scaling with the number of contacts. We further extend the formulation to a unified 6D contact model capturing tangential, torsional, and rolling friction, and introduce a practical dual-cone impedance heuristic. ComFree-Sim is implemented in Warp and exposed through a MuJoCo-compatible interface as a drop-in backend alternative to MuJoCo Warp (MJWarp). Experiments benchmark penetration, friction behaviors, stability, and simulation runtime scaling against MJWarp, demonstrating near-linear scaling and 2--3 times higher throughput in dense contact scenes with comparable physical fidelity. We deploy ComFree-Sim in real-time MPC for in-hand dexterous manipulation on a real-world multi-fingered LEAP hand and in dynamics-aware motion retargeting, demonstrating that low-latency simulation yields higher closed-loop success rates and enables practical high-frequency control in contact-rich tasks.
### Title:
          BiGain: Unified Token Compression for Joint Generation and Classification
 - **Authors:** Jiacheng Liu, Shengkun Tang, Jiacheng Cui, Dongkuan Xu, Zhiqiang Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Acceleration methods for diffusion models (e.g., token merging or downsampling) typically optimize synthesis quality under reduced compute, yet often ignore discriminative capacity. We revisit token compression with a joint objective and present BiGain, a training-free, plug-and-play framework that preserves generation quality while improving classification in accelerated diffusion models. Our key insight is frequency separation: mapping feature-space signals into a frequency-aware representation disentangles fine detail from global semantics, enabling compression that respects both generative fidelity and discriminative utility. BiGain reflects this principle with two frequency-aware operators: (1) Laplacian-gated token merging, which encourages merges among spectrally smooth tokens while discouraging merges of high-contrast tokens, thereby retaining edges and textures; and (2) Interpolate-Extrapolate KV Downsampling, which downsamples keys/values via a controllable interextrapolation between nearest and average pooling while keeping queries intact, thereby conserving attention precision. Across DiT- and U-Net-based backbones and ImageNet-1K, ImageNet-100, Oxford-IIIT Pets, and COCO-2017, our operators consistently improve the speed-accuracy trade-off for diffusion-based classification, while maintaining or enhancing generation quality under comparable acceleration. For instance, on ImageNet-1K, with 70% token merging on Stable Diffusion 2.0, BiGain increases classification accuracy by 7.15% while improving FID by 0.34 (1.85%). Our analyses indicate that balanced spectral retention, preserving high-frequency detail and low/mid-frequency semantics, is a reliable design rule for token compression in diffusion models. To our knowledge, BiGain is the first framework to jointly study and advance both generation and classification under accelerated diffusion, supporting lower-cost deployment.
### Title:
          Separable neural architectures as a primitive for unified predictive and generative intelligence
 - **Authors:** Reza T. Batley, Apurba Sarker, Rajib Mostakim, Andrew Klichine, Sourav Saha
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Intelligent systems across physics, language and perception often exhibit factorisable structure, yet are typically modelled by monolithic neural architectures that do not explicitly exploit this structure. The separable neural architecture (SNA) addresses this by formalising a representational class that unifies additive, quadratic and tensor-decomposed neural models. By constraining interaction order and tensor rank, SNAs impose a structural inductive bias that factorises high-dimensional mappings into low-arity components. Separability need not be a property of the system itself: it often emerges in the coordinates or representations through which the system is expressed. Crucially, this coordinate-aware formulation reveals a structural analogy between chaotic spatiotemporal dynamics and linguistic autoregression. By treating continuous physical states as smooth, separable embeddings, SNAs enable distributional modelling of chaotic systems. This approach mitigates the nonphysical drift characteristics of deterministic operators whilst remaining applicable to discrete sequences. The compositional versatility of this approach is demonstrated across four domains: autonomous waypoint navigation via reinforcement learning, inverse generation of multifunctional microstructures, distributional modelling of turbulent flow and neural language modelling. These results establish the separable neural architecture as a domain-agnostic primitive for predictive and generative intelligence, capable of unifying both deterministic and distributional representations.
## Keyword: localization
### Title:
          Edge-Assisted Multi-Robot Visual-Inertial SLAM with Efficient Communication
 - **Authors:** Xin Liu, Shuhuan Wen, Jing Zhao, Tony Z. Qiu, Hong Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The integration of cloud computing and edge computing is an effective way to achieve global consistent and real-time multi-robot Simultaneous Localization and Mapping (SLAM). Cloud computing effectively solves the problem of limited computing, communication and storage capacity of terminal equipment. However, limited bandwidth and extremely long communication links between terminal devices and the cloud result in serious performance degradation of multi-robot SLAM systems. To reduce the computational cost of feature tracking and improve the real-time performance of the robot, a lightweight SLAM method of optical flow tracking based on pyramid IMU prediction is proposed. On this basis, a centralized multi-robot SLAM system based on a robot-edge-cloud layered architecture is proposed to realize real-time collaborative SLAM. It avoids the problems of limited on-board computing resources and low execution efficiency of single robot. In this framework, only the feature points and keyframe descriptors are transmitted and lossless encoding and compression are carried out to realize real-time remote information transmission with limited bandwidth resources. This design reduces the actual bandwidth occupied in the process of data transmission, and does not cause the loss of SLAM accuracy caused by data compression. Through experimental verification on the EuRoC dataset, compared with the current most advanced local feature compression method, our method can achieve lower data volume feature transmission, and compared with the current advanced centralized multi-robot SLAM scheme, it can achieve the same or better positioning accuracy under low computational load.
### Title:
          Single molecule localization microscopy challenge: a biologically inspired benchmark for long-sequence modeling
 - **Authors:** Fatemeh Valeh, Monika Farsang, Radu Grosu, Gerhard Schütz
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State space models (SSMs) have recently achieved strong performance on long sequence modeling tasks while offering improved memory and computational efficiency compared to transformer based architectures. However, their evaluation has been largely limited to synthetic benchmarks and application domains such as language and audio, leaving their behavior on sparse and stochastic temporal processes in biological imaging unexplored. In this work, we introduce the Single Molecule Localization Microscopy Challenge (SMLM-C), a benchmark dataset consisting of ten SMLM simulations spanning dSTORM and DNA-PAINT modalities with varying hyperparameter designed to evaluate state space models on biologically realistic spatiotemporal point process data with known ground truth. Using a controlled subset of these simulations, we evaluate state space models and find that performance degrades substantially as temporal discontinuity increases, revealing fundamental challenges in modeling heavy-tailed blinking dynamics. These results highlight the need for sequence models better suited to sparse, irregular temporal processes encountered in real world scientific imaging data.
### Title:
          Distributed Kalman--Consensus Filtering with Adaptive Uncertainty Weighting for Multi-Object Tracking in Mobile Robot Networks
 - **Authors:** Niusha Khosravi, Rodrigo Ventura, Meysam Basiri
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents an implementation and evaluation of a Distributed Kalman--Consensus Filter (DKCF) for Multi-Object Tracking (MOT) in mobile robot networks operating under partial observability and heterogeneous localization uncertainty. A key challenge in such systems is the fusion of information from agents with differing localization quality, where frame misalignment can lead to inconsistent estimates, track duplication, and ghost tracks. To address this issue, we build upon the MOTLEE framework and retain its frame-alignment methodology, which uses consistently tracked dynamic objects as transient landmarks to improve relative pose estimates between robots. On top of this framework, we propose an uncertainty-aware adaptive consensus weighting mechanism that dynamically adjusts the influence of neighbor information based on the covariance of the transmitted estimates, thereby reducing the impact of unreliable data during distributed fusion. Local tracking is performed using a Kalman Filter (KF) with a Constant Velocity Model (CVM) and Global Nearest Neighbor (GNN) data association. simulation results demonstrate that adaptive weighting effectively protects local estimates from inconsistent data, yielding a MOTA improvement of 0.09 for agents suffering from localization drift, although system performance remains constrained by communication latency.
### Title:
          Resolving Java Code Repository Issues with iSWE Agent
 - **Authors:** Jatin Ganhotra, Sami Serhan, Antonio Abu Nassar, Avraham Shinnar, Ziv Nevo, Martin Hirzel
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Resolving issues on code repositories is an important part of software engineering. Various recent systems automatically resolve issues using large language models and agents, often with impressive performance. Unfortunately, most of these models and agents focus primarily on Python, and their performance on other programming languages is lower. In particular, a lot of enterprise software is written in Java, yet automated issue resolution for Java is under-explored. This paper introduces iSWE Agent, an automated issue resolver with an emphasis on Java. It consists of two sub-agents, one for localization and the other for editing. Both have access to novel tools based on rule-based Java static analysis and transformation. Using this approach, iSWE achieves state-of-the-art issue resolution rates across the Java splits of both Multi-SWE-bench and SWE-PolyBench. More generally, we hope that by combining the best of rule-based and model-based techniques, this paper contributes towards improving enterprise software development.
### Title:
          MirrorDrift: Actuated Mirror-Based Attacks on LiDAR SLAM
 - **Authors:** Rokuto Nagata, Kenji Koide, Kazuma Ikeda, Ozora Sako, Shion Horie, Kentaro Yoshioka
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR SLAM provides high-accuracy localization but is fragile to point-cloud corruption because scan matching assumes geometric consistency. Prior physical attacks on LiDAR SLAM largely rely on LiDAR spoofing via external signal injection, which requires sensor-specific timing knowledge and is increasingly mitigated by modern defense mechanisms such as timing obfuscation and injection rejection. In this work, we show that specular reflection offers an injection-free alternative and demonstrate an attack, MirrorDrift, that uses an actuated planar mirror to cause ghost points in LiDAR scans and systematically bias scan-matching correspondences. MirrorDrift optimizes mirror placement, alignment, and actuation. In simulation, it increases the average pose error (APE) by 6.1x over random placement, degrading three SLAM systems to 2.29-3.31 m mean APE. In real-world experiments on a modern LiDAR with state-of-the-art interference mitigation, it induces localization errors of up to 6.03 m. To the best of our knowledge, this is the first successful SLAM-targeted attack against production-grade secure LiDARs.
### Title:
          Efficient Cross-View Localization in 6G Space-Air-Ground Integrated Network
 - **Authors:** Min Hao, Yanbing Xu, Maoqiang Wu, Jinglin Huang, Chen Shang, Jiacheng Wang, Ruichen Zhang, Jiawen Kang, Dusit Niyato, Zhu Han, Wei Ni
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recently, visual localization has become an important supplement to improve localization reliability, and cross-view approaches can greatly enhance coverage and adaptability. Meanwhile, future 6G will enable a globally covered mobile communication system, with a space-air-ground integrated network (SAGIN) serving as key supporting architecture. Inspired by this, we explore an integration of cross-view localization (CVL) with 6G SAGIN, thereby enhancing its performance in latency, energy consumption, and privacy protection. First, we provide a comprehensive review of CVL and SAGIN, highlighting their capabilities, integration opportunities, and potential applications. Benefiting from the fast and extensive image collection and transmission capabilities of the 6G SAGIN architecture, CVL achieves higher localization accuracy and faster processing speed. Then, we propose a split-inference framework for implementing CVL, which fully leverages the distributed communication and computing resources of the 6G SAGIN architecture. Subsequently, we conduct joint optimization of communication, computation, and confidentiality within the proposed split-inference framework, aiming to provide a paradigm and a direction for making CVL efficient. Experimental results validate the effectiveness of the proposed framework and provide solutions to the optimization problem. Finally, we discuss potential research directions for 6G SAGIN-enabled CVL.
### Title:
          DeepHistoViT: An Interpretable Vision Transformer Framework for Histopathological Cancer Classification
 - **Authors:** Ravi Mosalpuri, Mohammed Abdelsamea, Ahmed Karam Eldaly
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Histopathology remains the gold standard for cancer diagnosis because it provides detailed cellular-level assessment of tissue morphology. However, manual histopathological examination is time-consuming, labour-intensive, and subject to inter-observer variability, creating a demand for reliable computer-assisted diagnostic tools. Recent advances in deep learning, particularly transformer-based architectures, have shown strong potential for modelling complex spatial dependencies in medical images. In this work, we propose DeepHistoViT, a transformer-based framework for automated classification of histopathological images. The model employs a customized Vision Transformer architecture with an integrated attention mechanism designed to capture fine-grained cellular structures while improving interpretability through attention-based localization of diagnostically relevant regions. The framework is evaluated on three publicly available histopathology datasets covering lung cancer, colon cancer, and acute lymphoblastic leukaemia. Experimental results demonstrate state-of-the-art performance across all datasets, with classification accuracy, precision, recall, F1-score, and ROC-AUC reaching 100 percent on the lung and colon cancer datasets, and 99.85 percent, 99.84 percent, 99.86 percent, 99.85 percent, and 99.99 percent respectively on the acute lymphoblastic leukaemia dataset. All performance metrics are reported with 95 percent confidence intervals. These results highlight the effectiveness of transformer-based architectures for histopathological image analysis and demonstrate the potential of DeepHistoViT as an interpretable computer-assisted diagnostic tool to support pathologists in clinical decision-making.
### Title:
          Stay in your Lane: Role Specific Queries with Overlap Suppression Loss for Dense Video Captioning
 - **Authors:** Seung Hyup Baek, Jimin Lee, Hyeongkeun Lee, Jae Won Cho
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dense Video Captioning (DVC) is a challenging multimodal task that involves temporally localizing multiple events within a video and describing them with natural language. While query-based frameworks enable the simultaneous, end-to-end processing of localization and captioning, their reliance on shared queries often leads to significant multi-task interference between the two tasks, as well as temporal redundancy in localization. In this paper, we propose utilizing role-specific queries that separate localization and captioning into independent components, allowing each to exclusively learn its role. We then employ contrastive alignment to enforce semantic consistency between the corresponding outputs, ensuring coherent behavior across the separated queries. Furthermore, we design a novel suppression mechanism in which mutual temporal overlaps across queries are penalized to tackle temporal redundancy, supervising the model to learn distinct, non-overlapping event regions for more precise localization. Additionally, we introduce a lightweight module that captures core event concepts to further enhance semantic richness in captions through concept-level representations. We demonstrate the effectiveness of our method through extensive experiments on major DVC benchmarks YouCook2 and ActivityNet Captions.
### Title:
          CoViLLM: An Adaptive Human-Robot Collaborative Assembly Framework Using Large Language Models for Manufacturing
 - **Authors:** Jiabao Zhao, Jonghan Lim, Hongliang Li, Ilya Kovalenko
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With increasing demand for mass customization, traditional manufacturing robots that rely on rule-based operations lack the flexibility to accommodate customized or new product variants. Human-Robot Collaboration (HRC) has demonstrated potential to improve system adaptability by leveraging human versatility and decision-making capabilities. However, existing HRC frame- works typically depend on predefined perception-manipulation pipelines, limiting their ability to autonomously generate task plans for new product assembly. In this work, we propose CoViLLM, an adaptive human-robot collaborative assembly frame- work that supports the assembly of customized and previously unseen products. CoViLLM combines depth-camera-based localization for object position estimation, human operator classification for identifying new components, and an Large Language Model (LLM) for assembly task planning based on natural language instructions. The framework is validated on the NIST Assembly Task Board for known, customized, and new product cases. Experimental results show that the proposed framework enables flexible collaborative assembly by extending HRC beyond predefined product and task settings.
### Title:
          R4Det: 4D Radar-Camera Fusion for High-Performance 3D Object Detection
 - **Authors:** Zhongyu Xia, Yousen Tang, Yongtao Wang, Zhifeng Wang, Weijun Qin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 4D radar-camera sensing configuration has gained increasing importance in autonomous driving. However, existing 3D object detection methods that fuse 4D Radar and camera data confront several challenges. First, their absolute depth estimation module is not robust and accurate enough, leading to inaccurate 3D localization. Second, the performance of their temporal fusion module will degrade dramatically or even fail when the ego vehicle's pose is missing or inaccurate. Third, for some small objects, the sparse radar point clouds may completely fail to reflect from their surfaces. In such cases, detection must rely solely on visual unimodal priors. To address these limitations, we propose R4Det, which enhances depth estimation quality via the Panoramic Depth Fusion module, enabling mutual reinforcement between absolute and relative depth. For temporal fusion, we design a Deformable Gated Temporal Fusion module that does not rely on the ego vehicle's pose. In addition, we built an Instance-Guided Dynamic Refinement module that extracts semantic prototypes from 2D instance guidance. Experiments show that R4Det achieves state-of-the-art 3D object detection results on the TJ4DRadSet and VoD datasets.
### Title:
          Multi-Agent Reinforcement Learning for UAV-Based Chemical Plume Source Localization
 - **Authors:** Zhirun Li, Derek Hollenbeck, Ruikun Wu, Michelle Sherman, Sihua Shao, Xiang Sun, Mostafa Hassanalian
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Undocumented orphaned wells pose significant health and environmental risks to nearby communities by releasing toxic gases and contaminating water sources, with methane emissions being a primary concern. Traditional survey methods such as magnetometry often fail to detect older wells effectively. In contrast, aerial in-situ sensing using unmanned aerial vehicles (UAVs) offers a promising alternative for methane emission detection and source localization. This study presents a robust and efficient framework based on a multi-agent deep reinforcement learning (MARL) algorithm for the chemical plume source localization (CPSL) problem. The proposed approach leverages virtual anchor nodes to coordinate UAV navigation, enabling collaborative sensing of gas concentrations and wind velocities through onboard and shared measurements. Source identification is achieved by analyzing the historical trajectory of anchor node placements within the plume. Comparative evaluations against the fluxotaxis method demonstrate that the MARL framework achieves superior performance in both localization accuracy and operational efficiency.
### Title:
          DocSage: An Information Structuring Agent for Multi-Doc Multi-Entity Question Answering
 - **Authors:** Teng Lin, Yizhang Zhu, Zhengxuan Zhang, Yuyu Luo, Nan Tang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-document Multi-entity Question Answering inherently demands models to track implicit logic between multiple entities across scattered documents. However, existing Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) frameworks suffer from critical limitations: standard RAG's vector similarity-based coarse-grained retrieval often omits critical facts, graph-based RAG fails to efficiently integrate fragmented complex relationship networks, and both lack schema awareness, leading to inadequate cross-document evidence chain construction and inaccurate entity relationship deduction. To address these challenges, we propose DocSage, an end-to-end agentic framework that integrates dynamic schema discovery, structured information extraction, and schema-aware relational reasoning with error guarantees. DocSage operates through three core modules: (1) A schema discovery module dynamically infers query-specific minimal joinable schemas to capture essential entities and relationships; (2) An extraction module transforms unstructured text into semantically coherent relational tables, enhanced by error-aware correction mechanisms to reduce extraction errors; (3) A reasoning module performs multi-hop relational reasoning over structured tables, leveraging schema awareness to efficiently align cross-document entities and aggregate evidence. This agentic design offers three key advantages: precise fact localization via SQL-powered indexing, natural support for cross-document entity joins through relational tables, and mitigated LLM attention diffusion via structured representation. Evaluations on two MDMEQA benchmarks demonstrate that DocSage significantly outperforms state-of-the-art long-context LLMs and RAG systems, achieving more than 27% accuracy improvements respectively.
### Title:
          Decentralized Cooperative Localization for Multi-Robot Systems with Asynchronous Sensor Fusion
 - **Authors:** Nivand Khosravi, Niusha Khosravi, Mohammad Bozorg, Masoud S. Bahraini
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decentralized cooperative localization (DCL) is a promising approach for nonholonomic mobile robots operating in GPS-denied environments with limited communication infrastructure. This paper presents a DCL framework in which each robot performs localization locally using an Extended Kalman Filter, while sharing measurement information during update stages only when communication links are available and companion robots are successfully detected by LiDAR. The framework preserves cross-correlation consistency among robot state estimates while handling asynchronous sensor data with heterogeneous sampling rates and accommodating accelerations during dynamic maneuvers. Unlike methods that require pre-aligned coordinate systems, the proposed approach allows robots to initialize with arbitrary reference-frame orientations and achieves automatic alignment through transformation matrices in both the prediction and update stages. To improve robustness in feature-sparse environments, we introduce a dual-landmark evaluation framework that exploits both static environmental features and mobile robots as dynamic landmarks. The proposed framework enables reliable detection and feature extraction during sharp turns, while prediction accuracy is improved through information sharing from mutual observations. Experimental results in both Gazebo simulation and real-world basement environments show that DCL outperforms centralized cooperative localization (CCL), achieving a 34% reduction in RMSE, while the dual-landmark variant yields an improvement of 56%. These results demonstrate the applicability of DCL to challenging domains such as enclosed spaces, underwater environments, and feature-sparse terrains where conventional localization methods are ineffective.
### Title:
          RDNet: Region Proportion-Aware Dynamic Adaptive Salient Object Detection Network in Optical Remote Sensing Images
 - **Authors:** Bin Wan, Runmin Cong, Xiaofei Zhou, Hao Fang, Yaoqi Sun, Sam Kwong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Salient object detection (SOD) in remote sensing images faces significant challenges due to large variations in object sizes, the computational cost of self-attention mechanisms, and the limitations of CNN-based extractors in capturing global context and long-range dependencies. Existing methods that rely on fixed convolution kernels often struggle to adapt to diverse object scales, leading to detail loss or irrelevant feature aggregation. To address these issues, this work aims to enhance robustness to scale variations and achieve precise object localization. We propose the Region Proportion-Aware Dynamic Adaptive Salient Object Detection Network (RDNet), which replaces the CNN backbone with the SwinTransformer for global context modeling and introduces three key modules: (1) the Dynamic Adaptive Detail-aware (DAD) module, which applies varied convolution kernels guided by object region proportions; (2) the Frequency-matching Context Enhancement (FCE) module, which enriches contextual information through wavelet interactions and attention; and (3) the Region Proportion-aware Localization (RPL) module, which employs cross-attention to highlight semantic details and integrates a Proportion Guidance (PG) block to assist the DAD module. By combining these modules, RDNet achieves robustness against scale variations and accurate localization, delivering superior detection performance compared with state-of-the-art methods.
### Title:
          A Two-Stage Dual-Modality Model for Facial Emotional Expression Recognition
 - **Authors:** Jiajun Sun, Zhe Gao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper addresses the expression (EXPR) recognition challenge in the 10th Affective Behavior Analysis in-the-Wild (ABAW) workshop and competition, which requires frame-level classification of eight facial emotional expressions from unconstrained videos. This task is challenging due to inaccurate face localization, large pose and scale variations, motion blur, temporal instability, and other confounding factors across adjacent frames. We propose a two-stage dual-modal (audio-visual) model to address these difficulties. Stage I focuses on robust visual feature extraction with a pretrained DINOv2-based encoder. Specifically, DINOv2 ViT-L/14 is used as the backbone, a padding-aware augmentation (PadAug) strategy is employed for image padding and data preprocessing from raw videos, and a mixture-of-experts (MoE) training head is introduced to enhance classifier diversity. Stage II addresses modality fusion and temporal consistency. For the visual modality, faces are re-cropped from raw videos at multiple scales, and the extracted visual features are averaged to form a robust frame-level representation. Concurrently, frame-aligned Wav2Vec 2.0 audio features are derived from short audio windows to provide complementary acoustic cues. These dual-modal features are integrated via a lightweight gated fusion module, followed by inference-time temporal smoothing. Experiments on the ABAW dataset demonstrate the effectiveness of the proposed method. The two-stage model achieves a Macro-F1 score of 0.5368 on the official validation set and 0.5122 +/- 0.0277 under 5-fold cross-validation, outperforming the official baselines.
## Keyword: transformer
### Title:
          Multimodal Self-Attention Network with Temporal Alignment for Audio-Visual Emotion Recognition
 - **Authors:** Inyong Koo, yeeun Seong, Minseok Son, Jaehyuk Jang, Changick Kim
 - **Subjects:** Subjects:
Multimedia (cs.MM); Sound (cs.SD); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio-visual emotion recognition (AVER) methods typically fuse utterance-level features, and even frame-level attention models seldom address the frame-rate mismatch across modalities. In this paper, we propose a Transformer-based framework focusing on the temporal alignment of multimodal features. Our design employs a multimodal self-attention encoder that simultaneously captures intra- and inter-modal dependencies within a shared feature space. To address heterogeneous sampling rates, we incorporate Temporally-aligned Rotary Position Embeddings (TaRoPE), which implicitly synchronize audio and video tokens. Furthermore, we introduce a Cross-Temporal Matching (CTM) loss that enforces consistency among temporally proximate pairs, guiding the encoder toward better alignment. Experiments on CREMA-D and RAVDESS datasets demonstrate consistent improvements over recent baselines, suggesting that explicitly addressing frame-rate mismatch helps preserve temporal cues and enhances cross-modal fusion.
### Title:
          Graph Tokenization for Bridging Graphs and Transformers
 - **Authors:** Zeyuan Guo, Enmao Diao, Cheng Yang, Chuan Shi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The success of large pretrained Transformers is closely tied to tokenizers, which convert raw input into discrete symbols. Extending these models to graph-structured data remains a significant challenge. In this work, we introduce a graph tokenization framework that generates sequential representations of graphs by combining reversible graph serialization, which preserves graph information, with Byte Pair Encoding (BPE), a widely adopted tokenizer in large language models (LLMs). To better capture structural information, the graph serialization process is guided by global statistics of graph substructures, ensuring that frequently occurring substructures appear more often in the sequence and can be merged by BPE into meaningful tokens. Empirical results demonstrate that the proposed tokenizer enables Transformers such as BERT to be directly applied to graph benchmarks without architectural modifications. The proposed approach achieves state-of-the-art results on 14 benchmark datasets and frequently outperforms both graph neural networks and specialized graph transformers. This work bridges the gap between graph-structured data and the ecosystem of sequence models. Our code is available at \href{this https URL}{\color{blue}here}.
### Title:
          Task-Conditioned Routing Signatures in Sparse Mixture-of-Experts Transformers
 - **Authors:** Mynampati Sri Ranganadha Avinash
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse Mixture-of-Experts (MoE) architectures enable efficient scaling of large language models through conditional computation, yet the routing mechanisms responsible for expert selection remain poorly understood. In this work, we introduce routing signatures, a vector representation summarizing expert activation patterns across layers for a given prompt, and use them to study whether MoE routing exhibits task-conditioned structure. Using OLMoE-1B-7B-0125-Instruct as an empirical testbed, we show that prompts from the same task category induce highly similar routing signatures, while prompts from different categories exhibit substantially lower similarity. Within-category routing similarity (0.8435 +/- 0.0879) significantly exceeds across-category similarity (0.6225 +/- 0.1687), corresponding to Cohen's d = 1.44. A logistic regression classifier trained solely on routing signatures achieves 92.5% +/- 6.1% cross-validated accuracy on four-way task classification. To ensure statistical validity, we introduce permutation and load-balancing baselines and show that the observed separation is not explained by sparsity or balancing constraints alone. We further analyze layer-wise signal strength and low-dimensional projections of routing signatures, finding that task structure becomes increasingly apparent in deeper layers. These results suggest that routing in sparse transformers is not merely a balancing mechanism, but a measurable task-sensitive component of conditional computation. We release MOE-XRAY, a lightweight toolkit for routing telemetry and analysis.
### Title:
          Higher-Order Modular Attention: Fusing Pairwise and Triadic Interactions for Protein Sequences
 - **Authors:** Shirin Amiraslani, Xin Gao
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer self-attention computes pairwise token interactions, yet protein sequence to phenotype relationships often involve cooperative dependencies among three or more residues that dot product attention does not capture explicitly. We introduce Higher-Order Modular Attention, HOMA, a unified attention operator that fuses pairwise attention with an explicit triadic interaction pathway. To make triadic attention practical on long sequences, HOMA employs block-structured, windowed triadic attention. We evaluate on three TAPE benchmarks for Secondary Structure, Fluorescence, and Stability. Our attention mechanism yields consistent improvements across all tasks compared with standard self-attention and efficient variants including block-wise attention and Linformer. These results suggest that explicit triadic terms provide complementary representational capacity for protein sequence prediction at controllable additional computational cost.
### Title:
          Attention Gathers, MLPs Compose: A Causal Analysis of an Action-Outcome Circuit in VideoViT
 - **Authors:** Sai V R Chereddy
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The paper explores how video models trained for classification tasks represent nuanced, hidden semantic information that may not affect the final outcome, a key challenge for Trustworthy AI models. Through Explainable and Interpretable AI methods, specifically mechanistic interpretability techniques, the internal circuit responsible for representing the action's outcome is reverse-engineered in a pre-trained video vision transformer, revealing that the "Success vs Failure" signal is computed through a distinct amplification cascade. While there are low-level differences observed from layer 0, the abstract and semantic representation of the outcome is progressively amplified from layers 5 through 11. Causal analysis, primarily using activation patching supported by ablation results, reveals a clear division of labor: Attention Heads act as "evidence gatherers", providing necessary low-level information for partial signal recovery, while MLP Blocks function as robust "concept composers", each of which is the primary driver to generate the "success" signal. This distributed and redundant circuit in the model's internals explains its resilience to simple ablations, demonstrating a core computational pattern for processing human-action outcomes. Crucially, the existence of this sophisticated circuit for representing complex outcomes, even within a model trained only for simple classification, highlights the potential for models to develop forms of 'hidden knowledge' beyond their explicit task, underscoring the need for mechanistic oversight for building genuinely Explainable and Trustworthy AI systems intended for deployment.
### Title:
          Algorithmic Capture, Computational Complexity, and Inductive Bias of Infinite Transformers
 - **Authors:** Orit Davidovich, Zohar Ringel
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Disordered Systems and Neural Networks (cond-mat.dis-nn); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We formally define Algorithmic Capture (i.e., ``grokking'' an algorithm) as the ability of a neural network to generalize to arbitrary problem sizes ($T$) with controllable error and minimal sample adaptation, distinguishing true algorithmic learning from statistical interpolation. By analyzing infinite-width transformers in both the lazy and rich regimes, we derive upper bounds on the inference-time computational complexity of the functions these networks can learn. We show that despite their universal expressivity, transformers possess an inductive bias towards low-complexity algorithms within the Efficient Polynomial Time Heuristic Scheme (EPTHS) class. This bias effectively prevents them from capturing higher-complexity algorithms, while allowing success on simpler tasks like search, copy, and sort.
### Title:
          GGPT: Geometry Grounded Point Transformer
 - **Authors:** Yutong Chen, Yiming Wang, Xucong Zhang, Sergey Prokudin, Siyu Tang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent feed-forward networks have achieved remarkable progress in sparse-view 3D reconstruction by predicting dense point maps directly from RGB images. However, they often suffer from geometric inconsistencies and limited fine-grained accuracy due to the absence of explicit multi-view constraints. We introduce the Geometry-Grounded Point Transformer (GGPT), a framework that augments feed-forward reconstruction with reliable sparse geometric guidance. We first propose an improved Structure-from-Motion pipeline based on dense feature matching and lightweight geometric optimisation to efficiently estimate accurate camera poses and partial 3D point clouds from sparse input views. Building on this foundation, we propose a geometry-guided 3D point transformer that refines dense point maps under explicit partial-geometry supervision using an optimised guidance encoding. Extensive experiments demonstrate that our method provides a principled mechanism for integrating geometric priors with dense feed-forward predictions, producing reconstructions that are both geometrically consistent and spatially complete, recovering fine structures and filling gaps in textureless areas. Trained solely on ScanNet++ with VGGT predictions, GGPT generalises across architectures and datasets, substantially outperforming state-of-the-art feed-forward 3D reconstruction models in both in-domain and out-of-domain settings.
### Title:
          DNS-GT: A Graph-based Transformer Approach to Learn Embeddings of Domain Names from DNS Queries
 - **Authors:** Massimiliano Altieri, Ronan Hamon, Roberto Corizzo, Michelangelo Ceci, Ignacio Sanchez
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Network intrusion detection systems play a crucial role in the security strategy employed by organisations to detect and prevent cyberattacks. Such systems usually combine pattern detection signatures with anomaly detection techniques powered by machine learning methods. However, the commonly proposed machine learning methods present drawbacks such as over-reliance on labeled data and limited generalization capabilities. To address these issues, embedding-based methods have been introduced to learn representations from network data, such as DNS traffic, mainly due to its large availability, that generalise effectively to many downstream tasks. However, current approaches do not properly consider contextual information among DNS queries. In this paper, we tackle this issue by proposing DNS-GT, a novel Transformer-based model that learns embeddings for domain names from sequences of DNS queries. The model is first pre-trained in a self-supervised fashion in order to learn the general behavior of DNS activity. Then, it can be finetuned on specific downstream tasks, exploiting interactions with other relevant queries in a given sequence. Our experiments with real-world DNS data showcase the ability of our method to learn effective domain name representations. A quantitative evaluation on domain name classification and botnet detection tasks shows that our approach achieves better results compared to relevant baselines, creating opportunities for further exploration of large-scale language models for intrusion detection systems. Our code is available at: this https URL.
### Title:
          A Simple Efficiency Incremental Learning Framework via Vision-Language Model with Nonlinear Multi-Adapters
 - **Authors:** Haihua Luo, Xuming Ran, Jiangrong Shen, Timo Hämäläinen, Zhonghua Chen, Qi Xu, Fengyu Cong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Incremental Learning (IL) aims to learn new tasks while preserving previously acquired knowledge. Integrating the zero-shot learning capabilities of pre-trained vision-language models into IL methods has marked a significant advancement. However, these methods face three primary challenges: (1) the need for improved training efficiency; (2) reliance on a memory bank to store previous data; and (3) the necessity of a strong backbone to augment the model's capabilities. In this paper, we propose SimE, a Simple and Efficient framework that employs a vision-language model with adapters designed specifically for the IL task. We report a remarkable phenomenon: there is a nonlinear correlation between the number of adaptive adapter connections and the model's IL capabilities. While increasing adapter connections between transformer blocks improves model performance, adding more adaptive connections within transformer blocks during smaller incremental steps does not enhance, and may even degrade the model's IL ability. Extensive experimental results show that SimE surpasses traditional methods by 9.6% on TinyImageNet and outperforms other CLIP-based methods by 5.3% on CIFAR-100. Furthermore, we conduct a systematic study to enhance the utilization of the zero-shot capabilities of CLIP. We suggest replacing SimE's encoder with a CLIP model trained on larger datasets (e.g., LAION2B) and stronger architectures (e.g., ViT-L/14).
### Title:
          Artificial Intelligence for Sentiment Analysis of Persian Poetry
 - **Authors:** Arash Zargar, Abolfazl Moshiri, Mitra Shafaei, Shabnam Rahimi-Golkhandan, Mohamad Tavakoli-Targhi, Farzad Khalvati
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advancements of the Artificial Intelligence (AI) have led to the development of large language models (LLMs) that are capable of understanding, analysing, and creating textual data. These language models open a significant opportunity in analyzing the literature and more specifically poetry. In the present work, we employ multiple Bidirectional encoder representations from transformers (BERT) and Generative Pre-trained Transformer (GPT) based language models to analyze the works of two prominent Persian poets: Jalal al-Din Muhammad Rumi (Rumi) and Parvin E'tesami. The main objective of this research is to investigate the capability of the modern language models in grasping complexities of the Persian poetry and explore potential correlations between the poems' sentiment and their meters. Our findings in this study indicates that GPT4o language model can reliably be used in analysis of Persian poetry. Furthermore, the results of our sentiment analysis revealed that in general, Rumi's poems express happier sentiments compared to Parvin E'tesami's poems. Furthermore, comparing the utilization of poetic meters highlighted Rumi's poems superiority in using meters to express a wider variety of sentiments. These findings are significant as they confirm that LLMs can be effectively applied in conducting computer-based semantic studies, where human interpretations are not required, and thereby significantly reducing potential biases in the analysis.
### Title:
          Single molecule localization microscopy challenge: a biologically inspired benchmark for long-sequence modeling
 - **Authors:** Fatemeh Valeh, Monika Farsang, Radu Grosu, Gerhard Schütz
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State space models (SSMs) have recently achieved strong performance on long sequence modeling tasks while offering improved memory and computational efficiency compared to transformer based architectures. However, their evaluation has been largely limited to synthetic benchmarks and application domains such as language and audio, leaving their behavior on sparse and stochastic temporal processes in biological imaging unexplored. In this work, we introduce the Single Molecule Localization Microscopy Challenge (SMLM-C), a benchmark dataset consisting of ten SMLM simulations spanning dSTORM and DNA-PAINT modalities with varying hyperparameter designed to evaluate state space models on biologically realistic spatiotemporal point process data with known ground truth. Using a controlled subset of these simulations, we evaluate state space models and find that performance degrades substantially as temporal discontinuity increases, revealing fundamental challenges in modeling heavy-tailed blinking dynamics. These results highlight the need for sequence models better suited to sparse, irregular temporal processes encountered in real world scientific imaging data.
### Title:
          On the Computational Hardness of Transformers
 - **Authors:** Barna Saha, Yinzhan Xu, Christopher Ye, Hantao Yu
 - **Subjects:** Subjects:
Computational Complexity (cs.CC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The transformer has revolutionized modern AI across language, vision, and beyond. It consists of $L$ layers, each running $H$ attention heads in parallel and feeding the combined output to the subsequent layer. In attention, the input consists of $N$ tokens, each a vector of dimension $m$. The attention mechanism involves multiplying three $N \times m$ matrices, applying softmax to an intermediate product. Several recent works have advanced our understanding of the complexity of attention. Known algorithms for transformers compute each attention head independently. This raises a fundamental question that has recurred throughout TCS under the guise of ``direct sum'' problems: can multiple instances of the same problem be solved more efficiently than solving each instance separately? Many answers to this question, both positive and negative, have arisen in fields spanning communication complexity and algorithm design. Thus, we ask whether transformers can be computed more efficiently than $LH$ independent evaluations of attention. In this paper, we resolve this question in the negative, and give the first non-trivial computational lower bounds for multi-head multi-layer transformers. In the small embedding regime ($m = N^{o(1)}$), computing $LH$ attention heads separately takes $LHN^{2 + o(1)}$ time. We establish that this is essentially optimal under SETH. In the large embedding regime ($m = N$), one can compute $LH$ attention heads separately using $LHN^{\omega + o(1)}$ arithmetic operations (plus exponents), where $\omega$ is the matrix multiplication exponent. We establish that this is optimal, by showing that $LHN^{\omega - o(1)}$ arithmetic operations are necessary when $\omega > 2$. Our lower bound in the large embedding regime relies on a novel application of the Baur-Strassen theorem, a powerful algorithmic tool underpinning the famous backpropagation algorithm.
### Title:
          Evaluating Explainable AI Attribution Methods in Neural Machine Translation via Attention-Guided Knowledge Distillation
 - **Authors:** Aria Nourbakhsh, Salima Lamsiyah, Adelaide Danilov, Christoph Schommer
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The study of the attribution of input features to the output of neural network models is an active area of research. While numerous Explainable AI (XAI) techniques have been proposed to interpret these models, the systematic and automated evaluation of these methods in sequence-to-sequence (seq2seq) models is less explored. This paper introduces a new approach for evaluating explainability methods in transformer-based seq2seq models. We use teacher-derived attribution maps as a structured side signal to guide a student model, and quantify the utility of different attribution methods through the student's ability to simulate targets. Using the Inseq library, we extract attribution scores over source-target sequence pairs and inject these scores into the attention mechanism of a student transformer model under four composition operators (addition, multiplication, averaging, and replacement). Across three language pairs (de-en, fr-en, ar-en) and attributions from Marian-MT and mBART models, Attention, Value Zeroing, and Layer Gradient $\times$ Activation consistently yield the largest gains in BLEU (and corresponding improvements in chrF) relative to baselines. In contrast, other gradient-based methods (Saliency, Integrated Gradients, DeepLIFT, Input $\times$ Gradient, GradientShap) lead to smaller and less consistent improvements. These results suggest that different attribution methods capture distinct signals and that attention-derived attributions better capture alignment between source and target representations in seq2seq models. Finally, we introduce an Attributor transformer that, given a source-target pair, learns to reconstruct the teacher's attribution map. Our findings demonstrate that the more accurately the Attributor can reproduce attribution maps, the more useful an injection of those maps is for the downstream task. The source code can be found on GitHub.
### Title:
          TimeSqueeze: Dynamic Patching for Efficient Time Series Forecasting
 - **Authors:** Sravan Kumar Ankireddy, Nikita Seleznev, Nam H. Nguyen, Yulun Wu, Senthil Kumar, Furong Huang, C. Bayan Bruss
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based time series foundation models face a fundamental trade-off in choice of tokenization: point-wise embeddings preserve temporal fidelity but scale poorly with sequence length, whereas fixed-length patching improves efficiency by imposing uniform boundaries that may disrupt natural transitions and blur informative local dynamics. In order to address these limitations, we introduce TimeSqueeze, a dynamic patching mechanism that adaptively selects patch boundaries within each sequence based on local signal complexity. TimeSqueeze first applies a lightweight state-space encoder to extract full-resolution point-wise features, then performs content-aware segmentation by allocating short patches to information-dense regions and long patches to smooth or redundant segments. This variable-resolution compression preserves critical temporal structure while substantially reducing the token sequence presented to the Transformer backbone. Specifically for large-scale pretraining, TimeSqueeze attains up to 20x faster convergence and 8x higher data efficiency compared to equivalent point-token baselines. Experiments across long-horizon forecasting benchmarks show that TimeSqueeze consistently outperforms comparable architectures that use either point-wise tokenization or fixed-size patching.
### Title:
          Multilingual Financial Fraud Detection Using Machine Learning and Transformer Models: A Bangla-English Study
 - **Authors:** Mohammad Shihab Uddin, Md Hasibul Amin, Nusrat Jahan Ema, Bushra Uddin, Tanvir Ahmed, Arif Hassan Zidan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Financial fraud detection has emerged as a critical research challenge amid the rapid expansion of digital financial platforms. Although machine learning approaches have demonstrated strong performance in identifying fraudulent activities, most existing research focuses exclusively on English-language data, limiting applicability to multilingual contexts. Bangla (Bengali), despite being spoken by over 250 million people, remains largely unexplored in this domain. In this work, we investigate financial fraud detection in a multilingual Bangla-English setting using a dataset comprising legitimate and fraudulent financial messages. We evaluate classical machine learning models (Logistic Regression, Linear SVM, and Ensemble classifiers) using TF-IDF features alongside transformer-based architectures. Experimental results using 5-fold stratified cross-validation demonstrate that Linear SVM achieves the best performance with 91.59 percent accuracy and 91.30 percent F1 score, outperforming the transformer model (89.49 percent accuracy, 88.88 percent F1) by approximately 2 percentage points. The transformer exhibits higher fraud recall (94.19 percent) but suffers from elevated false positive rates. Exploratory analysis reveals distinctive patterns: scam messages are longer, contain urgency-inducing terms, and frequently include URLs (32 percent) and phone numbers (97 percent), while legitimate messages feature transactional confirmations and specific currency references. Our findings highlight that classical machine learning with well-crafted features remains competitive for multilingual fraud detection, while also underscoring the challenges posed by linguistic diversity, code-mixing, and low-resource language constraints.
### Title:
          Ensuring Safety in Automated Mechanical Ventilation through Offline Reinforcement Learning and Digital Twin Verification
 - **Authors:** Hang Yu, Huidong Liu, Qingchen Zhang, William Joy, Kateryna Nikulina, Andreas A. Schuppert, Sina Saffaran, Declan Bates
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanical ventilation (MV) is a life-saving intervention for patients with acute respiratory failure (ARF) in the ICU. However, inappropriate ventilator settings could cause ventilator-induced lung injury (VILI). Also, clinicians workload is shown to be directly linked to patient outcomes. Hence, MV should be personalized and automated to improve patient outcomes. Previous attempts to incorporate personalization and automation in MV include traditional supervised learning and offline reinforcement learning (RL) approaches, which often neglect temporal dependencies and rely excessively on mortality-based rewards. As a result, early stage physiological deterioration and the risk of VILI are not adequately captured. To address these limitations, we propose Transformer-based Conservative Q-Learning (T-CQL), a novel offline RL framework that integrates a Transformer encoder for effective temporal modeling of patient dynamics, conservative adaptive regularization based on uncertainty quantification to ensure safety, and consistency regularization for robust decision-making. We build a clinically informed reward function that incorporates indicators of VILI and a score for severity of patients illness. Also, previous work predominantly uses Fitted Q-Evaluation (FQE) for RL policy evaluation on static offline data, which is less responsive to dynamic environmental changes and susceptible to distribution shifts. To overcome these evaluation limitations, interactive digital twins of ARF patients were used for online "at the bedside" evaluation. Our results demonstrate that T-CQL consistently outperforms existing state-of-the-art offline RL methodologies, providing safer and more effective ventilatory adjustments. Our framework demonstrates the potential of Transformer-based models combined with conservative RL strategies as a decision support tool in critical care.
### Title:
          DeepHistoViT: An Interpretable Vision Transformer Framework for Histopathological Cancer Classification
 - **Authors:** Ravi Mosalpuri, Mohammed Abdelsamea, Ahmed Karam Eldaly
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Histopathology remains the gold standard for cancer diagnosis because it provides detailed cellular-level assessment of tissue morphology. However, manual histopathological examination is time-consuming, labour-intensive, and subject to inter-observer variability, creating a demand for reliable computer-assisted diagnostic tools. Recent advances in deep learning, particularly transformer-based architectures, have shown strong potential for modelling complex spatial dependencies in medical images. In this work, we propose DeepHistoViT, a transformer-based framework for automated classification of histopathological images. The model employs a customized Vision Transformer architecture with an integrated attention mechanism designed to capture fine-grained cellular structures while improving interpretability through attention-based localization of diagnostically relevant regions. The framework is evaluated on three publicly available histopathology datasets covering lung cancer, colon cancer, and acute lymphoblastic leukaemia. Experimental results demonstrate state-of-the-art performance across all datasets, with classification accuracy, precision, recall, F1-score, and ROC-AUC reaching 100 percent on the lung and colon cancer datasets, and 99.85 percent, 99.84 percent, 99.86 percent, 99.85 percent, and 99.99 percent respectively on the acute lymphoblastic leukaemia dataset. All performance metrics are reported with 95 percent confidence intervals. These results highlight the effectiveness of transformer-based architectures for histopathological image analysis and demonstrate the potential of DeepHistoViT as an interpretable computer-assisted diagnostic tool to support pathologists in clinical decision-making.
### Title:
          Detect Anything in Real Time: From Single-Prompt Segmentation to Multi-Class Detection
 - **Authors:** Mehmet Kerem Turkcan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in vision-language modeling have produced promptable detection and segmentation systems that accept arbitrary natural language queries at inference time. Among these, SAM3 achieves state-of-the-art accuracy by combining a ViT-H/14 backbone with cross-modal transformer decoding and learned object queries. However, SAM3 processes a single text prompt per forward pass. Detecting N categories requires N independent executions, each dominated by the 439M-parameter backbone. We present Detect Anything in Real Time (DART), a training-free framework that converts SAM3 into a real-time multi-class detector by exploiting a structural invariant: the visual backbone is class-agnostic, producing image features independent of the text prompt. This allows the backbone computation to be shared between all classes, reducing its cost from O(N) to O(1). Combined with batched multi-class decoding, detection-only inference, and TensorRT FP16 deployment, these optimizations yield 5.6x cumulative speedup at 3 classes, scaling to 25x at 80 classes, without modifying any model weight. On COCO val2017 (5,000 images, 80 classes), DART achieves 55.8 AP at 15.8 FPS (4 classes, 1008x1008) on a single RTX 4080, surpassing purpose-built open-vocabulary detectors trained on millions of box annotations. For extreme latency targets, adapter distillation with a frozen encoder-decoder achieves 38.7 AP with a 13.9 ms backbone. Code and models are available at this https URL.
### Title:
          Attention Sinks Are Provably Necessary in Softmax Transformers: Evidence from Trigger-Conditional Tasks
 - **Authors:** Yuval Ran-Milo
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers often display an attention sink: probability mass concentrates on a fixed, content-agnostic position. We prove that computing a simple trigger-conditional behavior necessarily induces a sink in softmax self-attention models. Our results formalize a familiar intuition: normalization over a probability simplex must force attention to collapse onto a stable anchor to realize a default state (e.g., when the model needs to ignore the input). We instantiate this with a concrete task: when a designated trigger token appears, the model must return the average of all preceding token representations, and otherwise output zero, a task which mirrors the functionality of attention heads in the wild (Barbero et al., 2025; Guo et al., 2024). We also prove that non-normalized ReLU attention can solve the same task without any sink, confirming that the normalization constraint is the fundamental driver of sink behavior. Experiments validate our predictions and demonstrate they extend beyond the theoretically analyzed setting: softmax models develop strong sinks while ReLU attention eliminates them in both single-head and multi-head variants.
### Title:
          Mango-GS: Enhancing Spatio-Temporal Consistency in Dynamic Scenes Reconstruction using Multi-Frame Node-Guided 4D Gaussian Splatting
 - **Authors:** Tingxuan Huang, Haowei Zhu, Jun-hai Yong, Hao Pan, Bin Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing dynamic 3D scenes with photorealistic detail and strong temporal coherence remains a significant challenge. Existing Gaussian splatting approaches for dynamic scene modeling often rely on per-frame optimization, which can overfit to instantaneous states instead of capturing underlying motion dynamics. To address this, we present Mango-GS, a multi-frame, node-guided framework for high-fidelity 4D reconstruction. Mango-GS leverages a temporal Transformer to model motion dependencies within a short window of frames, producing temporally consistent deformations. For efficiency, temporal modeling is confined to a sparse set of control nodes. Each node is represented by a decoupled canonical position and a latent code, providing a stable semantic anchor for motion propagation and preventing correspondence drift under large motion. Our framework is trained end-to-end, enhanced by an input masking strategy and two multi-frame losses to improve robustness. Extensive experiments demonstrate that Mango-GS achieves state-of-the-art reconstruction quality and real-time rendering speed, enabling high-fidelity reconstruction and interactive rendering of dynamic scenes.
### Title:
          TornadoNet: Real-Time Building Damage Detection with Ordinal Supervision
 - **Authors:** Robinson Umeike, Cuong Pham, Ryan Hausen, Thang Dao, Shane Crawford, Tanya Brown-Giammanco, Gerard Lemson, John van de Lindt, Blythe Johnston, Arik Mitschang, Trung Do
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present TornadoNet, a comprehensive benchmark for automated street-level building damage assessment evaluating how modern real-time object detection architectures and ordinal-aware supervision strategies perform under realistic post-disaster conditions. TornadoNet provides the first controlled benchmark demonstrating how architectural design and loss formulation jointly influence multi-level damage detection from street-view imagery, delivering methodological insights and deployable tools for disaster response. Using 3,333 high-resolution geotagged images and 8,890 annotated building instances from the 2021 Midwest tornado outbreak, we systematically compare CNN-based detectors from the YOLO family against transformer-based models (RT-DETR) for multi-level damage detection. Models are trained under standardized protocols using a five-level damage classification framework based on IN-CORE damage states, validated through expert cross-annotation. Baseline experiments reveal complementary architectural strengths. CNN-based YOLO models achieve highest detection accuracy and throughput, with larger variants reaching 46.05% mAP@0.5 at 66-276 FPS on A100 GPUs. Transformer-based RT-DETR models exhibit stronger ordinal consistency, achieving 88.13% Ordinal Top-1 Accuracy and MAOE of 0.65, indicating more reliable severity grading despite lower baseline mAP. To align supervision with the ordered nature of damage severity, we introduce soft ordinal classification targets and evaluate explicit ordinal-distance penalties. RT-DETR trained with calibrated ordinal supervision achieves 44.70% mAP@0.5, a 4.8 percentage-point improvement, with gains in ordinal metrics (91.15% Ordinal Top-1 Accuracy, MAOE = 0.56). These findings establish that ordinal-aware supervision improves damage severity estimation when aligned with detector architecture. Model & Data: this https URL
### Title:
          Fractional Rotation, Full Potential? Investigating Performance and Convergence of Partial RoPE
 - **Authors:** Mohammad Aflah Khan, Krishna P. Gummadi, Manish Gupta, Abhilasha Ravichander
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rotary Positional Embedding (RoPE) is a common choice in transformer architectures for encoding relative positional information. Although earlier work has examined omitting RoPE in specific layers, the effect of varying the fraction of hidden dimensions that receive rotary transformations remains largely unexplored. This design choice can yield substantial memory savings, which becomes especially significant at long context lengths. We find up to 10x memory savings over the standard RoPE cache, while achieving comparable final loss. In this work, we present a systematic study examining the impact of partial RoPE on training dynamics and convergence across architectures and datasets. Our findings uncover several notable patterns: (1) applying RoPE to only a small fraction of dimensions (around 10%) achieves convergence comparable to using full RoPE; (2) these trends hold consistently across model size, sequence lengths and datasets of varying quality and architectures, with higher-quality data resulting in lower overall loss and similar benchmark performance; and (3) some models trained with NoPE (No Positional Encoding) showcase unstable learning trajectories, which can be alleviated through minimal RoPE application or QK-Norm which converges to a higher loss. Together, these results offer practical guidance for model designers aiming to balance efficiency and training stability, while emphasizing the previously overlooked importance of partial RoPE.
### Title:
          Learn Structure, Adapt on the Fly: Multi-Scale Residual Learning and Online Adaptation for Aerial Manipulators
 - **Authors:** Samaksh Ujjawal, Naveen Sudheer Nair, Shivansh Pratap Singh, Rishabh Dev Yadav, Wei Pan, Spandan Roy
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous Aerial Manipulators (AAMs) are inherently coupled, nonlinear systems that exhibit nonstationary and multiscale residual dynamics, particularly during manipulator reconfiguration and abrupt payload variations. Conventional analytical dynamic models rely on fixed parametric structures, while static data-driven model assume stationary dynamics and degrade under configuration changes and payload variations. Moreover, existing learning architectures do not explicitly factorize cross-variable coupling and multi-scale temporal effects, conflating instantaneous inertial dynamics with long-horizon regime evolution. We propose a predictive-adaptive framework for real-time residual modeling and compensation in AAMs. The core of this framework is the Factorized Dynamics Transformer (FDT), which treats physical variables as independent tokens. This design enables explicit cross-variable attention while structurally separating short-horizon inertial dependencies from long-horizon aerodynamic effects. To address deployment-time distribution shifts, a Latent Residual Adapter (LRA) performs rapid linear adaptation in the latent space via Recursive Least Squares, preserving the offline nonlinear representation without prohibitive computational overhead. The adapted residual forecast is directly integrated into a residual-compensated adaptive controller. Real-world experiments on an aerial manipulator subjected to unseen payloads demonstrate higher prediction fidelity, accelerated disturbance attenuation, and superior closed-loop tracking precision compared to state-of-the-art learning baselines, all while maintaining strict real-time feasibility.
### Title:
          PROMO: Promptable Outfitting for Efficient High-Fidelity Virtual Try-On
 - **Authors:** Haohua Chen, Tianze Zhou, Wei Zhu, Runqi Wang, Yandong Guan, Dejia Song, Yibo Chen, Xu Tang, Yao Hu, Lu Sheng, Zhiyong Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Virtual Try-on (VTON) has become a core capability for online retail, where realistic try-on results provide reliable fit guidance, reduce returns, and benefit both consumers and merchants. Diffusion-based VTON methods achieve photorealistic synthesis, yet often rely on intricate architectures such as auxiliary reference networks and suffer from slow sampling, making the trade-off between fidelity and efficiency a persistent challenge. We approach VTON as a structured image editing problem that demands strong conditional generation under three key requirements: subject preservation, faithful texture transfer, and seamless harmonization. Under this perspective, our training framework is generic and transfers to broader image editing tasks. Moreover, the paired data produced by VTON constitutes a rich supervisory resource for training general-purpose editors. We present PROMO, a promptable virtual try-on framework built upon a Flow Matching DiT backbone with latent multi-modal conditional concatenation. By leveraging conditioning efficiency and self-reference mechanisms, our approach substantially reduces inference overhead. On standard benchmarks, PROMO surpasses both prior VTON methods and general image editing models in visual fidelity while delivering a competitive balance between quality and speed. These results demonstrate that flow-matching transformers, coupled with latent multi-modal conditioning and self-reference acceleration, offer an effective and training-efficient solution for high-quality virtual try-on.
### Title:
          UCAN: Unified Convolutional Attention Network for Expansive Receptive Fields in Lightweight Super-Resolution
 - **Authors:** Cao Thien Tan, Phan Thi Thu Trang, Do Nghiem Duc, Ho Ngoc Anh, Hanyang Zhuang, Nguyen Duc Dung
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hybrid CNN-Transformer architectures achieve strong results in image super-resolution, but scaling attention windows or convolution kernels significantly increases computational cost, limiting deployment on resource-constrained devices. We present UCAN, a lightweight network that unifies convolution and attention to expand the effective receptive field efficiently. UCAN combines window-based spatial attention with a Hedgehog Attention mechanism to model both local texture and long-range dependencies, and introduces a distillation-based large-kernel module to preserve high-frequency structure without heavy computation. In addition, we employ cross-layer parameter sharing to further reduce complexity. On Manga109 ($4\times$), UCAN-L achieves 31.63 dB PSNR with only 48.4G MACs, surpassing recent lightweight models. On BSDS100, UCAN attains 27.79 dB, outperforming methods with significantly larger models. Extensive experiments show that UCAN achieves a superior trade-off between accuracy, efficiency, and scalability, making it well-suited for practical high-resolution image restoration.
### Title:
          STAIRS-Former: Spatio-Temporal Attention with Interleaved Recursive Structure Transformer for Offline Multi-task Multi-agent Reinforcement Learning
 - **Authors:** Jiwon Jeon, Myungsik Cho, Youngchul Sung
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Offline multi-agent reinforcement learning (MARL) with multi-task datasets is challenging due to varying numbers of agents across tasks and the need to generalize to unseen scenarios. Prior works employ transformers with observation tokenization and hierarchical skill learning to address these issues. However, they underutilize the transformer attention mechanism for inter-agent coordination and rely on a single history token, which limits their ability to capture long-horizon temporal dependencies in partially observable MARL settings. In this paper, we propose STAIRS-Former, a transformer architecture augmented with spatial and temporal hierarchies that enables effective attention over critical tokens while capturing long interaction histories. We further introduce token dropout to enhance robustness and generalization across varying agent populations. Extensive experiments on diverse multi-agent benchmarks, including SMAC, SMAC-v2, MPE, and MaMuJoCo, with multi-task datasets demonstrate that STAIRS-Former consistently outperforms prior methods and achieves new state-of-the-art performance.
### Title:
          Cross-Resolution Attention Network for High-Resolution PM2.5 Prediction
 - **Authors:** Ammar Kheder, Helmi Toropainen, Wenqing Peng, Samuel Antão, Zhi-Song Liu, Michael Boy
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers have achieved remarkable success in spatio-temporal prediction, but their scalability remains limited for ultra-high-resolution, continent-scale domains required in real-world environmental monitoring. A single European air-quality map at 1 km resolution comprises 29 million pixels, far beyond the limits of naive self-attention. We introduce CRAN-PM, a dual-branch Vision Transformer that leverages cross-resolution attention to efficiently fuse global meteorological data (25 km) with local high-resolution PM2.5 at the current time (1 km). Instead of including physically driven factors like temperature and topography as input, we further introduce elevation-aware self-attention and wind-guided cross-attention to force the network to learn physically consistent feature representations for PM2.5 forecasting. CRAN-PM is fully trainable and memory-efficient, generating the complete 29-million-pixel European map in 1.8 seconds on a single GPU. Evaluated on daily PM2.5 forecasting throughout Europe in 2022 (362 days, 2,971 European Environment Agency (EEA) stations), it reduces RMSE by 4.7% at T+1 and 10.7% at T+3 compared to the best single-scale baseline, while reducing bias in complex terrain by 36%.
### Title:
          Compression Favors Consistency, Not Truth: When and Why Language Models Prefer Correct Information
 - **Authors:** Konstantin Krestnikov
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Why do language models sometimes prefer correct statements even when trained on mixed-quality data? We introduce the Compression--Consistency Principle: next-token prediction favors hypotheses that allow shorter and more internally consistent descriptions of the training data. Truth bias emerges only when false alternatives are structurally harder to compress. We test this using small GPT-2-style character-level transformers (3.5M--86M parameters) on synthetic math corpora with controlled mixtures of correct and incorrect rules. In the random-error setting, models strongly prefer correct completions in paired evaluation: 83.1% accuracy at balanced data and 67.0% even when correct rules appear in only 10% of the corpus. Replacing random errors with a coherent but mathematically incorrect rule system largely eliminates the preference (near-chance accuracy). In a more natural-language-like synthetic world, the effect is weaker but still present (57.7%). Additional experiments show that embedding verification steps can restore preference for correctness even at small scale, while increasing the number of consistent rules produces a graded improvement in accuracy. Our results suggest that what appears as a "truth bias" is largely a side effect of compression pressure and preference for internal consistency, rather than an intrinsic drive toward truth. Full code and data are available at this https URL.
### Title:
          Large Language Models for Biomedical Article Classification
 - **Authors:** Jakub Proboszcz, Paweł Cichosz
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents a systematic and in-depth investigation of the utility of large language models as text classifiers for biomedical article classification. The study uses several small and mid-size open source models, as well as selected closed source ones, and is more comprehensive than most prior work with respect to the scope of evaluated configurations: different types of prompts, output processing methods for generating both class and class probability predictions, as well as few-shot example counts and selection methods. The performance of the most successful configurations is compared to that of conventional classification algorithms. The obtained average PR AUC over 15 challenging datasets above 0.4 for zero-shot prompting and nearly 0.5 for few-shot prompting comes close to that of the naïve Bayes classifier (0.5), the random forest algorithm (0.5 with default settings or 0.55 with hyperparameter tuning) and fine-tuned transformer models (0.5). These results confirm the utility of large language models as text classifiers for non-trivial domains and provide practical recommendations of the most promising setups, including in particular using output token probabilities for class probability prediction.
### Title:
          HELM: Hierarchical and Explicit Label Modeling with Graph Learning for Multi-Label Image Classification
 - **Authors:** Marjan Stoimchev, Boshko Koloski, Jurica Levatić, Dragi Kocev, Sašo Džeroski
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hierarchical multi-label classification (HMLC) is essential for modeling complex label dependencies in remote sensing. Existing methods, however, struggle with multi-path hierarchies where instances belong to multiple branches, and they rarely exploit unlabeled data. We introduce HELM (\textit{Hierarchical and Explicit Label Modeling}), a novel framework that overcomes these limitations. HELM: (i) uses hierarchy-specific class tokens within a Vision Transformer to capture nuanced label interactions; (ii) employs graph convolutional networks to explicitly encode the hierarchical structure and generate hierarchy-aware embeddings; and (iii) integrates a self-supervised branch to effectively leverage unlabeled imagery. We perform a comprehensive evaluation on four remote sensing image (RSI) datasets (UCM, AID, DFC-15, MLRSNet). HELM achieves state-of-the-art performance, consistently outperforming strong baselines in both supervised and semi-supervised settings, demonstrating particular strength in low-label scenarios.
### Title:
          Locating Demographic Bias at the Attention-Head Level in CLIP's Vision Encoder
 - **Authors:** Alaa Yasser, Kittipat Phunjanna, Marcos Escudero Viñolo, Catarina Barata, Jenny Benois-Pineau
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard fairness audits of foundation models quantify that a model is biased, but not where inside the network the bias resides. We propose a mechanistic fairness audit that combines projected residual-stream decomposition, zero-shot Concept Activation Vectors, and bias-augmented TextSpan analysis to locate demographic bias at the level of individual attention heads in vision transformers. As a feasibility case study, we apply this pipeline to the CLIP ViT-L-14 encoder on 42 profession classes of the FACET benchmark, auditing both gender and age bias. For gender, the pipeline identifies four terminal-layer heads whose ablation reduces global bias (Cramer's V: 0.381 -> 0.362) while marginally improving accuracy (+0.42%); a layer-matched random control confirms that this effect is specific to the identified heads. A single head in the final layer contributes to the majority of the reduction in the most stereotyped classes, and class-level analysis shows that corrected predictions shift toward the correct occupation. For age, the same pipeline identifies candidate heads, but ablation produces weaker and less consistent effects, suggesting that age bias is encoded more diffusely than gender bias in this model. These results provide preliminary evidence that head-level bias localisation is feasible for discriminative vision encoders and that the degree of localisability may vary across protected attributes. keywords: Bias . CLIP . Mechanistic Interpretability . Vision Transformer . Fairness
### Title:
          Towards High-Fidelity CAD Generation via LLM-Driven Program Generation and Text-Based B-Rep Primitive Grounding
 - **Authors:** Jiahao Li, Qingwang Zhang, Qiuyu Chen, Guozhan Qiu, Yunzhong Lou, Xiangdong Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The field of Computer-Aided Design (CAD) generation has made significant progress in recent years. Existing methods typically fall into two separate categorie: parametric CAD modeling and direct boundary representation (B-Rep) synthesis. In modern feature-based CAD systems, parametric modeling and B-Rep are inherently intertwined, as advanced parametric operations (e.g., fillet and chamfer) require explicit selection of B-Rep geometric primitives, and the B-Rep itself is derived from parametric operations. Consequently, this paradigm gap remains a critical factor limiting AI-driven CAD modeling for complex industrial product design. This paper present FutureCAD, a novel text-to-CAD framework that leverages large language models (LLMs) and a B-Rep grounding transformer (BRepGround) for high-fidelity CAD generation. Our method generates executable CadQuery scripts, and introduces a text-based query mechanism that enables the LLM to specify geometric selections via natural language, which BRepGround then grounds to the target primitives. To train our framework, we construct a new dataset comprising real-world CAD models. For the LLM, we apply supervised fine-tuning (SFT) to establish fundamental CAD generation capabilities, followed by reinforcement learning (RL) to improve generalization. Experiments show that FutureCAD achieves state-of-the-art CAD generation performance.
### Title:
          Risk-Based Dynamic Thermal Rating in Distribution Transformers via Probabilistic Forecasting
 - **Authors:** Scott Angus, Jethro Browell, David Greenwood, Matthew Deakin
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low voltage (LV) distribution transformers face accelerating demand growth while replacement lead times and costs continue to rise, making improved utilisation of existing assets essential. Static and conservative protection devices (PDs) in distribution transformers are inflexible and limit the available headroom of the transformer. This paper presents a probabilistic framework for dynamically forecasting optimal thermal protection settings. The proposed approach directly predicts the day-ahead scale factor which maximises the dynamic thermal rating of the transformer from historical load, temperature, and metadata using clustered quantile regression models trained on 644 UK LV transformers. Probabilistic forecasting quantifies overheating risk directly through the prediction percentile, enabling risk-informed operational decisions. Results show a 10--12\% additional capacity gain compared to static settings, with hotspot temperature risk matching the selected percentile, including under realistic temperature forecast errors. These results demonstrate a practical approach for distribution network operators to take advantage of PDs with adaptive settings to maximise capacity and manage risk on operational time scales.
### Title:
          EnTransformer: A Deep Generative Transformer for Multivariate Probabilistic Forecasting
 - **Authors:** Rajdeep Pathak, Rahul Goswami, Madhurima Panja, Palash Ghosh, Tanujit Chakraborty
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable uncertainty quantification is critical in multivariate time series forecasting problems arising in domains such as energy systems and transportation networks, among many others. Although Transformer-based architectures have recently achieved strong performance for sequence modeling, most probabilistic forecasting approaches rely on restrictive parametric likelihoods or quantile-based objectives. They can struggle to capture complex joint predictive distributions across multiple correlated time series. This work proposes EnTransformer, a deep generative forecasting framework that integrates engression, a stochastic learning paradigm for modeling conditional distributions, with the expressive sequence modeling capabilities of Transformers. The proposed approach injects stochastic noise into the model representation and optimizes an energy-based scoring objective to directly learn the conditional predictive distribution without imposing parametric assumptions. This design enables EnTransformer to generate coherent multivariate forecast trajectories while preserving Transformers' capacity to effectively model long-range temporal dependencies and cross-series interactions. We evaluate our proposed EnTransformer on several widely used benchmarks for multivariate probabilistic forecasting, including Electricity, Traffic, Solar, Taxi, KDD-cup, and Wikipedia datasets. Experimental results demonstrate that EnTransformer produces well-calibrated probabilistic forecasts and consistently outperforms the benchmark models.
### Title:
          Exhaustive Circuit Mapping of a Single-Cell Foundation Model Reveals Massive Redundancy, Heavy-Tailed Hub Architecture, and Layer-Dependent Differentiation Control
 - **Authors:** Ihor Kendiukhov
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability of biological foundation models has relied on selective feature sampling, pairwise interaction testing, and observational trajectory analysis. Each of these can introduce systematic bias. Here we present three experiments that address these limitations through exhaustive circuit tracing, higher order combinatorial ablation, and causal trajectory steering in Geneformer, a transformer based single cell foundation model. First, exhaustive tracing of all 4065 active sparse autoencoder features at layer 5 yields 1393850 significant downstream edges, a 27 fold expansion over selective sampling. This reveals a heavy tailed hub distribution in which 1.8 percent of features account for disproportionate connectivity and 40 percent of the top 20 hubs lack biological annotation. These results indicate systematic annotation bias in prior selective analyses. Second, three way combinatorial ablation across 8 feature triplets shows that redundancy deepens monotonically with interaction order, with a three way ratio of 0.59 versus a pairwise ratio of 0.74, and with zero synergy. This confirms that the model architecture is subadditive at all tested orders. Third, trajectory guided feature steering establishes a causal link between layer position and differentiation directionality. Late layer features at L17 consistently push cell states toward maturity, with fraction positive equal to 1.0. Early and mid layer features at L0 and L11 mostly push away from maturity, with fraction positive ranging from 0.00 to 0.58. Together these results move from correlation toward causal evidence for layer dependent control of cell state.
### Title:
          Statistical and structural identifiability in representation learning
 - **Authors:** Walter Nelson, Marco Fumero, Theofanis Karaletsos, Francesco Locatello
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Representation learning models exhibit a surprising stability in their internal representations. Whereas most prior work treats this stability as a single property, we formalize it as two distinct concepts: statistical identifiability (consistency of representations across runs) and structural identifiability (alignment of representations with some unobserved ground truth). Recognizing that perfect pointwise identifiability is generally unrealistic for modern representation learning models, we propose new model-agnostic definitions of statistical and structural near-identifiability of representations up to some error tolerance $\epsilon$. Leveraging these definitions, we prove a statistical $\epsilon$-near-identifiability result for the representations of models with nonlinear decoders, generalizing existing identifiability theory beyond last-layer representations in e.g. generative pre-trained transformers (GPTs) to near-identifiability of the intermediate representations of a broad class of models including (masked) autoencoders (MAEs) and supervised learners. Although these weaker assumptions confer weaker identifiability, we show that independent components analysis (ICA) can resolve much of the remaining linear ambiguity for this class of models, and validate and measure our near-identifiability claims empirically. With additional assumptions on the data-generating process, statistical identifiability extends to structural identifiability, yielding a simple and practical recipe for disentanglement: ICA post-processing of latent representations. On synthetic benchmarks, this approach achieves state-of-the-art disentanglement using a vanilla autoencoder. With a foundation model-scale MAE for cell microscopy, it disentangles biological variation from technical batch effects, substantially improving downstream generalization.
### Title:
          Pano360: Perspective to Panoramic Vision with Geometric Consistency
 - **Authors:** Zhengdong Zhu, Weiyi Xue, Zuyuan Yang, Wenlve Zhou, Zhiheng Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Prior panorama stitching approaches heavily rely on pairwise feature correspondences and are unable to leverage geometric consistency across multiple views. This leads to severe distortion and misalignment, especially in challenging scenes with weak textures, large parallax, and repetitive patterns. Given that multi-view geometric correspondences can be directly constructed in 3D space, making them more accurate and globally consistent, we extend the 2D alignment task to the 3D photogrammetric space. We adopt a novel transformer-based architecture to achieve 3D awareness and aggregate global information across all views. It directly utilizes camera poses to guide image warping for global alignment in 3D space and employs a multi-feature joint optimization strategy to compute the seams. Additionally, to establish an evaluation benchmark and train our network, we constructed a large-scale dataset of real-world scenes. Extensive experiments show that our method significantly outperforms existing alternatives in alignment accuracy and perceptual quality.
### Title:
          CLASP: Defending Hybrid Large Language Models Against Hidden State Poisoning Attacks
 - **Authors:** Alexandre Le Mercier, Thomas Demeester, Chris Develder
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State space models (SSMs) like Mamba have gained significant traction as efficient alternatives to Transformers, achieving linear complexity while maintaining competitive performance. However, Hidden State Poisoning Attacks (HiSPAs), a recently discovered vulnerability that corrupts SSM memory through adversarial strings, pose a critical threat to these architectures and their hybrid variants. Framing the HiSPA mitigation task as a binary classification problem at the token level, we introduce the CLASP model to defend against this threat. CLASP exploits distinct patterns in Mamba's block output embeddings (BOEs) and uses an XGBoost classifier to identify malicious tokens with minimal computational overhead. We consider a realistic scenario in which both SSMs and HiSPAs are likely to be used: an LLM screening résumés to identify the best candidates for a role. Evaluated on a corpus of 2,483 résumés totaling 9.5M tokens with controlled injections, CLASP achieves 95.9% token-level F1 score and 99.3% document-level F1 score on malicious tokens detection. Crucially, the model generalizes to unseen attack patterns: under leave-one-out cross-validation, performance remains high (96.9% document-level F1), while under clustered cross-validation with structurally novel triggers, it maintains useful detection capability (91.6% average document-level F1). Operating independently of any downstream model, CLASP processes 1,032 tokens per second with under 4GB VRAM consumption, potentially making it suitable for real-world deployment as a lightweight front-line defense for SSM-based and hybrid architectures. All code and detailed results are available at this https URL.
### Title:
          RDNet: Region Proportion-Aware Dynamic Adaptive Salient Object Detection Network in Optical Remote Sensing Images
 - **Authors:** Bin Wan, Runmin Cong, Xiaofei Zhou, Hao Fang, Yaoqi Sun, Sam Kwong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Salient object detection (SOD) in remote sensing images faces significant challenges due to large variations in object sizes, the computational cost of self-attention mechanisms, and the limitations of CNN-based extractors in capturing global context and long-range dependencies. Existing methods that rely on fixed convolution kernels often struggle to adapt to diverse object scales, leading to detail loss or irrelevant feature aggregation. To address these issues, this work aims to enhance robustness to scale variations and achieve precise object localization. We propose the Region Proportion-Aware Dynamic Adaptive Salient Object Detection Network (RDNet), which replaces the CNN backbone with the SwinTransformer for global context modeling and introduces three key modules: (1) the Dynamic Adaptive Detail-aware (DAD) module, which applies varied convolution kernels guided by object region proportions; (2) the Frequency-matching Context Enhancement (FCE) module, which enriches contextual information through wavelet interactions and attention; and (3) the Region Proportion-aware Localization (RPL) module, which employs cross-attention to highlight semantic details and integrates a Proportion Guidance (PG) block to assist the DAD module. By combining these modules, RDNet achieves robustness against scale variations and accurate localization, delivering superior detection performance compared with state-of-the-art methods.
### Title:
          HiAP: A Multi-Granular Stochastic Auto-Pruning Framework for Vision Transformers
 - **Authors:** Andy Li, Aiden Durrant, Milan Markovic, Georgios Leontidis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers require significant computational resources and memory bandwidth, severely limiting their deployment on edge devices. While recent structured pruning methods successfully reduce theoretical FLOPs, they typically operate at a single structural granularity and rely on complex, multi-stage pipelines with post-hoc thresholding to satisfy sparsity budgets. In this paper, we propose Hierarchical Auto-Pruning (HiAP), a continuous relaxation framework that discovers optimal sub-networks in a single end-to-end training phase without requiring manual importance heuristics or predefined per-layer sparsity targets. HiAP introduces stochastic Gumbel-Sigmoid gates at multiple granularities: macro-gates to prune entire attention heads and FFN blocks, and micro-gates to selectively prune intra-head dimensions and FFN neurons. By optimizing both levels simultaneously, HiAP addresses both the memory-bound overhead of loading large matrices and the compute-bound mathematical operations. HiAP naturally converges to stable sub-networks using a loss function that incorporates both structural feasibility penalties and analytical FLOPs. Extensive experiments on ImageNet demonstrate that HiAP organically discovers highly efficient architectures, and achieves a competitive accuracy-efficiency Pareto frontier for models like DeiT-Small, matching the performance of sophisticated multi-stage methods while significantly simplifying the deployment pipeline.
### Title:
          One Model, Many Budgets: Elastic Latent Interfaces for Diffusion Transformers
 - **Authors:** Moayed Haji-Ali, Willi Menapace, Ivan Skorokhodov, Dogyun Park, Anil Kag, Michael Vasilkovsky, Sergey Tulyakov, Vicente Ordonez, Aliaksandr Siarohin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion transformers (DiTs) achieve high generative quality but lock FLOPs to image resolution, limiting principled latency-quality trade-offs, and allocate computation uniformly across input spatial tokens, wasting resource allocation to unimportant regions. We introduce Elastic Latent Interface Transformer (ELIT), a drop-in, DiT-compatible mechanism that decouples input image size from compute. Our approach inserts a latent interface, a learnable variable-length token sequence on which standard transformer blocks can operate. Lightweight Read and Write cross-attention layers move information between spatial tokens and latents and prioritize important input regions. By training with random dropping of tail latents, ELIT learns to produce importance-ordered representations with earlier latents capturing global structure while later ones contain information to refine details. At inference, the number of latents can be dynamically adjusted to match compute constraints. ELIT is deliberately minimal, adding two cross-attention layers while leaving the rectified flow objective and the DiT stack unchanged. Across datasets and architectures (DiT, U-ViT, HDiT, MM-DiT), ELIT delivers consistent gains. On ImageNet-1K 512px, ELIT delivers an average gain of $35.3\%$ and $39.6\%$ in FID and FDD scores. Project page: this https URL
### Title:
          Attend Before Attention: Efficient and Scalable Video Understanding via Autoregressive Gazing
 - **Authors:** Baifeng Shi, Stephanie Fu, Long Lian, Hanrong Ye, David Eigen, Aaron Reite, Boyi Li, Jan Kautz, Song Han, David M. Chan, Pavlo Molchanov, Trevor Darrell, Hongxu Yin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-modal large language models (MLLMs) have advanced general-purpose video understanding but struggle with long, high-resolution videos -- they process every pixel equally in their vision transformers (ViTs) or LLMs despite significant spatiotemporal redundancy. We introduce AutoGaze, a lightweight module that removes redundant patches before processed by a ViT or an MLLM. Trained with next-token prediction and reinforcement learning, AutoGaze autoregressively selects a minimal set of multi-scale patches that can reconstruct the video within a user-specified error threshold, eliminating redundancy while preserving information. Empirically, AutoGaze reduces visual tokens by 4x-100x and accelerates ViTs and MLLMs by up to 19x, enabling scaling MLLMs to 1K-frame 4K-resolution videos and achieving superior results on video benchmarks (e.g., 67.0% on VideoMME). Furthermore, we introduce HLVid: the first high-resolution, long-form video QA benchmark with 5-minute 4K-resolution videos, where an MLLM scaled with AutoGaze improves over the baseline by 10.1% and outperforms the previous best MLLM by 4.5%. Project page: this https URL.
## Keyword: autonomous driving
### Title:
          A Survey of Reasoning in Autonomous Driving Systems: Open Challenges and Emerging Paradigms
 - **Authors:** Kejin Yu, Yuhan Sun, Taiqiang Wu, Ruixu Zhang, Zhiqiang Lin, Yuxin Meng, Junjie Wang, Yujiu Yang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The development of high-level autonomous driving (AD) is shifting from perception-centric limitations to a more fundamental bottleneck, namely, a deficit in robust and generalizable reasoning. Although current AD systems manage structured environments, they consistently falter in long-tail scenarios and complex social interactions that require human-like judgment. Meanwhile, the advent of large language and multimodal models (LLMs and MLLMs) presents a transformative opportunity to integrate a powerful cognitive engine into AD systems, moving beyond pattern matching toward genuine comprehension. However, a systematic framework to guide this integration is critically lacking. To bridge this gap, we provide a comprehensive review of this emerging field and argue that reasoning should be elevated from a modular component to the system's cognitive core. Specifically, we first propose a novel Cognitive Hierarchy to decompose the monolithic driving task according to its cognitive and interactive complexity. Building on this, we further derive and systematize seven core reasoning challenges, such as the responsiveness-reasoning trade-off and social-game reasoning. Furthermore, we conduct a dual-perspective review of the state-of-the-art, analyzing both system-centric approaches to architecting intelligent agents and evaluation-centric practices for their validation. Our analysis reveals a clear trend toward holistic and interpretable "glass-box" agents. In conclusion, we identify a fundamental and unresolved tension between the high-latency, deliberative nature of LLM-based reasoning and the millisecond-scale, safety-critical demands of vehicle control. For future work, a primary objective is to bridge the symbolic-to-physical gap by developing verifiable neuro-symbolic architectures, robust reasoning under uncertainty, and scalable models for implicit social negotiation.
### Title:
          Radiometric fingerprinting of object surfaces using mobile laser scanning and semantic 3D road space models
 - **Authors:** Benedikt Schwab, Thomas H. Kolbe
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although semantic 3D city models are internationally available and becoming increasingly detailed, the incorporation of material information remains largely untapped. However, a structured representation of materials and their physical properties could substantially broaden the application spectrum and analytical capabilities for urban digital twins. At the same time, the growing number of repeated mobile laser scans of cities and their street spaces yields a wealth of observations influenced by the material characteristics of the corresponding surfaces. To leverage this information, we propose radiometric fingerprints of object surfaces by grouping LiDAR observations reflected from the same semantic object under varying distances, incident angles, environmental conditions, sensors, and scanning campaigns. Our study demonstrates how 312.4 million individual beams acquired across four campaigns using five LiDAR sensors on the Audi Autonomous Driving Dataset (A2D2) vehicle can be automatically associated with 6368 individual objects of the semantic 3D city model. The model comprises a comprehensive and semantic representation of four inner-city streets at Level of Detail (LOD) 3 with centimeter-level accuracy. It is based on the CityGML 3.0 standard and enables fine-grained sub-differentiation of objects. The extracted radiometric fingerprints for object surfaces reveal recurring intra-class patterns that indicate class-dominant materials. The semantic model, the method implementations, and the developed geodatabase solution 3DSensorDB are released under: this https URL
### Title:
          DriveXQA: Cross-modal Visual Question Answering for Adverse Driving Scene Understanding
 - **Authors:** Mingzhe Tao, Ruiping Liu, Junwei Zheng, Yufan Chen, Kedi Ying, M. Saquib Sarfraz, Kailun Yang, Jiaming Zhang, Rainer Stiefelhagen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fusing sensors with complementary modalities is crucial for maintaining a stable and comprehensive understanding of abnormal driving scenes. However, Multimodal Large Language Models (MLLMs) are underexplored for leveraging multi-sensor information to understand adverse driving scenarios in autonomous vehicles. To address this gap, we propose the DriveXQA, a multimodal dataset for autonomous driving VQA. In addition to four visual modalities, five sensor failure cases, and five weather conditions, it includes $102,505$ QA pairs categorized into three types: global scene level, allocentric level, and ego-vehicle centric level. Since no existing MLLM framework adopts multiple complementary visual modalities as input, we design MVX-LLM, a token-efficient architecture with a Dual Cross-Attention (DCA) projector that fuses the modalities to alleviate information redundancy. Experiments demonstrate that our DCA achieves improved performance under challenging conditions such as foggy (GPTScore: $53.5$ vs. $25.1$ for the baseline). The established dataset and source code will be made publicly available.
### Title:
          Zero-Shot Cross-City Generalization in End-to-End Autonomous Driving: Self-Supervised versus Supervised Representations
 - **Authors:** Fatemeh Naeinian, Ali Hamza, Haoran Zhu, Anna Choromanska
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving models are typically trained on multi-city datasets using supervised ImageNet-pretrained backbones, yet their ability to generalize to unseen cities remains largely unexamined. When training and evaluation data are geographically mixed, models may implicitly rely on city-specific cues, masking failure modes that would occur under real domain shifts when generalizing to new locations. In this work we investigate zero-shot cross-city generalization in end-to-end trajectory planning and ask whether self-supervised visual representations improve transfer across cities. We conduct a comprehensive study by integrating self-supervised backbones (I-JEPA, DINOv2, and MAE) into planning frameworks. We evaluate performance under strict geographic splits on nuScenes in the open-loop setting and on NAVSIM in the closed-loop evaluation protocol. Our experiments reveal a substantial generalization gap when transferring models relying on traditional supervised backbones across cities with different road topologies and driving conventions, particularly when transferring from right-side to left-side driving environments. Self-supervised representation learning reduces this gap. In open-loop evaluation, a supervised backbone exhibits severe inflation when transferring from Boston to Singapore (L2 displacement ratio 9.77x, collision ratio 19.43x), whereas domain-specific self-supervised pretraining reduces this to 1.20x and 0.75x respectively. In closed-loop evaluation, self-supervised pretraining improves PDMS by up to 4 percent for all single-city training cities. These results show that representation learning strongly influences the robustness of cross-city planning and establish zero-shot geographic transfer as a necessary test for evaluating end-to-end autonomous driving systems.
### Title:
          Risk-Controllable Multi-View Diffusion for Driving Scenario Generation
 - **Authors:** Hongyi Lin, Wenxiu Shi, Heye Huang, Dingyi Zhuang, Song Zhang, Yang Liu, Xiaobo Qu, Jinhua Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating safety-critical driving scenarios is crucial for evaluating and improving autonomous driving systems, but long-tail risky situations are rarely observed in real-world data and difficult to specify through manual scenario design. Existing generative approaches typically treat risk as an after-the-fact label and struggle to maintain geometric consistency in multi-view driving scenes. We present RiskMV-DPO, a general and systematic pipeline for physically-informed, risk-controllable multi-view scenario generation. By integrating target risk levels with physically-grounded risk modeling, we autonomously synthesize diverse and high-stakes dynamic trajectories that serve as explicit geometric anchors for a diffusion-based video generator. To ensure spatial-temporal coherence and geometric fidelity, we introduce a geometry-appearance alignment module and a region-aware direct preference optimization (RA-DPO) strategy with motion-aware masking to focus learning on localized dynamic this http URL on the nuScenes dataset show that RiskMV-DPO can freely generate a wide spectrum of diverse long-tail scenarios while maintaining state-of-the-art visual quality, improving 3D detection mAP from 18.17 to 30.50 and reducing FID to 15.70. Our work shifts the role of world models from passive environment prediction to proactive, risk-controllable synthesis, providing a scalable toolchain for the safety-oriented development of embodied intelligence.
### Title:
          R4Det: 4D Radar-Camera Fusion for High-Performance 3D Object Detection
 - **Authors:** Zhongyu Xia, Yousen Tang, Yongtao Wang, Zhifeng Wang, Weijun Qin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 4D radar-camera sensing configuration has gained increasing importance in autonomous driving. However, existing 3D object detection methods that fuse 4D Radar and camera data confront several challenges. First, their absolute depth estimation module is not robust and accurate enough, leading to inaccurate 3D localization. Second, the performance of their temporal fusion module will degrade dramatically or even fail when the ego vehicle's pose is missing or inaccurate. Third, for some small objects, the sparse radar point clouds may completely fail to reflect from their surfaces. In such cases, detection must rely solely on visual unimodal priors. To address these limitations, we propose R4Det, which enhances depth estimation quality via the Panoramic Depth Fusion module, enabling mutual reinforcement between absolute and relative depth. For temporal fusion, we design a Deformable Gated Temporal Fusion module that does not rely on the ego vehicle's pose. In addition, we built an Instance-Guided Dynamic Refinement module that extracts semantic prototypes from 2D instance guidance. Experiments show that R4Det achieves state-of-the-art 3D object detection results on the TJ4DRadSet and VoD datasets.
