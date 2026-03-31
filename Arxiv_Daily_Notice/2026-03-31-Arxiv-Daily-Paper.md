# Showing new listings for Tuesday, 31 March 2026
## Keyword: SLAM
### Title:
          Unblur-SLAM: Dense Neural SLAM for Blurry Inputs
 - **Authors:** Qi Zhang, Denis Rozumny, Francesco Girlanda, Sezer Karaoglu, Marc Pollefeys, Theo Gevers, Martin R. Oswald
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose Unblur-SLAM, a novel RGB SLAM pipeline for sharp 3D reconstruction from blurred image inputs. In contrast to previous work, our approach is able to handle different types of blur and demonstrates state-of-the-art performance in the presence of both motion blur and defocus blur. Moreover, we adjust the computation effort with the amount of blur in the input image. As a first stage, our method uses a feed-forward image deblurring model for which we propose a suitable training scheme that can improve both tracking and mapping modules. Frames that are successfully deblurred by the feed-forward network obtain refined poses and depth through local-global multi-view optimization and loop closure. Frames that fail the first stage deblurring are directly modeled through the global 3DGS representation and an additional blur network to model multiple blurred sub-frames and simulate the blur formation process in 3D space, thereby learning sharp details and refined sub-frame poses. Experiments on several real-world datasets demonstrate consistent improvements in both pose estimation and sharp reconstruction results of geometry and texture.
### Title:
          GS3LAM: Gaussian Semantic Splatting SLAM
 - **Authors:** Linfei Li, Lin Zhang, Zhong Wang, Ying Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recently, the multi-modal fusion of RGB, depth, and semantics has shown great potential in dense Simultaneous Localization and Mapping (SLAM). However, a prerequisite for generating consistent semantic maps is the availability of dense, efficient, and scalable scene representations. Existing semantic SLAM systems based on explicit representations are often limited by resolution and an inability to predict unknown areas. Conversely, implicit representations typically rely on time-consuming ray tracing, failing to meet real-time requirements. Fortunately, 3D Gaussian Splatting (3DGS) has emerged as a promising representation that combines the efficiency of point-based methods with the continuity of geometric structures. To this end, we propose GS3LAM, a Gaussian Semantic Splatting SLAM framework that processes multimodal data to render consistent, dense semantic maps in real-time. GS3LAM models the scene as a Semantic Gaussian Field (SG-Field) and jointly optimizes camera poses and the field via multimodal error constraints. Furthermore, a Depth-adaptive Scale Regularization (DSR) scheme is introduced to resolve misalignments between scale-invariant Gaussians and geometric surfaces. To mitigate catastrophic forgetting, we propose a Random Sampling-based Keyframe Mapping (RSKM) strategy, which demonstrates superior performance over common local covisibility optimization methods. Extensive experiments on benchmark datasets show that GS3LAM achieves increased tracking robustness, superior rendering quality, and enhanced semantic precision compared to state-of-the-art methods. Source code is available at this https URL.
### Title:
          On the Role of Encoder Depth: Pruning Whisper and LoRA Fine-Tuning in SLAM-ASR
 - **Authors:** Ganesh Pavan Kartikeya Bharadwaj Kolluri, Michael Kampouridis, Ravi Shekhar
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic speech recognition (ASR) has advanced rapidly in recent years, driven by large-scale pretrained models and end-to-end architectures such as SLAM-ASR. A key component of SLAM-ASR systems is the Whisper speech encoder, which provides robust acoustic representations. While model pruning has been explored for the full Whisper encoder-decoder architecture, its impact within the SLAM-ASR setting remains under-investigated. In this work, we analyze the effects of layer pruning in the Whisper encoder when used as the acoustic backbone of SLAM-ASR. We further examine the extent to which LoRA-based fine-tuning can recover performance degradation caused by pruning. Experiments conducted across three Whisper variants (Small, Medium, Large-v2), three languages representing distinct resource levels (Danish, Dutch, English), and over 200 training runs demonstrate that pruning two encoder layers causes only 2-4% WER degradation, and that combining this pruning with LoRA adaptation consistently outperforms the unpruned baseline while reducing total parameters by 7-14%. Moreover, our error analysis reveals that LoRA primarily compensates through the language model's linguistic priors, reducing total word errors by 11-21% for Dutch and English, with substitutions and deletions showing the largest reductions. However, for low-resource Danish, the reduction is smaller (4-7%), and LoRA introduces increased insertion errors, indicating that compensation effectiveness depends on the LLM's pre-existing language proficiency and available training data.
### Title:
          Ghost-FWL: A Large-Scale Full-Waveform LiDAR Dataset for Ghost Detection and Removal
 - **Authors:** Kazuma Ikeda, Ryosei Hara, Rokuto Nagata, Ozora Sako.Zihao Ding, Takahiro Kado, Ibuki Fujioka, Taro Beppu, Mariko Isogawa, Kentaro Yoshioka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR has become an essential sensing modality in autonomous driving, robotics, and smart-city applications. However, ghost points (or ghosts), which are false reflections caused by multi-path laser returns from glass and reflective surfaces, severely degrade 3D mapping and localization accuracy. Prior ghost removal relies on geometric consistency in dense point clouds, failing on mobile LiDAR's sparse, dynamic data. We address this by exploiting full-waveform LiDAR (FWL), which captures complete temporal intensity profiles rather than just peak distances, providing crucial cues for distinguishing ghosts from genuine reflections in mobile scenarios. As this is a new task, we present Ghost-FWL, the first and largest annotated mobile FWL dataset for ghost detection and removal. Ghost-FWL comprises 24K frames across 10 diverse scenes with 7.5 billion peak-level annotations, which is 100x larger than existing annotated FWL datasets. Benefiting from this large-scale dataset, we establish a FWL-based baseline model for ghost detection and propose FWL-MAE, a masked autoencoder for efficient self-supervised representation learning on FWL data. Experiments show that our baseline outperforms existing methods in ghost removal accuracy, and our ghost removal further enhances downstream tasks such as LiDAR-based SLAM (66% trajectory error reduction) and 3D object detection (50x false positive reduction). The dataset and code is publicly available and can be accessed via the project page: this https URL
## Keyword: odometry
### Title:
          An Annotation-to-Detection Framework for Autonomous and Robust Vine Trunk Localization in the Field by Mobile Agricultural Robots
 - **Authors:** Dimitrios Chatziparaschis, Elia Scudiero, Brent Sams, Konstantinos Karydis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The dynamic and heterogeneous nature of agricultural fields presents significant challenges for object detection and localization, particularly for autonomous mobile robots that are tasked with surveying previously unseen unstructured environments. Concurrently, there is a growing need for real-time detection systems that do not depend on large-scale manually labeled real-world datasets. In this work, we introduce a comprehensive annotation-to-detection framework designed to train a robust multi-modal detector using limited and partially labeled training data. The proposed methodology incorporates cross-modal annotation transfer and an early-stage sensor fusion pipeline, which, in conjunction with a multi-stage detection architecture, effectively trains and enhances the system's multi-modal detection capabilities. The effectiveness of the framework was demonstrated through vine trunk detection in novel vineyard settings that featured diverse lighting conditions and varying crop densities to validate performance. When integrated with a customized multi-modal LiDAR and Odometry Mapping (LOAM) algorithm and a tree association module, the system demonstrated high-performance trunk localization, successfully identifying over 70% of trees in a single traversal with a mean distance error of less than 0.37m. The results reveal that by leveraging multi-modal, incremental-stage annotation and training, the proposed framework achieves robust detection performance regardless of limited starting annotations, showcasing its potential for real-world and near-ground agricultural applications.
### Title:
          Motion as a Sensing Modality for Metric Scale in Monocular Visual-Inertial Odometry
 - **Authors:** Hadush Hailu, Bruk Gebregziabher
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular visual-inertial odometry (VIO) cannot recover metric scale from vision alone; scale must be resolved through inertial measurements. We present a trajectory-dependent observability analysis showing that translational acceleration, produced by curvature, not constant-speed straight-line travel, is the fundamental source that couples scale to the inertial state. This relationship is formalized through the gravity-acceleration asymmetry in the IMU model, from which we derive rank conditions on the observability matrix and propose a lightweight excitation metric computable from raw IMU data. Controlled experiments on a differential-drive robot with a monocular camera and consumer-grade IMU validate the theory, with straight-line motion yielding 9.2% scale error, circular motion 6.4%, and figure-eight motion 4.8%, with excitation spanning four orders of magnitude. These results establish trajectory design as a practical mechanism for improving metric scale recovery.
## Keyword: livox
There is no result 
## Keyword: loam
### Title:
          An Annotation-to-Detection Framework for Autonomous and Robust Vine Trunk Localization in the Field by Mobile Agricultural Robots
 - **Authors:** Dimitrios Chatziparaschis, Elia Scudiero, Brent Sams, Konstantinos Karydis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The dynamic and heterogeneous nature of agricultural fields presents significant challenges for object detection and localization, particularly for autonomous mobile robots that are tasked with surveying previously unseen unstructured environments. Concurrently, there is a growing need for real-time detection systems that do not depend on large-scale manually labeled real-world datasets. In this work, we introduce a comprehensive annotation-to-detection framework designed to train a robust multi-modal detector using limited and partially labeled training data. The proposed methodology incorporates cross-modal annotation transfer and an early-stage sensor fusion pipeline, which, in conjunction with a multi-stage detection architecture, effectively trains and enhances the system's multi-modal detection capabilities. The effectiveness of the framework was demonstrated through vine trunk detection in novel vineyard settings that featured diverse lighting conditions and varying crop densities to validate performance. When integrated with a customized multi-modal LiDAR and Odometry Mapping (LOAM) algorithm and a tree association module, the system demonstrated high-performance trunk localization, successfully identifying over 70% of trees in a single traversal with a mean distance error of less than 0.37m. The results reveal that by leveraging multi-modal, incremental-stage annotation and training, the proposed framework achieves robust detection performance regardless of limited starting annotations, showcasing its potential for real-world and near-ground agricultural applications.
## Keyword: lidar
### Title:
          An Annotation-to-Detection Framework for Autonomous and Robust Vine Trunk Localization in the Field by Mobile Agricultural Robots
 - **Authors:** Dimitrios Chatziparaschis, Elia Scudiero, Brent Sams, Konstantinos Karydis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The dynamic and heterogeneous nature of agricultural fields presents significant challenges for object detection and localization, particularly for autonomous mobile robots that are tasked with surveying previously unseen unstructured environments. Concurrently, there is a growing need for real-time detection systems that do not depend on large-scale manually labeled real-world datasets. In this work, we introduce a comprehensive annotation-to-detection framework designed to train a robust multi-modal detector using limited and partially labeled training data. The proposed methodology incorporates cross-modal annotation transfer and an early-stage sensor fusion pipeline, which, in conjunction with a multi-stage detection architecture, effectively trains and enhances the system's multi-modal detection capabilities. The effectiveness of the framework was demonstrated through vine trunk detection in novel vineyard settings that featured diverse lighting conditions and varying crop densities to validate performance. When integrated with a customized multi-modal LiDAR and Odometry Mapping (LOAM) algorithm and a tree association module, the system demonstrated high-performance trunk localization, successfully identifying over 70% of trees in a single traversal with a mean distance error of less than 0.37m. The results reveal that by leveraging multi-modal, incremental-stage annotation and training, the proposed framework achieves robust detection performance regardless of limited starting annotations, showcasing its potential for real-world and near-ground agricultural applications.
### Title:
          Physics-Aware Diffusion for LiDAR Point Cloud Densification
 - **Authors:** Zeping Zhang, Robert Laganière
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR perception is severely limited by the distance-dependent sparsity of distant objects. While diffusion models can recover dense geometry, they suffer from prohibitive latency and physical hallucinations manifesting as ghost points. We propose Scanline-Consistent Range-Aware Diffusion, a framework that treats densification as probabilistic refinement rather than generation. By leveraging Partial Diffusion (SDEdit) on a coarse prior, we achieve high-fidelity results in just 156ms. Our novel Ray-Consistency loss and Negative Ray Augmentation enforce sensor physics to suppress artifacts. Our method achieves state-of-the-art results on KITTI-360 and nuScenes, directly boosting off-the-shelf 3D detectors without retraining. Code will be made available.
### Title:
          Autonomous overtaking trajectory optimization using reinforcement learning and opponent pose estimation
 - **Authors:** Matej Rene Cihlar, Luka Šiktar, Branimir Ćaran, Marko Švaco
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vehicle overtaking is one of the most complex driving maneuvers for autonomous vehicles. To achieve optimal autonomous overtaking, driving systems rely on multiple sensors that enable safe trajectory optimization and overtaking efficiency. This paper presents a reinforcement learning mechanism for multi-agent autonomous racing environments, enabling overtaking trajectory optimization, based on LiDAR and depth image data. The developed reinforcement learning agent uses pre-generated raceline data and sensor inputs to compute the steering angle and linear velocity for optimal overtaking. The system uses LiDAR with a 2D detection algorithm and a depth camera with YOLO-based object detection to identify the vehicle to be overtaken and its pose. The LiDAR and the depth camera detection data are fused using a UKF for improved opponent pose estimation and trajectory optimization for overtaking in racing scenarios. The results show that the proposed algorithm successfully performs overtaking maneuvers in both simulation and real-world experiments, with pose estimation RMSE of (0.0816, 0.0531) m in (x, y).
### Title:
          Robust Global-Local Behavior Arbitration via Continuous Command Fusion Under LiDAR Errors
 - **Authors:** Mohamed Elgouhary, Amr S. El-Wakeel
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modular autonomous driving systems must coordinate global progress objectives with local safety-driven reactions under imperfect sensing and strict real-time constraints. This paper presents a ROS2-native arbitration module that continuously fuses the outputs of two unchanged and interpretable controllers: a global reference-tracking controller based on Pure Pursuit and a reactive LiDAR-based Gap Follow controller. At each control step, both controllers propose Ackermann commands, and a PPO-trained policy predicts a continuous gate from a compact feature observation to produce a single fused drive command, augmented with practical safety checks. For comparison under identical ROS topic inputs and control rate, we implement a lightweight sampling-based predictive baseline. Robustness is evaluated using a ROS2 impairment protocol that injects LiDAR noise, delay, and dropout, and additionally sweeps forward-cone false short-range outliers. In a repeatable close-proximity passing scenario, we report safe success and failure rates together with per-step end-to-end controller runtime as sensing stress increases. The study is intended as a command-level robustness evaluation in a modular ROS2 setting, not as a replacement for planning-level interaction reasoning.
### Title:
          TerraSeg: Self-Supervised Ground Segmentation for Any LiDAR
 - **Authors:** Ted Lentsch, Santiago Montiel-Marín, Holger Caesar, Dariu M. Gavrila
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR perception is fundamental to robotics, enabling machines to understand their environment in 3D. A crucial task for LiDAR-based scene understanding and navigation is ground segmentation. However, existing methods are either handcrafted for specific sensor configurations or rely on costly per-point manual labels, severely limiting their generalization and scalability. To overcome this, we introduce TerraSeg, the first self-supervised, domain-agnostic model for LiDAR ground segmentation. We train TerraSeg on OmniLiDAR, a unified large-scale dataset that aggregates and standardizes data from 12 major public benchmarks. Spanning almost 22 million raw scans across 15 distinct sensor models, OmniLiDAR provides unprecedented diversity for learning a highly generalizable ground model. To supervise training without human annotations, we propose PseudoLabeler, a novel module that generates high-quality ground and non-ground labels through self-supervised per-scan runtime optimization. Extensive evaluations demonstrate that, despite using no manual labels, TerraSeg achieves state-of-the-art results on nuScenes, SemanticKITTI, and Waymo Perception while delivering real-time performance. Our code and model weights are publicly available.
### Title:
          Online Inertia Tensor Identification for Non-Cooperative Spacecraft via Augmented UKF
 - **Authors:** Batu Candan, Simone Servadio
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous proximity operations, such as active debris removal and on-orbit servicing, require high-fidelity relative navigation solutions that remain robust in the presence of parametric uncertainty. Standard estimation frameworks typically assume that the target spacecraft's mass properties are known a priori; however, for non-cooperative or tumbling targets, these parameters are often unknown or uncertain, leading to rapid divergence in model-based propagators. This paper presents an augmented Unscented Kalman Filter (UKF) framework designed to jointly estimate the relative 6-DOF pose and the full inertia tensor of a non-cooperative target spacecraft. The proposed architecture fuses visual measurements from monocular vision-based Convolutional Neural Networks (CNN) with depth information from LiDAR to constrain the coupled rigid-body dynamics. By augmenting the state vector to include the six independent elements of the inertia tensor, the filter dynamically recovers the target's normalized mass distribution in real-time without requiring ground-based pre-calibration. To ensure numerical stability and physical consistency during the estimation of constant parameters, the filter employs an adaptive process noise formulation that prevents covariance collapse while allowing for the gradual convergence of the inertial parameters. Numerical validation is performed via Monte Carlo simulations, demonstrating that the proposed Augmented UKF enables the simultaneous convergence of kinematic states and inertial parameters, thereby facilitating accurate long-term trajectory prediction and robust guidance in non-cooperative deep-space environments.
### Title:
          S3KF: Spherical State-Space Kalman Filtering for Panoramic 3D Multi-Object Tracking
 - **Authors:** Zhongyuan Liu, Shaonan Yu, Jianping Li, Pengfei Wan, Xinhang Xu, Pengfei Wang, Maggie Y. Gao, Lihua Xie
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Panoramic multi-object tracking is important for industrial safety monitoring, wide-area robotic perception, and infrastructure-light deployment in large workspaces. In these settings, the sensing system must provide full-surround coverage, metric geometric cues, and stable target association under wide field-of-view distortion and occlusion. Existing image-plane trackers are tightly coupled to the camera projection and become unreliable in panoramic imagery, while conventional Euclidean 3D formulations introduce redundant directional parameters and do not naturally unify angular, scale, and depth estimation. In this paper, we present $\mathbf{S^3KF}$, a panoramic 3D multi-object tracking framework built on a motorized rotating LiDAR and a quad-fisheye camera rig. The key idea is a geometry-consistent state representation on the unit sphere $\mathbb{S}^2$, where object bearing is modeled by a two-degree-of-freedom tangent-plane parameterization and jointly estimated with box scale and depth dynamics. Based on this state, we derive an extended spherical Kalman filtering pipeline that fuses panoramic camera detections with LiDAR depth observations for multimodal tracking. We further establish a map-based ground-truth generation pipeline using wearable localization devices registered to a shared global LiDAR map, enabling quantitative evaluation without motion-capture infrastructure. Experiments on self-collected real-world sequences show decimeter-level planar tracking accuracy, improved identity continuity over a 2D panoramic baseline in dynamic scenes, and real-time onboard operation on a Jetson AGX Orin platform. These results indicate that the proposed framework is a practical solution for panoramic perception and industrial-scale multi-object this http URL project page can be found at this https URL.
### Title:
          Annotation-Free Detection of Drivable Areas and Curbs Leveraging LiDAR Point Cloud Maps
 - **Authors:** Fulong Ma, Daojie Peng, Jun Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Drivable areas and curbs are critical traffic elements for autonomous driving, forming essential components of the vehicle visual perception system and ensuring driving safety. Deep neural networks (DNNs) have significantly improved perception performance for drivable area and curb detection, but most DNN-based methods rely on large manually labeled datasets, which are costly, time-consuming, and expert-dependent, limiting their real-world application. Thus, we developed an automated training data generation module. Our previous work generated training labels using single-frame LiDAR and RGB data, suffering from occlusion and distant point cloud sparsity. In this paper, we propose a novel map-based automatic data labeler (MADL) module, combining LiDAR mapping/localization with curb detection to automatically generate training data for both tasks. MADL avoids occlusion and point cloud sparsity issues via LiDAR mapping, creating accurate large-scale datasets for DNN training. In addition, we construct a data review agent to filter the data generated by the MADL module, eliminating low-quality samples. Experiments on the KITTI, KITTI-CARLA and 3D-Curb datasets show that MADL achieves impressive performance compared to manual labeling, and outperforms traditional and state-of-the-art self-supervised methods in robustness and accuracy.
### Title:
          LiDAR for Crowd Management: Applications, Benefits, and Future Directions
 - **Authors:** Abdullah Khanfor (1), Chaima Zaghouani (2), Hakim Ghazzai (3), Ahmad Alsharoa (2), Gianluca Setti (3),  ((1) the College of Computer Science and Information Systems, Najran University, (2) the College of Innovation &amp; Technology, University of Michigan-Flint, (3) King Abdullah University of Science and Technology (KAUST))
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Light Detection and Ranging (LiDAR) technology offers significant advantages for effective crowd management. This article presents LiDAR technology and highlights its primary advantages over other monitoring technologies, including enhanced privacy, performance in various weather conditions, and precise 3D mapping. We present a general taxonomy of four key tasks in crowd management: crowd detection, counting, tracking, and behavior classification, with illustrative examples of LiDAR applications for each task. We identify challenges and open research directions, including the scarcity of dedicated datasets, sensor fusion requirements, artificial intelligence integration, and processing needs for LiDAR point clouds. This article offers actionable insights for developing crowd management solutions tailored to public safety applications.
### Title:
          Collision Avoidance Control for a Two-wheeled Vehicle under Stochastic Vibration using an Almost Sure Control Barrier Function
 - **Authors:** Taichi Arimura, Yuki Nishimura, Taichi Ikezaki, Daisuke Tabuchi
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In recent years, many control problems of autonomous mobile robots have been developed. In particular, the robots are required to be safe; that is, they need to be controlled to avoid colliding with people or objects while traveling. In addition, since safety should be ensured even under irregular disturbances, the control for safety is required to be effective for stochastic systems. In this study, we design an almost sure safety-critical control law, which ensures safety with probability one, for a two-wheeled vehicle based on the stochastic control barrier function approach. In the procedure, we also consider a system model using the relative distance measured by a 2D LiDAR. The validity of the proposed control scheme is confirmed by experiments of a collision avoidance problem for a two-wheeled vehicle under vibration.
### Title:
          UniDA3D: A Unified Domain-Adaptive Framework for Multi-View 3D Object Detection
 - **Authors:** Hongjing Wu, Cheng Chi, Jinlin Wu, Yanzhao Su, Zhen Lei, Wenqi Ren
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Camera-only 3D object detection is critical for autonomous driving, offering a cost-effective alternative to LiDAR based methods. In particular, multi-view 3D object detection has emerged as a promising direction due to its balanced trade-off between performance and cost. However, existing methods often suffer significant performance degradation under complex environmental conditions such as nighttime, fog, and rain, primarily due to their reliance on training data collected mostly in ideal conditions. To address this challenge, we propose UniDA3D, a unified domain-adaptive multi-view 3D object detector designed for robust perception under diverse adverse conditions. UniDA3D formulates nighttime, rainy, and foggy scenes as a unified multi target domain adaptation problem and leverages a novel query guided domain discrepancy mitigation (QDDM) module to align object features between source and target domains at both batch and global levels via query-centric adversarial and contrastive learning. Furthermore, we introduce a domain-adaptive teacher student training pipeline with an exponential-moving-average teacher and dynamically updated high-quality pseudo labels to enhance consistency learning and suppress background noise in unlabeled target domains. In contrast to prior approaches that require separate training for each condition, UniDA3D performs a single unified training process across multiple domains, enabling robust all-weather 3D perception. On a synthesized multi-view 3D benchmark constructed by generating nighttime, rainy, and foggy counterparts from nuScenes (nuScenes-Night, nuScenes-Rain, and nuScenes-Haze), UniDA3D consistently outperforms state of-the-art camera-only multi-view 3D detectors under extreme conditions, achieving substantial gains in mAP and NDS while maintaining real-time inference efficiency.
### Title:
          Octree-based Learned Point Cloud Geometry Compression: A Lossy Perspective
 - **Authors:** Kaiyu Zheng, Wei Gao, Huiming Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Octree-based context learning has recently become a leading method in point cloud compression. However, its potential on lossy compression remains undiscovered. The traditional lossy compression paradigm using lossless octree representation with quantization step adjustment may result in severe distortions due to massive missing points in quantization. Therefore, we analyze data characteristics of different point clouds and propose lossy approaches specifically. For object point clouds that suffer from quantization step adjustment, we propose a new leaf nodes lossy compression method, which achieves lossy compression by performing bit-wise coding and binary prediction on leaf nodes. For LiDAR point clouds, we explore variable rate approaches and propose a simple but effective rate control method. Experimental results demonstrate that the proposed leaf nodes lossy compression method significantly outperforms the previous octree-based method on object point clouds, and the proposed rate control method achieves about 1% bit error without finetuning on LiDAR point clouds.
### Title:
          Intelligent Road Condition Monitoring using 3D In-Air SONAR Sensing
 - **Authors:** Amber Cassimon, Robin Kerstens, Walter Daems, Jan Steckel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we investigate the capabilities of in-air 3D SONAR sensors for the monitoring of road surface conditions. Concretely, we consider two applications: Road material classification and Road damage detection and classification. While such tasks can be performed with other sensor modalities, such as camera sensors and LiDAR sensors, these sensor modalities tend to fail in harsh sensing conditions, such as heavy rain, smoke or fog. By using a sensing modality that is robust to such interference, we enable the creation of opportunistic sensing applications, where vehicles performing other tasks (garbage collection, mail delivery, etc.) can also be used to monitor the condition of the road. For these tasks, we use a single dataset, in which different types of damages are annotated, with labels including the material of the road surface. In the material classification task, we differentiate between three different road materials: Asphalt, Concrete and Element roads. In the damage detection and classification task, we determine if there is damage, and what type of damage (independent of material type), without localizing the damage. We are succesful in determining the road surface type from SONAR sensor data, with F1 scores approaching 90% on the test set, but find that for the detection of damages performace lags, with F1 score around 75%. From this, we conclude that SONAR sensing is a promising modality to include in opportunistic sensing-based pavement management systems, but that further research is needed to reach the desired accuracy.
### Title:
          Ghost-FWL: A Large-Scale Full-Waveform LiDAR Dataset for Ghost Detection and Removal
 - **Authors:** Kazuma Ikeda, Ryosei Hara, Rokuto Nagata, Ozora Sako.Zihao Ding, Takahiro Kado, Ibuki Fujioka, Taro Beppu, Mariko Isogawa, Kentaro Yoshioka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR has become an essential sensing modality in autonomous driving, robotics, and smart-city applications. However, ghost points (or ghosts), which are false reflections caused by multi-path laser returns from glass and reflective surfaces, severely degrade 3D mapping and localization accuracy. Prior ghost removal relies on geometric consistency in dense point clouds, failing on mobile LiDAR's sparse, dynamic data. We address this by exploiting full-waveform LiDAR (FWL), which captures complete temporal intensity profiles rather than just peak distances, providing crucial cues for distinguishing ghosts from genuine reflections in mobile scenarios. As this is a new task, we present Ghost-FWL, the first and largest annotated mobile FWL dataset for ghost detection and removal. Ghost-FWL comprises 24K frames across 10 diverse scenes with 7.5 billion peak-level annotations, which is 100x larger than existing annotated FWL datasets. Benefiting from this large-scale dataset, we establish a FWL-based baseline model for ghost detection and propose FWL-MAE, a masked autoencoder for efficient self-supervised representation learning on FWL data. Experiments show that our baseline outperforms existing methods in ghost removal accuracy, and our ghost removal further enhances downstream tasks such as LiDAR-based SLAM (66% trajectory error reduction) and 3D object detection (50x false positive reduction). The dataset and code is publicly available and can be accessed via the project page: this https URL
