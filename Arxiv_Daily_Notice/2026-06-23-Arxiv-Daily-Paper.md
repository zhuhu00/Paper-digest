# Showing new listings for Tuesday, 23 June 2026
## Keyword: SLAM
### Title:
          UNSEEN: Uncertainty-aware Navigation via Sparse Estimation in Unknown Environments
 - **Authors:** Tommaso Faraci, Marco Camurri, Daniele Fontanelli, Luigi Palopoli
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual navigation in unknown environments remains a core challenge in mobile robotics, especially for resource-constrained platforms. Most existing approaches rely on loosely coupled modular pipelines and strong assumptions on perception quality or environmental structure, often resorting to multi-modal sensor suites that increase system complexity and deployment cost. Vision-only navigation offers a lightweight alternative, but its performance degrades severely under motion blur, low texture, and illumination changes, largely because they neglect the tight coupling between commanded motion and perception. While perception-aware methods partially address this issue, they typically optimize individual modules and fail to propagate uncertainty consistently across the navigation stack. In this paper, we present UNSEEN, a unified uncertainty- and perception-aware navigation framework that explicitly couples localization, mapping, and planning using only a front-mounted camera. UNSEEN estimates sparse maps and robot poses with associated uncertainties at 6Hz, and leverages them to plan trajectories that jointly optimize task progress and estimation accuracy in receding-horizon. Simulations and extensive real-world experiments in unknown environments demonstrate the robustness of the proposed approach, with UNSEEN-SLAM reducing absolute translational error by 9.8% and UNSEEN-Plan improving estimation accuracy by up to 45% compared to state-of-the-art methods, while achieving a 100% task success rate.
### Title:
          Ultra-Fusion: A Resilient Tightly-Coupled Multi-Sensor Fusion SLAM Framework under Sensor Degradation and Spatiotemporal Perturbation for Intelligent Transportation Systems
 - **Authors:** Yihong Tian, Junjie Zhang, Liuyang Li, Deteng Zhang, Yunfei Zuo, Jie Yin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable localization is essential for intelligent transportation systems (ITS), including autonomous vehicles, quadruped last-mile carriers, and infrastructure-inspection unmanned aerial vehicles (UAVs). Although tightly-coupled multi-sensor fusion improves accuracy in favorable conditions, deployed systems remain vulnerable to sensor degradation -- poor illumination, LiDAR degeneracy, wheel slippage, and GNSS outage -- and to spatiotemporal calibration errors. These failures are common in urban canyons, tunnels, and high-speed corridors, where localization drift can degrade route tracking, tunnel passage continuity, and local map alignment. This paper presents Ultra-Fusion, a tightly-coupled multi-sensor localization framework based on a unified sliding-window estimator. Asynchronous measurements are timestamp-ordered and converted into optional factors within one optimization window, supporting WIO, VIO, LIO, and LVIO with optional wheel and GNSS augmentation. Observability-aware initialization selects the bootstrap mode, factor-wise reliability scheduling gates degraded measurements, and online LiDAR--IMU spatiotemporal calibration refines temporal offsets and rotational extrinsics during operation. We extend the M3DGR benchmark with simulation trajectories and evaluate more than 60 open-source SLAM systems on M3DGR, M2DGR-Plus, KAIST, GrandTour, and MARS-LVIG. The results show competitive accuracy across wheeled, legged, and aerial platforms under long-duration and high-speed operation, degradation, and calibration perturbation, improving localization availability for road-level autonomy, campus and warehouse mobility, and low-altitude aerial inspection. To benefit the industrial and academic community, we will release source code and datasets upon paper acceptance.
### Title:
          Spectral GS-SLAM: Observability-Aware, Degeneracy-Robust Tracking for Real-Time 3D Gaussian Splatting SLAM
 - **Authors:** Edward Beng Wai Tan, Siew-Kei Lam, Dongshuo Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent 3DGS-SLAM systems enable real-time operation by leveraging conventional feature matching or ICP-based tracking, thereby avoiding the heavy dense photometric optimization used in earlier approaches. However, feature matching remains prone to failure in textureless environments, while ICP-based tracking struggles in structureless or geometrically degenerate scenes due to ill-conditioned optimization. To address this issue, we propose Spectral GS-SLAM, an efficient yet robust tracking framework that integrates ICP with complementary feature-based constraints. Our method mitigates numerical instability by adaptively compensating under-constrained directions in degenerate scenarios, without interfering with the shared Gaussian representation used for mapping. We further introduce a Gaussian-aware planarity weighting mechanism that exploits the intrinsic covariance structure of 3D Gaussians to characterize scene geometry and guide information fusion. Extensive evaluations on challenging TUM RGB-D sequences demonstrate that Spectral GS-SLAM achieves real-time performance (40.14 FPS) while maintaining consistent tracking in both structureless and featureless environments. The proposed method preserves trajectory integrity in degenerate scenes while maintaining competitive performance in non-adverse conditions.
### Title:
          GeoFlow-SLAM++: A Robust Multi-Camera Visual-Inertial SLAM System with Relocalization
 - **Authors:** Wei Fen, Tingyang Xiao, Liu Liu, Xiaolin Zhou, Zhizhong Su
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular and RGB-D visual-inertial SLAM systems remain susceptible to limited field of view, sensor-specific failure modes, and unreliable cross-session relocalization. To address these issues, we present GeoFlow-SLAM++, a tightly coupled multi-camera visual-inertial SLAM system that extends GeoFlow-SLAM from a single RGB-D sensor to a calibrated multi-camera rig with a unified body-centric formulation. Within this multi-camera framework, GeoFlow-SLAM++ supports two interchangeable visual front-ends: a conventional ORB front-end and a neural network feature (NN-Feature) front-end built on SuperPoint and LightGlue. The system unifies tracking, mapping, and relocalization on a shared body state, and combines multi-camera reprojection constraints, IMU pre-integration, cross-view place recognition, and dual-stream optical flow/NN-Feature tracking for robust localization. As an optional extension, the system can further incorporate cross-view-consistent pseudo-depth predictions from RGB images as auxiliary geometric constraints. We evaluate GeoFlow-SLAM++ on EuRoC, OpenLORIS, TUM, Hilti, and a self-collected handheld multi-camera dataset. Results show that the NN-Feature front-end improves robustness in appearance-challenging scenarios, the multi-camera formulation achieves competitive localization accuracy on Hilti, and the unified cross-view relocalization design reaches LiDAR-comparable performance on the handheld dataset.
### Title:
          ACEsplat: Accelerated 3D Gaussian Scene Regression via RGB and Poses Only
 - **Authors:** Mingkai Liu, Haohua Que, Dikai Fan, Haojia Gao, Tianle Zhu, Handong Yao, Qian Zhang, Ruopeng Zhang, Xianliang Huang, Fei Qiao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Per-scene 3D Gaussian Splatting (3DGS) enables high-fidelity rendering, but practical robotic and AR scene capture pipelines often depend on external geometric initialization (e.g., SfM point clouds or depth estimates), which can be slow and brittle in on-site deployment. We present ACEsplat, a fast per-scene optimization framework that reconstructs 3D Gaussian representations from RGB images and camera poses only, without requiring external 3D priors (e.g., precomputed SfM models or supervised depth maps). ACEsplat uses a two-stage pipeline: (1) a self-supervised scene coordinate regression (SCR) module builds an internal geometry prior within 4--5 minutes; (2) SCR features and coordinate priors are fused by a lightweight Gaussian initialization head, followed by per-scene 3DGS optimization. On static-view rendering, ACEsplat achieves 29.11 dB PSNR on Wayspots with real-time SLAM poses and 33.20 dB on Cambridge Landmarks with SfM-refined poses. On RealEstate10K sparse-view novel view synthesis, it achieves competitive image fidelity under a challenging 2-view setting. ACEsplat completes scene-specific SCR mapping and 3DGS reconstruction within 15--25 minutes on a single GPU, making it a practical RGB+pose-only solution for rapid scene setup in robotics and mixed-reality applications.
### Title:
          Reference-Free Assessment of Physical Consistency in World Model-based Video Generation
 - **Authors:** Yun Oh, Sukmin Yun
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce reference-free measures for evaluating the physical consistency of generated videos, combining relative and absolute approaches to assess fidelity. Although tools like WorldGym or WorldEval enable robotic simulation via video generation, physical fidelity gaps often prevent these environments from accurately reproducing real-world task success rates of VLA models. Unlike existing evaluation methods, which require costly human voting (Elo) or unavailable ground-truth references (FVD), our approach utilizes DROID-SLAM and SEA-RAFT to quantify physical inconsistencies, motivated by WorldScore. Videos filtered using our relative consistency assessment show an improvement in task success rates of over 8%, effectively narrowing the simulation-to-reality gap. Furthermore, our absolute assessment enables spatio-temporal localization, providing visualization of when and where physical artifacts occur.
### Title:
          HERCULES: An Open-Source Simulation Framework for Heterogeneous Multi-Robot SLAM, Collaborative Perception, and Exploration
 - **Authors:** Sandilya Sai Garimella, Daniel Chase Butterfield, Sean Wilson, Lu Gan
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Multiagent Systems (cs.MA); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present HERCULES, an open-source simulator and data-collection pipeline for heterogeneous multi-robot autonomy. Built upon the Unreal Engine 5 (UE5)-based simulators AirSim and Cosys-AirSim, HERCULES resolves key architectural limitations of prior frameworks to enable concurrent unmanned aerial and ground vehicle (UAV-UGV) operation in large-scale, photorealistic, dynamic environments. It introduces a new waypoint-tracking UGV controller that mirrors existing UAV control interfaces, and provides a shared navigation stack for mapping, traversability analysis, planning, and control across heterogeneous platforms. Expanding inherited sensor suites, it adds physics-based long-wave infrared (LWIR) cameras and configurable night-vision modes for degraded visual environments. HERCULES provides lightweight APIs, ROS 2 wrappers, and rigorous time synchronization across sensors and platforms, and brings state-of-the-art game-engine capabilities into robotics simulation, integrating intelligent agents such as pedestrians, traffic, and wildlife with high-fidelity dynamic phenomena, including fire, flooding, and crop disease spread. HERCULES runs in two modes: passively, replaying offline-designed trajectories to generate reproducible multi-modal datasets, and actively, running an online planner in closed loop from live observations. Our experiments in heterogeneous multi-robot SLAM, collaborative perception, and exploration, using both HERCULES-generated data and active closed-loop execution, demonstrate its utility for advancing heterogeneous multi-robot autonomy. We publicly release our source code, experiment code, documentation, and datasets, including a heterogeneous multi-robot SLAM benchmark collected with two UAVs and two UGVs across kilometer-scale desert, forest, and city environments, at this https URL.
## Keyword: odometry
### Title:
          Online Learning of Robust Legged Odometry with Minimal Exteroceptive Supervision
 - **Authors:** Abhijeet M. Kulkarni, Yuze Du, Guoquan Huang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust locomotion and navigation for legged robots relies heavily on dependable odometry. Traditional multi-sensor fusion for such state estimation requires meticulous sensor calibration and platform-specific kinematic modeling, which complicates deployment. Industrially packaged exteroceptive sensors can provide accurate motion tracking but remain vulnerable to perceptually degraded conditions. We thus develop a plug-and-play, robust legged odometry system that eliminates the need for explicit exteroceptive-to-proprioceptive calibration or system kinematic modeling. Our approach leverages established exteroceptive motion pipelines as a continuous supervisory signal to train an online learned velocity neural network directly from proprioceptive data. An Invariant EKF (InEKF) is then used to fuse the learned proprioceptive or exteroceptive velocity (if any) and IMU data. When exteroception fails due to environmental degradation, the system seamlessly falls back to using the learned proprioceptive model, yielding a resilient legged odometry that readily adapts to new hardware. We demonstrate the platform-agnostic, easily deployable nature of our approach on different quadruped platforms, showcasing promising results in maintaining robust motion estimation across challenging scenarios.
### Title:
          ISOPoT: Imaging Sonar Odometry by Point Tracking
 - **Authors:** Jaša Samec, Vid Rijavec, Marko Peljhan, Aleksander Grm, Andrej Androjna, Danijel Skočaj, Matej Dobrevski
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable navigation in underwater environments remains a key challenge in marine robotics. In such scenarios, forward-looking sonars are a natural choice for long-range perception, offering wide coverage even in turbid, low-visibility conditions. However, sonar images are inherently noisy, contain artifacts, and lack rich semantic structure, causing standard computer vision methods for keypoint detection and matching to perform poorly. In this paper, we introduce ISOPoT, an imaging sonar odometry method based on modern point tracking techniques. We propose a sonar odometry pipeline that uses multi-frame point tracks as its primary correspondence representation, augmented with lightweight optimizations to improve robustness. We evaluated the proposed method on the Aracati 2017 dataset, as well as on an internal sonar dataset collected in real-world underwater environments. Our results show that ISOPoT outperforms previous state-of-the-art methods consistently in both sonar-only scenarios and in multi-sensor settings.
## Keyword: livox
### Title:
          A Vendor-Agnostic LiDAR Data Conversion System with Multi-Signal Detection and Multi-Format Output
 - **Authors:** Param Patel, Jay Dave, Pratyush Chakraborty
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR (Light Detection and Ranging) sensors capture the surrounding environment as dense 3D point clouds by measuring the time-of-flight of emitted laser pulses, making them foundational across autonomous vehicles, robotics, and large-scale mapping. PCAP (Packet Capture) files from these sensors are the starting point of most 3D perception pipelines, yet internal packet structures, UDP (User Datagram Protocol) port conventions and encoding schemes differ enough across manufacturers that no single tool reads them all. Ouster, Velodyne, Hesai, and Livox each require their own SDK (Software Development Kit), their own environment setup, and their own conversion workflow. Supporting all four means maintaining four disconnected pipelines with no shared infrastructure. The pipeline described here takes a raw PCAP as input and handles vendor identification automatically, scoring six independent file characteristics through a weighted multi-signal approach to determine the source sensor. C++ SDKs handle Ouster and Velodyne, while Hesai and Livox rely on Python-based dpkt parsing where no open source SDK exists. From there, a single command writes output to any of five industry-standard formats. We tested on real outdoor captures. Ouster peaks at 2.08M points per second, Velodyne at 1.47M, both running through native C++ packet decoding. Hesai and Livox land at 110K and 150K respectively, where Python-layer parsing introduces overhead that compounds under sustained load. The 8-10x gap held consistently across runs. Tested on a consumer-grade i3 with 8GB RAM, no vendor configuration required
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          A UAV-Based Multi-Modal Vision System for Automated Sideslope Deformation Monitoring and Hazard Detection
 - **Authors:** Jingfeng Zhang, Yi Li, Xianchong Liang, Huan Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Slope hazards constitute a major safety threat to expressway infrastructure, and their evolution is typically manifested as slow surface deformation. Conventional manual inspection suffers from low efficiency and inadequate operational safety, especially on severely deteriorated slopes. Accordingly, there is an urgent need for an automated, high-precision solution capable of large-area slope observation and analysis. This study aims to develop a highly automated workflow for slope hazard detection using Unmanned Aerial Vehicle (UAV)-borne Light Detection and Ranging (LiDAR). The proposed workflow consists of a shared data-acquisition and ground-surface extraction stage, a single-observation hazard-screening branch based on RandLA-Net, and a multi-epoch deformation-monitoring branch based on grid-wise elevation differencing. To validate the effectiveness of the proposed system, we conducted multiple UAV-borne LiDAR data-acquisition flights in real expressway slope environments. The results show that the workflow can extract usable ground-surface point clouds under vegetation cover, identify potential hazard zones from single-observation point clouds, and quantify centimeter-level elevation changes using multi-epoch grid differencing. This study establishes an end-to-end UAV-borne LiDAR-based workflow for slope inspection and demonstrates its feasibility through controlled experiments, field tests, and simulation-based validation, thereby providing an implementable solution for automated slope-hazard monitoring and intelligent early warning.
### Title:
          ARGUSTRACK: A Multi-View Annotation System for Multi-Object Tracking
 - **Authors:** Hao Vo, Duc Nguyen, Ngan Le
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-Camera Multi-Target (MCMT) tracking has emerged as a critical capability for applications ranging from autonomous driving to animal behavior monitoring. While recent advances have yielded sophisticated tracking algorithms, the availability of annotated multi-view data remains a significant bottleneck. Existing annotation tools predominantly support single-camera workflows or rely on LiDAR sensors, making cross-view labeling tedious and impractical for camera-only setups. We present ARGUS-TRACK, a multi-camera annotation system that addresses these limitations by enabling annotators to work directly on a bird's-eye-view (BEV) plane. Given calibrated camera parameters, a single ground-plane annotation is automatically projected into 2D bounding boxes across all relevant views, inherently ensuring identity consistency without manual cross-view alignment. To further accelerate the labeling process, ARGUSTRACK incorporates two complementary mechanisms: a Temporal Aware module that propagates annotations from preceding frames to initialize new ones, requiring only minor positional adjustments; and a Multi-camera Semi-annotation module that leverages off-the-shelf 2D detectors combined with foot-point estimation to automatically generate candidate BEV positions for annotator verification. We evaluate ARGUSTRACK through a pilot study on multi-camera broiler tracking and demonstrate that it substantially reduces annotation time compared to conventional single-camera labeling workflows.
### Title:
          Mirage: a Clean-Label Backdoor against LiDAR 3D Object Detection
 - **Authors:** Ziba Parsons, Ang Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep neural network-based LiDAR 3D object detection serves as a critical perception component in safety-critical autonomous systems. However, recent studies have revealed its vulnerability to backdoor attacks. Existing attacks typically require white-box access or label modification and focus on geometric attacks such as object disappearance or bounding-box manipulation. In this paper, we present Mirage, a black-box and clean-label backdoor attack against deep neural network-based LiDAR 3DOD. Mirage injects a small number of label-consistent poisoning samples into the training set, causing the model to learn a malicious association between a trigger pattern and an attacker-chosen target class while preserving normal training semantics. As a result, the compromised model behaves normally on benign inputs yet systematically misclassifies triggered objects as the target class during deployment. We evaluate Mirage on multiple state-of-the-art LiDAR 3DOD models and benchmark datasets. Experimental results show that Mirage achieves a 73% misclassification success rate with a poisoning rate of only 0.5%, while maintaining detection performance close to that of benign models.
### Title:
          Ultra-Fusion: A Resilient Tightly-Coupled Multi-Sensor Fusion SLAM Framework under Sensor Degradation and Spatiotemporal Perturbation for Intelligent Transportation Systems
 - **Authors:** Yihong Tian, Junjie Zhang, Liuyang Li, Deteng Zhang, Yunfei Zuo, Jie Yin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable localization is essential for intelligent transportation systems (ITS), including autonomous vehicles, quadruped last-mile carriers, and infrastructure-inspection unmanned aerial vehicles (UAVs). Although tightly-coupled multi-sensor fusion improves accuracy in favorable conditions, deployed systems remain vulnerable to sensor degradation -- poor illumination, LiDAR degeneracy, wheel slippage, and GNSS outage -- and to spatiotemporal calibration errors. These failures are common in urban canyons, tunnels, and high-speed corridors, where localization drift can degrade route tracking, tunnel passage continuity, and local map alignment. This paper presents Ultra-Fusion, a tightly-coupled multi-sensor localization framework based on a unified sliding-window estimator. Asynchronous measurements are timestamp-ordered and converted into optional factors within one optimization window, supporting WIO, VIO, LIO, and LVIO with optional wheel and GNSS augmentation. Observability-aware initialization selects the bootstrap mode, factor-wise reliability scheduling gates degraded measurements, and online LiDAR--IMU spatiotemporal calibration refines temporal offsets and rotational extrinsics during operation. We extend the M3DGR benchmark with simulation trajectories and evaluate more than 60 open-source SLAM systems on M3DGR, M2DGR-Plus, KAIST, GrandTour, and MARS-LVIG. The results show competitive accuracy across wheeled, legged, and aerial platforms under long-duration and high-speed operation, degradation, and calibration perturbation, improving localization availability for road-level autonomy, campus and warehouse mobility, and low-altitude aerial inspection. To benefit the industrial and academic community, we will release source code and datasets upon paper acceptance.
### Title:
          LOGOS: LiDAR-Only Gaussian Elevation Splatting for Unified Tiny Obstacle Segmentation
 - **Authors:** Nan Ming, Yeqiang Qian, Chunxiang Wang, Ming Yang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust obstacle segmentation is essential for the safety of intelligent robots, where LiDAR-based perception systems play a fundamental role in the robot-environment interaction. While extensive LiDAR-based approaches have demonstrated high performance on common obstacles in urban scenarios, their results on tiny obstacles such as curbs, gravel, and potholes remain unsatisfactory due to the significant similarity between tiny obstacles and inherent road undulations. Moreover, their segmentation accuracy even deteriorates sharply when the LiDAR scans suffer from degradation in challenging off-road scenes. To overcome these bottlenecks, we propose LOGOS, a LiDAR-only unified tiny obstacle segmentation system, which models the road surface as a continuous mixture of 2D Gaussian primitives and distinguishes tiny obstacles via high-presicion elevation estimation. Unlike existing Gaussian splatting methods that rely on iterative RGB training, LOGOS is a backpropagation-free LiDAR-only approach. It directly estimates Gaussian parameters via a freespace-aware initialization by incrementally pruning non-road primitives using smoothness constraints. Subsequently, pointwise signed distances are computed via a novel normal-aware elevation splatting function, ensuring robustness to both flat and sloped terrains. We evaluate LOGOS on a highly heterogeneous benchmark of point cloud frames collected from urban mobility scenarios and mining haulage off-road environments. These data are practically acquired using different LiDAR sensors and exhibit large variations in point density, terrain roughness, and obstacle types. Experiments on the road and off-road scenes demonstrate that LOGOS significantly outperforms other state-of-the-art methods, particularly in degraded point cloud regions and challenging off-road scenarios, while maintaining real-time efficiency.
### Title:
          GeoFlow-SLAM++: A Robust Multi-Camera Visual-Inertial SLAM System with Relocalization
 - **Authors:** Wei Fen, Tingyang Xiao, Liu Liu, Xiaolin Zhou, Zhizhong Su
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular and RGB-D visual-inertial SLAM systems remain susceptible to limited field of view, sensor-specific failure modes, and unreliable cross-session relocalization. To address these issues, we present GeoFlow-SLAM++, a tightly coupled multi-camera visual-inertial SLAM system that extends GeoFlow-SLAM from a single RGB-D sensor to a calibrated multi-camera rig with a unified body-centric formulation. Within this multi-camera framework, GeoFlow-SLAM++ supports two interchangeable visual front-ends: a conventional ORB front-end and a neural network feature (NN-Feature) front-end built on SuperPoint and LightGlue. The system unifies tracking, mapping, and relocalization on a shared body state, and combines multi-camera reprojection constraints, IMU pre-integration, cross-view place recognition, and dual-stream optical flow/NN-Feature tracking for robust localization. As an optional extension, the system can further incorporate cross-view-consistent pseudo-depth predictions from RGB images as auxiliary geometric constraints. We evaluate GeoFlow-SLAM++ on EuRoC, OpenLORIS, TUM, Hilti, and a self-collected handheld multi-camera dataset. Results show that the NN-Feature front-end improves robustness in appearance-challenging scenarios, the multi-camera formulation achieves competitive localization accuracy on Hilti, and the unified cross-view relocalization design reaches LiDAR-comparable performance on the handheld dataset.
### Title:
          A Vendor-Agnostic LiDAR Data Conversion System with Multi-Signal Detection and Multi-Format Output
 - **Authors:** Param Patel, Jay Dave, Pratyush Chakraborty
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR (Light Detection and Ranging) sensors capture the surrounding environment as dense 3D point clouds by measuring the time-of-flight of emitted laser pulses, making them foundational across autonomous vehicles, robotics, and large-scale mapping. PCAP (Packet Capture) files from these sensors are the starting point of most 3D perception pipelines, yet internal packet structures, UDP (User Datagram Protocol) port conventions and encoding schemes differ enough across manufacturers that no single tool reads them all. Ouster, Velodyne, Hesai, and Livox each require their own SDK (Software Development Kit), their own environment setup, and their own conversion workflow. Supporting all four means maintaining four disconnected pipelines with no shared infrastructure. The pipeline described here takes a raw PCAP as input and handles vendor identification automatically, scoring six independent file characteristics through a weighted multi-signal approach to determine the source sensor. C++ SDKs handle Ouster and Velodyne, while Hesai and Livox rely on Python-based dpkt parsing where no open source SDK exists. From there, a single command writes output to any of five industry-standard formats. We tested on real outdoor captures. Ouster peaks at 2.08M points per second, Velodyne at 1.47M, both running through native C++ packet decoding. Hesai and Livox land at 110K and 150K respectively, where Python-layer parsing introduces overhead that compounds under sustained load. The 8-10x gap held consistently across runs. Tested on a consumer-grade i3 with 8GB RAM, no vendor configuration required
### Title:
          DrivingVoxels: Compositional Sparse Voxel Rasterization for Dynamic Driving Scene Reconstruction
 - **Authors:** Tania Aguirre, Luis Roldão, Moussab Bennehar, Nathan Piasco, Dzmitry Tsishkou, Simone Rossi, Pietro Michiardi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing dynamic urban scenes remains challenging due to the unbounded nature of driving environments and the presence of multiple dynamic objects. Currently, potentially faster sparse voxel methods are mainly designed for static scenarios. On the other hand, dynamic approaches based on 3D Gaussian Splatting, despite their high-fidelity, are often time-consuming for driving scenarios and exhibit uncontrollable memory growth in large scenes. To address these limitations, we present DrivingVoxels, a compositional sparse voxel rendering framework for dynamic driving scenes. Our method jointly rasterizes sparse voxels from multiple independent octrees within a single rendering pass. Each rigid dynamic object is represented by an octree defined in its local coordinate frame, while a separate static octree models the stationary background. DrivingVoxels adopts a fully explicit, neural-free representation together with a LiDAR-guided structural initialization that efficiently captures scene geometry. We evaluate our framework on the PandaSet benchmark, demonstrating that DrivingVoxels performs on par on perceptual metrics and better on structural metrics for NVS and reconstruction while requiring shorter training times than previous 3DGS-base methods to an efficient optimization workflow anchored by a strong LiDAR prior.
### Title:
          UECP: Uncertainty-Enhanced Collaborative Perception
 - **Authors:** Kang Yang, Tianci Bu, Peng Wang, Deying Li, Wen Jie, Yongcai Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Collaborative perception serves as a pivotal solution to enhance the perception capability of individual agents in autonomous driving, where a core challenge lies in seeking reliable evidence to quantify and weight the contribution of each participating agent. Existing methods typically rely on a confidence map, which is co-trained with the detection head, but it is inherently correlated with the detection results and thus fails to provide unbiased physical evidence. Furthermore, how to deeply integrate evidence into the cooperative fusion process remains an open question. To address these issues, this paper first proposes an uncertainty map, a physically grounded and unambiguous metric for evaluating perception quality. This map is directly supervised by real-time sensor signals, i.e., LiDAR point density, ensuring decoupling from detection noise and thereby providing physical scenario-aware evidence for weighting agent contribution. Based on this map, we develop the Uncertainty-Enhanced Collaborative Perception (UECP) framework, centered on the Uncertainty-Aware Pyramid Fusion (UAPF) module. UAPF uses a coarse-to-fine strategy, with two key components: Uncertainty-Weighted Downsampling (UWD) for high-fidelity feature preservation, and Uncertainty-Guided Residual Fusion (UGRF) to reinforce ego features, suppressing noise and ensuring robust fusion. Extensive experiments on real-world datasets show UECP outperforms state-of-the-art methods in effectiveness and robustness by embedding the uncertainty map into fusion. Code will be publicly available.
### Title:
          ShotcreteDepth: A Bi-modal Dataset for Robust Robotic Depth Perception in Shotcrete Construction Environments
 - **Authors:** Jakub Gregorek, Lars Arnold Dethlefsen, Patrick Schmidt, Mads Essenbæk, Jonas Flink Bentzen, Lazaros Nalpantidis
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce ShotcreteDepth, a bi-modal dataset from the construction domain that captures both an active shotcreting process and general construction environments. The dataset comprises stereo RGB imagery and LiDAR point clouds acquired under harsh real-world conditions, including high turbidity and poor illumination. Such conditions adversely affect sensor measurements, leading to incomplete and noisy observations that pose significant challenges for perception systems in autonomous applications. Alongside the dataset, we release a lightweight annotation tool designed for time-efficient labeling of LiDAR point clouds. ShotcreteDepth consists of 11,252 temporally synchronized data samples, of which 220 are annotated for evaluation purposes. The dataset supports research in stereo matching, depth completion, and depth estimation under conditions that closely reflect the operational complexities found in industrial settings. Project repository: this https URL
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Zhinong AI: A Design-Science Study of an AI-Enabled Agricultural Decision-Support Platform for Smallholder Production
 - **Authors:** Zhaoyang Li, Jiaqi Liu, Ruijie Zhang
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Artificial intelligence is increasingly moving from single-purpose agricultural recognition tools toward integrated decision-support systems that connect information access, diagnosis, task execution and post-action feedback. This paper presents a design-science case study of the Zhinong AI Agricultural Decision Platform, a farmer-facing system that integrates agricultural information push services, natural-language question answering, image-based crop disease diagnosis, plot and farming-calendar management, workflow orchestration, a Hainan Free Trade Port agricultural service zone and an age-friendly care mode. Based on public project materials, policy context and prior research on smart agriculture, machine learning and design science, the paper constructs a layered system architecture and a closed-loop decision process summarized as sensing, analysis, planning, execution and feedback. It further proposes a function-pain-point mapping matrix, an evaluation indicator system and a governance framework covering data provenance, model risk, expert review, privacy and adoption risk. The study does not claim measured field performance because production logs, controlled user studies and expert-labeled local image datasets were not available at the time of writing. Instead, the contribution is a structured research framework for transforming an AI agricultural prototype into an empirically testable, accountable and localized decision-support infrastructure for smallholder production.
### Title:
          MAGNIFIED: RL Fine-tuning of Multimodal Large Language Models for Motion Planning
 - **Authors:** Letian Chen, Yiren Lu, Justin Fu, Yichen Xie, Runsheng Xu, Jyh-Jing Hwang, Ben Sapp, Drago Anguelov
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-modal Large Language Models (MLLMs) have demonstrated remarkable capabilities in semantic understanding and common sense reasoning, making them promising candidates for solving planning problems in autonomous driving. However, the next-token text prediction objectives traditionally used in pre-training and supervised fine-tuning (SFT) of MLLMs may fall short of fulfilling the planning objectives for autonomous vehicles. The next-token prediction objective merely encourages per-token imitation in text, often irrespective of multi-step consequences and the alignment with crucial planning considerations such as giving space to other road actors. To overcome these limitations, we propose a reinforcement learning fine-tuning (RLFT) approach, MAGNIFIED, that aligns the MLLM-based driving agent with planning objectives by learning from token-level rewards. By mapping a sequence of predicted tokens to corresponding vehicle trajectories and learning from planning rewards, MAGNIFIED optimizes for the true planning objectives rather than focusing solely on token prediction accuracy, enabling the model to refine its understanding of the planning task beyond simple imitation. We validate our approach on the Waymo Open Motion Dataset with a novel setup incorporating rasterized birds-eye views and tokenized trajectories as inputs and planning-oriented outputs. An initial SFT phase establishes a strong baseline in outputting plan trajectories as sequences of X-Y coordinates in text, while subsequent RL fine-tuning substantially enhances planning performance relative to the SFT baseline (demonstrating over a 10.5% reduction in overlap rate and a 38.9% reduction in off-road rate), underscoring the potential of RLFT on MLLMs to achieve vehicle planning that is better aligned with compliant, comfortable, and efficient driving.
### Title:
          Bridging Multi-Valued Heuristics and Dimensionality Reduction in Multi-Objective Search
 - **Authors:** Maya Wolff, Ariel Felner, Oren Salzman
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-objective shortest-path (MOSP) algorithms traditionally rely on single-valued heuristics (SVHs), which associate each state with a single admissible cost vector. While SVHs provide safe lower bounds, they fail to capture the trade-off structure of the Pareto frontier and often yield weak search guidance. Multi-valued heuristics (MVHs) address this limitation by mapping states to sets of cost estimates, enabling a richer approximation of possible trade-offs. Modern MOSP algorithms are highly dependent on dimensionality reduction (DR) techniques to efficiently perform dominance checks. However, integrating MVHs with DR introduces subtle correctness challenges. We show that naively combining DR with MVHs destroys the ordering invariants required for DR, leading to unsound and incomplete search. To address this issue, we develop the first theoretical frameworks for safely integrating MVHs with DR. First, we introduce $\text{NAMOA}^*{\text{dr}\text{-}\text{mvh}}$, a theoretical baseline that restores search correctness by enforcing heuristic consistency. Recognizing the practical limitations of this approach, we then introduce our primary contribution, $\text{L}\text{-}\text{NAMOA}^*{\text{dr}\text{-}\text{mvh}}$. This algorithm employs a "lazy," optimistic approach to DR, preserving exact correctness with only an admissible MVH by dynamically detecting and repairing local ordering violations. Across a range of benchmarks, $\text{L}\text{-}\text{NAMOA}^*{\text{dr}\text{-}\text{mvh}}$ matches or improves over state-of-the-art MOSP algorithms, and achieves speedups of over 10x in instances where the additional guidance provided by the MVH translates into stronger pruning.
### Title:
          BELLS-O: Evaluating the Operational Trade-offs of LLM Supervision Systems
 - **Authors:** Leonhard Waibl, Felix Michalak, Hadrien Mariaccia
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM supervision systems, namely input/output moderation filters and jailbreak detectors, are the primary safeguard against misuse in deployed AI applications, yet existing benchmarks are often vendor-biased, omit cost and latency, and rarely compare specialized guardrails against repurposed generalist LLMs. We present BELLS-O (Benchmark for the Evaluation of LLM Supervision Systems, Operational), the first independent operational benchmark of LLM supervision systems. BELLS-O evaluates 28 systems from 17 providers: every major specialized guardrail (e.g., LlamaGuard-4, ShieldGemma-2, Lakera Guard) and frontier generalists repurposed as supervisors (e.g., GPT-5.4, Claude Sonnet 4.6, Grok-4.1), jointly on detection rate, false-positive rate, latency, and monetary cost. We cover input/output moderation across 11 harm categories and jailbreak detection across 13 attack techniques, using in-house datasets built from handcrafted prompts, expert-curated samples, and quality-controlled synthetic generation. To suppress latent generator fingerprints in synthetic data, every generated sample is paraphrased. Mapping the Pareto frontier reveals use-case-dependent tradeoffs. On content moderation, specialized supervisors are operationally dominant: top systems match frontier LLMs on detection (~95% vs. 94%) at comparably low false-positive rates (<=2%), while running 5-10x faster and ~10x cheaper. On jailbreak detection, the tradeoff shifts: frontier LLMs achieve higher detection and lower false-positive rates but at 10-50x higher cost and 5-10x higher latency. We release the benchmark, framework, leaderboard, and datasets as the first vendor-neutral basis for selecting safeguards under real deployment constraints.
### Title:
          VQ4SNN: Vector Quantization for Memory-Efficient FPGA Spiking Neural Networks
 - **Authors:** Dimitrios Sekertzis, Giorgos Dimitrakopoulos
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE); Artificial Intelligence (cs.AI); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking Neural Networks (SNNs) offer an energy-efficient paradigm for edge AI, making them attractive for hardware acceleration. However, deploying dense SNNs on FPGAs is constrained by limited on-chip memory for synaptic weight storage. To address this bottleneck, we propose VQ4SNN, a hardware-aware architecture that reduces memory requirements through Vector Quantization (VQ)-based weight sharing. To the best of our knowledge, this is the first application of VQ to pipelined spatial-dataflow SNN accelerators on FPGAs. VQ4SNN replaces conventional weight storage with a two-level memory organization consisting of compact pointers and a shared codebook of quantized weight vectors. The proposed design integrates FPGA-aware memory mapping with analytical VQ parameter selection, enabling efficient deployment on such accelerators while preserving inference accuracy. The experimental results show a reduction of 52-61% in the total number of BRAMs compared to the state-of-the-art uncompressed FPGA SNNs without increasing overall logic utilization.
### Title:
          D2HDMap: Non-visible Driveline Map Prior for Online Vectorized HD Map Prediction
 - **Authors:** Seojun Shon, Chikao Tsuchiya, Dhaval Bhanderi, David Ilstrup, Hsinmin Cheng, Christopher Ostafew
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate, up-to-date representations of road structures are critical for the safe operation of autonomous vehicles. Existing systems rely either on costly, maintenance-heavy high-definition (HD) maps which compromise safety when outdated, or purely sensor-based online mapping which struggles with long-range reliability and occlusion. Systems incorporating map prior information into online mapping seek to overcome drawbacks of both approaches by combining them in some way. We propose 'Driveline To HD Map' (D2HDMap), an online mapping system that injects a lightweight, non-visible driveline prior to guide the estimation of visible road structures such as lane dividers, road boundaries and crosswalks. This prior incurs less effort to create and update compared to full HD map priors used in other approaches. We also show that training with such a prior can improve generalization at inference time when no prior is available. Ablation studies conducted on the nuScenes and Argoverse 2 dataset demonstrate that models trained using a driveline prior largely retain performance even when priors are not available. On a geographically disjoint split, D2HDMap achieves 44.8 mAP, surpassing recent state-of-the-art. Additionally, noise-aware training substantially increases robustness to realistic localization error.
### Title:
          UNSEEN: Uncertainty-aware Navigation via Sparse Estimation in Unknown Environments
 - **Authors:** Tommaso Faraci, Marco Camurri, Daniele Fontanelli, Luigi Palopoli
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual navigation in unknown environments remains a core challenge in mobile robotics, especially for resource-constrained platforms. Most existing approaches rely on loosely coupled modular pipelines and strong assumptions on perception quality or environmental structure, often resorting to multi-modal sensor suites that increase system complexity and deployment cost. Vision-only navigation offers a lightweight alternative, but its performance degrades severely under motion blur, low texture, and illumination changes, largely because they neglect the tight coupling between commanded motion and perception. While perception-aware methods partially address this issue, they typically optimize individual modules and fail to propagate uncertainty consistently across the navigation stack. In this paper, we present UNSEEN, a unified uncertainty- and perception-aware navigation framework that explicitly couples localization, mapping, and planning using only a front-mounted camera. UNSEEN estimates sparse maps and robot poses with associated uncertainties at 6Hz, and leverages them to plan trajectories that jointly optimize task progress and estimation accuracy in receding-horizon. Simulations and extensive real-world experiments in unknown environments demonstrate the robustness of the proposed approach, with UNSEEN-SLAM reducing absolute translational error by 9.8% and UNSEEN-Plan improving estimation accuracy by up to 45% compared to state-of-the-art methods, while achieving a 100% task success rate.
### Title:
          A3C3: AI Algorithm and Accelerator Co-design, Co-search, and Co-generation
 - **Authors:** Selin Yildirim, Yingbing Huang, Deming Chen
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a holistic methodology for artificial intelligence algorithm and accelerator co-design, co-search, and co-generation (A3C3), which jointly optimizes neural network architectures and their hardware implementations to address the inefficiencies of traditional top-down AI system design flows. Conventional AI deployment often treats model design and hardware mapping as separate stages: an algorithm is first developed for accuracy, and only afterward adapted to meet latency, throughput, energy, or resource constraints. This separation can lead to suboptimal systems, particularly as modern AI workloads become increasingly heterogeneous, memory-intensive, and platform-dependent. A3C3 instead parameterizes both algorithmic and accelerator design spaces and searches them jointly, enabling the automatic generation of model-accelerator pairs that better balance accuracy, latency, throughput, energy efficiency, and hardware utilization. This article is a book chapter of the Handbook of Embedded Machine Learning, edited by Sudeep Pasricha and Muhammad Shafique, Springer Nature.
### Title:
          Bridging Technical AI, Societal Impacts, and Workforce Competencies in AI Education
 - **Authors:** Narges Zare, Divya Ramesh, Cori Faklaris
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As AI becomes embedded across everyday life and work, educators must help students connect technical knowledge with societal consequences and workplace responsibilities. Yet AI education often remains fragmented, with technical concepts, ethics, human-centered design, and workforce preparation taught separately. This work-in-progress presents a curriculum mapping framework that links technical systems, societal harms, and workforce competencies, beginning with institutional courses and expanding through an external 335-course registry. Early findings from six courses suggest that technical coverage is often strong, societal harms are present but unevenly integrated, and workforce competencies are rarely explicitly assessed. These findings speak to AI literacy efforts by showing that literacy cannot stop at awareness of AI concepts or harms; it must also include competencies for responsible action in AI-enabled contexts.
### Title:
          From Inference to Prediction: How Machine Learning is Reconfiguring Science (1990-2025)
 - **Authors:** Malena Mendez Isla, Vincent Lariviere, Diego Kozlowski
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Machine learning (ML) has reshaped scientific practice across disciplines, yet its epistemic consequences remain poorly understood. This paper analyzes how its broad diffusion reconfigures the conditions under which scientific claims are produced and evaluated. Using a hierarchical taxonomy of 255 ML techniques and embedding-based semantic mapping, we analyze 4.9 million scientific publications from OpenAlex (1990-2025). We reconstruct the semantic space of ML research and show a core-periphery structure, with physical sciences forming the methodological core and health sciences representing the primary growth area. We identify distinct methodological profiles across domains: predictive techniques concentrate in computer sciences while inferential approaches remain distributed across applied fields, reflecting historically differentiated validation regimes. We observe the displacement of inference-oriented techniques by predictive architectures in domains that have traditionally prioritized interpretability-most notably health sciences and social sciences. This displacement unfolds in two qualitatively distinct waves. The first (2015-2021) was driven by deep learning architectures that reduced predictive error while introducing epistemic opacity. The second (post 2022) is organized around a small number of architectures delivered through external companies, introducing a further layer of opacity over data and processes that researchers cannot access or report. This transformation expands the analytical capacity of science, and also reorganizes the conditions under which scientific knowledge can be produced and evaluated.
### Title:
          MEDLAYXPLAIN: Benchmarking the Expert-Lay Gap in Medical Vision-Language Models
 - **Authors:** Han Jang, Junhyeok Lee, Songsoo Kim, Chae Young Lim, Hyeonjin Goh, Heeseong Eum, Kyu Sung Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medical Vision-Language Models (Med-VLMs) achieve strong expert-level performance, yet their ability to generate patient-accessible descriptions remains underexplored. With the 21st Century Cures Act now mandating immediate patient access to diagnostic imaging results, evaluating whether Med-VLMs can bridge this Expert-Lay Gap is both urgent and clinically consequential for patient education and shared decision-making. To this end, we introduce MedLayXPlain, the first large-scale multimodal benchmark and evaluation framework for Medical Lay Language Generation (MLLG). MedLayXPlain-122K provides 122,789 region-grounded samples across 8 imaging modalities from 12 publicly available source datasets, each comprising a medical image with paired expert and lay captions anchored in a three-level Unified Medical Language System (UMLS) ontology hierarchy spanning 7 semantic groups, 43 semantic types, and 2,411 medical concepts. Lay captions are constructed via Hierarchical Ontology-Verified Refinement (HOVER), a three-step pipeline combining patient-centric vocabulary mapping, LLM-based constrained rewriting, and cross-model visual verification to enforce semantic equivalence while preventing hallucination. We further introduce MedLayEval, a lightweight 3B evaluator distilled from a 27B verifier that scores expert-lay alignment across five clinically grounded attributes, addressing the poor correlation between standard NLG metrics and clinical judgment. Benchmarking 33 VLMs on MedLayXPlain-122K reveals a systematic Expert-Lay Gap: medical VLMs achieve strong expert captioning but suffer significant lay-register degradation, while general-purpose VLMs produce more accessible language yet lack clinical precision, confirming that neither current paradigm adequately serves patient-facing communication.
