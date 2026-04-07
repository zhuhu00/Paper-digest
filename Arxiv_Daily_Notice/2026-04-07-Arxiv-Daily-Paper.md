# Showing new listings for Tuesday, 7 April 2026
## Keyword: SLAM
### Title:
          MPTF-Net: Multi-view Pyramid Transformer Fusion Network for LiDAR-based Place Recognition
 - **Authors:** Shuyuan Li, Zihang Wang, Xieyuanli Chen, Wenkai Zhu, Xiaoteng Fang, Peizhou Ni, Junhao Yang, Dong Kong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based place recognition (LPR) is essential for global localization and loop-closure detection in large-scale SLAM systems. Existing methods typically construct global descriptors from Range Images or BEV representations for matching. BEV is widely adopted due to its explicit 2D spatial layout encoding and efficient retrieval. However, conventional BEV representations rely on simple statistical aggregation, which fails to capture fine-grained geometric structures, leading to performance degradation in complex or repetitive environments. To address this, we propose MPTF-Net, a novel multi-view multi-scale pyramid Transformer fusion network. Our core contribution is a multi-channel NDT-based BEV encoding that explicitly models local geometric complexity and intensity distributions via Normal Distribution Transform, providing a noise-resilient structural prior. To effectively integrate these features, we develop a customized pyramid Transformer module that captures cross-view interactive correlations between Range Image Views (RIV) and NDT-BEV at multiple spatial scales. Extensive experiments on the nuScenes, KITTI and NCLT datasets demonstrate that MPTF-Net achieves state-of-the-art performance, specifically attaining a Recall@1 of 96.31\% on the nuScenes Boston split while maintaining an inference latency of only 10.02 ms, making it highly suitable for real-time autonomous unmanned systems.
### Title:
          Relational Epipolar Graphs for Robust Relative Camera Pose Estimation
 - **Authors:** Prateeth Rao, Sachit Rao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A key component of Visual Simultaneous Localization and Mapping (VSLAM) is estimating relative camera poses using matched keypoints. Accurate estimation is challenged by noisy correspondences. Classical methods rely on stochastic hypothesis sampling and iterative estimation, while learning-based methods often lack explicit geometric structure. In this work, we reformulate relative pose estimation as a relational inference problem over epipolar correspondence graphs, where matched keypoints are nodes and nearby ones are connected by edges. Graph operations such as pruning, message passing, and pooling estimate a quaternion rotation, translation vector, and the Essential Matrix (EM). Minimizing a loss comprising (i) $\mathcal{L}_2$ differences with ground truth (GT), (ii) Frobenius norm between estimated and GT EMs, (iii) singular value differences, (iv) heading angle differences, and (v) scale differences, yields the relative pose between image pairs. The dense detector-free method LoFTR is used for matching. Experiments on indoor and outdoor benchmarks show improved robustness to dense noise and large baseline variation compared to classical and learning-guided approaches, highlighting the effectiveness of global relational consensus.
### Title:
          WaterSplat-SLAM: Photorealistic Monocular SLAM in Underwater Environment
 - **Authors:** Kangxu Wang, Shaofeng Zou, Chenxing Jiang, Yixiang Dai, Siang Chen, Shaojie Shen, Guijin Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Underwater monocular SLAM is a challenging problem with applications from autonomous underwater vehicles to marine archaeology. However, existing underwater SLAM methods struggle to produce maps with high-fidelity rendering. In this paper, we propose WaterSplat-SLAM, a novel monocular underwater SLAM system that achieves robust pose estimation and photorealistic dense mapping. Specifically, we couple semantic medium filtering into two-view 3D reconstruction prior to enable underwater-adapted camera tracking and depth estimation. Furthermore, we present a semantic-guided rendering and adaptive map management strategy with an online medium-aware Gaussian map, modeling underwater environment in a photorealistic and compact manner. Experiments on multiple underwater datasets demonstrate that WaterSplat-SLAM achieves robust camera tracking and high-fidelity rendering in underwater environments.
### Title:
          ZeD-MAP: Bundle Adjustment Guided Zero-Shot Depth Maps for Real-Time Aerial Imaging
 - **Authors:** Selim Ahmet Iz, Francesco Nex, Norman Kerle, Henry Meissner, Ralf Berger
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time depth reconstruction from ultra-high-resolution UAV imagery is essential for time-critical geospatial tasks such as disaster response, yet remains challenging due to wide-baseline parallax, large image sizes, low-texture or specular surfaces, occlusions, and strict computational constraints. Recent zero-shot diffusion models offer fast per-image dense predictions without task-specific retraining, and require fewer labelled datasets than transformer-based predictors while avoiding the rigid capture geometry requirement of classical multi-view stereo. However, their probabilistic inference prevents reliable metric accuracy and temporal consistency across sequential frames and overlapping tiles. We present ZeD-MAP, a cluster-level framework that converts a test-time diffusion depth model into a metrically consistent, SLAM-like mapping pipeline by integrating incremental cluster-based bundle adjustment (BA). Streamed UAV frames are grouped into overlapping clusters; periodic BA produces metrically consistent poses and sparse 3D tie-points, which are reprojected into selected frames and used as metric guidance for diffusion-based depth estimation. Validation on ground-marker flights captured at approximately 50 m altitude (GSD is approximately 0.85 cm/px, corresponding to 2,650 square meters ground coverage per frame) with the DLR Modular Aerial Camera System (MACS) shows that our method achieves sub-meter accuracy, with approximately 0.87 m error in the horizontal (XY) plane and 0.12 m in the vertical (Z) direction, while maintaining per-image runtimes between 1.47 and 4.91 seconds. Results are subject to minor noise from manual point-cloud annotation. These findings show that BA-based metric guidance provides consistency comparable to classical photogrammetric methods while significantly accelerating processing, enabling real-time 3D map generation.
## Keyword: odometry
### Title:
          ViBA: Implicit Bundle Adjustment with Geometric and Temporal Consistency for Robust Visual Matching
 - **Authors:** Xiaoji Niu, Yuqing Wang, Yan Wang, Hailiang Tang, Tisheng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most existing image keypoint detection and description methods rely on datasets with accurate pose and depth annotations, limiting scalability and generalization, and often degrading navigation and localization performance. We propose ViBA, a sustainable learning framework that integrates geometric optimization with feature learning for continuous online training on unconstrained video streams. Embedded in a standard visual odometry pipeline, it consists of an implicitly differentiable geometric residual framework: (i) an initial tracking network for inter-frame correspondences, (ii) depth-based outlier filtering, and (iii) differentiable global bundle adjustment that jointly refines camera poses and feature positions by minimizing reprojection errors. By combining geometric consistency from BA with long-term temporal consistency across frames, ViBA enforces stable and accurate feature representations. We evaluate ViBA on EuRoC and UMA datasets. Compared with state-of-the-art methods such as SuperPoint+SuperGlue, ALIKED, and LightGlue, ViBA reduces mean absolute translation error (ATE) by 12-18% and absolute rotation error (ARE) by 5-10% across sequences, while maintaining real-time inference speeds (FPS 36-91). When evaluated on unseen sequences, it retains over 90% localization accuracy, demonstrating robust generalization. These results show that ViBA supports continuous online learning with geometric and temporal consistency, consistently improving navigation and localization in real-world scenarios.
### Title:
          DSERT-RoLL: Robust Multi-Modal Perception for Diverse Driving Conditions with Stereo Event-RGB-Thermal Cameras, 4D Radar, and Dual-LiDAR
 - **Authors:** Hoonhee Cho, Jae-Young Kang, Yuhwan Jeong, Yunseo Yang, Wonyoung Lee, Youngho Kim, Kuk-Jin Yoon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we present DSERT-RoLL, a driving dataset that incorporates stereo event, RGB, and thermal cameras together with 4D radar and dual LiDAR, collected across diverse weather and illumination conditions. The dataset provides precise 2D and 3D bounding boxes with track IDs and ego vehicle odometry, enabling fair comparisons within and across sensor combinations. It is designed to alleviate data scarcity for novel sensors such as event cameras and 4D radar and to support systematic studies of their behavior. We establish unified 3D and 2D benchmarks that enable direct comparison of characteristics and strengths across sensor families and within each family. We report baselines for representative single modality and multimodal methods and provide protocols that encourage research on different fusion strategies and sensor combinations. In addition, we propose a fusion framework that integrates sensor specific cues into a unified feature space and improves 3D detection robustness under varied weather and lighting.
### Title:
          CT-VoxelMap: Efficient Continuous-Time LiDAR-Inertial Odometry with Probabilistic Adaptive Voxel Mapping
 - **Authors:** Lei Zhao, Xingyi Li, Tianchen Deng, Chuan Cao, Han Zhang, Weidong Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Maintaining stable and accurate localization during fast motion or on rough terrain remains highly challenging for mobile robots with onboard resources. Currently, multi-sensor fusion methods based on continuous-time representation offer a potential and effective solution to this challenge. Among these, spline-based methods provide an efficient and intuitive approach for continuous-time representation. Previous continuous-time odometry works based on B-splines either treat control points as variables to be estimated or perform estimation in quaternion space, which introduces complexity in deriving analytical Jacobians and often overlooks the fitting error between the spline and the true trajectory over time. To address these issues, we first propose representing the increments of control points on matrix Lie groups as variables to be estimated. Leveraging the feature of the cumulative form of B-splines, we derive a more compact formulation that yields simpler analytical Jacobians without requiring additional boundary condition considerations. Second, we utilize forward propagation information from IMU measurements to estimate fitting errors online and further introduce a hybrid feature-based voxel map management strategy, enhancing system accuracy and robustness. Finally, we propose a re-estimation policy that significantly improves system computational efficiency and robustness. The proposed method is evaluated on multiple challenging public datasets, demonstrating superior performance on most sequences. Detailed ablation studies are conducted to analyze the impact of each module on the overall pose estimation system.
### Title:
          DINO-VO: Learning Where to Focus for Enhanced State Estimation
 - **Authors:** Qi Chen, Guanghao Li, Sijia Hu, Xin Gao, Junpeng Ma, Xiangyang Xue, Jian Pu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present DINO Patch Visual Odometry (DINO-VO), an end-to-end monocular visual odometry system with strong scene generalization. Current Visual Odometry (VO) systems often rely on heuristic feature extraction strategies, which can degrade accuracy and robustness, particularly in large-scale outdoor environments. DINO-VO addresses these limitations by incorporating a differentiable adaptive patch selector into the end-to-end pipeline, improving the quality of extracted patches and enhancing generalization across diverse datasets. Additionally, our system integrates a multi-task feature extraction module with a differentiable bundle adjustment (BA) module that leverages inverse depth priors, enabling the system to learn and utilize appearance and geometric information effectively. This integration bridges the gap between feature learning and state estimation. Extensive experiments on the TartanAir, KITTI, Euroc, and TUM datasets demonstrate that DINO-VO exhibits strong generalization across synthetic, indoor, and outdoor environments, achieving state-of-the-art tracking accuracy.
### Title:
          G-EDF-Loc: 3D Continuous Gaussian Distance Field for Robust Gradient-Based 6DoF Localization
 - **Authors:** José E. Maese, Lucía Coto-Elena, Luis Merino, Fernando Caballero
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a robust 6-DoF localization framework based on a direct, CPU-based scan-to-map registration pipeline. The system leverages G-EDF, a novel continuous and memory-efficient 3D distance field representation. The approach models the Euclidean Distance Field (EDF) using a Block-Sparse Gaussian Mixture Model with adaptive spatial partitioning, ensuring $C^1$ continuity across block transitions and mitigating boundary artifacts. By leveraging the analytical gradients of this continuous map, which maintain Eikonal consistency, the proposed method achieves high-fidelity spatial reconstruction and real-time localization. Experimental results on large-scale datasets demonstrate that G-EDF-Loc performs competitively against state-of-the-art methods, exhibiting exceptional resilience even under severe odometry degradation or in the complete absence of IMU priors.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          DSERT-RoLL: Robust Multi-Modal Perception for Diverse Driving Conditions with Stereo Event-RGB-Thermal Cameras, 4D Radar, and Dual-LiDAR
 - **Authors:** Hoonhee Cho, Jae-Young Kang, Yuhwan Jeong, Yunseo Yang, Wonyoung Lee, Youngho Kim, Kuk-Jin Yoon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we present DSERT-RoLL, a driving dataset that incorporates stereo event, RGB, and thermal cameras together with 4D radar and dual LiDAR, collected across diverse weather and illumination conditions. The dataset provides precise 2D and 3D bounding boxes with track IDs and ego vehicle odometry, enabling fair comparisons within and across sensor combinations. It is designed to alleviate data scarcity for novel sensors such as event cameras and 4D radar and to support systematic studies of their behavior. We establish unified 3D and 2D benchmarks that enable direct comparison of characteristics and strengths across sensor families and within each family. We report baselines for representative single modality and multimodal methods and provide protocols that encourage research on different fusion strategies and sensor combinations. In addition, we propose a fusion framework that integrates sensor specific cues into a unified feature space and improves 3D detection robustness under varied weather and lighting.
### Title:
          Spatiotemporal Interpolation of GEDI Biomass with Calibrated Uncertainty
 - **Authors:** Robin Young, Srinivasan Keshav
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monitoring deforestation-driven carbon emissions requires both spatially explicit and temporally continuous estimates of aboveground biomass density (AGBD) with calibrated uncertainty. NASA's Global Ecosystem Dynamics Investigation (GEDI) provides reliable LIDAR-derived AGBD, but its orbital sampling causes irregular spatiotemporal coverage, and occasional operational interruptions, including a 13-month hibernation from March 2023 to April 2024, leave extended gaps in the observational record. Prior work has used machine learning approaches to fill GEDI's spatial gaps using satellite-derived features, but temporal interpolation of biomass through unobserved periods, particularly across active disturbance events, remains largely unaddressed. Moreover, standard ensemble methods for biomass mapping have been shown to produce systematically miscalibrated prediction intervals. To address these gaps, we extend the Attentive Neural Process (ANP) framework, previously applied to spatial biomass interpolation, to jointly sparse spatiotemporal settings using geospatial foundation model embeddings. We treat space and time symmetrically, empirically validating a form of space-for-time substitution in which observations from nearby locations at other times inform predictions at held-out periods. Our results demonstrate that the ANP produces well-calibrated uncertainty estimates across disturbance regimes, supporting its use in Measurement, Reporting, and Verification (MRV) applications that require reliable uncertainty quantification for forest carbon accounting.
### Title:
          MPTF-Net: Multi-view Pyramid Transformer Fusion Network for LiDAR-based Place Recognition
 - **Authors:** Shuyuan Li, Zihang Wang, Xieyuanli Chen, Wenkai Zhu, Xiaoteng Fang, Peizhou Ni, Junhao Yang, Dong Kong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based place recognition (LPR) is essential for global localization and loop-closure detection in large-scale SLAM systems. Existing methods typically construct global descriptors from Range Images or BEV representations for matching. BEV is widely adopted due to its explicit 2D spatial layout encoding and efficient retrieval. However, conventional BEV representations rely on simple statistical aggregation, which fails to capture fine-grained geometric structures, leading to performance degradation in complex or repetitive environments. To address this, we propose MPTF-Net, a novel multi-view multi-scale pyramid Transformer fusion network. Our core contribution is a multi-channel NDT-based BEV encoding that explicitly models local geometric complexity and intensity distributions via Normal Distribution Transform, providing a noise-resilient structural prior. To effectively integrate these features, we develop a customized pyramid Transformer module that captures cross-view interactive correlations between Range Image Views (RIV) and NDT-BEV at multiple spatial scales. Extensive experiments on the nuScenes, KITTI and NCLT datasets demonstrate that MPTF-Net achieves state-of-the-art performance, specifically attaining a Recall@1 of 96.31\% on the nuScenes Boston split while maintaining an inference latency of only 10.02 ms, making it highly suitable for real-time autonomous unmanned systems.
## Keyword: loop detection
There is no result 
## Keyword: nerf
There is no result 
## Keyword: mapping
### Title:
          Personalized AI Practice Replicates Learning Rate Regularity at Scale
 - **Authors:** Jocelyn Beauchesne, Christine Maroti, Jeshua Bratman, Jerome Pesenti, Laurence Holt, Alex Tambellini, Allison McGrath, Matthew Guo, Sarah Peterson
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent research demonstrated that students exhibit consistent learning rates across diverse educational contexts. We test these findings using a dataset of 1.8 million (366k post-filtering) student interactions from the digital platform Campus AI providing further evidence to the observation of regularity in learning rate among students. Unlike prior work requiring manual cognitive modeling, Campus AI automatically generates Knowledge Components (KCs) and corresponding exercises, both of which are validated by human experts. This one-to-many mapping facilitates the application of Additive Factors Models to measure learning parameters without complex cognitive modeling. Using mixed-effects logistic regression, we confirmed the core finding of prior work: students displayed substantial variation in initial knowledge ($\text{IQR} = [2.78, 12.18]$ practice opportunities to reach 80% mastery) but remarkably consistent learning rates ($\text{IQR} = [7.01, 8.25]$ opportunities). Furthermore, students using this fully automated system achieved 80% mastery in a median of 7.22 practice opportunities, comparable to the 6.54 reported for expert-designed curricula. These results suggest that automated, science-grounded content generation can support effective personalized learning at scale. Data and code are publicly available. this https URL
### Title:
          NativeTernary: A Self-Delimiting Binary Encoding with Unary Run-Length Hierarchy Markers for Ternary Neural Network Weights, Structured Data, and General Computing Infrastructure
 - **Authors:** Maharshi Savdhariya
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 BitNet b1.58 (Ma et al., 2024) demonstrates that large language models can operate entirely on ternary weights {-1, 0, +1}, yet no native binary wire format exists for such models. NativeTernary closes this gap. We present NativeTernary, a binary encoding scheme that partitions the 2-bit pair space into three data symbols representing ternary values -- either balanced {-1, 0, +1} or unsigned {0, 1, 2} -- and a reserved structural delimiter. The central contribution is the use of unary run-length encoding to represent semantic hierarchy depth: a sequence of N consecutive delimiter pairs denotes a boundary of level N, encoding character, word, sentence, paragraph, and topic boundaries at cost 2, 4, 6, 8, and 10 bits respectively -- proportional to boundary rarity. The choice of which 2-bit pair serves as the delimiter is a design parameter: {11} is the primary embodiment, offering simple OR-gate detection; {00} is an alternative embodiment optimised for ultra-low-power CMOS systems, minimising switching activity. All four bit-pair choices are covered by the patent claims. We present three encoding variants: (1) the primary scheme with {11} as sole delimiter; (2) a dual-starter variant where both {10} and {11} initiate distinct symbol namespaces; and (3) an analysis of unsigned versus balanced ternary data mappings. We describe a path toward ternary-native general computing infrastructure requiring no hardware changes, and outline applications spanning ternary neural network weight storage, hierarchical natural language encoding, edge computing, IoT and satellite telemetry, industrial sensors, automotive systems, medical devices, gaming, and financial tick data. The decoder is a 10-line stateless state machine resilient to bitstream corruption.
### Title:
          Surrogate Model-Based Near-Optimal Gain Selection for Approach-Angle-Constrained Two-Phase Pure Proportional Navigation
 - **Authors:** Abhigyan Roy, Shreeya Padte, Abel Viji George, Vivek A, Satadal Ghosh
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In guidance literature, Pure Proportional Navigation (PPN) guidance is widely used for aerodynamically driven vehicles. A two-phase extension of PPN (2pPPN), which uses different navigation gains for an orientation phase and a final phase, has been presented to achieve any desired approach angle within an angular half-space. Recent studies show that the orientation phase can be realized through multiple feasible trajectories, creating an opportunity to select navigation gains that minimize overall guidance effort. This paper addresses the problem of near-optimal gain selection for given initial and desired terminal engagement geometries. Two optimization problems are considered: i) determination of the optimal orientation-phase gain for a specified final-phase gain, and ii) simultaneously determining the optimal gain pair for both phases that minimizes the total guidance effort. Determining the optimal gains analytically for arbitrary engagement geometries is intractable. Numerical simulations further reveal that these optimal gains vary smoothly with respect to the engagement conditions. Exploiting this property, a neural network (NN)-based regression model is developed in this paper to learn the nonlinear mapping between optimal gains and initial and desired terminal engagement geometries. The trained NN serves as a computationally efficient surrogate for generating the optimal gains manifold, enabling near-optimal realization of 2pPPN guidance. Numerical simulation studies demonstrate that the developed NN-based architecture predicts optimal gains with high accuracy, achieving very high (close to 0.9) value of coefficient of determination.
### Title:
          Neural Operators for Multi-Task Control and Adaptation
 - **Authors:** David Sewell, Xingjian Li, Stepan Tretiakov, Krishna Kumar, David Fridovich-Keil
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operator methods have emerged as powerful tools for learning mappings between infinite-dimensional function spaces, yet their potential in optimal control remains largely unexplored. We focus on multi-task control problems, whose solution is a mapping from task description (e.g., cost or dynamics functions) to optimal control law (e.g., feedback policy). We approximate these solution operators using a permutation-invariant neural operator architecture. Across a range of parametric optimal control environments and a locomotion benchmark, a single operator trained via behavioral cloning accurately approximates the solution operator and generalizes to unseen tasks, out-of-distribution settings, and varying amounts of task observations. We further show that the branch-trunk structure of our neural operator architecture enables efficient and flexible adaptation to new tasks. We develop structured adaptation strategies ranging from lightweight updates to full-network fine-tuning, achieving strong performance across different data and compute settings. Finally, we introduce meta-trained operator variants that optimize the initialization for few-shot adaptation. These methods enable rapid task adaptation with limited data and consistently outperform a popular meta-learning baseline. Together, our results demonstrate that neural operators provide a unified and efficient framework for multi-task control and adaptation.
### Title:
          Sim2Real-AD: A Modular Sim-to-Real Framework for Deploying VLM-Guided Reinforcement Learning in Real-World Autonomous Driving
 - **Authors:** Zilin Huang, Zhengyang Wan, Zihao Sheng, Boyue Wang, Junwei You, Yue Leng, Sikai Chen
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying reinforcement learning policies trained in simulation to real autonomous vehicles remains a fundamental challenge, particularly for VLM-guided RL frameworks whose policies are typically learned with simulator-native observations and simulator-coupled action semantics that are unavailable on physical platforms. This paper presents Sim2Real-AD, a modular framework for zero-shot sim-to-real transfer of CARLA-trained VLM-guided RL policies to full-scale vehicles without any real-world RL training data. The framework decomposes the transfer problem into four components: a Geometric Observation Bridge (GOB) that converts monocular front-view images into simulator-compatible bird's-eye-view (BEV) observations, a Physics-Aware Action Mapping (PAM) that translates policy outputs into platform-agnostic physical commands, a Two-Phase Progressive Training (TPT) strategy that stabilizes adaptation by separating action-space and observation-space transfer, and a Real-time Deployment Pipeline (RDP) that integrates perception, policy inference, control conversion, and safety monitoring for closed-loop execution. Simulation experiments show that the framework preserves the relative performance ordering of representative RL algorithms across different reward paradigms and validate the contribution of each module. Zero-shot deployment on a full-scale Ford E-Transit achieves success rates of 90%, 80%, and 75% in car-following, obstacle avoidance, and stop-sign interaction scenarios, respectively. To the best of our knowledge, this study is among the first to demonstrate zero-shot closed-loop deployment of a CARLA-trained VLM-guided RL policy on a full-scale real vehicle without any real-world RL training data. The demo video and code are available at: this https URL.
### Title:
          Multimodal Urban Tree Detection from Satellite and Street-Level Imagery via Annotation-Efficient Deep Learning Strategies
 - **Authors:** In Seon Kim, Ali Moghimi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Beyond the immediate biophysical benefits, urban trees play a foundational role in environmental sustainability and disaster mitigation. Precise mapping of urban trees is essential for environmental monitoring, post-disaster assessment, and strengthening policy. However, the transition from traditional, labor-intensive field surveys to scalable automated systems remains limited by high annotation costs and poor generalization across diverse urban scenarios. This study introduces a multimodal framework that integrates high-resolution satellite imagery with ground-level Google Street View to enable scalable and detailed urban tree detection under limited-annotation conditions. The framework first leverages satellite imagery to localize tree candidates and then retrieves targeted ground-level views for detailed detection, significantly reducing inefficient street-level sampling. To address the annotation bottleneck, domain adaptation is used to transfer knowledge from an existing annotated dataset to a new region of interest. To further minimize human effort, we evaluated three learning strategies: semi-supervised learning, active learning, and a hybrid approach combining both, using a transformer-based detection model. The hybrid strategy achieved the best performance with an F1-score of 0.90, representing a 12% improvement over the baseline model. In contrast, semi-supervised learning exhibited progressive performance degradation due to confirmation bias in pseudo-labeling, while active learning steadily improved results through targeted human intervention to label uncertain or incorrect predictions. Error analysis further showed that active and hybrid strategies reduced both false positives and false negatives. Our findings highlight the importance of a multimodal approach and guided annotation for scalable, annotation-efficient urban tree mapping to strengthen sustainable city planning.
