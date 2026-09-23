# Showing new listings for Wednesday, 23 September 2026
## Keyword: SLAM
### Title:
          Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking
 - **Authors:** Edward Beng Wai Tan, Siew-Kei Lam
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 ICP-based 3D Gaussian Splatting (3DGS) SLAM tracks in real time by registering incoming frames against map Gaussians, using each primitive's covariance for both rendering and registration. These two uses place conflicting demands on one covariance. The mapper shapes it to minimize photometric error, often flattening it against surfaces, while robust registration typically benefits from measurement uncertainty. We propose a dual-covariance parameterization. Each Gaussian keeps a single mean but holds two covariances: a rendering covariance optimized by the mapper, and a tracking covariance derived from an RGB-D sensor noise model. We further use the tracking covariances as Gaussian anchors for image corners, providing constraints in directions where depth geometry is weak. We evaluate on TUM RGB-D, ScanNet, Replica, and two outdoor sequences recorded with a RealSense D435i on wheeled and handheld platforms. We achieve robust tracking performance across multiple scenes and reduced odometry drift, while tracking at $\sim$ 60 FPS.
### Title:
          Unsigned Distance Maps on 2D Point Cloud Registration
 - **Authors:** Ricardo B. Sousa, Giorgio Grisetti, Héber Miguel Sobreira, Carlos André Silva, António Paulo Moreira
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 2D point cloud registration arises in laser odometry and Simultaneous Localization and Mapping (SLAM) for mobile robots. Iterative Closest Point (ICP) is one of the most widely used approaches. Still, its iterative procedure recomputes correspondences via nearest-neighbor search at every iteration, whereas correspondence-free alternatives focus on scan-to-map alignment. This paper proposes a 2D point cloud registration approach based on unsigned distance maps, precomputing the Euclidean distance to the nearest reference point, along with its spatial derivatives, over a discrete grid, replacing the per-iteration search with O(1) lookups. Moreover, point-to-point and point-to-plane error formulations are derived on the SE(2) manifold and solved via Gauss-Newton optimization. On a synthetic benchmark and the real-world IILABS 3D dataset, the precomputed point-to-point variant outperforms its analytical counterparts, achieving competitive laser-odometry drift compared to point-to-plane formulations, as the precomputed gradient regularizes correspondences in the presence of sensor noise.
### Title:
          A Statistical Analysis of Three Player Auction Bridge
 - **Authors:** Aritrabha Majumdar, Sourish Sarkar, Moutushi Chatterjee
 - **Subjects:** Subjects:
Computer Science and Game Theory (cs.GT); Statistics Theory (math.ST); Applications (stat.AP); Computation (stat.CO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Three-player Auction Bridge is a finite imperfect-information game in which dynamic partnerships create a distinctive interaction between scoring, strategic incentives, and payoff distribution. This paper develops a unified statistical and game-theoretic framework to evaluate a traditional scoring rule against a modified mechanism designed to improve strategic incentives. We first identify a structural defect in the original scheme: a bid-invariant slam bonus can make lower contracts strictly more attractive than higher ones. A bid-dependent correction removes this incentive distortion. We then compare the two schemes using higher-moment analysis, fairness measures, Nash equilibrium analysis, and General-Sum Counterfactual Regret Minimization (GS-CFR). The results show significant differences in the shape of the payoff distributions and reveal that, although both schemes remain highly balanced across physical seats, the modified scheme substantially increases inequality across strategic roles. The game is shown to be neither zero-sum nor constant-sum, motivating a general-sum rather than minimax analysis. Full-game GS-CFR further indicates a substantial increase in the bidder's payoff under the modified scheme, accompanied by a reduction in defender payoff and a shift from separating to partially pooling bidding behavior. These findings demonstrate that scoring-rule design can fundamentally reshape incentives, payoff distribution, and information transmission in imperfect-information games. The proposed framework provides a systematic approach to evaluating such mechanisms from both statistical and strategic perspectives.
### Title:
          ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards
 - **Authors:** Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Orchard robots need maps that preserve small but semantically important structures such as trunks, trellises, and fruit. 3D Gaussian Splatting (3DGS) SLAM achieves high photometric fidelity. However, its optimization remains appearance-driven, and transferring image semantics to 3D points is unreliable for thin structures, whose pixels may receive depth from background surfaces. We present ArborSplat, an online semantic 3DGS SLAM system that tracks with LiDAR odometry and optimizes semantics directly on the Gaussian map, constrained by class-specific height bands above a ground plane fitted to each keyframe's stereo point cloud, and fuses multi-view evidence into a semantic point cloud online while rejecting labels inconsistent with the local ground surface or with monocular depth. Class-constrained refinement reserves Gaussian capacity for underrepresented structures and, under reduced budgets, increases training-view accuracy on tree classes. We evaluate the approach on apple and pear orchards during dormancy, flowering, and harvesting. On full routes, it keeps ATE below 0.5 m on all 12 traversals. On shared 301-frame segments, it exceeds SGS-SLAM and GS3LAM by 0.23 to 0.50 training-view and 0.15 to 0.36 held-out mIoU while running 1.7 to 7.5 times faster, whereas SemGauss-SLAM runs out of GPU memory on all six.
### Title:
          TM-APR: Thermal Temporal-Memory Localization via Analytic Online Adaptation
 - **Authors:** Yanshuo Bai, Kanji Tanaka
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Thermal Visual Place Recognition (Thermal VPR) maps camera observations to metric poses within a mapped environment, serving as a prerequisite for autonomous navigation. However, thermal VPR suffers from severe environmental dependence, heavy online retraining overheads, and an inability to model dynamic non-linear shifts, causing existing frameworks to fail during online deployment. To achieve robust domain-invariant place recognition, we bridge Analytic Class-Incremental Learning (ACIL) with domain-invariant VPR for the first time, revealing that its gradient-free matrix updates construct a surprisingly strong baseline that outperforms conventional fine-tuning. Nevertheless, standard ACIL exhibits a critical vulnerability to extreme non-linear thermal fluctuations due to its structural linear assumptions. To overcome this limitation, we exploit a novel algebraic equivalence between ACIL and modern control theory, proposing a framework which embeds Unscented propagation (U-ACIL), Gaussian Mixture partitioning (GMM-ACIL), and minimax $H_\infty$ optimization ($H_\infty$-ACIL) directly into the update loop. Our formulation guarantees exact closed-form matrix updates within $\mathcal{O}(1)$ computational complexity, bypassing backpropagation to ensure that the online update latency ($\Delta t_{\mathrm{learn}}$) remains strictly bounded below the sensor acquisition interval ($\Delta t_{\mathrm{acquire}}$), thereby eliminating trajectory jumps in real-time SLAM pipelines.
## Keyword: odometry
### Title:
          GINIO: A Geometric SO(3)-Equivariant Interface for Neural Inertial Odometry
 - **Authors:** Chankyo Kim, Minghan Zhu, Tzu-Yuan Lin, Avantika Rattan, Maani Ghaffari
 - **Subjects:** Subjects:
Robotics (cs.RO); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Neural inertial odometry increasingly uses networks as learned measurements inside filtering pipelines. Such measurements should transform consistently under arbitrary IMU mounting conventions: their mean must transform as a vector, and their covariance must transform congruently as a second-order tensor. We present GINIO, a geometric SO(3)-equivariant interface for neural inertial odometry under arbitrary rotations of the IMU measurement frame. Given calibrated IMU windows, our framework predicts a motion measurement and uncertainty obeying these tensorial laws. To support efficient sensor-frame learning, we introduce Last-Frame Alignment (LFA), a deterministic preprocessing step that is provably equivalent to world-frame training for SO(3)-equivariant predictors. The connected estimator tracks sensor-local states such as IMU bias, separating nuisance estimation from the geometric law enforced by the learned measurement. We instantiate the same interface in filter-connected NIO, AirIO-style recurrent aerial prediction, EqNIO-style full-SO(3) canonicalization, and ResNet-style temporal backbones. On TLIO, GINIO achieves 2.018 m ID/SO(3) ATE while EqNIO degrades to 76.389 m, using 11.6x fewer FLOPs. On NanoBench, our AirIO-style instantiation improves ATE from 5.579 m to 1.430 m without external attitude input, and our ResNet-style instantiation reaches 0.581 m ATE versus 0.645 m for ResNet1D. On Fetch, GINIO empirically reduces unseen physical-remount ATE from 8.15 m to 0.50 m without retraining, demonstrating robustness beyond the exact coordinate-frame guarantee. For uncertainty, spectral covariance reduces covariance-equivariance error by over three orders of magnitude compared with a diagonal head.
### Title:
          Dual Covariance Gaussian Splatting SLAM: Decoupling Rendering and Registration for Robust Real-Time Tracking
 - **Authors:** Edward Beng Wai Tan, Siew-Kei Lam
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 ICP-based 3D Gaussian Splatting (3DGS) SLAM tracks in real time by registering incoming frames against map Gaussians, using each primitive's covariance for both rendering and registration. These two uses place conflicting demands on one covariance. The mapper shapes it to minimize photometric error, often flattening it against surfaces, while robust registration typically benefits from measurement uncertainty. We propose a dual-covariance parameterization. Each Gaussian keeps a single mean but holds two covariances: a rendering covariance optimized by the mapper, and a tracking covariance derived from an RGB-D sensor noise model. We further use the tracking covariances as Gaussian anchors for image corners, providing constraints in directions where depth geometry is weak. We evaluate on TUM RGB-D, ScanNet, Replica, and two outdoor sequences recorded with a RealSense D435i on wheeled and handheld platforms. We achieve robust tracking performance across multiple scenes and reduced odometry drift, while tracking at $\sim$ 60 FPS.
### Title:
          MOLA LiDAR-Inertial Odometry (MOLA-LIO) on the COMFORT Localization Benchmark
 - **Authors:** Jose Luis Blanco-Claraco
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This short report documents our entry to the COMFORT Localization Benchmark (IROS 2026), evaluated on the GrandTour dataset recorded with the Boxi payload. It extends MOLA-LO into a LiDAR-inertial system that also ingests IMU and, optionally, legged kinematic odometry. We describe the architecture, the streams consumed, the local protocol that selected the submitted configuration, and the measurements backing our real-time claim.
### Title:
          You Should Be Properly Scoring Your Odometry
 - **Authors:** Ola Rønning, Usama Saqib, Andrzej Wąsowski
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When we evaluate the performance of our odometry, it is common practice to score the estimated track against a ground truth. Unfortunately, scoring uses point metrics, such as the root mean square error, that ignore the covariance matrix which estimators like filters and smoothers already report. Using the covariance matters for two reasons. First, the covariance encodes the estimator's uncertainty, so it tells us whether the estimator trusts its own output. An overconfident estimator will not report itself lost. Second, the covariance weights the error in each direction of the estimate. Without the covariance, an estimator is unduly penalized for a high error in an uncertain direction. Instead of point metrics, we should use strictly proper scoring rules. These rules score the estimate together with its reported uncertainty. Strictly proper scoring rules recover the point metrics when no covariance is reported, and they diagnose covariance inconsistency when covariance is reported. Using a one-sided pairwise test, we show that two estimators can expose overconfidence in at least one of them without a ground truth. Strictly proper scoring rules and our pairwise test are available in our open-source framework smfeval. As a case study, we use smfeval to assess the uncertainty quality of the translational component of ground-based LiDAR-inertial odometry. Across four filters we find overconfidence - the worst case reports centimeter certainty with kilometer error. Knowing the filters are overconfident, we investigate the mechanism. The investigation traces overconfidence to filters crediting LiDAR measurements with more new information than they carry.
### Title:
          Unsigned Distance Maps on 2D Point Cloud Registration
 - **Authors:** Ricardo B. Sousa, Giorgio Grisetti, Héber Miguel Sobreira, Carlos André Silva, António Paulo Moreira
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 2D point cloud registration arises in laser odometry and Simultaneous Localization and Mapping (SLAM) for mobile robots. Iterative Closest Point (ICP) is one of the most widely used approaches. Still, its iterative procedure recomputes correspondences via nearest-neighbor search at every iteration, whereas correspondence-free alternatives focus on scan-to-map alignment. This paper proposes a 2D point cloud registration approach based on unsigned distance maps, precomputing the Euclidean distance to the nearest reference point, along with its spatial derivatives, over a discrete grid, replacing the per-iteration search with O(1) lookups. Moreover, point-to-point and point-to-plane error formulations are derived on the SE(2) manifold and solved via Gauss-Newton optimization. On a synthetic benchmark and the real-world IILABS 3D dataset, the precomputed point-to-point variant outperforms its analytical counterparts, achieving competitive laser-odometry drift compared to point-to-plane formulations, as the precomputed gradient regularizes correspondences in the presence of sensor noise.
### Title:
          End-to-End Visual Odometry with RNNs and Attention
 - **Authors:** Ruiyu Li, Yinjia Liu, Alexander Yu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video Odometry (VO) is the process of estimating the ego-motion of an object by analyzing visual information such as a sequence of frames from one or multiple cameras. It has been a popular research topic in computer vision and robotics, and its applications include mobile robotic systems as well as autonomous driving. In this project, we investigate existing end-to-end deep-learning approaches to VO, and propose a novel temporal attention-based model to improve upon the baseline. In addition, while the vast majority of existing deep-learning-based approaches to VO are trained on driving data, we investigate the performance of deep-learning-based VO to the more dynamic and complex problem of hand-held cameras.
### Title:
          ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards
 - **Authors:** Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Orchard robots need maps that preserve small but semantically important structures such as trunks, trellises, and fruit. 3D Gaussian Splatting (3DGS) SLAM achieves high photometric fidelity. However, its optimization remains appearance-driven, and transferring image semantics to 3D points is unreliable for thin structures, whose pixels may receive depth from background surfaces. We present ArborSplat, an online semantic 3DGS SLAM system that tracks with LiDAR odometry and optimizes semantics directly on the Gaussian map, constrained by class-specific height bands above a ground plane fitted to each keyframe's stereo point cloud, and fuses multi-view evidence into a semantic point cloud online while rejecting labels inconsistent with the local ground surface or with monocular depth. Class-constrained refinement reserves Gaussian capacity for underrepresented structures and, under reduced budgets, increases training-view accuracy on tree classes. We evaluate the approach on apple and pear orchards during dormancy, flowering, and harvesting. On full routes, it keeps ATE below 0.5 m on all 12 traversals. On shared 301-frame segments, it exceeds SGS-SLAM and GS3LAM by 0.23 to 0.50 training-view and 0.15 to 0.36 held-out mIoU while running 1.7 to 7.5 times faster, whereas SemGauss-SLAM runs out of GPU memory on all six.
### Title:
          Reduced Order Observers for Monocular Visual Inertial Odometry
 - **Authors:** Amel Abi, Mouaad Boughellaba, Miaomiao Wang, Abdelhamid Tayebi
 - **Subjects:** Subjects:
Systems and Control (eess.SY)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work develops a reduced order observer framework of monocular visual-inertial odometry (VIO). The key idea consists in considering the gravity vector in the body-frame as an additional state and constructing an appropriate output that relates the monocular bearing measurements and their time derivatives to the body-frame velocity. This eliminates the need for the estimation of the landmark positions, leading to a six-dimensional linear time-varying (LTV) observer for the body-frame velocity and gravity, endowed with uniform global exponential stability guarantees. These estimates are subsequently used to recover the orientation almost globally, up to an unknown constant yaw offset, and the position up to an unknown constant translation. The mixed-bearing framework is further extended to account for the inertial measurement unit (IMU) biases, yielding a twelve-dimensional LTV observer endowed with local exponential stability guarantees. Numerical simulations are provided to illustrate the effectiveness of the proposed observers.
## Keyword: livox
### Title:
          SparseNav: Instruction-conditioned Sparse Semantic Perception for Training-Free Vision-Language Navigation
 - **Authors:** Quanhua Chen, Juhan Kang, Runfeng Lin, ZiFei Zhang, Enquang Feng, Chunran Zheng, Xiwang Dong, Jiarong Lin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Map-based vision-language navigation (VLN) relies on persistent spatial representations to connect language understanding with geometric planning. However, acquiring semantics beyond the needs of the current instruction can introduce unnecessary perception cost and irrelevant annotations. Continuously accumulating unrelated objects may not only waste computation, but also clutter the visual-spatial representation consumed by the vision-language model (VLM) planner. To address this problem, we present SparseNav, a training-free framework that follows a less-is-more principle for semantic navigation. SparseNav persistently maintains a lightweight geometric bird's-eye-view (BEV) map and sparse landmark memory, acquiring new semantics on demand using the active sub-instruction to decide what is worth grounding. An instruction manager first tracks navigation progress and identifies the active landmark query. An instruction-conditioned perception mechanism then invokes open-vocabulary segmentation when the queried landmark is visible and its metric location can inform the next decision. The resulting landmark memory supports VLM selection among hybrid frontier and local directional waypoint candidates. Without any additional training, SparseNav achieves success rates of 42.8% on R2R-CE and 40.7% on RxR-CE, both on the Val-Unseen splits. Controlled ablations examine semantic perception strategies and the contributions of individual framework components. Furthermore, we successfully deployed SparseNav on a Unitree Go2 quadruped equipped with an Intel RealSense D455 RGB-D camera for geometric mapping and landmark grounding and a Livox MID-360 LiDAR for localization, without a prebuilt map. We validated its effectiveness across multiple indoor environments using instruction-conditioned waypoint navigation.
## Keyword: loam
There is no result 
## Keyword: lidar
### Title:
          Impact of Data Compression on Downstream AI Tasks: A Study using Teleoperated Driving over 5G
 - **Authors:** Qixin Zhang, Steven Sleder, Xinyue Hu, Faaiq Bilal, Wei Ye, Zhi-Li Zhang
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Teleoperation, such as remote driving, is considered as a key use case of 5G and Next-Generation (NextG) networks. In this context, robots, autonomous vehicles, or other autonomous agents transmit sensor data over mobile networks to edge or cloud servers, where AI systems collaborate with human operators to provide situational awareness and enable remote control. In the case of teleoperated driving, vehicles are equipped with an array of cameras and LiDAR devices, which can generate 100s Mbps (megabits per second) of data. As shown in existing measurement studies, such data volumes far exceed the \emph{uplink} capacity of currently deployed 5G networks, especially when multiple vehicles compete for radio resources. Data compression is thus imperative. In this paper, we explore the impact of sensor data compression on the performance of downstream AI tasks running in edge/cloud servers, which are crucial to alert human operators for safe teleoperation. Using object recognition and semantic segmentation as two example AI tasks, we study how data compression affects the performance of these two AI tasks using unimodal (video or LiDAR) and multi-modal (video+LiDAR) data. We find that lossy data compression generally decreases the performance of AI tasks. The performances of these AI tasks exhibit differing degrees of sensitivity based on the types of data sources and levels of compression. We also empirically identify an optimal trade-off point for the multi-modal vision tasks.
### Title:
          Case for Vehicle-Edge Collaborative Multi-Sensor Data Fusion for Autonomous Vehicle Teleoperation
 - **Authors:** Qixin Zhang, Ajay Kumar Gurumadaiah, Wei Ye, Eman Ramadan, Zhi-Li Zhang
 - **Subjects:** Subjects:
Networking and Internet Architecture (cs.NI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Teleoperation provides a critical safety fallback when autonomous vehicles (AVs) encounter scenarios that are outside their operational design domain. In practice, however, remote operators rely primarily on compressed camera streams over 5G, which often lack depth and spatial geometric cues for safe operation in complex dynamic environments. While multi-sensor fusion can enhance situational awareness, directly transmitting raw camera and LiDAR data is impractical due to 5G uplink bandwidth and latency constraints. In this paper, we propose SHARDED, a collaborative camera-LiDAR perception framework that deploys a feature-level fusion pipeline across the vehicle and edge to reduce uplink traffic while preserving 3D detection and depth estimation accuracy. We further design two complementary mechanisms for SHARDED: (i) A network-aware adaptive feature transmission mechanism that reduces data traffic by 50% on average (peaking at over 95%) compared to raw sensor data, and (ii) a latency-aware positional drift compensation mechanism to mitigate cross-modal misalignment induced by unstable network conditions. Evaluations on the nuScenes dataset and real-world 5G measurement traces show that SHARDED achieves competitive perception quality while reducing uplink bandwidth consumption and end-to-end latency.
### Title:
          PARTE: Plane-Assisted Robust Transformation Estimation for Point Cloud Registration
 - **Authors:** Abolfazl Babanazari, Carson Cramer, Tyler Summers, Carlos Nieto, Kaveh Fathian
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Global point-cloud registration remains challenging when limited overlap, repetitive geometry, and sensor noise produce correspondence sets dominated by outliers. Planar regions are particularly difficult for conventional point descriptors and are therefore often suppressed or discarded before matching. We present PARTE (Plane-Assisted Robust Transformation Estimation), a global registration method that instead treats planar structure as complementary registration evidence. PARTE extracts planar patches and represents them using our novel Plane Context Histogram (PCH), a descriptor that encodes the geometry surrounding each patch, while a two-level matching procedure identifies reliable plane correspondences. Candidate point and plane correspondences are combined in a confidence-weighted compatibility graph for joint outlier rejection, followed by rigid transformation estimation. When no usable plane correspondences are available, PARTE naturally reduces to point-only registration. We evaluate PARTE on 8,097 registration pairs across six indoor and outdoor benchmarks spanning dense RGB-D and sparse LiDAR measurements. Evaluations show PARTE achieves the highest overall success rate against 13 standard and state-of-the-art methods while maintaining low runtime. An open-source C++ implementation with Python bindings is provided at this https URL.
### Title:
          CDKF-Track: Cluster-aware Data-Driven Kalman Filtering for Cooperative 3D Multi-Object Tracking
 - **Authors:** Maria Damanaki, Nikos Piperigkos, Alexandros Gkillas, Aris S. Lalos
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-Object Tracking (MOT) is essential for EdgeAI perception systems, where accurate object localization and reliable identification enable safe decision-making. Singleagent MOT suffers from occlusions, sensor noise, and partial scene understanding in complex real-world scenarios. While multi-agent systems improve robustness by exploiting shared information, they introduce redundant measurements that lead to false data associations, and still struggle to capture nonlinear object dynamics. To address these challenges, we propose CDKFTrack, a Cluster-aware Data-Driven Kalman Filtering framework for Cooperative 3D MOT. The proposed method first fuses multivehicle 3D LiDAR detections through a Graph Laplacian-based formulation. Then, a cluster-aware redundancy reduction scheme groups spatially related detections and selects representative observations to reduce duplicate inputs to the tracker. The resulting detections are processed by a data-driven Kalman filter that learns object motion dynamics from data, reducing dependence on predefined linear motion assumptions. Furthermore, a wavelet-based temporal refinement module leverages the multiresolution decomposition property of wavelets to attenuate shortterm positional fluctuations and improve trajectory continuity. To the best of our knowledge, CDKF-Track is the first framework to jointly address detection-level fusion redundancy and learnable motion modeling in cooperative 3D MOT. Experimental results on the real-world V2V4Real dataset indicate that CDKF-Track achieves up to 27.99% improvements in tracking accuracy over state-of-the-art multi-agent MOT methods.
### Title:
          MOLA LiDAR-Inertial Odometry (MOLA-LIO) on the COMFORT Localization Benchmark
 - **Authors:** Jose Luis Blanco-Claraco
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This short report documents our entry to the COMFORT Localization Benchmark (IROS 2026), evaluated on the GrandTour dataset recorded with the Boxi payload. It extends MOLA-LO into a LiDAR-inertial system that also ingests IMU and, optionally, legged kinematic odometry. We describe the architecture, the streams consumed, the local protocol that selected the submitted configuration, and the measurements backing our real-time claim.
### Title:
          MatchFusion: Explicit-Implicit Instance Matching for Spatio-Temporal Multimodal Autonomous Driving
 - **Authors:** Xiaoyu Li, Jiajia Fu, Long Shi, Tianyu Du, Ruihang Li, Xian Wu, Lijun Zhao, Yingtao Zhang, Lining Sun, Ruifeng Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse instance representations provide a compact interface for spatial LiDAR-camera and temporal past-current interaction in multimodal perception and E2EAD. Effective interaction requires reliable instance correspondences despite geometric discrepancies and heterogeneous semantic representations. Attention-based methods exploit contextual semantics but often require specialized representation alignment, increasing computational overhead. In contrast, association based on structured object states is efficient and interpretable but lacks contextual evidence to resolve ambiguous matches. To combine these complementary strengths, we propose MatchFusion, a learnable instance matching and fusion module for spatio-temporal multimodal autonomous driving. MatchFusion initializes pairwise affinities using geometric similarity and category consistency, then selectively refines structurally plausible associations using instance embeddings. The resulting soft matchmap guides a common residual aggregation operator for adaptive information exchange. This unified matching-fusion formulation supports spatial LiDAR-camera and temporal past-current interaction, using multi-view image-plane geometry and motion-compensated BEV geometry as the respective structural priors. Experiments on nuScenes demonstrate consistent perception gains across diverse front-end configurations. Compared with a prior instance-centric fusion method, the MatchFusion-equipped system achieves higher perception accuracy while reducing FLOPs by 55.3% and GPU memory usage by 39.3%, with the matching-fusion module accounting for only 3.7% of total perception latency. Integrating temporal MatchFusion into SparseDrive further improves perception within an E2E framework without additional supervision. These results establish explicit-implicit matching as an effective and efficient mechanism for spatio-temporal instance interaction.
### Title:
          You Should Be Properly Scoring Your Odometry
 - **Authors:** Ola Rønning, Usama Saqib, Andrzej Wąsowski
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When we evaluate the performance of our odometry, it is common practice to score the estimated track against a ground truth. Unfortunately, scoring uses point metrics, such as the root mean square error, that ignore the covariance matrix which estimators like filters and smoothers already report. Using the covariance matters for two reasons. First, the covariance encodes the estimator's uncertainty, so it tells us whether the estimator trusts its own output. An overconfident estimator will not report itself lost. Second, the covariance weights the error in each direction of the estimate. Without the covariance, an estimator is unduly penalized for a high error in an uncertain direction. Instead of point metrics, we should use strictly proper scoring rules. These rules score the estimate together with its reported uncertainty. Strictly proper scoring rules recover the point metrics when no covariance is reported, and they diagnose covariance inconsistency when covariance is reported. Using a one-sided pairwise test, we show that two estimators can expose overconfidence in at least one of them without a ground truth. Strictly proper scoring rules and our pairwise test are available in our open-source framework smfeval. As a case study, we use smfeval to assess the uncertainty quality of the translational component of ground-based LiDAR-inertial odometry. Across four filters we find overconfidence - the worst case reports centimeter certainty with kilometer error. Knowing the filters are overconfident, we investigate the mechanism. The investigation traces overconfidence to filters crediting LiDAR measurements with more new information than they carry.
### Title:
          Predict Before You Step: Auditable Occupancy Forecasting for Dynamic Obstacle Avoidance under Sparse Guidance
 - **Authors:** Yuhui Mao, Fen Liu, Shenghai Yuan, Tianxin Hu, Ruimeng Liu, Rong Su
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Legged robots under sparse waypoint guidance must avoid moving obstacles using partial, rapidly changing LiDAR observations. We present LOOP (Latent-recurrent Occupancy rollOut Policy), a local avoidance policy that connects sparse waypoint guidance to a frozen locomotion controller at 50 Hz. From occupancy and ego-velocity histories, a recurrent predictor forecasts future occupancy over a 1 s horizon by warping the current map with learned flow and visibility gates. These maps guide velocity selection through map-derived features and geometric risk estimates, providing an explicit interface for inspecting and replacing predictions. In encounter-synchronised Isaac Lab evaluations, LOOP achieves 57.1% head-on success at obstacle speeds of 2.5-3.2 m/s, exceeding a retrained reactive baseline by 8.2 percentage points. Comparisons with a rollout-free BEV policy show smaller, scenario-dependent gains from the prediction branch, including improved crossing success and reduced variability across training seeds at the highest head-on speeds. The adapter runs onboard a Unitree Go2 in 14.5 ms per step and completes all 16 real-world crossing trials without collision, demonstrating deployment feasibility.
### Title:
          ArborSplat: Online Semantic Gaussian Splatting SLAM for Orchards
 - **Authors:** Alessandro Masini, Matteo Frosi, Mirko Usuelli, Matteo Matteucci
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Orchard robots need maps that preserve small but semantically important structures such as trunks, trellises, and fruit. 3D Gaussian Splatting (3DGS) SLAM achieves high photometric fidelity. However, its optimization remains appearance-driven, and transferring image semantics to 3D points is unreliable for thin structures, whose pixels may receive depth from background surfaces. We present ArborSplat, an online semantic 3DGS SLAM system that tracks with LiDAR odometry and optimizes semantics directly on the Gaussian map, constrained by class-specific height bands above a ground plane fitted to each keyframe's stereo point cloud, and fuses multi-view evidence into a semantic point cloud online while rejecting labels inconsistent with the local ground surface or with monocular depth. Class-constrained refinement reserves Gaussian capacity for underrepresented structures and, under reduced budgets, increases training-view accuracy on tree classes. We evaluate the approach on apple and pear orchards during dormancy, flowering, and harvesting. On full routes, it keeps ATE below 0.5 m on all 12 traversals. On shared 301-frame segments, it exceeds SGS-SLAM and GS3LAM by 0.23 to 0.50 training-view and 0.15 to 0.36 held-out mIoU while running 1.7 to 7.5 times faster, whereas SemGauss-SLAM runs out of GPU memory on all six.
### Title:
          Leveraging Vision-Based Point Cloud Map Priors for Camera-Based 3D Object Detection and Online Vectorized HD Mapping
 - **Authors:** Markus Käppeler, Rohit Mohan, Abhinav Valada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Camera-based 3D object detection and online vectorized HD mapping provide compact scene representations for autonomous driving, but both depend on accurate metric geometry and remain limited by depth ambiguity. Over long-term deployment, observations from repeated traversals can be accumulated into persistent point cloud priors that provide geometric context beyond the current observations. Existing explicit point cloud prior approaches, however, rely on LiDAR-based map construction and therefore require expensive 3D ranging sensors. We propose a framework that constructs a static point cloud prior map from previous camera traversals using Pi3X and augments each point with DINOv3 features. At runtime, a local prior patch is retrieved using global localization, encoded with a sparse voxel backbone, and fused in bird's-eye view (BEV) with lifted multi-view camera features. Task-specific sparse transformer heads then predict 3D objects and vectorized map elements from the fused representation. On Argoverse 2, the vision-based prior improves a strong baseline from 0.287 to 0.299 CDS and from 0.669 to 0.750 vectorized mapping mAP. Ablations show that semantic DINOv3 features are particularly important for vectorized mapping. These results demonstrate that vision-built geometric-semantic priors provide an effective form of long-term scene memory for camera-based perception, improving both tasks without LiDAR for prior-map construction or online inference.
### Title:
          SparseNav: Instruction-conditioned Sparse Semantic Perception for Training-Free Vision-Language Navigation
 - **Authors:** Quanhua Chen, Juhan Kang, Runfeng Lin, ZiFei Zhang, Enquang Feng, Chunran Zheng, Xiwang Dong, Jiarong Lin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Map-based vision-language navigation (VLN) relies on persistent spatial representations to connect language understanding with geometric planning. However, acquiring semantics beyond the needs of the current instruction can introduce unnecessary perception cost and irrelevant annotations. Continuously accumulating unrelated objects may not only waste computation, but also clutter the visual-spatial representation consumed by the vision-language model (VLM) planner. To address this problem, we present SparseNav, a training-free framework that follows a less-is-more principle for semantic navigation. SparseNav persistently maintains a lightweight geometric bird's-eye-view (BEV) map and sparse landmark memory, acquiring new semantics on demand using the active sub-instruction to decide what is worth grounding. An instruction manager first tracks navigation progress and identifies the active landmark query. An instruction-conditioned perception mechanism then invokes open-vocabulary segmentation when the queried landmark is visible and its metric location can inform the next decision. The resulting landmark memory supports VLM selection among hybrid frontier and local directional waypoint candidates. Without any additional training, SparseNav achieves success rates of 42.8% on R2R-CE and 40.7% on RxR-CE, both on the Val-Unseen splits. Controlled ablations examine semantic perception strategies and the contributions of individual framework components. Furthermore, we successfully deployed SparseNav on a Unitree Go2 quadruped equipped with an Intel RealSense D455 RGB-D camera for geometric mapping and landmark grounding and a Livox MID-360 LiDAR for localization, without a prebuilt map. We validated its effectiveness across multiple indoor environments using instruction-conditioned waypoint navigation.
### Title:
          Dr-LiSA: Direct Radar-Lidar Scan Alignment for $SE(3)$ Localization
 - **Authors:** Alex Zhang, Daniil Lisus, Cedric Le Gentil, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces Dr-LiSA, a first-of-its-kind direct method for localizing 2D spinning radar intensity measurements in $SE(3)$ against 3D lidar maps. Radar-lidar localization combines the complementary strengths of the two sensing modalities: radar is robust to adverse weather and precipitation, while lidar provides high-fidelity 3D maps in favourable conditions. However, existing radar-lidar localization methods are restricted to planar $SE(2)$ localization and have generally fallen short of the accuracy achieved by lidar-lidar and even radar-radar systems. A key challenge is the substantial sensing-modality gap between radar and lidar, which observe and represent scene structure in fundamentally different ways. Dr-LiSA bridges this gap using a learned forward model that predicts radar measurements from a lidar submap at a candidate pose, enabling direct photometric alignment of predicted and observed radar scans in $SE(3)$. Dr-LiSA outperforms prior radar-lidar approaches in $SE(2)$ while achieving planar accuracy competitive with state-of-the-art radar-radar localization across more than 90 km of on-road data.
### Title:
          Latent Commonality Expectation-Maximisation for Box-supervised Tree Crown Instance Segmentation
 - **Authors:** Thomas Pitts, Kunqi Li, Bin Liang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Individual tree crown segmentation from aerial imagery underpins tree-level carbon accounting, biodiversity, and restoration monitoring at landscape scale. However, existing models are predominantly trained on dense canopy forest imagery and degrade in savannah and drylands, where tree crowns are sparse, of variable appearance, and underrepresented in annotated benchmarks. These models also typically depend on costly polygon annotations. We introduce LACE (LAtent Commonality Expectation-maximisation), a box-supervised instance segmentation model, evaluated on 0.1 m/px aerial RGB tree crown imagery. LACE uses a frozen DINOv3-web ViT-L/16 encoder, applied at four spatial offsets and interlaced into a denser feature grid, with a lightweight CenterNet-style detection head trained solely on bounding boxes. We use expectation-maximisation to separate recurring appearance, the "treeness", within bounding boxes from surroundings. On the OAM-TCD benchmark test set, LACE reaches a mask AP$_{50}$ of $0.663 \pm 0.001$ (3 seeds) trained on 900 box-annotated images and without mask annotations, above the 0.626 scored by Restor's released mask-supervised Mask R-CNN, which was trained on the full ~4.2k image set. On a sparse-canopy holdout set, mask AP$_{50}$ rises to $0.691$ versus $0.612$ for Detectree2, a mask-supervised baseline. On NeonTreeEvaluation, using the official evaluation code, LACE reaches $0.728 \pm 0.003$ F1@0.4 (5 seeds) from 23,424 hand-annotated RGB boxes alone, matching the authors' DeepForest model's published 0.719, using under 0.1% of its training annotations and none of its LiDAR-derived 30M-crown pretraining set. By leveraging frozen self-supervised features, LACE matches or surpasses fully-supervised specialist baselines from boxes alone, removing the need for polygon annotation in tree crown instance segmentation for sparse-canopy environments where labelled data is scarce.
## Keyword: loop detection
There is no result 
## Keyword: nerf
### Title:
          NaCR: Visual Localization via NeRF-aided Camera Ray Regression
 - **Authors:** Yesheng Zhang, Xiang Dai, Xu Zhao, Chongyang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual localization (VL) is a fundamental technology for vision applications such as virtual reality. Recently, a novel VL paradigm, Camera Ray Regression (CRR), has emerged, which maps 2D image patches to 3D camera rays, but its accuracy is limited. To improve CRR accuracy, we notice a compelling duality: the inverse of this mapping is inherently performed by the novel view synthesis model, \ie, Neural Radiance Fields (NeRF). While NeRF renders image patches from camera rays via differentiable ray marching, CRR predicts the rays from image patches. Motivated by this complementary relationship, we propose NeRF-aided Camera Ray Regression (NaCR), a unified framework that seamlessly bridges NeRF and CRR at the ray level. First, NaCR incorporates three simple yet effective enhancements into the CRR baseline. Second, leveraging a pre-trained NeRF, NaCR augments the training data by synthesizing novel views tailored for efficient, patch-level consumption. Finally, exploiting the differentiability of NeRF, NaCR forms a closed-loop supervision pipeline where photometric rendering errors are back-propagated to optimize the predicted camera rays. To ensure stable convergence within the highly non-convex image space, we introduce a two-stage training curriculum. Extensive experiments across indoor and outdoor benchmarks demonstrate that NaCR achieves competitive accuracy. Comprehensive ablation studies validate the efficacy of each proposed component.
## Keyword: mapping
### Title:
          LLM-Driven Training-free Location-Attribute Synergic Fusion: A Closed-Loop Paradigm for Dual-source Encrypted POIs and LULC Mapping
 - **Authors:** Chang Li, Xingtao Peng, Yongjun Zhang, Yinfei He, Cairun Huang
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Dual-source encrypted points of interest (DSEP), POIs from two encrypted coordinate systems, suffer from intertwined location and attribute uncertainties, including nonlinear systematic misalignment and naming inconsistency, hindering land-use/land-cover (LULC) mapping. To the best of our knowledge, this paper is the first to propose an LLM-driven, training-free location-attribute synergic closed-loop optimization paradigm for DSEP fusion. The paradigm jointly refines location transformation and attribute correspondences through iterative feedback. Attribute-synergic location fusion uses an LLM-driven attribute matching method to establish DSEP correspondences, reducing matching complexity from O(N^2) to O(N), and refines transformation coefficients using an improved particle swarm optimization algorithm within ISODATA-clustered local subregions. Location-synergic attribute fusion then reassesses attribute confidence from updated geometric residuals through an LLM-fuzzy method. The refined correspondences feed back into location optimization, forming a bidirectional closed loop. Sample purification and adaptive radius contraction enable convergence in essentially two iterations. We further propose a training-free LULC mapping method that inherits land-use classes from encrypted maps through location fusion, producing vector-raster integrated LULC maps. A reference-free POI fusion evaluation method is applied across 31 provincial capitals and municipalities in mainland China. Experiments show that our method achieves an average DSEP location fusion residual of 4.58 m and attribute fusion accuracy of 95.12%, improving upon the open-source baseline and state-of-the-art method by 1.77 m and 14.87%, respectively. Overall, the method provides a training-free solution for DSEP fusion and enables georeferencing of encrypted vector data to WGS-84 without field-surveyed ground control points.
### Title:
          Indirect tipping: a social attack surface in AI agent populations
 - **Authors:** Ariel Flint, Luca Maria Aiello, Sara M. Constantino, Romualdo Pastor-Satorras, Andrea Baronchelli
 - **Subjects:** Subjects:
Multiagent Systems (cs.MA); Artificial Intelligence (cs.AI); Computers and Society (cs.CY); Systems and Control (eess.SY); Physics and Society (physics.soc-ph)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 As generative AI agents are deployed at scale, safety will depend not only on technical safeguards and individual model design, but also on collective equilibria that determine how agent populations process information, prioritize actions, and respond to uncertainty. Yet the same equilibria that enable agents to coordinate also create a social attack surface. The standard framework to assess this vulnerability is critical mass dynamics: the minimum fraction of adversarial agents required to overturn an equilibrium through direct competition. Here, we show that this approach risks underestimating system vulnerability by reducing the problem to the identification of singular tipping points, and ignoring indirect but potentially more efficient routes through which collective behavior can be redirected. Through experiments with populations of LLM agents and an analytic framework that captures their collective dynamics at scale, we map critical-mass thresholds that define a directed, weighted topology over the space of coordination equilibria, and treat this topology as a navigable landscape. We show that indirect tipping through intermediate stepping-stone equilibria can reduce the committed minority required to reach an alternative state, bypass majority requirements, and make possible transitions inaccessible through direct challenges. The diversity of available alternatives and timing of the attack further reshape this landscape, creating opportunities for control as well as risks of unintended destabilization. These results show that an equilibrium's resistance to committed intervention is not an intrinsic property but a structural feature of its competitive relations with alternative states. Securing populations of interacting AI agents therefore requires mapping this social landscape alongside individual agent capabilities and the technical channels through which they interact.
### Title:
          Beyond the Flat Seafloor: A Closed-Form Two-View Constraint to Aid Sidescan Sonar Reconstruction
 - **Authors:** Kalin Norman, Joshua G. Mangelson
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sidescan sonar is a common sensor for both manned and autonomous marine exploration and mapping, yet very few methods build upon or exploit the geometric projection model of the sensor. As sidescan sonar is limited to a 1D range measurement, many approximations are frequently used, including the long-standing assumption of a flat seafloor. Rather than make similar approximations, this paper focuses on a multi-view geometry based approach and formalizes a two-view geometric constraint and proves that a shared feature is constrained to a locus within the intersection of a sphere and a plane. In addition, we characterize what governs the size of the ambiguity locus through Monte Carlo simulation that is grounded in real aperture and mounting geometry for both a surface vessel and an underwater vehicle. We translate additional simulations of relative trajectories for both vehicle platforms into concrete survey-planning guidance. Our results show that locus length is strongly governed by elevation misalignment, and peaks at a moderate oblique crossing angle of approximately 20 degrees, with minimal locus lengths obtained at near parallel and anti-parallel passes.
### Title:
          Capability-Aware Arbitration for Semantic Intent-Based Shared Control
 - **Authors:** Zhaoda Du, Michael Bowman, Xiaoli Zhang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Shared control often allocates robot authority based on confidence in inferred human intent, assuming reliable autonomous execution. When this assumption fails, high intent confidence can cause over-helping. We present a capability-aware shared-control framework in which a vision-language model (VLM) infers human intent and provides semantic-intent confidence, while a vision-language-action (VLA) policy generates autonomous actions. VLA capability confidence is estimated online from the dispersion and local instability of stochastic action trajectories. We design a nonlinear arbitration policy that combines Bayesian-filtered semantic-intent confidence with VLA capability confidence through a sigmoid mapping to adapt robot authority. Our evaluation combined VLM/VLA confidence assessment with a study involving 12 participants performing pick-and-place and bidirectional stacking under in-distribution and out-of-distribution conditions. The proposed method achieved the highest task success rate (92%), compared with manual teleoperation (83%), intent-only arbitration (44%), and fixed equal-weight blending (10%). It also achieved higher control friendliness and lower authority-weighted disagreement than both shared-control baselines. These results demonstrate the benefit of incorporating VLA capability into authority allocation to mitigate over-helping and improve shared-control performance.
### Title:
          From Offline Proxies to Online Decisions: A Layered Engagement Evaluation Framework for Conversational AI
 - **Authors:** Xuanyi Li, Vaskar Nath, Hossein Amirkhani, Jay Li, Alex Deng
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Information Retrieval (cs.IR); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Online A/B experiments are the decision standard for user engagement, but traffic and readout time limit how many conversational-AI changes can be tested. We ask whether an offline signal designed to be computable without treatment-arm user exposure agrees with the outcomes of those experiments. We contribute a reusable construction and diagnosis checklist that treats an offline proxy as a chain of three alignments: behavioral label to product outcome, learned classifier to candidate-assistant behavior, and aggregated offline signal to experiment effect. A companion evaluation protocol audits the whole composite by interval-aware decision agreement, which compares offline and online confidence intervals instead of point estimates, and by within-experiment ranking. The instantiation we evaluate comprises a fixed evaluation suite on which candidate behavior is scored, an engagement classifier trained to predict session/prompt level engagements, and a calibration layer mapping sample-level score differences to online model-level engagement deltas. We then report the audit: 489 paired offline-online contrasts (one candidate arm against its control) from 27 experiments on a deployed multi-turn assistant, spanning model checkpoints to system-prompt tuning. Our primary test uses the 113 contrasts from eight experiments that ran after the map was frozen: on these the composite reaches 81.1% F1, against 34.3% for the raw classifier score it is built on, and makes no wrong-direction calls where that raw score makes 31. Every offline prediction was computed before its experiment ran to prevent overfitting. The evidence supports using the composite to prioritize candidates before scarce experiment traffic is allocated---in our deployment of the experiment, selecting among training checkpoints and tuning system prompts.
### Title:
          Effects of Assistance Delay on Joint Mechanics and Energetics in Biological Torque Control of a Hip Exoskeleton
 - **Authors:** Jimin An, Ryan Lee, Jingshu Peng, Eni Halilaj, Inseung Kang
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Biological torque control directly maps an estimated human joint moment to exoskeleton assistance, providing a task-agnostic strategy for supporting diverse locomotor activities. However, it remains unclear whether a fixed state-to-torque mapping provides effective assistance across biomechanically distinct tasks. We examined how assistance delay affected hip exoskeleton performance during level-ground (LG), ramp-ascent (RA), and ramp-descent (RD) walking. Eight participants completed a zero-torque baseline condition and five active assistance conditions with delays ranging from 40 to 320 ms. Across tasks and active delays, assistance reduced net metabolic rate by 5.24%, positive biological hip joint work by 5.86%, and total lower-limb positive joint work by 1.68% (all p < 0.05). Assistance delay affected both joint-work outcomes (both p < 0.001) but not net metabolic rate. Mechanical unloading generally decreased with increasing delay, whereas metabolic benefits remained comparatively stable. Relative to the zero-torque condition, net metabolic rate decreased by 9.75% during LG and 7.20% during RA but increased by 1.23% during RD. We did not detect task-dependent differences in the delay response. Our findings indicate that biological torque mappings should be evaluated based on the target outcome and mechanical role of the assisted joint, and that predominantly positive-power assistance may not generalize to negative-work-dominant locomotion without modification.
### Title:
          Data center cooling choices shift water impacts across the grid: An integrated water-energy model for sustainable data center development
 - **Authors:** Garrett Alston, Nancy Love, Rabab Haider
 - **Subjects:** Subjects:
Systems and Control (eess.SY); Computers and Society (cs.CY); Distributed, Parallel, and Cluster Computing (cs.DC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Data centers are being developed at an unprecedented pace, yet their energy and water impacts, and the spatial and temporal distribution of these impacts, remain poorly characterized. Data centers consume water for cooling (direct) and through electricity generation (indirect). Decisions on siting and cooling technology result in water-energy trade-offs that extend impacts beyond the facility's location. Existing assessment frameworks rely on facility efficiency metrics and average grid water intensity factors, suppressing the temporal impacts of data center load and generation availability. They also attribute indirect consumption to the facility's location rather than to the generators (and corresponding hydrologic regions) that respond to the added load, misattributing spatial impacts. To close this gap, we develop a computational model of the data center-energy-water nexus that links facility cooling and electricity demand with hourly economic dispatch, generator-level water consumption, and monthly subbasin depletion. Built on open-source data, the model resolves where and when water is consumed, and where this consumption compounds existing water risk or creates new risk. Using the model, we study different cooling configurations and proposed developments in the state of Michigan. Air-cooled data centers halve total water consumption relative to evaporative cooling, but increase electricity demand and raise indirect water consumption by one-third, shifting the water footprint from the facility to generators. Mapping these changes to subbasins reveals depletion increases beyond the data center sites, in regions that facility-level reporting may overlook. These results show that data center water and energy impacts cannot be assessed in isolation, motivating the need for integrated modeling to inform siting, design, and reporting practices.
### Title:
          RGSQ: Riemannian Geometry-Sensitive Quantization for Large Vision-Language Models
 - **Authors:** Zhiping Wu, Dongdong Ren, Yangchengyu Zhou, Zhengjie Zhang, Wenbin Li, Hongbing Pan, Yang Gao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large vision-language models (VLMs) can be efficiently deployed under stringent memory and latency constraints through post training quantization (PTQ). However, most PTQ methods are designed for unimodal large language models (LLMs). These methods treat quantization errors as isotropic perturbations under the Euclidean assumption, which provides weak guidance on directions most sensitive to quantization in VLMs. Consequently, directly adapting unimodal PTQ approaches or solely employing modality-specific scaling often leads to uneven bit-width distribution and inconsistent performance in low-bit settings. To address these challenges, we propose Riemannian Geometry-Sensitive Quantization (RGSQ), which formulates quantization as a reconstruction problem under a unified Fisher-Riemannian metric. RGSQ identifies modality-specific sensitive directions via Riemannian manifold mappings built from modality-partitioned empirical Fisher factors and fused into a modality-aware Kronecker-structured metric. We then apply geometry-aligned rotations to reorient the local tangent frame, steering low-bit perturbations toward loss-insensitive axes. Finally, we apply a whitening transformation that maps the Riemannian objective to an equivalent Euclidean form, enabling standard unimodal PTQ methods to evaluate multimodal quantization error under their original assumptions. Across an extensive and diverse set of mainstream VLM benchmarks, RGSQ achieves the highest accuracy and stability under extremely low-bit settings (W2A8 and W3A8). It outperforms VLM-aware baselines, such as MBQ and MQuant, by up to 5.9% and surpasses single-modality improvements by up to 8.6%.
### Title:
          SMTB: Fast Structure-Mapping with Tight Bounds
 - **Authors:** Daniel Weitekamp, Christopher MacLellan
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Structure-mapping forms analogies by aligning systems of relationally connected elements based on shared structure instead of surface features. We introduce a new structure-mapping algorithm: Structure-Mapping with Tight Bounds (SMTB) that is 5--15x faster than the structure-mapping engine (SME) and about 50\% better at finding mappings in large nested domains. SMTB is part of the broader Cognitive Rule Engine (CRE) project, a flexible multi-language-compatible framework with an accessible Python interface to state-of-the-art C++ implementations of core algorithms commonly used in cognitive systems such as pattern matching, planning, and structure-mapping. CRE and SMTB are designed to work with a wide range of representation choices. Unlike SME, which biases higher-order correspondences in tree-like predicate logic, SMTB maximizes relational connectivity without privileging higher-order relations. This allows SMTB to work just as well over arbitrary relational graphs as it does in tree-like domains of nested predicate logic. We discuss situations where privileging "higher-orderness" in structure-mapping can cause issues, and illustrate how SMTB avoids failure modes that SME would encounter in these situations. We also provide an evaluation comparing SMTB to SME v4 over 5845 domain pairs from the SME corpus.
### Title:
          Decoupling Disease, Covariates, and Individual Variability: A Unified Disentanglement Framework for Medical Image Classification
 - **Authors:** Shengjie Zhang, Jinglin Zhang, Zhuangzhuang Jiang, Ziqi Yu, Yipin Zhang, Qi Zhang, Xiang Chen, Haibo Yang, Fei Gao, Longbiao Cui, Yuan Zhou, Xiao-Yong Zhang, Alzheimer's Disease Neuroimaging Initiative
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Accurately isolating disease-related features from confounding covariates (e.g., age, gender, site) and individual variations remains a fundamental challenge in medical image classification. Traditional regression-based approaches may ignore non-linear relations between image features and true covariates. To overcome this issue, we present a generalized Medical Imaging Disentanglement Learning (MedIDL) framework. MedIDL maps image features into three mutually orthogonal latent spaces through specialized disentanglement heads: a disease classification head guided by a supervised loss, a covariate-alignment head constrained by cross-subject similarity matching, and a Gaussian head absorbing individual variations. We evaluated our framework across 7 datasets encompassing diverse imaging modalities. MedIDL outperforms state-of-the-art supervised and self-supervised classification methods in accuracy across all datasets. Association analyses demonstrate that MedIDL successfully isolates target-specific latent representations. Gradient-based interpretability mappings localize pathognomonic patterns aligning with established clinical literature.
### Title:
          Interpretable AI plus Handheld, Portable Retinal Photographs: A Low-Cost Glaucoma Screening Solution for West Africa
 - **Authors:** Charis Y. N. Chiang, Tarela Sarimiye, Adeyinka Ashaye, Martin Buist, Michael A. Hauser, Olusola Olawoye, Michaël J.A. Girard
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Purpose: To develop and evaluate an interpretable artificial intelligence (AI) framework for glaucoma screening from low-cost portable, handheld retinal fundus photographs in a West African population and to compare its performance with clinical tabletop fundus imaging. Methods: We used data from a community-based study of 681 participants (1,362 eyes) in Nigeria, comprising 414 glaucoma, 478 glaucoma suspect, and 470 non-glaucoma eyes. Fundus photographs were acquired using the low-cost handheld, portable Volk Viva retinal camera and the Canon CR-2-AF tabletop camera. We fine-tuned component models separately to each device to perform vessel segmentation, cup and disc boundary segmentation, and feature extraction to detect optic nerve head features. A final classification model combined these components to classify scans as glaucoma, glaucoma suspect or non-glaucoma. Feature-weight analysis and Gradient-weighted Class Activation Mapping were used for interpretation. Results: The models performed well on both Volk Viva and Canon CR-2-AF images: Vessel segmentation: 0.98 Dice Coefficient (DC) (Volk) and 0.94 DC (Canon); Cup and disc segmentation: 0.95 DC (Volk) and 0.96 DC (Canon); Optic nerve head feature detection: area under the receiver operating characteristic curve (AUCs) of 0.83$\pm$0.03 (Volk) and 0.87$\pm$0.04 (Canon); Classification model: AUCs of 0.85$\pm$0.01 (Volk) and 0.93$\pm$0.01 (Canon). Reports for each image, present model decision confidence scores and decision-rationale visualizations to support clinical interpretation. Conclusions: Volk Viva results were reasonably comparable to Canon CR-2-AF in the component models and not far behind in classification. This shows that interpretable AI combined with low-cost, portable imaging may enhance community-level glaucoma screening, especially in settings with limited specialist access and resources.
### Title:
          Annual Earth-observation embeddings encode wildfire disturbance and support simplified burned area mapping
 - **Authors:** Jovana Knezevic, Clement Atzberger, Zhengpeng Feng, Adam F. A. Pellegrini, Srinivasan Keshav, David Coomes
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Medium-resolution (10-30 m) burned area mapping is vital for monitoring wildfires and their impacts, but remains difficult to scale. Existing methods require either curated fire-specific imagery or dense time-series analysis. Here, we tested whether annual Earth-observation embeddings retain wildfire disturbance signals sufficiently to map burned areas without either requirement. Using Tessera and AlphaEarth embeddings, we tested individual burn-scar delineation, mapping of all same-year fires within an area, regional wall-to-wall mapping, cross-continental transfer, and intra-annual fire timing. Tessera strongly encoded wildfire disturbance, allowing even linear models to separate burned from unburned pixels; the signal was weaker in AlphaEarth. Models trained on a single Tessera embedding matched or exceeded equivalent models using paired pre- and post-fire HLS imagery, and outperformed post-fire imagery alone. The same approach mapped all same-year fires within benchmark scenes (F1 = 0.90). Applied across California, with no California fire data used for downstream training, it recovered 97% of reference burned area and detected substantially more small and medium-sized fires than GABAM or MCD64A1. Separately, a model trained on 2018-2021 US fires transferred without retraining to 88 European fires from 2024-2025 (F1 = 0.88). For well-detected fires, ignition timing was recovered with a mean absolute error of 13 days. Performance declined for fires ignited near the end of the calendar year, and wall-to-wall deployment produced systematic false positives in some unseen landscapes. Annual embeddings nevertheless achieve high segmentation accuracy while moving the burden of dense time series processing upstream, providing a promising path towards simpler regional burned area mapping.
### Title:
          Syndrome, Synergy, and Safety: Structured Reasoning and Knowledge-Driven Alignment for TCM Prescription Generation
 - **Authors:** Zheng Chen, ZhiCheng Du, Haoxuan Li, Peiwu Qin
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Applying large language models to Traditional Chinese Medicine (TCM) prescription generation reveals three clinically critical gaps: models produce end-to-end mappings without auditable reasoning following the li-fa-fang-yao paradigm (SR Gap), treat each encounter in isolation without follow-up adjustment via sui zheng jia jian (LA Gap), and fail to enforce absolute contraindication rules such as Shi Ba Fan (SC Gap). We propose a progressive four-stage framework (SFT $\to$ PG-CoT $\to$ Dynamic $\to$ K-RL) that addresses each gap: PG-CoT constrains CoT distillation under the li-fa-fang-yao paradigm to produce auditable diagnostic chains, Dynamic SFT models patient trajectories with explicit transition reasoning, and K-RL encodes deterministic pharmacological rules as rule-based DPO preference signals. Across 12 fine-tuned models and 6 zero-shot baselines, our framework substantially improves prescription quality over zero-shot baselines---with a 7B model (Mistral-7B) surpassing zero-shot GPT-5 on all three TCM evaluation metrics.
### Title:
          What Was Once Learned May Need to Be Unlearned: Machine Unlearning for Deprecated API Knowledge in Large Language Models
 - **Authors:** Jin Liu, Yanzhong He, Guancheng Lin, Xiao Liu, Jacky Wai Keung, Xiao Yu, Xiaoxue Ma
 - **Subjects:** Subjects:
Software Engineering (cs.SE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) for code completion may generate deprecated APIs because their pre-training corpora contain code from historical library versions. Existing approaches use inference-time intervention, model editing, or machine unlearning, but multiple plausible completions make predefined replacements restrictive. Moreover, existing studies rarely verify whether models exhibit the targeted deprecated behavior or evaluate unintended changes to other APIs. We conduct a systematic empirical study of machine unlearning for deprecated API knowledge and construct MUDAPIBench, a behavior-grounded benchmark with over 7,000 model-specific instances derived from 145 deprecated-to-up-to-date API mappings across eight Python libraries. Instances are retained only when the original model generates the target deprecated API. We evaluate eight representative unlearning methods across three code LLMs on deprecated API forgetting, up-to-date API generation, preservation of other and unrelated API behaviors, general code-generation capability, and efficiency. Results show that Gradient Difference (GD) provides the best overall trade-off, suppressing deprecated APIs while preserving other capabilities with moderate computational costs. Further analyses reveal substantial variation across libraries and show that APIs deprecated after the model's training-data cutoff are harder to forget. Layer-wise analyses indicate that GD achieves effective forgetting with comparatively controlled internal changes.
### Title:
          When Are Aggregate Agent Traces Diagnosable? Traffic-Governed Interpretation and Calibrated Abstention
 - **Authors:** Peiying Zhu, Sidi Chang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Runtime traces can appear transparent, but a closed-loop policy determines which states are visited and which failures become visible. We study a simulated hotel-pricing agent mapping time, inventory, and market state to discrete price actions under varying demand regimes. A fault may leave no aggregate trace when the policy rarely visits affected cells. We treat entry into aggregate-only fault interpretation as a diagnosability decision preceding scoring or localization. A reference-map gate requires repeated clean-policy support; a matched runtime gate then requires joint support in clean and current streams. Signal analysis occurs only after both pass. We calibrate false admission on a disjoint clean stream at the physical-component level and model detection by affected clean traffic rather than nominal cell coverage. In a frozen one-shot heldout, 55/72 (76.4%) regime-component units were reference-admitted, representing 20 physical components; 54/55 passed matched runtime admission, while the rejected unit abstained. Stable false admission was 0/20, with a one-sided exact 95% upper bound of 0.1391, meeting the frozen 0.20 criterion. Across 540 repeated unit-arm rows nested in those 20 clusters, affected clean traffic reduced negative log likelihood by 29.3% relative to cell coverage, a gain of 0.1264 nats per row (cluster-bootstrap 95% interval [0.0593, 0.1918]). Adding mask family and its interaction improved log loss by 0.0015 nats per row (one-sided upper bound 0.0066), below the frozen 0.01 practical-sufficiency margin. A development audit found that exact minimum hitting set and greedy selection chose identical supports in 12/12 scenarios because singleton evidence had resolved the conflicts. The result is a bounded rule for interpreting aggregate agent behavior: first establish exposure, then score change, and abstain when the trace cannot support the claim.
### Title:
          Metric-Bench: Exploring In-context Spatial Metric Reasoning in VLMs for Indoor Scenes
 - **Authors:** Yuling Xi, Haokai Zhang, Muzhi Zhu, Hao Zhong, Zongze Du, Hengyu Zhao, Chenchen Jing, Yufei Yin, Bin Qin, Yongjie Yang, Zhenbo Luo, Hao Chen, Chunhua Shen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Multimedia (cs.MM)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Metric reasoning is a critical and challenging task for Vision Language Models (VLMs), playing a pivotal role in embodied AI tasks such as robotic manipulation and autonomous navigation. However, current spatial reasoning remains bottlenecked by rigid pixel-level supervision; such localized optimization often compromises general multimodal intelligence, triggering performance degradation or catastrophic forgetting of broad reasoning capabilities. To address these limitations, we introduce Metric-Bench, a focused benchmark designed to guide metric-spatial reasoning using contextual information. By incorporating in-image reference objects with known physical dimensions, Metric-Bench guides models to implicitly learn the 2D-to-3D mapping without camera intrinsics. We further present MetricReasoner, a task-adapted reinforcement fine-tuning recipe for reference-grounded metric reasoning, using structured prompts and verifiable numerical rewards. Extensive experiments on Metric-Bench demonstrate that our approach significantly enhances spatial metric understanding, outperforming existing and even larger proprietary models by 43.1\%, while improving downstream embodied performance over a spatial-specialized counterpart by 30.4\% on RoboSpatial overall accuracy and 9.3\% on ERQA, and additionally delivering consistent gains on general benchmarks (15.9\% on V$\star$Bench, 88.9\% on BLINK), indicating that the proposed adaptation does not necessarily compromise general VLM capabilities.
### Title:
          Decoupling Logical Masks from GPU Execution for Dynamic Block-Sparse Attention
 - **Authors:** Shanghao Liu, Xiaoyun Yu, Wanting Li, Wenqi Jiang
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Attention computation makes inference expensive in video diffusion transformers (vDiTs), which generate videos through iterative denoising. Block-sparse attention (BSA) reduces this cost by computing only blocks selected by a logical mask, which specifies attention interactions to compute. However, coupling logical block geometry to execution choices limits adaptation to varying masks and graphics processing units (GPUs), while runtime kernel specialization can incur preparation overhead that outweighs execution time savings. We present Tessera, a specialized runtime for dynamic BSA that decouples logical masks from GPU execution while preserving specified attention interactions. Its physical mapping layer retains, combines, or subdivides logical attention blocks into physical tiles suited to different attention mask shapes and GPU architectures. Its task organization layer groups and schedules tiles within GPU tasks to reuse data, expose parallelism, and overlap data movement with computation. Finally, profile-guided regime selection enables low- overhead execution plan selection through a lookup table constructed from offline profiling. We implement Tessera with specialized CUDA kernels supporting four NVIDIA GPU generations. Evaluated on 2,315 real attention masks and industrial video diffusion models, Tessera achieves up to 6.79x BSA request speedup over baseline systems in the evaluated video diffusion models.
### Title:
          NaCR: Visual Localization via NeRF-aided Camera Ray Regression
 - **Authors:** Yesheng Zhang, Xiang Dai, Xu Zhao, Chongyang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual localization (VL) is a fundamental technology for vision applications such as virtual reality. Recently, a novel VL paradigm, Camera Ray Regression (CRR), has emerged, which maps 2D image patches to 3D camera rays, but its accuracy is limited. To improve CRR accuracy, we notice a compelling duality: the inverse of this mapping is inherently performed by the novel view synthesis model, \ie, Neural Radiance Fields (NeRF). While NeRF renders image patches from camera rays via differentiable ray marching, CRR predicts the rays from image patches. Motivated by this complementary relationship, we propose NeRF-aided Camera Ray Regression (NaCR), a unified framework that seamlessly bridges NeRF and CRR at the ray level. First, NaCR incorporates three simple yet effective enhancements into the CRR baseline. Second, leveraging a pre-trained NeRF, NaCR augments the training data by synthesizing novel views tailored for efficient, patch-level consumption. Finally, exploiting the differentiability of NeRF, NaCR forms a closed-loop supervision pipeline where photometric rendering errors are back-propagated to optimize the predicted camera rays. To ensure stable convergence within the highly non-convex image space, we introduce a two-stage training curriculum. Extensive experiments across indoor and outdoor benchmarks demonstrate that NaCR achieves competitive accuracy. Comprehensive ablation studies validate the efficacy of each proposed component.
### Title:
          Unsigned Distance Maps on 2D Point Cloud Registration
 - **Authors:** Ricardo B. Sousa, Giorgio Grisetti, Héber Miguel Sobreira, Carlos André Silva, António Paulo Moreira
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 2D point cloud registration arises in laser odometry and Simultaneous Localization and Mapping (SLAM) for mobile robots. Iterative Closest Point (ICP) is one of the most widely used approaches. Still, its iterative procedure recomputes correspondences via nearest-neighbor search at every iteration, whereas correspondence-free alternatives focus on scan-to-map alignment. This paper proposes a 2D point cloud registration approach based on unsigned distance maps, precomputing the Euclidean distance to the nearest reference point, along with its spatial derivatives, over a discrete grid, replacing the per-iteration search with O(1) lookups. Moreover, point-to-point and point-to-plane error formulations are derived on the SE(2) manifold and solved via Gauss-Newton optimization. On a synthetic benchmark and the real-world IILABS 3D dataset, the precomputed point-to-point variant outperforms its analytical counterparts, achieving competitive laser-odometry drift compared to point-to-plane formulations, as the precomputed gradient regularizes correspondences in the presence of sensor noise.
### Title:
          An Action Is Worth One Patch: Unified World-Action Modeling with PatchWAM
 - **Authors:** Tianheng Wang, Zhou Xie, Heng Jia, Jianhua Xu, Tong Zhang, Kaicheng Yu
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative visual models offer a foundation for learning representations of physical dynamics, yet their extension to continuous control raises a fundamental question: do visual prediction and action generation require separate computational pathways? Existing approaches usually introduce trainable action heads or separate action experts to bridge low-dimensional states and high-dimensional visual representations. In this work, we explore whether the visual backbone's existing capacity can also support control when actions are expressed in a compatible representation. Thus, we introduce PatchWAM (Patch World-Action Model), which treats continuous actions as another type of patch through a fixed mapping called Action-as-Patch. This allows a single model to predict both how the robot should move and what the scene may look like afterward. Visual prediction and action generation become parts of the same generative process, without a dedicated action head or separate action expert. Experiments with subsampled training windows show gains over a matched dual-expert control, while benchmark evaluations reach 91.8% success rate on LIBERO-Plus and 96.12% on RoboTwin 2.0 in a full-data setting with additional augmented demonstrations. More broadly, the result suggests that capability need not be added where it can be inherited: the constraint on extending a generative backbone is the interface a new signal is written in, not the capacity to model it.
### Title:
          Domain-Adaptive Pretraining Enhances Water Treatment Semantic Representation for Large-Scale Structured Literature Mining
 - **Authors:** Mudi Zhai (1), Ruihong Qiu (2), Qingyun Zeng (3,4), T. David Waite (1), Bing-Jie Ni (1), Haoran Duan (1,5) ((1) UNSW Water Research Centre, School of Civil and Environmental Engineering, The University of New South Wales, Sydney, NSW 2052, Australia (2) School of Electrical Engineering and Computer Science, The University of Queensland, Brisbane, QLD 4072, Australia (3) Microsoft Copilot Studio AI, Redmond, WA 98052, United States (4) Departments of Mathematics &amp; Department of Computer and Information Science, University of Pennsylvania, Philadelphia, PA 19104, United States (5) Department of Civil Engineering, The University of Hong Kong, Pokfulam, Hong Kong SAR, China)
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Water treatment research is expanding rapidly, but much of the knowledge acquired from this research remains scattered across unstructured literature. The field still lacks a dedicated language model that can efficiently capture water treatment-specific domain semantics for large-scale literature mining. Here, we address this by developing WaterBERT, a domain-adapted encoder model designed for semantic representation and structured information extraction from water treatment texts. WaterBERT was developed by continual pretraining on a large-scale water treatment corpus comprising about 2.97 billion tokens. Three fine-tuned models based on WaterBERT were systematically evaluated on downstream tasks, achieving the best overall performance among general-purpose and domain-specific BERT models, with F1 scores of 90.12% for multiclass treatment process classification, 79.50% for named entity recognition, and 74.04% for relation extraction. Beyond these benchmark tasks, we further demonstrated WaterBERT's advantages for large-scale literature processing. Applied to 5,144 Environmental Science & Technology articles, WaterBERT-BERTopic identified coherent, diverse, and domain-specific research topics without predefined categories. Building on WaterBERT, we processed 693,211 abstracts at substantially lower cost than commercial LLMs while retaining competitive extraction performance to construct a structured water treatment knowledge graph. The knowledge graph was then integrated with lexical and dense retrieval to develop a Water Knowledge-Enhanced Retrieval System (WaterKERS), which achieved a relevance score of 77.7, substantially outperforming text-based retrieval baselines (54.7-64.5). Through WaterBERT, this study provides a compact and scalable semantic foundation for large-scale information processing and evidence mapping in water treatment research.
### Title:
          Cellular-Communication-Level Interpretability for Pathology Foundation Models via Graph Distillation on Microenvironment
 - **Authors:** Yuxiang Xiao, Zhiwei Chen, Dan Dai, Wei Li, Tianyang Zhang, Yakun Ju, Yang Hu, Kaixiang Yang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Pathology foundation models (PFMs) provide strong tile-level representations but remain difficult to interpret at the cellular and microenvironmental scales that underpin clinical reasoning. We introduce Graph-Interpreter (G-Interp), a graph-distillation framework that equips a frozen PFM teacher with a cellular-communication-level "plug-in" interpreter, without modifying the teacher. For each tile, we segment cells as graph nodes and construct a microenvironment graph based on spatial adjacency. Graph neural network (GNN) students distil the PFM embedding, whilst learning attention-based message passing that yields node- and edge-level importances. We interpret these importances as cell-cell communication evidence, providing fine-grained explanations of how PFMs encode microenvironmental context. To stabilise distillation when graph abstraction is imperfect, we employ a lightweight auxiliary student to supply complementary visual cues and condition graph message passing, while keeping the primary interpretability signal graph-derived. We evaluate explanation faithfulness by mapping graph-selected evidence back to the image using instance masks and measuring teacher sensitivity under targeted vs non-target occlusions. Across multiple histopathology tasks, G-Interp produces highly scalable, microenvironment-aware explanations, while maintaining competitive predictive performance.
### Title:
          Acoustic Ellipses: Bio-Inspired Omnidirectional Echolocation in Cooperative Multi-Agent Systems using Frequency Sweeps
 - **Authors:** Petras Swissler, Lindsay Burke, Julia Hyland Bruno
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Inspired by the flight and song of birds, we propose an approach that enables cooperating agents to effectively identify obstacles in their environment by having a stationary source agent emit a frequency-modulated chirp while one or more listener agents observe the direct and reflected signals while in motion. We present a novel mapping approach that exploits the ``frequency gap'' between direct and reflected chirp signals to define candidate reflection ellipses, which are then fed into a 2D accumulation filter to identify locations with the highest density of potential reflections. We demonstrate this work first with simulation results derived from an efficient, bespoke audio simulator, examining the effect of obstacle count, sampling rate, and path curvature on the ability to accurately identify environmental obstacles for a one-listener scenario. We then examine different cooperative motion strategies for two-listener configurations. Finally, we validate the real-world viability of this approach through field experiments in an outdoor park setting to demonstrate the ability to identify frequency gaps using off-the-shelf hardware. Our results provide a foundation for a low-cost approach to environmental mapping in swarm robotic systems.
### Title:
          TSS: Target-Side Sparsification for Speculative Decoding in Domain-Specific Large Language Models
 - **Authors:** Haibo Hu, Lianming Huang, Qiao Li, Nan Guan, Chun Jason Xue
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Speculative decoding accelerates large language model inference through collaboration between a lightweight draft model and a target verifier. Existing methods mainly improve the draft side, while the target model is typically kept dense and unchanged. We show that, under domain-specific inference, full-depth target verification is not always the optimal choice. Counter-intuitively, skipping selected target layers can reduce verification cost while simultaneously increasing draft acceptance and preserving, or even improving, downstream task performance. Based on this observation, we propose TSS, a target-side sparsification framework for speculative decoding. TSS employs an acceptance- and metric-aware breadth search to explore multi-layer skip configurations without imposing a fixed priority between the two objectives. The selected configurations are stored in a domain-to-configuration mapping and applied by a lightweight skip controller, allowing one complete target model to support multiple sparse verification paths without retraining or permanent parameter pruning. Experiments on Spec-Bench across multiple domains, model scales, and speculative decoding methods show consistent improvements in draft acceptance and downstream task performance. In Translation setting, TSS increases the average accept length from 2.70 to 4.53 (+67.8%), improves BLEU from 0.131 to 0.237 (+80.9%), and raises end-to-end throughput from 75.6 to 127.3 tokens/s, corresponding to a 1.68X speedup.
### Title:
          EADC: Evaluation of Advanced and Deep-level Compliance in Large Language Models
 - **Authors:** Yan Zhang, Ruien Li, Yaoyao Peng, Wanxin Ren, Yijia Zhang, Wusheng Zhang, Guangwen Yang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large Language Models (LLMs) have been used in various industries. However, ensuring their compliance with complex laws and regulatory frameworks remains a great challenge. Existing evaluation paradigms mainly rely on static benchmarks that suffer from three severe limitations: First, the compliance rules being used do not comply with the requirements of Artificial Intelligence (AI) laws and regulations; Second, they only handle apparent, explicit compliance risks, leaving implicit and covert compliance risks undetected; Third, they fail to track the systematic propagation of risks along logical dependency chains or evaluate compliance within nuanced, context-based real-world scenarios. To bridge this critical gap, we introduce EADC, a novel advanced evaluation benchmark of LLMs based on an AI compliance knowledge graph and AI compliance legal experts. By mapping abstract legal rules into structured logical multi-relational graphs, our framework enables automated, evolving agents to distill and synthesize highly sophisticated adversarial scenarios. This compliance benchmark is reviewed and corrected by human AI legal experts throughout the whole process. The resulting dataset (4,435+ QA pairs) provides an extensive, multi-dimensional taxonomy covering critical regulatory frontiers, including bias and discrimination, fairness, personal privacy protection, and values. Crucially, our compliance dataset moves beyond shallow string-matching by incorporating contextual long-horizon interactions and logic-driven hazard chains, capturing deeply embedded compliance anomalies that bypass traditional filters. Experiment evaluations demonstrate that our framework exposes critical regulatory blind spots in state-of-the-art LLMs, offering a rigorous, AI laws and regulations-aligned benchmark to safeguard high-level and deep compliance in the application of LLMs.
### Title:
          Leveraging Vision-Based Point Cloud Map Priors for Camera-Based 3D Object Detection and Online Vectorized HD Mapping
 - **Authors:** Markus Käppeler, Rohit Mohan, Abhinav Valada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Camera-based 3D object detection and online vectorized HD mapping provide compact scene representations for autonomous driving, but both depend on accurate metric geometry and remain limited by depth ambiguity. Over long-term deployment, observations from repeated traversals can be accumulated into persistent point cloud priors that provide geometric context beyond the current observations. Existing explicit point cloud prior approaches, however, rely on LiDAR-based map construction and therefore require expensive 3D ranging sensors. We propose a framework that constructs a static point cloud prior map from previous camera traversals using Pi3X and augments each point with DINOv3 features. At runtime, a local prior patch is retrieved using global localization, encoded with a sparse voxel backbone, and fused in bird's-eye view (BEV) with lifted multi-view camera features. Task-specific sparse transformer heads then predict 3D objects and vectorized map elements from the fused representation. On Argoverse 2, the vision-based prior improves a strong baseline from 0.287 to 0.299 CDS and from 0.669 to 0.750 vectorized mapping mAP. Ablations show that semantic DINOv3 features are particularly important for vectorized mapping. These results demonstrate that vision-built geometric-semantic priors provide an effective form of long-term scene memory for camera-based perception, improving both tasks without LiDAR for prior-map construction or online inference.
### Title:
          Combining Hierarchical Cognitive Process with Process Supervision for Interpretable Scene Safety Understanding
 - **Authors:** Zhiyun Jiang, Hanyong Wang, Binbin Liang, Yu Xie, Zhengjie Wang, Menglong Yang, Wei Li
 - **Subjects:** Subjects:
Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Scene safety understanding plays a life-or-death role in situational awareness in various critical domains. Traditional methods that rely on learning direct mappings between scenes and safety levels often lack interpretability, limiting their reliability in critical applications. An effective approach to overcoming this challenge lies in interpreting human cognitive processes and equipping machine models with analogous cognitive capabilities. This work explores an effective way of integrating scene safety cognitive process modeling and process supervision. Specifically, we first construct a hierarchical cognitive safety structure, which motivates the development of a novel, high-quality scene safety understanding dataset based on multi-step reasoning with process labels. This dataset serves both as a benchmark and a resource to improve the safety reasoning capabilities of Large Language Models (LLMs), while also enabling a granular analysis of intermediate reasoning steps through information flow and saliency-based techniques. Building upon this foundation, we introduce a modular and flexible process supervision framework that reflects the hierarchical nature of human cognition. This framework leverages LLMs as the core architecture and incorporates Low-Rank Adaptation(LoRA) and Mixture-of-Experts (MoE) strategies to enable specialization and collaboration among expert modules, each tasked with specific sub-processes of the overall reasoning chain. Systematic experimental evaluations and analyses confirm that our framework exhibits superior interpretability and performance characteristics compared to traditional approaches.
### Title:
          SparseNav: Instruction-conditioned Sparse Semantic Perception for Training-Free Vision-Language Navigation
 - **Authors:** Quanhua Chen, Juhan Kang, Runfeng Lin, ZiFei Zhang, Enquang Feng, Chunran Zheng, Xiwang Dong, Jiarong Lin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Map-based vision-language navigation (VLN) relies on persistent spatial representations to connect language understanding with geometric planning. However, acquiring semantics beyond the needs of the current instruction can introduce unnecessary perception cost and irrelevant annotations. Continuously accumulating unrelated objects may not only waste computation, but also clutter the visual-spatial representation consumed by the vision-language model (VLM) planner. To address this problem, we present SparseNav, a training-free framework that follows a less-is-more principle for semantic navigation. SparseNav persistently maintains a lightweight geometric bird's-eye-view (BEV) map and sparse landmark memory, acquiring new semantics on demand using the active sub-instruction to decide what is worth grounding. An instruction manager first tracks navigation progress and identifies the active landmark query. An instruction-conditioned perception mechanism then invokes open-vocabulary segmentation when the queried landmark is visible and its metric location can inform the next decision. The resulting landmark memory supports VLM selection among hybrid frontier and local directional waypoint candidates. Without any additional training, SparseNav achieves success rates of 42.8% on R2R-CE and 40.7% on RxR-CE, both on the Val-Unseen splits. Controlled ablations examine semantic perception strategies and the contributions of individual framework components. Furthermore, we successfully deployed SparseNav on a Unitree Go2 quadruped equipped with an Intel RealSense D455 RGB-D camera for geometric mapping and landmark grounding and a Livox MID-360 LiDAR for localization, without a prebuilt map. We validated its effectiveness across multiple indoor environments using instruction-conditioned waypoint navigation.
### Title:
          The Disciplinary Language Transfer Problem: How Psychological Vocabulary Produces Governance Failures in AI Agent Deployment
 - **Authors:** Kymberly Lasser-Chere, Tyler Akidau, Marc Millstone
 - **Subjects:** Subjects:
Computers and Society (cs.CY); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 The vocabulary used to describe AI agents in governance contexts -- learning, memory, values, compliance, identity, trust -- is borrowed from psychological and organizational science, contributing to systematic failures in how organizations deploy, oversee, and hold agents accountable. This paper argues that the problem is not merely terminological but epistemological: psychological vocabulary carries an "invisible grammar" of its home discipline into governance discourse, calibrating frameworks to a metaphysical entity that does not exist in current AI architectures. We call this the disciplinary language transfer problem. Drawing on Wittgenstein's concept of language games, Kuhn's paradigm-laden observation, Haraway's situated knowledge, and Star and Griesemer's boundary object theory, we show that the transfer operates at three levels (epistemological assumptions, theoretical constructs, and surface vocabulary), each requiring a different remediation. We characterize six foundational epistemological assumptions embedded in Western psychological governance discourse, trace their origin in specific philosophical traditions, and show why each fails when applied to systems without developmental continuity. The paper's practical output is an actionable Disciplinary Audit: a six-question governance document scan operationalized through a translation taxonomy of thirty-seven terms mapping operational constructs to agent-appropriate replacements, presented here in abridged form and openly archived in full. The vocabulary reform proposed here is not merely terminological; it is the condition of possibility for governance frameworks that correctly identify what they are governing.
## Keyword: localization
### Title:
          mbariml: a curation pipeline for turning deep-sea imagery and video into object-detection training data
 - **Authors:** Lonny Lundsten, Kevin Barnard, Dave Caress
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Training data quantity and quality greatly affect object detection model performance, regardless of model architecture. When using object detection models on video and images from the deep sea, in which the objects of interest, primarily organisms, are sparse, faint, and hard to identify, incremental improvements to object detector performance may require an iterative approach to data labeling and management. This paper presents mbariml, a python-based video and image analysis pipeline built around the data labeling management process. mbariml uses an Ultralytics YOLO detection model, runs it over still images or video, stores every detection as a reviewable region of interest, groups those regions by visual similarity so that a human can accept or reject them in bulk, and exports the result as training data, statistics, image sidecars, and additional metadata. The human review stage is the centre of the design: an annotator can validate, relabel, resize, delete, and draw entirely new localizations, and every one of those edits is written back to the same database the detector wrote to. Video receives particular attention: the software treats each tracker-produced track as a provisional observation and selects one representative frame instead of retaining every detection in the track. We describe the pipeline stage by stage, including the operational middle-third heuristic used for track observation selection.
### Title:
          CDKF-Track: Cluster-aware Data-Driven Kalman Filtering for Cooperative 3D Multi-Object Tracking
 - **Authors:** Maria Damanaki, Nikos Piperigkos, Alexandros Gkillas, Aris S. Lalos
 - **Subjects:** Subjects:
Robotics (cs.RO); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multi-Object Tracking (MOT) is essential for EdgeAI perception systems, where accurate object localization and reliable identification enable safe decision-making. Singleagent MOT suffers from occlusions, sensor noise, and partial scene understanding in complex real-world scenarios. While multi-agent systems improve robustness by exploiting shared information, they introduce redundant measurements that lead to false data associations, and still struggle to capture nonlinear object dynamics. To address these challenges, we propose CDKFTrack, a Cluster-aware Data-Driven Kalman Filtering framework for Cooperative 3D MOT. The proposed method first fuses multivehicle 3D LiDAR detections through a Graph Laplacian-based formulation. Then, a cluster-aware redundancy reduction scheme groups spatially related detections and selects representative observations to reduce duplicate inputs to the tracker. The resulting detections are processed by a data-driven Kalman filter that learns object motion dynamics from data, reducing dependence on predefined linear motion assumptions. Furthermore, a wavelet-based temporal refinement module leverages the multiresolution decomposition property of wavelets to attenuate shortterm positional fluctuations and improve trajectory continuity. To the best of our knowledge, CDKF-Track is the first framework to jointly address detection-level fusion redundancy and learnable motion modeling in cooperative 3D MOT. Experimental results on the real-world V2V4Real dataset indicate that CDKF-Track achieves up to 27.99% improvements in tracking accuracy over state-of-the-art multi-agent MOT methods.
### Title:
          When Point Clouds Outperform Pixels: Rethinking Zero-Shot Multimodal Anomaly Detection
 - **Authors:** Chenglin Ye, Lupeng Liu, Dongbo Yu, Jun Xiao, Yunbiao Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Zero-shot multimodal anomaly detection commonly assumes that RGB and point cloud modalities are equally reliable and can contribute uniformly to anomaly localization. We challenge this assumption. Using a set of recently proposed stringent metrics that penalize false anomaly responses in normal regions, we find that point clouds are substantially more reliable than RGB under zero-shot category shift. Motivated by this observation, we propose WOOPS (\textbf{W}hen P\textbf{o}int Cl\textbf{o}uds Out\textbf{p}erform Pixel\textbf{s}), a reliability-aware zero-shot multimodal anomaly detection framework. To strengthen the more reliable geometric modality, we design a Multi-view Information Decoupling module to suppress heterogeneous information from multi-view point cloud projections and enhance point cloud feature quality. To avoid unconditional fusion, we further introduce a Modality Reliability Calibration module to adaptively calibrate modality contributions according to their reliability. Extensive experiments show that our method achieves the best or competitive performance under the new metrics in both unimodal and multimodal settings. Further analysis demonstrates that point cloud information also improves RGB-only inference, while ablations verify the effectiveness of both modules. Code will be released upon acceptance.
### Title:
          When Are Aggregate Agent Traces Diagnosable? Traffic-Governed Interpretation and Calibrated Abstention
 - **Authors:** Peiying Zhu, Sidi Chang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Runtime traces can appear transparent, but a closed-loop policy determines which states are visited and which failures become visible. We study a simulated hotel-pricing agent mapping time, inventory, and market state to discrete price actions under varying demand regimes. A fault may leave no aggregate trace when the policy rarely visits affected cells. We treat entry into aggregate-only fault interpretation as a diagnosability decision preceding scoring or localization. A reference-map gate requires repeated clean-policy support; a matched runtime gate then requires joint support in clean and current streams. Signal analysis occurs only after both pass. We calibrate false admission on a disjoint clean stream at the physical-component level and model detection by affected clean traffic rather than nominal cell coverage. In a frozen one-shot heldout, 55/72 (76.4%) regime-component units were reference-admitted, representing 20 physical components; 54/55 passed matched runtime admission, while the rejected unit abstained. Stable false admission was 0/20, with a one-sided exact 95% upper bound of 0.1391, meeting the frozen 0.20 criterion. Across 540 repeated unit-arm rows nested in those 20 clusters, affected clean traffic reduced negative log likelihood by 29.3% relative to cell coverage, a gain of 0.1264 nats per row (cluster-bootstrap 95% interval [0.0593, 0.1918]). Adding mask family and its interaction improved log loss by 0.0015 nats per row (one-sided upper bound 0.0066), below the frozen 0.01 practical-sufficiency margin. A development audit found that exact minimum hitting set and greedy selection chose identical supports in 12/12 scenarios because singleton evidence had resolved the conflicts. The result is a bounded rule for interpreting aggregate agent behavior: first establish exposure, then score change, and abstain when the trace cannot support the claim.
### Title:
          MOLA LiDAR-Inertial Odometry (MOLA-LIO) on the COMFORT Localization Benchmark
 - **Authors:** Jose Luis Blanco-Claraco
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This short report documents our entry to the COMFORT Localization Benchmark (IROS 2026), evaluated on the GrandTour dataset recorded with the Boxi payload. It extends MOLA-LO into a LiDAR-inertial system that also ingests IMU and, optionally, legged kinematic odometry. We describe the architecture, the streams consumed, the local protocol that selected the submitted configuration, and the measurements backing our real-time claim.
### Title:
          Boundary and Intra-Segment Learning for Partial Audio Deepfake Localization
 - **Authors:** Zhe Ye, Xiangui Kang, Minhua Huang, Kai Wu, Kong Aik Lee, Chng Eng Siong
 - **Subjects:** Subjects:
Sound (cs.SD); Audio and Speech Processing (eess.AS)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Partial audio deepfakes manipulate only selected speech regions, making them difficult to be localized. Existing methods exploit boundary cues for partial deepfake localization, but primarily focus on identifying boundary positions rather than modeling the feature changes that characterize authenticity transitions. Meanwhile, the internal characteristics of continuous bona fide and spoofed segments remain underexplored. In this paper, we propose Boundary and Intra-Segment Learning (BISL), which introduces boundary learning to model feature differences between adjacent frames and distinguish authenticity transitions from general acoustic variations. In addition, intra-segment learning captures the overall characteristics of continuous bona fide and spoofed segments while enhancing feature consistency within each segment. By jointly learning frame, boundary, and segment information, BISL enables more effective fine-grained partial audio deepfake localization. Experiments on multiple localization benchmarks show that BISL achieves an EER of 2.52\% and an F1-score of 97.40\% on PartialSpoof, outperforming the compared methods, while maintaining competitive performance on HAD and improved cross-dataset performance on LPS. The code will be made publicly available upon acceptance.
### Title:
          Robust Active-Perception Control for Global-State-Free Aerial-Ground Cooperation
 - **Authors:** Mingxuan Zhang, Jiajun Yu, Baozhe Zhang, Pengxiang Zhou, Wentao Liu, Fei Gao, Chao Xu, Yanjun Cao
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Aerial-ground cooperation requires real-time UAV--UGV relative-state information. Instead of maintaining global estimates for both robots, direct control in a UGV-attached non-inertial frame avoids reliance on global localization. Vision-based relative pose estimation with a passive marker offers a low-cost and effective solution. However, a fixed camera may lose sight of the moving UGV when the required UAV attitude conflicts with the field-of-view (FOV) constraint. To address this, we propose COPA, a robust active-perception framework for global-state-free aerial-ground cooperation. We use a single-axis gimbal to decouple the camera optical axis from the UAV pitch attitude. We derive an active-perception model that relates UAV motion, gimbal angle, and UGV motion to the target image-plane state.A Temporal Convolutional Network (TCN) predicts short-horizon UGV acceleration and angular velocity from recent motion history without global-state measurements. The model predictive control (MPC) uses these predictions to jointly optimize UAV and gimbal control. Simulations show that COPA maintains continuous target visibility, while ablation studies confirm that the TCN reduces peak errors during UGV motion transitions. Real-world experiments with UGV accelerations up to 3m/s^2 and yaw rates up to 1.0rad/s demonstrate robust tracking.
### Title:
          NaCR: Visual Localization via NeRF-aided Camera Ray Regression
 - **Authors:** Yesheng Zhang, Xiang Dai, Xu Zhao, Chongyang Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Visual localization (VL) is a fundamental technology for vision applications such as virtual reality. Recently, a novel VL paradigm, Camera Ray Regression (CRR), has emerged, which maps 2D image patches to 3D camera rays, but its accuracy is limited. To improve CRR accuracy, we notice a compelling duality: the inverse of this mapping is inherently performed by the novel view synthesis model, \ie, Neural Radiance Fields (NeRF). While NeRF renders image patches from camera rays via differentiable ray marching, CRR predicts the rays from image patches. Motivated by this complementary relationship, we propose NeRF-aided Camera Ray Regression (NaCR), a unified framework that seamlessly bridges NeRF and CRR at the ray level. First, NaCR incorporates three simple yet effective enhancements into the CRR baseline. Second, leveraging a pre-trained NeRF, NaCR augments the training data by synthesizing novel views tailored for efficient, patch-level consumption. Finally, exploiting the differentiability of NeRF, NaCR forms a closed-loop supervision pipeline where photometric rendering errors are back-propagated to optimize the predicted camera rays. To ensure stable convergence within the highly non-convex image space, we introduce a two-stage training curriculum. Extensive experiments across indoor and outdoor benchmarks demonstrate that NaCR achieves competitive accuracy. Comprehensive ablation studies validate the efficacy of each proposed component.
### Title:
          AT3D-AD: Anomaly Type-Aware 3D Anomaly Detection via Hierarchical Point-Language Alignment
 - **Authors:** Jingyu Zeng, Haoquan Lu, Can Gao
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Detecting and localizing 3D point-cloud defects is essential for industrial inspection. However, existing methods often suffer from imprecise localization due to the lack of anomaly supervision and reliance on single-granularity representations. To address these limitations, we propose Anomaly Type-Aware 3D Anomaly Detection (AT3D-AD), a unified framework for joint detection, localization, and classification. Specifically, we first design the Physics-Driven Parametric Anomaly Synthesis (PDPAS) module employing multiple parametric functions to generate synthetic anomalies, providing explicit anomaly supervision. Then, we propose the Hierarchical Global-Local Anomaly Alignment (HiGLA) module to align global and local representations within the normal and anomalous groups. Finally, we propose the Semantic-Geometric Anomaly Classification (SGAC) module to jointly learn localization and classification, yielding spatially precise and type-discriminative anomaly representations. Extensive experiments establish new state-of-the-art performance on all four benchmarks. AT3D-AD achieves Object/Point AUROC scores of 98.1\%/98.9\% on Anomaly-ShapeNet and 95.0\%/95.2\% on Real3D-AD, while reaching 74.2\% Macro-F1 for anomaly-type recognition on Real3D-AD.
### Title:
          Unsigned Distance Maps on 2D Point Cloud Registration
 - **Authors:** Ricardo B. Sousa, Giorgio Grisetti, Héber Miguel Sobreira, Carlos André Silva, António Paulo Moreira
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 2D point cloud registration arises in laser odometry and Simultaneous Localization and Mapping (SLAM) for mobile robots. Iterative Closest Point (ICP) is one of the most widely used approaches. Still, its iterative procedure recomputes correspondences via nearest-neighbor search at every iteration, whereas correspondence-free alternatives focus on scan-to-map alignment. This paper proposes a 2D point cloud registration approach based on unsigned distance maps, precomputing the Euclidean distance to the nearest reference point, along with its spatial derivatives, over a discrete grid, replacing the per-iteration search with O(1) lookups. Moreover, point-to-point and point-to-plane error formulations are derived on the SE(2) manifold and solved via Gauss-Newton optimization. On a synthetic benchmark and the real-world IILABS 3D dataset, the precomputed point-to-point variant outperforms its analytical counterparts, achieving competitive laser-odometry drift compared to point-to-plane formulations, as the precomputed gradient regularizes correspondences in the presence of sensor noise.
### Title:
          Design and Implementation of an Ultra-Low-Cost Wall-Climbing Robot for Infrastructure Crack Detection
 - **Authors:** Mrinmoy Modak, Supreyo Chakravorty Pretom, Shourv Tarafder, Daniel S. Drew
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Crack detection is a crucial process to ensure the safety and longevity of buildings and other infrastructure. In this paper, we developed a low-cost, automated crack detection robot that leverages CNN, EfficientNet-B0, and YOLOv8 for efficient identification of cracks in concrete surfaces with a curated crack image dataset introduced to support training and evaluation. YOLOv8's real-time object detection enhances crack localization, while CNN and EfficientNet-B0 provide binary classification, ensuring high precision and recall. The system consists of two stages. In the first stage, YOLOv8 detects and localizes wall regions from the video frame, and the bounding boxes are cropped. The second stage performs crack detection using one of three models by analyzing the cropped regions. Cost-effective approaches are also taken for robot design. The robot features a fan-based negative pressure adhesion system, a 4-wheeled skid-steering drive, and an ESP32-CAM for real-time image capture. Its lightweight 3D-printed chassis ensures stability, allowing it to navigate both walls and ceilings while capturing images for crack analysis. Unlike conventional wall-climbing robot designs, this robot incorporates a funnel-shaped body that enhances negative pressure generation and achieves a 44% reduction in duty cycle, significantly lowering power consumption. By combining low-cost hardware with a deep learning pipeline, our system provides a scalable, efficient, and accessible solution for real-time infrastructure inspection at an approximate total cost of $25, with a lightweight web application enabling smartphone-based control. This affordability makes the system more suitable for the developing world, where infrastructure inspection is often limited by budget constraints, labor intensity, and safety risks.
### Title:
          Bridging the Data Gap: Digital Twin as a New Paradigm for AI-based Radio Sensing
 - **Authors:** Éloi Sainte-Beuve (1, 2), Guillaume Larue (1), Louis-Adrien Dufrène (1), Quentin Lampin (1), Ali Al Khansa (1) ((1) Orange Research, (2) IMT Atlantique)
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Signal Processing (eess.SP)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We present a methodology that places a 3D digital twin (DT) of the environment as the main enabler behind the development of radio sensing at scale. The DT acts as a world model, providing geometry, materials, and transmitter/receiver placements to a ray-tracing engine that generates time-indexed channel impulse responses (CIRs) for large numbers of plausible scenes (moving people and objects, layout variants, seasonal/weather conditions, etc). From these synthetic sequences, we train a sequential neural network that maps CIR time series to spatial occupancy estimates, enabling device-free localization (DFL) without instrumented targets. We posit that sensing is best approached as an environment-conditioned learning problem: rather than seeking a single global model, we advocate training or fine-tuning local models specialized to a site-specific DT. As a first experiment, we introduce a novel State Space Model architecture, trained and evaluated across multiple room geometries. The localization performances obtained demonstrate the potential of the approach.
### Title:
          Leveraging Vision-Based Point Cloud Map Priors for Camera-Based 3D Object Detection and Online Vectorized HD Mapping
 - **Authors:** Markus Käppeler, Rohit Mohan, Abhinav Valada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Camera-based 3D object detection and online vectorized HD mapping provide compact scene representations for autonomous driving, but both depend on accurate metric geometry and remain limited by depth ambiguity. Over long-term deployment, observations from repeated traversals can be accumulated into persistent point cloud priors that provide geometric context beyond the current observations. Existing explicit point cloud prior approaches, however, rely on LiDAR-based map construction and therefore require expensive 3D ranging sensors. We propose a framework that constructs a static point cloud prior map from previous camera traversals using Pi3X and augments each point with DINOv3 features. At runtime, a local prior patch is retrieved using global localization, encoded with a sparse voxel backbone, and fused in bird's-eye view (BEV) with lifted multi-view camera features. Task-specific sparse transformer heads then predict 3D objects and vectorized map elements from the fused representation. On Argoverse 2, the vision-based prior improves a strong baseline from 0.287 to 0.299 CDS and from 0.669 to 0.750 vectorized mapping mAP. Ablations show that semantic DINOv3 features are particularly important for vectorized mapping. These results demonstrate that vision-built geometric-semantic priors provide an effective form of long-term scene memory for camera-based perception, improving both tasks without LiDAR for prior-map construction or online inference.
### Title:
          SparseNav: Instruction-conditioned Sparse Semantic Perception for Training-Free Vision-Language Navigation
 - **Authors:** Quanhua Chen, Juhan Kang, Runfeng Lin, ZiFei Zhang, Enquang Feng, Chunran Zheng, Xiwang Dong, Jiarong Lin
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Map-based vision-language navigation (VLN) relies on persistent spatial representations to connect language understanding with geometric planning. However, acquiring semantics beyond the needs of the current instruction can introduce unnecessary perception cost and irrelevant annotations. Continuously accumulating unrelated objects may not only waste computation, but also clutter the visual-spatial representation consumed by the vision-language model (VLM) planner. To address this problem, we present SparseNav, a training-free framework that follows a less-is-more principle for semantic navigation. SparseNav persistently maintains a lightweight geometric bird's-eye-view (BEV) map and sparse landmark memory, acquiring new semantics on demand using the active sub-instruction to decide what is worth grounding. An instruction manager first tracks navigation progress and identifies the active landmark query. An instruction-conditioned perception mechanism then invokes open-vocabulary segmentation when the queried landmark is visible and its metric location can inform the next decision. The resulting landmark memory supports VLM selection among hybrid frontier and local directional waypoint candidates. Without any additional training, SparseNav achieves success rates of 42.8% on R2R-CE and 40.7% on RxR-CE, both on the Val-Unseen splits. Controlled ablations examine semantic perception strategies and the contributions of individual framework components. Furthermore, we successfully deployed SparseNav on a Unitree Go2 quadruped equipped with an Intel RealSense D455 RGB-D camera for geometric mapping and landmark grounding and a Livox MID-360 LiDAR for localization, without a prebuilt map. We validated its effectiveness across multiple indoor environments using instruction-conditioned waypoint navigation.
### Title:
          Dr-LiSA: Direct Radar-Lidar Scan Alignment for $SE(3)$ Localization
 - **Authors:** Alex Zhang, Daniil Lisus, Cedric Le Gentil, Timothy D. Barfoot
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces Dr-LiSA, a first-of-its-kind direct method for localizing 2D spinning radar intensity measurements in $SE(3)$ against 3D lidar maps. Radar-lidar localization combines the complementary strengths of the two sensing modalities: radar is robust to adverse weather and precipitation, while lidar provides high-fidelity 3D maps in favourable conditions. However, existing radar-lidar localization methods are restricted to planar $SE(2)$ localization and have generally fallen short of the accuracy achieved by lidar-lidar and even radar-radar systems. A key challenge is the substantial sensing-modality gap between radar and lidar, which observe and represent scene structure in fundamentally different ways. Dr-LiSA bridges this gap using a learned forward model that predicts radar measurements from a lidar submap at a candidate pose, enabling direct photometric alignment of predicted and observed radar scans in $SE(3)$. Dr-LiSA outperforms prior radar-lidar approaches in $SE(2)$ while achieving planar accuracy competitive with state-of-the-art radar-radar localization across more than 90 km of on-road data.
## Keyword: transformer
### Title:
          Deepfakes and Synthetic Media: Generation, Detection, and Governance
 - **Authors:** Alexandros Gazis, Efstathios Karypidis, Kleanthi Santamouri, Theodoros Vavouras, Nikos E. Mastorakis, Stylianos Pappas
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Deepfakes, synthetic audiovisual content produced by deep generative models, have escalated into a critical threat across civilian and military domains, enabling identity fraud, disinformation campaigns, and evidence fabrication. In high-stakes environments, ranging from journalism and finance to healthcare and legal contexts, the consequences extend to severe misinformation, market manipulation, identity fraud, and the erosion of institutional trust. This entry explores how modern visual intelligence and computer vision techniques are used to detect deepfakes. It outlines key deepfake generation models, such as GANs, autoencoders, neural rendering, and diffusion systems, while also explaining how adversarial methods enhance realism and challenge existing detectors. The overview highlights visual artifacts, digital patterns, and physiological cues commonly leveraged in detection and reviews major CNN, transformer, and frequency-based approaches. It also summarizes evaluation practices and the difficulty of achieving strong generalization. Finally, it identifies emerging directions, including modern intelligence techniques for civilian and military content verification. This survey covers generation architectures (GANs, latent diffusion, neural rendering, video synthesis), the spatial, temporal, frequency-domain, and physiological artifacts they produce, and the detector families that exploit them. We examine evaluation benchmarks and protocols, highlighting cross-generator generalization as the field's central open challenge. Beyond detection, we discuss cryptographic provenance standards, watermarking, and regulatory frameworks (EU AI Act, DSA, GDPR). We conclude that effective deepfake governance requires defense-in-depth integrating forensic detection, verifiable provenance, and institutional accountability.
### Title:
          NPLSD: Accelerating Line-Segment Detection on NPU Microcontrollers
 - **Authors:** Parsa Hassani Shariat Panahi, Amir Hossein Jalilvand, M. Hassan Najafi
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Line-segment detection is fundamental to robotics, autonomous navigation, and industrial inspection. While transformer-based detectors achieve the highest accuracy, their deployment on microcontrollers remains impractical due to resource constraints. The STM32N6, with its Neural-ART NPU, promises to enable deep vision at the extreme edge. However, existing detectors rely on attention, grid-sampling, and normalization, operators that are unsupported by the convolution-oriented NPU. This architectural mismatch is characterized operator by operator: attention, grid-sampling, and normalization lack accelerator primitives, and the decoder's self-attention alone materializes a 39 MB score tensor that exceeds on-chip memory. To address this limitation, NPLSD is introduced as a pair of NPU-compatible line-segment detectors built from one design methodology. NPLSD-H retains the convolutional HGNetv2 backbone of LINEA and replaces the transformer head with a fully-convolutional feature pyramid and an F-Clip dense head. NPLSD-M adapts the M-LSD-tiny trunk to the supported operator set. Warm-started from ImageNet and trained on ShanghaiTech Wireframe, the 2.63M-parameter NPLSD-H reaches sAP^10=37.9 (35.9 int8); the 0.62M-parameter NPLSD-M reaches 41.9 (41.1 int8). A controlled ablation isolates the trunk as the only variable, and initialization alone accounts for 4.6 points.
### Title:
          Mitigating LLM Over-Refusal via Dynamic Semantic Routing Calibratione
 - **Authors:** Zixuan Wang, Bingjie Zhang, He Zhao, Dandan Guo
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Large language models (LLMs) aligned for safety often suffer from over-refusal, incorrectly rejecting benign yet safety-related instructions. Prior studies primarily attribute this to static representation overlap, largely overlooking the underlying dynamic mechanisms. In this paper, we present the mechanistic analysis of over-refusal through the lens of internal routing conflicts within transformer attention. We discover that a sparse subset of Hypersensitive Safety Heads misfires on Hard-Safe prompts, exhibiting abnormal attention entanglement that forcefully binds harmless target entities to refusal semantics. This triggers a severe, high-entropy routing conflict that deprives target entities of necessary attention. To counteract this, we propose Semantic Routing Calibration (SRC), a lightweight, training-free inference framework. SRC precisely localizes and dynamically suppresses these hypersensitive safety heads at the inference stage. Coupled with a dual-branch logits fusion that acts as a safety regularizer during subsequent decoding, SRC seamlessly restores trustworthy reasoning. Extensive experiments demonstrate that SRC alleviates over-refusal, with intrinsic safety performance preserved as much as feasible.
### Title:
          X-Planner: Event-Structured Task Planning for Embodied Intelligence
 - **Authors:** Howard Lu, Shalfun Li, Porter Pan, Cris, Lumen, Cyril, Eric Hu, Lily Li, Maeve Zhang, Robert Wang, KZ Zheng, Viggo Chen, Tim Ding, Regsis Cheng, YJ Xiao, Kian, Hai Lin, Alan Song, Elise Ma, Gody Li, Victor Yao, Yohann Tang, Ingrid Yu, Jason He, James Wang, Ryan Yu, Ping Yang, Chris Pan, Vincent Chen, Roy Gan, Hao Wang, Qian Wang
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Task planning bridges high-level instructions and executable behavior in long-horizon manipulation, yet modern Vision-Language-Action (VLA) systems often leave this intermediate structure implicit. Existing chain-of-thought (CoT) planners also tend to rely on coarse task-level annotations or serialize long reasoning traces token by token. We present X-Planner, a planning front-end that addresses both the supervision and representation of embodied reasoning. Our planning data combine Ego, UMI, and teleoperation under a hierarchy granularity with source-dependent annotation depth. Takeover-time annotations and human-designed failures supervise ongoing error recognition. On the model side, a shared VLM backbone exposes two event-structured plan forms: a discrete interface that emits interpretable event states and a latent interface that relays continuous CoT states across staggered Transformer depths through Staircase Decoding. A frozen latent-to-text reconstruction objective provides a semantic anchor for the latent representation. Offline two-step planning evaluation places X-Planner second among four evaluated models on both BERTScore-F1 and a judge-based Overall score. In real-robot experiments, respectively, outperforming the evaluated baselines. These results characterize planning-text quality and downstream execution.
### Title:
          MedGate-Fusion: Integrating First-Encounter Semantic Narratives and Physiological Biomarkers for Prospective Stroke Risk Stratification
 - **Authors:** Hemn Khdr, Mohammad Noaeen, Karim Keshavjee, Aziz Guergachi, Zahra Shakeri
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Prospective stroke risk stratification in primary care is challenging because early risk signals are distributed across routine biomarkers and unstructured clinical narratives. We propose MedGate-Fusion, a multi-modal gated architecture that integrates transformer-based embeddings of first-encounter narratives with ten routinely recorded risk markers. We used electronic medical record data from the Canadian Primary Care Sentinel Surveillance Network (CPCSSN). Starting from 808,921 encounter-level observations, we constructed a first-encounter cohort and retained 102,736 unique patient records with non-empty narratives and sufficient data to evaluate a five-year stroke outcome. To reduce explicit target leakage from diagnostic mentions in notes, we applied dictionary-based redaction of stroke-related terms prior to semantic encoding.
### Title:
          JAMB: Joint Action-Motion Diffusion for Bimanual Manipulation
 - **Authors:** Chuyang Xiao, Peilin Meng, David Held
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Coordinated bimanual manipulation is challenging because the motion of either arm can alter the shared 3D scene and thereby affect the other arm. Yet most diffusion policies generate actions without explicitly modeling these future geometric consequences, while predictive variants typically use future state only as auxiliary supervision or fixed conditioning. We address this limitation by proposing JAMB, a diffusion policy that jointly denoises bimanual actions and future 3D point tracks. By allowing action and track hypotheses to evolve together within a shared Transformer, each can inform and refine the other throughout denoising. We further ground multimodal representations in a shared spatiotemporal coordinate system to facilitate geometry-aware interaction during joint denoising. We evaluate JAMB on diverse bimanual manipulation tasks in RoboTwin 2.0 and on a real-world robot, comparing it with action-only policies and alternative future-prediction approaches spanning different state representations and learning objectives. Across 16 simulation tasks, JAMB achieves an average success rate of 83.4%, outperforming the strongest baseline by 23.9 percentage points. On three real-world tasks, it outperforms the action-only and auxiliary geometry prediction methods by 50.0 and 21.2 percentage points, respectively. Beyond these performance gains, JAMB shows stronger generalization to cluttered scenes and out-of-distribution backgrounds than the evaluated baselines. Together, these results demonstrate the effectiveness of our joint action-motion modeling framework for coordinated bimanual manipulation. Our project website is available at this https URL
### Title:
          Learning from Humans for Proactive Assistance in Human-Robot Collaborative Transport
 - **Authors:** Elvin Yang, Christoforos Mavrogiannis
 - **Subjects:** Subjects:
Robotics (cs.RO); Human-Computer Interaction (cs.HC); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We focus on human-robot collaborative transport, a challenging task of broad relevance spanning logistics, manufacturing, and the home, in which a user and a robot work together to relocate a large or heavy object. To act as an effective partner, the robot should reduce the user's effort by contributing to efficient relocation of the object while remaining physically responsive to them. Prior work often addresses these capabilities separately, producing robots that may move the object efficiently but resist user input, or accommodate the user but depend on continuous guidance. Our key insight is that obstacle-constrained collaborative transport requires integrating predictions of human collaborative behavior with compliant robot control. To this end, we introduce PROACT, a framework for human-robot collaborative transport that incorporates anticipation into compliant whole-body control through a learned model of human collaborative behavior. Trained on a large-scale, real-world dataset of dyadic human transport demonstrations, our transformer architecture distills collaborative behavior into predictions of future object motion. Across 108 real-world trials with a 9-DoF mobile manipulator, PROACT reduces mean interaction work by 59.2\% and 20.4\%, and mean completion time by 12.9\% and 6.9\%, relative to compliance-only and MPC baselines, respectively. Footage from our experiments can be found at this https URL.
### Title:
          PermuFormer: Multi-Task Pretraining for Permutation Representation in Algebraic Combinatorics
 - **Authors:** Henry Kvinge
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Combinatorics (math.CO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diverse pretraining has been shown to be an effective method for learning reusable, domain-aware representations that provide a starting point for fine-tuning on downstream tasks. While much of the excitement in AI for math has been concentrated in the use of frontier reasoning models to solve well-specified problems through the medium of language, narrow, specialized models remain an important component of the AI for math ecosystem. In contrast to large language models, specialized models are usually trained directly on the mathematical objects themselves (e.g., graphs, sequences of numbers) rather than the textual descriptions that characterize these objects. However, the common practice of training specialists from scratch may limit their ability to develop domain-aware representations that capture the multifaceted nature of mathematics. In this paper, we describe an approach to pretraining for permutation-focused tasks in algebraic combinatorics. We introduce PermuFormer, an autoregressive transformer trained on a 2.8 billion token multi-task, multi-encoding corpus. We show that PermuFormer is an effective starting point for fine-tuning on basic tasks unseen during pretraining and more complex research-level tasks, frequently outperforming the same architecture trained from scratch, baseline MLPs, and a fine-tuned generic language model of comparable size. We also analyze some of the internal mechanisms by which PermuFormer learns to solve training tasks. For example, we show that while some tasks can be linearly decoded directly from the internal representation of the prompt, other tasks require multiple rounds of generation before the answer can be decoded.
### Title:
          Mean Velocity Matching: Rethinking Generative Dynamics in Diffusion Models
 - **Authors:** Yunhong Zhang, Changjie Cao, Zhihua Zhang, Bingli Liu, Zongjie Cao, Zongyong Cui, Ying Yang
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This work studies prediction parameterization for stochastic generative dynamics in diffusion models. Existing velocity-based generative models provide the simplicity of learning a single transport field, but their standard formulation is deterministic, whereas stochastic extensions generally require additional score information or an intermediate velocity-to-score reconstruction. To retain single-field prediction while directly supporting stochastic reverse dynamics, this paper introduces Mean Velocity Matching (MVM). MVM constructs a Gaussian perturbation process for which the conditional expectation of a restoration-oriented velocity, $(x_0-x_t)/t$, directly forms the reverse-SDE drift. Consequently, a single learned field is sufficient to parameterize the stochastic reverse process without separately estimating or reconstructing the score. Because direct regression of this velocity becomes unbounded near $t=0$, MVM further introduces a $\sqrt{t}$-scaled parameterization that preserves the reverse dynamics while yielding a bounded training target. The same learned field also induces a deterministic probability-flow ODE, enabling stochastic and deterministic sampling to be studied within a unified formulation. Experiments with Transformer-based generative models achieve an FID of $\MVMImageNetThirtyTwoFID$ at \MVMImageNetThirtyTwoNFE\ NFE on ImageNet $32\times32$ and $\MVMImageNetTwoFiftySixFID$ at \MVMImageNetTwoFiftySixNFE\ NFE on ImageNet $256\times256$. Controlled SDE--ODE comparisons further show that the ODE performs better under very low NFE, whereas the stochastic reverse process achieves lower FID when sufficient function evaluations are available. These results demonstrate that MVM provides a direct single-field parameterization of stochastic reverse dynamics while maintaining competitive generation quality.
### Title:
          Real-Time Hand Gesture Recognition for OpenXR Using Transformer-Based Machine Learning
 - **Authors:** Salar Rezayani, Russell Butler
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Hand gesture recognition is a key component in human-computer interaction (HCI), enabling intuitive interfaces for applications in gaming, virtual reality (VR), robotics, and more. This study integrates transformer-based machine-learning models for real-time hand gesture recognition, using hand-tracking data captured through the OpenXR standard in Unity. We leverage positional data of hand joints and wrist rotation angles to train a custom gesture recognition system. By utilizing the sequential modeling capabilities of transformers, the system captures temporal dependencies within short gesture windows and classifies gestures robustly across hand orientations and sizes. The results show a significant improvement in gesture classification accuracy. Building on this, we outline how the approach can be extended toward detecting the flow of movement, i.e., the transitions between gestures, as future work.
### Title:
          Spend Classification Without Leakage: An Evaluation Harness and What It Changed in a Deployed System
 - **Authors:** Harshit Gupta
 - **Subjects:** Subjects:
Databases (cs.DB)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Assigning a standard commodity code to a free-text purchase line underpins enterprise spend analytics, and its reported accuracy cannot be checked. Published results use proprietary data or private samples under undocumented protocols; no two compare and there is no public benchmark. We build a harness with four protocols over 1.26 million labelled purchase lines from two US state governments. Enterprises rebuy continuously, so random splits put matching item text on both sides: 60.7% and 61.2% of test rows, 54.7% and 60.6% byte for byte. On California orders the best classical baseline scores 56.0% on repeated text but 31.9% on novel text, a 24-point gap widening with taxonomy depth. Embedding retrieval shrinks the gap from 23.8 to 19.1 points; a fine-tuned transformer does not escape it. On one corpus leaky evaluation cannot separate retrieval from the transformer, while three leak-free protocols put the transformer 2.3 to 3.6 points ahead, so leaky splits hide real differences, not just flatter both. We derive an upper bound on text-only classifiers from identical text with conflicting codes: 79.4% commodity accuracy on one corpus against 98.4% on the other, so accuracy does not compare across datasets. Spend-weighting the bound reflects the amount field more than labels. In a deployment of 920,927 lines, reviewers accepted 32.4% of suggestions on the novel-text population; 29.7-35.2% brackets benchmark rates near 31.9% and 34.8%. We release the harness in production use.
### Title:
          Transformer Heads Looking for Order
 - **Authors:** Jasper van Doornmalen, Alexander Kozachinskiy, Corinna Mathwieser, Tomasz Steifer, Felipe Urrutia, José Verschae, Przemysław Andrzej Wałȩga
 - **Subjects:** Subjects:
Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In this note, we show that the problem of checking, whether a sequence of bits is ordered, is not doable by 1-head 1-layer transformers but is doable by a 2-head 1-layer transformer. Unlike similar previous results, our results assume the model where transformers have an output MLP.
### Title:
          MachEmbodied-U0: Unified Understanding and Generation Model for Embodied Intelligence
 - **Authors:** Haoran Wen, Wenfu Wang, Kunsong Shi, Jingke Wang, Wancheng Feng, Yiren Zhang, Yueran Zhao, Xuancheng Zhang, Nanfei Ye, Xingru Chen, Zhaohong Sun, Chengmin Yang, Zikang Yu, Penghao Bi, Jia Shi, Yu Liu, Kun Zhan, Yan Xie
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 General-purpose robot control requires models to understand task intent, identify where to interact, capture how the scene evolves, and generate precise actions. Vision-language-action models provide strong semantic priors but typically do not explicitly model scene dynamics, while world-action models couple visual prediction with control without necessarily exposing the task-relevant semantic and spatial structure needed for fine-grained manipulation. We present MachEmbodied-U0 (ME-U0), a unified embodied foundation model connecting understanding and generation experts through a Mixture-of-Transformers architecture. Subtask prediction and affordance grounding guide joint visual-dynamics and action generation via flow matching. Visual dynamics encompass future RGB, depth, surface normals, and optical flow, providing complementary supervision for appearance, geometry, and motion. Multi-rate Rotary Position Encoding (MRPE) aligns visual dynamics with fine-grained control. We pretrain ME-U0 on approximately 4,200 hours of curated demonstrations from robotic datasets and egocentric datasets. Using only the supervision natively available in each downstream benchmark, ME-U0 achieves an average score of 17.66 on the RoboDojo simulation benchmark and average success rates of 99.0\% and 82.5\% on LIBERO and LIBERO-Plus, respectively. We additionally validate ME-U0 on real-world robotic manipulation tasks, demonstrating its effectiveness beyond simulation. Without corresponding downstream supervision, ME-U0 further demonstrates zero-shot subtask prediction, affordance grounding, and visual dynamics on simulated and real-world observations. Overall, ME-U0 combines competitive downstream control performance with transferable task-grounding and visual-dynamics capabilities across simulation and the real world.
### Title:
          Fysiverse-3D-Vision Technical Report: Generating Executable 3D Worlds from Images through Unified Spatial Reasoning
 - **Authors:** Dingkang Yang, Yizhou Liu, Wendong Cheng, Zizhi Chen, Shunli Wang, Yang Liu, Hongsheng Li, Lihua Zhang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Generative models have advanced image-conditioned 3D content creation, yet generating controllable and executable 3D scenes from a single image remains challenging. Existing 3D generative approaches can synthesize visually plausible objects and scenes, but their spatial layout estimation is coupled with specific asset generators. They struggle to jointly model object semantics, metric geometry, and scene-level spatial relationships, which are essential for interactive editing, physical simulation, and embodied applications. We propose Fysiverse-3D-Vision, a unified vision-language-geometry framework for generative 3D scene reconstruction and executable asset construction from a single image. We establish a shared representation where spatial reasoning and geometric reconstruction mutually enhance each other, allowing object layouts to be inferred beyond the constraints of individual asset generators. Our model integrates textual supervision, semantic visual cues, and geometric representations within a unified Transformer to capture scene context, metric geometry, and object-level interactions. An object-conditioned layout module performs cross-attention between target object representations and global geometric features to predict object translation, rotation, and scale. Training progressively learns geometry-language alignment, introduces layout reasoning while preserving reconstruction capability, and refines physical consistency through collision-aware optimization. By separating spatial layout reasoning from asset synthesis, Fysiverse-3D-Vision provides an adaptable interface for interactive scene editing, object-level manipulations, and executable 3D content generation. Experiments demonstrate that our framework achieves superior geometric consistency, layout estimation, rendering quality, and physical property understanding compared with existing approaches.
### Title:
          Evaluating Accuracy and Probabilistic Reliability of Zero-Shot Time Series Foundation Models
 - **Authors:** Panagiotis Michael, Moysis Symeonides, Demetris Trihinas
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Time Series Foundation Models (TSFMs) promise a paradigm shift toward zero-shot forecasting by eliminating task-specific training. However, existing works often overlook trade-offs between predictive accuracy and probabilistic calibration. This paper presents a benchmark study of six TSFMs evaluated on energy, traffic, and financial datasets. We contrast their performance against statistical baselines and a supervised DL model. The study reveals that while TSFMs outperform statistical methods and supervised models, they are subject to a fundamental trade-off between point accuracy and probabilistic reliability. Specifically, xLSTM architectures provide robust probabilistic calibration across horizons. In contrast, patch-based transformers offer competitive accuracy but face calibration issues at long horizons, while transformer-based models exhibit context saturation points for optimal zero-shot reasoning. These findings offer evidence-based guidance for balancing generalization and uncertainty quantification in real-world deployments.
### Title:
          Latest Exact Match Attention
 - **Authors:** Moritz Brösamle
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Computational Complexity (cs.CC); Computation and Language (cs.CL)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 We introduce latest exact match attention (LEMA), an attention variant for transformers where queries and keys are binarized and each query attends only to the latest exactly matching key. We prove that LEMA transformers with chain of thought can simulate word-RAMs, as was recently shown for the less restrictive rightmost hard attention. In contrast to prior hard attention variants, the restriction to exact matches enables an efficient converse direction: word-RAMs can simulate LEMA transformers at a cost per token independent of the context length. Together, these results yield a close correspondence between the two computational models in terms of both compute and memory. Beyond the theory, we propose a training method for LEMA transformers that handles their non-differentiable operations with a straight-through estimator for the binarization and a soft attention surrogate annealed towards LEMA. On a synthetic associative recall task, LEMA models trained this way use their growing state to store and recall a large number of associations, outperforming gated DeltaNet (GDN) with its fixed state size. As a first scaling test, we train LEMA language models with up to 834 million parameters. They match softmax transformers of around half their size in loss and, on repeated rare phrases and a needle-retrieval task, remain behind softmax transformers but recall across longer distances than GDN models of comparable size. Finally, we implement dictionary-based inference for LEMA transformers and show constant generation speed comparable to GDN despite their growing state, with the dictionaries residing in main memory rather than VRAM. Code is available at this https URL.
### Title:
          Protocol before progress: leakage-aware evaluation of AIS trajectory prediction
 - **Authors:** Zobeir Raisi, Vali Mohammad Nazarzehi Had
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Reported gains in vessel-trajectory prediction from Automatic Identification System (AIS) data are credited to new architectures, but the evaluation protocol is rarely measured as a source of error reduction. We build a leakage-aware protocol with vessel-, time- and region-disjoint splits and apply it to two corpora with different traffic: 31 days of Danish national AIS traffic and 30 days of US Gulf coast traffic off Houston and Galveston. On both, we audit TrAISformer, GATransformer, and controlled AISFormer-inspired reconstructions. Three protocol effects appear in both corpora. First, TrAISformer's best-of-16 oracle decoder lowers error by a factor of 2.1-3.2 relative to greedy decoding. Second, a split that shares vessels lowers its greedy error by 23-25% at one hour, against 2% or less for a compact 0.43 M-parameter encoder. Third, a region-disjoint split raises TrAISformer's one-hour error from 2.2 to 24.6 km on the US corpus, because 99.9% of the test contexts fall in longitude bins never seen in training; the encoder built on local offsets is unaffected by this. Architectural mechanisms matter less: GATransformer's graph attention gives no measurable benefit on either corpus, while its waterway feature is worth 12-22%. The effect of a time-disjoint split is not stable across corpora (13% versus 2%). We release the splits and code.
### Title:
          ARAFA: An LLM-Generated Arabic Fact-Checking Dataset
 - **Authors:** Christophe Khalil, Shady Elbassuoni, Rida Assaf
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Information Retrieval (cs.IR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Automatic fact-checking poses a significant challenge in Arabic natural language processing due to the scarcity of datasets and resources. In this manuscript, we introduce Arafa, a new large-scale dataset for fact-checking in Modern Standard Arabic, constructed through an automated framework leveraging large language models (LLMs). The dataset was constructed through a three-step pipeline: (1) claim generation from Arabic Wikipedia pages with supporting textual evidence, (2) claim mutation to generate challenging counterfactual claims with refuting evidence, and (3) an automatic validation step to validate that the generated claims are either supported or refuted by their accompanying evidence, or if the evidence does not provide enough information to judge the validity of the claims. The resulting dataset comprises 181,976 claim-evidence pairs labeled as supported, refuted, or not enough information. Human evaluation carried out on a test sample from the dataset demonstrated strong inter-annotator agreement (kappa = 0.89) using Cohen's Kappa for supported claims and (kappa = 0.94) for refuted claims. Automatic validation based on a human-evaluated sample achieved 86% accuracy for supported claims and 88% for refuted ones. To showcase Arafa's value as a resource for automatic Arabic fact-checking, four open-source transformer-based models were fine-tuned using Arafa, with the top-performing model achieving a Macro F1-score of 77% on the test data. In addition to Arafa being the first large-scale dataset for Arabic fact-checking, our framework presents a scalable approach for developing similar resources for other low-resource languages.
### Title:
          Decoupling Logical Masks from GPU Execution for Dynamic Block-Sparse Attention
 - **Authors:** Shanghao Liu, Xiaoyun Yu, Wanting Li, Wenqi Jiang
 - **Subjects:** Subjects:
Hardware Architecture (cs.AR)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Attention computation makes inference expensive in video diffusion transformers (vDiTs), which generate videos through iterative denoising. Block-sparse attention (BSA) reduces this cost by computing only blocks selected by a logical mask, which specifies attention interactions to compute. However, coupling logical block geometry to execution choices limits adaptation to varying masks and graphics processing units (GPUs), while runtime kernel specialization can incur preparation overhead that outweighs execution time savings. We present Tessera, a specialized runtime for dynamic BSA that decouples logical masks from GPU execution while preserving specified attention interactions. Its physical mapping layer retains, combines, or subdivides logical attention blocks into physical tiles suited to different attention mask shapes and GPU architectures. Its task organization layer groups and schedules tiles within GPU tasks to reuse data, expose parallelism, and overlap data movement with computation. Finally, profile-guided regime selection enables low- overhead execution plan selection through a lookup table constructed from offline profiling. We implement Tessera with specialized CUDA kernels supporting four NVIDIA GPU generations. Evaluated on 2,315 real attention masks and industrial video diffusion models, Tessera achieves up to 6.79x BSA request speedup over baseline systems in the evaluated video diffusion models.
### Title:
          Delving into Asymmetric Information Dynamics for High-Fidelity Virtual Try-On
 - **Authors:** Zishu Qin, Zhiyu Jin, Pipei Huang, Hao Zhou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Virtual try-on (VTON) requires precise pixel-level fidelity, yet mainstream Diffusion Transformers (DiTs) often suffer from texture degradation and structural drift. We identify symmetric interactions in standard joint-attention mechanisms as a source of these failures. Although such interactions support semantic flexibility in general-purpose editing, they allow stochastic noise to corrupt deterministic garment features in VTON. We analyze this problem through asymmetric information dynamics and introduce two diagnostic indicators: Conditional Attention Entropy (CAE) for feature unbiasedness and Injected Information Flux (IIF) for injection effectiveness. Our analysis suggests that symmetric bidirectional attention can corrupt conditional features and attenuate the conditional signal. To address these limitations, we propose RealFit, a framework that combines Unidirectional Information Flow (UIF) with Decoupled Timestep Modulation (DTM). UIF isolates the garment condition from stochastic noise to preserve garment identity, while DTM optimizes the modulation scale to maintain a strong conditional signal. The resulting time-invariant condition branch enables a conditional KV cache that reduces inference time by approximately 75%. RealFit offers a principled approach to conditional generation with state-of-the-art fidelity and efficiency.
### Title:
          What is the Better Curriculum: Controller-Shaped Grasping Behavior for Contact Force-Sensitive Manipulation
 - **Authors:** Ziyan Feng, Zizhao Yuan, Yulong Fu, Yuxin He, Zhiyuan Zhang, Zhengjie Zhang, Jinni Zhou, Renjing Xu, Qiang Nie
 - **Subjects:** Subjects:
Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 How should a robot learn to manipulate objects so fragile that sub-Newton contact forces can cause irreversible damage? Existing visuo-tactile policy learning typically treats tactile sensing as an additional policy input. In direct-contact force-sensitive manipulation, however, the bottleneck can arise earlier, during data collection: manual gripper control is too delayed and coarse-grained to reliably maintain the narrow force range required for stable grasping. We therefore use a deterministic 25 Hz tactile reflex controller as a collection-time teacher, producing demonstrations with controller-shaped grasping behavior for tactile-free policy learning. On Action Chunking with Transformers (ACT), policies trained from reflex-shaped demonstrations recover the teacher's grasping profile and achieve 95% stable grasps on the nominal plastic-cup task, substantially outperforming visually screened manual demonstrations. The same intervention improves in-distribution stability on $\pi_{0.5}$ and shows a favorable exploratory trend on an unseen paper-cup variant. Under randomized external disturbance, however, the reflex-data $\pi_{0.5}$ policy still fails in 45% of policy-only trials, whereas a deployment-time reflex arbiter retains all grasps. These results reveal a new role for tactile feedback in force-sensitive manipulation: rather than integrating tactile into the policy, we use it as a collection-time teacher that shapes grasping behavior in demonstrations for policy learning, while disturbance rejection remains controller-dependent, revealing the boundary of tactile-free policy.
### Title:
          GeoPair: Geometry-Preserving Cross-Layer Factorization for Training-Free Transformer Compression
 - **Authors:** Baher Mohammad, Ammar Ali, Stamatios Lefkimmiatis
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Transformer architectures exhibit cross-layer redundancies, yet post-training compression pipelines typically optimize layers in isolation or rely on heuristic grouping strategies that disregard layer-specific activation geometries. We introduce a principled, training-free framework that sequentially optimizes cross-layer weight pairings and shared-dictionary factorizations. Rather than forcing weights of adjacent layers to share a basis or heuristically merging activation statistics, our approach identifies structurally compatible projections and learns a shared representation that better preserves each layer's distinct calibration geometry. Coupled with structured sparsity, this yields highly efficient weight decompositions without sacrificing functional fidelity. Across diverse architectures, scales, and modalities, our method achieves state-of-the-art results, consistently outperforming independent structured weight decompositions and alternative pairwise weight factorizations, which operate under heuristic grouping strategies. By replacing heuristic engineering strategies with a convergent, optimization-driven pipeline, we establish a theoretically grounded foundation for scalable, transformer compression across different modalities.
### Title:
          GRIP: Gaussian Rendering as a Cross-Modal Bridge for Image-to-Point Cloud Registration
 - **Authors:** Karim Slimani, Catherine Achard, Eric Marchand, Brahim Tamadazte
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This paper introduces GRIP, a pose-conditioned refinement framework for pixel-to-point matching and 2D to 3D registration. Given an initial coarse pose estimate, GRIP addresses the structural mismatch between grid based image descriptors and unordered point cloud descriptors by softly rendering learned 3D point features onto the image grid through Gaussian feature splatting. The rendered point derived feature map is then fused with image features by a pixel aligned transformer, enabling visual semantic and geometric cues to interact in a shared 2D representation. The refined features are decoded and propagated to finer resolutions for dense correspondence estimation and final pose refinement. Experiments on RGB D Scenes V2 and 7 Scenes demonstrate state of the art inlier ratio and competitive registration recall, with stronger performance under stricter evaluation thresholds.
### Title:
          Faithful Faithfulness Evaluations: Challenges & Pitfalls Learned from a Breast MRI Case Study
 - **Authors:** Peachapong Poolpol, Henrik H. J. Detjen, Eike Petersen
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Human-Computer Interaction (cs.HC); Machine Learning (cs.LG); Image and Video Processing (eess.IV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Saliency maps are widely used to explain deep learning predictions in medical imaging, yet visually plausible explanations do not necessarily reflect a model's true decision process and may therefore mislead clinicians. We investigate this problem using a Vision Transformer-based breast MRI classifier trained on the ODELIA Breast MRI Challenge dataset and evaluate multiple saliency methods, including Last-layer Attention, Attention Rollout, Grad-SAM, Gradient Attention Rollout, GMAR, Grad-CAM, and HiResCAM. Our study highlights two often-overlooked challenges in perturbation-based faithfulness evaluation. First, method rankings depend strongly on the perturbation strategy, varying across intensity-based perturbations and transformer-based attention masking. Second, benchmarking saliency methods requires distinguishing between class-specific and class-agnostic explanations. To enable fair comparisons, we introduce non-class-specific variants of gradient-based methods and evaluate both settings separately. Across protocols, Grad-CAM and Gradient Attention Rollout consistently emerged as the strongest class-specific methods, although their relative ranking depended on the evaluation design. These findings expose important limitations of current saliency-based explainability approaches and highlight the need for more robust and standardized evaluation frameworks for trustworthy clinical AI systems.
### Title:
          EMERGE: Resolution-Agnostic Point Cloud Generation with Equivariant Graph-Based Diffusion
 - **Authors:** Ilias Mitsouras, Nikolaos Chaidos, Giorgos Stamou, Athanasios Voulodimos
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Point cloud generation has emerged as a crucial task for accurately capturing and reproducing the complexity of the physical world. However, existing generative approaches, predominantly relying on Transformers and Variational Autoencoders (VAEs), frequently ignore the continuous, non-grid topologies inherent to 3D spaces. Although the integration of graph-based structures has yielded significant benefits in related discriminative vision tasks, such geometric architectures remain noticeably absent from 3D generative modeling. To address this gap, we introduce EMERGE (Equivariant Multi-scale GNN for Resolution-agnostic point cloud GEneration), the first fully $SE(3)$-equivariant graph-based diffusion backbone explicitly designed to generate point clouds while preserving continuous spatial symmetries. Our framework bypasses the rigid resolution dependencies of standard generative pipelines, enabling zero-shot inference at multiple, arbitrary spatial resolutions. Extensive empirical evaluations demonstrate that EMERGE achieves State-of-the-Art generation quality across standard metrics, while the strong inherent geometric inductive biases enable significantly faster training convergence compared to existing baseline methods.
### Title:
          Optimizing Denoising Trajectories in dLLMs: A Lightweight Evolutionary Heuristic Approach
 - **Authors:** Zijian Zhao, Dian Jin, Xialiang Tong, Sen Li, Mingxuan Yuan
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Diffusion Large Language Models (dLLMs) have recently emerged as a promising alternative to conventional Auto-Regressive (AR) Large Language Models (LLMs). By leveraging bidirectional attention and parallel decoding, dLLMs enable more efficient generation. However, they require a carefully designed denoising scheduler at inference time (absent during training) whose choice significantly impacts generation quality. While confidence-based heuristic schedulers have shown strong empirical performance, they suffer from two critical failure modes: EOS Overflow and Proximal Bias. Through in-depth analysis of the Transformer's attention patterns, we reveal that these failures stem from certain positions assigning disproportionately high attention weights to invalid tokens (e.g., [MASK] and [EOS]), which produce misleading confidence signals. Building on this insight, empirical evidence shows that valid attention scores can provide complementary guidance to conventional confidence-based heuristics, yet no single metric consistently excels across all scenarios, implying that the optimal denoising trajectory is highly context-dependent. To address this problem, we propose a lightweight evolutionary heuristic scheduler optimized using the Covariance Matrix Adaptation Evolution Strategy (CMA-ES). Our scheduler dynamically integrates multiple heuristic features with a contextual mean-field embedding, while requiring only 393 trainable parameters. Evaluated on LLaDA and Dream across four reasoning and planning benchmarks, our method consistently outperforms strong baselines, including conventional heuristics, block auto-regressive methods, and recent State-Of-The-Art (SOTA) approaches. To the best of our knowledge, it represents the most parameter-efficient neural scheduler to date. Our code is available at this https URL .
### Title:
          BDSLI: A hybrid CNN-Transformer model for Bengali Sign Language interpretation
 - **Authors:** Abir Bin Yousuf, Muhammad Iqbal Hossain
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 This study introduces a novel hybrid CNN-Transformer architecture to address the limited progress in Bengali SLR, focusing on isolated sign word recognition and sentence generation. This specific model combination is new to Bengali SLR tasks. A custom video dataset was developed, featuring 62 distinct Bengali sign words (250 samples/class), along with a separate test dataset. The CNN-Transformer model demonstrated superior performance against all comparative and baseline models (e.g., CNN-LSTM, standalone TCN), achieving a 99.58% training accuracy (99.48% validation) and a 98.65% test accuracy. The trained model was subsequently deployed in a web application for real-world validation.
### Title:
          Match One, Learn with Graph: One-to-Graph Query Collaboration with Backward Sharing for Object Detection
 - **Authors:** Wenxiao Fan, Jingling Fu, Luohang Liu, Lichen Ma, Yu He, Zhiyang Yu, Weishan Bi, Junshi Huang, Yan Li, Gu Simiu, Kan Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 One-to-one (O2O) matching enables Detection Transformers (DETRs) to perform end-to-end set prediction by assigning each object to a single positive query. However, the strongest classification, center, scale, and overlap evidence for an object is often distributed across multiple queries. This mismatch leaves only the matched owner positively supervised for the object, while other evidence-bearing queries receive no box target for it. We term this query knowledge fragmentation. To exploit such complementary evidence without one-to-many supervision, we propose BS-O2G, a plug-in that builds a sparse prediction-aware graph from decoded features, boxes, and class distributions to organize query collaboration in feature and optimization spaces while preserving the original O2O matcher, positive labels, and objective. One-to-Graph (O2G) calibration propagates relative messages over this graph to consolidate query evidence in the forward pass, whereas Backward Sharing (BS) reuses its transposed detached adjacency to route gradients across persistent query basis vectors without changing the decoder input in the forward pass. Experiments across diverse DETR methods, backbones, COCO, and CrowdHuman show consistent gains and faster convergence with negligible parameter/FLOP growth and modest runtime overhead, supporting graph-based query collaboration as an alternative to expanding positive assignments.
### Title:
          Certified Mechanistic Interpretability: Lifting Single-Input Findings to Bounded Neighbourhoods
 - **Authors:** Zhen Zhang, Yanliang Huang, Peng Xie, Wenyuan Wu, Amr Alanwar
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Mechanistic interpretability reverse-engineers transformer circuits one input at a time, leaving observed mechanisms without guarantees over bounded input neighbourhoods. We address this gap with a framework based on constrained polynomial-zonotope (CPZ) propagation that lifts mechanistic-interpretability observations from a single input to certified statements over a bounded set of perturbations. Three internal-attention queries (top-$k$ stability, evidence mass, and attention entropy) are formulated as tractable programs over the simplex of attention weights, and CPZ propagation through transformer blocks is shown to preserve the softmax simplex and the LayerNorm zero-mean identity exactly. A recursive Jacobian zonotope construction extends the same certificates across layer depth by linearising the block stack at the input and avoids per-layer generator growth. We instantiate the framework on transformer attention; the resulting certificates offer a way to sharpen mechanistic statements that single-input inspection cannot resolve on its own, and to inform downstream decisions in regimes where empirical heuristics may be misleading.
### Title:
          Vorch-Human: Unified Multi-Task Human-Centric Generation via Long-Horizon Continuation
 - **Authors:** Yang Ding, Haoran Yu, Xin Ma, Yulei Lu, Menglin Han, Yaole Wang, Siqian Yang, Gang Yue, Kaihao Zhang, Yaohui Wang, Lin Ma
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Human-centric audio-visual generation spans several closely related tasks: animating a person from driving speech, jointly generating speech and video from a voice reference, and synthesizing a scene from paired appearance and voice references. Existing systems commonly solve these tasks with separate models, even though they share the same target modalities and differ mainly in which observations are provided as conditions. We present Vorch-Human, a unified human-centric generation framework built on a dual-stream audio-video diffusion transformer. Vorch-Human augments the conventional noisy audio/noisy video interface with clean condition-audio and condition-video token groups. Per-token task embeddings, temporal position types, condition masks, and a shared multimodal prompt encoder allow driving speech, timbre examples, first frames, and subject images to be expressed within one model. To supply the supervision required by this interface, we develop a two-level data pipeline. Level 1 analyzes each clip with speech recognition, vocal separation, face detection and tracking, active-speaker and synchronization models, audio/visual speaker clustering, and multimodal caption correction; it produces subject-indexed speech, appearance, and timbre annotations. Level 2 links the same person across clips from a common source video and mines identity- and outfit-consistent reference images after face, body, quality, pose, and vision-language verification. Finally, we adapt Vorch-Human to long-form audio-driven generation by training with clean latent prefixes and using the same frozen-prefix recurrence at inference. Each segment contributes only its newly generated suffix, reducing boundary discontinuity and long-horizon identity drift. Experiments on short and five-minute generation demonstrate strong identity preservation, audio-visual synchronization, and temporal stability.
### Title:
          Spectral Tail Interventions in Decoder-Only Language Models: Reasoning-Sensitive Weight Structure from Controlled Surgery
 - **Authors:** Ibne Farabi Shihab, Sanjida Akhter, Md Najmus Swaqeeb, Abu Sa-Adat Mohamed Moon-Im Al Ahsan, Anuj Sharma
 - **Subjects:** Subjects:
Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Weight-space structure often correlates with language-model behavior, but correlation alone does not establish computational involvement. We study concentrated upper spectral tails in decoder-only transformers through controlled interventions. At a fixed relative offset, we derive a finite-width conditional bound linking the inverse participation ratio of squared singular values to central pre-softmax logit kurtosis. We then define a pointwise query--key ($QK$) product-tail target and compare independent factor surgery with a product-targeted factorization that preserves native attention computation. Across three base checkpoints and five reasoning benchmarks, plus an instruction-tuned Phi checkpoint analyzed separately, the learned-tail edit is more damaging than the mean of five fixed spectrum-matched Haar controls in all 20 model--task cells. Eighteen paired contrasts remain significant after Holm correction, while two are directional but inconclusive. Product-targeted factors attain higher held-out tail-subspace fractions, providing an empirical bridge between product- and factor-level interventions. Component isolation identifies contributions from $QK$, value--output, and multilayer-perceptron blocks, although the theorem covers only $QK$. In separate studies, inverse participation precedes pooled accuracy transitions under a matched crossing rule, and residualized tail-aware low-rank adaptation (LoRA) reaches targets earlier than standard LoRA and PiSSA while final-score intervals overlap. Conclusions are restricted to the evaluated checkpoints, layers, tasks, interventions, and controls.
### Title:
          MGRL-RSCC: Multi-Granularity Reward Reinforcement Learning for Fine-Grained Remote Sensing Change Captioning
 - **Authors:** Futian Wang, Mengqi Wang, Xiao Wang, Wentao Wu, Haowen Wang, Zhicheng Zhao, Jin Tang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Remote Sensing Change Captioning (RSCC), which aims to generate accurate and detailed linguistic descriptions of ground object variations from bi-temporal remote sensing images, is a critical and challenging task in intelligent remote sensing interpretation. The mainstream autoregressive training paradigm faces severe exposure bias and train-test distribution mismatch, resulting in cumulative generation errors. They tend to produce conservative and template-fixed captions while ignoring subtle scene change details. To address these challenges, this paper proposes a novel multi-granularity reward reinforcement learning paradigm, termed MGRL-RSCC. Specifically, we first leverage a CNN and hierarchical self-attention module to extract and enhance visual features from bi-temporal remote sensing images. A Transformer decoder is then utilized to complete visual-to-linguistic translation. Different from existing methods, we design a dual-decoding strategy and a two-stage joint optimization scheme, which combines token-level supervised learning via greedy decoding and multi-granularity reward-driven self-critical reinforcement learning via sampling decoding. We further construct three complementary reward functions covering linguistic fluency, change state consistency, and structural-semantic relevance to comprehensively optimize caption quality and alleviate false and missing change descriptions. Extensive experiments on multiple public RSCC benchmark datasets demonstrate that the proposed MGRL-RSCC effectively mitigates exposure bias and conservative generation problems in traditional autoregressive methods. The source code and pre-trained models will be released on this https URL
### Title:
          Magnitude Profile Pruning: Calibration-Free Structured Attention Head Removal for Transformer Compression
 - **Authors:** Kasun Dewage, Marianna Pensky, Heranga K. Rathnasekara, Suranadi De Silva
 - **Subjects:** Subjects:
Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Structured pruning of attention heads provides a hardware-friendly way to compress Transformer language models. However, existing methods for measuring head-level importance require calibration data, gradient computation, or Hessian estimation. These requirements add extra overhead and make the methods depend on the data. Our work presents Magnitude Profile (MP) scoring, a training-free criterion for head importance that identifies dispensable heads through statistical outlier detection on weight row norms. Heads whose projection weights fall within the population bulk are pruned, while heads exhibiting outlier norms, which carry disproportionate representational capacity, are preserved. Our work further gives MP-G, a variant that handles Grouped Query Attention (GQA) by distributing shared key-value group scores across associated query heads. Across five models evaluated on WikiText-2 perplexity at 12.5%-50% head sparsity, MP-G achieves the best perplexity on OPT-6.7B at all sparsity levels (18.46 at 12.5%, 27.87 at 25%, 152.0 at 50%). MP-G also gives the best results on RoBERTa-large at 12.5% and 25% sparsity, with perplexity values of 7.27 and 10.28, outperforming calibration-dependent baselines including Wanda-Head, SparseGPT-Head, and Gradient-Head. It requires zero forward passes, calibration samples, or gradient computation. At 50% sparsity, head pruning yields up to 16% parameter reduction with 50% attention FLOP savings. Our results show that weight-only statistical scoring can match or outperform data-dependent methods for structured head pruning, providing a practical, zero-cost criterion for Transformer compression.
### Title:
          Can You Delete a Year of Market Data? Machine Unlearning Against Exact Retraining Oracles
 - **Authors:** Junyi Ye
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Statistical Finance (q-fin.ST)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 When a data license expires, deleting stored records does not remove influence encoded in a trained forecaster. Machine unlearning seeks to remove this influence without retraining. We benchmark temporal unlearning with 3,200 paired references trained on all data and oracles retrained without the requested period. The grid covers five architectures, four rolling folds, five deletable years, and three experimental deletion levels on an S&P 500 volatility panel. The 2020 COVID crisis year produces the largest memorization gap for every architecture. Removing it improves all three deployable models in every fold, with the largest improvement in the 2022 bear market, while the two non-deployable models respond inconsistently. The target for approximate unlearning is the oracle, not low predictive accuracy on the deleted period. In one Transformer cell, an oracle that never trained on 2020 still predicts it at an information coefficient of 0.51, compared with 0.55 for the reference; pushing predictions toward noise reduces test skill. Across twelve deployable architecture-method pairs, only TSMixer with the hinge method remains near the oracle in every fold, closing 74-118% of the reference-to-oracle gap without a measurable loss of test skill. Method rankings vary across architectures and rolling windows. Audit separation rises with prior memorization but can remain small after exact deletion. The window-level loss comparison reaches at most 0.69, and treating stock-level windows as independent inflates the absolute t-statistic by a median factor of 1.9. These results call for an explicit deletion scope, oracle validation for the relevant architecture and window, and power-aware auditing.
### Title:
          Rethinking Pairwise Token Interaction in Spiking Transformers
 - **Authors:** Sicheng Shen, Dongcheng Zhao, Zhiyuan Li, Jinyan Yu, Qian Zhang, Dengpeng Xing, Zhitong Zhang, Tielin Zhang
 - **Subjects:** Subjects:
Neural and Evolutionary Computing (cs.NE)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Spiking Transformers inherit token interaction mechanisms from conventional Transformers, yet their sparse binary representations fundamentally alter how token-to-token communication is established. In particular, spike-based query-key matching produces highly sparse and input-dependent interaction patterns, coupling information propagation to the instantaneous availability of matching spike events. This motivates a different interaction paradigm in which long-range communication does not rely solely on pairwise spike coincidence. We therefore propose Gated Spike Axial Propagation (GSAP), a spike-native token interaction mechanism that decouples information propagation from context selection. Instead of directly determining communication through query-key matching, GSAP first propagates spike-based context along the horizontal and vertical axes, allowing information to reach distant tokens through structured sequential propagation. A receiver-conditioned gate then determines how much of the propagated context is incorporated at each token, while a lightweight local pathway preserves fine-grained neighborhood information. In this way, GSAP reformulates token interaction as a propagate-then-select process, enabling structured long-range communication while retaining the sparse event-driven nature of spiking representations. Code is available at this https URL.
### Title:
          ForeDrive: Foresight-Guided End-to-End Autonomous Driving with a Planning-Relevant Latent World Model
 - **Authors:** Sinuo Wang, Zichong Gu, Yuhan Huang, Wenxin Wen, Xun Yang, Yiqing Zhang, Xingyu Zhang, Ningyu Che, Jie Ling, Qiankun Yu, Wei Liu, Jing Xu, Xinggang Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing latent world models are typically optimized for future predictability, yet the resulting representations are not necessarily useful for planning in autonomous driving. Predictions are commonly used for pretraining or auxiliary supervision rather than as direct conditioning signals for trajectory generation. We propose ForeDrive, which learns a planning-relevant latent representation and couples it asymmetrically to a Diffusion Transformer (DiT) planner. The planner consumes multi-horizon latent future representations learned with a JEPA-style world model; planning gradients update the shared online encoder, while stop-gradient routing trains the latent predictor with forecasting losses only. Because predicted futures have varying reliability across horizons and BEV trajectories are misaligned with image tokens, we use gated visual fusion, future-status injection, and Trajectory-Adaptive Bias (TAB) to inject future latents as guidance without overriding the current observation. Trained with pure imitation learning and using only the current front-view image as visual input at inference, ForeDrive attains 89.9 PDMS on NAVSIM v1 and 90.0 one-stage EPDMS on NAVSIM v2, without reinforcement learning or an external trajectory scorer.
### Title:
          Leveraging Vision-Based Point Cloud Map Priors for Camera-Based 3D Object Detection and Online Vectorized HD Mapping
 - **Authors:** Markus Käppeler, Rohit Mohan, Abhinav Valada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Camera-based 3D object detection and online vectorized HD mapping provide compact scene representations for autonomous driving, but both depend on accurate metric geometry and remain limited by depth ambiguity. Over long-term deployment, observations from repeated traversals can be accumulated into persistent point cloud priors that provide geometric context beyond the current observations. Existing explicit point cloud prior approaches, however, rely on LiDAR-based map construction and therefore require expensive 3D ranging sensors. We propose a framework that constructs a static point cloud prior map from previous camera traversals using Pi3X and augments each point with DINOv3 features. At runtime, a local prior patch is retrieved using global localization, encoded with a sparse voxel backbone, and fused in bird's-eye view (BEV) with lifted multi-view camera features. Task-specific sparse transformer heads then predict 3D objects and vectorized map elements from the fused representation. On Argoverse 2, the vision-based prior improves a strong baseline from 0.287 to 0.299 CDS and from 0.669 to 0.750 vectorized mapping mAP. Ablations show that semantic DINOv3 features are particularly important for vectorized mapping. These results demonstrate that vision-built geometric-semantic priors provide an effective form of long-term scene memory for camera-based perception, improving both tasks without LiDAR for prior-map construction or online inference.
### Title:
          KwaiMind Technical Report
 - **Authors:** Junlong Wu, Zijun Li, Yuting Hu, Jia Sun, Pengcheng Wei, Yimin Zhou, Honglie Wang, Huaiqing Wang, Dewen Fan, Fei Zuo, Haixuan Gao, Lihui Peng, Tingxuan She, Yuqing Li, Boheng Zhang, Fan Yang, Wenwu Ou
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Commercial image editing requires product identity preservation, accurate text rendering, and user appeal alongside general editing quality. We present KwaiMind, an image editing system combining general capabilities with e-commerce specialization. An agent-based data engine maintains approximately 1.8 million high-quality editing pairs. Built on a multimodal diffusion transformer, KwaiMind undergoes continued pre-training and supervised fine-tuning, followed by preference optimization and online reinforcement learning. A general-purpose vision-language judge and specialized rewards for click-through rate (CTR), text rendering, and product consistency guide specialized policies, which are consolidated through on-policy distillation. We introduce Ecom-Bench, covering 11 commercial editing tasks with task-specific visual evaluation and CTR-based ranking. KwaiMind achieves the strongest overall scores among evaluated open-source editors on ImgEdit, GEdit, both language splits of REDEdit, and Ecom-Bench visual quality, and the highest aggregate CTR ranking score among compared systems. Offline, CTR-guided optimization increases the proportion of generated images whose predicted CTR exceeds that of the original product image from 12.16% to 37.41%. In an online A/B experiment, CTR-based selection of product main images yields an approximately 2.44% relative increase in actual CTR. These results demonstrate the value of domain-specific data and reward-driven alignment for commercial image editing.
### Title:
          Do Vision Model See Like the Brain? A Comparison Across EEG Encoding Model
 - **Authors:** Shashank Baghel, Kshitij Dwivedi, Dinesh Singh, Sanjeev Nara
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Human-Computer Interaction (cs.HC)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Convolutional neural networks (CNNs) and vision transformers are both used to model the human visual system, but whether the two architectures diverge at a specific point in network depth is unclear. We compared six CNNs and two vision transformers by computing the Pearson correlation (r) between each model's predicted and measured EEG response at every layer or block, in ten participants viewing 200 natural images. For the transformer models, we also tested four token representations, from the classification (CLS) token alone to CLS combined with all patch tokens. CNNs showed strongest correspondence at the earliest layers, weakening at deeper layers, particularly later in the post-stimulus response. Transformers instead sustained strong correspondence at their deepest blocks, though not at their earliest ones. This advantage depended on token representation: pooled representations gave weaker peak correlations (r approx 0.48-0.51) than representations retaining all patch tokens (r=0.640 for CLIP-ViT-B/32, r=0.656 for DINOv2-ViT-B/14). Controlled comparisons showed architecture, not training objective, drove this effect: MoCo-v1 and ResNet-50 (matched architecture) performed nearly identically (r=0.673, 0.670), whereas CLIP-RN50 and CLIP-ViT-B/32 (matched objective) diverged until patch tokens were preserved. We propose that CNN training's classification bottleneck compresses brain-relevant information at depth, unlike transformers' self-attention and non-classification objectives. A spatial topography analysis showed a common occipital-dominant pattern across all models, indicating these differences reflect signal strength and persistence rather than distinct brain regions. Patch-preserving transformer representations sustain brain-predictive correspondence where CNNs collapse.
### Title:
          Virtual Encoders in Multimodal Transformers
 - **Authors:** Katsuya Ogata, Yuta Nakashima
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Multimodal language models traditionally rely on dedicated perceptual encoders to construct task-usable representations. More integrated architectures have recently emerged, which instead expose the shared transformer to lightly projected patches, audio frames, or discrete visual tokens. Where does this encoding happen when such representations are not provided? We find that the transformer can internalize this missing computation, constructing task-usable perceptual representations within its own early-to-middle layers before the downstream language model. We call this computational structure a Virtual Encoder. Across linear probing, similarities to perceptual encoders, and causal analyses, we identify signatures of this structure in models that receive perceptual tokens without continuous encoder-derived features. These analyses also suggest that the boundary between perception and language processing need not coincide within an architectural module. Instead, encoder-like computation can emerge as a functional regime within a shared transformer, providing a new perspective for understanding where and how multimodal models process perception.
### Title:
          MambaVoice: Lightweight Audiovisual Singing Voice Separation Via A Hybrid Mamba-Transformer Model
 - **Authors:** Adithi Shankar, Gopika Krishnan, Gloria Haro, Xavier Serra, Martín Rocamora
 - **Subjects:** Subjects:
Sound (cs.SD)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Isolating a target singing voice from a music video remains challenging, particularly in the presence of multiple vocalists and dense instrumental accompaniment. We propose MambaVoice, a lightweight audiovisual framework that leverages a hybrid Mamba--Transformer architecture for targeted singing voice separation. The model jointly encodes audio and visual streams using an attention-based band-split audio encoder and a spatio-temporal graph convolutional network (ST-GCN) for facial motion features. These modalities are fused through a multiplicative gating mechanism, enabling visual cues to selectively modulate audio representations. The fused features are processed by a hybrid backbone that combines Transformer self-attention with Selective State Space Models (SSMs), achieving efficient long-range temporal modeling with linear complexity. We evaluated MambaVoice on the Acappella and URSing datasets under challenging conditions, including mixtures with interfering singers. At 16.2 million parameters, the model demonstrates comparable performance, achieving 14.18 dB SDR on Acappella and strong cross-dataset performance on URSing, comparable to larger models at a fraction of the parameter count. These findings highlight the effectiveness of hybrid SSM--attention architectures for scalable, efficient audiovisual source separation, suggesting they are well-suited as lightweight components within larger pipelines. We conduct a perceptual study that further supports our improvements in objective metrics. We provide our implementation online.
### Title:
          A Spectral Theory of Grokking: Weight Decay induces Feature Learning
 - **Authors:** Lenz Pracher, Pascal de Jong, Oskar Lieshaus, Alan Jeffares, Steffen Rulands
 - **Subjects:** Subjects:
Machine Learning (cs.LG); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 In grokking an early fit to the training data separates from a much later improvement in generalization. During this delay, training can move from a fixed neural tangent kernel (NTK) regime to one in which task-relevant kernel eigendirections continue to evolve. We provide a quantitative theory for how this transition from lazy to rich learning can produce delayed generalization. For homogeneous networks trained with squared loss and $L_2$ weight decay, we show that a finite residual remains after memorization, with larger residual fractions in target components associated with smaller NTK eigenvalues. These residuals feed back into the dynamics of the NTK itself, and projecting the resulting dynamics onto task-relevant spectral directions yields a reduced system in which residual-driven kernel growth competes with weight decay. This system predicts that the grokking timescale is controlled by the product of learning rate and weight decay, that feature learning slows logarithmically near a critical decay above which task-aligned NTK structure can no longer support generalization, and that stronger decay can prevent fitting altogether. We test these predictions in modular addition. In a homogeneous MLP, task-aligned Fourier structure continues to emerge in the NTK after training accuracy has saturated, and an 84$\times$90-grid of trained networks across varying learning rate and weight decay recovers the predicted phase geometry and inverse-product scaling of the generalization time with learning rate and weight decay. A one-block Transformer shows similar macroscopic phase structure in a 42$\times$45-grid, as well as the same transition-time scaling despite violating exact homogeneity. Together, these results provide a mechanistic derivation connecting post-fit feature learning to both the onset of generalization and its phase structure in the learning rate and weight decay plane.
## Keyword: autonomous driving
### Title:
          Sometimes You Gotta Run Before You Can Walk: Run-then-Walk Scheduling Strategy for VLM Autonomous Driving
 - **Authors:** Yuqi Ye, Shangkun Sun, Junhong Lin, Jiayi Zhao, Changhao Peng, Wei Zheng, Guoqing Liu, Tiesong Zhao, Wei Gao
 - **Subjects:** Subjects:
Robotics (cs.RO); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Recent VLM-based autonomous driving planners adopt GRPO-style reinforcement learning to optimize driving performance. However, existing GRPO recipes either optimize driving efficiency, risking progress-seeking but unsafe behavior, or enforce early safety constraints, leading to overly conservative behavior; both require lengthy training. To solve these problems, we first reveal two distinct RL regimes: a progress regime (Run-GRPO) that aggressively explores high progress, and a safety regime (Walk-GRPO) that restores safety under stable progress. Based on this finding, we propose $\textit{Run-then-Walk}$, a simple yet effective two-stage reward scheduling strategy for GRPO, achieving both better performance and faster convergence. Unlike one-stage RL, which may focus on progress, safety, or a mixture of both within a single training phase, this schedule explicitly separates progress discovery from safety repair. In the $\textit{Run}$ phase, we focus on progress, allowing the policy to escape the conservative bias and discover high-progress modes. In the subsequent $\textit{Walk}$ phase, we introduce endpoint and safety strategy to repair unsafe behaviors from the Run phase. This reversed schedule overcomes the conservatism of Walk-first methods and the unsafe progress-seeking of joint optimization. We validate it with various VLM-based planners on multiple benchmarks: NAVSIMv1, NAVSIMv2, Navhard, and nuScenes. Extensive experiments demonstrate improved driving performance while requiring 40--50\% fewer RL training epochs than the baselines.
### Title:
          MatchFusion: Explicit-Implicit Instance Matching for Spatio-Temporal Multimodal Autonomous Driving
 - **Authors:** Xiaoyu Li, Jiajia Fu, Long Shi, Tianyu Du, Ruihang Li, Xian Wu, Lijun Zhao, Yingtao Zhang, Lining Sun, Ruifeng Li
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Sparse instance representations provide a compact interface for spatial LiDAR-camera and temporal past-current interaction in multimodal perception and E2EAD. Effective interaction requires reliable instance correspondences despite geometric discrepancies and heterogeneous semantic representations. Attention-based methods exploit contextual semantics but often require specialized representation alignment, increasing computational overhead. In contrast, association based on structured object states is efficient and interpretable but lacks contextual evidence to resolve ambiguous matches. To combine these complementary strengths, we propose MatchFusion, a learnable instance matching and fusion module for spatio-temporal multimodal autonomous driving. MatchFusion initializes pairwise affinities using geometric similarity and category consistency, then selectively refines structurally plausible associations using instance embeddings. The resulting soft matchmap guides a common residual aggregation operator for adaptive information exchange. This unified matching-fusion formulation supports spatial LiDAR-camera and temporal past-current interaction, using multi-view image-plane geometry and motion-compensated BEV geometry as the respective structural priors. Experiments on nuScenes demonstrate consistent perception gains across diverse front-end configurations. Compared with a prior instance-centric fusion method, the MatchFusion-equipped system achieves higher perception accuracy while reducing FLOPs by 55.3% and GPU memory usage by 39.3%, with the matching-fusion module accounting for only 3.7% of total perception latency. Integrating temporal MatchFusion into SparseDrive further improves perception within an E2E framework without additional supervision. These results establish explicit-implicit matching as an effective and efficient mechanism for spatio-temporal instance interaction.
### Title:
          End-to-End Visual Odometry with RNNs and Attention
 - **Authors:** Ruiyu Li, Yinjia Liu, Alexander Yu
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Video Odometry (VO) is the process of estimating the ego-motion of an object by analyzing visual information such as a sequence of frames from one or multiple cameras. It has been a popular research topic in computer vision and robotics, and its applications include mobile robotic systems as well as autonomous driving. In this project, we investigate existing end-to-end deep-learning approaches to VO, and propose a novel temporal attention-based model to improve upon the baseline. In addition, while the vast majority of existing deep-learning-based approaches to VO are trained on driving data, we investigate the performance of deep-learning-based VO to the more dynamic and complex problem of hand-held cameras.
### Title:
          ForeDrive: Foresight-Guided End-to-End Autonomous Driving with a Planning-Relevant Latent World Model
 - **Authors:** Sinuo Wang, Zichong Gu, Yuhan Huang, Wenxin Wen, Xun Yang, Yiqing Zhang, Xingyu Zhang, Ningyu Che, Jie Ling, Qiankun Yu, Wei Liu, Jing Xu, Xinggang Wang
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Existing latent world models are typically optimized for future predictability, yet the resulting representations are not necessarily useful for planning in autonomous driving. Predictions are commonly used for pretraining or auxiliary supervision rather than as direct conditioning signals for trajectory generation. We propose ForeDrive, which learns a planning-relevant latent representation and couples it asymmetrically to a Diffusion Transformer (DiT) planner. The planner consumes multi-horizon latent future representations learned with a JEPA-style world model; planning gradients update the shared online encoder, while stop-gradient routing trains the latent predictor with forecasting losses only. Because predicted futures have varying reliability across horizons and BEV trajectories are misaligned with image tokens, we use gated visual fusion, future-status injection, and Trajectory-Adaptive Bias (TAB) to inject future latents as guidance without overriding the current observation. Trained with pure imitation learning and using only the current front-view image as visual input at inference, ForeDrive attains 89.9 PDMS on NAVSIM v1 and 90.0 one-stage EPDMS on NAVSIM v2, without reinforcement learning or an external trajectory scorer.
### Title:
          Leveraging Vision-Based Point Cloud Map Priors for Camera-Based 3D Object Detection and Online Vectorized HD Mapping
 - **Authors:** Markus Käppeler, Rohit Mohan, Abhinav Valada
 - **Subjects:** Subjects:
Computer Vision and Pattern Recognition (cs.CV); Robotics (cs.RO)
 - **Arxiv link:** https://arxiv.org/abs/
 - **Pdf link:** https://arxiv.org/pdf/
 - **Abstract**
 Camera-based 3D object detection and online vectorized HD mapping provide compact scene representations for autonomous driving, but both depend on accurate metric geometry and remain limited by depth ambiguity. Over long-term deployment, observations from repeated traversals can be accumulated into persistent point cloud priors that provide geometric context beyond the current observations. Existing explicit point cloud prior approaches, however, rely on LiDAR-based map construction and therefore require expensive 3D ranging sensors. We propose a framework that constructs a static point cloud prior map from previous camera traversals using Pi3X and augments each point with DINOv3 features. At runtime, a local prior patch is retrieved using global localization, encoded with a sparse voxel backbone, and fused in bird's-eye view (BEV) with lifted multi-view camera features. Task-specific sparse transformer heads then predict 3D objects and vectorized map elements from the fused representation. On Argoverse 2, the vision-based prior improves a strong baseline from 0.287 to 0.299 CDS and from 0.669 to 0.750 vectorized mapping mAP. Ablations show that semantic DINOv3 features are particularly important for vectorized mapping. These results demonstrate that vision-built geometric-semantic priors provide an effective form of long-term scene memory for camera-based perception, improving both tasks without LiDAR for prior-map construction or online inference.