### Title:
          Real-time pedestrian attribute recognition with YOLOv8 and ResNet18
 - **Authors:** Houssam El Mir
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pedestrian attribute recognition (PAR) assigns semantic labels to detected pedestrians and is useful in surveillance, video retrieval, and human-centered graphics applications. This paper presents a two-stage framework in which YOLOv8n detects pedestrians and ResNet18-based models classify gender, estimate apparent age, and predict 61 binary attributes from each pedestrian crop. PETA and PA-100K are combined through semantic attribute mapping, producing a unified training corpus of more than 100,000 pedestrian images while retaining the PETA attribute space. On the reported test splits, the system obtains 99.89% gender classification accuracy, a 4.23-year apparent-age mean absolute error, and 89.96% multi-attribute accuracy with a 36.32% macro F1-score and 58.80% micro F1-score. Runtime measurements indicate 25-30 FPS on an NVIDIA RTX 5060 GPU. The results show that a lightweight detector-classifier pipeline can support real-time PAR, while low macro F1 indicates that rare attributes remain challenging.
### Title:
          Spectral GS-SLAM: Observability-Aware, Degeneracy-Robust Tracking for Real-Time 3D Gaussian Splatting SLAM
 - **Authors:** Edward Beng Wai Tan, Siew-Kei Lam, Dongshuo Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent 3DGS-SLAM systems enable real-time operation by leveraging conventional feature matching or ICP-based tracking, thereby avoiding the heavy dense photometric optimization used in earlier approaches. However, feature matching remains prone to failure in textureless environments, while ICP-based tracking struggles in structureless or geometrically degenerate scenes due to ill-conditioned optimization. To address this issue, we propose Spectral GS-SLAM, an efficient yet robust tracking framework that integrates ICP with complementary feature-based constraints. Our method mitigates numerical instability by adaptively compensating under-constrained directions in degenerate scenarios, without interfering with the shared Gaussian representation used for mapping. We further introduce a Gaussian-aware planarity weighting mechanism that exploits the intrinsic covariance structure of 3D Gaussians to characterize scene geometry and guide information fusion. Extensive evaluations on challenging TUM RGB-D sequences demonstrate that Spectral GS-SLAM achieves real-time performance (40.14 FPS) while maintaining consistent tracking in both structureless and featureless environments. The proposed method preserves trajectory integrity in degenerate scenes while maintaining competitive performance in non-adverse conditions.
