# Showing new listings for Friday, 17 April 2026
## Keyword: SLAM
### Title:
          A multi-platform LiDAR dataset for standardized forest inventory measurement at long term ecological monitoring sites
 - **Authors:** Michael R. Chang, Anna Candotti, Karl von Ellenrieder, Enrico Tomelleri, Marco Camurri
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a curated multi-platform LiDAR reference dataset from an instrumented ICOS forest plot, explicitly designed to support calibration, benchmarking, and integration of 3D structural data with ecological observations and standard allometric models. The dataset integrates UAV-borne laser scanning (ULS) to measure canopy coverage, terrestrial laser scanning (TLS) for detailed stem mapping, and backpack mobile laser scanning (MLS) with real-time SLAM for efficient sub-canopy acquisition. We focus on the control plot with the most complete and internally consistent registration, where TLS point clouds (~333 million points) are complemented by ULS and MLS data capturing canopy and understory strata. Marker-free, SLAM-aware protocols were used to reduce field and processing time, while manual and automated methods were combined. Final products are available in LAZ and E57 formats with UTM coordinates, together with registration reports for reproducibility. The dataset provides a benchmark for testing registration methods, evaluating scanning efficiency, and linking point clouds with segmentation, quantitative structure models, and allometric biomass estimation. By situating the acquisitions at a long-term ICOS site, it is explicitly linked to 3D structure with decades of ecological and flux measurements. More broadly, it illustrates how TLS, MLS, and ULS can be combined for repeated inventories and digital twins of forest ecosystems.
### Title:
          Keep It CALM: Toward Calibration-Free Kilometer-Level SLAM with Visual Geometry Foundation Models via an Assistant Eye
 - **Authors:** Tianjun Zhang, Fengyi Zhang, Tianchen Deng, Lin Zhang, Hesheng Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual Geometry Foundation Models (VGFMs) demonstrate remarkable zero-shot capabilities in local reconstruction. However, deploying them for kilometer-level Simultaneous Localization and Mapping (SLAM) remains challenging. In such scenarios, current approaches mainly rely on linear transforms (e.g., Sim3 and SL4) for sub-map alignment, while we argue that a single linear transform is fundamentally insufficient to model the complex, non-linear geometric distortions inherent in VGFM outputs. Forcing such rigid alignment leads to the rapid accumulation of uncorrected residuals, eventually resulting in significant trajectory drift and map divergence. To address these limitations, we present CAL2M (Calibration-free Assistant-eye based Large-scale Localization and Mapping), a plug-and-play framework compatible with arbitrary VGFMs. Distinct from traditional systems, CAL2M introduces an "assistant eye" solely to leverage the prior of constant physical spacing, effectively eliminating scale ambiguity without any temporal or spatial pre-calibration. Furthermore, leveraging the assumption of accurate feature matching, we propose an epipolar-guided intrinsic and pose correction model. Supported by an online intrinsic search module, it can effectively rectify rotation and translation errors caused by inaccurate intrinsics through fundamental matrix decomposition. Finally, to ensure accurate mapping, we introduce a globally consistent mapping strategy based on anchor propagation. By constructing and fusing anchors across the trajectory, we establish a direct local-to-global mapping relationship. This enables the application of nonlinear transformations to elastically align sub-maps, effectively eliminating geometric misalignments and ensuring a globally consistent reconstruction. The source code of CAL2M will be publicly available at this https URL.
### Title:
          CAVERS: Multimodal SLAM Data from a Natural Karstic Cave with Ground Truth Motion Capture
 - **Authors:** Giacomo Franchini, David Rodríguez-Martínez, Alfonso Martínez-Petersen, C. J. Pérez-del-Pulgar, Marcello Chiaberge
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous robots operating in natural karstic caves face perception and navigation challenges that are qualitatively distinct from those encountered in mines or tunnels: irregular geometry, reflective wet surfaces, near-zero ambient light, and complex branching passages. Yet publicly available datasets targeting this environment remain scarce and offer limited sensing modalities and environmental diversity. We present CAVERS, a multimodal dataset acquired in two structurally distinct rooms of Cueva de la Victoria, Málaga, Spain, comprising 24 sequences totaling approximately 335 GB of recorded data. The sensor suite combines an Intel RealSense D435i RGB-D-I camera, an Optris PI640i near-IR thermal camera, and a Velodyne VLP-16 LiDAR, operated both handheld and mounted on a wheeled rover under full darkness and artificial illumination. For most of the sequences, mm-accurate 6-DoF ground truth pose and velocity at 120 Hz are provided by an Optirack motion capture system installed directly inside the cave. We benchmark seven state-of-the-art SLAM and odometry algorithms spanning visual, visual-inertial, thermal-inertial, and LiDAR-based pipelines, as well as a 3D reconstruction pipeline, demonstrating the dataset's usability. %The dataset and all supplementary material are publicly available at: this https URL.
### Title:
          Dual Pose-Graph Semantic Localization for Vision-Based Autonomous Drone Racing
 - **Authors:** David Perez-Saura, Miguel Fernandez-Cortizas, Alvaro J. Gaona, Pascual Campoy
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous drone racing demands robust real-time localization under extreme conditions: high-speed flight, aggressive maneuvers, and payload-constrained platforms that often rely on a single camera for perception. Existing visual SLAM systems, while effective in general scenarios, struggle with motion blur and feature instability inherent to racing dynamics, and do not exploit the structured nature of racing environments. In this work, we present a dual pose-graph architecture that fuses odometry with semantic detections for robust localization. A temporary graph accumulates multiple gate observations between keyframes and optimizes them into a single refined constraint per landmark, which is then promoted to a persistent main graph. This design preserves the information richness of frequent detections while preventing graph growth from degrading real-time performance. The system is designed to be sensor-agnostic, although in this work we validate it using monocular visual-inertial odometry and visual gate detections. Experimental evaluation on the TII-RATM dataset shows a 56% to 74% reduction in ATE compared to standalone VIO, while an ablation study confirms that the dual-graph architecture achieves 10% to 12% higher accuracy than a single-graph baseline at identical computational cost. Deployment in the A2RL competition demonstrated that the system performs real-time onboard localization during flight, reducing the drift of the odometry baseline by up to 4.2 m per lap.
## Keyword: odometry
### Title:
          BIEVR-LIO: Robust LiDAR-Inertial Odometry through Bump-Image-Enhanced Voxel Maps
 - **Authors:** Patrick Pfreundschuh, Turcan Tuna, Cedric Le Gentil, Roland Siegwart, Cesar Cadena, Helen Oleynikova
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable odometry is essential for mobile robots as they increasingly enter more challenging environments, which often contain little information to constrain point cloud registration, resulting in degraded LiDAR-Inertial Odometry (LIO) accuracy or even divergence. To address this, we present BIEVR-LIO, a novel approach designed specifically to exploit subtle variations in the available geometry for improved robustness. We propose a high-resolution map representation that stores surfaces as compact voxel-wise oriented height images. This representation can directly be used for registration without the calculation of intermediate geometric primitives while still supporting efficient updates. Since informative geometry is often sparsely distributed in the environment, we further propose a map-informed point sampling strategy to focus registration on geometrically informative regions, improving robustness in uninformative environments while reducing computational cost compared to global high-resolution sampling. Experiments across multiple sensors, platforms, and environments demonstrates state-of-the-art performance in well-constrained scenes and substantial improvements in challenging scenarios where baseline methods diverge. Additionally, we demonstrate that the fine-grained geometry captured by BIEVR-LIO can be used for downstream tasks such as elevation mapping for robot locomotion.
### Title:
          CT-VIR: Continuous-Time Visual-Inertial-Ranging Fusion for Indoor Localization with Sparse Anchors
 - **Authors:** Yu-An Liu, Li Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual-inertial odometry (VIO) is widely used for mobile robot localization, but its long-term accuracy degrades without global constraints. Incorporating ranging sensors such as ultra-wideband (UWB) can mitigate drift; however, high-accuracy ranging usually requires well-deployed anchors, which is difficult to ensure in narrow or low-power environments. Moreover, most existing visual-inertial-ranging (VIR) fusion methods rely on discrete time-based filtering or optimization, making it difficult to balance positioning accuracy, trajectory consistency, and fusion efficiency under asynchronous multi-sensor sampling. To address these issues, we propose a spline-based continuous-time state estimation method for VIR fusion localization. In the preprocessing stage, VIO motion priors and UWB ranging measurements are used to construct virtual anchors and reject outliers, thereby alleviating geometric degeneration and improving range reliability. In the estimation stage, the pose trajectory is parameterized in continuous time using a B-spline, while inertial, visual, and ranging constraints are formulated as factors in a sliding-window graph. The spline control points, together with a small set of auxiliary parameters, are then jointly optimized to obtain a continuous-time trajectory estimate. Evaluations on public datasets and real-world experiments demonstrate the effectiveness and practical potential of the proposed approach.
### Title:
          CAVERS: Multimodal SLAM Data from a Natural Karstic Cave with Ground Truth Motion Capture
 - **Authors:** Giacomo Franchini, David Rodríguez-Martínez, Alfonso Martínez-Petersen, C. J. Pérez-del-Pulgar, Marcello Chiaberge
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous robots operating in natural karstic caves face perception and navigation challenges that are qualitatively distinct from those encountered in mines or tunnels: irregular geometry, reflective wet surfaces, near-zero ambient light, and complex branching passages. Yet publicly available datasets targeting this environment remain scarce and offer limited sensing modalities and environmental diversity. We present CAVERS, a multimodal dataset acquired in two structurally distinct rooms of Cueva de la Victoria, Málaga, Spain, comprising 24 sequences totaling approximately 335 GB of recorded data. The sensor suite combines an Intel RealSense D435i RGB-D-I camera, an Optris PI640i near-IR thermal camera, and a Velodyne VLP-16 LiDAR, operated both handheld and mounted on a wheeled rover under full darkness and artificial illumination. For most of the sequences, mm-accurate 6-DoF ground truth pose and velocity at 120 Hz are provided by an Optirack motion capture system installed directly inside the cave. We benchmark seven state-of-the-art SLAM and odometry algorithms spanning visual, visual-inertial, thermal-inertial, and LiDAR-based pipelines, as well as a 3D reconstruction pipeline, demonstrating the dataset's usability. %The dataset and all supplementary material are publicly available at: this https URL.
### Title:
          Dual Pose-Graph Semantic Localization for Vision-Based Autonomous Drone Racing
 - **Authors:** David Perez-Saura, Miguel Fernandez-Cortizas, Alvaro J. Gaona, Pascual Campoy
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous drone racing demands robust real-time localization under extreme conditions: high-speed flight, aggressive maneuvers, and payload-constrained platforms that often rely on a single camera for perception. Existing visual SLAM systems, while effective in general scenarios, struggle with motion blur and feature instability inherent to racing dynamics, and do not exploit the structured nature of racing environments. In this work, we present a dual pose-graph architecture that fuses odometry with semantic detections for robust localization. A temporary graph accumulates multiple gate observations between keyframes and optimizes them into a single refined constraint per landmark, which is then promoted to a persistent main graph. This design preserves the information richness of frequent detections while preventing graph growth from degrading real-time performance. The system is designed to be sensor-agnostic, although in this work we validate it using monocular visual-inertial odometry and visual gate detections. Experimental evaluation on the TII-RATM dataset shows a 56% to 74% reduction in ATE compared to standalone VIO, while an ablation study confirms that the dual-graph architecture achieves 10% to 12% higher accuracy than a single-graph baseline at identical computational cost. Deployment in the A2RL competition demonstrated that the system performs real-time onboard localization during flight, reducing the drift of the odometry baseline by up to 4.2 m per lap.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          RoSLAC: Robust Simultaneous Localization and Calibration of Multiple Magnetometers
 - **Authors:** Qiyang Lyu, Zhenyu Wu, Wei Wang, Hongming Shen, Danwei Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localization of autonomous mobile robots (AMRs) in enclosed or semi-enclosed environments such as offices, hotels, hospitals, indoor parking facilities, and underground spaces where GPS signals are weak or unavailable remains a major obstacle to the deployment of fully autonomous systems. Infrastructure-based localization approaches, such as QR codes and RFID, are constrained by high installation and maintenance costs as well as limited flexibility, while onboard sensor-based methods, including LiDAR- and vision-based solutions, are affected by ambiguous geometric features and frequent occlusions caused by dynamic obstacles such as pedestrians. Ambient magnetic field (AMF)-based localization has therefore attracted growing interest in recent years because it does not rely on external infrastructure or geometric features, making it well-suited for AMR applications such as service robots and security robots. However, magnetometer measurements are often corrupted by distortions caused by ferromagnetic materials present on the sensor platform, which bias the AMF and degrade localization reliability. As a result, accurate magnetometer calibration to estimate distortion parameters becomes essential. Conventional calibration methods that rely on rotating the magnetometer are impractical for large and heavy platforms. To address this limitation, this paper proposes a robust simultaneous localization and calibration (RoSLAC) approach based on alternating optimization, which iteratively and efficiently estimates both the platform pose and magnetometer calibration parameters. Extensive evaluations conducted in high-fidelity simulation and real-world environments demonstrate that the proposed RoSLAC method achieves high localization accuracy while maintaining low computational cost compared with state-of-the-art magnetometer calibration techniques.
