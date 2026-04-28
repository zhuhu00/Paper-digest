# Showing new listings for Tuesday, 28 April 2026
## Keyword: SLAM
### Title:
          Event-based SLAM Benchmark for High-Speed Maneuvers
 - **Authors:** Sheng Zhong, Junkai Niu, Guillermo Gallego, Kaizhen Sun, Yang Yi, Zhiqiang Miao, Dewen Hu, Yaonan Wang, Davide Scaramuzza, Yi Zhou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event-based cameras are bio-inspired sensors with pixels that independently and asynchronously respond to brightness changes at microsecond resolution, offering the potential to handle visual tasks in high-speed maneuvering scenarios. Existing event-based approaches, although successful in mitigating motion blur caused by high-speed maneuvers, suffer from many limitations. Some of them highlight a success of pose tracking for a fronto-parallel fast shaking camera closed to the structure, while others assume pure (optionally aggressive) three-degree-of-freedom rotations. The former requires persistent local map visibility within the field of view (FOV), whereas the latter fails to generalize to six-degree-of-freedom (6-DoF) motions where both linear and angular velocities may be large. Consequently, current successes do not fully demonstrate that event-based state estimation under arbitrary aggressive maneuvers is a fully solved problem. To quantitatively assess the extent to which the potential of event cameras has been unlocked, we conduct a thorough analysis of state-of-the-art (SOTA) event-based visual odometry (VO)/visual-inertial odometry (VIO) methods and report shortcomings in current public datasets. Furthermore, we introduce a benchmarking framework for event-based state estimation, called EvSLAM, characterized by sufficient variation in data collection platforms, diverse extreme lighting scenarios, and a wide scope of challenging motion patterns under a clear and rigorous definition of high-speed maneuvers for mobile robots, along with a novel evaluation metric designed to fairly assess the operational limits of event-based solutions. This framework benchmarks state-of-the-art methods, yielding insights into optimal architectures and persistent challenges.
### Title:
          OpenPodcar2: a robust, ROS2 vehicle for self-driving research
 - **Authors:** Rakshit Soni, Chris Waltham, Md Umar Ibrahim, Mark Crampton, Charles Fox
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 OpenPodcar2 is a robust, ROS2-interfaced, low-cost, open source hardware and software, autonomous vehicle platform based on an off-the-shelf, hard-canopy, mobility scooter donor vehicle. It is a modification of the previous OpenPodcar design, which extends it with robust electronics and ROS2 interfacing, to enable both research and also potential deployment use cases. The platform consists of (a) hardware components: documented as a bill of materials and build instructions; (b) integration to the general purpose OSH R4 mechatronics board and a Gazebo simulation of the vehicle, both presenting a common ROS2 interface (c) higher-level ROS2 software implementations and configurations of standard robot autonomous planning and control, including the nav2 stack which performs SLAM and enacts commands to drive the vehicle from a current to a desired pose around obstacles. OpenPodcar2 can transport a human passenger or similar load at speeds up to 15km/h, for example for use as a last-mile autonomous taxi service or to transport delivery containers similarly around a city center. It is small and safe enough to be parked in a standard research lab robust enough for some deployment cases. Total build cost was around 7,000USD from new components, or 2,000USD with a used Donor Vehicle. OpenPodcar2 thus provides a research balance between real world utility, safety, cost and robustness.
### Title:
          Passage-Aware Structural Mapping for RGB-D Visual SLAM
 - **Authors:** Ali Tourani, Miguel Fernandez-Cortizas, Saad Ejaz, David Pérez Saura, Asier Bikandi-Noya, Jose Luis Sanchez-Lopez, Holger Voos
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Doorways and passages are critical structural elements for indoor robot navigation, yet they remain underexplored in modern Visual SLAM (VSLAM) frameworks. This paper presents a passage-aware structural mapping approach for RGB-D VSLAM that detects doors and traversable openings by jointly fusing geometric, semantic, and topological cues. Doors are modeled as planar entities embedded within walls and classified as traversable or non-traversable based on their coplanarity with the supporting wall. Passages are inferred through two complementary strategies: traversal evidence accumulated from camera-wall interactions across consecutive keyframes, and geometric opening validation based on discontinuities in the mapped wall geometry. The proposed method is integrated into vS-Graphs as a proof of concept, enriching its scene graph with passage-level abstractions and improving room connectivity modeling. Qualitative evaluations on indoor office sequences demonstrate reliable doorway detection, and the framework lays the foundation for exploiting these elements in BIM-informed VSLAM. The source code is publicly available at this https URL.
## Keyword: odometry
### Title:
          Equivariant Filter for Radar-Inertial Odometry
 - **Authors:** Giulio Delama, Jan Michalczyk, Morten Nissov, Martin Scheiber, Alessandro Fornasier, Kostas Alexis, Stephan Weiss
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar-Inertial Odometry (RIO) based on the Extended Kalman Filter (EKF) relies on accurate extrinsic calibration between the radar and the Inertial Measurement Unit (IMU) and is sensitive to disturbances, as large linearization errors can degrade performance or even cause divergence. To address these limitations, this letter proposes an Equivariant Filter (EqF) for RIO based on a Lie group symmetry that geometrically couples navigation states and IMU biases, extending it to incorporate radar-IMU extrinsic calibration and multi-state constraint updates. This equivariant formulation inherently preserves consistency and enhances robustness, enabling reliable state estimation even under poor or completely wrong initialization of calibration states. Real-world experiments on two different Uncrewed Aerial Vehicles (UAVs) show that the proposed EqF-RIO achieves state-of-the-art accuracy under correct extrinsic calibration and offers improved convergence under large calibration errors, where the conventional EKF-RIO fails. Evaluation code is open-sourced.
### Title:
          Event-based SLAM Benchmark for High-Speed Maneuvers
 - **Authors:** Sheng Zhong, Junkai Niu, Guillermo Gallego, Kaizhen Sun, Yang Yi, Zhiqiang Miao, Dewen Hu, Yaonan Wang, Davide Scaramuzza, Yi Zhou
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event-based cameras are bio-inspired sensors with pixels that independently and asynchronously respond to brightness changes at microsecond resolution, offering the potential to handle visual tasks in high-speed maneuvering scenarios. Existing event-based approaches, although successful in mitigating motion blur caused by high-speed maneuvers, suffer from many limitations. Some of them highlight a success of pose tracking for a fronto-parallel fast shaking camera closed to the structure, while others assume pure (optionally aggressive) three-degree-of-freedom rotations. The former requires persistent local map visibility within the field of view (FOV), whereas the latter fails to generalize to six-degree-of-freedom (6-DoF) motions where both linear and angular velocities may be large. Consequently, current successes do not fully demonstrate that event-based state estimation under arbitrary aggressive maneuvers is a fully solved problem. To quantitatively assess the extent to which the potential of event cameras has been unlocked, we conduct a thorough analysis of state-of-the-art (SOTA) event-based visual odometry (VO)/visual-inertial odometry (VIO) methods and report shortcomings in current public datasets. Furthermore, we introduce a benchmarking framework for event-based state estimation, called EvSLAM, characterized by sufficient variation in data collection platforms, diverse extreme lighting scenarios, and a wide scope of challenging motion patterns under a clear and rigorous definition of high-speed maneuvers for mobile robots, along with a novel evaluation metric designed to fairly assess the operational limits of event-based solutions. This framework benchmarks state-of-the-art methods, yielding insights into optimal architectures and persistent challenges.
### Title:
          Pushing Radar Odometry Beyond the Pavement: Current Capabilities and Challenges
 - **Authors:** Shaunak Kolhe, Peng Jiang, Maggie Wigness, Philip Osteen, Timothy Overbye, Chrisitan Ellis, Srikanth Saripalli
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar offers unique advantages for localization in unstructured environments, including robustness to weather, lighting, and airborne particulates. While most prior work has studied radar odometry in urban, largely planar settings, its performance in off-road environments remains less understood. In this paper, we investigate the potential of radar for off-road odometry estimation and identify key challenges that arise from full $SE(3)$ vehicle motion, terrain-induced ground returns, and sparse or unstable features. To address these issues, we introduce two simple baselines: Radar-KISSICP, which applies motion compensation to generate 3D-aware radar pointclouds, and Radar-IMU, which leverages IMU preintegration to stabilize scan matching. Experiments on the Great Outdoors (GO) dataset demonstrate that these baselines improve trajectory estimation in challenging routes and provide a reference point for future development of radar odometry in off-road robotics.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          GenAssets: Generating in-the-wild 3D Assets in Latent Space
 - **Authors:** Ze Yang, Jingkang Wang, Haowei Zhang, Sivabalan Manivasagam, Yun Chen, Raquel Urtasun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-quality 3D assets for traffic participants are critical for multi-sensor simulation, which is essential for the safe end-to-end development of autonomy. Building assets from in-the-wild data is key for diversity and realism, but existing neural-rendering based reconstruction methods are slow and generate assets that render well only from viewpoints close to the original observations, limiting their usefulness in simulation. Recent diffusion-based generative models build complete and diverse assets, but perform poorly on in-the-wild driving scenes, where observed actors are captured under sparse and limited fields of view, and are partially occluded. In this work, we propose a 3D latent diffusion model that learns on in-the-wild LiDAR and camera data captured by a sensor platform and generates high-quality 3D assets with complete geometry and appearance. Key to our method is a "reconstruct-then-generate" approach that first leverages occlusion-aware neural rendering trained over multiple scenes to build a high-quality latent space for objects, and then trains a diffusion model that operates on the latent space. We show our method outperforms existing reconstruction and generation based methods, unlocking diverse and scalable content creation for simulation.
### Title:
          Learning to Identify Out-of-Distribution Objects for 3D LiDAR Anomaly Segmentation
 - **Authors:** Simone Mosco, Daniel Fusaro, Alberto Pretto
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding the surrounding environment is fundamental in autonomous driving and robotic perception. Distinguishing between known classes and previously unseen objects is crucial in real-world environments, as done in Anomaly Segmentation. However, research in the 3D field remains limited, with most existing approaches applying post-processing techniques from 2D vision. To cover this lack, we propose a new efficient approach that directly operates in the feature space, modeling the feature distribution of inlier classes to constrain anomalous samples. Moreover, the only publicly available 3D LiDAR anomaly segmentation dataset contains simple scenarios, with few anomaly instances, and exhibits a severe domain gap due to its sensor resolution. To bridge this gap, we introduce a set of mixed real-synthetic datasets for 3D LiDAR anomaly segmentation, built upon established semantic segmentation benchmarks, with multiple out-of-distribution objects and diverse, complex environments. Extensive experiments demonstrate that our approach achieves state-of-the-art and competitive results on the existing real-world dataset and the newly introduced mixed datasets, respectively, validating the effectiveness of our method and the utility of the proposed datasets. Code and datasets are available at this https URL.
### Title:
          CLLAP: Contrastive Learning-based LiDAR-Augmented Pretraining for Enhanced Radar-Camera Fusion
 - **Authors:** Bingyi Liu, Chuanhui Zhu, Hongfei Xue, Jian Teng, Jipeng Liu, Enshu Wang, Penglin Dai, Pu Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D object detection is critical for autonomous driving, necessitating reliable, cost-effective sensors capable of operating in adverse weather conditions. Camera and millimeter-wave radar fusion has emerged as a promising solution; however, these methods often rely on finely annotated radar data, which is scarce and labor-intensive to produce. To address this challenge, we present CLLAP, a Contrastive Learning-based LiDAR-Augmented Pretraining framework that enhances the performance of existing radar-camera fusion methods for 3D object detection. CLLAP leverages abundant LiDAR data to generate pseudo-radar data using the proposed L2R (LiDAR-to-Radar) Sampling method. Then, it incorporates this data into a novel dual-stage, dual-modality contrastive learning strategy, enabling effective self-supervised learning from paired pseudo-radar and image data. This approach facilitates effective pretraining of existing radar-camera fusion models in a plug-and-play manner, enhancing their feature extraction capabilities and improving detection accuracy and robustness. Experimental results using NuScenes and Lyft Level 5 datasets demonstrate significant performance improvements across three baseline models, highlighting CLLAP's effectiveness in advancing radar-camera fusion for autonomous driving applications.
### Title:
          AsyncShield: A Plug-and-Play Edge Adapter for Asynchronous Cloud-based VLA Navigation
 - **Authors:** Kai Yang, Zedong Chu, Yingnan Guo, Zhengbo Wang, Shichao Xie, Yanfen Shen, Xiaolong Wu, Xing Li, Mu Xu
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Vision-Language-Action (VLA) models have been demonstrated possessing strong zero-shot generalization for robot control, their massive parameter sizes typically necessitate cloud-based deployment. However, cloud deployment introduces network jitter and inference latency, which can induce severe spatiotemporal misalignment in mobile navigation under continuous displacement, so that the stale intents expressed in past ego frames may become spatially incorrect in the current frame and lead to collisions. To address this issue, we propose AsyncShield, a plug-and-play asynchronous control framework. AsyncShield discards traditional black-box time-series prediction in favor of a deterministic physical white-box spatial mapping. By maintaining a temporal pose buffer and utilizing kinematic transformations, the system accurately converts temporal lag into spatial pose offsets to restore the VLA's original geometric intent. To balance intent restoration fidelity and physical safety, the edge adaptation is formulated as a constrained Markov decision process (CMDP). Solved via the PPO-Lagrangian algorithm, a reinforcement learning adapter dynamically trades off between tracking the VLA intent and responding to high-frequency LiDAR obstacle avoidance hard constraints. Furthermore, benefiting from a standardized universal sub-goal interface, domain randomization, and perception-level adaptation via Collision Radius Inflation, AsyncShield operates as a lightweight, plug-and-play module. Simulation and real-world experiments demonstrate that, without fine-tuning any cloud-based foundation models, the framework exhibits zero-shot and robust generalization capabilities, effectively improving the success rate and physical safety of asynchronous navigation.
### Title:
          Large-Scale Photogrammetric Documentation of St. John's Co-Cathedral: A Workflow for Cultural Heritage Preservation
 - **Authors:** Matthew Kenely, Mark Bugeja, Andre Grima, Peter Pullicino, Matthew Pullicino, Dylan Seychell
 - **Subjects:** Subjects:
Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a comprehensive methodology for the large-scale photogrammetric documentation of St. John's Co-Cathedral in Valletta, Malta, a UNESCO World Heritage site renowned for its ornate Baroque architecture and Caravaggio masterpieces. Over seven nights of evening-only data collection, we captured 99,000 images using DSLR cameras, drone photography, and LIDAR scanning to create a highly detailed 3D reconstruction comprising 25-30 billion triangles. This paper documents our complete workflow for cultural heritage preservation, addressing the unique challenges of digitizing complex baroque architectural spaces with highly reflective metallic surfaces, dark materials, intricate tapestries, and restricted access. We detail our pipeline from multi-modal data acquisition through processing, including strategic image grading and AI-assisted denoising to address low-light grain, extensive LIDAR point cloud cleanup, hybrid photogrammetric reconstruction using RealityCapture, and mesh subdivision strategies for real-time visualization engines. Our methodology combines automated workflows with necessary manual intervention to handle the scale and complexity of the project, with particular attention to reflective surface challenges characteristic of baroque heritage sites. We also present preliminary experiments with Gaussian splatting as a complementary representation technique. The resulting digital archive serves multiple preservation purposes including disaster recovery documentation, conservation analysis, virtual tourism, and scholarly research. This work provides a detailed, replicable workflow for heritage professionals undertaking similar large-scale architectural documentation projects, addressing the practical challenges of applying photogrammetric methods in complex real-world heritage scenarios.
### Title:
          Real-time windrow detection from onboard tractor sensors for automated following
 - **Authors:** Lorenz Gunreben, Nico Heider, Sebastian Zürner, Martin Schieck, Bogdan Franczyk
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Proprietary design in commercial windrow-detection systems restricts transparency and limits progress in open autonomous forage-harvesting research. We present a multi-modal dataset combining stereo vision and LiDAR from tractor-mounted sensors during real baling operations. The dataset includes synchronized sensor data with GNSS trajectories, partly released as ROS2 Humble bags on Zenodo, with additional data available on request. Using this dataset, we implement a real-time (>20 Hz) centroid-based windrow-following method on an NVIDIA Jetson AGX Orin. Across the critical 4-10 m guidance range, stereo and LiDAR depth measurements show strong agreement (0.965 +/- 0.021), indicating that low-cost stereo sensors can approach LiDAR performance. Our open-source ROS 2 pipeline provides a reproducible benchmark for GPS-free windrow detection and supports development of practical autonomous forage-harvesting systems. Dataset: this https URL
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          RadTwin: Generalizable Wireless Digital Twin for Dynamic Environments
 - **Authors:** Yuru Zhang, Ming Zhao, Qiang Liu, Ahmed Alkhateeb, Abhishek K. Agrawal, Qi Qu
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precisely modeling radio propagation in dynamic wireless environments is fundamental to the realization of wireless digital twins. Traditional ray tracing methods rely on accurate 3D models with detailed environment parameters, while recent neural radiance field approaches learn representations tied to specific static scenes, requiring retraining when environments change. In this paper, we propose RadTwin, a generalizable wireless digital twin framework that explicitly conditions on scene geometry, enabling adaptation to dynamic environments without retraining. RadTwin comprises three key components: 1) a scenario representation network that extracts high-level latent scene features from point clouds, 2) an electromagnetic ray tracing module that computes physics-informed sparse attention masks identifying voxels that physically contribute signals toward each query direction, and 3) a neural propagation decoder that aggregates relevant scene features through masked cross-attention to learn how radio propagation behaves within the given scene geometry. We evaluate RadTwin on a customized dataset of indoor scenes with varying furniture arrangements. Experimental results show that RadTwin achieves 31.6% higher SSIM (0.846 vs. 0.643) and 91.96% lower LPIPS (0.023 vs. 0.286) compared to NeRF2. RadTwin further demonstrates superior cross-scale performance and high generalization and data efficiency, representing a significant advancement toward practical digital network twins for dynamic wireless environments.
### Title:
          Multivariate Gaussian NeRF for Wide Field-of-View Ultrasound Reconstruction
 - **Authors:** Patris Valera, Magdalena Wysocki, Felix Duelmer, Mohammad Farid Azampour, Sebastian Herz, Stefan Wörz, Nassir Navab
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wide Field-of-View (WFoV) reconstruction enhances 3D ultrasound imaging by providing valuable anatomical context for segmentation models and visualization. Clinical ultrasound volumes are predominantly acquired using convex probes, which generate expanding, diverging acoustic beams to maximize anatomical coverage. Stitching these sweeps together traditionally introduces significant compounding artifacts and aliasing due to depth-dependent resolution changes. Here, we introduce Ultra-Wide-NeRF, a Multivariate 3D Gaussian (MVG) NeRF-based method for WFoV ultrasound reconstruction. By explicitly modeling the complex beam geometry using distance-dependent convex volumetric sampling and anisotropic 3D Gaussians, our method inherently mitigates these compounding artifacts and provides anti-aliasing. Beyond simply reconstructing a static 3D grid, our NeRF-based approach yields a continuous neural representation of the tissue, enabling the synthesis of high-fidelity novel views from arbitrary virtual trajectories. We validate Ultra-Wide-NeRF for intracardiac echocardiography on phantom and porcine datasets, demonstrating that our method expands the spatial context important in intraoperative navigation. Code will be open-sourced upon publication.
## Keyword: mapping
### Title:
          LunarDepthNet: Generation of Digital Elevation Models using Deep Learning and Monocular Satellite Images
 - **Authors:** Aaranay Aadi, Jai Gopal Singla, Amitabh, Nitant Dube, Praveen Kumar Shukla, Vijaypal Singh Dhaka
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent times have seen an increase in demand of high quality Digital Elevation Models (DEMs) for the lunar surface, because they are highly important for studying the moon and planning future missions. However, there is an evident lack of detailed elevation data on the Moon. To overcome this limitation, this study proposes a novel deep learning method that estimates and generates a surface elevation map directly from monocular images of the surface. The dataset used comprises of the Chandrayaan-2 Terrain Mapping Camera (TMC) images with their corresponding Digital Terrain Models (DTMs). The study proposes LunarDepthNet, which comprises of a UNet architecture to generate DEMS. It incorporates an EfficientNet encoder and custom layers to correctly learn how the light shadows on the surface relate to the actual elevation values. A combined loss function was also utilized to keep the terrain details accurate and smooth. During validation, the model showed a stable loss convergence of 12%. It achieved a mean nRMSE of 0.437 and an MAE of 4.5m in the testing stage. These results prove the model can generate dependable elevation maps from single orbital images, which are quite useful in regions of the moon where stereo-images are not available.
### Title:
          EgoDyn-Bench: Evaluating Ego-Motion Understanding in Vision-Centric Foundation Models for Autonomous Driving
 - **Authors:** Finn Rasmus Schäfer, Yuan Gao, Dingrui Wang, Thomas Stauner, Stephan Günnemann, Mattia Piccinini, Sebastian Schmidt, Johannes Betz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Vision-Language Models (VLMs) have advanced highlevel reasoning in autonomous driving, their ability to ground this reasoning in the underlying physics of ego-motion remains poorly understood. We introduce EgoDyn-Bench, a diagnostic benchmark for evaluating the semantic ego-motion understanding of vision-centric foundation models. By mapping continuous vehicle kinematics to discrete motion concepts via a deterministic oracle, we decouple a model's internal physical logic from its visual perception. Our large-scale empirical audit spanning 20 + models, including closed-source MLLMs, open-source VLMs across multiple scales, and specialized VLAs, identifies a significant Perception Bottleneck: while models exhibit logical physical concepts, they consistently fail to accurately align them with visual observations, frequently underperforming classical non-learned geometric baselines. This failure persists across model scales and domain-specific training, indicating a structural deficit in how current architectures couple visual perception with physical reasoning. We demonstrate that providing explicit trajectory encodings substantially restores physical consistency across all evaluated models, revealing a functional disentanglement between vision and language: egomotion logic is derived almost exclusively from the language modality, while visual observations contribute negligible additional signal. This structural finding provides a standardized diagnostic framework and a practical pathway toward physically aligned embodied AI. Keywords: Ego-motion - Physical Reasoning - Foundation Models
### Title:
          Magnetic Indoor Localization through CNN Regression and Rotation Invariance
 - **Authors:** Helge Rosé, Konstantin Klipp, Tom Koubek, Bernd Schäufele, Ilja Radusch
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Indoor positioning is an essential technology for a wide range of applications in GNSS-denied environments, including indoor navigation and IoT systems. Combining convolutional neural networks (CNNs) and magnetic field-based features offers a low-cost, infrastructure-free solution for precise positioning. While magnetic fingerprints are a promising approach for indoor positioning, models trained on raw 3D magnetometer data are highly sensitive to device orientation. We address this by using two rotation invariant features derived from the 3D magnetic field: the norm (Mn) and the projection onto the gravity axis (Mg). We train a lightweight 7-layer dilated CNN (MagNetS/XL) on magnetic sequences to directly regress (x, y) positions. Using the MagPie dataset (three buildings, handheld trajectories), we systematically evaluate fixed and random rotations of test and/or train data. Raw 3D inputs (Mx, My , Mz) exhibit isotropic error increases under fixed 90° rotations and further degrade with growing random rotations. In contrast, 2D (Mn, Mg) inputs maintain rotation invariant accuracy and surpass the 3D inputs once rotation exceeds building-specific thresholds for three reference buildings: 0° for Loomis (large), 5° for Talbot (medium), and 6° for CSL (small). MagNetXL achieves or exceeds state-of-the-art accuracy on the MagPie dataset, and MagNetS delivers similar performance with roughly one third of the parameters, favoring mobile deployment. These results show that the robustness gained from rotation invariant inputs outweighs the loss of input dimensionality in realistic usage, allowing mapping and localization without orientation alignment or added infrastructure.
### Title:
          Text-Guided Multimodal Unified Industrial Anomaly Detection
 - **Authors:** Zewen Li, Shuo Ye, Zitong Yu, Weicheng Xie, Linlin Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Industrial anomaly detection based on RGB-3D multimodal data has emerged as a mainstream paradigm for intelligent quality inspection. However, existing unsupervised methods suffer from two critical limitations: ambiguous cross-modal alignment caused by the lack of high-level semantic guidance and insufficient geometric modeling for RGB-to-3D feature mapping. To address these issues, we propose a unified multimodal industrial anomaly detection framework guided by text semantics. The framework consists of two core modules: a Geometry-Aware Cross-Modal Mapper to preserve geometric structure during modality conversion, and an Object-Conditioned Textual Feature Adaptor to align multimodal features with semantic priors. Furthermore, we establish a unified learning paradigm for multimodal industrial anomaly detection, which breaks the one-model-one-class constraint and enables accurate anomaly detection across diverse classes using a single model. Extensive experiments on the MVTec 3D-AD and Eyecandies datasets demonstrate that our method achieves state-of-the-art performance in classification and localization under unsupervised settings.
