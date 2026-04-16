# Showing new listings for Thursday, 16 April 2026
## Keyword: SLAM
### Title:
          RadarSplat-RIO: Indoor Radar-Inertial Odometry with Gaussian Splatting-Based Radar Bundle Adjustment
 - **Authors:** Pou-Chun Kung, Yuan Tian, Zhengqin Li, Yue Liu, Eric Whitmire, Wolf Kienzle, Hrvoje Benko
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar is more resilient to adverse weather and lighting conditions than visual and Lidar simultaneous localization and mapping (SLAM). However, most radar SLAM pipelines still rely heavily on frame-to-frame odometry, which leads to substantial drift. While loop closure can correct long-term errors, it requires revisiting places and relies on robust place recognition. In contrast, visual odometry methods typically leverage bundle adjustment (BA) to jointly optimize poses and map within a local window. However, an equivalent BA formulation for radar has remained largely unexplored. We present the first radar BA framework enabled by Gaussian Splatting (GS), a dense and differentiable scene representation. Our method jointly optimizes radar sensor poses and scene geometry using full range-azimuth-Doppler data, bringing the benefits of multi-frame BA to radar for the first time. When integrated with an existing radar-inertial odometry frontend, our approach significantly reduces pose drift and improves robustness. Across multiple indoor scenes, our radar BA achieves substantial gains over the prior radar-inertial odometry, reducing average absolute translational and rotational errors by 90% and 80%, respectively.
### Title:
          UMI-3D: Extending Universal Manipulation Interface from Vision-Limited to 3D Spatial Perception
 - **Authors:** Ziming Wang
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present UMI-3D, a multimodal extension of the Universal Manipulation Interface (UMI) for robust and scalable data collection in embodied manipulation. While UMI enables portable, wrist-mounted data acquisition, its reliance on monocular visual SLAM makes it vulnerable to occlusions, dynamic scenes, and tracking failures, limiting its applicability in real-world environments. UMI-3D addresses these limitations by introducing a lightweight and low-cost LiDAR sensor tightly integrated into the wrist-mounted interface, enabling LiDAR-centric SLAM with accurate metric-scale pose estimation under challenging conditions. We further develop a hardware-synchronized multimodal sensing pipeline and a unified spatiotemporal calibration framework that aligns visual observations with LiDAR point clouds, producing consistent 3D representations of demonstrations. Despite maintaining the original 2D visuomotor policy formulation, UMI-3D significantly improves the quality and reliability of collected data, which directly translates into enhanced policy performance. Extensive real-world experiments demonstrate that UMI-3D not only achieves high success rates on standard manipulation tasks, but also enables learning of tasks that are challenging or infeasible for the original vision-only UMI setup, including large deformable object manipulation and articulated object operation. The system supports an end-to-end pipeline for data acquisition, alignment, training, and deployment, while preserving the portability and accessibility of the original UMI. All hardware and software components are open-sourced to facilitate large-scale data collection and accelerate research in embodied intelligence: \href{this https URL}{this https URL}.
### Title:
          Geometric Context Transformer for Streaming 3D Reconstruction
 - **Authors:** Lin-Zhuo Chen, Jian Gao, Yihang Chen, Ka Leong Cheng, Yipengjing Sun, Liangxiao Hu, Nan Xue, Xing Zhu, Yujun Shen, Yao Yao, Yinghao Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Streaming 3D reconstruction aims to recover 3D information, such as camera poses and point clouds, from a video stream, which necessitates geometric accuracy, temporal consistency, and computational efficiency. Motivated by the principles of Simultaneous Localization and Mapping (SLAM), we introduce LingBot-Map, a feed-forward 3D foundation model for reconstructing scenes from streaming data, built upon a geometric context transformer (GCT) architecture. A defining aspect of LingBot-Map lies in its carefully designed attention mechanism, which integrates an anchor context, a pose-reference window, and a trajectory memory to address coordinate grounding, dense geometric cues, and long-range drift correction, respectively. This design keeps the streaming state compact while retaining rich geometric context, enabling stable efficient inference at around 20 FPS on 518 x 378 resolution inputs over long sequences exceeding 10,000 frames. Extensive evaluations across a variety of benchmarks demonstrate that our approach achieves superior performance compared to both existing streaming and iterative optimization-based approaches.
## Keyword: odometry
### Title:
          RadarSplat-RIO: Indoor Radar-Inertial Odometry with Gaussian Splatting-Based Radar Bundle Adjustment
 - **Authors:** Pou-Chun Kung, Yuan Tian, Zhengqin Li, Yue Liu, Eric Whitmire, Wolf Kienzle, Hrvoje Benko
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar is more resilient to adverse weather and lighting conditions than visual and Lidar simultaneous localization and mapping (SLAM). However, most radar SLAM pipelines still rely heavily on frame-to-frame odometry, which leads to substantial drift. While loop closure can correct long-term errors, it requires revisiting places and relies on robust place recognition. In contrast, visual odometry methods typically leverage bundle adjustment (BA) to jointly optimize poses and map within a local window. However, an equivalent BA formulation for radar has remained largely unexplored. We present the first radar BA framework enabled by Gaussian Splatting (GS), a dense and differentiable scene representation. Our method jointly optimizes radar sensor poses and scene geometry using full range-azimuth-Doppler data, bringing the benefits of multi-frame BA to radar for the first time. When integrated with an existing radar-inertial odometry frontend, our approach significantly reduces pose drift and improves robustness. Across multiple indoor scenes, our radar BA achieves substantial gains over the prior radar-inertial odometry, reducing average absolute translational and rotational errors by 90% and 80%, respectively.
### Title:
          UNRIO: Uncertainty-Aware Velocity Learning for Radar-Inertial Odometry
 - **Authors:** Jui-Te Huang, Tinashu Huang, Anthony Rowe, Michael Kaess
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present UNRIO, an uncertainty-aware radar-inertial odometry system that estimates ego-velocity directly from raw mmWave radar IQ signals rather than processed point clouds. Existing radar-inertial odometry methods rely on handcrafted signal processing pipelines that discard latent information in the raw spectrum and require careful parameter tuning. To address this, we propose a transformer-based neural network built on the GRT architecture that processes the full 4-D spectral cube to predict body-frame velocity in two modes: a direct linear velocity estimate and a per-anglebin Doppler velocity map. The network is trained in three stages: geometric pretraining on LiDAR-projected depth, velocity or Doppler fine-tuning, and uncertainty calibration via negative log-likelihood loss, enabling it to produce uncertainty estimates alongside its predictions. These uncertainty estimates are propagated into a sliding-window pose graph that fuses radar velocity factors with IMU preintegration measurements. We train and evaluate UNRIO on the IQ1M dataset across diverse indoor environments with both forward and lateral motion patterns unseen during training. Our method achieves the lowest relative pose error on the majority of sequences, with particularly strong gains over classical DSP baselines on Lateral-motion trajectories where sparse point clouds degrade conventional velocity estimators.
### Title:
          Towards Multi-Object-Tracking with Radar on a Fast Moving Vehicle: On the Potential of Processing Radar in the Frequency Domain
 - **Authors:** Tim Hansen, Arturo Gomez-Chavez, Ilya Shimchik, Andreas Birk
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We promote in this paper the processing of radar data in the frequency domain to achieve higher robustness against noise and structural errors, especially in comparison to feature-based methods. This holds also for high dynamics in the scene, i.e., ego-motion of the vehicle with the sensor plus the presence of an unknown number of other moving objects. In addition to the high robustness, the processing in the frequency domain has the so far neglected advantage that the underlying correlation based methods used for, e.g., registration, provide information about all moving structures in the scene. A typical automotive application case is overtaking maneuvers, which in the context of autonomous racing are used here as a motivating example. Initial experiments and results with Fourier SOFT in 2D (FS2D) are presented that use the Boreas dataset to demonstrate radar-only-odometry, i.e., radar-odometry without sensor-fusion, to support our arguments.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          A Domain-Specific Language for LLM-Driven Trigger Generation in Multimodal Data Collection
 - **Authors:** Philipp Reis, Philipp Rigoll, Martin Zehetner, Jacqueline Henle, Stefan Otten, Eric Sax
 - **Subjects:** Subjects:
Databases (cs.DB); Computation and Language (cs.CL); Information Retrieval (cs.IR); Machine Learning (cs.LG); Programming Languages (cs.PL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data-driven systems depend on task-relevant data, yet data collection pipelines remain passive and indiscriminate. Continuous logging of multimodal sensor streams incurs high storage costs and captures irrelevant data. This paper proposes a declarative framework for intent-driven, on-device data collection that enables selective collection of multimodal sensor data based on high-level user requests. The framework combines natural language interaction with a formally specified domain-specific language (DSL). Large language models translate user-defined requirements into verifiable and composable DSL programs that define conditional triggers across heterogeneous sensors, including cameras, LiDAR, and system telemetry. Empirical evaluation on vehicular and robotic perception tasks shows that the DSL-based approach achieves higher generation consistency and lower execution latency than unconstrained code generation while maintaining comparable detection performance. The structured abstraction supports modular trigger composition and concurrent deployment on resource-constrained edge platforms. This approach replaces passive logging with a verifiable, intent-driven mechanism for multimodal data collection in real-time systems.
### Title:
          A High-Resolution Landscape Dataset for Concept-Based XAI With Application to Species Distribution Models
 - **Authors:** Augustin de la Brosse, Damien Garreau, Thomas Houet, Thomas Corpetti
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mapping the spatial distribution of species is essential for conservation policy and invasive species management. Species distribution models (SDMs) are the primary tools for this task, serving two purposes: achieving robust predictive performance while providing ecological insights into the driving factors of distribution. However, the increasing complexity of deep learning SDMs has made extracting these insights more challenging. To reconcile these objectives, we propose the first implementation of concept-based Explainable AI (XAI) for SDMs. We leverage the Robust TCAV (Testing with Concept Activation Vectors) methodology to quantify the influence of landscape concepts on model predictions. To enable this, we provide a new open-access landscape concept dataset derived from high-resolution multispectral and LiDAR drone imagery. It includes 653 patches across 15 distinct landscape concepts and 1,450 random reference patches, designed to suit a wide range of species. We demonstrate this approach through a case study of two aquatic insects, Plecoptera and Trichoptera, using two Convolutional Neural Networks and one Vision Transformer. Results show that concept-based XAI helps validate SDMs against expert knowledge while uncovering novel associations that generate new ecological hypotheses. Robust TCAV also provides landscape-level information, useful for policy-making and land management. Code and datasets are publicly available.
### Title:
          RobotPan: A 360$^\circ$ Surround-View Robotic Vision System for Embodied Perception
 - **Authors:** Jiahao Ma, Qiang Zhang, Peiran Liu, Zeran Su, Pihai Sun, Gang Han, Wen Zhao, Wei Cui, Zhang Zhang, Zhiyuan Xu, Renjing Xu, Jian Tang, Miaomiao Liu, Yijie Guo
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Surround-view perception is increasingly important for robotic navigation and loco-manipulation, especially in human-in-the-loop settings such as teleoperation, data collection, and emergency takeover. However, current robotic visual interfaces are often limited to narrow forward-facing views, or, when multiple on-board cameras are available, require cumbersome manual switching that interrupts the operator's workflow. Both configurations suffer from motion-induced jitter that causes simulator sickness in head-mounted displays. We introduce a surround-view robotic vision system that combines six cameras with LiDAR to provide full 360$^\circ$ visual coverage, while meeting the geometric and real-time constraints of embodied deployment. We further present \textsc{RobotPan}, a feed-forward framework that predicts \emph{metric-scaled} and \emph{compact} 3D Gaussians from calibrated sparse-view inputs for real-time rendering, reconstruction, and streaming. \textsc{RobotPan} lifts multi-view features into a unified spherical coordinate representation and decodes Gaussians using hierarchical spherical voxel priors, allocating fine resolution near the robot and coarser resolution at larger radii to reduce computational redundancy without sacrificing fidelity. To support long sequences, our online fusion updates dynamic content while preventing unbounded growth in static regions by selectively updating appearance. Finally, we release a multi-sensor dataset tailored to 360$^\circ$ novel view synthesis and metric 3D reconstruction for robotics, covering navigation, manipulation, and locomotion on real platforms. Experiments show that \textsc{RobotPan} achieves competitive quality against prior feed-forward reconstruction and view-synthesis methods while producing substantially fewer Gaussians, enabling practical real-time embodied deployment. Project website: this https URL
### Title:
          RadarSplat-RIO: Indoor Radar-Inertial Odometry with Gaussian Splatting-Based Radar Bundle Adjustment
 - **Authors:** Pou-Chun Kung, Yuan Tian, Zhengqin Li, Yue Liu, Eric Whitmire, Wolf Kienzle, Hrvoje Benko
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar is more resilient to adverse weather and lighting conditions than visual and Lidar simultaneous localization and mapping (SLAM). However, most radar SLAM pipelines still rely heavily on frame-to-frame odometry, which leads to substantial drift. While loop closure can correct long-term errors, it requires revisiting places and relies on robust place recognition. In contrast, visual odometry methods typically leverage bundle adjustment (BA) to jointly optimize poses and map within a local window. However, an equivalent BA formulation for radar has remained largely unexplored. We present the first radar BA framework enabled by Gaussian Splatting (GS), a dense and differentiable scene representation. Our method jointly optimizes radar sensor poses and scene geometry using full range-azimuth-Doppler data, bringing the benefits of multi-frame BA to radar for the first time. When integrated with an existing radar-inertial odometry frontend, our approach significantly reduces pose drift and improves robustness. Across multiple indoor scenes, our radar BA achieves substantial gains over the prior radar-inertial odometry, reducing average absolute translational and rotational errors by 90% and 80%, respectively.
### Title:
          Radar-Informed 3D Multi-Object Tracking under Adverse Conditions
 - **Authors:** Bingxue Xu, Emil Hedemalm, Ajinkya Khoche, Patric Jensfelt
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The challenge of 3D multi-object tracking (3D MOT) is achieving robustness in real-world applications, for example under adverse conditions and maintaining consistency as distance increases. To overcome these challenges, sensor fusion approaches that combine LiDAR, cameras, and radar have emerged. However, existing multi-modal fusion methods usually treat radar as another learned feature inside the network. When the overall model degrades in difficult environmental conditions, the robustness advantages that radar could provide are also reduced. We propose RadarMOT, a radar-informed 3D MOT framework that explicitly uses radar point cloud data as additional observation to refine state estimation and recover detector misses at long ranges. Evaluations on the MAN-TruckScenes dataset show that RadarMOT consistently improves the Average Multi-Object Tracking Accuracy (AMOTA) with absolute 12.7% at long range and 10.3% in adverse weather. The code will be available at this https URL
### Title:
          UNRIO: Uncertainty-Aware Velocity Learning for Radar-Inertial Odometry
 - **Authors:** Jui-Te Huang, Tinashu Huang, Anthony Rowe, Michael Kaess
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present UNRIO, an uncertainty-aware radar-inertial odometry system that estimates ego-velocity directly from raw mmWave radar IQ signals rather than processed point clouds. Existing radar-inertial odometry methods rely on handcrafted signal processing pipelines that discard latent information in the raw spectrum and require careful parameter tuning. To address this, we propose a transformer-based neural network built on the GRT architecture that processes the full 4-D spectral cube to predict body-frame velocity in two modes: a direct linear velocity estimate and a per-anglebin Doppler velocity map. The network is trained in three stages: geometric pretraining on LiDAR-projected depth, velocity or Doppler fine-tuning, and uncertainty calibration via negative log-likelihood loss, enabling it to produce uncertainty estimates alongside its predictions. These uncertainty estimates are propagated into a sliding-window pose graph that fuses radar velocity factors with IMU preintegration measurements. We train and evaluate UNRIO on the IQ1M dataset across diverse indoor environments with both forward and lateral motion patterns unseen during training. Our method achieves the lowest relative pose error on the majority of sequences, with particularly strong gains over classical DSP baselines on Lateral-motion trajectories where sparse point clouds degrade conventional velocity estimators.
### Title:
          Temporally Consistent Long-Term Memory for 3D Single Object Tracking
 - **Authors:** Jaejoon Yoo, SuBeen Lee, Yerim Jeon, Miso Lee, Jae-Pil Heo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Single Object Tracking (3D-SOT) aims to localize a target object across a sequence of LiDAR point clouds, given its 3D bounding box in the first frame. Recent methods have adopted a memory-based approach to utilize previously observed features of the target object, but remain limited to only a few recent frames. This work reveals that their temporal capacity is fundamentally constrained to short-term context due to severe temporal feature inconsistency and excessive memory overhead. To this end, we propose a robust long-term 3D-SOT framework, ChronoTrack, which preserves the temporal feature consistency while efficiently aggregating the diverse target features via long-term memory. Based on a compact set of learnable memory tokens, ChronoTrack leverages long-term information through two complementary objectives: a temporal consistency loss and a memory cycle consistency loss. The former enforces feature alignment across frames, alleviating temporal drift and improving the reliability of proposed long-term memory. In parallel, the latter encourages each token to encode diverse and discriminative target representations observed throughout the sequence via memory-point-memory cyclic walks. As a result, ChronoTrack achieves new state-of-the-art performance on multiple 3D-SOT benchmarks, demonstrating its effectiveness in long-term target modeling with compact memory while running at real-time speed of 42 FPS on a single RTX 4090 GPU. The code is available at this https URL
### Title:
          UMI-3D: Extending Universal Manipulation Interface from Vision-Limited to 3D Spatial Perception
 - **Authors:** Ziming Wang
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present UMI-3D, a multimodal extension of the Universal Manipulation Interface (UMI) for robust and scalable data collection in embodied manipulation. While UMI enables portable, wrist-mounted data acquisition, its reliance on monocular visual SLAM makes it vulnerable to occlusions, dynamic scenes, and tracking failures, limiting its applicability in real-world environments. UMI-3D addresses these limitations by introducing a lightweight and low-cost LiDAR sensor tightly integrated into the wrist-mounted interface, enabling LiDAR-centric SLAM with accurate metric-scale pose estimation under challenging conditions. We further develop a hardware-synchronized multimodal sensing pipeline and a unified spatiotemporal calibration framework that aligns visual observations with LiDAR point clouds, producing consistent 3D representations of demonstrations. Despite maintaining the original 2D visuomotor policy formulation, UMI-3D significantly improves the quality and reliability of collected data, which directly translates into enhanced policy performance. Extensive real-world experiments demonstrate that UMI-3D not only achieves high success rates on standard manipulation tasks, but also enables learning of tasks that are challenging or infeasible for the original vision-only UMI setup, including large deformable object manipulation and articulated object operation. The system supports an end-to-end pipeline for data acquisition, alignment, training, and deployment, while preserving the portability and accessibility of the original UMI. All hardware and software components are open-sourced to facilitate large-scale data collection and accelerate research in embodied intelligence: \href{this https URL}{this https URL}.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          PatchPoison: Poisoning Multi-View Datasets to Degrade 3D Reconstruction
 - **Authors:** Prajas Wadekar, Venkata Sai Pranav Bachina, Kunal Bhosikar, Ankit Gangwal, Charu Sharma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D Gaussian Splatting (3DGS) has recently enabled highly photorealistic 3D reconstruction from casually captured multi-view images. However, this accessibility raises a privacy concern: publicly available images or videos can be exploited to reconstruct detailed 3D models of scenes or objects without the owner's consent. We present PatchPoison, a lightweight dataset-poisoning method that prevents unauthorized 3D reconstruction. Unlike global perturbations, PatchPoison injects a small high-frequency adversarial patch, a structured checkerboard, into the periphery of each image in a multi-view dataset. The patch is designed to corrupt the feature-matching stage of Structure-from-Motion (SfM) pipelines such as COLMAP by introducing spurious correspondences that systematically misalign estimated camera poses. Consequently, downstream 3DGS optimization diverges from the correct scene geometry. On the NeRF-Synthetic benchmark, inserting a 12 X 12 pixel patch increases reconstruction error by 6.8x in LPIPS, while the poisoned images remain unobtrusive to human viewers. PatchPoison requires no pipeline modifications, offering a practical, "drop-in" preprocessing step for content creators to protect their multi-view data.
### Title:
          PartNerFace: Part-based Neural Radiance Fields for Animatable Facial Avatar Reconstruction
 - **Authors:** Xianggang Yu, Lingteng Qiu, Xiaohang Ren, Guanying Chen, Shuguang Cui, Xiaoguang Han, Baoyuan Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present PartNerFace, a part-based neural radiance fields approach, for reconstructing animatable facial avatar from monocular RGB videos. Existing solutions either simply condition the implicit network with the morphable model parameters or learn an imaginary canonical radiance field, making them fail to generalize to unseen facial expressions and capture fine-scale motion details. To address these challenges, we first apply inverse skinning based on a parametric head model to map an observed point to the canonical space, and then model fine-scale motions with a part-based deformation field. Our key insight is that the deformation of different facial parts should be modeled differently. Specifically, our part-based deformation field consists of multiple local MLPs to adaptively partition the canonical space into different parts, where the deformation of a 3D point is computed by aggregating the prediction of all local MLPs by a soft-weighting mechanism. Extensive experiments demonstrate that our method generalizes well to unseen expressions and is capable of modeling fine-scale facial motions, outperforming state-of-the-art methods both quantitatively and qualitatively.
## Keyword: mapping
### Title:
          KMMMU: Evaluation of Massive Multi-discipline Multimodal Understanding in Korean Language and Context
 - **Authors:** Nahyun Lee, Guijin Son, Hyunwoo Ko, Chanyoung Kim, JunYoung An, Kyubeen Han, Il-Youp Kwak
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce KMMMU, a native Korean benchmark for evaluating multimodal understanding in Korean cultural and institutional settings. KMMMU contains 3,466 questions from exams natively written in Korean, covering nine disciplines and nine visual modality categories, along with a 300-item Korean-specific subset and a hard subset of 627 questions. Unlike translated or English-centric benchmarks, KMMMU targets information-dense problems shaped by local conventions, official standards, and discipline-specific visual formats. Experiments show that the strongest open-source model reaches only 42.05% accuracy on the full set, while the best proprietary model achieves 52.42% on the hard subset. Performance varies across disciplines, with some disciplines emerging as bottlenecks, and Korean-specific questions showing gaps of up to 13.43%. Error analysis suggests that these failures stem less from insufficient reasoning depth than from weak convention-to-label mapping, few-shot symbolic induction, localized knowledge recall, and domain-specific standards understanding. KMMMU provides a testbed for multimodal evaluation beyond English-centric benchmarks and for developing more reliable systems for expert real-world tasks.
### Title:
          Fast Voxelization and Level of Detail for Microgeometry Rendering
 - **Authors:** Javier Fabre, Carlos Castillo, Carlos Rodriguez-Pardo, Jorge Lopez-Moreno
 - **Subjects:** Subjects:
Graphics (cs.GR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Many materials show anisotropic light scattering patterns due to the shape and local alignment of their underlying micro structures: surfaces with small elements such as fibers, or the ridges of a brushed metal, are very sparse and require a high spatial resolution to be properly represented as a volume. The acquisition of voxel data from such objects is a time and memory-intensive task, and most rendering approaches require an additional Level-of-Detail (LoD) data structure to aggregate the visual appearance, as observed from multiple distances, in order to reduce the number of samples computed per pixel (E.g.: MIP mapping). In this work we introduce first, an efficient parallel voxelization method designed to facilitate fast data aggregation at multiple resolution levels, and second, a novel representation based on hierarchical SGGX clustering that provides better accuracy than baseline methods. We validate our approach with a CUDA-based implementation of the voxelizer, tested both on triangle meshes and volumetric fabrics modeled with explicit fibers. Finally, we show the results generated with a path tracer based on the proposed LoD rendering model.
### Title:
          A High-Resolution Landscape Dataset for Concept-Based XAI With Application to Species Distribution Models
 - **Authors:** Augustin de la Brosse, Damien Garreau, Thomas Houet, Thomas Corpetti
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mapping the spatial distribution of species is essential for conservation policy and invasive species management. Species distribution models (SDMs) are the primary tools for this task, serving two purposes: achieving robust predictive performance while providing ecological insights into the driving factors of distribution. However, the increasing complexity of deep learning SDMs has made extracting these insights more challenging. To reconcile these objectives, we propose the first implementation of concept-based Explainable AI (XAI) for SDMs. We leverage the Robust TCAV (Testing with Concept Activation Vectors) methodology to quantify the influence of landscape concepts on model predictions. To enable this, we provide a new open-access landscape concept dataset derived from high-resolution multispectral and LiDAR drone imagery. It includes 653 patches across 15 distinct landscape concepts and 1,450 random reference patches, designed to suit a wide range of species. We demonstrate this approach through a case study of two aquatic insects, Plecoptera and Trichoptera, using two Convolutional Neural Networks and one Vision Transformer. Results show that concept-based XAI helps validate SDMs against expert knowledge while uncovering novel associations that generate new ecological hypotheses. Robust TCAV also provides landscape-level information, useful for policy-making and land management. Code and datasets are publicly available.
### Title:
          Threat Modeling and Attack Surface Analysis of IoT-Enabled Controlled Environment Agriculture Systems
 - **Authors:** Andrii Vakhnovskyi
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The United States designates Food and Agriculture as one of sixteen critical infrastructure sectors, yet no mandatory cybersecurity requirements exist for agricultural operations and no formal threat model has been published for Controlled Environment Agriculture (CEA) systems. This paper presents the first comprehensive threat model for IoT-enabled CEA, applying STRIDE analysis, MITRE ATT&CK for ICS mapping, and IEC 62443 zone-and-conduit decomposition to a production platform deployed across 30+ commercial facilities in 8 U.S. climate zones. We enumerate 123 unique threats across 25 data-flow-diagram elements spanning 15 communication protocols, 10 of which operate with zero authentication or encryption by design. We identify five novel attack classes unique to AI-driven CEA: stealth destabilization of neural-network-tuned PID controllers, baseline drift poisoning of anomaly detectors, cross-facility propagation via federated transfer learning, adversarial agronomic schedules that exploit crop biology rather than computational models, and reward poisoning of reinforcement-learning energy optimizers. Physical impact analysis quantifies crop loss timelines from minutes (aeroponics) to days, including worker safety hazards from CO2 injection manipulation. A survey of 10 commercial CEA vendors reveals only one CVE ever issued, zero bug bounty programs, and zero IEC 62443 certifications. We propose a defense-in-depth countermeasure framework and recommend Security Level 2 as a minimum baseline.
### Title:
          Lessons from Skill Development Programs -- Livelihood College of Dhamtari
 - **Authors:** Arnab Paul Choudhury, Nihal Patel
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Skill training is crucial for enabling dignified livelihood opportunities. In India, various schemes and initiatives aim to provide skill training in different domains, with ICT and digital technologies playing a vital role. However, there is limited research on understanding on-ground capacities \& constraints and the use of digital tools in these programs. In this study, we look into the mobilization, counseling, and training stages of the 5-stage skill development process that also includes placement and tracking, adopted in Dhamtari's Livelihood College in Chhattisgarh, India, and other programs nationwide. Through the immersion/crystallization approach and mixed-method analysis including GIS mapping, video analysis of CCTV streams, quantitative analysis, and unstructured conversations with administrators, trainers, mobilizers, counselors, and nearby industry personnel for over a year, we identified three major challenges. A lack of inclusive and gendered access to skilling; a tedious manual counseling process with insufficient support staff; and inconsistent trainee attendance alongside sub-standard utilization of digital assets. Finally, we discuss, ways to improve access to skill training by leveraging Vocational Training Partners(VTPs), ways to improve the utilization of existing digital assets, and considerations for improving the counseling process. We conclude by summarizing that skill development programs currently lack institutional elements that enable effective information exchange between stakeholders, thereby creating information bottlenecks that result in inefficiencies, hindering the service delivery. In sum, our study informs the HCI and ICTD literature on the on-ground challenges and constraints faced by stakeholders and the role of technology in supporting such initiatives.
### Title:
          HierFedCEA: Hierarchical Federated Edge Learning for Privacy-Preserving Climate Control Optimization Across Heterogeneous Controlled Environment Agriculture Facilities
 - **Authors:** Andrii Vakhnovskyi
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-facility knowledge transfer in Controlled Environment Agriculture (CEA) can reduce HVAC energy consumption by 30-38% and accelerate new facility commissioning from months to days. However, facility operators refuse to share raw operational data because it encodes commercially sensitive grow recipes. We present HierFedCEA, a hierarchical federated learning framework that enables privacy-preserving climate control optimization across heterogeneous CEA facilities. HierFedCEA decomposes the neural network PID auto-tuning model into three tiers aligned with the physical structure of the control problem: (1) a global physics tier capturing universal thermodynamic relationships; (2) a crop-cluster tier encoding cultivar-specific VPD-to-gain mappings; and (3) a local personalization tier adapting to facility-specific equipment dynamics. The framework applies tier-specific differential privacy budgets and leverages the extreme compactness of the 36-parameter PID model to achieve privacy essentially for free (excess risk < 0.15%). Simulation experiments calibrated from 7+ years of production deployment across 30+ commercial facilities in 8 U.S. climate zones demonstrate that HierFedCEA achieves 94% of centralized training performance while reducing total communication cost to under 1 MB. To the best of our knowledge, this is the first federated learning framework designed for CEA climate control.
### Title:
          Why Multimodal In-Context Learning Lags Behind? Unveiling the Inner Mechanisms and Bottlenecks
 - **Authors:** Yu Wang, Sharon Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context learning (ICL) enables models to adapt to new tasks via inference-time demonstrations. Despite its success in large language models, the extension of ICL to multimodal settings remains poorly understood in terms of its internal mechanisms and how it differs from text-only ICL. In this work, we conduct a systematic analysis of ICL in multimodal large language models. Using identical task formulations across modalities, we show that multimodal ICL performs comparably to text-only ICL in zero-shot settings but degrades significantly under few-shot demonstrations. To understand this gap, we decompose multimodal ICL into task mapping construction and task mapping transfer, and analyze how models establish cross-modal task mappings, and transfer them to query samples across layers. Our analysis reveals that current models lack reasoning-level alignment between visual and textual representations, and fail to reliably transfer learned task mappings to queries. Guided by these findings, we further propose a simple inference-stage enhancement method that reinforces task mapping transfer. Our results provide new insights into the mechanisms and limitations of multimodal ICL and suggest directions for more effective multimodal adaptation. Our code is available \href{this https URL}{here}.
### Title:
          Physically-Guided Optical Inversion Enable Non-Contact Side-Channel Attack on Isolated Screens
 - **Authors:** Zhiwen Zheng, Yuheng Qiao, Xiaoshuai Zhang, Zhao Huang, Tao Zhang, Huiyu Zhou, Shaowei Jiang, Jin Liu, Wenwen Tang, Xingru Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Noncontact exfiltration of electronic screen content poses a security challenge, with side-channel incursions as the principal vector. We introduce an optical projection side-channel paradigm that confronts two core instabilities: (i) the near-singular Jacobian spectrum of projection mapping breaches Hadamard stability, rendering inversion hypersensitive to perturbations; (ii) irreversible compression in light transport obliterates global semantic cues, magnifying reconstruction ambiguity. Exploiting passive speckle patterns formed by diffuse reflection, our Irradiance Robust Radiometric Inversion Network (IR4Net) fuses a Physically Regularized Irradiance Approximation (PRIrr-Approximation), which embeds the radiative transfer equation in a learnable optimizer, with a contour-to-detail cross-scale reconstruction mechanism that arrests noise propagation. Moreover, an Irreversibility Constrained Semantic Reprojection (ICSR) module reinstates lost global structure through context-driven semantic mapping. Evaluated across four scene categories, IR4Net achieves fidelity beyond competing neural approaches while retaining resilience to illumination perturbations.
### Title:
          RadarSplat-RIO: Indoor Radar-Inertial Odometry with Gaussian Splatting-Based Radar Bundle Adjustment
 - **Authors:** Pou-Chun Kung, Yuan Tian, Zhengqin Li, Yue Liu, Eric Whitmire, Wolf Kienzle, Hrvoje Benko
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar is more resilient to adverse weather and lighting conditions than visual and Lidar simultaneous localization and mapping (SLAM). However, most radar SLAM pipelines still rely heavily on frame-to-frame odometry, which leads to substantial drift. While loop closure can correct long-term errors, it requires revisiting places and relies on robust place recognition. In contrast, visual odometry methods typically leverage bundle adjustment (BA) to jointly optimize poses and map within a local window. However, an equivalent BA formulation for radar has remained largely unexplored. We present the first radar BA framework enabled by Gaussian Splatting (GS), a dense and differentiable scene representation. Our method jointly optimizes radar sensor poses and scene geometry using full range-azimuth-Doppler data, bringing the benefits of multi-frame BA to radar for the first time. When integrated with an existing radar-inertial odometry frontend, our approach significantly reduces pose drift and improves robustness. Across multiple indoor scenes, our radar BA achieves substantial gains over the prior radar-inertial odometry, reducing average absolute translational and rotational errors by 90% and 80%, respectively.
### Title:
          Parameter-efficient Quantum Multi-task Learning
 - **Authors:** Hevish Cowlessur, Chandra Thapa, Tansu Alpcan, Seyit Camtepe
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Emerging Technologies (cs.ET); Quantum Physics (quant-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-task learning (MTL) improves generalization and data efficiency by jointly learning related tasks through shared representations. In the widely used hard-parameter-sharing setting, a shared backbone is combined with task-specific prediction heads. However, task-specific parameters can grow rapidly with the number of tasks. Therefore, designing multi-task heads that preserve task specialization while improving parameter efficiency remains a key challenge. In Quantum Machine Learning (QML), variational quantum circuits (VQCs) provide a compact mechanism for mapping classical data to quantum states residing in high-dimensional Hilbert spaces, enabling expressive representations within constrained parameter budgets. We propose a parameter-efficient quantum multi-task learning (QMTL) framework that replaces conventional task-specific linear heads with a fully quantum prediction head in a hybrid architecture. The model consists of a VQC with a shared, task-independent quantum encoding stage, followed by lightweight task-specific ansatz blocks enabling localized task adaptation while maintaining compact parameterization. Under a controlled and capacity-matched formulation where the shared representation dimension grows with the number of tasks, our parameter-scaling analysis demonstrates that a standard classical head exhibits quadratic growth, whereas the proposed quantum head parameter cost scales linearly. We evaluate QMTL on three multi-task benchmarks spanning natural language processing, medical imaging, and multimodal sarcasm detection, where we achieve performance comparable to, and in some cases exceeding, classical hard-parameter-sharing baselines while consistently outperforming existing hybrid quantum MTL models with substantially fewer head parameters. We further demonstrate QMTL's executability on noisy simulators and real quantum hardware, illustrating its feasibility.
### Title:
          Self-Organizing Maps with Optimized Latent Positions
 - **Authors:** Seiki Ubukata, Akira Notsu, Katsuhiro Honda
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-Organizing Maps (SOM) are a classical method for unsupervised learning, vector quantization, and topographic mapping of high-dimensional data. However, existing SOM formulations often involve a trade-off between computational efficiency and a clearly defined optimization objective. Objective-based variants such as Soft Topographic Vector Quantization (STVQ) provide a principled formulation, but their neighborhood-coupled computations become expensive as the number of latent nodes increases. In this paper, we propose Self-Organizing Maps with Optimized Latent Positions (SOM-OLP), an objective-based topographic mapping method that introduces a continuous latent position for each data point. Starting from the neighborhood distortion of STVQ, we construct a separable surrogate local cost based on its local quadratic structure and formulate an entropy-regularized objective based on it. This yields a simple block coordinate descent scheme with closed-form updates for assignment probabilities, latent positions, and reference vectors, while guaranteeing monotonic non-increase of the objective and retaining linear per-iteration complexity in the numbers of data points and latent nodes. Experiments on a synthetic saddle manifold, scalability studies on the Digits and MNIST datasets, and 16 benchmark datasets show that SOM-OLP achieves competitive neighborhood preservation and quantization performance, favorable scalability for large numbers of latent nodes and large datasets, and the best average rank among the compared methods on the benchmark datasets.
### Title:
          ESCAPE: Episodic Spatial Memory and Adaptive Execution Policy for Long-Horizon Mobile Manipulation
 - **Authors:** Jingjing Qian, Zeyuan He, Chen Shi, Lei Xiao, Li Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Coordinating navigation and manipulation with robust performance is essential for embodied AI in complex indoor environments. However, as tasks extend over long horizons, existing methods often struggle due to catastrophic forgetting, spatial inconsistency, and rigid execution. To address these issues, we propose ESCAPE (Episodic Spatial Memory Coupled with an Adaptive Policy for Execution), operating through a tightly coupled perception-grounding-execution workflow. For robust perception, ESCAPE features a Spatio-Temporal Fusion Mapping module to autoregressively construct a depth-free, persistent 3D spatial memory, alongside a Memory-Driven Target Grounding module for precise interaction mask generation. To achieve flexible action, our Adaptive Execution Policy dynamically orchestrates proactive global navigation and reactive local manipulation to seize opportunistic targets. ESCAPE achieves state-of-the-art performance on the ALFRED benchmark, reaching 65.09% and 60.79% success rates in test seen and unseen environments with step-by-step instructions. By reducing redundant exploration, our ESCAPE attains substantial improvements in path-length-weighted metrics and maintains robust performance (61.24% / 56.04%) even without detailed guidance for long-horizon tasks.
### Title:
          From Pixels to Nucleotides: End-to-End Token-Based Video Compression for DNA Storage
 - **Authors:** Cihan Ruan, Lebin Zhou, Bingqing Zhao, Rongduo Han, Qiming Yuan, Chenchen Zhu, Linyi Han, Liang Yang, Wei Wang, Wei Jiang, Nam Ling
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 DNA-based storage has emerged as a promising approach to the global data crisis, offering molecular-scale density and millennial-scale stability at low maintenance cost. Over the past decade, substantial progress has been made in storing text, images, and files in DNA -- yet video remains an open challenge. The difficulty is not merely technical: effective video DNA storage requires co-designing compression and molecular encoding from the ground up, a challenge that sits at the intersection of two fields that have largely evolved independently. In this work, we present HELIX, the first end-to-end neural network jointly optimizing video compression and DNA encoding -- prior approaches treat the two stages independently, leaving biochemical constraints and compression objectives fundamentally misaligned. Our key insight: token-based representations naturally align with DNA's quaternary alphabet -- discrete semantic units map directly to ATCG bases. We introduce TK-SCONE (Token-Kronecker Structured Constraint-Optimized Neural Encoding), which achieves 1.91 bits per nucleotide through Kronecker-structured mixing that breaks spatial correlations and FSM-based mapping that guarantees biochemical constraints. Unlike two-stage approaches, HELIX learns token distributions simultaneously optimized for visual quality, prediction under masking, and DNA synthesis efficiency. This work demonstrates for the first time that learned compression and molecular storage converge naturally at token representations -- suggesting a new paradigm where neural video codecs are designed for biological substrates from the ground up.
### Title:
          Fast Time-Varying Contiguous Cartograms Using Integral Images
 - **Authors:** Vladimir Molchanov, Hennes Rave, Lars Linsen
 - **Subjects:** Subjects:
Computational Geometry (cs.CG); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cartograms are a technique for visually representing geographically distributed statistical data, where values of a numerical attribute are mapped to the size of geographic regions. Contiguous cartograms preserve the adjacencies of the original regions during the mapping. To be useful, contiguous cartograms also require approximate preservation of shapes and relative positions. Due to these desirable properties, contiguous cartograms are among the most popular ones. Most methods for constructing contiguous cartograms exploit a deformation of the original map. Aiming at the preservation of geographical properties, existing approaches are often algorithmically cumbersome and computationally intensive. We propose a novel deformation technique for computing time-varying contiguous cartograms based on integral images evaluated for a series of discrete density distributions. The density textures represent the given dynamic statistical data. The iterative application of the proposed mapping smoothly transforms the domain to gradually equalize the temporal density, i.e., region areas grow or shrink following their evolutionary statistical data. Global shape preservation at each time step is controlled by a single parameter that can be interactively adjusted by the user. Our efficient GPU implementation of the proposed algorithm is significantly faster than existing state-of-the-art methods while achieving comparable quality for cartographic accuracy, shape preservation, and topological error. We investigate strategies for transitioning between adjacent time steps and discuss the parameter choice. Our approach applies to comparative cartograms' morphing and interactive cartogram exploration.
### Title:
          A higher-order dual cell method for time-domain Maxwell equations
 - **Authors:** Lorenzo Codecasa, Bernard Kapidani, Joachim Schöberl, Markus Wess
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a higher-order extension of the dual cell method for the time-domain Maxwell equations in three spatial dimensions. The approach builds upon a variational reinterpretation of the Finite Integration Technique on dual meshes and generalises a previously developed two-dimensional high-order formulation. The electric and magnetic fields are discretised on mutually dual barycentric grids using curl-conforming polynomial spaces constructed via tensor-product Gauss--Radau interpolation. The resulting semi-discrete formulation yields block-diagonal mass matrices and sparse discrete curl operators, enabling explicit time integration while preserving a discrete energy identity. Special attention is devoted to the construction of compatible approximation spaces on the three-dimensional primal and dual meshes, the reference-to-physical element mappings, and the preservation of tangential continuity. We show that the method achieves arbitrary-order convergence, avoids spurious modes, and maintains optimal sparsity properties. Numerical experiments confirm spectral correctness, high-order accuracy, and computational efficiency on unstructured tetrahedral meshes.
### Title:
          Edge-Side Residual Timing and Frequency Control for Software-Defined Ground Stations in 5G NTN Uplinks
 - **Authors:** Longji He, Elena Emma Wang, Xichun Wang, Juntao Xu, Jiaming Li
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper studies a ground-segment implementation problem in 5G non-terrestrial networks (NTN): once UE-side geometric pre-compensation has produced a coarse timing/frequency prior, can an edge-side residual loop keep the uplink inside an NR-feasible operating region under rapid LEO dynamics? We examine this question with a software-defined ground station (SDGS) design that keeps the coarse prior at the UE and closes the residual timing-advance (TA) / carrier-frequency-offset (CFO) loop at the ground-station edge. This paper takes a systems-and-control view rather than proposing a full-stack intelligent architecture. Its evidence base consists of a March 2026 hardware-in-the-loop (HIL) campaign and a companion uncertainty analysis. The HIL campaign includes same-window reference runs collected on the same platform with edge residual control disabled, but it does not include a cloud-loop benchmark. The placement claim is therefore architectural and control-oriented rather than a head-to-head cloud-versus-edge proof. In the Shenzhen steady-state tracking interval, the edge-controlled mode lowers mean RTT from 70.51 +/- 2.34 ms to 32.84 +/- 2.56 ms and, within the retained Layer-3 transport mapping, improves artifact-level goodput from 80.14 +/- 0.14 Mbps to 196.04 +/- 1.87 Mbps relative to that reference configuration. Across four ground-station locations, the closed-loop controller keeps residual TA P95 at 0.49 us and residual CFO P95 within 76-77 Hz. Together with the uncertainty analysis, these observations support a bounded claim: an edge-side residual timing/frequency loop can keep the SDGS uplink in a more stable NR-feasible operating regime under the assumptions retained in the current HIL artifact.
### Title:
          Enhancing Local Life Service Recommendation with Agentic Reasoning in Large Language Model
 - **Authors:** Shiteng Cao, Xiaochong Lan, Yuwei Du, Jie Feng, Yinxing Liu, Xinlei Shi, Yong Li
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Local life service recommendation is distinct from general recommendation scenarios due to its strong living need-driven nature. Fundamentally, accurately identifying a user's immediate living need and recommending the corresponding service are inextricably linked tasks. However, prior works typically treat them in isolation, failing to achieve a unified modeling of need prediction and service recommendation. In this paper, we propose a novel large language model based framework that jointly performs living need prediction and service recommendation. To address the challenge of noise in raw consumption data, we introduce a behavioral clustering approach that filters out accidental factors and selectively preserves typical patterns. This enables the model to learn a robust logical basis for need generation and spontaneously generalize to long-tail scenarios. To navigate the vast search space stemming from diverse needs, merchants, and complex mapping paths, we employ a curriculum learning strategy combined with reinforcement learning with verifiable rewards. This approach guides the model to sequentially learn the logic from need generation to category mapping and specific service selection. Extensive experiments demonstrate that our unified framework significantly enhances both living need prediction performance and recommendation accuracy, validating the effectiveness of jointly modeling living needs and user behaviors.
### Title:
          Geometric Context Transformer for Streaming 3D Reconstruction
 - **Authors:** Lin-Zhuo Chen, Jian Gao, Yihang Chen, Ka Leong Cheng, Yipengjing Sun, Liangxiao Hu, Nan Xue, Xing Zhu, Yujun Shen, Yao Yao, Yinghao Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Streaming 3D reconstruction aims to recover 3D information, such as camera poses and point clouds, from a video stream, which necessitates geometric accuracy, temporal consistency, and computational efficiency. Motivated by the principles of Simultaneous Localization and Mapping (SLAM), we introduce LingBot-Map, a feed-forward 3D foundation model for reconstructing scenes from streaming data, built upon a geometric context transformer (GCT) architecture. A defining aspect of LingBot-Map lies in its carefully designed attention mechanism, which integrates an anchor context, a pose-reference window, and a trajectory memory to address coordinate grounding, dense geometric cues, and long-range drift correction, respectively. This design keeps the streaming state compact while retaining rich geometric context, enabling stable efficient inference at around 20 FPS on 518 x 378 resolution inputs over long sequences exceeding 10,000 frames. Extensive evaluations across a variety of benchmarks demonstrate that our approach achieves superior performance compared to both existing streaming and iterative optimization-based approaches.
## Keyword: localization
### Title:
          Formal Architecture Descriptors as Navigation Primitives for AI Coding Agents
 - **Authors:** Ruoqi Jin
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI coding agents spend a substantial fraction of their tool calls on undirected codebase exploration. We investigate whether providing agents with formal architecture descriptors can reduce this navigational overhead. We present three complementary studies. First, a controlled experiment (24 code localization tasks x 4 conditions, Claude Sonnet 4.6, temperature=0) demonstrates that architecture context reduces navigation steps by 33-44% (Wilcoxon p=0.009, Cohen's d=0.92), with no significant format difference detected across S-expression, JSON, YAML, and Markdown. Second, an artifact-vs-process experiment (15 tasks x 3 conditions) demonstrates that an automatically generated descriptor achieves 100% accuracy versus 80% blind (p=0.002, d=1.04), proving direct navigational value independent of developer self-clarification. Third, an observational field study across 7,012 Claude Code sessions shows 52% reduction in agent behavioral variance. A writer-side experiment (96 generation runs, 96 error injections) reveals critical failure mode differences: JSON fails atomically, YAML silently corrupts 50% of errors, S-expressions detect all structural completeness errors. We propose this http URL, an S-expression architecture descriptor, and open-source the Forge toolkit.
### Title:
          Olfactory pursuit: catching a moving odor source in complex flows
 - **Authors:** Maurizio Carbone, Lorenzo Piro, Robin A. Heinonen, Luca Biferale, Massimo Cencini, Antonio Celani
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Locating and intercepting a moving target from possibly delayed, intermittent sensory signals is a paradigmatic problem in decision-making under uncertainty, and a fundamental challenge for, e.g., animals seeking prey or mates and autonomous robotic systems. Odor signals are intermittent, strongly mixed by turbulent-like transport, and typically lag behind the true target position, thereby complicating localization. Here, we formulate olfactory pursuit as a partially observable Markov decision process in which an agent maintains a joint belief over the target's position and velocity. Using a discrete run-and-tumble model, we compute quasi-optimal policies by numerically solving the Bellman equation and benchmark them against well-established information-theoretic strategies such as Infotaxis. We show that purely exploratory policies are near-optimal when the target frequently reorients, but fail dramatically when the target exhibits persistent motion. We thus introduce a computationally efficient hybrid policy that combines the information-gain drive of Infotaxis with a "greedy" value function derived from an associated fully observable control problem. Our heuristic achieves near-optimal performance across all persistence times and substantially outperforms purely exploratory approaches. Moreover, our proposal demonstrates strong robustness even in more complex search scenarios, including continuous run-and-tumble prey motion with moderate persistence time, model mismatch, and more accurate plume dynamics representation. Our results identify predictive inference of target motion as the key ingredient for effective olfactory pursuit and provide a general framework for search in information-poor, dynamically evolving environments.
### Title:
          GeoLink: A 3D-Aware Framework Towards Better Generalization in Cross-View Geo-Localization
 - **Authors:** Hongyang Zhang, Yinhao Liu, Haitao Zhang, Zhongyi Wen, Shuxian Liang, Xiansheng Hua
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generalizable cross-view geo-localization aims to match the same location across views in unseen regions and conditions without GPS supervision. Its core difficulty lies in severe semantic inconsistency caused by viewpoint variation and poor generalization under domain shift. Existing methods mainly rely on 2D correspondence, but they are easily distracted by redundant shared information across views, leading to less transferable representations. To address this, we propose GeoLink, a 3D-aware semantic-consistent framework for Generalizable cross-view geo-localization. Specifically, we offline reconstruct scene point clouds from multi-view drone images using VGGT, providing stable structural priors. Based on these 3D anchors, we improve 2D representation learning in two complementary ways. A Geometric-aware Semantic Refinement module mitigates potentially redundant and view-biased dependencies in 2D features under 3D guidance. In addition, a Unified View Relation Distillation module transfers 3D structural relations to 2D features, improving cross-view alignment while preserving a 2D-only inference pipeline. Extensive experiments on multiple benchmarks show that GeoLink consistently outperforms state-of-the-art methods and achieves superior generalization across unseen domains and diverse weather environments.
### Title:
          A 3D SAM-Based Progressive Prompting Framework for Multi-Task Segmentation of Radiotherapy-induced Normal Tissue Injuries in Limited-Data Settings
 - **Authors:** Caiwen Jiang, Lei Zeng, Wei Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radiotherapy-induced normal tissue injury is a clinically important complication, and accurate segmentation of injury regions from medical images could facilitate disease assessment, treatment planning, and longitudinal monitoring. However, automatic segmentation of these lesions remains largely unexplored because of limited voxel-level annotations and substantial heterogeneity across injury types, lesion size, and imaging modality. To address this gap, we curate a dedicated head-and-neck radiotherapy-induced normal tissue injury dataset covering three manifestations: osteoradionecrosis (ORN), cerebral edema (CE), and cerebral radiation necrosis (CRN). We further propose a 3D SAM-based progressive prompting framework for multi-task segmentation in limited-data settings. The framework progressively incorporates three complementary prompts: text prompts for task-aware adaptation, dose-guided box prompts for coarse localization, and click prompts for iterative refinement. A small-target focus loss is introduced to improve local prediction and boundary delineation for small and sparse lesions. Experiments on ORN, CE, and CRN demonstrate that the proposed method achieves reliable segmentation performance across diverse injury types and outperforms state-of-the-art methods.
### Title:
          RadarSplat-RIO: Indoor Radar-Inertial Odometry with Gaussian Splatting-Based Radar Bundle Adjustment
 - **Authors:** Pou-Chun Kung, Yuan Tian, Zhengqin Li, Yue Liu, Eric Whitmire, Wolf Kienzle, Hrvoje Benko
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar is more resilient to adverse weather and lighting conditions than visual and Lidar simultaneous localization and mapping (SLAM). However, most radar SLAM pipelines still rely heavily on frame-to-frame odometry, which leads to substantial drift. While loop closure can correct long-term errors, it requires revisiting places and relies on robust place recognition. In contrast, visual odometry methods typically leverage bundle adjustment (BA) to jointly optimize poses and map within a local window. However, an equivalent BA formulation for radar has remained largely unexplored. We present the first radar BA framework enabled by Gaussian Splatting (GS), a dense and differentiable scene representation. Our method jointly optimizes radar sensor poses and scene geometry using full range-azimuth-Doppler data, bringing the benefits of multi-frame BA to radar for the first time. When integrated with an existing radar-inertial odometry frontend, our approach significantly reduces pose drift and improves robustness. Across multiple indoor scenes, our radar BA achieves substantial gains over the prior radar-inertial odometry, reducing average absolute translational and rotational errors by 90% and 80%, respectively.
### Title:
          Weight Patching: Toward Source-Level Mechanistic Localization in LLMs
 - **Authors:** Chenghao Sun, Chengsheng Zhang, Guanzheng Qin, Rui Dai, Xinmei Tian
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability seeks to localize model behavior to the internal components that causally realize it. Prior work has advanced activation-space localization and causal tracing, but modules that appear important in activation space may merely aggregate or amplify upstream signals rather than encode the target capability in their own parameters. To address this gap, we propose Weight Patching, a parameter-space intervention method for source-oriented analysis in paired same-architecture models that differ in how strongly they express a target capability under the inputs of interest. Given a base model and a behavior-specialized counterpart, Weight Patching replaces selected module weights from the specialized model into the base model under a fixed input. We instantiate the method on instruction following and introduce a framework centered on a vector-anchor behavioral interface that provides a shared internal criterion for whether a task-relevant control state has been formed or recovered in open-ended generation. Under this framework, the analysis reveals a hierarchy from shallow candidate source-side carriers to aggregation and routing modules, and further to downstream execution circuits. The recovered component scores can also guide mechanism-aware model merging, improving selective fusion across the evaluated expert combinations and providing additional external validation.
### Title:
          SceneGlue: Scene-Aware Transformer for Feature Matching without Scene-Level Annotation
 - **Authors:** Songlin Du, Xiaoyong Lu, Yaping Yan, Guobao Xiao, Xiaobo Lu, Takeshi Ikenaga
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Local feature matching plays a critical role in understanding the correspondence between cross-view images. However, traditional methods are constrained by the inherent local nature of feature descriptors, limiting their ability to capture non-local scene information that is essential for accurate cross-view correspondence. In this paper, we introduce SceneGlue, a scene-aware feature matching framework designed to overcome these limitations. SceneGlue leverages a hybridizable matching paradigm that integrates implicit parallel attention and explicit cross-view visibility estimation. The parallel attention mechanism simultaneously exchanges information among local descriptors within and across images, enhancing the scene's global context. To further enrich the scene awareness, we propose the Visibility Transformer, which explicitly categorizes features into visible and invisible regions, providing an understanding of cross-view scene visibility. By combining explicit and implicit scene-level awareness, SceneGlue effectively compensates for the local descriptor constraints. Notably, SceneGlue is trained using only local feature matches, without requiring scene-level groundtruth annotations. This scene-aware approach not only improves accuracy and robustness but also enhances interpretability compared to traditional methods. Extensive experiments on applications such as homography estimation, pose estimation, image matching, and visual localization validate SceneGlue's superior performance. The source code is available at this https URL.
### Title:
          HINTBench: Horizon-agent Intrinsic Non-attack Trajectory Benchmark
 - **Authors:** Jiacheng Wang, Jinchang Hou, Fabian Wang, Ping Jian, Chenfu Bao, Zhonghou Lv
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing agent-safety evaluation has focused mainly on externally induced risks. Yet agents may still enter unsafe trajectories under benign conditions. We study this complementary but underexplored setting through the lens of \emph{intrinsic} risk, where intrinsic failures remain latent, propagate across long-horizon execution, and eventually lead to high-consequence outcomes. To evaluate this setting, we introduce \emph{non-attack intrinsic risk auditing} and present \textbf{HINTBench}, a benchmark of 629 agent trajectories (523 risky, 106 safe; 33 steps on average) supporting three tasks: risk detection, risk-step localization, and intrinsic failure-type identification. Its annotations are organized under a unified five-constraint taxonomy. Experiments reveal a substantial capability gap: strong LLMs perform well on trajectory-level risk detection, but their performance drops to below 35 Strict-F1 on risk-step localization, while fine-grained failure diagnosis proves even harder. Existing guard models transfer poorly to this setting. These findings establish intrinsic risk auditing as an open challenge for agent safety.
### Title:
          Decoding the Delta: Unifying Remote Sensing Change Detection and Understanding with Multimodal Large Language Models
 - **Authors:** Xiaohe Li, Jiahao Li, Kaixin Zhang, Yuqiang Fang, Leilei Lin, Hong Wang, Haohua Wu, Zide Fan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While Multimodal Large Language Models (MLLMs) excel in general vision-language tasks, their application to remote sensing change understanding is hindered by a fundamental "temporal blindness". Existing architectures lack intrinsic mechanisms for multi-temporal contrastive reasoning and struggle with precise spatial grounding. To address this, we first introduce Delta-QA, a comprehensive benchmark comprising 180k visual question-answering samples. Delta-QA unifies pixel-level segmentation and visual question answering across bi- and tri-temporal scenarios, structuring change interpretation into four progressive cognitive dimensions. Methodologically, we propose Delta-LLaVA, a novel MLLM framework explicitly tailored for multi-temporal remote sensing interpretation. It overcomes the limitations of naive feature concatenation through three core innovations: a Change-Enhanced Attention module that systematically isolates and amplifies visual differences, a Change-SEG module utilizing Change Prior Embedding to extract differentiable difference features as input for the LLM, and Local Causal Attention to prevent cross-temporal contextual leakage. Extensive experiments demonstrate that Delta-LLaVA decisively outperforms leading generalist MLLMs and specialized segmentation models in complex change deduction and high-precision boundary localization, establishing a unified framework for earth observation intelligence.
### Title:
          UI-Zoomer: Uncertainty-Driven Adaptive Zoom-In for GUI Grounding
 - **Authors:** Fei Tang, Bofan Chen, Zhengxi Lu, Tongbo Chen, Songqin Nong, Tao Jiang, Wenhao Xu, Weiming Lu, Jun Xiao, Yueting Zhuang, Yongliang Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 GUI grounding, which localizes interface elements from screenshots given natural language queries, remains challenging for small icons and dense layouts. Test-time zoom-in methods improve localization by cropping and re-running inference at higher resolution, but apply cropping uniformly across all instances with fixed crop sizes, ignoring whether the model is actually uncertain on each case. We propose \textbf{UI-Zoomer}, a training-free adaptive zoom-in framework that treats both the trigger and scale of zoom-in as a prediction uncertainty quantification problem. A confidence-aware gate fuses spatial consensus among stochastic candidates with token-level generation confidence to selectively trigger zoom-in only when localization is uncertain. When triggered, an uncertainty-driven crop sizing module decomposes prediction variance into inter-sample positional spread and intra-sample box extent, deriving a per-instance crop radius via the law of total variance. Extensive experiments on ScreenSpot-Pro, UI-Vision, and ScreenSpot-v2 demonstrate consistent improvements over strong baselines across multiple model architectures, achieving gains of up to +13.4\%, +10.3\%, and +4.2\% respectively, with no additional training required.
### Title:
          Geometric Context Transformer for Streaming 3D Reconstruction
 - **Authors:** Lin-Zhuo Chen, Jian Gao, Yihang Chen, Ka Leong Cheng, Yipengjing Sun, Liangxiao Hu, Nan Xue, Xing Zhu, Yujun Shen, Yao Yao, Yinghao Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Streaming 3D reconstruction aims to recover 3D information, such as camera poses and point clouds, from a video stream, which necessitates geometric accuracy, temporal consistency, and computational efficiency. Motivated by the principles of Simultaneous Localization and Mapping (SLAM), we introduce LingBot-Map, a feed-forward 3D foundation model for reconstructing scenes from streaming data, built upon a geometric context transformer (GCT) architecture. A defining aspect of LingBot-Map lies in its carefully designed attention mechanism, which integrates an anchor context, a pose-reference window, and a trajectory memory to address coordinate grounding, dense geometric cues, and long-range drift correction, respectively. This design keeps the streaming state compact while retaining rich geometric context, enabling stable efficient inference at around 20 FPS on 518 x 378 resolution inputs over long sequences exceeding 10,000 frames. Extensive evaluations across a variety of benchmarks demonstrate that our approach achieves superior performance compared to both existing streaming and iterative optimization-based approaches.
## Keyword: transformer
### Title:
          A Multi-Model Approach to English-Bangla Sentiment Classification of Government Mobile Banking App Reviews
 - **Authors:** Md. Naim Molla, Md Muhtasim Munif Fahim, Md. Binyamin, Md Jahid Hasan Imran, Tonmoy Shil, Nura Rayhan, Md Rezaul Karim
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 For millions of users in developing economies who depend on mobile banking as their primary gateway to financial services, app quality directly shapes financial access. The study analyzed 5,652 Google Play reviews in English and Bangla (filtered from 11,414 raw reviews) for four Bangladeshi government banking apps. The authors used a hybrid labeling approach that combined use of the reviewer's star rating for each review along with a separate independent XLM-RoBERTa classifier to produce moderate inter-method agreement (kappa = 0.459). Traditional models outperformed transformer-based ones: Random Forest produced the highest accuracy (0.815), while Linear SVM produced the highest weighted F1 score (0.804); both were higher than the performance of fine-tuned XLM-RoBERTa (0.793). McNemar's test confirmed that all classical models were significantly superior to the off-the-shelf XLM-RoBERTa (p < 0.05), while differences with the fine-tuned variant were not statistically significant. DeBERTa-v3 was applied to analyze the sentiment at the aspect level across the reviews for the four apps; the reviewers expressed their dissatisfaction primarily with the speed of transactions and with the poor design of interfaces; eJanata app received the worst ratings from the reviewers across all apps. Three policy recommendations are made based on these findings - remediation of app quality, trust-centred release management, and Bangla-first NLP adoption - to assist state-owned banks in moving towards improving their digital services through data-driven methods. Notably, a 16.1-percentage-point accuracy gap between Bangla and English text highlights the need for low-resource language model development.
### Title:
          Before the First Token: Scale-Dependent Emergence of Hallucination Signals in Autoregressive Language Models
 - **Authors:** Dip Roy, Rajiv Misra, Sanjay Kumar Singh, Anisha Roy
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When do large language models decide to hallucinate? Despite serious consequences in healthcare, law, and finance, few formal answers exist. Recent work shows autoregressive models maintain internal representations distinguishing factual from fictional outputs, but when these representations peak as a function of model scale remains poorly understood. We study the temporal dynamics of hallucination-indicative internal representations across 7 autoregressive transformers (117M--7B parameters) using three fact-based datasets (TriviaQA, Simple Facts, Biography; 552 labeled examples). We identify a scale-dependent phase transition: models below 400M parameters show chance-level probe accuracy at every generation position (AUC = 0.48--0.67), indicating no reliable factuality signal. Above $\sim$1B parameters, a qualitatively different regime emerges where peak detectability occurs at position zero -- before any tokens are generated -- then declines during generation. This pre-generation signal is statistically significant in both Pythia-1.4B (p = 0.012) and Qwen2.5-7B (p = 0.038), spanning distinct architectures and training corpora. At the 7B scale, we observe a striking dissociation: Pythia-6.9B (base model, trained on The Pile) produces a flat temporal profile ($\Delta$ = +0.001, p = 0.989), while instruction-tuned Qwen2.5-7B shows a dominant pre-generation effect. This indicates raw scale alone is insufficient -- knowledge organization through instruction tuning or equivalent post-training is required for pre-commitment encoding. Activation steering along probe-derived directions fails to correct hallucinations across all models, confirming the signal is correlational rather than causal. Our findings provide scale-calibrated detection protocols and a concrete hypothesis on instruction tuning's role in developing knowledge circuits supporting factual generation.
### Title:
          The Long Delay to Arithmetic Generalization: When Learned Representations Outrun Behavior
 - **Authors:** Laura Gomezjurado Gonzalez
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Grokking in transformers trained on algorithmic tasks is characterized by a long delay between training-set fit and abrupt generalization, but the source of that delay remains poorly understood. In encoder-decoder arithmetic models, we argue that this delay reflects limited access to already learned structure rather than failure to acquire that structure in the first place. We study one-step Collatz prediction and find that the encoder organizes parity and residue structure within the first few thousand training steps, while output accuracy remains near chance for tens of thousands more. Causal interventions support the decoder bottleneck hypothesis. Transplanting a trained encoder into a fresh model accelerates grokking by 2.75 times, while transplanting a trained decoder actively hurts. Freezing a converged encoder and retraining only the decoder eliminates the plateau entirely and yields 97.6% accuracy, compared to 86.1% for joint training. What makes the decoder's job harder or easier depends on numeral representation. Across 15 bases, those whose factorization aligns with the Collatz map's arithmetic (e.g., base 24) reach 99.8% accuracy, while binary fails completely because its representations collapse and never recover. The choice of base acts as an inductive bias that controls how much local digit structure the decoder can exploit, producing large differences in learnability from the same underlying task.
### Title:
          Fairness in Multi-Agent Systems for Software Engineering: An SDLC-Oriented Rapid Review
 - **Authors:** Corey Yang-Smith, Ronnie de Souza Santos, Ahmad Abdellatif
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based large language models (LLMs) and multi-agent systems (MAS) are increasingly embedded across the software development lifecycle (SDLC), yet their fairness implications for developer-facing tools remain underexplored despite their growing role in shaping what code is written, reviewed, and released. We present a rapid review of recent work on fairness in MAS, emphasizing LLM-enabled settings and relevance to software engineering. Starting from an initial set of 350 papers, we screened and filtered the corpus for relevance, retaining 18 studies for final analysis. Across these 18 studies, fairness is framed as a combination of trustworthy AI principles, bias reduction across groups, and interactional dynamics in collectives, while evaluation spans accuracy metrics on bias benchmarks, demographic disparity measures, and emergent MAS-specific notions such as conformity and bias amplification. Reported harms include representational, quality-of-service, security and privacy, and governance failures, which we relate to SDLC stages where evidence is most and least developed. We identify three persistent gaps: (1) fragmented, rarely MAS-specific evaluation practices that limit comparability, (2) limited generalization due to simplified environments and narrow attribute coverage, and (3) scarce, weakly evaluated mitigation and governance mechanisms aligned to real software workflows. These findings suggest MAS fairness research is not yet ready to support deployable, fairness-assured software systems, motivating MAS-aware benchmarks, consistent protocols, and lifecycle-spanning governance.
### Title:
          Spectral Entropy Collapse as an Empirical Signature of Delayed Generalisation in Grokking
 - **Authors:** Truong Xuan Khanh, Truong Quynh Hoa, Luu Duc Trung, Phan Thanh Duc
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Grokking -- delayed generalisation long after memorisation -- lacks a predictive mechanistic explanation. We identify the normalised spectral entropy $\tilde{H}(t)$ of the representation covariance as a scalar order parameter for this transition, validated on 1-layer Transformers on group-theoretic tasks. Five contributions: (i) Grokking follows a two-phase pattern: norm expansion then entropy collapse. (ii) $\tilde{H}$ crosses a stable threshold $\tilde{H}^* \approx 0.61$ before generalisation in 100% of runs (mean lead: 1,020 steps). (iii) A causal intervention preventing collapse delays grokking by +5,020 steps ($p=0.044$); a norm-matched control ($n=30$, $p=5\times10^{-5}$) confirms entropy -- not norm -- drives the transition. (iv) A power-law $\Delta T = C_1(\tilde{H}-\tilde{H}^*)^\gamma+C_2$ ($R^2=0.543$) predicts grokking onset with 4.1% error. (v) The mechanism holds across abelian ($\mathbb{Z}/97\mathbb{Z}$) and non-abelian ($S_5$) groups. Crucially, MLPs show entropy collapse without grokking, proving collapse is necessary but not sufficient -- architecture matters. Code: this https URL
### Title:
          Graph Propagated Projection Unlearning: A Unified Framework for Vision and Audio Discriminative Models
 - **Authors:** Shreyansh Pathak, Jyotishman Das
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The need to selectively and efficiently erase learned information from deep neural networks is becoming increasingly important for privacy, regulatory compliance, and adaptive system design. We introduce Graph-Propagated Projection Unlearning (GPPU), a unified and scalable algorithm for class-level unlearning that operates across both vision and audio models. GPPU employs graph-based propagation to identify class-specific directions in the feature space and projects representations onto the orthogonal subspace, followed by targeted fine-tuning, to ensure that target class information is effectively and irreversibly removed. Through comprehensive evaluations on six vision datasets and two large-scale audio benchmarks spanning a variety of architectures including CNNs, Vision Transformers, and Audio Transformers, we demonstrate that GPPU achieves highly efficient unlearning, realizing 10-20x speedups over prior methodologies while preserving model utility on retained classes. Our framework provides a principled and modality-agnostic approach to machine unlearning, evaluated at a scale that has received limited attention in prior work, contributing toward more efficient and responsible deep learning.
### Title:
          Towards Patient-Specific Deformable Registration in Laparoscopic Surgery
 - **Authors:** Alberto Neri, Veronica Penza, Nazim Haouchine, Leonardo S. Mattos
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unsafe surgical care is a critical health concern, often linked to limitations in surgeon experience, skills, and situational awareness. Integrating patient-specific 3D models into the surgical field can enhance visualization, provide real-time anatomical guidance, and reduce intraoperative complications. However, reliably registering these models in general surgery remains challenging due to mismatches between preoperative and intraoperative organ surfaces, such as deformations and noise. To overcome these challenges, we introduce the first patient-specific non-rigid point cloud registration method, which leverages a novel data generation strategy to optimize outcomes for individual patients. Our approach combines a Transformer encoder-decoder architecture with overlap estimation and a dedicated matching module to predict dense correspondences, followed by a physics-based algorithm for registration. Experimental results on both synthetic and real data demonstrate that our patient-specific method significantly outperforms traditional agnostic approaches, achieving 45% Matching Score with 92% Inlier Ratio on synthetic data, highlighting its potential to improve surgical care.
### Title:
          Numerical Instability and Chaos: Quantifying the Unpredictability of Large Language Models
 - **Authors:** Chashi Mahiul Islam, Alan Villarreal, Mao Nishino, Shaeke Salman, Xiuwen Liu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As Large Language Models (LLMs) are increasingly integrated into agentic workflows, their unpredictability stemming from numerical instability has emerged as a critical reliability issue. While recent studies have demonstrated the significant downstream effects of these instabilities, the root causes and underlying mechanisms remain poorly understood. In this paper, we present a rigorous analysis of how unpredictability is rooted in the finite numerical precision of floating-point representations, tracking how rounding errors propagate, amplify, or dissipate through Transformer computation layers. Specifically, we identify a chaotic "avalanche effect" in the early layers, where minor perturbations trigger binary outcomes: either rapid amplification or complete attenuation. Beyond specific error instances, we demonstrate that LLMs exhibit universal, scale-dependent chaotic behaviors characterized by three distinct regimes: 1) a stable regime, where perturbations fall below an input-dependent threshold and vanish, resulting in constant outputs; 2) a chaotic regime, where rounding errors dominate and drive output divergence; and 3) a signal-dominated regime, where true input variations override numerical noise. We validate these findings extensively across multiple datasets and model architectures.
### Title:
          A High-Resolution Landscape Dataset for Concept-Based XAI With Application to Species Distribution Models
 - **Authors:** Augustin de la Brosse, Damien Garreau, Thomas Houet, Thomas Corpetti
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mapping the spatial distribution of species is essential for conservation policy and invasive species management. Species distribution models (SDMs) are the primary tools for this task, serving two purposes: achieving robust predictive performance while providing ecological insights into the driving factors of distribution. However, the increasing complexity of deep learning SDMs has made extracting these insights more challenging. To reconcile these objectives, we propose the first implementation of concept-based Explainable AI (XAI) for SDMs. We leverage the Robust TCAV (Testing with Concept Activation Vectors) methodology to quantify the influence of landscape concepts on model predictions. To enable this, we provide a new open-access landscape concept dataset derived from high-resolution multispectral and LiDAR drone imagery. It includes 653 patches across 15 distinct landscape concepts and 1,450 random reference patches, designed to suit a wide range of species. We demonstrate this approach through a case study of two aquatic insects, Plecoptera and Trichoptera, using two Convolutional Neural Networks and one Vision Transformer. Results show that concept-based XAI helps validate SDMs against expert knowledge while uncovering novel associations that generate new ecological hypotheses. Robust TCAV also provides landscape-level information, useful for policy-making and land management. Code and datasets are publicly available.
### Title:
          Early-Warning Learner Satisfaction Forecasting in MOOCs via Temporal Event Transformers and LLM Text Embeddings
 - **Authors:** Anna Kowalczyk, Jakub Kowalski
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learner satisfaction is a critical quality signal in massive open online courses (MOOCs), directly influencing retention, engagement, and platform reputation. Most existing methods infer satisfaction \emph{post hoc} from end-of-course reviews and star ratings, which are too late for effective intervention. In this paper, we study \textbf{early-warning satisfaction forecasting}: predicting a learner's eventual satisfaction score using only signals observed in the first $t$ days of a course (e.g., $t\!\in\!\{7, 14, 28\}$). We propose \textbf{TET-LLM}, a multi-modal fusion framework that combines (i) a \emph{temporal event Transformer} over fine-grained behavioral event sequences, (ii) \emph{LLM-based contextual embeddings} extracted from early textual traces such as forum posts and short feedback, and (iii) short-text \emph{topic/aspect distributions} to capture coarse satisfaction drivers. A heteroscedastic regression head outputs both a point estimate and a predictive uncertainty score, enabling conservative intervention policies. Comprehensive experiments on a large-scale multi-platform MOOC dataset demonstrate that TET-LLM consistently outperforms aggregate-feature and text-only baselines across all early-horizon settings, achieving an RMSE of 0.82 and AUC of 0.77 at the 7-day horizon. Ablation studies confirm the complementary contribution of each modality, and uncertainty calibration analysis shows near-nominal 90\% interval coverage.
### Title:
          MOONSHOT : A Framework for Multi-Objective Pruning of Vision and Large Language Models
 - **Authors:** Gabriel Afriat, Xiang Meng, Shibal Ibrahim, Hussein Hazimeh, Rahul Mazumder
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Weight pruning is a common technique for compressing large neural networks. We focus on the challenging post-training one-shot setting, where a pre-trained model is compressed without any retraining. Existing one-shot pruning methods typically optimize a single objective, such as a layer-wise reconstruction loss or a second-order Taylor approximation of the training loss. We highlight that neither objective alone is consistently the most effective across architectures and sparsity levels. Motivated by this insight, we propose MOONSHOT, a general and flexible framework that extends any single-objective pruning method into a multi-objective formulation by jointly optimizing both the layer-wise reconstruction error and second-order Taylor approximation of the training loss. MOONSHOT acts as a wrapper around existing pruning algorithms. To enable this integration while maintaining scalability to billion-parameter models, we propose modeling decisions and introduce an efficient procedure for computing the inverse Hessian, preserving the efficiency of state-of-the-art one-shot pruners. When combined with state-of-the-art pruning methods on Llama-3.2 and Llama-2 models, MOONSHOT reduces C4 perplexity by up to 32.6% at 2:4 sparsity and improves zero-shot mean accuracy across seven classification benchmarks by up to 4.9 points. On Vision Transformers, it improves accuracy on ImageNet-1k by over 5 points at 70% sparsity, and on ResNet-50, it yields a 4-point gain at 90% sparsity.
### Title:
          Can Cross-Layer Transcoders Replace Vision Transformer Activations? An Interpretable Perspective on Vision
 - **Authors:** Gerasimos Chatzoudis, Konstantinos D. Polyzos, Zhuowei Li, Difei Gu, Gemma E. Moran, Hao Wang, Dimitris N. Metaxas
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Understanding the internal activations of Vision Transformers (ViTs) is critical for building interpretable and trustworthy models. While Sparse Autoencoders (SAEs) have been used to extract human-interpretable features, they operate on individual layers and fail to capture the cross-layer computational structure of Transformers, as well as the relative significance of each layer in forming the last-layer representation. Alternatively, we introduce the adoption of Cross-Layer Transcoders (CLTs) as reliable, sparse, and depth-aware proxy models for MLP blocks in ViTs. CLTs use an encoder-decoder scheme to reconstruct each post-MLP activation from learned sparse embeddings of preceding layers, yielding a linear decomposition that transforms the final representation of ViTs from an opaque embedding into an additive, layer-resolved construction that enables faithful attribution and process-level interpretability. We train CLTs on CLIP ViT-B/32 and ViT-B/16 across CIFAR-100, COCO, and ImageNet-100. We show that CLTs achieve high reconstruction fidelity with post-MLP activations while preserving and even improving, in some cases, CLIP zero-shot classification accuracy. In terms of interpretability, we show that the cross-layer contribution scores provide faithful attribution, revealing that the final representation is concentrated in a smaller set of dominant layer-wise terms whose removal degrades performance and whose retention largely preserves it. These results showcase the significance of adopting CLTs as an alternative interpretable proxy of ViTs in the vision domain.
### Title:
          Deep Spatially-Regularized and Superpixel-Based Diffusion Learning for Unsupervised Hyperspectral Image Clustering
 - **Authors:** Vutichart Buranasiri, James M. Murphy
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 An unsupervised framework for hyperspectral image (HSI) clustering is proposed that incorporates masked deep representation learning with diffusion-based clustering, extending the Spatially-Regularized Superpixel-based Diffusion Learning ($S^2DL$) algorithm. Initially, a denoised latent representation of the original HSI is learned via an unsupervised masked autoencoder (UMAE) model with a Vision Transformer backbone. The UMAE takes spatial context and long-range spectral correlations into account and incorporates an efficient pretraining process via masking that utilizes only a small subset of training pixels. In the next stage, the entropy rate superpixel (ERS) algorithm is used to segment the image into superpixels, and a spatially regularized diffusion graph is constructed using Euclidean and diffusion distances within the compressed latent space instead of the HSI space. The proposed algorithm, Deep Spatially-Regularized Superpixel-based Diffusion Learning ($DS^2DL$), leverages more faithful diffusion distances and subsequent diffusion graph construction that better reflect the intrinsic geometry of the underlying data manifold, improving labeling accuracy and clustering quality. Experiments on Botswana and KSC datasets demonstrate the efficacy of $DS^2DL$.
### Title:
          SEDTalker: Emotion-Aware 3D Facial Animation Using Frame-Level Speech Emotion Diarization
 - **Authors:** Farzaneh Jafari, Stefano Berretti, Anup Basu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce SEDTalker, an emotion-aware framework for speech-driven 3D facial animation that leverages frame-level speech emotion diarization to achieve fine-grained expressive control. Unlike prior approaches that rely on utterance-level or manually specified emotion labels, our method predicts temporally dense emotion categories and intensities directly from speech, enabling continuous modulation of facial expressions over time. The diarized emotion signals are encoded as learned embeddings and used to condition a speech-driven 3D animation model based on a hybrid Transformer-Mamba architecture. This design allows effective disentanglement of linguistic content and emotional style while preserving identity and temporal coherence. We evaluate our approach on a large-scale multi-corpus dataset for speech emotion diarization and on the EmoVOCA dataset for emotional 3D facial animation. Quantitative results demonstrate strong frame-level emotion recognition performance and low geometric and temporal reconstruction errors, while qualitative results show smooth emotion transitions and consistent expression control. These findings highlight the effectiveness of frame-level emotion diarization for expressive and controllable 3D talking head generation.
### Title:
          Diffusion Sequence Models for Generative In-Context Meta-Learning of Robot Dynamics
 - **Authors:** Angelo Moroncelli, Matteo Rufolo, Gunes Cagin Aydin, Asad Ali Shahid, Loris Roveda
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate modeling of robot dynamics is essential for model-based control, yet remains challenging under distributional shifts and real-time constraints. In this work, we formulate system identification as an in-context meta-learning problem and compare deterministic and generative sequence models for forward dynamics prediction. We take a Transformer-based meta-model, as a strong deterministic baseline, and introduce to this setting two complementary diffusion-based approaches: (i) inpainting diffusion (Diffuser), which learns the joint input-observation distribution, and (ii) conditioned diffusion models (CNN and Transformer), which generate future observations conditioned on control inputs. Through large-scale randomized simulations, we analyze performance across in-distribution and out-of-distribution regimes, as well as computational trade-offs relevant for control. We show that diffusion models significantly improve robustness under distribution shift, with inpainting diffusion achieving the best performance in our experiments. Finally, we demonstrate that warm-started sampling enables diffusion models to operate within real-time constraints, making them viable for control applications. These results highlight generative meta-models as a promising direction for robust system identification in robotics.
### Title:
          RoTE: Coarse-to-Fine Multi-Level Rotary Time Embedding for Sequential Recommendation
 - **Authors:** Haolin Zhang, Longtao Xiao, Guohao Cai, Ruixuan Li, Xiu Li
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sequential recommendation models have been widely adopted for modeling user behavior. Existing approaches typically construct user interaction sequences by sorting items according to timestamps and then model user preferences from historical behaviors. While effective, such a process only considers the order of temporal information but overlooks the actual time spans between interactions, resulting in a coarse representation of users' temporal dynamics and limiting the model's ability to capture long-term and short-term interest evolution. To address this limitation, we propose RoTE, a novel multi-level temporal embedding module that explicitly models time span information in sequential recommendation. RoTE decomposes each interaction timestamp into multiple temporal granularities, ranging from coarse to fine, and incorporates the resulting temporal representations into item embeddings. This design enables models to capture heterogeneous temporal patterns and better perceive temporal distances among user interactions during sequence modeling. RoTE is a lightweight, plug-and-play module that can be seamlessly integrated into existing Transformer-based sequential recommendation models without modifying their backbone architectures. We apply RoTE to several representative models and conduct extensive experiments on three public benchmarks. Experimental results demonstrate that RoTE consistently enhances the corresponding backbone models, achieving up to a 20.11% improvement in NDCG@5, which confirms the effectiveness and generality of the proposed approach. Our code is available at this https URL.
### Title:
          A Multimodal Clinically Informed Coarse-to-Fine Framework for Longitudinal CT Registration in Proton Therapy
 - **Authors:** Caiwen Jiang, Yuzhen Ding, Mi Jia, Samir H. Patel, Terence T. Sio, Jonathan B. Ashman, Lisa A. McGee, Jean-Claude M. Rwigema, William G. Rule, Sameer R. Keole, Sujay A. Vora, William W. Wong, Nathan Y. Yu, Michele Y. Halyard, Steven E. Schild, Dinggang Shen, Wei Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Proton therapy offers superior organ-at-risk sparing but is highly sensitive to anatomical changes, making accurate deformable image registration (DIR) across longitudinal CT scans essential. Conventional DIR methods are often too slow for emerging online adaptive workflows, while existing deep learning-based approaches are primarily designed for generic benchmarks and underutilize clinically relevant information beyond images. To address this gap, we propose a clinically scalable coarse-to-fine deformable registration framework that integrates multimodal information from the proton radiotherapy workflow to accommodate diverse clinical scenarios. The model employs dual CNN-based encoders for hierarchical feature extraction and a transformer-based decoder to progressively refine deformation fields. Beyond CT intensities, clinically critical priors, including target and organ-at-risk contours, dose distributions, and treatment planning text, are incorporated through anatomy- and risk-guided attention, text-conditioned feature modulation, and foreground-aware optimization, enabling anatomically focused and clinically informed deformation estimation. We evaluate the proposed framework on a large-scale proton therapy DIR dataset comprising 1,222 paired planning and repeat CT scans across multiple anatomical regions and disease types. Extensive experiments demonstrate consistent improvements over state-of-the-art methods, enabling fast and robust clinically meaningful registration.
### Title:
          A Unified Conditional Flow for Motion Generation, Editing, and Intra-Structural Retargeting
 - **Authors:** Junlin Li, Xinhao Song, Siqi Wang, Haibin Huang, Yili Zhao
 - **Subjects:** Subjects:
Graphics (cs.GR); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Text-driven motion editing and intra-structural retargeting, where source and target share topology but may differ in bone lengths, are traditionally handled by fragmented pipelines with incompatible inputs and representations: editing relies on specialized generative steering, while retargeting is deferred to geometric post-processing. We present a unifying perspective where both tasks are cast as instances of conditional transport within a single generative framework. By leveraging recent advances in flow matching, we demonstrate that editing and retargeting are fundamentally the same generative task, distinguished only by which conditioning signal, semantic or structural, is modulated during inference. We implement this vision via a rectified-flow motion model jointly conditioned on text prompts and target skeletal structures. Our architecture extends a DiT-style transformer with per-joint tokenization and explicit joint self-attention to strictly enforce kinematic dependencies, while a multi-condition classifier-free guidance strategy balances text adherence with skeletal conformity. Experiments on SnapMoGen and a multi-character Mixamo subset show that a single trained model supports text-to-motion generation, zero-shot editing, and zero-shot intra-structural retargeting. This unified approach simplifies deployment and improves structural consistency compared to task-specific baselines.
### Title:
          MaMe & MaRe: Matrix-Based Token Merging and Restoration for Efficient Visual Perception and Synthesis
 - **Authors:** Simin Huo, Ning Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Token compression is crucial for mitigating the quadratic complexity of self-attention mechanisms in Vision Transformers (ViTs), which often involve numerous input tokens. Existing methods, such as ToMe, rely on GPU-inefficient operations (e.g., sorting, scattered writes), introducing overheads that limit their effectiveness. We introduce MaMe, a training-free, differentiable token merging method based entirely on matrix operations, which is GPU-friendly to accelerate ViTs. Additionally, we present MaRe, its inverse operation, for token restoration, forming a MaMe+MaRe pipeline for image synthesis. When applied to pre-trained models, MaMe doubles ViT-B throughput with a 2% accuracy drop. Notably, fine-tuning the last layer with MaMe boosts ViT-B accuracy by 1.0% at 1.1x speed. In SigLIP2-B@512 zero-shot classification, MaMe provides 1.3x acceleration with negligible performance degradation. In video tasks, MaMe accelerates VideoMAE-L by 48.5% on Kinetics-400 with only a 0.84% accuracy loss. Furthermore, MaMe achieves simultaneous improvements in both performance and speed on some tasks. In image synthesis, the MaMe+MaRe pipeline enhances quality while reducing Stable Diffusion v2.1 generation latency by 31%. Collectively, these results demonstrate MaMe's and MaRe's effectiveness in accelerating vision models. The code is available at this https URL}{this https URL.
### Title:
          A KL Lens on Quantization: Fast, Forward-Only Sensitivity for Mixed-Precision SSM-Transformer Models
 - **Authors:** Jason Kong, Nilesh Prasad Pandey, Flavio Ponzina, Tajana Rosing
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying Large Language Models (LLMs) on edge devices faces severe computational and memory constraints, limiting real-time processing and on-device intelligence. Hybrid architectures combining Structured State Space Models (SSMs) with transformer-based LLMs offer a balance of efficiency and performance. Aggressive quantization can drastically cut model size and speed up inference, but its uneven effects on different components require careful management. In this work, we propose a lightweight, backpropagation-free, surrogate-based sensitivity analysis framework to identify hybrid SSM-Transformer components most susceptible to quantization-induced degradation. Relying solely on forward-pass metrics, our method avoids expensive gradient computations and retraining, making it suitable for situations where access to in-domain data is limited due to proprietary restrictions or privacy constraints. We also provide a formal analysis showing that the Kullback-Leibler (KL) divergence metric better captures quantization sensitivity for Language modeling tasks than widely adopted alternatives such as mean squared error (MSE) and signal-to-quantization-noise ratio (SQNR). Through extensive experiments on SSM and hybrid architectures, our ablation studies confirm that KL-based rankings align with observed performance drops and outperform alternative metrics. This framework enables the practical deployment of advanced hybrid models on resource-constrained edge devices with minimal accuracy loss. We further validate our approach with real-world on-device profiling on Intel Lunar Lake hardware, demonstrating that KL-guided mixed-precision achieves near-FP16 perplexity with model sizes and throughput competitive with Uniform INT4 on both CPU and GPU execution modes. Code is available at this https URL.
### Title:
          FAST: A Synergistic Framework of Attention and State-space Models for Spatiotemporal Traffic Prediction
 - **Authors:** Xinjin Li, Jinghan Cao, Mengyue Wang, Yue Wu, Longxiang Yan, Yeyang Zhou, Ziqi Sha, Yu Ma
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traffic forecasting requires modeling complex temporal dynamics and long-range spatial dependencies over large sensor networks. Existing methods typically face a trade-off between expressiveness and efficiency: Transformer-based models capture global dependencies well but suffer from quadratic complexity, while recent selective state-space models are computationally efficient yet less effective at modeling spatial interactions in graph-structured traffic data. We propose FAST, a unified framework that combines attention and state-space modeling for scalable spatiotemporal traffic forecasting. FAST adopts a Temporal-Spatial-Temporal architecture, where temporal attention modules capture both short- and long-term temporal patterns, and a Mamba-based spatial module models long-range inter-sensor dependencies with linear complexity. To better represent heterogeneous traffic contexts, FAST further introduces a learnable multi-source spatiotemporal embedding that integrates historical traffic flow, temporal context, and node-level information, together with a multi-level skip prediction mechanism for hierarchical feature fusion. Experiments on PeMS04, PeMS07, and PeMS08 show that FAST consistently outperforms strong baselines from Transformer-, GNN-, attention-, and Mamba-based families. In particular, FAST achieves the best MAE and RMSE on all three benchmarks, with up to 4.3\% lower RMSE and 2.8\% lower MAE than the strongest baseline, demonstrating a favorable balance between accuracy, scalability, and generalization.
### Title:
          Outperforming Self-Attention Mechanisms in Solar Irradiance Forecasting via Physics-Guided Neural Networks
 - **Authors:** Mohammed Ezzaldin Babiker Abdullah, Rufaidah Abdallah Ibrahim Mohammed
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate Global Horizontal Irradiance (GHI) forecasting is critical for grid stability, particularly in arid regions characterized by rapid aerosol fluctuations. While recent trends favor computationally expensive Transformer-based architectures, this paper challenges the prevailing "complexity-first" paradigm. We propose a lightweight, Physics-Informed Hybrid CNN-BiLSTM framework that prioritizes domain knowledge over architectural depth. The model integrates a Convolutional Neural Network (CNN) for spatial feature extraction with a Bi-Directional LSTM for capturing temporal dependencies. Unlike standard data-driven approaches, our model is explicitly guided by a vector of 15 engineered features including Clear-Sky indices and Solar Zenith Angle - rather than relying solely on raw historical data. Hyperparameters are rigorously tuned using Bayesian Optimization to ensure global optimality. Experimental validation using NASA POWER data in Sudan demonstrates that our physics-guided approach achieves a Root Mean Square Error (RMSE) of 19.53 W/m^2, significantly outperforming complex attention-based baselines (RMSE 30.64 W/m^2). These results confirm a "Complexity Paradox": in high-noise meteorological tasks, explicit physical constraints offer a more efficient and accurate alternative to self-attention mechanisms. The findings advocate for a shift towards hybrid, physics-aware AI for real-time renewable energy management.
### Title:
          Bridging MARL to SARL: An Order-Independent Multi-Agent Transformer via Latent Consensus
 - **Authors:** Zijian Zhao, Jing Gao, Sen Li
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cooperative multi-agent reinforcement learning (MARL) is widely used to address large joint observation and action spaces by decomposing a centralized control problem into multiple interacting agents. However, such decomposition often introduces additional challenges, including non-stationarity, unstable training, weak coordination, and limited theoretical guarantees. In this paper, we propose the Consensus Multi-Agent Transformer (CMAT), a centralized framework that bridges cooperative MARL to a hierarchical single-agent reinforcement learning (SARL) formulation. CMAT treats all agents as a unified entity and employs a Transformer encoder to process the large joint observation space. To handle the extensive joint action space, we introduce a hierarchical decision-making mechanism in which a Transformer decoder autoregressively generates a high-level consensus vector, simulating the process by which agents reach agreement on their strategies in latent space. Conditioned on this consensus, all agents generate their actions simultaneously, enabling order-independent joint decision making and avoiding the sensitivity to action-generation order in conventional Multi-Agent Transformers (MAT). This factorization allows the joint policy to be optimized using single-agent PPO while preserving expressive coordination through the latent consensus. To evaluate the proposed method, we conduct experiments on benchmark tasks from StarCraft II, Multi-Agent MuJoCo, and Google Research Football. The results show that CMAT achieves superior performance over recent centralized solutions, sequential MARL methods, and conventional MARL baselines. The code for this paper is available at:this https URL .
### Title:
          ADP-DiT: Text-Guided Diffusion Transformer for Brain Image Generation in Alzheimer's Disease Progression
 - **Authors:** Juneyong Lee, Geonwoo Baek, Ikbeom Jang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Alzheimer's disease (AD) progresses heterogeneously across individuals, motivating subject-specific synthesis of follow-up magnetic resonance imaging (MRI) to support progression assessment. While Diffusion Transformers (DiT), an emerging transformer-based diffusion model, offer a scalable backbone for image synthesis, longitudinal AD MRI generation with clinically interpretable control over follow-up time and participant metadata remains underexplored. We present ADP-DiT, an interval-aware, clinically text-conditioned diffusion transformer for longitudinal AD MRI synthesis. ADP-DiT encodes follow-up interval together with multi-domain demographic, diagnostic (CN/MCI/AD), and neuropsychological information as a natural-language prompt, enabling time-specific control beyond coarse diagnostic stages. To inject this conditioning effectively, we use dual text encoders-OpenCLIP for vision-language alignment and T5 for richer clinical-language understanding. Their embeddings are fused into DiT through cross-attention for fine-grained guidance and adaptive layer normalization for global modulation. We further enhance anatomical fidelity by applying rotary positional embeddings to image tokens and performing diffusion in a pre-trained SDXL-VAE latent space to enable efficient high-resolution reconstruction. On 3,321 longitudinal 3T T1-weighted scans from 712 participants (259,038 image slices), ADP-DiT achieves SSIM 0.8739 and PSNR 29.32 dB, improving over a DiT baseline by +0.1087 SSIM and +6.08 dB PSNR while capturing progression-related changes such as ventricular enlargement and shrinking hippocampus. These results suggest that integrating comprehensive, subject-specific clinical conditions with architectures can improve longitudinal AD MRI synthesis.
### Title:
          DiT as Real-Time Rerenderer: Streaming Video Stylization with Autoregressive Diffusion Transformer
 - **Authors:** Hengye Lyu, Zisu Li, Yue Hong, Yueting Weng, Jiaxin Shi, Hanwang Zhang, Chen Liang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in video generation models has significantly accelerated video generation and related downstream tasks. Among these, video stylization holds important research value in areas such as immersive applications and artistic creation, attracting widespread attention. However, existing diffusion-based video stylization methods struggle to maintain stability and consistency when processing long videos, and their high computational cost and multi-step denoising make them difficult to apply in practical scenarios. In this work, we propose RTR-DiT (DiT as Real-Time Rerenderer), a steaming video stylization framework built upon Diffusion Transformer. We first fine-tune a bidirectional teacher model on a curated video stylization dataset, supporting both text-guided and reference-guided video stylization tasks, and subsequently distill it into a few-step autoregressive model via post-training with Self Forcing and Distribution Matching Distillation. Furthermore, we propose a reference-preserving KV cache update strategy that not only enables stable and consistent processing of long videos, but also supports real-time switching between text prompts and reference images. Experimental results show that RTR-DiT outperforms existing methods in both text-guided and reference-guided video stylization tasks, in terms of quantitative metrics and visual quality, and demonstrates excellent performance in real-time long video stylization and interactive style-switching applications.
### Title:
          AI Powered Image Analysis for Phishing Detection
 - **Authors:** K. Acharya, S. Ale, R. Kadel
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Phishing websites now rely heavily on visual imitation-copied logos, similar layouts, and matching colours-to avoid detection by text- and URL-based systems. This paper presents a deep learning approach that uses webpage screenshots for image-based phishing detection. Two vision models, ConvNeXt-Tiny and Vision Transformer (ViT-Base), were tested to see how well they handle visually deceptive phishing pages. The framework covers dataset creation, preprocessing, transfer learning with ImageNet weights, and evaluation using different decision thresholds. The results show that ConvNeXt-Tiny performs the best overall, achieving the highest F1-score at the optimised threshold and running more efficiently than ViT-Base. This highlights the strength of convolutional models for visual phishing detection and shows why threshold tuning is important for real-world deployment. As future work, the curated dataset used in this study will be released to support reproducibility and encourage further research in this area. Unlike many existing studies that primarily report accuracy, this work places greater emphasis on threshold-aware evaluation to better reflect real-world deployment conditions. By examining precision, recall, and F1-score across different decision thresholds, the study identifies operating points that balance detection performance and false-alarm control. In addition, the side-by-side comparison of ConvNeXt-Tiny and ViT-Base under the same experimental setup offers practical insights into how convolutional and transformer-based architectures differ in robustness and computational efficiency for visual phishing detection.
### Title:
          YOCO++: Enhancing YOCO with KV Residual Connections for Efficient LLM Inference
 - **Authors:** You Wu, Ziheng Chen, Yizhen Zhang, Haoyi Wu, Chengting Yu, Yuchi Xu, Wenbo Su, Bo Zheng, Kewei Tu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-layer key-value (KV) compression has been found to be effective in efficient inference of large language models (LLMs). Although they reduce the memory consumption of the KV cache, such methods usually introduce non-negligible performance degradation. In this work, we aim to enhance the performance of YOCO, a cross-layer KV compression method that shares the KVs of the middle layer with the top-half layers. We propose YOCO++, an enhanced YOCO that incorporates a weighted residual connection between the KVs of each bottom-half layer and the bottom layer. Compared to YOCO, YOCO++ increases model capacity while maintaining the same training and inference efficiency. Our experiments show that YOCO++ achieves state-of-the-art performance among the cross-layer KV compression methods at a 50% KV cache compression rate, outperforming the standard Transformer.
### Title:
          UNRIO: Uncertainty-Aware Velocity Learning for Radar-Inertial Odometry
 - **Authors:** Jui-Te Huang, Tinashu Huang, Anthony Rowe, Michael Kaess
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present UNRIO, an uncertainty-aware radar-inertial odometry system that estimates ego-velocity directly from raw mmWave radar IQ signals rather than processed point clouds. Existing radar-inertial odometry methods rely on handcrafted signal processing pipelines that discard latent information in the raw spectrum and require careful parameter tuning. To address this, we propose a transformer-based neural network built on the GRT architecture that processes the full 4-D spectral cube to predict body-frame velocity in two modes: a direct linear velocity estimate and a per-anglebin Doppler velocity map. The network is trained in three stages: geometric pretraining on LiDAR-projected depth, velocity or Doppler fine-tuning, and uncertainty calibration via negative log-likelihood loss, enabling it to produce uncertainty estimates alongside its predictions. These uncertainty estimates are propagated into a sliding-window pose graph that fuses radar velocity factors with IMU preintegration measurements. We train and evaluate UNRIO on the IQ1M dataset across diverse indoor environments with both forward and lateral motion patterns unseen during training. Our method achieves the lowest relative pose error on the majority of sequences, with particularly strong gains over classical DSP baselines on Lateral-motion trajectories where sparse point clouds degrade conventional velocity estimators.
### Title:
          Efficient Multi-View 3D Object Detection by Dynamic Token Selection and Fine-Tuning
 - **Authors:** Danish Nazir, Antoine Hanna-Asaad, Lucas Görnhardt, Jan Piewek, Thorsten Bagdonat, Tim Fingscheidt
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing multi-view three-dimensional (3D) object detection approaches widely adopt large-scale pre-trained vision transformer (ViT)-based foundation models as backbones, being computationally complex. To address this problem, current state-of-the-art (SOTA) \texttt{ToC3D} for efficient multi-view ViT-based 3D object detection employs ego-motion-based relevant token selection. However, there are two key limitations: (1) The fixed layer-individual token selection ratios limit computational efficiency during both training and inference. (2) Full end-to-end retraining of the ViT backbone is required for the multi-view 3D object detection method. In this work, we propose an image token compensator combined with a token selection for ViT backbones to accelerate multi-view 3D object detection. Unlike \texttt{ToC3D}, our approach enables dynamic layer-wise token selection within the ViT backbone. Furthermore, we introduce a parameter-efficient fine-tuning strategy, which trains only the proposed modules, thereby reducing the number of fine-tuned parameters from more than $300$ million (M) to only $1.6$ M. Experiments on the large-scale NuScenes dataset across three multi-view 3D object detection approaches demonstrate that our proposed method decreases computational complexity (GFLOPs) by $48\%$ ... $55\%$, inference latency (on an \texttt{NVIDIA-GV100} GPU) by $9\%$ ... $25\%$, while still improving mean average precision by $1.0\%$ ... $2.8\%$ absolute and NuScenes detection score by $0.4\%$ ... $1.2\%$ absolute compared to so-far SOTA \texttt{ToC3D}.
### Title:
          Ordinary Least Squares is a Special Case of Transformer
 - **Authors:** Xiaojun Tan, Yuchen Zhao
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Statistics Theory (math.ST); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The statistical essence of the Transformer architecture has long remained elusive: Is it a universal approximator, or a neural network version of known computational algorithms? Through rigorous algebraic proof, we show that the latter better describes Transformer's basic nature: Ordinary Least Squares (OLS) is a special case of the single-layer Linear Transformer. Using the spectral decomposition of the empirical covariance matrix, we construct a specific parameter setting where the attention mechanism's forward pass becomes mathematically equivalent to the OLS closed-form projection. This means attention can solve the problem in one forward pass, not by iterating. Building upon this prototypical case, we further uncover a decoupled slow and fast memory mechanism within Transformers. Finally, the evolution from our established linear prototype to standard Transformers is discussed. This progression facilitates the transition of the Hopfield energy function from linear to exponential memory capacity, thereby establishing a clear continuity between modern deep architectures and classical statistical inference.
### Title:
          Design and Behavior of Sparse Mixture-of-Experts Layers in CNN-based Semantic Segmentation
 - **Authors:** Svetlana Pavlitska, Haixi Fan, Konstantin Ditschuneit, J. Marius Zöllner
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse mixture-of-experts (MoE) layers have been shown to substantially increase model capacity without a proportional increase in computational cost and are widely used in transformer architectures, where they typically replace feed-forward network blocks. In contrast, integrating sparse MoE layers into convolutional neural networks (CNNs) remains inconsistent, with most prior work focusing on fine-grained MoEs operating at the filter or channel levels. In this work, we investigate a coarser, patch-wise formulation of sparse MoE layers for semantic segmentation, where local regions are routed to a small subset of convolutional experts. Through experiments on the Cityscapes and BDD100K datasets using encoder-decoder and backbone-based CNNs, we conduct a design analysis to assess how architectural choices affect routing dynamics and expert specialization. Our results demonstrate consistent, architecture-dependent improvements (up to +3.9 mIoU) with little computational overhead, while revealing strong design sensitivity. Our work provides empirical insights into the design and internal dynamics of sparse MoE layers in CNN-based dense prediction. Our code is available at this https URL.
### Title:
          Zero-shot Evaluation of Deep Learning for Java Code Clone Detection
 - **Authors:** Thomas S. Heinze
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Programming Languages (cs.PL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep Learning (DL) is becoming more and more widespread in clone detection, motivated by achieving near-perfect performance for this task. In particular in case of semantic code clones, which share only limited syntax but implement the same or similar functionality, Deep Learning appears to outperform conventional tools. In this paper, we want to investigate the generalizability of DL-based clone detectors for Java. We therefore replicate and evaluate the performance of five state-of-the-art DL-based clone detectors, including Transformers like CodeBERT and single-task models like FA-AST+GMN, in a zero-shot evaluation scenario, where we train/fine-tune and evaluate on different datasets and functionalities. Our experiments demonstrate that the models' generalizability to unseen code is limited. Further analysis reveals that the conventional clone detector NiCad even outperforms the DL-based clone detectors in such a zero-shot evaluation scenario.
### Title:
          From Synchrony to Sequence: Exo-to-Ego Generation via Interpolation
 - **Authors:** Mohammad Mahdi, Nedko Savov, Danda Pani Paudel, Luc Van Gool
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Exo-to-Ego video generation aims to synthesize a first-person video from a synchronized third-person view and corresponding camera poses. While paired supervision is available, synchronized exo-ego data inherently introduces substantial spatio-temporal and geometric discontinuities, violating the smooth-motion assumptions of standard video generation benchmarks. We identify this synchronization-induced jump as the central challenge and propose Syn2Seq-Forcing, a sequential formulation that interpolates between the source and target videos to form a single continuous signal. By reframing Exo2Ego as sequential signal modeling rather than a conventional condition-output task, our approach enables diffusion-based sequence models, e.g. Diffusion Forcing Transformers (DFoT), to capture coherent transitions across frames more effectively. Empirically, we show that interpolating only the videos, without performing pose interpolation already produces significant improvements, emphasizing that the dominant difficulty arises from spatio-temporal discontinuities. Beyond immediate performance gains, this formulation establishes a general and flexible framework capable of unifying both Exo2Ego and Ego2Exo generation within a single continuous sequence model, providing a principled foundation for future research in cross-view video synthesis.
### Title:
          Artificial intelligence application in lymphoma diagnosis with Vision Transformer using weakly supervised training
 - **Authors:** Nghia (Andy)Nguyen, Amer Wahed, Andy Quesada, Yasir Ali, Hanadi El Achi, Y. Helen Zhang, Jocelyn Ursua, Alex Banerjee, Sahib Kalra, L. Jeffrey Medeiros, Jie Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision transformers (ViT) have been shown to allow for more flexible feature detection and can outperform convolutional neural network (CNN) when pre-trained on sufficient data. Due to their promising feature detection capabilities, we deployed ViTs for morphological classification of anaplastic large cell lymphoma (ALCL) versus classic Hodgkin lymphoma (cHL). We had previously designed a ViT model which was trained on a small dataset of 1,200 image patches in fully supervised training. That model achieved a diagnostic accuracy of 100% and an F1 score of 1.0 on the independent test set. Since fully supervised training is not a practical method due to lack of expertise resources in both the training and testing phases, we conducted a recent study on a modified approach to training data (weakly supervised training) and show that labeling training image patch automatically at the slide level of each whole-slide-image is a more practical solution for clinical use of Vision Transformer. Our ViT model, trained on a larger dataset of 100,000 image patches, yields evaluation metrics with significant accuracy, F1 score, and area under the curve (AUC) at 91.85%, 0.92, and 0.98, respectively. These are respectable values that qualify this ViT model, with weakly supervised training, as a suitable tool for a deep learning module in clinical model development using automated image patch extraction.
### Title:
          Sentiment analysis for software engineering: How far can zero-shot learning (ZSL) go?
 - **Authors:** Reem Alfayez, Manal Binkhonain
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sentiment analysis in software engineering focuses on understanding emotions expressed in software artifacts. Previous research highlighted the limitations of applying general off-the-shelf sentiment analysis tools within the software engineering domain and indicated the need for specialized tools tailored to various software engineering contexts. The development of such tools heavily relies on supervised machine learning techniques that necessitate annotated datasets. Acquiring such datasets is a substantial challenge, as it requires domain-specific expertise and significant effort. Objective: This study explores the potential of ZSL to address the scarcity of annotated datasets in sentiment analysis within software engineering Method:} We conducted an empirical experiment to evaluate the performance of various ZSL techniques, including embedding-based, NLI-based, TARS-based, and generative-based ZSL techniques. We assessed the performance of these techniques under different labels setups to examine the impact of label configurations. Additionally, we compared the results of the ZSL techniques with state-of-the-art fine-tuned transformer-based models. Finally, we performed an error analysis to identify the primary causes of misclassifications. Results: Our findings demonstrate that ZSL techniques, particularly those combining expert-curated labels with embedding-based or generative-based models, can achieve macro-F1 scores comparable to fine-tuned transformer-based models. The error analysis revealed that subjectivity in annotation and polar facts are the main contributors to ZSL misclassifications. Conclusion: This study demonstrates the potential of ZSL for sentiment analysis in software engineering. ZSL can provide a solution to the challenge of annotated dataset scarcity by reducing reliance on annotated dataset.
### Title:
          ASTER: Latent Pseudo-Anomaly Generation for Unsupervised Time-Series Anomaly Detection
 - **Authors:** Romain Hermary, Samet Hicsonmez, Dan Pineau, Abd El Rahman Shabayek, Djamila Aouada
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time-series anomaly detection (TSAD) is critical in domains such as industrial monitoring, healthcare, and cybersecurity, but it remains challenging due to rare and heterogeneous anomalies and the scarcity of labelled data. This scarcity makes unsupervised approaches predominant, yet existing methods often rely on reconstruction or forecasting, which struggle with complex data, or on embedding-based approaches that require domain-specific anomaly synthesis and fixed distance metrics. We propose ASTER, a framework that generates pseudo-anomalies directly in the latent space, avoiding handcrafted anomaly injections and the need for domain expertise. A latent-space decoder produces tailored pseudo-anomalies to train a Transformer-based anomaly classifier, while a pre-trained LLM enriches the temporal and contextual representations of this space. Experiments on three benchmark datasets show that ASTER achieves state-of-the-art performance and sets a new standard for LLM-based TSAD.
### Title:
          ASTRA: Enhancing Multi-Subject Generation with Retrieval-Augmented Pose Guidance and Disentangled Position Embedding
 - **Authors:** Tianze Xia, Zijian Ning, Zonglin Zhao, Mingjia Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Subject-driven image generation has shown great success in creating personalized content, but its capabilities are largely confined to single subjects in common poses. Current approaches face a fundamental conflict when handling multiple subjects with complex, distinct actions: preserving individual identities while enforcing precise pose structures. This challenge often leads to identity fusion and pose distortion, as appearance and structure signals become entangled within the model's architecture. To resolve this conflict, we introduce ASTRA(Adaptive Synthesis through Targeted Retrieval Augmentation), a novel framework that architecturally disentangles subject appearance from pose structure within a unified Diffusion Transformer. ASTRA achieves this through a dual-pronged strategy. It first employs a Retrieval-Augmented Pose (RAG-Pose) pipeline to provide a clean, explicit structural prior from a curated database. Then, its core generative model learns to process these dual visual conditions using our Enhanced Universal Rotary Position Embedding (EURoPE), an asymmetric encoding mechanism that decouples identity tokens from spatial locations while binding pose tokens to the canvas. Concurrently, a Disentangled Semantic Modulation (DSM) adapter offloads the identity preservation task into the text conditioning stream. Extensive experiments demonstrate that our integrated approach achieves superior disentanglement. On our designed COCO-based complex pose benchmark, ASTRA achieves a new state-of-the-art in pose adherence, while maintaining high identity fidelity and text alignment in DreamBench.
### Title:
          SceneGlue: Scene-Aware Transformer for Feature Matching without Scene-Level Annotation
 - **Authors:** Songlin Du, Xiaoyong Lu, Yaping Yan, Guobao Xiao, Xiaobo Lu, Takeshi Ikenaga
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Local feature matching plays a critical role in understanding the correspondence between cross-view images. However, traditional methods are constrained by the inherent local nature of feature descriptors, limiting their ability to capture non-local scene information that is essential for accurate cross-view correspondence. In this paper, we introduce SceneGlue, a scene-aware feature matching framework designed to overcome these limitations. SceneGlue leverages a hybridizable matching paradigm that integrates implicit parallel attention and explicit cross-view visibility estimation. The parallel attention mechanism simultaneously exchanges information among local descriptors within and across images, enhancing the scene's global context. To further enrich the scene awareness, we propose the Visibility Transformer, which explicitly categorizes features into visible and invisible regions, providing an understanding of cross-view scene visibility. By combining explicit and implicit scene-level awareness, SceneGlue effectively compensates for the local descriptor constraints. Notably, SceneGlue is trained using only local feature matches, without requiring scene-level groundtruth annotations. This scene-aware approach not only improves accuracy and robustness but also enhances interpretability compared to traditional methods. Extensive experiments on applications such as homography estimation, pose estimation, image matching, and visual localization validate SceneGlue's superior performance. The source code is available at this https URL.
### Title:
          Causal Drawbridges: Characterizing Gradient Blocking of Syntactic Islands in Transformer LMs
 - **Authors:** Sasha Boguraev, Kyle Mahowald
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We show how causal interventions in Transformer models provide insights into English syntax by focusing on a long-standing challenge for syntactic theory: syntactic islands. Extraction from coordinated verb phrases is often degraded, yet acceptability varies gradiently with lexical content (e.g., "I know what he hates art and loves" vs. "I know what he looked down and saw"). We show that modern Transformer language models replicate human judgments across this gradient. Using causal interventions that isolate functionally relevant subspaces in Transformer blocks, attention modules, and MLPs, we demonstrate that extraction from coordination islands engages the same filler-gap mechanisms as canonical wh-dependencies, but that these mechanisms are selectively blocked to varying degrees. By projecting a large corpus of unrelated text onto these causally identified subspaces, we derive a novel linguistic hypothesis: the conjunction "and" is represented differently in extractable versus non-extractable constructions, corresponding to expressions encoding relational dependencies versus purely conjunctive uses. These results illustrate how mechanistic interpretability can inform syntax, generating new hypotheses about linguistic representation and processing.
### Title:
          OneHOI: Unifying Human-Object Interaction Generation and Editing
 - **Authors:** Jiun Tian Hoe, Weipeng Hu, Xudong Jiang, Yap-Peng Tan, Chee Seng Chan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human-Object Interaction (HOI) modelling captures how humans act upon and relate to objects, typically expressed as <person, action, object> triplets. Existing approaches split into two disjoint families: HOI generation synthesises scenes from structured triplets and layout, but fails to integrate mixed conditions like HOI and object-only entities; and HOI editing modifies interactions via text, yet struggles to decouple pose from physical contact and scale to multiple interactions. We introduce OneHOI, a unified diffusion transformer framework that consolidates HOI generation and editing into a single conditional denoising process driven by shared structured interaction representations. At its core, the Relational Diffusion Transformer (R-DiT) models verb-mediated relations through role- and instance-aware HOI tokens, layout-based spatial Action Grounding, a Structured HOI Attention to enforce interaction topology, and HOI RoPE to disentangle multi-HOI scenes. Trained jointly with modality dropout on our HOI-Edit-44K, along with HOI and object-centric datasets, OneHOI supports layout-guided, layout-free, arbitrary-mask, and mixed-condition control, achieving state-of-the-art results across both HOI generation and editing. Code is available at this https URL.
### Title:
          HiVLA: A Visual-Grounded-Centric Hierarchical Embodied Manipulation System
 - **Authors:** Tianshuo Yang, Guanyu Chen, Yutian Chen, Zhixuan Liang, Yitian Liu, Zanxin Chen, Chunpu Xu, Haotian Liang, Jiangmiao Pang, Yao Mu, Ping Luo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 While end-to-end Vision-Language-Action (VLA) models offer a promising paradigm for robotic manipulation, fine-tuning them on narrow control data often compromises the profound reasoning capabilities inherited from their base Vision-Language Models (VLMs). To resolve this fundamental trade-off, we propose HiVLA, a visual-grounded-centric hierarchical framework that explicitly decouples high-level semantic planning from low-level motor control. In high-level part, a VLM planner first performs task decomposition and visual grounding to generate structured plans, comprising a subtask instruction and a precise target bounding box. Then, to translate this plan into physical actions, we introduce a flow-matching Diffusion Transformer (DiT) action expert in low-level part equipped with a novel cascaded cross-attention mechanism. This design sequentially fuses global context, high-resolution object-centric crops and skill semantics, enabling the DiT to focus purely on robust execution. Our decoupled architecture preserves the VLM's zero-shot reasoning while allowing independent improvement of both components. Extensive experiments in simulation and the real world demonstrate that HiVLA significantly outperforms state-of-the-art end-to-end baselines, particularly excelling in long-horizon skill composition and the fine-grained manipulation of small objects in cluttered scenes.
### Title:
          Geometric Context Transformer for Streaming 3D Reconstruction
 - **Authors:** Lin-Zhuo Chen, Jian Gao, Yihang Chen, Ka Leong Cheng, Yipengjing Sun, Liangxiao Hu, Nan Xue, Xing Zhu, Yujun Shen, Yao Yao, Yinghao Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Streaming 3D reconstruction aims to recover 3D information, such as camera poses and point clouds, from a video stream, which necessitates geometric accuracy, temporal consistency, and computational efficiency. Motivated by the principles of Simultaneous Localization and Mapping (SLAM), we introduce LingBot-Map, a feed-forward 3D foundation model for reconstructing scenes from streaming data, built upon a geometric context transformer (GCT) architecture. A defining aspect of LingBot-Map lies in its carefully designed attention mechanism, which integrates an anchor context, a pose-reference window, and a trajectory memory to address coordinate grounding, dense geometric cues, and long-range drift correction, respectively. This design keeps the streaming state compact while retaining rich geometric context, enabling stable efficient inference at around 20 FPS on 518 x 378 resolution inputs over long sequences exceeding 10,000 frames. Extensive evaluations across a variety of benchmarks demonstrate that our approach achieves superior performance compared to both existing streaming and iterative optimization-based approaches.
## Keyword: autonomous driving
### Title:
          Towards Autonomous Driving with Short-Packet Rate Splitting: Age of Information Analysis and Optimization
 - **Authors:** Zirui Zheng, Yingyang Chen, Xinyue Pei, Xingwei Wang, Zhiquan Liu, Theodoros A. Tsiftsis, Miaowen Wen, Pingzhi Fan
 - **Subjects:** Subjects:
Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To address the high mobility impacts and the ultra-reliable and low-latency communication (URLLC) requirements in autonomous driving scenarios, rate-splitting multiple access (RSMA) combined with short-packet communication (SPC) emerges as a promising this http URL vehicles rely on real-time information exchange to ensure safety and coordination, making information freshness this http URL jointly capturing transmission delays and packet errors, age of information (AoI) serves as a comprehensive metric for this http URL this paper, we investigate short-packet rate splitting to enhance information freshness measured by the this http URL splitting the unicast messages into common and private parts, encoding all common parts together with the multicast message into a common stream, and encoding each private part into a private stream, RSMA effectively manages interference and enables achieving lower this http URL considering critical factors such as transmit power, vehicle velocity, blocklength, and the number of transmit antennas, we derive closed-form expressions for the average AoI (AAoI) of the common stream under partial decoding and the overall AAoI under complete this http URL enhance the AAoI performance, we propose the multi-start two-step successive convex approximation (SCA) this http URL algorithm first optimizes the power allocation and subsequently optimizes the rate splitting under the quality of service (QoS) trade-off this http URL results demonstrate that our short-packet rate-splitting scheme significantly improves the AAoI performance while ensuring system fairness and enabling ultra-low AAoI through the common stream, meeting the requirements of autonomous driving this http URL, the trade-off between the common and overall performance is revealed, indicating that the overall performance can be further enhanced while maintaining the advantages of the common stream.
### Title:
          Mosaic: An Extensible Framework for Composing Rule-Based and Learned Motion Planners
 - **Authors:** Nick Le Large, Marlon Steiner, Lingguang Wang, Willi Poh, Jan-Hendrik Pauls, Ömer Şahin Taş, Christoph Stiller
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Safe and explainable motion planning remains a central challenge in autonomous driving. While rule-based planners offer predictable and explainable behavior, they often fail to grasp the complexity and uncertainty of real-world traffic. Conversely, learned planners exhibit strong adaptability but suffer from reduced transparency and occasional safety violations. We introduce Mosaic, an extensible framework for structured decision-making that integrates both paradigms through arbitration graphs. By decoupling trajectory verification and scoring from the generation of trajectories by individual planners, every decision becomes transparent and traceable. Trajectory verification at a higher level introduces redundancy between the planners, limiting emergency braking to the rare case where all planners fail to produce a valid trajectory. Through unified scoring and optimal trajectory selection, rule-based and learned planners with complementary strengths and weaknesses can be combined to yield the best of both worlds. In experimental evaluation on nuPlan, Mosaic achieves 95.48 CLS-NR and 93.98 CLS-R on the Val14 closed-loop benchmark, setting a new state of the art, while reducing at-fault collisions by 30% compared to either planner in isolation. On the interPlan benchmark, focused on highly interactive and difficult scenarios, Mosaic scores 54.30 CLS-R, outperforming its best constituent planner by 23.3% - all without retraining or requiring additional data. The code is available at this http URL.
