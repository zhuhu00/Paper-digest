# Showing new listings for Wednesday, 25 March 2026
## Keyword: SLAM
### Title:
          Variable-Resolution Virtual Maps for Autonomous Exploration with Unmanned Surface Vehicles (USVs)
 - **Authors:** Ye Li, Yewei Huang, Wenlong GaoZhang, Alberto Quattrini Li, Brendan Englot, Yuanchang Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous exploration by unmanned surface vehicles (USVs) in near-shore waters requires reliable localisation and consistent mapping over extended areas, but this is challenged by GNSS degradation, environment-induced localisation uncertainty, and limited on-board computation. Virtual map-based methods explicitly model localisation and mapping uncertainty by tightly coupling factor-graph SLAM with a map uncertainty criterion. However, their storage and computational costs scale poorly with fixed-resolution workspace discretisations, leading to inefficiency in large near-shore environments. Moreover, overvaluing feature-sparse open-water regions can increase the risk of SLAM failure as a result of imbalance between exploration and exploitation. To address these limitations, we propose a Variable-Resolution Virtual Map (VRVM), a computationally efficient method for representing map uncertainty using bivariate Gaussian virtual landmarks placed in the cells of an adaptive quadtree. The adaptive quadtree enables an area-weighted uncertainty representation that keeps coarse, far-field virtual landmarks deliberately uncertain while allocating higher resolution to information-dense regions, and reduces the sensitivity of the map valuation to local refinements of the tree. An expectation-maximisation (EM) planner is adopted to evaluate pose and map uncertainty along frontiers using the VRVM, balancing exploration and exploitation. We evaluate VRVM against several state-of-the-art exploration algorithms in the VRX Gazebo simulator, using a realistic marina environment across different testing scenarios with an increasing level of exploration difficulty. The results indicate that our method offers safer behaviour and better utilisation of on-board computation in GNSS-degraded near-shore environments.
### Title:
          Digital Twin Enabled Simultaneous Learning and Modeling for UAV-assisted Secure Communications with Eavesdropping Attacks
 - **Authors:** Jieting Yuan, Songhan Zhao, Ye Xue, Yu Zhao, Bo Gu, Shimin Gong
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper focuses on secure communications in UAV-assisted wireless networks, which comprise multiple legitimate UAVs (LE-UAVs) and an intelligent eavesdropping UAV (EA-UAV). The intelligent EA-UAV can observe the LE-UAVs'transmission strategies and adaptively adjust its trajectory to maximize information interception. To counter this threat, we propose a mode-switching scheme that enables LE-UAVs to dynamically switch between the data transmission and jamming modes, thereby balancing data collection efficiency and communication security. However, acquiring full global network state information for LE-UAVs' decision-making incurs significant overhead, as the network state is highly dynamic and time-varying. To address this challenge, we propose a digital twin-enabled simultaneous learning and modeling (DT-SLAM) framework that allows LE-UAVs to learn policies efficiently within the DT, thereby avoiding frequent interactions with the real environment. To capture the competitive relationship between the EA-UAV and the LE-UAVs, we model their interactions as a multi-stage Stackelberg game and jointly optimize the GUs' transmission control, UAVs' trajectory planning, mode selection, and network formation to maximize overall secure throughput. Considering potential model mismatch between the DT and the real environment, we propose a robust proximal policy optimization (RPPO) algorithm that encourages LE-UAVs to explore service regions with higher uncertainty. Numerical results demonstrate that the proposed DT-SLAM framework effectively supports the learning process. Meanwhile, the RPPO algorithm converges about 12% faster and the secure throughput can be increased by 8.6% compared to benchmark methods.
## Keyword: odometry
### Title:
          Tightly-Coupled Radar-Visual-Inertial Odometry
 - **Authors:** Morten Nissov, Mohit Singh, Kostas Alexis
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual-Inertial Odometry (VIO) is a staple for reliable state estimation on constrained and lightweight platforms due to its versatility and demonstrated performance. However, pertinent challenges regarding robust operation in dark, low-texture, obscured environments complicate the use of such methods. Alternatively, Frequency Modulated Continuous Wave (FMCW) radars, and by extension Radar-Inertial Odometry (RIO), offer robustness to these visual challenges, albeit at the cost of reduced information density and worse long-term accuracy. To address these limitations, this work combines the two in a tightly coupled manner, enabling the resulting method to operate robustly regardless of environmental conditions or trajectory dynamics. The proposed method fuses image features, radar Doppler measurements, and Inertial Measurement Unit (IMU) measurements within an Iterated Extended Kalman Filter (IEKF) in real-time, with radar range data augmenting the visual feature depth initialization. The method is evaluated through flight experiments conducted in both indoor and outdoor environments, as well as through challenges to both exteroceptive modalities (such as darkness, fog, or fast flight), thoroughly demonstrating its robustness. The implementation of the proposed method is available at: this https URL .
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Spatially-Aware Evaluation Framework for Aerial LiDAR Point Cloud Semantic Segmentation: Distance-Based Metrics on Challenging Regions
 - **Authors:** Alex Salvatierra, José Antonio Sanz, Christian Gutiérrez, Mikel Galar
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic segmentation metrics for 3D point clouds, such as mean Intersection over Union (mIoU) and Overall Accuracy (OA), present two key limitations in the context of aerial LiDAR data. First, they treat all misclassifications equally regardless of their spatial context, overlooking cases where the geometric severity of errors directly impacts the quality of derived geospatial products such as Digital Terrain Models. Second, they are often dominated by the large proportion of easily classified points, which can mask meaningful differences between models and under-represent performance in challenging regions. To address these limitations, we propose a novel evaluation framework for comparing semantic segmentation models through two complementary approaches. First, we introduce distance-based metrics that account for the spatial deviation between each misclassified point and the nearest ground-truth point of the predicted class, capturing the geometric severity of errors. Second, we propose a focused evaluation on a common subset of hard points, defined as the points misclassified by at least one of the evaluated models, thereby reducing the bias introduced by easily classified points and better revealing differences in model performance in challenging regions. We validate our framework by comparing three state-of-the-art deep learning models on three aerial LiDAR datasets. Results demonstrate that the proposed metrics provide complementary information to traditional measures, revealing spatial error patterns that are critical for Earth Observation applications but invisible to conventional evaluation approaches. The proposed framework enables more informed model selection for scenarios where spatial consistency is critical.
### Title:
          MapForest: A Modular Field Robotics System for Forest Mapping and Invasive Species Localization
 - **Authors:** Sandeep Zachariah, Francisco Yandun, Sachet Korada, Abhisesh Silwal
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monitoring and controlling invasive tree species across large forests, parks, and trail networks is challenging due to limited accessibility, reliance on manual scouting, and degraded under-canopy GNSS. We present MapForest, a modular field robotics system that transforms multi-modal sensor data into GIS-ready invasive-species maps. Our system features: (i) a compact, platform-agnostic sensing payload that can be rapidly mounted on UAV, bicycle, or backpack platforms, and (ii) a software pipeline comprising LiDAR-inertial mapping, image-based invasive-species detection, and georeferenced map generation. To ensure reliable operation in GNSS-intermittent environments, we enhance a LiDAR-inertial mapping backbone with covariance-aware GNSS factors and robust loss kernels. We train an object detector to detect the Tree-of-Heaven (Ailanthus altissima) from onboard RGB imagery and fuse detections with the reconstructed map to produce geospatial outputs suitable for downstream decision making. We collected a dataset spanning six sites across urban environments, parks, trails, and forests to evaluate individual system modules, and report end-to-end results on two sites containing Tree-of-Heaven. The enhanced mapping module achieved a trajectory deviation error of 1.95 m over a 1.2 km forest traversal, and the Tree-of-Heaven detector achieved an F1 score of 0.653. The datasets and associated tooling are released to support reproducible research in forest mapping and invasive-species monitoring.
### Title:
          Typography-Based Monocular Distance Estimation Framework for Vehicle Safety Systems
 - **Authors:** Manognya Lokesh Reddy, Zheng Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate inter-vehicle distance estimation is a cornerstone of advanced driver assistance systems and autonomous driving. While LiDAR and radar provide high precision, their cost prohibits widespread adoption in mass-market vehicles. Monocular vision offers a low-cost alternative but suffers from scale ambiguity and sensitivity to environmental disturbances. This paper introduces a typography-based monocular distance estimation framework, which exploits the standardized typography of license plates as passive fiducial markers for metric distance estimation. The core geometric module uses robust plate detection and character segmentation to measure character height and computes distance via the pinhole camera model. The system incorporates interactive calibration, adaptive detection with strict and permissive modes, and multi-method character segmentation leveraging both adaptive and global thresholding. To enhance robustness, the framework further includes camera pose compensation using lane-based horizon estimation, hybrid deep-learning fusion, temporal Kalman filtering for velocity estimation, and multi-feature fusion that exploits additional typographic cues such as stroke width, character spacing, and plate border thickness. Experimental validation with a calibrated monocular camera in a controlled indoor setup achieved a coefficient of variation of 2.3% in character height across consecutive frames and a mean absolute error of 7.7%. The framework operates without GPU acceleration, demonstrating real-time feasibility. A comprehensive comparison with a plate-width based method shows that character-based ranging reduces the standard deviation of estimates by 35%, translating to smoother, more consistent distance readings in practice, where erratic estimates could trigger unnecessary braking or acceleration.
### Title:
          Gau-Occ: Geometry-Completed Gaussians for Multi-Modal 3D Occupancy Prediction
 - **Authors:** Chengxin Lv, Yihui Li, Hongyu Yang, YunHong Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D semantic occupancy prediction is crucial for autonomous driving. While multi-modal fusion improves accuracy over vision-only methods, it typically relies on computationally expensive dense voxel or BEV tensors. We present Gau-Occ, a multi-modal framework that bypasses dense volumetric processing by modeling the scene as a compact collection of semantic 3D Gaussians. To ensure geometric completeness, we propose a LiDAR Completion Diffuser (LCD) that recovers missing structures from sparse LiDAR to initialize robust Gaussian anchors. Furthermore, we introduce Gaussian Anchor Fusion (GAF), which efficiently integrates multi-view image semantics via geometry-aligned 2D sampling and cross-modal alignment. By refining these compact Gaussian descriptors, Gau-Occ captures both spatial consistency and semantic discriminability. Extensive experiments across challenging benchmarks demonstrate that Gau-Occ achieves state-of-the-art performance with significant computational efficiency.
### Title:
          LiZIP: An Auto-Regressive Compression Framework for LiDAR Point Clouds
 - **Authors:** Aditya Shibu, Kayvan Karim, Claudio Zito
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The massive volume of data generated by LiDAR sensors in autonomous vehicles creates a bottleneck for real-time processing and vehicle-to-everything (V2X) transmission. Existing lossless compression methods often force a trade-off: industry standard algorithms (e.g., LASzip) lack adaptability, while deep learning approaches suffer from prohibitive computational costs. This paper proposes LiZIP, a lightweight, near-lossless zero-drift compression framework based on neural predictive coding. By utilizing a compact Multi-Layer Perceptron (MLP) to predict point coordinates from local context, LiZIP efficiently encodes only the sparse residuals. We evaluate LiZIP on the NuScenes and Argoverse datasets, benchmarking against GZip, LASzip, and Google Draco (configured with 24-bit quantization to serve as a high-precision geometric baseline). Results demonstrate that LiZIP consistently achieves superior compression ratios across varying environments. The proposed system achieves a 7.5%-14.8% reduction in file size compared to the industry-standard LASzip and outperforms Google Draco by 8.8%-11.3% across diverse datasets. Furthermore, the system demonstrates generalization capabilities on the unseen Argoverse dataset without retraining. Against the general purpose GZip algorithm, LiZIP achieves a reduction of 38%-48%. This efficiency offers a distinct advantage for bandwidth constrained V2X applications and large scale cloud archival.
### Title:
          GTLR-GS: Geometry-Texture Aware LiDAR-Regularized 3D Gaussian Splatting for Realistic Scene Reconstruction
 - **Authors:** Yan Fang, Jianfei Ge, Jiangjian Xiao
 - **Subjects:** Subjects:
Graphics (cs.GR); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in 3D Gaussian Splatting (3DGS) have enabled real-time, photorealistic scene reconstruction. However, conventional 3DGS frameworks typically rely on sparse point clouds derived from Structure-from-Motion (SfM), which inherently suffer from scale ambiguity, limited geometric consistency, and strong view dependency due to the lack of geometric priors. In this work, a LiDAR-centric 3D Gaussian Splatting framework is proposed that explicitly incorporates metric geometric priors into the entire Gaussian optimization process. Instead of treating LiDAR data as a passive initialization source, 3DGS optimization is reformulated as a geometry-conditioned allocation and refinement problem under a fixed representational budget. Specifically, this work introduces (i) a geometry-texture-aware allocation strategy that selectively assigns Gaussian primitives to regions with high structural or appearance complexity, (ii) a curvature-adaptive refinement mechanism that dynamically guides Gaussian splitting toward geometrically complex areas during training, and (iii) a confidence-aware metric depth regularization that anchors the reconstructed geometry to absolute scale using LiDAR measurements while maintaining optimization stability. Extensive experiments on the ScanNet++ dataset and a custom real-world dataset validate the proposed approach. The results demonstrate state-of-the-art performance in metric-scale reconstruction with high geometric fidelity.
### Title:
          CCF: Complementary Collaborative Fusion for Domain Generalized Multi-Modal 3D Object Detection
 - **Authors:** Yuchen Wu, Kun Wang, Yining Pan, Na Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-modal fusion has emerged as a promising paradigm for accurate 3D object detection. However, performance degrades substantially when deployed in target domains different from training. In this work, focusing on dual-branch proposal-level detectors, we identify two factors that limit robust cross-domain generalization: 1) in challenging domains such as rain or nighttime, one modality may undergo severe degradation; 2) the LiDAR branch often dominates the detection process, leading to systematic underutilization of visual cues and vulnerability when point clouds are compromised. To address these challenges, we propose three components. First, Query-Decoupled Loss provides independent supervision for 2D-only, 3D-only, and fused queries, rebalancing gradient flow across modalities. Second, LiDAR-Guided Depth Prior augments 2D queries with instance-aware geometric priors through probabilistic fusion of image-predicted and LiDAR-derived depth distributions, improving their spatial initialization. Third, Complementary Cross-Modal Masking applies complementary spatial masks to the image and point cloud, encouraging queries from both modalities to compete within the fused decoder and thereby promoting adaptive fusion. Extensive experiments demonstrate substantial gains over state-of-the-art baselines while preserving source-domain performance. Code and models are publicly available at this https URL.
### Title:
          Edge Radar Material Classification Under Geometry Shifts
 - **Authors:** Jannik Hohmann, Dong Wang, Andreas Nüchter
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Material awareness can improve robotic navigation and interaction, particularly in conditions where cameras and LiDAR degrade. We present a lightweight mmWave radar material classification pipeline designed for ultra-low-power edge devices (TI IWRL6432), using compact range-bin intensity descriptors and a Multilayer Perceptron (MLP) for real-time inference. While the classifier reaches a macro-F1 of 94.2\% under the nominal training geometry, we observe a pronounced performance drop under realistic geometry shifts, including sensor height changes and small tilt angles. These perturbations induce systematic intensity scaling and angle-dependent radar cross section (RCS) effects, pushing features out of distribution and reducing macro-F1 to around 68.5\%. We analyze these failure modes and outline practical directions for improving robustness with normalization, geometry augmentation, and motion-aware features.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          UniQueR: Unified Query-based Feedforward 3D Reconstruction
 - **Authors:** Chensheng Peng, Quentin Herau, Jiezhi Yang, Yichen Xie, Yihan Hu, Wenzhao Zheng, Matthew Strong, Masayoshi Tomizuka, Wei Zhan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present UniQueR, a unified query-based feedforward framework for efficient and accurate 3D reconstruction from unposed images. Existing feedforward models such as DUSt3R, VGGT, and AnySplat typically predict per-pixel point maps or pixel-aligned Gaussians, which remain fundamentally 2.5D and limited to visible surfaces. In contrast, UniQueR formulates reconstruction as a sparse 3D query inference problem. Our model learns a compact set of 3D anchor points that act as explicit geometric queries, enabling the network to infer scene structure, including geometry in occluded regions--in a single forward pass. Each query encodes spatial and appearance priors directly in global 3D space (instead of per-frame camera space) and spawns a set of 3D Gaussians for differentiable rendering. By leveraging unified query interactions across multi-view features and a decoupled cross-attention design, UniQueR achieves strong geometric expressiveness while substantially reducing memory and computational cost. Experiments on Mip-NeRF 360 and VR-NeRF demonstrate that UniQueR surpasses state-of-the-art feedforward methods in both rendering quality and geometric accuracy, using an order of magnitude fewer primitives than dense alternatives.