### Title:
          On the Complementarity of Quantum and Classical Features: Adaptive Hybrid Quantum-Classical Feature Fusion for Breast Cancer Classification
 - **Authors:** Yasmin Rodrigues Sobrinho, João Renato Ribeiro Manesco, João Paulo Papa
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The integration of quantum machine learning with classical deep learning offers promising avenues for medical image analysis by mapping data into high-dimensional Hilbert spaces. However, effectively unifying these distinct paradigms remains challenging due to common optimization asymmetries. In this paper, a novel hybrid quantum-classical architecture for breast cancer diagnosis based on a dual-branch feature-extraction pipeline is proposed. Our framework extracts and unifies complementary representations from classical models and quantum circuits, exploring both trainable and deterministic (non-trainable) quantum paradigms. To integrate these embeddings, three progressive feature fusion strategies are introduced: Static Hybrid Fusion (SHF) for offline extraction, Dynamic Hybrid Fusion (DHF) for end-to-end co-adaptation, and a novel Temperature-Scaled Hybrid Fusion (TSHF). The TSHF strategy incorporates a learnable scalar, inspired by multimodal learning, that dynamically balances hybrid gradient dynamics and resolves optimization bottlenecks. Empirical validation on the BreastMNIST dataset confirms our hypothesis that unifying diverse feature representations creates a richer data context. The TSHF strategy, specifically when pairing a ResNet backbone with a trainable quantum circuit, achieved a peak accuracy of 87.82%, F1-score of 91.77%, and an AUC-ROC of 89.08%, outperforming purely classical baselines. These results demonstrate that the proposed hybrid framework improves classification accuracy and threshold reliability, providing a stable, high-performance architecture for the clinical deployment of quantum-enhanced diagnostic tools.
### Title:
          Network Edge Inference for Large Language Models: Principles, Techniques, and Opportunities
 - **Authors:** Zhixiong Chen, Bingjie Zhu, Jiangzhou Wang, Hyundong Shin, Arumugam Nallanathan, Dusit Niyato
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) have advanced rapidly, emerging as versatile tools across fields thanks to their exceptional language understanding, generation, and reasoning capabilities. However, performing LLM inference at the network edge remains challenging due to their large memory and compute demands. This survey outlines the challenges specific to LLM edge inference and provides a comprehensive overview of recent progress, covering system architectures, model optimization and deployment, and resource management and scheduling. By synthesizing state-of-the-art techniques and mapping future directions, this survey aims to unlock the potential of LLMs in resource-constrained edge environments.
### Title:
          Towards Causally Interpretable Wi-Fi CSI-Based Human Activity Recognition with Discrete Latent Compression and LTL Rule Extraction
 - **Authors:** Luca Cotti, Luca Lavazza, Marco Cominelli, Liying Han, Gaofeng Dong, Francesco Gringoli, Mani B. Srivastava, Trevor Bihl, Erik P. Blasch, Daniel O. Brigham, Kara Combs, Lance M. Kaplan, Federico Cerutti
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We address Human Activity Recognition (HAR) utilizing Wi-Fi Channel State Information (CSI) under the joint requirements of causal interpretability, symbolic controllability, and direct operation on high-dimensional raw signals. Deep neural models achieve strong predictive performance on CSI-based HAR (CHAR), yet rely on continuous latent representations that are opaque and difficult to modify; purely symbolic approaches, in contrast, cannot process raw CSI streams. We propose a fully automatic and strictly decoupled pipeline in which CSI magnitude windows are compressed by a categorical variational autoencoder with Gumbel-Softmax latent variables under a capacity-controlled objective, yielding a compact discrete representation. The encoder is then frozen and used as a deterministic mapping to one-hot latent trajectories. Causal discovery is performed on these trajectories to estimate class-conditional temporal dependency graphs. Statistically supported lagged dependencies are translated into Linear Temporal Logic (LTL) rules, producing a fully symbolic and deterministic classifier based solely on rule evaluation and aggregation, without any learned discriminative head. Because rules are defined over discrete latent variables, antenna-specific rule sets can in principle be combined at the symbolic level, enabling structured multi-antenna fusion without retraining the encoder. Results from CHAR Latent Temporal Rule Extraction (CHARL-TRE) indicate competitive performance while preserving explicit temporal and causal structure, showing that deterministic symbolic classification grounded in unsupervised discrete latent representations constitutes a viable alternative to end-to-end black-box models for wireless HAR.
### Title:
          Urban Flood Observations (UFO): A hand-labeled training and validation dataset of post-flood inundation
 - **Authors:** Rohit Mukherjee, Hannah K. Friedrich, Beth Tellman, Ariful Islam, Zhijie Zhang, Jonathan Giezendanner, Upmanu Lall, Venkataraman Lakshmi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Urban flooding affects lives and infrastructure worldwide. Mapping inundation in complex urban environments from satellite imagery remains challenging due to limited spatial resolution, infrequent acquisitions, and cloud cover. We present Urban Flood Observations (UFO), a global, hand-labeled dataset of post-flood inundation in diverse urban settings. UFO comprises 215 image chips (1024 by 1024 pixels) from 14 flood events between 2017 and 2021, derived from 3 m PlanetScope imagery. Each chip is annotated with two classes: 'inundated' (all visible surface water, including floodwater and pre-existing water bodies (permanent or seasonal)) and 'non-inundated'. To demonstrate the dataset's utility, we trained a segmentation model using leave-one-event-out cross-validation, achieving a mean Intersection over Union (IoU) of 77.3. We also used UFO to evaluate two widely used surface water products, the Sentinel-1-based NASA IMPACT model and Google's 10 m Dynamic World water class, which yielded IoUs of 44.1 and 48.1, respectively. UFO is publicly available to support the development and validation of urban inundation mapping methods.
### Title:
          Learning the Weather-Grid Nexus via Weather-to-Voltage (W2V) Predictive Modeling
 - **Authors:** Sol Lim, Min-Seung Ko, Farnaz Safdarian, Hao Zhu
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes a weather-to-voltage (W2V) predictive modeling framework to learn the underlying weather-grid nexus. Unlike existing approaches on weather-informed grid operations, our proposed W2V model can achieve the joint analysis of weather and grid states, and further leverage this coupling to enhance grid-aware weather forecasting (GAWF) as a key application. To achieve this end-to-end learning, the W2V model acts as a differentiable surrogate for weather-incorporated power flow analysis by mapping weather features at high spatial resolution directly to grid-wide bus voltages. Thanks to a compact neural network design and principal component analysis based initialization, it achieves high voltage prediction accuracy and numerical stability during training. Building on this capability, W2V-based voltage signals are used to guide the development of GAWF that can account for its downstream voltage prediction performance. Using a 6717-bus Texas synthetic test system with meteorological inputs from 701 weather locations, our numerical tests have verified the excellent accuracy and generalizability of the proposed W2V model. More importantly, the W2V model has enabled the GAWF to effectively prioritize the weather features and conditions that are most critical to grid operations, such as system-wide quick wind drops preceding ramp-ups.
### Title:
          ProEval: Proactive Failure Discovery and Efficient Performance Estimation for Generative AI Evaluation
 - **Authors:** Yizheng Huang, Wenjun Zeng, Aditi Kumaresan, Zi Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Evaluating generative AI models is increasingly resource-intensive due to slow inference, expensive raters, and a rapidly growing landscape of models and benchmarks. We propose ProEval, a proactive evaluation framework that leverages transfer learning to efficiently estimate performance and identify failure cases. ProEval employs pre-trained Gaussian Processes (GPs) as surrogates for the performance score function, mapping model inputs to metrics such as the severity of errors or safety violations. By framing performance estimation as Bayesian quadrature (BQ) and failure discovery as superlevel set sampling, we develop uncertainty-aware decision strategies that actively select or synthesize highly informative inputs for testing. Theoretically, we prove that our pre-trained GP-based BQ estimator is unbiased and bounded. Empirically, extensive experiments on reasoning, safety alignment, and classification benchmarks demonstrate that ProEval is significantly more efficient than competitive baselines. It requires 8-65x fewer samples to achieve estimates within 1% of the ground truth, while simultaneously revealing more diverse failure cases under a stricter evaluation budget.
### Title:
          h-MINT: Modeling Pocket-Ligand Binding with Hierarchical Molecular Interaction Network
 - **Authors:** Yanru Qu, Yijie Zhang, Wenjuan Tan, Xiangzhe Kong, Xiangxin Zhou, Chaoran Cheng, Mathieu Blanchette, Jiaxuan You, Ge Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate molecular representations are critical for drug discovery, and a central challenge lies in capturing the chemical environment of molecular fragments, as key interactions, such as H-bond and {\pi} stacking, occur only under specific local conditions. Most existing approaches represent molecules as atom-level graphs; however, atom-level representations can hardly express higher-order chemical context (e.g., stereochemistry, lone pairs, conjugation). Fragment-based methods (e.g., principal subgraph, predefined functional groups) fail to preserve essential information such as chirality, aromaticity, and ionic states. This work addresses these limitations from two aspects. (i) OverlapBPE tokenization. We propose a novel data-driven molecule tokenization method. Unlike existing approaches, our method allows overlapping fragments, reflecting the inherently fuzzy boundaries of small-molecule substructures and, together with enriched chemical information at the token level, thereby preserving a more complete chemical context. (ii) h-MINT model. OverlapBPE induces many-to-many atom-fragment mappings, which necessitate a new hierarchical architecture. We therefore develop a hierarchical molecular interaction network capable of jointly modeling interactions at both atom and fragment levels. By supporting fragment overlaps, the model naturally accommodates the many-to-many atom-fragment mappings introduced by the OverlapBPE scheme. Extensive evaluation against state-of-the-art methods shows our method improves binding affinity prediction by 2-4% Pearson/Spearman correlation on PDBBind and LBA, enhances virtual screening by 1-3% in key metrics on DUD-E and LIT-PCBA, and achieves the best overall HTS performance on PubChem assays. Further analysis demonstrates that our method effectively captures interactive information while maintaining good generalization.
### Title:
          A satellite foundation model for improved wealth monitoring
 - **Authors:** Zhuo Zheng, Iván Higuera-Mendieta, Richard Lee, David Newhouse, Talip Kilic, Stefano Ermon, Marshall Burke, David B. Lobell
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Poverty statistics guide social policy, but in many low- and middle-income countries, censuses and household surveys that collect these data are costly, infrequent, quickly outdated, and sometimes error-prone. Satellite imagery offers global coverage and the possibility of predicting economic livelihoods at scale, yet existing approaches to predicting livelihoods with imagery or other non-traditional data often fail to reliably identify local-level variation and, as we show, degrade under temporal shift. Here we introduce Tempov, a satellite foundation model pretrained by self-supervision on three million bi-temporal Landsat pairs and adapted with parameter-efficient fine-tuning to sparse survey labels. The model enables large-scale, high-resolution wealth mapping and dynamic measurement, including zero-shot nowcasting up to a decade after observed labels, retrospective hindcasting, and decadal change tracking, while outperforming existing neural network and geospatial foundation-model baselines. In low-label regimes, Tempov achieves competitive accuracy with only 10% of survey samples, indicating substantially reduced dependence on expensive label collection. The model further generalizes across populous countries within and outside Africa, and scales to a unified Africa-wide model with strong continent-level performance ($R^2=0.63$, $r^2=0.68$), from which we generate high-resolution decadal maps of wealth and wealth changes for the African continent. Analysis of these maps shows large variation in recent economic performance both within and across countries. Our open-source approach provides a pathway to timely, scalable, low-cost monitoring of wealth and poverty from routinely collected satellite data.
### Title:
          AnalogRetriever: Learning Cross-Modal Representations for Analog Circuit Retrieval
 - **Authors:** Yihan Wang, Lei Li, Yao Lai, Jing Wang, Yan Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Analog circuit design relies heavily on reusing existing intellectual property (IP), yet searching across heterogeneous representations such as SPICE netlists, schematics, and functional descriptions remains challenging. Existing methods are largely limited to exact matching within a single modality, failing to capture cross-modal semantic relationships. To bridge this gap, we present AnalogRetriever, a unified tri-modal retrieval framework for analog circuit search. We first build a high-quality dataset on top of Masala-CHAI through a two-stage repair pipeline that raises the netlist compile rate from 22\% to 100\%. Built on this foundation, AnalogRetriever encodes schematics and descriptions with a vision-language model and netlists with a port-aware relational graph convolutional network, mapping all three modalities into a shared embedding space via curriculum contrastive learning. Experiments show that AnalogRetriever achieves an average Recall@1 of 75.2\% across all six cross-modal retrieval directions, significantly outperforming existing baselines. When integrated into the AnalogCoder agentic framework as a retrieval-augmented generation module, it consistently improves functional pass rates and enables previously unsolved tasks to be completed. Our code and dataset will be released.
### Title:
          Robust Audio-Text Retrieval via Cross-Modal Attention and Hybrid Loss
 - **Authors:** Meizhu Liu, Matthew Rowe, Amit Agarwal, Michael Avendi, Yassi Abbasi, Hitesh Laxmichand Patel, Paul Li, Kyu J. Han, Tao Sheng, Sujith Ravi, Dan Roth
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio-text retrieval enables semantic alignment between audio content and natural language queries, supporting applications in multimedia search, accessibility, and surveillance. However, current state-of-the-art approaches struggle with long, noisy, and weakly labeled audio due to their reliance on contrastive learning and large-batch training. We propose a novel multimodal retrieval framework that refines audio and text embeddings using a cross-modal embedding refinement module combining transformer-based projection, linear mapping, and bidirectional attention. To further improve robustness, we introduce a hybrid loss function blending cosine similarity, $\mathcal{L}_{1}$, and contrastive objectives, enabling stable training even under small-batch constraints. Our approach efficiently handles long-form and noisy audio (SNR 5 to 15) via silence-aware chunking and attention-based pooling. Experiments on benchmark datasets demonstrate improvements over prior methods.
### Title:
          Constraint-Based Analysis of Reasoning Shortcuts in Neurosymbolic Learning
 - **Authors:** Akihiro Takemura, Katsumi Inoue, Masaaki Nishino
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neurosymbolic systems can satisfy logical constraints during learning without achieving the intended concept-label correspondence; this is a problem known as reasoning shortcuts. We formalize reasoning shortcuts as a constraint satisfaction problem and investigate under which conditions concept mappings are uniquely determined by the constraints. We prove that a discrimination property (requiring that no valid concept mapping can be transformed into another valid mapping by swapping two concept values) is necessary for shortcut-freeness under bijective mappings, but demonstrate via a counterexample that it is insufficient even when the constraint graph is connected. We develop an ASP-based algorithm that verifies whether a given constraint set uniquely determines the intended concept mapping, with proven soundness and completeness. When shortcuts are detected, a greedy repair algorithm eliminates them by augmenting the constraint set, converging in at most $k$ iterations, where $k$ is the number of alternative valid mappings. We further provide a complexity classification: deciding shortcut-freeness is coNP-complete, counting shortcuts is #P-complete, and finding minimal repairs is NP-hard. We also establish sample complexity bounds showing that logarithmically many label queries suffice for disambiguation in favorable cases, while querying all ambiguous positions suffices in the worst case. Experiments across eight benchmark domains validate our approach.
### Title:
          Keypoint-based Dynamic Object 6-DoF Pose Tracking via Event Camera
 - **Authors:** Zhe Wang, Qijin Song, Zihao Li, Jingyu Xiao, Weibang Bai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 6-DoF pose estimation of objects is critical for robots to perform precise manipulation tasks. However, for dynamic object pose estimation, conventional camera-based approaches face several major challenges, such as motion blur, sensor noise, and low-light limitation. To address these issues, we employ event cameras, whose high dynamic range and low latency offer a promising solution. Furthermore, we propose a keypoint-based detection and tracking approach for dynamic object pose estimation. Firstly, a keypoint detection network is constructed to extract keypoints from the time surface generated by the event stream. Subsequently, the polarity and spatial coordinates of the events are leveraged, and the event density in the vicinity of each keypoint is utilized to achieve continuous keypoint tracking. Finally, a hash mapping is established between the 2D keypoints and the 3D model keypoints, and the EPnP algorithm is employed to estimate the 6-DoF pose. Experimental results demonstrate that, whether in simulated or real event environments, the proposed method outperforms the event-based state-of-the-art methods in terms of both accuracy and robustness.
### Title:
          SEMA-SQL: Beyond Traditional Relational Querying with Large Language Models
 - **Authors:** Yin Lin, Tianjing Zeng, Zhongjun Ding, Rong Zhu, Bolin Ding, H. V. Jagadish, Jingren Zhou
 - **Subjects:** Subjects:
Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Relational databases excel at structured data analysis, but real-world queries increasingly require capabilities beyond standard SQL, such as semantically matching entities across inconsistent names, extracting information not explicitly stored in schemas, and analyzing unstructured text. While text-to-SQL systems enable natural language querying, they remain limited to relational operations and cannot leverage the semantic reasoning capabilities of modern large language models (LLMs). Conversely, recent semantic operator systems extend relational algebra with LLM-powered operations (e.g., semantic joins, mappings, aggregations), but require users to manually construct complex query pipelines. To address this gap, we present SEMA-SQL, a system that automatically answers natural language questions by generating efficient queries that combine relational operations with LLM semantic reasoning. We formalize Hybrid Relational Algebra (HRA), a declarative abstraction unifying traditional relational operators with LLM user-defined functions (UDFs). The system automates three critical aspects: (1) query generation via in-context learning that produces HRA queries with precise natural language specifications for LLM UDFs, (2) query optimization via cost-based transformations and UDF rewriting, and (3) efficient execution algorithms that reduce LLM invocations by an average of 93% in semantic joins through intelligent batching. Extensive experiments with known benchmarks, and extensions thereof, demonstrate the significant query capability improvements possible with our design.
### Title:
          Do Transaction-Level and Actor-Level AML Queues Agree? An Empirical Evaluation of Granularity Effects on the Elliptic++ Graph
 - **Authors:** Ankur Malik
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph-based anti-money laundering (AML) systems on blockchain networks can score suspicious activity at two granularity levels -- transactions or actor addresses -- yet compliance action is conducted per actor. This paper contributes an evaluation methodology for measuring how scoring granularity affects investigation queue composition under fixed review budgets. We formalize the evaluation through a projection framework mapping transaction-level scores to the actor-level action unit via four aggregation operators, and introduce budgeted investigation metrics -- yield@budget, burden decomposition, and case fragmentation. Using the public Elliptic++ Bitcoin dataset (203,769 transactions; 822,942 address occurrences), we train independent random forest classifiers at each level under a causal temporal protocol and compare review queues through Jaccard overlap, burden decomposition, and feature-matching ablations. At one-percent budget, temporal evaluation yields mean Jaccard of 0.374 (SD 0.171); static pooled evaluation yields 0.087 (95% CI [0.079, 0.094]). An enriched address model receiving all 237 features produces even lower overlap (Jaccard=0.051), with 4.3% illicit per 100 reviews versus 30.2% for the transaction-projected queue. Address-level detection value is temporally concentrated: two timesteps exceed 91% illicit per 100 reviews while the static burden is only 3.4%. A fixed hybrid policy underperforms the best single-level queue by 5.05pp (CI [-10.2pp, -0.9pp]). These findings establish that scoring granularity is a consequential design variable for AML investigation systems -- same data, same budget, different queues, different addresses investigated.
### Title:
          Safeguarding Skies: Airport Cybersecurity in the Digital Age
 - **Authors:** Suphannee Sivakorn, Nuttaya Rujiratanapat, Yotsapat Ruangpaisarn, Chanond Duangpayap, Sakulchai Saramat
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The aviation industry faces significant vulnerabilities from both physical and cybersecurity threats, highlighting the urgent need for enhanced cybersecurity measures amid increasingly sophisticated attacks. This paper systematically reviews emerging threats at airports, analyzing real-world incidents and relevant literature while mapping risks to the MITRE ATT&CK Matrix, a widely recognized knowledge base for categorizing cyberattack tactics, techniques, and procedures. This is the first to apply the MITRE Matrix to airport security risks, offering a novel approach to understanding and mitigating these challenges. Building on this analysis, the paper advocates for modern cybersecurity defense models, emphasizing Cybersecurity Frameworks and Zero Trust Architecture, as well as critical measures for supply chain risk management and strategies to mitigate ransomware and DoS attacks. Our analysis provides insights into vulnerabilities and actionable recommendations, serving as a comprehensive guide for aviation stakeholders to strengthen defenses against evolving cybersecurity threats.
### Title:
          Opening the Design Space: Two Years of Performance with Intelligent Musical Instruments
 - **Authors:** Charles Patrick Martin
 - **Subjects:** Subjects:
Sound (cs.SD); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Machine generation of symbolic music and digital audio are hot topics but there have been relatively few digital musical instruments that integrate generative AI. Present musical AI tools are not artist centred and do not support experimentation or integrating into musical instruments or practices. This work introduces an inexpensive generative AI instrument platform based on a single board computer that connects via MIDI to other musical devices. The platform uses artist-collected datasets with models trained on a regular computer. This paper asks what the design space of intelligent musical instruments might look like when accessible and portable AI systems are available for artistic exploration. I contribute five examples of instruments created and tested through a two-year first-person artistic research process. These show that (re)mapping can replace retraining for discovering AI interaction, that fast input interleaving is a new co-creative strategy, that small-data AI models can be a transportable design resource, and that cheap hardware can lower barriers to inclusion. This work could enable artists to explore new interaction and performance schemes with intelligent musical instruments.
### Title:
          SolarFCD: A Large-Scale Dataset and Benchmark for Solar Fault Classification in Photovoltaic Systems
 - **Authors:** Misbah Ijaz, Saif Ur Rehman Khan, Abd Ur Rehman, Arooj Zaib, Sebastian Vollmer, Andreas Dengel, Muhammad Nabeel Asim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The increasing global deployment of solar photovoltaic (PV) systems needs robust, scalable, and automated inspection technologies capable of detecting a wide range of panel flaws under a variety of operating situations. The lack of large-scale, multi-modal, publicly available annotated datasets is a major obstacle preventing advancement in this field. We introduce SolarFCD, an extensive dataset of solar panel defects created by methodically combining and reconciling three publicly accessible datasets covering two imaging modalities: RGB/Drone images and Thermal Infrared. The dataset consist of 4,435 images arranged under four unified defect classes such as: healthy images, Surface Obstruction, structural fault, and electrical fault. The dataset was divided into training, validation, and test splits at an 80:10:10 ratio through methodical label mapping, near-duplicate removal, and targeted augmentation of minority classes. Sixteen classification architectures from five design families were trained and assessed on the dataset to provide repeatable benchmark baselines. With an accuracy of 86.68%, precision of 88.65%, recall of 88.62%, and F1-score of 88.17%, ResNet101V2 performed the best overall. Per-class results showed balanced detection across all four defect categories within a narrow performance band of less than 1.2 percentage points. To promote open and repeatable research in automated PV inspection and solar energy operations and maintenance, the dataset, annotation files, and baseline code are made openly available.
### Title:
          Quasi-Equivariant Metanetworks
 - **Authors:** Viet-Hoang Tran, An Nguyen, Benoît Guérand, Thieu N. Vo, Tan M. Nguyen
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Metanetworks are neural architectures designed to operate directly on pretrained weights to perform downstream tasks. However, the parameter space serves only as a proxy for the underlying function class, and the parameter-function mapping is inherently non-injective: distinct parameter configurations may yield identical input-output behaviors. As a result, metanetworks that rely solely on raw parameters risk overlooking the intrinsic symmetries of the architecture. Reasoning about functional identity is therefore essential for effective metanetwork design, motivating the development of equivariant metanetworks, which incorporate equivariance principles to respect architectural symmetries. Existing approaches, however, typically enforce strict equivariance, which imposes rigid constraints and often leads to sparse and less expressive models. To address this limitation, we introduce the novel concept of quasi-equivariance, which allows metanetworks to move beyond the rigidity of strict equivariance while still preserving functional identity. We lay down a principled basis for this framework and demonstrate its broad applicability across diverse neural architectures, including feedforward, convolutional, and transformer networks. Through empirical evaluation, we show that quasi-equivariant metanetworks achieve good trade-offs between symmetry preservation and representational expressivity. These findings advance the theoretical understanding of weight-space learning and provide a principled foundation for the design of more expressive and functionally robust metanetworks.
### Title:
          Inverting Foundation Models of Brain Function with Simulation-Based Inference
 - **Authors:** Niels Bracher, Xavier Intes, Stefan T. Radev
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation models of brain activity promise a new frontier for in silico neuroscience by emulating neural responses to complex stimuli across tasks and modalities. A natural next step is to ask whether these models can also be used in reverse. Can we recover a stimulus or its properties from synthetic brain activity? We study this question in a proof-of-concept setting using TRIBEv2. We pair the brain emulator with large language models (LLMs) that generate news headlines from linguistic parameters such as valence, arousal, and dominance. We then use simulation-based inference to learn a probabilistic mapping from brain maps to latent stimulus parameters. Our results show that these parameters can be recovered from predicted brain maps, validating the quality of neural encodings. They also show that LLMs can serve as controllable stimulus generators for simulated experiments. Together, these findings provide a step toward decoding and inverse design with foundation brain models.
### Title:
          SMSI: System Model Security Inference: Automated Threat Modeling for Cyber-Physical Systems
 - **Authors:** RoÝah Radaideh, Ali Khreis
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Threat modeling for cyber-physical systems (CPS) remains a largely manual exercise. This project presents SMSI (System Model Security Inference), a hybrid neuro-symbolic pipeline that starts from a SysML architecture model and produces a prioritized list of NIST 800-53 security controls. The prototype has three main stages: a deterministic parser mapping system components to vulnerabilities via the NVD; a family of retrieval and classification models linking vulnerabilities to MITRE ATT&CK techniques; and a control recommender. We explore three approaches for CVE-to-ATT&CK mapping: a supervised classifier using fine-tuned SecureBERT+, retrieval-based dense encoders, and a zero-shot LLM approach using Gemma-4 26B. We validate the pipeline on a healthcare IoT gateway with nine software components. For the ATT&CK-to-NIST stage, pretrained SecureBERT achieves the highest control retrieval scores, demonstrating that dense embeddings provide a strong basis for automated control recommendation.
### Title:
          Failure-Centered Runtime Evaluation for Deployed Trilingual Public-Space Agents
 - **Authors:** M. Meng
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents PSA-Eval, a failure-centered runtime evaluation framework for deployed trilingual public-space agents. The central claim is that, when the evaluation object shifts from a static input-output mapping to a runtime system, the basic unit of analysis should shift from score to failure. PSA-Eval extends the conventional chain Question -> Answer -> Score -> End into Question -> Batch -> Run -> Score -> Failure Case -> Repair -> Regression Batch, making failures traceable, reviewable, repairable, and regression-testable. The framework uses trilingual equivalent inputs as controlled probes for observing group-level cross-language policy drift. We conduct a pilot study on a real trilingual digital front-desk system deployed in the lobby of an international financial institution. The pilot uses a simplified single-foundation-model setting (MA = MB), so the observed drift should not be interpreted as an A/B foundation-model difference. The study contains 81 samples organized into 27 trilingual equivalent question groups. Although the system achieves an average score of 23.15/24, 14 groups show non-zero cross-language score drift, 5 groups show drift of at least 3 points, and the maximum drift reaches 9 points. These results provide initial evidence that failure-centered runtime evaluation can expose structured deployment signals hidden by aggregate scoring.
### Title:
          EPM-RL: Reinforcement Learning for On-Premise Product Mapping in E-Commerce
 - **Authors:** Minhyeong Yu, Wonduk Seo
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Databases (cs.DB); Machine Learning (cs.LG); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Product mapping, the task of deciding whether two e-commerce listings refer to the same product, is a core problem for price monitoring and channel visibility. In real marketplaces, however, sellers frequently inject promotional keywords, platform-specific tags, and bundle descriptions into titles, causing the same product to appear under many different names. Recent LLM-based and multi-agent frameworks improve robustness and interpretability on such hard cases, but they often rely on expensive external APIs, repeated retrieval, and complex inference-time orchestration, making large-scale deployment costly and difficult in privacy-sensitive enterprise settings. To address these issues, we present EPM-RL, a reinforcement-learning-based framework for building an accurate and efficient on-premise e-commerce product mapping model. Our central idea is to distill high-cost agentic reasoning into a trainable in-house model. Starting from a curated set of product pairs with LLM-generated rationales and human verification, we first perform parameter-efficient fine-tuning (PEFT) on a small student model using structured reasoning outputs. We then further optimize the model with Reinforcement Learning (RL) using an agent-based reward that jointly evaluates output-format compliance, label correctness, reasoning--preference scores from specially designed judge models. Preliminary results show that EPM-RL consistently improves over PEFT-only training and offers a stronger quality--cost trade-off than commercial API-based baselines, while enabling private deployment and lower operational cost. These findings suggest that reinforcement learning can turn product mapping from a high-latency agentic pipeline into a scalable, inspectable, and production-ready in-house system.
### Title:
          Breaking the Scalability Limit of Multi-Projector Calibration with Embedded Cameras
 - **Authors:** Takumi Kawano, Kohei Miura, Daisuke Iwai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Conventional multi-projector calibration requires projecting and capturing structured light patterns for each projector sequentially, causing calibration time and effort to increase linearly with the number of projectors. This scalability bottleneck has long limited the deployment of large-scale projection mapping systems. We present a new calibration framework that breaks this limitation by embedding cameras into the surface of the calibration target. The embedded cameras directly capture the incoming projection light, enabling the separation of simultaneously projected structured light patterns from multiple projectors according to their incident directions. Our method establishes correspondences between the optical centers of the embedded cameras and the projector pixels, allowing the intrinsic and extrinsic parameters of all projectors to be simultaneously estimated. We further introduce a correction technique for small misalignments between the calibration board and camera optical centers. As a result, our system achieves calibration accuracy comparable to conventional methods while reducing the required number of projection-capture cycles from linear to nearly constant with respect to the number of projectors, dramatically improving scalability for dense multi-projector systems with overlapping projection regions, such as high-brightness stacking, super-resolution, light-field, and shadow-suppression displays.