### Title:
          BIEVR-LIO: Robust LiDAR-Inertial Odometry through Bump-Image-Enhanced Voxel Maps
 - **Authors:** Patrick Pfreundschuh, Turcan Tuna, Cedric Le Gentil, Roland Siegwart, Cesar Cadena, Helen Oleynikova
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable odometry is essential for mobile robots as they increasingly enter more challenging environments, which often contain little information to constrain point cloud registration, resulting in degraded LiDAR-Inertial Odometry (LIO) accuracy or even divergence. To address this, we present BIEVR-LIO, a novel approach designed specifically to exploit subtle variations in the available geometry for improved robustness. We propose a high-resolution map representation that stores surfaces as compact voxel-wise oriented height images. This representation can directly be used for registration without the calculation of intermediate geometric primitives while still supporting efficient updates. Since informative geometry is often sparsely distributed in the environment, we further propose a map-informed point sampling strategy to focus registration on geometrically informative regions, improving robustness in uninformative environments while reducing computational cost compared to global high-resolution sampling. Experiments across multiple sensors, platforms, and environments demonstrates state-of-the-art performance in well-constrained scenes and substantial improvements in challenging scenarios where baseline methods diverge. Additionally, we demonstrate that the fine-grained geometry captured by BIEVR-LIO can be used for downstream tasks such as elevation mapping for robot locomotion.
### Title:
          A multi-platform LiDAR dataset for standardized forest inventory measurement at long term ecological monitoring sites
 - **Authors:** Michael R. Chang, Anna Candotti, Karl von Ellenrieder, Enrico Tomelleri, Marco Camurri
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a curated multi-platform LiDAR reference dataset from an instrumented ICOS forest plot, explicitly designed to support calibration, benchmarking, and integration of 3D structural data with ecological observations and standard allometric models. The dataset integrates UAV-borne laser scanning (ULS) to measure canopy coverage, terrestrial laser scanning (TLS) for detailed stem mapping, and backpack mobile laser scanning (MLS) with real-time SLAM for efficient sub-canopy acquisition. We focus on the control plot with the most complete and internally consistent registration, where TLS point clouds (~333 million points) are complemented by ULS and MLS data capturing canopy and understory strata. Marker-free, SLAM-aware protocols were used to reduce field and processing time, while manual and automated methods were combined. Final products are available in LAZ and E57 formats with UTM coordinates, together with registration reports for reproducibility. The dataset provides a benchmark for testing registration methods, evaluating scanning efficiency, and linking point clouds with segmentation, quantitative structure models, and allometric biomass estimation. By situating the acquisitions at a long-term ICOS site, it is explicitly linked to 3D structure with decades of ecological and flux measurements. More broadly, it illustrates how TLS, MLS, and ULS can be combined for repeated inventories and digital twins of forest ecosystems.
### Title:
          Integrating Object Detection, LiDAR-Enhanced Depth Estimation, and Segmentation Models for Railway Environments
 - **Authors:** Enrico Francesco Giannico, Federico Nesti, Gianluca D'Amico, Mauro Marinoni, Edoardo Carosio, Filippo Salotti, Salvatore Sabina, Giorgio Buttazzo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Obstacle detection in railway environments is crucial for ensuring safety. However, very few studies address the problem using a complete, modular, and flexible system that can both detect objects in the scene and estimate their distance from the vehicle. Most works focus solely on detection, others attempt to identify the track, and only a few estimate obstacle distances. Additionally, evaluating these systems is challenging due to the lack of ground truth data. In this paper, we propose a modular and flexible framework that identifies the rail track, detects potential obstacles, and estimates their distance by integrating three neural networks for object detection, track segmentation, and monocular depth estimation with LiDAR point clouds. To enable a reliable and quantitative evaluation, the proposed framework is assessed using a synthetic dataset (SynDRA), which provides accurate ground truth annotations, allowing for direct performance comparison with existing methods. The proposed system achieves a mean absolute error (MAE) as low as 0.63 meters by integrating monocular depth maps with LiDAR, enabling not only accurate distance estimates but also spatial perception of the scene.
### Title:
          CAVERS: Multimodal SLAM Data from a Natural Karstic Cave with Ground Truth Motion Capture
 - **Authors:** Giacomo Franchini, David Rodríguez-Martínez, Alfonso Martínez-Petersen, C. J. Pérez-del-Pulgar, Marcello Chiaberge
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous robots operating in natural karstic caves face perception and navigation challenges that are qualitatively distinct from those encountered in mines or tunnels: irregular geometry, reflective wet surfaces, near-zero ambient light, and complex branching passages. Yet publicly available datasets targeting this environment remain scarce and offer limited sensing modalities and environmental diversity. We present CAVERS, a multimodal dataset acquired in two structurally distinct rooms of Cueva de la Victoria, Málaga, Spain, comprising 24 sequences totaling approximately 335 GB of recorded data. The sensor suite combines an Intel RealSense D435i RGB-D-I camera, an Optris PI640i near-IR thermal camera, and a Velodyne VLP-16 LiDAR, operated both handheld and mounted on a wheeled rover under full darkness and artificial illumination. For most of the sequences, mm-accurate 6-DoF ground truth pose and velocity at 120 Hz are provided by an Optirack motion capture system installed directly inside the cave. We benchmark seven state-of-the-art SLAM and odometry algorithms spanning visual, visual-inertial, thermal-inertial, and LiDAR-based pipelines, as well as a 3D reconstruction pipeline, demonstrating the dataset's usability. %The dataset and all supplementary material are publicly available at: this https URL.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          NG-GS: NeRF-Guided 3D Gaussian Splatting Segmentation
 - **Authors:** Yi He, Tao Wang, Yi Jin, Congyan Lang, Yidong Li, Haibin Ling
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in 3D Gaussian Splatting (3DGS) have enabled highly efficient and photorealistic novel view synthesis. However, segmenting objects accurately in 3DGS remains challenging due to the discrete nature of Gaussian representations, which often leads to aliasing and artifacts at object boundaries. In this paper, we introduce NG-GS, a novel framework for high-quality object segmentation in 3DGS that explicitly addresses boundary discretization. Our approach begins by automatically identifying ambiguous Gaussians at object boundaries using mask variance analysis. We then apply radial basis function (RBF) interpolation to construct a spatially continuous feature field, enhanced by multi-resolution hash encoding for efficient multi-scale representation. A joint optimization strategy aligns 3DGS with a lightweight NeRF module through alignment and spatial continuity losses, ensuring smooth and consistent segmentation boundaries. Extensive experiments on NVOS, LERF-OVS, and ScanNet benchmarks demonstrate that our method achieves state-of-the-art performance, with significant gains in boundary mIoU. Code is available at this https URL.
### Title:
          Hybrid Latents -- Geometry-Appearance-Aware Surfel Splatting
 - **Authors:** Neel Kelkar, Simon Niedermayr, Klaus Engel, Rüdiger Westermann
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a hybrid Gaussian-hash-grid radiance representation for reconstructing 2D Gaussian scene models from multi-view images. Similar to NeST splatting, our approach reduces the entanglement between geometry and appearance common in NeRF-based models, but adds per-Gaussian latent features alongside hash-grid features to bias the optimizer toward a separation of low- and high-frequency scene components. This explicit frequency-based decomposition reduces the tendency of high-frequency texture to compensate for geometric errors. Encouraging Gaussians with hard opacity falloffs further strengthens the separation between geometry and appearance, improving both geometry reconstruction and rendering efficiency. Finally, probabilistic pruning combined with a sparsity-inducing BCE opacity loss allows redundant Gaussians to be turned off, yielding a minimal set of Gaussians sufficient to represent the scene. Using both synthetic and real-world datasets, we compare against the state of the art in Gaussian-based novel-view synthesis and demonstrate superior reconstruction fidelity with an order of magnitude fewer primitives.
## Keyword: mapping
### Title:
          Hierarchical Retrieval Augmented Generation for Adversarial Technique Annotation in Cyber Threat Intelligence Text
 - **Authors:** Filippo Morbiato, Markus Keller, Priya Nair, Luca Romano
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mapping Cyber Threat Intelligence (CTI) text to MITRE ATT\&CK technique IDs is a critical task for understanding adversary behaviors and automating threat defense. While recent Retrieval-Augmented Generation (RAG) approaches have demonstrated promising capabilities in this domain, they fundamentally rely on a flat retrieval paradigm. By treating all techniques uniformly, these methods overlook the inherent taxonomy of the ATT\&CK framework, where techniques are structurally organized under high-level tactics. In this paper, we propose H-TechniqueRAG, a novel hierarchical RAG framework that injects this tactic-technique taxonomy as a strong inductive bias to achieve highly efficient and accurate annotation. Our approach introduces a two-stage hierarchical retrieval mechanism: it first identifies the macro-level tactics (the adversary's technical goals) and subsequently narrows the search to techniques within those tactics, effectively reducing the candidate search space by 77.5\%. To further bridge the gap between retrieval and generation, we design a tactic-aware reranking module and a hierarchy-constrained context organization strategy that mitigates LLM context overload and improves reasoning precision. Comprehensive experiments across three diverse CTI datasets demonstrate that H-TechniqueRAG not only outperforms the state-of-the-art TechniqueRAG by 3.8\% in F1 score, but also achieves a 62.4\% reduction in inference latency and a 60\% decrease in LLM API calls. Further analysis reveals that our hierarchical structural priors equip the model with superior cross-domain generalization and provide security analysts with highly interpretable, step-by-step decision paths.
### Title:
          SatBLIP: Context Understanding and Feature Identification from Satellite Imagery with Vision-Language Learning
 - **Authors:** Xue Wu, Shengting Cao, Jiaqi Gong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rural environmental risks are shaped by place-based conditions (e.g., housing quality, road access, land-surface patterns), yet standard vulnerability indices are coarse and provide limited insight into risk contexts. We propose SatBLIP, a satellite-specific vision-language framework for rural context understanding and feature identification that predicts county-level Social Vulnerability Index (SVI). SatBLIP addresses limitations of prior remote sensing pipelines-handcrafted features, manual virtual audits, and natural-image-trained VLMs-by coupling contrastive image-text alignment with bootstrapped captioning tailored to satellite semantics. We use GPT-4o to generate structured descriptions of satellite tiles (roof type/condition, house size, yard attributes, greenery, and road context), then fine-tune a satellite-adapted BLIP model to generate captions for unseen images. Captions are encoded with CLIP and fused with LLM-derived embeddings via attention for SVI estimation under spatial aggregation. Using SHAP, we identify salient attributes (e.g., roof form/condition, street width, vegetation, cars/open space) that consistently drive robust predictions, enabling interpretable mapping of rural risk environments.
### Title:
          BIEVR-LIO: Robust LiDAR-Inertial Odometry through Bump-Image-Enhanced Voxel Maps
 - **Authors:** Patrick Pfreundschuh, Turcan Tuna, Cedric Le Gentil, Roland Siegwart, Cesar Cadena, Helen Oleynikova
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable odometry is essential for mobile robots as they increasingly enter more challenging environments, which often contain little information to constrain point cloud registration, resulting in degraded LiDAR-Inertial Odometry (LIO) accuracy or even divergence. To address this, we present BIEVR-LIO, a novel approach designed specifically to exploit subtle variations in the available geometry for improved robustness. We propose a high-resolution map representation that stores surfaces as compact voxel-wise oriented height images. This representation can directly be used for registration without the calculation of intermediate geometric primitives while still supporting efficient updates. Since informative geometry is often sparsely distributed in the environment, we further propose a map-informed point sampling strategy to focus registration on geometrically informative regions, improving robustness in uninformative environments while reducing computational cost compared to global high-resolution sampling. Experiments across multiple sensors, platforms, and environments demonstrates state-of-the-art performance in well-constrained scenes and substantial improvements in challenging scenarios where baseline methods diverge. Additionally, we demonstrate that the fine-grained geometry captured by BIEVR-LIO can be used for downstream tasks such as elevation mapping for robot locomotion.
### Title:
          Crowdsourcing of Real-world Image Annotation via Visual Properties
 - **Authors:** Xiaolei Diao, Fausto Giunchiglia
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in data-centric artificial intelligence highlight inherent limitations in object recognition datasets. One of the primary issues stems from the semantic gap problem, which results in complex many-to-many mappings between visual data and linguistic descriptions. This bias adversely affects performance in computer vision tasks. This paper proposes an image annotation methodology that integrates knowledge representation, natural language processing, and computer vision techniques, aiming to reduce annotator subjectivity by applying visual property constraints. We introduce an interactive crowdsourcing framework that dynamically asks questions based on a predefined object category hierarchy and annotator feedback, guiding image annotation by visual properties. Experiments demonstrate the effectiveness of this methodology, and annotator feedback is discussed to optimize the crowdsourcing setup.
### Title:
          MapSR: Prompt-Driven Land Cover Map Super-Resolution via Vision Foundation Models
 - **Authors:** Ruiqi Wang, Qi Yu, Jie Ma, Hanlin Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-resolution (HR) land-cover mapping is often constrained by the high cost of dense HR annotations. We revisit this problem from the perspective of map super-resolution, which enhances coarse low-resolution (LR) land-cover products into HR maps at the resolution of the input imagery. Existing weakly supervised methods can leverage LR labels, but they typically use them to retrain dense predictors with substantial computational cost. We propose MapSR, a prompt-driven framework that decouples supervision from model training. MapSR uses LR labels once to extract class prompts from frozen vision foundation model features through a lightweight linear probe, after which HR mapping proceeds via training-free metric inference and graph-based prediction refinement. Specifically, class prompts are estimated by aggregating high-confidence HR features identified by the linear probe, and HR predictions are obtained by cosine-similarity matching followed by graph-based propagation for spatial refinement. Experiments on the Chesapeake Bay dataset show that MapSR achieves 59.64% mIoU without any HR labels, remaining competitive with the strongest weakly supervised baseline and surpassing a fully supervised baseline. Notably, MapSR reduces trainable parameters by four orders of magnitude and shortens training time from hours to minutes, enabling scalable HR mapping under limited annotation and compute budgets. The code is available at this https URL.
### Title:
          A multi-platform LiDAR dataset for standardized forest inventory measurement at long term ecological monitoring sites
 - **Authors:** Michael R. Chang, Anna Candotti, Karl von Ellenrieder, Enrico Tomelleri, Marco Camurri
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a curated multi-platform LiDAR reference dataset from an instrumented ICOS forest plot, explicitly designed to support calibration, benchmarking, and integration of 3D structural data with ecological observations and standard allometric models. The dataset integrates UAV-borne laser scanning (ULS) to measure canopy coverage, terrestrial laser scanning (TLS) for detailed stem mapping, and backpack mobile laser scanning (MLS) with real-time SLAM for efficient sub-canopy acquisition. We focus on the control plot with the most complete and internally consistent registration, where TLS point clouds (~333 million points) are complemented by ULS and MLS data capturing canopy and understory strata. Marker-free, SLAM-aware protocols were used to reduce field and processing time, while manual and automated methods were combined. Final products are available in LAZ and E57 formats with UTM coordinates, together with registration reports for reproducibility. The dataset provides a benchmark for testing registration methods, evaluating scanning efficiency, and linking point clouds with segmentation, quantitative structure models, and allometric biomass estimation. By situating the acquisitions at a long-term ICOS site, it is explicitly linked to 3D structure with decades of ecological and flux measurements. More broadly, it illustrates how TLS, MLS, and ULS can be combined for repeated inventories and digital twins of forest ecosystems.
### Title:
          SPAGBias: Uncovering and Tracing Structured Spatial Gender Bias in Large Language Models
 - **Authors:** Binxian Su, Haoye Lou, Shucheng Zhu, Weikang Wang, Ying Liu, Dong Yu, Pengyuan Liu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) are being increasingly used in urban planning, but since gendered space theory highlights how gender hierarchies are embedded in spatial organization, there is concern that LLMs may reproduce or amplify such biases. We introduce SPAGBias - the first systematic framework to evaluate spatial gender bias in LLMs. It combines a taxonomy of 62 urban micro-spaces, a prompt library, and three diagnostic layers: explicit (forced-choice resampling), probabilistic (token-level asymmetry), and constructional (semantic and narrative role analysis). Testing six representative models, we identify structured gender-space associations that go beyond the public-private divide, forming nuanced micro-level mappings. Story generation reveals how emotion, wording, and social roles jointly shape "spatial gender narratives". We also examine how prompt design, temperature, and model scale influence bias expression. Tracing experiments indicate that these patterns are embedded and reinforced across the model pipeline (pre-training, instruction tuning, and reward modeling), with model associations found to substantially exceed real-world distributions. Downstream experiments further reveal that such biases produce concrete failures in both normative and descriptive application settings. This work connects sociological theory with computational analysis, extending bias research into the spatial domain and uncovering how LLMs encode social gender cognition through language.
