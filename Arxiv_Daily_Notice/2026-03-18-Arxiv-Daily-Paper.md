# Showing new listings for Wednesday, 18 March 2026
## Keyword: SLAM
### Title:
          Industrial cuVSLAM Benchmark & Integration
 - **Authors:** Charbel Abi Hana, Kameel Amareen, Mohamad Mostafa, Dmitry Slepichev, Hesam Rabeti, Zheng Wang, Mihir Acharya, Anthony Rizk
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents a comprehensive benchmark evaluation of visual odometry (VO) and visual SLAM (VSLAM) systems for mobile robot navigation in real-world logistical environments. We compare multiple visual odometry approaches across controlled trajectories covering translational, rotational, and mixed motion patterns, as well as a large-scale production facility dataset spanning approximately 1.7 km. Performance is evaluated using Absolute Pose Error (APE) against ground truth from a Vicon motion capture system and a LiDAR-based SLAM reference. Our results show that a hybrid stack combining the cuVSLAM front-end with a custom SLAM back-end achieves the strongest mapping accuracy, motivating a deeper integration of cuVSLAM as the core VO component in our robotics stack. We further validate this integration by deploying and testing the cuVSLAM-based VO stack on an NVIDIA Jetson platform.
### Title:
          Fanar 2.0: Arabic Generative AI Stack
 - **Authors:** FANAR TEAM, Ummar Abbas, Mohammad Shahmeer Ahmad, Minhaj Ahmad, Abdulaziz Al-Homaid, Anas Al-Nuaimi, Enes Altinisik, Ehsaneddin Asgari, Sanjay Chawla, Shammur Chowdhury, Fahim Dalvi, Kareem Darwish, Nadir Durrani, Mohamed Elfeky, Ahmed Elmagarmid, Mohamed Eltabakh, Asim Ersoy, Masoomali Fatehkia, Mohammed Qusay Hashim, Majd Hawasly, Mohamed Hefeeda, Mus'ab Husaini, Keivin Isufaj, Soon-Gyo Jung, Houssam Lachemat, Ji Kim Lucas, Abubakr Mohamed, Tasnim Mohiuddin, Basel Mousi, Hamdy Mubarak, Ahmad Musleh, Mourad Ouzzani, Amin Sadeghi, Husrev Taha Sencar, Mohammed Shinoy, Omar Sinan, Yifan Zhang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Fanar 2.0, the second generation of Qatar's Arabic-centric Generative AI platform. Sovereignty is a first-class design principle: every component, from data pipelines to deployment infrastructure, was designed and operated entirely at QCRI, Hamad Bin Khalifa University. Fanar 2.0 is a story of resource-constrained excellence: the effort ran on 256 NVIDIA H100 GPUs, with Arabic having only ~0.5% of web data despite 400 million native speakers. Fanar 2.0 adopts a disciplined strategy of data quality over quantity, targeted continual pre-training, and model merging to achieve substantial gains within these constraints. At the core is Fanar-27B, continually pre-trained from a Gemma-3-27B backbone on a curated corpus of 120 billion high-quality tokens across three data recipes. Despite using 8x fewer pre-training tokens than Fanar 1.0, it delivers substantial benchmark improvements: Arabic knowledge (+9.1 pts), language (+7.3 pts), dialects (+3.5 pts), and English capability (+7.6 pts). Beyond the core LLM, Fanar 2.0 introduces a rich stack of new capabilities. FanarGuard is a state-of-the-art 4B bilingual moderation filter for Arabic safety and cultural alignment. The speech family Aura gains a long-form ASR model for hours-long audio. Oryx vision family adds Arabic-aware image and video understanding alongside culturally grounded image generation. An agentic tool-calling framework enables multi-step workflows. Fanar-Sadiq utilizes a multi-agent architecture for Islamic content. Fanar-Diwan provides classical Arabic poetry generation. FanarShaheen delivers LLM-powered bilingual translation. A redesigned multi-layer orchestrator coordinates all components through intent-aware routing and defense-in-depth safety validation. Taken together, Fanar 2.0 demonstrates that sovereign, resource-constrained AI development can produce systems competitive with those built at far greater scale.
### Title:
          Tarab: A Multi-Dialect Corpus of Arabic Lyrics and Poetry
 - **Authors:** Mo El-Haj
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce the Tarab Corpus, a large-scale cultural and linguistic resource that brings together Arabic song lyrics and poetry within a unified analytical framework. The corpus comprises 2.56 million verses and more than 13.5 million tokens, making it, to our knowledge, the largest open Arabic corpus of creative text spanning both classical and contemporary production. Tarab is broadly balanced between songs and poems and covers Classical Arabic, Modern Standard Arabic (MSA), and six major regional varieties: Egyptian, Gulf, Levantine, Iraqi, Sudanese, and Maghrebi Arabic. The artists and poets represented in the corpus are associated with 28 modern nation states and multiple historical eras, covering over fourteen centuries of Arabic creative expression from the Pre-Islamic period to the twenty-first century. Each verse is accompanied by structured metadata describing linguistic variety, geographic origin, and historical or cultural context, enabling comparative linguistic, stylistic, and diachronic analysis across genres and time. We describe the data collection, normalisation, and validation pipeline and present baseline analyses for variety identification and genre differentiation. The dataset is publicly available on HuggingFace at this https URL.
### Title:
          M^3: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM
 - **Authors:** Kerui Ren, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu, Bo Dai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Streaming reconstruction from uncalibrated monocular video remains challenging, as it requires both high-precision pose estimation and computationally efficient online refinement in dynamic environments. While coupling 3D foundation models with SLAM frameworks is a promising paradigm, a critical bottleneck persists: most multi-view foundation models estimate poses in a feed-forward manner, yielding pixel-level correspondences that lack the requisite precision for rigorous geometric optimization. To address this, we present M^3, which augments the Multi-view foundation model with a dedicated Matching head to facilitate fine-grained dense correspondences and integrates it into a robust Monocular Gaussian Splatting SLAM. M^3 further enhances tracking stability by incorporating dynamic area suppression and cross-inference intrinsic alignment. Extensive experiments on diverse indoor and outdoor benchmarks demonstrate state-of-the-art accuracy in both pose estimation and scene reconstruction. Notably, M^3 reduces ATE RMSE by 64.3% compared to VGGT-SLAM 2.0 and outperforms ARTDECO by 2.11 dB in PSNR on the ScanNet++ dataset.
## Keyword: odometry
### Title:
          SE(3)-LIO: Smooth IMU Propagation With Jointly Distributed Poses on SE(3) Manifold for Accurate and Robust LiDAR-Inertial Odometry
 - **Authors:** Gunhee Shin, Seungjae Lee, Jei Kong, Youngwoo Seo, Hyun Myung
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In estimating odometry accurately, an inertial measurement unit (IMU) is widely used owing to its high-rate measurements, which can be utilized to obtain motion information through IMU propagation. In this paper, we address the limitations of existing IMU propagation methods in terms of motion prediction and motion compensation. In motion prediction, the existing methods typically represent a 6-DoF pose by separating rotation and translation and propagate them on their respective manifold, so that the rotational variation is not effectively incorporated into translation propagation. During motion compensation, the relative transformation between predicted poses is used to compensate motion-induced distortion in other measurements, while inherent errors in the predicted poses introduce uncertainty in the relative transformation. To tackle these challenges, we represent and propagate the pose on SE(3) manifold, where propagated translation properly accounts for rotational variation. Furthermore, we precisely characterize the relative transformation uncertainty by considering the correlation between predicted poses, and incorporate this uncertainty into the measurement noise during motion compensation. To this end, we propose a LiDAR-inertial odometry (LIO), referred to as SE(3)-LIO, that integrates the proposed IMU propagation and uncertainty-aware motion compensation (UAMC). We validate the effectiveness of SE(3)-LIO on diverse datasets. Our source code and additional material are available at: this https URL.
### Title:
          PA-LVIO: Real-Time LiDAR-Visual-Inertial Odometry and Mapping with Pose-Only Bundle Adjustment
 - **Authors:** Hailiang Tang, Tisheng Zhang, Liqiang Wang, Xin Ding, Man Yuan, Xiaoji Niu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time LiDAR-visual-inertial odometry and mapping is crucial for navigation and planning tasks in intelligent transportation systems. This study presents a pose-only bundle adjustment (PA) LiDAR-visual-inertial odometry (LVIO), named PA-LVIO, to meet the urgent need for real-time navigation and mapping. The proposed PA framework for LiDAR and visual measurements is highly accurate and efficient, and it can derive reliable frame-to-frame constraints within multiple frames. A marginalization-free and frame-to-map (F2M) LiDAR measurement model is integrated into the state estimator to eliminate odometry drifts. Meanwhile, an IMU-centric online spatial-temporal calibration is employed to obtain a pixel-wise LiDAR-camera alignment. With accurate estimated odometry and extrinsics, a high-quality and RGB-rendered point-cloud map can be built. Comprehensive experiments are conducted on both public and private datasets collected by wheeled robot, unmanned aerial vehicle (UAV), and handheld devices with 28 sequences and more than 50 km trajectories. Sufficient results demonstrate that the proposed PA-LVIO yields superior or comparable performance to state-of-the-art LVIO methods, in terms of the odometry accuracy and mapping quality. Besides, PA-LVIO can run in real-time on both the desktop PC and the onboard ARM computer.
### Title:
          Industrial cuVSLAM Benchmark & Integration
 - **Authors:** Charbel Abi Hana, Kameel Amareen, Mohamad Mostafa, Dmitry Slepichev, Hesam Rabeti, Zheng Wang, Mihir Acharya, Anthony Rizk
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents a comprehensive benchmark evaluation of visual odometry (VO) and visual SLAM (VSLAM) systems for mobile robot navigation in real-world logistical environments. We compare multiple visual odometry approaches across controlled trajectories covering translational, rotational, and mixed motion patterns, as well as a large-scale production facility dataset spanning approximately 1.7 km. Performance is evaluated using Absolute Pose Error (APE) against ground truth from a Vicon motion capture system and a LiDAR-based SLAM reference. Our results show that a hybrid stack combining the cuVSLAM front-end with a custom SLAM back-end achieves the strongest mapping accuracy, motivating a deeper integration of cuVSLAM as the core VO component in our robotics stack. We further validate this integration by deploying and testing the cuVSLAM-based VO stack on an NVIDIA Jetson platform.
### Title:
          GenZ-LIO: Generalizable LiDAR-Inertial Odometry Beyond Indoor--Outdoor Boundaries
 - **Authors:** Daehan Lee, Hyungtae Lim, Seongjun Kim, Soonbin Rho, Changhyeon Lee, Sanghyun Park, Junwoo Hong, Eunseon Choi, Hyunyoung Jo, Soohee Han
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Light detection and ranging (LiDAR)-inertial odometry (LIO) enables accurate localization and mapping for autonomous navigation in various scenes. However, its performance remains sensitive to variations in spatial scale, which refers to the spatial extent of the scene reflected in the distribution of point ranges in a LiDAR scan. Transitions between confined indoor and expansive outdoor spaces induce substantial variations in point density, which may reduce robustness and computational efficiency. To address this issue, we propose GenZ-LIO, a LIO framework generalizable across both indoor and outdoor environments. GenZ-LIO comprises three key components. First, inspired by the principle of the proportional-integral-derivative (PID) controller, it adaptively regulates the voxel size for downsampling via feedback control, driving the voxelized point count toward a scale-informed setpoint while enabling stable and efficient processing across varying scene scales. Second, we formulate a hybrid-metric state update that jointly leverages point-to-plane and point-to-point residuals to mitigate LiDAR degeneracy arising from directionally insufficient geometric constraints. Third, to alleviate the computational burden introduced by point-to-point matching, we introduce a voxel-pruned correspondence search strategy that discards non-promising voxel candidates and reduces unnecessary computations. Experimental results demonstrate that GenZ-LIO achieves robust odometry estimation and improved computational efficiency across confined indoor, open outdoor, and transitional environments. Our code will be made publicly available upon publication.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          CLRNet: Targetless Extrinsic Calibration for Camera, Lidar and 4D Radar Using Deep Learning
 - **Authors:** Marcell Kegl, Andras Palffy, Csaba Benedek, Dariu M. Gavrila
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we address extrinsic calibration for camera, lidar, and 4D radar sensors. Accurate extrinsic calibration of radar remains a challenge due to the sparsity of its data. We propose CLRNet, a novel, multi-modal end-to-end deep learning (DL) calibration network capable of addressing joint camera-lidar-radar calibration, or pairwise calibration between any two of these sensors. We incorporate equirectangular projection, camera-based depth image prediction, additional radar channels, and leverage lidar with a shared feature space and loop closure loss. In extensive experiments using the View-of-Delft and Dual-Radar datasets, we demonstrate superior calibration accuracy compared to existing state-of-the-art methods, reducing both median translational and rotational calibration errors by at least 50%. Finally, we examine the domain transfer capabilities of the proposed network and baselines, when evaluating across datasets. The code will be made publicly available upon acceptance at: this https URL.
### Title:
          Robust Dynamic Object Detection in Cluttered Indoor Scenes via Learned Spatiotemporal Cues
 - **Authors:** Juan Rached, Yixuan Jia, Kota Kondo, Jonathan P. How
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable dynamic object detection in cluttered environments remains a critical challenge for autonomous navigation. Purely geometric LiDAR pipelines that rely on clustering and heuristic filtering can miss dynamic obstacles when they move in close proximity to static structure or are only partially observed. Vision-augmented approaches can provide additional semantic cues, but are often limited by closed-set detectors and camera field-of-view constraints, reducing robustness to novel obstacles and out-of-frustum events. In this work, we present a LiDAR-only framework that fuses temporal occupancy-grid-based motion segmentation with a learned bird's-eye-view (BEV) dynamic prior. A fusion module prioritizes 3D detections when available, while using the learned dynamic grid to recover detections that would otherwise be lost due to proximity-induced false negatives. Experiments with motion-capture ground truth show our method achieves 28.67% higher recall and 18.50% higher F1 score than the state-of-the-art in substantially cluttered environments while maintaining comparable precision and position error.
### Title:
          SE(3)-LIO: Smooth IMU Propagation With Jointly Distributed Poses on SE(3) Manifold for Accurate and Robust LiDAR-Inertial Odometry
 - **Authors:** Gunhee Shin, Seungjae Lee, Jei Kong, Youngwoo Seo, Hyun Myung
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In estimating odometry accurately, an inertial measurement unit (IMU) is widely used owing to its high-rate measurements, which can be utilized to obtain motion information through IMU propagation. In this paper, we address the limitations of existing IMU propagation methods in terms of motion prediction and motion compensation. In motion prediction, the existing methods typically represent a 6-DoF pose by separating rotation and translation and propagate them on their respective manifold, so that the rotational variation is not effectively incorporated into translation propagation. During motion compensation, the relative transformation between predicted poses is used to compensate motion-induced distortion in other measurements, while inherent errors in the predicted poses introduce uncertainty in the relative transformation. To tackle these challenges, we represent and propagate the pose on SE(3) manifold, where propagated translation properly accounts for rotational variation. Furthermore, we precisely characterize the relative transformation uncertainty by considering the correlation between predicted poses, and incorporate this uncertainty into the measurement noise during motion compensation. To this end, we propose a LiDAR-inertial odometry (LIO), referred to as SE(3)-LIO, that integrates the proposed IMU propagation and uncertainty-aware motion compensation (UAMC). We validate the effectiveness of SE(3)-LIO on diverse datasets. Our source code and additional material are available at: this https URL.
### Title:
          PA-LVIO: Real-Time LiDAR-Visual-Inertial Odometry and Mapping with Pose-Only Bundle Adjustment
 - **Authors:** Hailiang Tang, Tisheng Zhang, Liqiang Wang, Xin Ding, Man Yuan, Xiaoji Niu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time LiDAR-visual-inertial odometry and mapping is crucial for navigation and planning tasks in intelligent transportation systems. This study presents a pose-only bundle adjustment (PA) LiDAR-visual-inertial odometry (LVIO), named PA-LVIO, to meet the urgent need for real-time navigation and mapping. The proposed PA framework for LiDAR and visual measurements is highly accurate and efficient, and it can derive reliable frame-to-frame constraints within multiple frames. A marginalization-free and frame-to-map (F2M) LiDAR measurement model is integrated into the state estimator to eliminate odometry drifts. Meanwhile, an IMU-centric online spatial-temporal calibration is employed to obtain a pixel-wise LiDAR-camera alignment. With accurate estimated odometry and extrinsics, a high-quality and RGB-rendered point-cloud map can be built. Comprehensive experiments are conducted on both public and private datasets collected by wheeled robot, unmanned aerial vehicle (UAV), and handheld devices with 28 sequences and more than 50 km trajectories. Sufficient results demonstrate that the proposed PA-LVIO yields superior or comparable performance to state-of-the-art LVIO methods, in terms of the odometry accuracy and mapping quality. Besides, PA-LVIO can run in real-time on both the desktop PC and the onboard ARM computer.