### Title:
          Grounding Before Generalizing: How AI Differs from Humans in Causal Transfer
 - **Authors:** Liangru Xiang, Yuxi Ma, Zhihao Cao, Yixin Zhu, Song-Chun Zhu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Extracting abstract causal structures and applying them to novel situations is a hallmark of human intelligence. While Large Language Models (LLMs) and Vision Language Models (VLMs) have shown strong performance on a wide range of reasoning tasks, their capacity for interactive causal learning -- inducing latent structures through sequential exploration and transferring them across contexts -- remains uncharacterized. Human learners accomplish such transfer after minimal exposure, whereas classical Reinforcement Learning (RL) agents fail catastrophically. Whether state-of-the-art Artificial Intelligence (AI) models possess human-like mechanisms for abstract causal structure transfer is an open question. Using the OpenLock paradigm requiring sequential discovery of Common Cause (CC) and Common Effect (CE) structures, here we show that models exhibit fundamentally delayed or absent transfer: even successful models require initial environmental-specific mapping -- what we term environmental grounding -- before efficiency gains emerge, whereas humans leverage prior structural knowledge from the very first solution attempt. In the text-only condition, models matched or exceeded human discovery efficiency. In contrast, visual information -- in both the image-only and text-and-image conditions -- overall degraded rather than enhanced performance, revealing a broad reliance on symbolic processing rather than integrated multimodal reasoning. Models further exhibited systematic CC/CE asymmetries absent in humans, suggesting heuristic biases rather than direction-neutral causal abstraction. These findings reveal that large-scale statistical learning does not produce the decontextualized causal schemas underpinning human analogical reasoning, establishing grounding-dependent transfer as a fundamental limitation of current LLMs and VLMs.
### Title:
          AsyncShield: A Plug-and-Play Edge Adapter for Asynchronous Cloud-based VLA Navigation
 - **Authors:** Kai Yang, Zedong Chu, Yingnan Guo, Zhengbo Wang, Shichao Xie, Yanfen Shen, Xiaolong Wu, Xing Li, Mu Xu
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Vision-Language-Action (VLA) models have been demonstrated possessing strong zero-shot generalization for robot control, their massive parameter sizes typically necessitate cloud-based deployment. However, cloud deployment introduces network jitter and inference latency, which can induce severe spatiotemporal misalignment in mobile navigation under continuous displacement, so that the stale intents expressed in past ego frames may become spatially incorrect in the current frame and lead to collisions. To address this issue, we propose AsyncShield, a plug-and-play asynchronous control framework. AsyncShield discards traditional black-box time-series prediction in favor of a deterministic physical white-box spatial mapping. By maintaining a temporal pose buffer and utilizing kinematic transformations, the system accurately converts temporal lag into spatial pose offsets to restore the VLA's original geometric intent. To balance intent restoration fidelity and physical safety, the edge adaptation is formulated as a constrained Markov decision process (CMDP). Solved via the PPO-Lagrangian algorithm, a reinforcement learning adapter dynamically trades off between tracking the VLA intent and responding to high-frequency LiDAR obstacle avoidance hard constraints. Furthermore, benefiting from a standardized universal sub-goal interface, domain randomization, and perception-level adaptation via Collision Radius Inflation, AsyncShield operates as a lightweight, plug-and-play module. Simulation and real-world experiments demonstrate that, without fine-tuning any cloud-based foundation models, the framework exhibits zero-shot and robust generalization capabilities, effectively improving the success rate and physical safety of asynchronous navigation.
### Title:
          Open-Vocabulary Semantic Segmentation Network Integrating Object-Level Label and Scene-Level Semantic Features for Multimodal Remote Sensing Images
 - **Authors:** Jinkun Dai, Yuanxin Ye, Peng Tang, Tengfeng Tang, Xianping Ma, Jing Xiao, Mi Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic segmentation of multi-modal remote sensing imagery plays a pivotal role in land use/land cover (LULC) mapping, environmental monitoring, and precision earth observation. Current multi-modal approaches mainly focus on integrating complementary visual modalities, yet neglect the incorporating of non-visual textual data - a rich source of knowledge that can bridge semantic gaps between visual patterns and real-world concepts. To address this limitation, we propose TSMNet, a text supervised multi-modal open vocabulary semantic segmentation network that synergistically integrates textual supervision with visual representation for open-vocabulary semantic segmentation. Unlike conventional multi-modal segmentation frameworks, TSMNet introduces a dual-branch text encoder to extract both scene-level semantic and object-level label information from various textual data, enabling dynamic cross-modal fusion. These text-derived features dynamically interact with visual embeddings through the proposed text-guided visual semantic fusion module, enabling domain-aware feature refinement and human-interpretable decision-making. To verify our method, we innovatively construct two new multi-modal datasets, and carry out extensive experiments to make a comprehensive comparison between the proposed method and other state-of-the-art (SOTA) semantic segmentation models. Results demonstrate that TSMNet achieves superior segmentation accuracy while exhibiting robust generalization capabilities across diverse geographical and sensor-specific scenarios. This work establishes a new paradigm for explainable remote sensing analysis, demonstrating that textual knowledge integration significantly enhances model generalizability. The source code will be available at this https URL
### Title:
          Progressive Approximation in Deep Residual Networks: Theory and Validation
 - **Authors:** Wei Wang, Xiao-Yong Wei, Qing Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Universal Approximation Theorem (UAT) guarantees universal function approximation but does not explain how residual models distribute approximation across layers. We reframe residual networks as a layer-wise approximation process that builds an approximation trajectory from input to target, and prove the existence of progressive trajectories where error decreases monotonically with depth. It reveals that residual networks can implement structured, step-by-step refinement rather than end-to-end (E2E) black-box mapping. Building on this, we propose Layer-wise Progressive Approximation (LPA), a theoretically grounded training principle that explicitly aligns each layer with its residual target to realize such trajectories. LPA is architecture-agnostic: we observe progressive behavior in residual FNNs, ResNets, and Transformers across tasks including complex surface fitting, image classification, and NLP with LLMs for generation and classification. Crucially, this enables ``train once, use $N$ models": a single network yields useful predictions at every depth, supporting efficient shallow inference without retraining. Our work unifies approximation theory with practical deep learning, providing a new lens on representation learning and a flexible framework for multi-depth deployment. The source code will be released unpon acceptance at https://(open\_upon\_acceptance).