### Title:
          Distinguishing indistinguishable attractors: Unsupervised anomaly detection with reservoir computers
 - **Authors:** Davide Prosperino, Haochun Ma, Christoph Räth
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Chaotic Dynamics (nlin.CD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Detecting when a nonlinear dynamical system departs from its normal regime is a recurring problem across the sciences, from cardiology to climate and energy systems. We show that a very simple Kolmogorov--Smirnov test on the output weights of a reservoir computer is highly sensitive to regime changes in nonlinear dynamical systems, including those invisible to both classical nonlinear measures and modern deep-learning detectors. The core idea of our algorithm is to treat the readout layer of a reservoir computer as a representation of the input dynamics. Since the input mapping and the reservoir itself are random and fixed, the trained output weights are the only object encoding the system at hand. We summarize this fingerprint by the empirical cumulative distribution function of the readout weights and compare it to a reference band built from the training data. This unsupervised, online detector distinguishes two visually indistinguishable butterfly-shaped attractors, resolves parameter drifts seven times smaller than the strongest deep-learning baseline, flags noise four orders of magnitude below the signal, and identifies ventricular flutter in a clinical ECG recording. More broadly, we aim to establish a perspective on reservoir computers in which the trained output weights are treated as a representation of the learned system in their own right, rather than merely as a means to forecasting.
### Title:
          Unsupervised Disentanglement Without Compromises : How Functional Orthogonality Enforces Identifiability
 - **Authors:** Mathieu Cyrille Simon, Pascal Frossard, Christophe De Vleeschouwer
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper explores unsupervised disentangled representation learning from a functional perspective. We define latent concepts as factors that influence observations through locally orthogonal directions, formalized as an orthogonality constraint on the Jacobian of the generative mapping. We prove that this condition yields identifiability of general nonlinear generative models, without requiring statistical independence or causal assumptions, provided the latent domain admits all combinations of factor values. Experiments with orthogonality-regularized normalizing flows empirically confirm the theory, demonstrate reliable recovery of ground-truth factors, and shed light on the success of VAEs. These findings challenge the prevailing impossibility claims for unsupervised disentanglement and provide a principled alternative foundation.
### Title:
          Per-Entity Bias Mapping for AI Visibility: Why Brand Mentions Require Entity-Specific Calibration
 - **Authors:** Zoltan Varga
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI-mediated answer systems increasingly determine how brands and organizations are represented to users. Existing approaches reduce visibility to mention rate or citation frequency. This paper argues that aggregate metrics are insufficient because entities exhibit systematically different AI visibility error profiles. We introduce Per-Entity Bias Mapping (PEBM): a ten-dimensional framework distinguishing raw from verified mentions. Three failure modes are identified: (1) underrepresented entities suffer invisibility due to weak knowledge graph presence; (2) large entities suffer the Brand Hallucination Paradox -- model familiarity creates stronger surfaces for plausible but incorrect completions; (3) CEE entities face a structural infrastructure gap across knowledge graphs, NER, and entity linking. A fourth dimension, Parametric-Retrieval Lag Asymmetry, describes divergence between retrieval-augmented and parametric memory update cycles. A full-scale empirical study (n=100 Hungarian B2B entities, 1,400 probe runs, 2,062 sources) finds Tier 1 brands produce 52.69% fabricated citations versus 37.87% for Tier 3 entities (+14.82 pp; p=1.67e-11), supporting the Brand Hallucination Paradox. Regulatory-framed queries elevate fabrication to 56.77% versus 37.59% baseline (+19.2 pp). We identify rejection-induced confabulation escalation: agentic quality filters function as hallucination accelerators in compliance contexts. We introduce ghost cartography as a unifying mechanism: entities in sparse latent regions produce confident output interpolated from neighboring dense regions, yielding a two-dimensional confabulation space (fabricated presence vs. frozen representation).
### Title:
          Efficient Domain Decomposition for the Helmholtz Equation on GPUs
 - **Authors:** Amit Rotem
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Helmholtz equation governs wave propagation in acoustics, electromagnetics, and seismology, but its indefinite nature makes it difficult to solve with iterative methods. Domain decomposition methods are a natural fit for massively parallel architectures, yet mapping efficient Helmholtz solvers onto modern GPUs remains a challenge. We address both with two key contributions: (1) a block-level domain decomposition scheme, in which each subdomain is assigned to a single thread block and all solves run concurrently in a single kernel launch, and (2) WaveHoltz as the subdomain solver. WaveHoltz is a fixed-point iteration that is uniquely well-suited to the GPU execution model due to its minimal memory footprint and no reduction operations. Together, these eliminate device-level synchronizations and replace global memory traffic with shared memory and register-level operations, keeping subdomain data largely resident in L1 and L2 cache. We explore two threading strategies: one degree of freedom per thread for small subdomains, and multiple degrees of freedom per thread for larger ones. Benchmarks of our CUDA based implementation on a NVIDIA A100 show that WaveHoltz achieves 2x-25x speedup over MINRES, with the advantage growing with subdomain size. Crucially, evaluating the subdomain solver in single rather than double precision yields an additional 2x-10x speedup--a benefit largely unattainable by MINRES due to loss of Krylov vector orthogonality under reduced precision.
### Title:
          Quantile Adaptive Temperature Scaling for Confidence Calibration
 - **Authors:** Omprakash Chakraborty, Leo Fillioux, Ismail Ben Ayed, Jose Dolz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep neural networks often produce poorly calibrated confidence estimates, overstating their certainty even when predictions are incorrect. Temperature Scaling remains the most widely used posthoc calibration method due to its simplicity and effectiveness, yet its global, uniform rescaling of logits fails to correct the highly heterogeneous structure of miscalibration observed across the confidence spectrum. In particular, the largest correctness confidence discrepancies arise in different quantile regions depending on the setting, low confidence predictions, where uncertainty matters most, tend to exhibit the largest correctness confidence discrepancies, which standard TS leaves largely unaddressed. We introduce Quantile Adaptive Temperature Scaling (QaTS), a simple and efficient post hoc calibration method that adapts the temperature as a function of a predictions empirical confidence quantile. By mapping confidences into the quantile space, QaTS normalizes the calibration problem, makes the structure of miscalibration explicit and enables a monotone temperature function that adapts across quantiles while leaving well calibrated high confidence predictions largely unchanged. preserving high confidence behavior. This quantile aware formulation aligns naturally with a reparameterized Expected Calibration Error (ECE) objective and yields a sample wise temperature that is robust across a variety of challenging scenarios, such as class imbalance and distributional shifts. Across a broad range of datasets, architectures, evaluation scenarios and diverse tasks, QaTS consistently, and substantially, outperforms state of the art post hoc calibration methods, delivering more reliable and trustworthy confidence estimates without modifying model predictions.
### Title:
          Row-Based Layout Synthesis for Analog Circuits Using Height-Quantized Primitives
 - **Authors:** Endalk Y. Gebru, Ramprasath S., Ramesh Harjani, Sachin S. Sapatnekar
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Restrictive design rules and strong layout-dependent effects have tightened the coupling between physical layout decisions and electrical performance in advanced process nodes, such as FinFET, making analog and mixed-signal (AMS) layout automation increasingly difficult. This paper presents a quantized row-height layout synthesis methodology for AMS circuits, a methodology that has previously been shown to reduce the simulation-to-silicon gap. The proposed flow optimizes a row height fabric from circuit requirements and layout constraints while mapping analog building blocks into quantized-height rows. Results on multiple testcases demonstrate that the proposed flow synthesizes layouts with similar postlayout performance relative to less-constrained custom baseline designs, with comparable performance metrics. Our quantized-height designs are shown to reduce the schematic-to-postlayout performance gap by up to 68.5% and result in lower area for most of our testcases, with a maximum area reduction of 24.1%.
### Title:
          AgentDSE: Reasoning-Augmented Architectural Design Space Exploration
 - **Authors:** Chenyu Wang, Jiahe Caroline Shi, David Kong, Duane S. Boning, Zishen Wan, Yilun Du, Vijay Janapa Reddi
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional architectural design space exploration (DSE) is highly inefficient, typically requiring tens of thousands of simulator evaluations across various optimization methods. This inefficiency arises because conventional methods treat the simulator as a black-box oracle. In contrast, human architects effectively guide exploration by reasoning through physical constraints, performance bottlenecks, data reuse, and workload structures. To bridge this gap, we introduce AgentDSE, a simulator-in-the-loop methodology driven by a general-purpose large language model (LLM) coding agent. AgentDSE automates this architectural-reasoning loop without requiring model fine-tuning, precomputed design databases, or domain-specific optimizer code. Across deep neural network (DNN) accelerator mapping, hardware/software co-design, and CPU cache-hierarchy optimization, AgentDSE achieves competitive or better design quality with up to two orders of magnitude fewer evaluations. AgentDSE also produces inspectable traces that surface architectural hypotheses, performance cliffs, implicit priors, and simulator artifacts, making every search decision traceable rather than buried in optimizer state.
### Title:
          CoRDE: Concept-Prior Routed Diffusion Experts for Structural Generalization in Robot Manipulation
 - **Authors:** Haidong Huang, Xixin Zhao, Yaohua Zhou, Jiayu Song, Jiayi Zhang, Jun Ma, Haiyue Zhu, Xiaocong Li
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models excel at capturing multi-modal action distributions in robot imitation learning. However, in multi-task and long-horizon scenarios, monolithic architectures lack structural generalization capabilities, suffering from gradient conflicts between distinct semantic sub-stages. While pure data-driven Mixture-of-Experts (MoE) methods introduce labor division, they frequently trigger routing collapse, and instantiating full-scale experts causes parameter explosion and high expansion costs. To address these issues, we propose Concept-prior Routed Diffusion Experts (CoRDE), a structure-guided variational distillation framework. CoRDE extracts semantic distributions from a frozen concept encoder to guide the variational posterior responsibility via a learnable soft mapping matrix. This mechanism introduces an entropy-controlled responsibility inference process that encourages confident routing under reliable semantic predictions while preserving the stochastic diffusion term for behavioral diversity. To overcome parameter inflation, CoRDE employs a parameter-efficient expert pool using Low-Rank Adaptation (LoRA) on a shared frozen backbone. Theoretical analysis shows that the mixture score discrepancy is bounded by responsibility-weighted local expert errors, supporting high-fidelity generation under low-rank expert adaptation. Empirical evaluations confirm that, compared to existing baselines, CoRDE systematically reduces routing collapse, forming robust, semantically aligned expert allocations while achieving superior action quality and incremental learning efficiency.
### Title:
          Modularized Reinforcement Learning on LLMs: From MDP Creation to Exploration and Learning
 - **Authors:** Zhao Yang, Yuxuan Jiang, Ting-Chih Chen, Lincen Yang, Annie Wong, Chao Gao, Jacob E. Kooi, Zhong Li, Jiayang Shi, Kevin Qiu, Qi Huang, Xinrui Zu, Shiping Yang, Hengyuan Zhang, Ngai Wong, Filip Ilievski, Shujian Yu, Aske Plaat, Zhaochun Ren, Mark Hoogendoorn, Vincent François-Lavet
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reinforcement learning (RL) has become central to LLM post-training, yet the methods that dominate current pipelines, PPO and GRPO, represent only a narrow slice of what RL offers. Understanding why these methods prevail, and what alternatives exist, requires a principled examination of the design decisions that underlie any RL algorithm. This survey organizes that examination around three stages of algorithm construction. We begin with MDP creation: how the reward function, state space, action space, termination condition, and discount factor are, or could be, defined for LLM training. We then turn to exploration, covering temperature sampling, entropy regularization, intrinsic motivation, tree search, and curriculum learning. Finally, we address learning along four classical RL dimensions: model-free versus model-based, value-based versus policy-based versus actor-critic, on-policy versus off-policy, and credit assignment, including both Monte Carlo methods, which rely on full return estimates, and bootstrapping methods, which update estimates using other learned predictions. Mapping the LLM literature onto this taxonomy reveals a strikingly non-uniform distribution of research effort. Critic-free policy gradients and Monte Carlo credit assignment are densely populated, while value-based methods, off-policy actor-critic training, and bootstrapping-based credit assignment remain largely unexplored despite well-established counterparts in classical RL. These gaps represent concrete opportunities for transferring proven RL techniques to LLM training. By making these gaps explicit alongside the methods that have proven effective, this survey offers researchers in both RL and LLMs a shared framework for understanding current practice and identifying promising directions for future work.
### Title:
          InstructFX2FX: A Multi-turn Text-to-Preset Demo for Iterative Audio Effect Refinement
 - **Authors:** Song-Ze Yu, Milan Liessens Dujardin, Yuxuan Cai, Wantong Zhang
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present InstructFX2FX, an interactive demonstration of multi-turn, text-guided audio effect refinement. Existing text-to-preset systems are largely single-shot, mapping one textual descriptor to one preset. Real audio engineering is instead sequential: engineers refine an existing effect chain through successive instructions such as "make it warmer" or "too harsh, soften it." This poses a stateful problem that single-shot systems do not address: given the current effect parameters and a new instruction, update the sound while preserving what earlier instructions already achieved. InstructFX2FX tackles this with a hybrid architecture that divides labor between a language model and CLAP-guided optimization. The LLM acts as a high-level planner that selects effects, orders the signal chain, and proposes initial parameters, motivated by recent evidence that LLM initialization outperforms CLAP optimization from a random start; CLAP-guided optimization then refines those parameters perceptually, giving more controllable updates than re-prompting the LLM at each turn, which tends to perturb settings the user did not ask to change. At the demo, attendees drive a dry recording through successive natural-language instructions and inspect the evolving FX chain, intermediate optimization checkpoints, and session state. On SocialFX-derived descriptor transitions, CLAP-guided refinement lowers target-directed DSP-feature MMD on 9 of 10 directed descriptor pairs relative to an LLM-only reprompting baseline, reducing the average MMD by roughly 24% (0.45 to 0.34).
### Title:
          GeoFlow-SLAM++: A Robust Multi-Camera Visual-Inertial SLAM System with Relocalization
 - **Authors:** Wei Fen, Tingyang Xiao, Liu Liu, Xiaolin Zhou, Zhizhong Su
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular and RGB-D visual-inertial SLAM systems remain susceptible to limited field of view, sensor-specific failure modes, and unreliable cross-session relocalization. To address these issues, we present GeoFlow-SLAM++, a tightly coupled multi-camera visual-inertial SLAM system that extends GeoFlow-SLAM from a single RGB-D sensor to a calibrated multi-camera rig with a unified body-centric formulation. Within this multi-camera framework, GeoFlow-SLAM++ supports two interchangeable visual front-ends: a conventional ORB front-end and a neural network feature (NN-Feature) front-end built on SuperPoint and LightGlue. The system unifies tracking, mapping, and relocalization on a shared body state, and combines multi-camera reprojection constraints, IMU pre-integration, cross-view place recognition, and dual-stream optical flow/NN-Feature tracking for robust localization. As an optional extension, the system can further incorporate cross-view-consistent pseudo-depth predictions from RGB images as auxiliary geometric constraints. We evaluate GeoFlow-SLAM++ on EuRoC, OpenLORIS, TUM, Hilti, and a self-collected handheld multi-camera dataset. Results show that the NN-Feature front-end improves robustness in appearance-challenging scenarios, the multi-camera formulation achieves competitive localization accuracy on Hilti, and the unified cross-view relocalization design reaches LiDAR-comparable performance on the handheld dataset.
### Title:
          ACEsplat: Accelerated 3D Gaussian Scene Regression via RGB and Poses Only
 - **Authors:** Mingkai Liu, Haohua Que, Dikai Fan, Haojia Gao, Tianle Zhu, Handong Yao, Qian Zhang, Ruopeng Zhang, Xianliang Huang, Fei Qiao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Per-scene 3D Gaussian Splatting (3DGS) enables high-fidelity rendering, but practical robotic and AR scene capture pipelines often depend on external geometric initialization (e.g., SfM point clouds or depth estimates), which can be slow and brittle in on-site deployment. We present ACEsplat, a fast per-scene optimization framework that reconstructs 3D Gaussian representations from RGB images and camera poses only, without requiring external 3D priors (e.g., precomputed SfM models or supervised depth maps). ACEsplat uses a two-stage pipeline: (1) a self-supervised scene coordinate regression (SCR) module builds an internal geometry prior within 4--5 minutes; (2) SCR features and coordinate priors are fused by a lightweight Gaussian initialization head, followed by per-scene 3DGS optimization. On static-view rendering, ACEsplat achieves 29.11 dB PSNR on Wayspots with real-time SLAM poses and 33.20 dB on Cambridge Landmarks with SfM-refined poses. On RealEstate10K sparse-view novel view synthesis, it achieves competitive image fidelity under a challenging 2-view setting. ACEsplat completes scene-specific SCR mapping and 3DGS reconstruction within 15--25 minutes on a single GPU, making it a practical RGB+pose-only solution for rapid scene setup in robotics and mixed-reality applications.
### Title:
          BioMatrix: Towards a Comprehensive Biological Foundation Model Spanning the Modality Matrix of Sequences, Structures, and Language
 - **Authors:** Qizhi Pei, Zhimeng Zhou, Yi Duan, Yiyang Zhao, Wei Li, Han Guo, Liang He, Chengping Li, Chang-Yu Hsieh, Conghui He, Rui Yan, Lijun Wu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Biomolecules (q-bio.BM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present BioMatrix, the first multimodal foundation model that natively integrates sequences, structures, and natural language for both molecules and proteins within a single decoder-only architecture. Existing biological foundation models pursue native multimodality and broad entity coverage separately: those that fuse multiple modalities under a shared objective remain confined to a single entity type, while those spanning multiple entity types either omit explicit structural modeling or rely on adapter-based designs in which the model cannot natively generate the very modalities it can read. BioMatrix closes this gap by mapping molecular sequences (supporting both SMILES and SELFIES notations), molecular structures, protein sequences, protein structures, and natural language into a shared discrete token space through a unified tokenization scheme, so that all modalities are consumed and produced uniformly under a single next-token prediction objective -- without external encoders, projection adapters, or modality-specific output heads. Built upon the Qwen3 language model (1.7B and 4B), BioMatrix is continually pretrained on 304.4 billion tokens spanning general and domain-specific text, sequence and structure views of molecules and proteins, and cross-modal corpora that interleave biomolecular entities with scientific text and link distinct entities through molecule-protein and protein-protein interaction data. After tuning on a comprehensive suite of downstream applications covering 80 tasks across 6 categories -- encompassing single-entity and multi-entity understanding and generation tasks across and within modalities -- BioMatrix achieves state-of-the-art or competitive performance on 77 out of 80 tasks, demonstrating that a single, natively multimodal generalist model can effectively match or surpass specialized approaches across a wide range of biological tasks.
### Title:
          Learning a Normal World Model for Few-Shot Boundary-Calibrated Abnormality Detection
 - **Authors:** Weizhi Nie, Weichao Liu, Weijie Wang, Yuting Su
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Science and Game Theory (cs.GT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Abnormality detection in complex systems faces two practical barriers: abnormal labels are scarce, and binary labels do not quantify how far an event has departed from normal behavior. We study a normal-world modeling formulation for this setting. Instead of learning a large and incomplete space of abnormal classes, the model learns the normal world from abundant normal events and uses a few abnormal examples only to calibrate the boundary of normality. We instantiate this idea as a Hypergraph Entropic Normal-World Model. The model represents multivariate sensor windows as context-conditioned hypergraphs, where hyperedges capture high-order relations among groups of variables. It then defines abnormality by an entropy-aware normal-world energy that combines temporal prediction surprise, hypergraph consistency surprise, and latent normal-manifold departure. On the NASA C-MAPSS turbofan degradation benchmark, the proposed full energy achieves strong zero-shot and few-shot performance across all four subsets and reaches AUROC 0.9983 on FD004, the most complex setting with multiple operating conditions and fault modes. Beyond standard detection metrics, we introduce mechanistic validation tests to probe whether the energy encodes normal-world structure rather than a superficial input-output mapping. The learned energy accepts unseen healthy engines, increases along degradation trajectories, and sharply penalizes context-mismatched cross-variable coupling breaks. These results suggest that normal-world energy can serve as an anomaly score, a graded risk measure, and a testable representation of normal system behavior under severe abnormal-label scarcity.
### Title:
          Encoder-Decoder Manifold Alignment for Idempotent Generation
 - **Authors:** Dareen Alharthi, Abdul Waheed, Bhiksha Raj
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recently, several learning paradigms have been introduced to enforce idempotency in generative models. The goal is to ensure that repeated application of a model leaves samples unchanged once they lie on the target data manifold. In practice, however, many of these approaches fail to achieve exact fixed points, leading to instability and drift under repeated application. In this work, we argue that a key reason for this failure is a geometric mismatch between the manifolds learned by the encoder and decoder. The encoder projects inputs onto one latent manifold, while the decoder implicitly learns to reconstruct data from a different manifold. This discrepancy prevents the model from learning truly idempotent mappings. To address this issue, we propose a new training framework that explicitly closes this gap by forcing the encoder and decoder to learn consistent representations of the same underlying data manifold. By aligning the geometry of these components, our method encourages stable projections. Empirically, we show that our approach achieves significantly lower idempotency error and consistently regenerates identical outputs under repeated application, compared to existing methods. We demonstrate the effectiveness of the proposed framework on both image generation and image editing tasks. Finally, we show that enforcing idempotency in this manner improves identity preservation and information stability, leading to more realistic and controllable generative editing models.
### Title:
          MetaPS: Adaptive Programmatic Strategy Selection for Market Agents
 - **Authors:** Jiaxiang Chen, Aotian Luo, Zhouyi Zheng, Weiyi Huang, Chi Zhang, Zenglin Xu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 No single market strategy always wins: momentum, mean reversion, risk control,and event-driven rules can each succeed or fail as market conditions this http URL than asking large language models to directly generate market actions,we study an executable decision paradigm where an agent selects from a library of programmatic strategies, each implemented as a code module mapping market observations to this http URL propose \textbf{MetaPS}, a simulation-guided framework for adaptive programmatic strategy selection. MetaPS rolls out candidate strategies in simulated or backtested markets, identifies states where particular strategies lead to better future outcomes, and converts these state--strategy pairs into supervised fine-tuning data. During inference, the simulator is no longer queried: MetaPS observes only the current market state and candidate strategy context, selects a suitable strategy program, and the selected program produces the final action. Experiments on multi-stock trading and a controlled goods-exchange sandbox show that MetaPS consistently improves across model scales from 0.8B to 9B parameters. It outperforms fixed-strategy baselines, direct decision-making agents, and prompted API-based LLM agents; in several settings, compact fine-tuned models even surpass stronger API models. These results demonstrate that market simulations can provide scalable and targeted supervision for learning adaptive, interpretable, and executable strategy selection.
### Title:
          HFORD: Hybrid Forward Optimization and Reverse Design Method and Its Applications to On-Chip Millimeter-Wave Inductive Elements
 - **Authors:** Yuzhen Song, Yifan Wang, Guqiao Chen, Hanyu Liu, Qi Wu, Guangyi Lu, Haiming Wang, Wei Hong
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 On-chip inductive elements are pivotal in determining both the silicon footprint and performance of millimeter-wave (mmWave) integrated circuits. However, the layout-level synthesis of these passive devices is severely challenged by highly nonlinear geometry-to-performance mappings, computationally expensive full-wave electromagnetic simulations, topology-dependent design spaces, and the inherent non-uniqueness of inverse design. To overcome these bottlenecks, we propose a hybrid forward optimization and reverse design (HFORD) method for the target-to-layout synthesis of mmWave inductive elements. Utilizing a unified core to map device-level requirements to layout-level seeds, HFORD structures direct device targets and translates circuit specifications into a hierarchical synthesis flow. Specifically, sparse-fitting sampling is introduced to improve coverage across critical performance regions, while compact response-fitting coefficients significantly reduce training dimensionality. The HFORD core integrates a random forest for topology selection, a variational autoencoder for spectral feature generation, a mixture density network for probabilistic inverse mapping, and particle swarm optimization for latent space exploration. This integration improves the feasibility of the generated layout seeds under design rule check (DRC) constraints. Two design examples demonstrate that the proposed method accelerates the design cycle from hours to minutes compared to conventional optimization methods.
### Title:
          Federated learning with heavy-tailed gradient noise and communication noise: a variance-reduction based algorithm
 - **Authors:** Shengchao Zhao, Yongchao Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Federated learning (FL) is an emerging distributed machine learning paradigm that enables local devices to jointly train a global model while keeping data decentralized and private. We propose a variance-reduction based algorithm, VRA-FedSGD, for FL in the presence of heavy-tailed gradient noise and communication noise, where these noises are prevalent in large-scale machine learning over wireless networks and Internet of Things deployments. VRA-FedSGD employs a momentum variance reduction technique together with a nonlinear mapping to mitigate heavy-tailed gradient noise, and uses a variance-reduced aggregation mechanism to suppress heavy-tailed communication noise. In the mean sense, VRA-FedSGD achieves a convergence rate of {\small$\mathcal{O}\left(K^{-(p-1)/(2p-1)}\right)$} for nonconvex objective functions, where $p$ is the tail index of heavy-tailed noise. In the almost sure sense, VRA-FedSGD achieves a convergence rate of $\tilde{\mathcal{O}}\left(K^{-(1-1/(p-\epsilon))}\right)$ for strongly convex objective functions, where $\epsilon$ is an arbitrarily small constant. Simulated experiments on a logistic regression problem with real-world data verify the effectiveness of VRA-FedSGD.
### Title:
          Physically-guided Image Generation for Multi-Projection Mapping
 - **Authors:** Xingyun Liu, Yuqi Li, Jinhui Xiang, Pinyan Tang, Chong Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Projection Mapping (PM) enables seamless superimposition of digital content onto real-world 3D objects, serving as a fundamental technique for immersive visualization, digital twins, and interactive art. Although text-to-image diffusion models have greatly facilitated customized content creation, directly integrating them into practical PM pipelines remains challenging due to the mismatch between idealized 2D generation and physical constraints. To bridge this gap, this paper formalizes two application-level generative paradigms: the cooperative paradigm (harmonizing generated semantics with physical attributes) and the adversarial paradigm (eliminating surface interference via radiometric compensation). Based on this, we propose ConPhyG, a unified controllable physically-guided generative multi-projection mapping framework that enables creators to interactively adjust physical constraints and flexibly switch generative paradigms. In cooperative mode, multi-dimensional physical priors (per-pixel gamut, depth, and edges) are injected into the diffusion process. In adversarial mode, the framework releases the generative potential and applies bounded numerical optimization for multi-projector radiometric compensation. It allows users to dynamically switch constraints to balance artistic freedom with physical feasibility. Furthermore, we extend ConPhyG to 360-degree multi-view consistent PM using a sequential generation strategy. Quantitative and qualitative evaluations on a real-world four-projector setup demonstrate that ConPhyG significantly outperforms state-of-the-art methods in geometric alignment, gamut utilization, and semantic fidelity.
### Title:
          PI-DOSnet: A Physics-Informed Deep Operator-Splitting Network for Evolution Partial Differential Equations
 - **Authors:** Jizu Huang, Yue Qian, Tao Zhou
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Evolution partial differential equations (PDEs) describe time-dependent physical systems governed by differential laws and arise widely across science and engineering. In recent years, operator learning has emerged as a powerful and efficient paradigm for solving evolution PDEs by learning mappings between infinite-dimensional function spaces, enabling solution prediction without explicit time-step integration. In this work, we propose PI-DOSnet, a physics-informed operator learning framework built upon DOSnet and operator splitting. Unlike purely data-driven operator learning methods, PI-DOSnet incorporates physical constraints during training, allowing it to operate even in the absence of paired input-output data. Once trained, PI-DOSnet performs long-time inference of PDE solutions through an iterative strategy. We analyze the linear stability and approximation error of PI-DOSnet and demonstrate its accuracy, efficiency, and robustness through multiple numerical experiments. Moreover, for the Allen--Cahn equation, PI-DOSnet achieves energy stable solutions even with a large time-step size.
### Title:
          Efficient Continuous Semantic Mapping based on Spatio-Temporal Awareness
 - **Authors:** My Le Pham, Dinh Trieu Duong, Xiem HoangVan, Thanh Nguyen Canh
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Continuous semantic mapping allows autonomous robots to understand both the spatial structure and the semantic content of complex environments. However, most existing methods process the entire space, treat voxels as independent units, and do not keep the semantic labels consistent over time. This leads to high computational cost and reduced robustness in dynamic scenes. This paper proposes a semantic mapping method that brings spatial and temporal relationships into the semantic inference process. The method adjusts the inference range according to the local semantic uncertainty and fuses labels over time to improve map stability and computational efficiency. Experiments on the SemanticKITTI dataset show that the proposed method improves mapping accuracy by about 12% and reaches an mIoU of 54.92%, which is 13.18 percentage points higher than spatial-only mapping. These results show that spatiotemporal reasoning is effective for continuous semantic mapping in autonomous robotic systems.
### Title:
          HERCULES: An Open-Source Simulation Framework for Heterogeneous Multi-Robot SLAM, Collaborative Perception, and Exploration
 - **Authors:** Sandilya Sai Garimella, Daniel Chase Butterfield, Sean Wilson, Lu Gan
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Multiagent Systems (cs.MA); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present HERCULES, an open-source simulator and data-collection pipeline for heterogeneous multi-robot autonomy. Built upon the Unreal Engine 5 (UE5)-based simulators AirSim and Cosys-AirSim, HERCULES resolves key architectural limitations of prior frameworks to enable concurrent unmanned aerial and ground vehicle (UAV-UGV) operation in large-scale, photorealistic, dynamic environments. It introduces a new waypoint-tracking UGV controller that mirrors existing UAV control interfaces, and provides a shared navigation stack for mapping, traversability analysis, planning, and control across heterogeneous platforms. Expanding inherited sensor suites, it adds physics-based long-wave infrared (LWIR) cameras and configurable night-vision modes for degraded visual environments. HERCULES provides lightweight APIs, ROS 2 wrappers, and rigorous time synchronization across sensors and platforms, and brings state-of-the-art game-engine capabilities into robotics simulation, integrating intelligent agents such as pedestrians, traffic, and wildlife with high-fidelity dynamic phenomena, including fire, flooding, and crop disease spread. HERCULES runs in two modes: passively, replaying offline-designed trajectories to generate reproducible multi-modal datasets, and actively, running an online planner in closed loop from live observations. Our experiments in heterogeneous multi-robot SLAM, collaborative perception, and exploration, using both HERCULES-generated data and active closed-loop execution, demonstrate its utility for advancing heterogeneous multi-robot autonomy. We publicly release our source code, experiment code, documentation, and datasets, including a heterogeneous multi-robot SLAM benchmark collected with two UAVs and two UGVs across kilometer-scale desert, forest, and city environments, at this https URL.
### Title:
          A Formula-Driven Survey and Research Agenda for On-Policy Distillation
 - **Authors:** Bowen Zhang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 On-policy distillation (OPD) trains an LLM on states induced by the current or recent student policy: the student generates complete or partial rollouts, a teacher or self-teacher scores the resulting tokens under their generated contexts, and dense log-probability, logit, or distributional signals are converted into post-training updates. This survey studies OPD as a feedback-to-update problem rather than a single loss family. We develop a formula-driven taxonomy from two routes -- direct distributional losses and policy-gradient-style log-ratio updates -- and use it to organize core methods, verifier- or outcome-guided hybrids, industrial reports, framework implementations, failure modes, and stabilization recipes under explicit evidence boundaries. The taxonomy shows that OPD effectiveness depends not only on KL direction or teacher access, but also on state compatibility, support construction, temporal credit, vocabulary-level probability routing, gates and weights, and regularization. We further separate two mechanisms often conflated in sampled-token OPD stability discussions. Temporal credit asks how teacher-student log-ratio returns should weight sampled actions across a rollout; vocabulary routing asks where probability mass should move when negative feedback suppresses a sampled token. This distinction yields bias boundaries for immediate, return-to-go, discounted, and baseline-corrected estimators, motivates GAE-OPD as a value-based hypothesis for log-ratio returns, and motivates Counterfactual Routed OPD (CR-OPD) for routing probability mass toward teacher-supported, student-reachable alternatives. We close by mapping actionability diagnostics, failure mechanisms, case studies, open problems, and a reporting checklist onto the same feedback-to-update variables.
### Title:
          Measuring Behavior Portability in Large Language Models
 - **Authors:** Tianjia Dong, Nadav Kunievsky, James A. Evans
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computers and Society (cs.CY); Computer Science and Game Theory (cs.GT); General Economics (econ.GN)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models are increasingly deployed as autonomous decision makers, yet the behavioral mapping they exhibit can vary substantially across decision environments that are payoff-equivalent by construction-environments that share identical payoff-relevant structure but differ in surface presentation. This sensitivity renders suite-based evaluation fragile and raises a fundamental question of behavioral portability: how well does a behavioral mapping learned in one decision environment informative on another that preserves the same underlying incentive structure? We introduce a formal framework to measure this property. Our protocol fits an interpretable behavioral model on data pooled from a set of source environments and evaluates its out-of-sample predictive performance in a held-out target environment, benchmarking against an oracle trained directly on target data. Portability is quantified via a loss-agnostic measure that delivers worst-case bounds on the performance of the induced prediction-action mapping in the target environment. In controlled experiments spanning seven canonical economic decision problems, we document substantial and systematic portability losses, suggesting that behavioral characterizations of LLMs obtained in one decision environment cannot be assumed to transfer reliably to structurally equivalent alternatives.
### Title:
          Machine-knittable, Magnetically-Plug-n-Play E-Textile Prototyping
 - **Authors:** Yifan Li, Ryo Takahashi, Wakako Yukita, Irmandy Wicaksono, Kanata Matsutani, Yuhiro Iwamoto, Sunghoon Lee, Tomoyuki Yokota, Takao Someya, Yoshihiro Kawahara
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electronic textiles (e-textiles) integrated with wearable sensors are essential for daily motion monitoring and long-term physiological sensing. For example, capturing optimal kinematic or bio-signals requires aligning sensors with specific anatomical parts, which vary significantly across individuals and application scenarios. This necessity for personalization makes e-textile prototyping inherently iterative, however current fabrication methods, such as manual conductive stitching, rely on permanent bonds that restrict rapid adjustment. This paper introduces Plug-n-play e-knit, a machine-knittable e-textile prototyping platform that enables repeatable, quick adjustment of sensor positions across garments. First, to cover the large area of the textile for prototyping, we use industrial digital knitting of conductive yarn to integrate power and communication buses directly into the large-scale textile. Then, to ensure plug-n-play attachment to the textile, we employ soft-magnetic connectors that enable sensors to be repeatedly plugged into the wiring without damaging the fabric. Furthermore, our LED-positioning system enables the automatic identification and localization of each sensor node. We demonstrate the platform's capabilities through forearm movement calibration and position-aware temperature mapping.
### Title:
          Clutch: High Performance Vector-Scalar Comparison using DRAM via Chunked Temporal Coding
 - **Authors:** Daichi Tokuda, Tatsuya Kubo, Ismail Emir Yuksel, Ataberk Olgun, Haocong Luo, Tomoya Nagatani, Geraldo F. Oliveira, Abdullah Giray Yağlıkçı, Mohammad Sadrosadati, Onur Mutlu, Shinya Takamaeda-Yamazaki
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vector-scalar comparison is a fundamental computation primitive that compares each element in a vector against a single scalar value. It is widely used in various data-intensive workloads from databases to machine learning. Due to its low computational intensity, its execution tends to be memory-bound, limiting the utilization of compute resources. Processing-using-DRAM (PuD) is an emerging computing paradigm that performs massively parallel bitwise operations directly inside DRAM arrays, alleviating off-chip data movement. Existing PuD-based approaches require many DRAM commands because the comparison's algorithmic complexity grows with operand bit-width in the bit-serial execution model. This command overhead becomes the dominant bottleneck, limiting application-level speedup. We propose Clutch, a data representation and comparison algorithm that accelerates vector-scalar comparisons in PuD systems with high efficiency and scalability. Clutch first uses temporal coding, encoding each vector value as a sequence of leading ones, which enables lookup-based comparison against a scalar by accessing the corresponding DRAM row. To avoid the prohibitive memory footprint of lookup tables at high precision, Clutch partitions operands into multiple multi-bit chunks, compares chunks independently using compact lookup tables, and merges the per-chunk results with a PuD-efficient procedure. By adjusting the number of chunks, Clutch provides a flexible tradeoff between throughput and memory usage. Across predicate evaluation and decision tree inference, Clutch improves end-to-end application throughput and energy efficiency by an average of 12x and 69x over highly optimized CPU and GPU execution, and by 2.9x and 3.0x over the state-of-the-art bit-serial PuD implementation. We also present the first mapping of decision tree inference to PuD execution, extending PuD to a new application domain.
### Title:
          DJM: Compact Base Meshes for Displacement Mapping using Triangle Jacobians
 - **Authors:** Congyi Zhang, Nicholas Vining, Yanhong Lin, Alireza Khatami, Ziyu Sun, Xiaohu Guo, Wenping Wang, Alla Sheffer
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Representing complex geometry as a displacement function defined over a coarse base mesh enables compact storage and accelerated rendering. The core challenge in converting detailed triangle meshes into this representation is computing base meshes that have as few triangles as possible, while also supporting displacement functions that accurately approximate the input. Accurate approximation requires the supported displacement functions to bijectively map the input surface onto the base with low parametric distortion. We observe that this distortion can be measured by evaluating the pointwise Jacobian of the displacement functions. Our new DJM (Displacement Jacobian Metric)-based base-mesh construction method uses the Jacobian of the displacement functions to guide base mesh computation, enabling us to outperform prior approaches in terms of accuracy to size trade-off. We achieve this goal by proposing a variant of the QEM-based simplification scheme that constrains the displacement mapping between the input and the base to be bijective and low distortion (defined as satisfying a lower bound on the mapping Jacobian). When evaluating and encoding the displacement maps, we avoid unreliable ray-mesh intersections by explicitly storing the mapping between the input mesh and the base throughout the construction process, and use this mapping within a robust inverse barycentric displacement solver to obtain dense base-to-mesh correspondences to assist all computations. We demonstrate DJM to outperform alternative schemes in terms of reconstruction accuracy to size trade-off, and demonstrate its robustness and usability for micromesh-based rendering and neural encoding.
### Title:
          A Vendor-Agnostic LiDAR Data Conversion System with Multi-Signal Detection and Multi-Format Output
 - **Authors:** Param Patel, Jay Dave, Pratyush Chakraborty
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR (Light Detection and Ranging) sensors capture the surrounding environment as dense 3D point clouds by measuring the time-of-flight of emitted laser pulses, making them foundational across autonomous vehicles, robotics, and large-scale mapping. PCAP (Packet Capture) files from these sensors are the starting point of most 3D perception pipelines, yet internal packet structures, UDP (User Datagram Protocol) port conventions and encoding schemes differ enough across manufacturers that no single tool reads them all. Ouster, Velodyne, Hesai, and Livox each require their own SDK (Software Development Kit), their own environment setup, and their own conversion workflow. Supporting all four means maintaining four disconnected pipelines with no shared infrastructure. The pipeline described here takes a raw PCAP as input and handles vendor identification automatically, scoring six independent file characteristics through a weighted multi-signal approach to determine the source sensor. C++ SDKs handle Ouster and Velodyne, while Hesai and Livox rely on Python-based dpkt parsing where no open source SDK exists. From there, a single command writes output to any of five industry-standard formats. We tested on real outdoor captures. Ouster peaks at 2.08M points per second, Velodyne at 1.47M, both running through native C++ packet decoding. Hesai and Livox land at 110K and 150K respectively, where Python-layer parsing introduces overhead that compounds under sustained load. The 8-10x gap held consistently across runs. Tested on a consumer-grade i3 with 8GB RAM, no vendor configuration required
### Title:
          Neural Operator Processes for Probabilistic Operator Learning under Partial Observations
 - **Authors:** Jose Miguel Lara-Rangel, Serge Guillas
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators learn mappings between function spaces, but are typically developed with dense input-output training fields and fully observed inputs at inference. Many scientific problems require instead predicting solution fields from sparse, irregular, or partial observations under uncertainty. We introduce Neural Operator Processes (NOPs), a framework that unifies neural-process conditioning with neural-operator decoding to predict full output fields from limited context. NOPs condition on sparse joint input-output observations and support deterministic and probabilistic prediction within a shared encoder-decoder architecture. We study two conditioning strategies, convolutional pooled summaries and query-aligned attention, and analyze how their interaction with latent stochastic variables depends on PDE geometry. Across function regression and three PDE benchmarks, we find that sparse conditional operator learning is viable and can match dense-grid behavior in several regimes, that preserving local context-query geometry is essential in non-periodic settings but less so in spectrally smooth periodic regimes, and that uncertainty-aware operator learning succeeds when latent conditioning complements rather than overwrites the local geometric pathway. These results provide a basis for probabilistic operator learning under partial observations and help bridge operator learning and probabilistic meta-learning in function space.
### Title:
          Counterfactual learning of new adaptive instructional policies using logged data
 - **Authors:** Samuel Girard (SODA), Sein Minn (AIT), Amel Bouzeghoub (IP Paris, TSP - INF, ACMES-SAMOVAR), Jill-Jênn Vie (SODA)
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Optimizing instructional policies in Intelligent Tutoring Systems (ITS) typically requires costly online experimentation or student simulators that may fail to capture real-world dynamics. This paper introduces an offline contextual bandit framework that learns new adaptive policies directly from logged interaction data. By mapping student-item interactions onto a continuous latent proficiency-difficulty scale using a Rasch model, we cast the tutoring process as a continuous stochastic bandit problem. We propose a novel reward function designed to optimize ''flow'' by balancing task challenge with student success. Our approach includes a round-specific behavior policy estimation that serves as both a propensity model for off-policy evaluation and a diagnostic tool for ITS adaptivity. We demonstrate the efficacy of this framework across four large-scale real-world datasets, achieving consistent policy improvements over the logged behavior policy. The results show that effective instructional policies can be learned and visualized within seconds of computation, providing a scalable path for improving adaptive learning systems without further data collection.
### Title:
          Scene-agnostic ALS boresight self-calibration
 - **Authors:** Aurélien Brun, Jan Skaloud
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 ALS boresight calibration has relied for two decades on dedicated flight patterns over structured scenes containing planar surfaces of varied aspect and slope. While reliable, this approach imposes constraints on the scene content and operations, which limits its applicability to boresight recovery within routine mapping missions. We present a practical approach that substantially relaxes these requirements by replacing plane-based constraints with scene-agnostic point-to-point correspondences extracted automatically from overlapping ALS strips. Two complementary formulations are proposed to estimate boresight with laser vector observations: (i) a simpler parametric adjustment utilizing INS/GNSS trajectory; (ii) a rigorous formulation treating GNSS and raw inertial data within an existing factor-graph, i.e. a dynamic network, where boresight is added as an additional parameter. Both formulations are evaluated across four operational ALS flights equipped with five inertial systems, covering a wide range of flight altitudes, overlap geometries, terrain types and inertial sensor classes. The analysis draws a clear boundary between the legacy plane-based conditioning that falls short outside the calibration scenario and the proposed formulations, which either recover or absorb boresight effects under conventional mapping geometry. Among them, the lightweight formulation is sufficient for boresight recovery using tactical and navigation grade inertial sensors, while the general factor-graph approach is clearly superior when the inertial sensor errors are less observable within an optimal smoother. This supports the hypothesis that, for INS/GNSS trajectory of sufficient quality, the boresight calibration can be performed without particular scene prerequisites during routine mapping operations using a minimum of 3-4 overlapping strips, with either proposed formulation...
### Title:
          A Dual-Track Framework for Template-Constrained LaTeX Conversion
 - **Authors:** Chung Cheuk Hei, Liu Li
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the increasing demands for advanced document conversion, mapping structured Markdown drafts into template-compliant formats like LaTeX remains a challenge. Existing approaches largely depend on either deterministic rule-based converters or pure end-to-end Large Language Model (LLM) generation. The former fails to correctly handle asset insertions and template-specific constraints, while the latter tends to induce semantic drift, leading to hallucinations that are difficult to debug. To address these limitations, we introduce a robust Dual-Track Framework that systematically decouples template formatting from document processing: an offline track extracts template constraints into a reusable manifest, while an online track implements a hybrid execution pipeline. This pipeline confines LLM usage exclusively to reasoning-intensive components (e.g., semantic metadata, bibliographic references, and complex visual/tabular layouts) while delegating rule-based engines for deterministic processing. Empirical evaluation across 7 LaTeX templates and 56 published research papers demonstrates that our method preserves better structural fidelity, satisfies diverse layout constraints, and achieves a higher compilation success rate compared to the previous baselines.
### Title:
          General-Purpose Nonlinear Function Approximation via Linear Integrated Photonics
 - **Authors:** Ayana Mizuno, Isamu Takai, Makoto Nakai, Atsutaka Miyamichi, Ryuichi Konishi, Satoshi Sunada
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET); Optics (physics.optics)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Photonic computing has emerged as a promising platform for accelerating artificial intelligence workloads by enabling low-latency and energy-efficient linear operations such as vector-matrix multiplication. However, scalable on-chip high-order nonlinear processing remains challenging, limiting the functional versatility of current photonic hardware. Here, we present an optoelectronic approach for approximating high-order and high-dimensional nonlinear functions. The key to this approach lies in optical random Fourier feature mapping, which transforms nonlinear function evaluation into an equivalent linear computation. This approach enables nonlinear computing within a linear photonic framework, eliminating the need for complex optical nonlinear or active materials while preserving scalability and computational throughput in a simple silicon photonic circuit. We experimentally demonstrate a broad class of nonlinear functions, including tenth-order Legendre polynomials, computationally demanding special functions (Voigt, Fermi-Dirac, and Fresnel), neural-network activation functions, two-dimensional nonlinear functions, and a 10-dimensional softmax layer. This work establishes a general and scalable strategy for nonlinear computing in photonic integrated hardware and opens a pathway toward fully functional optical accelerators for next-generation computing systems.
### Title:
          Adaptive Hard-Soft Physics-Informed Neural Networks for Robust Boundary-Constrained PDE Solving
 - **Authors:** Duc Tien Nguyen, Trinh Minh Tuan, Nguyen Duc Manh, Vu Linh Nguyen, Dinh Gia Ninh
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physics-informed neural networks (PINNs) provide an effective way to solve partial differential equations (PDEs) by embedding physical principles into the learning process. However, the conventional PINN formulation, in which all constraints are imposed as soft penalty terms within a composite loss, often exhibits slow convergence, sensitivity to loss weight scaling, and inaccurate boundary enforcement due to poor conditioning of the optimization landscape. To address these limitations, this study proposes a unified hard--soft physics--informed neural network (HSPINN) with adaptive loss weighting. In this framework, Dirichlet and periodic boundary conditions are enforced exactly by construction through analytical or polynomial lifting, masking functions, and periodic feature mappings, while the governing PDE residuals, Neumann fluxes, and initial conditions are treated as soft constraints. An inverse-share softmax strategy dynamically balances the relative importance of individual loss components during training, eliminating manual penalty tuning and improving gradient stability. This formulation ensures boundary admissibility throughout optimization and enhances convergence efficiency and numerical robustness. Applications to representative elliptic (Poisson), parabolic (Burgers), and hyperbolic (convection with periodic boundaries) problems demonstrate that HSPINN consistently achieves faster convergence, higher accuracy, and greater stability than conventional PINNs, establishing a general and scalable foundation for physics-constrained deep learning across science and technology.
### Title:
          DexTeleop-0: Force-Aware Bimanual Dexterous Teleoperation with Ego-Centric Perception towards Shared Autonomy
 - **Authors:** Haichao Liu, Yuyao Jiang, Hyunsun Park, Yuanjiang Xue, Ziwei Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-grained, bimanual dexterous manipulation remains a foundational challenge in robotics. Traditional teleoperation systems often fail in contact-rich tasks because embodiment gaps hinder accurate kinematic mapping, while tactile and force feedback remain absent. Consequently, data collection efficiency for high-precision tasks remains prohibitively low. To address these limitations, we propose a tactile-driven adaptation strategy designed to enable fine-grained manipulation on top of teleoperation pipelines. Instantiated within our bimanual dexterous framework, DexTeleop-0, this strategy introduces a real-time optimization loop that bridges the embodiment gap by translating coarse human tracking intents into precise, force-compliant robotic commands with tactile sensing. By estimating accurate contact points and leveraging a tactile-enabled fingertip force-sensing profile, the system dynamically computes localized corrections using the operational space Jacobian with respect to joint angle updates. We rigorously evaluate this tactile-driven adaptation strategy across both simulated environments and real-world hardware. Compared with representative baselines, the proposed method consistently achieves higher task success rates and improved execution efficiency in robust grasping, disturbance-resilient manipulation, and complex dexterous tasks.
### Title:
          Ensuring Open Source Integrity: The Intersection of Copy-Based Reuse and License Compliance
 - **Authors:** Mahmoud Jahanshahi, Bogdan Vasilescu, Audris Mockus
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As other creative work, source code is protected by copyright. The owner can license the work, e.g., to permit copy and other kinds of use, and even start legal proceeding against license violators. However, source code can be reused in subtle ways, e.g., via copying without explicit package manager dependencies, making it hard to reason about potential license noncompliance. Using the World of Code infrastructure approximating the entirety of open source software, in this paper we create a copy-based code reuse network mapping direct copying across projects, and use it to quantify the extent of potential license noncompliance across the entire open source ecosystem. In addition, we estimate regression models to understand whether code copying is affected by the origin project's license, and, if so, how it varies with other project characteristics. We find that code in repositories with permissive licenses, such as MIT and Apache, shows higher likelihood of reuse across programming languages. In contrast, copyleft licenses, like the GPL, exhibit mixed effects. Public domain licenses, despite their aim of allowing unrestricted use, are associated with lower likelihood of copy-based reuse. A widespread potential license noncompliance appears to accompany copy-based reuse, with 39.4% of project combinations at potential noncompliance risk, particularly when licenses are unclear or absent. Our findings reveal that only 2.43% of reuse detected through the copy-based network was discoverable via dependency analysis, highlighting the limitations of existing dependency-tracking tools in capturing copy-based reuse.
### Title:
          Discovering Latent Groups for Robust Classification
 - **Authors:** Ankur Garg, Ulrich Aïvodji, Samira Ebrahimi Kahou, Vincent Michalski
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Machine learning models exploit spurious correlations, achieving high average accuracy but failing disproportionately on underrepresented subgroups. Existing methods address this by adjusting network parameters, guided either by subgroup annotations or inferred pseudo-group labels. Yet at inference, these methods produce only a class prediction, with no insight into a sample's latent subgroup. We propose neural classification trees (NCT), a framework that achieves robustness by encoding subgroup structure in its tree-shaped architecture. By routing each sample to an "easy" or "hard" node of this tree -- based on prediction correctness -- and reusing these routes as pseudo-labels for the next iteration, NCT disentangles conflicting subgroups, without requiring subgroup supervision. We evaluate NCT on five benchmarks spanning binary and multi-class spurious correlations. Our experiments show that the learned tree topology provides strong interpretability by consistently isolating minority subgroups, which provides a transparent mapping between the model architecture and the data's latent group structure, while yielding competitive robustness with state-of-the-art methods.
### Title:
          Hedgementation = Hedgerow Segmentation: A Remote Sensing Benchmark
 - **Authors:** Nathan Senyard, Salem Hamdani, Astrid Zhang, Derek Wang, Evan Shelhamer, Mathias Lécuyer, Joséphine Gantois
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose Hedgementation: a new benchmark to evaluate machine learning models for hedgerow mapping from remote sensing data at country scale and 10m$^2$ spatial resolution. We combine and harmonize multiple remote sensing data products and ground truth labels sourced from a hedgerow inventory in France. We measure the ability of three baseline models to generalize across spatial distance, and across climatic zones, a more explicitly challenging task. Our benchmark tests both supervised and self-supervised learning approaches for remote sensing, applied to tracking fine-scale features of high agricultural importance. The code to reproduce the benchmark and baselines results is available at this https URL.
## Keyword: localization
### Title:
          D2HDMap: Non-visible Driveline Map Prior for Online Vectorized HD Map Prediction
 - **Authors:** Seojun Shon, Chikao Tsuchiya, Dhaval Bhanderi, David Ilstrup, Hsinmin Cheng, Christopher Ostafew
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate, up-to-date representations of road structures are critical for the safe operation of autonomous vehicles. Existing systems rely either on costly, maintenance-heavy high-definition (HD) maps which compromise safety when outdated, or purely sensor-based online mapping which struggles with long-range reliability and occlusion. Systems incorporating map prior information into online mapping seek to overcome drawbacks of both approaches by combining them in some way. We propose 'Driveline To HD Map' (D2HDMap), an online mapping system that injects a lightweight, non-visible driveline prior to guide the estimation of visible road structures such as lane dividers, road boundaries and crosswalks. This prior incurs less effort to create and update compared to full HD map priors used in other approaches. We also show that training with such a prior can improve generalization at inference time when no prior is available. Ablation studies conducted on the nuScenes and Argoverse 2 dataset demonstrate that models trained using a driveline prior largely retain performance even when priors are not available. On a geographically disjoint split, D2HDMap achieves 44.8 mAP, surpassing recent state-of-the-art. Additionally, noise-aware training substantially increases robustness to realistic localization error.
### Title:
          UNSEEN: Uncertainty-aware Navigation via Sparse Estimation in Unknown Environments
 - **Authors:** Tommaso Faraci, Marco Camurri, Daniele Fontanelli, Luigi Palopoli
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual navigation in unknown environments remains a core challenge in mobile robotics, especially for resource-constrained platforms. Most existing approaches rely on loosely coupled modular pipelines and strong assumptions on perception quality or environmental structure, often resorting to multi-modal sensor suites that increase system complexity and deployment cost. Vision-only navigation offers a lightweight alternative, but its performance degrades severely under motion blur, low texture, and illumination changes, largely because they neglect the tight coupling between commanded motion and perception. While perception-aware methods partially address this issue, they typically optimize individual modules and fail to propagate uncertainty consistently across the navigation stack. In this paper, we present UNSEEN, a unified uncertainty- and perception-aware navigation framework that explicitly couples localization, mapping, and planning using only a front-mounted camera. UNSEEN estimates sparse maps and robot poses with associated uncertainties at 6Hz, and leverages them to plan trajectories that jointly optimize task progress and estimation accuracy in receding-horizon. Simulations and extensive real-world experiments in unknown environments demonstrate the robustness of the proposed approach, with UNSEEN-SLAM reducing absolute translational error by 9.8% and UNSEEN-Plan improving estimation accuracy by up to 45% compared to state-of-the-art methods, while achieving a 100% task success rate.
### Title:
          A Topology-Aware, Memory-Centric Architecture that Separates Root-Cause Derivation from Root-Cause Explanation
 - **Authors:** Momil Seedat
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern microservice deployments fail in ways that are easy to detect and hard to explain. When a fault propagates along service dependencies, alerts fire in floods, dashboards multiply, and the scarce resource, an engineer who understands how the services relate, is consumed reconstructing context that the monitoring stack discarded. We argue that the missing ingredient in autonomous operations is not a better anomaly detector or a larger language model, but operational memory: a persistent, structured representation of how a system normally behaves, how its parts depend on one another, and how it has failed before. We present O PS C ORTEX, a working multi-agent prototype that organizes this memory into four tiers and uses it to separate two tasks the field usually conflates: deriving a root cause and explaining it. Root cause is computed deterministically from a learned dependency graph and the temporal ordering of threshold crossings; a large language model (LLM) is then asked only to explain, confirm, and recommend, using evidence the system has already assembled. We motivate the design with two documented production cascading failures, review representative literature on observability, anomaly detection, graph-based localization, and LLM-assisted diagnosis, and show how each architectural choice maps directly to a failure mode those incidents exhibit. The prototype is validated on an instrumented e-commerce benchmark with eight injectable failure scenarios.
### Title:
          An implicitization-based solution to the minimal 4s/6r ToA problem using Cayley--Menger determinants
 - **Authors:** Evgeniy Martyushev
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The paper introduces an efficient algebraic solver for the 4-sender/6-receiver (4s/6r) Time-of-Arrival (ToA) self-localization problem, which involves determining the relative positions of all receivers and senders given their pairwise distance measurements. The problem is addressed through a new parametrization combining Cayley--Menger determinants with an implicitization technique. The proposed algorithm proceeds in three steps. First, a 148 x 211 Macaulay matrix is constructed from the coefficients of the original polynomial system. Second, PLU decomposition of this matrix yields a 63 x 63 matrix pair. Finally, up to 38 real solutions are obtained via generalized eigendecomposition followed by a validation step. Experiments on synthetic noise-free data demonstrate that the proposed solver outperforms existing methods by approximately three orders of magnitude in numerical accuracy while achieving an average runtime of 1.3x faster than the fastest alternative. Experiments on a real-world acoustic dataset confirm that, when integrated within a RANSAC framework, the solver provides a reliable initial guess for bundle adjustment refinement.
### Title:
          A Metaheuristic Framework for Optimized HAPS-Aided Localization in Urban Areas
 - **Authors:** Hongzhao Zheng, Mohamed Atia, Halim Yanikomeroglu
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-altitude platform stations (HAPS), originally designed for communication services, can also provide structured signals of opportunity (SoOP) to augment the global navigation satellite system (GNSS). However, dense urban environments introduce severe blockage and non-line-of-sight (NLOS) conditions that undermine GNSS accuracy and render geometric placement metrics insufficient. To address this, we propose a metaheuristic framework for jointly optimizing the number and placement of HAPS under practical constraints by integrating high-fidelity 3D city models, ray-tracing, and multi-objective optimization to handle the discrete and highly non-convex design space. Three metaheuristic solutions based on distinct search principles are developed to efficiently explore the solution space, all demonstrating rapid convergence and consistently outperforming a greedy baseline, particularly in the low-to-moderate HAPS regime. For representative dense urban scenarios, we show that four HAPS are sufficient to satisfy an 18-m average 3D positioning error bound (PEB) threshold, while configurations with two to five HAPS achieve over 50\% reduction in mean and root mean square (RMS) PEB and up to 94\% and 87\% reduction in standard deviation and coefficient of variation (CV), respectively, compared to the satellite-only case. Diminishing returns are observed beyond six HAPS due to geometric redundancy, emphasizing the importance of optimized placement. The framework further demonstrates strong robustness and generalizability across diverse urban environments with varying building morphology and propagation conditions, establishing it as an effective and scalable solution for HAPS-assisted localization in realistic urban settings.
### Title:
          Vesta: A Generalist Embodied Reasoning Model
 - **Authors:** Johan Bjorck, Zhiqi Li, Yunze Man, Jing Wang, An-Chieh Cheng, Sifei Liu, Shihao Wang, Zhiding Yu, Abhishek Badki, Stan Birchfield, Valts Blukis, Yevgen Chebotar, Siyi Chen, Sicong Leng, Yu-Cheng Chou, Tianli Ding, Boyi Li, Zhengyi Luo, Hang Su, Jonathan Tremblay, Tingwu Wang, Bowen Wen, Jimmy Wu, Xianghui Xie, Hanrong Ye, Hongxu Yin, K.R. Zentner, Liangyan Gui, Yu-Xiong Wang, Yuke Zhu, Linxi "Jim" Fan, Jan Kautz
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robots operating in open-world environments must seamlessly integrate localization, spatial reasoning, navigation, and long-horizon planning. While specialist models excel at individual tasks, deploying a multi-model stack is computationally expensive and prone to cascading errors. We present Vesta, a unified embodied generalist that consolidates these capabilities into a single foundation model. Our approach combines a diverse and massive curated corpus designed to induce spatial grounding and a simple multimodal memory harness that enables reasoning over extended time horizons. Across diverse benchmarks, Vesta on average beats individual SOTA baselines by >$20\%$ and beats an ensemble of per-category-best baselines by $>10\%$ -- thus demonstrating that a generalist model can match or exceed specialists. On real-world robotic tasks requiring memory and reasoning, Vesta improves task success by >35\%. Our work thus demonstrates that a single generalist is a feasible, scalable, and arguably preferable alternative to combining specialists.
### Title:
          Scaling Diverse Language Generation for 3D Visual Grounding
 - **Authors:** Austin T. Wang, Dongchen Yang, Angel X. Chang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Developing robust models for 3D visual grounding (3DVG), the localization of entities in a 3D scene described in natural language, is important for enabling agents to correspond spatial language with objects in the physical world. However, the lack of diverse descriptions at scale prevents models from generalizing beyond simple linguistic patterns. Recent such attempts lack diversity in the constraint types and language used to ground objects. Captioning methods cannot precisely contrast objects, which is important for visual grounding. We therefore propose ViGiL3D++, a scalable, scene-agnostic method that generates diverse visual grounding queries by combining constraint sampling in scene graphs with the language generation of LLMs. We show that it has greater diversity over existing scaled datasets and improves model performance over several 3DVG benchmarks but also illuminates outstanding limitations of VLMs.
### Title:
          SARIF: Segment Anything for Robust Image Forensics
 - **Authors:** Dong-Hyun Moon, Ju-Hyeon Nam, Sang-Chul Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Image forgery localization remains challenging due to diverse manipulation techniques and distribution shifts. Existing forgery localization models achieve high accuracy on benchmarks but often struggle with cross-domain generalization and robustness. In this paper, we propose SARIF (Segment Anything for Robust Image Forensics), a framework that leverages the Segment Anything Model (SAM), which has a promptable architecture and strong generalization ability. SARIF introduces a feedback-guided mask decoder and a dual-encoder design that extracts forgery-specific information to capture forensic traces while exploiting the SAM architecture. To localize manipulated regions, we design a block-wise prompting mechanism that derives forgery-specific cues from residual features between an adapted encoder and its frozen counterpart. These features are fused with the previous mask prompt to drive a feedback-based mask refinement process, enabling automatic forgery segmentation without manual input. Extensive experiments on standard forgery-localization benchmarks show that SARIF achieves strong average cross-dataset performance and robustness to common image corruptions.
### Title:
          SEED: Simple ViT and Evolving Harness for Explainable Text Forgery Detection
 - **Authors:** Kahim Wong, Kemou Li, Yiming Chen, Haiwei Wu, Jiantao Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI-assisted image editing threatens trust in financial, legal, and identity records. The GenText-Forensics Challenge at ACM MM 2026 addresses this by requiring structured forensic reports, in which integrating detection, pixel-level localization, and natural language explanation for multilingual text-centric forgery images. We present SEED, a modular system with three components. First, a similarity-guided pipeline augments training with diverse synthetic forgeries. Second, a single ViT, built on DINOv3 with LoRA adaptation, jointly performs detection and pixel-level localization while preserving pre-trained priors with minimal trainable parameters. Third, an evolving harness takes the detector's predictions and generates a complete forensic report via an MLLM, iteratively improved through a proposer-evaluator loop optimizing report quality. SEED ranked 3rd in the GenText-Forensics Challenge. Code and data are available at this https URL.
### Title:
          Ultra-Fusion: A Resilient Tightly-Coupled Multi-Sensor Fusion SLAM Framework under Sensor Degradation and Spatiotemporal Perturbation for Intelligent Transportation Systems
 - **Authors:** Yihong Tian, Junjie Zhang, Liuyang Li, Deteng Zhang, Yunfei Zuo, Jie Yin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable localization is essential for intelligent transportation systems (ITS), including autonomous vehicles, quadruped last-mile carriers, and infrastructure-inspection unmanned aerial vehicles (UAVs). Although tightly-coupled multi-sensor fusion improves accuracy in favorable conditions, deployed systems remain vulnerable to sensor degradation -- poor illumination, LiDAR degeneracy, wheel slippage, and GNSS outage -- and to spatiotemporal calibration errors. These failures are common in urban canyons, tunnels, and high-speed corridors, where localization drift can degrade route tracking, tunnel passage continuity, and local map alignment. This paper presents Ultra-Fusion, a tightly-coupled multi-sensor localization framework based on a unified sliding-window estimator. Asynchronous measurements are timestamp-ordered and converted into optional factors within one optimization window, supporting WIO, VIO, LIO, and LVIO with optional wheel and GNSS augmentation. Observability-aware initialization selects the bootstrap mode, factor-wise reliability scheduling gates degraded measurements, and online LiDAR--IMU spatiotemporal calibration refines temporal offsets and rotational extrinsics during operation. We extend the M3DGR benchmark with simulation trajectories and evaluate more than 60 open-source SLAM systems on M3DGR, M2DGR-Plus, KAIST, GrandTour, and MARS-LVIG. The results show competitive accuracy across wheeled, legged, and aerial platforms under long-duration and high-speed operation, degradation, and calibration perturbation, improving localization availability for road-level autonomy, campus and warehouse mobility, and low-altitude aerial inspection. To benefit the industrial and academic community, we will release source code and datasets upon paper acceptance.
### Title:
          RogueRover: Autonomous Rogue Device Localization for Incident Response
 - **Authors:** Priyanka Prakash Surve, Asaf Shabtai, Yuval Elovici
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physically localizing unauthorized wireless devices remains a critical bottleneck in cyber-physical security operations, where rogue access points can provide entry points for lateral movement and persistent compromise. While such devices can often be detected through network-side mechanisms, determining their physical location typically requires dense sensing infrastructure, site-specific RF fingerprinting, or manual inspection, limiting timely incident response. We investigate whether a single commodity robot can autonomously detect and localize rogue wireless devices under zero-configuration constraints, without RF fingerprinting, pre-installed sensors, or site calibration. We present RogueRover, an end-to-end system in which a quadruped robot autonomously patrols, collects spatially labeled RSSI measurements via a standard 802.11 interface, and estimates device locations offline. We evaluate the system across 11 patrol runs in a real indoor environment, with 6 rogue devices deployed under heterogeneous propagation conditions. Across 62 AP-patrol sessions, RogueRover achieves a median single-patrol localization error of 1.62 m without prior RF knowledge. Under multi-run aggregation, five of six devices are localized within 1 m. A blind trial validates the full pipeline, correctly identifying rogue devices among 73 observed BSSIDs and localizing them with errors of 0.34 m and 1.84 m. Across environments, simple weighted-centroid estimators perform comparably to, or better than, parametric path-loss models, indicating that measurement coverage from autonomous patrols is the primary determinant of localization accuracy under zero-prior constraints. Our results demonstrate that infrastructure-free, autonomous localization is feasible in practice, enabling rapid physical incident response in cyber-physical environments without additional sensing infrastructure.
### Title:
          NoduLoCC2026: Lung Nodule Localization and Classification Contest from Chest X-Ray Images
 - **Authors:** Adnan Mustafic, Halim Benhabiles, Adnane Cabani, Kristhian André Oliveira Aguilar, Romain Amigon, Clément Bardin, Chiara Bentifece, Marin Boehm, Kévin Bouchard, Laura Burattini, Diedre Carmo, Fahima Idiri, Matthis Lahargoue, Ilaria Marcantoni, Hicham Messaoudi, Cyril Meyer, Farid Meziane, Léon Morales, Letícia Rittner, Agnese Sbrollini, Léonard Zipper, Karim Hammoudi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose NoduLoCC2026, a challenge on lung nodule detection and localization in chest X-ray images. We have provided a dataset for both tasks and received submissions from 5 international teams. The participating teams' solutions are presented in this work along with results on an external dataset used for testing. Proposed methods show good performance on the classification task. The best method shows a balanced accuracy score of 0.72 and AUC-ROC of 0.79. We highlight the limitations of current approaches for the localization task, with the best approach having predicted the correct number of nodules on 53\% of the test images with a median distance of 12.83mm, showing that it is a more challenging task than the first one. The challenge website is available via this https URL.
### Title:
          Sea-Scan: High-Accuracy, ML-based Dark Vessel Detection and Localisation via Weakly Supervised DAS Monitoring
 - **Authors:** Tian Tian, Agastya Raj, Lara Flanagan, John Kennedy, Marco Ruffini
 - **Subjects:** Subjects:
Sound (cs.SD); Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present an ML-based vessel detection and localization system, trained with weak supervision from imperfect AIS labels, that achieves a 97.8% detection rate at 1.98% false-trigger rate, successfully identifies dark-vessel events from unlabeled data.
### Title:
          Mind the Noise: Sensitivity of Transformer-based Interaction-Aware Trajectory Prediction Models to Noisy Data
 - **Authors:** Shahab Salehi, Luca Lusvarghi, Miguel Sepulcre, Javier Gozalvez
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Trajectory prediction allows autonomous vehicles to anticipate the future behavior of surrounding objects (or agents) and, accordingly, maximize the safety and efficiency of their driving. State-of-the-art Transformed-based interaction-aware trajectory prediction models, which rely on attention mechanisms to capture multi-agent interactions and maximize prediction accuracy, are commonly trained and evaluated on long-range high-quality datasets. These datasets are typically obtained by aggregating data from multiple vehicles or drones and removing any object detection or tracking noise offline. Yet, information about a surrounding object's state (its position, speed, heading) is far from being noiseless in real-world deployments. Object state estimation is affected by perception uncertainties and localization errors that can be particularly large for objects received via Vehicle-to-Everything (V2X) communications. In this paper, we analyze the impact of noisy object state information on the trajectory prediction accuracy of a state-of-the-art Transformer-based interaction-aware trajectory prediction model. Our study demonstrates that trajectory prediction accuracy can rapidly deteriorate as the noise intensity increases. Numerical results show that the prediction accuracy can reduce by a 1.3x factor under small noise levels and by as much as a 3.9x factor under the highest (yet realistic) noise conditions. These findings reveal the strong sensitivity of trajectory prediction models to noisy data, underscoring the need for more realistic training and evaluation datasets as well as noise mitigation strategies.
### Title:
          Factual Retrieval in LLMs Is a Redundant, Distributed and Non-Contiguous Process
 - **Authors:** Hail Hochman, Natalie Shapira, Yoav Goldberg
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) store and recall factual knowledge, yet the precise mechanism of how entity representations are transformed to enable specific attribute retrieval remains underexplored. In this work, we investigate this mechanism through the lens of an "attribute-computation path"-a sequence of computational steps over the entity representation required to elicit a target attribute. We then propose an iterative patching protocol to identify a minimal subset of layers necessary for this computation. Applying our method to LLaMA 3.1 8B and Qwen3 8B, we find that these paths are non-contiguous, often skipping layers, and that models possess multiple, functionally-equivalent paths for the same entity and fact, highlighting a high degree of redundancy in attribute computation. This implies that knowledge computation is highly distributed, potentially explaining the localization-editing mismatch and suggesting that knowledge storage and retrieval in LLMs is far from being well understood.
### Title:
          MedHal-Loc: Are "Explainable-by-Architecture" Medical Hallucination Detectors Faithful Localizers? A Localization Benchmark
 - **Authors:** Minmin Chen, Daojian Lu, Yining Dai, Jvyu Cai, Fengdan Chen
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Detecting hallucinations in clinical text is increasingly framed as an explainability problem: systems should not merely flag an unreliable response but point to the offending span. Architectures built around knowledge-graph (KG) triple decomposition are marketed for exactly this auditability, yet their localization ability is typically assumed rather than measured. We introduce MedHal-Loc, a benchmark and metric for localization faithfulness -- whether a detector's top-ranked error unit actually overlaps the erroneous span. The controlled subset comprises 300 PubMedQA-derived statements with single, span-level errors injected across four localizable types (entity substitution, relation error, mechanism misattribution, invention), yielding gold spans by construction; a complementary natural subset documents that real hallucinations are dominated by diffuse conclusion-flips that resist span localization (a human expert accepted 1/18 candidate spans). Evaluating four fine-grained paradigms, we find that NLI-per-clause, consistency-per-sentence, and the dedicated span detector FAVA all localize well above chance, whereas an elaborate KG-triple pipeline localizes no better than chance (+3.3pp, n.s.), bottlenecked by ~59% entity-extraction coverage -- despite competitive detection F1 (0.609). Detection competence does not imply faithful localization; architectural explainability must be validated, not presumed.
### Title:
          Rubric-as-Experts: Case-Specific MQM Rubrics for Translation Quality Evaluation
 - **Authors:** Weilu Xu, Yunzhi Shen, Xinye Wang, Ranfei Dang, Shujian Huang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) have shown strong potential in fine-grained translation quality evaluation (QE), yet existing MQM-based approaches typically rely on fixed rubric configurations shared across all translation samples. However, translation instances often differ substantially in error complexity, ambiguity, and required evaluation granularity, making static rubric allocation suboptimal for span-level error detection. We find that larger MQM subtype spaces improve error coverage but also introduce more false positives, while different translation instances prefer different rubric granularities, suggesting that evaluation spaces should be allocated dynamically for each case. Motivated by these observations, we propose a case-specific dynamic rubric framework that adaptively constructs MQM evaluation spaces for individual translation instances. Unlike fully free-form rubric generation methods, our framework remains grounded in the predefined MQM taxonomy while dynamically selecting suitable subtype spaces and evaluation granularity for different cases. Experiments on WMT span-level QE benchmarks across multiple model scales demonstrate that the proposed framework consistently improves MCC and produces cleaner span-level error localization compared with static rubric settings. Our results suggest that combining structured MQM rubrics with case-specific adaptive allocation is an effective strategy for fine-grained LLM-based translation evaluation.