### Title:
          Evaluating Encodings for Bivariate Edges in Adjacency Matrices
 - **Authors:** Jorge Acosta-Hernández, Alexander Lex, Tingying He
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present the first empirical evaluation of techniques for encoding distributions of quantitative edge values within adjacency matrices. In many real-world networks, edges represent not a single value but a set of measurements. While adjacency matrices preserve structural clarity, their compact cells limit the simultaneous display of multiple values. To address this, we explore edge encodings that represent distributions by two values: a measure of central tendency (mean, median, mode) and a measure of dispersion (standard deviation, variance, IQR). We select four possible encodings for evaluation that prior work has suggested are suitable for the limited space available in matrices: a bivariate color palette, embedded bar charts, and two overlaid-mark designs mapping the primary attribute to color and the secondary attribute to area or angle. In a preregistered crowdsourced study with 156 participants, we assessed performance of these encodings across eight analytical tasks and collected readability and aesthetic ratings. Results reveal clear performance regimes: area-based overlaid marks and bar charts achieved the highest overall performance; angle-based marks show moderate but less stable performance,and bivariate color consistently underperforms these alternatives. These findings clarify how visual channels behave under strict constraints and delineate the strengths and limitations of key design choices for multivariate edge visualization.
### Title:
          Keep It CALM: Toward Calibration-Free Kilometer-Level SLAM with Visual Geometry Foundation Models via an Assistant Eye
 - **Authors:** Tianjun Zhang, Fengyi Zhang, Tianchen Deng, Lin Zhang, Hesheng Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual Geometry Foundation Models (VGFMs) demonstrate remarkable zero-shot capabilities in local reconstruction. However, deploying them for kilometer-level Simultaneous Localization and Mapping (SLAM) remains challenging. In such scenarios, current approaches mainly rely on linear transforms (e.g., Sim3 and SL4) for sub-map alignment, while we argue that a single linear transform is fundamentally insufficient to model the complex, non-linear geometric distortions inherent in VGFM outputs. Forcing such rigid alignment leads to the rapid accumulation of uncorrected residuals, eventually resulting in significant trajectory drift and map divergence. To address these limitations, we present CAL2M (Calibration-free Assistant-eye based Large-scale Localization and Mapping), a plug-and-play framework compatible with arbitrary VGFMs. Distinct from traditional systems, CAL2M introduces an "assistant eye" solely to leverage the prior of constant physical spacing, effectively eliminating scale ambiguity without any temporal or spatial pre-calibration. Furthermore, leveraging the assumption of accurate feature matching, we propose an epipolar-guided intrinsic and pose correction model. Supported by an online intrinsic search module, it can effectively rectify rotation and translation errors caused by inaccurate intrinsics through fundamental matrix decomposition. Finally, to ensure accurate mapping, we introduce a globally consistent mapping strategy based on anchor propagation. By constructing and fusing anchors across the trajectory, we establish a direct local-to-global mapping relationship. This enables the application of nonlinear transformations to elastically align sub-maps, effectively eliminating geometric misalignments and ensuring a globally consistent reconstruction. The source code of CAL2M will be publicly available at this https URL.
### Title:
          Beyond Literal Summarization: Redefining Hallucination for Medical SOAP Note Evaluation
 - **Authors:** Bhavik Vachhani, Kush Shrisvastava, Pranshu Nema, Sai Chiranthan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Evaluating large language models (LLMs) for clinical documentation tasks such as SOAP note generation remains challenging. Unlike standard summarization, these tasks require clinical abstraction, normalization of colloquial language, and medically grounded inference. However, prevailing evaluation methods including automated metrics and LLM as judge frameworks rely on lexical faithfulness, often labeling any information not explicitly present in the transcript as hallucination. We show that such approaches systematically misclassify clinically valid outputs as errors, inflating hallucination rates and distorting model assessment. Our analysis reveals that many flagged hallucinations correspond to legitimate clinical transformations, including synonym mapping, abstraction of examination findings, diagnostic inference, and guideline consistent care planning. By aligning evaluation criteria with clinical reasoning through calibrated prompting and retrieval grounded in medical ontologies we observe a significant shift in outcomes. Under a lexical evaluation regime, the mean hallucination rate is 35%, heavily penalizing valid reasoning. With inference aware evaluation, this drops to 9%, with remaining cases reflecting genuine safety concerns. These findings suggest that current evaluation practices over penalize valid clinical reasoning and may measure artifacts of evaluation design rather than true errors, underscoring the need for clinically informed evaluation in high context domains like medicine.
### Title:
          Improved Multiscale Structural Mapping with Supervertex Vision Transformer for the Detection of Alzheimer's Disease Neurodegeneration
 - **Authors:** Geonwoo Baek, David H. Salat, Ikbeom Jang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Alzheimer's disease (AD) confirmation often relies on positron emission tomography (PET) or cerebrospinal fluid (CSF) analysis, which are costly and invasive. Consequently, structural MRI biomarkers such as cortical thickness (CT) are widely used for non-invasive AD screening. Multiscale structural mapping (MSSM) was recently proposed to integrate gray-white matter contrasts (GWCs) with CT from a single T1-weighted MRI (T1w) scan. Building on this framework, we propose MSSM+, together with surface supervertex mapping (SSVM) and a Supervertex Vision Transformer (SV-ViT). 3D T1w images from individuals with AD and cognitively normal (CN) controls were analyzed. MSSM+ extends MSSM by incorporating sulcal depth and cortical curvature at the vertex level. SSVM partitions the cortical surface into supervertices (surface patches) that effectively represent inter- and intra-regional spatial relationships. SV-ViT is a Vision Transformer architecture operating on these supervertices, enabling anatomically informed learning from surface mesh representations. Compared with MSSM, MSSM+ identified more spatially extensive and statistically significant group differences between AD and CN. In AD vs. CN classification, MSSM+ achieved a 3%p higher area under the precision-recall curve than MSSM. Vendor-specific analyses further demonstrated reduced signal variability and consistently improved classification performance across MR manufacturers relative to CT, GWCs, and MSSM. These findings suggest that MSSM+ combined with SV-ViT is a promising MRI-based imaging marker for AD detection prior to CSF/PET confirmation.