### Title:
          Speech Enhancement Based on Drifting Models
 - **Authors:** Liang Xu, Diego Caviedes-Nozal, Bastiaan Kleijn, Longfei Felix Yan, Rasmus Kongsgaard Olsson
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI); Audio and Speech Processing (eess.AS); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose Speech Enhancement based on Drifting Models (DriftSE), a novel generative framework that formulates denoising as an equilibrium problem. Rather than relying on iterative sampling, DriftSE natively achieves one-step inference by evolving the pushforward distribution of a mapping function to directly match the clean speech distribution. This evolution is driven by a Drifting Field, a learned correction vector that guides samples toward the high-density regions of the clean distribution, which naturally facilitates training on unpaired data by matching distributions rather than paired samples. We investigate the framework under two formulations: a direct mapping from the noisy observation, and a stochastic conditional generative model from a Gaussian prior. Experiments on the VoiceBank-DEMAND benchmark demonstrate that DriftSE achieves high-fidelity enhancement in a single step, outperforming multi-step diffusion baselines and establishing a new paradigm for speech enhancement.
### Title:
          Differentiable Faithfulness Alignment for Cross-Model Circuit Transfer
 - **Authors:** Shun Shao, Binxu Wang, Shay B. Cohen, Anna Korhonen, Yonatan Belinkov
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability has made it possible to localize circuits underlying specific behaviors in language models, but existing methods are expensive, model-specific, and difficult to scale to larger architectures. We introduce \textbf{Differentiable Faithfulness Alignment (DFA)}, a framework that transfers circuit information from a smaller source model to a larger target model through a learned differentiable alignment. DFA projects source-model node importance scores into the target model and trains this mapping with a soft faithfulness objective, avoiding full circuit discovery on the target model. We evaluate DFA on Llama-3 and Qwen-2.5 across six tasks spanning factual retrieval, multiple-choice reasoning, and arithmetic. The strongest results occur on Llama-3 $1$B$\rightarrow3$B, where aligned circuits are often competitive with direct node attribution and zero-shot transfer remains effective. Recovery weakens for larger source--target gaps and is substantially lower on Qwen-2.5, suggesting that transfer becomes harder as architectural and scaling differences increase. Overall, DFA consistently outperforms simple baselines and, in some settings, recovers target-model circuits with faithfulness comparable to or stronger than direct attribution. These results suggest that smaller models can provide useful mechanistic priors for larger ones, while highlighting both the promise and the limits of node-level cross-model circuit alignment.\footnote{Code is available at this https URL.
### Title:
          Multispectral airborne laser scanning dataset for tree species classification: MS-ALS-SPECIES
 - **Authors:** Matti Hyyppä, Klaara Salolahti, Eric Hyyppä, Xiaowei Yu, Josef Taher, Leena Matikainen, Matti Lehtomäki, Paula Litkey, Teemu Hakala, Harri Kaartinen, Juha Hyyppä, Antero Kukko
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The shift from stand-level to individual-tree-level forest assessments supports improved biodiversity mapping, particularly in boreal ecosystems where tree species like aspen (Populus tremula L.) play a keystone role. While airborne laser scanning (ALS) is the standard for such inventories, a major limitation is the small number of publicly available ALS datasets containing high-quality, field-validated reference data. Furthermore, open multispectral ALS datasets with high-quality field reference data are completely lacking despite the potential of multispectral ALS data for tree species classification. This paper presents and details an open multispectral ALS dataset used in a recent international benchmarking study of machine learning and deep learning methods for tree species classification by Taher et al. (2026). The dataset comprises 6326 segment-level point clouds of individual trees representing nine species in Southern Finland. The point cloud data has been acquired using two multispectral laser scanning systems each operating at three laser wavelengths: a helicopter-borne system (HeliALS) with a point density exceeding 1000 points/m$^2$ and an Optech Titan system with approximately 35 points/m$^2$. We provide a detailed description of field data collection techniques developed in the study to facilitate the collection of high-quality ground truth data in an efficient and scalable manner. Additionally, our article presents new analyses on species classification using multispectral data building upon the initial findings of Taher et al. (2026). Furthermore, we study the relation between classification accuracy and tree height to highlight the versatility of the open dataset and to demonstrate the advantage of the point transformer model for small trees and minority species.
### Title:
          The Fragility of Learning LQG Controllers
 - **Authors:** Bruce D. Lee, Anastasios Tsiamis, Nikolai Matni, Manfred Morari, John Lygeros
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning methods are increasingly used to synthesize controllers from data, yet existing sample-complexity characterizations for continuous control are sharp only in the fully observed setting. This paper studies the partially observed case by deriving information-theoretic lower bounds for learning Linear Quadratic Gaussian (LQG) controllers from offline trajectories generated by a (linear) exploration policy. We prove an $\varepsilon$-local minimax excess-cost lower bound that applies to any algorithm mapping the offline dataset to a stabilizing linear controller. The bound is expressed in terms of the Hessian of the LQG cost with respect to model parameters and the inverse Fisher Information induced by the exploration policy. We further provide system-theoretic characterizations of these objects, enabling transparent construction of hard instances. Instantiating the bound on classical fragile robust-control examples, including variants of the Doyle LQG fragility counterexample and non-minimum-phase systems, demonstrates when fragile robust control problems translate into high sample complexity for learning-enabled control. These results suggest the asymptotic optimality of certainty-equivalent synthesis and motivate the importance of both task-directed experiment design and system co-design for sample-efficient learning in partially observed control.
### Title:
          Equivalence Checking of Quantum Circuits via Path-Sum and Weighted Model Counting
 - **Authors:** Wei-Jia Huang, Christophe Chareton, Yu-Fang Chen, Kai-Min Chung, Min-Hsiu Hsieh, Alfons Laarman, Jingyi Mei
 - **Subjects:** Subjects:
Symbolic Computation (cs.SC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Equivalence checking of quantum circuits is a central verification task in quantum computing, ensuring the correctness of circuit optimizations, hardware mappings, and compilation pipelines. Among the primary symbolic methods for this purpose, the path-sum formalism provides a compact representation with powerful reduction rules that yield a canonical form for the classically simulable Clifford fragment, but confluence fails beyond the Clifford fragment. We introduce a new weighted model counting (WMC) encoding for path-sums and combine it with the existing path-sum reductions to obtain a verifier that is both complete and efficient. Our method applies reductions whenever possible and invokes the WMC-based decision procedure on the residual path-sum, yielding a complete semantic check up to a global phase. We implement the approach and evaluate it on standard benchmarks. Results show that the hybrid method outperforms either component in isolation and competes with state-of-the-art tools.
### Title:
          Beyond the Attention Stability Boundary: Agentic Self-Synthesizing Reasoning Protocols
 - **Authors:** Dahlia Shehata, Ming Li
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As LLM agents transition to autonomous digital coworkers, maintaining deterministic goal-directedness in non-linear multi-turn conversations emerged as an architectural bottleneck. We identify and formalize a systemic failure mode termed the Attention Latch in decoder-only autoregressive Transformers. This phenomenon, a behavioral manifestation of Information Over-squashing, occurs when the cumulative probabilistic weight of historical context overrides mid-task updates, causing agents to remain anchored to obsolete constraints despite explicit contradictory instructions. We propose Self-Synthesizing Reasoning Protocols (SSRP), a metacognitive framework that implements a discrete separation between high-level architectural planning (Architect) and turn-by-turn procedural execution (Executive). We evaluate SSRP across 9K trajectories using the MultiWOZ 2.2 dataset and the Aggregate Pivot Accuracy (APA), a novel metric we validate by mapping its scores to the U-shaped 'Lost in the Middle' curve. We present 3 experimental tiers: a shallow recency-based retrieval pilot, a high-entropy SOP, and a semantic hijacked 3-hop Multi-Fact Synthesis task. Our results empirically locate the Attention Stability Boundary, where stateless Vanilla ReAct baselines for GPT 5.4 collapse to 0.1% success while SSRP achieves a 715X Resilience Lift. We demonstrate statistically significant gains across Gemini 3.1 Pro, Claude Sonnet 4.6 and DeepSeek V3.2. Audits confirm SSRP necessity by proving attentional lapse via a recursive reflexion baseline (100% success); decoupling the latch from positional bias through equidistant stress testing (90% accuracy); and formalizing SSRP via the Information Bottleneck principle and granularity ablations. Procedural Integrity audit (98.8% adherence) reveals a Grounding Paradox where high-stability models fail by refusing to hallucinate under retrieval-reasoning contamination.
### Title:
          Interoceptive machine framework: Toward interoception-inspired regulatory architectures in artificial intelligence
 - **Authors:** Diego Candia-Rivera (NERV)
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This review proposes an integrative framework grounded on interoception and embodied AI-termed the interoceptive machine framework-that translates biologically inspired principles of internal-state regulation into computational architectures for adaptive autonomy. Interoception, conceived as the monitoring, integration, and regulation of internal signals, has proven relevant for understanding adaptive behavior in biological systems. The proposed framework organizes interoceptive contributions into three functional principles: homeostatic, allostatic, and enactive, each associated with distinct computational roles: internal viability regulation, anticipatory uncertainty-based re-evaluation, and active data generation through interaction. These principles are not intended as direct neurophysiological mappings, but as abstractions that inform the design of artificial agents with improved self-regulation and context-sensitive behavior. By embedding internal state variables and regulatory loops within these principles, AI systems can achieve more robust decision-making, calibrated uncertainty handling, and adaptive interaction strategies, particularly in uncertain and dynamic environments. This approach provides a concrete and testable pathway toward agents capable of functionally grounded self-regulation, with direct implications for human-computer interaction and assistive technologies. Ultimately, the interoceptive machine framework offers a unifying perspective on how internal-state regulation can enhance autonomy, adaptivity, and robustness in embodied AI systems
### Title:
          Déjà Vu Packing: Optimizing FPGA Logic Clustering Runtime via Pattern Memoization
 - **Authors:** Milo Liebster, Amin Mohaghegh, Andrew Boutros
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Implementing a digital circuit on an FPGA fabric requires clustering technology-mapped netlist primitives into coarser-granularity blocks that can be directly mapped to the physical resources available on the FPGA. As the architecture of FPGA logic blocks (LBs) has grown in complexity, with sophisticated logic elements (LEs) and highly irregular local interconnect, this packing problem has become more challenging. To ensure the feasibility of intracluster routing, the computer-aided design (CAD) tools must solve a costly multi-source multi-sink routing problem for each candidate cluster. In this paper, we first show that such packing legality checks consume a significant portion of the CAD flow runtime for LB architectures with complex LEs and local routing structures resembling modern commercial FPGAs. We demonstrate that the packing stage constitutes 58% and 94% of the entire Versatile Place and Route (VPR) flow runtime on average when mapping a wide variety of benchmarks to the AMD 7-series-like and Altera Stratix-10-like VTR architecture captures, respectively. By analyzing the packing algorithm behavior, we observe that a significant fraction of the attempted packed clusters are repetitions of a much smaller number of packing patterns, and therefore many of the packing legality checks are redundant and could be skipped. To this end, we introduce our Déjà Vu packing approach, which leverages a novel packing signature tree data structure that enables efficient identification of recurring packing patterns and memoization of their legality check outcomes. Our approach speeds up the packing by up to 13.4x and 29.3x, with an average of 3.7x and 6.9x, across the evaluated benchmarks on the 7-series and Stratix 10 architectures. These packing runtime gains result in a significant 1.6x and 5.3x average reduction in end-to-end VPR runtime, while maintaining quality of results.
### Title:
          Passage-Aware Structural Mapping for RGB-D Visual SLAM
 - **Authors:** Ali Tourani, Miguel Fernandez-Cortizas, Saad Ejaz, David Pérez Saura, Asier Bikandi-Noya, Jose Luis Sanchez-Lopez, Holger Voos
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Doorways and passages are critical structural elements for indoor robot navigation, yet they remain underexplored in modern Visual SLAM (VSLAM) frameworks. This paper presents a passage-aware structural mapping approach for RGB-D VSLAM that detects doors and traversable openings by jointly fusing geometric, semantic, and topological cues. Doors are modeled as planar entities embedded within walls and classified as traversable or non-traversable based on their coplanarity with the supporting wall. Passages are inferred through two complementary strategies: traversal evidence accumulated from camera-wall interactions across consecutive keyframes, and geometric opening validation based on discontinuities in the mapped wall geometry. The proposed method is integrated into vS-Graphs as a proof of concept, enriching its scene graph with passage-level abstractions and improving room connectivity modeling. Qualitative evaluations on indoor office sequences demonstrate reliable doorway detection, and the framework lays the foundation for exploiting these elements in BIM-informed VSLAM. The source code is publicly available at this https URL.
## Keyword: localization
### Title:
          From Skeletons to Pixels: Few-Shot Precise Event Spotting via Representation and Prediction Distillation
 - **Authors:** Zhong Han Ervin Yeoh, Jiang Kan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Precise Event Spotting (PES) is essential in fast-paced sports such as tennis, where fine-grained events occur within very short temporal windows. Accurate frame-level localization is challenging because of motion blur, subtle action differences, and limited annotated data. We study two complementary distillation strategies for few-shot PES: Adaptive Weight Distillation (AWD), a prediction-level method that adaptively weights teacher supervision on unlabeled data, and Annealed Multimodal Distillation for Few-Shot Event Detection (AMD-FED), a representation-level framework that transfers robust skeleton knowledge into visual modalities through annealed pseudo-labeling. Both methods use multimodal distillation to improve generalization under limited supervision. We evaluate them on F3Set-Tennis(sub) under few-shot k-clip settings, where they consistently outperform single-modality baselines and prior PES approaches. After observing the stronger performance of representation-level distillation on tennis, we further validate AMD-FED on a second sports dataset, Figure Skating, where it also shows robust performance in the k-clip scenario. These results highlight the effectiveness of multimodal distillation, especially representation-level transfer, for few-shot precise event spotting.
### Title:
          Unified Multi-Foundation-Model Slide Representation for Pan-Cancer Recognition and Text-Guided Tumor Localization
 - **Authors:** Tianyang Wang, Ziyu Su, Abdul Rehman Akbar, Usama Sajjad, Lina Gokhale, Charles Rabolli, Wei Chen, Anil Parwani, Muhammad Khalid Khan Niazi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The expanding ecosystem of pathology foundation models has produced powerful but fragmented tile-level representations, limiting their use in clinical tasks that require unified slide-level reasoning and interpretable linkage to clinically meaningful information. We present ASTRA, a pan-cancer framework that integrates heterogeneous foundation-model representations into a shared slide-level representation space and semantically grounds that space using structured pathology annotation fields, including classification category, cancer type, and anatomic site. ASTRA combines sparse mixture-of-experts contextualization, masked multi-model reconstruction, and contrastive alignment to structured pathology prompts to learn slide representations that support 4-category classification, 3-class solid tumor typing, 16-class cancer typing, and text-guided tumor localization without pixel-level supervision. Developed on a CHTN cohort of 10,359 whole-slide images (WSIs) spanning 16 tumor types, ASTRA consistently improves pan-cancer classification across four pathology foundation-model backbones, achieving up to 97.8% macro-AUC for 4-category classification, 99.7% for 3-class solid tumor typing, and 99.2% for 16-class cancer typing. For tumor localization, ASTRA achieves a mean Dice of 0.897 on an annotated in-domain CHTN subset (n = 380) spanning 16 cancer types and 0.738 on an external TCGA cohort (n = 1,686) spanning four cancer types. These results demonstrate that minimal structured pathology annotation fields derived from slide-level metadata can provide effective semantic supervision for unified slide representation learning, enabling both pan-cancer prediction and weakly supervised tumor localization within a single framework.
### Title:
          Magnetic Indoor Localization through CNN Regression and Rotation Invariance
 - **Authors:** Helge Rosé, Konstantin Klipp, Tom Koubek, Bernd Schäufele, Ilja Radusch
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Indoor positioning is an essential technology for a wide range of applications in GNSS-denied environments, including indoor navigation and IoT systems. Combining convolutional neural networks (CNNs) and magnetic field-based features offers a low-cost, infrastructure-free solution for precise positioning. While magnetic fingerprints are a promising approach for indoor positioning, models trained on raw 3D magnetometer data are highly sensitive to device orientation. We address this by using two rotation invariant features derived from the 3D magnetic field: the norm (Mn) and the projection onto the gravity axis (Mg). We train a lightweight 7-layer dilated CNN (MagNetS/XL) on magnetic sequences to directly regress (x, y) positions. Using the MagPie dataset (three buildings, handheld trajectories), we systematically evaluate fixed and random rotations of test and/or train data. Raw 3D inputs (Mx, My , Mz) exhibit isotropic error increases under fixed 90° rotations and further degrade with growing random rotations. In contrast, 2D (Mn, Mg) inputs maintain rotation invariant accuracy and surpass the 3D inputs once rotation exceeds building-specific thresholds for three reference buildings: 0° for Loomis (large), 5° for Talbot (medium), and 6° for CSL (small). MagNetXL achieves or exceeds state-of-the-art accuracy on the MagPie dataset, and MagNetS delivers similar performance with roughly one third of the parameters, favoring mobile deployment. These results show that the robustness gained from rotation invariant inputs outweighs the loss of input dimensionality in realistic usage, allowing mapping and localization without orientation alignment or added infrastructure.
### Title:
          Text-Guided Multimodal Unified Industrial Anomaly Detection
 - **Authors:** Zewen Li, Shuo Ye, Zitong Yu, Weicheng Xie, Linlin Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Industrial anomaly detection based on RGB-3D multimodal data has emerged as a mainstream paradigm for intelligent quality inspection. However, existing unsupervised methods suffer from two critical limitations: ambiguous cross-modal alignment caused by the lack of high-level semantic guidance and insufficient geometric modeling for RGB-to-3D feature mapping. To address these issues, we propose a unified multimodal industrial anomaly detection framework guided by text semantics. The framework consists of two core modules: a Geometry-Aware Cross-Modal Mapper to preserve geometric structure during modality conversion, and an Object-Conditioned Textual Feature Adaptor to align multimodal features with semantic priors. Furthermore, we establish a unified learning paradigm for multimodal industrial anomaly detection, which breaks the one-model-one-class constraint and enables accurate anomaly detection across diverse classes using a single model. Extensive experiments on the MVTec 3D-AD and Eyecandies datasets demonstrate that our method achieves state-of-the-art performance in classification and localization under unsupervised settings.
### Title:
          Accelerating Frequency Domain Diffusion Models with Error-Feedback Event-Driven Caching
 - **Authors:** Dong Liu, Haisheng Wang, Yanxuan Yu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models achieve remarkable success in time series generation. However, slow inference limits their practical deployment. We propose E$^2$-CRF (Error-Feedback Event-Driven Cumulative Residual Feature caching) to accelerate frequency domain diffusion models. Our method exploits two structural properties: (1) spectral localization, where signal energy concentrates in low frequencies, and (2) mirror symmetry, which halves the effective frequency dimension. E$^2$-CRF uses a closed-loop error-feedback system that adaptively caches transformer KV features across diffusion steps. We trigger recomputation using event-driven residual dynamics instead of fixed schedules. Our method selectively recomputes high-energy or rapidly-changing tokens while reusing cached features for stable high-frequency components. E$^2$-CRF achieves ~2.2 speedup while maintaining sample quality. We demonstrate effectiveness on 5 datasets. Our caching strategy naturally aligns with the diffusion process's structure-to-detail progression. We include sufficient-condition error and complexity bounds under standard regularity assumptions (Appendix), alongside empirical validation. Our code is available at this https URL and is also integrated in this https URL.
### Title:
          From Pixels to Explanations: Interpretable Diabetic Retinopathy Grading with CNN-Transformer Ensembles, Visual Explainability and Vision-Language Models
 - **Authors:** Pir Bakhsh Khokhar, Carmine Gravino, Fabio Palomba, Sule Yildirim Yayilgan, Sarang Shaikh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The quality of diabetic retinopathy (DR) screening relies on the ability to correctly grade severity; however, many deep-learning (DL) classifiers cannot be easily interpreted in the clinical context. This study presents a methodology that combines strong discriminative models with multimodal explanations, converting retinal pixels into clinically interpretable outputs. Using the APTOS 2019 benchmark, we evaluated six representative CNN- and transformer-based backbones under a controlled protocol with stratified five-fold cross-validation. We then compared ensembling strategies (hard voting, weighted soft voting, stacking) and investigated a hybrid class-level fusion variant to exploit grade-specific advantages. For interpretability, we produced Grad-CAM++ visual attribution maps and short textual rationales using vision-language models (VLMs) conditioned on the fundus image and classifier outputs under conservative prompting constraints. Modern CNN backbones (ResNet-50 and ConvNeXt-Tiny) provided the strongest single-model baselines, with cross-validated QWK up to 0.919 and 0.914, respectively. Ensembling improved ordinal agreement, and weighted soft voting was the most consistent across folds (QWK 0.934 +/- 0.017). Hybrid class-level fusion was competitive but did not yield a statistically reliable improvement over standard fusion in paired fold comparisons (Holm-adjusted p >= 1.000). For explanation quality, Grad-CAM++ offered plausible but coarse localization, and VLM rationales were generally grade-consistent. Quantitatively, VLM variants showed a trade-off between clinical completeness and template-level semantic similarity (coverage 0.700 vs. BERTScore 0.072), while image-text alignment was comparable (CLIPScore approximately 0.34).
### Title:
          One Identity, Many Roles: Multimodal Entity Coreference for Enhanced Video Situation Recognition
 - **Authors:** Balaji Darur, Amanmeet Garg, Makarand Tapaswi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video Situation Recognition (VidSitu) addresses the challenging problem of "who did what to whom, with what, how, and where" in a video. It tests thorough video understanding by requiring identification of salient actions and associated short descriptions for event roles across multiple events. Grounding with VidSitu requires spatio-temporal localization of key entities across shots and varied appearances. We posit that coherent video understanding requires consistent identification of entities that play different roles. We propose Multimodal Entity Coreference (MEC) to unite entity descriptions in text with grounding across the video. Towards this, we introduce CineMEC, a multi-stage approach that unites event role mention groups with visual clusters of entities, without explicit grounding supervision during training. Our approach is designed to exploit the synergy between visual grounding and captioning, where improving one influences the other and vice versa. For evaluation, we extend the VidSitu dataset with grounding annotations. While previous work focuses primarily on descriptions, CineMEC improves consistency across both: captioning (+2.5% CIDEr, +7% LEA) and visual grounding (+18% HOTA).
### Title:
          StoryTR: Narrative-Centric Video Temporal Retrieval with Theory of Mind Reasoning
 - **Authors:** Xuanyue Zhong, Yuqiang Xie, Guanqun Bi, Jiangping Yang, Guibin Chen
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current video moment retrieval excels at action-centric tasks but struggles with narrative content. Models can see \textit{what is happening} but fail to reason \textit{why it matters}. This semantic gap stems from the lack of \textbf{Theory of Mind (ToM)}: the cognitive ability to infer implicit intentions, mental states, and narrative causality from surface-level observations. We introduce \textbf{StoryTR}, the first video moment retrieval benchmark requiring ToM reasoning, comprising 8.1k samples from narrative short-form videos (shorts/reels). These videos present an ideal testbed. Their high information density encodes meaning through subtle multimodal cues. For instance, a glance paired with a sigh carries entirely different semantics than the glance alone. Yet multimodal perception alone is insufficient; ToM is required to decode that a character ``smiling'' may actually be ``concealing hostility.'' To teach models this reasoning capability, we propose an \textbf{Agentic Data Pipeline} that generates training data with explicit three-tier ToM chains (intent decoding, narrative reasoning, boundary localization). Experiments reveal the severity of the reasoning gap: Gemini-3.0-Pro achieves only 0.53 Avg IoU on StoryTR. However, our 7B \textbf{Shorts-Moment} model, trained on ToM-guided data, improves +15.1\% relative IoU over baselines, demonstrating that \textit{narrative reasoning capability matters more than parameter scale}.
### Title:
          Learning from Noisy Prompts: Saliency-Guided Prompt Distillation for Robust Segmentation with SAM
 - **Authors:** Jingxuan Kang, Ziqi Zhang, Shaoming Zheng, Shuang Li, Uday Bharat Patel, Alexander Harry Fitzhugh, Phillip Lung, Yusuf Kiberu, Nikesh Jathanna, Shahnaz Jamil-Copley, Bernhard Kainz, Chen Qin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Segmentation is central to clinical diagnosis and monitoring, yet the reliability of modern foundation models in medical imaging still depends on the availability of precise prompts. The Segment Anything Model (SAM) offers powerful zero-shot capabilities, although it collapses under the weak, generic, and noisy prompts that dominate real clinical workflows. In practice, annotations such as centerline points are coarse and ambiguous, often drifting across neighboring anatomy and misguiding SAM toward inconsistent or incomplete masks. We introduce SPD, a Saliency-Guided Prompt Distillation framework that converts these unreliable cues into robust guidance. SPD first learns data-driven anatomical priors through a lightweight saliency head to obtain confident localization maps. These priors then drive Contextual Prompt Distillation, which validates and enriches noisy prompts using cues from anatomically adjacent slices, producing a consensus prompt set that matches the behavior of expert reasoning. A Pairwise Slice Consistency objective further enforces local anatomical coherence during segmentation. Experiments on four challenging MRI and CT benchmarks demonstrate that SPD consistently outperforms existing SAM adaptations and supervised baselines, delivering large gains in both region-based and boundary-based metrics. SPD provides a practical and principled path toward reliable foundation model deployment in clinical environments where only imperfect prompts are available.
### Title:
          An Empirical Evaluation of Locally Deployed LLMs for Bug Detection in Python Code
 - **Authors:** Jelena Ilić Vulićević
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) have demonstrated strong performance on a wide range of software engineering tasks, including code generation and analysis. However, most prior work relies on cloud-based models or specialized hardware, limiting practical applicability in privacy-sensitive or resource-constrained environments. In this paper, we present a systematic empirical evaluation of two locally deployed LLMs, LLaMA 3.2 and Mistral, for real-world Python bug detection using the BugsInPy benchmark. We evaluate 349 bugs across 17 projects using a zero-shot prompting approach at the function level and an automated keyword-based evaluation framework. Our results show that locally executed models achieve accuracy between 43% and 45%, while producing a large proportion of partially correct responses that identify problematic code regions without pinpointing the exact fix. Performance varies significantly across projects, highlighting the importance of codebase characteristics. The results demonstrate that local models can identify a meaningful share of bugs, though precise localization remains difficult for locally executed LLMs, particularly when handling complex and context dependent bugs in realistic development scenarios.
### Title:
          Geometry-Conditioned Diffusion for Occlusion-Robust In-Bed Pose Estimation
 - **Authors:** Navid Aslankhani Khameneh, Marco Carletti, Cigdem Beyan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robust in-bed human pose estimation under blanket occlusion remains challenging due to the scarcity of reliable labeled training data for heavily covered poses. Existing approaches rely on multi-modal sensing or image-to-image translation frameworks that remain conditioned on visible source imagery, limiting scalability and pose diversity. In this work, we reformulate occlusion-aware augmentation as a geometry-conditioned generative modeling task. We conduct a systematic comparison of deterministic masking, unpaired translation, paired diffusion-based translation, and a proposed pose-conditioned Latent Diffusion Model (Pose-LDM). Unlike image-guided methods, Pose-LDM synthesizes blanket-covered images directly from skeletal keypoints, eliminating dependence on paired supervision and pixel-level source-image conditioning while enabling generation from arbitrary pose inputs. All augmentation strategies are evaluated through their impact on downstream pose estimation under a fixed backbone. Pose- LDM achieves the highest strict localization accuracy under severe occlusion while maintaining overall detection performance comparable to paired diffusion models, approaching the performance of fully supervised training. These results demonstrate that geometry-conditioned diffusion provides an effective and supervision-efficient pathway toward occlusion-robust inbed pose estimation without modifying the sensing pipeline. The code is available at: this http URL GeoDiffPose.
### Title:
          ResAF-Net: An Anchor-Free Attention-Based Network for Tree Detection and Agricultural Mapping in Palestine
 - **Authors:** Rabee Al-Qasem
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable agricultural data is essential for food security, land-use planning, and economic resilience, yet in Palestine, such data remains difficult to collect at scale because of fragmented landscapes, limited field access, and restrictions on aerial monitoring. This paper presents ResAF-Net, a satellite-based tree detection framework designed for large-scale agricultural monitoring in resource-constrained settings. The proposed architecture combines a ResNet-50 encoder, Atrous Spatial Pyramid Pooling (ASPP), a feature-fusion stage, a multi-head self-attention refinement module, and an anchor-free FCOS detection head to improve tree localization in dense and heterogeneous scenes. Trained on the MillionTrees benchmark, the model achieved 82% Recall, 63.03% mAP@0.50, and 35.47% mAP@0.50:0.95 on the validation split, indicating strong sensitivity to tree presence while maintaining competitive localization quality. Beyond benchmark evaluation, we implemented the model within a web-based GIS application integrated with Palestinian cadastral data from GeoMolg, enabling tree analysis at scene, parcel, and community levels. This deployment demonstrates the practical feasibility of AI-assisted agricultural inventorying in Palestine. It provides a foundation for data-driven monitoring, reporting, and future species-level analysis of Mediterranean tree crops.
### Title:
          Towards Localizing Conversation Partners using Head Motion
 - **Authors:** Payal Mohapatra, Calvin Murdock, Ali Aroudi, Ishwarya Ananthabhotla, Anjali Menon, Buye Xu, Morteza Khaleghimeybodi
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many individuals struggle to understand conversation partners in noisy settings, particularly amid background speakers or due to hearing impairments. Emerging wearables like smartglasses offer a transformative opportunity to enhance speech from conversation partners. Crucial to this is identifying the direction in which the user wants to listen, which we refer to as the user's acoustic zones of interest. While current spatial audio-based methods can resolve the direction of vocal input, they are agnostic to listening preferences and have limited functionality in noisy settings with interfering speakers. To address this, behavioral cues are needed to actively infer a user's acoustic zones of interest. We explore the effectiveness of head-orienting behavior, captured by Inertial Measurement Units (IMUs) on smartglasses, as a modality for localizing these zones in seated conversations. We introduce HALo, a head-orientation-based acoustic zone localization network that leverages smartglasses' IMUs to non-invasively infer auditory zones of interest corresponding to conversation partner locations. By integrating an a priori estimate of the number of conversation partners, our approach yields a 21% performance improvement over existing methods. We complement this with CoCo, which classifies the number of conversation partners using only IMU data, achieving 0.74 accuracy and a 35% gain over rule-based and generic time-series baselines. We discuss practical considerations for feature extraction and inference and provide qualitative analyses over extended sessions. We also demonstrate a minimal end-to-end speech enhancement system, showing that head-orientation-based localization offers clear advantages in extremely noisy settings with multiple conversation partners.
### Title:
          2nd of the 5th PVUW MeViS-Audio Track: ASR-SaSaSa2VA
 - **Authors:** Zhiyu Wang, Xudong Kang, Shutao Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio-based video object segmentation aims to locate and segment objects in videos conditioned on audio cues, requiring precise understanding of both appearance and motion. Recent audio-driven video segmentation methods extend MLLMs by fusing audio and visual features for end-to-end localization. Despite their promise, these approaches are computationally intensive, struggle with aligning temporal audio cues to dynamic video content, and depend on large paired audio-video datasets. To address these challenges, we present ASR-SaSaSa2VA, a resource-efficient framework for audio-guided video segmentation. The key idea is to convert audio inputs into textual motion descriptions via automatic speech recognition (ASR) models and then leverage pre-trained text-based referring video segmentation models (e.g., SaSaSa2VA) for pixel-level predictions. To further enhance robustness, we incorporate a no-target expression detection module, implemented by a fine-tuned audio-based MLLM, which filters out audio clips that do not refer to any target object. This design allows the system to exploit strong pre-trained models while effectively handling ambiguous or irrelevant audio inputs. Our approach achieves a final score of 80.7 in the 5th PVUW Challenge (MeViS-v2-Audio track), earning the second-place ranking.
### Title:
          GoClick: Lightweight Element Grounding Model for Autonomous GUI Interaction
 - **Authors:** Hongxin Li, Yuntao Chen, Zhaoxiang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graphical User Interface (GUI) element grounding (precisely locating elements on screenshots based on natural language instructions) is fundamental for agents interacting with GUIs. Deploying this capability directly on resource-constrained devices like mobile phones is increasingly critical for GUI agents requiring low latency. However, this goal faces a significant challenge, as current visual grounding methods typically employ large vision-language model (VLM) (more than 2.5B parameters), making them impractical for on-device execution due to memory and computational constraints. To address this, this paper introduces GoClick, a lightweight GUI element grounding VLM with only 230M parameters that achieves excellent visual grounding accuracy, even on par with significantly larger models. Simply downsizing existing decoder-only VLMs is a straightforward way to design a lightweight model, but our experiments reveal that this approach yields suboptimal results. Instead, we select an encoder-decoder architecture, which outperforms decoder-only alternatives at small parameter scales for GUI grounding tasks. Additionally, the limited capacity of small VLMs encourages us to develop a Progressive Data Refinement pipeline that utilizes task type filtering and data ratio adjustment to extract a high-quality 3.8M-sample core set from a 10.8M raw dataset. Training GoClick using this core set brings notable grounding accuracy gains. Our experiments show that GoClick excels on multiple GUI element grounding benchmarks while maintaining a small size and high inference speed. GoClick also enhances GUI agent performance when integrated into a device-cloud collaboration framework, where GoClick helps cloud-based task planners perform precise element localization and achieve higher success rates. We hope our method serves as a meaningful exploration within the GUI agent community.
### Title:
          LAVA: Layered Audio-Visual Anti-tampering Watermarking for Robust Deepfake Detection and Localization
 - **Authors:** Bokang Zeng, Zheng Gao, Xiaoyu Li, Xiaoyan Feng, Jiaojiao Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Proactive watermarking offers a promising approach for deepfake tamper detection and localization in short-form videos. However, existing methods often decouple audio and visual evidence and assume that watermark signals remain reliable under real-world degradations, making tamper localization vulnerable to multimodal misalignment and compression distortions. Moreover, existing semi-fragile visual watermarking methods often degrade significantly under codec compression because their embedding bands overlap with compression-sensitive frequency regions. To address these limitations, we propose Layered Audio-Visual Anti-tampering Watermarking (LAVA), a calibration-aware audio-visual watermark fusion framework for deepfake tamper detection and localization. LAVA leverages cross-modal watermark fusion and calibration-aware alignment to preserve consistent and reliable tamper evidence under compression and audio-visual asynchrony, enabling robust tamper localization. Extensive experiments demonstrate that LAVA achieves near-perfect detection performance (AP = 0.999), remains robust to compression and multimodal misalignment, and significantly improves tamper localization reliability over existing audio-visual fusion baselines.
### Title:
          EXACT: an explainable anomaly-aware vision foundation model for analysis of 3D chest CT
 - **Authors:** Xuguang Bai, Mingxuan Liu, Tongxi Song, Yifei Chen, Hongjia Yang, Kasidit Anmahapong, Zihan Li, Ying Zhou, Qiyuan Tian
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chest computed tomography (CT) is central to the detection and management of thoracic disease, yet the growing scale and complexity of volumetric imaging increasingly exceed what can be addressed by scan-level prediction alone. Clinically useful AI for CT must not only recognize disease across the whole volume, but also localize abnormalities and provide interpretable visual evidence. Existing vision-language foundation models typically compress scans and reports into global image-text representations, limiting their ability to preserve spatial evidence and support clinically meaningful interpretation. Here we developed EXACT, an explainable anomaly-aware foundation model for three-dimensional chest CT that learns spatially resolved representations from paired clinical scans and radiology reports. EXACT was pre-trained on 25,692 CT-reports pairs using anatomy-aware weak supervision, jointly learning organ segmentation and multi-instance anomaly localization without manual voxel-level annotations. The resulting organ-specific anomaly-aware maps assign each voxel a disease-specific anomaly score confined to its corresponding anatomy, jointly encoding lesion extent and organ-level context. In retrospective multinational and multi-center evaluations, EXACT showed broad and consistent improvements across clinically relevant CT tasks, spanning multi-disease diagnosis, zero-shot anomaly localization, downstream adaptation, and visually grounded report generation, outperforming existing three-dimensional medical foundation models. By transforming routine clinical CT scans and free-text reports into explainable voxel-level representations, EXACT establishes a scalable paradigm for trustworthy volumetric medical AI.
### Title:
          Sub-Nyquist Sampling for Reaching Theoretical Minimal Sampling Rate Boundary
 - **Authors:** Dong Xiao, Jian Wang
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wideband spectrum sensing motivates sub-Nyquist sampling architectures that exploit spectral sparsity, yet in blind scenarios where subband locations are unknown, existing schemes require sampling rates at least twice the theoretical minimum. To this end, we propose a dual-frequency aliasing wideband converter (DAWC), which partitions the multiband spectrum into non-uniform frequency intervals and selectively samples only a subset of them, requiring no prior knowledge of subband locations. We demonstrate that under mild conditions on the signal and the system, DAWC achieves perfect subband localization and waveform reconstruction at the theoretical minimum rate. Moreover, we introduce an innovative side-information-aided subspace pursuit (MSSP) algorithm exploiting the common support structure inherent in the signal column submatrices for exact recovery of the spectrum support set. Based on the restricted isometry property (RIP), we provide stable recovery guarantees for MSSP in the presence of noise. Numerical simulations show that the proposed scheme achieves superior spectrum recovery accuracy compared to state-of-the-art methods.
### Title:
          Point Cloud Registration for Fusion between SPECT MPI and CTA Images
 - **Authors:** Ni Yao, Xiangyu Liu, Shaojie Tang, Danyang Sun, Chuang Han, Yanting Li, Jiaofen Nan, Chengyang Li, Fubao Zhu, Chen Zhao, Zhihui Xu, Weihua Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Clinical fusion of Single Photon Emission Computed Tomography Myocardial Perfusion Imaging (SPECT MPI) and Computed Tomography Angiography (CTA) remains limited by cross-modality misregistration and reliance on manual landmarks, which can hinder accurate ischemia localization and lesion-level functional assessment. To address this issue, we propose a registration and fusion framework for SPECT MPI and CTA that integrates functional and structural information for comprehensive cardiac evaluation. The proposed pipeline performs U-Net-based segmentation on both modalities. On SPECT MPI, only the left ventricle (LV) is extracted, and anatomical landmarks are automatically derived from characteristic LV structures. On CTA, both ventricles are segmented, and their spatial relationship is used to automatically define landmarks at the interventricular septal junction. Scale-space consistency preprocessing and landmark-driven coarse registration are applied to mitigate initial misalignment. Based on this initialization, multiple fine registration methods are evaluated on LV epicardial surface point clouds, including ICP, SICP, CPD, CluReg, FFD, and BCPD-plus-plus. The resulting transformations are then propagated to voxel-level resampling for high-precision SPECT-CTA fusion. In a retrospective cohort of 60 patients, the proposed framework preserved sub-millimeter coronary detail from CTA while accurately overlaying quantitative SPECT perfusion. Among the evaluated methods, BCPD-plus-plus achieved the highest accuracy with a mean point cloud distance of 1.7 mm. By combining robust initialization, comparative fine registration, and voxel-level fusion, the proposed approach provides a practical solution for myocardial ischemia localization and functional evaluation of coronary lesions, while remaining independent of any specific fine registration algorithm.
### Title:
          Pushing Radar Odometry Beyond the Pavement: Current Capabilities and Challenges
 - **Authors:** Shaunak Kolhe, Peng Jiang, Maggie Wigness, Philip Osteen, Timothy Overbye, Chrisitan Ellis, Srikanth Saripalli
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar offers unique advantages for localization in unstructured environments, including robustness to weather, lighting, and airborne particulates. While most prior work has studied radar odometry in urban, largely planar settings, its performance in off-road environments remains less understood. In this paper, we investigate the potential of radar for off-road odometry estimation and identify key challenges that arise from full $SE(3)$ vehicle motion, terrain-induced ground returns, and sparse or unstable features. To address these issues, we introduce two simple baselines: Radar-KISSICP, which applies motion compensation to generate 3D-aware radar pointclouds, and Radar-IMU, which leverages IMU preintegration to stabilize scan matching. Experiments on the Great Outdoors (GO) dataset demonstrate that these baselines improve trajectory estimation in challenging routes and provide a reference point for future development of radar odometry in off-road robotics.
## Keyword: transformer
### Title:
          The Randomness Floor: Measuring Intrinsic Non-Randomness in Language Model Token Distributions
 - **Authors:** Jarosław Hryszko
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Language models cannot be random. This paper introduces Entropic Deviation (ED), the normalised KL divergence between a model's token distribution and the uniform distribution, and measures it systematically across 31,200 generations spanning seven models, two architectures (transformer and state space), nine prompt categories, three temperatures, and five languages. Under semantically neutral prompts (empty strings, random characters, nonsense syllables) transformers still exhibit ED of approximately 0.30, meaning that 88-93% of the non-randomness observed under semantic prompts is intrinsic to the learned weights rather than induced by context. Three transformer families (Gemma, Llama, Qwen) converge on nearly identical ED values despite different training data and vocabularies. A state space model (Mamba2) reveals a qualitatively different regime: twice the ED, three times lower within-sequence variance, and massive sensitivity to temperature (r = -0.78) where transformers are nearly immune (r < 0.05). Cross-lingual experiments with Qwen-32B show a stable gradient across five languages (English, Japanese, Chinese, Polish, Arabic) that does not correlate with token fertility and persists when two languages sharing an identical tokeniser subset are compared. These findings establish a structural lower bound on randomness in pretrained language models, characterise how this bound differs across architectures, and demonstrate that language itself modulates the bound independently of tokenisation.
### Title:
          The Spectral Lifecycle of Transformer Training: Transient Compression Waves, Persistent Spectral Gradients, and the Q/K--V Asymmetry
 - **Authors:** Yi Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present the first systematic study of weight matrix singular value spectra \emph{during} transformer pretraining, tracking full SVD decompositions of every weight matrix at 25-step intervals across three model scales (30M--285M parameters). We discover three phenomena: \textbf{(1)~Transient Compression Waves:} stable rank compression propagates as a traveling wave from early to late layers, creating a dramatic gradient that peaks early then \emph{reverses} -- late layers eventually over-compress past early layers. \textbf{(2)~Persistent Spectral Gradients:} the power-law exponent~$\alpha$ develops a permanent depth gradient forming a non-monotonic inverted-U in deeper models, with peaks shifting toward earlier layers as depth increases. \textbf{(3)~Q/K--V Functional Asymmetry:} value/output projections compress uniformly while query/key projections carry the full depth-dependent dynamics. The dissociation between transient compression and persistent spectral shape reveals that \emph{rank and spectral shape encode fundamentally different information about training}. We formalize this as a two-timescale dynamical model and derive scaling laws ($\Delta\alpha \propto L^{0.26}$, $R^2{=}0.99$). We validate on nine models across three families (custom, GPT-2, Pythia; 30M--1B parameters; 8--36 layers), demonstrate that $\alpha$ predicts layer importance ($\rho{=}0.69$--$0.84$, $p{<}0.02$), and show that spectral-guided pruning outperforms Last-N heuristics by $1.1{\times}$--$3.6{\times}$ across seven models in two families (GPT-2 124M--774M, Pythia 160M--1B), with worst-vs-best gaps up to $23.7{\times}$ confirming the causal role of spectral structure.
### Title:
          BiTA: Bidirectional Gated Recurrent Unit-Transformer Aggregator in a Temporal Graph Network Framework for Alert Prediction in Computer Networks
 - **Authors:** Zahra Makki Nayeri, Mohsen Rezvani
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Proactive alert prediction in computer networks is critical for mitigating evolving cyber threats and enabling timely defensive actions. Temporal Graph Neural Networks (TGNs) provide a principled framework for modeling time-evolving interactions; however, existing TGN-based methods predominantly rely on unidirectional or single-mechanism temporal aggregation, which limits their ability to capture recursive, multi-scale temporal patterns commonly observed in real-world attack behaviors. In this paper, we propose BiTA, a Bidirectional Gated Recurrent Unit-Transformer Aggregator for temporal graph learning. Rather than introducing a deeper or higher-capacity model, BiTA redesigns the temporal aggregation function within the TGN framework by jointly encoding bidirectional sequential dependencies and long-range contextual relations over each node's temporal neighborhood. This aggregation strategy enables complementary temporal reasoning at different scales while preserving the original TGN memory and message-passing structure. We evaluate BiTA on real-world alert datasets, demonstrating significant improvements in key performance metrics such as area under the curve, average precision, mean reciprocal rank, and per-category prediction accuracy when compared to state-of-the-art temporal graph models. BiTA outperforms baseline methods under both transductive and inductive settings, highlighting its robustness and generalization capabilities in dynamic network environments. BiTA is a scalable and interpretable framework for real-time cyber threat anticipation, paving the way toward more intelligent and adaptive intrusion detection systems.
### Title:
          Stochastic KV Routing: Enabling Adaptive Depth-Wise Cache Sharing
 - **Authors:** Anastasiia Filippova, David Grangier, Marco Cuturi, João Monteiro
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Serving transformer language models with high throughput requires caching Key-Values (KVs) to avoid redundant computation during autoregressive generation. The memory footprint of KV caching is significant and heavily impacts serving costs. This work proposes to lessen these memory requirements. While recent work has largely addressed KV cache reduction via compression and eviction along the temporal axis, we argue that the \emph{depth} dimension offers an orthogonal and robust avenue for optimization. Although prior research suggests that a full cache for every layer is redundant, implementing cross-layer cache sharing remains a practical challenge; existing methods typically suffer from reduced throughput or increased time-to-first-token. In this paper, we demonstrate that dropping a layer's cache offers efficient optimization without information loss. We propose a simple training approach: random cross-layer attention. During training, layers randomly choose to attend either to their own KV states or those of a preceding layer. This stochastic process adapts the model to be robust to various depth-wise cache sharing strategies, ensuring flexibility for unknown hardware constraints at deployment time. Our evaluations show that applying this scheme during pre-training or fine-tuning enables depth-wise cache sharing for various model families. Furthermore, for larger models in data-constrained settings, this approach is suggestive of a regularization-like effect, frequently preserving or improving performance while significantly reducing the cache's memory footprint.
### Title:
          AutoCompress: Critical Layer Isolation for Efficient Transformer Compression
 - **Authors:** Archit Thorat
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present AutoCompress, a transformer compression method motivated by an empirical finding: in small transformers, Layer 0 carries disproportionately high task-critical information, with an NTK-based importance score of 3.6 compared to a maximum of 0.054 for all other layers -- a gap of over 60x. Based on this finding, we propose Critical Layer Isolation (CLI), an architecture that protects Layer 0 at full dimensionality, compresses all intermediate layers through a learned bottleneck, and restores the full dimension at the final layer. Applied to GPT-2 Medium (354.8M parameters), CLI-GPT2 achieves 204.5 perplexity on WikiText-103 with only 143.8M parameters -- a 2.47x compression ratio and 59.5% parameter reduction. Crucially, an ablation study demonstrates that a uniform bottleneck baseline of comparable size achieves only 571.8 perplexity under identical training conditions, confirming that the architectural decision to protect Layer 0 -- rather than simply reducing model size -- is the primary driver of performance. Code and checkpoints are publicly available.
### Title:
          FreqFormer: Hierarchical Frequency-Domain Attention with Adaptive Spectral Routing for Long-Sequence Video Diffusion Transformers
 - **Authors:** Haopeng Jin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-sequence video diffusion transformers hit a quadratic self-attention cost that dominates runtime and memory for very long token sequences. Most efficient attention methods use one approximation everywhere, yet video features are spectrally structured: low frequencies carry global layout and coarse motion; high frequencies carry texture and fine detail. We present FreqFormer, a frequency-aware heterogeneous attention framework. Token features are split into spectral bands with different operators: dense global attention on compressed low-frequency content, structured block-sparse attention on mid frequencies, and sliding-window local attention on high frequencies. A lightweight spectral routing network allocates heads across bands using layer statistics and the diffusion timestep, shifting compute toward global structure early in denoising and detail later. Cross-band summary tokens provide cheap residual exchange. FreqFormer is paired with a fused GPU execution plan that co-schedules dense, sparse, and local branches to cut kernel launches and memory traffic. We give a consistent complexity model, an orthonormal-decomposition view of approximation, and simulation-based systems numbers (throughput, arithmetic intensity, memory traffic, duration scaling). In simulations from 64K to 1M tokens, FreqFormer substantially reduces estimated attention FLOPs and KV-related memory traffic versus dense attention while keeping a hardware-friendly pattern, supporting spectrally structured heterogeneous attention as a practical direction for long-video diffusion transformers.
### Title:
          Shape: A Self-Supervised 3D Geometry Foundation Model for Industrial CAD Analysis
 - **Authors:** Bayangmbe Mounmo, Sam Chien, Mile Mitrovic
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Industrial CAD workflows require robust, generalizable 3D geometric representations supporting accuracy and explainability. We introduce Shape, a self-supervised foundation model converting surface meshes into dense per-token embeddings. Shape combines a structured 3D latent grid, a multi-scale geometry-aware tokenizer (MAGNO) with cross-attention, and a transformer processor using grouped-query attention and RMSNorm. A learned reconstruction prior enables per-region attribution for explainable predictions. Pretraining uses masked-token reconstruction of normalized geometry statistics and multi-resolution contrastive consistency. The 10.9M-parameter backbone is pretrained on 61,052 CAD meshes from Thingi10K, MFCAD, and Fusion360. On a held-out split of 2,983 meshes, Shape achieves reconstruction R2 = 0.729 and 98.1% top-1 retrieval under the Wang-Isola protocol, with near-zero reconstruction train/val gap (contrastive scores use a larger evaluation pool). A 2x2 ablation on loss type and target-space normalization shows per-dimension normalization is critical: without it, performance collapses (R2 < 0.14, top-1 < 88%); with it, both losses succeed (R2 > 0.70, top-1 > 96%). Smooth-L1 offers secondary stability. Code, embeddings, and an interactive demo are released at this https URL.
### Title:
          ATTN-FIQA: Interpretable Attention-based Face Image Quality Assessment with Vision Transformers
 - **Authors:** Guray Ozgur, Tahar Chettaoui, Eduarda Caldeira, Jan Niklas Kolf, Marco Huber, Andrea Atzori, Naser Damer, Fadi Boutros
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Face Image Quality Assessment (FIQA) aims to assess the recognition utility of face samples and is essential for reliable face recognition (FR) systems. Existing approaches require computationally expensive procedures such as multiple forward passes, backpropagation, or additional training, and only recent work has focused on the use of Vision Transformers. Recent studies highlighted that these architectures inherently function as saliency learners with attention patterns naturally encoding spatial importance. This work proposes ATTN-FIQA, a novel training-free approach that investigates whether pre-softmax attention scores from pre-trained Vision Transformer-based face recognition models can serve as quality indicators. We hypothesize that attention magnitudes intrinsically encode quality: high-quality images with discriminative facial features enable strong query-key alignments producing focused, high-magnitude attention patterns, while degraded images generate diffuse, low-magnitude patterns. ATTN-FIQA extracts pre-softmax attention matrices from the final transformer block, aggregate multi-head attention information across all patches, and compute image-level quality scores through simple averaging, requiring only a single forward pass through pre-trained models without architectural modifications, backpropagation, or additional training. Through comprehensive evaluation across eight benchmark datasets and four FR models, this work demonstrates that attention-based quality scores effectively correlate with face image quality and provide spatial interpretability, revealing which facial regions contribute most to quality determination.
### Title:
          EX-FIQA: Leveraging Intermediate Early eXit Representations from Vision Transformers for Face Image Quality Assessment
 - **Authors:** Guray Ozgur, Tahar Chettaoui, Eduarda Caldeira, Jan Niklas Kolf, Andrea Atzori, Fadi Boutros, Naser Damer
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Face Image Quality Assessment is crucial for reliable face recognition systems, yet existing Vision Transformer-based approaches rely exclusively on final-layer representations, ignoring quality-relevant information captured at intermediate network depths. This paper presents the first comprehensive investigation of how intermediate representations within ViTs contribute to face quality assessment through early exit mechanisms and score fusion strategies. We systematically analyze all twelve transformer blocks of ViT-FIQA architectures, demonstrating that different depths capture distinct and complementary quality-relevant information, as evidenced by varying attention patterns and performance characteristics across network layers. We propose a score fusion framework that combines quality predictions from multiple transformer blocks without architectural modifications or additional training. Our early exit analysis reveals optimal performance-efficiency trade-offs, enabling significant computational savings while maintaining competitive performance. Through extensive evaluation across eight benchmark datasets using four FR models, we demonstrate that our fusion strategy improves upon single-exit approaches. Our proposed quality fusion approach employs depth-weighted averaging that assigns progressively higher importance to deeper transformer blocks, achieving the best quality assessment performance by effectively leveraging the hierarchical nature of feature learning in ViTs. Our work challenges the conventional wisdom that only deep features matter for face analysis, revealing that intermediate representations contain valuable information for quality assessment. The proposed framework offers practical benefits for real-world biometric systems by enabling adaptive computation based on resource constraints while maintaining competitive quality assessment capabilities.
### Title:
          MAE-Based Self-Supervised Pretraining for Data-Efficient Medical Image Segmentation Using nnFormer
 - **Authors:** R. M. Krishna Sureddi, T. Satyanarayana Murthy, Nomula Varsha Reddy, Adi Kanishka, Nalla Manvika Reddy
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer architectures, including nnFormer,have demonstrated promising results in volumetric medical image segmentation by being able to capture long-range spatial interactions. Although they have high performance, these models need large quantities of labeled training data and are also likely to overfit and become training unstable. This is a serious practical problem because it is not only time-consuming but also expensive to obtain medical images that are annotated by experts. Moreover, fully supervised traditional training pipelines do not take advantage of the available large amounts of unlabeled medical imaging data that can be easily obtained in the clinics. We have solved these drawbacks by advancing the efficiency of the nnFormer with a self-supervised pretraining framework, which is based on the Masked Autoencoders (MAE). In this method, the model is pretrained on unlabeled volumetric medical images to reconstruct randomly masked parts of the input. This allows the encoder to learn meaningful anatomical and structural representations . The encoder is then further fine-tuned on a labeled dataset on the downstream segmentation task. Conducted Experiment shows that the offered method leads to a higher segmentation performance on the count of Dice score, a quicker convergence rate on the course of the fine-tuning procedure, and a superior generalization on the basis of limited labeled data . These findings validate that self-supervised learning combined with transformer-based segmentation models is an appropriate approach to the problem of data shortage in medical image analysis.
### Title:
          MeshLAM: Feed-Forward One-Shot Animatable Textured Mesh Avatar Reconstruction
 - **Authors:** Yisheng He, Steven Hoi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce MeshLAM, a feed-forward framework for one-shot animatable mesh head reconstruction that generates high-fidelity, animatable 3D head avatars from a single image. Unlike previous work that relies on time-consuming test-time optimization or extensive multi-view data, our method produces complete mesh representations with inherent animatability from a single image in a single forward pass. Our approach employs a dual shape and texture map architecture that simultaneously processes mesh vertices and texture map with extracted image features from a shared transformer backbone, allowing for coherent shape carving and appearance modeling. To prevent mesh collapse and ensure topological integrity during feed-forward deformation, we propose an iterative GRU-based decoding mechanism with progressive geometry deformation and texture refinement, coupled with a novel reprojection-based texture guidance mechanism that anchors appearance learning to the input image. Extensive experiments demonstrate that our method outperforms state-of-the-art approaches in reconstruction quality, animation capability, and computational efficiency. Project page at this https URL.
### Title:
          Accelerating Frequency Domain Diffusion Models with Error-Feedback Event-Driven Caching
 - **Authors:** Dong Liu, Haisheng Wang, Yanxuan Yu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models achieve remarkable success in time series generation. However, slow inference limits their practical deployment. We propose E$^2$-CRF (Error-Feedback Event-Driven Cumulative Residual Feature caching) to accelerate frequency domain diffusion models. Our method exploits two structural properties: (1) spectral localization, where signal energy concentrates in low frequencies, and (2) mirror symmetry, which halves the effective frequency dimension. E$^2$-CRF uses a closed-loop error-feedback system that adaptively caches transformer KV features across diffusion steps. We trigger recomputation using event-driven residual dynamics instead of fixed schedules. Our method selectively recomputes high-energy or rapidly-changing tokens while reusing cached features for stable high-frequency components. E$^2$-CRF achieves ~2.2 speedup while maintaining sample quality. We demonstrate effectiveness on 5 datasets. Our caching strategy naturally aligns with the diffusion process's structure-to-detail progression. We include sufficient-condition error and complexity bounds under standard regularity assumptions (Appendix), alongside empirical validation. Our code is available at this https URL and is also integrated in this https URL.
### Title:
          RecoverFormer: End-to-End Contact-Aware Recovery for Humanoid Robots
 - **Authors:** Zihui Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humanoid robots operating in unstructured environments must recover from unexpected disturbances-a capability that remains challenging for end-to-end control policies. We present RECOVERFORMER, a fully end-to-end humanoid recovery policy that learns when and how to switch among recovery behaviors-including compensatory stepping, hand-environment contact, and center-of-mass reshaping-while maintaining robust performance under model mismatch. The architecture combines a causal transformer over a 50-step observation history with two novel heads: a latent recovery mode that enables smooth transitions among distinct recovery strategies, and a contact affordance head that predicts which environmental surfaces (walls, railings, table edges) are beneficial for stabilization. We evaluate RECOVERFORMER on the Unitree G1 humanoid in MuJoCo. Trained only on open floor, RECOVERFORMER transfers zero shot to walled environments, achieving 100% recovery success across 100-300 N pushes and across wall distances from 0.25-1.4m. Under zero-shot dynamics mismatch, RECOVERFORMER reaches 75.5% at plus +25% mass, 89% under 30 ms latency, 91.5% at low friction, and 99% under compound friction, latency and mass perturbation. The learned latent modes specialize across force regimes without mode-level supervision, validated by t-SNE analysis of 300 episodes. Taken together, these results show that a single end-to-end policy can deliver multi-modal, contact aware humanoid recovery that generalizes across perturbation magnitude, contact geometry, and dynamics shift.
### Title:
          Secure eFPGA-Enabled Edge LLM Inference: Architectural and Hardware Countermeasures
 - **Authors:** Voktho Das, M Zafir Sadik Khan, Jafar Vafaei, Kimia Azar, Hadi Kamali
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Edge deployment of transformer-based models increasingly relies on ASIC accelerators due to their high performance and energy efficiency, achieved through optimized dataflows, specialized architectures, low-bitwidth computation, and efficient memory hierarchies. However, these advantages come with significant security vulnerabilities. ASIC-based DNN accelerators are susceptible to side-channel attacks (e.g., power, electromagnetic, and timing analysis) and fault injection attacks (e.g., voltage manipulation, clock glitches, and memory perturbations), which can lead to model extraction or compromised inference integrity. Furthermore, threats introduced during design and fabrication, such as hardware Trojans or untrusted third-party IPs, further expand the attack surface. To address these challenges, we explore a hybrid ASIC+eFPGA architecture that combines the efficiency of ASICs with the flexibility of reconfigurable logic. The integrated eFPGA enables security-oriented mechanisms such as adaptive runtime monitoring, side-channel mitigation and post-deployment patching. By leveraging these capabilities, the proposed approach enhances system resilience against both runtime and supply-chain attacks, while preserving the performance benefits of ASIC-based transformer inference.
### Title:
          From Pixels to Explanations: Interpretable Diabetic Retinopathy Grading with CNN-Transformer Ensembles, Visual Explainability and Vision-Language Models
 - **Authors:** Pir Bakhsh Khokhar, Carmine Gravino, Fabio Palomba, Sule Yildirim Yayilgan, Sarang Shaikh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The quality of diabetic retinopathy (DR) screening relies on the ability to correctly grade severity; however, many deep-learning (DL) classifiers cannot be easily interpreted in the clinical context. This study presents a methodology that combines strong discriminative models with multimodal explanations, converting retinal pixels into clinically interpretable outputs. Using the APTOS 2019 benchmark, we evaluated six representative CNN- and transformer-based backbones under a controlled protocol with stratified five-fold cross-validation. We then compared ensembling strategies (hard voting, weighted soft voting, stacking) and investigated a hybrid class-level fusion variant to exploit grade-specific advantages. For interpretability, we produced Grad-CAM++ visual attribution maps and short textual rationales using vision-language models (VLMs) conditioned on the fundus image and classifier outputs under conservative prompting constraints. Modern CNN backbones (ResNet-50 and ConvNeXt-Tiny) provided the strongest single-model baselines, with cross-validated QWK up to 0.919 and 0.914, respectively. Ensembling improved ordinal agreement, and weighted soft voting was the most consistent across folds (QWK 0.934 +/- 0.017). Hybrid class-level fusion was competitive but did not yield a statistically reliable improvement over standard fusion in paired fold comparisons (Holm-adjusted p >= 1.000). For explanation quality, Grad-CAM++ offered plausible but coarse localization, and VLM rationales were generally grade-consistent. Quantitatively, VLM variants showed a trade-off between clinical completeness and template-level semantic similarity (coverage 0.700 vs. BERTScore 0.072), while image-text alignment was comparable (CLIPScore approximately 0.34).
### Title:
          CNN-ViT Fusion with Adaptive Attention Gate for Brain Tumor MRI Classification: A Hybrid Deep Learning Model
 - **Authors:** Syed Ibad Hasnain, Muhammad Faris, Hafiza Syeda Yusra Tirmizi, Rabail Khowaja, Hafsa Israr
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Early detection and classifying brain tumors using Magnetic Resonance Imaging (MRI) images is highly important but difficult to extract in medical images. Convolutional Neural Networks (CNNs) are good at capturing both local texture and spatial information whereas Vision Transformers (ViTs) are good at capturing long-range global dependencies. We propose a new hybrid architecture that combines a SqueezeNet-style CNN branch with a MobileViT-style global transformer branch, through an Adaptive Attention Gate mechanism, in this paper. The gate learns dynamically per-sample, per-feature weights to weight the contribution of each branch, allowing context-sensitive merging of local and global representations. The proposed model has a test accuracy of 97.60, a precision of 97.30, a recall of 97.50, an F1-score of 97.40, and a macro-average area under the curve (AUC) of 0.9946 with a trained and evaluated on the Brain Tumor MRI Dataset (Kaggle). These scores are higher than single CNN and ViT baselines, and current competitive fusion methods, showing that dynamic feature weighting is an effective way to classify medical images.
### Title:
          BSViT: A Burst Spiking Vision Transformer for Expressive and Efficient Visual Representation Learning
 - **Authors:** Hongxiang Peng, Dewei Bai, Hong Qu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking Vision Transformers (S-ViTs) offer a promising framework for energy-efficient visual learning. However, existing designs remain limited by two fundamental issues: the restricted information capacity of binary spike coding and the dense token interactions introduced by global self-attention. To address these challenges, this work proposes BSViT, a burst spiking-driven Vision Transformer featuring a Dual-Channel Burst Spiking Self-Attention (DBSSA) mechanism. DBSSA encodes queries with binary spikes and keys with burst spikes to enhance representational capacity. The value pathway adopts dual excitatory and inhibitory binary channels, enabling signed modulation and richer spike interactions. Importantly, the entire attention operation preserves addition-only computation, ensuring compatibility with energy-efficient neuromorphic hardware. To further reduce spike activity and incorporate spatial priors, a patch adjacency masking strategy is introduced to restrict attention to local neighborhoods, resulting in structure-aware sparsity and reduced computational overhead. In addition, burst spike coding is systematically integrated across the network to increase spike-level representational capacity beyond conventional binary spiking. Extensive experiments on both static and event-based vision benchmarks demonstrate that BSViT consistently outperforms existing spiking Transformers in accuracy while maintaining competitive energy efficiency.
### Title:
          MotionHiFlow: Text-to-motion via hierarchical flow matching
 - **Authors:** Heng Li, Xiaotong Lin, Ling-An Zeng, Yulei Kang, Shuai Li, Jian-Fang Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-to-motion generation aims to generate 3D human motions that are tightly aligned with the input text while remaining physically plausible and rich in fine-grained detail. Although recent approaches can produce complex and natural movements, they usually operate at only one temporal scale, which limits both semantic alignment and temporal coherence. Inspired by the fact that complex motions are conceptualized hierarchically rather than at a single temporal scale in the human cognitive system, we propose \textit{MotionHiFlow}, a hierarchical flow matching framework to generate motion progressively by constructing flow path from low to high temporal scales. The flows at lower scales capture high-level semantics and coarse motion structures, while flows at higher scales refine temporal details. To link the flows across scales, we introduce a novel cross-scale transition process, ensuring continuity and preserving noise consistency. Furthermore, by integrating a Text-Motion Diffusion Transformer and a topology-aware Motion VAE, MotionHiFlow explicitly models structural dependencies among joints via joint-aware positional encoding and skeletal topology, enabling precise semantic alignment alongside fine-grained motion details. Extensive experiments on HumanML3D and KIT-ML benchmarks demonstrate state-of-the-art performance, with ablation studies confirming the effectiveness of the hierarchical design and key components. Code is available at this https URL.
### Title:
          Contrastive Learning for Multimodal Human Activity Recognition with Limited Labeled Data
 - **Authors:** Long Jing, Zhixiong Yang, Yajun Zhang, Xinlong Feng
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human activity recognition serves as the foundation for various emerging applications. In recent years, researchers have used collaborative sensing of multi-source sensors to capture complex and dynamic human activities. However, multimodal human activity sensing typically encounters highly heterogeneous data across modalities and label scarcity, resulting in an application gap between existing solutions and real-world needs. In this paper, we propose CLMM, a general contrastive learning framework for human activity recognition that achieves effective multimodal recognition with limited labeled data. CLMM employs a novel two-stage training strategy. In the first stage, CLMM employs a CNN-DiffTransformer encoder to capture cross-modal shared information by extracting local and global features. Meanwhile, a hard-positive samples weighting algorithm enhances gradient propagation to reinforce shared learning. In the second stage, a dual-branch architecture combining quality-guided attention and bidirectional gated units captures modality-specific information, while a primary-auxiliary collaborative training strategy fuses both shared and modality-specific information. Experimental results on three public datasets demonstrate that CLMM significantly improves state-of-the-art baselines in both recognition accuracy and convergence performance.
### Title:
          Robust Audio-Text Retrieval via Cross-Modal Attention and Hybrid Loss
 - **Authors:** Meizhu Liu, Matthew Rowe, Amit Agarwal, Michael Avendi, Yassi Abbasi, Hitesh Laxmichand Patel, Paul Li, Kyu J. Han, Tao Sheng, Sujith Ravi, Dan Roth
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Audio-text retrieval enables semantic alignment between audio content and natural language queries, supporting applications in multimedia search, accessibility, and surveillance. However, current state-of-the-art approaches struggle with long, noisy, and weakly labeled audio due to their reliance on contrastive learning and large-batch training. We propose a novel multimodal retrieval framework that refines audio and text embeddings using a cross-modal embedding refinement module combining transformer-based projection, linear mapping, and bidirectional attention. To further improve robustness, we introduce a hybrid loss function blending cosine similarity, $\mathcal{L}_{1}$, and contrastive objectives, enabling stable training even under small-batch constraints. Our approach efficiently handles long-form and noisy audio (SNR 5 to 15) via silence-aware chunking and attention-based pooling. Experiments on benchmark datasets demonstrate improvements over prior methods.
### Title:
          TEMPO: Transformers for Temporal Disease Progression from Cross-Sectional Data
 - **Authors:** Hongtao Hao, Joseph L. Austerweil
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event-Based Models (EBMs) infer biomarker progression from cross-sectional data but typically only as ordinal sequences and rely on rigid model assumptions. We propose \textsc{Tempo}, a Transformer architecture that learns both ordinal and continuous event sequences through simulation-based supervised learning. \textsc{Tempo} uses two Transformer modules: one treats biomarkers as tokens to infer event sequencing; the other treats patients as tokens, representing each by their per-biomarker abnormality profile, to infer patients' disease stages. On synthetic benchmarks, \textsc{Tempo} reduces normalized Kendall's Tau distance by 52.89\% and staging MAE by 25.33\% compared to state-of-the-art SA-EBM, with larger reductions in high-dimensional settings (58.88\% and 61.10\%). Applied to ADNI, \textsc{Tempo} recovers a biologically plausible Alzheimer's progression: early medial temporal atrophy, followed by amyloid accumulation and cognitive decline, and late-stage tau pathology with terminal acceleration of global neurodegeneration -- broadly consistent with established disease models. \textsc{Tempo} also eliminates the need to derive custom inference algorithms and enables rapid empirical comparison of generative hypotheses.
### Title:
          When Context Sticks: Studying Interference in In-Context Learning
 - **Authors:** Hanna Rød, Dagny Streit, Nils Valseth Selte, Justin Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper investigates context stickiness in in-context learning (ICL), a phenomenon where earlier examples in a prompt interfere with a transformer's ability to adapt to later tasks. Using synthetic regression tasks over linear and quadratic functions, we examine how models trained under sequential, mixed, and random curricula handle abrupt task switches during inference. By sweeping over structured combinations of misleading linear examples followed by recovery quadratic examples, we quantify how prior context biases prediction error and how quickly models realign. Our results show strong evidence of persistent interference: more preceding linear examples reliably degrade quadratic predictions, while additional quadratic examples reduce error but with diminishing returns. We further find that training curricula significantly modulate resilience, with sequential training on the target function class yielding the fastest recovery, and surprisingly, random training producing the least robust behavior.
### Title:
          Resource-Constrained UAV-Based Weed Detection for Site-Specific Management on Edge Devices
 - **Authors:** Linyuan Wang, Haibo Yao, Te-Ming Tseng, Kelvin Betitame, Xin Sun, Hanbo Huang, Dong Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Weeds compete with crops for light, water, and nutrients, reducing yield and crop quality. Efficient weed detection is essential for site-specific weed management (SSWM). Although deep learning models have been deployed on UAV-based edge systems, a systematic understanding of how different model architectures perform under real-world resource constraints is still lacking. To address this gap, this study proposes a deployment-oriented framework for real-time UAV-based weed detection on resource-constrained edge platforms. The framework integrates UAV data acquisition, model development, and on-device inference, with a focus on balancing detection accuracy and computational efficiency. A diverse set of state-of-the-art object detection models is evaluated, including convolution-based YOLO models (v8-v12) and transformer-based RT-DETR models (v1-v2). Experiments on three edge devices (Jetson Orin Nano, Jetson AGX Xavier, and Jetson AGX Orin) demonstrate clear trade-offs between accuracy and inference latency across models and hardware configurations. Results show that high-capacity models achieve up to 86.9% mAP50 but suffer from high latency, limiting real-time deployment. In contrast, lightweight models achieve 66%-71% mAP50 with significantly lower latency, enabling real-time performance. Among all models, RT-DETRv2-R50-M achieves competitive accuracy (79% mAP50) with improved efficiency, while YOLOv10n provides the fastest inference speed. YOLOv11s and RT-DETRv2-R50-M offer the best balance between accuracy and speed, making them strong candidates for real-time UAV deployment.
### Title:
          From Edges to Depth: Probing the Spatial Hierarchy in Vision Transformers
 - **Authors:** Jainum Sanghavi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers trained only on image classification routinely transfer to tasks that demand spatial understanding, yet they receive no spatial supervision during pretraining. We ask where and how robustly such structure is encoded. Probing a frozen ViT-B/16 layerwise for two complementary properties, local patch boundaries (BSDS500) and per-patch depth (NYU Depth V2), reveals a clear hierarchy: boundary structure becomes linearly decodable at layers 5-6 (AP = 0.833), while depth, which requires integrating global cues, peaks two to three layers later at layer 8 (MAE = 0.0875). Both signals collapse at the final classification layer, and random-weight controls confirm the encodings are learned rather than architectural. Causal interventions add specificity: ablating the single direction a linear depth probe reads degrades depth decoding by up to 165%, while ablating any other direction changes it by less than 1%. Targeted activation patching along that direction shows the depth signal is partially re-derived at each layer rather than passively carried in the residual stream, with mid-layer interventions persisting most strongly downstream. The result is that a classification-trained ViT develops an actively maintained spatial hierarchy that mirrors the early-to-late progression observed in the primate visual cortex.
### Title:
          A Benchmark Suite of Reddit-Derived Datasets for Mental Health Detection
 - **Authors:** Khalid Hasan, Jamil Saquer
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Information Retrieval (cs.IR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The growing availability of online support groups has opened up new windows to study mental health through natural language processing (NLP). However, it is hindered by a lack of high-quality, well-validated datasets. Existing studies have a tendency to build task-specific corpora without collecting them into widely available resources, and this makes reproducibility as well as cross-task comparison challenging. In this paper, we present a uniform benchmark set of four Reddit-based datasets for disjoint but complementary tasks: (i) detection of suicidal ideation, (ii) binary general mental disorder detection, (iii) bipolar disorder detection, and (iv) multi-class mental disorder classification. All datasets were established upon diligent linguistic inspection, well-defined annotation guidelines, and human-judgmental verification. Inter-annotator agreement metrics always exceeded the baseline agreement score of 0.8, ensuring the labels' trustworthiness. Previous work's evidence of performance on both transformer and contextualized recurrent models demonstrates that these models receive excellent performances on tasks (F1 ~ 93-99%), further validating the usefulness of the datasets. By combining these resources, we establish a unifying foundation for reproducible mental health NLP studies with the ability to carry out cross-task benchmarking, multi-task learning, and fair model comparison. The presented benchmark suite provides the research community with an easy-to-access and varied resource for advancing computational approaches toward mental health research.
### Title:
          Hybrid JIT-CUDA Graph Optimization for Low-Latency Large Language Model Inference
 - **Authors:** Divakar Kumar Yadav, Tian Zhao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) have achieved strong performance across natural language and multimodal tasks, yet their practical deployment remains constrained by inference latency and kernel launch overhead, particularly in interactive, short-sequence settings. This paper presents a hybrid runtime framework that combines Just-In-Time (JIT) compilation with CUDA Graph execution to reduce launch overhead while preserving runtime flexibility during autoregressive decoding. The framework partitions transformer inference into static components executed via CUDA Graph replay and dynamic components handled through JIT-compiled kernels, enabling asynchronous graph capture and reuse across decoding steps. We evaluate the proposed approach on LLaMA-2 7B using single-GPU, batch-size-one inference across prompt lengths from 10 to 500 tokens. Experimental results show that the hybrid runtime reduces Time-to-First-Token (TTFT) by up to 66.0% and achieves lower P99 latency compared with TensorRT-LLM in this regime. These results indicate that hybrid JIT-CUDA Graph execution can effectively reduce inference latency and variance for short-sequence LLM workloads, making it a practical optimization strategy for latency-sensitive AI applications.
### Title:
          Supernodes and Halos: Loss-Critical Hubs in LLM Feed-Forward Layers
 - **Authors:** Audrey Cherilyn, Houman Safaai
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study the organization of channel-level importance in transformer feed-forward networks (FFNs). Using a Fisher-style loss proxy (LP) based on activation-gradient second moments, we show that loss sensitivity is concentrated in a small set of channels within each layer. In Llama-3.1-8B, the top 1% of channels per layer accounts for a median of 58.7% of LP mass, with a range of 33.0% to 86.1%. We call these loss-critical channels supernodes. Although FFN layers also contain strong activation outliers, LP-defined supernodes overlap only weakly with activation-defined outliers and are not explained by activation power or weight norms alone. Around this core, we find a weaker but consistent halo structure: some non-supernode channels share the supernodes' write support and show stronger redundancy with the protected core. We use one-shot structured FFN pruning as a diagnostic test of this organization. At 50% FFN sparsity, baselines that prune many supernodes degrade sharply, whereas our SCAR variants explicitly protect the supernode core; the strongest variant, SCAR-Prot, reaches perplexity 54.8 compared with 989.2 for Wanda-channel. The LP-concentration pattern appears across Mistral-7B, Llama-2-7B, and Qwen2-7B, remains visible in targeted Llama-3.1-70B experiments, and increases during OLMo-2-7B pretraining. These results suggest that LLM FFNs develop a small learned core of loss-critical channels, and that preserving this core is important for reliable structured pruning.
### Title:
          Interpretable Physics-Informed Load Forecasting for U.S. Grid Resilience: SHAP-Guided Ensemble Validation in Hybrid Deep Learning Under Extreme Weather
 - **Authors:** Md Abubakkar, Sajib Debnath, Md. Uzzal Mia
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate short-term electricity load forecasting is a cornerstone of U.S. grid reliability; however, prevailing deep learning models remain opaque, limiting operator trust during extreme weather. A unified, interpretable, physics-informed ensemble framework is proposed, integrating a Convolutional Neural Network (CNN) branch for local feature extraction and a Transformer branch for long-range dependency modeling; the branches are fused through a validation-optimized weighted ensemble and regularized by a physics-informed loss derived from the piecewise parabolic temperature-demand relationship of the Electric Reliability Council of Texas (ERCOT) system. Post-hoc interpretability is provided through SHapley Additive exPlanations (SHAP) with the DeepExplainer backend, yielding global and event-level attributions. Using eight years of ERCOT hourly load data (2018-2025) fused with Automated Surface Observing System (ASOS) records from three Texas stations, the framework achieves 713 MW MAE, 812 MW RMSE, and 1.18% MAPE on the test window. For Hampel-flagged extreme events, MAPE falls by 20.7% relative to its Transformer branch and by 40.5% relative to its CNN branch; an ablation confirms that the parabolic and ramp constraints drive a 14.7% RMSE reduction. SHAP analysis reveals a regime shift: temperature dominates under normal operation, whereas wind speed and precipitation become more influential during cold fronts and heatwaves.
### Title:
          Physics-Aware LLM-Based Probabilistic Wind Power Scenario Generation under Extreme Icing Conditions
 - **Authors:** Lei Wang, Ying Zhang, Di Shi, Fei Ding
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurately characterizing wind power uncertainty under icing and post-disaster conditions remains a critical challenge for resilient power system operation. To address this issue, this paper proposes a physics-aware large language model (LLM) framework for probabilistic wind power scenario generation under extreme icing conditions. The proposed framework integrates supervisory control and data acquisition (SCADA)-based physical modeling, multimodal tokenization, and a causal Transformer architecture trained in an autoregressive manner. A physics-aware decoding scheme effectively enforces rated power limits and ramping constraints on the generated trajectories while preserving stochastic diversity. Case studies using real wind turbine data show that the proposed method reproduces icing-induced power degradation and temporal variability observed during extreme weather. The resulting scenarios are physically consistent and high-fidelity, thereby significantly enhancing resilience assessment and recovery planning in renewable-integrated power systems.
### Title:
          ClusterFusion++: Expanding Cluster-Level Fusion to Full Transformer-Block Decoding
 - **Authors:** ChiHeng Jin, Hongche Yu, Xihui Chen
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language model (LLM) decoding is latency-sensitive and often bottlenecked by fragmented operator execution and repeated off-chip materialization of intermediate tensors. Prior work expands fusion scope by leveraging thread-block clusters and on-chip inter-block collectives to fuse attention-side operators such as QKV projection, attention, and output projection. We develop ClusterFusion++, a CUDA-level extension that broadens fusion to the full Transformer decoder block for GPT-NeoX/Pythia models: LayerNorm -> QKV -> RoPE -> decode attention -> output projection -> Post-LN -> MLP -> residual. We additionally engineer a CUDA-Graph-compatible execution mode with persistent Tensor Memory Accelerator (TMA) descriptors to reduce per-step overhead. On an NVIDIA RTX 5090-class GPU, ClusterFusion++ improves throughput by 1.34x for Pythia-2.8B and yields similar gains for Pythia-6.9B, while maintaining high output fidelity (near-token-identical generation, with minor non-determinism from FP16 atomics).
### Title:
          Adaptive Swin Transformer Partitioning over AI-RAN Networks
 - **Authors:** Tam Thanh Nguyen, Yong Hao Pua, Tuan Van Ngo, Mao V. Ngo, Jihong Park, Binbin Chen, Tony Q. S. Quek
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper demonstrates the feasibility of transformer-based split inference for real-time video object detection over dynamic 5G AI-RAN networks. We extend throughput-aware adaptive splitting from CNNs to a Swin Transformer backbone and show that practical split execution is achievable for transformer-based vision models without retraining. To address the large intermediate activations inherent to transformers, we introduce an efficient, accuracy-preserving activation compression pipeline that substantially reduces uplink payload. The complete system -- including adaptive split selection, transformer inference, and compression -- is implemented and validated end-to-end on a real-time detection workload, with distributed UPF (dUPF) integration further reducing user-plane latency and improving runtime stability. Extensive measurements on an NVIDIA Aerial-based AI-RAN testbed jointly account for inference and 5G communication energy, quantifying the latency-energy-privacy trade-offs in realistic deployments.
### Title:
          Talker-T2AV: Joint Talking Audio-Video Generation with Autoregressive Diffusion Modeling
 - **Authors:** Zhen Ye, Xu Tan, Aoxiong Yin, Hongzhan Lin, Guangyan Zhang, Peiwen Sun, Yiming Li, Chi-Min Chan, Wei Ye, Shikun Zhang, Wei Xue
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL); Multimedia (cs.MM); Sound (cs.SD); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Joint audio-video generation models have shown that unified generation yields stronger cross-modal coherence than cascaded approaches. However, existing models couple modalities throughout denoising via pervasive attention, treating high-level semantics and low-level details in a fully entangled manner. This is suboptimal for talking head synthesis: while audio and facial motion are semantically correlated, their low-level realizations (acoustic signals and visual textures) follow distinct rendering processes. Enforcing joint modeling across all levels causes unnecessary entanglement and reduces efficiency. We propose Talker-T2AV, an autoregressive diffusion framework where high-level cross-modal modeling occurs in a shared backbone, while low-level refinement uses modality-specific decoders. A shared autoregressive language model jointly reasons over audio and video in a unified patch-level token space. Two lightweight diffusion transformer heads decode the hidden states into frame-level audio and video latents. Experiments on talking portrait benchmarks show Talker-T2AV outperforms dual-branch baselines in lip-sync accuracy, video quality, and audio quality, achieving stronger cross-modal consistency than cascaded pipelines.
### Title:
          TimingLLM: A Two-Stage Retrieval-Augmented Framework for Pre-Synthesis Timing Prediction from Verilog
 - **Authors:** Armin Abdollahi, Negin Ashrafi, Mehdi Kamal, Massoud Pedram
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Early, tool-free prediction of post-synthesis timing remains a key obstacle to rapid RTL iteration. We introduce TimingLLM, a two-stage retrieval-augmented LLM pipeline that estimates worst negative slack (WNS) and total negative slack (TNS) directly from Verilog. Stage 1 is a fine-tuned LLM that acts as a compact post-synthesis timing oracle, producing path-level arrivals/required times that are summarized into lightweight structural-timing cues (e.g., bag-of-gates counts, critical-path depth, gate-type patterns). Stage 2 is an LLM-based regressor that predicts WNS/TNS and applies a learned diagonal steering vector at the last transformer block, computed from the k nearest timing-labeled modules in a disjoint retrieval bank. On VerilogEval, TimingLLM attains R_WNS = 0.91 (MAPE 12%) and R_TNS=0.97 (MAPE 16%) while running 1.3-1.6 times faster than prior methods. Training uses a new 60k-module Verilog corpus with synthesis reports, which we will release. After training once, TimingLLM can be adapted to new technology libraries and PVT corners by refitting only a small regression head on 1000 labeled modules per setting, consistently outperforming state-of-the-art baselines.
### Title:
          Applications of the Transformer Architecture in AI-Assisted English Reading Comprehension
 - **Authors:** Ping Li
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper studies interpretable and fair artificial intelligence architectures for understanding English reading. Introduced transformer-based models, integrating advanced attention mechanisms and gradient-based feature attribution. The model's lack of interpretability, reduction of algorithmic bias, and unreliable performance in learning environments are the current issues faced in natural language teaching. A unified technical pipeline has been constructed, including adversarial bias correction methods, token-level attribution analysis, and multi-head attention heatmap visualization. Experimental validation was conducted using a large-scale labeled English reading comprehension dataset, and the data partitioning scheme and parameter optimization procedures have been determined. The method significantly outperforms the state-of-the-art models for this task in terms of accuracy and macro-average F1 score; in some aspects, it even surpasses or closely matches the results of human evaluations. In multi-week user experiments, the explainable transformer improved teachers' trust and operability in feedback-based assessments within the scoring system. The proposed method aims to ensure high prediction accuracy and fairness for different learners. This indicates that it is a real-world educational application based on artificial intelligence with a focus on interpretation. Improve the user experience in AI-assisted reading comprehension systems, counteract biases, and enhance the details explained by transformers.
### Title:
          A Synergistic CNN-Transformer Network with Pooling Attention Fusion for Hyperspectral Image Classification
 - **Authors:** Peng Chen, Wenxuan He, Feng Qian, Guangyao Shi, Jingwen Yan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In the hyperspectral image (HSI) classification task, each pixel is categorized into a specific land-cover category or material. Convolutional neural networks (CNNs) and transformers have been widely used to extract local and non-local features in HSI classification. Recent works have utilized a multi-scale vision transformer (ViT) to enhance spectral feature capture and yield promising results. However, most existing methods still face challenges in the effective joint use of spatial-spectral information and in preserving information across layers during the propagation process. To address these issues, we propose a synergistic CNN-Transformer network with pooling attention fusion for HSI classification, which collaboratively utilizes CNNs and ViT to process spatial and spectral features separately. Specifically, we propose a Twin-Branch Feature Extraction (TBFE) module, which employs 3D and 2D convolution in parallel to comprehensively extract spectral and spatial features from HSI. A hybrid pooling attention (HPA) module is designed to aggregate spatial attention. Moreover, a cascade transformer encoder is employed for global spectral feature extraction, and a simple yet efficient cross-layer feature fusion (CFF) module is designed to reduce the loss of crucial information in the previous network layers. Extensive experiments are conducted on several representative datasets to demonstrate the superior performance of our proposed method compared to the state-of-the-art works. Code is available at this https URL.