### Title:
          Physics-Informed Transformer for Real-Time High-Fidelity Topology Optimization
 - **Authors:** Aaron Lutheran, Srijan Das, Alireza Tabarraei
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Topology optimization is used for the design of high-performance structures but remains fundamentally limited by its iterative nature, requiring repeated finite element analyses that prevent real-time deployment and large-scale design exploration. In this work, we introduce a physics-informed transformer architecture that directly learns a non-iterative mapping from boundary conditions, loading configurations, and derived physical fields to optimized structural topologies. By leveraging global self-attention, the proposed model captures long-range mechanical interactions that govern structural response, overcoming the locality limitations of convolutional architectures. A conditioning-token mechanism embeds global problem parameters, while spatially distributed stress and strain energy fields are encoded as patch tokens within a Vision Transformer framework. To ensure physical realism and manufacturability, we incorporate auxiliary loss functions that enforce volume constraints, load adherence, and structural connectivity through a differentiable formulation. The framework is further extended to dynamic loading scenarios using frequency-domain encoding and transfer learning, enabling efficient generalization from static to time-dependent problems. Comprehensive benchmarking demonstrates that the proposed model achieves fidelity beyond that of diffusion models, while requiring only a single forward pass, thereby eliminating iterative inference entirely. This establishes topology optimization as a real-time operator-learning problem, enabling high-fidelity structural design with significant reductions in computational cost.
### Title:
          A Multimodal Foundation Model of Spatial Transcriptomics and Histology for Biological Discovery and Clinical Prediction
 - **Authors:** Jinxi Xiang, Siyu Hou, Yuchen Li, Ryan Quinton, Xiaoming Zhang, Feyisope Eweje, Xiangde Luo, Yijiang Chen, Zhe Li, Colin Bergstrom, Ted Kim, Sierra Willens, Francesca Maria Olguin, Matthew Abikenari, Andrew Heider, Sanjeeth Rajaram, Joel Neal, Maximilian Diehn, Xiang Zhou, Ruijiang Li
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spatial transcriptomics (ST) enables gene expression mapping within anatomical context but remains costly and low-throughput. Hematoxylin and eosin (H\&E) staining offers rich morphology yet lacks molecular resolution. We present \textbf{\ours} (\textbf{S}patial \textbf{T}ranscriptomics and hist\textbf{O}logy \textbf{R}epresentation \textbf{M}odel), a foundation model trained on 1.2 million spatially resolved transcriptomic profiles with matched histology across 18 organs. Using a hierarchical architecture integrating morphological features, gene expression, and spatial context, STORM bridges imaging and omics through robust molecular--morphological representations. STORM enhances spatial domain discovery, producing biologically coherent tissue maps, and outperforms existing methods in predicting spatial gene expression from H\&E images across 11 tumor types. The model is platform-agnostic, performing consistently across Visium, Xenium, Visium HD, and CosMx. Applied to 23 independent cohorts comprising 7,245 patients, STORM significantly improves immunotherapy response prediction and prognostication over established biomarkers, providing a scalable framework for spatially informed discovery and clinical precision medicine.
### Title:
          Beyond Retrieval: Modeling Confidence Decay and Deterministic Agentic Platforms in Generative Engine Optimization
 - **Authors:** XinYu Zhao, ChengYou Li, XiangBao Meng, Kai Zhang, XiaoDong Liu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative Engine Optimization (GEO) is rapidly reshaping digital marketing paradigms in the era of Large Language Models (LLMs). However, current GEO strategies predominantly rely on Retrieval-Augmented Generation (RAG), which inherently suffers from probabilistic hallucinations and the "zero-click" paradox, failing to establish sustainable commercial trust. In this paper, we systematically deconstruct the probabilistic flaws of existing RAG-based GEO and propose a paradigm shift towards deterministic multi-agent intent routing. First, we mathematically formulate Semantic Entropy Drift (SED) to model the dynamic decay of confidence curves in LLMs over continuous temporal and contextual perturbations. To rigorously quantify optimization value in black-box commercial engines, we introduce the Isomorphic Attribution Regression (IAR) model, leveraging a Multi-Agent System (MAS) probe with strict human-in-the-loop physical isolation to enforce hallucination penalties. Furthermore, we architect the Deterministic Agent Handoff (DAH) protocol, conceptualizing an Agentic Trust Brokerage (ATB) ecosystem where LLMs function solely as intent routers rather than final answer generators. We empirically validate this architecture using EasyNote, an industrial AI meeting minutes product by Yishu Technology. By routing the intent of "knowledge graph mapping on an infinite canvas" directly to its specialized proprietary agent via DAH, we demonstrate the reduction of vertical task hallucination rates to near zero. This work establishes a foundational theoretical framework for next-generation GEO and paves the way for a well-ordered, deterministic human-AI collaboration ecosystem.
### Title:
          Region-Based Constellation Designs for Constructive Interference Precoding in MU-MIMO
 - **Authors:** Yupeng Zheng, Chunmei Xu, Jinfei Wang, Yi Ma, Rahim Tafazolli
 - **Subjects:** Subjects:
Information Theory (cs.IT); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The performance of constructive interference precoding (CIP) for multi-user multi-antenna (MU-MIMO) systems is governed by the structure of the constructive interference (CI) regions, yet this is overlooked in conventional constellation design. This work proposes the region-based constellation (RBC) model to lay the foundation for CIP constellation design. An RBC directly defines the mapping between messages and their feasible regions, instead of deriving them from an existing constellation. To provide insight for RBC design, we study the limitations of quadrature-amplitude-modulation (QAM)-based CIP. Analytical results show that the restrictive CI regions of QAM symbols are systematically misaligned with the objective-minimising sign pattern, resulting in a significant gap to the theoretical performance limit. From the perspective of improving sign alignment, two novel RBC schemes with non-convex feasible regions are proposed, namely mirrored-ends QAM (ME-QAM) and real-extended ME-QAM. A low-complexity algorithm is also developed for the resulting mixed-integer quadratic program, achieving a complexity comparable to QAM-based CIP. Simulation results with constellation sizes $\{16,64\}$ demonstrate up to $4$~dB signal-to-noise-ratio gain of the proposed schemes over QAM-based CIP. The proposed RBC model is also applicable to other systems with non-bijective modulation, representing a promising direction for future research.
### Title:
          Mambalaya: Einsum-Based Fusion Optimizations on State-Space Models
 - **Authors:** Toluwanimi O. Odemuyiwa, John D. Owens, Joel S. Emer, Michael Pellauer
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mamba is an emerging, complex workload with various short-range and long-range dependencies, nonlinearities, and elementwise computations that are unable to run at near-peak speeds on modern hardware. Specifically, Mamba's complex dependency graph makes fusion across its full operator cascade difficult, leaving substantial inter-operator memory traffic on the table. To address these challenges, we propose Mambalaya, a novel reconfigurable accelerator that leverages fusion to overcome the limitations of Mamba. We use the recently proposed cascade-of-Einsums abstraction to characterize Mamba's full computational structure, then apply the extended Einsum framework to systematically explore inter-Einsum fusion opportunities. This principled approach yields a series of fusion mappings that reduce off-chip inter-Einsum traffic. These mappings are supported by the underlying Mambalaya architecture. Mambalaya achieves a layer performance speedup of 4.9$\times$ for prefill and 1.9$\times$ for generation over MARCA. In prefill-dominated scenarios, it achieves up to 1.5$\times$ over a recent fine-grained, memory-aware fusion accelerator for Mamba.
### Title:
          Beyond Crash-to-Patch: Patch Evolution for Linux Kernel Repair
 - **Authors:** Luyao Bai, Kenan Alghythee, Hang Zhang, Xiaoguang Wang
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Linux kernel bug repair is typically approached as a direct mapping from crash reports to code patches. In practice, however, kernel fixes undergo iterative revision on mailing lists before acceptance, with reviewer feedback shaping correctness, concurrency handling, and API compliance. This iterative refinement process encodes valuable repair knowledge that existing automated approaches overlook. We present a large-scale study of kernel patch evolution, reconstructing 6946 syzbot-linked bug-fix lifecycles that connect crash reports, reproducers, mailing-list discussions, revision histories, and merged fixes. Our analysis confirms that accepted repairs are frequently non-local and governed by reviewer-enforced constraints not present in bug reports. Building on these insights, we develop PatchAdvisor, a repair framework that integrates retrieval-based memory with a fine-tuned diagnostic advisor to guide a coding agent toward reviewer-aligned patches. Evaluation on temporally held-out syzbot cases demonstrates that leveraging patch-evolution history yields measurable gains in both reviewer-aligned refinement signals and end-to-end repair quality compared to unguided and retrieval-only baselines.
### Title:
          Where to Steer: Input-Dependent Layer Selection for Steering Improves LLM Alignment
 - **Authors:** Soham Gadgil, Chris Lin, Su-In Lee
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Steering vectors have emerged as a lightweight and effective approach for aligning large language models (LLMs) at inference time, enabling modulation over model behaviors by shifting LLM representations towards a target behavior. However, existing methods typically apply steering vectors at a globally fixed layer, implicitly assuming that the optimal intervention layer is invariant across inputs. We argue that this assumption is fundamentally limited, as representations relevant to a target behavior can be encoded at different layers depending on the input. Theoretically, we show that different inputs can require steering at different layers to achieve alignment with a desirable model behavior. We also provide empirical evidence that the optimal steering layer varies substantially across inputs in practice. Motivated by these observations, we introduce Where to Steer (W2S), a framework that adaptively selects the intervention layer conditioned on the input, by learning a mapping from input embeddings to optimal steering layers. Across multiple LLMs and alignment behaviors, W2S consistently outperforms fixed-layer baselines, with improvements in both in-distribution and out-of-distribution settings. Our findings highlight the importance of input-dependent control in LLM alignment and demonstrate that adaptive layer selection is a key design dimension missing in the current methodology of steering vectors.
### Title:
          Spatiotemporal Interpolation of GEDI Biomass with Calibrated Uncertainty
 - **Authors:** Robin Young, Srinivasan Keshav
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monitoring deforestation-driven carbon emissions requires both spatially explicit and temporally continuous estimates of aboveground biomass density (AGBD) with calibrated uncertainty. NASA's Global Ecosystem Dynamics Investigation (GEDI) provides reliable LIDAR-derived AGBD, but its orbital sampling causes irregular spatiotemporal coverage, and occasional operational interruptions, including a 13-month hibernation from March 2023 to April 2024, leave extended gaps in the observational record. Prior work has used machine learning approaches to fill GEDI's spatial gaps using satellite-derived features, but temporal interpolation of biomass through unobserved periods, particularly across active disturbance events, remains largely unaddressed. Moreover, standard ensemble methods for biomass mapping have been shown to produce systematically miscalibrated prediction intervals. To address these gaps, we extend the Attentive Neural Process (ANP) framework, previously applied to spatial biomass interpolation, to jointly sparse spatiotemporal settings using geospatial foundation model embeddings. We treat space and time symmetrically, empirically validating a form of space-for-time substitution in which observations from nearby locations at other times inform predictions at held-out periods. Our results demonstrate that the ANP produces well-calibrated uncertainty estimates across disturbance regimes, supporting its use in Measurement, Reporting, and Verification (MRV) applications that require reliable uncertainty quantification for forest carbon accounting.
### Title:
          Lotka-Sharpe Neural Operators for Control of Population PDEs
 - **Authors:** Miroslav Krstic, Iasson Karafyllis, Luke Bhan, Carina Veil
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Machine Learning (cs.LG); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Age-structured predator-prey integro-partial differential equations provide models of interacting populations in ecology, epidemiology, and biotechnology. A key challenge in feedback design for these systems is the scalar $\zeta$, defined implicitly by the Lotka-Sharpe nonlinear integral condition, as a mapping from fertility and mortality rates to $\zeta$. To solve this challenge with operator learning, we first prove that the Lotka-Sharpe operator is Lipschitz continuous, guaranteeing the existence of arbitrarily accurate neural operator approximations over a compact set of fertility and mortality functions. We then show that the resulting approximate feedback law preserves semi-global practical asymptotic stability under propagation of the operator approximation error through various other nonlinear operators, all the way through to the control input. In the numerical results, not only do we learn ``once-and-for-all'' the canonical Lotka-Sharpe (LS) operator, and thus make it available for future uses in control of other age-structured population interconnections, but we demonstrate the online usage of the neural LS operator under estimation of the fertility and mortality functions.
### Title:
          DC-Ada: Reward-Only Decentralized Observation-Interface Adaptation for Heterogeneous Multi-Robot Teams
 - **Authors:** Saad Alqithami
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Heterogeneity is a defining feature of deployed multi-robot teams: platforms often differ in sensing modalities, ranges, fields of view, and failure patterns. Controllers trained under nominal sensing can degrade sharply when deployed on robots with missing or mismatched sensors, even when the task and action interface are unchanged. We present DC-Ada, a reward-only decentralized adaptation method that keeps a pretrained shared policy frozen and instead adapts compact per-robot observation transforms to map heterogeneous sensing into a fixed inference interface. DC-Ada is gradient-free and communication-minimal: it uses budgeted accept/reject random search with short common-random-number rollouts under a strict step budget. We evaluate DC-Ada against four baselines in a deterministic 2D multi-robot simulator covering warehouse logistics, search and rescue, and collaborative mapping, across four heterogeneity regimes (H0--H3) and five seeds with a matched budget of $200{,}000$ joint environment steps per run. Results show that heterogeneity can substantially degrade a frozen shared policy and that no single mitigation dominates across all tasks and metrics. Observation normalization is strongest for reward robustness in warehouse logistics and competitive in search and rescue, while the frozen shared policy is strongest for reward in collaborative mapping. DC-Ada offers a useful complementary operating point: it improves completion most clearly in severe coverage-based mapping while requiring only scalar team returns and no policy fine-tuning or persistent communication. These results position DC-Ada as a practical deploy-time adaptation method for heterogeneous teams.
### Title:
          From Plausible to Causal: Counterfactual Semantics for Policy Evaluation in Simulated Online Communities
 - **Authors:** Agam Goyal, Yian Wang, Eshwar Chandrasekharan, Hari Sundaram
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LLM-based social simulations can generate believable community interactions, enabling ``policy wind tunnels'' where governance interventions are tested before deployment. But believability is not causality. Claims like ``intervention $A$ reduces escalation'' require causal semantics that current simulation work typically does not specify. We propose adopting the causal counterfactual framework, distinguishing \textit{necessary causation} (would the outcome have occurred without the intervention?) from \textit{sufficient causation} (does the intervention reliably produce the outcome?). This distinction maps onto different stakeholder needs: moderators diagnosing incidents require evidence about necessity, while platform designers choosing policies require evidence about sufficiency. We formalize this mapping, show how simulation design can support estimation under explicit assumptions, and argue that the resulting quantities should be interpreted as simulator-conditional causal estimates whose policy relevance depends on simulator fidelity. Establishing this framework now is essential: it helps define what adequate fidelity means and moves the field from simulations that look realistic toward simulations that can support policy changes.
### Title:
          Ledger-State Stigmergy: A Formal Framework for Indirect Coordination Grounded in Distributed Ledger State
 - **Authors:** Fernando Paredes García
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous software agents on blockchains solve distributed-coordination problems by reading shared ledger state instead of exchanging direct messages. Liquidation keepers, arbitrage bots, and other autonomous on-chain agents watch balances, contract storage, and event logs; when conditions change, they act. The ledger therefore functions as a replicated shared-state medium through which decentralized agents coordinate indirectly. This form of indirect coordination mirrors what Grassé called stigmergy in 1959: organisms coordinating through traces left in a shared environment, with no central plan. Stigmergy has mature formalizations in swarm intelligence and multi-agent systems, and on-chain agents already behave stigmergically in practice, but no prior application-layer framework cleanly bridges the two. We introduce Indirect coordination grounded in ledger state (Coordinación indirecta basada en el estado del registro contable) as a ledger-specific applied definition that maps Grassé's mechanism onto distributed ledger technology. We operationalize this with a state-transition formalism, identify three recurring base on-chain coordination patterns (State-Flag, Event-Signal, Threshold- Trigger) together with a Commit-Reveal sequencing overlay, and work through a State-Flag task-board example to compare ledger-state coordination analytically with off-chain messaging and centralized orchestration. The contribution is a reusable vocabulary, a ledger-specific formal mapping, and design guidance for decentralized coordination over replicated shared state at the application layer.
### Title:
          A Reciprocity-Law-Compliant Photoacoustic Forward-Adjoint Operator
 - **Authors:** Ashkan Javaherian
 - **Subjects:** Subjects:
Numerical Analysis (math.NA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We extend the forward-adjoint operator framework derived in our previous study to photoacoustic tomography (PAT). In that earlier work, the acoustic forward operator included a reception operator that maps, at each time step, the pressure wavefield in free space onto the boundary (receiver surface). It was shown that this reception operator serves as a left-inverse of an emission operator that maps the pressure restricted to the boundary (emitter surface) onto free space, perfectly complying with the reciprocity law of physics. In this study, we define the full PAT forward operator as a composite mapping composed of an acoustic forward operator equipped with a scaled variant of the previously proposed reception operator, and an operator describing the photoacoustic source. Singularities arising both in the reception step (due to the boundary restriction) and in the photoacoustic source (due to its instantaneous nature) are regularized using regularized Dirac delta distributions. The resulting PAT forward-adjoint operator pair satisfies an inner-product relation, which we verify through numerical experiments on a discretized domain. The effectiveness of the proposed operator pair is further demonstrated using an iterative minimization framework that yields both qualitatively and quantitatively accurate reconstructions of an initial pressure distribution from the corresponding Dirichlet-type boundary data.
### Title:
          Triggering and Detecting Exploitable Library Vulnerability from the Client by Directed Greybox Fuzzing
 - **Authors:** Yukai Zhao, Menghan Wu, Xing Hu, Shaohua Wang, Meng Luo, Xin Xia
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Developers utilize third-party libraries to improve productivity, which also introduces potential security risks. Existing approaches generate tests for public functions to trigger library vulnerabilities from client programs, yet they depend on proof-of-concepts (PoCs), which are often unavailable. In this paper, we propose a new approach, LiveFuzz, based on directed greybox fuzzing (DGF) to detect the exploitability of library vulnerabilities from client programs without PoCs. LiveFuzz exploits a target tuple to extend existing DGF techniques to cross-program scenarios. Based on the target tuple, LiveFuzz introduces a novel Abstract Path Mapping mechanism to project execution paths, mitigating the preference for shorter paths. LiveFuzz also proposes a risk-based adaptive mutation to mitigate excessive mutation. To evaluate LiveFuzz, we construct a new dataset including 61 cases of library vulnerabilities exploited from client programs. Results show that LiveFuzz increases the number of target-reachable paths compared with all baselines and improves the average speed of vulnerability exposure. Three vulnerabilities are triggered exclusively by LiveFuzz.
### Title:
          Physical Sensitivity Kernels Can Emerge in Data-Driven Forward Models: Evidence From Surface-Wave Dispersion
 - **Authors:** Ziye Yu, Yuqi Cai, Xin Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Geophysics (physics.geo-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data-driven neural networks are increasingly used as surrogate forward models in geophysics, but it remains unclear whether they recover only the data mapping or also the underlying physical sensitivity structure. Here we test this question using surface-wave dispersion. By comparing automatically differentiated gradients from a neural-network surrogate with theoretical sensitivity kernels, we show that the learned gradients can recover the main depth-dependent structure of physical kernels across a broad range of periods. This indicates that neural surrogate models can learn physically meaningful differential information, rather than acting as purely black-box predictors. At the same time, strong structural priors in the training distribution can introduce systematic artifacts into the inferred sensitivities. Our results show that neural forward surrogates can recover useful physical information for inversion and uncertainty analysis, while clarifying the conditions under which this differential structure remains physically consistent.
### Title:
          Ideally-Smooth Transition between Grid-Forming and Grid-Following Inverters based on State Mapping Method
 - **Authors:** Zhenshuai Liu, Yitong Li, Zirui Wang, Jiashuo Gu, Yao Qin, Jinjun Liu
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 There has been widespread global increasing use of renewable energy sources, which are usually connected to the electricity grids via power electronic inverters. Traditionally, these inverter-based resources operate in either grid-forming (GFM) or grid-following (GFL) mode. But more recently, the need of switching between these two modes are glowingly required because of the complex operation scenarios of systems such as source-side limitations, grid-side services, fault disturbances, etc. However, due to the differences between GFM and GFL modes, a direct switching between them would lead to large oscillations or even instability of inverters. Therefore, in this paper, a method called state mapping method for analyzing the switching transient and designing the switching control is proposed. Based on this method, an ideally-smooth transition between GFM and GFL can be achieved. The effectiveness of the proposed method is verified by both the theoretical analysis and experiment tests.
### Title:
          C2|Q>: A Robust Framework for Bridging Classical and Quantum Software Development -- RCR Report
 - **Authors:** Boshuai Ye, Arif Ali Khan, Teemu Pihkakoski, Peng Liang, Muhammad Azeem Akbar, Matti Silveri, Lauri Malmi
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This is the Replicated Computational Results (RCR) Report for the paper C2|Q>: A Robust Framework for Bridging Classical and Quantum Software Development. The paper introduces a modular, hardware-agnostic framework that translates classical problem specifications - Python code or structured JSON - into executable quantum programs across ten problem families and multiple hardware backends. We release the framework source code on GitHub at this https URL, a pretrained parser model on Zenodo at this https URL, evaluation data in a separate Zenodo record at this https URL, and a PyPI package at this https URL for lightweight CLI and API use. Experiment 1 is supported through a released pretrained model and training notebook, while Experiments 2 and 3 are directly executable via documented make targets. This report describes the artifact structure, setup instructions, and the mapping from each execution route to the corresponding experiment.
### Title:
          LACE-S: Toward Sensitivity-consistent Locational Average Carbon Emissions via Neural Representation
 - **Authors:** Young-ho Cho, Min-Seung Ko, Hao Zhu
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Carbon-aware grid optimization relies on accurate locational emission metrics to effectively guide demand-side decarbonization tasks such as spatial load shifting. However, existing metrics are only valid around limited operating regions and unfortunately cannot generalize the emission patterns beyond these regions. When these metrics are used to signal carbon-sensitive resources, they could paradoxically increase system-wide emissions. This work seeks to develop a sensitivity-consistent metric for locational average carbon emissions (LACE-S) using a neural representation approach. To ensure physical validity, the neural model enforces total emission balance through an explicit projection layer while matching marginal emission sensitivities across the entire loading region. Jacobian-based regularization is further introduced to capture the underlying partition of load buses with closely aligned generator responses. Moreover, we present a scalable zonal aggregation strategy, ZACE-S, to reduce the model complexity by mapping nodal inputs to predefined market zones. Numerical tests on the IEEE 30-bus system have verified the performance improvements of LACE-S in matching total emissions and their sensitivities over the non-regularized design. Crucially, while spatial load shifting driven by existing metrics often increases the post-shift emissions, the proposed LACE-S metric has led to a reliable reduction of system-wide emissions, demonstrating its excellent consistency with the global emission patterns.
### Title:
          MAVEN: A Mesh-Aware Volumetric Encoding Network for Simulating 3D Flexible Deformation
 - **Authors:** Zhe Feng, Shilong Tao, Haonan Sun, Shaohan Chen, Zhanxing Zhu, Yunhuai Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning-based approaches, particularly graph neural networks (GNNs), have gained prominence in simulating flexible deformations and contacts of solids, due to their ability to handle unstructured physical fields and nonlinear regression on graph structures. However, existing GNNs commonly represent meshes with graphs built solely from vertices and edges. These approaches tend to overlook higher-dimensional spatial features, e.g., 2D facets and 3D cells, from the original geometry. As a result, it is challenging to accurately capture boundary representations and volumetric characteristics, though this information is critically important for modeling contact interactions and internal physical quantity propagation, particularly under sparse mesh discretization. In this paper, we introduce MAVEN, a mesh-aware volumetric encoding network for simulating 3D flexible deformation, which explicitly models geometric mesh elements of higher dimension to achieve a more accurate and natural physical simulation. MAVEN establishes learnable mappings among 3D cells, 2D facets, and vertices, enabling flexible mutual transformations. Explicit geometric features are incorporated into the model to alleviate the burden of implicitly learning geometric patterns. Experimental results show that MAVEN consistently achieves state-of-the-art performance across established datasets and a novel metal stretch-bending task featuring large deformations and prolonged contacts.
### Title:
          Relational Epipolar Graphs for Robust Relative Camera Pose Estimation
 - **Authors:** Prateeth Rao, Sachit Rao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A key component of Visual Simultaneous Localization and Mapping (VSLAM) is estimating relative camera poses using matched keypoints. Accurate estimation is challenged by noisy correspondences. Classical methods rely on stochastic hypothesis sampling and iterative estimation, while learning-based methods often lack explicit geometric structure. In this work, we reformulate relative pose estimation as a relational inference problem over epipolar correspondence graphs, where matched keypoints are nodes and nearby ones are connected by edges. Graph operations such as pruning, message passing, and pooling estimate a quaternion rotation, translation vector, and the Essential Matrix (EM). Minimizing a loss comprising (i) $\mathcal{L}_2$ differences with ground truth (GT), (ii) Frobenius norm between estimated and GT EMs, (iii) singular value differences, (iv) heading angle differences, and (v) scale differences, yields the relative pose between image pairs. The dense detector-free method LoFTR is used for matching. Experiments on indoor and outdoor benchmarks show improved robustness to dense noise and large baseline variation compared to classical and learning-guided approaches, highlighting the effectiveness of global relational consensus.
### Title:
          AI Agents Under EU Law
 - **Authors:** Luca Nannini, Adam Leon Smith, Michele Joshua Maggini, Enrico Panai, Sandra Feliciano, Aleksandr Tiulkanov, Elena Maran, James Gealy, Piercosma Bisconti
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI); Cryptography and Security (cs.CR); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI agents - i.e. AI systems that autonomously plan, invoke external tools, and execute multi-step action chains with reduced human involvement - are being deployed at scale across enterprise functions ranging from customer service and recruitment to clinical decision support and critical infrastructure management. The EU AI Act (Regulation 2024/1689) regulates these systems through a risk-based framework, but it does not operate in isolation: providers face simultaneous obligations under the GDPR, the Cyber Resilience Act, the Digital Services Act, the Data Act, the Data Governance Act, sector-specific legislation, the NIS2 Directive, and the revised Product Liability Directive. This paper provides the first systematic regulatory mapping for AI agent providers integrating (a) draft harmonised standards under Standardisation Request M/613 to CEN/CENELEC JTC 21 as of January 2026, (b) the GPAI Code of Practice published in July 2025, (c) the CRA harmonised standards programme under Mandate M/606 accepted in April 2025, and (d) the Digital Omnibus proposals of November 2025. We present a practical taxonomy of nine agent deployment categories mapping concrete actions to regulatory triggers, identify agent-specific compliance challenges in cybersecurity, human oversight, transparency across multi-party action chains, and runtime behavioral drift. We propose a twelve-step compliance architecture and a regulatory trigger mapping connecting agent actions to applicable legislation. We conclude that high-risk agentic systems with untraceable behavioral drift cannot currently satisfy the AI Act's essential requirements, and that the provider's foundational compliance task is an exhaustive inventory of the agent's external actions, data flows, connected systems, and affected persons.
### Title:
          nascTime: A Full-Stack 5G-TSN Bridge Simulation Framework with SDAP-Based QoS Mapping and IEEE 802.1AS Transparent Clock
 - **Authors:** Mohamed Seliem, Utz Roedig, Cormac Sreenan, Dirk Pesch
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The integration of 5G with IEEE 802.1 Time-Sensitive Networking (TSN) is essential for enabling flexible and mobile deterministic communication in industrial automation. The 3GPP Release 16 specification defines a bridge architecture where the 5G system operates as a transparent TSN bridge, incorporating Network-side and Device-side TSN Translators (NW-TT, DS-TT), a TSN Application Function, and QoS mapping between TSN Priority Code Points and 5G QoS Flow Identifiers. However, existing simulation frameworks model only subsets of this architecture, either QoS mapping without time synchronization, or time synchronization without data plane traffic, and none implements the complete QoS pipeline through the 3GPP SDAP layer with per-flow Data Radio Bearer selection. We present nascTime[20], an open simulation framework built on OMNeT 6.3, INET 4.6, and Simu5G that implements the complete 3GPP Release 16 5G-TSN bridge model. The framework provides end-to-end QoS mapping from TSN PCP through to 5G QFI via the SDAP/DRB pipeline, IEEE 802.1AS transparent clock behavior with measured residence time correction through L2-in-GTP-U gPTP transport, and multi-endpoint scaling with bidirectional traffic. The bridge ports integrate with INET's LayeredEthernetInterface and streaming PHY for compatibility with TSN features including Time-Aware Shaping and frame preemption. We validate nascTime with a three-endpoint factory scenario demonstrating near-perfect packet delivery across two traffic classes, correct gPTP synchronization with residence time correction, and zero packet loss. nascTime is the first simulation framework to model the full 5G-TSN bridge data path with SDAP-based QoS differentiation and measured IEEE 802.1AS transparent clock behavior in a multi-endpoint topology.
### Title:
          WaterSplat-SLAM: Photorealistic Monocular SLAM in Underwater Environment
 - **Authors:** Kangxu Wang, Shaofeng Zou, Chenxing Jiang, Yixiang Dai, Siang Chen, Shaojie Shen, Guijin Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Underwater monocular SLAM is a challenging problem with applications from autonomous underwater vehicles to marine archaeology. However, existing underwater SLAM methods struggle to produce maps with high-fidelity rendering. In this paper, we propose WaterSplat-SLAM, a novel monocular underwater SLAM system that achieves robust pose estimation and photorealistic dense mapping. Specifically, we couple semantic medium filtering into two-view 3D reconstruction prior to enable underwater-adapted camera tracking and depth estimation. Furthermore, we present a semantic-guided rendering and adaptive map management strategy with an online medium-aware Gaussian map, modeling underwater environment in a photorealistic and compact manner. Experiments on multiple underwater datasets demonstrate that WaterSplat-SLAM achieves robust camera tracking and high-fidelity rendering in underwater environments.
### Title:
          ROSClaw: A Hierarchical Semantic-Physical Framework for Heterogeneous Multi-Agent Collaboration
 - **Authors:** Rongfeng Zhao, Xuanhao Zhang, Zhaochen Guo, Xiang Shao, Zhongpan Zhu, Bin He, Jie Chen
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The integration of large language models (LLMs) with embodied agents has improved high-level reasoning capabilities; however, a critical gap remains between semantic understanding and physical execution. While vision-language-action (VLA) and vision-language-navigation (VLN) systems enable robots to perform manipulation and navigation tasks from natural language instructions, they still struggle with long-horizon sequential and temporally structured tasks. Existing frameworks typically adopt modular pipelines for data collection, skill training, and policy deployment, resulting in high costs in experimental validation and policy optimization. To address these limitations, we propose ROSClaw, an agent framework for heterogeneous robots that integrates policy learning and task execution within a unified vision-language model (VLM) controller. The framework leverages e-URDF representations of heterogeneous robots as physical constraints to construct a sim-to-real topological mapping, enabling real-time access to the physical states of both simulated and real-world agents. We further incorporate a data collection and state accumulation mechanism that stores robot states, multimodal observations, and execution trajectories during real-world execution, enabling subsequent iterative policy optimization. During deployment, a unified agent maintains semantic continuity between reasoning and execution, and dynamically assigns task-specific control to different agents, thereby improving robustness in multi-policy execution. By establishing an autonomous closed-loop framework, ROSClaw minimizes the reliance on robot-specific development workflows. The framework supports hardware-level validation, automated generation of SDK-level control programs, and tool-based execution, enabling rapid cross-platform transfer and continual improvement of robotic skills. Ours project page: this https URL.
### Title:
          ZeD-MAP: Bundle Adjustment Guided Zero-Shot Depth Maps for Real-Time Aerial Imaging
 - **Authors:** Selim Ahmet Iz, Francesco Nex, Norman Kerle, Henry Meissner, Ralf Berger
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time depth reconstruction from ultra-high-resolution UAV imagery is essential for time-critical geospatial tasks such as disaster response, yet remains challenging due to wide-baseline parallax, large image sizes, low-texture or specular surfaces, occlusions, and strict computational constraints. Recent zero-shot diffusion models offer fast per-image dense predictions without task-specific retraining, and require fewer labelled datasets than transformer-based predictors while avoiding the rigid capture geometry requirement of classical multi-view stereo. However, their probabilistic inference prevents reliable metric accuracy and temporal consistency across sequential frames and overlapping tiles. We present ZeD-MAP, a cluster-level framework that converts a test-time diffusion depth model into a metrically consistent, SLAM-like mapping pipeline by integrating incremental cluster-based bundle adjustment (BA). Streamed UAV frames are grouped into overlapping clusters; periodic BA produces metrically consistent poses and sparse 3D tie-points, which are reprojected into selected frames and used as metric guidance for diffusion-based depth estimation. Validation on ground-marker flights captured at approximately 50 m altitude (GSD is approximately 0.85 cm/px, corresponding to 2,650 square meters ground coverage per frame) with the DLR Modular Aerial Camera System (MACS) shows that our method achieves sub-meter accuracy, with approximately 0.87 m error in the horizontal (XY) plane and 0.12 m in the vertical (Z) direction, while maintaining per-image runtimes between 1.47 and 4.91 seconds. Results are subject to minor noise from manual point-cloud annotation. These findings show that BA-based metric guidance provides consistency comparable to classical photogrammetric methods while significantly accelerating processing, enabling real-time 3D map generation.
### Title:
          Hardware-Level Governance of AI Compute: A Feasibility Taxonomy for Regulatory Compliance and Treaty Verification
 - **Authors:** Samar Ansari
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Computers and Society (cs.CY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The governance of frontier AI increasingly relies on controlling access to computational resources, yet the hardware-level mechanisms invoked by policy proposals remain largely unexamined from an engineering perspective. This paper bridges the gap between AI governance and computer engineering by proposing a taxonomy of 20 hardware-level governance mechanisms, organised by function (monitoring, verification, enforcement) and assessed for technical feasibility on a four-point scale from currently deployable to speculative. For each mechanism, we provide a technical description, a feasibility rating, and an identification of adversarial vulnerabilities. We map the taxonomy onto four governance scenarios: domestic regulation, bilateral agreements, multilateral treaty verification, and industry self-regulation. Our analysis reveals a structural mismatch: the mechanisms most needed for treaty verification, including on-chip compute metering, cryptographic proof-of-training, and hardware-embedded enforcement, are also the least mature. We assess principal threats to compute-based governance, including algorithmic efficiency gains, distributed training methods, and sovereignty concerns. We identify a temporal constraint: the window during which semiconductor manufacturing concentration makes hardware-level governance implementable is narrowing, while R&D timelines for critical mechanisms span years. We present an adversary-tiered threat analysis distinguishing commercial, non-state, and nation-state actors, arguing the appropriate security standard is tamper-evident assurance analogous to IAEA verification rather than absolute tamper-proofing. The taxonomy, feasibility classification, and mechanism-to-scenario mapping provide a technical foundation for policymakers and identify the R&D investments required before hardware-level governance can support verifiable international agreements.
### Title:
          A Validated Taxonomy on Software Energy Smells
 - **Authors:** Mohammadjavad Mehditabar, Saurabhsingh Rajput, Tushar Sharma
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As software proliferates across domains, its aggregate energy footprint has become a major concern. To reduce software's growing environmental footprint, developers need to identify and refactor energy smells: source code implementations, design choices, or programming practices that lead to inefficient use of computing resources. Existing catalogs of such smells are either domain-specific, limited to performance anti-patterns, lack fine-grained root cause classification, or remain unvalidated against measured energy data. In this paper, we present a comprehensive, language-agnostic, taxonomy of software energy smells. Through a systematic literature review of 60 papers and exhaustive snowballing, we coded 320 inefficiency patterns into 12 primary energy smells and 65 root causes mapped to the primary smells. To empirically validate this taxonomy, we profile over 21,000 functionally equivalent Python code pairs for energy, time, and memory, and classified the top 3000 pairs by energy difference using a multi-step LLM pipeline, mapping 55 of the 65 root causes to real code. The analysis reveals that 71% of samples exhibit multiple co-occurring smells, memory-related smells yield the highest per-fix energy savings, while power draw variation across patterns confirms that energy optimization cannot be reduced to performance optimization alone. Along with the taxonomy, we release the labeled dataset, including energy profiles and reasoning traces, to the community. Together, they provide a shared vocabulary, actionable refactoring guidelines, and an empirical foundation for energy smell detection, energy-efficient code generation, and green software engineering at large.
## Keyword: localization
### Title:
          ViBA: Implicit Bundle Adjustment with Geometric and Temporal Consistency for Robust Visual Matching
 - **Authors:** Xiaoji Niu, Yuqing Wang, Yan Wang, Hailiang Tang, Tisheng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Most existing image keypoint detection and description methods rely on datasets with accurate pose and depth annotations, limiting scalability and generalization, and often degrading navigation and localization performance. We propose ViBA, a sustainable learning framework that integrates geometric optimization with feature learning for continuous online training on unconstrained video streams. Embedded in a standard visual odometry pipeline, it consists of an implicitly differentiable geometric residual framework: (i) an initial tracking network for inter-frame correspondences, (ii) depth-based outlier filtering, and (iii) differentiable global bundle adjustment that jointly refines camera poses and feature positions by minimizing reprojection errors. By combining geometric consistency from BA with long-term temporal consistency across frames, ViBA enforces stable and accurate feature representations. We evaluate ViBA on EuRoC and UMA datasets. Compared with state-of-the-art methods such as SuperPoint+SuperGlue, ALIKED, and LightGlue, ViBA reduces mean absolute translation error (ATE) by 12-18% and absolute rotation error (ARE) by 5-10% across sequences, while maintaining real-time inference speeds (FPS 36-91). When evaluated on unseen sequences, it retains over 90% localization accuracy, demonstrating robust generalization. These results show that ViBA supports continuous online learning with geometric and temporal consistency, consistently improving navigation and localization in real-world scenarios.
### Title:
          CT-VoxelMap: Efficient Continuous-Time LiDAR-Inertial Odometry with Probabilistic Adaptive Voxel Mapping
 - **Authors:** Lei Zhao, Xingyi Li, Tianchen Deng, Chuan Cao, Han Zhang, Weidong Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Maintaining stable and accurate localization during fast motion or on rough terrain remains highly challenging for mobile robots with onboard resources. Currently, multi-sensor fusion methods based on continuous-time representation offer a potential and effective solution to this challenge. Among these, spline-based methods provide an efficient and intuitive approach for continuous-time representation. Previous continuous-time odometry works based on B-splines either treat control points as variables to be estimated or perform estimation in quaternion space, which introduces complexity in deriving analytical Jacobians and often overlooks the fitting error between the spline and the true trajectory over time. To address these issues, we first propose representing the increments of control points on matrix Lie groups as variables to be estimated. Leveraging the feature of the cumulative form of B-splines, we derive a more compact formulation that yields simpler analytical Jacobians without requiring additional boundary condition considerations. Second, we utilize forward propagation information from IMU measurements to estimate fitting errors online and further introduce a hybrid feature-based voxel map management strategy, enhancing system accuracy and robustness. Finally, we propose a re-estimation policy that significantly improves system computational efficiency and robustness. The proposed method is evaluated on multiple challenging public datasets, demonstrating superior performance on most sequences. Detailed ablation studies are conducted to analyze the impact of each module on the overall pose estimation system.
### Title:
          When Does Multimodal AI Help? Diagnostic Complementarity of Vision-Language Models and CNNs for Spectrum Management in Satellite-Terrestrial Networks
 - **Authors:** Yuanhang Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The adoption of vision-language models (VLMs) for wireless network management is accelerating, yet no systematic understanding exists of where these large foundation models outperform lightweight convolutional neural networks (CNNs) for spectrum-related tasks. This paper presents the first diagnostic comparison of VLMs and CNNs for spectrum heatmap understanding in non-terrestrial network and terrestrial network (NTN-TN) cooperative systems. We introduce SpectrumQA, a benchmark comprising 108K visual question-answer pairs across four granularity levels: scene classification (L1), regional reasoning (L2), spatial localization (L3), and semantic reasoning (L4). Our experiments on three NTN-TN scenarios with a frozen Qwen2-VL-7B and a trained ResNet-18 reveal a clear taskdependent complementarity: CNN achieves 72.9% accuracy at severity classification (L1) and 0.552 IoU at spatial localization (L3), while VLM uniquely enables semantic reasoning (L4) with F1=0.576 using only three in-context examples-a capability fundamentally absent in CNN architectures. Chain-of-thought (CoT) prompting further improves VLM reasoning by 12.6% (F1: 0.209->0.233) while having zero effect on spatial tasks, confirming that the complementarity is rooted in architectural differences rather than prompting limitations. A deterministic task-type router that delegates supervised tasks to CNN and reasoning tasks to VLM achieves a composite score of 0.616, a 39.1% improvement over CNN alone. We further show that VLM representations exhibit stronger cross-scenario robustness, with smaller performance degradation in 5 out of 6 transfer directions. These findings provide actionable guidelines: deploy CNNs for spatial localization and VLMs for semantic spectrum reasoning, rather than treating them as substitutes.
### Title:
          ActivityForensics: A Comprehensive Benchmark for Localizing Manipulated Activity in Videos
 - **Authors:** Peijun Bao, Anwei Luo, Gang Pan, Alex C. Kot, Xudong Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Temporal forgery localization aims to temporally identify manipulated segments in videos. Most existing benchmarks focus on appearance-level forgeries, such as face swapping and object removal. However, recent advances in video generation have driven the emergence of activity-level forgeries that modify human actions to distort event semantics, resulting in highly deceptive forgeries that critically undermine media authenticity and public trust. To overcome this issue, we introduce ActivityForensics, the first large-scale benchmark for localizing manipulated activity in videos. It contains over 6K forged video segments that are seamlessly blended into the video context, rendering high visual consistency that makes them almost indistinguishable from authentic content to the human eye. We further propose Temporal Artifact Diffuser (TADiff), a simple yet effective baseline that exposes artifact cues through a diffusion-based feature regularizer. Based on ActivityForensics, we introduce comprehensive evaluation protocols covering intra-domain, cross-domain, and open-world settings, and benchmark a wide range of state-of-the-art forgery localizers to facilitate future research. The dataset and code are available at this https URL.
### Title:
          Beyond Task-Driven Features for Object Detection
 - **Authors:** Meilun Zhou, Alina Zare
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Task-driven features learned by modern object detectors optimize end task loss yet often capture shortcut correlations that fail to reflect underlying annotation structure. Such representations limit transfer, interpretability, and robustness when task definitions change or supervision becomes sparse. This paper introduces an annotation-guided feature augmentation framework that injects embeddings into an object detection backbone. The method constructs dense spatial feature grids from annotation-guided latent spaces and fuses them with feature pyramid representations to influence region proposal and detection heads. Experiments across wildlife and remote sensing datasets evaluate classification, localization, and data efficiency under multiple supervision regimes. Results show consistent improvements in object focus, reduced background sensitivity, and stronger generalization to unseen or weakly supervised tasks. The findings demonstrate that aligning features with annotation geometry yields more meaningful representations than purely task optimized features.
### Title:
          SARES-DEIM: Sparse Mixture-of-Experts Meets DETR for Robust SAR Ship Detection
 - **Authors:** Fenghao Song, Shaojing Yang, Xi Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ship detection in Synthetic Aperture Radar (SAR) imagery is fundamentally challenged by inherent coherent speckle noise, complex coastal clutter, and the prevalence of small-scale targets. Conventional detectors, primarily designed for optical imagery, often exhibit limited robustness against SAR-specific degradation and suffer from the loss of fine-grained ship signatures during spatial downsampling. To address these limitations, we propose SARES-DEIM, a domain-aware detection framework grounded in the DEtection TRansformer (DETR) paradigm. Central to our approach is SARESMoE (SAR-aware Expert Selection Mixture-of-Experts), a module leveraging a sparse gating mechanism to selectively route features toward specialized frequency and wavelet experts. This sparsely-activated architecture effectively filters speckle noise and semantic clutter while maintaining high computational efficiency. Furthermore, we introduce the Space-to-Depth Enhancement Pyramid (SDEP) neck to preserve high-resolution spatial cues from shallow stages, significantly improving the localization of small targets. Extensive experiments on two benchmark datasets demonstrate the superiority of SARES-DEIM. Notably, on the challenging HRSID dataset, our model achieves a mAP50:95 of 76.4% and a mAP50 of 93.8%, outperforming state-of-the-art YOLO-series and specialized SAR detectors.
### Title:
          Subspace Control: Turning Constrained Model Steering into Controllable Spectral Optimization
 - **Authors:** Yancheng Huang, Changsheng Wang, Chongyu Fan, Yicheng Lang, Bingqi Shang, Yang Zhang, Mingyi Hong, Qing Qu, Alvaro Velasquez, Sijia Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Foundation models, such as large language models (LLMs), are powerful but often require customization before deployment to satisfy practical constraints such as safety, privacy, and task-specific requirements, leading to "constrained" optimization problems for model steering and adaptation. However, solving such problems remains largely underexplored and is particularly challenging due to interference between the primary objective and constraint objectives during optimization. In this paper, we propose a subspace control framework for constrained model training. Specifically, (i) we first analyze, from a model merging perspective, how spectral cross-task interference arises and show that it can be resolved via a one-shot solution that orthogonalizes the merged subspace; (ii) we establish a connection between this solution and gradient orthogonalization in the spectral optimizer Muon; and (iii) building on these insights, we introduce SIFT (spectral interference-free training), which leverages a localization scheme to selectively intervene during optimization, enabling controllable updates that mitigate objective-constraint conflicts. We evaluate SIFT across four representative applications: (a) machine unlearning, (b) safety alignment, (c) text-to-speech adaptation, and (d) hallucination mitigation. Compared to both control-based and control-free baselines, SIFT consistently achieves substantial and robust performance improvements across all tasks. Code is available at this https URL.
### Title:
          Spatially-Weighted CLIP for Street-View Geo-localization
 - **Authors:** Ting Han, Fengjiao Li, Chunsong Chen, Haoling Huang, Yiping Chen, Meiliu Wu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper proposes Spatially-Weighted CLIP (SW-CLIP), a novel framework for street-view geo-localization that explicitly incorporates spatial autocorrelation into vision-language contrastive learning. Unlike conventional CLIP-based methods that treat all non-matching samples as equally negative, SW-CLIP leverages Tobler's First Law of Geography to model geographic relationships through distance-aware soft supervision. Specifically, we introduce a location-as-text representation to encode geographic positions and replace one-hot InfoNCE targets with spatially weighted soft labels derived from geodesic distance. Additionally, a neighborhood-consistency regularization is employed to preserve local spatial structure in the embedding space. Experiments on a multi-city dataset demonstrate that SW-CLIP significantly improves geo-localization accuracy, reduces long-tail errors, and enhances spatial coherence compared to standard CLIP. The results highlight the importance of shifting from semantic alignment to geographic alignment for robust geo-localization and provide a general paradigm for integrating spatial principles into multimodal representation learning.
### Title:
          MPTF-Net: Multi-view Pyramid Transformer Fusion Network for LiDAR-based Place Recognition
 - **Authors:** Shuyuan Li, Zihang Wang, Xieyuanli Chen, Wenkai Zhu, Xiaoteng Fang, Peizhou Ni, Junhao Yang, Dong Kong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based place recognition (LPR) is essential for global localization and loop-closure detection in large-scale SLAM systems. Existing methods typically construct global descriptors from Range Images or BEV representations for matching. BEV is widely adopted due to its explicit 2D spatial layout encoding and efficient retrieval. However, conventional BEV representations rely on simple statistical aggregation, which fails to capture fine-grained geometric structures, leading to performance degradation in complex or repetitive environments. To address this, we propose MPTF-Net, a novel multi-view multi-scale pyramid Transformer fusion network. Our core contribution is a multi-channel NDT-based BEV encoding that explicitly models local geometric complexity and intensity distributions via Normal Distribution Transform, providing a noise-resilient structural prior. To effectively integrate these features, we develop a customized pyramid Transformer module that captures cross-view interactive correlations between Range Image Views (RIV) and NDT-BEV at multiple spatial scales. Extensive experiments on the nuScenes, KITTI and NCLT datasets demonstrate that MPTF-Net achieves state-of-the-art performance, specifically attaining a Recall@1 of 96.31\% on the nuScenes Boston split while maintaining an inference latency of only 10.02 ms, making it highly suitable for real-time autonomous unmanned systems.
### Title:
          G-EDF-Loc: 3D Continuous Gaussian Distance Field for Robust Gradient-Based 6DoF Localization
 - **Authors:** José E. Maese, Lucía Coto-Elena, Luis Merino, Fernando Caballero
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper presents a robust 6-DoF localization framework based on a direct, CPU-based scan-to-map registration pipeline. The system leverages G-EDF, a novel continuous and memory-efficient 3D distance field representation. The approach models the Euclidean Distance Field (EDF) using a Block-Sparse Gaussian Mixture Model with adaptive spatial partitioning, ensuring $C^1$ continuity across block transitions and mitigating boundary artifacts. By leveraging the analytical gradients of this continuous map, which maintain Eikonal consistency, the proposed method achieves high-fidelity spatial reconstruction and real-time localization. Experimental results on large-scale datasets demonstrate that G-EDF-Loc performs competitively against state-of-the-art methods, exhibiting exceptional resilience even under severe odometry degradation or in the complete absence of IMU priors.
### Title:
          Multilingual Prompt Localization for Agent-as-a-Judge: Language and Backbone Sensitivity in Requirement-Level Evaluation
 - **Authors:** Alhasan Mahmood, Samir Abdaljalil, Hasan Kurban
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Evaluation language is typically treated as a fixed English default in agentic code benchmarks, yet we show that changing the judge's language can invert backbone rankings. We localize the Agent-as-a-Judge prompt stack to five typologically diverse languages (English, Arabic, Turkish, Chinese, Hindi) and evaluate 55 DevAI development tasks across three developer-agent frameworks and six judge backbones, totaling 4950 judge runs. The central finding is that backbone and language interact: GPT-4o achieves the highest satisfaction in English (44.72\%), while Gemini leads in Arabic (51.72\%, $p<0.001$ vs.\ GPT-4o) and Hindi (53.22\%). No single backbone dominates across all languages, and inter-backbone agreement on individual requirement judgments is modest (Fleiss' $\kappa \leq 0.231$). A controlled ablation further shows that localizing judge-side instructions, not just benchmark content, can be decisive: Hindi satisfaction drops from 42.8\% to 23.2\% under partial localization. These results indicate that language should be treated as an explicit evaluation variable in agentic benchmarks. Full requirement-level judgments and runtime statistics are released for reproducibility.
### Title:
          Relational Epipolar Graphs for Robust Relative Camera Pose Estimation
 - **Authors:** Prateeth Rao, Sachit Rao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A key component of Visual Simultaneous Localization and Mapping (VSLAM) is estimating relative camera poses using matched keypoints. Accurate estimation is challenged by noisy correspondences. Classical methods rely on stochastic hypothesis sampling and iterative estimation, while learning-based methods often lack explicit geometric structure. In this work, we reformulate relative pose estimation as a relational inference problem over epipolar correspondence graphs, where matched keypoints are nodes and nearby ones are connected by edges. Graph operations such as pruning, message passing, and pooling estimate a quaternion rotation, translation vector, and the Essential Matrix (EM). Minimizing a loss comprising (i) $\mathcal{L}_2$ differences with ground truth (GT), (ii) Frobenius norm between estimated and GT EMs, (iii) singular value differences, (iv) heading angle differences, and (v) scale differences, yields the relative pose between image pairs. The dense detector-free method LoFTR is used for matching. Experiments on indoor and outdoor benchmarks show improved robustness to dense noise and large baseline variation compared to classical and learning-guided approaches, highlighting the effectiveness of global relational consensus.
## Keyword: transformer
### Title:
          Knowledge Packs: Zero-Token Knowledge Delivery via KV Cache Injection
 - **Authors:** Andrey Pustovit
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 RAG wastes tokens. We propose Knowledge Packs: pre-computed KV caches that deliver the same knowledge at zero token cost. For causal transformers, the KV cache from a forward pass on text F is identical to what a joint pass on F+q would produce - this follows directly from the causal mask. The equivalence is exact but fragile: wrong chat template formatting causes 6-7pp degradation, which we believe explains prior claims of KV outperforming RAG. With correct formatting: zero divergences across 700 questions on Qwen3-8B and Llama-3.1-8B, up to 95% token savings. The KV interface also enables behavioral steering that RAG cannot do. Because RoPE rotates keys but leaves values untouched, contrastive deltas on cached values can nudge model behavior while key arithmetic destroys coherence. The effect sits in mid-layer values (33-66%), independent directions are nearly orthogonal (cos~0) and compose, and both channels - knowledge and steering - run simultaneously at alpha<=0.7 without interference. No training, no weight modification.
### Title:
          Safe Decentralized Operation of EV Virtual Power Plant with Limited Network Visibility via Multi-Agent Reinforcement Learning
 - **Authors:** Chenghao Huang, Jiarong Fan, Weiqing Wang, Hao Wang
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Artificial Intelligence (cs.AI); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As power systems advance toward net-zero targets, behind-the-meter renewables are driving rapid growth in distributed energy resources (DERs). Virtual power plants (VPPs) increasingly coordinate these resources to support power distribution network (PDN) operation, with EV charging stations (EVCSs) emerging as a key asset due to their strong impact on local voltages. However, in practice, VPPs must make operational decisions with only partial visibility of PDN states, relying on limited, aggregated information shared by the distribution system operator. This work proposes a safety-enhanced VPP framework for coordinating multiple EVCSs under such realistic information constraints to ensure voltage security while maintaining economic operation. We develop Transformer-assisted Lagrangian Multi-Agent Proximal Policy Optimization (TL-MAPPO), in which EVCS agents learn decentralized charging policies via centralized training with Lagrangian regularization to enforce voltage and demand-satisfaction constraints. A transformer-based embedding layer deployed on each EVCS agent captures temporal correlations among prices, loads, and charging demand to improve decision quality. Experiments on a realistic 33-bus PDN show that the proposed framework reduces voltage violations by approximately 45% and operational costs by approximately 10% compared to representative multi-agent DRL baselines, highlighting its potential for practical VPP deployment.
### Title:
          XAttnRes: Cross-Stage Attention Residuals for Medical Image Segmentation
 - **Authors:** Xinyu Liu, Qing Xu, Zhen Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In the field of Large Language Models (LLMs), Attention Residuals have recently demonstrated that learned, selective aggregation over all preceding layer outputs can outperform fixed residual connections. We propose Cross-Stage Attention Residuals (XAttnRes), a mechanism that maintains a global feature history pool accumulating both encoder and decoder stage outputs. Through lightweight pseudo-query attention, each stage selectively aggregates from all preceding representations. To bridge the gap between the same-dimensional Transformer layers in LLMs and the multi-scale encoder-decoder stages in segmentation networks, XAttnRes introduces spatial alignment and channel projection steps that handle cross-resolution features with negligible overhead. When added to existing segmentation networks, XAttnRes consistently improves performance across four datasets and three imaging modalities. We further observe that XAttnRes alone, even without skip connections, achieves performance on par with the baseline, suggesting that learned aggregation can recover the inter-stage information flow traditionally provided by predetermined connections.
### Title:
          PollutionNet: A Vision Transformer Framework for Climatological Assessment of NO$_2$ and SO$_2$ Using Satellite-Ground Data Fusion
 - **Authors:** Prasanjit Dey, Soumyabrata Dev, Bianca Schoen-Phelan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Atmospheric and Oceanic Physics (physics.ao-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate assessment of atmospheric nitrogen dioxide (NO$_2$) and sulfur dioxide (SO$_2$) is essential for understanding climate-air quality interactions, supporting environmental policy, and protecting public health. Traditional monitoring approaches face limitations: satellite observations provide broad spatial coverage but suffer from data gaps, while ground-based sensors offer high temporal resolution but limited spatial extent. To address these challenges, we propose PollutionNet, a Vision Transformer-based framework that integrates Sentinel-5P TROPOMI vertical column density (VCD) data with ground-level observations. By leveraging self-attention mechanisms, PollutionNet captures complex spatiotemporal dependencies that are often missed by conventional CNN and RNN models. Applied to Ireland (2020-2021), our case study demonstrates that PollutionNet achieves state-of-the-art performance (RMSE: 6.89 $\mu$g/m$^3$ for NO$_2$, 4.49 $\mu$g/m$^3$ for SO$_2$), reducing prediction errors by up to 14% compared to baseline models. Beyond accuracy gains, PollutionNet provides a scalable and data-efficient tool for applied climatology, enabling robust pollution assessments in regions with sparse monitoring networks. These results highlight the potential of advanced machine learning approaches to enhance climate-related air quality research, inform environmental management, and support sustainable policy decisions.
### Title:
          When Sinks Help or Hurt: Unified Framework for Attention Sink in Large Vision-Language Models
 - **Authors:** Jiho Choi, Jaemin Kim, Sanghwan Kim, Seunghoon Hong, Jin-Hwi Park
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Attention sinks are defined as tokens that attract disproportionate attention. While these have been studied in single modality transformers, their cross-modal impact in Large Vision-Language Models (LVLM) remains largely unexplored: are they redundant artifacts or essential global priors? This paper first categorizes visual sinks into two distinct categories: ViT-emerged sinks (V-sinks), which propagate from the vision encoder, and LLM-emerged sinks (L-sinks), which arise within deep LLM layers. Based on the new definition, our analysis reveals a fundamental performance trade-off: while sinks effectively encode global scene-level priors, their dominance can suppress the fine-grained visual evidence required for local perception. Furthermore, we identify specific functional layers where modulating these sinks most significantly impacts downstream performance. To leverage these insights, we propose Layer-wise Sink Gating (LSG), a lightweight, plug-and-play module that dynamically scales the attention contributions of V-sink and the rest visual tokens. LSG is trained via standard next-token prediction, requiring no task-specific supervision while keeping the LVLM backbone frozen. In most layers, LSG yields improvements on representative multimodal benchmarks, effectively balancing global reasoning and precise local evidence.
### Title:
          Bridging the Dimensionality Gap: A Taxonomy and Survey of 2D Vision Model Adaptation for 3D Analysis
 - **Authors:** Akshat Pandya, Bhavuk Jain
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The remarkable success of Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs) in 2D vision has spurred significant research in extending these architectures to the complex domain of 3D analysis. Yet, a core challenge arises from a fundamental dichotomy between the regular, dense grids of 2D images and the irregular, sparse nature of 3D data such as point clouds and meshes. This survey provides a comprehensive review and a unified taxonomy of adaptation strategies that bridge this gap, classifying them into three families: (1) Data-centric methods that project 3D data into 2D formats to leverage off-the-shelf 2D models, (2) Architecture-centric methods that design intrinsic 3D networks, and (3) Hybrid methods, which synergistically combine the two modeling paradigms to benefit from both rich visual priors of large 2D datasets and explicit geometric reasoning of 3D models. Through this framework, we qualitatively analyze the fundamental trade-offs between these families concerning computational complexity, reliance on large-scale pre-training, and the preservation of geometric inductive biases. We discuss key open challenges and outline promising future research directions, including the development of 3D foundation models, advancements in self-supervised learning (SSL) for geometric data, and the deeper integration of multi-modal signals.
### Title:
          Hierarchical Awareness Adapters with Hybrid Pyramid Feature Fusion for Dense Depth Prediction
 - **Authors:** Wuqi Su, Huilun Song, Chen Zhao, Chi Xu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Monocular depth estimation from a single RGB image remains a fundamental challenge in computer vision due to inherent scale ambiguity and the absence of explicit geometric cues. Existing approaches typically rely on increasingly complex network architectures to regress depth maps, which escalates training costs and computational overhead without fully exploiting inter-pixel spatial dependencies. We propose a multilevel perceptual conditional random field (CRF) model built upon the Swin Transformer backbone that addresses these limitations through three synergistic innovations: (1) an adaptive hybrid pyramid feature fusion (HPF) strategy that captures both short-range and long-range dependencies by combining multi-scale spatial pyramid pooling with biaxial feature aggregation, enabling effective integration of global and local contextual information; (2) a hierarchical awareness adapter (HA) that enriches cross-level feature interactions within the encoder through lightweight broadcast modules with learnable dimensional scaling, reducing computational complexity while enhancing representational capacity; and (3) a fully-connected CRF decoder with dynamic scaling attention that models fine-grained pixel-level spatial relationships, incorporating a bias learning unit to prevent extreme-value collapse and ensure stable training. Extensive experiments on NYU Depth v2, KITTI, and MatterPort3D datasets demonstrate that our method achieves state-of-the-art performance, reducing Abs Rel to 0.088 ($-$7.4\%) and RMSE to 0.316 ($-$5.4\%) on NYU Depth v2, while attaining near-perfect threshold accuracy ($\delta < 1.25^3 \approx 99.8\%$) on KITTI with only 194M parameters and 21ms inference time.
### Title:
          Noise Steering for Controlled Text Generation: Improving Diversity and Reading-Level Fidelity in Arabic Educational Story Generation
 - **Authors:** Haziq Mohammad Khalid, Salsabeel Shapsough, Imran Zualkernan
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generating diverse, pedagogically valid stories for Arabic early-grade reading assessments requires balancing tight constraints on vocabulary, reading level, and narrative structure against the need to avoid repetitive plots that undermine assessment validity. We investigate noise steering, injecting calibrated Gaussian perturbations into the internal representations of transformer models at inference time, as a training-free diversity method evaluated across five small Arabic-centric language models (7-9B parameters). We compare four injection strategies against high-temperature sampling baselines, measuring diversity, quality, constraint adherence, and reading grade level. Residual stream noise consistently improves narrative diversity with minimal quality or constraint cost and preserves early-grade reading level across all models. Attention entropy noise injection (AENI) stabilizes the otherwise unreliable attention-logit noise while recovering quality. High-temperature sampling inflates reading grade level and causes catastrophic collapse on several models. We find internal representation-level perturbation to be a more suitable diversity strategy than output-level stochasticity for constrained educational content generation.
### Title:
          Zero-Shot Quantization via Weight-Space Arithmetic
 - **Authors:** Daniele Solombrino, Antonio Andrea Gargiulo, Adrian Robert Minut, Luca Zhou, Alessandro Zirilli, Emanuele Rodolà
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We show that robustness to post-training quantization (PTQ) is a transferable direction in weight space. We call this direction the quantization vector: extracted from a donor task by simple weight-space arithmetic, it can be used to patch a receiver model and improve robustness to PTQ-induced noise by as much as 60%, without receiver-side quantization-aware training (QAT). Because the method requires no receiver training data, it provides a zero-shot, low-cost alternative to QAT for extremely low-bit deployment. We demonstrate this on Vision Transformer (ViT) models. More broadly, our results suggest that quantization robustness is not merely a byproduct of task-specific training, but a reusable feature of weight-space geometry that can be transferred rather than retrained.
### Title:
          AEGIS: Scaling Long-Sequence Homomorphic Encrypted Transformer Inference via Hybrid Parallelism on Multi-GPU Systems
 - **Authors:** Zhaoting Gong, Ran Ran, Fan Yao, Wujie Wen
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fully Homomorphic Encryption (FHE) enables privacy-preserving Transformer inference, but long-sequence encrypted Transformers quickly exceed single-GPU memory capacity because encoded weights are already large and encrypted activations grow rapidly with sequence length. Multi-GPU execution therefore becomes unavoidable, yet scaling remains challenging because communication is jointly induced by application-level aggregation and encryption-level RNS coupling. Existing approaches either synchronize between devices frequently or replicate encrypted tensors across devices, leading to excessive communication and latency. We present AEGIS, an Application-Encryption Guided Inference System for scalable long-sequence encrypted Transformer inference on multi-GPU platforms. AEGIS derives device placement from ciphertext dependencies jointly induced by Transformer dataflow and CKKS polynomial coupling, co-locating modulus-coherent and token-coherent data so that communication is introduced only when application dependencies require it, while reordering polynomial operators to overlap the remaining collectives with computation. On 2048-token inputs, AEGIS reduces inter-GPU communication by up to 57.9% in feed-forward networks and 81.3% in self-attention versus prior state-of-the-art designs. On four GPUs, it achieves up to 96.62% scaling efficiency, 3.86x end-to-end speedup, and 69.1% per-device memory reduction. These results establish coordinated application-encryption parallelism as a practical foundation for scalable homomorphic Transformer inference.
### Title:
          Inference-Path Optimization via Circuit Duplication in Frozen Visual Transformers for Marine Species Classification
 - **Authors:** Thomas Manuel Rost
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automated underwater species classification is constrained by annotation cost and environmental variation that limits the transferability of fully supervised models. Recent work has shown that frozen embeddings from self-supervised vision foundation models already provide a strong label-efficient baseline for marine image classification. Here we investigate whether this frozen-embedding regime can be improved at inference time, without fine-tuning or changing model weights. We apply Circuit Duplication, an inference-time method originally proposed for Large Language Models, in which a selected range of transformer layers is traversed twice during the forward pass. We evaluate on the class-imbalanced AQUA20 benchmark using frozen DINOv3 embeddings under two settings: global circuit selection, where a single duplicated circuit is chosen for the full dataset, and class-specific circuit selection, where each species may receive a different optimal circuit. Both settings use simple semi-supervised downstream classifiers. Circuit Duplication consistently improves over the standard frozen forward pass. At the maximum label budget, class-specific selection reaches a macro F1 of 0.875, closing the gap to the fully supervised ConvNeXt benchmark (0.889) to 1.4 points without any gradient-based training. Four species exceed their fully supervised reference, with octopus improving by +12.1 F1 points. Across all budgets, roughly 75% of classes prefer a class-specific circuit, indicating a genuinely class-dependent benefit. To our knowledge, this is the first application of Circuit Duplication to computer vision.
### Title:
          Agile Story-Point Estimation: Is RAG a Better Way to Go?
 - **Authors:** Lamyea Maha, Tajmilur Rahman, Chanchal Roy
 - **Subjects:** Subjects:
Software Engineering (cs.SE); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The sprint-based iterative approach in the Agile software development method allows continuous feedback and adaptation. One of the crucial Agile software development activities is the sprint planning session where developers estimate the effort required to complete tasks through a consensus-based estimation technique such as Planning Poker. In the Agile software development method, a common unit of measuring development effort is Story Point (SP) which is assigned to tasks to understand the complexity and development time needed to complete them. Despite the benefits of this process, it is an extremely time-consuming manual process. To mitigate this issue, in this study, we investigated if this manual process can be automated using Retrieval Augmented Generation (RAG) which comprises a "Retriever" and a "Generator". We applied two embedding models - bge-large-en-v1.5, and Sentence-Transformers' all-mpnet-base-v2 on 23 open-source software projects of varying sizes and examined four key aspects: 1) how retrieval hyper-parameters influence the performance, 2) whether estimation accuracy differs across different sizes of the projects, 3) whether embedding model choice affects accuracy, and 4) how the RAG-based approach compares to the existing baselines. Although the RAG-based approach outperformed the baseline models in several occasions, our results did not exhibit statistically significant differences in performance across the projects or across the embedding models. This highlights the need for further studies and refinement of the RAG, and model adaptation strategies for better accuracy in automatically estimating user stories.
### Title:
          Olmo Hybrid: From Theory to Practice and Back
 - **Authors:** William Merrill, Yanhong Li, Tyler Romero, Anej Svete, Caia Costello, Pradeep Dasigi, Dirk Groeneveld, David Heineman, Bailey Kuehl, Nathan Lambert, Jacob Morrison, Luca Soldaini, Finbarr Timbers, Pete Walsh, Noah A. Smith, Hannaneh Hajishirzi, Ashish Sabharwal
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent work has demonstrated the potential of non-transformer language models, especially linear recurrent neural networks (RNNs) and hybrid models that mix recurrence and attention. Yet there is no consensus on whether the potential benefits of these new architectures justify the risk and effort of scaling them up. To address this, we provide evidence for the advantages of hybrid models over pure transformers on several fronts. First, theoretically, we show that hybrid models do not merely inherit the expressivity of transformers and linear RNNs, but can express tasks beyond both, such as code execution. Putting this theory to practice, we train Olmo Hybrid, a 7B-parameter model largely comparable to Olmo 3 7B but with the sliding window layers replaced by Gated DeltaNet layers. We show that Olmo Hybrid outperforms Olmo 3 across standard pretraining and mid-training evaluations, demonstrating the benefit of hybrid models in a controlled, large-scale setting. We find that the hybrid model scales significantly more efficiently than the transformer, explaining its higher performance. However, its unclear why greater expressivity on specific formal problems should result in better scaling or superior performance on downstream tasks unrelated to those problems. To explain this apparent gap, we return to theory and argue why increased expressivity should translate to better scaling efficiency, completing the loop. Overall, our results suggest that hybrid models mixing attention and recurrent layers are a powerful extension to the language modeling paradigm: not merely to reduce memory during inference, but as a fundamental way to obtain more expressive models that scale better during pretraining.
### Title:
          Fast Cross-Operator Optimization of Attention Dataflow
 - **Authors:** Haodong Chang, Hailiang Hu, Zhenrui Wang, Yu Gong, Rongjian Liang, Zhexiang Tang, Bo Yuan, Jiang Hu
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Attention is a fundamental computational kernel that accounts for the majority of the workload in transformer and LLM computing. Optimizing dataflow is crucial for enhancing both performance and energy efficiency in attention computation. This optimization involves a range of decisions, such as tiling, computation ordering and buffer management, and can be applied at both intra-operator and inter-operator levels, resulting in a highly complex decision space. We propose a new approach to cross-operator dataflow optimization. Its centerpiece is an analytical performance model that spans a large decision space and enables matrix-based encoding of multiple candidate solutions. Built on this foundation, a vast number of solutions can be evaluated rapidly, and with the aid of an effective pruning technique, the optimal solution can be identified through exhaustive enumeration. We refer to our method as MMEE (Matrix Multiplication Encoded Enumeration). The ability to efficiently enumerate a large design space allows MMEE to deliver higher-quality solutions at a substantially faster speed compared to prior approaches. The MMEE approach is evaluated across various test cases for different accelerator configurations. For energy-driven optimization, MMEE reduces energy consumption by 48%-50% and latency by 31%-69%, compared to state-of-the-art methods. For latency-driven optimization, MMEE achieves simultaneous reductions of 40%-50% in energy consumption and 40%-69% in latency, respectively. Additionally, MMEE is $64\times$ to $343\times$ faster than previous works.
### Title:
          Resource-Conscious Modeling for Next- Day Discharge Prediction Using Clinical Notes
 - **Authors:** Ha Na Cho, Sairam Sutari, Alexander Lopez, Hansen Bow, Kai Zheng
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Timely discharge prediction is essential for optimizing bed turnover and resource allocation in elective spine surgery units. This study evaluates the feasibility of lightweight, fine-tuned large language models (LLMs) and traditional text-based models for predicting next-day discharge using postoperative clinical notes. We compared 13 models, including TF-IDF with XGBoost and LGBM, and compact LLMs (DistilGPT-2, Bio_ClinicalBERT) fine-tuned via LoRA. TF-IDF with LGBM achieved the best balance, with an F1-score of 0.47 for the discharge class, a recall of 0.51, and the highest AUC-ROC (0.80). While LoRA improved recall in DistilGPT2, overall transformer-based and generative models underperformed. These findings suggest interpretable, resource-efficient models may outperform compact LLMs in real-world, imbalanced clinical prediction tasks.
### Title:
          Multimodal Urban Tree Detection from Satellite and Street-Level Imagery via Annotation-Efficient Deep Learning Strategies
 - **Authors:** In Seon Kim, Ali Moghimi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Beyond the immediate biophysical benefits, urban trees play a foundational role in environmental sustainability and disaster mitigation. Precise mapping of urban trees is essential for environmental monitoring, post-disaster assessment, and strengthening policy. However, the transition from traditional, labor-intensive field surveys to scalable automated systems remains limited by high annotation costs and poor generalization across diverse urban scenarios. This study introduces a multimodal framework that integrates high-resolution satellite imagery with ground-level Google Street View to enable scalable and detailed urban tree detection under limited-annotation conditions. The framework first leverages satellite imagery to localize tree candidates and then retrieves targeted ground-level views for detailed detection, significantly reducing inefficient street-level sampling. To address the annotation bottleneck, domain adaptation is used to transfer knowledge from an existing annotated dataset to a new region of interest. To further minimize human effort, we evaluated three learning strategies: semi-supervised learning, active learning, and a hybrid approach combining both, using a transformer-based detection model. The hybrid strategy achieved the best performance with an F1-score of 0.90, representing a 12% improvement over the baseline model. In contrast, semi-supervised learning exhibited progressive performance degradation due to confirmation bias in pseudo-labeling, while active learning steadily improved results through targeted human intervention to label uncertain or incorrect predictions. Error analysis further showed that active and hybrid strategies reduced both false positives and false negatives. Our findings highlight the importance of a multimodal approach and guided annotation for scalable, annotation-efficient urban tree mapping to strengthen sustainable city planning.
### Title:
          Physics-Informed Transformer for Real-Time High-Fidelity Topology Optimization
 - **Authors:** Aaron Lutheran, Srijan Das, Alireza Tabarraei
 - **Subjects:** Subjects:
Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Topology optimization is used for the design of high-performance structures but remains fundamentally limited by its iterative nature, requiring repeated finite element analyses that prevent real-time deployment and large-scale design exploration. In this work, we introduce a physics-informed transformer architecture that directly learns a non-iterative mapping from boundary conditions, loading configurations, and derived physical fields to optimized structural topologies. By leveraging global self-attention, the proposed model captures long-range mechanical interactions that govern structural response, overcoming the locality limitations of convolutional architectures. A conditioning-token mechanism embeds global problem parameters, while spatially distributed stress and strain energy fields are encoded as patch tokens within a Vision Transformer framework. To ensure physical realism and manufacturability, we incorporate auxiliary loss functions that enforce volume constraints, load adherence, and structural connectivity through a differentiable formulation. The framework is further extended to dynamic loading scenarios using frequency-domain encoding and transfer learning, enabling efficient generalization from static to time-dependent problems. Comprehensive benchmarking demonstrates that the proposed model achieves fidelity beyond that of diffusion models, while requiring only a single forward pass, thereby eliminating iterative inference entirely. This establishes topology optimization as a real-time operator-learning problem, enabling high-fidelity structural design with significant reductions in computational cost.
### Title:
          Structural Rigidity and the 57-Token Predictive Window: A Physical Framework for Inference-Layer Governability in Large Language Models
 - **Authors:** Gregory M. Ruddell
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Current AI safety relies on behavioral monitoring and post-training alignment, yet empirical measurement shows these approaches produce no detectable pre-commitment signal in a majority of instruction-tuned models tested. We present an energy-based governance framework connecting transformer inference dynamics to constraint-satisfaction models of neural computation, and apply it to a seven-model cohort across five geometric regimes. Using trajectory tension (rho = ||a|| / ||v||), we identify a 57-token pre-commitment window in Phi-3-mini-4k-instruct under greedy decoding on arithmetic constraint probes. This result is model-specific, task-specific, and configuration-specific, demonstrating that pre-commitment signals can exist but are not universal. We introduce a five-regime taxonomy of inference behavior: Authority Band, Late Signal, Inverted, Flat, and Scaffold-Selective. Energy asymmetry ({\Sigma}\r{ho}_misaligned / {\Sigma}\r{ho}_aligned) serves as a unifying metric of structural rigidity across these regimes. Across seven models, only one configuration exhibits a predictive signal prior to commitment; all others show silent failure, late detection, inverted dynamics, or flat geometry. We further demonstrate that factual hallucination produces no predictive signal across 72 test conditions, consistent with spurious attractor settling in the absence of a trained world-model constraint. These results establish that rule violation and hallucination are distinct failure modes with different detection requirements. Internal geometry monitoring is effective only where resistance exists; detection of factual confabulation requires external verification mechanisms. This work provides a measurable framework for inference-layer governability and introduces a taxonomy for evaluating deployment risk in autonomous AI systems.
### Title:
          CRAFT: Video Diffusion for Bimanual Robot Data Generation
 - **Authors:** Jason Chen, I-Chun Arthur Liu, Gaurav Sukhatme, Daniel Seita
 - **Subjects:** Subjects:
Robotics (cs.RO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bimanual robot learning from demonstrations is fundamentally limited by the cost and narrow visual diversity of real-world data, which constrains policy robustness across viewpoints, object configurations, and embodiments. We present Canny-guided Robot Data Generation using Video Diffusion Transformers (CRAFT), a video diffusion-based framework for scalable bimanual demonstration generation that synthesizes temporally coherent manipulation videos while producing action labels. By conditioning video diffusion on edge-based structural cues extracted from simulator-generated trajectories, CRAFT produces physically plausible trajectory variations and supports a unified augmentation pipeline spanning object pose changes, camera viewpoints, lighting and background variations, cross-embodiment transfer, and multi-view synthesis. We leverage a pre-trained video diffusion model to convert simulated videos, along with action labels from the simulation trajectories, into action-consistent demonstrations. Starting from only a few real-world demonstrations, CRAFT generates a large, visually diverse set of photorealistic training data, bypassing the need to replay demonstrations on the real robot (Sim2Real). Across simulated and real-world bimanual tasks, CRAFT improves success rates over existing augmentation strategies and straightforward data scaling, demonstrating that diffusion-based video generation can substantially expand demonstration diversity and improve generalization for dual-arm manipulation tasks. Our project website is available at: this https URL
### Title:
          When Do Hallucinations Arise? A Graph Perspective on the Evolution of Path Reuse and Path Compression
 - **Authors:** Xinnan Dai, Kai Yang, Cheng Luo, Shenglai Zeng, Kai Guo, Jiliang Tang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reasoning hallucinations in large language models (LLMs) often appear as fluent yet unsupported conclusions that violate either the given context or underlying factual knowledge. Although such failures are widely observed, the mechanisms by which decoder-only Transformers produce them remain poorly understood. We model next-token prediction as a graph search process over an underlying graph, where entities correspond to nodes and learned transitions form edges. From this perspective, contextual reasoning is a constrained search over a sampled subgraph (intrinsic reasoning), while context-free queries rely on memorized structures in the underlying graph (extrinsic reasoning). We show that reasoning hallucinations arise from two fundamental mechanisms: \textbf{Path Reuse}, where memorized knowledge overrides contextual constraints during early training, and \textbf{Path Compression}, where frequently traversed multi-step paths collapse into shortcut edges in later training. Together, these mechanisms provide a unified explanation for reasoning hallucinations in LLMs and connected to well-known behaviors observed in downstream applications.
### Title:
          Physics-Informed Untrained Learning for RGB-Guided Superresolution Single-Pixel Hyperspectral Imaging
 - **Authors:** Hao Zhang, Bilige Xu, Lichen Wei, Xu Ma, Wenyi Ren
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Optics (physics.optics)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Single-pixel imaging (SPI) offers a cost-effective route to hyperspectral acquisition but struggles to recover high-fidelity spatial and spectral details under extremely low sampling rates, a severely ill-posed inverse problem. While deep learning has shown potential, existing data-driven methods demand large-scale pretraining datasets that are often impractical in hyperspectral imaging. To overcome this limitation, we propose an end-to-end physics-informed framework that leverages untrained neural networks and RGB guidance for joint hyperspectral reconstruction and super-resolution without any external training data. The framework comprises three physically grounded stages: (1) a Regularized Least-Squares method with RGB-derived Grayscale Priors (LS-RGP) that initializes the solution by exploiting cross-modal structural correlations; (2) an Untrained Hyperspectral Recovery Network (UHRNet) that refines the reconstruction through measurement consistency and hybrid regularization; and (3) a Transformer-based Untrained Super-Resolution Network (USRNet) that upsamples the spatial resolution via cross-modal attention, transferring high-frequency details from the RGB guide. Extensive experiments on benchmark datasets demonstrate that our approach significantly surpasses state-of-the-art algorithms in both reconstruction accuracy and spectral fidelity. Moreover, a proof-of-concept experiment using a physical single-pixel imaging system validates the framework's practical applicability, successfully reconstructing a 144-band hyperspectral data cube at a mere 6.25% sampling rate. The proposed method thus provides a robust, data-efficient solution for computational hyperspectral imaging.
### Title:
          Simple yet Effective: Low-Rank Spatial Attention for Neural Operators
 - **Authors:** Zherui Yang, Haiyang Xin, Tao Du, Ligang Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural operators have emerged as data-driven surrogates for solving partial differential equations (PDEs), and their success hinges on efficiently modeling the long-range, global coupling among spatial points induced by the underlying physics. In many PDE regimes, the induced global interaction kernels are empirically compressible, exhibiting rapid spectral decay that admits low-rank approximations. We leverage this observation to unify representative global mixing modules in neural operators under a shared low-rank template: compressing high-dimensional pointwise features into a compact latent space, processing global interactions within it, and reconstructing the global context back to spatial points. Guided by this view, we introduce Low-Rank Spatial Attention (LRSA) as a clean and direct instantiation of this template. Crucially, unlike prior approaches that often rely on non-standard aggregation or normalization modules, LRSA is built purely from standard Transformer primitives, i.e., attention, normalization, and feed-forward networks, yielding a concise block that is straightforward to implement and directly compatible with hardware-optimized kernels. In our experiments, such a simple construction is sufficient to achieve high accuracy, yielding an average error reduction of over 17\% relative to second-best methods, while remaining stable and efficient in mixed-precision training.
### Title:
          Can Natural Image Autoencoders Compactly Tokenize fMRI Volumes for Long-Range Dynamics Modeling?
 - **Authors:** Peter Yongho Kim, Juhyeon Park, Jungwoo Park, Jubin Choi, Jungwoo Seo, Jiook Cha, Taesup Moon
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modeling long-range spatiotemporal dynamics in functional Magnetic Resonance Imaging (fMRI) remains a key challenge due to the high dimensionality of the four-dimensional signals. Prior voxel-based models, although demonstrating excellent performance and interpretation capabilities, are constrained by prohibitive memory demands and thus can only capture limited temporal windows. To address this, we propose TABLeT (Two-dimensionally Autoencoded Brain Latent Transformer), a novel approach that tokenizes fMRI volumes using a pre-trained 2D natural image autoencoder. Each 3D fMRI volume is compressed into a compact set of continuous tokens, enabling long-sequence modeling with a simple Transformer encoder with limited VRAM. Across large-scale benchmarks including the UK-Biobank (UKB), Human Connectome Project (HCP), and ADHD-200 datasets, TABLeT outperforms existing models in multiple tasks, while demonstrating substantial gains in computational and memory efficiency over the state-of-the-art voxel-based method given the same input. Furthermore, we develop a self-supervised masked token modeling approach to pre-train TABLeT, which improves the model's performance for various downstream tasks. Our findings suggest a promising approach for scalable and interpretable spatiotemporal modeling of brain activity. Our code is available at this https URL.
### Title:
          Algebraic Diversity: Group-Theoretic Spectral Estimation from Single Observations
 - **Authors:** Mitchell A. Thornton
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Information Theory (cs.IT); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We prove that temporal averaging over multiple observations can be replaced by algebraic group action on a single observation for second-order statistical estimation. A General Replacement Theorem establishes conditions under which a group-averaged estimator from one snapshot achieves equivalent subspace decomposition to multi-snapshot covariance estimation, and an Optimality Theorem proves that the symmetric group is universally optimal (yielding the KL transform). The framework unifies the DFT, DCT, and KLT as special cases of group-matched spectral transforms, with a closed-form double-commutator eigenvalue problem for polynomial-time optimal group selection. Five applications are demonstrated: MUSIC DOA estimation from a single snapshot, massive MIMO channel estimation with 64% throughput gain, single-pulse waveform classification at 90% accuracy, graph signal processing with non-Abelian groups, and a new algebraic analysis of transformer LLMs revealing that RoPE uses the wrong algebraic group for 70-80% of attention heads across five models (22,480 head observations), that the optimal group is content-dependent, and that spectral-concentration-based pruning improves perplexity at the 13B scale. All diagnostics require a single forward pass with no gradients or training.
### Title:
          A Generative Foundation Model for Multimodal Histopathology
 - **Authors:** Jinxi Xiang, Mingjie Li, Siyu Hou, Yijiang Chen, Xiangde Luo, Yuanfeng Ji, Xiang Zhou, Ehsan Adeli, Akshay Chaudhari, Curtis P. Langlotz, Kilian M. Pohl, Ruijiang Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate diagnosis and treatment of complex diseases require integrating histological, molecular, and clinical data, yet in practice these modalities are often incomplete owing to tissue scarcity, assay cost, and workflow constraints. Existing computational approaches attempt to impute missing modalities from available data but rely on task-specific models trained on narrow, single source-target pairs, limiting their generalizability. Here we introduce MuPD (Multimodal Pathology Diffusion), a generative foundation model that embeds hematoxylin and eosin (H&E)-stained histology, molecular RNA profiles, and clinical text into a shared latent space through a diffusion transformer with decoupled cross-modal attention. Pretrained on 100 million histology image patches, 1.6 million text-histology pairs, and 10.8 million RNA-histology pairs spanning 34 human organs, MuPD supports diverse cross-modal synthesis tasks with minimal or no task-specific fine-tuning. For text-conditioned and image-to-image generation, MuPD synthesizes histologically faithful tissue architectures, reducing Fréchet inception distance (FID) scores by 50% relative to domain-specific models and improving few-shot classification accuracy by up to 47% through synthetic data augmentation. For RNA-conditioned histology generation, MuPD reduces FID by 23% compared with the next-best method while preserving cell-type distributions across five cancer types. As a virtual stainer, MuPD translates H&E images to immunohistochemistry and multiplex immunofluorescence, improving average marker correlation by 37% over existing approaches. These results demonstrate that a single, unified generative model pretrained across heterogeneous pathology modalities can substantially outperform specialized alternatives, providing a scalable computational framework for multimodal histopathology.
### Title:
          ART: Adaptive Relational Transformer for Pedestrian Trajectory Prediction with Temporal-Aware Relations
 - **Authors:** Ruochen Li, Ziyi Chang, Junyan Hu, Jiannan Li, Amir Atapour-Abarghouei, Hubert P. H. Shum
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate prediction of real-world pedestrian trajectories is crucial for a wide range of robot-related applications. Recent approaches typically adopt graph-based or transformer-based frameworks to model interactions. Despite their effectiveness, these methods either introduce unnecessary computational overhead or struggle to represent the diverse and time-varying characteristics of human interactions. In this work, we present an Adaptive Relational Transformer (ART), which introduces a Temporal-Aware Relation Graph (TARG) to explicitly capture the evolution of pairwise interactions and an Adaptive Interaction Pruning (AIP) mechanism to reduce redundant computations efficiently. Extensive evaluations on ETH/UCY and NBA benchmarks show that ART delivers state-of-the-art accuracy with high computational efficiency.
### Title:
          CAGMamba: Context-Aware Gated Cross-Modal Mamba Network for Multimodal Sentiment Analysis
 - **Authors:** Minghai Jiao, Jing Xiao, Peng Xiao, Ende Zhang, Shuang Kan, Wenyan Jiang, Jinyao Li, Yixian Liu, Haidong Xin
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal Sentiment Analysis (MSA) requires effective modeling of cross-modal interactions and contextual dependencies while remaining computationally efficient. Existing fusion approaches predominantly rely on Transformer-based cross-modal attention, which incurs quadratic complexity with respect to sequence length and limits scalability. Moreover, contextual information from preceding utterances is often incorporated through concatenation or independent fusion, without explicit temporal modeling that captures sentiment evolution across dialogue turns. To address these limitations, we propose CAGMamba, a context-aware gated cross-modal Mamba framework for dialogue-based sentiment analysis. Specifically, we organize the contextual and the current-utterance features into a temporally ordered binary sequence, which provides Mamba with explicit temporal structure for modeling sentiment evolution. To further enable controllable cross-modal integration, we propose a Gated Cross-Modal Mamba Network (GCMN) that integrates cross-modal and unimodal paths via learnable gating to balance information fusion and modality preservation, and is trained with a three-branch multi-task objective over text, audio, and fused predictions. Experiments on three benchmark datasets demonstrate that CAGMamba achieves state-of-the-art or competitive results across multiple evaluation metrics. All codes are available at this https URL.
### Title:
          AI Appeals Processor: A Deep Learning Approach to Automated Classification of Citizen Appeals in Government Services
 - **Authors:** Vladimir Beskorovainyi
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Government agencies worldwide face growing volumes of citizen appeals, with electronic submissions increasing significantly over recent years. Traditional manual processing averages 20 minutes per appeal with only 67% classification accuracy, creating significant bottlenecks in public service delivery. This paper presents AI Appeals Processor, a microservice-based system that integrates natural language processing and deep learning techniques for automated classification and routing of citizen appeals. We evaluate multiple approaches -- including Bag-of-Words with SVM, TF-IDF with SVM, fastText, Word2Vec with LSTM, and BERT -- on a representative dataset of 10,000 real citizen appeals across three primary categories (complaints, applications, and proposals) and seven thematic domains. Our experiments demonstrate that a Word2Vec+LSTM architecture achieves 78% classification accuracy while reducing processing time by 54%, offering an optimal balance between accuracy and computational efficiency compared to transformer-based models.
### Title:
          DiffSparse: Accelerating Diffusion Transformers with Learned Token Sparsity
 - **Authors:** Haowei Zhu, Ji Liu, Ziqiong Liu, Dong Li, Junhai Yong, Bin Wang, Emad Barsoum
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion models demonstrate outstanding performance in image generation, but their multi-step inference mechanism requires immense computational cost. Previous works accelerate inference by leveraging layer or token cache techniques to reduce computational cost. However, these methods fail to achieve superior acceleration performance in few-step diffusion transformer models due to inefficient feature caching strategies, manually designed sparsity allocation, and the practice of retaining complete forward computations in several steps in these token cache methods. To tackle these challenges, we propose a differentiable layer-wise sparsity optimization framework for diffusion transformer models, leveraging token caching to reduce token computation costs and enhance acceleration. Our method optimizes layer-wise sparsity allocation in an end-to-end manner through a learnable network combined with a dynamic programming solver. Additionally, our proposed two-stage training strategy eliminates the need for full-step processing in existing methods, further improving efficiency. We conducted extensive experiments on a range of diffusion-transformer models, including DiT-XL/2, PixArt-$\alpha$, FLUX, and Wan2.1. Across these architectures, our method consistently improves efficiency without degrading sample quality. For example, on PixArt-$\alpha$ with 20 sampling steps, we reduce computational cost by $54\%$ while achieving generation metrics that surpass those of the original model, substantially outperforming prior approaches. These results demonstrate that our method delivers large efficiency gains while often improving generation quality.
### Title:
          TransGP: Task-Conditioned Transformer-Guided Genetic Programming for Multitask Dynamic Flexible Job Shop Scheduling
 - **Authors:** Meng Xu, Jiao Liu, Hua Yu, Yew Soon Ong
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hyper-heuristics have become a popular approach for solving dynamic flexible job shop scheduling (DFJSS) problems. They use gradient-free optimization techniques like Genetic Programming (GP) to evolve non-differentiable heuristics. However, conventional GP methods tend to converge slowly because they rely solely on evolutionary search to find good heuristics. Existing multitask GP methods can solve multiple tasks simultaneously and speed up the search by transferring knowledge across similar tasks. But they mostly exchange heuristic building blocks without truly generating heuristics conditioned on task information. In this paper, we aim to accelerate convergence and enable task-specific heuristic generation by incorporating a task-conditioned Transformer model. The Transformer works in two ways. First, it learns the distribution of elite heuristics, biasing the search toward promising regions of the heuristic space. Second, through conditional generation, it produces heuristics tailored to specific tasks, allowing the model to handle multiple scheduling tasks at once and improving overall optimization efficiency. Based on these ideas, we propose TransGP, a Task-Conditioned Transformer-Guided GP framework. This evolutionary paradigm integrates generative modeling with GP, enabling efficient multitask heuristic learning and knowledge transfer. We evaluate TransGP on a range of DFJSS scenarios. Experimental results show that TransGP consistently outperforms multitask GP baselines, widely used handcrafted heuristics, and the pure Transformer model, achieving faster convergence, superior solution quality, and enhanced robustness.
### Title:
          Automated Attention Pattern Discovery at Scale in Large Language Models
 - **Authors:** Jonathan Katzy, Razvan-Mihai Popescu, Erik Mekkes, Arie van Deursen, Maliheh Izadi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models have found success by scaling up capabilities to work in general settings. The same can unfortunately not be said for interpretability methods. The current trend in mechanistic interpretability is to provide precise explanations of specific behaviors in controlled settings. These often do not generalize, or are too resource intensive for larger studies. In this work we propose to study repeated behaviors in large language models by mining completion scenarios in Java code datasets, through exploiting the structured nature of code. We collect the attention patterns generated in the attention heads to demonstrate that they are scalable signals for global interpretability of model components. We show that vision models offer a promising direction for analyzing attention patterns at scale. To demonstrate this, we introduce the Attention Pattern - Masked Autoencoder(AP-MAE), a vision transformer-based model that efficiently reconstructs masked attention patterns. Experiments on StarCoder2 show that AP-MAE (i) reconstructs masked attention patterns with high accuracy, (ii) generalizes across unseen models with minimal degradation, (iii) reveals recurring patterns across inferences, (iv) predicts whether a generation will be correct without access to ground truth, with accuracies ranging from 55% to 70% depending on the task, and (v) enables targeted interventions that increase accuracy by 13.6% when applied selectively, but cause collapse when applied excessively. These results establish attention patterns as a scalable signal for interpretability and demonstrate that AP-MAE provides a transferable foundation for both analysis and intervention in large language models. Beyond its standalone value, AP-MAE also serves as a selection procedure to guide fine-grained mechanistic approaches. We release code and models to support future work in large-scale interpretability.
### Title:
          HistoFusionNet: Histogram-Guided Fusion and Frequency-Adaptive Refinement for Nighttime Image Dehazing
 - **Authors:** Mohammad Heydari, Wei Dong, Shahram Shirani, Jun Chen, Han Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Nighttime image dehazing remains a challenging low-level vision problem due to the joint presence of haze, glow, non-uniform illumination, color distortion, and sensor noise, which often invalidate assumptions commonly used in daytime dehazing. To address these challenges, we propose HistoFusionNet, a transformer-enhanced architecture tailored for nighttime image dehazing by combining histogram-guided representation learning with frequency-adaptive feature refinement. Built upon a multi-scale encoder-decoder backbone, our method introduces histogram transformer blocks that model long-range dependencies by grouping features according to their dynamic-range characteristics, enabling more effective aggregation of similarly degraded regions under complex nighttime lighting. To further improve restoration fidelity, we incorporate a frequency-aware refinement branch that adaptively exploits complementary low- and high-frequency cues, helping recover scene structures, suppress artifacts, and enhance local details. This design yields a unified framework that is particularly well suited to the heterogeneous degradations encountered in real nighttime hazy scenes. Extensive experiments and highly competitive performance of our method on the NTIRE 2026 Nighttime Image Dehazing Challenge benchmark demonstrate the effectiveness of the proposed method. Our team ranked 1st among 22 participating teams, highlighting the robustness and competitive performance of HistoFusionNet. The code is available at: this https URL
### Title:
          Rényi Attention Entropy for Patch Pruning
 - **Authors:** Hiroaki Aizawa, Yuki Igaue
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformers are strong baselines in both vision and language because self-attention captures long-range dependencies across tokens. However, the cost of self-attention grows quadratically with the number of tokens. Patch pruning mitigates this cost by estimating per-patch importance and removing redundant patches. To identify informative patches for pruning, we introduce a criterion based on the Shannon entropy of the attention distribution. Low-entropy patches, which receive selective and concentrated attention, are kept as important, while high-entropy patches with attention spread across many locations are treated as redundant. We also extend the criterion from Shannon to Rényi entropy, which emphasizes sharp attention peaks and supports pruning strategies that adapt to task needs and computational limits. In experiments on fine-grained image recognition, where patch selection is critical, our method reduced computation while preserving accuracy. Moreover, adjusting the pruning policy through the Rényi entropy measure yields further gains and improves the trade-off between accuracy and computation.
### Title:
          InCaRPose: In-Cabin Relative Camera Pose Estimation Model and Dataset
 - **Authors:** Felix Stillger, Lukas Hahn, Frederik Hasecke, Tobias Meisen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Camera extrinsic calibration is a fundamental task in computer vision. However, precise relative pose estimation in constrained, highly distorted environments, such as in-cabin automotive monitoring (ICAM), remains challenging. We present InCaRPose, a Transformer-based architecture designed for robust relative pose prediction between image pairs, which can be used for camera extrinsic calibration. By leveraging frozen backbone features such as DINOv3 and a Transformer-based decoder, our model effectively captures the geometric relationship between a reference and a target view. Unlike traditional methods, our approach achieves absolute metric-scale translation within the physically plausible adjustment range of in-cabin camera mounts in a single inference step, which is critical for ICAM, where accurate real-world distances are required for safety-relevant perception. We specifically address the challenges of highly distorted fisheye cameras in automotive interiors by training exclusively on synthetic data. Our model is capable of generalization to real-world cabin environments without relying on the exact same camera intrinsics and additionally achieves competitive performance on the public 7-Scenes dataset. Despite having limited training data, InCaRPose maintains high precision in both rotation and translation, even with a ViT-Small backbone. This enables real-time performance for time-critical inference, such as driver monitoring in supervised autonomous driving. We release our real-world In-Cabin-Pose test dataset consisting of highly distorted vehicle-interior images and our code at this https URL.
### Title:
          k-Maximum Inner Product Attention for Graph Transformers and the Expressive Power of GraphGPS The Expressive Power of GraphGPS
 - **Authors:** Jonas De Schouwer, Haitz Sáez de Ocáriz Borde, Xiaowen Dong
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph transformers have shown promise in overcoming limitations of traditional graph neural networks, such as oversquashing and difficulties in modelling long-range dependencies. However, their application to large-scale graphs is hindered by the quadratic memory and computational complexity of the all-to-all attention mechanism. Although alternatives such as linearized attention and restricted attention patterns have been proposed, these often degrade performance or limit expressive power. To better balance efficiency and effectiveness, we introduce k-Maximum Inner Product (k-MIP) attention for graph transformers. k-MIP attention selects the most relevant key nodes per query via a top-k operation, yielding a sparse yet flexible attention pattern. Combined with an attention score computation based on symbolic matrices, this results in linear memory complexity and practical speedups of up to an order of magnitude compared to all-to-all attention, enabling the processing of graphs with over 500k nodes on a single A100 GPU. We provide a theoretical analysis of expressive power, showing that k-MIP attention does not compromise the expressiveness of graph transformers: specifically, we prove that k-MIP transformers can approximate any full-attention transformer to arbitrary precision. In addition, we analyze the expressive power of the GraphGPS framework, in which we integrate our attention mechanism, and establish an upper bound on its graph distinguishing capability in terms of the S-SEG-WL test. Finally, we validate our approach on the Long Range Graph Benchmark, the City-Networks benchmark, and two custom large-scale inductive point cloud datasets, consistently ranking among the top-performing scalable graph transformers.
### Title:
          Explainability-Guided Adversarial Attacks on Transformer-Based Malware Detectors Using Control Flow Graphs
 - **Authors:** Andrew Wheeler, Kshitiz Aryal, Maanak Gupta
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based malware detection systems operating on graph modalities such as control flow graphs (CFGs) achieve strong performance by modeling structural relationships in program behavior. However, their robustness to adversarial evasion attacks remains underexplored. This paper examines the vulnerability of a RoBERTa-based malware detector that linearizes CFGs into sequences of function calls, a design choice that enables transformer modeling but may introduce token-level sensitivities and ordering artifacts exploitable by adversaries. By evaluating evasion strategies within this graph-to-sequence framework, we provide insight into the practical robustness of transformer-based malware detectors beyond aggregate detection accuracy. This paper proposes a white-box adversarial evasion attack that leverages explainability mechanisms to identify and perturb most influential graph components. Using token- and word-level attributions derived from integrated gradients, the attack iteratively replaces positively attributed function calls with synthetic external imports, producing adversarial CFG representations without altering overall program structure. Experimental evaluation on small- and large-scale Windows Portable Executable (PE) datasets demonstrates that the proposed method can reliably induce misclassification, even against models trained to high accuracy. Our results highlight that explainability tools, while valuable for interpretability, can also expose critical attack surfaces in transformer-based malware detectors.
### Title:
          Collapse-Free Prototype Readout Layer for Transformer Encoders
 - **Authors:** Giansalvo Cirrincione, Rahul Ranjeev Kumar
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 DDCL-Attention is a prototype-based readout layer for transformer encoders that replaces simple pooling methods, such as mean pooling or class tokens, with a learned compression mechanism. It uses a small set of global prototype vectors and assigns tokens to them through soft probabilistic matching, producing compact token summaries at linear complexity in sequence length. The method offers three main advantages. First, it avoids prototype collapse through an exact decomposition of the training loss into a reconstruction term and a diversity term, ensuring that prototypes remain distinct. Second, its joint training with the encoder is shown to be stable under a practical timescale condition, using Tikhonov's singular perturbation theory and explicit learning-rate constraints. Third, the same framework supports three uses: a final readout layer, a differentiable codebook extending VQ-VAE, and a hierarchical document compressor. Experiments on four datasets confirm the theoretical predictions: the loss decomposition holds exactly, prototype separation grows as expected when the stability condition is met, and the codebook reaches full utilization, outperforming standard hard vector quantization. An additional study on orbital debris classification shows that the method also applies beyond standard NLP and vision tasks, including scientific tabular data.
### Title:
          Learning 3D Reconstruction with Priors in Test Time
 - **Authors:** Lei Zhou, Haoyu Wu, Akshat Dave, Dimitris Samaras
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce a test-time framework for multiview Transformers (MVTs) that incorporates priors (e.g., camera poses, intrinsics, and depth) to improve 3D tasks without retraining or modifying pre-trained image-only networks. Rather than feeding priors into the architecture, we cast them as constraints on the predictions and optimize the network at inference time. The optimization loss consists of a self-supervised objective and prior penalty terms. The self-supervised objective captures the compatibility among multi-view predictions and is implemented using photometric or geometric loss between renderings from other views and each view itself. Any available priors are converted into penalty terms on the corresponding output modalities. Across a series of 3D vision benchmarks, including point map estimation and camera pose estimation, our method consistently improves performance over base MVTs by a large margin. On the ETH3D, 7-Scenes, and NRGBD datasets, our method reduces the point-map distance error by more than half compared with the base image-only models. Our method also outperforms retrained prior-aware feed-forward methods, demonstrating the effectiveness of our test-time constrained optimization (TCO) framework for incorporating priors into 3D vision tasks.
### Title:
          Reimagining RAN Automation in 6G: An Agentic AI Framework with Hierarchical Online Decision Transformer
 - **Authors:** Md Arafat Habib, Medhat Elsayed, Majid Bavand, Pedro Enrique Iturria Rivera, Yigit Ozcan, Melike Erol-Kantarci
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we propose an Agentic Artificial Intelligence (AI) framework for wireless networks. The framework coordinates a pool of AI agents guided by Natural Language (NL) inputs from a human operator. At its core, the super agent is powered by a Hierarchical Online Decision Transformer (H-ODT). It orchestrates three categories of agents: (i) inter-slice, intra-slice resource allocation agents, (ii) network application orchestration agents, and (iii) self-healing agents. The orchestration takes place with the help of an Agentic Retrieval-Augmented Generation (RAG) module that integrates knowledge from heterogeneous sources. In this proposed methodology, the super agent directly interfaces with operators and generates sequential policies to activate relevant agents. The proposed framework is evaluated against three state-of-the-art baselines, showing improved throughput, reduced network delay, and higher energy efficiency at both slice-level and system-wide performance metrics. Also, the proposed Agentic framework introduces a bi-level human operator intent validation methodology, both at the slice-level and Key Performance Indicator (KPI)-level using generative AI-based time series predictors. We could rule out performance-degrading operator intents with an accuracy of 88.5%. Lastly, while being interrupted by any performance-degrading events, the self-healing capability of Agentic AI in our framework automatically recovers 90% of its previous performance, avoiding quality-of-service drifts when there is no human involvement.
### Title:
          Duality Theory for Non-Markovian Linear Gaussian Models
 - **Authors:** Aditya Kudre, Heng-Sheng Chang, Prashant G. Mehta
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work develops a duality theory for partially observed linear Gaussian models in discrete time. The state process evolves according to a causal but non-Markovian (or higher-order Gauss-Markov) structure, captured by a lower-triangular transition operator, which is related to transformer, with $T$ as the context length. The main contributions are: (i) a dual control system for the linear Gaussian model, formulated as a backward difference equation (B $\Delta$ E); (ii) a duality principle establishing that a specific linear-quadratic optimal control problem for the B $\Delta$ E is dual to the filtering problem for the partially observed model; and (iii) an explicit optimal control formula yielding a novel (transformer-like) linear predictor, referred to as the dual filter, whose computational complexity scales linearly in the time horizon $T$, in contrast to the $O(T^3)$ cost of classical smoothing and Wiener-Hopf approaches.
### Title:
          Diagonal-Tiled Mixed-Precision Attention for Efficient Low-Bit MXFP Inference
 - **Authors:** Yifu Ding, Xinhao Zhang, Jinyang Guo
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer-based large language models (LLMs) have demonstrated remarkable performance across a wide range of real-world tasks, but their inference cost remains prohibitively high due to the quadratic complexity of attention and the memory bandwidth limitations of high-precision operations. In this work, we present a low-bit mixed-precision attention kernel using the microscaling floating-point (MXFP) data format, utilizing the computing capability on next-generation GPU architectures. Our Diagonal-Tiled Mixed-Precision Attention (DMA) incorporates two kinds of low-bit computation at the tiling-level, and is a delicate fused kernel implemented using Triton, exploiting hardware-level parallelism and memory efficiency to enable fast and efficient inference without compromising model performance. Extensive empirical evaluations on NVIDIA B200 GPUs show that our kernel maintains generation quality with negligible degradation, and meanwhile achieves significant speedup by kernel fusion. We release our code at this https URL.
### Title:
          VLA-Forget: Vision-Language-Action Unlearning for Embodied Foundation Models
 - **Authors:** Ravi Ranjan, Agoritsa Polyzou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language-action (VLA) models are emerging as embodied foundation models for robotic manipulation, but their deployment introduces a new unlearning challenge: removing unsafe, spurious, or privacy-sensitive behaviors without degrading perception, language grounding, and action control. In OpenVLA-style policies, behavior is produced through a fused visual encoder, a cross-modal projector, and a language backbone that predicts tokenized robot actions, so undesirable knowledge can be distributed across perception, alignment, and reasoning/action layers rather than confined to a single module. Consequently, partial unlearning applied only to the vision stack or only to the language backbone is often insufficient, while conventional unlearning baselines designed for standalone vision or language models may leave residual forgetting or incur unnecessary utility loss in embodied settings. We propose VLA-Forget, a hybrid unlearning framework that combines ratio-aware selective editing for perception and cross-modal specificity with layer-selective reasoning/action unlearning for utility-preserving forgetting. VLA-Forget jointly optimizes three objectives: targeted forgetting, perceptual preservation, and reasoning retention, through staged updates over the visual encoder, projector, and upper action-generating transformer blocks. Across forget-set behavior probes and retain-task evaluations, VLA-Forget improves forgetting efficacy by 10%, preserves perceptual specificity by 22%, retains reasoning and task success by 9%, and reduces post-quantization recovery by 55% relative to strong unlearning baselines.
### Title:
          BWTA: Accurate and Efficient Binarized Transformer by Algorithm-Hardware Co-design
 - **Authors:** Yifu Ding, Xianglong Liu, Shenghao Jin, Jinyang Guo, Jiwen Lu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ultra low-bit quantization brings substantial efficiency for Transformer-based models, but the accuracy degradation and limited GPU support hinder its wide usage. In this paper, we analyze zero-point distortion in binarization and propose a Binary Weights & Ternary Activations (BWTA) quantization scheme, which projects tiny values to zero and preserves the accuracy of extremely low-bit models. For training, we propose Smooth Multi-Stage Quantization, combining a Levelwise Degradation Strategy and a Magnitude-Alignment Projection Factor to enable stable and fast convergence. For inference, we develop a BWTA MatMul CUDA kernel with instruction-level parallel bit-packing and comprehensive binary/ternary MatMul implementations for both linear and attention operators, allowing seamless integration across Transformer architectures. Experiments show that BWTA approaches full-precision performance for BERT, with an average 3.5% drop on GLUE and less than 2% drop on five tasks, and achieves comparable perplexity and accuracy for LLMs. In efficiency, it delivers 16 to 24 times kernel-level speedup over FP16 on NVIDIA GPUs, and 216 to 330 tokens/s end-to-end prefill speedup with lower memory footprint on LLMs. As an algorithm-hardware co-design, BWTA demonstrates practical, low-latency ultra-low-bit inference without sacrificing model quality.
### Title:
          Automated Expected Cost Analysis for Quantum Programs
 - **Authors:** Georg Moser, Michael Schaper
 - **Subjects:** Subjects:
Programming Languages (cs.PL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In recent years, quantum computing has gained a substantial amount of momentum, and the capabilities of quantum devices are continually expanding and improving. Nevertheless, writing a quantum program from scratch remains tedious and error-prone work, showcasing the clear demand for automated tool support. We present Qet, a fully automated static program analysis tool that yields a precise expected cost analysis of mixed classical-quantum programs. Qet supports programs with advanced features like mid-circuit measurements and classical control flow. The methodology of our prototype implementation is based on a recently proposed quantum expectation transformer framework, generalising Dijkstra's predicate transformer and Hoare logic. The prototype implementation Qet is evaluated on a number of case studies taken from the literature and online references. Qet is able to fully automatically infer precise upper bounds on the expected costs that previously could only be derived by tedious manual calculations.
### Title:
          High-Fidelity Mural Restoration via a Unified Hybrid Mask-Aware Transformer
 - **Authors:** Jincheng Jiang, Qianhao Han, Chi Zhang, Zheng Zheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ancient murals are valuable cultural artifacts, but many have suffered severe degradation due to environmental exposure, material aging, and human activity. Restoring these artworks is challenging because it requires both reconstructing large missing structures and strictly preserving authentic, undamaged regions. This paper presents the Hybrid Mask-Aware Transformer (HMAT), a unified framework for high-fidelity mural restoration. HMAT integrates Mask-Aware Dynamic Filtering for robust local texture modeling with a Transformer bottleneck for long-range structural inference. To further address the diverse morphology of degradation, we introduce a mask-conditional style fusion module that dynamically guides the generative process. In addition, a Teacher-Forcing Decoder with hard-gated skip connections is designed to enforce fidelity in valid regions and focus reconstruction on missing areas. We evaluate HMAT on the DHMural dataset and a curated Nine-Colored Deer dataset under varying degradation levels. Experimental results demonstrate that the proposed method achieves competitive performance compared to state-of-the-art approaches, while producing more structurally coherent and visually faithful restorations. These findings suggest that HMAT provides an effective solution for the digital restoration of cultural heritage murals.
### Title:
          RUQuant: Towards Refining Uniform Quantization for Large Language Models
 - **Authors:** Han Liu, Haotian Gao, Changya Li, Feng Zhang, Xiaotong Zhang, Wei Wang, Hong Yu
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The increasing size and complexity of large language models (LLMs) have raised significant challenges in deployment efficiency, particularly under resource constraints. Post-training quantization (PTQ) has emerged as a practical solution by compressing models without requiring retraining. While existing methods focus on uniform quantization schemes for both weights and activations, they often suffer from substantial accuracy degradation due to the non-uniform nature of activation distributions. In this work, we revisit the activation quantization problem from a theoretical perspective grounded in the Lloyd-Max optimality conditions. We identify the core issue as the non-uniform distribution of activations within the quantization interval, which causes the optimal quantization point under the Lloyd-Max criterion to shift away from the midpoint of the interval. To address this issue, we propose a two-stage orthogonal transformation method, RUQuant. In the first stage, activations are divided into blocks. Each block is mapped to uniformly sampled target vectors using composite orthogonal matrices, which are constructed from Householder reflections and Givens rotations. In the second stage, a global Householder reflection is fine-tuned to further minimize quantization error using Transformer output discrepancies. Empirical results show that our method achieves near-optimal quantization performance without requiring model fine-tuning: RUQuant achieves 99.8% of full-precision accuracy with W6A6 and 97% with W4A4 quantization for a 13B LLM, within approximately one minute. A fine-tuned variant yields even higher accuracy, demonstrating the effectiveness and scalability of our approach.
### Title:
          Unmasking Hallucinations: A Causal Graph-Attention Perspective on Factual Reliability in Large Language Models
 - **Authors:** Sailesh kiran kurra, Shiek Ruksana, Vishal Borusu
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper primarily focuses on the hallucinations caused due to AI language models(LLMs).LLMs have shown extraordinary Language understanding and generation capabilities .Still it has major a disadvantage hallucinations which give outputs which are factually incorrect ,misleading or unsupported by input data . These hallucinations cause serious problems in scenarios like medical diagnosis or legal this http URL this work,we propose causal graph attention network (GCAN) framework that reduces hallucinations through interpretation of internal attention flow within a transformer architecture with the help of constructing token level graphs that combine self attention weights and gradient based influence this http URL method quantifies each tokens factual dependency using a new metric called the Causal Contribution Score (CCS). We further introduce a fact-anchored graph reweighting layer that dynamically reduces the influence of hallucination prone nodes during generation. Experiments on standard benchmarks such as TruthfulQA and HotpotQA show a 27.8 percent reduction in hallucination rate and 16.4 percent improvement in factual accuracy over baseline retrieval-augmented generation (RAG) models. This work contributes to the interpretability,robustness, and factual reliability of future LLM architectures.
### Title:
          ATSS: Detecting AI-Generated Videos via Anomalous Temporal Self-Similarity
 - **Authors:** Hang Wang, Chao Shen, Lei Zhang, Zhi-Qi Cheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 AI-generated videos (AIGVs) have achieved unprecedented photorealism, posing severe threats to digital forensics. Existing AIGV detectors focus mainly on localized artifacts or short-term temporal inconsistencies, thus often fail to capture the underlying generative logic governing global temporal evolution, limiting AIGV detection performance. In this paper, we identify a distinctive fingerprint in AIGVs, termed anomalous temporal self-similarity (ATSS). Unlike real videos that exhibit stochastic natural dynamics, AIGVs follow deterministic anchor-driven trajectories (e.g., text or image prompts), inducing unnaturally repetitive correlations across visual and semantic domains. To exploit this, we propose the ATSS method, a multimodal detection framework that exploits this insight via a triple-similarity representation and a cross-attentive fusion mechanism. Specifically, ATSS reconstructs semantic trajectories by leveraging frame-wise descriptions to construct visual, textual, and cross-modal similarity matrices, which jointly quantify the inherent temporal anomalies. These matrices are encoded by dedicated Transformer encoders and integrated via a bidirectional cross-attentive fusion module to effectively model intra- and inter-modal dynamics. Extensive experiments on four large-scale benchmarks, including GenVideo, EvalCrafter, VideoPhy, and VidProM, demonstrate that ATSS significantly outperforms state-of-the-art methods in terms of AP, AUC, and ACC metrics, exhibiting superior generalization across diverse video generation models. Code and models of ATSS will be released at this https URL.
### Title:
          TORA: Topological Representation Alignment for 3D Shape Assembly
 - **Authors:** Nahyuk Lee, Zhiang Chen, Marc Pollefeys, Sunghwan Hong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Flow-matching methods for 3D shape assembly learn point-wise velocity fields that transport parts toward assembled configurations, yet they receive no explicit guidance about which cross-part interactions should drive the motion. We introduce TORA, a topology-first representation alignment framework that distills relational structure from a frozen pretrained 3D encoder into the flow-matching backbone during training. We first realize this via simple instantiation, token-wise cosine matching, which injects the learned geometric descriptors from the teacher representation. We then extend to employ a Centered Kernel Alignment (CKA) loss to match the similarity structure between student and teacher representations for enhanced topological alignment. Through systematic probing of diverse 3D encoders, we show that geometry- and contact-centric teacher properties, not semantic classification ability, govern alignment effectiveness, and that alignment is most beneficial at later transformer layers where spatial structure naturally emerges. TORA introduces zero inference overhead while yielding two consistent benefits: faster convergence (up to 6.9$\times$) and improved accuracy in-distribution, along with greater robustness under domain shift. Experiments on five benchmarks spanning geometric, semantic, and inter-object assembly demonstrate state-of-the-art performance, with particularly pronounced gains in zero-shot transfer to unseen real-world and synthetic datasets. Project page: this https URL.
### Title:
          Extracting and Steering Emotion Representations in Small Language Models: A Methodological Comparison
 - **Authors:** Jihoon Jeong
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Small language models (SLMs) in the 100M-10B parameter range increasingly power production systems, yet whether they possess the internal emotion representations recently discovered in frontier models remains unknown. We present the first comparative analysis of emotion vector extraction methods for SLMs, evaluating 9 models across 5 architectural families (GPT-2, Gemma, Qwen, Llama, Mistral) using 20 emotions and two extraction methods (generation-based and comprehension-based). Generation-based extraction produces statistically superior emotion separation (Mann-Whitney p = 0.007; Cohen's d = -107.5), with the advantage modulated by instruction tuning and architecture. Emotion representations localize at middle transformer layers (~50% depth), following a U-shaped curve that is architecture-invariant from 124M to 3B parameters. We validate these findings against representational anisotropy baselines across 4 models and confirm causal behavioral effects through steering experiments, independently verified by an external emotion classifier (92% success rate, 37/40 scenarios). Steering reveals three regimes -- surgical (coherent text transformation), repetitive collapse, and explosive (text degradation) -- quantified by perplexity ratios and separated by model architecture rather than scale. We document cross-lingual emotion entanglement in Qwen, where steering activates semantically aligned Chinese tokens that RLHF does not suppress, raising safety concerns for multilingual deployment. This work provides methodological guidelines for emotion research on open-weight models and contributes to the Model Medicine series by bridging external behavioral profiling with internal representational analysis.
### Title:
          LAA-X: Unified Localized Artifact Attention for Quality-Agnostic and Generalizable Face Forgery Detection
 - **Authors:** Dat Nguyen, Enjie Ghorbel, Anis Kacem, Marcella Astrid, Djamila Aouada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper, we propose Localized Artifact Attention X (LAA-X), a novel deepfake detection framework that is both robust to high-quality forgeries and capable of generalizing to unseen manipulations. Existing approaches typically rely on binary classifiers coupled with implicit attention mechanisms, which often fail to generalize beyond known manipulations. In contrast, LAA-X introduces an explicit attention strategy based on a multi-task learning framework combined with blending-based data synthesis. Auxiliary tasks are designed to guide the model toward localized, artifact-prone (i.e., vulnerable) regions. The proposed framework is compatible with both CNN and transformer backbones, resulting in two different versions, namely, LAA-Net and LAA-Former, respectively. Despite being trained only on real and pseudo-fake samples, LAA-X competes with state-of-the-art methods across multiple benchmarks. Code and pre-trained weights for LAA-Net\footnote{this https URL} and LAA-Former\footnote{this https URL} are publicly available.
### Title:
          InsTraj: Instructing Diffusion Models with Travel Intentions to Generate Real-world Trajectories
 - **Authors:** Yuanshao Zhu, Yuxuan Liang, Xiangyu Zhao, Liang Han, Xinwei Fang, Xuetao Wei, James Jianqiao Yu
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The generation of realistic and controllable GPS trajectories is a fundamental task for applications in urban planning, mobility simulation, and privacy-preserving data sharing. However, existing methods face a two-fold challenge: they lack the deep semantic understanding to interpret complex user travel intent, and struggle to handle complex constraints while maintaining the realistic diversity inherent in human behavior. To resolve this, we introduce InsTraj, a novel framework that instructs diffusion models to generate high-fidelity trajectories directly from natural language descriptions. Specifically, InsTraj first utilizes a powerful large language model to decipher unstructured travel intentions formed in natural language, thereby creating rich semantic blueprints and bridging the representation gap between intentions and trajectories. Subsequently, we proposed a multimodal trajectory diffusion transformer that can integrate semantic guidance to generate high-fidelity and instruction-faithful trajectories that adhere to fine-grained user intent. Comprehensive experiments on real-world datasets demonstrate that InsTraj significantly outperforms state-of-the-art methods in generating trajectories that are realistic, diverse, and semantically faithful to the input instructions.
### Title:
          SARES-DEIM: Sparse Mixture-of-Experts Meets DETR for Robust SAR Ship Detection
 - **Authors:** Fenghao Song, Shaojing Yang, Xi Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ship detection in Synthetic Aperture Radar (SAR) imagery is fundamentally challenged by inherent coherent speckle noise, complex coastal clutter, and the prevalence of small-scale targets. Conventional detectors, primarily designed for optical imagery, often exhibit limited robustness against SAR-specific degradation and suffer from the loss of fine-grained ship signatures during spatial downsampling. To address these limitations, we propose SARES-DEIM, a domain-aware detection framework grounded in the DEtection TRansformer (DETR) paradigm. Central to our approach is SARESMoE (SAR-aware Expert Selection Mixture-of-Experts), a module leveraging a sparse gating mechanism to selectively route features toward specialized frequency and wavelet experts. This sparsely-activated architecture effectively filters speckle noise and semantic clutter while maintaining high computational efficiency. Furthermore, we introduce the Space-to-Depth Enhancement Pyramid (SDEP) neck to preserve high-resolution spatial cues from shallow stages, significantly improving the localization of small targets. Extensive experiments on two benchmark datasets demonstrate the superiority of SARES-DEIM. Notably, on the challenging HRSID dataset, our model achieves a mAP50:95 of 76.4% and a mAP50 of 93.8%, outperforming state-of-the-art YOLO-series and specialized SAR detectors.
### Title:
          Measuring Robustness of Speech Recognition from MEG Signals Under Distribution Shift
 - **Authors:** Sheng-You Chien, Bo-Yi Mao, Yi-Ning Chang, Po-Chih Kuo
 - **Subjects:** Subjects:
Sound (cs.SD); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study investigates robust speech-related decoding from non-invasive MEG signals using the LibriBrain phoneme-classification benchmark from the 2025 PNPL competition. We compare residual convolutional neural networks (CNNs), an STFT-based CNN, and a CNN--Transformer hybrid, while also examining the effects of group averaging, label balancing, repeated grouping, normalization strategies, and data augmentation. Across our in-house implementations, preprocessing and data-configuration choices matter more than additional architectural complexity, among which instance normalization emerges as the most influential modification for generalization. The strongest of our own models, a CNN with group averaging, label balancing, repeated grouping, and instance normalization, achieves 60.95% F1-macro on the test split, compared with 39.53% for the plain CNN baseline. However, most of our models, without instance normalization, show substantial validation-to-test degradation, indicating that distribution shift induced by different normalization statistics is a major obstacle to generalization in our experiments. By contrast, MEGConformer maintains 64.09% F1-macro on both validation and test, and saliency-map analysis is qualitatively consistent with this contrast: weaker models exhibit more concentrated or repetitive phoneme-sensitive patterns across splits, whereas MEGConformer appears more distributed. Overall, the results suggest that improving the reliability of non-invasive phoneme decoding will likely require better handling of normalization-related distribution shift while also addressing the challenge of single-trial decoding.
### Title:
          Scale-Aware Vision-Language Adaptation for Extreme Far-Distance Video Person Re-identification
 - **Authors:** Ashwat Rajbhandari, Bharatesh Chakravarthi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Extreme far-distance video person re-identification (ReID) is particularly challenging due to scale compression, resolution degradation, motion blur, and aerial-ground viewpoint mismatch. As camera altitude and subject distance increase, models trained on close-range imagery degrade significantly. In this work, we investigate how large-scale vision-language models can be adapted to operate reliably under these conditions. Starting from a CLIP-based baseline, we upgrade the visual backbone from ViT-B/16 to ViT-L/14 and introduce backbone-aware selective fine-tuning to stabilize adaptation of the larger transformer. To address noisy and low-resolution tracklets, we incorporate a lightweight temporal attention pooling mechanism that suppresses degraded frames and emphasizes informative observations. We retain adapter-based and prompt-conditioned cross-view learning to mitigate aerial-ground domain shifts, and further refine retrieval using improved optimization and k-reciprocal re-ranking. Experiments on the DetReIDX stress-test benchmark show that our approach achieves mAP scores of 46.69 (A2G), 41.23 (G2A), and 22.98 (A2A), corresponding to an overall mAP of 35.73. These results show that large-scale vision-language backbones, when combined with stability-focused adaptation, significantly enhance robustness in extreme far-distance video person ReID.
### Title:
          CAWN: Continuous Acoustic Wave Networks for Autoregressive Language Modeling
 - **Authors:** Dejan Čugalj, Aleksandar Jevremovic
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Modern Large Language Models (LLMs) rely on Transformer self-attention, which scales quadratically with sequence length. Recent linear-time alternatives, like State Space Models (SSMs), often suffer from signal degradation over extended contexts. We introduce the Continuous Acoustic Wave Network (CAWN), a fully continuous sequence-mixing architecture. Instead of discrete matrix-based attention, CAWN projects hidden states into multi-headed complex-domain phasors, achieving sequence mixing through a causal, $O(L)$ Phase Accumulation mechanism. To prevent signal degradation over ultra-long contexts, we introduce a dual-gated Selective Phase Resonance mechanism incorporating Frequency-Dependent Retention, Hard-Threshold Gating via Straight-Through Estimation, and a Temporal Syntax Cache to capture short-term local dependencies. We also replace standard dense linear projections with Depth-wise Harmonic Convolutions for optimal spatial frequency mixing, augmented by Block Attention Residuals for depth-wise state routing. Scaled to a 150M-parameter model, CAWN utilizes custom Triton kernels for hardware-efficient, true-complex phase accumulation in float32. Trained via a continuous streaming loop on a 100-Billion-token corpus, the prototype is evaluated at a 5-Billion-token milestone. Empirical evaluations via a Targeted Semantic Retrieval protocol demonstrate robust vocabulary acquisition and extended explicitly learned contextual denoising. By leveraging $O(1)$ state-passing via chunked prefill, the model retrieves targeted information across 2,000,000 tokens while strictly plateauing at 8.72 GB of Peak VRAM, empirically overcoming the $O(L^2)$ context memory wall.
### Title:
          Agents for Agents: An Interrogator-Based Secure Framework for Autonomous Internet of Underwater Things
 - **Authors:** Ali Akarma, Toqeer Ali Syed, Abdul Khadar Jilani, Salman Jan, Hammad Muneer, Muazzam A. Khan, Changli Yu
 - **Subjects:** Subjects:
Multiagent Systems (cs.MA); Artificial Intelligence (cs.AI); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous underwater vehicles (AUVs) and sensor nodes increasingly support decentralized sensing and coordination in the Internet of Underwater Things (IoUT), yet most deployments rely on static trust once authentication is established, leaving long-duration missions vulnerable to compromised or behaviorally deviating agents. In this paper, an interrogator based structure is presented that incorporates the idea of behavioral trust monitoring into underwater multi-agent operation without interfering with autonomy. Privileged interrogator module is a passive communication metadata analyzer that uses a lightweight transformer model to calculate dynamic trust scores, which are used to authorize the forwarding of mission critical data. Suspicious agents cause proportional monitoring and conditional restrictions, which allow fast containment and maintain network continuity. The evidence of trust is stored in a permissioned blockchain consortium which offers identity management which is not tampered and is decentralized without causing the overhead of public consensus mechanisms. Simulation based analysis shows that the evaluation of the result compares to a relative improvement of 21.7% in the detection accuracy compared to the static trust baselines with limited energy overhead. These findings suggest that behavior driven validation has the capability of reinforcing underwater coordination without compromising scalability and deployment.
### Title:
          A Persistent Homology Design Space for 3D Point Cloud Deep Learning
 - **Authors:** Prachi Kudeshia, Jiju Poovvancheri, Amr Ghoneim, Dong Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Persistent Homology (PH) offers stable, multi-scale descriptors of intrinsic shape structure by capturing connected components, loops, and voids that persist across scales, providing invariants that complement purely geometric representations of 3D data. Yet, despite strong theoretical guarantees and increasing empirical adoption, its integration into deep learning for point clouds remains largely ad hoc and architecturally peripheral. In this work, we introduce a unified design space for Persistent-Homology driven learning in 3D point clouds (3DPHDL), formalizing the interplay between complex construction, filtration strategy, persistence representation, neural backbone, and prediction task. Beyond the canonical pipeline of diagram computation and vectorization, we identify six principled injection points through which topology can act as a structural inductive bias reshaping sampling, neighborhood graphs, optimization dynamics, self-supervision, output calibration, and even internal network regularization. We instantiate this framework through a controlled empirical study on ModelNet40 classification and ShapeNetPart segmentation, systematically augmenting representative backbones (PointNet, DGCNN, and Point Transformer) with persistence diagrams, images, and landscapes, and analyzing their impact on accuracy, robustness to noise and sampling variation, and computational scalability. Our results demonstrate consistent improvements in topology-sensitive discrimination and part consistency, while revealing meaningful trade-offs between representational expressiveness and combinatorial complexity. By viewing persistent homology not merely as an auxiliary feature but as a structured component within the learning pipeline, this work provides a systematic framework for incorporating topological reasoning into 3D point cloud learning.
### Title:
          HighFM: Towards a Foundation Model for Learning Representations from High-Frequency Earth Observation Data
 - **Authors:** Stella Girtsou, Konstantinos Alexis, Giorgos Giannopoulos, Harris Kontoes
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The increasing frequency and severity of climate related disasters have intensified the need for real time monitoring, early warning, and informed decision-making. Earth Observation (EO), powered by satellite data and Machine Learning (ML), offers powerful tools to meet these challenges. Foundation Models (FMs) have revolutionized EO ML by enabling general-purpose pretraining on large scale remote sensing datasets. However most existing models rely on high-resolution satellite imagery with low revisit rates limiting their suitability for fast-evolving phenomena and time critical emergency response. In this work, we present HighFM, a first cut approach towards a FM for high temporal resolution, multispectral EO data. Leveraging over 2 TB of SEVIRI imagery from the Meteosat Second Generation (MSG) platform, we adapt the SatMAE masked autoencoding framework to learn robust spatiotemporal representations. To support real time monitoring, we enhance the original architecture with fine grained temporal encodings to capture short term variability. The pretrained models are then finetuned on cloud masking and active fire detection tasks. We benchmark our SEVIRI pretrained Vision Transformers against traditional baselines and recent geospatial FMs, demonstrating consistent gains across both balanced accuracy and IoU metrics. Our results highlight the potential of temporally dense geostationary data for real-time EO, offering a scalable path toward foundation models for disaster detection and tracking.
### Title:
          Light-Bound Transformers: Hardware-Anchored Robustness for Silicon-Photonic Computer Vision Systems
 - **Authors:** Xuming Chen, Deniz Najafi, Chengwei Zhou, Pietro Mercati, Arman Roohi, Mohsen Imani, Mahdi Nikdast, Shaahin Angizi, Gourav Datta
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deploying Vision Transformers (ViTs) on near-sensor analog accelerators demands training pipelines that are explicitly aligned with device-level noise and energy constraints. We introduce a compact framework for silicon-photonic execution of ViTs that integrates measured hardware noise, robust attention training, and an energy-aware processing flow. We first characterize bank-level noise in microring-resonator (MR) arrays, including fabrication variation, thermal drift, and amplitude noise, and convert these measurements into closed-form, activation-dependent variance proxies for attention logits and feed-forward activations. Using these proxies, we develop Chance-Constrained Training (CCT), which enforces variance-normalized logit margins to bound attention rank flips, and a noise-aware LayerNorm that stabilizes feature statistics without changing the optical schedule. These components yield a practical ``measure $\rightarrow$ model $\rightarrow$ train $\rightarrow$ run'' pipeline that optimizes accuracy under noise while respecting system energy limits. Hardware-in-the-loop experiments with MR photonic banks show that our approach restores near-clean accuracy under realistic noise budgets, with no in-situ learning or additional optical MACs.
### Title:
          CPT: Controllable and Editable Design Variations with Language Models
 - **Authors:** Karthik Suresh, Amine Ben Khalifa, Li Zhang, Wei-ting Hsu, Fangzheng Wu, Vinay More, Asim Kadav
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Designing visually diverse and high-quality designs remains a manual, time-consuming process, limiting scalability and personalization in creative workflows. We present a system for generating editable design variations using a decoder-only language model, the Creative Pre-trained Transformer (CPT), trained to predict visual style attributes in design templates. At the core of our approach is a new representation called Creative Markup Language (CML), a compact, machine-learning-friendly format that captures canvas-level structure, page layout, and element-level details (text, images, and vector graphics), including both content and style. We fine-tune CPT on a large corpus of design templates authored by professional designers, enabling it to learn meaningful, context-aware predictions for attributes such as color schemes and font choices. The model produces semantically structured and stylistically coherent outputs, preserving internal consistency across elements. Unlike generative image models, our system yields fully editable design documents rather than pixel-only images, allowing users to iterate and personalize within a design editor. In experiments, our approach generates contextual color and font variations for existing templates and shows promise in adjusting layouts while maintaining design principles.
### Title:
          Compressible Softmax-Attended Language under Incompressible Attention
 - **Authors:** Wonsuk Lee
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Across every attention head in five transformer language models (124M--7B parameters, four architecture families), the logit energy field $\tilde{E}$ reaches 90\% of its variance in 2--11 singular components. The \emph{learned} interaction matrix $W_Q^\mathrm{T} W_K$ needs 38--75 components for the same threshold out of $d_h \in \{64, 128\}$. The spectral gap is $5$--$25\times$ in effective rank. The attention mechanism allocates capacity uniformly across all $d_h$ dimensions, but language concentrates the actual interaction into a few. The compressibility of softmax-attended language is a property of the data, not the frame that analyzes it.
### Title:
          BiTDiff: Fine-Grained 3D Conducting Motion Generation via BiMamba-Transformer Diffusion
 - **Authors:** Tianzhi Jia, Kaixing Yang, Xiaole Yang, Xulong Tang, Ke Qiu, Shikui Wei, Yao Zhao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 3D conducting motion generation aims to synthesize fine-grained conductor motions from music, with broad potential in music education, virtual performance, digital human animation, and human-AI co-creation. However, this task remains underexplored due to two major challenges: (1) the lack of large-scale fine-grained 3D conducting datasets and (2) the absence of effective methods that can jointly support long-sequence generation with high quality and efficiency. To address the data limitation, we develop a quality-oriented 3D conducting motion collection pipeline and construct CM-Data, a fine-grained SMPL-X dataset with about 10 hours of conducting motion data. To the best of our knowledge, CM-Data is the first and largest public dataset for 3D conducting motion generation. To address the methodological limitation, we propose BiTDiff, a novel framework for 3D conducting motion generation, built upon a BiMamba-Transformer hybrid model architecture for efficient long-sequence modeling and a Diffusion-based generative strategy with human-kinematic decomposition for high-quality motion synthesis. Specifically, BiTDiff introduces auxiliary physical-consistency losses and a hand-/body-specific forward-kinematics design for better fine-grained motion modeling, while leveraging BiMamba for memory-efficient long-sequence temporal modeling and Transformer for cross-modal semantic alignment. In addition, BiTDiff supports training-free joint-level motion editing, enabling downstream human-AI interaction design. Extensive quantitative and qualitative experiments demonstrate that BiTDiff achieves state-of-the-art (SOTA) performance for 3D conducting motion generation on the CM-Data dataset. Code will be available upon acceptance.
### Title:
          Training Transformers in Cosine Coefficient Space
 - **Authors:** Mohamed Amine Bergach
 - **Subjects:** Subjects:
Performance (cs.PF); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We parameterize the weight matrices of a transformer in the two-dimensional discrete cosine transform (DCT) domain, retaining only the lowest-frequency coefficients. At each forward pass the full weight matrix is reconstructed via the inverse DCT; gradients propagate through the reconstruction to update the spectral coefficients directly. On character-level language modeling (Shakespeare, 1M characters), a 4-layer transformer trained from scratch in this representation matches the perplexity of the standard parameterization (6.1 vs.\ 6.1) while storing 52\% of the parameters. At 4$\times$ compression (29\% of parameters), the model reaches perplexity 6.9 -- outperforming a low-rank baseline (perplexity 8.8 at 21\% of parameters) at a comparable reduction. The method requires no architectural changes, no pre-trained checkpoint, and no auxiliary loss. It reduces to replacing each \texttt{this http URL} with a drop-in spectral layer that stores $K$ DCT coefficients instead of $n \times m$ weights.
### Title:
          Beyond Few-Step Inference: Accelerating Video Diffusion Transformer Model Serving with Inter-Request Caching Reuse
 - **Authors:** Hao Liu, Ye Huang, Chenghuan Huang, Zhenyi Zheng, Jiangsu Du, Ziyang Ma, Jing Lyu, Yutong Lu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video Diffusion Transformer (DiT) models are a dominant approach for high-quality video generation but suffer from high inference cost due to iterative denoising. Existing caching approaches primarily exploit similarity within the diffusion process of a single request to skip redundant denoising steps. In this paper, we introduce Chorus, a caching approach that leverages similarity across requests to accelerate video diffusion model serving. Chorus achieves up to 45\% speedup on industrial 4-step distilled models, where prior intra-request caching approaches are ineffective. Particularly, Chorus employs a three-stage caching strategy along the denoising process. Stage 1 performs full reuse of latent features from similar requests. Stage 2 exploits inter-request caching in specific latent regions during intermediate denoising steps. This stage is combined with Token-Guided Attention Amplification to improve semantic alignment between the generated video and the conditional prompts, thereby extending the applicability of full reuse to later denoising steps.
### Title:
          Same Geometry, Opposite Noise: Transformer Magnitude Representations Lack Scalar Variability
 - **Authors:** Jon-Paul Cacioli
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Quantitative Methods (q-bio.QM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scalar variability -- the finding that representational noise scales proportionally with magnitude, producing a constant coefficient of variation -- is a hallmark of biological magnitude systems. We tested whether transformer language models exhibit this property by analysing the dispersion of hidden-state representations across carrier sentences for 26 numerical magnitudes in three 7-8B parameter models (Llama-3-8B-Instruct, Mistral-7B-Instruct-v0.3, Llama-3-8B-Base; data from Cacioli, 2026). We found the opposite: representational variability decreased with magnitude along the magnitude axis (scaling exponent alpha approx -0.19; 0/16 primary layers with alpha > 0, all three models). The negative sign was consistent in full-dimensional space (alpha approx -0.04) and after sentence-identity correction (alpha approx -0.007). The anti-scalar pattern was 3-5x stronger along the magnitude axis than orthogonal dimensions, and corpus frequency strongly predicted per-magnitude variability (rho = .84). These results demonstrate that distributional learning alone is insufficient to produce scalar variability: transformers reproduce log-compressive magnitude geometry but not the constant-CV noise signature observed in biological systems.
### Title:
          MPTF-Net: Multi-view Pyramid Transformer Fusion Network for LiDAR-based Place Recognition
 - **Authors:** Shuyuan Li, Zihang Wang, Xieyuanli Chen, Wenkai Zhu, Xiaoteng Fang, Peizhou Ni, Junhao Yang, Dong Kong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 LiDAR-based place recognition (LPR) is essential for global localization and loop-closure detection in large-scale SLAM systems. Existing methods typically construct global descriptors from Range Images or BEV representations for matching. BEV is widely adopted due to its explicit 2D spatial layout encoding and efficient retrieval. However, conventional BEV representations rely on simple statistical aggregation, which fails to capture fine-grained geometric structures, leading to performance degradation in complex or repetitive environments. To address this, we propose MPTF-Net, a novel multi-view multi-scale pyramid Transformer fusion network. Our core contribution is a multi-channel NDT-based BEV encoding that explicitly models local geometric complexity and intensity distributions via Normal Distribution Transform, providing a noise-resilient structural prior. To effectively integrate these features, we develop a customized pyramid Transformer module that captures cross-view interactive correlations between Range Image Views (RIV) and NDT-BEV at multiple spatial scales. Extensive experiments on the nuScenes, KITTI and NCLT datasets demonstrate that MPTF-Net achieves state-of-the-art performance, specifically attaining a Recall@1 of 96.31\% on the nuScenes Boston split while maintaining an inference latency of only 10.02 ms, making it highly suitable for real-time autonomous unmanned systems.
### Title:
          Firebolt-VL: Efficient Vision-Language Understanding with Cross-Modality Modulation
 - **Authors:** Quoc-Huy Trinh, Mustapha Abdullahi, Bo Zhao, Debesh Jha
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent advances in multimodal large language models (MLLMs) have enabled impressive progress in vision-language understanding, yet their high computational cost limits deployment in resource-constrained scenarios such as personal assistants, document understanding, and smart cameras. Most existing methods rely on Transformer-based cross-attention, whose quadratic complexity hinders efficiency. Moreover, small vision-language models often struggle to precisely capture fine-grained, task-relevant visual regions, leading to degraded performance on fine-grained reasoning tasks that limit their effectiveness in the real world. To address these issues, we introduce Firebolt-VL, an efficient vision-language model that replaces the Transformer-based decoder with a Liquid Foundation Model (LFM) decoder. To further enhance visual grounding, we propose a Token-Grid Correlation Module, which computes lightweight correlations between text tokens and image patches and modulates via the state-space model with FiLM conditioning. This enables the model to selectively emphasize visual regions relevant to the textual prompt while maintaining linear-time inference. Experimental results across multiple benchmarks demonstrate that Firebolt-VL achieves accurate, fine-grained understanding with significantly improved efficiency. Our model and code are available at: this https URL
### Title:
          Greedy and Transformer-Based Multi-Port Selection for Slow Fluid Antenna Multiple Access
 - **Authors:** Darian Perez-Adan, Jose P. Gonzalez-Coma, F. Javier Lopez-Martinez, Luis Castedo
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We address the port-selection problem in fluid antenna multiple access (FAMA) systems with multi-port fluid antenna (FA) receivers. Existing methods either achieve near-optimal spectral efficiency (SE) at prohibitive computational cost or sacrifice significant performance for lower complexity. We propose two complementary strategies: (i) GFwd+S, a greedy forward-selection method with swap refinement that consistently outperforms state-of-the-art reference schemes in terms of SE, and (ii) a Transformer-based neural network trained via imitation learning followed by a Reinforce policy-gradient stage, which approaches GFwd+S performance at lower computational cost.
### Title:
          Preserving Forgery Artifacts: AI-Generated Video Detection at Native Scale
 - **Authors:** Zhengcen Li, Chenyang Jiang, Hang Zhao, Shiyang Zhou, Yunyang Mo, Feng Gao, Fan Yang, Qiben Shan, Shaocong Wu, Jingyong Su
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The rapid advancement of video generation models has enabled the creation of highly realistic synthetic media, raising significant societal concerns regarding the spread of misinformation. However, current detection methods suffer from critical limitations. They rely on preprocessing operations like fixed-resolution resizing and cropping. These operations not only discard subtle, high-frequency forgery traces but also cause spatial distortion and significant information loss. Furthermore, existing methods are often trained and evaluated on outdated datasets that fail to capture the sophistication of modern generative models. To address these challenges, we introduce a comprehensive dataset and a novel detection framework. First, we curate a large-scale dataset of over 140K videos from 15 state-of-the-art open-source and commercial generators, along with Magic Videos benchmark designed specifically for evaluating ultra-realistic synthetic content. In addition, we propose a novel detection framework built on the Qwen2.5-VL Vision Transformer, which operates natively at variable spatial resolutions and temporal durations. This native-scale approach effectively preserves the high-frequency artifacts and spatiotemporal inconsistencies typically lost during conventional preprocessing. Extensive experiments demonstrate that our method achieves superior performance across multiple benchmarks, underscoring the critical importance of native-scale processing and establishing a robust new baseline for AI-generated video detection.
### Title:
          Synthesis4AD: Synthetic Anomalies are All You Need for 3D Anomaly Detection
 - **Authors:** Yihan Sun, Yuqi Cheng, Junjie Zu, Yuxiang Tan, Guoyang Xie, Yucheng Wang, Yunkang Cao, Weiming Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Industrial 3D anomaly detection performance is fundamentally constrained by the scarcity and long-tailed distribution of abnormal samples. To address this challenge, we propose Synthesis4AD, an end-to-end paradigm that leverages large-scale, high-fidelity synthetic anomalies to learn more discriminative representations for 3D anomaly detection. At the core of Synthesis4AD is 3D-DefectStudio, a software platform built upon the controllable synthesis engine MPAS, which injects geometrically realistic defects guided by higher-dimensional support primitives while simultaneously generating accurate point-wise anomaly masks. Furthermore, Synthesis4AD incorporates a multimodal large language model (MLLM) to interpret product design information and automatically translate it into executable anomaly synthesis instructions, enabling scalable and knowledge-driven anomalous data generation. To improve the robustness and generalization of the downstream detector on unstructured point clouds, Synthesis4AD further introduces a training pipeline based on spatial-distribution normalization and geometry-faithful data augmentations, which alleviates the sensitivity of Point Transformer architectures to absolute coordinates and improves feature learning under realistic data variations. Extensive experiments demonstrate state-of-the-art performance on Real3D-AD, MulSen-AD, and a real-world industrial parts dataset. The proposed synthesis method MPAS and the interactive system 3D-DefectStudio will be publicly released at this https URL.
### Title:
          ZeD-MAP: Bundle Adjustment Guided Zero-Shot Depth Maps for Real-Time Aerial Imaging
 - **Authors:** Selim Ahmet Iz, Francesco Nex, Norman Kerle, Henry Meissner, Ralf Berger
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Real-time depth reconstruction from ultra-high-resolution UAV imagery is essential for time-critical geospatial tasks such as disaster response, yet remains challenging due to wide-baseline parallax, large image sizes, low-texture or specular surfaces, occlusions, and strict computational constraints. Recent zero-shot diffusion models offer fast per-image dense predictions without task-specific retraining, and require fewer labelled datasets than transformer-based predictors while avoiding the rigid capture geometry requirement of classical multi-view stereo. However, their probabilistic inference prevents reliable metric accuracy and temporal consistency across sequential frames and overlapping tiles. We present ZeD-MAP, a cluster-level framework that converts a test-time diffusion depth model into a metrically consistent, SLAM-like mapping pipeline by integrating incremental cluster-based bundle adjustment (BA). Streamed UAV frames are grouped into overlapping clusters; periodic BA produces metrically consistent poses and sparse 3D tie-points, which are reprojected into selected frames and used as metric guidance for diffusion-based depth estimation. Validation on ground-marker flights captured at approximately 50 m altitude (GSD is approximately 0.85 cm/px, corresponding to 2,650 square meters ground coverage per frame) with the DLR Modular Aerial Camera System (MACS) shows that our method achieves sub-meter accuracy, with approximately 0.87 m error in the horizontal (XY) plane and 0.12 m in the vertical (Z) direction, while maintaining per-image runtimes between 1.47 and 4.91 seconds. Results are subject to minor noise from manual point-cloud annotation. These findings show that BA-based metric guidance provides consistency comparable to classical photogrammetric methods while significantly accelerating processing, enabling real-time 3D map generation.
### Title:
          Fine-Tuning Integrity for Modern Neural Networks: Structured Drift Proofs via Norm, Rank, and Sparsity Certificates
 - **Authors:** Zhenhang Shang, Kani Chen
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-tuning is now the primary method for adapting large neural networks, but it also introduces new integrity risks. An untrusted party can insert backdoors, change safety behavior, or overwrite large parts of a model while claiming only small updates. Existing verification tools focus on inference correctness or full-model provenance and do not address this problem. We introduce Fine-Tuning Integrity (FTI) as a security goal for controlled model evolution. An FTI system certifies that a fine-tuned model differs from a trusted base only within a policy-defined drift class. We propose Succinct Model Difference Proofs (SMDPs) as a new cryptographic primitive for enforcing these drift constraints. SMDPs provide zero-knowledge proofs that the update to a model is norm-bounded, low-rank, or sparse. The verifier cost depends only on the structure of the drift, not on the size of the model. We give concrete SMDP constructions based on random projections, polynomial commitments, and streaming linear checks. We also prove an information-theoretic lower bound showing that some form of structure is necessary for succinct proofs. Finally, we present architecture-aware instantiations for transformers, CNNs, and MLPs, together with an end-to-end system that aggregates block-level proofs into a global certificate.
### Title:
          Hallucination Basins: A Dynamic Framework for Understanding and Controlling LLM Hallucinations
 - **Authors:** Kalyan Cherukuri, Lav R. Varshney
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) hallucinate: they produce fluent outputs that are factually incorrect. We present a geometric dynamical systems framework in which hallucinations arise from task-dependent basin structure in latent space. Using autoregressive hidden-state trajectories across multiple open-source models and benchmarks, we find that separability is strongly task-dependent rather than universal: factoid settings can show clearer basin separation, whereas summarization and misconception-heavy settings are typically less stable and often overlap. We formalize this behavior with task-complexity and multi-basin theorems, characterize basin emergence in L-layer transformers, and show that geometry-aware steering can reduce hallucination probability without retraining.
### Title:
          AvatarPointillist: AutoRegressive 4D Gaussian Avatarization
 - **Authors:** Hongyu Liu, Xuan Wang, Yating Wang, Zijian Wu, Ziyu Wan, Yue Ma, Runtao Liu, Boyao Zhou, Yujun Shen, Qifeng Chen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce AvatarPointillist, a novel framework for generating dynamic 4D Gaussian avatars from a single portrait image. At the core of our method is a decoder-only Transformer that autoregressively generates a point cloud for 3D Gaussian Splatting. This sequential approach allows for precise, adaptive construction, dynamically adjusting point density and the total number of points based on the subject's complexity. During point generation, the AR model also jointly predicts per-point binding information, enabling realistic animation. After generation, a dedicated Gaussian decoder converts the points into complete, renderable Gaussian attributes. We demonstrate that conditioning the decoder on the latent features from the AR generator enables effective interaction between stages and markedly improves fidelity. Extensive experiments validate that AvatarPointillist produces high-quality, photorealistic, and controllable avatars. We believe this autoregressive formulation represents a new paradigm for avatar generation, and we will release our code inspire future research.
### Title:
          Unified Vector Floorplan Generation via Markup Representation
 - **Authors:** Kaede Shiohara, Toshihiko Yamasaki
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic residential floorplan generation has long been a central challenge bridging architecture and computer graphics, aiming to make spatial design more efficient and accessible. While early methods based on constraint satisfaction or combinatorial optimization ensure feasibility, they lack diversity and flexibility. Recent generative models achieve promising results but struggle to generalize across heterogeneous conditional tasks, such as generation from site boundaries, room adjacency graphs, or partial layouts, due to their suboptimal representations. To address this gap, we introduce Floorplan Markup Language (FML), a general representation that encodes floorplan information within a single structured grammar, which casts the entire floorplan generation problem into a next token prediction task. Leveraging FML, we develop a transformer-based generative model, FMLM, capable of producing high-fidelity and functional floorplans under diverse conditions. Comprehensive experiments on the RPLAN dataset demonstrate that FMLM, despite being a single model, surpasses the previous task-specific state-of-the-art methods.
### Title:
          Free-Range Gaussians: Non-Grid-Aligned Generative 3D Gaussian Reconstruction
 - **Authors:** Ahan Shabanov, Peter Hedman, Ethan Weber, Zhengqin Li, Denis Rozumny, Gael Le Lan, Naina Dhingra, Lei Luo, Andrea Vedaldi, Christian Richardt, Andrea Tagliasacchi, Bo Zhu, Numair Khan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Free-Range Gaussians, a multi-view reconstruction method that predicts non-pixel, non-voxel-aligned 3D Gaussians from as few as four images. This is done through flow matching over Gaussian parameters. Our generative formulation of reconstruction allows the model to be supervised with non-grid-aligned 3D data, and enables it to synthesize plausible content in unobserved regions. Thus, it improves on prior methods that produce highly redundant grid-aligned Gaussians, and suffer from holes or blurry conditional means in unobserved regions. To handle the number of Gaussians needed for high-quality results, we introduce a hierarchical patching scheme to group spatially related Gaussians into joint transformer tokens, halving the sequence length while preserving structure. We further propose a timestep-weighted rendering loss during training, and photometric gradient guidance and classifier-free guidance at inference to improve fidelity. Experiments on Objaverse and Google Scanned Objects show consistent improvements over pixel and voxel-aligned methods while using significantly fewer Gaussians, with large gains when input views leave parts of the object unobserved.
### Title:
          Vanast: Virtual Try-On with Human Image Animation via Synthetic Triplet Supervision
 - **Authors:** Hyunsoo Cha, Wonjung Woo, Byungjun Kim, Hanbyul Joo
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present Vanast, a unified framework that generates garment-transferred human animation videos directly from a single human image, garment images, and a pose guidance video. Conventional two-stage pipelines treat image-based virtual try-on and pose-driven animation as separate processes, which often results in identity drift, garment distortion, and front-back inconsistency. Our model addresses these issues by performing the entire process in a single unified step to achieve coherent synthesis. To enable this setting, we construct large-scale triplet supervision. Our data generation pipeline includes generating identity-preserving human images in alternative outfits that differ from garment catalog images, capturing full upper and lower garment triplets to overcome the single-garment-posed video pair limitation, and assembling diverse in-the-wild triplets without requiring garment catalog images. We further introduce a Dual Module architecture for video diffusion transformers to stabilize training, preserve pretrained generative quality, and improve garment accuracy, pose adherence, and identity preservation while supporting zero-shot garment interpolation. Together, these contributions allow Vanast to produce high-fidelity, identity-consistent animation across a wide range of garment types.
## Keyword: autonomous driving
### Title:
          YOLOv11 Demystified: A Practical Guide to High-Performance Object Detection
 - **Authors:** Nikhileswara Rao Sulake
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 YOLOv11 is the latest iteration in the You Only Look Once (YOLO) series of real-time object detectors, introducing novel architectural modules to improve feature extraction and small-object detection. In this paper, we present a detailed analysis of YOLOv11, including its backbone, neck, and head components. The model key innovations, the C3K2 blocks, Spatial Pyramid Pooling - Fast (SPPF), and C2PSA (Cross Stage Partial with Spatial Attention) modules enhance spatial feature processing while preserving speed. We compare YOLOv11 performance to prior YOLO versions on standard benchmarks, highlighting improvements in mean Average Precision (mAP) and inference speed. Our results demonstrate that YOLOv11 achieves superior accuracy without sacrificing real-time capabilities, making it well-suited for applications in autonomous driving, surveillance, and video this http URL work formalizes YOLOv11 in a research context, providing a clear reference for future studies.
### Title:
          SpectralSplat: Appearance-Disentangled Feed-Forward Gaussian Splatting for Driving Scenes
 - **Authors:** Quentin Herau, Tianshuo Xu, Depu Meng, Jiezhi Yang, Chensheng Peng, Spencer Sherk, Yihan Hu, Wei Zhan
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Graphics (cs.GR); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Feed-forward 3D Gaussian Splatting methods have achieved impressive reconstruction quality for autonomous driving scenes, yet they entangle scene geometry with transient appearance properties such as lighting, weather, and time of day. This coupling prevents relighting, appearance transfer, and consistent rendering across multi-traversal data captured under varying environmental conditions. We present SpectralSplat, a method that disentangles appearance from geometry within a feed-forward Gaussian Splatting framework. Our key insight is to factor color prediction into an appearance-agnostic base stream and and appearance-conditioned adapted stream, both produced by a shared MLP conditioned on a global appearance embedding derived from DINOv2 features. To enforce disentanglement, we train with paired observations generated by a hybrid relighting pipeline that combines physics-based intrinsic decomposition with diffusion based generative refinement, and supervise with complementary consistency, reconstruction, cross-appearance, and base color losses. We further introduce an appearance-adaptable temporal history that stores appearance-agnostic features, enabling accumulated Gaussians to be re-rendered under arbitrary target appearances. Experiments demonstrate that SpectralSplat preserves the reconstruction quality of the underlying backbone while enabling controllable appearance transfer and temporally consistent relighting across driving sequences.
### Title:
          HAD: Combining Hierarchical Diffusion with Metric-Decoupled RL for End-to-End Driving
 - **Authors:** Wenhao Yao, Xinglong Sun, Zhenxin Li, Shiyi Lan, Zi Wang, Jose M. Alvarez, Zuxuan Wu
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 End-to-end planning has emerged as a dominant paradigm for autonomous driving, where recent models often adopt a scoring-selection framework to choose trajectories from a large set of candidates, with diffusion-based decoding showing strong promise. However, directly selecting from the entire candidate space remains difficult to optimize, and Gaussian perturbations used in diffusion often introduce unrealistic trajectories that complicate the denoising process. In addition, for training these models, reinforcement learning (RL) has shown promise, but existing end-to-end RL approaches typically rely on a single coupled reward without structured signals, limiting optimization effectiveness. To address these challenges, we propose HAD, an end-to-end planning framework with a Hierarchical Diffusion Policy that decomposes planning into a coarse-to-fine process. To improve trajectory generation, we introduce Structure-Preserved Trajectory Expansion, which produces realistic candidates while maintaining kinematic structure. For policy learning, we develop Metric-Decoupled Policy Optimization (MDPO) to enable structured RL optimization across multiple driving objectives. Extensive experiments show that HAD achieves new state-of-the-art performance on both NAVSIM and HUGSIM, outperforming prior arts by a huge margin: +2.3 EPDMS on NAVSIM and +4.9 Route Completion on HUGSIM.
### Title:
          InCaRPose: In-Cabin Relative Camera Pose Estimation Model and Dataset
 - **Authors:** Felix Stillger, Lukas Hahn, Frederik Hasecke, Tobias Meisen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Camera extrinsic calibration is a fundamental task in computer vision. However, precise relative pose estimation in constrained, highly distorted environments, such as in-cabin automotive monitoring (ICAM), remains challenging. We present InCaRPose, a Transformer-based architecture designed for robust relative pose prediction between image pairs, which can be used for camera extrinsic calibration. By leveraging frozen backbone features such as DINOv3 and a Transformer-based decoder, our model effectively captures the geometric relationship between a reference and a target view. Unlike traditional methods, our approach achieves absolute metric-scale translation within the physically plausible adjustment range of in-cabin camera mounts in a single inference step, which is critical for ICAM, where accurate real-world distances are required for safety-relevant perception. We specifically address the challenges of highly distorted fisheye cameras in automotive interiors by training exclusively on synthetic data. Our model is capable of generalization to real-world cabin environments without relying on the exact same camera intrinsics and additionally achieves competitive performance on the public 7-Scenes dataset. Despite having limited training data, InCaRPose maintains high precision in both rotation and translation, even with a ViT-Small backbone. This enables real-time performance for time-critical inference, such as driver monitoring in supervised autonomous driving. We release our real-world In-Cabin-Pose test dataset consisting of highly distorted vehicle-interior images and our code at this https URL.
### Title:
          DriveVA: Video Action Models are Zero-Shot Drivers
 - **Authors:** Mengmeng Liu, Diankun Zhang, Jiuming Liu, Jianfeng Cui, Hongwei Xie, Guang Chen, Hangjun Ye, Michael Ying Yang, Francesco Nex, Hao Cheng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generalization is a central challenge in autonomous driving, as real-world deployment requires robust performance under unseen scenarios, sensor domains, and environmental conditions. Recent world-model-based planning methods have shown strong capabilities in scene understanding and multi-modal future prediction, yet their generalization across datasets and sensor configurations remains limited. In addition, their loosely coupled planning paradigm often leads to poor video-trajectory consistency during visual imagination. To overcome these limitations, we propose DriveVA, a novel autonomous driving world model that jointly decodes future visual forecasts and action sequences in a shared latent generative process. DriveVA inherits rich priors on motion dynamics and physical plausibility from well-pretrained large-scale video generation models to capture continuous spatiotemporal evolution and causal interaction patterns. To this end, DriveVA employs a DiT-based decoder to jointly predict future action sequences (trajectories) and videos, enabling tighter alignment between planning and scene evolution. We also introduce a video continuation strategy to strengthen long-duration rollout consistency. DriveVA achieves an impressive closed-loop performance of 90.9 PDM score on the challenge NAVSIM. Extensive experiments also demonstrate the zero-shot capability and cross-domain generalization of DriveVA, which reduces average L2 error and collision rate by 78.9% and 83.3% on nuScenes and 52.5% and 52.4% on the Bench2drive built on CARLA v2 compared with the state-of-the-art world-model-based planner.
### Title:
          GA-GS: Generation-Assisted Gaussian Splatting for Static Scene Reconstruction
 - **Authors:** Yedong Shen, Shiqi Zhang, Sha Zhang, Yifan Duan, Xinran Zhang, Wenhao Yu, Lu Zhang, Jiajun Deng, Yanyong Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reconstructing static 3D scene from monocular video with dynamic objects is important for numerous applications such as virtual reality and autonomous driving. Current approaches typically rely on background for static scene reconstruction, limiting the ability to recover regions occluded by dynamic objects. In this paper, we propose GA-GS, a Generation-Assisted Gaussian Splatting method for Static Scene Reconstruction. The key innovation of our work lies in leveraging generation to assist in reconstructing occluded regions. We employ a motion-aware module to segment and remove dynamic regions, and thenuse a diffusion model to inpaint the occluded areas, providing pseudo-ground-truth supervision. To balance contributions from real background and generated region, we introduce a learnable authenticity scalar for each Gaussian primitive, which dynamically modulates opacity during splatting for authenticity-aware rendering and supervision. Since no existing dataset provides ground-truth static scene of video with dynamic objects, we construct a dataset named Trajectory-Match, using a fixed-path robot to record each scene with/without dynamic objects, enabling quantitative evaluation in reconstruction of occluded regions. Extensive experiments on both the DAVIS and our dataset show that GA-GS achieves state-of-the-art performance in static scene reconstruction, especially in challenging scenarios with large-scale, persistent occlusions.
### Title:
          Adversarial Robustness Analysis of Cloud-Assisted Autonomous Driving Systems
 - **Authors:** Maher Al Islam, Amr S. El-Wakeel
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous vehicles increasingly rely on deep learning-based perception and control, which impose substantial computational demands. Cloud-assisted architectures offload these functions to remote servers, enabling enhanced perception and coordinated decision-making through the Internet of Vehicles (IoV). However, this paradigm introduces cross-layer vulnerabilities, where adversarial manipulation of perception models and network impairments in the vehicle-cloud link can jointly undermine safety-critical autonomy. This paper presents a hardware-in-the-loop IoV testbed that integrates real-time perception, control, and communication to evaluate such vulnerabilities in cloud-assisted autonomous driving. A YOLOv8-based object detector deployed on the cloud is subjected to whitebox adversarial attacks using the Fast Gradient Sign Method (FGSM) and Projected Gradient Descent (PGD), while network adversaries induce delay and packet loss in the vehicle-cloud loop. Results show that adversarial perturbations significantly degrade perception performance, with PGD reducing detection precision and recall from 0.73 and 0.68 in the clean baseline to 0.22 and 0.15 at epsilon= 0.04. Network delays of 150-250 ms, corresponding to transient losses of approximately 3-4 frames, and packet loss rates of 0.5-5 % further destabilize closed-loop control, leading to delayed actuation and rule violations. These findings highlight the need for cross-layer resilience in cloud-assisted autonomous driving systems.
### Title:
          Reproducibility study on how to find Spurious Correlations, Shortcut Learning, Clever Hans or Group-Distributional non-robustness and how to fix them
 - **Authors:** Ole Delzer, Sidney Bender
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep Neural Networks (DNNs) are increasingly utilized in high-stakes domains like medical diagnostics and autonomous driving where model reliability is critical. However, the research landscape for ensuring this reliability is terminologically fractured across communities that pursue the same goal of ensuring models rely on causally relevant features rather than confounding signals. While frameworks such as distributionally robust optimization (DRO), invariant risk minimization (IRM), shortcut learning, simplicity bias, and the Clever Hans effect all address model failure due to spurious correlations, researchers typically only reference work within their own domains. This reproducibility study unifies these perspectives through a comparative analysis of correction methods under challenging constraints like limited data availability and severe subgroup imbalance. We evaluate recently proposed correction methods based on explainable artificial intelligence (XAI) techniques alongside popular non-XAI baselines using both synthetic and real-world datasets. Findings show that XAI-based methods generally outperform non-XAI approaches, with Counterfactual Knowledge Distillation (CFKD) proving most consistently effective at improving generalization. Our experiments also reveal that the practical application of many methods is hindered by a dependency on group labels, as manual annotation is often infeasible and automated tools like Spectral Relevance Analysis (SpRAy) struggle with complex features and severe imbalance. Furthermore, the scarcity of minority group samples in validation sets renders model selection and hyperparameter tuning unreliable, posing a significant obstacle to the deployment of robust and trustworthy models in safety-critical areas.
### Title:
          Multimodal Backdoor Attack on VLMs for Autonomous Driving via Graffiti and Cross-Lingual Triggers
 - **Authors:** Jiancheng Wang, Lidan Liang, Yong Wang, Zengzhen Su, Haifeng Xia, Yuanting Yan, Wei Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual language model (VLM) is rapidly being integrated into safety-critical systems such as autonomous driving, making it an important attack surface for potential backdoor attacks. Existing backdoor attacks mainly rely on unimodal, explicit, and easily detectable triggers, making it difficult to construct both covert and stable attack channels in autonomous driving scenarios. GLA introduces two naturalistic triggers: graffiti-based visual patterns generated via stable diffusion inpainting, which seamlessly blend into urban scenes, and cross-language text triggers, which introduce distributional shifts while maintaining semantic consistency to build robust language-side trigger signals. Experiments on DriveVLM show that GLA requires only a 10\% poisoning ratio to achieve a 90\% Attack Success Rate (ASR) and a 0\% False Positive Rate (FPR). More insidiously, the backdoor does not weaken the model on clean tasks, but instead improves metrics such as BLEU-1, making it difficult for traditional performance-degradation-based detection methods to identify the attack. This study reveals underestimated security threats in self-driving VLMs and provides a new attack paradigm for backdoor evaluation in safety-critical multimodal systems.
### Title:
          Multi-Modal Sensor Fusion using Hybrid Attention for Autonomous Driving
 - **Authors:** Mayank Mayank, Bharanidhar Duraisamy, Florian Geiß, Abhinav Valada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate 3D object detection for autonomous driving requires complementary sensors. Cameras provide dense semantics but unreliable depth, while millimeter-wave radar offers precise range and velocity measurements with sparse geometry. We propose MMF-BEV, a radar-camera BEV fusion framework that leverages deformable attention for cross-modal feature alignment on the View-of-Delft (VoD) 4D radar dataset [1]. MMF-BEV builds a BEVDepth [2] camera branch and a RadarBEVNet [3] radar branch, each enhanced with Deformable Self-Attention, and fuses them via a Deformable Cross-Attention module. We evaluate three configurations: camera-only, radar-only, and hybrid fusion. A sensor contribution analysis quantifies per-distance modality weighting, providing interpretable evidence of sensor complementarity. A two-stage training strategy - pre-training the camera branch with depth supervision, then jointly training radar and fusion modules stabilizes learning. Experiments on VoD show that MMF-BEV consistently outperforms unimodal baselines and achieves competitive results against prior fusion methods across all object classes in both the full annotated area and near-range Region of Interest.
### Title:
          The Blind Spot of Adaptation: Quantifying and Mitigating Forgetting in Fine-tuned Driving Models
 - **Authors:** Runhao Mao, Hanshi Wang, Yixiang Yang, Qianli Ma, Jingmeng Zhou, Zhipeng Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The integration of Vision-Language Models (VLMs) into autonomous driving promises to solve long-tail scenarios, but this paradigm faces the critical and unaddressed challenge of catastrophic forgetting. The very fine-tuning process used to adapt these models to driving-specific data simultaneously erodes their invaluable pre-trained world knowledge, creating a self-defeating paradox that undermines the core reason for their use. This paper provides the first systematic investigation into this phenomenon. We introduce a new large-scale dataset of 180K scenes, which enables the first-ever benchmark specifically designed to quantify catastrophic forgetting in autonomous driving. Our analysis reveals that existing methods suffer from significant knowledge degradation. To address this, we propose the Drive Expert Adapter (DEA), a novel framework that circumvents this trade-off by shifting adaptation from the weight space to the prompt space. DEA dynamically routes inference through different knowledge experts based on scene-specific cues, enhancing driving-task performance without corrupting the model's foundational parameters. Extensive experiments demonstrate that our approach not only achieves state-of-the-art results on driving tasks but also effectively mitigates catastrophic forgetting, preserving the essential generalization capabilities that make VLMs a transformative force for autonomous systems. Data and model are released at FidelityDrivingBench.
### Title:
          HorizonWeaver: Generalizable Multi-Level Semantic Editing for Driving Scenes
 - **Authors:** Mauricio Soroco, Francesco Pittaluga, Zaid Tasneem, Abhishek Aich, Bingbing Zhuang, Wuyang Chen, Manmohan Chandraker, Ziyu Jiang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Ensuring safety in autonomous driving requires scalable generation of realistic, controllable driving scenes beyond what real-world testing provides. Yet existing instruction guided image editors, trained on object-centric or artistic data, struggle with dense, safety-critical driving layouts. We propose HorizonWeaver, which tackles three fundamental challenges in driving scene editing: (1) multi-level granularity, requiring coherent object- and scene-level edits in dense environments; (2) rich high-level semantics, preserving diverse objects while following detailed instructions; and (3) ubiquitous domain shifts, handling changes in climate, layout, and traffic across unseen environments. The core of HorizonWeaver is a set of complementary contributions across data, model, and training: (1) Data: Large-scale dataset generation, where we build a paired real/synthetic dataset from Boreas, nuScenes, and Argoverse2 to improve generalization; (2) Model: Language-Guided Masks for fine-grained editing, where semantics-enriched masks and prompts enable precise, language-guided edits; and (3) Training: Content preservation and instruction alignment, where joint losses enforce scene consistency and instruction fidelity. Together, HorizonWeaver provides a scalable framework for photorealistic, instruction-driven editing of complex driving scenes, collecting 255K images across 13 editing categories and outperforming prior methods in L1, CLIP, and DINO metrics, achieving +46.4% user preference and improving BEV segmentation IoU by +33%. Project page: this https URL