### Title:
          Cross-Modal Corroboration for Annotation-Free Wildlife Monitoring
 - **Authors:** Bharath Pillai, Varun Viswapriyan, Christopher Stewart, Tanya Berger-Wolf, Jenna Kline
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling wildlife monitoring for real-world conservation deployments requires automated analysis of smart sensors that operate under severe annotation scarcity. We propose leveraging expert knowledge of species activity patterns as an annotation-free validation signal for multimodal monitoring pipelines. We operationalize agreement as the alignment of independently derived hourly activity curves both with each other and with published behavioral priors-a three-way convergence that rules out shared-data confounds and dataset-internal correlation as alternative explanations. Our vision pipeline combines zero-shot species detection via BioCLIP 2, sliced inference to handle deployment-constrained camera positioning, and geometry-based geographic localization from camera trap imagery. Our acoustic pipeline detects species vocalizations via a fine-tuned classifier. We validate the pipeline on a breeding herd of Milu deer and demonstrate that both modalities independently recover activity patterns consistent with known deer behavioral ecology with minimal manual annotation. The framework applies to species detectable in both visual and acoustic modalities for which behavioral priors are documented in the literature, suggesting a practical path toward self-validating wildlife-monitoring pipelines at conservation scale.
### Title:
          HPP: Hierarchical Programmatic Probing for Long Video Understanding by Decoupling Perception and Reasoning
 - **Authors:** Awais Rauf, Ahmed Hasssan, Greg Slabaugh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding long videos requires fine-grained perception and multi-step, higher-order reasoning over complex, long-range spatio-temporal dynamics. Vision-language models (VLMs) encode video frames into visual tokens and attempt to perform both perception and multi-step planning latently, within a single forward pass. This coupled formulation, however, is bottlenecked by the LLM's limited capacity to discover and execute multi-step strategies in its latent representations. To address this bottleneck, we propose Hierarchical Programmatic Probing (HPP), a framework that decouples semantic perception from higher-order temporal reasoning by reformulating long video understanding as iterative, programmatic exploration of a hierarchically segmented video. Specifically, a coding-capable LLM plans and executes a multi-step strategy in an interactive coding environment, probing the video for information and invoking a VLM for localized perception on demand. To make probing tractable over long videos, we introduce three components: information-density-aware hierarchical segmentation, late-interaction semantic retrieval, and structured probing functions for coarse-to-fine temporal localization. We validate HPP on LongVideoBench, which requires both fine-grained perception and long-range relational reasoning, and show that decoupling the two via iterative programmatic probing yields substantial gains. Further results on EgoSchema, VideoMME, and MLVU demonstrate the effectiveness of our approach across diverse long-video benchmarks.
### Title:
          A11YRepair: Bridging Web Accessibility Barriers via Knowledge-Enhanced Divide-and-Conquer Repair
 - **Authors:** Kai Huang, Ling Zhu, Jian Zhang, Xiaofei Xie, Chunyang Chen
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Web accessibility (A11Y), which ensures web content is perceivable and usable for users with disabilities, is a critical requirement for modern web applications. Yet existing tooling overwhelmingly focuses on detecting A11Y violations rather than repairing them. Automated program repair (APR) techniques appear promising for this setting, but our study shows that state-of-the-art APR systems perform poorly when applied to real-world A11Y violations. Unlike conventional sparse-bug scenarios, web A11Y issues often manifest as multiple structurally related violations per page, requiring coordinated edits across multiple files. Existing repair systems fail to manage this multi-fault scale, as they handle each bug individually without considering their relationships or incorporating domain rules such as the Web Content Accessibility Guidelines (WCAG). We propose A11YRepair, an LLM-based framework for web A11Y repair. A11YRepair introduces a divide-and-conquer workflow that first clusters violations requiring coordinated edits to reduce redundant localization, and then decomposes each cluster by root cause so the LLM can generate focused and consistent patches. The framework further incorporates WCAG-driven knowledge to strengthen domain awareness during both fault localization and patch synthesis. To support systematic evaluation, we construct A11YBench, a benchmark of 60 real-world web projects collected from GitHub. Experimental results show that A11YRepair achieves higher repair effectiveness and lower cost than state-of-the-art baselines, and ablation studies confirm the importance of its divide-and-conquer design and selective domain knowledge integration. Specifically, patches generated by A11YRepair have been merged into open-source projects from Google, Microsoft, Facebook, IBM, K8s, Docker, and Alibaba, demonstrating its practical value.
### Title:
          CoSA: Correlation-Guided Change Attention with Learnable Residual Gating for Remote Sensing Change Detection
 - **Authors:** Abdirashid Omar, Jonghyuk Park
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote sensing change detection (CD) from bi-temporal imagery is critical for applications such as urban monitoring, disaster assessment, and environmental management, yet robust localization remains challenging under sparse changes, noisy labels, and appearance variations. In this paper, we propose Context Sampling Attention (CoSA), a lightweight decoder-side refinement module that explicitly leverages bi-temporal feature correlation as a control signal for adaptive change-aware feature enhancement. This differs from conventional attention mechanisms that rely on implicit feature weighting without explicit temporal control. In the implemented FC-Siam setting, CoSA computes normalized same-location cross-correlation between paired decoder features, converts low correlation into a change gate, and injects the resulting gated residual at native 1/8 and 1/16 feature scales through learnable residual scaling. This design enables effective discrimination between stable and ambiguous regions without relying on computationally expensive global attention. Extensive experiments on four benchmark datasets (LEVIR-CD, S2Looking, DSIFN, and CLCD) demonstrate consistent improvements over strong baselines, achieving 1.5-2.6% gains in changed-class F1 while introducing negligible parameter overhead. Ablation studies confirm that multiscale placement and learnable residual gating are both important for peak performance. These results indicate that CoSA establishes a practical and effective refinement paradigm for enhancing temporal discriminability in Siamese change detection frameworks.
### Title:
          Holmes: Multimodal Agentic Diagnosis for Mixed-Language Mobile Crashes at Industrial Scale
 - **Authors:** Jia Li, Wenyuan Ma, Ting Peng, Haibin Zheng, Yuetang Deng
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diagnosing mobile crashes in ultra-large-scale industrial applications is a formidable challenge due to the sheer volume of code, the complexity of mixed-language environments, and the inability to reproduce failures locally. Traditional static analysis struggles with scalability, while existing LLM-based agents often rely on reproducible environments unavailable in post-mortem scenarios. We present Holmes, a multi-agent system that automates root cause analysis by synthesizing multimodal runtime signals--stack traces, logs, and thread states--to reconstruct failure contexts without reproduction. Holmes introduces a hierarchical Retrieve-Explore-Reason architecture that leverages low-level artifacts (e.g., registers, assembly) to bridge the semantic gap between open-source business logic and closed-source system frameworks. By dynamically compressing the search space using runtime clues, Holmes precisely navigates 70-million-line codebases to identify non-local defects. Evaluated on real-world crashes from WeChat, Holmes achieves 87.6% accuracy in function-level fault localization and reduces average investigation time by over 98% (to ~77 seconds), demonstrating its effectiveness in transforming labor-intensive debugging into an efficient verification workflow.
### Title:
          Look Before You Zoom: Adaptive Routing for the Resolution-Context Trade-off in Visual RAG
 - **Authors:** Oanh N. Tran, Thanh Quoc Hung Le, Oscar Chew, Kuan-Hao Huang, Khoa D. Doan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language Models (VLMs) struggle as query-relevant objects become smaller. To address this, recent training-free approaches dynamically retrieve and zoom into local image regions. However, we show that indiscriminately applying retrieval ignores a critical vulnerability: the resolution-context trade-off. Patch-based zooming recovers details for small targets, but can split large objects and destroy global spatial context; attention-based retrieval better preserves large objects, but remains less reliable on tiny details; and global perception is often fastest when retrieval is unnecessary. Motivated by these failure modes, we introduce ViRGo (Visual Retrieval or Global Perception), a lightweight framework that formulates visual retrieval as an adaptive routing problem. ViRGo estimates object scale from the VLM's intrinsic localization heads during the initial forward pass and combines it with semantic token confidence to select between global perception, patch-based retrieval, and attention-based retrieval with minimal additional computation. Experiments across multiple VQA benchmarks and object-size groups show that ViRGo improves the accuracy-efficiency trade-off: it matches patch retrieval on small details, leverages attention-based retrieval for larger objects, and reduces inference time by routing to the global baseline when zooming is unnecessary.
### Title:
          GeoFlow-SLAM++: A Robust Multi-Camera Visual-Inertial SLAM System with Relocalization
 - **Authors:** Wei Fen, Tingyang Xiao, Liu Liu, Xiaolin Zhou, Zhizhong Su
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular and RGB-D visual-inertial SLAM systems remain susceptible to limited field of view, sensor-specific failure modes, and unreliable cross-session relocalization. To address these issues, we present GeoFlow-SLAM++, a tightly coupled multi-camera visual-inertial SLAM system that extends GeoFlow-SLAM from a single RGB-D sensor to a calibrated multi-camera rig with a unified body-centric formulation. Within this multi-camera framework, GeoFlow-SLAM++ supports two interchangeable visual front-ends: a conventional ORB front-end and a neural network feature (NN-Feature) front-end built on SuperPoint and LightGlue. The system unifies tracking, mapping, and relocalization on a shared body state, and combines multi-camera reprojection constraints, IMU pre-integration, cross-view place recognition, and dual-stream optical flow/NN-Feature tracking for robust localization. As an optional extension, the system can further incorporate cross-view-consistent pseudo-depth predictions from RGB images as auxiliary geometric constraints. We evaluate GeoFlow-SLAM++ on EuRoC, OpenLORIS, TUM, Hilti, and a self-collected handheld multi-camera dataset. Results show that the NN-Feature front-end improves robustness in appearance-challenging scenarios, the multi-camera formulation achieves competitive localization accuracy on Hilti, and the unified cross-view relocalization design reaches LiDAR-comparable performance on the handheld dataset.
### Title:
          Cross-View Yaw Estimation in Location Uncertainty with Line-Aligning Yaw Scoring
 - **Authors:** Taeho Kang, Nairan Zhang, Yelin Kim, Yujiao Shi, Youngki Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate yaw estimation is a bottleneck in cross-view localization between ground view and Bird's Eye View (BEV). Existing methods couple yaw with translation and rely on height or projection assumptions that degrade under large yaw ambiguity. We disentangle yaw from location accuracy and introduce LAYS, a radially invariant line-consensus voting method. By exploiting the radial invariance of our formulation, we achieve sub-degree yaw precision via 3D voting over all candidate poses, while eliminating the need for accurate location. Our key observation is that a ground-image column matched to BEV pixels induces the same yaw across all camera positions along the radial direction of the pixels. LAYS matches BEV pixels to ground columns using feature similarity and accumulates the induced yaw votes into discrete 3D bins, where correct correspondences along the radial line concentrate into a sharp peak for the correct yaw. Experiments on Mapillary, Ford, KITTI, and VIGOR show significant gains under unknown yaw, particularly for normal FoV with unknown yaw (+28$\sim$45\%p), and using LAYS as a yaw prior improves downstream 3-DoF localization.
### Title:
          Resolving Multi-Target Association in OFDM-based ISAC via Vision-aided Multi-Modal Learning
 - **Authors:** Meng Hua, Chenghong Bian, Deniz Gunduz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Orthogonal frequency division multiplexing (OFDM)-based integrated sensing and communication (ISAC) systems commonly extract target parameters by peak-searching a delay-Doppler map (DDM) constructed from reflected pilots. In multi-target scenarios, this results in ambiguity: the DDM does not reveal which physical target produced which peak, and two targets within the same delay-Doppler resolution cell cannot be separated. We propose a vision-assisted OFDM-ISAC framework that resolves both limitations by fusing wireless and visual modalities. The transmitter encodes an onboard street-view image with deep joint source-channel coding (DeepJSCC) and transmits it over the same OFDM waveform used for sensing; the receiver reconstructs the image, runs a fine-tuned YOLOv5 detector and fuses the resulting per-target features (bounding-box coordinates and class labels) with the DDM and transmitter-receiver geometry through a learned multi-modal network. To stabilize training of the high dimensional delay and Doppler classifiers, we introduce a Kullback Leibler loss against triangular soft labels centered on the ground-truth bin. On a Blender-rendered vehicular testbed, the proposed framework achieves a 16 cm localization root mean square error (RMSE) and a 10.8 ns delay RMSE. An ablation study confirms that removing the visual modality causes a 60x degradation in localization. These results highlight the potential of vision to overcome the data-association and resolution limits of single-modality ISAC.
### Title:
          Efficient Document Tampering Localization with Multi-Level Discrepancy Features and Unified DCT-Quantization Embedding
 - **Authors:** Mohamed Dhouib, Ye Zhu, Sonia Vanier, Aymen Shabou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localizing document tampering is extremely challenging, as manipulations are crafted to appear visually consistent and often leave only subtle traces that are nearly invisible to the human eye. In prior work, evaluation has been largely dominated by synthetic benchmarks that closely match the training distribution, and methods have shown steady progress under this setting. However, these gains often translate poorly to human-made forgeries and to cross-domain evaluation, where both the source documents and the tampering pipeline can change, leading to a distribution shift. In addition, since the introduction of the Frequency Perception Head for the discrete cosine transform (DCT) modality, it has become a standard choice, and subsequent work has largely focused on downstream modules and fusion strategies rather than revisiting the backbone itself. To help close this gap in cross-domain performance and improve the DCT backbone design, we propose \textbf{DiffNet}, a relatively simple yet effective RGB--DCT early-fusion architecture driven by two key design choices. First, to ensure that the decoder aggregates multi-scale inconsistency evidence rather than operating on raw, content-heavy activations, we apply a lightweight multi-level discrepancy transformation at the output of each backbone stage, replacing features with magnitude-only responses to learned zero-sum filters. Second, we design an efficient DCT-domain backbone that relies on a lightweight frequency-index-aware DCT--quantization joint embedding. Our approach achieves state-of-the-art performance on cross-domain and human-made document tampering localization, outperforming prior methods by around 30\%, with up to $7\times$ higher throughput than the previous best model.
### Title:
          First-Token Broadcasters: Mechanistic Origins of Language Identity and Distributed Robustness in Transformers
 - **Authors:** Arjun Pillai, Christian Hoang, Anjelo Jann Laroza
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Why do multilingual language models sometimes generate in the wrong language, and why is this so hard to fix? We introduce Language Identity Head Ablation (LIHA), a causal intervention that zeros each attention head individually and measures the resulting language switch rate across a parallel dataset of 2,700 prompt-language pairs spanning seven languages. Applied to GPT-2, LIHA identifies a small set of first-token broadcaster heads - led by L6H1 (switch rate 0.32, 3.23 $\sigma$ above the population mean) - that attend persistently to the first prompt token, propagating its language signal throughout generation. Compensatory redistribution when heads are ablated is statistically significant (p < $10^{-5}$) and follows a directional, hierarchical pattern: compensation always recruits heads in layers above the ablated head, suggesting a feedforward cascade rather than global diffusion. To probe how training regime shapes these circuits, we apply LIHA to a controlled pair - Qwen2.5-1.5B-Base and Qwen2.5-1.5B-Instruct - identical in architecture and size, differing only in training. The base model is nearly flat (max SR=0.016, 200/336 heads at SR=0.0); the instruct model concentrates causal influence sharply at layer 0, led by L0H5 (SR=0.224, 8.93 $\sigma$ above mean), with all other layers near zero. This controlled comparison provides direct causal evidence that instruction tuning reorganizes language identity circuits toward early-layer localization. Extended experiments with Chinese and Russian confirm that first-token broadcasting is script-specific in GPT-2, with non-Latin languages handled at layer 0 - the same locus as the instruction-tuned model. Code and data will be released upon publication.
### Title:
          Reference-Free Assessment of Physical Consistency in World Model-based Video Generation
 - **Authors:** Yun Oh, Sukmin Yun
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce reference-free measures for evaluating the physical consistency of generated videos, combining relative and absolute approaches to assess fidelity. Although tools like WorldGym or WorldEval enable robotic simulation via video generation, physical fidelity gaps often prevent these environments from accurately reproducing real-world task success rates of VLA models. Unlike existing evaluation methods, which require costly human voting (Elo) or unavailable ground-truth references (FVD), our approach utilizes DROID-SLAM and SEA-RAFT to quantify physical inconsistencies, motivated by WorldScore. Videos filtered using our relative consistency assessment show an improvement in task success rates of over 8%, effectively narrowing the simulation-to-reality gap. Furthermore, our absolute assessment enables spatio-temporal localization, providing visualization of when and where physical artifacts occur.
### Title:
          Code Isn't Memory: A Structural Codebase Index Inside a Coding Agent
 - **Authors:** Ishaan Bhola, Adithyan Krishnan, Sravanth Kurmala, Mukunda NS
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Coding agents now interleave LLMs with retrieval over the working repository, and retrieval implementations vary widely across deployed harnesses. Inside a fixed coding-agent harness on a fixed model, does adding a structural codebase index actually change cost or resolve? We ran three arms (the harness with the index, the same harness without it, and an agentic-grep comparator) on SWE-PolyBench Verified and SWE-bench Pro with Claude Opus 4.7 held fixed throughout, across three seeds, inside a leak-audited per-task sandbox. The within-harness ablation produces a large localization gain and a statistically separated resolve gain, with no cost penalty per cell and lower cost per solve. The cross-harness check shows that the index does not regress against an agentic-grep baseline on resolve or localization, again at no cost penalty. We release the per-cell exclusion ledger, the leak-audit script, the localization extractor, and the results database. The deployment question for a structural codebase index is thus not whether it is too expensive to run (across seeds, the index lands at a lower $/solved than agentic grep) but whether the workload includes multi-file changes where structural ranking pays off.
### Title:
          MAPS: Multi-Anchor Projection Similarity for Joint Vision-Language Geo-Localization
 - **Authors:** Yutong Hu, Siyuan Tan, Shaocheng Yan, Pengcheng Shi, Qingwu Hu, Jiayuan Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humans localize places by integrating perceptual cues from vision with semantic reasoning from language, forming a scene understanding that is both intuitive and structured. Although existing geo-localization models have made substantial progress in cross-view and cross-modal settings, they are largely built upon point-to-point alignment, which is insufficient for joint vision-language queries. In such queries, visual and textual cues do not simply act as independent references, but jointly define a semantic subspace for locating the target. In this paper, we formulate vision-language geo-localization (VLGL) with joint image-text queries as a multi-anchor geometric alignment problem and propose a unified framework for this setting. To realize this formulation, we propose Multi-Anchor Projection Similarity (MAPS), a new metric which constructs an anchor plane from visual and textual query features in a high-dimensional space and measures similarity by the projection length of the target feature onto this plane. Unlike cosine similarity which evaluates isolated pairwise relations, MAPS captures the geometric consistency between the target feature and the joint query subspace, providing a more discriminative ranking criterion during retrieval. To make the learned representation consistent with this geometry, we further introduce a MAPS-based contrastive loss that drives target features toward the corresponding anchor plane. The proposed framework, similarity metric, and training objective jointly yield state-of-the-art performance in VLGL.
### Title:
          Non-Uniform L2 Cache Latency Across the Streaming Multiprocessors of an NVIDIA L40
 - **Authors:** Faruk Alpay, Baris Basaran
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The NVIDIA L40 exposes a 96 MiB L2 cache usually modeled as one uniform pool with a single hit latency. We show this is wrong at the granularity a kernel sees: L2-hit latency depends strongly and reproducibly on which physical streaming multiprocessor (SM) issues the load. A turn-serialized, %smid-resolved probe maps the hit latency across all 142 SMs in one launch; it is not a constant near 279 cycles but spans 222-339 cycles (a 52% range), with per-repetition noise below 0.01 cycles. An additive model $L = \mu + a(\mathrm{sm}) + b(\mathrm{slice})$ explains $R^2 = 0.87$ (0.98 with one rank-1 term), and the SM term is two-fold symmetric (two halves of 72 SMs at correlation $r = 0.999$), following the AD102 GPC layout. Independent access patterns agree per SM at $r = 1.000$, so the effect is physical. The same probe on a Blackwell RTX 5090 shows it generalizes, while the per-die pattern is device-specific. Read as a fingerprint, a single user-level probe identifies the SM within a device at 92%, and two physically identical L40s are separated at 100% despite near-identical mean latency (per-SM map $r = 0.63$): a per-die hardware identity, not a clock artifact. This is a self-localization and fingerprinting primitive: a kernel reads its own placement and device, not a victim's, and extracts no secret data. The map is stable, unchanged after an hour at full utilization on both devices. As a consequence, distributing latency-bound work by the map cuts makespan by up to 11%. Single-thread capacity, line-tag, prefetch-modifier, and persisting-L2 results appear as controls. The artifact contains seeds, raw observations, the trained model, and regeneration scripts.
### Title:
          LoCC: Detection and Localization of Lip-Syncing Deepfakes via Counterfactual Frame Consistency
 - **Authors:** Soumyya Kanti Datta, Shan Jia, Siwei Lyu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Lip-syncing deepfakes are among the most challenging forms of manipulated media because their artifacts are localized almost exclusively to the mouth region and evolve dynamically over time. Detecting such deepfakes requires precise temporal and spatial modeling of lip motion. In this paper, we propose LoCC, a novel detection framework that performs fine-grained detection and localization of lip-syncing deepfakes at both segment and frame levels. Unlike prior approaches that analyze videos holistically, our method evaluates whether each frame aligns with a counterfactual estimate generated from its temporal neighbors. Real videos exhibit strong and stable consistency, whereas lip-sync deepfakes introduce localized inconsistencies. Following a teacher-student learning paradigm, our model effectively captures these frame-level discrepancies and achieves superior performance over state-of-the-art methods on multiple benchmark lip-syncing deepfake datasets, including LAV-DF, AVDF1M, FakeAVCeleb, and KODF, and generalizes well across compression levels and datasets.
### Title:
          Machine-knittable, Magnetically-Plug-n-Play E-Textile Prototyping
 - **Authors:** Yifan Li, Ryo Takahashi, Wakako Yukita, Irmandy Wicaksono, Kanata Matsutani, Yuhiro Iwamoto, Sunghoon Lee, Tomoyuki Yokota, Takao Someya, Yoshihiro Kawahara
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electronic textiles (e-textiles) integrated with wearable sensors are essential for daily motion monitoring and long-term physiological sensing. For example, capturing optimal kinematic or bio-signals requires aligning sensors with specific anatomical parts, which vary significantly across individuals and application scenarios. This necessity for personalization makes e-textile prototyping inherently iterative, however current fabrication methods, such as manual conductive stitching, rely on permanent bonds that restrict rapid adjustment. This paper introduces Plug-n-play e-knit, a machine-knittable e-textile prototyping platform that enables repeatable, quick adjustment of sensor positions across garments. First, to cover the large area of the textile for prototyping, we use industrial digital knitting of conductive yarn to integrate power and communication buses directly into the large-scale textile. Then, to ensure plug-n-play attachment to the textile, we employ soft-magnetic connectors that enable sensors to be repeatedly plugged into the wiring without damaging the fabric. Furthermore, our LED-positioning system enables the automatic identification and localization of each sensor node. We demonstrate the platform's capabilities through forearm movement calibration and position-aware temperature mapping.
### Title:
          Homographic Navigation: Geometry-Driven Camera Guidance for Deterministic Planar Capture
 - **Authors:** Dominik Kroupa, Marek Vaško, Muh Yuzril Ihza Baharuddin, Adam Herout
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present homographic navigation, a geometry-centric framework for guiding camera acquisition toward precise capture of planar regions. Rather than treating homography as an output, we use it as an organizing variable that unifies learning, alignment, and evaluation. From a single annotated reference image, we generate unlimited synthetic training data via homographic augmentation and train a single-shot model for joint recognition and localization of multiple artifacts (physical objects with a rectangular planar target) through sparse keypoint prediction. To address precision under limited model input resolution, we introduce a two-pass inference scheme with global detection followed by localized refinement, and a Stable Warp training strategy that significantly improves accuracy, particularly in the high-precision regime. The model also predicts confidence estimates per predicted keypoint and per the whole sample. Experimental results demonstrate that accurate planar alignment can be achieved from minimal supervision, providing a foundation for geometry-driven camera guidance and future learning from in-the-wild video data.
### Title:
          Fursee: Hybrid YOLO-DINOv3 Framework for Fursuit Identity Retrieval and Clustering
 - **Authors:** Jundi Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Global furry conventions produce massive fursuit photographs, while manual sorting brings heavy labor costs and calls for automatic identity retrieval and clustering solutions. General multimodal models lack dedicated optimization for complex fursuit scenes, and no public benchmark dataset exists for this task. To fill this gap, we build a specialized fursuit image dataset and present a three-stage hybrid pipeline Fursee for fursuit identity retrieval and clustering. First, YOLO detects and crops high-resolution fursuit head patches to improve localization of small and overlapping targets. Second, ArcFace optimizes DINOv3 embeddings to enlarge angular separation between different identities on the feature hypersphere. Third, DBSCAN performs unsupervised clustering, with silhouette-coefficient-driven search automatically selecting optimal hyperparameters rather than fixed manual radius. Retrieval and clustering experiments verify that our pipeline outperforms mainstream multimodal models including GPT5.5, Claude Opus 4.8 and Qwen3.7-Plus on all evaluation metrics, achieving competitive performance for fursuit head retrieval and grouping.