### Title:
          Neural Grammatical Error Correction for Romanian
 - **Authors:** Teodor-Mihai Cotet, Stefan Ruseti, Mihai Dascalu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Resources for Grammatical Error Correction (GEC) in non-English languages are scarce, while available spellcheckers in these languages are mostly limited to simple corrections and rules. In this paper we introduce a first GEC corpus for Romanian consisting of 10k pairs of sentences. In addition, the German version of ERRANT (ERRor ANnotation Toolkit) scorer was adapted for Romanian to analyze this corpus and extract edits needed for evaluation. Multiple neural models were experimented, together with pretraining strategies, which proved effective for GEC in low-resource settings. Our baseline consists of a small Transformer model trained only on the GEC dataset (F0.5 of 44.38), whereas the best performing model is produced by pretraining a larger Transformer model on artificially generated data, followed by finetuning on the actual corpus (F0.5 of 53.76). The proposed method for generating additional training examples is easily extensible and can be applied to any language, as it requires only a POS tagger
### Title:
          Hardware-Efficient Softmax and Layer Normalization with Guaranteed Normalization for Edge Devices
 - **Authors:** Dawon Choi, Hana Kim, Ji-Hoon Kim
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In Transformer models, non-GEMM (non-General Matrix Multiplication) operations -- especially Softmax and Layer Normalization (LayerNorm) -- often dominate hardware cost due to their nonlinear nature. To address this, previous approximation studies mainly target rank-oriented tasks, which is acceptable for classification. However, edge Natural Language Processing (NLP) applications and edge generative AI are largely evaluated based on score-oriented tasks, so normalization-guaranteed non-GEMM operations are essential. We propose a hardware-efficient Softmax and LayerNorm with Guaranteed Normalization for Edge devices. Our design employs hardware-efficient approximation methods while preserving the normalization (Softmax: $\sum p = 1$, LayerNorm: $\sigma = 1$). Our architecture is described in Verilog HDL and synthesized using the Samsung 28nm CMOS process. In accuracy evaluation, we achieve high accuracy with minimal degradation: GLUE +0.07%, SQuAD -0.01%, perplexity -0.09%. Implementation results show that our architecture is small: $942\,\mu m^2$ for Softmax, $1199\,\mu m^2$ for LayerNorm. Compared to the state of the art, we achieve up to 11x and 14x reduction in area, respectively.
### Title:
          BVI-Mamba: Video Enhancement Using a Visual State-Space Model for Low-Light and Underwater Environments
 - **Authors:** Guoxi Huang, Ruirui Lin, Yini Li, David R. Bull, Nantheera Anantrasirichai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Videos captured in low-light and underwater conditions often suffer from distortions such as noise, low contrast, color imbalance, and blur. These issues not only limit visibility but also degrade automatic tasks like detection. Post-processing is typically required but can be time-consuming. AI-based tools for video enhancement also demand significantly more computational resources compared to image-based methods. This paper introduces a novel framework, Visual Mamba, designed to reduce memory usage and computational time by leveraging the Visual State Space (VSS) model. The framework consists of two modules: (i) a feature alignment module, where spatio-temporal displacement between input frames is registered in the feature space, and (ii) an enhancement module, where noise removal and brightness adjustment are performed using a UNet-like architecture, with all convolutional layers replaced by VSS blocks. Experimental results show that the Visual Mamba technique outperforms Transformer and convolution-based models in both low-light and underwater video enhancement tasks. Code is available on line at this https URL.
