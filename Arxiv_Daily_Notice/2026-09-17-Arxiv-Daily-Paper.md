# Showing new listings for Thursday, 17 September 2026
## Keyword: SLAM
### Title:
          Co-occurrence-Aware Quadratic Assignment for Local Feature Matching in Simultaneous Localization and Mapping
 - **Authors:** Yutaka Yamada, Yohei Hamakawa, Yutaro Ishigaki, Masaya Yamasaki, Kosuke Tatsumura
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Local feature matching, which associates keypoints in two images as keypoint pairs, is fundamental to Visual Simultaneous Localization and Mapping (Visual SLAM). Nearest Neighbor (NN) search is commonly used for keypoint matching, but it has difficulty selecting correct keypoint pairs when multiple candidates have similar costs. To improve matching accuracy, this paper proposes a keypoint matching method that considers the pairwise co-occurrence of two keypoint pairs. The keypoint matching is formulated as a quadratic assignment problem, which is an NP-hard combinatorial optimization problem, making it difficult to solve quickly on conventional computers. Recently, Ising machines have been developed as computing devices capable of solving hard combinatorial optimization problems. Using a simulated bifurcation based Ising machine, the proposed method improved matching accuracy by approximately 8 percentage points over a conventional method on the HPatches dataset. Furthermore, we integrated the proposed method into ORB-SLAM3, a representative academic Visual SLAM system, and achieved a 3.78-fold improvement in absolute pose error (APE) and a 2.85-fold improvement in relative pose error (RPE) on the KITTI dataset scenes where multiple same shape objects are repeatedly arranged, which are challenging for accurate self-pose estimation by the original ORB-SLAM3.
### Title:
          SOL-SLAM: Inverse Compositional Gauss-Newton Direct Registration for Fast Sonar-Only Local SLAM
 - **Authors:** Kalvik Jakkala, Jason O'Kane
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous underwater navigation typically relies on complex and expensive multi-modal sensor suites designed to prioritize global Simultaneous Localization and Mapping (SLAM) accuracy. However, local reactive behaviors such as coarse navigation and obstacle avoidance require only local consistency---a capability that should be feasible using only a Forward-Looking Sonar (FLS), yet remains largely unaddressed, leaving a critical gap in FLS-only local SLAM. Moreover, existing acoustic SLAM frameworks predominantly rely on sparse feature extraction methods that discard substantial portions of the already information-sparse acoustic returns. To overcome these limitations, this work introduces a dense direct registration approach that aligns full acoustic intensity scans to a recursively updated local map. Real-time execution is achieved via an Inverse Compositional Gauss-Newton optimization strategy that minimizes computational overhead. Experimental evaluations show that this dense method yields significant improvements on translation error compared to sparse keypoint baselines, maintaining stable sub-meter tracking precision over wide displacement gaps. Moreover, this approach delivers odometry performance comparable to multi-sensor fusion pipelines (FLS, DVL, and IMU), bypassing expensive payload dependencies in feature-rich environments. We validate real-world applicability through AUV field trials, running the full local SLAM approach onboard an embedded, resource-constrained computer.
## Keyword: odometry
### Title:
          Benchmarking Visual-Inertial Odometry in Subterranean Environments Under Sensor Degradation, Miscalibration, and Dynamic Occlusion
 - **Authors:** Yueying Zhu, Xiang Li, Thien-Minh Nguyen, Xuehe Wang, Shenghai Yuan
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual-inertial odometry (VIO) is a core capability for autonomous operation in GPS-denied subterranean environments, yet its reliability can degrade sharply under sensor drift, calibration errors, and dynamic occlusion. Existing evaluations mainly emphasize nominal-condition accuracy, offering limited insight into when practical deployment failures occur. In this work, we present a failure-centric stress-test benchmark for VIO in underground environments using the CERBERUS dataset. We systematically evaluate four representative VIO systems spanning filtering-, optimization-, and learning-based paradigms under nine practical perturbation settings, including IMU bias and noise variation, camera intrinsic and extrinsic drift, and dynamic scene occlusion. Beyond conventional trajectory error, we analyze robustness limits through coverage ratio and failure thresholds, revealing breakdown behaviors that are not captured by nominal-condition performance alone. Our study shows distinct vulnerability patterns across VIO paradigms: some methods are more sensitive to inertial degradation, while others are more affected by geometric miscalibration or dynamic interference. These results provide deployment-oriented guidance for VIO selection, calibration prioritization, and reliable operation in challenging underground scenarios. To support reproducible evaluation and future extensions, we will release the full benchmark scripts and evaluation pipeline.
### Title:
          SOL-SLAM: Inverse Compositional Gauss-Newton Direct Registration for Fast Sonar-Only Local SLAM
 - **Authors:** Kalvik Jakkala, Jason O'Kane
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous underwater navigation typically relies on complex and expensive multi-modal sensor suites designed to prioritize global Simultaneous Localization and Mapping (SLAM) accuracy. However, local reactive behaviors such as coarse navigation and obstacle avoidance require only local consistency---a capability that should be feasible using only a Forward-Looking Sonar (FLS), yet remains largely unaddressed, leaving a critical gap in FLS-only local SLAM. Moreover, existing acoustic SLAM frameworks predominantly rely on sparse feature extraction methods that discard substantial portions of the already information-sparse acoustic returns. To overcome these limitations, this work introduces a dense direct registration approach that aligns full acoustic intensity scans to a recursively updated local map. Real-time execution is achieved via an Inverse Compositional Gauss-Newton optimization strategy that minimizes computational overhead. Experimental evaluations show that this dense method yields significant improvements on translation error compared to sparse keypoint baselines, maintaining stable sub-meter tracking precision over wide displacement gaps. Moreover, this approach delivers odometry performance comparable to multi-sensor fusion pipelines (FLS, DVL, and IMU), bypassing expensive payload dependencies in feature-rich environments. We validate real-world applicability through AUV field trials, running the full local SLAM approach onboard an embedded, resource-constrained computer.
## Keyword: livox
There is no result 
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Imitation Learning for Autonomous Driving in CARLA
 - **Authors:** Jordy Kieto
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Behavioral cloning trains a policy offline on expert demonstrations, but deployment is closed loop: each action affects the observations the policy receives next. We study how much closed-loop driving competence a compact multimodal policy can acquire from offline demonstrations in the CARLA simulator. The policy uses five-frame histories of RGB images, LiDAR, vehicle telemetry, and lane waypoints to predict throttle, brake, and steering at 20 Hz. Demonstrations were collected in three stages, ending with a systematic route-generation procedure that enumerates spawn points and feasible maneuvers and verifies completed autopilot routes. The released 1.36 million parameter policy was trained on 236,882 windows, representing about 3.3 hours of driving from 448 captures. The resulting policy drives autonomously for hours on training and held-out routes. In our runs, it did so without collisions and also transferred qualitatively to an unseen CARLA town with different road geometry. We also observed recovery from large trajectory deviations, although we do not claim systematic recovery without controlled evaluation. We report offline metrics and distinguish measured results from qualitative closed-loop observations. We release the code, trained checkpoint, ONNX model, data sample, and an evidence audit for the reported claims.
### Title:
          DRT&R: Direct Radar Teach & Repeat
 - **Authors:** Alexander Krawciw, Daniil Lisus, Cedric Le Gentil, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar-based navigation is appealing for its robustness to adverse conditions involving airborne particles, such as precipitation, dust, fog, and smoke, that can cause lidar-based systems to fail. Recently, direct methods that retain and use the entire radar scan rather than sparse points have improved on-road global localization performance. However, they have yet to be deployed in off-road environments or in closed-loop systems. Additionally, even direct global maps may lose information: their global nature leads to a smoothing out of viewpoint-dependent radar artifacts, which can provide pose information when mapping and localization occur along similar trajectories. This paper introduces Direct Radar Teach & Repeat (DRT&R): a direct spinning radar-based navigation stack that maximizes the amount of retained information by combining direct radar processing with local mapping. DRT&R yields state-of-the-art (SOTA) localization performance in both on-road and off-road environments. Using 344 km of on-road data and 20 km of off-road data, DRT&R is able to localize to within 4 cm in most on-road and off-road conditions, and 12 cm in geometrically degenerate and sparse environments. DRT&R is also evaluated autonomously in closed loop with an MPC controller for more than 10 km using a Clearpath Warthog off-road vehicle, demonstrating that it runs in real time and achieves SOTA tracking performance for off-road radar navigation.
### Title:
          PESTO: Formally Correct Registration of LiDAR Point Clouds with Limited Overlap
 - **Authors:** Valen Yamamoto, Matteo Marchi, Paulo Tabuada
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this paper we tackle the problem of aligning LiDAR point clouds also known as the point cloud registration problem. We propose a new algorithm, PESTO, that exploits tetrahedra as "universal features" for LiDAR data, i.e., features that are agnostic to the environment where the LiDAR sensors are deployed. We show empirically that PESTO is competitive with existing solutions for aligning LiDAR point clouds, especially in environments with occlusions. Moreover, we establish PESTO's formal correctness by proving worst-case bounds on the alignment error.
### Title:
          OmniRisk: Omnidirectional Trajectory-Risk Learning for Agile Quadrotor Dynamic Avoidance
 - **Authors:** Yifan He, Yang Liu, Wenhao Zhao, Hai Lin, Deping Zhang, Mingze Ma, Fei Gao, Huan Yu, Zipeng Dai, Ziming Ding
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Agile quadrotor avoidance of fast-moving obstacles requires anticipating collisions and selecting feasible maneuvers within short reaction windows. Reliable predictive avoidance remains challenging because sparse range observations do not directly reveal obstacle motion, while online trajectory optimizers either scale poorly with obstacle count or remain efficient at the expense of reliability in dense, high-speed encounters. We present OmniRisk, an omnidirectional planning framework that learns trajectory-level risk offline for efficient onboard evasion. A fixed-dimensional tensor combines LiDAR range panoramas, dynamic masks, and Cartesian surface velocities to represent geometry and motion jointly. We formulate an asymmetric risk field aligned with obstacle velocity that emphasizes approaching interactions and attenuates receding ones. Accumulating this risk along predicted relative trajectories provides dense supervision and discourages unnecessary hesitation after obstacles pass. A dual-branch circular convolutional network predicts terminal boundary states and dynamic risks for candidate primitives over an omnidirectional anchor lattice in a single forward pass, followed by selection and closed-form reconstruction of the selected candidate primitive. This formulation removes online risk accumulation along trajectories and makes risk-inference cost independent of obstacle count. OmniRisk enables efficient onboard avoidance, with real-world flights demonstrating consecutive evasive maneuvers at relative encounter speeds up to 15 m/s without fine-tuning. Code is available at this https URL.
### Title:
          VLM-MPPI: Grounding Natural Language in Behaviorally Diverse Trajectories for Aerial Navigation
 - **Authors:** Hanbing Zhang, Fangguo Zhao, Zerui Li, Xin Guan, Peng Cheng, Shuo Li
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a hierarchical UAV navigation framework that aligns natural-language intent with dynamically feasible flight behaviors in cluttered indoor environments. To bridge the gap between abstract semantics and low-level control, we employ a parallelized ensemble of six behavior-conditioned Model Predictive Path Integral (MPPI) planners. Crucially, by designing mode-specific guiding costs and sampling biases, we induce distinct trajectory modes that converge to unique behavioral means, yielding a compact set of intentionally diverse candidates rather than mere stochastic variations. We project these 3D candidates onto the onboard first-person-view RGB stream, turning language grounding into a visual action selection problem. A pretrained vision--language model (VLM) asynchronously selects the candidate index given the overlaid FPV image and a natural-language prompt, while MPPI replans at 20Hz and a PID-based low-level controller tracks the selected trajectory. We implement the full pipeline in NVIDIA Isaac Sim and on a real-world quadrotor platform equipped with LiDAR and RGB sensing. Experiments in both simulation and real-world flights show semantically meaningful behavior diversity, robust language alignment despite VLM latency, and safe, repeatable flight across all modes, achieving 100% task success in our evaluated scenarios.
### Title:
          Semantic-ITC: A Frame-wise Indoor Mobile Laser Scanning Dataset and Benchmark for Semantic Segmentation
 - **Authors:** Haiyang Wu, Muhammad Affan, George Vosselman, Ville Lehtola
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Semantic labels for indoor mobile laser scanning (MLS) frames remain largely absent from current point cloud semantic segmentation benchmarks, which mainly focus on reconstructed indoor scenes or outdoor LiDAR perception. This paper introduces Semantic-ITC, to the best of our knowledge the first public dataset and benchmark for frame-wise indoor MLS semantic segmentation. The dataset contains 52 indoor sequences, 79,108 MLS frames, and 1.23 billion labeled points collected in classrooms, corridors, meeting rooms, offices, and study areas. Labels are attached directly to measured LiDAR points in each frame using 16 semantic classes covering structural elements, furniture, room equipment, vegetation, and other indoor objects. Semantic-ITC preserves the sparse, non-uniform, and frame-wise sampling pattern of indoor MLS, making it distinct from scene-level reconstructed point clouds and mesh-based indoor datasets. The annotations are produced by a hybrid workflow that combines predictions from a visual foundation model applied to synchronized RGB images, structural information from BIM, and manual refinement, with the final labels assigned to the original LiDAR frames. A single-frame benchmark is provided, and the best baseline reaches 79.27\% mIoU. Remaining errors are concentrated around object boundaries and ambiguous indoor classes, indicating the challenges of indoor MLS segmentation under sparse frame geometry and long-tailed class distributions. The dataset provides a public benchmark for evaluating semantic segmentation directly on measured indoor MLS frames and supports future studies on frame-wise indoor MLS semantic segmentation.
### Title:
          PASSAGE: Scaling Scene-Aligned Motion Learning for Perceptive Humanoid Traversal in Cluttered Environments
 - **Authors:** Yuxuan Ma, Zicheng Zeng, Chunlin Peng, Zhoujian Li, Zetong Zhao, Zhikai Zhang, Yunrui Lian, Han Xue, Sikai Liang, Weiyi Zhu, Mulin Chen, Chenghuai Lin, Jiayu Zeng, Yanwei An, Songan Zhang, Jiayuan Gu, Jilong Wang, Jingbo Wang, He Wang, Li Yi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humanoid robots can step over, squeeze past, and duck under obstacles, but learning to select and coordinate these behaviors from onboard perception remains challenging. Many existing approaches rely on task-specific reinforcement-learning objectives or curated motion libraries, making broad behavioral coverage costly. We present PASSAGE, a perception-conditioned planner--tracker framework for humanoid traversal. Using virtual reality and inertial motion capture, we collect 100 h of scene-aligned human motion across 1,500 cluttered scenes. A conditional flow-matching planner generates short-horizon references from motion history, a local destination, and a robot-centric multi-layer elevation map, while a perceptive whole-body tracker executes them at 50 Hz with geometric feedback. Real-time chunking promotes inter-chunk consistency, and planner-side RL post-training under the frozen tracker further improves closed-loop performance. Without skill annotations or obstacle-specific policies, one planner--tracker pair selects and composes traversal behaviors across unseen geometries. In simulation, component ablations quantify the contribution of each stage. Across three independent training seeds, scaling captured data from 6 to 100 h increases mean contact-free success from 48.1% to 68.9% on held-out scenes, while the final model with validated scene augmentation reaches 70.3%. The fully onboard system integrates egocentric 3D LiDAR perception, online occupancy mapping, 6.25 Hz planning, and 50 Hz control on a Jetson AGX Orin; tests across 50 unseen physical layouts demonstrate traversal without prebuilt maps or offboard computation.
### Title:
          SEAM: Submap-Anchored Evidence for Lifelong LiDAR Mapping under Trajectory Deformation
 - **Authors:** Kyuwon Kim
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose SEAM, a LiDAR-based lifelong mapping framework. Instead of relying on a single anchor spanning the entire session, SEAM generates evidence based on a trajectory optimized with submap-level anchors, and performs dynamic object removal and change detection. Through submap-level reprojection, the generated evidence remains usable even if the trajectory is subsequently modified by a new session, eliminating the need to recompute the entire process from scratch. SEAM suppresses geometrically unreliable inter-session loop edges using a DOP-based confidence measure. Suppressing unreliable loop edges prevents alignment errors. SEAM also uses a directional voxel-wise evidence model. The model accounts for occupancy patterns that vary with ray direction. Direction-aware evidence separates dynamic objects from environmental changes more precisely. Experiments on a real construction-site dataset and a long-term multi-session dataset show that SEAM achieves higher accuracy and faster processing than existing methods.
### Title:
          Loco-Loco-RL: Low-Cost Terrain Mapping for Humanoid Locomotion with Reinforcement Learning
 - **Authors:** Jordan Dowdy, Gryffin Reizian, Jean Chagas Vaz
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Informative terrain perception is important for robust reinforcement learning policies in humanoid locomotion. Still, common sensors such as depth cameras and LiDARs incur high cost, power, and processing overhead while often producing redundant, high-resolution data. This work uses a low-cost time-of-flight sensor to provide a compact 3D local terrain representation for humanoid locomotion. To efficiently use this sparse exteroceptive input, we introduce a token-compressed temporal transformer policy. Proprioceptive and terrain observations are tokenized and processed by a self-attention multi-head transformer to capture within-timestep relationships between observation terms. The attended tokens are then compressed through an MLP-based latent-space token compression module before being stored in a rolling 15-timestep history. A second cross-attention multi-head transformer extracts temporal locomotion features from this compact history for policy learning. By compressing tokens before temporal aggregation, the architecture preserves important terrain-observation structure while limiting the dimensional growth of attention over observation histories. We validate our method through sim-to-real transfer on physical hardware using a terrain-based locomotion benchmark, demonstrating robust humanoid terrain walking with low-cost local terrain sensing.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          PhysVGGT: Feed-Forward Dense Physical Property Estimation from A Single Image
 - **Authors:** Sneha Paul, Guile Wu, Bingbing Liu, Dongfeng Bai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physical properties, such as friction, hardness, stiffness, and density, govern how robots should grasp, manipulate and interact with objects, yet estimating these properties from RGB images remains challenging. Existing methods typically employ per-object reconstruction augmented with physical properties or directly query vision-language models at test time, which results in substantial computational overhead that limits their applicability. In this work, we present PhysVGGT, a feed-forward model that predicts dense maps of friction coefficient, Shore hardness, Young's modulus, and density, together with object-level mass, from a single RGB image in one forward pass. The key idea of PhysVGGT is to formulate physical property estimation as a dense per-pixel prediction problem and employ a visual geometry transformer to extract geometry-aware tokens from the input image followed by a dense prediction branch for estimating local physical properties and a global prediction branch for estimating object-level mass. In addition, we introduce a scalable pseudo-label generation pipeline that enables large-scale weakly supervised training for dense physical property prediction, substantially reducing the need for expensive direct physical measurements. Extensive experiments show that PhysVGGT achieves state-of-the-art performance on the ABO-500 dataset and generalizes effectively to the out-of-distribution NeRF2Physics dataset. Moreover, PhysVGGT eliminates the need for per-object reconstruction and test-time optimization, achieving an inference latency of only 0.13s per image, making it $27\times$ faster than the previous state of the art.