### Title:
          osmAG-Nav: A Hierarchical Semantic Topometric Navigation Stack for Robust Lifelong Indoor Autonomy
 - **Authors:** Yongqi Zhang, Jiajie Zhang, Chengqian Li, Fujing Xie, Sören Schwertfeger
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The deployment of mobile robots in large-scale, multi-floor environments demands navigation systems that achieve spatial scalability without compromising local kinematic precision. Traditional navigation stacks, reliant on monolithic occupancy grid maps, face severe bottlenecks in storage efficiency, cross-floor reasoning, and long-horizon planning. To address these limitations, this paper presents osmAG-Nav, a complete, open-source ROS2 navigation stack built upon the hierarchical semantic topometric OpenStreetMap Area Graph (osmAG) map standard. The system follows a "System of Systems" architecture that decouples global topological reasoning from local metric execution. A Hierarchical osmAG planner replaces dense grid searches with an LCA-anchored pipeline on a passage-centric graph whose edge costs derive from local raster traversability rather than Euclidean distance, yielding low-millisecond planning on long campus-scale routes. A Rolling Window mechanism rasterizes a fixed-size local metric grid around the robot, keeping the local costmap memory footprint independent of the total mapped area, while a Segmented Execution strategy dispatches intermediate goals to standard ROS2 controllers for smooth handoffs. System robustness is reinforced by a structure-aware LiDAR localization framework that filters dynamic clutter against permanent architectural priors. Extensive experiments on a real-world multi-story indoor-outdoor campus (>11,025 m^2) show that, on the same-floor benchmark subset, osmAG-Nav delivers up to 7816x lower planning latency than a grid-based baseline on long routes while maintaining low path-length overhead and lifelong localization stability. A single-floor long-range robot mission further validates the integrated stack reliability. The full stack is released as modular ROS2 Lifecycle Nodes.
### Title:
          A Self-Rotating Tri-Rotor UAV for Field of View Expansion and Autonomous Flight
 - **Authors:** Xiaobin Zhou, Zihao Zheng, Aoxu Jin, Lei Qiang, Bo Zhu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unmanned Aerial Vehicles (UAVs) perception relies on onboard sensors like cameras and LiDAR, which are limited by the narrow field of view (FoV). We present Self-Perception INertial Navigation Enabled Rotorcraft (SPINNER), a self-rotating tri-rotor UAV for the FoV expansion and autonomous flight. Without adding extra sensors or energy consumption, SPINNER significantly expands the FoV of onboard camera and LiDAR sensors through continuous spin motion, thereby enhancing environmental perception efficiency. SPINNER achieves full 3-dimensional position and roll--pitch attitude control using only three brushless motors, while adjusting the rotation speed via anti-torque plates design. To address the strong coupling, severe nonlinearity, and complex disturbances induced by spinning flight, we develop a disturbance compensation control framework that combines nonlinear model predictive control (MPC) with incremental nonlinear dynamic inversion. Experimental results demonstrate that SPINNER maintains robust flight under wind disturbances up to 4.8 \,m/s and achieves high-precision trajectory tracking at a maximum speed of 2.0\,m/s. Moreover, tests in parking garages and forests show that the rotational perception mechanism substantially improves FoV coverage and enhances perception capability of SPINNER.
### Title:
          Industrial3D: A Terrestrial LiDAR Point Cloud Dataset and CrossParadigm Benchmark for Industrial Infrastructure
 - **Authors:** Chao Yin, Hongzhe Yue, Qing Han, Difeng Hu, Zhenyu Liang, Fangzhou Lin, Bing Sun, Boyu Wang, Mingkai Li, Wei Yao, Jack C.P. Cheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated semantic understanding of dense point clouds is a prerequisite for Scan-to-BIM pipelines, digital twin construction, and as-built verification--core tasks in the digital transformation of the construction industry. Yet for industrial mechanical, electrical, and plumbing (MEP) facilities, this challenge remains largely unsolved: TLS acquisitions of water treatment plants, chiller halls, and pumping stations exhibit extreme geometric ambiguity, severe occlusion, and extreme class imbalance that architectural benchmarks (e.g., S3DIS or ScanNet) cannot adequately represent. We present Industrial3D, a terrestrial LiDAR dataset comprising 612 million expertly labelled points at 6 mm resolution from 13 water treatment facilities. At 6.6x the scale of the closest comparable MEP dataset, Industrial3D provides the largest and most demanding testbed for industrial 3D scene understanding to date. We further establish the first industrial cross-paradigm benchmark, evaluating nine representative methods across fully supervised, weakly supervised, unsupervised, and foundation model settings under a unified benchmark protocol. The best supervised method achieves 55.74% mIoU, whereas zero-shot Point-SAM reaches only 15.79%--a 39.95 percentage-point gap that quantifies the unresolved domain-transfer challenge for industrial TLS data. Systematic analysis reveals that this gap originates from a dual crisis: statistical rarity (215:1 imbalance, 3.5x more severe than S3DIS) and geometric ambiguity (tail-class points share cylindrical primitives with head-class pipes) that frequency-based re-weighting alone cannot resolve. Industrial3D, along with benchmark code and pre-trained models, will be publicly available at this https URL.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          RehearsalNeRF: Decoupling Intrinsic Neural Fields of Dynamic Illuminations for Scene Editing
 - **Authors:** Changyeon Won, Hyunjun Jung, Jungu Cho, Seonmi Park, Chi-Hoon Lee, Hae-Gon Jeon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although there has been significant progress in neural radiance fields, an issue on dynamic illumination changes still remains unsolved. Different from relevant works that parameterize time-variant/-invariant components in scenes, subjects' radiance is highly entangled with their own emitted radiance and lighting colors in spatio-temporal domain. In this paper, we present a new effective method to learn disentangled neural fields under the severe illumination changes, named RehearsalNeRF. Our key idea is to leverage scenes captured under stable lighting like rehearsal stages, easily taken before dynamic illumination occurs, to enforce geometric consistency between the different lighting conditions. In particular, RehearsalNeRF employs a learnable vector for lighting effects which represents illumination colors in a temporal dimension and is used to disentangle projected light colors from scene radiance. Furthermore, our RehearsalNeRF is also able to reconstruct the neural fields of dynamic objects by simply adopting off-the-shelf interactive masks. To decouple the dynamic objects, we propose a new regularization leveraging optical flow, which provides coarse supervision for the color disentanglement. We demonstrate the effectiveness of RehearsalNeRF by showing robust performances on novel view synthesis and scene editing under dynamic illumination conditions. Our source code and video datasets will be publicly available.