### Title:
          Industrial cuVSLAM Benchmark & Integration
 - **Authors:** Charbel Abi Hana, Kameel Amareen, Mohamad Mostafa, Dmitry Slepichev, Hesam Rabeti, Zheng Wang, Mihir Acharya, Anthony Rizk
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents a comprehensive benchmark evaluation of visual odometry (VO) and visual SLAM (VSLAM) systems for mobile robot navigation in real-world logistical environments. We compare multiple visual odometry approaches across controlled trajectories covering translational, rotational, and mixed motion patterns, as well as a large-scale production facility dataset spanning approximately 1.7 km. Performance is evaluated using Absolute Pose Error (APE) against ground truth from a Vicon motion capture system and a LiDAR-based SLAM reference. Our results show that a hybrid stack combining the cuVSLAM front-end with a custom SLAM back-end achieves the strongest mapping accuracy, motivating a deeper integration of cuVSLAM as the core VO component in our robotics stack. We further validate this integration by deploying and testing the cuVSLAM-based VO stack on an NVIDIA Jetson platform.
### Title:
          AW-MoE: All-Weather Mixture of Experts for Robust Multi-Modal 3D Object Detection
 - **Authors:** Hongwei Lin, Xun Huang, Chenglu Wen, Cheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust 3D object detection under adverse weather conditions is crucial for autonomous driving. However, most existing methods simply combine all weather samples for training while overlooking data distribution discrepancies across different weather scenarios, leading to performance conflicts. To address this issue, we introduce AW-MoE, the framework that innovatively integrates Mixture of Experts (MoE) into weather-robust multi-modal 3D object detection approaches. AW-MoE incorporates Image-guided Weather-aware Routing (IWR), which leverages the superior discriminability of image features across weather conditions and their invariance to scene variations for precise weather classification. Based on this accurate classification, IWR selects the top-K most relevant Weather-Specific Experts (WSE) that handle data discrepancies, ensuring optimal detection under all weather conditions. Additionally, we propose a Unified Dual-Modal Augmentation (UDMA) for synchronous LiDAR and 4D Radar dual-modal data augmentation while preserving the realism of scenes. Extensive experiments on the real-world dataset demonstrate that AW-MoE achieves ~ 15% improvement in adverse-weather performance over state-of-the-art methods, while incurring negligible inference overhead. Moreover, integrating AW-MoE into established baseline detectors yields performance improvements surpassing current state-of-the-art methods. These results show the effectiveness and strong scalability of our AW-MoE. We will release the code publicly at this https URL.
### Title:
          GenZ-LIO: Generalizable LiDAR-Inertial Odometry Beyond Indoor--Outdoor Boundaries
 - **Authors:** Daehan Lee, Hyungtae Lim, Seongjun Kim, Soonbin Rho, Changhyeon Lee, Sanghyun Park, Junwoo Hong, Eunseon Choi, Hyunyoung Jo, Soohee Han
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Light detection and ranging (LiDAR)-inertial odometry (LIO) enables accurate localization and mapping for autonomous navigation in various scenes. However, its performance remains sensitive to variations in spatial scale, which refers to the spatial extent of the scene reflected in the distribution of point ranges in a LiDAR scan. Transitions between confined indoor and expansive outdoor spaces induce substantial variations in point density, which may reduce robustness and computational efficiency. To address this issue, we propose GenZ-LIO, a LIO framework generalizable across both indoor and outdoor environments. GenZ-LIO comprises three key components. First, inspired by the principle of the proportional-integral-derivative (PID) controller, it adaptively regulates the voxel size for downsampling via feedback control, driving the voxelized point count toward a scale-informed setpoint while enabling stable and efficient processing across varying scene scales. Second, we formulate a hybrid-metric state update that jointly leverages point-to-plane and point-to-point residuals to mitigate LiDAR degeneracy arising from directionally insufficient geometric constraints. Third, to alleviate the computational burden introduced by point-to-point matching, we introduce a voxel-pruned correspondence search strategy that discards non-promising voxel candidates and reduces unnecessary computations. Experimental results demonstrate that GenZ-LIO achieves robust odometry estimation and improved computational efficiency across confined indoor, open outdoor, and transitional environments. Our code will be made publicly available upon publication.
### Title:
          Learning Human-Object Interaction for 3D Human Pose Estimation from LiDAR Point Clouds
 - **Authors:** Daniel Sungho Jung, Dohee Cho, Kyoung Mu Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding humans from LiDAR point clouds is one of the most critical tasks in autonomous driving due to its close relationships with pedestrian safety, yet it remains challenging in the presence of diverse human-object interactions and cluttered backgrounds. Nevertheless, existing methods largely overlook the potential of leveraging human-object interactions to build robust 3D human pose estimation frameworks. There are two major challenges that motivate the incorporation of human-object interaction. First, human-object interactions introduce spatial ambiguity between human and object points, which often leads to erroneous 3D human keypoint predictions in interaction regions. Second, there exists severe class imbalance in the number of points between interacting and non-interacting body parts, with the interaction-frequent regions such as hand and foot being sparsely observed in LiDAR data. To address these challenges, we propose a Human-Object Interaction Learning (HOIL) framework for robust 3D human pose estimation from LiDAR point clouds. To mitigate the spatial ambiguity issue, we present human-object interaction-aware contrastive learning (HOICL) that effectively enhances feature discrimination between human and object points, particularly in interaction regions. To alleviate the class imbalance issue, we introduce contact-aware part-guided pooling (CPPool) that adaptively reallocates representational capacity by compressing overrepresented points while preserving informative points from interacting body parts. In addition, we present an optional contact-based temporal refinement that refines erroneous per-frame keypoint estimates using contact cues over time. As a result, our HOIL effectively leverages human-object interaction to resolve spatial ambiguity and class imbalance in interaction regions. Codes will be released.
### Title:
          $x^2$-Fusion: Cross-Modality and Cross-Dimension Flow Estimation in Event Edge Space
 - **Authors:** Ruishan Guo, Ciyu Ruan, Haoyang Wang, Zihang Gong, Jingao Xu, Xinlei Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Estimating dense 2D optical flow and 3D scene flow is essential for dynamic scene understanding. Recent work combines images, LiDAR, and event data to jointly predict 2D and 3D motion, yet most approaches operate in separate heterogeneous feature spaces. Without a shared latent space that all modalities can align to, these systems rely on multiple modality-specific blocks, leaving cross-sensor mismatches unresolved and making fusion unnecessarily this http URL cameras naturally provide a spatiotemporal edge signal, which we can treat as an intrinsic edge field to anchor a unified latent representation, termed the Event Edge Space. Building on this idea, we introduce $x^2$-Fusion, which reframes multimodal fusion as representation unification: event-derived spatiotemporal edges define an edge-centric homogeneous space, and image and LiDAR features are explicitly aligned in this shared this http URL this space, we perform reliability-aware adaptive fusion to estimate modality reliability and emphasize stable cues under degradation. We further employ cross-dimension contrast learning to tightly couple 2D optical flow with 3D scene flow. Extensive experiments on both synthetic and real benchmarks show that $x^2$-Fusion achieves state-of-the-art accuracy under standard conditions and delivers substantial improvements in challenging scenarios.
