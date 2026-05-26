# Showing new listings for Tuesday, 26 May 2026
## Keyword: SLAM
### Title:
          A Decentralized LiDAR-SLAM System with Certifiably Optimal Pose Graph Optimization
 - **Authors:** Baoshan Song, Feng Huang, Li-Ta Hsu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decentralized multi-robot LiDAR-SLAM is essential for collaborative missions but faces significant challenges in maintaining global consistency. Existing frameworks predominantly rely on local-search optimization or one-time coordinate alignment, which are prone to suboptimal convergence and long-term inconsistency, especially in large-scale or degenerate environments. To address these limitations, this paper presents the first decentralized LiDAR-SLAM system that integrates a state-of-the-art certifiably optimal Pose Graph Optimization (PGO) backend. By leveraging the Riemannian Block Coordinate Descent (RBCD) algorithm, our system ensures globally consistent trajectory estimation without requiring accurate initial guesses. Experimental results demonstrate that the proposed framework achieves superior robustness, improving trajectory RMSE by up to 48.9% compared to the state-of-the-art DiSCo-SLAM.
### Title:
          FusionCore: A 23-State Unscented Kalman Filter for IMU, Wheel Encoder, GPS, and Visual SLAM Fusion in ROS 2
 - **Authors:** Manan Kharwar (Independent Researcher, Hamilton, ON, Canada)
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present FusionCore, an open-source ROS 2 sensor fusion package that fuses IMU, wheel encoder odometry, GPS, and Visual SLAM pose into a single 100 Hz odometry stream using a 23-state Unscented Kalman Filter (UKF). The 23rd state is an online estimate of the wheel encoder's systematic yaw rate bias, identified through GPS heading cross-covariance and subtracted during GPS blackouts to reduce heading drift in coast mode. FusionCore also estimates gyroscope and accelerometer biases as explicit filter states, handles GPS natively in ECEF without a separate coordinate projection node, applies per-sensor Mahalanobis chi-squared outlier gating calibrated to measurement degrees of freedom, and adapts sensor noise covariance automatically from the innovation sequence. VSLAM pose fusion enables GPS-denied operation with any visual odometry or SLAM system, including automatic recovery from map reinitialization. We evaluate against robot_localization on twelve full-length sequences (55-92 min each) from the NCLT public dataset. FusionCore achieves lower Absolute Trajectory Error (ATE) on ten of twelve sequences, with improvements ranging from 1.2x to 22.2x on winning sequences. The robot_localization UKF diverges numerically on all twelve sequences. FusionCore is available at this https URL under the Apache 2.0 license.
### Title:
          G-DRAGON: Geospatial Reasoning and Dynamic Planning for Retrieval-Augmented Outdoor Navigation
 - **Authors:** Dongzhihan Wang, Yi Du, Jianan Sun, Yuan Xue, Yingchen Zhang, Bing Xiao, Chen Wang, Liang Xu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous ground robots operating in large-scale outdoor environments require both robust long-range navigation and fine-grained ''last-mile'' exploration. Current advances in visual-language navigation (VLN) work well at short-range tasks, lacking geospatial grounding for long-distance missions. Some OpenStreetMap (OSM)-based methods relying on cloud-based Large Language Models (LLMs) are prone to factual hallucination and cannot conduct ''last-mile'' exploration based on human instruction. To address these challenges, we present G-DRAGON, a retrieval-augmented framework for outdoor, open-world navigation. This framework maps natural-language commands to versioned, local OSM entities via generative retrieval based on lightweight LLM, yielding accurate coordinates for global route planning. A high-level planning module bridges global topological routes with the SLAM system, projecting geospatial waypoints into the robot's navigable frame. For the ''last mile," the framework transitions to frontier-based exploration and open-set semantic voxel mapping to localize open-vocabulary targets. Experimental results in simulation demonstrate our framework outperforms state-of-the-art baselines. Furthermore, we validate the system in unseen real-world urban environments on an Unmanned Ground Vehicle (UGV), successfully completing person-search missions with trajectories of up to 500m.
## Keyword: odometry
### Title:
          Vision-Guided Outdoor Flight and Obstacle Evasion via Reinforcement Learning
 - **Authors:** Shiladitya Dutta, Aayush Gupta, Varun Saran, Avideh Zakhor
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although quadcopters boast impressive traversal capabilities enabled by their omnidirectional maneuverability, the need for continuous pilot control in complex environments impedes their application in GNSS and telemetry-denied scenarios. To this end, we propose a novel sensorimotor policy that uses stereo-vision depth and visual-inertial odometry (VIO) to autonomously navigate through obstacles in an unknown environment to reach a goal point. The policy is comprised of a pre-trained autoencoder as the perception head followed by a planning and control LSTM network which outputs velocity commands that can be followed by an off-the-shelf commercial drone. We leverage reinforcement and privileged learning paradigms to train the policy in simulation through a two-stage process: 1) initial training with optimal trajectories generated by a global motion planner acting as a supervisory backbone, 2) further fine-tuning in a curriculum environment. To bridge the sim-to-real gap, we employ domain randomization and reward shaping to create a policy that is both robust to noise and domain shift. In outdoor experiments, our approach achieves successful zero-shot transfer to both obstacle environments and a drone platform that were never encountered during training.
### Title:
          Elevator-LIO: Robust LiDAR-Inertial Odometry for Multi-Floor Navigation under Elevator-Induced Non-Inertial Motion
 - **Authors:** Yifan Zhang, Yudong Huang, Yuchong Zhang, Changze Li, Haoran Liu, Ming Yang, Tong Qin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents Elevator-LIO, a LiDAR-inertial odometry framework designed to achieve continuous robot localization during elevator travel, thereby supporting cross-floor robotic tasks. To address the state-estimation problem in non-inertial frames, Elevator-LIO establishes a decoupled state-estimation model that separately models the robot motion relative to the elevator and the elevator motion itself, and embeds it into a mode-dependent iterated error-state Kalman filter framework. This framework degenerates to conventional LIO estimation in ordinary indoor environments, while enabling the propagation and constrained update of elevator-related states in elevator non-inertial environments, thereby achieving continuous and stable localization. An elevator mode manager detects elevator entry and exit events using LiDAR ranging statistics and estimated states, and introduces event-triggered zero-velocity and zero-acceleration updates when the elevator stops to suppress accumulated vertical drift. In addition, this paper adopts an adaptive voxel downsampling strategy to maintain a stable number of effective points under significant environmental scale changes. We conduct extensive experiments on 20 real-world sequences containing 79 elevator rides, including practical challenges such as large-scale spaces, long vertical travel, dynamic pedestrian interference, and mirror reflections. The results show that Elevator-LIO maintains continuous localization accuracy in all sequences, with terminal height error below 1 cm in 17 sequences. In contrast, existing representative localization systems perform poorly on these elevator sequences. Tests on the Hilti 2022/2023 datasets further show that the proposed method remains competitive in standard indoor scenarios. The project page is available at this https URL.
### Title:
          LC-Flow: Learning Local Continuous Optical Flow and Confidence from events
 - **Authors:** Gunwoo Jeon, Chaesong Park, Jongwoo Lim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event cameras capture brightness changes asynchronously with microsecond resolution, yet existing optical flow methods fail to fully exploit this temporal continuity. Frame-based approaches impose artificial accumulation latency and suffer from domain overfitting, while model-based local methods operate statelessly, discarding temporal history between predictions and yielding inaccurate flows. We propose \textbf{LC-Flow}, the first temporally continuous, learning-based optical flow estimator that operates purely from local events. At its core, a Continuous Local Recurrent Network maintains persistent hidden states per spatial grid, incrementally accumulating temporal context as events arrive. Unlike frame-based methods constrained to fixed accumulation windows, and unlike stateless model-based methods that recompute motion from scratch at each step, LC-Flow produces sparse local flow estimates at arbitrary timestamps with full motion history. To address the inherent ambiguity of local observations, we jointly learn a confidence score that quantifies the reliability of each prediction, explicitly handling event sparsity and the aperture problem. This confidence serves a dual role: filtering unreliable estimates for downstream tasks such as visual odometry, and providing principled weights for a multi-scale confidence-guided aggregation that reconstructs globally consistent flow from the sparse local outputs. LC-Flow achieves state-of-the-art performance among local methods on both MVSEC and DSEC, while the confidence-guided aggregation establishes a new overall state-of-the-art on the MVSEC benchmark, surpassing heavy frame-based networks that rely on global spatial priors.
### Title:
          RAMBA: 4D Radar Mapping by Bundle Adjustment
 - **Authors:** Jianzhu Huai, Yiwen Chen, Binliang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 4D radar is increasingly attractive for robotic mapping because it provides range, azimuth, elevation, and Doppler measurements while remaining robust in adverse visibility conditions. Although recent radar and radar--inertial odometry methods have achieved promising online state estimation performance, offline global map refinement for 4D radar remains underexplored. This paper presents RAMBA, a radar bundle-adjustment framework for globally consistent 4D radar mapping. Given initial poses and radar frames from a radar--inertial odometry front-end, RAMBA jointly refines radar frame states using covariance-weighted geometric residuals, IMU preintegration factors, and radar ego-velocity constraints. The geometric residuals extend pairwise GICP to a multi-frame optimization by forming voxel-based correspondences across selected frames and weighting each residual with point covariances. To improve robustness against drift and revisits, RAMBA enforces temporal consistency during correspondence formation while explicitly supporting loop-closure constraints. Experiments on the ColoRadar and SNAIL Radar datasets show that RAMBA improves map consistency and usually enhances trajectory accuracy over radar--inertial odometry and pose-graph optimization baselines.
### Title:
          FusionCore: A 23-State Unscented Kalman Filter for IMU, Wheel Encoder, GPS, and Visual SLAM Fusion in ROS 2
 - **Authors:** Manan Kharwar (Independent Researcher, Hamilton, ON, Canada)
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present FusionCore, an open-source ROS 2 sensor fusion package that fuses IMU, wheel encoder odometry, GPS, and Visual SLAM pose into a single 100 Hz odometry stream using a 23-state Unscented Kalman Filter (UKF). The 23rd state is an online estimate of the wheel encoder's systematic yaw rate bias, identified through GPS heading cross-covariance and subtracted during GPS blackouts to reduce heading drift in coast mode. FusionCore also estimates gyroscope and accelerometer biases as explicit filter states, handles GPS natively in ECEF without a separate coordinate projection node, applies per-sensor Mahalanobis chi-squared outlier gating calibrated to measurement degrees of freedom, and adapts sensor noise covariance automatically from the innovation sequence. VSLAM pose fusion enables GPS-denied operation with any visual odometry or SLAM system, including automatic recovery from map reinitialization. We evaluate against robot_localization on twelve full-length sequences (55-92 min each) from the NCLT public dataset. FusionCore achieves lower Absolute Trajectory Error (ATE) on ten of twelve sequences, with improvements ranging from 1.2x to 22.2x on winning sequences. The robot_localization UKF diverges numerically on all twelve sequences. FusionCore is available at this https URL under the Apache 2.0 license.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Mode-as-Sequence: Translating Multimodal Motion Prediction into Unified Sequential Mode Modeling
 - **Authors:** Zikang Zhou, Haibo Hu, Xinhong Chen, Yifan Zhang, Nan Guan, Yung-Hui Li, Chun Jason Xue, Jianping Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal motion forecasting is inherently under-supervised: each training scene provides only one realized future, yet multiple plausible futures exist. This sparse supervision often leads to mode collapse (redundant hypotheses and insufficient mode coverage) and unreliable confidence ranking when predicting a small set of trajectories. We propose Mode-as-Sequence, a unified decoding framework that translates an unordered mode set into an ordered mode sequence and explicitly models mode-to-mode dependency. Under this framework, we develop two complementary instantiations. ModeSeq performs recurrent mode decoding, where each mode is generated conditioned on the previously generated modes, encouraging diverse, non-redundant hypotheses with calibrated confidence ordering. To remove the mode-by-mode autoregressive bottleneck, we further propose Parallel ModeSeq, which preserves the same causal dependency using masked mode-to-mode self-attention while decoding all modes in a single forward pass, enabling efficient large-$K$ inference and scalable joint-scene prediction. To learn representative modes and calibrated confidence under sparse labels, we introduce Early-Match-Take-All (EMTA) and its joint-scene extension MA-EMTA, together with a lightweight ranking regularizer that reduces confidence inversions. Extensive experiments on large-scale benchmarks demonstrate consistent improvements in both ranking-oriented metrics and best-of-K accuracy across datasets, horizons, and object types. In the Waymo Open Dataset challenges, ModeSeq achieves 1st place in the 2024 LiDAR-free motion prediction track, and Parallel ModeSeq achieves 1st place in the 2025 Interaction Prediction Challenge, validating the effectiveness of Mode-as-Sequence for both accuracy and efficiency.
### Title:
          WideDepth: Millimeter-Accurate Benchmark for Fisheye Depth Estimation
 - **Authors:** Ilia Indyk, Ignat Penshin, Ivan Sosin, Maxim Monastyrny, Aleksei Valenkov, Ilya Makarov
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fisheye cameras are increasingly adopted in robotics for near-field manipulation, navigation, and immersive perception, yet indoor depth benchmarks with accurate ground truth are still missing. To address this, we introduce WideDepth - the first indoor dataset for fisheye depth estimation, featuring 101 scenes containing 5K high-resolution stereo pairs labeled with millimeter-level ground truth depth and disparity. Our dataset also includes paired pinhole and fisheye samples across varying fields of view and baselines in both horizontal and vertical stereo setups. We further propose a method to adapt pinhole-trained stereo models to fisheye images and introduce a novel stereo fisheye image generation pipeline based on high-resolution LiDAR scans. Leveraging these methods, we thoroughly evaluate state-of-the-art monocular depth, stereo matching, and depth completion models on our benchmark. Additionally, we provide 18K LiDAR-derived sparse depth training samples, achieving up to a 62% performance boost on fisheye data when fine-tuning pinhole-based stereo models. In summary, the high precision and versatility of our benchmark set a strong foundation for advancing research in fisheye depth estimation and robotics perception. Project page: this https URL
### Title:
          D2-V2X: Depth-Driven Cooperative V2X Reasoning for Autonomous Driving
 - **Authors:** Kevin Richard, Alphin Varghese, Colin Pham, David Oh, Srijan Das
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Single-vehicle Vision-Language Models (VLMs) are fundamentally constrained by sensor occlusions. While Vehicle-to-Everything (V2X) systems mitigate this, current benchmarks lack the cooperative reasoning required for resolving ambiguities in complex environments. We introduce D2-V2X, a spatially-aware Question-Rationale-Answer (QRA) benchmark featuring 8,500 triplets derived from multimodal vehicle and infrastructure sensors. We additionally establish a baseline that aligns 3D LiDAR features with the VLM's latent space. By enforcing natural language Chain-of-Thought rationales prior to structured JSON outputs, our model is forced to explicitly articulate spatial relations. Our experiments demonstrate that grounding VLMs in cooperative LiDAR achieves 24.4% recall in identifying occluded hazards compared to near-zero in zero-shot models and reduces spatial estimation error for visible objects by 77% compared to the zero-shot baseline. While the model achieves a functional decision-making F1-score of 53.5, we identify 3D-to-2D projection as a fundamental bottleneck in current VLM architectures, establishing a new baseline for future innovation. Data, code, and trained models available at this https URL
### Title:
          Elevator-LIO: Robust LiDAR-Inertial Odometry for Multi-Floor Navigation under Elevator-Induced Non-Inertial Motion
 - **Authors:** Yifan Zhang, Yudong Huang, Yuchong Zhang, Changze Li, Haoran Liu, Ming Yang, Tong Qin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents Elevator-LIO, a LiDAR-inertial odometry framework designed to achieve continuous robot localization during elevator travel, thereby supporting cross-floor robotic tasks. To address the state-estimation problem in non-inertial frames, Elevator-LIO establishes a decoupled state-estimation model that separately models the robot motion relative to the elevator and the elevator motion itself, and embeds it into a mode-dependent iterated error-state Kalman filter framework. This framework degenerates to conventional LIO estimation in ordinary indoor environments, while enabling the propagation and constrained update of elevator-related states in elevator non-inertial environments, thereby achieving continuous and stable localization. An elevator mode manager detects elevator entry and exit events using LiDAR ranging statistics and estimated states, and introduces event-triggered zero-velocity and zero-acceleration updates when the elevator stops to suppress accumulated vertical drift. In addition, this paper adopts an adaptive voxel downsampling strategy to maintain a stable number of effective points under significant environmental scale changes. We conduct extensive experiments on 20 real-world sequences containing 79 elevator rides, including practical challenges such as large-scale spaces, long vertical travel, dynamic pedestrian interference, and mirror reflections. The results show that Elevator-LIO maintains continuous localization accuracy in all sequences, with terminal height error below 1 cm in 17 sequences. In contrast, existing representative localization systems perform poorly on these elevator sequences. Tests on the Hilti 2022/2023 datasets further show that the proposed method remains competitive in standard indoor scenarios. The project page is available at this https URL.
### Title:
          Ghosts in the Point Clouds: De-glaring LiDAR in the Transient Domain
 - **Authors:** Avery Gump, Connor Henley, Sungjin Cheong, Akarsh Prabhakara, Mohit Gupta
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern LiDARs are rapidly transitioning from bulky, mechanically scanned systems to ultra-compact, low-cost, solid-state arrays. This miniaturization-while enabling scalability, affordability, and camera-like data structures-introduces a new and severe failure mode: internal-multipath glare. When light from a bright or retroreflective surface reflects and scatters within the LiDAR, light that should reach a single pixel spreads across the pixel array. The resulting artifacts create phantom objects, obscure real ones, and produce safety-critical "ghosts in the point clouds." This paper introduces a physically grounded sensing model and algorithmic techniques for addressing this effect. We show that internal glare can be represented as a linear, scene-independent operator-the Transient Glare Spread Function (TGSF)-acting on the transient measurements. Building on this model, we develop a training-free approach that operates on low-level LiDAR detections (or echoes) prior to point-cloud formation, leveraging knowledge of the glare spread function to reason about the likelihood of each detection arising from glare. The resulting approach is compatible with existing LiDAR signal-processing pipelines, and deployable on unmodified commercial sensors. Using experiments with real single-photon LiDAR hardware, we demonstrate substantial suppression of severe glare artifacts while preserving true scene structure.
### Title:
          MR-LiDAR: A Multi-Resolution Roadside LiDAR Benchmark for Perception Diagnostics and Deployment Guidance
 - **Authors:** Shunlai Cui, Peng Cao, Yuan Zhu, Yongjiang He, Jiacheng Yin, Xiao Huo, Gang Cao, Xiaobo Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR model selection is a critical issue in roadside sensing systems, as it directly determines both perception capability and deployment cost. However, the lack of empirical benchmarks for comparing perception performance across different LiDAR configurations has greatly constrained scientific sensor selection and deployment planning. To address this gap, we present MR-LiDAR, a controlled multi-resolution LiDAR benchmark for roadside perception diagnostics. Using 16-, 32-, 80-, and 128-beam LiDARs in identical roadside scenarios, we collect point clouds and ground-truth annotations for diverse traffic participants, including vehicles and vulnerable road users (VRUs), across varying distances. This controlled design isolates intrinsic LiDAR specifications, particularly beam count and beam distribution, as the key variables for precise performance diagnostics. Based on MR-LiDAR, we conduct systematic empirical analyses to examine how beam count, beam distribution, target distance, object category, and vehicle occlusion affect LiDAR perception performance. The results reveal that all of these factors have substantial impacts. In particular, contrary to the common assumption that higher beam counts always yield better perception, we show that an 80-beam LiDAR with optimized beam distribution can match or even outperform a 128-beam LiDAR with uniform beam distribution. In addition, we provide a practical reference guide for LiDAR selection, including target point-count statistics and detection performance comparisons based on two widely used detection algorithms. This work offers a diagnostic benchmark and practical guidance for determining cost-effective LiDAR configurations in roadside perception applications.
### Title:
          ARCANE-PedSynth: Synthetic Multi-Pedestrian Datasets with Behavioural Crossing Annotations
 - **Authors:** Muhammad Naveed Riaz, Maciej Wielgosz, Antonio M. López Peña
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present ARCANE-PedSynth, an open-source CARLA-based software framework for generating synthetic multi-pedestrian datasets with dense behavioural annotations for pedestrian crossing prediction in autonomous driving. The framework overcomes CARLA's native 9% crossing rate through a hybrid AI-manual pedestrian control architecture, enabling configurable target rates up to 75%. A 12-state behavioural finite state machine with five character archetypes produces diverse crossing behaviours. The framework generates synchronised RGB, LiDAR, and DVS data with per-frame crossing labels, behavioural states, and estimated 2D pose keypoints. We demonstrate ARCANE-PedSynth through PedSynth++, an example dataset generated with the framework, comprising 533 multi-pedestrian clips across 12 weather conditions with RGB, LiDAR, and DVS streams. ARCANE-PedSynth is fully reproducible via CLI parameterisation and Docker containerisation.
### Title:
          A Decentralized LiDAR-SLAM System with Certifiably Optimal Pose Graph Optimization
 - **Authors:** Baoshan Song, Feng Huang, Li-Ta Hsu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decentralized multi-robot LiDAR-SLAM is essential for collaborative missions but faces significant challenges in maintaining global consistency. Existing frameworks predominantly rely on local-search optimization or one-time coordinate alignment, which are prone to suboptimal convergence and long-term inconsistency, especially in large-scale or degenerate environments. To address these limitations, this paper presents the first decentralized LiDAR-SLAM system that integrates a state-of-the-art certifiably optimal Pose Graph Optimization (PGO) backend. By leveraging the Riemannian Block Coordinate Descent (RBCD) algorithm, our system ensures globally consistent trajectory estimation without requiring accurate initial guesses. Experimental results demonstrate that the proposed framework achieves superior robustness, improving trajectory RMSE by up to 48.9% compared to the state-of-the-art DiSCo-SLAM.
### Title:
          Semantics-Guided Multimodal Masked Autoencoder Pretraining for 3D BEV Object Detection
 - **Authors:** Prabuddhi Wariyapperuma, Rajitha de Silva, Marc Hanheide, Thomas Bohné, Leonardo Guevara
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D bird's-eye view (BEV) object detection is essential for autonomous driving, and depends strongly on effective multimodal representations from complementary sensors such as cameras and LiDAR. Multimodal masked autoencoders have shown strong potential for learning such representations for downstream 3D BEV object detection. However, existing methods typically apply uniform random masking to camera and LiDAR inputs, treating all regions equally, and learn representations only through masked reconstruction. We propose a semantics-guided multimodal masked autoencoder framework that introduces semantic information during pretraining through two separate components: (i) semantics-guided LiDAR voxel masking, which preserves semantically important LiDAR regions more strongly, and (ii) an auxiliary point-wise LiDAR semantic decoder branch that injects semantic guidance in addition to reconstruction. On BEVFusion 3D object detection, our semantics-guided pretraining strategy improves performance on the nuScenes mini validation set compared to the standard UniM2AE baseline: semantics-guided LiDAR voxel masking yields +1.49% mean Average Precision (mAP) and +1.66% nuScenes Detection Score (NDS), while decoder-side point semantic supervision yields +1.39% mAP and +3.22% NDS over the baseline.
### Title:
          GreenSeg: Ground Segmentation Algorithm for Agricultural Robots in Mediterranean Greenhouses using RGB-D Point Clouds
 - **Authors:** Fernando Cañadas-Aránega, José C. Moreno, José L. Blanco-Claraco
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Greenhouse agriculture in the Mediterranean region faces significant automation challenges due to its unique structural and environmental constraints. These environments are characterized by extremely narrow aisles, heterogeneous terrains ranging from concrete to tilled soil and severe optical interference caused by polyethylene covers, which induce specular reflections and "ghost points" in depth sensors. While autonomous navigation is essential for digitizing agricultural tasks, traditional solutions often rely on expensive 3D LiDAR systems that are economically unscalable for most facilities. To address this, this paper presents GreenSeg, a robust perception framework for autonomous navigation using RGB-D sensing. The proposed method introduces a dual-layer validation strategy: a robust global plane fitting combined with a surface curvature filter for terrain adaptability, and a seed-point-based Region Growing constraint to ensure the spatial continuity of the navigable plane. Experimental validation was conducted using the AGRICOBIOT I platform across four diurnal scenarios with varying solar elevations. The results show that GreenSeg consistently outperforms benchmark segmentation methods, achieving peak improvements of 11.58% in mean Recall and 19.24% in mIoU during critical rotational maneuvers at the end of corridors. These findings confirm that the proposed algorithm enables stable and safe autonomous navigation in unstructured, dynamic agricultural environments that are subject to budget constraints and sensitive to lighting conditions.
### Title:
          Neuromorphic LiDAR-based Bird's Eye View Object Detection using Energy-efficient Spiking Neural Networks
 - **Authors:** Sambit Mohapatra, Senthil Yogamani, Heinrich Gotzig, Patrick Mader
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving perception demands accurate and efficient processing of three-dimensional sensor data under strict power constraints. Traditional convolutional neural networks achieve strong detection accuracy but are computationally intensive, limiting their suitability for deployment on resource-constrained neuromorphic platforms. Spiking neural networks offer a compelling alternative through event-driven sparse computation, yet their application to complex real-world perception tasks such as three-dimensional object detection remains limited. In this work, we propose an end-to-end spiking encoder-decoder network for object detection in bird's eye view representations of LiDAR point clouds, trained using surrogate gradient backpropagation. We train two variants: a membrane potential variant that reads continuous neuron state at the output stage for maximum accuracy, achieving $92.05$/$87.04$/$86.51$ AP at $\mathrm{IoU}\!=\!0.5$ (Easy/Moderate/Hard), and, a fully binary spiking variant that operates exclusively on spike trains at every layer for direct neuromorphic deployment. We evaluate four input spike encoding strategies and demonstrate that allowing the network to learn spike representations directly from data outperforms hand-crafted Poisson, latency, and z-axis encoding schemes on the KITTI benchmark, where sequential frames are unavailable and the BEV input is presented repeatedly across timesteps as a proxy for temporal streaming. A block-wise energy analysis demonstrates a $3.33\times$ reduction in synaptic operation energy over an equivalent CNN under conservative loop-based operation. Together, these results demonstrate the viability of spiking neural networks for accurate and energy-efficient neuromorphic perception in autonomous driving.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          ArtSplat: Feed-Forward Articulated 3D Gaussian Splatting from Sparse Multi-State Uncalibrated Views
 - **Authors:** Inseo Lee, Yoonji Kim, Eugene Sohn, Jiwoong Lee, Jungmin You, Joonseok Lee, Jin-Hwa Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Articulated object reconstruction from sparse-view images is an ill-posed problem that requires simultaneous inference of geometry and underlying articulation structure. Existing methods for articulated object reconstruction based on NeRF and 3D Gaussian Splatting (3DGS) typically rely on dense views or strong priors (e.g., depth maps, joint types, predefined number of joints) and require costly per-object optimization. In this paper, we propose ArtSplat, the first feed-forward framework for articulated 3D Gaussian Splatting. It reconstructs both geometry and joint parameters from sparse multi-view images across multiple articulation states in a single forward pass. To address the challenges of single-pass articulated reconstruction, we introduce a per-pixel joint map representation that enables the integration of joint parameter estimation into the feed-forward pipeline. We further propose a Cross-State Attention (CSA) mechanism with state tokens, which effectively captures discrete motion across input states. Experiments on 68 articulated objects from PartNet-Mobility, including both single- and multi-joint configurations, demonstrate that ArtSplat achieves competitive performance in both geometry and joint estimation, while being over 400 times faster than baselines.
### Title:
          Depth Peeling for High-Fidelity Gaussian-Enhanced Surfel Rendering
 - **Authors:** Keyang Ye, Hongzhi Wu, Kun Zhou
 - **Subjects:** Subjects:
Graphics (cs.GR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Novel view synthesis has been significantly advanced by NeRFs and 3D Gaussian Splatting (3DGS), which require ordering volumetric samples or primitives for correct color blending. While the recent Gaussian-Enhanced Surfels (GES) enable high-performance, sort-free rendering, they suffer from aliasing artifacts and suboptimal reconstruction. To address these limitations, we propose DP-GES, a novel representation that augments opaque surfels with semi-transparent boundaries and leverages Depth Peeling to establish accurate per-pixel ordering. This design enables sort-free Gaussian splatting with correct transmittance modulation, effectively eliminating aliasing and popping artifacts while facilitating a fully differentiable joint optimization. Extensive experiments demonstrate that our method achieves superior reconstruction quality and compares favorably against state-of-the-art techniques across a wide range of scenes.
## Keyword: mapping
### Title:
          BoxLitE: A Faithful Knowledge Base Embedding Based on Convex Optimization
 - **Authors:** Bruno F. Lourenço, Hesham Morgan, Ana Ozaki, Aleksandar Pavlović, Emanuel Sallinger
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Logic in Computer Science (cs.LO); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Knowledge base (KB) embeddings aim at combining the capability of classical knowledge graph embeddings to generalize the information present in facts, the ABox, with conceptual knowledge represented in an ontology language, the TBox. Several authors have recently explored the idea of mapping concepts to convex regions in a vector space. This is useful to represent hierarchies, typically present in TBoxes, since more general concepts can be mapped to larger regions, containing those regions associated with more specific concepts. However, the power of convexity is rarely leveraged during the actual learning tasks. Here, we introduce BoxLitE, a KB embedding model for DL-Lite$^{\mathcal{H}}$ that allows for convex optimization. We show that for any satisfiable DL-Lite$^{\mathcal{H}}$ KB, there is a BoxLitE embedding that is a weakly faithful model. As a proof of concept, we show how to formulate the KB embedding task as a convex optimization problem and how to obtain embeddings with such desirable faithfulness properties.
### Title:
          A Dynamical Framework for Cognitive Processes Based on Transformations and Semantic Equivalence
 - **Authors:** Carlo Cattani, Dioneia Motta Monte-Serrat
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes a structural and dynamical framework for modeling cognitive processes within a cybernetic perspective. Cognitive states are represented as elements of a state space evolving through an iterative update rule of the form \[ X_{t+1} = \pi\big(F(f(X_t))\big), \] where $f$ describes internal transformations, $F$ represents interpretative mappings, and $\pi$ enforces semantic equivalence. The model is interpreted as a feedback system integrating transformation, observation, and stabilization. A categorical formulation is introduced to capture compositional structure, while the associated dynamics are analyzed through fixed-point arguments and contraction conditions ensuring stability. To demonstrate the operational character of the framework, a computational illustration is provided, together with a qualitative analysis of the induced dynamics. A concrete linguistic application shows how context-dependent interpretation can be modeled as a trajectory toward a stable semantic class. The proposed approach connects dynamical systems, category theory, and cognitive modeling, and provides a unified representation of cognition as a feedback-driven process evolving toward invariant interpretations.
### Title:
          A Per-Access Upper Bound for Shared-Resource Interference in Direct-Mapped Multicore Architectures
 - **Authors:** Felipe T. Pedroni
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Operating Systems (cs.OS); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a formal bounding analysis for maximum credible interference in multicore processors under strict architectural invariants: direct-mapped L2 cache (1-way associativity), disabled Miss Status Handling Registers (MSHRs), single-bank main memory, deterministic pinned tasks with fixed physical memory mapping, and a pessimistic L2/memory arbitration policy. We prove that, under these invariants, the per-critical-access stall imposed on a target task T is bounded above by (N-1)Lmem, and that this bound is attained by a synchronized adversarial workload of N-1 congruent-different-tag memory requests issued in phase with T's critical accesses. The argument is per-access and direct, requiring no informal multiplicative interference function. The derivation is purely analytical and discussed in the context of DO-178C/CAST-32A certification objectives for airborne software. Limitations and conditions for applicability are explicitly stated. This work provides a traceable method for separating multicore interference from Worst-Case Execution Time (WCET) budgets under fixed architectural constraints.
### Title:
          Efficient Uniform Sampling of Surjections via their Profiles
 - **Authors:** Arnaud Carayol, Pablo Rotondo
 - **Subjects:** Subjects:
Data Structures and Algorithms (cs.DS); Discrete Mathematics (cs.DM); Probability (math.PR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this article, we develop efficient sampling algorithms for random surjections from $[n]$ to $[k]$ for all $n \geq k$. We make no assumption about $n$ and $k$. In particular, we do not make the common assumption that the ratio $\frac{n}{k}$ is constant. All our guarantees are uniform in $n$ and $k$. Our first insight is that all the complexity in sampling random surjections is captured by sampling a smaller structure which we call the \emph{profile} of the surjection. More precisely, the profile associates to each occurring preimage size $s$ the number of preimages of size $s$. Using standard techniques, we show that the problem of sampling surjections reduces to sampling the profile with the induced distribution. This is partly explained by the fact that profiles are always sublinear, with at most $\sqrt{2n}$ entries in the worst case. We provide a complete set of algorithms to directly sample the \emph{profile} of a random surjection with the induced distribution, covering the full parameter space. These algorithms are shown to be optimal up to logarithmic factors in the expected size of the output. Our algorithms are based on exact-size Boltzmann samplers, which are standard rejection-based samplers. We partition the parameter space into three main regions. In each region, we optimize both the rejection rate and the cost of each sampling round. Profiles capture a number of relevant statistics of random surjections and might be of independent interest. In a related context, profiles have been recently studied by Devroye et al. for random mappings. As a spin-off result, we answer an open question from Devroye and Los '25 by providing an optimal algorithm also for the profiles of a random mapping when $k > n/\log n$. The results of this article are not only of theoretical interest but lead to samplers implementable in practice.
### Title:
          Overcoming "Physics Shock" in Earth Observation A Heteroscedastic Uncertainty Framework for PINN-based Flood Inference
 - **Authors:** Tewodros Syum Gebre, Jagrati Talreja, Matilda Anokye, Leila Hashemi-Beni
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rapid and accurate flood extent mapping from Remote Sensing data, such as Synthetic Aperture Radar (SAR), is critical for operational disaster response, but standard Deep Learning models often produce physically impossible predictions due to a lack of hydrological constraints. While PhysicsInformed Neural Networks (PINNs) attempt to address this by embedding governing laws directly into the loss function, their application to real-world remote sensing data frequently fails. Enforcing rigid spatial derivatives (e.g., the 2D Shallow Water Equations) onto unconditioned latent spaces attempting to fit noisy SAR speckle causes catastrophic gradient divergence, a phenomenon we term Physics Shock. In this paper, we propose a novel Uncertainty-Aware PINN framework tailored specifically for applied Earth Observation that addresses this instability. By integrating a dynamic Warm-Start protocol and modeling heteroscedastic aleatoric uncertainty via a negative log-likelihood objective, the network learns to dynamically relax physical constraints in regions of high sensor noise while strictly enforcing them in high-confidence areas. Evaluated on the Sen1Floods11 dataset, our probabilistic Attention-Gated FNO-UNet successfully stabilizes multi-objective optimization, achieving a +25% relative improvement in Intersection over Union (IoU) compared to deterministic baselines. Furthermore, through Deep Ensembles, we successfully disentangle intrinsic sensor noise from out-of-distribution terrain ignorance, providing operational agencies with highly calibrated, physically consistent confidence bounds for robust disaster mitigation and real-time decision-making.
### Title:
          Riemannian Archetypal Analysis: Interpretable non-linear data analysis on deformed star distributions
 - **Authors:** Willem Diepeveen, Deanna Needell
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Differential Geometry (math.DG); Optimization and Control (math.OC); Statistics Theory (math.ST)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Classical archetypal analysis is appealing for its interpretability, but its linear geometry can limit performance on data with strongly non-linear structure; at the same time, existing neural extensions improve flexibility while often weakening the geometric meaning of archetypes and interpolations. In this work, we develop a Riemannian version of archetypal analysis based on data-driven pullback geometry for real-valued data, with the goal of combining the interpretability of classical archetypal analysis with the expressive power of modern non-linear models. We introduce a class of deformed star distributions together with associated pullback Riemannian geometry to provide a statistical interpretation of the resulting manifold mappings, define the Riemannian archetypal mapping (RAM) as a projection onto the manifold of geodesically convex combinations of archetypes, and propose a practical optimization scheme based on convex relaxation followed by non-convex refinement. We further propose a learning scheme that yields reasonable, albeit generally suboptimal, deformed star distributions from data. Experiments on synthetic examples and MNIST show that the resulting framework produces meaningful geodesics, useful denoising projections, and geometry-aware classifications, while also clarifying where current optimization limitations remain.
### Title:
          Single View Seafloor Recovery from Imaging Sonar via Differentiable Rendering
 - **Authors:** Sevan Brodjian, Michael Hobley, Pietro Perona
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sonar is often the only modality suitable for high-resolution imaging underwater due to light attenuation and turbidity. Forward-looking imaging sonar provides measurements over range and horizontal angle but collapses vertical structure into a flat image, creating ambiguities that make 3D recovery challenging. A common use case for imaging sonar is underwater terrain mapping (bathymetry), yet current methods require many views, expensive multi-sensor setups, or significant training data, which limits use and adaptability to new environments. We present a training-free method that recovers bathymetry from a single sonar image in under 30 seconds via differentiable rendering, conditioned on a known seafloor tilt. To our knowledge, this is the first differentiable rendering approach for single-view height recovery in sonar. Our method implements differentiable sonar ray tracing and optimizes an explicit height field to reproduce the target image. On synthetic datasets, our approach outperforms a supervised CNN under distribution shift and remains close on rough terrain, while the CNN wins in-distribution. By modeling physically grounded priors of the sonar process, our method adapts across sensor configurations and environments without training data.
### Title:
          Incorporating Deep Learning Design in Database Queries
 - **Authors:** Yuval Lev Lubarsky, Dean Light, Boaz Berger, Shunit Agmon, Benny Kimelfeld
 - **Subjects:** Subjects:
Databases (cs.DB); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning over relational databases is conventionally realized by translating data into graph representations and applying graph-based neural networks within external frameworks. This round-trip between the database and external machine learning (ML) systems introduces non-trivial engineering overhead. In effect, these graph neural networks operate on tuple embeddings and manipulate them in ways that capture the interactions induced by relational joins. Given this natural correspondence, there is no fundamental reason why specifying a neural network over relational data should be substantially harder than querying it. We propose an approach that naturally integrates deep learning with database queries. The key idea is to associate each tuple with provenance, represented as a vector embedding with learnable parameters. Queries are lifted to operate jointly on data and embeddings, mapping input relations with embedded tuples to output relations with embedded tuples. This approach provides a declarative foundation for relational deep learning, facilitating integration with database systems, optimization, and wide adoption. We describe RelaNN, a proof-of-concept implementation of this approach built on top of PyTorch and cuDF. We illustrate the utility of RelaNN by implementing various graph-learning models, including graph convolutional networks, heterogeneous graph transformers, hypergraph neural networks and deep homomorphism networks. The simplicity of the programs and their competitive runtime performance demonstrate a concrete path toward making the implementation of state-of-the-art neural networks over databases as simple as writing a query.
### Title:
          Teaching Through Analogies: A Modular Pipeline for Educational Analogy Generation
 - **Authors:** Mariam Barakat, Ekaterina Kochmar
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Analogies help learners understand unfamiliar concepts by relating them to known concepts. Despite recent advances, large language models (LLMs) continue to struggle to generate analogies of comparable quality to those produced by humans. We present a modular pipeline for educational analogy generation, decomposing the task into four stages: source finding, sub-concept generation, explanation generation, and evaluation. Grounded in Structure Mapping Theory, the pipeline enables systematic, stage-by-stage analysis of how model choice and input configuration affect analogy quality. We evaluate 12 state-of-the-art LLMs across six model families on two datasets with structured sub-concept annotations (SCAR and ParallelPARC), alongside seven embedding models for closed-setting retrieval. Our results show that sub-concepts substantially improve explanation quality and closed setting retrieval precision but provide limited benefit in open-ended source generation. We further introduce an LLM-as-a-judge evaluation methodology and validate its scoring against human annotations from seven annotators, finding that Claude Sonnet 4.6 aligns more reliably with human rankings than with fine-grained absolute scores. Taken together, our findings reveal cross-stage interactions that isolated studies cannot capture, and highlight sub-concept grounding as a key driver of analogy quality generation.
### Title:
          An Empirical Evaluation of LLM-Generated Code Security Across Prompting Methods
 - **Authors:** Mohammed Kharma, Ahmed Sabbah, Mohammad Alkhanafseh, Mohammad Hammoudeh, David Mohaisen
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The growing use of Large Language Models (LLMs) for automated code generation has enhanced software development efficiency, but often at the cost of security. Generated code frequently overlooks critical concerns, leaving it vulnerable to issues such as weak encryption and improper input validation. To investigate this problem, we present a comprehensive empirical evaluation of the security quality of LLM-generated code across five LLMs and four programming languages (Java, C++, C, and Python), examining the impact of multiple prompt engineering methods. We introduce a weaknesses-aware zero-shot chain-of-thought (WA-0CoT) prompting strategy that enriches prompts with security context using CWE mappings to guide model reasoning. Our empirical analysis, supported by chi-square tests, finds no statistically significant reductions in vulnerability frequency or density across prompt methods. However, prompting strategies, including WA-0CoT, systematically influence the compositional distribution of CWE categories, with effects varying by programming language. These findings suggest that while security-aware prompting alters the structure of generated weaknesses, prompt engineering alone is insufficient to reliably reduce overall vulnerability levels. The results highlight the importance of language-aware and model-aware prompt design when evaluating the security properties of LLM-generated code.
### Title:
          Adaptive Human-AI Coordination via Hierarchical Action Disentanglement
 - **Authors:** Adnan Ahmad, Bahareh Nakisa, Mohammad Naim Rastgoo
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human-AI collaboration requires agents that can adapt to diverse partner behaviors and skill levels while remaining robust to unseen partners. Existing methods often collapse to a single dominant behavior or learn poorly aligned skills, limiting effective coordination. We propose Intrinsic Action Disentanglement (IAD), a deep hierarchical reinforcement learning (DHRL) framework that learns distinct, partner-aware low-level action sequences conditioned on high-level latent skills. IAD introduces an intrinsic reward that explicitly encourages disentangled action distributions of the agent's low-level policy across skills, yielding an interpretable mapping between high-level decisions and partner-specific behavioral responses. By capturing temporally extended interaction patterns, IAD enables flexible adaptation to heterogeneous partner dynamics under distributional shift. We evaluate IAD in the Overcooked-AI domain across multiple layouts and diverse partner settings, including unseen simulated partners, a human-proxy model trained on human-human gameplay, and real human partners. Results show that IAD consistently outperforms strong baselines and achieves more reliable, adaptive coordination across all settings.
### Title:
          SliceWorld: A Predictive and Controllable World-State Model for CT Report Generation
 - **Authors:** Yuanhe Tian, Yan Song
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 CT report generation (CTRG) requires models to summarize three-dimensional anatomical context and pathological findings from hundreds of axial slices. Existing methods typically learn a direct image-to-text mapping, providing limited mechanisms for modeling how CT evidence evolves across slices or how reports respond to controlled changes in latent lesion-related factors. We propose SliceWorld, a CT-specific world-state framework that treats an axial CT scan as an ordered sequence along the z-axis. SliceWorld encodes prefix CT evidence into factor-aware latent states containing anatomy, lesion, and uncertainty components, and projects these states into world tokens used for multi-step future-slice feature prediction, lesion-factor intervention, and LLM-based report generation. The model is first pretrained on CT slice sequences with predictive, factor-aware, and counterfactual objectives, and is then fine-tuned on paired CT-report data. Experiments on M3D-Cap and CT-RATE show that SliceWorld improves natural language generation metrics and clinically oriented automatic evaluation. Further analyses demonstrate multi-horizon future-slice prediction, measurable factor alignment, reduced-slice robustness, and selective lesion-sensitive report modulation.
### Title:
          ConceptM$^3$oE: Concept-Guided Multimodal Mixture of Experts for Interpretable Computational Pathology
 - **Authors:** Xuan Wang, Zhongling Xu, Gopi Kannedhara, Joakim Nguyen, Jian Yu, Jinrui Fang, Abdurrahmaan Baghdadi, Tianlong Chen, Awais Naeem, Chandra Krishnan, Edward Castillo, Andrew H. Song, Ankita Shukla, Ying Ding, Nicholas Konz, Hairong Wang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Healthcare models are transitioning from unimodal prediction toward multimodal reasoning over heterogeneous diagnostic inputs. In computational pathology, for complex tumor subtypes where morphology alone can be challenging to distinguish, pathology reports and molecular measurements may provide additional diagnostic evidence alongside whole-slide images, yet existing models often fail to clarify how diverse signals assemble into recognizable diagnostic concepts. We propose ConceptM$^3$oE (Concept Multimodal MoE), which embeds concept formation directly within interaction-aware mixture-of-experts (MoE) pathways. The architecture decomposes evidence into modality-specific, redundant, and synergistic experts, which are then projected into structured concept bottlenecks mapping latent features to a hierarchy of morphology and biomarker concepts. To prevent the information loss typical of interpretable bottlenecks, we utilize residual pathways within each expert to allow task-relevant signals to flow both through the concepts and directly to the final task prediction, so that high performance is maintained alongside interpretability. Across an institutional pediatric brain tumor cohort and a public glioma cohort, the framework delivers competitive performance to unconstrained models while producing reasoning traces validated by an independent neuropathologist. In data-limited regimes, ConceptM$^3$oE improves limited-data performance, increasing macro-F1 from 56.41% to 66.70% at small training sizes compared to non-concept-informed baselines, while also showing faster training convergence consistent with the regularizing effect of concept learning. This work offers a scalable path toward high-performance medical AI that is inherently verifiable and better aligned with the complex decision-making of clinical practice.
### Title:
          Phonetic Modeling of Dialectal Variation in Vietnamese Speech
 - **Authors:** Quan Ngoc Hoang, Long Hoang Huu Nguyen, Nghia Hieu Nguyen, Kiet Van Nguyen, Ngan Luu-Thuy Nguyen
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vietnamese exhibits substantial dialectal phonetic variation across Northern, Central, and Southern regions, where identical lexical items may be realized with markedly different pronunciations. Such variation poses challenges for automatic speech recognition (ASR) and remains difficult to model computationally due to the complex relationship between Vietnamese orthography and phonology. Existing approaches typically address dialect variability at the word level, assuming dialect-invariant mappings between spelling and pronunciation, which limits their ability to capture systematic phonetic differences. We propose a dialect-aware phonetic framework that explicitly models Vietnamese phonological structure and dialectal variation at both the vocabulary and decoding levels. The framework introduces a phonetic vocabulary that decomposes each syllable into structured phonetic components and maps them to dialect-specific IPA representations, together with a phonetic-structure decoder that jointly predicts these components. Experiments on the UIT-ViMD, a only-available dataset for multi-dialect in Vietnamese, show that the proposed approach outperforms various pre-trained baselines, \textbf{especially matches the performance of the strongest pretrained wav2ve2-base-vi-250h} across dialects while \textbf{using substantially fewer parameters and no external pretraining}. Code for experimental reproducibility will be publicly available upon the acceptance of this paper.
### Title:
          Coarse-to-Fine Domain Incremental Learning with Attentive Distillation for Mining Footprint Segmentation in Multispectral Imagery
 - **Authors:** Alif Tri Handoyo, Vincent C.S. Lee, Rizka Widyarini Purwanto, Alex M. Lechner, Deanna Kemp, Muhamad Risqi U. Saputra
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatically mapping and segmenting global mining footprints using remote sensing and deep learning is critical for monitoring the socio-environmental risks and impacts of mining, yet its progress is hindered by the scarcity of fine-grained annotated data. Although large-scale datasets with coarse boundaries are widely available, leveraging them to improve fine-grained segmentation is challenging due to significant domain shift. To address this, we propose MineC2FNet, a coarse-to-fine domain incremental learning framework that exploits abundant coarse data to enhance fine-grained mining footprint segmentation. MineC2FNet adopts a teacher-student architecture with attentive distillation at both the feature and prediction levels, selectively transferring generalized knowledge from the coarse domain while enabling boundary refinement using limited fine-grained data (fine domain). We further introduce an expertly validated dataset of 219 images with precise boundary annotations across diverse geographies and commodities. Extensive experiments against state-of-the-art approaches, including domain adaptation and domain incremental learning methods, demonstrate that MineC2FNet achieves superior performance while effectively handling domain shift. The dataset and code are publicly available at this https URL.
### Title:
          TIGER: Text-Informed Generalized Enzyme-Reaction Retrieval
 - **Authors:** Yuhang Zhang, Keyan Ding, Peilin Chen, Han Liu, Can Lin, Ruixi Chen, Shiqi Wang, Qi Song
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Biomolecules (q-bio.BM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Enzyme-reaction retrieval is a fundamental problem in computational biology, underpinning enzyme characterization, reaction mechanism elucidation, and the rational design of metabolic pathways and biocatalysts. As a bidirectional task, it entails both enzyme-to-reaction and reaction-to-enzyme mapping. However, existing approaches suffer from poor generalization across tasks and distributions, with performance highly sensitive to dataset splits and substantial asymmetry between retrieval directions. To address these challenges, we present TIGER, a Text-Informed Generalized Enzyme-Reaction Retrieval framework that leverages protein-to-text generation models to distill textual semantic knowledge from enzyme sequences, providing a generalized representation that bridges enzymes and biochemical reactions. To ensure the quality and reliability of textual semantics, we design a Dynamic Gating Network that adaptively fuses text-derived knowledge with sequence features, enabling more consistent and informative enzyme representations, while a Structure-Shared Feature Projector aligns enzyme and reaction representations within a unified latent space. Extensive experiments demonstrate that, under bidirectional retrieval supervision, TIGER significantly outperforms state-of-the-art baselines across diverse distributions and exhibits strong robustness and transferability across tasks.
### Title:
          Lake Detection and Water Quality Estimation in Sentinel-2 Data
 - **Authors:** Iulia Pleşu, Alexandra Băicoianu, Ioana Cristina Plajer
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With climate change and increasing human pressure on natural landscapes, inland water resources are becoming progressively scarcer, more vulnerable, and more difficult to manage sustainably. Reliable and automated methods for detecting, monitoring, and assessing surface water bodies are therefore of growing scientific and practical importance. In this paper, we investigate and compare three distinct machine learning architectures for water body identification and monitoring. Their performance is evaluated through quantitative metrics and real-world examples. Furthermore, a direct comparison with classical NDWI thresholding is conducted on a representative test image to highlight differences between data-driven and index-based approaches. This analysis allows us to identify the best-performing model in terms of accuracy, robustness, and practical applicability. Beyond detection, a major challenge for meaningful water quality assessment lies in the consistent and interpretable visualization of spectral water indices. Standard color mapping techniques are often inadequate or potentially misleading for environmental applications. To address this gap, we propose a suite of meaningful color schemes adapted for water quality indices, facilitating clearer interpretation, comparison, and decision-making for human users.
### Title:
          IQA-Spider: Unifying Multi-Granularity Image Quality Assessment with Reasoning, Grounding and Referring
 - **Authors:** Xinge Peng, Yiting Lu, Xin Li, Zhibo Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present IQA-Spider, the first image quality assessment (IQA) framework that unifies reasoning, grounding, and referring into a single LMM-based framework for multi-granularity quality understanding. Existing LMM-based IQA methods typically support only partial perception dimensions, such as quality description and question answering~(\textit{i.e.}, reasoning) or pixel-level grounding. This limitation largely stems from the absence of (i) a unified task and data formulation and (ii) effective optimization paradigms for multi-granularity learning. To address these limitations, we formulate a rigorous four-task paradigm covering global and local quality description, pixel-level grounding, and region-level referring. Based on this formulation, we construct a corresponding IQA dataset with a scalable and automatic annotation pipeline, thereby providing a solid foundation for unified multi-granularity learning. To further enable unified perception, we adopt a conflict-free two-stage design that progressively extends text-level multi-granularity understanding to pixel-level grounding: (i) the first stage equips the model with fine-grained text-level reasoning across multiple IQA tasks, and (ii) the second stage introduces a training-free text-to-point grounding paradigm, which bridges textual semantics and pixel-level perception by mapping token logits to spatial coordinates. Based on these efforts, we achieve IQA-Spider with unified multi-granularity explainable image quality assessment. Extensive experiments across multiple benchmarks demonstrate strong performance, validating the effectiveness and versatility of the proposed formulation and framework.
### Title:
          CyBOKClaw: Human-in-the-Loop CyBOK Mapping for Cybersecurity Curriculum
 - **Authors:** Yan Lin Aung, Kevin Togbe
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents CyBOKClaw, an interpretable human-in-the-loop retrieval framework for mapping cybersecurity keywords or phrases (KWoPs) to the Cyber Security Body of Knowledge (CyBOK). Rather than treating the task as strict exact classification, the framework is designed as a top-k candidate generator for expert review. It combines query normalization, curated term expansion, concept-level boosts, topic-description enrichment, and domain-sensitive ranking rules. Because educational KWoPs are often broad, ambiguous, and only approximately aligned with CyBOK terminology, strict exact matching provides only a partial account of practical utility. We therefore evaluate the framework using both structural retrieval metrics and an expert-guided top-5 usefulness metric, ECA-5 (Exact or Closest Acceptable Match at top-5), which records whether the returned candidates contain at least one mapping that an expert would judge exact or accept as the nearest practical CyBOK placement. On the development dataset, CyBOKClaw achieves 64.73% EXA-5 (Exact Match at top-5), 84.18% structural semantic alignment, and 91.88% ECA-5; on the validation dataset, it achieves 81.19% EXA-5, 93.32% structural semantic alignment, and 98.00% ECA-5. These results show that expert-guided top-k usefulness provides a more faithful account of practical CyBOK mapping utility than exact structural matching alone, and that CyBOKClaw is effective as a CyBOK-specific expert-support retrieval system.
### Title:
          CALIBURN: A Regime-Sensitivity Study of Operationally Calibrated Streaming Intrusion Detection
 - **Authors:** Michel A. Youssef
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Streaming network intrusion detection systems must process flows continuously while keeping memory bounded, but most current methods leave alerting threshold selection as a post-hoc tuning problem poorly suited to production. Operators need alerting behaviour specifiable before deployment using inputs such as false-negative cost, false-positive cost, and alerting budget. This paper presents CALIBURN, a five-component streaming alerting pipeline composed of a truncated Bayesian online change-point detector, an isotonic calibration layer mapping the change-point posterior to an empirical conditional attack probability, a cost-sensitive decision threshold derived from operator-specified misclassification costs, a Conformal Risk Control wrapper that converts an alert-budget specification into a within-window valid threshold under exchangeability, and a multi-window burn-rate alerting layer adapted from Site Reliability Engineering practice. Rather than claiming uniform dominance, we present CALIBURN as a regime-sensitivity study, evaluating the pipeline across three attack-prevalence regimes: LITNET-2020 at 5.2 percent, CICIDS2017 at 22.06 percent, and UNSW-NB15 at 64 percent. In the rare-attack regime, CALIBURN achieves AUC-PR 0.943 on LITNET-2020, outperforming the best streaming baseline by 2.21x and the best batch reference by 4.12x; isotonic calibration reduces Brier score by 30 percent. In the moderate-prevalence regime, CALIBURN remains the strongest streaming method on CICIDS2017 but is exceeded by batch density methods. In the high-prevalence regime, all streaming methods approach the prevalence floor. We further identify two distinct CRC-collapse mechanisms driving the alert rule to degeneracy at small alpha, treating both as operational guidance for practitioners.
### Title:
          Leveraging pretrained RGB denoisers for hyperspectral image restoration
 - **Authors:** Daniele Picone, Mohamad Jouni, Mauro Dalla-Mura
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hyperspectral image restoration faces several challenges, including limited training data, strong sensor specificity, and high spectral dimensionality. These limitations hinder the learning of robust hyperspectral priors, motivating the reuse of priors learned from large-scale RGB data. In this work, we propose a minimally trained, lightweight adapter that repurposes frozen pretrained RGB denoisers for hyperspectral restoration through a projection mapping. The method denoises low-dimensional spectral projections and reconstructs the hyperspectral cube through constrained linear aggregation, while preserving plug-and-play compatibility and the stability properties of the underlying RGB denoiser. Experiments on denoising, deblurring, and super-resolution across multiple datasets demonstrate consistent improvements over hyperspectral-specific baselines, showing the strong transferability of large-scale RGB priors.
### Title:
          IV-Net: A neural network for elliptic PDEs with random and highly varying coefficients
 - **Authors:** Shan Zhong, George Biros
 - **Subjects:** Subjects:
Numerical Analysis (math.NA); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a novel neural operator architecture designed to approximate solutions of linear elliptic partial differential equations with high-contrast, spatially varying coefficients. The network, termed the Iterated V-shaped Net (IV-Net), realizes a mapping from the input coefficients and righthand side to the corresponding solution field. The architecture of IV-Net is informed by, and closely resembles, a V-cycle multigrid solver. The IV-Net model is parameterized via convolutional layers defined in the physical domain. For coercive problems with highly heterogeneous coefficients, the proposed network exhibits superior performance relative to a proper orthogonal decomposition (POD) approach and several existing neural operator architectures. For low-frequency oscillatory Helmholtz problems with smooth coefficients, its performance is similar to that of a Fourier neural operator. We analyze the approximation error and convergence behavior of IV-Net, its data efficiency, and its dependence on the underlying discretization mesh. Furthermore, we demonstrate the practical effectiveness of the architecture through a series of numerical experiments, including applications to uncertainty quantification, inverse problems, and prediction of quantities of interest.
### Title:
          QuoVLA: Quotient Space for Vision-Language-Action Models
 - **Authors:** Xuan Wang, Yinan Wu, Haoran Duan, Jungong Han
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA) models commonly adapt pretrained Vision-Language Models (VLMs) to robot control by mapping visual observations and language instructions to continuous actions. Existing approaches typically take an action-insufficiency view, assuming that pretrained VLM latents either lack directly usable action information or should be shielded from action-learning signals. Against this view, our \textit{Quotient Theory for VLA} shows that pretrained VLM latents are not action-insufficient but action-sufficient: they already contain the information needed for control, yet remain overcomplete by distinguishing prompt-level variations that induce the same optimal action behavior. To operationalize this theory, we propose QuoVLA, a quotient-space framework for VLA that compresses pretrained VLM latents into action-sufficient representations. Specifically, QuoVLA instantiates this principle with a quantization module and a dual-branch design with relative temporal-complexity regularization, preserving action-relevant information while removing prompt-level redundancy. Extensive experiments across multiple benchmarks demonstrate that QuoVLA achieves strong performance, with particularly notable improvements in generalization under visual, linguistic, and environmental distribution shifts. Our code will be made publicly available.
### Title:
          RAMBA: 4D Radar Mapping by Bundle Adjustment
 - **Authors:** Jianzhu Huai, Yiwen Chen, Binliang Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 4D radar is increasingly attractive for robotic mapping because it provides range, azimuth, elevation, and Doppler measurements while remaining robust in adverse visibility conditions. Although recent radar and radar--inertial odometry methods have achieved promising online state estimation performance, offline global map refinement for 4D radar remains underexplored. This paper presents RAMBA, a radar bundle-adjustment framework for globally consistent 4D radar mapping. Given initial poses and radar frames from a radar--inertial odometry front-end, RAMBA jointly refines radar frame states using covariance-weighted geometric residuals, IMU preintegration factors, and radar ego-velocity constraints. The geometric residuals extend pairwise GICP to a multi-frame optimization by forming voxel-based correspondences across selected frames and weighting each residual with point covariances. To improve robustness against drift and revisits, RAMBA enforces temporal consistency during correspondence formation while explicitly supporting loop-closure constraints. Experiments on the ColoRadar and SNAIL Radar datasets show that RAMBA improves map consistency and usually enhances trajectory accuracy over radar--inertial odometry and pose-graph optimization baselines.
### Title:
          VEOcc: Voxel-Centric Online Semantic Occupancy Prediction For Embodied Scene Understanding
 - **Authors:** Ruoyu Wang, Yong Liu, Sheng Tao, Yuhang Lin, Yukai Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Crucial for autonomous exploration, online 3D occupancy prediction and mapping incrementally constructs dense spatial representations on the fly. However, recent Gaussian-centric methods struggle with structural boundary fidelity and rely heavily on predefined scene-size priors, fundamentally limiting their operational efficiency. In this work, we present VEOcc, a voxel-centric framework formulated as a recursive perception-and-assimilation paradigm. By eliminating the need for initial scale estimation, VEOcc enables highly streamlined, open-ended map expansion. Furthermore, to robustly aggregate noisy temporal observations within the discrete voxel space, we propose a Spatio-Temporal-Aware Online Update Strategy. It integrates Cross-Temporal Logit Aggregation (TLA) for temporal consistency, Reliability-Aware Confidence Modulation (RCM) for spatial uncertainty calibration, and Confidence-Driven Incremental State Update (CSU) for robust global state assimilation. % Extensive experiments on Occ-ScanNet and EmbodiedOcc-ScanNet demonstrate that VEOcc establishes new state-of-the-art performance in both local and embodied settings, providing an accurate and efficient solution for real-world exploration. Extensive experiments on Occ-ScanNet and EmbodiedOcc-ScanNet demonstrate that VEOcc establishes new state-of-the-art performance in both local and embodied settings. Notably, zero-shot evaluations on self-collected video sequences further confirm its robust out-of-distribution generalization capability in completely unseen real-world environments. Ultimately, our framework provides an accurate and highly efficient solution for autonomous exploration. Code and supplementary visualizations are available on our project page: this https URL.
### Title:
          DECICE: AI-Driven Scheduling and Digital Twin Integration for the Cloud-HPC-Edge Compute Continuum
 - **Authors:** Aasish Kumar Sharma, Felix Stein, Mirac Aydin, Michael Bidollahkhani, Sachin P. Nanavati, Mohsen Seyedkazemi Ardebili, Giorgi Mamulashvili, Mojtaba Akbari, Jonathan Decker, Zoya Masih, Julian M. Kunkel
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents the DECICE project (Device Edge Cloud Intelligent Collaboration framEwork), a Horizon Europe Research and Innovation Action (Grant No. 101092582, December 2022 to November 2025) that developed an open-source framework for intelligent workload scheduling across the cloud-HPC-edge compute continuum. A consortium of 12 partners across 6 European countries organized the work into six work packages covering AI-driven scheduling, digital twin infrastructure, system architecture and integration, monitoring, use case validation, and dissemination. The two core technical contributions are an Integrated AI Scheduler (IAIS) employing RNN-based prediction and formal workflow modeling for constraint-aware workload mapping, and a Digital Twin aggregating real-time metrics with carbon intensity and anomaly prediction for energy-aware scheduling. The framework operates within Kubernetes environments, supports unified workflow ingestion from multiple formats, and bridges cloud-native and HPC orchestration through a Slurm integration layer. We present the project vision, the overall architecture, contributions from each work package, quantitative evaluation results, and the open-source release.
### Title:
          A general tensor-structured compression scheme for efficient large language models
 - **Authors:** Ying Lu, Peng-Fei Zhou, Qi-Xuan Fang, Pan Zhang, Shi-Ju Ran, Gang Su
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Quantum Physics (quant-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are dominated by dense linear transformations, whose storage, memory and computational overheads hinder efficient adaptation and deployment while masking the functional impacts of structural simplification. Here we present Tensor Mixture (MixT), a general tensor-structured compression scheme that replaces targeted dense linear layers with natively executable mixtures of tensor operators. Operating directly on generic linear projections instead of model-specific components, MixT is potentially applicable across Transformer-based LLMs and other dense neural mappings. We evaluate MixT on Qwen3-8B and LLaMA2-7B under a unified recovery protocol, identifying a broad compressible regime in which MMLU accuracy is largely preserved before an abrupt transition at model-specific boundaries. This transition coincides with coordinated shifts in output entropy, prediction entropy and inter-layer geometry. At the LLaMA2-7B transition boundary, MixT reduces full-model parameters by 47.5\%, inference FLOPs by 37.1\%, training FLOPs by 52.1\% and peak inference memory by 60.4\%, demonstrating its practical potential for lower-cost LLM compression.
### Title:
          PDEInvBench: A Comprehensive Dataset and Design Space Exploration of Neural Networks for PDE Inverse Problems
 - **Authors:** Divyam Goel, Nithin Chalapathi, Sanjeev Raja, Aditi S. Krishnapriyan
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inverse problems in partial differential equations (PDEs) involve estimating the physical parameters of a system from observed spatiotemporal solution this http URL networks are well-suited for PDE parameter estimation due to their capability to model function-to-function space transformations. While existing benchmarks of machine learning methods for PDEs primarily focus on the forward problem, there are no similar comprehensive studies and benchmark datasets on PDE inverse problems, i.e., mapping solution fields to underlying physical parameters. We fill this gap by introducing PDEInvBench, a comprehensive benchmark dataset consisting of numerical simulations for both time-dependent and time-independent PDEs across a wide range of physical behaviors and parameters. Our dataset includes evaluation splits that assess performance in both in-distribution and various out-of-distribution settings. Using our benchmark dataset, we comprehensively explore the design space of neural networks for PDE inverse problems along three key dimensions: (1) optimization procedures, analyzing the role of supervised, self-supervised, and test-time training objectives on performance, (2) problem representations, where we study the value of architectural choices with different inductive biases and various conditioning strategies, and (3) scaling, which we perform with respect to both model and data size. Our experiments reveal several practical insights: 1) neural networks perform best with a two-stage training procedure: initial supervision with PDE parameters followed by test-time fine-tuning using the PDE residual, 2) incorporating PDE derivatives as input features consistently improves accuracy, and 3) increasing the diversity of initial conditions in the training data yields greater performance gains than expanding the range of PDE parameters. We make our dataset and codebase publicly available.
### Title:
          MARVEL: Universal Murray's Law-informed Vessel Tree Segmentation and Topology Estimation
 - **Authors:** Yi Zhou, Thiara Sana Ahmed, Jacqueline Chua, Meng Wang, Qinrong Zhang, Alejandro F. Frangi, Huazhu Fu, Jun Cheng, Leopold Schmetterer, Bingyao Tan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vascular circulation follows fundamental biophysical principles that optimize mass transport and metabolic energy expenditure, which can be effectively modeled by Murray's law. However, contemporary deep learning methods for vascular segmentation often neglect these biophysical constraints. This leads to physiologically implausible branching and misclassification vascular trees, rendering. These automated segmentation results are unreliable unreliable for downstream clinical tasks such as blood flow simulation or disease quantification. In this paper, we introduce MARVEL (Universal MurrAy's law-infoRmed Vessel sEgmentation and topoLogy estimation), a backbone-agnostic framework that integrates biophysical priors into vascular tree extraction. MARVEL combines per-pixel supervision with explicit radius predictions to enforce local bifurcation constraints derived from an empirical width-exponent mapping. We implement these constraints as differentiable regularizers during training to guide models toward physiologically consistent reconstructions. We evaluate MARVEL on eight public datasets across multiple vascular modalities and segmentation backbones. Results demonstrate MARVEL's superior performance in segmentation accuracy, topological consistency, and physiological plausibility. By converting segmented masks into graph-based hemodynamic simulations, we demonstrate that MARVEL preserves the subtle pathological narrowing and topological connectivity required to distinguish hypertensive from normotensive eyes. Results show that MARVEL significantly improves the classification of hypertension via arteriovenous pressure differences in the eye (p < 0.001), outperforming baseline models in both topological consistency and clinical predictive value.