### Title:
          RaTA-Tool: Retrieval-based Tool Selection with Multimodal Large Language Models
 - **Authors:** Gabriele Mattioli, Evelyn Turri, Sara Sarto, Lorenzo Baraldi, Marcella Cornia, Lorenzo Baraldi, Rita Cucchiara
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tool learning with foundation models aims to endow AI systems with the ability to invoke external resources -- such as APIs, computational utilities, and specialized models -- to solve complex tasks beyond the reach of standalone language generation. While recent advances in Large Language Models (LLMs) and Multimodal Large Language Models (MLLMs) have expanded their reasoning and perception capabilities, existing tool-use methods are predominantly limited to text-only inputs and closed-world settings. Consequently, they struggle to interpret multimodal user instructions and cannot generalize to tools unseen during training. In this work, we introduce RaTA-Tool, a novel framework for open-world multimodal tool selection. Rather than learning direct mappings from user queries to fixed tool identifiers, our approach enables an MLLM to convert a multimodal query into a structured task description and subsequently retrieve the most appropriate tool by matching this representation against semantically rich, machine-readable tool descriptions. This retrieval-based formulation naturally supports extensibility to new tools without retraining. To further improve alignment between task descriptions and tool selection, we incorporate a preference-based optimization stage using Direct Preference Optimization (DPO). To support research in this setting, we also introduce the first dataset for open-world multimodal tool use, featuring standardized tool descriptions derived from Hugging Face model cards. Extensive experiments demonstrate that our approach significantly improves tool-selection performance, particularly in open-world, multimodal scenarios.
### Title:
          Efficient calculation of available space for multi-NUMA virtual machines
 - **Authors:** Andrei Gudkov, Elizaveta Ponomareva, Alexis Pospelov
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Data Structures and Algorithms (cs.DS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Increasing demand for computational power has led cloud providers to employ multi-NUMA servers and offer multi-NUMA virtual machines to their customers. However, multi-NUMA VMs introduce additional complexity to scheduling algorithms. Beyond merely selecting a host for a VM, the scheduler has to map virtual NUMA topology onto the physical NUMA topology of the server to ensure optimal VM performance and minimize interference with co-located VMs. Under these constraints, maximizing the number of allocated multi-NUMA VMs on a host becomes a combinatorial optimization problem. In this paper, we derive closed-form expressions to compute the maximum number of VMs for a given flavor that can be additionally allocated onto a physical server. We consider nontrivial scenarios of mapping 2- and 4-NUMA symmetric VMs to 4- and 8-NUMA physical topologies. Our results have broad applicability, ranging from real-time dashboards (displaying available cluster capacity per VM flavor) to optimization tools for large-scale cloud resource reorganization.
### Title:
          Autonomous Evolution of EDA Tools: Multi-Agent Self-Evolved ABC
 - **Authors:** Cunxi Yu, Haoxing Ren
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces the first \emph{self-evolving} logic synthesis framework, which leverages Large Language Model (LLM) agents to autonomously improve the source code of \textsc{ABC}, the widely adopted logic synthesis system. Our framework operates on the \emph{entire integrated ABC codebase}, and the output repository preserves its single-binary execution model and command interface. In the initial evolution cycle, we bootstrap the system using existing prior open-source synthesis components, covering flow tuning, logic minimization, and technology mapping, but without manually injecting new heuristics. On top of this foundation, a team of LLM-based agents iteratively rewrites and evolves specific sub-components of ABC following our ``programming guidance`` prompts under a unified correctness and QoR-driven evaluation loop. Each evolution cycle proposes code modifications, compiles the integrated binary, validates correctness, and evaluates quality-of-results (QoR) on \emph{multi-suite benchmarks including ISCAS~85/89/99, VTR, EPFL, and IWLS~2005}. Through continuous feedback, the system discovers optimizations beyond human-designed heuristics, effectively \emph{learning new synthesis strategies} that enhance QoR. We detail the architecture of this self-improving system, its integration with \textsc{ABC}, and results demonstrating that the framework can autonomously and progressively improve EDA tool at full million-line scale.
### Title:
          Assessing the Potential of Masked Autoencoder Foundation Models in Predicting Downhole Metrics from Surface Drilling Data
 - **Authors:** Aleksander Berezowski, Hassan Hassanzadeh, Gouri Ginde
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Oil and gas drilling operations generate extensive time-series data from surface sensors, yet accurate real-time prediction of critical downhole metrics remains challenging due to the scarcity of labelled downhole measurements. This systematic mapping study reviews thirteen papers published between 2015 and 2025 to assess the potential of Masked Autoencoder Foundation Models (MAEFMs) for predicting downhole metrics from surface drilling data. The review identifies eight commonly collected surface metrics and seven target downhole metrics. Current approaches predominantly employ neural network architectures such as artificial neural networks (ANNs) and long short-term memory (LSTM) networks, yet no studies have explored MAEFMs despite their demonstrated effectiveness in time-series modeling. MAEFMs offer distinct advantages through self-supervised pre-training on abundant unlabeled data, enabling multi-task prediction and improved generalization across wells. This research establishes that MAEFMs represent a technically feasible but unexplored opportunity for drilling analytics, recommending future empirical validation of their performance against existing models and exploration of their broader applicability in oil and gas operations.
## Keyword: localization
### Title:
          RoSLAC: Robust Simultaneous Localization and Calibration of Multiple Magnetometers
 - **Authors:** Qiyang Lyu, Zhenyu Wu, Wei Wang, Hongming Shen, Danwei Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Localization of autonomous mobile robots (AMRs) in enclosed or semi-enclosed environments such as offices, hotels, hospitals, indoor parking facilities, and underground spaces where GPS signals are weak or unavailable remains a major obstacle to the deployment of fully autonomous systems. Infrastructure-based localization approaches, such as QR codes and RFID, are constrained by high installation and maintenance costs as well as limited flexibility, while onboard sensor-based methods, including LiDAR- and vision-based solutions, are affected by ambiguous geometric features and frequent occlusions caused by dynamic obstacles such as pedestrians. Ambient magnetic field (AMF)-based localization has therefore attracted growing interest in recent years because it does not rely on external infrastructure or geometric features, making it well-suited for AMR applications such as service robots and security robots. However, magnetometer measurements are often corrupted by distortions caused by ferromagnetic materials present on the sensor platform, which bias the AMF and degrade localization reliability. As a result, accurate magnetometer calibration to estimate distortion parameters becomes essential. Conventional calibration methods that rely on rotating the magnetometer are impractical for large and heavy platforms. To address this limitation, this paper proposes a robust simultaneous localization and calibration (RoSLAC) approach based on alternating optimization, which iteratively and efficiently estimates both the platform pose and magnetometer calibration parameters. Extensive evaluations conducted in high-fidelity simulation and real-world environments demonstrate that the proposed RoSLAC method achieves high localization accuracy while maintaining low computational cost compared with state-of-the-art magnetometer calibration techniques.
### Title:
          CooperDrive: Enhancing Driving Decisions Through Cooperative Perception
 - **Authors:** Deyuan Qu, Qi Chen, Takayuki Shimizu, Onur Altintas
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles equipped with robust onboard perception, localization, and planning still face limitations in occlusion and non-line-of-sight (NLOS) scenarios, where delayed reactions can increase collision risk. We propose CooperDrive, a cooperative perception framework that augments situational awareness and enables earlier, safer driving decisions. CooperDrive offers two key advantages: (i) each vehicle retains its native perception, localization, and planning stack, and (ii) a lightweight object-level sharing and fusion strategy bridges perception and planning. Specifically, CooperDrive reuses detector Bird's-Eye View (BEV) features to estimate accurate vehicle poses without additional heavy encoders, thereby reconstructing BEV representations and feeding the planner with low latency. On the planning side, CooperDrive leverages the expanded object set to anticipate potential conflicts earlier and adjust speed and trajectory proactively, thereby transforming reactive behaviors into predictive and safer driving decisions. Real-world closed-loop tests at occlusion-heavy NLOS intersections demonstrate that CooperDrive increases reaction lead time, minimum time-to-collision (TTC), and stopping margin, while requiring only 90 kbps bandwidth and maintaining an average end-to-end latency of 89 ms.
### Title:
          CT-VIR: Continuous-Time Visual-Inertial-Ranging Fusion for Indoor Localization with Sparse Anchors
 - **Authors:** Yu-An Liu, Li Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual-inertial odometry (VIO) is widely used for mobile robot localization, but its long-term accuracy degrades without global constraints. Incorporating ranging sensors such as ultra-wideband (UWB) can mitigate drift; however, high-accuracy ranging usually requires well-deployed anchors, which is difficult to ensure in narrow or low-power environments. Moreover, most existing visual-inertial-ranging (VIR) fusion methods rely on discrete time-based filtering or optimization, making it difficult to balance positioning accuracy, trajectory consistency, and fusion efficiency under asynchronous multi-sensor sampling. To address these issues, we propose a spline-based continuous-time state estimation method for VIR fusion localization. In the preprocessing stage, VIO motion priors and UWB ranging measurements are used to construct virtual anchors and reject outliers, thereby alleviating geometric degeneration and improving range reliability. In the estimation stage, the pose trajectory is parameterized in continuous time using a B-spline, while inertial, visual, and ranging constraints are formulated as factors in a sliding-window graph. The spline control points, together with a small set of auxiliary parameters, are then jointly optimized to obtain a continuous-time trajectory estimate. Evaluations on public datasets and real-world experiments demonstrate the effectiveness and practical potential of the proposed approach.
### Title:
          AIPC: Agent-Based Automation for AI Model Deployment with Qualcomm AI Runtime
 - **Authors:** Jianhao Su, Zhanwei Wu, ShengTing Huang, Weidong Feng
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Edge AI model deployment is a multi-stage engineering process involving model conversion, operator compatibility handling, quantization calibration, runtime integration, and accuracy validation. In practice, this workflow is long, failure-prone, and heavily dependent on deployment expertise, particularly when targeting hardware-specific inference runtimes. This technical report presents AIPC (AI Porting Conversion), an AI agent-driven approach for constrained automation of AI model deployment. AIPC decomposes deployment into standardized, verifiable stages and injects deployment-domain knowledge into agent execution through Agent Skills, helper scripts, and a stage-wise validation loop. This design reduces both the expertise barrier and the engineering time required for hardware deployment. Using Qualcomm AI Runtime (QAIRT) as the primary scenario, this report examines automated deployment across representative vision, multimodal, and speech models. In the cases covered here, AIPC can complete deployment from PyTorch to runnable QNN/SNPE inference within 7-20 minutes for structurally regular vision models, with indicative API costs roughly in the range of USD 0.7-10. For more complex models involving less-supported operators, dynamic shapes, or autoregressive decoding structures, fully automated deployment may still require further advances, but AIPC already provides practical support for execution, failure localization, and bounded repair.
### Title:
          The Courtroom Trial of Pixels: Robust Image Manipulation Localization via Adversarial Evidence and Reinforcement Learning Judgment
 - **Authors:** Songlin Li, Zhiqing Guo, Dan Ma, Changtao Miao, Gaobo Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Although some existing image manipulation localization (IML) methods incorporate authenticity-related supervision, this information is typically utilized merely as an auxiliary training signal to enhance the model's sensitivity to manipulation artifacts, rather than being explicitly modeled as localization evidence opposing the manipulated regions. Consequently, when manipulation traces are subtle or degraded by post-processing and noise, these methods struggle to explicitly compare manipulated and authentic evidence, resulting in unreliable predictions in ambiguous areas. To address these issues, we propose a courtroom-style adjudication framework that regards IML task as the confrontation of evidence followed by judgment. The framework comprises a prosecution stream, a defense stream, and a judge model. We first build a dual-hypothesis segmentation architecture on a shared multi-scale encoder, in which the prosecution stream asserts manipulation and the defense stream asserts authenticity. Guided by edge priors, it produces evidence for manipulated and authentic regions through cascaded multi-level fusion, bidirectional disagreement suppression, and dynamic debate refinement. We further develop a reinforcement learning judge model that performs strategic re-inference and refinement on uncertain regions, yielding a manipulated-region mask. The judge model is trained with advantage-based rewards and a soft-IoU objective, and reliability is calibrated via entropy and cross-hypothesis consistency. Experimental results show that our model achieves superior average performance compared with SOTA IML methods.
### Title:
          HWE-Bench: Benchmarking LLM Agents on Real-World Hardware Bug Repair Tasks
 - **Authors:** Fan Cui, Hongyuan Hou, Zizhang Luo, Chenyun Yin, Yun Liang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing benchmarks for hardware design primarily evaluate Large Language Models (LLMs) on isolated, component-level tasks such as generating HDL modules from specifications, leaving repository-scale evaluation unaddressed. We introduce HWE-Bench, the first large-scale, repository-level benchmark for evaluating LLM agents on real-world hardware bug repair tasks. HWE-Bench comprises 417 task instances derived from real historical bug-fix pull requests across six major open-source projects spanning both Verilog/SystemVerilog and Chisel, covering RISC-V cores, SoCs, and security roots-of-trust. Each task is grounded in a fully containerized environment where the agent must resolve a real bug report, with correctness validated through the project's native simulation and regression flows. The benchmark is built through a largely automated pipeline that enables efficient expansion to new repositories. We evaluate seven LLMs with four agent frameworks and find that the best agent resolves 70.7% of tasks overall, with performance exceeding 90% on smaller cores but dropping below 65% on complex SoC-level projects. We observe larger performance gaps across models than commonly reported on software benchmarks, and difficulty is driven by project scope and bug-type distribution rather than code size alone. Our failure analysis traces agent failures to three stages of the debugging process: fault localization, hardware-semantic reasoning, and cross-artifact coordination across RTL, configuration, and verification components, providing concrete directions for developing more capable hardware-aware agents.
### Title:
          ASGNet: Adaptive Spectrum Guidance Network for Automatic Polyp Segmentation
 - **Authors:** Yanguang Sun, Hengmin Zhang, Jianjun Qian, Jian Yang, Lei Luo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Early identification and removal of polyps can reduce the risk of developing colorectal cancer. However, the diverse morphologies, complex backgrounds and often concealed nature of polyps make polyp segmentation in colonoscopy images highly challenging. Despite the promising performance of existing deep learning-based polyp segmentation methods, their perceptual capabilities remain biased toward local regions, mainly because of the strong spatial correlations between neighboring pixels in the spatial domain. This limitation makes it difficult to capture the complete polyp structures, ultimately leading to sub-optimal segmentation results. In this paper, we propose a novel adaptive spectrum guidance network, called ASGNet, which addresses the limitations of spatial perception by integrating spectral features with global attributes. Specifically, we first design a spectrum-guided non-local perception module that jointly aggregates local and global information, therefore enhancing the discriminability of polyp structures, and refining their boundaries. Moreover, we introduce a multi-source semantic extractor that integrates rich high-level semantic information to assist in the preliminary localization of polyps. Furthermore, we construct a dense cross-layer interaction decoder that effectively integrates diverse information from different layers and strengthens it to generate high-quality representations for accurate polyp segmentation. Extensive quantitative and qualitative results demonstrate the superiority of our ASGNet approach over 21 state-of-the-art methods across five widely-used polyp segmentation benchmarks. The code will be publicly available at: this https URL.
### Title:
          Keep It CALM: Toward Calibration-Free Kilometer-Level SLAM with Visual Geometry Foundation Models via an Assistant Eye
 - **Authors:** Tianjun Zhang, Fengyi Zhang, Tianchen Deng, Lin Zhang, Hesheng Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual Geometry Foundation Models (VGFMs) demonstrate remarkable zero-shot capabilities in local reconstruction. However, deploying them for kilometer-level Simultaneous Localization and Mapping (SLAM) remains challenging. In such scenarios, current approaches mainly rely on linear transforms (e.g., Sim3 and SL4) for sub-map alignment, while we argue that a single linear transform is fundamentally insufficient to model the complex, non-linear geometric distortions inherent in VGFM outputs. Forcing such rigid alignment leads to the rapid accumulation of uncorrected residuals, eventually resulting in significant trajectory drift and map divergence. To address these limitations, we present CAL2M (Calibration-free Assistant-eye based Large-scale Localization and Mapping), a plug-and-play framework compatible with arbitrary VGFMs. Distinct from traditional systems, CAL2M introduces an "assistant eye" solely to leverage the prior of constant physical spacing, effectively eliminating scale ambiguity without any temporal or spatial pre-calibration. Furthermore, leveraging the assumption of accurate feature matching, we propose an epipolar-guided intrinsic and pose correction model. Supported by an online intrinsic search module, it can effectively rectify rotation and translation errors caused by inaccurate intrinsics through fundamental matrix decomposition. Finally, to ensure accurate mapping, we introduce a globally consistent mapping strategy based on anchor propagation. By constructing and fusing anchors across the trajectory, we establish a direct local-to-global mapping relationship. This enables the application of nonlinear transformations to elastically align sub-maps, effectively eliminating geometric misalignments and ensuring a globally consistent reconstruction. The source code of CAL2M will be publicly available at this https URL.
### Title:
          Graph Theoretical Outlier Rejection for 4D Radar Registration in Feature-Poor Environments
 - **Authors:** Georg Dorndorf, Daniel Adolfsson, Masrur Doostdar
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automotive 4D imaging radar is well suited for operation in dusty and low-visibility environments, but scan registration remains challenging due to scan sparsity and spurious detections caused by noise and multipath reflections. This difficulty is compounded in feature-poor open-pit mines, where the lack of distinctive landmarks reduces correspondence reliability. We integrate graph-based pairwise consistency maximization (PCM) as an outlier rejection step within the iterative closest points (ICP) loop. We propose a radar-adapted pairwise distance-invariant scoring function for graph-based (PCM) that incorporates anisotropic, per-detection uncertainty derived from a radar measurement model. The consistency maximization problem is approximated with a greedy heuristic that finds a large clique in the pairwise consistency graph. The refined correspondence set improves robustness when the initial association set is heavily contaminated. We evaluate a standard Euclidean distance residual and our uncertainty-aware residual on an open-pit mine dataset collected with a 4D imaging radar. Compared to the generalized ICP (GICP) baseline without PCM, our method reduces segment relative position error (RPE) by 29.6% on 1 m segments and by up to 55% on 100 m segments. The presented method is intended for integration into localization pipelines and is suitable for online use due to the greedy heuristic in graph-based (PCM).
### Title:
          POMDP-based Object Search with Growing State Space and Hybrid Action Domain
 - **Authors:** Yongbo Chen, Hesheng Wang, Shoudong Huang, Hanna Kurniawati
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficiently locating target objects in complex indoor environments with diverse furniture, such as shelves, tables, and beds, is a significant challenge for mobile robots. This difficulty arises from factors like localization errors, limited fields of view, and visual occlusion. We address this by framing the object-search task as a highdimensional Partially Observable Markov Decision Process (POMDP) with a growing state space and hybrid (continuous and discrete) action spaces in 3D environments. Based on a meticulously designed perception module, a novel online POMDP solver named the growing neural process filtered k-center clustering tree (GNPF-kCT) is proposed to tackle this problem. Optimal actions are selected using Monte Carlo Tree Search (MCTS) with belief tree reuse for growing state space, a neural process network to filter useless primitive actions, and k-center clustering hypersphere discretization for efficient refinement of high-dimensional action spaces. A modified upper-confidence bound (UCB), informed by belief differences and action value functions within cells of estimated diameters, guides MCTS expansion. Theoretical analysis validates the convergence and performance potential of our method. To address scenarios with limited information or rewards, we also introduce a guessed target object with a grid-world model as a key strategy to enhance search efficiency. Extensive Gazebo simulations with Fetch and Stretch robots demonstrate faster and more reliable target localization than POMDP-based baselines and state-of-the-art (SOTA) non-POMDP-based solvers, especially large language model (LLM) based methods, in object search under the same computational constraints and perception systems. Real-world tests in office environments confirm the practical applicability of our approach. Project page: this https URL.
### Title:
          Flow of Truth: Proactive Temporal Forensics for Image-to-Video Generation
 - **Authors:** Yuzhuo Chen, Zehua Ma, Han Fang, Hengyi Wang, Guanjie Wang, Weiming Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid rise of image-to-video (I2V) generation enables realistic videos to be created from a single image but also brings new forensic demands. Unlike static images, I2V content evolves over time, requiring forensics to move beyond 2D pixel-level tampering localization toward tracing how pixels flow and transform throughout the video. As frames progress, embedded traces drift and deform, making traditional spatial forensics ineffective. To address this unexplored dimension, we present **Flow of Truth**, the first proactive framework focusing on temporal forensics in I2V generation. A key challenge lies in discovering a forensic signature that can evolve consistently with the generation process, which is inherently a creative transformation rather than a deterministic reconstruction. Despite this intrinsic difficulty, we innovatively redefine video generation as *the motion of pixels through time rather than the synthesis of frames*. Building on this view, we propose a learnable forensic template that follows pixel motion and a template-guided flow module that decouples motion from image content, enabling robust temporal tracing. Experiments show that Flow of Truth generalizes across commercial and open-source I2V models, substantially improving temporal forensics performance.
### Title:
          Source Distance Estimation in Turbulent Airflow: Exploiting Molecule Degradation Diversity
 - **Authors:** Bastian Heinlein, Timo Jakumeit, Robert Schober, Maximilian Schäfer, Vahid Jamali
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In nature, estimating the location of a molecule source in turbulent airflow is a central, and yet highly challenging problem for mate search and foraging. Recently, it has also received increasing attention in synthetic molecular communication (SMC), e.g., for leakage detection. One important aspect of source localization is to estimate the distance to the molecule source, e.g., to determine whether it is worth to travel to a potential mating partner or food source, or to decide whether a leak is close enough for inspection. In this study, based on realistic simulations, we show that the diversity induced by molecule mixtures can aid source localization. In particular, when different molecule types in a mixture are subject to atmospheric degradation with different degradation rates, the relative abundance of the different species observed at the receiver enables low-complexity estimation of the source distance. Furthermore, this feature can be combined with already established concentration-based and temporal features of observed molecular signals to further increase estimation accuracy. Thereby, we show that molecule degradation diversity of molecule mixtures can help to realize one of the important envisioned SMC applications, namely source localization, even in turbulent airflow, opening new opportunities for the exploitation of SMC to solve real-world problems.
### Title:
          Dual Pose-Graph Semantic Localization for Vision-Based Autonomous Drone Racing
 - **Authors:** David Perez-Saura, Miguel Fernandez-Cortizas, Alvaro J. Gaona, Pascual Campoy
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous drone racing demands robust real-time localization under extreme conditions: high-speed flight, aggressive maneuvers, and payload-constrained platforms that often rely on a single camera for perception. Existing visual SLAM systems, while effective in general scenarios, struggle with motion blur and feature instability inherent to racing dynamics, and do not exploit the structured nature of racing environments. In this work, we present a dual pose-graph architecture that fuses odometry with semantic detections for robust localization. A temporary graph accumulates multiple gate observations between keyframes and optimizes them into a single refined constraint per landmark, which is then promoted to a persistent main graph. This design preserves the information richness of frequent detections while preventing graph growth from degrading real-time performance. The system is designed to be sensor-agnostic, although in this work we validate it using monocular visual-inertial odometry and visual gate detections. Experimental evaluation on the TII-RATM dataset shows a 56% to 74% reduction in ATE compared to standalone VIO, while an ablation study confirms that the dual-graph architecture achieves 10% to 12% higher accuracy than a single-graph baseline at identical computational cost. Deployment in the A2RL competition demonstrated that the system performs real-time onboard localization during flight, reducing the drift of the odometry baseline by up to 4.2 m per lap.
### Title:
          AD4AD: Benchmarking Visual Anomaly Detection Models for Safer Autonomous Driving
 - **Authors:** Fabrizio Genilotti, Arianna Stropeni, Gionata Grotto, Francesco Borsatti, Manuel Barusco, Davide Dalle Pezze, Gian Antonio Susto
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The reliability of a machine vision system for autonomous driving depends heavily on its training data distribution. When a vehicle encounters significantly different conditions, such as atypical obstacles, its perceptual capabilities can degrade substantially. Unlike many domains where errors carry limited consequences, failures in autonomous driving translate directly into physical risk for passengers, pedestrians, and other road users. To address this challenge, we explore Visual Anomaly Detection (VAD) as a solution. VAD enables the identification of anomalous objects not present during training, allowing the system to alert the driver when an unfamiliar situation is detected. Crucially, VAD models produce pixel-level anomaly maps that can guide driver attention to specific regions of concern without requiring any prior assumptions about the nature or form of the hazard. We benchmark eight state-of-the-art VAD methods on AnoVox, the largest synthetic dataset for anomaly detection in autonomous driving. In particular, we evaluate performance across four backbone architectures spanning from large networks to lightweight ones such as MobileNet and DeiT-Tiny. Our results demonstrate that VAD transfers effectively to road scenes. Notably, Tiny-Dinomaly achieves the best accuracy-efficiency trade-off for edge deployment, matching full-scale localization performance at a fraction of the memory cost. This study represents a concrete step toward safer, more responsible deployment of autonomous vehicles, ultimately improving protection for passengers, pedestrians, and all road users.
## Keyword: transformer
### Title:
          Correcting Suppressed Log-Probabilities in Language Models with Post-Transformer Adapters
 - **Authors:** Bryan Sanchez
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Alignment-tuned language models frequently suppress factual log-probabilities on politically sensitive topics despite retaining the knowledge in their hidden representations. We show that a 786K-parameter (approximately 0.02% of the base model) post-transformer adapter, trained on frozen hidden states, corrects this suppression on 31 ideology-discriminating facts across Qwen3-4B, 8B, and 14B. The adapter memorizes all 15 training facts and generalizes to 11--39% of 16 held-out facts across 5 random splits per scale, with zero knowledge regressions via anchored training. Both gated (SwiGLU) and ungated (linear bottleneck) adapters achieve comparable results; neither consistently outperforms the other (Fisher exact p > 0.09 at all scales). On instruct models, the adapter corrects log-probability rankings. When applied at all token positions during generation, the adapter produces incoherent output; however, when applied only at the current prediction position (last-position-only), the adapter produces coherent, less censored text. A logit-space adapter operating after token projection fails to produce coherent generation at any application mode, suggesting hidden-state intervention is the correct level for generation correction. A previously undocumented silent gradient bug in Apple MLX explains all null results in earlier iterations of this work: the standard pattern nn.value_and_grad(model, fn)(this http URL()) returns zero gradients without error; the correct pattern nn.value_and_grad(model, fn)(model, data) resolves this. We provide a minimal reproduction and discuss implications for other adapter research using MLX.
### Title:
          Internal Knowledge Without External Expression: Probing the Generalization Boundary of a Classical Chinese Language Model
 - **Authors:** Jiuting Chen, Yuan Lian, Hao Wu, Tianqi Huang, Hiroshi Sasaki, Makoto Kouno, Jongil Choi
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We train a 318M-parameter Transformer language model from scratch on a curated corpus of 1.56 billion tokens of pure Classical Chinese, with zero English characters or Arabic numerals. Through systematic out-of-distribution (OOD) testing, we investigate whether the model can distinguish known from unknown inputs, and crucially, whether it can express this distinction in its generated text. We find a clear dissociation between internal and external uncertainty. Internally, the model exhibits a perplexity jump ratio of 2.39x between real and fabricated historical events (p = 8.9e-11, n = 92 per group), with semi-fabricated events (real figures + fictional events) showing the highest perplexity (4.24x, p = 1.1e-16), demonstrating genuine factual encoding beyond syntactic pattern matching. Externally, however, the model never learns to express uncertainty: classical Chinese epistemic markers appear at lower rates for OOD questions (3.5%) than for in-distribution questions (8.3%, p = 0.023), reflecting rhetorical conventions rather than genuine metacognition. We replicate both findings across three languages (Classical Chinese, English, Japanese), three writing systems, and eight models from 110M to 1.56B parameters. We further show that uncertainty expression frequency is determined entirely by training data conventions, with Classical Chinese models showing a "humility paradox" (more hedging for known topics), while Japanese models almost never hedge. We argue that metacognitive expression -- the ability to say "I don't know" -- does not emerge from language modeling alone and requires explicit training signals such as RLHF.
### Title:
          Attention to Mamba: A Recipe for Cross-Architecture Distillation
 - **Authors:** Abhinav Moudgil, Ningyuan Huang, Eeshan Gunesh Dhekane, Pau Rodríguez, Luca Zappella, Federico Danieli
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State Space Models (SSMs) such as Mamba have become a popular alternative to Transformer models, due to their reduced memory consumption and higher throughput at generation compared to their Attention-based counterparts. On the other hand, the community has built up a considerable body of knowledge on how to train Transformers, and many pretrained Transformer models are readily available. To facilitate the adoption of SSMs while leveraging existing pretrained Transformers, we aim to identify an effective recipe to distill an Attention-based model into a Mamba-like architecture. In prior work on cross-architecture distillation, however, it has been shown that a naïve distillation procedure from Transformers to Mamba fails to preserve the original teacher performance, a limitation often overcome with hybrid solutions combining Attention and SSM blocks. The key argument from our work is that, by equipping Mamba with a principled initialization, we can recover an overall better recipe for cross-architectural distillation. To this end, we propose a principled two-stage approach: first, we distill knowledge from a traditional Transformer into a linearized version of Attention, using an adaptation of the kernel trick. Then, we distill the linearized version into an adapted Mamba model that does not use any Attention block. Overall, the distilled Mamba model is able to preserve the original Pythia-1B Transformer performance in downstream tasks, maintaining a perplexity of 14.11 close to the teacher's 13.86. To show the efficacy of our recipe, we conduct thorough ablations at 1B scale with 10B tokens varying sequence mixer architecture, scaling analysis on model sizes and total distillation tokens, and a sensitivity analysis on tokens allocation between stages.
### Title:
          Shapley Value-Guided Adaptive Ensemble Learning for Explainable Financial Fraud Detection with U.S. Regulatory Compliance Validation
 - **Authors:** Mohammad Nasir Uddin, Md Munna Aziz
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Financial crime costs U.S. institutions over $32 billion each year. Although AI tools for fraud detection have become more advanced, their use in real-world systems still faces a major obstacle: many of these models operate as black boxes that cannot provide the transparent, auditable explanations required by regulations such as OCC Bulletin 2011-12 and Federal Reserve SR 11-7. This study makes three main contributions. First, it offers a thorough evaluation of explanation quality across faithfulness (sufficiency and comprehensiveness at k=5, 10, and 15) and stability (Kendall's W across 30 bootstrap samples). XGBoost paired with TreeExplainer achieves near-perfect stability (W=0.9912), while LSTM with DeepExplainer shows weak results (W=0.4962). Second, the paper introduces the SHAP-Guided Adaptive Ensemble (SGAE), which dynamically adjusts per-transaction ensemble weights based on SHAP attribution agreement, achieving the highest AUC-ROC among all tested models (0.8837 held-out; 0.9245 cross-validation). Third, a complete three-architecture evaluation of LSTM, Transformer, and GNN-GraphSAGE on the full 590,540-transaction IEEE-CIS dataset is provided, with GNN-GraphSAGE achieving AUC-ROC 0.9248 and F1=0.6013. All results are mapped directly to OCC, SR 11-7, and BSA-AML regulatory compliance requirements.
### Title:
          Geometrically Consistent Multi-View Scene Generation from Freehand Sketches
 - **Authors:** Ahmed Bourouis, Savas Ozkan, Andrea Maracani, Yi-Zhe Song, Mete Ozay
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We tackle a new problem: generating geometrically consistent multi-view scenes from a single freehand sketch. Freehand sketches are the most geometrically impoverished input one could offer a multi-view generator. They convey scene intent through abstract strokes while introducing spatial distortions that actively conflict with any consistent 3D interpretation. No prior method attempts this; existing multi-view approaches require photographs or text, while sketch-to-3D methods need multiple views or costly per-scene optimisation. We address three compounding challenges; absent training data, the need for geometric reasoning from distorted 2D input, and cross-view consistency, through three mutually reinforcing contributions: (i) a curated dataset of $\sim$9k sketch-to-multiview samples, constructed via an automated generation and filtering pipeline; (ii) Parallel Camera-Aware Attention Adapters (CA3) that inject geometric inductive biases into the video transformer; and (iii) a Sparse Correspondence Supervision Loss (CSL) derived from Structure-from-Motion reconstructions. Our framework synthesizes all views in a single denoising process without requiring reference images, iterative refinement, or per-scene optimization. Our approach significantly outperforms state-of-the-art two-stage baselines, improving realism (FID) by over 60% and geometric consistency (Corr-Acc) by 23%, while providing up to a 3.7$\times$ inference speedup.
### Title:
          Three-Phase Transformer
 - **Authors:** Mohammad R. Abu Ayyash
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Three-Phase Transformer (3PT), a residual-stream structural prior for decoder-only Transformers on a standard SwiGLU + RMSNorm + RoPE + GQA backbone. The hidden vector is partitioned into N equally-sized cyclic channels, each maintained by phase-respecting ops: a per-channel RMSNorm, a 2D Givens rotation between attention and FFN that rotates each channel by theta + i*(2*pi/N), and a head-count constraint aligning GQA heads with the partition. The architecture is a self-stabilizing equilibrium between scrambling and re-imposition, not a bolted-on module. The partition carves out a one-dimensional DC subspace orthogonal to the channels, into which we inject a fixed Gabriel's horn profile r(p) = 1/(p+1) as an absolute-position side-channel composing orthogonally with RoPE's relative-position rotation. The canonical N=3 borrows its metaphor from balanced three-phase AC, where three sinusoids 120 degrees apart sum to zero with no anti-correlated pair. At 123M parameters on WikiText-103, 3PT achieves -7.20% perplexity (-2.62% bits-per-byte) over a matched RoPE-Only baseline at +1,536 parameters (0.00124% of total), with 1.93x step-count convergence speedup (1.64x wall-clock). N behaves as a parameter-sharing knob rather than a unique optimum: at 5.5M an N-sweep over {1,2,3,4,6,8,12} is near-monotone with N=1 winning; at 123M a three-seed sweep finds N=3 and N=1 statistically indistinguishable. The load-bearing mechanism is the channel-partitioned residual stream, per-block rotation, per-phase normalization, and horn DC injection. We characterize (a) self-stabilization of the geometry without explicit enforcement, a novel instance of the conservation-law framework for neural networks; (b) a U-shaped depth profile of rotation-angle drift at 12 layers; (c) orthogonal composition with RoPE, attention, and FFN.
### Title:
          Zero-Ablation Overstates Register Content Dependence in DINO Vision Transformers
 - **Authors:** Felipe Parodi, Jordan Matelsky, Melanie Segado
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Zero-ablation -- replacing token activations with zero vectors -- is widely used to probe token function in vision transformers. Register zeroing in DINOv2+registers and DINOv3 produces large drops (up to $-36.6$\,pp classification, $-30.9$\,pp segmentation), suggesting registers are functionally indispensable. However, three replacement controls -- mean-substitution, noise-substitution, and cross-image register-shuffling -- preserve performance across classification, correspondence, and segmentation, remaining within ${\sim}1$\,pp of the unmodified baseline. Per-patch cosine similarity shows these replacements genuinely perturb internal representations, while zeroing causes disproportionately large perturbations, consistent with why it alone degrades tasks. We conclude that zero-ablation overstates dependence on exact register content. In the frozen-feature evaluations we test, performance depends on plausible register-like activations rather than on exact image-specific values. Registers nevertheless buffer dense features from \texttt{[CLS]} dependence and are associated with compressed patch geometry. These findings, including the replacement-control results, replicate at ViT-B scale.
### Title:
          Hierarchical vs. Flat Iteration in Shared-Weight Transformers
 - **Authors:** Sang-Il Han
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present an empirical study of whether hierarchically structured, shared-weight recurrence can match the representational quality of independent-layer stacking in a Transformer-based language model. HRM-LM replaces L independent Transformer layers with a two-speed recurrent pair: a Fast module operating at every step for local refinement, and a Slow module operating every T steps for global compression. This recurrent hierarchy is unrolled for M = N x T steps with shared parameters. The central and most robust finding, supported by a parameter-matched Universal Transformer ablation (UniTF, 1.2B) across five independent runs, is a sharp empirical gap between the two approaches.
### Title:
          Seeing Through Circuits: Faithful Mechanistic Interpretability for Vision Transformers
 - **Authors:** Nina Żukowska, Wolfgang Stammer, Bernt Schiele, Jonas Fischer
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transparency of neural networks' internal reasoning is at the heart of interpretability research, adding to trust, safety, and understanding of these models. The field of mechanistic interpretability has recently focused on studying task-specific computational graphs, defined by connections (edges) between model components. Such edge-based circuits have been defined in the context of large language models, yet vision-based approaches so far only consider neuron-based circuits. These tell which information is encoded, but not how it is routed through the complex wiring of a neural network. In this work, we investigate whether useful mechanistic circuits can be identified through computational graphs in vision transformers. We propose an effective method for Automatic Visual Circuit Discovery (Vi-CD) that recovers class-specific circuits for classification, identifies circuits underlying typographic attacks in CLIP, and discovers circuits that lend themselves for steering to correct harmful model behavior. Overall, we find that insightful and actionable edge-based circuits can be recovered from vision transformers, adding transparency to the internal computations of these models.
### Title:
          Co-distilled attention guided masked image modeling with noisy teacher for self-supervised learning on medical images
 - **Authors:** Jue Jiang, Aneesh Rangnekar, Harini Veeraraghavan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Masked image modeling (MIM) is a highly effective self-supervised learning (SSL) approach to extract useful feature representations from unannotated data. Predominantly used random masking methods make SSL less effective for medical images due to the contextual similarity of neighboring patches, leading to information leakage and SSL simplification. Hierarchical shifted window (Swin) transformer, a highly effective approach for medical images cannot use advanced masking methods as it lacks a global [CLS] token. Hence, we introduced an attention guided masking mechanism for Swin within a co-distillation learning framework to selectively mask semantically co-occurring and discriminative patches, to reduce information leakage and increase the difficulty of SSL pretraining. However, attention guided masking inevitably reduces the diversity of attention heads, which negatively impacts downstream task performance. To address this, we for the first time, integrate a noisy teacher into the co-distillation framework (termed DAGMaN) that performs attentive masking while preserving high attention head diversity. We demonstrate the capability of DAGMaN on multiple tasks including full- and few-shot lung nodule classification, immunotherapy outcome prediction, tumor segmentation, and unsupervised organs clustering.
### Title:
          FreqTrack: Frequency Learning based Vision Transformer for RGB-Event Object Tracking
 - **Authors:** Jinlin You, Muyu Li, Xudong Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing single-modal RGB trackers often face performance bottlenecks in complex dynamic scenes, while the introduction of event sensors offers new potential for enhancing tracking capabilities. However, most current RGB-event fusion methods, primarily designed in the spatial domain using convolutional, Transformer, or Mamba architectures, fail to fully exploit the unique temporal response and high-frequency characteristics of event data. To address this, we1 propose FreqTrack, a frequency-aware RGBE tracking framework that establishes complementary inter-modal correlations through frequency-domain transformations for more robust feature fusion. We design a Spectral Enhancement Transformer (SET) layer that incorporates multi-head dynamic Fourier filtering to adaptively enhance and select frequency-domain features. Additionally, we develop a Wavelet Edge Refinement (WER) module, which leverages learnable wavelet transforms to explicitly extract multi-scale edge structures from event data, effectively improving modeling capability in high-speed and low-light scenarios. Extensive experiments on the COESOT and FE108 datasets demonstrate that FreqTrack achieves highly competitive performance, particularly attaining leading precision of 76.6\% on the COESOT benchmark, validating the effectiveness of frequency-domain modeling for RGBE tracking.
### Title:
          CoCoDiff: Optimizing Collective Communications for Distributed Diffusion Transformer Inference Under Ulysses Sequence Parallelism
 - **Authors:** Bin Ma, Xingjian Ding, Tekin Bicer, Pengfei Su, Dong Li
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Transformers (DiTs) are increasingly adopted in scientific computing, yet growing model sizes and resolutions make distributed multi-GPU inference essential. Ulysses sequence parallelism scales DiT inference but introduces frequent all-to-all collectives that dominate latency. Overlapping these with computation is difficult due to tight data dependencies, large message volumes, and asymmetric interconnect bandwidths. We introduce CoCoDiff, a distributed DiT inference engine exploiting two observations: (1) V requires only linear projection while Q/K need additional normalization and RoPE, creating opportunities to overlap V's communication with Q/K computation; (2) adjacent denoising steps produce similar tensors, yielding temporal redundancy. CoCoDiff introduces three mechanisms: Tile-Aware Parallel All-to-all (TAPA) decomposes collectives into topology-aligned phases; V-First scheduling hides V's communication behind Q/K computation; and V-Major selective communication transmits only active projections on slow interconnects. On the Aurora supercomputer with four DiT models across 1-8 nodes (up to 96 Intel GPU tiles), CoCoDiff achieves an average speedup of 3.6x, peaking at 8.4x.
### Title:
          Revisiting Token Compression for Accelerating ViT-based Sparse Multi-View 3D Object Detectors
 - **Authors:** Mingqian Ji, Shanshan Zhang, Jian Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformer (ViT)-based sparse multi-view 3D object detectors have achieved remarkable accuracy but still suffer from high inference latency due to heavy token processing. To accelerate these models, token compression has been widely explored. However, our revisit of existing strategies, such as token pruning, merging, and patch size enlargement, reveals that they often discard informative background cues, disrupt contextual consistency, and lose fine-grained semantics, negatively affecting 3D detection. To overcome these limitations, we propose SEPatch3D, a novel framework that dynamically adjusts patch sizes while preserving critical semantic information within coarse patches. Specifically, we design Spatiotemporal-aware Patch Size Selection (SPSS) that assigns small patches to scenes containing nearby objects to preserve fine details and large patches to background-dominated scenes to reduce computation cost. To further mitigate potential detail loss, Informative Patch Selection (IPS) selects the informative patches for feature refinement, and Cross-Granularity Feature Enhancement (CGFE) injects fine-grained details into selected coarse patches, enriching semantic features. Experiments on the nuScenes and Argoverse 2 validation sets show that SEPatch3D achieves up to \textbf{57\%} faster inference than the StreamPETR baseline and \textbf{20\%} higher efficiency than the state-of-the-art ToC3D-faster, while preserving comparable detection accuracy. Code is available at this https URL.
### Title:
          Multigrain-aware Semantic Prototype Scanning and Tri-Token Prompt Learning Embraced High-Order RWKV for Pan-Sharpening
 - **Authors:** Junfeng Li, Wenyang Zhou, Xueheng Li, Xuanhua He, Jianhou Gan, Wenqi Ren
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we propose a Multigrain-aware Semantic Prototype Scanning paradigm for pan-sharpening, built upon a high-order RWKV architecture and a tri-token prompting mechanism derived from semantic clustering. Specifically, our method contains three key components: 1) Multigrain-aware Semantic Prototype Scanning. Although RWKV offers a efficient linear-complexity alternative to Transformers, its conventional bidirectional raster scanning is still semantic-agnostic and prone to positional bias. To address this issue, we introduce a semantic-driven scanning strategy that leverages locality-sensitive hashing to group semantically related regions and construct multi-grain semantic prototypes, enabling context-aware token reordering and more coherent global interaction. 2) Tri-token Prompt Learning. We design a tri-token prompting mechanism consisting of a global token, cluster-derived prototype tokens, and a learnable register token. The global and prototype tokens provide complementary semantic priors for RWKV modeling, while the register token helps suppress noisy and artifact-prone intermediate representations. 3) Invertible Q-Shift. To counteract spatial details, we apply center difference convolution on the value pathway to inject high-frequency information, and introduce an invertible multi-scale Q-shift operation for efficient and lossless feature transformation without parameter-heavy receptive field expansion. Experimental results demonstrate the superiority of our method.
### Title:
          CMTM: Cross-Modal Token Modulation for Unsupervised Video Object Segmentation
 - **Authors:** Inseok Jeon, Suhwan Cho, Minhyeok Lee, Seunghoon Lee, Minseok Kang, Jungho Lee, Chaewon Park, Donghyeong Kim, Sangyoun Lee
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in unsupervised video object segmentation have highlighted the potential of two-stream architectures that integrate appearance and motion cues. However, fully leveraging these complementary sources of information requires effectively modeling their interdependencies. In this paper, we introduce cross-modality token modulation, a novel approach designed to strengthen the interaction between appearance and motion cues. Our method establishes dense connections between tokens from each modality, enabling efficient intra-modal and inter-modal information propagation through relation transformer blocks. To improve learning efficiency, we incorporate a token masking strategy that addresses the limitations of relying solely on increased model complexity. Our approach achieves state-of-the-art performance across all public benchmarks, outperforming existing methods.
### Title:
          A Mechanistic Account of Attention Sinks in GPT-2: One Circuit, Broader Implications for Mitigation
 - **Authors:** Yuval Ran-Milo, Hila Ofek, Shahar Mendel
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers commonly exhibit an attention sink: disproportionately high attention to the first position. We study this behavior in GPT-2-style models with learned query biases and absolute positional embeddings. Combining structural analysis with causal interventions, validated across natural-language, mathematical, and code inputs, we find that the sink arises from the interaction among (i) a learned query bias, (ii) the first-layer MLP transformation of the positional encoding, and (iii) structure in the key projection. Crucially, each component we identify is individually dispensable: architectures omitting each of them robustly exhibit sinks. This indicates that attention sinks may arise through distinct circuits across architectures. These findings inform mitigation of sinks, and motivate broader investigation into why sinks emerge.
### Title:
          HAMSA: Scanning-Free Vision State Space Models via SpectralPulseNet
 - **Authors:** Badri N. Patro, Vijay S. Agneeswaran
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision State Space Models (SSMs) like Vim, VMamba, and SiMBA rely on complex scanning strategies to adapt sequential SSMs to process 2D images, introducing computational overhead and architectural complexity. We propose HAMSA, a scanning-free SSM operating directly in the spectral domain. HAMSA introduces three key innovations: (1) simplified kernel parameterization-a single Gaussian-initialized complex kernel replacing traditional (A, B, C) matrices, eliminating discretization instabilities; (2) SpectralPulseNet (SPN)-an input-dependent frequency gating mechanism enabling adaptive spectral modulation; and (3) Spectral Adaptive Gating Unit (SAGU)-magnitude-based gating for stable gradient flow in the frequency domain. By leveraging FFT-based convolution, HAMSA eliminates sequential scanning while achieving O(L log L) complexity with superior simplicity and efficiency. On ImageNet-1K, HAMSA reaches 85.7% top-1 accuracy (state-of-the-art among SSMs), with 2.2 X faster inference than transformers (4.2ms vs 9.2ms for DeiT-S) and 1.4-1.9X speedup over scanning-based SSMs, while using less memory (2.1GB vs 3.2-4.5GB) and energy (12.5J vs 18-25J). HAMSA demonstrates strong generalization across transfer learning and dense prediction tasks.
### Title:
          Expressivity of Transformers: A Tropical Geometry Perspective
 - **Authors:** Ye Su, Yong Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 To quantify the geometric expressivity of transformers, we introduce a tropical geometry framework to characterize their exact spatial partitioning capabilities. By modeling self-attention as a vector-valued tropical rational map, we prove it evaluates exactly to a Power Voronoi Diagram in the zero-temperature limit. Building on this equivalence, we establish a combinatorial rationale for Multi-Head Self-Attention (MHSA): via the Minkowski sum of Newton polytopes, multi-head aggregation expands the polyhedral complexity to $\mathcal{O}(N^H)$, overcoming the $\mathcal{O}(N)$ bottleneck of single heads. Extending this to deep architectures, we derive the first tight asymptotic bounds on the number of linear regions in transformers ($\Theta(N^{d_{\text{model}}L})$), demonstrating a combinatorial explosion driven intrinsically by sequence length $N$, ambient embedding dimension $d_{\text{model}}$, and network depth $L$. Importantly, we guarantee that this idealized polyhedral skeleton is geometrically stable: finite-temperature soft attention preserves these topological partitions via exponentially tight differential approximation bounds.