## Keyword: mapping
### Title:
          A Systematic Evaluation of the COTQ Provincial Land Cover Product: Structural Consistency, Spectral Separability, and Relative Positioning Against ESA, ESRI, and Google Products
 - **Authors:** Étienne Clabaut, Samuel Foucher, Yacine Bouroubi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 High-resolution land use and land cover (LULC) products derived from Sentinel-2 imagery are widely used for environmental monitoring and land management, yet their performance can vary across regions with complex ecological gradients and heterogeneous surface conditions. In Quebec, these limitations motivated the development of a provincial 10-m land-cover product, the COTQ, designed to support annual monitoring of land occupation and soil artificialisation. This study presents a systematic evaluation of the COTQ product relative to three global 10-m LULC datasets: ESA WorldCover, ESRI LandCover, and Google DynamicWorld. This paper does not introduce a new mapping methodology but focuses on analysing the behaviour and consistency of the COTQ using complementary evaluation approaches. All products are harmonized under a common legend and compared using structural indicators (object-size distributions, shape complexity, Adjusted Rand Index, and Intersection over Union), spectral separability metrics derived from Sentinel-2 reflectance data, and a targeted photo-interpretation of disagreement areas. The analysis is conducted over eight Sentinel-2 tiles selected to represent the main bioclimatic domains of Québec, from temperate and boreal forests to northern tundra environments. The results show that the COTQ exhibits structural and spectral characteristics most similar to ESA WorldCover among the reference global products, while revealing systematic differences linked to class definitions and thematic priorities, particularly for urban areas, wetlands, and rocky or cryptogamic surfaces. This multi-criteria evaluation provides an objective characterization of the COTQ product and clarifies its relative positioning with respect to existing global land-cover datasets for operational land monitoring in Québec.
### Title:
          Beyond Performance Metrics: Uncertainty Mapping of Label Ambiguity in Fazekas Score Prediction
 - **Authors:** Susanne Schmid, Johanna Ospel, Richard Frayne, Roberto Souza
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reference labels used to train medical image classification models are not always as certain as they may appear, and this uncertainty has implications on performance metrics. In this study, we propose a framework to analyze model performance for periventricular Fazekas score prediction that goes beyond conventional metrics. The Fazekas score is an ordinal visual rating scale used to assess the severity of white matter hyperintensities and is known to be affected by inter-rater variability. While the best Fazekas score prediction model achieved a Matthews correlation coefficient (MCC) of 0.70, performance varied across data splits and loss functions, making interpretation of model capabilities difficult. Rather than interpreting epistemic uncertainty of a model's prediction as an isolated scalar value, our approach of uncertainty mapping relates uncertainty to its position within the learned feature representation. This highlights regions of class-boundary transitions where cases appear more ambiguous and misclassifications are more likely. It also identifies potential label disagreement, including low-uncertainty misclassified cases that expert review found to be inconsistent with the original reference Fazekas score. Therefore, uncertainty mapping allows model behaviour to be examined in relation to class separation and potential model-label disagreement. Loss function choice also influenced the uncertainty profile, with some models showing clearer class separation and more localized uncertainty in ambiguous regions than others. These findings suggest that uncertainty mapping for Fazekas score predictions can support model interpretation and targeted dataset review when reference labels are affected by ambiguity/ inter-rater variability.
### Title:
          DRT&R: Direct Radar Teach & Repeat
 - **Authors:** Alexander Krawciw, Daniil Lisus, Cedric Le Gentil, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar-based navigation is appealing for its robustness to adverse conditions involving airborne particles, such as precipitation, dust, fog, and smoke, that can cause lidar-based systems to fail. Recently, direct methods that retain and use the entire radar scan rather than sparse points have improved on-road global localization performance. However, they have yet to be deployed in off-road environments or in closed-loop systems. Additionally, even direct global maps may lose information: their global nature leads to a smoothing out of viewpoint-dependent radar artifacts, which can provide pose information when mapping and localization occur along similar trajectories. This paper introduces Direct Radar Teach & Repeat (DRT&R): a direct spinning radar-based navigation stack that maximizes the amount of retained information by combining direct radar processing with local mapping. DRT&R yields state-of-the-art (SOTA) localization performance in both on-road and off-road environments. Using 344 km of on-road data and 20 km of off-road data, DRT&R is able to localize to within 4 cm in most on-road and off-road conditions, and 12 cm in geometrically degenerate and sparse environments. DRT&R is also evaluated autonomously in closed loop with an MPC controller for more than 10 km using a Clearpath Warthog off-road vehicle, demonstrating that it runs in real time and achieves SOTA tracking performance for off-road radar navigation.
### Title:
          Detecting Argument-Swap Bugs Using Context-Enhanced Code Representations
 - **Authors:** Subrata Das, Ali Aman, Muhammad Asaduzzaman, Kawser Wazed Nafi, Salimur Choudhury
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Names of source code elements convey rich semantic information and have been widely used in software engineering tasks such as bug detection, code completion, type prediction, and code classification. Prior studies exploit lexical similarity between method arguments and formal parameter names to detect bugs caused by incorrectly ordered arguments, typically relying on establishing mappings between method calls and their corresponding definitions. However, such mappings are often difficult to obtain in dynamically typed languages like Python. In this paper, we present BugProbe, a learning-based approach for detecting incorrectly ordered arguments in Python method calls that does not require call-to-definition mappings. Our approach leverages multiple sources of contextual information, including local context and argument usage context, and combines name-based similarity with machine learning to construct expressive representations of method arguments. We collect a new dataset of 132,739 Python source files from the top-1,000 starred GitHub repositories, yielding 3,371,244 synthetic training examples, and contribute a curated benchmark of 55 real-world argument-swap bugs manually verified from commit histories. We evaluate our approach on this dataset and show that it achieves high accuracy and consistently outperforms a state-of-the-art baseline across standard evaluation metrics. These results demonstrate that effective detection of argument-ordering bugs is possible without relying on explicit call-to-definition resolution, making the approach well suited for dynamically typed language settings.
### Title:
          Co-occurrence-Aware Quadratic Assignment for Local Feature Matching in Simultaneous Localization and Mapping
 - **Authors:** Yutaka Yamada, Yohei Hamakawa, Yutaro Ishigaki, Masaya Yamasaki, Kosuke Tatsumura
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Local feature matching, which associates keypoints in two images as keypoint pairs, is fundamental to Visual Simultaneous Localization and Mapping (Visual SLAM). Nearest Neighbor (NN) search is commonly used for keypoint matching, but it has difficulty selecting correct keypoint pairs when multiple candidates have similar costs. To improve matching accuracy, this paper proposes a keypoint matching method that considers the pairwise co-occurrence of two keypoint pairs. The keypoint matching is formulated as a quadratic assignment problem, which is an NP-hard combinatorial optimization problem, making it difficult to solve quickly on conventional computers. Recently, Ising machines have been developed as computing devices capable of solving hard combinatorial optimization problems. Using a simulated bifurcation based Ising machine, the proposed method improved matching accuracy by approximately 8 percentage points over a conventional method on the HPatches dataset. Furthermore, we integrated the proposed method into ORB-SLAM3, a representative academic Visual SLAM system, and achieved a 3.78-fold improvement in absolute pose error (APE) and a 2.85-fold improvement in relative pose error (RPE) on the KITTI dataset scenes where multiple same shape objects are repeatedly arranged, which are challenging for accurate self-pose estimation by the original ORB-SLAM3.
### Title:
          Multi-Session Multimodal Underwater Mapping with Acoustic and Optical Imaging
 - **Authors:** Precious Philip-Ifabiyi, Valerio Franchi, Fausto Ferreira, Nuno Gracias
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurate seafloor mapping is essential for marine science, archaeology, and environmental monitoring. However, integrating data from different sensors, such as side-scan sonar and optical cameras, collected across separate survey sessions, remains challenging due to positioning drift and sensor offsets. This paper presents a multi-session, multimodal underwater mapping framework based on factor graph optimization. The method jointly optimizes vehicle trajectories, 3D landmark positions, sensor extrinsics, and per-session global alignment transformations. By combining rigid inter-session corrections with local trajectory deformations, it compensates for both inter-session offsets and intra-session distortions from accumulated navigation errors. The proposed methodology was validated on real-world datasets collected along the Catalan coast. Results show measurable improvements in map consistency over both unoptimized and rigid-alignment baselines across all metrics, including Pixel Accuracy and mean Intersection over Union. The method achieves a 3.4% improvement in pixel accuracy over the unoptimized baseline, corresponding to improved semantic labelling across approximately 14700 $\text{m}^2$ of mapped area. Qualitative results further show consistent co-registration between sonar and optical maps, even in the presence of significant trajectory distortions and inter-session misalignments. These findings demonstrate the potential of the proposed framework to generate coherent multimodal seafloor maps from heterogeneous underwater surveys.
### Title:
          Mixed-Integer Nonlinear Differentiable Predictive Control for Underground Pumped Hydro Energy Storage Systems
 - **Authors:** Honghui Zheng, Ján Boldocký, Yury Dvorkin, Ján Drgoňa
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper extends Mixed-Integer Differentiable Predictive Control (MI-DPC) to multi-modal discrete decisions and nonconvex polynomial dynamics arising in Underground Pumped Hydro Energy Storage Systems (UPHES). A neural policy mapping problem parameters to continuous setpoints and integer mode selections via a Gumbel-Softmax layer is trained in a self-supervised manner by differentiating the expectation of the finite horizon control objective through the nonlinear dynamics model. Three methodological contributions enable this extension: a parallel differentiable simulator that preserves gradient magnitude, a Transformer encoder that captures long-range temporal dependencies, and a Gumbel-Softmax temperature annealing schedule that regularizes the combinatorial search. We demonstrate the framework on day-ahead scheduling of a UPHES, a large-scale mixed-integer optimal control problem with nonlinear unit performance curves and volume-head coupling. MI-DPC achieves only 1.6% suboptimality relative to a piecewise mixed-integer quadratic programming baseline, while providing five orders of magnitude speedup in online scheduling time.
### Title:
          Modeling the Developmental Shift in Telicity Acquisition
 - **Authors:** Ellie Xia, Parisa Kordjamshidi, Alan Hezao Ke
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Acquiring telicity, which is the distinction between bounded (e.g., ate an apple) and unbounded (e.g., ate apples) events, requires first language (L1) learners to map surface-level and semantic cues to abstract event structures, but the computational trajectory of this mapping is not well understood. We introduce a Difference in Surprisal method that uses GPT2 token surprisal over paired temporal adverbial diagnostics (in an hour versus for an hour) to automatically label telicity across English CHILDES corpora, validated against expert linguist judgments. Using these labels, we train diagnostic logistic regression classifiers on 12 syntactic and lexical semantic features to compare how child speech and child-directed speech encode telicity. The two models diverge: the child model reaches near perfect accuracy through a single deterministic cue, the presence of a post-verbal determiner, while the adult model relies more heavily on verb class and other lexical semantic features, with the determiner cue neutralized. This trajectory supports Syntactic Bootstrapping: learners first exploit high-frequency structural cues as a scaffold to bootstrap, before developing fully compositional, verb-based event structures.
### Title:
          A Design Space for Visual Interfaces for Generative Image Models
 - **Authors:** Susie S.Y. Li, Mingwei S.G. Li, Remco Chang
 - **Subjects:** Subjects:
Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Interactive visual interfaces have become an important means of controlling generative image models, enabling users to manipulate generation through prompts, direct manipulation, and a range of interactions. However, existing techniques are typically presented as independent systems, making it difficult to understand how they relate, compare their interaction mechanisms, or identify opportunities for new interface designs. We introduce a design space for interactive visual interfaces for generative image models derived from 51 research systems and practitioner tools. The framework decomposes each system into three complementary components: the user interface (U), the controllable model objects (Z), and the mapping function ($\phi$) that translates user interaction into model operations. This decomposition provides a common representation for analyzing heterogeneous interaction techniques across model families, revealing recurring design patterns and underexplored regions of the design space. We further present an interactive corpus explorer that support comparative analysis, and discuss usage scenarios for both educational settings and HCI/AI practitioners identifying research and design opportunities.
### Title:
          Bridging the Opacity: Evidence-Backed Cross-Chain Transaction Correspondence Reconstruction Across Heterogeneous Blockchains
 - **Authors:** Dan Lin, Huan Xiao, Ziwei Li, Xiapu Luo, Jiachi Chen, Jiajing Wu, Zibin Zheng
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-chain bridges enable interoperability, but they also break the transaction trails needed to trace illicit funds. Third-party investigators typically cannot access the source-to-destination mappings maintained by bridge backends, and our survey of 131 bridges finds that only 16.79% provide complete public tracking. Existing approaches depend on official APIs, EVM-specific assumptions, or fragile temporal heuristics, limiting their ability to trace transfers across heterogeneous ledgers. We present XSplicer, an evidence-driven system for reconstructing cross-chain transaction correspondence (xTCR) without privileged access to bridge backends. XSplicer derives unified semantic specifications from public protocol documentation and transaction examples, translates them into lightweight parsers and verifiers, and links source and destination transactions by prioritizing hard evidence and using soft clues only when necessary. We evaluate XSplicer on seven bridge protocols spanning EVM, Bitcoin, and Solana. XSplicer achieves 92.5% global recovery rate and up to 98.61% on individual protocols. Under adversarial noise, its hard-evidence verifier retains the correct match in 100% of tested cases, while soft-clue matching degrades as ambiguity increases. In two real-world case studies, XSplicer recovers more than 1,900 historical transaction pairs after Multichain ceased operations and identifies 754 illicit cross-chain transfers worth 105.6 million USD in the Bybit laundering incident. These results show that public protocol invariants can support practical cross-chain forensics without privileged bridge mappings.
### Title:
          T-SANDHI: Tone Sandhi-aware Adaptive Network with Decoupled Hybrid Injection for Low-resource Taiwanese Hokkien Speech Recognition
 - **Authors:** Hung-Yang Sung, Chien-Chun Wang, Tien-Hong Lo, Yu-Sheng Tsao, Yung-Chang Hsu, Berlin Chen
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In Taiwanese Hokkien automatic speech recognition (ASR), prior studies often treat tone sandhi as a major challenge under the assumption that models fail to process implicit phonological variations. However, our experiments on Taiwanese Hokkien reveal that speech foundation models actually handle tone sandhi variations effectively, and the real performance bottleneck stems from a localized confusion between these variations and retained citation tones. To address this, we propose T-SANDHI to explicitly decouple surface acoustics from underlying lexical intent on top of a frozen Whisper backbone. Using a lexicon-guided multi-task learning structure driven by text-derived pseudo labels, our lightweight hybrid injection module integrates independent citation and sandhi phonetic streams via dynamic gating. Extensive evaluation on the TAT-MOE corpus and two blind test sets demonstrates that this explicit disentanglement effectively resolves tonal mapping confusion, outperforming baselines with strict parameter efficiency.
### Title:
          CapMap-MS-TTA: 3rd Place Solution for the MUMU Track of the 8th LSVOS Challenge at ECCV 2026
 - **Authors:** Chengfeng Qiu, Kaifeng Wei
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The MUMU track of the 8th Large-scale Video Object Segmentation (LSVOS) Challenge requires a single unified multimodal model to jointly solve image tagging (Task A), open-vocabulary object detection (Task B), and English captioning (Task C) under strict resource constraints (<=0.5B parameters and <=8 GB peak GPU memory). We present CapMap-MS-TTA, a training-free submission built on Microsoft Florence-2-base (~231M parameters), combining caption keyword mapping with multi-scale flip test-time augmentation. Task C uses the native <DETAILED_CAPTION> pathway with length/token sanitization. Task A maps the same detailed caption into the official quality/scene/event vocabularies via an expanded keyword lexicon with whole-word matching and a lightweight expand-hints stage. Task B runs Florence-2 open detection (<OD>) with multi-scale and horizontal-flip test-time augmentation (TTA), followed by label-aware non-maximum suppression (NMS). Without fine-tuning, the system improves our reproduced Florence-2 baseline from 15.16 to a best public score of 16.4815, and ranks 3rd on the final MUMU leaderboard.
### Title:
          CANTABILE: Learning Expressive Dynamics for Robotic Piano Performance
 - **Authors:** Woosik Kim, Wonhyeok Choi, Sunghoon Im
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robotic piano playing has emerged as a standard benchmark for dexterous bimanual manipulation, yet progress on it has been measured almost entirely by note accuracy -- which keys are pressed (pitch) and when (onset) -- leaving the musical dynamics essential for expressive performance neither rewarded nor evaluated. We propose CANTABILE, a dynamics-aware framework for robotic piano performance that (i) closes the score-to-contact loop by conditioning the policy on upcoming velocity goals and mapping each key's angular velocity at onset back to MIDI velocity, (ii) couples a velocity-fidelity reward with an onset-coverage reward, so that dynamics cannot be improved by omitting difficult notes, and (iii) refines a frozen dynamics-aware base policy with an alpha-scaled, finger-only residual that localizes strike-intensity adaptation away from nominal note execution. On EXPRESSIVE-51, a dynamics-rich 51-song subset of RoboPianist, CANTABILE raises Velocity F1 -- jointly measuring pitch, onset, and intensity within a +/-8 MIDI-velocity tolerance -- from 0.06 to 0.34 over the RoboPianist baseline, improves all 51 songs, more than halves matched-note velocity error, and reduces log-mel distance to reference audio by 8%. Intensity-randomized training further enables runtime control of performance intensity without retraining.
### Title:
          Macroscopic Motion Patterns from Generalized Velocity Rigidity in Multi-Agent Networks
 - **Authors:** Ronghai He, Changhuang Wan
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional graph rigidity theory enforces structural constraints in the position space, effectively restricting a multi-agent formation to a static geometric shape. In this paper, we introduce a fundamental paradigm shift by applying rigidity constraints directly to the agents' continuous-time velocity space. We propose the concept of generalized velocity rigidity, demonstrating that the macroscopic physical motion patterns of a multi-agent network are entirely dictated by the underlying static graph topology. By strictly confining the network's acceleration profile to the null space of the velocity rigidity matrix, we mathematically map the trivial motions of this null space into exact physical trajectories. Specifically, we prove that translational, rotational, and scaling trivial motions seamlessly integrate into cohesive curved flocking, synchronized helical and circular $\mathrm{SO}(d)$ orbiting, and exponential spatial homothety, respectively. Furthermore, we analyze velocity-space singularities, showing that velocity consensus induces a valid topological contraction rather than a structural failure. Finally, we provide comprehensive numerical simulations to validate these theoretical mappings, demonstrating that complex macroscopic maneuvers can be orchestrated purely through algebraic constraints in the velocity space, unlocking unprecedented spatial shape flexibility for multi-agent swarms.
### Title:
          What Counts as Strategic Reasoning? A Systematic Mapping of Chess Research on Humans, Engines, and Language Models
 - **Authors:** Paolo Ciancarini, Remo Pareschi
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Chess has long served as a model domain for studying search, expertise, decision-making, and artificial intelligence. The emergence of large language models (LLMs) has renewed the relevance of chess as a controlled environment for investigating strategic reasoning and comparing human and artificial decision-making. We present a systematic mapping study of recent research spanning human players, classical chess engines, neural and reinforcement-learning systems, LLMs, and hybrid approaches. The final map comprises 84 core study families, classified according to agent type, strategic-reasoning stages, and evaluation dimensions. The map reveals a literature strongly concentrated on situation assessment, evaluation, and action selection, while explicit planning, explanation, metacognition, and human--AI collaboration remain less explored. LLM research places particular emphasis on state representation and generalization, whereas grounded explanation appears more frequently in hybrid approaches combining language models with engines, expert knowledge, or other external structures. Two distinctions emerge that the map aggregates rather than resolves: hybrid systems differ in where and when heterogeneous capabilities combine, and evaluations that show improved human performance do not thereby establish human--AI synergy. We propose both as extensions of the mapping framework. We argue that chess provides a useful bridge between cognitive and computational perspectives on strategic reasoning, and identify explicit planning, grounded and faithful explanation, metacognitive calibration, and human--AI complementarity as directions for future research.
### Title:
          One-Step Retrieval Framework for Real-Time Sponsored Search Ads Using Hierarchical Text Representations
 - **Authors:** Tongtong Liu, Renyu Zhang, Jiayu Ding, Hongchao Guo, Xintao Yang, He Wei, Zhaoyu Li, Haiyang Wu
 - **Subjects:** Subjects:
Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Traditional retrieval systems typically use multi-stage cascading architectures (MCA), where each module is optimized independently, leading to inconsistent objectives and the premature elimination of high-potential candidates. Recent LLM-based generation methods offer end-to-end solutions but use discrete semantic identifiers (SIDs) to retrieve ads, which are not learned by the base LLM and require memorization of numerous SID-to-ad mappings during SFT, suffering from limited generalization to unseen ads, high maintenance and update costs. The one-to-one mapping between SIDs and advertisements leads to inefficient decoding. Moreover, these methods rely on a small reward model (e.g. pctr) for relevance and ranking, limiting the LLM's ability to fully assess ads' commercial value. To address these challenges, we propose A uNified Generation-discriminative-ranking reaL-time rEtrieval (ANGLE) framework. ANGLE uses LLM-generated hierarchical textual representations, which consist of commercial intent that provide high-level overviews and ad abstract that deliver fine-grained details. Additionally, ANGLE integrates retrieval, relevance, and ranking directly within a single LLM, enabling precise and efficient ranking of ads by leveraging the full capabilities of the LLM. We applied ANGLE to the real-world search scenarios, achieving a 1.81% increase in consumption and a 2.16% increase in gross merchandise volume (GMV). We also conducted offline evaluations of ANGLE and seven baselines, with ANGLE outperforming all across key metrics such as HR and ACR.
### Title:
          Beyond Quadratic Loss: The Stability Phase Diagram of Adam
 - **Authors:** Gaoxiang Tang, Huanran Chen, Ziming Liu
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Optimization and Control (math.OC); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Loss spikes are recurrent instabilities in neural-network training and can arise from multiple mechanisms. For Adam in particular, macroscopic loss spikes have been linked to optimizer dynamics, yet how its two momentum timescales govern them remains unclear. We investigate this dependence by mapping training dynamics across the $(\beta_1,\beta_2)$ plane. Across a range of model--task settings, an approximately linear boundary, $1-\beta_2=C(1-\beta_1)$, separates spiky from non-spiky dynamics, whereas a one-dimensional quadratic loss produces approximately cubic slope. A one-dimensional superquadratic loss $L(x)\propto|x|^n$ recovers the near-linear scaling and links the boundary coefficient to the effective loss exponent $n$. We further show that confident cross-entropy losses develop a core--wall landscape comprising a narrow quadratic core followed by a steep wall, which produces effective superquadratic behavior at the scale of an optimizer update. Together, these results connect Adam loss spikes to both the mismatch between momentum timescales and finite-scale superquadratic loss geometry beyond the Hessian.
### Title:
          GraphPoint: Semantic Entity Graphs and Point Trajectories for Compositional Robot Manipulation
 - **Authors:** Kang Luo, Hesheng Wang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Robot manipulation policies often struggle to generalize beyond their demonstrations, even when new instructions involve familiar objects and behaviors. When language and scenes are strongly correlated during training, a policy can learn a fixed visual-action mapping rather than respond to the requested behavior. We investigate compositional reuse at two levels: within a subtask, combining familiar entities, action types, and action modifiers; and across subtasks, reusing learned subtasks in unseen long-horizon tasks. We introduce CoMani, a benchmark with controlled splits for evaluating both capabilities. Matched initial scenes and controlled changes to a single semantic factor encourage reliance on language rather than visual shortcuts. We further propose GraphPoint, which connects semantic entity graphs to geometric control by predicting future gripper point trajectories and converting them into actions using robot geometry. The framework organizes the gripper and objects by semantic roles and conditions their interactions on action types and modifiers, while predicted progress guides transitions during execution. Experiments and ablations on CoMani validate the effectiveness of our method for instruction-dependent generalization at both levels. Code will be released at GraphPoint.