### Title:
          Architectural Limits of Cloud TPUs in Finite-Field Cryptography
 - **Authors:** Hung Dang, Xuan Phu Dang, Tue Nguyen
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We empirically characterise the cost-efficiency deficit between cloud Tensor Processing Units and GPUs for finite-field cryptography. Against A100 GPU baselines (cuZK), we measure a $[5{,}558\times, 6{,}908\times]$ deficit across v5p and v4 architectures under an FP32-mantissa staging discipline, and a $\sim$$4{,}693\times$ deficit using v5p's native \texttt{int32} accumulator. We analytically project this deficit into a fundamental arithmetic penalty (lacking wide-integer ALUs) and a spatial penalty. We demonstrate that evaluating concurrent multi-tenant deployments, where strict separation forces eager Montgomery reduction, yields a projected $5.19\times$ spatial collapse; relaxing this constraint theoretically recovers these spatial cycles, yet the underlying arithmetic penalty remains. To facilitate this characterisation, we deploy \codename as a measurement vehicle. By mapping low-degree polynomials onto matrix-form Number Theoretic Transforms, the scheduler stacks heterogeneous polynomials into dense 2D matrices, achieving $\sim$$100\%$ K-dimension column occupancy on uniform workloads ($>$$92\%$ on mixed-degree traces). However, despite optimal K-dimension packing, severe M-dimension under-utilisation (e.g., $6.25\%$ on v4) combined with overwhelming VPU-bound Montgomery reduction stalls mathematically starve the systolic arrays. A post-hoc HLO validator ensures these measurements remain structurally isolated against the XLA fusion engine. Our findings empirically demonstrate the structural inadequacy of AI-optimised systolic arrays for exact, high-throughput field arithmetic.
### Title:
          Autoregression-Free Neural Operators for Time-Dependent PDEs
 - **Authors:** Jiaquan Zhang, Caiyan Qin, Haoyu Bian, Libin Cai, Yi Lu, Chaoning Zhang, Wei Dong, Yuanfang Guo, Yang Yang, Hen Tao Shen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators learn mappings from function-dependent inputs to solutions, providing an effective framework for solving partial differential equations (PDEs). For time-dependent PDEs, existing methods typically perform long-horizon prediction through autoregressive rollout directly in high-dimensional physical field spaces, where each predicted state is recursively fed back as the input for the next step. Although effective for short-term prediction, this autoregressive rollout and the lack of continuous-time modeling lead to progressive error accumulation over long-horizon rollouts. In this work, we propose Autoregression-Free Neural Operators (AFNO), which map the time evolution of PDEs into a latent space and model continuous-time vector fields within it. AFNO uses flow matching to learn the latent vector field, thereby enabling continuous evolution over extended horizons, avoiding autoregressive rollout and capturing dynamics under varying parameter configurations through explicit conditioning on physical parameters. Theoretical analysis and extensive experiments on six PDEs demonstrate that AFNO improves long-horizon prediction stability and consistently reduces rollout errors compared with the baselines.
### Title:
          LLM-as-a-Reviewer: Benchmarking Their Ability, Divergence, and Prompt Injection Resistance as Paper Reviewers
 - **Authors:** Lingyao Li, Junjie Xiong, Changjia Zhu, Runlong Yu, Chen Chen, Junyu Wang, Renkai Ma, Zhicong Lu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Computers and Society (cs.CY); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are increasingly used in academic peer review, yet their reliability, alignment with human judgment, and robustness to adversarial attacks remain poorly understood. We present a systematic benchmark of LLM-as-a-Reviewer on 898 papers stratified from NeurIPS and ICLR, evaluating 12 LLMs along three axes: rating calibration, divergence from human reviewers, and resistance to prompt injection embedded via an invisible font-mapping attack. We find that LLMs systematically overrate weaker submissions and diverge from humans in topical emphasis, under-flagging Clarity and over-flagging Reproducibility, while producing reviews two to three times longer with lower lexical diversity and a more standardized vocabulary. Prompt injection remains highly effective. Simple hidden instructions can promote low-scoring papers to acceptance-level ratings in a substantial fraction of cases, with effectiveness varying sharply across model families. While LLMs offer utility in structuring evaluations, their integration into peer review requires safeguards against both intrinsic biases and adversarial risks.
### Title:
          OPAL: Omnidirectional Path-efficient Aerial 3D expLoration
 - **Authors:** Yoga Satwik Chappidi, Avideh Zakhor
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous exploration is critical for robot mapping unknown environments. Desirable characteristics of exploration algorithms include compute efficiency and small traversed distance during the exploration process. Motivated by these, we present Omnidirectional Path-efficient Aerial 3D expLoration (OPAL), an exploration framework centered on deliberate 360-degree yaw rotation at ambiguous branch points rather than compute-heavy global tour planning. We devise multiple variants of OPAL to determine the frontier-selection strategy once the yaw pan is completed. One variant is model-free, while others use large language models (LLMs) or vision-language models (VLMs). We characterize the performance of these variants while varying the vicinity search radius to include frontiers in the selection process. Through simulations we find that although the time-consuming in-place yaw rotation increases total exploration time relative to more computationally complex baselines such as EDEN and FALCON, OPAL is computationally simpler and achieves shorter travel distances and higher coverage-versus-distance area under the curve. We also show that adjusting the frontier-selection search radius enables a tradeoff between travel distance and total exploration time. We verify our results on a Modal AI drone in two indoor environments by comparing OPAL against FALCON, and find that the traveled distance for a variant of OPAL to be as much as 25% lower than FALCON.
### Title:
          MetaphorVU: Towards Metaphorical Video Understanding
 - **Authors:** Zhuoqun Li, Boxi Cao, Guiping Jiang, Fangrui Lv, Ruotong Pan, Jianan Wang, Xiangyu Wu, Hongyu Lin, Yaojie Lu, Yong Du, Ruyin Jia, Liyan, Tingting Gao, Han Li, Xianpei Han, Le Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Metaphorical videos are prevalent across various real-world scenarios to convey complex ideas, and understanding them typically requires high-order cognitive capabilities. The lack of systematic studies on metaphorical video understanding not only constrains the real-world applicability of MLLMs but also impedes the thorough assessment of their high-order cognitive capabilities. To bridge this gap, we propose MetaphorVU-Bench, the first systematic and comprehensive benchmark dedicated to metaphorical video understanding. Through experiments, we find current MLLMs struggle with accurate metaphorical video understanding, lagging far behind human level, primarily due to defective cross-domain mapping. Motivated by this finding, we construct a metaphor knowledge graph as mapping augmentation and propose MetaphorBoost, an inference-time enhancement framework achieving consistent performance improvement. Our benchmark, analysis, and method provide useful insights and a foundation for future research on advancing MLLMs.