### Title:
          Rethinking Prototype-based Similarity Learning for Few-Shot Object Detection
 - **Authors:** KunHo Heo, Seungjae kim, Wongyu Lee, SuYeon Kim, MyeongAh Cho
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Few-shot object detection aims to detect novel object categories from only a few labeled examples, avoiding costly large-scale annotation. Recent prototype-based similarity learning approaches enable training-free adaptation by matching query features with class prototypes. However, they suffer from two fundamental limitations: (i) class confusion arising from inter-class similarity margin collapse, and (ii) insufficient visual cues for precise localization, as similarity scores capture only class-level semantic affinity while providing limited spatial information. To address these issues, we introduce two complementary components. Text-Anchored Semantic Mask (TSMa) leverages class-level text features as semantic anchors to identify semantically aligned channels through channel-wise interaction between visual and text features. By suppressing style-induced spurious responses and emphasizing class-intrinsic signals, TSMa enlarges inter-class similarity margins and mitigates class confusion. We further propose Stage-Aligned Hierarchical Autoregressive Regression (SHARe), which reformulates localization as a hierarchical autoregressive process that progressively refines bounding boxes across multiple stages. SHARe leverages the layer-wise characteristics of ViT representations by aligning feature abstraction levels with regression stages: deeper layers guide early coarse localization, while shallower layers rich in edge and texture cues refine spatial details in later stages. Experiments on COCO demonstrate a new state of the art, outperforming the previous best by +10.1 nAP, with extensive analysis validating each component. The code is available at this https URL.
### Title:
          P-JEPA: Procedural Video Representation Learning via Joint Embedding Predictive Architecture
 - **Authors:** Felix Tristram, Stefano Gasperini, Benjamin Killeen, Marcel Walch, Christian Benz, Nassir Navab, Ghazal Ghazaei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The increasing maturity of embodied AI platforms has driven a growing interest in procedural video representation learning to support intelligent assistance systems for complex, multi-step tasks. Leveraging large-scale latent predictive training, video foundation models capture video dynamics, enabling downstream tasks such as activity understanding, spatiotemporal localization, and predictive control. However, procedural videos include actions with long-range dependencies that these models do not support, due to the quadratic complexity of self-attention. Distinct actions, for example, may be visually similar despite appearing at different points in the procedure, such as turning the stove on versus off. Here, we propose a backbone-agnostic approach that learns long-duration video representations by reducing the problem to a dense, frame-aligned action space and predicting pooled masked latent vectors. This approach allows our Procedural Joint Embedding Predictive Architecture (P-JEPA) to ingest videos over 30 minutes long, enabling effective long-form understanding of procedural steps. We evaluate P-JEPA using features extracted with VJEPA2.1, TSM, and I3D over the EgoExo4D, EgoProceL, and Assembly101 datasets, finding that it consistently improves linear separability, streaming inference, and temporal action segmentation performance, achieving state-of-the-art results on EgoExo4D fine-grained action classification while using an order of magnitude fewer parameters than LLM-based methods and running in real time.
### Title:
          Flow6D: Discrete-to-Continuous Flow Matching for Efficient and Accurate Category-Level 6D Pose Estimation
 - **Authors:** Mingyu Mei, Li Zhang, Zibo Dai, Han Sun, Xinyue Zhao, Huiliang Shen, Zaixing He
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 6D pose estimation is a key task in computer vision and embodied AI, widely used in robotic manipulation, augmented reality, etc. Existing methods directly regress in a high-dimensional continuous space, facing two key challenges in category-level pose estimation: limited accuracy due to noise and local optima, and inefficient search over an infinite space that hinders real-time performance. This paper proposes Flow6D, a hierarchical flow matching framework with a two-stage discrete latent space localization-continuous pose regression strategy. Rotation and translation parameters are first discretized into bins, with a discrete flow matching model locking the latent space around the true pose to reduce search complexity. Then, by sampling in the latent space, a continuous flow matching model predicts local pose residuals to optimize the estimate and regress to an accurate pose. The framework also naturally extends to articulated objects, outperforming state-of-the-art methods on synthetic and real datasets with real-time inference at 70 FPS. Project website: this https URL.
### Title:
          UnBias-Plus: Detect, Explain, and Rewrite Bias
 - **Authors:** Ahmed Y. Radwan, Ahmed ElKady, Sindhuja Chaduvula, Mohamed Hafez, Amrit Krishnan, Shaina Raza
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bias in natural language remains a persistent challenge in both human-written and AI-generated content, affecting domains such as journalism, education, and AI research. Most existing detection methods identify only the presence of bias, with limited support for granular detection, interpretable explanations, neutral rewriting, and openly available trained models. We present UnBias-Plus, an open-source toolkit unifying (1) segment-level multi-class bias classification, (2) biased span localization, (3) neutral text rewriting, and (4) reasoning for each decision. Available via Python, CLI, REST API, and web interfaces, UnBias-Plus supports accessible bias analysis. The toolkit, source code, models, datasets, and documentation are publicly available.
### Title:
          A Reduced Order Model for Emergent Mechanics in Woven Systems
 - **Authors:** Anvay A. Pradhan, Evgueni T. Filipov, Talia Y. Moore
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Woven structures exhibit rich mechanical behaviors including anisotropic stiffness, shear-induced locking, and crimp interchange that emerge purely from the geometric arrangement of individual weavers rather than from constituent material properties. Existing models either homogenize these interactions or resolve them at prohibitive computational cost. We introduce a reduced-order model that bridges this gap by representing individual weaver interactions through a system of nodes and four physically interpretable stiffness elements capturing axial deformation, in-plane uncrimping, inter-weaver shear, and frictional slip. Eigenvalue analysis of the unit cell confirms that the lowest-energy deformation modes correspond directly to known weave-specific phenomena, and that each element is necessary for a complete kinematic and mechanistic description. Element stiffness parameters are calibrated against empirical three-point bending and shear data, achieving agreement within 5% across varied weaver widths and spacings. The validated model is then applied to demonstrate capabilities beyond the reach of continuum approaches including: the emergent Poisson's response arising from crimp interchange, stepwise force reduction during progressive weaver pullout, stress localization under three distinct tearing configurations, and programmable mechanical anisotropy through spatially graded weaver stiffness. The physical transparency and computational efficiency of the framework position it as a practical tool for the analysis and design of woven architected materials with programmable mechanical response.
## Keyword: transformer
### Title:
          NeuroShield: A Device-Agnostic Foundation Model for EEG Authentication
 - **Authors:** Matin Fallahi, Patricia Arias-Cabarcos, Thorsten Strufe
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A central challenge in EEG authentication is that models are typically tied to the acquisition settings in which they are trained. In particular, variations in headset hardware, channel layout, and signal duration create heterogeneous recordings that existing models are not designed to handle, causing each new headset or dataset to be treated as a separate model-development problem. This fragmentation limits multi-dataset learning, hinders knowledge transfer, and reduces model reusability. To address this limitation, we present NeuroShield, a reusable foundation model for EEG authentication that learns identity-discriminative embeddings from variable-channel and variable-length EEG recordings through a dual-stage transformer architecture. We pretrain NeuroShield on three public EEG datasets comprising 15{,}762 subjects and 28{,}116 sessions, and evaluate transfer on two unseen downstream datasets. Our evaluations show that, after fine-tuning, NeuroShield reduces equal error rate by 0.44--8.06 percentage points relative to the state of the art. NeuroShield further generalizes to segments longer than those seen during training and operates across channel layouts not encountered during pretraining. These results establish NeuroShield as a reusable and adaptable EEG identity encoder across heterogeneous recording settings. We release NeuroShield as open source to support reproducibility and community adoption.
### Title:
          MemoryVAM: Integrating Memory into Video Action Model for Robot Manipulation
 - **Authors:** Yuxin Jiang, Chang Yu, Yunuo Chen, Xiang Feng, Yin Yang, Nishank Gite, Chenfanfu Jiang
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video-world-model policies learn action-relevant representations by predicting future observations. However, they condition on only a short observation window, which renders long-horizon manipulation non-Markovian when the correct action depends on earlier events that are no longer visible. We present MemoryVAM, an episodic memory mechanism for video-world-model policies. We employ a Recap-Cue (RC) module, in which a Perceiver-based Recap Compressor maps per-frame CLIP embeddings into compact memory tokens, and a lightweight Cue Gate estimates task completion from memory and language. These tokens are injected into both the video backbone and the action decoder, aligning policy imagination with episode progress and conditioning actions on history. Our model trains the memory module with video prediction, a delta-reconstruction auxiliary loss, and episode-boundary supervision, requiring no per-frame progress labels. The same mechanism applies to UNet and Diffusion Transformer (DiT) backbones by changing only the cross-attention injection interface. On LIBERO-Mem, our model improves average success from 5% to 42.5%. On real robots, it achieves 78.3% success on counting tasks, 80.0% on spatial recall, and 75.0% on sequential tracking. Project page: this https URL
### Title:
          JPPD: Joint Prediction_Planning Diffusion with Differentiable Safety Guidance for Dynamic Obstacle Avoidance in Intelligent Transportation Systems
 - **Authors:** Jiahao Wu, Shengwen Yu
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Shared-space transportation operation requires low-speed autonomous platforms to navigate safely and efficiently among pedestrians, service robots, micromobility users, carts, and other road users. Most existing systems decompose this problem into trajectory prediction followed by motion planning, which creates one-way information flow: predicted participant futures influence the robot plan, but the selected robot plan cannot influence the predicted multi-agent evolution. This paper presents a joint prediction-planning diffusion framework that treats participant prediction and robot planning as a single conditional trajectory generation problem, where the model samples the future robot trajectory and all participant trajectories from one coupled distribution using a causal Transformer with cross-trajectory attention. To replace heuristic repulsive post-processing, the framework introduces differentiable safety potential guidance, a time-varying occupancy-probability potential whose gradient directly guides the joint sampler, and conditional flow matching is used to reduce inference steps while preserving multimodal trajectory diversity. The evaluation emphasizes shared-space operational effects, including near misses, blockage time, induced participant deviation, hard-braking events, and embedded latency, rather than treating average displacement error and final displacement error as the main result. Experiments in scenario-grounded simulation, naturalistic pedestrian replay, Isaac Sim validation, and ROS/Orin deployment show that joint sampling improves tail safety and runtime efficiency over a separated prediction-then-planning baseline.
### Title:
          Spatio-Temporal Wildfire Spread Prediction in Canada using a Video Swin-Hybrid-U-Net and Satellite Imagery
 - **Authors:** Maulik Srivastava, Esha Saha, Hao Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Background: Wildfires in Canada present increasing threats to ecosystems, communities, and infrastructure, demanding accurate forecasting tools to aid mitigation efforts. Existing models often lack scalability or fail to capture temporal dynamics effectively. Aims: This study aims to develop a deep learning framework tailored to Canadian wildfire spread prediction that captures spatio-temporal patterns in environmental data. Methods: We propose a U-Net architecture integrating a Video Swin Transformer encoder with a convolutional decoder to model three-day sequences of meteorological and environmental variables. Data are exclusively sourced from public repositories via Google Earth Engine, ensuring transparency and scalability. The model is trained and tested on a curated dataset of major Canadian wildfire events from 2014 to 2023. Key results: Our approach achieves strong predictive performance by effectively leveraging spatio-temporal attention to forecast next-day fire incidence maps. Conclusions: The model successfully captures complex wildfire dynamics unique to Canada's landscape and temporal variability. Implications: This framework paves the way for advanced spatio-temporal wildfire forecasting research and operational applications using publicly accessible datasets.
### Title:
          An approach with Visual and Tabular Mamba to multimodal medical data using Mixed Fusion
 - **Authors:** Matheus B. Rocha, Gustavo B. Dettogni, Renato A. Krohling
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This article presents a complementary approach for integrating multimodal medical data in cancer classification, based on state space models represented by the Mamba architecture. To this end, a mixed multimodal fusion architecture, called Mixed Fusion, was employed and developed to enhance the interpretability of the decision-making process. The proposed approach explores two variants of Mamba: one dedicated to visual processing, responsible for classifying the lesion image and generating probabilities associated with the target classes, and another focused on tabular processing, which uses these probabilities together with clinical and/or sociodemographic data to produce the final diagnosis. The experiments were conducted on two medical datasets: PAD-UFES-20, composed of clinical images and information associated with skin lesions, and NDB-UFES, consisting of histopathological images and sociodemographic data related to oral cancer. The results indicate slightly lower performance in balanced accuracy, compared with Transformer-based approaches, on PAD-UFES-20, and superior performance on NDB-UFES. Additionally, substantial gains were observed in the recall metric. Furthermore, the adoption of the Mixed Fusion architecture enables the application of the Shapley Additive Explanations (SHAP) method, increasing the interpretability of the results. These findings indicate that Mamba-based models constitute a suitable alternative for multimodal classification in medical data, especially in scenarios in which sensitivity is a relevant requirement.
### Title:
          Massive Activations Are Architecturally Robust: A Controlled Scratch/Commitment Residual Stream Test
 - **Authors:** Maruthi Vemula (University of North Carolina at Chapel Hill)
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Trained transformers reliably develop massive activations, a small number of hidden dimensions whose magnitude is far above the median and which concentrate on the sequence-start token. Whether these outliers are a removable artifact of the residual stream's overloaded read and write role, or instead a functional necessity, is actively debated. We test the artifact hypothesis directly, with an architectural intervention. Our architecture, Ledger Residuals, splits the residual stream into a mutable scratch stream (Deliberation) that intermediate computation may freely overwrite and a protected, decode-only accumulator (Commitment) that holds the representation the model reads out. If massive activations exist only because one stream is forced to be both scratchpad and answer, then a dedicated answer channel should remove the need for them. We find that it does not. In matched-loss language models at the 160M and 290M scales, the model rebuilds the canonical fixed-dimension, start-token outlier inside the protected channel. The rebuilt feature is smaller in magnitude than in a standard transformer but more sharply concentrated on the start token, and a stronger sparsity penalty makes it more persistent and more concentrated still, rather than removing it. Massive activations therefore look architecturally robust: they re-emerge in whichever representation the model decodes from, which is what we would expect if they are functional rather than incidental. We release our architecture and measurement code.
### Title:
          From Sentiment to Actionable Insights: A Data-Driven Public Sentiment Analysis of Advanced Air Mobility
 - **Authors:** Esrat Farhana Dulia, Amina Dhaher, Raiful Hasan, Syed Arbab Mohd Shihab
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Advanced Air Mobility (AAM) is an emerging low-altitude air transportation system whose successful deployment depends not only on technological advancement but also on public acceptance. This acceptance will drive government support, regulations, noise standards, and willingness to fly, and in turn the overall commercial viability of AAM. Understanding public sentiment toward AAM is therefore essential for identifying its societal barriers and informing its adoption strategies. This study analyzes 306,009 human-generated texts collected from Reddit and Quora to examine public discourse on AAM using AI-based models. Because multiple sentiment analysis models exist, identifying the most accurate model is critical for reliable AAM sentiment prediction and trustworthy public opinion analysis. Accordingly, seven models spanning lexicon-based, machine learning, deep learning, and transformer-based approaches are evaluated for AAM-specific sentiment classification. ModernBERT achieves the best classification performance and is used to label the full dataset. Using the resulting sentiment labels, Latent Dirichlet Allocation (LDA) is applied within each sentiment class to uncover latent topics in public opinion. The analysis identifies 20 distinct topics and traces their temporal evolution from 2008 to 2025. A cross-sentiment topic analysis further reveals six major clusters of public concern: workforce and skill development (25.29% of the dataset), regulation and compliance (24.64%), technical performance of drones (20.99%), military, geopolitics, and defense (14.58%), safety and operational risks (8.51%), and noise and disturbance (5.98%). Based on these findings, this study provides actionable strategies to address these concerns, thereby, improving public acceptance and support AAM deployment.
### Title:
          Perturbation-Based Uncertainty for Failure Detection in Vision-Language-Action Models
 - **Authors:** Yousung Lee, Dongsoo Har
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models have shown strong performance in robotic manipulation, but reliable uncertainty quantification remains challenging, particularly under distribution shift. Unlike autoregressive policies, many modern VLA models generate continuous actions through regression or flow-based generation, where explicit predictive probabilities are unavailable. Moreover, existing approaches often rely on stochastic action sampling or supervised failure labels, limiting their applicability across diverse pretrained VLA models. In this work, we propose a label-free and model-agnostic framework for inference-time uncertainty estimation through hidden activation perturbations, motivated by Bayesian perspectives on local model variations. Specifically, we inject Gaussian perturbations into transformer hidden activations and estimate epistemic signals from disagreement across perturbed action predictions. Experiments on LIBERO and LIBERO-PRO show that perturbation-based uncertainty consistently improves failure detection under distribution shift compared to sampling-based uncertainty, providing a practical uncertainty signal for VLA models.
### Title:
          UniSLAD: A Unified Framework for Structural and Logical Industrial Visual Anomaly Detection
 - **Authors:** Changyi Li, Chao Yang, Yu Xiao, Kari Tammi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual anomaly detection is a fundamental task in industrial automation. While existing approaches have achieved notable progress in identifying structural defects, the detection of logical anomalies remains relatively underexplored. In practice, structural and logical anomalies frequently co-occur in industrial workflows. Therefore, a solution capable of detecting both structural and logical anomalies is crucial for advancing comprehensive anomaly detection research. To address this limitation, we propose a unified framework, termed UniSLAD, which jointly addresses logical and structural anomalies without additional training, enabling a practical solution for dynamic industrial environments. First, we introduce a dual-feature extractor that synergistically integrates a Convolutional Neural Network (CNN) backbone for local texture perception with a Transformer backbone for global contextual reasoning, yielding richer and more comprehensive representations. Building on this foundation, we design dual-granularity feature representation modules. At the patch level, memory banks enhanced by the Mahalanobis Transform (MT) preserve representative features and support more discriminative anomaly scoring. At the image level, distribution maps are aggregated using Lower-Upper Mean (LUM) and Power Mean Pooling (PMP), yielding a more robust global representation than conventional average pooling. Extensive experiments on the two industrial benchmarks demonstrate that UniSLAD achieves competitive performance in comprehensive anomaly detection, achieving 99.4% and 93.1%, respectively. Furthermore, ablation studies verify the individual contributions and effectiveness of each proposed component.