### Title:
          Video-Based Markerless Motion Capture for Clinical and Rehabilitation Biomechanics: A PRISMA-ScR Scoping Review of Validated Architectures, Clinical Readiness, and Emerging Methods
 - **Authors:** Florian Delaplace (LAMHESS, CHU), Elodie Piche (LAMHESS), Frédéric Chorin, Raphael Zory (IUF, LAMHESS)
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Medical Physics (physics.med-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Background.. Video-based markerless motion capture promises movement analysis without the cost, space and skin-marker constraints of optoelectronic systems, with particular potential for clinical and rehabilitation settings. Whether validated pipelines yet deliver clinically acceptable biomechanics, and how they relate to the underlying computer-vision research, remains unclear. Methods. We conducted a scoping review following the PRISMA extension for Scoping Reviews, with a registered protocol and searches of PubMed, Scopus and IEEE Xplore (January 2015 to February 2026; the computer-vision scan was updated to July 2026). A dual-tier design paired a primary corpus of validated biomechanical studies with a complementary, curated and deliberately non-exhaustive corpus of emerging computer-vision work, used qualitatively. We charted study characteristics, pipeline architecture, validation methods and joint-angle accuracy. Results. We included 117 studies, most published from 2024 onward and conducted on healthy adults walking in a laboratory. Pipelines formed five architectural families across monocular and multi-camera modalities; most reported raw joint angles without biomechanical refinement. Sagittal lower-limb agreement clustered around 5 to 6{\textdegree}, generally short of clinical acceptability, while out-of-plane kinematics, kinetics, and pathological or older populations were rarely validated. Emerging computer-vision building blocks (foundation-model mesh recovery, differentiable inverse kinematics, video-based kinetics) were almost absent from validated studies. Conclusions. Video-based markerless capture is not yet interchangeable with marker-based systems for clinical joint kinematics, and it remains barely validated where rehabilitation needs it most: older and pathological populations, out-of-plane kinematics, and kinetics. Mapping this evidence gap onto emerging computer-vision advances, we propose hypothesis-generating design guidelines, not a validated method, to steer the next generation of pipelines toward accessible, clinically meaningful movement analysis.
### Title:
          PASSAGE: Scaling Scene-Aligned Motion Learning for Perceptive Humanoid Traversal in Cluttered Environments
 - **Authors:** Yuxuan Ma, Zicheng Zeng, Chunlin Peng, Zhoujian Li, Zetong Zhao, Zhikai Zhang, Yunrui Lian, Han Xue, Sikai Liang, Weiyi Zhu, Mulin Chen, Chenghuai Lin, Jiayu Zeng, Yanwei An, Songan Zhang, Jiayuan Gu, Jilong Wang, Jingbo Wang, He Wang, Li Yi
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humanoid robots can step over, squeeze past, and duck under obstacles, but learning to select and coordinate these behaviors from onboard perception remains challenging. Many existing approaches rely on task-specific reinforcement-learning objectives or curated motion libraries, making broad behavioral coverage costly. We present PASSAGE, a perception-conditioned planner--tracker framework for humanoid traversal. Using virtual reality and inertial motion capture, we collect 100 h of scene-aligned human motion across 1,500 cluttered scenes. A conditional flow-matching planner generates short-horizon references from motion history, a local destination, and a robot-centric multi-layer elevation map, while a perceptive whole-body tracker executes them at 50 Hz with geometric feedback. Real-time chunking promotes inter-chunk consistency, and planner-side RL post-training under the frozen tracker further improves closed-loop performance. Without skill annotations or obstacle-specific policies, one planner--tracker pair selects and composes traversal behaviors across unseen geometries. In simulation, component ablations quantify the contribution of each stage. Across three independent training seeds, scaling captured data from 6 to 100 h increases mean contact-free success from 48.1% to 68.9% on held-out scenes, while the final model with validated scene augmentation reaches 70.3%. The fully onboard system integrates egocentric 3D LiDAR perception, online occupancy mapping, 6.25 Hz planning, and 50 Hz control on a Jetson AGX Orin; tests across 50 unseen physical layouts demonstrate traversal without prebuilt maps or offboard computation.
### Title:
          SEAM: Submap-Anchored Evidence for Lifelong LiDAR Mapping under Trajectory Deformation
 - **Authors:** Kyuwon Kim
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We propose SEAM, a LiDAR-based lifelong mapping framework. Instead of relying on a single anchor spanning the entire session, SEAM generates evidence based on a trajectory optimized with submap-level anchors, and performs dynamic object removal and change detection. Through submap-level reprojection, the generated evidence remains usable even if the trajectory is subsequently modified by a new session, eliminating the need to recompute the entire process from scratch. SEAM suppresses geometrically unreliable inter-session loop edges using a DOP-based confidence measure. Suppressing unreliable loop edges prevents alignment errors. SEAM also uses a directional voxel-wise evidence model. The model accounts for occupancy patterns that vary with ray direction. Direction-aware evidence separates dynamic objects from environmental changes more precisely. Experiments on a real construction-site dataset and a long-term multi-session dataset show that SEAM achieves higher accuracy and faster processing than existing methods.
### Title:
          Physics-based prediction, uncertainty quantification and decision-making for IN718 crystallographic texture intensity across LPBF defocus regimes
 - **Authors:** Yisheng Lu, John Riris, Jie Song, Yao Fu, Jie Chen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Materials Science (cond-mat.mtrl-sci); Computational Engineering, Finance, and Science (cs.CE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reliable prediction of crystallographic texture in laser powder bed fusion is critical for linking process conditions with anisotropic response and for qualification. However, black-box models may fail under shift and cannot distinguish weak data support from loss of physical validity. This study develops a two-stage physics-based model for <001> || BD (build direction) texture in Inconel 718. Stage 1 maps process variables to melting mode and melt pool geometry. Stage 2 predicts texture by combining an empirical physics model with a random-forest residual model. A k-nearest-neighbor weight attenuates residual corrections for poorly supported queries, while a study-specific areal beam-power-density criterion withholds predictions outside the adopted conduction envelope. Conformal intervals are evaluated on the retained physics-valid set, and SHAP and Sobol analyses assess residual sensitivity. Under a controlled leave-one-defocus-out evaluation, the physics anchor achieved R^2 = 0.778, against -0.001 for the black-box model and 0.750 for the gated hybrid. Under leave-one-group-out cross-validation, the gated hybrid reached R^2 = 0.592 against 0.538 for the black-box model. Retained-set coverage was 92.9% at a mean full width of 3.65 multiples of a uniform distribution (MUD) under grouped cross-validation and 100% at a width of 3.21 MUD under transfer to a withheld +80 mm defocus regime. An illustrative mapping produced a retained BD elastic-modulus span of 127-187 GPa. On nine conditions from a separately built sample set, the framework withheld three, attenuated three, and matched the measured ordering for the rest. Separating data applicability, physics validity, and predictive uncertainty into distinct decisions lets the framework transfer where an unconstrained model does not, and withhold predictions where no model class performs adequately.
### Title:
          SOL-SLAM: Inverse Compositional Gauss-Newton Direct Registration for Fast Sonar-Only Local SLAM
 - **Authors:** Kalvik Jakkala, Jason O'Kane
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous underwater navigation typically relies on complex and expensive multi-modal sensor suites designed to prioritize global Simultaneous Localization and Mapping (SLAM) accuracy. However, local reactive behaviors such as coarse navigation and obstacle avoidance require only local consistency---a capability that should be feasible using only a Forward-Looking Sonar (FLS), yet remains largely unaddressed, leaving a critical gap in FLS-only local SLAM. Moreover, existing acoustic SLAM frameworks predominantly rely on sparse feature extraction methods that discard substantial portions of the already information-sparse acoustic returns. To overcome these limitations, this work introduces a dense direct registration approach that aligns full acoustic intensity scans to a recursively updated local map. Real-time execution is achieved via an Inverse Compositional Gauss-Newton optimization strategy that minimizes computational overhead. Experimental evaluations show that this dense method yields significant improvements on translation error compared to sparse keypoint baselines, maintaining stable sub-meter tracking precision over wide displacement gaps. Moreover, this approach delivers odometry performance comparable to multi-sensor fusion pipelines (FLS, DVL, and IMU), bypassing expensive payload dependencies in feature-rich environments. We validate real-world applicability through AUV field trials, running the full local SLAM approach onboard an embedded, resource-constrained computer.
### Title:
          Tabular Deep Learning vs Classical Machine Learning for Urban Land Cover Classification
 - **Authors:** Muntasir Tabasum, Tanpia Tasnim, Md. Ekramul Islam, Al Zadid Sultan Bin Habib
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Urban Land Cover (ULC) classification plays a crucial role in urban planning, environmental monitoring, and sustainable development. We study this task using the ULC dataset from the UCI Machine Learning Repository, which includes tabular features derived from high-resolution aerial imagery across nine classes (e.g., roads, trees, grass, water). The dataset presents typical remote sensing challenges, including high dimensionality, heterogeneous features, and class imbalance. In a unified, reproducible pipeline, we benchmark classical machine learning models (e.g., Logistic Regression, SVM, Random Forest, XGBoost, CatBoost) against Tabular Deep Learning (TDL) models (TabNet, FT-Transformer, TabTransformer, TabSeq, and 1D CNNs). To address class imbalance, we employ weighted cross-entropy loss for TDL models and evaluate performance using accuracy, macro-precision, macro-recall, macro-F1, AUC-ROC, and confusion matrices. Our results show that while tree ensembles remain strong general baselines, TDL models can match or exceed their performance when non-linear interactions are significant and imbalance handling is effective, providing complementary advantages for urban land cover mapping. See code: this https URL
### Title:
          Probabilistic Linear Explanations
 - **Authors:** Frederic Koriche, Jean-Marie Lagniez, Chi Tran
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Formal explainability provides mathematically grounded justifications for individual predictions. However, abductive explanations often exceed human cognitive limits by involving too many features, while probabilistic relaxations have remained largely limited to categorical classification. We present a unified framework for probabilistic explainability based on sparse, anchored linear models, applicable to both binary classification and continuous regression. By mapping instances to the Boolean hypercube, our linear explanations strictly generalize subset-based approaches: they capture both the magnitude and direction of feature contributions while enforcing a prescribed sparsity budget $k$. We show that minimizing the relevance error for such explanations is \ClassNPPP-hard when the underlying model is a neural network, and we relate this intractable objective to a tractable surrogate---the fidelity error. For a parameterized family of local distributions, the relevance error of any $k$-sparse explanation is bounded by its fidelity error up to a multiplicative factor that remains small locally. We address the resulting empirical problem using two complementary approaches: a Mixed Integer Programming (MIP) formulation that yields provably optimal empirical solutions while maintaining polynomial sample complexity, and a polynomial-time Iterative Hard Thresholding (IHT) algorithm with provable approximation guarantees. Empirical evaluations show that, unlike state-of-the-art baselines such as LIME and MAPLE, our explanations satisfy both the anchoring and sparsity constraints by construction, while consistently achieving lower relevance error.
## Keyword: localization
### Title:
          Reflect, Revise, Reuse: Training-Free Skill Evolution for GUI Agents
 - **Authors:** Bofan Chen, Boxuan Zhang, Fei Tang, Zhengxi Lu, Yong Du, Tongbo Chen, Weiming Lu, Jun Xiao, Yueting Zhuang, Yongliang Shen
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 GUI agents execute long-horizon tasks on dynamic graphical user interfaces, where pop-ups, delayed loads, and relocated widgets routinely invalidate plans fixed before execution. Recent agent-skill frameworks encapsulate reusable procedural knowledge to mitigate this, yet existing skill designs are largely developed without targeting GUI execution dynamics and treat skills as static artifacts produced before deployment rather than living procedural knowledge that improves through it. We argue that what GUI agents need is not better static skills, but skills that can be revised from execution feedback at deployment time, without additional training. We propose \textbf{EvoSkill-GUI}, a training-free framework in which each skill is a structured multi-file package containing retrieval metadata, executable plans, backup localization, failure-recovery rules, accessibility utilities, and failure cases. EvoSkill-GUI operates through a \textbf{\emph{reflect-revise-reuse}} loop: the executor performs instant in-rollout revisions, an isolated critic diagnoses failed trajectories under strict information isolation, and the executor edits specific skill files through a restricted tool interface. Across MobileWorld, AndroidWorld, and OSWorld, three mainstream GUI benchmarks spanning mobile and desktop platforms, EvoSkill-GUI consistently improves multiple base models without any training, with maximum gains of $+16.2\%$, $+6.0\%$, and $+10.5\%$ respectively, and evolved skill libraries continue to benefit related tasks rather than being rebuilt from scratch. Our code is available at this https URL.
### Title:
          DRT&R: Direct Radar Teach & Repeat
 - **Authors:** Alexander Krawciw, Daniil Lisus, Cedric Le Gentil, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Radar-based navigation is appealing for its robustness to adverse conditions involving airborne particles, such as precipitation, dust, fog, and smoke, that can cause lidar-based systems to fail. Recently, direct methods that retain and use the entire radar scan rather than sparse points have improved on-road global localization performance. However, they have yet to be deployed in off-road environments or in closed-loop systems. Additionally, even direct global maps may lose information: their global nature leads to a smoothing out of viewpoint-dependent radar artifacts, which can provide pose information when mapping and localization occur along similar trajectories. This paper introduces Direct Radar Teach & Repeat (DRT&R): a direct spinning radar-based navigation stack that maximizes the amount of retained information by combining direct radar processing with local mapping. DRT&R yields state-of-the-art (SOTA) localization performance in both on-road and off-road environments. Using 344 km of on-road data and 20 km of off-road data, DRT&R is able to localize to within 4 cm in most on-road and off-road conditions, and 12 cm in geometrically degenerate and sparse environments. DRT&R is also evaluated autonomously in closed loop with an MPC controller for more than 10 km using a Clearpath Warthog off-road vehicle, demonstrating that it runs in real time and achieves SOTA tracking performance for off-road radar navigation.
### Title:
          AgenTeeth: A Model-Agnostic Framework for Suppressing Hallucination in Frozen Vision-Language Models on Dental X-Rays via Tool Evidence Injection
 - **Authors:** Ahmed Rafid, Fariya Ahmed, Rumman Adib, Mehedi Ahamed, Ajwad Abrar, Tareque Mohmud Chowdhury
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision-language models (VLMs) remain largely unreliable on panoramic dental radiographs and can rely on learned anatomical priors rather than evidence in the image. This is particularly problematic for tooth localization and spatial reasoning, and fine-tuned dental VLMs can retain the same spatial biases. We present AgenTeeth, a model-agnostic, tool-augmented framework that grounds frozen VLMs using seven specialized dental vision experts. A question-aware orchestrator selects the relevant tools, whose detections are mapped to FDI tooth numbers or anatomical regions and returned as structured findings together with annotated image overlays. A fresh synthesis call then answers the question using this evidence, without fine-tuning the underlying VLM. On MMOral-OPG-Bench, AgenTeeth improves four backbone VLMs by 12.9-23.0 percentage points over their baselines. Our strongest configuration reaches 65.66% on open-ended VQA, compared with 45.35% for OralGPT-Plus. The advantage also holds at matched scale: a frozen Qwen2.5-VL-7B-Instruct with AgenTeeth reaches 48.11%, exceeding OralGPT-Plus built on the same backbone after supervised fine-tuning and reinforcement learning for tool use. We release the framework, all seven expert models, and a dentist-annotated dataset for alveolar bone-loss detection in panoramic radiographs.
### Title:
          CALIPER: Metric-Grounded Model-Free Recognition of Visually Similar Industrial Parts
 - **Authors:** Alankrit Gupta, Chenxi Tao, Seung-Kyum Choi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fine-grained recognition of visually similar industrial parts is challenging when classes differ primarily in physical dimensions. Normalizing detected object crops to a fixed input size suppresses absolute scale, while CAD models and large class-specific datasets may be unavailable in evolving industrial inventories. We present CALIPER, a model-free RGB-D framework that couples support-based appearance matching with metric size evidence. Each training class is onboarded from a single turntable RGB-D video and one to two labeled real images; 3D reconstruction provides novel-view appearance support, while aligned depth yields a class-specific metric size profile. At inference, a coarse YOLOv8n-seg model localizes parts, and a frozen DINOv2 backbone with an episodically trained embedding head performs fine-grained support matching. Margin-conditioned metric fusion activates probabilistic size evidence only for appearance-ambiguous decisions. New classes are enrolled from a small RGB-D support set without updating network parameters. We evaluate CALIPER on 18 visually similar industrial parts: 16 classes are used for training, while two screws are reserved for training-free enrollment. CALIPER achieves 88.2% closed-set accuracy with 99.8% localization recall and 85.7% overall accuracy after 10-shot enrollment of the two unseen screws. Metric fusion improves unseen-class accuracy by up to 37.4 percentage points without statistically significant degradation of the original inventory. Robot-arm deployment identifies 17/18 parts without deployment-specific retraining.
### Title:
          Co-occurrence-Aware Quadratic Assignment for Local Feature Matching in Simultaneous Localization and Mapping
 - **Authors:** Yutaka Yamada, Yohei Hamakawa, Yutaro Ishigaki, Masaya Yamasaki, Kosuke Tatsumura
 - **Subjects:** Subjects:
Emerging Technologies (cs.ET)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Local feature matching, which associates keypoints in two images as keypoint pairs, is fundamental to Visual Simultaneous Localization and Mapping (Visual SLAM). Nearest Neighbor (NN) search is commonly used for keypoint matching, but it has difficulty selecting correct keypoint pairs when multiple candidates have similar costs. To improve matching accuracy, this paper proposes a keypoint matching method that considers the pairwise co-occurrence of two keypoint pairs. The keypoint matching is formulated as a quadratic assignment problem, which is an NP-hard combinatorial optimization problem, making it difficult to solve quickly on conventional computers. Recently, Ising machines have been developed as computing devices capable of solving hard combinatorial optimization problems. Using a simulated bifurcation based Ising machine, the proposed method improved matching accuracy by approximately 8 percentage points over a conventional method on the HPatches dataset. Furthermore, we integrated the proposed method into ORB-SLAM3, a representative academic Visual SLAM system, and achieved a 3.78-fold improvement in absolute pose error (APE) and a 2.85-fold improvement in relative pose error (RPE) on the KITTI dataset scenes where multiple same shape objects are repeatedly arranged, which are challenging for accurate self-pose estimation by the original ORB-SLAM3.
### Title:
          Demystifying Gate-Level Localization of RTL Trojans
 - **Authors:** Navid Nader Tehrani, Azadeh Davoodi, Rasit Onur Topaloglu
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hardware Trojans are malicious modifications that compromise functionality or leak sensitive data. They pose a severe threat, particularly when inserted at the Register Transfer Level (RTL). After synthesis, these Trojans are often concealed by optimizations in gate-level netlists. Recent efforts, including the ICCAD 2025 contest, emphasize golden-chip-free detection using machine learning (ML) on labeled netlists. In this work, we show that RTL Trojans exhibit stable structural and signal-flow patterns post-synthesis, enabling effective detection through targeted heuristics rather than generic ML feature learning. We propose LoRD, a lightweight heuristic-based approach that exploits these distinctive subgraph signatures, achieving near-perfect detection and localization on the contest testcases. Com- pared to a transformer-based ML baseline and top five teams, LoRD achieves on-average a score of 2.957 (out of 3) for Trojan- implanted designs without the data and tuning overhead.
### Title:
          Experimental Settings in LLM-Based Program Repair: A Study of Inputs, Tool Access, Feedback, and Validation
 - **Authors:** Xushu Dai, Yicheng Cai, Nanqing Luo, Pei-Yu Tseng
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Evaluations of automated program repair (APR) systems commonly report the benchmark, the number of repaired defects, and the tests used for final patch validation, but these items no longer fully specify the repair task presented to a system. Recent LLM-based systems differ in the information supplied before repair, the repository and testing operations permitted during repair, and the feedback returned after unsuccessful attempts, allowing the same benchmark to instantiate substantially different repair tasks ranging from localized patch generation to repository-level diagnosis and iterative repair. We present a framework for explicitly specifying the experimental settings associated with reported APR results. We analyze reported experimental settings from systems evaluated on Defects4J and SWE-bench and characterize each result by its task unit, fault-localization assumptions, initial input, tool access, repair-time feedback, final validation, and resource budget. Our analysis shows that benchmark identity alone is insufficient to reconstruct the evaluated task or determine the appropriate scope of comparison across reported repair rates. We therefore introduce a machine-readable schema for specifying each experimental setting to improve reproducibility and make the scope of cross-system comparisons explicit.
### Title:
          SetPlanner: A Lightweight Plug-in Point-Set Planner for Frozen SAM
 - **Authors:** Dawei Yan, Yuezhe Yang, Menglan Ruan, Chunfeng Yang, Yudong Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Segment Anything Models provide reusable priors, yet they require user prompts and cannot support fully automatic instrument segmentation. Automatic prompting is difficult for thin, articulated, reflective, and partly occluded tools, where several configurations can be valid. We formulate automatic prompting as lightweight point-set planning and isolate the point source under a frozen pathway. To this end, we present SetPlanner, a 1.52M-parameter plug-in point-set planner for frozen SAM. The plug-in preserves SAM's point-prompt interface and enables reuse across backbones. SetPlanner plans complete unordered K-point sets from geometry-aware targets with a permutation-aware conditional flow. SAM decodes eight candidates; their consensus readout yields a ground-truth-free prediction. Across three endoscopic datasets, SetPlanner wins all six transfer routes over a LoRA-adapted system. Under our frozen-pathway protocol, SetPlanner reaches 0.934 Dice on Kvasir-Instrument and recovers 96% of a 44.4-point localization gap, while candidate disagreement ranks low-Dice cases at AUROC 0.969.
### Title:
          CLASP: A Cluster-Level Autonomous Selective Picking Robot with a Soft Rolling-Band Gripper for Fresh-Market Blueberry Harvesting
 - **Authors:** Yixuan Xia, Yilin Cai, Natalia Belen Espinoza, Changying Li, Zilfina Rubio Ames, Xin Zhang, Yue Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Fresh-market blueberries require selective, gentle picking, which is labor-intensive and expensive. Over-the-row machine harvesters are fast but non-selective, bruising mixed-ripeness fruit and limiting yield to the processing market. Selective robotic harvesters typically target individual fruits rather than fruit clusters, which limits harvesting efficiency for small, densely clustered blueberries. This paper presents CLASP, a Cluster-Level Autonomous Selective Picking robot with a Soft Active Rolling-Band Gripper (SARB-Gripper). Two compliant bands envelop the cluster and roll against the fruit, drawing mature berries off in sequence, while closed-loop regulation of the pulling force keeps the applied load below the immature detachment threshold. A global-to-local perception pipeline pairs an eye-to-hand camera for global cluster detection and target selection with an eye-in-hand camera for local localization and cluster orientation estimation. Field measurements confirm a clear detachment-force separation between mature and immature fruit, and the SARB-Gripper reproduces a commanded pulling force to within \SI{3.7}{\percent}, enabling selective harvesting at the cluster level. In end-to-end field trials, CLASP autonomously grasped 23 of 25 presented clusters (\SI{92}{\percent}). With the component cost of approximately \$3326 per unit, CLASP offers a scalable approach to selective cluster-level harvesting for fresh-market blueberries.
### Title:
          Finder: Agentic Closed-Loop Object Finding for Embodied Grounding
 - **Authors:** Shixiong Xu, Zhiyuan Chen, Song Ding, Rui Luo, Xiaowei Liang, Dongxu Miao, Zhiying Du
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Finding the object referred to by language in a partially observed 3D scene is a core capability for embodied agents. Existing approaches either couple object search with online exploration, which can be costly when relevant observations have already been captured, or query pre-built open-vocabulary maps and scene graphs in a static, one-shot fashion. We present Finder, an agentic closed-loop object-finding primitive for embodied grounding. Instead of treating grounding as passive retrieval from a fixed scene representation, Finder maintains a typed loop state that links query-conditioned planning, scoped evidence gathering, candidate verification, and accept/continue/abort control. When evidence is incomplete or ambiguous, the loop can redirect subsequent perception and comparison rather than simply returning the top retrieved object. On open-vocabulary embodied Object Retrieval in Habitat/HM3D and real-world RGB-D scenes, Finder improves the averaged 1m success rate by 15.75 points over strong baselines. The same primitive also transfers to sequential object grounding and embodied object-centric question answering, improving spatial and temporal localization without changing the inner grounding protocol. Project page: this https URL.
### Title:
          Characterizing Refraction-Induced Ranging Bias in Underwater Collaborative Localization
 - **Authors:** Timothy Kogucki, Alan Papalia
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work studies how refraction-induced bias on acoustic ranging affects multi-agent collaborative localization in a range of oceanographic conditions and spatial scales. While multi-agent range-aided navigation, which uses range measurements to either fixed infrastructure or other agents, is a promising solution to the challenges of large-scale underwater localization, its accuracy depends strongly on the quality of range measurements. Sound speed variability induces refraction (bending) of acoustic rays, yet, for algorithmic tractability, standard sensor fusion pipelines assume straight-line propagation. This refraction systematically biases range measurements to be longer than the straight-line assumption predicts. However, the effects of this bias on multi-agent collaborative localization on kilometer scales remains unexplored. We present a series of simulated experiments with several agents operating over kilometer scales. The simulation uses HYCOM reanalysis data to recreate realistic oceanographic conditions, ray tracing to generate refraction-informed ranges, and a centralized multi-agent factor graph estimator to quantify the resulting measurement bias on estimated trajectories. Preliminary results indicate that refraction-induced bias can induce significant degradation of estimated trajectories, particularly in regions with sharp sound-speed gradients. We also share the simulation environment to support further studies this https URL.
### Title:
          ReRadar: Robust Radar Global Localization via Rotation-Equivariant Descriptor Learning
 - **Authors:** Duc Manh Nguyen, Truong Giang Dao, Gia Nghiem Luong, Viet Trung Hoang, Anh Quang Nguyen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Global localization with scanning millimeter-wave radar remains challenging because place-recognition descriptors often discard spatial structure needed for accurate pose retrieval. We present ReRadar, a radar global localization pipeline that extracts rotation-equivariant intermediate features using steerable convolutional neural networks, forms rotation-invariant descriptors through group pooling and NetVLAD aggregation, and combines descriptor retrieval with landmark-based matching to estimate the robot's three-degree-of-freedom (3-DoF) pose. Across fixed database-query evaluations, ReRadar with target-dataset adaptation achieves 99.37% Recall@1 on OORD Bellmouth, 91.44% Recall@1 with 80.99% F1_max on Mulran DCC01, and 99.38% Recall@1 on falling-snow Boreas sequence. Without target-dataset data, the cross-dataset model reaches 98.07% Recall@1 on OORD, performing comparably to the evaluated state-of-the-art methods.
### Title:
          Multi-View Mixture-of-Experts with Vision-Language Reranking for Cross-View Object Geo-Localization
 - **Authors:** Xuyu Fan, Qi Ming, Zhu Han, Liuqian Wang, Siyuan Cao, Xiaohan Zhang, Xudong Zhao, Mingjing Zhao, Yuhan Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cross-view object geo-localization (CVOGL) locates a target in satellite imagery using drone or street-view queries. Existing methods train separate detectors for each viewpoint, leading to parameter redundancy and impeding cross-view knowledge sharing. Moreover, top-ranked satellite candidates are often visually similar, so visual appearance and categorical labels alone are insufficient to resolve such ambiguity. To address these, we propose MVLGeo, an efficient framework designed to unify multiple viewpoints and reduce model redundancy. First, we introduce environmental contextual text from the query view as cues to distinguish visually similar candidates via Vision-Language Reranking (VL-Rerank). Second, we design a multi-view Mixture-of-Experts architecture (MV-MoE) with a shared encoder and view-specific experts to reduce redundancy and promote knowledge sharing, while cross-view contrastive learning aligns their representations for consistency. Third, we introduce an adaptive elliptical prior (ESAM-Prior) as auxiliary positional encoding for anisotropic geometric perception. Extensive experiments on the CVOGL benchmarks confirm that MVLGeo, as a unified model for multiple query viewpoints, achieves state-of-the-art performance, demonstrating robustness to input degradation and generalization across viewpoints. Code and models will be available on GitHub to facilitate future work.
### Title:
          WISE: A Lightweight, Weakly-Supervised Model for Onboard Fire Smoke Detection and Localization
 - **Authors:** Sha Lu, Yu Sun, Liang Zhao, Jixue Liu, Lin Liu, Jiuyong Li, A. K. Qin, Alejandro Mousist, Stefan Peters
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wildfire smoke detection from satellite imagery is critical for early warning and rapid response. For onboard satellite deployment, detection systems must operate under strict memory and latency constraints while providing spatially informative outputs for downstream decision-making. Existing tile-level classification methods are computationally efficient but lack spatial localization, whereas pixel-level segmentation approaches provide detailed masks yet are typically too computationally demanding for real-time onboard execution. To address this gap, we propose WISE (Weakly-supervised Inference-efficient Smoke Extraction), a deployment-oriented framework for onboard fire smoke detection and localization. WISE leverages only tile-level annotations through a teacher-student distillation strategy, where an offline teacher provides soft spatial supervision to a lightweight WISE-Student optimized for efficient onboard inference. The student jointly predicts tile-level smoke presence and smoke probability maps within a single forward pass, enabling spatially informative detection under strict computational constraints. WISE was evaluated through in-orbit execution aboard the ISS-mounted IMAGIN-e payload. Three model variants achieve average inference times of 0.10 s, 0.14 s, and 0.26 s per tile, indicating near-real-time per-tile inference within onboard resource limits. Ground-based experiments on Landsat 5 and Landsat 8 imagery further indicate effective detection and spatially informative localization. The best-performing variant achieves a mean tile-level F1 score of 0.964 and a mean pixel-level F1 score of 0.750 across 10 runs, while containing only 0.12M parameters and requiring approximately 3 GFLOPs. Together, these results indicate that WISE is a practical candidate for low-latency wildfire smoke monitoring from space under onboard resource constraints.
### Title:
          From Pixels to Semantics: Edge AI for UAV-Based Critical Infrastructure Inspection
 - **Authors:** Reza Farahani, Naser Hossein Motlagh, Zoha Azimi, Christian Timmerer, Lorenzo Carnevale, Sasu Tarkoma, Schahram Dustdar
 - **Subjects:** Subjects:
Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Critical infrastructure assets such as bridges, tunnels, dams, and power line networks require timely and scalable inspection. While conventional manual inspection remains costly and hazardous, unmanned aerial vehicle (UAV)-based inspection has emerged as an efficient alternative for monitoring difficult-to-access structures. Existing UAV inspection pipelines have evolved from cloud-centric offline processing toward edge-based perception using lightweight object detectors such as YOLO for real- time defect localization. This article explores the transition toward fully edge-native semantic inspection powered by lightweight vision language models (VLMs), where UAVs move beyond object detection toward contextual structural understanding. It categorizes existing UAV inspection architectures, identifies their key system challenges and architectural requirements, and experimentally assesses the feasibility of semantic edge intelligence on NVIDIA Jetson UAV-class hardware using the COCO-Bridge dataset. The evaluation integrates a fine-tuned YOLO-26M for object localization and a lightweight SmolVLM-256 for semantic reasoning. Finally, it outlines future directions toward agentic, autonomous, trustworthy, and collaborative semantic UAV inspection across the edge-cloud continuum.
### Title:
          Divide and Conquer: Mixture-of-Bottleneck Experts in Informative Ordinal Space for Video-based Multimodal Sentiment Analysis
 - **Authors:** Ronghao Lin, Qiaolin He, Zefeng Lu, Yichu Liu, Li Huang, Sijie Mai, Haifeng Hu, Yap-peng Tan
 - **Subjects:** Subjects:
Multimedia (cs.MM); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video-based Multimodal sentiment analysis (MSA) must handle information from text, audio, and image sequence in human speaking videos, yet current methods often fail to integrate modalities with task awareness. Most models treat video sentiment prediction as a single task, overlooking its ordinal nature, and their fusion strategies struggle to capture diverse unique and synergic cues across modalities. To address these limitations, we adopt a divide-and-conquer perspective by reformulating MSA as an ordinal regression problem and decoupling it into polarity recognition and intensity prediction. Driven by information theory, we introduce a Mixture-of-Bottleneck (MoB) framework that assigns different latents to polarity- and intensity-specific experts for different modalities. With the learning of information bottleneck, each expert learns compact and task-relevant representations while filtering out redundancy and noise. A multimodal bottleneck routing fusion module then fuses these expert latents with hard mining strategy, guiding the prediction in the ordinal sentiment space. Extensive experiments on 4 MSA datasets and 4 language models show that MoB effectively leverages informative latents from diverse modalities and captures general sentiment structure. Beyond stronger performance, MoB comprehensively captures fine-grained intra- and inter-modal dynamics, enabling more trustworthy localization of nuanced video sentiment signals.
### Title:
          STUNet-Fusion: Spatiotemporal Needle-Tip Localization in Ultrasound Video via Multi-Channel Motion Fusion
 - **Authors:** Chia-Chi Hsu, Chia-Hsuan Hsu, Che-Chou Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Needle-tip localization in ultrasound remains challenging because the needle may appear weak, discontinuous, or partially invisible, while imaging artifacts and anatomical structures can produce similar responses. To address this problem, we propose STUNet-Fusion, a spatiotemporal framework for needle-tip localization in ultrasound videos. The proposed method formulates the input as a tri-channel spatio-temporal fusion tensor, comprising grayscale appearance, grid-based motion feature, and raw frame difference. A shared ResNet-34 encoder extracts spatial features, ConvLSTM integrates temporal dependencies, and a U-Net decoder reconstructs a dense probability heatmap. The final coordinates are extracted via a soft-argmax operation to achieve sub-pixel localization accuracy. Experimental results demonstrate that this spatiotemporal fusion strategy significantly improves localization robustness compared to conventional baselines.
### Title:
          RankGround: Efficient High-Resolution GUI Grounding via Lightweight Reranker-Guided Crop Selection
 - **Authors:** Liyang Fan, Xinping Bi, Yitai Li, Shuaimin Li, Hui Li, Min Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Computation and Language (cs.CL); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graphical User Interface (GUI) grounding is a fundamental perception task for multimodal agents, enabling them to interpret natural language instructions and interact with digital interfaces. Existing methods face a fundamental trade-off between accuracy and efficiency: direct full-image inference often fails to capture small or visually similar UI elements, while multi-crop strategies improve localization at the cost of multiple expensive Vision-Language Model (VLM) calls per query. To address this challenge, we propose RankGround, a two-stage framework that achieves accurate GUI grounding with a single VLM call per query. Central to our approach is GroundRanker, a lightweight multimodal reranker that identifies the most promising crop from a dense candidate set. Because no off-the-shelf ranking dataset is available, we construct ranking supervision data from existing grounding datasets. A strict containment criterion and boundary-aware positive augmentation improve alignment and spatial coverage in cluttered layouts. GroundRanker is then trained with a two-stage curriculum: a pointwise objective first learns coarse containment, and a listwise objective refines subtle semantic and spatial distinctions among visually similar crops. Experimental results show that RankGround consistently outperforms strong baselines while reducing computational cost. It achieves 1.4 times faster inference and improves localization accuracy by 5.5% on average over the second-best method across all backbones and screen scales, establishing a new state of the art in both efficiency and precision for GUI grounding.
### Title:
          Active perception for robotic harvesting: 3D reconstruction and localisation of tomatoes hidden within clusters in a Mediterranean greenhouse
 - **Authors:** Fernando Cañadas-Aránega, Rowan Border, José C. Moreno, José L. Blanco-Claraco
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automating robotic harvesting in intensive agriculture within Mediterranean greenhouses requires overcoming significant challenges related to the geometric complexity of plants and occluded fruits. Although existing literature offers solutions targeting crops that grow in isolation (e.g., apples, sweet peppers, or peaches), the fundamental challenge lies in cluster-growing vegetables, where fixed sensors mounted on robotic systems fail to detect fruits hidden behind the visible surface. To address this limitation, this study presents a comprehensive pipeline for the 3D reconstruction and precise localization of each fruit within a cluster, including heavily occluded instances. The proposed methodology is structured into five sequential stages: i) point cloud acquisition using the AgriSEE Next Best View (NBV) active planner; ii) stochastic noise filtering via Statistical Outlier Removal (SOR); iii) surface classification and segmentation using Region Growing (RG); iv) isolation and recovery of occluded fruits through Density-Based Spatial Clustering of Applications with Noise (DBSCAN); and v) 3D pose estimation (position and orientation). This approach extracts the complete cluster geometry, ensuring the reliable identification of partially hidden tomatoes. Evaluated across multiple scenarios with varying occlusion levels within a simulation framework rigorously validated against real-world conditions, the system achieves a precision exceeding 90\%, an average recall of 82.8\%, and a mean Intersection over Union (mIoU) of 80.7\%. Furthermore, it demonstrates high repeatability in centroid estimation with a Root Mean Square Error (RMSE) of merely 4.2~mm, verifying its technical feasibility and high accuracy for autonomous harvesting operations.
### Title:
          DISTA-Net++: Rethinking Infrared Small Target Unmixing Beyond Sub-Pixel Separation
 - **Authors:** Mengze Xu, Zhu Liu, Weidong Sheng, Boyang Li, Yimian Dai, Ming-Ming Cheng, Jian Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Long-range infrared imaging frequently confronts dense target clusters whose diffraction-limited signatures merge into a single indistinguishable blob, concealing the number, sub-pixel positions, and radiant intensities of the underlying sources. While deep learning has advanced general object detection, resolving such Closely-Spaced Infrared Small Targets (CSIST) remains largely unexplored, owing to a systemic infrastructure void and a fundamental paradigm mismatch. The dominant formulation, which reduces unmixing to a blind, discrete sub-pixel separation, is inherently insufficient: without semantic guidance, the ill-posed inverse problem admits ambiguous solutions plagued by false and missed detections, while grid-based discretization locks predictions onto fixed lattice centers, chaining precision to prohibitively expensive grid refinement. We argue that CSIST unmixing should instead be informed and continuous. To ground this paradigm shift, we establish the first comprehensive open-source ecosystem for the field, comprising the large-scale CSIST-100K benchmark, a tailored metric suite, and the GrokCSO toolkit. Upon this foundation, we propose DISTA-Net++, which anchors a dynamic deep unfolding backbone with two synergistic mechanisms: a Count-Guided Prior that injects the global target count as an explicit semantic constraint to regularize the solution space, and a Continuous Coordinate Rectification that regresses off-grid offsets to decouple localization accuracy from grid resolution. Extensive experiments validate our paradigm: even under the most economical 3x division, DISTA-Net++ surpasses 7x-division state-of-the-art methods by 16.15% in CSO-mAP and 62.96% in count accuracy at merely one-sixth of their computation, demonstrating that unmixing precision need not be purchased with finer discretization. The complete ecosystem is available at this https URL.