### Title:
          To View Transform or Not to View Transform: NeRF-based Pre-training Perspective
 - **Authors:** Hyeonjun Jeong, Juyeb Shin, Dongsuk Kum
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural radiance fields (NeRFs) have emerged as a prominent pre-training paradigm for vision-centric autonomous driving, which enhances 3D geometry and appearance understanding in a fully self-supervised manner. To apply NeRF-based pretraining to 3D perception models, recent approaches have simply applied NeRFs to volumetric features obtained from view transformation. However, coupling NeRFs with view transformation inherits conflicting priors; view transformation imposes discrete and rigid representations, whereas radiance fields assume continuous and adaptive functions. When these opposing assumptions are forced into a single pipeline, the misalignment surfaces as blurry and ambiguous 3D representations that ultimately limit 3D scene understanding. Moreover, the NeRF network for pre-training is discarded during downstream tasks, resulting in inefficient utilization of enhanced 3D representations through NeRF. In this paper, we propose a novel NeRF-Resembled Point-based 3D detector that can learn continuous 3D representation and thus avoid the misaligned priors from view transformation. NeRP3D preserves the pre-trained NeRF network regardless of the tasks, inheriting the principle of continuous 3D representation learning and leading to greater potentials for both scene reconstruction and detection tasks. Experiments on nuScenes dataset demonstrate that our proposed approach significantly improves previous state-of-the-art methods, outperforming not only pretext scene reconstruction tasks but also downstream detection tasks.
### Title:
          SVGS: Single-View to 3D Object Editing via Gaussian Splatting
 - **Authors:** Pengcheng Xue, Yan Tian, Qiutao Song, Ziyi Wang, Linyang He, Weiping Ding, Mahmoud Hassaballah, Karen Egiazarian, Wei-Fa Yang, Leszek Rutkowski
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-driven 3D scene editing has attracted considerable interest due to its convenience and user-friendliness. However, methods that rely on implicit 3D representations, such as Neural Radiance Fields (NeRF), while effective in rendering complex scenes, are hindered by slow processing speeds and limited control over specific regions of the scene. Moreover, existing approaches, including Instruct-NeRF2NeRF and GaussianEditor, which utilize multi-view editing strategies, frequently produce inconsistent results across different views when executing text instructions. This inconsistency can adversely affect the overall performance of the model, complicating the task of balancing the consistency of editing results with editing efficiency. To address these challenges, we propose a novel method termed Single-View to 3D Object Editing via Gaussian Splatting (SVGS), which is a single-view text-driven editing technique based on 3D Gaussian Splatting (3DGS). Specifically, in response to text instructions, we introduce a single-view editing strategy grounded in multi-view diffusion models, which reconstructs 3D scenes by leveraging only those views that yield consistent editing results. Additionally, we employ sparse 3D Gaussian Splatting as the 3D representation, which significantly enhances editing efficiency. We conducted a comparative analysis of SVGS against existing baseline methods across various scene settings, and the results indicate that SVGS outperforms its counterparts in both editing capability and processing speed, representing a significant advancement in 3D editing technology. For further details, please visit our project page at: this https URL.
## Keyword: mapping
### Title:
          Surface-Constrained Offline Warping with Contact-Aware Online Pose Projection for Safe Robotic Trajectory Execution
 - **Authors:** Farong Wang, Sai Swaminathan, Fei Liu
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robotic manipulation tasks that require repeated tool motion along curved surfaces frequently arise in surface finishing, inspection, and guided interaction. In practice, nominal motion primitives are often designed independently of the deployment surface and later reused across varying geometries. Directly tiling such primitives onto nonplanar surfaces introduces geometric inconsistencies, leading to interpenetration, orientation discontinuities, and cumulative drift over repeated cycles. We present a two-stage framework that separates geometric embedding from execution-level regulation. An offline surface-constrained warping operator embeds a nominal periodic primitive onto curved surfaces through asymmetric diffeomorphic deformation of dual-track waypoints and axis-consistent orientation completion, producing a surface-adapted reference trajectory. An online contact-aware projection operator then enforces bounded deviation relative to this reference using FSR-driven disturbance adaptation and a conic orientation safety constraint. Experiments across multiple analytic surface families and real-robot validation on a sinusoidal surface demonstrate improved geometric continuity, reduced large orientation jumps, and robust contact maintenance compared with direct tiling. These results show that decoupling offline geometric remapping from lightweight online projection enables stable and repeatable surface-embedded trajectory execution under sensor-lite feedbacks.
### Title:
          On the Carbon Footprint of Economic Research in the Age of Generative AI
 - **Authors:** Andres Alonso-Robisco, Carlos Esparcia, Francisco Jareño
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI); Computers and Society (cs.CY); General Economics (econ.GN)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative artificial intelligence (AI) is increasingly used to write and refactor research code, expanding computational workflows. At the same time, Green AI research has largely measured the footprint of models rather than the downstream workflows in which GenAI is a tool. We shift the unit of analysis from models to workflows and treat prompts as decision policies that allocate discretion between researcher and system, governing what is executed and when iteration stops. We contribute in two ways. First, we map the recent Green AI literature into seven themes: training footprint is the largest cluster, while inference efficiency and system level optimisation are growing rapidly, alongside measurement protocols, green algorithms, governance, and security and efficiency trade-offs. Second, we benchmark a modern economic survey workflow, an LDA-based literature mapping implemented with GenAI assisted coding and executed in a fixed cloud notebook, measuring runtime and estimated CO2e with CodeCarbon. Injecting generic green language into prompts has no reliable effect, whereas operational constraints and decision rule prompts deliver large and stable footprint reductions while preserving decision equivalent topic outputs. The results identify human in the loop governance as a practical lever to align GenAI productivity with environmental efficiency.
### Title:
          Brain-inspired AI for Edge Intelligence: a systematic review
 - **Authors:** Yingchao Cheng, Meijia Wang, Zhifeng Hao, Rajkumar Buyya
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Artificial Intelligence (cs.AI); Hardware Architecture (cs.AR); Operating Systems (cs.OS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Spiking Neural Networks (SNNs) promise to circumvent the severe Size, Weight, and Power (SWaP) constraints of edge intelligence, the field currently faces a "Deployment Paradox" where theoretical energy gains are frequently negated by the inefficiencies of mapping asynchronous, event-driven dynamics onto traditional von Neumann substrates. Transcending the reductionism of algorithm-only reviews, this survey adopts a rigorous system-level hardware-software co-design perspective to examine the 2020-2025 trajectory, specifically targeting the "last mile" technologies - from quantization methodologies to hybrid architectures - that translate biological plausibility into silicon reality. We critically dissect the interplay between training complexity (the dichotomy of direct learning vs. conversion), the "memory wall" bottlenecking stateful neuronal updates, and the critical software gap in neuromorphic compilation toolchains. Finally, we envision a roadmap to reconcile the fundamental "Sync-Async Mismatch," proposing the development of a standardized Neuromorphic OS as the foundational layer for realizing a ubiquitous, energy-autonomous Green Cognitive Substrate.
### Title:
          An Annotation-to-Detection Framework for Autonomous and Robust Vine Trunk Localization in the Field by Mobile Agricultural Robots
 - **Authors:** Dimitrios Chatziparaschis, Elia Scudiero, Brent Sams, Konstantinos Karydis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The dynamic and heterogeneous nature of agricultural fields presents significant challenges for object detection and localization, particularly for autonomous mobile robots that are tasked with surveying previously unseen unstructured environments. Concurrently, there is a growing need for real-time detection systems that do not depend on large-scale manually labeled real-world datasets. In this work, we introduce a comprehensive annotation-to-detection framework designed to train a robust multi-modal detector using limited and partially labeled training data. The proposed methodology incorporates cross-modal annotation transfer and an early-stage sensor fusion pipeline, which, in conjunction with a multi-stage detection architecture, effectively trains and enhances the system's multi-modal detection capabilities. The effectiveness of the framework was demonstrated through vine trunk detection in novel vineyard settings that featured diverse lighting conditions and varying crop densities to validate performance. When integrated with a customized multi-modal LiDAR and Odometry Mapping (LOAM) algorithm and a tree association module, the system demonstrated high-performance trunk localization, successfully identifying over 70% of trees in a single traversal with a mean distance error of less than 0.37m. The results reveal that by leveraging multi-modal, incremental-stage annotation and training, the proposed framework achieves robust detection performance regardless of limited starting annotations, showcasing its potential for real-world and near-ground agricultural applications.
### Title:
          Training-Free Diffusion-Driven Modeling of Pareto Set Evolution for Dynamic Multiobjective Optimization
 - **Authors:** Jian Guan, Huolong Wu, Zhenzhong Wang, Gary G. Yen, Min Jiang
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dynamic multiobjective optimization problems (DMOPs) feature time-varying objectives, which cause the Pareto optimal solution (POS) set to drift over time and make it difficult to maintain both convergence and diversity under limited response time. Many existing prediction-based dynamic multiobjective evolutionary algorithms (DMOEAs) either depend on learned models with nontrivial training cost or employ one-step population mapping, which may overlook the gradual nature of POS evolution. This paper proposes DD-DMOEA, a training-free diffusion-based dynamic response mechanism for DMOPs. The key idea is to treat the POS obtained in the previous environment as a "noisy" sample set and to guide its evolution toward the current POS through an analytically constructed multi-step denoising process. A knee-point-based auxiliary strategy is used to specify the target region in the new environment, and an explicit probability-density formulation is derived to compute the denoising update without neural training. To reduce the risk of misleading guidance caused by knee-point prediction errors, an uncertainty-aware scheme adaptively adjusts the guidance strength according to the historical prediction deviation. Experiments on the CEC2018 dynamic multiobjective benchmarks show that DD-DMOEA achieves competitive or better convergence-diversity performance and provides faster dynamic response than several state-of-the-art DMOEAs.
### Title:
          ReMemNav: A Rethinking and Memory-Augmented Framework for Zero-Shot Object Navigation
 - **Authors:** Feng Wu, Wei Zuo, Wenliang Yang, Jun Xiao, Yang Liu, Xinhua Zeng
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Zero-shot object navigation requires agents to locate unseen target objects in unfamiliar environments without prior maps or task-specific training which remains a significant challenge. Although recent advancements in vision-language models(VLMs) provide promising commonsense reasoning capabilities for this task, these models still suffer from spatial hallucinations, local exploration deadlocks, and a disconnect between high-level semantic intent and low-level control. In this regard, we propose a novel hierarchical navigation framework named ReMemNav, which seamlessly integrates panoramic semantic priors and episodic memory with VLMs. We introduce the Recognize Anything Model to anchor the spatial reasoning process of the VLM. We also design an adaptive dual-modal rethinking mechanism based on an episodic semantic buffer queue. The proposed mechanism actively verifies target visibility and corrects decisions using historical memory to prevent deadlocks. For low-level action execution, ReMemNav extracts a sequence of feasible actions using depth masks, allowing the VLM to select the optimal action for mapping into actual spatial movement. Extensive evaluations on HM3D and MP3D demonstrate that ReMemNav outperforms existing training-free zero-shot baselines in both success rate and exploration efficiency. Specifically, we achieve significant absolute performance improvements, with SR and SPL increasing by 1.7% and 7.0% on HM3D v0.1, 18.2% and 11.1% on HM3D v0.2, and 8.7% and 7.9% on MP3D.
### Title:
          Unblur-SLAM: Dense Neural SLAM for Blurry Inputs
 - **Authors:** Qi Zhang, Denis Rozumny, Francesco Girlanda, Sezer Karaoglu, Marc Pollefeys, Theo Gevers, Martin R. Oswald
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose Unblur-SLAM, a novel RGB SLAM pipeline for sharp 3D reconstruction from blurred image inputs. In contrast to previous work, our approach is able to handle different types of blur and demonstrates state-of-the-art performance in the presence of both motion blur and defocus blur. Moreover, we adjust the computation effort with the amount of blur in the input image. As a first stage, our method uses a feed-forward image deblurring model for which we propose a suitable training scheme that can improve both tracking and mapping modules. Frames that are successfully deblurred by the feed-forward network obtain refined poses and depth through local-global multi-view optimization and loop closure. Frames that fail the first stage deblurring are directly modeled through the global 3DGS representation and an additional blur network to model multiple blurred sub-frames and simulate the blur formation process in 3D space, thereby learning sharp details and refined sub-frame poses. Experiments on several real-world datasets demonstrate consistent improvements in both pose estimation and sharp reconstruction results of geometry and texture.
### Title:
          PiCSRL: Physics-Informed Contextual Spectral Reinforcement Learning
 - **Authors:** Mitra Nasr Azadani, Syed Usama Imtiaz, Nasrin Alamdari
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-dimensional low-sample-size (HDLSS) datasets constrain reliable environmental model development, where labeled data remain sparse. Reinforcement learning (RL)-based adaptive sensing methods can learn optimal sampling policies, yet their application is severely limited in HDLSS contexts. In this work, we present PiCSRL (Physics-Informed Contextual Spectral Reinforcement Learning), where embeddings are designed using domain knowledge and parsed directly into the RL state representation for improved adaptive sensing. We developed an uncertainty-aware belief model that encodes physics-informed features to improve prediction. As a representative example, we evaluated our approach for cyanobacterial gene concentration adaptive sampling task using NASA PACE hyperspectral imagery over Lake Erie. PiCSRL achieves optimal station selection (RMSE = 0.153, 98.4% bloom detection rate, outperforming random (0.296) and UCB (0.178) RMSE baselines, respectively. Our ablation experiments demonstrate that physics-informed features improve test generalization (0.52 R^2, +0.11 over raw bands) in semi-supervised learning. In addition, our scalability test shows that PiCSRL scales effectively to large networks (50 stations, >2M combinations) with significant improvements over baselines (p = 0.002). We posit PiCSRL as a sample-efficient adaptive sensing method across Earth observation domains for improved observation-to-target mapping.
### Title:
          VAN-AD: Visual Masked Autoencoder with Normalizing Flow For Time Series Anomaly Detection
 - **Authors:** PengYu Chen, Shang Wan, Xiaohou Shi, Yuan Chang, Yan Sun, Sajal K. Das
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time series anomaly detection (TSAD) is essential for maintaining the reliability and security of IoT-enabled service systems. Existing methods require training one specific model for each dataset, which exhibits limited generalization capability across different target datasets, hindering anomaly detection performance in various scenarios with scarce training data. To address this limitation, foundation models have emerged as a promising direction. However, existing approaches either repurpose large language models (LLMs) or construct largescale time series datasets to develop general anomaly detection foundation models, and still face challenges caused by severe cross-modal gaps or in-domain heterogeneity. In this paper, we investigate the applicability of large-scale vision models to TSAD. Specifically, we adapt a visual Masked Autoencoder (MAE) pretrained on ImageNet to the TSAD task. However, directly transferring MAE to TSAD introduces two key challenges: overgeneralization and limited local perception. To address these challenges, we propose VAN-AD, a novel MAE-based framework for TSAD. To alleviate the over-generalization issue, we design an Adaptive Distribution Mapping Module (ADMM), which maps the reconstruction results before and after MAE into a unified statistical space to amplify discrepancies caused by abnormal patterns. To overcome the limitation of local perception, we further develop a Normalizing Flow Module (NFM), which combines MAE with normalizing flow to estimate the probability density of the current window under the global distribution. Extensive experiments on nine real-world datasets demonstrate that VAN-AD consistently outperforms existing state-of-the-art methods across multiple evaluation this http URL make our code and datasets available at this https URL.
### Title:
          The Observability Gap: Why Output-Level Human Feedback Fails for LLM Coding Agents
 - **Authors:** Yinghao Wang, Cheng Wang
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language model (LLM) multi-agent coding systems typically fix agent capabilities at design time. We study an alternative setting, earned autonomy, in which a coding agent starts with zero pre-defined functions and incrementally builds a reusable function library through lightweight human feedback on visual output alone. We evaluate this setup in a Blender-based 3D scene generation task requiring both spatial reasoning and programmatic geometric control. Although the agent rediscovered core utility functions comparable to a human reference implementation, it achieved 0% full-scene success under output-only feedback across multiple instruction granularities, where success required satisfying object completeness, ground contact, collision avoidance, and scale plausibility simultaneously. Our analysis identifies a structural observability gap: bugs originate in code logic and execution state, while human evaluation occurs only at the output layer, and the many-to-one mapping from internal states to visible outcomes prevents symptom-level feedback from reliably identifying root causes. This mismatch leads to persistent failure mode oscillation rather than convergence. A diagnostic intervention that injected minimal code-level knowledge restored convergence, strongly supporting the interpretation that the main bottleneck lies in feedback observability rather than programming competence. We formalize this phenomenon as a feedback paradox in domains with deep causal chains between internal code logic and perceptual outcomes, and argue that effective human-agent collaboration in such settings requires intermediate observability beyond output-only evaluation.
### Title:
          ImmSET: Sequence-Based Predictor of TCR-pMHC Specificity at Scale
 - **Authors:** Marco Garcia Noceda, Matthew T Noakes, Andrew FigPope, Daniel E Mattox, Bryan Howie, Harlan Robins
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 T cells are a critical component of the adaptive immune system, playing a role in infectious disease, autoimmunity, and cancer. T cell function is mediated by the T cell receptor (TCR) protein, a highly diverse receptor targeting specific peptides presented by the major histocompatibility complex (pMHCs). Predicting the specificity of TCRs for their cognate pMHCs is central to understanding adaptive immunity and enabling personalized therapies. However, accurate prediction of this protein-protein interaction remains challenging due to the extreme diversity of both TCRs and pMHCs. Here, we present ImmSET (Immune Synapse Encoding Transformer), a novel sequence-based architecture designed to model interactions among sets of variable-length biological sequences. We train this model across a range of dataset sizes and compositions and study the resulting models' generalization to pMHC targets. We describe a failure mode in prior sequence-based approaches that inflates previously reported performance on this task and show that ImmSET remains robust under stricter evaluation. In systematically testing the scaling behavior of ImmSET with training data, we show that performance scales consistently with data volume across multiple data types and compares favorably with the pre-trained protein language model ESM2 fine-tuned on the same datasets. Finally, we demonstrate that ImmSET can outperform AlphaFold2 and AlphaFold3-based pipelines on TCR-pMHC specificity prediction when provided sufficient training data. This work establishes ImmSET as a scalable modeling paradigm for multi-sequence interaction problems, demonstrated in the TCR-pMHC setting but generalizable to other biological domains where high-throughput sequence-driven reasoning complements structure prediction and experimental mapping.
### Title:
          PhySkin: Physics-based Bone-driven Neural Garment Simulation
 - **Authors:** Astitva Srivastava, Hsiao-yu Chen, Ryan Goldade, Philipp Herholz, Zhongshi Jiang, Gene Wei-Chin Lin, Lingchen Yang, Nikolaos Sarafianos, Tuur Stuyck, Egor Larionov
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in digital avatar technology have enabled the generation of compelling virtual characters, but deploying these avatars on compute-constrained devices poses significant challenges for achieving realistic garment deformations. While physics-based simulations yield accurate results, they are computationally prohibitive for real-time applications. Conversely, linear blend skinning offers efficiency but fails to capture the complex dynamics of loose-fitting garments, resulting in unrealistic motion and visual artifacts. Neural methods have shown promise, yet they struggle to animate loose clothing plausibly under strict performance constraints. In this work, we present a novel approach for fast and physically plausible garment draping tailored for resource-constrained environments. Our method leverages a reduced-space quasi-static neural simulation, mapping the garment's full degrees of freedom to a set of bone handles that drive deformation. A neural deformation model is trained in a fully self-supervised manner, eliminating the need for costly simulation data. At runtime, a lightweight neural network modulates the handle deformations based on body shape and pose, enabling realistic garment behavior that respects physical properties such as gravity, fabric stretching, bending, and collision avoidance. Experimental results demonstrate that our method achieves physically plausible garment drapes while generalizing across diverse poses and body shapes, supporting zero-shot evaluation and mesh topology independence. Our method's runtime significantly outperforms past works, as it runs in microseconds per frame using single-threaded CPU inference, offering a practical solution for real-time avatar animation on low-compute devices.
### Title:
          Unsupervised Behavioral Compression: Learning Low-Dimensional Policy Manifolds through State-Occupancy Matching
 - **Authors:** Andrea Fraschini, Davide Tenedini, Riccardo Zamboni, Mirco Mutti, Marcello Restelli
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep Reinforcement Learning (DRL) is widely recognized as sample-inefficient, a limitation attributable in part to the high dimensionality and substantial functional redundancy inherent to the policy parameter space. A recent framework, which we refer to as Action-based Policy Compression (APC), mitigates this issue by compressing the parameter space $\Theta$ into a low-dimensional latent manifold $\mathcal Z$ using a learned generative mapping $g:\mathcal Z \to \Theta$. However, its performance is severely constrained by relying on immediate action-matching as a reconstruction loss, a myopic proxy for behavioral similarity that suffers from compounding errors across sequential decisions. To overcome this bottleneck, we introduce Occupancy-based Policy Compression (OPC), which enhances APC by shifting behavior representation from immediate action-matching to long-horizon state-space coverage. Specifically, we propose two principal improvements: (1) we curate the dataset generation with an information-theoretic uniqueness metric that delivers a diverse population of policies; and (2) we propose a fully differentiable compression objective that directly minimizes the divergence between the true and reconstructed mixture occupancy distributions. These modifications force the generative model to organize the latent space around true functional similarity, promoting a latent representation that generalizes over a broad spectrum of behaviors while retaining most of the original parameter space's expressivity. Finally, we empirically validate the advantages of our contributions across multiple continuous control benchmarks.
### Title:
          EFlow: Fast Few-Step Video Generator Training from Scratch via Efficient Solution Flow
 - **Authors:** Dogyun Park, Yanyu Li, Sergey Tulyakov, Anil Kag
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling video diffusion transformers is fundamentally bottlenecked by two compounding costs: the expensive quadratic complexity of attention per step, and the iterative sampling steps. In this work, we propose EFlow, an efficient few-step training framework, that tackles these bottlenecks simultaneously. To reduce sampling steps, we build on a solution-flow objective that learns a function mapping a noised state at time t to time s. Making this formulation computationally feasible and high-quality at video scale, however, demands two complementary innovations. First, we propose Gated Local-Global Attention, a token-droppable hybrid block which is efficient, expressive, and remains highly stable under aggressive random token-dropping, substantially reducing per-step compute. Second, we develop an efficient few-step training recipe. We propose Path-Drop Guided training to replace the expensive guidance target with a computationally cheap, weak path. Furthermore, we augment this with a Mean-Velocity Additivity regularizer to ensure high fidelity at extremely low step counts. Together, our EFlow enables a practical from-scratch training pipeline, achieving up to 2.5x higher training throughput over standard solution-flow, and 45.3x lower inference latency than standard iterative models with competitive performance on Kinetics and large-scale text-to-video datasets.
### Title:
          PRUE: A Practical Recipe for Field Boundary Segmentation at Scale
 - **Authors:** Gedeon Muhawenayo, Caleb Robinson, Subash Khanal, Zhanpei Fang, Isaac Corley, Alexander Wollam, Tianyi Gao, Leonard Strnad, Ryan Avery, Lyndon Estes, Ana M. Tárano, Nathan Jacobs, Hannah Kerner
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale maps of field boundaries are essential for agricultural monitoring tasks. Existing deep learning approaches for satellite-based field mapping are sensitive to illumination, spatial scale, and changes in geographic location. We conduct the first systematic evaluation of segmentation and geospatial foundation models (GFMs) for global field boundary delineation using the Fields of The World (FTW) benchmark. We evaluate 18 models under unified experimental settings, showing that a U-Net semantic segmentation model outperforms instance-based and GFM alternatives on a suite of performance and deployment metrics. We propose a new segmentation approach that combines a U-Net backbone, composite loss functions, and targeted data augmentations to enhance performance and robustness under real-world conditions. Our model achieves a 76\% IoU and 47\% object-F1 on FTW, an increase of 6\% and 9\% over the previous baseline. Our approach provides a practical framework for reliable, scalable, and reproducible field boundary delineation across model design, training, and inference. We release all models and model-derived field boundary datasets for five countries.
### Title:
          Recruiting Heterogeneous Crowdsource Vehicles for Updating a High-definition Map
 - **Authors:** Wentao Ye, Yuan Luo, Bo Liu, Jianwei Huang
 - **Subjects:** Subjects:
Computer Science and Game Theory (cs.GT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The high-definition map is a cornerstone of autonomous driving. Unlike constructing a costly fleet of mapping vehicles, the crowdsourcing paradigm is a cost-effective way to keep an HD map up to date. Achieving practical success for crowdsourcing-based HD maps is contingent on addressing two critical issues: freshness and recruitment costs. Given that crowdsource vehicles are often heterogeneous in terms of operational costs and sensing capabilities, it is practical to recruit heterogeneous crowdsource vehicles to achieve the tradeoff between freshness and recruitment costs. However, existing works neglect this aspect. To solve it, we formulate this problem as a Markov decision process. We demonstrate that the optimal policy is threshold-type age-dependent. Additionally, our findings reveal some counter-intuitive insights. In some cases, the company should initiate vehicle recruitment earlier when vehicles arrive more frequently, or have higher operational costs or sensing capabilities.} Besides, we propose an efficient algorithm, called the bound-based relative value iteration (BRVI) algorithm, to overcome the technical challenge that finding an optimal policy is time-consuming. Numerical simulations show that (i) the optimal policy reduces the average cost by $19.04\%$ compared to the state-of-the-art mechanism}, and (ii) the proposed algorithm can reduce the convergence time by $13.66\%$ on average compared to the existing algorithm.
### Title:
          Spectral-Aware Text-to-Time Series Generation with Billion-Scale Multimodal Meteorological Data
 - **Authors:** Shijie Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-time-series generation is particularly important in meteorology, where natural language offers intuitive control over complex, multi-scale atmospheric dynamics. Existing approaches are constrained by the lack of large-scale, physically grounded multimodal datasets and by architectures that overlook the spectral-temporal structure of weather signals. We address these challenges with a unified framework for text-guided meteorological time-series generation. First, we introduce MeteoCap-3B, a billion-scale weather dataset paired with expert-level captions constructed via a Multi-agent Collaborative Captioning (MACC) pipeline, yielding information-dense and physically consistent annotations. Building on this dataset, we propose MTransformer, a diffusion-based model that enables precise semantic control by mapping textual descriptions into multi-band spectral priors through a Spectral Prompt Generator, which guides generation via frequency-aware attention. Extensive experiments on real-world benchmarks demonstrate state-of-the-art generation quality, accurate cross-modal alignment, strong semantic controllability, and substantial gains in downstream forecasting under data-sparse and zero-shot settings. Additional results on general time-series benchmarks indicate that the proposed framework generalizes beyond meteorology.
### Title:
          Defend: Automated Rebuttals for Peer Review with Minimal Author Guidance
 - **Authors:** Jyotsana Khatri, Manasi Patwardhan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rebuttal generation is a critical component of the peer review process for scientific papers, enabling authors to clarify misunderstandings, correct factual inaccuracies, and guide reviewers toward a more accurate evaluation. We observe that Large Language Models (LLMs) often struggle to perform targeted refutation and maintain accurate factual grounding when used directly for rebuttal generation, highlighting the need for structured reasoning and author intervention. To address this, in the paper, we introduce DEFEND an LLM based tool designed to explicitly execute the underlying reasoning process of automated rebuttal generation, while keeping the author-in-the-loop. As opposed to writing the rebuttals from scratch, the author needs to only drive the reasoning process with minimal intervention, leading an efficient approach with minimal effort and less cognitive load. We compare DEFEND against three other paradigms: (i) Direct rebuttal generation using LLM (DRG), (ii) Segment-wise rebuttal generation using LLM (SWRG), and (iii) Sequential approach (SA) of segment-wise rebuttal generation without author intervention. To enable finegrained evaluation, we extend the ReviewCritique dataset, creating review segmentation, deficiency, error type annotations, rebuttal-action labels, and mapping to gold rebuttal segments. Experimental results and a user study demonstrate that directly using LLMs perform poorly in factual correctness and targeted refutation. Segment-wise generation and the automated sequential approach with author-in-the-loop, substantially improve factual correctness and strength of refutation.
### Title:
          Annotation-Free Detection of Drivable Areas and Curbs Leveraging LiDAR Point Cloud Maps
 - **Authors:** Fulong Ma, Daojie Peng, Jun Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Drivable areas and curbs are critical traffic elements for autonomous driving, forming essential components of the vehicle visual perception system and ensuring driving safety. Deep neural networks (DNNs) have significantly improved perception performance for drivable area and curb detection, but most DNN-based methods rely on large manually labeled datasets, which are costly, time-consuming, and expert-dependent, limiting their real-world application. Thus, we developed an automated training data generation module. Our previous work generated training labels using single-frame LiDAR and RGB data, suffering from occlusion and distant point cloud sparsity. In this paper, we propose a novel map-based automatic data labeler (MADL) module, combining LiDAR mapping/localization with curb detection to automatically generate training data for both tasks. MADL avoids occlusion and point cloud sparsity issues via LiDAR mapping, creating accurate large-scale datasets for DNN training. In addition, we construct a data review agent to filter the data generated by the MADL module, eliminating low-quality samples. Experiments on the KITTI, KITTI-CARLA and 3D-Curb datasets show that MADL achieves impressive performance compared to manual labeling, and outperforms traditional and state-of-the-art self-supervised methods in robustness and accuracy.
### Title:
          Stability Analysis of Monolithic Globally Divergence-Free ALE-HDG Methods for Fluid-Structure Interaction
 - **Authors:** Shuaijun Liu, Xiaoping Xie
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we propose two monolithic fully discrete finite element methods for fluid-structure interaction (FSI) based on a novel Piola-type Arbitrary Lagrangian-Eulerian (ALE) mapping. For the temporal discretization, we apply the backward Euler method to both the non-conservative and conservative formulations. For the spatial discretization, we adopt arbitrary order hybridizable discontinuous Galerkin (HDG) methods for the incompressible Navier-Stokes and linear elasticity equations, and a continuous Galerkin (CG) method for the fluid mesh movement. We derive stability results for both the temporal semi-discretization and the fully discretization, and show that the velocity approximations of the fully discrete schemes are globally divergence-free. Several numerical experiments are performed to verify the performance of the proposed methods.
### Title:
          ContraMap: Contrastive Uncertainty Mapping for Robot Environment Representation
 - **Authors:** Chi Cuong Le, Weiming Zhi
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable robot perception requires not only predicting scene structure, but also identifying where predictions should be treated as unreliable due to sparse or missing observations. We present ContraMap, a contrastive continuous mapping method that augments kernel-based discriminative maps with an explicit uncertainty class trained using synthetic noise samples. This formulation treats unobserved regions as a contrastive class, enabling joint environment prediction and spatial uncertainty estimation in real time without Bayesian inference. Under a simple mixture-model view, we show that the probability assigned to the uncertainty class is a monotonic function of a distance-aware uncertainty surrogate. Experiments in 2D occupancy mapping, 3D semantic mapping, and tabletop scene reconstruction show that ContraMap preserves mapping quality, produces spatially coherent uncertainty estimates, and is substantially more efficient than Bayesian kernelmap baselines.
### Title:
          LiDAR for Crowd Management: Applications, Benefits, and Future Directions
 - **Authors:** Abdullah Khanfor (1), Chaima Zaghouani (2), Hakim Ghazzai (3), Ahmad Alsharoa (2), Gianluca Setti (3),  ((1) the College of Computer Science and Information Systems, Najran University, (2) the College of Innovation &amp; Technology, University of Michigan-Flint, (3) King Abdullah University of Science and Technology (KAUST))
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Light Detection and Ranging (LiDAR) technology offers significant advantages for effective crowd management. This article presents LiDAR technology and highlights its primary advantages over other monitoring technologies, including enhanced privacy, performance in various weather conditions, and precise 3D mapping. We present a general taxonomy of four key tasks in crowd management: crowd detection, counting, tracking, and behavior classification, with illustrative examples of LiDAR applications for each task. We identify challenges and open research directions, including the scarcity of dedicated datasets, sensor fusion requirements, artificial intelligence integration, and processing needs for LiDAR point clouds. This article offers actionable insights for developing crowd management solutions tailored to public safety applications.
### Title:
          GS3LAM: Gaussian Semantic Splatting SLAM
 - **Authors:** Linfei Li, Lin Zhang, Zhong Wang, Ying Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recently, the multi-modal fusion of RGB, depth, and semantics has shown great potential in dense Simultaneous Localization and Mapping (SLAM). However, a prerequisite for generating consistent semantic maps is the availability of dense, efficient, and scalable scene representations. Existing semantic SLAM systems based on explicit representations are often limited by resolution and an inability to predict unknown areas. Conversely, implicit representations typically rely on time-consuming ray tracing, failing to meet real-time requirements. Fortunately, 3D Gaussian Splatting (3DGS) has emerged as a promising representation that combines the efficiency of point-based methods with the continuity of geometric structures. To this end, we propose GS3LAM, a Gaussian Semantic Splatting SLAM framework that processes multimodal data to render consistent, dense semantic maps in real-time. GS3LAM models the scene as a Semantic Gaussian Field (SG-Field) and jointly optimizes camera poses and the field via multimodal error constraints. Furthermore, a Depth-adaptive Scale Regularization (DSR) scheme is introduced to resolve misalignments between scale-invariant Gaussians and geometric surfaces. To mitigate catastrophic forgetting, we propose a Random Sampling-based Keyframe Mapping (RSKM) strategy, which demonstrates superior performance over common local covisibility optimization methods. Extensive experiments on benchmark datasets show that GS3LAM achieves increased tracking robustness, superior rendering quality, and enhanced semantic precision compared to state-of-the-art methods. Source code is available at this https URL.
### Title:
          Electrospinning-Data.org: A FAIR, Structured Knowledge Resource for Nanofiber Fabrication
 - **Authors:** Mehrab Mahdian, Ferenc Ender, Tamas Pardy
 - **Subjects:** Subjects:
Databases (cs.DB); Materials Science (cond-mat.mtrl-sci)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electrospinning is a versatile nanofabrication technique whose outcomes emerge from a complex, high-dimensional interplay between solution properties, processing parameters, and environmental conditions. Optimizing this parameter space for targeted fiber morphology is inherently challenging, often driving extensive trial-and-error experimentation and generating vast experimental data across laboratories worldwide. Yet this knowledge remains fragmented and underutilized due to inconsistent reporting and a pervasive bias toward successful outcomes, limiting reproducibility and hindering data-driven research. Here we introduce this http URL, a FAIR-aligned data aggregation infrastructure that organizes dispersed electrospinning experiments into structured, reusable, and failure-aware scientific records. The platform is built around a unified process-structure-property data model linking experimental inputs, environmental conditions, and nanofiber morphology, annotated through a controlled vocabulary, within a consistent, machine-readable schema. A two-stage moderation pipeline combining automated validation with expert review supports data quality and long-term interoperability. The resulting structured, failure-inclusive corpus provides a framework for data-driven research, including predictive modelling, inverse design of target morphologies, and systematic mapping of instability regimes that would otherwise require extensive trial-and-error experimentation.
### Title:
          FlashSign: Pose-Free Guidance for Efficient Sign Language Video Generation
 - **Authors:** Liuzhou Zhang, Zeyu Zhang, Biao Wu, Luyao Tang, Zirui Song, Hongyang He, Renda Han, Guangzhen Yao, Huacan Wang, Ronghao Chen, Xiuying Chen, Guan Huang, Zheng Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sign language plays a crucial role in bridging communication gaps between the deaf and hard-of-hearing communities. However, existing sign language video generation models often rely on complex intermediate representations, which limits their flexibility and efficiency. In this work, we propose a novel pose-free framework for real-time sign language video generation. Our method eliminates the need for intermediate pose representations by directly mapping natural language text to sign language videos using a diffusion-based approach. We introduce two key innovations: (1) a pose-free generative model based on the a state-of-the-art diffusion backbone, which learns implicit text-to-gesture alignments without pose estimation, and (2) a Trainable Sliding Tile Attention (T-STA) mechanism that accelerates inference by exploiting spatio-temporal locality patterns. Unlike previous training-free sparsity approaches, T-STA integrates trainable sparsity into both training and inference, ensuring consistency and eliminating the train-test gap. This approach significantly reduces computational overhead while maintaining high generation quality, making real-time deployment feasible. Our method increases video generation speed by 3.07x without compromising video quality. Our contributions open new avenues for real-time, high-quality, pose-free sign language synthesis, with potential applications in inclusive communication tools for diverse communities. Code: this https URL.
### Title:
          CARV: A Diagnostic Benchmark for Compositional Analogical Reasoning in Multimodal LLMs
 - **Authors:** Yongkang Du, Xiaohan Zou, Minhao Cheng, Lu Lin
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Analogical reasoning tests a fundamental aspect of human cognition: mapping the relation from one pair of objects to another. Existing evaluations of this ability in multimodal large language models (MLLMs) overlook the ability to compose rules from multiple sources, a critical component of higher-order intelligence. To close this gap, we introduce CARV (Compositional Analogical Reasoning in Vision), a novel task together with a 5,500-sample dataset as the first diagnostic benchmark. We extend the analogy from a single pair to multiple pairs, which requires MLLMs to extract symbolic rules from each pair and compose new transformations. Evaluation on the state-of-the-art MLLMs reveals a striking performance gap: even Gemini-2.5 Pro achieving only 40.4% accuracy, far below human-level performance of 100%. Diagnostic analysis shows two consistent failure modes: (1) decomposing visual changes into symbolic rules, and (2) maintaining robustness under diverse or complex settings, highlighting the limitations of current MLLMs on this task.
### Title:
          Hg-I2P: Bridging Modalities for Generalizable Image-to-Point-Cloud Registration via Heterogeneous Graphs
 - **Authors:** Pei An, Junfeng Ding, Jiaqi Yang, Yulong Wang, Jie Ma, Liangliang Nan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image-to-point-cloud (I2P) registration aims to align 2D images with 3D point clouds by establishing reliable 2D-3D correspondences. The drastic modality gap between images and point clouds makes it challenging to learn features that are both discriminative and generalizable, leading to severe performance drops in unseen scenarios. We address this challenge by introducing a heterogeneous graph that enables refining both cross-modal features and correspondences within a unified architecture. The proposed graph represents a mapping between segmented 2D and 3D regions, which enhances cross-modal feature interaction and thus improves feature discriminability. In addition, modeling the consistency among vertices and edges within the graph enables pruning of unreliable correspondences. Building on these insights, we propose a heterogeneous graph embedded I2P registration method, termed Hg-I2P. It learns a heterogeneous graph by mining multi-path feature relationships, adapts features under the guidance of heterogeneous edges, and prunes correspondences using graph-based projection consistency. Experiments on six indoor and outdoor benchmarks under cross-domain setups demonstrate that Hg-I2P significantly outperforms existing methods in both generalization and accuracy. Code is released on this https URL.
### Title:
          Beyond the Answer: Decoding the Behavior of LLMs as Scientific Reasoners
 - **Authors:** Rohan Pandey, Eric Ye, Michael Li
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As Large Language Models (LLMs) achieve increasingly sophisticated performance on complex reasoning tasks, current architectures serve as critical proxies for the internal heuristics of frontier models. Characterizing emergent reasoning is vital for long-term interpretability and safety. Furthermore, understanding how prompting modulates these processes is essential, as natural language will likely be the primary interface for interacting with AGI systems. In this work, we use a custom variant of Genetic Pareto (GEPA) to systematically optimize prompts for scientific reasoning tasks, and analyze how prompting can affect reasoning behavior. We investigate the structural patterns and logical heuristics inherent in GEPA-optimized prompts, and evaluate their transferability and brittleness. Our findings reveal that gains in scientific reasoning often correspond to model-specific heuristics that fail to generalize across systems, which we call "local" logic. By framing prompt optimization as a tool for model interpretability, we argue that mapping these preferred reasoning structures for LLMs is an important prerequisite for effectively collaborating with superhuman intelligence.
### Title:
          SIMR-NO: A Spectrally-Informed Multi-Resolution Neural Operator for Turbulent Flow Super-Resolution
 - **Authors:** Muhammad Abid, Omer San
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Fluid Dynamics (physics.flu-dyn)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing high-resolution turbulent flow fields from severely under-resolved observations is a fundamental inverse problem in computational fluid dynamics and scientific machine learning. Classical interpolation methods fail to recover missing fine-scale structures, while existing deep learning approaches rely on convolutional architectures that lack the spectral and multiscale inductive biases necessary for physically faithful reconstruction at large upscaling factors. We introduce the Spectrally-Informed Multi-Resolution Neural Operator (SIMR-NO), a hierarchical operator learning framework that factorizes the ill-posed inverse mapping across intermediate spatial resolutions, combines deterministic interpolation priors with spectrally gated Fourier residual corrections at each stage, and incorporates local refinement modules to recover fine-scale spatial features beyond the truncated Fourier basis. The proposed method is evaluated on Kolmogorov-forced two-dimensional turbulence, where $128\times128$ vorticity fields are reconstructed from extremely coarse $8\times8$ observations representing a $16\times$ downsampling factor. Across 201 independent test realizations, SIMR-NO achieves a mean relative $\ell_2$ error of $26.04\%$ with the lowest error variance among all methods, reducing reconstruction error by $31.7\%$ over FNO, $26.0\%$ over EDSR, and $9.3\%$ over LapSRN. Beyond pointwise accuracy, SIMR-NO is the only method that faithfully reproduces the ground-truth energy and enstrophy spectra across the full resolved wavenumber range, demonstrating physically consistent super-resolution of turbulent flow fields.
### Title:
          AXON: An Automated Netlist Optimization Framework for High-Speed Adders
 - **Authors:** Tiantian Yang, Xuanle Ren, Qingdian Wan, Qi Meng
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adders are fundamental building blocks in modern digital systems, and their performance, power, and area (PPA) directly impact system efficiency. Contemporary adders typically use parallel-prefix architectures with established PPA trade-offs, but these often fail to deliver globally optimal PPA for specific design goals. Prior work lacks netlist-/cell-level awareness, and general synthesis heuristics are not adder-specific, resulting in suboptimal PPA. To address this, we propose AXON, an automated netlist optimization framework for adders. It performs design space exploration from architectural to netlist level, integrating prefix topology search with standard-cell-aware mapping via a hierarchical approach to quickly converge to near-optimal PPA solutions. We also introduce a hybrid ultra-high-speed adder combining parallel-prefix and Ling architectures to shorten the critical path. Experiments on TSMC 28nm library show AXON improves delay, area-delay product, and energy-delay product by up to 10.3%, 12.6%, and 32.1% respectively, compared to commercial synthesis tools.
### Title:
          Ghost-FWL: A Large-Scale Full-Waveform LiDAR Dataset for Ghost Detection and Removal
 - **Authors:** Kazuma Ikeda, Ryosei Hara, Rokuto Nagata, Ozora Sako.Zihao Ding, Takahiro Kado, Ibuki Fujioka, Taro Beppu, Mariko Isogawa, Kentaro Yoshioka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR has become an essential sensing modality in autonomous driving, robotics, and smart-city applications. However, ghost points (or ghosts), which are false reflections caused by multi-path laser returns from glass and reflective surfaces, severely degrade 3D mapping and localization accuracy. Prior ghost removal relies on geometric consistency in dense point clouds, failing on mobile LiDAR's sparse, dynamic data. We address this by exploiting full-waveform LiDAR (FWL), which captures complete temporal intensity profiles rather than just peak distances, providing crucial cues for distinguishing ghosts from genuine reflections in mobile scenarios. As this is a new task, we present Ghost-FWL, the first and largest annotated mobile FWL dataset for ghost detection and removal. Ghost-FWL comprises 24K frames across 10 diverse scenes with 7.5 billion peak-level annotations, which is 100x larger than existing annotated FWL datasets. Benefiting from this large-scale dataset, we establish a FWL-based baseline model for ghost detection and propose FWL-MAE, a masked autoencoder for efficient self-supervised representation learning on FWL data. Experiments show that our baseline outperforms existing methods in ghost removal accuracy, and our ghost removal further enhances downstream tasks such as LiDAR-based SLAM (66% trajectory error reduction) and 3D object detection (50x false positive reduction). The dataset and code is publicly available and can be accessed via the project page: this https URL
### Title:
          A Multi-Agent Rhizomatic Pipeline for Non-Linear Literature Analysis
 - **Authors:** Julio C. Serrano. Joonas Kevari, Rumy Narayan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Systematic literature reviews in the social sciences overwhelmingly follow arborescent logics -- hierarchical keyword filtering, linear screening, and taxonomic classification -- that suppress the lateral connections, ruptures, and emergent patterns characteristic of complex research landscapes. This research note presents the Rhizomatic Research Agent (V3), a multi-agent computational pipeline grounded in Deleuzian process-relational ontology, designed to conduct non-linear literature analysis through 12 specialized agents operating across a seven-phase architecture. The system was developed in response to the methodological groundwork established by (Narayan2023), who employed rhizomatic inquiry in her doctoral research on sustainable energy transitions but relied on manual, researcher-driven exploration. The Rhizomatic Research Agent operationalizes the six principles of the rhizome -- connection, heterogeneity, multiplicity, asignifying rupture, cartography, and decalcomania -- into an automated pipeline integrating large language model (LLM) orchestration, dual-source corpus ingestion from OpenAlex and arXiv, SciBERT semantic topography, and dynamic rupture detection protocols. Preliminary deployment demonstrates the system's capacity to surface cross-disciplinary convergences and structural research gaps that conventional review methods systematically overlook. The pipeline is open-source and extensible to any phenomenon zone where non-linear knowledge mapping is required.
### Title:
          Feel Robot Feels: Tactile Feedback Array Glove for Dexterous Manipulation
 - **Authors:** Feiyu Jia, Xiaojie Niu, Sizhe Yang, Qingwei Ben, Tao Huang, Feng zhao, Jingbo Wang, Jiangmiao Pang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Teleoperation is a key approach for collecting high-quality, physically consistent demonstrations for robotic manipulation. However, teleoperation for dexterous manipulation remains constrained by: (i) inaccurate hand-robot motion mapping, which limits teleoperated dexterity, and (ii) limited tactile feedback that forces vision-dominated interaction and hinders perception of contact geometry and force variation. To address these challenges, we present TAG, a low-cost glove system that integrates precise hand motion capture with high-resolution tactile feedback, enabling effective tactile-in-the-loop dexterous teleoperation. For motion capture, TAG employs a non-contact magnetic sensing design that provides drift-free, electromagnetically robust 21-DoF joint tracking with joint angle estimation errors below 1 degree. Meanwhile, to restore tactile sensation, TAG equips each finger with a 32-actuator tactile array within a compact 2 cm^2 module, allowing operators to directly feel physical interactions at the robot end-effector through spatial activation patterns. Through real-world teleoperation experiments and user studies, we show that TAG enables reliable real-time perception of contact geometry and dynamic force, improves success rates in contact-rich teleoperation tasks, and increases the reliability of demonstration data collection for learning-based manipulation.
### Title:
          Pandora: Articulated 3D Scene Graphs from Egocentric Vision
 - **Authors:** Alan Yu, Yun Chang, Christopher Xie, Luca Carlone
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robotic mapping systems typically approach building metric-semantic scene representations from the robot's own sensors and cameras. However, these "first person" maps inherit the robot's own limitations due to its embodiment or skillset, which may leave many aspects of the environment unexplored. For example, the robot might not be able to open drawers or access wall cabinets. In this sense, the map representation is not as complete, and requires a more capable robot to fill in the gaps. We narrow these blind spots in current methods by leveraging egocentric data captured as a human naturally explores a scene wearing Project Aria glasses, giving a way to directly transfer knowledge about articulation from the human to any deployable robot. We demonstrate that, by using simple heuristics, we can leverage egocentric data to recover models of articulate object parts, with quality comparable to those of state-of-the-art methods based on other input modalities. We also show how to integrate these models into 3D scene graph representations, leading to a better understanding of object dynamics and object-container relationships. We finally demonstrate that these articulated 3D scene graphs enhance a robot's ability to perform mobile manipulation tasks, showcasing an application where a Boston Dynamics Spot is tasked with retrieving concealed target items, given only the 3D scene graph as input.
### Title:
          RAD-AI: Rethinking Architecture Documentation for AI-Augmented Ecosystems
 - **Authors:** Oliver Aleksander Larsen, Mahyar T. Moghaddam
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI-augmented ecosystems (interconnected systems where multiple AI components interact through shared data and infrastructure) are becoming the architectural norm for smart cities, autonomous fleets, and intelligent platforms. Yet the architecture documentation frameworks practitioners rely on, arc42 and the C4 model, were designed for deterministic software and cannot capture probabilistic behavior, data-dependent evolution, or dual ML/software lifecycles. This gap carries regulatory consequence: the EU AI Act (Regulation 2024/1689) mandates technical documentation through Annex IV that no existing framework provides structured support for, with enforcement for high-risk systems beginning August 2, 2026. We present RAD-AI, a backward-compatible extension framework that augments arc42 with eight AI-specific sections and C4 with three diagram extensions, complemented by a systematic EU AI Act Annex IV compliance mapping. A regulatory coverage assessment with six experienced software-architecture practitioners provides preliminary evidence that RAD-AI increases Annex IV addressability from approximately 36% to 93% (mean rating) and demonstrates substantial improvement over existing frameworks. Comparative analysis on two production AI platforms (Uber Michelangelo, Netflix Metaflow) captures eight additional AI-specific concerns missed by standard frameworks and demonstrates that documentation deficiencies are structural rather than domain-specific. An illustrative smart mobility ecosystem case study reveals ecosystem-level concerns, including cascading drift and differentiated compliance obligations, that are invisible under standard notation.
## Keyword: localization
### Title:
          SpatialPoint: Spatial-aware Point Prediction for Embodied Localization
 - **Authors:** Qiming Zhu, Zhirui Fang, Tianming Zhang, Chuanxiu Liu, Xiaoke Jiang, Lei Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Embodied intelligence fundamentally requires a capability to determine where to act in 3D space. We formalize this requirement as embodied localization -- the problem of predicting executable 3D points conditioned on visual observations and language instructions. We instantiate embodied localization with two complementary target types: touchable points, surface-grounded 3D points enabling direct physical interaction, and air points, free-space 3D points specifying placement and navigation goals, directional constraints, or geometric relations. Embodied localization is inherently a problem of embodied 3D spatial reasoning -- yet most existing vision-language systems rely predominantly on RGB inputs, necessitating implicit geometric reconstruction that limits cross-scene generalization, despite the widespread adoption of RGB-D sensors in robotics. To address this gap, we propose SpatialPoint, a spatial-aware vision-language framework with careful design that integrates structured depth into a vision-language model (VLM) and generates camera-frame 3D coordinates. We construct a 2.6M-sample RGB-D dataset covering both touchable and air points QA pairs for training and evaluation. Extensive experiments demonstrate that incorporating depth into VLMs significantly improves embodied localization performance. We further validate SpatialPoint through real-robot deployment across three representative tasks: language-guided robotic arm grasping at specified locations, object placement to target destinations, and mobile robot navigation to goal positions.
### Title:
          An Annotation-to-Detection Framework for Autonomous and Robust Vine Trunk Localization in the Field by Mobile Agricultural Robots
 - **Authors:** Dimitrios Chatziparaschis, Elia Scudiero, Brent Sams, Konstantinos Karydis
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The dynamic and heterogeneous nature of agricultural fields presents significant challenges for object detection and localization, particularly for autonomous mobile robots that are tasked with surveying previously unseen unstructured environments. Concurrently, there is a growing need for real-time detection systems that do not depend on large-scale manually labeled real-world datasets. In this work, we introduce a comprehensive annotation-to-detection framework designed to train a robust multi-modal detector using limited and partially labeled training data. The proposed methodology incorporates cross-modal annotation transfer and an early-stage sensor fusion pipeline, which, in conjunction with a multi-stage detection architecture, effectively trains and enhances the system's multi-modal detection capabilities. The effectiveness of the framework was demonstrated through vine trunk detection in novel vineyard settings that featured diverse lighting conditions and varying crop densities to validate performance. When integrated with a customized multi-modal LiDAR and Odometry Mapping (LOAM) algorithm and a tree association module, the system demonstrated high-performance trunk localization, successfully identifying over 70% of trees in a single traversal with a mean distance error of less than 0.37m. The results reveal that by leveraging multi-modal, incremental-stage annotation and training, the proposed framework achieves robust detection performance regardless of limited starting annotations, showcasing its potential for real-world and near-ground agricultural applications.
### Title:
          JND-Guided Neural Watermarking with Spatial Transformer Decoding for Screen-Capture Robustness
 - **Authors:** Jiayi Qin, Jingwei Li, Chuan Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Screen-shooting robust watermarking aims to imperceptibly embed extractable information into host images such that the watermark survives the complex distortion pipeline of screen display and camera recapture. However, achieving high extraction accuracy while maintaining satisfactory visual quality remains an open challenge, primarily because the screen-shooting channel introduces severe and entangled degradations including Moiré patterns, color-gamut shifts, perspective warping, and sensor noise. In this paper, we present an end-to-end deep learning framework that jointly optimizes watermark embedding and extraction for screen-shooting robustness. Our framework incorporates three key innovations: (i) a comprehensive noise simulation layer that faithfully models realistic screen-shooting distortions -- notably including a physically-motivated Moiré pattern generator -- enabling the network to learn robust representations against the full spectrum of capture-channel noise through adversarial training; (ii) a Just Noticeable Distortion (JND) perceptual loss function that adaptively modulates watermark embedding strength by supervising the perceptual discrepancy between the JND coefficient map and the watermark residual, thereby concentrating watermark energy in perceptually insensitive regions to maximize visual quality; and (iii) two complementary automatic localization modules -- a semantic-segmentation-based foreground extractor for captured image rectification and a symmetric noise template mechanism for anti-cropping region recovery -- that enable fully automated watermark decoding under realistic deployment conditions. Extensive experiments demonstrate that our method achieves an average PSNR of 30.94~dB and SSIM of 0.94 on watermarked images while embedding 127-bit payloads.
### Title:
          RatSeizure: A Benchmark and Saliency-Context Transformer for Rat Seizure Localization
 - **Authors:** Ting Yu Tsai, An Yu, Lucy Lee, Felix X.-F. Ye, Damian S. Shin, Tzu-Jen Kao, Xin Li, Ming-Ching Chang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Animal models, particularly rats, play a critical role in seizure research for studying epileptogenesis and treatment response. However, progress is limited by the lack of datasets with precise temporal annotations and standardized evaluation protocols. Existing animal behavior datasets often have limited accessibility, coarse labeling, and insufficient temporal localization of clinically meaningful events. To address these limitations, we introduce RatSeizure, the first publicly benchmark for fine-grained seizure behavior analysis. The dataset consists of recorded clips annotated with seizure-related action units and temporal boundaries, enabling both behavior classification and temporal localization. We further propose RaSeformer, a saliency-context Transformer for temporal action localization that highlights behavior-relevant context while suppressing redundant cues. Experiments on RatSeizure show that RaSeformer achieves strong performance and provides a competitive reference model for this challenging task. We also establish standardized dataset splits and evaluation protocols to support reproducible benchmarking.
### Title:
          The Ice Sheet State and Parameter Estimator (ICESEE) Library (v1.0.0): Ensemble Kalman Filtering for Ice Sheet Models
 - **Authors:** Brian Kyanjo, Talea L. Mayo, Alexander A. Robel
 - **Subjects:** Subjects:
Computational Complexity (cs.CC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 ICESEE (ICE Sheet statE and parameter Estimator) is a Python-based, open-source data assimilation framework designed for seamless integration with ice sheet and Earth system models. It implements a parallel Ensemble Kalman Filter (EnKF) with full MPI support for scalable assimilation in state and parameter spaces. ICESEE uses a matrix-free update scheme from Evensen (2003), which avoids explicit forecast error covariance construction and eliminates the need for localization in high-dimensional, nonlinear systems. ICESEE also supports four EnKF variants, including a localized version for methodological testing. It enables indirect inference of unobserved model parameters through a hybrid assimilation-inversion strategy. The framework features modular coupling interfaces, adaptive state indexing, and efficient parallel I/O, making it extensible to a variety of modeling environments. ICESEE has been successfully coupled with ISSM, Icepack, and other models. In this study, we focus on applications with ISSM and Icepack, demonstrating ICESEE's interoperability, performance, scalability, and ability to improve state estimates and infer uncertain parameters. Performance benchmarks show strong and weak scaling, highlighting ICESEE's potential for large-scale, observation-constrained ice sheet reanalyses.
### Title:
          GUIDED: Granular Understanding via Identification, Detection, and Discrimination for Fine-Grained Open-Vocabulary Object Detection
 - **Authors:** Jiaming Li, Zhijia Liang, Weikai Chen, Lin Ma, Guanbin Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-grained open-vocabulary object detection (FG-OVD) aims to detect novel object categories described by attribute-rich texts. While existing open-vocabulary detectors show promise at the base-category level, they underperform in fine-grained settings due to the semantic entanglement of subjects and attributes in pretrained vision-language model (VLM) embeddings -- leading to over-representation of attributes, mislocalization, and semantic drift in embedding space. We propose GUIDED, a decomposition framework specifically designed to address the semantic entanglement between subjects and attributes in fine-grained prompts. By separating object localization and fine-grained recognition into distinct pathways, HUIDED aligns each subtask with the module best suited for its respective roles. Specifically, given a fine-grained class name, we first use a language model to extract a coarse-grained subject and its descriptive attributes. Then the detector is guided solely by the subject embedding, ensuring stable localization unaffected by irrelevant or overrepresented attributes. To selectively retain helpful attributes, we introduce an attribute embedding fusion module that incorporates attribute information into detection queries in an attention-based manner. This mitigates over-representation while preserving discriminative power. Finally, a region-level attribute discrimination module compares each detected region against full fine-grained class names using a refined vision-language model with a projection head for improved alignment. Extensive experiments on FG-OVD and 3F-OVD benchmarks show that GUIDED achieves new state-of-the-art results, demonstrating the benefits of disentangled modeling and modular optimization. Our code will be released at this https URL.
### Title:
          MultiLoc: Multi-view Guided Relative Pose Regression for Fast and Robust Visual Re-Localization
 - **Authors:** Nobel Dang, Bing Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Relative Pose Regression (RPR) generalizes well to unseen environments, but its performance is often limited due to pairwise and local spatial views. To this end, we propose MultiLoc, a novel multi-view guided RPR model trained at scale, equipping relative pose regression with globally consistent spatial and geometric understanding. Specifically, our method jointly fuses multiple reference views and their associated camera poses in a single forward pass, enabling accurate zero-shot pose estimation with real-time efficiency. To reliably supply informative context, we further propose a co-visibility-driven retrieval strategy for geometrically relevant reference view selection. MultiLoc establishes a new benchmark in visual re-localization, consistently outperforming existing state-of-the-art (SOTA) relative pose regression (RPR) methods across diverse datasets, including WaySpots, Cambridge Landmarks, and Indoor6. Furthermore, MultiLoc's pose regressor exhibits SOTA performance in relative pose estimation, surpassing RPR, feature matching and non-regression-based techniques on the MegaDepth-1500, ScanNet-1500, and ACID benchmarks. These results demonstrate robust domain generalization of MultiLoc across indoor, outdoor and natural environments. Code will be made publicly available.
### Title:
          Reasoning-Driven Anomaly Detection and Localization with Image-Level Supervision
 - **Authors:** Yizhou Jin, Yuezhu Feng, Jinjin Zhang, Peng Wang, Qingjie Liu, Yunhong Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal large language models (MLLMs) have recently demonstrated remarkable reasoning and perceptual abilities for anomaly detection. However, most approaches remain confined to image-level anomaly detection and textual reasoning, while pixel-level localization still relies on external vision modules and dense annotations. In this work, we activate the intrinsic reasoning potential of MLLMs to perform anomaly detection, pixel-level localization, and interpretable reasoning solely from image-level supervision, without any auxiliary components or pixel-wise labels. Specifically, we propose Reasoning-Driven Anomaly Localization (ReAL), which extracts anomaly-related tokens from the autoregressive reasoning process and aggregates their attention responses to produce pixel-level anomaly maps. We further introduce a Consistency-Guided Reasoning Optimization (CGRO) module that leverages reinforcement learning to align reasoning tokens with visual attentions, resulting in more coherent reasoning and accurate anomaly localization. Extensive experiments on four public benchmarks demonstrate that our method significantly improves anomaly detection, localization, and interpretability. Remarkably, despite relying solely on image-level supervision, our approach achieves performance competitive with MLLM-based methods trained under dense pixel-level supervision. Code is available at this https URL.
### Title:
          K$α$LOS finds Consensus: A Meta-Algorithm for Evaluating Inter-Annotator Agreement in Complex Vision Tasks
 - **Authors:** David Tschirschwitz, Volker Rodehorst
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Progress in object detection benchmarks is stagnating. It is limited not by architectures but by the inability to distinguish model improvements from label noise. To restore trust in benchmarking the field requires rigorous quantification of annotation consistency to ensure the reliability of evaluation data. However, standard statistical metrics fail to handle the instance correspondence problem inherent to vision tasks. Furthermore, validating new agreement metrics remains circular because no objective ground truth for agreement exists. This forces reliance on unverifiable heuristics. We propose K$\alpha$LOS (KALOS), a unified meta-algorithm that generalizes the "Localization First" principle to standardize dataset quality evaluation. By resolving spatial correspondence before assessing agreement, our framework transforms complex spatio-categorical problems into nominal reliability matrices. Unlike prior heuristic implementations, K$\alpha$LOS employs a principled, data-driven configuration; by statistically calibrating the localization parameters to the inherent agreement distribution, it generalizes to diverse tasks ranging from bounding boxes to volumetric segmentation or pose estimation. This standardization enables granular diagnostics beyond a single score. These include annotator vitality, collaboration clustering, and localization sensitivity. To validate this approach, we introduce a novel and empirically derived noise generator. Where prior validations relied on uniform error assumptions, our controllable testbed models complex and non-isotropic human variability. This provides evidence of the metric's properties and establishes K$\alpha$LOS as a robust standard for distinguishing signal from noise in modern computer vision benchmarks.
### Title:
          Zero-shot Vision-Language Reranking for Cross-View Geolocalization
 - **Authors:** Yunus Talha Erzurumlu, John E. Anderson, William J. Shuart, Charles Toth, Alper Yilmaz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view geolocalization (CVGL) systems, while effective at retrieving a list of relevant candidates (high Recall@k), often fail to identify the single best match (low Top-1 accuracy). This work investigates the use of zero-shot Vision-Language Models (VLMs) as rerankers to address this gap. We propose a two-stage framework: state-of-the-art (SOTA) retrieval followed by VLM reranking. We systematically compare two strategies: (1) Pointwise (scoring candidates individually) and (2) Pairwise (comparing candidates relatively). Experiments on the VIGOR dataset show a clear divergence: all pointwise methods cause a catastrophic drop in performance or no change at all. In contrast, a pairwise comparison strategy using LLaVA improves Top-1 accuracy over the strong retrieval baseline. Our analysis concludes that, these VLMs are poorly calibrated for absolute relevance scoring but are effective at fine-grained relative visual judgment, making pairwise reranking a promising direction for enhancing CVGL precision.
### Title:
          Predictive Modeling in AUV Navigation: A Perspective from Kalman Filtering
 - **Authors:** Zizhan Tang, Yao Liu, Jessica Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a safety-oriented framework for autonomous underwater vehicles (AUVs) that improves localization accuracy, enhances trajectory prediction, and supports efficient search operations during communication loss. Acoustic signals emitted by the AUV are detected by a network of fixed buoys, which compute Time-Difference-of-Arrival (TDOA) range-difference measurements serving as position observations. These observations are subsequently fused with a Kalman-based prediction model to obtain continuous, noise-robust state estimates. The combined method achieves significantly better localization precision and trajectory stability than TDOA-only baselines. Beyond real-time tracking, our framework offers targeted search-and-recovery capability by predicting post-disconnection motion and explicitly modeling uncertainty growth. The search module differentiates between continued navigation and propulsion failure, allowing search resources to be deployed toward the most probable recovery region. Our framework fuses multi-buoy acoustic data with Kalman filtering and uncertainty propagation to maintain navigation accuracy and yield robust search-region definitions during communication loss.
### Title:
          Streamlined Open-Vocabulary Human-Object Interaction Detection
 - **Authors:** Chang Sun, Dongliang Liao, Changxing Ding
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary human-object interaction (HOI) detection aims to localize and recognize all human-object interactions in an image, including those unseen during training. Existing approaches usually rely on the collaboration between a conventional HOI detector and a Vision-Language Model (VLM) to recognize unseen HOI categories. However, feature fusion in this paradigm is challenging due to significant gaps in cross-model representations. To address this issue, we introduce SL-HOI, a StreamLined open-vocabulary HOI detection framework based solely on the powerful DINOv3 model. Our design leverages the complementary strengths of DINOv3's components: its backbone for fine-grained localization and its text-aligned vision head for open-vocabulary interaction classification. Moreover, to facilitate smooth cross-attention between the interaction queries and the vision head's output, we propose first feeding both the interaction queries and the backbone image tokens into the vision head, effectively bridging their representation gaps. All DINOv3 parameters in our approach are frozen, with only a small number of learnable parameters added, allowing a fast adaptation to the HOI detection task. Extensive experiments show that SL-HOI achieves state-of-the-art performance on both the SWiG-HOI and HICO-DET benchmarks, demonstrating the effectiveness of our streamlined model architecture. Code is available at this https URL.
### Title:
          S3KF: Spherical State-Space Kalman Filtering for Panoramic 3D Multi-Object Tracking
 - **Authors:** Zhongyuan Liu, Shaonan Yu, Jianping Li, Pengfei Wan, Xinhang Xu, Pengfei Wang, Maggie Y. Gao, Lihua Xie
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Panoramic multi-object tracking is important for industrial safety monitoring, wide-area robotic perception, and infrastructure-light deployment in large workspaces. In these settings, the sensing system must provide full-surround coverage, metric geometric cues, and stable target association under wide field-of-view distortion and occlusion. Existing image-plane trackers are tightly coupled to the camera projection and become unreliable in panoramic imagery, while conventional Euclidean 3D formulations introduce redundant directional parameters and do not naturally unify angular, scale, and depth estimation. In this paper, we present $\mathbf{S^3KF}$, a panoramic 3D multi-object tracking framework built on a motorized rotating LiDAR and a quad-fisheye camera rig. The key idea is a geometry-consistent state representation on the unit sphere $\mathbb{S}^2$, where object bearing is modeled by a two-degree-of-freedom tangent-plane parameterization and jointly estimated with box scale and depth dynamics. Based on this state, we derive an extended spherical Kalman filtering pipeline that fuses panoramic camera detections with LiDAR depth observations for multimodal tracking. We further establish a map-based ground-truth generation pipeline using wearable localization devices registered to a shared global LiDAR map, enabling quantitative evaluation without motion-capture infrastructure. Experiments on self-collected real-world sequences show decimeter-level planar tracking accuracy, improved identity continuity over a 2D panoramic baseline in dynamic scenes, and real-time onboard operation on a Jetson AGX Orin platform. These results indicate that the proposed framework is a practical solution for panoramic perception and industrial-scale multi-object this http URL project page can be found at this https URL.
### Title:
          Annotation-Free Detection of Drivable Areas and Curbs Leveraging LiDAR Point Cloud Maps
 - **Authors:** Fulong Ma, Daojie Peng, Jun Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Drivable areas and curbs are critical traffic elements for autonomous driving, forming essential components of the vehicle visual perception system and ensuring driving safety. Deep neural networks (DNNs) have significantly improved perception performance for drivable area and curb detection, but most DNN-based methods rely on large manually labeled datasets, which are costly, time-consuming, and expert-dependent, limiting their real-world application. Thus, we developed an automated training data generation module. Our previous work generated training labels using single-frame LiDAR and RGB data, suffering from occlusion and distant point cloud sparsity. In this paper, we propose a novel map-based automatic data labeler (MADL) module, combining LiDAR mapping/localization with curb detection to automatically generate training data for both tasks. MADL avoids occlusion and point cloud sparsity issues via LiDAR mapping, creating accurate large-scale datasets for DNN training. In addition, we construct a data review agent to filter the data generated by the MADL module, eliminating low-quality samples. Experiments on the KITTI, KITTI-CARLA and 3D-Curb datasets show that MADL achieves impressive performance compared to manual labeling, and outperforms traditional and state-of-the-art self-supervised methods in robustness and accuracy.
### Title:
          OpenDPR: Open-Vocabulary Change Detection via Vision-Centric Diffusion-Guided Prototype Retrieval for Remote Sensing Imagery
 - **Authors:** Qi Guo, Jue Wang, Yinhe Liu, Yanfei Zhong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary change detection (OVCD) seeks to recognize arbitrary changes of interest by enabling generalization beyond a fixed set of predefined classes. We reformulate OVCD as a two-stage pipeline: first generate class-agnostic change proposals using visual foundation models (VFMs) such as SAM and DINOv2, and then perform category identification with vision-language models (VLMs) such as CLIP. We reveal that category identification errors are the primary bottleneck of OVCD, mainly due to the limited ability of VLMs based on image-text matching to represent fine-grained land-cover categories. To address this, we propose OpenDPR, a training-free vision-centric diffusion-guided prototype retrieval framework. OpenDPR leverages diffusion models to construct diverse prototypes for target categories offline, and to perform similarity retrieval with change proposals in the visual space during inference. The secondary bottleneck lies in change localization, due to the inherent lack of change priors in VFMs. To bridge this gap, we design a spatial-to-change weakly supervised change detection module named S2C to adapt their strong spatial modeling capabilities for change localization. Integrating the pretrained S2C into OpenDPR leads to an optional weakly supervised variant named OpenDPR-W, which further improves OVCD with minimal supervision. Experimental results on four benchmark datasets demonstrate that the proposed methods achieve state-of-the-art performance under both supervision modes. Code is available at this https URL.
### Title:
          RHO: Robust Holistic OSM-Based Metric Cross-View Geo-Localization
 - **Authors:** Junwei Zheng, Ruize Dai, Ruiping Liu, Zichao Zeng, Yufan Chen, Fangjinhua Wang, Kunyu Peng, Kailun Yang, Jiaming Zhang, Rainer Stiefelhagen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Metric Cross-View Geo-Localization (MCVGL) aims to estimate the 3-DoF camera pose (position and heading) by matching ground and satellite images. In this work, instead of pinhole and satellite images, we study robust MCVGL using holistic panoramas and OpenStreetMap (OSM). To this end, we establish a large-scale MCVGL benchmark dataset, CV-RHO, with over 2.7M images under different weather and lighting conditions, as well as sensor noise. Furthermore, we propose a model termed RHO with a two-branch Pin-Pan architecture for accurate visual localization. A Split-Undistort-Merge (SUM) module is introduced to address the panoramic distortion, and a Position-Orientation Fusion (POF) mechanism is designed to enhance the localization accuracy. Extensive experiments prove the value of our CV-RHO dataset and the effectiveness of the RHO model, with a significant performance gain up to 20% compared with the state-of-the-art baselines. Project page: this https URL.
### Title:
          GS3LAM: Gaussian Semantic Splatting SLAM
 - **Authors:** Linfei Li, Lin Zhang, Zhong Wang, Ying Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recently, the multi-modal fusion of RGB, depth, and semantics has shown great potential in dense Simultaneous Localization and Mapping (SLAM). However, a prerequisite for generating consistent semantic maps is the availability of dense, efficient, and scalable scene representations. Existing semantic SLAM systems based on explicit representations are often limited by resolution and an inability to predict unknown areas. Conversely, implicit representations typically rely on time-consuming ray tracing, failing to meet real-time requirements. Fortunately, 3D Gaussian Splatting (3DGS) has emerged as a promising representation that combines the efficiency of point-based methods with the continuity of geometric structures. To this end, we propose GS3LAM, a Gaussian Semantic Splatting SLAM framework that processes multimodal data to render consistent, dense semantic maps in real-time. GS3LAM models the scene as a Semantic Gaussian Field (SG-Field) and jointly optimizes camera poses and the field via multimodal error constraints. Furthermore, a Depth-adaptive Scale Regularization (DSR) scheme is introduced to resolve misalignments between scale-invariant Gaussians and geometric surfaces. To mitigate catastrophic forgetting, we propose a Random Sampling-based Keyframe Mapping (RSKM) strategy, which demonstrates superior performance over common local covisibility optimization methods. Extensive experiments on benchmark datasets show that GS3LAM achieves increased tracking robustness, superior rendering quality, and enhanced semantic precision compared to state-of-the-art methods. Source code is available at this https URL.
### Title:
          Learning Multi-View Spatial Reasoning from Cross-View Relations
 - **Authors:** Suchae Jeong, Jaehwi Song, Haeone Lee, Hanna Kim, Jian Kim, Dongjun Lee, Dong Kyu Shin, Changyeon Kim, Dongyoon Hahm, Woogyeol Jin, Juheon Choi, Kimin Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models (VLMs) have achieved impressive results on single-view vision tasks, but lack the multi-view spatial reasoning capabilities essential for embodied AI systems to understand 3D environments and manipulate objects across different viewpoints. In this work, we introduce Cross-View Relations (XVR), a large-scale dataset designed to teach VLMs spatial reasoning across multiple views. XVR comprises 100K vision-question-answer samples derived from 18K diverse 3D scenes and 70K robotic manipulation trajectories, spanning three fundamental spatial reasoning tasks: Correspondence (matching objects across views), Verification (validating spatial relationships), and Localization (identifying object positions). VLMs fine-tuned on XVR achieve substantial improvements on established multi-view and robotic spatial reasoning benchmarks (MindCube and RoboSpatial). When integrated as backbones in Vision-Language-Action models, XVR-trained representations improve success rates on RoboCasa. Our results demonstrate that explicit training on cross-view spatial relations significantly enhances multi-view reasoning and transfers effectively to real-world robotic manipulation.
### Title:
          Progressive Prompt-Guided Cross-Modal Reasoning for Referring Image Segmentation
 - **Authors:** Jiachen Li, Hongyun Wang, Jinyu Xu, Wenbo Jiang, Yanchun Ma, Yongjian Liu, Qing Xie, Bolong Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Referring image segmentation aims to localize and segment a target object in an image based on a free-form referring expression. The core challenge lies in effectively bridging linguistic descriptions with object-level visual representations, especially when referring expressions involve detailed attributes and complex inter-object relationships. Existing methods either rely on cross-modal alignment or employ Semantic Segmentation Prompts, but they often lack explicit reasoning mechanisms for grounding language descriptions to target regions in the image. To address these limitations, we propose PPCR, a Progressive Prompt-guided Cross-modal Reasoning framework for referring image segmentation. PPCR explicitly structures the reasoning process as a Semantic Understanding-Spatial Grounding-Instance Segmentation pipeline. Specifically, PPCR first employs multimodal large language models (MLLMs) to generate Semantic Segmentation Prompt that capture key semantic cues of the target object. Based on this semantic context, Spatial Segmentation Prompt are further generated to reason about object location and spatial extent, enabling a progressive transition from semantic understanding to spatial grounding. The Semantic and Spatial Segmentation prompts are then jointly integrated into the segmentation module to guide accurate target localization and segmentation. Extensive experiments on standard referring image segmentation benchmarks demonstrate that PPCR consistently outperforms existing methods. The code will be publicly released to facilitate reproducibility.
### Title:
          MedLoc-R1: Performance-Aware Curriculum Reward Scheduling for GRPO-Based Medical Visual Grounding
 - **Authors:** Guangjing Yang, Ziyuan Qin, Chaoran Zhang, Chenlin Du, Jinlin Wang, Wanran Sun, Zhenyu Zhang, Bing Ji, Qicheng Lao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medical visual grounding serves as a crucial foundation for fine-grained multimodal reasoning and interpretable clinical decision support. Despite recent advances in reinforcement learning (RL) for grounding tasks, existing approaches such as Group Relative Policy Optimization~(GRPO) suffer from severe reward sparsity when directly applied to medical images, primarily due to the inherent difficulty of localizing small or ambiguous regions of interest, which is further exacerbated by the rigid and suboptimal nature of fixed IoU-based reward schemes in RL. This leads to vanishing policy gradients and stagnated optimization, particularly during early training. To address this challenge, we propose MedLoc-R1, a performance-aware reward scheduling framework that progressively tightens the reward criterion in accordance with model readiness. MedLoc-R1 introduces a sliding-window performance tracker and a multi-condition update rule that automatically adjust the reward schedule from dense, easily obtainable signals to stricter, fine-grained localization requirements, while preserving the favorable properties of GRPO without introducing auxiliary networks or additional gradient paths. Experiments on three medical visual grounding benchmarks demonstrate that MedLoc-R1 consistently improves both localization accuracy and training stability over GRPO-based baselines. Our framework offers a general, lightweight, and effective solution for RL-based grounding in high-stakes medical applications. Code \& checkpoints are available at \hyperlink{}{this https URL}.
### Title:
          Ghost-FWL: A Large-Scale Full-Waveform LiDAR Dataset for Ghost Detection and Removal
 - **Authors:** Kazuma Ikeda, Ryosei Hara, Rokuto Nagata, Ozora Sako.Zihao Ding, Takahiro Kado, Ibuki Fujioka, Taro Beppu, Mariko Isogawa, Kentaro Yoshioka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR has become an essential sensing modality in autonomous driving, robotics, and smart-city applications. However, ghost points (or ghosts), which are false reflections caused by multi-path laser returns from glass and reflective surfaces, severely degrade 3D mapping and localization accuracy. Prior ghost removal relies on geometric consistency in dense point clouds, failing on mobile LiDAR's sparse, dynamic data. We address this by exploiting full-waveform LiDAR (FWL), which captures complete temporal intensity profiles rather than just peak distances, providing crucial cues for distinguishing ghosts from genuine reflections in mobile scenarios. As this is a new task, we present Ghost-FWL, the first and largest annotated mobile FWL dataset for ghost detection and removal. Ghost-FWL comprises 24K frames across 10 diverse scenes with 7.5 billion peak-level annotations, which is 100x larger than existing annotated FWL datasets. Benefiting from this large-scale dataset, we establish a FWL-based baseline model for ghost detection and propose FWL-MAE, a masked autoencoder for efficient self-supervised representation learning on FWL data. Experiments show that our baseline outperforms existing methods in ghost removal accuracy, and our ghost removal further enhances downstream tasks such as LiDAR-based SLAM (66% trajectory error reduction) and 3D object detection (50x false positive reduction). The dataset and code is publicly available and can be accessed via the project page: this https URL
### Title:
          osmAG-Nav: A Hierarchical Semantic Topometric Navigation Stack for Robust Lifelong Indoor Autonomy
 - **Authors:** Yongqi Zhang, Jiajie Zhang, Chengqian Li, Fujing Xie, Sören Schwertfeger
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The deployment of mobile robots in large-scale, multi-floor environments demands navigation systems that achieve spatial scalability without compromising local kinematic precision. Traditional navigation stacks, reliant on monolithic occupancy grid maps, face severe bottlenecks in storage efficiency, cross-floor reasoning, and long-horizon planning. To address these limitations, this paper presents osmAG-Nav, a complete, open-source ROS2 navigation stack built upon the hierarchical semantic topometric OpenStreetMap Area Graph (osmAG) map standard. The system follows a "System of Systems" architecture that decouples global topological reasoning from local metric execution. A Hierarchical osmAG planner replaces dense grid searches with an LCA-anchored pipeline on a passage-centric graph whose edge costs derive from local raster traversability rather than Euclidean distance, yielding low-millisecond planning on long campus-scale routes. A Rolling Window mechanism rasterizes a fixed-size local metric grid around the robot, keeping the local costmap memory footprint independent of the total mapped area, while a Segmented Execution strategy dispatches intermediate goals to standard ROS2 controllers for smooth handoffs. System robustness is reinforced by a structure-aware LiDAR localization framework that filters dynamic clutter against permanent architectural priors. Extensive experiments on a real-world multi-story indoor-outdoor campus (>11,025 m^2) show that, on the same-floor benchmark subset, osmAG-Nav delivers up to 7816x lower planning latency than a grid-based baseline on long routes while maintaining low path-length overhead and lifelong localization stability. A single-floor long-range robot mission further validates the integrated stack reliability. The full stack is released as modular ROS2 Lifecycle Nodes.
### Title:
          Rethinking Structure Preservation in Text-Guided Image Editing with Visual Autoregressive Models
 - **Authors:** Tao Xia, Jiawei Liu, Yukun Zhang, Ting Liu, Wei Wang, Lei Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual autoregressive (VAR) models have recently emerged as a promising family of generative models, enabling a wide range of downstream vision tasks such as text-guided image editing. By shifting the editing paradigm from noise manipulation in diffusion-based methods to token-level operations, VAR-based approaches achieve better background preservation and significantly faster inference. However, existing VAR-based editing methods still face two key challenges: accurately localizing editable tokens and maintaining structural consistency in the edited results. In this work, we propose a novel text-guided image editing framework rooted in an analysis of intermediate feature distributions within VAR models. First, we introduce a coarse-to-fine token localization strategy that can refine editable regions, balancing editing fidelity and background preservation. Second, we analyze the intermediate representations of VAR models and identify structure-related features, by which we design a simple yet effective feature injection mechanism to enhance structural consistency between the edited and source images. Third, we develop a reinforcement learning-based adaptive feature injection scheme that automatically learns scale- and layer-specific injection ratios to jointly optimize editing fidelity and structure preservation. Extensive experiments demonstrate that our method achieves superior structural consistency and editing quality compared with state-of-the-art approaches, across both local and global editing scenarios.
### Title:
          TGIF2: Extended Text-Guided Inpainting Forgery Dataset & Benchmark
 - **Authors:** Hannes Mareen, Dimitrios Karageorgiou, Paschalis Giakoumoglou, Peter Lambert, Symeon Papadopoulos, Glenn Van Wallendael
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Cryptography and Security (cs.CR); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative AI has made text-guided inpainting a powerful image editing tool, but at the same time a growing challenge for media forensics. Existing benchmarks, including our text-guided inpainting forgery (TGIF) dataset, show that image forgery localization (IFL) methods can localize manipulations in spliced images but struggle not in fully regenerated (FR) images, while synthetic image detection (SID) methods can detect fully regenerated images but cannot perform localization. With new generative inpainting models emerging and the open problem of localization in FR images remaining, updated datasets and benchmarks are needed. We introduce TGIF2, an extended version of TGIF, that captures recent advances in text-guided inpainting and enables a deeper analysis of forensic robustness. TGIF2 augments the original dataset with edits generated by FLUX.1 models, as well as with random non-semantic masks. Using the TGIF2 dataset, we conduct a forensic evaluation spanning IFL and SID, including fine-tuning IFL methods on FR images and generative super-resolution attacks. Our experiments show that both IFL and SID methods degrade on FLUX.1 manipulations, highlighting limited generalization. Additionally, while fine-tuning improves localization on FR images, evaluation with random non-semantic masks reveals object bias. Furthermore, generative super-resolution significantly weakens forensic traces, demonstrating that common image enhancement operations can undermine current forensic pipelines. In summary, TGIF2 provides an updated dataset and benchmark, which enables new insights into the challenges posed by modern inpainting and AI-based image enhancements. TGIF2 is available at this https URL.
### Title:
          Not Search, But Scan: Benchmarking MLLMs on Scan-Oriented Academic Paper Reasoning
 - **Authors:** Rongjin Li, Zichen Tang, Xianghe Wang, Xinyi Hu, Zhengyu Wang, Zhengyu Lu, Yiling Huang, Jiayuan Chen, Weisheng Tan, Jiacheng Liu, Zhongjun Yang, Haihong E
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the rapid progress of multimodal large language models (MLLMs), AI already performs well at literature retrieval and certain reasoning tasks, serving as a capable assistant to human researchers, yet it remains far from autonomous research. The fundamental reason is that current work on academic paper reasoning is largely confined to a search-oriented paradigm centered on pre-specified targets, with reasoning grounded in relevance retrieval, which struggles to support researcher-style full-document understanding, reasoning, and verification. To bridge this gap, we propose \textbf{ScholScan}, a new benchmark for academic paper reasoning. ScholScan introduces a scan-oriented task setting that asks models to read and cross-check entire papers like human researchers, scanning the document to identify consistency issues. The benchmark comprises 1,800 carefully annotated questions drawn from nine error categories across 13 natural-science domains and 715 papers, and provides detailed annotations for evidence localization and reasoning traces, together with a unified evaluation protocol. We assessed 15 models across 24 input configurations and conducted a fine-grained analysis of MLLM capabilities for all error categories. Across the board, retrieval-augmented generation (RAG) methods yield no significant improvements, revealing systematic deficiencies of current MLLMs on scan-oriented tasks and underscoring the challenge posed by ScholScan. We expect ScholScan to be the leading and representative work of the scan-oriented task paradigm.
## Keyword: transformer
### Title:
          A Multimodal Deep Learning Framework for Edema Classification Using HCT and Clinical Data
 - **Authors:** Aram Ansary Ogholbake, Hannah Choi, Spencer Brandenburg, Alyssa Antuna, Zahraa Al-Sharshahi, Makayla Cox, Haseeb Ahmed, Jacqueline Frank, Nathan Millson, Luke Bauerle, Jessica Lee, David Dornbos III, Qiang Cheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose AttentionMixer, a unified deep learning framework for multimodal detection of brain edema that combines structural head CT (HCT) with routine clinical metadata. While HCT provides rich spatial information, clinical variables such as age, laboratory values, and scan timing capture complementary context that might be ignored or naively concatenated. AttentionMixer is designed to fuse these heterogeneous sources in a principled and efficient manner. HCT volumes are first encoded using a self-supervised Vision Transformer Autoencoder (ViT-AE++), without requiring large labeled datasets. Clinical metadata are mapped into the same feature space and used as keys and values in a cross-attention module, where HCT-derived feature vector serves as queries. This cross-attention fusion allows the network to dynamically modulate imaging features based on patient-specific context and provides an interpretable mechanism for multimodal integration. A lightweight MLP-Mixer then refines the fused representation before final classification, enabling global dependency modeling with substantially reduced parameter overhead. Missing or incomplete metadata are handled via a learnable embedding, promoting robustness to real-world clinical data quality. We evaluate AttentionMixer on a curated brain HCT cohort with expert edema annotations using five-fold cross-validation. Compared with strong HCT-only, metadata-only, and prior multimodal baselines, AttentionMixer achieves superior performance (accuracy 87.32%, precision 92.10%, F1-score 85.37%, AUC 94.14%). Ablation studies confirm the benefit of both cross-attention and MLP-Mixer refinement, and permutation-based metadata importance analysis highlights clinically meaningful variables driving predictions. These results demonstrate that structured, interpretable multimodal fusion can substantially improve edema detection in clinical practice.
### Title:
          Steering Sparse Autoencoder Latents to Control Dynamic Head Pruning in Vision Transformers (Student Abstract)
 - **Authors:** Yousung Lee, Dongsoo Har
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dynamic head pruning in Vision Transformers (ViTs) improves efficiency by removing redundant attention heads, but existing pruning policies are often difficult to interpret and control. In this work, we propose a novel framework by integrating Sparse Autoencoders (SAEs) with dynamic pruning, leveraging their ability to disentangle dense embeddings into interpretable and controllable sparse latents. Specifically, we train an SAE on the final-layer residual embedding of the ViT and amplify the sparse latents with different strategies to alter pruning decisions. Among them, per-class steering reveals compact, class-specific head subsets that preserve accuracy. For example, bowl improves accuracy (76% to 82%) while reducing head usage (0.72 to 0.33) via heads h2 and h5. These results show that sparse latent features enable class-specific control of dynamic pruning, effectively bridging pruning efficiency and mechanistic interpretability in ViTs.
### Title:
          Motion Semantics Guided Normalizing Flow for Privacy-Preserving Video Anomaly Detection
 - **Authors:** Yang Liu, Boan Chen, Yuanyuan Meng, Jing Liu, Zhengliang Guo, Wei Zhou, Peng Sun, Hong Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As embodied perception systems increasingly bridge digital and physical realms in interactive multimedia applications, the need for privacy-preserving approaches to understand human activities in physical environments has become paramount. Video anomaly detection is a critical task in such embodied multimedia systems for intelligent surveillance and forensic analysis. Skeleton-based approaches have emerged as a privacy-preserving alternative that processes physical world information through abstract human pose representations while discarding sensitive visual attributes such as identity and facial features. However, existing skeleton-based methods predominantly model continuous motion trajectories in a monolithic manner, failing to capture the hierarchical nature of human activities composed of discrete semantic primitives and fine-grained kinematic details, which leads to reduced discriminability when anomalies manifest at different abstraction levels. In this regard, we propose Motion Semantics Guided Normalizing Flow (MSG-Flow) that decomposes skeleton-based VAD into hierarchical motion semantics modeling. It employs vector quantized variational auto-encoder to discretize continuous motion into interpretable primitives, an autoregressive Transformer to model semantic-level temporal dependencies, and a conditional normalizing flow to capture detail-level pose variations. Extensive experiments on benchmarks (HR-ShanghaiTech & HR-UBnormal) demonstrate that MSG-Flow achieves state-of-the-art performance with 88.1% and 75.8% AUC respectively.
### Title:
          TDEC: Deep Embedded Image Clustering with Transformer and Distribution Information
 - **Authors:** Ruilin Zhang, Haiyang Zheng, Hongpeng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image clustering is a crucial but challenging task in multimedia machine learning. Recently the combination of clustering with deep learning has achieved promising performance against conventional methods on high-dimensional image data. Unfortunately, existing deep clustering methods (DC) often ignore the importance of information fusion with a global perception field among different image regions on clustering images, especially complex ones. Additionally, the learned features are usually clustering-unfriendly in terms of dimensionality and are based only on simple distance information for the clustering. In this regard, we propose a deep embedded image clustering TDEC, which for the first time to our knowledge, jointly considers feature representation, dimensional preference, and robust assignment for image clustering. Specifically, we introduce the Transformer to form a novel module T-Encoder to learn discriminative features with global dependency while using the Dim-Reduction block to build a friendly low-dimensional space favoring clustering. Moreover, the distribution information of embedded features is considered in the clustering process to provide reliable supervised signals for joint training. Our method is robust and allows for more flexibility in data size, the number of clusters, and the context complexity. More importantly, the clustering performance of TDEC is much higher than recent competitors. Extensive experiments with state-of-the-art approaches on complex datasets show the superiority of TDEC.
### Title:
          Survey on Remote Sensing Scene Classification: From Traditional Methods to Large Generative AI Models
 - **Authors:** Qionghao Huang, Can Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote sensing scene classification has experienced a paradigmatic transformation from traditional handcrafted feature methods to sophisticated artificial intelligence systems that now form the backbone of modern Earth observation applications. This comprehensive survey examines the complete methodological evolution, systematically tracing development from classical texture descriptors and machine learning classifiers through the deep learning revolution to current state-of-the-art foundation models and generative AI approaches. We chronicle the pivotal shift from manual feature engineering to automated hierarchical representation learning via convolutional neural networks, followed by advanced architectures including Vision Transformers, graph neural networks, and hybrid frameworks. The survey provides in-depth coverage of breakthrough developments in self-supervised foundation models and vision-language systems, highlighting exceptional performance in zero-shot and few-shot learning scenarios. Special emphasis is placed on generative AI innovations that tackle persistent challenges through synthetic data generation and advanced feature learning strategies. We analyze contemporary obstacles including annotation costs, multimodal data fusion complexities, interpretability demands, and ethical considerations, alongside current trends in edge computing deployment, federated learning frameworks, and sustainable AI practices. Based on comprehensive analysis of recent advances and gaps, we identify key future research priorities: advancing hyperspectral and multi-temporal analysis capabilities, developing robust cross-domain generalization methods, and establishing standardized evaluation protocols to accelerate scientific progress in remote sensing scene classification systems.
### Title:
          GradAttn: Replacing Fixed Residual Connections with Task-Modulated Attention Pathways
 - **Authors:** Soudeep Ghoshal, Himanshu Buckchash
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep ConvNets suffer from gradient signal degradation as network depth increases, limiting effective feature learning in complex architectures. ResNet addressed this through residual connections, but these fixed short-circuits cannot adapt to varying input complexity or selectively emphasize task relevant features across network hierarchies. This study introduces GradAttn, a hybrid CNN-transformer framework that replaces fixed residual connections with attention-controlled gradient flow. By extracting multi-scale CNN features at different depths and regulating them through self-attention, GradAttn dynamically weights shallow texture features and deep semantic representations. For representational analysis, we evaluated three GradAttn variants across eight diverse datasets, from natural images, medical imaging, to fashion recognition. Results demonstrate that GradAttn outperforms ResNet-18 on five of eight datasets, achieving up to +11.07% accuracy improvement on FashionMNIST while maintaining comparable network size. Gradient flow analysis reveals that controlled instabilities, introduced by attention, often coincide with improved generalization, challenging the assumption that perfect stability is optimal. Furthermore, positional encoding effectiveness proves dataset dependent, with CNN hierarchies frequently encoding sufficient spatial structure. These findings allow attention mechanisms as enablers of learnable gradient control, offering a new paradigm for adaptive representation learning in deep neural architectures.
### Title:
          Tiny-ViT: A Compact Vision Transformer for Efficient and Explainable Potato Leaf Disease Classification
 - **Authors:** Shakil Mia, Umme Habiba, Urmi Akter, SK Rezwana Quadir Raisa, Jeba Maliha, Md. Iqbal Hossain, Md. Shakhauat Hossan Sumon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Early and precise identification of plant diseases, especially in potato crops is important to ensure the health of the crops and ensure the maximum yield . Potato leaf diseases, such as Early Blight and Late Blight, pose significant challenges to farmers, often resulting in yield losses and increased pesticide use. Traditional methods of detection are not only time-consuming, but are also subject to human error, which is why automated and efficient methods are required. The paper introduces a new method of potato leaf disease classification Tiny-ViT model, which is a small and effective Vision Transformer (ViT) developed to be used in resource-limited systems. The model is tested on a dataset of three classes, namely Early Blight, Late Blight, and Healthy leaves, and the preprocessing procedures include resizing, CLAHE, and Gaussian blur to improve the quality of the image. Tiny-ViT model has an impressive test accuracy of 99.85% and a mean CV accuracy of 99.82% which is better than baseline models such as DEIT Small, SWIN Tiny, and MobileViT XS. In addition to this, the model has a Matthews Correlation Coefficient (MCC) of 0.9990 and narrow confidence intervals (CI) of [0.9980, 0.9995], which indicates high reliability and generalization. The training and testing inference time is competitive, and the model exhibits low computational expenses, thereby, making it applicable in real-time applications. Moreover, interpretability of the model is improved with the help of GRAD-CAM, which identifies diseased areas. Altogether, the proposed Tiny-ViT is a solution with a high level of robustness, efficiency, and explainability to the problem of plant disease classification.
### Title:
          A training-free framework for high-fidelity appearance transfer via diffusion transformers
 - **Authors:** Shengrong Gu, Ye Wang, Song Wu, Rui Ma, Qian Wang, Lanjun Wang, Zili Yi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) excel at generation, but their global self-attention makes controllable, reference-image-based editing a distinct challenge. Unlike U-Nets, naively injecting local appearance into a DiT can disrupt its holistic scene structure. We address this by proposing the first training-free framework specifically designed to tame DiTs for high-fidelity appearance transfer. Our core is a synergistic system that disentangles structure and appearance. We leverage high-fidelity inversion to establish a rich content prior for the source image, capturing its lighting and micro-textures. A novel attention-sharing mechanism then dynamically fuses purified appearance features from a reference, guided by geometric priors. Our unified approach operates at 1024px and outperforms specialized methods on tasks ranging from semantic attribute transfer to fine-grained material application. Extensive experiments confirm our state-of-the-art performance in both structural preservation and appearance fidelity.
### Title:
          Learning to Select Visual In-Context Demonstrations
 - **Authors:** Eugene Lee, Yu-Chi Lin, Jiajie Diao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Large Language Models (MLLMs) adapt to visual tasks via in-context learning (ICL), which relies heavily on demonstration quality. The dominant demonstration selection strategy is unsupervised k-Nearest Neighbor (kNN) search. While simple, this similarity-first approach is sub-optimal for complex factual regression tasks; it selects redundant examples that fail to capture the task's full output range. We reframe selection as a sequential decision-making problem and introduce Learning to Select Demonstrations (LSD), training a Reinforcement Learning agent to construct optimal demonstration sets. Using a Dueling DQN with a query-centric Transformer Decoder, our agent learns a policy that maximizes MLLM downstream performance. Evaluating across five visual regression benchmarks, we uncover a crucial dichotomy: while kNN remains optimal for subjective preference tasks, LSD significantly outperforms baselines on objective, factual regression tasks. By balancing visual relevance with diversity, LSD better defines regression boundaries, illuminating when learned selection is strictly necessary for visual ICL.
### Title:
          RatSeizure: A Benchmark and Saliency-Context Transformer for Rat Seizure Localization
 - **Authors:** Ting Yu Tsai, An Yu, Lucy Lee, Felix X.-F. Ye, Damian S. Shin, Tzu-Jen Kao, Xin Li, Ming-Ching Chang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Animal models, particularly rats, play a critical role in seizure research for studying epileptogenesis and treatment response. However, progress is limited by the lack of datasets with precise temporal annotations and standardized evaluation protocols. Existing animal behavior datasets often have limited accessibility, coarse labeling, and insufficient temporal localization of clinically meaningful events. To address these limitations, we introduce RatSeizure, the first publicly benchmark for fine-grained seizure behavior analysis. The dataset consists of recorded clips annotated with seizure-related action units and temporal boundaries, enabling both behavior classification and temporal localization. We further propose RaSeformer, a saliency-context Transformer for temporal action localization that highlights behavior-relevant context while suppressing redundant cues. Experiments on RatSeizure show that RaSeformer achieves strong performance and provides a competitive reference model for this challenging task. We also establish standardized dataset splits and evaluation protocols to support reproducible benchmarking.
### Title:
          Sparse-by-Design Cross-Modality Prediction: L0-Gated Representations for Reliable and Efficient Learning
 - **Authors:** Filippo Cenacchi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predictive systems increasingly span heterogeneous modalities such as graphs, language, and tabular records, but sparsity and efficiency remain modality-specific (graph edge or neighborhood sparsification, Transformer head or layer pruning, and separate tabular feature-selection pipelines). This fragmentation makes results hard to compare, complicates deployment, and weakens reliability analysis across end-to-end KDD pipelines. A unified sparsification primitive would make accuracy-efficiency trade-offs comparable across modalities and enable controlled reliability analysis under representation compression. We ask whether a single representation-level mechanism can yield comparable accuracy-efficiency trade-offs across modalities while preserving or improving probability calibration. We propose L0-Gated Cross-Modality Learning (L0GM), a modality-agnostic, feature-wise hard-concrete gating framework that enforces L0-style sparsity directly on learned representations. L0GM attaches hard-concrete stochastic gates to each modality's classifier-facing interface: node embeddings (GNNs), pooled sequence embeddings such as CLS (Transformers), and learned tabular embedding vectors (tabular models). This yields end-to-end trainable sparsification with an explicit control knob for the active feature fraction. To stabilize optimization and make trade-offs interpretable, we introduce an L0-annealing schedule that induces clear accuracy-sparsity Pareto frontiers. Across three public benchmarks (ogbn-products, Adult, IMDB), L0GM achieves competitive predictive performance while activating fewer representation dimensions, and it reduces Expected Calibration Error (ECE) in our evaluation. Overall, L0GM establishes a modality-agnostic, reproducible sparsification primitive that supports comparable accuracy, efficiency, and calibration trade-off analysis across heterogeneous modalities.
### Title:
          Epileptic Seizure Prediction Using Patient-Adaptive Transformer Networks
 - **Authors:** Mohamed Mahdi, Asma Baghdadi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Epileptic seizure prediction from electroencephalographic (EEG) recordings remains challenging due to strong inter-patient variability and the complex temporal structure of neural signals. This paper presents a patient-adaptive transformer framework for short-horizon seizure forecasting. The proposed approach employs a two-stage training strategy: self-supervised pretraining is first used to learn general EEG temporal representations through autoregressive sequence modeling, followed by patient-specific fine-tuning for binary prediction of seizure onset within a 30-second horizon. To enable transformer-based sequence learning, multichannel EEG signals are processed using noise-aware preprocessing and discretized into tokenized temporal sequences. Experiments conducted on subjects from the TUH EEG dataset demonstrate that the proposed method achieves validation accuracies above 90% and F1 scores exceeding 0.80 across evaluated patients, supporting the effectiveness of combining self-supervised representation learning with patient-specific adaptation for individualized seizure prediction.
### Title:
          FatigueFormer: Static-Temporal Feature Fusion for Robust sEMG-Based Muscle Fatigue Recognition
 - **Authors:** Tong Zhang, Hong Guo, Shuangzhou Yan, Dongkai Weng, Jian Wang, Hongxin Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present FatigueFormer, a semi-end-to-end framework that deliberately combines saliency-guided feature separation with deep temporal modeling to learn interpretable and generalizable muscle fatigue dynamics from surface electromyography (sEMG). Unlike prior approaches that struggle to maintain robustness across varying Maximum Voluntary Contraction (MVC) levels due to signal variability and low SNR, FatigueFormer employs parallel Transformer-based sequence encoders to separately capture static and temporal feature dynamics, fusing their complementary representations to improve performance stability across low- and high-MVC conditions. Evaluated on a self-collected dataset spanning 30 participants across four MVC levels (20-80%), it achieves state-of-the-art accuracy and strong generalization under mild-fatigue conditions. Beyond performance, FatigueFormer enables attention-based visualization of fatigue dynamics, revealing how feature groups and time windows contribute differently across varying MVC levels, offering interpretable insight into fatigue progression.
### Title:
          ImmSET: Sequence-Based Predictor of TCR-pMHC Specificity at Scale
 - **Authors:** Marco Garcia Noceda, Matthew T Noakes, Andrew FigPope, Daniel E Mattox, Bryan Howie, Harlan Robins
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 T cells are a critical component of the adaptive immune system, playing a role in infectious disease, autoimmunity, and cancer. T cell function is mediated by the T cell receptor (TCR) protein, a highly diverse receptor targeting specific peptides presented by the major histocompatibility complex (pMHCs). Predicting the specificity of TCRs for their cognate pMHCs is central to understanding adaptive immunity and enabling personalized therapies. However, accurate prediction of this protein-protein interaction remains challenging due to the extreme diversity of both TCRs and pMHCs. Here, we present ImmSET (Immune Synapse Encoding Transformer), a novel sequence-based architecture designed to model interactions among sets of variable-length biological sequences. We train this model across a range of dataset sizes and compositions and study the resulting models' generalization to pMHC targets. We describe a failure mode in prior sequence-based approaches that inflates previously reported performance on this task and show that ImmSET remains robust under stricter evaluation. In systematically testing the scaling behavior of ImmSET with training data, we show that performance scales consistently with data volume across multiple data types and compares favorably with the pre-trained protein language model ESM2 fine-tuned on the same datasets. Finally, we demonstrate that ImmSET can outperform AlphaFold2 and AlphaFold3-based pipelines on TCR-pMHC specificity prediction when provided sufficient training data. This work establishes ImmSET as a scalable modeling paradigm for multi-sequence interaction problems, demonstrated in the TCR-pMHC setting but generalizable to other biological domains where high-throughput sequence-driven reasoning complements structure prediction and experimental mapping.
### Title:
          MOOZY: A Patient-First Foundation Model for Computational Pathology
 - **Authors:** Yousef Kotp, Vincent Quoc-Huy Trinh, Christopher Pal, Mahdi S. Hosseini
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Computational pathology needs whole-slide image (WSI) foundation models that transfer across diverse clinical tasks, yet current approaches remain largely slide-centric, often depend on private data and expensive paired-report supervision, and do not explicitly model relationships among multiple slides from the same patient. We present MOOZY, a patient-first pathology foundation model in which the patient case, not the individual slide, is the core unit of representation. MOOZY explicitly models dependencies across all slides from the same patient via a case transformer during pretraining, combining multi-stage open self-supervision with scaled low-cost task supervision. In Stage 1, we pretrain a vision-only slide encoder on 77,134 public slide feature grids using masked self-distillation. In Stage 2, we align these representations with clinical semantics using a case transformer and multi-task supervision over 333 tasks from 56 public datasets, including 205 classification and 128 survival tasks across four endpoints. Across eight held-out tasks with five-fold frozen-feature probe evaluation, MOOZY achieves best or tied-best performance on most metrics and improves macro averages over TITAN by +7.37%, +5.50%, and +7.83% and over PRISM by +8.83%, +10.70%, and +9.78% for weighted F1, weighted ROC-AUC, and balanced accuracy, respectively. MOOZY is also parameter efficient with 85.77M parameters, 14x smaller than GigaPath. These results demonstrate that open, reproducible patient-level pretraining yields transferable embeddings, providing a practical path toward scalable patient-first histopathology foundation models.
### Title:
          EFlow: Fast Few-Step Video Generator Training from Scratch via Efficient Solution Flow
 - **Authors:** Dogyun Park, Yanyu Li, Sergey Tulyakov, Anil Kag
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling video diffusion transformers is fundamentally bottlenecked by two compounding costs: the expensive quadratic complexity of attention per step, and the iterative sampling steps. In this work, we propose EFlow, an efficient few-step training framework, that tackles these bottlenecks simultaneously. To reduce sampling steps, we build on a solution-flow objective that learns a function mapping a noised state at time t to time s. Making this formulation computationally feasible and high-quality at video scale, however, demands two complementary innovations. First, we propose Gated Local-Global Attention, a token-droppable hybrid block which is efficient, expressive, and remains highly stable under aggressive random token-dropping, substantially reducing per-step compute. Second, we develop an efficient few-step training recipe. We propose Path-Drop Guided training to replace the expensive guidance target with a computationally cheap, weak path. Furthermore, we augment this with a Mean-Velocity Additivity regularizer to ensure high fidelity at extremely low step counts. Together, our EFlow enables a practical from-scratch training pipeline, achieving up to 2.5x higher training throughput over standard solution-flow, and 45.3x lower inference latency than standard iterative models with competitive performance on Kinetics and large-scale text-to-video datasets.
### Title:
          Spectral-Aware Text-to-Time Series Generation with Billion-Scale Multimodal Meteorological Data
 - **Authors:** Shijie Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-time-series generation is particularly important in meteorology, where natural language offers intuitive control over complex, multi-scale atmospheric dynamics. Existing approaches are constrained by the lack of large-scale, physically grounded multimodal datasets and by architectures that overlook the spectral-temporal structure of weather signals. We address these challenges with a unified framework for text-guided meteorological time-series generation. First, we introduce MeteoCap-3B, a billion-scale weather dataset paired with expert-level captions constructed via a Multi-agent Collaborative Captioning (MACC) pipeline, yielding information-dense and physically consistent annotations. Building on this dataset, we propose MTransformer, a diffusion-based model that enables precise semantic control by mapping textual descriptions into multi-band spectral priors through a Spectral Prompt Generator, which guides generation via frequency-aware attention. Extensive experiments on real-world benchmarks demonstrate state-of-the-art generation quality, accurate cross-modal alignment, strong semantic controllability, and substantial gains in downstream forecasting under data-sparse and zero-shot settings. Additional results on general time-series benchmarks indicate that the proposed framework generalizes beyond meteorology.
### Title:
          Preconditioned Attention: Enhancing Efficiency in Transformers
 - **Authors:** Hemanth Saratchandran
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Central to the success of Transformers is the attention block, which effectively models global dependencies among input tokens associated to a dataset. However, we theoretically demonstrate that standard attention mechanisms in transformers often produce ill-conditioned matrices with large condition numbers. This ill-conditioning is a well-known obstacle for gradient-based optimizers, leading to inefficient training. To address this issue, we introduce preconditioned attention, a novel approach that incorporates a conditioning matrix into each attention head. Our theoretical analysis shows that this method significantly reduces the condition number of attention matrices, resulting in better-conditioned matrices that improve optimization. Conditioned attention serves as a simple drop-in replacement for a wide variety of attention mechanisms in the literature. We validate the effectiveness of preconditioned attention across a diverse set of transformer applications, including image classification, object detection, instance segmentation, long sequence modeling and language modeling.
### Title:
          Hybrid Deep Learning with Temporal Data Augmentation for Accurate Remaining Useful Life Prediction of Lithium-Ion Batteries
 - **Authors:** Yun Tian, Guili Wang, Jian Bi, Kaixin Han, Chenglu Wu, Zhiyi Lu, Chenhao Li, Liangwang Sun, Minyu Zhou, Chenchen Xu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate prediction of lithium-ion battery remaining useful life (RUL) is essential for reliable health monitoring and data-driven analysis of battery degradation. However, the robustness and generalization capabilities of existing RUL prediction models are significantly challenged by complex operating conditions and limited data availability. To address these limitations, this study proposes a hybrid deep learning model, CDFormer, which integrates convolutional neural networks, deep residual shrinkage networks, and Transformer encoders extract multiscale temporal features from battery measurement signals, including voltage, current, and capacity. This architecture enables the joint modeling of local and global degradation dynamics, effectively improving the accuracy of RUL this http URL enhance predictive reliability, a composite temporal data augmentation strategy is proposed, incorporating Gaussian noise, time warping, and time resampling, explicitly accounting for measurement noise and variability. CDFormer is evaluated on two real-world datasets, with experimental results demonstrating its consistent superiority over conventional recurrent neural network-based and Transformer-based baselines across key metrics. By improving the reliability and predictive performance of RUL prediction from measurement data, CDFormer provides accurate and reliable forecasts, supporting effective battery health monitoring and data-driven maintenance strategies.
### Title:
          HD-VGGT: High-Resolution Visual Geometry Transformer
 - **Authors:** Tianrun Chen, Yuanqi Hu, Yidong Han, Hanjie Xu, Deyi Ji, Qi Zhu, Chunan Yu, Xin Zhang, Cheng Chen, Chaotao Ding, Ying Zang, Xuanfu Li, Jin Ma, Lanyun Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-resolution imagery is essential for accurate 3D reconstruction, as many geometric details only emerge at fine spatial scales. Recent feed-forward approaches, such as the Visual Geometry Grounded Transformer (VGGT), have demonstrated the ability to infer scene geometry from large collections of images in a single forward pass. However, scaling these models to high-resolution inputs remains challenging: the number of tokens in transformer architectures grows rapidly with both image resolution and the number of views, leading to prohibitive computational and memory costs. Moreover, we observe that visually ambiguous regions, such as repetitive patterns, weak textures, or specular surfaces, often produce unstable feature tokens that degrade geometric inference, especially at higher resolutions. We introduce HD-VGGT, a dual-branch architecture for efficient and robust high-resolution 3D reconstruction. A low-resolution branch predicts a coarse, globally consistent geometry, while a high-resolution branch refines details via a learned feature upsampling module. To handle unstable tokens, we propose Feature Modulation, which suppresses unreliable features early in the transformer. HD-VGGT leverages high-resolution images and supervision without full-resolution transformer costs, achieving state-of-the-art reconstruction quality.
### Title:
          Complet4R: Geometric Complete 4D Reconstruction
 - **Authors:** Weibang Wang, Kenan Li, Zhuoguang Chen, Yijun Yuan, Hang Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Complet4R, a novel end-to-end framework for Geometric Complete 4D Reconstruction, which aims to recover temporally coherent and geometrically complete reconstruction for dynamic scenes. Our method formalizes the task of Geometric Complete 4D Reconstruction as a unified framework of reconstruction and completion, by directly accumulating full contexts onto each frame. Unlike previous approaches that rely on pairwise reconstruction or local motion estimation, Complet4R utilizes a decoder-only transformer to operate all context globally directly from sequential video input, reconstructing a complete geometry for every single timestamp, including occluded regions visible in other frames. Our method demonstrates the state-of-the-art performance on our proposed benchmark for Geometric Complete 4D Reconstruction and the 3D Point Tracking task. Code will be released to support future research.
### Title:
          MeshTailor: Cutting Seams via Generative Mesh Traversal
 - **Authors:** Xueqi Ma, Xingguang Yan, Congyue Zhang, Hui Huang
 - **Subjects:** Subjects:
Graphics (cs.GR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present MeshTailor, the first mesh-native generative framework for synthesizing edge-aligned seams on 3D surfaces. Unlike prior optimization-based or extrinsic learning-based methods, MeshTailor operates directly on the mesh graph, eliminating projection artifacts and fragile snapping heuristics. We introduce ChainingSeams, a hierarchical serialization of the seam graph that prioritizes global structural cuts before local details in a coarse-to-fine manner, and a dual-stream encoder that fuses topological and geometric context. Leveraging this hierarchical representation and enriched vertex embeddings, our MeshTailor Transformer utilizes an autoregressive pointer layer to trace seams vertex-by-vertex within local neighborhoods, ensuring projection-free, edge-aligned seams. Extensive evaluations show that MeshTailor produces more coherent, professional-quality seam layouts compared to recent optimization-based and learning-based baselines.
### Title:
          Multimodal Forecasting for Commodity Prices Using Spectrogram-Based and Time Series Representations
 - **Authors:** Soyeon Park, Doohee Chung, Charmgil Hong
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Forecasting multivariate time series remains challenging due to complex cross-variable dependencies and the presence of heterogeneous external influences. This paper presents Spectrogram-Enhanced Multimodal Fusion (SEMF), which combines spectral and temporal representations for more accurate and robust forecasting. The target time series is transformed into Morlet wavelet spectrograms, from which a Vision Transformer encoder extracts localized, frequency-aware features. In parallel, exogenous variables, such as financial indicators and macroeconomic signals, are encoded via a Transformer to capture temporal dependencies and multivariate dynamics. A bidirectional cross-attention module integrates these modalities into a unified representation that preserves distinct signal characteristics while modeling cross-modal correlations. Applied to multiple commodity price forecasting tasks, SEMF achieves consistent improvements over seven competitive baselines across multiple forecasting horizons and evaluation metrics. These results demonstrate the effectiveness of multimodal fusion and spectrogram-based encoding in capturing multi-scale patterns within complex financial time series.
### Title:
          Falcon Perception
 - **Authors:** Aviraj Bevli, Sofian Chaybouti, Yasser Dahou, Hakim Hacid, Ngoc Dung Huynh, Phuc H. Le Khac, Sanath Narayan, Wamiq Reyaz Para, Ankit Singh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Perception-centric systems are typically implemented with a modular encoder-decoder pipeline: a vision backbone for feature extraction and a separate decoder (or late-fusion module) for task prediction. This raises a central question: is this architectural separation essential or can a single early-fusion stack do both perception and task modeling at scale? We introduce Falcon Perception, a unified dense Transformer that processes image patches and text tokens in a shared parameter space from the first layer, using a hybrid attention pattern (bidirectional among image tokens, causal for prediction tokens) to combine global visual context with autoregressive, variable-length instance generation. To keep dense outputs practical, Falcon Perception retains a lightweight token interface and decodes continuous spatial outputs with specialized heads, enabling parallel high-resolution mask prediction. Our design promotes simplicity: we keep a single scalable backbone and shift complexity toward data and training signals, adding only small heads where outputs are continuous and dense. On SA-Co, Falcon Perception improves mask quality to 68.0 Macro-F$_1$ compared to 62.3 of SAM3. We also introduce PBench, a benchmark targeting compositional prompts (OCR, spatial constraints, relations) and dense long-context regimes, where the model shows better gains. Finally, we extend the same early-fusion recipe to Falcon OCR: a compact 300M-parameter model which attains 80.3% on olmOCR and 88.64 on OmniDocBench.
### Title:
          SpatialStack: Layered Geometry-Language Fusion for 3D VLM Spatial Reasoning
 - **Authors:** Jiang Zhang, Shijie Zhou, Bangya Liu, Achuta Kadambi, Zhiwen Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large vision-language models (VLMs) still struggle with reliable 3D spatial reasoning, a core capability for embodied and physical AI systems. This limitation arises from their inability to capture fine-grained 3D geometry and spatial relationships. While recent efforts have introduced multi-view geometry transformers into VLMs, they typically fuse only the deep-layer features from vision and geometry encoders, discarding rich hierarchical signals and creating a fundamental bottleneck for spatial understanding. To overcome this, we propose SpatialStack, a general hierarchical fusion framework that progressively aligns vision, geometry, and language representations across the model hierarchy. Moving beyond conventional late-stage vision-geometry fusion, SpatialStack stacks and synchronizes multi-level geometric features with the language backbone, enabling the model to capture both local geometric precision and global contextual semantics. Building upon this framework, we develop VLM-SpatialStack, a model that achieves state-of-the-art performance on multiple 3D spatial reasoning benchmarks. Extensive experiments and ablations demonstrate that our multi-level fusion strategy consistently enhances 3D understanding and generalizes robustly across diverse spatial reasoning tasks, establishing SpatialStack as an effective and extensible design paradigm for vision-language-geometry integration in next-generation multimodal physical AI systems.
### Title:
          Evaluating Large and Lightweight Vision Models for Irregular Component Segmentation in E-Waste Disassembly
 - **Authors:** Xinyao Zhang, Chang Liu, Xiao Liang, Minghui Zheng, Sara Behdad
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precise segmentation of irregular and densely arranged components is essential for robotic disassembly and material recovery in electronic waste (e-waste) recycling. This study evaluates the impact of model architecture and scale on segmentation performance by comparing SAM2, a transformer-based vision model, with the lightweight YOLOv8 network. Both models were trained and tested on a newly collected dataset of 1,456 annotated RGB images of laptop components including logic boards, heat sinks, and fans, captured under varying illumination and orientation conditions. Data augmentation techniques, such as random rotation, flipping, and cropping, were applied to improve model robustness. YOLOv8 achieved higher segmentation accuracy (mAP50 = 98.8%, mAP50-95 = 85%) and stronger boundary precision than SAM2 (mAP50 = 8.4%). SAM2 demonstrated flexibility in representing diverse object structures but often produced overlapping masks and inconsistent contours. These findings show that large pre-trained models require task-specific optimization for industrial applications. The resulting dataset and benchmarking framework provide a foundation for developing scalable vision algorithms for robotic e-waste disassembly and circular manufacturing systems.
### Title:
          From None to All: Self-Supervised 3D Reconstruction via Novel View Synthesis
 - **Authors:** Ranran Huang, Weixun Luo, Ye Mao, Krystian Mikolajczyk
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we introduce NAS3R, a self-supervised feed-forward framework that jointly learns explicit 3D geometry and camera parameters with no ground-truth annotations and no pretrained priors. During training, NAS3R reconstructs 3D Gaussians from uncalibrated and unposed context views and renders target views using its self-predicted camera parameters, enabling self-supervised training from 2D photometric supervision. To ensure stable convergence, NAS3R integrates reconstruction and camera prediction within a shared transformer backbone regulated by masked attention, and adopts a depth-based Gaussian formulation that facilitates well-conditioned optimization. The framework is compatible with state-of-the-art supervised 3D reconstruction architectures and can incorporate pretrained priors or intrinsic information when available. Extensive experiments show that NAS3R achieves superior results to other self-supervised methods, establishing a scalable and geometry-aware paradigm for 3D reconstruction from unconstrained data. Code and models are publicly available at this https URL.
### Title:
          Copilot-Assisted Second-Thought Framework for Brain-to-Robot Hand Motion Decoding
 - **Authors:** Yizhe Li (1), Shixiao Wang (1), Jian K. Liu (1) ((1) University of Birmingham, Birmingham, United Kingdom)
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Motor kinematics prediction (MKP) from electroencephalography (EEG) is an important research area for developing movement-related brain-computer interfaces (BCIs). While traditional methods often rely on convolutional neural networks (CNNs) or recurrent neural networks (RNNs), Transformer-based models have shown strong ability in modeling long sequential EEG data. In this study, we propose a CNN-attention hybrid model for decoding hand kinematics from EEG during grasp-and-lift tasks, achieving strong performance in within-subject experiments. We further extend this approach to EEG-EMG multimodal decoding, which yields substantially improved results. Within-subject tests achieve PCC values of 0.9854, 0.9946, and 0.9065 for the X, Y, and Z axes, respectively, computed on the midpoint trajectory between the thumb and index finger, while cross-subject tests result in 0.9643, 0.9795, and 0.5852. The decoded trajectories from both modalities are then used to control a Franka Panda robotic arm in a MuJoCo simulation. To enhance trajectory fidelity, we introduce a copilot framework that filters low-confidence decoded points using a motion-state-aware critic within a finite-state machine. This post-processing step improves the overall within-subject PCC of EEG-only decoding to 0.93 while excluding fewer than 20% of the data points.
### Title:
          Over-Refusal and Representation Subspaces: A Mechanistic Analysis of Task-Conditioned Refusal in Aligned LLMs
 - **Authors:** Utsav Maskey, Mark Dras, Usman Naseem
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Aligned language models that are trained to refuse harmful requests also exhibit over-refusal: they decline safe instructions that seemingly resemble harmful instructions. A natural approach is to ablate the global refusal direction, steering the hidden-state vectors away or towards the harmful-refusal examples, but this corrects over-refusal only incidentally while disrupting the broader refusal mechanism. In this work, we analyse the representational geometry of both refusal types to understand why this happens. We show that harmful-refusal directions are task-agnostic and can be captured by a single global vector, whereas over-refusal directions are task-dependent: they reside within the benign task-representation clusters, vary across tasks, and span a higher-dimensional subspace. Linear probing confirms that the two refusal types are representationally distinct from the early transformer layers. These findings provide a mechanistic explanation of why global direction ablation alone cannot address over-refusal, and establish that task-specific geometric interventions are necessary.
### Title:
          SPROUT: A Scalable Diffusion Foundation Model for Agricultural Vision
 - **Authors:** Shuai Xiang, Wei Guo, James Burridge, Shouyang Liu, Hao Lu, Tokihiro Fukatsu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Foundation Models (VFM) pre-trained on large-scale unlabeled data have achieved remarkable success on general computer vision tasks, yet typically suffer from significant domain gaps when applied to agriculture. In this context, we introduce $SPROUT$ ($S$calable $P$lant $R$epresentation model via $O$pen-field $U$nsupervised $T$raining), a multi-crop, multi-task agricultural foundation model trained via diffusion denoising. SPROUT leverages a VAE-free Pixel-space Diffusion Transformer to learn rich, structure-aware representations through denoising and enabling efficient end-to-end training. We pre-train SPROUT on a curated dataset of 2.6 million high-quality agricultural images spanning diverse crops, growth stages, and environments. Extensive experiments demonstrate that SPROUT consistently outperforms state-of-the-art web-pretrained and agricultural foundation models across a wide range of downstream tasks, while requiring substantially lower pre-training cost. The code and model are available at this https URL.
### Title:
          LongCat-Next: Lexicalizing Modalities as Discrete Tokens
 - **Authors:** Meituan LongCat Team: Bin Xiao, Chao Wang, Chengjiang Li, Chi Zhang, Chong Peng, Hang Yu, Hao Yang, Haonan Yan, Haoze Sun, Haozhe Zhao, Hong Liu, Hui Su, Jiaqi Zhang, Jiawei Wang, Jing Li, Kefeng Zhang, Manyuan Zhang, Minhao Jing, Peng Pei, Quan Chen, Taofeng Xue, Tongxin Pan, Xiaotong Li, Xiaoyang Li, Xiaoyu Zhao, Xing Hu, Xinyang Lin, Xunliang Cai, Yan Bai, Yan Feng, Yanjie Li, Yao Qiu, Yerui Sun, Yifan Lu, Ying Luo, Yipeng Mei, Yitian Chen, Yuchen Xie, Yufang Liu, Yufei Chen, Yulei Qian, Yuqi Peng, Zhihang Yu, Zhixiong Han, Changran Wang, Chen Chen, Dian Zheng, Fengjiao Chen, Ge Yang, Haowei Guo, Haozhe Wang, Hongyu Li, Huicheng Jiang, Jiale Hong, Jialv Zou, Jiamu Li, Jianping Lin, Jiaxing Liu, Jie Yang, Jing Jin, Jun Kuang, Juncheng She, Kunming Luo, Kuofeng Gao, Lin Qiu, Linsen Guo, Mianqiu Huang, Qi Li, Qian Wang, Rumei Li, Siyu Ren, Wei Wang, Wenlong He, Xi Chen, Xiao Liu, Xiaoyu Li, Xu Huang, Xuanyu Zhu, Xuezhi Cao, Yaoming Zhu, Yifei Cao, Yimeng Jia, Yizhen Jiang, Yufei Gao, Zeyang Hu, Zhenlong Yuan, Zijian Zhang, Ziwen Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The prevailing Next-Token Prediction (NTP) paradigm has driven the success of large language models through discrete autoregressive modeling. However, contemporary multimodal systems remain language-centric, often treating non-linguistic modalities as external attachments, leading to fragmented architectures and suboptimal integration. To transcend this limitation, we introduce Discrete Native Autoregressive (DiNA), a unified framework that represents multimodal information within a shared discrete space, enabling a consistent and principled autoregressive modeling across modalities. A key innovation is the Discrete Native Any-resolution Visual Transformer (dNaViT), which performs tokenization and de-tokenization at arbitrary resolutions, transforming continuous visual signals into hierarchical discrete tokens. Building on this foundation, we develop LongCat-Next, a native multimodal model that processes text, vision, and audio under a single autoregressive objective with minimal modality-specific design. As an industrial-strength foundation model, it excels at seeing, painting, and talking within a single framework, achieving strong performance across a wide range of multimodal benchmarks. In particular, LongCat-Next addresses the long-standing performance ceiling of discrete vision modeling on understanding tasks and provides a unified approach to effectively reconcile the conflict between understanding and generation. As an attempt toward native multimodality, we open-source the LongCat-Next and its tokenizers, hoping to foster further research and development in the community. GitHub: this https URL
### Title:
          SPREAD: Spatial-Physical REasoning via geometry Aware Diffusion
 - **Authors:** Minzhang Li, Kuixiang Shao, Xuebing Li, Yuyang Jiao, Yinuo Bai, Hengan Zhou, Sixian Shen, Jiayuan Gu, Jingyi Yu
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated 3D scene generation is pivotal for applications spanning virtual reality, digital content creation, and Embodied AI. While computer graphics prioritizes aesthetic layouts, vision and robotics demand scenes that mirror real-world complexity which current data-driven methods struggle to achieve due to limited unstructured training data and insufficient spatial and physical modeling. We propose SPREAD, a diffusion-based framework that jointly learns spatial and physical relationships through a graph transformer, explicitly conditioning on posed scene point clouds for geometric awareness. Moreover, our model integrates differentiable guidance for collision avoidance, relational constraint, and gravity, ensuring physically coherent scenes without sacrificing relational context. Our experiments on 3D-FRONT and ProcTHOR datasets demonstrate state-of-the-art performance in spatial-relational reasoning and physical metrics. Moreover, \ours{} outperforms baselines in scene consistency and stability during pre- and post-physics simulation, proving its capability to generate simulation-ready environments for embodied AI agents.
### Title:
          OPRO: Orthogonal Panel-Relative Operators for Panel-Aware In-Context Image Generation
 - **Authors:** Sanghyeon Lee, Minwoo Lee, Euijin Shin, Kangyeol Kim, Seunghwan Choi, Jaegul Choo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a parameter-efficient adaptation method for panel-aware in-context image generation with pre-trained diffusion transformers. The key idea is to compose learnable, panel-specific orthogonal operators onto the backbone's frozen positional encodings. This design provides two desirable properties: (1) isometry, which preserves the geometry of internal features, and (2) same-panel invariance, which maintains the model's pre-trained intra-panel synthesis behavior. Through controlled experiments, we demonstrate that the effectiveness of our adaptation method is not tied to a specific positional encoding design but generalizes across diverse positional encoding regimes. By enabling effective panel-relative conditioning, the proposed method consistently improves in-context image-based instructional editing pipelines, including state-of-the-art approaches.
### Title:
          Amped: Adaptive Multi-stage Non-edge Pruning for Edge Detection
 - **Authors:** Yuhan Gao, Xinqing Li, Xin He, Bing Li, Xinzhong Zhu, Ming-Ming Cheng, Yun Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Edge detection is a fundamental image analysis task that underpins numerous high-level vision applications. Recent advances in Transformer architectures have significantly improved edge quality by capturing long-range dependencies, but this often comes with computational overhead. Achieving higher pixel-level accuracy requires increased input resolution, further escalating computational cost and limiting practical deployment. Building on the strong representational capacity of recent Transformer-based edge detectors, we propose an Adaptive Multi-stage non-edge Pruning framework for Edge Detection(Amped). Amped identifies high-confidence non-edge tokens and removes them as early as possible to substantially reduce computation, thus retaining high accuracy while cutting GFLOPs and accelerating inference with minimal performance loss. Moreover, to mitigate the structural complexity of existing edge detection networks and facilitate their integration into real-world systems, we introduce a simple yet high-performance Transformer-based model, termed Streamline Edge Detector(SED). Applied to both existing detectors and our SED, the proposed pruning strategy provides a favorable balance between accuracy and efficiency-reducing GFLOPs by up to 40% with only a 0.4% drop in ODS F-measure. In addition, despite its simplicity, SED achieves a state-of-the-art ODS F-measure of 86.5%. The code will be released.
### Title:
          Low-Rank Adaptation Reduces Catastrophic Forgetting in Sequential Transformer Encoder Fine-Tuning: Controlled Empirical Evidence and Frozen-Backbone Representation Probes
 - **Authors:** Ashish Pandey
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequential fine-tuning of pretrained language encoders often overwrites previously acquired capabilities, but the forgetting behavior of parameter-efficient updates remains under-characterized. We present a controlled empirical study of Low-Rank Adaptation (LoRA) in sequential transformer encoder fine-tuning with companion representation probes that test a frozen-backbone explanation of its robustness. In five full-validation BERT-base reruns on an RTE->MRPC->CoLA->SST-2 sequence, full fine-tuning yields 19.9%+/-4.8% average forgetting, whereas standard LoRA (r=8, query/value modules) yields 0.6%+/-1.4% (paired t-test, p=0.002, Cohen's d_s=3.12). Task-level analyses confirm this reduction is not merely an aggregate effect. Secondary experiments on RoBERTa-base show the same pattern, and the strongest EWC baseline remains at 15.5%+/-1.4% forgetting. A six-task extension reveals that low average forgetting can hide strong task-level heterogeneity. Fine-grained freezing ablations show a marked forgetting drop once frozen parameters exceed roughly 95%, with classifier-only and shallow-adapter baselines approaching LoRA. Companion task-similarity probes in GPT-2 and RoBERTa show the same directional story: frozen-backbone regimes preserve higher inter-task similarity than full fine-tuning, gradual unfreezing weakens stability, and full fine-tuning exhibits its clearest divergence at the final transformer layer. These results support a restrained mechanistic interpretation: LoRA helps largely because backbone freezing preserves a more stable shared feature scaffold. We position standard LoRA as both a strong empirical baseline for sequential encoder adaptation and a useful probe of how selective plasticity shapes interference in transformer continual learning.
### Title:
          Look, Compare and Draw: Differential Query Transformer for Automatic Oil Painting
 - **Authors:** Lingyu Liu, Yaxiong Wang, Li Zhu, Lizi Liao, Zhedong Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work introduces a new approach to automatic oil painting that emphasizes the creation of dynamic and expressive brushstrokes. A pivotal challenge lies in mitigating the duplicate and common-place strokes, which often lead to less aesthetic outcomes. Inspired by the human painting process, \ie, observing, comparing, and drawing, we incorporate differential image analysis into a neural oil painting model, allowing the model to effectively concentrate on the incremental impact of successive brushstrokes. To operationalize this concept, we propose the Differential Query Transformer (DQ-Transformer), a new architecture that leverages differentially derived image representations enriched with positional encoding to guide the stroke prediction process. This integration enables the model to maintain heightened sensitivity to local details, resulting in more refined and nuanced stroke generation. Furthermore, we incorporate adversarial training into our framework, enhancing the accuracy of stroke prediction and thereby improving the overall realism and fidelity of the synthesized paintings. Extensive qualitative evaluations, complemented by a controlled user study, validate that our DQ-Transformer surpasses existing methods in both visual realism and artistic authenticity, typically achieving these results with fewer strokes. The stroke-by-stroke painting animations are available on our project website.
### Title:
          SkyNet: Belief-Aware Planning for Partially-Observable Stochastic Games
 - **Authors:** Adam Haile
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In 2019, Google DeepMind released MuZero, a model-based reinforcement learning method that achieves strong results in perfect-information games by combining learned dynamics models with Monte Carlo Tree Search (MCTS). However, comparatively little work has extended MuZero to partially observable, stochastic, multi-player environments, where agents must act under uncertainty about hidden state. Such settings arise not only in card games but in domains such as autonomous negotiation, financial trading, and multi-agent robotics. In the absence of explicit belief modeling, MuZero's latent encoding has no dedicated mechanism for representing uncertainty over unobserved variables. To address this, we introduce SkyNet (Belief-Aware MuZero), which adds ego-conditioned auxiliary heads for winner prediction and rank estimation to the standard MuZero architecture. These objectives encourage the latent state to retain information predictive of outcomes under partial observability, without requiring explicit belief-state tracking or changes to the search algorithm. We evaluate SkyNet on Skyjo, a partially observable, non-zero-sum, stochastic card game, using a decision-granularity environment, transformer-based encoding, and a curriculum of heuristic opponents with self-play. In 1000-game head-to-head evaluations at matched checkpoints, SkyNet achieves a 75.3% peak win rate against the baseline (+194 Elo, $p < 10^{-50}$). SkyNet also outperforms the baseline against heuristic opponents (0.720 vs.\ 0.466 win rate). Critically, the belief-aware model initially underperforms the baseline but decisively surpasses it once training throughput is sufficient, suggesting that belief-aware auxiliary supervision improves learned representations under partial observability, but only given adequate data flow.
### Title:
          Feeds Don't Tell the Whole Story: Measuring Online-Offline Emotion Alignment
 - **Authors:** Sina Elahimanesh, Mohammadali Mohammadkhani, Shohreh Kasaei
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In contemporary society, social media is deeply integrated into daily life, yet emotional expression often differs between real and online contexts. We studied the Persian community on X to explore this gap, designing a human-centered pipeline to measure alignment between real-world and social media emotions. Recent tweets and images of participants were collected and analyzed using Transformers-based text and image sentiment modules. Friends of participants provided insights into their real-world emotions, which were compared with online expressions using a distance criterion. The study involved N=105 participants, 393 friends, over 8,300 tweets, and 2,000 media images. Results showed only 28% similarity between images and real-world emotions, while tweets aligned about 76% with participants' real-life feelings. Statistical analyses confirmed significant disparities in sentiment proportions across images, tweets, and friends' perceptions, highlighting differences in emotional expression between online and offline environments and demonstrating practical utility of the proposed pipeline for understanding digital self-presentation.
### Title:
          Tracking without Seeing: Geospatial Inference using Encrypted Traffic from Distributed Nodes
 - **Authors:** Sadik Yagiz Yetim, Gaofeng Dong, Isaac-Neil Zanoria, Ronit Barman, Maggie Wigness, Tarek Abdelzaher, Mani Srivastava, Suhas Diggavi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate observation of dynamic environments traditionally relies on synthesizing raw, signal-level information from multiple distributed sensors. This work investigates an alternative approach: performing geospatial inference using only encrypted packet-level information, without access to the raw sensory data. We further explore how this indirect information can be fused with directly available sensory data to extend overall inference capabilities. We introduce GraySense, a learning-based framework that performs geospatial object tracking by analyzing encrypted wireless video transmission traffic, such as packet sizes, from cameras with inaccessible streams. GraySense leverages the inherent relationship between scene dynamics and transmitted packet sizes to infer object motion. The framework consists of two stages: (1) a Packet Grouping module that identifies frame boundaries and estimates frame sizes from encrypted network traffic, and (2) a Tracker module, based on a Transformer encoder with a recurrent state, which fuses indirect packet-based inputs with optional direct camera-based inputs to estimate the object's position. Extensive experiments with realistic videos from the CARLA simulator and emulated networks under varying conditions show that GraySense achieves 2.33 meters tracking error (Euclidean distance) without raw signal access, within the dimensions of tracked objects (4.61m x 1.93m). To our knowledge, this capability has not been previously demonstrated, expanding the use of latent signals for sensing.
### Title:
          RG-TTA: Regime-Guided Meta-Control for Test-Time Adaptation in Streaming Time Series
 - **Authors:** Indar Kumar, Akanksha Tiwari, Sai Krishna Jasti, Ankit Hemant Lade
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Test-time adaptation (TTA) enables neural forecasters to adapt to distribution shifts in streaming time series, but existing methods apply the same adaptation intensity regardless of the nature of the shift. We propose Regime-Guided Test-Time Adaptation (RG-TTA), a meta-controller that continuously modulates adaptation intensity based on distributional similarity to previously-seen regimes. Using an ensemble of Kolmogorov-Smirnov, Wasserstein-1, feature-distance, and variance-ratio metrics, RG-TTA computes a similarity score for each incoming batch and uses it to (i) smoothly scale the learning rate -- more aggressive for novel distributions, conservative for familiar ones -- and (ii) control gradient effort via loss-driven early stopping rather than fixed budgets, allowing the system to allocate exactly the effort each batch requires. As a supplementary mechanism, RG-TTA gates checkpoint reuse from a regime memory, loading stored specialist models only when they demonstrably outperform the current model (loss improvement >= 30%). RG-TTA is model-agnostic and strategy-composable: it wraps any forecaster exposing train/predict/save/load interfaces and enhances any gradient-based TTA method. We demonstrate three compositions -- RG-TTA, RG-EWC, and RG-DynaTTA -- and evaluate 6 update policies (3 baselines + 3 regime-guided variants) across 4 compact architectures (GRU, iTransformer, PatchTST, DLinear), 14 datasets (6 real-world multivariate benchmarks + 8 synthetic regime scenarios), and 4 forecast horizons (96, 192, 336, 720) under a streaming evaluation protocol with 3 random seeds (672 experiments total). Regime-guided policies achieve the lowest MSE in 156 of 224 seed-averaged experiments (69.6%), with RG-EWC winning 30.4% and RG-TTA winning 29.0%. Overall, RG-TTA reduces MSE by 5.7% vs TTA while running 5.5% faster; RG-EWC reduces MSE by 14.1% vs standalone EWC.
### Title:
          Rényi Entropy: A New Token Pruning Metric for Vision Transformers
 - **Authors:** Wei-Yuan Su, Ruijie Zhang, Zheng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) achieve state-of-the-art performance but suffer from the $O(N^2)$ complexity of self-attention, making inference costly for high-resolution inputs. To address this bottleneck, token pruning has emerged as a critical technique to accelerate inference. Most existing methods rely on the [CLS] token to estimate patch importance. However, we argue that the [CLS] token can be unreliable in early layers where semantic representations are still immature. As a result, pruning in the early layer often leads to inaccurate importance estimation and unnecessary information loss. In this work, we propose a training-free token importance metric, namely Col-Ln, which is derived from Rényi entropy that enables the identification of informative tokens from the first layer of the network, thereby enabling more reliable pruning in token reduction. Extensive experiments on ViTs and Large Vision-Language Models (LVLMs) demonstrate that our approach consistently outperforms state-of-the-art pruning methods across diverse benchmarks.
### Title:
          Physics-Guided Transformer (PGT): Physics-Aware Attention Mechanism for PINNs
 - **Authors:** Ehsan Zeraatkar, Rodion Podorozhny, Jelena Tešić
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing continuous physical fields from sparse, irregular observations is a central challenge in scientific machine learning, particularly for systems governed by partial differential equations (PDEs). Existing physics-informed methods typically enforce governing equations as soft penalty terms during optimization, often leading to gradient imbalance, instability, and degraded physical consistency under limited data. We introduce the Physics-Guided Transformer (PGT), a neural architecture that embeds physical structure directly into the self-attention mechanism. Specifically, PGT incorporates a heat-kernel-derived additive bias into attention logits, encoding diffusion dynamics and temporal causality within the representation. Query coordinates attend to these physics-conditioned context tokens, and the resulting features are decoded using a FiLM-modulated sinusoidal implicit network that adaptively controls spectral response. We evaluate PGT on the one-dimensional heat equation and two-dimensional incompressible Navier-Stokes systems. In sparse 1D reconstruction with 100 observations, PGT achieves a relative L2 error of 5.9e-3, significantly outperforming both PINNs and sinusoidal representations. In the 2D cylinder wake problem, PGT uniquely achieves both low PDE residual (8.3e-4) and competitive relative error (0.034), outperforming methods that optimize only one objective. These results demonstrate that embedding physics within attention improves stability, generalization, and physical fidelity under data-scarce conditions.
### Title:
          ExFusion: Efficient Transformer Training via Multi-Experts Fusion
 - **Authors:** Jiacheng Ruan, Daize Dong, Xiaoye Qu, Tong Zhu, Ting Liu, Yuzhuo Fu, Yu Cheng, Suncheng Xiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mixture-of-Experts (MoE) models substantially improve performance by increasing the capacity of dense architectures. However, directly training MoE models requires considerable computational resources and introduces extra overhead in parameter storage and deployment. Therefore, it is critical to develop an approach that leverages the multi-expert capability of MoE to enhance performance while incurring minimal additional cost. To this end, we propose a novel pre-training approach, termed ExFusion, which improves the efficiency of Transformer training through multi-expert fusion. Specifically, during the initialization phase, ExFusion upcycles the feed-forward network (FFN) of the Transformer into a multi-expert configuration, where each expert is assigned a weight for later parameter fusion. During training, these weights allow multiple experts to be fused into a single unified expert equivalent to the original FFN, which is subsequently used for forward computation. As a result, ExFusion introduces multi-expert characteristics into the training process while incurring only marginal computational cost compared to standard dense training. After training, the learned weights are used to integrate multi-experts into a single unified expert, thereby eliminating additional overhead in storage and deployment. Extensive experiments on a variety of computer vision and natural language processing tasks demonstrate the effectiveness of the proposed method.
### Title:
          What an Autonomous Agent Discovers About Molecular Transformer Design: Does It Transfer?
 - **Authors:** Edward Wijaya
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning models for drug-like molecules and proteins overwhelmingly reuse transformer architectures designed for natural language, yet whether molecular sequences benefit from different designs has not been systematically tested. We deploy autonomous architecture search via an agent across three sequence types (SMILES, protein, and English text as control), running 3,106 experiments on a single GPU. For SMILES, architecture search is counterproductive: tuning learning rates and schedules alone outperforms the full search (p = 0.001). For natural language, architecture changes drive 81% of improvement (p = 0.009). Proteins fall between the two. Surprisingly, although the agent discovers distinct architectures per domain (p = 0.004), every innovation transfers across all three domains with <1% degradation, indicating that the differences reflect search-path dependence rather than fundamental biological requirements. We release a decision framework and open-source toolkit for molecular modeling teams to choose between autonomous architecture search and simple hyperparameter tuning.
### Title:
          Efficient Domain Adaptation for Text Line Recognition via Decoupled Language Models
 - **Authors:** Arundhathi Dev, Justin Zhan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Optical character recognition remains critical infrastructure for document digitization, yet state-of-the-art performance is often restricted to well-resourced institutions by prohibitive computational barriers. End-to-end transformer architectures achieve strong accuracy but demand hundreds of GPU hours for domain adaptation, limiting accessibility for practitioners and digital humanities scholars. We present a modular detection-and-correction framework that achieves near-SOTA accuracy with single-GPU training. Our approach decouples lightweight visual character detection (domain-agnostic) from domain-specific linguistic correction using pretrained sequence models including T5, ByT5, and BART. By training the correctors entirely on synthetic noise, we enable annotation-free domain adaptation without requiring labeled target images. Evaluating across modern clean handwriting, cursive script, and historical documents, we identify a critical "Pareto frontier" in architecture selection: T5-Base excels on modern text with standard vocabulary, whereas ByT5-Base dominates on historical documents by reconstructing archaic spellings at the byte level. Our results demonstrate that this decoupled paradigm matches end-to-end transformer accuracy while reducing compute by approximately 95%, establishing a viable, resource-efficient alternative to monolithic OCR architectures.
### Title:
          Skillful Kilometer-Scale Regional Weather Forecasting via Global and Regional Coupling
 - **Authors:** Weiqi Chen, Wenwei Wang, Qilong Yuan, Lefei Shen, Bingqing Peng, Jiawei Chen, Bo Wu, Liang Sun
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data-driven weather models have advanced global medium-range forecasting, yet high-resolution regional prediction remains challenging due to unresolved multiscale interactions between large-scale dynamics and small-scale processes such as terrain-induced circulations and coastal effects. This paper presents a global-regional coupling framework for kilometer-scale regional weather forecasting that synergistically couples a pretrained Transformer-based global model with a high-resolution regional network via a novel bidirectional coupling module, ScaleMixer. ScaleMixer dynamically identifies meteorologically critical regions through adaptive key-position sampling and enables cross-scale feature interaction through dedicated attention mechanisms. The framework produces forecasts at $0.05^\circ$ ($\sim 5 \mathrm{km}$ ) and 1-hour resolution over China, significantly outperforming operational NWP and AI baselines on both gridded reanalysis data and real-time weather station observations. It exhibits exceptional skill in capturing fine-grained phenomena such as orographic wind patterns and Foehn warming, demonstrating effective global-scale coherence with high-resolution fidelity. The code is available at this https URL.
### Title:
          Policy-Controlled Generalized Share: A General Framework with a Transformer Instantiation for Strictly Online Switching-Oracle Tracking
 - **Authors:** Hongkai Hu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Statistical Finance (q-fin.ST)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Static regret to a single expert is often the wrong target for strictly online prediction under non-stationarity, where the best expert may switch repeatedly over time. We study Policy-Controlled Generalized Share (PCGS), a general strictly online framework in which the generalized-share recursion is fixed while the post-loss update controls are allowed to vary adaptively. Its principal instantiation in this paper is PCGS-TF, which uses a causal Transformer as an update controller: after round t finishes and the loss vector is observed, the Transformer outputs the controls that map w_t to w_{t+1} without altering the already committed decision w_t. Under admissible post-loss update controls, we obtain a pathwise weighted regret guarantee for general time-varying learning rates, and a standard dynamic-regret guarantee against any expert path with at most S switches under the constant-learning-rate specialization. Empirically, on a controlled synthetic suite with exact dynamic-programming switching-oracle evaluation, PCGS-TF attains the lowest mean dynamic regret in all seven non-stationary families, with its advantage increasing for larger expert pools. On a reproduced household-electricity benchmark, PCGS-TF also achieves the lowest normalized dynamic regret for S = 5, 10, and 20.
### Title:
          Variational Neurons in Transformers for Language Modeling
 - **Authors:** Yves Ruffenach
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers for language modeling usually rely on deterministic internal computation, with uncertainty expressed mainly at the output layer. We introduce variational neurons into Transformer feed-forward computation so that uncertainty becomes part of the internal computation itself. Concretely, we replace deterministic feed-forward units with local variational units based on EVE while preserving the overall Transformer backbone. We evaluate this design in compact next-token language-modeling settings. We compare deterministic and variational variants with both predictive and probabilistic criteria. Alongside negative log-likelihood, perplexity and accuracy, we analyze calibration, conditional variance, mutual information and latent-usage statistics. The resulting picture is clear. Variational neurons integrate stably into Transformers, preserve strong predictive performance and produce informative uncertainty signals. The experiments also show that task quality, useful depth and internal stability are distinct properties. These results establish variational Transformers as a practical form of uncertainty-aware language modeling. They show that Transformers can predict with an explicit internal structure of uncertainty, which supports stronger probabilistic evaluation and a more informative analysis of model behavior.
### Title:
          DiffAttn: Diffusion-Based Drivers' Visual Attention Prediction with LLM-Enhanced Semantic Reasoning
 - **Authors:** Weimin Liu, Qingkun Li, Jiyuan Qiu, Wenjun Wang, Joshua H. Meng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Drivers' visual attention provides critical cues for anticipating latent hazards and directly shapes decision-making and control maneuvers, where its absence can compromise traffic safety. To emulate drivers' perception patterns and advance visual attention prediction for intelligent vehicles, we propose DiffAttn, a diffusion-based framework that formulates this task as a conditional diffusion-denoising process, enabling more accurate modeling of drivers' attention. To capture both local and global scene features, we adopt Swin Transformer as encoder and design a decoder that combines a Feature Fusion Pyramid for cross-layer interaction with dense, multi-scale conditional diffusion to jointly enhance denoising learning and model fine-grained local and global scene contexts. Additionally, a large language model (LLM) layer is incorporated to enhance top-down semantic reasoning and improve sensitivity to safety-critical cues. Extensive experiments on four public datasets demonstrate that DiffAttn achieves state-of-the-art (SoTA) performance, surpassing most video-based, top-down-feature-driven, and LLM-enhanced baselines. Our framework further supports interpretable driver-centric scene understanding and has the potential to improve in-cabin human-machine interaction, risk perception, and drivers' state measurement in intelligent vehicles.
### Title:
          VulnScout-C: A Lightweight Transformer for C Code Vulnerability Detection
 - **Authors:** Aymen Lassoued, Nacef Mbarek, Bechir Dardouri, Bassem Ouni, Qing Li, Fakhri Karray
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vulnerability detection in C programs is a critical challenge in software security. Although large language models (LLMs) achieve strong detection performance, their multi-billion-parameter scale makes them impractical for integration into development workflows requiring low latency and continuous analysis. We introduce VULNSCOUT-C, a compact transformer architecture with 693M total parameters (353M active during inference), derived from the Qwen model family and optimized for C code vulnerability detection. Alongside the model, we present VULNSCOUT, a new 33,565-sample curated dataset generated through a controlled multi-agent pipeline with formal verification, designed to fill coverage gaps in existing benchmarks across underrepresented CWE categories. Evaluated on a standardized C vulnerability detection benchmark, VULNSCOUT-C outperforms all evaluated baselines, including state-of-the-art reasoning LLMs and commercial static analysis tools, while offering a fraction of their inference cost. These results demonstrate that task-specialized compact architectures can match or even outperform the detection capability of models orders of magnitude larger, making continuous, low-latency vulnerability analysis practical within real-world development workflows.
### Title:
          Beyond Scanpaths: Graph-Based Gaze Simulation in Dynamic Scenes
 - **Authors:** Luke Palmer, Petar Palasek, Hazem Abdelkawy
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurately modelling human attention is essential for numerous computer vision applications, particularly in the domain of automotive safety. Existing methods typically collapse gaze into saliency maps or scanpaths, treating gaze dynamics only implicitly. We instead formulate gaze modelling as an autoregressive dynamical system and explicitly unroll raw gaze trajectories over time, conditioned on both gaze history and the evolving environment. Driving scenes are represented as gaze-centric graphs processed by the Affinity Relation Transformer (ART), a heterogeneous graph transformer that models interactions between driver gaze, traffic objects, and road structure. We further introduce the Object Density Network (ODN) to predict next-step gaze distributions, capturing the stochastic and object-centric nature of attentional shifts in complex environments. We also release Focus100, a new dataset of raw gaze data from 30 participants viewing egocentric driving footage. Trained directly on raw gaze, without fixation filtering, our unified approach produces more natural gaze trajectories, scanpath dynamics, and saliency maps than existing attention models, offering valuable insights for the temporal modelling of human attention in dynamic environments.
### Title:
          Deep Research of Deep Research: From Transformer to Agent, From AI to AI for Science
 - **Authors:** Yipeng Yu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the advancement of large language models (LLMs) in their knowledge base and reasoning capabilities, their interactive modalities have evolved from pure text to multimodality and further to agentic tool use. Consequently, their applications have broadened from question answering to AI assistants and now to general-purpose agents. Deep research (DR) represents a prototypical vertical application for general-purpose agents, which represents an ideal approach for intelligent information processing and assisting humans in discovering and solving problems, with the goal of reaching or even surpassing the level of top human scientists. This paper provides a deep research of deep research. We articulate a clear and precise definition of deep research and unify perspectives from industry's deep research and academia's AI for Science (AI4S) within a developmental framework. We position LLMs and Stable Diffusion as the twin pillars of generative AI, and lay out a roadmap evolving from the Transformer to agents. We examine the progress of AI4S across various disciplines. We identify the predominant paradigms of human-AI interaction and prevailing system architectures, and discuss the major challenges and fundamental research issues that remain. AI supports scientific innovation, and science also can contribute to AI growth (Science for AI, S4AI). We hope this paper can help bridge the gap between the AI and AI4S communities.
### Title:
          Critic-Free Deep Reinforcement Learning for Maritime Coverage Path Planning on Irregular Hexagonal Grids
 - **Authors:** Carlos S. Sepúlveda, Gonzalo A. Ruz
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Neural and Evolutionary Computing (cs.NE); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Maritime surveillance missions, such as search and rescue and environmental monitoring, rely on the efficient allocation of sensing assets over vast and geometrically complex areas. Traditional Coverage Path Planning (CPP) approaches depend on decomposition techniques that struggle with irregular coastlines, islands, and exclusion zones, or require computationally expensive re-planning for every instance. We propose a Deep Reinforcement Learning (DRL) framework to solve CPP on hexagonal grid representations of irregular maritime areas. Unlike conventional methods, we formulate the problem as a neural combinatorial optimization task where a Transformer-based pointer policy autoregressively constructs coverage tours. To overcome the instability of value estimation in long-horizon routing problems, we implement a critic-free Group-Relative Policy Optimization (GRPO) scheme. This method estimates advantages through within-instance comparisons of sampled trajectories rather than relying on a value function. Experiments on 1,000 unseen synthetic maritime environments demonstrate that a trained policy achieves a 99.0% Hamiltonian success rate, more than double the best heuristic (46.0%), while producing paths 7% shorter and with 24% fewer heading changes than the closest baseline. All three inference modes (greedy, stochastic sampling, and sampling with 2-opt refinement) operate under 50~ms per instance on a laptop GPU, confirming feasibility for real-time on-board deployment.
### Title:
          EdgeDiT: Hardware-Aware Diffusion Transformers for Efficient On-Device Image Generation
 - **Authors:** Sravanth Kodavanti, Manjunath Arveti, Sowmya Vajrala, Srinivas Miriyala, Vikram N R
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiT) have established a new state-of-the-art in high-fidelity image synthesis; however, their massive computational complexity and memory requirements hinder local deployment on resource-constrained edge devices. In this paper, we introduce EdgeDiT, a family of hardware-efficient generative transformers specifically engineered for mobile Neural Processing Units (NPUs), such as the Qualcomm Hexagon and Apple Neural Engine (ANE). By leveraging a hardware-aware optimization framework, we systematically identify and prune structural redundancies within the DiT backbone that are particularly taxing for mobile data-flows. Our approach yields a series of lightweight models that achieve a 20-30% reduction in parameters, a 36-46% decrease in FLOPs, and a 1.65-fold reduction in on-device latency without sacrificing the scaling advantages or the expressive capacity of the original transformer architecture. Extensive benchmarking demonstrates that EdgeDiT offers a superior Pareto-optimal trade-off between Frechet Inception Distance (FID) and inference latency compared to both optimized mobile U-Nets and vanilla DiT variants. By enabling responsive, private, and offline generative AI directly on-device, EdgeDiT provides a scalable blueprint for transitioning large-scale foundation models from high-end GPUs to the palm of the user.
### Title:
          Active Stereo-Camera Outperforms Multi-Sensor Setup in ACT Imitation Learning for Humanoid Manipulation
 - **Authors:** Robin Kühn, Moritz Schappler, Thomas Seel, Dennis Bank
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The complexity of teaching humanoid robots new tasks is one of the major reasons hindering their widespread adoption in the industry. While Imitation Learning (IL), particularly Action Chunking with Transformers (ACT), enables rapid task acquisition, there is no consensus yet on the optimal sensory hardware required for manipulation tasks. This paper benchmarks 14 sensor combinations on the Unitree G1 humanoid robot equipped with three-finger hands for two manipulation tasks. We explicitly evaluate the integration of tactile and proprioceptive modalities alongside active vision. Our analysis demonstrates that strategic sensor selection can outperform complex configurations in data-limited regimes while reducing computational overhead. We develop an open-source Unified Ablation Framework that utilizes sensor masking on a comprehensive master dataset. Results indicate that additional modalities often degrade performance for IL with limited data. A minimal active stereo-camera setup outperformed complex multi-sensor configurations, achieving 87.5% success in a spatial generalization task and 94.4% in a structured manipulation task. Conversely, adding pressure sensors to this setup reduced success to 67.3% in the latter task due to a low signal-to-noise ratio. We conclude that in data-limited regimes, active vision offers a superior trade-off between robustness and complexity. While tactile modalities may require larger datasets to be effective, our findings validate that strategic sensor selection is critical for designing an efficient learning process.
### Title:
          Next-Token Prediction and Regret Minimization
 - **Authors:** Mehryar Mohri, Clayton Sanford, Jon Schneider, Kiran Vodrahalli, Yifan Wu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Science and Game Theory (cs.GT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We consider the question of how to employ next-token prediction algorithms in adversarial online decision-making environments. Specifically, if we train a next-token prediction model on a distribution $\mathcal{D}$ over sequences of opponent actions, when is it the case that the induced online decision-making algorithm (by approximately best responding to the model's predictions) has low adversarial regret (i.e., when is $\mathcal{D}$ a \emph{low-regret distribution})? For unbounded context windows (where the prediction made by the model can depend on all the actions taken by the adversary thus far), we show that although not every distribution $\mathcal{D}$ is a low-regret distribution, every distribution $\mathcal{D}$ is exponentially close (in TV distance) to one low-regret distribution, and hence sublinear regret can always be achieved at negligible cost to the accuracy of the original next-token prediction model. In contrast to this, for bounded context windows (where the prediction made by the model can depend only on the past $w$ actions taken by the adversary, as may be the case in modern transformer architectures), we show that there are some distributions $\mathcal{D}$ of opponent play that are $\Theta(1)$-far from any low-regret distribution $\mathcal{D'}$ (even when $w = \Omega(T)$ and such distributions exist). Finally, we complement these results by showing that the unbounded context robustification procedure can be implemented by layers of a standard transformer architecture, and provide empirical evidence that transformer models can be efficiently trained to represent these new low-regret distributions.
### Title:
          Compressing Transformer Language Models via Matrix Product Operator Decomposition: A Case Study on PicoGPT
 - **Authors:** Younes Javanmard, Tanmoy Pandit, Masoud Mardani
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Data Analysis, Statistics and Probability (physics.data-an)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based language models achieve strong performance across NLP tasks, but their quadratic parameter scaling with hidden dimension makes deployment on resource-constrained hardware expensive. We study Matrix Product Operator (MPO) decomposition as a principled compression method for transformers. MPO factorises weight matrices into chains of low-rank cores, with approximation quality controlled by the bond dimension chi. We replace every this http URL layer in PicoGPT, a GPT-2-style character-level language model with about 1M parameters, with an MPOLinear module parameterised as an MPO chain. Cores are initialised either by TT-SVD from pretrained dense weights or from random initialisation, and trained using standard PyTorch autograd without a custom backward pass. We derive balanced factorisation schemes for the five distinct weight shapes in PicoGPT and evaluate bond dimensions chi in {4, 8, 16, 32} on Tiny Shakespeare. MPO compression achieves up to 13x compression per transformer block at chi = 4. At chi = 16, the model uses 191,872 parameters instead of 1,020,224 while retaining 97.7% of baseline token accuracy (51.6% vs 52.8%). Reconstruction error follows the expected trend and is lower for three-site than two-site factorisations at the same bond dimension. The chi = 8 model gives the best accuracy per parameter, exceeding the dense baseline by 2.7x on this metric. These results show that MPO parameterisation is a practical and theoretically grounded alternative to low-rank methods and unstructured pruning for transformer compression.
### Title:
          Seen2Scene: Completing Realistic 3D Scenes with Visibility-Guided Flow
 - **Authors:** Quan Meng, Yujin Chen, Lei Li, Matthias Nießner, Angela Dai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Seen2Scene, the first flow matching-based approach that trains directly on incomplete, real-world 3D scans for scene completion and generation. Unlike prior methods that rely on complete and hence synthetic 3D data, our approach introduces visibility-guided flow matching, which explicitly masks out unknown regions in real scans, enabling effective learning from real-world, partial observations. We represent 3D scenes using truncated signed distance field (TSDF) volumes encoded in sparse grids and employ a sparse transformer to efficiently model complex scene structures while masking unknown regions. We employ 3D layout boxes as an input conditioning signal, and our approach is flexibly adapted to various other inputs such as text or partial scans. By learning directly from real-world, incomplete 3D scans, Seen2Scene enables realistic 3D scene completion for complex, cluttered real environments. Experiments demonstrate that our model produces coherent, complete, and realistic 3D scenes, outperforming baselines in completion accuracy and generation quality.
### Title:
          T-Norm Operators for EU AI Act Compliance Classification: An Empirical Comparison of Lukasiewicz, Product, and Gödel Semantics in a Neuro-Symbolic Reasoning System
 - **Authors:** Adam Laabs
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a first comparative pilot study of three t-norm operators -- Lukasiewicz (T_L), Product (T_P), and Gödel (T_G) - as logical conjunction mechanisms in a neuro-symbolic reasoning system for EU AI Act compliance classification. Using the LGGT+ (Logic-Guided Graph Transformers Plus) engine and a benchmark of 1035 annotated AI system descriptions spanning four risk categories (prohibited, high_risk, limited_risk, minimal_risk), we evaluate classification accuracy, false positive and false negative rates, and operator behaviour on ambiguous cases. At n=1035, all three operators differ significantly (McNemar p<0.001). T_G achieves highest accuracy (84.5%) and best borderline recall (85%), but introduces 8 false positives (0.8%) via min-semantics over-classification. T_L and T_P maintain zero false positives, with T_P outperforming T_L (81.2% vs. 78.5%). Our principal findings are: (1) operator choice is secondary to rule base completeness; (2) T_L and T_P maintain zero false positives but miss borderline cases; (3) T_G's min-semantics achieves higher recall at cost of 0.8% false positive rate; (4) a mixed-semantics classifier is the productive next step. We release the LGGT+ core engine (201/201 tests passing) and benchmark dataset (n=1035) under Apache 2.0.
### Title:
          Information-Theoretic Limits of Safety Verification for Self-Improving Systems
 - **Authors:** Arsenios Scrivens
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Can a safety gate permit unbounded beneficial self-modification while maintaining bounded cumulative risk? We formalize this question through dual conditions -- requiring sum delta_n < infinity (bounded risk) and sum TPR_n = infinity (unbounded utility) -- and establish a theory of their (in)compatibility. Classification impossibility (Theorem 1): For power-law risk schedules delta_n = O(n^{-p}) with p > 1, any classifier-based gate under overlapping safe/unsafe distributions satisfies TPR_n <= C_alpha * delta_n^beta via Holder's inequality, forcing sum TPR_n < infinity. This impossibility is exponent-optimal (Theorem 3). A second independent proof via the NP counting method (Theorem 4) yields a 13% tighter bound without Holder's inequality. Universal finite-horizon ceiling (Theorem 5): For any summable risk schedule, the exact maximum achievable classifier utility is U*(N, B) = N * TPR_NP(B/N), growing as exp(O(sqrt(log N))) -- subpolynomial. At N = 10^6 with budget B = 1.0, a classifier extracts at most U* ~ 87 versus a verifier's ~500,000. Verification escape (Theorem 2): A Lipschitz ball verifier achieves delta = 0 with TPR > 0, escaping the impossibility. Formal Lipschitz bounds for pre-LayerNorm transformers under LoRA enable LLM-scale verification. The separation is strict. We validate on GPT-2 (d_LoRA = 147,456): conditional delta = 0 with TPR = 0.352. Comprehensive empirical validation is in the companion paper [D2].
### Title:
          GPU-Accelerated Optimization of Transformer-Based Neural Networks for Real-Time Inference
 - **Authors:** Soutrik Mukherjee, Sangwhan Cha
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents the design and evaluation of a GPU-accelerated inference pipeline for transformer models using NVIDIA TensorRT with mixed-precision optimization. We evaluate BERT-base (110M parameters) and GPT-2 (124M parameters) across batch sizes from 1 to 32 and sequence lengths from 32 to 512. The system achieves up to 64.4x speedup over CPU baselines, sub-10 ms latency for single-sample inference, and a 63 percent reduction in memory usage. We introduce a hybrid precision strategy that preserves FP32 for numerically sensitive operations such as softmax and layer normalization, while applying FP16 to linear layers. This approach maintains high numerical fidelity (cosine similarity >= 0.9998 relative to baseline outputs) and eliminates NaN instability. The pipeline is implemented as a modular, containerized system that enables reproducible benchmarking across more than 360 configurations. Cross-GPU validation on an NVIDIA A100 shows consistent FP16 speedup ratios between 1.84x and 2.00x, along with stable numerical behavior. Downstream evaluation on SST-2 demonstrates no accuracy degradation under hybrid precision. Validation on WikiText-2 shows that random inputs underestimate NaN instability by up to 6x for full FP16, while confirming the robustness of the hybrid approach (0.0 percent NaN, cosine similarity >= 0.9998). These results provide a detailed characterization of performance and accuracy trade-offs across GPU architectures and offer practical guidance for deploying transformer models in latency-critical environments.
### Title:
          FlowIt: Global Matching for Optical Flow with Confidence-Guided Refinement
 - **Authors:** Sadra Safadoust, Fabio Tosi, Matteo Poggi, Fatma Güney
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present FlowIt, a novel architecture for optical flow estimation designed to robustly handle large pixel displacements. At its core, FlowIt leverages a hierarchical transformer architecture that captures extensive global context, enabling the model to effectively model long-range correspondences. To overcome the limitations of localized matching, we formulate the flow initialization as an optimal transport problem. This formulation yields a highly robust initial flow field, alongside explicitly derived occlusion and confidence maps. These cues are then seamlessly integrated into a guided refinement stage, where the network actively propagates reliable motion estimates from high-confidence regions into ambiguous, low-confidence areas. Extensive experiments across the Sintel, KITTI, Spring, and LayeredFlow datasets validate the efficacy of our approach. FlowIt achieves state-of-the-art results on the competitive Sintel and KITTI benchmarks, while simultaneously establishing new state-of-the-art cross-dataset zero-shot generalization performance on Sintel, Spring, and LayeredFlow.
### Title:
          On-the-fly Repulsion in the Contextual Space for Rich Diversity in Diffusion Transformers
 - **Authors:** Omer Dahary, Benaya Koren, Daniel Garibi, Daniel Cohen-Or
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Graphics (cs.GR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern Text-to-Image (T2I) diffusion models have achieved remarkable semantic alignment, yet they often suffer from a significant lack of variety, converging on a narrow set of visual solutions for any given prompt. This typicality bias presents a challenge for creative applications that require a wide range of generative outcomes. We identify a fundamental trade-off in current approaches to diversity: modifying model inputs requires costly optimization to incorporate feedback from the generative path. In contrast, acting on spatially-committed intermediate latents tends to disrupt the forming visual structure, leading to artifacts. In this work, we propose to apply repulsion in the Contextual Space as a novel framework for achieving rich diversity in Diffusion Transformers. By intervening in the multimodal attention channels, we apply on-the-fly repulsion during the transformer's forward pass, injecting the intervention between blocks where text conditioning is enriched with emergent image structure. This allows for redirecting the guidance trajectory after it is structurally informed but before the composition is fixed. Our results demonstrate that repulsion in the Contextual Space produces significantly richer diversity without sacrificing visual fidelity or semantic adherence. Furthermore, our method is uniquely efficient, imposing a small computational overhead while remaining effective even in modern "Turbo" and distilled models where traditional trajectory-based interventions typically fail.
## Keyword: autonomous driving
### Title:
          Efficient and Cost-effective Vehicle Recruitment for HD Map Crowdsourcing
 - **Authors:** Wentao Ye, Yuan Luo, Bo Liu, Jianwei Huang
 - **Subjects:** Subjects:
Computer Science and Game Theory (cs.GT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The high-definition (HD) map is a cornerstone of autonomous driving. The crowdsourcing paradigm is a cost-effective way to keep an HD map up-to-date. Current HD map crowdsourcing mechanisms aim to enhance HD map freshness within recruitment budgets. However, many overlook unique and critical traits of crowdsourcing vehicles, such as random arrival and heterogeneity, leading to either compromised map freshness or excessive recruitment costs. Furthermore, these characteristics complicate the characterization of the feasible space of the optimal recruitment policy, necessitating a method to compute it efficiently in dynamic transportation this http URL overcome these challenges, we propose an efficient and cost-effective vehicle recruitment (ENTER) mechanism. Specifically, the ENTER mechanism has a threshold structure and balances freshness with recruitment costs while accounting for the vehicles' random arrival and heterogeneity. It also integrates the bound-based relative value iteration (RVI) algorithm, which utilizes the threshold-type structure and upper bounds of thresholds to reduce the feasible space and expedite convergence. Numerical results show that the proposed ENTER mechanism increases the HD map company's payoff by 23.40% and 43.91% compared to state-of-the-art mechanisms that do not account for vehicle heterogeneity and random arrivals, respectively. Furthermore, the bound-based RVI algorithm in the ENTER mechanism reduces computation time by an average of 18.91% compared to the leading RVI-based algorithm.
### Title:
          Recruiting Heterogeneous Crowdsource Vehicles for Updating a High-definition Map
 - **Authors:** Wentao Ye, Yuan Luo, Bo Liu, Jianwei Huang
 - **Subjects:** Subjects:
Computer Science and Game Theory (cs.GT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The high-definition map is a cornerstone of autonomous driving. Unlike constructing a costly fleet of mapping vehicles, the crowdsourcing paradigm is a cost-effective way to keep an HD map up to date. Achieving practical success for crowdsourcing-based HD maps is contingent on addressing two critical issues: freshness and recruitment costs. Given that crowdsource vehicles are often heterogeneous in terms of operational costs and sensing capabilities, it is practical to recruit heterogeneous crowdsource vehicles to achieve the tradeoff between freshness and recruitment costs. However, existing works neglect this aspect. To solve it, we formulate this problem as a Markov decision process. We demonstrate that the optimal policy is threshold-type age-dependent. Additionally, our findings reveal some counter-intuitive insights. In some cases, the company should initiate vehicle recruitment earlier when vehicles arrive more frequently, or have higher operational costs or sensing capabilities.} Besides, we propose an efficient algorithm, called the bound-based relative value iteration (BRVI) algorithm, to overcome the technical challenge that finding an optimal policy is time-consuming. Numerical simulations show that (i) the optimal policy reduces the average cost by $19.04\%$ compared to the state-of-the-art mechanism}, and (ii) the proposed algorithm can reduce the convergence time by $13.66\%$ on average compared to the existing algorithm.
### Title:
          RailVQA: A Benchmark and Framework for Efficient Interpretable Visual Cognition in Automatic Train Operation
 - **Authors:** Sen Zhang, Runmei Li, Zhichao Zheng, Yuhe Zhang, Jiani Li, Kailun Zhang, Tao Zhang, Wenjun Wu, Qunbo Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic Train Operation (ATO) relies on low-latency, reliable cab-view visual perception and decision-oriented inference to ensure safe operation in complex and dynamic railway environments. However, existing approaches focus primarily on basic perception and often generalize poorly to rare yet safety-critical corner cases. They also lack the high-level reasoning and planning capabilities required for operational decision-making. Although recent Large Multi-modal Models (LMMs) show strong generalization and cognitive capabilities, their use in safety-critical ATO is hindered by high computational cost and hallucination risk. Meanwhile, reliable domain-specific benchmarks for systematically evaluating cognitive capabilities are still lacking. To address these gaps, we introduce RailVQA-bench, the first VQA benchmark for cab-view visual cognition in ATO, comprising 20,000 single-frame and 1,168 video based QA pairs to evaluate cognitive generalization and interpretability in both static and dynamic scenarios. Furthermore, we propose RailVQA-CoM, a collaborative large-small model framework that combines small-model efficiency with large-model cognition via a transparent three-module architecture and adaptive temporal sampling, improving perceptual generalization and enabling efficient reasoning and planning. Experiments demonstrate that the proposed approach substantially improves performance, enhances interpretability, reduces inference latency, and strengthens cross-domain generalization, while enabling plug-and-play deployment in autonomous driving systems. Code and datasets will be available at this https URL.
### Title:
          An Instance-Centric Panoptic Occupancy Prediction Benchmark for Autonomous Driving
 - **Authors:** Yi Feng, Junwu E, Zizhan Guo, Yu Ma, Hanli Wang, Rui Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Panoptic occupancy prediction aims to jointly infer voxel-wise semantics and instance identities within a unified 3D scene representation. Nevertheless, progress in this field remains constrained by the absence of high-quality 3D mesh resources, instance-level annotations, and physically consistent occupancy datasets. Existing benchmarks typically provide incomplete and low-resolution geometry without instance-level annotations, limiting the development of models capable of achieving precise geometric reconstruction, reliable occlusion reasoning, and holistic 3D understanding. To address these challenges, this paper presents an instance-centric benchmark for the 3D panoptic occupancy prediction task. Specifically, we introduce ADMesh, the first unified 3D mesh library tailored for autonomous driving, which integrates over 15K high-quality 3D models with diverse textures and rich semantic annotations. Building upon ADMesh, we further construct CarlaOcc, a large-scale, physically consistent panoptic occupancy dataset generated using the CARLA simulator. This dataset contains over 100K frames with fine-grained, instance-level occupancy ground truth at voxel resolutions as fine as 0.05 m. Furthermore, standardized evaluation metrics are introduced to quantify the quality of existing occupancy datasets. Finally, a systematic benchmark of representative models is established on the proposed dataset, which provides a unified platform for fair comparison and reproducible research in the field of 3D panoptic perception. Code and dataset are available at this https URL.
### Title:
          Robust Global-Local Behavior Arbitration via Continuous Command Fusion Under LiDAR Errors
 - **Authors:** Mohamed Elgouhary, Amr S. El-Wakeel
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modular autonomous driving systems must coordinate global progress objectives with local safety-driven reactions under imperfect sensing and strict real-time constraints. This paper presents a ROS2-native arbitration module that continuously fuses the outputs of two unchanged and interpretable controllers: a global reference-tracking controller based on Pure Pursuit and a reactive LiDAR-based Gap Follow controller. At each control step, both controllers propose Ackermann commands, and a PPO-trained policy predicts a continuous gate from a compact feature observation to produce a single fused drive command, augmented with practical safety checks. For comparison under identical ROS topic inputs and control rate, we implement a lightweight sampling-based predictive baseline. Robustness is evaluated using a ROS2 impairment protocol that injects LiDAR noise, delay, and dropout, and additionally sweeps forward-cone false short-range outliers. In a repeatable close-proximity passing scenario, we report safe success and failure rates together with per-step end-to-end controller runtime as sensing stress increases. The study is intended as a command-level robustness evaluation in a modular ROS2 setting, not as a replacement for planning-level interaction reasoning.
### Title:
          Uni-World VLA: Interleaved World Modeling and Planning for Autonomous Driving
 - **Authors:** Qiqi Liu, Huan Xu, Jingyu Li, Bin Sun, Zhihui Hao, Dangen She, Xiatian Zhu, Li Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving requires reasoning about how the environment evolves and planning actions accordingly. Existing world-model-based approaches typically predict future scenes first and plan afterwards, resulting in open-loop imagination that may drift from the actual decision process. In this paper, we present Uni-World VLA, a unified vision-language-action (VLA) model that tightly interleaves future frame prediction and trajectory planning. Instead of generating a full world rollout before planning, our model alternates between predicting future frames and ego actions step by step, allowing planning decisions to be continuously conditioned on the imagined future observations. This interleaved generation forms a closed-loop interaction between world modeling and control, enabling more adaptive decision-making in dynamic traffic scenarios. In addition, we incorporate monocular depth information into frames to provide stronger geometric cues for world modeling, improving long-horizon scene prediction. Experiments on the NAVSIM benchmark show that our approach achieves competitive closed-loop planning performance while producing high-fidelity future frame predictions. These results demonstrate that tightly coupling world prediction and planning is a promising direction for scalable VLA driving systems.
### Title:
          Class-Distribution Guided Active Learning for 3D Occupancy Prediction in Autonomous Driving
 - **Authors:** Wonjune Kim, In-Jae Lee, Sihwan Hwang, Sanmin Kim, Dongsuk Kum
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D occupancy prediction provides dense spatial understanding critical for safe autonomous driving. However, this task suffers from a severe class imbalance due to its volumetric representation, where safety-critical objects (bicycles, traffic cones, pedestrians) occupy minimal voxels compared to dominant backgrounds. Additionally, voxel-level annotation is costly, yet dedicating effort to dominant classes is inefficient. To address these challenges, we propose a class-distribution guided active learning framework for selecting training samples to annotate in autonomous driving datasets. Our approach combines three complementary criteria to select the training samples. Inter-sample diversity prioritizes samples whose predicted class distributions differ from those of the labeled set, intra-set diversity prevents redundant sampling within each acquisition cycle, and frequency-weighted uncertainty emphasizes rare classes by reweighting voxel-level entropy with inverse per-sample class proportions. We ensure evaluation validity by using a geographically disjoint train/validation split of Occ3D-nuScenes, which reduces train-validation overlap and mitigates potential map memorization. With only 42.4% labeled data, our framework reaches 26.62 mIoU, comparable to full supervision and outperforming active learning baselines at the same budget. We further validate generality on SemanticKITTI using a different architecture, demonstrating consistent effectiveness across datasets.
### Title:
          HMPDM: A Diffusion Model for Driving Video Prediction with Historical Motion Priors
 - **Authors:** Ke Li, Tianjia Yang, Kaidi Liang, Xianbiao Hu, Ruwen Qin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video prediction is a useful function for autonomous driving, enabling intelligent vehicles to reliably anticipate how driving scenes will evolve and thereby supporting reasoning and safer planning. However, existing models are constrained by multi-stage training pipelines and remain insufficient in modeling the diverse motion patterns in real driving scenes, leading to degraded temporal consistency and visual quality. To address these challenges, this paper introduces the historical motion priors-informed diffusion model (HMPDM), a video prediction model that leverages historical motion priors to enhance motion understanding and temporal coherence. The proposed deep learning system introduces three key designs: (i) a Temporal-aware Latent Conditioning (TaLC) module for implicit historical motion injection; (ii) a Motion-aware Pyramid Encoder (MaPE) for multi-scale motion representation; (iii) a Self-Conditioning (SC) strategy for stable iterative denoising. Extensive experiments on the Cityscapes and KITTI benchmarks demonstrate that HMPDM outperforms state-of-the-art video prediction methods with efficiency, achieving a 28.2% improvement in FVD on Cityscapes under the same monocular RGB input configuration setting. The implementation codes are publicly available at this https URL.
### Title:
          Annotation-Free Detection of Drivable Areas and Curbs Leveraging LiDAR Point Cloud Maps
 - **Authors:** Fulong Ma, Daojie Peng, Jun Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Drivable areas and curbs are critical traffic elements for autonomous driving, forming essential components of the vehicle visual perception system and ensuring driving safety. Deep neural networks (DNNs) have significantly improved perception performance for drivable area and curb detection, but most DNN-based methods rely on large manually labeled datasets, which are costly, time-consuming, and expert-dependent, limiting their real-world application. Thus, we developed an automated training data generation module. Our previous work generated training labels using single-frame LiDAR and RGB data, suffering from occlusion and distant point cloud sparsity. In this paper, we propose a novel map-based automatic data labeler (MADL) module, combining LiDAR mapping/localization with curb detection to automatically generate training data for both tasks. MADL avoids occlusion and point cloud sparsity issues via LiDAR mapping, creating accurate large-scale datasets for DNN training. In addition, we construct a data review agent to filter the data generated by the MADL module, eliminating low-quality samples. Experiments on the KITTI, KITTI-CARLA and 3D-Curb datasets show that MADL achieves impressive performance compared to manual labeling, and outperforms traditional and state-of-the-art self-supervised methods in robustness and accuracy.
### Title:
          Benchmarking Multi-View BEV Object Detection with Mixed Pinhole and Fisheye Cameras
 - **Authors:** Xiangzhong Liu, Hao Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern autonomous driving systems increasingly rely on mixed camera configurations with pinhole and fisheye cameras for full view perception. However, Bird's-Eye View (BEV) 3D object detection models are predominantly designed for pinhole cameras, leading to performance degradation under fisheye distortion. To bridge this gap, we introduce a multi-view BEV detection benchmark with mixed cameras by converting KITTI-360 into nuScenes format. Our study encompasses three adaptations: rectification for zero-shot evaluation and fine-tuning of nuScenes-trained models, distortion-aware view transformation modules (VTMs) via the MEI camera model, and polar coordinate representations to better align with radial distortion. We systematically evaluate three representative BEV architectures, BEVFormer, BEVDet and PETR, across these strategies. We demonstrate that projection-free architectures are inherently more robust and effective against fisheye distortion than other VTMs. This work establishes the first real-data 3D detection benchmark with fisheye and pinhole images and provides systematic adaptation and practical guidelines for designing robust and cost-effective 3D perception systems. The code is available at this https URL.
### Title:
          UniDA3D: A Unified Domain-Adaptive Framework for Multi-View 3D Object Detection
 - **Authors:** Hongjing Wu, Cheng Chi, Jinlin Wu, Yanzhao Su, Zhen Lei, Wenqi Ren
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Camera-only 3D object detection is critical for autonomous driving, offering a cost-effective alternative to LiDAR based methods. In particular, multi-view 3D object detection has emerged as a promising direction due to its balanced trade-off between performance and cost. However, existing methods often suffer significant performance degradation under complex environmental conditions such as nighttime, fog, and rain, primarily due to their reliance on training data collected mostly in ideal conditions. To address this challenge, we propose UniDA3D, a unified domain-adaptive multi-view 3D object detector designed for robust perception under diverse adverse conditions. UniDA3D formulates nighttime, rainy, and foggy scenes as a unified multi target domain adaptation problem and leverages a novel query guided domain discrepancy mitigation (QDDM) module to align object features between source and target domains at both batch and global levels via query-centric adversarial and contrastive learning. Furthermore, we introduce a domain-adaptive teacher student training pipeline with an exponential-moving-average teacher and dynamically updated high-quality pseudo labels to enhance consistency learning and suppress background noise in unlabeled target domains. In contrast to prior approaches that require separate training for each condition, UniDA3D performs a single unified training process across multiple domains, enabling robust all-weather 3D perception. On a synthesized multi-view 3D benchmark constructed by generating nighttime, rainy, and foggy counterparts from nuScenes (nuScenes-Night, nuScenes-Rain, and nuScenes-Haze), UniDA3D consistently outperforms state of-the-art camera-only multi-view 3D detectors under extreme conditions, achieving substantial gains in mAP and NDS while maintaining real-time inference efficiency.
### Title:
          Energy-Aware Imitation Learning for Steering Prediction Using Events and Frames
 - **Authors:** Hu Cao, Jiong Liu, Xingzhuo Yan, Rui Song, Yan Xia, Walter Zimmer, Guang Chen, Alois Knoll
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In autonomous driving, relying solely on frame-based cameras can lead to inaccuracies caused by factors like long exposure times, high-speed motion, and challenging lighting conditions. To address these issues, we introduce a bio-inspired vision sensor known as the event camera. Unlike conventional cameras, event cameras capture sparse, asynchronous events that provide a complementary modality to mitigate these challenges. In this work, we propose an energy-aware imitation learning framework for steering prediction that leverages both events and frames. Specifically, we design an Energy-driven Cross-modality Fusion Module (ECFM) and an energy-aware decoder to produce reliable and safe predictions. Extensive experiments on two public real-world datasets, DDD20 and DRFuser, demonstrate that our method outperforms existing state-of-the-art (SOTA) approaches. The codes and trained models will be released upon acceptance.
### Title:
          To View Transform or Not to View Transform: NeRF-based Pre-training Perspective
 - **Authors:** Hyeonjun Jeong, Juyeb Shin, Dongsuk Kum
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural radiance fields (NeRFs) have emerged as a prominent pre-training paradigm for vision-centric autonomous driving, which enhances 3D geometry and appearance understanding in a fully self-supervised manner. To apply NeRF-based pretraining to 3D perception models, recent approaches have simply applied NeRFs to volumetric features obtained from view transformation. However, coupling NeRFs with view transformation inherits conflicting priors; view transformation imposes discrete and rigid representations, whereas radiance fields assume continuous and adaptive functions. When these opposing assumptions are forced into a single pipeline, the misalignment surfaces as blurry and ambiguous 3D representations that ultimately limit 3D scene understanding. Moreover, the NeRF network for pre-training is discarded during downstream tasks, resulting in inefficient utilization of enhanced 3D representations through NeRF. In this paper, we propose a novel NeRF-Resembled Point-based 3D detector that can learn continuous 3D representation and thus avoid the misaligned priors from view transformation. NeRP3D preserves the pre-trained NeRF network regardless of the tasks, inheriting the principle of continuous 3D representation learning and leading to greater potentials for both scene reconstruction and detection tasks. Experiments on nuScenes dataset demonstrate that our proposed approach significantly improves previous state-of-the-art methods, outperforming not only pretext scene reconstruction tasks but also downstream detection tasks.
### Title:
          $AutoDrive\text{-}P^3$: Unified Chain of Perception-Prediction-Planning Thought via Reinforcement Fine-Tuning
 - **Authors:** Yuqi Ye, Zijian Zhang, Junhong Lin, Shangkun Sun, Changhao Peng, Wei Gao
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models (VLMs) are increasingly being adopted for end-to-end autonomous driving systems due to their exceptional performance in handling long-tail scenarios. However, current VLM-based approaches suffer from two major limitations: 1) Some VLMs directly output planning results without chain-of-thought (CoT) reasoning, bypassing crucial perception and prediction stages which creates a significant domain gap and compromises decision-making capability; 2) Other VLMs can generate outputs for perception, prediction, and planning tasks but employ a fragmented decision-making approach where these modules operate separately, leading to a significant lack of synergy that undermines true planning performance. To address these limitations, we propose ${AutoDrive\text{-}P^3}$, a novel framework that seamlessly integrates $\textbf{P}$erception, $\textbf{P}$rediction, and $\textbf{P}$lanning through structured reasoning. We introduce the ${P^3\text{-}CoT}$ dataset to facilitate coherent reasoning and propose ${P^3\text{-}GRPO}$, a hierarchical reinforcement learning algorithm that provides progressive supervision across all three tasks. Specifically, ${AutoDrive\text{-}P^3}$ progressively generates CoT reasoning and answers for perception, prediction, and planning, where perception provides essential information for subsequent prediction and planning, while both perception and prediction collectively contribute to the final planning decisions, enabling safer and more interpretable autonomous driving. Additionally, to balance inference efficiency with performance, we introduce dual thinking modes: detailed thinking and fast thinking. Extensive experiments on both open-loop (nuScenes) and closed-loop (NAVSIMv1/v2) benchmarks demonstrate that our approach achieves state-of-the-art performance in planning tasks. Code is available at this https URL.
### Title:
          Ghost-FWL: A Large-Scale Full-Waveform LiDAR Dataset for Ghost Detection and Removal
 - **Authors:** Kazuma Ikeda, Ryosei Hara, Rokuto Nagata, Ozora Sako.Zihao Ding, Takahiro Kado, Ibuki Fujioka, Taro Beppu, Mariko Isogawa, Kentaro Yoshioka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR has become an essential sensing modality in autonomous driving, robotics, and smart-city applications. However, ghost points (or ghosts), which are false reflections caused by multi-path laser returns from glass and reflective surfaces, severely degrade 3D mapping and localization accuracy. Prior ghost removal relies on geometric consistency in dense point clouds, failing on mobile LiDAR's sparse, dynamic data. We address this by exploiting full-waveform LiDAR (FWL), which captures complete temporal intensity profiles rather than just peak distances, providing crucial cues for distinguishing ghosts from genuine reflections in mobile scenarios. As this is a new task, we present Ghost-FWL, the first and largest annotated mobile FWL dataset for ghost detection and removal. Ghost-FWL comprises 24K frames across 10 diverse scenes with 7.5 billion peak-level annotations, which is 100x larger than existing annotated FWL datasets. Benefiting from this large-scale dataset, we establish a FWL-based baseline model for ghost detection and propose FWL-MAE, a masked autoencoder for efficient self-supervised representation learning on FWL data. Experiments show that our baseline outperforms existing methods in ghost removal accuracy, and our ghost removal further enhances downstream tasks such as LiDAR-based SLAM (66% trajectory error reduction) and 3D object detection (50x false positive reduction). The dataset and code is publicly available and can be accessed via the project page: this https URL
### Title:
          TwinMixing: A Shuffle-Aware Feature Interaction Model for Multi-Task Segmentation
 - **Authors:** Minh-Khoi Do, Huy Che, Dinh-Duy Phan, Duc-Khai Lam, Duc-Lung Vu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate and efficient perception is essential for autonomous driving, where segmentation tasks such as drivable-area and lane segmentation provide critical cues for motion planning and control. However, achieving high segmentation accuracy while maintaining real-time performance on low-cost hardware remains a challenging problem. To address this issue, we introduce TwinMixing, a lightweight multi-task segmentation model designed explicitly for drivable-area and lane segmentation. The proposed network features a shared encoder and task-specific decoders, enabling both feature sharing and task specialization. Within the encoder, we propose an Efficient Pyramid Mixing (EPM) module that enhances multi-scale feature extraction through a combination of grouped convolutions, depthwise dilated convolutions and channel shuffle operations, effectively expanding the receptive field while minimizing computational cost. Each decoder adopts a Dual-Branch Upsampling (DBU) Block composed of a learnable transposed convolution-based Fine detailed branch and a parameter-free bilinear interpolation-based Coarse grained branch, achieving detailed yet spatially consistent feature reconstruction. Extensive experiments on the BDD100K dataset validate the effectiveness of TwinMixing across three configurations - tiny, base, and large. Among them, the base configuration achieves the best trade-off between accuracy and computational efficiency, reaching 92.0% mIoU for drivable-area segmentation and 32.3% IoU for lane segmentation with only 0.43M parameters and 3.95 GFLOPs. Moreover, TwinMixing consistently outperforms existing segmentation models on the same tasks, as illustrated in Fig. 1. Thanks to its compact and modular design, TwinMixing demonstrates strong potential for real-time deployment in autonomous driving and embedded perception systems. The source code: this https URL.
### Title:
          FL-PBM: Pre-Training Backdoor Mitigation for Federated Learning
 - **Authors:** Osama Wehbi, Sarhad Arisdakessian, Omar Abdel Wahab, Azzam Mourad, Hadi Otrok, Jamal Bentahar
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Cryptography and Security (cs.CR); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Backdoor attacks pose a significant threat to the integrity and reliability of Artificial Intelligence (AI) models, enabling adversaries to manipulate model behavior by injecting poisoned data with hidden triggers. These attacks can lead to severe consequences, especially in critical applications such as autonomous driving, healthcare, and finance. Detecting and mitigating backdoor attacks is crucial across the lifespan of model's phases, including pre-training, in-training, and post-training. In this paper, we propose Pre-Training Backdoor Mitigation for Federated Learning (FL-PBM), a novel defense mechanism that proactively filters poisoned data on the client side before model training in a federated learning (FL) environment. The approach consists of three stages: (1) inserting a benign trigger into the data to establish a controlled baseline, (2) applying Principal Component Analysis (PCA) to extract discriminative features and assess the separability of the data, (3) performing Gaussian Mixture Model (GMM) clustering to identify potentially malicious data samples based on their distribution in the PCA-transformed space, and (4) applying a targeted blurring technique to disrupt potential backdoor triggers. Together, these steps ensure that suspicious data is detected early and sanitized effectively, thereby minimizing the influence of backdoor triggers on the global model. Experimental evaluations on image-based datasets demonstrate that FL-PBM reduces attack success rates by up to 95% compared to baseline federated learning (FedAvg) and by 30 to 80% relative to state-of-the-art defenses (RDFL and LPSF). At the same time, it maintains over 90% clean model accuracy in most experiments, achieving better mitigation without degrading model performance.