## Keyword: mapping
### Title:
          Whether, Not Which: Mechanistic Interpretability Reveals Dissociable Affect Reception and Emotion Categorization in LLMs
 - **Authors:** Michael Keeman
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models appear to develop internal representations of emotion -- "emotion circuits," "emotion neurons," and structured emotional manifolds have been reported across multiple model families. But every study making these claims uses stimuli signalled by explicit emotion keywords, leaving a fundamental question unanswered: do these circuits detect genuine emotional meaning, or do they detect the word "devastated"? We present the first clinical validity test of emotion circuit claims using mechanistic interpretability methods grounded in clinical psychology -- clinical vignettes that evoke emotions through situational and behavioural cues alone, emotion keywords removed. Across six models (Llama-3.2-1B, Llama-3-8B, Gemma-2-9B; base and instruct variants), we apply four convergent mechanistic interpretability methods -- linear probing, causal activation patching, knockout experiments, and representational geometry -- and discover two dissociable emotion processing mechanisms. Affect reception -- detecting emotionally significant content -- operates with near-perfect accuracy (AUROC 1.000), consistent with early-layer saturation, and replicates across all six models. Emotion categorization -- mapping affect to specific emotion labels -- is partially keyword-dependent, dropping 1-7% without keywords and improving with scale. Causal activation patching confirms keyword-rich and keyword-free stimuli share representational space, transferring affective salience rather than emotion-category identity. These findings falsify the keyword-spotting hypothesis, establish a novel mechanistic dissociation, and introduce clinical stimulus methodology as a rigorous standard for testing emotion processing claims in large language models -- with direct implications for AI safety evaluation and alignment. All stimuli, code, and data are released for replication.
### Title:
          A Multi-Task Targeted Learning Framework for Lithium-Ion Battery State-of-Health and Remaining Useful Life
 - **Authors:** Chenhan Wang, Zhengyi Bao, Huipin Lin, Jiahao Nie, Chunxiang Zhu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurately predicting the state-of-health (SOH) and remaining useful life (RUL) of lithium-ion batteries is crucial for ensuring the safe and efficient operation of electric vehicles while minimizing associated risks. However, current deep learning methods are limited in their ability to selectively extract features and model time dependencies for these two parameters. Moreover, most existing methods rely on traditional recurrent neural networks, which have inherent shortcomings in long-term time-series modeling. To address these issues, this paper proposes a multi-task targeted learning framework for SOH and RUL prediction, which integrates multiple neural networks, including a multi-scale feature extraction module, an improved extended LSTM, and a dual-stream attention module. First, a feature extraction module with multi-scale CNNs is designed to capture detailed local battery decline patterns. Secondly, an improved extended LSTM network is employed to enhance the model's ability to retain long-term temporal information, thus improving temporal relationship modeling. Building on this, the dual-stream attention module-comprising polarized attention and sparse attention to selectively focus on key information relevant to SOH and RUL, respectively, by assigning higher weights to important features. Finally, a many-to-two mapping is achieved through the dual-task layer. To optimize the model's performance and reduce the need for manual hyperparameter tuning, the Hyperopt optimization algorithm is used. Extensive comparative experiments on battery aging datasets demonstrate that the proposed method reduces the average RMSE for SOH and RUL predictions by 111.3\% and 33.0\%, respectively, compared to traditional and state-of-the-art methods.
### Title:
          Unified Algebraic Absorption of Finite-Blocklength Penalties via Generalized Logarithmic Mapping
 - **Authors:** Hiroki Suyari
 - **Subjects:** Subjects:
Information Theory (cs.IT); Mathematical Physics (math-ph); Probability (math.PR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In finite-blocklength information theory, evaluating the fundamental limits of channel coding typically relies on normal approximations and Edgeworth expansions, which introduce additive polynomial corrections for skewness and higher-order moments. This paper proposes an alternative approach: rather than appending external error terms to a Gaussian baseline, we absorb these finite-length penalties using a generalized $q$-algebraic framework. By introducing a dynamic scaling law $1-q_n = \alpha n^{-1}$ for the tuning parameter, we prove that the $q$-generalized information density corresponds to macroscopic higher-order fluctuations. Specifically, by setting this scaling constant to $\alpha = T/(3V^2)$ (where $V$ is the varentropy and $T$ is the third central moment), our framework recovers the third-order coding limit, absorbing the $O(1)$ non-Gaussian penalty without relying on Hermite polynomials. Furthermore, we demonstrate that the $k$-th degree term of our algebraic expansion matches the $O(n^{1-k/2})$ asymptotic order of the $(k+1)$-th moment Edgeworth correction. This approach unifies classical probabilistic approximations within a single algebraic structure, establishing a mathematical connection between finite-blocklength analysis and generalized logarithmic mappings.
### Title:
          MapForest: A Modular Field Robotics System for Forest Mapping and Invasive Species Localization
 - **Authors:** Sandeep Zachariah, Francisco Yandun, Sachet Korada, Abhisesh Silwal
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monitoring and controlling invasive tree species across large forests, parks, and trail networks is challenging due to limited accessibility, reliance on manual scouting, and degraded under-canopy GNSS. We present MapForest, a modular field robotics system that transforms multi-modal sensor data into GIS-ready invasive-species maps. Our system features: (i) a compact, platform-agnostic sensing payload that can be rapidly mounted on UAV, bicycle, or backpack platforms, and (ii) a software pipeline comprising LiDAR-inertial mapping, image-based invasive-species detection, and georeferenced map generation. To ensure reliable operation in GNSS-intermittent environments, we enhance a LiDAR-inertial mapping backbone with covariance-aware GNSS factors and robust loss kernels. We train an object detector to detect the Tree-of-Heaven (Ailanthus altissima) from onboard RGB imagery and fuse detections with the reconstructed map to produce geospatial outputs suitable for downstream decision making. We collected a dataset spanning six sites across urban environments, parks, trails, and forests to evaluate individual system modules, and report end-to-end results on two sites containing Tree-of-Heaven. The enhanced mapping module achieved a trajectory deviation error of 1.95 m over a 1.2 km forest traversal, and the Tree-of-Heaven detector achieved an F1 score of 0.653. The datasets and associated tooling are released to support reproducible research in forest mapping and invasive-species monitoring.
### Title:
          Parallel OctoMapping: A Scalable Framework for Enhanced Path Planning in Autonomous Navigation
 - **Authors:** Yihui Mao, Tian Tan, Xuehui Shen, Warren E. Dixon, Rushikesh Kamalapurkar
 - **Subjects:** Subjects:
Robotics (cs.RO); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mapping is essential in robotics and autonomous systems because it provides the spatial foundation for path planning. Efficient mapping enables planning algorithms to generate reliable paths while ensuring safety and adapting in real time to complex environments. Fixed-resolution mapping methods often produce overly conservative obstacle representations that lead to suboptimal paths or planning failures in cluttered scenes. To address this issue, we introduce Parallel OctoMapping (POMP), an efficient OctoMap-based mapping technique that maximizes available free space and supports multi-threaded computation. To the best of our knowledge, POMP is the first method that, at a fixed occupancy-grid resolution, refines the representation of free space while preserving map fidelity and compatibility with existing search-based planners. It can therefore be integrated into existing planning pipelines, yielding higher pathfinding success rates and shorter path lengths, especially in cluttered environments, while substantially improving computational efficiency.
### Title:
          High Resolution Flood Extent Detection Using Deep Learning with Random Forest Derived Training Labels
 - **Authors:** Azizbek Nuriddinov, Ebrahim Ahmadisharaf, Mohammad Reza Alizadeh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Validation of flood models, used to support risk mitigation strategies, remains challenging due to limited observations during extreme events. High-frequency, high-resolution optical imagery (~3 m), such as PlanetScope, offers new opportunities for flood mapping, although applications remain limited by cloud cover and the lack of labeled training data during disasters. To address this, we develop a flood mapping framework that integrates PlanetScope optical imagery with topographic features using machine learning (ML) and deep learning (DL) algorithms. A Random Forest model was applied to expert-annotated flood masks to generate training labels for DL models, U-Net. Two U-Net models with ResNet18 backbone were trained using optical imagery only (4 bands) and optical imagery combined with Height Above Nearest Drainage (HAND) and topographic slope (6 bands). Hurricane Ida (September 2021), which caused catastrophic flooding across the eastern United States, including the New York City metropolitan area, was used as an example to evaluate the framework. Results demonstrate that the U-Net model with topographic features achieved very close performance to the optical-only configuration (F1=0.92 and IoU=0.85 by both modeling scenarios), indicating that HAND and slope provide only marginal value to inundation extent detection. The proposed framework offers a scalable and label-efficient approach for mapping inundation extent that enables modeling under data-scarce flood scenarios.
### Title:
          SCALE-Sim TPU: Validating and Extending SCALE-Sim for TPUs
 - **Authors:** Jingtian Dang, Ritik Raj, Changhai Man, Jianming Tong, Tushar Krishna
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Performance (cs.PF)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cycle-accurate simulators are widely used to study systolic accelerators, yet their accuracy and usability are often limited by weak validation against real hardware and poor integration with modern ML compiler stacks. This paper presents SCALE-Sim TPU, a validated and extended version of SCALE-Sim v3 for TPU-style accelerators. Specifically, we make three contributions: (1) We validate SCALE-Sim's systolic GEMM model against measurements on Google TPU v4 and show that simulated cycle counts exhibit a strong linear correlation with hardware latency, enabling a simple cycle-to-latency mapping. (2) We introduce lightweight learned latency models for non-systolic elementwise operations, achieving median relative errors below 3 percent using only tensor size and shape, substantially improving end-to-end latency estimation. (3) We integrate a StableHLO-based frontend that allows workloads from modern ML frameworks such as JAX and PyTorch to be simulated directly via a unified compiler IR. Together, these contributions improve the fidelity, coverage, and practicality of cycle-accurate simulation for whole-model performance analysis on TPUs.
### Title:
          L2O-CCG: Adversarial Learning with Set Generalization for Adaptive Robust Optimization
 - **Authors:** Zhiyi Zhou, Ján Drgoňa, Yury Dvorkin
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The adversarial subproblem in two-stage adaptive robust optimization (ARO), which identifies the worst-case uncertainty realization, is a major computational bottleneck. This difficulty is exacerbated when the recourse value function is non-concave and the uncertainty set shifts across applications. Existing approaches typically exploit specific structural assumptions on the value function or the uncertainty set geometry to reformulate this subproblem, but degrade when these assumptions are violated or the geometry changes at deployment. To address this challenge, we propose L2O-CCG, a bi-level framework that enables the integration of structure-aware adversarial solvers within the constraint-and-column generation (CCG) algorithm. As one instantiation, we develop a generalizable adversarial learning method, which replaces solver-based adversarial search with a learned proximal gradient optimizer that can generalize across uncertainty set geometries without retraining. Here, an inner-level neural network approximates the recourse value function from offline data, while an outer-level pre-trained mapping generates iteration-dependent step sizes for a proximal gradient scheme. We also establish out-of-distribution convergence bounds under uncertainty set parameter shifts, showing how the trajectory deviation of the learned optimizer is bounded by the uncertainty set shift. We illustrate performance of the L2O-CCG method on a building HVAC management task.
### Title:
          A vision-language model and platform for temporally mapping surgery from video
 - **Authors:** Dani Kiyasseh
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mapping surgery is fundamental to developing operative guidelines and enabling autonomous robotic surgery. Recent advances in artificial intelligence (AI) have shown promise in mapping the behaviour of surgeons from videos, yet current models remain narrow in scope, capturing limited behavioural components within single procedures, and offer limited translational value, as they remain inaccessible to practising surgeons. Here we introduce Halsted, a vision-language model trained on the Halsted Surgical Atlas (HSA), one of the most comprehensive annotated video libraries grown through an iterative self-labelling framework and encompassing over 650,000 videos across eight surgical specialties. To facilitate benchmarking, we publicly release HSA-27k, a subset of the Halsted Surgical Atlas. Halsted surpasses previous state-of-the-art models in mapping surgical activity while offering greater comprehensiveness and computational efficiency. To bridge the longstanding translational gap of surgical AI, we develop the Halsted web platform (this https URL) to provide surgeons anywhere in the world with the previously-unavailable capability of automatically mapping their own procedures within minutes. By standardizing unstructured surgical video data and making these capabilities directly accessible to surgeons, our work brings surgical AI closer to clinical deployment and helps pave the way toward autonomous robotic surgery.
### Title:
          A Foundation Model for Instruction-Conditioned In-Context Time Series Tasks
 - **Authors:** Anish Saha, Konstantin Shmakov
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context learning (ICL) allows a model to adapt at inference time by conditioning on examples rather than updating parameters. Existing time-series foundation models use implicit positional context, retrieval, or task-specific objectives, but rarely explicit instruction-conditioned demonstrations. We present a foundation model for instruction-conditioned in-context time-series tasks based on a quantile-regression T5 encoder-decoder. Historical examples and queries are encoded with a structured tokenization scheme that marks target series, covariates, context, and task-specific future information. A hierarchical Transformer with per-example encoding, example-level fusion, and cross-example attention conditions decoding on demonstration pairs, enabling forecasting and related tasks without task-specific fine-tuning. We train on large-scale real and synthetic time series using supervised forecasting plus self-supervised tasks, including imputation, reconstruction, classification, anomaly detection, and source demixing. This multi-task training learns a distribution over task mappings and improves adaptation to local structure at inference time. Across diverse datasets, frequencies, and horizons, our method outperforms strong foundation baselines on point and probabilistic forecasting benchmarks, including fev-bench and GIFT-Eval, while remaining competitive on classification and anomaly detection.
### Title:
          Learning to Trust: How Humans Mentally Recalibrate AI Confidence Signals
 - **Authors:** ZhaoBin Li, Mark Steyvers
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Productive human-AI collaboration requires appropriate reliance, yet contemporary AI systems are often miscalibrated, exhibiting systematic overconfidence or underconfidence. We investigate whether humans can learn to mentally recalibrate AI confidence signals through repeated experience. In a behavioral experiment (N = 200), participants predicted the AI's correctness across four AI calibration conditions: standard, overconfidence, underconfidence, and a counterintuitive "reverse confidence" mapping. Results demonstrate robust learning across all conditions, with participants significantly improving their accuracy, discrimination, and calibration alignment over 50 trials. We present a computational model utilizing a linear-in-log-odds (LLO) transformation and a Rescorla-Wagner learning rule to explain these dynamics. The model reveals that humans adapt by updating their baseline trust and confidence sensitivity, using asymmetric learning rates to prioritize the most informative errors. While humans can compensate for monotonic miscalibration, we identify a significant boundary in the reverse confidence scenario, where a substantial proportion of participants struggled to override initial inductive biases. These findings provide a mechanistic account of how humans adapt their trust in AI confidence signals through experience.
### Title:
          When Data Protection Fails to Protect: Law, Power, and Postcolonial Governance in Bangladesh
 - **Authors:** Pratyasha Saha, Anita Say Chan, Sharifa Sultana
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rapid digitization across government services, financial platforms, and telecommunications has intensified the collection and processing of large scale personal data in Bangladesh. In response, the state has introduced multiple regulatory instruments, including the Personal Data Protection Ordinance, the Cyber Security Ordinance, and the National Data Governance Ordinance in 2025. While these initiatives signal an emerging legal regime for data protection, little scholarly work examines how these frameworks operate collectively in practice. This paper presents a legal and institutional analysis of Bangladeshs emerging data protection regime through a systematic review of these three ordinances. Through this review, the paper provides an integrated mapping of Bangladeshs evolving data protection framework and identifies key legal and institutional barriers that undermine the effective protection of citizens personal data. Our findings reveal that this emerging regime is constrained by limited institutional independence, uneven regulatory capacity, and the misaligned legal assumption of individualized, autonomous data subjects. Furthermore, these frameworks invisibilize prevalent sociotechnical layers, such as informal data flows and mediated access via human bridges, rendering formal protections difficult to operationalize. This paper contributes to HCI scholarship by expanding the concept of data protection as a complex sociotechnical design problem shaped by the informal infrastructures of the Global South.
### Title:
          MAGICIAN: Efficient Long-Term Planning with Imagined Gaussians for Active Mapping
 - **Authors:** Shiyao Li, Antoine Guédon, Shizhe Chen, Vincent Lepetit
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Active mapping aims to determine how an agent should move to efficiently reconstruct an unknown environment. Most existing approaches rely on greedy next-best-view prediction, resulting in inefficient exploration and incomplete scene reconstruction. To address this limitation, we introduce MAGICIAN, a novel long-term planning framework that maximizes accumulated surface coverage gain through Imagined Gaussians, a scene representation derived from a pre-trained occupancy network with strong structural priors. This representation enables efficient computation of coverage gain for any novel viewpoint via fast volumetric rendering, allowing its integration into a tree-search algorithm for long-horizon planning. We update Imagined Gaussians and refine the planned trajectory in a closed-loop manner. Our method achieves state-of-the-art performance across indoor and outdoor benchmarks with varying action spaces, demonstrating the critical advantage of long-term planning in active mapping.
### Title:
          Large-Scale Avalanche Mapping from SAR Images with Deep Learning-based Change Detection
 - **Authors:** Mattia Gatti, Alberto Mariani, Ignazio Gallo, Fabiano Monti
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate change detection from satellite imagery is essential for monitoring rapid mass-movement hazards such as snow avalanches, which increasingly threaten human life, infrastructure, and ecosystems due to their rising frequency and intensity. This study presents a systematic investigation of large-scale avalanche mapping through bi-temporal change detection using Sentinel-1 synthetic aperture radar (SAR) imagery. Extensive experiments across multiple alpine ecoregions with manually validated avalanche inventories show that treating the task as a unimodal change detection problem, relying solely on pre- and post-event SAR images, achieves the most consistent performance. The proposed end-to-end pipeline achieves an F1-score of 0.8061 in a conservative (F1-optimized) configuration and attains an F2-score of 0.8414 with 80.36% avalanche-polygon hit rate under a less conservative, recall-oriented (F2-optimized) tuning. These results highlight the trade-off between precision and completeness and demonstrate how threshold adjustment can improve the detection of smaller or marginal avalanches. The release of the annotated multi-region dataset establishes a reproducible benchmark for SAR-based avalanche mapping.
### Title:
          Variable-Resolution Virtual Maps for Autonomous Exploration with Unmanned Surface Vehicles (USVs)
 - **Authors:** Ye Li, Yewei Huang, Wenlong GaoZhang, Alberto Quattrini Li, Brendan Englot, Yuanchang Liu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous exploration by unmanned surface vehicles (USVs) in near-shore waters requires reliable localisation and consistent mapping over extended areas, but this is challenged by GNSS degradation, environment-induced localisation uncertainty, and limited on-board computation. Virtual map-based methods explicitly model localisation and mapping uncertainty by tightly coupling factor-graph SLAM with a map uncertainty criterion. However, their storage and computational costs scale poorly with fixed-resolution workspace discretisations, leading to inefficiency in large near-shore environments. Moreover, overvaluing feature-sparse open-water regions can increase the risk of SLAM failure as a result of imbalance between exploration and exploitation. To address these limitations, we propose a Variable-Resolution Virtual Map (VRVM), a computationally efficient method for representing map uncertainty using bivariate Gaussian virtual landmarks placed in the cells of an adaptive quadtree. The adaptive quadtree enables an area-weighted uncertainty representation that keeps coarse, far-field virtual landmarks deliberately uncertain while allocating higher resolution to information-dense regions, and reduces the sensitivity of the map valuation to local refinements of the tree. An expectation-maximisation (EM) planner is adopted to evaluate pose and map uncertainty along frontiers using the VRVM, balancing exploration and exploitation. We evaluate VRVM against several state-of-the-art exploration algorithms in the VRX Gazebo simulator, using a realistic marina environment across different testing scenarios with an increasing level of exploration difficulty. The results indicate that our method offers safer behaviour and better utilisation of on-board computation in GNSS-degraded near-shore environments.
### Title:
          Vision-based Deep Learning Analysis of Unordered Biomedical Tabular Datasets via Optimal Spatial Cartography
 - **Authors:** Sakib Mostafa, Tarik Massoud, Maximilian Diehn, Lei Xing, Md Tauhidul Islam
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tabular data are central to biomedical research, from liquid biopsy and bulk and single-cell transcriptomics to electronic health records and phenotypic profiling. Unlike images or sequences, however, tabular datasets lack intrinsic spatial organization: features are treated as unordered dimensions, and their relationships must be inferred implicitly by the model. This limits the ability of vision architectures to exploit local structure and higher-order feature interactions in non-spatial biomedical data. Here we introduce Dynamic Feature Mapping (Dynomap), an end-to-end deep learning framework that learns a task-optimized spatial topology of features directly from data. Dynomap jointly optimizes feature placement and prediction through a fully differentiable rendering mechanism, without relying on heuristics, predefined groupings, or external priors. By transforming high-dimensional tabular vectors into learned feature maps, Dynomap enables vision-based models to operate effectively on unordered biomedical inputs. Across multiple clinical and biological datasets, Dynomap consistently outperformed classical machine learning, modern deep tabular models, and existing vector-to-image approaches. In liquid biopsy data, Dynomap organized clinically relevant gene signatures into coherent spatial patterns and improved multiclass cancer subtype prediction accuracy by up to 18%. In a Parkinson disease voice dataset, it clustered disease-associated acoustic descriptors and improved accuracy by up to 8%. Similar gains and interpretable feature organization were observed in additional biomedical datasets. These results establish Dynomap as a general strategy for bridging tabular and vision-based deep learning and for uncovering structured, clinically relevant patterns in high-dimensional biomedical data.
### Title:
          WiFi2Cap: Semantic Action Captioning from Wi-Fi CSI via Limb-Level Semantic Alignment
 - **Authors:** Tzu-Ti Wei, Chu-Yu Huang, Yu-Chee Tseng, Jen-Jee Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Privacy-preserving semantic understanding of human activities is important for indoor sensing, yet existing Wi-Fi CSI-based systems mainly focus on pose estimation or predefined action classification rather than fine-grained language generation. Mapping CSI to natural-language descriptions remains challenging because of the semantic gap between wireless signals and language and direction-sensitive ambiguities such as left/right limb confusion. We propose WiFi2Cap, a three-stage framework for generating action captions directly from Wi-Fi CSI. A vision-language teacher learns transferable supervision from synchronized video-text pairs, and a CSI student is aligned to the teacher's visual space and text embeddings. To improve direction-sensitive captioning, we introduce a Mirror-Consistency Loss that reduces mirrored-action and left-right ambiguities during cross-modal alignment. A prefix-tuned language model then generates action descriptions from CSI embeddings. We also introduce the WiFi2Cap Dataset, a synchronized CSI-RGB-sentence benchmark for semantic captioning from Wi-Fi signals. Experimental results show that WiFi2Cap consistently outperforms baseline methods on BLEU-4, METEOR, ROUGE-L, CIDEr, and SPICE, demonstrating effective privacy-friendly semantic sensing.
### Title:
          Rank-Aware Resource Scheduling for Tightly-Coupled MPI Workloads on Kubernetes
 - **Authors:** Tianfang Xie
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fully provisioned Message Passing Interface (MPI) parallelism achieves near-optimal wall-clock time for Computational Fluid Dynamics (CFD) solvers. This work addresses a complementary question for shared, cloud-managed clusters: can fine-grained CPU provisioning reduce resource reservation of low-load subdomains, improving cluster packing efficiency without unacceptably degrading performance? We propose rank-aware resource scheduling on Kubernetes, mapping each MPI rank to a pod whose CPU request is proportional to its subdomain cell count. We also demonstrate In-Place Pod Vertical Scaling (Kubernetes v1.35 GA) for mid-simulation CPU adjustment without pod restart. Three findings emerge. First, hard CPU limits via the Linux CFS bandwidth controller cause 78x slowdown through cascading stalls at MPI_Allreduce barriers; requests-only allocation eliminates throttling entirely. Second, on non-burstable this http URL instances, concentric decomposition with equal CPU is 19% faster than the Scotch baseline, while adding proportional CPU yields a further 3% improvement. Third, at 16 MPI ranks on 101K-cell meshes, proportional allocation is 20% faster than equal allocation while reducing sparse-subdomain provisioned CPU by 82%, freeing 6.5 vCPU of scheduling headroom. Experiments are conducted on AWS EC2 this http URL clusters (4-16 ranks) running k3s v1.35. All scripts and data are released as open source.
### Title:
          A Video Steganography for H.265/HEVC Based on Multiple CU Size and Block Structure Distortion
 - **Authors:** Xiang Zhang, Wen Jiang, Fei Peng, Wenbin Huang, Ziqiang Li, Zhangjie Fu
 - **Subjects:** Subjects:
Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video steganography based on block structure, which embeds secret information by modifying Coding Unit (CU) block structure of I-frames, is currently a research hotspot. However, the existing algorithms still suffer from the limitation of poor anti-steganalysis, which results from significantly disrupting the original CU block structure after embedding secret information. To overcome this limitation, this paper proposes a video steganography algorithm based on multiple CU size and block structure distortion. Our algorithm introduces three key innovations: 1) a CU Block Structure Stability Metric (CBSSM) based on CU block structure restoration phenomenon to reveal the reasons for the insufficient anti-steganalysis performance of current algorithms. 2) a novel mapping rule based on multiple CU size to reduce block structure change and enhance embedding capacity. 3) a three-level distortion function based on block structure to better guide the secret information embedding. This triple strategy ensures that the secret information embedding minimizes disruption to the original CU block structure while concealing it primarily in areas where block structure changes occur after recompression, ultimately enhancing the algorithm's anti-steganalysis. Comprehensive experimental results highlight the crucial role of the proposed CBSSM in evaluating anti-steganalysis performance even at a low embedding rate. Meanwhile, compared to State-of-the-Art video steganography algorithms based on block structure, our proposed steganography algorithm exhibits greater anti-steganalysis, as well as further improving visual quality, bitrate increase ratio and embedding capacity.
### Title:
          Dynamical Systems Theory Behind a Hierarchical Reasoning Model
 - **Authors:** Vasiliy A. Es'kin, Mikhail E. Smorkalov
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Dynamical Systems (math.DS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current large language models (LLMs) primarily rely on linear sequence generation and massive parameter counts, yet they severely struggle with complex algorithmic reasoning. While recent reasoning architectures, such as the Hierarchical Reasoning Model (HRM) and Tiny Recursive Model (TRM), demonstrate that compact recursive networks can tackle these tasks, their training dynamics often lack rigorous mathematical guarantees, leading to instability and representational collapse. We propose the Contraction Mapping Model (CMM), a novel architecture that reformulates discrete recursive reasoning into continuous Neural Ordinary and Stochastic Differential Equations (NODEs/NSDEs). By explicitly enforcing the convergence of the latent phase point to a stable equilibrium state and mitigating feature collapse with a hyperspherical repulsion loss, the CMM provides a mathematically grounded and highly stable reasoning engine. On the Sudoku-Extreme benchmark, a 5M-parameter CMM achieves a state-of-the-art accuracy of 93.7 %, outperforming the 27M-parameter HRM (55.0 %) and 5M-parameter TRM (87.4 %). Remarkably, even when aggressively compressed to an ultra-tiny footprint of just 0.26M parameters, the CMM retains robust predictive power, achieving 85.4 % on Sudoku-Extreme and 82.2 % on the Maze benchmark. These results establish a new frontier for extreme parameter efficiency, proving that mathematically rigorous latent dynamics can effectively replace brute-force scaling in artificial reasoning.
### Title:
          AgentRAE: Remote Action Execution through Notification-based Visual Backdoors against Screenshots-based Mobile GUI Agents
 - **Authors:** Yutao Luo, Haotian Zhu, Shuchao Pang, Zhigang Lu, Tian Dong, Yongbin Zhou, Minhui Xue
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid adoption of mobile graphical user interface (GUI) agents, which autonomously control applications and operating systems (OS), exposes new system-level attack surfaces. Existing backdoors against web GUI agents and general GenAI models rely on environmental injection or deceptive pop-ups to mislead the agent operation. However, these techniques do not work on screenshots-based mobile GUI agents due to the challenges of restricted trigger design spaces, OS background interference, and conflicts in multiple trigger-action mappings. We propose AgentRAE, a novel backdoor attack capable of inducing Remote Action Execution in mobile GUI agents using visually natural triggers (e.g., benign app icons in notifications). To address the underfitting caused by natural triggers and achieve accurate multi-target action redirection, we design a novel two-stage pipeline that first enhances the agent's sensitivity to subtle iconographic differences via contrastive learning, and then associates each trigger with a specific mobile GUI agent action through a backdoor post-training. Our extensive evaluation reveals that the proposed backdoor preserves clean performance with an attack success rate of over 90% across ten mobile operations. Furthermore, it is hard to visibly detect the benign-looking triggers and circumvents eight representative state-of-the-art defenses. These results expose an overlooked backdoor vector in mobile GUI agents, underscoring the need for defenses that scrutinize notification-conditioned behaviors and internal agent representations.
### Title:
          YOLOv10 with Kolmogorov-Arnold networks and vision-language foundation models for interpretable object detection and trustworthy multimodal AI in computer vision perception
 - **Authors:** Marios Impraimakis, Daniel Vazquez, Feiyu Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computation and Language (cs.CL); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The interpretable object detection capabilities of a novel Kolmogorov-Arnold network framework are examined here. The approach refers to a key limitation in computer vision for autonomous vehicles perception, and beyond. These systems offer limited transparency regarding the reliability of their confidence scores in visually degraded or ambiguous scenes. To address this limitation, a Kolmogorov-Arnold network is employed as an interpretable post-hoc surrogate to model the trustworthiness of the You Only Look Once (Yolov10) detections using seven geometric and semantic features. The additive spline-based structure of the Kolmogorov-Arnold network enables direct visualisation of each feature's influence. This produces smooth and transparent functional mappings that reveal when the model's confidence is well supported and when it is unreliable. Experiments on both Common Objects in Context (COCO), and images from the University of Bath campus demonstrate that the framework accurately identifies low-trust predictions under blur, occlusion, or low texture. This provides actionable insights for filtering, review, or downstream risk mitigation. Furthermore, a bootstrapped language-image (BLIP) foundation model generates descriptive captions of each scene. This tool enables a lightweight multimodal interface without affecting the interpretability layer. The resulting system delivers interpretable object detection with trustworthy confidence estimates. It offers a powerful tool for transparent and practical perception component for autonomous and multimodal artificial intelligence applications.
### Title:
          AirSimAG: A High-Fidelity Simulation Platform for Air-Ground Collaborative Robotics
 - **Authors:** Yangjie Cui, Xin Dong, Boyang Gao, Jinwu Xiang, Daochun Li, Zhan Tu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As spatial intelligence continues to evolve, heterogeneous multi-agent systems-particularly the collaboration between Unmanned Aerial Vehicles (UAVs) and Unmanned Ground Vehicles (UGVs), have demonstrated strong potential in complex applications such as search and rescue, urban surveillance, and environmental monitoring. However, existing simulation platforms are primarily designed for single-agent dynamics and lack dedicated frameworks for interactive air-ground collaborative simulation. In this paper, we present AirsimAG, a high-fidelity air-ground collaborative simulation platform built upon an extensively customized AirSim framework. The platform enables synchronized multi-agent simulation and supports heterogeneous sensing and control interfaces for UAV-UGV systems. To demonstrate its capabilities, we design a set of representative air-ground collaborative tasks, including mapping, planning, tracking, formation, and exploration. We further provide quantitative analyses based on these tasks to illustrate the platform effectiveness in supporting multi-agent coordination and cross-modal data consistency. The AirsimAG simulation platform is publicly available at this https URL.
### Title:
          Active Robotic Perception for Disease Detection and Mapping in Apple Trees
 - **Authors:** Hayden Feddock, Francisco Yandun, Srđan Aćimović, Abhisesh Silwal
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale orchard production requires timely and precise disease monitoring, yet routine manual scouting is labor-intensive and financially impractical at the scale of modern operations. As a result, disease outbreaks are often detected late and tracked at coarse spatial resolutions, typically at the orchard-block level. We present an autonomous mobile active perception system for targeted disease detection and mapping in dormant apple trees, demonstrated on one of the most devastating diseases affecting apple today -- fire blight. The system integrates flash-illuminated stereo RGB sensing, real-time depth estimation, instance-level segmentation, and confidence-aware semantic 3D mapping to achieve precise localization of disease symptoms. Semantic predictions are fused into the volumetric occupancy map representation enabling the tracking of both occupancy and per-voxel semantic confidence, building actionable spatial maps for growers. To actively refine observations within complex canopies, we evaluate three viewpoint planning strategies within a unified perception-action loop: a deterministic geometric baseline, a volumetric next-best-view planner that maximizes unknown-space reduction, and a semantic next-best-view planner that prioritizes low-confidence symptomatic regions. Experiments on a fabricated lab tree and five simulated symptomatic trees demonstrate reliable symptom localization and mapping as a precursor to a field evaluation. In simulation, the semantic planner achieves the highest F1 score (0.6106) after 30 viewpoints, while the volumetric planner achieves the highest ROI coverage (85.82\%). In the lab setting, the semantic planner attains the highest final F1 (0.9058), with both next-best-view planners substantially improving coverage over the baseline.
### Title:
          PHANTOM Hand
 - **Authors:** Teng Yan, Jiongxu Chen, Qixiang Hua, Yue Yu, Zihang Wang, Yaohua Liu, Bingzhuo Zhong
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tendon-driven underactuated hands excel in adaptive grasping but often suffer from kinematic unpredictability and highly non-linear force transmission. This ambiguity limits their ability to perform precise free-motion shaping and deliver reliable payloads for complex manipulation tasks. To address this, we introduce the PHANTOM Hand (Hybrid Precision-Augmented Compliance): a modular, 1:1 human-scale system featuring 6 actuators and 15 degrees of freedom (DoFs). We propose a unified framework that bridges the gap between precise analytic shaping and robust compliant grasping. By deriving a sparse mapping from physical geometry and integrating a mechanics-based compensation model, we effectively suppress kinematic drift caused by spring counter-tension and tendon elasticity. This approach achieves sub-degree kinematic reproducibility for free-motion planning while retaining the inherent mechanical compliance required for stable physical interaction. Experimental validation confirms the system's capabilities through (1) kinematic analysis verifying sub-degree global accuracy across the workspace; (2) static expressibility tests demonstrating complex hand gestures; (3) diverse grasping experiments covering power, precision, and tool-use categories; and (4) quantitative fingertip force characterization. The results demonstrate that the PHANTOM hand successfully combines analytic kinematic precision with continuous, predictable force output, significantly expanding the payload and dexterity of underactuated hands. To drive the development of the underactuated manipulation ecosystem, all hardware designs and control scripts are fully open-sourced for community engagement.
### Title:
          ViKey: Enhancing Temporal Understanding in Videos via Visual Prompting
 - **Authors:** Yeonkyung Lee, Dayun Ju, Youngmin Kim, Seil Kang, Seong Jae Hwang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advancements in Video Large Language Models (VideoLLMs) have enabled strong performance across diverse multimodal video tasks. To reduce the high computational cost of processing dense video frames, efficiency-oriented methods such as frame selection have been widely adopted. While effective at minimizing redundancy, these methods often cause notable performance drops on tasks requiring temporal reasoning. Unlike humans, who can infer event progression from sparse visual cues, VideoLLMs frequently misinterpret temporal relations when intermediate frames are omitted. To address this limitation, we explore visual prompting (VP) as a lightweight yet effective way to enhance temporal understanding in VideoLLMs. Our analysis reveals that simply annotating each frame with explicit ordinal information helps the model perceive temporal continuity. This visual cue also supports frame-level referencing and mitigates positional ambiguity within a sparsely sampled sequence. Building on these insights, we introduce ViKey, a training-free framework that combines VP with a lightweight Keyword-Frame Mapping (KFM) module. KFM leverages frame indices as dictionary-like keys to link textual cues to the most relevant frames, providing explicit temporal anchors during inference. Despite its simplicity, our approach substantially improves temporal reasoning and, on some datasets, preserves dense-frame baseline performance with as few as 20% of frames.
### Title:
          A Latency Coding Framework for Deep Spiking Neural Networks with Ultra-Low Latency
 - **Authors:** Yi Lu, Jianhao Ding, Zhaofei Yu
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking neural networks (SNNs) offer a biologically inspired computing paradigm with significant potential for energy-efficient neural processing. Among neural coding schemes of SNNs, Time-To-First-Spike (TTFS) coding, which encodes information through the precise timing of a neuron's first spike, provides exceptional energy efficiency and biological plausibility. Despite its theoretical advantages, existing TTFS models lack efficient training methods, suffering from high inference latency and limited performance. In this work, we present a comprehensive framework, which enables the efficient training of deep TTFS-coded SNNs by employing backpropagation throuh time (BPTT) algorithm. We name the generalized TTFS coding method in our framework as latency coding. The framework includes: (1) a latency encoding (LE) module with feature extraction and straight-through estimators to address severe information loss in direct intensity-to-latency mapping and ensure smooth gradient flow; (2) relaxation of the strict single-spike constraint of traditional TTFS, allowing neurons of intermediate layers to fire multiple times to mitigating gradient vanishing in deep networks; (3) a temporal adaptive decision (TAD) loss function that dynamically weights supervision signals based on sample-dependent confidence, resolving the incompatibility between latency coding and standard cross-entropy loss. Experimental results demonstrate that our method achieves state-of-the-art accuracy in comparison to existing TTFS-coded SNNs with ultra-low inference latency and superior energy efficiency. The framework also demonstrates improved robustness against input corruptions. Our study investigates the characteristics and potential of latency coding in scenarios demanding rapid response, providing valuable insights for further exploiting the temporal learning capabilities of SNNs.
### Title:
          Canonical Byte-String Encoding for Finite-Ring Cryptosystems
 - **Authors:** Kyrylo Riabov, Serhii Kryvyi
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Information Theory (cs.IT)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ring-mapping protocols need a canonical byte-to-residue layer before any algebraic encryption step can begin. This paper isolates that layer and presents the base-m length codec, a canonical map from byte strings of length less than 2^64 to lists of residues modulo m. The encoder builds on and adapts an rANS-based system proposed by Duda. Decoding is exact for all moduli satisfying the paper's parameter bounds. Because the encoding carries the byte length in its fixed-width header, decoding is also tolerant to appended valid suffix digits. The paper is accompanied by a Rust implementation of the described protocol, a Lean 4 formalization of the abstract codec with machine-checked proofs, and performance benchmarks. The Lean 4 formalization establishes fixed-width prefix inversion and payload-state bounds below 2^64, stream-level roundtrip correctness, and that every emitted symbol is a valid residue modulo m. We conclude with a complexity analysis and a discussion of practical considerations arising in real-world use of the codec.
## Keyword: localization
### Title:
          SOUPLE: Enhancing Audio-Visual Localization and Segmentation with Learnable Prompt Contexts
 - **Authors:** Khanh Binh Nguyen, Chae Jung Park
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale pre-trained image-text models exhibit robust multimodal representations, yet applying the Contrastive Language-Image Pre-training (CLIP) model to audio-visual localization remains challenging. Replacing the classification token ([CLS]) with an audio-embedded token ([V_A]) struggles to capture semantic cues, and the prompt "a photo of a [V_A]" fails to establish meaningful connections between audio embeddings and context tokens. To address these issues, we propose Sound-aware Prompt Learning (SOUPLE), which replaces fixed prompts with learnable context tokens. These tokens incorporate visual features to generate conditional context for a mask decoder, effectively bridging semantic correspondence between audio and visual inputs. Experiments on VGGSound, SoundNet, and AVSBench demonstrate that SOUPLE improves localization and segmentation performance.
### Title:
          ENC-Bench: A Benchmark for Evaluating Multimodal Large Language Models in Electronic Navigational Chart Understanding
 - **Authors:** Ao Cheng, Xingming Li, Xuanyu Ji, Xixiang He, Qiyao Sun, Chunping Qiu, Runke Huang, Qingyong Hu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Electronic Navigational Charts (ENCs) are the safety-critical backbone of modern maritime navigation, yet it remains unclear whether multimodal large language models (MLLMs) can reliably interpret them. Unlike natural images or conventional charts, ENCs encode regulations, bathymetry, and route constraints via standardized vector symbols, scale-dependent rendering, and precise geometric structure -- requiring specialized maritime expertise for interpretation. We introduce ENC-Bench, the first benchmark dedicated to professional ENC understanding. ENC-Bench contains 20,490 expert-validated samples from 840 authentic National Oceanic and Atmospheric Administration (NOAA) ENCs, organized into a three-level hierarchy: Perception (symbol and feature recognition), Spatial Reasoning (coordinate localization, bearing, distance), and Maritime Decision-Making (route legality, safety assessment, emergency planning under multiple constraints). All samples are generated from raw S-57 data through a calibrated vector-to-image pipeline with automated consistency checks and expert review. We evaluate 10 state-of-the-art MLLMs such as GPT-4o, Gemini 2.5, Qwen3-VL, InternVL-3, and GLM-4.5V, under a unified zero-shot protocol. The best model achieves only 47.88% accuracy, with systematic challenges in symbolic grounding, spatial computation, multi-constraint reasoning, and robustness to lighting and scale variations. By establishing the first rigorous ENC benchmark, we open a new research frontier at the intersection of specialized symbolic reasoning and safety-critical AI, providing essential infrastructure for advancing MLLMs toward professional maritime applications.
### Title:
          It Takes Two: A Duet of Periodicity and Directionality for Burst Flicker Removal
 - **Authors:** Lishen Qu, Shihao Zhou, Jie Liang, Hui Zeng, Lei Zhang, Jufeng Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Flicker artifacts, arising from unstable illumination and row-wise exposure inconsistencies, pose a significant challenge in short-exposure photography, severely degrading image quality. Unlike typical artifacts, e.g., noise and low-light, flicker is a structured degradation with specific spatial-temporal patterns, which are not accounted for in current generic restoration frameworks, leading to suboptimal flicker suppression and ghosting artifacts. In this work, we reveal that flicker artifacts exhibit two intrinsic characteristics, periodicity and directionality, and propose Flickerformer, a transformer-based architecture that effectively removes flicker without introducing ghosting. Specifically, Flickerformer comprises three key components: a phase-based fusion module (PFM), an autocorrelation feed-forward network (AFFN), and a wavelet-based directional attention module (WDAM). Based on the periodicity, PFM performs inter-frame phase correlation to adaptively aggregate burst features, while AFFN exploits intra-frame structural regularities through autocorrelation, jointly enhancing the network's ability to perceive spatially recurring patterns. Moreover, motivated by the directionality of flicker artifacts, WDAM leverages high-frequency variations in the wavelet domain to guide the restoration of low-frequency dark regions, yielding precise localization of flicker artifacts. Extensive experiments demonstrate that Flickerformer outperforms state-of-the-art approaches in both quantitative metrics and visual quality. The source code is available at this https URL.
### Title:
          TDATR: Improving End-to-End Table Recognition via Table Detail-Aware Learning and Cell-Level Visual Alignment
 - **Authors:** Chunxia Qin, Chenyu Liu, Pengcheng Xia, Jun Du, Baocai Yin, Bing Yin, Cong Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Tables are pervasive in diverse documents, making table recognition (TR) a fundamental task in document analysis. Existing modular TR pipelines separately model table structure and content, leading to suboptimal integration and complex workflows. End-to-end approaches rely heavily on large-scale TR data and struggle in data-constrained scenarios. To address these issues, we propose TDATR (Table Detail-Aware Table Recognition) improves end-to-end TR through table detail-aware learning and cell-level visual alignment. TDATR adopts a ``perceive-then-fuse'' strategy. The model first performs table detail-aware learning to jointly perceive table structure and content through multiple structure understanding and content recognition tasks designed under a language modeling paradigm. These tasks can naturally leverage document data from diverse scenarios to enhance model robustness. The model then integrates implicit table details to generate structured HTML outputs, enabling more efficient TR modeling when trained with limited data. Furthermore, we design a structure-guided cell localization module integrated into the end-to-end TR framework, which efficiently locates cell and strengthens vision-language alignment. It enhances the interpretability and accuracy of TR. We achieve state-of-the-art or highly competitive performance on seven benchmarks without dataset-specific fine-tuning.
### Title:
          URA-Net: Uncertainty-Integrated Anomaly Perception and Restoration Attention Network for Unsupervised Anomaly Detection
 - **Authors:** Wei Luo, Peng Xing, Yunkang Cao, Haiming Yao, Weiming Shen, Zechao Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Unsupervised anomaly detection plays a pivotal role in industrial defect inspection and medical image analysis, with most methods relying on the reconstruction framework. However, these methods may suffer from over-generalization, enabling them to reconstruct anomalies well, which leads to poor detection performance. To address this issue, instead of focusing solely on normality reconstruction, we propose an innovative Uncertainty-Integrated Anomaly Perception and Restoration Attention Network (URA-Net), which explicitly restores abnormal patterns to their corresponding normality. First, unlike traditional image reconstruction methods, we utilize a pre-trained convolutional neural network to extract multi-level semantic features as the reconstruction target. To assist the URA-Net learning to restore anomalies, we introduce a novel feature-level artificial anomaly synthesis module to generate anomalous samples for training. Subsequently, a novel uncertainty-integrated anomaly perception module based on Bayesian neural networks is introduced to learn the distributions of anomalous and normal features. This facilitates the estimation of anomalous regions and ambiguous boundaries, laying the foundation for subsequent anomaly restoration. Then, we propose a novel restoration attention mechanism that leverages global normal semantic information to restore detected anomalous regions, thereby obtaining defect-free restored features. Finally, we employ residual maps between input features and restored features for anomaly detection and localization. The comprehensive experimental results on two industrial datasets, MVTec AD and BTAD, along with a medical image dataset, OCT-2017, unequivocally demonstrate the effectiveness and superiority of the proposed method.
### Title:
          JFTA-Bench: Evaluate LLM's Ability of Tracking and Analyzing Malfunctions Using Fault Trees
 - **Authors:** Yuhui Wang, Zhixiong Yang, Ming Zhang, Shihan Dou, Zhiheng Xi, Enyu Zhou, Senjie Jin, Yujiong Shen, Dingwei Zhu, Yi Dong, Tao Gui, Qi Zhang, Xuanjing Huang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In the maintenance of complex systems, fault trees are used to locate problems and provide targeted solutions. To enable fault trees stored as images to be directly processed by large language models, which can assist in tracking and analyzing malfunctions, we propose a novel textual representation of fault trees. Building on it, we construct a benchmark for multi-turn dialogue systems that emphasizes robust interaction in complex environments, evaluating a model's ability to assist in malfunction localization, which contains $3130$ entries and $40.75$ turns per entry on average. We train an end-to-end model to generate vague information to reflect user behavior and introduce long-range rollback and recovery procedures to simulate user error scenarios, enabling assessment of a model's integrated capabilities in task tracking and error recovery, and Gemini 2.5 pro archives the best performance.
### Title:
          On the Suboptimality of Rate--Distortion-Optimal Compression: Fundamental Accuracy Limits for Distributed Localization
 - **Authors:** Amir Weiss
 - **Subjects:** Subjects:
Information Theory (cs.IT); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We derive fundamental accuracy limits for distributed localization when a fusion center has access only to independently rate-distortion (RD)-optimally compressed versions of multi-sensor observations, under a line-of-sight propagation model with a Gaussian wideband waveform. Using the Gaussian RD test-channel model together with a Whittle spectral Fisher-information characterization, we obtain an explicit frequency-domain Cramér-Rao lower bound. A two-band, two-level specialization yields closed-form expressions and reveals a rate-induced regime change: RD-optimal compression under a squared-error distortion measure can eliminate localization-informative spectral content. A simple band-selective scheme can outperform RD compression by orders of magnitude at the same rate, motivating localization-aware compression for networked sensing and integrated sensing and communication systems.
### Title:
          Concept-based explanations of Segmentation and Detection models in Natural Disaster Management
 - **Authors:** Samar Heydari, Jawher Said, Galip Ümit Yolcu, Evgenii Kortukov, Elena Golimblevskaia, Evgenios Vlachos, Vasileios Mygdalis, Ioannis Pitas, Sebastian Lapuschkin, Leila Arras
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning models for flood and wildfire segmentation and object detection enable precise, real-time disaster localization when deployed on embedded drone platforms. However, in natural disaster management, the lack of transparency in their decision-making process hinders human trust required for emergency response. To address this, we present an explainability framework for understanding flood segmentation and car detection predictions on the widely used PIDNet and YOLO architectures. More specifically, we introduce a novel redistribution strategy that extends Layer-wise Relevance Propagation (LRP) explanations for sigmoid-gated element-wise fusion layers. This extension allows LRP relevances to flow through the fusion modules of PIDNet, covering the entire computation graph back to the input image. Furthermore, we apply Prototypical Concept-based Explanations (PCX) to provide both local and global explanations at the concept level, revealing which learned features drive the segmentation and detection of specific disaster semantic classes. Experiments on a publicly available flood dataset show that our framework provides reliable and interpretable explanations while maintaining near real-time inference capabilities, rendering it suitable for deployment on resource-constrained platforms, such as Unmanned Aerial Vehicles (UAVs).
### Title:
          Traffic Sign Recognition in Autonomous Driving: Dataset, Benchmark, and Field Experiment
 - **Authors:** Guoyang Zhao, Weiqing Qi, Kai Zhang, Chenguang Zhang, Zeying Gong, Zhihai Bi, Kai Chen, Benshan Ma, Ming Liu, Jun Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traffic Sign Recognition (TSR) is a core perception capability for autonomous driving, where robustness to cross-region variation, long-tailed categories, and semantic ambiguity is essential for reliable real-world deployment. Despite steady progress in recognition accuracy, existing traffic sign datasets and benchmarks offer limited diagnostic insight into how different modeling paradigms behave under these practical challenges. We present TS-1M, a large-scale and globally diverse traffic sign dataset comprising over one million real-world images across 454 standardized categories, together with a diagnostic benchmark designed to analyze model capability boundaries. Beyond standard train-test evaluation, we provide a suite of challenge-oriented settings, including cross-region recognition, rare-class identification, low-clarity robustness, and semantic text understanding, enabling systematic and fine-grained assessment of modern TSR models. Using TS-1M, we conduct a unified benchmark across three representative learning paradigms: classical supervised models, self-supervised pretrained models, and multimodal vision-language models (VLMs). Our analysis reveals consistent paradigm-dependent behaviors, showing that semantic alignment is a key factor for cross-region generalization and rare-category recognition, while purely visual models remain sensitive to appearance shift and data imbalance. Finally, we validate the practical relevance of TS-1M through real-scene autonomous driving experiments, where traffic sign recognition is integrated with semantic reasoning and spatial localization to support map-level decision constraints. Overall, TS-1M establishes a reference-level diagnostic benchmark for TSR and provides principled insights into robust and semantic-aware traffic sign perception. Project page: this https URL.
### Title:
          Active Robotic Perception for Disease Detection and Mapping in Apple Trees
 - **Authors:** Hayden Feddock, Francisco Yandun, Srđan Aćimović, Abhisesh Silwal
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large-scale orchard production requires timely and precise disease monitoring, yet routine manual scouting is labor-intensive and financially impractical at the scale of modern operations. As a result, disease outbreaks are often detected late and tracked at coarse spatial resolutions, typically at the orchard-block level. We present an autonomous mobile active perception system for targeted disease detection and mapping in dormant apple trees, demonstrated on one of the most devastating diseases affecting apple today -- fire blight. The system integrates flash-illuminated stereo RGB sensing, real-time depth estimation, instance-level segmentation, and confidence-aware semantic 3D mapping to achieve precise localization of disease symptoms. Semantic predictions are fused into the volumetric occupancy map representation enabling the tracking of both occupancy and per-voxel semantic confidence, building actionable spatial maps for growers. To actively refine observations within complex canopies, we evaluate three viewpoint planning strategies within a unified perception-action loop: a deterministic geometric baseline, a volumetric next-best-view planner that maximizes unknown-space reduction, and a semantic next-best-view planner that prioritizes low-confidence symptomatic regions. Experiments on a fabricated lab tree and five simulated symptomatic trees demonstrate reliable symptom localization and mapping as a precursor to a field evaluation. In simulation, the semantic planner achieves the highest F1 score (0.6106) after 30 viewpoints, while the volumetric planner achieves the highest ROI coverage (85.82\%). In the lab setting, the semantic planner attains the highest final F1 (0.9058), with both next-best-view planners substantially improving coverage over the baseline.
### Title:
          Steering LLMs for Culturally Localized Generation
 - **Authors:** Simran Khanuja, Hongbin Liu, Shujian Zhang, John Lambert, Mingqing Chen, Rajiv Mathews, Lun Wang
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLMs are deployed globally, yet produce responses biased towards cultures with abundant training data. Existing cultural localization approaches such as prompting or post-training alignment are black-box, hard to control, and do not reveal whether failures reflect missing knowledge or poor elicitation. In this paper, we address these gaps using mechanistic interpretability to uncover and manipulate cultural representations in LLMs. Leveraging sparse autoencoders, we identify interpretable features that encode culturally salient information and aggregate them into Cultural Embeddings (CuE). We use CuE both to analyze implicit cultural biases under underspecified prompts and to construct white-box steering interventions. Across multiple models, we show that CuE-based steering increases cultural faithfulness and elicits significantly rarer, long-tail cultural concepts than prompting alone. Notably, CuE-based steering is complementary to black-box localization methods, offering gains when applied on top of prompt-augmented inputs. This also suggests that models do benefit from better elicitation strategies, and don't necessarily lack long-tail knowledge representation, though this varies across cultures. Our results provide both diagnostic insight into cultural representations in LLMs and a controllable method to steer towards desired cultures.
## Keyword: transformer
### Title:
          Scaling Attention via Feature Sparsity
 - **Authors:** Yan Xie, Tiansheng Wen, Tangda Huang, Bo Chen, Chenyu You, Stefanie Jegelka, Yifei Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling Transformers to ultra-long contexts is bottlenecked by the $O(n^2 d)$ cost of self-attention. Existing methods reduce this cost along the sequence axis through local windows, kernel approximations, or token-level sparsity, but these approaches consistently degrade accuracy. In this paper, we instead explore an orthogonal axis: feature sparsity. We propose Sparse Feature Attention (SFA), where queries and keys are represented as $k$-sparse codes that preserve high-dimensional expressivity while reducing the cost of attention from $\Theta(n^2 d)$ to $\Theta(n^2 k^2/d)$. To make this efficient at scale, we introduce FlashSFA, an IO-aware kernel that extends FlashAttention to operate directly on sparse overlaps without materializing dense score matrices. Across GPT-2 and Qwen3 pretraining, SFA matches dense baselines while improving speed by up to $2.5\times$ and reducing FLOPs and KV-cache by nearly 50\%. On synthetic and downstream benchmarks, SFA preserves retrieval accuracy and robustness at long contexts, outperforming short-embedding baselines that collapse feature diversity. These results establish feature-level sparsity as a complementary and underexplored axis for efficient attention, enabling Transformers to scale to orders-of-magnitude longer contexts with minimal quality loss. Code is available at this https URL.
### Title:
          Latent Semantic Manifolds in Large Language Models
 - **Authors:** Mohamed A. Mabrok
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) perform internal computations in continuous vector spaces yet produce discrete tokens -- a fundamental mismatch whose geometric consequences remain poorly understood. We develop a mathematical framework that interprets LLM hidden states as points on a latent semantic manifold: a Riemannian submanifold equipped with the Fisher information metric, where tokens correspond to Voronoi regions partitioning the manifold. We define the expressibility gap, a geometric measure of the semantic distortion from vocabulary discretization, and prove two theorems: a rate-distortion lower bound on distortion for any finite vocabulary, and a linear volume scaling law for the expressibility gap via the coarea formula. We validate these predictions across six transformer architectures (124M-1.5B parameters), confirming universal hourglass intrinsic dimension profiles, smooth curvature structure, and linear gap scaling with slopes 0.87-1.12 (R^2 > 0.985). The margin distribution across models reveals a persistent hard core of boundary-proximal representations invariant to scale, providing a geometric decomposition of perplexity. We discuss implications for architecture design, model compression, decoding strategies, and scaling laws
### Title:
          UniFluids: Unified Neural Operator Learning with Conditional Flow-matching
 - **Authors:** Haosen Li, Qi Meng, Jiahao Li, Rui Zhang, Ruihua Song, Liang Ma, Zhi-Ming Ma
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Partial differential equation (PDE) simulation holds extensive significance in scientific research. Currently, the integration of deep neural networks to learn solution operators of PDEs has introduced great potential. In this paper, we present UniFluids, a conditional flow-matching framework that harnesses the scalability of diffusion Transformer to unify learning of solution operators across diverse PDEs with varying dimensionality and physical variables. Unlike the autoregressive PDE foundation models, UniFluids adopts flow-matching to achieve parallel sequence generation, making it the first such approach for unified operator learning. Specifically, the introduction of a unified four-dimensional spatiotemporal representation for the heterogeneous PDE datasets enables joint training and conditional encoding. Furthermore, we find the effective dimension of the PDE dataset is much lower than its patch dimension. We thus employ $x$-prediction in the flow-matching operator learning, which is verified to significantly improve prediction accuracy. We conduct a large-scale evaluation of UniFluids on several PDE datasets covering spatial dimensions 1D, 2D and 3D. Experimental results show that UniFluids achieves strong prediction accuracy and demonstrates good scalability and cross-scenario generalization capability. The code will be released later.
### Title:
          Emergency Preemption Without Online Exploration: A Decision Transformer Approach
 - **Authors:** Haoran Su, Hanxiao Deng, Yandong Sun
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Emergency vehicle (EV) response time is a critical determinant of survival outcomes, yet deployed signal preemption strategies remain reactive and uncontrollable. We propose a return-conditioned framework for emergency corridor optimization based on the Decision Transformer (DT). By casting corridor optimization as offline, return-conditioned sequence modeling, our approach (1) eliminates online environment interaction during policy learning, (2) enables dispatch-level urgency control through a single target-return scalar, and (3) extends to multi-agent settings via a Multi-Agent Decision Transformer (MADT) with graph attention for spatial coordination. On the LightSim simulator, DT reduces average EV travel time by 37.7% relative to fixed-timing preemption on a 4x4 grid (88.6 s vs. 142.3 s), achieving the lowest civilian delay (11.3 s/veh) and fewest EV stops (1.2) among all methods, including online RL baselines that require environment interaction. MADT further improves on larger grids, overtaking DT with 45.2% reduction on 8x8 via graph-attention coordination. Return conditioning produces a smooth dispatch interface: varying the target return from 100 to -400 trades EV travel time (72.4-138.2 s) against civilian delay (16.8-5.4 s/veh), requiring no retraining. A Constrained DT extension adds explicit civilian disruption budgets as a second control knob.
### Title:
          A graph neural network based chemical mechanism reduction method for combustion applications
 - **Authors:** Manuru Nithin Padiyar, Priyabrat Dash, Konduri Aditya
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Direct numerical simulations of turbulent reacting flows involving millions of grid points and detailed chemical mechanisms with hundreds of species and thousands of reactions are computationally prohibitive. To address this challenge, we present two data-driven chemical mechanism reduction formulations based on graph neural networks (GNNs) with message-passing transformer layers that learn nonlinear dependencies among species and reactions. The first formulation, GNN-SM, employs a pre-trained surrogate model to guide reduction across a broad range of reactor conditions. The second formulation, GNN-AE, uses an autoencoder formulation to obtain highly compact mechanisms that remain accurate within the thermochemical regimes used during training. The approaches are demonstrated on detailed mechanisms for methane (53 species, 325 reactions), ethylene (96 species, 1054 reactions), and iso-octane (1034 species, 8453 reactions). GNN-SM achieves reductions comparable to the established graph-based method DRGEP while maintaining accuracy across a wide range of thermochemical states. In contrast, GNN-AE achieves up to 95% reduction in species and reactions and outperforms DRGEP within its target conditions. Overall, the proposed framework provides an automated, machine-learning-based pathway for chemical mechanism reduction that can complement traditional expert-guided analytical approaches.
### Title:
          Hybrid Associative Memories
 - **Authors:** Leon Lufkin, Tomás Figliolia, Beren Millidge, Kamesh Krishnamurthy
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recurrent neural networks (RNNs) and self-attention are both widely used sequence-mixing layers that maintain an internal memory. However, this memory is constructed using two orthogonal mechanisms: RNNs compress the entire past into a fixed-size state, whereas self-attention's state stores every past time step growing its state (the KV cache) linearly with the sequence length. This results in orthogonal strengths and weaknesses. Self-attention layers excel at retrieving information in the context but have large memory and computational costs, while RNNs are more efficient but degrade over longer contexts and underperform for precise recall tasks. Prior work combining these mechanisms has focused primarily on naively interleaving them to reduce computational cost without regard to their complementary mechanisms. We propose the Hybrid Associative Memory (HAM) layer, which combines self-attention and RNNs while leveraging their individual strengths: the RNN compresses the entire sequence, while attention supplements it *only* with information that is difficult for the RNN to predict, which is hence the most valuable information to explicitly store. HAM layers enable data-dependent growth of the KV cache, which can be precisely controlled by the user with a single, continuous threshold. We find that this fine-grained control of the KV cache growth rate has a smooth trade-off with loss and performance. Empirically, we show that our hybrid architecture offers strong, competitive performance relative to RNNs and Transformers even at substantially lower KV-cache usage.
### Title:
          Trained Persistent Memory for Frozen Decoder-Only LLMs
 - **Authors:** Hong Jeong
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Decoder-only language models are stateless: hidden representations are discarded after every forward pass and nothing persists across sessions. Jeong (2026a) showed that trained memory adapters give a frozen encoder-decoder backbone persistent latent-space memory, building on the lateral-memory framework of Jeong (2026b,c). Here we ask whether the same principle transfers to the decoder-only setting, where no cross-attention pathway exists and memory must enter through self-attention alone. We adapt six methods -- prefix, parallel cross-attention, KV extension, Hebbian memory, context-gated branch, and slot-based sparse write -- to a frozen GPT-2, training only a small adapter $\theta_{mem}$. The write rule is shared; only the read injection changes from decoder cross-attention to self-attention KV prefix or parallel branch. On LoCoMo we find a striking inductive-bias dichotomy: at $1\times$ capacity, three methods with strong architectural priors -- cross-attention (M.2), Hebbian (M.4), and slot write (M.6) -- achieve retained-memory scores of $7-18\%$ and knowledge gains $\Delta K$ of $7-10$, while the other three fail ($< 0.4\%$). At $10\times$ capacity all six converge, showing the gap is architectural, not fundamental. Together with the encoder-decoder results of Jeong (2026a) and the brain-inspired modules of Jeong (2026b,c), these findings establish persistent latent-space memory as a general paradigm spanning major transformer families.
### Title:
          Neural Structure Embedding for Symbolic Regression via Continuous Structure Search and Coefficient Optimization
 - **Authors:** Fateme Memar, Tao Zhe, Dongjie Wang
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Symbolic regression aims to discover human-interpretable equations that explain observational data. However, existing approaches rely heavily on discrete structure search (e.g., genetic programming), which often leads to high computational cost, unstable performance, and limited scalability to large equation spaces. To address these challenges, we propose SRCO, a unified embedding-driven framework for symbolic regression that transforms symbolic structures into a continuous, optimizable representation space. The framework consists of three key components: (1) structure embedding: we first generate a large pool of exploratory equations using traditional symbolic regression algorithms and train a Transformer model to compress symbolic structures into a continuous embedding space; (2) continuous structure search: the embedding space enables efficient exploration using gradient-based or sampling-based optimization, significantly reducing the cost of navigating the combinatorial structure space; and (3) coefficient optimization: for each discovered structure, we treat symbolic coefficients as learnable parameters and apply gradient optimization to obtain accurate numerical values. Experiments on synthetic and real-world datasets show that our approach consistently outperforms state-of-the-art methods in equation accuracy, robustness, and search efficiency. This work introduces a new paradigm for symbolic regression by bridging symbolic equation discovery with continuous embedding learning and optimization.
### Title:
          Functional Component Ablation Reveals Specialization Patterns in Hybrid Language Model Architectures
 - **Authors:** Hector Borobia, Elies Seguí-Mas, Guillermina Tormo-Carbó
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hybrid language models combining attention with state space models (SSMs) or linear attention offer improved efficiency, but whether both components are genuinely utilized remains unclear. We present a functional component ablation framework applied to two sub-1B hybrid models -- Qwen3.5-0.8B (sequential: Gated DeltaNet + softmax attention) and Falcon-H1-0.5B (parallel: Mamba-2 + attention) -- with a pure Transformer control (Qwen2.5-0.5B). Through group ablations, layer-wise sweeps, positional ablations, matched random controls, and perplexity analysis across five benchmarks, we establish four findings: (1) both component types are essential and neither is bypassed; (2) the alternative component (linear attention or SSM) is the primary language modeling backbone, causing >35,000x perplexity degradation when removed versus ~82x for attention; (3) component importance follows a positional gradient, with early layers being disproportionately critical; and (4) hybrid architectures exhibit 20-119x greater resilience to random layer removal than pure Transformers, revealing built-in functional redundancy between component types. These results provide actionable guidance for hybrid model compression, architecture design, and fault-tolerant deployment.
### Title:
          Tiny Inference-Time Scaling with Latent Verifiers
 - **Authors:** Davide Bucciarelli, Evelyn Turri, Lorenzo Baraldi, Marcella Cornia, Lorenzo Baraldi, Rita Cucchiara
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inference-time scaling has emerged as an effective way to improve generative models at test time by using a verifier to score and select candidate outputs. A common choice is to employ Multimodal Large Language Models (MLLMs) as verifiers, which can improve performance but introduce substantial inference-time cost. Indeed, diffusion pipelines operate in an autoencoder latent space to reduce computation, yet MLLM verifiers still require decoding candidates to pixel space and re-encoding them into the visual embedding space, leading to redundant and costly operations. In this work, we propose Verifier on Hidden States (VHS), a verifier that operates directly on intermediate hidden representations of Diffusion Transformer (DiT) single-step generators. VHS analyzes generator features without decoding to pixel space, thereby reducing the per-candidate verification cost while improving or matching the performance of MLLM-based competitors. We show that, under tiny inference budgets with only a small number of candidates per prompt, VHS enables more efficient inference-time scaling reducing joint generation-and-verification time by 63.3%, compute FLOPs by 51% and VRAM usage by 14.5% with respect to a standard MLLM verifier, achieving a +2.7% improvement on GenEval at the same inference-time budget.
### Title:
          CanViT: Toward Active-Vision Foundation Models
 - **Authors:** Yohaï-Eliel Berreby, Sabrina Du, Audrey Durand, B. Suresh Krishna
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Active computer vision promises efficient, biologically plausible perception through sequential, localized glimpses, but lacks scalable general-purpose architectures and pretraining pipelines. As a result, Active-Vision Foundation Models (AVFMs) have remained unexplored. We introduce CanViT, the first task- and policy-agnostic AVFM. CanViT uses scene-relative RoPE to bind a retinotopic Vision Transformer backbone and a spatiotopic scene-wide latent workspace, the canvas. Efficient interaction with this high-capacity working memory is supported by Canvas Attention, a novel asymmetric cross-attention mechanism. We decouple thinking (backbone-level) and memory (canvas-level), eliminating canvas-side self-attention and fully-connected layers to achieve low-latency sequential inference and scalability to large scenes. We propose a label-free active vision pretraining scheme, policy-agnostic passive-to-active dense latent distillation: reconstructing scene-wide DINOv3 embeddings from sequences of low-resolution glimpses with randomized locations, zoom levels, and lengths. We pretrain CanViT-B from a random initialization on 13.2 million ImageNet-21k scenes -- an order of magnitude more than previous active models -- and 1 billion random glimpses, in 166 hours on a single H100. On ADE20K segmentation, a frozen CanViT-B achieves 38.5% mIoU in a single low-resolution glimpse, outperforming the best active model's 27.6% with 19.5x fewer inference FLOPs and no fine-tuning, as well as its FLOP- or input-matched DINOv3 teacher. Given additional glimpses, CanViT-B reaches 45.9% ADE20K mIoU. On ImageNet-1k classification, CanViT-B reaches 81.2% top-1 accuracy with frozen teacher probes. CanViT generalizes to longer rollouts, larger scenes, and new policies. Our work closes the wide gap between passive and active vision on semantic segmentation and demonstrates the potential of AVFMs as a new research axis.
### Title:
          A Foundation Model for Instruction-Conditioned In-Context Time Series Tasks
 - **Authors:** Anish Saha, Konstantin Shmakov
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In-context learning (ICL) allows a model to adapt at inference time by conditioning on examples rather than updating parameters. Existing time-series foundation models use implicit positional context, retrieval, or task-specific objectives, but rarely explicit instruction-conditioned demonstrations. We present a foundation model for instruction-conditioned in-context time-series tasks based on a quantile-regression T5 encoder-decoder. Historical examples and queries are encoded with a structured tokenization scheme that marks target series, covariates, context, and task-specific future information. A hierarchical Transformer with per-example encoding, example-level fusion, and cross-example attention conditions decoding on demonstration pairs, enabling forecasting and related tasks without task-specific fine-tuning. We train on large-scale real and synthetic time series using supervised forecasting plus self-supervised tasks, including imputation, reconstruction, classification, anomaly detection, and source demixing. This multi-task training learns a distribution over task mappings and improves adaptation to local structure at inference time. Across diverse datasets, frequencies, and horizons, our method outperforms strong foundation baselines on point and probabilistic forecasting benchmarks, including fev-bench and GIFT-Eval, while remaining competitive on classification and anomaly detection.
### Title:
          TimeWeaver: Age-Consistent Reference-Based Face Restoration with Identity Preservation
 - **Authors:** Teer Song, Yue Zhang, Yu Tian, Ziyang Wang, Xianlin Zhang, Guixuan Zhang, Xuan Liu, Xueming Li, Yasen Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent progress in face restoration has shifted from visual fidelity to identity fidelity, driving a transition from reference-free to reference-based paradigms that condition restoration on reference images of the same person. However, these methods assume the reference and degraded input are age-aligned. When only cross-age references are available, as in historical restoration or missing-person retrieval, they fail to maintain age fidelity. To address this limitation, we propose TimeWeaver, the first reference-based face restoration framework supporting cross-age references. Given arbitrary reference images and a target-age prompt, TimeWeaver produces restorations with both identity fidelity and age consistency. Specifically, we decouple identity and age conditioning across training and inference. During training, the model learns an age-robust identity representation by fusing a global identity embedding with age-suppressed facial tokens via a transformer-based ID-Fusion module. During inference, two training-free techniques, Age-Aware Gradient Guidance and Token-Targeted Attention Boost, steer sampling toward desired age semantics, enabling precise adherence to the target-age prompt. Extensive experiments show that TimeWeaver surpasses existing methods in visual quality, identity preservation, and age consistency.