### Title:
          SOL-SLAM: Inverse Compositional Gauss-Newton Direct Registration for Fast Sonar-Only Local SLAM
 - **Authors:** Kalvik Jakkala, Jason O'Kane
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Autonomous underwater navigation typically relies on complex and expensive multi-modal sensor suites designed to prioritize global Simultaneous Localization and Mapping (SLAM) accuracy. However, local reactive behaviors such as coarse navigation and obstacle avoidance require only local consistency---a capability that should be feasible using only a Forward-Looking Sonar (FLS), yet remains largely unaddressed, leaving a critical gap in FLS-only local SLAM. Moreover, existing acoustic SLAM frameworks predominantly rely on sparse feature extraction methods that discard substantial portions of the already information-sparse acoustic returns. To overcome these limitations, this work introduces a dense direct registration approach that aligns full acoustic intensity scans to a recursively updated local map. Real-time execution is achieved via an Inverse Compositional Gauss-Newton optimization strategy that minimizes computational overhead. Experimental evaluations show that this dense method yields significant improvements on translation error compared to sparse keypoint baselines, maintaining stable sub-meter tracking precision over wide displacement gaps. Moreover, this approach delivers odometry performance comparable to multi-sensor fusion pipelines (FLS, DVL, and IMU), bypassing expensive payload dependencies in feature-rich environments. We validate real-world applicability through AUV field trials, running the full local SLAM approach onboard an embedded, resource-constrained computer.
### Title:
          Automated Dental Caries Segmentation in Panoramic Radiographs Using Dual-Stage Deep Learning
 - **Authors:** Jihun Kim, Kyeonghun Kim, Jong-yeol Lee, Yeongseok Seo, Dohyun Chun
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Early detection of dental caries remains challenging due to limitations in traditional diagnostic methods, particularly for proximal lesions in posterior teeth. Deep learning models show promise for automated caries detection but face scalability constraints due to requirements for large volumes of expertly annotated training data. This study presents a dual-stage deep learning framework combining Faster R-CNN for tooth localization with U-Net for pixel-wise caries segmentation in panoramic radiographs. We developed a systematic transformation pipeline to convert large-scale polygon-annotated datasets into high-resolution binary segmentation masks, enabling pixel-wise supervised learning. The framework was trained using both expert-verified datasets and algorithmically processed labels from 3,000 panoramic images. Our approach achieved robust performance with an IoU of 0.9013, Dice coefficient of 0.9482, Recall of 0.9433, and Precision of 0.9774, demonstrating superior accuracy compared to existing methods while significantly reducing false-positive rates. The dual-stage framework effectively addresses data annotation bottlenecks in dental AI applications and demonstrates potential for scalable, automated caries detection systems that can improve diagnostic consistency and support clinical decision-making.
## Keyword: transformer
### Title:
          DANTINOX: A Unified Framework for Multi-Paradigm Language Modeling
 - **Authors:** Marco Simoni, Aleksandar Fontana, Giulio Rossolini, Andrea Saracino
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Language generation research increasingly spans three paradigms: autoregressive decoding, discrete masked diffusion, and continuous flow-matching. Comparing them is difficult because each lives in a separate codebase, so measured differences often reflect implementation details rather than the paradigms themselves. We present DantinoX, an open-source JAX/Flax library in which a single modular Transformer backbone serves all three paradigms. Switching the generation paradigm, attention mechanism, or hardware topology requires only a configuration change, while the backbone architecture, tokenizer, initialization strategy, and training infrastructure remain consistent. This enables controlled cross-paradigm comparisons within one API for training, streaming inference, and benchmarking.
### Title:
          Selective Prediction and Uncertainty-Aware Referral for Pap Smear Classification
 - **Authors:** Nisreen Albzour, Sarah S. Lam
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deep learning models for cervical cytology are almost always evaluated as if every prediction must be acted upon, yet a screening system deployed alongside a cytopathologist need not classify every slide: it can defer the cases it is least certain about. Evaluating such a system requires asking not only how often it is correct, but whether its confidence ranks its errors to the bottom. This paper studies selective prediction and uncertainty-aware referral on the Herlev Pap smear dataset under a binary Normal-versus-Abnormal formulation. Two lightweight transformer backbones (Swin-Tiny, TinyViT-5M) are fine-tuned on Herlev from ImageNet-pretrained weights with weighted random sampling, calibrated by post-hoc temperature scaling fit on a held-out calibration subset, and compared against a soft-voting ensemble of both models. Discrimination is reported alongside expected calibration error (ECE) and, as the primary endpoint, the area under the risk-coverage curve (AURC). No statistically significant difference was detected between the two configurations in accuracy or macro-F1, yet the ensemble halves AURC (0.0022 vs. 0.0045, a 51.8% reduction, lower in all five folds) and extends the coverage at which zero errors are made from 18.3% to 72.8% of the pooled test predictions. The same ensemble is nonetheless worse calibrated in absolute terms (ECE 0.0339 vs. 0.0247) and produces more false negatives (14 vs. 10). These results separate two properties that are frequently conflated: the ability to rank predictions by trustworthiness, and the accuracy of the confidence values themselves. Ensembling improves the former while degrading the latter, and the former directly governs the observed risk-coverage tradeoff, whereas the latter governs the interpretation of the reported confidence values.
### Title:
          WARD: Runtime Workload-Adaptive Vision TRansformer Framework for Dependable Edge AI
 - **Authors:** Mahdi Taheri, Pramit Kumar Bhaduri, Mohammad Masoumi, Ali Mahani
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Edge-deployed AI operate under dynamically changing power budgets, reliability requirements, and input distributions, requiring continuous adaptation. Such conditions arise in long-running edge AI applications, including autonomous systems, industrial monitoring, and satellite onboard intelligence. Existing fault-tolerant methods assume static operating conditions, whereas continual learning techniques neglect concurrent hardware faults during online adaptation. Moreover, the practical deployment of runtime-adaptive reliability frameworks on programmable AI accelerators remains largely unexplored. This paper presents WARD, a runtime-adaptive Vision Transformer framework that combines channel-wise subnetwork partitioning, reliability-aware continual learning, and dynamic operating-mode scheduling to jointly optimize performance, fault tolerance, and adaptation according to runtime conditions. Two physically isolated subnetworks execute under four operating modes (i.e. Full-Precision Mode, Low-Power Mode, High-Reliability Mode, and Adaptive Mode) that dynamically adjust computational cost and reliability while ensuring uninterrupted inference for real-time requirements. To validate the practical deployability of the proposed framework, WARD is implemented on a lightweight FPGA-based accelerator extended with runtime hardware support for mode scheduling and resource management. Experimental results demonstrate that the proposed split architecture achieves a network-level failure rate of only 1.79% under high Bit Error Rates. The hardware implementation incurs less than 5% area overhead and supports runtime mode transitions within few clock cycles, demonstrating that adaptive reliability management can be integrated into programmable edge AI accelerators with negligible implementation overhead.
### Title:
          Where Grokking Happens: Distributed Utility and Fourier Recoding Without a Module Switch
 - **Authors:** Dekun Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Where in a Transformer is the change from memorization to generalization functionally expressed? We introduce Transition Games--behavior-aligned exact activation games with paired non-generalizing controls--and find distributed utility gain with a prospective block-0 attention bias; selected degree-two modes account for 67--92% of its addition contrast across replacement games, and a disjoint exact path study confirms that block-1 MLP mediates more of their effect than all other tested downstream paths in 12/12 pairs. The sharper "MLP memorizes, attention generalizes" prediction instead reverses (-.331 bits/example at the memory anchor; 0/12 in the predicted direction), while routing onset, global rank collapse, and a prime-invariant architecture ridge also fail, identifying grokking here as spectral recoding of an existing distributed circuit rather than a module switch.