### Title:
          Personalized and Context-Aware Transformer Models for Predicting Post-Intervention Physiological Responses from Wearable Sensor Data
 - **Authors:** Esther Brown, Victoria Dean, Finale Doshi-Velez
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Consumer wearables enable continuous measurement of physiological data related to stress and recovery, but turning these streams into actionable, personalized stress-management recommendations remains a challenge. In practice, users often do not know how a given intervention, defined as an activity intended to reduce stress, will affect heart rate (HR), heart rate variability (HRV), or inter-beat intervals (BBI) over the next 15 to 120 minutes. We present a framework that predicts post-intervention trajectories and the direction of change for these physiological indicators across time windows. Our methodology combines a Transformer model for multi-horizon trajectories of percent change relative to a pre-intervention baseline, direction-of-change calls (positive, negative, or neutral) at each horizon, and an empirical study using wearable sensor data overlaid with user-tagged events and interventions. This proof of concept shows that personalized post-intervention prediction is feasible. We encourage future integration into stress-management tools for personalized intervention recommendations tailored to each person's day following further validation in larger studies and, where applicable, appropriate regulatory review.
### Title:
          OmniGCD: Abstracting Generalized Category Discovery for Modality Agnosticism
 - **Authors:** Jordan Shipard, Arnold Wiliem, Kien Nguyen Thanh, Wei Xiang, Clinton Fookes
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generalized Category Discovery (GCD) challenges methods to identify known and novel classes using partially labeled data, mirroring human category learning. Unlike prior GCD methods, which operate within a single modality and require dataset-specific fine-tuning, we propose a modality-agnostic GCD approach inspired by the human brain's abstract category formation. Our $\textbf{OmniGCD}$ leverages modality-specific encoders (e.g., vision, audio, text, remote sensing) to process inputs, followed by dimension reduction to construct a $\textbf{GCD latent space}$, which is transformed at test-time into a representation better suited for clustering using a novel synthetically trained Transformer-based model. To evaluate OmniGCD, we introduce a $\textbf{zero-shot GCD setting}$ where no dataset-specific fine-tuning is allowed, enabling modality-agnostic category discovery. $\textbf{Trained once on synthetic data}$, OmniGCD performs zero-shot GCD across 16 datasets spanning four modalities, improving classification accuracy for known and novel classes over baselines (average percentage point improvement of $\textbf{+6.2}$, $\textbf{+17.9}$, $\textbf{+1.5}$ and $\textbf{+12.7}$ for vision, text, audio and remote sensing). This highlights the importance of strong encoders while decoupling representation learning from category discovery. Improving modality-agnostic methods will propagate across modalities, enabling encoder development independent of GCD. Our work serves as a benchmark for future modality-agnostic GCD works, paving the way for scalable, human-inspired category discovery. All code is available $\href{this https URL}{here}$
### Title:
          Constraint-based Pre-training: From Structured Constraints to Scalable Model Initialization
 - **Authors:** Fu Feng, Yucheng Xie, Ruixiao Shi, Jing Wang, Xin Geng
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The pre-training and fine-tuning paradigm has become the dominant approach for model adaptation. However, conventional pre-training typically yields models at a fixed scale, whereas practical deployment often requires models of varying sizes, exposing its limitations when target model scales differ from those used during pre-training. To address this, we propose an innovative constraint-based pre-training paradigm that imposes structured constraints during pre-training to disentangle size-agnostic knowledge into reusable weight templates, while assigning size-specific adaptation to lightweight weight scalers, thereby reformulating variable-sized model initialization as a multi-task adaptation problem. Within this paradigm, we further introduce WeiT, which employs Kronecker-based constraints to regularize the pre-training process. Specifically, model parameters are represented as compositions of weight templates via concatenation and weighted aggregation, with adaptive connections governed by lightweight weight scalers whose parameters are learned from limited data. This design enables flexible and efficient construction of model weights across diverse downstream scales. Extensive experiments demonstrate the efficiency and effectiveness of WeiT, achieving state-of-the-art performance in initializing models with varying depths and widths across a broad range of perception and embodied learning tasks, including Image Classification, Image Generation, and Embodied Control. Moreover, its effectiveness generalizes to both Transformer-based and Convolution-based architectures, consistently enabling faster convergence and improved performance even under full training.
### Title:
          Domain Fine-Tuning FinBERT on Finnish Histopathological Reports: Train-Time Signals and Downstream Correlations
 - **Authors:** Rami Luisto, Liisa Petäinen, Tommi Grönholm, Jan Böhm, Maarit Ahtiainen, Tomi Lilja, Ilkka Pölönen, Sami Äyrämö
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In NLP classification tasks where little labeled data exists, domain fine-tuning of transformer models on unlabeled data is an established approach. In this paper we have two aims. (1) We describe our observations from fine-tuning the Finnish BERT model on Finnish medical text data. (2) We report on our attempts to predict the benefit of domain-specific pre-training of Finnish BERT from observing the geometry of embedding changes due to domain fine-tuning. Our driving motivation is the common\situation in healthcare AI where we might experience long delays in acquiring datasets, especially with respect to labels.
### Title:
          Nautilus: An Auto-Scheduling Tensor Compiler for Efficient Tiled GPU Kernels
 - **Authors:** Yifan Zhao, Yuchen Yang, Matei Budiu, Sasa Misailovic
 - **Subjects:** Subjects:
Programming Languages (cs.PL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Nautilus, a novel tensor compiler that moves toward fully automated math-to-kernel optimization. Nautilus compiles a high-level algebraic specification of tensor operators into efficient tiled GPU kernels. Nautilus's successive lowering design allows high-level optimizations, expression rewrites, and tile optimizations to be jointly applied in a single end-to-end system. Nautilus presents a novel auto-scheduler that discovers sequences of high-level optimizations, while preserving the regular program structure needed by tile optimizers. Nautilus's auto-scheduler captures complex interactions and trade-offs in the high-level optimizations, including aggressive global transformations like advanced reduction fusion. Nautilus is the first end-to-end tensor compiler capable of starting from a math-like description of attention and automatically discovering FlashAttention-3-like kernels, offloading the entire burden of optimization from the programmer to the compiler. Across five transformer-based models and 150 evaluation configurations on NVIDIA GH200 and RTX 5090 GPUs, Nautilus achieves up to 23% higher throughput than state-of-the-art compilers on GH200 and up to 42% on RTX 5090, while matching or exceeding manually written cuDNN kernels on many long-sequence configurations.
### Title:
          Improved Multiscale Structural Mapping with Supervertex Vision Transformer for the Detection of Alzheimer's Disease Neurodegeneration
 - **Authors:** Geonwoo Baek, David H. Salat, Ikbeom Jang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Alzheimer's disease (AD) confirmation often relies on positron emission tomography (PET) or cerebrospinal fluid (CSF) analysis, which are costly and invasive. Consequently, structural MRI biomarkers such as cortical thickness (CT) are widely used for non-invasive AD screening. Multiscale structural mapping (MSSM) was recently proposed to integrate gray-white matter contrasts (GWCs) with CT from a single T1-weighted MRI (T1w) scan. Building on this framework, we propose MSSM+, together with surface supervertex mapping (SSVM) and a Supervertex Vision Transformer (SV-ViT). 3D T1w images from individuals with AD and cognitively normal (CN) controls were analyzed. MSSM+ extends MSSM by incorporating sulcal depth and cortical curvature at the vertex level. SSVM partitions the cortical surface into supervertices (surface patches) that effectively represent inter- and intra-regional spatial relationships. SV-ViT is a Vision Transformer architecture operating on these supervertices, enabling anatomically informed learning from surface mesh representations. Compared with MSSM, MSSM+ identified more spatially extensive and statistically significant group differences between AD and CN. In AD vs. CN classification, MSSM+ achieved a 3%p higher area under the precision-recall curve than MSSM. Vendor-specific analyses further demonstrated reduced signal variability and consistently improved classification performance across MR manufacturers relative to CT, GWCs, and MSSM. These findings suggest that MSSM+ combined with SV-ViT is a promising MRI-based imaging marker for AD detection prior to CSF/PET confirmation.
### Title:
          Curvature-Aligned Probing for Local Loss-Landscape Stabilization
 - **Authors:** Nikita Kiselev, Andrey Grabovoy
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Local loss-landscape stabilization under sample growth is typically measured either pointwise or through isotropic averaging in the full parameter space. Despite practical value, both choices probe directions that contribute little to the dominant local deformation of strongly anisotropic neural landscapes. We recast stabilization as an observational problem and introduce a unified family of criteria parameterized by an aggregation order and a probing distribution; within this family we propose a curvature-aligned criterion $\Delta_2^{(D)}$ that probes the loss increment field in the top-$D$ eigenspace of the empirical Hessian near a trained solution. Solely from a local quadratic model, we prove that $\Delta_2^{(D)}$ preserves the $O(k^{-2})$ mean-squared rate of the full-space criterion while replacing ambient-dimension curvature dependence with dependence on the subspace dimension $D$; a corollary gives a closed-form spectral expression and a proposition identifies the top-$D$ eigenspace as extremal within the eigenspace-aligned family. We also derive scalable estimators based on Hessian-vector products, subspace Monte Carlo, and a closed-form Gaussian-moment proxy. On a decoder-only transformer, a curvature-aligned probe occupying a tiny fraction of parameter space already reproduces the full-space mean-squared signal to within numerical noise throughout the validated local regime, and the closed-form estimator is orders of magnitude faster than direct Monte Carlo after subspace construction.
### Title:
          Generative Data Augmentation for Skeleton Action Recognition
 - **Authors:** Xu Dong, Wanqing Li, Anthony Adeyemi-Ejeye, Andrew Gilbert
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Skeleton-based human action recognition is a powerful approach for understanding human behaviour from pose data, but collecting large-scale, diverse, and well-annotated 3D skeleton datasets is both expensive and labor-intensive. To address this challenge, we propose a conditional generative pipeline for data augmentation in skeleton action recognition. Our method learns the distribution of real skeleton sequences under the constraint of action labels, enabling the synthesis of diverse and high-fidelity data. Even with limited training samples, it can effectively generate skeleton sequences and achieve competitive recognition performance in low-data scenarios, demonstrating strong generalisation in downstream tasks. Specifically, we introduce a Transformer-based encoder-decoder architecture, combined with a generative refinement module and a dropout mechanism, to balance fidelity and diversity during sampling. Experiments on HumanAct12 and the refined NTU-RGBD (NTU-VIBE) dataset show that our approach consistently improves the accuracy of multiple skeleton-based action recognition models, validating its effectiveness in both few-shot and full-data settings. The source code can be found at here.
### Title:
          Towards Faster Language Model Inference Using Mixture-of-Experts Flow Matching
 - **Authors:** Aihua Li
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Flow matching retains the generation quality of diffusion models while enabling substantially faster inference, making it a compelling paradigm for generative modeling. However, when applied to language modeling, it exhibits fundamental limitations in representing complex latent distributions with irregular geometries, such as anisotropy and multimodality. To address these challenges, we propose a mixture-of-experts flow matching (MoE-FM) framework, which captures complex global transport geometries in latent space by decomposing them into locally specialized vector fields. Building on MoE-FM, we develop a non-autoregressive (NAR) language modeling approach, named YAN, instantiated with both Transformer and Mamba architectures. Across multiple downstream tasks, YAN achieves generation quality on par with both autoregressive (AR) and diffusion-based NAR language models, while requiring as few as three sampling steps. This yields a $40\times$ speedup over AR baselines and up to a $10^3\times$ speedup over diffusion language models, demonstrating substantial efficiency advantages for language modeling.
### Title:
          What Is the Minimum Architecture for Prolepsis? Early Irrevocable Commitment Across Tasks in Small Transformers
 - **Authors:** Éric Jacopin
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When do transformers commit to a decision, and what prevents them from correcting it? We introduce \textbf{prolepsis}: a transformer commits early, task-specific attention heads sustain the commitment, and no layer corrects it. Replicating \citeauthor{lindsey2025biology}'s (\citeyear{lindsey2025biology}) planning-site finding on open models (Gemma~2 2B, Llama~3.2 1B), we ask five questions. (Q1)~Planning is invisible to six residual-stream methods; CLTs are necessary. (Q2)~The planning-site spike replicates with identical geometry. (Q3)~Specific attention heads route the decision to the output, filling a gap flagged as invisible to attribution graphs. (Q4)~Search requires ${\leq}16$ layers; commitment requires more. (Q5)~Factual recall shows the same motif at a different network depth, with zero overlap between recurring planning heads and the factual top-10. Prolepsis is architectural: the template is shared, the routing substrates differ. All experiments run on a single consumer GPU (16\,GB VRAM).
### Title:
          Learning Where to Embed: Noise-Aware Positional Embedding for Query Retrieval in Small-Object Detection
 - **Authors:** Yangchen Zeng, Zhenyu Yu, Dongming Jiang, Wenbo Zhang, Yifan Hong, Zhanhua Hu, Jiao Luo, Kangning Cui
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based detectors have advanced small-object detection, but they often remain inefficient and vulnerable to background-induced query noise, which motivates deep decoders to refine low-quality queries. We present HELP (Heatmap-guided Embedding Learning Paradigm), a noise-aware positional-semantic fusion framework that studies where to embed positional information by selectively preserving positional encodings in foreground-salient regions while suppressing background clutter. Within HELP, we introduce Heatmap-guided Positional Embedding (HPE) as the core embedding mechanism and visualize it with a heatbar for interpretable diagnosis and fine-tuning. HPE is integrated into both the encoder and decoder: it guides noise-suppressed feature encoding by injecting heatmap-aware positional encoding, and it enables high-quality query retrieval by filtering background-dominant embeddings via a gradient-based mask filter before decoding. To address feature sparsity in complex small targets, we integrate Linear-Snake Convolution to enrich retrieval-relevant representations. The gradient-based heatmap supervision is used during training only, incurring no additional gradient computation at inference. As a result, our design reduces decoder layers from eight to three and achieves a 59.4% parameter reduction (66.3M vs. 163M) while maintaining consistent accuracy gains under a reduced compute budget across benchmarks. Code Repository: this https URL
### Title:
          Beyond the Laplacian: Doubly Stochastic Matrices for Graph Neural Networks
 - **Authors:** Zhaobo Hu, Vincent Gauthier, Mehdi Naima
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph Neural Networks (GNNs) conventionally rely on standard Laplacian or adjacency matrices for structural message passing. In this work, we substitute the traditional Laplacian with a Doubly Stochastic graph Matrix (DSM), derived from the inverse of the modified Laplacian, to naturally encode continuous multi-hop proximity and strict local centrality. To overcome the intractable $O(n^3)$ complexity of exact matrix inversion, we first utilize a truncated Neumann series to scalably approximate the DSM, which serves as the foundation for our proposed DsmNet. Furthermore, because algebraic truncation inherently causes probability mass leakage, we introduce DsmNet-compensate. This variant features a mathematically rigorous Residual Mass Compensation mechanism that analytically re-injects the truncated tail mass into self-loops, strictly restoring row-stochasticity and structural dominance. Extensive theoretical and empirical analyses demonstrate that our decoupled architectures operate efficiently in $O(K|E|)$ time and effectively mitigate over-smoothing by bounding Dirichlet energy decay, providing robust empirical validation on homophilic benchmarks. Finally, we establish the theoretical boundaries of the DSM on heterophilic topologies and demonstrate its versatility as a continuous structural encoding for Graph Transformers.
### Title:
          Class Unlearning via Depth-Aware Removal of Forget-Specific Directions
 - **Authors:** Arman Hatami, Romina Aalishah, Ilya E. Monosov
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Machine unlearning aims to remove targeted knowledge from a trained model without the cost of retraining from scratch. In class unlearning, however, reducing accuracy on forget classes does not necessarily imply true forgetting: forgotten information can remain encoded in internal representations, and apparent forgetting may arise from classifier-head suppression rather than representational removal. We show that existing class-unlearning methods often exhibit weak or negative selectivity, preserve forget-class structure in deep representations, or rely heavily on final-layer bias shifts. We then introduce DAMP (Depth-Aware Modulation by Projection), a one-shot, closed-form weight-surgery method that removes forget-specific directions from a pretrained network without gradient-based optimization. At each stage, DAMP computes class prototypes in the input space of the next learnable operator, extracts forget directions as residuals relative to retain-class prototypes, and applies a projection-based update to reduce downstream sensitivity to those directions. To preserve utility, DAMP uses a parameter-free depth-aware scaling rule derived from probe separability, applying smaller edits in early layers and larger edits in deeper layers. The method naturally extends to multi-class forgetting through low-rank subspace removal. Across MNIST, CIFAR-10, CIFAR-100, and Tiny ImageNet, and across convolutional and transformer architectures, DAMP more closely resembles the retraining gold standard than some of the prior methods, improving selective forgetting while better preserving retain-class performance and reducing residual forget-class structure in deep layers.
### Title:
          AdaSplash-2: Faster Differentiable Sparse Attention
 - **Authors:** Nuno Gonçalves, Hugo Pitorro, Vlad Niculae, Edoardo Ponti, Lei Li, Andre Martins, Marcos Treviso
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse attention has been proposed as a way to alleviate the quadratic cost of transformers, a central bottleneck in long-context training. A promising line of work is $\alpha$-entmax attention, a differentiable sparse alternative to softmax that enables input-dependent sparsity yet has lagged behind softmax due to the computational overhead necessary to compute the normalizer $\tau$. In this paper, we introduce AdaSplash-2, which addresses this limitation through a novel histogram-based initialization that reduces the number of iterations needed to compute $\tau$ to typically 1--2. The key idea is to compute a coarse histogram of attention scores on the fly and store it in on-chip SRAM, yielding a more accurate initialization that enables fast forward and backward computation. Combined with a sparsity-aware GPU implementation that skips zero blocks with low overhead, AdaSplash-2 matches or improves per-step training time relative to FlashAttention-2 when block sparsity is moderate-to-high (e.g., $>$60\%), which often occurs at long-context lengths. On downstream tasks, models trained with our efficient $\alpha$-entmax attention match softmax baselines at short-context lengths and achieve substantial gains in long-context settings.
### Title:
          StreamCacheVGGT: Streaming Visual Geometry Transformers with Robust Scoring and Hybrid Cache Compression
 - **Authors:** Xuanyi Liu, Deyi Ji, Chunan Yu, Qi Zhu, Xuanfu Li, Jin Ma, Tianrun Chen, Lanyun Zhu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing dense 3D geometry from continuous video streams requires stable inference under a constant memory budget. Existing $O(1)$ frameworks primarily rely on a ``pure eviction'' paradigm, which suffers from significant information destruction due to binary token deletion and evaluation noise from localized, single-layer scoring. To address these bottlenecks, we propose StreamCacheVGGT, a training-free framework that reimagines cache management through two synergistic modules: Cross-Layer Consistency-Enhanced Scoring (CLCES) and Hybrid Cache Compression (HCC). CLCES mitigates activation noise by tracking token importance trajectories across the Transformer hierarchy, employing order-statistical analysis to identify sustained geometric salience. Leveraging these robust scores, HCC transcends simple eviction by introducing a three-tier triage strategy that merges moderately important tokens into retained anchors via nearest-neighbor assignment on the key-vector manifold. This approach preserves essential geometric context that would otherwise be lost. Extensive evaluations on five benchmarks (7-Scenes, NRGBD, ETH3D, Bonn, and KITTI) demonstrate that StreamCacheVGGT sets a new state-of-the-art, delivering superior reconstruction accuracy and long-term stability while strictly adhering to constant-cost constraints.
### Title:
          TokenGS: Decoupling 3D Gaussian Prediction from Pixels with Learnable Tokens
 - **Authors:** Jiawei Ren, Michal Jan Tyszkiewicz, Jiahui Huang, Zan Gojcic
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this work, we revisit several key design choices of modern Transformer-based approaches for feed-forward 3D Gaussian Splatting (3DGS) prediction. We argue that the common practice of regressing Gaussian means as depths along camera rays is suboptimal, and instead propose to directly regress 3D mean coordinates using only a self-supervised rendering loss. This formulation allows us to move from the standard encoder-only design to an encoder-decoder architecture with learnable Gaussian tokens, thereby unbinding the number of predicted primitives from input image resolution and number of views. Our resulting method, TokenGS, demonstrates improved robustness to pose noise and multiview inconsistencies, while naturally supporting efficient test-time optimization in token space without degrading learned priors. TokenGS achieves state-of-the-art feed-forward reconstruction performance on both static and dynamic scenes, producing more regularized geometry and more balanced 3DGS distribution, while seamlessly recovering emergent scene attributes such as static-dynamic decomposition and scene flow.
### Title:
          Stability and Generalization in Looped Transformers
 - **Authors:** Asher Labovich
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Looped transformers promise test-time compute scaling by spending more iterations on harder problems, but it remains unclear which architectural choices let them extrapolate to harder problems at test time rather than memorize training-specific solutions. We introduce a fixed-point based framework for analyzing looped architectures along three axes of stability -- reachability, input-dependence, and geometry -- and use it to characterize when fixed-point iteration yields meaningful predictions. Theoretically, we prove that looped networks without recall have countable fixed points and cannot achieve strong input-dependence at any spectral regime, while recall combined with outer normalization reliably produces a regime in which fixed points are simultaneously reachable, locally smooth in the input, and supported by stable backpropagation. Empirically, we train single-layer looped transformers on chess, sudoku, and prefix-sums and find that downstream performance tracks the framework's predictions across tasks and architectural configurations. We additionally introduce internal recall, a novel recall placement variant, and show that it becomes competitive with -- and on sudoku, substantially better than -- standard recall placement once outer normalization is applied.
### Title:
          R3D: Revisiting 3D Policy Learning
 - **Authors:** Zhengdong Hong, Shenrui Wu, Haozhe Cui, Boyi Zhao, Ran Ji, Yiyang He, Hangxing Zhang, Zundong Ke, Jun Wang, Guofeng Zhang, Jiayuan Gu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D policy learning promises superior generalization and cross-embodiment transfer, but progress has been hindered by training instabilities and severe overfitting, precluding the adoption of powerful 3D perception models. In this work, we systematically diagnose these failures, identifying the omission of 3D data augmentation and the adverse effects of Batch Normalization as primary causes. We propose a new architecture coupling a scalable transformer-based 3D encoder with a diffusion decoder, engineered specifically for stability at scale and designed to leverage large-scale pre-training. Our approach significantly outperforms state-of-the-art 3D baselines on challenging manipulation benchmarks, establishing a new and robust foundation for scalable 3D imitation learning. Project Page: this https URL
## Keyword: autonomous driving
### Title:
          Towards Verified and Targeted Explanations through Formal Methods
 - **Authors:** Hanchen David Wang, Diego Manzanas Lopez, Preston K. Robinette, Ipek Oguz, Taylor T. Johnson, Meiyi Ma
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As deep neural networks are deployed in safety-critical domains such as autonomous driving and medical diagnosis, stakeholders need explanations that are interpretable but also trustworthy with formal guarantees. Existing XAI methods fall short: heuristic attribution techniques (e.g., LIME, Integrated Gradients) highlight influential features but offer no mathematical guarantees about decision boundaries, while formal methods verify robustness yet remain untargeted, analyzing the nearest boundary regardless of whether it represents a critical risk. In safety-critical systems, not all misclassifications carry equal consequences; confusing a "Stop" sign for a "60 kph" sign is far more dangerous than confusing it with a "No Passing" sign. We introduce ViTaX (Verified and Targeted Explanations), a formal XAI framework that generates targeted semifactual explanations with mathematical guarantees. For a given input (class y) and a user-specified critical alternative (class t), ViTaX: (1) identifies the minimal feature subset most sensitive to the y->t transition, and (2) applies formal reachability analysis to guarantee that perturbing these features by epsilon cannot flip the classification to t. We formalize this through Targeted epsilon-Robustness, certifying whether a feature subset remains robust under perturbation toward a specific target class. ViTaX is the first method to provide formally guaranteed explanations of a model's resilience against user-identified alternatives. Evaluations on MNIST, GTSRB, EMNIST, and TaxiNet demonstrate over 30% fidelity improvement with minimal explanation cardinality.
### Title:
          AD4AD: Benchmarking Visual Anomaly Detection Models for Safer Autonomous Driving
 - **Authors:** Fabrizio Genilotti, Arianna Stropeni, Gionata Grotto, Francesco Borsatti, Manuel Barusco, Davide Dalle Pezze, Gian Antonio Susto
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The reliability of a machine vision system for autonomous driving depends heavily on its training data distribution. When a vehicle encounters significantly different conditions, such as atypical obstacles, its perceptual capabilities can degrade substantially. Unlike many domains where errors carry limited consequences, failures in autonomous driving translate directly into physical risk for passengers, pedestrians, and other road users. To address this challenge, we explore Visual Anomaly Detection (VAD) as a solution. VAD enables the identification of anomalous objects not present during training, allowing the system to alert the driver when an unfamiliar situation is detected. Crucially, VAD models produce pixel-level anomaly maps that can guide driver attention to specific regions of concern without requiring any prior assumptions about the nature or form of the hazard. We benchmark eight state-of-the-art VAD methods on AnoVox, the largest synthetic dataset for anomaly detection in autonomous driving. In particular, we evaluate performance across four backbone architectures spanning from large networks to lightweight ones such as MobileNet and DeiT-Tiny. Our results demonstrate that VAD transfers effectively to road scenes. Notably, Tiny-Dinomaly achieves the best accuracy-efficiency trade-off for edge deployment, matching full-scale localization performance at a fraction of the memory cost. This study represents a concrete step toward safer, more responsible deployment of autonomous vehicles, ultimately improving protection for passengers, pedestrians, and all road users.
### Title:
          RAD-2: Scaling Reinforcement Learning in a Generator-Discriminator Framework
 - **Authors:** Hao Gao, Shaoyu Chen, Yifan Zhu, Yuehao Song, Wenyu Liu, Qian Zhang, Xinggang Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-level autonomous driving requires motion planners capable of modeling multimodal future uncertainties while remaining robust in closed-loop interactions. Although diffusion-based planners are effective at modeling complex trajectory distributions, they often suffer from stochastic instabilities and the lack of corrective negative feedback when trained purely with imitation learning. To address these issues, we propose RAD-2, a unified generator-discriminator framework for closed-loop planning. Specifically, a diffusion-based generator is used to produce diverse trajectory candidates, while an RL-optimized discriminator reranks these candidates according to their long-term driving quality. This decoupled design avoids directly applying sparse scalar rewards to the full high-dimensional trajectory space, thereby improving optimization stability. To further enhance reinforcement learning, we introduce Temporally Consistent Group Relative Policy Optimization, which exploits temporal coherence to alleviate the credit assignment problem. In addition, we propose On-policy Generator Optimization, which converts closed-loop feedback into structured longitudinal optimization signals and progressively shifts the generator toward high-reward trajectory manifolds. To support efficient large-scale training, we introduce BEV-Warp, a high-throughput simulation environment that performs closed-loop evaluation directly in Bird's-Eye View feature space via spatial warping. RAD-2 reduces the collision rate by 56% compared with strong diffusion-based planners. Real-world deployment further demonstrates improved perceived safety and driving smoothness in complex urban traffic.