### Title:
          Multitask-Informed Prior for In-Context Learning on Tabular Data: Application to Steel Property Prediction
 - **Authors:** Dimitrios Sinodinos, Bahareh Nikpour, Jack Yi Wei, Sushant Sinha, Xiaoping Ma, Kashif Rehman, Stephen Yue, Narges Armanfard
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate prediction of mechanical properties of steel during hot rolling processes, such as Thin Slab Direct Rolling (TSDR), remains challenging due to complex interactions among chemical compositions, processing parameters, and resultant microstructures. Traditional empirical and experimental methodologies, while effective, are often resource-intensive and lack adaptability to varied production conditions. Moreover, most existing approaches do not explicitly leverage the strong correlations among key mechanical properties, missing an opportunity to improve predictive accuracy through multitask learning. To address this, we present a multitask learning framework that injects multitask awareness into the prior of TabPFN--a transformer-based foundation model for in-context learning on tabular data--through novel fine-tuning strategies. Originally designed for single-target regression or classification, we augment TabPFN's prior with two complementary approaches: (i) target averaging, which provides a unified scalar signal compatible with TabPFN's single-target architecture, and (ii) task-specific adapters, which introduce task-specific supervision during fine-tuning. These strategies jointly guide the model toward a multitask-informed prior that captures cross-property relationships among key mechanical metrics. Extensive experiments on an industrial TSDR dataset demonstrate that our multitask adaptations outperform classical machine learning methods and recent state-of-the-art tabular learning models across multiple evaluation metrics. Notably, our approach enhances both predictive accuracy and computational efficiency compared to task-specific fine-tuning, demonstrating that multitask-aware prior adaptation enables foundation models for tabular data to deliver scalable, rapid, and reliable deployment for automated industrial quality control and process optimization in TSDR.
### Title:
          From Pixels to Semantics: A Multi-Stage AI Framework for Structural Damage Detection in Satellite Imagery
 - **Authors:** Bijay Shakya, Catherine Hoier, Khandaker Mamun Ahmed
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Rapid and accurate structural damage assessment following natural disasters is critical for effective emergency response and recovery. However, remote sensing imagery often suffers from low spatial resolution, contextual ambiguity, and limited semantic interpretability, reducing the reliability of traditional detection pipelines. In this work, we propose a novel hybrid framework that integrates AI-based super-resolution, deep learning object detection, and Vision-Language Models (VLMs) for comprehensive post-disaster building damage assessment. First, we enhance pre- and post-disaster satellite imagery using a Video Restoration Transformer (VRT) to upscale images from 1024x1024 to 4096x4096 resolution, improving structural detail visibility. Next, a YOLOv11-based detector localizes buildings in pre-disaster imagery, and cropped building regions are analyzed using VLMs to semantically assess structural damage across four severity levels. To ensure robust evaluation in the absence of ground-truth captions, we employ CLIPScore for reference-free semantic alignment and introduce a multi-model VLM-as-a-Jury strategy to reduce individual model bias in safety-critical decision making. Experiments on subsets of the xBD dataset, including the Moore Tornado and Hurricane Matthew events, demonstrate that the proposed framework enhances the semantic interpretation of damaged buildings. In addition, our framework provides helpful recommendations to first responders for recovery based on damage analysis.
### Title:
          It Takes Two: A Duet of Periodicity and Directionality for Burst Flicker Removal
 - **Authors:** Lishen Qu, Shihao Zhou, Jie Liang, Hui Zeng, Lei Zhang, Jufeng Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Flicker artifacts, arising from unstable illumination and row-wise exposure inconsistencies, pose a significant challenge in short-exposure photography, severely degrading image quality. Unlike typical artifacts, e.g., noise and low-light, flicker is a structured degradation with specific spatial-temporal patterns, which are not accounted for in current generic restoration frameworks, leading to suboptimal flicker suppression and ghosting artifacts. In this work, we reveal that flicker artifacts exhibit two intrinsic characteristics, periodicity and directionality, and propose Flickerformer, a transformer-based architecture that effectively removes flicker without introducing ghosting. Specifically, Flickerformer comprises three key components: a phase-based fusion module (PFM), an autocorrelation feed-forward network (AFFN), and a wavelet-based directional attention module (WDAM). Based on the periodicity, PFM performs inter-frame phase correlation to adaptively aggregate burst features, while AFFN exploits intra-frame structural regularities through autocorrelation, jointly enhancing the network's ability to perceive spatially recurring patterns. Moreover, motivated by the directionality of flicker artifacts, WDAM leverages high-frequency variations in the wavelet domain to guide the restoration of low-frequency dark regions, yielding precise localization of flicker artifacts. Extensive experiments demonstrate that Flickerformer outperforms state-of-the-art approaches in both quantitative metrics and visual quality. The source code is available at this https URL.