### Title:
          WildDepth: A Multimodal Dataset for 3D Wildlife Perception and Depth Estimation
 - **Authors:** Muhammad Aamir, Naoya Muramatsu, Sangyun Shin, Matthew Wijers, Jiaxing Jhong, Xinyu Hou, Amir Patel, Andrew Markham
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Digital Libraries (cs.DL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Depth estimation and 3D reconstruction have been extensively studied as core topics in computer vision. Starting from rigid objects with relatively simple geometric shapes, such as vehicles, the research has expanded to address general objects, including challenging deformable objects, such as humans and animals. However, for the animal, in particular, the majority of existing models are trained based on datasets without metric scale, which can help validate image-only models. To address this limitation, we present WildDepth, a multimodal dataset and benchmark suite for depth estimation, behavior detection, and 3D reconstruction from diverse categories of animals ranging from domestic to wild environments with synchronized RGB and LiDAR. Experimental results show that the use of multi-modal data improves depth reliability by up to 10% RMSE, while RGB-LiDAR fusion enhances 3D reconstruction fidelity by 12% in Chamfer distance. By releasing WildDepth and its benchmarks, we aim to foster robust multimodal perception systems that generalize across domains.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          SAC-NeRF: Adaptive Ray Sampling for Neural Radiance Fields via Soft Actor-Critic Reinforcement Learning
 - **Authors:** Chenyu Ge
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural Radiance Fields (NeRF) have achieved photorealistic novel view synthesis but suffer from computational inefficiency due to dense ray sampling during volume rendering. We propose SAC-NeRF, a reinforcement learning framework that learns adaptive sampling policies using Soft Actor-Critic (SAC). Our method formulates sampling as a Markov Decision Process where an RL agent learns to allocate samples based on scene characteristics. We introduce three technical components: (1) a Gaussian mixture distribution color model providing uncertainty estimates, (2) a multi-component reward function balancing quality, efficiency, and consistency, and (3) a two-stage training strategy addressing environment non-stationarity. Experiments on Synthetic-NeRF and LLFF datasets show that SAC-NeRF reduces sampling points by 35-48\% while maintaining rendering quality within 0.3-0.8 dB PSNR of dense sampling baselines. While the learned policy is scene-specific and the RL framework adds complexity compared to simpler heuristics, our work demonstrates that data-driven sampling strategies can discover effective patterns that would be difficult to hand-design.
## Keyword: mapping
### Title:
          Bayesian-guided inverse design of hyperelastic microstructures: Application to stochastic metamaterials
 - **Authors:** Hooman Danesh, Henning Wessels
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 From a given pool of all feasible design variants, our aim is to identify a structure that achieves a target macroscopic stress response. For each candidate design, the response is obtained from a high-fidelity oracle, in particular, time- and resource-intensive computational homogenization or experiments. We consider the case where (i) the geometry cannot be conveniently parameterized, rendering gradient-based optimization inapplicable, and (ii) brute-force evaluation of all candidates is infeasible due to the cost of oracle queries. To tackle this challenge, we propose a Bayesian-guided inverse design framework that proceeds as follows. First, the dimensionality of the design variants is reduced through statistical feature engineering, and the resulting low-dimensional descriptors are mapped to effective constitutive parameters describing the macroscopic hyperelastic response. This mapping is modeled using a multi-output Gaussian process surrogate that accounts for correlations between the parameters. The surrogate is trained using uncertainty-driven active learning under severe budget constraints, allowing only a very limited number of high-fidelity oracle evaluations. Based on surrogate predictions, a finite number of promising candidates are shortlisted. Since the surrogate accuracy is inherently limited, the final selection of the optimal design is performed through high-fidelity oracle evaluations within the shortlist. In numerical test cases, we consider a dataset of 50,000 candidate structures. Active learning requires labeling less than half a percent of the full dataset. Bayesian-guided inverse design under unseen loading conditions reaches a prescribed error threshold with only a handful of oracle evaluations in the majority of cases.
### Title:
          Generative Inverse Design with Abstention via Diagonal Flow Matching
 - **Authors:** Miguel de Campos, Werner Krebs, Hanno Gottschalk
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inverse design aims to find design parameters $x$ achieving target performance $y^*$. Generative approaches learn bidirectional mappings between designs and labels, enabling diverse solution sampling. However, standard conditional flow matching (CFM), when adapted to inverse problems by pairing labels with design parameters, exhibits strong sensitivity to their arbitrary ordering and scaling, leading to unstable training. We introduce Diagonal Flow Matching (Diag-CFM), which resolves this through a zero-anchoring strategy that pairs design coordinates with noise and labels with zero, making the learning problem provably invariant to coordinate permutations. This yields order-of-magnitude improvements in round-trip accuracy over CFM and invertible neural network baselines across design dimensions up to $P{=}100$. We develop two architecture-intrinsic uncertainty metrics, Zero-Deviation and Self-Consistency, that enable three practical capabilities: selecting the best candidate among multiple generations, abstaining from unreliable predictions, and detecting out-of-distribution targets; consistently outperforming ensemble and general-purpose alternatives across all tasks. We validate on airfoil, gas turbine combustor, and an analytical benchmark with scalable design dimension.
### Title:
          CTG-DB: An Ontology-Based Transformation of ClinicalTrials.gov to Enable Cross-Trial Drug Safety Analyses
 - **Authors:** Jeffery L. Painter, François Haguinet, Andrew Bate
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 this http URL (this http URL) is the largest publicly accessible registry of clinical studies, yet its registry-oriented architecture and heterogeneous adverse event (AE) terminology limit systematic pharmacovigilance (PV) analytics. AEs are typically recorded as investigator-reported text rather than standardized identifiers, requiring manual reconciliation to identify coherent safety concepts. We present the this http URL Transformation Database (CTG-DB), an open-source pipeline that ingests the complete this http URL XML archive and produces a relational database aligned to standardized AE terminology using the Medical Dictionary for Regulatory Activities (MedDRA). CTG-DB preserves arm-level denominators, represents placebo and comparator arms, and normalizes AE terminology using deterministic exact and fuzzy matching to ensure transparent and reproducible mappings. This framework enables concept-level retrieval and cross-trial aggregation for scalable placebo-referenced safety analyses and integration of clinical trial evidence into downstream PV signal detection.
### Title:
          Determinism in the Undetermined: Deterministic Output in Charge-Conserving Continuous-Time Neuromorphic Systems with Temporal Stochasticity
 - **Authors:** Jing Yan, Kang You, Zhezhi He, Yaoyu Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Achieving deterministic computation results in asynchronous neuromorphic systems remains a fundamental challenge due to the inherent temporal stochasticity of continuous-time hardware. To address this, we develop a unified continuous-time framework for spiking neural networks (SNNs) that couples the Law of Charge Conservation with minimal neuron-level constraints. This integration ensures that the terminal state depends solely on the aggregate input charge, providing a unique cumulated output invariant to temporal stochasticity. We prove that this mapping is strictly invariant to spike timing in acyclic networks, whereas recurrent connectivity can introduce temporal sensitivity. Furthermore, we establish an exact representational correspondence between these charge-conserving SNNs and quantized artificial neural networks, bridging the gap between static deep learning and event-driven dynamics without approximation errors. These results establish a rigorous theoretical basis for designing continuous-time neuromorphic systems that harness the efficiency of asynchronous processing while maintaining algorithmic determinism.
### Title:
          CoDesignAI: An AI-Enabled Multi-Agent, Multi-User System for Collaborative Urban Design at the Conceptual Stage
 - **Authors:** Zhaoxi Zhang, Ruolin Wu, Feiyang Ren, Sridevi Turaga, Tamir Mendel
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Public participation has become increasingly important in collaborative urban design; yet, existing processes often face challenges in achieving efficient and scalable citizen engagement. To address this gap, this study explores how large language models (LLMs) can support cooperation among community members in participatory design. We introduce CoDesignAI, a collaborative urban design tool that combines multiple users, representing residents or stakeholders, with multiple AI agents, representing domain experts who provide facilitation and professional knowledge during the conceptual stage of urban design. This paper presents the system architecture and main components of the tool, illustrating how users interact with AI agents within a collaborative and iterative design workflow. Specifically, the system integrates generative AI with spatial mapping services to support street-level visualization of design proposals. AI agents assist users by summarizing discussion content, extracting shared design intentions, and generating prompts for presenting design interventions. The system also enables users to revise and refine their ideas over multiple rounds while documenting the design process. By combining conversational AI, multi-user interaction, and image-based design grounded in real-world urban contexts, this study argues that AI-enabled design systems can help shift urban design from an expert-centered practice to a more open and participatory process. The paper contributes a new web-based platform for AI-assisted collaborative design and offers an early exploration of how AI agents may expand the capacity for public participation in urban design.
### Title:
          FlatLands: Generative Floormap Completion From a Single Egocentric View
 - **Authors:** Subhransu S. Bhattacharjee, Dylan Campbell, Rahul Shome
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A single egocentric image typically captures only a small portion of the floor, yet a complete metric traversability map of the surroundings would better serve applications such as indoor navigation. We introduce FlatLands, a dataset and benchmark for single-view bird's-eye view (BEV) floor completion. The dataset contains 270,575 observations from 17,656 real metric indoor scenes drawn from six existing datasets, with aligned observation, visibility, validity, and ground-truth BEV maps, and the benchmark includes both in- and out-of-distribution evaluation protocols. We compare training-free approaches, deterministic models, ensembles, and stochastic generative models. Finally, we instantiate the task as an end-to-end monocular RGB-to-floormaps pipeline. FlatLands provides a rigorous testbed for uncertainty-aware indoor mapping and generative completion for embodied navigation.
### Title:
          The Era of End-to-End Autonomy: Transitioning from Rule-Based Driving to Large Driving Models
 - **Authors:** Eduardo Nebot, Julie Stephany Berrio Perez
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving is undergoing a shift from modular rule based pipelines toward end to end (E2E) learning systems. This paper examines this transition by tracing the evolution from classical sense perceive plan control architectures to large driving models (LDMs) capable of mapping raw sensor input directly to driving actions. We analyze recent developments including Tesla's Full Self Driving (FSD) V12 V14, Rivian's Unified Intelligence platform, NVIDIA Cosmos, and emerging commercial robotaxi deployments, focusing on architectural design, deployment strategies, safety considerations and industry implications. A key emerging product category is supervised E2E driving, often referred to as FSD (Supervised) or L2 plus plus, which several manufacturers plan to deploy from 2026 onwards. These systems can perform most of the Dynamic Driving Task (DDT) in complex environments while requiring human supervision, shifting the driver's role to safety oversight. Early operational evidence suggests E2E learning handles the long tail distribution of real world driving scenarios and is becoming a dominant commercial strategy. We also discuss how similar architectural advances may extend beyond autonomous vehicles (AV) to other embodied AI systems, including humanoid robotics.
### Title:
          Volumetrically Consistent Implicit Atlas Learning via Neural Diffeomorphic Flow for Placenta MRI
 - **Authors:** Athena Taymourtash, S. Mazdak Abulnaga, Esra Abaci Turk, P. Ellen Grant, Polina Golland
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Establishing dense volumetric correspondences across anatomical shapes is essential for group-level analysis but remains challenging for implicit neural representations. Most existing implicit registration methods rely on supervision near the zero-level set and thus capture only surface correspondences, leaving interior deformations under-constrained. We introduce a volumetrically consistent implicit model that couples reconstruction of signed distance functions (SDFs) with neural diffeomorphic flow to learn a shared canonical template of the placenta. Volumetric regularization, including Jacobian-determinant and biharmonic penalties, suppresses local folding and promotes globally coherent deformations. In the motivating application to placenta MRI, our formulation jointly reconstructs individual placentas, aligns them to a population-derived implicit template, and enables voxel-wise intensity mapping in a unified canonical space. Experiments on in-vivo placenta MRI scans demonstrate improved geometric fidelity and volumetric alignment over surface-based implicit baseline methods, yielding anatomically interpretable and topologically consistent flattening suitable for group analysis.
### Title:
          RecBundle: A Next-Generation Geometric Paradigm for Explainable Recommender Systems
 - **Authors:** Hui Wang, Tianzhu Hu, Mingming Li, Xi Zhou, Chun Gan, Jiao Dai, Jizhong Han, Songlin Hu, Tao Guo
 - **Subjects:** Subjects:
Information Retrieval (cs.IR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recommender systems are inherently dynamic feedback loops where prolonged local interactions accumulate into macroscopic structural degradation such as information cocoons. Existing representation learning paradigms are universally constrained by the assumption of a single flat space, forcing topologically grounded user associations and semantically driven historical interactions to be fitted within the same vector space. This excessive coupling of heterogeneous information renders it impossible for researchers to mechanistically distinguish and identify the sources of systemic bias. To overcome this theoretical bottleneck, we introduce Fiber Bundle from modern differential geometry and propose a novel geometric analysis paradigm for recommender systems. This theory naturally decouples the system space into two hierarchical layers: the base manifold formed by user interaction networks, and the fibers attached to individual user nodes that carry their dynamic preferences. Building upon this, we construct RecBundle, a framework oriented toward next-generation recommender systems that formalizes user collaboration as geometric connection and parallel transport on the base manifold, while mapping content evolution to holonomy transformations on fibers. From this foundation, we identify future application directions encompassing quantitative mechanisms for information cocoons and evolutionary bias, geometric meta-theory for adaptive recommendation, and novel inference architectures integrating large language models (LLMs). Empirical analysis on real-world MovieLens and Amazon Beauty datasets validates the effectiveness of this geometric framework.
### Title:
          PA-LVIO: Real-Time LiDAR-Visual-Inertial Odometry and Mapping with Pose-Only Bundle Adjustment
 - **Authors:** Hailiang Tang, Tisheng Zhang, Liqiang Wang, Xin Ding, Man Yuan, Xiaoji Niu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time LiDAR-visual-inertial odometry and mapping is crucial for navigation and planning tasks in intelligent transportation systems. This study presents a pose-only bundle adjustment (PA) LiDAR-visual-inertial odometry (LVIO), named PA-LVIO, to meet the urgent need for real-time navigation and mapping. The proposed PA framework for LiDAR and visual measurements is highly accurate and efficient, and it can derive reliable frame-to-frame constraints within multiple frames. A marginalization-free and frame-to-map (F2M) LiDAR measurement model is integrated into the state estimator to eliminate odometry drifts. Meanwhile, an IMU-centric online spatial-temporal calibration is employed to obtain a pixel-wise LiDAR-camera alignment. With accurate estimated odometry and extrinsics, a high-quality and RGB-rendered point-cloud map can be built. Comprehensive experiments are conducted on both public and private datasets collected by wheeled robot, unmanned aerial vehicle (UAV), and handheld devices with 28 sequences and more than 50 km trajectories. Sufficient results demonstrate that the proposed PA-LVIO yields superior or comparable performance to state-of-the-art LVIO methods, in terms of the odometry accuracy and mapping quality. Besides, PA-LVIO can run in real-time on both the desktop PC and the onboard ARM computer.
### Title:
          PureCLIP-Depth: Prompt-Free and Decoder-Free Monocular Depth Estimation within CLIP Embedding Space
 - **Authors:** Ryutaro Miya, Kazuyoshi Fushinobu, Tatsuya Kawaguchi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose PureCLIP-Depth, a completely prompt-free, decoder-free Monocular Depth Estimation (MDE) model that operates entirely within the Contrastive Language-Image Pre-training (CLIP) embedding space. Unlike recent models that rely heavily on geometric features, we explore a novel approach to MDE driven by conceptual information, performing computations directly within the conceptual CLIP space. The core of our method lies in learning a direct mapping from the RGB domain to the depth domain strictly inside this embedding space. Our approach achieves state-of-the-art performance among CLIP embedding-based models on both indoor and outdoor datasets. The code used in this research is available at: this https URL
### Title:
          Industrial cuVSLAM Benchmark & Integration
 - **Authors:** Charbel Abi Hana, Kameel Amareen, Mohamad Mostafa, Dmitry Slepichev, Hesam Rabeti, Zheng Wang, Mihir Acharya, Anthony Rizk
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work presents a comprehensive benchmark evaluation of visual odometry (VO) and visual SLAM (VSLAM) systems for mobile robot navigation in real-world logistical environments. We compare multiple visual odometry approaches across controlled trajectories covering translational, rotational, and mixed motion patterns, as well as a large-scale production facility dataset spanning approximately 1.7 km. Performance is evaluated using Absolute Pose Error (APE) against ground truth from a Vicon motion capture system and a LiDAR-based SLAM reference. Our results show that a hybrid stack combining the cuVSLAM front-end with a custom SLAM back-end achieves the strongest mapping accuracy, motivating a deeper integration of cuVSLAM as the core VO component in our robotics stack. We further validate this integration by deploying and testing the cuVSLAM-based VO stack on an NVIDIA Jetson platform.
### Title:
          GenZ-LIO: Generalizable LiDAR-Inertial Odometry Beyond Indoor--Outdoor Boundaries
 - **Authors:** Daehan Lee, Hyungtae Lim, Seongjun Kim, Soonbin Rho, Changhyeon Lee, Sanghyun Park, Junwoo Hong, Eunseon Choi, Hyunyoung Jo, Soohee Han
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Light detection and ranging (LiDAR)-inertial odometry (LIO) enables accurate localization and mapping for autonomous navigation in various scenes. However, its performance remains sensitive to variations in spatial scale, which refers to the spatial extent of the scene reflected in the distribution of point ranges in a LiDAR scan. Transitions between confined indoor and expansive outdoor spaces induce substantial variations in point density, which may reduce robustness and computational efficiency. To address this issue, we propose GenZ-LIO, a LIO framework generalizable across both indoor and outdoor environments. GenZ-LIO comprises three key components. First, inspired by the principle of the proportional-integral-derivative (PID) controller, it adaptively regulates the voxel size for downsampling via feedback control, driving the voxelized point count toward a scale-informed setpoint while enabling stable and efficient processing across varying scene scales. Second, we formulate a hybrid-metric state update that jointly leverages point-to-plane and point-to-point residuals to mitigate LiDAR degeneracy arising from directionally insufficient geometric constraints. Third, to alleviate the computational burden introduced by point-to-point matching, we introduce a voxel-pruned correspondence search strategy that discards non-promising voxel candidates and reduces unnecessary computations. Experimental results demonstrate that GenZ-LIO achieves robust odometry estimation and improved computational efficiency across confined indoor, open outdoor, and transitional environments. Our code will be made publicly available upon publication.
### Title:
          OGScene3D: Incremental Open-Vocabulary 3D Gaussian Scene Graph Mapping for Scene Understanding
 - **Authors:** Siting Zhu, Ziyun Lu, Guangming Wang, Chenguang Huang, Yongbo Chen, I-Ming Chen, Wolfram Burgard, Hesheng Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-vocabulary scene understanding is crucial for robotic applications, enabling robots to comprehend complex 3D environmental contexts and supporting various downstream tasks such as navigation and manipulation. However, existing methods require pre-built complete 3D semantic maps to construct scene graphs for scene understanding, which limits their applicability in robotic scenarios where environments are explored incrementally. To address this challenge, we propose OGScene3D, an open-vocabulary scene understanding system that achieves accurate 3D semantic mapping and scene graph construction incrementally. Our system employs a confidence-based Gaussian semantic representation that jointly models semantic predictions and their reliability, enabling robust scene modeling. Building on this representation, we introduce a hierarchical 3D semantic optimization strategy that achieves semantic consistency through local correspondence establishment and global refinement, thereby constructing globally consistent semantic maps. Moreover, we design a long-term global optimization method that leverages temporal memory of historical observations to enhance semantic predictions. By integrating 2D-3D semantic consistency with Gaussian rendering contribution, this method continuously refines the semantic understanding of the entire this http URL, we develop a progressive graph construction approach that dynamically creates and updates both nodes and semantic relationships, allowing continuous updating of the 3D scene graphs. Extensive experiments on widely used datasets and real-world scenes demonstrate the effectiveness of our OGScene3D on open-vocabulary scene understanding.
### Title:
          Micro-AU CLIP: Fine-Grained Contrastive Learning from Local Independence to Global Dependency for Micro-Expression Action Unit Detection
 - **Authors:** Jinsheng Wei, Fengzhou Guo, Yante Li, Haoyu Chen, Guanming Lu, Guoying Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Micro-expression (ME) action units (Micro-AUs) provide objective clues for fine-grained genuine emotion analysis. Most existing Micro-AU detection methods learn AU features from the whole facial image/video, which conflicts with the inherent locality of AU, resulting in insufficient perception of AU regions. In fact, each AU independently corresponds to specific localized facial muscle movements (local independence), while there is an inherent dependency between some AUs under specific emotional states (global dependency). Thus, this paper explores the effectiveness of the independence-to-dependency pattern and proposes a novel micro-AU detection framework, micro-AU CLIP, that uniquely decomposes the AU detection process into local semantic independence modeling (LSI) and global semantic dependency (GSD) modeling. In LSI, Patch Token Attention (PTA) is designed, mapping several local features within the AU region to the same feature space; In GSD, Global Dependency Attention (GDA) and Global Dependency Loss (GDLoss) are presented to model the global dependency relationships between different AUs, thereby enhancing each AU feature. Furthermore, considering CLIP's native limitations in micro-semantic alignment, a microAU contrastive loss (MiAUCL) is designed to learn AU features by a fine-grained alignment of visual and text features. Also, Micro-AU CLIP is effectively applied to ME recognition in an emotion-label-free way. The experimental results demonstrate that Micro-AU CLIP can fully learn fine-grained micro-AU features, achieving state-of-the-art performance.
### Title:
          Automated identification of Ichneumonoidea wasps via YOLO-based deep learning: Integrating HiresCam for Explainable AI
 - **Authors:** Joao Manoel Herrera Pinheiro, Gabriela Do Nascimento Herrera, Alvaro Doria Dos Santos, Luciana Bueno Dos Reis Fernandes, Ricardo V. Godoy, Eduardo A. B. Almeida, Helena Carolina Onody, Marcelo Andrade Da Costa Vieira, Angelica Maria Penteado-Dias, Marcelo Becker
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate taxonomic identification of parasitoid wasps within the superfamily Ichneumonoidea is essential for biodiversity assessment, ecological monitoring, and biological control programs. However, morphological similarity, small body size, and fine-grained interspecific variation make manual identification labor-intensive and expertise-dependent. This study proposes a deep learning-based framework for the automated identification of Ichneumonoidea wasps using a YOLO-based architecture integrated with High-Resolution Class Activation Mapping (HiResCAM) to enhance interpretability. The proposed system simultaneously identifies wasp families from high-resolution images. The dataset comprises 3556 high-resolution images of Hymenoptera specimens. The taxonomic distribution is primarily concentrated among the families Ichneumonidae (n = 786), Braconidae (n = 648), Apidae (n = 466), and Vespidae (n = 460). Extensive experiments were conducted using a curated dataset, with model performance evaluated through precision, recall, F1 score, and accuracy. The results demonstrate high accuracy of over 96 % and robust generalization across morphological variations. HiResCAM visualizations confirm that the model focuses on taxonomically relevant anatomical regions, such as wing venation, antennae segmentation, and metasomal structures, thereby validating the biological plausibility of the learned features. The integration of explainable AI techniques improves transparency and trustworthiness, making the system suitable for entomological research to accelerate biodiversity characterization in an under-described parasitoid superfamily.
### Title:
          Semantic One-Dimensional Tokenizer for Image Reconstruction and Generation
 - **Authors:** Yunpeng Qu, Kaidong Zhang, Yukang Ding, Ying Chen, Jian Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual generative models based on latent space have achieved great success, underscoring the significance of visual tokenization. Mapping images to latents boosts efficiency and enables multimodal alignment for scaling up in downstream tasks. Existing visual tokenizers primarily map images into fixed 2D spatial grids and focus on pixel-level restoration, which hinders the capture of representations with compact global semantics. To address these issues, we propose \textbf{SemTok}, a semantic one-dimensional tokenizer that compresses 2D images into 1D discrete tokens with high-level semantics. SemTok sets a new state-of-the-art in image reconstruction, achieving superior fidelity with a remarkably compact token representation. This is achieved via a synergistic framework with three key innovations: a 2D-to-1D tokenization scheme, a semantic alignment constraint, and a two-stage generative training strategy. Building on SemTok, we construct a masked autoregressive generation framework, which yields notable improvements in downstream image generation tasks. Experiments confirm the effectiveness of our semantic 1D tokenization. Our code will be open-sourced.
### Title:
          Deep Reinforcement Learning-Assisted Automated Operator Portfolio for Constrained Multi-objective Optimization
 - **Authors:** Shuai Shao, Ye Tian, Shangshang Yang, Xingyi Zhang
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Constrained multi-objective optimization problems (CMOPs) are of great significance in the context of practical applications, ranging from scientific to engineering domains. Most existing constrained multi-objective evolutionary algorithms (CMOEAs) usually employ fixed operators all the time, which exhibit poor versatility in handling various CMOPs. Therefore, some recent studies have focused on adaptively selecting the best operators for the current population states during the search process. The evolutionary algorithms proposed in these studies learn the value of each operator and recommend the operator with the highest value for the current population, resulting in only a single operator being recommended at each generation, which can potentially lead to local optima and inefficient utilization of function evaluations. To address the dilemma in operator adaptation, this paper proposes a reinforcement learning-based automated operator portfolio approach to learn an allocation scheme of operators at each generation. This approach considers the optimization-related and constraint-related features of the current population as states, the overall improvement in population convergence and diversity as rewards, and different operator portfolios as actions. By utilizing deep neural networks to establish a mapping model between the population states and the expected cumulative rewards, the proposed approach determines the optimal operator portfolio during the evolutionary process. By embedding the proposed approach into existing CMOEAs, a deep reinforcement learning-assisted automated operator portfolio based evolutionary algorithm for solving CMOPs, abbreviated as CMOEA-AOP, is developed. Empirical studies on 33 benchmark problems demonstrate that the proposed algorithm significantly enhances the performance of CMOEAs and exhibits more stable performance across different CMOPs.
### Title:
          Dimensional Type Systems and Deterministic Memory Management: Design-Time Semantic Preservation in Native Compilation
 - **Authors:** Houston Haynes
 - **Subjects:** Subjects:
Programming Languages (cs.PL); Category Theory (math.CT); Logic (math.LO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a compilation framework in which dimensional type annotations persist through multi-stage MLIR lowering, enabling the compiler to jointly resolve numeric representation selection and deterministic memory management as coeffect properties of a single program semantic graph (PSG). Dimensional inference determines value ranges; value ranges determine representation selection; representation selection determines word width and memory footprint; and memory footprint, combined with escape classification, determines allocation strategy and cross-target transfer fidelity. The Dimensional Type System (DTS) extends Hindley-Milner unification with constraints drawn from finitely generated abelian groups, yielding inference that is decidable in polynomial time, complete, and principal. Where conventional systems erase dimensional annotations before code generation, DTS carries them as compilation metadata through each lowering stage, making them available where representation and memory placement decisions occur. Deterministic Memory Management (DMM), formalized as a coeffect discipline within the same graph, unifies escape analysis and memory placement with the dimensional framework. Escape analysis classifies value lifetimes into four categories (stack-scoped, closure-captured, return-escaping, byref-escaping), each mapping to a verified allocation strategy. We identify implications for auto-differentiation: the dimensional algebra is closed under the chain rule, and forward-mode gradient computation exhibits a coeffect signature that the framework can verify. The practical consequence is a development environment where escape diagnostics, allocation strategy, representation fidelity, and cache locality estimation are design-time views over the compilation graph.
### Title:
          Evo-Retriever: LLM-Guided Curriculum Evolution with Viewpoint-Pathway Collaboration for Multimodal Document Retrieval
 - **Authors:** Weiqing Li, Jinyue Guo, Yaqi Wang, Haiyang Xiao, Yuewei Zhang, Guohua Liu, Hao Henry Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual-language models (VLMs) excel at data mappings, but real-world document heterogeneity and unstructuredness disrupt the consistency of cross-modal embeddings. Recent late-interaction methods enhance image-text alignment through multi-vector representations, yet traditional training with limited samples and static strategies cannot adapt to the model's dynamic evolution, causing cross-modal retrieval confusion. To overcome this, we introduce Evo-Retriever, a retrieval framework featuring an LLM-guided curriculum evolution built upon a novel Viewpoint-Pathway collaboration. First, we employ multi-view image alignment to enhance fine-grained matching via multi-scale and multi-directional perspectives. Then, a bidirectional contrastive learning strategy generates "hard queries" and establishes complementary learning paths for visual and textual disambiguation to rebalance supervision. Finally, the model-state summary from the above collaboration is fed into an LLM meta-controller, which adaptively adjusts the training curriculum using expert knowledge to promote the model's evolution. On ViDoRe V2 and MMEB (VisDoc), Evo-Retriever achieves state-of-the-art performance, with nDCG@5 scores of 65.2% and 77.1%.
### Title:
          Unlearning for One-Step Generative Models via Unbalanced Optimal Transport
 - **Authors:** Hyundo Choi, Junhyeong An, Jinseong Park, Jaewoong Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in one-step generative frameworks, such as flow map models, have significantly improved the efficiency of image generation by learning direct noise-to-data mappings in a single forward pass. However, machine unlearning for ensuring the safety of these powerful generators remains entirely unexplored. Existing diffusion unlearning methods are inherently incompatible with these one-step models, as they rely on a multi-step iterative denoising process. In this work, we propose UOT-Unlearn, a novel plug-and-play class unlearning framework for one-step generative models based on the Unbalanced Optimal Transport (UOT). Our method formulates unlearning as a principled trade-off between a forget cost, which suppresses the target class, and an $f$-divergence penalty, which preserves overall generation fidelity via relaxed marginal constraints. By leveraging UOT, our method enables the probability mass of the forgotten class to be smoothly redistributed to the remaining classes, rather than collapsing into low-quality or noise-like samples. Experimental results on CIFAR-10 and ImageNet-256 demonstrate that our framework achieves superior unlearning success (PUL) and retention quality (u-FID), significantly outperforming baselines.
### Title:
          Bridging the Simulation-to-Reality Gap in Electron Microscope Calibration via VAE-EM Estimation
 - **Authors:** Jilles S. van Hulst, W.P.M.H. (Maurice)Heemels, Duarte J. Antunes
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electron microscopy has enabled many scientific breakthroughs across multiple fields. A key challenge is the tuning of microscope parameters based on images to overcome optical aberrations that deteriorate image quality. This calibration problem is challenging due to the high-dimensional and noisy nature of the diagnostic images, and the fact that optimal parameters cannot be identified from a single image. We tackle the calibration problem for Scanning Transmission Electron Microscopes (STEM) by employing variational autoencoders (VAEs), trained on simulated data, to learn low-dimensional representations of images, whereas most existing methods extract only scalar values. We then simultaneously estimate the model that maps calibration parameters to encoded representations and the optimal calibration parameters using an expectation maximization (EM) approach. This joint estimation explicitly addresses the simulation-to-reality gap inherent in data-driven methods that train on simulated data from a digital twin. We leverage the known symmetry property of the optical system to establish global identifiability of the joint estimation problem, ensuring that a unique optimum exists. We demonstrate that our approach is substantially faster and more consistent than existing methods on a real STEM, achieving a 2x reduction in estimation error while requiring fewer observations. This represents a notable advance in automated STEM calibration and demonstrates the potential of VAEs for information compression in images. Beyond microscopy, the VAE-EM framework applies to inverse problems where simulated training data introduces a reality gap and where non-injective mappings would otherwise prevent unique solutions.
### Title:
          Deep Tabular Representation Corrector
 - **Authors:** Hangting Ye, Peng Wang, Wei Fan, Xiaozhuang Song, He Zhao, Dandan Gun, Yi Chang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tabular data have been playing a mostly important role in diverse real-world fields, such as healthcare, engineering, finance, etc. The recent success of deep learning has fostered many deep networks (e.g., Transformer, ResNet) based tabular learning methods. Generally, existing deep tabular machine learning methods are along with the two paradigms, i.e., in-learning and pre-learning. In-learning methods need to train networks from scratch or impose extra constraints to regulate the representations which nonetheless train multiple tasks simultaneously and make learning more difficult, while pre-learning methods design several pretext tasks for pre-training and then conduct task-specific fine-tuning, which however need much extra training effort with prior knowledge. In this paper, we introduce a novel deep Tabular Representation Corrector, TRC, to enhance any trained deep tabular model's representations without altering its parameters in a model-agnostic manner. Specifically, targeting the representation shift and representation redundancy that hinder prediction, we propose two tasks, i.e., (i) Tabular Representation Re-estimation, that involves training a shift estimator to calculate the inherent shift of tabular representations to subsequently mitigate it, thereby re-estimating the representations and (ii) Tabular Space Mapping, that transforms the above re-estimated representations into a light-embedding vector space via a coordinate estimator while preserves crucial predictive information to minimize redundancy. The two tasks jointly enhance the representations of deep tabular models without touching on the original models thus enjoying high efficiency. Finally, we conduct extensive experiments on state-of-the-art deep tabular machine learning models coupled with TRC on various tabular benchmarks which have shown consistent superiority.
### Title:
          Runtime Governance for AI Agents: Policies on Paths
 - **Authors:** Maurits Kaptein, Vassilis-Javed Khan, Andriy Podstavnychy
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI agents -- systems that plan, reason, and act using large language models -- produce non-deterministic, path-dependent behavior that cannot be fully governed at design time, where with governed we mean striking the right balance between as high as possible successful task completion rate and the legal, data-breach, reputational and other costs associated with running agents. We argue that the execution path is the central object for effective runtime governance and formalize compliance policies as deterministic functions mapping agent identity, partial path, proposed next action, and organizational state to a policy violation probability. We show that prompt-level instructions (and "system prompts"), and static access control are special cases of this framework: the former shape the distribution over paths without actually evaluating them; the latter evaluates deterministic policies that ignore the path (i.e., these can only account for a specific subset of all possible paths). In our view, runtime evaluation is the general case, and it is necessary for any path-dependent policy. We develop the formal framework for analyzing AI agent governance, present concrete policy examples (inspired by the AI act), discuss a reference implementation, and identify open problems including risk calibration and the limits of enforced compliance.
### Title:
          Omnilingual SONAR: Cross-Lingual and Cross-Modal Sentence Embeddings Bridging Massively Multilingual Text and Speech
 - **Authors:** Omnilingual SONAR Team: João Maria Janeiro, Pere-Lluís Huguet Cabot, Ioannis Tsiamas, Yen Meng, Vivek Iyer, Guillem Ramírez, Loic Barrault, Belen Alastruey, Yu-An Chung, Marta R. Costa-Jussa, David Dale, Kevin Heffernan, Jaehyeong Jo, Artyom Kozhevnikov, Alexandre Mourachko, Christophe Ropers, Holger Schwenk, Paul-Ambroise Duquenne
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-lingual sentence encoders typically cover only a few hundred languages and often trade downstream quality for stronger alignment, limiting their adoption. We introduce OmniSONAR, a new family of omnilingual, cross-lingual and cross-modal sentence embedding models that natively embed text, speech, code, and mathematical expressions in a single semantic space, while delivering state-of-the-art downstream performance at the scale of thousands of languages, from high-resource to extremely low-resource varieties. To reach this scale without representation collapse, we use progressive training. We first learn a strong foundational space for 200 languages with an LLM-initialized encoder-decoder, combining token-level decoding with a novel split-softmax contrastive loss and synthetic hard negatives. Building on this foundation, we expand to several thousands language varieties via a two-stage teacher-student encoder distillation framework. Finally, we demonstrate the cross-modal extensibility of this space by seamlessly mapping 177 spoken languages into it. OmniSONAR halves cross-lingual similarity search error on the 200-language FLORES dataset and reduces error by a factor of 15 on the 1,560-language BIBLE benchmark. It also enables strong translation, outperforming NLLB-3B on multilingual benchmarks and exceeding prior models (including much larger LLMs) by 15 chrF++ points on 1,560 languages into English BIBLE translation. OmniSONAR also performs strongly on MTEB and XLCoST. For speech, OmniSONAR achieves a 43% lower similarity-search error and reaches 97% of SeamlessM4T speech-to-text quality, despite being zero-shot for translation (trained only on ASR data). Finally, by training an encoder-decoder LM, Spectrum, exclusively on English text processing OmniSONAR embedding sequences, we unlock high-performance transfer to thousands of languages and speech for complex downstream tasks.
### Title:
          SynthChain: A Synthetic Benchmark and Forensic Analysis of Advanced and Stealthy Software Supply Chain Attacks
 - **Authors:** Zhuoran Tan, Wenbo Guo, Taylor Brierley, Jiewen Luo, Jeremy Singer, Christos Anagnostopoulos
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Advanced software supply chain (SSC) attacks are increasingly runtime-only and leave fragmented evidence across hosts, services, and build/dependency layers, so any single telemetry stream is inherently insufficient to reconstruct full compromise chains under realistic access and budget limits. We present SynthChain, a near-production testbed and a multi-source runtime dataset with chain-level ground truth, derived from real-world malicious packages and exploit campaigns. SynthChain covers seven representative supply-chain exploit scenarios across PyPI, npm, and a native C/C++ supply-chain case, spanning Windows and Linux, and involving four hosts and one containerized environment. Scenarios span realistic time windows from minutes to hours and are annotated with 14 MITRE ATT&CK tactics and 161 techniques (29-104 techniques per scenario). Beyond releasing the data, we quantify observability constraints by mapping each chain step to the minimum evidence needed for detection and cross-source correlation. With realistic trace availability, no single source is chain-complete: the best single source reaches only 0.391 weighted tag/step coverage and 0.403 mean chain reconstruction. Even minimal two-source fusion boosts coverage to 0.636 and reconstruction to 0.639 (approximately 1.6x gain), with consistent chain coverage/recall improvements (0.545). The corpus contains approximately 0.58M raw multi-source events and 1.50M evaluation rows, enabling controlled studies of detection under constrained telemetry. We release the dataset, ground truth, and artifacts to support reproducible, forensic-aware runtime defenses and to guide efficient detection for software supply chains.
## Keyword: localization
### Title:
          Attribution-Guided Model Rectification of Unreliable Neural Network Behaviors
 - **Authors:** Peiyu Yang, Naveed Akhtar, Jiantong Jiang, Ajmal Mian
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The performance of neural network models deteriorates due to their unreliable behavior on non-robust features of corrupted samples. Owing to their opaque nature, rectifying models to address this problem often necessitates arduous data cleaning and model retraining, resulting in huge computational and manual overhead. In this work, we leverage rank-one model editing to establish an attribution-guided model rectification framework that effectively locates and corrects model unreliable behaviors. We first distinguish our rectification setting from existing model editing, yielding a formulation that corrects unreliable behavior while preserving model performance and reducing reliance on large budgets of cleansed samples. We further reveal a bottleneck of model rectifying arising from heterogeneous editability across layers. To target the primary source of misbehavior, we introduce an attribution-guided layer localization method that quantifies layer-wise editability and identifies the layer most responsible for unreliabilities. Extensive experiments demonstrate the effectiveness of our method in correcting unreliabilities observed for neural Trojans, spurious correlations and feature leakage. Our method shows remarkable performance by achieving its editing objective with as few as a single cleansed sample, which makes it appealing for practice.
### Title:
          Grounding the Score: Explicit Visual Premise Verification for Reliable Vision-Language Process Reward Models
 - **Authors:** Junxin Wang, Dai Guan, Weijie Qiu, Zhihang Li, Yongbo Gai, Zhengyi Yang, Mengyu Zhou, Erchao Zhao, Xiaoxi Jiang, Guanjun Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language process reward models (VL-PRMs) are increasingly used to score intermediate reasoning steps and rerank candidates under test-time scaling. However, they often function as black-box judges: a low step score may reflect a genuine reasoning mistake or simply the verifier's misperception of the image. This entanglement between perception and reasoning leads to systematic false positives (rewarding hallucinated visual premises) and false negatives (penalizing correct grounded statements), undermining both reranking and error localization. We introduce Explicit Visual Premise Verification (EVPV), a lightweight verification interface that conditions step scoring on the reliability of the visual premises a step depends on. The policy is prompted to produce a step-wise visual checklist that makes required visual facts explicit, while a constraint extractor independently derives structured visual constraints from the input image. EVPV matches checklist claims against these constraints to compute a scalar visual reliability signal, and calibrates PRM step rewards via reliability gating: rewards for visually dependent steps are attenuated when reliability is low and preserved when reliability is high. This decouples perceptual uncertainty from logical evaluation without per-step tool calls. Experiments on VisualProcessBench and six multimodal reasoning benchmarks show that EVPV improves step-level verification and consistently boosts Best-of-N reranking accuracy over strong baselines. Furthermore, injecting controlled corruption into the extracted constraints produces monotonic performance degradation, providing causal evidence that the gains arise from constraint fidelity and explicit premise verification rather than incidental prompt effects. Code is available at: this https URL
### Title:
          Point-to-Mask: From Arbitrary Point Annotations to Mask-Level Infrared Small Target Detection
 - **Authors:** Weihua Gao, Wenlong Niu, Jie Tang, Man Yang, Jiafeng Zhang, Xiaodong Peng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Infrared small target detection (IRSTD) methods predominantly formulate the task as pixel-level segmentation, which requires costly dense annotations and is not well suited to tiny targets with weak texture and ambiguous boundaries. To address this issue, we propose Point-to-Mask, a framework that bridges low-cost point supervision and mask-level detection through two components: a Physics-driven Adaptive Mask Generation (PAMG) module that converts point annotations into compact target masks and geometric cues, and a lightweight Radius-aware Point Regression Network (RPR-Net) that reformulates IRSTD as target center localization and effective radius regression using spatiotemporal motion cues. The two modules form a closed loop: PAMG generates pseudo masks and geometric supervision during training, while the geometric predictions of RPR-Net are fed back to PAMG for pixel-level mask recovery during inference. To facilitate systematic evaluation, we further construct SIRSTD-Pixel, a sequential dataset with refined pixel-level annotations. Experiments show that the proposed framework achieves strong pseudo-label quality, high detection accuracy, and efficient inference, approaching full-supervision performance under point-supervised settings with substantially lower annotation cost. Code and datasets will be available at: this https URL.
### Title:
          GenZ-LIO: Generalizable LiDAR-Inertial Odometry Beyond Indoor--Outdoor Boundaries
 - **Authors:** Daehan Lee, Hyungtae Lim, Seongjun Kim, Soonbin Rho, Changhyeon Lee, Sanghyun Park, Junwoo Hong, Eunseon Choi, Hyunyoung Jo, Soohee Han
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Light detection and ranging (LiDAR)-inertial odometry (LIO) enables accurate localization and mapping for autonomous navigation in various scenes. However, its performance remains sensitive to variations in spatial scale, which refers to the spatial extent of the scene reflected in the distribution of point ranges in a LiDAR scan. Transitions between confined indoor and expansive outdoor spaces induce substantial variations in point density, which may reduce robustness and computational efficiency. To address this issue, we propose GenZ-LIO, a LIO framework generalizable across both indoor and outdoor environments. GenZ-LIO comprises three key components. First, inspired by the principle of the proportional-integral-derivative (PID) controller, it adaptively regulates the voxel size for downsampling via feedback control, driving the voxelized point count toward a scale-informed setpoint while enabling stable and efficient processing across varying scene scales. Second, we formulate a hybrid-metric state update that jointly leverages point-to-plane and point-to-point residuals to mitigate LiDAR degeneracy arising from directionally insufficient geometric constraints. Third, to alleviate the computational burden introduced by point-to-point matching, we introduce a voxel-pruned correspondence search strategy that discards non-promising voxel candidates and reduces unnecessary computations. Experimental results demonstrate that GenZ-LIO achieves robust odometry estimation and improved computational efficiency across confined indoor, open outdoor, and transitional environments. Our code will be made publicly available upon publication.
### Title:
          Rethinking Pose Refinement in 3D Gaussian Splatting under Pose Prior and Geometric Uncertainty
 - **Authors:** Mangyu Kong, Jaewon Lee, Seongwon Lee, Euntai Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has recently emerged as a powerful scene representation and is increasingly used for visual localization and pose refinement. However, despite its high-quality differentiable rendering, the robustness of 3DGS-based pose refinement remains highly sensitive to both the initial camera pose and the reconstructed geometry. In this work, we take a closer look at these limitations and identify two major sources of uncertainty: (i) pose prior uncertainty, which often arises from regression or retrieval models that output a single deterministic estimate, and (ii) geometric uncertainty, caused by imperfections in the 3DGS reconstruction that propagate errors into PnP solvers. Such uncertainties can distort reprojection geometry and destabilize optimization, even when the rendered appearance still looks plausible. To address these uncertainties, we introduce a relocalization framework that combines Monte Carlo pose sampling with Fisher Information-based PnP optimization. Our method explicitly accounts for both pose and geometric uncertainty and requires no retraining or additional supervision. Across diverse indoor and outdoor benchmarks, our approach consistently improves localization accuracy and significantly increases stability under pose and depth noise.
## Keyword: transformer
### Title:
          Tokenization Tradeoffs in Structured EHR Foundation Models
 - **Authors:** Lin Lawrence Guo, Santiago Eduardo Arciniegas, Joseph Jihyung Lee, Adam Paul Yan, George Tomlinson, Jason Fries, Lillian Sung
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation models for structured electronic health records (EHRs) are pretrained on longitudinal sequences of timestamped clinical events to learn adaptable patient representations. Tokenization -- how these timelines are converted into discrete model inputs -- determines what information is preserved, how efficiently it is encoded, and which relationships must be learned versus precomputed. Yet the impact of tokenization design choices on downstream performance and computational efficiency remains largely unexplored. Here, we pretrained a transformer on pediatric EHR data under a factorial design, varying tokenization along event encoding, time encoding, and workflow annotation. We evaluated area-under-the-receiver-operating-characteristic curve across 74 clinical prediction tasks. Joint event encoding and positional time encoding outperformed their alternatives (73/74 and 71/74 tasks) while requiring 39.5% and 9.6% fewer pretraining floating-point operations, respectively. Targeted ablations traced the joint encoding advantage to local binding efficiency, that is, code-attribute pairs are combined into single tokens, rather than split across tokens that the model must learn to associate during pretraining. External evaluation on an adult intensive care unit cohort demonstrated that this advantage generalizes despite substantial vocabulary mismatch, while temporal and workflow effects remain institution-specific. These results establish tokenization as a tractable lever for improving both the performance and efficiency of EHR foundation models.
### Title:
          XLinear: Frequency-Enhanced MLP with CrossFilter for Robust Long-Range Forecasting
 - **Authors:** Xiang Ao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time series forecasters are widely used across various domains. Among them, MLP (multi-layer perceptron)-based forecasters have been proven to be more robust to noise compared to Transformer-based forecasters. However, MLP struggles to capture complex features, resulting in limitations on capturing long-range dependencies. To address this challenge, we propose XLinear, an MLP-based forecaster for long-range forecasting. Firstly, we decompose the time series into trend and seasonal components. For the trend component which contains long-range characteristics, we design Enhanced Frequency Attention (EFA) to capture long-term dependencies by leveraging frequency-domain operations. Additionally, a CrossFilter Block is proposed for the seasonal component to maintain the model's robustness to noise, avoiding the problems of low robustness often caused by attention mechanisms. Experimental results demonstrate that XLinear achieves state-of-the-art performance on test datasets. While keeping the lightweight architecture and high robustness of MLP-based models, our forecaster outperforms other MLP-based forecasters in capturing long-range dependencies.
### Title:
          A federated learning framework with knowledge graph and temporal transformer for early sepsis prediction in multi-center ICUs
 - **Authors:** Yue Chang, Guangsen Lin, Jyun Jie Chuang, Shunqi Liu, Xinkui Li, Yaozheng Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The early prediction of sepsis in intensive care unit (ICU) patients is crucial for improving survival rates. However, the development of accurate predictive models is hampered by data fragmentation across healthcare institutions and the complex, temporal nature of medical data, all under stringent privacy constraints. To address these challenges, we propose a novel framework that uniquely integrates federated learning (FL) with a medical knowledge graph and a temporal transformer model, enhanced by meta-learning capabilities. Our approach enables collaborative model training across multiple hospitals without sharing raw patient data, thereby preserving privacy. The model leverages a knowledge graph to incorporate structured medical relationships and employs a temporal transformer to capture long-range dependencies in clinical time-series data. A model-agnostic meta-learning (MAML) strategy is further incorporated to facilitate rapid adaptation of the global model to local data distributions. Evaluated on the MIMIC-IV and eICU datasets, our method achieves an area under the curve (AUC) of 0.956, which represents a 22.4% improvement over conventional centralized models and a 12.7% improvement over standard federated learning, demonstrating strong predictive capability for sepsis. This work presents a reliable and privacy-preserving solution for multi-center collaborative early warning of sepsis.
### Title:
          QV May Be Enough: Toward the Essence of Attention in LLMs
 - **Authors:** Zhang Edward
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Starting from first principles and a linguistic perspective centered on part-of-speech (POS) and syntactic analysis, this paper explores and derives the underlying essence of the Query-Key-Value (QKV) mechanism within the Transformer architecture. Based on this theoretical foundation, we provide a unified explanatory framework for the efficacy of contemporary architectures, including MQA, GQA, and MLA, while identifying their inherent trade-offs and potential optimization trajectories. We introduce the QV paradigm and provide empirical evidence for its validity. Building upon this, we propose the QV-Ka optimization scheme, which is further substantiated through experimental validation. The interpretable theoretical analysis of the QKV mechanism presented in this work establishes a robust foundation for the future evolution of large language model architectures.
### Title:
          Spectral Edge Dynamics of Training Trajectories: Signal--Noise Geometry Across Scales
 - **Authors:** Yongzhong Xu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite hundreds of millions of parameters, transformer training trajectories evolve within only a few coherent directions. We introduce \emph{Spectral Edge Dynamics} (SED) to measure this structure: rolling-window SVD of parameter updates reveals a sharp boundary -- the \emph{spectral edge} -- between coherent optimization directions and stochastic noise, identified by the maximum consecutive singular value ratio $\sigma_k/\sigma_{k+1}$. Across a 51M-parameter TinyStories model (4~seeds) and GPT-2 124M under a distribution shift, the spectral edge exhibits a universal three-phase pattern (rise, plateau, collapse), signal rank adjusts with task complexity ($k^* = 2$ at 51M, $k^* = 3$ at 124M), and the directional coupling between spectral geometry and validation loss reverses with window size -- a \emph{lag flip} reflecting the timescale of trajectory integration. Johnson--Lindenstrauss projection to $d = 10W$ dimensions (e.g., $d = 100$ for $W = 10$) preserves the spectral gap within 5.7\%, making the framework applicable to models of arbitrary size. In companion work, the same spectral geometry provides early-warning signals of grokking -- predicting generalization 600--1{,}700 steps before it occurs across modular arithmetic, Dyck languages, and the SCAN benchmark.
### Title:
          Feed-forward Gaussian Registration for Head Avatar Creation and Editing
 - **Authors:** Malte Prinzler, Paulo Gotardo, Siyu Tang, Timo Bolkart
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present MATCH (Multi-view Avatars from Topologically Corresponding Heads), a multi-view Gaussian registration method for high-quality head avatar creation and editing. State-of-the-art multi-view head avatar methods require time-consuming head tracking followed by expensive avatar optimization, often resulting in a total creation time of more than one day. MATCH, in contrast, directly predicts Gaussian splat textures in correspondence from calibrated multi-view images in just 0.5 seconds per frame, without requiring data preprocessing. The learned intra-subject correspondence across frames enables fast creation of personalized head avatars, while correspondence across subjects supports applications such as expression transfer, optimization-free tracking, semantic editing, and identity interpolation. We establish these correspondences end-to-end using a transformer-based model that predicts Gaussian splat textures in the fixed UV layout of a template mesh. To achieve this, we introduce a novel registration-guided attention block, where each UV-map token attends exclusively to image tokens depicting its corresponding mesh region. This design improves efficiency and performance compared to dense cross-view attention. MATCH outperforms existing methods in novel-view synthesis, geometry registration, and head avatar generation, while making avatar creation 10 times faster than the closest competing baseline. The code and model weights are available on the project website.
### Title:
          Self-Admitted Technical Debt in Scientific Software: Prioritization, Sentiment, and Propagation Across Artifacts
 - **Authors:** Eric L. Melin, Nasir U. Eisty, Gregory R. Watson, Addi Malviya-Thakur
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-admitted technical debt (SATD) impairs scientific software (SSW), yet its prioritization, sentiment, persistence, and propagation remains underexplored. Understanding how SSW developers express, and address SATD is crucial for improving SSW maintenance, and tooling. This study investigates how SATD types and artifacts in SSW are prioritized, how sentiment relates to urgency, SATD removal and resolution rates, and the extent to which SATD propagates across artifacts. We analyzed nine SSW repositories using a SATD classification model and a semantic embedding-based prioritization heuristic. SATD was examined across multiple artifacts, with sentiment assessed via a fine-tuned transformer. Propagation was traced, priority scores compared to static analysis, and removal and resolution rates quantified. SATD in comments, commits, and pull requests receive higher priority than SATD in issues, with negative sentiment amplifying urgency. Resolution and removal rates lag behind open-source software (OSS) averages. Most SATD remains confined to the originating artifact, but longer propagation chains are rare and correlate with higher priority, highlighting persistent and high impact debt. Prioritization is influenced by artifact type and sentiment, while low removal and resolution rates signal persistent debt. Cross-artifact propagation marks high priority, unresolved SATD, providing empirical guidance for targeted monitoring, review prioritization, and tool supported maintenance in SSW.
### Title:
          PhasorFlow: A Python Library for Unit Circle Based Computing
 - **Authors:** Dibakar Sigdel, Namuna Panday
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present PhasorFlow, an open-source Python library introducing a computational paradigm operating on the $S^1$ unit circle. Inputs are encoded as complex phasors $z = e^{i\theta}$ on the $N$-Torus ($\mathbb{T}^N$). As computation proceeds via unitary wave interference gates, global norm is preserved while individual components drift into $\mathbb{C}^N$, allowing algorithms to natively leverage continuous geometric gradients for predictive learning. PhasorFlow provides three core contributions. First, we formalize the Phasor Circuit model ($N$ unit circle threads, $M$ gates) and introduce a 22-gate library covering Standard Unitary, Non-Linear, Neuromorphic, and Encoding operations with full matrix algebra simulation. Second, we present the Variational Phasor Circuit (VPC), analogous to Variational Quantum Circuits (VQC), enabling optimization of continuous phase parameters for classical machine learning tasks. Third, we introduce the Phasor Transformer, replacing expensive $QK^TV$ attention with a parameter-free, DFT-based token mixing layer inspired by FNet. We validate PhasorFlow on non-linear spatial classification, time-series prediction, financial volatility detection, and neuromorphic tasks including neural binding and oscillatory associative memory. Our results establish unit circle computing as a deterministic, lightweight, and mathematically principled alternative to classical neural networks and quantum circuits. It operates on classical hardware while sharing quantum mechanics' unitary foundations. PhasorFlow is available at this https URL.
### Title:
          Sparse but not Simpler: A Multi-Level Interpretability Analysis of Vision Transformers
 - **Authors:** Siyu Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse neural networks are often hypothesized to be more interpretable than dense models, motivated by findings that weight sparsity can produce compact circuits in language models. However, it remains unclear whether structural sparsity itself leads to improved semantic interpretability. In this work, we systematically evaluate the relationship between weight sparsity and interpretability in Vision Transformers using DeiT-III B/16 models pruned with Wanda. To assess interpretability comprehensively, we introduce \textbf{IMPACT}, a multi-level framework that evaluates interpretability across four complementary levels: neurons, layer representations, task circuits, and model-level attribution. Layer representations are analyzed using BatchTopK sparse autoencoders, circuits are extracted via learnable node masking, and explanations are evaluated with transformer attribution using insertion and deletion metrics. Our results reveal a clear structural effect but limited interpretability gains. Sparse models produce circuits with approximately $2.5\times$ fewer edges than dense models, yet the fraction of active nodes remains similar or higher, indicating that pruning redistributes computation rather than isolating simpler functional modules. Consistent with this observation, sparse models show no systematic improvements in neuron-level selectivity, SAE feature interpretability, or attribution faithfulness. These findings suggest that structural sparsity alone does not reliably yield more interpretable vision models, highlighting the importance of evaluation frameworks that assess interpretability beyond circuit compactness.
### Title:
          Do Not Leave a Gap: Hallucination-Free Object Concealment in Vision-Language Models
 - **Authors:** Amira Guesmi, Muhammad Shafique
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models (VLMs) have recently shown remarkable capabilities in visual understanding and generation, but remain vulnerable to adversarial manipulations of visual content. Prior object-hiding attacks primarily rely on suppressing or blocking region-specific representations, often creating semantic gaps that inadvertently induce hallucination, where models invent plausible but incorrect objects. In this work, we demonstrate that hallucination arises not from object absence per se, but from semantic discontinuity introduced by such suppression-based attacks. We propose a new class of \emph{background-consistent object concealment} attacks, which hide target objects by re-encoding their visual representations to be statistically and semantically consistent with surrounding background regions. Crucially, our approach preserves token structure and attention flow, avoiding representational voids that trigger hallucination. We present a pixel-level optimization framework that enforces background-consistent re-encoding across multiple transformer layers while preserving global scene semantics. Extensive experiments on state-of-the-art vision-language models show that our method effectively conceals target objects while preserving up to $86\%$ of non-target objects and reducing grounded hallucination by up to $3\times$ compared to attention-suppression-based attacks.
### Title:
          Towards Fair and Robust Volumetric CT Classification via KL-Regularised Group Distributionally Robust Optimisation
 - **Authors:** Samuel Johnny, Blessed Guda, Frank Ebeledike, Goodness Obasi, Moise Busogi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated diagnosis from chest computed tomography (CT) scans faces two persistent challenges in clinical deployment: distribution shift across acquisition sites and performance disparity across demographic subgroups. We address both simultaneously across two complementary tasks: binary COVID-19 classification from multi-site CT volumes (Task 1) and four-class lung pathology recognition with gender-based fairness constraints (Task 2). Our framework combines a lightweight MobileViT-XXS slice encoder with a two-layer SliceTransformer aggregator for volumetric reasoning, and trains with a KL-regularised Group Distributionally Robust Optimisation (Group DRO) objective that adaptively upweights underperforming acquisition centres and demographic subgroups. Unlike standard Group DRO, the KL penalty prevents group weight collapse, providing a stable balance between worst-case protection and average performance. For Task 2, we define groups at the granularity of gender class, directly targeting severely underrepresented combinations such as female Squamous cell carcinoma. On Task 1, our best configuration achieves a challenge F1 of 0.835, surpassing the best published challenge entry by +5.9. On Task 2, Group DRO with {\alpha} = 0.5 achieves a mean per-gender macro F1 of 0.815, outperforming the best challenge entry by +11.1 pp and improving Female Squamous F1 by +17.4 over the Fo- cal Loss baseline.
### Title:
          A Family of LLMs Liberated from Static Vocabularies
 - **Authors:** Aleph Alpha: Adnen Abdessaied, Artur Baranowski, Lukas Balles, Michael Barlow, Fabien C. Y. Benureau, Felix Berkenkamp, Lukas Bluebaum, Bastian Boll, Thomas F. Burns, Björn Deiseroth, Constantin Eichenberg, David Friede, Pablo Iyu Guerrero, Ahmed Hammam, Bastian Harren, Johann Higl, Yasser Jadidi, Carina Kauf, Johannes Messner, Jan Hendrik Metzen, Max Meuer, Vedant Nanda, Pit Neitemeier, Koen Oostermeijer, Letitia Parcalabescu, Markus Pernpointner, Felix Reinfurt, Dylan Rodriquez, Grégory Schott, Philipp Siedler, Martin Simonovsky, Till Speicher, Volker Stampa, Stephan Wäldchen, Samuel Weinbach, Gregor Ziegltrum
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tokenization is a central component of natural language processing in current large language models (LLMs), enabling models to convert raw text into processable units. Although learned tokenizers are widely adopted, they exhibit notable limitations, including their large, fixed vocabulary sizes and poor adaptability to new domains or languages. We present a family of models with up to 70 billion parameters based on the hierarchical autoregressive transformer (HAT) architecture. In HAT, an encoder transformer aggregates bytes into word embeddings and then feeds them to the backbone, a classical autoregressive transformer. The outputs of the backbone are then cross-attended by the decoder and converted back into bytes. We show that we can reuse available pre-trained models by converting the Llama 3.1 8B and 70B models into the HAT architecture: Llama-3.1-8B-TFree-HAT and Llama-3.1-70B-TFree-HAT are byte-level models whose encoder and decoder are trained from scratch, but where we adapt the pre-trained Llama backbone, i.e., the transformer blocks with the embedding matrix and head removed, to handle word embeddings instead of the original tokens. We also provide a 7B HAT model, Llama-TFree-HAT-Pretrained, trained entirely from scratch on nearly 4 trillion words. The HAT architecture improves text compression by reducing the number of required sequence positions and enhances robustness to intra-word variations, e.g., spelling differences. Through pre-training, as well as subsequent supervised fine-tuning and direct preference optimization in English and German, we show strong proficiency in both languages, improving on the original Llama 3.1 in most benchmarks. We release our models (including 200 pre-training checkpoints) on Hugging Face.
### Title:
          W2T: LoRA Weights Already Know What They Can Do
 - **Authors:** Xiaolong Han, Ferrante Neri, Zijian Jiang, Fang Wu, Yanfang Ye, Lu Yin, Zehong Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Each LoRA checkpoint compactly stores task-specific updates in low-rank weight matrices, offering an efficient way to adapt large language models to new tasks and domains. In principle, these weights already encode what the adapter does and how well it performs. In this paper, we ask whether this information can be read directly from the weights, without running the base model or accessing training data. A key obstacle is that a single LoRA update can be factorized in infinitely many ways. Without resolving this ambiguity, models trained on the factors may fit the particular factorization rather than the underlying update. To this end, we propose \methodfull, which maps each LoRA update to a provably canonical form via QR decomposition followed by SVD, so that all equivalent factorizations share the same representation. The resulting components are then tokenized and processed by a Transformer to produce a weight-space embedding. Across language and vision LoRA collections, W2T achieves strong results on attribute classification, performance prediction, and adapter retrieval, demonstrating that LoRA weights reliably indicate model behavior once factorization ambiguity is removed. Code is available at this https URL.
### Title:
          Residual Stream Duality in Modern Transformer Architectures
 - **Authors:** Yifan Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent work has made clear that the residual pathway is not mere optimization plumbing; it is part of the model's representational machinery. We agree, but argue that the cleanest way to organize this design space is through a two-axis view of the Transformer. A decoder evolves information along two ordered dimensions: sequence position and layer depth. Self-attention already provides adaptive mixing along the sequence axis, whereas the residual stream usually performs fixed addition along the depth axis. If we fix a token position and treat layer index as the ordered variable, then a causal depth-wise residual attention read is exactly the same local operator as causal short sliding-window attention (ShortSWA), except written over depth rather than over sequence. This is the core residual stream duality behind Transformer$^2$. This perspective also clarifies the recent literature. ELC-BERT and DenseFormer already show that learned aggregation over depth can outperform uniform residual accumulation, while Vertical Attention, DeepCrossAttention (DCA), MUDDFormer, and Attention Residuals move further toward explicit attention-based routing over earlier layers. The key point, however, is that operator-level duality does not imply systems-level symmetry. For large-scale autoregressive models, sequence-axis ShortSWA is usually the more hardware-friendly placement because it reuses token-side sliding-window kernels, KV-cache layouts, and chunked execution. If the goal is instead to change the shortcut itself, Deep Delta Learning (DDL) is the cleaner intervention because it modifies the residual operator directly rather than adding a separate cross-layer retrieval path. Our recommendation is therefore simple: use DDL when the shortcut is the object of interest, and use sequence-axis ShortSWA when the goal is local adaptive mixing.
### Title:
          Collaborative Temporal Feature Generation via Critic-Free Reinforcement Learning for Cross-User Sensor-Based Activity Recognition
 - **Authors:** Xiaozhou Ye, Feng Jiang, Zihan Wang, Xiulai Wang, Yutao Zhang, Kevin I-Kai Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human Activity Recognition using wearable inertial sensors is foundational to healthcare monitoring, fitness analytics, and context-aware computing, yet its deployment is hindered by cross-user variability arising from heterogeneous physiological traits, motor habits, and sensor placements. Existing domain generalization approaches either neglect temporal dependencies in sensor streams or depend on impractical target-domain annotations. We propose a different paradigm: modeling generalizable feature extraction as a collaborative sequential generation process governed by reinforcement learning. Our framework, CTFG (Collaborative Temporal Feature Generation), employs a Transformer-based autoregressive generator that incrementally constructs feature token sequences, each conditioned on prior context and the encoded sensor input. The generator is optimized via Group-Relative Policy Optimization, a critic-free algorithm that evaluates each generated sequence against a cohort of alternatives sampled from the same input, deriving advantages through intra-group normalization rather than learned value estimation. This design eliminates the distribution-dependent bias inherent in critic-based methods and provides self-calibrating optimization signals that remain stable across heterogeneous user distributions. A tri-objective reward comprising class discrimination, cross-user invariance, and temporal fidelity jointly shapes the feature space to separate activities, align user distributions, and preserve fine-grained temporal content. Evaluations on the DSADS and PAMAP2 benchmarks demonstrate state-of-the-art cross-user accuracy (88.53\% and 75.22\%), substantial reduction in inter-task training variance, accelerated convergence, and robust generalization under varying action-space dimensionalities.
### Title:
          ViT-AdaLA: Adapting Vision Transformers with Linear Attention
 - **Authors:** Yifan Li, Seunghyun Yoon, Viet Dac Lai, Franck Dernoncourt, Jason Kuen, Yu Kong, Trung Bui
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) based vision foundation models (VFMs) have achieved remarkable performance across diverse vision tasks, but suffer from quadratic complexity that limits scalability to long sequences. Existing linear attention approaches for ViTs are typically trained from scratch, requiring substantial computational resources, while linearization-based methods developed for large language model decoders do not transfer well to ViTs. To address these challenges, we propose ViT-AdaLA, a novel framework for effectively adapting and transferring prior knowledge from VFMs to linear attention ViTs. ViT-AdaLA consists of three stages: attention alignment, feature alignment, and supervised fine-tuning. In the attention alignment stage, we align vanilla linear attention with the original softmax-based attention in each block to approximate the behavior of softmax attention. However, residual approximation errors inevitably accumulate across layers. We mitigate this by fine-tuning the linearized ViT to align its final-layer features with a frozen softmax VFM teacher. Finally, the adapted prior knowledge is transferred to downstream tasks through supervised fine-tuning. Extensive experiments on classification and segmentation tasks demonstrate the effectiveness and generality of ViT-AdaLA over various state-of-the-art linear attention counterpart.
### Title:
          Parallel In-context Learning for Large Vision Language Models
 - **Authors:** Shin'ya Yamaguchi, Daiki Chijiwa, Tamao Sakao, Taku Hasegawa
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large vision-language models (LVLMs) employ multi-modal in-context learning (MM-ICL) to adapt to new tasks by leveraging demonstration examples. While increasing the number of demonstrations boosts performance, they incur significant inference latency due to the quadratic computational cost of Transformer attention with respect to the context length. To address this trade-off, we propose Parallel In-Context Learning (Parallel-ICL), a plug-and-play inference algorithm. Parallel-ICL partitions the long demonstration context into multiple shorter, manageable chunks. It processes these chunks in parallel and integrates their predictions at the logit level, using a weighted Product-of-Experts (PoE) ensemble to approximate the full-context output. Guided by ensemble learning theory, we introduce principled strategies for Parallel-ICL: (i) clustering-based context chunking to maximize inter-chunk diversity and (ii) similarity-based context compilation to weight predictions by query relevance. Extensive experiments on VQA, image captioning, and classification benchmarks demonstrate that Parallel-ICL achieves performance comparable to full-context MM-ICL, while significantly improving inference speed. Our work offers an effective solution to the accuracy-efficiency trade-off in MM-ICL, enabling dynamic task adaptation with substantially reduced inference overhead.
### Title:
          NeuronSpark: A Spiking Neural Network Language Model with Selective State Space Dynamics
 - **Authors:** Zhengzheng Tang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We ask whether a pure spiking backbone can learn large-scale language modeling from random initialization, without Transformer distillation. We introduce NeuronSpark, a 0.9B-parameter SNN language model trained with next-token prediction and surrogate gradients. The model combines selective state-space spiking dynamics, leakage-current inter-layer communication, PonderNet adaptive timesteps, fused Triton PLIF kernels, and stabilization techniques (residual centering, lateral-inhibition normalization, and natural-gradient compensation). Under a constrained budget (about 1.4B pretraining tokens and 6.5K SFT steps), NeuronSpark-0.9B reaches 3.6 pretraining loss and shows early multi-turn dialogue behavior after SFT. These results support the feasibility of end-to-end language modeling with a pure SNN architecture at this scale.
### Title:
          GATS: Gaussian Aware Temporal Scaling Transformer for Invariant 4D Spatio-Temporal Point Cloud Representation
 - **Authors:** Jiayi Tian, Jiaze Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding 4D point cloud videos is essential for enabling intelligent agents to perceive dynamic environments. However, temporal scale bias across varying frame rates and distributional uncertainty in irregular point clouds make it highly challenging to design a unified and robust 4D backbone. Existing CNN or Transformer based methods are constrained either by limited receptive fields or by quadratic computational complexity, while neglecting these implicit distortions. To address this problem, we propose a novel dual invariant framework, termed \textbf{Gaussian Aware Temporal Scaling (GATS)}, which explicitly resolves both distributional inconsistencies and temporal. The proposed \emph{Uncertainty Guided Gaussian Convolution (UGGC)} incorporates local Gaussian statistics and uncertainty aware gating into point convolution, thereby achieving robust neighborhood aggregation under density variation, noise, and occlusion. In parallel, the \emph{Temporal Scaling Attention (TSA)} introduces a learnable scaling factor to normalize temporal distances, ensuring frame partition invariance and consistent velocity estimation across different frame rates. These two modules are complementary: temporal scaling normalizes time intervals prior to Gaussian estimation, while Gaussian modeling enhances robustness to irregular distributions. Our experiments on mainstream benchmarks MSR-Action3D (\textbf{+6.62\%} accuracy), NTU RGBD (\textbf{+1.4\%} accuracy), and Synthia4D (\textbf{+1.8\%} mIoU) demonstrate significant performance gains, offering a more efficient and principled paradigm for invariant 4D point cloud video understanding with superior accuracy, robustness, and scalability compared to Transformer based counterparts.
### Title:
          SignNav: Leveraging Signage for Semantic Visual Navigation in Large-Scale Indoor Environments
 - **Authors:** Jian Sun, Yuming Huang, He Li, Shuqi Xiao, Shenyan Guo, Maani Ghaffari, Qingbiao Li, Chengzhong Xu, Hui Kong
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humans routinely leverage semantic hints provided by signage to navigate to destinations within novel Large-Scale Indoor (LSI) environments, such as hospitals and airport terminals. However, this capability remains underexplored within the field of embodied navigation. This paper introduces a novel embodied navigation task, SignNav, which requires the agent to interpret semantic hint from signage and reason about the subsequent action based on current observation. To facilitate research in this domain, we construct the LSI-Dataset for the training and evaluation of various SignNav agents. Dynamically changing semantic hints and sparse placement of signage in LSI environments present significant challenges to the SignNav task. To address these challenges, we propose the Spatial-Temporal Aware Transformer (START) model for end-to-end decision-making. The spatial-aware module grounds the semantic hint of signage into physical world, while the temporal-aware module captures long-range dependencies between historical states and current observation. Leveraging a two-stage training strategy with Dataset Aggregation (DAgger), our approach achieves state-of-the-art performance, recording an 80% Success Rate (SR) and 0.74 NDTW on val-unseen split. Real-world deployment further demonstrates the practicality of our method in physical environment without pre-built map.
### Title:
          KidsNanny: A Two-Stage Multimodal Content Moderation Pipeline Integrating Visual Classification, Object Detection, OCR, and Contextual Reasoning for Child Safety
 - **Authors:** Viraj Panchal, Tanmay Talsaniya, Parag Patel, Meet Patel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present KidsNanny, a two-stage multimodal content moderation architecture for child safety. Stage 1 combines a vision transformer (ViT) with an object detector for visual screening (11.7 ms); outputs are routed as text not raw pixels to Stage 2, which applies OCR and a text based 7B language model for contextual reasoning (120 ms total pipeline). We evaluate on the UnsafeBench Sexual category (1,054 images) under two regimes: vision-only, isolating Stage 1, and multimodal, evaluating the full Stage 1+2 pipeline. Stage 1 achieves 80.27% accuracy and 85.39% F1 at 11.7 ms; vision-only baselines range from 59.01% to 77.04% accuracy. The full pipeline achieves 81.40% accuracy and 86.16% F1 at 120 ms, compared to ShieldGemma-2 (64.80% accuracy, 1,136 ms) and LlavaGuard (80.36% accuracy, 4,138 ms). To evaluate text-awareness, we filter two subsets: a text+visual subset (257 images) and a text-only subset (44 images where safety depends primarily on embedded text). On text-only images, KidsNanny achieves 100% recall (25/25 positives; small sample) and 75.76% precision; ShieldGemma-2 achieves 84% recall and 60% precision at 1,136 ms. Results suggest that dedicated OCR-based reasoning may offer recall-precision advantages on text-embedded threats at lower latency, though the small text-only subset limits generalizability. By documenting this architecture and evaluation methodology, we aim to contribute to the broader research effort on efficient multimodal content moderation for child safety.
### Title:
          PanguMotion: Continuous Driving Motion Forecasting with Pangu Transformers
 - **Authors:** Quanhao Ren, Yicheng Li, Nan Song
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Motion forecasting is a core task in autonomous driving systems, aiming to accurately predict the future trajectories of surrounding agents to ensure driving safety. Existing methods typically process discrete driving scenes independently, neglecting the temporal continuity and historical context correlations inherent in real-world driving environments. This paper proposes PanguMotion, a motion forecasting framework for continuous driving scenarios that integrates Transformer blocks from the Pangu-1B large language model as feature enhancement modules into autonomous driving motion prediction architectures. We conduct experiments on the Argoverse 2 datasets processed by the RealMotion data reorganization strategy, transforming each independent scene into a continuous sequence to mimic real-world driving scenarios.
### Title:
          Synergizing Deep Learning and Biological Heuristics for Extreme Long-Tail White Blood Cell Classification
 - **Authors:** Trong-Duc Nguyen, Hoang-Long Nguyen, Huy-Hieu Pham
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated white blood cell (WBC) classification is essential for leukemia screening but remains challenged by extreme class imbalance, long-tail distributions, and domain shift, leading deep models to overfit dominant classes and fail on rare subtypes. We propose a hybrid framework for rare-class generalization that integrates a generative Pix2Pix-based restoration module for artifact removal, a Swin Transformer ensemble with MedSigLIP contrastive embeddings for robust representation learning, and a biologically-inspired refinement step using geometric spikiness and Mahalanobis-based morphological constraints to recover out-of-distribution predictions. Evaluated on the WBCBench 2026 challenge, our method achieves a Macro-F1 of 0.77139 on the private leaderboard, demonstrating strong performance under severe imbalance and highlighting the value of incorporating biological priors into deep learning for hematological image analysis.
### Title:
          DriveFix: Spatio-Temporally Coherent Driving Scene Restoration
 - **Authors:** Heyu Si, Brandon James Denis, Muyang Sun, Dragos Datcu, Yaoru Li, Xin Jin, Ruiju Fu, Yuliia Tatarinova, Federico Landi, Jie Song, Mingli Song, Qi Guo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advancements in 4D scene reconstruction, particularly those leveraging diffusion priors, have shown promise for novel view synthesis in autonomous driving. However, these methods often process frames independently or in a view-by-view manner, leading to a critical lack of spatio-temporal synergy. This results in spatial misalignment across cameras and temporal drift in sequences. We propose DriveFix, a novel multi-view restoration framework that ensures spatio-temporal coherence for driving scenes. Our approach employs an interleaved diffusion transformer architecture with specialized blocks to explicitly model both temporal dependencies and cross-camera spatial consistency. By conditioning the generation on historical context and integrating geometry-aware training losses, DriveFix enforces that the restored views adhere to a unified 3D geometry. This enables the consistent propagation of high-fidelity textures and significantly reduces artifacts. Extensive evaluations on the Waymo, nuScenes, and PandaSet datasets demonstrate that DriveFix achieves state-of-the-art performance in both reconstruction and novel view synthesis, marking a substantial step toward robust 4D world modeling for real-world deployment.
### Title:
          Learning to Predict, Discover, and Reason in High-Dimensional Discrete Event Sequences
 - **Authors:** Hugo Math
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electronic control units (ECUs) embedded within modern vehicles generate a large number of asynchronous events known as diagnostic trouble codes (DTCs). These discrete events form complex temporal sequences that reflect the evolving health of the vehicle's subsystems. In the automotive industry, domain experts manually group these codes into higher-level error patterns (EPs) using Boolean rules to characterize system faults and ensure safety. However, as vehicle complexity grows, this manual process becomes increasingly costly, error-prone, and difficult to scale. Notably, the number of unique DTCs in a modern vehicle is on the same order of magnitude as the vocabulary of a natural language, often numbering in the tens of thousands. This observation motivates a paradigm shift: treating diagnostic sequences as a language that can be modeled, predicted, and ultimately explained. Traditional statistical approaches fail to capture the rich dependencies and do not scale to high-dimensional datasets characterized by thousands of nodes, large sample sizes, and long sequence lengths. Specifically, the high cardinality of categorical event spaces in industrial logs poses a significant challenge, necessitating new machine learning architectures tailored to such event-driven systems. This thesis addresses automated fault diagnostics by unifying event sequence modeling, causal discovery, and large language models (LLMs) into a coherent framework for high-dimensional event streams. It is structured in three parts, reflecting a progressive transition from prediction to causal understanding and finally to reasoning for vehicle diagnostics. Consequently, we introduce several Transformer-based architectures for predictive maintenance, scalable sample- and population-level causal discovery frameworks and a multi-agent system that automates the synthesis of Boolean EP rules.
### Title:
          $D^3$-RSMDE: 40$\times$ Faster and High-Fidelity Remote Sensing Monocular Depth Estimation
 - **Authors:** Ruizhi Wang, Weihan Li, Zunlei Feng, Haofei Zhang, Mingli Song, Jiayu Wang, Jie Song, Li Sun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time, high-fidelity monocular depth estimation from remote sensing imagery is crucial for numerous applications, yet existing methods face a stark trade-off between accuracy and efficiency. Although using Vision Transformer (ViT) backbones for dense prediction is fast, they often exhibit poor perceptual quality. Conversely, diffusion models offer high fidelity but at a prohibitive computational cost. To overcome these limitations, we propose Depth Detail Diffusion for Remote Sensing Monocular Depth Estimation ($D^3$-RSMDE), an efficient framework designed to achieve an optimal balance between speed and quality. Our framework first leverages a ViT-based module to rapidly generate a high-quality preliminary depth map construction, which serves as a structural prior, effectively replacing the time-consuming initial structure generation stage of diffusion models. Based on this prior, we propose a Progressive Linear Blending Refinement (PLBR) strategy, which uses a lightweight U-Net to refine the details in only a few iterations. The entire refinement step operates efficiently in a compact latent space supported by a Variational Autoencoder (VAE). Extensive experiments demonstrate that $D^3$-RSMDE achieves a notable 11.85% reduction in the Learned Perceptual Image Patch Similarity (LPIPS) perceptual metric over leading models like Marigold, while also achieving over a 40x speedup in inference and maintaining VRAM usage comparable to lightweight ViT models.
### Title:
          Poisoning the Pixels: Revisiting Backdoor Attacks on Semantic Segmentation
 - **Authors:** Guangsheng Zhang, Huan Tian, Leo Zhang, Tianqing Zhu, Ming Ding, Wanlei Zhou, Bo Liu
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic segmentation models are widely deployed in safety-critical applications such as autonomous driving, yet their vulnerability to backdoor attacks remains largely underexplored. Prior segmentation backdoor studies transfer threat settings from existing image classification tasks, focusing primarily on object-to-background mis-segmentation. In this work, we revisit the threats by systematically examining backdoor attacks tailored to semantic segmentation. We identify four coarse-grained attack vectors (Object-to-Object, Object-to-Background, Background-to-Object, and Background-to-Background attacks), as well as two fine-grained vectors (Instance-Level and Conditional attacks). To formalize these attacks, we introduce BADSEG, a unified framework that optimizes trigger designs and applies label manipulation strategies to maximize attack performance while preserving victim model utility. Extensive experiments across diverse segmentation architectures on benchmark datasets demonstrate that BADSEG achieves high attack effectiveness with minimal impact on clean samples. We further evaluate six representative defenses and find that they fail to reliably mitigate our attacks, revealing critical gaps in current defenses. Finally, we demonstrate that these vulnerabilities persist in recent emerging architectures, including transformer-based networks and the Segment Anything Model (SAM), thereby compromising their security. Our work reveals previously overlooked security vulnerabilities in semantic segmentation, and motivates the development of defenses tailored to segmentation-specific threat models.
### Title:
          SF-Mamba: Rethinking State Space Model for Vision
 - **Authors:** Masakazu Yoshimura, Teruaki Hayashi, Yuki Hoshino, Wei-Yao Wang, Takeshi Ohashi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The realm of Mamba for vision has been advanced in recent years to strike for the alternatives of Vision Transformers (ViTs) that suffer from the quadratic complexity. While the recurrent scanning mechanism of Mamba offers computational efficiency, it inherently limits non-causal interactions between image patches. Prior works have attempted to address this limitation through various multi-scan strategies; however, these approaches suffer from inefficiencies due to suboptimal scan designs and frequent data rearrangement. Moreover, Mamba exhibits relatively slow computational speed under short token lengths, commonly used in visual tasks. In pursuit of a truly efficient vision encoder, we rethink the scan operation for vision and the computational efficiency of Mamba. To this end, we propose SF-Mamba, a novel visual Mamba with two key proposals: auxiliary patch swapping for encoding bidirectional information flow under an unidirectional scan and batch folding with periodic state reset for advanced GPU parallelism. Extensive experiments on image classification, object detection, and instance and semantic segmentation consistently demonstrate that our proposed SF-Mamba significantly outperforms state-of-the-art baselines while improving throughput across different model sizes. We will release the source code after publication.
### Title:
          3D Fourier-based Global Feature Extraction for Hyperspectral Image Classification
 - **Authors:** Muhammad Ahmad
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hyperspectral image classification (HSIC) has been significantly advanced by deep learning methods that exploit rich spatial-spectral correlations. However, existing approaches still face fundamental limitations: transformer-based models suffer from poor scalability due to the quadratic complexity of self-attention, while recent Fourier transform-based methods typically rely on 2D spatial FFTs and largely ignore critical inter-band spectral dependencies inherent to hyperspectral data. To address these challenges, we propose Hybrid GFNet (HGFNet), a novel architecture that integrates localized 3D convolutional feature extraction with frequency-domain global filtering via GFNet-style blocks for efficient and robust spatial-spectral representation learning. HGFNet introduces three complementary frequency transforms tailored to hyperspectral imagery: Spectral Fourier Transform (a 1D FFT along the spectral axis), Spatial Fourier Transform (a 2D FFT over spatial dimensions), and Spatial-Spatial Fourier Transform (a 3D FFT jointly over spectral and spatial dimensions), enabling comprehensive and high-dimensional frequency modeling. The 3D convolutional layers capture fine-grained local spatial-spectral structures, while the Fourier-based global filtering modules efficiently model long-range dependencies and suppress noise. To further mitigate the severe class imbalance commonly observed in HSIC, HGFNet incorporates an Adaptive Focal Loss (AFL) that dynamically adjusts class-wise focusing and weighting, improving discrimination for underrepresented classes.
### Title:
          Capability-Guided Compression: Toward Interpretability-Aware Budget Allocation for Large Language Models
 - **Authors:** Rishaank Gupta
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language model compression has made substantial progress through pruning, quantization, and low-rank decomposition, yet a fundamental limitation persists across all existing methods: compression budgets are allocated without any representation of what individual model components functionally encode. We term this the capability-blind compression problem and argue it is a root cause of two well-documented failures -- the insensitivity of perplexity-based evaluation to reasoning capability loss, and the abrupt phase transitions in model performance recently characterized by Ma et al. (2026). We propose Capability-Guided Compression (CGC), a framework that addresses this by using Sparse Autoencoder (SAE)-derived capability density maps to allocate differential compression budgets across transformer components. Capability density is a formally defined scalar measure combining the feature breadth, activation entropy, and cross-input consistency of a component's SAE feature activation distribution. We prove theoretically that components with higher capability density exhibit lower structural redundancy and reach their individual phase transition points at lower compression ratios, providing the first pre-compression mechanism for component-level phase transition prediction. Experiments on GPT-2 Medium confirm that capability density is statistically independent of Wanda importance scores (Spearman rho = -0.054, n = 384 heads), establishing it as a genuinely novel compression signal orthogonal to all existing importance metrics. We report a negative result on PPL-based compression comparison and provide a principled diagnosis identifying GPT-2 Medium as an insufficient test bed for the full CGC hypothesis. The theoretical framework, density formalism, and orthogonality finding constitute a foundation for capability-aware compression research.
### Title:
          DST-Net: A Dual-Stream Transformer with Illumination-Independent Feature Guidance and Multi-Scale Spatial Convolution for Low-Light Image Enhancement
 - **Authors:** Yicui Shi, Yuhan Chen, Xiangfei Huang, Zhenguo Wang, Wenxuan Yu, Ying Fang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Low-light image enhancement aims to restore the visibility of images captured by visual sensors in dim environments by addressing their inherent signal degradations, such as luminance attenuation and structural corruption. Although numerous algorithms attempt to improve image quality, existing methods often cause a severe loss of intrinsic signal priors. To overcome these challenges, we propose a Dual-Stream Transformer Network (DST-Net) based on illumination-agnostic signal prior guidance and multi-scale spatial convolutions. First, to address the loss of critical signal features under low-light conditions, we design a feature extraction module. This module integrates Difference of Gaussians (DoG), LAB color space transformations, and VGG-16 for texture extraction, utilizing decoupled illumination-agnostic features as signal priors to continuously guide the enhancement process. Second, we construct a dual-stream interaction architecture. By employing a cross-modal attention mechanism, the network leverages the extracted priors to dynamically rectify the deteriorated signal representation of the enhanced image, ultimately achieving iterative enhancement through differentiable curve estimation. Furthermore, to overcome the inability of existing methods to preserve fine structures and textures, we propose a Multi-Scale Spatial Fusion Block (MSFB) featuring pseudo-3D and 3D gradient operator convolutions. This module integrates explicit gradient operators to recover high-frequency edges while capturing inter-channel spatial correlations via multi-scale spatial convolutions. Extensive evaluations and ablation studies demonstrate that DST-Net achieves superior performance in subjective visual quality and objective metrics. Specifically, our method achieves a PSNR of 25.64 dB on the LOL dataset. Subsequent validation on the LSRW dataset further confirms its robust cross-scene generalization.
### Title:
          SympFormer: Accelerated attention blocks via Inertial Dynamics on Density Manifolds
 - **Authors:** Viktor Stein, Wuchen Li, Gabriele Steidl
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optimization and Control (math.OC); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers owe much of their empirical success in natural language processing to the self-attention blocks. Recent perspectives interpret attention blocks as interacting particle systems, whose mean-field limits correspond to gradient flows of interaction energy functionals on probability density spaces equipped with Wasserstein-$2$-type metrics. We extend this viewpoint by introducing accelerated attention blocks derived from inertial Nesterov-type dynamics on density spaces. In our proposed architecture, tokens carry both spatial (feature) and velocity variables. The time discretization and the approximation of accelerated density dynamics yield Hamiltonian momentum attention blocks, which constitute the proposed accelerated attention architectures. In particular, for linear self-attention, we show that the attention blocks approximate a Stein variational gradient flow, using a bilinear kernel, of a potential energy. In this setting, we prove that elliptically contoured probability distributions are preserved by the accelerated attention blocks. We present implementable particle-based algorithms and demonstrate that the proposed accelerated attention blocks converge faster than the classical attention blocks while preserving the number of oracle calls.
### Title:
          ASCENT: Transformer-Based Aircraft Trajectory Prediction in Non-Towered Terminal Airspace
 - **Authors:** Alexander Prutsch, David Schinagl, Horst Possegger
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate trajectory prediction can improve General Aviation safety in non-towered terminal airspace, where high traffic density increases accident risk. We present ASCENT, a lightweight transformer-based model for multi-modal 3D aircraft trajectory forecasting, which integrates domain-aware 3D coordinate normalization and parameterized predictions. ASCENT employs a transformer-based motion encoder and a query-based decoder, enabling the generation of diverse maneuver hypotheses with low latency. Experiments on the TrajAir and TartanAviation datasets demonstrate that our model outperforms prior baselines, as the encoder effectively captures motion dynamics and the decoder aligns with structured aircraft traffic patterns. Furthermore, ablation studies confirm the contributions of the decoder design, coordinate-frame modeling, and parameterized outputs. These results establish ASCENT as an effective approach for real-time aircraft trajectory prediction in non-towered terminal airspace.
### Title:
          Understanding Cell Fate Decisions with Temporal Attention
 - **Authors:** Florian Bürger, Martim Dias Gomes, Adrián E. Granada, Noémie Moreau, Katarzyna Bozek
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Cell Behavior (q-bio.CB); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding non-genetic determinants of cell fate is critical for developing and improving cancer therapies, as genetically identical cells can exhibit divergent outcomes under the same treatment conditions. In this work, we present a deep learning approach for cell fate prediction from raw long-term live-cell recordings of cancer cell populations under chemotherapeutic treatment. Our Transformer model is trained to predict cell fate directly from raw image sequences, without relying on predefined morphological or molecular features. Beyond classification, we introduce a comprehensive explainability framework for interpreting the temporal and morphological cues guiding the model's predictions. We demonstrate that prediction of cell outcomes is possible based on the video only, our model achieves balanced accuracy of 0.94 and an F1-score of 0.93. Attention and masking experiments further indicate that the signal predictive of the cell fate is not uniquely located in the final frames of a cell trajectory, as reliable predictions are possible up to 10 h before the event. Our analysis reveals distinct temporal distribution of predictive information in the mitotic and apoptotic sequences, as well as the role of cell morphology and p53 signaling in determining cell outcomes. Together, these findings demonstrate that attention-based temporal models enable accurate cell fate prediction while providing biologically interpretable insights into non-genetic determinants of cellular decision-making. The code is available at this https URL.
### Title:
          VideoMatGen: PBR Materials through Joint Generative Modeling
 - **Authors:** Jon Hasselgren, Zheng Zeng, Milos Hasan, Jacob Munkberg
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a method for generating physically-based materials for 3D shapes based on a video diffusion transformer architecture. Our method is conditioned on input geometry and a text description, and jointly models multiple material properties (base color, roughness, metallicity, height map) to form physically plausible materials. We further introduce a custom variational auto-encoder which encodes multiple material modalities into a compact latent space, which enables joint generation of multiple modalities without increasing the number of tokens. Our pipeline generates high-quality materials for 3D shapes given a text prompt, compatible with common content creation tools.
### Title:
          Deep Tabular Representation Corrector
 - **Authors:** Hangting Ye, Peng Wang, Wei Fan, Xiaozhuang Song, He Zhao, Dandan Gun, Yi Chang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tabular data have been playing a mostly important role in diverse real-world fields, such as healthcare, engineering, finance, etc. The recent success of deep learning has fostered many deep networks (e.g., Transformer, ResNet) based tabular learning methods. Generally, existing deep tabular machine learning methods are along with the two paradigms, i.e., in-learning and pre-learning. In-learning methods need to train networks from scratch or impose extra constraints to regulate the representations which nonetheless train multiple tasks simultaneously and make learning more difficult, while pre-learning methods design several pretext tasks for pre-training and then conduct task-specific fine-tuning, which however need much extra training effort with prior knowledge. In this paper, we introduce a novel deep Tabular Representation Corrector, TRC, to enhance any trained deep tabular model's representations without altering its parameters in a model-agnostic manner. Specifically, targeting the representation shift and representation redundancy that hinder prediction, we propose two tasks, i.e., (i) Tabular Representation Re-estimation, that involves training a shift estimator to calculate the inherent shift of tabular representations to subsequently mitigate it, thereby re-estimating the representations and (ii) Tabular Space Mapping, that transforms the above re-estimated representations into a light-embedding vector space via a coordinate estimator while preserves crucial predictive information to minimize redundancy. The two tasks jointly enhance the representations of deep tabular models without touching on the original models thus enjoying high efficiency. Finally, we conduct extensive experiments on state-of-the-art deep tabular machine learning models coupled with TRC on various tabular benchmarks which have shown consistent superiority.
### Title:
          Diverging Transformer Predictions for Human Sentence Processing: A Comprehensive Analysis of Agreement Attraction Effects
 - **Authors:** Titus von der Malsburg, Sebastian Padó
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers underlie almost all state-of-the-art language models in computational linguistics, yet their cognitive adequacy as models of human sentence processing remains disputed. In this work, we use a surprisal-based linking mechanism to systematically evaluate eleven autoregressive transformers of varying sizes and architectures on a more comprehensive set of English agreement attraction configurations than prior work. Our experiments yield mixed results: While transformer predictions generally align with human reading time data for prepositional phrase configurations, performance degrades significantly on object-extracted relative clause configurations. In the latter case, predictions also diverge markedly across models, and no model successfully replicates the asymmetric interference patterns observed in humans. We conclude that current transformer models do not explain human morphosyntactic processing, and that evaluations of transformers as cognitive models must adopt rigorous, comprehensive experimental designs to avoid spurious generalizations from isolated syntactic configurations or individual models.
### Title:
          Grid-World Representations in Transformers Reflect Predictive Geometry
 - **Authors:** Sasha Brenner, Thomas R. Knösche, Nico Scherf
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Next-token predictors often appear to develop internal representations of the latent world and its rules. The probabilistic nature of these models suggests a deep connection between the structure of the world and the geometry of probability distributions. In order to understand this link more precisely, we use a minimal stochastic process as a controlled setting: constrained random walks on a two-dimensional lattice that must reach a fixed endpoint after a predetermined number of steps. Optimal prediction of this process solely depends on a sufficient vector determined by the walker's position relative to the target and the remaining time horizon; in other words, the probability distributions are parametrized by the world's geometry. We train decoder-only transformers on prefixes sampled from the exact distribution of these walks and compare their hidden activations to the analytically derived sufficient vectors. Across models and layers, the learned representations align strongly with the ground-truth predictive vectors and are often low-dimensional. This provides a concrete example in which world-model-like representations can be directly traced back to the predictive geometry of the data itself. Although demonstrated in a simplified toy system, the analysis suggests that geometric representations supporting optimal prediction may provide a useful lens for studying how neural networks internalize grammatical and other structural constraints.
### Title:
          SOMP: Scalable Gradient Inversion for Large Language Models via Subspace-Guided Orthogonal Matching Pursuit
 - **Authors:** Yibo Li, Qiongxiu Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Gradient inversion attacks reveal that private training text can be reconstructed from shared gradients, posing a privacy risk to large language models (LLMs). While prior methods perform well in small-batch settings, scaling to larger batch sizes and longer sequences remains challenging due to severe signal mixing, high computational cost, and degraded fidelity. We present SOMP (Subspace-Guided Orthogonal Matching Pursuit), a scalable gradient inversion framework that casts text recovery from aggregated gradients as a sparse signal recovery problem. Our key insight is that aggregated transformer gradients retain exploitable head-wise geometric structure together with sample-level sparsity. SOMP leverages these properties to progressively narrow the search space and disentangle mixed signals without exhaustive search. Experiments across multiple LLM families, model scales, and five languages show that SOMP consistently outperforms prior methods in the aggregated-gradient this http URL long sequences at batch size B=16, SOMP achieves substantially higher reconstruction fidelity than strong baselines, while remaining computationally competitive. Even under extreme aggregation (up to B=128), SOMP still recovers meaningful text, suggesting that privacy leakage can persist in regimes where prior attacks become much less effective.
### Title:
          What DINO saw: ALiBi positional encoding reduces positional bias in Vision Transformers
 - **Authors:** Moritz Pawlowsky, Antonis Vamvakeros, Alexander Weiss, Anja Bielefeld, Samuel J. Cooper, Ronan Docherty
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Materials Science (cond-mat.mtrl-sci)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision transformers (ViTs) - especially feature foundation models like DINOv2 - learn rich representations useful for many downstream tasks. However, architectural choices (such as positional encoding) can lead to these models displaying positional biases and artefacts independent of semantic content. This makes zero-shot adaption difficult in fields like material science, where images are often cross-sections of homogeneous microstructure (i.e. having no preferred direction). In this work, we investigate the positional bias in ViTs via linear probing, finding it present across a range of objectives and positional encodings, and subsequently reduce it by finetuning models to use ALiBi relative positional encoding. We demonstrate that these models retain desirable general semantics and their unbiased features can be used successfully in trainable segmentation of complex microscopy images.
### Title:
          GIST: Gauge-Invariant Spectral Transformers for Scalable Graph Neural Operators
 - **Authors:** Mattia Rigotti, Nicholas Thumiger, Thomas Frick
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adapting transformer positional encoding to meshes and graph-structured data presents significant computational challenges: exact spectral methods require cubic-complexity eigendecomposition and can inadvertently break gauge invariance through numerical solver artifacts, while efficient approximate methods sacrifice gauge symmetry by design. Both failure modes cause catastrophic generalization in inductive learning, where models trained with one set of numerical choices fail when encountering different spectral decompositions of similar graphs or discretizations of the same mesh. We propose GIST (Gauge-Invariant Spectral Transformers), a new graph transformer architecture that resolves this challenge by achieving end-to-end $\mathcal{O}(N)$ complexity through random projections while algorithmically preserving gauge invariance via inner-product-based attention on the projected embeddings. We prove GIST achieves discretization-invariant learning with bounded mismatch error, enabling parameter transfer across arbitrary mesh resolutions for neural operator applications. Empirically, GIST matches state-of-the-art on standard graph benchmarks (e.g., achieving 99.50% micro-F1 on PPI) while uniquely scaling to mesh-based Neural Operator benchmarks with up to 750K nodes, achieving state-of-the-art aerodynamic prediction on the challenging DrivAerNet and DrivAerNet++ datasets.
### Title:
          Long-Horizon Traffic Forecasting via Incident-Aware Conformal Spatio-Temporal Transformers
 - **Authors:** Mayur Patil, Qadeer Ahmed, Shawn Midlam-Mohler, Stephanie Marik, Allen Sheldon, Rajeev Chhajer, Nithin Santhanam
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable multi-horizon traffic forecasting is challenging because network conditions are stochastic, incident disruptions are intermittent, and effective spatial dependencies vary across time-of-day patterns. This study is conducted on the Ohio Department of Transportation (ODOT) traffic count data and corresponding ODOT crash records. This work utilizes a Spatio-Temporal Transformer (STT) model with Adaptive Conformal Prediction (ACP) to produce multi-horizon forecasts with calibrated uncertainty. We propose a piecewise Coefficient of Variation (CV) strategy that models hour-to-hour traveltime variability using a log-normal distribution, enabling the construction of a per-hour dynamic adjacency matrix. We further perturb edge weights using incident-related severity signals derived from the ODOT crash dataset that comprises incident clearance time, weather conditions, speed violations, work zones, and roadway functional class, to capture localized disruptions and peak/off-peak transitions. This dynamic graph construction replaces a fixed-CV assumption and better represents changing traffic conditions within the forecast window. For validation, we generate extended trips via multi-hour loop runs on the Columbus, Ohio, network in SUMO simulations and apply a Monte Carlo simulation to obtain travel-time distributions for a Vehicle Under Test (VUT). Experiments demonstrate improved long-horizon accuracy and well-calibrated prediction intervals compared to other baseline methods.
### Title:
          Demystifing Video Reasoning
 - **Authors:** Ruisi Wang, Zhongang Cai, Fanyi Pu, Junxiang Xu, Wanqi Yin, Maijunxian Wang, Ran Ji, Chenyang Gu, Bo Li, Ziqi Huang, Hokin Deng, Dahua Lin, Ziwei Liu, Lei Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in video generation have revealed an unexpected phenomenon: diffusion-based video models exhibit non-trivial reasoning capabilities. Prior work attributes this to a Chain-of-Frames (CoF) mechanism, where reasoning is assumed to unfold sequentially across video frames. In this work, we challenge this assumption and uncover a fundamentally different mechanism. We show that reasoning in video models instead primarily emerges along the diffusion denoising steps. Through qualitative analysis and targeted probing experiments, we find that models explore multiple candidate solutions in early denoising steps and progressively converge to a final answer, a process we term Chain-of-Steps (CoS). Beyond this core mechanism, we identify several emergent reasoning behaviors critical to model performance: (1) working memory, enabling persistent reference; (2) self-correction and enhancement, allowing recovery from incorrect intermediate solutions; and (3) perception before action, where early steps establish semantic grounding and later steps perform structured manipulation. During a diffusion step, we further uncover self-evolved functional specialization within Diffusion Transformers, where early layers encode dense perceptual structure, middle layers execute reasoning, and later layers consolidate latent representations. Motivated by these insights, we present a simple training-free strategy as a proof-of-concept, demonstrating how reasoning can be improved by ensembling latent trajectories from identical models with different random seeds. Overall, our work provides a systematic understanding of how reasoning emerges in video generation models, offering a foundation to guide future research in better exploiting the inherent reasoning dynamics of video models as a new substrate for intelligence.
### Title:
          WorldCam: Interactive Autoregressive 3D Gaming Worlds with Camera Pose as a Unifying Geometric Representation
 - **Authors:** Jisu Nam, Yicong Hong, Chun-Hao Paul Huang, Feng Liu, JoungBin Lee, Jiyoung Kim, Siyoon Jin, Yunsung Lee, Jaeyoon Jung, Suhwan Choi, Seungryong Kim, Yang Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in video diffusion transformers have enabled interactive gaming world models that allow users to explore generated environments over extended horizons. However, existing approaches struggle with precise action control and long-horizon 3D consistency. Most prior works treat user actions as abstract conditioning signals, overlooking the fundamental geometric coupling between actions and the 3D world, whereby actions induce relative camera motions that accumulate into a global camera pose within a 3D world. In this paper, we establish camera pose as a unifying geometric representation to jointly ground immediate action control and long-term 3D consistency. First, we define a physics-based continuous action space and represent user inputs in the Lie algebra to derive precise 6-DoF camera poses, which are injected into the generative model via a camera embedder to ensure accurate action alignment. Second, we use global camera poses as spatial indices to retrieve relevant past observations, enabling geometrically consistent revisiting of locations during long-horizon navigation. To support this research, we introduce a large-scale dataset comprising 3,000 minutes of authentic human gameplay annotated with camera trajectories and textual descriptions. Extensive experiments show that our approach substantially outperforms state-of-the-art interactive gaming world models in action controllability, long-horizon visual quality, and 3D spatial consistency.
## Keyword: autonomous driving
### Title:
          CorrectionPlanner: Self-Correction Planner with Reinforcement Learning in Autonomous Driving
 - **Authors:** Yihong Guo, Dongqiangzi Ye, Sijia Chen, Anqi Liu, Xianming Liu
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving requires safe planning, but most learning-based planners lack explicit self-correction ability: once an unsafe action is proposed, there is no mechanism to correct it. Thus, we propose CorrectionPlanner, an autoregressive planner with self-correction that models planning as motion-token generation within a propose, evaluate, and correct loop. At each planning step, the policy proposes an action, namely a motion token, and a learned collision critic predicts whether it will induce a collision within a short horizon. If the critic predicts a collision, we retain the sequence of historical unsafe motion tokens as a self-correction trace, generate the next motion token conditioned on it, and repeat this process until a safe motion token is proposed or the safety criterion is met. This self-correction trace, consisting of all unsafe motion tokens, represents the planner's correction process in motion-token space, analogous to a reasoning trace in language models. We train the planner with imitation learning followed by model-based reinforcement learning using rollouts from a pretrained world model that realistically models agents' reactive behaviors. Closed-loop evaluations show that CorrectionPlanner reduces collision rate by over 20% on Waymax and achieves state-of-the-art planning scores on nuPlan.
### Title:
          Safety Case Patterns for VLA-based driving systems: Insights from SimLingo
 - **Authors:** Gerhard Yu, Fuyuki Ishikawa, Oluwafemi Odu, Alvine Boaye Belle
 - **Subjects:** Subjects:
Robotics (cs.RO); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-Language-Action (VLA)-based driving systems represent a significant paradigm shift in autonomous driving since, by combining traffic scene understanding, linguistic interpretation, and action generation, these systems enable more flexible, adaptive, and instruction-responsive driving behaviors. However, despite their growing adoption and potential to support socially responsible autonomous driving while understanding high-level human instructions, VLA-based driving systems may exhibit new types of hazardous behaviors. Such as the addition of natural language inputs (e.g., user or navigation instructions) into the multimodal control loop, which may lead to unpredictable and unsafe behaviors that could endanger vehicle occupants and pedestrians. Hence, assuring the safety of these systems is crucial to help build trust in their operations. To support this, we propose a novel safety case design approach called RAISE. Our approach introduces novel patterns tailored to instruction-based driving systems such as VLA-based driving systems, an extension of Hazard Analysis and Risk Assessment (HARA) detailing safe scenarios and their outcomes, and a design technique to create the safety cases of VLA-based driving systems. A case study on SimLingo illustrates how our approach can be used to construct rigorous, evidence-based safety claims for this emerging class of autonomous driving systems.
### Title:
          The Era of End-to-End Autonomy: Transitioning from Rule-Based Driving to Large Driving Models
 - **Authors:** Eduardo Nebot, Julie Stephany Berrio Perez
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving is undergoing a shift from modular rule based pipelines toward end to end (E2E) learning systems. This paper examines this transition by tracing the evolution from classical sense perceive plan control architectures to large driving models (LDMs) capable of mapping raw sensor input directly to driving actions. We analyze recent developments including Tesla's Full Self Driving (FSD) V12 V14, Rivian's Unified Intelligence platform, NVIDIA Cosmos, and emerging commercial robotaxi deployments, focusing on architectural design, deployment strategies, safety considerations and industry implications. A key emerging product category is supervised E2E driving, often referred to as FSD (Supervised) or L2 plus plus, which several manufacturers plan to deploy from 2026 onwards. These systems can perform most of the Dynamic Driving Task (DDT) in complex environments while requiring human supervision, shifting the driver's role to safety oversight. Early operational evidence suggests E2E learning handles the long tail distribution of real world driving scenarios and is becoming a dominant commercial strategy. We also discuss how similar architectural advances may extend beyond autonomous vehicles (AV) to other embodied AI systems, including humanoid robotics.
### Title:
          PanguMotion: Continuous Driving Motion Forecasting with Pangu Transformers
 - **Authors:** Quanhao Ren, Yicheng Li, Nan Song
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Motion forecasting is a core task in autonomous driving systems, aiming to accurately predict the future trajectories of surrounding agents to ensure driving safety. Existing methods typically process discrete driving scenes independently, neglecting the temporal continuity and historical context correlations inherent in real-world driving environments. This paper proposes PanguMotion, a motion forecasting framework for continuous driving scenarios that integrates Transformer blocks from the Pangu-1B large language model as feature enhancement modules into autonomous driving motion prediction architectures. We conduct experiments on the Argoverse 2 datasets processed by the RealMotion data reorganization strategy, transforming each independent scene into a continuous sequence to mimic real-world driving scenarios.
### Title:
          AW-MoE: All-Weather Mixture of Experts for Robust Multi-Modal 3D Object Detection
 - **Authors:** Hongwei Lin, Xun Huang, Chenglu Wen, Cheng Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust 3D object detection under adverse weather conditions is crucial for autonomous driving. However, most existing methods simply combine all weather samples for training while overlooking data distribution discrepancies across different weather scenarios, leading to performance conflicts. To address this issue, we introduce AW-MoE, the framework that innovatively integrates Mixture of Experts (MoE) into weather-robust multi-modal 3D object detection approaches. AW-MoE incorporates Image-guided Weather-aware Routing (IWR), which leverages the superior discriminability of image features across weather conditions and their invariance to scene variations for precise weather classification. Based on this accurate classification, IWR selects the top-K most relevant Weather-Specific Experts (WSE) that handle data discrepancies, ensuring optimal detection under all weather conditions. Additionally, we propose a Unified Dual-Modal Augmentation (UDMA) for synchronous LiDAR and 4D Radar dual-modal data augmentation while preserving the realism of scenes. Extensive experiments on the real-world dataset demonstrate that AW-MoE achieves ~ 15% improvement in adverse-weather performance over state-of-the-art methods, while incurring negligible inference overhead. Moreover, integrating AW-MoE into established baseline detectors yields performance improvements surpassing current state-of-the-art methods. These results show the effectiveness and strong scalability of our AW-MoE. We will release the code publicly at this https URL.
### Title:
          Toward Deep Representation Learning for Event-Enhanced Visual Autonomous Perception: the eAP Dataset
 - **Authors:** Jinghang Li, Shichao Li, Qing Lian, Peiliang Li, Xiaozhi Chen, Yi Zhou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent visual autonomous perception systems achieve remarkable performances with deep representation learning. However, they fail in scenarios with challenging this http URL event cameras can mitigate this problem, there is a lack of a large-scale dataset to develop event-enhanced deep visual perception models in autonomous driving scenes. To address the gap, we present the eAP (event-enhanced Autonomous Perception) dataset, the largest dataset with event cameras for autonomous perception. We demonstrate how eAP can facilitate the study of different autonomous perception tasks, including 3D vehicle detection and object time-to-contact (TTC) estimation, through deep representation learning. Based on eAP, we demonstrate the ffrst successful use of events to improve a popular 3D vehicle detection network in challenging illumination scenarios. eAP also enables a devoted study of the representation learning problem of object TTC estimation. We show how a geometryaware representation learning framework leads to the best eventbased object TTC estimation network that operates at 200 FPS. The dataset, code, and pre-trained models will be made publicly available for future research.
### Title:
          DriveFix: Spatio-Temporally Coherent Driving Scene Restoration
 - **Authors:** Heyu Si, Brandon James Denis, Muyang Sun, Dragos Datcu, Yaoru Li, Xin Jin, Ruiju Fu, Yuliia Tatarinova, Federico Landi, Jie Song, Mingli Song, Qi Guo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advancements in 4D scene reconstruction, particularly those leveraging diffusion priors, have shown promise for novel view synthesis in autonomous driving. However, these methods often process frames independently or in a view-by-view manner, leading to a critical lack of spatio-temporal synergy. This results in spatial misalignment across cameras and temporal drift in sequences. We propose DriveFix, a novel multi-view restoration framework that ensures spatio-temporal coherence for driving scenes. Our approach employs an interleaved diffusion transformer architecture with specialized blocks to explicitly model both temporal dependencies and cross-camera spatial consistency. By conditioning the generation on historical context and integrating geometry-aware training losses, DriveFix enforces that the restored views adhere to a unified 3D geometry. This enables the consistent propagation of high-fidelity textures and significantly reduces artifacts. Extensive evaluations on the Waymo, nuScenes, and PandaSet datasets demonstrate that DriveFix achieves state-of-the-art performance in both reconstruction and novel view synthesis, marking a substantial step toward robust 4D world modeling for real-world deployment.
### Title:
          Learning Human-Object Interaction for 3D Human Pose Estimation from LiDAR Point Clouds
 - **Authors:** Daniel Sungho Jung, Dohee Cho, Kyoung Mu Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding humans from LiDAR point clouds is one of the most critical tasks in autonomous driving due to its close relationships with pedestrian safety, yet it remains challenging in the presence of diverse human-object interactions and cluttered backgrounds. Nevertheless, existing methods largely overlook the potential of leveraging human-object interactions to build robust 3D human pose estimation frameworks. There are two major challenges that motivate the incorporation of human-object interaction. First, human-object interactions introduce spatial ambiguity between human and object points, which often leads to erroneous 3D human keypoint predictions in interaction regions. Second, there exists severe class imbalance in the number of points between interacting and non-interacting body parts, with the interaction-frequent regions such as hand and foot being sparsely observed in LiDAR data. To address these challenges, we propose a Human-Object Interaction Learning (HOIL) framework for robust 3D human pose estimation from LiDAR point clouds. To mitigate the spatial ambiguity issue, we present human-object interaction-aware contrastive learning (HOICL) that effectively enhances feature discrimination between human and object points, particularly in interaction regions. To alleviate the class imbalance issue, we introduce contact-aware part-guided pooling (CPPool) that adaptively reallocates representational capacity by compressing overrepresented points while preserving informative points from interacting body parts. In addition, we present an optional contact-based temporal refinement that refines erroneous per-frame keypoint estimates using contact cues over time. As a result, our HOIL effectively leverages human-object interaction to resolve spatial ambiguity and class imbalance in interaction regions. Codes will be released.
### Title:
          Poisoning the Pixels: Revisiting Backdoor Attacks on Semantic Segmentation
 - **Authors:** Guangsheng Zhang, Huan Tian, Leo Zhang, Tianqing Zhu, Ming Ding, Wanlei Zhou, Bo Liu
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic segmentation models are widely deployed in safety-critical applications such as autonomous driving, yet their vulnerability to backdoor attacks remains largely underexplored. Prior segmentation backdoor studies transfer threat settings from existing image classification tasks, focusing primarily on object-to-background mis-segmentation. In this work, we revisit the threats by systematically examining backdoor attacks tailored to semantic segmentation. We identify four coarse-grained attack vectors (Object-to-Object, Object-to-Background, Background-to-Object, and Background-to-Background attacks), as well as two fine-grained vectors (Instance-Level and Conditional attacks). To formalize these attacks, we introduce BADSEG, a unified framework that optimizes trigger designs and applies label manipulation strategies to maximize attack performance while preserving victim model utility. Extensive experiments across diverse segmentation architectures on benchmark datasets demonstrate that BADSEG achieves high attack effectiveness with minimal impact on clean samples. We further evaluate six representative defenses and find that they fail to reliably mitigate our attacks, revealing critical gaps in current defenses. Finally, we demonstrate that these vulnerabilities persist in recent emerging architectures, including transformer-based networks and the Segment Anything Model (SAM), thereby compromising their security. Our work reveals previously overlooked security vulnerabilities in semantic segmentation, and motivates the development of defenses tailored to segmentation-specific threat models.
### Title:
          CD-FKD: Cross-Domain Feature Knowledge Distillation for Robust Single-Domain Generalization in Object Detection
 - **Authors:** Junseok Lee, Sungho Shin, Seongju Lee, Kyoobin Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Single-domain generalization is essential for object detection, particularly when training models on a single source domain and evaluating them on unseen target domains. Domain shifts, such as changes in weather, lighting, or scene conditions, pose significant challenges to the generalization ability of existing models. To address this, we propose Cross-Domain Feature Knowledge Distillation (CD-FKD), which enhances the generalization capability of the student network by leveraging both global and instance-wise feature distillation. The proposed method uses diversified data through downscaling and corruption to train the student network, whereas the teacher network receives the original source domain data. The student network mimics the features of the teacher through both global and instance-wise distillation, enabling it to extract object-centric features effectively, even for objects that are difficult to detect owing to corruption. Extensive experiments on challenging scenes demonstrate that CD-FKD outperforms state-of-the-art methods in both target domain generalization and source domain performance, validating its effectiveness in improving object detection robustness to domain shifts. This approach is valuable in real-world applications, like autonomous driving and surveillance, where robust object detection in diverse environments is crucial.