### Title:
          Rank, Head-Channel Non-Identifiability, and Symmetry Breaking: A Precise Analysis of Representational Collapse in Transformers
 - **Authors:** Giansalvo Cirrincione
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A widely cited result by Dong et al. (2021) showed that Transformers built from self-attention alone, without skip connections or feed-forward layers, suffer from rapid rank collapse: all token representations converge to a single direction. The proposed remedy was the MLP. We show that this picture, while correct in the regime studied by Dong, is incomplete in ways that matter for architectural understanding. Three results are established. First, layer normalisation is precisely affine-rank-neutral: it preserves the affine rank of the token representation set exactly. The widespread claim that LN "plays no role" is imprecise; the correct statement is sharper. Second, residual connections generically obstruct rank collapse in real Transformers such as BERT-base, in a measure-theoretic sense, without contribution from the MLP. The MLP's irreplaceable function is different: generating feature directions outside the linear span of the original token embeddings, which no stack of attention layers can produce. Third, a phenomenon distinct from rank collapse is identified: head-channel non-identifiability. After multi-head attention sums per-head outputs through the output projection, individual contributions cannot be canonically attributed to a specific head; n(H-1)d_k degrees of freedom per layer remain ambiguous when recovering a single head from the mixed signal. The MLP cannot remedy this because it acts on the post-summation signal. A constructive partial remedy is proposed: a position-gated output projection (PG-OP) at parameter overhead below 1.6% of the standard output projection. The four collapse phenomena identified in the literature -- rank collapse in depth, in width, head-channel non-identifiability, and entropy collapse -- are unified under a symmetry-breaking framework, each corresponding to a distinct symmetry of the Transformer's forward pass.
### Title:
          Caries DETR: Tooth Structure-aware Prior and Lesion-aware Dynamic Loss Refinement for DETR Based Caries Detection
 - **Authors:** Xuefen Liu, Xinquan Yang, Mianjie Zheng, Kun Tang, Xuguang Li, Xiaoqi Guo, Linlin Shen, He Meng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As dental caries appear as subtle, low-contrast lesions in intraoral imaging, existing deep learning models face significant challenges in the early detection of caries. While recent Transformer-based detectors have shown promising results in natural images, they often fail to capture the domain-specific anatomical priors crucial for dental caries detection. In this paper, we propose Caries-DETR, a specialized Transformer framework for caries detection in intraoral images. A Tooth Structure-aware Query Initialization (TSQI) is designed, leveraging large-scale intraoral photograph pre-training and a structure perception branch (SPB) to integrate high-frequency structural priors, guiding the model to focus on anatomically significant lesion areas. Furthermore, we design a Lesion-aware Dynamic Loss Refinement (LDLR) to implement quality-driven hard mining through adaptive loss reweighting based on lesion size, anatomical relevance, and prediction quality, optimizing detection for subtle lesions. Extensive experiments on two public datasets (i.e., AlphaDent and DentalAI) demonstrate that Caries-DETR achieves a state-of-the-art performance compared to existing methods and exhibits good generalization and robustness. Code and data at this https URL}{this https URL.
### Title:
          AIPsy-Affect: A Keyword-Free Clinical Stimulus Battery for Mechanistic Interpretability of Emotion in Language Models
 - **Authors:** Michael Keeman
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability research on emotion in large language models -- linear probing, activation patching, sparse autoencoder (SAE) feature analysis, causal ablation, steering vector extraction -- depends on stimuli that contain the words for the emotions they test. When a probe fires on "I am furious", it is unclear whether the model has detected anger or detected the word "furious". The two readings have very different consequences for every downstream claim about emotion circuits, features, and interventions. We release AIPsy-Affect, a 480-item clinical stimulus battery that removes the confound at the stimulus level: 192 keyword-free vignettes evoking each of Plutchik's eight primary emotions through narrative situation alone, 192 matched neutral controls that share characters, setting, length, and surface structure with the affect surgically removed, plus moderate-intensity and discriminant-validity splits. The matched-pair structure supports linear probing, activation patching, SAE feature analysis, causal ablation, and steering vector extraction under a strong methodological guarantee: any internal representation that distinguishes a clinical item from its matched neutral cannot be doing so on the basis of emotion-keyword presence. A three-method NLP defense battery -- bag-of-words sentiment, an emotion-category lexicon, and a contextual transformer classifier -- confirms the property: bag-of-words methods see only situational vocabulary, and a contextual classifier detects affect (p < 10^-15) but cannot identify the category (5.2% top-1 vs. 82.5% on a keyword-rich control). AIPsy-Affect extends our earlier 96-item battery (arXiv:2603.22295) by a factor of four and is released openly under MIT license.
### Title:
          Quasi-Equivariant Metanetworks
 - **Authors:** Viet-Hoang Tran, An Nguyen, Benoît Guérand, Thieu N. Vo, Tan M. Nguyen
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Metanetworks are neural architectures designed to operate directly on pretrained weights to perform downstream tasks. However, the parameter space serves only as a proxy for the underlying function class, and the parameter-function mapping is inherently non-injective: distinct parameter configurations may yield identical input-output behaviors. As a result, metanetworks that rely solely on raw parameters risk overlooking the intrinsic symmetries of the architecture. Reasoning about functional identity is therefore essential for effective metanetwork design, motivating the development of equivariant metanetworks, which incorporate equivariance principles to respect architectural symmetries. Existing approaches, however, typically enforce strict equivariance, which imposes rigid constraints and often leads to sparse and less expressive models. To address this limitation, we introduce the novel concept of quasi-equivariance, which allows metanetworks to move beyond the rigidity of strict equivariance while still preserving functional identity. We lay down a principled basis for this framework and demonstrate its broad applicability across diverse neural architectures, including feedforward, convolutional, and transformer networks. Through empirical evaluation, we show that quasi-equivariant metanetworks achieve good trade-offs between symmetry preservation and representational expressivity. These findings advance the theoretical understanding of weight-space learning and provide a principled foundation for the design of more expressive and functionally robust metanetworks.
### Title:
          Transformer as an Euler Discretization of Score-based Variational Flow
 - **Authors:** Huadong Liao
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite the Transformer's dominance across machine learning, its architecture remains largely heuristic and lacks a unified theoretical foundation. We introduce Score-based Variational Flow (SVFlow), a continuous-time dynamical system for representation learning in which the state evolves according to a variational posterior-weighted average of conditional log-likelihood scores, and provide a principled basis for regularization through variational consistency. We show that forward Euler discretization of spherical SVFlow exactly recovers the Transformer architecture. Multi-head attention approximates SVFlow vector field via a vMF kernel-smoothed posterior, while MoE/FFN approximates it in a relaxed network-based way, and the residual-normalization block implements a relaxed retraction that maintains spherical geometry. This unification explains why attention trains stably without explicit regularization while MoE requires auxiliary balancing losses. Experiments on pre-trained language models with prefix shuffling show that SVFlow-induced metrics correlate with task performance, reveal depth-dependent sensitivity, and reflect the intrinsic dynamics of attention.
### Title:
          Modeling Induced Pleasure through Cognitive Appraisal Prediction via Multimodal Fusion
 - **Authors:** Nastaran Dab, Raziyeh Zall, Mohammadreza Kangavari
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Human-Computer Interaction (cs.HC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal affective computing analyzes user-generated social media content to predict emotional states. However, a critical gap remains in understanding how visual content shapes cognitive interpretations and elicits specific affective experiences such as pleasure. This study introduces a novel computational model to infer video-induced pleasure via cognitive appraisal variables. The proposed model addresses four challenges: (1) noisy and inconsistent human labels, (2) the semantic gap between "positive emotions" and "pleasure," (3) the scarcity of pleasure-specific datasets, and (4) the limited interpretability of existing black-box fusion methods. Our approach integrates data-driven and cognitive theory-driven methods, using cognitive appraisal theory and a fuzzy model within an innovative framework. The model employs transformer-based architectures and attention mechanisms for fine-grained multimodal feature extraction and interpretable fusion to capture both inter- and intra-modal dynamics associated with pleasure. This enables the prediction of underlying appraisal variables, thereby bridging the semantic gap and enhancing model explainability beyond conventional statistical associations. Experimental results validate the efficacy of the proposed method in detecting video-induced pleasure, achieving a peak accuracy of 0.6624 in predicting pleasure levels. These findings highlight promising implications for affective content recommendation, intelligent media creation, and advancing our understanding of how digital media influences human emotions.
### Title:
          Edit Where You Mean: Region-Aware Adapter Injection for Mask-Free Local Image Editing
 - **Authors:** Honghao Cai, Xiangyuan Wang, Yunhao Bai, Haohua Chen, Tianze Zhou, Runqi Wang, Wei Zhu, Yibo Chen, Xu Tang, Yao Hu, Zhen Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large diffusion transformers (DiTs) follow global editing instructions well but consistently leak local edits into unrelated regions, because joint-attention architectures offer no explicit channel telling the network where to apply the edit. We introduce REDEdit, a co-trained, instruction- and region-aware adapter framework that retrofits a frozen DiT into a precise local editor without modifying its backbone weights. A lightweight Block Adapter at every transformer block injects a structured condition stream that factorizes what to edit (instruction semantics) from where to edit (spatial mask); a learned SpatialGate routes the adapter signal selectively into the edit region while keeping the rest of the image near-identical to the source; and a Region-Aware Loss focuses the training objective on the changing pixels. Because these components make the backbone's internal representation mask-aware end-to-end, a thin MaskPredictor head trained jointly with the editor can ground the edit region directly from the instruction and source image eliminating any user-mask requirement at deployment. We evaluate on two complementary benchmarks: MagicBrush (paired ground-truth targets) to measure pixel-level preservation and edit accuracy, and Emu-Edit Test (no ground-truth images, 9 diverse edit categories) to stress-test instruction following and generalization across edit types. On both, REDEdit achieves state-of-the-art results, simultaneously outperforming mask-free and oracle-mask baselines. A seven-variant ablation cleanly isolates the contribution of each component.
### Title:
          On the Generalization Properties of Selective State-Space Models for Filtering Tasks for Unknown Systems
 - **Authors:** Alex Tang, M. Emrullah Ildiz, Batin Kurt, Samet Oymak, Necmiye Ozay
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Selective State-Space Models (SSMs) such as Mamba have emerged as an alternative architecture to self-attention based transformers in sequence modeling tasks. Recent works have demonstrated the use of transformers in some filtering and output prediction tasks via in-context learning. In this paper, we analyze whether structured SSMs can work equally well for filtering of unknown systems. In particular, we train the SSM on trajectory samples from a set of systems. At run-time, the SSM is given the outputs of an unknown system from the same set and is expected to predict the next output online. Theoretically, under appropriate assumptions, we derive generalization bounds as to why SSMs succeed in such tasks. Empirically, we demonstrate the performance via several numerical examples. We also discuss the advantages and disadvantages of SSMs versus transformers for this task.
### Title:
          Graph Memory Transformer (GMT)
 - **Authors:** Nicola Zanarini, Niccolò Ferrari
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We investigate whether the Feed-Forward Network (FFN) sublayer in a decoder-only transformer can be replaced by an explicit learned memory graph while preserving the surrounding autoregressive architecture. The proposed Graph Memory Transformer (GMT) keeps causal self-attention intact, but replaces the usual per-token FFN transformation with a memory cell that routes token representations over a learned bank of centroids connected by a learned directed transition matrix. In the base GMT v7 instantiation studied here, each of 16 transformer blocks contains 128 centroids, a 128 * 128 edge matrix, gravitational source routing, token-conditioned target selection, and a gated displacement readout. The cell therefore returns movement from an estimated source memory state toward a target memory state, rather than a retrieved value. The resulting model is a fully decoder-only language model with 82.2M trainable parameters and no dense FFN sublayers, compared with a 103.0M-parameter dense GPT-style baseline used in the evaluation. The base v7 model trains stably and exposes centroid usage, transition structure, and source-to-target movement as directly inspectable quantities of the forward computation. It remains behind the larger dense baseline in validation loss and perplexity (3.5995/36.58 vs. 3.2903/26.85), while showing close zero-shot benchmark behavior under the evaluated setting. These results are not intended as a state-of-the-art claim; they support the viability and structural interpretability of replacing dense within-token transformation with graph-mediated memory navigation. Broader scaling, optimized kernels, and more extensive benchmark evaluation are left for subsequent work.
### Title:
          Cardiac Stability Theory: An Axiomatically Grounded Framework for Continuous Cardiac Health Monitoring via Smartphone Photoplethysmography
 - **Authors:** Timothy Oladunni, Farouk Ganiyu Adewumi
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Cardiac Stability Theory (CST), an axiomatically grounded framework formally defining cardiovascular health as a stability margin around a cardiac dynamical attractor. From four axioms we derive the Cardiac Stability Index (CSI), a composite scalar in [0,1] integrating the largest Lyapunov exponent, recurrence determinism, and signal entropy via time-delay embedding. The ECG-based model (CSISurrogateV2, CNN-Transformer) achieves $R^2=0.8788$, MAE$=0.0234$ on PTB-XL (21,799 recordings). We extend CSI to smartphone PPG via Complementary Domain Transfer (CDT): CSISurrogateV2 generates pseudo-labels for the BUT PPG dataset (48 recordings, 12 subjects), training TinyCSINet (122,849 parameters), achieving MAE$=0.0557$, $\rho=0.660$ on the held-out test set ($n=1065$ windows) at ${<}30$ ms mobile latency. CDT is validated on BIDMC, Welltory, and RWS-PPG. Paired validation on 5,035 BIDMC windows yields $r=0.454$ ($\rho=0.485$, $p<10^{-295}$), confirming correlated cardiac stability across modalities. CSI is negatively correlated with age (slope $= -0.000225$ CSI/year, PTB-XL), discriminates atrial fibrillation from normal sinus rhythm (AUROC$=0.89$), and is robust under Perturbation Invariance Training (max AUC drop 1.65\%). We derive HeartSpan, a longitudinal stability metric relative to population age norms, enabling continuous non-invasive cardiac monitoring from commodity smartphones for longevity tracking and cardiac risk stratification.
### Title:
          Machine Learning and Deep Learning Models for Short Term Electricity Price Forecasting in Australia's National Electricity Market
 - **Authors:** Wei Lu, Jay Wang, Dingli Duan, Ding Mao, Caiyi Song, John Huang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Short term electricity price forecast is essential in competitive power markets, yet electricity price series exhibit high volatility, irregularity, and non-stationarity. This phenomenon is pronounced in the South Australian region of the National Electricity Market, where high renewable penetration drives price volatility and frequent negative price intervals, while structural changes such as the transition to five-minute settlement further complicate forecast. To address these challenges, this study develops a unified benchmark framework. Under identical data preprocessing, feature engineering with lag features, rolling statistics, cyclic temporal encodings, and so on, and an 85% to 15% chronological train test split, six algorithms are systematically compared, including AWMLSTM, CatBoost, GBRT, LSTM, LightGBM, and SVR. The results show that for price prediction, tree-based models, especially GBRT with an R squared value of 0.88, generally outperform LSTM and SVR. However, all models achieve a mean absolute percentage error above 90%, and more than 65% of GBRT predictions have relative errors above 10%, which highlights the inherent difficulty of price forecast. For demand prediction, all models perform substantially better than in price prediction. AWMLSTM and GBRT achieve an R2 value of 0.96 with mean absolute percentage error below 32%, and GBRT has 74.37% of samples within 5% error, while LSTM and SVR perform less accurately in both tasks. Future improvements should focus on hybrid models such as tree plus transformers, data augmentation for extreme events, and error correction to better capture price spikes.
### Title:
          AMAVA: Adaptive Motion-Aware Video-to-Audio Framework for Visually-Impaired Assistance
 - **Authors:** Benjamin Klein, Kazi Ruslan Rahman, Sanchita Ghose
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Navigational aids for blind and low vision individuals struggle conveying dynamic real-world environments, leading to cognitive overload from continuous, undifferentiated feedback. We present AMAVA, a novel real-time video-to-audio framework that converts mobile device video into contextually relevant sound effects or text-to-speech descriptions. We propose a motion-aware pipeline using a lightweight AI classification model to distinguish between low and high-movement scenes followed by a real-time text-to-audio synthesis pipeline to enhance environmental perception more efficiently. In static environments, AMAVA generates spoken audio scene descriptions for situational awareness. In high-movement situations, it prioritizes safety by delivering sound cues, such as spoken hazard alerts and environmental sound effects. These audio outputs are produced by a decoder-only transformer-based vision-language model with mixture-of-experts and cross-modal attention for visual understanding, in conjunction with neural text-to-speech and natural sound synthesis networks. The proposed framework uses prompt-based caching and category-specific throttling to avoid auditory clutter and minimize latency. We present a comprehensive evaluation of the system, including a real-time navigation study comparing a white cane alone versus with AMAVA, that shows a significant increase in user confidence and perceived safety.
### Title:
          DecompKAN: Decomposed Patch-KAN for Long-Term Time Series Forecasting
 - **Authors:** Naveen Mysore
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate time series forecasting in scientific domains such as climate modeling, physiological monitoring, and energy systems benefits from both competitive predictions and model transparency. This work proposes DecompKAN, a lightweight attention-free architecture that combines trend-residual decomposition, channel-wise patching, learned instance normalization, and B-spline Kolmogorov-Arnold Network (KAN) edge functions. Each KAN edge learns an explicit, inspectable 1D scalar function over learned patch-embedding coordinates that can be directly visualized. On standard benchmarks, DecompKAN achieves best or tied-best MSE on 15 of 32 dataset-horizon combinations among selected published baselines, and achieves best or tied-best MSE on 20 of 36 comparisons under a controlled same-recipe evaluation across 9 datasets including the physiological PPG-DaLiA benchmark. The architecture shows particular strength on datasets with smooth temporal dynamics (Solar -17%, ECL -10% vs. iTransformer, Weather) and physiological time series. Visualization of learned edge functions reveals qualitatively different latent nonlinearities across domains. Ablation analysis shows that the architectural pipeline (decomposition, patching, normalization) drives performance more than the choice of nonlinear layer, while the KAN formulation enables inspection of learned latent transformations.
### Title:
          Improving Robustness of Tabular Retrieval via Representational Stability
 - **Authors:** Kushal Raj Bhandari, Adarsh Singh, Jianxi Gao, Soham Dan, Vivek Gupta
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Information Retrieval (cs.IR); Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based table retrieval systems flatten structured tables into token sequences, making retrieval sensitive to the choice of serialization even when table semantics remain unchanged. We show that semantically equivalent serializations, such as $\texttt{csv}$, $\texttt{tsv}$, $\texttt{html}$, $\texttt{markdown}$, and $\texttt{ddl}$, can produce substantially different embeddings and retrieval results across multiple benchmarks and retriever families. To address this instability, we treat serialization embedding as noisy views of a shared semantic signal and use its centroid as a canonical target representation. We show that centroid averaging suppresses format-specific variation and can recover the semantic content common to different serializations when format-induced shifts differ across tables. Empirically, centroid representations outrank individual formats in aggregate pairwise comparisons across $\texttt{MPNet}$, $\texttt{BGE-M3}$, $\texttt{ReasonIR}$, and $\texttt{SPLADE}$. We further introduce a lightweight residual bottleneck adapter on top of a frozen encoder that maps single-serialization embeddings towards centroid targets while preserving variance and enforcing covariance regularization. The adapter improves robustness for several dense retrievers, though gains are model-dependent and weaker for sparse lexical retrieval. These results identify serialization sensitivity as a major source of retrieval variance and show the promise of post hoc geometric correction for serialization-invariant table retrieval. Our code, datasets, and models are available at $\href{this https URL}{this https URL}$.
### Title:
          Disagreement as Signals: Dual-view Calibration for Sequential Recommendation Denoising
 - **Authors:** Sijia Li, Min Gao, Zongwei Wang, Zhiyi Liu, Xin Xia, Yi Zhang
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequential recommendation seeks to model the evolution of user interests by capturing temporal user intent and item-level transition patterns. Transformer-based recommenders demonstrate a strong capacity for learning long-range and interpretable dependencies, yet remain vulnerable to behavioral noise that is misaligned with users' true preferences. Recent large language model (LLM)-based approaches attempt to denoise interaction histories through static semantic editing. Such methods neglect the learning dynamics of recommendation models and fail to account for the evolving nature of user interests. To address this limitation, we propose a Dual-view Calibration framework for Sequential Recommendation denoising (DC4SR). Specifically, we introduce a semantic prior, derived from an LLM fine-tuned via labeled historical interactions, to estimate the noise distribution from a semantic perspective. From the learning perspective, we further employ a model-side posterior that infers the noise distribution based on the model's learning dynamics. The disagreement between the two distributions is then leveraged to jointly refine semantic understanding and learning-aware model-side representations. Through iterative updates, dynamic dual-view calibration is achieved for both the global semantic prior and the model-side posterior, enabling consistent alignment with evolving user interests. Extensive experiments demonstrate that DC4SR consistently outperforms strong Transformer-based recommenders and LLM-based denoising methods, exhibiting enhanced robustness across training stages and noise conditions.
### Title:
          Progressive Approximation in Deep Residual Networks: Theory and Validation
 - **Authors:** Wei Wang, Xiao-Yong Wei, Qing Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The Universal Approximation Theorem (UAT) guarantees universal function approximation but does not explain how residual models distribute approximation across layers. We reframe residual networks as a layer-wise approximation process that builds an approximation trajectory from input to target, and prove the existence of progressive trajectories where error decreases monotonically with depth. It reveals that residual networks can implement structured, step-by-step refinement rather than end-to-end (E2E) black-box mapping. Building on this, we propose Layer-wise Progressive Approximation (LPA), a theoretically grounded training principle that explicitly aligns each layer with its residual target to realize such trajectories. LPA is architecture-agnostic: we observe progressive behavior in residual FNNs, ResNets, and Transformers across tasks including complex surface fitting, image classification, and NLP with LLMs for generation and classification. Crucially, this enables ``train once, use $N$ models": a single network yields useful predictions at every depth, supporting efficient shallow inference without retraining. Our work unifies approximation theory with practical deep learning, providing a new lens on representation learning and a flexible framework for multi-depth deployment. The source code will be released unpon acceptance at https://(open\_upon\_acceptance).
### Title:
          PointTransformerX:Portable and Efficient 3D Point Cloud Processing without Sparse Algorithms
 - **Authors:** Laurenz Reichardt, Nikolas Ebert, Oliver Wasenmüller
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D point cloud perception remains tightly coupled to custom CUDA operators for spatial operations, limiting portability and efficiency on non-NVIDIA, AMD, and embedded hardware. We introduce PointTransformerX (PTX), a fully PyTorch-native vision transformer backbone for 3D point clouds, removing all custom CUDA operators and external libraries while retaining competitive accuracy. PTX introduces 3D-GS-RoPE, a rotary positional embedding that encodes 3D spatial relationships directly in self-attention without neighborhood construction, and further replaces sparse convolutional patch embedding with a linear projection. PTX explores inference-time scaling of attention windows to improve accuracy without retraining. With a redesigned feed-forward network, PTX achieves 98.7\% of PointTransformer V3's accuracy on ScanNet with 79.2\% fewer parameters and executing 1.6\times faster while requiring just 253 MB memory. PTX runs natively on NVIDIA GPUs, AMD GPUs (ROCm), and CPUs, providing an efficient and portable foundation for point cloud perception.
### Title:
          SolarTformer: A Transformer Based Deep Learning Approach for Short Term Solar Power Forecasting
 - **Authors:** Ankan Basu, Jyotiraditya Roy, Aditya Datta, Prayas Sanyal, Sumanta Banerjee
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate forecasting of solar power output is essential for efficient integration of renewable energy into the grid. In this study, an attention-based deep learning model, inspired by transformer architecture, is used for short-term solar power forecasting. Our proposed model, "SolarTformer", is designed to predict solar power output from meteorological data. Unlike traditional models, SolarTformer leverages self-attention mechanisms to effectively capture temporal dependencies and spatial variability in solar irradiance. In addition, the proposed methodology includes feeding power station-specific metadata into the model, which helps to generalize between power stations located at different locations and with different panel configurations and in different seasons. Our experiments demonstrate that SolarTformer significantly outperforms previous models on the same data set. In particular, the model exhibits strong performance on both clear and cloudy days, indicating high robustness and generalizability. These findings highlight the potential of attention-based architectures in enhancing the accuracy of solar forecasting, contributing to a more reliable management of renewable energy.
### Title:
          Unconstrained Multi-view Human Pose Estimation with Algebraic Priors
 - **Authors:** Xiaolin Qin, Qianlei Wang, Jiacen Liu, Chaoning Zhang, Fei Zhu, Zhang Yi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recovering 3D human pose from multi-view imagery typically relies on precise camera calibration, which is often unavailable in real-world scenarios, thereby severely limiting the applicability of existing methods. To overcome this challenge, we propose an unconstrained framework that synergizes deep neural networks, algebraic priors, and temporal dynamics for uncalibrated multi-view human pose estimation. First, we introduce the Triangulation with Transformer Regressor (TTR), which reformulates classical triangulation into a data-driven token fusion process to bypass the dependency on explicit camera parameters. Second, to explicitly embed the inherent algebraic relations of the multi-view variety into the learning process, we propose the Gröbner basis Corrector (GC). This pioneering loss formulation enforces constraints derived from the multi-view variety to ensure the neural predictions strictly adhere to the laws of projective geometry. Finally, we devise the Temporal Equivariant Rectifier (TER), which exploits the equivariance property of human motion to impose temporal coherence and structural consistency, effectively mitigating scale ambiguity in uncalibrated settings. Extensive evaluations on standard benchmarks demonstrate that our framework establishes a new state-of-the-art for uncalibrated multi-view human pose estimation. Notably, our approach significantly closes the performance gap between calibration-free methods and fully calibrated oracles.
### Title:
          Monocular Depth Estimation via Neural Network with Learnable Algebraic Group and Ring Structures
 - **Authors:** Qianlei Wang, Kexun Chen, Shaolin Zhang, Hongli Gao, Chaoning Zhang, Xiaolin Qin
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular depth estimation (MDE) has witnessed remarkable progress driven by Convolutional Neural Networks and transformer-based architectures. However, these approaches typically treat the problem as a generic image-to-image regression on Euclidean grids, thereby overlooking the intrinsic algebraic and geometric structures induced by perspective projection. To address this limitation, we propose LAGRNet, a novel framework that fundamentally grounds MDE in algebraic geometry by explicitly embedding learnable group, ring, and sheaf structures into the deep learning pipeline. Modeling feature maps as sections of a sheaf over an approximated image manifold, our method first establishes a Group-defined Feature Manifold (GFM) parameterized by a learned algebraic group action to enforce projective equivariance and robustness against view changes. To facilitate algebraically consistent cross-scale interactions, we subsequently introduce a Ring Convolution Layer (RCL) that formulates feature fusion as a graded ring homomorphism. Furthermore, to ensure global topological consistency, a Sheaf-based Module (SM) aggregates local depth cues via Čech nerve on the image topology. Extensive zero-shot evaluations across the KITTI, NYU-Depth V2, and ETH3D benchmarks demonstrate that LAGRNet significantly outperforms state-of-the-art methods in both accuracy and generalization capabilities.
### Title:
          ARETE: Attention-based Rasterized Encoding for Topology Estimation using HSV-transformed Crowdsourced Vehicle Fleet Data
 - **Authors:** Daniel Fritz, Dimitrios Lagamtzis, Michael Mink, Markus Enzweiler, Steffen Schober
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The continuous advancement of autonomous driving (AD) introduces challenges across multiple disciplines to ensure safe and efficient driving. One such challenge is the generation of High-Definition (HD) maps, which must remain up to date and highly accurate for downstream automotive tasks. One promising approach is the use of crowdsourced data from a vehicle fleet, representing road topology and lane-level features. This work focuses on the generation of centerlines and lane dividers from crowdsourced vehicle trajectories. We adopt a Detection Transformer (DETR)-based approach, where a rasterized representation of vehicle trajectories is used as input to predict vectorized lane representations. Each lane consists of a centerline with an associated direction and corresponding lane dividers that are geometrically constrained by the centerline. Our method includes the extraction of local tiles, from which crowdsourced vehicle trajectories are aggregated. Each tile undergoes a transformation into a rasterized representation encoding both the presence and direction of each trajectory, enabling the prediction of vectorized directed lanes. Experiments are conducted on an internal dataset as well as on the public datasets nuScenes and nuPlan.
### Title:
          Multispectral airborne laser scanning dataset for tree species classification: MS-ALS-SPECIES
 - **Authors:** Matti Hyyppä, Klaara Salolahti, Eric Hyyppä, Xiaowei Yu, Josef Taher, Leena Matikainen, Matti Lehtomäki, Paula Litkey, Teemu Hakala, Harri Kaartinen, Juha Hyyppä, Antero Kukko
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The shift from stand-level to individual-tree-level forest assessments supports improved biodiversity mapping, particularly in boreal ecosystems where tree species like aspen (Populus tremula L.) play a keystone role. While airborne laser scanning (ALS) is the standard for such inventories, a major limitation is the small number of publicly available ALS datasets containing high-quality, field-validated reference data. Furthermore, open multispectral ALS datasets with high-quality field reference data are completely lacking despite the potential of multispectral ALS data for tree species classification. This paper presents and details an open multispectral ALS dataset used in a recent international benchmarking study of machine learning and deep learning methods for tree species classification by Taher et al. (2026). The dataset comprises 6326 segment-level point clouds of individual trees representing nine species in Southern Finland. The point cloud data has been acquired using two multispectral laser scanning systems each operating at three laser wavelengths: a helicopter-borne system (HeliALS) with a point density exceeding 1000 points/m$^2$ and an Optech Titan system with approximately 35 points/m$^2$. We provide a detailed description of field data collection techniques developed in the study to facilitate the collection of high-quality ground truth data in an efficient and scalable manner. Additionally, our article presents new analyses on species classification using multispectral data building upon the initial findings of Taher et al. (2026). Furthermore, we study the relation between classification accuracy and tree height to highlight the versatility of the open dataset and to demonstrate the advantage of the point transformer model for small trees and minority species.
### Title:
          Comparative Evaluation of Modern Deep Learning Methodologies for Portfolio Optimization
 - **Authors:** Samuel Ozechi, Banjo Francis, Wisdom Yakanu, Joe Wayne Byers
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study proposes a portfolio optimization framework that integrates advanced deep learning architectures with traditional financial models to enhance risk-adjusted performance. Using historical data from 2015-2023 across equities, ETFs, and bonds, the research evaluates the predictive power of Graph Neural Networks (GNNs), Deep Reinforcement Learning (DRL), Transformers, and Autoencoders. The models jointly address covariance estimation, return forecasting, dynamic asset allocation, and dimensionality reduction. Hybrid approaches such as Transformer+GNN and Autoencoder+DRL are also explored to capture both relational and temporal market structures. Performance is assessed through backtesting using metrics including volatility, cumulative return, maximum drawdown, annualized return, and Sharpe ratio across seven strategies, including Equal-Weighted, 60/40 allocation, and Mean-Variance Optimization (MVO). Results show that hybrid models provide superior stability and risk control, with Transformer+GNN achieving the lowest volatility and drawdown. MVO, when paired with well-calibrated inputs, delivers the highest cumulative return and Sharpe ratio, highlighting the continued relevance of traditional methods. Standalone DRL underperforms due to limited structural awareness, while Autoencoders exhibit behavior similar to Equal-Weight strategies, emphasizing the need for dynamic policy learning. These findings align with existing literature on relational modeling and feature compression in finance. Overall, the study demonstrates that combining deep learning with financial theory yields robust and adaptive portfolio strategies and suggests exploring latent representations within traditional optimization frameworks to improve scalability and performance.
### Title:
          Beyond the Attention Stability Boundary: Agentic Self-Synthesizing Reasoning Protocols
 - **Authors:** Dahlia Shehata, Ming Li
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As LLM agents transition to autonomous digital coworkers, maintaining deterministic goal-directedness in non-linear multi-turn conversations emerged as an architectural bottleneck. We identify and formalize a systemic failure mode termed the Attention Latch in decoder-only autoregressive Transformers. This phenomenon, a behavioral manifestation of Information Over-squashing, occurs when the cumulative probabilistic weight of historical context overrides mid-task updates, causing agents to remain anchored to obsolete constraints despite explicit contradictory instructions. We propose Self-Synthesizing Reasoning Protocols (SSRP), a metacognitive framework that implements a discrete separation between high-level architectural planning (Architect) and turn-by-turn procedural execution (Executive). We evaluate SSRP across 9K trajectories using the MultiWOZ 2.2 dataset and the Aggregate Pivot Accuracy (APA), a novel metric we validate by mapping its scores to the U-shaped 'Lost in the Middle' curve. We present 3 experimental tiers: a shallow recency-based retrieval pilot, a high-entropy SOP, and a semantic hijacked 3-hop Multi-Fact Synthesis task. Our results empirically locate the Attention Stability Boundary, where stateless Vanilla ReAct baselines for GPT 5.4 collapse to 0.1% success while SSRP achieves a 715X Resilience Lift. We demonstrate statistically significant gains across Gemini 3.1 Pro, Claude Sonnet 4.6 and DeepSeek V3.2. Audits confirm SSRP necessity by proving attentional lapse via a recursive reflexion baseline (100% success); decoupling the latch from positional bias through equidistant stress testing (90% accuracy); and formalizing SSRP via the Information Bottleneck principle and granularity ablations. Procedural Integrity audit (98.8% adherence) reveals a Grounding Paradox where high-stability models fail by refusing to hallucinate under retrieval-reasoning contamination.
### Title:
          Dialysis Risk Prediction and Treatment Effect Estimation for AKI patients using Longitudinal Electronic Health Records
 - **Authors:** Kalyani P. Pande, Evan Yang, Bryan Zhu, Sandeep K. Mallipattu, Alisa Yurovsky, Tengfei Ma
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Progression to dialysis or end-stage renal disease is a rare but clinically important outcome. Clinicians need evidence on how medication exposures influence downstream risk. We constructed a fixed-window EHR cohort (90-day observation, 730-day prediction; N=81401; dialysis/ESRD prevalence: 1.1%) and modeled sequences of diagnoses, procedures, and medications with kidney laboratory trends (creatinine, BUN, eGFR). A transformer-based causal multi-head model was trained to estimate drug- and ingredient-level average treatment effects (ATEs) using counterfactual exposure removal and insertion under a full medication history setup. On test set, predictive performance reached an AUC of 0.694 and PR-AUC of 0.094. At the selected decision threshold (0.883), the model achieved an F1 score of 0.201 with a Brier score of 0.018. Post-hoc causal analyses of lab changes (eGFR, creatinine, BUN) using IPTW, AIPW, naive, and covariate-adjusted OLS methods assessed clinical directionality. Results showed partial protective-direction support for ACE/ARB exposures and worsening-direction signals for loop diuretics.
### Title:
          Point-MF: One-step Point Cloud Generation from a Single Image via Mean Flows
 - **Authors:** Yuta Baba, Keiji Yanai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Single-image point cloud reconstruction must infer complete 3D geometry, including occluded parts, from a single RGB image. While diffusion-based reconstructors achieve high accuracy, they typically require many denoising iterations, resulting in slow and expensive inference. We propose Point-MF, a Mean-Flow-based framework for low-NFE single-image point cloud reconstruction that couples a Mean-Flow-compatible architecture with an auxiliary loss. Specifically, Point-MF operates directly in point-cloud space to learn the mean velocity field and enables one-step reconstruction with a single network function evaluation (1-NFE), without relying on VAE-based latent representations. To make Mean Flow effective under large interval jumps, Point-MF employs a Diffusion Transformer tailored to the Mean-Flow setting, conditioned on frozen DINOv3 image features via a lightweight token adapter and equipped with explicit interval/time conditioning. Moreover, we introduce Denoised Space Anchor, a set-distance auxiliary loss on the denoised-space estimate $x_\theta$ induced by the predicted velocity field, to stabilize large-step generation and reduce outliers and density artifacts. On ShapeNet-R2N2 and Pix3D, Point-MF strikes a strong balance between reconstruction quality and inference speed compared to multi-step diffusion baselines and competitive feedforward models, while generating high-quality point clouds with millisecond-level latency.
### Title:
          Fraud Detection in Cryptocurrency Markets with Spatio-Temporal Graph Neural Networks
 - **Authors:** Lidia Losavio, Luca Persia, Madan Sathe, Dimosthenis Pasadakis
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Technological advancements in cryptocurrency markets have increased accessibility for investors, but concurrently exposed them to the risks of market manipulations. Existing fraud detection mechanisms typically rely on machine learning methods that treat each financial asset (i.e., token) and its related transactions independently. However, market manipulation strategies are rarely isolated events, but are rather characterized by coordination, repetition, and frequent transfers among related assets. This suggests that relational structure constitutes an integral component of the signal and can be effectively represented through graphical means. In this paper, we propose three graph construction methods that rely on aggregated hourly market data. The proposed graphs are processed by a unified spatio-temporal Graph Neural Network (GNN) architecture that combines attention-based spatial aggregation with temporal Transformer encoding. We evaluate our methodology on a real-world dataset comprised of pump-and-dump schemes in cryptocurrency markets, spanning a period of over three years. Our comparative results showcase that our graph-based models achieve significant improvements over standard machine learning baselines in detecting anomalous events. Our work highlights that learned market connectivity provides substantial gains for detecting coordinated market manipulation schemes.
### Title:
          DETOUR: A Practical Backdoor Attack against Object Detection
 - **Authors:** Dazhuang Liu, Yanqi Qiao, Rui Wang, Kaitai Liang, Georgios Smaragdakis
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Object detection (OD) is critical to real-world vision systems, yet existing backdoor attacks on detection transformers (DETRs) for OD tasks rely on patch-wise triggers optimized at fixed locations with minimal perturbations. Such attacks overlook that backdoor triggers in the real world may appear at different sizes, fields of view (FoVs), and locations in images, while minimal perturbations are difficult for cameras to capture, limiting attack practicality. We first observe that a patch-wise trigger in DETR delivers high attack effectiveness when activating the backdoor across neighboring locations, a phenomenon we term the trigger radiating effect (TRE). Meanwhile, inserting patch-wise triggers across multiple locations synergistically enhances TRE, resulting in high attack effectiveness across images. We propose DETOUR, a practical backdoor attack by using semantic triggers that are effective in real-world object detection systems. To ensure attack practicality, we rescale trigger patterns to different sizes and insert them at various predefined locations during backdoor training, enabling the model to recognize the trigger regardless of its spatial configurations. To address FoV variations in physical deployments, we extract the trigger pattern from a real-world object (e.g., a mug) captured under multiple FoVs and inject the trigger accordingly, promoting viewpoint-invariant backdoor activation and enhancing TRE across the entire image. As a result, the backdoor can be reliably activated under diverse FoVs and spatial configurations.
### Title:
          Workplace Demands and Emotional Expression Among Early Childhood Educators: A Computational Analysis of Professional Online Discourse
 - **Authors:** Hailong Jiang
 - **Subjects:** Subjects:
Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Early childhood educators work in settings characterized by heavy regulation, emotional labor, staffing instability, and low pay. Although these conditions are well documented in survey-based research, less is known about how they manifest in the day-to-day language educators use in peer spaces. This study examines 7,506 posts from r/ECEProfessionals, a large online community used by early childhood education practitioners. Using a structured, computer-assisted thematic coding workflow and transformer-based emotion classification, posts were organized into 15 themes and mapped onto an adapted Job Demands-Resources (JD-R) framework. Across the corpus, 56.7% of posts centered on demands when task-level and core job demands were combined, compared with 33.6% focused on resources and 9.6% on career conditions. Emotion estimates indicated a broadly neutral tone overall; however, fear emerged as the most prominent non-neutral emotion. Demand-related categories also exhibited higher levels of sadness and anger than resource-related categories. These findings suggest that professional online discourse in early childhood education reflects a work environment structured more around strain than support. The study offers a practical framework for examining how occupational conditions are discussed and emotionally experienced in large-scale professional texts.
### Title:
          Long-Context Aware Upcycling: A New Frontier for Hybrid LLM Scaling
 - **Authors:** Parsa Ashrafi Fashi, Utkarsh Saxena, Mehdi Rezagholizadeh, Aref Jafari, Akash Haridas, Mingyu Yang, Vansh Bhatia, Guihong Li, Vikram Appia, Emad Barsoum
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hybrid sequence models that combine efficient Transformer components with linear sequence modeling blocks are a promising alternative to pure Transformers, but most are still pretrained from scratch and therefore fail to reuse existing Transformer checkpoints. We study upcycling as a practical path to convert pretrained Transformer LLMs into hybrid architectures while preserving short-context quality and improving long-context capability. We call our solution \emph{HyLo} (HYbrid LOng-context): a long-context upcycling recipe that combines architectural adaptation with efficient Transformer blocks, Multi-Head Latent Attention (MLA), and linear blocks (Mamba2 or Gated DeltaNet), together with staged long-context training and teacher-guided distillation for stable optimization. HyLo extends usable context length by up to $32\times$ through efficient post-training and reduces KV-cache memory by more than $90\%$, enabling up to 2M-token prefill and decoding in our \texttt{vLLM} inference stack, while comparable Llama baselines run out of memory beyond 64K context. Across 1B- and 3B-scale settings (Llama- and Qwen-based variants), HyLo delivers consistently strong short- and long-context performance and significantly outperforms state-of-the-art upcycled hybrid baselines on long-context evaluations such as RULER. Notably, at similar scale, HyLo-Qwen-1.7B trained on only 10B tokens significantly outperforms JetNemotron (trained on 400B tokens) on GSM8K, Lm-Harness common sense reasoning and RULER-64K.
### Title:
          Learning to Rotate: Temporal and Semantic Rotary Encoding for Sequential Modeling
 - **Authors:** Hailing Cheng, Daqi Sun, Xinyu Lu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Every Transformer architecture dedicates enormous capacity to learning rich representations in semantic embedding space -- yet the rotation manifold acted upon by Rotary Positional Embeddings (RoPE) has been treated as a fixed, hand-crafted structure, populated only by discrete ordinal indices. We argue that this rotation space is a largely overlooked second dimension of expressivity in the attention mechanism, one whose systematic exploration may open a new door for attention-based architectures. The analogy to complex numbers is instructive: just as introducing the imaginary axis -- orthogonal to and independent of the real line -- unlocked new algebraic structure once believed impossible, treating the rotation manifold as a learnable, signal-conditioned space opens an orthogonal degree of freedom in attention. In this framing, the token embedding encodes the semantic (real) component of a representation -- what a token means -- while the rotation encodes its dynamic (imaginary) component -- how it relates to every other token across time, position, and context. We introduce SIREN-RoPE, a concrete instantiation of this idea, which populates the rotation dimension with heterogeneous signals -- continuous timestamps, cyclical temporal patterns, and categorical metadata -- via a dual-branch Sinusoidal Representation Network (SIREN). As a proof of concept, we evaluate on a production-scale news feed dataset from a major social network using a generative recommender as the ranking model, demonstrating that activating this hidden dimension yields consistent improvements across calibration and ranking objectives with negligible computational overhead. We invite the community to view the rotation space not as a solved positional-encoding detail, but as an untapped axis whose rich structure may prove as consequential for attention as the imaginary unit proved for algebra.
### Title:
          OmniShotCut: Holistic Relational Shot Boundary Detection with Shot-Query Transformer
 - **Authors:** Boyang Wang, Guangyi Xu, Zhipeng Tang, Jiahui Zhang, Zezhou Cheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Shot Boundary Detection (SBD) aims to automatically identify shot changes and divide a video into coherent shots. While SBD was widely studied in the literature, existing state-of-the-art methods often produce non-interpretable boundaries on transitions, miss subtle yet harmful discontinuities, and rely on noisy, low-diversity annotations and outdated benchmarks. To alleviate these limitations, we propose OmniShotCut to formulate SBD as structured relational prediction, jointly estimating shot ranges with intra-shot relations and inter-shot relations, by a shot query-based dense video Transformer. To avoid imprecise manual labeling, we adopt a fully synthetic transition synthesis pipeline that automatically reproduces major transition families with precise boundaries and parameterized variants. We also introduce OmniShotCutBench, a modern wide-domain benchmark enabling holistic and diagnostic evaluation.
## Keyword: autonomous driving
### Title:
          WeatherSeg: Weather-Robust Image Segmentation using Teacher-Student Dual Learning and Classifier-Updating Attention
 - **Authors:** Zhang Zhang, Yifeng Zeng, Jinquan Pan, Yinghui Pan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 WeatherSeg, an advanced semi-supervised segmentation framework, addresses autonomous driving's environmental perception challenges in adverse weather while reducing annotation costs. This framework integrates a Dual Teacher-Student Weight-Sharing Model (DTSWSM) that enables knowledge distillation from weather-affected images, and a Classifier Weight Updating Attention Mechanism (CWUAM) that dynamically adjusts classifier weights based on environmental attributes. Comprehensive evaluations demonstrate that WeatherSeg significantly outperforms baseline models in both accuracy and robustness across various weather conditions, including clear, rainy, cloudy, and foggy scenarios, establishing it as an effective solution for all-weather semantic segmentation in autonomous driving and related applications.
### Title:
          EgoDyn-Bench: Evaluating Ego-Motion Understanding in Vision-Centric Foundation Models for Autonomous Driving
 - **Authors:** Finn Rasmus Schäfer, Yuan Gao, Dingrui Wang, Thomas Stauner, Stephan Günnemann, Mattia Piccinini, Sebastian Schmidt, Johannes Betz
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Vision-Language Models (VLMs) have advanced highlevel reasoning in autonomous driving, their ability to ground this reasoning in the underlying physics of ego-motion remains poorly understood. We introduce EgoDyn-Bench, a diagnostic benchmark for evaluating the semantic ego-motion understanding of vision-centric foundation models. By mapping continuous vehicle kinematics to discrete motion concepts via a deterministic oracle, we decouple a model's internal physical logic from its visual perception. Our large-scale empirical audit spanning 20 + models, including closed-source MLLMs, open-source VLMs across multiple scales, and specialized VLAs, identifies a significant Perception Bottleneck: while models exhibit logical physical concepts, they consistently fail to accurately align them with visual observations, frequently underperforming classical non-learned geometric baselines. This failure persists across model scales and domain-specific training, indicating a structural deficit in how current architectures couple visual perception with physical reasoning. We demonstrate that providing explicit trajectory encodings substantially restores physical consistency across all evaluated models, revealing a functional disentanglement between vision and language: egomotion logic is derived almost exclusively from the language modality, while visual observations contribute negligible additional signal. This structural finding provides a standardized diagnostic framework and a practical pathway toward physically aligned embodied AI. Keywords: Ego-motion - Physical Reasoning - Foundation Models
### Title:
          SwarmDrive: Semantic V2V Coordination for Latency-Constrained Cooperative Autonomous Driving
 - **Authors:** Anjie Qiu, Donglin Wang, Zexin Fang, Sanket Partani, Hans D. Schotten
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cloud-hosted LLM inference for autonomous driving adds round-trip delay and depends on stable connectivity, while purely local edge models struggle under occlusion. We present SwarmDrive, a semantic Vehicle-to-Vehicle (V2V) coordination framework in which nearby vehicles run local Small Language Models (SLMs), share compact intent distributions only when uncertainty is high, and fuse them through event-triggered consensus. We evaluate SwarmDrive in a 5-seed executable study built around one occluded intersection case, combining matched operating-point comparisons with robustness sweeps. In that setting, SwarmDrive under its 6G communication setting ("Swarm 6G") raises success from 68.9% to 94.1% over a single local SLM while reducing latency from a 510 ms cloud reference to 151.4 ms. However, an increased number of participating vehicles leads to higher communication overhead and packet loss. SwarmDrive also evaluates the impact of swarm-size, packet-loss, and entropy-threshold sweeps and shows that the cooperative gain holds across ablations and is best balanced near an active swarm size of 4 vehicles and an entropy trigger threshold of 0.65 in the current prototype. These results show that semantic edge cooperation can work under tight latency constraints in the targeted intersection case, but they are not a deployment-grade validation of a real 6G stack.
### Title:
          Attention-Augmented YOLOv8 with Ghost Convolution for Real-Time Vehicle Detection in Intelligent Transportation Systems
 - **Authors:** Syed Sajid Ullah, Muhammad Zunair Zamir, Ahsan Ishfaq, Salman Khan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate vehicle detection is a critical component of autonomous driving, traffic surveillance, and intelligent transportation systems. This paper presents an enhanced YOLOv8n-based model that integrates the Ghost Module, Convolutional Block Attention Module (CBAM), and Deformable Convolutional Networks v2 (DCNv2) to improve detection performance. The Ghost Module reduces feature redundancy through efficient feature generation, CBAM refines feature representation via channel and spatial attention, and DCNv2 enhances adaptability to geometric variations in vehicle structures. Evaluated on the KITTI dataset, the proposed model achieves 95.4% mAP@0.5, representing an 8.97% improvement over the baseline YOLOv8n, along with 96.2% precision, 93.7% recall, and a 94.93% F1-score. Comparative analysis against seven state-of-the-art detectors demonstrates consistent superiority across key performance metrics, while ablation studies validate the individual and combined contributions of the integrated modules. By addressing feature redundancy, attention refinement, and spatial adaptability, the proposed approach offers a robust and computationally efficient solution for vehicle detection in diverse and complex traffic environments.
### Title:
          Vision-Based Lane Following and Traffic Sign Recognition for Resource-Constrained Autonomous Vehicles
 - **Authors:** Md Tanjemul Islam, Md Rafiul Kabir
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles (AVs) rely on real-time perception systems to understand road environments and ensure safe navigation. However, implementing reliable perception algorithms on resource-constrained embedded platforms remains challenging due to limited computational resources. This paper presents a lightweight vision-based framework that integrates lane detection, lane tracking, and traffic sign recognition for embedded autonomous vehicles. A computationally efficient threshold-based lane segmentation method combined with perspective transformation and histogram-based curvature estimation is used for robust lane tracking under varying illumination conditions. A rule-based steering controller generates steering commands to maintain stable vehicle navigation. For traffic sign recognition, two lightweight convolutional neural networks (CNNs), EfficientNet-B0 and MobileNetV2, are evaluated using a custom dataset captured from the vehicle's onboard camera. Experimental results show that the system achieves real-time performance while maintaining accurate lane tracking with only 3.16% maximum offset RMSE. EfficientNet-B0 achieves a high offline classification accuracy of 98.77% on the test dataset, while achieving 90% accuracy during real-time on-device deployment, outperforming MobileNetV2 in both settings. MobileNetV2, however, offers slightly faster inference and lower computational cost. These results highlight the effectiveness of lightweight vision-based perception pipelines for resource-constrained autonomous driving applications.
### Title:
          Transferable Physical-World Adversarial Patches Against Object Detection in Autonomous Driving
 - **Authors:** Zihui Zhu, Ziqi Zhou, Yichen Wang, Lulu Xue, Minghui Li, Shengshan Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning drives major advances in autonomous driving (AD), where object detectors are central to perception. However, adversarial attacks pose significant threats to the reliability and safety of these systems, with physical adversarial patches representing a particularly potent form of attack. Physical adversarial patch attacks pose severe risks but are usually crafted for a single model, yielding poor transferability to unseen detectors. We propose AdvAD, a transfer-based physical attack against object detection in autonomous driving. Instead of targeting a specific detector, AdvAD optimizes adversarial patches over multiple detection models in a unified framework, encouraging the learned perturbations to capture shared vulnerabilities across architectures. The optimization process adaptively balances model contributions and enforces robustness to physical variations. It further employs data augmentation and geometric transformations to maintain patch effectiveness under diverse physical conditions. Experiments in both digital and real-world settings show that AdvAD consistently outperforms state-of-the-art (SOTA) attacks in performance and transferability.
### Title:
          Empirical Insights of Test Selection Metrics under Multiple Testing Objectives and Distribution Shifts
 - **Authors:** Jingyu Zhang, Fan Wang, Jacky Keung, Yihan Liao, Yan Xiao, Lei Ma
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning (DL)-based systems can exhibit unexpected behavior when exposed to out-of-distribution (OOD) scenarios, posing serious risks in safety-critical domains such as malware detection and autonomous driving. This underscores the importance of thoroughly testing such systems before deployment. To this end, researchers have proposed a wide range of test selection metrics designed to effectively select inputs. However, prior evaluations of metrics reveal three key limitations: (1) narrow testing objectives, for example, many studies assess metrics only for fault detection, leaving their effectiveness for performance estimation unclear; (2) limited coverage of OOD scenarios, with natural and label shifts are rarely considered; (3) Biased dataset selection, where most work focuses on image data while other modalities remain underexplored. Consequently, a unified benchmark that examines how these metrics perform under multiple testing objectives, diverse OOD scenarios, and different data modalities is still lacking. This leaves practitioners uncertain about which test selection metrics are most suitable for their specific objectives and contexts. To address this gap, we conduct an extensive empirical study of 15 existing metrics, evaluating them under three testing objectives (fault detection, performance estimation, and retraining guidance), five types of OOD scenarios (corrupted, adversarial, temporal, natural, and label shifts), three data modalities (image, text, and Android packages), and 13 DL models. In total, our study encompasses 1,640 experimental scenarios, offering a comprehensive evaluation and statistical analysis.
### Title:
          UniAda: Universal Adaptive Multi-objective Adversarial Attack for End-to-End Autonomous Driving Systems
 - **Authors:** Jingyu Zhang, Jacky Wai Keung, Yan Xiao, Yihan Liao, Yishu Li, Xiaoxue Ma
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Adversarial attacks play a pivotal role in testing and improving the reliability of deep learning (DL) systems. Existing literature has demonstrated that subtle perturbations to the input can elicit erroneous outcomes, thereby substantially compromising the security of DL systems. This has emerged as a critical concern in the development of DL-based safety-critical systems like Autonomous Driving Systems (ADSs). The focus of existing adversarial attack methods on End-to-End (E2E) ADSs has predominantly centered on misbehaviors of steering angle, which overlooks speed-related controls or imperceptible perturbations. To address these challenges, we introduce UniAda, a multi-objective white-box attack technique with a core function that revolves around crafting an image-agnostic adversarial perturbation capable of simultaneously influencing both steering and speed controls. UniAda capitalizes on an intricately designed multi-objective optimization function with the Adaptive Weighting Scheme (AWS), enabling the concurrent optimization of diverse objectives. Validated with both simulated and real-world driving data, UniAda outperforms five benchmarks across two metrics, inducing steering and speed deviations from 3.54 degrees to 29 degrees and 11 km per hour to 22 km per hour on average. This systematic approach establishes UniAda as a proven technique for adversarial attacks on modern DL-based E2E ADSs.
### Title:
          Large Language Model based Interactive Decision-Making for Autonomous Driving
 - **Authors:** Xinwei Dong, Jiyang Li, Jiabin Xie, Yang Yi, Tianshang Jia, Shiyu Fang, Ye Tian, Peng Hang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In high-conflict mixed-traffic scenarios involving human-driven and autonomous vehicles, most existing autonomous driving systems default to overly conservative behaviors, lack proactive interaction, and consequently suffer from limited public acceptance. To mitigate intent misunderstandings and decision failures, we present a Large Language Model based interactive decision-making framework that augments scene understanding and intent-aware interaction to jointly improve safety and efficiency. The approach uses Object-Process Methodology to semantically model complex multi-vehicle scenes, abstracting low-level perceptual data into objects, processes, and relations, thereby streamlining reasoning over latent causal structure. Building on this representation, the Large Language Model parses both explicit and implicit intents of surrounding agents and, under jointly enforced safety and efficiency constraints, selects candidate maneuvers. We further generate perturbed trajectory candidates via Monte Carlo sampling and evaluate them to obtain an optimized executable trajectory. To foster transparency and coordination with nearby road users, the final decision is translated by the Large Language Model into concise natural-language messages and broadcast through an external Human-Machine Interface, completing a closed loop from scene understanding to action to language. Experiments in a cluster driving simulator demonstrate that the proposed method outperforms traditional baselines across safety, comfort, and efficiency metrics, while a Turing-test-style evaluation indicates a high degree of human-likeness in decision making. Besides, these results suggest that coupling semantic scene abstraction with Large Language Model mediated intent reasoning and language-based eHMI communication offers a practical pathway toward interactive, trustworthy autonomous driving in dense mixed traffic.
### Title:
          Grammar-Constrained Refinement of Safety Operational Rules Using Language in the Loop: What Could Go Wrong
 - **Authors:** Khouloud Gaaloul, Zaid Ghazal, Madhu Latha Pulimi, Sam Emmanuel Kathiravan
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safety specifications in cyber-physical systems (CPS) capture the operational conditions the system must satisfy to operate safely within its intended environment. As operating environments evolve, operational rules must be continuously refined to preserve consistency with observed system behavior during simulation-based verification and validation. Revising inconsistent rules is challenging because the changes must remain syntactically correct under a domain-specific grammar. Language-in-the-loop refinement further raises safety concerns beyond syntactic violations, as it can produce semantically unjustified refinements that overfit to the observed outcomes. We introduce a framework that combines counterfactual reasoning with a grammar-constrained refinement loop to refine operational rules, aligning them with the observed system behavior. Applied to an autonomous driving control system, our approach successfully resolved the inconsistencies in an operational rule inferred by a conventional baseline while remaining grammar compliant. An empirical large language model (LLM) study further revealed model-dependent refinement quality and safety lessons, which motivate rigorous grammar enforcement, stronger semantic validation, and broader evaluation in future work.
### Title:
          Learning to Identify Out-of-Distribution Objects for 3D LiDAR Anomaly Segmentation
 - **Authors:** Simone Mosco, Daniel Fusaro, Alberto Pretto
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding the surrounding environment is fundamental in autonomous driving and robotic perception. Distinguishing between known classes and previously unseen objects is crucial in real-world environments, as done in Anomaly Segmentation. However, research in the 3D field remains limited, with most existing approaches applying post-processing techniques from 2D vision. To cover this lack, we propose a new efficient approach that directly operates in the feature space, modeling the feature distribution of inlier classes to constrain anomalous samples. Moreover, the only publicly available 3D LiDAR anomaly segmentation dataset contains simple scenarios, with few anomaly instances, and exhibits a severe domain gap due to its sensor resolution. To bridge this gap, we introduce a set of mixed real-synthetic datasets for 3D LiDAR anomaly segmentation, built upon established semantic segmentation benchmarks, with multiple out-of-distribution objects and diverse, complex environments. Extensive experiments demonstrate that our approach achieves state-of-the-art and competitive results on the existing real-world dataset and the newly introduced mixed datasets, respectively, validating the effectiveness of our method and the utility of the proposed datasets. Code and datasets are available at this https URL.
### Title:
          ESIA: An Energy-Based Spatiotemporal Interaction-Aware Framework for Pedestrian Intention Prediction
 - **Authors:** Yanping Wu, Meiting Dang, Lin Wu, Edmond S. L. Ho, Zhenghua Chen, Chongfeng Wei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in autonomous driving have motivated research on pedestrian intention prediction, which aims to infer future crossing decisions and actions by modeling temporal dynamics, social interactions, and environmental context. However, existing studies remain constrained by oversimplified multi-agent interaction patterns, opaque reasoning logic, and a lack of global consistency in behavioral predictions, which compromise both robustness and interpretability. In this work, we propose ESIA (Energy-based Spatiotemporal Interaction-Aware framework), a novel Conditional Random Field (CRF)-based paradigm. We cast the intention prediction task as a structured prediction problem over a unified graph-based representation, treating pedestrians and the environment as spatiotemporal nodes. To characterize their distinct roles, we assign unary potentials to nodes to capture individual intentions, and pairwise potentials to edges to encode social and environmental interactions. These potentials are integrated into a unified global energy function to ensure scene-level consistency across behavioral predictions. To further constrain inference without ground-truth supervision, we introduce structural consistency terms to penalize logical contradictions. This optimization is efficiently solved via a novel Unary-Seeded Simulated Annealing (U-SSA) algorithm, which leverages high-confidence unary priors to rapidly converge to a high-quality solution. Extensive experiments on standard benchmarks demonstrate that ESIA achieves state-of-the-art performance with improved interpretability over existing methods.
### Title:
          VLM-VPI: A Vision-Language Reasoning Framework for Improving Automated Vehicle-Pedestrian Interactions
 - **Authors:** Qingwen Pu, Kun Xie, Yuxiang Liu
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous driving systems often infer pedestrian yielding behavior from geometric and kinematic cues alone, limiting their ability to reason about visual scene context and age-dependent behavioral variability. This limitation can produce delayed interventions in safety-critical encounters and unnecessary braking in benign interactions. This work introduces Vision-Language Model-based Vehicle-Pedestrian Interaction (VLM-VPI), a multimodal reasoning framework for pedestrian intent understanding and yielding-aware control in autonomous driving. The system combines three components: a multimodal perception layer that captures visual and kinematic observations, a reasoning layer that uses Qwen3-VL 8B for visual scene understanding and GPT-OSS 20B for few-shot intent reasoning, and a tiered safety controller that applies age-specific braking margins for children, adults, and seniors. In 112 CARLA scenarios, VLM-VPI achieves 92.3% intent classification accuracy, outperforming a rule-based baseline (78.4%), supervised trajectory models (73.5-82.4%), and a zero-shot LLM configuration (88.4%). Validation on 24 real-world PIE scenarios yields 87.5% accuracy, indicating functional sim-to-real transferability. Across 200 simulation cases, VLM-VPI reduces the false-alarm rate from 7.4% to 2.8% and mean intersection traversal time from 13.5 s to 11.8 s. Conflict occurrences decrease from 124 to 33, while mean minimum time-to-collision improves from 1.92 s to 4.47 s. Demographic-adaptive control further reduces conflicts by 60% for children and 54.5% for seniors compared with uniform control. These results show that an explicit vision-language reasoning layer can improve both safety and efficiency by linking pedestrian intent, demographic context, and vehicle control decisions.
### Title:
          CLLAP: Contrastive Learning-based LiDAR-Augmented Pretraining for Enhanced Radar-Camera Fusion
 - **Authors:** Bingyi Liu, Chuanhui Zhu, Hongfei Xue, Jian Teng, Jipeng Liu, Enshu Wang, Penglin Dai, Pu Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D object detection is critical for autonomous driving, necessitating reliable, cost-effective sensors capable of operating in adverse weather conditions. Camera and millimeter-wave radar fusion has emerged as a promising solution; however, these methods often rely on finely annotated radar data, which is scarce and labor-intensive to produce. To address this challenge, we present CLLAP, a Contrastive Learning-based LiDAR-Augmented Pretraining framework that enhances the performance of existing radar-camera fusion methods for 3D object detection. CLLAP leverages abundant LiDAR data to generate pseudo-radar data using the proposed L2R (LiDAR-to-Radar) Sampling method. Then, it incorporates this data into a novel dual-stage, dual-modality contrastive learning strategy, enabling effective self-supervised learning from paired pseudo-radar and image data. This approach facilitates effective pretraining of existing radar-camera fusion models in a plug-and-play manner, enhancing their feature extraction capabilities and improving detection accuracy and robustness. Experimental results using NuScenes and Lyft Level 5 datasets demonstrate significant performance improvements across three baseline models, highlighting CLLAP's effectiveness in advancing radar-camera fusion for autonomous driving applications.
### Title:
          TopoHR: Hierarchical Centerline Representation for Cyclic Topology Reasoning in Driving Scenes with Point-to-Instance Relations
 - **Authors:** Yifeng Bai, Zhirong Chen, Erkang Cheng, Haibin Ling
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Topology reasoning is crucial for autonomous driving. Current methods primarily focus on instance-level learning for centerline detection, followed by a sequential module for topology reasoning that relies on simplified MLP layers. Moreover, they often neglect the importance of \textit{point-to-instance} (P2I) relationships in topology reasoning. To address these limitations, we present TopoHR (Topological Hierarchical Representation), a novel end-to-end framework that establishes cyclic interaction between centerline detection and topology reasoning, allowing them to iteratively enhance each other. Specifically, we introduce a hierarchical centerline representation including point queries, instance queries, and semantic representations. These multi-level features are seamlessly integrated and fused within a hierarchical centerline decoder. Furthermore, we design a hierarchical topology reasoning module that captures both fine-grained P2I relationships and global instance-to-instance (I2I) connections within a unified architecture. With these novel components, TopoHR ensures accurate and robust topology reasoning. On the OpenLane-V2 benchmark, TopoHR refreshes state-of-the-art performance with significant improvements. Notably, compared with previous best results, TopoHR achieves +3.8 in $\mathrm{DET}_{\text{l}}$, +5.4 in $\mathrm{TOP}_{\text{ll}}$ on $\text{subset_A}$ and +11.0 in $\mathrm{DET}_{\text{l}}$, +7.9 in $\mathrm{TOP}_{\text{ll}}$ on $\text{subset_B}$, validating the effectiveness of the proposed components. The code will be shared publicly at this https URL.
### Title:
          Projected Attainable Speed Space: A Driving Efficiency Metric Connecting Instantaneous Evaluation to Travel Time
 - **Authors:** Xiaohua Zhao, Zhaowei Huang, Chen Chen, Haiyi Yang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inefficient driving behaviors, such as overly conservative yielding, remain a key obstacle to deployment of autonomous vehicles (AVs). Instantaneous driving efficiency metrics are crucial for self-driving decision-making because they affect real-time performance evaluation and control optimization. However, commonly used indicators, including speed, relative speed, and inter-vehicle distance, are limited in capturing traffic context and in ensuring consistency between instantaneous outputs and travel-level outcomes. This study proposes the Projected Attainable Speed Space (PASS) model, a unified framework for driving efficiency assessment across instantaneous and travel-level analyses by integrating kinematic and spatial traffic information. PASS characterizes instantaneous driving efficiency with two coupled elements: potential for speed improvement (available acceleration space) and response to that potential (utilization of available acceleration space). Available acceleration space is referenced to projected attainable speed, derived from an idealized catch-up maneuver using relative speed and spacing to the leading vehicle; utilization is represented by the temporal change in available acceleration space. To ensure cross-scale consistency, time-aggregated PASS is defined as a travel-level efficiency metric. Trajectory data from a driving simulation experiment are used for parameter calibration to maximize agreement between time-aggregated PASS and observed travel times. Across 10 lane-change events, results show strong consistency, with an average coefficient of determination of 0.913, validating PASS for consistent efficiency evaluation across instantaneous and travel-level temporal scales. This study provides a unified, physically grounded framework that supports real-time decision-making and long-term performance analysis in autonomous driving.
### Title:
          ARETE: Attention-based Rasterized Encoding for Topology Estimation using HSV-transformed Crowdsourced Vehicle Fleet Data
 - **Authors:** Daniel Fritz, Dimitrios Lagamtzis, Michael Mink, Markus Enzweiler, Steffen Schober
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The continuous advancement of autonomous driving (AD) introduces challenges across multiple disciplines to ensure safe and efficient driving. One such challenge is the generation of High-Definition (HD) maps, which must remain up to date and highly accurate for downstream automotive tasks. One promising approach is the use of crowdsourced data from a vehicle fleet, representing road topology and lane-level features. This work focuses on the generation of centerlines and lane dividers from crowdsourced vehicle trajectories. We adopt a Detection Transformer (DETR)-based approach, where a rasterized representation of vehicle trajectories is used as input to predict vectorized lane representations. Each lane consists of a centerline with an associated direction and corresponding lane dividers that are geometrically constrained by the centerline. Our method includes the extraction of local tiles, from which crowdsourced vehicle trajectories are aggregated. Each tile undergoes a transformation into a rasterized representation encoding both the presence and direction of each trajectory, enabling the prediction of vectorized directed lanes. Experiments are conducted on an internal dataset as well as on the public datasets nuScenes and nuPlan.