### Title:
          Transformers Trained via Gradient Descent Can Provably Learn a Class of Teacher Models
 - **Authors:** Chenyang Zhang, Qingyue Zhao, Quanquan Gu, Yuan Cao
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have achieved great success across a wide range of applications, yet the theoretical foundations underlying their success remain largely unexplored. To demystify the strong capacities of transformers applied to versatile scenarios and tasks, we theoretically investigate utilizing transformers as students to learn from a class of teacher models. Specifically, the teacher models covered in our analysis include convolution layers with average pooling, graph convolution layers, and various classic statistical learning models, including a variant of sparse token selection models [Sanford et al., 2023, Wang et al., 2024] and group-sparse linear predictors [Zhang et al., 2025]. When learning from this class of teacher models, we prove that one-layer transformers with simplified "position-only'' attention can successfully recover all parameter blocks of the teacher models, thus achieving the optimal population loss. Building upon the efficient mimicry of trained transformers towards teacher models, we further demonstrate that they can generalize well to a broad class of out-of-distribution data under mild assumptions. The key in our analysis is to identify a fundamental bilinear structure shared by various learning tasks, which enables us to establish unified learning guarantees for these tasks when treating them as teachers for transformers.
### Title:
          Avoiding Over-smoothing in Social Media Rumor Detection with Pre-trained Propagation Tree Transformer
 - **Authors:** Chaoqun Cui, Caiyan Jia
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning techniques for rumor detection typically utilize Graph Neural Networks (GNNs) to analyze post relations. These methods, however, falter due to over-smoothing issues when processing rumor propagation structures, leading to declining performance. Our investigation into this issue reveals that over-smoothing is intrinsically tied to the structural characteristics of rumor propagation trees, in which the majority of nodes are 1-level nodes. Furthermore, GNNs struggle to capture long-range dependencies within these trees. To circumvent these challenges, we propose a Pre-Trained Propagation Tree Transformer (P2T3) method based on pure Transformer architecture. It extracts all conversation chains from a tree structure following the propagation direction of replies, utilizes token-wise embedding to infuse connection information and introduces necessary inductive bias, and pre-trains on large-scale unlabeled datasets. Experiments indicate that P2T3 surpasses previous state-of-the-art methods in multiple benchmark datasets and performs well under few-shot conditions. P2T3 not only avoids the over-smoothing issue inherent in GNNs but also potentially offers a large model or unified multi-modal scheme for future social media research.
### Title:
          The Coordinate System Problem in Persistent Structural Memory for Neural Architectures
 - **Authors:** Abhinaba Basu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Neural and Evolutionary Computing (cs.NE); Neurons and Cognition (q-bio.NC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce the Dual-View Pheromone Pathway Network (DPPN), an architecture that routes sparse attention through a persistent pheromone field over latent slot transitions, and use it to discover two independent requirements for persistent structural memory in neural networks. Through five progressively refined experiments using up to 10 seeds per condition across 5 model variants and 4 transfer targets, we identify a core principle: persistent memory requires a stable coordinate system, and any coordinate system learned jointly with the model is inherently unstable. We characterize three obstacles -- pheromone saturation, surface-structure entanglement, and coordinate incompatibility -- and show that neither contrastive updates, multi-source distillation, Hungarian alignment, nor semantic decomposition resolves the instability when embeddings are learned from scratch. Fixed random Fourier features provide extrinsic coordinates that are stable, structure-blind, and informative, but coordinate stability alone is insufficient: routing-bias pheromone does not transfer (10 seeds, p>0.05). DPPN outperforms transformer and random sparse baselines for within-task learning (AULC 0.700 vs 0.680 vs 0.670). Replacing routing bias with learning-rate modulation eliminates negative transfer: warm pheromone as a learning-rate prior achieves +0.003 on same-family tasks (17 seeds, p<0.05) while never reducing performance. A structure completion function over extrinsic coordinates produces +0.006 same-family bonus beyond regularization, showing the catch-22 between stability and informativeness is partially permeable to learned functions. The contribution is two independent requirements for persistent structural memory: (a) coordinate stability and (b) graceful transfer mechanism.
### Title:
          TRINE: A Token-Aware, Runtime-Adaptive FPGA Inference Engine for Multimodal AI
 - **Authors:** Hyunwoo Oh, Hanning Chen, Sanggeon Yun, Yang Ni, Suyeon Jang, Behnam Khaleghi, Fei Wen, Mohsen Imani
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal stacks that mix ViTs, CNNs, GNNs, and transformer NLP strain embedded platforms because their compute/memory patterns diverge and hard real-time targets leave little slack. TRINE is a single-bitstream FPGA accelerator and compiler that executes end-to-end multimodal inference without reconfiguration. Layers are unified as DDMM/SDDMM/SpMM and mapped to a mode-switchable engine that toggles at runtime among weight/output-stationary systolic, 1xCS SIMD, and a routable adder tree (RADT) on a shared PE array. A width-matched, two-stage top-k unit enables in-stream token pruning, while dependency-aware layer offloading (DALO) overlaps independent kernels across reconfigurable processing units to sustain utilization. Evaluated on Alveo U50 and ZCU104, TRINE reduces latency by up to 22.57x vs. RTX 4090 and 6.86x vs. Jetson Orin Nano at 20-21 W; token pruning alone yields up to 7.8x on ViT-heavy pipelines, and DALO contributes up to 79% throughput improvement. With int8 quantization, accuracy drops remain <2.5% across representative tasks, delivering state-of-the-art latency and energy efficiency for unified vision, language, and graph workloads-in one bitstream.
### Title:
          FixationFormer: Direct Utilization of Expert Gaze Trajectories for Chest X-Ray Classification
 - **Authors:** Daniel Beckmann, Benjamin Risse
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Expert eye movements provide a rich, passive source of domain knowledge in radiology, offering a powerful cue for integrating diagnostic reasoning into computer-aided analysis. However, direct integration into CNN-based systems, which historically have dominated the medical image analysis domain, is challenging: gaze recordings are sequential, temporally dense yet spatially sparse, noisy, and variable across experts. As a consequence, most existing image-based models utilize reduced representations such as heatmaps. In contrast, gaze naturally aligns with transformer architectures, as both are sequential in nature and rely on attention to highlight relevant input regions. In this work, we introduce FixationFormer, a transformer-based architecture that represents expert gaze trajectories as sequences of tokens, thereby preserving their temporal and spatial structure. By modeling gaze sequences jointly with image features, our approach addresses sparsity and variability in gaze data while enabling a more direct and fine-grained integration of expert diagnostic cues through explicit cross-attention between the image and gaze token sequences. We evaluate our method on three publicly available benchmark chest X-ray datasets and demonstrate that it achieves state-of-the-art classification performance, highlighting the value of representing gaze as a sequence in transformer-based medical image analysis.
### Title:
          Caption Generation for Dongba Paintings via Prompt Learning and Semantic Fusion
 - **Authors:** Shuangwu Qian, Xiaochan Yuan, Pengfei Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dongba paintings, the treasured pictorial legacy of the Naxi people in southwestern China, feature richly layered visual elements, vivid color palettes, and pronounced ethnic and regional cultural symbolism, yet their automatic textual description remains largely unexplored owing to severe domain shift when mainstream captioning models are applied directly. This paper proposes \textbf{PVGF-DPC} (\textit{Prompt and Visual Semantic-Generation Fusion-based Dongba Painting Captioning}), an encoder-decoder framework that integrates a content prompt module with a novel visual semantic-generation fusion loss to bridge the gap between generic natural-image captioning and the culturally specific imagery found in Dongba art. A MobileNetV2 encoder extracts discriminative visual features, which are injected into the layer normalization of a 10-layer Transformer decoder initialized with pretrained BERT weights; meanwhile, the content prompt module maps the image feature vector to culture-aware labels -- such as \emph{deity}, \emph{ritual pattern}, or \emph{hell ghost} -- and constructs a post-prompt that steers the decoder toward thematically accurate descriptions. The visual semantic-generation fusion loss jointly optimizes the cross-entropy objectives of both the prompt predictor and the caption generator, encouraging the model to extract key cultural and visual cues and to produce captions that are semantically aligned with the input image. We construct a dedicated Dongba painting captioning dataset comprising 9{}408 augmented images with culturally grounded annotations spanning seven thematic categories.
### Title:
          Generative Event Pretraining with Foundation Model Alignment
 - **Authors:** Jianwen Cao, Jiaxu Xing, Nico Messikommer, Davide Scaramuzza
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event cameras provide robust visual signals under fast motion and challenging illumination conditions thanks to their microsecond latency and high dynamic range. However, their unique sensing characteristics and limited labeled data make it challenging to train event-based visual foundation models (VFMs), which are crucial for learning visual features transferable across tasks. To tackle this problem, we propose GEP (Generative Event Pretraining), a two-stage framework that transfers semantic knowledge learned from internet-scale image datasets to event data while learning event-specific temporal dynamics. First, an event encoder is aligned to a frozen VFM through a joint regression-contrastive objective, grounding event features in image semantics. Second, a transformer backbone is autoregressively pretrained on mixed event-image sequences to capture the temporal structure unique to events. Our approach outperforms state-of-the-art event pretraining methods on a diverse range of downstream tasks, including object recognition, segmentation, and depth estimation. Together, VFM-guided alignment and generative sequence modeling yield a semantically rich, temporally aware event model that generalizes robustly across domains.
### Title:
          MSR-HuBERT: Self-supervised Pre-training for Adaptation to Multiple Sampling Rates
 - **Authors:** Zikang Huang, Meng Ge, Tianrui Wang, Xuanchen Li, Xiaobao Wang, Longbiao Wang, Jianwu Dang
 - **Subjects:** Subjects:
Sound (cs.SD); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised learning (SSL) has advanced speech processing. However, existing speech SSL methods typically assume a single sampling rate and struggle with mixed-rate data due to temporal resolution mismatch. To address this limitation, we propose MSRHuBERT, a multi-sampling-rate adaptive pre-training method. Building on HuBERT, we replace its single-rate downsampling CNN with a multi-sampling-rate adaptive downsampling CNN that maps raw waveforms from different sampling rates to a shared temporal resolution without resampling. This design enables unified mixed-rate pre-training and fine-tuning. In experiments spanning 16 to 48 kHz, MSRHuBERT outperforms HuBERT on speech recognition and full-band speech reconstruction, preserving high-frequency detail while modeling low-frequency semantic structure. Moreover, MSRHuBERT retains HuBERT's mask-prediction objective and Transformer encoder, so existing analyses and improvements that were developed for HuBERT can apply directly.
### Title:
          MLLM-HWSI: A Multimodal Large Language Model for Hierarchical Whole Slide Image Understanding
 - **Authors:** Basit Alawode, Arif Mahmood, Muaz Khalifa Al-Radi, Shahad Albastaki, Asim Khan, Muhammad Bilal, Moshira Ali Abdalla, Mohammed Bennamoun, Sajid Javed
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Whole Slide Images (WSIs) exhibit hierarchical structure, where diagnostic information emerges from cellular morphology, regional tissue organization, and global context. Existing Computational Pathology (CPath) Multimodal Large Language Models (MLLMs) typically compress an entire WSI into a single embedding, which hinders fine-grained grounding and ignores how pathologists synthesize evidence across different scales. We introduce \textbf{MLLM-HWSI}, a Hierarchical WSI-level MLLM that aligns visual features with pathology language at four distinct scales, cell as word, patch as phrase, region as sentence, and WSI as paragraph to support interpretable evidence-grounded reasoning. MLLM-HWSI decomposes each WSI into multi-scale embeddings with scale-specific projectors and jointly enforces (i) a hierarchical contrastive objective and (ii) a cross-scale consistency loss, preserving semantic coherence from cells to the WSI. We compute diagnostically relevant patches and aggregate segmented cell embeddings into a compact cellular token per-patch using a lightweight \textit{Cell-Cell Attention Fusion (CCAF)} transformer. The projected multi-scale tokens are fused with text tokens and fed to an instruction-tuned LLM for open-ended reasoning, VQA, report, and caption generation tasks. Trained in three stages, MLLM-HWSI achieves new SOTA results on 13 WSI-level benchmarks across six CPath tasks. By aligning language with multi-scale visual evidence, MLLM-HWSI provides accurate, interpretable outputs that mirror diagnostic workflows and advance holistic WSI understanding. Code is available at: \href{this https URL}{GitHub}.
### Title:
          MsFormer: Enabling Robust Predictive Maintenance Services for Industrial Devices
 - **Authors:** Jiahui Zhou, Dan Li, Ruibing Jin, Jian Lou, Yanran Zhao, Zhenghua Chen, Zigui Jiang, See-Kiong Ng
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Providing reliable predictive maintenance is a critical industrial AI service essential for ensuring the high availability of manufacturing devices. Existing deep-learning methods present competitive results on such tasks but lack a general service-oriented framework to capture complex dependencies in industrial IoT sensor data. While Transformer-based models show strong sequence modeling capabilities, their direct deployment as robust AI services faces significant bottlenecks. Specifically, streaming sensor data collected in real-world service environments often exhibits multi-scale temporal correlations driven by machine working principles. Besides, the datasets available for training time-to-failure predictive services are typically limited in size. These issues pose significant challenges for directly applying existing models as robust predictive services. To address these challenges, we propose MsFormer, a lightweight Multi-scale Transformer designed as a unified AI service model for reliable industrial predictive maintenance. MsFormer incorporates a Multi-scale Sampling (MS) module and a tailored position encoding mechanism to capture sequential correlations across multi-streaming service data. Additionally, to accommodate data-scarce service environments, MsFormer adopts a lightweight attention mechanism with straightforward pooling operations instead of self-attention. Extensive experiments on real-world datasets demonstrate that the proposed framework achieves significant performance improvements over state-of-the-art methods. Furthermore, MsFormer outperforms across industrial devices and operating conditions, demonstrating strong generalizability while maintaining a highly reliable Quality of Service (QoS).
### Title:
          VoDaSuRe: A Large-Scale Dataset Revealing Domain Shift in Volumetric Super-Resolution
 - **Authors:** August Leander Høeg, Sophia Wiinberg Bardenfleth, Hans Martin Kjer, Tim Bjørn Dyrby, Vedrana Andersen Dahl, Anders Bjorholm Dahl
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in volumetric super-resolution (SR) have demonstrated strong performance in medical and scientific imaging, with transformer- and CNN-based approaches achieving impressive results even at extreme scaling factors. In this work, we show that much of this performance stems from training on downsampled data rather than real low-resolution scans. This reliance on downsampling is partly driven by the scarcity of paired high- and low-resolution 3D datasets. To address this, we introduce VoDaSuRe, a large-scale volumetric dataset containing paired high- and low-resolution scans. When training models on VoDaSuRe, we reveal a significant discrepancy: SR models trained on downsampled data produce substantially sharper predictions than those trained on real low-resolution scans, which smooth fine structures. Conversely, applying models trained on downsampled data to real scans preserves more structure but is inaccurate. Our findings suggest that current SR methods are overstated - when applied to real data, they do not recover structures lost in low-resolution scans and instead predict a smoothed average. We argue that progress in deep learning-based volumetric SR requires datasets with paired real scans of high complexity, such as VoDaSuRe. Our dataset and code are publicly available through: this https URL
### Title:
          PhysSkin: Real-Time and Generalizable Physics-Based Animation via Self-Supervised Neural Skinning
 - **Authors:** Yuanhang Lei, Tao Cheng, Xingxuan Li, Boming Zhao, Siyuan Huang, Ruizhen Hu, Peter Yichen Chen, Hujun Bao, Zhaopeng Cui
 - **Subjects:** Subjects:
Graphics (cs.GR); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Achieving real-time physics-based animation that generalizes across diverse 3D shapes and discretizations remains a fundamental challenge. We introduce PhysSkin, a physics-informed framework that addresses this challenge. In the spirit of Linear Blend Skinning, we learn continuous skinning fields as basis functions lifting motion subspace coordinates to full-space deformation, with subspace defined by handle transformations. To generate mesh-free, discretization-agnostic, and physically consistent skinning fields that generalize well across diverse 3D shapes, PhysSkin employs a new neural skinning fields autoencoder which consists of a transformer-based encoder and a cross-attention decoder. Furthermore, we also develop a novel physics-informed self-supervised learning strategy that incorporates on-the-fly skinning-field normalization and conflict-aware gradient correction, enabling effective balancing of energy minimization, spatial smoothness, and orthogonality constraints. PhysSkin shows outstanding performance on generalizable neural skinning and enables real-time physics-based animation.
### Title:
          Gaze-Regularized Vision-Language-Action Models for Robotic Manipulation
 - **Authors:** Anupam Pani, Yanchao Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Despite advances in Vision-Language-Action (VLA) models, robotic manipulation struggles with fine-grained tasks because current models lack mechanisms for active visual attention allocation. Human gaze naturally encodes intent, planning, and execution patterns -- offering a powerful supervisory signal for guiding robot perception. We introduce a gaze-regularized training framework that aligns VLA models' internal attention with human visual patterns without architectural modifications or inference-time overhead. Our method transforms temporally aggregated gaze heatmaps into patch-level distributions and regularizes the transformer's attention through KL divergence, creating an inductive bias toward task-relevant features while preserving deployment efficiency. When integrated into existing VLA architectures, our approach yields 4-12% improvements across manipulation benchmarks. The gaze-regularized models reach equivalent performance with fewer training steps and maintain robustness under lighting variations and sensor noise. Beyond performance metrics, the learned attention patterns produce interpretable visualizations that mirror human strategies, enhancing trust in robotic systems. Moreover, our framework requires no eye-tracking equipment and applies directly to existing datasets. These results demonstrate that human perceptual priors can significantly accelerate robot learning while improving both task performance and system interpretability.
### Title:
          Decoding AI Authorship: Can LLMs Truly Mimic Human Style Across Literature and Politics?
 - **Authors:** Nasser A Alsadhan
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Amidst the rising capabilities of generative AI to mimic specific human styles, this study investigates the ability of state-of-the-art large language models (LLMs), including GPT-4o, Gemini 1.5 Pro, and Claude Sonnet 3.5, to emulate the authorial signatures of prominent literary and political figures: Walt Whitman, William Wordsworth, Donald Trump, and Barack Obama. Utilizing a zero-shot prompting framework with strict thematic alignment, we generated synthetic corpora evaluated through a complementary framework combining transformer-based classification (BERT) and interpretable machine learning (XGBoost). Our methodology integrates Linguistic Inquiry and Word Count (LIWC) markers, perplexity, and readability indices to assess the divergence between AI-generated and human-authored text. Results demonstrate that AI-generated mimicry remains highly detectable, with XGBoost models trained on a restricted set of eight stylometric features achieving accuracy comparable to high-dimensional neural classifiers. Feature importance analyses identify perplexity as the primary discriminative metric, revealing a significant divergence in the stochastic regularity of AI outputs compared to the higher variability of human writing. While LLMs exhibit distributional convergence with human authors on low-dimensional heuristic features, such as syntactic complexity and readability, they do not yet fully replicate the nuanced affective density and stylistic variance inherent in the human-authored corpus. By isolating the specific statistical gaps in current generative mimicry, this study provides a comprehensive benchmark for LLM stylistic behavior and offers critical insights for authorship attribution in the digital humanities and social media.
### Title:
          ViBe: Ultra-High-Resolution Video Synthesis Born from Pure Images
 - **Authors:** Yunfeng Wu, Hongying Cheng, Zihao He, Songhua Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based video diffusion models rely on 3D attention over spatial and temporal tokens, which incurs quadratic time and memory complexity and makes end-to-end training for ultra-high-resolution videos prohibitively expensive. To overcome this bottleneck, we propose a pure image adaptation framework that upgrades a video Diffusion Transformer pre-trained at its native scale to synthesize higher-resolution videos. Unfortunately, naively fine-tuning with high-resolution images alone often introduces noticeable noise due to the image-video modality gap. To address this, we decouple the learning objective to separately handle modality alignment and spatial extrapolation. At the core of our approach is Relay LoRA, a two-stage adaptation strategy. In the first stage, the video diffusion model is adapted to the image domain using low-resolution images to bridge the modality gap. In the second stage, the model is further adapted with high-resolution images to acquire spatial extrapolation capability. During inference, only the high-resolution adaptation is retained to preserve the video generation modality while enabling high-resolution video synthesis. To enhance fine-grained detail synthesis, we further propose a High-Frequency-Awareness-Training-Objective, which explicitly encourages the model to recover high-frequency components from degraded latent representations via a dedicated reconstruction loss. Extensive experiments demonstrate that our method produces ultra-high-resolution videos with rich visual details without requiring any video training data, even outperforming previous state-of-the-art models trained on high-resolution videos by 0.8 on the VBench benchmark. Code will be available at this https URL.
### Title:
          FHAvatar: Fast and High-Fidelity Reconstruction of Face-and-Hair Composable 3D Head Avatar from Few Casual Captures
 - **Authors:** Yujie Sun, Zhuoqiang Cai, Chaoyue Niu, Jianchuan Chen, Zhiwen Chen, Chengfei Lv, Fan Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present FHAvatar, a novel framework for reconstructing 3D Gaussian avatars with composable face and hair components from an arbitrary number of views. Unlike previous approaches that couple facial and hair representations within a unified modeling process, we explicitly decouple two components in texture space by representing the face with planar Gaussians and the hair with strand-based Gaussians. To overcome the limitations of existing methods that rely on dense multi-view captures or costly per-identity optimization, we propose an aggregated transformer backbone to learn geometry-aware cross-view priors and head-hair structural coherence from multi-view datasets, enabling effective and efficient feature extraction and fusion from few casual captures. Extensive quantitative and qualitative experiments demonstrate that FHAvatar achieves state-of-the-art reconstruction quality from only a few observations of new identities within minutes, while supporting real-time animation, convenient hairstyle transfer, and stylized editing, broadening the accessibility and applicability of digital avatar creation.
### Title:
          Object Pose Transformer: Unifying Unseen Object Pose Estimation
 - **Authors:** Weihang Li, Lorenzo Garattoni, Fabien Despinoy, Nassir Navab, Benjamin Busam
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Learning model-free object pose estimation for unseen instances remains a fundamental challenge in 3D vision. Existing methods typically fall into two disjoint paradigms: category-level approaches predict absolute poses in a canonical space but rely on predefined taxonomies, while relative pose methods estimate cross-view transformations but cannot recover single-view absolute pose. In this work, we propose Object Pose Transformer (\ours{}), a unified feed-forward framework that bridges these paradigms through task factorization within a single model. \ours{} jointly predicts depth, point maps, camera parameters, and normalized object coordinates (NOCS) from RGB inputs, enabling both category-level absolute SA(3) pose and unseen-object relative SE(3) pose. Our approach leverages contrastive object-centric latent embeddings for canonicalization without requiring semantic labels at inference time, and uses point maps as a camera-space representation to enable multi-view relative geometric reasoning. Through cross-frame feature interaction and shared object embeddings, our model leverages relative geometric consistency across views to improve absolute pose estimation, reducing ambiguity in single-view predictions. Furthermore, \ours{} is camera-agnostic, learning camera intrinsics on-the-fly and supporting optional depth input for metric-scale recovery, while remaining fully functional in RGB-only settings. Extensive experiments on diverse benchmarks (NOCS, HouseCat6D, Omni6DPose, Toyota-Light) demonstrate state-of-the-art performance in both absolute and relative pose estimation tasks within a single unified architecture.
### Title:
          ABot-PhysWorld: Interactive World Foundation Model for Robotic Manipulation with Physics Alignment
 - **Authors:** Yuzhi Chen, Ronghan Chen, Dongjie Huo, Yandan Yang, Dekang Qi, Haoyun Liu, Tong Lin, Shuang Zeng, Junjin Xiao, Xinyuan Chang, Feng Xiong, Xing Wei, Zhiheng Ma, Mu Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video-based world models offer a powerful paradigm for embodied simulation and planning, yet state-of-the-art models often generate physically implausible manipulations - such as object penetration and anti-gravity motion - due to training on generic visual data and likelihood-based objectives that ignore physical laws. We present ABot-PhysWorld, a 14B Diffusion Transformer model that generates visually realistic, physically plausible, and action-controllable videos. Built on a curated dataset of three million manipulation clips with physics-aware annotation, it uses a novel DPO-based post-training framework with decoupled discriminators to suppress unphysical behaviors while preserving visual quality. A parallel context block enables precise spatial action injection for cross-embodiment control. To better evaluate generalization, we introduce EZSbench, the first training-independent embodied zero-shot benchmark combining real and synthetic unseen robot-task-scene combinations. It employs a decoupled protocol to separately assess physical realism and action alignment. ABot-PhysWorld achieves new state-of-the-art performance on PBench and EZSbench, surpassing Veo 3.1 and Sora v2 Pro in physical plausibility and trajectory consistency. We will release EZSbench to promote standardized evaluation in embodied video generation.
### Title:
          Harnessing Lightweight Transformer with Contextual Synergic Enhancement for Efficient 3D Medical Image Segmentation
 - **Authors:** Xinyu Liu, Zhen Chen, Wuyang Li, Chenxin Li, Yixuan Yuan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers have shown remarkable performance in 3D medical image segmentation, but their high computational requirements and need for large amounts of labeled data limit their applicability. To address these challenges, we consider two crucial aspects: model efficiency and data efficiency. Specifically, we propose Light-UNETR, a lightweight transformer designed to achieve model efficiency. Light-UNETR features a Lightweight Dimension Reductive Attention (LIDR) module, which reduces spatial and channel dimensions while capturing both global and local features via multi-branch attention. Additionally, we introduce a Compact Gated Linear Unit (CGLU) to selectively control channel interaction with minimal parameters. Furthermore, we introduce a Contextual Synergic Enhancement (CSE) learning strategy, which aims to boost the data efficiency of Transformers. It first leverages the extrinsic contextual information to support the learning of unlabeled data with Attention-Guided Replacement, then applies Spatial Masking Consistency that utilizes intrinsic contextual information to enhance the spatial context reasoning for unlabeled data. Extensive experiments on various benchmarks demonstrate the superiority of our approach in both performance and efficiency. For example, with only 10% labeled data on the Left Atrial Segmentation dataset, our method surpasses BCP by 1.43% Jaccard while drastically reducing the FLOPs by 90.8% and parameters by 85.8%. Code is released at this https URL.
### Title:
          VTAM: Video-Tactile-Action Models for Complex Physical Interaction Beyond VLAs
 - **Authors:** Haoran Yuan, Weigang Yi, Zhenyu Zhang, Wendi Chen, Yuchen Mo, Jiashi Yin, Xinzhuo Li, Xiangyu Zeng, Chuan Wen, Cewu Lu, Katherine Driggs-Campbell, Ismini Lourentzou
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video-Action Models (VAMs) have emerged as a promising framework for embodied intelligence, learning implicit world dynamics from raw video streams to produce temporally consistent action predictions. Although such models demonstrate strong performance on long-horizon tasks through visual reasoning, they remain limited in contact-rich scenarios where critical interaction states are only partially observable from vision alone. In particular, fine-grained force modulation and contact transitions are not reliably encoded in visual tokens, leading to unstable or imprecise behaviors. To bridge this gap, we introduce the Video-Tactile Action Model (VTAM), a multimodal world modeling framework that incorporates tactile perception as a complementary grounding signal. VTAM augments a pretrained video transformer with tactile streams via a lightweight modality transfer finetuning, enabling efficient cross-modal representation learning without tactile-language paired data or independent tactile pretraining. To stabilize multimodal fusion, we introduce a tactile regularization loss that enforces balanced cross-modal attention, preventing visual latent dominance in the action model. VTAM demonstrates superior performance in contact-rich manipulation, maintaining a robust success rate of 90 percent on average. In challenging scenarios such as potato chip pick-and-place requiring high-fidelity force awareness, VTAM outperforms the pi 0.5 baseline by 80 percent. Our findings demonstrate that integrating tactile feedback is essential for correcting visual estimation errors in world action models, providing a scalable approach to physically grounded embodied foundation models.
### Title:
          TETO: Tracking Events with Teacher Observation for Motion Estimation and Frame Interpolation
 - **Authors:** Jini Yang, Eunbeen Hong, Soowon Son, Hyunkoo Lee, Sunghwan Hong, Sunok Kim, Seungryong Kim
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Event cameras capture per-pixel brightness changes with microsecond resolution, offering continuous motion information lost between RGB frames. However, existing event-based motion estimators depend on large-scale synthetic data that often suffers from a significant sim-to-real gap. We propose TETO (Tracking Events with Teacher Observation), a teacher-student framework that learns event motion estimation from only $\sim$25 minutes of unannotated real-world recordings through knowledge distillation from a pretrained RGB tracker. Our motion-aware data curation and query sampling strategy maximizes learning from limited data by disentangling object motion from dominant ego-motion. The resulting estimator jointly predicts point trajectories and dense optical flow, which we leverage as explicit motion priors to condition a pretrained video diffusion transformer for frame interpolation. We achieve state-of-the-art point tracking on EVIMO2 and optical flow on DSEC using orders of magnitude less training data, and demonstrate that accurate motion estimation translates directly to superior frame interpolation quality on BS-ERGB and HQ-EVFI.
## Keyword: autonomous driving
### Title:
          Typography-Based Monocular Distance Estimation Framework for Vehicle Safety Systems
 - **Authors:** Manognya Lokesh Reddy, Zheng Liu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate inter-vehicle distance estimation is a cornerstone of advanced driver assistance systems and autonomous driving. While LiDAR and radar provide high precision, their cost prohibits widespread adoption in mass-market vehicles. Monocular vision offers a low-cost alternative but suffers from scale ambiguity and sensitivity to environmental disturbances. This paper introduces a typography-based monocular distance estimation framework, which exploits the standardized typography of license plates as passive fiducial markers for metric distance estimation. The core geometric module uses robust plate detection and character segmentation to measure character height and computes distance via the pinhole camera model. The system incorporates interactive calibration, adaptive detection with strict and permissive modes, and multi-method character segmentation leveraging both adaptive and global thresholding. To enhance robustness, the framework further includes camera pose compensation using lane-based horizon estimation, hybrid deep-learning fusion, temporal Kalman filtering for velocity estimation, and multi-feature fusion that exploits additional typographic cues such as stroke width, character spacing, and plate border thickness. Experimental validation with a calibrated monocular camera in a controlled indoor setup achieved a coefficient of variation of 2.3% in character height across consecutive frames and a mean absolute error of 7.7%. The framework operates without GPU acceleration, demonstrating real-time feasibility. A comprehensive comparison with a plate-width based method shows that character-based ranging reduces the standard deviation of estimates by 35%, translating to smoother, more consistent distance readings in practice, where erratic estimates could trigger unnecessary braking or acceleration.
### Title:
          Gau-Occ: Geometry-Completed Gaussians for Multi-Modal 3D Occupancy Prediction
 - **Authors:** Chengxin Lv, Yihui Li, Hongyu Yang, YunHong Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D semantic occupancy prediction is crucial for autonomous driving. While multi-modal fusion improves accuracy over vision-only methods, it typically relies on computationally expensive dense voxel or BEV tensors. We present Gau-Occ, a multi-modal framework that bypasses dense volumetric processing by modeling the scene as a compact collection of semantic 3D Gaussians. To ensure geometric completeness, we propose a LiDAR Completion Diffuser (LCD) that recovers missing structures from sparse LiDAR to initialize robust Gaussian anchors. Furthermore, we introduce Gaussian Anchor Fusion (GAF), which efficiently integrates multi-view image semantics via geometry-aligned 2D sampling and cross-modal alignment. By refining these compact Gaussian descriptors, Gau-Occ captures both spatial consistency and semantic discriminability. Extensive experiments across challenging benchmarks demonstrate that Gau-Occ achieves state-of-the-art performance with significant computational efficiency.
### Title:
          Traffic Sign Recognition in Autonomous Driving: Dataset, Benchmark, and Field Experiment
 - **Authors:** Guoyang Zhao, Weiqing Qi, Kai Zhang, Chenguang Zhang, Zeying Gong, Zhihai Bi, Kai Chen, Benshan Ma, Ming Liu, Jun Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traffic Sign Recognition (TSR) is a core perception capability for autonomous driving, where robustness to cross-region variation, long-tailed categories, and semantic ambiguity is essential for reliable real-world deployment. Despite steady progress in recognition accuracy, existing traffic sign datasets and benchmarks offer limited diagnostic insight into how different modeling paradigms behave under these practical challenges. We present TS-1M, a large-scale and globally diverse traffic sign dataset comprising over one million real-world images across 454 standardized categories, together with a diagnostic benchmark designed to analyze model capability boundaries. Beyond standard train-test evaluation, we provide a suite of challenge-oriented settings, including cross-region recognition, rare-class identification, low-clarity robustness, and semantic text understanding, enabling systematic and fine-grained assessment of modern TSR models. Using TS-1M, we conduct a unified benchmark across three representative learning paradigms: classical supervised models, self-supervised pretrained models, and multimodal vision-language models (VLMs). Our analysis reveals consistent paradigm-dependent behaviors, showing that semantic alignment is a key factor for cross-region generalization and rare-category recognition, while purely visual models remain sensitive to appearance shift and data imbalance. Finally, we validate the practical relevance of TS-1M through real-scene autonomous driving experiments, where traffic sign recognition is integrated with semantic reasoning and spatial localization to support map-level decision constraints. Overall, TS-1M establishes a reference-level diagnostic benchmark for TSR and provides principled insights into robust and semantic-aware traffic sign perception. Project page: this https URL.
### Title:
          PoseDriver: A Unified Approach to Multi-Category Skeleton Detection for Autonomous Driving
 - **Authors:** Yasamin Borhani, Taylor Mordan, Yihan Wang, Reyhaneh Hosseininejad, Javad Khoramdel, Alexandre Alahi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Object skeletons offer a concise representation of structural information, capturing essential aspects of posture and orientation that are crucial for autonomous driving applications. However, a unified architecture that simultaneously handles multiple instances and categories using only the input image remains elusive. In this paper, we introduce PoseDriver, a unified framework for bottom-up multi-category skeleton detection tailored to common objects in driving scenarios. We model each category as a distinct task to systematically address the challenges of multi-task learning. Specifically, we propose a novel approach for lane detection based on skeleton representations, achieving state-of-the-art performance on the OpenLane dataset. Moreover, we present a new dataset for bicycle skeleton detection and assess the transferability of our framework to novel categories. Experimental results validate the effectiveness of the proposed approach.
### Title:
          Modeling Edge-to-Cloud Offloading Workloads for Autonomous Vehicles
 - **Authors:** Longkun Li, Evangelos Pournaras
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles generate large volumes of data for applications such as fleet monitoring, model retraining, and high-definition map updates. Existing studies often rely on generic traffic traces, which do not capture the characteristics of autonomous driving workloads. This paper proposes a system-level workload modeling framework for vehicle-to-cloud data. We classify offloaded data into three types: telemetry, event-driven fleet learning, and high-definition map updates, while we model their generation using a parameterized formulation based on empirical data. Using a real-world mobility trace from Munich, we analyze the resulting workloads over time and space. The results show that workload scales with vehicle penetration, exhibits temporal structure and spatial imbalance across access points, and is distinguished from baseline traffic models.
### Title:
          Rectify, Don't Regret: Avoiding Pitfalls of Differentiable Simulation in Trajectory Prediction
 - **Authors:** Harsh Yadav, Christian Bohn, Tobias Meisen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current open-loop trajectory models struggle in real-world autonomous driving because minor initial deviations often cascade into compounding errors, pushing the agent into out-of-distribution states. While fully differentiable closed-loop simulators attempt to address this, they suffer from shortcut learning: the loss gradients flow backward through induced state inputs, inadvertently leaking future ground truth information directly into the model's own previous predictions. The model exploits these signals to artificially avoid drift, non-causally "regretting" past mistakes rather than learning genuinely reactive recovery. To address this, we introduce a detached receding horizon rollout. By explicitly severing the computation graph between simulation steps, the model learns genuine recovery behaviors from drifted states, forcing it to "rectify" mistakes rather than non-causally optimizing past predictions. Extensive evaluations on the nuScenes and DeepScenario datasets show our approach yields more robust recovery strategies, reducing target collisions by up to 33.24% compared to fully differentiable closed-loop training at high replanning frequencies. Furthermore, compared to standard open-loop baselines, our non-differentiable framework decreases collisions by up to 27.74% in dense environments while simultaneously improving multi-modal prediction diversity and lane alignment.