### Title:
          B[FM]$^2$: Brain Foundation Model via Flow Matching with SplitUNet
 - **Authors:** Jaedong Hwang, Kathleen Zhang, Wei Dai, Konstantinos Kontras, Maarten Vanmarcke, Maarten De Vos, Ila Fiete, Paul Pu Liang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 EEG foundation models can learn generalizable representations from large-scale EEG corpora to enable single-backbone transfer across diverse clinical and brain-computer interface tasks. Existing models typically discretize the continuous multi-channel EEG waveform into patches or codebook tokens and train a transformer with masked self-supervision. Recognizing that this discretization fragments continuous brain rhythms and obscures fine-grained temporal dynamics, we present B[FM]$^2$(Brain Foundation Model via Flow Matching), whose inductive bias aligns with the data by pretraining directly on the raw signal using continuous-time flow matching without patches, tokenization, or masking. However, multi-channel EEG signals pose an architectural challenge for flow matching: time is densely sampled and highly autocorrelated (thousands of timepoints), while the electrode axis is short (tens of channels) at distinct scalp positions. To address this time-electrode asymmetry, we introduce SplitUNet, a velocity network that factorizes each block into separate 1D temporal and 1D electrode convolutions and downsamples only along time, preserving electrode topology throughout the hierarchy. B[FM]$^2$ sets a new state of the art on 7 of 9 standard downstream EEG classification tasks, using a pretraining budget of only 36,895 segments ($\approx$ 307h), 1-2 orders of magnitude ($\approx$ 30x) less than required by existing EEG foundation models. Further, it generates synthetic EEGs that two board-certified neurologists cannot distinguish from brain data (Cohen's $\kappa =$ -0.096). this https URL
### Title:
          Go-with-the-Track: Video Compositing and Motion Control with Point Tracking
 - **Authors:** Koichi Namekata, Yash Kant, Zhizheng Liu, Ryan D Burgert, Yuancheng Xu, Kuan Heng Lin, Emmett Steven, Julien Philip, Li Ma, Andrea Vedaldi, Paul Debevec, Ning Yu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Filmmaking demands precise motion control and reference image compositing -- capabilities that existing methods treat separately. Point-track-conditioned image-to-video models restrict content insertion to the first frame, while reference-to-video models lack fine-grained spatial-temporal control over how reference content integrates across frames. We present Go-with-the-Track, which unifies both capabilities by jointly conditioning on multiple reference images and reference-anchored point-tracks -- extending conventional point-tracks to explicitly establish correspondences between generated frames and reference images, thus enabling precise compositing and motion control throughout the video. To achieve this, we introduce spatially-aware point-track embeddings that encode the full sequence of point-track coordinates using a coordinate-wise MLP followed by temporal pooling. This representation captures the spatial characteristics of each point-track (serving as a unique identifier), while the embedding similarity correlates directly with spatial proximity, enhancing the model's ability to distinguish and associate point-tracks. We inject these point-track embeddings into a video diffusion transformer via a lightweight adapter, resolving the pixel-to-patch resolution mismatch while avoiding the substantial motion detail loss inherent in naive point-track subsampling. We use a hybrid training strategy to train jointly on dynamic, static, and synthetic scene video datasets to boost motion controllability. Experiments demonstrate that Go-with-the-Track achieves superior motion and reference control in a single model and enables new capabilities: multi-reference conditioned video generation with point-track driven compositing, as well as camera control for both static and dynamic scenes. Project Page: this https URL
### Title:
          Short-Term Electricity Demand Forecasting for New England Using a Hybrid Transformer-XGBoost Framework with Weather, Calendar, and COVID-19 Indicators
 - **Authors:** Reza Ghanavati, Behrooz Mosallaei
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate short-term electricity demand forecasting is critical for reliable power system operation, energy market planning, and infrastructure optimization. This paper presents a hybrid framework combining a Transformer encoder for temporal feature extraction with gradient-boosted decision trees (XGBoost) for daily electricity demand forecasting across New England. The framework integrates meteorological observations from six cities spanning all six New England states, calendar and holiday effects, autoregressive demand lags, and COVID-19 epidemiological variables. Hyperparameter optimization uses Optuna with a multivariate Tree-structured Parzen Estimator over 500 trials, with a leakage-free 70/15/15 chronological train-validation-test split. The hybrid model achieves a test RMSE of 8,876 MWh, MAPE of 2.05%, and R-squared of 0.906. A tabular-only XGBoost baseline achieves RMSE of 9,304 MWh, MAPE of 2.21%, and R-squared of 0.896. A Diebold-Mariano test (Harvey-Leybourne-Newbold correction) confirms the 427.7 MWh difference is statistically indistinguishable from noise (DM = -1.126, p = 0.262). An ablation study reveals COVID-19 features improved training accuracy but had asymmetric test effects: removal degraded hybrid RMSE by 3.2% while marginally improving XGBoost-only by 1.2%. A SHAP temporal analysis shows 5 of 8 COVID features rank higher on the post-acute test set than during pandemic-active training, indicating the model over-applies learned pandemic patterns. These findings establish temporal validity decay as a central mechanism: behavioral disruptions drove a strong COVID-demand signal during 2020-2021, but adaptation was complete by mid-2022, leaving epidemiological features as noise amplifying overfitting to stale pandemic patterns.
### Title:
          Comparing Transformers and Hybrid Models at the Token Level
 - **Authors:** Yanhong Li, William Merrill
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hybrid language models that mix attention and recurrent layers have shown promise: theoretically, recurrent layers ameliorate the limitations of pure transformers on state tracking, and empirically, hybrids can outperform pure transformers in loss and downstream evaluations \citep{waleffe2024empirical,merrill2026olmohybrid}. Yet it remains unclear which data or capabilities drive these gains, and to what degree they reflect the theoretical advantages motivating hybrid models. We address this question using the open weights from Olmo 3 \citep{olmo2025olmo3} and Olmo Hybrid \citep{merrill2026olmohybrid}: we compare the loss of a matched transformer and hybrid at the same target tokens under the same prefixes, stratifying the results by natural token tags, copy features, delimiter structure, and controlled synthetic probes. The hybrid has lower loss on most tag families, but the gains are not uniform: they are largest for open-class content words and smaller for many closed-class function words. Across prose, code, and markup, the hybrid's loss advantage is larger on opening delimiters than on the corresponding closing delimiters, and nearly vanishes on repeated $n$-grams. Synthetic probes show the same split: the hybrid is favored on pronoun-memory and entity-tracking tasks, whereas the transformer is favored on bracket-matching tasks that require choosing closing delimiters. These patterns suggest that the recurrent layers in hybrids improve predictions that leverage the semantic state of a document, whereas attention helps on tokens predictable by $n$-gram copying or syntactic bracket matching. We conclude with proof-of-concept filtered evaluations showing how token-level decompositions can sharpen pretraining diagnostics for hybrid architectures.
### Title:
          Learning through Internalization
 - **Authors:** Nikolaos Tsilivis, Nirmit Joshi, Marko Medvedev, Julia Kempe, Nati Srebro
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study internalization processes, by which neural-network-based systems absorb an explicit computational procedure into their own weights, and how they facilitate learning. We investigate how transformers internalize the simulation of semiautomata by internalizing chain-of-thought (CoT) tokens, which classes of semiautomata are harder to internalize, and expose the flip side of internalization, that is, a progressive degradation of out-of-distribution performance. We then provide the first provable analysis of successful internalization: for the task of learning parities, we show that a simplified one-layer transformer provably first learns the target with explicit CoT supervision and then internalizes the autoregressive generation as CoT tokens are progressively removed, learning to directly compute the parity. This task is computationally hard to learn from data without CoT supervision. Finally, we discuss how learning through internalization relates to the \textit{Positive Distribution Shift} phenomenon recently introduced by~\citet{Med+26}.
### Title:
          Grouped Query Experts: Mixture-of-Experts on GQA Self-Attention
 - **Authors:** Vishesh Tripathi, Abhay Kumar
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-attention is central to Transformer performance and is often the most expensive part of the Transformer at long context lengths because its pairwise token interactions scale quadratically with sequence length. Standard dense attention also applies the same set of attention heads to every token regardless of token difficulty or information content. This uniform activation can waste compute, especially as sequences grow longer and attention cost increases rapidly. We propose Grouped Query Experts (GQE), a mixture-of-experts layer on top of grouped-query attention (GQA). Within each GQA group, a router selects k query-head experts per token while all key-value (KV) heads remain dense and unchanged. Thus, GQE keeps the KV cache benefits of GQA and reduces only the active query-head computation. On a fixed 30B token budget at the 250M parameter scale, GQE matches the all-active GQA baseline in downstream accuracy while activating half the query heads per token.
### Title:
          Duet: Dual-Robot Understanding via Efficient Teaching
 - **Authors:** Yiqi Zhao, Ruohai Ge, Celina Shiyu Wang, Junjie Ye, Muchen Xu, Minhao Li, Sergey Zakharov, Basile Van Hoorick, Vitor Campagnolo Guizilini, Leonidas Guibas, Gaurav S. Sukhatme, Jyotirmoy V. Deshmukh, Yue Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dual-robot collaboration enables tasks that exceed the reach and payload of a single robot, such as collaboratively transporting objects across environments and executing coordinated handovers. Data acquisition is the primary bottleneck for training these systems. To this end, we introduce DUET, a dual-robot learning framework for mobile manipulation. For efficient data collection, we create a unified dual-embodiment synchronized VR-based teleoperation system for in-domain heterogeneous robot data collection. We further develop a complementary tracking pipeline that records human-human coordination and collaborative mobile manipulation priors. To allow efficient learning, we introduce an Action Chunking Transformer based architecture that first pretrains collaborative policies on efficient human-human demonstrations, before finetuning them on a minimal set of real-robot teleoperation trajectories. We develop a benchmark of four collaborative tasks to evaluate our framework using a Unitree G1 humanoid and a Dexmate Vega1 mobile manipulator. The results demonstrate that harnessing human priors not only yields superior task performance compared to baselines trained only on robot data, but also reduces the total human effort required for data collection. Our human data collection pipeline achieves 5.4x acceleration on average from teleoperation, but we perform equally or better than robot-only data trained policies across all tasks. Our project page is available at this https URL.
### Title:
          An Efficient and Effective Architecture for Large-Scale Traffic Prediction via Geometry-Adaptive Square Partitioning
 - **Authors:** Yongfeng Su, Hongwen Li, Zijian Zhang, Ziquan Fang, Lu Chen, Christian S. Jensen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traffic prediction is a core task in intelligent transportation systems and urban-scale decision making. Despite the effectiveness of mainstream neural-network based methods, their deployment in real-world settings with thousands of traffic sensors is jeopardized severely by their poor computational scalability. To address this, the community has attempted to incorporate spatial database partitioning techniques (e.g., Grid, Quadtree, and K-D Tree) to improve model scalability. However, these approaches rely on handcrafted geometric heuristics and often produce irregular or imbalanced data partitions, leading to boundary fragmentation, excessive padding overheads, and degraded model accuracy. In this paper, we propose SqLinear, an efficient and effective architecture for large-scale traffic prediction. First, we design Square Partition, a geometry-adaptive algorithm that partitions massive traffic sensors into balanced, non-overlapping, and near-square spatial regions. Unlike existing heuristic-based designs, Square Partition is theoretically grounded and provides provable guarantees on aspect ratio, balance, and partition utilization, establishing a high-quality foundation for downstream spatiotemporal modeling. Next, we propose a Hierarchical Linear Interaction (HLI) module that abandons the costly attention mechanisms commonly used in Transformer-based spatio-temporal models. HLI efficiently captures both local intra-region dynamics and global inter-region dependencies through a lightweight linear interaction scheme, enabling effective spatiotemporal modeling with linear computational complexity. Extensive experiments on four large-scale traffic datasets and 10 baselines show that SqLinear reduces MAE by 2.30% on average under standard setting and by 5.81% under extreme scalability settings, while reducing training runtime by 13.27%--30.84% in spatial- and horizon-scaling scenarios.
### Title:
          FiLM-Coordinated Dual-Branch Transformer for Global-Local Dependency Modeling in Language Modeling
 - **Authors:** Zhiqiang Zhou, Xu Ling, Junliang Dai
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard Transformers use a single self-attention pathway to model both global dependencies and local patterns, creating tension between long-range structural reasoning and fine-grained local representation learning. We propose a FiLM-coordinated dual-branch Transformer for language modeling, where each layer explicitly contains a global branch and a local branch, and feature-wise linear modulation (FiLM) is used for dynamic cross-branch coordination instead of simple concatenation or static addition. The key idea is that the two branches represent different dependency views of the same input, making channel-wise calibration more suitable than heavy token-level interaction. We therefore design a bidirectional FiLM module in which each branch generates per-channel scaling and shifting parameters to condition the other. Experiments on multiple small-scale language modeling settings show that the proposed structure consistently outperforms same-width single-branch baselines and weakened dual-branch variants under a fixed lightweight configuration. On TinyShakespeare and a 1M-character subset of WikiText-2, the full dual-branch FiLM model achieves the best results among same-width structural baselines. Multi-seed results support the stability of the gains, while mechanistic analyses show that FiLM learns input-dependent, layer-dependent, and channel-selective modulation patterns rather than static scaling. Parameter-matched widened single-branch baselines also indicate that the current design still leaves room for improvement in parameter efficiency.
### Title:
          ConnectomeBench2: A Unified Benchmark for Automated Connectomic Proofreading
 - **Authors:** Jeff Brown, Tim Farkas, Gleb Razgar, Edward S. Boyden
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Proofreading--correcting segmentation errors in 3D brain reconstructions--is the rate-limiting step in synapse-resolution connectomics. We release ConnectomeBench2, a unified multi-species dataset of over 716,485 expert-labeled proofreading decisions with >4,500,000 associated images spanning four major open connectomes (mouse, human, zebrafish, fly), spanning both split and merge error correction. Trained on this dataset, a single Vision Transformer with shared encoders for mesh geometry and electron microscopy reaches human-level accuracy across species for split error correction and merge error identification, with performance scaling with data size and modality. Beyond accuracy, we show that the model is well-calibrated within distribution, that measures of distribution distance predict where calibration and accuracy will degrade on unseen data, and that connectomics-specific pretraining and active learning-based sample selection show potential to substantially reduce the labeling effort needed to extend to new species and brain regions. The benchmark provides the infrastructure to train and evaluate increasingly capable vision models for connectomic proofreading. Data and code availability. The ConnectomeBench2 dataset is released on Hugging Face at this https URL. The accompanying codebase is available on GitHub at this https URL.
### Title:
          Dead-Direction Signatures: A Cheap Spectral Reading of Singular Complexity
 - **Authors:** Tejas Pradeep Shirodkar, P. J. Narayanan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Singular learning theory characterises the complexity of a deep network through the geometry of its loss singularities. The local learning coefficient (LLC), the standard estimator of Watanabe's real log canonical threshold (RLCT, $\lambda$), reads this geometry as an integrated Bayesian scalar through SGLD, which needs per-task calibration and $10^4$-$10^6$ forward-backward passes per checkpoint. We introduce Dead-Direction Signatures (DDS), a family of cheap closed-form spectral readings of singular structure: each reads a network's activation matrix or per-sample-gradient Fisher-Gram at a chosen layer, replacing the SGLD posterior chain with spectral linear algebra. The readings rest on a dead-direction framework that predicts a structural correlation between activation- and Fisher-side spectra at any singular minimum, and a rank-multiplicative volume identity that single-eigenvalue monitors cannot produce: the active-volume $\log\det^{+}(G)$ slope counts the dead directions, tracking the rank-deficit $r$ across $r \in \{1,2,3,4\}$ (slope ratios $2.0, 3.1, 4.0$ at $r{=}2,3,4$ against the predicted $2,3,4$), where the smallest eigenvalue is rank-blind. On reduced-rank regression with closed-form $\lambda$, calibrated LLC recovers $\lambda$ at $99\%$ mean and the DDS observables rank-track it at the framework-predicted sign; on a non-linear modular-addition transformer DDS separates $d_{\mathrm{model}}$ across eighteen orders of magnitude where calibrated LLC at the protocol budget is rank-flat. Complementary to LLC's integrated posterior reading, DDS gives a directional, layer-local handle on a network's dead directions, read in closed form from its activation and gradient spectra.
### Title:
          Comparative Evaluation of Machine Learning and Deep Learning Models for Wound-Rotor Synchronous Motor Performance Prediction
 - **Authors:** Kıvanç Doğan, Ahmet Orhan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wound rotor synchronous motors have emerged as a strong alternative that eliminates dependence on REEs. However, WRSM design requires the simultaneous optimization of numerous geometric and electromagnetic parameters, and the high computational cost of conventional finite element analysis severely limits the rapid exploration of the large parameter space. Although there are machine-learning-based surrogate modeling studies in the literature, they generally compare only a limited number of models, exclude deep learning architectures, and do not provide a comprehensive benchmark specific to WRSM. In this study, the performance of a total of eight machine learning and deep learning models from four different algorithmic families was systematically compared for the prediction of WRSM torque and motor efficiency. On a dataset of 3351 samples generated using Latin Hypercube Sampling in the Motor-CAD simulation environment, each model was trained with 10 different random seed values and tuned via Optuna hyperparameter optimization. Different from the existing literature, this study jointly offers a broad model spectrum including recent deep learning architectures such as FT Transformer, a multi-seed reproducibility protocol, and a Pareto analysis of the computational cost-accuracy trade-off. The results revealed that neural-network-based models systematically outperform tree-based models. The FT-Transformer model achieved the highest single-model accuracy with R^2 = 0.9928, producing predictions in 0.33 milliseconds and thus obtaining several orders of magnitude speedup compared to FEA. Model performances were evaluated in a multidimensional manner using R^2, MAE, RMSE, and MAPE metrics.
### Title:
          Few-Shot Hyperspectral Aphid Detection via FastGAN Synthetic Data Generation, Transformer-Based Classification and Explainable AI
 - **Authors:** Ali Saeidan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Early detection of aphid infestation in crops is essential for preventing yield loss and reducing unnecessary pesticide use. Hyperspectral imaging combined with Spectral Information Divergence (SID) analysis offers a non-destructive approach for monitoring plant health; however, deep learning methods applied to hyperspectral data are often limited by small dataset sizes. In this study, a data-efficient generative adversarial network (FastGAN) was employed to augment a hyperspectral SID dataset of faba bean leaves containing healthy and aphid-infested samples. The trained generator produced 10,000 synthetic images preserving structural and spectral characteristics of real samples. Image quality was evaluated using Frechet Inception Distance (FID), demonstrating stable convergence and realistic reconstruction of leaf morphology and infestation patterns. The augmented dataset was used to train four classification architectures: VGG16, ResNet-50, EfficientNet, and Vision Transformer (ViT). Results showed that dataset augmentation significantly improved classification robustness, with performance progressively increasing from classical convolutional networks to transformer-based models. The ViT model achieved the highest accuracy and F1-scores, while EfficientNet provided strong balanced performance and ResNet-50 showed moderate improvements over VGG16. Confusion matrix analysis confirmed reduced false negatives and improved disease detection when using advanced architectures. The findings demonstrate that FastGAN-based augmentation effectively enhances hyperspectral plant disease classification and that transformer-based models provide the most reliable discrimination between healthy and infested leaves.
### Title:
          A Rank-One Popularity Component in Dot-Product Recommender Scores:Population Theory and Prior-Separation Evidence
 - **Authors:** Yang Cheng
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Representation anisotropy in recommender systems is often attributed to Transformer architectures. We identify a more general source in the conditional training distribution. For any encoder using a dot-product softmax decoder, the population-optimal score decomposes into pointwise mutual information, an item-marginal term log p(i), and a context-dependent offset. After centering, the item marginal produces a context-shared rank-one score component, while time-varying marginals induce a low-rank popularity subspace. This score-level result does not imply universal embedding collapse because its transfer to embeddings depends on factorization geometry. Experiments on synthetic data and public Alibaba and Tianchi interaction logs support the proposed mechanism. Separating log p(i) from the learned dot product reduces the measured popularity-aligned score energy by 98.6 percent in a matched intervention. Permutation tests confirm that this reduction is specific to the empirical popularity direction. These results explain a class of apparent representation degeneration as a decoder-level consequence of long-tailed item marginals rather than a property unique to Transformer encoders.
### Title:
          Topological Neural Dynamics: A Neuron-wise Framework for Sequence Modeling
 - **Authors:** Borui Cai, Yao Zhao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing sequence models, including RNNs, LSTMs, continuous-time networks, and Transformers, share a common structural principle: layer-wise dynamics, where all neurons in the same layer co-evolve through a shared parameterized operator, leaving individual neurons no freedom to evolve independently. Yet in many complex dynamical systems, rich global behavior emerges precisely from locally evolving units interacting through structured connectivity. Inspired by this principle, we introduce Topological Neural Dynamics (TND), a sequence modeling framework that shifts computation from layer-wise to neuron-wise dynamics. TND represents a neural system as a directed neuron graph, an interaction operator, and a local dynamics function, where each neuron evolves independently and collective computation emerges from interactions through the explicit graph topology. We instantiate TND as a discrete-time graph-coupled dynamical system and evaluate it as a case study on a behavior cloning task in single-player Pong. Compared with Vanilla RNN, Sparse RNN, LSTM, Closed-form continuous-time neural network (CfC), and Transformer baselines, TND achieves the best catch rate and a mean of 17.47 consecutive catches per round, more than three times that of the strongest baseline. These results suggest that shifting from layer-wise to neuron-wise dynamics provides an effective inductive bias for sequence modeling.
### Title:
          Mind the Noise: Sensitivity of Transformer-based Interaction-Aware Trajectory Prediction Models to Noisy Data
 - **Authors:** Shahab Salehi, Luca Lusvarghi, Miguel Sepulcre, Javier Gozalvez
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Trajectory prediction allows autonomous vehicles to anticipate the future behavior of surrounding objects (or agents) and, accordingly, maximize the safety and efficiency of their driving. State-of-the-art Transformed-based interaction-aware trajectory prediction models, which rely on attention mechanisms to capture multi-agent interactions and maximize prediction accuracy, are commonly trained and evaluated on long-range high-quality datasets. These datasets are typically obtained by aggregating data from multiple vehicles or drones and removing any object detection or tracking noise offline. Yet, information about a surrounding object's state (its position, speed, heading) is far from being noiseless in real-world deployments. Object state estimation is affected by perception uncertainties and localization errors that can be particularly large for objects received via Vehicle-to-Everything (V2X) communications. In this paper, we analyze the impact of noisy object state information on the trajectory prediction accuracy of a state-of-the-art Transformer-based interaction-aware trajectory prediction model. Our study demonstrates that trajectory prediction accuracy can rapidly deteriorate as the noise intensity increases. Numerical results show that the prediction accuracy can reduce by a 1.3x factor under small noise levels and by as much as a 3.9x factor under the highest (yet realistic) noise conditions. These findings reveal the strong sensitivity of trajectory prediction models to noisy data, underscoring the need for more realistic training and evaluation datasets as well as noise mitigation strategies.
### Title:
          Urban Power Grid Topology and Hierarchy Identification from Open Data
 - **Authors:** Shiliang Zhang, Sabita Maharjan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding the complex topology and hierarchy of urban power grid is crucial for energy prognosis, power flow management, and system resilience analysis. However, detailed grid information remains largely proprietary. This creates significant barriers for research and innovation, especially when analyzing the last-mile distribution networks connecting individual buildings. This paper addresses this challenge by developing an open-data-driven framework for the complete identification of urban power grid topology, from high-voltage transmission down to individual building connections. Particularly, we fuse public infrastructure data (power-lines, substations, transformers, poles) to map the high and medium-voltage skeleton using graph-based algorithms. We then leverage geospatial machine learning on OpenStreetMap building data to group power demand clusters, and infer the physical topology of the final distribution lines linking the clustered buildings. We apply the developed framework to the district of Alna in Oslo, Norway, and we reconstruct the complete grid topology that connects 7,330 buildings and all major electricity infrastructure assets. With the research in this work, we provide a critical tool that facilitates power system analysis, e.g., power flow optimization, cascading failure simulation, and grid resilience against the penetration of distributed renewable generation.
### Title:
          SOHET: Sequence Of Heterogeneous Events Transformer with Self-Supervised Pre-Training
 - **Authors:** Kees Jan de Vries, Mustafa Radha, Mathijs de Jong
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many machine learning applications rely on heterogeneous event streams to make predictions, either causally as events arrive or bidirectionally over complete sequences. We propose SOHET (Sequence Of Heterogeneous Events Transformer), a hierarchical architecture combining event-type-specific tabular encoders with temporal and type embeddings, processed by a causal or bidirectional transformer. We introduce three self-supervised pre-training objectives for the causal setting. On a proprietary large-scale real-world this http URL fraud detection task with 17 event types, SOHET outperforms FlexTPP, NAPPT, and CIPPT by 5.8%. Pre-training yields an additional 2.6% gain and 2.4% faster convergence. On the EBES benchmark, bidirectional SOHET matches or exceeds the published best on 6 out of 8 tasks.
### Title:
          Universal Encoders for Modular Relational Deep Learning
 - **Authors:** Jakub Peleška, Gustav Šír
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Relational Deep Learning (RDL) models multi-tabular databases as temporal heterogeneous graphs for end-to-end representation learning. While RDL is evolving rapidly, existing approaches face significant generalization obstacles. They are either schema-specific, requiring training from scratch for every new database, or they rely on monolithic architectures that entangle feature encoding with graph message-passing. Analyzing these limitations, we establish four core pillars for building foundational relational models: semantic granularity, structural topology, temporal causality, and unified optimization. Addressing these pillars, we propose a modular approach that decouples row encoding from graph message-passing. We introduce the Universal Row Encoder, a transformer-based module that integrates raw cell data with schema metadata$-$including column semantics, table names, and global distribution statistics$-$to produce table-width invariant row embeddings. By explicitly feeding global statistics to an intra-row self-attention mechanism, the encoder natively contextualizes unseen features and handles sparse data. Serving as a flexible "backend" for any downstream graph architecture, our pretrained encoder enhances cross-database knowledge transfer on the established RelBench benchmarks while improving learning convergence and memory footprint.
### Title:
          DisSpeech: Low-Resource Controllable Mandarin Stuttered Speech Synthesis for ASR Augmentation
 - **Authors:** Yao Lu
 - **Subjects:** Subjects:
Sound (cs.SD); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Stuttered speech recognition remains challenging, with disfluencies such as repetitions, prolongations, and blocks disrupting speech continuity and acoustic patterns. This problem is further aggravated in Mandarin scenarios by the limited availability of stuttered speech data, which makes it difficult to train robust ASR models for diverse disfluency patterns. To address this problem, this paper proposes DisSpeech, a discrete speech token-based framework for low-resource controllable Mandarin stuttered speech synthesis and ASR data augmentation. The proposed framework introduces explicit stuttering event labels to control different disfluency patterns. Text and stuttering event labels are mapped into semantic speech tokens by a non-autoregressive masked generative Transformer, followed by prosody-aware acoustic reconstruction with explicit pitch and energy modeling. With fine-tuning using less than 50 hours of Mandarin stuttered speech, DisSpeech can generate controllable stuttered speech with competitive speech quality. Experimental results show that the proposed method outperforms previous stuttered speech synthesis methods in both speech quality and event controllability. Furthermore, the synthesized stuttered speech effectively improves multiple ASR models, with Qwen3-ASR-0.6B achieving a state-of-the-art CER of 4.19% on the evaluated Mandarin stuttered speech recognition task, while causing only slight degradation on fluent speech.
### Title:
          Decoupling the Declarative from the Procedural in Vision-Language-Action Models
 - **Authors:** Nikolaos Tsagkas, Andreas Sochopoulos, Chris Xiaoxuan Lu, Oisin Mac Aodha, Alexandros Kouris
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying generalist robotic agents in the real world requires transferable skills. Specifically, a policy trained to clone a behavior from object-specific demonstrations must generalize beyond that object, otherwise data collection requirements become intractable. Recently, fine-tuning of pre-trained billion-parameter Vision-Language Models (VLMs), initially on large-scale robot datasets and then on fewer scenario-specific demonstrations, has emerged as the predominant paradigm for designing Vision-Language-Action (VLA) models. While these policies achieve state-of-the-art manipulation performance in-distribution, they remain brittle to minor spatial, semantic, and task variations. In this work, we address the inability of current models to decouple the declarative (i.e., concepts and entity semantics) from the procedural knowledge (i.e., how to do something) encoded in their parameters, which is a fundamental bottleneck for zero-shot skill transfer to novel objects. To address this, we propose w$^{2}$VLA, a new VLA model with restructured information flow. Rather than feeding all multimodal tokens from the VLM encoder into a large, opaque transformer-based action expert, our approach modulates the robot state sequence with visual, spatial, and skill information in a compositional and interpretable manner. Unlike popular, state-of-the-art VLAs, we show that our modular approach successfully decouples knowledge representations, enabling robust behavior cloning and unprecedented zero-shot skill transfer capabilities across dissimilar, unseen objects.
### Title:
          Compressing Observation History into Agent Memory: Distilling Transformers into Recurrent Transformers
 - **Authors:** Philippe Weinzaepfel, Christian Wolf, Bülent Mert Sariyildiz, Guillaume Bono, Gianluca Monaci
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers are AI's workhorse with strong performance in modeling sequential data, but their computational cost becomes prohibitive when processing long sequences. We target long-horizon streaming vision and robotics applications like map-free pose estimation, where it is particularly impractical to store and maintain a history of observations. Recurrent Transformers address this limitation by maintaining fixed-size memory but their performance lags behind that of transformers operating over the full observation history. We argue that this gap does not stem from architectural limitations, but from differences in how these models learn to compress past information. Without access to an observation history, recurrent models must explicitly decide what to retain in memory at each step, a significantly harder learning problem. In this work, we propose a distillation approach that transfers the compression strategy of a classical full-history transformer to a recurrent variant. We enable this by designing a teacher model that explicitly compresses its observation history into a fixed-size bottleneck representation. By directly supervising the student's memory with this bottleneck representation, we align the two compression mechanisms. We show that this approach allows to train a recurrent latent robotic memory with linear-time complexity while substantially narrowing the performance gap to full-history transformers.
### Title:
          LIG: Layer-wise Integrated Gradients for Within-Layer Flow Analysis in Transformers
 - **Authors:** Eight Suzuki, Hideitsu Hino, Noboru Murata
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers achieve strong performance, but their internal computations remain opaque. We view each Transformer layer as a dynamic graph whose nodes are token representations and per-head attention outputs, with Multi-Head Attention (ATT) and MLP as module boundaries. On this graph we use LIG (Layer-wise Integrated Gradients), which applies set-to-set Integrated Gradients (IG) at nonlinear module boundaries. Set-to-set IG applies IG to a map from a set of input token representations to a set of output representations, evaluating token-to-token contributions, which is not standard in prior IG applications. This extends IG from the usual scalar-objective setting to set-to-set maps via an L2 scalarization, and composes within-layer contributions in the spirit of Layer-wise Relevance Propagation (LRP), with IG completeness playing the role of LRP-style conservation at each boundary. We use LIG to analyze (i) the agreement between module-wise composition and layer-whole attribution under an L2 criterion, and (ii) within-layer information flow by tracing separated ATT and MLP contributions. On BERT-base and PTB, configurations that best preserved within-layer consistency used the target token's embedding as the ATT baseline and either the ATT output at a=0 or Zero as the MLP baseline. We therefore present LIG as a diagnostic XAI tool at module-boundary granularity, without model-specific retraining or per-operation interpreter design. Code is available at this https URL.
### Title:
          The Two-Hump Problem: Bridging the Difficulty Gap in Mathematical Reinforcement Learning
 - **Authors:** Lucas Fagan, Michele Tarquini, Ali Shehper, Maksymilian Manko, Angus Gruen, Coco Huang, Giorgi Butbaia, Davide Passaro, Sergei Gukov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Group Theory (math.GR); Geometric Topology (math.GT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mathematical search problems present a unique challenge for Reinforcement Learning (RL) due to vast search spaces and sparse rewards. In previous works, the Andrews-Curtis (AC) conjecture was established as an illustrative example of such problems. In this work, we identify a critical structural barrier in the AC landscape: a "Two-Hump" distribution, where problem instances are either trivially solvable or effectively impossible, with a scarcity of intermediate "hard-but-solvable" instances required for effective learning. We tackle this challenge through two primary avenues: novel data generation techniques to populate the difficulty gap, and significant algorithmic enhancements including the introduction of supermoves and Transformer-based architectures. We demonstrate substantial performance improvements over previous baselines, and release new comprehensive benchmark datasets including AC-19 (125,192 AC-trivial presentations of varying difficulty with length at most 19) and AC-1M (1,136,154 hard AC-trivial presentations of length at most 30), the first large-scale, publicly available datasets of this kind.
### Title:
          Evaluating Document-Tuned Transformer Representations for Person-level Mental Health Assessment
 - **Authors:** Aaron Marker, Oscar Kjell, Vasudha Varadarajan, H. Andrew Schwartz
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Person-level psychological assessment requires aggregating meaning across many messages from the same individual, a task that document-level training objectives were not explicitly designed for. We present a systematic, empirical comparison between architecturally matched traditional (a) base-transformers and (b) document-tuned-transformers (further contrastively fine-tuned at the document-level, sometimes referred to as "sentence transformers") under otherwise identical conditions. Comparing layer-wise and overall performance across two longitudinal mental health and psychological datasets, we find document-tuned models demonstrated a consistent improvement over base representations (increase in Pearson r of 13.4%, p=.015). Robustness analyses revealed document-tuned models remained more accurate under perturbations to word deletion, synonym replacement, typo injection, and back translation. Further, hedged language (e.g., `usually') was more characteristic of outcomes in document-tuned embeddings while abundance (e.g., `lot') was more characteristic of base-transformers, suggesting document-tuned models may better capture uncertainty. These results suggest representation choice impacts mental health prediction, document-tuned models often being more adept.
### Title:
          Towards Imputation of Pre-Trained Language Model Metadata using Semantic Fingerprinting
 - **Authors:** Adekunle Ajibode, Oussama Ben Sghaier, Keheliya Gallaba, Bram Adams, Ahmed E. Hassan
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pre-trained language models (PTLMs) hosted on platforms such as Hugging Face form complex lineage structures similar to software dependency graphs. However, unlike traditional software ecosystems, PTLM repositories often lack reliable provenance due to missing metadata, such as licenses, reuse methods, pipeline tags, model types, and training libraries. To address this gap, we introduce Semantic Fingerprinting (SemFin), a lightweight approach that combines Hugging Face (HF) configuration files with model repository tags to automatically impute missing model metadata fields and reconstruct model lineage chains. We evaluate SemFin on a large-scale dataset of 317,133 PTLMs. Our results show that configuration files typically encode the technical requirements necessary to instantiate and reuse models, enabling them to serve as a structural blueprint for model reuse, particularly for transformer-based architectures. By combining these configuration files with model repository tags, SemFin significantly outperforms the existing propagation-based imputation approaches, improving prediction accuracy by up to 31.4% and 26.6% compared to Graph Avg and Hub Avg baselines. Importantly, SemFin also imputes metadata for 16.6% of isolated models where propagation-based methods fail. Applying SemFin to impute missing reuse-method and license metadata for 167,089 unlabeled models reveals that traceable reuse method chains expand by 75.9% and license lineage chains by 53.6%, uncovering 86 previously invisible reuse method patterns, while the proportion of incompatible license patterns only increases from 34.8% to 36.8%. These findings demonstrate how automatically derived structural signals can support the automated construction of AI Bills of Materials (AIBOMs), helping transform metadata from an error-prone manual declaration into information inferred directly from model artifacts.
### Title:
          AgroSense 2.0: Cross-Modal Transformer Fusion with Geospatial Raster Integration and Interpretable Multi-Task Learning for Precision Crop Recommendation
 - **Authors:** Vishal Pandey, Rishav Tewari, Ruzina Haque Laskar
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Crop recommendation systems in precision agriculture have long suffered from a fundamental modality gap: visual soil characterization and chemical nutrient profiling are typically treated as independent inference problems, with fusion often reduced to late-stage feature concatenation. AgroSense~2.0 addresses this limitation through three architectural advances. First, we introduce continental-scale geospatial integration via a seven-band soil raster (\texttt{india\_soil\this http URL}) spanning India, encoding Nitrogen, pH, SOC, Clay, Sand, Silt, and Bulk Density as $32\times32$ spatial patches, a modality entirely absent from prior work. Second, we replace naive feature concatenation with a cross-modal Transformer fusion module, where tabular nutrient features attend over image representations via multi-head attention, enabling richer inter-modal dependency modeling than shallow fusion. Third, we adopt a multi-task objective jointly optimizing soil classification and crop recommendation through a shared backbone, improving generalization via complementary cross-task signal. To enhance interpretability, we apply TreeSHAP to the tabular branch, revealing crop-conditioned nutrient sensitivity: humidity and rainfall emerge as the most influential features globally, while crop-specific profiles diverge meaningfully rainfall dominates rice, nitrogen and potassium dominate maize, and humidity and nitrogen dominate coffee. These explanations provide transparency into model decisions and surface both agronomically consistent patterns and dataset-specific divergences worth further study. Together, these contributions establish AgroSense~2.0 as a more principled, interpretable, and geospatially grounded framework for precision agriculture.
### Title:
          The Pitfall of Scaling Up: Uncovering and Mitigating Popularity Bias Amplification in Scaling Transformer-based Recommenders
 - **Authors:** Weiqin Yang, Yue Pan, Chongming Gao, Sheng Zhou, Xiang Wang, Can Wang, Jiawei Chen
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We identify a critical pitfall in scaling transformer-based sequential recommenders: while increasing model size improves recommendation accuracy, it simultaneously amplifies popularity bias. This bias drives systems to over-recommend popular items at the expense of niche ones, which not only undermines fairness but also degrades the broader ecosystem by reinforcing the Matthew effect and filter bubbles. Consequently, this bias amplification emerges as a fundamental obstacle to sustainable model scaling. Through comprehensive theoretical and empirical analyses, we uncover the root cause of this amplification. Our findings reveal that as model depth increases, the two core components of the transformer architecture, i.e., attention aggregation and feed-forward projections, synergistically induce severe spectral collapse in model predictions, which directly translates to the amplification of popularity bias. To address this challenge, we propose SPRINT (Scalable Popularity Regularization IN Transformers), which mitigates spectral collapse during scaling by constraining (i) the maximum column-sums of the attention score matrices and (ii) the spectral norms of the feed-forward parameters. Extensive experiments demonstrate that SPRINT significantly improves both accuracy and long-tail fairness. Crucially, it yields more favorable scaling behaviors when expanding model sizes from 0.05M to 0.34B parameters. The code is available at this https URL.
### Title:
          ScalePredictor: Instance-aware Scale Learning for Accurate Quantization of Vision Transformers
 - **Authors:** Changjun Li, Runqing Jiang, Lian Xu, Ye Zhang, Qingyong Hu, Yulan Guo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers have achieved remarkable success in many fields, yet their deployment on edge devices remains challenging due to their substantial computational demands. Post-Training Quantization (PTQ) offers an attractive solution by compressing models using a small calibration set with minimal training overhead. However, most existing PTQ works adopt a static quantization paradigm that is uniformly applied to all instances. Given the substantial diversity of natural images, the activation distributions vary significantly across samples, making these methods inherently suboptimal. In this paper, we propose ScalePredictor, a dynamic quantization framework for accurate and efficient quantization scale learning of ViTs. We first reveal a hidden correlation between the distribution range of shallow-layer activations and the optimal scales of deeper layers. Based on this, we develop a scale learning mechanism that integrates an efficient range extraction approach to capture robust range statistics at the shallow stage, which are then fed into a Taylor-motivated polynomial scale projection module to generate all quantization scales simultaneously. With the efficiency of polynomial approximation, ScalePredictor introduces insignificant computational overhead while avoiding costly just-in-time calibration. Extensive experiments on ImageNet demonstrate that ScalePredictor consistently outperforms prior PTQ methods, achieving a more favorable accuracy-efficiency trade-off. Code and additional results are shown in the supplementary materials.
### Title:
          Integrating Facial Generation into Full-Duplex Spoken Dialogue Systems
 - **Authors:** Jingjing Jiang, Atsumoto Ohashi, Ryuichiro Higashinaka
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Computation and Language (cs.CL); Computer Vision and Pattern Recognition (cs.CV); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Full-duplex spoken dialogue models, such as Moshi, enable natural, low-latency voice conversations. However, they remain limited to the audio modality, lacking the facial expressions that are integral to human communication. We present Moshi-Face, the first full-duplex dialogue model that jointly processes the user's audio and facial input while simultaneously generating speech and facial motion. We first construct a vector-quantized variational autoencoder (VQ-VAE) as a face codec that encodes 3D head meshes extracted from facial videos into compact discrete tokens, referred to as face tokens, and conversely reconstructs 3D meshes from these tokens. We then extend Moshi with a Face Transformer module that generates face tokens non-autoregressively, enabling Moshi-Face to produce synchronized audio and face tokens in real time. Experiments show that Moshi-Face achieves audiovisual alignment at low latency while preserving the dialogue quality of the original audio-only model.
### Title:
          SPOTR: Spatio-temporal Pooling One-Token Reconstruction for Universal Physiological Signal Self-supervised Learning
 - **Authors:** Yiyu Gui, Mingzhi Chen, Yuesheng Zhu, Guibo Luo, Yuchao Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physiological signals such as EEG, ECG, and PPG are widely used in clinical monitoring. Recent self-supervised learning (SSL) methods offer an attractive way to leverage unlabeled recordings, yet they still fall short in practice. In particular, current SSL methods struggle across heterogeneous datasets, often distorting clinically meaningful structures or learning shortcuts from temporal and cross-channel redundancy. Consequently, existing SSL methods often deliver limited performance under linear probing, a lightweight adaptation setting that better matches real-world medical scenarios. Moreover, most Transformer-based SSL models encode a flattened spatiotemporal token sequence, incurring high computation and memory cost, and are typically developed within a single modality. To address these limitations, we present SPOTR (Spatio-temporal Pooling One-Token Reconstruction), a compress-reconstruct pretraining framework that introduces a single-token global bottleneck for physiological signals. SPOTR compresses each waveform into a single-token representation and reconstructs the signal conditioned only on this representation. Meanwhile, SPOTR introduces an efficient spatio-temporal compaction module to reduce computation and memory cost. Pretrained on 20 datasets spanning EEG, iEEG, ECG, and PPG, SPOTR consistently outperforms the strongest baseline under linear probing, improving average AUC by 18.49%, 21.71%, 17.86%, and 4.64%, respectively. Compared with a representative general-purpose time-series foundation model, SPOTR achieves around 78% lower latency and 52% lower peak GPU memory on average. The code can be found at this https URL.
### Title:
          Analyzing the Analyzers: Model Counting Meets Abstract Interpretation
 - **Authors:** Junda Zheng, Peisen Yao
 - **Subjects:** Subjects:
Programming Languages (cs.PL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Abstract interpretation offers a principled foundation for static analysis by approximating concrete program semantics via abstract domains. However, quantitatively comparing the precision of different domains remains a longstanding challenge. We present MCAI (Model Counting meets Abstract Interpretation), a new methodology that employs model counting to measure the precision of abstract domains. Unlike prior approaches that assess precision relative to specific analysis queries, MCAI encodes both concrete semantics and abstract values as logical formulas, enabling a client-independent, quantitative metric of imprecision that captures the inherent semantic loss in the abstractions. We apply MCAI to four abstract domains and evaluate the precision of their best abstract transformers via symbolic abstraction. Our results yield several insights: the Interval domain, despite its simplicity, often achieves precision comparable to that of Octagon; many octagonal constraints are semantically redundant; and the bit-level KnownBit domains consistently outperform the word-level domains. MCAI offers both theoretical insights into the precision of abstract domains and practical guidance for selecting suitable abstractions.
### Title:
          What Do Neural Networks Learn for TDOA Estimation? A Cross-Architecture Probing Study
 - **Authors:** Yaozhong Kang, Jiang Wang, Runwu Shi, Takeshi Ashizawa, Benjamin Yen, Kazuhiro Nakadai
 - **Subjects:** Subjects:
Sound (cs.SD); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural networks outperform classical GCC-PHAT for Time-Difference-of-Arrival (TDOA) estimation in noise and reverberation, yet their internal strategy remains unexplored. To uncover it, we turn GCC-PHAT's mathematical steps into diagnostic targets, probing hidden layers of three architectures (MLP, CNN, Transformer) and complementing with gradient attribution and causal frequency masking. We find that cross-power computation consistently emerges across all architectures and conditions, while PHAT whitening, the defining step of GCC-PHAT, fails to emerge. Instead, networks learn a magnitude-aware frequency weighting that preserves per-frequency reliability information discarded by PHAT. This makes PHAT an information bottleneck: removing it from both classical and neural GCC pipelines improves performance under additive noise. On real-world reverberant data, PHAT remains the best classical weighting, but end-to-end networks achieve lower error by learning data-adaptive weighting.
### Title:
          Morphology-Aware Multimodal Representation Learning for Insect Phylogenetic Reconstruction
 - **Authors:** Zixuan Liu, Kaijie Yu, Chun He, Xiaoxu Cai, Xinhai Ye, Haishuai Wang, Gongyin Ye, Jiajun Bu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Morphological traits provide important evidence for phylogenetic reconstruction and evolutionary relationship analysis. Recent image-based approaches have introduced deep learning, particularly convolutional models, to derive morphological features from specimen images, but these methods generally rely on single-modality visual representations and do not explicitly incorporate morphological semantics. This study proposes a morphology-aware multimodal alignment framework for insect phylogenetic reconstruction. The framework combines specimen images with curated morphological descriptions by adapting a vision transformer through parameter-efficient fine-tuning and supervised contrastive learning, followed by image-text alignment in a shared latent space. The learned image embeddings are then used as continuous traits for Bayesian phylogenetic reconstruction. On the public Rove-Tree-11 dataset, comparative and ablation experiments across multiple visual backbones and feature adaptation strategies demonstrate that multimodal alignment improves topological agreement with the reference phylogeny. The results indicate that the proposed framework can derive morphology-aware visual traits for computational phylogenetic reconstruction.
### Title:
          BAC-JEPA: Label-Efficient Breast Arterial Calcification Segmentation via Synthetic Mammography-Guided Supervision
 - **Authors:** Scott Chase Waggener, Lakshman Tamil
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Breast arterial calcification (BAC) on screening mammograms is an emerging cardiovascular risk biomarker, but quantitative use requires reproducible segmentation and expert pixel-level labels are costly. We present BAC-JEPA, a label-efficient segmentation framework trained on procedurally generated arterial calcification inserted into real mammographic backgrounds with exact masks. Candidate backgrounds were selected from model-screened mammograms with low predicted BAC response; the generator samples arterial structure, disease burden, radiographic appearance, and hard-negative distractors including nonarterial calcifications and metallic objects. Synthetic masks are paired with mammography self-supervised Vision Transformer encoders and a high-resolution convolutional decoder to produce full-resolution segmentation maps. The study used 75,472 mammography studies from 34,956 patients for background selection and representation learning, trained on synthetic images from 10,000 backgrounds, selected checkpoints with 1,000 development backgrounds, and evaluated transfer on all 1,000 human-labeled BacSeg synthetic 2D mammograms. On held-out synthetic validation data, the larger backbone achieved IoU 0.5325 and Dice 0.6357. On BacSeg, image-level classification from segmentation probability maps reached AUROC 0.8719, with 0.8547 for the smaller backbone. Four-view inference required 110.68--213.63 ms on an RTX 5090 GPU, and severe-preset synthetic image generation averaged 2.7071 s per image on a multicore workstation. These results indicate that BAC-specific synthetic supervision can produce useful image-level transfer without human pixel-level training masks, while expert-reviewed real-mammogram segmentation remains necessary for clinical validation and calibration.
### Title:
          Accurate identification and measurement of the precipitate area by two-stage deep neural networks in novel chromium-based alloys
 - **Authors:** Zeyu Xia, Kan Ma, Sibo Cheng, Thomas Blackburn, Ziling Peng, Kewei Zhu, Weihang Zhang, Dunhui Xiao, Alexander J Knowles, Rossella Arcucci
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Materials Science (cond-mat.mtrl-sci); Machine Learning (cs.LG); Chemical Physics (physics.chem-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The performance of advanced materials for extreme environments is underpinned by their microstructure, including the size and distribution of reinforcing phases. Chromium-based superalloys are a recently proposed alternative to conventional face-centred-cubic superalloys for high-temperature applications, such as Concentrated Solar Power, and their development requires efficient measurement of precipitate volume fraction and size distribution from electron microscopy images. Traditional fixed-threshold image processing is sensitive to background noise, generalises poorly across materials, and requires substantial manual measurement effort. To address these bottlenecks, this study proposes DT-SegNet, an end-to-end two-stage deep learning scheme based on YOLOv5 and SegFormer for object detection and segmentation in electron microscopy images. The approach combines the training efficiency of convolutional neural networks at the detection stage with the segmentation accuracy of a Vision Transformer. Numerical experiments show that DT-SegNet substantially outperforms state-of-the-art segmentation tools offered by Weka and ilastik across metrics including accuracy, precision, recall, and F1-score. The model provides a useful tool for alloy-development microstructure examinations and helps address the large datasets associated with high-throughput alloy development.
### Title:
          From Convolution to Transformer: A Comparative Study of U-Net Variants for Brain Tumor and Retinal Vessel Segmentation
 - **Authors:** Khoa Pham, Sindhuja Penchala, Jiacheng Li, Andy Perkins, Noorbakhsh Amiri Golilarz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medical image segmentation plays an important role in computer aided diagnosis, treatment planning, and disease monitoring. U-Net has been widely used for biomedical image segmentation because of its encoder decoder structure and skip connections. However, conventional convolution based U-Net models may have limited ability to capture long range dependencies and global contextual information, which can affect performance in complex segmentation tasks. This paper presents a comparative study of five U-Net based architectures: U-Net 3D, Residual U-Net, Attention U-Net, UNETR, and Swin UNETR. The models are evaluated on two benchmark datasets: BraTS 2023 for brain tumor segmentation and DRIVE for retinal vessel segmentation. Experimental results show that Swin UNETR achieves the best overall performance, with Dice scores of 0.8965 on BraTS 2023 and 0.8078 on DRIVE. The results suggest that transformer based U-Net variants are effective for segmentation tasks requiring global contextual modeling, while residual learning remains useful for fine structure segmentation. This study provides practical insights into model selection for medical image segmentation across volumetric MRI and retinal imaging tasks.
### Title:
          SamatNext v0.2-B: An Exploratory Study of RMS-Normalized Hybrid Decoders for Curriculum Retention in Small Code Models
 - **Authors:** Samat Zharassov
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Standard autoregressive Transformer decoders can often exhibit substantial forgetting under sequential fine-tuning on shifting curriculum distributions. This technical report evaluates SamatNext v0.2-B, an experimental 356M-parameter hybrid sequence decoder that alternates Differential-Attention-style layers with DeltaNet-inspired simplified linear-state mixer layers using RMS normalization and output scale calibration. We study the model under a controlled staged Python code curriculum and compare it with a parameter-matched Transformer baseline. In this setting, SamatNext v0.2-B achieves a 100.0% pass rate on the controlled Stage 5 holdout while retaining 98.8% of adjacent Stage 3 semantic behavior and reaching 12.0% on the Stage 2E early syntax holdout. The strongest Transformer baseline reaches 97.6% on Stage 5 but retains only 6.0% of Stage 3 behavior. Both architectures remain weak on long-horizon early-stage retention, so the result should be interpreted as evidence of an altered retention/plasticity tradeoff in this controlled setting, not as a general solution to catastrophic forgetting. Code, model specifications, evaluation scripts, and result tables are provided for independent verification.
### Title:
          SCENIC: Semantic-Conditioned Edge-Aware Neural Framework for Structured IoT Command Generation
 - **Authors:** Luke Ztz Hu, Hongbing Lang, Songping Mai
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Edge Internet of Things (IoT) agents are often constrained by memory capacity, privacy requirements, communication latency, and recurring inference cost. Current smart-home assistants commonly rely on API-level command interfaces or cloud-based language models that remain difficult to deploy on edge devices. This paper addresses edge IoT command generation as a many-to-one structured output task, where multiple natural-language instructions map to the same canonical command string for deterministic smart-home parsing. To support this setting, we propose Semantic-Conditioned Edge-Aware Neural Framework for Structured IoT Command Generation (SCENIC), an end-to-end framework covering model architecture selection, Smart Home Instruct data generation, triplet-loss contrastive supervised fine-tuning, pruning and quantization, and deployment-oriented export. We evaluate sub-0.2B-scale transformer backbones, which are, to the best of our knowledge, among the smallest language-model backbones studied for edge IoT structured command generation. On Smart Home Instruct-Bench, the strongest dense decoder-only row reaches 99.0% EM@1, while the encoder-decoder model retains stronger high-sparsity behavior. A representative pruned INT8 encoder-decoder export preserves 91.0% EM@1 and 99.0% EM@5 while reducing exported model size by 25.38%. TensorRT profiling of the NVIDIA 2:4 sparse encoder export further shows up to 1.8x encoder-component speedup, indicating that the selected encoder-decoder deployment path can retain structured command accuracy under edge-oriented compression while hardware acceleration evidence remains component-level. The SCENIC code and experimental artifacts are open sourced to support reproducibility.
### Title:
          All Routes Lead to Collapse
 - **Authors:** K. R. Balasubramanian
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Attention sinks, representation collapse, and norm stratification are treated as transformer-specific pathologies. We show they are not specific to attention: they are what content-based routing does under a fixed similarity metric. We give a reframing identity: softmax attention is Boltzmann-weighted aggregation over Euclidean distances with constant key norms, so its score omits a $-\|k\|^2$ term and is blind to key magnitude. This predicts that any router whose metric is ill-matched to its representations should compensate, by concentrating its routing and collapsing the routed representations. We test it on routers that score and aggregate over different axes: softmax attention over tokens (nine pretrained transformers), graph attention over nodes, a selective state-space model and a recurrent mixer over time, and learned residuals over depth. All develop the same signature, and two within-model ablations show it is caused by the routing mechanism rather than by incidental dynamics. The form is contingent, set by the strength of the positional brake each router carries alongside its content score; we sweep that brake and move the onset across its whole range. The mechanism is not contingent, and it does not require norm stratification: a router with norm-normalized keys concentrates just the same. We do not claim these models implement Riemannian geometry; the geometric view is a diagnostic that names the inadequacy of the flat, norm-blind metric.
### Title:
          Structured Hyperedge Adaptation for Parameter-Efficient Fine-Tuning of Vision Transformers
 - **Authors:** Edwin Kwadwo Tenagyei, Lei Wang, Ugochukwu Ejike Akpudo, Jun Zhou, Yongsheng Gao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Parameter-efficient fine-tuning (PEFT) has become a practical solution for adapting large pretrained vision transformers (ViTs) to downstream tasks while updating only a small subset of parameters. However, existing adapter-based methods perform adaptation independently for each token, implicitly assuming that token refinements should be learned in isolation. This token-wise formulation overlooks the structured relationships among tokens that naturally arise in visual scenes, potentially leading to redundant updates and spatially inconsistent feature refinement. In this work, we revisit the design of parameter-efficient adapters and propose to perform adaptation in hyperedge space rather than token space. We introduce HyperAdapter, a hypergraph-based adapter architecture that enables structured, group-aware adaptation through soft token routing. HyperAdapter constructs a soft hypergraph over ViT tokens using prototype-based assignments, aggregates token features into latent hyperedge representations, applies lightweight bottleneck adaptation at the hyperedge level, and diffuses the resulting updates back to tokens via the hypergraph incidence structure. This design injects an explicit structural inductive bias into PEFT while preserving the modularity and efficiency of standard adapters. Extensive experiments across diverse visual benchmarks demonstrate that structured hyperedge adaptation consistently outperforms strong PEFT baselines under comparable parameter budgets, with particularly pronounced gains on tasks requiring structured reasoning. Our results suggest that the choice of adaptation space is a critical yet underexplored dimension in parameter-efficient transfer for ViTs.
### Title:
          Cross-Layer Intrusion Detection in 5G O-RAN: Gains and Limits of Fusing Radio Telemetry with Network Flow Records
 - **Authors:** Hamed Fard, Ilya Komarov, Gerhard Wunder
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open RAN disaggregation enables joint analysis of DU radio telemetry and CU-side network-flow records, motivating cross-layer intrusion detection. We evaluate whether fusing these two modalities improves over each individually across seven architectures, using run-disjoint splits over ten seeds on a live 5G O-RAN dataset. Radio features match or outperform network flows on ROC-AUC and run-level detection rate across all architectures. Fusion yields selective ROC-AUC gains but at a one-percent false-positive operating point improves detection rate only for GRU and Transformer, reducing it for the other five models. The benefit is confined to architectures where both single-modality detection rates fall below 0.75. A DoS-to-Benign confusion of 27 to 46 percent persists across all 42 tested configurations of architecture, modality, and window duration, pointing to a limitation in the tested windowed statistical aggregation rather than in model capacity. Code is publicly available.
### Title:
          BLENDS: Bayesian Learning-Enhanced Deep Smoothing for GNSS-Denied Environments
 - **Authors:** Nadav Cohen, Itzik Klein
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Maintaining accurate navigation during GNSS outages remains a significant challenge for autonomous systems relying on low-cost inertial sensors. While classical smoothing methods, such as the two-filter smoother and Rauch-Tung-Striebel smoother, exploit measurements collected before and after an outage, their performance remains limited by the accuracy of conventional GNSS measurements. This paper presents Bayesian learning-enhanced navigation with deep smoothing (BLENDS), a transformer-based framework that augments Bayesian smoothing with learned covariance adaptation and state correction. The proposed method preserves the statistical foundations of Bayesian estimation while leveraging data-driven learning to improve navigation accuracy. Evaluations on the quadrotor dataset with GNSS outages demonstrate that BLENDS consistently outperforms both model-based smoothers, achieving up to 25.6% improvement in the position root mean square error while also reducing estimation uncertainty. Furthermore, BLENDS learns to compensate for the systematic bias between conventional GNSS positioning and RTK ground truth, enabling accuracy beyond that achievable with conventional GNSS measurements alone. The results demonstrate the potential of learning-enhanced Bayesian smoothing for resilient and high-accuracy navigation in GNSS-challenged environments.
### Title:
          Deep Learning-Based Sign Language Recognition from Videos and Cross-Lingual Translation to Indian Vernaculars
 - **Authors:** Chandranath Adak, Ramesh Nandipalli
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sign language is a primary mode of communication for the global deaf and hard-of-hearing community, yet automated tools that recognize sign gestures from video and translate them into natural language text remain limited, particularly for low-resource Indian languages. We present a two-stage deep learning pipeline that (i) classifies short sign language video clips into English word labels using a fine-tuned VideoMAE video transformer, and (ii) translates the predicted English label into Hindi, Telugu, and Bengali using Meta AI's No Language Left Behind (NLLB-200) multilingual translation model. The classification model is fine-tuned on a 13-class subset of the AI4Bharat Indian Sign Language video corpus from IIT Madras, processing 16-frame clips sampled uniformly from each video at 224 x 224 resolution. Under a small-scale academic setting (13 classes, 197 clips, 80-20 split), the fine-tuned model reaches 99% training accuracy and 78% validation accuracy after 15 epochs. We provide a per-class breakdown via a confusion matrix and classification report, identify the dominant failure modes (confusable adjective pairs such as ugly, deaf, blind, hat, and dress), and describe a Streamlit-based inference demo that takes a user-uploaded video and returns the predicted English label alongside its Hindi, Telugu, and Bengali translations. We discuss the scope, limitations (small label set, isolated-word rather than continuous signing, single-signer style sensitivity, ambiguity of single-word machine translation), and directions for future work, including expanding to sentence-level generation and a larger vocabulary. Code is released to support reproducibility.
### Title:
          NegAS: Negative Label Guided Attention and Scoring for Out-of-Distribution Object Detection with Vision-Language Models
 - **Authors:** Yingjie Zhang, Shuai Li, Peng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Out-of-Distribution (OOD) detection is essential for ensuring the robustness and reliability of object detection systems deployed in safety-critical applications. While prior research has mainly focused on uni-modal detectors or vision-language model (VLM) based classifiers, the potential of VLM-based object detectors in OOD scenarios remains underexplored. In this work, we take the first step toward building OOD object detection methods upon VLMs. We identify two challenges specific to VLM detectors: (i) their text-guided attention enhances foreground with ID labels but treats background uniformly, leaving potential OOD regions unexploited for separating in-distribution (ID) from OOD instances; and (ii) their sigmoid-based multi-label outputs are incompatible with softmax-based OOD scores, calling for scoring functions consistent with VLM probabilistic outputs. Hence, we introduce Negative Label Guided Attention and Scoring (NegAS). To address (i), we propose a negative label guided attention module (NegA), where LLM-generated, visually-similar but semantically-different negative labels are used to guide attention toward potential OOD background regions. To address (ii), we introduce a novel sigmoid-based OOD scoring function (NegS) that leverages both ID and negative labels, producing strong responses for ID instances and suppressed responses for OOD ones. Extensive experiments demonstrate that our approach improves OOD detection performance by a large margin while maintaining ID accuracy, e.g., reducing the FPR95 by 11.4% on the COCO dataset and 25.5% on the OpenImages dataset compared to the baseline model. While initially designed for dense VLM detectors like YOLO-World, we successfully adapt NegAS to Grounding DINO, a query-based VLM transformer and achieve significant improvements, demonstrating the generalizability of our framework.
### Title:
          Venice-H1: Failure-Aware Query Re-Ranking with Multi-Scale Grid Signatures for Referring Image Segmentation
 - **Authors:** Nicolò Savioli
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern Referring Image Segmentation (RIS) systems generate multiple candidate masks per expression but rely on a simple heuristic--typically the argmax detection score--to select the final output. We identify query selection as a failure-case bottleneck: although heuristic selection succeeds on 82-93% of samples, the residual 7-18% of failures dominate the error budget, leaving a best-query selection gap of 3-11% mIoU. We introduce Venice-H1, a lightweight, backbone-decoupled post-hoc re-ranking module that encodes each candidate through multi-scale grid signatures--compact spatial descriptors pooled onto 4x4, 8x8, and 16x16 grids--and feeds them to a Transformer-based re-ranker with a Failure Gate (ROCAUC 0.78-0.82) that intervenes only when the default choice is likely suboptimal. Instantiated on DeRIS-L and DeRIS-B, Venice-H1 achieves delta_fail of +1.40 and +0.89 mIoU with strictly positive 95% CIs on all 16/16 (split, backbone) pairs and harmful-switch rates below 0.53%. Zero-shot transfer to medical referring segmentation (MS-CXR, M3D-RefSeg-2D) yields +1.16 and +0.51 mIoU without RIS-backbone fine-tuning. The module adds approximately 11.3M parameters and under 1 ms latency.
### Title:
          HiMatch-AD: DINOv3-driven Hierarchical Matching for Training-free Medical Anomaly Detection
 - **Authors:** Jiayu Huo, Jingyuan Hong, Meng Zhou, Liyun Chen, Le Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Anomaly detection is essential for medical image analysis, where pathological regions often appear as rare deviations from normal anatomical structures. While training-based methods have achieved promising performance, they require task-specific optimization and extensive normal data, which limits scalability across modalities and institutions. Training-free approaches offer greater flexibility by leveraging pretrained visual representations, yet existing methods typically rely on simple nearest-neighbor retrieval and naive aggregation strategies, which may fail to capture hierarchical semantics and ignore the reliability of multiple anomaly responses. In this work, we propose HiMatch-AD, a DINOv3-driven hierarchical matching framework for training-free medical anomaly detection. Our method first retrieves semantically relevant normal references via dual-branch matching that jointly considers global CLS-token similarity and patch-level representations. Hierarchical anomaly maps are then generated across multiple transformer stages by comparing clustered normal features with query representations. To robustly aggregate anomaly responses, we introduce a unified uncertainty-based fusion mechanism that adaptively weights maps according to their reliability. The entire framework operates without any task-specific training. Extensive experiments on the BMAD benchmark, including brain MRI, liver CT, and retinal OCT datasets, demonstrate that HiMatch-AD consistently outperforms both training-based and DINO-based state-of-the-art methods, which highlights the effectiveness of multi-level matching and uncertainty-aware fusion for scalable medical anomaly detection.
### Title:
          Automated sign detection across the Electronic Babylonian Library: A large-scale dataset and end-to-end cuneiform OCR pipeline
 - **Authors:** Wentao Che, Esteban Garcés Arias, Asim Niaz, Andreas Bender, Enrique Jiménez
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning to read cuneiform tablets is an extremely demanding task; consequently, of the roughly half million excavated tablets, only a small fraction has been analysed by Assyriologists. Computer vision offers a promising avenue for decipherment but requires large, densely annotated datasets. To address this limitation, the largest annotated cuneiform sign dataset to date is used, and a Deformable Detection Transformer (DETR)-based object detection model is evaluated under two class granularities of 173 and 106 classes. The proposed system integrates automatic tablet-side extraction, heuristic line grouping, and n-gram-based textual similarity evaluation to bridge visual sign detection and textual structure, and achieves consistent improvements of up to 28-37% over prior work on COCO-style detection metrics. At inference, the method is applied to 87,668 tablet fragments from the Electronic Babylonian Library (eBL) corpus, producing nearly 2.9 million sign detections. Although the approach operates without linguistic priors and remains sensitive to tablet damage and layout variability, it provides a scalable and interpretable foundation for corpus-wide cuneiform analysis and supports future integration with multimodal and linguistic modelling frameworks.
### Title:
          Identifying Quality Indicators in Student Self-Reflections in Software Engineering
 - **Authors:** Matthew Minish, Matthias Galster, Fabian Gilson
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Context: Reflection is a fundamental skill in software engineering education, particularly in project-based courses where students learn through extended group work and need to develop their ability to reflect iteratively throughout their work. For students to benefit from reflection, their written reflections need to be assessed so that feedback can guide and improve their reflective practice. However, manually assessing written reflections to guide reflections is time-consuming, and often results in broad, non-specific feedback for a student to improve. Objective: This study builds on reflective writing frameworks to produce an eight-indicator scheme for assessing student reflections in software engineering. Furthermore, this study validates an automated classifier for assessing reflections against the framework, enabling scalable and structured feedback whilst reducing instructor workload. Method: We adapted existing reflection frameworks through iterative refinement to create our eight-indicator framework. Three annotators labelled student reflection texts, establishing moderate to reliable inter-rater agreement. We then trained and evaluated multiple encoder-only transformer models and compared them with decoder-only large language models using zero-shot prompting. Results: The fine-tuned RoBERTa model achieved the strongest performance, substantially outperforming decoder-only models in both accuracy and speed. The classifier demonstrated human-level agreement on most indicators whilst enabling near-instantaneous classification. We provide two model variants optimised for different assessment priorities. Conclusions: Our fine-tuned encoder-only models enable efficient automated assessment of reflective writing. The framework and automated classifier offer a means to provide timely, structured feedback on student reflections in software engineering.
### Title:
          moBERTo: A Modern Encoder for Portuguese via Continued Pretraining of ModernBERT
 - **Authors:** Thiago Laitz, Thales Sales Almeida, João Guilherme Alves Santos, Giovana Kerche Bonás
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Encoder-only transformer models remain essential for production NLP pipelines. We introduce moBERTo, a Portuguese adaptation of ModernBERT obtained through continued pretraining of the ModernBERT-base checkpoint on 60 billion tokens (5 epochs over a 12-billion-token corpus curated from FineWeb2 and filtered with educational and STEM classifiers). We preserve the original architecture, including rotary positional embeddings, alternating local-global attention, flash attention, and unpadding. We evaluate moBERTo across information retrieval (including long-context retrieval at up to 8,192 tokens), document classification, named entity recognition, and natural language understanding. Our best variant, which combines a Portuguese tokenizer with subword-matching embedding transfer and long-context post-training, achieves the highest average reranking nDCG@10 across three Portuguese retrieval benchmarks and the best results on PLUE-PT. Through ablation studies, we show that (i) continued pretraining is strongly preferable to training from scratch, particularly for preserving long-context capabilities; (ii) tokenizer adaptation improves token-level tasks but degrades long-context retrieval; (iii) a dedicated long-context post-training phase at 8,192 tokens further improves reranking and NER; and (iv) encoder-only architectures remain competitive with larger decoder-only alternatives for discriminative tasks. We publicly release the model weights at this https URL and training data at this https URL on Hugging Face.
### Title:
          Text Dictates, Music Decorates: Energy-based Attention for Editable Dance Motion Generation
 - **Authors:** Seong Jong Yoo, Siyuan Peng, Felix Gu, Stratis Aloimonos, Cornelia Fermüller
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Choreographic motion generation poses unique challenges for AI, demanding precise semantic control over complex, temporally structured, and expressive full-body dynamics. While existing models can synthesize motion from music, they remain largely black boxes. Conversely, attempting to condition generation on both text and music frequently leads to modality collapse, where dense acoustic rhythms overwhelm sparse semantic text prompts, destroying user controllability. To resolve this spatial-temporal conflict, we propose STREAM (Structural-Temporal Rhythmic Energy-based Attention for Motion), a modality-decoupled diffusion transformer. STREAM strictly separates conditioning pathways: global text semantics dictate the kinematic structure via Adaptive Layer Normalization (AdaLN), while a novel Bimodal Energy-Based Attention Module (BEAM) routes these features to the musical beat without overwriting the semantics. We further introduce Motorica++, a newly curated dataset enriched with domain-specific dance vocabulary and frame-level semantic annotations from existing Motorica dataset. Additionally, to rigorously quantify zero-shot editability, we propose the Exchange Evaluation Protocol and Editable Dance Score (EDS). Through extensive experiments, STREAM achieves state-of-the-art alignment between motion and music while perfectly preserving choreographic semantics, positioning AI not merely as a reactive synthesizer, but as a controllable, collaborative partner for artistic direction. The source code and datasets are available at this https URL.
### Title:
          One-Step Flow Matching for Generative Modeling of Path-Dependent Physical Fields
 - **Authors:** Yijing Zhou, Jasmin Jelovica
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Engineering, Finance, and Science (cs.CE); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physical simulations for intricate geometries with path-dependent constitutive models face difficulties due to the enormous computational cost they require. Recently, the emergence of generative AI models, which succeed in image and video synthesis tasks, has provided a promise to further improve simulations. Although U-Net-based denoising diffusion probabilistic models (DDPMs) have been adopted for elastic stress field generation, they typically require hundreds of sampling steps, and applications of generative models to path-dependent, e.g. plastic, stress fields remain very limited. In this work, we propose a novel flow matching (FM) model based on a transformer backbone for high-resolution path-dependent stress field generation with stochastic loading-unloading paths and geometry. The proposed model operates within the latent space of a variational autoencoder (VAE) and formulates the simulation of plastic fields as a video synthesis task, directly generating the stress fields across all time steps. Meanwhile, we design a non-Gaussian source distribution for flow matching, such that crossings among conditional transport paths are reduced during training. This enables our model to generate satisfactory samples in one step without relying on distillation. In addition, we introduce token-level loading embeddings and two auxiliary networks to further enhance the model performance in path-dependent simulation. The results demonstrate that, even with a limited training dataset, our model can accurately generate high-resolution path-dependent fields. It is much more computationally efficient than finite element analysis, providing a speedup of 6 to 7 times over FEM on CPUs and approximately two orders of magnitude speedup on consumer-grade GPUs.
### Title:
          Visual Geometry Transformer in the Wild: Distractor-Free 3D Reconstruction
 - **Authors:** Tianbo Pan, Xingyi Yang, Shizun Wang, Xinchao Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current end-to-end multi-view 3D reconstruction methods achieve impressive results, but rely on a restrictive static assumption: the scenes is entire distractor-free with perfect cross-view geometry. This reliance on idealized inputs causes even the most advanced methods to fail in real-world settings, where transient distractors and occlusions present. To address this, we propose Visual Geometry Transformer in the Wild (VGTW), an end-to-end framework for robust reconstruction from inconsistent views. At its core, we isolate and suppress distractor-affected regions while preserving the consistent components across views. Specifically, we introduce a Distractor-aware Training (DAT) strategy that separates clean features from distractor-contaminated ones in the attention mechanism while enforcing feature consistency across images. To enable this, we train the model with an auxiliary mask prediction head, using supervision from a new dataset we collected with pixel-level distractor masks. The resulting VGTW model is a feed-forward network that directly outputs clean, distractor-free point clouds. Remarkably, it requires no additional 3D supervision, remains computationally efficient, and is compatible with existing pipelines. Extensive experiments validate our approach, demonstrating state-of-the-art performance and robust generalization in diverse, real-world scenarios.
### Title:
          Discovering Crystal Structure Prediction Algorithms with an AI Co-Scientist
 - **Authors:** Kiyoung Seong, Nayoung Kim, Sungsoo Ahn
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce Human-AI Co-discovery system (HACO) for scientific algorithm discovery through cross-domain search and sparse human steering. Starting from the goal of generating crystal structures from chemical compositions, HACO searched across generative modeling methodologies from multiple fields and identified MaskGIT, a masked generative model from vision, as a promising framework for crystal structure prediction (CSP). HACO instantiated this masked formulation as a discrete token model of crystal structure; guided by sparse high-level human objectives, it then added crystallographic symmetry tokens, space group stratified sampling for polymorph coverage, and sub-bin coordinate refinement, yielding the Masked Generative Crystal Transformer (MaskGXT). On the MP-20 polymorph split, MaskGXT reaches 79.06% match-everyone-to-reference (METRe) accuracy, compared with 70.87% for the strongest evaluated baseline. MaskGXT also attains the best match rate on standard MP-20 and MPTS-52 CSP benchmarks. These results provide evidence that, in domains offering cheap, fast, and well-aligned validation, transfer-guided interactive AI co-scientists can contribute to scientific algorithm discovery by identifying transferable modeling principles and combining them with targeted human domain guidance.
### Title:
          SpotAttention: Plug-In Block-Sparse Routing for Pretrained Long-Context Transformers
 - **Authors:** Huzama Ahmad, Se-Young Yun
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long contexts have become standard in pretrained LLMs, yet they remain expensive to run: prefill compute grows quadratically with sequence length, and every decode step re-reads a key-value cache that grows linearly with it. Sparse attention cuts these costs by attending only to a relevant subset of past tokens, but selecting that subset is itself expensive. We present SpotAttention, a lightweight selector that attaches to a frozen pretrained transformer and learns by KL distillation to estimate its attention distribution. The selector picks the top-K keys each query attends to, and because its estimate is a calibrated distribution, a dual top-p rule reads the per-query, per-layer budget directly from it. Across Qwen3 (dense, 4B-32B) and Qwen3.5 (hybrid linear/full attention, 4B-9B), SpotAttention matches dense accuracy at contexts up to 128K tokens, eight times the training length. Decode at L=128K runs 3.9x faster than FlashAttention and 1.8x faster than Twilight, the strongest training-free baseline. Quantizing the selector's K-cache to INT4 or FP4 microscale shrinks it 3.5x at no accuracy cost.
### Title:
          Controllable Texture Tiling with Transformed RoPE-Enhanced Diffusion Models
 - **Authors:** Junrong Huang, Zhiyuan Zhang, Rui Tang, Hongbo Fu, Jnig Liao
 - **Subjects:** Subjects:
Graphics (cs.GR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Realistic integration of user-specified textures into scene images is a fundamental task in computer graphics and image editing. While existing material transfer and reference-guided inpainting methods can edit surface appearances, they often fail to address the specific requirements of texture tiling. This task necessitates precisely repeating a reference pattern according to user-defined parameters such as frequency, orientation, and scale. Furthermore, current generative approaches often struggle to maintain the structural fidelity of the reference texture, limited by either destructive pixel-level resampling or the lack of fine-grained spatial information in semantic image encoders, and they frequently fail to preserve the coherent lighting and geometry of the original scene. In this paper, we propose a novel framework for controllable and high-fidelity texture tiling based on Diffusion Transformers. Our approach introduces two key technical innovations to decouple spatial manipulation from content generation. First, we propose a Coordinate-Transformed Rotary Embedding mechanism. By applying 2D affine transformations directly to the relative positional embeddings between the target latent and the image condition, we achieve precise control over tiling patterns without explicit pixel warping, thereby utilizing the full information of the reference condition without degradation. Second, a Disjoint Attention Mask is employed to shield reference features from semantic leakage. This preserves structural integrity while seamlessly blending the synthesized texture with the scene's original lighting and geometry. Extensive experiments demonstrate that our method outperforms state-of-the-art baselines in both control accuracy and texture fidelity.
### Title:
          ScalingAttention: Discovering Intrinsic Sparse Attention Topology for Video Diffusion Transformers
 - **Authors:** Ruiliang Zhou, Xuecheng Wu, Kang He, Guangyun Han, Bin Liu, Qinqin Chen, Wende Xu, Qingjie Zhao, Chengru Song
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Diffusion Transformers (DiTs) have revolutionized high-fidelity video generation, their reliance on 3D full attention creates a quadratic computational bottleneck. Existing sparse methods face a dilemma: dynamic pruning suffers from prohibitive runtime overhead and memory fragmentation, while static heuristics fail to capture fine-grained dependencies. In this work, we propose ScalingAttention, a training-free framework grounded in a key inductive bias: while individual activations are input-dependent, the high-mass attention regions for each head rapidly converge to a stable, prompt-agnostic Intrinsic Sparse Topology. This topology is weight-encoded, scale-invariant, and efficient to extract. ScalingAttention decouples topology discovery from sparsity control via: (1) WEST (Weight-Encoded Sparse Topology), which extracts a robust block-sparse prior mask offline to eliminate runtime search; (2) FAST (Fidelity-Aware Sensitivity Tuning), which adaptively tunes head-wise sparsity based on diffusion fidelity requirements. To ensure practical acceleration, we co-design a hardware-aligned bit-wise block-sparse kernel. Experiments on Wan2.1 show up to 1.90X end-to-end speedup with superior fidelity, establishing a new Pareto frontier over state-of-the-art baselines.
### Title:
          SPAR: Semantic-Pixel Self-Alignment and Adaptive Routing for Unified Multimodal Models
 - **Authors:** Hongxiang Li, Hongxu Chen, Chenyang Zhu, Xiaoshuang Huang, Jiayin Cai, Xiaolong Jiang, Yao Hu, Long Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Large Language Models (MLLMs) have achieved remarkable success in visual understanding but remain constrained in visual generation due to the fundamental feature discrepancy between semantic perception and pixel-level reconstruction. Bridging this gap requires overcoming two core challenges: endowing semantic encoders with high-fidelity reconstruction capabilities, and effectively aligning generative models with semantic spaces without relying on external teachers. To this end, we propose a novel unified multimodal framework featuring \textbf{S}emantic-\textbf{P}ixel self-alignment and \textbf{A}daptive \textbf{R}outing (\textbf{SPAR}). First, to reconcile semantic perception with pixel-level reconstruction, we introduce an asymmetric dual-stream unified tokenizer. A lightweight semantic stream anchors discriminative features, while a Transformer-augmented pixel stream recovers fine-grained visual details into a unified compact latent space. Second, to eliminate external dependencies, we propose a self-aligned generation paradigm that natively leverages this optimized tokenizer as an internal alignment teacher for the diffusion model. Furthermore, to facilitate flexible multimodal interaction within this unified space, we introduce Dynamic Token Routing, which enables each token to adaptively aggregate multi-layer MLLM features based on its distinct semantic demands. Extensive experiments demonstrate that SPAR establishes the state-of-the-art for unified architectures, achieving exceptional generation and reconstruction quality while preserving foundational visual understanding capabilities.
### Title:
          Three-Step Hierarchical Transformer for Multi-Pedestrian Trajectory Prediction
 - **Authors:** Raphaël Delécluse, Hazem Wannous, Laurent Grisoni, Laurent Guimas
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pedestrian trajectory prediction requires modeling temporal dynamics, multimodal cues, and social interactions in crowded environments. Existing methods often address these factors separately or entangle them in costly attention blocks, limiting scalability, flexibility, and interpretability. We propose a three-step hierarchical Transformer that explicitly separates temporal encoding, multimodal fusion, and scene-level interaction reasoning. Lightweight GRU summaries enable efficient cross-modal attention, while social attention over time--agent tokens captures inter-pedestrian influences at manageable cost. Experiments on JTA, JRDB, and the Pedestrians and Cyclists in Road Traffic dataset show state-of-the-art performance on real-world datasets (JRDB, Urban) and competitive results on JTA. Ablation and qualitative analyses confirm the contribution of each stage and the model's ability to anticipate complex behaviors such as early turning.
### Title:
          LUMINA-26: Low-Light Understanding for Modeling and Interpreting Night-time Actions
 - **Authors:** Aman Kumar Pandey, Anil Singh Parihar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-light human action recognition remains a challenging problem due to poor illumination, amplified noise, motion ambiguity, and diverse real-world scenes. Existing low-light datasets often lack sufficient action diversity, capture realism, or balanced class distribution, limiting the development of robust models. To address this, we introduce LUMINA-26: Low-Light Understanding for Modeling and Interpreting Night-time Actions, comprising 6,784 clips across 26 action classes, recorded from 22 subjects across 20 indoor and outdoor locations under naturally occurring low-light conditions. We also propose Illumi-Net: An Illumination-Adaptive Mixture-of-Experts Network, which leverages video-level illumination cues to guide adaptive enhancement and transformer-based spatio-temporal feature extraction, with expert-conditioned decision fusion. Our method surpasses previous state-of-the-art performance on ELLAR (Top-1: 55.13%, Top-5: 78.87%) and establishes a strong baseline on LUMINA-26 (Top-1: 75.95%, Top-5: 93.58%), offering a practical benchmark for future low-light action recognition research.
### Title:
          The Fractal Neural Operator: Overcoming Spectral Bias in Chaotic Attractors via Prime-Harmonic Weierstrass Encodings
 - **Authors:** Kanishk Awadhiya
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Analysis of PDEs (math.AP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning models, particularly Transformers and Neural Operators, exhibit a well-documented "spectral bias," effectively acting as low-pass filters that smooth out high-frequency information. While benign in fluid dynamics, this bias is catastrophic for Chaotic Dynamical Systems, where the underlying strange attractor is characterized by fractal geometry and infinite spectral density. We introduce the Fractal Neural Operator (FNO), a novel architecture that utilizes a non-resonant prime number basis to approximate continuous dynamical systems. Unlike geometric encodings ($2^k$), which suffer from spectral gaps and resonance, our Harmonic Weierstrass Encoder injects infinite spectral resolution into the latent space. We demonstrate that FNO extends the valid prediction horizon of the Lorenz-63 system to 347 Lyapunov times, exceeding state-of-the-art Reservoir Computing baselines by a factor of 2.3x. These results suggest that "chaos" is not inherently unpredictable to neural networks, but rather requires non-differentiable, fractal embedding manifolds.
### Title:
          MambaADv2: Evolving Duality-enhanced State Space Model for Unsupervised Anomaly Detection
 - **Authors:** Xiaobin Hu, Haoyang He, Bo Yin, Yu He, Lei Xie, Jiangning Zhang, Yu-Gang Jiang, Shuicheng Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While recent advancements in anomaly detection have demonstrated the efficacy of CNN- and Transformer-based approaches, these architectures face inherent limitations: CNNs struggle to capture long-range dependencies, whereas Transformers suffer from quadratic computational complexity. Consequently, Mamba-based architectures have attracted considerable attention, as they successfully combine superior long-range dependency modeling with linear computational complexity. By critically rethinking the structural evolution across the Mamba lineage 1-3 series, this paper proposes MambaADv2, a framework tailored for multi-class unsupervised anomaly detection. MambaADv2 comprises a pre-trained encoder and a Mamba-inspired decoder, equipped with Duality-enhanced State Space (DSS) modules across multiple scales. The proposed DSS module effectively models both global dependencies and local representations by integrating parallel-cascaded Hybrid State Space (HSS) blocks and frequency-enhanced convolution operations. The structure of the Hybrid State Space (HSS) block is tailored by following the SSD-based Mamba lineage and incorporating Mamba3-style position-aware state-space modeling, leveraging the dual computational paths of linear recurrence and parallel matrix formulation to model local continuity and global contextual comparison, thereby better serving the core anomaly detection objective of precisely reconstructing normal representations while magnifying anomalous deviations. Additionally, we propose a semantics-adaptive progressive scanning strategy that decays scanning complexity along the feature pyramid.
### Title:
          Privacy-Preserving Person Re-Identification from Temporal Sequences with Transformer and Hungarian Optimization
 - **Authors:** Raphaël Delécluse, Hazem Wannous, Laurent Guimas
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Person re-identification (Re-ID) is a crucial task in surveillance and human behavior analysis, often used in public spaces such as transport hubs. Traditional RGB-based Re-ID methods raise privacy concerns and are highly sensitive to lighting variations and occlusion. In this paper, we propose a novel Re-ID approach that leverages depth images, which inherently obscures facial and other identifiable features, making it a privacy-preserving solution. Our method addresses the association problem between multiple views of individuals by applying the Hungarian algorithm, optimizing the matching process through minimization of the global cost across the distance matrix. We further enhance the approach by introducing temporal sequences of frames as input to a Transformer encoder architecture, which exploits both RGB and depth modalities. This architecture captures dynamic movement patterns, improving feature extraction and re-identification accuracy. Additionally, we employ batch hard triplet loss to enhance discriminative feature learning by focusing on the hardest samples. We evaluate both depth-only and RGB-D models on several top-view datasets, including TVPR2, GODPR, and BIWI RGBD-ID. Our results demonstrate that depth-only re-identification can achieve competitive performance compared to state-of-the-art methods, as measured by standard metrics such as Cumulative Matching Characteristics (CMC) and Mean Average Precision (mAP), while prioritizing privacy preservation.
### Title:
          SteerVTE: Seamless Video Text Editing with Style and Glyph Control
 - **Authors:** Kai Zeng, Moran Li, Zhengwei Wang, Yingchen Yu, Yiheng Lin, Ruichuan An, Ming Lu, Qi She, Wentao Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual text editing aims to precisely modify text in images and videos while preserving stylistic consistency and visual realism. Despite significant advances in the image domain, video text editing remains largely unexplored: it is a localized task demanding stroke-level precision within small text regions, which compounds the challenges of cross-frame accuracy, temporal coherence, and stylistic fidelity. We introduce SteerVTE, a unified framework that \underline{\textbf{steer}}s a frozen video diffusion model to perform precise \underline{\textbf{V}}ideo \underline{\textbf{T}}ext \underline{\textbf{E}}diting through style and glyph control. Built on a frozen diffusion transformer, SteerVTE attaches a lightweight text context adapter with two complementary modules: a style encoder capturing the original text's visual attributes, and dual-granularity glyph encoders encoding the target text at both the line and character levels. To overcome the inherently weak text rendering priors of video foundation models, we further propose a glyph-aware spatial-focal loss and a three-stage progressive training curriculum that scales from image to video data. To support large-scale training, we also develop an automatic synthesis pipeline and construct SteerVTE-1M, a dataset of one million triplets spanning diverse scenes, fonts, and stylistic effects. Extensive experiments demonstrate that SteerVTE substantially outperforms existing video editing baselines across text accuracy, style consistency, and temporal coherence.
### Title:
          RT-DocLayout: Real-Time End-to-End Document Layout Analysis with Reading Order in the Wild
 - **Authors:** Cheng Cui, Tingquan Gao, Xueqing Wang, Changda Zhou, Hongen Liu, Ting Sun, Yubo Zhang, Zelun Zhang, Jiaxuan Liu, Manhui Lin, Yue Zhang, Suyin Liang, Yiqing Xiang, Yi Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate document layout analysis remains a critical bottleneck for document parsing systems, due to the intricate coupling among heterogeneous document layout elements, geometric distortions (\eg, paper warping and bending, perspective variations), and reading order within diverse layout structures. Existing approaches typically rely on fragmented multi-stage pipelines or computationally heavy generative Transformer architectures, leading to error propagation and limited efficiency. In this paper, we present RT-DocLayout, a highly efficient end-to-end framework for document layout analysis, designed as a front-end for document parsing tasks. The proposed model unifies classification, detection, pixel-level segmentation, and reading order prediction for layout elements within a single 33M-parameter architecture. Built upon the RT-DETR, our key contribution is a unified multi-task formulation within a single query-based decoder that simultaneously classifies, regresses bounding box, generates masks, and constructs relationship to reason reading order. By jointly learning geometric and structural representations, RT-DocLayout introduces multi-task optimization that substantially improves robustness under real-world document distortions. Extensive experiments on public benchmarks demonstrate state-of-the-art performance in document layout analysis while maintaining real-time inference speed(132.1 FPS). When coupled with downstream OCR engines, RT-DocLayout significantly improves full-document reconstruction quality, providing a scalable and practical foundation for real-world document intelligence systems.
### Title:
          Superhuman AI for Generals.io Using Self-Play Reinforcement Learning
 - **Authors:** Matej Straka, Viliam Lisý, Martin Schmid
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a superhuman AI agent for this http URL, a real-time strategy game that requires both long-horizon planning and short-term tactics under strong imperfect information. Trained for four days on 4x NVIDIA H200 GPUs, our agent reaches #1 on the public 1v1 leaderboard of over 5,000 human players, leading the second-ranked player by the same margin that separates second place from 25th, and beats the two top-ranked humans head-to-head with a combined 199-70 record across 269 ladder matches. A key enabler is a JAX-native simulator that reaches tens of millions of frames per second on a single GPU, roughly a 10,000x speedup over the prior simulator. On top of this, we train a vision transformer policy end-to-end by self-play with a policy-gradient loop and sparse win/loss reward, using top-advantage sample filtering and an exponential moving average of the policy parameters. Taken together, our findings highlight what matters, and what does not, once a fast simulator removes the data bottleneck.
### Title:
          Convergence of Gradient Descent for General Neural Network Architectures Beyond the NTK Regime
 - **Authors:** Yuqing Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Dynamical Systems (math.DS); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training dynamics is central to understanding neural networks, yet its theoretical analysis remains difficult even for simple architectures and becomes substantially more challenging for general modern architectures. In this paper, we propose a convergence framework for analyzing gradient descent (GD) dynamics under a broad family of neural network architectures and datasets beyond the neural tangent kernel (NTK) regime. The framework is formulated at the level of network blocks and covers architectures including pre-normalized multi-layer transformers. More precisely, under mild assumptions, we prove that for almost all initializations, GD with regular learning rates converges to the neighbourhood of a stationary point. This is mainly proved by establishing an iterate-dependent PL-type inequality through analyticity and measure-zero arguments, and by proving Lipschitz smoothness along the GD trajectory through polynomial generalized smoothness and a local relaxed dissipative condition. We further interpret the theorem under Xavier initialization and practical architectural scaling, showing that the learning rate scale depends on the depth and effective bottleneck dimensions rather than the largest width. Finally, we derive structural nondegeneracy implications for residual connections and function composition, and provide a generic characterization of global minimizers within our framework.
### Title:
          Energy-Based Transformers as Predictors of Reading Difficulty
 - **Authors:** Jakub Dotlacil, Ece Takmaz
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer language models have become established tools for modeling human sentence processing, with measures such as surprisal and attention entropy serving as effective predictors of reading difficulty that together capture complementary aspects of processing load. Here, we explore a related class of transformer models: energy-based transformers, which provide a principled formal link to associative memory models, bringing processing research into direct contact with the broader literature on Hopfield networks and dense associative memory. To our knowledge, this is the first exploration of an energy-based transformer measure in computational psycholinguistics. Across reading-time corpora (Natural Stories, UCL eye-tracking, UCL self-paced reading), the energy measure is a robust predictor of reading times, providing significant fit beyond surprisal in all three. In a controlled experiment on relative clause processing, energy at a single layer captures the well-known object/subject asymmetry. We find evidence that it subsumes effects attributable to both attention entropy and surprisal, suggesting that energy may serve as a single unified predictor where multiple complementary measures have previously been required.
### Title:
          HyperQuant: A Rate-Distortion-Optimal Quantization Pipeline for Large Language and Diffusion Models
 - **Authors:** Yuval Domb, Hadar Sackstein, Tomer Solberg
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present HyperQuant (Hadamard, optimallY Packing, Entropy Rice-coding), a unified post-training quantization pipeline for the weights and the KV cache of large language and diffusion transformers. Across a suite of self-contained experiments (Table 1), HyperQuant outperforms the recent HIGGS scheme at every operating point from 3 to 5 bits per scalar (bps) on weights, and beats both TurboQuant and OCTOPUS on KV quantization down to 1.7 bps. Beyond the LLM setting, HyperQuant quantizes the 19B-parameter LTX-2 DiT video model with no observable per-frame artifacts. End-to-end on an H100 at 4 bps, HyperQuant compresses the linear weights ~3.9x and the KV cache ~3.79x at near-lossless quality. HyperQuant combines four known ideas into a single construction: (i) a per-tile Randomized Hadamard Transform that makes the per-coordinate distribution of weights and activations approximately Gaussian; (ii) quantization to a low-dimensional optimal lattice (E8, D4, A2, or Z); (iii) lossless bit-stripping and near-entropy-optimal variable-length Rice coding of the lattice indices; and (iv) bias-correction methods for the KV cache that keep the reconstruction unbiased under inner products, preserving attention semantics. We further integrate the pipeline with 8-bit and 4-bit Tensor-Core MMA paths (fp8-e4m3, int8, nvfp4, mxfp4), and find that int8 beats fp8 on the post-RHT lattice output. Project page: this https URL
### Title:
          MeshFlow: Mesh Generation with Equivariant Flow Matching
 - **Authors:** Qi Sun, Kiyohiro Nakayama, Jing Nathan Yan, Qixing Huang, Alexander Rush, Leonidas Guibas, Gordon Wetzstein, Jing Liao, Guandao Yang
 - **Subjects:** Subjects:
Graphics (cs.GR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Meshes are among the most common 3D scene representations, but directly generating meshes is challenging because the representation contains important symmetries, including permutation invariance of faces and vertices. MeshFlow learns to generate triangle meshes directly as triangle soups, avoiding the need to serialize meshes into long autoregressive sequences. We adopt equivariant optimal-transport flow matching models that respect the key symmetries of triangle soups: arbitrary permutations of faces and permutations of the vertices within each face. Toward this goal, we propose a simple yet effective modification to the Diffusion Transformer architecture, resulting in a scalable network capable of modeling a velocity field while maintaining the desired equivariance. We further introduce an optimal-transport-based training objective that improves convergence by eliminating supervision signals that violate these symmetries. MeshFlow achieves mesh quality comparable to state-of-the-art autoregressive mesh generators while providing about an 18$\times$ speedup during inference. Project page is at this https URL.
### Title:
          UniverSat: Resolution- and Modality-Agnostic Transformers for Earth Observation
 - **Authors:** Yohann Perron, Guillaume Astruc, Nicolas Gonthier, Clement Mallet, Loic Landrieu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViT) dominate computer vision. However, their reliance on rigid patch projectors hinders transfer to Earth Observation (EO), where input modalities, scales, and resolutions vary widely. We introduce UniverSat, a ViT-style backbone built around a Universal Patch Encoder that maps patches from arbitrary spatial, spectral, and temporal resolutions, and from both optical and non-optical sensors, into a shared embedding space with a shared set of weights. This enables training a single model on heterogeneous multimodal corpora via self-supervision, yielding robust, sensor-agnostic spatial features. We validate this approach with strong results across classification and segmentation on standard EO benchmarks from GeoBench, PANGEABench, and SpectralEarth. Our code and models are available at this https URL.
### Title:
          Scaling State-Space Models from Lines to Paragraphs: An Ablation of Mamba-based OCR
 - **Authors:** Merveilles Agbeti-Messan, Pierrick Tranouez, Stéphane Nicolas, Clément Chatelain, Thierry Paquet
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end OCR increasingly relies on autoregressive sequence models, where the quadratic cost of Transformer attention limits efficient transcription of long, paragraph-level text. State-Space Models (SSMs) such as Mamba offer linear-time decoding and have recently been shown to match Transformer accuracy on printed historical lines, but their behavior as sequences grow from short lines to full paragraphs, and their generalization to handwriting, remain poorly understood. We study how a Mamba-based OCR recognizer scales from lines to paragraphs. We first conduct a systematic exploration of its four core hyperparameters (decoder depth, state dimension, expansion factor, and connector depth) on synthetic paragraphs from 100 to 1,000 characters, identifying the recurrent state dimension and the expansion factor as the dominant levers for long-sequence accuracy. We then compare the recognizer against a Transformer baseline trained under an identical protocol. On clean synthetic paragraphs, both models stay below 1% CER at every length while the SSM runs 1.4 to 4.5 times faster, the speedup growing with sequence length. On real handwriting, however, the SSM lags clearly behind: it reaches 8.2% CER on IAM lines and 10.0% on IAM paragraphs, against 4.2% and 3.5% for the Transformer baseline. Through controlled experiments we show that a substantial part of this gap stems from data scarcity rather than from an intrinsic architectural limit: the autoregressive SSM decoder is markedly data-hungry on long sequences. Our study clarifies when SSMs are a practical choice for large-scale document transcription and when they are not.
### Title:
          The Energy Consumption of Transformer Fine-Tuning: A Roofline-Inspired Scaling Model
 - **Authors:** Mansour Zoubeirou a Mayaki
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Hardware Architecture (cs.AR); Computation and Language (cs.CL); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based models underpin modern natural language processing but incur rapidly growing computational and energy costs. As training scales in both model size and parallelism, accurately predicting energy consumption has become critical for sustainable and cost-aware system design. We present a framework for modeling the energy consumption of Transformer training on multiple GPUs. Using controlled architectural sweeps of BERT models, we relate measured energy to lightweight proxies for compute, memory traffic, and hardware efficiency. Inspired by roofline models, our approach incorporates a speedup-based hardware-efficiency factor that captures the effects of tensor parallelism and fully sharded data parallelism. We derive a scaling law model that accurately predicts training energy across heterogeneous configurations.
### Title:
          A Generative Model for Closed-Loop Microsimulation of Signalized Intersections
 - **Authors:** Yash Ranjan, Rahul Sengupta, Anand Rangarajan, Sanjay Ranka
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traffic microsimulators rely on hand-crafted behavior models that reproduce aggregate flow but miss the heterogeneous interactions between vehicles at signalized intersections. Learned trajectory predictors capture richer interactions but are short-horizon and tend to be unstable when run in closed loop. We present Enactor, an actor-centric generative model for closed-loop intersection microsimulation. The model focuses on vehicles; pedestrians are included as context that can influence vehicle decisions but not predicted. Dynamic actors and lane polylines are encoded in polar coordinates referenced to the intersection center. A transformer with separate spatial and temporal attention blocks predicts a distribution over each actor's next-step motion ($s$, $\alpha$). Training uses a closed-loop curriculum so the model is exposed to its own predictions. We evaluate Enactor in two regimes. In a 4000-second simulation-in-the-loop test at two intersection geometries, Enactor controls every dynamic vehicle against a continuously refreshing actor set rather than the fixed cohort that learned trajectory predictors are usually evaluated against. It recovers the SUMO data generator's speed and travel-time distributions with KL divergence over an order of magnitude lower than a recent transformer baseline on travel time, and substantially lower on speed (roughly $5\times$ lower at Site 1), and reduces red-light violations relative to the same baseline by more than an order of magnitude. An ablation isolates the leader rear-bumper feature as the change with the largest effect on intersection-aware safety metrics. We also evaluate on real-world field data and apply the same architecture to naturalistic vehicle trajectories from a fish-eye camera at a signalized intersection and evaluate it on multi-horizon predictive tasks. Enactor outperforms a constant-velocity baseline at every horizon evaluated.
### Title:
          The Topology of Ill-Posed Questions: Persistent Homology for Detection and Steering in LLMs
 - **Authors:** Guangyu Jiang, Sizhe Tang, Mahdi Imani, Tian Lan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ill-posed questions, including ambiguous, underspecified, or contradictory queries, may admit no valid answer or multiple plausible answers, posing a challenge for large language models (LLMs). Existing approaches largely analyze ill-posedness through model outputs and often focus on specific subclasses. We investigate whether diverse sources of ill-posedness can be represented within a unified topology of LLM internal states and whether this structure can be used to steer response behavior. We model the contextual hidden states of prompt tokens at each transformer layer as a point cloud and characterize its geometry using finite zero-dimensional persistent homology. Each layer is summarized by three compact descriptors: mean finite lifetime, normalized lifetime entropy, and largest-lifetime concentration. Concatenating these descriptors across layers yields a topology representation of the question. We further introduce topology-conditioned activation steering, which retrieves topologically similar examples and constructs query-specific activation interventions that encourage source-aware clarification or abstention. Across three open-weight LLMs, topology features consistently outperform prompt-based and pooled-hidden-state baselines for ill-posedness classification, improving average accuracy from \(67.4\%\) to \(78.9\%\) on AmbigQA, from \(79.9\%\) to \(88.5\%\) on SituatedQA, and from \(57.6\%\) to \(69.6\%\) on CLAMBER 9-way classification. Topology-conditioned steering increases the average total acceptable response rate from \(61.4\%\) to \(70.6\%\) and grounded acceptable responses from \(11.9\%\) to \(16.4\%\). These results show that persistent homology provides both an interpretable representation of ill-posedness and an effective mechanism for targeted response steering.
### Title:
          Scaling Linear Mode Connectivity and Merging to Billion Parameter Pretrained Transformers
 - **Authors:** Tianyi Li, Zhiqiang Shen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Linear mode connectivity (LMC) provides a promising foundation for understanding and merging independently trained neural networks, but existing methods typically optimize the interpolation path from only one model endpoint, limiting their scalability and effectiveness for large pretrained transformers. We propose a novel and scalable framework for enabling LMC-based model merging to {\em billion-parameter pretrained transformers}. Our method applies properly parameterized functionality-preserving weight transformations to align functionally equivalent solutions, and introduces a dual learning procedure in which both models jointly learn their corresponding transformations toward a shared linear interpolation path. This bidirectional optimization substantially reduces interpolation barriers and enables more reliable merging across large-scale architectures. Empirically, we show that our approach achieves near-zero loss barriers on WikiText for language models with medium-sized parameters, representing, to our knowledge, the first demonstration of near-barrier-free linear connectivity at this scale. In the vision domain, ViT-L maintains above 69\% ImageNet top-1 accuracy throughout the interpolation path, while modern billion-parameter LLMs exhibit only small loss barriers. These results suggest that properly resolving parameter symmetries enables large pretrained Transformers to be connected and merged through simple linear paths with substantially improved interpolation performance. Code: this https URL .
### Title:
          Vera: A Layered Diffusion Model for Content-Preserving Video Editing
 - **Authors:** Hongkai Zheng, Ta-Ying Cheng, Benjamin Klein, Yisong Yue, Zhuoning Yuan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video diffusion models have enabled remarkable progress in video generation and editing. However, content preservation remains a core challenge: existing methods regenerate every pixel and often alter elements that should remain unchanged, such as characters or background scenes. We introduce Vera, a layered diffusion framework for content-preserving video editing. Instead of regenerating the entire video, Vera generates an edit layer along with an alpha matte for compositing with the source video, separating creative editing from content preservation by design. To encourage coherent composition with the source video, we extend the text-to-video DiT into a Mixture-of-Transformers (MoT) architecture, with separate DiTs for each layer that interact through joint self-attention. To support the training of Vera, we further construct a high-quality layered dataset with accurate alpha mattes, diverse scenes and dynamics, and visual effects. Across our quantitative benchmark and human preference study, Vera outperforms leading open-source video editing models in content preservation while remaining competitive in edit quality, using 486K frames of layered training data.
### Title:
          DiT-Reward: Generative Representations for Text-to-Image Reward Modeling
 - **Authors:** Yuanming Yang, Guoqing Ma, Bo Wang, Yuan Zhang, Wei Tang, Chenyi Li, Haoyang Huang, Nan Duan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Can representations learned for image generation also support the evaluation of generated images? We study text-to-image reward prediction as a downstream task of generative representation learning. To this end, we introduce DiT-Reward, which converts a pretrained text-to-image Diffusion Transformer into a reward model by processing near-clean image latents and aggregating text-conditioned image representations across transformer layers. Under the same training data mixture as HPSv3, DiT-Reward outperforms HPSv3 on all four evaluated preference benchmarks, reaching 85.6% on HPDv2 and 77.6% on HPDv3. When the generative backbone is frozen, a lightweight learned head can still extract meaningful preference predictions from its representations. Probing across depth further reveals that downstream reward performance is strongest in the middle-to-late layers and benefits from combining representations across different stages. We also observe consistent positive scaling with generative backbone capacity. Finally, when used to optimize Stable Diffusion 3.5 Large with Flow-GRPO, DiT-Reward outperforms HPSv3 along the matched training trajectory, with particularly clear gains in realism. Direct latent scoring also achieves a 1.65x inference speedup over HPSv3 with comparable peak memory. These results show that pretrained generative DiTs provide transferable representations for reward modeling and policy optimization.
### Title:
          Pose Anything Anywhere:Model-free Object Poses from Arbitrary References
 - **Authors:** Hongli Xu, Jiaqi Hu, Junwen Huang, Boyang Zhong, Peter KT Yu, Nassir Navab, Benjamin Busam, Slobodan Ilic
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Estimating the 6D pose of unseen objects is a fundamental yet challenging problem for open-world robotics and embodied perception. Model-based methods are accurate but depend on CAD assets or heavy onboarding, while most model-free approaches are still limited to pairwise single-anchor matching and thus fail under occlusion and large viewpoint changes with low query-reference overlap. Therefore, we present PANY, a unified model-free framework that seamlessly supports both RGB and RGB-D inputs, operates on one or sparse pose-free reference views, and generalizes effectively to novel objects. Built on a multi-view transformer geometry backbone, PANY moves beyond pairwise matching by learning view-consistent geometry and cross-view alignment cues that remain stable under wide baselines and limited overlap. When additional unposed assist views are available, PANY aggregates them via pose-graph canonical registration to increase geometric coverage and reinforce the final pose. Extensive experiments show that PANY achieves state-of-the-art performance across multiple benchmarks, substantially outperforming existing model-free methods, improving pose accuracy by +12% on YCB-V and over +20% on LM-O. Furthermore, PANY consistently performs well under both single-reference and sparse-reference settings, demonstrating strong robustness in real-world environments.
### Title:
          Muown Implicitly Performs Angular Step-size Decay
 - **Authors:** Florian Hübler, Kai Lion, Antonio Orvieto, Niao He
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Matrix-aware optimizers such as Muon and Muown have recently shown strong empirical performance for pre-training Transformers. In particular, Muown separates each weight matrix into row magnitudes and an un-normalized direction variable, updating the former with Adam and the latter with Muon. We show that the directional update of Muown is equivalent to a Riemannian step on the normalized directions, while the magnitude of the un-normalized parameterization only modulates the angular step size. This explains the step-size stability of Muown and suggests making the angular step size explicit. The resulting method, AngularMuown, optimizes directly over the normalized directions and uses a schedulable angular multiplier decoupled from the radial magnitude update. AngularMuown improves over Muown and, at the time of writing, a preliminary version is leading the per-optimizer category of the modded nanoGPT speedrunning competition. Further experiments on Qwen2-0.5B, and 1.1B parameter mixture-of-experts models confirm the algorithm scales beyond small models. An implementation of the algorithm is available at this https URL
### Title:
          Tapered Language Models
 - **Authors:** Reza Bayat, Ali Behrouz, Aaron Courville
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern language models, including transformer, recurrent, and memory-based variants, share a common chassis: a stack of identical layers in which parameters are allocated uniformly across depth. This is a default inherited from the original transformer and largely unchanged since, yet a growing body of evidence suggests that layers contribute non-uniformly to the final output, with later layers refining the residual stream rather than transforming it. We ask whether parameter capacity should reflect this asymmetry. Our controlled experiment shows that, under a fixed budget, allocating more capacity to earlier layers and less to later layers improves perplexity over a uniform-width baseline, while the reverse allocation hurts. Building on this result, we introduce Tapered Language Models (TLMs), an architectural principle in which a parameter-bearing component is monotonically tapered across depth under a fixed total budget. MLPs are the natural site for this instantiation: they dominate parameter count across all modern LM families and expose width as a single, clean axis of variation. Across three model scales and four architectures (Transformer, Gated Attention, Hope-attention, and Titans), tapering MLP width via a smooth cosine schedule consistently improves perplexity and downstream benchmark performance over uniform baselines, at no additional parameter or compute cost. These findings establish depth-aware capacity allocation as a simple, architecture-agnostic axis of language model design, a free lever hidden in plain sight.
## Keyword: autonomous driving
### Title:
          MAGNIFIED: RL Fine-tuning of Multimodal Large Language Models for Motion Planning
 - **Authors:** Letian Chen, Yiren Lu, Justin Fu, Yichen Xie, Runsheng Xu, Jyh-Jing Hwang, Ben Sapp, Drago Anguelov
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-modal Large Language Models (MLLMs) have demonstrated remarkable capabilities in semantic understanding and common sense reasoning, making them promising candidates for solving planning problems in autonomous driving. However, the next-token text prediction objectives traditionally used in pre-training and supervised fine-tuning (SFT) of MLLMs may fall short of fulfilling the planning objectives for autonomous vehicles. The next-token prediction objective merely encourages per-token imitation in text, often irrespective of multi-step consequences and the alignment with crucial planning considerations such as giving space to other road actors. To overcome these limitations, we propose a reinforcement learning fine-tuning (RLFT) approach, MAGNIFIED, that aligns the MLLM-based driving agent with planning objectives by learning from token-level rewards. By mapping a sequence of predicted tokens to corresponding vehicle trajectories and learning from planning rewards, MAGNIFIED optimizes for the true planning objectives rather than focusing solely on token prediction accuracy, enabling the model to refine its understanding of the planning task beyond simple imitation. We validate our approach on the Waymo Open Motion Dataset with a novel setup incorporating rasterized birds-eye views and tokenized trajectories as inputs and planning-oriented outputs. An initial SFT phase establishes a strong baseline in outputting plan trajectories as sequences of X-Y coordinates in text, while subsequent RL fine-tuning substantially enhances planning performance relative to the SFT baseline (demonstrating over a 10.5% reduction in overlap rate and a 38.9% reduction in off-road rate), underscoring the potential of RLFT on MLLMs to achieve vehicle planning that is better aligned with compliant, comfortable, and efficient driving.
### Title:
          ARGUSTRACK: A Multi-View Annotation System for Multi-Object Tracking
 - **Authors:** Hao Vo, Duc Nguyen, Ngan Le
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-Camera Multi-Target (MCMT) tracking has emerged as a critical capability for applications ranging from autonomous driving to animal behavior monitoring. While recent advances have yielded sophisticated tracking algorithms, the availability of annotated multi-view data remains a significant bottleneck. Existing annotation tools predominantly support single-camera workflows or rely on LiDAR sensors, making cross-view labeling tedious and impractical for camera-only setups. We present ARGUS-TRACK, a multi-camera annotation system that addresses these limitations by enabling annotators to work directly on a bird's-eye-view (BEV) plane. Given calibrated camera parameters, a single ground-plane annotation is automatically projected into 2D bounding boxes across all relevant views, inherently ensuring identity consistency without manual cross-view alignment. To further accelerate the labeling process, ARGUSTRACK incorporates two complementary mechanisms: a Temporal Aware module that propagates annotations from preceding frames to initialize new ones, requiring only minor positional adjustments; and a Multi-camera Semi-annotation module that leverages off-the-shelf 2D detectors combined with foot-point estimation to automatically generate candidate BEV positions for annotator verification. We evaluate ARGUSTRACK through a pilot study on multi-camera broiler tracking and demonstrate that it substantially reduces annotation time compared to conventional single-camera labeling workflows.
### Title:
          One Image is All You Need: Agentic One-Shot Image Generation via Text-Based World Models for Long-Tail Spatial Perception
 - **Authors:** Keqin Zeng, Shuting Su, Shihao Lin, Ziyue Li, Rui Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Graphics (cs.GR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable spatial decision automation, such as autonomous driving and maritime surveillance, critically depends on robust visual perception. However, real-world spatiotemporal data exhibits severe heterogeneity, often manifesting as extreme long-tail distributions for safety-critical scenarios. This data scarcity induces dataset shift that degrades detection performance and pose safety risks. While synthetic data generation offers a potential solution, existing generative approaches, such as diffusion models and Generative Adversarial Networks (GANs), often lack explicit spatial grounding and structural constraints, resulting in spatial and physical inconsistencies in generated scenes. To address these challenges, we introduce WMGen-v1, an agentic text-based world model framework for long-tail spatial data generation. WMGen-v1 employs a Large Vision-Language Model (LVLM) to construct a structured scene representation from a single reference image, while a Large Language Model (LLM) performs guidance-based scene expansion under physical plausibility and commonsense constraints. Subsequently, conditioned on the structured semantic representations produced by this reasoning process, a diffusion model generates diverse and physically grounded long-tail training data. Experiments on internal industrial datasets, ROADWork, and LaRS benchmarks demonstrate that WMGen-v1 outperforms baseline approaches. Notably, detectors trained solely on WMGen-v1 synthetic data approach real-only performance on aggregate dataset-level metrics, highlighting its potential to alleviate long-tail data scarcity for downstream spatial perception.
### Title:
          BadDreamer: Transferable Backdoor Attacks against Video World Models for Autonomous Driving
 - **Authors:** Zhe Shuai, Xiaopeng Xie, Yikun Zeng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video world models are increasingly used in autonomous driving to forecast future scene evolution and provide future-aware spatio-temporal representations for downstream action prediction. In perception-to-action pipelines, these representations can directly influence ego-vehicle waypoint planning, making the learned future dynamics a critical security-sensitive component. Despite their promise, the training-time security risks of autonomous-driving video world models remain largely unexplored. We present BadDreamer, a transferable spatio-temporal backdoor attack that targets the perception side of this pipeline. Unlike conventional backdoors that manipulate image labels, prompt outputs, or action supervision, BadDreamer poisons the learned transition dynamics of a video world model. It constructs trigger-erasure sequences in which an oncoming yellow delivery rider is visible in the observed context frames but erased from the future frames. After fine-tuning on a small fraction of such sequences, the compromised world model learns a hidden conditional association: when the physical trigger appears, it hallucinates a future where the rider disappears and the road appears clear. We further show that this corrupted future-aware representation can transfer to the downstream action module without directly modifying ego-trajectory labels, inducing unsafe non-evasive waypoint predictions. Our experiments instantiate this attack on a representative open-source perception-to-action pipeline, revealing a representation-level safety risk in autonomous-driving video world models and highlighting the need for backdoor-aware validation beyond clean generation quality.
### Title:
          A Stitch in Time Saves Nine: Preserving Policy Compatibility Under Perception Updates in End-to-End Autonomous Driving
 - **Authors:** Yueyuan Li, Yifei Xiao, Mingyang Jiang, Xiang Zuo, Songan Zhang, Ming Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end autonomous driving systems tightly couple perception and decision-making through latent representations. Consequently, updates to perception models can alter these representations and degrade the performance of downstream policies that remain fixed. Existing solutions typically rely on policy retraining or architectural decoupling, both of which incur substantial computation and validation costs. In this paper, we formulate the model stitching problem for end-to-end autonomous driving and test the hypothesis that policy compatibility can be preserved through lightweight latent-space alignment. We study low-complexity model stitching methods, including linear and convolutional stitchers, for restoring compatibility between updated perception modules and frozen downstream policy modules. Experiments demonstrate that stitching effectively preserves downstream driving behavior under diverse perception updates, including changes in random initialization, sensor configuration, and training domain. In the most challenging cross-domain setting from nuScenes to CARLA, convolutional stitching retains over 91\% of the no-shift driving score while reducing adaptation time from \SI{22.18}{h} to \SI{0.91}{h}. These results suggest that model stitching provides an effective and computationally efficient alternative to retraining or fine-tuning for maintaining end-to-end autonomous driving systems. The model will be open-sourced upon paper acceptance at this https URL to support further research and development in autonomous driving.
### Title:
          FAST: A Framework for Aligned Sampling and Training in Parallel Reinforcement Learning for Autonomous Driving
 - **Authors:** Bonan Wang, Letian Tao, Bin Shuai, Jiaxin Gao, Wenxin Zhao, Wei Xiong, Kehua Sheng, Bo Zhang, Yang Guan, Shengbo Eben Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep reinforcement learning is pivotal for closed-loop autonomous driving yet remains constrained by severe bottlenecks in sampling efficiency. Standard parallel sampling mitigates this but suffers from the straggler effect, where the premature termination of a single environment necessitates a synchronized batch re-initialization, leading to suboptimal sample utilization and prohibitive re-initialization latency. To address this, we propose FAST, a synchronous parallel framework tailored for closed-loop simulation. Specifically, FAST employs Dynamic Parallel Sampling Alignment (DPSA) to maintain vectorization synchronization by extending terminated episodes via virtual continuation, thereby decoupling the sampling loop from individual terminations. By dynamically triggering global truncation based on the termination rate of parallel clips, FAST effectively eliminates the bottleneck of premature resets without sacrificing data diversity. Furthermore, to strictly preserve theoretical consistency, we incorporate a Scaled Mask-Padding Optimization (SMPO) that leverages validity masking and adaptive loss normalization to nullify the bias from auxiliary padding data. Empirical evaluations demonstrate that FAST achieves at least a 1.78 times wall-clock speedup over the single-clip baseline while preserving statistical unbiasedness.
### Title:
          A DVDrive Approach for doScenes Instructed Driving Challenge
 - **Authors:** Zijian Fu, Xiangyang Chu, Mengshi Qi, Huadong Ma, Guanghao Zhang, Wei Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Instruction-conditioned trajectory prediction is an emerging problem in autonomous driving, where a model predicts the future ego trajectory not only from visual scene context and historical motion, but also from a natural-language maneuver instruction. This paper presents our submission to the doScenes Instructed Driving Challenge, built upon OmniDrive, a vision-language-action driving agent with 3D perception, reasoning, and planning capabilities. We adapt OmniDrive to the doScenes setting by training it on instruction-annotated nuScenes scenes and generating a 6-second ego trajectory represented by 12 future waypoints. To improve multi-view visual grounding, we further introduce a DVPE-style divided-view perception module into the OmniDrive perception head. Instead of attending globally to all camera features, the proposed module groups query features and image tokens into divided local view spaces and performs visibility-aware cross-attention within each view. This design reduces irrelevant cross-view interference and helps the model better align language instructions with local driving-relevant visual evidence. The code is publicly available at: this https URL.
### Title:
          Active Inference as the Test-Time Scaling Law for Physical AI Agents
 - **Authors:** Omar Hashash, Christo Kurisummoottil Thomas, Walid Saad, Merouane Debbah, Karl Friston, Adeel Razi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, a novel test-time scaling law for physical artificial intelligence (AI) agents is introduced. This scaling law enables physical AI agents to reason with their world models to generalize in unforeseen scenarios at test time. The derived scaling law is grounded in the first principle of active inference, which equips agents with the general objective to survive in the real world, under which their specific task objectives are subsumed. Active inference achieves this by providing the reasoning to resolve prediction errors that arise when the agent encounters unforeseen situations outside its training distribution, enabling generalization in non-stationary environments. The proposed scaling law captures this by dynamically updating the agent's policy with this reasoning at test time. This policy update is modeled as a soft Bayesian inference process in which beliefs about the policy are updated using the reasoning that reduces expected prediction errors under allowable policies as a likelihood. The resulting posterior policy admits a biological interpretation, recovering the scaling mechanism that engages the brain's basal ganglia and prefrontal cortex at test time. To solve this analytically intractable problem, a variational inference solution minimizing free energy bounds is developed. This solution extends to enable learning beyond training by reinforcing new instances, resolved at test time, in both the policy and world model. Unlike existing scaling laws constrained by model size and training data, the derived solution scales with the continuous real-world experience of a physical AI agent. Simulation results on an autonomous driving task demonstrate that the proposed solution outperforms model-free Q-learning and model-based Bayesian reinforcement learning, achieving robust generalization to unforeseen scenarios while improving inference efficiency by over 36%.
### Title:
          Intend, Reflect, Refine: An Adaptive Multimodal Reflection Framework for Autonomous Driving
 - **Authors:** Zisheng Chen, Yuping Qiu, Jianhua Han, Tao Tang, Xiuwei Chen, Likui Zhang, Ying-Cong Chen, Hang Xu, Xiaodan Liang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent Vision-Language-Action (VLA) models have advanced end-to-end autonomous driving by incorporating reasoning for better interpretability and planning quality. However, most existing approaches directly generate the final trajectory without explicitly examining its future consequences, which limits their reliability in complex and dynamic environments. To address this limitation, we propose IRR-Drive (Intend, Reflect, Refine), an adaptive multimodal reflection framework for autonomous driving. Specifically, to tightly couple high-level reasoning with physical constraints, IRR-Drive first generates a preliminary textual intention and anticipates potential interactions by predicting future semantic bird's-eye view (BEV) representations. This dual-modality (Text + BEV) reflection space explicitly models anticipated scene evolution, enabling the model to rigorously self-correct and refine its initial intent before generating the final trajectory. Furthermore, to balance planning performance and computational efficiency, we construct reflection-oriented training data and design an adaptive reflection reward, enabling the model to adaptively select its reasoning mode according to scene complexity. Instead of using reasoning primarily as an auxiliary interpretation, IRR-Drive directly integrates an adaptive reflection mechanism into the planning framework, enabling grounded, decision-aware trajectory correction that is driven by scene complexity. Our method achieves state-of-the-art performance on the NAVSIM benchmark in both PDMS and EPDMS. Extensive experiments demonstrate the effectiveness of our multimodal reflection framework and validate the efficacy of the proposed adaptive reflection strategy.
### Title:
          Humanoid-OmniOcc: Stereo-Based Full-View Occupancy Dataset for Embodied AI
 - **Authors:** Xianda Guo, Bohao Zhang, Chenwei Huang, Shiyuan Chen, Ruilin Wang, Yiqun Duan, Cong Yang, Qin Zou, Wei Sui
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Occupancy prediction at voxel-level granularity is essential for safe robotic navigation and interaction in complex environments. Existing occupancy datasets, however, are predominantly designed for autonomous driving with vehicle-centric biases -- forward-facing cameras, far-field geometry, and static road priors -- limiting their applicability to embodied humanoid perception. We present Humanoid-OmniOcc, a large-scale panoramic stereo-based occupancy dataset tailored for humanoid robots. The dataset encompasses 15 diverse simulated indoor scenes and 5 real-world environments, yielding over 155K samples with broad scene and style diversity. Importantly, the dataset is designed around a Real2Sim2Real closed-loop paradigm: real sensor specifications drive physically accurate simulation, simulation produces large-scale annotated training data, and models trained in simulation are directly evaluated on real-world captures -- enabling iterative refinement of the sim-to-real pipeline. We further propose \textbf{H}umanoid \textbf{S}urround \textbf{S}tereo-guided \textbf{Occ}upancy model (Humanoid-OmniOcc) that exploits robust depth priors for accurate 2D-to-3D lifting. Extensive experiments show that Humanoid-OmniOcc consistently outperforms monocular baselines and generalizes well to both unseen simulated test scenes and real-world environments, validating the effectiveness of the Real2Sim2Real design. Code and data will be available upon acceptance at this https URL.
### Title:
          UECP: Uncertainty-Enhanced Collaborative Perception
 - **Authors:** Kang Yang, Tianci Bu, Peng Wang, Deying Li, Wen Jie, Yongcai Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Collaborative perception serves as a pivotal solution to enhance the perception capability of individual agents in autonomous driving, where a core challenge lies in seeking reliable evidence to quantify and weight the contribution of each participating agent. Existing methods typically rely on a confidence map, which is co-trained with the detection head, but it is inherently correlated with the detection results and thus fails to provide unbiased physical evidence. Furthermore, how to deeply integrate evidence into the cooperative fusion process remains an open question. To address these issues, this paper first proposes an uncertainty map, a physically grounded and unambiguous metric for evaluating perception quality. This map is directly supervised by real-time sensor signals, i.e., LiDAR point density, ensuring decoupling from detection noise and thereby providing physical scenario-aware evidence for weighting agent contribution. Based on this map, we develop the Uncertainty-Enhanced Collaborative Perception (UECP) framework, centered on the Uncertainty-Aware Pyramid Fusion (UAPF) module. UAPF uses a coarse-to-fine strategy, with two key components: Uncertainty-Weighted Downsampling (UWD) for high-fidelity feature preservation, and Uncertainty-Guided Residual Fusion (UGRF) to reinforce ego features, suppressing noise and ensuring robust fusion. Extensive experiments on real-world datasets show UECP outperforms state-of-the-art methods in effectiveness and robustness by embedding the uncertainty map into fusion. Code will be publicly available.