### Title:
          TapSampling: Inference-Time Sampling with a Task-Progress-Understanding Verifier for Robotic Manipulation
 - **Authors:** Sizhe Zhao, Shengping Zhang, Shuo Yang, Weiyu Zhao, Shuigen Wang, Xiangyang Ji
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing embodied control research demonstrates remarkable performance improvements by scaling training data and model size. We instead explore inference-time strategy as an alternative axis. Non-deterministic generative models, such as diffusion and autoregressive models, have been widely adopted in the field of embodied control. However, the single-shot inference paradigm limits their performance. In this paper, we propose \textbf{TapSampling}, a plug-and-play framework for inference-time sampling. First, we introduce an Action-VAE that represents actions in a low-dimensional latent space by mapping policy-generated initial actions into a compressed posterior distribution, from which any number of latent samples can be drawn and decoded into candidate actions that approximate the true action distribution. Second, we formulate action verification as task-progress outcome prediction, using the intrinsic sequential structure of robotic datasets to train a semantically grounded verifier for interpretable action selection. Furthermore, TapSampling is a policy-agnostic framework. Extensive experiments in both simulated and real-world environments demonstrate that our method substantially improves multiple generalist policies without further policy finetuning. Code and models are available at the project page.
### Title:
          Beyond Query Memorization: Large Language Model Routing with Query Decomposition and Historical Matching
 - **Authors:** Bo Lv, Jingbo Sun
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Optimizing the trade-off among predictive performance and computational cost is a central focus in the deployment of Large Language Models (LLMs). Current routing methods primarily rely on direct mapping from queries to models based on surface-level features, making them susceptible to the memorization trap and leading to poor generalizability on out-of-distribution (OOD) data. In this paper, we propose DecoR, a novel routing framework that recasts the routing task as a matching process of sifting similar queries from historical logs, effectively mitigating the memorization trap. To enhance matching accuracy, we introduce a query capability deconstruction method that decouples linguistic surface forms from task-intrinsic requirements, directing matching toward capability dimensions to ground decisions in essential task attributes. Furthermore, we develop CodaSet, a comprehensive benchmark for assessing routing generalization, where experimental results demonstrate that DecoR maintains superior accuracy while substantially lowering inference costs across both in-distribution and OOD settings. All the codes and data are available at this https URL.
### Title:
          Insuring Every Action: An Authority Frontier Framework for Runtime Actuarial Control of Autonomous AI Agents
 - **Authors:** Hao-Hsuan Chen
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Risk Management (q-fin.RM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous AI agents increasingly issue side-effect-bearing actions: database mutations, refunds, payments, external commitments. We propose the Actuarial Action Interface (AAI), a deterministic runtime contract that prices each such action against a contractually fixed safe default under a time-consistent risk mapping, and gates execution against a per-boundary reserve capital budget. We then develop the Authority Frontier, an evaluation primitive measuring how much autonomous authority the runtime releases at each level of reserve capital. The framework provides (i) a deterministic quote-bind-commit protocol with toll-bounded capability tokens; (ii) a universal seven-class action taxonomy mapping heterogeneous tool calls to comparable authority units; (iii) replay determinism and pathwise reserve coverage under alpha-spending; (iv) cross-domain normalization via full reserve demand C_full and capital metrics Capital@k. We instantiate AAI across four agentic environments (database mutation, customer-service refund, and the public tau-bench retail and airline tool-use traces) and report a live Postgres panel in which three Azure-hosted models propose actions through the same contract. The frontier exhibits a common low-reserve refusal and intermediate-release pattern across domains, with saturation only where the budget grid reaches full reserve demand; required reserve capital varies by 22x (Capital@50 from 289 to 6457). The framework does not force domains into the same shape; it surfaces each domain's actuarial geometry. In the live panel the contract prevents realized loss across all three models at low budget while differing in underwriting persistence under denial: model identity is an actuarial underwriting variable. The contribution is a benchmark-ready evaluation framework for runtime actuarial control of autonomous-agent side effects.
### Title:
          G-DRAGON: Geospatial Reasoning and Dynamic Planning for Retrieval-Augmented Outdoor Navigation
 - **Authors:** Dongzhihan Wang, Yi Du, Jianan Sun, Yuan Xue, Yingchen Zhang, Bing Xiao, Chen Wang, Liang Xu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous ground robots operating in large-scale outdoor environments require both robust long-range navigation and fine-grained ''last-mile'' exploration. Current advances in visual-language navigation (VLN) work well at short-range tasks, lacking geospatial grounding for long-distance missions. Some OpenStreetMap (OSM)-based methods relying on cloud-based Large Language Models (LLMs) are prone to factual hallucination and cannot conduct ''last-mile'' exploration based on human instruction. To address these challenges, we present G-DRAGON, a retrieval-augmented framework for outdoor, open-world navigation. This framework maps natural-language commands to versioned, local OSM entities via generative retrieval based on lightweight LLM, yielding accurate coordinates for global route planning. A high-level planning module bridges global topological routes with the SLAM system, projecting geospatial waypoints into the robot's navigable frame. For the ''last mile," the framework transitions to frontier-based exploration and open-set semantic voxel mapping to localize open-vocabulary targets. Experimental results in simulation demonstrate our framework outperforms state-of-the-art baselines. Furthermore, we validate the system in unseen real-world urban environments on an Unmanned Ground Vehicle (UGV), successfully completing person-search missions with trajectories of up to 500m.
### Title:
          Llamion Technical Report
 - **Authors:** Kisu Yang, Yoonna Jang, Hyeonseok Moon, Hwanseok Jang, Taewoo Lee, Hyungjin Lee, Jeseung Lee, Juhyoung Park, Heuiseok Lim
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We release Llamion, a family of 14B-parameter open-weight language models obtained by transforming Orion-14B into the standardized Llama-family architecture. The transformation is performed by Efficient Knowledge Preservation for Transformation (KEPT), a recipe that combines (i) Normal Parameter Mapping (NPM) for unchanged modules, (ii) Optimized Parameter Mapping (OPM), a training-free LayerNorm-to-RMSNorm initialization we prove optimal under the near-zero-mean activation regime induced by weight decay, and (iii) Cross-architecture Knowledge Distillation (XKD), an equal-size frozen-teacher distillation that aligns the converted model's outputs with the source model's on any reasonable input distribution. Llamion recovers Orion's behaviour on H6, MT-Bench, and KoMMLU with only ~123M tokens on a single A100 in four days; Llamion-Base reaches 66.87% on KoMMLU, exceeding the next-best entry of the Open Ko LLM Leaderboard by >7.0 absolute points at submission time. Capabilities entirely absent from the transfer corpus (Python programming and 200K-token context handling) survive the architectural transition intact. We release three checkpoints (Base, Chat, LongChat) that load with trust_remote_code=False in the Hugging Face Transformers library.
### Title:
          ParkourFormer: Integrating Predictive Supervision and Sequence Modeling into Parkour Locomotion
 - **Authors:** Yanheng Mai, Wenhao Xu, Zirui Huang, Yifei Fu, Shengwei Dong, Xinjue Wang, Kailun Huang, Yanzhe Xie, Renjing Xu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humanoid parkour requires locomotion policies to coordinate whole-body dynamics across rapidly changing terrains such as stairs, gaps, slopes, and obstacles. Existing reinforcement learning policies are largely reactive, mapping observations directly to actions without explicitly modeling future body states. Such modeling becomes critical in agile locomotion tasks where successful motion execution depends strongly on anticipating upcoming contact transitions and body this http URL present ParkourFormer, a Transformer-based sequence modeling framework that reformulates humanoid locomotion as a future-conditioned decision-making problem. The current robot state queries historical sensorimotor trajectories through cross-attention, while a lightweight prediction head forecasts short-horizon future proprioceptive states. The predicted future states, trained with supervised signals, are fused with temporal features to generate actions, enabling the policy to jointly reason over motion history and anticipated future dynamics. We evaluate ParkourFormer on a diverse multi-terrain humanoid parkour benchmark including stairs, gaps, slopes, rough terrain, and obstacle traversal. Experiments in simulation and on a real humanoid robot show that ParkourFormer achieves a 93.85% average traversal success rate on highly challenging terrains, with improvements of up to 42.73% over strong MLP, MoE-based MLP, and vanilla Transformer baselines, while maintaining a single unified policy across all terrain types. These results demonstrate that explicit future-state modeling significantly improves robustness and generalization for agile whole-body locomotion.
## Keyword: localization
### Title:
          A Large-Scale Dataset and Benchmark: Do Protein-Ligand Models Learn Binding Sites or Just Binding Likelihood?
 - **Authors:** Zhaohan Meng, Zhen Bai, Ke Yuan, Iadh Ounis, Zaiqiao Meng, Hao Xu, Joseph Loscalzo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Protein-ligand modeling underpins computational drug discovery and molecular design. Existing protein-ligand benchmarks typically evaluate whether a protein and ligand interact and how strongly they bind, through tasks such as binary binding prediction and affinity regression. However, these evaluations provide limited evidence of whether models can localize binding sites or identify the non-covalent interactions underlying molecular recognition. To address this gap, we introduce InteractBind, a large-scale protein-ligand dataset comprising approximately 100k protein-ligand pairs, together with a benchmark for fine-grained evaluation. The core fine-grained task is that of binding-site localization, which uses protein-residue and ligand-atom interaction maps spanning six major types of non-covalent interactions to assess whether model-derived interaction maps localize binding sites. InteractBind further includes binding affinity and protein similarity-controlled splits to support realistic generalization assessment. Using InteractBind, we evaluate eight existing sequence-based and interaction-aware models, assessing binary binding prediction and binding-site localization. Results reveal limited binding-site localization despite strong binary binding prediction, with marked variation across non-covalent interaction types. Overall, InteractBind establishes a benchmark paradigm that encourages the development of more interpretable and physically grounded protein-ligand models.
### Title:
          ViViD-5K: Vineyard vision dataset for field-based berry detection and segmentation and grape cluster closure estimation
 - **Authors:** Xiangzhi Tong, Chengrui Zhang, Mac Flaherty, Andre Matteo Garcia, Dominic Gorman, Jonathan Jaramillo, Justine E. Vanden Heuvel, Yu Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Other Quantitative Biology (q-bio.OT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cluster closure, defined as the progressive filling of gaps between the berries in a grape bunch, is a key trait in vineyard management, impacting disease risk. However, traditional visual scoring methods are labor-intensive, subjective, and lack temporal resolution. Existing datasets rarely support fine-grained berry-level analysis, limiting the development of robust deep learning models. In this work, we present ViViD-5k, a large-scale in-field Vineyard Vision Dataset containing 5,000 images with dense annotations, including over 648,000 berry centroids and cluster segmentation masks spanning 13 grape varieties. Building on this dataset, we introduce GrapeSAM, a two-stage visual pipeline that combines point-based berry localization with prompt-based segmentation using Segment Anything, followed by transformer-based cluster segmentation. The pipeline enables automated, in-field estimation of cluster closure with minimal supervision. Quantitative results demonstrate strong segmentation and counting accuracy across diverse conditions, while visualizations confirm robustness on both in-domain and out-of-domain samples. This work provides a scalable and objective alternative to manual compactness scoring and supports high-throughput grape phenotyping with enhanced spatial detail.
### Title:
          Elevator-LIO: Robust LiDAR-Inertial Odometry for Multi-Floor Navigation under Elevator-Induced Non-Inertial Motion
 - **Authors:** Yifan Zhang, Yudong Huang, Yuchong Zhang, Changze Li, Haoran Liu, Ming Yang, Tong Qin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents Elevator-LIO, a LiDAR-inertial odometry framework designed to achieve continuous robot localization during elevator travel, thereby supporting cross-floor robotic tasks. To address the state-estimation problem in non-inertial frames, Elevator-LIO establishes a decoupled state-estimation model that separately models the robot motion relative to the elevator and the elevator motion itself, and embeds it into a mode-dependent iterated error-state Kalman filter framework. This framework degenerates to conventional LIO estimation in ordinary indoor environments, while enabling the propagation and constrained update of elevator-related states in elevator non-inertial environments, thereby achieving continuous and stable localization. An elevator mode manager detects elevator entry and exit events using LiDAR ranging statistics and estimated states, and introduces event-triggered zero-velocity and zero-acceleration updates when the elevator stops to suppress accumulated vertical drift. In addition, this paper adopts an adaptive voxel downsampling strategy to maintain a stable number of effective points under significant environmental scale changes. We conduct extensive experiments on 20 real-world sequences containing 79 elevator rides, including practical challenges such as large-scale spaces, long vertical travel, dynamic pedestrian interference, and mirror reflections. The results show that Elevator-LIO maintains continuous localization accuracy in all sequences, with terminal height error below 1 cm in 17 sequences. In contrast, existing representative localization systems perform poorly on these elevator sequences. Tests on the Hilti 2022/2023 datasets further show that the proposed method remains competitive in standard indoor scenarios. The project page is available at this https URL.
### Title:
          EgoAction: Egocentric Action Composition with Reliability-Aware Temporal Fusion for the EPIC-KITCHENS Action Detection Challenge at CVPR 2026
 - **Authors:** Zhiheng Fu, Zixu Li, Zhiwei Chen, Fangxu Liu, Yupeng Hu, Weili Guan, Liqiang Nie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The EPIC-KITCHENS-100 Action Detection challenge evaluates whether a model can localize the start and end of each action in long untrimmed egocentric videos and assign the corresponding verb--noun action label. In this report, we formulate our submission as EgoAction (Egocentric Action Composition with Reliability-Aware Temporal Fusion), a unified decoupled detection and fusion pipeline. The pipeline uses EPIC-finetuned VideoMAE-L features, trains separate noun and verb temporal detectors with causal temporal modeling, composes action hypotheses from top noun--verb pairs, and introduces a confidence-adaptive boundary fusion rule at post-processing time. The key observation is that verb and noun streams often fail differently: verb scores are sensitive to motion transitions, whereas noun scores are sensitive to hand-object visibility and object clutter. A fixed arithmetic mean of their predicted boundaries can therefore amplify localization errors when one stream degenerates. We replace this hard-coded mean with Dynamic Weighted Fusion (DWF), which normalizes the maximum noun and verb classification confidences into proposal-wise boundary weights and linearly combines the two intervals. This lightweight tensor-only operator shifts boundary authority toward the more reliable stream while preserving the decoupled action scoring mechanism. Together with sliding-window inference, top-K noun--verb action composition, and class-wise Soft-NMS, EgoAction provides a compact and reproducible system for egocentric temporal action detection.
### Title:
          FoodMonitor: Benchmarking MLLMs for Explainable Compliance Analysis
 - **Authors:** Ruihao Xu, Xingming Shui, Jingxuan Niu, Yiqin Wang, Jilin Yu, Haoji Zhang, Yansong Tang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As AI-powered compliance monitoring becomes increasingly important in public governance and industrial safety, the ability to provide verifiable evidence and traceable accountability signals is essential. However, existing video anomaly detection datasets focus on event-level binary classification, lacking the rule-driven, explainable analysis required for real-world compliance scenarios. We introduce FoodMonitor, a benchmark for explainable compliance analysis in commercial kitchen surveillance. FoodMonitor comprises 477 video clips with 3,307 violation annotations across a dual-channel design covering both person-level and environment-level violations. Each annotation specifies which rule was violated, what non-compliant behavior occurred, and who committed it with frame-level bounding boxes. We establish a unified evaluation protocol with a two-stage matching mechanism that separately assesses spatial localization and semantic understanding, along with a composite metric ($C_{\text{score}}$) that balances environment and person detection performance. Systematic evaluation of several state-of-the-art multimodal large language models reveals that the best-performing model achieves only 0.360 $C_{\text{score}}$, with spatial localization and fine-grained rule understanding emerging as the primary bottlenecks. Our analysis identifies two distinct failure modes: localization-dominated errors and semantics-dominated errors, providing diagnostic insights for future model development.
### Title:
          TS-Skill: A Benchmark for Evaluating Analytical Skills in Time-Series Question Answering
 - **Authors:** Liying Han, Kang Yang, Oliver Wang, Jason Wu, Pengrui Quan, Gaofeng Dong, Ozan Baris Mulayim, Sizhe Ma, Yuyang Yuan, Dezhi Hong, Mario Berges, Mani Srivastava
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) and time-series language models (TSLMs) are increasingly applied to time-series question answering (TSQA). Unlike text-only QA, TSQA requires models to ground answers in temporal signals whose patterns may occur at different scales, specific time locations, or across separated intervals. However, existing benchmarks are typically organized by task types or high-level reasoning categories, making it difficult to diagnose the underlying signal-level capabilities driving model performance. We introduce TS-Skill, a controlled benchmark for evaluating three composable analytical skills in TSQA: temporal scale selection (SK1), temporal localization (SK2), and cross-interval integration (SK3). TS-Skill provides timestamp-aware questions, broad domain coverage, and human-validated QA quality. To construct the benchmark at scale, we develop SKEvol, a skill-guided agentic framework that combines domain-aware time-series seed generation, skill-controlled question generation, metadata- and code-assisted answer construction, multi-phase signal-grounded verification, and human-in-the-loop curation. Experiments on ten state-of-the-art LLMs and TSLMs reveal substantial and uneven capability gaps across SK1-SK3. In particular, SK3 remains consistently challenging for non-agent models, whereas tool-augmented agents show a selective advantage on standalone SK3. These findings demonstrate that skill-level evaluation can uncover temporal reasoning failures that are obscured by aggregate TSQA scores.
### Title:
          Calibrating Probabilistic Object Detectors with Annotator Disagreement
 - **Authors:** Zhi Qin Tan, Owen Addison, Yunpeng Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High degrees of disagreement among annotators can exist for ambiguous objects, e.g. in medical images, underscoring the challenges of establishing ground truth annotations in object detection tasks. Despite this, all existing object detectors implicitly require access to ground truth annotations for either training or evaluation. The fundamental questions we target are: How can we learn an object detector with multiple annotators' annotations but without objective ground truth annotations due to object ambiguity, and how can we enable the learned detector to express meaningful model predictive uncertainties in detecting ambiguous objects? To answer these questions, we present an interpretable approach to calibrate probabilistic object detectors, where the calibration goal is to align the class confidence and bounding box variance estimates to the annotators' annotation distribution. We introduce an efficient yet effective framework to calibrate probabilistic object detectors by designing four evaluation metrics to measure calibration errors regarding classification and localization, and proposing a train-time calibration and post-hoc calibrator, all without the need to access any ground truth. This framework is generalizable to many existing probabilistic object detectors, such as the YOLO families and two-stage detectors. Empirical results with real-world and synthetic datasets of medical and natural images demonstrate the superior performance of the proposed framework with three popular object detectors.
### Title:
          Multiscale Real-Time Object Detection in the NMS-Free Era: A Comparative Performance Evaluation of YOLOv8 and YOLO26
 - **Authors:** Chidera G. Oguine, Kanyifeechukwu J. Oguine, Obiozor M. Oguine, Ozioma C. Oguine
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Non-Maximum Suppression (NMS) remains a key post-processing step in many real-time object detection pipelines, but it can introduce latency variation and deployment complexity in resource-constrained settings. Recent NMS-free designs such as YOLO26 aim to reduce this dependence through end-to-end detection, yet their performance relative to established NMS-based models such as YOLOv8 remains underexplored beyond standard benchmarks. This paper compares YOLOv8 and YOLO26 on Pascal VOC and VisDrone, representing general object detection and dense aerial small-object detection, respectively. Both model families are evaluated across five scales using accuracy, localization, model size, GFLOPs, and CPU/GPU latency. Results show that YOLO26 achieves stronger detection performance and lower model complexity on Pascal VOC across most scales, while the performance gap narrows on VisDrone, where both models struggle with dense small targets. YOLOv8 remains competitive in GPU latency, showing that NMS-free design does not guarantee universal deployment superiority. Overall, the study shows that detector selection depends on dataset characteristics, object scale, model capacity, and hardware constraints.
### Title:
          Interpretability Transfer from Language to Vision via Sparse Autoencoders
 - **Authors:** Alexey Kravets, Da Li, Chuan Li, Da Chen, Vinay P. Namboodiri
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in language model interpretability using sparse autoencoders (SAEs) have yet to effectively translate to the visual domain, mainly due to the difficulty and ambiguity of labeling visual concepts. In this paper, we introduce Visual Interpretability via SAE Transfer Alignment (VISTA), a framework that transfers interpretability from language to vision in a LLaVA-style vision-language model by constraining a visual projector to map visual tokens into an LLM's pre-existing, labeled textual SAE space. This approach enables visual interpretability without training dedicated vision SAEs. By regularizing the projector using the LLM's SAE reconstruction loss, VISTA achieves a threefold increase in the matching rate, which measures how accurately the most activating textual concepts in the SAE space correspond to semantic elements in the image. Using this framework, we further analyze spatial localization properties of different vision encoders and show that DINOv2 features have stronger localization abilities than other encoders. Leveraging this precision, we validate VISTA's cross-modal alignment through fine-grained, localized concept interventions, where specific objects are removed or replaced in the model's perception while preserving the surrounding scene. This results in improvements of 35% in object removal and 47% in object replacement tasks over vision-only baselines, providing causal evidence that visual tokens inhabit the text SAE manifold. These contributions are validated across multiple LLM architectures.
### Title:
          TinyFormer: Preserving Tiny Objects in YOLO-DETRHybridReal-time Detectors
 - **Authors:** Jun-Wei Hsieh, Meng-Yu Kao, Ghufron Wahyu Kurniawan, Kuan-Chuan Peng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 YOLO-series and DETR-based detectors struggle with tiny-object detection. YOLO-style models benefit from efficient dense prediction, but their large-stride backbones may suppress tiny instances in deep feature maps and make grid assignment ambiguous. DETR-based models remove hand-crafted post-processing through set prediction, yet they reason over coarse token grids, where tiny objects occupy only a few weak tokens and are easily overlooked during matching. To address these limitations, we propose TinyFormer, a unified YOLO--DETR hybrid real-time detector that combines ViT representations, NMS-free set prediction, and a YOLO-style pyramid neck for accurate small-object detection. TinyFormer introduces a Parallel Bi-fusion Module (PBM), which builds high-resolution shortcuts from shallow stages to the feature pyramid, preserving fine spatial details during multi-scale fusion. We further design a Spatial Semantic Adapter (SSA) to compensate for the spatial loss caused by coarse tokenization. SSA extracts high-resolution cues from early stages and injects them into transformer token embeddings, improving tiny-object localization without sacrificing the global modeling ability of DETR. Experiments on MS COCO show that TinyFormer consistently outperforms recent YOLO-series detectors and the strong DEIMv2 baseline. TinyFormer-X achieves 58.4% AP even without PBM, while adding PBM improves the overall AP to 58.5% and brings a 1.6% AP gain on small objects. With Objects365 pre-training, TinyFormer-X-PBM reaches 60.2% AP, surpassing RF-DETR and other Objects365-pretrained detectors with fewer parameters and lower computation. These results demonstrate that TinyFormer bridges dense YOLO-style feature fusion and DETR-style set prediction, providing a strong accuracy-efficiency trade-off for real-time tiny-object detection. Code is available at this https URL.
### Title:
          Localization then Neutralization: Gradient-guided Token Suppression against Visual Prompt Injection Attack
 - **Authors:** Dongpeng Zhang, Ke Ma, Yangbangyan Jiang, Gaozheng Pei, Longtao Huang, Qianqian Xu, Qingming Huang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adversarial images pose a severe security threat to multimodal large language models through prompt injection. Existing defenses largely lack a principled understanding of the underlying mechanisms and struggle to balance efficiency and defense utility. In this work, we show that successful adversarial attacks do not rely on the entire image uniformly but instead depend on a small subset of critical image tokens. Based on this insight, we propose Gradient Token Masking (GTM), which localizes these tokens via gradient analysis and neutralizes them through masking. We find that attribution based on the first generated token's output probability fails when attacks preserve the predicted token. To overcome this, GTM utilizes the Hidden-State Gradient Norm score for generation-influence attribution under adversarial inputs. We prove that its ranking is consistent with that of the full adversarial loss gradient, providing a theoretical guarantee for accurate localization. Our method requires only a single forward-backward pass to identify and zero out a small number of high-scoring tokens, effectively disrupting the adversarial attack path. Extensive experiments on prompt injection and multimodal jailbreak attacks demonstrate that our approach reduces attack success rates (ASR) to near zero while preserving model utility with negligible computational overhead.
### Title:
          InvariantCloud: A Globally Invariant, Uniquely Indexed Point Cloud Framework for Robust 6-DoF Tactile Pose Tracking
 - **Authors:** Pengfei Ye, Yuxiang Ma, Yi Zhou, Wei Chen, Wenzhen Dong, Molong Duan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in imitation learning and vision-language models highlight the need for high-fidelity tactile perception, with 6-DoF tactile object pose estimation providing a crucial foundation for precise robotic manipulation. We introduce InvariantCloud, a 6-DoF pose estimation framework that leverages the global invariance of surface marker constellations on vision-based tactile sensors. In contrast to recent approaches, our one-shot globally invariant point cloud registration suppresses cumulative drift and overcomes long-standing limitations in accurately estimating yaw (Z-axis) rotation. Experimental verifications show that InvariantCloud achieves superior yaw tracking accuracy and re-localization repeatability compared to existing benchmarks, demonstrating its precision and robustness in long-sequence manipulation tasks.
### Title:
          FusionCore: A 23-State Unscented Kalman Filter for IMU, Wheel Encoder, GPS, and Visual SLAM Fusion in ROS 2
 - **Authors:** Manan Kharwar (Independent Researcher, Hamilton, ON, Canada)
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present FusionCore, an open-source ROS 2 sensor fusion package that fuses IMU, wheel encoder odometry, GPS, and Visual SLAM pose into a single 100 Hz odometry stream using a 23-state Unscented Kalman Filter (UKF). The 23rd state is an online estimate of the wheel encoder's systematic yaw rate bias, identified through GPS heading cross-covariance and subtracted during GPS blackouts to reduce heading drift in coast mode. FusionCore also estimates gyroscope and accelerometer biases as explicit filter states, handles GPS natively in ECEF without a separate coordinate projection node, applies per-sensor Mahalanobis chi-squared outlier gating calibrated to measurement degrees of freedom, and adapts sensor noise covariance automatically from the innovation sequence. VSLAM pose fusion enables GPS-denied operation with any visual odometry or SLAM system, including automatic recovery from map reinitialization. We evaluate against robot_localization on twelve full-length sequences (55-92 min each) from the NCLT public dataset. FusionCore achieves lower Absolute Trajectory Error (ATE) on ten of twelve sequences, with improvements ranging from 1.2x to 22.2x on winning sequences. The robot_localization UKF diverges numerically on all twelve sequences. FusionCore is available at this https URL under the Apache 2.0 license.
### Title:
          MTLLFM: Multimodal-Temporal Laughter Localization: UR-FUNNY-Temporal and SMILE-Temporal Benchmarks with an Adaptive Multimodal Fusion Model
 - **Authors:** Eyal Hanania, Nadav Kirsch, Daniel Arkushin, Jonathan Benvenisti, Amos Bercovich, Elie Zemmour, Sahar Froim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Detecting laughter in video is essential for affective computing and narrative understanding, yet existing approaches treat it as coarse clip-level classification, failing to capture precise temporal boundaries of brief, transient laughter events. We address this gap with two complementary contributions. First, we introduce UR-FUNNY-Temporal and SMILE-Temporal, fully annotated temporal laughter datasets extending two widely-used humor benchmarks. Our annotations cover over 11,053 videos (78.8 hours) and provide precise onset/offset boundaries for each laughter event, along with rich metadata distinguishing speaker vs. audience laughter, modality dominance (acoustic, visual, or both), and intensity levels. Second, we propose a lightweight weakly-supervised framework for temporal laughter localization. Our architecture combines fixed HuBERT and MAE encoders with temporal softmax pooling and adaptive modality gating, learning fine-grained temporal grounding from clip-level labels without requiring frame-level annotations during training. Experiments across three datasets demonstrate that our approach substantially outperforms multimodal foundation models including Gemini 3 Flash, achieving 99% F1 and 68.1% localization precision on sports broadcast data. Ablations validate each architectural component. Furthermore, our precise temporal tags improve downstream laughter reasoning by 227% on CIDEr, enabling GPT-3.5 to outperform GPT-4o. The code, UR-FUNNY-Temporal and SMILE-Temporal datasets are publicly available at this https URL.
### Title:
          A Heuristic Approach to Localize CSS Properties for Responsive Layout Failures
 - **Authors:** Tasmia Zerin, B M Mainul Hossain, Kazi Sakib
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Responsive Layout Failures (RLFs) typically arise from CSS properties that hinder proper layout behavior in different screen sizes. To find an accurate and effective solution for repairing RLFs, localization of those problematic properties is necessary. However, existing approaches only detect RLFs and apply broad CSS patches for them. The patches alter the entire layout without localizing the root cause of failure. To address this gap, we propose a heuristic approach to identify the specific CSS properties that developers would typically localize manually. The approach first detects the RLFs existing in a webpage and their affected elements. Next, it localizes the nearby HTML elements using RLF direction and relative alignment of the elements present in the RLF region. The involved CSS properties of those elements are then identified using a ranked search set of CSS properties, created by analyzing Quora and Stack Overflow queries. Finally, elements and their corresponding property pairs are ranked based on their impact on RLFs. We have implemented this approach into a tool called {\normalfont \textsc{LocaliCSS}} and evaluated it on a set of webpages using Top N Rank, MRR and P@K metrics. The tool achieved localization accuracy ranging from 45.2% (Top-1) to 92.86% (Top-7), with an MRR of 76% and a P@3 of 77.13%. Additionally, experienced front-end engineers manually localized the RLFs as part of our evaluation. Their preferred CSS properties matched the suggestions from our approach in 42.86% of cases for Top-1 rankings and up to 90.48% for Top-7 rankings.
### Title:
          An Efficient and Privacy-Preserving Architecture for Cross-Institutional Collaborative RAG
 - **Authors:** Chenxin Mao, Shangyu Liu, Zhenzhe Zheng, Fan Wu, Jie Wu, Guihai Chen
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Retrieval-Augmented Generation (RAG) empowers LLMs with external knowledge, making cross-institutional domain-specific knowledge base integration a highly promising deployment paradigm. Despite this potential, strict privacy regulations create severe "data silos" that obstruct such collaboration. Building federated RAG systems requires distributed inference, but the Transformer's self-attention mechanism fundamentally conflicts with this by mandating cross-node access to distributed Key-Value caches. To address this challenge, we present FedRAG, a high-throughput, privacy-preserving federated RAG framework. At its core is a novel Scrambled Distributed Attention protocol that utilizes numerically stable feature scrambling and token permutation. By dynamically delegating scrambled computations to collaborating nodes, our system successfully decouples attention execution from data localization without exposing plaintext. Crucially, our approach requires no specialized hardware or model retraining, circumventing the prohibitive latency and communication overheads of cryptographic solutions while robustly defending against intermediate state inversion attacks. Extensive evaluations demonstrate our framework preserves negligible (<0.1\%) model utility degradation and achieves up to a 62$\times$ latency reduction over existing secure baselines, sustaining practical, human-reading throughput for cross-institutional knowledge synergy.
### Title:
          TTPrint: Evidence-Grounded TTP Extraction via Diverge-then-Converge Verification
 - **Authors:** Yutong Cheng, Changze Li, Raihan Sultan Pasha Basuki, Qian Cui, Wei Ding, Peng Gao
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Extracting MITRE ATT&CK techniques from cyber threat intelligence (CTI) reports is an open-set, multi-label problem requiring both high recall (not missing techniques) and high precision (not hallucinating unsupported ones). Existing methods--rule-based, supervised, and LLM-based--struggle to achieve both: rule-based and supervised approaches lack generalizability across diverse attack descriptions, while LLM-based approaches that couple candidate generation and validation within a single inference step suffer from limited recall and precision simultaneously. We propose TTPrint, which addresses this challenge through a diverge-then-converge design inspired by how human analysts work: first extracting broadly, then verifying rigorously. In the divergent phase, reports are decomposed into atomic behaviors and candidate techniques are proposed broadly. A deterministic span localization stage then anchors each candidate to a specific evidence window in the source text. A convergent verification stage retains only candidates supported by both the localized evidence and the authoritative MITRE definition. We contribute two evaluation resources--a cleaned TRAM benchmark (TRAM-Clean) and a new annotated dataset (TTPrint-Bench)--to address known annotation noise in existing benchmarks and elevate the task to document-level TTP extraction. On TRAM-Clean and TTPrint-Bench, TTPrint achieves 76.48% and 87.39% macro-F1 respectively, outperforming the leading baseline by 63.5% and 29.4%. A multi-backbone analysis across six LLMs and a threshold sensitivity study further demonstrate generalizability across model choices and provide practical guidance for parameter selection.
### Title:
          RePlan-Bot: Multi-Level Replanning for Embodied Instruction Following
 - **Authors:** Xicheng Gong, Guozheng Sun, Peiran Xu, Yadong Mu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Embodied instruction following (EIF) requires agents to understand and execute complex natural language commands within interactive 3D environments. Despite recent advances, existing methods often fail in long-horizon planning and handling irreversible state changes, resulting in low task success rates. To address these challenges, we introduce RePlan-Bot, a novel EIF agent that performs multi-level, continuous replanning throughout task execution. RePlan-Bot integrates a high-level LLM-based auditor for dynamic sub-goal adjustments guided by environmental feedback, a commonsense-guided search mechanism based on a multi-layered instance map for precise and structured object localization, and a lightweight ViT-based corrector to preemptively fix risky low-level actions. Evaluated on the ALFRED benchmark, RePlan-Bot achieves state-of-the-art performance in both seen and unseen environments, demonstrating superior adaptability and reliability.
### Title:
          EchoPilot: Training-Free Ultrasound Video Segmentation via Scale-Space Semantic Prompting and Reliability-Gated Memory
 - **Authors:** Ruiqiang Xiao, Zhaohu Xing, Yijun Yang, Zhenyan Han, Weiming Wang, Kaishun Wu, Lei Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ultrasound video segmentation is clinically valuable yet difficult due to speckle noise, weak boundaries, and rapid anatomical deformation. Recent promptable foundation models enable point-guided segmentation, but their direct deployment in ultrasound remains unreliable: a single point provides insufficient spatial context to resolve scale ambiguity, and greedy memory updates amplify early errors into severe temporal drift. We present EchoPilot, a training-free framework for ultrasound video segmentation under sparse first-frame interaction, requiring only a single point click and an anatomical category name. EchoPilot orchestrates a frozen medical vision-language model (VLM) for semantic localization, a vision foundation model (VFM) for dense geometric feature extraction, and a promptable video segmentor for mask prediction and propagation. To resolve initialization ambiguity, we propose Scale-Space Semantic Prompting, which first selects an optimal contextual view via a parameter-free S.E.E.D. (Semantic Energy-Entropy Density) criterion, and then synthesizes geometrically precise auxiliary point prompts from dense foundation features without additional user interaction. To reduce propagation drift, a Reliability-Gated Memory update is further introduced to selectively freeze the segmentor's memory bank under uncertain predictions, preventing error accumulation. We also contribute the first dynamic fetal placenta ultrasound video segmentation dataset with 671 annotated frames. Across three ultrasound video datasets, EchoPilot achieves state-of-the-art performance under the sparse-interactive setting, consistently outperforming training-free baselines and finetuned specialists.
### Title:
          LLaVA-OneVision-2: Towards Next-Generation Perceptual Intelligence
 - **Authors:** Xiang An, Yin Xie, Feilong Tang, Yunyao Yan, Huajie Tan, Didi Zhu, Changrui Chen, Xiuwei Zhao, Bin Qin, Kaicheng Yang, Yifei Shen, Yuanhan Zhang, Kaichen Zhang, Wenkang Zhang, Zheng Cheng, Nansen Zhang, Chunsheng Wu, Chunjiang Ge, Zimin Ran, Dehua Song, Chunyuan Li, Shikun Feng, Ming Hu, Zhangquan Chen, Junbo Niu, Bo Li, Ziyong Feng, Ziwei Liu, Zongyuan Ge, Jiankang Deng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce LLaVA-OneVision-2 (LLaVA-OV-2), the most capable vision-language model in the LLaVA-OneVision series to date, achieving superior performance across a broad range of multimodal benchmarks. The model builds on a native OneVision-Encoder and incorporates Windowed Attention for efficient local computation while maintaining native resolution. Its key advance is codec-stream tokenization: it treats compressed video as a continuous bit-cost stream, where bit-cost dynamics determine adaptive temporal groups, and motion-residual cues select salient spatial evidence into compact visual canvases. This allocation concentrates a limited token budget on event-bearing content, enabling more stable long-video token compression than fixed groups of pictures. A shared 3D RoPE further places codec canvases, sampled frames, and images in a unified spatiotemporal coordinate system. Furthermore, we build the LLaVA-OV-2 data and training stack around large-scale open supervision: approximately 8M re-captioned video samples for pretraining, a 4M-sample spatial corpus for fine-tuning. We also introduce JumpScore, a temporal-localization benchmark targeting fine-grained grounding in high-frequency, densely repeated motion, a regime underrepresented by existing video evaluations. A standout capability of LLaVA-OV-2 is its unified perception across video understanding, temporal grounding, spatial grounding, and manipulation-trace reasoning. On JumpScore, LLaVA-OneVision-2-8B reaches 74.9 JumpScore mAP, surpassing Qwen3-VL-8B (30.1) by +44.8 points; under matched visual-token budgets on the same benchmark, codec-stream inputs improve temporal grounding over frame sampling by +9.7 points. Across standard benchmarks, LLaVA-OneVision-2-8B further outperforms Qwen3-VL-8B by +4.3 average points on video tasks, +5.3 on spatial tasks, and +15.6 average J&F on tracking tasks.
### Title:
          Goal-driven Bayesian Optimal Experimental Design for Robust Decision-Making Under Model Uncertainty
 - **Authors:** Jinwoo Go, Xiaoning Qian, Byung-Jun Yoon
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bayesian optimal experimental design (BOED) selects experiments to maximize information gain about model parameters. However, in decision-critical settings, reducing parameter uncertainty does not necessarily improve downstream decisions, as only specific parameter directions relevant to the objective truly matter. We propose GoBOED, a goal-driven BOED framework that directly optimizes experimental designs for a specified decision-making objective. GoBOED combines an amortized variational posterior surrogate with a differentiable convex decision layer, enabling gradient-based design optimization that is fully decision-focused. We theoretically show that GoBOED gradients are insensitive to parameter directions irrelevant to the decision objective, providing a formal justification for why goal-driven design achieves equivalent decision quality over a wider set of experimental designs than information-gain maximization. Empirically, across source localization, epidemic management, and pharmacokinetic control, GoBOED identifies designs that better align with downstream decision objectives and reveals that near-optimal design windows are substantially wider than those predicted by goal-agnostic BOED approaches.
### Title:
          Pixel-Level Pavement Distress Assessment Using Instance Segmentation
 - **Authors:** Logan Dewick (University of Wisconsin - Green Bay), Bibesh Pyakurel (University of Wisconsin - Green Bay), Kong Pheng Yang (University of Wisconsin - Green Bay), Nazim Choudhury (University of Wisconsin - Green Bay), M. G. Sarwar Murshed (University of Wisconsin - Green Bay)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated pavement distress assessment requires more than image-level classification or coarse bounding box detection, demanding precise localization of thin, branching, and irregular cracks to achieve the geometric precision necessary for maintenance-relevant quantification. This paper presents a vision-based pavement distress analysis system based on Mask R-CNN instance segmentation and evaluates it on UWGB-StreetCrack, a custom field-collected roadway image dataset acquired with a vehicle-mounted smartphone and manually annotated with polygon labels for longitudinal cracks, transverse cracks, alligator cracks, and potholes. Five Detectron2-based Mask R-CNN backbone variants were considered under a consistent fine-tuning protocol. The best-performing model, Mask R-CNN with a ResNet-101 FPN backbone, achieved 84.23% precision, 90.04% recall, and an F1 score of 87.04% under the project-specific bounding-box matching protocol. The same model produced an aggregate predicted crack-area fraction of 2.164%, closely matching the 2.170% ground-truth crack-area fraction. To contextualize the segmentation system against a detector-oriented alternative, a CSPDarknet53-based YOLO detector was also adapted and retrained on the dataset, reaching 27.5% precision and 20.7% recall on the validation protocol. The results show that instance segmentation is a practical direction for field pavement imagery and aggregate crack-area estimation, while also exposing open challenges in annotation consistency, class imbalance, confounder rejection, and mask-level benchmarking.
### Title:
          EVIDENT: Routing MLLM Adaptation through Entity-Grounded Visual Evidence for Cross-Domain Video Temporal Grounding
 - **Authors:** Geo Ahn, Jiwook Han, Youngrae Kim, Joonseok Lee, Jinwoo Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-tuning MLLMs for Video Temporal Grounding (VTG) often improves in-domain performance but degrades sharply under domain shift. In this work, we find that this failure is primarily driven not just by unseen query concepts, but by visual domain shift, which prevents the model from coupling its learned temporal localization knowledge with its inherent entity-attention capability. To address this, we introduce EVIDENT, a parameter-efficient adaptation framework that anchors temporal grounding in the inherent entity-attention of pre-trained MLLMs by routing VTG adaptation through explicit visual entity evidence. EVIDENT consists of three components: (i) an Entity Bottleneck Adapter that transforms dense visual tokens into compact entity-level slots, (ii) an Entity-Binding Distillation loss that instills objectness priors into the semantically unstructured MLLM visual space, guiding each slot to bind to a coherent entity, and (iii) an Entity-to-eVidence gating mechanism that leverages the captured entities as evidence, steering the model to localize moments containing query-relevant entities. Together, these components enable VTG fine-tuning to rely on entity-grounded evidence rather than brittle dataset shortcuts. Experiments on cross-domain VTG benchmarks show that EVIDENT consistently improves out-of-domain robustness while preserving competitive in-domain performance with modest parameter overhead. These results suggest that entity-level grounding is an effective inductive bias for generalizable temporal localization.
## Keyword: transformer
### Title:
          PiAnnotate: A Web Annotation Tool for Piano Fingering, with a Diagnostic Probe
 - **Authors:** Joonhyung Bae, Kirak Kim, Hyeyoon Cho, Sein Lee, Yoon-Seok Choi, Hyeon Hur, Gyubin Lee, Akira Maezawa, Jonghwa Park, Jaebum Park, Juhan Nam
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Piano fingering shapes how a passage can be played, yet it is difficult to label after a performance. An annotator must decide which finger produced each note while reconciling the score, timing, video, and hand motion. We present PiAnnotate, a web-based pipeline for adding expert fingering annotations to the FurElise performance dataset. The tool brings together a piano-roll view, performance video, and a 3D MANO hand mesh so that reviewers can inspect each assignment in musical and physical context. Rather than storing only the final answer, PiAnnotate keeps paired rule-based and human-edited fingering tracks. These paired tracks make the annotation history auditable by showing where a geometric rule was sufficient, where experts intervened, and how labels changed across review passes. As a final diagnostic, we train a small Transformer probe on the paired tracks. The probe improves on the rule baseline on held-out pieces while remaining conservative about changing labels that were already correct, suggesting that the edited labels contain learnable structure rather than only isolated fixes.
### Title:
          Machine Intelligence that Understands Visual and Linguistic Information and Interacts with Humans and Environments
 - **Authors:** Van Quang Nguyen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Advancements at the intersection of computer vision and natural language processing are crucial for applications like assistive tech, multimedia querying, and robotics. This dissertation proposes novel architectures to improve intelligent agents across three key vision-language tasks: image captioning, visual dialog, and interactive instruction following. First, we address limitations in visual representation for image captioning. Traditional models rely on region-based features from CNN detectors, which lack global context and suffer from high computational overhead. We propose GRIT (Grid and Region-based Image captioning Transformer), a transformer-only architecture. By integrating grid and region features using a DETR-based detector, GRIT enables end-to-end training and out-performs prior methods in both inference accuracy and speed. Second, we tackle visual dialog, which requires multi-turn conversation about an image. The challenge lies in efficiently modeling interactions between multiple inputs (image, question, history). We introduce LTMI (Light-weight Transformer for Many Inputs). Utilizing a specialized attention block, an LTMI layer matches the representational power of a standard Transformer extension while utilizing less than one-tenth of its parameters, as validated on the VisDial dataset. Finally, we study interactive instruction-following for embodied AI using the ALFRED dataset. We propose a framework featuring a two-stage instruction interpretation: it first decodes language directives independently of visual context to predict a tentative action-object sequence, which is then fused with visual features for final execution. Using multiple egocentric views and hierarchical attention, our method accurately localizes objects and achieves a state-of-the-art unseen success rate of 8.37%.
### Title:
          Towards Verifiable Transformers: Solver-Checkable Circuit Explanations
 - **Authors:** Neel Somani
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Logic in Computer Science (cs.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability often identifies circuits inside Transformer models, but explanations of those circuits are usually validated through examples, ablations, and manual reasoning. This leaves a gap between finding a plausible circuit and proving what the circuit does. We introduce Verifiable Transformers, a framework for converting task-localized Transformer circuits into bounded, solver-checkable claims. Given a behavior, a finite task domain, and a candidate-token projection, we extract a task circuit and verify properties such as projected functional equivalence, edge necessity, task-relevant invariance, and final-residual robustness. Direct verification encodes the extracted circuit itself into an SMT solver. When a circuit contains operators that are not exactly or tractably encodable, surrogate-mediated verification fits an SMT-encodable surrogate, validates it against the extracted circuit over the bounded domain, and verifies symbolic explanations against the surrogate. We instantiate direct verification with a GPT-style architecture using Signed L1 BandNorm, sparsemax attention, and LeakyReLU. On small symbolic sequence tasks, we train an SMT-representable Transformer, extract sparse circuits for quote closing and bracket type tracking, and exhaustively verify projected functional equivalence, content invariance, edge necessity, and final-residual robustness. At GPT-2 scale, the same operator stack trains stably on OpenWebText, although naive direct SMT verification remains intractable. We also demonstrate surrogate-mediated verification on task-localized circuits with hard-to-encode attention, showing both verified symbolic explanations and solver-generated counterexamples. The goal is not full-model verification, but a concrete path for turning mechanistic circuit explanations into formal propositions that can be proven or refuted.
### Title:
          Learning to See Like Humans: Gaze-Aligned Cycling Safety Prediction
 - **Authors:** Luís Maria Perdigão, Miguel Costa, Carlos Santiago, Manuel Marques
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cycling delivers significant public-health and environmental benefits, yet its uptake in cities is often limited by perceived safety. When street environments appear unsafe, individuals are less likely to cycle, making perception a key barrier to adoption. Recent work has shown that pairwise comparisons of street-view images provide a scalable way to learn subjective safety judgments. However, existing approaches do not explicitly model human visual attention, which plays a central role in how humans perceive safety. We propose an Eye-Tracking-Guided Perceived Cycling Safety framework (EG-PCS) that integrates gaze data into a pairwise learning pipeline based on vision transformers. By supervising the model's attention mechanism with eye-tracking signals, we encourage alignment between learned attention maps and human fixation patterns. Experiments show that gaze-guided models achieve similar ranking performance compared to state-of-the-art approaches while producing attention maps that more accurately reflect human visual attention behavior. Our results demonstrate that incorporating eye-tracking information enhances both predictive accuracy and interpretability in perception-based urban analytics.
### Title:
          Hidden-State Privacy Has an Empty Middle
 - **Authors:** Alexander Okezue Bell
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Of $1{,}536$ Gaussian release covariances we tested for single-layer hidden-state privacy, zero achieve both moderate utility and moderate privacy against an adaptive retrieval attacker. We prove a complementary Fisher-ball lower bound: every full-rank Gaussian release at $O(1)$ Fisher utility admits a direction whose Mahalanobis signal grows linearly in hidden width, ruling out uniform Gaussian safety in the class and matching the empirical empty middle. The diagonal inverse-Fisher release $\Sigma^\star_{\mathrm{diag}}(\mathcal{K}) = (2\mathcal{K}/d)\,\mathrm{diag}(1/F_{ii})$ is the unique minimax-optimal diagonal mechanism at first-order KL budget $\mathcal{K}$ and the only release with worst-attacker top-1 $\le 0.001$ at every point of a 32 model-layer grid, but it sits on a privacy/utility edge rather than filling the middle. A generalized-eigen mechanism reaching $13\times$ Pareto reduction under Euclidean retrieval collapses to $100\%$ top-1 under the adaptive Mahalanobis attacker, and a full-trajectory sequence inverter recovers $94\%$ of clean GPT-2 prefixes but $0\%$ under $\Sigma_{\mathrm{diag}}$. A split-memory transformer trained from scratch reaches $G_{\mathrm{Mah}} \in [20, 33]$ at 90M and maintains a $6$--$24\times$ advantage over same-budget GPT baselines from 30M to 1B at a fixed-token language-modeling loss penalty; pretrained models top out at 9.3. These results reframe hidden-state release from mechanism-design within the Gaussian class to architecture or release co-design.
### Title:
          Spectral Probe-Circuits: A Three-Step Recipe for Identifying Attention-Head Circuits in Pretrained Transformers
 - **Authors:** Yongzhong Xu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a three-step recipe for identifying attention-head circuits in pretrained transformers. A per-head spectral signal -- the time-integrated participation ratio of each head's attention output -- ranks heads doing sustained content-dependent computation without labels or attribution gradients. A task-pattern screen filters this general indicator into a task-specific candidate circuit, and group ablation against a matched-random control completes the causal claim. We validate across an 8x parameter range (51M to 1B-active / 7B-total), two architecture families (dense, mixture-of-experts), and four pretraining pipelines. The recipe ports: a 2-6 head induction circuit is causally necessary in every model tested, with a 94-100% drop in synthetic-induction top-1 after ablation. The spectral signal is predictive without supervision: on six independent seeds of a 51M-parameter probe model, the same computation identifies the seed-specific circuit on each seed. The fraction of heads doing identifiable specialized computation is conserved at 17-19% across the Pythia family (124M to 410M), while specific induction circuits stay 3-11 heads -- sublinear in total head count. This paper is the methodology anchor of a three-paper program; companion papers extend the recipe to developmental trajectories during pretraining and to composed-task circuits where pattern selectivity decouples from task-causal structure.
### Title:
          fMRI-Diffusion: Generating fMRI Time Series Via a Temporal Transformer Diffusion Model for Major Depressive Disorder Diagnosis
 - **Authors:** Muhammad Asif Hasan, Yanming Zhu, Xuefei Yin, Alan Wee-Chung Liew
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diagnosing Major Depressive Disorder (MDD) from functional magnetic resonance imaging (fMRI) using functional connectivity (FC) analysis requires large amounts of labeled data that are scarce in clinical settings. Existing augmentation methods synthesize FC matrices, which compress fMRI recordings into static pairwise summaries and discard temporal information. We propose fMRI-Diffusion, a framework that synthesizes region-of-interest (ROI)-level fMRI time series rather than FC matrices. A Temporal Transformer serves as the denoising network within a denoising diffusion probabilistic model, treating each time point as a token to capture temporal dependencies through self-attention. A supervised pretraining strategy initializes the Transformer with task-relevant representations before diffusion training, and FC matrices are derived from the synthesized time series for classification. Experiments on the REST-meta-MDD dataset show that augmenting training data with synthetic time series consistently improves diagnostic accuracy across ten classifiers, six parcellation atlases, and three acquisition sites. The method outperforms five recent FC-based synthesis approaches, with accuracy gains of up to 3.7 percentage points over the strongest baseline. Ablation studies confirm the contributions of both the Transformer-based denoiser and the pretraining strategy. Distributional fidelity metrics remain below 0.06 across all conditions, indicating close agreement between real and synthetic distributions. These findings suggest that synthesizing fMRI time series before FC computation preserves temporal information lost in matrix-level augmentation and provides a practical strategy for MDD diagnosis under limited data.
### Title:
          Incorporating Deep Learning Design in Database Queries
 - **Authors:** Yuval Lev Lubarsky, Dean Light, Boaz Berger, Shunit Agmon, Benny Kimelfeld
 - **Subjects:** Subjects:
Databases (cs.DB); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning over relational databases is conventionally realized by translating data into graph representations and applying graph-based neural networks within external frameworks. This round-trip between the database and external machine learning (ML) systems introduces non-trivial engineering overhead. In effect, these graph neural networks operate on tuple embeddings and manipulate them in ways that capture the interactions induced by relational joins. Given this natural correspondence, there is no fundamental reason why specifying a neural network over relational data should be substantially harder than querying it. We propose an approach that naturally integrates deep learning with database queries. The key idea is to associate each tuple with provenance, represented as a vector embedding with learnable parameters. Queries are lifted to operate jointly on data and embeddings, mapping input relations with embedded tuples to output relations with embedded tuples. This approach provides a declarative foundation for relational deep learning, facilitating integration with database systems, optimization, and wide adoption. We describe RelaNN, a proof-of-concept implementation of this approach built on top of PyTorch and cuDF. We illustrate the utility of RelaNN by implementing various graph-learning models, including graph convolutional networks, heterogeneous graph transformers, hypergraph neural networks and deep homomorphism networks. The simplicity of the programs and their competitive runtime performance demonstrate a concrete path toward making the implementation of state-of-the-art neural networks over databases as simple as writing a query.
### Title:
          Characterizing the Representational Capacity of Neural Processes
 - **Authors:** Robin Young
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 What functions can Neural Processes represent? We analyze the representational capacity of popular NP architectures: Conditional Neural Processes (CNPs), Attentive Neural Processes (ANPs), Transformer Neural Processes (TNPs), and their latent variants. We prove these architectures form a strict hierarchy. CNP-representable functions are exactly those depending on finitely many expected features of the context distribution. ANPs strictly generalize CNPs via query-dependent reweighting, enabling kernel smoothers. ConvCNPs and ANPs are incomparable; each contains functions outside the other, separated by stationarity versus translation equivariance. TNPs with $L$ self-attention layers capture $L$-hop context interactions. For latent NPs, we show finite-dimensional latents provide coherent sampling but do not circumvent encoder limitations; matching GP posterior distributions requires latent dimension scaling with context size. These results provide a theoretical foundation for architecture selection based on task structure.
### Title:
          GIBLy: Improving 3D Semantic Segmentation through an Architecture-Agnostic Lightweight Geometric Inductive Bias Layer
 - **Authors:** Diogo Lavado, Alessandra Micheletti, Clàudia Soares
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In 3D scene understanding, deep learning models rely on large models and extensive training to capture basic geometric structures that are present in the 3D data. However, existing methods lack explicit mechanisms to incorporate geometric information, such as learnable primitive shapes, often necessitating large models and more training data which in turn increases cost and can limit generalization. We introduce GIBLy, a lightweight geometric inductive bias layer that integrates learnable geometric priors into 3D segmentation pipelines. GIBLy enhances existing architectures -- whether MLP-based, convolution-based, or transformer-based -- by providing features aligned with simple geometric shapes (and thus human-interpretable) that improve segmentation performance with minimal computational overhead. We validate our approach across multiple 3D semantic segmentation benchmarks, demonstrating consistent performance gains, including up to +11.5% mIoU on TS40K with PTV3, while adding only 58K extra parameters. Our results highlight the benefit of explicitly encoding geometric structure to support accurate and efficient 3D scene understanding, with a lightweight add-on layer
### Title:
          Causal Physics Steering in Video World Models via Concept Activation Vectors
 - **Authors:** Nahid Alam
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video world models learn representations of physical dynamics, but controlling their physical expectations at inference time remains an open problem. Recent interpretability work identified a Physics Emergence Zone (PEZ), a group of middle transformer layers in VideoMAE where physical plausibility is represented separately from other visual features. However, it remained unclear whether this structure could be used to directly control the model's physics reasoning. We present physics steering, a training-free method that uses the weight vector of a linear probe at a PEZ layer as a Concept Activation Vector (CAV) and injects it into hidden states during inference. This shifts the model's physical expectations without changing any model weights. On the IntPhys benchmark, this intervention reliably shifts the model's plausibility judgment in either direction, depending on the steering sign. The effect appears only when the intervention is applied within the Physics Emergence Zone, suggesting that the relevant physics representation is localized there. We further find that physics is encoded separately from motion direction, and that different intuitive physics principles occupy distinct directions within this representation space. Together, these results show that physical reasoning in VideoMAE is not only readable, but also directly steerable.
### Title:
          Interdomain Attention: Beyond Token-Level Key-Value Memory
 - **Authors:** Naoki Kiyohara, Harrison Bo Hua Zhu, Riccardo El Hassanin, Zhuo Sun, Wenlong Chen, Samir Bhatt, Yingzhen Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers and deep state space models (SSMs) sit at opposite ends of a basic design choice: attention routes each query through a growing key-value (KV) cache by content-based matching at quadratic cost, while deep SSMs compress context into a fixed-size recurrent state that is not directly addressed by query-key matching. We propose Interdomain Attention, which integrates an SSM into an attention module through kernel methods: an attention kernel is approximated by a finite feature map, the resulting key features and values are projected onto a shared set of basis functions maintained by a single SSM recurrence, and each query attends to the compressed coefficients through its own feature map, recovering query-conditioned attention over a fixed-size state. The scalable layer is a learned relaxation of this derivation, and we validate its components through ablations. In a 125M to 1.3B autoregressive language-modeling study on FineWeb-Edu at matched recurrent-state budget, Interdomain Attention improves on an SSM token mixer at every scale, surpasses a same-recipe softmax baseline at 1.3B on validation perplexity and on the eight-task commonsense suite, and inherits the length-flat behavior of its fixed-state core out to 3.5x the training context. Ablations indicate that the query-conditioned projection is the main source of the gain.
### Title:
          ViViD-5K: Vineyard vision dataset for field-based berry detection and segmentation and grape cluster closure estimation
 - **Authors:** Xiangzhi Tong, Chengrui Zhang, Mac Flaherty, Andre Matteo Garcia, Dominic Gorman, Jonathan Jaramillo, Justine E. Vanden Heuvel, Yu Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Other Quantitative Biology (q-bio.OT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cluster closure, defined as the progressive filling of gaps between the berries in a grape bunch, is a key trait in vineyard management, impacting disease risk. However, traditional visual scoring methods are labor-intensive, subjective, and lack temporal resolution. Existing datasets rarely support fine-grained berry-level analysis, limiting the development of robust deep learning models. In this work, we present ViViD-5k, a large-scale in-field Vineyard Vision Dataset containing 5,000 images with dense annotations, including over 648,000 berry centroids and cluster segmentation masks spanning 13 grape varieties. Building on this dataset, we introduce GrapeSAM, a two-stage visual pipeline that combines point-based berry localization with prompt-based segmentation using Segment Anything, followed by transformer-based cluster segmentation. The pipeline enables automated, in-field estimation of cluster closure with minimal supervision. Quantitative results demonstrate strong segmentation and counting accuracy across diverse conditions, while visualizations confirm robustness on both in-domain and out-of-domain samples. This work provides a scalable and objective alternative to manual compactness scoring and supports high-throughput grape phenotyping with enhanced spatial detail.
### Title:
          SinFormer: A Tailored Transformer for Robust Radio Frequency Fingerprint Identification
 - **Authors:** Liu Yang, Qiang Li, Xiaoyang Ren
 - **Subjects:** Subjects:
Information Theory (cs.IT); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 With the rapid proliferation of wireless and Internet of Things (IoT) devices, ensuring secure and reliable device identification has become a significant challenge. Traditional security techniques, such as IP or MAC address-based authentication, are susceptible to spoofing, whereas Radio Frequency Fingerprint Identification (RFFI) offers a more secure alternative by exploiting the unique hardware imperfections in devices' RF signals. In this paper, we propose a novel deep learning-based framework for RFFI that enhances both accuracy and reliability in challenging RF environments. The core of our approach is the Signal Inception Transformer (SinFormer), which leverages a specialized multi-scale self-attention mechanism to effectively capture both large-scale and fine-grained fingerprints in signals, significantly improving identification accuracy. To further enhance robustness and reliability, we introduce a two-stage training strategy that enables the model to learn general signal features and maintain performance under adverse conditions, such as low Signal-to-Noise Ratio (SNR) or channel variations. The effectiveness of the proposed method is validated using a real-world dataset. Experimental results show that the SinFormer framework consistently outperforms existing methods in accuracy and robustness across diverse and challenging scenarios.
### Title:
          Benchmarking the Limits of In-Context Reinforcement Learning for Ad-Hoc Teamwork
 - **Authors:** Yuheng Jing, Kai Li, Ziwen Zhang, Jiajun Zhang, Zeyao Ma, Jiaxi Yang, Lei Zhang, Zhe Wu, Jinmin He, Junliang Xing, Jian Cheng
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-Context Reinforcement Learning (ICRL) has enabled foundation agents to adapt instantaneously to novel tasks, yet its efficacy in Ad-Hoc Teamwork (AHT)-where coordination with unknown partners is required-remains unexplored. To rigorously evaluate this, we introduce a large-scale benchmark ICRL4AHT, built upon a high-throughput JAX implementation of Overcooked-V2. Our benchmark includes a large, diverse teammate suite spanning both RL and heuristic policies, enabling controlled train-test shifts, and provides a reproducible end-to-end pipeline for teammate generation, learning-history collection, dataset construction, and online multi-episode evaluation. We evaluate representative history-conditioned ICRL algorithms, including Algorithm Distillation (AD) and Decision-Pretrained Transformer (DPT), across millions of transitions. Results reveal notable limitations: contrary to their success in single-agent domains, these baselines fail to exhibit robust test-time adaptation in multi-agent settings. Specifically, these methods frequently underperform random baselines across both unseen teammate and unseen layout tracks, with no clear in-context improvement over long horizons. These findings highlight the challenges of strategic inference under partial observability within the OvercookedV2 AHT protocol, establishing our benchmark as a critical testbed for next-generation coordination algorithms.
### Title:
          Momentum Streams for Optimizer-Inspired Transformers
 - **Authors:** Jingchu Gai, Nai-Chieh Huang, Jiayun Wu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The residual update of a pre-norm Transformer layer admits an interpretation as one step of a first-order optimizer acting on a surrogate token energy, wherein the attention and MLP sublayers function as gradient oracles. Based on this observation, we build a family of optimizer-inspired Transformers (triple-momentum, Adam/AdamW, Muon, SOAP) and compare them under matched compute. In our main pretraining experiment, the triple-momentum TMMFormer achieves the lowest validation loss, outperforming the vanilla Transformer and prior architectural variants. A controlled ablation and supporting theory show that momentum, not preconditioning, is the main source of the gain. We further show that TMMFormer and other momentum-based designs reach flatter minima than the vanilla Transformer, which leads to less forgetting and better generalization.
### Title:
          CAffNet: Hard Constraint-Affine Neural Networks
 - **Authors:** Yang Zhao, Jungeun Lee, Jeong hwan Jeon, Sze Zheng Yong
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a novel framework for embedding hard constraint satisfaction into neural network (NN) architectures, specifically feedforward neural networks and transformers, with input-dependent affine constraints of arbitrary cardinality. Traditional constraint enforcement approaches either rely on penalty-based soft constraints, which offer no guarantee of satisfaction, or on post-processing methods that enforce constraints after the NN is trained, which may lead to suboptimality. We introduce a trainable constraint-affine (CAffine) layer into NNs, yielding CAffNet, which goes beyond enforcing affine constraints via fixed orthogonal or parallel projections and enables joint optimization with network parameters. Moreover, we impose no restrictions on the constraint space dimensions and establish that our construction preserves the universal approximation properties of NNs, while providing provable guarantees on constraint adherence for all inputs. Experimental validation demonstrates robust performance across diverse domains requiring guaranteed constraint satisfaction.
### Title:
          Temporal Concept Drift in Legal Judgment Prediction: Neural Baselines Across Three Epochs of Ukrainian Court Decisions
 - **Authors:** Volodymyr Ovcharov
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Legal NLP benchmarks evaluate models on randomly split data, implicitly assuming that legal language is stationary. We test this assumption by fine-tuning four transformer encoders -- XLM-RoBERTa (base and large) and their legal-domain variants -- on Ukrainian court decisions from three temporal epochs defined by geopolitical disruptions: pre-war (2008-2013), hybrid war (2014-2021), and full-scale invasion (2022-2026). Each model is trained on one epoch and evaluated on all three, producing a 3x3 cross-temporal generalization matrix. Four findings emerge. (1) Forward degradation is severe: models trained on pre-war data lose up to 27.2 percentage points of macro-F1 when applied to full-scale invasion era decisions. (2) The degradation is asymmetric: backward transfer (full-scale to pre-war) is substantially more robust than forward transfer, consistent with the hypothesis that legal language is additive. (3) Legal-domain pretraining (Legal-XLM-R) does not improve absolute performance but reduces forward degradation magnitude and asymmetry. (4) Chronological continual learning eliminates catastrophic forgetting for general XLM-R: pre-war knowledge is fully retained (+1.8 to +6.2 pp) while full-scale performance gains +16.5 to +19.0 pp; reverse-chronological training causes severe forgetting. Cross-jurisdictional pretraining on Swiss Judgment Prediction data improves absolute performance but does not reduce temporal degradation magnitude, confirming that temporal drift is an intrinsic property of legal language evolution. The dataset (428K decisions across three epochs) is publicly available as a LEXTREME contribution.
### Title:
          TempRet: Temporal Enhancement and Two-Stage Reranking for CVPR 2026 EPIC-KITCHENS-100 Multi-Instance Retrieval Challenge
 - **Authors:** Zixu Li, Yupeng Hu, Zhiwei Chen, Zhiheng Fu, Xiaowei Zhu, Weili Guan, Liqiang Nie
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video-text retrieval has witnessed remarkable progress driven by large-scale vision-language pretraining, yet most existing approaches inherit an implicit assumption from image-text retrieval: that visual semantics can be captured frame-by-frame. This assumption overlooks the temporal dynamics of egocentric videos. The EPIC-KITCHENS-100 Multi-Instance Retrieval (MIR) challenge further raises the bar by providing soft-label relevance matrices rather than binary labels, demanding models that can resolve graded semantic correspondences across modalities. In this report, we present our solution, termed TempRet, to the CVPR 2026 EPIC-KITCHENS-100 MIR challenge. Our approach builds upon a CLIP-based dual-encoder backbone and introduces two key components to address the temporal and cross-modal challenges. First, a temporal transformer operates exclusively on the video side, modeling inter-frame dependencies through learnable positional encodings and multi-head self-attention over frame-level CLIP features. Second, a two-stage reranking pipeline first retrieves Top-K candidates via the dual-encoder, then refines their scores using a cross-encoder equipped with an Image-Text Matching (ITM) head. The entire system is trained with Symmetric Multi-Similarity Loss to exploit the soft-label relevance matrices provided by the challenge. Our method achieves 67.97% average mAP and 82.92% average nDCG on the EK-100 MIR benchmark, demonstrating the effectiveness of temporal modeling and cross-modal refinement for egocentric video retrieval.
### Title:
          Grammatically-Guided Sparse Attention for Efficient and Interpretable Transformers
 - **Authors:** Spandan Pratyush
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The quadratic complexity of self-attention in Transformer models remains a significant bottleneck for processing long sequences and deploying large language models efficiently. For this approach, there has been significant research into Sparse Attention, and Deepseek Sparse Attention has combined various methods of creating segments of tokens to reduce the time complexity. This paper introduces a novel approach, Grammatically-Guided Sparse Attention, which constrains attention computations based on the grammatical roles of tokens. By leveraging Parts-of-Speech (POS) tags, attention masks are dynamically generated that enforce linguistically coherent connections between tokens, reducing the computational graph without sacrificing essential linguistic dependencies. Two masking strategies are proposed and evaluated: a hard mask that strictly allows only predefined grammatical interactions, and a soft mask that biases attention towards these interactions. The experiments, conducted on the SST-2 sentiment classification task using a DistilBERT-like architecture, demonstrate that Grammatically-Guided Sparse Attention maintains comparable accuracy to full attention while significantly reducing the theoretical computational overhead. Preliminary results show accuracy values of 0.8200 for hard masking and 0.8165 for soft masking, closely matching the 0.8200 of full attention, providing a path towards more efficient, interpretable, and linguistically-informed Transformer architectures.
### Title:
          Emission-Aware Reinforcement Learning for Sustainable Electric Vehicle Charging and Carbon Dioxide Reduction Under Varying Renewable Penetration
 - **Authors:** Ninglin Ou, Mohammad A. Razzaque, Iftekher Islam Shovon, Shafkat Khan Siam, Shafiuzzaman K Khadem, Krishnendu Guha, Mayeen U Khandaker, Md. Noor-A-Rahim
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid growth of Electric Vehicle (EV) adoption challenges power distribution networks through peak load spikes, voltage instability, and transformer overloads from uncoordinated charging. While Model Predictive Control (MPC) and standard Reinforcement Learning (RL) methods have addressed these issues, existing approaches rarely treat real-time carbon intensity or fluctuating renewable energy (RE) availability as primary scheduling objectives, leaving substantial decarbonisation potential unrealised. This paper proposes an emission-aware RL strategy based on the Soft Actor Critic (SAC) algorithm, with a multi-objective reward that penalises carbon emissions, curtailed on-site renewables, and unmet user demand. The agent is trained within a unified benchmarking framework on the EV2Gym platform, incorporating behind-the-meter solar and wind profiles, time-varying EirGrid carbon intensity data, and realistic workplace EV behaviour across 25 Electric Vehicle Supply Equipment (EVSE) units. Nine control strategies, including heuristics, emission-aware MPC variants, and the proposed RL agent, are compared under five renewable penetration scenarios (0%-50%) over ten independent runs each. The RL agent achieves a carbon intensity as low as 23.96 grams of carbon dioxide per kilowatt-hour under 50% wind penetration, representing up to 87% emission reduction versus the uncontrolled baseline, and outperforms the external graph-based Power Distribution Network (PDN) benchmark. Transformer overload remains below 7 kWh across scenarios, against up to 1093 kWh for the As Fast As Possible (AFAP) heuristic, and renewable self-consumption reaches 52% under combined wind and solar supply. Embedding carbon intensity forecasts into the RL state and reward aligns charging with low-emission periods while preserving grid compliance and user satisfaction.
### Title:
          Polymorphism Is Rotation: Operational Mechanistic Interpretability from a Two-Layer Transformer to Pythia-70m
 - **Authors:** Jordan F. McCann
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Independently trained transformers compute the same function in residual-stream bases that differ by a uniform random rotation on $\mathrm{SO}(d_{\mathrm{model}})$. We call this phenomenon polymorphism: same function, mutually unintelligible interior coordinates. One matrix multiplication per model pair removes it: an orthogonal Procrustes fit on a single batch of activations transfers sparse-autoencoder feature dictionaries and steering vectors between independently trained models, with no retraining. The phenomenon is invisible to the standard SAE universality metric. Decoder-column cosine similarity matches across seeds at 98%, the SAE-universality headline number, while an SAE trained on one seed reconstructs another seed's activations at negative explained variance, worse than predicting the constant mean. The decoder columns align; the encoder reads from a rotated frame. A single Procrustes rotation $R$ restores reconstruction to within 0.025 EV of the within-seed ceiling at every internal site. $R$ is Haar-distributed: $\|R - I\|_F$ matches the random-orthogonal prediction $\sqrt{2 d_{\mathrm{model}}}$ to 0.1% at $d_{\mathrm{model}} = 512$, and a Kolmogorov-Smirnov test of $R$'s eigenvalue spectrum against Haar $\mathrm{SO}(d_{\mathrm{model}})$ returns $p \approx 1.000$ pooled and per-pair. Diff-of-means steering vectors transfer in three regimes by alignment with $R$'s invariant subspace: clean when pinned by shared output weights, partial when overlapping the rotated subspace, inverted otherwise. With no shared I/O (Pythia), all three collapse to universally inverted. The same rotation account holds across training checkpoints within a single run. Validated on a 104k-parameter Dyck-3 transformer and nine independently-trained Pythia-70m seeds on The Pile, via a pre-registered four-bar operational framework. Frontier-scale (10B+) replication remains open.
### Title:
          CSP-Atlas: Concept-Specific Neural Circuits in a Sparse Python Transformer
 - **Authors:** Piotr Wilam
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A sparse 8-layer code transformer develops dedicated neural circuitry for every Python construct tested, and that circuitry is organised by a clean computational principle rather than by semantic category. We extract neural circuits for 106 concepts (43 AST node types, 63 builtin objects) by marginalising across 63,800 controlled prompts, and decompose each circuit into concept-specific and token-driven components using contrastive checker prompts that present a keyword token without its associated syntactic structure. Three findings emerge. First, all 106 concepts produce non-empty universal circuits at every one of nine parameter settings, and the ranking of concept-specificity across constructs is stable across the sweep - survival is not an artifact of a permissive threshold. Second, AST circuits contain a genuine concept component distinct from token activation: concept-only neurons constitute up to 62.5% of the loudest-firing neurons at mid-to-late layers, while builtin circuits are almost entirely token-driven. Third, six computationally atomic constructs - Import, ImportFrom, Break, Continue, Pass, Assert - cluster together despite being semantically unrelated, sharing only the property of being single-statement constructs requiring no nested body; this atomicity super-cluster, together with a four-tier hierarchy organised by token ambiguity and structural distinctiveness, shows that the model's internal organisation tracks computational structure rather than meaning. The methodology, full decomposition data, and analysis code are released.
### Title:
          Reasoning to Align: Implicit Reasoning in Diffusion Transformers for Video Editing
 - **Authors:** Yan Li, Lin Liu, Xiaopeng Zhang, Qi Tian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Instruction-based video editing requires transforming a source video according to a natural-language instruction while preserving irrelevant content and remaining temporally coherent. We argue that existing Diffusion Transformer (DiT) editors struggle with this task for two structural reasons. First, conditioning signals are fed undifferentiated into all transformer blocks, forcing a single token stream to encode both global editing intent and fine-grained visual evidence. Second, the cross-attention patterns that govern the edit are supervised only indirectly through pixel-level reconstruction, leaving the model's internal reasoning process under-constrained. To address both limitations, we propose RVEDiT, an implicit Reasoning Video Editing DiT framework built around two complementary components. The first, Granularity-Routed Token Conditioning, introduces learnable editing tokens distilled from a multimodal LLM and routes them to shallow blocks, while reserving native visual and textual tokens for deeper blocks, thereby inducing a coarse-to-fine editing process inside the backbone. The second, Reference-Anchored Attention Alignment, employs a parameter-sharing reference branch during training and maximizes the mutual information between the attention features of the editing and reference branches, regularizing the model's internal reasoning without incurring any additional inference cost. Experiments on standard instruction-based video editing benchmarks show that RVEDiT consistently outperforms state-of-the-art baselines, with particularly strong gains on localized and compositional edits.
### Title:
          Beyond the Aggregation Dilemma: Prior-Retaining Decoupled Learning for Multimodal Graphs
 - **Authors:** Hao Yan, Xuanru Wang, Jun Yin, Shirui Pan, Senzhang Wang, Chengqi Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Attributed Graph Learning (MAGL) integrates intrinsic node attributes with structural topology via graph aggregation. However, as pretrained encoders evolve into Large Foundation Models (LFMs), the landscape of MAGL fundamentally shifts: under high-confidence LFM priors, mandatory aggregation introduces topological noise that overwhelms discriminative signals, triggering a counter-intuitive performance inversion where sophisticated MAGL architectures underperform simple topology-agnostic MLPs. Through systematic empirical and theoretical analysis, we identify that this inversion stems from a fundamental aggregation dilemma characterized by two concurrent pathologies: (1) Representational Pathology (SNR Degradation) - mandatory aggregation dilutes robust intrinsic features with topological noise, causing the noise penalty to outweigh its collaborative benefit; and (2) Optimization Pathology (Gradient Starvation) - topological aggregation attenuates gradient flow, while a shared task loss causes dominant modalities to prematurely suppress weaker ones. To resolve this dilemma, we propose SUPRA (Shared-Unique Prior-Retaining Architecture), a decoupled dual-pathway paradigm. SUPRA processes modality-specific features through topology-agnostic MLPs while capturing structural synergy via a lightweight shared GNN, with auxiliary deep supervision counteracting gradient starvation. Extensive evaluations demonstrate that SUPRA achieves state-of-the-art performance while requiring 3.5x lower peak GPU memory and up to 4.4x faster training time than Multimodal Graph Transformers.
### Title:
          Motion-Compensated Weight Compression
 - **Authors:** Ismail Lamaakal
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural network weights are increasingly a bottleneck for deployment, yet most compression pipelines treat layers independently and overlook cross-layer redundancy induced by function-preserving symmetries. We propose Motion-Compensated Weight Compression (MCWC), a weight-only codec that aligns permutation-symmetric blocks (e.g., hidden units and attention heads) to maximize cross-layer correspondence, turning depth into a predictable sequence. In the aligned coordinate system, MCWC uses a lightweight layer-sequential predictor with periodic keyframes and encodes only quantized prediction residuals using a learned entropy model trained under a rate distortion objective. A simple decoder reconstructs deployable weights by entropy decoding, dequantization, predictor-driven reconstruction, and inverse alignment, enabling fast weight materialization for inference. Across Transformer language modeling and vision classification, MCWC improves the rate accuracy Pareto frontier over strong quantization and learned weight-codec baselines, while maintaining competitive decode time. Ablations confirm that alignment, prediction, entropy modeling, and keyframe scheduling are each necessary for the full gains. Our code is available via this https URL.
### Title:
          A Contractive Feedback Semantics for Reinforcement Learning
 - **Authors:** Zuyuan Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Discounted reinforcement learning is usually presented through Bellman equations on closed Markov decision processes. This paper develops a compositional view: a one-step decision process is treated as an open stochastic component, and infinite-horizon policy evaluation is obtained by closing a contractive feedback loop. The resulting semantics assigns typed Bellman transformers to open components, interprets series and parallel wiring as composition and tensoring of transformers, and interprets feedback as an admissible guarded Banach trace realized by a unique fixed point. This perspective yields three theoretical consequences. First, approximate component equivalence is a contextual congruence for admitted well-typed guarded one-hole contexts: local operator error remains controlled after plugging the component into a surrounding circuit that uses the hole once and whose feedback nodes have certified uniform guardedness. Second, exact and approximate state abstractions become commuting or near-commuting coalgebraic diagrams, giving value-preservation and explicit sup-norm distortion bounds. Third, under monotone $\omega$-continuous contract-transformer semantics, safety, risk, and resource specifications can be represented as quantale-valued contracts, where local inductive bounds lift through wiring and feedback by least-fixed-point reasoning. Its central claim is not that all RL morphisms form a global traced monoidal category, but that discounted Bellman evaluation admits a contractive feedback semantics on the admissible class of guarded circuits.
### Title:
          Muon in Vision Transformers: Optimizer-Recipe Interactions and Gradient Spectra
 - **Authors:** Ben S. Southworth, Shuai Jiang, Daniel McBride, Eric C. Cyr, Stephen Thomas
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Muon is a recently developed matrix-aware optimizer that has shown strong results in transformer training, but its behavior in vision transformers (ViTs) is not yet well understood. We study Muon for ViT training, largely on ImageNet-100 and Pl@ntNet-300K, comparing against AdamW under standard vision recipes involving mixup, cutmix, smoothing, and random augmentation and erasing. Muon consistently outperforms AdamW, with especially large gains on long-tailed Pl@ntNet macro top-1. These gains are also recipe-dependent, where Muon benefits much more than AdamW from advanced and significant data augmentation techniques. To understand this interaction, we analyze the singular-value structure of matrix gradients throughout the ViT. Within Muon training runs, removing heavy data augmentation induces a late-training spectral concentration and mode collapse in gradient matrices, primarily in deep MLP-down blocks. Under a fixed "full" augmentation recipe, the clearest Muon-AdamW contrast appears instead in QKV gradients, where AdamW gradient energy remains concentrated in a much narrower basis while Muon spreads energy across substantially more singular modes. Muon in ViTs is therefore best understood as an optimizer-recipe interaction. Under a fixed recipe, Muon differs from AdamW most clearly in attention projections, where its gradients consist of a broader spectral basis. Within Muon, a full training recipe is important for preventing late spectral concentration and mode collapse in deep feedforward blocks. We further demonstrate efficacy in training ViTs on image segmentation and masked autoencoder models, where Muon outperforms AdamW in all settings considered.
### Title:
          Self-Supervised Contrastive Learning for Cardiac MR Sequence Classification
 - **Authors:** Yuli Wang, Hyewon Jung, Dongshen Peng, Yuwei Dai, Jing Wu, Haoyue Guan, Yoko Kato, Zhicheng Jiao, Yu Sun, Ihab Kamel, Joao Lima, Cheng Ting Lin, Harrison Bai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformer (ViT) models, utilizing self-attention mechanisms, have demonstrated robust generalization capabilities across various vision tasks, including image classification. However, these models, typically pretrained on general public datasets, often lack the specialized domain knowledge necessary for medical imaging applications. In this study, we investigate the adaptation of ViT models, specifically for cardiac magnetic resonance (MR) images, using an in-house dataset. We found that pretrained ViT features do not effectively transfer to the cardiac MR domain. To overcome this limitation, we introduce an adaptation strategy that utilizes image-based self-supervised contrastive learning, demonstrating superior performance compared to traditional supervised training approaches. Moreover, our adapted ViT model exhibits strong generalization to external MR datasets such as BraTS and ADNI. Through ablation studies, we further investigate the impact of batch size and dataset scale on performance. Ultimately, our adapted model achieves classification AUC exceeding 0.75 across the four most common cardiac MR sequences.
### Title:
          AOEPT: Breaking the Implicit Modality-Reduction Bottleneck in Modality-Missing Prompt Tuning
 - **Authors:** Jian Lang, Rongpei Hong, Ting Zhong, Fan Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying multimodal systems in real-world environments often entails handling modality-missing scenarios, where one or more modalities are unavailable. While recent studies address this challenge for the general Multimodal Transformer (MT) architecture via prompt tuning, we identify a fundamental limitation in these methods: the Implicit Modality-Reduction bottleneck. By conditioning prompts solely on the observed modalities, they inadvertently restrict the reasoning scope of MTs to the modality-reduced subspace, cutting off access to the latent information sources of the missing modalities. To overcome this limitation, we propose AOEPT, which pioneers a novel modal-contextualized prompting fashion. Specifically, we introduce lightweight Modal-Contextualized Prompts (MCPs) that distill global modality-wise priors from training data, serving as latent repositories of the information sources for missing modalities. Conditioned on the remaining modalities, these MCPs are instantiated into instance-aware prompts that selectively augment missing-modality information for each sample, thereby restoring the reasoning scope of MTs beyond the observed-modality-only subspace. Experiments across various multimodal benchmarks and backbones confirm the strong performance of AOEPT, with minimal computational overhead.
### Title:
          Translators as Invisible Teachers of AI: Copyright, Translation Memory, and the Political Economy of Linguistic Data
 - **Authors:** Masaru Yamada
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper examines how the labour of translators has been transformed into foundational data capital for the age of artificial intelligence (AI). Translation memories (TM) and parallel corpora preserve a one-to-one correspondence between source and target text and therefore constitute extraordinarily valuable supervised training data for machine translation. The development of statistical machine translation (SMT), neural machine translation (NMT), the Transformer architecture, and multilingual large language models (LLMs) cannot be disentangled from the accumulation of such translation data. And yet, translators' renditions have been bought as deliverables under contract, segmented as technical objects, and processed as "information analysis" data under copyright law -- losing their moral, creative, and economic attribution to the translators who produced them. The paper develops two concepts to capture this process. The first is appropriation without consumption: a mode of use in which works are not read, viewed, or listened to, but only mined for statistical features -- a use that is legitimated under Article 30-4 of the Japanese Copyright Act. The second is the invisible teacherisation of translators: the process by which translators, through the construction of translation memories, post-editing, and quality assessment, have functioned as teachers of AI without recognition as such. Drawing on the data supply chain that runs from translators through language service providers (LSPs) and platforms to model developers, on a comparative reading of Japanese, European, and United States legal frameworks, on the distinction between open and proprietary AI models, and on the premium status that human-generated data has acquired in the era of model collapse, the paper asks what translators are actually afraid of, and points toward concrete directions for redistributive design.
### Title:
          Tiny Brains, Giant Impact: Uncovering the Keystone Neurons of LLM with Just a Few Prompts
 - **Authors:** Xiangtian Ji, Yuxin Chen, Zhengzhou Cai, Xiang Wang, An Zhang, Tat-Seng Chua
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) display strong comprehensive abilities, yet the internal mechanisms that support these behaviors remain insufficiently understood. In this work, we show that across a wide range of open-weight Transformers, a subset of neurons remains consistently highly activated during inference across tasks of multiple capability dimensions. By probing along the cross-task activation strength, an extremely sparse subset is isolated, whose removal causes a collapse in model behavior, which we term keystone neurons. Our analysis reveals that keystone neurons are a stable and intrinsic neuron subset of the model that is largely established during pretraining. The parameters associated with these neurons are tightly calibrated during the training process, and their precise values are critical for the capabilities of the model. Building on these insights, we propose a supervised fine-tuning approach that updates only keystone neurons, achieving task gains comparable to or even better than full-parameter fine-tuning while better preserving performance in other capability dimensions, despite modifying a much smaller number of parameters.
### Title:
          The Concept Allocation Zone: Tracking How Concepts Form Across Transformer Depth
 - **Authors:** James Henry
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Concept formation in transformer language models is depth-extended, not a single-layer event: concepts emerge gradually across a contiguous region of the residual stream. Mechanistic interpretability methods identify the single layer of peak class separation -- the "best layer" -- capturing a snapshot rather than the process itself. We introduce the Concept Allocation Zone (CAZ): the depth interval within which a concept becomes measurably separable, the region allocated to its geometric expression. We formalize the CAZ through three layer-wise metrics (Separation, Concept Coherence, Concept Velocity) and derive principled boundary detection without manual layer sweeps. A CAZ is not a concept: it is the depth region within which the model organizes its geometry to make a concept separable. A single concept typically participates in multiple CAZes; multiple concepts may share one. Empirical validation across 34 models from 8 architectural families and 7 concepts reveals that the separation curve S(l) is frequently multimodal. A scored detector uncovers "gentle CAZes" -- subtle allocation regions invisible to standard peak detection but causally active in 93-100% of cases under ablation (16 of 34 models; 26 in the companion validation paper). The framework generates seven testable predictions; four yield clear verdicts (two not supported, one partially supported, one supported), one had its precondition invalidated by the data, and two are underpowered -- with cross-architecture alignment confirmed as depth-matched rather than monolithic under leave-one-concept-out cross-validation. Reference implementation: rosetta_tools v1.3.1 (doi:https://doi.org/10.5281/zenodo.20361433).
### Title:
          Clustering as Reasoning: A $k$-Means Interpretation of Chain-of-Thought Graph Learning
 - **Authors:** Xuanting Xie, Zhaochen Guo, Bingheng Li, Xingtong Yu, Zhifei Liao, Zhao Kang, Yuan Fang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chain-of-Thought (CoT) prompting has shown promise in enhancing the reasoning capabilities of large language models (LLMs) on text-attributed graphs (TAGs). This work reframes CoT-based graph learning through the principle of clustering as reasoning, offering a $k$-means interpretation of how iterative reasoning operates over graph-structured data. We observe that existing graph CoT methods rely on disjoint architectures and fixed graph representations, limiting step-by-step semantic-topological interaction and interpretability. To overcome this limitation, we propose a unified framework named KCoT that integrates CoT reasoning with graph representation learning. Our key theoretical result reveals a formal mathematical correspondence between a Transformer block and the $k$-means algorithm, allowing reasoning to be interpreted as iterative assignment and update steps. Based on this insight, we introduce a Semantic Discriminating Prompt that explicitly formulates these steps as structured CoT reasoning, together with a structure-grounded alignment strategy to fuse topological priors with evolving thought-conditioned representations. Experiments on standard benchmarks demonstrate consistent improvements over state-of-the-art methods, validating clustering as a principled mechanism for CoT-based graph learning.
### Title:
          Lngram: N-gram Conditional Memory in Latent Space
 - **Authors:** Yunao Zheng, Guoyang Xia, Xiaojie Wang, Lei Ren
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequence modeling requires both compositional reasoning and local static knowledge retrieval, yet standard Transformers handle both through dense computation. Engram partially decouples retrieval from the backbone, but its token-based keys remain tied to text tokenization and hash compression. We propose Lngram, a latent-space conditional memory module that learns discrete symbols directly from hidden states and performs N-gram lookup over these symbols. This design removes the dependence on tokenizer IDs and naturally extends to non-text modalities. In our evaluated settings, Lngram outperforms Transformer and Engram baselines, consistently reduces perplexity in long-context language modeling, and effectively injects domain knowledge when added post hoc to pretrained models. Joint training with the backbone further surpasses full fine-tuning, while experiments on vision-language and vision-language-action tasks show overall gains. Analyses with LogitLens and CKA suggest that Lngram enables prediction-relevant information to emerge earlier, increasing effective depth with limited inference and memory overhead. Code is available at this https URL.
### Title:
          Trajectory-Consistent Calibration for Cache-Accelerated Diffusion Models
 - **Authors:** Mingyu Liang, Dingkun Xu, Jingwei Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers require repeated denoiser evaluations during iterative sampling, making inference computationally expensive. Cache-based acceleration reduces this cost by reusing intermediate representations across denoising steps, but can introduce representation deviations and degrade generation quality. In this paper, we analyze these deviations and show that effective calibration should consider both the direct mismatch caused by reuse and the subsequent trajectory shift induced by earlier corrections. To address this challenge, we propose Trajectory-Consistent Calibration (TCC), a training-free method that calibrates cached representations toward their full-computation counterparts. Specifically, rather than estimating all calibration priors from a single uncorrected cache trajectory, TCC uses an offline iterative procedure so that each prior accounts for the trajectory shift induced by preceding calibrations. Experiments on PixArt-alpha and DiT-XL/2 show that TCC consistently improves FID across representative cache-based acceleration methods while preserving their underlying reuse policies. Notably, in a representative PixArt-alpha cache-acceleration setting based on FORA, TCC reduces FID from 29.83 to 27.35, slightly surpassing the full-computation baseline.
### Title:
          DTO: a Differentiable Training Objective for Effective Counterfactual Story Rewriting
 - **Authors:** Amelia Girard, Massimo Piccardi
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Counterfactual story rewriting is a natural language processing task that requires updating an existing story to reflect a chosen alternative event, yet preserving all the unaffected storyline elements and overall coherence. While large language models have recently made remarkable progress on this task, it still remains challenging since the required modifications are typically very small in size and highly localized. As a consequence, models trained in a conventional manner with the maximum-likelihood training objective tend to overlook these nuances. At the same time, more sophisticated training approaches based on reinforcement learning are notoriously slow and difficult to set up. For these reasons, our paper proposes a novel, differentiable training objective (DTO) that directly optimizes for the requisite counterfactual improvements. In our approach, a transformer model is fine-tuned via end-to-end backpropagation against a fully differentiable loss function that jointly rewards (i) fidelity to the reference rewrite and (ii) semantic consistency with the source narrative. The empirical evaluation on the TimeTravel and ART datasets shows that the proposed DTO approach has been able to surpass a maximum-likelihood baseline and a preference-based approach, and perform competitively against two contemporary large language models in all evaluation metrics. These findings substantiate the effectiveness of task-specific differentiable objectives for nuanced, controlled text-generation tasks.
### Title:
          Snapshot Polarimetric Display Inverse Rendering
 - **Authors:** Seokjun Choi, Yunseong Moon, Kaizhang Kang, Hoon-Gyu Chung, Jin-Nyeong Kim, Giljoo Nam, Seung-Hwan Baek
 - **Subjects:** Subjects:
Graphics (cs.GR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inverse rendering remains a core challenge in graphics and vision, especially in the snapshot configurations required for lightweight desktop workflows, where the per-frame information budget is highly constrained. Previous inverse rendering work explores various available dimensions for enriching the per-shot information, including temporal modulation, spectral encoding, and polarization. In this work, we introduce polarimetric display inverse rendering, using an LCD to project a linearly polarized RGB binary pattern and an RGB polarization camera augmented with a quarter-wave plate to acquire spectro-polarimetric measurements in a single shot. A feed-forward transformer maps these measurements to per-pixel normal, albedo, roughness, and metallicity. To overcome training data scarcity, we expand a limited set of measured polarimetric bidirectional reflectance distribution functions via a generative manifold. Evaluations on a real desktop setup demonstrate accurate inverse rendering across diverse scenes, outperforming existing approaches.
### Title:
          BandVQ: Band-Wise Vector-Quantized EEG Foundation Model
 - **Authors:** Jamiyan Sukhbaatar, Satoshi Imamura, Toshihisa Tanaka
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A central challenge in electroencephalography (EEG) foundation modeling is learning transferable representations across recordings with diverse tasks, montages, references, and spectral characteristics. Existing masked modeling approaches often rely on broadband continuous patches or a single discrete representation, which may underrepresent frequency-specific activity. This paper proposes BandVQ, a band-wise vector-quantized EEG foundation model that decomposes EEG into delta, theta, alpha, beta, and gamma bands, trains an independent VQ-VAE tokenizer for each band, and pretrains a shared Transformer encoder on the resulting discrete VQ code indices. The encoder uses masked code tokens, quantized absolute log-power tokens, channel and temporal embeddings, and metadata prefix tokens representing reference, band, task family, and phase. Region-based masking is also introduced to reduce the trivial reconstruction of spatially adjacent electrodes. The model is pretrained on 71 public EEG corpora comprising over 9,200 subjects and 357,000 single-channel hours and evaluated on six subject-independent classification datasets. Under the current evaluation setting, the proposed model achieves strong transfer performance, with the highest reported results on three cognitive tasks and competitive performance on three motor imagery tasks.
### Title:
          MambaDSF: Multi-Scale SSM with Dilated Feature Fusion for Sonar Small Target Detection
 - **Authors:** Hui Lin, Jiayi Li, Jing Wang, Shenghui Rong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sonar imaging is the primary modality for underwater target detection, yet small targets remain difficult to detect due to insufficient pixel coverage, low acoustic contrast, and scale ambiguity across imaging ranges. CNN-based detectors extract local features efficiently but cannot suppress noise-induced false alarms without global acoustic context. Transformer-based methods capture long-range dependencies at quadratic computational cost. Existing Mamba-based vision models offer efficient linear-cost scanning but lack multi-scale semantic alignment across pyramid levels, multi-receptive-field fusion, and small-target-aware training supervision needed for reliable sonar detection. This letter proposes Mamba Dilated-Scale Fusion (MambaDSF), a hybrid framework addressing these limitations through three contributions: a Mamba Enhanced Feature Pyramid (MambaEFP) backbone that jointly captures local echo cues and global acoustic context at linear complexity; a Dilate Fusion Mamba (DFMamba) encoder that enforces multi-scale feature alignment across pyramid levels; and Scale-Adaptive Weighted IoU (SA-WIoU) and Cross-Scale Coherence (CSC) losses that stabilize small-target training. MambaDSF achieves 91.5% mAP50 on the UATD forward-looking sonar benchmark with 28.7 million parameters, surpassing all compared detectors. On a small-target subset the gain reached +2.2 percentage points, and cross-domain evaluation on FLS and MD-FLS confirms the generalization of the proposed architecture. The codes are publicly available at this https URL.
### Title:
          H$^{2}$MT: Semantic Hierarchy-Aware Hierarchical Memory Transformer
 - **Authors:** Maryam Haghifam, Zifan He, Jason Cong, Yizhou Sun
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based LLMs achieve strong results on many language tasks; however, long inputs remain challenging because context windows are finite, and prefill latency and memory grow rapidly with prompt length. Flat token-stream processing and chunk-based retrieval can therefore spend substantial computation and context budget on text unrelated to the query. Offline-indexed RAG additionally introduces external storage and index management overhead, and typically appends retrieved evidence as raw text, increasing prefill cost and latency. H^{2}MT makes long-context inference structure-aware: it builds a semantic hierarchy offline, computes a memory embedding for each node via bottom-up post-order aggregation, and routes queries coarse-to-fine at inference to prune irrelevant branches early. On LongBench QA (NarrativeQA, HotpotQA, QASPER) and two structured technical-document settings, H MT achieves favorable quality efficiency trade-offs, delivering competitive ROUGE-L and F1 (where applicable) with lower peak GPU memory and time-to-first-token (TTFT) than prompt compression, memory-token methods, and retrieval-augmented generation baselines.
### Title:
          X-Edit: Exact, Explicit, and Explainable Null-Space Editing for Medical Vision Transformers
 - **Authors:** Yuanye Liu, Siyuan Zhou, Ke Zhang, Lei Li, Wei Chen, Xiahai Zhuang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pre-trained Vision Transformers (ViTs) are increasingly deployed for medical image classification. However, correcting their inevitable failure cases in dynamic clinical scenarios poses a critical challenge. Conventional fine-tuning approaches inherently suffer from catastrophic forgetting, severely degrading previously acquired diagnostic capabilities. Such instability fundamentally compromises clinical safety. Addressing this vulnerability requires an active, controllable, and reliable intervention mechanism that is both theoretically grounded and inherently interpretable. To this end, we propose X-Edit (eXact, eXplicit, and eXplainable Editing), an efficient null-space model editing framework. X-Edit transitions the editing process from iterative gradient-based optimization to a theoretically grounded, closed-form solution. Specifically, we first explicitly localize the influential layers via causal tracing governing the erroneous prediction. Subsequently, we construct an orthogonal null-space projection matrix from a curated anchor set. By geometrically constraining the exact parameter update strictly within this null space, we provide mathematical guarantees that the intervention rectifies targeted errors without perturbing established diagnostic representations. Extensive evaluations on six medical imaging benchmarks demonstrate that X-Edit comprehensively suppresses catastrophic forgetting while achieving superior edit success rates. Our code is available at this https URL.
### Title:
          TGFormer: Towards Temporal Graph Transformer with Auto-Correlation Mechanism
 - **Authors:** Hongjiang Chen, Pengfei Jiao, Ming Du, Xuan Guo, Zhidong Zhao, Di Jin, Xiao Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The growing interest in Temporal Graph Neural Networks (TGNNs) stems from their ability to model complex dynamics and deliver superior performance. However, TGNNs encounter fundamental challenges in capturing long-term dependencies and identifying periodic patterns. To address these limitations, we propose TGFormer, a novel Transformer architecture specifically designed for temporal graphs. Our model redefines temporal graph learning by establishing a trajectory framework that aligns with time series analysis principles. This approach allows TGFormer to derive node representations through systematic analysis of historical interactions, enabling granular examination of node relationships across sequential timestamps. Building upon stochastic process theory, we develop an auto-correlation mechanism that systematically uncovers periodic dependencies in node interactions. This innovation empowers TGFormer to perform dependency discovery and representation aggregation at sub-interaction levels, demonstrating superior efficiency and accuracy compared to conventional attention mechanisms. Experimental validation across six public benchmarks confirms the effectiveness of our approach, with TGFormer at most achieving 9.35\% precision improvement compared to state-of-the-art approaches.
### Title:
          Exploring Profiles of Cognitive Distortions Associated with Mental Health Disorders
 - **Authors:** Alina Anikejeva, Kairit Sirts
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cognitive distortions, distorted patterns of thinking, have been increasingly studied in computational mental health research. Although they are related to many, if not all, mental health disorders, most existing studies focus primarily on depression. In this work, we explore distortion profiles across multiple mental health conditions. We analyzed a large Reddit-based dataset containing posts from nine self-reported mental health groups as well as a control group using both an n-gram-based method and a fine-tuned transformer model for detecting cognitive distortions. Mental health groups, both when pooled together and when examined individually, showed higher prevalence of cognitive distortions compared to the control group, with the effect sizes ranging from small to moderate. When comparing distortion profiles across conditions, we observed largely similar patterns, although some groups exhibited overall higher levels of distortions than others. These findings suggest that relatively simple lexical approaches can be useful for exploratory analyses of group-level trends in large-scale mental health text data.
### Title:
          TinyFormer: Preserving Tiny Objects in YOLO-DETRHybridReal-time Detectors
 - **Authors:** Jun-Wei Hsieh, Meng-Yu Kao, Ghufron Wahyu Kurniawan, Kuan-Chuan Peng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 YOLO-series and DETR-based detectors struggle with tiny-object detection. YOLO-style models benefit from efficient dense prediction, but their large-stride backbones may suppress tiny instances in deep feature maps and make grid assignment ambiguous. DETR-based models remove hand-crafted post-processing through set prediction, yet they reason over coarse token grids, where tiny objects occupy only a few weak tokens and are easily overlooked during matching. To address these limitations, we propose TinyFormer, a unified YOLO--DETR hybrid real-time detector that combines ViT representations, NMS-free set prediction, and a YOLO-style pyramid neck for accurate small-object detection. TinyFormer introduces a Parallel Bi-fusion Module (PBM), which builds high-resolution shortcuts from shallow stages to the feature pyramid, preserving fine spatial details during multi-scale fusion. We further design a Spatial Semantic Adapter (SSA) to compensate for the spatial loss caused by coarse tokenization. SSA extracts high-resolution cues from early stages and injects them into transformer token embeddings, improving tiny-object localization without sacrificing the global modeling ability of DETR. Experiments on MS COCO show that TinyFormer consistently outperforms recent YOLO-series detectors and the strong DEIMv2 baseline. TinyFormer-X achieves 58.4% AP even without PBM, while adding PBM improves the overall AP to 58.5% and brings a 1.6% AP gain on small objects. With Objects365 pre-training, TinyFormer-X-PBM reaches 60.2% AP, surpassing RF-DETR and other Objects365-pretrained detectors with fewer parameters and lower computation. These results demonstrate that TinyFormer bridges dense YOLO-style feature fusion and DETR-style set prediction, providing a strong accuracy-efficiency trade-off for real-time tiny-object detection. Code is available at this https URL.
### Title:
          PQDT: Pseudo-Query Dual Transformer for Robust Point Cloud Restoration
 - **Authors:** Haoqing Wu, Alexa Nawotki, Jochen Garcke
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Point clouds are a fundamental 3D representation in computer vision, enabling a wide range of perception tasks. However, real-world point clouds often suffer from degradations such as incompleteness, noise, outliers, and irregular density, caused by sensor limitations or occlusions. Recovering clean and detailed shapes from such degraded data is crucial for downstream applications. While existing learning-based methods achieve progress on individual tasks like completion or denoising, they typically rely on global bottleneck features, which lose fine-grained geometry and remain sensitive to varying input quality. We propose a unified 3D restoration network that directly takes point clouds as input and adaptively reconstructs high-quality geometry under diverse degradation scenarios. At the core of our approach is a Pseudo-Query module, implemented within a Transformer backbone, which reformulates geometric translation into two cooperative stages to enhance structural clarity, robustness, and local detail preservation. Extensive experiments on curated benchmarks demonstrate that our approach surpasses state-of-the-art performance in general 3D restoration. It effectively handles complex combinations of completion, deformation, and denoising degradations. With this work, we provide a novel unified, point-only backbone for robust 3D restoration, enabling more versatile 3D perception.
### Title:
          Blocked Gibbs meets Diffusion Transformers: Unsupervised Learning for Constraint Optimization
 - **Authors:** Yudong W. Xu, Wenhao Li, Xiaoyu Wang, Scott Sanner, Elias B. Khalil
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models have shown promise in learning to solve constraint optimization problems. However, they are mostly restricted to problems with binary variables and rely on graph neural networks, hindering their application to a broader range of problems such as those with general discrete variables or constraint structures that necessitate global rather than local reasoning. We investigate the use of Diffusion Transformers to address the aforementioned limitations. A naive implementation performs poorly due to a fundamental mismatch between the standard diffusion process and constraint solving: while the former applies small, incremental denoising across all variables, the latter requires substantially altering specific subsets of variables to attain feasibility or optimality. Our method, Blocked Gibbs Diffusion Transformer (BloGDiT), is the first to address this limitation by replacing standard joint Gaussian denoising with blocked Gaussian denoising. BloGDiT uses iterative block resampling and anneals the block size over time to facilitate large, targeted edits within a block of variables. Across Sudoku, Graph Coloring, Maximum Independent Set, and MaxCut, BloGDiT matches or outperforms existing methods, demonstrating that blocked Gibbs-style diffusion provides a highly effective inductive bias for Transformer-based constraint satisfaction and optimization.
### Title:
          K-U-KAN: Koopman-Enhanced U-KAN for 3D Dental Reconstruction from a Single Panoramic X-ray Radiograph
 - **Authors:** Bikram Keshari Parida, Abhijit Sen, Wonsang You
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A panoramic X-ray compresses a 3D jaw into a 2D strip; we aim to recover the missing depth cleanly and fast. Existing implicit neural representations render realistic volumes but are slow to train, sensitive to sampling and positional encodings, and costly in practice. Pure CNN baselines are efficient yet struggle with the dental arch's long-range geometry, blur fine enamel-dentin boundaries, and offer little interpretability. We present K-U-KAN, a three-stage pipeline that (i) lifts 2D features into depth-aware observables with Kolmogorov-Arnold Networks, (ii) advances these observables by a stable, phase-aware linear evolution via a Koopman token block, and (iii) places the predicted depth bins onto focal-trough rays before a lightweight 3D attention U-KAN refines the volume. This marriage of physics (Beer-Lambert image formation), geometry (horseshoe focal trough), and learned linear dynamics yields sharp anatomy, fewer artifacts, and robust behavior on native radiographic intensities with batch size one. On held-out data, K-U-KAN matches transformer/implicit baselines on signal and structure metrics, clearly improves perceptual quality, and trains in roughly half the time-making single-view PX $\to$ CBCT reconstruction more practical for clinical pipelines.
### Title:
          Multilingual Humour-Aware Retrieval with Dense and Re-Ranking Models
 - **Authors:** Georgios Arampatzis, Avi Arampatzis
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humour-aware information retrieval poses unique challenges beyond standard semantic retrieval, as systems must account not only for topical relevance but also for humour-specific linguistic phenomena such as wordplay, phonetic ambiguity, and polysemy. In this paper, Team DUTH studies multilingual humour-aware information retrieval using the CLEF 2025 JOKER Task 1 benchmark, which evaluates humour retrieval in English and Portuguese. Our approach combines multilingual XLM-RoBERTa-based dense retrieval with additional system variants, including neural re-ranking, in order to assess the extent to which general-purpose Transformer models can capture humour-specific relevance. The results reveal substantial cross-lingual variation. While the Portuguese runs demonstrate comparatively strong performance across MAP, MRR, and early precision metrics, the English runs perform significantly worse, with relevant humorous documents frequently appearing at lower ranks. These findings highlight the limitations of purely semantic dense representations for humour retrieval, particularly when humour depends on surface-level cues that are not explicitly modelled by multilingual encoders. We further analyse contributing factors to this discrepancy, including dataset characteristics, query-document alignment, and variation in humour mechanisms. Overall, the Team DUTH experiments establish multilingual dense-retrieval and re-ranking baselines and provide insights into the challenges of modelling humour-aware relevance within the JOKER framework.
### Title:
          AME-TS: Anchored Mixture-of-Experts for Time Series Forecasting
 - **Authors:** Rui Wang, Renhao Xue, Ray Razi, Huan Song, Hannah R. Marlowe
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time series forecasting models are increasingly scaled through large Transformer backbones, yet most existing approaches process all series through a shared dense computation path despite substantial heterogeneity in temporal structure. Mixture-of-Experts (MoE) offers a natural alternative by enabling conditional computation, but standard MoE routing leaves expert specialization weakly identified and often unstable during downstream adaptation. We propose AME-TS, a structure-guided sparse time series foundation model that aligns expert routing with interpretable temporal structure. AME-TS first uses a lightweight regime predictor to estimate series-level descriptors, including forecastability, seasonality, trend, and sparsity, and maps them to a soft structural prior over experts. This series-level prior guides token-level routing during training, encouraging structure-aligned specialization. On the GIFT-Eval benchmark, AME-TS delivers a strong accuracy-efficiency tradeoff across model scales: it substantially outperforms existing time series foundation models at small model scales and remains competitive with the strongest models at larger scales, while activating substantially fewer parameters through sparse routing. We further show that AME-TS learns more interpretable routing geometry and substantially more stable expert specialization than standard MoE during fine-tuning on the M5 dataset. These results suggest that structure-aware routing is an effective and reliable way to realize the benefits of sparse expert models for time series forecasting.
### Title:
          Continuous-Depth Field Theory for Transformer Patching and Mechanistic Interpretability
 - **Authors:** David N. Olivieri, Antonio F. Pérez Rodríguez
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability often uses activation patching, causal tracing, path patching, and steering directions to reveal behaviorally meaningful directions in Transformer activation space. This paper develops a field-theoretic framework for organizing and predicting such interventions. Treating the residual stream as a depth-token field, we formulate patching as localized source insertion, patch effects as sensitivity-field predictions, downstream propagation as empirical Green-function response, and patch selection as an adjoint variational problem. Empirically, we test the forward response theory in GPT-2-style autoregressive Transformers by applying localized residual-field interventions and observing the induced residual-field differences and logit-difference responses. We identify a bounded local linear regime; predict patch effects from first-order sensitivities across residual sites; measure structured anisotropic propagation across depth and token position; construct response descriptions from high-sensitivity sites and sliced Green operators; and show that prompt-induced residual displacements can transfer answer behavior. These results establish response objects, namely sensitivities, propagated fields, and Green-operator slices, as a practical language for organizing patching experiments and as the forward mathematical basis for formulating patch-site inference and cross-scale this http URL.
### Title:
          Teaching Video Generators to Remember: Eliciting Dynamic Memory for Out-of-Sight State Evolution
 - **Authors:** Tianshuo Xu, Yichen Xie, Depu Meng, Chensheng Peng, Quentin Herau, Bo Jiang, Yihan Hu, Wei Zhan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video world models should maintain evolving states when evidence is unobserved, yet current generators often freeze hidden states upon interruption. This is not simply a capacity problem: pretrained video diffusion transformers already possess KV-cache mechanisms capable of non-local retrieval, but they are rarely trained to use them as dynamic memory. We introduce ReMind, a framework eliciting dynamic memory behavior via memory-oriented data, event-aware training, and cache adaptation. Organized around a taxonomy of 100+ dynamic events, we build a camera-annotated training mixture combining VLM-filtered real videos, generated hard dynamics, synthetic camera loops, and memory-interruption augmentations. Each clip is converted into a frame graph with protected anchors, degraded intervals, and explicit temporal gaps. A node-structured curriculum, including node-drop, noisy memory, frontier continuation, and reference-cache training, forces the model to retrieve relevant past states across interruptions rather than relying solely on local continuity. PM-RoPE, an elegant camera-phase RoPE extension, unlocks spatiotemporal retrieval at a single-attention cost while preserving pretrained pathways. ReMind achieves the best overall scores on STEVO-Bench and recovery tasks. Furthermore, general image-to-video evaluations confirm this curriculum avoids catastrophic forgetting. We will open-source our code, data, and models.
### Title:
          Toward Native Multimodal Modeling: A Roadmap
 - **Authors:** Siyu An, Junru Lu, Junnan Dong, Qiufeng Wang, Yinghui Li, Weizhi Fei, Zichao Yu, Zheng Yuan, Biao Liu, Haopeng Wang, Renzhao Liang, Yixuan Yang, Yunhang Shen, Bo Ke, Keyu Chen, Linhao Luo, Difan Zou, Xiao Huang, Di Yin, Ruizhi Qiao, Xing Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal modeling represents a vital step from modality-agnostic reasoning toward world modeling. While early approaches predominantly rely on late-fusion that assembles encoders and frozen language backbones with output heads, recent efforts have shifted the paradigm toward native multimodal modeling (NMM) with the intrinsic integration of modalities for superior multimodal performance. Despite its potential, the design space of native architectures remains insufficiently defined. In this paper, we present the community with a formalized roadmap for this transition. Specifically, we formally define the architectural nativity, distinguishing mid-fusion and early-fusion from non-native paradigms. We further organize the existing native models through the lens of input-output duality into three categories: (i) Multi-to-Text for cross-modal comprehension with text-only output; (ii) Multi-to-Target for scenario-oriented generation, e.g., image, audio and video generation, and (iii) Multi-to-Multi for unified modeling with symmetric input-output. We deliver a comprehensive and industrial-grade investigation into the transition toward the definitive NMM framework, where understanding and generation seamlessly coexist within a unified transformer paradigm. We systematically unpack the end-to-end pipeline from industrial perspectives from architectural coordination, massive data curation, to full-stack training recipes, inference & deployment, and the comprehensive evaluation for truly native modeling.
### Title:
          A general tensor-structured compression scheme for efficient large language models
 - **Authors:** Ying Lu, Peng-Fei Zhou, Qi-Xuan Fang, Pan Zhang, Shi-Ju Ran, Gang Su
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Quantum Physics (quant-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are dominated by dense linear transformations, whose storage, memory and computational overheads hinder efficient adaptation and deployment while masking the functional impacts of structural simplification. Here we present Tensor Mixture (MixT), a general tensor-structured compression scheme that replaces targeted dense linear layers with natively executable mixtures of tensor operators. Operating directly on generic linear projections instead of model-specific components, MixT is potentially applicable across Transformer-based LLMs and other dense neural mappings. We evaluate MixT on Qwen3-8B and LLaMA2-7B under a unified recovery protocol, identifying a broad compressible regime in which MMLU accuracy is largely preserved before an abrupt transition at model-specific boundaries. This transition coincides with coordinated shifts in output entropy, prediction entropy and inter-layer geometry. At the LLaMA2-7B transition boundary, MixT reduces full-model parameters by 47.5\%, inference FLOPs by 37.1\%, training FLOPs by 52.1\% and peak inference memory by 60.4\%, demonstrating its practical potential for lower-cost LLM compression.
### Title:
          Rethinking Feature Alignment in Generalist Graph Anomaly Detection: A Relational Fingerprint-based Approach
 - **Authors:** Yujing Liu, Yixin Liu, Yu Zheng, Alan Wee-Chung Liew, Xiaofeng Cao, Shirui Pan
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generalist graph anomaly detection (GAD) aims to detect anomalies on unseen graphs without graph-specific retraining. Nevertheless, existing approaches primarily focus on aligning heterogeneous features across different data domains via PCA-based projection, which harmonizes feature dimensions ignores feature semantics. As a result, GAD models fail to learn transferable semantic knowledge, and even exhibit negative transfer on unseen graphs. To address this issue, we propose a Relational Fingerprint-based generalist GAD approach (ReFi-GAD for short), aligning heterogeneous raw features with a universal and semantics-aware Relational Fingerprint (ReFi) that encodes anomaly-indicative cues from both contextual and structural perspectives. Building on ReFi, we design a fingerprint-grounded generalist GAD model, which combines a transformer-based encoder to capture domain-invariant knowledge with an SNR-guided refinement module for domain-specific adaptation. Extensive experiments on 14 datasets demonstrate that ReFi-GAD significantly outperforms state-of-the-art methods.
### Title:
          A Lightweight Hybrid Transformer-CRF Architecture for Multi-Type Bangla Medical Entity Recognition
 - **Authors:** Peyal Saha, Ahsanul Haque Hasib, Shoumik Barman Polok
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 MedER refers to the identification of medical entities. It is crucial for extracting structured clinical information from unstructured medical text. Many existing systems rely on transformer-based models, which are computationally expensive and difficult to deploy in resource-constrained environments. Furthermore, earlier works often use relaxed evaluation metrics that artificially inflate performance by rewarding correct prediction of dominant "Outside" (O) tokens. In this paper, we propose a lightweight Medical Entity Recognition (MedER) framework for the Bangla language. We establish a rigorous baseline using a 12-layer BanglaBERT model combined with a Conditional Random Field (CRF) layer for exact-boundary entity detection. To address deployment constraints, we compress this teacher model into a 4-layer student network through Knowledge Distillation (KD), where the student learns from the teacher's pre-CRF soft emission logits. Finally, we apply INT8 dynamic quantization to further reduce model size and inference cost. Our final quantized student achieves an 8.6x CPU speedup while requiring nearly 48 percent less storage than the CRF teacher model.
### Title:
          RepSAM: Bridging Foundation Models to Robotic Vision via Representation-Guided Adaptation
 - **Authors:** Wenhui Chu
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robotic perception in unstructured environments remains challenging despite the zero-shot capabilities of foundation models such as SAM. This work attributes performance degradation to non-uniform representation shifts across transformer layers: shallow layers exhibit substantial domain gaps (CKA < 0.5), whereas deep layers transfer effectively (CKA > 0.7). Based on this observation, we propose RepSAM, a representation-guided parameter-efficient fine-tuning (PEFT) framework for adapting foundation models to robotic vision. RepSAM employs a theoretically grounded CKA-guided rank allocation strategy combined with a multi-modal fusion module for robust handling of challenging robotic scenarios, including transparent objects and cluttered scenes. Experimental evaluation across six benchmarks and robotic manipulation tasks demonstrates that RepSAM achieves 97.9% of full fine-tuning performance (89.0% vs. 90.9% mIoU) while reducing trainable parameters by 158x (from 632M to 4.0M). RepSAM outperforms DoRA by 7.9% mIoU with just 4 hours of training on a single A100 GPU (a 96x reduction from full fine-tuning, which takes 384 GPU-hours). These improvements are statistically significant (p < 0.01) and translate to a 12.0% absolute improvement in robotic manipulation success rates over the LoRA (RGB) baseline.
### Title:
          A Controlled Synthetic Benchmark for Educational Aspect-Based Sentiment Analysis
 - **Authors:** Yehudit Aperstein, Alexander Apartsin
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Educational aspect-based sentiment analysis (ABSA) can support course improvement, but public aspect-labeled student feedback remains scarce because educational reviews are private, institution-specific, and expensive to annotate. This study introduces a controlled synthetic benchmark for educational ABSA built from 10,000 synthetic course reviews with explicit train-validation-test splits and a 20-aspect pedagogical schema spanning instructional quality, assessment and course management, learning demand, learning environment, and engagement. The corpus is generated with sampled target labels, sampled nuance attributes, and a realism-tuned prompt refined through a three-cycle judge-editor procedure. On the resulting benchmark, local baselines with TF-IDF, two-step transformers, and joint encoders show that the task is nontrivial; the strongest untuned model, BERT, reaches a held-out detection micro-F1 of 0.2760, while a modest lower-rate BERT schedule improves this to 0.2930. Full-test GPT-based inference with gpt-5.2 reaches 0.2519 micro-F1 in zero-shot mode and 0.2501 with retrieval-based few-shot prompting, placing batch inference above the classical baseline and close to the compact joint encoders. A conservative external evaluation on 2,829 mapped student-feedback reviews from Herath et al. yields a micro-F1 of 0.4593 for BERT on a 9-aspect overlap, indicating partial synthetic-to-real transfer. Realism and faithfulness analyses are reported as generator diagnostics that clarify how the benchmark was stabilized and where label noise remains. The study therefore contributes a synthetic educational ABSA corpus, a documented generation procedure, and a reproducible benchmark setting for a domain in which public labeled data remain difficult to obtain.
### Title:
          Is Inference Mediated by Distinct Semantic Structures in LLMs? A Mechanistic Interpretation
 - **Authors:** Nura Aljaafari, Marco Valentino, André Freitas
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting a label correctly does not necessarily require representing the operation that produces it. Transformer representations are known to carry label-level information, but whether they encode semantic operations producing those labels is unclear. We investigate this in Natural Language Inference using controlled premise-hypothesis pairs that differ by a single semantic transformation. Using layer-wise activations, we estimate operation-level subspaces via SVD and test their causal relevance through activation steering in four open-weight decoder models. Transformation effects are decodable with $84.8$-$99\%$ accuracy and occupy partially distinct but overlapping subspaces, exceeding random-subspace baselines. Steering experiments show that these directions causally influence predictions, though steerability varies across models; cross-operation steering further reveals structured interference and a dissociation between subspace selectivity and cross-operation independence. These findings indicate that the models encode not only that a hypothesis relates to a premise but also, in part, how it does so, implying that mechanistic analysis and control should operate at the level of semantic operations rather than predicted labels alone.
### Title:
          ADMFormer: An Adaptive-Decomposition Transformer with Time-Varying Masked Spatial Attention for Traffic Forecasting
 - **Authors:** Ruiwen Gu, Qitai Tan, Yahao Liu, Xiao-Ping Zhang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate traffic forecasting is essential for intelligent transportation systems, supporting a wide range of real-world applications. However, it remains challenging due to two key factors:~(1) Traffic series contain heterogeneous temporal patterns, where stable periodic regularities coexist with event-driven fluctuations. Existing methods often treat them within a unified representation, limiting their ability to capture fine-grained temporal dynamics.~(2)Spatial dependencies among nodes are inherently dynamic and sparse, while dense all-pairs attention often introduces redundant interactions and amplifies noise. To address these issues, we propose ADMFormer, an Adaptive-Decomposition Transformer with Time-Varying Masked Spatial Attention. Specifically, ADMFormer first employs a time-node adaptive gating mechanism to decouple traffic signals into dominant regularities and residual fluctuations that vary across time and nodes. A dual-branch temporal module is then designed to separately capture global periodic dependencies and high-frequency irregular variations from these two decomposed components. Furthermore, ADMFormer introduces a time-varying masked spatial attention that sparsifies spatial interactions based on real-time traffic states, thereby effectively preserving dynamic and informative dependencies. Extensive experiments on four real-world datasets demonstrate that ADMFormer achieves state-of-the-art performance.
### Title:
          DisagFusion: Asynchronous Pipeline Parallelism and Elastic Scheduling for Disaggregated Diffusion Serving
 - **Authors:** Hantian Zha, Teng Ma, Yang Yong, Haiwen Fu, Ruiyang Ma, Wei Gao, Ruihao Gong, Xianglong Liu, Wei Wang, Yunpeng Chai
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion-based generation is increasingly powering production content pipelines; however, deploying these models at scale remains a significant challenge. Model weights frequently exceed the memory capacity of commodity GPUs, while the encoder, diffusion transformer (DiT), and decoder stages exhibit highly imbalanced computational and memory footprints. A natural remedy is disaggregated serving-running stages as separate services on heterogeneous GPUs-yet this introduces new bottlenecks, including stage handoff overheads and fast-changing workloads that make cross-stage provisioning and scheduling brittle. This paper presents DisagFusion, enabling asynchronous pipeline parallelism and elastic scheduling for disaggregated diffusion serving. First, DisagFusion introduces asynchronous pipeline parallelism that overlaps computation and stage-to-stage communication to reduce pipeline bubbles and mitigate network jitter. Second, DisagFusion employs a hybrid instance scheduling strategy that combines lightweight performance prediction with runtime feedback to continuously rebalance instance ratio across stages under workload shifts. We implement DisagFusion and evaluate it with modern diffusion models. Compared to a monolithic baseline, DisagFusion improves throughput by 3.4x-20.5x and reduces end-to-end latency by 18.5x, while enabling flexible, cost-efficient deployment across heterogeneous GPUs.
### Title:
          Towards the Connection between Activation Sparsity and Flat Minima
 - **Authors:** Ze Peng, Jian Zhang, Lei Qi, Yang Gao, Yinghuan Shi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The observation that activation sparsity emerges in MLP blocks of standardly trained Transformers offers an opportunity to drastically reduce computation costs without sacrificing performance. To theoretically explain this phenomenon, existing works have shown that activation sparsity does not result from the data properties or data fitting but from the implicit bias of the training process. However, these connections are obtained with strong assumptions, which cannot be applied to deep models standardly trained with a large number of steps. Different from these works, we find that the flatness of loss landscapes is also closely related to the MLP activation sparsity and can serve as a weaker and naturally emerging assumption standard deep networks. Specifically, we find that 1) the MLP activation sparsity equals a ratio between "augmented flatness" (a weighted sum of flatness measures) and the product of the input norm and activation gradient of the MLP. We empirically find that this ratio decreases during training, leading to sparse activations. 2) We also propose the notion of derivative sparsity, which reduces to activation sparsity under ReLU, but further enables pruning in the backward propagation and is more stable than activation sparsity. With the theoretical findings, we can further encourage activation sparsity by decreasing the numerator and increasing the denominator of the ratio using three methods. These plug-and-play modifications can effectively reduce the ratio and produce sparser activations. Experiments on ImageNet-1K and C4 demonstrate relative improvements of at least 36% on inference sparsity and at least 50% on training sparsity over vanilla Transformers, indicating further potential cost reduction in both inference and training
### Title:
          Analogies between Transformer Layers and Power Method
 - **Authors:** Chenglong Li, Claudio Altafini
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In the paper we show that there is an analogy between the operations occurring in a layer of a transformer (projections and layer normalizations, disregarding the feedforward neural network) and a step in the power method. Coherently with this analogy, we show that passing through a layer the tokens tend to be tilted towards the principal eigenvector of a matrix which is the product of the output and value weight matrices of that layer. In the special case of a transformer with shared weights (i.e., in which all layers have identical weights) then the alignment with this principal eigenvector is particularly evident empirically, and can also be shown analytically. The analogy also suggests a method to steer the output of the transformer towards an arbitrary desired direction in token space.
### Title:
          Closed-Form Node Classification with Exact Graph Unlearning
 - **Authors:** Aditya Gaur, Charu Sharma
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph neural networks for node classification are typically trained by gradient descent over hundreds or thousands of epochs. Recent work has shown that, when properly tuned, classic GCN/SAGE/GAT architectures can match graph transformers on many node-classification benchmarks. We ask a complementary question: how much of this performance can be recovered by deterministic closed-form solvers, and what guarantees does this enable? We introduce a routed closed-form framework selected by adjusted homophily. For assortative graphs, we use SGC-style propagation followed by Ridge regression; for heterophilous graphs, we introduce LCF-Net, a layer-wise closed-form graph feature-refinement network whose per-layer Ridge solves are capped by a Gaussian kernel-Ridge head. Across 14 benchmarks, including ogbn-arxiv and ogbn-proteins, our closed-form predictors match or beat the best vanilla 2-layer GCN/SAGE/GAT on 9 of 9 measured datasets, tie tuned deep recipes within one standard deviation on 9 of 12 small benchmarks, and exceed the OGB-leaderboard plain GCN on both large graphs. The remaining heterophilous gap closely tracks the gain from vanilla 2-layer to deep SAGE, suggesting that the residual difference is primarily architectural. Because our predictors are explicit solutions of deterministic linear systems, modified graph inputs can be re-solved to obtain retrain-equivalent parameters. We formalize exact graph-object unlearning for label, feature, edge, node, and subgraph modifications, prove K-hop locality for Ridge components, and verify exactness across 109 configurations. On ogbn-arxiv, localized updates give $21$--$45\times$ speedups over full re-solving and roughly $10^{6}\times$ speedups over gradient retraining. Structural-inversion experiments further quantify the privacy floor of exact retraining and the additional leakage of approximate graph-unlearning methods.
### Title:
          Llamion Technical Report
 - **Authors:** Kisu Yang, Yoonna Jang, Hyeonseok Moon, Hwanseok Jang, Taewoo Lee, Hyungjin Lee, Jeseung Lee, Juhyoung Park, Heuiseok Lim
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We release Llamion, a family of 14B-parameter open-weight language models obtained by transforming Orion-14B into the standardized Llama-family architecture. The transformation is performed by Efficient Knowledge Preservation for Transformation (KEPT), a recipe that combines (i) Normal Parameter Mapping (NPM) for unchanged modules, (ii) Optimized Parameter Mapping (OPM), a training-free LayerNorm-to-RMSNorm initialization we prove optimal under the near-zero-mean activation regime induced by weight decay, and (iii) Cross-architecture Knowledge Distillation (XKD), an equal-size frozen-teacher distillation that aligns the converted model's outputs with the source model's on any reasonable input distribution. Llamion recovers Orion's behaviour on H6, MT-Bench, and KoMMLU with only ~123M tokens on a single A100 in four days; Llamion-Base reaches 66.87% on KoMMLU, exceeding the next-best entry of the Open Ko LLM Leaderboard by >7.0 absolute points at submission time. Capabilities entirely absent from the transfer corpus (Python programming and 200K-token context handling) survive the architectural transition intact. We release three checkpoints (Base, Chat, LongChat) that load with trust_remote_code=False in the Hugging Face Transformers library.
### Title:
          Profiling-Driven Adaptive Distributed Transformer Inference on Embedded Edge Deployment
 - **Authors:** Muhammad Azlan Qazi, Alexandros Iosifidis, Qi Zhang
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Distributing Transformer inference across embedded edge devices can alleviate individual memory and compute constraints, yet practical benefits on real hardware remain unclear: prior work relies largely on simulations that overlook hardware-specific communication overheads. We present a hardware prototype study on NVIDIA Jetson Orin Nano devices connected over WiFi. Our key finding is that the dominant bottleneck is not just network bandwidth but also the CPU-GPU staging during communication. Because Jetson's integrated GPU architecture lacks the PCIe/NVLink pathway that NCCL requires, all inter-device data communication should be routed through GLOO and staged in CPU memory; an overhead that scales with communication data volume and makes full-tensor exchange slower than single-device inference across the batch sizes for medium sized models such as ViT. We therefore evaluate Prism by combining Segment Means compression with lightweight offline profiling to adaptively select between local and distributed execution at runtime. Experiments show that this strategy reduces latency by 65%-77% and energy consumption by 34%-52% relative to full-tensor exchange in static distributed execution setup, demonstrating that profiling-driven adaptation is essential for practical distributed Transformer inference on embedded hardware.
### Title:
          An Efficient and Privacy-Preserving Architecture for Cross-Institutional Collaborative RAG
 - **Authors:** Chenxin Mao, Shangyu Liu, Zhenzhe Zheng, Fan Wu, Jie Wu, Guihai Chen
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Retrieval-Augmented Generation (RAG) empowers LLMs with external knowledge, making cross-institutional domain-specific knowledge base integration a highly promising deployment paradigm. Despite this potential, strict privacy regulations create severe "data silos" that obstruct such collaboration. Building federated RAG systems requires distributed inference, but the Transformer's self-attention mechanism fundamentally conflicts with this by mandating cross-node access to distributed Key-Value caches. To address this challenge, we present FedRAG, a high-throughput, privacy-preserving federated RAG framework. At its core is a novel Scrambled Distributed Attention protocol that utilizes numerically stable feature scrambling and token permutation. By dynamically delegating scrambled computations to collaborating nodes, our system successfully decouples attention execution from data localization without exposing plaintext. Crucially, our approach requires no specialized hardware or model retraining, circumventing the prohibitive latency and communication overheads of cryptographic solutions while robustly defending against intermediate state inversion attacks. Extensive evaluations demonstrate our framework preserves negligible (<0.1\%) model utility degradation and achieves up to a 62$\times$ latency reduction over existing secure baselines, sustaining practical, human-reading throughput for cross-institutional knowledge synergy.
### Title:
          SIREN: Unified Multi-Granularity Semantic Interaction for Multi-Modal Lifelong User Interest Modeling
 - **Authors:** Yaqian Zhang, Ruyi Yu, Tianyi Li, Bohan Liu, Maoquan Ye, Ke Wang, Shifeng Wen, Junwei Pan, Lijie Wang, Qi Zhou, Yeshou Cai, Chengguo Yin, Lifeng Wang, Hui Li, Lei Xiao, Haijie Gu
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Industrial recommender systems increasingly leverage lifelong user behavior histories and rich multi-modal content to capture evolving user preferences. However, effectively integrating multi-modal features into lifelong interest modeling remains challenging due to the inherent misalignment between multi-modal and collaborative spaces. Existing paradigms typically rely on separate modeling of multi-modal sequence and behavior sequence, and late fusion to alleviate the modality gap, which results in coarse-grained multi-modal representation and limited integration. In this paper, we propose SIREN, a unified multi-granularity semantic interaction framework for multi-modal lifelong user interest modeling. In the General Search Unit stage, we introduce two alternative retrieval strategies: multi-modal similarity-based soft retrieval for retrieval effectiveness, and Semantic ID (SemID)-based hard retrieval for efficient industrial serving. For the Exact Search Unit stage, we explicitly incorporate target-aware relevance via coarse similarity buckets and fine-grained prefix-encoded SemIDs, enabling unified interaction with collaborative ID features within the target-conditioned transformer architecture. Extensive experiments on the offline dataset demonstrate that SIREN achieves a state-of-the-art GAUC. Online A/B tests further demonstrate consistent GMV gains across multiple production scenarios, including +2.28% in Weixin Moments, +3.87% in Weixin Official Accounts, and +1.61% in Weixin Channels. From July 2025, SIREN has been fully launched for full-traffic serving in Tencent's advertising platform.
### Title:
          Invariant-Based Weight Sharing for Message Passing
 - **Authors:** Florian Seiffarth
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Message-passing neural networks (MPNNs) are a powerful framework for learning representations of graph-structured domains. However, weights in MPNNs act on features only, limiting their ability to capture structural patterns. We introduce a novel structure-aware weight sharing principle that explicitly incorporates information inherent to the graph structure. Weights are indexed directly by user-chosen graph invariants, i.e., functions preserved under node permutations, enabling systematic reuse across structurally equivalent subgraphs. We present ShareGNNs, which instantiate this principle within a simple encoder-decoder architecture, resulting in an MPNN with learnable adjacency and transformer-like connectivity. We show that their expressivity is at least as strong as the discriminative power of the chosen invariants, providing explicit control over the model complexity. Experiments on synthetic and real-world data, as well as subgraph counting tasks, demonstrate consistent improvements over standard MPNNs, competitive expressivity beyond the 1-WL test, and scalability to large datasets.
### Title:
          ParkourFormer: Integrating Predictive Supervision and Sequence Modeling into Parkour Locomotion
 - **Authors:** Yanheng Mai, Wenhao Xu, Zirui Huang, Yifei Fu, Shengwei Dong, Xinjue Wang, Kailun Huang, Yanzhe Xie, Renjing Xu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humanoid parkour requires locomotion policies to coordinate whole-body dynamics across rapidly changing terrains such as stairs, gaps, slopes, and obstacles. Existing reinforcement learning policies are largely reactive, mapping observations directly to actions without explicitly modeling future body states. Such modeling becomes critical in agile locomotion tasks where successful motion execution depends strongly on anticipating upcoming contact transitions and body this http URL present ParkourFormer, a Transformer-based sequence modeling framework that reformulates humanoid locomotion as a future-conditioned decision-making problem. The current robot state queries historical sensorimotor trajectories through cross-attention, while a lightweight prediction head forecasts short-horizon future proprioceptive states. The predicted future states, trained with supervised signals, are fused with temporal features to generate actions, enabling the policy to jointly reason over motion history and anticipated future dynamics. We evaluate ParkourFormer on a diverse multi-terrain humanoid parkour benchmark including stairs, gaps, slopes, rough terrain, and obstacle traversal. Experiments in simulation and on a real humanoid robot show that ParkourFormer achieves a 93.85% average traversal success rate on highly challenging terrains, with improvements of up to 42.73% over strong MLP, MoE-based MLP, and vanilla Transformer baselines, while maintaining a single unified policy across all terrain types. These results demonstrate that explicit future-state modeling significantly improves robustness and generalization for agile whole-body locomotion.
### Title:
          DiSC: Resolution-Scalable Acceleration of Diffusion Models by Exploiting Sparsity and Cached Token Reuse with Hash-based Distribution
 - **Authors:** Jieon Yoon, Hangyeol Lee, Jaehoon Heo, Joo-Young Kim
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based diffusion models offer superior scalability and performance but suffer from high computational overhead due to the iterative nature and quadratic complexity of self-attention at high resolutions. In this paper, we propose DiSC, a resolution-scalable, sparsity-aware hardware accelerator. At the software level, DiSC introduces two algorithms: Cached Token Reuse (CTR), and Softmax Thresholding with Sparsity Mask Reuse (ST). CTR introduces a mechanism that translates spatial variations in the input latent difference across steps into a token-level reuse decision, effectively eliminating redundant token computation. ST induces sparsity in attention operations by reusing a generated sparsity pattern, leveraging temporal similarity to bypass costly prediction overhead. Together, these algorithms provide resolution-scalable computational benefits and yield a moderate sparsity and hybrid dense-sparse workload. To exploit this efficiently, we design a specialized hardware architecture and unified dataflow. This architecture avoids dedicated sparsity-handling components; instead, a hash-based distribution over on-chip memory banks allows DiSC to reuse its existing compute engines for sparse operations, efficiently exploiting the induced sparsity with minimal hardware overhead. Evaluated on DiT and PixArt-Sigma, DiSC achieves 3.47-4.74x and 2.48-3.50x speedups over NVIDIA A100 and H100 GPUs, respectively, with energy savings ranging from 46.4% to 68.1%.
### Title:
          ATV-Net: Adaptive Triple-View Network with Dynamic Feature Fusion
 - **Authors:** Hsin-Jui Pan, Sheng-Wei Chan, Meng-Qian Li, Chun-Po Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent semantic segmentation research has increasingly moved toward stronger context modeling, dense attention, and transformer-based architectures. Although these models achieve impressive performance, classical CNN-based segmentation pipelines remain attractive because of their simplicity, efficiency, and ease of implementation. This paper revisits a practical question: how far can a ResNet-based segmentation model be improved by only modifying the segmentation head? We propose ATV-Net, an Adaptive Triple-View Network that strengthens a ResNet-101 backbone using three simple but complementary receptive-field views. The micro view captures point-wise semantic responses, the local view models neighborhood structures and object boundaries, and the scout view provides enlarged contextual cues. Instead of fusing these views with fixed weights, ATV-Net introduces an Adaptive Decision Gate that dynamically selects receptive-field responses according to input scene characteristics. A compact global coordination layer is further applied to improve spatial and semantic consistency. Experiments on the Cityscapes validation set show that ATV-Net achieves 80.31\% mIoU. This result suggests that classical CNN-based segmentation is still far from obsolete: with simple receptive-field views and adaptive fusion, a ResNet-based pipeline can reach a competitive accuracy level without relying on transformer-style global attention or overly complex context modules.
### Title:
          Event-to-Video Reconstruction using Spatio-Temporal and Frequency-Enhanced Deep Neural Networks
 - **Authors:** Ramna Maqsood, Paulo Nunes, Luís Ducla Soares, Caroline Conti
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event cameras offer significant advantages over conventional frame-based counterparts, including high temporal resolution, low latency, and energy efficiency. These characteristics make them suitable for high-speed and high-dynamic range scene acquisition scenarios; however, the lack of dense intensity frames limits the direct applicability of conventional computer vision methods for scene understanding. Event-to-video (E2V) reconstruction seeks to bridge this gap by converting asynchronous event streams into a sequence of synchronous video frames. Existing E2V reconstruction methods based on convolutional neural networks and transformers operate primarily in the spatial domain and often struggle to recover fine structural details while suppressing severe reconstruction artifacts. To address these issues, we propose MSFET-E2V, a novel multiscale frequency-enhanced transformer model. At its core lies a cross-domain attention module, which fuses spatio-temporal features with frequency-aware representations derived from the discrete wavelet transform. Unlike prior methods relying solely on spatial attention, our approach effectively captures both local and global structures by taking into account low- and high-frequency components, enhancing detail preservation and robustness across various motion scenarios. Furthermore, we propose a lightweight wavelet-enhanced skip block that serves as a skip connection, facilitating artifact suppression and structural detail refinement through joint spatial-frequency domain processing. Extensive experiments demonstrate that MSFET-E2V achieves superior performance over state-of-the-art methods on multiple real-world event datasets, offering significant gains in reconstruction quality. Moreover, compared to the existing transformer-based method, our proposed model significantly reduces the number of parameters, the GPU memory usage, and inference time.
### Title:
          Geometric Evolution Maps: Extracting Stable Concept Probes from Transformer Residual Streams
 - **Authors:** James Henry
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Concept probes extracted from transformer residual streams are only as reliable as the layer from which they are extracted. The common practice of probing at a fixed late layer or at the peak of a separation score function ignores a fundamental structural feature: concept representations undergo substantial directional rotation during their assembly phase, and do not settle into a stable direction until a characteristic handoff layer after the primary Concept Allocation Zone (CAZ). We introduce Geometric Evolution Maps (GEMs), which track the full directional trajectory of a concept through residual stream activations, identify the handoff layer where rotation ceases, and extract the settled probe direction from that layer. Across 23 architectures spanning 70M to 14B parameters and 17 concept types, the entry-to-exit cosine similarity within CAZs has a mean of 0.233, showing that probe direction at CAZ entry does not reliably predict probe direction at exit. Ablation experiments across 391 concept x model pairs (23 models x 17 concepts) show that GEM-extracted probes are at least as precise as peak-layer probes in 268/391 trials (68.5%), and strictly outperform in 259/391 (66.2%). The architecture split is pronounced: MHA models favour the handoff in 173/221 trials (78.3%); GQA models favour the handoff in only 56/119 trials (47.1%). Model-level Wilcoxon: W=214, N=23, p=0.010 (one-sided). An adaptive ablation width rule targets the 79/391 near-final-layer cases: it improves probe quality in 60/79 triggered cases (75.9%), mean gain +7.44pp. A direction-specificity control confirms the ablation effect is concept-direction specific: median 377x suppression rate versus random-direction ablation (99.1% of concept directions beat all 10 random seeds). Reference implementation: rosetta_tools v1.3.1 (doi:https://doi.org/10.5281/zenodo.20361433).
### Title:
          The Quantization Benefits of Residual-Free Transformers
 - **Authors:** Yiping Ji, Mahalakshmi Sabanayagam, Peyman Moghadam, Hemanth Saratchandran, Simon Lucey
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale transformer training and deployment are increasingly constrained by the transfer of activations, gradients, and optimizer states across accelerators. Low-bit quantization offers a natural remedy, but transformer activations are often heavy-tailed and outlier-dominated, making simple quantization highly lossy. We show that this difficulty is not only a property of the quantizer, but also of the architecture. Specifically, residual connections can drive transformer activations away from Gaussianity during training. Using controlled comparisons between residual and residual-free transformers, we demonstrate that this effect leads to substantially higher quantization error and accuracy degradation at low precision in residual models. We explain the phenomenon through an excess kurtosis analysis, showing that residual mixing can amplify non-Gaussianity, whereas dense mixing in residual-free contracts non-Gaussianity. We then show that residual-free transformers can be made trainable using orthogonal initialization, spectral or second-order optimization, and depth-aware scaling of attention temperature. In language tasks, while there is a small drop in full precision performance, these models retain near-Gaussian activations and exhibit significantly improved robustness to low-bit quantization. Our results identify an accuracy--compressibility trade-off in transformer design and motivate architecture-level approaches to quantization-friendly foundation models.
### Title:
          Predicting Stock Price Direction on Earnings Announcement Days using Multi-modal Deep Learning
 - **Authors:** Manuel Noseda, Nathan Soldati, Marco Paina
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Statistical Finance (q-fin.ST)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting stock price movements during Earnings Announcements (EAs) is a significant challenge due to market noise and high-impact price discontinuities. In this study, we evaluate whether pre-announcement news sentiment, firm fundamentals, and recent market dynamics jointly predict the directional price movement of equities on EA days. We construct a multi-modal feature space combining 15 fundamental metrics, 3 price-based technical indicators and sentiment scores derived from financial news articles processed using FinBERT. We compare a Long Short-Term Memory (LSTM) network and a Transformer-based architecture against a logistic regression baseline, and further assess all models with and without sentiment features to quantify their incremental value. Our results indicate that while the LSTM demonstrates higher precision through a conservative safe-bet strategy, the Transformer model exhibits superior sensitivity in identifying volatile movements, achieving a higher macro F1-score, with ablation experiments showing a consistent benefit from incorporating news sentiment.
### Title:
          Does Continued Pretraining on a Learner Corpus Improve Automated Essay Scoring on English Proficiency Tests? Evidence from EFCAMDAT
 - **Authors:** Duy Anh Nguyen
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent automated essay scoring (AES) studies increasingly use pretrained transformer models, but these models are usually pretrained on general-domain English and may under-represent second-language learner writing. This study investigates whether domain-adaptive continued pretraining (DAPT) on the EFCAMDAT learner corpus improves transformer-based AES for English proficiency tests. We apply DAPT to three transformer encoders and evaluate them on FCE and IELTS in both in-domain scoring and few-shot cross-dataset transfer. Full-corpus DAPT produces mixed results across models, datasets, and metrics. Further analyses suggest that these mixed effects are partly explained by mismatches in proficiency, genre, and communicative purpose between EFCAMDAT and the downstream datasets. A proficiency-based ablation shows that targeted DAPT using CEFR-aligned subsets improves downstream scoring more reliably than full-corpus DAPT, especially for FCE with B1--B2 data. However, these gains do not consistently improve cross-dataset transfer. Overall, the findings suggest that continued pretraining on a learner-writing corpus can benefit in-domain AES for English assessment when the pretraining data is sufficiently aligned with the downstream assessment settings. However, it does not automatically improve transferability across different English proficiency test datasets.
### Title:
          Where Concept Erasure Should Occur: Concept-Layer Alignment in Text-to-Video Diffusion Models
 - **Authors:** Yiwei Xie, Ping Liu, Zheng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-video diffusion transformers encode semantic information unevenly across model depth, which constrains effective concept erasure. We identify a representational bottleneck, termed concept-layer topological alignment, under which target concepts exhibit higher separability at certain representational depths. Outside these depths, concept and non-target signals remain strongly entangled, limiting the effectiveness of depth-specific erasure. This observation reframes concept erasure as the problem of identifying representational depths where concept-non-target separation naturally emerges. Motivated by this structural constraint, we introduce CLEAR, a separability-driven optimization framework for concept erasure that explicitly enforces concept-layer alignment. CLEAR operationalizes this principle by formulating layer selection as an optimization problem over concept-non-target separability, rather than relying on layer-agnostic or heuristic choices. To enable this, we introduce a separability-aware objective that favors layers exhibiting stronger concept-non-target separation. Experiments on large-scale text-to-video diffusion models demonstrate that enforcing concept--layer alignment leads to more precise concept suppression while preserving overall generative quality.
### Title:
          Context-driven Missing-Modality Learning for Robust Medical Diagnosis with Image-Tabular Data
 - **Authors:** Tianling Liu, Lequan Yu, Tong Han, Liang Wan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While multimodal data integrating diverse imaging and clinical tabular records is crucial for accurate medical diagnosis, the arbitrary absence of specific modalities is prevalent in clinical practice, severely degrading the performance of multimodal models. Existing methods either discard missing modalities, leading to information loss, or struggle to synthesize them without capturing complex inter-modal dependencies. To address these limitations, we propose a novel Context-driven Missing-Modality Learning (CMML) framework, which sequentially performs modality synthesis and semantic alignment to achieve robust diagnosis under arbitrary missing conditions. Specifically, we design a Cascade Residual Transformer-based Autoencoder (CRTA) that leverages learnable context tokens acting as dataset-level semantic prior to capture inter-modal dependencies and synthesize key missing representations. These representations are further enriched by modality-specific memory banks. To resolve the discrepancy between original available and synthesized representations, we transform the learned context tokens into instance-adaptive semantic references by infusing multimodal representations from the CRTA's outputs. This reference guides the alignment of heterogeneous modality representations into a unified space, where class-aware contrastive refinement is finally applied to explore discriminative diagnostic cues. Extensive evaluations on skin lesion (Derm7pt), ocular disease (ODIR), and meningioma (MEN) datasets demonstrate that CMML significantly outperforms state-of-the-art (SOTA) methods, yielding AVG AUC improvements of 1.26%, 0.97%, and 1.32%, respectively.
### Title:
          Triplet-Block Diffusion RWKV
 - **Authors:** Ke Lin, Yiyang Luo, Zhaolong Su, Yunya Song, Anyi Rao
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Causal Transformer language models suffer from strictly sequential decoding and a quadratic per-step attention cost. While linear-time causal models and discrete diffusion models each address these weaknesses, their integration remains inherently inconsistent: diffusion requires bidirectional attention, while causal models are unidirectional. To unify these architectures, we propose $B^3D-RWKV$, a diffusion RWKV variant that integrates the model's $O(L)$ inference efficiency with parallel, bidirectional discrete-diffusion through a \emph{triplet-block layout} method. $B^3D-RWKV-7.2B$ reaches comparable accuracy on an 8-task suite versus existing models while significantly outperforming baselines in decoding throughput with an average of $\mathbf{1.6\times}$ speedup.
### Title:
          Forgotten Words: Benchmarking NeoBERT for Dementia Detection in Low-Resource Conversational Filipino and English Speech
 - **Authors:** Rez Samantha Z. Floresca, Edric Castel C. Hao, Hannah Grachiella Buñales, Chelsea Dominique E. Temprosa, Georgianna Z. Reyes, Kervin Gabriel L. Chua
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dementia detection from spontaneous speech offers a scalable approach to cognitive screening, yet NLP systems remain predominantly English-centric. This limitation is especially acute in the Philippines, where Filipino-English code-switching is pervasive and no prior work has addressed NLP-based dementia detection. We present the first systematic evaluation of transformer-based dementia detection in Filipino speech and the first assessment of NeoBERT in a clinical NLP setting. To separate language from domain effects, we construct a parallel bilingual dataset of 4,000 DementiaBank-derived transcripts, with Filipino translations produced manually to preserve discourse-level markers of cognitive decline. We evaluate five model families, TF-IDF + LogReg, BERT, NeoBERT, XLM-R, and RoBERTa-Tagalog, under monolingual, zero-shot cross-lingual, and bilingual fine-tuning settings. We find that in-domain performance does not transfer across languages, with English-trained BERT dropping to Macro-F1 = 0.455 on Filipino, and that architectural modernization alone does not improve robustness. Bilingual fine-tuning, however, eliminates cross-lingual degradation across all transformer models, converging to Macro-F1 = 0.969-0.973. These results suggest that multilingual clinical NLP performance is driven primarily by linguistic coverage during training rather than model scale or architecture.
### Title:
          Length Generalization with Log-Depth Recurrent Units
 - **Authors:** Charles Pert, Dalal Alrajeh, Alessandra Russo
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Length generalization remains a persistent challenge for neural networks: recurrent models tend to suffer from positional biases, while transformers are constrained by fixed computational depth. Regular languages provide a frequently used testbed for evaluating length generalization, as label prediction can be checked for any sequence length. We propose MLP-LDRU, a type of Log-Depth Recurrent Unit, which captures a class of associativity-biased operators designed to approximate recurrence through parallel reduction. We evaluate MLP-LDRU on 21 regular-language tasks, consisting of standard benchmarks and new prefix languages, where it achieves 100% out-of-distribution accuracy on 18 tasks and at least 99.9% on the remaining 3 when increasing max training length, outperforming comparable recurrent and attention-based models. We further evaluate MLP-LDRU beyond regular languages on ListOps and NLP classification benchmarks, where it performs competitively.
### Title:
          OrpQuant: Geometric Orthogonal Residual Projection for Multiplier-Free Power-of-Two Transformer Quantization
 - **Authors:** Maoyang Xiang, Bo Wang, Tao Luo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The deployment of Large Language Models (LLMs) and Vision Transformers (ViTs) on edge devices is significantly constrained by memory limitations and the critical timing bottlenecks introduced by dense Multiply-Accumulate (MAC) arrays. In the ultra-low bit regime, logarithmic Power-of-Two (PoT) quantization provides a hardware-efficient alternative by replacing MAC operations with bit-shifts. However, the non-uniform exponential lattice is inherently limited by a \textbf{Low Angular Resolution Regime}, a structural flaw that becomes particularly pronounced at sub-4-bit thresholds, leading to a notable degradation of high-dimensional feature manifolds. To address this geometric limitation, we propose Orthogonal Residual Projection (ORP), an algorithm-hardware co-design framework. By formulating quantization as a dual-basis geometric projection, ORP adaptively synthesizes a higher-resolution residual lattice using strictly shift-and-add operations. Furthermore, ORP's analytical solver offers a practical alternative to computationally intensive gradient-based optimization, reducing the full-model calibration time for LLaMA-2-7B to approximately \textbf{15 minutes}. Extensive evaluations demonstrate ORP's applicability across modalities and its hardware efficiency. Under the 3-bit (W3/A16) constraint, ORP achieves a perplexity of 6.10 on LLaMA-2-7B, comparing favorably to conventional MAC-intensive baselines like AWQ without relying on asymmetric scaling, while maintaining competitive accuracy in 4-bit scenarios. At the silicon level, standard-cell RTL synthesis at a 28nm node indicates that ORP effectively mitigates the timing bottlenecks associated with dense multiplier trees.
### Title:
          Language Models Need Sleep
 - **Authors:** Sangyun Lee, Sean McLeish, Tom Goldstein, Giulia Fanti
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based large language models are increasingly used for long-horizon tasks; however, their attention mechanism scales poorly with context length. To handle this, we study a sleep-like consolidation mechanism in which a model periodically converts recent context into persistent fast weights before clearing its key-value cache. During sleep, the model performs $N$ offline recurrent passes over the accumulated context and updates the fast weights in its state-space model (SSM) blocks through a learned local rule. During inference, this shifts extra computation to sleep while preserving the latency of wake-time prediction. We test our method on controlled synthetic tasks, including cellular automata and multi-hop graph retrieval, as well as a realistic math reasoning task, on which a regular transformer as well as SSM-attention hybrid models fail. We then show that increasing sleep duration $N$ for our models improves performance, with the largest gains on examples that require deeper reasoning.
### Title:
          Looped Diffusion Language Models
 - **Authors:** Sanghyun Lee, Chunsan Hong, Seungryong Kim, Jonghyun Lee, Jongho Park, Dongmin Park
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Masked diffusion models (MDMs) have emerged as a promising alternative to autoregressive models for language modeling, yet the effective design of transformer architectures for MDMs remains underexplored. In this paper, we show that selectively looping the early-middle transformer layers significantly improves both training efficiency and model performance in MDMs. We call this approach LoopMDM(Looped Masked Diffusion Model), which brings two key benefits: looping layers at training-time yields a depth-scaling effect without adding parameters, while varying the number of loops at inference-time enables flexible compute scaling. Despite the simplicity, the results are striking: across multiple pre-training corpora, LoopMDM matches the performance of same-size MDMs with up to 3.3 fewer training FLOPs, while its final performance outperforms them on various reasoning benchmarks, including up to 8.5 points on GSM8K. It even surpasses deeper non-looped MDMs trained with comparable per-step compute, indicating that selective looping is more effective than naive depth scaling. Furthermore, LoopMDM can scale inference-time compute by increasing the number of loops. Adaptively adjusting the number of loops throughout the sampling process further yields additional gains in compute efficiency while maintaining performance. Lastly, with attention analysis, we provide evidence that looping is effective in MDMs by promoting interactions among masked positions. Our code and weights will be publicly released.
### Title:
          AnyScene: Towards Highly Controllable Driving Scene Generation at Anywhere and Beyond
 - **Authors:** Haiming Zhang, Junfei Zhou, Feng Jiang, Jingzhong Li, Zhenglong Guo, Penglin Dai, Jifeng Dai, Yan Xie, Benjin Zhu
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating high-fidelity and controllable synthetic data is critical for advancing end-to-end autonomous driving, particularly for addressing the long tail of rare safety-critical scenarios. Existing occupancy-guided methods typically rely on shallow conditioning mechanisms and reference-frame-dependent video synthesis, which limits fine-grained controllability from arbitrary BEV layouts and restricts their applicability for scalable simulation. In this paper, we propose AnyScene, a unified occupancy-centric framework for driving scene generation. AnyScene generates semantic occupancy sequences from BEV layouts through a Spatial-Temporal Occupancy Diffusion Transformer that jointly tokenizes BEV and occupancy features in an autoregressive manner. This design enables precise controllability from cross-dataset and user-defined BEV inputs while naturally supporting long-horizon generation. Building upon the generated occupancy, a Geometry-Grounded View Expansion module treats occupancy as the canonical spatial representation and synthesizes temporally consistent multi-view driving videos in a reference-free and autoregressive fashion, supporting flexible camera configurations at inference time. Extensive experiments demonstrate that AnyScene achieves state-of-the-art performance in both occupancy and video generation. It exhibits strong generalization to unseen and customized layouts, and provides measurable benefits for downstream tasks such as sparse-view 3D reconstruction.
## Keyword: autonomous driving
### Title:
          Reason--Imagine--Act: Closed-Loop LLM Decision Making with World Models for Autonomous Driving
 - **Authors:** Zhengqi Sun, Yiwen Sun, Boxuan Liu, Tailai Chen, Tianxu Guo, Jiabin Liu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are promising for autonomous driving, but semantics-only decision policies can yield physically unsafe behavior in dynamic traffic. Existing methods either perform online language reasoning without explicit dynamics verification or use world models mainly in offline pipelines, leaving a gap between semantic intent and physical feasibility at decision time. We propose Reason--Imagine--Act (RIA), a closed-loop framework that couples an LLM reasoner with an action-conditioned world model for online safety verification. At each step, the LLM proposes an action template and candidate sub-actions, the world model performs short-horizon rollouts, and a safety scorer selects the safest executable action with feedback to the next reasoning step. Under a unified CARLA point-goal protocol (1000 episodes), RIA achieves 80.05% route completion, 51.10% arrival rate, and 0.20% collision rate. Under the same closed-loop interface, RIA consistently outperforms training-free baselines, including CARLA TM and MADA, on core closed-loop metrics. For reproducibility, code is available at this https URL.
### Title:
          PEDESTRIANQA: A Benchmark for Vision-Language Models on Pedestrian Intention and Trajectory Prediction
 - **Authors:** Naman Mishra, Shankar Gangisetty, C. V. Jawahar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pedestrian intention and trajectory prediction are critical for the safe deployment of autonomous driving systems, directly influencing navigation decisions in complex traffic environments. Recent advances in large vision-language models offer a powerful new paradigm for these tasks by combining high-capacity visual understanding with flexible natural language reasoning. In this work, we introduce PedestrianQA, a large-scale video-based dataset that formulates pedestrian intention and trajectory prediction as question-answering tasks augmented with structured rationales. PedestrianQA expresses richly annotated pedestrian sequences, in natural language, enabling VLMs to learn from visual dynamics, contextual cues, and interactions among traffic agents while generating concise explanations of their predictions without needing specialized architectures tailored for each task. Empirical evaluations across PIE, JAAD, TITAN, and IDD-PeD show that finetuning state-of-the-art VLMs on PedestrianQA significantly improves intention classification, trajectory forecasting accuracy, and the quality of explanatory rationales, demonstrating the strong potential of VLMs as a unified and explainable framework for safety-critical pedestrian behavior modeling.
### Title:
          ARCANE-PedSynth: Synthetic Multi-Pedestrian Datasets with Behavioural Crossing Annotations
 - **Authors:** Muhammad Naveed Riaz, Maciej Wielgosz, Antonio M. López Peña
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present ARCANE-PedSynth, an open-source CARLA-based software framework for generating synthetic multi-pedestrian datasets with dense behavioural annotations for pedestrian crossing prediction in autonomous driving. The framework overcomes CARLA's native 9% crossing rate through a hybrid AI-manual pedestrian control architecture, enabling configurable target rates up to 75%. A 12-state behavioural finite state machine with five character archetypes produces diverse crossing behaviours. The framework generates synchronised RGB, LiDAR, and DVS data with per-frame crossing labels, behavioural states, and estimated 2D pose keypoints. We demonstrate ARCANE-PedSynth through PedSynth++, an example dataset generated with the framework, comprising 533 multi-pedestrian clips across 12 weather conditions with RGB, LiDAR, and DVS streams. ARCANE-PedSynth is fully reproducible via CLI parameterisation and Docker containerisation.
### Title:
          Scaling up Energy-Aware Multi-Agent Reinforcement Learning for Mission-Oriented Drone Networks with Individual Reward
 - **Authors:** Changling Li, Ying Li
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-agent reinforcement learning (MARL) has shown wide applicability in collaborative systems such as autonomous driving and smart cities for its ability of learning through interaction. With the recent development of drone networks, researchers have also applied MARL to address the trajectory planning problems. However, the dynamic environment and the limited battery capacity are still challenging for using MARL to achieve efficient collaborative task execution. In this paper, we propose an energy-aware MARL model as an attempt to tackle these challenges, leveraging Deep Q-Networks (DQN) with \emph{individual reward functions} driven by the task execution progress and the remaining battery of drones. We conduct a set of simulation studies for the proposed mode and compare it with the shared reward MARL~\cite{Li2022MARL} to explore the impact of credit assignment in MARL. The results indicate that our proposed model can achieve at least 80\% success rate regardless of the task locations and lengths. Similar to the shared reward mode, the individual reward mode can achieve a better success rate when the task density is high, and it can hit nearly a 100\% success rate when task density gets close to 40\%. The true advantage of our proposed model with individual reward is revealed when scaling up the environment. The comparison to the shared reward MARL shows that the our proposed model is more robust towards the change of the environment size and agent numbers. It can achieve higher success rate with fewer steps due to the clarity of the goal which improves energy efficiency even better.
### Title:
          RECTOR: Priority-Aware Rule-Based Reranking for Compliance-Aware Autonomous Driving Trajectory Selection
 - **Authors:** Hadi Hajieghrary, Benedikt Walter, Chaitanya Shinde, Paul Schmitt, Miguel Hurtado
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving stacks must pick one trajectory from a multi-modal candidate set; choosing by model confidence ignores safety, traffic-law, and comfort constraints. We present \textsc{RECTOR} (Rule-Enforced Constrained Trajectory Orchestrator), a post-generation reranking layer that scores candidates against a tiered rulebook (Safety~$\succ$~Legal~$\succ$~Road~$\succ$~Comfort) via differentiable proxies and a scene-conditioned applicability mechanism, then selects with a deterministic $\varepsilon$-lexicographic rule that preserves cross-tier priority by construction -- without retraining the predictor. On the Waymo Open Motion Dataset \texttt{validation\_interactive} split (43{,}219 augmented instances, $K{=}6$), under Protocol~B (28-rule proxy catalog, oracle applicability) rule-aware selection cuts Safety+Legal violations from 28.58\% to 20.42\% and Total from 40.32\% to 32.41\% versus confidence-only on the same candidates. A uniform-weight weighted-sum baseline matches binary compliance on this benchmark -- the empirical lift comes from rule-aware ranking, while the lexicographic guarantee is the structural differentiator no weight calibration can replicate. Under adversarial confidence corruption, confidence-only selection fails in 100\% of scenarios while both rule-aware selectors reject the injected mode in $\sim$96\%. All figures are proxy-evaluator results (not a safety certificate), open-loop, 5\,s horizon, U.S.\ rules, validation split.
### Title:
          Semantics-Guided Multimodal Masked Autoencoder Pretraining for 3D BEV Object Detection
 - **Authors:** Prabuddhi Wariyapperuma, Rajitha de Silva, Marc Hanheide, Thomas Bohné, Leonardo Guevara
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D bird's-eye view (BEV) object detection is essential for autonomous driving, and depends strongly on effective multimodal representations from complementary sensors such as cameras and LiDAR. Multimodal masked autoencoders have shown strong potential for learning such representations for downstream 3D BEV object detection. However, existing methods typically apply uniform random masking to camera and LiDAR inputs, treating all regions equally, and learn representations only through masked reconstruction. We propose a semantics-guided multimodal masked autoencoder framework that introduces semantic information during pretraining through two separate components: (i) semantics-guided LiDAR voxel masking, which preserves semantically important LiDAR regions more strongly, and (ii) an auxiliary point-wise LiDAR semantic decoder branch that injects semantic guidance in addition to reconstruction. On BEVFusion 3D object detection, our semantics-guided pretraining strategy improves performance on the nuScenes mini validation set compared to the standard UniM2AE baseline: semantics-guided LiDAR voxel masking yields +1.49% mean Average Precision (mAP) and +1.66% nuScenes Detection Score (NDS), while decoder-side point semantic supervision yields +1.39% mAP and +3.22% NDS over the baseline.
### Title:
          Neuromorphic LiDAR-based Bird's Eye View Object Detection using Energy-efficient Spiking Neural Networks
 - **Authors:** Sambit Mohapatra, Senthil Yogamani, Heinrich Gotzig, Patrick Mader
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving perception demands accurate and efficient processing of three-dimensional sensor data under strict power constraints. Traditional convolutional neural networks achieve strong detection accuracy but are computationally intensive, limiting their suitability for deployment on resource-constrained neuromorphic platforms. Spiking neural networks offer a compelling alternative through event-driven sparse computation, yet their application to complex real-world perception tasks such as three-dimensional object detection remains limited. In this work, we propose an end-to-end spiking encoder-decoder network for object detection in bird's eye view representations of LiDAR point clouds, trained using surrogate gradient backpropagation. We train two variants: a membrane potential variant that reads continuous neuron state at the output stage for maximum accuracy, achieving $92.05$/$87.04$/$86.51$ AP at $\mathrm{IoU}\!=\!0.5$ (Easy/Moderate/Hard), and, a fully binary spiking variant that operates exclusively on spike trains at every layer for direct neuromorphic deployment. We evaluate four input spike encoding strategies and demonstrate that allowing the network to learn spike representations directly from data outperforms hand-crafted Poisson, latency, and z-axis encoding schemes on the KITTI benchmark, where sequential frames are unavailable and the BEV input is presented repeatedly across timesteps as a proxy for temporal streaming. A block-wise energy analysis demonstrates a $3.33\times$ reduction in synaptic operation energy over an equivalent CNN under conservative loop-based operation. Together, these results demonstrate the viability of spiking neural networks for accurate and energy-efficient neuromorphic perception in autonomous driving.
### Title:
          Stabilizing Streaming Video Geometry via Dynamic Feature Normalization
 - **Authors:** Xiaoyang Lyu, Muxin Liu, Xiaoshan Wu, Ruicheng Wang, Yi-Hua Huang, Yang-Tian Sun, Shaoshuai Shi, Xiaojuan Qi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Consistent 3D geometry estimation from streaming RGB input is crucial for real-world applications such as autonomous driving, embodied AI, and large-scale reconstruction. While modern monocular geometry foundation models achieve strong single-image accuracy, they exhibit severe temporal inconsistency on continuous input, notably dominated by scale--shift drifting. Through targeted empirical analysis, we trace this instability to its root cause: fluctuations in latent feature statistics, whose mean and variance directly determine the predicted depth's scale and shift. Building on this insight, we introduce Dynamic Feature Normalization (DyFN), a lightweight, causal recurrent module that dynamically and robustly modulates feature statistics to maintain stable geometry over time. We adapt powerful pretrained monocular geometry models for streaming by finetuning only DyFN, a mere 2\% additional parameters, while keeping the backbone frozen, thereby achieving temporal consistency without compromising single-image accuracy. Extensive experiments across four benchmarks show that DyFN effectively eliminates temporal artifacts such as disjointed layering and positional jitter, and achieves state-of-the-art temporal stability, improving over prior streaming methods by up to 14\% and even outperforming heavier non-causal video baselines. Project Page: this https URL
### Title:
          Physics-Aware 3D Gaussian Editing for Driving Scene Generation
 - **Authors:** Feng Zhou, Jian Zhang, Yuhang Sun, He Wang, Qiong Wen, Debao Kong, Tieru Wu, Rui Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has shown great potential in autonomous driving simulation and data generation, enabling photorealistic reconstruction and flexible scene manipulation. However, existing 3DGS scene editing methods have limited support for road geometry editing (e.g., inserting speed humps or sunken roads), and generally do not couple such edits with plausible vehicle-road interaction dynamics. Such editing is essential for generating training data under extreme driving scenarios or evaluating system reliability under these road irregularities. Moreover, many optimization-based methods require minutes of per-edit refinement, while existing efficient alternatives mainly focus on appearance-level or object-level manipulation rather than physics-aware road irregularity editing. To address these limitations, we propose RoVES, a Road-and-Vehicle Editing System for physics-aware 3D Gaussian editing in driving scenes. RoVES enables single-image-driven road geometry insertion and couples the edited road profile with a 4-DOF half-car vehicle dynamics model to achieve physics-aware vehicle pose correction in vertical displacement and pitch. RoVES inserts road elements in a one-shot, optimization-free pipeline (1.84s), and the full pipeline (including color transfer and vehicle-dynamics-based pose correction) completes in 6.24s; it edits dynamic vehicles via pose editing and corrects poses frame-by-frame to approximate dynamics-consistent vertical displacement and pitch responses. Experiments on the Waymo dataset show that RoVES provides practical efficiency and competitive visual consistency for physics-aware driving scene generation.
### Title:
          Decision-Making with Lightweight Confidence-Aware Language Model for Autonomous Driving
 - **Authors:** Ruoyu Yao, Ruiguo Zhong, Pei Liu, Mingxing Peng, Rui Yang, Jun Ma
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) and Multimodal LLMs (MLLMs) have demonstrated immense potential in autonomous driving (AD) by offering human-like reasoning and open-world generalization. However, the excessive computational overhead and high inference latency of these massive models severely hinder their deployment in resource-constrained AD systems. To address this challenge, we propose a novel decision-making framework utilizing a lightweight confidence-aware language model, which bridges the gap between complex multimodal intention reasoning and efficient inference. Specifically, we design a multi-agent collaborative workflow, comprising action voting, confidence assessment, and summarization agents, to generate high-quality, confidence-annotated decision demonstrations via explicit Chain-of-Thought (CoT) reasoning. These demonstrations are then distilled into a lightweight language model featuring a dual-head architecture, enabling the joint prediction of decision probabilities and the generation of textual rationales. The distillation is realized via a confidence-aware fine-tuning strategy coupled with Retrieval Augmented Generation (RAG) to enhance the model's adaptability and data efficiency. Comprehensive closed-loop experiments on the nuPlan benchmark demonstrate that our approach achieves state-of-the-art (SOTA) success rates in both regular and long-tail scenarios while maintaining low inference latency.
### Title:
          A Pedestrian-Vehicle Interaction Benchmark and Annotation Framework for Unstructured Scenes via Uncalibrated Cameras
 - **Authors:** Haoyang Peng, Qian Hu, Songan Zhang, Ming Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Predicting the interaction between pedestrian and vehicle is essential for autonomous driving safety in unstructured and semi-structured scenarios; however, this task is severely hindered by the scarcity of public datasets that feature dense pedestrian-vehicle interactions. Most current studies rely on structured road data, leaving the complex, heterogeneous interactions found in unstructured environments insufficiently represented and researched. In this paper, we propose a dataset annotation framework based on video data from uncalibrated surveillance cameras and present PINNS (Pedestrian-vehicle Interaction dataset from uNcalibrated cameras in uNstructured Scenes). The dataset covers multiple countries and regions, includes diverse typical traffic scenarios, and considers variations in seasons, lighting conditions, and weather. It focuses on complex scenes with dense pedestrian-vehicle interactions and is designed to be easily extensible. The dataset is constructed and annotated according to the standard issued by the Chinese Association of Automation, providing both trajectory data and corresponding scene-level information. Furthermore, this paper analyzes current challenges and research directions in heterogeneous agent trajectory prediction, shows the necessity and usefulness of the proposed dataset. We hope our framework and dataset will facilitate research on trajectory prediction and autonomous driving in complex mixed traffic scenarios. PINNS is publicly available at this https URL.
### Title:
          AnyScene: Towards Highly Controllable Driving Scene Generation at Anywhere and Beyond
 - **Authors:** Haiming Zhang, Junfei Zhou, Feng Jiang, Jingzhong Li, Zhenglong Guo, Penglin Dai, Jifeng Dai, Yan Xie, Benjin Zhu
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating high-fidelity and controllable synthetic data is critical for advancing end-to-end autonomous driving, particularly for addressing the long tail of rare safety-critical scenarios. Existing occupancy-guided methods typically rely on shallow conditioning mechanisms and reference-frame-dependent video synthesis, which limits fine-grained controllability from arbitrary BEV layouts and restricts their applicability for scalable simulation. In this paper, we propose AnyScene, a unified occupancy-centric framework for driving scene generation. AnyScene generates semantic occupancy sequences from BEV layouts through a Spatial-Temporal Occupancy Diffusion Transformer that jointly tokenizes BEV and occupancy features in an autoregressive manner. This design enables precise controllability from cross-dataset and user-defined BEV inputs while naturally supporting long-horizon generation. Building upon the generated occupancy, a Geometry-Grounded View Expansion module treats occupancy as the canonical spatial representation and synthesizes temporally consistent multi-view driving videos in a reference-free and autoregressive fashion, supporting flexible camera configurations at inference time. Extensive experiments demonstrate that AnyScene achieves state-of-the-art performance in both occupancy and video generation. It exhibits strong generalization to unseen and customized layouts, and provides measurable benefits for downstream tasks such as sparse-view 3D reconstruction.