### Title:
          Not All Patches Are Equally Forgettable: Spatially Localized Domain Unlearning in Vision-Language Models
 - **Authors:** Akanksha Singh, Vinod K. Kurmi
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pre-trained vision-language models (VLMs) exhibit strong cross-domain recognition performance even without additional training. However, this robustness can also preserve undesirable domain-specific behavior, as domain-related and semantic information often remain entangled within the learned representation space, making selective domain unlearning challenging. Existing approaches typically address this problem through latent-space disentanglement and prompt- or feature-level interventions, without directly attributing and attenuating individual patch-token contributions. However, here we suggest that rather than uniformly suppressing the full representation, it may be more effective to exploit the spatial structure of vision transformers to localize and suppress patch regions that contribute disproportionately to forget-domain prediction. Patches that strongly influence forget-domain prediction may not be equally important for semantic recognition, suggesting that forgetting should be guided according to the domain contribution of different visual regions. Specifically, we propose a two-stage patch-selective framework that first estimates patch-level domain sensitivity and then selectively attenuates patches whose contribution to forget-domain prediction is stronger than their semantic utility. We evaluate our framework on Office-Home, Mini DomainNet, and DomainNet. Experimental results demonstrate improved forgetting-retention tradeoffs compared to prior methods while improving retained-domain recognition by up to 3.8\%. Additional evaluations under visually overlapping and unseen-domain settings further demonstrate improved robustness under distribution shift.
### Title:
          The Unbearable Weight: Scaling Models and Methods for UAV Audio Classification
 - **Authors:** Andrew P. Berg, Qian Zhang, Mia Y. Wang
 - **Subjects:** Subjects:
Sound (cs.SD); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As unmanned aerial vehicles (UAVs) become increasingly prevalent in consumer and defense settings, classifying them reliably from limited, modality-specific data is an urgent challenge. The dominant approach, large pretrained networks fully fine-tuned on task data, carries a substantial computational and memory weight that is hard to bear in resource-constrained UAV deployments, where edge inference and rapid retraining for emerging platforms are both required. This paper systematically scales across both model architectures and fine-tuning methods for UAV audio classification, asking when that weight is justified and when lighter alternatives prevail. Using a custom dataset of 3,100 audio clips spanning 31 drone classes, we evaluate transformer (ViT, AST) and convolutional (custom CNN, ResNet-18/152, MobileNet-V3-S/L, EfficientNet-B0/B7) backbones under full fine-tuning, classifier-only fine-tuning, and four parameter-efficient fine-tuning (PEFT) methods: SSF, IA3, OFT, and selective batch-norm tuning. All configurations are evaluated with 5-fold cross-validation across accuracy, training time, trainable-parameter share, and inference-time memory footprint. Selective batch-norm fine-tuning of EfficientNet-B7 with three-fold augmentations achieves the highest validation accuracy (97.65% +- 0.30) while updating under 0.5% of model parameters. Across the sweep, lightweight CNNs consistently outperform transformers on both accuracy and efficiency. For UAV audio classification under data scarcity, scaling the method outperforms scaling the model.
### Title:
          Long-Context Demonstration Selection Using State Space Models
 - **Authors:** Ziniu Zhang, Zhenshuo Zhang, Ruoxuan Xiong, Gene Cooperman, Hongyang R. Zhang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We study the problem of demonstration selection, which involves selecting a subset of examples for prepending to a query to a language model. This problem is closely related to in-context learning and language model inference. Since the inference cost of a transformer model scales quadratically with sequence length, the selection problem becomes especially challenging in a long-context scenario. In this paper, we tackle this problem by building on state space models (SSMs), which require only linear inference time given the input. Our approach involves two algorithms. The first learns a small set of SSMs through distillation of a (trained) transformer model. We partition all the layers into consecutive groups. Then for each group, we estimate a separate state space model to replicate the input-output behavior within the adjacent layers. Second, we map the distilled model outputs to a small set of tokens, and apply these embeddings for demonstration selection in downstream applications. We perform extensive experiments in both synthetic and real-world datasets to validate our approach. We demonstrate that the distilled SSMs only incur an approximation error of less than $0.7\%$ relative to the true output. In downstream evaluation, we show that on several text classification and reasoning tasks, our approach reduces FLOPs by $14.2\times$ and improves accuracy by $6.48\%$ relative to baseline demonstration selection methods.
### Title:
          Demystifying Gate-Level Localization of RTL Trojans
 - **Authors:** Navid Nader Tehrani, Azadeh Davoodi, Rasit Onur Topaloglu
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hardware Trojans are malicious modifications that compromise functionality or leak sensitive data. They pose a severe threat, particularly when inserted at the Register Transfer Level (RTL). After synthesis, these Trojans are often concealed by optimizations in gate-level netlists. Recent efforts, including the ICCAD 2025 contest, emphasize golden-chip-free detection using machine learning (ML) on labeled netlists. In this work, we show that RTL Trojans exhibit stable structural and signal-flow patterns post-synthesis, enabling effective detection through targeted heuristics rather than generic ML feature learning. We propose LoRD, a lightweight heuristic-based approach that exploits these distinctive subgraph signatures, achieving near-perfect detection and localization on the contest testcases. Com- pared to a transformer-based ML baseline and top five teams, LoRD achieves on-average a score of 2.957 (out of 3) for Trojan- implanted designs without the data and tuning overhead.
### Title:
          Mixed-Integer Nonlinear Differentiable Predictive Control for Underground Pumped Hydro Energy Storage Systems
 - **Authors:** Honghui Zheng, Ján Boldocký, Yury Dvorkin, Ján Drgoňa
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper extends Mixed-Integer Differentiable Predictive Control (MI-DPC) to multi-modal discrete decisions and nonconvex polynomial dynamics arising in Underground Pumped Hydro Energy Storage Systems (UPHES). A neural policy mapping problem parameters to continuous setpoints and integer mode selections via a Gumbel-Softmax layer is trained in a self-supervised manner by differentiating the expectation of the finite horizon control objective through the nonlinear dynamics model. Three methodological contributions enable this extension: a parallel differentiable simulator that preserves gradient magnitude, a Transformer encoder that captures long-range temporal dependencies, and a Gumbel-Softmax temperature annealing schedule that regularizes the combinatorial search. We demonstrate the framework on day-ahead scheduling of a UPHES, a large-scale mixed-integer optimal control problem with nonlinear unit performance curves and volume-head coupling. MI-DPC achieves only 1.6% suboptimality relative to a piecewise mixed-integer quadratic programming baseline, while providing five orders of magnitude speedup in online scheduling time.
### Title:
          The Operable Pareto Front: Distilling Offline Search into Run-Time Control for Multi-Objective UAV Edge-Computing Scheduling
 - **Authors:** Qiao Liao, Zhiyong Feng, Bin Wu, Guodong Fan
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 A UAV mobile edge computing (MEC) fleet trades energy against delay, and its schedules form a Pareto front; we call a scheduler operable when the fleet can be asked for any point on that front at run time. We propose PrefDT, to the best of our knowledge the first preference-conditioned Decision Transformer for the problem of joint trajectory, association and offloading scheduling. Its idea comes from language modeling: we hand the model the desired trade-off as an input, such that a single model only needs to be trained once offline to return any desired point on the curve in one rollout. The fleet's state is summarized by attention pooling with a per-user bypass, so the scheduler keeps working when user reports are lost. The energy target is a running budget decremented by what the fleet actually spends. As a result, when wind or load pushes consumption off the plan, the policy can track the difference and hold its budget. Because no corpus of preference-labeled flights exists, we design a distillation pipeline and build the corpus by ourselves. In simulation against 26 method variants, PrefDT produces the best trade-off curve of any learned method and holds its energy budget to within 0.6% when propulsion cost rises by half in mid-flight.
### Title:
          The Attention Within: Consensus Dynamics in Selective State Space Models
 - **Authors:** João Pedro Silvestre, Álvaro Rodríguez Abella, Paulo Tabuada
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Systems and Control (eess.SY); Dynamical Systems (math.DS); Optimization and Control (math.OC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Selective state space models (SSMs) have recently emerged as a compelling alternative to transformers, combining competitive performance with substantially improved inference efficiency. At each SSM layer, a sequence of hidden states are propagated by a recurrence, mixing information of different tokens. Despite using a different mechanism, this mixing plays a role analogous to attention in transformers. In fact, recent works have shown that the two architectures may be closer than they first appear, as this recurrence admits a formulation akin to linear attention. In transformers, attention is known to drive the tokens to cluster, i.e., to reach consensus, collapsing in the limit to a single direction. Thus, we ask: does the recurrence at the core of SSMs drive the tokens to consensus, as attention does in transformers? To answer this question, we take a dynamical systems perspective on SSMs, modeling the evolution of tokens across layers as an ordinary differential equation. By exploiting input-to-state stability arguments, we establish local exponential stability of the consensus equilibria and characterize their domain of attraction for time-varying weight matrices, a setting not addressed by previous results. We thereby show that the resemblance between SSMs and transformers does run deeper: the recurrence at the core of SSMs aggregates tokens just as attention does. Numerical experiments on a pretrained Mamba-2 model point to the output gate as the component that regulates the extent of this consensus, preventing the tokens from reaching it in full.
### Title:
          Position Anchor Tuning: Towards Efficient Adaptation of Pre-Trained Point Cloud Transformers
 - **Authors:** Zheng Liu, Xin Gao, Jinchao Zhu, Gao Huang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Parameter-efficient fine-tuning (PEFT) has recently emerged as a pivotal research direction for adapting pre-trained point cloud transformers to diverse downstream tasks. Although existing methods achieve excellent fine-tuning performance with high parameter efficiency, they ignore inference efficiency. To tackle this problem, a novel PEFT method termed position anchor tuning (PAT) is proposed in this paper. As multi-head attention (MHA) and feed-forward network (FFN) are computation-heavy blocks in pre-trained transformers, PAT decreases their computational cost through token aggregation-expansion pairs. Each pair comprises a token aggregation module (TAM) and a token expansion module (TEM). For MHA and FFN blocks, TAMs extract representative tokens from their input tokens based on position anchors in 3D space. These extracted tokens, rather than the original input tokens, are processed by the blocks, thereby reducing the number of tokens involved in computation. Then, TEMs propagate the learned representations back to the original input tokens. Since TAMs are solely responsible for capturing task-specific representations, base-sharing low-rank adaptation (BSLoRA) is further introduced to enable them to learn such representations effectively with only a small number of trainable parameters. Extensive experiments on widely used benchmarks demonstrate that PAT performs comparably to state-of-the-art methods while incurring significantly lower computational overhead and fewer trainable parameters.
### Title:
          vidax: A Unified JAX Framework for Video Generative Models on Accelerator Meshes
 - **Authors:** Congyue Deng
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Distributed, Parallel, and Cluster Computing (cs.DC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Open-source video generative models ship almost exclusively as PyTorch/CUDA reference implementations. This leaves Cloud TPU pods without a production-ready inference path, despite offering large, cost-effective accelerator memory pools ideal for long-sequence spatiotemporal attention. We present vidax, an open-source JAX/Flax inference engine and zero-copy PyTorch-to-JAX weight translator for modern video generation architectures. vidax covers a diverse set of spatiotemporal models --- including Diffusion Transformers, omnimodal Mixture-of-Transformers, 3D VAEs, text encoders, and native samplers --- with zero PyTorch dependency in the execution path. The framework unifies 1D tensor parallelism with DeepSpeed-Ulysses sequence parallelism on a single JAX sharding mesh, integrates TPU flash-attention kernels, and implements per-layer weight offloading to support reference resolutions that exceed single-device memory. We benchmark compile times, latency, and peak memory utilization on TPU v4-8 hardware, and document real-world numerical bugs surfaced during checkpoint translation. vidax is released open-source as a baseline for JAX and TPU video generation research.
### Title:
          FoundAna: A GNN-assisted Foundation Model for Graph Anomaly Detection
 - **Authors:** Suprim Nakarmi, Chahana Dahal, Yue Zhao, Junggab Son, Zuobin Xiong
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Graph anomaly detection aims to identify graph structures (e.g., nodes, edges, or subgraphs) that deviate significantly from expected patterns, which supports critical applications in fraud detection, spam identification, network intrusion, etc. Despite the growing methods in the field, existing approaches follow a one-model-per-dataset paradigm, limiting their transferability across diverse real-world scenarios due to task heterogeneity, label scarcity, and domain variability. In this work, we introduce FoundAna, a GNN-assisted Foundation Model for Graph Anomaly Detection - the first foundation model framework designated for generalizable, cross-graph anomaly detection by combining GNNs and transformers. FoundAna integrates an anomaly detection-specific GNN component with a standard transformer encoder augmented by four complementary positional encodings, which enable the model to capture both local and global structural information. Specifically, the positional encoding enriched node representations are passed through attribute and adjacency decoders, and the reconstruction errors serve as the anomaly score. Extensive experiments on nine benchmark datasets spanning financial, social, and citation network domains demonstrate that FoundAna consistently outperforms state-of-the-art baselines. The code implementation and Supplementary materials are here: this https URL.
### Title:
          Technical Report: One-Step Drifting Action Heads for GR00T N1.7
 - **Authors:** Xihe Shao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 One-step action generation can substantially reduce the inference cost of vision-language-action (VLA) policies, but its effect on closed-loop task success remains an open question. This technical report studies a GR00T N1.7 variant in which the iterative diffusion-transformer action head is replaced by a one-step drifting action head, together with an overlap-conditioned extension for asynchronous chunk replacement. All multi-seed drifting runs were trained on two NVIDIA A800 GPUs. On LIBERO, the action head reduces the mean model-forward time of the action head from approximately $45.3\,\mathrm{ms}$ to $5.0\,\mathrm{ms}$, while the measured backbone-plus-head time falls from approximately $70.0\,\mathrm{ms}$ to $30.6\,\mathrm{ms}$. However, this speedup is accompanied by a systematic reduction in task success. Across three drifting seeds, success is $64.0\pm4.0\%$ on LIBERO-Spatial, $52.0\pm1.0\%$ on LIBERO-Goal, and $26.0\pm2.6\%$ on LIBERO-Long. The low seed variance indicates that the degradation is not explained by random initialization alone. We report the result as a speed--success trade-off rather than an overall improvement, and discuss likely contributing factors including deterministic one-step mode averaging, batch-dependent geometry estimation, long open-loop chunk execution, and the fact that synchronous LIBERO evaluation does not exercise the asynchronous overlap path.
### Title:
          PRISM: Predictive Representation of Interaction Style and Motion for Social Robot Navigation
 - **Authors:** Bo-Han Chen, Hiromu Taketsugu, Norimichi Ukita
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humans often observe others before interacting and adjust their behavior accordingly. Robot navigation in crowds, however, often represents pedestrians mainly by observed geometric states, leaving individual differences in interaction tendencies implicit. We propose PRISM (Predictive Representation of Interaction Style and Motion), a framework that infers interaction traits from passive observations of human-human interactions. PRISM encodes human trajectories into a continuous ordinal latent space with a transformer encoder trained by Rank-N-Contrast loss, and pairs each inferred trait with a temporal-stability score supplied to the navigation policy. In randomized crowd simulations, PRISM reduces collision rates over the geometry-only baseline and yields small improvements in navigation-time and path-length metrics. These results suggest the utility of passive latent-trait inference for social navigation in dynamic crowds.
### Title:
          MoRE: Mixture of Reused Experts
 - **Authors:** Eric S. Qiu, Utku Umur Acikalin, Justin Lovelace, Christian Belardi, Arjun B. Mulchandani, Carla P. Gomes, Kilian Q. Weinberger
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mixture-of-Experts (MoE) architectures decouple model capacity from computational cost, yet incur high memory footprints as parameters grow linearly with the number of experts. Recurrent Transformers achieve parameter efficiency by reusing layer weights, but typically lack the capacity for competitive language modeling. We propose Mixture of Reused Experts (MoRE), a hybrid that shares expert pools across groups of adjacent layers. Each layer retains its own router but selects from a larger shared pool, expanding the diversity of routing combinations without additional parameters. To enable shared experts to distinguish between layers, we introduce lightweight learnable depth embeddings that condition each layer's input before routing. Experiments across three model scales (114M-1.15B parameters) show that MoRE consistently achieves lower perplexity and stronger downstream performance than standard MoEs and state-of-the-art weight-sharing architectures at matched compute and parameter budgets, with only minimal modifications to existing MoE implementations.
### Title:
          WholeBodyWAM: Learning Whole-Body World Action Models with Scalable Motion Priors
 - **Authors:** Bowei Zhang, Qiyao Zhang, Shuanghao Bai, Xinhua Wang, Meng Li, Yilei Wang, Leiwang Zhang, Jian Tang, Lu Zhou, Lei Sun, Zhengping Che
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Humanoid whole-body manipulation requires coordinated whole-body dynamics, yet large-scale trajectories from a target robot are expensive to collect and difficult to scale. In contrast, whole-body motion from human and humanoid sources is abundantly available, although such data cannot be directly used as embodiment-specific robot actions. This work asks whether these scalable motion resources can instead provide a transferable predictive prior for humanoid world-action modeling. We introduce WholeBodyWAM, a humanoid world-action model that learns whole-body dynamics from large-scale heterogeneous motion before target-robot training. We curate UniMotion-4K, a motion corpus spanning more than 4K hours from human videos, native 3D motion datasets, and heterogeneous humanoid platforms, and canonicalize these diverse sources into a unified motion space. A language-conditioned Motion Expert is then pretrained to predict future whole-body motion without target-robot action supervision. During robot post-training, the pretrained Motion Expert is integrated with Video and Action Experts through asymmetric Mixture-of-Transformers (MoT) attention, enabling predictive scene dynamics and whole-body motion to jointly inform embodiment-specific action generation. Experiments show that WholeBodyWAM consistently benefits from increased motion-pretraining scale, improves future-motion prediction and downstream task performance, and transfers effectively to real-world humanoid manipulation. Moreover, the pretrained motion prior substantially improves data efficiency under limited target-robot demonstrations.
### Title:
          A Lightweight CNN Integrated Compact Convolutional Transformer for Multi-Scale Feature Learning and reducing computational complexity for breast cancer mammography image detection and classification
 - **Authors:** Md Taimur Ahad (Department of Management North South University, Dhaka, Bangladesh), Ainuddin Ahmed (Department of Management North South University, Dhaka, Bangladesh)
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Over the years, Convolutional Neural Networks (CNNs) have demonstrated strong capability in cancer detection and classification using medical images. However, CNN-based models often struggle to capture long-range contextual dependencies. In such scenarios, integrating Compact Convolutional Transformer (CCT) architectures after the CCT layer allows CNN-extracted features to reshape into compact patch tokens using a CCT tokenizer, followed by the addition of positional embeddings to preserve spatial structure. Using 5-fold cross-validation, the model was tested on 3 sets of breast cancer mammography. With only 250,435 parameters, the model achieved 99%-100% accuracy across 3 datasets, indicating robust generalization. Explainable AI (XAI) was integrated into the model to explain the breast cancer classification process to enhance clinical trust. The results indicate that the proposed framework is suitable for computer-aided diagnosis systems, particularly in resource-constrained clinical environments. The novelty of the proposed CNN-integrated CCT overcomes the limitation of CNN's gradient degradation in the last layers by integrating convolutional tokenization with transformer-based learning. Lighter than ViT, which is effective in capturing long-range dependencies, the model has also proven efficient in breast cancer classification by capturing long-range dependencies among breast tissue regions.
### Title:
          Decoder-Agnostic Token Merging for Vision Transformers: A Systematic Study of G2TM
 - **Authors:** Victor Bercy, Martyna Poreba, Michal Szczepanski, Samia Bouchafa
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Vision Transformers (ViTs) have achieved state-of-the-art performance across a range of computer vision tasks, mainly thanks to the self-attention mechanism. However, its complexity, increasing quadratically with the number of tokens, remains the major obstacle to ViT efficiency and deployment at scale. Token merging reduces this cost by aggregating redundant tokens. Yet existing methods are typically evaluated within a single architecture, leaving open whether their effectiveness stems from the merging mechanism itself or from the specific decoder they are paired with. We extend Graph-Guided Token Merging (G2TM), a single module inserted early in a ViT-based network, beyond its original Segmenter setting. We evaluate G2TM across three semantic segmentation frameworks (Segmenter, SETR, EoMT) and three decoder families (Linear, Transformer-, convolution-based), as well as standard ViT image classification. Our results show that G2TM's behavior and accuracy-efficiency trade-off are consistent across every tested architecture for a given backbone size, indicating that its effectiveness is a property of the encoder rather than the decoder. G2TM also generalizes well to image classification, achieving an even smaller degradation in accuracy compared to semantic segmentation. We further find that G2TM's optimal hyperparameters, resulting in a consistent drop in GFLOPs of 22-47% and an increase in throughput by up to 74% for segmentation models on ADE20K dataset, depend primarily on the backbone's pre-training recipe and on the target dataset, rather than on the decoder choice.
### Title:
          A GAN-Based Framework for Robust DDoS Attack Detection
 - **Authors:** Makram Chehayeb, Walid Fahs, Amina Rizk, Rida Khatoun, Omran Berjawi
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Cryptography and Security (cs.CR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The availability and consistency of online services remain vulnerable due to Distributed Denial of Service (DDoS) attacks. These attacks are evolving by adopting more complex strategies to evade traditional network security systems. Despite the effectiveness of machine learning models in detecting DDoS traffic, targeted adversarial attacks can degrade their classification accuracy. This work proposes a robust detection framework that integrates generative adversarial modelling with advanced machine learning models. We trained Random Forests, Deep Neural Ensembles, and Transformer-based models using the CICDDoS2019 dataset to establish the frameworks baseline performance. To enhance the models defensive capacity, we generated synthetic adversarial flows that simulate potential evasion attempts and adversarial traffic using a Wasserstein Generative Adversarial Network with Gradient Penalty (WGAN-GP). Then, we combined the generated traffic with benign and malicious traffic to construct hybrid datasets to train the models to learn more generalizable decision boundaries. The experimental results indicate that the proposed methodology significantly enhances detection accuracy and resilience, especially against unseen adversarial traffic. We also tested the designed framework using real-world generated traffic, which demonstrates its capability in practical settings. The scalable and efficient solution against adversarial DDoS attacks, introduced in this work, paves the way towards more resilient and adaptive network defense systems that combine generative adversarial augmentation with recent advances in learning models.
### Title:
          MiST: Mid-Training LLMs for Cybersecurity
 - **Authors:** Oded Ovadia, Elad Ben Zaken, Elad Guttman, Orly Moreno Kadosh
 - **Subjects:** Subjects:
Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Cybersecurity combines high-stakes analysis with complex technical language, making it an impactful and challenging domain for LLMs. We present MiST (Mid-trained Security Transformer), a suite of 8B and 32B models that achieve strong performance on public cybersecurity benchmarks. We use mid-training as an intermediate adaptation stage between general pre-training and cybersecurity training. Rather than performing continual pre-training over large volumes of raw domain text, we curate a compact, expert-vetted seed corpus, and transform it into high-quality domain-specific synthetic training data. The final MiST checkpoints improve mean cybersecurity accuracy by +13.1 and +8.6 absolute percentage points over the corresponding Qwen baselines for 8B and 32B, respectively, corresponding to relative gains of +27.0% and +15.8%. Ablation results further show that these cybersecurity gains arise in the mid-training and supervised fine-tuning stages through a combination of the synthetic data generation flows. Furthermore, we show that MiST provides a stronger initialization for downstream task-specific fine-tuning adaptation and reinforcement learning.
### Title:
          InterMASH: A Unified Geometric Representation for Grasp Synthesis
 - **Authors:** Xuanze Yang, Yumeng Liu, Haiyang Xin, Changhao Li, Haowei Shen, Kai Xu, Ligang Liu, Ruizhen Hu
 - **Subjects:** Subjects:
Robotics (cs.RO); Graphics (cs.GR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Grasp synthesis aims to generate stable and physically plausible hand--object interactions, and has become a fundamental problem in both human hand modeling and robotic manipulation. However, a unified representation across human and robotic hands is still lacking, mainly due to differences in hand morphology and surface modeling. Prior methods typically rely on either contact maps or dense implicit descriptors to represent interaction, but these representations are often incomplete or computationally expensive and redundant. We propose InterMASH, a unified geometric representation that establishes cross-embodiment correspondence using sphere-fixed anchors. At each anchor, low-degree spherical harmonics compactly encode local hand geometry, object geometry, and contact, forming an explicit and interpretable token sequence. Building on this natively tokenized structure, we introduce a conditional Diffusion Transformer that operates directly in the proposed InterMASH representation space and jointly generates hand geometry and contact, improving consistency and physical plausibility. Our method achieves competitive performance with state-of-the-art methods on key physical feasibility metrics in a large-scale ShadowHand benchmark, supports joint training across multiple hands, and shows that cross-embodiment fine-tuning with human grasp data can improve robotic grasp success and diversity. Project page is available at this https URL.
### Title:
          DiT-Garment: Garment Dynamics with Diffusion Transformers
 - **Authors:** Antoine Dumoulin, Laurence Boissieux, Joao Regateiro, Pierre Hellier, Stefanie Wuhrer
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present DiT-Garment to model dynamic 3D clothing over human body models in arbitrary motion. Unlike existing methods, DiT-Garment can animate garments with unseen designs and physical materials, while allowing for direct inference of deformations for any target pose. To achieve this, we leverage a 2D diffusion transformer architecture to learn 3D deformations in a 2D UV-space. As the result is non-deterministic, our generative model learns the distribution of possible outcomes. The template garment is represented as a 3D triangle mesh spatially aligned with a 3D human body model in a standardized pose. To work with different garment designs without the need of a common template or complex graph convolution operations, the diffusion transformer is conditioned on a 3D position map of the template, represented in UV-space, which allows to implicitly learn a deformation of the 3D space around the body in standard pose. Further conditioning on body motion and physical parameters allows to physically ground the model. We quantitatively and qualitatively evaluate DiT-Garment on both synthetic and real data. While only trained on synthetic simulations of automatically generated cloth designs, our method generalizes to captured and artist-made garment designs. Code and data are available for research purposes at this https URL.
### Title:
          Interpretable Patch-Based Deep Learning for Wildfire Spread Prediction from Ensemble Simulations
 - **Authors:** Marcin Lawenda, Aleksandra Krasicka, David Caballero, Luis Torres, Łukasz Szustak
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Wildfire spread is traditionally predicted using physics-based simulators, which are physically interpretable but whose cost increases with each additional ensemble member. We ask how well deep learning surrogates can reproduce these simulations at a fraction of this cost, training them on 10,584 fire spread simulations at 2m resolution for the Rectoret region in Catalonia, Spain. Four architectures are compared: a patch-based U-Net, a transfer-learned ResNet-50, a physics-informed network constrained by the wind-driven advection equation and a Swin-Unet transformer. Among the terrain and vegetation variables, only surface fuel load predicts burn probability with any strength (r = 0.27) and including it lowers prediction error by 21%. The remaining variables correlate weakly and are highly duplicative. Next, an experiment with saliency, occlusion and rotation demonstrates the models' learning. Convolutional models rely primarily on distance from the current fire front, while Swin-Unet assigns more weight to fuel and terrain, a finding also noted in an unrelated wildfire dataset. When applied without retraining to the second region, Pedriza, all three convolutional models still predict fire spread, losing accuracy by a small but systematic margin.
### Title:
          Learning Where to Focus: Self-Supervised Multi-Scale ViTs for Histopathology
 - **Authors:** Anabel Stammer, Valay Bundele, Mehran Hosseinzadeh, Hendrik P.A. Lensch
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pathologists diagnose diseases by first locating suspicious tissue and then examining it at higher magnification, whereas self-supervised vision transformers (ViTs) allocate the same spatial resolution to every image region despite diagnostic evidence being sparse and spanning multiple biological scales. Recent pathology foundation models have substantially improved representation quality by scaling training data and model capacity, but largely retain uniform tokenization. We instead investigate whether pathology representations can be improved by learning where to allocate spatial resolution during self-supervised learning. To this end, we propose CRAFT (Coarse-to-fine Region-Adaptive Feature Tokenization), a DINO-based framework that learns image-dependent mixed-scale representations by using self-supervised attention to selectively refine informative regions while preserving coarse context, together with a symmetric cross-scale regularization objective that encourages complementary coarse and fine representations. Across CAMELYON16, TCGA-Lung subtype classification, and TCGA-LUAD survival prediction, CRAFT consistently outperforms comparable-scale self-supervised methods while requiring lower inference computation. Despite using only a compact 22M parameter backbone trained on comparatively small pathology datasets, CRAFT remains competitive with, and often surpasses, substantially larger pathology foundation models.
### Title:
          Multi-Teacher Distillation for Cross-Domain Streaming Electrolaryngeal Speech Encoding
 - **Authors:** Benedikt Mayrhofer, Enrique Orozco Olivares, Franz Pernkopf, Philipp Aichinger, Martin Hagmüller
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Self-supervised learning (SSL) has improved speech representations, yet performance degrades in pathological domains such as electrolaryngeal (EL) speech, and the computational footprint of SSL models limits their applicability in real-time, on-device deployment. We propose a multi-teacher knowledge distillation framework to train a lightweight, streaming content encoder that generalizes across healthy (HE) and EL speech. Two teachers are distilled progressively: a frozen SSL model providing discrete phonetic cluster targets from HE speech, and an EL-fine-tuned speech recognition model supplying continuous bottleneck feature targets. Evaluated via downstream speech recognition, our approach reduces the EL word error rate to 21.2%, compared to 39.3% for the strongest zero-shot SSL baseline. Among causal convolutional, Transformer, Conformer, and Mamba-based student architectures, a Mel-Conformer achieves the best combination of EL accuracy and computational efficiency. The final encoder contains 21.9,M parameters and runs at a real-time factor of 0.30 under ONNX Runtime on a single CPU core.
### Title:
          PhysVGGT: Feed-Forward Dense Physical Property Estimation from A Single Image
 - **Authors:** Sneha Paul, Guile Wu, Bingbing Liu, Dongfeng Bai
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Physical properties, such as friction, hardness, stiffness, and density, govern how robots should grasp, manipulate and interact with objects, yet estimating these properties from RGB images remains challenging. Existing methods typically employ per-object reconstruction augmented with physical properties or directly query vision-language models at test time, which results in substantial computational overhead that limits their applicability. In this work, we present PhysVGGT, a feed-forward model that predicts dense maps of friction coefficient, Shore hardness, Young's modulus, and density, together with object-level mass, from a single RGB image in one forward pass. The key idea of PhysVGGT is to formulate physical property estimation as a dense per-pixel prediction problem and employ a visual geometry transformer to extract geometry-aware tokens from the input image followed by a dense prediction branch for estimating local physical properties and a global prediction branch for estimating object-level mass. In addition, we introduce a scalable pseudo-label generation pipeline that enables large-scale weakly supervised training for dense physical property prediction, substantially reducing the need for expensive direct physical measurements. Extensive experiments show that PhysVGGT achieves state-of-the-art performance on the ABO-500 dataset and generalizes effectively to the out-of-distribution NeRF2Physics dataset. Moreover, PhysVGGT eliminates the need for per-object reconstruction and test-time optimization, achieving an inference latency of only 0.13s per image, making it $27\times$ faster than the previous state of the art.
### Title:
          Learning Holistic Whole-Body Loco-Manipulation with a Bipedal Mobile Manipulator
 - **Authors:** Zhongyu Chen, Yuxuan Nai, Qian Chen, Yidong Zhu, Chen Jing, Qihan Wang, Xudong Li, Zhizhan Li, Leixin Chang, Liangjing Yang, Hua Chen
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Bipedal loco-manipulation enables robots to interact with objects beyond the nominal workspace of their arms by coordinating locomotion and manipulation. Realizing this capability requires a low-level whole-body controller that translates task-level manipulation goals into coordinated arm and leg motions while maintaining balance. We present a unified whole-body controller trained with reinforcement learning that directly maps 6-DoF end-effector targets to coordinated actions for the bipedal base and robotic arm. Given only an end-effector target, the learned controller autonomously coordinates reaching, postural adaptation, and stepping without explicit base-velocity or footstep commands. A reward-gating strategy regulates the trade-offs among end-effector tracking, locomotion, and balance during training, while a temporal context estimator combines windowed Transformer encoding, recurrent GRU memory, and auxiliary dynamics prediction to extract dynamics-relevant information from observation history. Real-robot experiments demonstrate that the same controller supports reaching, postural adaptation, and stepping under commands from VR teleoperation, a learned diffusion policy, and scripted trajectories, providing a common end-effector interface for diverse manipulation tasks.
### Title:
          KDTwin: Task-Aware Knowledge Distillation for Lightweight Multi-Task Driving Scene Segmentation
 - **Authors:** Huy Che, Minh-Khoi Do, Dinh-Duy Phan, Duc-Khai Lam
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient perception models are essential for real-time autonomous driving, where accuracy and computational cost must be carefully balanced. However, applying knowledge distillation to multi-task driving scene segmentation is challenging because drivable-area and lane segmentation exhibit different spatial characteristics and class imbalance. We propose KDTwin, a task-aware distillation framework for lightweight multi-task segmentation networks. The proposed method performs distillation at both the shared encoder and task-specific decoders. Encoder-level pairwise distillation transfers spatial relational knowledge to enhance the student's shared representation. For the decoders, we use a weighted loss for drivable-area segmentation and a boundary-aware loss for lane segmentation, enabling task-adaptive knowledge transfer without increasing inference complexity. Experiments on BDD100K show consistent improvements across the evaluated CNN-based and Transformer-based student models without increasing inference-time parameters or FLOPs. The results show that designing distillation objectives according to task-specific characteristics can effectively enhance multi-task segmentation performance for autonomous driving. The source code is available at this https URL.
### Title:
          Capability Emergence Can Be Forecast: Per-Seed, In Advance, With Calibrated Intervals, Certified False Alarms, and a Blind Pre-Registered Gate
 - **Authors:** Gunner Levi Howe
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Emergent capabilities are widely treated as unpredictable: loss improves smoothly while abilities appear abruptly. Prior work offers early-warning indicators but never scores them as forecasts: no lead time at controlled false-alarm rate, no calibration, no negatives, no blind tests. We supply that discipline and show that, in grokking model systems and small language models, emergence timing is forecastable per run, in advance, with calibrated uncertainty. Across 30 transformers at identical configuration, the formation time of the previous-token head forecasts each seed's induction-head emergence at Spearman rho=0.977 with median lead 975 steps (~15% of training); a best-case loss rule ties the ranking with 50-step lead (a nowcast). Conformal intervals covered 15/15 held-out seeds, and the frozen rule passed blind pre-registered gates on TWO never-seen configurations (10/10 and 9/10 coverage). A trap-language rung then attacked our own rule as pre-registered: where previous-token context pays for the task itself, the bare precursor false-alarms on 10/10 capability-blocked runs, while the mechanism-composed conjunction is certified in both language classes (0 false alarms) and times emergence at rho=1.000. Finally, a gap-origin study broke the fixed offset (both lr and batch move the gap ~2.3x; no external clock owns it) and revealed the law beneath: across 80 valid-anchor runs the anchor fires at 0.843 of time-to-emergence -- t_event ~= 1.19 x t_anchor -- and this multiplicative rule passed its own blind gate (5/5) at a third unseen configuration. False alarms are certified against 33 manufactured negatives. The precursor leads across 3 public model families (Pythia, OLMo, OLMo-2; 7 suites), with OLMo-2 at 1B tokens showing precursor formed, capability absent. Four pre-registered kill criteria fired and are reported. Every freeze precedes its data in a public commit chain.
### Title:
          Tabular Deep Learning vs Classical Machine Learning for Urban Land Cover Classification
 - **Authors:** Muntasir Tabasum, Tanpia Tasnim, Md. Ekramul Islam, Al Zadid Sultan Bin Habib
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Urban Land Cover (ULC) classification plays a crucial role in urban planning, environmental monitoring, and sustainable development. We study this task using the ULC dataset from the UCI Machine Learning Repository, which includes tabular features derived from high-resolution aerial imagery across nine classes (e.g., roads, trees, grass, water). The dataset presents typical remote sensing challenges, including high dimensionality, heterogeneous features, and class imbalance. In a unified, reproducible pipeline, we benchmark classical machine learning models (e.g., Logistic Regression, SVM, Random Forest, XGBoost, CatBoost) against Tabular Deep Learning (TDL) models (TabNet, FT-Transformer, TabTransformer, TabSeq, and 1D CNNs). To address class imbalance, we employ weighted cross-entropy loss for TDL models and evaluate performance using accuracy, macro-precision, macro-recall, macro-F1, AUC-ROC, and confusion matrices. Our results show that while tree ensembles remain strong general baselines, TDL models can match or exceed their performance when non-linear interactions are significant and imbalance handling is effective, providing complementary advantages for urban land cover mapping. See code: this https URL
### Title:
          Loco-Loco-RL: Low-Cost Terrain Mapping for Humanoid Locomotion with Reinforcement Learning
 - **Authors:** Jordan Dowdy, Gryffin Reizian, Jean Chagas Vaz
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Informative terrain perception is important for robust reinforcement learning policies in humanoid locomotion. Still, common sensors such as depth cameras and LiDARs incur high cost, power, and processing overhead while often producing redundant, high-resolution data. This work uses a low-cost time-of-flight sensor to provide a compact 3D local terrain representation for humanoid locomotion. To efficiently use this sparse exteroceptive input, we introduce a token-compressed temporal transformer policy. Proprioceptive and terrain observations are tokenized and processed by a self-attention multi-head transformer to capture within-timestep relationships between observation terms. The attended tokens are then compressed through an MLP-based latent-space token compression module before being stored in a rolling 15-timestep history. A second cross-attention multi-head transformer extracts temporal locomotion features from this compact history for policy learning. By compressing tokens before temporal aggregation, the architecture preserves important terrain-observation structure while limiting the dimensional growth of attention over observation histories. We validate our method through sim-to-real transfer on physical hardware using a terrain-based locomotion benchmark, demonstrating robust humanoid terrain walking with low-cost local terrain sensing.
### Title:
          How Model Growth, Recursion, and Boundary Operators Influence Scaling Exponents
 - **Authors:** Zixi Chen, Akshay Vegesna, Samip Dahal, Andrew Gordon Wilson
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scaling laws predict how loss decreases with increases in computation. We show, contrary to conventional wisdom, that architectural interventions can modify scaling exponents in pre-training, leading to exponential improvements in performance with increases in computation. As an anchoring point, we consider the architectural formulation of looped transformers. Although not typically used in this way, looping, also known as recursive depth, provides a mechanism for model growth, by increasing the number of loops during training. Model growth, with and without shared weights, provides the biggest changes to the scaling exponents. In particular, a 7.4B model growth architecture matches GPT-3 13B on CORE with roughly $20\times$ less compute, and has compute efficiency gains that increase with scale. Moreover, simply using a boundary operator in a vanilla transformer, which normalizes and injects an earlier block, also provides increasing compute-efficiency gains, although to a lesser extent. In the data-constrained, multi-epoch setting, standard looping has a useful regularizing effect, where we find it is compute-optimal to increase the number of loops with scale. These results can be understood through the lens of computational depth: for a given computational budget, we wish to increase the usable depth of the transformer, which can lead to efficiency gains that increase with scale.
### Title:
          PointZero: 3D Point Track Completion for Learning Transferable 3D Dynamics
 - **Authors:** Bardienus P. Duisterhof, Kaifeng Zhang, Adam Hung, Bowen Wen, Stan Birchfield, Yunzhu Li, Deva Ramanan, Jeffrey Ichnowski
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 World models endow perceptual systems with the ability to predict how scenes evolve under interaction. They are most beneficial when trained on diverse volumes of data, to instill a rich prior into downstream applications. Existing methods typically require robot action labels to learn action-conditioned 3D dynamics, which excludes web video data from the training pool. We study 3D point track completion as a pre-training objective for learning transferable 3D dynamics without robot data. Given a single RGB-D observation and sparse partial 3D trajectories (tracks), we predict future 3D tracks of all observed points. We show this objective produces a rich 3D dynamics prior, without requiring robot action labels. We contribute a diverse dataset of 2.9 million synthetic frames spanning deformable, articulated, and rigid objects, and use it to train PointZero. We show that a flexible and expressive transformer, PointZero, outperforms prior methods on the same data. We demonstrate the utility of our pre-training objective by post-training PointZero for two downstream applications: (1) action-conditioned 3D dynamics prediction and (2) imitation learning. When fine-tuned to condition on end-effector pose, PointZero outperforms the baselines on the recent PGND 3D dynamics benchmark. When fine-tuned to predict robot actions and 3D tracks, PointZero outperforms or matches the baselines on 6/7 simulated and real-world robot manipulation tasks. We furthermore evaluate training PointZero from scratch to isolate the benefits of our proposed architecture from those of our proposed pre-training objective and dataset. We release the dataset, checkpoints, and full training recipe.
## Keyword: autonomous driving
### Title:
          RAF-VLA: Representation Alignment with the Future for End-to-End Autonomous Driving
 - **Authors:** Dogun Kim, Yongjae Lee, Joonhee Lim, Yeina Lee, Junhyeok Park, Moogeun Park, Dongsuk Kum
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent Vision-Language-Action (VLA) models for autonomous driving have incorporated world modeling by predicting future driving scenes alongside driving actions, demonstrating strong planning performance. Future driving scenes are utilized as dense supervision, encouraging the policy to learn rich internal representations useful for planning. However, these World-Modeling VLAs rely on explicit future generation to learn such representations, thereby introducing two key limitations: additional training burden and inference latency. To address these limitations, we propose RAF-VLA (Representation Alignment with the Future), a VLA-based autonomous driving framework that shapes planning-relevant internal representations through direct guidance from future-frame representations. RAF-VLA employs Future-Aligned Supervised Fine-Tuning, in which a straightforward regularization aligns the policy's hidden states with future-frame representations obtained from a pretrained world encoder while learning driving actions. This simple alignment allows RAF-VLA to avoid the training burden and inference latency associated with future generation. Extensive experiments on the NAVSIM benchmark show that RAF-VLA achieves competitive planning performance against state-of-the-art VLA planners with substantially fewer training samples seen. Moreover, RAF-VLA incurs only 3.8% training overhead and a negligible 1 ms inference overhead.
### Title:
          Learning from Distributed Eyes: Leveraging Collaborative Perception for Automated Model Adaptation
 - **Authors:** Yanan Ma, Yihang Tao, Zhengru Fang, Zihan Fang, Yiqin Deng, Xianhao Chen, Yuguang Fang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In autonomous driving, perception models often struggle to generalize to new environments due to domain shifts. While unsupervised model adaptation offers a feasible solution without labor-intensive manual labeling, existing methods that rely solely on the ego-vehicle's data often lead to inferior pseudo-labeling performance. To address this critical issue, we propose LDE, Learning from Distributed ``Eyes", a novel framework that transforms collaborative perception (CP) into a source of high-quality supervision for model adaptation. This pseudo-labeling approach is hyperparameter-insensitive and relatively reliable, assuming CP often outperforms single-agent's perception. However, naively implementing this approach encounters (1) the communication bottleneck of sharing rich features under time and bandwidth constraints, (2) the view discrepancy between the CP view and the learner's Field of View (FoV), and (3) the unreliability even in CP-generated labels. To address these issues, we design an adaptation-oriented feature sharing mechanism that selectively transmits the most critical information for adaptation, an FoV filtering method that meticulously eliminates mismatched labels, and a curriculum learning strategy to progressively exploit pseudo labels. Extensive experiments on 3D object detection tasks demonstrate that LDE consistently outperforms both the pre-trained models and state-of-the-art unsupervised adaptation methods.
### Title:
          Accuracy- and Real-Time-Aware 4D Radar Preprocessing for Autonomous Driving Perception Systems
 - **Authors:** Woo-Jin Jung, Dong-Hee Paek, Jeong-Su Park, Seung-Hyun Kong
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 4D radar has emerged as a promising next-generation sensor for improving the robustness of autonomous driving perception systems because of its stable sensing capability under adverse weather conditions. However, deploying 4D radar in embedded environments with limited hardware resources requires radar-representation preprocessing that jointly considers perception accuracy, real-time performance, and computational complexity. This paper proposes a preprocessing framework for 4D-radar-based 3D object detection. First, Percentile-based 3D Shape Preservation (P3DP) extracts point clouds from radar tensors while preserving object-shape information and suppressing noise and false alarms. Second, Multi-frame-based Noise Point Discrimination using Kernel Density Estimation (MF-KDE) improves the density and reliability of sparse radar point clouds. Finally, Embedded \& NetScore (ENS) evaluates suitability for embedded deployment by jointly considering accuracy, real-time performance, adverse-weather robustness, and model complexity.
### Title:
          FIVE-VLA: Fast and EffectIVE Autonomous Driving with Recurrent Action Memory
 - **Authors:** Kemal Oksuz, Alexandru Buburuzan, Yuhan Yao, Puneet K. Dokania
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 State-of-the-art vision-language-action models (VLA) for autonomous driving face critical limitations: excessive parameter counts, inefficient high-resolution image processing, and lack of temporal memory. We introduce Fast and EffectIVE VLA (FIVE-VLA) to address these through two key contributions. First, we employ an efficient vision encoder that processes high-resolution ($448 \times 896$) images while generating only 98 tokens, over $5\times$ fewer than existing approaches, and bypass text generation entirely for single-pass trajectory prediction. Second, we propose Recurrent Action Memory (RAM), a lightweight module that conditions action prediction on previous action tokens, providing temporal context critical for manoeuvres such as overtaking and emergency braking. With only 641M parameters, FIVE-VLA completes $\sim$10% more routes without traffic rule infractions than the previous state-of-the-art VLA on the challenging Bench2Drive closed-loop driving benchmark. Non-reactive open-loop simulation on the large-scale real-world NVIDIA Physical AI AV dataset shows 10.2% and 7.7% lower collision-violation rates than SimLingo in single- and four-view settings, respectively. Additionally, FIVE-VLA runs at $\sim$30 fps on an A100 and $\sim$4 fps on a T4 GPU (proxy to an edge device), representing an 8-30$\times$ speedup over previous methods.
### Title:
          GNN-Accelerated Mixed-Integer Dual MPC for Interactive Driving
 - **Authors:** Yidan Zhu, Shuhao Qi, Luyao Zhang, Sofie Haesaert, Jonas Mårtensson
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In interactions with uncertain opponents, dual model predictive control (MPC) can improve performance through information-seeking actions that reduce uncertainty about opponents' behavior. Its recent applications to autonomous driving, however, are limited to scenarios involving a single opponent on a single lane. This paper presents a mixed-integer dual MPC for multiple reactive opponents on multi-lane roads, jointly optimizing integer-valued maneuver decisions (lane changes and safe-region selections), and continuous motion over a scenario tree that samples plausible interactions with the opponents. As interaction complexity increases, solving the resulting mixed-integer nonlinear program becomes increasingly expensive. To reduce this computational burden, a graph neural network (GNN) predicts the optimal maneuver decisions, and high-confidence predictions are fixed before the reduced problem is solved. Simulations show that active probing behavior emerges in complex interactive scenarios, and that GNN guidance fixes $76.3\%$ of the integer decisions and reduces the solve time by $2.5\times$ on average, with negligible degradation of optimality.
### Title:
          KDTwin: Task-Aware Knowledge Distillation for Lightweight Multi-Task Driving Scene Segmentation
 - **Authors:** Huy Che, Minh-Khoi Do, Dinh-Duy Phan, Duc-Khai Lam
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Efficient perception models are essential for real-time autonomous driving, where accuracy and computational cost must be carefully balanced. However, applying knowledge distillation to multi-task driving scene segmentation is challenging because drivable-area and lane segmentation exhibit different spatial characteristics and class imbalance. We propose KDTwin, a task-aware distillation framework for lightweight multi-task segmentation networks. The proposed method performs distillation at both the shared encoder and task-specific decoders. Encoder-level pairwise distillation transfers spatial relational knowledge to enhance the student's shared representation. For the decoders, we use a weighted loss for drivable-area segmentation and a boundary-aware loss for lane segmentation, enabling task-adaptive knowledge transfer without increasing inference complexity. Experiments on BDD100K show consistent improvements across the evaluated CNN-based and Transformer-based student models without increasing inference-time parameters or FLOPs. The results show that designing distillation objectives according to task-specific characteristics can effectively enhance multi-task segmentation performance for autonomous driving. The source code is available at this https URL.
